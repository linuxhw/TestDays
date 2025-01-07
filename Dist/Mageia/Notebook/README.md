Mageia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 78

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| OEM      | I42IL1                      | [3a9938d946](https://linux-hardware.org/?probe=3a9938d946) | Oct 26, 2024 |
| Acer     | Aspire A315-59G             | [3c57995295](https://linux-hardware.org/?probe=3c57995295) | Oct 05, 2024 |
| Lenovo   | G585 20137                  | [379f6e6fef](https://linux-hardware.org/?probe=379f6e6fef) | Oct 05, 2024 |
| HP       | Pavilion g4                 | [c705d7afa6](https://linux-hardware.org/?probe=c705d7afa6) | Oct 05, 2024 |
| ASUSTek  | ZenBook UX425EA_UX425EA     | [17286ddcf5](https://linux-hardware.org/?probe=17286ddcf5) | Oct 03, 2024 |
| HP       | Laptop 17-ca1xxx            | [1e94fd61d3](https://linux-hardware.org/?probe=1e94fd61d3) | Aug 29, 2024 |
| HP       | Victus by Gaming Laptop ... | [62d3477a3b](https://linux-hardware.org/?probe=62d3477a3b) | May 10, 2024 |
| Acer     | Aspire 5742Z                | [f9ceb71c71](https://linux-hardware.org/?probe=f9ceb71c71) | Apr 11, 2024 |
| Acer     | Aspire SW5-011              | [4e8ad9d65f](https://linux-hardware.org/?probe=4e8ad9d65f) | Apr 10, 2024 |
| Acer     | Aspire SW5-011              | [6f6cb62f08](https://linux-hardware.org/?probe=6f6cb62f08) | Apr 02, 2024 |
| Acer     | Aspire SW5-011              | [6fbb2e2797](https://linux-hardware.org/?probe=6fbb2e2797) | Apr 01, 2024 |
| HP       | ProBook 650 G1              | [f097372357](https://linux-hardware.org/?probe=f097372357) | Mar 31, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X712... | [d6f2169d3f](https://linux-hardware.org/?probe=d6f2169d3f) | Mar 26, 2024 |
| Insyde   | BayTrail                    | [2566898a32](https://linux-hardware.org/?probe=2566898a32) | Mar 23, 2024 |
| Lenovo   | G50-30 80G0                 | [e1e268d222](https://linux-hardware.org/?probe=e1e268d222) | Jan 18, 2024 |
| HP       | ProBook 450 G1              | [028d205023](https://linux-hardware.org/?probe=028d205023) | Jan 09, 2024 |
| HP       | Compaq 6710b (GB887ET#AB... | [2aaeccac56](https://linux-hardware.org/?probe=2aaeccac56) | Jan 08, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop K660... | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop K660... | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| HP       | 255 15.6 inch G9 Noteboo... | [b1394cc278](https://linux-hardware.org/?probe=b1394cc278) | Oct 30, 2023 |
| Lenovo   | IdeaPad Slim 3 15AMN8 82... | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Lenovo   | IdeaPad Slim 3 15AMN8 82... | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| Fujitsu  | S6420                       | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| HP       | Pavilion Notebook           | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| Dell     | Latitude E5470              | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| ASUSTek  | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| HP       | Laptop 14-cm0xxx            | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Compaq   | 420                         | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| ASUSTek  | K73SD                       | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| Dell     | Latitude 7370               | [a254d0d7f1](https://linux-hardware.org/?probe=a254d0d7f1) | Apr 02, 2023 |
| Dell     | Latitude 7370               | [b8a0b25983](https://linux-hardware.org/?probe=b8a0b25983) | Mar 30, 2023 |
| HP       | ProBook 5330m               | [2ec50367d4](https://linux-hardware.org/?probe=2ec50367d4) | Mar 11, 2023 |
| HP       | Unknown                     | [702ed67add](https://linux-hardware.org/?probe=702ed67add) | Dec 17, 2022 |
| HP       | Unknown                     | [d952fd785e](https://linux-hardware.org/?probe=d952fd785e) | Dec 17, 2022 |
| Fujitsu  | CELSIUS H720                | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| Irbis    | NB264                       | [103ca2d20b](https://linux-hardware.org/?probe=103ca2d20b) | Sep 16, 2022 |
| ASUSTek  | X751LN                      | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Schenker | VIA_14_SVI14E20             | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| Notebook | NH5x_NH7x_HHx_HJx_HKx       | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Dell     | Latitude E5570              | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Toshiba  | dynabook R73/A              | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Dell     | Latitude E5570              | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell     | Latitude E5570              | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell     | Precision 5530              | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Lenovo   | ThinkPad T61 6468AE2        | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| ASUSTek  | X751LN                      | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Notebook | NL40_50GU                   | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion   | DEFENDER P10                | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion   | DEFENDER P10                | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Fujitsu  | LIFEBOOK E752               | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Lenovo   | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| ASUSTek  | X751LN                      | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| ASUSTek  | X556URK                     | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| ASUSTek  | X751LN                      | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| Dell     | Latitude E6530              | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Dell     | Inspiron 5480               | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| Kiano    | SlimNote 15.6               | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano    | SlimNote 15.6               | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek  | X751LN                      | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| Dell     | Inspiron 5480               | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| HP       | Spectre 13 Ultrabook        | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| HP       | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP       | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP       | ProBook 445 G7              | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| Acer     | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Dell     | Inspiron 5480               | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| HP       | Unknown                     | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer     | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP       | Pavilion dv6                | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| Lenovo   | G480 20149                  | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| Lenovo   | G570 20079                  | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Mageia 9  | 24        | 43.64%  |
| Mageia 8  | 19        | 34.55%  |
| Mageia 7  | 11        | 20%     |
| Mageia 10 | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Mageia | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.6.52-desktop-1.mga9   | 5         | 8.33%   |
| 5.7.19-desktop-3.mga7   | 4         | 6.67%   |
| 5.7.19-desktop-1.mga7   | 3         | 5%      |
| 6.6.18-desktop-1.mga9   | 2         | 3.33%   |
| 6.4.9-desktop-4.mga9    | 2         | 3.33%   |
| 6.4.8-desktop-6.mga9    | 2         | 3.33%   |
| 6.4.16-desktop-3.mga9   | 2         | 3.33%   |
| 5.6.14-desktop-2.mga7   | 2         | 3.33%   |
| 5.15.4-desktop-1.mga8   | 2         | 3.33%   |
| 5.15.32-desktop-1.mga8  | 2         | 3.33%   |
| 6.6.43-desktop-1.mga9   | 1         | 1.67%   |
| 6.6.28-desktop-1.mga9   | 1         | 1.67%   |
| 6.6.22-desktop-1.mga9   | 1         | 1.67%   |
| 6.6.22-desktop-1.mga10  | 1         | 1.67%   |
| 6.5.13-server-6.mga9    | 1         | 1.67%   |
| 6.5.13-desktop-6.mga9   | 1         | 1.67%   |
| 6.4.6-desktop-2.mga9    | 1         | 1.67%   |
| 6.4.3-desktop-1.mga9    | 1         | 1.67%   |
| 6.2.2-desktop-2.mga9    | 1         | 1.67%   |
| 6.1.45-desktop-1.mga8   | 1         | 1.67%   |
| 6.1.14-desktop-1.mga9   | 1         | 1.67%   |
| 6.0.10-desktop-1.mga9   | 1         | 1.67%   |
| 5.9.6-desktop-1.mga8    | 1         | 1.67%   |
| 5.9.16-desktop-1.mga7   | 1         | 1.67%   |
| 5.9.11-desktop-3.mga8   | 1         | 1.67%   |
| 5.8.5-desktop-2.mga8    | 1         | 1.67%   |
| 5.7.8-desktop-1.mga8    | 1         | 1.67%   |
| 5.6.6-desktop-1.mga7    | 1         | 1.67%   |
| 5.18.15-desktop-1.mga8  | 1         | 1.67%   |
| 5.16.10-desktop-2.mga8  | 1         | 1.67%   |
| 5.15.98-desktop-1.mga8  | 1         | 1.67%   |
| 5.15.79-desktop-1.mga8  | 1         | 1.67%   |
| 5.15.43-desktop-1.mga8  | 1         | 1.67%   |
| 5.15.35-desktop-2.mga8  | 1         | 1.67%   |
| 5.15.117-desktop-2.mga8 | 1         | 1.67%   |
| 5.10.46-desktop-1.mga8  | 1         | 1.67%   |
| 5.10.33-desktop-1.mga8  | 1         | 1.67%   |
| 5.10.30-desktop-1.mga8  | 1         | 1.67%   |
| 5.10.27-desktop-1.mga8  | 1         | 1.67%   |
| 5.10.25-desktop-1.mga8  | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.7.19   | 7         | 11.67%  |
| 6.6.52   | 5         | 8.33%   |
| 6.6.22   | 2         | 3.33%   |
| 6.6.18   | 2         | 3.33%   |
| 6.5.13   | 2         | 3.33%   |
| 6.4.9    | 2         | 3.33%   |
| 6.4.8    | 2         | 3.33%   |
| 6.4.16   | 2         | 3.33%   |
| 5.6.14   | 2         | 3.33%   |
| 5.15.4   | 2         | 3.33%   |
| 5.15.32  | 2         | 3.33%   |
| 5.10.16  | 2         | 3.33%   |
| 6.6.43   | 1         | 1.67%   |
| 6.6.28   | 1         | 1.67%   |
| 6.4.6    | 1         | 1.67%   |
| 6.4.3    | 1         | 1.67%   |
| 6.2.2    | 1         | 1.67%   |
| 6.1.45   | 1         | 1.67%   |
| 6.1.14   | 1         | 1.67%   |
| 6.0.10   | 1         | 1.67%   |
| 5.9.6    | 1         | 1.67%   |
| 5.9.16   | 1         | 1.67%   |
| 5.9.11   | 1         | 1.67%   |
| 5.8.5    | 1         | 1.67%   |
| 5.7.8    | 1         | 1.67%   |
| 5.6.6    | 1         | 1.67%   |
| 5.18.15  | 1         | 1.67%   |
| 5.16.10  | 1         | 1.67%   |
| 5.15.98  | 1         | 1.67%   |
| 5.15.79  | 1         | 1.67%   |
| 5.15.43  | 1         | 1.67%   |
| 5.15.35  | 1         | 1.67%   |
| 5.15.117 | 1         | 1.67%   |
| 5.10.46  | 1         | 1.67%   |
| 5.10.33  | 1         | 1.67%   |
| 5.10.30  | 1         | 1.67%   |
| 5.10.27  | 1         | 1.67%   |
| 5.10.25  | 1         | 1.67%   |
| 5.10.20  | 1         | 1.67%   |
| 5.10.12  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 11        | 18.97%  |
| 5.15    | 9         | 15.52%  |
| 6.4     | 8         | 13.79%  |
| 5.7     | 8         | 13.79%  |
| 5.10    | 7         | 12.07%  |
| 5.9     | 3         | 5.17%   |
| 5.6     | 3         | 5.17%   |
| 6.5     | 2         | 3.45%   |
| 6.1     | 2         | 3.45%   |
| 6.2     | 1         | 1.72%   |
| 6.0     | 1         | 1.72%   |
| 5.8     | 1         | 1.72%   |
| 5.18    | 1         | 1.72%   |
| 5.16    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 28        | 50.91%  |
| KDE        | 8         | 14.55%  |
| GNOME      | 8         | 14.55%  |
| XFCE       | 5         | 9.09%   |
| fluxbox    | 2         | 3.64%   |
| X-Cinnamon | 1         | 1.82%   |
| MATE       | 1         | 1.82%   |
| LXQt       | 1         | 1.82%   |
| Unknown    | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 94.34%  |
| Wayland | 3         | 5.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 24        | 45.28%  |
| Unknown | 18        | 33.96%  |
| LightDM | 6         | 11.32%  |
| GDM     | 3         | 5.66%   |
| TDM     | 2         | 3.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| fr_FR | 12        | 22.64%  |
| en_US | 10        | 18.87%  |
| en_GB | 6         | 11.32%  |
| es_PE | 3         | 5.66%   |
| de_DE | 3         | 5.66%   |
| ru_RU | 2         | 3.77%   |
| pt_BR | 2         | 3.77%   |
| it_IT | 2         | 3.77%   |
| hu_HU | 2         | 3.77%   |
| es_MX | 2         | 3.77%   |
| es_GT | 2         | 3.77%   |
| bg_BG | 2         | 3.77%   |
| ro_RO | 1         | 1.89%   |
| pl_PL | 1         | 1.89%   |
| es_ES | 1         | 1.89%   |
| es_CR | 1         | 1.89%   |
| en_CA | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 35        | 61.4%   |
| BIOS | 22        | 38.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 90.57%  |
| Xfs     | 1         | 1.89%   |
| Overlay | 1         | 1.89%   |
| Jfs     | 1         | 1.89%   |
| Ext3    | 1         | 1.89%   |
| Btrfs   | 1         | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 25        | 44.64%  |
| Unknown | 16        | 28.57%  |
| MBR     | 15        | 26.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 86.79%  |
| Yes       | 7         | 13.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 74.55%  |
| Yes       | 14        | 25.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 16        | 30.19%  |
| ASUSTek Computer | 8         | 15.09%  |
| Lenovo           | 7         | 13.21%  |
| Dell             | 6         | 11.32%  |
| Acer             | 5         | 9.43%   |
| Fujitsu          | 3         | 5.66%   |
| Notebook         | 2         | 3.77%   |
| Toshiba          | 1         | 1.89%   |
| Schenker         | 1         | 1.89%   |
| OEM              | 1         | 1.89%   |
| Medion           | 1         | 1.89%   |
| Kiano            | 1         | 1.89%   |
| Insyde           | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 3.77%   |
| Toshiba dynabook R73/A                   | 1         | 1.89%   |
| Schenker VIA_14_SVI14E20                 | 1         | 1.89%   |
| OEM I42IL1                               | 1         | 1.89%   |
| Notebook NL40_50GU                       | 1         | 1.89%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 1.89%   |
| Medion DEFENDER P10                      | 1         | 1.89%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 1.89%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 1.89%   |
| Lenovo IdeaPad Slim 3 15AMN8 82XQ        | 1         | 1.89%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.89%   |
| Lenovo G585 20137                        | 1         | 1.89%   |
| Lenovo G50-30 80G0                       | 1         | 1.89%   |
| Lenovo G480 20149                        | 1         | 1.89%   |
| Kiano SlimNote 15.6                      | 1         | 1.89%   |
| Insyde BayTrail                          | 1         | 1.89%   |
| HP Victus by Gaming Laptop 15-fb0xxx     | 1         | 1.89%   |
| HP Spectre 13 Ultrabook                  | 1         | 1.89%   |
| HP ProBook 650 G1                        | 1         | 1.89%   |
| HP ProBook 5330m                         | 1         | 1.89%   |
| HP ProBook 450 G1                        | 1         | 1.89%   |
| HP ProBook 445 G7                        | 1         | 1.89%   |
| HP Pavilion Notebook                     | 1         | 1.89%   |
| HP Pavilion g4                           | 1         | 1.89%   |
| HP Pavilion dv6                          | 1         | 1.89%   |
| HP Laptop 17-ca1xxx                      | 1         | 1.89%   |
| HP Laptop 14-cm0xxx                      | 1         | 1.89%   |
| HP EliteBook 840 G3                      | 1         | 1.89%   |
| HP Compaq 6710b (GB887ET#ABH)            | 1         | 1.89%   |
| HP 255 15.6 inch G9 Notebook PC          | 1         | 1.89%   |
| Fujitsu S6420                            | 1         | 1.89%   |
| Fujitsu LIFEBOOK E752                    | 1         | 1.89%   |
| Fujitsu CELSIUS H720                     | 1         | 1.89%   |
| Dell Precision 5530                      | 1         | 1.89%   |
| Dell Latitude E6530                      | 1         | 1.89%   |
| Dell Latitude E5570                      | 1         | 1.89%   |
| Dell Latitude E5470                      | 1         | 1.89%   |
| Dell Latitude 7370                       | 1         | 1.89%   |
| Dell Inspiron 5480                       | 1         | 1.89%   |
| ASUS ZenBook UX425EA_UX425EA             | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Acer Aspire      | 5         | 9.43%   |
| HP ProBook       | 4         | 7.55%   |
| Dell Latitude    | 4         | 7.55%   |
| HP Pavilion      | 3         | 5.66%   |
| ASUS VivoBook    | 3         | 5.66%   |
| Lenovo ThinkPad  | 2         | 3.77%   |
| Lenovo IdeaPad   | 2         | 3.77%   |
| HP Laptop        | 2         | 3.77%   |
| Unknown          | 2         | 3.77%   |
| Toshiba dynabook | 1         | 1.89%   |
| Schenker VIA     | 1         | 1.89%   |
| OEM I42IL1       | 1         | 1.89%   |
| Notebook NL40    | 1         | 1.89%   |
| Notebook NH5x    | 1         | 1.89%   |
| Medion DEFENDER  | 1         | 1.89%   |
| Lenovo G585      | 1         | 1.89%   |
| Lenovo G50-30    | 1         | 1.89%   |
| Lenovo G480      | 1         | 1.89%   |
| Kiano SlimNote   | 1         | 1.89%   |
| Insyde BayTrail  | 1         | 1.89%   |
| HP Victus        | 1         | 1.89%   |
| HP Spectre       | 1         | 1.89%   |
| HP EliteBook     | 1         | 1.89%   |
| HP Compaq        | 1         | 1.89%   |
| HP 255           | 1         | 1.89%   |
| Fujitsu S6420    | 1         | 1.89%   |
| Fujitsu LIFEBOOK | 1         | 1.89%   |
| Fujitsu CELSIUS  | 1         | 1.89%   |
| Dell Precision   | 1         | 1.89%   |
| Dell Inspiron    | 1         | 1.89%   |
| ASUS ZenBook     | 1         | 1.89%   |
| ASUS X751LN      | 1         | 1.89%   |
| ASUS X556URK     | 1         | 1.89%   |
| ASUS Q551LN      | 1         | 1.89%   |
| ASUS K73SD       | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 7         | 13.21%  |
| 2016 | 5         | 9.43%   |
| 2014 | 5         | 9.43%   |
| 2022 | 4         | 7.55%   |
| 2020 | 4         | 7.55%   |
| 2019 | 4         | 7.55%   |
| 2018 | 4         | 7.55%   |
| 2013 | 4         | 7.55%   |
| 2017 | 3         | 5.66%   |
| 2011 | 3         | 5.66%   |
| 2007 | 3         | 5.66%   |
| 2021 | 2         | 3.77%   |
| 2010 | 2         | 3.77%   |
| 2008 | 2         | 3.77%   |
| 2009 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 53        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 33.33%  |
| 8.01-16.0  | 11        | 20.37%  |
| 3.01-4.0   | 9         | 16.67%  |
| 16.01-24.0 | 6         | 11.11%  |
| 32.01-64.0 | 4         | 7.41%   |
| 2.01-3.0   | 3         | 5.56%   |
| 1.01-2.0   | 2         | 3.7%    |
| 0.51-1.0   | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 20        | 35.09%  |
| 1.01-2.0   | 16        | 28.07%  |
| 4.01-8.0   | 11        | 19.3%   |
| 3.01-4.0   | 5         | 8.77%   |
| 0.51-1.0   | 4         | 7.02%   |
| 16.01-24.0 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 74.55%  |
| 2      | 12        | 21.82%  |
| 3      | 2         | 3.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 58.49%  |
| Yes       | 22        | 41.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 77.36%  |
| No        | 12        | 22.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 94.34%  |
| No        | 3         | 5.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 73.58%  |
| No        | 14        | 26.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| France          | 12        | 22.64%  |
| UK              | 5         | 9.43%   |
| USA             | 3         | 5.66%   |
| Peru            | 3         | 5.66%   |
| Netherlands     | 3         | 5.66%   |
| Italy           | 3         | 5.66%   |
| Germany         | 3         | 5.66%   |
| Russia          | 2         | 3.77%   |
| Romania         | 2         | 3.77%   |
| Mexico          | 2         | 3.77%   |
| Guatemala       | 2         | 3.77%   |
| Bulgaria        | 2         | 3.77%   |
| Brazil          | 2         | 3.77%   |
| The Netherlands | 1         | 1.89%   |
| Poland          | 1         | 1.89%   |
| Indonesia       | 1         | 1.89%   |
| Hungary         | 1         | 1.89%   |
| Greece          | 1         | 1.89%   |
| Costa Rica      | 1         | 1.89%   |
| Colombia        | 1         | 1.89%   |
| Canada          | 1         | 1.89%   |
| Australia       | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Paris                 | 3         | 5.17%   |
| Arequipa              | 3         | 5.17%   |
| Versailles            | 2         | 3.45%   |
| Guatemala City        | 2         | 3.45%   |
| Delft                 | 2         | 3.45%   |
| Wiwersheim            | 1         | 1.72%   |
| Tver                  | 1         | 1.72%   |
| Tours                 | 1         | 1.72%   |
| Toulouse              | 1         | 1.72%   |
| The Hague             | 1         | 1.72%   |
| Surabaya              | 1         | 1.72%   |
| Strasbourg            | 1         | 1.72%   |
| Sofia                 | 1         | 1.72%   |
| Sao Paulo             | 1         | 1.72%   |
| Sant'Angelo Lodigiano | 1         | 1.72%   |
| San Antonio           | 1         | 1.72%   |
| Rommerskirchen        | 1         | 1.72%   |
| Rome                  | 1         | 1.72%   |
| Quaregna              | 1         | 1.72%   |
| Poznan                | 1         | 1.72%   |
| Oxford                | 1         | 1.72%   |
| Ottawa                | 1         | 1.72%   |
| Oloron-Sainte-Marie   | 1         | 1.72%   |
| Odenville             | 1         | 1.72%   |
| Nordenham             | 1         | 1.72%   |
| Miercurea-Ciuc        | 1         | 1.72%   |
| Melbourne             | 1         | 1.72%   |
| Marino                | 1         | 1.72%   |
| March                 | 1         | 1.72%   |
| Luce                  | 1         | 1.72%   |
| León                 | 1         | 1.72%   |
| Le Faouet             | 1         | 1.72%   |
| Kemerovo              | 1         | 1.72%   |
| Iztapalapa            | 1         | 1.72%   |
| Hexham                | 1         | 1.72%   |
| Győr                 | 1         | 1.72%   |
| Guaratingueta         | 1         | 1.72%   |
| Guapiles              | 1         | 1.72%   |
| Giannitsa             | 1         | 1.72%   |
| Ferney-Voltaire       | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 7         | 10     | 10.94%  |
| WDC                         | 6         | 8      | 9.38%   |
| Unknown                     | 6         | 8      | 9.38%   |
| Seagate                     | 6         | 6      | 9.38%   |
| Kingston                    | 6         | 7      | 9.38%   |
| Toshiba                     | 5         | 6      | 7.81%   |
| Hitachi                     | 4         | 4      | 6.25%   |
| SK hynix                    | 3         | 4      | 4.69%   |
| Intel                       | 3         | 4      | 4.69%   |
| SanDisk                     | 2         | 2      | 3.13%   |
| Crucial                     | 2         | 2      | 3.13%   |
| Union Memory (Shenzhen)     | 1         | 1      | 1.56%   |
| SPCC                        | 1         | 1      | 1.56%   |
| SABRENT                     | 1         | 1      | 1.56%   |
| Phison                      | 1         | 1      | 1.56%   |
| LDLC                        | 1         | 1      | 1.56%   |
| Kingston Technology Company | 1         | 1      | 1.56%   |
| KingFast                    | 1         | 2      | 1.56%   |
| JMicron Technology          | 1         | 1      | 1.56%   |
| HUSKY                       | 1         | 1      | 1.56%   |
| HGST                        | 1         | 5      | 1.56%   |
| GOODRAM                     | 1         | 1      | 1.56%   |
| Fujitsu                     | 1         | 1      | 1.56%   |
| China                       | 1         | 1      | 1.56%   |
| A-DATA Technology           | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                       | 3         | 4.29%   |
| Unknown MMC Card  16GB                       | 2         | 2.86%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 2.86%   |
| Samsung SSD 860 EVO 500GB                    | 2         | 2.86%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 2.86%   |
| Crucial CT120BX500SSD1 120GB                 | 2         | 2.86%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 1         | 1.43%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.43%   |
| WDC WDS100T2B0A 1TB SSD                      | 1         | 1.43%   |
| WDC WD5000LPLX-66ZNTT1 500GB                 | 1         | 1.43%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 1.43%   |
| WDC WD Green 2.5 480GB SSD                   | 1         | 1.43%   |
| Unknown MMC Card  8GB                        | 1         | 1.43%   |
| Unknown MMC Card  7GB                        | 1         | 1.43%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.43%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.43%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1.43%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1.43%   |
| SPCC Solid State Disk 128GB                  | 1         | 1.43%   |
| SK hynix SKHynix_HFS256GEJ4X112N 256GB       | 1         | 1.43%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB    | 1         | 1.43%   |
| SK hynix PC711 HFS512GDE9X073N 512GB         | 1         | 1.43%   |
| SK hynix NVMe SSD Drive 512GB                | 1         | 1.43%   |
| Seagate ST96812AS 64GB                       | 1         | 1.43%   |
| Seagate ST9250315AS 250GB                    | 1         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1.43%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1.43%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.43%   |
| SanDisk SDSSDH3500G 500GB                    | 1         | 1.43%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD          | 1         | 1.43%   |
| Samsung SSD 970 EVO Plus 1TB                 | 1         | 1.43%   |
| Samsung SSD 870 QVO 1TB                      | 1         | 1.43%   |
| Samsung SSD 850 EVO 500GB                    | 1         | 1.43%   |
| Samsung NVMe SSD Drive 500GB                 | 1         | 1.43%   |
| Samsung MZVLQ256HBJD-00BH1 256GB             | 1         | 1.43%   |
| Samsung MZVLQ256HAJD-000H1 256GB             | 1         | 1.43%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 1.43%   |
| SABRENT Disk 2TB                             | 1         | 1.43%   |
| Phison E12S-1TB-PHISON-SSD-B27B              | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 6         | 6      | 30%     |
| Toshiba            | 4         | 5      | 20%     |
| Hitachi            | 4         | 4      | 20%     |
| WDC                | 2         | 4      | 10%     |
| SABRENT            | 1         | 1      | 5%      |
| JMicron Technology | 1         | 1      | 5%      |
| HGST               | 1         | 5      | 5%      |
| Fujitsu            | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 18.18%  |
| WDC                 | 3         | 3      | 13.64%  |
| Kingston            | 3         | 3      | 13.64%  |
| SanDisk             | 2         | 2      | 9.09%   |
| Crucial             | 2         | 2      | 9.09%   |
| SPCC                | 1         | 1      | 4.55%   |
| LDLC                | 1         | 1      | 4.55%   |
| KingFast            | 1         | 2      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| HUSKY               | 1         | 1      | 4.55%   |
| GOODRAM             | 1         | 1      | 4.55%   |
| China               | 1         | 1      | 4.55%   |
| A-DATA Technology   | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 24     | 33.85%  |
| HDD  | 20        | 27     | 30.77%  |
| NVMe | 17        | 21     | 26.15%  |
| MMC  | 6         | 8      | 9.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 49     | 60.32%  |
| NVMe | 17        | 21     | 26.98%  |
| MMC  | 6         | 8      | 9.52%   |
| SAS  | 2         | 2      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 35     | 77.5%   |
| 0.51-1.0   | 8         | 15     | 20%     |
| 1.01-2.0   | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 20        | 37.74%  |
| 501-1000   | 14        | 26.42%  |
| 101-250    | 13        | 24.53%  |
| 21-50      | 2         | 3.77%   |
| 51-100     | 2         | 3.77%   |
| 1001-2000  | 1         | 1.89%   |
| Unknown    | 1         | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 14        | 25%     |
| 101-250   | 12        | 21.43%  |
| 1-20      | 12        | 21.43%  |
| 51-100    | 10        | 17.86%  |
| 501-1000  | 4         | 7.14%   |
| 251-500   | 2         | 3.57%   |
| 1001-2000 | 1         | 1.79%   |
| Unknown   | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 12.5%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 12.5%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 12.5%   |
| Kingston SA400S37240G 240GB SSD    | 1         | 1      | 12.5%   |
| Hitachi HTS725050A9A364 500GB      | 1         | 1      | 12.5%   |
| Hitachi HTS542525K9A300 250GB      | 1         | 1      | 12.5%   |
| Fujitsu MHZ2160BH G2 160GB         | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 37.5%   |
| Hitachi  | 2         | 2      | 25%     |
| Toshiba  | 1         | 1      | 12.5%   |
| Kingston | 1         | 1      | 12.5%   |
| Fujitsu  | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |
| Fujitsu | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Works    | 31        | 37     | 52.54%  |
| Detected | 20        | 35     | 33.9%   |
| Malfunc  | 8         | 8      | 13.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 64.41%  |
| AMD                          | 7         | 11.86%  |
| Samsung Electronics          | 4         | 6.78%   |
| Kingston Technology Company  | 4         | 6.78%   |
| SK hynix                     | 3         | 5.08%   |
| Toshiba America Info Systems | 1         | 1.69%   |
| SanDisk                      | 1         | 1.69%   |
| Phison Electronics           | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 7.58%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 7.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 6.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 3.03%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 2         | 3.03%   |
| AMD SB600 IDE                                                                  | 2         | 3.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.52%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 1.52%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.52%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.52%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.52%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.52%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 1         | 1.52%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 1         | 1.52%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 1         | 1.52%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.52%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.52%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 1.52%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.52%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.52%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.52%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 39        | 60%     |
| NVMe | 16        | 24.62%  |
| RAID | 5         | 7.69%   |
| IDE  | 5         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 79.25%  |
| AMD    | 11        | 20.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 5.66%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 3.77%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 3.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.77%   |
| AMD Turion 64 X2 Mobile Technology TL-60      | 2         | 3.77%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.89%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.89%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 1.89%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 1.89%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.89%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.89%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.89%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.89%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.89%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 1         | 1.89%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 1         | 1.89%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 1         | 1.89%   |
| Intel Celeron CPU N2820 @ 2.13GHz             | 1         | 1.89%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 1.89%   |
| Intel Atom CPU Z3745 @ 1.33GHz                | 1         | 1.89%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.89%   |
| Intel 12th Gen Core i5-12450H                 | 1         | 1.89%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 1.89%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.89%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 24.53%  |
| Intel Core i7           | 11        | 20.75%  |
| Other                   | 4         | 7.55%   |
| Intel Core i3           | 3         | 5.66%   |
| Intel Core 2 Duo        | 3         | 5.66%   |
| Intel Atom              | 3         | 5.66%   |
| Intel Pentium           | 2         | 3.77%   |
| AMD Turion 64 X2 Mobile | 2         | 3.77%   |
| AMD Ryzen 7             | 2         | 3.77%   |
| AMD Ryzen 5             | 2         | 3.77%   |
| AMD Ryzen 3             | 2         | 3.77%   |
| Intel Pentium Silver    | 1         | 1.89%   |
| Intel Core m5           | 1         | 1.89%   |
| Intel Celeron           | 1         | 1.89%   |
| AMD E                   | 1         | 1.89%   |
| AMD A6                  | 1         | 1.89%   |
| AMD A10                 | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 58.49%  |
| 4      | 15        | 28.3%   |
| 8      | 3         | 5.66%   |
| 6      | 3         | 5.66%   |
| 10     | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 37        | 69.81%  |
| 1      | 16        | 30.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 43.64%  |
| 0x306a9    | 4         | 7.27%   |
| 0x806e9    | 3         | 5.45%   |
| 0x406e3    | 3         | 5.45%   |
| 0x40651    | 2         | 3.64%   |
| 0x306c3    | 2         | 3.64%   |
| 0x206a7    | 2         | 3.64%   |
| 0x08108109 | 2         | 3.64%   |
| 0xa0652    | 1         | 1.82%   |
| 0x906ea    | 1         | 1.82%   |
| 0x806ec    | 1         | 1.82%   |
| 0x806eb    | 1         | 1.82%   |
| 0x706a1    | 1         | 1.82%   |
| 0x506e3    | 1         | 1.82%   |
| 0x406c4    | 1         | 1.82%   |
| 0x20655    | 1         | 1.82%   |
| 0x0a50000f | 1         | 1.82%   |
| 0x0a50000d | 1         | 1.82%   |
| 0x08a00008 | 1         | 1.82%   |
| 0x08600106 | 1         | 1.82%   |
| 0x05000119 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 6         | 11.32%  |
| Haswell          | 6         | 11.32%  |
| Skylake          | 5         | 9.43%   |
| IvyBridge        | 5         | 9.43%   |
| Silvermont       | 4         | 7.55%   |
| SandyBridge      | 4         | 7.55%   |
| Zen+             | 2         | 3.77%   |
| Zen 3            | 2         | 3.77%   |
| Westmere         | 2         | 3.77%   |
| Penryn           | 2         | 3.77%   |
| K8 Hammer        | 2         | 3.77%   |
| Excavator        | 2         | 3.77%   |
| Alderlake Hybrid | 2         | 3.77%   |
| Unknown          | 2         | 3.77%   |
| Zen 2            | 1         | 1.89%   |
| TigerLake        | 1         | 1.89%   |
| IceLake          | 1         | 1.89%   |
| Goldmont plus    | 1         | 1.89%   |
| Core             | 1         | 1.89%   |
| CometLake        | 1         | 1.89%   |
| Bobcat           | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 60.87%  |
| AMD    | 14        | 20.29%  |
| Nvidia | 13        | 18.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.17%   |
| Intel HD Graphics 620                                                                    | 3         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 4.17%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 2.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.78%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 2         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.78%   |
| Nvidia TU117M [GeForce MX550]                                                            | 1         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.39%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.39%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.39%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.39%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.39%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 1.39%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.39%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.39%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.39%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.39%   |
| Intel HD Graphics 530                                                                    | 1         | 1.39%   |
| Intel HD Graphics 515                                                                    | 1         | 1.39%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.39%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.39%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.39%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 43.4%   |
| Intel + Nvidia | 13        | 24.53%  |
| 1 x AMD        | 9         | 16.98%  |
| 2 x Intel      | 3         | 5.66%   |
| Intel + AMD    | 3         | 5.66%   |
| 2 x AMD        | 2         | 3.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 53        | 98.15%  |
| Proprietary | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 60.71%  |
| 1.01-2.0   | 10        | 17.86%  |
| 0.01-0.5   | 5         | 8.93%   |
| 3.01-4.0   | 3         | 5.36%   |
| 0.51-1.0   | 3         | 5.36%   |
| 5.01-6.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 21.43%  |
| LG Display              | 10        | 17.86%  |
| Chimei Innolux          | 9         | 16.07%  |
| BOE                     | 9         | 16.07%  |
| Samsung Electronics     | 6         | 10.71%  |
| Chi Mei Optoelectronics | 3         | 5.36%   |
| Sharp                   | 2         | 3.57%   |
| Lenovo                  | 1         | 1.79%   |
| HannStar                | 1         | 1.79%   |
| Eizo                    | 1         | 1.79%   |
| Ancor Communications    | 1         | 1.79%   |
| Acer                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch             | 2         | 3.51%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.75%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch                   | 1         | 1.75%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch        | 1         | 1.75%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch      | 1         | 1.75%   |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0457 1920x1080 345x194mm 15.6-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD03EF 1366x768 223x125mm 10.1-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 1.75%   |
| LG Display LCD Monitor LGD0215 1920x1080 345x194mm 15.6-inch              | 1         | 1.75%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 1         | 1.75%   |
| HannStar HSD140PHW1 HSD0583 1366x768 309x174mm 14.0-inch                  | 1         | 1.75%   |
| Eizo CS270 ENC2694 1920x1080 597x336mm 27.0-inch                          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch           | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.75%   |
| BOE LCD Monitor BOE0B2B 1920x1200 345x215mm 16.0-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE09CA 1920x1080 344x194mm 15.5-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 43.64%  |
| 1366x768 (WXGA)    | 17        | 30.91%  |
| 1600x900 (HD+)     | 5         | 9.09%   |
| 1280x800 (WXGA)    | 3         | 5.45%   |
| 1920x1200 (WUXGA)  | 2         | 3.64%   |
| 3840x2160 (4K)     | 1         | 1.82%   |
| 3200x1800 (QHD+)   | 1         | 1.82%   |
| 2560x1440 (QHD)    | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 44.64%  |
| 17     | 9         | 16.07%  |
| 13     | 8         | 14.29%  |
| 14     | 7         | 12.5%   |
| 24     | 2         | 3.57%   |
| 31     | 1         | 1.79%   |
| 27     | 1         | 1.79%   |
| 22     | 1         | 1.79%   |
| 16     | 1         | 1.79%   |
| 10     | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 67.86%  |
| 351-400     | 9         | 16.07%  |
| 201-300     | 4         | 7.14%   |
| 501-600     | 3         | 5.36%   |
| 601-700     | 1         | 1.79%   |
| 401-500     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 88.46%  |
| 16/10 | 6         | 11.54%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 44.64%  |
| 81-90          | 12        | 21.43%  |
| 121-130        | 8         | 14.29%  |
| 71-80          | 3         | 5.36%   |
| 201-250        | 3         | 5.36%   |
| 351-500        | 1         | 1.79%   |
| 41-50          | 1         | 1.79%   |
| 301-350        | 1         | 1.79%   |
| 131-140        | 1         | 1.79%   |
| 111-120        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 43.64%  |
| 101-120       | 19        | 34.55%  |
| 51-100        | 8         | 14.55%  |
| 161-240       | 2         | 3.64%   |
| More than 240 | 1         | 1.82%   |
| 1-50          | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 48        | 90.57%  |
| 2     | 5         | 9.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 26        | 33.77%  |
| Realtek Semiconductor    | 24        | 31.17%  |
| Qualcomm Atheros         | 8         | 10.39%  |
| Broadcom                 | 8         | 10.39%  |
| MediaTek                 | 3         | 3.9%    |
| Broadcom Limited         | 3         | 3.9%    |
| Sierra Wireless          | 2         | 2.6%    |
| Marvell Technology Group | 1         | 1.3%    |
| Dell                     | 1         | 1.3%    |
| ASIX Electronics         | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.21%   |
| Intel Wireless 8260                                                    | 4         | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 3.16%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 3.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 3.16%   |
| Sierra Wireless MC8305 Modem                                           | 2         | 2.11%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 2.11%   |
| Intel Wireless 7260                                                    | 2         | 2.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 2.11%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.11%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 2.11%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 2.11%   |
| Broadcom BCM4311 802.11a/b/g                                           | 2         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.05%   |
| Realtek RTL8187SE Wireless LAN Controller                              | 1         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 1.05%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.05%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                    | 1         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.05%   |
| Intel Wireless 8265 / 8275                                             | 1         | 1.05%   |
| Intel Wireless 3165                                                    | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.05%   |
| Intel Ultimate N WiFi Link 5300                                        | 1         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 1.05%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.05%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 46.3%   |
| Realtek Semiconductor | 8         | 14.81%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| Broadcom              | 7         | 12.96%  |
| MediaTek              | 3         | 5.56%   |
| Sierra Wireless       | 2         | 3.7%    |
| Dell                  | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 7.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 5.56%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 5.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 5.56%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 3.7%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.7%    |
| Intel Wireless 7260                                            | 2         | 3.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 3.7%    |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.85%   |
| Realtek RTL8187SE Wireless LAN Controller                      | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.85%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.85%   |
| Intel Wireless 3165                                            | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.85%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.85%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.85%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.85%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                   | 1         | 1.85%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 51.22%  |
| Intel                    | 11        | 26.83%  |
| Broadcom Limited         | 3         | 7.32%   |
| Qualcomm Atheros         | 2         | 4.88%   |
| Broadcom                 | 2         | 4.88%   |
| Marvell Technology Group | 1         | 2.44%   |
| ASIX Electronics         | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 39.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 9.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 9.76%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 4.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 4.88%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 2         | 4.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 2.44%   |
| Intel Ethernet Connection I219-V                                       | 1         | 2.44%   |
| Intel Ethernet Connection I217-V                                       | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 2.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 1         | 2.44%   |
| ASIX AX88772B                                                          | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 54.95%  |
| Ethernet | 41        | 45.05%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 81.48%  |
| Ethernet | 10        | 18.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 73.58%  |
| 1     | 11        | 20.75%  |
| 0     | 3         | 5.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 66.67%  |
| Yes  | 18        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 16        | 40%     |
| Realtek Semiconductor   | 6         | 15%     |
| IMC Networks            | 6         | 15%     |
| Hewlett-Packard         | 3         | 7.5%    |
| Foxconn / Hon Hai       | 2         | 5%      |
| Broadcom                | 2         | 5%      |
| Taiyo Yuden             | 1         | 2.5%    |
| MediaTek                | 1         | 2.5%    |
| Lite-On Technology      | 1         | 2.5%    |
| Dell                    | 1         | 2.5%    |
| Cambridge Silicon Radio | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 7.5%    |
| Intel AX200 Bluetooth                               | 3         | 7.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5%      |
| Realtek 802.11ac WLAN Adapter                       | 2         | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 5%      |
| Intel AX201 Bluetooth                               | 2         | 5%      |
| IMC Networks Wireless_Device                        | 2         | 5%      |
| IMC Networks Bluetooth Device                       | 2         | 5%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 5%      |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 5%      |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 2.5%    |
| Realtek RTL8723B Bluetooth                          | 1         | 2.5%    |
| Realtek Bluetooth Radio                             | 1         | 2.5%    |
| MediaTek MT7630e Bluetooth Adapter                  | 1         | 2.5%    |
| Lite-On Bluetooth Device                            | 1         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 1         | 2.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 2.5%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.5%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.5%    |
| Broadcom HP Portable Valentine                      | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 40        | 67.8%   |
| AMD                 | 12        | 20.34%  |
| Nvidia              | 5         | 8.47%   |
| Walmart             | 1         | 1.69%   |
| C-Media Electronics | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 9.46%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 6         | 8.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 4.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.05%   |
| Nvidia GA107 High Definition Audio Controller                              | 2         | 2.7%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 2.7%    |
| Walmart AB13X Headset Adapter                                              | 1         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.35%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series LPE Audio Controller             | 1         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.35%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.35%   |
| AMD High Definition Audio Controller                                       | 1         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 29.09%  |
| SK hynix            | 11        | 20%     |
| Unknown             | 8         | 14.55%  |
| Kingston            | 6         | 10.91%  |
| Micron Technology   | 5         | 9.09%   |
| Corsair             | 2         | 3.64%   |
| Unknown (ABCD)      | 1         | 1.82%   |
| Team                | 1         | 1.82%   |
| Smart               | 1         | 1.82%   |
| Ramaxel Technology  | 1         | 1.82%   |
| CSX                 | 1         | 1.82%   |
| Crucial             | 1         | 1.82%   |
| Unknown             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 5.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.45%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.45%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s            | 2         | 3.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 3.45%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.72%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                            | 1         | 1.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 1.72%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 1.72%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 1639MT/s           | 1         | 1.72%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.72%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 1         | 1.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.72%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.72%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.72%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.72%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 19        | 43.18%  |
| DDR4    | 14        | 31.82%  |
| SDRAM   | 3         | 6.82%   |
| DDR2    | 3         | 6.82%   |
| LPDDR4  | 2         | 4.55%   |
| LPDDR5  | 1         | 2.27%   |
| LPDDR3  | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 95.12%  |
| Row Of Chips | 2         | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 20        | 40.82%  |
| 8192  | 13        | 26.53%  |
| 2048  | 7         | 14.29%  |
| 1024  | 5         | 10.2%   |
| 16384 | 3         | 6.12%   |
| 32768 | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 27.66%  |
| 3200  | 5         | 10.64%  |
| 2667  | 4         | 8.51%   |
| 2400  | 4         | 8.51%   |
| 1333  | 3         | 6.38%   |
| 667   | 3         | 6.38%   |
| 4199  | 2         | 4.26%   |
| 2133  | 2         | 4.26%   |
| 1334  | 2         | 4.26%   |
| 1066  | 2         | 4.26%   |
| 6400  | 1         | 2.13%   |
| 4267  | 1         | 2.13%   |
| 3266  | 1         | 2.13%   |
| 3000  | 1         | 2.13%   |
| 1639  | 1         | 2.13%   |
| 975   | 1         | 2.13%   |
| 533   | 1         | 2.13%   |

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
| Chicony Electronics                    | 16        | 33.33%  |
| IMC Networks                           | 5         | 10.42%  |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Luxvisions Innotech Limited            | 3         | 6.25%   |
| Lite-On Technology                     | 3         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.25%   |
| Alcor Micro                            | 3         | 6.25%   |
| Suyin                                  | 2         | 4.17%   |
| Microdia                               | 2         | 4.17%   |
| Sunplus Innovation Technology          | 1         | 2.08%   |
| Sonix Technology                       | 1         | 2.08%   |
| Primax Electronics                     | 1         | 2.08%   |
| Logitech                               | 1         | 2.08%   |
| Bison Electronics                      | 1         | 2.08%   |
| Apple                                  | 1         | 2.08%   |
| Acer                                   | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 6.12%   |
| Chicony USB2.0 Camera                                                      | 3         | 6.12%   |
| Chicony Integrated Camera                                                  | 3         | 6.12%   |
| Lite-On HP HD Webcam                                                       | 2         | 4.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 4.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 4.08%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 4.08%   |
| Chicony FJ Camera                                                          | 2         | 4.08%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.04%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 2.04%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 2.04%   |
| Sonix USB2.0 FHD UVC WebCam                                                | 1         | 2.04%   |
| Realtek USB Camera                                                         | 1         | 2.04%   |
| Primax HP Truevision FHD                                                   | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.04%   |
| Microdia Integrated Webcam                                                 | 1         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 2.04%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 2.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.04%   |
| Logitech Fujitsu Webcam                                                    | 1         | 2.04%   |
| Lite-On HP Webcam                                                          | 1         | 2.04%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.04%   |
| Chicony Integrated IR Camera                                               | 1         | 2.04%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.04%   |
| Chicony HD WebCam                                                          | 1         | 2.04%   |
| Chicony CNF8161                                                            | 1         | 2.04%   |
| Chicony ACER HD User Facing                                                | 1         | 2.04%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.04%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 1         | 2.04%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.04%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 2.04%   |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.04%   |
| Acer BisonCam,NB Pro                                                       | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 4         | 36.36%  |
| AuthenTec                          | 4         | 36.36%  |
| Shenzhen Goodix Technology         | 2         | 18.18%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 27.27%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner                            | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 9.09%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 9.09%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 60%     |
| O2 Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 30        | 53.57%  |
| 1     | 19        | 33.93%  |
| 2     | 4         | 7.14%   |
| 3     | 3         | 5.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 11        | 33.33%  |
| Fingerprint reader    | 11        | 33.33%  |
| Chipcard              | 5         | 15.15%  |
| Storage               | 1         | 3.03%   |
| Sound                 | 1         | 3.03%   |
| Net/wireless          | 1         | 3.03%   |
| Multimedia controller | 1         | 3.03%   |
| Camera                | 1         | 3.03%   |
| Bluetooth             | 1         | 3.03%   |

