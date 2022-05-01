Elementary 5.1.7 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Elementary 5.1.7.

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

Total: 92

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| HP        | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| Dell      | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek   | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASRock    | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock    | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| ASUSTek   | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Foxconn   | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| Foxconn   | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple     | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Intel     | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel     | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| Foxconn   | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| Gigabyte  | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Gigabyte  | H67A-USB3-B3                | [aaabb5b80f](https://linux-hardware.org/?probe=aaabb5b80f) | Sep 28, 2021 |
| Gigabyte  | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Gigabyte  | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| Gigabyte  | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Acer      | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| Biostar   | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar   | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek   | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASUSTek   | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek   | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| Gigabyte  | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek   | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell      | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell      | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI       | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP        | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI       | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| HP        | 843F                        | [de77cd09ab](https://linux-hardware.org/?probe=de77cd09ab) | Mar 22, 2021 |
| Gigabyte  | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP        | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo    | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| MSI       | B450M PRO-VDH MAX           | [d152990d34](https://linux-hardware.org/?probe=d152990d34) | Feb 13, 2021 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte  | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte  | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| MSI       | B450M PRO-VDH MAX           | [458481448c](https://linux-hardware.org/?probe=458481448c) | Feb 07, 2021 |
| ASRock    | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar   | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar   | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI       | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA      | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI       | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| ASUSTek   | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI       | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell      | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek   | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| MSI       | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| Biostar   | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock    | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell      | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| ASUSTek   | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte  | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP        | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte  | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek   | TUF GAMING X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| MSI       | B450M PRO-VDH MAX           | [29e128bea9](https://linux-hardware.org/?probe=29e128bea9) | Nov 20, 2020 |
| ASUSTek   | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte  | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| ASUSTek   | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| MSI       | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI       | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP        | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek   | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek   | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte  | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer      | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel     | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI       | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek   | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI       | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell      | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte  | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo    | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek   | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP        | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP        | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek   | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI       | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.4.0-48-generic       | 8        | 10.81%  |
| 5.4.0-65-generic       | 6        | 8.11%   |
| 5.4.0-54-generic       | 6        | 8.11%   |
| 5.4.0-42-generic       | 5        | 6.76%   |
| 5.4.0-58-generic       | 4        | 5.41%   |
| 5.4.0-47-generic       | 3        | 4.05%   |
| 5.4.0-90-generic       | 2        | 2.7%    |
| 5.4.0-80-generic       | 2        | 2.7%    |
| 5.4.0-71-generic       | 2        | 2.7%    |
| 5.4.0-70-generic       | 2        | 2.7%    |
| 5.4.0-60-generic       | 2        | 2.7%    |
| 5.4.0-56-generic       | 2        | 2.7%    |
| 5.4.0-53-generic       | 2        | 2.7%    |
| 5.4.0-52-generic       | 2        | 2.7%    |
| 4.15.0-161-generic     | 2        | 2.7%    |
| 4.15.0-128-generic     | 2        | 2.7%    |
| 4.15.0-112-generic     | 2        | 2.7%    |
| 5.4.0-94-generic       | 1        | 1.35%   |
| 5.4.0-91-generic       | 1        | 1.35%   |
| 5.4.0-84-generic       | 1        | 1.35%   |
| 5.4.0-77-generic       | 1        | 1.35%   |
| 5.4.0-74-generic       | 1        | 1.35%   |
| 5.4.0-73-generic       | 1        | 1.35%   |
| 5.4.0-67-generic       | 1        | 1.35%   |
| 5.4.0-66-generic       | 1        | 1.35%   |
| 5.4.0-62-generic       | 1        | 1.35%   |
| 5.4.0-49-generic       | 1        | 1.35%   |
| 5.4.0-45-generic       | 1        | 1.35%   |
| 5.4.0-107-generic      | 1        | 1.35%   |
| 5.4.0-100-generic      | 1        | 1.35%   |
| 5.17.0-051700-generic  | 1        | 1.35%   |
| 5.15.12-051512-generic | 1        | 1.35%   |
| 4.18.0-25-generic      | 1        | 1.35%   |
| 4.15.0-162-generic     | 1        | 1.35%   |
| 4.15.0-140-generic     | 1        | 1.35%   |
| 4.15.0-136-generic     | 1        | 1.35%   |
| 4.15.0-122-generic     | 1        | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 52       | 83.87%  |
| 4.15.0  | 7        | 11.29%  |
| 5.17.0  | 1        | 1.61%   |
| 5.15.12 | 1        | 1.61%   |
| 4.18.0  | 1        | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 52       | 83.87%  |
| 4.15    | 7        | 11.29%  |
| 5.17    | 1        | 1.61%   |
| 5.15    | 1        | 1.61%   |
| 4.18    | 1        | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 62       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 59       | 93.65%  |
| Unknown  | 4        | 6.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 62       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 77.42%  |
| LightDM | 7        | 11.29%  |
| TDM     | 5        | 8.06%   |
| SDDM    | 1        | 1.61%   |
| GDM     | 1        | 1.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 38.1%   |
| en_GB   | 6        | 9.52%   |
| es_ES   | 4        | 6.35%   |
| en_CA   | 3        | 4.76%   |
| pt_BR   | 2        | 3.17%   |
| pl_PL   | 2        | 3.17%   |
| es_MX   | 2        | 3.17%   |
| de_DE   | 2        | 3.17%   |
| uk_UA   | 1        | 1.59%   |
| sv_SE   | 1        | 1.59%   |
| hu_HU   | 1        | 1.59%   |
| gl_ES   | 1        | 1.59%   |
| fr_FR   | 1        | 1.59%   |
| fr_BE   | 1        | 1.59%   |
| es_SV   | 1        | 1.59%   |
| es_PA   | 1        | 1.59%   |
| es_EC   | 1        | 1.59%   |
| en_PH   | 1        | 1.59%   |
| en_IN   | 1        | 1.59%   |
| en_IE   | 1        | 1.59%   |
| en_HK   | 1        | 1.59%   |
| en_AU   | 1        | 1.59%   |
| el_GR   | 1        | 1.59%   |
| de_AT   | 1        | 1.59%   |
| cs_CZ   | 1        | 1.59%   |
| Unknown | 1        | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 37       | 58.73%  |
| EFI  | 26       | 41.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 59       | 93.65%  |
| Btrfs | 3        | 4.76%   |
| Xfs   | 1        | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 53       | 85.48%  |
| GPT     | 6        | 9.68%   |
| MBR     | 3        | 4.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 96.77%  |
| Yes       | 2        | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 75.81%  |
| Yes       | 15       | 24.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 29.03%  |
| Gigabyte Technology | 12       | 19.35%  |
| MSI                 | 6        | 9.68%   |
| Hewlett-Packard     | 5        | 8.06%   |
| Dell                | 5        | 8.06%   |
| ASRock              | 4        | 6.45%   |
| Biostar             | 3        | 4.84%   |
| Intel               | 2        | 3.23%   |
| Acer                | 2        | 3.23%   |
| Lenovo              | 1        | 1.61%   |
| Foxconn             | 1        | 1.61%   |
| EVGA                | 1        | 1.61%   |
| eMachines           | 1        | 1.61%   |
| Apple               | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS P8H61-M LX3 R2.0           | 2        | 3.23%   |
| ASUS All Series                 | 2        | 3.23%   |
| MSI P35 Platinum(MS-7345)       | 1        | 1.61%   |
| MSI MS-7C94                     | 1        | 1.61%   |
| MSI MS-7C02                     | 1        | 1.61%   |
| MSI MS-7A38                     | 1        | 1.61%   |
| MSI MS-7788                     | 1        | 1.61%   |
| MSI MS-7721                     | 1        | 1.61%   |
| Lenovo ThinkCentre M92p 3227D13 | 1        | 1.61%   |
| Intel DG41RQ AAE54511-204       | 1        | 1.61%   |
| Intel DG35EC AAE29266-205       | 1        | 1.61%   |
| HP Slim Desktop 290-p0xxx       | 1        | 1.61%   |
| HP ProDesk 600 G1 SFF           | 1        | 1.61%   |
| HP Compaq 8100 Elite SFF PC     | 1        | 1.61%   |
| HP Compaq 8100 Elite CMT PC     | 1        | 1.61%   |
| HP 260-p128ns                   | 1        | 1.61%   |
| Gigabyte Z77M-D3H               | 1        | 1.61%   |
| Gigabyte Z77-DS3H               | 1        | 1.61%   |
| Gigabyte Z68P-DS3               | 1        | 1.61%   |
| Gigabyte Z390 DESIGNARE         | 1        | 1.61%   |
| Gigabyte H81M-S2H               | 1        | 1.61%   |
| Gigabyte H67A-USB3-B3           | 1        | 1.61%   |
| Gigabyte H61M-S2PV              | 1        | 1.61%   |
| Gigabyte H61M-DS2               | 1        | 1.61%   |
| Gigabyte GA-MA78GM-S2H          | 1        | 1.61%   |
| Gigabyte F2A88XN-WIFI           | 1        | 1.61%   |
| Gigabyte AB350M-DS3H V2         | 1        | 1.61%   |
| Gigabyte A320M-S2H V2           | 1        | 1.61%   |
| Foxconn p6610f                  | 1        | 1.61%   |
| EVGA 132-CK-NF79                | 1        | 1.61%   |
| eMachines EL1358G               | 1        | 1.61%   |
| Dell Vostro 400                 | 1        | 1.61%   |
| Dell Precision T1600            | 1        | 1.61%   |
| Dell OptiPlex 960               | 1        | 1.61%   |
| Dell OptiPlex 360               | 1        | 1.61%   |
| Dell OptiPlex 3070              | 1        | 1.61%   |
| Biostar TA785G3 HD              | 1        | 1.61%   |
| Biostar Hi-Fi A70U3P            | 1        | 1.61%   |
| Biostar H61MH                   | 1        | 1.61%   |
| ASUS Z170-DELUXE                | 1        | 1.61%   |
| ASUS TUF GAMING X570-PLUS       | 1        | 1.61%   |
| ASUS TUF B360-PLUS GAMING       | 1        | 1.61%   |
| ASUS STRIX Z270H GAMING         | 1        | 1.61%   |
| ASUS ROG STRIX Z390-H GAMING    | 1        | 1.61%   |
| ASUS ROG STRIX B350-F GAMING    | 1        | 1.61%   |
| ASUS PRIME Z270-A               | 1        | 1.61%   |
| ASUS PRIME X470-PRO             | 1        | 1.61%   |
| ASUS PRIME H310M-E R2.0         | 1        | 1.61%   |
| ASUS PRIME A320M-K              | 1        | 1.61%   |
| ASUS PRIME A320I-K              | 1        | 1.61%   |
| ASUS M5A97                      | 1        | 1.61%   |
| ASUS M5A78L-M PLUS/USB3         | 1        | 1.61%   |
| ASUS CM6630_CM6730_CM6830       | 1        | 1.61%   |
| ASRock Z87E-ITX                 | 1        | 1.61%   |
| ASRock Z75 Pro3                 | 1        | 1.61%   |
| ASRock Z370 Pro4                | 1        | 1.61%   |
| ASRock H97M Pro4                | 1        | 1.61%   |
| Apple MacPro1,1                 | 1        | 1.61%   |
| Acer Aspire XC-603G             | 1        | 1.61%   |
| Acer Aspire X3200               | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 5        | 8.06%   |
| Dell OptiPlex          | 3        | 4.84%   |
| HP Compaq              | 2        | 3.23%   |
| ASUS TUF               | 2        | 3.23%   |
| ASUS ROG               | 2        | 3.23%   |
| ASUS P8H61-M           | 2        | 3.23%   |
| ASUS All               | 2        | 3.23%   |
| Acer Aspire            | 2        | 3.23%   |
| MSI P35                | 1        | 1.61%   |
| MSI MS-7C94            | 1        | 1.61%   |
| MSI MS-7C02            | 1        | 1.61%   |
| MSI MS-7A38            | 1        | 1.61%   |
| MSI MS-7788            | 1        | 1.61%   |
| MSI MS-7721            | 1        | 1.61%   |
| Lenovo ThinkCentre     | 1        | 1.61%   |
| Intel DG41RQ           | 1        | 1.61%   |
| Intel DG35EC           | 1        | 1.61%   |
| HP Slim                | 1        | 1.61%   |
| HP ProDesk             | 1        | 1.61%   |
| HP 260-p128ns          | 1        | 1.61%   |
| Gigabyte Z77M-D3H      | 1        | 1.61%   |
| Gigabyte Z77-DS3H      | 1        | 1.61%   |
| Gigabyte Z68P-DS3      | 1        | 1.61%   |
| Gigabyte Z390          | 1        | 1.61%   |
| Gigabyte H81M-S2H      | 1        | 1.61%   |
| Gigabyte H67A-USB3-B3  | 1        | 1.61%   |
| Gigabyte H61M-S2PV     | 1        | 1.61%   |
| Gigabyte H61M-DS2      | 1        | 1.61%   |
| Gigabyte GA-MA78GM-S2H | 1        | 1.61%   |
| Gigabyte F2A88XN-WIFI  | 1        | 1.61%   |
| Gigabyte AB350M-DS3H   | 1        | 1.61%   |
| Gigabyte A320M-S2H     | 1        | 1.61%   |
| Foxconn p6610f         | 1        | 1.61%   |
| EVGA 132-CK-NF79       | 1        | 1.61%   |
| eMachines EL1358G      | 1        | 1.61%   |
| Dell Vostro            | 1        | 1.61%   |
| Dell Precision         | 1        | 1.61%   |
| Biostar TA785G3        | 1        | 1.61%   |
| Biostar Hi-Fi          | 1        | 1.61%   |
| Biostar H61MH          | 1        | 1.61%   |
| ASUS Z170-DELUXE       | 1        | 1.61%   |
| ASUS STRIX             | 1        | 1.61%   |
| ASUS M5A97             | 1        | 1.61%   |
| ASUS M5A78L-M          | 1        | 1.61%   |
| ASUS CM6630            | 1        | 1.61%   |
| ASRock Z87E-ITX        | 1        | 1.61%   |
| ASRock Z75             | 1        | 1.61%   |
| ASRock Z370            | 1        | 1.61%   |
| ASRock H97M            | 1        | 1.61%   |
| Apple MacPro1          | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 9        | 14.52%  |
| 2019 | 7        | 11.29%  |
| 2012 | 7        | 11.29%  |
| 2011 | 7        | 11.29%  |
| 2008 | 7        | 11.29%  |
| 2018 | 6        | 9.68%   |
| 2017 | 4        | 6.45%   |
| 2016 | 4        | 6.45%   |
| 2009 | 4        | 6.45%   |
| 2014 | 2        | 3.23%   |
| 2010 | 2        | 3.23%   |
| 2020 | 1        | 1.61%   |
| 2015 | 1        | 1.61%   |
| 2007 | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 21       | 33.87%  |
| 4.01-8.0    | 10       | 16.13%  |
| 3.01-4.0    | 10       | 16.13%  |
| 16.01-24.0  | 9        | 14.52%  |
| 32.01-64.0  | 6        | 9.68%   |
| 2.01-3.0    | 2        | 3.23%   |
| 1.01-2.0    | 2        | 3.23%   |
| 24.01-32.0  | 1        | 1.61%   |
| 64.01-256.0 | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 28       | 40%     |
| 2.01-3.0  | 16       | 22.86%  |
| 4.01-8.0  | 14       | 20%     |
| 3.01-4.0  | 10       | 14.29%  |
| 8.01-16.0 | 1        | 1.43%   |
| 0.51-1.0  | 1        | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 43.75%  |
| 2      | 19       | 29.69%  |
| 3      | 5        | 7.81%   |
| 4      | 4        | 6.25%   |
| 5      | 3        | 4.69%   |
| 7      | 2        | 3.13%   |
| 6      | 2        | 3.13%   |
| 0      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 53.85%  |
| Yes       | 30       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 96.77%  |
| No        | 2        | 3.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 53.97%  |
| No        | 29       | 46.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 69.35%  |
| Yes       | 19       | 30.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 6        | 9.68%   |
| UK           | 6        | 9.68%   |
| Brazil       | 6        | 9.68%   |
| Spain        | 4        | 6.45%   |
| Poland       | 4        | 6.45%   |
| Canada       | 4        | 6.45%   |
| Mexico       | 3        | 4.84%   |
| India        | 2        | 3.23%   |
| Germany      | 2        | 3.23%   |
| Venezuela    | 1        | 1.61%   |
| Ukraine      | 1        | 1.61%   |
| Sweden       | 1        | 1.61%   |
| Sint Maarten | 1        | 1.61%   |
| Russia       | 1        | 1.61%   |
| Philippines  | 1        | 1.61%   |
| Panama       | 1        | 1.61%   |
| Netherlands  | 1        | 1.61%   |
| Malaysia     | 1        | 1.61%   |
| Luxembourg   | 1        | 1.61%   |
| Kosovo       | 1        | 1.61%   |
| Ireland      | 1        | 1.61%   |
| Indonesia    | 1        | 1.61%   |
| Hungary      | 1        | 1.61%   |
| Hong Kong    | 1        | 1.61%   |
| Greece       | 1        | 1.61%   |
| France       | 1        | 1.61%   |
| El Salvador  | 1        | 1.61%   |
| Ecuador      | 1        | 1.61%   |
| Czechia      | 1        | 1.61%   |
| Costa Rica   | 1        | 1.61%   |
| Belgium      | 1        | 1.61%   |
| Austria      | 1        | 1.61%   |
| Australia    | 1        | 1.61%   |
| Argentina    | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Fortaleza                 | 3        | 4.55%   |
| Berlin                    | 2        | 3.03%   |
| Wroclaw                   | 1        | 1.52%   |
| Whiting Bay               | 1        | 1.52%   |
| Warsaw                    | 1        | 1.52%   |
| Vilvoorde                 | 1        | 1.52%   |
| Vannes                    | 1        | 1.52%   |
| Tseung Kwan O             | 1        | 1.52%   |
| SГЈo JosГ© dos Campos | 1        | 1.52%   |
| Sokolov                   | 1        | 1.52%   |
| Saunders                  | 1        | 1.52%   |
| San Salvador              | 1        | 1.52%   |
| Rio de Janeiro            | 1        | 1.52%   |
| Quito                     | 1        | 1.52%   |
| Quezon City               | 1        | 1.52%   |
| Prizren                   | 1        | 1.52%   |
| Pontevedra                | 1        | 1.52%   |
| Philipsburg               | 1        | 1.52%   |
| Pell City                 | 1        | 1.52%   |
| PÃ©cs                   | 1        | 1.52%   |
| Panchkula                 | 1        | 1.52%   |
| Panama City               | 1        | 1.52%   |
| Opp                       | 1        | 1.52%   |
| Novosibirsk               | 1        | 1.52%   |
| Morelia                   | 1        | 1.52%   |
| Moravia                   | 1        | 1.52%   |
| Montreal                  | 1        | 1.52%   |
| Mexico City               | 1        | 1.52%   |
| Manchester                | 1        | 1.52%   |
| Macon                     | 1        | 1.52%   |
| Luxembourg                | 1        | 1.52%   |
| Lund                      | 1        | 1.52%   |
| Lamia                     | 1        | 1.52%   |
| Kota Kinabalu             | 1        | 1.52%   |
| Kentville                 | 1        | 1.52%   |
| Juazeiro                  | 1        | 1.52%   |
| Jozefow                   | 1        | 1.52%   |
| Jepara                    | 1        | 1.52%   |
| Irpin                     | 1        | 1.52%   |
| Innsbruck                 | 1        | 1.52%   |
| Ingenio                   | 1        | 1.52%   |
| Highland Park             | 1        | 1.52%   |
| Havre de Grace            | 1        | 1.52%   |
| Gilbert                   | 1        | 1.52%   |
| Flint                     | 1        | 1.52%   |
| Flesherton                | 1        | 1.52%   |
| Farmington                | 1        | 1.52%   |
| Emmen                     | 1        | 1.52%   |
| Dundas                    | 1        | 1.52%   |
| Dublin                    | 1        | 1.52%   |
| Debica                    | 1        | 1.52%   |
| CГіrdoba                | 1        | 1.52%   |
| Corbera de Llobregat      | 1        | 1.52%   |
| Coatbridge                | 1        | 1.52%   |
| Clapham                   | 1        | 1.52%   |
| Central                   | 1        | 1.52%   |
| Caracas                   | 1        | 1.52%   |
| Campbeltown               | 1        | 1.52%   |
| Cala d'Or                 | 1        | 1.52%   |
| Bristol                   | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 38     | 26.17%  |
| WDC                 | 17       | 26     | 15.89%  |
| Samsung Electronics | 15       | 25     | 14.02%  |
| Kingston            | 9        | 20     | 8.41%   |
| Crucial             | 9        | 11     | 8.41%   |
| Toshiba             | 5        | 16     | 4.67%   |
| SanDisk             | 5        | 5      | 4.67%   |
| Hitachi             | 3        | 3      | 2.8%    |
| Unknown             | 2        | 2      | 1.87%   |
| HGST                | 2        | 3      | 1.87%   |
| A-DATA Technology   | 2        | 3      | 1.87%   |
| WDC WDS             | 1        | 1      | 0.93%   |
| PNY                 | 1        | 1      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OWC                 | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 2      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Intel               | 1        | 1      | 0.93%   |
| GOODRAM             | 1        | 3      | 0.93%   |
| GeIL                | 1        | 1      | 0.93%   |
| China               | 1        | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 4        | 3.17%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 3.17%   |
| Toshiba DT01ACA100 1TB             | 3        | 2.38%   |
| SanDisk SSD PLUS 480GB             | 3        | 2.38%   |
| Samsung SSD 850 EVO 250GB          | 3        | 2.38%   |
| Kingston SV300S37A120G 120GB SSD   | 3        | 2.38%   |
| Crucial CT120BX300SSD1 120GB       | 3        | 2.38%   |
| Seagate ST3500418AS 500GB          | 2        | 1.59%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 1.59%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 1.59%   |
| Samsung SSD 970 EVO 500GB          | 2        | 1.59%   |
| Samsung SSD 850 EVO 500GB          | 2        | 1.59%   |
| Samsung SSD 840 EVO 500GB          | 2        | 1.59%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.59%   |
| Crucial CT120BX500SSD1 120GB       | 2        | 1.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.79%   |
| WDC WDS250G2B0B-00YS70 250GB SSD   | 1        | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 0.79%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.79%   |
| WDC WDS100T1R0B-68A4Z0 1TB SSD     | 1        | 0.79%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD  | 1        | 0.79%   |
| WDC WD6003FZBX-00K5WB0 6TB         | 1        | 0.79%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1        | 0.79%   |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 0.79%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 0.79%   |
| WDC WD5000AAKS-00M9A0 500GB        | 1        | 0.79%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 0.79%   |
| WDC WD3000GLFS-01F8U0 304GB        | 1        | 0.79%   |
| WDC WD20EZRX-22D8PB0 2TB           | 1        | 0.79%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.79%   |
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 0.79%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1        | 0.79%   |
| WDC WD10JPVT-22A1YT0 1TB           | 1        | 0.79%   |
| WDC WD10EZEX-75M2NA0 1TB           | 1        | 0.79%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1        | 0.79%   |
| WDC WD10EURX-63UY4Y0 1TB           | 1        | 0.79%   |
| WDC WD10EALX-009BA0 1TB            | 1        | 0.79%   |
| Unknown SD/MMC/MS PRO 16GB         | 1        | 0.79%   |
| Unknown NVMe SSD Drive 1024GB      | 1        | 0.79%   |
| Toshiba MQ01ABD032 320GB           | 1        | 0.79%   |
| Toshiba MK5065GSX 500GB            | 1        | 0.79%   |
| Toshiba HDWD130 3TB                | 1        | 0.79%   |
| Seagate ST9160821AS 160GB          | 1        | 0.79%   |
| Seagate ST9160314AS 160GB          | 1        | 0.79%   |
| Seagate ST8000AS0003-2HH188 8TB    | 1        | 0.79%   |
| Seagate ST500LX025-1U717D 500GB    | 1        | 0.79%   |
| Seagate ST500DM002-1SB10A 500GB    | 1        | 0.79%   |
| Seagate ST3750640AS 752GB          | 1        | 0.79%   |
| Seagate ST3500312CS 500GB          | 1        | 0.79%   |
| Seagate ST3320620NS 320GB          | 1        | 0.79%   |
| Seagate ST3320613AS 320GB          | 1        | 0.79%   |
| Seagate ST3250310AS 250GB          | 1        | 0.79%   |
| Seagate ST3160815AS 160GB          | 1        | 0.79%   |
| Seagate ST31000528AS 1TB           | 1        | 0.79%   |
| Seagate ST2000DX001-1CM164 2TB     | 1        | 0.79%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 0.79%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 0.79%   |
| Seagate ST1000VT000 HN-M101MBB 1TB | 1        | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 0.79%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 38     | 51.85%  |
| WDC                 | 12       | 21     | 22.22%  |
| Toshiba             | 5        | 16     | 9.26%   |
| Samsung Electronics | 3        | 3      | 5.56%   |
| Hitachi             | 3        | 3      | 5.56%   |
| HGST                | 2        | 3      | 3.7%    |
| Unknown             | 1        | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 16     | 23.08%  |
| Kingston            | 9        | 13     | 17.31%  |
| Crucial             | 9        | 11     | 17.31%  |
| WDC                 | 5        | 5      | 9.62%   |
| SanDisk             | 5        | 5      | 9.62%   |
| A-DATA Technology   | 2        | 3      | 3.85%   |
| WDC WDS             | 1        | 1      | 1.92%   |
| PNY                 | 1        | 1      | 1.92%   |
| Patriot             | 1        | 1      | 1.92%   |
| OWC                 | 1        | 1      | 1.92%   |
| OCZ                 | 1        | 2      | 1.92%   |
| KingSpec            | 1        | 1      | 1.92%   |
| Intel               | 1        | 1      | 1.92%   |
| GOODRAM             | 1        | 3      | 1.92%   |
| GeIL                | 1        | 1      | 1.92%   |
| China               | 1        | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 42       | 85     | 48.28%  |
| SSD  | 38       | 66     | 43.68%  |
| NVMe | 7        | 14     | 8.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 147    | 84.29%  |
| NVMe | 7        | 14     | 10%     |
| SAS  | 4        | 4      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 96     | 62.2%   |
| 0.51-1.0   | 20       | 33     | 24.39%  |
| 1.01-2.0   | 6        | 12     | 7.32%   |
| 4.01-10.0  | 3        | 3      | 3.66%   |
| 2.01-3.0   | 2        | 7      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 30.3%   |
| 251-500        | 18       | 27.27%  |
| 501-1000       | 12       | 18.18%  |
| More than 3000 | 4        | 6.06%   |
| 1001-2000      | 4        | 6.06%   |
| 2001-3000      | 3        | 4.55%   |
| 51-100         | 3        | 4.55%   |
| 21-50          | 2        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 23.53%  |
| 21-50          | 12       | 17.65%  |
| 51-100         | 12       | 17.65%  |
| 101-250        | 11       | 16.18%  |
| 501-1000       | 6        | 8.82%   |
| 251-500        | 4        | 5.88%   |
| More than 3000 | 3        | 4.41%   |
| 1001-2000      | 3        | 4.41%   |
| 2001-3000      | 1        | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB    | 1        | 1      | 12.5%   |
| WDC WD5000AAKX-221CA1 500GB     | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 12.5%   |
| Seagate ST2000DM006-2DM164 2TB  | 1        | 1      | 12.5%   |
| Samsung Electronics HD204UI 2TB | 1        | 1      | 12.5%   |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 12.5%   |
| HGST HUS724030ALA640 3TB        | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 37.5%   |
| WDC                 | 2        | 2      | 25%     |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Kingston            | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 42.86%  |
| WDC                 | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| HGST                | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 87.5%   |
| SSD  | 1        | 1      | 12.5%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 52       | 135    | 75.36%  |
| Works    | 9        | 22     | 13.04%  |
| Malfunc  | 8        | 8      | 11.59%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 41       | 53.25%  |
| AMD                         | 18       | 23.38%  |
| Samsung Electronics         | 5        | 6.49%   |
| Nvidia                      | 3        | 3.9%    |
| ASMedia Technology          | 3        | 3.9%    |
| Kingston Technology Company | 2        | 2.6%    |
| JMicron Technology          | 2        | 2.6%    |
| Silicon Image               | 1        | 1.3%    |
| Marvell Technology Group    | 1        | 1.3%    |
| ADATA Technology            | 1        | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 10.89%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 5.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.97%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.97%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.98%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.98%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.98%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.98%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.98%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.99%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.99%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.99%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.99%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.99%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.99%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.99%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.99%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.99%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.99%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.99%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.99%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.99%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 0.99%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.99%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.99%   |
| ASMedia 106x SATA/RAID Controller                                                       | 1        | 0.99%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 64.47%  |
| IDE  | 17       | 22.37%  |
| NVMe | 7        | 9.21%   |
| RAID | 3        | 3.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 67.74%  |
| AMD    | 20       | 32.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-3330S CPU @ 2.70GHz              | 3        | 4.84%   |
| Intel Core i5-3330 CPU @ 3.00GHz               | 2        | 3.23%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 2        | 3.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 3.23%   |
| Intel Core i3-9100 CPU @ 3.60GHz               | 2        | 3.23%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 2        | 3.23%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 3.23%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 2        | 3.23%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 2        | 3.23%   |
| AMD FX-6100 Six-Core Processor                 | 2        | 3.23%   |
| Intel Xeon CPU E31230 @ 3.20GHz                | 1        | 1.61%   |
| Intel Xeon CPU E31225 @ 3.10GHz                | 1        | 1.61%   |
| Intel Xeon CPU 5160 @ 3.00GHz                  | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz    | 1        | 1.61%   |
| Intel Pentium CPU G3258 @ 3.20GHz              | 1        | 1.61%   |
| Intel Core i7-9700KF CPU @ 3.60GHz             | 1        | 1.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 1.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 1.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 1        | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 1.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 1.61%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.61%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 1.61%   |
| Intel Core i5-2500 CPU @ 3.30GHz               | 1        | 1.61%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.61%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 1        | 1.61%   |
| Intel Core i5 CPU 650 @ 3.20GHz                | 1        | 1.61%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1        | 1.61%   |
| Intel Core i3-4160T CPU @ 3.10GHz              | 1        | 1.61%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz          | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 1        | 1.61%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz           | 1        | 1.61%   |
| Intel Celeron G4900 CPU @ 3.10GHz              | 1        | 1.61%   |
| Intel Celeron CPU J1900 @ 1.99GHz              | 1        | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 1.61%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 1.61%   |
| AMD Phenom II X4 965 Processor                 | 1        | 1.61%   |
| AMD Phenom II X4 955 Processor                 | 1        | 1.61%   |
| AMD Phenom 8450 Triple-Core Processor          | 1        | 1.61%   |
| AMD Athlon II X4 635 Processor                 | 1        | 1.61%   |
| AMD Athlon II X3 425 Processor                 | 1        | 1.61%   |
| AMD A8-7680 Radeon R7, 10 Compute Cores 4C+6G  | 1        | 1.61%   |
| AMD A8-7670K Radeon R7, 10 Compute Cores 4C+6G | 1        | 1.61%   |
| AMD A4-5300 APU with Radeon HD Graphics        | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 29.03%  |
| AMD Ryzen 5             | 7        | 11.29%  |
| Intel Core i7           | 6        | 9.68%   |
| Intel Core i3           | 5        | 8.06%   |
| Intel Core 2 Quad       | 4        | 6.45%   |
| Intel Xeon              | 3        | 4.84%   |
| Intel Core 2 Duo        | 2        | 3.23%   |
| Intel Celeron           | 2        | 3.23%   |
| AMD Ryzen 3             | 2        | 3.23%   |
| AMD Phenom II X4        | 2        | 3.23%   |
| AMD FX                  | 2        | 3.23%   |
| AMD A8                  | 2        | 3.23%   |
| Intel Pentium Dual-Core | 1        | 1.61%   |
| Intel Pentium           | 1        | 1.61%   |
| AMD Ryzen 9             | 1        | 1.61%   |
| AMD Phenom              | 1        | 1.61%   |
| AMD Athlon II X4        | 1        | 1.61%   |
| AMD Athlon II X3        | 1        | 1.61%   |
| AMD A4                  | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 39       | 62.9%   |
| 2      | 10       | 16.13%  |
| 6      | 5        | 8.06%   |
| 3      | 4        | 6.45%   |
| 8      | 2        | 3.23%   |
| 12     | 1        | 1.61%   |
| 1      | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 98.39%  |
| 2      | 1        | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 66.13%  |
| 2      | 21       | 33.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 62       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 7        | 11.29%  |
| 0x306a9    | 6        | 9.68%   |
| 0x306c3    | 5        | 8.06%   |
| 0x906eb    | 4        | 6.45%   |
| Unknown    | 4        | 6.45%   |
| 0x1067a    | 3        | 4.84%   |
| 0x08108109 | 3        | 4.84%   |
| 0x906e9    | 2        | 3.23%   |
| 0x506e3    | 2        | 3.23%   |
| 0x10676    | 2        | 3.23%   |
| 0x08701021 | 2        | 3.23%   |
| 0x0600063e | 2        | 3.23%   |
| 0x010000c8 | 2        | 3.23%   |
| 0x906ed    | 1        | 1.61%   |
| 0x906ec    | 1        | 1.61%   |
| 0x906ea    | 1        | 1.61%   |
| 0x6fb      | 1        | 1.61%   |
| 0x6f6      | 1        | 1.61%   |
| 0x30673    | 1        | 1.61%   |
| 0x20652    | 1        | 1.61%   |
| 0x106e5    | 1        | 1.61%   |
| 0x08701013 | 1        | 1.61%   |
| 0x08101016 | 1        | 1.61%   |
| 0x0810100b | 1        | 1.61%   |
| 0x0800820d | 1        | 1.61%   |
| 0x08001129 | 1        | 1.61%   |
| 0x0600611a | 1        | 1.61%   |
| 0x06003106 | 1        | 1.61%   |
| 0x06001119 | 1        | 1.61%   |
| 0x010000db | 1        | 1.61%   |
| 0x01000083 | 1        | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 9        | 14.52%  |
| SandyBridge | 8        | 12.9%   |
| IvyBridge   | 6        | 9.68%   |
| Haswell     | 6        | 9.68%   |
| Penryn      | 5        | 8.06%   |
| K10         | 5        | 8.06%   |
| Zen+        | 4        | 6.45%   |
| Zen 2       | 3        | 4.84%   |
| Zen         | 3        | 4.84%   |
| Core        | 3        | 4.84%   |
| Skylake     | 2        | 3.23%   |
| Bulldozer   | 2        | 3.23%   |
| Westmere    | 1        | 1.61%   |
| Steamroller | 1        | 1.61%   |
| Silvermont  | 1        | 1.61%   |
| Piledriver  | 1        | 1.61%   |
| Nehalem     | 1        | 1.61%   |
| Excavator   | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 24       | 36.36%  |
| Nvidia | 22       | 33.33%  |
| Intel  | 20       | 30.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 7.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 7.25%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 4.35%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 4.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.9%    |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 2.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.9%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.45%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.45%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.45%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.45%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.45%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.45%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.45%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.45%   |
| Nvidia G98 [GeForce 9300 GE]                                                | 1        | 1.45%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.45%   |
| Nvidia G84GL [Quadro FX 570]                                                | 1        | 1.45%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.45%   |
| Intel HD Graphics 530                                                       | 1        | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.45%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.45%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 1.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.45%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 1.45%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                            | 1        | 1.45%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 1.45%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.45%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.45%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 1.45%   |
| AMD Cedar GL [FirePro 2270]                                                 | 1        | 1.45%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.45%   |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 1.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.45%   |
| AMD Baffin [Radeon Pro WX 4100]                                             | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 23       | 37.1%   |
| 1 x Nvidia     | 20       | 32.26%  |
| 1 x Intel      | 16       | 25.81%  |
| 2 x Nvidia     | 1        | 1.61%   |
| 2 x AMD        | 1        | 1.61%   |
| Intel + Nvidia | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42       | 67.74%  |
| Proprietary | 18       | 29.03%  |
| Unknown     | 2        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 18       | 29.03%  |
| Unknown    | 15       | 24.19%  |
| 0.01-0.5   | 9        | 14.52%  |
| 7.01-8.0   | 7        | 11.29%  |
| 0.51-1.0   | 6        | 9.68%   |
| 3.01-4.0   | 5        | 8.06%   |
| 5.01-6.0   | 2        | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 11       | 16.67%  |
| Samsung Electronics  | 9        | 13.64%  |
| Goldstar             | 9        | 13.64%  |
| AOC                  | 5        | 7.58%   |
| Ancor Communications | 5        | 7.58%   |
| ViewSonic            | 3        | 4.55%   |
| LG Electronics       | 3        | 4.55%   |
| Acer                 | 3        | 4.55%   |
| Unknown              | 2        | 3.03%   |
| Hewlett-Packard      | 2        | 3.03%   |
| BenQ                 | 2        | 3.03%   |
| Apple                | 2        | 3.03%   |
| ___                  | 1        | 1.52%   |
| Vizio                | 1        | 1.52%   |
| SAC                  | 1        | 1.52%   |
| Ruijiang             | 1        | 1.52%   |
| Philips              | 1        | 1.52%   |
| KIV                  | 1        | 1.52%   |
| Iiyama               | 1        | 1.52%   |
| HPN                  | 1        | 1.52%   |
| Haier                | 1        | 1.52%   |
| Fujitsu Siemens      | 1        | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 3        | 4.29%   |
| ___ LCDTV16 ___0101 1360x768                                            | 1        | 1.43%   |
| Vizio D39h-D0 VIZ1002 1366x768 853x479mm 38.5-inch                      | 1        | 1.43%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch           | 1        | 1.43%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 1.43%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch            | 1        | 1.43%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                     | 1        | 1.43%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 1.43%   |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch       | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch    | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch     | 1        | 1.43%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 1        | 1.43%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch    | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 1.43%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                       | 1        | 1.43%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                   | 1        | 1.43%   |
| Ruijiang HDMI RJT003A 1920x1080 800x480mm 36.7-inch                     | 1        | 1.43%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 1.43%   |
| LG Electronics LCD Monitor W2252 3600x1080                              | 1        | 1.43%   |
| LG Electronics LCD Monitor M227WAP 1920x1080                            | 1        | 1.43%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                       | 1        | 1.43%   |
| KIV Kivi TV KIV0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.43%   |
| Iiyama PL3270Q IVM7608 2560x1440 698x393mm 31.5-inch                    | 1        | 1.43%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                    | 1        | 1.43%   |
| HPN LCD Monitor HP 27fh 1920x1080                                       | 1        | 1.43%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch              | 1        | 1.43%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch               | 1        | 1.43%   |
| Haier HAIER HRE0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.43%   |
| Goldstar M288WA GSM563D 1680x1050 434x270mm 20.1-inch                   | 1        | 1.43%   |
| Goldstar L1750SQ GSM43E8 1280x1024 338x270mm 17.0-inch                  | 1        | 1.43%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1        | 1.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1        | 1.43%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                    | 1        | 1.43%   |
| Goldstar E2241 GSM5818 1920x1080 480x270mm 21.7-inch                    | 1        | 1.43%   |
| Fujitsu Siemens P19-1 FUS0452 1280x1024 376x301mm 19.0-inch             | 1        | 1.43%   |
| Dell U3415W DELA0A7 3440x1440 798x335mm 34.1-inch                       | 1        | 1.43%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                       | 1        | 1.43%   |
| Dell S2009W DELA044 1600x900 443x249mm 20.0-inch                        | 1        | 1.43%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                       | 1        | 1.43%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                        | 1        | 1.43%   |
| Dell P190S DEL405A 1280x1024 376x301mm 19.0-inch                        | 1        | 1.43%   |
| Dell LCD Monitor U2212HM                                                | 1        | 1.43%   |
| Dell LCD Monitor SE2419HR 1920x1080                                     | 1        | 1.43%   |
| Dell LCD Monitor S2817Q 3968x1280                                       | 1        | 1.43%   |
| Dell LCD Monitor P2412H 1920x1080                                       | 1        | 1.43%   |
| Dell LCD Monitor E2009W 1680x1050                                       | 1        | 1.43%   |
| Dell E2016H DELA0C8 1600x900 432x236mm 19.4-inch                        | 1        | 1.43%   |
| Dell 2007FP DELA020 1600x1200 367x275mm 18.1-inch                       | 1        | 1.43%   |
| BenQ PJ BNQ0203 1920x1080                                               | 1        | 1.43%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                       | 1        | 1.43%   |
| Apple Cinema HD Display APP9220 2560x1600 641x401mm 29.8-inch           | 1        | 1.43%   |
| Apple Cinema HD APP9221 2560x1600 641x401mm 29.8-inch                   | 1        | 1.43%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 1        | 1.43%   |
| AOC LCD Monitor 2757                                                    | 1        | 1.43%   |
| AOC 2770 AOC2770 1920x1080 598x336mm 27.0-inch                          | 1        | 1.43%   |
| AOC 2369 AOC2369 1920x1080 509x286mm 23.0-inch                          | 1        | 1.43%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                          | 1        | 1.43%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch        | 1        | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 40.63%  |
| 1600x900 (HD+)     | 7        | 10.94%  |
| 2560x1440 (QHD)    | 4        | 6.25%   |
| 1680x1050 (WSXGA+) | 4        | 6.25%   |
| 3840x2160 (4K)     | 3        | 4.69%   |
| 1366x768 (WXGA)    | 3        | 4.69%   |
| Unknown            | 3        | 4.69%   |
| 3440x1440          | 2        | 3.13%   |
| 2560x1600          | 2        | 3.13%   |
| 1280x1024 (SXGA)   | 2        | 3.13%   |
| 5120x1440          | 1        | 1.56%   |
| 3968x1280          | 1        | 1.56%   |
| 3600x1080          | 1        | 1.56%   |
| 2288x1287          | 1        | 1.56%   |
| 2048x1152          | 1        | 1.56%   |
| 1600x1200          | 1        | 1.56%   |
| 1440x900 (WXGA+)   | 1        | 1.56%   |
| 1024x768 (XGA)     | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 20.9%   |
| 21      | 7        | 10.45%  |
| 20      | 7        | 10.45%  |
| 27      | 6        | 8.96%   |
| 19      | 6        | 8.96%   |
| 24      | 5        | 7.46%   |
| 23      | 4        | 5.97%   |
| 84      | 2        | 2.99%   |
| 32      | 2        | 2.99%   |
| 29      | 2        | 2.99%   |
| 22      | 2        | 2.99%   |
| 18      | 2        | 2.99%   |
| 72      | 1        | 1.49%   |
| 57      | 1        | 1.49%   |
| 38      | 1        | 1.49%   |
| 34      | 1        | 1.49%   |
| 33      | 1        | 1.49%   |
| 31      | 1        | 1.49%   |
| 17      | 1        | 1.49%   |
| 15      | 1        | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 20       | 31.75%  |
| Unknown     | 14       | 22.22%  |
| 501-600     | 13       | 20.63%  |
| 701-800     | 4        | 6.35%   |
| 601-700     | 3        | 4.76%   |
| 1501-2000   | 3        | 4.76%   |
| 351-400     | 2        | 3.17%   |
| 301-350     | 2        | 3.17%   |
| 801-900     | 1        | 1.59%   |
| 1001-1500   | 1        | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 32       | 56.14%  |
| Unknown | 13       | 22.81%  |
| 16/10   | 5        | 8.77%   |
| 5/4     | 3        | 5.26%   |
| 4/3     | 2        | 3.51%   |
| 3/2     | 1        | 1.75%   |
| 21/9    | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 23.81%  |
| Unknown        | 14       | 22.22%  |
| 151-200        | 11       | 17.46%  |
| 351-500        | 7        | 11.11%  |
| 301-350        | 6        | 9.52%   |
| More than 1000 | 4        | 6.35%   |
| 141-150        | 3        | 4.76%   |
| 251-300        | 1        | 1.59%   |
| 101-110        | 1        | 1.59%   |
| 501-1000       | 1        | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 53.45%  |
| Unknown | 14       | 24.14%  |
| 101-120 | 11       | 18.97%  |
| 1-50    | 2        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 71.43%  |
| 2     | 11       | 17.46%  |
| 3     | 4        | 6.35%   |
| 0     | 3        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 42.86%  |
| Intel                           | 24       | 26.37%  |
| Qualcomm Atheros                | 7        | 7.69%   |
| Broadcom                        | 5        | 5.49%   |
| TP-Link                         | 4        | 4.4%    |
| Nvidia                          | 3        | 3.3%    |
| VIA Technologies                | 1        | 1.1%    |
| Samsung Electronics             | 1        | 1.1%    |
| Qualcomm Atheros Communications | 1        | 1.1%    |
| Microsoft                       | 1        | 1.1%    |
| Huawei Technologies             | 1        | 1.1%    |
| D-Link System                   | 1        | 1.1%    |
| D-Link                          | 1        | 1.1%    |
| BUFFALO                         | 1        | 1.1%    |
| Broadcom Limited                | 1        | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 31       | 30.39%  |
| Intel I211 Gigabit Network Connection                                             | 4        | 3.92%   |
| Intel Ethernet Connection (2) I219-V                                              | 4        | 3.92%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 3        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                                              | 3        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 1.96%   |
| Realtek 802.11ac NIC                                                              | 2        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 2        | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 2        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                               | 2        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 2        | 1.96%   |
| Intel 82578DM Gigabit Network Connection                                          | 2        | 1.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 1.96%   |
| VIA VT6105/VT6106S [Rhine-III]                                                    | 1        | 0.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1        | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 1        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                           | 1        | 0.98%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                   | 1        | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 0.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 1        | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 1        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 1        | 0.98%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 1        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 0.98%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 0.98%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 0.98%   |
| Nvidia MCP77 Ethernet                                                             | 1        | 0.98%   |
| Nvidia MCP61 Ethernet                                                             | 1        | 0.98%   |
| Nvidia MCP55 Ethernet                                                             | 1        | 0.98%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 0.98%   |
| Intel Wireless-AC 9260                                                            | 1        | 0.98%   |
| Intel Wireless 8260                                                               | 1        | 0.98%   |
| Intel Wireless 7260                                                               | 1        | 0.98%   |
| Intel Ethernet Connection I217-V                                                  | 1        | 0.98%   |
| Intel Ethernet Connection I217-LM                                                 | 1        | 0.98%   |
| Intel Ethernet Connection (2) I218-V                                              | 1        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 1        | 0.98%   |
| Intel 82566DC Gigabit Network Connection                                          | 1        | 0.98%   |
| Intel 82562V-2 10/100 Network Connection                                          | 1        | 0.98%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                            | 1        | 0.98%   |
| Huawei JNY-LX1                                                                    | 1        | 0.98%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 0.98%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1        | 0.98%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                           | 1        | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                   | 1        | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                        | 1        | 0.98%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 1        | 0.98%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller               | 1        | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 30.56%  |
| Intel                           | 6        | 16.67%  |
| Qualcomm Atheros                | 5        | 13.89%  |
| TP-Link                         | 4        | 11.11%  |
| Broadcom                        | 4        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| Microsoft                       | 1        | 2.78%   |
| D-Link System                   | 1        | 2.78%   |
| D-Link                          | 1        | 2.78%   |
| BUFFALO                         | 1        | 2.78%   |
| Broadcom Limited                | 1        | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 3        | 8.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 5.41%   |
| Realtek 802.11ac NIC                                                              | 2        | 5.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 2        | 5.41%   |
| Intel Wi-Fi 6 AX200                                                               | 2        | 5.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 5.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1        | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 2.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                           | 1        | 2.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                   | 1        | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 2.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 2.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 1        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 2.7%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 1        | 2.7%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 2.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 2.7%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 2.7%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 2.7%    |
| Intel Wireless-AC 9260                                                            | 1        | 2.7%    |
| Intel Wireless 8260                                                               | 1        | 2.7%    |
| Intel Wireless 7260                                                               | 1        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 2.7%    |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 2.7%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1        | 2.7%    |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                           | 1        | 2.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                        | 1        | 2.7%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 1        | 2.7%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller               | 1        | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 34       | 53.97%  |
| Intel                 | 20       | 31.75%  |
| Nvidia                | 3        | 4.76%   |
| Qualcomm Atheros      | 2        | 3.17%   |
| VIA Technologies      | 1        | 1.59%   |
| Samsung Electronics   | 1        | 1.59%   |
| Huawei Technologies   | 1        | 1.59%   |
| Broadcom              | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 47.69%  |
| Intel I211 Gigabit Network Connection                             | 4        | 6.15%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 6.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.08%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 3.08%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 1.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.54%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.54%   |
| Nvidia MCP55 Ethernet                                             | 1        | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.54%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.54%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.54%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.54%   |
| Huawei JNY-LX1                                                    | 1        | 1.54%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 63.83%  |
| WiFi     | 34       | 36.17%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 66.67%  |
| WiFi     | 26       | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 69.84%  |
| 2     | 13       | 20.63%  |
| 3     | 4        | 6.35%   |
| 4     | 1        | 1.59%   |
| 0     | 1        | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 87.1%   |
| Yes  | 8        | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 9        | 42.86%  |
| Intel                   | 6        | 28.57%  |
| Realtek Semiconductor   | 2        | 9.52%   |
| ASUSTek Computer        | 2        | 9.52%   |
| IMC Networks            | 1        | 4.76%   |
| Apple                   | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 9        | 42.86%  |
| Intel Bluetooth wireless interface                    | 2        | 9.52%   |
| Intel AX200 Bluetooth                                 | 2        | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 4.76%   |
| Realtek Bluetooth Radio                               | 1        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 4.76%   |
| IMC Networks BCM20702A0                               | 1        | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.76%   |
| Apple Bluetooth USB Host Controller                   | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 41       | 39.42%  |
| AMD                    | 29       | 27.88%  |
| Nvidia                 | 21       | 20.19%  |
| C-Media Electronics    | 5        | 4.81%   |
| JMTek                  | 3        | 2.88%   |
| Generalplus Technology | 2        | 1.92%   |
| Texas Instruments      | 1        | 0.96%   |
| Hewlett-Packard        | 1        | 0.96%   |
| Astro Gaming           | 1        | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10       | 8.33%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5        | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5        | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                            | 5        | 4.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 4.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 3.33%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 2.5%    |
| JMTek USB PnP Audio Device                                                        | 3        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2.5%    |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.5%    |
| AMD FCH Azalia Controller                                                         | 3        | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.67%   |
| Generalplus Technology USB Audio Device                                           | 2        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2        | 1.67%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.83%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.83%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia MCP55 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia GM200 High Definition Audio                                                | 1        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 0.83%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.83%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1        | 0.83%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 0.83%   |
| Hewlett-Packard Premium Digital Headset                                           | 1        | 0.83%   |
| C-Media Electronics USB Modi Device                                               | 1        | 0.83%   |
| C-Media Electronics USB Audio Device                                              | 1        | 0.83%   |
| C-Media Electronics CM106 Like Sound Device                                       | 1        | 0.83%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 0.83%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 0.83%   |
| Astro Gaming Astro A20                                                            | 1        | 0.83%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1        | 0.83%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                            | 1        | 0.83%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 1        | 0.83%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 1        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                          | 1        | 0.83%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 1        | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 33.33%  |
| Unknown             | 4        | 13.33%  |
| Crucial             | 4        | 13.33%  |
| SK Hynix            | 3        | 10%     |
| Patriot             | 2        | 6.67%   |
| Corsair             | 2        | 6.67%   |
| Samsung Electronics | 1        | 3.33%   |
| Ramaxel Technology  | 1        | 3.33%   |
| Nanya Technology    | 1        | 3.33%   |
| Micron Technology   | 1        | 3.33%   |
| G.Skill             | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 6.25%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1        | 3.13%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 3.13%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 3.13%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 3.13%   |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s      | 1        | 3.13%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 3.13%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s   | 1        | 3.13%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s       | 1        | 3.13%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s  | 1        | 3.13%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s           | 1        | 3.13%   |
| Patriot RAM PSD22G8002 2GB DIMM DDR2 800MT/s              | 1        | 3.13%   |
| Nanya RAM Module 4GB FB-DIMM DDR2 667MT/s                 | 1        | 3.13%   |
| Micron RAM 16JTF25664AZ-1G4F 2GB DIMM DDR3 1333MT/s       | 1        | 3.13%   |
| Kingston RAM Module 4GB FB-DIMM DDR2 667MT/s              | 1        | 3.13%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1        | 3.13%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.13%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 3.13%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 3.13%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 3.13%   |
| Kingston RAM HP497157-B88-ELDW 2048MB DIMM DDR3 1333MT/s  | 1        | 3.13%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 3.13%   |
| G.Skill RAM F3-12800CL9-4GBRL 4096MB DIMM DDR3 1600MT/s   | 1        | 3.13%   |
| Crucial RAM CT51264AA667.M16FC 4GB DIMM DDR2 667MT/s      | 1        | 3.13%   |
| Crucial RAM CT12864BA1339A.C8F 1024MB DIMM DDR3 667MT/s   | 1        | 3.13%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8192MB DIMM DDR4 2400MT/s | 1        | 3.13%   |
| Crucial RAM BLS16G4D240FSC.16FBD 16GB DIMM DDR4 2400MT/s  | 1        | 3.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 1        | 3.13%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s     | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 39.13%  |
| DDR4    | 7        | 30.43%  |
| DDR2    | 5        | 21.74%  |
| Unknown | 2        | 8.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 21       | 91.3%   |
| SODIMM  | 1        | 4.35%   |
| FB-DIMM | 1        | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 10       | 35.71%  |
| 8192  | 8        | 28.57%  |
| 2048  | 6        | 21.43%  |
| 16384 | 2        | 7.14%   |
| 1024  | 2        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 6        | 22.22%  |
| 667   | 4        | 14.81%  |
| 3466  | 2        | 7.41%   |
| 2400  | 2        | 7.41%   |
| 1600  | 2        | 7.41%   |
| 800   | 2        | 7.41%   |
| 3600  | 1        | 3.7%    |
| 3334  | 1        | 3.7%    |
| 2934  | 1        | 3.7%    |
| 2933  | 1        | 3.7%    |
| 2133  | 1        | 3.7%    |
| 1867  | 1        | 3.7%    |
| 1866  | 1        | 3.7%    |
| 1800  | 1        | 3.7%    |
| 1639  | 1        | 3.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 5        | 71.43%  |
| Canon              | 1        | 14.29%  |
| Brother Industries | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Printing Support         | 1        | 14.29%  |
| HP LaserJet Pro M201dw      | 1        | 14.29%  |
| HP LaserJet 1320            | 1        | 14.29%  |
| HP Deskjet 2050 J510        | 1        | 14.29%  |
| HP Deskjet 1000 J110 series | 1        | 14.29%  |
| Canon TR8500 series         | 1        | 14.29%  |
| Brother MFC-T910DW          | 1        | 14.29%  |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 5        | 33.33%  |
| Z-Star Microelectronics     | 1        | 6.67%   |
| Samsung Electronics         | 1        | 6.67%   |
| Microsoft                   | 1        | 6.67%   |
| Microdia                    | 1        | 6.67%   |
| LG Electronics              | 1        | 6.67%   |
| KYE Systems (Mouse Systems) | 1        | 6.67%   |
| Generalplus Technology      | 1        | 6.67%   |
| Cubeternet                  | 1        | 6.67%   |
| Chicony Electronics         | 1        | 6.67%   |
| Apple                       | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 4        | 26.67%  |
| Z-Star Venus USB2.0 Camera                            | 1        | 6.67%   |
| Samsung Galaxy A5 (MTP)                               | 1        | 6.67%   |
| Microsoft LifeCam VX-2000                             | 1        | 6.67%   |
| Microdia Sonix USB 2.0 Camera                         | 1        | 6.67%   |
| Logitech Webcam C270                                  | 1        | 6.67%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 6.67%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 1        | 6.67%   |
| Generalplus GENERAL WEBCAM                            | 1        | 6.67%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 1        | 6.67%   |
| Chicony USB2.0 UVC VGA                                | 1        | 6.67%   |
| Apple iPhone 4                                        | 1        | 6.67%   |

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
| 0     | 56       | 87.5%   |
| 1     | 8        | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 2        | 25%     |
| Graphics card | 2        | 25%     |
| Camera        | 2        | 25%     |
| Network       | 1        | 12.5%   |
| Card reader   | 1        | 12.5%   |

