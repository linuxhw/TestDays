Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP       | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo   | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek  | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer     | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung  | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung  | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek  | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo   | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell     | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell     | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo   | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek  | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP       | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo   | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo   | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer     | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple    | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell     | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek  | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek  | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell     | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell     | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo   | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek  | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo   | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell     | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI      | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI      | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell     | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek  | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek  | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell     | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell     | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP       | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP       | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu  | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu  | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell     | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu  | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock   | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP       | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP       | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP       | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock   | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP       | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP       | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer    | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar  | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar  | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell     | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell     | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer     | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek  | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek  | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek  | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek  | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo   | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo   | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo   | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta   | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo   | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell     | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta   | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo   | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo   | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo   | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek  | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek  | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell     | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple    | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer     | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.8.0-53-generic  | 13        | 22.03%  |
| 5.8.0-50-generic  | 12        | 20.34%  |
| 5.8.0-55-generic  | 10        | 16.95%  |
| 5.8.0-59-generic  | 8         | 13.56%  |
| 5.11.0-25-generic | 6         | 10.17%  |
| 5.8.0-63-generic  | 4         | 6.78%   |
| 5.8.0-49-generic  | 4         | 6.78%   |
| 5.8.0-45-generic  | 1         | 1.69%   |
| 5.4.0-42-generic  | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 51        | 87.93%  |
| 5.11.0  | 6         | 10.34%  |
| 5.4.0   | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 51        | 87.93%  |
| 5.11    | 6         | 10.34%  |
| 5.4     | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 57        | 98.28%  |
| Cinnamon | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 56        | 96.55%  |
| Wayland | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 87.93%  |
| GDM     | 6         | 10.34%  |
| TDM     | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 20        | 34.48%  |
| de_DE | 6         | 10.34%  |
| pt_BR | 5         | 8.62%   |
| en_IN | 5         | 8.62%   |
| nl_NL | 3         | 5.17%   |
| pl_PL | 2         | 3.45%   |
| hu_HU | 2         | 3.45%   |
| en_GB | 2         | 3.45%   |
| zh_TW | 1         | 1.72%   |
| ru_UA | 1         | 1.72%   |
| ru_RU | 1         | 1.72%   |
| nl_BE | 1         | 1.72%   |
| it_IT | 1         | 1.72%   |
| fr_FR | 1         | 1.72%   |
| es_PE | 1         | 1.72%   |
| es_MX | 1         | 1.72%   |
| es_ES | 1         | 1.72%   |
| es_CL | 1         | 1.72%   |
| en_ZA | 1         | 1.72%   |
| en_PH | 1         | 1.72%   |
| en_CA | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 61.02%  |
| BIOS | 23        | 38.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 94.83%  |
| Overlay | 1         | 1.72%   |
| Ext3    | 1         | 1.72%   |
| Btrfs   | 1         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 87.93%  |
| GPT     | 6         | 10.34%  |
| MBR     | 1         | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 98.28%  |
| Yes       | 1         | 1.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 89.66%  |
| Yes       | 6         | 10.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 12        | 20.69%  |
| Lenovo              | 11        | 18.97%  |
| Dell                | 9         | 15.52%  |
| Hewlett-Packard     | 7         | 12.07%  |
| Gigabyte Technology | 5         | 8.62%   |
| Acer                | 4         | 6.9%    |
| Apple               | 2         | 3.45%   |
| Samsung Electronics | 1         | 1.72%   |
| Razer               | 1         | 1.72%   |
| Quanta              | 1         | 1.72%   |
| Pegatron            | 1         | 1.72%   |
| MSI                 | 1         | 1.72%   |
| Fujitsu             | 1         | 1.72%   |
| Biostar             | 1         | 1.72%   |
| ASRock              | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Dell OptiPlex 990                       | 2         | 3.45%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.72%   |
| Razer Book 13 - RZ09-0357               | 1         | 1.72%   |
| Quanta CA27                             | 1         | 1.72%   |
| Pegatron NE502AV-ABA a6750t             | 1         | 1.72%   |
| MSI Pro 3515 Series                     | 1         | 1.72%   |
| Lenovo Yoga C740-15IML 81TD             | 1         | 1.72%   |
| Lenovo Yoga 730-13IWL 81JR              | 1         | 1.72%   |
| Lenovo Yoga 330-11IGM 81A6              | 1         | 1.72%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00     | 1         | 1.72%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA    | 1         | 1.72%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1         | 1.72%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1         | 1.72%   |
| Lenovo IdeaPad Y570 0862                | 1         | 1.72%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 1.72%   |
| Lenovo IdeaPad 100-15IBD 80QQ           | 1         | 1.72%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1         | 1.72%   |
| HP Z1 Entry Tower G5                    | 1         | 1.72%   |
| HP ProBook 650 G2                       | 1         | 1.72%   |
| HP ProBook 450 G2                       | 1         | 1.72%   |
| HP ENVY x360 Convertible 15m-ee0xxx     | 1         | 1.72%   |
| HP 290 G2 MT Business PC                | 1         | 1.72%   |
| HP 15                                   | 1         | 1.72%   |
| Gigabyte Komputer OPTIMUS               | 1         | 1.72%   |
| Gigabyte H61M-USB3-B3                   | 1         | 1.72%   |
| Gigabyte B85-HD3                        | 1         | 1.72%   |
| Gigabyte B550M H                        | 1         | 1.72%   |
| Gigabyte B450 AORUS ELITE               | 1         | 1.72%   |
| Fujitsu LIFEBOOK AH532                  | 1         | 1.72%   |
| Dell XPS L501X                          | 1         | 1.72%   |
| Dell XPS 13 9370                        | 1         | 1.72%   |
| Dell Vostro 5490                        | 1         | 1.72%   |
| Dell Inspiron 7537                      | 1         | 1.72%   |
| Dell Inspiron 3582                      | 1         | 1.72%   |
| Dell Inspiron 3576                      | 1         | 1.72%   |
| Dell G3 3579                            | 1         | 1.72%   |
| Biostar A320MH                          | 1         | 1.72%   |
| ASUS X406UAR                            | 1         | 1.72%   |
| ASUS UNLOCK INSTALL                     | 1         | 1.72%   |
| ASUS TUF Gaming FX505DT_FX505DT         | 1         | 1.72%   |
| ASUS PRIME X570-PRO                     | 1         | 1.72%   |
| ASUS PRIME X570-P                       | 1         | 1.72%   |
| ASUS PRIME B450M-GAMING/BR              | 1         | 1.72%   |
| ASUS P8H61-M LE                         | 1         | 1.72%   |
| ASUS P5K                                | 1         | 1.72%   |
| ASUS M5A97 LE R2.0                      | 1         | 1.72%   |
| ASUS M5A78L-M/USB3                      | 1         | 1.72%   |
| ASUS M4A88TD-V EVO/USB3                 | 1         | 1.72%   |
| ASUS All Series                         | 1         | 1.72%   |
| ASRock 990FX Extreme6                   | 1         | 1.72%   |
| Apple iMac17,1                          | 1         | 1.72%   |
| Apple iMac14,1                          | 1         | 1.72%   |
| Acer Swift SF313-51                     | 1         | 1.72%   |
| Acer Aspire XC-605G                     | 1         | 1.72%   |
| Acer Aspire E5-551G                     | 1         | 1.72%   |
| Acer Aspire E1-571                      | 1         | 1.72%   |
| Unknown                                 | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo Yoga           | 3         | 5.17%   |
| Lenovo IdeaPad        | 3         | 5.17%   |
| Dell Inspiron         | 3         | 5.17%   |
| ASUS PRIME            | 3         | 5.17%   |
| Acer Aspire           | 3         | 5.17%   |
| Lenovo ThinkPad       | 2         | 3.45%   |
| Lenovo ThinkCentre    | 2         | 3.45%   |
| HP ProBook            | 2         | 3.45%   |
| Dell XPS              | 2         | 3.45%   |
| Dell OptiPlex         | 2         | 3.45%   |
| Samsung 350V5C        | 1         | 1.72%   |
| Razer Book            | 1         | 1.72%   |
| Quanta CA27           | 1         | 1.72%   |
| Pegatron NE502AV-ABA  | 1         | 1.72%   |
| MSI Pro               | 1         | 1.72%   |
| Lenovo IdeaCentre     | 1         | 1.72%   |
| HP Z1                 | 1         | 1.72%   |
| HP ENVY               | 1         | 1.72%   |
| HP 290                | 1         | 1.72%   |
| HP 15                 | 1         | 1.72%   |
| Gigabyte Komputer     | 1         | 1.72%   |
| Gigabyte H61M-USB3-B3 | 1         | 1.72%   |
| Gigabyte B85-HD3      | 1         | 1.72%   |
| Gigabyte B550M        | 1         | 1.72%   |
| Gigabyte B450         | 1         | 1.72%   |
| Fujitsu LIFEBOOK      | 1         | 1.72%   |
| Dell Vostro           | 1         | 1.72%   |
| Dell G3               | 1         | 1.72%   |
| Biostar A320MH        | 1         | 1.72%   |
| ASUS X406UAR          | 1         | 1.72%   |
| ASUS UNLOCK           | 1         | 1.72%   |
| ASUS TUF              | 1         | 1.72%   |
| ASUS P8H61-M          | 1         | 1.72%   |
| ASUS P5K              | 1         | 1.72%   |
| ASUS M5A97            | 1         | 1.72%   |
| ASUS M5A78L-M         | 1         | 1.72%   |
| ASUS M4A88TD-V        | 1         | 1.72%   |
| ASUS All              | 1         | 1.72%   |
| ASRock 990FX          | 1         | 1.72%   |
| Apple iMac17          | 1         | 1.72%   |
| Apple iMac14          | 1         | 1.72%   |
| Acer Swift            | 1         | 1.72%   |
| Unknown               | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 13        | 22.41%  |
| 2019 | 10        | 17.24%  |
| 2021 | 8         | 13.79%  |
| 2018 | 5         | 8.62%   |
| 2014 | 4         | 6.9%    |
| 2013 | 4         | 6.9%    |
| 2015 | 3         | 5.17%   |
| 2011 | 3         | 5.17%   |
| 2016 | 2         | 3.45%   |
| 2008 | 2         | 3.45%   |
| 2012 | 1         | 1.72%   |
| 2010 | 1         | 1.72%   |
| 2009 | 1         | 1.72%   |
| 2007 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 27        | 46.55%  |
| Notebook    | 24        | 41.38%  |
| Convertible | 4         | 6.9%    |
| All in one  | 3         | 5.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 87.93%  |
| Enabled  | 7         | 12.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 17        | 28.81%  |
| 16.01-24.0 | 14        | 23.73%  |
| 4.01-8.0   | 13        | 22.03%  |
| 3.01-4.0   | 10        | 16.95%  |
| 32.01-64.0 | 3         | 5.08%   |
| 1.01-2.0   | 2         | 3.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 27        | 45%     |
| 2.01-3.0 | 20        | 33.33%  |
| 3.01-4.0 | 7         | 11.67%  |
| 4.01-8.0 | 4         | 6.67%   |
| 0.51-1.0 | 2         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 63.79%  |
| 2      | 12        | 20.69%  |
| 3      | 4         | 6.9%    |
| 4      | 3         | 5.17%   |
| 5      | 1         | 1.72%   |
| 0      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 54.24%  |
| No        | 27        | 45.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 86.44%  |
| No        | 8         | 13.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 68.97%  |
| No        | 18        | 31.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 58.62%  |
| No        | 24        | 41.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 27.59%  |
| Germany      | 6         | 10.34%  |
| India        | 5         | 8.62%   |
| Brazil       | 5         | 8.62%   |
| Netherlands  | 3         | 5.17%   |
| UK           | 2         | 3.45%   |
| Mexico       | 2         | 3.45%   |
| Hungary      | 2         | 3.45%   |
| Ukraine      | 1         | 1.72%   |
| Taiwan       | 1         | 1.72%   |
| Spain        | 1         | 1.72%   |
| South Africa | 1         | 1.72%   |
| Romania      | 1         | 1.72%   |
| Poland       | 1         | 1.72%   |
| Philippines  | 1         | 1.72%   |
| Peru         | 1         | 1.72%   |
| Madagascar   | 1         | 1.72%   |
| Italy        | 1         | 1.72%   |
| Denmark      | 1         | 1.72%   |
| Chile        | 1         | 1.72%   |
| Canada       | 1         | 1.72%   |
| Belgium      | 1         | 1.72%   |
| Azerbaijan   | 1         | 1.72%   |
| Austria      | 1         | 1.72%   |
| Australia    | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Hyderabad              | 2         | 3.45%   |
| Xalapa                 | 1         | 1.72%   |
| Vienna                 | 1         | 1.72%   |
| Vespasiano             | 1         | 1.72%   |
| Vancouver              | 1         | 1.72%   |
| Trujillo               | 1         | 1.72%   |
| São Bernardo do Campo | 1         | 1.72%   |
| Sutton Coldfield       | 1         | 1.72%   |
| Stadskanaal            | 1         | 1.72%   |
| San Francisco          | 1         | 1.72%   |
| Sacramento             | 1         | 1.72%   |
| Rome                   | 1         | 1.72%   |
| Rio de Janeiro         | 1         | 1.72%   |
| Rancagua               | 1         | 1.72%   |
| Quezon City            | 1         | 1.72%   |
| Pretoria               | 1         | 1.72%   |
| Pascoag                | 1         | 1.72%   |
| Palm Coast             | 1         | 1.72%   |
| Oscoda                 | 1         | 1.72%   |
| Ohmbach                | 1         | 1.72%   |
| Oak Creek              | 1         | 1.72%   |
| Nyiregyhaza            | 1         | 1.72%   |
| New Taipei             | 1         | 1.72%   |
| Mérida                | 1         | 1.72%   |
| Monheim am Rhein       | 1         | 1.72%   |
| Mentor                 | 1         | 1.72%   |
| Melbourne              | 1         | 1.72%   |
| Ludwigsburg            | 1         | 1.72%   |
| Littleton              | 1         | 1.72%   |
| Kyiv                   | 1         | 1.72%   |
| Kolkata                | 1         | 1.72%   |
| Idaho Falls            | 1         | 1.72%   |
| Hamburg                | 1         | 1.72%   |
| Ghent                  | 1         | 1.72%   |
| Gdynia                 | 1         | 1.72%   |
| Galgamacsa             | 1         | 1.72%   |
| Fortaleza              | 1         | 1.72%   |
| Fort Worth             | 1         | 1.72%   |
| Eugene                 | 1         | 1.72%   |
| Ernakulam              | 1         | 1.72%   |
| Dudley                 | 1         | 1.72%   |
| Dortmund               | 1         | 1.72%   |
| Copenhagen             | 1         | 1.72%   |
| Contagem               | 1         | 1.72%   |
| Charlottesville        | 1         | 1.72%   |
| Charlotte              | 1         | 1.72%   |
| Bedum                  | 1         | 1.72%   |
| Beacon                 | 1         | 1.72%   |
| Baltimore              | 1         | 1.72%   |
| Baku                   | 1         | 1.72%   |
| Bad Mergentheim        | 1         | 1.72%   |
| Arlington              | 1         | 1.72%   |
| Arad                   | 1         | 1.72%   |
| Antananarivo           | 1         | 1.72%   |
| Amsterdam              | 1         | 1.72%   |
| Aldaia                 | 1         | 1.72%   |
| Ahmedabad              | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 15        | 20     | 18.75%  |
| Seagate                   | 11        | 14     | 13.75%  |
| Samsung Electronics       | 11        | 14     | 13.75%  |
| Kingston                  | 7         | 10     | 8.75%   |
| SanDisk                   | 6         | 8      | 7.5%    |
| Toshiba                   | 5         | 5      | 6.25%   |
| Unknown                   | 4         | 5      | 5%      |
| Phison                    | 3         | 3      | 3.75%   |
| Intel                     | 3         | 3      | 3.75%   |
| Apple                     | 2         | 2      | 2.5%    |
| A-DATA Technology         | 2         | 2      | 2.5%    |
| USB30                     | 1         | 2      | 1.25%   |
| Silicon Motion            | 1         | 3      | 1.25%   |
| Micron/Crucial Technology | 1         | 1      | 1.25%   |
| Maxtor                    | 1         | 1      | 1.25%   |
| Lexar                     | 1         | 1      | 1.25%   |
| KIOXIA                    | 1         | 1      | 1.25%   |
| KingFast                  | 1         | 1      | 1.25%   |
| JMicron                   | 1         | 1      | 1.25%   |
| HGST                      | 1         | 1      | 1.25%   |
| Hewlett-Packard           | 1         | 1      | 1.25%   |
| Crucial                   | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 2.3%    |
| Unknown SD/MMC/MS PRO 16GB              | 2         | 2.3%    |
| Phison NVMe SSD Drive 1TB               | 2         | 2.3%    |
| Kingston SA400S37240G 240GB SSD         | 2         | 2.3%    |
| WDC WDS250G2B0A-00SM50 250GB SSD        | 1         | 1.15%   |
| WDC WD5000LPVT-22G33T0 500GB            | 1         | 1.15%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 1         | 1.15%   |
| WDC WD5000AAKS-00YGA0 500GB             | 1         | 1.15%   |
| WDC WD40EZAZ-00SF3B0 4TB                | 1         | 1.15%   |
| WDC WD3200BUCT-63TWBY0 320GB            | 1         | 1.15%   |
| WDC WD30EZRX-00D8PB0 3TB                | 1         | 1.15%   |
| WDC WD20EURX-61T0FY0 2TB                | 1         | 1.15%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 1.15%   |
| WDC WD10EZEX-60M2NA0 1TB                | 1         | 1.15%   |
| WDC WD10EZEX-21M2NA0 1TB                | 1         | 1.15%   |
| WDC WD10EZEX-08M2NA0 1TB                | 1         | 1.15%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1         | 1.15%   |
| WDC WD10EURX-63FH1Y0 1TB                | 1         | 1.15%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 1.15%   |
| USB30 Disk 250GB                        | 1         | 1.15%   |
| Unknown MMC Card  32GB                  | 1         | 1.15%   |
| Unknown MMC Card  128GB                 | 1         | 1.15%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 1         | 1.15%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.15%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1.15%   |
| Toshiba HDWD110 1TB                     | 1         | 1.15%   |
| Toshiba DT01ACA300 3TB                  | 1         | 1.15%   |
| Silicon Motion NVMe SSD Drive 128GB     | 1         | 1.15%   |
| Silicon Motion NVME SSD 128GB           | 1         | 1.15%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.15%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1.15%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.15%   |
| Seagate ST4000DM004-2CV104 4TB          | 1         | 1.15%   |
| Seagate ST380811AS 80GB                 | 1         | 1.15%   |
| Seagate ST31500341AS 1TB                | 1         | 1.15%   |
| Seagate ST1000VM002-1CT162 1TB          | 1         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.15%   |
| Seagate ST1000LM010-9YH146 1TB          | 1         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.15%   |
| Seagate ST1000DM003-1CH162 1TB          | 1         | 1.15%   |
| SanDisk SSD PLUS 480GB                  | 1         | 1.15%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1.15%   |
| SanDisk SDSSDA120G 120GB                | 1         | 1.15%   |
| SanDisk SD8SN8U256G1002 256GB SSD       | 1         | 1.15%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 1.15%   |
| Sandisk NVMe SSD Drive 250GB            | 1         | 1.15%   |
| Samsung SSD 870 QVO 1TB                 | 1         | 1.15%   |
| Samsung SSD 860 EVO 500GB               | 1         | 1.15%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.15%   |
| Samsung SSD 840 EVO 250GB               | 1         | 1.15%   |
| Samsung SSD 840 EVO 120GB               | 1         | 1.15%   |
| Samsung NVMe SSD Drive 512GB            | 1         | 1.15%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 1.15%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 1.15%   |
| Samsung MZVLB512HBJQ-00A00 512GB        | 1         | 1.15%   |
| Samsung HM640JJ 640GB                   | 1         | 1.15%   |
| Samsung HD502HJ 500GB                   | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 18     | 38.89%  |
| Seagate             | 11        | 14     | 30.56%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Samsung Electronics | 3         | 3      | 8.33%   |
| Apple               | 2         | 2      | 5.56%   |
| Maxtor              | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Hewlett-Packard     | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 9      | 25%     |
| Samsung Electronics | 5         | 6      | 20.83%  |
| SanDisk             | 4         | 5      | 16.67%  |
| Toshiba             | 2         | 2      | 8.33%   |
| A-DATA Technology   | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| USB30               | 1         | 2      | 4.17%   |
| Lexar               | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 43     | 41.89%  |
| SSD     | 22        | 30     | 29.73%  |
| NVMe    | 15        | 20     | 20.27%  |
| Unknown | 4         | 4      | 5.41%   |
| MMC     | 2         | 3      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 73     | 69.23%  |
| NVMe | 15        | 20     | 23.08%  |
| SAS  | 3         | 4      | 4.62%   |
| MMC  | 2         | 3      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 41     | 54.55%  |
| 0.51-1.0   | 20        | 26     | 36.36%  |
| 3.01-4.0   | 2         | 2      | 3.64%   |
| 1.01-2.0   | 2         | 2      | 3.64%   |
| 2.01-3.0   | 1         | 2      | 1.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 23        | 39.66%  |
| 101-250        | 12        | 20.69%  |
| 501-1000       | 9         | 15.52%  |
| 1-20           | 4         | 6.9%    |
| More than 3000 | 2         | 3.45%   |
| 21-50          | 2         | 3.45%   |
| 2001-3000      | 2         | 3.45%   |
| 1001-2000      | 2         | 3.45%   |
| 51-100         | 2         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 46.67%  |
| 21-50          | 12        | 20%     |
| 101-250        | 7         | 11.67%  |
| 51-100         | 7         | 11.67%  |
| More than 3000 | 2         | 3.33%   |
| 251-500        | 2         | 3.33%   |
| 1001-2000      | 1         | 1.67%   |
| 501-1000       | 1         | 1.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB   | 1         | 1      | 50%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 51        | 92     | 86.44%  |
| Works    | 6         | 6      | 10.17%  |
| Malfunc  | 2         | 2      | 3.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 57.14%  |
| AMD                         | 13        | 18.57%  |
| Samsung Electronics         | 4         | 5.71%   |
| Sandisk                     | 3         | 4.29%   |
| Phison Electronics          | 3         | 4.29%   |
| VIA Technologies            | 1         | 1.43%   |
| Silicon Motion              | 1         | 1.43%   |
| Micron/Crucial Technology   | 1         | 1.43%   |
| KIOXIA                      | 1         | 1.43%   |
| Kingston Technology Company | 1         | 1.43%   |
| JMicron Technology          | 1         | 1.43%   |
| ASMedia Technology          | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 8.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 5.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 3.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 3.8%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 2.53%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.53%   |
| Intel SSD 660P Series                                                                   | 2         | 2.53%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 2.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 2.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2.53%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 2.53%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 1.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 1.27%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 1.27%   |
| Samsung NVMe Controller                                                                 | 1         | 1.27%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.27%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 1.27%   |
| KIOXIA Non-Volatile memory controller                                                   | 1         | 1.27%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 1.27%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 1.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 1.27%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1         | 1.27%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.27%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1         | 1.27%   |
| AMD FCH SATA Controller D                                                               | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 43        | 61.43%  |
| NVMe | 15        | 21.43%  |
| IDE  | 8         | 11.43%  |
| RAID | 4         | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 74.14%  |
| AMD    | 15        | 25.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 5.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 3.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.45%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 3.45%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 3.45%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.45%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 1.72%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 1.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.72%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 1.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.72%   |
| Intel Core i5-4570R CPU @ 2.70GHz             | 1         | 1.72%   |
| Intel Core i5-4430 CPU @ 3.00GHz              | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i5-2500S CPU @ 2.70GHz             | 1         | 1.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 1.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 1.72%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1         | 1.72%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.72%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 1.72%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.72%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 1.72%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 1.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 1.72%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 1.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 1         | 1.72%   |
| AMD Phenom II X4 965 Processor                | 1         | 1.72%   |
| AMD FX-9590 Eight-Core Processor              | 1         | 1.72%   |
| AMD FX-8320E Eight-Core Processor             | 1         | 1.72%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 1.72%   |
| AMD FX-6350 Six-Core Processor                | 1         | 1.72%   |
| AMD A6-5400K APU with Radeon HD Graphics      | 1         | 1.72%   |
| AMD A6-5400B APU with Radeon HD Graphics      | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 29.31%  |
| Intel Core i7           | 9         | 15.52%  |
| Intel Core i3           | 8         | 13.79%  |
| AMD Ryzen 7             | 4         | 6.9%    |
| AMD FX                  | 4         | 6.9%    |
| Intel Celeron           | 3         | 5.17%   |
| Other                   | 2         | 3.45%   |
| AMD Ryzen 5             | 2         | 3.45%   |
| AMD A6                  | 2         | 3.45%   |
| Intel Pentium Dual-Core | 1         | 1.72%   |
| Intel Pentium Dual      | 1         | 1.72%   |
| Intel Core 2 Quad       | 1         | 1.72%   |
| Intel Core 2 Duo        | 1         | 1.72%   |
| AMD Ryzen 9             | 1         | 1.72%   |
| AMD Ryzen 3             | 1         | 1.72%   |
| AMD Phenom II X4        | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 31        | 53.45%  |
| 2      | 18        | 31.03%  |
| 8      | 4         | 6.9%    |
| 1      | 2         | 3.45%   |
| 12     | 1         | 1.72%   |
| 6      | 1         | 1.72%   |
| 3      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 67.24%  |
| 1      | 19        | 32.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ea    | 5         | 8.47%   |
| 0x206a7    | 5         | 8.47%   |
| Unknown    | 5         | 8.47%   |
| 0x306c3    | 4         | 6.78%   |
| 0x306a9    | 4         | 6.78%   |
| 0x06000852 | 3         | 5.08%   |
| 0x906eb    | 2         | 3.39%   |
| 0x806ec    | 2         | 3.39%   |
| 0x806c1    | 2         | 3.39%   |
| 0x706a1    | 2         | 3.39%   |
| 0x6fb      | 2         | 3.39%   |
| 0x40651    | 2         | 3.39%   |
| 0x306d4    | 2         | 3.39%   |
| 0x08701021 | 2         | 3.39%   |
| 0x0800820d | 2         | 3.39%   |
| 0x06001119 | 2         | 3.39%   |
| 0x906ea    | 1         | 1.69%   |
| 0x806eb    | 1         | 1.69%   |
| 0x6fd      | 1         | 1.69%   |
| 0x506e3    | 1         | 1.69%   |
| 0x40661    | 1         | 1.69%   |
| 0x30678    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08701013 | 1         | 1.69%   |
| 0x08600106 | 1         | 1.69%   |
| 0x08108102 | 1         | 1.69%   |
| 0x08101016 | 1         | 1.69%   |
| 0x06003106 | 1         | 1.69%   |
| 0x010000c8 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 20.69%  |
| Haswell       | 7         | 12.07%  |
| SandyBridge   | 6         | 10.34%  |
| Piledriver    | 5         | 8.62%   |
| Zen 2         | 4         | 6.9%    |
| IvyBridge     | 4         | 6.9%    |
| Zen+          | 3         | 5.17%   |
| Core          | 3         | 5.17%   |
| TigerLake     | 2         | 3.45%   |
| Skylake       | 2         | 3.45%   |
| Goldmont plus | 2         | 3.45%   |
| Broadwell     | 2         | 3.45%   |
| Zen           | 1         | 1.72%   |
| Steamroller   | 1         | 1.72%   |
| Silvermont    | 1         | 1.72%   |
| Penryn        | 1         | 1.72%   |
| Nehalem       | 1         | 1.72%   |
| K10           | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 52.17%  |
| Nvidia | 20        | 28.99%  |
| AMD    | 13        | 18.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 5         | 7.04%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 5.63%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.82%   |
| Intel HD Graphics 5500                                                      | 2         | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.82%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 2.82%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2         | 2.82%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2         | 2.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 1.41%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 1.41%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 1.41%   |
| Nvidia GK208BM [GeForce 920M]                                               | 1         | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 1.41%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 555M]                                             | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 435M]                                             | 1         | 1.41%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1         | 1.41%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.41%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                   | 1         | 1.41%   |
| Intel HD Graphics 630                                                       | 1         | 1.41%   |
| Intel Crystal Well Integrated Iris Pro Graphics 5200                        | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 1.41%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1         | 1.41%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.41%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                   | 1         | 1.41%   |
| AMD Saturn XT [FirePro M6100]                                               | 1         | 1.41%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1         | 1.41%   |
| AMD RS780L [Radeon 3000]                                                    | 1         | 1.41%   |
| AMD Renoir                                                                  | 1         | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 1.41%   |
| AMD Picasso                                                                 | 1         | 1.41%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 1.41%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                          | 1         | 1.41%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                | 1         | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 44.07%  |
| 1 x Nvidia     | 12        | 20.34%  |
| 1 x AMD        | 9         | 15.25%  |
| Intel + Nvidia | 7         | 11.86%  |
| 2 x AMD        | 2         | 3.39%   |
| Intel + AMD    | 2         | 3.39%   |
| AMD + Nvidia   | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 74.14%  |
| Proprietary | 14        | 24.14%  |
| Unknown     | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 53.45%  |
| 1.01-2.0   | 10        | 17.24%  |
| 3.01-4.0   | 4         | 6.9%    |
| 0.51-1.0   | 4         | 6.9%    |
| 0.01-0.5   | 4         | 6.9%    |
| 5.01-6.0   | 3         | 5.17%   |
| 7.01-8.0   | 1         | 1.72%   |
| 2.01-3.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 13.11%  |
| Samsung Electronics | 7         | 11.48%  |
| BOE                 | 7         | 11.48%  |
| Vizio               | 3         | 4.92%   |
| Philips             | 3         | 4.92%   |
| Lenovo              | 3         | 4.92%   |
| Chimei Innolux      | 3         | 4.92%   |
| Acer                | 3         | 4.92%   |
| Sharp               | 2         | 3.28%   |
| InfoVision          | 2         | 3.28%   |
| Hewlett-Packard     | 2         | 3.28%   |
| Goldstar            | 2         | 3.28%   |
| Dell                | 2         | 3.28%   |
| Apple               | 2         | 3.28%   |
| AOC                 | 2         | 3.28%   |
| ViewSonic           | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |
| Sceptre Tech        | 1         | 1.64%   |
| PANDA               | 1         | 1.64%   |
| LG Electronics      | 1         | 1.64%   |
| LG Display          | 1         | 1.64%   |
| Gigabyte Technology | 1         | 1.64%   |
| Gateway             | 1         | 1.64%   |
| BenQ                | 1         | 1.64%   |
| AUS                 | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 3.23%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch              | 1         | 1.61%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                         | 1         | 1.61%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 1.61%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                          | 1         | 1.61%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1         | 1.61%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                | 1         | 1.61%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 1.61%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1         | 1.61%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1         | 1.61%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch   | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch  | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1         | 1.61%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch     | 1         | 1.61%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1         | 1.61%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 1.61%   |
| Philips LCD Monitor 240B 1920x1200                                     | 1         | 1.61%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 1.61%   |
| LG Electronics LCD Monitor EW224 1920x1080                             | 1         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 1         | 1.61%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch               | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 1         | 1.61%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                    | 1         | 1.61%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch           | 1         | 1.61%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch            | 1         | 1.61%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1         | 1.61%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch     | 1         | 1.61%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 1.61%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 1         | 1.61%   |
| Goldstar LCD Monitor GSM580C 1680x1050 510x290mm 23.1-inch             | 1         | 1.61%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch       | 1         | 1.61%   |
| Gateway VX930 GWY232D 1600x1200 350x262mm 17.2-inch                    | 1         | 1.61%   |
| Dell S2715H DEL40BA 1920x1080 598x336mm 27.0-inch                      | 1         | 1.61%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch       | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch        | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch        | 1         | 1.61%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE085B 1920x1080 344x194mm 15.5-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE082E 1920x1080 309x174mm 14.0-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE07DD 1920x1080 293x165mm 13.2-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                  | 1         | 1.61%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                   | 1         | 1.61%   |
| BOE LCD Monitor BOE05E9 1366x768 256x144mm 11.6-inch                   | 1         | 1.61%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 1         | 1.61%   |
| AUS LCD Monitor ASUS VP247 1920x1080                                   | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 1         | 1.61%   |
| AU Optronics LCD Monitor 1366x768                                      | 1         | 1.61%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                       | 1         | 1.61%   |
| Apple iMac APPA012 1920x1080 480x270mm 21.7-inch                       | 1         | 1.61%   |
| AOC LCD Monitor 2269W 1920x1080                                        | 1         | 1.61%   |
| AOC AG323FWG3R3 AOC3230 1920x1080 698x393mm 31.5-inch                  | 1         | 1.61%   |
| Acer LCD Monitor S271HL 1920x1080                                      | 1         | 1.61%   |
| Acer K202HQL ACR03E0 1600x900 432x240mm 19.5-inch                      | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 56.9%   |
| 1366x768 (WXGA)    | 12        | 20.69%  |
| 3840x2160 (4K)     | 4         | 6.9%    |
| 3840x2400          | 1         | 1.72%   |
| 3840x1080          | 1         | 1.72%   |
| 3440x1440          | 1         | 1.72%   |
| 1920x1200 (WUXGA)  | 1         | 1.72%   |
| 1680x1050 (WSXGA+) | 1         | 1.72%   |
| 1600x900 (HD+)     | 1         | 1.72%   |
| 1600x1200          | 1         | 1.72%   |
| 1440x900 (WXGA+)   | 1         | 1.72%   |
| 1280x800 (WXGA)    | 1         | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 26.23%  |
| Unknown | 8         | 13.11%  |
| 13      | 6         | 9.84%   |
| 31      | 4         | 6.56%   |
| 27      | 4         | 6.56%   |
| 24      | 4         | 6.56%   |
| 23      | 3         | 4.92%   |
| 21      | 3         | 4.92%   |
| 48      | 2         | 3.28%   |
| 18      | 2         | 3.28%   |
| 11      | 2         | 3.28%   |
| 46      | 1         | 1.64%   |
| 41      | 1         | 1.64%   |
| 34      | 1         | 1.64%   |
| 22      | 1         | 1.64%   |
| 19      | 1         | 1.64%   |
| 17      | 1         | 1.64%   |
| 14      | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 33.33%  |
| 501-600     | 10        | 16.67%  |
| Unknown     | 8         | 13.33%  |
| 401-500     | 7         | 11.67%  |
| 201-300     | 6         | 10%     |
| 601-700     | 4         | 6.67%   |
| 1001-1500   | 3         | 5%      |
| 701-800     | 1         | 1.67%   |
| 901-1000    | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 73.21%  |
| Unknown | 8         | 14.29%  |
| 16/10   | 4         | 7.14%   |
| 4/3     | 1         | 1.79%   |
| 32/9    | 1         | 1.79%   |
| 21/9    | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 26.23%  |
| 201-250        | 10        | 16.39%  |
| Unknown        | 8         | 13.11%  |
| 351-500        | 5         | 8.2%    |
| 71-80          | 4         | 6.56%   |
| 301-350        | 4         | 6.56%   |
| 81-90          | 3         | 4.92%   |
| 151-200        | 3         | 4.92%   |
| 501-1000       | 3         | 4.92%   |
| 51-60          | 2         | 3.28%   |
| 141-150        | 2         | 3.28%   |
| More than 1000 | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 19        | 31.15%  |
| 101-120       | 14        | 22.95%  |
| 121-160       | 13        | 21.31%  |
| Unknown       | 8         | 13.11%  |
| 161-240       | 3         | 4.92%   |
| More than 240 | 2         | 3.28%   |
| 1-50          | 2         | 3.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 89.66%  |
| 2     | 5         | 8.62%   |
| 0     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 40.66%  |
| Intel                 | 26        | 28.57%  |
| Qualcomm Atheros      | 12        | 13.19%  |
| Broadcom              | 5         | 5.49%   |
| Samsung Electronics   | 2         | 2.2%    |
| Ralink                | 2         | 2.2%    |
| TP-Link               | 1         | 1.1%    |
| Ralink Technology     | 1         | 1.1%    |
| NetGear               | 1         | 1.1%    |
| Google                | 1         | 1.1%    |
| DisplayLink           | 1         | 1.1%    |
| D-Link System         | 1         | 1.1%    |
| Broadcom Limited      | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 29.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.06%   |
| Intel Wireless 7260                                               | 3         | 3.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.04%   |
| Realtek 802.11ac NIC                                              | 2         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.04%   |
| Intel Wireless-AC 9260                                            | 2         | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 2.04%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.02%   |
| Ralink RT2600 802.11 MIMO                                         | 1         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.02%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 1.02%   |
| Intel Wireless 8260                                               | 1         | 1.02%   |
| Intel Wireless 7265                                               | 1         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.02%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.02%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.02%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.02%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.02%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.02%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.02%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.02%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 1         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 46.51%  |
| Qualcomm Atheros      | 9         | 20.93%  |
| Realtek Semiconductor | 5         | 11.63%  |
| Broadcom              | 4         | 9.3%    |
| Ralink                | 2         | 4.65%   |
| TP-Link               | 1         | 2.33%   |
| Ralink Technology     | 1         | 2.33%   |
| NetGear               | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 3         | 6.98%   |
| Intel Wireless 7260                                         | 3         | 6.98%   |
| Realtek 802.11ac NIC                                        | 2         | 4.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 2         | 4.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 4.65%   |
| Intel Wireless-AC 9260                                      | 2         | 4.65%   |
| Intel Wi-Fi 6 AX201                                         | 2         | 4.65%   |
| Intel Wi-Fi 6 AX200                                         | 2         | 4.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth             | 2         | 4.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 2         | 4.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                | 2         | 4.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1         | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 1         | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1         | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                  | 1         | 2.33%   |
| Ralink MT7601U Wireless Adapter                             | 1         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                   | 1         | 2.33%   |
| Ralink RT2600 802.11 MIMO                                   | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 1         | 2.33%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 1         | 2.33%   |
| Intel Wireless 8260                                         | 1         | 2.33%   |
| Intel Wireless 7265                                         | 1         | 2.33%   |
| Intel Centrino Wireless-N 2230                              | 1         | 2.33%   |
| Intel Centrino Wireless-N 105                               | 1         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 1         | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                 | 1         | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter          | 1         | 2.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller      | 1         | 2.33%   |
| Broadcom BCM43142 802.11b/g/n                               | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 62.96%  |
| Intel                 | 8         | 14.81%  |
| Qualcomm Atheros      | 3         | 5.56%   |
| Broadcom              | 3         | 5.56%   |
| Samsung Electronics   | 2         | 3.7%    |
| Google                | 1         | 1.85%   |
| DisplayLink           | 1         | 1.85%   |
| D-Link System         | 1         | 1.85%   |
| Broadcom Limited      | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 52.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 3.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.82%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.82%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.82%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.82%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.82%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.82%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.82%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 56.04%  |
| WiFi     | 40        | 43.96%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 58.54%  |
| WiFi     | 34        | 41.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 51.72%  |
| 2     | 27        | 46.55%  |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 66.1%   |
| Yes  | 20        | 33.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 50%     |
| Qualcomm Atheros Communications | 5         | 14.71%  |
| Lite-On Technology              | 3         | 8.82%   |
| IMC Networks                    | 2         | 5.88%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| Apple                           | 2         | 5.88%   |
| Ralink                          | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| Broadcom                        | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20.59%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.82%   |
| Lite-On Bluetooth Device                            | 2         | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 5.88%   |
| Intel AX201 Bluetooth                               | 2         | 5.88%   |
| Intel AX200 Bluetooth                               | 2         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.88%   |
| Apple Bluetooth USB Host Controller                 | 2         | 5.88%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.94%   |
| Qualcomm Atheros Bluetooth                          | 1         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.94%   |
| Lite-On BCM43142A0                                  | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.94%   |
| IMC Networks Bluetooth Device                       | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.94%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module            | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 43        | 53.75%  |
| Nvidia            | 16        | 20%     |
| AMD               | 15        | 18.75%  |
| Creative Labs     | 2         | 2.5%    |
| Texas Instruments | 1         | 1.25%   |
| Numark            | 1         | 1.25%   |
| Klipsch Audio     | 1         | 1.25%   |
| JMTek             | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 6.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 4.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.13%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.13%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.08%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 2.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 2.08%   |
| Texas Instruments PCM2901 Audio Codec                                      | 1         | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.04%   |
| Nvidia Audio device                                                        | 1         | 1.04%   |
| Numark MixTrack Pro                                                        | 1         | 1.04%   |
| Klipsch Audio Klipsch KG-200 Headphones                                    | 1         | 1.04%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.04%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.04%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 1.04%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 1.04%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.04%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1         | 1.04%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.04%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 33.33%  |
| Micron Technology   | 3         | 25%     |
| Unknown             | 2         | 16.67%  |
| Team                | 1         | 8.33%   |
| SK Hynix            | 1         | 8.33%   |
| Kingston            | 1         | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s           | 1         | 6.67%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1         | 6.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 6.67%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                | 1         | 6.67%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                | 1         | 6.67%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s         | 1         | 6.67%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 6.67%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 6.67%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s          | 1         | 6.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 6.67%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s          | 1         | 6.67%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 6.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 1         | 6.67%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 6.67%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 4         | 33.33%  |
| DDR3    | 4         | 33.33%  |
| SDRAM   | 1         | 8.33%   |
| LPDDR4  | 1         | 8.33%   |
| LPDDR3  | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 6         | 54.55%  |
| DIMM         | 3         | 27.27%  |
| Row Of Chips | 2         | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 7         | 53.85%  |
| 8192 | 4         | 30.77%  |
| 2048 | 2         | 15.38%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 4         | 33.33%  |
| 2667  | 3         | 25%     |
| 4267  | 1         | 8.33%   |
| 4199  | 1         | 8.33%   |
| 2400  | 1         | 8.33%   |
| 1867  | 1         | 8.33%   |
| 1333  | 1         | 8.33%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 6         | 19.35%  |
| Sunplus Innovation Technology          | 4         | 12.9%   |
| Chicony Electronics                    | 4         | 12.9%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 12.9%   |
| Microdia                               | 3         | 9.68%   |
| Acer                                   | 3         | 9.68%   |
| Realtek Semiconductor                  | 2         | 6.45%   |
| Apple                                  | 2         | 6.45%   |
| Quanta                                 | 1         | 3.23%   |
| Microsoft                              | 1         | 3.23%   |
| Jieli Technology                       | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                         | 2         | 6.45%   |
| Realtek Integrated_Webcam_HD                         | 2         | 6.45%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 6.45%   |
| IMC Networks Integrated Camera                       | 2         | 6.45%   |
| Apple FaceTime HD Camera (Built-in)                  | 2         | 6.45%   |
| Acer Integrated Camera                               | 2         | 6.45%   |
| Sunplus HD WebCam                                    | 1         | 3.23%   |
| Sunplus HD User Facing                               | 1         | 3.23%   |
| Quanta Laptop_Integrated_Webcam_2HDM                 | 1         | 3.23%   |
| Microsoft MicrosoftÂ LifeCam Cinema                 | 1         | 3.23%   |
| Microdia WebCam SC-13HDL12639P                       | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                        | 1         | 3.23%   |
| Microdia Integrated HD Webcam                        | 1         | 3.23%   |
| Jieli USB PHY 2.0                                    | 1         | 3.23%   |
| IMC Networks Lenovo EasyCamera                       | 1         | 3.23%   |
| IMC Networks EasyCamera                              | 1         | 3.23%   |
| Chicony HP Wide Vision HD Camera                     | 1         | 3.23%   |
| Chicony HD WebCam                                    | 1         | 3.23%   |
| Chicony FJ Camera                                    | 1         | 3.23%   |
| Chicony EasyCamera                                   | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam        | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) USB HD webcam | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 1         | 3.23%   |
| Acer Lenovo EasyCamera                               | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader          | 2         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 25%     |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 46        | 79.31%  |
| 1     | 9         | 15.52%  |
| 2     | 3         | 5.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 6         | 42.86%  |
| Fingerprint reader | 4         | 28.57%  |
| Graphics card      | 3         | 21.43%  |
| Bluetooth          | 1         | 7.14%   |

