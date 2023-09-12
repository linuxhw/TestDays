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

Total: 63

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Gigabyte | GA-78LMT-USB3 x.x    | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Dell     | 0WR7PY A01           | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| HP       | 21EF                 | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| ASRock   | H97M Pro4            | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Dell     | 0F6X5P A00           | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| ASRock   | B450M-HDV R4.0       | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
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
| Ubuntu 18.04                 | 10       | 20.83%  |
| Ubuntu 20.04                 | 5        | 10.42%  |
| Arch Rolling                 | 5        | 10.42%  |
| OpenMandriva 23.03           | 4        | 8.33%   |
| OpenMandriva 4.2             | 3        | 6.25%   |
| Ubuntu 22.04                 | 2        | 4.17%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 4.17%   |
| OpenMandriva 4.3             | 2        | 4.17%   |
| Fedora 34                    | 2        | 4.17%   |
| Ubuntu 22.10                 | 1        | 2.08%   |
| Ubuntu 19.10                 | 1        | 2.08%   |
| ROSA R10                     | 1        | 2.08%   |
| Pop!_OS 22.04                | 1        | 2.08%   |
| OpenMandriva 4.90            | 1        | 2.08%   |
| Manjaro 21.2.3               | 1        | 2.08%   |
| Linux Mint 20.3              | 1        | 2.08%   |
| Linux Mint 19.3              | 1        | 2.08%   |
| Fedora 37                    | 1        | 2.08%   |
| Fedora 33                    | 1        | 2.08%   |
| CentOS 8                     | 1        | 2.08%   |
| BlackPanther 18.1            | 1        | 2.08%   |
| Arch                         | 1        | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 18       | 40%     |
| OpenMandriva | 9        | 20%     |
| Arch         | 6        | 13.33%  |
| Fedora       | 3        | 6.67%   |
| openSUSE     | 2        | 4.44%   |
| Linux Mint   | 2        | 4.44%   |
| ROSA         | 1        | 2.22%   |
| Pop!_OS      | 1        | 2.22%   |
| Manjaro      | 1        | 2.22%   |
| CentOS       | 1        | 2.22%   |
| BlackPanther | 1        | 2.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 6.2.6-desktop-1omv2390          | 3        | 5.56%   |
| 5.10.14-desktop-1omv4002        | 3        | 5.56%   |
| 5.16.7-desktop-1omv4003         | 2        | 3.7%    |
| 6.3.7-arch1-1                   | 1        | 1.85%   |
| 6.1.18-200.fc37.x86_64          | 1        | 1.85%   |
| 6.1.1-desktop-1omv2290          | 1        | 1.85%   |
| 5.9.16-200.fc33.x86_64          | 1        | 1.85%   |
| 5.8.5-arch1-1                   | 1        | 1.85%   |
| 5.7.7-zen1-1-zen                | 1        | 1.85%   |
| 5.7.7-arch1-1                   | 1        | 1.85%   |
| 5.4.0-42-generic                | 1        | 1.85%   |
| 5.4.0-37-generic                | 1        | 1.85%   |
| 5.4.0-125-generic               | 1        | 1.85%   |
| 5.4.0-110-generic               | 1        | 1.85%   |
| 5.4.0-107-generic               | 1        | 1.85%   |
| 5.3.0-46-generic                | 1        | 1.85%   |
| 5.3.0-42-generic                | 1        | 1.85%   |
| 5.3.0-40-generic                | 1        | 1.85%   |
| 5.19.0-32-generic               | 1        | 1.85%   |
| 5.19.0-23-generic               | 1        | 1.85%   |
| 5.18.12-desktop-3omv4090        | 1        | 1.85%   |
| 5.18.10-76051810-generic        | 1        | 1.85%   |
| 5.17.6-xanmod1                  | 1        | 1.85%   |
| 5.15.21-1-MANJARO               | 1        | 1.85%   |
| 5.15.0-53-generic               | 1        | 1.85%   |
| 5.14.13-200.fc34.x86_64         | 1        | 1.85%   |
| 5.13.0-40-generic               | 1        | 1.85%   |
| 5.13.0-27-generic               | 1        | 1.85%   |
| 5.12.15-arch1-1                 | 1        | 1.85%   |
| 5.12.12-300.fc34.x86_64         | 1        | 1.85%   |
| 5.11.0-40-generic               | 1        | 1.85%   |
| 5.11.0-25-generic               | 1        | 1.85%   |
| 5.1.6-050106-generic            | 1        | 1.85%   |
| 5.1.2-zen1-1-zen                | 1        | 1.85%   |
| 5.0.0-32-generic                | 1        | 1.85%   |
| 5.0.0-25-generic                | 1        | 1.85%   |
| 4.9.87-nrj-desktop-2rosa-x86_64 | 1        | 1.85%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 1        | 1.85%   |
| 4.18.16-desktop-1bP             | 1        | 1.85%   |
| 4.18.15-1-default               | 1        | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 5        | 10%     |
| 5.4.0   | 4        | 8%      |
| 6.2.6   | 3        | 6%      |
| 5.3.0   | 3        | 6%      |
| 5.10.14 | 3        | 6%      |
| 5.7.7   | 2        | 4%      |
| 5.19.0  | 2        | 4%      |
| 5.16.7  | 2        | 4%      |
| 5.13.0  | 2        | 4%      |
| 5.11.0  | 2        | 4%      |
| 5.0.0   | 2        | 4%      |
| 6.3.7   | 1        | 2%      |
| 6.1.18  | 1        | 2%      |
| 6.1.1   | 1        | 2%      |
| 5.9.16  | 1        | 2%      |
| 5.8.5   | 1        | 2%      |
| 5.18.12 | 1        | 2%      |
| 5.18.10 | 1        | 2%      |
| 5.17.6  | 1        | 2%      |
| 5.15.21 | 1        | 2%      |
| 5.15.0  | 1        | 2%      |
| 5.14.13 | 1        | 2%      |
| 5.12.15 | 1        | 2%      |
| 5.12.12 | 1        | 2%      |
| 5.1.6   | 1        | 2%      |
| 5.1.2   | 1        | 2%      |
| 4.9.87  | 1        | 2%      |
| 4.9.60  | 1        | 2%      |
| 4.18.16 | 1        | 2%      |
| 4.18.15 | 1        | 2%      |
| 4.18.0  | 1        | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 5        | 10.2%   |
| 5.4     | 4        | 8.16%   |
| 6.2     | 3        | 6.12%   |
| 5.3     | 3        | 6.12%   |
| 5.10    | 3        | 6.12%   |
| 4.18    | 3        | 6.12%   |
| 6.1     | 2        | 4.08%   |
| 5.7     | 2        | 4.08%   |
| 5.19    | 2        | 4.08%   |
| 5.18    | 2        | 4.08%   |
| 5.16    | 2        | 4.08%   |
| 5.15    | 2        | 4.08%   |
| 5.13    | 2        | 4.08%   |
| 5.12    | 2        | 4.08%   |
| 5.11    | 2        | 4.08%   |
| 5.1     | 2        | 4.08%   |
| 5.0     | 2        | 4.08%   |
| 6.3     | 1        | 2.04%   |
| 5.9     | 1        | 2.04%   |
| 5.8     | 1        | 2.04%   |
| 5.17    | 1        | 2.04%   |
| 5.14    | 1        | 2.04%   |
| 4.9     | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 44       | 97.78%  |
| i686   | 1        | 2.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 22       | 48.89%  |
| KDE5       | 12       | 26.67%  |
| Unknown    | 4        | 8.89%   |
| XFCE       | 2        | 4.44%   |
| X-Cinnamon | 2        | 4.44%   |
| LXQt       | 1        | 2.22%   |
| KDE4       | 1        | 2.22%   |
| KDE        | 1        | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 38       | 84.44%  |
| Wayland | 4        | 8.89%   |
| Tty     | 2        | 4.44%   |
| Unknown | 1        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 42.22%  |
| SDDM    | 15       | 33.33%  |
| GDM     | 5        | 11.11%  |
| GDM3    | 4        | 8.89%   |
| LightDM | 1        | 2.22%   |
| KDM     | 1        | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 19       | 41.3%   |
| es_DO   | 17       | 36.96%  |
| Unknown | 7        | 15.22%  |
| es_ES   | 2        | 4.35%   |
| es_US   | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 66.67%  |
| EFI  | 15       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 29       | 63.04%  |
| Overlay | 8        | 17.39%  |
| Btrfs   | 6        | 13.04%  |
| Xfs     | 2        | 4.35%   |
| Unknown | 1        | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 45.83%  |
| GPT     | 18       | 37.5%   |
| MBR     | 8        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 73.91%  |
| Yes       | 12       | 26.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 57.45%  |
| Yes       | 20       | 42.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 16       | 35.56%  |
| Gigabyte Technology | 11       | 24.44%  |
| Hewlett-Packard     | 7        | 15.56%  |
| ASRock              | 3        | 6.67%   |
| MSI                 | 2        | 4.44%   |
| ASUSTek Computer    | 2        | 4.44%   |
| Unknown             | 2        | 4.44%   |
| Foxconn             | 1        | 2.22%   |
| Biostar             | 1        | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte GA-78LMT-USB3 6.0         | 3        | 6.67%   |
| Dell OptiPlex 990                  | 2        | 4.44%   |
| Dell OptiPlex 3010                 | 2        | 4.44%   |
| Unknown                            | 2        | 4.44%   |
| MSI MS-7A34                        | 1        | 2.22%   |
| MSI MS-7817                        | 1        | 2.22%   |
| HP t520 Flexible Series TC         | 1        | 2.22%   |
| HP EliteDesk 800 G1 USDT           | 1        | 2.22%   |
| HP EliteDesk 705 G3 SFF            | 1        | 2.22%   |
| HP Compaq Elite 8300 SFF           | 1        | 2.22%   |
| HP Compaq Elite 8300 CMT           | 1        | 2.22%   |
| HP Compaq dc7900 Small Form Factor | 1        | 2.22%   |
| HP Compaq 8000 Elite CMT PC        | 1        | 2.22%   |
| Gigabyte Z87X-UD5 TH               | 1        | 2.22%   |
| Gigabyte Z170X-Gaming 7            | 1        | 2.22%   |
| Gigabyte GA-78LMT-USB3 R2          | 1        | 2.22%   |
| Gigabyte GA-78LMT-S2P              | 1        | 2.22%   |
| Gigabyte B450M DS3H V2             | 1        | 2.22%   |
| Gigabyte B450M DS3H                | 1        | 2.22%   |
| Gigabyte B450 AORUS M              | 1        | 2.22%   |
| Gigabyte A520I AC                  | 1        | 2.22%   |
| Foxconn p6-2040fr                  | 1        | 2.22%   |
| Dell Precision WorkStation T5500   | 1        | 2.22%   |
| Dell PowerEdge T40                 | 1        | 2.22%   |
| Dell OptiPlex 9020                 | 1        | 2.22%   |
| Dell OptiPlex 780                  | 1        | 2.22%   |
| Dell OptiPlex 755                  | 1        | 2.22%   |
| Dell OptiPlex 745                  | 1        | 2.22%   |
| Dell OptiPlex 7010                 | 1        | 2.22%   |
| Dell OptiPlex 390                  | 1        | 2.22%   |
| Dell OptiPlex 3050                 | 1        | 2.22%   |
| Dell OptiPlex 3020                 | 1        | 2.22%   |
| Dell OptiPlex 160                  | 1        | 2.22%   |
| Dell DM061                         | 1        | 2.22%   |
| Biostar G41D3C                     | 1        | 2.22%   |
| ASUS H170 PRO GAMING               | 1        | 2.22%   |
| ASUS H110M-E/M.2                   | 1        | 2.22%   |
| ASRock H97M Pro4                   | 1        | 2.22%   |
| ASRock G41M-VS3                    | 1        | 2.22%   |
| ASRock B450M-HDV R4.0              | 1        | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 13       | 28.89%  |
| HP Compaq              | 4        | 8.89%   |
| Gigabyte GA-78LMT-USB3 | 4        | 8.89%   |
| HP EliteDesk           | 2        | 4.44%   |
| Gigabyte B450M         | 2        | 4.44%   |
| Unknown                | 2        | 4.44%   |
| MSI MS-7A34            | 1        | 2.22%   |
| MSI MS-7817            | 1        | 2.22%   |
| HP t520                | 1        | 2.22%   |
| Gigabyte Z87X-UD5      | 1        | 2.22%   |
| Gigabyte Z170X-Gaming  | 1        | 2.22%   |
| Gigabyte GA-78LMT-S2P  | 1        | 2.22%   |
| Gigabyte B450          | 1        | 2.22%   |
| Gigabyte A520I         | 1        | 2.22%   |
| Foxconn p6-2040fr      | 1        | 2.22%   |
| Dell Precision         | 1        | 2.22%   |
| Dell PowerEdge         | 1        | 2.22%   |
| Dell DM061             | 1        | 2.22%   |
| Biostar G41D3C         | 1        | 2.22%   |
| ASUS H170              | 1        | 2.22%   |
| ASUS H110M-E           | 1        | 2.22%   |
| ASRock H97M            | 1        | 2.22%   |
| ASRock G41M-VS3        | 1        | 2.22%   |
| ASRock B450M-HDV       | 1        | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 6        | 13.33%  |
| 2011 | 6        | 13.33%  |
| 2013 | 5        | 11.11%  |
| 2017 | 4        | 8.89%   |
| 2015 | 4        | 8.89%   |
| 2018 | 3        | 6.67%   |
| 2012 | 3        | 6.67%   |
| 2016 | 2        | 4.44%   |
| 2010 | 2        | 4.44%   |
| 2009 | 2        | 4.44%   |
| 2008 | 2        | 4.44%   |
| 2007 | 2        | 4.44%   |
| 2021 | 1        | 2.22%   |
| 2020 | 1        | 2.22%   |
| 2019 | 1        | 2.22%   |
| 2006 | 1        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 45       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 44       | 97.78%  |
| Enabled  | 1        | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 11       | 24.44%  |
| 3.01-4.0    | 9        | 20%     |
| 16.01-24.0  | 9        | 20%     |
| 4.01-8.0    | 8        | 17.78%  |
| 24.01-32.0  | 2        | 4.44%   |
| 0.51-1.0    | 2        | 4.44%   |
| 32.01-64.0  | 1        | 2.22%   |
| 2.01-3.0    | 1        | 2.22%   |
| 64.01-256.0 | 1        | 2.22%   |
| 1.01-2.0    | 1        | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 20       | 43.48%  |
| 2.01-3.0  | 12       | 26.09%  |
| 3.01-4.0  | 6        | 13.04%  |
| 0.51-1.0  | 4        | 8.7%    |
| 4.01-8.0  | 3        | 6.52%   |
| 8.01-16.0 | 1        | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 55.32%  |
| 2      | 10       | 21.28%  |
| 3      | 7        | 14.89%  |
| 4      | 4        | 8.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 53.33%  |
| Yes       | 21       | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 44       | 97.78%  |
| No        | 1        | 2.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 50%     |
| No        | 23       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 75.56%  |
| Yes       | 11       | 24.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Dominican Republic | 45       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Santo Domingo Este         | 25       | 52.08%  |
| Santiago de los Caballeros | 5        | 10.42%  |
| Santo Domingo              | 4        | 8.33%   |
| San Pedro de Macorís      | 2        | 4.17%   |
| San Juan                   | 2        | 4.17%   |
| San Cristobal              | 2        | 4.17%   |
| Nacional                   | 2        | 4.17%   |
| Sosua, Cabarete            | 1        | 2.08%   |
| San Francisco de Macorís  | 1        | 2.08%   |
| Moca                       | 1        | 2.08%   |
| La Romana                  | 1        | 2.08%   |
| Constanza                  | 1        | 2.08%   |
| Alejandro Bass             | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 31     | 31.94%  |
| Samsung Electronics | 9        | 13     | 12.5%   |
| WDC                 | 7        | 9      | 9.72%   |
| Toshiba             | 7        | 10     | 9.72%   |
| Kingston            | 7        | 8      | 9.72%   |
| Hitachi             | 6        | 8      | 8.33%   |
| SanDisk             | 2        | 3      | 2.78%   |
| Intel               | 2        | 2      | 2.78%   |
| Crucial             | 2        | 3      | 2.78%   |
| Unknown             | 1        | 1      | 1.39%   |
| SPCC                | 1        | 1      | 1.39%   |
| Phison Electronics  | 1        | 1      | 1.39%   |
| Patriot             | 1        | 1      | 1.39%   |
| Maxtor              | 1        | 1      | 1.39%   |
| China               | 1        | 1      | 1.39%   |
| A-DATA Technology   | 1        | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3        | 3.66%   |
| Toshiba DT01ACA050 500GB            | 2        | 2.44%   |
| Seagate ST380815AS 80GB             | 2        | 2.44%   |
| Seagate ST3500418AS 500GB           | 2        | 2.44%   |
| Seagate ST3160815AS 160GB           | 2        | 2.44%   |
| Kingston SV300S37A120G 120GB SSD    | 2        | 2.44%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 2.44%   |
| Hitachi HTS545050A7E380 500GB       | 2        | 2.44%   |
| WDC WD6400AAKS-22A7B2 640GB         | 1        | 1.22%   |
| WDC WD5000AZLX-60K2TA0 500GB        | 1        | 1.22%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 1.22%   |
| WDC WD40EZRZ-75GXCB0 4TB            | 1        | 1.22%   |
| WDC WD2500AAKX-001CA0 250GB         | 1        | 1.22%   |
| WDC WD2500AAJS-75M0A0 250GB         | 1        | 1.22%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 1.22%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 1.22%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1        | 1.22%   |
| Unknown FK0032CAAZP 32GB            | 1        | 1.22%   |
| Toshiba MQ01ACF050 500GB            | 1        | 1.22%   |
| Toshiba MQ01ABD050V 500GB           | 1        | 1.22%   |
| Toshiba MK3275GSX 320GB             | 1        | 1.22%   |
| Toshiba MK2556GSY 250GB             | 1        | 1.22%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 1.22%   |
| Toshiba HDWE160 6TB                 | 1        | 1.22%   |
| SPCC Solid State Disk 1TB           | 1        | 1.22%   |
| Seagate ST980412ASG 80GB            | 1        | 1.22%   |
| Seagate ST9250410AS 250GB           | 1        | 1.22%   |
| Seagate ST8000DM004-2CX188 8TB      | 1        | 1.22%   |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1.22%   |
| Seagate ST3320620AS 320GB           | 1        | 1.22%   |
| Seagate ST3320418AS 320GB           | 1        | 1.22%   |
| Seagate ST3250318AS 250GB           | 1        | 1.22%   |
| Seagate ST3160215AS 160GB           | 1        | 1.22%   |
| Seagate ST3160212SCE 160GB          | 1        | 1.22%   |
| Seagate ST31000528AS 1TB            | 1        | 1.22%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB      | 1        | 1.22%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 31     | 50%     |
| WDC                 | 7        | 9      | 15.22%  |
| Toshiba             | 6        | 8      | 13.04%  |
| Hitachi             | 6        | 8      | 13.04%  |
| Samsung Electronics | 3        | 5      | 6.52%   |
| Maxtor              | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 8      | 33.33%  |
| Samsung Electronics | 5        | 5      | 23.81%  |
| Intel               | 2        | 2      | 9.52%   |
| Crucial             | 2        | 3      | 9.52%   |
| SPCC                | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 2      | 4.76%   |
| Patriot             | 1        | 1      | 4.76%   |
| China               | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 36       | 62     | 59.02%  |
| SSD     | 19       | 24     | 31.15%  |
| NVMe    | 5        | 7      | 8.2%    |
| Unknown | 1        | 1      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 86     | 88.24%  |
| NVMe | 5        | 7      | 9.8%    |
| SAS  | 1        | 1      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 64     | 67.24%  |
| 0.51-1.0   | 11       | 13     | 18.97%  |
| 1.01-2.0   | 4        | 5      | 6.9%    |
| 3.01-4.0   | 2        | 2      | 3.45%   |
| 4.01-10.0  | 2        | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 24%     |
| 501-1000       | 9        | 18%     |
| 1-20           | 8        | 16%     |
| 251-500        | 7        | 14%     |
| 51-100         | 6        | 12%     |
| More than 3000 | 4        | 8%      |
| 21-50          | 2        | 4%      |
| 1001-2000      | 1        | 2%      |
| Unknown        | 1        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 41.18%  |
| 21-50          | 8        | 15.69%  |
| 251-500        | 6        | 11.76%  |
| 51-100         | 5        | 9.8%    |
| 501-1000       | 4        | 7.84%   |
| 101-250        | 3        | 5.88%   |
| 2001-3000      | 2        | 3.92%   |
| More than 3000 | 1        | 1.96%   |
| Unknown        | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 1      | 7.14%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 1        | 1      | 7.14%   |
| Toshiba MQ01ABD050V 500GB       | 1        | 1      | 7.14%   |
| Toshiba MK3275GSX 320GB         | 1        | 1      | 7.14%   |
| Toshiba MK2556GSY 250GB         | 1        | 1      | 7.14%   |
| Seagate ST500LM000-1EJ162 500GB | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 7.14%   |
| Seagate ST3250318AS 250GB       | 1        | 1      | 7.14%   |
| Samsung Electronics HD154UI 1TB | 1        | 1      | 7.14%   |
| Hitachi HTS722020K9SA00 200GB   | 1        | 1      | 7.14%   |
| Hitachi HTS547564A9E384 640GB   | 1        | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB   | 1        | 1      | 7.14%   |
| Hitachi HDT721025SLA380 250GB   | 1        | 1      | 7.14%   |
| Crucial CT240BX500SSD1 240GB    | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 4        | 4      | 28.57%  |
| Toshiba             | 3        | 3      | 21.43%  |
| Seagate             | 3        | 3      | 21.43%  |
| WDC                 | 2        | 2      | 14.29%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 4        | 4      | 30.77%  |
| Toshiba             | 3        | 3      | 23.08%  |
| Seagate             | 3        | 3      | 23.08%  |
| WDC                 | 2        | 2      | 15.38%  |
| Samsung Electronics | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 13     | 90.91%  |
| SSD  | 1        | 1      | 9.09%   |

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
| Detected | 25       | 48     | 46.3%   |
| Works    | 18       | 31     | 33.33%  |
| Malfunc  | 10       | 14     | 18.52%  |
| Failed   | 1        | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 29       | 55.77%  |
| AMD                              | 14       | 26.92%  |
| Samsung Electronics              | 2        | 3.85%   |
| VIA Technologies                 | 1        | 1.92%   |
| Toshiba America Info Systems     | 1        | 1.92%   |
| Silicon Integrated Systems [SiS] | 1        | 1.92%   |
| SanDisk                          | 1        | 1.92%   |
| Phison Electronics               | 1        | 1.92%   |
| Marvell Technology Group         | 1        | 1.92%   |
| ASMedia Technology               | 1        | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 8.22%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 8.22%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 5.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 5.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 4.11%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 4.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.74%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.74%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.74%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.37%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 1.37%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 1.37%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 1.37%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.37%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.37%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.37%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.37%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.37%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.37%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.37%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 57.38%  |
| IDE  | 16       | 26.23%  |
| RAID | 5        | 8.2%    |
| NVMe | 5        | 8.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 66.67%  |
| AMD    | 15       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 6.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 4.44%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 4.44%   |
| AMD FX-4100 Quad-Core Processor             | 2        | 4.44%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 2.22%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 2.22%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 2.22%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 2.22%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 2.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2.22%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 2.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.22%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 2.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 2.22%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 2.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 2.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2.22%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.22%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 2.22%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 2.22%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 2.22%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 2.22%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2.22%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 2.22%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 2.22%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 2.22%   |
| AMD Sempron Processor LE-1100               | 1        | 2.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 2.22%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.22%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 2.22%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.22%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2.22%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.22%   |
| AMD PRO A10-8770 R7, 10 COMPUTE CORES 4C+6G | 1        | 2.22%   |
| AMD Phenom II X4 B95 Processor              | 1        | 2.22%   |
| AMD GX-212JC SOC with Radeon R2E Graphics   | 1        | 2.22%   |
| AMD FX-6350 Six-Core Processor              | 1        | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 28.89%  |
| AMD Ryzen 5             | 5        | 11.11%  |
| AMD FX                  | 5        | 11.11%  |
| Intel Core i7           | 3        | 6.67%   |
| Intel Core 2 Duo        | 3        | 6.67%   |
| Intel Xeon              | 2        | 4.44%   |
| Intel Core i3           | 2        | 4.44%   |
| Intel Pentium Dual-Core | 1        | 2.22%   |
| Intel Pentium D         | 1        | 2.22%   |
| Intel Pentium 4         | 1        | 2.22%   |
| Intel Pentium           | 1        | 2.22%   |
| Intel Core 2 Quad       | 1        | 2.22%   |
| Intel Celeron           | 1        | 2.22%   |
| Intel Atom              | 1        | 2.22%   |
| AMD Sempron             | 1        | 2.22%   |
| AMD Ryzen 3             | 1        | 2.22%   |
| AMD PRO A10             | 1        | 2.22%   |
| AMD Phenom II X4        | 1        | 2.22%   |
| AMD GX                  | 1        | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 51.11%  |
| 2      | 13       | 28.89%  |
| 6      | 4        | 8.89%   |
| 1      | 3        | 6.67%   |
| 12     | 1        | 2.22%   |
| 3      | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 97.78%  |
| 2      | 1        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 57.78%  |
| 2      | 19       | 42.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 45       | 97.83%  |
| 64-bit         | 1        | 2.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 19.57%  |
| 0x306c3    | 5        | 10.87%  |
| 0x306a9    | 4        | 8.7%    |
| 0x506e3    | 3        | 6.52%   |
| 0x206a7    | 3        | 6.52%   |
| 0x1067a    | 3        | 6.52%   |
| 0x0800820d | 3        | 6.52%   |
| 0x06000852 | 3        | 6.52%   |
| 0x6fb      | 2        | 4.35%   |
| 0xf65      | 1        | 2.17%   |
| 0xf49      | 1        | 2.17%   |
| 0x906ea    | 1        | 2.17%   |
| 0x906e9    | 1        | 2.17%   |
| 0x106c2    | 1        | 2.17%   |
| 0x10661    | 1        | 2.17%   |
| 0x08108109 | 1        | 2.17%   |
| 0x08101013 | 1        | 2.17%   |
| 0x0600611a | 1        | 2.17%   |
| 0x0600063d | 1        | 2.17%   |
| 0x010000db | 1        | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 6        | 13.33%  |
| IvyBridge   | 5        | 11.11%  |
| Zen+        | 4        | 8.89%   |
| SandyBridge | 4        | 8.89%   |
| Skylake     | 3        | 6.67%   |
| Piledriver  | 3        | 6.67%   |
| Penryn      | 3        | 6.67%   |
| Core        | 3        | 6.67%   |
| NetBurst    | 2        | 4.44%   |
| KabyLake    | 2        | 4.44%   |
| Bulldozer   | 2        | 4.44%   |
| Zen 3       | 1        | 2.22%   |
| Zen         | 1        | 2.22%   |
| Westmere    | 1        | 2.22%   |
| Puma        | 1        | 2.22%   |
| K8 Hammer   | 1        | 2.22%   |
| K10         | 1        | 2.22%   |
| Excavator   | 1        | 2.22%   |
| Bonnell     | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 21       | 44.68%  |
| AMD                              | 14       | 29.79%  |
| Nvidia                           | 10       | 21.28%  |
| VIA Technologies                 | 1        | 2.13%   |
| Silicon Integrated Systems [SiS] | 1        | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 12.77%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 6.38%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 6.38%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 4.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 4.26%   |
| Intel HD Graphics 530                                                       | 2        | 4.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 4.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.26%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                   | 1        | 2.13%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 2.13%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.13%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 2.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 2.13%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.13%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.13%   |
| Intel HD Graphics 630                                                       | 1        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 2.13%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 2.13%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.13%   |
| Intel 82G965 Integrated Graphics Controller                                 | 1        | 2.13%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.13%   |
| AMD Mullins [Radeon R1E/R2E Graphics]                                       | 1        | 2.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.13%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.13%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 19       | 42.22%  |
| 1 x AMD    | 14       | 31.11%  |
| 1 x Nvidia | 10       | 22.22%  |
| 1 x VIA    | 1        | 2.22%   |
| 1 x SiS    | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 38       | 82.61%  |
| Proprietary | 6        | 13.04%  |
| Unknown     | 2        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 47.83%  |
| 1.01-2.0   | 7        | 15.22%  |
| 0.01-0.5   | 5        | 10.87%  |
| 3.01-4.0   | 4        | 8.7%    |
| 0.51-1.0   | 4        | 8.7%    |
| 7.01-8.0   | 3        | 6.52%   |
| 2.01-3.0   | 1        | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 10       | 27.03%  |
| Hewlett-Packard      | 6        | 16.22%  |
| AOC                  | 5        | 13.51%  |
| Acer                 | 3        | 8.11%   |
| Sony                 | 2        | 5.41%   |
| Samsung Electronics  | 2        | 5.41%   |
| ViewSonic            | 1        | 2.7%    |
| Unknown (XXX)        | 1        | 2.7%    |
| Panasonic            | 1        | 2.7%    |
| NEC Computers        | 1        | 2.7%    |
| LG Electronics       | 1        | 2.7%    |
| KTC                  | 1        | 2.7%    |
| Goldstar             | 1        | 2.7%    |
| BenQ                 | 1        | 2.7%    |
| Ancor Communications | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                         | 2        | 5.13%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                       | 2        | 5.13%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 2.56%   |
| Unknown (XXX) MS82P XXX001A 1360x768 330x210mm 15.4-inch              | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1        | 2.56%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch  | 1        | 2.56%   |
| Panasonic TV MEI0206 1920x1080                                        | 1        | 2.56%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch          | 1        | 2.56%   |
| LG Electronics LCD Monitor W1943 1984x768                             | 1        | 2.56%   |
| LG Electronics LCD Monitor LG TV                                      | 1        | 2.56%   |
| KTC Q3202S KTC3200 2560x1440 698x392mm 31.5-inch                      | 1        | 2.56%   |
| Hewlett-Packard w1858 HWP281A 1366x768 413x234mm 18.7-inch            | 1        | 2.56%   |
| Hewlett-Packard V244h HPN3358 1920x1080 531x299mm 24.0-inch           | 1        | 2.56%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch         | 1        | 2.56%   |
| Hewlett-Packard LA2205 HWP2849 1680x1050 473x296mm 22.0-inch          | 1        | 2.56%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 1        | 2.56%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch           | 1        | 2.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 1        | 2.56%   |
| Goldstar TV GSM75E3 1024x768 920x518mm 41.6-inch                      | 1        | 2.56%   |
| Dell SP2208WFP DEL403A 1680x1050 473x296mm 22.0-inch                  | 1        | 2.56%   |
| Dell SE2717H/HX DELD0A0 1920x1080 598x336mm 27.0-inch                 | 1        | 2.56%   |
| Dell P2213 DELF041 1680x1050 473x296mm 22.0-inch                      | 1        | 2.56%   |
| Dell P2017H DELD094 1600x900 434x236mm 19.4-inch                      | 1        | 2.56%   |
| Dell E2020H DELA159 1600x900 434x236mm 19.4-inch                      | 1        | 2.56%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 2.56%   |
| Dell E177FP DELA023 1280x1024 340x270mm 17.1-inch                     | 1        | 2.56%   |
| Dell DEL 1708FPBLK DEL4045 1280x1024 338x270mm 17.0-inch              | 1        | 2.56%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 1        | 2.56%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                     | 1        | 2.56%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                     | 1        | 2.56%   |
| AOC TFT1780 AOC1780 1280x1024 376x301mm 19.0-inch                     | 1        | 2.56%   |
| AOC LCD Monitor 2243W 1920x1080                                       | 1        | 2.56%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                      | 1        | 2.56%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 1        | 2.56%   |
| Acer X193W ACR000C 1440x900 410x256mm 19.0-inch                       | 1        | 2.56%   |
| Acer V223W ACR0027 1680x1050 473x296mm 22.0-inch                      | 1        | 2.56%   |
| Acer P225HQL ACR014E 1920x1080 476x268mm 21.5-inch                    | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 31.58%  |
| 1680x1050 (WSXGA+) | 6        | 15.79%  |
| 1280x1024 (SXGA)   | 5        | 13.16%  |
| 1360x768           | 3        | 7.89%   |
| 2560x1440 (QHD)    | 2        | 5.26%   |
| 1600x900 (HD+)     | 2        | 5.26%   |
| 1440x900 (WXGA+)   | 2        | 5.26%   |
| 1366x768 (WXGA)    | 2        | 5.26%   |
| 3840x2160 (4K)     | 1        | 2.63%   |
| 1984x768           | 1        | 2.63%   |
| 1024x768 (XGA)     | 1        | 2.63%   |
| Unknown            | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 22      | 6        | 15.79%  |
| 19      | 6        | 15.79%  |
| 27      | 4        | 10.53%  |
| 21      | 4        | 10.53%  |
| 17      | 4        | 10.53%  |
| 18      | 3        | 7.89%   |
| Unknown | 3        | 7.89%   |
| 50      | 2        | 5.26%   |
| 24      | 2        | 5.26%   |
| 84      | 1        | 2.63%   |
| 41      | 1        | 2.63%   |
| 32      | 1        | 2.63%   |
| 15      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 17       | 45.95%  |
| 501-600     | 6        | 16.22%  |
| 301-350     | 5        | 13.51%  |
| Unknown     | 3        | 8.11%   |
| 1001-1500   | 2        | 5.41%   |
| 701-800     | 1        | 2.7%    |
| 351-400     | 1        | 2.7%    |
| 1501-2000   | 1        | 2.7%    |
| 901-1000    | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 52.78%  |
| 16/10   | 10       | 27.78%  |
| 5/4     | 5        | 13.89%  |
| Unknown | 2        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 10       | 26.32%  |
| 201-250        | 8        | 21.05%  |
| 141-150        | 7        | 18.42%  |
| 301-350        | 4        | 10.53%  |
| More than 1000 | 3        | 7.89%   |
| Unknown        | 3        | 7.89%   |
| 351-500        | 1        | 2.63%   |
| 101-110        | 1        | 2.63%   |
| 501-1000       | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 70.27%  |
| 101-120 | 5        | 13.51%  |
| 1-50    | 3        | 8.11%   |
| Unknown | 3        | 8.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 80.43%  |
| 2     | 5        | 10.87%  |
| 0     | 4        | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 25       | 36.76%  |
| Intel                           | 18       | 26.47%  |
| Ralink Technology               | 6        | 8.82%   |
| Broadcom                        | 6        | 8.82%   |
| Qualcomm Atheros                | 5        | 7.35%   |
| Qualcomm Atheros Communications | 2        | 2.94%   |
| Linksys                         | 2        | 2.94%   |
| VIA Technologies                | 1        | 1.47%   |
| Tul Corporation / PowerColor    | 1        | 1.47%   |
| TP-Link                         | 1        | 1.47%   |
| HTC (High Tech Computer)        | 1        | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 28%     |
| Ralink MT7601U Wireless Adapter                                   | 5        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 4%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 4%      |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 2.67%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.33%   |
| Tul Corporation / PowerColor Network controller                   | 1        | 1.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 1.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 1.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.33%   |
| Realtek 802.11ac NIC                                              | 1        | 1.33%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 1.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.33%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 1.33%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.33%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.33%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 1.33%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1        | 1.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.33%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.33%   |
| Broadcom BCM43217 802.11b/g/n                                     | 1        | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 38.46%  |
| Ralink Technology               | 6        | 23.08%  |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| Qualcomm Atheros                | 2        | 7.69%   |
| Linksys                         | 2        | 7.69%   |
| Broadcom                        | 2        | 7.69%   |
| TP-Link                         | 1        | 3.85%   |
| Intel                           | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 5        | 19.23%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3        | 11.54%  |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 7.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 3.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 3.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 3.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 3.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1        | 3.85%   |
| Realtek 802.11ac NIC                                           | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 3.85%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 3.85%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]  | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1        | 3.85%   |
| Broadcom BCM43217 802.11b/g/n                                  | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 22       | 45.83%  |
| Intel                    | 17       | 35.42%  |
| Broadcom                 | 4        | 8.33%   |
| Qualcomm Atheros         | 3        | 6.25%   |
| VIA Technologies         | 1        | 2.08%   |
| HTC (High Tech Computer) | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 43.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 10.42%  |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 4.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 2.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.08%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.08%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.08%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 2.08%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1        | 2.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.08%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 2.08%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 2.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 64.71%  |
| WiFi     | 23       | 33.82%  |
| Unknown  | 1        | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 67.39%  |
| WiFi     | 15       | 32.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 35       | 77.78%  |
| 2     | 9        | 20%     |
| 0     | 1        | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 89.36%  |
| Yes  | 5        | 10.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 7        | 63.64%  |
| Intel                   | 1        | 9.09%   |
| IMC Networks            | 1        | 9.09%   |
| Dynex                   | 1        | 9.09%   |
| ASUSTek Computer        | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 7        | 63.64%  |
| Intel Bluetooth Device                                   | 1        | 9.09%   |
| IMC Networks BCM20702A0                                  | 1        | 9.09%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 9.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 27       | 42.86%  |
| AMD                              | 17       | 26.98%  |
| Nvidia                           | 10       | 15.87%  |
| Logitech                         | 2        | 3.17%   |
| VIA Technologies                 | 1        | 1.59%   |
| Silicon Integrated Systems [SiS] | 1        | 1.59%   |
| JMTek                            | 1        | 1.59%   |
| Creative Labs                    | 1        | 1.59%   |
| C-Media Electronics              | 1        | 1.59%   |
| Blue Microphones                 | 1        | 1.59%   |
| BigBen Interactive               | 1        | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 7.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 7.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 7.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 6.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 3.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.8%    |
| Nvidia High Definition Audio Controller                                    | 2        | 2.53%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 2.53%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 2.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2.53%   |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.53%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.53%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 1.27%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.27%   |
| Logitech QuickCam Fusion                                                   | 1        | 1.27%   |
| Logitech Headset H390                                                      | 1        | 1.27%   |
| JMTek USB Speaker                                                          | 1        | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.27%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.27%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 1        | 1.27%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 1        | 1.27%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1        | 1.27%   |
| BigBen Interactive Revolution Pro Controller                               | 1        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.27%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 8        | 22.86%  |
| Unknown             | 5        | 14.29%  |
| Samsung Electronics | 5        | 14.29%  |
| Micron Technology   | 3        | 8.57%   |
| Corsair             | 3        | 8.57%   |
| Kingston            | 2        | 5.71%   |
| V-Color             | 1        | 2.86%   |
| Ramaxel Technology  | 1        | 2.86%   |
| Qimonda             | 1        | 2.86%   |
| Patriot             | 1        | 2.86%   |
| Nanya Technology    | 1        | 2.86%   |
| G.Skill             | 1        | 2.86%   |
| Elpida              | 1        | 2.86%   |
| Crucial             | 1        | 2.86%   |
| Avant               | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 2        | 5.41%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 2        | 5.41%   |
| V-Color RAM TL48G32S8KGRGB16 8192MB DIMM DDR4 3200MT/s    | 1        | 2.7%    |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                 | 1        | 2.7%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 2.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 2.7%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 2.7%    |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s             | 1        | 2.7%    |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s      | 1        | 2.7%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s      | 1        | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 2.7%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 2.7%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s       | 1        | 2.7%    |
| Samsung RAM M378B5673FH0-CF8 2048MB DIMM DDR3 1067MT/s    | 1        | 2.7%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 2.7%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s       | 1        | 2.7%    |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.7%    |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s     | 1        | 2.7%    |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s          | 1        | 2.7%    |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s           | 1        | 2.7%    |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR2 49926MT/s       | 1        | 2.7%    |
| Nanya RAM NT1GT64U88D0BY-3C 1024MB DIMM DDR2 667MT/s      | 1        | 2.7%    |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s     | 1        | 2.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 2.7%    |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s       | 1        | 2.7%    |
| Kingston RAM HP497157-D88-ELFWG 2GB DIMM DDR3 1333MT/s    | 1        | 2.7%    |
| Kingston RAM 9965745-028.A00G 16GB DIMM DDR4 2666MT/s     | 1        | 2.7%    |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s        | 1        | 2.7%    |
| Elpida RAM SyncMAX 512MB DIMM DDR 533MT/s                 | 1        | 2.7%    |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s     | 1        | 2.7%    |
| Corsair RAM CMY16GX3M2A1600C9 8GB DIMM DDR3 2133MT/s      | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s     | 1        | 2.7%    |
| Avant RAM F6428U52E6800F 1024MB DIMM DDR 533MT/s          | 1        | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 34.62%  |
| DDR4    | 8        | 30.77%  |
| SDRAM   | 4        | 15.38%  |
| Unknown | 3        | 11.54%  |
| DDR2    | 1        | 3.85%   |
| DDR     | 1        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 22       | 95.65%  |
| SODIMM | 1        | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 33.33%  |
| 4096  | 9        | 33.33%  |
| 2048  | 5        | 18.52%  |
| 1024  | 2        | 7.41%   |
| 16384 | 1        | 3.7%    |
| 512   | 1        | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 20%     |
| 1333    | 6        | 20%     |
| 2133    | 3        | 10%     |
| 2933    | 2        | 6.67%   |
| 49926   | 1        | 3.33%   |
| 3600    | 1        | 3.33%   |
| 3200    | 1        | 3.33%   |
| 2934    | 1        | 3.33%   |
| 2666    | 1        | 3.33%   |
| 2400    | 1        | 3.33%   |
| 1867    | 1        | 3.33%   |
| 1648    | 1        | 3.33%   |
| 1331    | 1        | 3.33%   |
| 1067    | 1        | 3.33%   |
| 667     | 1        | 3.33%   |
| 533     | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

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


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam HD-5001   | 2        | 22.22%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 11.11%  |
| OmniVision Monitor Webcam               | 1        | 11.11%  |
| OmniVision Monitor Integrated Webcam    | 1        | 11.11%  |
| Microsoft LifeCam VX-2000               | 1        | 11.11%  |
| Logitech Webcam Pro 9000                | 1        | 11.11%  |
| Jieli USB PHY 2.0                       | 1        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1        | 11.11%  |

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
| 0     | 38       | 82.61%  |
| 1     | 8        | 17.39%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 5        | 62.5%   |
| Network       | 1        | 12.5%   |
| Net/wireless  | 1        | 12.5%   |
| Camera        | 1        | 12.5%   |

