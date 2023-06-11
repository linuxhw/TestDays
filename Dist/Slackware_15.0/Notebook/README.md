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

Total: 48

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Acer      | Swift SF114-34              | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| Apple     | MacBookAir7,2               | [941aa94750](https://linux-hardware.org/?probe=941aa94750) | Apr 13, 2023 |
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
| 5.15.19     | 11        | 27.5%   |
| 5.19.17     | 2         | 5%      |
| 5.17.1      | 2         | 5%      |
| 5.15.80     | 2         | 5%      |
| 5.15.38     | 2         | 5%      |
| 5.13.8      | 2         | 5%      |
| 6.1.12      | 1         | 2.5%    |
| 6.1.1       | 1         | 2.5%    |
| 5.17.5      | 1         | 2.5%    |
| 5.17.2      | 1         | 2.5%    |
| 5.16.9-joe1 | 1         | 2.5%    |
| 5.16.12     | 1         | 2.5%    |
| 5.15.78.a   | 1         | 2.5%    |
| 5.15.63     | 1         | 2.5%    |
| 5.15.37.a   | 1         | 2.5%    |
| 5.15.33.kjh | 1         | 2.5%    |
| 5.15.27     | 1         | 2.5%    |
| 5.15.1      | 1         | 2.5%    |
| 5.14.9      | 1         | 2.5%    |
| 5.14.8      | 1         | 2.5%    |
| 5.14.10     | 1         | 2.5%    |
| 5.14.0      | 1         | 2.5%    |
| 5.13.5      | 1         | 2.5%    |
| 5.13.11     | 1         | 2.5%    |
| 5.10.91     | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 11        | 27.5%   |
| 5.19.17 | 2         | 5%      |
| 5.17.1  | 2         | 5%      |
| 5.15.80 | 2         | 5%      |
| 5.15.38 | 2         | 5%      |
| 5.13.8  | 2         | 5%      |
| 6.1.12  | 1         | 2.5%    |
| 6.1.1   | 1         | 2.5%    |
| 5.17.5  | 1         | 2.5%    |
| 5.17.2  | 1         | 2.5%    |
| 5.16.9  | 1         | 2.5%    |
| 5.16.12 | 1         | 2.5%    |
| 5.15.78 | 1         | 2.5%    |
| 5.15.63 | 1         | 2.5%    |
| 5.15.37 | 1         | 2.5%    |
| 5.15.33 | 1         | 2.5%    |
| 5.15.27 | 1         | 2.5%    |
| 5.15.1  | 1         | 2.5%    |
| 5.14.9  | 1         | 2.5%    |
| 5.14.8  | 1         | 2.5%    |
| 5.14.10 | 1         | 2.5%    |
| 5.14.0  | 1         | 2.5%    |
| 5.13.5  | 1         | 2.5%    |
| 5.13.11 | 1         | 2.5%    |
| 5.10.91 | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 21        | 53.85%  |
| 5.17    | 4         | 10.26%  |
| 5.13    | 4         | 10.26%  |
| 5.14    | 3         | 7.69%   |
| 6.1     | 2         | 5.13%   |
| 5.19    | 2         | 5.13%   |
| 5.16    | 2         | 5.13%   |
| 5.10    | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 21        | 52.5%   |
| XFCE      | 9         | 22.5%   |
| Unknown   | 4         | 10%     |
| xwmconfig | 1         | 2.5%    |
| MATE      | 1         | 2.5%    |
| KDE       | 1         | 2.5%    |
| GNOME     | 1         | 2.5%    |
| awesome   | 1         | 2.5%    |
| 2bwm      | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 24        | 58.54%  |
| Tty     | 14        | 34.15%  |
| Wayland | 3         | 7.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 25        | 62.5%   |
| Unknown | 9         | 22.5%   |
| XDM     | 4         | 10%     |
| LightDM | 1         | 2.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 29        | 74.36%  |
| de_DE | 3         | 7.69%   |
| pt_BR | 2         | 5.13%   |
| it_IT | 2         | 5.13%   |
| fr_FR | 2         | 5.13%   |
| ru_RU | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 24        | 61.54%  |
| BIOS | 15        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 82.05%  |
| Overlay | 3         | 7.69%   |
| Btrfs   | 3         | 7.69%   |
| Xfs     | 1         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 26        | 66.67%  |
| MBR     | 7         | 17.95%  |
| Unknown | 6         | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 80%     |
| Yes       | 8         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 58.97%  |
| Yes       | 16        | 41.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 10        | 25.64%  |
| Lenovo           | 9         | 23.08%  |
| MSI              | 4         | 10.26%  |
| Dell             | 4         | 10.26%  |
| ASUSTek Computer | 3         | 7.69%   |
| Acer             | 2         | 5.13%   |
| Valve            | 1         | 2.56%   |
| System76         | 1         | 2.56%   |
| Sony             | 1         | 2.56%   |
| Notebook         | 1         | 2.56%   |
| Fujitsu          | 1         | 2.56%   |
| Framework        | 1         | 2.56%   |
| Dynabook         | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 5.13%   |
| Valve Jupiter                            | 1         | 2.56%   |
| System76 Oryx Pro                        | 1         | 2.56%   |
| Sony SVE1713A1EW                         | 1         | 2.56%   |
| Notebook X170KM-G                        | 1         | 2.56%   |
| MSI Modern 14 B11MO                      | 1         | 2.56%   |
| MSI Modern 14 B10MW                      | 1         | 2.56%   |
| MSI GP76 Leopard 11UG                    | 1         | 2.56%   |
| MSI GE76 Raider 11UE                     | 1         | 2.56%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 2.56%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 2.56%   |
| Lenovo ThinkPad T61 765912G              | 1         | 2.56%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 2.56%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 2.56%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 2.56%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2.56%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2.56%   |
| HP ProBook 6570b                         | 1         | 2.56%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2.56%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2.56%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 2.56%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 2.56%   |
| HP Laptop 15-bs1xx                       | 1         | 2.56%   |
| HP ENVY Laptop 17-cr0xxx                 | 1         | 2.56%   |
| HP EliteBook 8440p                       | 1         | 2.56%   |
| HP EliteBook 840 G5                      | 1         | 2.56%   |
| HP 245 G7 Notebook PC                    | 1         | 2.56%   |
| Fujitsu LIFEBOOK A544                    | 1         | 2.56%   |
| Framework Laptop                         | 1         | 2.56%   |
| Dynabook P1-C7MP-BL                      | 1         | 2.56%   |
| Dell Vostro 3500                         | 1         | 2.56%   |
| Dell Precision M4700                     | 1         | 2.56%   |
| Dell Latitude 3520                       | 1         | 2.56%   |
| Dell Inspiron 15-3552                    | 1         | 2.56%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 2.56%   |
| Acer Swift SF114-34                      | 1         | 2.56%   |
| Acer Nitro AN515-54                      | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 20.51%  |
| MSI Modern          | 2         | 5.13%   |
| HP Pavilion         | 2         | 5.13%   |
| HP OMEN             | 2         | 5.13%   |
| HP EliteBook        | 2         | 5.13%   |
| ASUS VivoBook       | 2         | 5.13%   |
| Valve Jupiter       | 1         | 2.56%   |
| System76 Oryx       | 1         | 2.56%   |
| Sony SVE1713A1EW    | 1         | 2.56%   |
| Notebook X170KM-G   | 1         | 2.56%   |
| MSI GP76            | 1         | 2.56%   |
| MSI GE76            | 1         | 2.56%   |
| Lenovo IdeaPad      | 1         | 2.56%   |
| HP ProBook          | 1         | 2.56%   |
| HP Laptop           | 1         | 2.56%   |
| HP ENVY             | 1         | 2.56%   |
| HP 245              | 1         | 2.56%   |
| Fujitsu LIFEBOOK    | 1         | 2.56%   |
| Framework Laptop    | 1         | 2.56%   |
| Dynabook P1-C7MP-BL | 1         | 2.56%   |
| Dell Vostro         | 1         | 2.56%   |
| Dell Precision      | 1         | 2.56%   |
| Dell Latitude       | 1         | 2.56%   |
| Dell Inspiron       | 1         | 2.56%   |
| ASUS ROG            | 1         | 2.56%   |
| Acer Swift          | 1         | 2.56%   |
| Acer Nitro          | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 17.95%  |
| 2020 | 7         | 17.95%  |
| 2022 | 5         | 12.82%  |
| 2012 | 5         | 12.82%  |
| 2017 | 4         | 10.26%  |
| 2019 | 2         | 5.13%   |
| 2010 | 2         | 5.13%   |
| 2018 | 1         | 2.56%   |
| 2016 | 1         | 2.56%   |
| 2015 | 1         | 2.56%   |
| 2014 | 1         | 2.56%   |
| 2013 | 1         | 2.56%   |
| 2009 | 1         | 2.56%   |
| 2007 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 94.87%  |
| Yes  | 2         | 5.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 9         | 23.08%  |
| 8.01-16.0   | 9         | 23.08%  |
| 3.01-4.0    | 8         | 20.51%  |
| 4.01-8.0    | 7         | 17.95%  |
| 32.01-64.0  | 3         | 7.69%   |
| 24.01-32.0  | 2         | 5.13%   |
| 64.01-256.0 | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 15        | 35.71%  |
| 1.01-2.0   | 10        | 23.81%  |
| 4.01-8.0   | 8         | 19.05%  |
| 0.51-1.0   | 4         | 9.52%   |
| 3.01-4.0   | 2         | 4.76%   |
| 0.01-0.5   | 2         | 4.76%   |
| 16.01-24.0 | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 74.36%  |
| 2      | 9         | 23.08%  |
| 4      | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 79.49%  |
| Yes       | 8         | 20.51%  |

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
| Yes       | 39        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 89.74%  |
| No        | 4         | 10.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 11        | 28.21%  |
| Kazakhstan   | 3         | 7.69%   |
| Italy        | 3         | 7.69%   |
| Germany      | 3         | 7.69%   |
| South Africa | 2         | 5.13%   |
| Portugal     | 2         | 5.13%   |
| Japan        | 2         | 5.13%   |
| France       | 2         | 5.13%   |
| Brazil       | 2         | 5.13%   |
| Sweden       | 1         | 2.56%   |
| Spain        | 1         | 2.56%   |
| Serbia       | 1         | 2.56%   |
| Russia       | 1         | 2.56%   |
| Mexico       | 1         | 2.56%   |
| India        | 1         | 2.56%   |
| Greece       | 1         | 2.56%   |
| Chile        | 1         | 2.56%   |
| Canada       | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 5%      |
| Sun Prairie       | 2         | 5%      |
| Lisbon            | 2         | 5%      |
| Frignano          | 2         | 5%      |
| Worpswede         | 1         | 2.5%    |
| Tsukuba           | 1         | 2.5%    |
| Skövde           | 1         | 2.5%    |
| Sao Paulo         | 1         | 2.5%    |
| Santiago          | 1         | 2.5%    |
| Round Rock        | 1         | 2.5%    |
| Reno              | 1         | 2.5%    |
| Renazzo           | 1         | 2.5%    |
| Plainwell         | 1         | 2.5%    |
| Ōtsu             | 1         | 2.5%    |
| Oberstreit        | 1         | 2.5%    |
| Moscow            | 1         | 2.5%    |
| Montreal          | 1         | 2.5%    |
| Mexico City       | 1         | 2.5%    |
| Meuselwitz        | 1         | 2.5%    |
| McKinney          | 1         | 2.5%    |
| Luxeuil-les-Bains | 1         | 2.5%    |
| League City       | 1         | 2.5%    |
| Kent              | 1         | 2.5%    |
| Karaganda         | 1         | 2.5%    |
| Johannesburg      | 1         | 2.5%    |
| Hayward           | 1         | 2.5%    |
| Greater Noida     | 1         | 2.5%    |
| Fortaleza         | 1         | 2.5%    |
| Fayetteville      | 1         | 2.5%    |
| Chessy            | 1         | 2.5%    |
| Chania            | 1         | 2.5%    |
| Cape Town         | 1         | 2.5%    |
| Bremervoerde      | 1         | 2.5%    |
| Belgrade          | 1         | 2.5%    |
| Algeciras         | 1         | 2.5%    |
| Abingdon          | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 16     | 23.91%  |
| WDC                 | 6         | 7      | 13.04%  |
| Toshiba             | 3         | 3      | 6.52%   |
| SK hynix            | 3         | 3      | 6.52%   |
| SanDisk             | 3         | 4      | 6.52%   |
| Kingston            | 3         | 3      | 6.52%   |
| Intel               | 3         | 3      | 6.52%   |
| HGST                | 3         | 3      | 6.52%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| Unknown             | 1         | 1      | 2.17%   |
| Silicon Motion      | 1         | 1      | 2.17%   |
| Seagate             | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| KIOXIA              | 1         | 1      | 2.17%   |
| Hewlett-Packard     | 1         | 2      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 4%      |
| Intel SSD 660P Series 512GB                         | 2         | 4%      |
| HGST HTS725050A7E630 500GB                          | 2         | 4%      |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 2%      |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 2%      |
| WDC WD10JPVT-08A1YT2 1TB                            | 1         | 2%      |
| WDC WD Green 2.5 240GB                              | 1         | 2%      |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                  | 1         | 2%      |
| Unknown MMC Card  512GB                             | 1         | 2%      |
| Toshiba MQ04ABF100 1TB                              | 1         | 2%      |
| Toshiba MQ01ACF032 320GB                            | 1         | 2%      |
| Toshiba MQ01ABF050 500GB                            | 1         | 2%      |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 2%      |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB             | 1         | 2%      |
| SK hynix BC511 256GB                                | 1         | 2%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 1         | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2%      |
| SanDisk Ultra II 960GB SSD                          | 1         | 2%      |
| SanDisk SDSSDA240G 240GB                            | 1         | 2%      |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2%      |
| Samsung SSD PM830 2.5 7mm 128GB                     | 1         | 2%      |
| Samsung SSD 980 PRO 500GB                           | 1         | 2%      |
| Samsung SSD 980 PRO 2TB                             | 1         | 2%      |
| Samsung SSD 970 EVO Plus 2TB                        | 1         | 2%      |
| Samsung SSD 970 EVO 2TB                             | 1         | 2%      |
| Samsung SSD 870 EVO 1TB                             | 1         | 2%      |
| Samsung SSD 860 EVO mSATA 500GB                     | 1         | 2%      |
| Samsung NVMe SSD Drive 256GB                        | 1         | 2%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 2%      |
| Samsung MZVLQ512HALU-000H1 512GB                    | 1         | 2%      |
| Samsung MZVLQ1T0HBLB-00BH1 1024GB                   | 1         | 2%      |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 1         | 2%      |
| Samsung MZVKW512HMJP-000H1 512GB                    | 1         | 2%      |
| Samsung MZ7LN256HCHP-000L7 256GB SSD                | 1         | 2%      |
| Plextor PX-128M6S 128GB SSD                         | 1         | 2%      |
| Micron MTFDKBA1T0TFH-1BC1AABHA 1024GB               | 1         | 2%      |
| Micron 2210_MTFDHBA512QFD 512GB                     | 1         | 2%      |
| KIOXIA KBG40ZNS256G NVMe 256GB                      | 1         | 2%      |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 2%      |
| Kingston SHSS37A480G 480GB SSD                      | 1         | 2%      |

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
| NVMe | 22        | 27     | 47.83%  |
| SSD  | 13        | 16     | 28.26%  |
| HDD  | 10        | 10     | 21.74%  |
| MMC  | 1         | 1      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 22        | 27     | 51.16%  |
| SATA | 20        | 26     | 46.51%  |
| MMC  | 1         | 1      | 2.33%   |

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
| 501-1000       | 12        | 30.77%  |
| 101-250        | 10        | 25.64%  |
| 251-500        | 8         | 20.51%  |
| 1001-2000      | 4         | 10.26%  |
| 21-50          | 2         | 5.13%   |
| 1-20           | 2         | 5.13%   |
| More than 3000 | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 10        | 25%     |
| 1-20      | 8         | 20%     |
| 251-500   | 7         | 17.5%   |
| 21-50     | 7         | 17.5%   |
| 51-100    | 4         | 10%     |
| 1001-2000 | 2         | 5%      |
| 501-1000  | 2         | 5%      |

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
| Works    | 31        | 37     | 72.09%  |
| Detected | 8         | 13     | 18.6%   |
| Malfunc  | 4         | 4      | 9.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 23        | 50%     |
| Samsung Electronics       | 8         | 17.39%  |
| AMD                       | 4         | 8.7%    |
| SK hynix                  | 3         | 6.52%   |
| SanDisk                   | 2         | 4.35%   |
| Micron Technology         | 2         | 4.35%   |
| Silicon Motion            | 1         | 2.17%   |
| Micron/Crucial Technology | 1         | 2.17%   |
| KIOXIA                    | 1         | 2.17%   |
| Biwin Storage Technology  | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 8%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 6%      |
| Samsung NVMe SSD Controller 980                                                  | 3         | 6%      |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 6%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 6%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 6%      |
| SK hynix BC511                                                                   | 2         | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 4%      |
| Micron NVMe Storage Controller                                                   | 2         | 4%      |
| Intel SSD 660P Series                                                            | 2         | 4%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 2%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2%      |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 2%      |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2%      |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 2%      |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2%      |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 2%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2%      |
| Intel SSD 600P Series                                                            | 1         | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 2%      |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 2%      |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 22        | 44.9%   |
| SATA | 19        | 38.78%  |
| RAID | 7         | 14.29%  |
| IDE  | 1         | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 87.18%  |
| AMD    | 5         | 12.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 10.26%  |
| Intel 12th Gen Core i7-12700H                 | 3         | 7.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 5.13%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 2.56%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.56%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 2.56%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.56%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.56%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.56%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.56%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.56%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 1         | 2.56%   |
| AMD Custom APU 0405                           | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 13        | 33.33%  |
| Intel Core i5        | 9         | 23.08%  |
| Intel Core i7        | 8         | 20.51%  |
| AMD Ryzen 5          | 2         | 5.13%   |
| Intel Pentium Silver | 1         | 2.56%   |
| Intel Pentium        | 1         | 2.56%   |
| Intel Core i3        | 1         | 2.56%   |
| Intel Core 2 Duo     | 1         | 2.56%   |
| Intel Celeron        | 1         | 2.56%   |
| AMD Ryzen 9          | 1         | 2.56%   |
| AMD E1               | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 38.46%  |
| 4      | 11        | 28.21%  |
| 8      | 7         | 17.95%  |
| 14     | 3         | 7.69%   |
| 6      | 2         | 5.13%   |
| 10     | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 87.18%  |
| 1      | 5         | 12.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 23.08%  |
| 0x306a9    | 5         | 12.82%  |
| 0x806d1    | 4         | 10.26%  |
| 0x906a3    | 3         | 7.69%   |
| 0x806c1    | 3         | 7.69%   |
| 0xa0671    | 1         | 2.56%   |
| 0xa0652    | 1         | 2.56%   |
| 0x906c0    | 1         | 2.56%   |
| 0x906a4    | 1         | 2.56%   |
| 0x806ec    | 1         | 2.56%   |
| 0x806ea    | 1         | 2.56%   |
| 0x406e3    | 1         | 2.56%   |
| 0x406c4    | 1         | 2.56%   |
| 0x306d4    | 1         | 2.56%   |
| 0x306c3    | 1         | 2.56%   |
| 0x20655    | 1         | 2.56%   |
| 0x08900201 | 1         | 2.56%   |
| 0x08600106 | 1         | 2.56%   |
| 0x08108109 | 1         | 2.56%   |
| 0x07000106 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 15.38%  |
| IvyBridge        | 5         | 12.82%  |
| Icelake          | 5         | 12.82%  |
| Alderlake Hybrid | 4         | 10.26%  |
| Westmere         | 3         | 7.69%   |
| TigerLake        | 3         | 7.69%   |
| Zen 2            | 2         | 5.13%   |
| Skylake          | 2         | 5.13%   |
| Zen+             | 1         | 2.56%   |
| Tremont          | 1         | 2.56%   |
| Silvermont       | 1         | 2.56%   |
| Jaguar           | 1         | 2.56%   |
| Haswell          | 1         | 2.56%   |
| Core             | 1         | 2.56%   |
| CometLake        | 1         | 2.56%   |
| Broadwell        | 1         | 2.56%   |
| Unknown          | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 53.85%  |
| Nvidia | 16        | 30.77%  |
| AMD    | 8         | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 7.55%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 5.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.66%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 5.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.77%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.77%   |
| AMD Renoir                                                                               | 2         | 3.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.89%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.89%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.89%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.89%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.89%   |
| Intel HD Graphics 630                                                                    | 1         | 1.89%   |
| Intel HD Graphics 620                                                                    | 1         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.89%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.89%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.89%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.89%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 43.59%  |
| Intel + Nvidia | 11        | 28.21%  |
| 1 x AMD        | 7         | 17.95%  |
| 1 x Nvidia     | 3         | 7.69%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 33        | 84.62%  |
| Proprietary | 6         | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 64.1%   |
| 0.51-1.0   | 4         | 10.26%  |
| 0.01-0.5   | 4         | 10.26%  |
| 7.01-8.0   | 3         | 7.69%   |
| 5.01-6.0   | 1         | 2.56%   |
| 3.01-4.0   | 1         | 2.56%   |
| 1.01-2.0   | 1         | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 10        | 23.81%  |
| LG Display          | 7         | 16.67%  |
| AU Optronics        | 7         | 16.67%  |
| Chimei Innolux      | 4         | 9.52%   |
| Samsung Electronics | 3         | 7.14%   |
| Hewlett-Packard     | 3         | 7.14%   |
| Sharp               | 2         | 4.76%   |
| Lenovo              | 2         | 4.76%   |
| Valve               | 1         | 2.38%   |
| Sony                | 1         | 2.38%   |
| PANDA               | 1         | 2.38%   |
| Dell                | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 4.76%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 2.38%   |
| Sony TV SNY8102 1360x768                                              | 1         | 2.38%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 2.38%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 2.38%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 2.38%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 2.38%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 2.38%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.38%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 2.38%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 2.38%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 2.38%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 2.38%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 2.38%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 2.38%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.38%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 1         | 2.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.38%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 2.38%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO439D 1920x1080 382x215mm 17.3-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch         | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 21        | 52.5%   |
| 1366x768 (WXGA) | 9         | 22.5%   |
| 2880x1620       | 2         | 5%      |
| 1600x900 (HD+)  | 2         | 5%      |
| 1280x800 (WXGA) | 2         | 5%      |
| 800x1280        | 1         | 2.5%    |
| 3840x2160 (4K)  | 1         | 2.5%    |
| 2256x1504       | 1         | 2.5%    |
| 1360x768        | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 33.33%  |
| 14     | 7         | 16.67%  |
| 13     | 6         | 14.29%  |
| 17     | 5         | 11.9%   |
| 16     | 2         | 4.76%   |
| 72     | 1         | 2.38%   |
| 27     | 1         | 2.38%   |
| 24     | 1         | 2.38%   |
| 23     | 1         | 2.38%   |
| 21     | 1         | 2.38%   |
| 12     | 1         | 2.38%   |
| 11     | 1         | 2.38%   |
| 7      | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 61.9%   |
| 351-400     | 7         | 16.67%  |
| 201-300     | 3         | 7.14%   |
| 501-600     | 2         | 4.76%   |
| 401-500     | 2         | 4.76%   |
| 1501-2000   | 1         | 2.38%   |
| 1-100       | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 87.18%  |
| 16/10 | 3         | 7.69%   |
| 3/2   | 1         | 2.56%   |
| 0.67  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 38.1%   |
| 81-90          | 13        | 30.95%  |
| 121-130        | 5         | 11.9%   |
| More than 1000 | 1         | 2.38%   |
| 61-70          | 1         | 2.38%   |
| 51-60          | 1         | 2.38%   |
| 1-40           | 1         | 2.38%   |
| 301-350        | 1         | 2.38%   |
| 251-300        | 1         | 2.38%   |
| 201-250        | 1         | 2.38%   |
| 151-200        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 51.22%  |
| 101-120       | 10        | 24.39%  |
| 161-240       | 4         | 9.76%   |
| 51-100        | 4         | 9.76%   |
| More than 240 | 1         | 2.44%   |
| 1-50          | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 87.18%  |
| 2     | 5         | 12.82%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 45.16%  |
| Realtek Semiconductor | 21        | 33.87%  |
| MediaTek              | 3         | 4.84%   |
| Broadcom Limited      | 3         | 4.84%   |
| ASIX Electronics      | 2         | 3.23%   |
| Sitecom Europe        | 1         | 1.61%   |
| Ralink Technology     | 1         | 1.61%   |
| Qualcomm Atheros      | 1         | 1.61%   |
| Huawei Technologies   | 1         | 1.61%   |
| Hewlett-Packard       | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 21.33%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 5.33%   |
| Intel Wireless 8265 / 8275                                        | 3         | 4%      |
| Intel Wi-Fi 6 AX200                                               | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.67%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.67%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.67%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.67%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 2.67%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.33%   |
| Intel Wireless 8260                                               | 1         | 1.33%   |
| Intel Wireless 7260                                               | 1         | 1.33%   |
| Intel Wireless 3165                                               | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.33%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.33%   |
| Huawei E353/E3131                                                 | 1         | 1.33%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 1.33%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 65%     |
| Realtek Semiconductor | 5         | 12.5%   |
| MediaTek              | 3         | 7.5%    |
| Broadcom Limited      | 3         | 7.5%    |
| Sitecom Europe        | 1         | 2.5%    |
| Ralink Technology     | 1         | 2.5%    |
| Qualcomm Atheros      | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 9.76%   |
| Intel Wireless 8265 / 8275                                    | 3         | 7.32%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 7.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 4.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 4.88%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 4.88%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 4.88%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.44%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 2.44%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.44%   |
| Intel Wireless 8260                                           | 1         | 2.44%   |
| Intel Wireless 7260                                           | 1         | 2.44%   |
| Intel Wireless 3165                                           | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 2.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 2.44%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 59.38%  |
| Intel                 | 10        | 31.25%  |
| ASIX Electronics      | 2         | 6.25%   |
| Huawei Technologies   | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 48.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.09%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 6.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 6.06%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 6.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 3.03%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.03%   |
| Huawei E353/E3131                                                 | 1         | 3.03%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 54.17%  |
| Ethernet | 32        | 44.44%  |
| Modem    | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 76.74%  |
| Ethernet | 10        | 23.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 71.79%  |
| 1     | 11        | 28.21%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 84.62%  |
| Yes  | 6         | 15.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 62.86%  |
| Broadcom              | 5         | 14.29%  |
| IMC Networks          | 4         | 11.43%  |
| Realtek Semiconductor | 3         | 8.57%   |
| Foxconn / Hon Hai     | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 20%     |
| Intel AX201 Bluetooth                            | 6         | 17.14%  |
| Intel AX210 Bluetooth                            | 4         | 11.43%  |
| Intel AX200 Bluetooth                            | 3         | 8.57%   |
| IMC Networks Wireless_Device                     | 3         | 8.57%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 5.71%   |
| Realtek Bluetooth Radio                          | 1         | 2.86%   |
| Intel Bluetooth Device                           | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 2.86%   |
| IMC Networks Bluetooth Radio                     | 1         | 2.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 2.86%   |
| Broadcom HP Portable SoftSailing                 | 1         | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 2.86%   |
| Broadcom BCM20702A0                              | 1         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 2.86%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 34        | 59.65%  |
| Nvidia              | 14        | 24.56%  |
| AMD                 | 8         | 14.04%  |
| C-Media Electronics | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 8.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.06%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 6.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 6.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 4.84%   |
| Nvidia Audio device                                                                               | 3         | 4.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.84%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 3.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.61%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.61%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.61%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.61%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 26.32%  |
| SK hynix            | 9         | 23.68%  |
| Kingston            | 7         | 18.42%  |
| Micron Technology   | 4         | 10.53%  |
| Crucial             | 3         | 7.89%   |
| Neo Forza           | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |
| Essencore Limited   | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s     | 2         | 5%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 5%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 2.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 2.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s            | 1         | 2.5%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 2.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.5%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 2.5%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.5%    |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s             | 1         | 2.5%    |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 2.5%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 2.5%    |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 2.5%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s              | 1         | 2.5%    |
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s            | 1         | 2.5%    |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 2.5%    |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.5%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.5%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.5%    |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s        | 1         | 2.5%    |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 2.5%    |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.5%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 2.5%    |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s               | 1         | 2.5%    |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 2.5%    |
| Kingston RAM 9905712-007.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.5%    |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 2.5%    |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.5%    |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 2.5%    |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 2.5%    |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 3200MT/s                | 1         | 2.5%    |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| A-DATA RAM AO1L16BC4R1-BX7S 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 51.52%  |
| DDR3   | 10        | 30.3%   |
| LPDDR5 | 3         | 9.09%   |
| LPDDR4 | 1         | 3.03%   |
| LPDDR3 | 1         | 3.03%   |
| DDR5   | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 87.88%  |
| Row Of Chips | 4         | 12.12%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 44.74%  |
| 4096  | 14        | 36.84%  |
| 16384 | 5         | 13.16%  |
| 32768 | 1         | 2.63%   |
| 2048  | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 30.56%  |
| 1600  | 9         | 25%     |
| 2667  | 4         | 11.11%  |
| 6400  | 2         | 5.56%   |
| 2400  | 2         | 5.56%   |
| 4800  | 1         | 2.78%   |
| 4267  | 1         | 2.78%   |
| 4266  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1867  | 1         | 2.78%   |
| 1334  | 1         | 2.78%   |
| 1333  | 1         | 2.78%   |
| 701   | 1         | 2.78%   |

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
| Chicony Electronics                    | 11        | 30.56%  |
| Acer                                   | 5         | 13.89%  |
| Microdia                               | 4         | 11.11%  |
| Realtek Semiconductor                  | 3         | 8.33%   |
| Sonix Technology                       | 2         | 5.56%   |
| Quanta                                 | 2         | 5.56%   |
| Luxvisions Innotech Limited            | 2         | 5.56%   |
| Bison Electronics                      | 2         | 5.56%   |
| Syntek                                 | 1         | 2.78%   |
| Samsung Electronics                    | 1         | 2.78%   |
| Logitech                               | 1         | 2.78%   |
| Lenovo                                 | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 8.33%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 5.56%   |
| Chicony Integrated Camera                                      | 2         | 5.56%   |
| Chicony HD User Facing                                         | 2         | 5.56%   |
| Acer BisonCam,NB Pro                                           | 2         | 5.56%   |
| Syntek USB2.0 Camera                                           | 1         | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.78%   |
| Realtek Laptop Camera                                          | 1         | 2.78%   |
| Realtek Integrated Camera                                      | 1         | 2.78%   |
| Realtek EasyCamera                                             | 1         | 2.78%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.78%   |
| Quanta HP Webcam                                               | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.78%   |
| Microdia Integrated Webcam                                     | 1         | 2.78%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.78%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                                    | 1         | 2.78%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.78%   |
| Chicony Web Camera - FHD                                       | 1         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.78%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.78%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 2.78%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.78%   |
| Chicony HP HD Camera                                           | 1         | 2.78%   |
| Chicony FJ Camera                                              | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.78%   |
| Bison ThinkPad Integrated Camera                               | 1         | 2.78%   |
| Bison Integrated Camera                                        | 1         | 2.78%   |

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
| 0     | 24        | 60%     |
| 1     | 12        | 30%     |
| 2     | 3         | 7.5%    |
| 3     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 45.45%  |
| Graphics card         | 4         | 18.18%  |
| Multimedia controller | 3         | 13.64%  |
| Net/wireless          | 2         | 9.09%   |
| Chipcard              | 2         | 9.09%   |
| Bluetooth             | 1         | 4.55%   |

