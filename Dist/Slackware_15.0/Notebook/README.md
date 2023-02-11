Slackware 15.0 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 43

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X140e 20BMS03E0... | [fb4c4aebf9](https://linux-hardware.org/?probe=fb4c4aebf9) | Jan 31, 2023 |
| Lenovo    | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HP        | EliteBook 8440p             | [9edc837033](https://linux-hardware.org/?probe=9edc837033) | Jan 13, 2023 |
| HP        | OMEN by Laptop 17-ck0xxx    | [9655429e71](https://linux-hardware.org/?probe=9655429e71) | Jan 06, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Acer      | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [799470f1aa](https://linux-hardware.org/?probe=799470f1aa) | Dec 05, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [0cd3005f69](https://linux-hardware.org/?probe=0cd3005f69) | Dec 01, 2022 |
| HP        | OMEN by Laptop 16-b1xxx     | [32b68762df](https://linux-hardware.org/?probe=32b68762df) | Nov 30, 2022 |
| Lenovo    | ThinkPad T470 20JNS01R01    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [e7f2dc737e](https://linux-hardware.org/?probe=e7f2dc737e) | Oct 09, 2022 |
| Lenovo    | ThinkPad T410 2518C3U       | [4d250adf3b](https://linux-hardware.org/?probe=4d250adf3b) | Oct 04, 2022 |
| Lenovo    | ThinkPad T61 765912G        | [bd04e564a0](https://linux-hardware.org/?probe=bd04e564a0) | Sep 24, 2022 |
| Fujitsu   | LIFEBOOK A544               | [e5785106f1](https://linux-hardware.org/?probe=e5785106f1) | Aug 09, 2022 |
| MSI       | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Sony      | SVE1713A1EW                 | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| MSI       | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI       | GE76 Raider 11UE            | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook  | X170KM-G                    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Dell      | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP        | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo    | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell      | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.15.19     | 11        | 29.73%  |
| 5.19.17     | 2         | 5.41%   |
| 5.17.1      | 2         | 5.41%   |
| 5.13.8      | 2         | 5.41%   |
| 6.1.1       | 1         | 2.7%    |
| 5.17.5      | 1         | 2.7%    |
| 5.17.2      | 1         | 2.7%    |
| 5.16.9-joe1 | 1         | 2.7%    |
| 5.16.12     | 1         | 2.7%    |
| 5.15.80     | 1         | 2.7%    |
| 5.15.78.a   | 1         | 2.7%    |
| 5.15.63     | 1         | 2.7%    |
| 5.15.38     | 1         | 2.7%    |
| 5.15.37.a   | 1         | 2.7%    |
| 5.15.33.kjh | 1         | 2.7%    |
| 5.15.27     | 1         | 2.7%    |
| 5.15.1      | 1         | 2.7%    |
| 5.14.9      | 1         | 2.7%    |
| 5.14.8      | 1         | 2.7%    |
| 5.14.10     | 1         | 2.7%    |
| 5.14.0      | 1         | 2.7%    |
| 5.13.5      | 1         | 2.7%    |
| 5.13.11     | 1         | 2.7%    |
| 5.10.91     | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 11        | 29.73%  |
| 5.19.17 | 2         | 5.41%   |
| 5.17.1  | 2         | 5.41%   |
| 5.13.8  | 2         | 5.41%   |
| 6.1.1   | 1         | 2.7%    |
| 5.17.5  | 1         | 2.7%    |
| 5.17.2  | 1         | 2.7%    |
| 5.16.9  | 1         | 2.7%    |
| 5.16.12 | 1         | 2.7%    |
| 5.15.80 | 1         | 2.7%    |
| 5.15.78 | 1         | 2.7%    |
| 5.15.63 | 1         | 2.7%    |
| 5.15.38 | 1         | 2.7%    |
| 5.15.37 | 1         | 2.7%    |
| 5.15.33 | 1         | 2.7%    |
| 5.15.27 | 1         | 2.7%    |
| 5.15.1  | 1         | 2.7%    |
| 5.14.9  | 1         | 2.7%    |
| 5.14.8  | 1         | 2.7%    |
| 5.14.10 | 1         | 2.7%    |
| 5.14.0  | 1         | 2.7%    |
| 5.13.5  | 1         | 2.7%    |
| 5.13.11 | 1         | 2.7%    |
| 5.10.91 | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 19        | 52.78%  |
| 5.17    | 4         | 11.11%  |
| 5.13    | 4         | 11.11%  |
| 5.14    | 3         | 8.33%   |
| 5.19    | 2         | 5.56%   |
| 5.16    | 2         | 5.56%   |
| 6.1     | 1         | 2.78%   |
| 5.10    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 21        | 56.76%  |
| XFCE      | 6         | 16.22%  |
| Unknown   | 4         | 10.81%  |
| xwmconfig | 1         | 2.7%    |
| MATE      | 1         | 2.7%    |
| KDE       | 1         | 2.7%    |
| GNOME     | 1         | 2.7%    |
| awesome   | 1         | 2.7%    |
| 2bwm      | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 21        | 55.26%  |
| Tty     | 14        | 36.84%  |
| Wayland | 3         | 7.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 23        | 62.16%  |
| Unknown | 9         | 24.32%  |
| XDM     | 4         | 10.81%  |
| GDM     | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 27        | 75%     |
| pt_BR | 2         | 5.56%   |
| it_IT | 2         | 5.56%   |
| fr_FR | 2         | 5.56%   |
| de_DE | 2         | 5.56%   |
| ru_RU | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 58.33%  |
| BIOS | 15        | 41.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 30        | 83.33%  |
| Btrfs   | 3         | 8.33%   |
| Overlay | 2         | 5.56%   |
| Xfs     | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 23        | 63.89%  |
| MBR     | 7         | 19.44%  |
| Unknown | 6         | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 86.49%  |
| Yes       | 5         | 13.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 55.56%  |
| Yes       | 16        | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 25%     |
| Hewlett-Packard  | 9         | 25%     |
| MSI              | 4         | 11.11%  |
| Dell             | 4         | 11.11%  |
| ASUSTek Computer | 3         | 8.33%   |
| System76         | 1         | 2.78%   |
| Sony             | 1         | 2.78%   |
| Notebook         | 1         | 2.78%   |
| Fujitsu          | 1         | 2.78%   |
| Framework        | 1         | 2.78%   |
| Dynabook         | 1         | 2.78%   |
| Acer             | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 5.56%   |
| System76 Oryx Pro                        | 1         | 2.78%   |
| Sony SVE1713A1EW                         | 1         | 2.78%   |
| Notebook X170KM-G                        | 1         | 2.78%   |
| MSI Modern 14 B11MO                      | 1         | 2.78%   |
| MSI Modern 14 B10MW                      | 1         | 2.78%   |
| MSI GP76 Leopard 11UG                    | 1         | 2.78%   |
| MSI GE76 Raider 11UE                     | 1         | 2.78%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 2.78%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 2.78%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 2.78%   |
| Lenovo ThinkPad T61 765912G              | 1         | 2.78%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 2.78%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 2.78%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 2.78%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2.78%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2.78%   |
| HP ProBook 6570b                         | 1         | 2.78%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2.78%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2.78%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 2.78%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 2.78%   |
| HP Laptop 15-bs1xx                       | 1         | 2.78%   |
| HP EliteBook 8440p                       | 1         | 2.78%   |
| HP EliteBook 840 G5                      | 1         | 2.78%   |
| HP 245 G7 Notebook PC                    | 1         | 2.78%   |
| Fujitsu LIFEBOOK A544                    | 1         | 2.78%   |
| Framework Laptop                         | 1         | 2.78%   |
| Dynabook P1-C7MP-BL                      | 1         | 2.78%   |
| Dell Vostro 3500                         | 1         | 2.78%   |
| Dell Precision M4700                     | 1         | 2.78%   |
| Dell Latitude 3520                       | 1         | 2.78%   |
| Dell Inspiron 15-3552                    | 1         | 2.78%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 2.78%   |
| Acer Nitro AN515-54                      | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 22.22%  |
| MSI Modern          | 2         | 5.56%   |
| HP Pavilion         | 2         | 5.56%   |
| HP OMEN             | 2         | 5.56%   |
| HP EliteBook        | 2         | 5.56%   |
| ASUS VivoBook       | 2         | 5.56%   |
| System76 Oryx       | 1         | 2.78%   |
| Sony SVE1713A1EW    | 1         | 2.78%   |
| Notebook X170KM-G   | 1         | 2.78%   |
| MSI GP76            | 1         | 2.78%   |
| MSI GE76            | 1         | 2.78%   |
| Lenovo IdeaPad      | 1         | 2.78%   |
| HP ProBook          | 1         | 2.78%   |
| HP Laptop           | 1         | 2.78%   |
| HP 245              | 1         | 2.78%   |
| Fujitsu LIFEBOOK    | 1         | 2.78%   |
| Framework Laptop    | 1         | 2.78%   |
| Dynabook P1-C7MP-BL | 1         | 2.78%   |
| Dell Vostro         | 1         | 2.78%   |
| Dell Precision      | 1         | 2.78%   |
| Dell Latitude       | 1         | 2.78%   |
| Dell Inspiron       | 1         | 2.78%   |
| ASUS ROG            | 1         | 2.78%   |
| Acer Nitro          | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 19.44%  |
| 2020 | 6         | 16.67%  |
| 2012 | 5         | 13.89%  |
| 2017 | 4         | 11.11%  |
| 2022 | 3         | 8.33%   |
| 2019 | 2         | 5.56%   |
| 2010 | 2         | 5.56%   |
| 2018 | 1         | 2.78%   |
| 2016 | 1         | 2.78%   |
| 2015 | 1         | 2.78%   |
| 2014 | 1         | 2.78%   |
| 2013 | 1         | 2.78%   |
| 2009 | 1         | 2.78%   |
| 2007 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 36        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 94.44%  |
| Yes  | 2         | 5.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 8         | 22.22%  |
| 8.01-16.0   | 8         | 22.22%  |
| 4.01-8.0    | 7         | 19.44%  |
| 3.01-4.0    | 7         | 19.44%  |
| 32.01-64.0  | 3         | 8.33%   |
| 24.01-32.0  | 2         | 5.56%   |
| 64.01-256.0 | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 13        | 33.33%  |
| 1.01-2.0   | 9         | 23.08%  |
| 4.01-8.0   | 8         | 20.51%  |
| 0.51-1.0   | 4         | 10.26%  |
| 3.01-4.0   | 2         | 5.13%   |
| 0.01-0.5   | 2         | 5.13%   |
| 16.01-24.0 | 1         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 75%     |
| 2      | 8         | 22.22%  |
| 4      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 77.78%  |
| Yes       | 8         | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 80.56%  |
| No        | 7         | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 88.89%  |
| No        | 4         | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 10        | 27.78%  |
| Kazakhstan   | 3         | 8.33%   |
| Italy        | 3         | 8.33%   |
| South Africa | 2         | 5.56%   |
| Portugal     | 2         | 5.56%   |
| Japan        | 2         | 5.56%   |
| Germany      | 2         | 5.56%   |
| France       | 2         | 5.56%   |
| Brazil       | 2         | 5.56%   |
| Sweden       | 1         | 2.78%   |
| Spain        | 1         | 2.78%   |
| Serbia       | 1         | 2.78%   |
| Russia       | 1         | 2.78%   |
| Mexico       | 1         | 2.78%   |
| Greece       | 1         | 2.78%   |
| Chile        | 1         | 2.78%   |
| Canada       | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 5.41%   |
| Sun Prairie       | 2         | 5.41%   |
| Lisbon            | 2         | 5.41%   |
| Frignano          | 2         | 5.41%   |
| Worpswede         | 1         | 2.7%    |
| Tsukuba           | 1         | 2.7%    |
| Skövde           | 1         | 2.7%    |
| Sao Paulo         | 1         | 2.7%    |
| Santiago          | 1         | 2.7%    |
| Round Rock        | 1         | 2.7%    |
| Reno              | 1         | 2.7%    |
| Renazzo           | 1         | 2.7%    |
| Plainwell         | 1         | 2.7%    |
| Ōtsu             | 1         | 2.7%    |
| Oberstreit        | 1         | 2.7%    |
| Moscow            | 1         | 2.7%    |
| Montreal          | 1         | 2.7%    |
| Mexico City       | 1         | 2.7%    |
| McKinney          | 1         | 2.7%    |
| Luxeuil-les-Bains | 1         | 2.7%    |
| League City       | 1         | 2.7%    |
| Karaganda         | 1         | 2.7%    |
| Johannesburg      | 1         | 2.7%    |
| Hayward           | 1         | 2.7%    |
| Fortaleza         | 1         | 2.7%    |
| Fayetteville      | 1         | 2.7%    |
| Chessy            | 1         | 2.7%    |
| Chania            | 1         | 2.7%    |
| Cape Town         | 1         | 2.7%    |
| Bremervoerde      | 1         | 2.7%    |
| Belgrade          | 1         | 2.7%    |
| Algeciras         | 1         | 2.7%    |
| Abingdon          | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 23.81%  |
| WDC                 | 6         | 7      | 14.29%  |
| Toshiba             | 3         | 3      | 7.14%   |
| SanDisk             | 3         | 4      | 7.14%   |
| Kingston            | 3         | 3      | 7.14%   |
| Intel               | 3         | 3      | 7.14%   |
| HGST                | 3         | 3      | 7.14%   |
| SK hynix            | 2         | 2      | 4.76%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| Crucial             | 2         | 2      | 4.76%   |
| Seagate             | 1         | 1      | 2.38%   |
| Plextor             | 1         | 1      | 2.38%   |
| KIOXIA              | 1         | 1      | 2.38%   |
| Hewlett-Packard     | 1         | 2      | 2.38%   |
| Gigabyte Technology | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 4.35%   |
| Intel SSD 660P Series 512GB                         | 2         | 4.35%   |
| HGST HTS725050A7E630 500GB                          | 2         | 4.35%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 2.17%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 2.17%   |
| WDC WD10JPVT-08A1YT2 1TB                            | 1         | 2.17%   |
| WDC WD Green 2.5 240GB                              | 1         | 2.17%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 1         | 2.17%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 2.17%   |
| Toshiba MQ01ACF032 320GB                            | 1         | 2.17%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.17%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 2.17%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB             | 1         | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2.17%   |
| SanDisk Ultra II 960GB SSD                          | 1         | 2.17%   |
| SanDisk SDSSDA240G 240GB                            | 1         | 2.17%   |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2.17%   |
| Samsung SSD PM830 2.5 7mm 128GB                     | 1         | 2.17%   |
| Samsung SSD 980 PRO 500GB                           | 1         | 2.17%   |
| Samsung SSD 980 PRO 2TB                             | 1         | 2.17%   |
| Samsung SSD 970 EVO Plus 2TB                        | 1         | 2.17%   |
| Samsung SSD 970 EVO 2TB                             | 1         | 2.17%   |
| Samsung SSD 870 EVO 1TB                             | 1         | 2.17%   |
| Samsung SSD 860 EVO mSATA 500GB                     | 1         | 2.17%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2.17%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 1         | 2.17%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 1         | 2.17%   |
| Samsung MZVKW512HMJP-000H1 512GB                    | 1         | 2.17%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 1         | 2.17%   |
| Plextor PX-128M6S 128GB SSD                         | 1         | 2.17%   |
| Micron MTFDKBA1T0TFH-1BC1AABHA 1TB                  | 1         | 2.17%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 2.17%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                      | 1         | 2.17%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 2.17%   |
| Kingston SHSS37A480G 480GB SSD                      | 1         | 2.17%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 2.17%   |
| Intel SSDPEKKF256G7L 256GB                          | 1         | 2.17%   |
| HGST HTS545050A7E380 500GB                          | 1         | 2.17%   |
| HP SSD EX950 2TB                                    | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 30%     |
| Toshiba | 3         | 3      | 30%     |
| HGST    | 3         | 3      | 30%     |
| Seagate | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 5      | 23.08%  |
| Kingston            | 3         | 3      | 23.08%  |
| WDC                 | 2         | 3      | 15.38%  |
| SanDisk             | 2         | 2      | 15.38%  |
| Plextor             | 1         | 1      | 7.69%   |
| Gigabyte Technology | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 24     | 45.24%  |
| SSD  | 13        | 16     | 30.95%  |
| HDD  | 10        | 10     | 23.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 26     | 51.28%  |
| NVMe | 19        | 24     | 48.72%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 17     | 63.64%  |
| 0.51-1.0   | 8         | 9      | 36.36%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 12        | 33.33%  |
| 101-250        | 9         | 25%     |
| 251-500        | 8         | 22.22%  |
| 1001-2000      | 4         | 11.11%  |
| 1-20           | 2         | 5.56%   |
| More than 3000 | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 9         | 24.32%  |
| 251-500   | 7         | 18.92%  |
| 1-20      | 7         | 18.92%  |
| 21-50     | 6         | 16.22%  |
| 51-100    | 4         | 10.81%  |
| 1001-2000 | 2         | 5.41%   |
| 501-1000  | 2         | 5.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 25%     |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 25%     |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 25%     |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Plextor             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| HDD  | 2         | 2      | 50%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 28        | 34     | 71.79%  |
| Detected | 7         | 12     | 17.95%  |
| Malfunc  | 4         | 4      | 10.26%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 23        | 53.49%  |
| Samsung Electronics       | 7         | 16.28%  |
| AMD                       | 4         | 9.3%    |
| SK hynix                  | 2         | 4.65%   |
| SanDisk                   | 2         | 4.65%   |
| Micron Technology         | 2         | 4.65%   |
| Micron/Crucial Technology | 1         | 2.33%   |
| KIOXIA                    | 1         | 2.33%   |
| Biwin Storage Technology  | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 8.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 8.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 6.38%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 6.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 4.26%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 4.26%   |
| Micron Non-Volatile memory controller                                            | 2         | 4.26%   |
| Intel SSD 660P Series                                                            | 2         | 4.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 2.13%   |
| SK hynix BC511                                                                   | 1         | 2.13%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.13%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.13%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.13%   |
| Intel SSD 600P Series                                                            | 1         | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 2.13%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 2.13%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 43.48%  |
| NVMe | 19        | 41.3%   |
| RAID | 6         | 13.04%  |
| IDE  | 1         | 2.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 88.89%  |
| AMD    | 4         | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 11.11%  |
| Intel 12th Gen Core i7-12700H                 | 3         | 8.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 5.56%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.78%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 2.78%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.78%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.78%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.78%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.78%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.78%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 11        | 30.56%  |
| Intel Core i5    | 9         | 25%     |
| Intel Core i7    | 8         | 22.22%  |
| AMD Ryzen 5      | 2         | 5.56%   |
| Intel Pentium    | 1         | 2.78%   |
| Intel Core i3    | 1         | 2.78%   |
| Intel Core 2 Duo | 1         | 2.78%   |
| Intel Celeron    | 1         | 2.78%   |
| AMD Ryzen 9      | 1         | 2.78%   |
| AMD E1           | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 41.67%  |
| 4      | 9         | 25%     |
| 8      | 7         | 19.44%  |
| 14     | 3         | 8.33%   |
| 6      | 2         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 88.89%  |
| 1      | 4         | 11.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 25%     |
| 0x306a9    | 5         | 13.89%  |
| 0x806d1    | 4         | 11.11%  |
| 0x906a3    | 3         | 8.33%   |
| 0x806c1    | 3         | 8.33%   |
| 0xa0671    | 1         | 2.78%   |
| 0xa0652    | 1         | 2.78%   |
| 0x806ec    | 1         | 2.78%   |
| 0x806ea    | 1         | 2.78%   |
| 0x406e3    | 1         | 2.78%   |
| 0x406c4    | 1         | 2.78%   |
| 0x306d4    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x20655    | 1         | 2.78%   |
| 0x08600106 | 1         | 2.78%   |
| 0x08108109 | 1         | 2.78%   |
| 0x07000106 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 16.67%  |
| IvyBridge        | 5         | 13.89%  |
| Icelake          | 5         | 13.89%  |
| Westmere         | 3         | 8.33%   |
| TigerLake        | 3         | 8.33%   |
| Alderlake Hybrid | 3         | 8.33%   |
| Zen 2            | 2         | 5.56%   |
| Skylake          | 2         | 5.56%   |
| Zen+             | 1         | 2.78%   |
| Silvermont       | 1         | 2.78%   |
| Jaguar           | 1         | 2.78%   |
| Haswell          | 1         | 2.78%   |
| Core             | 1         | 2.78%   |
| CometLake        | 1         | 2.78%   |
| Broadwell        | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 54.17%  |
| Nvidia | 15        | 31.25%  |
| AMD    | 7         | 14.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 8.16%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 6.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 6.12%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 6.12%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 6.12%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 4.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 4.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 4.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 4.08%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 4.08%   |
| AMD Renoir                                                                               | 2         | 4.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.04%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 2.04%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 2.04%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.04%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.04%   |
| Intel HD Graphics 630                                                                    | 1         | 2.04%   |
| Intel HD Graphics 620                                                                    | 1         | 2.04%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.04%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 2.04%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 44.44%  |
| Intel + Nvidia | 10        | 27.78%  |
| 1 x AMD        | 6         | 16.67%  |
| 1 x Nvidia     | 3         | 8.33%   |
| AMD + Nvidia   | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 30        | 83.33%  |
| Proprietary | 6         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 63.89%  |
| 0.01-0.5   | 4         | 11.11%  |
| 7.01-8.0   | 3         | 8.33%   |
| 0.51-1.0   | 3         | 8.33%   |
| 5.01-6.0   | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 10        | 25.64%  |
| LG Display          | 7         | 17.95%  |
| AU Optronics        | 7         | 17.95%  |
| Samsung Electronics | 3         | 7.69%   |
| Chimei Innolux      | 3         | 7.69%   |
| Sharp               | 2         | 5.13%   |
| Lenovo              | 2         | 5.13%   |
| Hewlett-Packard     | 2         | 5.13%   |
| Sony                | 1         | 2.56%   |
| PANDA               | 1         | 2.56%   |
| Dell                | 1         | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 5.13%   |
| Sony TV SNY8102 1360x768                                              | 1         | 2.56%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 2.56%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 2.56%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 2.56%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 2.56%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 2.56%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 2.56%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch               | 1         | 2.56%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 1         | 2.56%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 2.56%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 2.56%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.56%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 1         | 2.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.56%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 2.56%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 380x210mm 17.1-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch         | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 19        | 51.35%  |
| 1366x768 (WXGA) | 9         | 24.32%  |
| 2880x1620       | 2         | 5.41%   |
| 1600x900 (HD+)  | 2         | 5.41%   |
| 1280x800 (WXGA) | 2         | 5.41%   |
| 3840x2160 (4K)  | 1         | 2.7%    |
| 2256x1504       | 1         | 2.7%    |
| 1360x768        | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 15        | 38.46%  |
| 14     | 7         | 17.95%  |
| 13     | 5         | 12.82%  |
| 17     | 4         | 10.26%  |
| 16     | 2         | 5.13%   |
| 72     | 1         | 2.56%   |
| 27     | 1         | 2.56%   |
| 24     | 1         | 2.56%   |
| 21     | 1         | 2.56%   |
| 12     | 1         | 2.56%   |
| 11     | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 66.67%  |
| 351-400     | 6         | 15.38%  |
| 201-300     | 3         | 7.69%   |
| 501-600     | 2         | 5.13%   |
| 401-500     | 1         | 2.56%   |
| 1501-2000   | 1         | 2.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 88.89%  |
| 16/10 | 3         | 8.33%   |
| 3/2   | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 43.59%  |
| 81-90          | 12        | 30.77%  |
| 121-130        | 4         | 10.26%  |
| More than 1000 | 1         | 2.56%   |
| 61-70          | 1         | 2.56%   |
| 51-60          | 1         | 2.56%   |
| 301-350        | 1         | 2.56%   |
| 251-300        | 1         | 2.56%   |
| 151-200        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 52.63%  |
| 101-120       | 10        | 26.32%  |
| 161-240       | 3         | 7.89%   |
| 51-100        | 3         | 7.89%   |
| More than 240 | 1         | 2.63%   |
| 1-50          | 1         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 88.89%  |
| 2     | 4         | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 46.43%  |
| Realtek Semiconductor | 20        | 35.71%  |
| MediaTek              | 3         | 5.36%   |
| Broadcom Limited      | 3         | 5.36%   |
| Sitecom Europe        | 1         | 1.79%   |
| Ralink Technology     | 1         | 1.79%   |
| Qualcomm Atheros      | 1         | 1.79%   |
| Hewlett-Packard       | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 23.19%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 5.8%    |
| Intel Wireless 8265 / 8275                                        | 3         | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.9%    |
| MediaTek WLAN controller                                          | 2         | 2.9%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.9%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.9%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 2.9%    |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.45%   |
| Intel Wireless 8260                                               | 1         | 1.45%   |
| Intel Wireless 7260                                               | 1         | 1.45%   |
| Intel Wireless 3165                                               | 1         | 1.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.45%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.45%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.45%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 64.86%  |
| Realtek Semiconductor | 4         | 10.81%  |
| MediaTek              | 3         | 8.11%   |
| Broadcom Limited      | 3         | 8.11%   |
| Sitecom Europe        | 1         | 2.7%    |
| Ralink Technology     | 1         | 2.7%    |
| Qualcomm Atheros      | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 10.53%  |
| Intel Wireless 8265 / 8275                                    | 3         | 7.89%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 7.89%   |
| MediaTek WLAN controller                                      | 2         | 5.26%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 5.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 5.26%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 5.26%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.63%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 2.63%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.63%   |
| Intel Wireless 8260                                           | 1         | 2.63%   |
| Intel Wireless 7260                                           | 1         | 2.63%   |
| Intel Wireless 3165                                           | 1         | 2.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.63%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 65.52%  |
| Intel                 | 10        | 34.48%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 53.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 10%     |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 6.67%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 3.33%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 54.55%  |
| Ethernet | 29        | 43.94%  |
| Modem    | 1         | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 82.05%  |
| Ethernet | 7         | 17.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 77.78%  |
| 1     | 8         | 22.22%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 86.11%  |
| Yes  | 5         | 13.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 62.5%   |
| Broadcom              | 5         | 15.63%  |
| Realtek Semiconductor | 3         | 9.38%   |
| IMC Networks          | 3         | 9.38%   |
| Foxconn / Hon Hai     | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 21.88%  |
| Intel Bluetooth Device                           | 5         | 15.63%  |
| Intel AX210 Bluetooth                            | 4         | 12.5%   |
| Intel AX200 Bluetooth                            | 3         | 9.38%   |
| IMC Networks Wireless_Device                     | 3         | 9.38%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 6.25%   |
| Realtek Bluetooth Radio                          | 1         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 3.13%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 3.13%   |
| Broadcom HP Portable SoftSailing                 | 1         | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 3.13%   |
| Broadcom BCM20702A0                              | 1         | 3.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 3.13%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 59.26%  |
| Nvidia              | 14        | 25.93%  |
| AMD                 | 7         | 12.96%  |
| C-Media Electronics | 1         | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 8.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.47%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 6.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 5.08%   |
| Nvidia Audio device                                                                               | 3         | 5.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 5.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 5.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 5.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 5.08%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 3.39%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.39%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 3.39%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.69%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.69%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.69%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 25.71%  |
| Samsung Electronics | 8         | 22.86%  |
| Kingston            | 7         | 20%     |
| Micron Technology   | 3         | 8.57%   |
| Crucial             | 3         | 8.57%   |
| Neo Forza           | 1         | 2.86%   |
| Nanya Technology    | 1         | 2.86%   |
| Essencore Limited   | 1         | 2.86%   |
| Corsair             | 1         | 2.86%   |
| A-DATA Technology   | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s     | 2         | 5.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 2.7%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 2.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.7%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.7%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 2.7%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 2.7%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 2.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                | 1         | 2.7%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s              | 1         | 2.7%    |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 2.7%    |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.7%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8192MB SODIMM DDR4 3200MT/s              | 1         | 2.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.7%    |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 2.7%    |
| Kingston RAM KNWMX1-ETB 4096MB SODIMM DDR3 1600MT/s                  | 1         | 2.7%    |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.7%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 2.7%    |
| Kingston RAM KF2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 2.7%    |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 2.7%    |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.7%    |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 2.7%    |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 2.7%    |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 3200MT/s                | 1         | 2.7%    |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| A-DATA RAM AO1L16BC4R1-BX7S 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 53.33%  |
| DDR3   | 10        | 33.33%  |
| LPDDR5 | 2         | 6.67%   |
| LPDDR3 | 1         | 3.33%   |
| DDR5   | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 90%     |
| Row Of Chips | 3         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 45.71%  |
| 4096  | 11        | 31.43%  |
| 16384 | 4         | 11.43%  |
| 2048  | 3         | 8.57%   |
| 32768 | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 10        | 30.3%   |
| 1600  | 9         | 27.27%  |
| 2667  | 4         | 12.12%  |
| 6400  | 2         | 6.06%   |
| 2400  | 2         | 6.06%   |
| 4800  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1867  | 1         | 3.03%   |
| 1334  | 1         | 3.03%   |
| 1333  | 1         | 3.03%   |
| 701   | 1         | 3.03%   |

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
| Chicony Electronics                    | 9         | 26.47%  |
| Acer                                   | 7         | 20.59%  |
| Microdia                               | 4         | 11.76%  |
| Realtek Semiconductor                  | 3         | 8.82%   |
| Sonix Technology                       | 2         | 5.88%   |
| Quanta                                 | 2         | 5.88%   |
| Luxvisions Innotech Limited            | 2         | 5.88%   |
| Syntek                                 | 1         | 2.94%   |
| Samsung Electronics                    | 1         | 2.94%   |
| Logitech                               | 1         | 2.94%   |
| Lenovo                                 | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 8.82%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 5.88%   |
| Chicony Integrated Camera                                      | 2         | 5.88%   |
| Acer BisonCam,NB Pro                                           | 2         | 5.88%   |
| Syntek USB2.0 Camera                                           | 1         | 2.94%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 2.94%   |
| Realtek Laptop Camera                                          | 1         | 2.94%   |
| Realtek Integrated Camera                                      | 1         | 2.94%   |
| Realtek EasyCamera                                             | 1         | 2.94%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.94%   |
| Quanta HP Webcam                                               | 1         | 2.94%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.94%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.94%   |
| Microdia Integrated Webcam                                     | 1         | 2.94%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.94%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.94%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 2.94%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.94%   |
| Chicony Web Camera - FHD                                       | 1         | 2.94%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.94%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.94%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.94%   |
| Chicony HP HD Camera                                           | 1         | 2.94%   |
| Chicony HD User Facing                                         | 1         | 2.94%   |
| Chicony FJ Camera                                              | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.94%   |
| Acer ThinkPad Integrated Camera                                | 1         | 2.94%   |
| Acer Integrated Camera                                         | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 5         | 50%     |
| Synaptics                          | 2         | 20%     |
| Realtek USB2.0 Finger Print Bridge | 2         | 20%     |
| STMicroelectronics                 | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 30%     |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 20%     |
| Unknown                                                         | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 10%     |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                           | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 59.46%  |
| 1     | 11        | 29.73%  |
| 2     | 3         | 8.11%   |
| 3     | 1         | 2.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 50%     |
| Graphics card         | 3         | 15%     |
| Net/wireless          | 2         | 10%     |
| Multimedia controller | 2         | 10%     |
| Chipcard              | 2         | 10%     |
| Bluetooth             | 1         | 5%      |

