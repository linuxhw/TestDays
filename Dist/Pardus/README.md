Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI           | MS-7360                     | Desktop     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| MSI           | MS-7360                     | Desktop     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pardus 21.2   | 9         | 16.98%  |
| Pardus 21.3   | 8         | 15.09%  |
| Pardus 21.1   | 6         | 11.32%  |
| Pardus 21.4   | 5         | 9.43%   |
| Pardus 19.5   | 5         | 9.43%   |
| Pardus 21.0   | 4         | 7.55%   |
| Pardus 19.4-1 | 3         | 5.66%   |
| Pardus 19.4   | 3         | 5.66%   |
| Pardus 19.3   | 3         | 5.66%   |
| Pardus 19.2   | 3         | 5.66%   |
| Pardus 19.1   | 2         | 3.77%   |
| Pardus 19.0   | 2         | 3.77%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 49        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-13-amd64           | 6         | 11.11%  |
| 5.10.0-19-amd64           | 4         | 7.41%   |
| 5.10.0-20-amd64           | 3         | 5.56%   |
| 5.10.0-11-amd64           | 3         | 5.56%   |
| 4.19.0-6-amd64            | 3         | 5.56%   |
| 4.19.0-13-amd64           | 3         | 5.56%   |
| 4.19.0-10-amd64           | 3         | 5.56%   |
| 5.9.0-0.bpo.2-amd64       | 2         | 3.7%    |
| 5.10.0-9-amd64            | 2         | 3.7%    |
| 5.10.0-8-amd64            | 2         | 3.7%    |
| 5.10.0-21-amd64           | 2         | 3.7%    |
| 5.10.0-16-amd64           | 2         | 3.7%    |
| 5.10.0-14-amd64           | 2         | 3.7%    |
| 5.10.0-10-amd64           | 2         | 3.7%    |
| 4.19.0-8-amd64            | 2         | 3.7%    |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 1.85%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 1.85%   |
| 5.10.0-18-amd64           | 1         | 1.85%   |
| 5.10.0-17-amd64           | 1         | 1.85%   |
| 5.10.0-15-amd64           | 1         | 1.85%   |
| 5.10.0-12-amd64           | 1         | 1.85%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 1.85%   |
| 4.19.0-5-amd64            | 1         | 1.85%   |
| 4.19.0-19-amd64           | 1         | 1.85%   |
| 4.19.0-18-amd64           | 1         | 1.85%   |
| 4.19.0-17-amd64           | 1         | 1.85%   |
| 4.19.0-16-amd64           | 1         | 1.85%   |
| 4.19.0-12-amd64           | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 31        | 60.78%  |
| 4.19.0  | 16        | 31.37%  |
| 5.9.0   | 2         | 3.92%   |
| 6.0.11  | 1         | 1.96%   |
| 5.4.0   | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 31        | 60.78%  |
| 4.19    | 16        | 31.37%  |
| 5.9     | 2         | 3.92%   |
| 6.0     | 1         | 1.96%   |
| 5.4     | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 32        | 64%     |
| GNOME      | 13        | 26%     |
| KDE5       | 2         | 4%      |
| Unknown    | 2         | 4%      |
| X-Cinnamon | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 49        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 64%     |
| TDM     | 6         | 12%     |
| GDM     | 6         | 12%     |
| LightDM | 5         | 10%     |
| SDDM    | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 39        | 78%     |
| en_US   | 3         | 6%      |
| Unknown | 3         | 6%      |
| pt_BR   | 1         | 2%      |
| hu_HU   | 1         | 2%      |
| fur_IT  | 1         | 2%      |
| fr_FR   | 1         | 2%      |
| en_GB   | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 38        | 74.51%  |
| EFI  | 13        | 25.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 97.96%  |
| Overlay | 1         | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 70%     |
| GPT     | 13        | 26%     |
| MBR     | 2         | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 93.88%  |
| Yes       | 3         | 6.12%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 83.67%  |
| Yes       | 8         | 16.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 24.49%  |
| MSI                 | 6         | 12.24%  |
| Hewlett-Packard     | 6         | 12.24%  |
| ASUSTek Computer    | 6         | 12.24%  |
| Toshiba             | 3         | 6.12%   |
| Acer                | 3         | 6.12%   |
| Sony                | 2         | 4.08%   |
| Packard Bell        | 2         | 4.08%   |
| Gigabyte Technology | 2         | 4.08%   |
| Dell                | 2         | 4.08%   |
| TUXEDO              | 1         | 2.04%   |
| Samsung Electronics | 1         | 2.04%   |
| Philco              | 1         | 2.04%   |
| Olidata             | 1         | 2.04%   |
| HUAWEI              | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 3         | 6.12%   |
| Toshiba Satellite C855-1VM                 | 1         | 2.04%   |
| Toshiba Satellite C660                     | 1         | 2.04%   |
| Toshiba PORTEGE M780                       | 1         | 2.04%   |
| Sony SVF1521QSTB                           | 1         | 2.04%   |
| Sony SVE14A2V2ES                           | 1         | 2.04%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.04%   |
| Philco 14F                                 | 1         | 2.04%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.04%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.04%   |
| Olidata T7700                              | 1         | 2.04%   |
| MSI MS-7C09                                | 1         | 2.04%   |
| MSI MS-7A65                                | 1         | 2.04%   |
| MSI MS-7817                                | 1         | 2.04%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 2.04%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.04%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.04%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.04%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 2.04%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.04%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 2.04%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.04%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.04%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.04%   |
| Lenovo G510 20238                          | 1         | 2.04%   |
| Lenovo G50-45 80E3                         | 1         | 2.04%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.04%   |
| HP Pavilion 15                             | 1         | 2.04%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.04%   |
| HP All-in-One 24-f0xx                      | 1         | 2.04%   |
| HP 530                                     | 1         | 2.04%   |
| HP 250 G3                                  | 1         | 2.04%   |
| HP 15                                      | 1         | 2.04%   |
| Gigabyte A320M-S2H                         | 1         | 2.04%   |
| Gigabyte A320M-H                           | 1         | 2.04%   |
| Dell Latitude E6540                        | 1         | 2.04%   |
| Dell G5 5587                               | 1         | 2.04%   |
| ASUS X555YI                                | 1         | 2.04%   |
| ASUS V230IC-DDR4                           | 1         | 2.04%   |
| ASUS P7H55-M LX                            | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| MSI MS-7360              | 3         | 6.12%   |
| Lenovo ThinkPad          | 3         | 6.12%   |
| Toshiba Satellite        | 2         | 4.08%   |
| Packard Bell EasyNote    | 2         | 4.08%   |
| Lenovo IdeaPad           | 2         | 4.08%   |
| Acer Aspire              | 2         | 4.08%   |
| Toshiba PORTEGE          | 1         | 2.04%   |
| Sony SVF1521QSTB         | 1         | 2.04%   |
| Sony SVE14A2V2ES         | 1         | 2.04%   |
| Samsung 300E4A           | 1         | 2.04%   |
| Philco 14F               | 1         | 2.04%   |
| Olidata T7700            | 1         | 2.04%   |
| MSI MS-7C09              | 1         | 2.04%   |
| MSI MS-7A65              | 1         | 2.04%   |
| MSI MS-7817              | 1         | 2.04%   |
| Lenovo Yoga              | 1         | 2.04%   |
| Lenovo V145-15AST        | 1         | 2.04%   |
| Lenovo V110-15ISK        | 1         | 2.04%   |
| Lenovo ThinkCentre       | 1         | 2.04%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.04%   |
| Lenovo G510              | 1         | 2.04%   |
| Lenovo G50-45            | 1         | 2.04%   |
| HUAWEI KLVL-WXXW         | 1         | 2.04%   |
| HP Pavilion              | 1         | 2.04%   |
| HP Laptop                | 1         | 2.04%   |
| HP All-in-One            | 1         | 2.04%   |
| HP 530                   | 1         | 2.04%   |
| HP 250                   | 1         | 2.04%   |
| HP 15                    | 1         | 2.04%   |
| Gigabyte A320M-S2H       | 1         | 2.04%   |
| Gigabyte A320M-H         | 1         | 2.04%   |
| Dell Latitude            | 1         | 2.04%   |
| Dell G5                  | 1         | 2.04%   |
| ASUS X555YI              | 1         | 2.04%   |
| ASUS V230IC-DDR4         | 1         | 2.04%   |
| ASUS P7H55-M             | 1         | 2.04%   |
| ASUS P5G41C-M            | 1         | 2.04%   |
| ASUS E402BP              | 1         | 2.04%   |
| ASUS All                 | 1         | 2.04%   |
| Acer Veriton             | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 9         | 18.37%  |
| 2018 | 7         | 14.29%  |
| 2010 | 5         | 10.2%   |
| 2017 | 4         | 8.16%   |
| 2015 | 4         | 8.16%   |
| 2007 | 4         | 8.16%   |
| 2020 | 3         | 6.12%   |
| 2014 | 3         | 6.12%   |
| 2021 | 2         | 4.08%   |
| 2019 | 2         | 4.08%   |
| 2016 | 2         | 4.08%   |
| 2011 | 2         | 4.08%   |
| 2008 | 1         | 2.04%   |
| 2006 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 33        | 67.35%  |
| Desktop     | 13        | 26.53%  |
| All in one  | 2         | 4.08%   |
| Convertible | 1         | 2.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 20        | 40%     |
| 4.01-8.0   | 11        | 22%     |
| 8.01-16.0  | 8         | 16%     |
| 16.01-24.0 | 6         | 12%     |
| 2.01-3.0   | 2         | 4%      |
| 1.01-2.0   | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 23        | 42.59%  |
| 2.01-3.0   | 17        | 31.48%  |
| 3.01-4.0   | 8         | 14.81%  |
| 4.01-8.0   | 3         | 5.56%   |
| 24.01-32.0 | 1         | 1.85%   |
| 8.01-16.0  | 1         | 1.85%   |
| 0.51-1.0   | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 63.27%  |
| 2      | 15        | 30.61%  |
| 3      | 2         | 4.08%   |
| 4      | 1         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 57.14%  |
| No        | 21        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 93.88%  |
| No        | 3         | 6.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 65.31%  |
| No        | 17        | 34.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 43        | 87.76%  |
| UK      | 1         | 2.04%   |
| Sweden  | 1         | 2.04%   |
| Italy   | 1         | 2.04%   |
| Germany | 1         | 2.04%   |
| France  | 1         | 2.04%   |
| Brazil  | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Istanbul             | 14        | 26.92%  |
| Bursa                | 6         | 11.54%  |
| Ankara               | 6         | 11.54%  |
| Izmir                | 4         | 7.69%   |
| Aydin                | 4         | 7.69%   |
| Konya                | 2         | 3.85%   |
| Çanakkale           | 2         | 3.85%   |
| Yaman                | 1         | 1.92%   |
| Soleymieu            | 1         | 1.92%   |
| Serik                | 1         | 1.92%   |
| Sao Gabriel          | 1         | 1.92%   |
| Samsun               | 1         | 1.92%   |
| Malatya              | 1         | 1.92%   |
| London               | 1         | 1.92%   |
| Landskrona           | 1         | 1.92%   |
| Kirchheim unter Teck | 1         | 1.92%   |
| Gaziantep            | 1         | 1.92%   |
| Esenyurt             | 1         | 1.92%   |
| Bolzano              | 1         | 1.92%   |
| Artvin               | 1         | 1.92%   |
| Antalya              | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 18     | 20.9%   |
| Samsung Electronics | 9         | 14     | 13.43%  |
| Seagate             | 8         | 11     | 11.94%  |
| SanDisk             | 5         | 5      | 7.46%   |
| Kingston            | 3         | 4      | 4.48%   |
| A-DATA Technology   | 3         | 3      | 4.48%   |
| Unknown             | 2         | 3      | 2.99%   |
| Toshiba             | 2         | 3      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| KIOXIA-EXCERIA      | 2         | 2      | 2.99%   |
| Hitachi             | 2         | 2      | 2.99%   |
| HGST                | 2         | 2      | 2.99%   |
| China               | 2         | 2      | 2.99%   |
| Team                | 1         | 1      | 1.49%   |
| SPCC                | 1         | 1      | 1.49%   |
| Silicon Motion      | 1         | 1      | 1.49%   |
| Phison              | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 2      | 1.49%   |
| Lexar               | 1         | 1      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| Intenso             | 1         | 2      | 1.49%   |
| Corsair             | 1         | 1      | 1.49%   |
| addlink             | 1         | 1      | 1.49%   |
| Unknown             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB                 | 3         | 4.29%   |
| A-DATA SU650 120GB SSD                      | 3         | 4.29%   |
| SanDisk SSD PLUS 240GB                      | 2         | 2.86%   |
| HGST HTS545050A7E680 500GB                  | 2         | 2.86%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD            | 1         | 1.43%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 1.43%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 1.43%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 1.43%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1.43%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 1.43%   |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 1.43%   |
| WDC WD2500BEVS-00UST0 250GB                 | 1         | 1.43%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1.43%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 1.43%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1.43%   |
| Unknown SD/MMC/MS PRO 64GB                  | 1         | 1.43%   |
| Unknown MMC Card  64GB                      | 1         | 1.43%   |
| Toshiba MK6475GSX 640GB                     | 1         | 1.43%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1.43%   |
| Team T253X1240G 240GB SSD                   | 1         | 1.43%   |
| SPCC Solid State Disk 512GB                 | 1         | 1.43%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 1.43%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 1.43%   |
| Silicon Motion Longline SSD 512GB           | 1         | 1.43%   |
| Seagate ST9500325AS 500GB                   | 1         | 1.43%   |
| Seagate ST9120822AS 120GB                   | 1         | 1.43%   |
| Seagate ST500LM000-1EJ162 500GB             | 1         | 1.43%   |
| Seagate ST3160318AS 160GB                   | 1         | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1.43%   |
| Seagate Expansion+ 2TB                      | 1         | 1.43%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 1.43%   |
| SanDisk Ultra II 240GB SSD                  | 1         | 1.43%   |
| SanDisk SSD U110 16GB                       | 1         | 1.43%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 1.43%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 1.43%   |
| Samsung SSD 850 PRO 256GB                   | 1         | 1.43%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 1.43%   |
| Samsung MZALQ512HALU-000L1 512GB            | 1         | 1.43%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 17     | 43.33%  |
| Seagate             | 7         | 10     | 23.33%  |
| Samsung Electronics | 3         | 6      | 10%     |
| Toshiba             | 2         | 3      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Unknown             | 1         | 2      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 5         | 5      | 17.24%  |
| Samsung Electronics | 4         | 4      | 13.79%  |
| Kingston            | 3         | 4      | 10.34%  |
| A-DATA Technology   | 3         | 3      | 10.34%  |
| KIOXIA-EXCERIA      | 2         | 2      | 6.9%    |
| China               | 2         | 2      | 6.9%    |
| WDC                 | 1         | 1      | 3.45%   |
| Team                | 1         | 1      | 3.45%   |
| SPCC                | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| Seagate             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 2      | 3.45%   |
| Lexar               | 1         | 1      | 3.45%   |
| KingSpec            | 1         | 1      | 3.45%   |
| Intenso             | 1         | 2      | 3.45%   |
| Corsair             | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 42     | 46.55%  |
| SSD     | 24        | 32     | 41.38%  |
| NVMe    | 4         | 7      | 6.9%    |
| Unknown | 2         | 2      | 3.45%   |
| MMC     | 1         | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 73     | 86.54%  |
| NVMe | 4         | 7      | 7.69%   |
| SAS  | 2         | 3      | 3.85%   |
| MMC  | 1         | 1      | 1.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 52     | 72.55%  |
| 0.51-1.0   | 12        | 18     | 23.53%  |
| 1.01-2.0   | 2         | 4      | 3.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 24        | 48%     |
| 251-500    | 13        | 26%     |
| 501-1000   | 6         | 12%     |
| 51-100     | 4         | 8%      |
| 21-50      | 2         | 4%      |
| 2001-3000  | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 20        | 40%     |
| 21-50    | 12        | 24%     |
| 51-100   | 9         | 18%     |
| 101-250  | 7         | 14%     |
| 251-500  | 1         | 2%      |
| 501-1000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1      | 33.33%  |
| Seagate ST9120822AS 120GB        | 1         | 1      | 33.33%  |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| Seagate  | 1         | 1      | 33.33%  |
| Kingston | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 35        | 61     | 67.31%  |
| Works    | 14        | 20     | 26.92%  |
| Malfunc  | 3         | 3      | 5.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 70.91%  |
| AMD                      | 8         | 14.55%  |
| Marvell Technology Group | 3         | 5.45%   |
| Samsung Electronics      | 2         | 3.64%   |
| SK hynix                 | 1         | 1.82%   |
| Silicon Motion           | 1         | 1.82%   |
| Phison Electronics       | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 10.61%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 6.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 6.06%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                  | 3         | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4.55%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                 | 3         | 4.55%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                           | 3         | 4.55%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 3.03%   |
| AMD FCH SATA Controller D                                                              | 2         | 3.03%   |
| SK hynix BC511                                                                         | 1         | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.52%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.52%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 73.58%  |
| IDE  | 9         | 16.98%  |
| NVMe | 4         | 7.55%   |
| RAID | 1         | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 81.63%  |
| AMD    | 9         | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 3         | 6.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 4.08%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 4.08%   |
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 2.04%   |
| Intel Pentium CPU B950 @ 2.10GHz             | 1         | 2.04%   |
| Intel Core i9-9900 CPU @ 3.10GHz             | 1         | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 2.04%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 2.04%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 2.04%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 2.04%   |
| Intel Core i5-7600 CPU @ 3.50GHz             | 1         | 2.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 2.04%   |
| Intel Core i5-6400T CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz             | 1         | 2.04%   |
| Intel Core i5-4440 CPU @ 3.10GHz             | 1         | 2.04%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 2.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 2.04%   |
| Intel Core i5-10400 CPU @ 2.90GHz            | 1         | 2.04%   |
| Intel Core i3-9100F CPU @ 3.60GHz            | 1         | 2.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 1         | 2.04%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 2.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 1         | 2.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 2.04%   |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 2.04%   |
| Intel Core i3-2310M CPU @ 2.10GHz            | 1         | 2.04%   |
| Intel Core i3 CPU 540 @ 3.07GHz              | 1         | 2.04%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz        | 1         | 2.04%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz         | 1         | 2.04%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 1         | 2.04%   |
| Intel Core 2 CPU T5200 @ 1.60GHz             | 1         | 2.04%   |
| Intel Celeron CPU N3350 @ 1.10GHz            | 1         | 2.04%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 1         | 2.04%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 2.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 1         | 2.04%   |
| AMD Ryzen 5 3500X 6-Core Processor           | 1         | 2.04%   |
| AMD C-50 Processor                           | 1         | 2.04%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 11        | 22.45%  |
| Intel Core i3     | 10        | 20.41%  |
| Intel Core i7     | 5         | 10.2%   |
| Other             | 4         | 8.16%   |
| Intel Core 2 Quad | 4         | 8.16%   |
| AMD A8            | 3         | 6.12%   |
| Intel Pentium     | 2         | 4.08%   |
| Intel Core 2      | 2         | 4.08%   |
| Intel Celeron     | 2         | 4.08%   |
| AMD Ryzen 5       | 2         | 4.08%   |
| Intel Core i9     | 1         | 2.04%   |
| Intel Core 2 Duo  | 1         | 2.04%   |
| AMD C-50          | 1         | 2.04%   |
| AMD A10           | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 55.1%   |
| 4      | 17        | 34.69%  |
| 6      | 4         | 8.16%   |
| 8      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 55.1%   |
| 1      | 22        | 44.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 60.78%  |
| 0x07030105 | 2         | 3.92%   |
| 0x906ed    | 1         | 1.96%   |
| 0x906eb    | 1         | 1.96%   |
| 0x906ea    | 1         | 1.96%   |
| 0x906e9    | 1         | 1.96%   |
| 0x806ea    | 1         | 1.96%   |
| 0x806c1    | 1         | 1.96%   |
| 0x6f6      | 1         | 1.96%   |
| 0x506e3    | 1         | 1.96%   |
| 0x406e3    | 1         | 1.96%   |
| 0x306d4    | 1         | 1.96%   |
| 0x306c3    | 1         | 1.96%   |
| 0x306a9    | 1         | 1.96%   |
| 0x20655    | 1         | 1.96%   |
| 0x1067a    | 1         | 1.96%   |
| 0x08608102 | 1         | 1.96%   |
| 0x06006705 | 1         | 1.96%   |
| 0x0600611a | 1         | 1.96%   |
| 0x05000029 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 16.33%  |
| Haswell     | 6         | 12.24%  |
| Core        | 6         | 12.24%  |
| Excavator   | 4         | 8.16%   |
| Westmere    | 3         | 6.12%   |
| SandyBridge | 3         | 6.12%   |
| IvyBridge   | 3         | 6.12%   |
| Broadwell   | 3         | 6.12%   |
| TigerLake   | 2         | 4.08%   |
| Skylake     | 2         | 4.08%   |
| Puma        | 2         | 4.08%   |
| Zen 2       | 1         | 2.04%   |
| Silvermont  | 1         | 2.04%   |
| Penryn      | 1         | 2.04%   |
| Goldmont    | 1         | 2.04%   |
| CometLake   | 1         | 2.04%   |
| Bobcat      | 1         | 2.04%   |
| Unknown     | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 51.67%  |
| AMD    | 16        | 26.67%  |
| Nvidia | 13        | 21.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GT200 [GeForce GTX 260]                                                           | 3         | 4.41%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.41%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 2.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.94%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 2.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 2.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 2.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.94%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.47%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.47%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.47%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.47%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.47%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.47%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.47%   |
| Intel HD Graphics 630                                                                    | 1         | 1.47%   |
| Intel HD Graphics 620                                                                    | 1         | 1.47%   |
| Intel HD Graphics 530                                                                    | 1         | 1.47%   |
| Intel HD Graphics 520                                                                    | 1         | 1.47%   |
| Intel HD Graphics 500                                                                    | 1         | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.47%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 40.82%  |
| 1 x Nvidia     | 9         | 18.37%  |
| 1 x AMD        | 7         | 14.29%  |
| 2 x AMD        | 5         | 10.2%   |
| Intel + Nvidia | 4         | 8.16%   |
| Intel + AMD    | 4         | 8.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 97.96%  |
| Proprietary | 1         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 76%     |
| 0.01-0.5   | 6         | 12%     |
| 0.51-1.0   | 3         | 6%      |
| 1.01-2.0   | 2         | 4%      |
| 5.01-6.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 7         | 14.29%  |
| Samsung Electronics     | 6         | 12.24%  |
| Goldstar                | 6         | 12.24%  |
| Chimei Innolux          | 5         | 10.2%   |
| BOE                     | 5         | 10.2%   |
| AU Optronics            | 5         | 10.2%   |
| LG Philips              | 2         | 4.08%   |
| Dell                    | 2         | 4.08%   |
| Chi Mei Optoelectronics | 2         | 4.08%   |
| Acer                    | 2         | 4.08%   |
| SAC                     | 1         | 2.04%   |
| Lenovo                  | 1         | 2.04%   |
| Iiyama                  | 1         | 2.04%   |
| Hewlett-Packard         | 1         | 2.04%   |
| Beko                    | 1         | 2.04%   |
| AOC                     | 1         | 2.04%   |
| AGO                     | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 3         | 5.88%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch        | 1         | 1.96%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 1.96%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                          | 1         | 1.96%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 1.96%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 1.96%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 1.96%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch         | 1         | 1.96%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                    | 1         | 1.96%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                     | 1         | 1.96%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 1.96%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                        | 1         | 1.96%   |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                       | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| Beko TV BEK4448 1920x1080 1210x680mm 54.6-inch                           | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 19        | 39.58%  |
| 1920x1080 (FHD)    | 16        | 33.33%  |
| 1680x1050 (WSXGA+) | 3         | 6.25%   |
| 1600x900 (HD+)     | 3         | 6.25%   |
| 1280x800 (WXGA)    | 2         | 4.17%   |
| 1280x1024 (SXGA)   | 2         | 4.17%   |
| 3840x2160 (4K)     | 1         | 2.08%   |
| 2160x1440          | 1         | 2.08%   |
| 1440x900 (WXGA+)   | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 24        | 48%     |
| 23     | 7         | 14%     |
| 17     | 3         | 6%      |
| 14     | 3         | 6%      |
| 21     | 2         | 4%      |
| 13     | 2         | 4%      |
| 12     | 2         | 4%      |
| 72     | 1         | 2%      |
| 31     | 1         | 2%      |
| 27     | 1         | 2%      |
| 22     | 1         | 2%      |
| 20     | 1         | 2%      |
| 19     | 1         | 2%      |
| 11     | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 59.18%  |
| 401-500     | 8         | 16.33%  |
| 501-600     | 5         | 10.2%   |
| 201-300     | 4         | 8.16%   |
| 601-700     | 1         | 2.04%   |
| 351-400     | 1         | 2.04%   |
| 1501-2000   | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 75%     |
| 3/2   | 4         | 8.33%   |
| 16/10 | 4         | 8.33%   |
| 5/4   | 2         | 4.17%   |
| 4/3   | 2         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 48%     |
| 201-250        | 10        | 20%     |
| 81-90          | 5         | 10%     |
| 151-200        | 2         | 4%      |
| 141-150        | 2         | 4%      |
| More than 1000 | 1         | 2%      |
| 71-80          | 1         | 2%      |
| 61-70          | 1         | 2%      |
| 51-60          | 1         | 2%      |
| 351-500        | 1         | 2%      |
| 301-350        | 1         | 2%      |
| 131-140        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 19        | 38%     |
| 51-100  | 17        | 34%     |
| 121-160 | 10        | 20%     |
| 161-240 | 3         | 6%      |
| 1-50    | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 89.8%   |
| 2     | 4         | 8.16%   |
| 0     | 1         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 51.35%  |
| Intel                 | 16        | 21.62%  |
| Qualcomm Atheros      | 7         | 9.46%   |
| Broadcom              | 4         | 5.41%   |
| Ralink Technology     | 2         | 2.7%    |
| Ralink                | 2         | 2.7%    |
| ASUSTek Computer      | 2         | 2.7%    |
| ZyXEL Communications  | 1         | 1.35%   |
| Xiaomi                | 1         | 1.35%   |
| JMicron Technology    | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 31.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 4.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 3.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 3.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 3.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 2.2%    |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.2%    |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.1%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.1%    |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.1%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.1%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.1%    |
| Intel Wireless 8265 / 8275                                           | 1         | 1.1%    |
| Intel Wireless 7265                                                  | 1         | 1.1%    |
| Intel Wireless 7260                                                  | 1         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.1%    |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.1%    |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.1%    |
| Intel Centrino Wireless-N 2230                                       | 1         | 1.1%    |
| Intel Centrino Wireless-N 130                                        | 1         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.1%    |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.1%    |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.1%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 32.56%  |
| Realtek Semiconductor | 12        | 27.91%  |
| Qualcomm Atheros      | 6         | 13.95%  |
| Broadcom              | 4         | 9.3%    |
| Ralink Technology     | 2         | 4.65%   |
| Ralink                | 2         | 4.65%   |
| ASUSTek Computer      | 2         | 4.65%   |
| ZyXEL Communications  | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 9.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 6.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 6.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 6.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 4.65%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 4.65%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.33%   |
| Intel Wireless 7265                                            | 1         | 2.33%   |
| Intel Wireless 7260                                            | 1         | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.33%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.33%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.33%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.33%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.33%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.33%   |
| ASUS 802.11ac NIC                                              | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 78.72%  |
| Intel                 | 6         | 12.77%  |
| Xiaomi                | 1         | 2.13%   |
| Qualcomm Atheros      | 1         | 2.13%   |
| JMicron Technology    | 1         | 2.13%   |
| Broadcom              | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 60.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 14.58%  |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 2.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 2.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 2.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 2.08%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 2.08%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.08%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 2.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 53.49%  |
| WiFi     | 40        | 46.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 65.38%  |
| Ethernet | 18        | 34.62%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 69.39%  |
| 1     | 15        | 30.61%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 93.88%  |
| Yes  | 3         | 6.12%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 28.13%  |
| Realtek Semiconductor           | 7         | 21.88%  |
| Qualcomm Atheros Communications | 3         | 9.38%   |
| Toshiba                         | 2         | 6.25%   |
| Lite-On Technology              | 2         | 6.25%   |
| IMC Networks                    | 2         | 6.25%   |
| Cambridge Silicon Radio         | 2         | 6.25%   |
| Realtek                         | 1         | 3.13%   |
| Ralink                          | 1         | 3.13%   |
| Foxconn International           | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 12.5%   |
| Intel Bluetooth wireless interface                  | 4         | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.25%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.13%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.13%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.13%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Realtek Bluetooth Radio                             | 1         | 3.13%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.13%   |
| Intel AX201 Bluetooth                               | 1         | 3.13%   |
| Intel AX200 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.13%   |
| IMC Networks Bluetooth Device                       | 1         | 3.13%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 3.13%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.13%   |
| Broadcom HP Portable Valentine                      | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 67.8%   |
| AMD                   | 12        | 20.34%  |
| Nvidia                | 5         | 8.47%   |
| Kingston Technology   | 1         | 1.69%   |
| Barco Display Systems | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 5.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 5.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.05%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.05%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.7%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 2.7%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 2         | 2.7%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Kingston Technology HyperX QuadCast S                                                             | 1         | 1.35%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.35%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.35%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.35%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 38.89%  |
| SK hynix            | 2         | 11.11%  |
| Kingston            | 2         | 11.11%  |
| A-DATA Technology   | 2         | 11.11%  |
| Unknown (0x4509)    | 1         | 5.56%   |
| Unknown             | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |
| Kingmax             | 1         | 5.56%   |
| G.Skill             | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 5.26%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 5.26%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 5.26%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 5.26%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 5.26%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 5.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 5.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 5.26%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 5.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 5.26%   |
| Samsung RAM M378A2K43DB1-CTD 16GB DIMM DDR4 2667MT/s               | 1         | 5.26%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 5.26%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s               | 1         | 5.26%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                  | 1         | 5.26%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 5.26%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 5.26%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 5.26%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 5.26%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 12        | 66.67%  |
| DDR3  | 4         | 22.22%  |
| SDRAM | 1         | 5.56%   |
| DDR2  | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 64.71%  |
| DIMM         | 5         | 29.41%  |
| Row Of Chips | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 52.94%  |
| 4096  | 5         | 29.41%  |
| 2048  | 2         | 11.76%  |
| 16384 | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 4         | 22.22%  |
| 2133    | 4         | 22.22%  |
| 3200    | 3         | 16.67%  |
| 1600    | 3         | 16.67%  |
| 3400    | 1         | 5.56%   |
| 2400    | 1         | 5.56%   |
| 1333    | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Zebra           | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Hewlett-Packard | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra TLP2844                    | 2         | 28.57%  |
| Zebra Zebra GC420d Label Printer | 1         | 14.29%  |
| HP LaserJet P1102                | 1         | 14.29%  |
| Canon PIXMA MX340                | 1         | 14.29%  |
| Canon LBP6030w/6018w             | 1         | 14.29%  |
| Canon LBP6000                    | 1         | 14.29%  |

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
| Chicony Electronics                    | 13        | 37.14%  |
| Realtek Semiconductor                  | 3         | 8.57%   |
| Microdia                               | 3         | 8.57%   |
| IMC Networks                           | 3         | 8.57%   |
| Luxvisions Innotech Limited            | 2         | 5.71%   |
| Acer                                   | 2         | 5.71%   |
| Suyin                                  | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| MacroSilicon                           | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| Foxconn / Hon Hai                      | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Arkmicro Technologies                  | 1         | 2.86%   |
| ALi                                    | 1         | 2.86%   |
| Alcor Micro                            | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                           | 2         | 5.71%   |
| Chicony Integrated Camera                           | 2         | 5.71%   |
| Chicony EasyCamera                                  | 2         | 5.71%   |
| Acer EasyCamera                                     | 2         | 5.71%   |
| Suyin HP Webcam                                     | 1         | 2.86%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 2.86%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.86%   |
| Microdia Integrated Camera                          | 1         | 2.86%   |
| MacroSilicon USB Video                              | 1         | 2.86%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.86%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.86%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 2.86%   |
| IMC Networks EasyCamera                             | 1         | 2.86%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 2.86%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.86%   |
| Chicony USB2.0 Camera                               | 1         | 2.86%   |
| Chicony HP Truevision HD                            | 1         | 2.86%   |
| Chicony HP High Definition 1MP Webcam               | 1         | 2.86%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 2.86%   |
| Chicony Front Camera                                | 1         | 2.86%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 2.86%   |
| Chicony CNA7157                                     | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 2.86%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 2.86%   |
| ALi Gateway Webcam                                  | 1         | 2.86%   |
| Alcor Micro USB 2.0 PC Camera                       | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| AuthenTec                  | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 33.33%  |
| Shenzhen Goodix  Fingerprint Device          | 1         | 33.33%  |
| AuthenTec AES1600                            | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Advanced Card Systems | 2         | 66.67%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 39        | 76.47%  |
| 1     | 9         | 17.65%  |
| 2     | 3         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 21.43%  |
| Fingerprint reader       | 3         | 21.43%  |
| Communication controller | 2         | 14.29%  |
| Chipcard                 | 2         | 14.29%  |
| Camera                   | 2         | 14.29%  |
| Net/wireless             | 1         | 7.14%   |
| Bluetooth                | 1         | 7.14%   |

