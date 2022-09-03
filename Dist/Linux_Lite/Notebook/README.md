Linux Lite - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux Lite.

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

Total: 75

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu  | FMVNQ8P6                    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| ASUSTek  | UX303LN                     | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Lenovo   | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple    | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek  | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| HP       | Pavilion g4                 | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek  | X555YI                      | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP       | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Samsung  | 530XBB                      | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Minix    | Z64 V1.2                    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Dell     | Inspiron 16 5620            | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix    | Z64 V1.2                    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell     | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo   | IdeaPad Gaming 3 15IHU6 ... | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer     | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Acer     | Aspire 1410                 | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo   | ThinkPad T400 6475E13       | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell     | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| Insignia | NS-P11W7100                 | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell     | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| HP       | 15 Notebook PC              | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| HP       | Compaq CQ45                 | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek  | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer     | Aspire A315-53              | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| Acer     | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP       | Laptop 15-dw3xxx            | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| HP       | Compaq nw9440 (EY615ET#A... | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP       | Pavilion dv6500             | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek  | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek  | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| ASUSTek  | X541SA                      | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP       | Pavilion dv6500             | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| Acer     | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| HP       | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP       | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung  | 905S3G/906S3G/915S3G/930... | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer     | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell     | MXG061                      | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Acer     | Swift SF314-56              | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer     | Swift SF314-56              | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| Dell     | Vostro1710                  | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell     | Inspiron 5452               | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| HP       | EliteBook Folio 9470m       | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek  | X541SA                      | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP       | Laptop 14-cm0xxx            | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP       | Laptop 14-cm0xxx            | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu  | LIFEBOOK U747               | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop E203... | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek  | K50IE                       | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| ASUSTek  | K54LY                       | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer     | Aspire V5-552               | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP       | Compaq 6735b                | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell     | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP       | Laptop 17-by2xxx            | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer     | Predator PH317-52           | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| HP       | 655                         | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP       | 655                         | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba  | Satellite T215D             | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba  | Satellite T215D             | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Lenovo   | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek  | 1001PX                      | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer     | Aspire 5750                 | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer     | Aspire 5750                 | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| Dell     | Latitude D530               | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| Acer     | Aspire ES1-511              | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google   | Chell                       | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek  | X751LD                      | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek  | X751LD                      | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo   | 3000 V200 0764A11           | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR       | ST Pro-KN                   | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| ASUSTek  | N750JK                      | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung  | NC110P/NC108P/NC111P        | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek  | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Linux Lite 5.8 | 12        | 20.69%  |
| Linux Lite 5.4 | 9         | 15.52%  |
| Linux Lite 5.2 | 9         | 15.52%  |
| Linux Lite 5.0 | 8         | 13.79%  |
| Linux Lite 6.0 | 7         | 12.07%  |
| Linux Lite 5.6 | 7         | 12.07%  |
| Linux Lite 3.8 | 3         | 5.17%   |
| Linux Lite 4.8 | 2         | 3.45%   |
| Linux Lite 4.4 | 1         | 1.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Lite | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-40-generic                   | 4         | 6.45%   |
| 5.4.0-70-generic                   | 3         | 4.84%   |
| 5.4.0-52-generic                   | 3         | 4.84%   |
| 5.4.0-109-generic                  | 3         | 4.84%   |
| 5.15.0-33-generic                  | 3         | 4.84%   |
| 5.4.0-90-generic                   | 2         | 3.23%   |
| 5.4.0-81-generic                   | 2         | 3.23%   |
| 5.4.0-74-generic                   | 2         | 3.23%   |
| 5.4.0-58-generic                   | 2         | 3.23%   |
| 5.4.0-42-generic                   | 2         | 3.23%   |
| 5.4.0-107-generic                  | 2         | 3.23%   |
| 5.4.0-104-generic                  | 2         | 3.23%   |
| 5.4.0-96-generic                   | 1         | 1.61%   |
| 5.4.0-94-generic                   | 1         | 1.61%   |
| 5.4.0-91-generic                   | 1         | 1.61%   |
| 5.4.0-88-generic                   | 1         | 1.61%   |
| 5.4.0-77-generic                   | 1         | 1.61%   |
| 5.4.0-71-generic                   | 1         | 1.61%   |
| 5.4.0-66-generic                   | 1         | 1.61%   |
| 5.4.0-65-generic                   | 1         | 1.61%   |
| 5.4.0-56-generic                   | 1         | 1.61%   |
| 5.4.0-48-generic                   | 1         | 1.61%   |
| 5.4.0-33-generic                   | 1         | 1.61%   |
| 5.4.0-124-generic                  | 1         | 1.61%   |
| 5.4.0-122-generic                  | 1         | 1.61%   |
| 5.4.0-113-generic                  | 1         | 1.61%   |
| 5.4.0-110-generic                  | 1         | 1.61%   |
| 5.4.0-105-generic                  | 1         | 1.61%   |
| 5.4.0-100-generic                  | 1         | 1.61%   |
| 5.16.0                             | 1         | 1.61%   |
| 5.15.0-47-generic                  | 1         | 1.61%   |
| 5.15.0-40-generic                  | 1         | 1.61%   |
| 5.15.0-30-generic                  | 1         | 1.61%   |
| 5.15.0-27-generic                  | 1         | 1.61%   |
| 5.13.0-30-lowlatency               | 1         | 1.61%   |
| 5.10.0-051000daily20201222-generic | 1         | 1.61%   |
| 4.4.0-217-generic                  | 1         | 1.61%   |
| 4.4.0-210-generic                  | 1         | 1.61%   |
| 4.15.0-99-generic                  | 1         | 1.61%   |
| 4.15.0-91-generic                  | 1         | 1.61%   |
| 4.15.0-169-generic                 | 1         | 1.61%   |
| 4.15.0-166-generic                 | 1         | 1.61%   |
| 4.15.0-163-generic                 | 1         | 1.61%   |
| 4.15.0-162-generic                 | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 43        | 72.88%  |
| 5.15.0  | 7         | 11.86%  |
| 4.15.0  | 4         | 6.78%   |
| 4.4.0   | 2         | 3.39%   |
| 5.16.0  | 1         | 1.69%   |
| 5.13.0  | 1         | 1.69%   |
| 5.10.0  | 1         | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 43        | 72.88%  |
| 5.15    | 7         | 11.86%  |
| 4.15    | 4         | 6.78%   |
| 4.4     | 2         | 3.39%   |
| 5.16    | 1         | 1.69%   |
| 5.13    | 1         | 1.69%   |
| 5.10    | 1         | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 96.49%  |
| i686   | 2         | 3.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 43        | 75.44%  |
| GNOME   | 12        | 21.05%  |
| Deepin  | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 98.25%  |
| Unknown | 1         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 33        | 55.93%  |
| TDM     | 15        | 25.42%  |
| Unknown | 10        | 16.95%  |
| GDM     | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 28        | 49.12%  |
| pl_PL | 5         | 8.77%   |
| fr_FR | 4         | 7.02%   |
| de_DE | 4         | 7.02%   |
| en_GB | 3         | 5.26%   |
| ru_UA | 2         | 3.51%   |
| ru_RU | 2         | 3.51%   |
| pt_BR | 2         | 3.51%   |
| it_IT | 2         | 3.51%   |
| es_ES | 2         | 3.51%   |
| zh_CN | 1         | 1.75%   |
| es_CO | 1         | 1.75%   |
| en_AU | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 33        | 57.89%  |
| BIOS | 24        | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 48        | 84.21%  |
| Overlay | 6         | 10.53%  |
| Btrfs   | 2         | 3.51%   |
| Zfs     | 1         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 24        | 42.11%  |
| Unknown | 20        | 35.09%  |
| MBR     | 13        | 22.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 85.96%  |
| Yes       | 8         | 14.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 68.97%  |
| Yes       | 18        | 31.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 13        | 22.81%  |
| Hewlett-Packard     | 12        | 21.05%  |
| Acer                | 9         | 15.79%  |
| Dell                | 7         | 12.28%  |
| Lenovo              | 5         | 8.77%   |
| Samsung Electronics | 3         | 5.26%   |
| Fujitsu             | 2         | 3.51%   |
| TR                  | 1         | 1.75%   |
| Toshiba             | 1         | 1.75%   |
| Minix               | 1         | 1.75%   |
| Insignia            | 1         | 1.75%   |
| Google              | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| TR ST Pro-KN                           | 1         | 1.75%   |
| Toshiba Satellite T215D                | 1         | 1.75%   |
| Samsung NC110P/NC108P/NC111P           | 1         | 1.75%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 1.75%   |
| Samsung 530XBB                         | 1         | 1.75%   |
| Minix Z64                              | 1         | 1.75%   |
| Lenovo ThinkPad T400 6475E13           | 1         | 1.75%   |
| Lenovo ThinkPad L480 20LS001AMC        | 1         | 1.75%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1    | 1         | 1.75%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 1         | 1.75%   |
| Lenovo 3000 V200 0764A11               | 1         | 1.75%   |
| Insignia NS-P11W7100                   | 1         | 1.75%   |
| HP Pavilion g4                         | 1         | 1.75%   |
| HP Pavilion dv6500                     | 1         | 1.75%   |
| HP Laptop 17-by2xxx                    | 1         | 1.75%   |
| HP Laptop 15-dw3xxx                    | 1         | 1.75%   |
| HP Laptop 14-cm0xxx                    | 1         | 1.75%   |
| HP EliteBook Folio 9470m               | 1         | 1.75%   |
| HP EliteBook 8440p                     | 1         | 1.75%   |
| HP Compaq nw9440 (EY615ET#ABU)         | 1         | 1.75%   |
| HP Compaq CQ45                         | 1         | 1.75%   |
| HP Compaq 2510p                        | 1         | 1.75%   |
| HP 655                                 | 1         | 1.75%   |
| HP 15 Notebook PC                      | 1         | 1.75%   |
| Google Chell                           | 1         | 1.75%   |
| Fujitsu LIFEBOOK U747                  | 1         | 1.75%   |
| Fujitsu FMVNQ8P6                       | 1         | 1.75%   |
| Dell Vostro1710                        | 1         | 1.75%   |
| Dell MXG071                            | 1         | 1.75%   |
| Dell MXG061                            | 1         | 1.75%   |
| Dell Latitude D530                     | 1         | 1.75%   |
| Dell Inspiron 7559                     | 1         | 1.75%   |
| Dell Inspiron 5452                     | 1         | 1.75%   |
| Dell Inspiron 16 5620                  | 1         | 1.75%   |
| ASUS X751LD                            | 1         | 1.75%   |
| ASUS X555YI                            | 1         | 1.75%   |
| ASUS X541SA                            | 1         | 1.75%   |
| ASUS X540YA                            | 1         | 1.75%   |
| ASUS VivoBook_ASUSLaptop E203NA_E203NA | 1         | 1.75%   |
| ASUS VivoBook 14_ASUS Laptop X407UAR   | 1         | 1.75%   |
| ASUS UX303LN                           | 1         | 1.75%   |
| ASUS N750JK                            | 1         | 1.75%   |
| ASUS N53Jf                             | 1         | 1.75%   |
| ASUS K54LY                             | 1         | 1.75%   |
| ASUS K50IE                             | 1         | 1.75%   |
| ASUS 900                               | 1         | 1.75%   |
| ASUS 1001PX                            | 1         | 1.75%   |
| Apple MacBookAir6,1                    | 1         | 1.75%   |
| Acer Swift SF314-56                    | 1         | 1.75%   |
| Acer Predator PH317-52                 | 1         | 1.75%   |
| Acer Extensa 5220                      | 1         | 1.75%   |
| Acer Aspire V5-552                     | 1         | 1.75%   |
| Acer Aspire ES1-511                    | 1         | 1.75%   |
| Acer Aspire A315-53                    | 1         | 1.75%   |
| Acer Aspire 5750                       | 1         | 1.75%   |
| Acer Aspire 5600                       | 1         | 1.75%   |
| Acer Aspire 1410                       | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 6         | 10.53%  |
| HP Laptop            | 3         | 5.26%   |
| HP Compaq            | 3         | 5.26%   |
| Dell Inspiron        | 3         | 5.26%   |
| Lenovo ThinkPad      | 2         | 3.51%   |
| Lenovo IdeaPad       | 2         | 3.51%   |
| HP Pavilion          | 2         | 3.51%   |
| HP EliteBook         | 2         | 3.51%   |
| ASUS VivoBook        | 2         | 3.51%   |
| TR ST                | 1         | 1.75%   |
| Toshiba Satellite    | 1         | 1.75%   |
| Samsung NC110P       | 1         | 1.75%   |
| Samsung 905S3G       | 1         | 1.75%   |
| Samsung 530XBB       | 1         | 1.75%   |
| Minix Z64            | 1         | 1.75%   |
| Lenovo 3000          | 1         | 1.75%   |
| Insignia NS-P11W7100 | 1         | 1.75%   |
| HP 655               | 1         | 1.75%   |
| HP 15                | 1         | 1.75%   |
| Google Chell         | 1         | 1.75%   |
| Fujitsu LIFEBOOK     | 1         | 1.75%   |
| Fujitsu FMVNQ8P6     | 1         | 1.75%   |
| Dell Vostro1710      | 1         | 1.75%   |
| Dell MXG071          | 1         | 1.75%   |
| Dell MXG061          | 1         | 1.75%   |
| Dell Latitude        | 1         | 1.75%   |
| ASUS X751LD          | 1         | 1.75%   |
| ASUS X555YI          | 1         | 1.75%   |
| ASUS X541SA          | 1         | 1.75%   |
| ASUS X540YA          | 1         | 1.75%   |
| ASUS UX303LN         | 1         | 1.75%   |
| ASUS N750JK          | 1         | 1.75%   |
| ASUS N53Jf           | 1         | 1.75%   |
| ASUS K54LY           | 1         | 1.75%   |
| ASUS K50IE           | 1         | 1.75%   |
| ASUS 900             | 1         | 1.75%   |
| ASUS 1001PX          | 1         | 1.75%   |
| Apple MacBookAir6    | 1         | 1.75%   |
| Acer Swift           | 1         | 1.75%   |
| Acer Predator        | 1         | 1.75%   |
| Acer Extensa         | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 7         | 12.28%  |
| 2018 | 6         | 10.53%  |
| 2008 | 6         | 10.53%  |
| 2010 | 5         | 8.77%   |
| 2016 | 4         | 7.02%   |
| 2015 | 4         | 7.02%   |
| 2012 | 4         | 7.02%   |
| 2007 | 4         | 7.02%   |
| 2020 | 3         | 5.26%   |
| 2017 | 3         | 5.26%   |
| 2011 | 3         | 5.26%   |
| 2019 | 2         | 3.51%   |
| 2006 | 2         | 3.51%   |
| 2022 | 1         | 1.75%   |
| 2021 | 1         | 1.75%   |
| 2013 | 1         | 1.75%   |
| 2004 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 94.74%  |
| Enabled  | 3         | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 98.25%  |
| Yes  | 1         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 23        | 40.35%  |
| 4.01-8.0   | 10        | 17.54%  |
| 1.01-2.0   | 10        | 17.54%  |
| 16.01-24.0 | 6         | 10.53%  |
| 8.01-16.0  | 3         | 5.26%   |
| 0.51-1.0   | 3         | 5.26%   |
| 32.01-64.0 | 1         | 1.75%   |
| 2.01-3.0   | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 27        | 45.76%  |
| 2.01-3.0  | 14        | 23.73%  |
| 0.51-1.0  | 9         | 15.25%  |
| 3.01-4.0  | 4         | 6.78%   |
| 0.01-0.5  | 3         | 5.08%   |
| 4.01-8.0  | 1         | 1.69%   |
| 8.01-16.0 | 1         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 84.21%  |
| 2      | 8         | 14.04%  |
| 3      | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 57.89%  |
| Yes       | 24        | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 82.46%  |
| No        | 10        | 17.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 98.25%  |
| No        | 1         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 73.68%  |
| No        | 15        | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 8.77%   |
| Germany     | 5         | 8.77%   |
| France      | 5         | 8.77%   |
| Brazil      | 5         | 8.77%   |
| Ukraine     | 4         | 7.02%   |
| Poland      | 4         | 7.02%   |
| UK          | 3         | 5.26%   |
| Spain       | 3         | 5.26%   |
| Russia      | 3         | 5.26%   |
| Romania     | 3         | 5.26%   |
| Italy       | 2         | 3.51%   |
| Australia   | 2         | 3.51%   |
| Venezuela   | 1         | 1.75%   |
| Turkey      | 1         | 1.75%   |
| Slovakia    | 1         | 1.75%   |
| Philippines | 1         | 1.75%   |
| Netherlands | 1         | 1.75%   |
| Myanmar     | 1         | 1.75%   |
| Mexico      | 1         | 1.75%   |
| Iran        | 1         | 1.75%   |
| Guadeloupe  | 1         | 1.75%   |
| El Salvador | 1         | 1.75%   |
| Colombia    | 1         | 1.75%   |
| Chile       | 1         | 1.75%   |
| Canada      | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Sydney               | 2         | 3.45%   |
| Pabianice            | 2         | 3.45%   |
| Odessa               | 2         | 3.45%   |
| Żywiec              | 1         | 1.72%   |
| Yangon               | 1         | 1.72%   |
| Würzburg            | 1         | 1.72%   |
| Wiesbaden            | 1         | 1.72%   |
| Warsaw               | 1         | 1.72%   |
| Wahroonga            | 1         | 1.72%   |
| Voluntari            | 1         | 1.72%   |
| Vinnytsia            | 1         | 1.72%   |
| Varennes-les-Narcy   | 1         | 1.72%   |
| Valencia             | 1         | 1.72%   |
| Tucape               | 1         | 1.72%   |
| Teresina             | 1         | 1.72%   |
| Tarragona            | 1         | 1.72%   |
| Svidník             | 1         | 1.72%   |
| St. Petersburg       | 1         | 1.72%   |
| Shadrinsk            | 1         | 1.72%   |
| Sao Paulo            | 1         | 1.72%   |
| Sabadell             | 1         | 1.72%   |
| Queretaro            | 1         | 1.72%   |
| Paris                | 1         | 1.72%   |
| Paranaque City       | 1         | 1.72%   |
| Nudlingen            | 1         | 1.72%   |
| Novaci               | 1         | 1.72%   |
| Moscow               | 1         | 1.72%   |
| Milan                | 1         | 1.72%   |
| Marseille            | 1         | 1.72%   |
| Madrid               | 1         | 1.72%   |
| London               | 1         | 1.72%   |
| Les Abymes           | 1         | 1.72%   |
| La Libertad          | 1         | 1.72%   |
| La Glacerie          | 1         | 1.72%   |
| Kyiv                 | 1         | 1.72%   |
| Kingston upon Thames | 1         | 1.72%   |
| Jaraguá do Sul      | 1         | 1.72%   |
| Izmir                | 1         | 1.72%   |
| Gorgan               | 1         | 1.72%   |
| Frankfurt am Main    | 1         | 1.72%   |
| Elk Grove Village    | 1         | 1.72%   |
| Eggenfelden          | 1         | 1.72%   |
| Edmonton             | 1         | 1.72%   |
| Drancy               | 1         | 1.72%   |
| Didsbury             | 1         | 1.72%   |
| Des Moines           | 1         | 1.72%   |
| Cotia                | 1         | 1.72%   |
| Coquimbo             | 1         | 1.72%   |
| Constanța           | 1         | 1.72%   |
| Cheboksary           | 1         | 1.72%   |
| Cabedelo             | 1         | 1.72%   |
| Brooklyn             | 1         | 1.72%   |
| Bondeno              | 1         | 1.72%   |
| Bogotá              | 1         | 1.72%   |
| Unknown              | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 18.75%  |
| WDC                 | 9         | 12     | 14.06%  |
| Toshiba             | 8         | 9      | 12.5%   |
| Samsung Electronics | 7         | 8      | 10.94%  |
| Kingston            | 5         | 5      | 7.81%   |
| Unknown             | 4         | 5      | 6.25%   |
| HGST                | 3         | 3      | 4.69%   |
| SanDisk             | 2         | 2      | 3.13%   |
| Micron Technology   | 2         | 3      | 3.13%   |
| Hitachi             | 2         | 2      | 3.13%   |
| GOODRAM             | 2         | 2      | 3.13%   |
| Crucial             | 2         | 2      | 3.13%   |
| SK hynix            | 1         | 1      | 1.56%   |
| LITEON              | 1         | 1      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| ASUS-PHISON         | 1         | 2      | 1.56%   |
| ASMT                | 1         | 1      | 1.56%   |
| Apple               | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB              | 3         | 4.55%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 4.55%   |
| Unknown MMC Card  32GB                | 2         | 3.03%   |
| Seagate ST9320325AS 320GB             | 2         | 3.03%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1.52%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 1.52%   |
| WDC WD2500BEVE-00A0HT0 250GB          | 1         | 1.52%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1.52%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1.52%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.52%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB  | 1         | 1.52%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB  | 1         | 1.52%   |
| Unknown SD64G  64GB                   | 1         | 1.52%   |
| Unknown NCard  32GB                   | 1         | 1.52%   |
| Unknown DA4064  64GB                  | 1         | 1.52%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1.52%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.52%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1.52%   |
| Toshiba MQ01ABD032V -63 320GB         | 1         | 1.52%   |
| Toshiba MK1011GAH 100GB               | 1         | 1.52%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1.52%   |
| Seagate ST9500423AS 500GB             | 1         | 1.52%   |
| Seagate ST9160823ASG 160GB            | 1         | 1.52%   |
| Seagate ST9160301AS 160GB             | 1         | 1.52%   |
| Seagate ST640LM0 00 HM641JI 640GB     | 1         | 1.52%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1.52%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1.52%   |
| Seagate ST320LM000 HM321HI 320GB      | 1         | 1.52%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 1.52%   |
| SanDisk Z400s M.2 2280 128GB SSD      | 1         | 1.52%   |
| SanDisk DF4032  32GB                  | 1         | 1.52%   |
| Samsung SSD 980 250GB                 | 1         | 1.52%   |
| Samsung PM991a NVMe 1024GB            | 1         | 1.52%   |
| Samsung MZVLB256HAHQ-000L7 256GB      | 1         | 1.52%   |
| Samsung MZVKW512HMJP-00007 512GB      | 1         | 1.52%   |
| Samsung MZMTE128HMGR-00007 128GB SSD  | 1         | 1.52%   |
| Samsung MZMTD128HAFV-000 128GB SSD    | 1         | 1.52%   |
| Samsung HM160HI 160GB                 | 1         | 1.52%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD   | 1         | 1.52%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD   | 1         | 1.52%   |
| LITEON CV5-8Q512 512GB SSD            | 1         | 1.52%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1.52%   |
| Kingston RBUSNS8154P3128GJ1 128GB     | 1         | 1.52%   |
| Intel SSDSA2CW080G3 80GB              | 1         | 1.52%   |
| Hitachi HTS723216L9SA60 160GB         | 1         | 1.52%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1.52%   |
| HGST HTS725050A7E630 500GB            | 1         | 1.52%   |
| HGST HTS721010A9E630 1TB              | 1         | 1.52%   |
| HGST HTS541010A7E630 1TB              | 1         | 1.52%   |
| GOODRAM SSDPR-CL100-120-G3 120GB      | 1         | 1.52%   |
| GOODRAM IR-SSDPR-S25A-240 240GB       | 1         | 1.52%   |
| Crucial CT120BX500SSD1 120GB          | 1         | 1.52%   |
| Crucial CT1000BX500SSD1 1TB           | 1         | 1.52%   |
| ASUS-PHISON SSD 16GB                  | 1         | 1.52%   |
| ASUS-PHISON OB S 4GB SSD              | 1         | 1.52%   |
| ASMT USB 3.0 Destop H 5TB             | 1         | 1.52%   |
| Apple SSD SD0128F 121GB               | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 37.5%   |
| Toshiba             | 8         | 9      | 25%     |
| WDC                 | 5         | 7      | 15.63%  |
| HGST                | 3         | 3      | 9.38%   |
| Hitachi             | 2         | 2      | 6.25%   |
| Samsung Electronics | 1         | 2      | 3.13%   |
| ASMT                | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 20%     |
| WDC                 | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Micron Technology   | 2         | 3      | 10%     |
| GOODRAM             | 2         | 2      | 10%     |
| Crucial             | 2         | 2      | 10%     |
| SK hynix            | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| ASUS-PHISON         | 1         | 2      | 5%      |
| Apple               | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 36     | 50.82%  |
| SSD  | 19        | 22     | 31.15%  |
| NVMe | 6         | 8      | 9.84%   |
| MMC  | 5         | 6      | 8.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 56     | 77.97%  |
| NVMe | 6         | 8      | 10.17%  |
| MMC  | 5         | 6      | 8.47%   |
| SAS  | 2         | 2      | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 45     | 74.51%  |
| 0.51-1.0   | 11        | 11     | 21.57%  |
| 1.01-2.0   | 1         | 1      | 1.96%   |
| 4.01-10.0  | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 36.21%  |
| 251-500        | 14        | 24.14%  |
| 1-20           | 7         | 12.07%  |
| 51-100         | 7         | 12.07%  |
| 21-50          | 4         | 6.9%    |
| 501-1000       | 4         | 6.9%    |
| More than 3000 | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 35        | 59.32%  |
| 21-50     | 11        | 18.64%  |
| 51-100    | 7         | 11.86%  |
| 101-250   | 5         | 8.47%   |
| 2001-3000 | 1         | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS480G2G0A-00JH30 480GB SSD | 1         | 1      | 12.5%   |
| WDC WD10JPVX-22JC3T0 1TB         | 1         | 1      | 12.5%   |
| Toshiba MQ01ABD050 500GB         | 1         | 1      | 12.5%   |
| Seagate ST9500423AS 500GB        | 1         | 1      | 12.5%   |
| Seagate ST9320325AS 320GB        | 1         | 1      | 12.5%   |
| Seagate ST9160823ASG 160GB       | 1         | 1      | 12.5%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 12.5%   |
| Hitachi HTS545016B9A300 160GB    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

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
| Works    | 26        | 30     | 44.83%  |
| Detected | 24        | 34     | 41.38%  |
| Malfunc  | 8         | 8      | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 42        | 71.19%  |
| AMD                         | 8         | 13.56%  |
| Samsung Electronics         | 4         | 6.78%   |
| SanDisk                     | 2         | 3.39%   |
| Nvidia                      | 1         | 1.69%   |
| Marvell Technology Group    | 1         | 1.69%   |
| Kingston Technology Company | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 9.86%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 9.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 5.63%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.82%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 2.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 2.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 2.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 2.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.41%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.41%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.41%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 1.41%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.41%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.41%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 65.15%  |
| IDE  | 13        | 19.7%   |
| NVMe | 6         | 9.09%   |
| RAID | 4         | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 85.96%  |
| AMD    | 8         | 14.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 3.51%   |
| Intel Core 2 CPU T7600 @ 2.33GHz                | 2         | 3.51%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 2         | 3.51%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 1.75%   |
| Intel Pentium CPU N3710 @ 1.60GHz               | 1         | 1.75%   |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 1.75%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 1.75%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 1.75%   |
| Intel Genuine CPU T2050 @ 1.60GHz               | 1         | 1.75%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz                | 1         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 1.75%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 1.75%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 1.75%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 1.75%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 1.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 1.75%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 1         | 1.75%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 1.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 1.75%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 1.75%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 1.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 1.75%   |
| Intel Core 2 Duo CPU U7600 @ 1.20GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 1.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 1.75%   |
| Intel Celeron M processor 900MHz                | 1         | 1.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1         | 1.75%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 1.75%   |
| Intel Celeron CPU B830 @ 1.80GHz                | 1         | 1.75%   |
| Intel Celeron CPU 723 @ 1.20GHz                 | 1         | 1.75%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 1.75%   |
| Intel Atom CPU Z3735F @ 1.33GHz                 | 1         | 1.75%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 1         | 1.75%   |
| Intel Atom CPU N2600 @ 1.60GHz                  | 1         | 1.75%   |
| Intel 12th Gen Core i7-1255U                    | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 1.75%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 1         | 1.75%   |
| AMD Quad-Core Processor (up to 1.4GHz)          | 1         | 1.75%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G   | 1         | 1.75%   |
| AMD E2-1800 APU with Radeon HD Graphics         | 1         | 1.75%   |
| AMD Athlon II Neo K125 Processor                | 1         | 1.75%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 1         | 1.75%   |
| AMD A10-5757M APU with Radeon HD Graphics       | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 15.79%  |
| Intel Core 2 Duo        | 8         | 14.04%  |
| Intel Core i7           | 5         | 8.77%   |
| Intel Core i3           | 5         | 8.77%   |
| Intel Celeron           | 5         | 8.77%   |
| Intel Pentium           | 4         | 7.02%   |
| Intel Atom              | 4         | 7.02%   |
| Other                   | 3         | 5.26%   |
| Intel Core 2            | 2         | 3.51%   |
| AMD E2                  | 2         | 3.51%   |
| AMD A8                  | 2         | 3.51%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Genuine           | 1         | 1.75%   |
| Intel Core m7           | 1         | 1.75%   |
| Intel Celeron M         | 1         | 1.75%   |
| AMD Quad-Core           | 1         | 1.75%   |
| AMD Athlon II Neo       | 1         | 1.75%   |
| AMD A12                 | 1         | 1.75%   |
| AMD A10                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 63.16%  |
| 4      | 15        | 26.32%  |
| 1      | 4         | 7.02%   |
| 10     | 1         | 1.75%   |
| 6      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 52.63%  |
| 2      | 27        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 96.49%  |
| 32-bit         | 2         | 3.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x6fd      | 3         | 5.26%   |
| 0x40651    | 3         | 5.26%   |
| 0x306a9    | 3         | 5.26%   |
| 0x30678    | 3         | 5.26%   |
| 0x206a7    | 3         | 5.26%   |
| 0x1067a    | 3         | 5.26%   |
| Unknown    | 3         | 5.26%   |
| 0x806ea    | 2         | 3.51%   |
| 0x806e9    | 2         | 3.51%   |
| 0x806c1    | 2         | 3.51%   |
| 0x6fb      | 2         | 3.51%   |
| 0x6f6      | 2         | 3.51%   |
| 0x406c3    | 2         | 3.51%   |
| 0x20655    | 2         | 3.51%   |
| 0x10676    | 2         | 3.51%   |
| 0x906ea    | 1         | 1.75%   |
| 0x906e9    | 1         | 1.75%   |
| 0x906a4    | 1         | 1.75%   |
| 0x806ec    | 1         | 1.75%   |
| 0x806eb    | 1         | 1.75%   |
| 0x706a1    | 1         | 1.75%   |
| 0x6d8      | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x506c9    | 1         | 1.75%   |
| 0x406e3    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x306c3    | 1         | 1.75%   |
| 0x30661    | 1         | 1.75%   |
| 0x106ca    | 1         | 1.75%   |
| 0x07030105 | 1         | 1.75%   |
| 0x06006705 | 1         | 1.75%   |
| 0x06006118 | 1         | 1.75%   |
| 0x06001119 | 1         | 1.75%   |
| 0x05000119 | 1         | 1.75%   |
| 0x010000c8 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 8         | 14.04%  |
| Core             | 7         | 12.28%  |
| Silvermont       | 6         | 10.53%  |
| Penryn           | 5         | 8.77%   |
| Haswell          | 4         | 7.02%   |
| SandyBridge      | 3         | 5.26%   |
| IvyBridge        | 3         | 5.26%   |
| Westmere         | 2         | 3.51%   |
| TigerLake        | 2         | 3.51%   |
| Skylake          | 2         | 3.51%   |
| Puma             | 2         | 3.51%   |
| P6               | 2         | 3.51%   |
| Excavator        | 2         | 3.51%   |
| Bonnell          | 2         | 3.51%   |
| Piledriver       | 1         | 1.75%   |
| K10              | 1         | 1.75%   |
| Jaguar           | 1         | 1.75%   |
| Goldmont plus    | 1         | 1.75%   |
| Goldmont         | 1         | 1.75%   |
| Bobcat           | 1         | 1.75%   |
| Alderlake Hybrid | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 67.19%  |
| Nvidia | 12        | 18.75%  |
| AMD    | 9         | 14.06%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 7.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 7.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 4.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.23%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.82%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.41%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.41%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 425M]                                                          | 1         | 1.41%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.41%   |
| Nvidia G84M [GeForce 8700M GT]                                                           | 1         | 1.41%   |
| Nvidia G71M [GeForce Go 7950 GTX]                                                        | 1         | 1.41%   |
| Nvidia G71GLM [Quadro FX 1500M]                                                          | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.41%   |
| Intel VGA compatible controller                                                          | 1         | 1.41%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.41%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.41%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 1.41%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 1.41%   |
| Intel HD Graphics 630                                                                    | 1         | 1.41%   |
| Intel HD Graphics 620                                                                    | 1         | 1.41%   |
| Intel HD Graphics 530                                                                    | 1         | 1.41%   |
| Intel HD Graphics 515                                                                    | 1         | 1.41%   |
| Intel HD Graphics 500                                                                    | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.41%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 1.41%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.41%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.41%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.41%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.41%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 63.16%  |
| 1 x AMD        | 8         | 14.04%  |
| Intel + Nvidia | 7         | 12.28%  |
| 1 x Nvidia     | 5         | 8.77%   |
| 2 x AMD        | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 84.48%  |
| Proprietary | 8         | 13.79%  |
| Unknown     | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 68.42%  |
| 0.01-0.5   | 9         | 15.79%  |
| 0.51-1.0   | 4         | 7.02%   |
| 3.01-4.0   | 2         | 3.51%   |
| 1.01-2.0   | 2         | 3.51%   |
| 5.01-6.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 20%     |
| LG Display              | 9         | 15%     |
| Samsung Electronics     | 8         | 13.33%  |
| Chimei Innolux          | 6         | 10%     |
| BOE                     | 6         | 10%     |
| Chi Mei Optoelectronics | 5         | 8.33%   |
| Goldstar                | 2         | 3.33%   |
| Sony                    | 1         | 1.67%   |
| Seiko/Epson             | 1         | 1.67%   |
| SANYO                   | 1         | 1.67%   |
| PANDA                   | 1         | 1.67%   |
| LG Philips              | 1         | 1.67%   |
| Lenovo                  | 1         | 1.67%   |
| HannStar                | 1         | 1.67%   |
| eMachines               | 1         | 1.67%   |
| CPT                     | 1         | 1.67%   |
| BenQ                    | 1         | 1.67%   |
| Apple                   | 1         | 1.67%   |
| Unknown                 | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                       | 1         | 1.67%   |
| Seiko/Epson LCD Monitor                                                   | 1         | 1.67%   |
| SANYO LCD SAN1207 1360x768                                                | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3845 1280x800 331x207mm 15.4-inch      | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch      | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch      | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDCC34F 3840x2160 344x194mm 15.5-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch      | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch     | 1         | 1.67%   |
| PANDA LCD Monitor NCP0004 1920x1080 294x165mm 13.3-inch                   | 1         | 1.67%   |
| LG Philips LCD Monitor LPL118A 1920x1200 370x230mm 17.2-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch               | 1         | 1.67%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD03E3 1366x768 309x174mm 14.0-inch               | 1         | 1.67%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch               | 1         | 1.67%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch               | 1         | 1.67%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 1         | 1.67%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 1         | 1.67%   |
| Goldstar W2243 GSM56FF 1920x1080 480x270mm 21.7-inch                      | 1         | 1.67%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                     | 1         | 1.67%   |
| eMachines E190HQV EMA0212 1280x1024 440x250mm 19.9-inch                   | 1         | 1.67%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch           | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 293x165mm 13.2-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch           | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1221 1280x800 261x163mm 12.1-inch  | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 1.67%   |
| BOE LCD Monitor BOE09D2 1920x1080 344x194mm 15.5-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 1.67%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 1         | 1.67%   |
| BOE LCD Monitor BOE0662 1366x768 344x194mm 15.5-inch                      | 1         | 1.67%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                     | 1         | 1.67%   |
| BenQ BL2411 BNQ8011 1920x1200 518x324mm 24.1-inch                         | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO44ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO3014 1280x800 261x163mm 12.1-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO219C 1920x1200 344x215mm 16.0-inch            | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO152C 1366x768 293x164mm 13.2-inch             | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO143C 1366x768 309x173mm 13.9-inch             | 1         | 1.67%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 1         | 1.67%   |
| Unknown                                                                   | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 25        | 41.67%  |
| 1920x1080 (FHD)   | 15        | 25%     |
| 1920x1200 (WUXGA) | 6         | 10%     |
| 1280x800 (WXGA)   | 5         | 8.33%   |
| 3840x2160 (4K)    | 2         | 3.33%   |
| 1600x900 (HD+)    | 2         | 3.33%   |
| 3840x2400         | 1         | 1.67%   |
| 1440x900 (WXGA+)  | 1         | 1.67%   |
| 1360x768          | 1         | 1.67%   |
| 1024x600          | 1         | 1.67%   |
| Unknown           | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 19        | 31.67%  |
| 14      | 8         | 13.33%  |
| 13      | 8         | 13.33%  |
| 17      | 7         | 11.67%  |
| 11      | 5         | 8.33%   |
| Unknown | 3         | 5%      |
| 21      | 2         | 3.33%   |
| 12      | 2         | 3.33%   |
| 65      | 1         | 1.67%   |
| 46      | 1         | 1.67%   |
| 24      | 1         | 1.67%   |
| 19      | 1         | 1.67%   |
| 16      | 1         | 1.67%   |
| 10      | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 55%     |
| 201-300     | 11        | 18.33%  |
| 351-400     | 7         | 11.67%  |
| 401-500     | 3         | 5%      |
| Unknown     | 3         | 5%      |
| 1001-1500   | 2         | 3.33%   |
| 501-600     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 75%     |
| 16/10   | 12        | 21.43%  |
| Unknown | 2         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 31.67%  |
| 81-90          | 13        | 21.67%  |
| 51-60          | 5         | 8.33%   |
| 131-140        | 4         | 6.67%   |
| 71-80          | 3         | 5%      |
| 121-130        | 3         | 5%      |
| Unknown        | 3         | 5%      |
| 61-70          | 2         | 3.33%   |
| 201-250        | 2         | 3.33%   |
| More than 1000 | 1         | 1.67%   |
| 41-50          | 1         | 1.67%   |
| 251-300        | 1         | 1.67%   |
| 151-200        | 1         | 1.67%   |
| 111-120        | 1         | 1.67%   |
| 501-1000       | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 21        | 36.21%  |
| 101-120       | 21        | 36.21%  |
| 51-100        | 8         | 13.79%  |
| Unknown       | 3         | 5.17%   |
| More than 240 | 2         | 3.45%   |
| 161-240       | 2         | 3.45%   |
| 1-50          | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 52        | 89.66%  |
| 2     | 6         | 10.34%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 32.18%  |
| Intel                 | 24        | 27.59%  |
| Qualcomm Atheros      | 18        | 20.69%  |
| Broadcom              | 8         | 9.2%    |
| Broadcom Limited      | 4         | 4.6%    |
| Ralink                | 2         | 2.3%    |
| Sierra Wireless       | 1         | 1.15%   |
| Ralink Technology     | 1         | 1.15%   |
| D-Link                | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 17        | 15.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 8         | 7.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 4.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 3.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 3         | 2.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 1.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 2         | 1.87%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 1.87%   |
| Intel Wireless 3165                                                                           | 2         | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 1.87%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 0.93%   |
| Realtek USB 10/100 LAN                                                                        | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                         | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 0.93%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1         | 0.93%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1         | 0.93%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.93%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 0.93%   |
| Intel Wireless 7265                                                                           | 1         | 0.93%   |
| Intel Wireless 7260                                                                           | 1         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                                          | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.93%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 0.93%   |
| Intel Centrino Advanced-N 6200                                                                | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                                      | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                                      | 1         | 0.93%   |
| Intel 82566MM Gigabit Network Connection                                                      | 1         | 0.93%   |
| D-Link WLAN controller                                                                        | 1         | 0.93%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                                      | 1         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                                       | 1         | 0.93%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                           | 1         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                        | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                               | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express                              | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express                              | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 37.29%  |
| Qualcomm Atheros      | 17        | 28.81%  |
| Realtek Semiconductor | 10        | 16.95%  |
| Broadcom              | 3         | 5.08%   |
| Ralink                | 2         | 3.39%   |
| Broadcom Limited      | 2         | 3.39%   |
| Sierra Wireless       | 1         | 1.69%   |
| Ralink Technology     | 1         | 1.69%   |
| D-Link                | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 5         | 8.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 4         | 6.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 5.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 3         | 5.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 5.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 3         | 5.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 2         | 3.39%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 3.39%   |
| Intel Wireless 3165                                                                           | 2         | 3.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 2         | 3.39%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 1         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1         | 1.69%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.69%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 1.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 1.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 1         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 1.69%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)                       | 1         | 1.69%   |
| Intel Wireless 7265                                                                           | 1         | 1.69%   |
| Intel Wireless 7260                                                                           | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 1.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.69%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 1.69%   |
| Intel Centrino Advanced-N 6200                                                                | 1         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 1         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 1         | 1.69%   |
| D-Link WLAN controller                                                                        | 1         | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 1         | 1.69%   |
| Broadcom BCM4311 802.11b/g WLAN                                                               | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 57.45%  |
| Intel                 | 7         | 14.89%  |
| Qualcomm Atheros      | 6         | 12.77%  |
| Broadcom              | 5         | 10.64%  |
| Broadcom Limited      | 2         | 4.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 35.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 16.67%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.17%   |
| Realtek USB 10/100 LAN                                            | 1         | 2.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.08%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 2.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.08%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express          | 1         | 2.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 2.08%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.08%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express  | 1         | 2.08%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 54.37%  |
| Ethernet | 47        | 45.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 77.05%  |
| Ethernet | 14        | 22.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 78.95%  |
| 1     | 11        | 19.3%   |
| 0     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 82.46%  |
| Yes  | 10        | 17.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 30.95%  |
| Realtek Semiconductor           | 7         | 16.67%  |
| IMC Networks                    | 4         | 9.52%   |
| Qualcomm Atheros Communications | 3         | 7.14%   |
| Lite-On Technology              | 3         | 7.14%   |
| Hewlett-Packard                 | 3         | 7.14%   |
| Broadcom                        | 3         | 7.14%   |
| Dell                            | 2         | 4.76%   |
| Toshiba                         | 1         | 2.38%   |
| Ralink                          | 1         | 2.38%   |
| Foxconn / Hon Hai               | 1         | 2.38%   |
| Apple                           | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 6         | 14.29%  |
| Realtek Bluetooth Radio                          | 4         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 3         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                   | 2         | 4.76%   |
| IMC Networks Bluetooth Device                    | 2         | 4.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 2         | 4.76%   |
| Dell Wireless 355 Bluetooth                      | 2         | 4.76%   |
| Broadcom BCM2045 Bluetooth                       | 2         | 4.76%   |
| Toshiba Askey Bluetooth Module                   | 1         | 2.38%   |
| Realtek RTL8821A Bluetooth                       | 1         | 2.38%   |
| Ralink RT3290 Bluetooth                          | 1         | 2.38%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 2.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 2.38%   |
| Lite-On Bluetooth Device                         | 1         | 2.38%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 2.38%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 2.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 2.38%   |
| Intel Bluetooth Device                           | 1         | 2.38%   |
| Intel AX201 Bluetooth                            | 1         | 2.38%   |
| IMC Networks Bluetooth USB Host Controller       | 1         | 2.38%   |
| IMC Networks Bluetooth Radio                     | 1         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 2.38%   |
| Foxconn / Hon Hai BCM20702A0                     | 1         | 2.38%   |
| Broadcom HP Portable Valentine                   | 1         | 2.38%   |
| Apple Bluetooth USB Host Controller              | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 46        | 75.41%  |
| AMD              | 9         | 14.75%  |
| Nvidia           | 4         | 6.56%   |
| Logitech         | 1         | 1.64%   |
| Blue Microphones | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 9.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 6.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 6.76%   |
| AMD FCH Azalia Controller                                                                         | 5         | 6.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 5.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.05%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.7%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Logitech G635 Gaming Headset                                                                      | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.35%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 1.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.35%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 1.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.35%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.35%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.35%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 22.64%  |
| SK hynix            | 10        | 18.87%  |
| Micron Technology   | 7         | 13.21%  |
| Unknown             | 5         | 9.43%   |
| Kingston            | 5         | 9.43%   |
| Elpida              | 3         | 5.66%   |
| Ramaxel Technology  | 2         | 3.77%   |
| Nanya Technology    | 2         | 3.77%   |
| A-DATA Technology   | 2         | 3.77%   |
| Unknown             | 2         | 3.77%   |
| Unknown (ABCD)      | 1         | 1.89%   |
| Transcend           | 1         | 1.89%   |
| Qimonda             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 3.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 3.64%   |
| Unknown                                                             | 2         | 3.64%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1866MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.82%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.82%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.82%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 1.82%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 1.82%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| SK hynix RAM HMT112S6TFR8C-G7 1024MB SODIMM 1066MT/s                | 1         | 1.82%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.82%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.82%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.82%   |
| Samsung RAM M4 70T5669AZ0-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 1.82%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s           | 1         | 1.82%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR 2048MT/s               | 1         | 1.82%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.82%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Qimonda RAM 64T128021EDL2.5B2 1024MB SODIMM DDR2 800MT/s            | 1         | 1.82%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s                | 1         | 1.82%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.82%   |
| Micron RAM 4KTF25664HZ-1G6P1 2GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.82%   |
| Kingston RAM Module 2048MB SODIMM DDR2 667MT/s                      | 1         | 1.82%   |
| Kingston RAM Module 2048MB SODIMM DDR 667MT/s                       | 1         | 1.82%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.82%   |
| Kingston RAM ASU1333D3S9DR8/2G 2048MB SODIMM DDR3 4199MT/s          | 1         | 1.82%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s             | 1         | 1.82%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 1.82%   |
| Elpida RAM FCJ41UG6BBU0-DJ-F 4GB SODIMM DDR3 1600MT/s               | 1         | 1.82%   |
| Elpida RAM EBE21UE8ACUA-8G-E 2GB SODIMM DDR2 975MT/s                | 1         | 1.82%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s                | 1         | 1.82%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s                | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 18        | 39.13%  |
| DDR4    | 11        | 23.91%  |
| DDR2    | 8         | 17.39%  |
| SDRAM   | 4         | 8.7%    |
| LPDDR4  | 3         | 6.52%   |
| DDR     | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 42        | 97.67%  |
| DIMM   | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 17        | 34.69%  |
| 2048  | 15        | 30.61%  |
| 8192  | 10        | 20.41%  |
| 1024  | 6         | 12.24%  |
| 16384 | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 31.91%  |
| 2667    | 7         | 14.89%  |
| 3200    | 4         | 8.51%   |
| 667     | 4         | 8.51%   |
| 975     | 3         | 6.38%   |
| 4199    | 2         | 4.26%   |
| 2400    | 2         | 4.26%   |
| 2048    | 2         | 4.26%   |
| 3266    | 1         | 2.13%   |
| 1866    | 1         | 2.13%   |
| 1334    | 1         | 2.13%   |
| 1333    | 1         | 2.13%   |
| 1066    | 1         | 2.13%   |
| 800     | 1         | 2.13%   |
| 400     | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

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
| Chicony Electronics                    | 13        | 28.26%  |
| Suyin                                  | 5         | 10.87%  |
| Quanta                                 | 5         | 10.87%  |
| Cheng Uei Precision Industry (Foxlink) | 5         | 10.87%  |
| Silicon Motion                         | 3         | 6.52%   |
| IMC Networks                           | 3         | 6.52%   |
| Sunplus Innovation Technology          | 2         | 4.35%   |
| Realtek Semiconductor                  | 2         | 4.35%   |
| Alcor Micro                            | 2         | 4.35%   |
| OmniVision Technologies                | 1         | 2.17%   |
| Microdia                               | 1         | 2.17%   |
| Logitech                               | 1         | 2.17%   |
| Lite-On Technology                     | 1         | 2.17%   |
| Aveo Technology                        | 1         | 2.17%   |
| Apple                                  | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                               | 5         | 10.87%  |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 4.35%   |
| Quanta HP TrueVision HD Camera                              | 2         | 4.35%   |
| Chicony FJ Camera                                           | 2         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 4.35%   |
| Suyin USB 2.0 Camera                                        | 1         | 2.17%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.17%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.17%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 2.17%   |
| Sunplus HD WebCam                                           | 1         | 2.17%   |
| Silicon Motion WebCam SC-10HDD13335N                        | 1         | 2.17%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 2.17%   |
| Silicon Motion Web Camera                                   | 1         | 2.17%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 2.17%   |
| Realtek USB Camera                                          | 1         | 2.17%   |
| Quanta VGA WebCam                                           | 1         | 2.17%   |
| Quanta HP Truevision HD                                     | 1         | 2.17%   |
| Quanta HD Webcam                                            | 1         | 2.17%   |
| OmniVision OV2640 Webcam                                    | 1         | 2.17%   |
| Microdia Integrated_Webcam_FHD                              | 1         | 2.17%   |
| Logitech HD Webcam C615                                     | 1         | 2.17%   |
| Lite-On Integrated Camera                                   | 1         | 2.17%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.17%   |
| IMC Networks EasyCamera                                     | 1         | 2.17%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 2.17%   |
| Chicony VGA Webcam                                          | 1         | 2.17%   |
| Chicony USB 2.0 Camera                                      | 1         | 2.17%   |
| Chicony Integrated Camera                                   | 1         | 2.17%   |
| Chicony HD WebCam (Asus N-series)                           | 1         | 2.17%   |
| Chicony HD WebCam                                           | 1         | 2.17%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) FJ 5M Camera         | 1         | 2.17%   |
| Aveo USB2.0 Camera                                          | 1         | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 1         | 2.17%   |
| Alcor Micro Asus Integrated Webcam                          | 1         | 2.17%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 4         | 50%     |
| Validity Sensors      | 1         | 12.5%   |
| Synaptics             | 1         | 12.5%   |
| Samsung Electronics   | 1         | 12.5%   |
| LighTuning Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor             | 2         | 25%     |
| Validity Sensors VFS451 Fingerprint Reader       | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Samsung Fingerprint Device                       | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor      | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor                     | 1         | 12.5%   |
| AuthenTec AES1600                                | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| O2 Micro Oz776 SmartCard Reader     | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 68.97%  |
| 1     | 14        | 24.14%  |
| 2     | 4         | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 36.36%  |
| Net/wireless             | 3         | 13.64%  |
| Chipcard                 | 2         | 9.09%   |
| Bluetooth                | 2         | 9.09%   |
| Storage                  | 1         | 4.55%   |
| Sound                    | 1         | 4.55%   |
| Net/ethernet             | 1         | 4.55%   |
| Multimedia controller    | 1         | 4.55%   |
| Graphics card            | 1         | 4.55%   |
| Dvb card                 | 1         | 4.55%   |
| Communication controller | 1         | 4.55%   |

