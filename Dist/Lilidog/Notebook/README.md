Lilidog - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lilidog.

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
| Acer          | Nitro AN515-54              | [071a512314](https://linux-hardware.org/?probe=071a512314) | Dec 17, 2024 |
| Lenovo        | ThinkPad X131e 33722WU      | [1e06ef890d](https://linux-hardware.org/?probe=1e06ef890d) | Dec 04, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [963aca3a61](https://linux-hardware.org/?probe=963aca3a61) | Nov 22, 2024 |
| HP            | ProBook 450 G5              | [022c2f84fc](https://linux-hardware.org/?probe=022c2f84fc) | Nov 10, 2024 |
| Lenovo        | 3000 G410                   | [cf7fd7d924](https://linux-hardware.org/?probe=cf7fd7d924) | Oct 28, 2024 |
| Lenovo        | 3000 G410                   | [294011f6db](https://linux-hardware.org/?probe=294011f6db) | Oct 28, 2024 |
| PC Special... | P65_67RSRP                  | [45ef7521c8](https://linux-hardware.org/?probe=45ef7521c8) | Aug 18, 2024 |
| Dell          | Latitude E6530              | [829814779a](https://linux-hardware.org/?probe=829814779a) | Jul 25, 2024 |
| HP            | Laptop 15s-fq1xxx           | [9cc57cd7ff](https://linux-hardware.org/?probe=9cc57cd7ff) | Jun 20, 2024 |
| HP            | Laptop 15s-fq1xxx           | [760c95f432](https://linux-hardware.org/?probe=760c95f432) | May 15, 2024 |
| Matsushita... | CF-52GDN30AG                | [19d09b44b2](https://linux-hardware.org/?probe=19d09b44b2) | May 11, 2024 |
| Toshiba       | Satellite P200              | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Acer          | Aspire E5-573               | [1060cb82e8](https://linux-hardware.org/?probe=1060cb82e8) | May 01, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [6d235ddbaf](https://linux-hardware.org/?probe=6d235ddbaf) | Apr 29, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [419fb8dfca](https://linux-hardware.org/?probe=419fb8dfca) | Apr 28, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a154dad3b7](https://linux-hardware.org/?probe=a154dad3b7) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [6006e10996](https://linux-hardware.org/?probe=6006e10996) | Apr 20, 2024 |
| HP            | 630                         | [4aee0c5868](https://linux-hardware.org/?probe=4aee0c5868) | Mar 10, 2024 |
| HP            | 510 Notebook PC (RU962AA... | [94571f879e](https://linux-hardware.org/?probe=94571f879e) | Mar 02, 2024 |
| Dell          | Latitude E5420              | [1cdafef139](https://linux-hardware.org/?probe=1cdafef139) | Feb 07, 2024 |
| HP            | Pavilion 11 x360 PC         | [1d8dbbd8af](https://linux-hardware.org/?probe=1d8dbbd8af) | Jan 29, 2024 |
| Acer          | Aspire E1-470               | [732a523ea8](https://linux-hardware.org/?probe=732a523ea8) | Jan 28, 2024 |
| ASUSTek       | X550VC                      | [90ebdf4197](https://linux-hardware.org/?probe=90ebdf4197) | Jan 22, 2024 |
| HP            | ProBook 6560b               | [6d2bbcc556](https://linux-hardware.org/?probe=6d2bbcc556) | Jan 21, 2024 |
| Lenovo        | ThinkPad T430s 2356GUU      | [df4e542b16](https://linux-hardware.org/?probe=df4e542b16) | Jan 15, 2024 |
| PC Special... | P65_67RSRP                  | [f2af84bdfc](https://linux-hardware.org/?probe=f2af84bdfc) | Jan 13, 2024 |
| Apple         | MacBook4,1                  | [6d15625c9b](https://linux-hardware.org/?probe=6d15625c9b) | Jan 05, 2024 |
| Lenovo        | ThinkPad X280 20KES63G00    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Toshiba       | Satellite Pro L450          | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Acer          | AOD270                      | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Acer          | Aspire one                  | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Sony          | VPCF23P1E                   | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| Google        | Sand                        | [97e4755fe5](https://linux-hardware.org/?probe=97e4755fe5) | Nov 07, 2023 |
| Dell          | Inspiron 1318               | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| HP            | 435                         | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Google        | Sand                        | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Lenovo        | G500 20236                  | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Acer          | V5-131                      | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| Acer          | AOD255E                     | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| GPU Compan... | GWNR71517                   | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| Dell          | Inspiron 3793               | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Lilidog 23 | 34        | 59.65%  |
| Lilidog 22 | 16        | 28.07%  |
| Lilidog 24 | 7         | 12.28%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lilidog | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.5.0-0.deb12.4-amd64     | 8         | 13.11%  |
| 6.1.0-9-amd64             | 5         | 8.2%    |
| 5.10.0-15-amd64           | 4         | 6.56%   |
| 6.6.13+bpo-amd64          | 3         | 4.92%   |
| 6.1.0-10-amd64            | 3         | 4.92%   |
| 5.10.0-16-amd64           | 3         | 4.92%   |
| 6.5.0-0.deb12.1-amd64     | 2         | 3.28%   |
| 6.11.5+bpo-amd64          | 2         | 3.28%   |
| 6.1.0-20-amd64            | 2         | 3.28%   |
| 6.1.0-18-amd64            | 2         | 3.28%   |
| 6.1.0-16-amd64            | 2         | 3.28%   |
| 5.10.0-21-amd64           | 2         | 3.28%   |
| 5.10.0-18-amd64           | 2         | 3.28%   |
| 6.8.9-5-liquorix-amd64    | 1         | 1.64%   |
| 6.7.12+bpo-amd64          | 1         | 1.64%   |
| 6.4.5-1-liquorix-amd64    | 1         | 1.64%   |
| 6.4.0-0.deb12.2-amd64     | 1         | 1.64%   |
| 6.12.1-1-liquorix-amd64   | 1         | 1.64%   |
| 6.10.11+bpo-amd64         | 1         | 1.64%   |
| 6.1.0-7-amd64             | 1         | 1.64%   |
| 6.1.0-25-686-pae          | 1         | 1.64%   |
| 6.1.0-23-amd64            | 1         | 1.64%   |
| 6.1.0-21-amd64            | 1         | 1.64%   |
| 6.1.0-18-686-pae          | 1         | 1.64%   |
| 6.1.0-13-amd64            | 1         | 1.64%   |
| 6.1.0-13-686-pae          | 1         | 1.64%   |
| 6.1.0-11-amd64            | 1         | 1.64%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 1.64%   |
| 6.0.10-x64v1-xanmod1      | 1         | 1.64%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 1.64%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 1.64%   |
| 5.10.0-22-amd64           | 1         | 1.64%   |
| 5.10.0-14-amd64           | 1         | 1.64%   |
| 5.10.0-13-amd64           | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 22        | 37.93%  |
| 5.10.0  | 12        | 20.69%  |
| 6.5.0   | 10        | 17.24%  |
| 6.6.13  | 3         | 5.17%   |
| 6.11.5  | 2         | 3.45%   |
| 6.8.9   | 1         | 1.72%   |
| 6.7.12  | 1         | 1.72%   |
| 6.4.5   | 1         | 1.72%   |
| 6.4.0   | 1         | 1.72%   |
| 6.12.1  | 1         | 1.72%   |
| 6.10.11 | 1         | 1.72%   |
| 6.0.10  | 1         | 1.72%   |
| 6.0.0   | 1         | 1.72%   |
| 5.17.0  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 37.93%  |
| 5.10    | 12        | 20.69%  |
| 6.5     | 10        | 17.24%  |
| 6.6     | 3         | 5.17%   |
| 6.4     | 2         | 3.45%   |
| 6.11    | 2         | 3.45%   |
| 6.0     | 2         | 3.45%   |
| 6.8     | 1         | 1.72%   |
| 6.7     | 1         | 1.72%   |
| 6.12    | 1         | 1.72%   |
| 6.10    | 1         | 1.72%   |
| 5.17    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 50        | 94.34%  |
| i686   | 3         | 5.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 34        | 60.71%  |
| openbox          | 21        | 37.5%   |
| dk               | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 53        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 53        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 48.15%  |
| de_DE | 5         | 9.26%   |
| pl_PL | 4         | 7.41%   |
| es_ES | 3         | 5.56%   |
| ru_RU | 2         | 3.7%    |
| es_CO | 2         | 3.7%    |
| en_GB | 2         | 3.7%    |
| pt_BR | 1         | 1.85%   |
| it_IT | 1         | 1.85%   |
| fi_FI | 1         | 1.85%   |
| es_MX | 1         | 1.85%   |
| es_CL | 1         | 1.85%   |
| es_AR | 1         | 1.85%   |
| en_IE | 1         | 1.85%   |
| en_CA | 1         | 1.85%   |
| en_AU | 1         | 1.85%   |
| cs_CZ | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 50.94%  |
| EFI  | 26        | 49.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 72.22%  |
| Overlay | 11        | 20.37%  |
| Btrfs   | 3         | 5.56%   |
| Xfs     | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 28        | 51.85%  |
| MBR  | 26        | 48.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 63.16%  |
| Yes       | 21        | 36.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 83.02%  |
| Yes       | 9         | 16.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 12        | 22.64%  |
| Acer                           | 10        | 18.87%  |
| Hewlett-Packard                | 8         | 15.09%  |
| Dell                           | 7         | 13.21%  |
| ASUSTek Computer               | 3         | 5.66%   |
| Toshiba                        | 2         | 3.77%   |
| Panasonic                      | 2         | 3.77%   |
| Google                         | 2         | 3.77%   |
| Apple                          | 2         | 3.77%   |
| TUXEDO                         | 1         | 1.89%   |
| Sony                           | 1         | 1.89%   |
| PC Specialist                  | 1         | 1.89%   |
| Matsushita Electric Industrial | 1         | 1.89%   |
| GPU Company                    | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire E5-573                          | 2         | 3.77%   |
| Acer AOD255E                                | 2         | 3.77%   |
| TUXEDO N8xEJEK                              | 1         | 1.89%   |
| Toshiba Satellite Pro L450                  | 1         | 1.89%   |
| Toshiba Satellite P200                      | 1         | 1.89%   |
| Sony VPCF23P1E                              | 1         | 1.89%   |
| PC Specialist P65_67RSRP                    | 1         | 1.89%   |
| Panasonic CFMX4-1                           | 1         | 1.89%   |
| Panasonic CF-31ATXAX1M                      | 1         | 1.89%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 1.89%   |
| Lenovo Yoga Slim 7 14ARE05 82A2             | 1         | 1.89%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 1.89%   |
| Lenovo ThinkPad X280 20KES63G00             | 1         | 1.89%   |
| Lenovo ThinkPad X131e 33722WU               | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW  | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900    | 1         | 1.89%   |
| Lenovo ThinkPad T430s 2356GUU               | 1         | 1.89%   |
| Lenovo ThinkPad T400 6474WPU                | 1         | 1.89%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 1         | 1.89%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 1         | 1.89%   |
| Lenovo G500 20236                           | 1         | 1.89%   |
| Lenovo 3000 G410                            | 1         | 1.89%   |
| HP ProBook 6560b                            | 1         | 1.89%   |
| HP ProBook 450 G5                           | 1         | 1.89%   |
| HP Pavilion 11 x360 PC                      | 1         | 1.89%   |
| HP Laptop 15s-fq1xxx                        | 1         | 1.89%   |
| HP G62                                      | 1         | 1.89%   |
| HP 630                                      | 1         | 1.89%   |
| HP 510 Notebook PC (RU962AA#ABE)            | 1         | 1.89%   |
| HP 435                                      | 1         | 1.89%   |
| GPU Company GWNR71517                       | 1         | 1.89%   |
| Google Sand                                 | 1         | 1.89%   |
| Google Auron_Yuna                           | 1         | 1.89%   |
| Dell Latitude E6530                         | 1         | 1.89%   |
| Dell Latitude E5440                         | 1         | 1.89%   |
| Dell Latitude E5420                         | 1         | 1.89%   |
| Dell Latitude 7414                          | 1         | 1.89%   |
| Dell Latitude 7390                          | 1         | 1.89%   |
| Dell Inspiron 3793                          | 1         | 1.89%   |
| Dell Inspiron 1318                          | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 6         | 11.32%  |
| Dell Latitude                               | 5         | 9.43%   |
| Acer Aspire                                 | 5         | 9.43%   |
| Toshiba Satellite                           | 2         | 3.77%   |
| Lenovo IdeaPad                              | 2         | 3.77%   |
| HP ProBook                                  | 2         | 3.77%   |
| Dell Inspiron                               | 2         | 3.77%   |
| ASUS VivoBook                               | 2         | 3.77%   |
| Acer AOD255E                                | 2         | 3.77%   |
| TUXEDO N8xEJEK                              | 1         | 1.89%   |
| Sony VPCF23P1E                              | 1         | 1.89%   |
| PC Specialist P65                           | 1         | 1.89%   |
| Panasonic CFMX4-1                           | 1         | 1.89%   |
| Panasonic CF-31ATXAX1M                      | 1         | 1.89%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 1.89%   |
| Lenovo Yoga                                 | 1         | 1.89%   |
| Lenovo Y520-15IKBN                          | 1         | 1.89%   |
| Lenovo G500                                 | 1         | 1.89%   |
| Lenovo 3000                                 | 1         | 1.89%   |
| HP Pavilion                                 | 1         | 1.89%   |
| HP Laptop                                   | 1         | 1.89%   |
| HP G62                                      | 1         | 1.89%   |
| HP 630                                      | 1         | 1.89%   |
| HP 510                                      | 1         | 1.89%   |
| HP 435                                      | 1         | 1.89%   |
| GPU Company GWNR71517                       | 1         | 1.89%   |
| Google Sand                                 | 1         | 1.89%   |
| Google Auron                                | 1         | 1.89%   |
| ASUS X550VC                                 | 1         | 1.89%   |
| Apple MacBookPro3                           | 1         | 1.89%   |
| Apple MacBook4                              | 1         | 1.89%   |
| Acer V5-131                                 | 1         | 1.89%   |
| Acer Nitro                                  | 1         | 1.89%   |
| Acer AOD270                                 | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 5         | 9.43%   |
| 2012 | 5         | 9.43%   |
| 2011 | 5         | 9.43%   |
| 2010 | 5         | 9.43%   |
| 2013 | 4         | 7.55%   |
| 2008 | 4         | 7.55%   |
| 2007 | 4         | 7.55%   |
| 2021 | 3         | 5.66%   |
| 2020 | 3         | 5.66%   |
| 2019 | 3         | 5.66%   |
| 2017 | 3         | 5.66%   |
| 2016 | 2         | 3.77%   |
| 2015 | 2         | 3.77%   |
| 2014 | 2         | 3.77%   |
| 2009 | 2         | 3.77%   |
| 2022 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 52        | 98.11%  |
| Enabled  | 1         | 1.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 94.34%  |
| Yes  | 3         | 5.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 29.63%  |
| 3.01-4.0    | 16        | 29.63%  |
| 16.01-24.0  | 6         | 11.11%  |
| 8.01-16.0   | 5         | 9.26%   |
| 1.01-2.0    | 4         | 7.41%   |
| 32.01-64.0  | 2         | 3.7%    |
| 24.01-32.0  | 1         | 1.85%   |
| 2.01-3.0    | 1         | 1.85%   |
| 64.01-256.0 | 1         | 1.85%   |
| 0.51-1.0    | 1         | 1.85%   |
| 0.01-0.5    | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 33        | 57.89%  |
| 1.01-2.0 | 15        | 26.32%  |
| 2.01-3.0 | 7         | 12.28%  |
| 3.01-4.0 | 1         | 1.75%   |
| 0.01-0.5 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 81.48%  |
| 2      | 7         | 12.96%  |
| 3      | 2         | 3.7%    |
| 4      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 60.38%  |
| Yes       | 21        | 39.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 81.48%  |
| No        | 10        | 18.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 98.11%  |
| No        | 1         | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 70.91%  |
| No        | 16        | 29.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 18.87%  |
| Germany     | 8         | 15.09%  |
| Poland      | 5         | 9.43%   |
| Spain       | 4         | 7.55%   |
| Netherlands | 2         | 3.77%   |
| Italy       | 2         | 3.77%   |
| Finland     | 2         | 3.77%   |
| Colombia    | 2         | 3.77%   |
| Canada      | 2         | 3.77%   |
| Vietnam     | 1         | 1.89%   |
| Ukraine     | 1         | 1.89%   |
| UK          | 1         | 1.89%   |
| Thailand    | 1         | 1.89%   |
| Portugal    | 1         | 1.89%   |
| Mexico      | 1         | 1.89%   |
| Kenya       | 1         | 1.89%   |
| Honduras    | 1         | 1.89%   |
| France      | 1         | 1.89%   |
| Czechia     | 1         | 1.89%   |
| Chile       | 1         | 1.89%   |
| Bulgaria    | 1         | 1.89%   |
| Brazil      | 1         | 1.89%   |
| Belgium     | 1         | 1.89%   |
| Australia   | 1         | 1.89%   |
| Argentina   | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Fayetteville                | 3         | 5.66%   |
| Milan                       | 2         | 3.77%   |
| Medellín                   | 2         | 3.77%   |
| Helsinki                    | 2         | 3.77%   |
| Egan                        | 2         | 3.77%   |
| Denver                      | 2         | 3.77%   |
| Zduny                       | 1         | 1.89%   |
| Wroclaw                     | 1         | 1.89%   |
| Viña del Mar               | 1         | 1.89%   |
| Uelzen                      | 1         | 1.89%   |
| Stockton-on-Tees            | 1         | 1.89%   |
| Stabroek                    | 1         | 1.89%   |
| Sofia                       | 1         | 1.89%   |
| Sevastopol                  | 1         | 1.89%   |
| Schiedam                    | 1         | 1.89%   |
| San Nicolás de los Arroyos | 1         | 1.89%   |
| Rumia                       | 1         | 1.89%   |
| Rinteln                     | 1         | 1.89%   |
| Ratchathewi                 | 1         | 1.89%   |
| Poznan                      | 1         | 1.89%   |
| Poricany                    | 1         | 1.89%   |
| Ossa de Montiel             | 1         | 1.89%   |
| Norderstedt                 | 1         | 1.89%   |
| Neu-Isenburg                | 1         | 1.89%   |
| Nairobi                     | 1         | 1.89%   |
| Morgantown                  | 1         | 1.89%   |
| Monclova                    | 1         | 1.89%   |
| Madrid                      | 1         | 1.89%   |
| Lisbon                      | 1         | 1.89%   |
| L'Isle-sur-la-Sorgue        | 1         | 1.89%   |
| Ho Chi Minh City            | 1         | 1.89%   |
| Groningen                   | 1         | 1.89%   |
| Gdansk                      | 1         | 1.89%   |
| Filderstadt                 | 1         | 1.89%   |
| Eppelborn                   | 1         | 1.89%   |
| El Progreso                 | 1         | 1.89%   |
| Edmonton                    | 1         | 1.89%   |
| Düsseldorf                 | 1         | 1.89%   |
| Darmstadt                   | 1         | 1.89%   |
| Clermont                    | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 12.7%   |
| Samsung Electronics | 8         | 10     | 12.7%   |
| Kingston            | 6         | 7      | 9.52%   |
| WDC                 | 5         | 8      | 7.94%   |
| Toshiba             | 5         | 6      | 7.94%   |
| SanDisk             | 3         | 5      | 4.76%   |
| Crucial             | 3         | 3      | 4.76%   |
| Unknown             | 2         | 2      | 3.17%   |
| Micron Technology   | 2         | 3      | 3.17%   |
| Hitachi             | 2         | 2      | 3.17%   |
| Wibtek              | 1         | 1      | 1.59%   |
| SPCC                | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Mushkin             | 1         | 1      | 1.59%   |
| Lexar               | 1         | 1      | 1.59%   |
| KIOXIA              | 1         | 3      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| KingFast            | 1         | 1      | 1.59%   |
| JMicron Technology  | 1         | 1      | 1.59%   |
| Intel               | 1         | 1      | 1.59%   |
| Integral            | 1         | 2      | 1.59%   |
| Hikvision           | 1         | 1      | 1.59%   |
| GOODRAM             | 1         | 1      | 1.59%   |
| Fanxiang            | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |
| Blackpcs            | 1         | 1      | 1.59%   |
| Apacer              | 1         | 1      | 1.59%   |
| AMD                 | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 4         | 5.97%   |
| Toshiba MQ04ABF100 1TB               | 3         | 4.48%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2.99%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.99%   |
| Wibtek W800S 512GB SSD               | 1         | 1.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1.49%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 1.49%   |
| WDC WD600UE-22KVT0 64GB              | 1         | 1.49%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.49%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.49%   |
| WDC WD10SPCX-60KHST0 1TB             | 1         | 1.49%   |
| Unknown NCard  32GB                  | 1         | 1.49%   |
| Unknown DA4064  64GB                 | 1         | 1.49%   |
| Toshiba MK6034GSX 64GB               | 1         | 1.49%   |
| Toshiba MK1665GSX 160GB              | 1         | 1.49%   |
| SPCC Solid State Disk 256GB          | 1         | 1.49%   |
| Seagate ST9320325AS 320GB            | 1         | 1.49%   |
| Seagate ST9250315AS 250GB            | 1         | 1.49%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.49%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1.49%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1.49%   |
| Seagate OneTouch HDD 2TB             | 1         | 1.49%   |
| Seagate Expansion 1TB                | 1         | 1.49%   |
| SanDisk SSD PLUS 480GB               | 1         | 1.49%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 1.49%   |
| SanDisk DF4032  32GB                 | 1         | 1.49%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 1.49%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 1.49%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.49%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.49%   |
| Samsung PM991a NVMe 512GB            | 1         | 1.49%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.49%   |
| Samsung MZNTE128HMGR-00000 128GB SSD | 1         | 1.49%   |
| PNY 240GB SATA SSD                   | 1         | 1.49%   |
| Mushkin MKNSSDCR120GB                | 1         | 1.49%   |
| Micron MTFDHBA512QFD 512GB           | 1         | 1.49%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 1.49%   |
| Lexar SSD NM620 256GB                | 1         | 1.49%   |
| KIOXIA KBG40ZNV1T02 1TB              | 1         | 1.49%   |
| Kingston SNS4151S332GD 32GB SSD      | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 10     | 42.11%  |
| Toshiba | 5         | 6      | 26.32%  |
| WDC     | 4         | 5      | 21.05%  |
| Hitachi | 2         | 2      | 10.53%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 18.75%  |
| Kingston            | 5         | 6      | 15.63%  |
| Crucial             | 3         | 3      | 9.38%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Wibtek              | 1         | 1      | 3.13%   |
| WDC                 | 1         | 1      | 3.13%   |
| SPCC                | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Mushkin             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 2      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| KingFast            | 1         | 1      | 3.13%   |
| Integral            | 1         | 2      | 3.13%   |
| GOODRAM             | 1         | 1      | 3.13%   |
| Fanxiang            | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| Blackpcs            | 1         | 1      | 3.13%   |
| Apacer              | 1         | 1      | 3.13%   |
| AMD                 | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 30        | 35     | 49.18%  |
| HDD     | 18        | 23     | 29.51%  |
| NVMe    | 10        | 14     | 16.39%  |
| MMC     | 2         | 5      | 3.28%   |
| Unknown | 1         | 1      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 55     | 74.58%  |
| NVMe | 10        | 14     | 16.95%  |
| SAS  | 3         | 4      | 5.08%   |
| MMC  | 2         | 5      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 41     | 77.08%  |
| 0.51-1.0   | 9         | 15     | 18.75%  |
| 1.01-2.0   | 2         | 2      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 29.82%  |
| 251-500        | 11        | 19.3%   |
| 1-20           | 11        | 19.3%   |
| 501-1000       | 7         | 12.28%  |
| 51-100         | 6         | 10.53%  |
| 21-50          | 2         | 3.51%   |
| 1001-2000      | 2         | 3.51%   |
| More than 3000 | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 44        | 80%     |
| 21-50    | 6         | 10.91%  |
| 251-500  | 2         | 3.64%   |
| 101-250  | 1         | 1.82%   |
| 501-1000 | 1         | 1.82%   |
| 51-100   | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 2         | 3      | 25%     |
| Toshiba MQ04ABF100 1TB          | 1         | 1      | 12.5%   |
| Toshiba MK1665GSX 160GB         | 1         | 1      | 12.5%   |
| Seagate ST9250315AS 250GB       | 1         | 1      | 12.5%   |
| SanDisk SSD PLUS 480GB          | 1         | 1      | 12.5%   |
| Mushkin MKNSSDCR120GB           | 1         | 1      | 12.5%   |
| Kingston SNS4151S332GD 32GB SSD | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 4      | 37.5%   |
| Toshiba  | 2         | 2      | 25%     |
| SanDisk  | 1         | 1      | 12.5%   |
| Mushkin  | 1         | 1      | 12.5%   |
| Kingston | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| Toshiba | 2         | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 44        | 59     | 75.86%  |
| Malfunc  | 8         | 9      | 13.79%  |
| Detected | 5         | 9      | 8.62%   |
| Failed   | 1         | 1      | 1.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 75.86%  |
| AMD                          | 4         | 6.9%    |
| Samsung Electronics          | 3         | 5.17%   |
| Shenzhen Longsys Electronics | 1         | 1.72%   |
| SanDisk                      | 1         | 1.72%   |
| Micron Technology            | 1         | 1.72%   |
| MAXIO Technology (Hangzhou)  | 1         | 1.72%   |
| Marvell Technology Group     | 1         | 1.72%   |
| KIOXIA                       | 1         | 1.72%   |
| Kingston Technology Company  | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4         | 6.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 4         | 6.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 4         | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 4         | 6.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 3         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 4.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 3.08%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 2         | 3.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 2         | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 3.08%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 2         | 3.08%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 1.54%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 1         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 1         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 1.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 1         | 1.54%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 1         | 1.54%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1         | 1.54%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                                                          | 1         | 1.54%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 1.54%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                                               | 1         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 1         | 1.54%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 1         | 1.54%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 1         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 1         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 1         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                                               | 1         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                                                       | 1         | 1.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                                                     | 1         | 1.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                                           | 1         | 1.54%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                                                    | 1         | 1.54%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                                                    | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 58.73%  |
| NVMe | 10        | 15.87%  |
| IDE  | 9         | 14.29%  |
| RAID | 7         | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 88.68%  |
| AMD    | 6         | 11.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 3.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 3.77%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 3.77%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.77%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.89%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.89%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.89%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 1.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.89%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.89%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.89%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.89%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.89%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.89%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.89%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz        | 1         | 1.89%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.89%   |
| Intel Celeron M processor 1.50GHz           | 1         | 1.89%   |
| Intel Celeron CPU N2820 @ 2.13GHz           | 1         | 1.89%   |
| Intel Celeron CPU B840 @ 1.90GHz            | 1         | 1.89%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 1         | 1.89%   |
| Intel Celeron 3205U @ 1.50GHz               | 1         | 1.89%   |
| Intel Atom CPU N270 @ 1.60GHz               | 1         | 1.89%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 1.89%   |
| Intel 12th Gen Core i7-1260P                | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 22.64%  |
| Intel Core i7           | 10        | 18.87%  |
| Intel Core 2 Duo        | 6         | 11.32%  |
| Other                   | 4         | 7.55%   |
| Intel Celeron           | 4         | 7.55%   |
| Intel Atom              | 4         | 7.55%   |
| Intel Core i3           | 3         | 5.66%   |
| Intel Pentium           | 2         | 3.77%   |
| Intel Pentium Dual-Core | 1         | 1.89%   |
| Intel Pentium Dual      | 1         | 1.89%   |
| Intel Celeron M         | 1         | 1.89%   |
| AMD Ryzen 7             | 1         | 1.89%   |
| AMD Ryzen 5             | 1         | 1.89%   |
| AMD Phenom II           | 1         | 1.89%   |
| AMD E                   | 1         | 1.89%   |
| AMD Athlon II Dual-Core | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 56.6%   |
| 4      | 15        | 28.3%   |
| 1      | 4         | 7.55%   |
| 6      | 2         | 3.77%   |
| 12     | 1         | 1.89%   |
| 3      | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 60.38%  |
| 1      | 21        | 39.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 96.23%  |
| 32-bit         | 2         | 3.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 39.29%  |
| 0x306a9    | 3         | 5.36%   |
| 0x806ea    | 2         | 3.57%   |
| 0x806c1    | 2         | 3.57%   |
| 0x706e5    | 2         | 3.57%   |
| 0x406e3    | 2         | 3.57%   |
| 0x40651    | 2         | 3.57%   |
| 0x306d4    | 2         | 3.57%   |
| 0x20655    | 2         | 3.57%   |
| 0x106ca    | 2         | 3.57%   |
| 0x1067a    | 2         | 3.57%   |
| 0x906ea    | 1         | 1.79%   |
| 0x906e9    | 1         | 1.79%   |
| 0x6fd      | 1         | 1.79%   |
| 0x6fa      | 1         | 1.79%   |
| 0x6d8      | 1         | 1.79%   |
| 0x506e3    | 1         | 1.79%   |
| 0x506c9    | 1         | 1.79%   |
| 0x206a7    | 1         | 1.79%   |
| 0x106c2    | 1         | 1.79%   |
| 0x10676    | 1         | 1.79%   |
| 0x08600106 | 1         | 1.79%   |
| 0x08108109 | 1         | 1.79%   |
| 0x010000c8 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 13.21%  |
| IvyBridge        | 6         | 11.32%  |
| Penryn           | 4         | 7.55%   |
| Core             | 4         | 7.55%   |
| Bonnell          | 4         | 7.55%   |
| Westmere         | 3         | 5.66%   |
| Skylake          | 3         | 5.66%   |
| SandyBridge      | 3         | 5.66%   |
| Haswell          | 3         | 5.66%   |
| TigerLake        | 2         | 3.77%   |
| K10              | 2         | 3.77%   |
| IceLake          | 2         | 3.77%   |
| Broadwell        | 2         | 3.77%   |
| Zen+             | 1         | 1.89%   |
| Zen 2            | 1         | 1.89%   |
| Zen              | 1         | 1.89%   |
| Silvermont       | 1         | 1.89%   |
| P6               | 1         | 1.89%   |
| Goldmont         | 1         | 1.89%   |
| Bobcat           | 1         | 1.89%   |
| Alderlake Hybrid | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 69.84%  |
| Nvidia | 10        | 15.87%  |
| AMD    | 9         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 8.96%   |
| Intel UHD Graphics 620                                                        | 4         | 5.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 4.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 4.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 4.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 4.48%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 4.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 1         | 1.49%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 1.49%   |
| Nvidia GM108M [GeForce 930MX]                                                 | 1         | 1.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.49%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 1.49%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.49%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 1.49%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.49%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.49%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 1.49%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.49%   |
| Intel HD Graphics 630                                                         | 1         | 1.49%   |
| Intel HD Graphics 5500                                                        | 1         | 1.49%   |
| Intel HD Graphics 530                                                         | 1         | 1.49%   |
| Intel HD Graphics                                                             | 1         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.49%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.49%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 1.49%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 1.49%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 1.49%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]              | 1         | 1.49%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                       | 1         | 1.49%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 1.49%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 50%     |
| Intel + Nvidia | 8         | 14.81%  |
| 2 x Intel      | 7         | 12.96%  |
| 1 x AMD        | 7         | 12.96%  |
| 1 x Nvidia     | 3         | 5.56%   |
| Intel + AMD    | 2         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 52        | 98.11%  |
| Unknown | 1         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 66.04%  |
| 0.01-0.5   | 8         | 15.09%  |
| 1.01-2.0   | 4         | 7.55%   |
| 3.01-4.0   | 3         | 5.66%   |
| 7.01-8.0   | 1         | 1.89%   |
| 2.01-3.0   | 1         | 1.89%   |
| 0.51-1.0   | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 33.33%  |
| LG Display              | 12        | 22.22%  |
| Chimei Innolux          | 5         | 9.26%   |
| Chi Mei Optoelectronics | 4         | 7.41%   |
| BOE                     | 4         | 7.41%   |
| Samsung Electronics     | 2         | 3.7%    |
| LG Philips              | 2         | 3.7%    |
| Sharp                   | 1         | 1.85%   |
| Lenovo                  | 1         | 1.85%   |
| JDI                     | 1         | 1.85%   |
| Insignia                | 1         | 1.85%   |
| EQV                     | 1         | 1.85%   |
| Apple                   | 1         | 1.85%   |
| AOC                     | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 3.7%    |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 2         | 3.7%    |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch             | 2         | 3.7%    |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch      | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch     | 1         | 1.85%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 1         | 1.85%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch               | 1         | 1.85%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 1         | 1.85%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.85%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                   | 1         | 1.85%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                     | 1         | 1.85%   |
| Insignia NS-32D220NA18 BBY0050 1680x1050 708x398mm 32.0-inch              | 1         | 1.85%   |
| EQV LCD Monitor EQV1080 1920x1080 477x268mm 21.5-inch                     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch  | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 1         | 1.85%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE08F2 1920x1080 310x174mm 14.0-inch                     | 1         | 1.85%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                      | 1         | 1.85%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch             | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 36.54%  |
| 1366x768 (WXGA)    | 18        | 34.62%  |
| 1600x900 (HD+)     | 4         | 7.69%   |
| 1280x800 (WXGA)    | 4         | 7.69%   |
| 1024x600           | 4         | 7.69%   |
| 1920x1200 (WUXGA)  | 1         | 1.92%   |
| 1680x1050 (WSXGA+) | 1         | 1.92%   |
| 1440x900 (WXGA+)   | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 38.89%  |
| 14     | 11        | 20.37%  |
| 17     | 5         | 9.26%   |
| 10     | 4         | 7.41%   |
| 13     | 3         | 5.56%   |
| 11     | 3         | 5.56%   |
| 12     | 2         | 3.7%    |
| 54     | 1         | 1.85%   |
| 34     | 1         | 1.85%   |
| 22     | 1         | 1.85%   |
| 21     | 1         | 1.85%   |
| 16     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 59.26%  |
| 201-300     | 11        | 20.37%  |
| 351-400     | 7         | 12.96%  |
| 401-500     | 2         | 3.7%    |
| 701-800     | 1         | 1.85%   |
| 1001-1500   | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 86.27%  |
| 16/10 | 7         | 13.73%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 38.89%  |
| 81-90          | 13        | 24.07%  |
| 41-50          | 4         | 7.41%   |
| 121-130        | 4         | 7.41%   |
| 51-60          | 3         | 5.56%   |
| 61-70          | 2         | 3.7%    |
| More than 1000 | 1         | 1.85%   |
| 71-80          | 1         | 1.85%   |
| 201-250        | 1         | 1.85%   |
| 151-200        | 1         | 1.85%   |
| 131-140        | 1         | 1.85%   |
| 111-120        | 1         | 1.85%   |
| 501-1000       | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 40.74%  |
| 101-120 | 20        | 37.04%  |
| 51-100  | 7         | 12.96%  |
| 161-240 | 3         | 5.56%   |
| 1-50    | 2         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 90.74%  |
| 2     | 4         | 7.41%   |
| 0     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 24        | 26.97%  |
| Intel                           | 24        | 26.97%  |
| Qualcomm Atheros                | 19        | 21.35%  |
| Broadcom                        | 11        | 12.36%  |
| Marvell Technology Group        | 2         | 2.25%   |
| Broadcom Limited                | 2         | 2.25%   |
| Samsung Electronics             | 1         | 1.12%   |
| Research In Motion              | 1         | 1.12%   |
| Ralink                          | 1         | 1.12%   |
| Qualcomm Atheros Communications | 1         | 1.12%   |
| ICS Advent                      | 1         | 1.12%   |
| Dell                            | 1         | 1.12%   |
| Cal-Comp Electronic             | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 12        | 11.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 7         | 6.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 4.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 2.88%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.88%   |
| Intel Wireless 8260                                                                   | 3         | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.92%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 1.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 1.92%   |
| Intel Wireless 7260                                                                   | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.92%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.92%   |
| Intel 82567LM Gigabit Network Connection                                              | 2         | 1.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 2         | 1.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                           | 1         | 0.96%   |
| Research In Motion BlackBerry                                                         | 1         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.96%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.96%   |
| Realtek 802.11ac NIC                                                                  | 1         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 0.96%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.96%   |
| Intel Wireless 7265                                                                   | 1         | 0.96%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.96%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.96%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 38.89%  |
| Qualcomm Atheros                | 17        | 31.48%  |
| Broadcom                        | 9         | 16.67%  |
| Realtek Semiconductor           | 5         | 9.26%   |
| Ralink                          | 1         | 1.85%   |
| Qualcomm Atheros Communications | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 9.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 7.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 5.56%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 5.56%   |
| Intel Wireless 8260                                                                   | 3         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 3.7%    |
| Intel Wireless 7260                                                                   | 2         | 3.7%    |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 3.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 2         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.85%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.85%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.85%   |
| Intel Wireless 7265                                                                   | 1         | 1.85%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.85%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.85%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 43.48%  |
| Intel                    | 13        | 28.26%  |
| Qualcomm Atheros         | 4         | 8.7%    |
| Broadcom                 | 3         | 6.52%   |
| Marvell Technology Group | 2         | 4.35%   |
| Broadcom Limited         | 2         | 4.35%   |
| Research In Motion       | 1         | 2.17%   |
| ICS Advent               | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 26.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 15.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 6.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 4.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 4.35%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 4.35%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 4.35%   |
| Research In Motion BlackBerry                                          | 1         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 2.17%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.17%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 2.17%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.17%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.17%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 2.17%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 52%     |
| Ethernet | 44        | 44%     |
| Modem    | 4         | 4%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 70.18%  |
| Ethernet | 17        | 29.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 77.36%  |
| 1     | 11        | 20.75%  |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 64.15%  |
| Yes  | 19        | 35.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 35.9%   |
| Qualcomm Atheros Communications | 6         | 15.38%  |
| Lite-On Technology              | 5         | 12.82%  |
| Broadcom                        | 3         | 7.69%   |
| IMC Networks                    | 2         | 5.13%   |
| Dell                            | 2         | 5.13%   |
| Apple                           | 2         | 5.13%   |
| Toshiba                         | 1         | 2.56%   |
| Realtek Semiconductor           | 1         | 2.56%   |
| Ralink                          | 1         | 2.56%   |
| Hewlett-Packard                 | 1         | 2.56%   |
| Foxconn / Hon Hai               | 1         | 2.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 9         | 23.08%  |
| Qualcomm Atheros AR3011 Bluetooth                  | 3         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 5.13%   |
| Lite-On Atheros AR3012 Bluetooth                   | 2         | 5.13%   |
| Intel AX201 Bluetooth                              | 2         | 5.13%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 2         | 5.13%   |
| Toshiba Integrated Bluetooth HCI                   | 1         | 2.56%   |
| Realtek Bluetooth Radio                            | 1         | 2.56%   |
| Ralink RT3290 Bluetooth                            | 1         | 2.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 2.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 2.56%   |
| Lite-On Bluetooth USB Host Controller              | 1         | 2.56%   |
| Lite-On Bluetooth Radio                            | 1         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 2.56%   |
| IMC Networks Bluetooth Device                      | 1         | 2.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 1         | 2.56%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                 | 1         | 2.56%   |
| Dell DW375 Bluetooth Module                        | 1         | 2.56%   |
| Dell BCM20702A0 Bluetooth Module                   | 1         | 2.56%   |
| Broadcom BCM20702A0                                | 1         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 2.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 2.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 47        | 75.81%  |
| AMD               | 8         | 12.9%   |
| Nvidia            | 5         | 8.06%   |
| Texas Instruments | 1         | 1.61%   |
| JMTek             | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 8.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 8.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 6.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 5.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.11%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.11%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 3         | 4.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.74%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.74%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 1.37%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.37%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.37%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.37%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.37%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.37%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.37%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 1.37%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.37%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 12        | 19.05%  |
| Unknown                      | 10        | 15.87%  |
| Samsung Electronics          | 10        | 15.87%  |
| Kingston                     | 7         | 11.11%  |
| Micron Technology            | 6         | 9.52%   |
| Elpida                       | 4         | 6.35%   |
| A-DATA Technology            | 4         | 6.35%   |
| Crucial                      | 3         | 4.76%   |
| Ramaxel Technology           | 2         | 3.17%   |
| Unknown (0xFFFF000000000000) | 1         | 1.59%   |
| Toshiba                      | 1         | 1.59%   |
| Timetec                      | 1         | 1.59%   |
| Nanya Technology             | 1         | 1.59%   |
| ASint Technology             | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 4.41%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 2         | 2.94%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 1.47%   |
| Unknown (0xFFFF000000000000) RAM Module 2GB SODIMM DDR2 667MT/s  | 1         | 1.47%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 1         | 1.47%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 1         | 1.47%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 1.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 1.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.47%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Ramaxel RAM RMSA3230KE68H9F2133 4GB SODIMM DDR4 2133MT/s         | 1         | 1.47%   |
| Ramaxel RAM RMN1150LA38D6F-667 512MB SODIMM DDR2 667MT/s         | 1         | 1.47%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 21        | 42.86%  |
| DDR4   | 14        | 28.57%  |
| DDR2   | 10        | 20.41%  |
| LPDDR4 | 3         | 6.12%   |
| LPDDR3 | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 86.27%  |
| Row Of Chips | 4         | 7.84%   |
| Unknown      | 2         | 3.92%   |
| Chip         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 18        | 32.73%  |
| 2048  | 16        | 29.09%  |
| 8192  | 13        | 23.64%  |
| 1024  | 3         | 5.45%   |
| 32768 | 2         | 3.64%   |
| 16384 | 2         | 3.64%   |
| 512   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 23.64%  |
| 667     | 8         | 14.55%  |
| 2667    | 6         | 10.91%  |
| 3200    | 4         | 7.27%   |
| 2400    | 4         | 7.27%   |
| 1334    | 3         | 5.45%   |
| 1333    | 3         | 5.45%   |
| 1067    | 2         | 3.64%   |
| 533     | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| 8400    | 1         | 1.82%   |
| 4267    | 1         | 1.82%   |
| 4266    | 1         | 1.82%   |
| 2267    | 1         | 1.82%   |
| 2133    | 1         | 1.82%   |
| 1867    | 1         | 1.82%   |
| 1066    | 1         | 1.82%   |
| 975     | 1         | 1.82%   |

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
| Chicony Electronics                    | 15        | 35.71%  |
| Microdia                               | 4         | 9.52%   |
| Sunplus Innovation Technology          | 3         | 7.14%   |
| Realtek Semiconductor                  | 3         | 7.14%   |
| IMC Networks                           | 2         | 4.76%   |
| Bison Electronics                      | 2         | 4.76%   |
| Apple                                  | 2         | 4.76%   |
| ALi                                    | 2         | 4.76%   |
| Syntek                                 | 1         | 2.38%   |
| Suyin                                  | 1         | 2.38%   |
| Sonix Technology                       | 1         | 2.38%   |
| Ricoh                                  | 1         | 2.38%   |
| Quanta                                 | 1         | 2.38%   |
| Primax Electronics                     | 1         | 2.38%   |
| Luxvisions Innotech Limited            | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 3         | 7.14%   |
| Chicony USB 2.0 Camera                              | 2         | 4.76%   |
| Chicony HD WebCam (Acer)                            | 2         | 4.76%   |
| Syntek Integrated Camera                            | 1         | 2.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 2.38%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 2.38%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.38%   |
| Sunplus HD WebCam                                   | 1         | 2.38%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 2.38%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.38%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.38%   |
| Realtek EasyCamera                                  | 1         | 2.38%   |
| Realtek 2SF022                                      | 1         | 2.38%   |
| Quanta HD User Facing                               | 1         | 2.38%   |
| Primax webcam                                       | 1         | 2.38%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 2.38%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.38%   |
| Microdia Integrated Webcam                          | 1         | 2.38%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 2.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.38%   |
| Lite-On Integrated Camera                           | 1         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.38%   |
| IMC Networks Integrated Camera                      | 1         | 2.38%   |
| Chicony WebCam                                      | 1         | 2.38%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.38%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.38%   |
| Chicony Integrated Camera                           | 1         | 2.38%   |
| Chicony HP Integrated Webcam                        | 1         | 2.38%   |
| Chicony HP HD Camera                                | 1         | 2.38%   |
| Chicony EasyCamera                                  | 1         | 2.38%   |
| Chicony Camera                                      | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.38%   |
| Bison Integrated Camera                             | 1         | 2.38%   |
| Bison BisonCam, NB Pro                              | 1         | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.38%   |
| Apple Built-in iSight                               | 1         | 2.38%   |
| ALi WebCam                                          | 1         | 2.38%   |
| ALi Gateway Webcam                                  | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 40%     |
| Validity Sensors      | 1         | 20%     |
| Synaptics             | 1         | 20%     |
| Focal-systems.Corp    | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor  | 2         | 40%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Synaptics Prometheus Fingerprint Reader    | 1         | 20%     |
| Focal-systems.Corp FT9201Fingerprint.Ì  | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 71.7%   |
| 1     | 13        | 24.53%  |
| 2     | 2         | 3.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 29.41%  |
| Fingerprint reader    | 5         | 29.41%  |
| Camera                | 2         | 11.76%  |
| Storage               | 1         | 5.88%   |
| Net/wireless          | 1         | 5.88%   |
| Multimedia controller | 1         | 5.88%   |
| Chipcard              | 1         | 5.88%   |
| Bluetooth             | 1         | 5.88%   |

