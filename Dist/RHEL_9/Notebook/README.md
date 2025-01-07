RHEL 9 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

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

Total: 82

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7490               | [5781936456](https://linux-hardware.org/?probe=5781936456) | Dec 31, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [ea8d4bb295](https://linux-hardware.org/?probe=ea8d4bb295) | Nov 24, 2024 |
| HP            | EliteBook 840 G5            | [3d9365dd8e](https://linux-hardware.org/?probe=3d9365dd8e) | Nov 08, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [9f24fcf5f6](https://linux-hardware.org/?probe=9f24fcf5f6) | Nov 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1a592a4c8c](https://linux-hardware.org/?probe=1a592a4c8c) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [88c68a9636](https://linux-hardware.org/?probe=88c68a9636) | Oct 19, 2024 |
| Dell          | Latitude E6520              | [1fccf13e1b](https://linux-hardware.org/?probe=1fccf13e1b) | Oct 14, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8b9768888f](https://linux-hardware.org/?probe=8b9768888f) | Sep 29, 2024 |
| UNOWHY        | Y13G010S4EI                 | [8bc1a2e515](https://linux-hardware.org/?probe=8bc1a2e515) | Sep 25, 2024 |
| Dell          | Precision 7730              | [7f0ef4c558](https://linux-hardware.org/?probe=7f0ef4c558) | Sep 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [325da6b558](https://linux-hardware.org/?probe=325da6b558) | Sep 16, 2024 |
| Dell          | Precision 7530              | [f24cdeec73](https://linux-hardware.org/?probe=f24cdeec73) | Aug 18, 2024 |
| Lenovo        | IdeaPad S145-15API 81UT     | [4d550f9d4c](https://linux-hardware.org/?probe=4d550f9d4c) | Jul 22, 2024 |
| Unknown       | G13                         | [ac710043ec](https://linux-hardware.org/?probe=ac710043ec) | Jul 09, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [07807f87ab](https://linux-hardware.org/?probe=07807f87ab) | Jul 04, 2024 |
| HP            | EliteBook 855 G7 Noteboo... | [70d021b045](https://linux-hardware.org/?probe=70d021b045) | Jul 02, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [cd307f9782](https://linux-hardware.org/?probe=cd307f9782) | Jun 27, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [5f79f30b85](https://linux-hardware.org/?probe=5f79f30b85) | Jun 19, 2024 |
| Dell          | Latitude 5520               | [c1a7e532c9](https://linux-hardware.org/?probe=c1a7e532c9) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [0179e77195](https://linux-hardware.org/?probe=0179e77195) | Jun 10, 2024 |
| Dell          | Latitude 3340               | [3719b02ec1](https://linux-hardware.org/?probe=3719b02ec1) | Jun 10, 2024 |
| HP            | EliteBook 860 16 inch G1... | [a2f0057f55](https://linux-hardware.org/?probe=a2f0057f55) | Jun 05, 2024 |
| HP            | EliteBook 860 16 inch G1... | [75728b162c](https://linux-hardware.org/?probe=75728b162c) | Jun 04, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [564a4d2df9](https://linux-hardware.org/?probe=564a4d2df9) | May 27, 2024 |
| Dell          | Precision 7540              | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| Dell          | Precision 7540              | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
| MSI           | Modern 15 A5M               | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Dell          | Inspiron N5040              | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Dell          | Precision M4800             | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d4e6e0ae3e](https://linux-hardware.org/?probe=d4e6e0ae3e) | Jan 19, 2024 |
| MSI           | Katana GF76 12UC            | [73c3208c03](https://linux-hardware.org/?probe=73c3208c03) | Jan 10, 2024 |
| MSI           | Katana GF76 12UC            | [15db2ea112](https://linux-hardware.org/?probe=15db2ea112) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Precision 3480              | [e81f3e856b](https://linux-hardware.org/?probe=e81f3e856b) | Jan 03, 2024 |
| Dell          | Precision 7530              | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell          | G16 7620                    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP            | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| HP            | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| MSI           | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Dell          | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Dell          | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Dell          | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 6         | 9.09%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 6.06%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 6.06%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 4.55%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 4.55%   |
| 5.14.0-427.42.1.el9_4.x86_64 | 3         | 4.55%   |
| 5.14.0-427.22.1.el9_4.x86_64 | 3         | 4.55%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 4.55%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 4.55%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 4.55%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 4.55%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 3.03%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 3.03%   |
| 5.14.0-427.33.1.el9_4.x86_64 | 2         | 3.03%   |
| 5.14.0-427.20.1.el9_4.x86_64 | 2         | 3.03%   |
| 5.14.0-427.18.1.el9_4.x86_64 | 2         | 3.03%   |
| 5.14.0-427.13.1.el9_4.x86_64 | 2         | 3.03%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 2         | 3.03%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 2         | 3.03%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 3.03%   |
| 6.7.1-1.el9.elrepo.x86_64    | 1         | 1.52%   |
| 6.5.2-1.el9.elrepo.x86_64    | 1         | 1.52%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 1.52%   |
| 5.14.0-503.19.1.el9_5.x86_64 | 1         | 1.52%   |
| 5.14.0-427.40.1.el9_4.x86_64 | 1         | 1.52%   |
| 5.14.0-427.37.1.el9_4.x86_64 | 1         | 1.52%   |
| 5.14.0-427.26.1.el9_4.x86_64 | 1         | 1.52%   |
| 5.14.0-39.el9.x86_64         | 1         | 1.52%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1         | 1.52%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 60        | 96.77%  |
| 6.7.1   | 1         | 1.61%   |
| 6.5.2   | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 60        | 96.77%  |
| 6.7     | 1         | 1.61%   |
| 6.5     | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 58        | 90.63%  |
| KDE5            | 2         | 3.13%   |
| GNOME Classic   | 2         | 3.13%   |
| XFCE            | 1         | 1.56%   |
| GNOME Flashback | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 48        | 77.42%  |
| X11     | 14        | 22.58%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 67.74%  |
| GDM     | 20        | 32.26%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 47        | 75.81%  |
| en_GB | 4         | 6.45%   |
| pt_BR | 2         | 3.23%   |
| cs_CZ | 2         | 3.23%   |
| ro_RO | 1         | 1.61%   |
| ko_KR | 1         | 1.61%   |
| fr_FR | 1         | 1.61%   |
| en_IN | 1         | 1.61%   |
| en_IE | 1         | 1.61%   |
| en_CA | 1         | 1.61%   |
| C     | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 93.55%  |
| BIOS | 4         | 6.45%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 59        | 95.16%  |
| Ext4 | 3         | 4.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 67.74%  |
| GPT     | 20        | 32.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 95.16%  |
| Yes       | 3         | 4.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 90.32%  |
| Yes       | 6         | 9.68%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 30.65%  |
| Dell                | 19        | 30.65%  |
| Hewlett-Packard     | 8         | 12.9%   |
| MSI                 | 5         | 8.06%   |
| ASUSTek Computer    | 4         | 6.45%   |
| UNOWHY              | 1         | 1.61%   |
| System76            | 1         | 1.61%   |
| Samsung Electronics | 1         | 1.61%   |
| Razer               | 1         | 1.61%   |
| LG Electronics      | 1         | 1.61%   |
| Gigabyte Technology | 1         | 1.61%   |
| Unknown             | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| UNOWHY Y13G010S4EI                           | 1         | 1.61%   |
| System76 Galago Pro                          | 1         | 1.61%   |
| Samsung 730QCJ/730QCR                        | 1         | 1.61%   |
| Razer Blade 15 Mid 2019-Base                 | 1         | 1.61%   |
| MSI Modern 15 A5M                            | 1         | 1.61%   |
| MSI Katana GF76 12UC                         | 1         | 1.61%   |
| MSI Katana GF66 12UC                         | 1         | 1.61%   |
| MSI GP75 Leopard 9SD                         | 1         | 1.61%   |
| MSI GE72VR 7RF                               | 1         | 1.61%   |
| LG 15Z95P-GRLGL                              | 1         | 1.61%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US     | 1         | 1.61%   |
| Lenovo ThinkPad X1 Extreme Gen 5 21DFS08200  | 1         | 1.61%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5S08300 | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900  | 1         | 1.61%   |
| Lenovo ThinkPad T490 20N3S77601              | 1         | 1.61%   |
| Lenovo ThinkPad T16 Gen 1 21CH000JUS         | 1         | 1.61%   |
| Lenovo ThinkPad S1 Yoga 12 20DK001YMC        | 1         | 1.61%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS        | 1         | 1.61%   |
| Lenovo ThinkPad L480 20LS0015UK              | 1         | 1.61%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00         | 1         | 1.61%   |
| Lenovo ThinkPad Edge E431 62771L7            | 1         | 1.61%   |
| Lenovo ThinkPad E14 20RA001MMZ               | 1         | 1.61%   |
| Lenovo ThinkBook 14-IIL 20SL                 | 1         | 1.61%   |
| Lenovo ThinkBook 13x G2 IAP 21AT             | 1         | 1.61%   |
| Lenovo ThinkBook 13s-IWL 20R9                | 1         | 1.61%   |
| Lenovo Legion Y540-15IRH-PG0 81SY            | 1         | 1.61%   |
| Lenovo IdeaPad S145-15API 81UT               | 1         | 1.61%   |
| Lenovo IdeaPad 330S-14IKB U 81F4             | 1         | 1.61%   |
| Lenovo IdeaPad 320-15IKB 80XL                | 1         | 1.61%   |
| HP Stream Laptop 11-ak0xxx                   | 1         | 1.61%   |
| HP ProBook 640 G2                            | 1         | 1.61%   |
| HP Laptop 14s-dk0xxx                         | 1         | 1.61%   |
| HP EliteBook 860 16 inch G10 Notebook PC     | 1         | 1.61%   |
| HP EliteBook 855 G7 Notebook PC              | 1         | 1.61%   |
| HP EliteBook 840 G5                          | 1         | 1.61%   |
| HP EliteBook 2570p                           | 1         | 1.61%   |
| HP 340S G7                                   | 1         | 1.61%   |
| Gigabyte AERO 15 KD                          | 1         | 1.61%   |
| Dell XPS 17 9710                             | 1         | 1.61%   |
| Dell Precision M4800                         | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 19.35%  |
| Dell Precision     | 8         | 12.9%   |
| Dell Latitude      | 6         | 9.68%   |
| HP EliteBook       | 4         | 6.45%   |
| Lenovo ThinkBook   | 3         | 4.84%   |
| Lenovo IdeaPad     | 3         | 4.84%   |
| Dell Inspiron      | 3         | 4.84%   |
| MSI Katana         | 2         | 3.23%   |
| UNOWHY Y13G010S4EI | 1         | 1.61%   |
| System76 Galago    | 1         | 1.61%   |
| Samsung 730QCJ     | 1         | 1.61%   |
| Razer Blade        | 1         | 1.61%   |
| MSI Modern         | 1         | 1.61%   |
| MSI GP75           | 1         | 1.61%   |
| MSI GE72VR         | 1         | 1.61%   |
| LG 15Z95P-GRLGL    | 1         | 1.61%   |
| Lenovo Legion      | 1         | 1.61%   |
| HP Stream          | 1         | 1.61%   |
| HP ProBook         | 1         | 1.61%   |
| HP Laptop          | 1         | 1.61%   |
| HP 340S            | 1         | 1.61%   |
| Gigabyte AERO      | 1         | 1.61%   |
| Dell XPS           | 1         | 1.61%   |
| Dell G16           | 1         | 1.61%   |
| ASUS Z450LA        | 1         | 1.61%   |
| ASUS VivoBook      | 1         | 1.61%   |
| ASUS TUF           | 1         | 1.61%   |
| ASUS ASUS          | 1         | 1.61%   |
| Unknown            | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 13        | 20.97%  |
| 2021 | 10        | 16.13%  |
| 2020 | 7         | 11.29%  |
| 2022 | 6         | 9.68%   |
| 2023 | 5         | 8.06%   |
| 2018 | 4         | 6.45%   |
| 2017 | 3         | 4.84%   |
| 2015 | 3         | 4.84%   |
| 2014 | 3         | 4.84%   |
| 2011 | 3         | 4.84%   |
| 2013 | 2         | 3.23%   |
| 2016 | 1         | 1.61%   |
| 2012 | 1         | 1.61%   |
| 2010 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 62        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 48        | 76.19%  |
| Enabled  | 15        | 23.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 98.39%  |
| Yes  | 1         | 1.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 23        | 37.1%   |
| 4.01-8.0    | 15        | 24.19%  |
| 32.01-64.0  | 9         | 14.52%  |
| 3.01-4.0    | 6         | 9.68%   |
| 64.01-256.0 | 5         | 8.06%   |
| 24.01-32.0  | 2         | 3.23%   |
| 16.01-24.0  | 2         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 36.92%  |
| 2.01-3.0   | 20        | 30.77%  |
| 3.01-4.0   | 12        | 18.46%  |
| 8.01-16.0  | 6         | 9.23%   |
| 1.01-2.0   | 2         | 3.08%   |
| 32.01-64.0 | 1         | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 60.94%  |
| 2      | 18        | 28.13%  |
| 3      | 6         | 9.38%   |
| 4      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 85.48%  |
| Yes       | 9         | 14.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 77.42%  |
| No        | 14        | 22.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 98.39%  |
| No        | 1         | 1.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 81.25%  |
| No        | 12        | 18.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 27.42%  |
| India       | 5         | 8.06%   |
| Canada      | 3         | 4.84%   |
| Brazil      | 3         | 4.84%   |
| UK          | 2         | 3.23%   |
| Turkey      | 2         | 3.23%   |
| Spain       | 2         | 3.23%   |
| South Korea | 2         | 3.23%   |
| Romania     | 2         | 3.23%   |
| Italy       | 2         | 3.23%   |
| Guatemala   | 2         | 3.23%   |
| Czechia     | 2         | 3.23%   |
| Chile       | 2         | 3.23%   |
| Vietnam     | 1         | 1.61%   |
| Switzerland | 1         | 1.61%   |
| Sri Lanka   | 1         | 1.61%   |
| Slovakia    | 1         | 1.61%   |
| Russia      | 1         | 1.61%   |
| Norway      | 1         | 1.61%   |
| Netherlands | 1         | 1.61%   |
| Mexico      | 1         | 1.61%   |
| Kenya       | 1         | 1.61%   |
| Jordan      | 1         | 1.61%   |
| Ireland     | 1         | 1.61%   |
| Indonesia   | 1         | 1.61%   |
| France      | 1         | 1.61%   |
| Finland     | 1         | 1.61%   |
| Egypt       | 1         | 1.61%   |
| Austria     | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Santiago            | 2         | 3.13%   |
| Jaipur              | 2         | 3.13%   |
| Guatemala City      | 2         | 3.13%   |
| Zlín               | 1         | 1.56%   |
| Whiteley            | 1         | 1.56%   |
| Vancouver           | 1         | 1.56%   |
| Valbrembo           | 1         | 1.56%   |
| Urbandale           | 1         | 1.56%   |
| Stratham            | 1         | 1.56%   |
| Spring Hill         | 1         | 1.56%   |
| Skien               | 1         | 1.56%   |
| Seoul               | 1         | 1.56%   |
| Sao Paulo           | 1         | 1.56%   |
| Saint Paul          | 1         | 1.56%   |
| Râmnicu Vâlcea    | 1         | 1.56%   |
| Providence          | 1         | 1.56%   |
| Prairieville        | 1         | 1.56%   |
| Piracicaba          | 1         | 1.56%   |
| Parker              | 1         | 1.56%   |
| Nuenen              | 1         | 1.56%   |
| Newcastle upon Tyne | 1         | 1.56%   |
| New Delhi           | 1         | 1.56%   |
| Nairobi             | 1         | 1.56%   |
| Mountlake Terrace   | 1         | 1.56%   |
| Morlaix             | 1         | 1.56%   |
| Montgomery          | 1         | 1.56%   |
| Milano              | 1         | 1.56%   |
| Maltepe             | 1         | 1.56%   |
| Madrid              | 1         | 1.56%   |
| Liberec             | 1         | 1.56%   |
| Kolkata             | 1         | 1.56%   |
| Klosterneuburg      | 1         | 1.56%   |
| Kemerovo            | 1         | 1.56%   |
| Jeonju              | 1         | 1.56%   |
| Houston             | 1         | 1.56%   |
| Hope                | 1         | 1.56%   |
| Ho Chi Minh City    | 1         | 1.56%   |
| Helsinki            | 1         | 1.56%   |
| Freehold            | 1         | 1.56%   |
| Fort Collins        | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 21        | 25     | 23.08%  |
| Sandisk                     | 9         | 11     | 9.89%   |
| Unknown                     | 7         | 7      | 7.69%   |
| Toshiba                     | 7         | 8      | 7.69%   |
| Seagate                     | 6         | 7      | 6.59%   |
| KIOXIA                      | 6         | 7      | 6.59%   |
| Micron Technology           | 4         | 4      | 4.4%    |
| WDC                         | 3         | 3      | 3.3%    |
| SK hynix                    | 3         | 3      | 3.3%    |
| Kingston                    | 3         | 3      | 3.3%    |
| Micron/Crucial Technology   | 2         | 3      | 2.2%    |
| Intel                       | 2         | 3      | 2.2%    |
| Unknown                     | 2         | 2      | 2.2%    |
| WDC WDS                     | 1         | 1      | 1.1%    |
| Union Memory                | 1         | 1      | 1.1%    |
| SSSTC                       | 1         | 1      | 1.1%    |
| SABRENT                     | 1         | 1      | 1.1%    |
| Realtek                     | 1         | 1      | 1.1%    |
| PNY                         | 1         | 1      | 1.1%    |
| Plextor                     | 1         | 1      | 1.1%    |
| Phison                      | 1         | 1      | 1.1%    |
| Kingston Technology Company | 1         | 1      | 1.1%    |
| KingSpec                    | 1         | 1      | 1.1%    |
| Kingmax                     | 1         | 1      | 1.1%    |
| HGST                        | 1         | 1      | 1.1%    |
| Golden                      | 1         | 1      | 1.1%    |
| DERLAR                      | 1         | 1      | 1.1%    |
| China                       | 1         | 1      | 1.1%    |
| A-DATA Technology           | 1         | 1      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 6         | 6.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 5.32%   |
| Unknown MMC Card  64GB                               | 3         | 3.19%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 3         | 3.19%   |
| Unknown MMC Card  256GB                              | 2         | 2.13%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 2.13%   |
| Seagate ST1000LM049-2GH172 1TB                       | 2         | 2.13%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 2         | 2.13%   |
| Micron 2400_MTFDKBA512QFM 512GB                      | 2         | 2.13%   |
| KIOXIA KBG5AZNT1T02 LA 1024GB                        | 2         | 2.13%   |
| Unknown                                              | 2         | 2.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 1.06%   |
| WDC WDS 250G2B0A-00SM50 250GB SSD                    | 1         | 1.06%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 1         | 1.06%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 1.06%   |
| Unknown MMC Card  512GB                              | 1         | 1.06%   |
| Unknown MMC Card  483MB                              | 1         | 1.06%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB              | 1         | 1.06%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 1         | 1.06%   |
| Toshiba MQ01ACF050 500GB                             | 1         | 1.06%   |
| Toshiba MQ01ACF032 320GB                             | 1         | 1.06%   |
| Toshiba MQ01ABF032 320GB                             | 1         | 1.06%   |
| Toshiba MQ01ABD100 1TB                               | 1         | 1.06%   |
| Toshiba KXG50ZNV512G NVMe 512GB                      | 1         | 1.06%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                       | 1         | 1.06%   |
| SK hynix SHGP31-1000GM 1TB                           | 1         | 1.06%   |
| SK hynix NVMe SSD Drive 1024GB                       | 1         | 1.06%   |
| SK hynix HFM256GD3JX013N 256GB                       | 1         | 1.06%   |
| Seagate ST500LT012-9WS142 500GB                      | 1         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1         | 1.06%   |
| Seagate BUP Slim BK 2TB                              | 1         | 1.06%   |
| Seagate Backup+ Hub BK 4TB                           | 1         | 1.06%   |
| Sandisk WD Blue SN570 500GB                          | 1         | 1.06%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 1         | 1.06%   |
| Sandisk WD Black SN850 2TB                           | 1         | 1.06%   |
| Sandisk PC SN520 NVMe SSD 256GB                      | 1         | 1.06%   |
| SanDisk NVMe SSD Drive 1TB                           | 1         | 1.06%   |
| Samsung SSD PM851 2.5 7mm 256GB                      | 1         | 1.06%   |
| Samsung SSD PM830 2.5 7mm 128GB                      | 1         | 1.06%   |
| Samsung SSD 980 1TB                                  | 1         | 1.06%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 40%     |
| Seagate | 6         | 7      | 40%     |
| WDC     | 1         | 1      | 6.67%   |
| SABRENT | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 35.29%  |
| WDC                 | 2         | 2      | 11.76%  |
| WDC WDS             | 1         | 1      | 5.88%   |
| PNY                 | 1         | 1      | 5.88%   |
| Plextor             | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| KingSpec            | 1         | 1      | 5.88%   |
| Kingmax             | 1         | 1      | 5.88%   |
| Intel               | 1         | 2      | 5.88%   |
| DERLAR              | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 46        | 58     | 54.76%  |
| SSD     | 15        | 18     | 17.86%  |
| HDD     | 15        | 16     | 17.86%  |
| MMC     | 7         | 9      | 8.33%   |
| Unknown | 1         | 1      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 45        | 57     | 54.88%  |
| SATA | 24        | 29     | 29.27%  |
| MMC  | 7         | 9      | 8.54%   |
| SAS  | 6         | 7      | 7.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 16     | 46.67%  |
| 0.51-1.0   | 13        | 14     | 43.33%  |
| 1.01-2.0   | 2         | 2      | 6.67%   |
| 3.01-4.0   | 1         | 2      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 29.69%  |
| 501-1000       | 15        | 23.44%  |
| 251-500        | 11        | 17.19%  |
| 1001-2000      | 8         | 12.5%   |
| 51-100         | 4         | 6.25%   |
| 21-50          | 3         | 4.69%   |
| 2001-3000      | 2         | 3.13%   |
| More than 3000 | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 21        | 32.31%  |
| 21-50     | 18        | 27.69%  |
| 51-100    | 9         | 13.85%  |
| 251-500   | 7         | 10.77%  |
| 101-250   | 6         | 9.23%   |
| 1001-2000 | 3         | 4.62%   |
| Unknown   | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 25%     |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 25%     |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 2         | 2      | 50%     |
| Micron/Crucial Technology | 1         | 1      | 25%     |
| Intel                     | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 2      | 25%     |

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
| Detected | 46        | 74     | 69.7%   |
| Works    | 16        | 23     | 24.24%  |
| Malfunc  | 4         | 5      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 37        | 44.05%  |
| Samsung Electronics          | 15        | 17.86%  |
| SanDisk                      | 9         | 10.71%  |
| KIOXIA                       | 6         | 7.14%   |
| Micron Technology            | 4         | 4.76%   |
| SK hynix                     | 3         | 3.57%   |
| Kingston Technology Company  | 3         | 3.57%   |
| Micron/Crucial Technology    | 2         | 2.38%   |
| Union Memory (Shenzhen)      | 1         | 1.19%   |
| Toshiba America Info Systems | 1         | 1.19%   |
| Phison Electronics           | 1         | 1.19%   |
| AMD                          | 1         | 1.19%   |
| ADATA Technology             | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 6         | 6.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 6         | 6.82%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 5         | 5.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 5         | 5.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 4         | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 4.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 3         | 3.41%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 3         | 3.41%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 3         | 3.41%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 3.41%   |
| Intel Comet Lake SATA AHCI Controller                                         | 3         | 3.41%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 2.27%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 2         | 2.27%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 2         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 2.27%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 2         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 2.27%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                         | 1         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 1.14%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 1.14%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 1         | 1.14%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 1         | 1.14%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                         | 1         | 1.14%   |
| Phison E12 NVMe Controller                                                    | 1         | 1.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 1.14%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                     | 1         | 1.14%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 1.14%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 1         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 1         | 1.14%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 1         | 1.14%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                              | 1         | 1.14%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                          | 1         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.14%   |
| Intel SSD 660P Series                                                         | 1         | 1.14%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 1.14%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 44        | 53.01%  |
| SATA | 31        | 37.35%  |
| RAID | 8         | 9.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 91.94%  |
| AMD    | 5         | 8.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 4.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 4.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 4.84%   |
| Intel 12th Gen Core i7-12700H           | 3         | 4.84%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 3.23%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 3.23%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 2         | 3.23%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 2         | 3.23%   |
| Intel Xeon W-11855M CPU @ 3.20GHz       | 1         | 1.61%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.61%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.61%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 1.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.61%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 1.61%   |
| Intel Celeron N5095A @ 2.00GHz          | 1         | 1.61%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 1         | 1.61%   |
| Intel Celeron N4100 CPU @ 1.10GHz       | 1         | 1.61%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 1         | 1.61%   |
| Intel 13th Gen Core i7-1360P            | 1         | 1.61%   |
| Intel 13th Gen Core i7-1355U            | 1         | 1.61%   |
| Intel 13th Gen Core i5-1335U            | 1         | 1.61%   |
| Intel 12th Gen Core i9-12900K           | 1         | 1.61%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.61%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.61%   |
| Intel 12th Gen Core i5-12450H           | 1         | 1.61%   |
| Intel 12th Gen Core i5-1235U            | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Other           | 18        | 29.03%  |
| Intel Core i5   | 18        | 29.03%  |
| Intel Core i7   | 12        | 19.35%  |
| Intel Celeron   | 4         | 6.45%   |
| Intel Core i3   | 3         | 4.84%   |
| AMD Ryzen 7 PRO | 2         | 3.23%   |
| AMD Ryzen 5     | 2         | 3.23%   |
| Intel Xeon      | 1         | 1.61%   |
| Intel Core i9   | 1         | 1.61%   |
| AMD Ryzen 3     | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 24        | 38.71%  |
| 2      | 14        | 22.58%  |
| 8      | 8         | 12.9%   |
| 6      | 7         | 11.29%  |
| 10     | 4         | 6.45%   |
| 14     | 3         | 4.84%   |
| 12     | 2         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 90.32%  |
| 1      | 6         | 9.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 39.68%  |
| 0x806ec    | 6         | 9.52%   |
| 0x806d1    | 4         | 6.35%   |
| 0x906a3    | 3         | 4.76%   |
| 0x706e5    | 2         | 3.17%   |
| 0x506e3    | 2         | 3.17%   |
| 0x406e3    | 2         | 3.17%   |
| 0x306a9    | 2         | 3.17%   |
| 0x906ed    | 1         | 1.59%   |
| 0x906ea    | 1         | 1.59%   |
| 0x906e9    | 1         | 1.59%   |
| 0x906a4    | 1         | 1.59%   |
| 0x90672    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x706a8    | 1         | 1.59%   |
| 0x706a1    | 1         | 1.59%   |
| 0x40651    | 1         | 1.59%   |
| 0x306d4    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x0a404102 | 1         | 1.59%   |
| 0x08608103 | 1         | 1.59%   |
| 0x08600106 | 1         | 1.59%   |
| 0x08108109 | 1         | 1.59%   |
| 0x08108102 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 29.03%  |
| Alderlake Hybrid | 11        | 17.74%  |
| Icelake          | 7         | 11.29%  |
| Skylake          | 4         | 6.45%   |
| TigerLake        | 3         | 4.84%   |
| Haswell          | 3         | 4.84%   |
| Goldmont plus    | 3         | 4.84%   |
| Zen+             | 2         | 3.23%   |
| Westmere         | 2         | 3.23%   |
| IvyBridge        | 2         | 3.23%   |
| Broadwell        | 2         | 3.23%   |
| Unknown          | 2         | 3.23%   |
| Zen 2            | 1         | 1.61%   |
| Tremont          | 1         | 1.61%   |
| SandyBridge      | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 66.67%  |
| Nvidia | 17        | 22.67%  |
| AMD    | 8         | 10.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 4         | 5.33%   |
| Intel UHD Graphics 620                                                        | 4         | 5.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 5.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 5.33%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 4         | 5.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 4%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 3         | 4%      |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 3         | 4%      |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 4%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 2.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 2.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 2.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 2.67%   |
| Intel HD Graphics 5500                                                        | 2         | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.67%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 2         | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.33%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 1.33%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.33%   |
| Nvidia GP104GLM [Quadro P3200 Mobile]                                         | 1         | 1.33%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                         | 1         | 1.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                               | 1         | 1.33%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 1.33%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 1.33%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 1.33%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.33%   |
| Intel HD Graphics 630                                                         | 1         | 1.33%   |
| Intel HD Graphics 620                                                         | 1         | 1.33%   |
| Intel HD Graphics 530                                                         | 1         | 1.33%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                         | 1         | 1.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.33%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 1.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.33%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 1         | 1.33%   |
| AMD Rembrandt [Radeon 680M]                                                   | 1         | 1.33%   |
| AMD Lucienne                                                                  | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 59.68%  |
| Intel + Nvidia | 10        | 16.13%  |
| 1 x Nvidia     | 7         | 11.29%  |
| 1 x AMD        | 5         | 8.06%   |
| Intel + AMD    | 3         | 4.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 87.1%   |
| Proprietary | 7         | 11.29%  |
| Unknown     | 1         | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 67.74%  |
| 5.01-6.0   | 6         | 9.68%   |
| 1.01-2.0   | 6         | 9.68%   |
| 3.01-4.0   | 2         | 3.23%   |
| 0.01-0.5   | 2         | 3.23%   |
| 2.01-3.0   | 1         | 1.61%   |
| 16.01-24.0 | 1         | 1.61%   |
| 8.01-16.0  | 1         | 1.61%   |
| 0.51-1.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 15        | 18.52%  |
| AU Optronics         | 12        | 14.81%  |
| LG Display           | 11        | 13.58%  |
| Chimei Innolux       | 8         | 9.88%   |
| CSO                  | 5         | 6.17%   |
| Samsung Electronics  | 4         | 4.94%   |
| Dell                 | 4         | 4.94%   |
| Hewlett-Packard      | 3         | 3.7%    |
| Goldstar             | 3         | 3.7%    |
| Vizio                | 2         | 2.47%   |
| Sharp                | 2         | 2.47%   |
| Lenovo               | 2         | 2.47%   |
| Unknown (XXX)        | 1         | 1.23%   |
| Philips              | 1         | 1.23%   |
| PANDA                | 1         | 1.23%   |
| InfoVision           | 1         | 1.23%   |
| Gigabyte Technology  | 1         | 1.23%   |
| CEX                  | 1         | 1.23%   |
| BOE Technology Group | 1         | 1.23%   |
| ASUSTek Computer     | 1         | 1.23%   |
| AOC                  | 1         | 1.23%   |
| Acer                 | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                   | 2         | 2.38%   |
| Unknown (XXX) Beyond TV XXX9221 1920x1080 1209x680mm 54.6-inch        | 1         | 1.19%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 1.19%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 1.19%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 1.19%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1         | 1.19%   |
| Philips PHL 272B7QPJ PHL0900 2560x1440 600x340mm 27.2-inch            | 1         | 1.19%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 1.19%   |
| LG Display LCD Monitor LGD0753 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD06CF 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0645 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 1.19%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1         | 1.19%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1         | 1.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch          | 1         | 1.19%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 1.19%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch           | 1         | 1.19%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 1         | 1.19%   |
| Goldstar UltraFine GSM5B11 4096x2304 600x340mm 27.2-inch              | 1         | 1.19%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 1         | 1.19%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 1.19%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 1         | 1.19%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                    | 1         | 1.19%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1         | 1.19%   |
| Dell E2218HN DELF09E 1920x1080 476x268mm 21.5-inch                    | 1         | 1.19%   |
| CSO SNF601BS1-1 CSO150D 1920x1080 344x193mm 15.5-inch                 | 1         | 1.19%   |
| CSO LCD Monitor CSO160D 1920x1200 344x215mm 16.0-inch                 | 1         | 1.19%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 51.39%  |
| 1366x768 (WXGA)   | 12        | 16.67%  |
| 3840x2160 (4K)    | 5         | 6.94%   |
| 1920x1200 (WUXGA) | 5         | 6.94%   |
| 2560x1440 (QHD)   | 4         | 5.56%   |
| 2560x1600         | 3         | 4.17%   |
| Unknown           | 2         | 2.78%   |
| 6400x2160         | 1         | 1.39%   |
| 5120x1440         | 1         | 1.39%   |
| 3840x2400         | 1         | 1.39%   |
| 2160x1350         | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 19        | 24.05%  |
| 13      | 18        | 22.78%  |
| 14      | 8         | 10.13%  |
| 27      | 5         | 6.33%   |
| 24      | 5         | 6.33%   |
| 16      | 5         | 6.33%   |
| 17      | 4         | 5.06%   |
| 54      | 3         | 3.8%    |
| 23      | 3         | 3.8%    |
| 31      | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 72      | 1         | 1.27%   |
| 21      | 1         | 1.27%   |
| 18      | 1         | 1.27%   |
| 12      | 1         | 1.27%   |
| 11      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 55.13%  |
| 501-600     | 12        | 15.38%  |
| 201-300     | 9         | 11.54%  |
| 351-400     | 4         | 5.13%   |
| 1001-1500   | 3         | 3.85%   |
| 601-700     | 2         | 2.56%   |
| 401-500     | 2         | 2.56%   |
| Unknown     | 2         | 2.56%   |
| 1501-2000   | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 51        | 79.69%  |
| 16/10   | 11        | 17.19%  |
| Unknown | 2         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 23.75%  |
| 101-110        | 19        | 23.75%  |
| 201-250        | 8         | 10%     |
| 71-80          | 7         | 8.75%   |
| 301-350        | 5         | 6.25%   |
| 111-120        | 5         | 6.25%   |
| More than 1000 | 4         | 5%      |
| 121-130        | 4         | 5%      |
| 351-500        | 2         | 2.5%    |
| 251-300        | 2         | 2.5%    |
| Unknown        | 2         | 2.5%    |
| 61-70          | 1         | 1.25%   |
| 51-60          | 1         | 1.25%   |
| 141-150        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 42.11%  |
| 101-120       | 15        | 19.74%  |
| 161-240       | 10        | 13.16%  |
| 51-100        | 10        | 13.16%  |
| More than 240 | 4         | 5.26%   |
| 1-50          | 3         | 3.95%   |
| Unknown       | 2         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 69.84%  |
| 2     | 12        | 19.05%  |
| 3     | 4         | 6.35%   |
| 5     | 1         | 1.59%   |
| 4     | 1         | 1.59%   |
| 0     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 51.58%  |
| Realtek Semiconductor | 29        | 30.53%  |
| Qualcomm Atheros      | 8         | 8.42%   |
| DisplayLink           | 2         | 2.11%   |
| Broadcom              | 2         | 2.11%   |
| Ralink Technology     | 1         | 1.05%   |
| Qualcomm              | 1         | 1.05%   |
| OPPO Electronics      | 1         | 1.05%   |
| MediaTek              | 1         | 1.05%   |
| Broadcom Limited      | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 10.08%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 8.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 3.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 3.36%   |
| Intel Wireless 8265 / 8275                                             | 4         | 3.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 3.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 2.52%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 2.52%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 2.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.68%   |
| Intel Wireless 8260                                                    | 2         | 1.68%   |
| Intel Wireless 7265                                                    | 2         | 1.68%   |
| Intel Wireless 7260                                                    | 2         | 1.68%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.68%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.84%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.84%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.84%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.84%   |
| Intel Wireless 3165                                                    | 1         | 0.84%   |
| Intel Wireless 3160                                                    | 1         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 0.84%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 72.58%  |
| Qualcomm Atheros      | 6         | 9.68%   |
| Realtek Semiconductor | 5         | 8.06%   |
| Broadcom              | 2         | 3.23%   |
| Ralink Technology     | 1         | 1.61%   |
| Qualcomm              | 1         | 1.61%   |
| MediaTek              | 1         | 1.61%   |
| Broadcom Limited      | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                            | 6         | 9.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 4         | 6.45%   |
| Intel Wireless 8265 / 8275                                  | 4         | 6.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 4         | 6.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 3         | 4.84%   |
| Intel Wi-Fi 6 AX201                                         | 3         | 4.84%   |
| Intel Raptor Lake PCH CNVi WiFi                             | 3         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 2         | 3.23%   |
| Intel Wireless 8260                                         | 2         | 3.23%   |
| Intel Wireless 7265                                         | 2         | 3.23%   |
| Intel Wireless 7260                                         | 2         | 3.23%   |
| Intel Wi-Fi 6 AX200                                         | 2         | 3.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]     | 2         | 3.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                             | 2         | 3.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                    | 2         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 2         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                             | 1         | 1.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                  | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 1         | 1.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                     | 1         | 1.61%   |
| Intel Wireless 3165                                         | 1         | 1.61%   |
| Intel Wireless 3160                                         | 1         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                              | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                            | 1         | 1.61%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                             | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 50.91%  |
| Intel                 | 22        | 40%     |
| Qualcomm Atheros      | 2         | 3.64%   |
| DisplayLink           | 2         | 3.64%   |
| OPPO Electronics      | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12        | 21.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 17.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 7.02%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 5.26%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.75%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.75%   |
| OPPO OnePlus Nord 4                                                    | 1         | 1.75%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.75%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.75%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.75%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.75%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.75%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.75%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 1.75%   |
| DisplayLink USB 4K Graphic Docking                                     | 1         | 1.75%   |
| DisplayLink Dell D3100 Docking Station                                 | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 55.45%  |
| Ethernet | 49        | 44.55%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 71.64%  |
| Ethernet | 19        | 28.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 67.74%  |
| 1     | 20        | 32.26%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 70.97%  |
| Yes  | 18        | 29.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 69.81%  |
| Qualcomm Atheros Communications | 5         | 9.43%   |
| Realtek Semiconductor           | 4         | 7.55%   |
| Broadcom                        | 3         | 5.66%   |
| USI                             | 1         | 1.89%   |
| MediaTek                        | 1         | 1.89%   |
| IMC Networks                    | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 11        | 20.75%  |
| Intel Bluetooth wireless interface             | 8         | 15.09%  |
| Intel AX211 Bluetooth                          | 6         | 11.32%  |
| Qualcomm Atheros  Bluetooth Device             | 5         | 9.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 9.43%   |
| Realtek Bluetooth Radio                        | 3         | 5.66%   |
| Intel AX210 Bluetooth                          | 3         | 5.66%   |
| Intel AX200 Bluetooth                          | 2         | 3.77%   |
| USI Bluetooth Device                           | 1         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.89%   |
| MediaTek Wireless_Device                       | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.89%   |
| IMC Networks Bluetooth Radio                   | 1         | 1.89%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.89%   |
| ASUS ASUS USB-BT500                            | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 59.38%  |
| Nvidia                   | 15        | 15.63%  |
| AMD                      | 7         | 7.29%   |
| Realtek Semiconductor    | 5         | 5.21%   |
| Texas Instruments        | 3         | 3.13%   |
| SteelSeries ApS          | 1         | 1.04%   |
| Sony                     | 1         | 1.04%   |
| Plantronics              | 1         | 1.04%   |
| Nordic Semiconductor ASA | 1         | 1.04%   |
| LG Electronics           | 1         | 1.04%   |
| Lenovo                   | 1         | 1.04%   |
| Hewlett-Packard          | 1         | 1.04%   |
| Corsair                  | 1         | 1.04%   |
| BEHRINGER International  | 1         | 1.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                              | 7         | 6.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                      | 7         | 6.67%   |
| Intel Cannon Lake PCH cAVS                                                   | 6         | 5.71%   |
| Realtek Semiconductor USB Audio                                              | 5         | 4.76%   |
| Intel Tiger Lake-H HD Audio Controller                                       | 5         | 4.76%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                   | 5         | 4.76%   |
| Nvidia GA106 High Definition Audio Controller                                | 4         | 3.81%   |
| Intel Comet Lake PCH-LP cAVS                                                 | 4         | 3.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.86%   |
| Intel Raptor Lake-P/U/H cAVS                                                 | 3         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                 | 3         | 2.86%   |
| Texas Instruments PCM2902 Audio Codec                                        | 2         | 1.9%    |
| Nvidia TU116 High Definition Audio Controller                                | 2         | 1.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller               | 2         | 1.9%    |
| Nvidia GP104 High Definition Audio Controller                                | 2         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                      | 2         | 1.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                    | 2         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                        | 2         | 1.9%    |
| Intel CM238 HD Audio Controller                                              | 2         | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                       | 2         | 1.9%    |
| Intel Broadwell-U Audio Controller                                           | 2         | 1.9%    |
| Intel 8 Series HD Audio Controller                                           | 2         | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller          | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                     | 2         | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                           | 2         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                          | 2         | 1.9%    |
| Texas Instruments PCM2704 16-bit stereo audio DAC                            | 1         | 0.95%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                | 1         | 0.95%   |
| Sony DualSense wireless controller (PS5)                                     | 1         | 0.95%   |
| Plantronics Blackwire C5220 headset (remote control and 3.5mm audio adapter) | 1         | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                                | 1         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                           | 1         | 0.95%   |
| Nvidia GA107 High Definition Audio Controller                                | 1         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                                | 1         | 0.95%   |
| Nvidia GA102 High Definition Audio Controller                                | 1         | 0.95%   |
| Nordic Semiconductor ASA USB Composite Device                                | 1         | 0.95%   |
| LG Electronics USB Audio                                                     | 1         | 0.95%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                                 | 1         | 0.95%   |
| Intel Jasper Lake HD Audio                                                   | 1         | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                       | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 28.57%  |
| SK hynix            | 5         | 23.81%  |
| Kingston            | 4         | 19.05%  |
| Crucial             | 2         | 9.52%   |
| Team                | 1         | 4.76%   |
| Smart               | 1         | 4.76%   |
| Micron Technology   | 1         | 4.76%   |
| Elpida              | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 4.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 4.55%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 4.55%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 4.55%   |
| SK hynix RAM H5AN8G6NDJR-XNC 4GB Row Of Chips DDR4 2400MT/s  | 1         | 4.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 4.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 4.55%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 4.55%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| Kingston RAM X74R9W-MIE 8GB SODIMM DDR4 2933MT/s             | 1         | 4.55%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 1         | 4.55%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 4.55%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| Crucial RAM CT4G4SFS824A.M8FE 4GB SODIMM DDR4 2400MT/s       | 1         | 4.55%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 72.22%  |
| DDR3   | 3         | 16.67%  |
| LPDDR5 | 2         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 83.33%  |
| Row Of Chips | 3         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 35%     |
| 16384 | 5         | 25%     |
| 4096  | 5         | 25%     |
| 32768 | 2         | 10%     |
| 2048  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 23.81%  |
| 3200  | 4         | 19.05%  |
| 2400  | 4         | 19.05%  |
| 1600  | 3         | 14.29%  |
| 6400  | 2         | 9.52%   |
| 2133  | 2         | 9.52%   |
| 2933  | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 100%    |

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
| Chicony Electronics                    | 14        | 22.58%  |
| Sunplus Innovation Technology          | 8         | 12.9%   |
| Microdia                               | 7         | 11.29%  |
| IMC Networks                           | 6         | 9.68%   |
| Bison Electronics                      | 6         | 9.68%   |
| Realtek Semiconductor                  | 3         | 4.84%   |
| Lite-On Technology                     | 3         | 4.84%   |
| Luxvisions Innotech Limited            | 2         | 3.23%   |
| Syntek                                 | 1         | 1.61%   |
| Suyin                                  | 1         | 1.61%   |
| Sonix Technology                       | 1         | 1.61%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.61%   |
| Samsung Electronics                    | 1         | 1.61%   |
| Remo Tech                              | 1         | 1.61%   |
| Quanta                                 | 1         | 1.61%   |
| Microsoft                              | 1         | 1.61%   |
| LG Electronics                         | 1         | 1.61%   |
| icSpring                               | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.61%   |
| Alcor Micro                            | 1         | 1.61%   |
| Acer                                   | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                      | 5         | 8.06%   |
| Chicony Integrated Camera                         | 4         | 6.45%   |
| Microdia Integrated_Webcam_HD                     | 3         | 4.84%   |
| IMC Networks Integrated Camera                    | 3         | 4.84%   |
| Realtek Integrated_Webcam_HD                      | 2         | 3.23%   |
| Lite-On Integrated Camera                         | 2         | 3.23%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 2         | 3.23%   |
| Chicony HP HD Camera                              | 2         | 3.23%   |
| Bison Integrated Camera                           | 2         | 3.23%   |
| Bison HD Webcam                                   | 2         | 3.23%   |
| Syntek Integrated Camera                          | 1         | 1.61%   |
| Suyin Integrated_Webcam_HD                        | 1         | 1.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 1.61%   |
| Sunplus Integrated Camera                         | 1         | 1.61%   |
| Sunplus DICOTA 4K                                 | 1         | 1.61%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 1.61%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 1.61%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1.61%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 1.61%   |
| Realtek Integrated Webcam_HD                      | 1         | 1.61%   |
| Quanta HP TrueVision HD Camera                    | 1         | 1.61%   |
| Microsoft LifeCam VX-2000                         | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_0.3M            | 1         | 1.61%   |
| Microdia Integrated_Webcam_FHD                    | 1         | 1.61%   |
| Microdia Integrated Webcam                        | 1         | 1.61%   |
| Microdia 1.3 MPixel Integrated Webcam             | 1         | 1.61%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.61%   |
| Luxvisions Innotech Limited Integrated Camera     | 1         | 1.61%   |
| Lite-On HP HD Camera                              | 1         | 1.61%   |
| LG LG UltraFine Display Camera                    | 1         | 1.61%   |
| IMC Networks USB Camera                           | 1         | 1.61%   |
| icSpring camera                                   | 1         | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                     | 1         | 1.61%   |
| Chicony ThinkPad T490 Webcam                      | 1         | 1.61%   |
| Chicony LG Camera                                 | 1         | 1.61%   |
| Chicony Integrated RGB Camera                     | 1         | 1.61%   |
| Chicony HP TrueVision HD Camera                   | 1         | 1.61%   |
| Chicony HP HD Webcam [Fixed]                      | 1         | 1.61%   |
| Chicony HP 5MP Camera                             | 1         | 1.61%   |
| Chicony HD Webcam                                 | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 61.54%  |
| Validity Sensors           | 2         | 15.38%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |
| Samsung Electronics        | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI Device                                 | 3         | 23.08%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 23.08%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 7.69%   |
| Validity Sensors VFS491                                   | 1         | 7.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics Prometheus Fingerprint Reader                   | 1         | 7.69%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 91.67%  |
| Alcor Micro | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 41.67%  |
| Broadcom 58200                                                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 37        | 59.68%  |
| 1     | 21        | 33.87%  |
| 2     | 2         | 3.23%   |
| 5     | 1         | 1.61%   |
| 3     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 38.24%  |
| Chipcard              | 6         | 17.65%  |
| Graphics card         | 4         | 11.76%  |
| Net/wireless          | 3         | 8.82%   |
| Multimedia controller | 3         | 8.82%   |
| Storage               | 1         | 2.94%   |
| Sound                 | 1         | 2.94%   |
| Firewire controller   | 1         | 2.94%   |
| Card reader           | 1         | 2.94%   |
| Camera                | 1         | 2.94%   |

