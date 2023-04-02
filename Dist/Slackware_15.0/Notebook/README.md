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

Total: 46

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Valve     | Jupiter                     | [e9844f7162](https://linux-hardware.org/?probe=e9844f7162) | Mar 13, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [fde666c0ea](https://linux-hardware.org/?probe=fde666c0ea) | Feb 17, 2023 |
| HP        | ENVY Laptop 17-cr0xxx       | [5ce5272a93](https://linux-hardware.org/?probe=5ce5272a93) | Feb 17, 2023 |
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
| 5.15.19     | 11        | 28.21%  |
| 5.19.17     | 2         | 5.13%   |
| 5.17.1      | 2         | 5.13%   |
| 5.15.80     | 2         | 5.13%   |
| 5.13.8      | 2         | 5.13%   |
| 6.1.12      | 1         | 2.56%   |
| 6.1.1       | 1         | 2.56%   |
| 5.17.5      | 1         | 2.56%   |
| 5.17.2      | 1         | 2.56%   |
| 5.16.9-joe1 | 1         | 2.56%   |
| 5.16.12     | 1         | 2.56%   |
| 5.15.78.a   | 1         | 2.56%   |
| 5.15.63     | 1         | 2.56%   |
| 5.15.38     | 1         | 2.56%   |
| 5.15.37.a   | 1         | 2.56%   |
| 5.15.33.kjh | 1         | 2.56%   |
| 5.15.27     | 1         | 2.56%   |
| 5.15.1      | 1         | 2.56%   |
| 5.14.9      | 1         | 2.56%   |
| 5.14.8      | 1         | 2.56%   |
| 5.14.10     | 1         | 2.56%   |
| 5.14.0      | 1         | 2.56%   |
| 5.13.5      | 1         | 2.56%   |
| 5.13.11     | 1         | 2.56%   |
| 5.10.91     | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 11        | 28.21%  |
| 5.19.17 | 2         | 5.13%   |
| 5.17.1  | 2         | 5.13%   |
| 5.15.80 | 2         | 5.13%   |
| 5.13.8  | 2         | 5.13%   |
| 6.1.12  | 1         | 2.56%   |
| 6.1.1   | 1         | 2.56%   |
| 5.17.5  | 1         | 2.56%   |
| 5.17.2  | 1         | 2.56%   |
| 5.16.9  | 1         | 2.56%   |
| 5.16.12 | 1         | 2.56%   |
| 5.15.78 | 1         | 2.56%   |
| 5.15.63 | 1         | 2.56%   |
| 5.15.38 | 1         | 2.56%   |
| 5.15.37 | 1         | 2.56%   |
| 5.15.33 | 1         | 2.56%   |
| 5.15.27 | 1         | 2.56%   |
| 5.15.1  | 1         | 2.56%   |
| 5.14.9  | 1         | 2.56%   |
| 5.14.8  | 1         | 2.56%   |
| 5.14.10 | 1         | 2.56%   |
| 5.14.0  | 1         | 2.56%   |
| 5.13.5  | 1         | 2.56%   |
| 5.13.11 | 1         | 2.56%   |
| 5.10.91 | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 20        | 52.63%  |
| 5.17    | 4         | 10.53%  |
| 5.13    | 4         | 10.53%  |
| 5.14    | 3         | 7.89%   |
| 6.1     | 2         | 5.26%   |
| 5.19    | 2         | 5.26%   |
| 5.16    | 2         | 5.26%   |
| 5.10    | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 21        | 53.85%  |
| XFCE      | 8         | 20.51%  |
| Unknown   | 4         | 10.26%  |
| xwmconfig | 1         | 2.56%   |
| MATE      | 1         | 2.56%   |
| KDE       | 1         | 2.56%   |
| GNOME     | 1         | 2.56%   |
| awesome   | 1         | 2.56%   |
| 2bwm      | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 23        | 57.5%   |
| Tty     | 14        | 35%     |
| Wayland | 3         | 7.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 25        | 64.1%   |
| Unknown | 9         | 23.08%  |
| XDM     | 4         | 10.26%  |
| GDM     | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 29        | 76.32%  |
| pt_BR | 2         | 5.26%   |
| it_IT | 2         | 5.26%   |
| fr_FR | 2         | 5.26%   |
| de_DE | 2         | 5.26%   |
| ru_RU | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 23        | 60.53%  |
| BIOS | 15        | 39.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 31        | 81.58%  |
| Overlay | 3         | 7.89%   |
| Btrfs   | 3         | 7.89%   |
| Xfs     | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 25        | 65.79%  |
| MBR     | 7         | 18.42%  |
| Unknown | 6         | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 82.05%  |
| Yes       | 7         | 17.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 57.89%  |
| Yes       | 16        | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 10        | 26.32%  |
| Lenovo           | 9         | 23.68%  |
| MSI              | 4         | 10.53%  |
| Dell             | 4         | 10.53%  |
| ASUSTek Computer | 3         | 7.89%   |
| Valve            | 1         | 2.63%   |
| System76         | 1         | 2.63%   |
| Sony             | 1         | 2.63%   |
| Notebook         | 1         | 2.63%   |
| Fujitsu          | 1         | 2.63%   |
| Framework        | 1         | 2.63%   |
| Dynabook         | 1         | 2.63%   |
| Acer             | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 5.26%   |
| Valve Jupiter                            | 1         | 2.63%   |
| System76 Oryx Pro                        | 1         | 2.63%   |
| Sony SVE1713A1EW                         | 1         | 2.63%   |
| Notebook X170KM-G                        | 1         | 2.63%   |
| MSI Modern 14 B11MO                      | 1         | 2.63%   |
| MSI Modern 14 B10MW                      | 1         | 2.63%   |
| MSI GP76 Leopard 11UG                    | 1         | 2.63%   |
| MSI GE76 Raider 11UE                     | 1         | 2.63%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 2.63%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 2.63%   |
| Lenovo ThinkPad T61 765912G              | 1         | 2.63%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 2.63%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 2.63%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 2.63%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2.63%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2.63%   |
| HP ProBook 6570b                         | 1         | 2.63%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2.63%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2.63%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 2.63%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 2.63%   |
| HP Laptop 15-bs1xx                       | 1         | 2.63%   |
| HP ENVY Laptop 17-cr0xxx                 | 1         | 2.63%   |
| HP EliteBook 8440p                       | 1         | 2.63%   |
| HP EliteBook 840 G5                      | 1         | 2.63%   |
| HP 245 G7 Notebook PC                    | 1         | 2.63%   |
| Fujitsu LIFEBOOK A544                    | 1         | 2.63%   |
| Framework Laptop                         | 1         | 2.63%   |
| Dynabook P1-C7MP-BL                      | 1         | 2.63%   |
| Dell Vostro 3500                         | 1         | 2.63%   |
| Dell Precision M4700                     | 1         | 2.63%   |
| Dell Latitude 3520                       | 1         | 2.63%   |
| Dell Inspiron 15-3552                    | 1         | 2.63%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 2.63%   |
| Acer Nitro AN515-54                      | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 21.05%  |
| MSI Modern          | 2         | 5.26%   |
| HP Pavilion         | 2         | 5.26%   |
| HP OMEN             | 2         | 5.26%   |
| HP EliteBook        | 2         | 5.26%   |
| ASUS VivoBook       | 2         | 5.26%   |
| Valve Jupiter       | 1         | 2.63%   |
| System76 Oryx       | 1         | 2.63%   |
| Sony SVE1713A1EW    | 1         | 2.63%   |
| Notebook X170KM-G   | 1         | 2.63%   |
| MSI GP76            | 1         | 2.63%   |
| MSI GE76            | 1         | 2.63%   |
| Lenovo IdeaPad      | 1         | 2.63%   |
| HP ProBook          | 1         | 2.63%   |
| HP Laptop           | 1         | 2.63%   |
| HP ENVY             | 1         | 2.63%   |
| HP 245              | 1         | 2.63%   |
| Fujitsu LIFEBOOK    | 1         | 2.63%   |
| Framework Laptop    | 1         | 2.63%   |
| Dynabook P1-C7MP-BL | 1         | 2.63%   |
| Dell Vostro         | 1         | 2.63%   |
| Dell Precision      | 1         | 2.63%   |
| Dell Latitude       | 1         | 2.63%   |
| Dell Inspiron       | 1         | 2.63%   |
| ASUS ROG            | 1         | 2.63%   |
| Acer Nitro          | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 18.42%  |
| 2020 | 6         | 15.79%  |
| 2022 | 5         | 13.16%  |
| 2012 | 5         | 13.16%  |
| 2017 | 4         | 10.53%  |
| 2019 | 2         | 5.26%   |
| 2010 | 2         | 5.26%   |
| 2018 | 1         | 2.63%   |
| 2016 | 1         | 2.63%   |
| 2015 | 1         | 2.63%   |
| 2014 | 1         | 2.63%   |
| 2013 | 1         | 2.63%   |
| 2009 | 1         | 2.63%   |
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
| Disabled | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 94.74%  |
| Yes  | 2         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 9         | 23.68%  |
| 8.01-16.0   | 9         | 23.68%  |
| 4.01-8.0    | 7         | 18.42%  |
| 3.01-4.0    | 7         | 18.42%  |
| 32.01-64.0  | 3         | 7.89%   |
| 24.01-32.0  | 2         | 5.26%   |
| 64.01-256.0 | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 15        | 36.59%  |
| 1.01-2.0   | 9         | 21.95%  |
| 4.01-8.0   | 8         | 19.51%  |
| 0.51-1.0   | 4         | 9.76%   |
| 3.01-4.0   | 2         | 4.88%   |
| 0.01-0.5   | 2         | 4.88%   |
| 16.01-24.0 | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 73.68%  |
| 2      | 9         | 23.68%  |
| 4      | 1         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 78.95%  |
| Yes       | 8         | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 81.58%  |
| No        | 7         | 18.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 89.47%  |
| No        | 4         | 10.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 11        | 28.95%  |
| Kazakhstan   | 3         | 7.89%   |
| Italy        | 3         | 7.89%   |
| South Africa | 2         | 5.26%   |
| Portugal     | 2         | 5.26%   |
| Japan        | 2         | 5.26%   |
| Germany      | 2         | 5.26%   |
| France       | 2         | 5.26%   |
| Brazil       | 2         | 5.26%   |
| Sweden       | 1         | 2.63%   |
| Spain        | 1         | 2.63%   |
| Serbia       | 1         | 2.63%   |
| Russia       | 1         | 2.63%   |
| Mexico       | 1         | 2.63%   |
| India        | 1         | 2.63%   |
| Greece       | 1         | 2.63%   |
| Chile        | 1         | 2.63%   |
| Canada       | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 5.13%   |
| Sun Prairie       | 2         | 5.13%   |
| Lisbon            | 2         | 5.13%   |
| Frignano          | 2         | 5.13%   |
| Worpswede         | 1         | 2.56%   |
| Tsukuba           | 1         | 2.56%   |
| Skövde           | 1         | 2.56%   |
| Sao Paulo         | 1         | 2.56%   |
| Santiago          | 1         | 2.56%   |
| Round Rock        | 1         | 2.56%   |
| Reno              | 1         | 2.56%   |
| Renazzo           | 1         | 2.56%   |
| Plainwell         | 1         | 2.56%   |
| Ōtsu             | 1         | 2.56%   |
| Oberstreit        | 1         | 2.56%   |
| Moscow            | 1         | 2.56%   |
| Montreal          | 1         | 2.56%   |
| Mexico City       | 1         | 2.56%   |
| McKinney          | 1         | 2.56%   |
| Luxeuil-les-Bains | 1         | 2.56%   |
| League City       | 1         | 2.56%   |
| Karaganda         | 1         | 2.56%   |
| Johannesburg      | 1         | 2.56%   |
| Hayward           | 1         | 2.56%   |
| Greater Noida     | 1         | 2.56%   |
| Fortaleza         | 1         | 2.56%   |
| Federal Way       | 1         | 2.56%   |
| Fayetteville      | 1         | 2.56%   |
| Chessy            | 1         | 2.56%   |
| Chania            | 1         | 2.56%   |
| Cape Town         | 1         | 2.56%   |
| Bremervoerde      | 1         | 2.56%   |
| Belgrade          | 1         | 2.56%   |
| Algeciras         | 1         | 2.56%   |
| Abingdon          | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 24.44%  |
| WDC                 | 6         | 7      | 13.33%  |
| Toshiba             | 3         | 3      | 6.67%   |
| SanDisk             | 3         | 4      | 6.67%   |
| Kingston            | 3         | 3      | 6.67%   |
| Intel               | 3         | 3      | 6.67%   |
| HGST                | 3         | 3      | 6.67%   |
| SK hynix            | 2         | 2      | 4.44%   |
| Micron Technology   | 2         | 2      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| Unknown             | 1         | 1      | 2.22%   |
| Silicon Motion      | 1         | 1      | 2.22%   |
| Seagate             | 1         | 1      | 2.22%   |
| Plextor             | 1         | 1      | 2.22%   |
| KIOXIA              | 1         | 1      | 2.22%   |
| Hewlett-Packard     | 1         | 2      | 2.22%   |
| Gigabyte Technology | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                               | 2         | 4.08%   |
| Intel SSD 660P Series 512GB                            | 2         | 4.08%   |
| HGST HTS725050A7E630 500GB                             | 2         | 4.08%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                         | 1         | 2.04%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                         | 1         | 2.04%   |
| WDC WD10JPVT-08A1YT2 1TB                               | 1         | 2.04%   |
| WDC WD Green 2.5 240GB SSD                             | 1         | 2.04%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                     | 1         | 2.04%   |
| Unknown MMC Card  512GB                                | 1         | 2.04%   |
| Toshiba MQ04ABF100 1TB                                 | 1         | 2.04%   |
| Toshiba MQ01ACF032 320GB                               | 1         | 2.04%   |
| Toshiba MQ01ABF050 500GB                               | 1         | 2.04%   |
| SK hynix HFM001TD3JX013N 1TB                           | 1         | 2.04%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB                | 1         | 2.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 1         | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 1         | 2.04%   |
| SanDisk Ultra II 960GB SSD                             | 1         | 2.04%   |
| SanDisk SDSSDA240G 240GB                               | 1         | 2.04%   |
| SanDisk NVMe SSD Drive 1TB                             | 1         | 2.04%   |
| Samsung SSD PM830 2.5 7mm 128GB                        | 1         | 2.04%   |
| Samsung SSD 980 PRO 500GB                              | 1         | 2.04%   |
| Samsung SSD 980 PRO 2TB                                | 1         | 2.04%   |
| Samsung SSD 970 EVO Plus 2TB                           | 1         | 2.04%   |
| Samsung SSD 970 EVO 2TB                                | 1         | 2.04%   |
| Samsung SSD 870 EVO 1TB                                | 1         | 2.04%   |
| Samsung SSD 860 EVO mSATA 500GB                        | 1         | 2.04%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB                 | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB    | 1         | 2.04%   |
| Samsung MZVLQ512HALU-000H1 512GB                       | 1         | 2.04%   |
| Samsung MZVLQ1T0HBLB-00BH1 1TB                         | 1         | 2.04%   |
| Samsung MZVL21T0HCLR-00B00 1TB                         | 1         | 2.04%   |
| Samsung MZVKW512HMJP-000H1 512GB                       | 1         | 2.04%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                   | 1         | 2.04%   |
| Plextor PX-128M6S 128GB SSD                            | 1         | 2.04%   |
| Micron MTFDKBA1T0TFH-1BC1AABHA 1TB                     | 1         | 2.04%   |
| Micron 2210_MTFDHBA512QFD 512GB                        | 1         | 2.04%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                         | 1         | 2.04%   |
| Kingston SUV400S37240G 240GB SSD                       | 1         | 2.04%   |
| Kingston SHSS37A480G 480GB SSD                         | 1         | 2.04%   |
| Kingston SA400S37240G 240GB SSD                        | 1         | 2.04%   |

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
| NVMe | 21        | 26     | 46.67%  |
| SSD  | 13        | 16     | 28.89%  |
| HDD  | 10        | 10     | 22.22%  |
| MMC  | 1         | 1      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 26     | 50%     |
| SATA | 20        | 26     | 47.62%  |
| MMC  | 1         | 1      | 2.38%   |

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
| 501-1000       | 12        | 31.58%  |
| 101-250        | 9         | 23.68%  |
| 251-500        | 8         | 21.05%  |
| 1001-2000      | 4         | 10.53%  |
| 21-50          | 2         | 5.26%   |
| 1-20           | 2         | 5.26%   |
| More than 3000 | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 9         | 23.08%  |
| 1-20      | 8         | 20.51%  |
| 251-500   | 7         | 17.95%  |
| 21-50     | 7         | 17.95%  |
| 51-100    | 4         | 10.26%  |
| 1001-2000 | 2         | 5.13%   |
| 501-1000  | 2         | 5.13%   |

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
| Works    | 30        | 36     | 71.43%  |
| Detected | 8         | 13     | 19.05%  |
| Malfunc  | 4         | 4      | 9.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 23        | 51.11%  |
| Samsung Electronics       | 8         | 17.78%  |
| AMD                       | 4         | 8.89%   |
| SK hynix                  | 2         | 4.44%   |
| SanDisk                   | 2         | 4.44%   |
| Micron Technology         | 2         | 4.44%   |
| Silicon Motion            | 1         | 2.22%   |
| Micron/Crucial Technology | 1         | 2.22%   |
| KIOXIA                    | 1         | 2.22%   |
| Biwin Storage Technology  | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 8.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 8.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 6.12%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 6.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 6.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 6.12%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 4.08%   |
| Micron NVMe Storage Controller                                                   | 2         | 4.08%   |
| Intel SSD 660P Series                                                            | 2         | 4.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 2.04%   |
| SK hynix BC511                                                                   | 1         | 2.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.04%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 2.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2.04%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.04%   |
| Intel SSD 600P Series                                                            | 1         | 2.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 2.04%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 2.04%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 21        | 43.75%  |
| SATA | 19        | 39.58%  |
| RAID | 7         | 14.58%  |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 86.84%  |
| AMD    | 5         | 13.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 10.53%  |
| Intel 12th Gen Core i7-12700H                 | 3         | 7.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 5.26%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.63%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.63%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.63%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.63%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 2.63%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.63%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.63%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.63%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.63%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.63%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.63%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.63%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.63%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.63%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 1         | 2.63%   |
| AMD Custom APU 0405                           | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 13        | 34.21%  |
| Intel Core i5    | 9         | 23.68%  |
| Intel Core i7    | 8         | 21.05%  |
| AMD Ryzen 5      | 2         | 5.26%   |
| Intel Pentium    | 1         | 2.63%   |
| Intel Core i3    | 1         | 2.63%   |
| Intel Core 2 Duo | 1         | 2.63%   |
| Intel Celeron    | 1         | 2.63%   |
| AMD Ryzen 9      | 1         | 2.63%   |
| AMD E1           | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 39.47%  |
| 4      | 10        | 26.32%  |
| 8      | 7         | 18.42%  |
| 14     | 3         | 7.89%   |
| 6      | 2         | 5.26%   |
| 10     | 1         | 2.63%   |

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
| 2      | 34        | 89.47%  |
| 1      | 4         | 10.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 23.68%  |
| 0x306a9    | 5         | 13.16%  |
| 0x806d1    | 4         | 10.53%  |
| 0x906a3    | 3         | 7.89%   |
| 0x806c1    | 3         | 7.89%   |
| 0xa0671    | 1         | 2.63%   |
| 0xa0652    | 1         | 2.63%   |
| 0x906a4    | 1         | 2.63%   |
| 0x806ec    | 1         | 2.63%   |
| 0x806ea    | 1         | 2.63%   |
| 0x406e3    | 1         | 2.63%   |
| 0x406c4    | 1         | 2.63%   |
| 0x306d4    | 1         | 2.63%   |
| 0x306c3    | 1         | 2.63%   |
| 0x20655    | 1         | 2.63%   |
| 0x08900201 | 1         | 2.63%   |
| 0x08600106 | 1         | 2.63%   |
| 0x08108109 | 1         | 2.63%   |
| 0x07000106 | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 15.79%  |
| IvyBridge        | 5         | 13.16%  |
| Icelake          | 5         | 13.16%  |
| Alderlake Hybrid | 4         | 10.53%  |
| Westmere         | 3         | 7.89%   |
| TigerLake        | 3         | 7.89%   |
| Zen 2            | 2         | 5.26%   |
| Skylake          | 2         | 5.26%   |
| Zen+             | 1         | 2.63%   |
| Silvermont       | 1         | 2.63%   |
| Jaguar           | 1         | 2.63%   |
| Haswell          | 1         | 2.63%   |
| Core             | 1         | 2.63%   |
| CometLake        | 1         | 2.63%   |
| Broadwell        | 1         | 2.63%   |
| Unknown          | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 52.94%  |
| Nvidia | 16        | 31.37%  |
| AMD    | 8         | 15.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 7.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 5.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 5.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.85%   |
| AMD Renoir                                                                               | 2         | 3.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.92%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.92%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.92%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.92%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.92%   |
| Intel HD Graphics 630                                                                    | 1         | 1.92%   |
| Intel HD Graphics 620                                                                    | 1         | 1.92%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.92%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.92%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.92%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.92%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 42.11%  |
| Intel + Nvidia | 11        | 28.95%  |
| 1 x AMD        | 7         | 18.42%  |
| 1 x Nvidia     | 3         | 7.89%   |
| AMD + Nvidia   | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 84.21%  |
| Proprietary | 6         | 15.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 63.16%  |
| 0.51-1.0   | 4         | 10.53%  |
| 0.01-0.5   | 4         | 10.53%  |
| 7.01-8.0   | 3         | 7.89%   |
| 5.01-6.0   | 1         | 2.63%   |
| 3.01-4.0   | 1         | 2.63%   |
| 1.01-2.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 10        | 24.39%  |
| LG Display          | 7         | 17.07%  |
| AU Optronics        | 7         | 17.07%  |
| Samsung Electronics | 3         | 7.32%   |
| Hewlett-Packard     | 3         | 7.32%   |
| Chimei Innolux      | 3         | 7.32%   |
| Sharp               | 2         | 4.88%   |
| Lenovo              | 2         | 4.88%   |
| Valve               | 1         | 2.44%   |
| Sony                | 1         | 2.44%   |
| PANDA               | 1         | 2.44%   |
| Dell                | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 4.88%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 2.44%   |
| Sony TV SNY8102 1360x768                                              | 1         | 2.44%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 2.44%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 2.44%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 2.44%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 2.44%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 2.44%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 2.44%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 2.44%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 2.44%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 2.44%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 2.44%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 2.44%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 2.44%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 2.44%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.44%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 2.44%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 1         | 2.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.44%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 2.44%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO439D 1920x1080 382x215mm 17.3-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 380x210mm 17.1-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch         | 1         | 2.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 1         | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 20        | 51.28%  |
| 1366x768 (WXGA) | 9         | 23.08%  |
| 2880x1620       | 2         | 5.13%   |
| 1600x900 (HD+)  | 2         | 5.13%   |
| 1280x800 (WXGA) | 2         | 5.13%   |
| 800x1280        | 1         | 2.56%   |
| 3840x2160 (4K)  | 1         | 2.56%   |
| 2256x1504       | 1         | 2.56%   |
| 1360x768        | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 34.15%  |
| 14     | 7         | 17.07%  |
| 17     | 5         | 12.2%   |
| 13     | 5         | 12.2%   |
| 16     | 2         | 4.88%   |
| 72     | 1         | 2.44%   |
| 27     | 1         | 2.44%   |
| 24     | 1         | 2.44%   |
| 23     | 1         | 2.44%   |
| 21     | 1         | 2.44%   |
| 12     | 1         | 2.44%   |
| 11     | 1         | 2.44%   |
| 7      | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 60.98%  |
| 351-400     | 7         | 17.07%  |
| 201-300     | 3         | 7.32%   |
| 501-600     | 2         | 4.88%   |
| 401-500     | 2         | 4.88%   |
| 1501-2000   | 1         | 2.44%   |
| 1-100       | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 86.84%  |
| 16/10 | 3         | 7.89%   |
| 3/2   | 1         | 2.63%   |
| 0.67  | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 39.02%  |
| 81-90          | 12        | 29.27%  |
| 121-130        | 5         | 12.2%   |
| More than 1000 | 1         | 2.44%   |
| 61-70          | 1         | 2.44%   |
| 51-60          | 1         | 2.44%   |
| 1-40           | 1         | 2.44%   |
| 301-350        | 1         | 2.44%   |
| 251-300        | 1         | 2.44%   |
| 201-250        | 1         | 2.44%   |
| 151-200        | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 50%     |
| 101-120       | 10        | 25%     |
| 161-240       | 4         | 10%     |
| 51-100        | 4         | 10%     |
| More than 240 | 1         | 2.5%    |
| 1-50          | 1         | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 86.84%  |
| 2     | 5         | 13.16%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 45%     |
| Realtek Semiconductor | 21        | 35%     |
| MediaTek              | 3         | 5%      |
| Broadcom Limited      | 3         | 5%      |
| ASIX Electronics      | 2         | 3.33%   |
| Sitecom Europe        | 1         | 1.67%   |
| Ralink Technology     | 1         | 1.67%   |
| Qualcomm Atheros      | 1         | 1.67%   |
| Hewlett-Packard       | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 21.92%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 5.48%   |
| Intel Wireless 8265 / 8275                                        | 3         | 4.11%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.74%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.74%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter          | 2         | 2.74%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.74%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.74%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 2.74%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.37%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.37%   |
| Intel Wireless 8260                                               | 1         | 1.37%   |
| Intel Wireless 7260                                               | 1         | 1.37%   |
| Intel Wireless 3165                                               | 1         | 1.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.37%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.37%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.37%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.37%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.37%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 1.37%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 64.1%   |
| Realtek Semiconductor | 5         | 12.82%  |
| MediaTek              | 3         | 7.69%   |
| Broadcom Limited      | 3         | 7.69%   |
| Sitecom Europe        | 1         | 2.56%   |
| Ralink Technology     | 1         | 2.56%   |
| Qualcomm Atheros      | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 10%     |
| Intel Wireless 8265 / 8275                                    | 3         | 7.5%    |
| Intel Wi-Fi 6 AX200                                           | 3         | 7.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 5%      |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter      | 2         | 5%      |
| Intel Wi-Fi 6 AX201                                           | 2         | 5%      |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 5%      |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 5%      |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.5%    |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 2.5%    |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.5%    |
| Intel Wireless 8260                                           | 1         | 2.5%    |
| Intel Wireless 7260                                           | 1         | 2.5%    |
| Intel Wireless 3165                                           | 1         | 2.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 2.5%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 61.29%  |
| Intel                 | 10        | 32.26%  |
| ASIX Electronics      | 2         | 6.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 50%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.38%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 6.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 6.25%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.13%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.13%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 3.13%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.13%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 3.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 54.29%  |
| Ethernet | 31        | 44.29%  |
| Modem    | 1         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 78.57%  |
| Ethernet | 9         | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 73.68%  |
| 1     | 10        | 26.32%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 86.84%  |
| Yes  | 5         | 13.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 61.76%  |
| Broadcom              | 5         | 14.71%  |
| IMC Networks          | 4         | 11.76%  |
| Realtek Semiconductor | 3         | 8.82%   |
| Foxconn / Hon Hai     | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 20.59%  |
| Intel AX201 Bluetooth                            | 5         | 14.71%  |
| Intel AX210 Bluetooth                            | 4         | 11.76%  |
| Intel AX200 Bluetooth                            | 3         | 8.82%   |
| IMC Networks Wireless_Device                     | 3         | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 5.88%   |
| Realtek Bluetooth Radio                          | 1         | 2.94%   |
| Intel Bluetooth Device                           | 1         | 2.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 2.94%   |
| IMC Networks Bluetooth Radio                     | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 2.94%   |
| Broadcom HP Portable SoftSailing                 | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 2.94%   |
| Broadcom BCM20702A0                              | 1         | 2.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 33        | 58.93%  |
| Nvidia              | 14        | 25%     |
| AMD                 | 8         | 14.29%  |
| C-Media Electronics | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 8.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.2%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 6.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 6.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 4.92%   |
| Nvidia Audio device                                                                               | 3         | 4.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.92%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.28%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 3.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.64%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.64%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.64%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.64%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 27.03%  |
| SK hynix            | 9         | 24.32%  |
| Kingston            | 7         | 18.92%  |
| Micron Technology   | 3         | 8.11%   |
| Crucial             | 3         | 8.11%   |
| Neo Forza           | 1         | 2.7%    |
| Nanya Technology    | 1         | 2.7%    |
| Essencore Limited   | 1         | 2.7%    |
| Corsair             | 1         | 2.7%    |
| A-DATA Technology   | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s     | 2         | 5.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 5.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 2.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s            | 1         | 2.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 2.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.56%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 2.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.56%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 2.56%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 2.56%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 2.56%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s              | 1         | 2.56%   |
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s            | 1         | 2.56%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 2.56%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.56%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 2.56%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.56%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.56%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s               | 1         | 2.56%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 2.56%   |
| Kingston RAM 9905712-007.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.56%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 2.56%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.56%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 2.56%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 2.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 2.56%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 3200MT/s                | 1         | 2.56%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 2.56%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 53.13%  |
| DDR3   | 10        | 31.25%  |
| LPDDR5 | 3         | 9.38%   |
| LPDDR3 | 1         | 3.13%   |
| DDR5   | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 90.63%  |
| Row Of Chips | 3         | 9.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 45.95%  |
| 4096  | 12        | 32.43%  |
| 16384 | 4         | 10.81%  |
| 2048  | 3         | 8.11%   |
| 32768 | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 31.43%  |
| 1600  | 9         | 25.71%  |
| 2667  | 4         | 11.43%  |
| 6400  | 2         | 5.71%   |
| 2400  | 2         | 5.71%   |
| 4800  | 1         | 2.86%   |
| 4266  | 1         | 2.86%   |
| 2133  | 1         | 2.86%   |
| 1867  | 1         | 2.86%   |
| 1334  | 1         | 2.86%   |
| 1333  | 1         | 2.86%   |
| 701   | 1         | 2.86%   |

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
| Chicony Electronics                    | 10        | 28.57%  |
| Acer                                   | 6         | 17.14%  |
| Microdia                               | 4         | 11.43%  |
| Realtek Semiconductor                  | 3         | 8.57%   |
| Sonix Technology                       | 2         | 5.71%   |
| Quanta                                 | 2         | 5.71%   |
| Luxvisions Innotech Limited            | 2         | 5.71%   |
| Syntek                                 | 1         | 2.86%   |
| Samsung Electronics                    | 1         | 2.86%   |
| Logitech                               | 1         | 2.86%   |
| Lenovo                                 | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Bison Electronics                      | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 8.57%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 5.71%   |
| Chicony Integrated Camera                                      | 2         | 5.71%   |
| Acer BisonCam,NB Pro                                           | 2         | 5.71%   |
| Syntek USB2.0 Camera                                           | 1         | 2.86%   |
| Samsung Galaxy A5 (MTP)                                        | 1         | 2.86%   |
| Realtek Laptop Camera                                          | 1         | 2.86%   |
| Realtek Integrated Camera                                      | 1         | 2.86%   |
| Realtek EasyCamera                                             | 1         | 2.86%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.86%   |
| Quanta HP Webcam                                               | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.86%   |
| Microdia Integrated Webcam                                     | 1         | 2.86%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.86%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.86%   |
| Logitech C920 PRO HD Webcam                                    | 1         | 2.86%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.86%   |
| Chicony Web Camera - FHD                                       | 1         | 2.86%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.86%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.86%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 2.86%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.86%   |
| Chicony HP HD Camera                                           | 1         | 2.86%   |
| Chicony HD User Facing                                         | 1         | 2.86%   |
| Chicony FJ Camera                                              | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.86%   |
| Bison ThinkPad Integrated Camera                               | 1         | 2.86%   |
| Acer Integrated Camera                                         | 1         | 2.86%   |

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
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 10%     |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 10%     |
| Synaptics UWP WBDI                                              | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                           | 1         | 10%     |
| Unknown                                                         | 1         | 10%     |

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
| 0     | 23        | 58.97%  |
| 1     | 12        | 30.77%  |
| 2     | 4         | 10.26%  |

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

