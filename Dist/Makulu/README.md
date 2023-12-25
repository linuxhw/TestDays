Makulu - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Makulu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Makulu/Desktop/README.md) and [notebooks](/Dist/Makulu/Notebook/README.md).

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

Total: 83

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0GXM1W A02                  | Desktop     | [daa70c78f0](https://linux-hardware.org/?probe=daa70c78f0) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [9b084ae5b9](https://linux-hardware.org/?probe=9b084ae5b9) | Dec 11, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [459870519f](https://linux-hardware.org/?probe=459870519f) | Dec 09, 2023 |
| HP            | 89E9 0100                   | All in one  | [1065dc9d0b](https://linux-hardware.org/?probe=1065dc9d0b) | Nov 18, 2023 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [f6d894d339](https://linux-hardware.org/?probe=f6d894d339) | Aug 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [8033ce619e](https://linux-hardware.org/?probe=8033ce619e) | Aug 22, 2023 |
| Dell          | Latitude E5470              | Notebook    | [2fa90c8f06](https://linux-hardware.org/?probe=2fa90c8f06) | Aug 22, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| MSI           | Z97 MPOWER                  | Desktop     | [0cf75057cc](https://linux-hardware.org/?probe=0cf75057cc) | Jun 24, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [55046e008f](https://linux-hardware.org/?probe=55046e008f) | May 11, 2023 |
| Fujitsu       | STYLISTIC Q665              | Notebook    | [438b08fb3d](https://linux-hardware.org/?probe=438b08fb3d) | Mar 06, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| Fujitsu       | STYLISTIC Q665              | Notebook    | [268703bd9e](https://linux-hardware.org/?probe=268703bd9e) | Feb 13, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [53f4f127f2](https://linux-hardware.org/?probe=53f4f127f2) | Jan 31, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [cbc5231e9c](https://linux-hardware.org/?probe=cbc5231e9c) | Jan 30, 2023 |
| Eii           | GB01                        | Desktop     | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| Dell          | Latitude E64406342Q0286/    | Notebook    | [e044c94514](https://linux-hardware.org/?probe=e044c94514) | Dec 26, 2022 |
| Dell          | Latitude E64406342Q0286/    | Notebook    | [41b2b27a91](https://linux-hardware.org/?probe=41b2b27a91) | Dec 16, 2022 |
| Dell          | Latitude E64406342Q0286/    | Notebook    | [e8b2c9218f](https://linux-hardware.org/?probe=e8b2c9218f) | Dec 15, 2022 |
| MSI           | 970A-G43                    | Desktop     | [cf36036d1d](https://linux-hardware.org/?probe=cf36036d1d) | Oct 18, 2022 |
| MSI           | 970A-G43                    | Desktop     | [c9c2e07ada](https://linux-hardware.org/?probe=c9c2e07ada) | Oct 10, 2022 |
| MSI           | 970A-G43                    | Desktop     | [0b6ff268e1](https://linux-hardware.org/?probe=0b6ff268e1) | Oct 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d750223c3f](https://linux-hardware.org/?probe=d750223c3f) | Sep 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5e75c2d00d](https://linux-hardware.org/?probe=5e75c2d00d) | May 29, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [a583bbdc35](https://linux-hardware.org/?probe=a583bbdc35) | May 19, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [2f4a501c6a](https://linux-hardware.org/?probe=2f4a501c6a) | Mar 05, 2022 |
| Dell          | Latitude 3540               | Notebook    | [6fb057646a](https://linux-hardware.org/?probe=6fb057646a) | Feb 25, 2022 |
| Samsung       | R580                        | Notebook    | [b796f42cc3](https://linux-hardware.org/?probe=b796f42cc3) | Jan 31, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [5d298b8068](https://linux-hardware.org/?probe=5d298b8068) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [c014435339](https://linux-hardware.org/?probe=c014435339) | Dec 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [97cfd9951b](https://linux-hardware.org/?probe=97cfd9951b) | Dec 29, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [cb48d8f436](https://linux-hardware.org/?probe=cb48d8f436) | Dec 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e3873f9847](https://linux-hardware.org/?probe=e3873f9847) | Dec 23, 2021 |
| Dell          | 0DPRF9 A00                  | All in one  | [b3559aeec4](https://linux-hardware.org/?probe=b3559aeec4) | Dec 20, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d3dc0d2eec](https://linux-hardware.org/?probe=d3dc0d2eec) | Nov 04, 2021 |
| ASUSTek       | N55SL                       | Notebook    | [11ed4def95](https://linux-hardware.org/?probe=11ed4def95) | Oct 24, 2021 |
| Dell          | 0TP406                      | Desktop     | [df97b29e2e](https://linux-hardware.org/?probe=df97b29e2e) | Oct 23, 2021 |
| Dell          | 0TP406                      | Desktop     | [5e3ac96715](https://linux-hardware.org/?probe=5e3ac96715) | Oct 22, 2021 |
| MSI           | Boston                      | Desktop     | [c45a00b3d6](https://linux-hardware.org/?probe=c45a00b3d6) | Oct 22, 2021 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [f3168dad1b](https://linux-hardware.org/?probe=f3168dad1b) | Oct 21, 2021 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [d3c50b3461](https://linux-hardware.org/?probe=d3c50b3461) | Sep 26, 2021 |
| Lenovo        | IdeaPad Y530                | Notebook    | [6ca5521110](https://linux-hardware.org/?probe=6ca5521110) | Sep 24, 2021 |
| MSI           | Boston                      | Desktop     | [d95f0de735](https://linux-hardware.org/?probe=d95f0de735) | Sep 21, 2021 |
| MSI           | Boston                      | Desktop     | [50f3ed26ef](https://linux-hardware.org/?probe=50f3ed26ef) | Sep 21, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [b5e3a47db9](https://linux-hardware.org/?probe=b5e3a47db9) | Sep 06, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9787940762](https://linux-hardware.org/?probe=9787940762) | Aug 29, 2021 |
| ELSA          | EA H410M-E                  | Desktop     | [b67c732be6](https://linux-hardware.org/?probe=b67c732be6) | Jul 19, 2021 |
| ELSA          | EA H410M-E                  | Desktop     | [97d82b0054](https://linux-hardware.org/?probe=97d82b0054) | Jul 19, 2021 |
| Dell          | 0MWYPT A00                  | Desktop     | [3577268e97](https://linux-hardware.org/?probe=3577268e97) | Jul 14, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [0da2654313](https://linux-hardware.org/?probe=0da2654313) | Jun 21, 2021 |
| Alienware     | 02XRCM A01                  | Desktop     | [42fb24801d](https://linux-hardware.org/?probe=42fb24801d) | Jun 18, 2021 |
| Alienware     | 02XRCM A01                  | Desktop     | [929ffb30b7](https://linux-hardware.org/?probe=929ffb30b7) | Jun 18, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [66f7c33d00](https://linux-hardware.org/?probe=66f7c33d00) | Jun 08, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [1ce8c5e2c7](https://linux-hardware.org/?probe=1ce8c5e2c7) | Jun 03, 2021 |
| Dell          | 0XFWHV A00                  | Desktop     | [e318737297](https://linux-hardware.org/?probe=e318737297) | May 02, 2021 |
| Lenovo        | IdeaCentre K430             | Desktop     | [cfee2604e5](https://linux-hardware.org/?probe=cfee2604e5) | Apr 30, 2021 |
| HP            | ENVY Notebook               | Notebook    | [61cb15af98](https://linux-hardware.org/?probe=61cb15af98) | Apr 28, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [b9086bf814](https://linux-hardware.org/?probe=b9086bf814) | Apr 14, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [10987a7dec](https://linux-hardware.org/?probe=10987a7dec) | Apr 13, 2021 |
| MSI           | A68HM-P33                   | Desktop     | [52eb515b91](https://linux-hardware.org/?probe=52eb515b91) | Apr 01, 2021 |
| ASRock        | Z77 Pro4                    | Desktop     | [981009625b](https://linux-hardware.org/?probe=981009625b) | Mar 29, 2021 |
| Flextronic... | CPU-5A-C21 C21              | Desktop     | [4aca4558e4](https://linux-hardware.org/?probe=4aca4558e4) | Mar 21, 2021 |
| HP            | Compaq 15                   | Notebook    | [455bc50dc9](https://linux-hardware.org/?probe=455bc50dc9) | Mar 15, 2021 |
| Dell          | 0FK9H3 A00                  | All in one  | [51d212b73f](https://linux-hardware.org/?probe=51d212b73f) | Mar 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [323c65cc17](https://linux-hardware.org/?probe=323c65cc17) | Mar 11, 2021 |
| Dell          | 0XCR8D A01                  | Desktop     | [3ed805ccdf](https://linux-hardware.org/?probe=3ed805ccdf) | Feb 26, 2021 |
| HP            | ENVY Notebook               | Notebook    | [f71898211e](https://linux-hardware.org/?probe=f71898211e) | Feb 25, 2021 |
| Dell          | 0XCR8D A01                  | Desktop     | [4f32c299db](https://linux-hardware.org/?probe=4f32c299db) | Feb 21, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [61834d7ebf](https://linux-hardware.org/?probe=61834d7ebf) | Dec 03, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [80ed244689](https://linux-hardware.org/?probe=80ed244689) | Dec 02, 2020 |
| Lenovo        | ThinkPad T420 4236W1W       | Notebook    | [3c3ff4f10e](https://linux-hardware.org/?probe=3c3ff4f10e) | Dec 02, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c588dc3be6](https://linux-hardware.org/?probe=c588dc3be6) | Nov 27, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [b27a626476](https://linux-hardware.org/?probe=b27a626476) | Oct 03, 2020 |
| Lenovo        | ThinkPad T420 4236W1W       | Notebook    | [73279e52cd](https://linux-hardware.org/?probe=73279e52cd) | Oct 01, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [c8a79a4b9f](https://linux-hardware.org/?probe=c8a79a4b9f) | Sep 30, 2020 |
| HP            | Pavilion 17                 | Notebook    | [a6aa670ab4](https://linux-hardware.org/?probe=a6aa670ab4) | Sep 02, 2020 |
| HP            | Pavilion 17                 | Notebook    | [03171f4dbe](https://linux-hardware.org/?probe=03171f4dbe) | Aug 30, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [585646c033](https://linux-hardware.org/?probe=585646c033) | Feb 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Makulu 2020              | 27        | 49.09%  |
| Makulu Build: 2021.12.15 | 6         | 10.91%  |
| Makulu 2021              | 4         | 7.27%   |
| Makulu Beta1             | 3         | 5.45%   |
| Makulu Bld-2022.08.19    | 2         | 3.64%   |
| Makulu 2022.12.29        | 2         | 3.64%   |
| Makulu Buildvar          | 1         | 1.82%   |
| Makulu Build: 2022.01.06 | 1         | 1.82%   |
| Makulu Bld-2022.12.04    | 1         | 1.82%   |
| Makulu Bld-2022.11.03    | 1         | 1.82%   |
| Makulu Bld-2022.08.10    | 1         | 1.82%   |
| Makulu Beta-2            | 1         | 1.82%   |
| Makulu 68                | 1         | 1.82%   |
| Makulu 2023.07.12        | 1         | 1.82%   |
| Makulu 2023.01.11        | 1         | 1.82%   |
| Makulu 20                | 1         | 1.82%   |
| Makulu 14                | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Makulu | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.8.0-44-generic       | 6         | 10.71%  |
| 5.11.0-41-generic      | 5         | 8.93%   |
| 5.10.0-8-amd64         | 4         | 7.14%   |
| 5.4.0-42-generic       | 3         | 5.36%   |
| 5.11.0-43-generic      | 3         | 5.36%   |
| 6.3.0-1-amd64          | 2         | 3.57%   |
| 6.0.0-5-amd64          | 2         | 3.57%   |
| 5.8.0-50-generic       | 2         | 3.57%   |
| 5.15.0-56-generic      | 2         | 3.57%   |
| 5.15.0-53-generic      | 2         | 3.57%   |
| 5.15.0-46-generic      | 2         | 3.57%   |
| 5.14.0-2-amd64         | 2         | 3.57%   |
| 6.1.6-060106-generic   | 1         | 1.79%   |
| 6.1.11-060111-generic  | 1         | 1.79%   |
| 5.8.0-59-generic       | 1         | 1.79%   |
| 5.8.0-49-generic       | 1         | 1.79%   |
| 5.8.0-48-generic       | 1         | 1.79%   |
| 5.8.0-41-generic       | 1         | 1.79%   |
| 5.8.0-38-generic       | 1         | 1.79%   |
| 5.8.0-23-generic       | 1         | 1.79%   |
| 5.4.0-54-generic       | 1         | 1.79%   |
| 5.4.0-48-generic       | 1         | 1.79%   |
| 5.15.10-051510-generic | 1         | 1.79%   |
| 5.15.0-88-generic      | 1         | 1.79%   |
| 5.15.0-79-generic      | 1         | 1.79%   |
| 5.15.0-48-generic      | 1         | 1.79%   |
| 5.12.11-051211-generic | 1         | 1.79%   |
| 5.11.0-38-generic      | 1         | 1.79%   |
| 5.11.0-36-generic      | 1         | 1.79%   |
| 5.11.0-27-generic      | 1         | 1.79%   |
| 5.10.0-7-amd64         | 1         | 1.79%   |
| 5.10.0-3-amd64         | 1         | 1.79%   |
| 4.14.0-041400-generic  | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 14        | 25%     |
| 5.11.0  | 11        | 19.64%  |
| 5.15.0  | 9         | 16.07%  |
| 5.10.0  | 6         | 10.71%  |
| 5.4.0   | 5         | 8.93%   |
| 6.3.0   | 2         | 3.57%   |
| 6.0.0   | 2         | 3.57%   |
| 5.14.0  | 2         | 3.57%   |
| 6.1.6   | 1         | 1.79%   |
| 6.1.11  | 1         | 1.79%   |
| 5.15.10 | 1         | 1.79%   |
| 5.12.11 | 1         | 1.79%   |
| 4.14.0  | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 14        | 25.45%  |
| 5.11    | 11        | 20%     |
| 5.15    | 10        | 18.18%  |
| 5.10    | 6         | 10.91%  |
| 5.4     | 5         | 9.09%   |
| 6.3     | 2         | 3.64%   |
| 6.0     | 2         | 3.64%   |
| 5.14    | 2         | 3.64%   |
| 6.1     | 1         | 1.82%   |
| 5.12    | 1         | 1.82%   |
| 4.14    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| GNOME       | 38        | 70.37%  |
| X-Cinnamon  | 12        | 22.22%  |
| MakuluGameR | 2         | 3.7%    |
| Core        | 1         | 1.85%   |
| Cinnamon    | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 54        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 77.78%  |
| LightDM | 9         | 16.67%  |
| TDM     | 2         | 3.7%    |
| MDM     | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 20        | 36.36%  |
| de_DE   | 11        | 20%     |
| en_CA   | 7         | 12.73%  |
| en_GB   | 6         | 10.91%  |
| pt_BR   | 2         | 3.64%   |
| it_IT   | 2         | 3.64%   |
| en_AU   | 2         | 3.64%   |
| tr_TR   | 1         | 1.82%   |
| pl_PL   | 1         | 1.82%   |
| nl_NL   | 1         | 1.82%   |
| eu_ES   | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 35        | 63.64%  |
| EFI  | 20        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 47        | 85.45%  |
| Tmpfs | 6         | 10.91%  |
| Btrfs | 2         | 3.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 79.63%  |
| GPT     | 8         | 14.81%  |
| MBR     | 3         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 87.04%  |
| Yes       | 7         | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 90.74%  |
| Yes       | 5         | 9.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 15        | 27.78%  |
| Hewlett-Packard     | 7         | 12.96%  |
| ASUSTek Computer    | 6         | 11.11%  |
| Lenovo              | 5         | 9.26%   |
| Gigabyte Technology | 5         | 9.26%   |
| MSI                 | 4         | 7.41%   |
| HUAWEI              | 2         | 3.7%    |
| ASRock              | 2         | 3.7%    |
| Samsung Electronics | 1         | 1.85%   |
| Fujitsu             | 1         | 1.85%   |
| Flextronics         | 1         | 1.85%   |
| ELSA                | 1         | 1.85%   |
| Eii                 | 1         | 1.85%   |
| Apple               | 1         | 1.85%   |
| Alienware           | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V14-IIL 82C4                      | 2         | 3.7%    |
| Dell OptiPlex 7010                       | 2         | 3.7%    |
| Samsung R580                             | 1         | 1.85%   |
| MSI PPPPPPP-CCC#MMMMMMMM                 | 1         | 1.85%   |
| MSI MS-7915                              | 1         | 1.85%   |
| MSI MS-7721                              | 1         | 1.85%   |
| MSI MS-7693                              | 1         | 1.85%   |
| Lenovo ThinkPad T420 4236W1W             | 1         | 1.85%   |
| Lenovo IdeaPad Y530                      | 1         | 1.85%   |
| Lenovo IdeaCentre K430                   | 1         | 1.85%   |
| HUAWEI MateBook X                        | 1         | 1.85%   |
| HUAWEI KPL-W0X                           | 1         | 1.85%   |
| HP ProLiant DL360 G7                     | 1         | 1.85%   |
| HP Pavilion Laptop 15z-cw100             | 1         | 1.85%   |
| HP Pavilion All-in-One Desktop 27-ca1xxx | 1         | 1.85%   |
| HP Pavilion 17                           | 1         | 1.85%   |
| HP Laptop 17-ca2xxx                      | 1         | 1.85%   |
| HP ENVY Notebook                         | 1         | 1.85%   |
| HP Compaq 15                             | 1         | 1.85%   |
| Gigabyte Z390 AORUS ULTRA                | 1         | 1.85%   |
| Gigabyte GA-MA785GM-US2H                 | 1         | 1.85%   |
| Gigabyte GA-880GM-UD2H                   | 1         | 1.85%   |
| Gigabyte B85M-HD3                        | 1         | 1.85%   |
| Gigabyte 990FXA-UD5                      | 1         | 1.85%   |
| Fujitsu STYLISTIC Q665                   | 1         | 1.85%   |
| Flextronics 7238US00                     | 1         | 1.85%   |
| ELSA EA H410M-E                          | 1         | 1.85%   |
| Eii M1T                                  | 1         | 1.85%   |
| Dell XPS420                              | 1         | 1.85%   |
| Dell Precision Tower 3620                | 1         | 1.85%   |
| Dell OptiPlex 9020                       | 1         | 1.85%   |
| Dell OptiPlex 5070                       | 1         | 1.85%   |
| Dell Latitude E64406342Q0286/            | 1         | 1.85%   |
| Dell Latitude E5470                      | 1         | 1.85%   |
| Dell Latitude 3540                       | 1         | 1.85%   |
| Dell Inspiron One 2305                   | 1         | 1.85%   |
| Dell Inspiron 7790 AIO                   | 1         | 1.85%   |
| Dell Inspiron 660s                       | 1         | 1.85%   |
| Dell Inspiron 580                        | 1         | 1.85%   |
| Dell Inspiron 5565                       | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Dell Inspiron            | 6         | 11.11%  |
| Dell OptiPlex            | 4         | 7.41%   |
| HP Pavilion              | 3         | 5.56%   |
| Dell Latitude            | 3         | 5.56%   |
| Lenovo V14-IIL           | 2         | 3.7%    |
| Samsung R580             | 1         | 1.85%   |
| MSI PPPPPPP-CCC#MMMMMMMM | 1         | 1.85%   |
| MSI MS-7915              | 1         | 1.85%   |
| MSI MS-7721              | 1         | 1.85%   |
| MSI MS-7693              | 1         | 1.85%   |
| Lenovo ThinkPad          | 1         | 1.85%   |
| Lenovo IdeaPad           | 1         | 1.85%   |
| Lenovo IdeaCentre        | 1         | 1.85%   |
| HUAWEI MateBook          | 1         | 1.85%   |
| HUAWEI KPL-W0X           | 1         | 1.85%   |
| HP ProLiant              | 1         | 1.85%   |
| HP Laptop                | 1         | 1.85%   |
| HP ENVY                  | 1         | 1.85%   |
| HP Compaq                | 1         | 1.85%   |
| Gigabyte Z390            | 1         | 1.85%   |
| Gigabyte GA-MA785GM-US2H | 1         | 1.85%   |
| Gigabyte GA-880GM-UD2H   | 1         | 1.85%   |
| Gigabyte B85M-HD3        | 1         | 1.85%   |
| Gigabyte 990FXA-UD5      | 1         | 1.85%   |
| Fujitsu STYLISTIC        | 1         | 1.85%   |
| Flextronics 7238US00     | 1         | 1.85%   |
| ELSA EA                  | 1         | 1.85%   |
| Eii M1T                  | 1         | 1.85%   |
| Dell XPS420              | 1         | 1.85%   |
| Dell Precision           | 1         | 1.85%   |
| ASUS TUF                 | 1         | 1.85%   |
| ASUS PRIME               | 1         | 1.85%   |
| ASUS P5QC                | 1         | 1.85%   |
| ASUS N55SL               | 1         | 1.85%   |
| ASUS M5A97               | 1         | 1.85%   |
| ASUS K55VD               | 1         | 1.85%   |
| ASRock Z77               | 1         | 1.85%   |
| ASRock B450              | 1         | 1.85%   |
| Apple MacBookAir6        | 1         | 1.85%   |
| Alienware Aurora         | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 14.81%  |
| 2012 | 8         | 14.81%  |
| 2020 | 6         | 11.11%  |
| 2018 | 6         | 11.11%  |
| 2019 | 4         | 7.41%   |
| 2010 | 4         | 7.41%   |
| 2016 | 3         | 5.56%   |
| 2014 | 3         | 5.56%   |
| 2009 | 3         | 5.56%   |
| 2015 | 2         | 3.7%    |
| 2011 | 2         | 3.7%    |
| 2008 | 2         | 3.7%    |
| 2022 | 1         | 1.85%   |
| 2017 | 1         | 1.85%   |
| 2007 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 29        | 53.7%   |
| Notebook   | 21        | 38.89%  |
| All in one | 3         | 5.56%   |
| Server     | 1         | 1.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 32.73%  |
| 3.01-4.0   | 13        | 23.64%  |
| 8.01-16.0  | 12        | 21.82%  |
| 32.01-64.0 | 7         | 12.73%  |
| 16.01-24.0 | 5         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 24        | 40.68%  |
| 1.01-2.0 | 23        | 38.98%  |
| 4.01-8.0 | 6         | 10.17%  |
| 3.01-4.0 | 6         | 10.17%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 63.64%  |
| 2      | 10        | 18.18%  |
| 4      | 4         | 7.27%   |
| 3      | 4         | 7.27%   |
| 8      | 1         | 1.82%   |
| 5      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 51.85%  |
| Yes       | 26        | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 87.04%  |
| No        | 7         | 12.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 72.73%  |
| No        | 15        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 55.56%  |
| No        | 24        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 29.63%  |
| Germany     | 10        | 18.52%  |
| UK          | 7         | 12.96%  |
| Canada      | 7         | 12.96%  |
| Australia   | 3         | 5.56%   |
| Poland      | 2         | 3.7%    |
| Italy       | 2         | 3.7%    |
| Brazil      | 2         | 3.7%    |
| Uganda      | 1         | 1.85%   |
| Turkey      | 1         | 1.85%   |
| Switzerland | 1         | 1.85%   |
| Spain       | 1         | 1.85%   |
| Netherlands | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| London               | 2         | 3.51%   |
| Dallas               | 2         | 3.51%   |
| Berlin               | 2         | 3.51%   |
| Zurich               | 1         | 1.75%   |
| Weirton              | 1         | 1.75%   |
| Tacoma               | 1         | 1.75%   |
| Sydney               | 1         | 1.75%   |
| Stralsund            | 1         | 1.75%   |
| Steinfeld            | 1         | 1.75%   |
| Spanaway             | 1         | 1.75%   |
| Santurtzi            | 1         | 1.75%   |
| Saint John           | 1         | 1.75%   |
| Piotrkow Trybunalski | 1         | 1.75%   |
| Pinhalzinho          | 1         | 1.75%   |
| Palmopolis           | 1         | 1.75%   |
| Oschersleben         | 1         | 1.75%   |
| Oberhausen           | 1         | 1.75%   |
| Northborough         | 1         | 1.75%   |
| New York             | 1         | 1.75%   |
| Munich               | 1         | 1.75%   |
| Millers Creek        | 1         | 1.75%   |
| Melbourne            | 1         | 1.75%   |
| Mayen                | 1         | 1.75%   |
| Manitouwadge         | 1         | 1.75%   |
| Manchester           | 1         | 1.75%   |
| Los Angeles          | 1         | 1.75%   |
| Lodz                 | 1         | 1.75%   |
| Knoxville            | 1         | 1.75%   |
| Kitchener            | 1         | 1.75%   |
| Kansas City          | 1         | 1.75%   |
| Kampala              | 1         | 1.75%   |
| Jamestown            | 1         | 1.75%   |
| Izmir                | 1         | 1.75%   |
| Imperia              | 1         | 1.75%   |
| Hillegom             | 1         | 1.75%   |
| Helensburgh          | 1         | 1.75%   |
| Heidenrod            | 1         | 1.75%   |
| Glovertown           | 1         | 1.75%   |
| Freisbach            | 1         | 1.75%   |
| Etobicoke            | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 15        | 18     | 17.05%  |
| Samsung Electronics       | 11        | 15     | 12.5%   |
| WDC                       | 9         | 11     | 10.23%  |
| SanDisk                   | 9         | 9      | 10.23%  |
| Toshiba                   | 6         | 6      | 6.82%   |
| Crucial                   | 4         | 4      | 4.55%   |
| Unknown                   | 3         | 3      | 3.41%   |
| Kingston                  | 3         | 4      | 3.41%   |
| Hitachi                   | 3         | 3      | 3.41%   |
| JMicron Technology        | 2         | 2      | 2.27%   |
| Intenso                   | 2         | 2      | 2.27%   |
| Transcend                 | 1         | 1      | 1.14%   |
| T-FORCE                   | 1         | 1      | 1.14%   |
| SK hynix                  | 1         | 1      | 1.14%   |
| PNY                       | 1         | 1      | 1.14%   |
| Patriot                   | 1         | 1      | 1.14%   |
| Origin                    | 1         | 1      | 1.14%   |
| ORICO                     | 1         | 1      | 1.14%   |
| Micron/Crucial Technology | 1         | 1      | 1.14%   |
| Micron Technology         | 1         | 1      | 1.14%   |
| Maxtor                    | 1         | 1      | 1.14%   |
| LITEONIT                  | 1         | 1      | 1.14%   |
| LITEON                    | 1         | 2      | 1.14%   |
| Lite-On Technology        | 1         | 1      | 1.14%   |
| Leven                     | 1         | 1      | 1.14%   |
| KIOXIA                    | 1         | 1      | 1.14%   |
| Intel                     | 1         | 1      | 1.14%   |
| HGST                      | 1         | 1      | 1.14%   |
| China                     | 1         | 1      | 1.14%   |
| ASMT                      | 1         | 1      | 1.14%   |
| Apple                     | 1         | 1      | 1.14%   |
| A-DATA Technology         | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  128GB                      | 2         | 2.2%    |
| Toshiba MQ01ABD100 1TB                       | 2         | 2.2%    |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2.2%    |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2.2%    |
| SanDisk SSD PLUS 1000GB                      | 2         | 2.2%    |
| SanDisk NVMe SSD Drive 500GB                 | 2         | 2.2%    |
| Samsung NVMe SSD Drive 1TB                   | 2         | 2.2%    |
| Kingston SA400S37240G 240GB SSD              | 2         | 2.2%    |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1.1%    |
| WDC WD7501AAES-75W7A0 752GB                  | 1         | 1.1%    |
| WDC WD5000AADS-00L4B1 500GB                  | 1         | 1.1%    |
| WDC WD40EZRZ-00GXCB0 4TB                     | 1         | 1.1%    |
| WDC WD3200AAKS-75L9A0 320GB                  | 1         | 1.1%    |
| WDC WD2500BEVS-22UST0 250GB                  | 1         | 1.1%    |
| WDC WD1600AAJS-22PSA0 160GB                  | 1         | 1.1%    |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1.1%    |
| WDC WD10EZEX-00KUWA0 1TB                     | 1         | 1.1%    |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 1.1%    |
| Transcend TS64GMSA230S 64GB SSD              | 1         | 1.1%    |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.1%    |
| Toshiba MQ01ABF050M 500GB                    | 1         | 1.1%    |
| Toshiba HDWD130 3TB                          | 1         | 1.1%    |
| Toshiba DT01ACA050 500GB                     | 1         | 1.1%    |
| T-FORCE 1TB                                  | 1         | 1.1%    |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.1%    |
| Seagate ST9500325AS 500GB                    | 1         | 1.1%    |
| Seagate ST940210AS 40GB                      | 1         | 1.1%    |
| Seagate ST9320325AS 320GB                    | 1         | 1.1%    |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.1%    |
| Seagate ST3500418AS 500GB                    | 1         | 1.1%    |
| Seagate ST3320820AS 320GB                    | 1         | 1.1%    |
| Seagate ST3320620AS 320GB                    | 1         | 1.1%    |
| Seagate ST31000524AS 1TB                     | 1         | 1.1%    |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.1%    |
| Seagate Expansion Desk 6TB                   | 1         | 1.1%    |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB | 1         | 1.1%    |
| SanDisk SSD U110 128GB                       | 1         | 1.1%    |
| SanDisk SSD PLUS 480GB                       | 1         | 1.1%    |
| SanDisk SDSSDH3 512G                         | 1         | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 40%     |
| WDC                 | 8         | 10     | 22.86%  |
| Toshiba             | 5         | 5      | 14.29%  |
| Hitachi             | 3         | 3      | 8.57%   |
| Unknown             | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| Maxtor              | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| ASMT                | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 17.65%  |
| Samsung Electronics | 5         | 7      | 14.71%  |
| Crucial             | 4         | 4      | 11.76%  |
| Kingston            | 3         | 4      | 8.82%   |
| Intenso             | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| Seagate             | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Origin              | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| LITEON              | 1         | 2      | 2.94%   |
| Leven               | 1         | 1      | 2.94%   |
| JMicron Technology  | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 29        | 40     | 39.73%  |
| SSD     | 27        | 38     | 36.99%  |
| NVMe    | 12        | 16     | 16.44%  |
| Unknown | 3         | 3      | 4.11%   |
| MMC     | 2         | 2      | 2.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 73     | 69.12%  |
| NVMe | 12        | 16     | 17.65%  |
| SAS  | 7         | 8      | 10.29%  |
| MMC  | 2         | 2      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 53     | 60.34%  |
| 0.51-1.0   | 18        | 20     | 31.03%  |
| 1.01-2.0   | 2         | 2      | 3.45%   |
| 3.01-4.0   | 1         | 1      | 1.72%   |
| 2.01-3.0   | 1         | 1      | 1.72%   |
| 4.01-10.0  | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 34.55%  |
| 501-1000       | 12        | 21.82%  |
| 251-500        | 11        | 20%     |
| 51-100         | 4         | 7.27%   |
| More than 3000 | 3         | 5.45%   |
| 1001-2000      | 3         | 5.45%   |
| 21-50          | 2         | 3.64%   |
| 1-20           | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 35.59%  |
| 21-50          | 18        | 30.51%  |
| 251-500        | 8         | 13.56%  |
| 51-100         | 7         | 11.86%  |
| More than 3000 | 3         | 5.08%   |
| 101-250        | 2         | 3.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAKS-75L9A0 320GB | 1         | 2      | 50%     |
| Seagate ST31000524AS 1TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 100%    |

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
| Detected | 48        | 87     | 87.27%  |
| Works    | 5         | 9      | 9.09%   |
| Malfunc  | 2         | 3      | 3.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 47.22%  |
| AMD                          | 16        | 22.22%  |
| Samsung Electronics          | 7         | 9.72%   |
| ASMedia Technology           | 4         | 5.56%   |
| SanDisk                      | 3         | 4.17%   |
| Marvell Technology Group     | 2         | 2.78%   |
| Toshiba America Info Systems | 1         | 1.39%   |
| SK hynix                     | 1         | 1.39%   |
| Micron/Crucial Technology    | 1         | 1.39%   |
| Lite-On Technology           | 1         | 1.39%   |
| KIOXIA                       | 1         | 1.39%   |
| Hewlett-Packard              | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 9.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 4.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 4.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 4.94%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.47%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.23%   |
| SK hynix PC400 NVMe SSD                                                        | 1         | 1.23%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.23%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 1.23%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.23%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 1.23%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1         | 1.23%   |
| Lite-On CB1-SD256, CB1-SD512 NVMe SSD                                          | 1         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.23%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 43        | 61.43%  |
| NVMe | 12        | 17.14%  |
| IDE  | 9         | 12.86%  |
| RAID | 6         | 8.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 68.52%  |
| AMD    | 17        | 31.48%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 3.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 3.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 3.7%    |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 1.85%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 1.85%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 1.85%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 1.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1.85%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 1         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.85%   |
| Intel Core i3-9100T CPU @ 3.10GHz             | 1         | 1.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.85%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1         | 1.85%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.85%   |
| Intel 12th Gen Core i7-12700T                 | 1         | 1.85%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.85%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 1.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 11        | 20.37%  |
| Intel Core i5           | 10        | 18.52%  |
| Intel Core i3           | 7         | 12.96%  |
| AMD FX                  | 3         | 5.56%   |
| Other                   | 2         | 3.7%    |
| Intel Pentium Dual-Core | 2         | 3.7%    |
| Intel Core 2 Quad       | 2         | 3.7%    |
| AMD Ryzen 7             | 2         | 3.7%    |
| AMD Ryzen 5             | 2         | 3.7%    |
| AMD Ryzen 3             | 2         | 3.7%    |
| Intel Xeon              | 1         | 1.85%   |
| Intel Pentium           | 1         | 1.85%   |
| Intel Core M            | 1         | 1.85%   |
| Intel Celeron           | 1         | 1.85%   |
| AMD Phenom II X4        | 1         | 1.85%   |
| AMD Phenom              | 1         | 1.85%   |
| AMD E1                  | 1         | 1.85%   |
| AMD Athlon II X2        | 1         | 1.85%   |
| AMD A8                  | 1         | 1.85%   |
| AMD A4                  | 1         | 1.85%   |
| AMD A12                 | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 24        | 44.44%  |
| 2      | 23        | 42.59%  |
| 6      | 3         | 5.56%   |
| 12     | 2         | 3.7%    |
| 8      | 2         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 98.15%  |
| 2      | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 35        | 64.81%  |
| 1      | 19        | 35.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 30.36%  |
| 0x306a9    | 5         | 8.93%   |
| 0x40651    | 2         | 3.57%   |
| 0x306c3    | 2         | 3.57%   |
| 0x206a7    | 2         | 3.57%   |
| 0x08108109 | 2         | 3.57%   |
| 0x06001119 | 2         | 3.57%   |
| 0x06000852 | 2         | 3.57%   |
| 0x906ed    | 1         | 1.79%   |
| 0x90672    | 1         | 1.79%   |
| 0x806ec    | 1         | 1.79%   |
| 0x806e9    | 1         | 1.79%   |
| 0x706e5    | 1         | 1.79%   |
| 0x706a1    | 1         | 1.79%   |
| 0x6fb      | 1         | 1.79%   |
| 0x506e3    | 1         | 1.79%   |
| 0x406e3    | 1         | 1.79%   |
| 0x206c2    | 1         | 1.79%   |
| 0x20655    | 1         | 1.79%   |
| 0x20652    | 1         | 1.79%   |
| 0x1067a    | 1         | 1.79%   |
| 0x08701021 | 1         | 1.79%   |
| 0x08108102 | 1         | 1.79%   |
| 0x08101007 | 1         | 1.79%   |
| 0x07000110 | 1         | 1.79%   |
| 0x0700010f | 1         | 1.79%   |
| 0x06006118 | 1         | 1.79%   |
| 0x010000c9 | 1         | 1.79%   |
| 0x010000c8 | 1         | 1.79%   |
| 0x010000c7 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 7         | 12.96%  |
| KabyLake         | 6         | 11.11%  |
| Haswell          | 6         | 11.11%  |
| Piledriver       | 5         | 9.26%   |
| Zen+             | 4         | 7.41%   |
| Westmere         | 3         | 5.56%   |
| Skylake          | 3         | 5.56%   |
| K10              | 3         | 5.56%   |
| SandyBridge      | 2         | 3.7%    |
| Penryn           | 2         | 3.7%    |
| Jaguar           | 2         | 3.7%    |
| IceLake          | 2         | 3.7%    |
| Core             | 2         | 3.7%    |
| Zen 2            | 1         | 1.85%   |
| Zen              | 1         | 1.85%   |
| Goldmont plus    | 1         | 1.85%   |
| Excavator        | 1         | 1.85%   |
| CometLake        | 1         | 1.85%   |
| Broadwell        | 1         | 1.85%   |
| Alderlake Hybrid | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 43.55%  |
| Nvidia | 18        | 29.03%  |
| AMD    | 17        | 27.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 4.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 4.84%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 3.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 3.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 3.23%   |
| Intel HD Graphics 530                                                       | 2         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 3.23%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2         | 3.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 3.23%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.61%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.61%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 1.61%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 1.61%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1         | 1.61%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 1.61%   |
| Nvidia GK107GL [Quadro K2000D]                                              | 1         | 1.61%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1         | 1.61%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                           | 1         | 1.61%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 1.61%   |
| Nvidia GF119M [GeForce 610M]                                                | 1         | 1.61%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                        | 1         | 1.61%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1         | 1.61%   |
| Nvidia G96CM [GeForce 9600M GS]                                             | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.61%   |
| Intel HD Graphics 620                                                       | 1         | 1.61%   |
| Intel HD Graphics 5300                                                      | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.61%   |
| Intel AlderLake-S GT1                                                       | 1         | 1.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 1.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 37.5%   |
| 1 x AMD        | 17        | 30.36%  |
| 1 x Nvidia     | 15        | 26.79%  |
| Intel + Nvidia | 3         | 5.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 87.27%  |
| Proprietary | 6         | 10.91%  |
| Unknown     | 1         | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 50.91%  |
| 1.01-2.0   | 12        | 21.82%  |
| 0.01-0.5   | 8         | 14.55%  |
| 0.51-1.0   | 4         | 7.27%   |
| 7.01-8.0   | 1         | 1.82%   |
| 5.01-6.0   | 1         | 1.82%   |
| 3.01-4.0   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 6         | 11.11%  |
| Samsung Electronics     | 5         | 9.26%   |
| LG Display              | 5         | 9.26%   |
| Hewlett-Packard         | 4         | 7.41%   |
| Goldstar                | 4         | 7.41%   |
| Chimei Innolux          | 4         | 7.41%   |
| AU Optronics            | 3         | 5.56%   |
| Acer                    | 3         | 5.56%   |
| BOE                     | 2         | 3.7%    |
| BenQ                    | 2         | 3.7%    |
| AOC                     | 2         | 3.7%    |
| Vizio                   | 1         | 1.85%   |
| Toshiba                 | 1         | 1.85%   |
| Sony                    | 1         | 1.85%   |
| Sharp                   | 1         | 1.85%   |
| Ruijiang                | 1         | 1.85%   |
| Panasonic               | 1         | 1.85%   |
| LG Electronics          | 1         | 1.85%   |
| HannStar                | 1         | 1.85%   |
| Gateway                 | 1         | 1.85%   |
| Element                 | 1         | 1.85%   |
| Chi Mei Optoelectronics | 1         | 1.85%   |
| AUS                     | 1         | 1.85%   |
| ASUSTek Computer        | 1         | 1.85%   |
| Apple                   | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 1.82%   |
| Toshiba LCD Monitor TV 1920x1080                                         | 1         | 1.82%   |
| Sony TV SNYDC01 1360x768                                                 | 1         | 1.82%   |
| Sharp LQ116M1JW02 SHP1440 1920x1080 256x144mm 11.6-inch                  | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SMS27A850T 2560x1440                     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 1.82%   |
| Ruijiang RJT HDMI RJT1200 1920x1080 320x180mm 14.5-inch                  | 1         | 1.82%   |
| Panasonic TV MEIC135 1920x1080 698x392mm 31.5-inch                       | 1         | 1.82%   |
| LG Electronics LCD Monitor LG IPS FULLHD                                 | 1         | 1.82%   |
| LG Electronics LCD Monitor LG HDR 4K 7360x2160                           | 1         | 1.82%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                              | 1         | 1.82%   |
| Hewlett-Packard LCD Monitor 2310 1920x1080                               | 1         | 1.82%   |
| Hewlett-Packard LCD Monitor 2009                                         | 1         | 1.82%   |
| Hewlett-Packard Contino HPN404C 1920x1080 597x366mm 27.6-inch            | 1         | 1.82%   |
| HannStar Hanns.G HH241 HSD2275 1920x1080 521x293mm 23.5-inch             | 1         | 1.82%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                     | 1         | 1.82%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                      | 1         | 1.82%   |
| Goldstar E2050 GSM4EAD 1600x900 443x249mm 20.0-inch                      | 1         | 1.82%   |
| Goldstar 32LG3000 GSM75F0 1920x1080 700x390mm 31.5-inch                  | 1         | 1.82%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                    | 1         | 1.82%   |
| Element ELSW3917BF ELE6308 1366x768 1365x768mm 61.7-inch                 | 1         | 1.82%   |
| Dell ST2420L DELA067 1920x1080 531x299mm 24.0-inch                       | 1         | 1.82%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                        | 1         | 1.82%   |
| Dell P2217H DELA0D7 1920x1080 476x267mm 21.5-inch                        | 1         | 1.82%   |
| Dell LCD Monitor E228WFP                                                 | 1         | 1.82%   |
| Dell Inspiron 7790 DEL93FF 1920x1080 510x287mm 23.0-inch                 | 1         | 1.82%   |
| Dell 23" AIO DELB123 1920x1080 510x287mm 23.0-inch                       | 1         | 1.82%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1746 1600x900 382x214mm 17.2-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 26        | 50%     |
| 1366x768 (WXGA)  | 7         | 13.46%  |
| 3840x2160 (4K)   | 4         | 7.69%   |
| 1600x900 (HD+)   | 3         | 5.77%   |
| 2560x1440 (QHD)  | 2         | 3.85%   |
| 1360x768         | 2         | 3.85%   |
| Unknown          | 2         | 3.85%   |
| 7360x2160        | 1         | 1.92%   |
| 3840x2400        | 1         | 1.92%   |
| 3120x1050        | 1         | 1.92%   |
| 2160x1440        | 1         | 1.92%   |
| 1440x900 (WXGA+) | 1         | 1.92%   |
| 1280x800 (WXGA)  | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 17.65%  |
| 23      | 7         | 13.73%  |
| Unknown | 6         | 11.76%  |
| 14      | 4         | 7.84%   |
| 13      | 4         | 7.84%   |
| 31      | 3         | 5.88%   |
| 27      | 3         | 5.88%   |
| 21      | 3         | 5.88%   |
| 72      | 2         | 3.92%   |
| 17      | 2         | 3.92%   |
| 86      | 1         | 1.96%   |
| 61      | 1         | 1.96%   |
| 38      | 1         | 1.96%   |
| 24      | 1         | 1.96%   |
| 20      | 1         | 1.96%   |
| 19      | 1         | 1.96%   |
| 16      | 1         | 1.96%   |
| 11      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 26.92%  |
| 501-600     | 10        | 19.23%  |
| Unknown     | 6         | 11.54%  |
| 601-700     | 5         | 9.62%   |
| 401-500     | 5         | 9.62%   |
| 351-400     | 4         | 7.69%   |
| 201-300     | 3         | 5.77%   |
| 1501-2000   | 3         | 5.77%   |
| 801-900     | 1         | 1.92%   |
| 1001-1500   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 75%     |
| Unknown | 6         | 12.5%   |
| 16/10   | 5         | 10.42%  |
| 3/2     | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 9         | 17.65%  |
| 101-110        | 9         | 17.65%  |
| 81-90          | 7         | 13.73%  |
| Unknown        | 6         | 11.76%  |
| More than 1000 | 4         | 7.84%   |
| 151-200        | 4         | 7.84%   |
| 351-500        | 3         | 5.88%   |
| 301-350        | 3         | 5.88%   |
| 121-130        | 3         | 5.88%   |
| 71-80          | 1         | 1.96%   |
| 51-60          | 1         | 1.96%   |
| 501-1000       | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 20        | 38.46%  |
| 121-160       | 10        | 19.23%  |
| 101-120       | 9         | 17.31%  |
| Unknown       | 6         | 11.54%  |
| 1-50          | 4         | 7.69%   |
| 161-240       | 2         | 3.85%   |
| More than 240 | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 89.09%  |
| 2     | 3         | 5.45%   |
| 3     | 2         | 3.64%   |
| 0     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 28        | 35%     |
| Intel                           | 22        | 27.5%   |
| Qualcomm Atheros                | 11        | 13.75%  |
| Broadcom                        | 6         | 7.5%    |
| Qualcomm Atheros Communications | 2         | 2.5%    |
| Broadcom Limited                | 2         | 2.5%    |
| TP-Link                         | 1         | 1.25%   |
| Ralink Technology               | 1         | 1.25%   |
| Ralink                          | 1         | 1.25%   |
| MediaTek                        | 1         | 1.25%   |
| Marvell Technology Group        | 1         | 1.25%   |
| Edimax Technology               | 1         | 1.25%   |
| D-Link System                   | 1         | 1.25%   |
| D-Link                          | 1         | 1.25%   |
| AVM                             | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 20        | 21.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 5         | 5.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 3         | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 3.26%   |
| Intel Wireless 7265                                                                  | 3         | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 3         | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 2         | 2.17%   |
| Intel Wireless-AC 9260                                                               | 2         | 2.17%   |
| Intel Ethernet Connection I217-LM                                                    | 2         | 2.17%   |
| Intel Ethernet Connection (7) I219-V                                                 | 2         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                                | 2         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 2.17%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 1.09%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 1         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 1         | 1.09%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 1.09%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 1.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                             | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 1         | 1.09%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]               | 1         | 1.09%   |
| MediaTek WiFi                                                                        | 1         | 1.09%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 1.09%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 1.09%   |
| Intel Wireless 8260                                                                  | 1         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                                  | 1         | 1.09%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                                | 1         | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                                 | 1         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 34.09%  |
| Qualcomm Atheros                | 8         | 18.18%  |
| Realtek Semiconductor           | 6         | 13.64%  |
| Broadcom                        | 4         | 9.09%   |
| Qualcomm Atheros Communications | 2         | 4.55%   |
| TP-Link                         | 1         | 2.27%   |
| Ralink Technology               | 1         | 2.27%   |
| Ralink                          | 1         | 2.27%   |
| MediaTek                        | 1         | 2.27%   |
| Edimax Technology               | 1         | 2.27%   |
| D-Link System                   | 1         | 2.27%   |
| D-Link                          | 1         | 2.27%   |
| Broadcom Limited                | 1         | 2.27%   |
| AVM                             | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 3         | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 6.67%   |
| Intel Wireless 7265                                                                  | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 2         | 4.44%   |
| Intel Wireless-AC 9260                                                               | 2         | 4.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 4.44%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 2.22%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 2.22%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 2.22%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 2.22%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 2.22%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]               | 1         | 2.22%   |
| MediaTek WiFi                                                                        | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 2.22%   |
| Intel Wireless 8260                                                                  | 1         | 2.22%   |
| Intel Wi-Fi 6 AX200                                                                  | 1         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 2.22%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 2.22%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                             | 1         | 2.22%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 1         | 2.22%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 2.22%   |
| Broadcom Network controller                                                          | 1         | 2.22%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                 | 1         | 2.22%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 1         | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 1         | 2.22%   |
| AVM FRITZ!WLAN AC 860                                                                | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 57.45%  |
| Intel                    | 12        | 25.53%  |
| Qualcomm Atheros         | 4         | 8.51%   |
| Broadcom                 | 2         | 4.26%   |
| Marvell Technology Group | 1         | 2.13%   |
| Broadcom Limited         | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 20        | 42.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 10.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 6.38%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 4.26%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 4.26%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 2.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 2.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 2.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 2.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 2.13%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.13%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 2.13%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 2.13%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 2.13%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 1         | 2.13%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 54.02%  |
| WiFi     | 40        | 45.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 51.79%  |
| WiFi     | 27        | 48.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 51.85%  |
| 1     | 25        | 46.3%   |
| 4     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 70.91%  |
| Yes  | 16        | 29.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 38.71%  |
| Realtek Semiconductor           | 5         | 16.13%  |
| Broadcom                        | 5         | 16.13%  |
| Qualcomm Atheros Communications | 3         | 9.68%   |
| IMC Networks                    | 1         | 3.23%   |
| Dell                            | 1         | 3.23%   |
| Cambridge Silicon Radio         | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |
| Apple                           | 1         | 3.23%   |
| Actions                         | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 16.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 12.9%   |
| Realtek Bluetooth Radio                             | 2         | 6.45%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.23%   |
| Intel AX200 Bluetooth                               | 1         | 3.23%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 3.23%   |
| Dell BT Mini-Receiver                               | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 3.23%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 3.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.23%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.23%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.23%   |
| Actions general adapter                             | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 36        | 45.57%  |
| AMD                 | 22        | 27.85%  |
| Nvidia              | 16        | 20.25%  |
| Creative Labs       | 2         | 2.53%   |
| ROCCAT              | 1         | 1.27%   |
| C-Media Electronics | 1         | 1.27%   |
| Unknown             | 1         | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 7         | 7.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6         | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 5         | 5.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4         | 4.26%   |
| AMD FCH Azalia Controller                                                                       | 4         | 4.26%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 3         | 3.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 3         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3         | 3.19%   |
| AMD Kabini HDMI/DP Audio                                                                        | 3         | 3.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2         | 2.13%   |
| Nvidia GF116 High Definition Audio Controller                                                   | 2         | 2.13%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 2         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2         | 2.13%   |
| Intel 8 Series HD Audio Controller                                                              | 2         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2         | 2.13%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2         | 2.13%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                | 2         | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2         | 2.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2         | 2.13%   |
| ROCCAT Elo 7.1 USB                                                                              | 1         | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia High Definition Audio Controller                                                         | 1         | 1.06%   |
| Nvidia GT216 HDMI Audio Controller                                                              | 1         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1         | 1.06%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 1         | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 1         | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 1         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                           | 1         | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                    | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 1         | 1.06%   |
| Intel Broadwell-U Audio Controller                                                              | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 40%     |
| Unknown             | 1         | 10%     |
| Team                | 1         | 10%     |
| Smart               | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| Micron Technology   | 1         | 10%     |
| Kingston            | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 1066MT/s                      | 1         | 10%     |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 1         | 10%     |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM 1333MT/s               | 1         | 10%     |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1         | 10%     |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1         | 10%     |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 10%     |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 10%     |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 10%     |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 1         | 10%     |
| Kingston RAM K531R8-HYA 4GB DIMM DDR3 1600MT/s               | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 4         | 50%     |
| DDR3    | 3         | 37.5%   |
| Unknown | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 5         | 55.56%  |
| SODIMM       | 3         | 33.33%  |
| Row Of Chips | 1         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 3         | 33.33%  |
| 8192  | 2         | 22.22%  |
| 2048  | 2         | 22.22%  |
| 32768 | 1         | 11.11%  |
| 16384 | 1         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 2         | 20%     |
| 2667  | 2         | 20%     |
| 1800  | 2         | 20%     |
| 3600  | 1         | 10%     |
| 1600  | 1         | 10%     |
| 1333  | 1         | 10%     |
| 1066  | 1         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Omnidirectional Control Technology | 1         | 33.33%  |
| Dymo-CoStar                        | 1         | 33.33%  |
| Canon                              | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Omnidirectional Control USB-Parallel Bridge | 1         | 33.33%  |
| Dymo-CoStar LabelWriter 400                 | 1         | 33.33%  |
| Canon PIXMA MX920 Series                    | 1         | 33.33%  |

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
| Chicony Electronics                    | 5         | 19.23%  |
| Suyin                                  | 3         | 11.54%  |
| Realtek Semiconductor                  | 3         | 11.54%  |
| Microdia                               | 3         | 11.54%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 11.54%  |
| IMC Networks                           | 2         | 7.69%   |
| Z-Star Microelectronics                | 1         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Sonix Technology                       | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Microsoft                              | 1         | 3.85%   |
| Logitech                               | 1         | 3.85%   |
| Lite-On Technology                     | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 7.69%   |
| Z-Star WebCam SCB-1900N                                        | 1         | 3.85%   |
| Suyin UVC HD Webcam                                            | 1         | 3.85%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 3.85%   |
| Suyin HP Truevision HD                                         | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 3.85%   |
| Sonix USB 2.0 Camera                                           | 1         | 3.85%   |
| Realtek Laptop_Integrated_Webcam_HD                            | 1         | 3.85%   |
| Realtek Integrated_Webcam_FHD                                  | 1         | 3.85%   |
| Realtek FJ Camera                                              | 1         | 3.85%   |
| Quanta HP 5MP Camera                                           | 1         | 3.85%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 3.85%   |
| Microdia Integrated Camera                                     | 1         | 3.85%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 3.85%   |
| Logitech Webcam B500                                           | 1         | 3.85%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 3.85%   |
| IMC Networks Integrated Camera                                 | 1         | 3.85%   |
| IMC Networks Huawei Web Camera - HD                            | 1         | 3.85%   |
| Chicony UVC 1.00 device HD UVC WebCam                          | 1         | 3.85%   |
| Chicony Lenovo EasyCamera                                      | 1         | 3.85%   |
| Chicony Laptop_Integrated_Webcam_2M                            | 1         | 3.85%   |
| Chicony Integrated Camera                                      | 1         | 3.85%   |
| Chicony FJ 5M Camera                                           | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 2         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Broadcom 5880                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 47        | 85.45%  |
| 1     | 6         | 10.91%  |
| 3     | 1         | 1.82%   |
| 2     | 1         | 1.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 2         | 22.22%  |
| Fingerprint reader    | 2         | 22.22%  |
| Chipcard              | 2         | 22.22%  |
| Network               | 1         | 11.11%  |
| Net/wireless          | 1         | 11.11%  |
| Graphics card         | 1         | 11.11%  |

