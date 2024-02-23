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

Total: 44

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lilidog 23 | 24        | 60%     |
| Lilidog 22 | 16        | 40%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lilidog | 38        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.5.0-0.deb12.4-amd64     | 7         | 16.28%  |
| 6.1.0-9-amd64             | 5         | 11.63%  |
| 5.10.0-15-amd64           | 4         | 9.3%    |
| 6.1.0-10-amd64            | 3         | 6.98%   |
| 5.10.0-16-amd64           | 3         | 6.98%   |
| 6.5.0-0.deb12.1-amd64     | 2         | 4.65%   |
| 6.1.0-16-amd64            | 2         | 4.65%   |
| 5.10.0-21-amd64           | 2         | 4.65%   |
| 5.10.0-18-amd64           | 2         | 4.65%   |
| 6.4.5-1-liquorix-amd64    | 1         | 2.33%   |
| 6.4.0-0.deb12.2-amd64     | 1         | 2.33%   |
| 6.1.0-7-amd64             | 1         | 2.33%   |
| 6.1.0-13-amd64            | 1         | 2.33%   |
| 6.1.0-13-686-pae          | 1         | 2.33%   |
| 6.1.0-11-amd64            | 1         | 2.33%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 2.33%   |
| 6.0.10-x64v1-xanmod1      | 1         | 2.33%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 2.33%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 2.33%   |
| 5.10.0-22-amd64           | 1         | 2.33%   |
| 5.10.0-14-amd64           | 1         | 2.33%   |
| 5.10.0-13-amd64           | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 14        | 35%     |
| 5.10.0  | 12        | 30%     |
| 6.5.0   | 9         | 22.5%   |
| 6.4.5   | 1         | 2.5%    |
| 6.4.0   | 1         | 2.5%    |
| 6.0.10  | 1         | 2.5%    |
| 6.0.0   | 1         | 2.5%    |
| 5.17.0  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 14        | 35%     |
| 5.10    | 12        | 30%     |
| 6.5     | 9         | 22.5%   |
| 6.4     | 2         | 5%      |
| 6.0     | 2         | 5%      |
| 5.17    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 97.37%  |
| i686   | 1         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 31        | 77.5%   |
| openbox          | 9         | 22.5%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 38        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 38        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 22        | 56.41%  |
| de_DE | 4         | 10.26%  |
| pl_PL | 2         | 5.13%   |
| es_ES | 2         | 5.13%   |
| es_CO | 2         | 5.13%   |
| en_GB | 2         | 5.13%   |
| pt_BR | 1         | 2.56%   |
| it_IT | 1         | 2.56%   |
| es_CL | 1         | 2.56%   |
| en_IE | 1         | 2.56%   |
| cs_CZ | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 20        | 52.63%  |
| EFI  | 18        | 47.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 27        | 69.23%  |
| Overlay | 10        | 25.64%  |
| Btrfs   | 2         | 5.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 20        | 51.28%  |
| GPT  | 19        | 48.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 65%     |
| Yes       | 14        | 35%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 81.58%  |
| Yes       | 7         | 18.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Acer             | 8         | 21.05%  |
| Lenovo           | 7         | 18.42%  |
| Hewlett-Packard  | 5         | 13.16%  |
| Dell             | 5         | 13.16%  |
| Panasonic        | 2         | 5.26%   |
| Google           | 2         | 5.26%   |
| ASUSTek Computer | 2         | 5.26%   |
| Apple            | 2         | 5.26%   |
| TUXEDO           | 1         | 2.63%   |
| Toshiba          | 1         | 2.63%   |
| Sony             | 1         | 2.63%   |
| PC Specialist    | 1         | 2.63%   |
| GPU Company      | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 5.26%   |
| TUXEDO N8xEJEK                             | 1         | 2.63%   |
| Toshiba Satellite Pro L450                 | 1         | 2.63%   |
| Sony VPCF23P1E                             | 1         | 2.63%   |
| PC Specialist P65_67RSRP                   | 1         | 2.63%   |
| Panasonic CFMX4-1                          | 1         | 2.63%   |
| Panasonic CF-31ATXAX1M                     | 1         | 2.63%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 2.63%   |
| Lenovo ThinkPad X280 20KES63G00            | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 2.63%   |
| Lenovo ThinkPad T430s 2356GUU              | 1         | 2.63%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 2.63%   |
| Lenovo G500 20236                          | 1         | 2.63%   |
| HP ProBook 6560b                           | 1         | 2.63%   |
| HP Pavilion 11 x360 PC                     | 1         | 2.63%   |
| HP Laptop 15s-fq1xxx                       | 1         | 2.63%   |
| HP G62                                     | 1         | 2.63%   |
| HP 435                                     | 1         | 2.63%   |
| GPU Company GWNR71517                      | 1         | 2.63%   |
| Google Sand                                | 1         | 2.63%   |
| Google Auron_Yuna                          | 1         | 2.63%   |
| Dell Latitude E5440                        | 1         | 2.63%   |
| Dell Latitude 7414                         | 1         | 2.63%   |
| Dell Latitude 7390                         | 1         | 2.63%   |
| Dell Inspiron 3793                         | 1         | 2.63%   |
| Dell Inspiron 1318                         | 1         | 2.63%   |
| ASUS X550VC                                | 1         | 2.63%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 2.63%   |
| Apple MacBookPro3,1                        | 1         | 2.63%   |
| Apple MacBook4,1                           | 1         | 2.63%   |
| Acer V5-131                                | 1         | 2.63%   |
| Acer Aspire one                            | 1         | 2.63%   |
| Acer Aspire E5-573                         | 1         | 2.63%   |
| Acer Aspire E1-470                         | 1         | 2.63%   |
| Acer Aspire 7540                           | 1         | 2.63%   |
| Acer AOD270                                | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 5         | 13.16%  |
| Acer Aspire            | 4         | 10.53%  |
| Dell Latitude          | 3         | 7.89%   |
| Dell Inspiron          | 2         | 5.26%   |
| Acer AOD255E           | 2         | 5.26%   |
| TUXEDO N8xEJEK         | 1         | 2.63%   |
| Toshiba Satellite      | 1         | 2.63%   |
| Sony VPCF23P1E         | 1         | 2.63%   |
| PC Specialist P65      | 1         | 2.63%   |
| Panasonic CFMX4-1      | 1         | 2.63%   |
| Panasonic CF-31ATXAX1M | 1         | 2.63%   |
| Lenovo Yoga            | 1         | 2.63%   |
| Lenovo G500            | 1         | 2.63%   |
| HP ProBook             | 1         | 2.63%   |
| HP Pavilion            | 1         | 2.63%   |
| HP Laptop              | 1         | 2.63%   |
| HP G62                 | 1         | 2.63%   |
| HP 435                 | 1         | 2.63%   |
| GPU Company GWNR71517  | 1         | 2.63%   |
| Google Sand            | 1         | 2.63%   |
| Google Auron           | 1         | 2.63%   |
| ASUS X550VC            | 1         | 2.63%   |
| ASUS VivoBook          | 1         | 2.63%   |
| Apple MacBookPro3      | 1         | 2.63%   |
| Apple MacBook4         | 1         | 2.63%   |
| Acer V5-131            | 1         | 2.63%   |
| Acer AOD270            | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 5         | 13.16%  |
| 2010 | 5         | 13.16%  |
| 2013 | 4         | 10.53%  |
| 2012 | 3         | 7.89%   |
| 2011 | 3         | 7.89%   |
| 2008 | 3         | 7.89%   |
| 2021 | 2         | 5.26%   |
| 2020 | 2         | 5.26%   |
| 2019 | 2         | 5.26%   |
| 2016 | 2         | 5.26%   |
| 2014 | 2         | 5.26%   |
| 2009 | 2         | 5.26%   |
| 2017 | 1         | 2.63%   |
| 2015 | 1         | 2.63%   |
| 2007 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 37        | 97.37%  |
| Enabled  | 1         | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 92.11%  |
| Yes  | 3         | 7.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 31.58%  |
| 3.01-4.0   | 11        | 28.95%  |
| 16.01-24.0 | 5         | 13.16%  |
| 1.01-2.0   | 4         | 10.53%  |
| 8.01-16.0  | 3         | 7.89%   |
| 32.01-64.0 | 1         | 2.63%   |
| 2.01-3.0   | 1         | 2.63%   |
| 0.51-1.0   | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 26        | 66.67%  |
| 1.01-2.0 | 9         | 23.08%  |
| 2.01-3.0 | 4         | 10.26%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 84.62%  |
| 2      | 5         | 12.82%  |
| 4      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 60.53%  |
| Yes       | 15        | 39.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 82.05%  |
| No        | 7         | 17.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 97.37%  |
| No        | 1         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 69.23%  |
| No        | 12        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 23.68%  |
| Germany     | 7         | 18.42%  |
| Spain       | 3         | 7.89%   |
| Poland      | 2         | 5.26%   |
| Netherlands | 2         | 5.26%   |
| Italy       | 2         | 5.26%   |
| Colombia    | 2         | 5.26%   |
| Vietnam     | 1         | 2.63%   |
| UK          | 1         | 2.63%   |
| Thailand    | 1         | 2.63%   |
| Portugal    | 1         | 2.63%   |
| Mexico      | 1         | 2.63%   |
| Kenya       | 1         | 2.63%   |
| Finland     | 1         | 2.63%   |
| Czechia     | 1         | 2.63%   |
| Chile       | 1         | 2.63%   |
| Canada      | 1         | 2.63%   |
| Brazil      | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Fayetteville           | 3         | 7.89%   |
| Milan                  | 2         | 5.26%   |
| Medellín              | 2         | 5.26%   |
| Egan                   | 2         | 5.26%   |
| Denver                 | 2         | 5.26%   |
| Zduny                  | 1         | 2.63%   |
| Viña del Mar          | 1         | 2.63%   |
| Uelzen                 | 1         | 2.63%   |
| Stockton-on-Tees       | 1         | 2.63%   |
| Schiedam               | 1         | 2.63%   |
| Rumia                  | 1         | 2.63%   |
| Rinteln                | 1         | 2.63%   |
| Ratchathewi            | 1         | 2.63%   |
| Poricany               | 1         | 2.63%   |
| Norderstedt            | 1         | 2.63%   |
| Nairobi                | 1         | 2.63%   |
| Morgantown             | 1         | 2.63%   |
| Monclova               | 1         | 2.63%   |
| Madrid                 | 1         | 2.63%   |
| Lisbon                 | 1         | 2.63%   |
| Ho Chi Minh City       | 1         | 2.63%   |
| Helsinki               | 1         | 2.63%   |
| Groningen              | 1         | 2.63%   |
| Filderstadt            | 1         | 2.63%   |
| Eppelborn              | 1         | 2.63%   |
| Edmonton               | 1         | 2.63%   |
| Düsseldorf            | 1         | 2.63%   |
| Darmstadt              | 1         | 2.63%   |
| Charlotte              | 1         | 2.63%   |
| Cervera del Rio Alhama | 1         | 2.63%   |
| Campo Grande           | 1         | 2.63%   |
| Barcelona              | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 15.91%  |
| Seagate             | 6         | 7      | 13.64%  |
| WDC                 | 4         | 5      | 9.09%   |
| Toshiba             | 3         | 4      | 6.82%   |
| Kingston            | 3         | 3      | 6.82%   |
| SanDisk             | 2         | 4      | 4.55%   |
| Crucial             | 2         | 2      | 4.55%   |
| Wibtek              | 1         | 1      | 2.27%   |
| Unknown             | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| Mushkin             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 2      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| KIOXIA              | 1         | 1      | 2.27%   |
| KingSpec            | 1         | 1      | 2.27%   |
| KingFast            | 1         | 1      | 2.27%   |
| Intel               | 1         | 1      | 2.27%   |
| Integral            | 1         | 1      | 2.27%   |
| Hitachi             | 1         | 1      | 2.27%   |
| GOODRAM             | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| Blackpcs            | 1         | 1      | 2.27%   |
| Apacer              | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB             | 2         | 4.35%   |
| Wibtek W800S 512GB SSD                      | 1         | 2.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD            | 1         | 2.17%   |
| WDC WDS100T2B0C-00PXH0 1TB                  | 1         | 2.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 2.17%   |
| WDC WD1600BEVT-22ZCT0 160GB                 | 1         | 2.17%   |
| WDC WD10SPCX-60KHST0 1TB                    | 1         | 2.17%   |
| Unknown NCard  32GB                         | 1         | 2.17%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 2.17%   |
| Toshiba MK6034GSX 64GB                      | 1         | 2.17%   |
| Toshiba MK1665GSX 160GB                     | 1         | 2.17%   |
| Seagate ST9320325AS 320GB                   | 1         | 2.17%   |
| Seagate ST9250315AS 250GB                   | 1         | 2.17%   |
| Seagate ST320LT020-9YG142 320GB             | 1         | 2.17%   |
| Seagate OneTouch HDD 1TB                    | 1         | 2.17%   |
| SanDisk SD8TN8U256G1001 256GB SSD           | 1         | 2.17%   |
| SanDisk DF4032  32GB                        | 1         | 2.17%   |
| Samsung SSD PM841 2.5 7mm 256GB             | 1         | 2.17%   |
| Samsung SSD 970 EVO Plus 250GB              | 1         | 2.17%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.17%   |
| Samsung SSD 860 EVO 1TB                     | 1         | 2.17%   |
| Samsung SSD 850 EVO 250GB                   | 1         | 2.17%   |
| Samsung PM991a NVMe 512GB                   | 1         | 2.17%   |
| Samsung MZVL21T0HCLR-00BL7 1TB              | 1         | 2.17%   |
| Samsung MZNTE128HMGR-00000 128GB SSD        | 1         | 2.17%   |
| PNY 240GB SATA SSD                          | 1         | 2.17%   |
| Mushkin MKNSSDCR120GB                       | 1         | 2.17%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD         | 1         | 2.17%   |
| Lexar SSD NM620 256GB                       | 1         | 2.17%   |
| KIOXIA KBG40ZNV1T02 1TB                     | 1         | 2.17%   |
| Kingston SNS4151S332GD 32GB SSD             | 1         | 2.17%   |
| Kingston SKC3000D2048G 2TB                  | 1         | 2.17%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.17%   |
| KingSpec MT-512 512GB SSD                   | 1         | 2.17%   |
| KingFast SSD 240GB                          | 1         | 2.17%   |
| Intel SSDPEKKF256G8L BTHH831605D3256B 256GB | 1         | 2.17%   |
| Integral V Series SATA SSD 1TB-1000GB       | 1         | 2.17%   |
| Hitachi HTS545016B9SA00 160GB               | 1         | 2.17%   |
| GOODRAM SSDPR-CL100-480-G3 480GB            | 1         | 2.17%   |
| Crucial CT500BX500SSD1 500GB                | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 46.15%  |
| WDC     | 3         | 3      | 23.08%  |
| Toshiba | 3         | 4      | 23.08%  |
| Hitachi | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 21.74%  |
| Kingston            | 2         | 2      | 8.7%    |
| Crucial             | 2         | 2      | 8.7%    |
| Wibtek              | 1         | 1      | 4.35%   |
| WDC                 | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| Mushkin             | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 2      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| KingFast            | 1         | 1      | 4.35%   |
| Integral            | 1         | 1      | 4.35%   |
| GOODRAM             | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| Blackpcs            | 1         | 1      | 4.35%   |
| Apacer              | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 24     | 51.16%  |
| HDD  | 12        | 15     | 27.91%  |
| NVMe | 8         | 9      | 18.6%   |
| MMC  | 1         | 4      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 38     | 75.61%  |
| NVMe | 8         | 9      | 19.51%  |
| SAS  | 1         | 1      | 2.44%   |
| MMC  | 1         | 4      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 81.82%  |
| 0.51-1.0   | 6         | 9      | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 27.5%   |
| 251-500    | 10        | 25%     |
| 1-20       | 10        | 25%     |
| 51-100     | 4         | 10%     |
| 21-50      | 2         | 5%      |
| 1001-2000  | 2         | 5%      |
| 501-1000   | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 33        | 82.5%   |
| 21-50   | 5         | 12.5%   |
| 101-250 | 1         | 2.5%    |
| 51-100  | 1         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 2         | 3      | 33.33%  |
| Toshiba MK1665GSX 160GB         | 1         | 1      | 16.67%  |
| Seagate ST9250315AS 250GB       | 1         | 1      | 16.67%  |
| Mushkin MKNSSDCR120GB           | 1         | 1      | 16.67%  |
| Kingston SNS4151S332GD 32GB SSD | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 4      | 50%     |
| Toshiba  | 1         | 1      | 16.67%  |
| Mushkin  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 75%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
| SSD  | 2         | 2      | 33.33%  |

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
| Works    | 31        | 39     | 77.5%   |
| Malfunc  | 6         | 7      | 15%     |
| Detected | 2         | 5      | 5%      |
| Failed   | 1         | 1      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 75.61%  |
| Samsung Electronics          | 3         | 7.32%   |
| AMD                          | 3         | 7.32%   |
| Shenzhen Longsys Electronics | 1         | 2.44%   |
| SanDisk                      | 1         | 2.44%   |
| KIOXIA                       | 1         | 2.44%   |
| Kingston Technology Company  | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 4         | 8.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 3         | 6.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 3         | 6.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 3         | 6.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 3         | 6.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 4.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 2         | 4.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 4.35%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 2.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                                          | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 1         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 2.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 1         | 2.17%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 2.17%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                                                 | 1         | 2.17%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 1         | 2.17%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                                      | 1         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                                              | 1         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 1         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 1         | 2.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                                                     | 1         | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 1         | 2.17%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                                                    | 1         | 2.17%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                                                    | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 1         | 2.17%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 66.67%  |
| NVMe | 8         | 17.78%  |
| IDE  | 5         | 11.11%  |
| RAID | 2         | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 89.47%  |
| AMD    | 4         | 10.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 5.26%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 5.26%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 5.26%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 2.63%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.63%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 2.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.63%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 2.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.63%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.63%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 2.63%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 2.63%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 1         | 2.63%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 2.63%   |
| Intel Celeron CPU N2820 @ 2.13GHz             | 1         | 2.63%   |
| Intel Celeron CPU B840 @ 1.90GHz              | 1         | 2.63%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2.63%   |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 2.63%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2.63%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 1         | 2.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.63%   |
| AMD Phenom II N830 Triple-Core Processor      | 1         | 2.63%   |
| AMD Athlon II Dual-Core M300                  | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 23.68%  |
| Intel Core i7           | 8         | 21.05%  |
| Intel Core 2 Duo        | 4         | 10.53%  |
| Intel Celeron           | 4         | 10.53%  |
| Intel Atom              | 4         | 10.53%  |
| Intel Pentium           | 2         | 5.26%   |
| Other                   | 1         | 2.63%   |
| Intel Pentium Dual-Core | 1         | 2.63%   |
| Intel Core i3           | 1         | 2.63%   |
| AMD Ryzen 7             | 1         | 2.63%   |
| AMD Ryzen 5             | 1         | 2.63%   |
| AMD Phenom II           | 1         | 2.63%   |
| AMD Athlon II Dual-Core | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 57.89%  |
| 4      | 10        | 26.32%  |
| 1      | 3         | 7.89%   |
| 6      | 2         | 5.26%   |
| 3      | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 63.16%  |
| 1      | 14        | 36.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 97.37%  |
| 32-bit         | 1         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 33.33%  |
| 0x306a9    | 3         | 7.69%   |
| 0x806ea    | 2         | 5.13%   |
| 0x406e3    | 2         | 5.13%   |
| 0x40651    | 2         | 5.13%   |
| 0x306d4    | 2         | 5.13%   |
| 0x106ca    | 2         | 5.13%   |
| 0x906ea    | 1         | 2.56%   |
| 0x806c1    | 1         | 2.56%   |
| 0x706e5    | 1         | 2.56%   |
| 0x6fa      | 1         | 2.56%   |
| 0x506c9    | 1         | 2.56%   |
| 0x206a7    | 1         | 2.56%   |
| 0x20655    | 1         | 2.56%   |
| 0x106c2    | 1         | 2.56%   |
| 0x1067a    | 1         | 2.56%   |
| 0x10676    | 1         | 2.56%   |
| 0x08600106 | 1         | 2.56%   |
| 0x08108109 | 1         | 2.56%   |
| 0x010000c8 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 5         | 13.16%  |
| KabyLake    | 4         | 10.53%  |
| Bonnell     | 4         | 10.53%  |
| Skylake     | 3         | 7.89%   |
| Penryn      | 3         | 7.89%   |
| Westmere    | 2         | 5.26%   |
| SandyBridge | 2         | 5.26%   |
| K10         | 2         | 5.26%   |
| IceLake     | 2         | 5.26%   |
| Haswell     | 2         | 5.26%   |
| Core        | 2         | 5.26%   |
| Broadwell   | 2         | 5.26%   |
| Zen+        | 1         | 2.63%   |
| Zen 2       | 1         | 2.63%   |
| TigerLake   | 1         | 2.63%   |
| Silvermont  | 1         | 2.63%   |
| Goldmont    | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 72.09%  |
| Nvidia | 6         | 13.95%  |
| AMD    | 6         | 13.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 10.87%  |
| Intel UHD Graphics 620                                                        | 3         | 6.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 4.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 4.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 4.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 4.35%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 4.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 2.17%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 2.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 2.17%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 2.17%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 2.17%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 2.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 2.17%   |
| Intel HD Graphics 5500                                                        | 1         | 2.17%   |
| Intel HD Graphics                                                             | 1         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 2.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.17%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.17%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]              | 1         | 2.17%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                     | 1         | 2.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 1         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.17%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 2.17%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 57.89%  |
| 2 x Intel      | 4         | 10.53%  |
| 1 x AMD        | 4         | 10.53%  |
| 1 x Nvidia     | 3         | 7.89%   |
| Intel + Nvidia | 3         | 7.89%   |
| Intel + AMD    | 2         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 37        | 97.37%  |
| Unknown | 1         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 71.05%  |
| 0.01-0.5   | 5         | 13.16%  |
| 1.01-2.0   | 3         | 7.89%   |
| 3.01-4.0   | 2         | 5.26%   |
| 7.01-8.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 36.84%  |
| LG Display              | 7         | 18.42%  |
| Chimei Innolux          | 5         | 13.16%  |
| Chi Mei Optoelectronics | 3         | 7.89%   |
| BOE                     | 2         | 5.26%   |
| Sharp                   | 1         | 2.63%   |
| Samsung Electronics     | 1         | 2.63%   |
| Lenovo                  | 1         | 2.63%   |
| JDI                     | 1         | 2.63%   |
| EQV                     | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |
| AOC                     | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 5.26%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 2.63%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch               | 1         | 2.63%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch               | 1         | 2.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                   | 1         | 2.63%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                     | 1         | 2.63%   |
| EQV LCD Monitor EQV1080 1920x1080 477x268mm 21.5-inch                     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 290x170mm 13.2-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1600 1920x1080 374x192mm 16.6-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 2.63%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                      | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch             | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 1         | 2.63%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 1         | 2.63%   |
| AOC 2219 AOC2219 1680x1050 474x296mm 22.0-inch                            | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 15        | 40.54%  |
| 1920x1080 (FHD)    | 12        | 32.43%  |
| 1024x600           | 4         | 10.81%  |
| 1600x900 (HD+)     | 2         | 5.41%   |
| 1280x800 (WXGA)    | 2         | 5.41%   |
| 1920x1200 (WUXGA)  | 1         | 2.7%    |
| 1680x1050 (WSXGA+) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 31.58%  |
| 14     | 8         | 21.05%  |
| 17     | 4         | 10.53%  |
| 10     | 4         | 10.53%  |
| 13     | 3         | 7.89%   |
| 12     | 2         | 5.26%   |
| 11     | 2         | 5.26%   |
| 22     | 1         | 2.63%   |
| 21     | 1         | 2.63%   |
| 16     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 52.63%  |
| 201-300     | 10        | 26.32%  |
| 351-400     | 6         | 15.79%  |
| 401-500     | 2         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 89.19%  |
| 16/10 | 4         | 10.81%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 31.58%  |
| 81-90          | 10        | 26.32%  |
| 41-50          | 4         | 10.53%  |
| 121-130        | 4         | 10.53%  |
| 61-70          | 2         | 5.26%   |
| 51-60          | 2         | 5.26%   |
| 71-80          | 1         | 2.63%   |
| 201-250        | 1         | 2.63%   |
| 151-200        | 1         | 2.63%   |
| 111-120        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 42.11%  |
| 121-160 | 14        | 36.84%  |
| 51-100  | 5         | 13.16%  |
| 161-240 | 3         | 7.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 92.31%  |
| 2     | 2         | 5.13%   |
| 0     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 27.42%  |
| Realtek Semiconductor           | 16        | 25.81%  |
| Qualcomm Atheros                | 15        | 24.19%  |
| Broadcom                        | 8         | 12.9%   |
| Marvell Technology Group        | 2         | 3.23%   |
| Research In Motion              | 1         | 1.61%   |
| Ralink                          | 1         | 1.61%   |
| Qualcomm Atheros Communications | 1         | 1.61%   |
| ICS Advent                      | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 6         | 8.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 6         | 8.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 4.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 4.11%   |
| Intel Wireless 8260                                                                   | 3         | 4.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.74%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 2.74%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 2.74%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.74%   |
| Intel Wireless 7260                                                                   | 2         | 2.74%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 2.74%   |
| Research In Motion BlackBerry                                                         | 1         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.37%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 1.37%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 1.37%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.37%   |
| Intel Wireless 7265                                                                   | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.37%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 1.37%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 1.37%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.37%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 1.37%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 1.37%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 35.9%   |
| Qualcomm Atheros                | 13        | 33.33%  |
| Broadcom                        | 6         | 15.38%  |
| Realtek Semiconductor           | 4         | 10.26%  |
| Ralink                          | 1         | 2.56%   |
| Qualcomm Atheros Communications | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 7.69%   |
| Intel Wireless 8260                                                                   | 3         | 7.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 5.13%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 5.13%   |
| Intel Wireless 7260                                                                   | 2         | 5.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.56%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 2.56%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.56%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 2.56%   |
| Intel Wireless 7265                                                                   | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 2.56%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 2.56%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.56%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 2.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 2.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 13        | 38.24%  |
| Intel                    | 10        | 29.41%  |
| Qualcomm Atheros         | 4         | 11.76%  |
| Broadcom                 | 3         | 8.82%   |
| Marvell Technology Group | 2         | 5.88%   |
| Research In Motion       | 1         | 2.94%   |
| ICS Advent               | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6         | 17.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 17.65%  |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 5.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 5.88%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 5.88%   |
| Research In Motion BlackBerry                                          | 1         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 2.94%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.94%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.94%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 2.94%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.94%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 2.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 53.62%  |
| Ethernet | 32        | 46.38%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 65.85%  |
| Ethernet | 14        | 34.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 76.32%  |
| 1     | 8         | 21.05%  |
| 0     | 1         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 57.89%  |
| Yes  | 16        | 42.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 40.74%  |
| Lite-On Technology              | 4         | 14.81%  |
| Qualcomm Atheros Communications | 3         | 11.11%  |
| IMC Networks                    | 2         | 7.41%   |
| Broadcom                        | 2         | 7.41%   |
| Apple                           | 2         | 7.41%   |
| Realtek Semiconductor           | 1         | 3.7%    |
| Ralink                          | 1         | 3.7%    |
| Hewlett-Packard                 | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 8         | 29.63%  |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 7.41%   |
| Lite-On Atheros AR3012 Bluetooth                   | 2         | 7.41%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 2         | 7.41%   |
| Realtek Bluetooth Radio                            | 1         | 3.7%    |
| Ralink RT3290 Bluetooth                            | 1         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 3.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 3.7%    |
| Lite-On Bluetooth USB Host Controller              | 1         | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 3.7%    |
| Intel AX201 Bluetooth                              | 1         | 3.7%    |
| IMC Networks Bluetooth Device                      | 1         | 3.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 1         | 3.7%    |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 3.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 3.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 79.07%  |
| AMD    | 5         | 11.63%  |
| Nvidia | 3         | 6.98%   |
| JMTek  | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 9.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 9.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 7.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 5.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 3.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.92%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.92%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.96%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.96%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 8         | 19.05%  |
| Unknown                      | 7         | 16.67%  |
| Samsung Electronics          | 5         | 11.9%   |
| Micron Technology            | 5         | 11.9%   |
| Kingston                     | 4         | 9.52%   |
| Elpida                       | 4         | 9.52%   |
| A-DATA Technology            | 4         | 9.52%   |
| Unknown (0xFFFF000000000000) | 1         | 2.38%   |
| Toshiba                      | 1         | 2.38%   |
| Timetec                      | 1         | 2.38%   |
| Nanya Technology             | 1         | 2.38%   |
| Crucial                      | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 4.44%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 2.22%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 2.22%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 2.22%   |
| Unknown (0xFFFF000000000000) RAM Module 2GB SODIMM DDR2 667MT/s  | 1         | 2.22%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 1         | 2.22%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 1         | 2.22%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.22%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 2.22%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 2.22%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.22%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.22%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.22%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 2.22%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 1         | 2.22%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 2.22%   |
| Micron RAM MT53B256M32D1NP 1GB LPDDR4 2400MT/s                   | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8192MB SODIMM DDR4 2400MT/s          | 1         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.22%   |
| Kingston RAM KHX2133C13S4/8G 8GB SODIMM DDR4 2133MT/s            | 1         | 2.22%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.22%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 1         | 2.22%   |
| Kingston RAM 9905295-045.A01LF 2GB SODIMM DDR 667MT/s            | 1         | 2.22%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB SODIMM LPDDR3 1867MT/s           | 1         | 2.22%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB Chip LPDDR3 1867MT/s             | 1         | 2.22%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 2.22%   |
| Elpida RAM EBJ40UG8EFU0 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.22%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.22%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 47.06%  |
| DDR4   | 8         | 23.53%  |
| DDR2   | 6         | 17.65%  |
| LPDDR4 | 3         | 8.82%   |
| LPDDR3 | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 85.71%  |
| Row Of Chips | 2         | 5.71%   |
| Unknown      | 2         | 5.71%   |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 37.14%  |
| 2048  | 12        | 34.29%  |
| 8192  | 7         | 20%     |
| 1024  | 2         | 5.71%   |
| 16384 | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 25%     |
| 667     | 6         | 16.67%  |
| 2667    | 4         | 11.11%  |
| 2400    | 3         | 8.33%   |
| 1334    | 2         | 5.56%   |
| 1067    | 2         | 5.56%   |
| 8400    | 1         | 2.78%   |
| 4267    | 1         | 2.78%   |
| 4266    | 1         | 2.78%   |
| 2133    | 1         | 2.78%   |
| 1867    | 1         | 2.78%   |
| 1333    | 1         | 2.78%   |
| 1066    | 1         | 2.78%   |
| 975     | 1         | 2.78%   |
| 533     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

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
| Chicony Electronics                    | 11        | 36.67%  |
| Microdia                               | 3         | 10%     |
| Sunplus Innovation Technology          | 2         | 6.67%   |
| Realtek Semiconductor                  | 2         | 6.67%   |
| IMC Networks                           | 2         | 6.67%   |
| Apple                                  | 2         | 6.67%   |
| ALi                                    | 2         | 6.67%   |
| Acer                                   | 2         | 6.67%   |
| Suyin                                  | 1         | 3.33%   |
| Ricoh                                  | 1         | 3.33%   |
| Luxvisions Innotech Limited            | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam (Acer)                            | 2         | 6.67%   |
| Chicony HD WebCam                                   | 2         | 6.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 3.33%   |
| Sunplus HD WebCam                                   | 1         | 3.33%   |
| Ricoh USB2.0 Camera                                 | 1         | 3.33%   |
| Realtek USB Camera                                  | 1         | 3.33%   |
| Realtek Lenovo EasyCamera                           | 1         | 3.33%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.33%   |
| Microdia Integrated Webcam                          | 1         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.33%   |
| IMC Networks Integrated Camera                      | 1         | 3.33%   |
| Chicony WebCam                                      | 1         | 3.33%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.33%   |
| Chicony USB 2.0 Camera                              | 1         | 3.33%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.33%   |
| Chicony Integrated Camera                           | 1         | 3.33%   |
| Chicony HP Webcam-101                               | 1         | 3.33%   |
| Chicony Camera                                      | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 3.33%   |
| Apple Built-in iSight                               | 1         | 3.33%   |
| ALi WebCam                                          | 1         | 3.33%   |
| ALi Gateway Webcam                                  | 1         | 3.33%   |
| Acer Integrated Camera                              | 1         | 3.33%   |
| Acer BisonCam, NB Pro                               | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 66.67%  |
| Focal-systems.Corp    | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 2         | 66.67%  |
| Focal-systems.Corp FT9201Fingerprint.Ì | 1         | 33.33%  |

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
| 0     | 26        | 68.42%  |
| 1     | 12        | 31.58%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 33.33%  |
| Fingerprint reader    | 3         | 25%     |
| Net/wireless          | 1         | 8.33%   |
| Multimedia controller | 1         | 8.33%   |
| Chipcard              | 1         | 8.33%   |
| Camera                | 1         | 8.33%   |
| Bluetooth             | 1         | 8.33%   |

