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

Total: 87

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6220              | Notebook    | [a795975b1e](https://linux-hardware.org/?probe=a795975b1e) | Apr 02, 2024 |
| Unknown       | V00                         | Mini pc     | [c703749791](https://linux-hardware.org/?probe=c703749791) | Mar 21, 2024 |
| Samsung       | 950QDB                      | Convertible | [d491268c86](https://linux-hardware.org/?probe=d491268c86) | Mar 16, 2024 |
| Samsung       | 950QDB                      | Convertible | [8d4fd6acf0](https://linux-hardware.org/?probe=8d4fd6acf0) | Mar 14, 2024 |
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
| Makulu 2020              | 27        | 46.55%  |
| Makulu Build: 2021.12.15 | 6         | 10.34%  |
| Makulu 2021              | 4         | 6.9%    |
| Makulu Beta1             | 3         | 5.17%   |
| Makulu Bld-2022.08.19    | 2         | 3.45%   |
| Makulu Beta-2            | 2         | 3.45%   |
| Makulu Beta-1            | 2         | 3.45%   |
| Makulu 2022.12.29        | 2         | 3.45%   |
| Makulu Buildvar          | 1         | 1.72%   |
| Makulu Build: 2022.01.06 | 1         | 1.72%   |
| Makulu Bld-2022.12.04    | 1         | 1.72%   |
| Makulu Bld-2022.11.03    | 1         | 1.72%   |
| Makulu Bld-2022.08.10    | 1         | 1.72%   |
| Makulu 68                | 1         | 1.72%   |
| Makulu 2023.07.12        | 1         | 1.72%   |
| Makulu 2023.01.11        | 1         | 1.72%   |
| Makulu 20                | 1         | 1.72%   |
| Makulu 14                | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Makulu | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.8.0-44-generic       | 6         | 10.17%  |
| 5.11.0-41-generic      | 5         | 8.47%   |
| 5.10.0-8-amd64         | 4         | 6.78%   |
| 6.3.0-1-amd64          | 3         | 5.08%   |
| 5.4.0-42-generic       | 3         | 5.08%   |
| 5.11.0-43-generic      | 3         | 5.08%   |
| 6.0.0-5-amd64          | 2         | 3.39%   |
| 5.15.0-56-generic      | 2         | 3.39%   |
| 5.15.0-53-generic      | 2         | 3.39%   |
| 5.15.0-46-generic      | 2         | 3.39%   |
| 5.14.0-2-amd64         | 2         | 3.39%   |
| 6.7.1-060701-generic   | 1         | 1.69%   |
| 6.1.6-060106-generic   | 1         | 1.69%   |
| 6.1.11-060111-generic  | 1         | 1.69%   |
| 5.8.0-59-generic       | 1         | 1.69%   |
| 5.8.0-55-generic       | 1         | 1.69%   |
| 5.8.0-50-generic       | 1         | 1.69%   |
| 5.8.0-49-generic       | 1         | 1.69%   |
| 5.8.0-48-generic       | 1         | 1.69%   |
| 5.8.0-41-generic       | 1         | 1.69%   |
| 5.8.0-38-generic       | 1         | 1.69%   |
| 5.8.0-23-generic       | 1         | 1.69%   |
| 5.4.0-54-generic       | 1         | 1.69%   |
| 5.4.0-48-generic       | 1         | 1.69%   |
| 5.15.10-051510-generic | 1         | 1.69%   |
| 5.15.0-91-generic      | 1         | 1.69%   |
| 5.15.0-88-generic      | 1         | 1.69%   |
| 5.15.0-79-generic      | 1         | 1.69%   |
| 5.15.0-48-generic      | 1         | 1.69%   |
| 5.12.11-051211-generic | 1         | 1.69%   |
| 5.11.0-38-generic      | 1         | 1.69%   |
| 5.11.0-36-generic      | 1         | 1.69%   |
| 5.11.0-27-generic      | 1         | 1.69%   |
| 5.10.0-7-amd64         | 1         | 1.69%   |
| 5.10.0-3-amd64         | 1         | 1.69%   |
| 4.14.0-041400-generic  | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 14        | 23.73%  |
| 5.11.0  | 11        | 18.64%  |
| 5.15.0  | 10        | 16.95%  |
| 5.10.0  | 6         | 10.17%  |
| 5.4.0   | 5         | 8.47%   |
| 6.3.0   | 3         | 5.08%   |
| 6.0.0   | 2         | 3.39%   |
| 5.14.0  | 2         | 3.39%   |
| 6.7.1   | 1         | 1.69%   |
| 6.1.6   | 1         | 1.69%   |
| 6.1.11  | 1         | 1.69%   |
| 5.15.10 | 1         | 1.69%   |
| 5.12.11 | 1         | 1.69%   |
| 4.14.0  | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 14        | 24.14%  |
| 5.15    | 11        | 18.97%  |
| 5.11    | 11        | 18.97%  |
| 5.10    | 6         | 10.34%  |
| 5.4     | 5         | 8.62%   |
| 6.3     | 3         | 5.17%   |
| 6.0     | 2         | 3.45%   |
| 5.14    | 2         | 3.45%   |
| 6.7     | 1         | 1.72%   |
| 6.1     | 1         | 1.72%   |
| 5.12    | 1         | 1.72%   |
| 4.14    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| GNOME       | 38        | 66.67%  |
| X-Cinnamon  | 15        | 26.32%  |
| MakuluGameR | 2         | 3.51%   |
| Core        | 1         | 1.75%   |
| Cinnamon    | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 57        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 80.7%   |
| LightDM | 8         | 14.04%  |
| TDM     | 2         | 3.51%   |
| MDM     | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 21        | 36.21%  |
| de_DE   | 11        | 18.97%  |
| en_CA   | 7         | 12.07%  |
| en_GB   | 6         | 10.34%  |
| pt_BR   | 3         | 5.17%   |
| it_IT   | 2         | 3.45%   |
| en_AU   | 2         | 3.45%   |
| tr_TR   | 1         | 1.72%   |
| pl_PL   | 1         | 1.72%   |
| nl_NL   | 1         | 1.72%   |
| hu_HU   | 1         | 1.72%   |
| eu_ES   | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 38        | 65.52%  |
| EFI  | 20        | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 50        | 86.21%  |
| Tmpfs | 6         | 10.34%  |
| Btrfs | 2         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 82.46%  |
| GPT     | 7         | 12.28%  |
| MBR     | 3         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 87.72%  |
| Yes       | 7         | 12.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 92.98%  |
| Yes       | 4         | 7.02%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 16        | 28.07%  |
| Hewlett-Packard     | 7         | 12.28%  |
| ASUSTek Computer    | 6         | 10.53%  |
| Lenovo              | 5         | 8.77%   |
| Gigabyte Technology | 5         | 8.77%   |
| MSI                 | 4         | 7.02%   |
| Samsung Electronics | 2         | 3.51%   |
| HUAWEI              | 2         | 3.51%   |
| ASRock              | 2         | 3.51%   |
| Fujitsu             | 1         | 1.75%   |
| Flextronics         | 1         | 1.75%   |
| ELSA                | 1         | 1.75%   |
| Eii                 | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |
| Alienware           | 1         | 1.75%   |
| Acer                | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V14-IIL 82C4                      | 2         | 3.51%   |
| Dell OptiPlex 7010                       | 2         | 3.51%   |
| Samsung R580                             | 1         | 1.75%   |
| Samsung 950QDB                           | 1         | 1.75%   |
| MSI PPPPPPP-CCC#MMMMMMMM                 | 1         | 1.75%   |
| MSI MS-7915                              | 1         | 1.75%   |
| MSI MS-7721                              | 1         | 1.75%   |
| MSI MS-7693                              | 1         | 1.75%   |
| Lenovo ThinkPad T420 4236W1W             | 1         | 1.75%   |
| Lenovo IdeaPad Y530                      | 1         | 1.75%   |
| Lenovo IdeaCentre K430                   | 1         | 1.75%   |
| HUAWEI MateBook X                        | 1         | 1.75%   |
| HUAWEI KPL-W0X                           | 1         | 1.75%   |
| HP ProLiant DL360 G7                     | 1         | 1.75%   |
| HP Pavilion Laptop 15z-cw100             | 1         | 1.75%   |
| HP Pavilion All-in-One Desktop 27-ca1xxx | 1         | 1.75%   |
| HP Pavilion 17                           | 1         | 1.75%   |
| HP Laptop 17-ca2xxx                      | 1         | 1.75%   |
| HP ENVY Notebook                         | 1         | 1.75%   |
| HP Compaq 15                             | 1         | 1.75%   |
| Gigabyte Z390 AORUS ULTRA                | 1         | 1.75%   |
| Gigabyte GA-MA785GM-US2H                 | 1         | 1.75%   |
| Gigabyte GA-880GM-UD2H                   | 1         | 1.75%   |
| Gigabyte B85M-HD3                        | 1         | 1.75%   |
| Gigabyte 990FXA-UD5                      | 1         | 1.75%   |
| Fujitsu STYLISTIC Q665                   | 1         | 1.75%   |
| Flextronics 7238US00                     | 1         | 1.75%   |
| ELSA EA H410M-E                          | 1         | 1.75%   |
| Eii M1T                                  | 1         | 1.75%   |
| Dell XPS420                              | 1         | 1.75%   |
| Dell Precision Tower 3620                | 1         | 1.75%   |
| Dell OptiPlex 9020                       | 1         | 1.75%   |
| Dell OptiPlex 5070                       | 1         | 1.75%   |
| Dell Latitude E64406342Q0286/            | 1         | 1.75%   |
| Dell Latitude E6220                      | 1         | 1.75%   |
| Dell Latitude E5470                      | 1         | 1.75%   |
| Dell Latitude 3540                       | 1         | 1.75%   |
| Dell Inspiron One 2305                   | 1         | 1.75%   |
| Dell Inspiron 7790 AIO                   | 1         | 1.75%   |
| Dell Inspiron 660s                       | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Dell Inspiron            | 6         | 10.53%  |
| Dell OptiPlex            | 4         | 7.02%   |
| Dell Latitude            | 4         | 7.02%   |
| HP Pavilion              | 3         | 5.26%   |
| Lenovo V14-IIL           | 2         | 3.51%   |
| Samsung R580             | 1         | 1.75%   |
| Samsung 950QDB           | 1         | 1.75%   |
| MSI PPPPPPP-CCC#MMMMMMMM | 1         | 1.75%   |
| MSI MS-7915              | 1         | 1.75%   |
| MSI MS-7721              | 1         | 1.75%   |
| MSI MS-7693              | 1         | 1.75%   |
| Lenovo ThinkPad          | 1         | 1.75%   |
| Lenovo IdeaPad           | 1         | 1.75%   |
| Lenovo IdeaCentre        | 1         | 1.75%   |
| HUAWEI MateBook          | 1         | 1.75%   |
| HUAWEI KPL-W0X           | 1         | 1.75%   |
| HP ProLiant              | 1         | 1.75%   |
| HP Laptop                | 1         | 1.75%   |
| HP ENVY                  | 1         | 1.75%   |
| HP Compaq                | 1         | 1.75%   |
| Gigabyte Z390            | 1         | 1.75%   |
| Gigabyte GA-MA785GM-US2H | 1         | 1.75%   |
| Gigabyte GA-880GM-UD2H   | 1         | 1.75%   |
| Gigabyte B85M-HD3        | 1         | 1.75%   |
| Gigabyte 990FXA-UD5      | 1         | 1.75%   |
| Fujitsu STYLISTIC        | 1         | 1.75%   |
| Flextronics 7238US00     | 1         | 1.75%   |
| ELSA EA                  | 1         | 1.75%   |
| Eii M1T                  | 1         | 1.75%   |
| Dell XPS420              | 1         | 1.75%   |
| Dell Precision           | 1         | 1.75%   |
| ASUS TUF                 | 1         | 1.75%   |
| ASUS PRIME               | 1         | 1.75%   |
| ASUS P5QC                | 1         | 1.75%   |
| ASUS N55SL               | 1         | 1.75%   |
| ASUS M5A97               | 1         | 1.75%   |
| ASUS K55VD               | 1         | 1.75%   |
| ASRock Z77               | 1         | 1.75%   |
| ASRock B450              | 1         | 1.75%   |
| Apple MacBookAir6        | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 14.04%  |
| 2012 | 8         | 14.04%  |
| 2020 | 6         | 10.53%  |
| 2018 | 6         | 10.53%  |
| 2019 | 4         | 7.02%   |
| 2010 | 4         | 7.02%   |
| 2016 | 3         | 5.26%   |
| 2014 | 3         | 5.26%   |
| 2011 | 3         | 5.26%   |
| 2009 | 3         | 5.26%   |
| 2022 | 2         | 3.51%   |
| 2015 | 2         | 3.51%   |
| 2008 | 2         | 3.51%   |
| 2021 | 1         | 1.75%   |
| 2017 | 1         | 1.75%   |
| 2007 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 29        | 50.88%  |
| Notebook    | 22        | 38.6%   |
| All in one  | 3         | 5.26%   |
| Convertible | 1         | 1.75%   |
| Mini pc     | 1         | 1.75%   |
| Server      | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 31.03%  |
| 3.01-4.0   | 13        | 22.41%  |
| 8.01-16.0  | 13        | 22.41%  |
| 32.01-64.0 | 8         | 13.79%  |
| 16.01-24.0 | 6         | 10.34%  |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 24        | 38.71%  |
| 1.01-2.0 | 22        | 35.48%  |
| 3.01-4.0 | 9         | 14.52%  |
| 4.01-8.0 | 7         | 11.29%  |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 63.79%  |
| 2      | 11        | 18.97%  |
| 4      | 4         | 6.9%    |
| 3      | 4         | 6.9%    |
| 8      | 1         | 1.72%   |
| 5      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 54.39%  |
| Yes       | 26        | 45.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 85.96%  |
| No        | 8         | 14.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 74.14%  |
| No        | 15        | 25.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 57.89%  |
| No        | 24        | 42.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 28.07%  |
| Germany     | 10        | 17.54%  |
| Canada      | 8         | 14.04%  |
| UK          | 7         | 12.28%  |
| Brazil      | 3         | 5.26%   |
| Australia   | 3         | 5.26%   |
| Poland      | 2         | 3.51%   |
| Uganda      | 1         | 1.75%   |
| Turkey      | 1         | 1.75%   |
| Switzerland | 1         | 1.75%   |
| Spain       | 1         | 1.75%   |
| Netherlands | 1         | 1.75%   |
| Italy       | 1         | 1.75%   |
| Hungary     | 1         | 1.75%   |
| France      | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| London               | 2         | 3.33%   |
| Dallas               | 2         | 3.33%   |
| Berlin               | 2         | 3.33%   |
| Zurich               | 1         | 1.67%   |
| Weirton              | 1         | 1.67%   |
| Tacoma               | 1         | 1.67%   |
| Sydney               | 1         | 1.67%   |
| Stralsund            | 1         | 1.67%   |
| Steinfeld            | 1         | 1.67%   |
| Spanaway             | 1         | 1.67%   |
| Santurtzi            | 1         | 1.67%   |
| Saint John           | 1         | 1.67%   |
| Russell              | 1         | 1.67%   |
| Porto Alegre         | 1         | 1.67%   |
| Piotrkow Trybunalski | 1         | 1.67%   |
| Pinhalzinho          | 1         | 1.67%   |
| Paris                | 1         | 1.67%   |
| Palmopolis           | 1         | 1.67%   |
| Oschersleben         | 1         | 1.67%   |
| Oberhausen           | 1         | 1.67%   |
| Northborough         | 1         | 1.67%   |
| New York             | 1         | 1.67%   |
| Munich               | 1         | 1.67%   |
| Millers Creek        | 1         | 1.67%   |
| Melbourne            | 1         | 1.67%   |
| Mayen                | 1         | 1.67%   |
| Manitouwadge         | 1         | 1.67%   |
| Manchester           | 1         | 1.67%   |
| Los Angeles          | 1         | 1.67%   |
| Lodz                 | 1         | 1.67%   |
| Knoxville            | 1         | 1.67%   |
| Kitchener            | 1         | 1.67%   |
| Kansas City          | 1         | 1.67%   |
| Kampala              | 1         | 1.67%   |
| Jamestown            | 1         | 1.67%   |
| Izmir                | 1         | 1.67%   |
| Imperia              | 1         | 1.67%   |
| Hillegom             | 1         | 1.67%   |
| Helensburgh          | 1         | 1.67%   |
| Glovertown           | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 15        | 18     | 16.13%  |
| Samsung Electronics         | 12        | 16     | 12.9%   |
| WDC                         | 9         | 11     | 9.68%   |
| SanDisk                     | 9         | 9      | 9.68%   |
| Toshiba                     | 6         | 6      | 6.45%   |
| Unknown                     | 4         | 4      | 4.3%    |
| Crucial                     | 4         | 4      | 4.3%    |
| Kingston                    | 3         | 4      | 3.23%   |
| Hitachi                     | 3         | 3      | 3.23%   |
| LITEONIT                    | 2         | 2      | 2.15%   |
| JMicron Technology          | 2         | 2      | 2.15%   |
| Intenso                     | 2         | 2      | 2.15%   |
| Transcend                   | 1         | 1      | 1.08%   |
| T-FORCE                     | 1         | 1      | 1.08%   |
| SK hynix                    | 1         | 1      | 1.08%   |
| PNY                         | 1         | 1      | 1.08%   |
| Patriot                     | 1         | 1      | 1.08%   |
| Origin                      | 1         | 1      | 1.08%   |
| ORICO                       | 1         | 1      | 1.08%   |
| Micron/Crucial Technology   | 1         | 1      | 1.08%   |
| Micron Technology           | 1         | 1      | 1.08%   |
| Maxtor                      | 1         | 1      | 1.08%   |
| LITEON                      | 1         | 2      | 1.08%   |
| Lite-On Technology          | 1         | 1      | 1.08%   |
| Leven                       | 1         | 1      | 1.08%   |
| KIOXIA                      | 1         | 1      | 1.08%   |
| Kingston Technology Company | 1         | 2      | 1.08%   |
| Intel                       | 1         | 1      | 1.08%   |
| HGST                        | 1         | 1      | 1.08%   |
| Hewlett-Packard             | 1         | 1      | 1.08%   |
| China                       | 1         | 1      | 1.08%   |
| ASMT                        | 1         | 1      | 1.08%   |
| Apple                       | 1         | 1      | 1.08%   |
| A-DATA Technology           | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  128GB                      | 2         | 2.08%   |
| Toshiba MQ01ABD100 1TB                       | 2         | 2.08%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2.08%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2.08%   |
| SanDisk NVMe SSD Drive 500GB                 | 2         | 2.08%   |
| Samsung NVMe SSD Drive 1TB                   | 2         | 2.08%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 2.08%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1.04%   |
| WDC WD7501AAES-75W7A0 752GB                  | 1         | 1.04%   |
| WDC WD5000AADS-00L4B1 500GB                  | 1         | 1.04%   |
| WDC WD40EZRZ-00GXCB0 4TB                     | 1         | 1.04%   |
| WDC WD3200AAKS-75L9A0 320GB                  | 1         | 1.04%   |
| WDC WD2500BEVS-22UST0 250GB                  | 1         | 1.04%   |
| WDC WD1600AAJS-22PSA0 160GB                  | 1         | 1.04%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1.04%   |
| WDC WD10EZEX-00KUWA0 1TB                     | 1         | 1.04%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 1.04%   |
| Unknown Compact Flash 977MB                  | 1         | 1.04%   |
| Transcend TS64GMSA230S 64GB SSD              | 1         | 1.04%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.04%   |
| Toshiba MQ01ABF050M 500GB                    | 1         | 1.04%   |
| Toshiba HDWD130 3TB                          | 1         | 1.04%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1.04%   |
| T-FORCE 1TB                                  | 1         | 1.04%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.04%   |
| Seagate ST9500325AS 500GB                    | 1         | 1.04%   |
| Seagate ST940210AS 40GB                      | 1         | 1.04%   |
| Seagate ST9320325AS 320GB                    | 1         | 1.04%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.04%   |
| Seagate ST3500418AS 500GB                    | 1         | 1.04%   |
| Seagate ST3320820AS 320GB                    | 1         | 1.04%   |
| Seagate ST3320620AS 320GB                    | 1         | 1.04%   |
| Seagate ST31000524AS 1TB                     | 1         | 1.04%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.04%   |
| Seagate Expansion+ Desk 4TB                  | 1         | 1.04%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB | 1         | 1.04%   |
| SanDisk SSD U110 128GB                       | 1         | 1.04%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 17     | 37.84%  |
| WDC                 | 8         | 10     | 21.62%  |
| Toshiba             | 5         | 5      | 13.51%  |
| Hitachi             | 3         | 3      | 8.11%   |
| Unknown             | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| JMicron Technology  | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| ASMT                | 1         | 1      | 2.7%    |

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
| LITEONIT            | 2         | 2      | 5.88%   |
| Intenso             | 2         | 2      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| Transcend           | 1         | 1      | 2.94%   |
| Seagate             | 1         | 1      | 2.94%   |
| PNY                 | 1         | 1      | 2.94%   |
| Patriot             | 1         | 1      | 2.94%   |
| Origin              | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEON              | 1         | 2      | 2.94%   |
| Leven               | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 42     | 38.96%  |
| SSD     | 27        | 38     | 35.06%  |
| NVMe    | 14        | 19     | 18.18%  |
| Unknown | 4         | 4      | 5.19%   |
| MMC     | 2         | 2      | 2.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 74     | 65.75%  |
| NVMe | 14        | 19     | 19.18%  |
| SAS  | 9         | 10     | 12.33%  |
| MMC  | 2         | 2      | 2.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 55     | 61.67%  |
| 0.51-1.0   | 18        | 20     | 30%     |
| 3.01-4.0   | 2         | 2      | 3.33%   |
| 1.01-2.0   | 2         | 2      | 3.33%   |
| 2.01-3.0   | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 32.76%  |
| 251-500        | 13        | 22.41%  |
| 501-1000       | 13        | 22.41%  |
| 51-100         | 4         | 6.9%    |
| More than 3000 | 3         | 5.17%   |
| 1001-2000      | 3         | 5.17%   |
| 21-50          | 2         | 3.45%   |
| 1-20           | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 35.48%  |
| 21-50          | 19        | 30.65%  |
| 251-500        | 8         | 12.9%   |
| 51-100         | 7         | 11.29%  |
| More than 3000 | 3         | 4.84%   |
| 101-250        | 3         | 4.84%   |

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
| Detected | 53        | 93     | 88.33%  |
| Works    | 5         | 9      | 8.33%   |
| Malfunc  | 2         | 3      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 35        | 46.05%  |
| AMD                          | 17        | 22.37%  |
| Samsung Electronics          | 8         | 10.53%  |
| ASMedia Technology           | 4         | 5.26%   |
| SanDisk                      | 3         | 3.95%   |
| Marvell Technology Group     | 2         | 2.63%   |
| Toshiba America Info Systems | 1         | 1.32%   |
| SK hynix                     | 1         | 1.32%   |
| Micron/Crucial Technology    | 1         | 1.32%   |
| Lite-On Technology           | 1         | 1.32%   |
| KIOXIA                       | 1         | 1.32%   |
| Kingston Technology Company  | 1         | 1.32%   |
| Hewlett-Packard              | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 10.47%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 4.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 4.65%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 3.49%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 3.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 3.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.33%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.33%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 1.16%   |
| SK hynix PC400 NVMe SSD                                                        | 1         | 1.16%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.16%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.16%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 1.16%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.16%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.16%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 1.16%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1         | 1.16%   |
| Lite-On CB1-SD256, CB1-SD512 NVMe SSD                                          | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.16%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 1         | 1.16%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 1         | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 1.16%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.16%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.16%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 59.46%  |
| NVMe | 14        | 18.92%  |
| IDE  | 9         | 12.16%  |
| RAID | 7         | 9.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 39        | 68.42%  |
| AMD    | 18        | 31.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 3.51%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 3.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 3.51%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 1.75%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 1.75%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 1.75%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 1.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.75%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.75%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.75%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 1.75%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 1.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.75%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 1.75%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 1         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.75%   |
| Intel Core i3-9100T CPU @ 3.10GHz             | 1         | 1.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.75%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1         | 1.75%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.75%   |
| Intel 12th Gen Core i7-12700T                 | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.75%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 1.75%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 12        | 21.05%  |
| Intel Core i5           | 10        | 17.54%  |
| Intel Core i3           | 7         | 12.28%  |
| Other                   | 3         | 5.26%   |
| AMD Ryzen 5             | 3         | 5.26%   |
| AMD FX                  | 3         | 5.26%   |
| Intel Pentium Dual-Core | 2         | 3.51%   |
| Intel Core 2 Quad       | 2         | 3.51%   |
| AMD Ryzen 7             | 2         | 3.51%   |
| AMD Ryzen 3             | 2         | 3.51%   |
| Intel Xeon              | 1         | 1.75%   |
| Intel Pentium           | 1         | 1.75%   |
| Intel Core M            | 1         | 1.75%   |
| Intel Celeron           | 1         | 1.75%   |
| AMD Phenom II X4        | 1         | 1.75%   |
| AMD Phenom              | 1         | 1.75%   |
| AMD E1                  | 1         | 1.75%   |
| AMD Athlon II X2        | 1         | 1.75%   |
| AMD A8                  | 1         | 1.75%   |
| AMD A4                  | 1         | 1.75%   |
| AMD A12                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 25        | 43.86%  |
| 2      | 24        | 42.11%  |
| 6      | 4         | 7.02%   |
| 12     | 2         | 3.51%   |
| 8      | 2         | 3.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 98.25%  |
| 2      | 1         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 66.67%  |
| 1      | 19        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 33.9%   |
| 0x306a9    | 5         | 8.47%   |
| 0x40651    | 2         | 3.39%   |
| 0x306c3    | 2         | 3.39%   |
| 0x206a7    | 2         | 3.39%   |
| 0x08108109 | 2         | 3.39%   |
| 0x06001119 | 2         | 3.39%   |
| 0x06000852 | 2         | 3.39%   |
| 0x906ed    | 1         | 1.69%   |
| 0x90672    | 1         | 1.69%   |
| 0x806ec    | 1         | 1.69%   |
| 0x806e9    | 1         | 1.69%   |
| 0x706e5    | 1         | 1.69%   |
| 0x706a1    | 1         | 1.69%   |
| 0x6fb      | 1         | 1.69%   |
| 0x506e3    | 1         | 1.69%   |
| 0x406e3    | 1         | 1.69%   |
| 0x206c2    | 1         | 1.69%   |
| 0x20655    | 1         | 1.69%   |
| 0x20652    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08701021 | 1         | 1.69%   |
| 0x08108102 | 1         | 1.69%   |
| 0x08101007 | 1         | 1.69%   |
| 0x07000110 | 1         | 1.69%   |
| 0x0700010f | 1         | 1.69%   |
| 0x06006118 | 1         | 1.69%   |
| 0x010000c9 | 1         | 1.69%   |
| 0x010000c8 | 1         | 1.69%   |
| 0x010000c7 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 7         | 12.28%  |
| KabyLake         | 6         | 10.53%  |
| Haswell          | 6         | 10.53%  |
| Piledriver       | 5         | 8.77%   |
| Zen+             | 4         | 7.02%   |
| Westmere         | 3         | 5.26%   |
| Skylake          | 3         | 5.26%   |
| SandyBridge      | 3         | 5.26%   |
| K10              | 3         | 5.26%   |
| Penryn           | 2         | 3.51%   |
| Jaguar           | 2         | 3.51%   |
| IceLake          | 2         | 3.51%   |
| Core             | 2         | 3.51%   |
| Zen 3            | 1         | 1.75%   |
| Zen 2            | 1         | 1.75%   |
| Zen              | 1         | 1.75%   |
| TigerLake        | 1         | 1.75%   |
| Goldmont plus    | 1         | 1.75%   |
| Excavator        | 1         | 1.75%   |
| CometLake        | 1         | 1.75%   |
| Broadwell        | 1         | 1.75%   |
| Alderlake Hybrid | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 44.62%  |
| Nvidia | 18        | 27.69%  |
| AMD    | 18        | 27.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 4.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 4.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 3.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 3.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 3.08%   |
| Intel HD Graphics 530                                                       | 2         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 3.08%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2         | 3.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 3.08%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.54%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 1.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.54%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 1.54%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 1.54%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1         | 1.54%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 1.54%   |
| Nvidia GK107GL [Quadro K2000D]                                              | 1         | 1.54%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1         | 1.54%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                           | 1         | 1.54%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 1.54%   |
| Nvidia GF119M [GeForce 610M]                                                | 1         | 1.54%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                        | 1         | 1.54%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1         | 1.54%   |
| Nvidia G96CM [GeForce 9600M GS]                                             | 1         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 1.54%   |
| Intel HD Graphics 620                                                       | 1         | 1.54%   |
| Intel HD Graphics 5300                                                      | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.54%   |
| Intel AlderLake-S GT1                                                       | 1         | 1.54%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 38.98%  |
| 1 x AMD        | 18        | 30.51%  |
| 1 x Nvidia     | 15        | 25.42%  |
| Intel + Nvidia | 3         | 5.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 87.93%  |
| Proprietary | 6         | 10.34%  |
| Unknown     | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 53.45%  |
| 1.01-2.0   | 12        | 20.69%  |
| 0.01-0.5   | 8         | 13.79%  |
| 0.51-1.0   | 4         | 6.9%    |
| 7.01-8.0   | 1         | 1.72%   |
| 5.01-6.0   | 1         | 1.72%   |
| 3.01-4.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 14.04%  |
| Dell                    | 6         | 10.53%  |
| LG Display              | 5         | 8.77%   |
| Hewlett-Packard         | 4         | 7.02%   |
| Goldstar                | 4         | 7.02%   |
| Chimei Innolux          | 4         | 7.02%   |
| AU Optronics            | 3         | 5.26%   |
| Acer                    | 3         | 5.26%   |
| BOE                     | 2         | 3.51%   |
| BenQ                    | 2         | 3.51%   |
| AOC                     | 2         | 3.51%   |
| Vizio                   | 1         | 1.75%   |
| Toshiba                 | 1         | 1.75%   |
| Sony                    | 1         | 1.75%   |
| Sharp                   | 1         | 1.75%   |
| Ruijiang                | 1         | 1.75%   |
| Panasonic               | 1         | 1.75%   |
| LG Electronics          | 1         | 1.75%   |
| HannStar                | 1         | 1.75%   |
| Gateway                 | 1         | 1.75%   |
| Element                 | 1         | 1.75%   |
| Chi Mei Optoelectronics | 1         | 1.75%   |
| AUS                     | 1         | 1.75%   |
| ASUSTek Computer        | 1         | 1.75%   |
| Apple                   | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1         | 1.72%   |
| Toshiba LCD Monitor TV 1920x1080                                      | 1         | 1.72%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 1.72%   |
| Sharp LQ116M1JW02 SHP1440 1920x1080 256x144mm 11.6-inch               | 1         | 1.72%   |
| Samsung Electronics LS27AG32x SAM71DC 1920x1080 597x336mm 27.0-inch   | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SMS27A850T 2560x1440                  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 1.72%   |
| Ruijiang RJT HDMI RJT1200 1920x1080 320x180mm 14.5-inch               | 1         | 1.72%   |
| Panasonic TV MEIC135 1920x1080 698x392mm 31.5-inch                    | 1         | 1.72%   |
| LG Electronics LCD Monitor LG IPS FULLHD                              | 1         | 1.72%   |
| LG Electronics LCD Monitor LG HDR 4K 7360x2160                        | 1         | 1.72%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD04DA 1920x1080 344x194mm 15.5-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 1         | 1.72%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.72%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                           | 1         | 1.72%   |
| Hewlett-Packard LCD Monitor 2310 1920x1080                            | 1         | 1.72%   |
| Hewlett-Packard LCD Monitor 2009                                      | 1         | 1.72%   |
| Hewlett-Packard Contino HPN404C 1920x1080 597x366mm 27.6-inch         | 1         | 1.72%   |
| HannStar Hanns.G HH241 HSD2275 1920x1080 521x293mm 23.5-inch          | 1         | 1.72%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                  | 1         | 1.72%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                   | 1         | 1.72%   |
| Goldstar E2050 GSM4EAD 1600x900 443x249mm 20.0-inch                   | 1         | 1.72%   |
| Goldstar 32LG3000 GSM75F0 1920x1080 700x390mm 31.5-inch               | 1         | 1.72%   |
| Gateway FHX2300 GWY00BF 1920x1080 509x286mm 23.0-inch                 | 1         | 1.72%   |
| Element ELSW3917BF ELE6308 1366x768 1365x768mm 61.7-inch              | 1         | 1.72%   |
| Dell ST2420L DELA067 1920x1080 530x300mm 24.0-inch                    | 1         | 1.72%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                     | 1         | 1.72%   |
| Dell P2217H DELA0D7 1920x1080 476x267mm 21.5-inch                     | 1         | 1.72%   |
| Dell LCD Monitor E228WFP                                              | 1         | 1.72%   |
| Dell INSPIRON ONE DELB123 1920x1080 510x287mm 23.0-inch               | 1         | 1.72%   |
| Dell Inspiron 7790 DEL93FF 1920x1080 510x287mm 23.0-inch              | 1         | 1.72%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1746 1600x900 382x214mm 17.2-inch       | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 28        | 50.91%  |
| 1366x768 (WXGA)  | 8         | 14.55%  |
| 3840x2160 (4K)   | 4         | 7.27%   |
| 1600x900 (HD+)   | 3         | 5.45%   |
| 2560x1440 (QHD)  | 2         | 3.64%   |
| 1360x768         | 2         | 3.64%   |
| Unknown          | 2         | 3.64%   |
| 7360x2160        | 1         | 1.82%   |
| 3840x2400        | 1         | 1.82%   |
| 3120x1050        | 1         | 1.82%   |
| 2160x1440        | 1         | 1.82%   |
| 1440x900 (WXGA+) | 1         | 1.82%   |
| 1280x800 (WXGA)  | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 20.37%  |
| 23      | 7         | 12.96%  |
| Unknown | 6         | 11.11%  |
| 27      | 4         | 7.41%   |
| 14      | 4         | 7.41%   |
| 13      | 4         | 7.41%   |
| 31      | 3         | 5.56%   |
| 21      | 3         | 5.56%   |
| 72      | 2         | 3.7%    |
| 17      | 2         | 3.7%    |
| 86      | 1         | 1.85%   |
| 61      | 1         | 1.85%   |
| 38      | 1         | 1.85%   |
| 24      | 1         | 1.85%   |
| 20      | 1         | 1.85%   |
| 19      | 1         | 1.85%   |
| 16      | 1         | 1.85%   |
| 11      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 27.27%  |
| 501-600     | 11        | 20%     |
| Unknown     | 6         | 10.91%  |
| 601-700     | 5         | 9.09%   |
| 401-500     | 5         | 9.09%   |
| 351-400     | 5         | 9.09%   |
| 201-300     | 3         | 5.45%   |
| 1501-2000   | 3         | 5.45%   |
| 801-900     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 39        | 76.47%  |
| Unknown | 6         | 11.76%  |
| 16/10   | 5         | 9.8%    |
| 3/2     | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 20.37%  |
| 201-250        | 9         | 16.67%  |
| 81-90          | 7         | 12.96%  |
| Unknown        | 6         | 11.11%  |
| More than 1000 | 4         | 7.41%   |
| 301-350        | 4         | 7.41%   |
| 151-200        | 4         | 7.41%   |
| 351-500        | 3         | 5.56%   |
| 121-130        | 3         | 5.56%   |
| 71-80          | 1         | 1.85%   |
| 51-60          | 1         | 1.85%   |
| 501-1000       | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 22        | 40%     |
| 121-160       | 11        | 20%     |
| 101-120       | 9         | 16.36%  |
| Unknown       | 6         | 10.91%  |
| 1-50          | 4         | 7.27%   |
| 161-240       | 2         | 3.64%   |
| More than 240 | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 89.66%  |
| 2     | 3         | 5.17%   |
| 3     | 2         | 3.45%   |
| 0     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 34.52%  |
| Intel                           | 24        | 28.57%  |
| Qualcomm Atheros                | 11        | 13.1%   |
| Broadcom                        | 6         | 7.14%   |
| Ralink Technology               | 2         | 2.38%   |
| Qualcomm Atheros Communications | 2         | 2.38%   |
| Broadcom Limited                | 2         | 2.38%   |
| TP-Link                         | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |
| MediaTek                        | 1         | 1.19%   |
| Marvell Technology Group        | 1         | 1.19%   |
| Edimax Technology               | 1         | 1.19%   |
| D-Link System                   | 1         | 1.19%   |
| D-Link                          | 1         | 1.19%   |
| AVM                             | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller               | 21        | 21.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 5         | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 4         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 3         | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 3.06%   |
| Intel Wireless 7265                                                                  | 3         | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 2         | 2.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 2         | 2.04%   |
| Intel Ethernet Connection I217-LM                                                    | 2         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                                                 | 2         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                                                | 2         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 2.04%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 1.02%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                                    | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 1         | 1.02%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 1.02%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.02%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 1.02%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                             | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 1.02%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                       | 1         | 1.02%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]               | 1         | 1.02%   |
| MediaTek WiFi                                                                        | 1         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 1.02%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 1.02%   |
| Intel Wireless 8260                                                                  | 1         | 1.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 1         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                                  | 1         | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 35.42%  |
| Qualcomm Atheros                | 8         | 16.67%  |
| Realtek Semiconductor           | 7         | 14.58%  |
| Broadcom                        | 4         | 8.33%   |
| Ralink Technology               | 2         | 4.17%   |
| Qualcomm Atheros Communications | 2         | 4.17%   |
| TP-Link                         | 1         | 2.08%   |
| Ralink                          | 1         | 2.08%   |
| MediaTek                        | 1         | 2.08%   |
| Edimax Technology               | 1         | 2.08%   |
| D-Link System                   | 1         | 2.08%   |
| D-Link                          | 1         | 2.08%   |
| Broadcom Limited                | 1         | 2.08%   |
| AVM                             | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 3         | 6.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 6.12%   |
| Intel Wireless 7265                                                                  | 3         | 6.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 2         | 4.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 2         | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 4.08%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 2.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 2.04%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 2.04%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 2.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 2.04%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 2.04%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 2.04%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]               | 1         | 2.04%   |
| MediaTek WiFi                                                                        | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                                           | 1         | 2.04%   |
| Intel Wireless 8260                                                                  | 1         | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                                  | 1         | 2.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 2.04%   |
| Intel Centrino Advanced-N 6235                                                       | 1         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 1         | 2.04%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                             | 1         | 2.04%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 1         | 2.04%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 2.04%   |
| Broadcom Network controller                                                          | 1         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                 | 1         | 2.04%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 1         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 1         | 2.04%   |
| AVM FRITZ!WLAN AC 860                                                                | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 28        | 57.14%  |
| Intel                    | 13        | 26.53%  |
| Qualcomm Atheros         | 4         | 8.16%   |
| Broadcom                 | 2         | 4.08%   |
| Marvell Technology Group | 1         | 2.04%   |
| Broadcom Limited         | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 21        | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 10.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 8.16%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 4.08%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 4.08%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 4.08%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 2.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 2.04%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 2.04%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 2.04%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 2.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 2.04%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 1         | 2.04%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 53.26%  |
| WiFi     | 43        | 46.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 30        | 50.85%  |
| WiFi     | 29        | 49.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 52.63%  |
| 1     | 26        | 45.61%  |
| 4     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 70.69%  |
| Yes  | 17        | 29.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 38.24%  |
| Realtek Semiconductor           | 6         | 17.65%  |
| Broadcom                        | 5         | 14.71%  |
| Qualcomm Atheros Communications | 3         | 8.82%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| IMC Networks                    | 1         | 2.94%   |
| Dell                            | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |
| Apple                           | 1         | 2.94%   |
| Actions                         | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 11.76%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 11.76%  |
| Intel Bluetooth wireless interface                  | 3         | 8.82%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.88%   |
| Intel Bluetooth Device                              | 2         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.94%   |
| Intel AX210 Bluetooth                               | 1         | 2.94%   |
| Intel AX200 Bluetooth                               | 1         | 2.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.94%   |
| Dell BT Mini-Receiver                               | 1         | 2.94%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 2.94%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.94%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.94%   |
| Actions general adapter                             | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 38        | 46.34%  |
| AMD                 | 23        | 28.05%  |
| Nvidia              | 16        | 19.51%  |
| Creative Labs       | 2         | 2.44%   |
| ROCCAT              | 1         | 1.22%   |
| C-Media Electronics | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 7         | 7.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6         | 6.12%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 6         | 6.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4         | 4.08%   |
| AMD FCH Azalia Controller                                                                       | 4         | 4.08%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 3         | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 3         | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3         | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3         | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 3         | 3.06%   |
| AMD Kabini HDMI/DP Audio                                                                        | 3         | 3.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 2         | 2.04%   |
| Nvidia GF116 High Definition Audio Controller                                                   | 2         | 2.04%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 2         | 2.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                              | 2         | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2         | 2.04%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2         | 2.04%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                | 2         | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2         | 2.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 2         | 2.04%   |
| ROCCAT Elo 7.1 USB                                                                              | 1         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia High Definition Audio Controller                                                         | 1         | 1.02%   |
| Nvidia GT216 HDMI Audio Controller                                                              | 1         | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 1         | 1.02%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 1         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 1         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                     | 1         | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 1         | 1.02%   |
| Intel Haswell-ULT HD Audio Controller                                                           | 1         | 1.02%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                    | 1         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 1         | 1.02%   |

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
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s          | 1         | 10%     |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s          | 1         | 10%     |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 10%     |
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
| Chicony Electronics                    | 5         | 17.86%  |
| Suyin                                  | 3         | 10.71%  |
| Realtek Semiconductor                  | 3         | 10.71%  |
| Microdia                               | 3         | 10.71%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10.71%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| IMC Networks                           | 2         | 7.14%   |
| Z-Star Microelectronics                | 1         | 3.57%   |
| Sonix Technology                       | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 3.57%   |
| Quanta                                 | 1         | 3.57%   |
| Microsoft                              | 1         | 3.57%   |
| Logitech                               | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 7.14%   |
| Z-Star WebCam SCB-1900N                                        | 1         | 3.57%   |
| Suyin UVC HD Webcam                                            | 1         | 3.57%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 3.57%   |
| Suyin HP Truevision HD                                         | 1         | 3.57%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 3.57%   |
| Sonix USB 2.0 Camera                                           | 1         | 3.57%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 3.57%   |
| Realtek Integrated_Webcam_FHD                                  | 1         | 3.57%   |
| Realtek Integrated Webcam HD                                   | 1         | 3.57%   |
| Realtek FJ Camera                                              | 1         | 3.57%   |
| Quanta HP 5MP Camera                                           | 1         | 3.57%   |
| Microsoft LifeCam VX-2000                                      | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 3.57%   |
| Microdia Integrated Camera                                     | 1         | 3.57%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 3.57%   |
| Logitech Webcam B500                                           | 1         | 3.57%   |
| Lite-On HP Wide Vision HD Camera                               | 1         | 3.57%   |
| IMC Networks Integrated Camera                                 | 1         | 3.57%   |
| IMC Networks Huawei Web Camera - HD                            | 1         | 3.57%   |
| Chicony UVC 1.00 device HD UVC WebCam                          | 1         | 3.57%   |
| Chicony Lenovo EasyCamera                                      | 1         | 3.57%   |
| Chicony Laptop_Integrated_Webcam_2M                            | 1         | 3.57%   |
| Chicony Integrated Camera                                      | 1         | 3.57%   |
| Chicony FJ 5M Camera                                           | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.57%   |

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
| Broadcom | 2         | 66.67%  |
| O2 Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 48        | 82.76%  |
| 1     | 6         | 10.34%  |
| 2     | 3         | 5.17%   |
| 3     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 3         | 23.08%  |
| Chipcard              | 3         | 23.08%  |
| Fingerprint reader    | 2         | 15.38%  |
| Storage               | 1         | 7.69%   |
| Network               | 1         | 7.69%   |
| Net/wireless          | 1         | 7.69%   |
| Net/ethernet          | 1         | 7.69%   |
| Graphics card         | 1         | 7.69%   |

