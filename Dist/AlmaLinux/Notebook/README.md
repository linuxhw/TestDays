AlmaLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 74

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Falco                       | [9a82a5b9e8](https://linux-hardware.org/?probe=9a82a5b9e8) | Jan 26, 2024 |
| HP        | ENVY 15                     | [95ec6d10d0](https://linux-hardware.org/?probe=95ec6d10d0) | Jan 19, 2024 |
| Acer      | TravelMate 5735Z            | [6d759892ab](https://linux-hardware.org/?probe=6d759892ab) | Jan 12, 2024 |
| Acer      | TravelMate 5735Z            | [2ad65584c2](https://linux-hardware.org/?probe=2ad65584c2) | Jan 11, 2024 |
| HP        | Falco                       | [f6a8ee9181](https://linux-hardware.org/?probe=f6a8ee9181) | Jan 11, 2024 |
| Dell      | Precision 5680              | [82dc0a13bb](https://linux-hardware.org/?probe=82dc0a13bb) | Jan 10, 2024 |
| Timi      | TM1709                      | [f566951fd0](https://linux-hardware.org/?probe=f566951fd0) | Dec 14, 2023 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| AOCWEI    | A2                          | [ac8272a8a8](https://linux-hardware.org/?probe=ac8272a8a8) | Nov 26, 2023 |
| Acer      | Aspire E5-553               | [a8349dda46](https://linux-hardware.org/?probe=a8349dda46) | Nov 16, 2023 |
| Dell      | XPS 13 9360                 | [e0bc805f38](https://linux-hardware.org/?probe=e0bc805f38) | Nov 16, 2023 |
| AOCWEI    | A2                          | [1006e22f22](https://linux-hardware.org/?probe=1006e22f22) | Nov 09, 2023 |
| Toshiba   | Satellite C50-A             | [056e939d6d](https://linux-hardware.org/?probe=056e939d6d) | Nov 09, 2023 |
| Toshiba   | Satellite C50-A             | [6c8040c314](https://linux-hardware.org/?probe=6c8040c314) | Nov 08, 2023 |
| Notebook  | NS50_70MU                   | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook  | NS50_70MU                   | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| Dell      | Precision 7760              | [4b42c6c7f1](https://linux-hardware.org/?probe=4b42c6c7f1) | Oct 14, 2023 |
| HP        | Laptop 14-ep0xxx            | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo    | G580 20157                  | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| Dell      | Latitude E5420              | [0b1b042a5b](https://linux-hardware.org/?probe=0b1b042a5b) | Sep 19, 2023 |
| HP        | Notebook                    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell      | Inspiron 5379               | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Dell      | Inspiron 5379               | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| Dell      | Latitude 5490               | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Lenovo    | ThinkPad E14 Gen 2 20TBS... | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Timi      | RedmiBook 14-APCS           | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| HP        | 17-ak041ur                  | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| Dell      | Inspiron 5555               | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| Dell      | Inspiron 5555               | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| Dell      | Inspiron 5555               | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Maibenben | MaiBook X series            | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Dell      | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| MSI       | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP        | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| TUXEDO    | Aura 15 Gen1                | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO    | Aura 15 Gen1                | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Lenovo    | ThinkPad P1 Gen 4i 20Y30... | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Google    | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Dell      | Inspiron 3501               | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Lenovo    | V14-ARE 82DQ                | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| HP        | Falco                       | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell      | Latitude E6510              | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| HP        | Falco                       | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| HP        | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo    | B50-30 20382                | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Lenovo    | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| Toshiba   | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer      | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Acer      | TravelMate 5735Z            | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| HP        | Falco                       | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP        | Laptop 15-ef1xxx            | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP        | ENVY dv6                    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| HP        | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| HP        | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google    | Kohaku                      | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google    | Kohaku                      | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo    | ThinkPad T440s 20ARS32P0... | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Lenovo    | ThinkBook 13s-IWL 20R9      | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Intel     | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel     | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Dell      | Inspiron 3185               | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell      | Inspiron 3185               | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo    | Yoga 2 13 20344             | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo    | IdeaPad S145-15IWL 81MV     | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| HP        | EliteBook 8570w             | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| Dell      | Inspiron 3185               | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell      | Inspiron 3185               | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell      | Inspiron 3185               | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| Lenovo    | IdeaPad 330-15ARR 81D2      | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.2 | 13        | 24.07%  |
| AlmaLinux 9.1 | 8         | 14.81%  |
| AlmaLinux 9.3 | 7         | 12.96%  |
| AlmaLinux 9.0 | 6         | 11.11%  |
| AlmaLinux 8.6 | 5         | 9.26%   |
| AlmaLinux 8.4 | 5         | 9.26%   |
| AlmaLinux 8.8 | 3         | 5.56%   |
| AlmaLinux 8.3 | 3         | 5.56%   |
| AlmaLinux 8.5 | 2         | 3.7%    |
| AlmaLinux 8.9 | 1         | 1.85%   |
| AlmaLinux 8.7 | 1         | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 51        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 5         | 9.09%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 4         | 7.27%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 4         | 7.27%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 7.27%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 5.45%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 3.64%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 3.64%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 2         | 3.64%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 3.64%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2         | 3.64%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 3.64%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 3.64%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2         | 3.64%   |
| 6.4.0-1.el8.elrepo.x86_64    | 1         | 1.82%   |
| 5.4.175-1.el8.elrepo.x86_64  | 1         | 1.82%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 1         | 1.82%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 1.82%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1         | 1.82%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1         | 1.82%   |
| 4.18.0-513.9.1.el8_9.x86_64  | 1         | 1.82%   |
| 4.18.0-477.27.2.el8_8.x86_64 | 1         | 1.82%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 1         | 1.82%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 1         | 1.82%   |
| 4.18.0-425.3.1.el8.x86_64    | 1         | 1.82%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 1.82%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 1.82%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 1.82%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 1.82%   |
| 4.18.0-305.el8.x86_64        | 1         | 1.82%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1         | 1.82%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1         | 1.82%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 34        | 64.15%  |
| 4.18.0  | 17        | 32.08%  |
| 6.4.0   | 1         | 1.89%   |
| 5.4.175 | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 34        | 64.15%  |
| 4.18    | 17        | 32.08%  |
| 6.4     | 1         | 1.89%   |
| 5.4     | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 36        | 70.59%  |
| XFCE            | 4         | 7.84%   |
| KDE5            | 4         | 7.84%   |
| MATE            | 3         | 5.88%   |
| GNOME Classic   | 2         | 3.92%   |
| GNOME Flashback | 1         | 1.96%   |
| Unknown         | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 34        | 65.38%  |
| X11     | 16        | 30.77%  |
| Tty     | 2         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 47.06%  |
| GDM     | 21        | 41.18%  |
| SDDM    | 3         | 5.88%   |
| LightDM | 3         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 30        | 58.82%  |
| de_DE | 6         | 11.76%  |
| fr_FR | 3         | 5.88%   |
| C     | 3         | 5.88%   |
| pl_PL | 2         | 3.92%   |
| ru_RU | 1         | 1.96%   |
| it_IT | 1         | 1.96%   |
| es_VE | 1         | 1.96%   |
| es_ES | 1         | 1.96%   |
| en_IN | 1         | 1.96%   |
| en_GB | 1         | 1.96%   |
| en_CA | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 74.51%  |
| BIOS | 13        | 25.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 41        | 80.39%  |
| Ext4 | 10        | 19.61%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 25        | 49.02%  |
| Unknown | 22        | 43.14%  |
| MBR     | 4         | 7.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 90.2%   |
| Yes       | 5         | 9.8%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 86.27%  |
| Yes       | 7         | 13.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 27.45%  |
| Hewlett-Packard  | 12        | 23.53%  |
| Dell             | 9         | 17.65%  |
| Acer             | 3         | 5.88%   |
| Toshiba          | 2         | 3.92%   |
| Timi             | 2         | 3.92%   |
| Google           | 2         | 3.92%   |
| TUXEDO           | 1         | 1.96%   |
| Notebook         | 1         | 1.96%   |
| MSI              | 1         | 1.96%   |
| Maibenben        | 1         | 1.96%   |
| Intel            | 1         | 1.96%   |
| ASUSTek Computer | 1         | 1.96%   |
| AOCWEI           | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                      | 1         | 1.96%   |
| Toshiba Satellite L50-C                  | 1         | 1.96%   |
| Toshiba Satellite C50-A                  | 1         | 1.96%   |
| Timi TM1709                              | 1         | 1.96%   |
| Timi RedmiBook 14-APCS                   | 1         | 1.96%   |
| Notebook NS50_70MU                       | 1         | 1.96%   |
| MSI GL75 9SE                             | 1         | 1.96%   |
| Maibenben MaiBook X series               | 1         | 1.96%   |
| Lenovo Yoga 2 13 20344                   | 1         | 1.96%   |
| Lenovo V14-ARE 82DQ                      | 1         | 1.96%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT | 1         | 1.96%   |
| Lenovo ThinkPad T440s 20ARS32P00         | 1         | 1.96%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00     | 1         | 1.96%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS     | 1         | 1.96%   |
| Lenovo ThinkPad E14 Gen 2 20TBS0CK00     | 1         | 1.96%   |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 1.96%   |
| Lenovo Legion 5 15IMH05H 81Y6            | 1         | 1.96%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 1.96%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 1         | 1.96%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 1         | 1.96%   |
| Lenovo G580 20157                        | 1         | 1.96%   |
| Lenovo B50-30 20382                      | 1         | 1.96%   |
| Intel powered classmate PC               | 1         | 1.96%   |
| HP ZBook 17 G2                           | 1         | 1.96%   |
| HP Notebook                              | 1         | 1.96%   |
| HP Laptop 17-cp0xxx                      | 1         | 1.96%   |
| HP Laptop 15-ef1xxx                      | 1         | 1.96%   |
| HP Laptop 14-ep0xxx                      | 1         | 1.96%   |
| HP Falco                                 | 1         | 1.96%   |
| HP ENVY dv6                              | 1         | 1.96%   |
| HP ENVY 15                               | 1         | 1.96%   |
| HP EliteBook 8570w                       | 1         | 1.96%   |
| HP EliteBook 850 G8 Notebook PC          | 1         | 1.96%   |
| HP EliteBook 8470p                       | 1         | 1.96%   |
| HP 17-ak041ur                            | 1         | 1.96%   |
| Google Kohaku                            | 1         | 1.96%   |
| Google Kefka                             | 1         | 1.96%   |
| Dell XPS 13 9360                         | 1         | 1.96%   |
| Dell Precision 7760                      | 1         | 1.96%   |
| Dell Precision 5680                      | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 9.8%    |
| Lenovo IdeaPad    | 3         | 5.88%   |
| HP Laptop         | 3         | 5.88%   |
| HP EliteBook      | 3         | 5.88%   |
| Dell Latitude     | 3         | 5.88%   |
| Dell Inspiron     | 3         | 5.88%   |
| Toshiba Satellite | 2         | 3.92%   |
| Lenovo Legion     | 2         | 3.92%   |
| HP ENVY           | 2         | 3.92%   |
| Dell Precision    | 2         | 3.92%   |
| TUXEDO Aura       | 1         | 1.96%   |
| Timi TM1709       | 1         | 1.96%   |
| Timi RedmiBook    | 1         | 1.96%   |
| Notebook NS50     | 1         | 1.96%   |
| MSI GL75          | 1         | 1.96%   |
| Maibenben MaiBook | 1         | 1.96%   |
| Lenovo Yoga       | 1         | 1.96%   |
| Lenovo V14-ARE    | 1         | 1.96%   |
| Lenovo G580       | 1         | 1.96%   |
| Lenovo B50-30     | 1         | 1.96%   |
| Intel powered     | 1         | 1.96%   |
| HP ZBook          | 1         | 1.96%   |
| HP Notebook       | 1         | 1.96%   |
| HP Falco          | 1         | 1.96%   |
| HP 17-ak041ur     | 1         | 1.96%   |
| Google Kohaku     | 1         | 1.96%   |
| Google Kefka      | 1         | 1.96%   |
| Dell XPS          | 1         | 1.96%   |
| ASUS ASUS         | 1         | 1.96%   |
| AOCWEI A2         | 1         | 1.96%   |
| Acer TravelMate   | 1         | 1.96%   |
| Acer TMP453-MG    | 1         | 1.96%   |
| Acer Aspire       | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 15.69%  |
| 2019 | 6         | 11.76%  |
| 2018 | 6         | 11.76%  |
| 2021 | 4         | 7.84%   |
| 2014 | 4         | 7.84%   |
| 2012 | 4         | 7.84%   |
| 2023 | 3         | 5.88%   |
| 2022 | 3         | 5.88%   |
| 2011 | 3         | 5.88%   |
| 2010 | 3         | 5.88%   |
| 2016 | 2         | 3.92%   |
| 2015 | 2         | 3.92%   |
| 2013 | 2         | 3.92%   |
| 2017 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 51        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 45        | 86.54%  |
| Enabled  | 7         | 13.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 94.12%  |
| Yes  | 3         | 5.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 35.29%  |
| 4.01-8.0    | 14        | 27.45%  |
| 3.01-4.0    | 8         | 15.69%  |
| 16.01-24.0  | 4         | 7.84%   |
| 32.01-64.0  | 3         | 5.88%   |
| 1.01-2.0    | 2         | 3.92%   |
| 24.01-32.0  | 1         | 1.96%   |
| 64.01-256.0 | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 35.85%  |
| 1.01-2.0  | 13        | 24.53%  |
| 3.01-4.0  | 9         | 16.98%  |
| 4.01-8.0  | 8         | 15.09%  |
| 8.01-16.0 | 2         | 3.77%   |
| 0.51-1.0  | 2         | 3.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 69.23%  |
| 2      | 13        | 25%     |
| 3      | 2         | 3.85%   |
| 0      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 76.47%  |
| Yes       | 12        | 23.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 78.43%  |
| No        | 11        | 21.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 86.54%  |
| No        | 7         | 13.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 23.53%  |
| Germany      | 7         | 13.73%  |
| France       | 4         | 7.84%   |
| India        | 3         | 5.88%   |
| Canada       | 3         | 5.88%   |
| Spain        | 2         | 3.92%   |
| South Africa | 2         | 3.92%   |
| Russia       | 2         | 3.92%   |
| Poland       | 2         | 3.92%   |
| Indonesia    | 2         | 3.92%   |
| Venezuela    | 1         | 1.96%   |
| Sweden       | 1         | 1.96%   |
| Puerto Rico  | 1         | 1.96%   |
| Pakistan     | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Mexico       | 1         | 1.96%   |
| Italy        | 1         | 1.96%   |
| Hungary      | 1         | 1.96%   |
| China        | 1         | 1.96%   |
| Bulgaria     | 1         | 1.96%   |
| Belgium      | 1         | 1.96%   |
| Bangladesh   | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Queens             | 2         | 3.92%   |
| Johannesburg       | 2         | 3.92%   |
| Hamburg            | 2         | 3.92%   |
| Dresden            | 2         | 3.92%   |
| Winterswijk        | 1         | 1.96%   |
| Wejherowo          | 1         | 1.96%   |
| Warsaw             | 1         | 1.96%   |
| Uppsala            | 1         | 1.96%   |
| Thiruvananthapuram | 1         | 1.96%   |
| Suzhou             | 1         | 1.96%   |
| South Tangerang    | 1         | 1.96%   |
| Sofia              | 1         | 1.96%   |
| Saint-Brieuc       | 1         | 1.96%   |
| Rome               | 1         | 1.96%   |
| Regina             | 1         | 1.96%   |
| Redlands           | 1         | 1.96%   |
| Penza              | 1         | 1.96%   |
| Parla              | 1         | 1.96%   |
| Paris              | 1         | 1.96%   |
| Ottawa             | 1         | 1.96%   |
| Mangalore          | 1         | 1.96%   |
| Los Angeles        | 1         | 1.96%   |
| Lille              | 1         | 1.96%   |
| Land O' Lakes      | 1         | 1.96%   |
| Lahore             | 1         | 1.96%   |
| Kennewick          | 1         | 1.96%   |
| Irapuato           | 1         | 1.96%   |
| Huntersville       | 1         | 1.96%   |
| Houston            | 1         | 1.96%   |
| Guglingen          | 1         | 1.96%   |
| Guanare            | 1         | 1.96%   |
| Gistel             | 1         | 1.96%   |
| Gardony            | 1         | 1.96%   |
| Essen              | 1         | 1.96%   |
| Dhaka              | 1         | 1.96%   |
| Columbia           | 1         | 1.96%   |
| Coimbatore         | 1         | 1.96%   |
| Castelginest       | 1         | 1.96%   |
| Calgary            | 1         | 1.96%   |
| Boulder            | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 7         | 8      | 10.77%  |
| Samsung Electronics         | 7         | 7      | 10.77%  |
| SK hynix                    | 5         | 5      | 7.69%   |
| Seagate                     | 4         | 4      | 6.15%   |
| Intel                       | 4         | 5      | 6.15%   |
| Sandisk                     | 3         | 3      | 4.62%   |
| Kingston                    | 3         | 3      | 4.62%   |
| Unknown                     | 2         | 3      | 3.08%   |
| Toshiba                     | 2         | 2      | 3.08%   |
| Plextor                     | 2         | 2      | 3.08%   |
| Netac                       | 2         | 2      | 3.08%   |
| LITEONIT                    | 2         | 5      | 3.08%   |
| KIOXIA                      | 2         | 2      | 3.08%   |
| Kingston Technology Company | 2         | 2      | 3.08%   |
| Hitachi                     | 2         | 3      | 3.08%   |
| HGST                        | 2         | 2      | 3.08%   |
| Union Memory                | 1         | 1      | 1.54%   |
| Transcend                   | 1         | 1      | 1.54%   |
| SSSTC                       | 1         | 1      | 1.54%   |
| Micron Technology           | 1         | 1      | 1.54%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.54%   |
| Lite-On Technology          | 1         | 1      | 1.54%   |
| Lenovo                      | 1         | 1      | 1.54%   |
| HJDK                        | 1         | 1      | 1.54%   |
| Emtec                       | 1         | 2      | 1.54%   |
| Dell                        | 1         | 2      | 1.54%   |
| Crucial                     | 1         | 2      | 1.54%   |
| China                       | 1         | 1      | 1.54%   |
| ASMT                        | 1         | 2      | 1.54%   |
| A-DATA Technology           | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                             | 2         | 3.03%   |
| SK hynix SC311 SATA 256GB SSD                      | 2         | 3.03%   |
| HGST HTS541010A9E680 1TB                           | 2         | 3.03%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 1.52%   |
| WDC WD10SPZX-60Z10T1 1TB                           | 1         | 1.52%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.52%   |
| WDC WD10JPVX-00JC3T0 1TB                           | 1         | 1.52%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB               | 1         | 1.52%   |
| Unknown SD/MMC/MS PRO 256GB                        | 1         | 1.52%   |
| Unknown MMC Card  16GB                             | 1         | 1.52%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB            | 1         | 1.52%   |
| Transcend TS256GMTE220S 256GB                      | 1         | 1.52%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1.52%   |
| Toshiba MK6475GSX 640GB                            | 1         | 1.52%   |
| SSSTC CL1-3D256 256GB                              | 1         | 1.52%   |
| SK hynix PC801 NVMe 1TB                            | 1         | 1.52%   |
| SK hynix NVMe SSD Drive 256GB                      | 1         | 1.52%   |
| SK hynix BC511 NVMe 256GB                          | 1         | 1.52%   |
| Seagate ST9500325AS 500GB                          | 1         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 1.52%   |
| Seagate ST250LM004 HN-M250MBB 250GB                | 1         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.52%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 1         | 1.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 1         | 1.52%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                | 1         | 1.52%   |
| Samsung SSD PM810 FDE 2.5 256GB                    | 1         | 1.52%   |
| Samsung SSD 870 EVO 500GB                          | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 1         | 1.52%   |
| Samsung MZVLQ512HALU-00000 512GB                   | 1         | 1.52%   |
| Samsung MZVLQ128HBHQ-000H1 128GB                   | 1         | 1.52%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                     | 1         | 1.52%   |
| Samsung MZALQ512HALU-000L1 512GB                   | 1         | 1.52%   |
| Plextor PX-256S3C 256GB SSD                        | 1         | 1.52%   |
| Plextor PX-128S3C 128GB SSD                        | 1         | 1.52%   |
| Netac SSD 128GB                                    | 1         | 1.52%   |
| Netac NVMe SSD Drive 2TB                           | 1         | 1.52%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD                | 1         | 1.52%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB | 1         | 1.52%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                     | 1         | 1.52%   |
| LITEONIT LGT-128M6G 128GB SSD                      | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 7      | 35.29%  |
| Seagate | 4         | 4      | 23.53%  |
| Toshiba | 2         | 2      | 11.76%  |
| Hitachi | 2         | 3      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |
| Unknown | 1         | 2      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 13.64%  |
| SK hynix            | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 2      | 9.09%   |
| Plextor             | 2         | 2      | 9.09%   |
| LITEONIT            | 2         | 5      | 9.09%   |
| Intel               | 2         | 3      | 9.09%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| HJDK                | 1         | 1      | 4.55%   |
| Dell                | 1         | 2      | 4.55%   |
| Crucial             | 1         | 2      | 4.55%   |
| China               | 1         | 1      | 4.55%   |
| ASMT                | 1         | 2      | 4.55%   |
| A-DATA Technology   | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 22        | 24     | 36.07%  |
| SSD     | 20        | 29     | 32.79%  |
| HDD     | 17        | 20     | 27.87%  |
| MMC     | 1         | 1      | 1.64%   |
| Unknown | 1         | 2      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 45     | 56.9%   |
| NVMe | 22        | 24     | 37.93%  |
| SAS  | 2         | 6      | 3.45%   |
| MMC  | 1         | 1      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 33     | 67.57%  |
| 0.51-1.0   | 12        | 16     | 32.43%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 36.54%  |
| 251-500    | 13        | 25%     |
| 501-1000   | 9         | 17.31%  |
| 51-100     | 4         | 7.69%   |
| 1001-2000  | 3         | 5.77%   |
| 21-50      | 2         | 3.85%   |
| 1-20       | 2         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 26        | 48.15%  |
| 21-50    | 13        | 24.07%  |
| 51-100   | 7         | 12.96%  |
| 101-250  | 6         | 11.11%  |
| 251-500  | 1         | 1.85%   |
| 501-1000 | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 4      | 50%     |
| HGST HTS541010A9E680 1TB       | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEONIT | 1         | 4      | 50%     |
| HGST     | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 4      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Works    | 26        | 37     | 50%     |
| Detected | 24        | 34     | 46.15%  |
| Malfunc  | 2         | 5      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 31        | 50%     |
| AMD                            | 8         | 12.9%   |
| Samsung Electronics            | 5         | 8.06%   |
| SanDisk                        | 3         | 4.84%   |
| Union Memory (Shenzhen)        | 2         | 3.23%   |
| SK hynix                       | 2         | 3.23%   |
| Kingston Technology Company    | 2         | 3.23%   |
| Toshiba America Info Systems   | 1         | 1.61%   |
| Solid State Storage Technology | 1         | 1.61%   |
| Silicon Motion                 | 1         | 1.61%   |
| Netac Technology               | 1         | 1.61%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.61%   |
| Marvell Technology Group       | 1         | 1.61%   |
| Lite-On Technology             | 1         | 1.61%   |
| Lenovo                         | 1         | 1.61%   |
| KIOXIA                         | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 12.7%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 6.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 6.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 4.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 3.17%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 1.59%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 1.59%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.59%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 1.59%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 1.59%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.59%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.59%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.59%   |
| Netac PCIe 3 NVMe SSD (DRAM-less)                                              | 1         | 1.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.59%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.59%   |
| Lite-On CX2-8B256, CX2-8B512 NVMe SSD                                          | 1         | 1.59%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                 | 1         | 1.59%   |
| KIOXIA NVMe SSD Controller XG7                                                 | 1         | 1.59%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 1         | 1.59%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.59%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.59%   |
| Intel SSD 660P Series                                                          | 1         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.59%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.59%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 54.24%  |
| NVMe | 22        | 37.29%  |
| RAID | 4         | 6.78%   |
| IDE  | 1         | 1.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 76.47%  |
| AMD    | 12        | 23.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 5.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.92%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.96%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.96%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 1.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.96%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 1.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.96%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.96%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.96%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.96%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.96%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.96%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.96%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 1         | 1.96%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.96%   |
| Intel Celeron N4020C CPU @ 1.10GHz            | 1         | 1.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.96%   |
| Intel Celeron CPU N2820 @ 2.13GHz             | 1         | 1.96%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.96%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 1.96%   |
| Intel 13th Gen Core i7-13800H                 | 1         | 1.96%   |
| Intel 13th Gen Core i7-1355U                  | 1         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.96%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 1         | 1.96%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.96%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.96%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 21.57%  |
| Intel Core i7           | 9         | 17.65%  |
| Other                   | 7         | 13.73%  |
| Intel Core i3           | 4         | 7.84%   |
| Intel Celeron           | 4         | 7.84%   |
| AMD Ryzen 7             | 4         | 7.84%   |
| Intel Pentium           | 2         | 3.92%   |
| AMD Ryzen 5             | 2         | 3.92%   |
| AMD A12                 | 2         | 3.92%   |
| Intel Xeon              | 1         | 1.96%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Atom              | 1         | 1.96%   |
| AMD Ryzen 3             | 1         | 1.96%   |
| AMD A6                  | 1         | 1.96%   |
| AMD A10                 | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 45.1%   |
| 4      | 17        | 33.33%  |
| 8      | 4         | 7.84%   |
| 6      | 4         | 7.84%   |
| 14     | 1         | 1.96%   |
| 10     | 1         | 1.96%   |
| 1      | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 41        | 80.39%  |
| 1      | 10        | 19.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 13.21%  |
| 0x806ec    | 4         | 7.55%   |
| 0x306a9    | 4         | 7.55%   |
| 0x806c1    | 3         | 5.66%   |
| 0x40651    | 3         | 5.66%   |
| 0x806ea    | 2         | 3.77%   |
| 0x806d1    | 2         | 3.77%   |
| 0x206a7    | 2         | 3.77%   |
| 0x08600106 | 2         | 3.77%   |
| 0x08108109 | 2         | 3.77%   |
| 0x0600611a | 2         | 3.77%   |
| 0xb06a3    | 1         | 1.89%   |
| 0xa0652    | 1         | 1.89%   |
| 0x906ed    | 1         | 1.89%   |
| 0x906ea    | 1         | 1.89%   |
| 0x806e9    | 1         | 1.89%   |
| 0x406e3    | 1         | 1.89%   |
| 0x406c4    | 1         | 1.89%   |
| 0x306d4    | 1         | 1.89%   |
| 0x306c3    | 1         | 1.89%   |
| 0x30678    | 1         | 1.89%   |
| 0x30673    | 1         | 1.89%   |
| 0x20655    | 1         | 1.89%   |
| 0x106ca    | 1         | 1.89%   |
| 0x1067a    | 1         | 1.89%   |
| 0x0a50000c | 1         | 1.89%   |
| 0x08608103 | 1         | 1.89%   |
| 0x0810100b | 1         | 1.89%   |
| 0x06006705 | 1         | 1.89%   |
| 0x06006704 | 1         | 1.89%   |
| 0x06006110 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 21.57%  |
| Haswell          | 5         | 9.8%    |
| Excavator        | 5         | 9.8%    |
| IvyBridge        | 4         | 7.84%   |
| TigerLake        | 3         | 5.88%   |
| Silvermont       | 3         | 5.88%   |
| Zen+             | 2         | 3.92%   |
| Zen 2            | 2         | 3.92%   |
| SandyBridge      | 2         | 3.92%   |
| Icelake          | 2         | 3.92%   |
| Alderlake Hybrid | 2         | 3.92%   |
| Zen 3            | 1         | 1.96%   |
| Zen              | 1         | 1.96%   |
| Westmere         | 1         | 1.96%   |
| Skylake          | 1         | 1.96%   |
| Penryn           | 1         | 1.96%   |
| Goldmont plus    | 1         | 1.96%   |
| CometLake        | 1         | 1.96%   |
| Broadwell        | 1         | 1.96%   |
| Bonnell          | 1         | 1.96%   |
| Unknown          | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 57.14%  |
| Nvidia | 14        | 22.22%  |
| AMD    | 13        | 20.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 6.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 6.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 4.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 4.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 4.69%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.13%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.56%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.56%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.56%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 1.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.56%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 1.56%   |
| Nvidia GA107GLM [RTX A1000 6GB Laptop GPU]                                               | 1         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.56%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.56%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                                    | 1         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.56%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 1.56%   |
| Intel HD Graphics                                                                        | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 49.02%  |
| Intel + Nvidia | 10        | 19.61%  |
| 1 x AMD        | 10        | 19.61%  |
| 1 x Nvidia     | 3         | 5.88%   |
| 2 x AMD        | 1         | 1.96%   |
| Intel + AMD    | 1         | 1.96%   |
| AMD + Nvidia   | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 90.2%   |
| Proprietary | 4         | 7.84%   |
| Unknown     | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 60.78%  |
| 0.01-0.5   | 9         | 17.65%  |
| 5.01-6.0   | 4         | 7.84%   |
| 1.01-2.0   | 4         | 7.84%   |
| 3.01-4.0   | 2         | 3.92%   |
| 0.51-1.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 22.22%  |
| LG Display              | 9         | 16.67%  |
| BOE                     | 9         | 16.67%  |
| Samsung Electronics     | 7         | 12.96%  |
| PANDA                   | 4         | 7.41%   |
| Chimei Innolux          | 4         | 7.41%   |
| Sharp                   | 2         | 3.7%    |
| InfoVision              | 2         | 3.7%    |
| Seiki                   | 1         | 1.85%   |
| HannStar                | 1         | 1.85%   |
| Dell                    | 1         | 1.85%   |
| Chi Mei Optoelectronics | 1         | 1.85%   |
| BenQ                    | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 2         | 3.7%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 3.7%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 1.85%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 1.85%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 1.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4164 3840x2400 344x215mm 16.0-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 1.85%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch                  | 1         | 1.85%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.85%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 1.85%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 1.85%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 1.85%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 1.85%   |
| HannStar LCD Monitor HSD0001 1920x1080 309x174mm 14.0-inch               | 1         | 1.85%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                       | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1510 1920x1080 344x193mm 15.5-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.85%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE08C5 1920x1080 380x210mm 17.1-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE0810 1920x1080 309x173mm 13.9-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 1.85%   |
| BOE LCD Monitor BOE06FD 1920x1080 294x165mm 13.3-inch                    | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 30        | 56.6%   |
| 1366x768 (WXGA)  | 15        | 28.3%   |
| 3840x2160 (4K)   | 3         | 5.66%   |
| 1600x900 (HD+)   | 2         | 3.77%   |
| 3840x2400        | 1         | 1.89%   |
| 3200x1800 (QHD+) | 1         | 1.89%   |
| 2560x1600        | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 20        | 37.04%  |
| 14     | 10        | 18.52%  |
| 13     | 8         | 14.81%  |
| 17     | 7         | 12.96%  |
| 31     | 3         | 5.56%   |
| 16     | 2         | 3.7%    |
| 11     | 2         | 3.7%    |
| 24     | 1         | 1.85%   |
| 21     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 66.67%  |
| 351-400     | 7         | 12.96%  |
| 201-300     | 6         | 11.11%  |
| 601-700     | 3         | 5.56%   |
| 501-600     | 1         | 1.85%   |
| 401-500     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 95.92%  |
| 16/10 | 2         | 4.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 37.04%  |
| 81-90          | 14        | 25.93%  |
| 121-130        | 7         | 12.96%  |
| 71-80          | 4         | 7.41%   |
| 351-500        | 3         | 5.56%   |
| 51-60          | 2         | 3.7%    |
| 201-250        | 2         | 3.7%    |
| 111-120        | 2         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 50.94%  |
| 101-120       | 14        | 26.42%  |
| More than 240 | 4         | 7.55%   |
| 51-100        | 4         | 7.55%   |
| 161-240       | 3         | 5.66%   |
| 1-50          | 1         | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 86.27%  |
| 2     | 5         | 9.8%    |
| 0     | 2         | 3.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 26        | 32.91%  |
| Intel                           | 25        | 31.65%  |
| Qualcomm Atheros                | 14        | 17.72%  |
| Broadcom Limited                | 4         | 5.06%   |
| Broadcom                        | 3         | 3.8%    |
| TP-Link                         | 1         | 1.27%   |
| Sierra Wireless                 | 1         | 1.27%   |
| Samsung Electronics             | 1         | 1.27%   |
| Ralink Technology               | 1         | 1.27%   |
| Qualcomm Atheros Communications | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| ASIX Electronics                | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 14.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 4.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 4.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 3.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 3.09%   |
| Intel Wireless 7260                                                    | 3         | 3.09%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 3.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 3.09%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 2.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 2.06%   |
| Intel Wireless 8265 / 8275                                             | 2         | 2.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.06%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.06%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 1.03%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 1.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 1.03%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 1.03%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.03%   |
| MediaTek moto e22                                                      | 1         | 1.03%   |
| Intel Wireless 7265                                                    | 1         | 1.03%   |
| Intel Wireless 3165                                                    | 1         | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 1         | 1.03%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.03%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 41.82%  |
| Qualcomm Atheros                | 13        | 23.64%  |
| Realtek Semiconductor           | 11        | 20%     |
| Broadcom                        | 3         | 5.45%   |
| Broadcom Limited                | 2         | 3.64%   |
| Sierra Wireless                 | 1         | 1.82%   |
| Ralink Technology               | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 4         | 7.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 4         | 7.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 3         | 5.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 3         | 5.45%   |
| Intel Wireless 7260                                         | 3         | 5.45%   |
| Intel Wi-Fi 6 AX200                                         | 3         | 5.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 3         | 5.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 3.64%   |
| Intel Wireless 8265 / 8275                                  | 2         | 3.64%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 2         | 3.64%   |
| Intel Wi-Fi 6 AX201                                         | 2         | 3.64%   |
| Sierra Wireless EM7345 4G LTE                               | 1         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 1         | 1.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 1         | 1.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter         | 1         | 1.82%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 1.82%   |
| Ralink MT7601U Wireless Adapter                             | 1         | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                             | 1         | 1.82%   |
| Intel Wireless 7265                                         | 1         | 1.82%   |
| Intel Wireless 3165                                         | 1         | 1.82%   |
| Intel Raptor Lake PCH CNVi WiFi                             | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.82%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.82%   |
| Intel Centrino Ultimate-N 6300                              | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 1         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 1         | 1.82%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                     | 1         | 1.82%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 1.82%   |
| Broadcom BCM43225 802.11b/g/n                               | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                               | 1         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 56.1%   |
| Intel                 | 10        | 24.39%  |
| Qualcomm Atheros      | 2         | 4.88%   |
| Broadcom Limited      | 2         | 4.88%   |
| TP-Link               | 1         | 2.44%   |
| Samsung Electronics   | 1         | 2.44%   |
| MediaTek              | 1         | 2.44%   |
| ASIX Electronics      | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 9.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 7.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 4.76%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 2.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.38%   |
| MediaTek moto e22                                                      | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.38%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 2.38%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 2.38%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.38%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 2.38%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 1         | 2.38%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 56.04%  |
| Ethernet | 40        | 43.96%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 64.29%  |
| Ethernet | 20        | 35.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 64.71%  |
| 1     | 17        | 33.33%  |
| 0     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 74.51%  |
| Yes  | 13        | 25.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 46.67%  |
| Realtek Semiconductor           | 8         | 17.78%  |
| Qualcomm Atheros Communications | 8         | 17.78%  |
| Foxconn / Hon Hai               | 3         | 6.67%   |
| Broadcom                        | 2         | 4.44%   |
| Lite-On Technology              | 1         | 2.22%   |
| IMC Networks                    | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 15.56%  |
| Realtek Bluetooth Radio                             | 6         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 13.33%  |
| Intel AX201 Bluetooth                               | 6         | 13.33%  |
| Intel AX200 Bluetooth                               | 3         | 6.67%   |
| Intel AX210 Bluetooth                               | 2         | 4.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 4.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.22%   |
| Lite-On Bluetooth Device                            | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Intel Bluetooth Device                              | 1         | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.22%   |
| IMC Networks Bluetooth Device                       | 1         | 2.22%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.22%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 39        | 60.94%  |
| AMD                  | 12        | 18.75%  |
| Nvidia               | 10        | 15.63%  |
| C-Media Electronics  | 2         | 3.13%   |
| Conrad Electronic SE | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 8.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 7.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 6.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 4         | 5%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 3.75%   |
| Nvidia Audio device                                                                               | 2         | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.5%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.5%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.25%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.25%   |
| Conrad Electronic SE MIDI Cable UA0037                                                            | 1         | 1.25%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.25%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 27.03%  |
| SK hynix            | 8         | 21.62%  |
| Micron Technology   | 6         | 16.22%  |
| Kingston            | 5         | 13.51%  |
| Elpida              | 3         | 8.11%   |
| Unknown (0x0100)    | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |
| Timetec             | 1         | 2.7%    |
| Crucial             | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 4.88%   |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s                     | 2         | 4.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.44%   |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s                | 1         | 2.44%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 2.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 2.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 2.44%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.44%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 2.44%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 2.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.44%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.44%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 1         | 2.44%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.44%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.44%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.44%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s                     | 1         | 2.44%   |
| Kingston RAM 9905703-026.A00G 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.44%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 2.44%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 800MT/s | 1         | 2.44%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.44%   |
| Unknown                                                                   | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 53.57%  |
| DDR3   | 8         | 28.57%  |
| LPDDR3 | 3         | 10.71%  |
| LPDDR5 | 1         | 3.57%   |
| DDR2   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 82.14%  |
| Row Of Chips | 5         | 17.86%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 43.33%  |
| 4096  | 11        | 36.67%  |
| 16384 | 3         | 10%     |
| 2048  | 2         | 6.67%   |
| 32768 | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 27.27%  |
| 1600  | 7         | 21.21%  |
| 2667  | 5         | 15.15%  |
| 2133  | 3         | 9.09%   |
| 2400  | 2         | 6.06%   |
| 1866  | 2         | 6.06%   |
| 1333  | 2         | 6.06%   |
| 6400  | 1         | 3.03%   |
| 800   | 1         | 3.03%   |
| 667   | 1         | 3.03%   |

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
| IMC Networks                           | 5         | 11.36%  |
| Microdia                               | 4         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 9.09%   |
| Bison Electronics                      | 4         | 9.09%   |
| Suyin                                  | 3         | 6.82%   |
| Realtek Semiconductor                  | 3         | 6.82%   |
| Luxvisions Innotech Limited            | 3         | 6.82%   |
| USB Camera                             | 1         | 2.27%   |
| Syntek                                 | 1         | 2.27%   |
| SunplusIT                              | 1         | 2.27%   |
| Sunplus Innovation Technology          | 1         | 2.27%   |
| Acer                                   | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 8.89%   |
| Chicony HP Truevision HD                                                 | 3         | 6.67%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 4.44%   |
| Microdia Integrated Webcam HD                                            | 2         | 4.44%   |
| Chicony Integrated HP HD Webcam                                          | 2         | 4.44%   |
| Bison Integrated Camera                                                  | 2         | 4.44%   |
| USB Camera USB Camera                                                    | 1         | 2.22%   |
| Syntek Integrated Camera                                                 | 1         | 2.22%   |
| Suyin HP Truevision HD                                                   | 1         | 2.22%   |
| Suyin HD WebCam                                                          | 1         | 2.22%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 2.22%   |
| SunplusIT HD Webcam                                                      | 1         | 2.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 2.22%   |
| Realtek EasyCamera                                                       | 1         | 2.22%   |
| Microdia Lenovo EasyCamera                                               | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera                            | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.22%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 2.22%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 2.22%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.22%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 2.22%   |
| Chicony Lenovo EasyCamera                                                | 1         | 2.22%   |
| Chicony Integrated RGB Camera                                            | 1         | 2.22%   |
| Chicony HP TrueVision HD Camera                                          | 1         | 2.22%   |
| Chicony HD WebCam                                                        | 1         | 2.22%   |
| Chicony EasyCamera                                                       | 1         | 2.22%   |
| Chicony 8M Camera                                                        | 1         | 2.22%   |
| Chicony 720p HD Camera                                                   | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam             | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision FHD Camera         | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.22%   |
| Bison USB Camera                                                         | 1         | 2.22%   |
| Bison Lenovo EasyCamera                                                  | 1         | 2.22%   |
| Acer HD Webcam                                                           | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 70%     |
| Synaptics             | 2         | 20%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                          | 2         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader      | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor        | 1         | 10%     |
| Validity Sensors Fingerprint scanner             | 1         | 10%     |
| Synaptics UWP WBDI Device                        | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 10%     |
| Elan ELAN:ARM-M4                                 | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 50%     |
| SCM Microsystems | 1         | 25%     |
| Alcor Micro      | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 25%     |
| Broadcom 58200                                         | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 25        | 49.02%  |
| 1     | 19        | 37.25%  |
| 2     | 6         | 11.76%  |
| 7     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 27.78%  |
| Graphics card         | 8         | 22.22%  |
| Net/wireless          | 6         | 16.67%  |
| Multimedia controller | 5         | 13.89%  |
| Bluetooth             | 2         | 5.56%   |
| Storage               | 1         | 2.78%   |
| Sound                 | 1         | 2.78%   |
| Firewire controller   | 1         | 2.78%   |
| Chipcard              | 1         | 2.78%   |
| Camera                | 1         | 2.78%   |

