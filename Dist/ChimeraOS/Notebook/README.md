ChimeraOS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

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

Total: 64

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V3-772G              | [e9bc1c5d68](https://linux-hardware.org/?probe=e9bc1c5d68) | Jan 19, 2024 |
| Dell          | Latitude 7310               | [664667c69b](https://linux-hardware.org/?probe=664667c69b) | Jan 19, 2024 |
| HP            | Pavilion 15                 | [dad46e573f](https://linux-hardware.org/?probe=dad46e573f) | Jan 07, 2024 |
| ASUSTek       | G74Sx                       | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| Sony          | SVS13A25PLB                 | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP            | ProBook 4540s               | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| HP            | ProBook 4540s               | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Valve         | Galileo                     | [355d2e1a38](https://linux-hardware.org/?probe=355d2e1a38) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0018284858](https://linux-hardware.org/?probe=0018284858) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f65efa02b6](https://linux-hardware.org/?probe=f65efa02b6) | Dec 16, 2023 |
| Notebook      | P15SM-A/SM1-A               | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Dell          | Latitude E5540              | [33e3a21810](https://linux-hardware.org/?probe=33e3a21810) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [7cb8811992](https://linux-hardware.org/?probe=7cb8811992) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [9d2fdb067c](https://linux-hardware.org/?probe=9d2fdb067c) | Nov 25, 2023 |
| Acer          | Aspire V3-772G              | [742d987926](https://linux-hardware.org/?probe=742d987926) | Nov 21, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| Dell          | G15 5510                    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| Dell          | Precision 7520              | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Acer          | Aspire VX5-591G             | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
| Alienware     | 17 R2                       | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| Dell          | Latitude 3590               | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Acer          | Nitro AN515-57              | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Anbernic      | Win600                      | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| GPD           | P2 MAX                      | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| Acer          | Aspire A715-42G             | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| AMI           | Unknown                     | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Google        | Snappy                      | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Acer          | Nitro AN515-51              | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| ChimeraOS 44-1 | 13        | 24.53%  |
| ChimeraOS 43-1 | 12        | 22.64%  |
| ChimeraOS 39   | 8         | 15.09%  |
| ChimeraOS 42   | 7         | 13.21%  |
| ChimeraOS 41   | 5         | 9.43%   |
| ChimeraOS 45   | 2         | 3.77%   |
| ChimeraOS 44   | 2         | 3.77%   |
| ChimeraOS 38   | 2         | 3.77%   |
| ChimeraOS 43   | 1         | 1.89%   |
| ChimeraOS      | 1         | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.5.6-chos1-chimeraos-1 | 13        | 24.53%  |
| 6.3.9-chimeraos-1       | 13        | 24.53%  |
| 6.1.11-arch1-1          | 8         | 15.09%  |
| 6.1.27-1-lts            | 7         | 13.21%  |
| 6.1.21-1-lts            | 5         | 9.43%   |
| 6.5.3-chos1-chimeraos-1 | 2         | 3.77%   |
| 6.1.1-arch1-1           | 2         | 3.77%   |
| 6.6.7-chos4-chimeraos-1 | 1         | 1.89%   |
| 6.6.1-chos3-chimeraos-1 | 1         | 1.89%   |
| 6.4.9-0-generic         | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.6   | 13        | 24.53%  |
| 6.3.9   | 13        | 24.53%  |
| 6.1.11  | 8         | 15.09%  |
| 6.1.27  | 7         | 13.21%  |
| 6.1.21  | 5         | 9.43%   |
| 6.5.3   | 2         | 3.77%   |
| 6.1.1   | 2         | 3.77%   |
| 6.6.7   | 1         | 1.89%   |
| 6.6.1   | 1         | 1.89%   |
| 6.4.9   | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 41.51%  |
| 6.5     | 15        | 28.3%   |
| 6.3     | 13        | 24.53%  |
| 6.6     | 2         | 3.77%   |
| 6.4     | 1         | 1.89%   |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 53        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 51        | 96.23%  |
| X11     | 2         | 3.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 42        | 79.25%  |
| pt_BR | 3         | 5.66%   |
| es_ES | 3         | 5.66%   |
| it_IT | 2         | 3.77%   |
| fr_FR | 1         | 1.89%   |
| fr_CA | 1         | 1.89%   |
| C     | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 53        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 52        | 98.11%  |
| Ext4  | 1         | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 10        | 18.87%  |
| Acer                | 8         | 15.09%  |
| Lenovo              | 6         | 11.32%  |
| Dell                | 6         | 11.32%  |
| Hewlett-Packard     | 5         | 9.43%   |
| ONE-NETBOOK         | 3         | 5.66%   |
| MSI                 | 3         | 5.66%   |
| Razer               | 2         | 3.77%   |
| Valve               | 1         | 1.89%   |
| Sony                | 1         | 1.89%   |
| Notebook            | 1         | 1.89%   |
| Micro Electronics   | 1         | 1.89%   |
| GPD                 | 1         | 1.89%   |
| Google              | 1         | 1.89%   |
| Gigabyte Technology | 1         | 1.89%   |
| Anbernic            | 1         | 1.89%   |
| AMI                 | 1         | 1.89%   |
| Alienware           | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 3.77%   |
| Acer Aspire V3-772G                         | 2         | 3.77%   |
| Unknown                                     | 2         | 3.77%   |
| Valve Galileo                               | 1         | 1.89%   |
| Sony SVS13A25PLB                            | 1         | 1.89%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 1.89%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 1.89%   |
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P         | 1         | 1.89%   |
| Notebook P15SM-A/SM1-A                      | 1         | 1.89%   |
| MSI MS-7C91                                 | 1         | 1.89%   |
| MSI GE75 Raider 10SF                        | 1         | 1.89%   |
| MSI CX62 6QD                                | 1         | 1.89%   |
| Micro MG-VCP17I-3070                        | 1         | 1.89%   |
| Lenovo Y50-70 20378                         | 1         | 1.89%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 1.89%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 1.89%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.89%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 1.89%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 1.89%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 1.89%   |
| HP ProBook 4540s                            | 1         | 1.89%   |
| HP Pavilion 15                              | 1         | 1.89%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 1.89%   |
| HP 250 G4 Notebook PC                       | 1         | 1.89%   |
| GPD P2 MAX                                  | 1         | 1.89%   |
| Google Snappy                               | 1         | 1.89%   |
| Gigabyte Z97X-Gaming 5                      | 1         | 1.89%   |
| Dell Precision 7520                         | 1         | 1.89%   |
| Dell Latitude E5540                         | 1         | 1.89%   |
| Dell Latitude 7310                          | 1         | 1.89%   |
| Dell Latitude 3590                          | 1         | 1.89%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 1.89%   |
| Dell G15 5510                               | 1         | 1.89%   |
| ASUS Zephyrus S GX502GV_GX502GV             | 1         | 1.89%   |
| ASUS VivoBook_ASUSLaptop X570DD_X570DD      | 1         | 1.89%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 1.89%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 1.89%   |
| ASUS ROG CROSSHAIR VIII HERO                | 1         | 1.89%   |
| ASUS K45VM                                  | 1         | 1.89%   |
| ASUS G74Sx                                  | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 6         | 11.32%  |
| ONE-NETBOOK ONEXPLAYER | 3         | 5.66%   |
| Lenovo IdeaPad         | 3         | 5.66%   |
| Dell Latitude          | 3         | 5.66%   |
| Razer Blade            | 2         | 3.77%   |
| ASUS ROG               | 2         | 3.77%   |
| ASUS ASUS              | 2         | 3.77%   |
| Acer Nitro             | 2         | 3.77%   |
| Unknown                | 2         | 3.77%   |
| Valve Galileo          | 1         | 1.89%   |
| Sony SVS13A25PLB       | 1         | 1.89%   |
| Notebook P15SM-A       | 1         | 1.89%   |
| MSI MS-7C91            | 1         | 1.89%   |
| MSI GE75               | 1         | 1.89%   |
| MSI CX62               | 1         | 1.89%   |
| Micro MG-VCP17I-3070   | 1         | 1.89%   |
| Lenovo Y50-70          | 1         | 1.89%   |
| Lenovo ThinkPad        | 1         | 1.89%   |
| Lenovo Legion          | 1         | 1.89%   |
| HP Victus              | 1         | 1.89%   |
| HP ProBook             | 1         | 1.89%   |
| HP Pavilion            | 1         | 1.89%   |
| HP EliteBook           | 1         | 1.89%   |
| HP 250                 | 1         | 1.89%   |
| GPD P2                 | 1         | 1.89%   |
| Google Snappy          | 1         | 1.89%   |
| Gigabyte Z97X-Gaming   | 1         | 1.89%   |
| Dell Precision         | 1         | 1.89%   |
| Dell Inspiron          | 1         | 1.89%   |
| Dell G15               | 1         | 1.89%   |
| ASUS Zephyrus          | 1         | 1.89%   |
| ASUS VivoBook          | 1         | 1.89%   |
| ASUS TUF               | 1         | 1.89%   |
| ASUS K45VM             | 1         | 1.89%   |
| ASUS G74Sx             | 1         | 1.89%   |
| Anbernic Win600        | 1         | 1.89%   |
| Alienware 17           | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 18.87%  |
| 2023 | 6         | 11.32%  |
| 2020 | 6         | 11.32%  |
| 2017 | 6         | 11.32%  |
| 2019 | 4         | 7.55%   |
| 2015 | 4         | 7.55%   |
| 2013 | 4         | 7.55%   |
| 2022 | 3         | 5.66%   |
| 2014 | 3         | 5.66%   |
| 2012 | 3         | 5.66%   |
| 2016 | 2         | 3.77%   |
| 2018 | 1         | 1.89%   |
| 2011 | 1         | 1.89%   |

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
| No   | 52        | 98.11%  |
| Yes  | 1         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 12        | 22.64%  |
| 4.01-8.0    | 10        | 18.87%  |
| 32.01-64.0  | 10        | 18.87%  |
| 8.01-16.0   | 9         | 16.98%  |
| 3.01-4.0    | 6         | 11.32%  |
| 24.01-32.0  | 4         | 7.55%   |
| 64.01-256.0 | 2         | 3.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 24        | 45.28%  |
| 1.01-2.0  | 11        | 20.75%  |
| 3.01-4.0  | 10        | 18.87%  |
| 4.01-8.0  | 7         | 13.21%  |
| 8.01-16.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 52.83%  |
| 2      | 22        | 41.51%  |
| 6      | 1         | 1.89%   |
| 4      | 1         | 1.89%   |
| 3      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 81.13%  |
| Yes       | 10        | 18.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 81.13%  |
| No        | 10        | 18.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 84.91%  |
| No        | 8         | 15.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 20        | 37.74%  |
| Brazil       | 5         | 9.43%   |
| UK           | 3         | 5.66%   |
| Vietnam      | 2         | 3.77%   |
| Spain        | 2         | 3.77%   |
| Saudi Arabia | 2         | 3.77%   |
| Netherlands  | 2         | 3.77%   |
| Italy        | 2         | 3.77%   |
| Germany      | 2         | 3.77%   |
| Canada       | 2         | 3.77%   |
| Switzerland  | 1         | 1.89%   |
| Romania      | 1         | 1.89%   |
| Poland       | 1         | 1.89%   |
| Peru         | 1         | 1.89%   |
| Hungary      | 1         | 1.89%   |
| France       | 1         | 1.89%   |
| Czechia      | 1         | 1.89%   |
| Costa Rica   | 1         | 1.89%   |
| Colombia     | 1         | 1.89%   |
| Belgium      | 1         | 1.89%   |
| Algeria      | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 1.89%   |
| Vũng Tàu               | 1         | 1.89%   |
| Virginia Beach           | 1         | 1.89%   |
| Vila-seca                | 1         | 1.89%   |
| Tulcea                   | 1         | 1.89%   |
| St Louis                 | 1         | 1.89%   |
| Springfield              | 1         | 1.89%   |
| Soldotna                 | 1         | 1.89%   |
| Santa Cruz das Palmeiras | 1         | 1.89%   |
| San José                | 1         | 1.89%   |
| Saltillo                 | 1         | 1.89%   |
| Ridley Park              | 1         | 1.89%   |
| Pittsburg                | 1         | 1.89%   |
| Pennsauken               | 1         | 1.89%   |
| Parma                    | 1         | 1.89%   |
| Olympia                  | 1         | 1.89%   |
| Newport News             | 1         | 1.89%   |
| Monticello               | 1         | 1.89%   |
| Milan                    | 1         | 1.89%   |
| Miami                    | 1         | 1.89%   |
| Manchester               | 1         | 1.89%   |
| Manaus                   | 1         | 1.89%   |
| Maastricht               | 1         | 1.89%   |
| Lima                     | 1         | 1.89%   |
| Legazpia                 | 1         | 1.89%   |
| Las Vegas                | 1         | 1.89%   |
| Kolea                    | 1         | 1.89%   |
| Jeddah                   | 1         | 1.89%   |
| Hot Springs              | 1         | 1.89%   |
| Highland Park            | 1         | 1.89%   |
| Hewitt                   | 1         | 1.89%   |
| Herndon                  | 1         | 1.89%   |
| Gelsenkirchen            | 1         | 1.89%   |
| Foz do Iguaçu           | 1         | 1.89%   |
| Fortaleza                | 1         | 1.89%   |
| Fairbanks                | 1         | 1.89%   |
| Dessau                   | 1         | 1.89%   |
| Dammam                   | 1         | 1.89%   |
| Clichy-sous-Bois         | 1         | 1.89%   |
| Chattanooga              | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 13        | 16     | 15.66%  |
| Samsung Electronics         | 11        | 11     | 13.25%  |
| Sandisk                     | 6         | 6      | 7.23%   |
| Micron Technology           | 6         | 6      | 7.23%   |
| Kingston                    | 6         | 6      | 7.23%   |
| Unknown                     | 5         | 5      | 6.02%   |
| Seagate                     | 5         | 5      | 6.02%   |
| Intel                       | 5         | 5      | 6.02%   |
| Micron/Crucial Technology   | 3         | 4      | 3.61%   |
| Toshiba                     | 2         | 2      | 2.41%   |
| SK hynix                    | 2         | 2      | 2.41%   |
| Phison Electronics          | 2         | 2      | 2.41%   |
| KIOXIA                      | 2         | 2      | 2.41%   |
| Hitachi                     | 2         | 2      | 2.41%   |
| HGST                        | 2         | 2      | 2.41%   |
| Crucial                     | 2         | 2      | 2.41%   |
| WDC PC S                    | 1         | 1      | 1.2%    |
| SSSTC                       | 1         | 1      | 1.2%    |
| Realtek Semiconductor       | 1         | 1      | 1.2%    |
| Realtek                     | 1         | 1      | 1.2%    |
| NT-1TB                      | 1         | 1      | 1.2%    |
| Kingston Technology Company | 1         | 1      | 1.2%    |
| JMicron Technology          | 1         | 1      | 1.2%    |
| Biwin Storage Technology    | 1         | 1      | 1.2%    |
| A-DATA Technology           | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 4.71%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 3         | 3.53%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 2         | 2.35%   |
| Unknown MMC Card  64GB                             | 2         | 2.35%   |
| SK hynix HFM512GD3JX016N 512GB                     | 2         | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 2.35%   |
| Micron 1100 SATA 256GB SSD                         | 2         | 2.35%   |
| Kingston SV300S37A120G 120GB SSD                   | 2         | 2.35%   |
| Intel SSDPEKNU512GZ 512GB                          | 2         | 2.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 1.18%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 1.18%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1         | 1.18%   |
| WDC WDBNCE0010PNC 1TB SSD                          | 1         | 1.18%   |
| WDC WD7500BPVT-80HXZT3 752GB                       | 1         | 1.18%   |
| WDC WD7500BPVT-55HXZT3 752GB                       | 1         | 1.18%   |
| WDC WD20SPZX-08UA7 2TB                             | 1         | 1.18%   |
| WDC WD201KFGX-68BKJN0 20TB                         | 1         | 1.18%   |
| WDC WD10SPZX-80Z10T2 1TB                           | 1         | 1.18%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 1.18%   |
| WDC WD10SPCX-24HWST1 1TB                           | 1         | 1.18%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1         | 1.18%   |
| WDC WD10EZEX-60M2NA0 1TB                           | 1         | 1.18%   |
| WDC PC S N530 SDBPNPZ 256GB                        | 1         | 1.18%   |
| Unknown NVMe SSD Drive 1024GB                      | 1         | 1.18%   |
| Unknown MMC Card  512GB                            | 1         | 1.18%   |
| Unknown MMC Card  16GB                             | 1         | 1.18%   |
| Toshiba XG6 NVMe SSD Controller 256GB              | 1         | 1.18%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.18%   |
| SSSTC CVB-8D128-HP 128GB                           | 1         | 1.18%   |
| Seagate ST9320423AS 320GB                          | 1         | 1.18%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 1.18%   |
| Seagate ST3500418AS 500GB                          | 1         | 1.18%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.18%   |
| Sandisk WD_BLACK SN850X 2000GB                     | 1         | 1.18%   |
| Sandisk WD_BLACK SN770 2TB                         | 1         | 1.18%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 1         | 1.18%   |
| Sandisk WD Black SN850 1024GB                      | 1         | 1.18%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 1         | 1.18%   |
| SanDisk SDSSDX240GG25 240GB                        | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 11     | 52.38%  |
| Seagate | 5         | 5      | 23.81%  |
| Hitachi | 2         | 2      | 9.52%   |
| HGST    | 2         | 2      | 9.52%   |
| Toshiba | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 20.83%  |
| WDC                 | 4         | 5      | 16.67%  |
| Samsung Electronics | 4         | 4      | 16.67%  |
| Micron Technology   | 4         | 4      | 16.67%  |
| Crucial             | 2         | 2      | 8.33%   |
| SSSTC               | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| NT-1TB              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 35     | 41.1%   |
| SSD     | 19        | 25     | 26.03%  |
| HDD     | 18        | 21     | 24.66%  |
| MMC     | 4         | 4      | 5.48%   |
| Unknown | 2         | 2      | 2.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 34     | 44.12%  |
| SATA | 30        | 45     | 44.12%  |
| SAS  | 4         | 4      | 5.88%   |
| MMC  | 4         | 4      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 16        | 16     | 43.24%  |
| 0.01-0.5   | 16        | 25     | 43.24%  |
| 1.01-2.0   | 3         | 3      | 8.11%   |
| 3.01-4.0   | 1         | 1      | 2.7%    |
| 10.01-20.0 | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 18        | 33.96%  |
| 1001-2000      | 18        | 33.96%  |
| 251-500        | 7         | 13.21%  |
| 501-1000       | 5         | 9.43%   |
| 2001-3000      | 3         | 5.66%   |
| 101-250        | 2         | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 18        | 33.96%  |
| 51-100         | 10        | 18.87%  |
| 101-250        | 8         | 15.09%  |
| 251-500        | 7         | 13.21%  |
| 501-1000       | 5         | 9.43%   |
| More than 3000 | 3         | 5.66%   |
| 1001-2000      | 1         | 1.89%   |
| 1-20           | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 54        | 87     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 34        | 49.28%  |
| Samsung Electronics          | 7         | 10.14%  |
| AMD                          | 6         | 8.7%    |
| SanDisk                      | 5         | 7.25%   |
| Micron/Crucial Technology    | 3         | 4.35%   |
| SK hynix                     | 2         | 2.9%    |
| Phison Electronics           | 2         | 2.9%    |
| Micron Technology            | 2         | 2.9%    |
| KIOXIA                       | 2         | 2.9%    |
| Kingston Technology Company  | 2         | 2.9%    |
| Toshiba America Info Systems | 1         | 1.45%   |
| Realtek Semiconductor        | 1         | 1.45%   |
| INNOGRIT                     | 1         | 1.45%   |
| Biwin Storage Technology     | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 6.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 5.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 5.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 4.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 2.7%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.35%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.35%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.35%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.35%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.35%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.35%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 1.35%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.35%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.35%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.35%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.35%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.35%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 1         | 1.35%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.35%   |
| Intel SSD 660P Series                                                          | 1         | 1.35%   |
| Intel SSD 600P Series                                                          | 1         | 1.35%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.35%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 30        | 42.25%  |
| SATA | 30        | 42.25%  |
| RAID | 11        | 15.49%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 75.47%  |
| AMD    | 13        | 24.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 5.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 3.77%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 3.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 3.77%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 3.77%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 3.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.77%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 1.89%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.89%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.89%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.89%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.89%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.89%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.89%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.89%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.89%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 1.89%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.89%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 1.89%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.89%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.89%   |
| Intel Atom x7-Z8700 CPU @ 1.60GHz             | 1         | 1.89%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.89%   |
| Intel 12th Gen Core i5-12600KF                | 1         | 1.89%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.89%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.89%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 1.89%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.89%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 1.89%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 13        | 24.53%  |
| Intel Core i5 | 13        | 24.53%  |
| Other         | 9         | 16.98%  |
| AMD Ryzen 9   | 4         | 7.55%   |
| AMD Ryzen 7   | 4         | 7.55%   |
| AMD Ryzen 5   | 3         | 5.66%   |
| Intel Core i3 | 2         | 3.77%   |
| Intel Pentium | 1         | 1.89%   |
| Intel Core m3 | 1         | 1.89%   |
| Intel Celeron | 1         | 1.89%   |
| Intel Atom    | 1         | 1.89%   |
| AMD Athlon    | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 21        | 39.62%  |
| 2      | 13        | 24.53%  |
| 8      | 8         | 15.09%  |
| 6      | 7         | 13.21%  |
| 12     | 2         | 3.77%   |
| 14     | 1         | 1.89%   |
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
| 2      | 44        | 83.02%  |
| 1      | 9         | 16.98%  |

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


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 11        | 20.75%  |
| Unknown     | 11        | 20.75%  |
| Haswell     | 8         | 15.09%  |
| Skylake     | 4         | 7.55%   |
| Zen+        | 3         | 5.66%   |
| Zen 3       | 3         | 5.66%   |
| CometLake   | 3         | 5.66%   |
| TigerLake   | 2         | 3.77%   |
| SandyBridge | 2         | 3.77%   |
| IvyBridge   | 2         | 3.77%   |
| Zen 2       | 1         | 1.89%   |
| Zen         | 1         | 1.89%   |
| Silvermont  | 1         | 1.89%   |
| Goldmont    | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 41.67%  |
| Nvidia | 33        | 39.29%  |
| AMD    | 16        | 19.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 5.95%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 4         | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 4.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 3.57%   |
| Intel HD Graphics 630                                                       | 3         | 3.57%   |
| Intel HD Graphics 530                                                       | 3         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 2.38%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 2.38%   |
| Intel UHD Graphics 620                                                      | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 2.38%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2         | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.19%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.19%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                    | 1         | 1.19%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 1.19%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 1.19%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                       | 1         | 1.19%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                  | 1         | 1.19%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.19%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 1.19%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 1.19%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.19%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.19%   |
| Nvidia GK107M [GeForce GT 750M]                                             | 1         | 1.19%   |
| Nvidia GK107M [GeForce GT 640M LE]                                          | 1         | 1.19%   |
| Nvidia GK106M [GeForce GTX 760M]                                            | 1         | 1.19%   |
| Nvidia GK104M [GeForce GTX 860M]                                            | 1         | 1.19%   |
| Nvidia GF116M [GeForce GT 560M]                                             | 1         | 1.19%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                           | 1         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.19%   |
| Intel UHD Graphics 615                                                      | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 23        | 43.4%   |
| 1 x Intel      | 8         | 15.09%  |
| 1 x AMD        | 8         | 15.09%  |
| 1 x Nvidia     | 5         | 9.43%   |
| AMD + Nvidia   | 5         | 9.43%   |
| Intel + AMD    | 3         | 5.66%   |
| Other          | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 31        | 58.49%  |
| Proprietary | 21        | 39.62%  |
| Unknown     | 1         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 11        | 19.3%   |
| LG Display          | 10        | 17.54%  |
| BOE                 | 9         | 15.79%  |
| AU Optronics        | 9         | 15.79%  |
| Samsung Electronics | 2         | 3.51%   |
| Vizio               | 1         | 1.75%   |
| Valve               | 1         | 1.75%   |
| Unknown (XXX)       | 1         | 1.75%   |
| TMX                 | 1         | 1.75%   |
| Sharp               | 1         | 1.75%   |
| Sceptre Tech        | 1         | 1.75%   |
| SANYO               | 1         | 1.75%   |
| RTK                 | 1         | 1.75%   |
| Philips             | 1         | 1.75%   |
| PANDA               | 1         | 1.75%   |
| Lenovo              | 1         | 1.75%   |
| Insignia            | 1         | 1.75%   |
| HJW                 | 1         | 1.75%   |
| Goldstar            | 1         | 1.75%   |
| GameMax             | 1         | 1.75%   |
| Fujitsu Siemens     | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 3         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 2         | 3.51%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 3.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 3.51%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 1.75%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                  | 1         | 1.75%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 1.75%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 1.75%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 1.75%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch       | 1         | 1.75%   |
| SANYO LED MONITOR SAN3219 1360x768 304x228mm 15.0-inch               | 1         | 1.75%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 1.75%   |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                      | 1         | 1.75%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1         | 1.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD05DB 1920x1080 294x165mm 13.3-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD0459 1920x1080 382x215mm 17.3-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 1.75%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 1         | 1.75%   |
| LG Display LCD Monitor LGD02F8 1366x768 310x170mm 13.9-inch          | 1         | 1.75%   |
| Lenovo P27h-28 LEN62ED 2560x1440 597x336mm 27.0-inch                 | 1         | 1.75%   |
| Insignia NS-22E400NA14 BBY0042 1920x1080 544x306mm 24.6-inch         | 1         | 1.75%   |
| HJW MACROSILICON HJW9291 1680x1050 530x290mm 23.8-inch               | 1         | 1.75%   |
| Goldstar M237WDP GSM5779 1920x1080 510x290mm 23.1-inch               | 1         | 1.75%   |
| GameMax GMX32CEWQ GMX0315 2560x1440 697x392mm 31.5-inch              | 1         | 1.75%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1340 1600x900 294x165mm 13.3-inch      | 1         | 1.75%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 30        | 54.55%  |
| 1366x768 (WXGA) | 9         | 16.36%  |
| 2560x1440 (QHD) | 5         | 9.09%   |
| 1600x2560       | 3         | 5.45%   |
| 3840x2160 (4K)  | 2         | 3.64%   |
| 800x1280        | 1         | 1.82%   |
| 3440x1440       | 1         | 1.82%   |
| 1600x900 (HD+)  | 1         | 1.82%   |
| 1360x768        | 1         | 1.82%   |
| 1280x960        | 1         | 1.82%   |
| 1280x768        | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 45.61%  |
| 17     | 7         | 12.28%  |
| 13     | 3         | 5.26%   |
| 8      | 3         | 5.26%   |
| 31     | 2         | 3.51%   |
| 27     | 2         | 3.51%   |
| 21     | 2         | 3.51%   |
| 14     | 2         | 3.51%   |
| 84     | 1         | 1.75%   |
| 57     | 1         | 1.75%   |
| 54     | 1         | 1.75%   |
| 49     | 1         | 1.75%   |
| 35     | 1         | 1.75%   |
| 34     | 1         | 1.75%   |
| 23     | 1         | 1.75%   |
| 16     | 1         | 1.75%   |
| 11     | 1         | 1.75%   |
| 7      | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 50.88%  |
| 351-400     | 8         | 14.04%  |
| 501-600     | 3         | 5.26%   |
| 201-300     | 3         | 5.26%   |
| 101-200     | 3         | 5.26%   |
| 701-800     | 2         | 3.51%   |
| 601-700     | 2         | 3.51%   |
| 401-500     | 2         | 3.51%   |
| 1001-1500   | 2         | 3.51%   |
| 801-900     | 1         | 1.75%   |
| 1501-2000   | 1         | 1.75%   |
| 1-100       | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 88.46%  |
| 0.62  | 4         | 7.69%   |
| 21/9  | 1         | 1.92%   |
| 0.56  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 48.21%  |
| 121-130        | 7         | 12.5%   |
| 1-40           | 4         | 7.14%   |
| More than 1000 | 3         | 5.36%   |
| 81-90          | 3         | 5.36%   |
| 351-500        | 3         | 5.36%   |
| 71-80          | 2         | 3.57%   |
| 301-350        | 2         | 3.57%   |
| 201-250        | 2         | 3.57%   |
| 51-60          | 1         | 1.79%   |
| 151-200        | 1         | 1.79%   |
| 501-1000       | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 50.91%  |
| 101-120       | 10        | 18.18%  |
| 51-100        | 6         | 10.91%  |
| 161-240       | 5         | 9.09%   |
| More than 240 | 3         | 5.45%   |
| 1-50          | 3         | 5.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 77.36%  |
| 2     | 8         | 15.09%  |
| 0     | 3         | 5.66%   |
| 3     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 35        | 36.84%  |
| Intel                           | 30        | 31.58%  |
| Qualcomm Atheros                | 14        | 14.74%  |
| MediaTek                        | 5         | 5.26%   |
| Broadcom Limited                | 3         | 3.16%   |
| ASIX Electronics                | 2         | 2.11%   |
| TP-Link                         | 1         | 1.05%   |
| Samsung Electronics             | 1         | 1.05%   |
| Ralink Technology               | 1         | 1.05%   |
| Qualcomm Atheros Communications | 1         | 1.05%   |
| Qualcomm                        | 1         | 1.05%   |
| Broadcom                        | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 23.76%  |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 4.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 4.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 3.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 3.96%   |
| Intel Wireless 7265                                                    | 3         | 2.97%   |
| Intel Wireless 3165                                                    | 3         | 2.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 2.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 1.98%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.98%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.98%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.98%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 1.98%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.98%   |
| TP-Link 802.11ac NIC                                                   | 1         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.99%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.99%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1         | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.99%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.99%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1         | 0.99%   |
| Intel Centrino Wireless-N 6150                                         | 1         | 0.99%   |
| Intel Centrino Wireless-N + WiMAX 6150                                 | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 52.73%  |
| Qualcomm Atheros                | 11        | 20%     |
| MediaTek                        | 5         | 9.09%   |
| Realtek Semiconductor           | 4         | 7.27%   |
| TP-Link                         | 1         | 1.82%   |
| Ralink Technology               | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| Qualcomm                        | 1         | 1.82%   |
| Broadcom Limited                | 1         | 1.82%   |
| Broadcom                        | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 8.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 7.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 7.14%   |
| Intel Wireless 7265                                                  | 3         | 5.36%   |
| Intel Wireless 3165                                                  | 3         | 5.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 5.36%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 5.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 3.57%   |
| Intel Wireless 8265 / 8275                                           | 2         | 3.57%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 3.57%   |
| TP-Link 802.11ac NIC                                                 | 1         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.79%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.79%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 1.79%   |
| Intel Centrino Wireless-N + WiMAX 6150                               | 1         | 1.79%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1         | 1.79%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 1         | 1.79%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 73.33%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Intel                 | 3         | 6.67%   |
| Broadcom Limited      | 2         | 4.44%   |
| ASIX Electronics      | 2         | 4.44%   |
| Samsung Electronics   | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 53.33%  |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 11.11%  |
| Realtek PCIe GbE Family Controller                                     | 2         | 4.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 4.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 4.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 4.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 2.22%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 2.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 2.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 2.22%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.22%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 55.21%  |
| Ethernet | 43        | 44.79%  |

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
| 2     | 37        | 69.81%  |
| 1     | 15        | 28.3%   |
| 3     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 60.38%  |
| Yes  | 21        | 39.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 60%     |
| Qualcomm Atheros Communications | 5         | 11.11%  |
| Lite-On Technology              | 4         | 8.89%   |
| IMC Networks                    | 4         | 8.89%   |
| Realtek Semiconductor           | 1         | 2.22%   |
| Realtek                         | 1         | 2.22%   |
| MediaTek                        | 1         | 2.22%   |
| Foxconn / Hon Hai               | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 20%     |
| Intel Bluetooth wireless interface                  | 8         | 17.78%  |
| Intel AX210 Bluetooth                               | 5         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.67%   |
| IMC Networks Wireless_Device                        | 3         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.44%   |
| Lite-On Bluetooth Device                            | 2         | 4.44%   |
| Realtek Bluetooth Radio                             | 1         | 2.22%   |
| Realtek Bluetooth Radio                             | 1         | 2.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 2.22%   |
| MediaTek Wireless_Device                            | 1         | 2.22%   |
| Lite-On Wireless_Device                             | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Intel Bluetooth Device                              | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.22%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 37        | 46.25%  |
| Nvidia                 | 20        | 25%     |
| AMD                    | 15        | 18.75%  |
| Sony                   | 3         | 3.75%   |
| Realtek Semiconductor  | 1         | 1.25%   |
| Logitech               | 1         | 1.25%   |
| Kingston Technology    | 1         | 1.25%   |
| Google                 | 1         | 1.25%   |
| Generalplus Technology | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 10        | 10.31%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 6         | 6.19%   |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 5.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 5         | 5.15%   |
| Intel Tiger Lake-H HD Audio Controller                              | 4         | 4.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 4         | 4.12%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 3.09%   |
| Nvidia Audio device                                                 | 3         | 3.09%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 3.09%   |
| Intel CM238 HD Audio Controller                                     | 3         | 3.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 3.09%   |
| Sony DualSense wireless controller (PS5)                            | 2         | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 2.06%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 2.06%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 2.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 2.06%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.06%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 2.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 2.06%   |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 2.06%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 1.03%   |
| Realtek Semiconductor USB Audio                                     | 1         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 1.03%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.03%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 1.03%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1         | 1.03%   |
| Nvidia GF116 High Definition Audio Controller                       | 1         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 1.03%   |
| Logitech PRO X                                                      | 1         | 1.03%   |
| Kingston Technology HyperX QuadCast                                 | 1         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.03%   |
| Intel Alder Lake-S HD Audio Controller                              | 1         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 11        | 28.95%  |
| Sunplus Innovation Technology | 5         | 13.16%  |
| Microdia                      | 5         | 13.16%  |
| IMC Networks                  | 5         | 13.16%  |
| Realtek Semiconductor         | 2         | 5.26%   |
| Quanta                        | 2         | 5.26%   |
| Bison Electronics             | 2         | 5.26%   |
| Syntek                        | 1         | 2.63%   |
| Suyin                         | 1         | 2.63%   |
| Sonix Technology              | 1         | 2.63%   |
| Silicon Motion                | 1         | 2.63%   |
| Logitech                      | 1         | 2.63%   |
| Acer                          | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Sunplus HD WebCam                    | 3         | 7.89%   |
| IMC Networks Integrated Camera       | 3         | 7.89%   |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 5.26%   |
| Chicony Integrated Camera            | 2         | 5.26%   |
| Chicony HD WebCam                    | 2         | 5.26%   |
| Chicony HD User Facing               | 2         | 5.26%   |
| Bison Lenovo EasyCamera              | 2         | 5.26%   |
| Syntek USB2.0 Camera                 | 1         | 2.63%   |
| Suyin HP Truevision HD               | 1         | 2.63%   |
| Sunplus Integrated_Webcam_HD         | 1         | 2.63%   |
| Sunplus ASUS Webcam                  | 1         | 2.63%   |
| Sonix USB2.0 HD UVC WebCam           | 1         | 2.63%   |
| Silicon Motion 300k Pixel Camera     | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD         | 1         | 2.63%   |
| Realtek Integrated Webcam            | 1         | 2.63%   |
| Quanta HP HD Camera                  | 1         | 2.63%   |
| Quanta HD User Facing                | 1         | 2.63%   |
| Microdia USB 2.0 Camera              | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD        | 1         | 2.63%   |
| Microdia Integrated_Webcam_FHD       | 1         | 2.63%   |
| Microdia HP Webcam                   | 1         | 2.63%   |
| Logitech Webcam C930e                | 1         | 2.63%   |
| Chicony USB2.0 0.3M UVC WebCam       | 1         | 2.63%   |
| Chicony HP Wide Vision HD Camera     | 1         | 2.63%   |
| Chicony HP Truevision HD             | 1         | 2.63%   |
| Chicony HP HD Webcam [Fixed]         | 1         | 2.63%   |
| Chicony EasyCamera                   | 1         | 2.63%   |
| Acer BisonCam, NB Pro                | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |
| AuthenTec                  | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 25%     |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| Broadcom 5880  | 1         | 50%     |
| Broadcom 58200 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 60.38%  |
| 1     | 17        | 32.08%  |
| 2     | 4         | 7.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 13        | 52%     |
| Fingerprint reader    | 4         | 16%     |
| Multimedia controller | 3         | 12%     |
| Chipcard              | 2         | 8%      |
| Network               | 1         | 4%      |
| Net/wireless          | 1         | 4%      |
| Net/ethernet          | 1         | 4%      |

