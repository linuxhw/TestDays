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

Total: 57

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook  | P7xxTM                      | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook  | P7xxTM                      | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo    | ThinkPad E16 Gen 1 21JT0... | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek   | ASUS TUF Dash F15 FX517Z... | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| Dell      | Vostro 3405                 | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [b8ceea98b8](https://linux-hardware.org/?probe=b8ceea98b8) | Aug 18, 2023 |
| Valve     | Jupiter                     | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo    | IdeaPad 5 15ALC05 82LN      | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| HP        | Laptop 14s-fq0xxx           | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
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
| 5.15.19     | 12        | 25%     |
| 5.19.17     | 3         | 6.25%   |
| 5.15.117    | 3         | 6.25%   |
| 6.1.44      | 2         | 4.17%   |
| 5.17.1      | 2         | 4.17%   |
| 5.15.80     | 2         | 4.17%   |
| 5.15.38     | 2         | 4.17%   |
| 5.13.8      | 2         | 4.17%   |
| 6.1.51      | 1         | 2.08%   |
| 6.1.12      | 1         | 2.08%   |
| 6.1.1       | 1         | 2.08%   |
| 5.17.5      | 1         | 2.08%   |
| 5.17.2      | 1         | 2.08%   |
| 5.16.9-joe1 | 1         | 2.08%   |
| 5.16.12     | 1         | 2.08%   |
| 5.15.78.a   | 1         | 2.08%   |
| 5.15.63     | 1         | 2.08%   |
| 5.15.37.a   | 1         | 2.08%   |
| 5.15.33.kjh | 1         | 2.08%   |
| 5.15.27     | 1         | 2.08%   |
| 5.15.1      | 1         | 2.08%   |
| 5.14.9      | 1         | 2.08%   |
| 5.14.8      | 1         | 2.08%   |
| 5.14.10     | 1         | 2.08%   |
| 5.14.0      | 1         | 2.08%   |
| 5.13.5      | 1         | 2.08%   |
| 5.13.11     | 1         | 2.08%   |
| 5.10.91     | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 12        | 25%     |
| 5.19.17  | 3         | 6.25%   |
| 5.15.117 | 3         | 6.25%   |
| 6.1.44   | 2         | 4.17%   |
| 5.17.1   | 2         | 4.17%   |
| 5.15.80  | 2         | 4.17%   |
| 5.15.38  | 2         | 4.17%   |
| 5.13.8   | 2         | 4.17%   |
| 6.1.51   | 1         | 2.08%   |
| 6.1.12   | 1         | 2.08%   |
| 6.1.1    | 1         | 2.08%   |
| 5.17.5   | 1         | 2.08%   |
| 5.17.2   | 1         | 2.08%   |
| 5.16.9   | 1         | 2.08%   |
| 5.16.12  | 1         | 2.08%   |
| 5.15.78  | 1         | 2.08%   |
| 5.15.63  | 1         | 2.08%   |
| 5.15.37  | 1         | 2.08%   |
| 5.15.33  | 1         | 2.08%   |
| 5.15.27  | 1         | 2.08%   |
| 5.15.1   | 1         | 2.08%   |
| 5.14.9   | 1         | 2.08%   |
| 5.14.8   | 1         | 2.08%   |
| 5.14.10  | 1         | 2.08%   |
| 5.14.0   | 1         | 2.08%   |
| 5.13.5   | 1         | 2.08%   |
| 5.13.11  | 1         | 2.08%   |
| 5.10.91  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 53.19%  |
| 6.1     | 5         | 10.64%  |
| 5.17    | 4         | 8.51%   |
| 5.13    | 4         | 8.51%   |
| 5.19    | 3         | 6.38%   |
| 5.14    | 3         | 6.38%   |
| 5.16    | 2         | 4.26%   |
| 5.10    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 22        | 46.81%  |
| XFCE      | 14        | 29.79%  |
| Unknown   | 5         | 10.64%  |
| xwmconfig | 1         | 2.13%   |
| MATE      | 1         | 2.13%   |
| KDE       | 1         | 2.13%   |
| GNOME     | 1         | 2.13%   |
| awesome   | 1         | 2.13%   |
| 2bwm      | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 27        | 55.1%   |
| Tty     | 19        | 38.78%  |
| Wayland | 3         | 6.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 26        | 54.17%  |
| XDM     | 10        | 20.83%  |
| Unknown | 10        | 20.83%  |
| LightDM | 1         | 2.08%   |
| GDM     | 1         | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 36        | 78.26%  |
| de_DE | 3         | 6.52%   |
| pt_BR | 2         | 4.35%   |
| it_IT | 2         | 4.35%   |
| fr_FR | 2         | 4.35%   |
| ru_RU | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 65.22%  |
| BIOS | 16        | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 85.11%  |
| Overlay | 3         | 6.38%   |
| Btrfs   | 3         | 6.38%   |
| Xfs     | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 32        | 69.57%  |
| MBR     | 7         | 15.22%  |
| Unknown | 7         | 15.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 82.98%  |
| Yes       | 8         | 17.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 56.52%  |
| Yes       | 20        | 43.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 12        | 26.09%  |
| Hewlett-Packard  | 11        | 23.91%  |
| Dell             | 5         | 10.87%  |
| MSI              | 4         | 8.7%    |
| ASUSTek Computer | 4         | 8.7%    |
| Notebook         | 2         | 4.35%   |
| Acer             | 2         | 4.35%   |
| Valve            | 1         | 2.17%   |
| System76         | 1         | 2.17%   |
| Sony             | 1         | 2.17%   |
| Fujitsu          | 1         | 2.17%   |
| Framework        | 1         | 2.17%   |
| Dynabook         | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 4.35%   |
| Valve Jupiter                            | 1         | 2.17%   |
| System76 Oryx Pro                        | 1         | 2.17%   |
| Sony SVE1713A1EW                         | 1         | 2.17%   |
| Notebook X170KM-G                        | 1         | 2.17%   |
| Notebook P7xxTM                          | 1         | 2.17%   |
| MSI Modern 14 B11MO                      | 1         | 2.17%   |
| MSI Modern 14 B10MW                      | 1         | 2.17%   |
| MSI GP76 Leopard 11UG                    | 1         | 2.17%   |
| MSI GE76 Raider 11UE                     | 1         | 2.17%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 2.17%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 2.17%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 2.17%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 2.17%   |
| Lenovo ThinkPad T61 765912G              | 1         | 2.17%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 2.17%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 2.17%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 2.17%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 2.17%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 2.17%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 2.17%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 2.17%   |
| HP ProBook 6570b                         | 1         | 2.17%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 2.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 2.17%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 2.17%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 2.17%   |
| HP Laptop 15-bs1xx                       | 1         | 2.17%   |
| HP Laptop 14s-fq0xxx                     | 1         | 2.17%   |
| HP ENVY Laptop 17-cr0xxx                 | 1         | 2.17%   |
| HP EliteBook 8440p                       | 1         | 2.17%   |
| HP EliteBook 840 G5                      | 1         | 2.17%   |
| HP 245 G7 Notebook PC                    | 1         | 2.17%   |
| Fujitsu LIFEBOOK A544                    | 1         | 2.17%   |
| Framework Laptop                         | 1         | 2.17%   |
| Dynabook P1-C7MP-BL                      | 1         | 2.17%   |
| Dell Vostro 3500                         | 1         | 2.17%   |
| Dell Vostro 3405                         | 1         | 2.17%   |
| Dell Precision M4700                     | 1         | 2.17%   |
| Dell Latitude 3520                       | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 10        | 21.74%  |
| MSI Modern          | 2         | 4.35%   |
| Lenovo IdeaPad      | 2         | 4.35%   |
| HP Pavilion         | 2         | 4.35%   |
| HP OMEN             | 2         | 4.35%   |
| HP Laptop           | 2         | 4.35%   |
| HP EliteBook        | 2         | 4.35%   |
| Dell Vostro         | 2         | 4.35%   |
| ASUS VivoBook       | 2         | 4.35%   |
| Valve Jupiter       | 1         | 2.17%   |
| System76 Oryx       | 1         | 2.17%   |
| Sony SVE1713A1EW    | 1         | 2.17%   |
| Notebook X170KM-G   | 1         | 2.17%   |
| Notebook P7xxTM     | 1         | 2.17%   |
| MSI GP76            | 1         | 2.17%   |
| MSI GE76            | 1         | 2.17%   |
| HP ProBook          | 1         | 2.17%   |
| HP ENVY             | 1         | 2.17%   |
| HP 245              | 1         | 2.17%   |
| Fujitsu LIFEBOOK    | 1         | 2.17%   |
| Framework Laptop    | 1         | 2.17%   |
| Dynabook P1-C7MP-BL | 1         | 2.17%   |
| Dell Precision      | 1         | 2.17%   |
| Dell Latitude       | 1         | 2.17%   |
| Dell Inspiron       | 1         | 2.17%   |
| ASUS ROG            | 1         | 2.17%   |
| ASUS ASUS           | 1         | 2.17%   |
| Acer Swift          | 1         | 2.17%   |
| Acer Nitro          | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 21.74%  |
| 2021 | 8         | 17.39%  |
| 2022 | 6         | 13.04%  |
| 2012 | 5         | 10.87%  |
| 2017 | 4         | 8.7%    |
| 2019 | 2         | 4.35%   |
| 2016 | 2         | 4.35%   |
| 2010 | 2         | 4.35%   |
| 2023 | 1         | 2.17%   |
| 2018 | 1         | 2.17%   |
| 2015 | 1         | 2.17%   |
| 2014 | 1         | 2.17%   |
| 2013 | 1         | 2.17%   |
| 2009 | 1         | 2.17%   |
| 2007 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 46        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 46        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 95.65%  |
| Yes  | 2         | 4.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 14        | 30.43%  |
| 16.01-24.0  | 9         | 19.57%  |
| 4.01-8.0    | 8         | 17.39%  |
| 3.01-4.0    | 8         | 17.39%  |
| 32.01-64.0  | 3         | 6.52%   |
| 24.01-32.0  | 2         | 4.35%   |
| 64.01-256.0 | 2         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 16        | 32%     |
| 1.01-2.0   | 12        | 24%     |
| 4.01-8.0   | 11        | 22%     |
| 3.01-4.0   | 4         | 8%      |
| 0.51-1.0   | 4         | 8%      |
| 0.01-0.5   | 2         | 4%      |
| 16.01-24.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 72.34%  |
| 2      | 10        | 21.28%  |
| 4      | 2         | 4.26%   |
| 3      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 82.61%  |
| Yes       | 8         | 17.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 82.61%  |
| No        | 8         | 17.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 89.13%  |
| No        | 5         | 10.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 11        | 23.91%  |
| Portugal     | 3         | 6.52%   |
| Kazakhstan   | 3         | 6.52%   |
| Japan        | 3         | 6.52%   |
| Italy        | 3         | 6.52%   |
| Germany      | 3         | 6.52%   |
| South Africa | 2         | 4.35%   |
| India        | 2         | 4.35%   |
| France       | 2         | 4.35%   |
| Brazil       | 2         | 4.35%   |
| Sweden       | 1         | 2.17%   |
| Spain        | 1         | 2.17%   |
| Serbia       | 1         | 2.17%   |
| Russia       | 1         | 2.17%   |
| Romania      | 1         | 2.17%   |
| Mexico       | 1         | 2.17%   |
| Iran         | 1         | 2.17%   |
| Greece       | 1         | 2.17%   |
| China        | 1         | 2.17%   |
| Chile        | 1         | 2.17%   |
| Canada       | 1         | 2.17%   |
| Argentina    | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 4.26%   |
| Tsukuba           | 2         | 4.26%   |
| Sun Prairie       | 2         | 4.26%   |
| Lisbon            | 2         | 4.26%   |
| Greater Noida     | 2         | 4.26%   |
| Frignano          | 2         | 4.26%   |
| Worpswede         | 1         | 2.13%   |
| Villa Carlos Paz  | 1         | 2.13%   |
| Tehran            | 1         | 2.13%   |
| Skövde           | 1         | 2.13%   |
| Sao Paulo         | 1         | 2.13%   |
| Santiago          | 1         | 2.13%   |
| Round Rock        | 1         | 2.13%   |
| Reno              | 1         | 2.13%   |
| Renazzo           | 1         | 2.13%   |
| Plainwell         | 1         | 2.13%   |
| Ōtsu             | 1         | 2.13%   |
| Oberstreit        | 1         | 2.13%   |
| Moscow            | 1         | 2.13%   |
| Montreal          | 1         | 2.13%   |
| Mexico City       | 1         | 2.13%   |
| Meuselwitz        | 1         | 2.13%   |
| McKinney          | 1         | 2.13%   |
| Luxeuil-les-Bains | 1         | 2.13%   |
| League City       | 1         | 2.13%   |
| Kent              | 1         | 2.13%   |
| Karaganda         | 1         | 2.13%   |
| Johannesburg      | 1         | 2.13%   |
| Hayward           | 1         | 2.13%   |
| Guimaraes         | 1         | 2.13%   |
| Guangzhou         | 1         | 2.13%   |
| Fortaleza         | 1         | 2.13%   |
| Fayetteville      | 1         | 2.13%   |
| Chessy            | 1         | 2.13%   |
| Chania            | 1         | 2.13%   |
| Cape Town         | 1         | 2.13%   |
| Bucharest         | 1         | 2.13%   |
| Bremervoerde      | 1         | 2.13%   |
| Belgrade          | 1         | 2.13%   |
| Algeciras         | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 13        | 19     | 22.41%  |
| WDC                         | 8         | 9      | 13.79%  |
| Kingston                    | 5         | 5      | 8.62%   |
| Intel                       | 5         | 5      | 8.62%   |
| SanDisk                     | 4         | 5      | 6.9%    |
| Toshiba                     | 3         | 3      | 5.17%   |
| SK hynix                    | 3         | 3      | 5.17%   |
| HGST                        | 3         | 3      | 5.17%   |
| Seagate                     | 2         | 2      | 3.45%   |
| Micron Technology           | 2         | 2      | 3.45%   |
| Crucial                     | 2         | 2      | 3.45%   |
| Unknown                     | 1         | 2      | 1.72%   |
| Transcend                   | 1         | 1      | 1.72%   |
| Silicon Motion              | 1         | 1      | 1.72%   |
| Plextor                     | 1         | 1      | 1.72%   |
| KIOXIA                      | 1         | 1      | 1.72%   |
| Kingston Technology Company | 1         | 1      | 1.72%   |
| Hewlett-Packard             | 1         | 2      | 1.72%   |
| Gigabyte Technology         | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 3         | 4.76%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 3.17%   |
| Intel SSD 660P Series 1024GB                          | 2         | 3.17%   |
| HGST HTS725050A7E630 500GB                            | 2         | 3.17%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 1.59%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 1.59%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 1         | 1.59%   |
| WDC WD10JPVT-08A1YT2 1TB                              | 1         | 1.59%   |
| WDC WD Green 2.5 240GB                                | 1         | 1.59%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                    | 1         | 1.59%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 1.59%   |
| Unknown MMC Card  512GB                               | 1         | 1.59%   |
| Transcend TS256GMTE352T-VLV 256GB                     | 1         | 1.59%   |
| Toshiba MQ04ABF100 1TB                                | 1         | 1.59%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 1.59%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 1.59%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 1.59%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB               | 1         | 1.59%   |
| SK hynix BC511 512GB                                  | 1         | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 1         | 1.59%   |
| Seagate ST2000LX001-1RG174 2TB                        | 1         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 1.59%   |
| Sandisk WD PC SN740 SDDQNQD-1T00-1201 1024GB          | 1         | 1.59%   |
| SanDisk Ultra II 960GB SSD                            | 1         | 1.59%   |
| SanDisk SDSSDA240G 240GB                              | 1         | 1.59%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.59%   |
| Samsung SSD PM830 2.5 7mm 128GB                       | 1         | 1.59%   |
| Samsung SSD 980 PRO 500GB                             | 1         | 1.59%   |
| Samsung SSD 980 PRO 2TB                               | 1         | 1.59%   |
| Samsung SSD 980 PRO 1TB                               | 1         | 1.59%   |
| Samsung SSD 970 EVO Plus 500GB                        | 1         | 1.59%   |
| Samsung SSD 970 EVO Plus 2TB                          | 1         | 1.59%   |
| Samsung SSD 970 EVO 2TB                               | 1         | 1.59%   |
| Samsung SSD 870 EVO 1TB                               | 1         | 1.59%   |
| Samsung SSD 860 EVO mSATA 500GB                       | 1         | 1.59%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB   | 1         | 1.59%   |
| Samsung MZVLQ512HALU-000H1 512GB                      | 1         | 1.59%   |
| Samsung MZVLQ1T0HBLB-00BH1 1024GB                     | 1         | 1.59%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 33.33%  |
| Toshiba | 3         | 3      | 25%     |
| HGST    | 3         | 3      | 25%     |
| Seagate | 2         | 2      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 31.25%  |
| Samsung Electronics | 4         | 6      | 25%     |
| WDC                 | 2         | 3      | 12.5%   |
| SanDisk             | 2         | 2      | 12.5%   |
| Plextor             | 1         | 1      | 6.25%   |
| Gigabyte Technology | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 35     | 50%     |
| SSD  | 16        | 19     | 28.57%  |
| HDD  | 11        | 12     | 19.64%  |
| MMC  | 1         | 2      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 35     | 52.83%  |
| SATA | 22        | 29     | 41.51%  |
| SAS  | 2         | 2      | 3.77%   |
| MMC  | 1         | 2      | 1.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 21     | 66.67%  |
| 0.51-1.0   | 8         | 9      | 29.63%  |
| 1.01-2.0   | 1         | 1      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 29.79%  |
| 501-1000       | 13        | 27.66%  |
| 251-500        | 9         | 19.15%  |
| 1001-2000      | 5         | 10.64%  |
| 21-50          | 2         | 4.26%   |
| 1-20           | 2         | 4.26%   |
| More than 3000 | 1         | 2.13%   |
| 2001-3000      | 1         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 13        | 27.08%  |
| 251-500   | 8         | 16.67%  |
| 21-50     | 8         | 16.67%  |
| 1-20      | 8         | 16.67%  |
| 51-100    | 5         | 10.42%  |
| 1001-2000 | 3         | 6.25%   |
| 501-1000  | 3         | 6.25%   |

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
| Works    | 37        | 47     | 72.55%  |
| Detected | 10        | 17     | 19.61%  |
| Malfunc  | 4         | 4      | 7.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 27        | 49.09%  |
| Samsung Electronics         | 9         | 16.36%  |
| AMD                         | 5         | 9.09%   |
| SanDisk                     | 4         | 7.27%   |
| SK hynix                    | 3         | 5.45%   |
| Micron Technology           | 2         | 3.64%   |
| Silicon Motion              | 1         | 1.82%   |
| Micron/Crucial Technology   | 1         | 1.82%   |
| KIOXIA                      | 1         | 1.82%   |
| Kingston Technology Company | 1         | 1.82%   |
| Biwin Storage Technology    | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 6.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 6.67%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 6.67%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 5%      |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 5%      |
| Intel SSD 660P Series                                                            | 3         | 5%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 5%      |
| SK hynix BC511 NVMe SSD                                                          | 2         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 3.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.67%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.67%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.67%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 1.67%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 1.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.67%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.67%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 1.67%   |
| Intel SSD 600P Series                                                            | 1         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.67%   |
| Biwin Storage EX950 NVMe SSD                                                     | 1         | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 28        | 48.28%  |
| SATA | 22        | 37.93%  |
| RAID | 7         | 12.07%  |
| IDE  | 1         | 1.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 80.43%  |
| AMD    | 9         | 19.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 8.7%    |
| Intel 12th Gen Core i7-12700H                 | 3         | 6.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 4.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.35%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 2.17%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.17%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.17%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.17%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 2.17%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.17%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 2.17%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.17%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.17%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 2.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.17%   |
| Intel 12th Gen Core i7-12650H                 | 1         | 2.17%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.17%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.17%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 2.17%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 2.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx | 1         | 2.17%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 1         | 2.17%   |
| AMD Custom APU 0405                           | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 14        | 30.43%  |
| Intel Core i5        | 10        | 21.74%  |
| Intel Core i7        | 9         | 19.57%  |
| AMD Ryzen 7          | 3         | 6.52%   |
| AMD Ryzen 5          | 3         | 6.52%   |
| Intel Pentium Silver | 1         | 2.17%   |
| Intel Pentium        | 1         | 2.17%   |
| Intel Core i3        | 1         | 2.17%   |
| Intel Core 2 Duo     | 1         | 2.17%   |
| Intel Celeron        | 1         | 2.17%   |
| AMD Ryzen 9          | 1         | 2.17%   |
| AMD E1               | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 34.78%  |
| 4      | 12        | 26.09%  |
| 8      | 10        | 21.74%  |
| 14     | 3         | 6.52%   |
| 6      | 3         | 6.52%   |
| 10     | 2         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 86.96%  |
| 1      | 6         | 13.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 21.74%  |
| 0x306a9    | 5         | 10.87%  |
| 0x906a3    | 4         | 8.7%    |
| 0x806d1    | 4         | 8.7%    |
| 0x806c1    | 3         | 6.52%   |
| 0x406e3    | 2         | 4.35%   |
| 0x08600106 | 2         | 4.35%   |
| 0x08108109 | 2         | 4.35%   |
| 0xa0671    | 1         | 2.17%   |
| 0xa0652    | 1         | 2.17%   |
| 0x906ea    | 1         | 2.17%   |
| 0x906c0    | 1         | 2.17%   |
| 0x906a4    | 1         | 2.17%   |
| 0x806ec    | 1         | 2.17%   |
| 0x806ea    | 1         | 2.17%   |
| 0x406c4    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x20655    | 1         | 2.17%   |
| 0x08900201 | 1         | 2.17%   |
| 0x08608102 | 1         | 2.17%   |
| 0x07000106 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 15.22%  |
| IvyBridge        | 5         | 10.87%  |
| Icelake          | 5         | 10.87%  |
| Alderlake Hybrid | 5         | 10.87%  |
| Zen 2            | 3         | 6.52%   |
| Westmere         | 3         | 6.52%   |
| TigerLake        | 3         | 6.52%   |
| Skylake          | 3         | 6.52%   |
| Zen+             | 2         | 4.35%   |
| Unknown          | 2         | 4.35%   |
| Zen 3            | 1         | 2.17%   |
| Tremont          | 1         | 2.17%   |
| Silvermont       | 1         | 2.17%   |
| Jaguar           | 1         | 2.17%   |
| Haswell          | 1         | 2.17%   |
| Core             | 1         | 2.17%   |
| CometLake        | 1         | 2.17%   |
| Broadwell        | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 50%     |
| Nvidia | 18        | 30%     |
| AMD    | 12        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 6.56%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 4.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 4.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.92%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 4.92%   |
| AMD Renoir                                                                               | 3         | 4.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 3.28%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 3.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.28%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.64%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.64%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 1.64%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.64%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.64%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.64%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.64%   |
| Intel HD Graphics 630                                                                    | 1         | 1.64%   |
| Intel HD Graphics 620                                                                    | 1         | 1.64%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.64%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.64%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.64%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1         | 1.64%   |
| AMD Lucienne                                                                             | 1         | 1.64%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.64%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.64%   |
| AMD Barcelo                                                                              | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 39.13%  |
| Intel + Nvidia | 11        | 23.91%  |
| 1 x AMD        | 11        | 23.91%  |
| 1 x Nvidia     | 5         | 10.87%  |
| AMD + Nvidia   | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 84.78%  |
| Proprietary | 7         | 15.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 58.7%   |
| 0.01-0.5   | 5         | 10.87%  |
| 7.01-8.0   | 4         | 8.7%    |
| 0.51-1.0   | 4         | 8.7%    |
| 1.01-2.0   | 3         | 6.52%   |
| 5.01-6.0   | 2         | 4.35%   |
| 3.01-4.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 11        | 21.15%  |
| AU Optronics        | 9         | 17.31%  |
| LG Display          | 7         | 13.46%  |
| Chimei Innolux      | 7         | 13.46%  |
| Samsung Electronics | 4         | 7.69%   |
| Hewlett-Packard     | 3         | 5.77%   |
| Sharp               | 2         | 3.85%   |
| Lenovo              | 2         | 3.85%   |
| Goldstar            | 2         | 3.85%   |
| Valve               | 1         | 1.92%   |
| Sony                | 1         | 1.92%   |
| PANDA               | 1         | 1.92%   |
| HKC                 | 1         | 1.92%   |
| Dell                | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 3.85%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 3.85%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.92%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.92%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.92%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.92%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.92%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.92%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.92%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 1.92%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.92%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.92%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 1.92%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.92%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0A7D 1920x1200 345x215mm 16.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 1         | 1.92%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 26        | 52%     |
| 1366x768 (WXGA)   | 10        | 20%     |
| 3840x2160 (4K)    | 2         | 4%      |
| 2880x1620         | 2         | 4%      |
| 2560x1440 (QHD)   | 2         | 4%      |
| 1600x900 (HD+)    | 2         | 4%      |
| 1280x800 (WXGA)   | 2         | 4%      |
| 800x1280          | 1         | 2%      |
| 2256x1504         | 1         | 2%      |
| 1920x1200 (WUXGA) | 1         | 2%      |
| 1360x768          | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 32.69%  |
| 14     | 8         | 15.38%  |
| 13     | 8         | 15.38%  |
| 17     | 5         | 9.62%   |
| 31     | 3         | 5.77%   |
| 16     | 3         | 5.77%   |
| 72     | 1         | 1.92%   |
| 27     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |
| 23     | 1         | 1.92%   |
| 21     | 1         | 1.92%   |
| 12     | 1         | 1.92%   |
| 11     | 1         | 1.92%   |
| 7      | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 63.46%  |
| 351-400     | 7         | 13.46%  |
| 601-700     | 3         | 5.77%   |
| 201-300     | 3         | 5.77%   |
| 501-600     | 2         | 3.85%   |
| 401-500     | 2         | 3.85%   |
| 1501-2000   | 1         | 1.92%   |
| 1-100       | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 86.96%  |
| 16/10 | 4         | 8.7%    |
| 3/2   | 1         | 2.17%   |
| 0.67  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 36.54%  |
| 81-90          | 16        | 30.77%  |
| 121-130        | 5         | 9.62%   |
| 351-500        | 3         | 5.77%   |
| More than 1000 | 1         | 1.92%   |
| 61-70          | 1         | 1.92%   |
| 51-60          | 1         | 1.92%   |
| 1-40           | 1         | 1.92%   |
| 301-350        | 1         | 1.92%   |
| 251-300        | 1         | 1.92%   |
| 201-250        | 1         | 1.92%   |
| 151-200        | 1         | 1.92%   |
| 111-120        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 55.1%   |
| 101-120       | 11        | 22.45%  |
| 51-100        | 5         | 10.2%   |
| 161-240       | 4         | 8.16%   |
| More than 240 | 1         | 2.04%   |
| 1-50          | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 39        | 84.78%  |
| 2     | 7         | 15.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 43.66%  |
| Realtek Semiconductor | 25        | 35.21%  |
| MediaTek              | 3         | 4.23%   |
| Broadcom Limited      | 3         | 4.23%   |
| ASIX Electronics      | 3         | 4.23%   |
| Qualcomm Atheros      | 2         | 2.82%   |
| Sitecom Europe        | 1         | 1.41%   |
| Ralink Technology     | 1         | 1.41%   |
| Huawei Technologies   | 1         | 1.41%   |
| Hewlett-Packard       | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 19.32%  |
| Intel Wireless 8265 / 8275                                        | 4         | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.41%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.27%   |
| Intel Wireless 8260                                               | 2         | 2.27%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.27%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 2         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.27%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter          | 1         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.14%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.14%   |
| Realtek Realtek WLAN controller                                   | 1         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.14%   |
| Intel Wireless 7260                                               | 1         | 1.14%   |
| Intel Wireless 3165                                               | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.14%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 61.7%   |
| Realtek Semiconductor | 9         | 19.15%  |
| MediaTek              | 3         | 6.38%   |
| Broadcom Limited      | 3         | 6.38%   |
| Sitecom Europe        | 1         | 2.13%   |
| Ralink Technology     | 1         | 2.13%   |
| Qualcomm Atheros      | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 4         | 8.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 8.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 6.25%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 6.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 4.17%   |
| Intel Wireless 8260                                           | 2         | 4.17%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 4.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 4.17%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 4.17%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 2.08%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 2.08%   |
| Realtek Realtek WLAN controller                               | 1         | 2.08%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.08%   |
| Intel Wireless 7260                                           | 1         | 2.08%   |
| Intel Wireless 3165                                           | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 2.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.08%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.08%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 55.26%  |
| Intel                 | 12        | 31.58%  |
| ASIX Electronics      | 3         | 7.89%   |
| Qualcomm Atheros      | 1         | 2.63%   |
| Huawei Technologies   | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 43.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.69%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 5.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 5.13%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 5.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.56%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.56%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.56%   |
| Huawei E353/E3131                                                 | 1         | 2.56%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 54.12%  |
| Ethernet | 38        | 44.71%  |
| Modem    | 1         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 76.92%  |
| Ethernet | 12        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 71.74%  |
| 1     | 13        | 28.26%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 84.78%  |
| Yes  | 7         | 15.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 60.98%  |
| Realtek Semiconductor | 6         | 14.63%  |
| Broadcom              | 5         | 12.2%   |
| IMC Networks          | 4         | 9.76%   |
| Foxconn / Hon Hai     | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 9         | 21.95%  |
| Intel AX201 Bluetooth                            | 7         | 17.07%  |
| Intel AX210 Bluetooth                            | 4         | 9.76%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 7.32%   |
| Realtek Bluetooth Radio                          | 3         | 7.32%   |
| Intel AX200 Bluetooth                            | 3         | 7.32%   |
| IMC Networks Wireless_Device                     | 3         | 7.32%   |
| Intel Bluetooth Device                           | 1         | 2.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 2.44%   |
| IMC Networks Bluetooth Radio                     | 1         | 2.44%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 2.44%   |
| Broadcom HP Portable SoftSailing                 | 1         | 2.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 2.44%   |
| Broadcom BCM20702A0                              | 1         | 2.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 2.44%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 55.22%  |
| Nvidia              | 16        | 23.88%  |
| AMD                 | 12        | 17.91%  |
| C-Media Electronics | 1         | 1.49%   |
| ASUSTek Computer    | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 9.21%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 6.58%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 6.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.58%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 5.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 5.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.95%   |
| Nvidia Audio device                                                                               | 3         | 3.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.63%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 2.63%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.32%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.32%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.32%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.32%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.32%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.32%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.32%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 28.89%  |
| SK hynix            | 10        | 22.22%  |
| Kingston            | 7         | 15.56%  |
| Micron Technology   | 5         | 11.11%  |
| Crucial             | 3         | 6.67%   |
| Corsair             | 2         | 4.44%   |
| Neo Forza           | 1         | 2.22%   |
| Nanya Technology    | 1         | 2.22%   |
| Innodisk            | 1         | 2.22%   |
| Essencore Limited   | 1         | 2.22%   |
| A-DATA Technology   | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s     | 2         | 4.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 4.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                | 2         | 4.17%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s              | 2         | 4.17%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 2         | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 2.08%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 2.08%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s            | 1         | 2.08%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 2.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.08%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s               | 1         | 2.08%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s                 | 1         | 2.08%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                | 1         | 2.08%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 2.08%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 2.08%   |
| Samsung RAM K3LK7K70BM-BGCP000 4GB SODIMM LPDDR5 4266MT/s            | 1         | 2.08%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 2.08%   |
| Nanya RAM NT4GC64C88B1NS-DI 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.08%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s         | 1         | 2.08%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.08%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.08%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s        | 1         | 2.08%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 2.08%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.08%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.08%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s                | 1         | 2.08%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 2.08%   |
| Kingston RAM 9905712-007.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.08%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 2.08%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.08%   |
| Innodisk RAM M4S08S681QMMM52-12 8GB SODIMM DDR4 3200MT/s             | 1         | 2.08%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 2.08%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 53.85%  |
| DDR3   | 10        | 25.64%  |
| LPDDR5 | 3         | 7.69%   |
| LPDDR3 | 2         | 5.13%   |
| DDR5   | 2         | 5.13%   |
| LPDDR4 | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 85%     |
| Row Of Chips | 5         | 12.5%   |
| Chip         | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 50%     |
| 4096  | 14        | 31.82%  |
| 16384 | 6         | 13.64%  |
| 32768 | 1         | 2.27%   |
| 2048  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 33.33%  |
| 1600  | 9         | 21.43%  |
| 2667  | 5         | 11.9%   |
| 6400  | 2         | 4.76%   |
| 4800  | 2         | 4.76%   |
| 2400  | 2         | 4.76%   |
| 1867  | 2         | 4.76%   |
| 4267  | 1         | 2.38%   |
| 4266  | 1         | 2.38%   |
| 2133  | 1         | 2.38%   |
| 1334  | 1         | 2.38%   |
| 1333  | 1         | 2.38%   |
| 701   | 1         | 2.38%   |

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
| Chicony Electronics                    | 13        | 29.55%  |
| Bison Electronics                      | 5         | 11.36%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Microdia                               | 4         | 9.09%   |
| Syntek                                 | 3         | 6.82%   |
| Sonix Technology                       | 3         | 6.82%   |
| Luxvisions Innotech Limited            | 3         | 6.82%   |
| Quanta                                 | 2         | 4.55%   |
| Acer                                   | 2         | 4.55%   |
| Sunplus Innovation Technology          | 1         | 2.27%   |
| Samsung Electronics                    | 1         | 2.27%   |
| Logitech                               | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 3         | 6.82%   |
| Bison HD Webcam                                                | 3         | 6.82%   |
| Syntek Integrated Camera                                       | 2         | 4.55%   |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 4.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 4.55%   |
| Chicony HD User Facing                                         | 2         | 4.55%   |
| Acer BisonCam,NB Pro                                           | 2         | 4.55%   |
| Syntek USB2.0 Camera                                           | 1         | 2.27%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2.27%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 2.27%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2.27%   |
| Realtek Laptop Camera                                          | 1         | 2.27%   |
| Realtek Integrated Camera                                      | 1         | 2.27%   |
| Realtek EasyCamera                                             | 1         | 2.27%   |
| Realtek Bluetooth Radio                                        | 1         | 2.27%   |
| Quanta HP Wide Vision HD Camera                                | 1         | 2.27%   |
| Quanta HP Webcam                                               | 1         | 2.27%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.27%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 2.27%   |
| Microdia Integrated Webcam                                     | 1         | 2.27%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.27%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2.27%   |
| Logitech HD Pro Webcam C920                                    | 1         | 2.27%   |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2.27%   |
| Chicony Web Camera - FHD                                       | 1         | 2.27%   |
| Chicony USB 2.0 Camera                                         | 1         | 2.27%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2.27%   |
| Chicony HP TrueVision HD Camera                                | 1         | 2.27%   |
| Chicony HP True Vision 5MP Camera                              | 1         | 2.27%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.27%   |
| Chicony HP HD Camera                                           | 1         | 2.27%   |
| Chicony FJ Camera                                              | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.27%   |
| Bison ThinkPad Integrated Camera                               | 1         | 2.27%   |
| Bison Integrated Camera                                        | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 6         | 42.86%  |
| Synaptics                          | 3         | 21.43%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 14.29%  |
| STMicroelectronics                 | 1         | 7.14%   |
| Shenzhen Goodix Technology         | 1         | 7.14%   |
| Elan Microelectronics              | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 3         | 21.43%  |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 1         | 7.14%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 7.14%   |
| Synaptics WBDI Device                                           | 1         | 7.14%   |
| Synaptics UWP WBDI                                              | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                                | 1         | 7.14%   |
| Unknown                                                         | 1         | 7.14%   |

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
| 0     | 27        | 57.45%  |
| 1     | 15        | 31.91%  |
| 2     | 4         | 8.51%   |
| 3     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 51.85%  |
| Graphics card         | 4         | 14.81%  |
| Multimedia controller | 3         | 11.11%  |
| Net/wireless          | 2         | 7.41%   |
| Chipcard              | 2         | 7.41%   |
| Camera                | 1         | 3.7%    |
| Bluetooth             | 1         | 3.7%    |

