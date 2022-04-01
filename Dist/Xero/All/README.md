Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 69

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell     | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP       | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI      | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell     | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek  | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI   | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell     | Latitude 7480               | Notebook    | [1083fec58a](https://linux-hardware.org/?probe=1083fec58a) | Mar 19, 2022 |
| Dell     | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple    | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP       | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo   | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo   | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI      | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell     | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo   | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell     | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo   | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek  | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer     | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell     | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo   | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP       | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo   | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP       | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP       | 2179                        | All in one  | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell     | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP       | 2179                        | All in one  | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP       | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek  | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [3e4f21099d](https://linux-hardware.org/?probe=3e4f21099d) | Dec 17, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI      | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo   | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP       | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo   | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell     | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock   | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [203afc45fd](https://linux-hardware.org/?probe=203afc45fd) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 44        | 84.62%  |
| Xero         | 8         | 15.38%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.15-arch1-1              | 6         | 10.34%  |
| 5.16.2-arch1-1               | 3         | 5.17%   |
| 5.16.1-arch1-1               | 3         | 5.17%   |
| 5.14.14-arch1-1              | 3         | 5.17%   |
| 5.16.8-arch1-1               | 2         | 3.45%   |
| 5.16.16-arch1-1              | 2         | 3.45%   |
| 5.16.13-arch1-1              | 2         | 3.45%   |
| 5.16.12-arch1-1              | 2         | 3.45%   |
| 5.14.8-zen1-1-zen            | 2         | 3.45%   |
| 5.17.1-arch1-1               | 1         | 1.72%   |
| 5.16.16-zen1-1-zen           | 1         | 1.72%   |
| 5.16.14-arch1-1              | 1         | 1.72%   |
| 5.16.10-arch1-1              | 1         | 1.72%   |
| 5.15.9-AMD                   | 1         | 1.72%   |
| 5.15.8-zen1-1-zen            | 1         | 1.72%   |
| 5.15.4-arch1-1               | 1         | 1.72%   |
| 5.15.3-zen1-1-zen            | 1         | 1.72%   |
| 5.15.26-1-lts                | 1         | 1.72%   |
| 5.15.13-arch1-1              | 1         | 1.72%   |
| 5.15.13-AMD                  | 1         | 1.72%   |
| 5.15.12-zen1-1-zen           | 1         | 1.72%   |
| 5.15.12-arch1-1-surface      | 1         | 1.72%   |
| 5.15.12-arch1-1              | 1         | 1.72%   |
| 5.15.11-arch2-1-surface      | 1         | 1.72%   |
| 5.15.11-arch2-1              | 1         | 1.72%   |
| 5.15.10-arch1-1              | 1         | 1.72%   |
| 5.14.9-zen2-1-zen            | 1         | 1.72%   |
| 5.14.8-arch1-1               | 1         | 1.72%   |
| 5.14.16-zen1-1-zen           | 1         | 1.72%   |
| 5.14.16-arch1-2-surface      | 1         | 1.72%   |
| 5.14.16-arch1-1              | 1         | 1.72%   |
| 5.14.15-zen1-1-zen           | 1         | 1.72%   |
| 5.14.14-zen1-1-zen           | 1         | 1.72%   |
| 5.14.12-arch1-1              | 1         | 1.72%   |
| 5.14.11-hardened1-1-hardened | 1         | 1.72%   |
| 5.13.4-zen1-1-zen            | 1         | 1.72%   |
| 5.13.13-AMD                  | 1         | 1.72%   |
| 5.12.5-AMD                   | 1         | 1.72%   |
| 5.11.16-zen1-1-zen           | 1         | 1.72%   |
| 5.10.88-1-lts                | 1         | 1.72%   |
| 5.10.80-1-lts                | 1         | 1.72%   |
| 5.10.71-1-lts                | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 10.34%  |
| 5.14.14 | 4         | 6.9%    |
| 5.16.2  | 3         | 5.17%   |
| 5.16.16 | 3         | 5.17%   |
| 5.16.1  | 3         | 5.17%   |
| 5.15.12 | 3         | 5.17%   |
| 5.14.8  | 3         | 5.17%   |
| 5.14.16 | 3         | 5.17%   |
| 5.16.8  | 2         | 3.45%   |
| 5.16.13 | 2         | 3.45%   |
| 5.16.12 | 2         | 3.45%   |
| 5.15.13 | 2         | 3.45%   |
| 5.15.11 | 2         | 3.45%   |
| 5.17.1  | 1         | 1.72%   |
| 5.16.14 | 1         | 1.72%   |
| 5.16.10 | 1         | 1.72%   |
| 5.15.9  | 1         | 1.72%   |
| 5.15.8  | 1         | 1.72%   |
| 5.15.4  | 1         | 1.72%   |
| 5.15.3  | 1         | 1.72%   |
| 5.15.26 | 1         | 1.72%   |
| 5.15.10 | 1         | 1.72%   |
| 5.14.9  | 1         | 1.72%   |
| 5.14.15 | 1         | 1.72%   |
| 5.14.12 | 1         | 1.72%   |
| 5.14.11 | 1         | 1.72%   |
| 5.13.4  | 1         | 1.72%   |
| 5.13.13 | 1         | 1.72%   |
| 5.12.5  | 1         | 1.72%   |
| 5.11.16 | 1         | 1.72%   |
| 5.10.88 | 1         | 1.72%   |
| 5.10.80 | 1         | 1.72%   |
| 5.10.71 | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 41.07%  |
| 5.14    | 13        | 23.21%  |
| 5.15    | 12        | 21.43%  |
| 5.10    | 3         | 5.36%   |
| 5.13    | 2         | 3.57%   |
| 5.17    | 1         | 1.79%   |
| 5.12    | 1         | 1.79%   |
| 5.11    | 1         | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 47        | 88.68%  |
| XFCE  | 4         | 7.55%   |
| GNOME | 2         | 3.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 40        | 78.43%  |
| Wayland | 9         | 17.65%  |
| Tty     | 2         | 3.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 31        | 56.36%  |
| LightDM | 14        | 25.45%  |
| Unknown | 8         | 14.55%  |
| TDM     | 1         | 1.82%   |
| GDM     | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 30        | 57.69%  |
| en_IN | 5         | 9.62%   |
| C     | 4         | 7.69%   |
| pl_PL | 3         | 5.77%   |
| it_IT | 2         | 3.85%   |
| en_GB | 2         | 3.85%   |
| en_AU | 2         | 3.85%   |
| en_IL | 1         | 1.92%   |
| en_CA | 1         | 1.92%   |
| de_DE | 1         | 1.92%   |
| de_AT | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 69.23%  |
| BIOS | 16        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 42        | 79.25%  |
| Ext4    | 7         | 13.21%  |
| Overlay | 4         | 7.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 37        | 71.15%  |
| Unknown | 8         | 15.38%  |
| MBR     | 7         | 13.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 84.91%  |
| Yes       | 8         | 15.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 66.67%  |
| Yes       | 17        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 25.49%  |
| Lenovo              | 10        | 19.61%  |
| Hewlett-Packard     | 7         | 13.73%  |
| Dell                | 7         | 13.73%  |
| MSI                 | 4         | 7.84%   |
| Pegatron            | 2         | 3.92%   |
| Gigabyte Technology | 2         | 3.92%   |
| ASRock              | 2         | 3.92%   |
| Acer                | 2         | 3.92%   |
| HUAWEI              | 1         | 1.96%   |
| Apple               | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Pegatron p6-2026                         | 1         | 1.96%   |
| Pegatron D15K                            | 1         | 1.96%   |
| MSI MS-7B61                              | 1         | 1.96%   |
| MSI MS-7971                              | 1         | 1.96%   |
| MSI GP73 Leopard 8RD                     | 1         | 1.96%   |
| MSI GF63 Thin 9SCX                       | 1         | 1.96%   |
| Lenovo Yoga 710-15IKB 80V5               | 1         | 1.96%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.96%   |
| Lenovo ThinkPad W530 24384CU             | 1         | 1.96%   |
| Lenovo ThinkPad T460 20FMS1XX00          | 1         | 1.96%   |
| Lenovo Legion Y740-15IRHg 81UH           | 1         | 1.96%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 1.96%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.96%   |
| Lenovo IdeaPad S145-15IIL 81W8           | 1         | 1.96%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 1.96%   |
| Lenovo IdeaPad 3 15IML05 81WR            | 1         | 1.96%   |
| HUAWEI WRT-WX9                           | 1         | 1.96%   |
| HP Z230 SFF Workstation                  | 1         | 1.96%   |
| HP ProOne 400 G1 AiO                     | 1         | 1.96%   |
| HP Pavilion Desktop 590-p0xxx            | 1         | 1.96%   |
| HP Notebook                              | 1         | 1.96%   |
| HP Laptop 15s-eq0xxx                     | 1         | 1.96%   |
| HP Laptop 15-da0xxx                      | 1         | 1.96%   |
| HP ENVY Sleekbook 4                      | 1         | 1.96%   |
| Gigabyte Z170X-UD3                       | 1         | 1.96%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.96%   |
| Dell Vostro 3590                         | 1         | 1.96%   |
| Dell Venue 11 Pro 7130 vPro              | 1         | 1.96%   |
| Dell Precision T1500                     | 1         | 1.96%   |
| Dell Precision M3800                     | 1         | 1.96%   |
| Dell Latitude E6520                      | 1         | 1.96%   |
| Dell Latitude E6430                      | 1         | 1.96%   |
| Dell Latitude 7480                       | 1         | 1.96%   |
| ASUS X510UNR                             | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ   | 1         | 1.96%   |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA  | 1         | 1.96%   |
| ASUS TUF Z390-PLUS GAMING                | 1         | 1.96%   |
| ASUS TUF GAMING X570-PLUS                | 1         | 1.96%   |
| ASUS TUF Gaming B550M-PLUS               | 1         | 1.96%   |
| ASUS TUF B360M-PLUS GAMING/BR            | 1         | 1.96%   |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 1.96%   |
| ASUS PRIME A320M-K                       | 1         | 1.96%   |
| ASUS P5Q PRO TURBO                       | 1         | 1.96%   |
| ASUS Maximus IX HERO                     | 1         | 1.96%   |
| ASUS ASUS TUF Gaming F15 FX506LU_FX506LU | 1         | 1.96%   |
| ASUS ASUS EXPERTBOOK B9400CEA_B9450CEA   | 1         | 1.96%   |
| ASRock X570 Taichi                       | 1         | 1.96%   |
| ASRock B450M Pro4                        | 1         | 1.96%   |
| Apple MacBookAir6,2                      | 1         | 1.96%   |
| Acer Aspire X5950                        | 1         | 1.96%   |
| Acer Aspire A315-58G                     | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS TUF           | 4         | 7.84%   |
| Lenovo Legion      | 3         | 5.88%   |
| Lenovo IdeaPad     | 3         | 5.88%   |
| Dell Latitude      | 3         | 5.88%   |
| Lenovo ThinkPad    | 2         | 3.92%   |
| HP Laptop          | 2         | 3.92%   |
| Dell Precision     | 2         | 3.92%   |
| ASUS VivoBook      | 2         | 3.92%   |
| ASUS ASUS          | 2         | 3.92%   |
| Acer Aspire        | 2         | 3.92%   |
| Pegatron p6-2026   | 1         | 1.96%   |
| Pegatron D15K      | 1         | 1.96%   |
| MSI MS-7B61        | 1         | 1.96%   |
| MSI MS-7971        | 1         | 1.96%   |
| MSI GP73           | 1         | 1.96%   |
| MSI GF63           | 1         | 1.96%   |
| Lenovo Yoga        | 1         | 1.96%   |
| Lenovo Y520-15IKBN | 1         | 1.96%   |
| HUAWEI WRT-WX9     | 1         | 1.96%   |
| HP Z230            | 1         | 1.96%   |
| HP ProOne          | 1         | 1.96%   |
| HP Pavilion        | 1         | 1.96%   |
| HP Notebook        | 1         | 1.96%   |
| HP ENVY            | 1         | 1.96%   |
| Gigabyte Z170X-UD3 | 1         | 1.96%   |
| Gigabyte X570      | 1         | 1.96%   |
| Dell Vostro        | 1         | 1.96%   |
| Dell Venue         | 1         | 1.96%   |
| ASUS X510UNR       | 1         | 1.96%   |
| ASUS ROG           | 1         | 1.96%   |
| ASUS PRIME         | 1         | 1.96%   |
| ASUS P5Q           | 1         | 1.96%   |
| ASUS Maximus       | 1         | 1.96%   |
| ASRock X570        | 1         | 1.96%   |
| ASRock B450M       | 1         | 1.96%   |
| Apple MacBookAir6  | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 19.61%  |
| 2020 | 8         | 15.69%  |
| 2018 | 7         | 13.73%  |
| 2017 | 6         | 11.76%  |
| 2021 | 3         | 5.88%   |
| 2015 | 3         | 5.88%   |
| 2012 | 3         | 5.88%   |
| 2016 | 2         | 3.92%   |
| 2014 | 2         | 3.92%   |
| 2013 | 2         | 3.92%   |
| 2011 | 2         | 3.92%   |
| 2010 | 2         | 3.92%   |
| 2009 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 30        | 58.82%  |
| Desktop     | 19        | 37.25%  |
| Convertible | 1         | 1.96%   |
| All in one  | 1         | 1.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 31.37%  |
| 16.01-24.0 | 13        | 25.49%  |
| 8.01-16.0  | 9         | 17.65%  |
| 32.01-64.0 | 6         | 11.76%  |
| 3.01-4.0   | 5         | 9.8%    |
| 24.01-32.0 | 2         | 3.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 17        | 29.31%  |
| 1.01-2.0  | 15        | 25.86%  |
| 4.01-8.0  | 14        | 24.14%  |
| 3.01-4.0  | 6         | 10.34%  |
| 8.01-16.0 | 2         | 3.45%   |
| 0.51-1.0  | 2         | 3.45%   |
| 0.01-0.5  | 2         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 54.9%   |
| 2      | 15        | 29.41%  |
| 3      | 4         | 7.84%   |
| 6      | 2         | 3.92%   |
| 7      | 1         | 1.96%   |
| 4      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 80.39%  |
| Yes       | 10        | 19.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 84.31%  |
| No        | 8         | 15.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 84.31%  |
| No        | 8         | 15.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 78.43%  |
| No        | 11        | 21.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 11        | 21.57%  |
| India                 | 7         | 13.73%  |
| Poland                | 3         | 5.88%   |
| Italy                 | 3         | 5.88%   |
| Greece                | 2         | 3.92%   |
| France                | 2         | 3.92%   |
| Canada                | 2         | 3.92%   |
| Australia             | 2         | 3.92%   |
| UK                    | 1         | 1.96%   |
| Turkey                | 1         | 1.96%   |
| Sweden                | 1         | 1.96%   |
| Spain                 | 1         | 1.96%   |
| Portugal              | 1         | 1.96%   |
| Palestinian Territory | 1         | 1.96%   |
| Pakistan              | 1         | 1.96%   |
| Norway                | 1         | 1.96%   |
| Morocco               | 1         | 1.96%   |
| Mongolia              | 1         | 1.96%   |
| Mexico                | 1         | 1.96%   |
| Malaysia              | 1         | 1.96%   |
| Lebanon               | 1         | 1.96%   |
| Israel                | 1         | 1.96%   |
| Hungary               | 1         | 1.96%   |
| Germany               | 1         | 1.96%   |
| Colombia              | 1         | 1.96%   |
| Brazil                | 1         | 1.96%   |
| Austria               | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Melbourne       | 2         | 3.77%   |
| Zell am See     | 1         | 1.89%   |
| Wrexham         | 1         | 1.89%   |
| Wells           | 1         | 1.89%   |
| Warsaw          | 1         | 1.89%   |
| Vannes          | 1         | 1.89%   |
| Ulan Bator      | 1         | 1.89%   |
| Toronto         | 1         | 1.89%   |
| Tel Aviv        | 1         | 1.89%   |
| Taranto         | 1         | 1.89%   |
| Springfield     | 1         | 1.89%   |
| Salt Lake City  | 1         | 1.89%   |
| Ramallah        | 1         | 1.89%   |
| Poznan          | 1         | 1.89%   |
| Phoenix         | 1         | 1.89%   |
| Passos          | 1         | 1.89%   |
| Panchkula       | 1         | 1.89%   |
| Oslo            | 1         | 1.89%   |
| Neu-Ulm         | 1         | 1.89%   |
| Mumbai          | 1         | 1.89%   |
| Montreal        | 1         | 1.89%   |
| Monterrey       | 1         | 1.89%   |
| Madurai         | 1         | 1.89%   |
| Lucknow         | 1         | 1.89%   |
| Longview        | 1         | 1.89%   |
| Longmont        | 1         | 1.89%   |
| Lisbon          | 1         | 1.89%   |
| Lamia           | 1         | 1.89%   |
| Kuala Lumpur    | 1         | 1.89%   |
| Kista           | 1         | 1.89%   |
| Istanbul        | 1         | 1.89%   |
| Islamabad       | 1         | 1.89%   |
| Granollers      | 1         | 1.89%   |
| Genoa           | 1         | 1.89%   |
| Gdansk          | 1         | 1.89%   |
| Ernakulam       | 1         | 1.89%   |
| East Malvern    | 1         | 1.89%   |
| Dunkirk         | 1         | 1.89%   |
| Denver          | 1         | 1.89%   |
| Danville        | 1         | 1.89%   |
| Chicago         | 1         | 1.89%   |
| Chennai         | 1         | 1.89%   |
| Casablanca      | 1         | 1.89%   |
| Budapest        | 1         | 1.89%   |
| Brisbane        | 1         | 1.89%   |
| Bogotá         | 1         | 1.89%   |
| Blairsville     | 1         | 1.89%   |
| Bhubaneswar     | 1         | 1.89%   |
| Beirut          | 1         | 1.89%   |
| Bari            | 1         | 1.89%   |
| Athens          | 1         | 1.89%   |
| Aix-en-Provence | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 17        | 28     | 20.24%  |
| WDC                       | 14        | 18     | 16.67%  |
| Samsung Electronics       | 14        | 24     | 16.67%  |
| Toshiba                   | 7         | 9      | 8.33%   |
| SanDisk                   | 3         | 3      | 3.57%   |
| Kingston                  | 3         | 5      | 3.57%   |
| Phison                    | 2         | 2      | 2.38%   |
| Micron Technology         | 2         | 3      | 2.38%   |
| LITEON                    | 2         | 2      | 2.38%   |
| Intel                     | 2         | 3      | 2.38%   |
| HGST                      | 2         | 2      | 2.38%   |
| China                     | 2         | 2      | 2.38%   |
| XPG                       | 1         | 1      | 1.19%   |
| Unknown                   | 1         | 1      | 1.19%   |
| PNY                       | 1         | 1      | 1.19%   |
| PLEXTOR                   | 1         | 1      | 1.19%   |
| Micron/Crucial Technology | 1         | 1      | 1.19%   |
| KIOXIA                    | 1         | 1      | 1.19%   |
| Intenso                   | 1         | 1      | 1.19%   |
| Hitachi                   | 1         | 1      | 1.19%   |
| GOODRAM                   | 1         | 1      | 1.19%   |
| Crucial                   | 1         | 1      | 1.19%   |
| Apple                     | 1         | 1      | 1.19%   |
| Apacer                    | 1         | 1      | 1.19%   |
| A-DATA Technology         | 1         | 1      | 1.19%   |
| 2-Power                   | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                     | 2         | 2.08%   |
| Seagate ST1000LM049-2GH172 1TB             | 2         | 2.08%   |
| Seagate ST1000LM048-2E7172 1TB             | 2         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 2.08%   |
| Samsung SSD 970 EVO 1TB                    | 2         | 2.08%   |
| Samsung SSD 860 EVO 1TB                    | 2         | 2.08%   |
| Kingston SA400S37240G 240GB SSD            | 2         | 2.08%   |
| XPG GAMMIX S50 2TB                         | 1         | 1.04%   |
| WDC WDS500G3XHC-00SJG0 500GB               | 1         | 1.04%   |
| WDC WDS500G3X0C-00SJG0 500GB               | 1         | 1.04%   |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1         | 1.04%   |
| WDC WD800JD-00MSA1 80GB                    | 1         | 1.04%   |
| WDC WD7500BPKT-75PK4T0 752GB               | 1         | 1.04%   |
| WDC WD6400AAKS-22A7B2 640GB                | 1         | 1.04%   |
| WDC WD5000AAKX-60U6AA0 500GB               | 1         | 1.04%   |
| WDC WD2500BEVT-60ZCT1 250GB                | 1         | 1.04%   |
| WDC WD2003FZEX-00SRLA0 2TB                 | 1         | 1.04%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1         | 1.04%   |
| WDC WD10EZEX-22MFCA0 1TB                   | 1         | 1.04%   |
| WDC WD1002FAEX-00Z3A0 1TB                  | 1         | 1.04%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB       | 1         | 1.04%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB       | 1         | 1.04%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 1.04%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB       | 1         | 1.04%   |
| Unknown G1J38E  64GB                       | 1         | 1.04%   |
| Toshiba MQ01ABF050M 500GB                  | 1         | 1.04%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 1.04%   |
| Toshiba MK4058GSX 400GB                    | 1         | 1.04%   |
| Toshiba KBG40ZNT512G MEMORY 512GB          | 1         | 1.04%   |
| Toshiba KBG30ZMV256G 256GB                 | 1         | 1.04%   |
| Toshiba HDWR160 6TB                        | 1         | 1.04%   |
| Toshiba HDWE160 6TB                        | 1         | 1.04%   |
| Seagate ST9500325AS 500GB                  | 1         | 1.04%   |
| Seagate ST500LT012-9WS142 500GB            | 1         | 1.04%   |
| Seagate ST500LM000-SSHD-8GB                | 1         | 1.04%   |
| Seagate ST3500418AS 500GB                  | 1         | 1.04%   |
| Seagate ST250DM000-1BD141 250GB            | 1         | 1.04%   |
| Seagate ST2000DX001-1CM164 2TB             | 1         | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB             | 1         | 1.04%   |
| Seagate ST2000DM006-2DM164 2TB             | 1         | 1.04%   |
| Seagate ST2000DM001-1ER164 2TB             | 1         | 1.04%   |
| Seagate ST1000DX001-SSHD-8GB               | 1         | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB             | 1         | 1.04%   |
| Seagate ST10000NE0008-2JM101 10TB          | 1         | 1.04%   |
| Seagate One Touch HDD 5TB                  | 1         | 1.04%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB | 1         | 1.04%   |
| Seagate Expansion 320GB                    | 1         | 1.04%   |
| Seagate Backup+ Hub BK 10TB                | 1         | 1.04%   |
| SanDisk SDSSDH31024G 1024GB                | 1         | 1.04%   |
| Sandisk NVMe SSD Drive 500GB               | 1         | 1.04%   |
| Sandisk NVMe SSD Drive 256GB               | 1         | 1.04%   |
| Samsung SSD 980 PRO 2TB                    | 1         | 1.04%   |
| Samsung SSD 980 PRO 1TB                    | 1         | 1.04%   |
| Samsung SSD 970 EVO Plus 500GB             | 1         | 1.04%   |
| Samsung SSD 960 EVO 250GB                  | 1         | 1.04%   |
| Samsung SSD 860 EVO 250GB                  | 1         | 1.04%   |
| Samsung SSD 850 EVO 250GB                  | 1         | 1.04%   |
| Samsung PM961 NVMe 1024GB                  | 1         | 1.04%   |
| Samsung MZVLB1T0HBLR-00000 1TB             | 1         | 1.04%   |
| Samsung MZVLB1T0HALR-000L2 1TB             | 1         | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 27     | 50%     |
| WDC                 | 8         | 10     | 23.53%  |
| Toshiba             | 5         | 7      | 14.71%  |
| HGST                | 2         | 2      | 5.88%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 30%     |
| LITEON              | 2         | 2      | 10%     |
| Kingston            | 2         | 3      | 10%     |
| China               | 2         | 2      | 10%     |
| SanDisk             | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| PLEXTOR             | 1         | 1      | 5%      |
| GOODRAM             | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |
| Apacer              | 1         | 1      | 5%      |
| 2-Power             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 48     | 36.99%  |
| NVMe    | 26        | 42     | 35.62%  |
| SSD     | 18        | 23     | 24.66%  |
| MMC     | 1         | 1      | 1.37%   |
| Unknown | 1         | 1      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 69     | 55.22%  |
| NVMe | 26        | 42     | 38.81%  |
| SAS  | 3         | 3      | 4.48%   |
| MMC  | 1         | 1      | 1.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 33     | 44.9%   |
| 0.51-1.0   | 18        | 25     | 36.73%  |
| 1.01-2.0   | 5         | 8      | 10.2%   |
| 4.01-10.0  | 4         | 5      | 8.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 16        | 29.09%  |
| 1001-2000      | 15        | 27.27%  |
| 501-1000       | 6         | 10.91%  |
| 251-500        | 5         | 9.09%   |
| Unknown        | 4         | 7.27%   |
| 51-100         | 3         | 5.45%   |
| 2001-3000      | 2         | 3.64%   |
| 1-20           | 2         | 3.64%   |
| 21-50          | 1         | 1.82%   |
| 101-250        | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 33.93%  |
| 51-100         | 15        | 26.79%  |
| 1-20           | 7         | 12.5%   |
| Unknown        | 4         | 7.14%   |
| 1001-2000      | 3         | 5.36%   |
| 501-1000       | 3         | 5.36%   |
| 251-500        | 2         | 3.57%   |
| More than 3000 | 1         | 1.79%   |
| 21-50          | 1         | 1.79%   |
| 2001-3000      | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB   | 1         | 1      | 8.33%   |
| WDC WD1002FAEX-00Z3A0 1TB      | 1         | 2      | 8.33%   |
| Toshiba MQ01ABF050M 500GB      | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 8.33%   |
| Toshiba MK4058GSX 400GB        | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB      | 1         | 1      | 8.33%   |
| Seagate ST500LM000-SSHD-8GB    | 1         | 1      | 8.33%   |
| Seagate ST2000DM006-2DM164 2TB | 1         | 1      | 8.33%   |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 8.33%   |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 8.33%   |
| Hitachi HTS725050A9A364 500GB  | 1         | 1      | 8.33%   |
| China SATA3 240GB SSD          | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| WDC     | 2         | 3      | 18.18%  |
| Toshiba | 2         | 3      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| China   | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 50%     |
| WDC     | 2         | 3      | 20%     |
| Toshiba | 2         | 3      | 20%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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
| Works    | 41        | 81     | 65.08%  |
| Detected | 11        | 21     | 17.46%  |
| Malfunc  | 11        | 13     | 17.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 40        | 51.95%  |
| Samsung Electronics          | 9         | 11.69%  |
| Sandisk                      | 8         | 10.39%  |
| AMD                          | 8         | 10.39%  |
| Toshiba America Info Systems | 2         | 2.6%    |
| Phison Electronics           | 2         | 2.6%    |
| Micron Technology            | 2         | 2.6%    |
| Seagate Technology           | 1         | 1.3%    |
| Realtek Semiconductor        | 1         | 1.3%    |
| Micron/Crucial Technology    | 1         | 1.3%    |
| KIOXIA                       | 1         | 1.3%    |
| Kingston Technology Company  | 1         | 1.3%    |
| ADATA Technology             | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 8.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 6.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 6.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 4.82%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 3.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.61%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 2.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.41%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.41%   |
| Micron Non-Volatile memory controller                                          | 2         | 2.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.41%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 2.41%   |
| Intel SSD 660P Series                                                          | 2         | 2.41%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 2.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.41%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.2%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.2%    |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.2%    |
| Sandisk Non-Volatile memory controller                                         | 1         | 1.2%    |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.2%    |
| Samsung Apple PCIe SSD                                                         | 1         | 1.2%    |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.2%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.2%    |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.2%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.2%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.2%    |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.2%    |
| AMD FCH SATA Controller D                                                      | 1         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.2%    |
| ADATA Non-Volatile memory controller                                           | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 41        | 54.67%  |
| NVMe | 26        | 34.67%  |
| RAID | 8         | 10.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 42        | 82.35%  |
| AMD    | 9         | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 5.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 3.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.92%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2         | 3.92%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1         | 1.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.96%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.96%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 1.96%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.96%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.96%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.96%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.96%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 1         | 1.96%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.96%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 1.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.96%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1         | 1.96%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 1.96%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 1.96%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 1.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.96%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1         | 1.96%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1         | 1.96%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.96%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1         | 1.96%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.96%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.96%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 1.96%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.96%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.96%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 17        | 33.33%  |
| Intel Core i5     | 15        | 29.41%  |
| Intel Core i3     | 4         | 7.84%   |
| AMD Ryzen 5       | 4         | 7.84%   |
| Other             | 3         | 5.88%   |
| AMD Ryzen 7       | 2         | 3.92%   |
| Intel Genuine     | 1         | 1.96%   |
| Intel Core 2 Quad | 1         | 1.96%   |
| Intel Celeron     | 1         | 1.96%   |
| AMD Ryzen 9       | 1         | 1.96%   |
| AMD Ryzen 3       | 1         | 1.96%   |
| AMD Athlon        | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 45.1%   |
| 2      | 15        | 29.41%  |
| 6      | 8         | 15.69%  |
| 8      | 4         | 7.84%   |
| 12     | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 82.69%  |
| 1      | 9         | 17.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 20.75%  |
| 0x906ea    | 4         | 7.55%   |
| 0x806e9    | 4         | 7.55%   |
| 0x806ec    | 3         | 5.66%   |
| 0x806c1    | 3         | 5.66%   |
| 0x906ed    | 2         | 3.77%   |
| 0x906e9    | 2         | 3.77%   |
| 0x506e3    | 2         | 3.77%   |
| 0x306c3    | 2         | 3.77%   |
| 0x306a9    | 2         | 3.77%   |
| 0x0a201016 | 2         | 3.77%   |
| 0x08701021 | 2         | 3.77%   |
| 0xa0652    | 1         | 1.89%   |
| 0x906eb    | 1         | 1.89%   |
| 0x806eb    | 1         | 1.89%   |
| 0x706e5    | 1         | 1.89%   |
| 0x706a8    | 1         | 1.89%   |
| 0x406e3    | 1         | 1.89%   |
| 0x40651    | 1         | 1.89%   |
| 0x206a7    | 1         | 1.89%   |
| 0x20655    | 1         | 1.89%   |
| 0x1067a    | 1         | 1.89%   |
| 0x08701013 | 1         | 1.89%   |
| 0x08600106 | 1         | 1.89%   |
| 0x08108109 | 1         | 1.89%   |
| 0x0810100b | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 39.22%  |
| Haswell       | 5         | 9.8%    |
| Zen 2         | 4         | 7.84%   |
| TigerLake     | 3         | 5.88%   |
| Skylake       | 3         | 5.88%   |
| IvyBridge     | 3         | 5.88%   |
| Zen+          | 2         | 3.92%   |
| Zen 3         | 2         | 3.92%   |
| SandyBridge   | 2         | 3.92%   |
| Zen           | 1         | 1.96%   |
| Westmere      | 1         | 1.96%   |
| Penryn        | 1         | 1.96%   |
| Nehalem       | 1         | 1.96%   |
| IceLake       | 1         | 1.96%   |
| Goldmont plus | 1         | 1.96%   |
| CometLake     | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 46.48%  |
| Nvidia | 27        | 38.03%  |
| AMD    | 11        | 15.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 5.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 5.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 4.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 3         | 4.23%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 2.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 2         | 2.82%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 2.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 2.82%   |
| Intel UHD Graphics 620                                                                | 2         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 2.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 2.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.41%   |
| Nvidia TU117M                                                                         | 1         | 1.41%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 1.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 1.41%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 1.41%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 1         | 1.41%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.41%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 1.41%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 1         | 1.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 1         | 1.41%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 1         | 1.41%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 1.41%   |
| Nvidia GK107 [GeForce GT 740]                                                         | 1         | 1.41%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 1.41%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.41%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                        | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.41%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.41%   |
| Intel HD Graphics 630                                                                 | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.41%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                      | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.41%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                    | 1         | 1.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.41%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 1.41%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 1         | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 16        | 31.37%  |
| 1 x Intel      | 13        | 25.49%  |
| 1 x Nvidia     | 11        | 21.57%  |
| 1 x AMD        | 8         | 15.69%  |
| Intel + AMD    | 3         | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 29        | 55.77%  |
| Proprietary | 22        | 42.31%  |
| Unknown     | 1         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 59.62%  |
| 1.01-2.0   | 8         | 15.38%  |
| 7.01-8.0   | 5         | 9.62%   |
| 5.01-6.0   | 4         | 7.69%   |
| 0.01-0.5   | 2         | 3.85%   |
| 3.01-4.0   | 1         | 1.92%   |
| 8.01-16.0  | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 10        | 16.95%  |
| BOE                  | 8         | 13.56%  |
| AU Optronics         | 7         | 11.86%  |
| Chimei Innolux       | 6         | 10.17%  |
| LG Display           | 4         | 6.78%   |
| Ancor Communications | 3         | 5.08%   |
| Hewlett-Packard      | 2         | 3.39%   |
| Goldstar             | 2         | 3.39%   |
| Apple                | 2         | 3.39%   |
| AOC                  | 2         | 3.39%   |
| Acer                 | 2         | 3.39%   |
| Sharp                | 1         | 1.69%   |
| Sceptre Tech         | 1         | 1.69%   |
| PANDA                | 1         | 1.69%   |
| Lenovo               | 1         | 1.69%   |
| Kogan                | 1         | 1.69%   |
| KOC                  | 1         | 1.69%   |
| Idek Iiyama          | 1         | 1.69%   |
| Hitachi              | 1         | 1.69%   |
| Gigabyte Technology  | 1         | 1.69%   |
| Dell                 | 1         | 1.69%   |
| ASUSTek Computer     | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 3.33%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 1.67%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 1.67%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.67%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1         | 1.67%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch       | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch   | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 1.67%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 1.67%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.67%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.67%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.67%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                | 1         | 1.67%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch                | 1         | 1.67%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 1.67%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                               | 1         | 1.67%   |
| Hitachi HISENSE HEC002F 3840x2160 1150x650mm 52.0-inch                  | 1         | 1.67%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch             | 1         | 1.67%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 1         | 1.67%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 1         | 1.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1         | 1.67%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch          | 1         | 1.67%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 1.67%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.67%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                   | 1         | 1.67%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                   | 1         | 1.67%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 1.67%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 1         | 1.67%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 1         | 1.67%   |
| BOE LCD Monitor BOE06D1 1366x768 309x173mm 13.9-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 1         | 1.67%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.67%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch          | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch           | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.67%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch          | 1         | 1.67%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 1         | 1.67%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                   | 1         | 1.67%   |
| AOC 27B2 AOC2702 1920x1080 600x340mm 27.2-inch                          | 1         | 1.67%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                        | 1         | 1.67%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch        | 1         | 1.67%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 800x340mm 34.2-inch   | 1         | 1.67%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch   | 1         | 1.67%   |
| Acer X233H ACR0093 1920x1080 510x287mm 23.0-inch                        | 1         | 1.67%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                       | 1         | 1.67%   |
| Acer G215H ACR0109 1920x1080 477x268mm 21.5-inch                        | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 30        | 53.57%  |
| 1366x768 (WXGA)   | 6         | 10.71%  |
| 3840x2160 (4K)    | 5         | 8.93%   |
| 2560x1440 (QHD)   | 4         | 7.14%   |
| 3440x1440         | 3         | 5.36%   |
| 3840x1080         | 1         | 1.79%   |
| 2560x1080         | 1         | 1.79%   |
| 2160x1440         | 1         | 1.79%   |
| 1920x540          | 1         | 1.79%   |
| 1920x1200 (WUXGA) | 1         | 1.79%   |
| 1600x900 (HD+)    | 1         | 1.79%   |
| 1440x900 (WXGA+)  | 1         | 1.79%   |
| 1280x1024 (SXGA)  | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 36.21%  |
| 27      | 5         | 8.62%   |
| 14      | 4         | 6.9%    |
| 13      | 4         | 6.9%    |
| 34      | 3         | 5.17%   |
| 24      | 3         | 5.17%   |
| 23      | 3         | 5.17%   |
| 21      | 3         | 5.17%   |
| 84      | 2         | 3.45%   |
| 31      | 2         | 3.45%   |
| 18      | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 54      | 1         | 1.72%   |
| 48      | 1         | 1.72%   |
| 28      | 1         | 1.72%   |
| 17      | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 46.55%  |
| 501-600     | 10        | 17.24%  |
| 401-500     | 5         | 8.62%   |
| 701-800     | 3         | 5.17%   |
| 601-700     | 3         | 5.17%   |
| 351-400     | 2         | 3.45%   |
| 201-300     | 2         | 3.45%   |
| 1501-2000   | 2         | 3.45%   |
| 1001-1500   | 2         | 3.45%   |
| Unknown     | 2         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 80.77%  |
| 21/9    | 4         | 7.69%   |
| 16/10   | 2         | 3.85%   |
| 5/4     | 1         | 1.92%   |
| 32/9    | 1         | 1.92%   |
| 3/2     | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 36.21%  |
| 201-250        | 8         | 13.79%  |
| 81-90          | 7         | 12.07%  |
| 351-500        | 5         | 8.62%   |
| 301-350        | 5         | 8.62%   |
| More than 1000 | 3         | 5.17%   |
| 151-200        | 2         | 3.45%   |
| Unknown        | 2         | 3.45%   |
| 71-80          | 1         | 1.72%   |
| 251-300        | 1         | 1.72%   |
| 141-150        | 1         | 1.72%   |
| 121-130        | 1         | 1.72%   |
| 501-1000       | 1         | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 40.74%  |
| 101-120       | 13        | 24.07%  |
| 51-100        | 13        | 24.07%  |
| 161-240       | 2         | 3.7%    |
| Unknown       | 2         | 3.7%    |
| More than 240 | 1         | 1.85%   |
| 1-50          | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 41        | 78.85%  |
| 2     | 9         | 17.31%  |
| 3     | 1         | 1.92%   |
| 0     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 44.59%  |
| Realtek Semiconductor | 27        | 36.49%  |
| Qualcomm Atheros      | 3         | 4.05%   |
| Broadcom Limited      | 2         | 2.7%    |
| Broadcom              | 2         | 2.7%    |
| ASIX Electronics      | 2         | 2.7%    |
| TP-Link               | 1         | 1.35%   |
| Samsung Electronics   | 1         | 1.35%   |
| Qualcomm              | 1         | 1.35%   |
| NetGear               | 1         | 1.35%   |
| Microsoft             | 1         | 1.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 19        | 20.88%  |
| Intel Wi-Fi 6 AX200                                                       | 5         | 5.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                         | 3         | 3.3%    |
| Intel Wi-Fi 6 AX201                                                       | 3         | 3.3%    |
| Intel I211 Gigabit Network Connection                                     | 3         | 3.3%    |
| Intel Ethernet Connection (2) I219-V                                      | 3         | 3.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 3.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 2         | 2.2%    |
| Intel Wireless-AC 9260                                                    | 2         | 2.2%    |
| Intel Wireless 8265 / 8275                                                | 2         | 2.2%    |
| Intel Ethernet Connection (7) I219-V                                      | 2         | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 2.2%    |
| ASIX AX88179 Gigabit Ethernet                                             | 2         | 2.2%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.1%    |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1         | 1.1%    |
| Qualcomm Redmi Note 7                                                     | 1         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 1         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1         | 1.1%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.1%    |
| Intel Wireless 8260                                                       | 1         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.1%    |
| Intel Ethernet Connection I219-V                                          | 1         | 1.1%    |
| Intel Ethernet Connection I217-LM                                         | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                     | 1         | 1.1%    |
| Intel Ethernet Connection (13) I219-V                                     | 1         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.1%    |
| Intel Centrino Wireless-N 2230                                            | 1         | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1         | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.1%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.1%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 63.64%  |
| Realtek Semiconductor | 7         | 15.91%  |
| Qualcomm Atheros      | 2         | 4.55%   |
| Broadcom Limited      | 2         | 4.55%   |
| Broadcom              | 2         | 4.55%   |
| TP-Link               | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| Microsoft             | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 5         | 11.36%  |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 11.36%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 6.82%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 6.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 6.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 4.55%   |
| Intel Wireless-AC 9260                                                    | 2         | 4.55%   |
| Intel Wireless 8265 / 8275                                                | 2         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 4.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 2.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 2.27%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 1         | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 2.27%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 2.27%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 2.27%   |
| Intel Wireless 8260                                                       | 1         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 2.27%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 2.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 2.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 2.27%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 53.19%  |
| Intel                 | 15        | 31.91%  |
| Qualcomm Atheros      | 2         | 4.26%   |
| ASIX Electronics      | 2         | 4.26%   |
| Samsung Electronics   | 1         | 2.13%   |
| Qualcomm              | 1         | 2.13%   |
| Broadcom              | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 40.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 6.38%   |
| Intel I211 Gigabit Network Connection                             | 3         | 6.38%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.26%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 4.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.13%   |
| Qualcomm Redmi Note 7                                             | 1         | 2.13%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.13%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 50%     |
| Ethernet | 43        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 62.5%   |
| Ethernet | 21        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 52.94%  |
| 1     | 21        | 41.18%  |
| 3     | 2         | 3.92%   |
| 0     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 76.92%  |
| Yes  | 12        | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 60%     |
| Realtek Semiconductor           | 5         | 12.5%   |
| Broadcom                        | 4         | 10%     |
| IMC Networks                    | 2         | 5%      |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| Dell                            | 1         | 2.5%    |
| Cambridge Silicon Radio         | 1         | 2.5%    |
| ASUSTek Computer                | 1         | 2.5%    |
| Apple                           | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 27.5%   |
| Intel AX200 Bluetooth                               | 5         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.5%    |
| Intel AX201 Bluetooth                               | 3         | 7.5%    |
| Realtek Bluetooth Radio                             | 2         | 5%      |
| Intel Bluetooth wireless interface                  | 2         | 5%      |
| Intel Bluetooth Device                              | 2         | 5%      |
| IMC Networks Bluetooth Radio                        | 2         | 5%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.5%    |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 2.5%    |
| Broadcom BCM2045A0                                  | 1         | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.5%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 42        | 50.6%   |
| Nvidia                 | 17        | 20.48%  |
| AMD                    | 11        | 13.25%  |
| Razer USA              | 2         | 2.41%   |
| Corsair                | 2         | 2.41%   |
| C-Media Electronics    | 2         | 2.41%   |
| Tenx Technology        | 1         | 1.2%    |
| Samsung Electronics    | 1         | 1.2%    |
| Plantronics            | 1         | 1.2%    |
| Logitech               | 1         | 1.2%    |
| Kingston Technology    | 1         | 1.2%    |
| Hewlett-Packard        | 1         | 1.2%    |
| Generalplus Technology | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 7.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 7.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 5.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 3.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.19%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 3.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 2.13%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.13%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.13%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.13%   |
| Tenx Technology USB AUDIO                                                  | 1         | 1.06%   |
| Samsung Electronics USBC Headset                                           | 1         | 1.06%   |
| Razer USA Razer Kraken X USB                                               | 1         | 1.06%   |
| Razer USA Razer Kraken Ultimate                                            | 1         | 1.06%   |
| Plantronics C320-M                                                         | 1         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.06%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.06%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.06%   |
| Logitech G633 Gaming Headset                                               | 1         | 1.06%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1         | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.06%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.06%   |
| Hewlett-Packard E240C                                                      | 1         | 1.06%   |
| Generalplus Technology USB Audio Device                                    | 1         | 1.06%   |
| Corsair Slipstream Multi-Device Receiver                                   | 1         | 1.06%   |
| Corsair CORSAIR HS60 PRO SURROUND                                          | 1         | 1.06%   |
| C-Media Electronics USB Modi Device                                        | 1         | 1.06%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 1.06%   |
| C-Media Electronics Blue Snowball                                          | 1         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.06%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 14        | 25.45%  |
| Samsung Electronics | 13        | 23.64%  |
| Micron Technology   | 5         | 9.09%   |
| G.Skill             | 5         | 9.09%   |
| Kingston            | 4         | 7.27%   |
| Crucial             | 4         | 7.27%   |
| Corsair             | 3         | 5.45%   |
| Unknown             | 2         | 3.64%   |
| Ramaxel Technology  | 2         | 3.64%   |
| Unifosa             | 1         | 1.82%   |
| Team                | 1         | 1.82%   |
| PNY                 | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 3.45%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 3.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.72%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.72%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 1.72%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.72%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s             | 1         | 1.72%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.72%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.72%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.72%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.72%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 1.72%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 1.72%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.72%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s              | 1         | 1.72%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 1.72%   |
| Kingston RAM KHYXPX-MID 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.72%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s              | 1         | 1.72%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Kingston RAM 99U5428-069.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s              | 1         | 1.72%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 1         | 1.72%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s           | 1         | 1.72%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s        | 1         | 1.72%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s             | 1         | 1.72%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s             | 1         | 1.72%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4096MB DIMM DDR4 2400MT/s         | 1         | 1.72%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s            | 1         | 1.72%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 1.72%   |
| Corsair RAM CMSO16GX4M2A2133C15 8GB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s             | 1         | 1.72%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s            | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 30        | 68.18%  |
| DDR3   | 10        | 22.73%  |
| SDRAM  | 1         | 2.27%   |
| LPDDR4 | 1         | 2.27%   |
| LPDDR3 | 1         | 2.27%   |
| DDR2   | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 55.56%  |
| DIMM         | 15        | 33.33%  |
| Row Of Chips | 5         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 47.92%  |
| 4096  | 16        | 33.33%  |
| 16384 | 7         | 14.58%  |
| 2048  | 2         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 14        | 28%     |
| 3200  | 8         | 16%     |
| 1600  | 8         | 16%     |
| 2400  | 4         | 8%      |
| 3266  | 2         | 4%      |
| 4400  | 1         | 2%      |
| 4267  | 1         | 2%      |
| 4199  | 1         | 2%      |
| 4133  | 1         | 2%      |
| 3800  | 1         | 2%      |
| 3600  | 1         | 2%      |
| 3067  | 1         | 2%      |
| 2747  | 1         | 2%      |
| 2666  | 1         | 2%      |
| 2176  | 1         | 2%      |
| 2133  | 1         | 2%      |
| 1450  | 1         | 2%      |
| 1333  | 1         | 2%      |
| 800   | 1         | 2%      |

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
| IMC Networks                           | 6         | 17.65%  |
| Chicony Electronics                    | 6         | 17.65%  |
| Realtek Semiconductor                  | 4         | 11.76%  |
| Quanta                                 | 3         | 8.82%   |
| Acer                                   | 3         | 8.82%   |
| Syntek                                 | 2         | 5.88%   |
| Sunplus Innovation Technology          | 2         | 5.88%   |
| Microdia                               | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Logitech                               | 1         | 2.94%   |
| Lite-On Technology                     | 1         | 2.94%   |
| Generalplus Technology                 | 1         | 2.94%   |
| Alpha Imaging Technology               | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                             | 2         | 5.88%   |
| Quanta HP TrueVision HD Camera                                       | 2         | 5.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                                   | 2         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam                                    | 2         | 5.88%   |
| Chicony Integrated Camera                                            | 2         | 5.88%   |
| Chicony EasyCamera                                                   | 2         | 5.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 2.94%   |
| Sunplus HP Truevision HD                                             | 1         | 2.94%   |
| Realtek Integrated_Webcam_HD                                         | 1         | 2.94%   |
| Realtek Integrated Webcam_HD                                         | 1         | 2.94%   |
| Realtek Integrated Webcam                                            | 1         | 2.94%   |
| Realtek Built-In Video Camera                                        | 1         | 2.94%   |
| Quanta HD User Facing                                                | 1         | 2.94%   |
| Microdia Integrated_Webcam_HD                                        | 1         | 2.94%   |
| Microdia Dell Integrated HD Webcam                                   | 1         | 2.94%   |
| Logitech Webcam C600                                                 | 1         | 2.94%   |
| Lite-On Integrated Camera                                            | 1         | 2.94%   |
| IMC Networks VGA UVC WebCam                                          | 1         | 2.94%   |
| IMC Networks Integrated Camera                                       | 1         | 2.94%   |
| Generalplus GENERAL WEBCAM                                           | 1         | 2.94%   |
| Chicony HP Webcam                                                    | 1         | 2.94%   |
| Chicony HP High Definition 1MP Webcam                                | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                     | 1         | 2.94%   |
| Alpha Imaging Integrated_Webcam_8M                                   | 1         | 2.94%   |
| Acer ThinkPad Integrated Camera                                      | 1         | 2.94%   |
| Acer SunplusIT Integrated Camera                                     | 1         | 2.94%   |
| Acer HD Webcam                                                       | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 1         | 50%     |
| Shenzhen Goodix  FingerPrint Device | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 73.08%  |
| 1     | 12        | 23.08%  |
| 2     | 2         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 3         | 18.75%  |
| Chipcard              | 3         | 18.75%  |
| Fingerprint reader    | 2         | 12.5%   |
| Camera                | 2         | 12.5%   |
| Bluetooth             | 2         | 12.5%   |
| Storage               | 1         | 6.25%   |
| Network               | 1         | 6.25%   |
| Net/wireless          | 1         | 6.25%   |
| Multimedia controller | 1         | 6.25%   |

