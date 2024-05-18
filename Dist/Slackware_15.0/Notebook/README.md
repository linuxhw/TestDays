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

Total: 71

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad T430s 2355CL4      | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Lenovo    | ThinkPad T16 Gen 2 21K7C... | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| Dell      | Precision 7510              | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| Lenovo    | ThinkPad T430s 2355CL4      | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| MSI       | Modern 14 B5M               | [585c473256](https://linux-hardware.org/?probe=585c473256) | Mar 08, 2024 |
| Dell      | XPS 13 9370                 | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Notebook  | NL5xNU                      | [e83f0b4085](https://linux-hardware.org/?probe=e83f0b4085) | Feb 18, 2024 |
| Dell      | XPS 13 9370                 | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| HP        | Laptop 14s-fq0xxx           | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| Acer      | Aspire SW5-012              | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| Lenovo    | V330-14ARR 81B1             | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Toshiba   | Satellite C660              | [483998d7de](https://linux-hardware.org/?probe=483998d7de) | Oct 20, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [aafdab7043](https://linux-hardware.org/?probe=aafdab7043) | Oct 13, 2023 |
| HP        | OMEN by Laptop 16-b1xxx     | [a1a64b6621](https://linux-hardware.org/?probe=a1a64b6621) | Oct 05, 2023 |
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


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.15.19                     | 12        | 20.69%  |
| 5.15.145                    | 4         | 6.9%    |
| 5.15.117                    | 4         | 6.9%    |
| 5.19.17                     | 3         | 5.17%   |
| 6.1.44                      | 2         | 3.45%   |
| 5.17.1                      | 2         | 3.45%   |
| 5.15.80                     | 2         | 3.45%   |
| 5.15.38                     | 2         | 3.45%   |
| 5.13.8                      | 2         | 3.45%   |
| 6.7.5-gsh-clevo-NL51NU-SW15 | 1         | 1.72%   |
| 6.6.8                       | 1         | 1.72%   |
| 6.6.28                      | 1         | 1.72%   |
| 6.5.5                       | 1         | 1.72%   |
| 6.1.51                      | 1         | 1.72%   |
| 6.1.12                      | 1         | 1.72%   |
| 6.1.1                       | 1         | 1.72%   |
| 5.17.5                      | 1         | 1.72%   |
| 5.17.2                      | 1         | 1.72%   |
| 5.16.9-joe1                 | 1         | 1.72%   |
| 5.16.12                     | 1         | 1.72%   |
| 5.15.78.a                   | 1         | 1.72%   |
| 5.15.63                     | 1         | 1.72%   |
| 5.15.37.a                   | 1         | 1.72%   |
| 5.15.33.kjh                 | 1         | 1.72%   |
| 5.15.27                     | 1         | 1.72%   |
| 5.15.118                    | 1         | 1.72%   |
| 5.15.1                      | 1         | 1.72%   |
| 5.14.9                      | 1         | 1.72%   |
| 5.14.8                      | 1         | 1.72%   |
| 5.14.10                     | 1         | 1.72%   |
| 5.14.0                      | 1         | 1.72%   |
| 5.13.5                      | 1         | 1.72%   |
| 5.13.11                     | 1         | 1.72%   |
| 5.10.91                     | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.19  | 12        | 20.69%  |
| 5.15.145 | 4         | 6.9%    |
| 5.15.117 | 4         | 6.9%    |
| 5.19.17  | 3         | 5.17%   |
| 6.1.44   | 2         | 3.45%   |
| 5.17.1   | 2         | 3.45%   |
| 5.15.80  | 2         | 3.45%   |
| 5.15.38  | 2         | 3.45%   |
| 5.13.8   | 2         | 3.45%   |
| 6.7.5    | 1         | 1.72%   |
| 6.6.8    | 1         | 1.72%   |
| 6.6.28   | 1         | 1.72%   |
| 6.5.5    | 1         | 1.72%   |
| 6.1.51   | 1         | 1.72%   |
| 6.1.12   | 1         | 1.72%   |
| 6.1.1    | 1         | 1.72%   |
| 5.17.5   | 1         | 1.72%   |
| 5.17.2   | 1         | 1.72%   |
| 5.16.9   | 1         | 1.72%   |
| 5.16.12  | 1         | 1.72%   |
| 5.15.78  | 1         | 1.72%   |
| 5.15.63  | 1         | 1.72%   |
| 5.15.37  | 1         | 1.72%   |
| 5.15.33  | 1         | 1.72%   |
| 5.15.27  | 1         | 1.72%   |
| 5.15.118 | 1         | 1.72%   |
| 5.15.1   | 1         | 1.72%   |
| 5.14.9   | 1         | 1.72%   |
| 5.14.8   | 1         | 1.72%   |
| 5.14.10  | 1         | 1.72%   |
| 5.14.0   | 1         | 1.72%   |
| 5.13.5   | 1         | 1.72%   |
| 5.13.11  | 1         | 1.72%   |
| 5.10.91  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 54.39%  |
| 6.1     | 5         | 8.77%   |
| 5.17    | 4         | 7.02%   |
| 5.13    | 4         | 7.02%   |
| 5.19    | 3         | 5.26%   |
| 5.14    | 3         | 5.26%   |
| 6.6     | 2         | 3.51%   |
| 5.16    | 2         | 3.51%   |
| 6.7     | 1         | 1.75%   |
| 6.5     | 1         | 1.75%   |
| 5.10    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 27        | 48.21%  |
| XFCE      | 16        | 28.57%  |
| Unknown   | 6         | 10.71%  |
| MATE      | 2         | 3.57%   |
| xwmconfig | 1         | 1.79%   |
| KDE       | 1         | 1.79%   |
| GNOME     | 1         | 1.79%   |
| awesome   | 1         | 1.79%   |
| 2bwm      | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 31        | 53.45%  |
| Tty     | 24        | 41.38%  |
| Wayland | 3         | 5.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 31        | 53.45%  |
| Unknown | 13        | 22.41%  |
| XDM     | 12        | 20.69%  |
| LightDM | 1         | 1.72%   |
| GDM     | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 41        | 74.55%  |
| de_DE | 3         | 5.45%   |
| pt_BR | 2         | 3.64%   |
| it_IT | 2         | 3.64%   |
| fr_FR | 2         | 3.64%   |
| cs_CZ | 2         | 3.64%   |
| zh_TW | 1         | 1.82%   |
| ru_RU | 1         | 1.82%   |
| en_SE | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 35        | 62.5%   |
| BIOS | 21        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 84.21%  |
| Btrfs   | 4         | 7.02%   |
| Overlay | 3         | 5.26%   |
| Xfs     | 1         | 1.75%   |
| Jfs     | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 36        | 64.29%  |
| MBR     | 10        | 17.86%  |
| Unknown | 10        | 17.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 82.14%  |
| Yes       | 10        | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 62.5%   |
| Yes       | 21        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 27.27%  |
| Hewlett-Packard  | 11        | 20%     |
| Dell             | 7         | 12.73%  |
| MSI              | 5         | 9.09%   |
| ASUSTek Computer | 4         | 7.27%   |
| Notebook         | 3         | 5.45%   |
| Acer             | 3         | 5.45%   |
| Valve            | 1         | 1.82%   |
| Toshiba          | 1         | 1.82%   |
| System76         | 1         | 1.82%   |
| Sony             | 1         | 1.82%   |
| Fujitsu          | 1         | 1.82%   |
| Framework        | 1         | 1.82%   |
| Dynabook         | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop K6500ZE_K6500ZE | 2         | 3.64%   |
| Valve Jupiter                            | 1         | 1.82%   |
| Toshiba Satellite C660                   | 1         | 1.82%   |
| System76 Oryx Pro                        | 1         | 1.82%   |
| Sony SVE1713A1EW                         | 1         | 1.82%   |
| Notebook X170KM-G                        | 1         | 1.82%   |
| Notebook P7xxTM                          | 1         | 1.82%   |
| Notebook NL5xNU                          | 1         | 1.82%   |
| MSI Modern 14 B5M                        | 1         | 1.82%   |
| MSI Modern 14 B11MO                      | 1         | 1.82%   |
| MSI Modern 14 B10MW                      | 1         | 1.82%   |
| MSI GP76 Leopard 11UG                    | 1         | 1.82%   |
| MSI GE76 Raider 11UE                     | 1         | 1.82%   |
| Lenovo V330-14ARR 81B1                   | 1         | 1.82%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 1.82%   |
| Lenovo ThinkPad X140e 20BMS03E00         | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2FT00 | 1         | 1.82%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.82%   |
| Lenovo ThinkPad T470p 20J60018MS         | 1         | 1.82%   |
| Lenovo ThinkPad T470 20JNS01R01          | 1         | 1.82%   |
| Lenovo ThinkPad T430s 2355CL4            | 1         | 1.82%   |
| Lenovo ThinkPad T410 2518C3U             | 1         | 1.82%   |
| Lenovo ThinkPad T16 Gen 2 21K7CTO1WW     | 1         | 1.82%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 1.82%   |
| Lenovo ThinkPad E16 Gen 1 21JT000PJP     | 1         | 1.82%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.82%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 1.82%   |
| HP ProBook 6570b                         | 1         | 1.82%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 1.82%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 1.82%   |
| HP OMEN by Laptop 17-ck0xxx              | 1         | 1.82%   |
| HP OMEN by Laptop 16-b1xxx               | 1         | 1.82%   |
| HP Laptop 15-bs1xx                       | 1         | 1.82%   |
| HP Laptop 14s-fq0xxx                     | 1         | 1.82%   |
| HP ENVY Laptop 17-cr0xxx                 | 1         | 1.82%   |
| HP EliteBook 8440p                       | 1         | 1.82%   |
| HP EliteBook 840 G5                      | 1         | 1.82%   |
| HP 245 G7 Notebook PC                    | 1         | 1.82%   |
| Fujitsu LIFEBOOK A544                    | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 21.82%  |
| MSI Modern          | 3         | 5.45%   |
| Lenovo IdeaPad      | 2         | 3.64%   |
| HP Pavilion         | 2         | 3.64%   |
| HP OMEN             | 2         | 3.64%   |
| HP Laptop           | 2         | 3.64%   |
| HP EliteBook        | 2         | 3.64%   |
| Dell Vostro         | 2         | 3.64%   |
| Dell Precision      | 2         | 3.64%   |
| ASUS VivoBook       | 2         | 3.64%   |
| Valve Jupiter       | 1         | 1.82%   |
| Toshiba Satellite   | 1         | 1.82%   |
| System76 Oryx       | 1         | 1.82%   |
| Sony SVE1713A1EW    | 1         | 1.82%   |
| Notebook X170KM-G   | 1         | 1.82%   |
| Notebook P7xxTM     | 1         | 1.82%   |
| Notebook NL5xNU     | 1         | 1.82%   |
| MSI GP76            | 1         | 1.82%   |
| MSI GE76            | 1         | 1.82%   |
| Lenovo V330-14ARR   | 1         | 1.82%   |
| HP ProBook          | 1         | 1.82%   |
| HP ENVY             | 1         | 1.82%   |
| HP 245              | 1         | 1.82%   |
| Fujitsu LIFEBOOK    | 1         | 1.82%   |
| Framework Laptop    | 1         | 1.82%   |
| Dynabook P1-C7MP-BL | 1         | 1.82%   |
| Dell XPS            | 1         | 1.82%   |
| Dell Latitude       | 1         | 1.82%   |
| Dell Inspiron       | 1         | 1.82%   |
| ASUS ROG            | 1         | 1.82%   |
| ASUS ASUS           | 1         | 1.82%   |
| Acer Swift          | 1         | 1.82%   |
| Acer Nitro          | 1         | 1.82%   |
| Acer Aspire         | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 10        | 18.18%  |
| 2021 | 9         | 16.36%  |
| 2022 | 6         | 10.91%  |
| 2012 | 5         | 9.09%   |
| 2017 | 4         | 7.27%   |
| 2019 | 3         | 5.45%   |
| 2018 | 3         | 5.45%   |
| 2010 | 3         | 5.45%   |
| 2023 | 2         | 3.64%   |
| 2016 | 2         | 3.64%   |
| 2015 | 2         | 3.64%   |
| 2014 | 2         | 3.64%   |
| 2013 | 1         | 1.82%   |
| 2009 | 1         | 1.82%   |
| 2008 | 1         | 1.82%   |
| 2007 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 55        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 96.36%  |
| Yes  | 2         | 3.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 15        | 26.79%  |
| 4.01-8.0    | 11        | 19.64%  |
| 16.01-24.0  | 10        | 17.86%  |
| 3.01-4.0    | 8         | 14.29%  |
| 32.01-64.0  | 4         | 7.14%   |
| 64.01-256.0 | 4         | 7.14%   |
| 24.01-32.0  | 3         | 5.36%   |
| 1.01-2.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 19        | 31.15%  |
| 1.01-2.0   | 16        | 26.23%  |
| 4.01-8.0   | 13        | 21.31%  |
| 0.51-1.0   | 5         | 8.2%    |
| 3.01-4.0   | 4         | 6.56%   |
| 16.01-24.0 | 2         | 3.28%   |
| 0.01-0.5   | 2         | 3.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 67.86%  |
| 2      | 15        | 26.79%  |
| 4      | 2         | 3.57%   |
| 3      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 81.82%  |
| Yes       | 10        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 83.93%  |
| No        | 9         | 16.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 98.18%  |
| No        | 1         | 1.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 87.27%  |
| No        | 7         | 12.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 21.82%  |
| Japan        | 4         | 7.27%   |
| Portugal     | 3         | 5.45%   |
| Kazakhstan   | 3         | 5.45%   |
| Italy        | 3         | 5.45%   |
| Germany      | 3         | 5.45%   |
| France       | 3         | 5.45%   |
| Spain        | 2         | 3.64%   |
| South Africa | 2         | 3.64%   |
| Romania      | 2         | 3.64%   |
| India        | 2         | 3.64%   |
| Czechia      | 2         | 3.64%   |
| Brazil       | 2         | 3.64%   |
| UK           | 1         | 1.82%   |
| Taiwan       | 1         | 1.82%   |
| Sweden       | 1         | 1.82%   |
| Serbia       | 1         | 1.82%   |
| Russia       | 1         | 1.82%   |
| Mexico       | 1         | 1.82%   |
| Iran         | 1         | 1.82%   |
| Greece       | 1         | 1.82%   |
| China        | 1         | 1.82%   |
| Chile        | 1         | 1.82%   |
| Canada       | 1         | 1.82%   |
| Argentina    | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tsukuba            | 3         | 5.36%   |
| Ust-Kamenogorsk    | 2         | 3.57%   |
| Sun Prairie        | 2         | 3.57%   |
| Lisbon             | 2         | 3.57%   |
| Greater Noida      | 2         | 3.57%   |
| Frignano           | 2         | 3.57%   |
| Bucharest          | 2         | 3.57%   |
| Worpswede          | 1         | 1.79%   |
| Villa Carlos Paz   | 1         | 1.79%   |
| Tehran             | 1         | 1.79%   |
| Taichung           | 1         | 1.79%   |
| Skövde            | 1         | 1.79%   |
| Sao Paulo          | 1         | 1.79%   |
| Santiago           | 1         | 1.79%   |
| Santander          | 1         | 1.79%   |
| Round Rock         | 1         | 1.79%   |
| Roudnice nad Labem | 1         | 1.79%   |
| Reno               | 1         | 1.79%   |
| Renazzo            | 1         | 1.79%   |
| Punxsutawney       | 1         | 1.79%   |
| Plainwell          | 1         | 1.79%   |
| Ōtsu              | 1         | 1.79%   |
| Oberstreit         | 1         | 1.79%   |
| Novy Jicin         | 1         | 1.79%   |
| Moscow             | 1         | 1.79%   |
| Montreal           | 1         | 1.79%   |
| Mexico City        | 1         | 1.79%   |
| Meuselwitz         | 1         | 1.79%   |
| McKinney           | 1         | 1.79%   |
| Luxeuil-les-Bains  | 1         | 1.79%   |
| League City        | 1         | 1.79%   |
| Kent               | 1         | 1.79%   |
| Karaganda          | 1         | 1.79%   |
| Johannesburg       | 1         | 1.79%   |
| Hayward            | 1         | 1.79%   |
| Harringay          | 1         | 1.79%   |
| Guimaraes          | 1         | 1.79%   |
| Guangzhou          | 1         | 1.79%   |
| Fortaleza          | 1         | 1.79%   |
| Fayetteville       | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 15        | 21     | 20.83%  |
| WDC                         | 8         | 9      | 11.11%  |
| Kingston                    | 6         | 6      | 8.33%   |
| SanDisk                     | 5         | 7      | 6.94%   |
| Intel                       | 5         | 6      | 6.94%   |
| Seagate                     | 4         | 4      | 5.56%   |
| Toshiba                     | 3         | 3      | 4.17%   |
| SK hynix                    | 3         | 3      | 4.17%   |
| Micron Technology           | 3         | 3      | 4.17%   |
| HGST                        | 3         | 3      | 4.17%   |
| Unknown                     | 2         | 4      | 2.78%   |
| Micron/Crucial Technology   | 2         | 2      | 2.78%   |
| Crucial                     | 2         | 2      | 2.78%   |
| Verbatim                    | 1         | 2      | 1.39%   |
| Transcend                   | 1         | 1      | 1.39%   |
| Silicon Motion              | 1         | 1      | 1.39%   |
| Plextor                     | 1         | 1      | 1.39%   |
| LITEON                      | 1         | 1      | 1.39%   |
| KIOXIA                      | 1         | 1      | 1.39%   |
| Kingston Technology Company | 1         | 1      | 1.39%   |
| JMicron Technology          | 1         | 1      | 1.39%   |
| Hewlett-Packard             | 1         | 2      | 1.39%   |
| Gigabyte Technology         | 1         | 1      | 1.39%   |
| External                    | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 4         | 5%      |
| Intel SSD 660P Series 1024GB                          | 3         | 3.75%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 2.5%    |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 2.5%    |
| HGST HTS725050A7E630 500GB                            | 2         | 2.5%    |
| WDC WDS100T2B0B-00YS70 1TB SSD                        | 1         | 1.25%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 1         | 1.25%   |
| WDC WD5000BEKT-60KA9T0 500GB                          | 1         | 1.25%   |
| WDC WD10JPVT-08A1YT2 1TB                              | 1         | 1.25%   |
| WDC WD Green 2.5 240GB                                | 1         | 1.25%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB                    | 1         | 1.25%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 1.25%   |
| Verbatim Vi550 S3 SSD 256GB                           | 1         | 1.25%   |
| Unknown MMC Card  64GB                                | 1         | 1.25%   |
| Unknown MMC Card  512GB                               | 1         | 1.25%   |
| Unknown MMC Card  32GB                                | 1         | 1.25%   |
| Transcend TS256GMTE352T-VLV 256GB                     | 1         | 1.25%   |
| Toshiba MQ04ABF100 1TB                                | 1         | 1.25%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 1.25%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 1.25%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 1.25%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB               | 1         | 1.25%   |
| SK hynix BC511 256GB                                  | 1         | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1         | 1.25%   |
| Seagate ST2000LX001-1RG174 2TB                        | 1         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 1         | 1.25%   |
| Sandisk WDC PC SN540 SDDPNPF-512G-1032 512GB          | 1         | 1.25%   |
| Sandisk WD PC SN740 SDDQNQD-1T00-1201 1TB             | 1         | 1.25%   |
| Sandisk WD Black SN850 512GB                          | 1         | 1.25%   |
| SanDisk Ultra II 960GB SSD                            | 1         | 1.25%   |
| SanDisk SDSSDA240G 240GB                              | 1         | 1.25%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.25%   |
| Samsung SSD PM830 2.5 7mm 128GB                       | 1         | 1.25%   |
| Samsung SSD 980 PRO 500GB                             | 1         | 1.25%   |
| Samsung SSD 980 PRO 2TB                               | 1         | 1.25%   |
| Samsung SSD 980 PRO 1TB                               | 1         | 1.25%   |
| Samsung SSD 970 EVO Plus 500GB                        | 1         | 1.25%   |
| Samsung SSD 970 EVO Plus 2TB                          | 1         | 1.25%   |
| Samsung SSD 970 EVO 2TB                               | 1         | 1.25%   |
| Samsung SSD 870 EVO 1TB                               | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 4         | 4      | 26.67%  |
| Seagate            | 4         | 4      | 26.67%  |
| Toshiba            | 3         | 3      | 20%     |
| HGST               | 3         | 3      | 20%     |
| JMicron Technology | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 28.57%  |
| Samsung Electronics | 4         | 6      | 19.05%  |
| WDC                 | 2         | 3      | 9.52%   |
| SanDisk             | 2         | 2      | 9.52%   |
| Verbatim            | 1         | 2      | 4.76%   |
| Plextor             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Gigabyte Technology | 1         | 1      | 4.76%   |
| External            | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 42     | 47.14%  |
| SSD  | 21        | 25     | 30%     |
| HDD  | 14        | 15     | 20%     |
| MMC  | 2         | 4      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 42     | 50%     |
| SATA | 27        | 36     | 40.91%  |
| SAS  | 4         | 4      | 6.06%   |
| MMC  | 2         | 4      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 68.57%  |
| 0.51-1.0   | 10        | 11     | 28.57%  |
| 1.01-2.0   | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 18        | 31.58%  |
| 101-250        | 15        | 26.32%  |
| 251-500        | 9         | 15.79%  |
| 1001-2000      | 7         | 12.28%  |
| 21-50          | 2         | 3.51%   |
| 1-20           | 2         | 3.51%   |
| 51-100         | 2         | 3.51%   |
| More than 3000 | 1         | 1.75%   |
| 2001-3000      | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 15        | 25.42%  |
| 251-500   | 13        | 22.03%  |
| 1-20      | 10        | 16.95%  |
| 21-50     | 9         | 15.25%  |
| 51-100    | 5         | 8.47%   |
| 501-1000  | 4         | 6.78%   |
| 1001-2000 | 3         | 5.08%   |

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
| Works    | 44        | 59     | 70.97%  |
| Detected | 14        | 23     | 22.58%  |
| Malfunc  | 4         | 4      | 6.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 46.97%  |
| Samsung Electronics         | 11        | 16.67%  |
| AMD                         | 7         | 10.61%  |
| SanDisk                     | 5         | 7.58%   |
| SK hynix                    | 3         | 4.55%   |
| Micron/Crucial Technology   | 3         | 4.55%   |
| Micron Technology           | 2         | 3.03%   |
| Silicon Motion              | 1         | 1.52%   |
| KIOXIA                      | 1         | 1.52%   |
| Kingston Technology Company | 1         | 1.52%   |
| Biwin Storage Technology    | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 8.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 7.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 7.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 7.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 4.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 4.23%   |
| Intel SSD 660P Series                                                            | 3         | 4.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 4.23%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 2.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 2.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 1.41%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.41%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                      | 1         | 1.41%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.41%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 1.41%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.41%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 1.41%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 1.41%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 1         | 1.41%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.41%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.41%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.41%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 1         | 1.41%   |
| Intel SSD 600P Series                                                            | 1         | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 1.41%   |
| Biwin Storage EX950 NVMe SSD                                                     | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 33        | 47.83%  |
| SATA | 27        | 39.13%  |
| RAID | 8         | 11.59%  |
| IDE  | 1         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 76.36%  |
| AMD    | 13        | 23.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 7.27%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 5.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 3.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 3.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.64%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.82%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.82%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.82%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.82%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.82%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.82%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.82%   |
| Intel Core i5-4310M CPU @ 2.70GHz             | 1         | 1.82%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.82%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.82%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.82%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.82%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.82%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.82%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.82%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 1.82%   |
| Intel 12th Gen Core i7-12650H                 | 1         | 1.82%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 1.82%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 1.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.82%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 1.82%   |
| AMD Ryzen 7 PRO 7840U w/ Radeon 780M Graphics | 1         | 1.82%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 1         | 1.82%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 1         | 1.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 14        | 25.45%  |
| Intel Core i7        | 11        | 20%     |
| Intel Core i5        | 11        | 20%     |
| AMD Ryzen 5          | 5         | 9.09%   |
| AMD Ryzen 7          | 4         | 7.27%   |
| Intel Core i3        | 2         | 3.64%   |
| Intel Pentium Silver | 1         | 1.82%   |
| Intel Pentium        | 1         | 1.82%   |
| Intel Core 2 Duo     | 1         | 1.82%   |
| Intel Celeron        | 1         | 1.82%   |
| Intel Atom           | 1         | 1.82%   |
| AMD Ryzen 9          | 1         | 1.82%   |
| AMD Ryzen 7 PRO      | 1         | 1.82%   |
| AMD E1               | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 32.73%  |
| 4      | 16        | 29.09%  |
| 8      | 12        | 21.82%  |
| 6      | 4         | 7.27%   |
| 14     | 3         | 5.45%   |
| 10     | 2         | 3.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 48        | 87.27%  |
| 1      | 7         | 12.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 29.82%  |
| 0x306a9    | 5         | 8.77%   |
| 0x906a3    | 4         | 7.02%   |
| 0x806d1    | 4         | 7.02%   |
| 0x806c1    | 3         | 5.26%   |
| 0x806ea    | 2         | 3.51%   |
| 0x406e3    | 2         | 3.51%   |
| 0x20655    | 2         | 3.51%   |
| 0x08600106 | 2         | 3.51%   |
| 0x08108109 | 2         | 3.51%   |
| 0xa0671    | 1         | 1.75%   |
| 0xa0652    | 1         | 1.75%   |
| 0x906ea    | 1         | 1.75%   |
| 0x906c0    | 1         | 1.75%   |
| 0x906a4    | 1         | 1.75%   |
| 0x806ec    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x306c3    | 1         | 1.75%   |
| 0x30678    | 1         | 1.75%   |
| 0x08900201 | 1         | 1.75%   |
| 0x08608103 | 1         | 1.75%   |
| 0x08608102 | 1         | 1.75%   |
| 0x07000106 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 8         | 14.29%  |
| IvyBridge        | 6         | 10.71%  |
| Icelake          | 5         | 8.93%   |
| Alderlake Hybrid | 5         | 8.93%   |
| Unknown          | 5         | 8.93%   |
| Westmere         | 4         | 7.14%   |
| Skylake          | 4         | 7.14%   |
| Zen 2            | 3         | 5.36%   |
| TigerLake        | 3         | 5.36%   |
| Zen+             | 2         | 3.57%   |
| Zen 3            | 2         | 3.57%   |
| Silvermont       | 2         | 3.57%   |
| Zen              | 1         | 1.79%   |
| Tremont          | 1         | 1.79%   |
| Jaguar           | 1         | 1.79%   |
| Haswell          | 1         | 1.79%   |
| Core             | 1         | 1.79%   |
| CometLake        | 1         | 1.79%   |
| Broadwell        | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 47.83%  |
| Nvidia | 19        | 27.54%  |
| AMD    | 17        | 24.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 5.71%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 4.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 4.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.29%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 4.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.29%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 4.29%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 2.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.86%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.86%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.86%   |
| AMD Lucienne                                                                             | 2         | 2.86%   |
| AMD Barcelo                                                                              | 2         | 2.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.43%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 1.43%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                         | 1         | 1.43%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.43%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.43%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.43%   |
| Nvidia GA107M [GeForce RTX 2050]                                                         | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.43%   |
| Intel HD Graphics 630                                                                    | 1         | 1.43%   |
| Intel HD Graphics 620                                                                    | 1         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.43%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.43%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.43%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1         | 1.43%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 38.18%  |
| 1 x AMD        | 16        | 29.09%  |
| Intel + Nvidia | 11        | 20%     |
| 1 x Nvidia     | 6         | 10.91%  |
| AMD + Nvidia   | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 47        | 83.93%  |
| Proprietary | 9         | 16.07%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 59.65%  |
| 0.01-0.5   | 7         | 12.28%  |
| 0.51-1.0   | 5         | 8.77%   |
| 7.01-8.0   | 4         | 7.02%   |
| 1.01-2.0   | 3         | 5.26%   |
| 5.01-6.0   | 2         | 3.51%   |
| 3.01-4.0   | 2         | 3.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 14        | 21.88%  |
| AU Optronics        | 10        | 15.63%  |
| LG Display          | 8         | 12.5%   |
| Chimei Innolux      | 7         | 10.94%  |
| Samsung Electronics | 5         | 7.81%   |
| Hewlett-Packard     | 4         | 6.25%   |
| Sharp               | 3         | 4.69%   |
| Lenovo              | 2         | 3.13%   |
| Goldstar            | 2         | 3.13%   |
| Dell                | 2         | 3.13%   |
| Valve               | 1         | 1.56%   |
| Sony                | 1         | 1.56%   |
| PANDA               | 1         | 1.56%   |
| Hyundai ImageQuest  | 1         | 1.56%   |
| HKC                 | 1         | 1.56%   |
| BenQ                | 1         | 1.56%   |
| AOC                 | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 2         | 3.13%   |
| Goldstar ULTRAGEAR GSM7765 2560x1440 697x392mm 31.5-inch              | 2         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 2         | 3.13%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 1.56%   |
| Sony TV SNY8102 1360x768                                              | 1         | 1.56%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch               | 1         | 1.56%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.56%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 1.56%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.56%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.56%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD04B9 1920x1080 340x190mm 15.3-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 1         | 1.56%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 1.56%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 1         | 1.56%   |
| Hyundai ImageQuest B70A HIQ5004 1280x1024 330x270mm 16.8-inch         | 1         | 1.56%   |
| HKC LCD Monitor HKC36B1 1366x768 309x174mm 14.0-inch                  | 1         | 1.56%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch            | 1         | 1.56%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 1.56%   |
| Hewlett-Packard 22vc HWP330E 1920x1080 480x270mm 21.7-inch            | 1         | 1.56%   |
| Hewlett-Packard 22f HPN3541 1920x1080 476x268mm 21.5-inch             | 1         | 1.56%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 1.56%   |
| Dell S2721H DEL41F5 1920x1080 598x336mm 27.0-inch                     | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1774 1920x1080 381x214mm 17.2-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 1.56%   |
| BOE LCD Monitor BOE0B80 1920x1200 345x215mm 16.0-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE0A7D 1920x1200 345x215mm 16.0-inch                 | 1         | 1.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 51.67%  |
| 1366x768 (WXGA)    | 10        | 16.67%  |
| 3840x2160 (4K)     | 3         | 5%      |
| 1600x900 (HD+)     | 3         | 5%      |
| 2880x1620          | 2         | 3.33%   |
| 2560x1440 (QHD)    | 2         | 3.33%   |
| 1920x1200 (WUXGA)  | 2         | 3.33%   |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 800x1280           | 1         | 1.67%   |
| 2256x1504          | 1         | 1.67%   |
| 1680x1050 (WSXGA+) | 1         | 1.67%   |
| 1360x768           | 1         | 1.67%   |
| 1280x1024 (SXGA)   | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 32.81%  |
| 14     | 9         | 14.06%  |
| 13     | 9         | 14.06%  |
| 17     | 6         | 9.38%   |
| 16     | 4         | 6.25%   |
| 31     | 3         | 4.69%   |
| 27     | 3         | 4.69%   |
| 21     | 2         | 3.13%   |
| 72     | 1         | 1.56%   |
| 24     | 1         | 1.56%   |
| 23     | 1         | 1.56%   |
| 22     | 1         | 1.56%   |
| 12     | 1         | 1.56%   |
| 11     | 1         | 1.56%   |
| 7      | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 60.94%  |
| 351-400     | 8         | 12.5%   |
| 501-600     | 4         | 6.25%   |
| 401-500     | 4         | 6.25%   |
| 201-300     | 4         | 6.25%   |
| 601-700     | 3         | 4.69%   |
| 1501-2000   | 1         | 1.56%   |
| 1-100       | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 83.64%  |
| 16/10 | 6         | 10.91%  |
| 5/4   | 1         | 1.82%   |
| 3/2   | 1         | 1.82%   |
| 0.67  | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 35.94%  |
| 81-90          | 17        | 26.56%  |
| 121-130        | 5         | 7.81%   |
| 351-500        | 3         | 4.69%   |
| 301-350        | 3         | 4.69%   |
| 201-250        | 3         | 4.69%   |
| 111-120        | 2         | 3.13%   |
| More than 1000 | 1         | 1.56%   |
| 71-80          | 1         | 1.56%   |
| 61-70          | 1         | 1.56%   |
| 51-60          | 1         | 1.56%   |
| 1-40           | 1         | 1.56%   |
| 251-300        | 1         | 1.56%   |
| 151-200        | 1         | 1.56%   |
| 141-150        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 53.33%  |
| 101-120       | 12        | 20%     |
| 51-100        | 9         | 15%     |
| 161-240       | 5         | 8.33%   |
| More than 240 | 1         | 1.67%   |
| 1-50          | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 80%     |
| 2     | 11        | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 40.48%  |
| Realtek Semiconductor | 31        | 36.9%   |
| Qualcomm Atheros      | 4         | 4.76%   |
| MediaTek              | 4         | 4.76%   |
| Broadcom Limited      | 3         | 3.57%   |
| ASIX Electronics      | 3         | 3.57%   |
| Sitecom Europe        | 1         | 1.19%   |
| Ralink Technology     | 1         | 1.19%   |
| Qualcomm              | 1         | 1.19%   |
| Huawei Technologies   | 1         | 1.19%   |
| Hewlett-Packard       | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 19.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 3.81%   |
| Intel Wireless 8265 / 8275                                             | 4         | 3.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 3.81%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.86%   |
| Intel Wireless 8260                                                    | 3         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 1.9%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 1.9%    |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.9%    |
| Broadcom Limited BCM43228 802.11a/b/g/n                                | 2         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.9%    |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter               | 1         | 0.95%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.95%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.95%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 0.95%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.95%   |
| Intel Wireless 7260                                                    | 1         | 0.95%   |
| Intel Wireless 3165                                                    | 1         | 0.95%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 1         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 1         | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 58.18%  |
| Realtek Semiconductor | 10        | 18.18%  |
| MediaTek              | 4         | 7.27%   |
| Qualcomm Atheros      | 3         | 5.45%   |
| Broadcom Limited      | 3         | 5.45%   |
| Sitecom Europe        | 1         | 1.82%   |
| Ralink Technology     | 1         | 1.82%   |
| Qualcomm              | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 4         | 7.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 4         | 7.14%   |
| Intel Wi-Fi 6 AX200                                           | 4         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 5.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 5.36%   |
| Intel Wireless 8260                                           | 3         | 5.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 5.36%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 3.57%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 3.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 3.57%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                       | 2         | 3.57%   |
| Sitecom Europe WL-113 rev 2 Wireless Network USB Adapter      | 1         | 1.79%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 1         | 1.79%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 1.79%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 1.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.79%   |
| Intel Wireless 7260                                           | 1         | 1.79%   |
| Intel Wireless 3165                                           | 1         | 1.79%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 1.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.79%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 59.57%  |
| Intel                 | 14        | 29.79%  |
| ASIX Electronics      | 3         | 6.38%   |
| Qualcomm Atheros      | 1         | 2.13%   |
| Huawei Technologies   | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 41.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 4.17%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 4.17%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 4.17%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 4.17%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 2.08%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.08%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 2.08%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 2.08%   |
| Huawei E353/E3131                                                      | 1         | 2.08%   |
| ASIX AX88772A Fast Ethernet                                            | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 52.94%  |
| Ethernet | 47        | 46.08%  |
| Modem    | 1         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 75%     |
| Ethernet | 15        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 70.91%  |
| 1     | 15        | 27.27%  |
| 0     | 1         | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 81.82%  |
| Yes  | 10        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 56.25%  |
| Realtek Semiconductor           | 6         | 12.5%   |
| Broadcom                        | 6         | 12.5%   |
| IMC Networks                    | 4         | 8.33%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| USI                             | 1         | 2.08%   |
| Qualcomm Atheros Communications | 1         | 2.08%   |
| MediaTek                        | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                           | 7         | 14.58%  |
| Intel AX201 Bluetooth                            | 7         | 14.58%  |
| Intel AX210 Bluetooth                            | 4         | 8.33%   |
| Intel AX200 Bluetooth                            | 4         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 6.25%   |
| Intel Bluetooth wireless interface               | 3         | 6.25%   |
| IMC Networks Wireless_Device                     | 3         | 6.25%   |
| Realtek Bluetooth Radio                          | 2         | 4.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 4.17%   |
| USI Bluetooth Device                             | 1         | 2.08%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 2.08%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 2.08%   |
| MediaTek Wireless_Device                         | 1         | 2.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 2.08%   |
| Intel AX211 Bluetooth                            | 1         | 2.08%   |
| IMC Networks Bluetooth Radio                     | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller  | 1         | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 2.08%   |
| Broadcom HP Portable SoftSailing                 | 1         | 2.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                | 1         | 2.08%   |
| Broadcom BCM20702A0                              | 1         | 2.08%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 53.95%  |
| Nvidia              | 17        | 22.37%  |
| AMD                 | 16        | 21.05%  |
| C-Media Electronics | 1         | 1.32%   |
| ASUSTek Computer    | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 12.36%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 6.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 5.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 5.62%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 4.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 4.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.37%   |
| Nvidia Audio device                                                                               | 3         | 3.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.25%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 2.25%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 2.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.12%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.12%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 1.12%   |
| ASUSTek Computer C-Media Audio                                                                    | 1         | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.12%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 30.77%  |
| SK hynix            | 10        | 19.23%  |
| Micron Technology   | 7         | 13.46%  |
| Kingston            | 7         | 13.46%  |
| Crucial             | 4         | 7.69%   |
| Corsair             | 2         | 3.85%   |
| Unknown             | 1         | 1.92%   |
| Neo Forza           | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| Innodisk            | 1         | 1.92%   |
| Essencore Limited   | 1         | 1.92%   |
| A-DATA Technology   | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 5.36%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 3.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 3.57%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 3.57%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 3.57%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s        | 2         | 3.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.79%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.79%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.79%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s           | 1         | 1.79%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s             | 1         | 1.79%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 1.79%   |
| Samsung RAM K3LK7K70BM-BGCP000 4096MB SODIMM 4266MT/s            | 1         | 1.79%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s          | 1         | 1.79%   |
| Nanya RAM NT4GC64C88B1NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.79%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.79%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.79%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.79%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.79%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s           | 1         | 1.79%   |
| Micron RAM 16ATF2G64HZ-2G1B1 16384MB SODIMM DDR4 2133MT/s        | 1         | 1.79%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.79%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.79%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s      | 1         | 1.79%   |
| Kingston RAM 9905712-007.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 24        | 52.17%  |
| DDR3   | 13        | 28.26%  |
| LPDDR5 | 3         | 6.52%   |
| LPDDR3 | 3         | 6.52%   |
| DDR5   | 2         | 4.35%   |
| LPDDR4 | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 85.11%  |
| Row Of Chips | 6         | 12.77%  |
| Chip         | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 50%     |
| 4096  | 15        | 28.85%  |
| 16384 | 7         | 13.46%  |
| 32768 | 2         | 3.85%   |
| 2048  | 2         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 16        | 32%     |
| 1600  | 10        | 20%     |
| 2667  | 5         | 10%     |
| 2133  | 3         | 6%      |
| 1334  | 3         | 6%      |
| 6400  | 2         | 4%      |
| 4800  | 2         | 4%      |
| 2400  | 2         | 4%      |
| 1867  | 2         | 4%      |
| 1333  | 2         | 4%      |
| 4267  | 1         | 2%      |
| 4266  | 1         | 2%      |
| 701   | 1         | 2%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| QinHeng CH340S | 1         | 100%    |

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
| Chicony Electronics                    | 14        | 28%     |
| Bison Electronics                      | 9         | 18%     |
| Realtek Semiconductor                  | 5         | 10%     |
| Microdia                               | 4         | 8%      |
| Syntek                                 | 3         | 6%      |
| Sonix Technology                       | 3         | 6%      |
| Luxvisions Innotech Limited            | 3         | 6%      |
| Quanta                                 | 2         | 4%      |
| Acer                                   | 2         | 4%      |
| Sunplus Innovation Technology          | 1         | 2%      |
| Samsung Electronics                    | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Lenovo                                 | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Bison HD Webcam                                                | 4         | 8%      |
| Chicony Integrated Camera                                      | 3         | 6%      |
| Bison BisonCam,NB Pro                                          | 3         | 6%      |
| Syntek Integrated Camera                                       | 2         | 4%      |
| Sonix USB2.0 FHD UVC WebCam                                    | 2         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 4%      |
| Chicony HD User Facing                                         | 2         | 4%      |
| Acer Integrated Camera                                         | 2         | 4%      |
| Syntek USB2.0 Camera                                           | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2%      |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 2%      |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 2%      |
| Realtek Laptop Camera                                          | 1         | 2%      |
| Realtek Integrated_Webcam_HD                                   | 1         | 2%      |
| Realtek Integrated Camera                                      | 1         | 2%      |
| Realtek EasyCamera                                             | 1         | 2%      |
| Realtek Bluetooth Radio                                        | 1         | 2%      |
| Quanta HP Wide Vision HD Camera                                | 1         | 2%      |
| Quanta HP Webcam                                               | 1         | 2%      |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                  | 1         | 2%      |
| Microdia Integrated Webcam                                     | 1         | 2%      |
| Microdia Dell Integrated HD Webcam                             | 1         | 2%      |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 2%      |
| Logitech C920 PRO HD Webcam                                    | 1         | 2%      |
| Lenovo Integrated Webcam [R5U877]                              | 1         | 2%      |
| Chicony Web Camera - FHD                                       | 1         | 2%      |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 2%      |
| Chicony Integrated Camera (1280x720@30)                        | 1         | 2%      |
| Chicony HP TrueVision HD Camera                                | 1         | 2%      |
| Chicony HP True Vision 5MP Camera                              | 1         | 2%      |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2%      |
| Chicony HP HD Camera                                           | 1         | 2%      |
| Chicony FJ Camera                                              | 1         | 2%      |
| Chicony Chicony USB 2.0 Camera                                 | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2%      |
| Bison ThinkPad Integrated Camera                               | 1         | 2%      |
| Bison Integrated Camera                                        | 1         | 2%      |

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
| Synaptics TouchPad                                              | 1         | 7.14%   |
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
| Upek        | 1         | 25%     |
| Lenovo      | 1         | 25%     |
| Broadcom    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 25%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 25%     |
| Broadcom 5880                                              | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 33        | 57.89%  |
| 1     | 18        | 31.58%  |
| 2     | 5         | 8.77%   |
| 3     | 1         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 45.16%  |
| Graphics card         | 5         | 16.13%  |
| Net/wireless          | 4         | 12.9%   |
| Multimedia controller | 3         | 9.68%   |
| Chipcard              | 3         | 9.68%   |
| Camera                | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

