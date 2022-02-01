MX 19 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 19.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Intel         | H81                      | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ECS           | A55F-M3                  | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| MSI           | B460M PRO                | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                  | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| ASUSTek       | Maximus VII HERO         | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO         | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Dell          | 0P611C A00               | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| GreatWall     | U320                     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Dell          | 0M017G A00               | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Intel         | Unknown                  | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Dell          | 0M017G A00               | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| Dell          | 0P611C A00               | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| ASUSTek       | X79-DELUXE               | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Intel         | DZ77SL-50K AAG55115-300  | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| MSI           | MPG B550 GAMING PLUS     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | TUF B450-PRO GAMING      | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| MSI           | B350 TOMAHAWK            | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| ASRock        | H81M-ITX                 | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus           | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASRock        | K8A780LM                 | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                 | [2340ea8f96](https://linux-hardware.org/?probe=2340ea8f96) | Feb 23, 2021 |
| ASRock        | K8A780LM                 | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| ASRock        | K8A780LM                 | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                 | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASRock        | K8A780LM                 | [ba37404fee](https://linux-hardware.org/?probe=ba37404fee) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus           | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| Intel         | MAHOBAY                  | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                  | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING  | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A            | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                  | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| ASRock        | H110M-ITX                | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| ASUSTek       | PRIME B450M-A            | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Dell          | 0D28YY A00               | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Dell          | 0M9KCM A02               | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Gigabyte      | B450M DS3H-CF            | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 8265                     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Dell          | 0M5DCD A00               | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0       | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                    | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                    | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3 | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3 | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| MSI           | 970A-G43                 | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Gigabyte      | GA-880GM-UD2H            | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Intel         | DCP847SKE G80890-105     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Gigabyte      | A320M-DS2-CF             | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                 | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| ASRock        | Z68 Pro3-M               | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | 0F373D A00               | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | M4A77T                   | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| ASUSTek       | PRIME H310M-K            | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| ASRock        | K8A780LM                 | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                 | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                 | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Gigabyte      | GA-880GA-UD3H            | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X            | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                   | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| Dell          | 088DT1 A01               | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| Gigabyte      | P43-ES3G                 | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| ASUSTek       | M2N-MX SE Plus           | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 14       | 28.57%  |
| 5.6.0-2-amd64              | 5        | 10.2%   |
| 5.10.0-5mx-amd64           | 3        | 6.12%   |
| 4.19.0-14-amd64            | 3        | 6.12%   |
| 4.19.0-13-amd64            | 3        | 6.12%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 4.08%   |
| 5.8.0-3-amd64              | 2        | 4.08%   |
| 5.4.0-3-amd64              | 2        | 4.08%   |
| 4.19.0-18-amd64            | 2        | 4.08%   |
| 4.19.0-17-amd64            | 2        | 4.08%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 2.04%   |
| 5.5.0-050500rc1-lowlatency | 1        | 2.04%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 2.04%   |
| 5.4.10                     | 1        | 2.04%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 2.04%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 2.04%   |
| 5.10.0-9mx-amd64           | 1        | 2.04%   |
| 5.10.0-8mx-rt-amd64        | 1        | 2.04%   |
| 5.10.0-0.bpo.3-amd64       | 1        | 2.04%   |
| 4.19.0-12-amd64            | 1        | 2.04%   |
| 4.19.0-10-686-pae          | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 21       | 47.73%  |
| 5.10.0  | 6        | 13.64%  |
| 5.6.0   | 5        | 11.36%  |
| 5.8.16  | 2        | 4.55%   |
| 5.8.0   | 2        | 4.55%   |
| 5.5.0   | 2        | 4.55%   |
| 5.4.0   | 2        | 4.55%   |
| 5.4.7   | 1        | 2.27%   |
| 5.4.10  | 1        | 2.27%   |
| 5.3.0   | 1        | 2.27%   |
| 5.2.21  | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 21       | 47.73%  |
| 5.10    | 6        | 13.64%  |
| 5.6     | 5        | 11.36%  |
| 5.8     | 4        | 9.09%   |
| 5.4     | 4        | 9.09%   |
| 5.5     | 2        | 4.55%   |
| 5.3     | 1        | 2.27%   |
| 5.2     | 1        | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 41       | 97.62%  |
| i686   | 1        | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| XFCE | 35       | 83.33%  |
| KDE5 | 5        | 11.9%   |
| MATE | 1        | 2.38%   |
| KDE  | 1        | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 42       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 39       | 92.86%  |
| SDDM    | 3        | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 13       | 28.89%  |
| Unknown | 9        | 20%     |
| sk_SK   | 4        | 8.89%   |
| pt_BR   | 3        | 6.67%   |
| pl_PL   | 3        | 6.67%   |
| en_GB   | 3        | 6.67%   |
| de_DE   | 3        | 6.67%   |
| uk_UA   | 1        | 2.22%   |
| tr_TR   | 1        | 2.22%   |
| hu_HU   | 1        | 2.22%   |
| fr_FR   | 1        | 2.22%   |
| es_ES   | 1        | 2.22%   |
| en_IE   | 1        | 2.22%   |
| en_AU   | 1        | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 69.05%  |
| EFI  | 13       | 30.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 40       | 95.24%  |
| Btrfs | 2        | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 50%     |
| MBR     | 20       | 47.62%  |
| Unknown | 1        | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 70.45%  |
| Yes       | 13       | 29.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 59.52%  |
| No        | 17       | 40.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 21.43%  |
| Dell                | 8        | 19.05%  |
| Gigabyte Technology | 6        | 14.29%  |
| ASRock              | 6        | 14.29%  |
| MSI                 | 4        | 9.52%   |
| Intel               | 4        | 9.52%   |
| Hewlett-Packard     | 1        | 2.38%   |
| GreatWall           | 1        | 2.38%   |
| Gateway             | 1        | 2.38%   |
| Fujitsu Siemens     | 1        | 2.38%   |
| ECS                 | 1        | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Dell Studio 540              | 2        | 4.76%   |
| ASRock K8A780LM              | 2        | 4.76%   |
| MSI MS-7C88                  | 1        | 2.38%   |
| MSI MS-7C56                  | 1        | 2.38%   |
| MSI MS-7A34                  | 1        | 2.38%   |
| MSI MS-7693                  | 1        | 2.38%   |
| Intel MAHOBAY                | 1        | 2.38%   |
| Intel H81                    | 1        | 2.38%   |
| Intel DCP847SKE G80890-105   | 1        | 2.38%   |
| HP 3031h                     | 1        | 2.38%   |
| GreatWall U320               | 1        | 2.38%   |
| Gigabyte Z68AP-D3            | 1        | 2.38%   |
| Gigabyte P43-ES3G            | 1        | 2.38%   |
| Gigabyte GA-880GM-UD2H       | 1        | 2.38%   |
| Gigabyte GA-880GA-UD3H       | 1        | 2.38%   |
| Gigabyte B450M DS3H          | 1        | 2.38%   |
| Gigabyte A320M-DS2           | 1        | 2.38%   |
| Gateway SX2185               | 1        | 2.38%   |
| Fujitsu Siemens ESPRIMO P    | 1        | 2.38%   |
| ECS A55F-M3                  | 1        | 2.38%   |
| Dell XPS720                  | 1        | 2.38%   |
| Dell OptiPlex 9010           | 1        | 2.38%   |
| Dell OptiPlex 790            | 1        | 2.38%   |
| Dell OptiPlex 760            | 1        | 2.38%   |
| Dell OptiPlex 390            | 1        | 2.38%   |
| Dell Inspiron 3847           | 1        | 2.38%   |
| ASUS X79-DELUXE              | 1        | 2.38%   |
| ASUS TUF B450-PRO GAMING     | 1        | 2.38%   |
| ASUS ROG STRIX B550-F GAMING | 1        | 2.38%   |
| ASUS PRIME H310M-R R2.0      | 1        | 2.38%   |
| ASUS PRIME H310M-K           | 1        | 2.38%   |
| ASUS PRIME B450M-A           | 1        | 2.38%   |
| ASUS M4A77T                  | 1        | 2.38%   |
| ASUS M2N-MX SE Plus          | 1        | 2.38%   |
| ASUS All Series              | 1        | 2.38%   |
| ASRock Z68 Pro3-M            | 1        | 2.38%   |
| ASRock X370 Gaming X         | 1        | 2.38%   |
| ASRock H81M-ITX              | 1        | 2.38%   |
| ASRock H110M-ITX             | 1        | 2.38%   |
| Unknown                      | 1        | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 4        | 9.52%   |
| ASUS PRIME              | 3        | 7.14%   |
| Dell Studio             | 2        | 4.76%   |
| ASRock K8A780LM         | 2        | 4.76%   |
| MSI MS-7C88             | 1        | 2.38%   |
| MSI MS-7C56             | 1        | 2.38%   |
| MSI MS-7A34             | 1        | 2.38%   |
| MSI MS-7693             | 1        | 2.38%   |
| Intel MAHOBAY           | 1        | 2.38%   |
| Intel H81               | 1        | 2.38%   |
| Intel DCP847SKE         | 1        | 2.38%   |
| HP 3031h                | 1        | 2.38%   |
| GreatWall U320          | 1        | 2.38%   |
| Gigabyte Z68AP-D3       | 1        | 2.38%   |
| Gigabyte P43-ES3G       | 1        | 2.38%   |
| Gigabyte GA-880GM-UD2H  | 1        | 2.38%   |
| Gigabyte GA-880GA-UD3H  | 1        | 2.38%   |
| Gigabyte B450M          | 1        | 2.38%   |
| Gigabyte A320M-DS2      | 1        | 2.38%   |
| Gateway SX2185          | 1        | 2.38%   |
| Fujitsu Siemens ESPRIMO | 1        | 2.38%   |
| ECS A55F-M3             | 1        | 2.38%   |
| Dell XPS720             | 1        | 2.38%   |
| Dell Inspiron           | 1        | 2.38%   |
| ASUS X79-DELUXE         | 1        | 2.38%   |
| ASUS TUF                | 1        | 2.38%   |
| ASUS ROG                | 1        | 2.38%   |
| ASUS M4A77T             | 1        | 2.38%   |
| ASUS M2N-MX             | 1        | 2.38%   |
| ASUS All                | 1        | 2.38%   |
| ASRock Z68              | 1        | 2.38%   |
| ASRock X370             | 1        | 2.38%   |
| ASRock H81M-ITX         | 1        | 2.38%   |
| ASRock H110M-ITX        | 1        | 2.38%   |
| Unknown                 | 1        | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 7        | 16.67%  |
| 2013 | 5        | 11.9%   |
| 2018 | 4        | 9.52%   |
| 2008 | 4        | 9.52%   |
| 2020 | 3        | 7.14%   |
| 2019 | 3        | 7.14%   |
| 2017 | 3        | 7.14%   |
| 2015 | 3        | 7.14%   |
| 2010 | 3        | 7.14%   |
| 2016 | 2        | 4.76%   |
| 2012 | 2        | 4.76%   |
| 2009 | 1        | 2.38%   |
| 2007 | 1        | 2.38%   |
| 2006 | 1        | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 42       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 42       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 15       | 35.71%  |
| 8.01-16.0  | 9        | 21.43%  |
| 3.01-4.0   | 7        | 16.67%  |
| 4.01-8.0   | 5        | 11.9%   |
| 1.01-2.0   | 4        | 9.52%   |
| 32.01-64.0 | 2        | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 14       | 31.82%  |
| 2.01-3.0  | 12       | 27.27%  |
| 3.01-4.0  | 7        | 15.91%  |
| 0.51-1.0  | 7        | 15.91%  |
| 4.01-8.0  | 3        | 6.82%   |
| 8.01-16.0 | 1        | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 45.45%  |
| 1      | 16       | 36.36%  |
| 5      | 3        | 6.82%   |
| 4      | 3        | 6.82%   |
| 3      | 2        | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 57.14%  |
| No        | 18       | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 69.05%  |
| Yes       | 13       | 30.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 83.33%  |
| Yes       | 7        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 23.81%  |
| UK          | 4        | 9.52%   |
| Slovakia    | 4        | 9.52%   |
| Poland      | 3        | 7.14%   |
| Brazil      | 3        | 7.14%   |
| Spain       | 2        | 4.76%   |
| Serbia      | 2        | 4.76%   |
| India       | 2        | 4.76%   |
| Germany     | 2        | 4.76%   |
| Australia   | 2        | 4.76%   |
| Ukraine     | 1        | 2.38%   |
| Turkey      | 1        | 2.38%   |
| Netherlands | 1        | 2.38%   |
| Ireland     | 1        | 2.38%   |
| Hungary     | 1        | 2.38%   |
| France      | 1        | 2.38%   |
| Denmark     | 1        | 2.38%   |
| Austria     | 1        | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 4        | 9.3%    |
| Montevallo               | 2        | 4.65%   |
| Belgrade                 | 2        | 4.65%   |
| Virginia Beach           | 1        | 2.33%   |
| Vienna                   | 1        | 2.33%   |
| Valencia                 | 1        | 2.33%   |
| Tilburg                  | 1        | 2.33%   |
| Szar                     | 1        | 2.33%   |
| Sydney                   | 1        | 2.33%   |
| Stargard                 | 1        | 2.33%   |
| Springdale               | 1        | 2.33%   |
| Serrana                  | 1        | 2.33%   |
| Pleasant Hill            | 1        | 2.33%   |
| Pabianice                | 1        | 2.33%   |
| Oxford                   | 1        | 2.33%   |
| Norwalk                  | 1        | 2.33%   |
| Newtownabbey             | 1        | 2.33%   |
| Melbourne                | 1        | 2.33%   |
| McLoud                   | 1        | 2.33%   |
| Mainz                    | 1        | 2.33%   |
| Madrid                   | 1        | 2.33%   |
| Lyon                     | 1        | 2.33%   |
| Kharagpur                | 1        | 2.33%   |
| Istanbul                 | 1        | 2.33%   |
| Greenwich                | 1        | 2.33%   |
| Gosport                  | 1        | 2.33%   |
| Gdansk                   | 1        | 2.33%   |
| Fort Wayne               | 1        | 2.33%   |
| Florian??polis           | 1        | 2.33%   |
| Dubno                    | 1        | 2.33%   |
| Chula Vista              | 1        | 2.33%   |
| Castleknock              | 1        | 2.33%   |
| Campos dos Goytacazes    | 1        | 2.33%   |
| Bremerhaven              | 1        | 2.33%   |
| Bengaluru                | 1        | 2.33%   |
| Barrington               | 1        | 2.33%   |
| Ankara                   | 1        | 2.33%   |
| Albertslund Municipality | 1        | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 20       | 29     | 25.64%  |
| WDC                       | 16       | 19     | 20.51%  |
| Hitachi                   | 8        | 11     | 10.26%  |
| Samsung Electronics       | 6        | 7      | 7.69%   |
| Toshiba                   | 5        | 6      | 6.41%   |
| Crucial                   | 5        | 5      | 6.41%   |
| Kingston                  | 4        | 5      | 5.13%   |
| SanDisk                   | 3        | 3      | 3.85%   |
| Mushkin                   | 2        | 2      | 2.56%   |
| GOODRAM                   | 2        | 3      | 2.56%   |
| A-DATA Technology         | 2        | 3      | 2.56%   |
| Micron/Crucial Technology | 1        | 1      | 1.28%   |
| KingFast                  | 1        | 1      | 1.28%   |
| Intel                     | 1        | 2      | 1.28%   |
| Fujitsu                   | 1        | 2      | 1.28%   |
| Corsair                   | 1        | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3        | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 3        | 3.45%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2        | 2.3%    |
| WDC WD15EARX-00PASB0 1TB            | 2        | 2.3%    |
| Toshiba MK5065GSX 500GB             | 2        | 2.3%    |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 2.3%    |
| SanDisk SDSSDP128G 128GB            | 2        | 2.3%    |
| Hitachi HTS543232A7A384 320GB       | 2        | 2.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 1.15%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1        | 1.15%   |
| WDC WD80EZAZ-11TDBA0 8TB            | 1        | 1.15%   |
| WDC WD5003ABYX-01WERA1 500GB        | 1        | 1.15%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 1.15%   |
| WDC WD2500JS-75NCB3 250GB           | 1        | 1.15%   |
| WDC WD2500AAJS-00L7A0 250GB         | 1        | 1.15%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 1.15%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1.15%   |
| WDC WD1600AVVS-63L2B0 160GB         | 1        | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1        | 1.15%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1        | 1.15%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 1.15%   |
| WDC WD10EARX-00N0YB0 1TB            | 1        | 1.15%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 1.15%   |
| Toshiba MK6465GSX 640GB             | 1        | 1.15%   |
| Toshiba MG06ACA10TE 10TB            | 1        | 1.15%   |
| Toshiba DT01ACA300 3TB              | 1        | 1.15%   |
| Toshiba DT01ACA100 1TB              | 1        | 1.15%   |
| Seagate ST3500820AS 500GB           | 1        | 1.15%   |
| Seagate ST3500418AS 500GB           | 1        | 1.15%   |
| Seagate ST3500413AS 500GB           | 1        | 1.15%   |
| Seagate ST3320413CS 320GB           | 1        | 1.15%   |
| Seagate ST3320413AS 320GB           | 1        | 1.15%   |
| Seagate ST33000651NS 3TB            | 1        | 1.15%   |
| Seagate ST320LT007-9ZV142 320GB     | 1        | 1.15%   |
| Seagate ST3160318AS 160GB           | 1        | 1.15%   |
| Seagate ST2000DM001-9YN164 2TB      | 1        | 1.15%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1.15%   |
| Seagate ST1000NM0055-1V410C 1TB     | 1        | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB      | 1        | 1.15%   |
| Seagate ST1000DM003-1SB10C 1TB      | 1        | 1.15%   |
| Seagate ST1000DM003-1SB102 1TB      | 1        | 1.15%   |
| Seagate ST1000DM003-1ER162 1TB      | 1        | 1.15%   |
| SanDisk SSD PLUS 1000GB             | 1        | 1.15%   |
| Samsung SSD 970 EVO Plus 1TB        | 1        | 1.15%   |
| Samsung SSD 970 EVO 1TB             | 1        | 1.15%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.15%   |
| Samsung SSD 860 EVO 1TB             | 1        | 1.15%   |
| Samsung SSD 850 EVO 120GB           | 1        | 1.15%   |
| Samsung HD322GJ 320GB               | 1        | 1.15%   |
| Mushkin MKNSSDPL500GB-D8            | 1        | 1.15%   |
| Mushkin MKNSSDAT60GB-V 64GB         | 1        | 1.15%   |
| Micron/Crucial NVMe SSD Drive 500GB | 1        | 1.15%   |
| Kingston SKC600512G 512GB SSD       | 1        | 1.15%   |
| Kingston SKC600256G 256GB SSD       | 1        | 1.15%   |
| Kingston SKC2000M8250G 250GB        | 1        | 1.15%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1.15%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 1.15%   |
| KingFast SSD 256GB                  | 1        | 1.15%   |
| Intel SSDSC2KW256G8 256GB           | 1        | 1.15%   |
| Hitachi HUA723020ALA641 2TB         | 1        | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 29     | 40.82%  |
| WDC                 | 14       | 17     | 28.57%  |
| Hitachi             | 8        | 11     | 16.33%  |
| Toshiba             | 5        | 6      | 10.2%   |
| Samsung Electronics | 1        | 2      | 2.04%   |
| Fujitsu             | 1        | 2      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 5        | 5      | 21.74%  |
| SanDisk             | 3        | 3      | 13.04%  |
| Samsung Electronics | 3        | 3      | 13.04%  |
| Kingston            | 3        | 4      | 13.04%  |
| WDC                 | 2        | 2      | 8.7%    |
| GOODRAM             | 2        | 3      | 8.7%    |
| A-DATA Technology   | 2        | 3      | 8.7%    |
| Mushkin             | 1        | 1      | 4.35%   |
| KingFast            | 1        | 1      | 4.35%   |
| Intel               | 1        | 2      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 67     | 59.02%  |
| SSD  | 19       | 27     | 31.15%  |
| NVMe | 6        | 6      | 9.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 94     | 86.96%  |
| NVMe | 6        | 6      | 13.04%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 51     | 50%     |
| 0.51-1.0   | 18       | 28     | 28.13%  |
| 1.01-2.0   | 6        | 7      | 9.38%   |
| 2.01-3.0   | 4        | 4      | 6.25%   |
| 3.01-4.0   | 2        | 2      | 3.13%   |
| 4.01-10.0  | 2        | 2      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 11       | 23.4%   |
| 501-1000       | 8        | 17.02%  |
| 1001-2000      | 7        | 14.89%  |
| 101-250        | 6        | 12.77%  |
| More than 3000 | 5        | 10.64%  |
| 51-100         | 4        | 8.51%   |
| 21-50          | 3        | 6.38%   |
| 2001-3000      | 3        | 6.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 20.93%  |
| 251-500        | 8        | 18.6%   |
| 21-50          | 7        | 16.28%  |
| 101-250        | 7        | 16.28%  |
| 501-1000       | 4        | 9.3%    |
| 1001-2000      | 3        | 6.98%   |
| 2001-3000      | 2        | 4.65%   |
| 51-100         | 2        | 4.65%   |
| More than 3000 | 1        | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5003ABYX-01WERA1 500GB      | 1        | 1      | 5.88%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 1      | 5.88%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 1      | 5.88%   |
| WDC WD1600AVVS-63L2B0 160GB       | 1        | 1      | 5.88%   |
| WDC WD10EZEX-75WN4A0 1TB          | 1        | 1      | 5.88%   |
| Toshiba MK6465GSX 640GB           | 1        | 1      | 5.88%   |
| Seagate ST3500820AS 500GB         | 1        | 1      | 5.88%   |
| Seagate ST3320413CS 320GB         | 1        | 1      | 5.88%   |
| Seagate ST33000651NS 3TB          | 1        | 1      | 5.88%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 5.88%   |
| Samsung Electronics HD322GJ 320GB | 1        | 2      | 5.88%   |
| Hitachi HUA722020ALA331 2TB       | 1        | 1      | 5.88%   |
| Hitachi HDT721010SLA360 1TB       | 1        | 1      | 5.88%   |
| Hitachi HDP725016GLA380 160GB     | 1        | 1      | 5.88%   |
| Fujitsu MHV2060BH PL 64GB         | 1        | 2      | 5.88%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 5.88%   |
| Crucial CT240M500SSD1 240GB       | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 31.25%  |
| Seagate             | 3        | 4      | 18.75%  |
| Hitachi             | 3        | 3      | 18.75%  |
| Crucial             | 2        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 2      | 6.25%   |
| Fujitsu             | 1        | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 35.71%  |
| Seagate             | 3        | 4      | 21.43%  |
| Hitachi             | 3        | 3      | 21.43%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 2      | 7.14%   |
| Fujitsu             | 1        | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 17     | 85.71%  |
| SSD  | 2        | 2      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2        | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 66.67%  |
| Seagate | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 34       | 72     | 62.96%  |
| Malfunc  | 13       | 19     | 24.07%  |
| Detected | 4        | 5      | 7.41%   |
| Failed   | 3        | 4      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 23       | 43.4%   |
| AMD                         | 16       | 30.19%  |
| Samsung Electronics         | 2        | 3.77%   |
| Nvidia                      | 2        | 3.77%   |
| Marvell Technology Group    | 2        | 3.77%   |
| JMicron Technology          | 2        | 3.77%   |
| ASMedia Technology          | 2        | 3.77%   |
| Silicon Motion              | 1        | 1.89%   |
| Phison Electronics          | 1        | 1.89%   |
| Micron/Crucial Technology   | 1        | 1.89%   |
| Kingston Technology Company | 1        | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 9.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 6.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 5.26%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 3.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 3.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 3.95%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.63%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.63%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.63%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 2.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.32%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.32%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.32%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.32%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 1.32%   |
| Nvidia MCP55 IDE                                                                        | 1        | 1.32%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.32%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 1.32%   |
| Marvell Group 88SE9170 SATA 6G Controller                                               | 1        | 1.32%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 1.32%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.32%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.32%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.32%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.32%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.32%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.32%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.32%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.32%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.32%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 32       | 55.17%  |
| IDE  | 18       | 31.03%  |
| NVMe | 6        | 10.34%  |
| RAID | 2        | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 59.52%  |
| AMD    | 17       | 40.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 7.14%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 4.76%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 4.76%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 4.76%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 2.38%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 2.38%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 2.38%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 2.38%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.38%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.38%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 2.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 2.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 2.38%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 2.38%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 2.38%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 2.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 2.38%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.38%   |
| Intel Core 2 Extreme CPU Q6850 @ 3.00GHz    | 1        | 2.38%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.38%   |
| Intel Celeron D CPU 3.46GHz                 | 1        | 2.38%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 2.38%   |
| Intel Atom CPU D2550 @ 1.86GHz              | 1        | 2.38%   |
| AMD Sempron Processor 3000+                 | 1        | 2.38%   |
| AMD Sempron Processor 2800+                 | 1        | 2.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.38%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.38%   |
| AMD Phenom II X6 1090T Processor            | 1        | 2.38%   |
| AMD Phenom II X4 965 Processor              | 1        | 2.38%   |
| AMD Phenom II X4 925 Processor              | 1        | 2.38%   |
| AMD E1-2500 APU with Radeon HD Graphics     | 1        | 2.38%   |
| AMD Athlon X4 950 Quad Core Processor       | 1        | 2.38%   |
| AMD Athlon II X2 260 Processor              | 1        | 2.38%   |
| AMD Athlon 7750 Dual-Core Processor         | 1        | 2.38%   |
| AMD A4-3300 APU with Radeon HD Graphics     | 1        | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 14.29%  |
| Intel Core i7           | 4        | 9.52%   |
| AMD Ryzen 5             | 4        | 9.52%   |
| Intel Core i3           | 3        | 7.14%   |
| Intel Core 2 Quad       | 3        | 7.14%   |
| AMD Ryzen 7             | 3        | 7.14%   |
| Intel Pentium           | 2        | 4.76%   |
| AMD Sempron             | 2        | 4.76%   |
| AMD Phenom II X4        | 2        | 4.76%   |
| Intel Pentium Gold      | 1        | 2.38%   |
| Intel Pentium Dual-Core | 1        | 2.38%   |
| Intel Core 2 Extreme    | 1        | 2.38%   |
| Intel Core 2 Duo        | 1        | 2.38%   |
| Intel Celeron D         | 1        | 2.38%   |
| Intel Celeron           | 1        | 2.38%   |
| Intel Atom              | 1        | 2.38%   |
| AMD Phenom II X6        | 1        | 2.38%   |
| AMD E1                  | 1        | 2.38%   |
| AMD Athlon X4           | 1        | 2.38%   |
| AMD Athlon II X2        | 1        | 2.38%   |
| AMD Athlon              | 1        | 2.38%   |
| AMD A4                  | 1        | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 38.1%   |
| 4      | 14       | 33.33%  |
| 6      | 5        | 11.9%   |
| 8      | 4        | 9.52%   |
| 1      | 3        | 7.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 59.52%  |
| 2      | 17       | 40.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 42       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 5        | 11.9%   |
| Unknown    | 5        | 11.9%   |
| 0x306c3    | 4        | 9.52%   |
| 0x1067a    | 2        | 4.76%   |
| 0x10677    | 2        | 4.76%   |
| 0x08701021 | 2        | 4.76%   |
| 0x0800820d | 2        | 4.76%   |
| 0xf65      | 1        | 2.38%   |
| 0xa0653    | 1        | 2.38%   |
| 0x906ed    | 1        | 2.38%   |
| 0x906eb    | 1        | 2.38%   |
| 0x6fb      | 1        | 2.38%   |
| 0x506e3    | 1        | 2.38%   |
| 0x306e4    | 1        | 2.38%   |
| 0x306a9    | 1        | 2.38%   |
| 0x30661    | 1        | 2.38%   |
| 0x20652    | 1        | 2.38%   |
| 0x08001138 | 1        | 2.38%   |
| 0x08001137 | 1        | 2.38%   |
| 0x08001126 | 1        | 2.38%   |
| 0x0700010f | 1        | 2.38%   |
| 0x06006118 | 1        | 2.38%   |
| 0x03000027 | 1        | 2.38%   |
| 0x010000dc | 1        | 2.38%   |
| 0x010000db | 1        | 2.38%   |
| 0x010000c8 | 1        | 2.38%   |
| 0x01000083 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 11.9%   |
| Penryn      | 5        | 11.9%   |
| K10         | 5        | 11.9%   |
| Haswell     | 4        | 9.52%   |
| Zen         | 3        | 7.14%   |
| IvyBridge   | 3        | 7.14%   |
| Zen+        | 2        | 4.76%   |
| Zen 2       | 2        | 4.76%   |
| KabyLake    | 2        | 4.76%   |
| K8 Hammer   | 2        | 4.76%   |
| Westmere    | 1        | 2.38%   |
| Skylake     | 1        | 2.38%   |
| NetBurst    | 1        | 2.38%   |
| K10 Llano   | 1        | 2.38%   |
| Jaguar      | 1        | 2.38%   |
| Excavator   | 1        | 2.38%   |
| Core        | 1        | 2.38%   |
| CometLake   | 1        | 2.38%   |
| Bonnell     | 1        | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 16       | 34.78%  |
| AMD    | 16       | 34.78%  |
| Intel  | 14       | 30.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 10%     |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 6%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 6%      |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 4%      |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 2        | 4%      |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 2        | 4%      |
| AMD RS780L [Radeon 3000]                                                    | 2        | 4%      |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 2%      |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 2%      |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 2%      |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2%      |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2%      |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 2%      |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 2%      |
| Nvidia GF114 [GeForce GTX 560 SE]                                           | 1        | 2%      |
| Nvidia GF110 [GeForce GTX 570]                                              | 1        | 2%      |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 2%      |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 2%      |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2%      |
| Intel HD Graphics 530                                                       | 1        | 2%      |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2%      |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 2%      |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2%      |
| AMD SuperSumo [Radeon HD 6410D]                                             | 1        | 2%      |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                           | 1        | 2%      |
| AMD RV516 [Radeon X1300/X1550 Series]                                       | 1        | 2%      |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 2%      |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 2%      |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 2%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2%      |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 2%      |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 2%      |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 16       | 35.56%  |
| 1 x AMD    | 16       | 35.56%  |
| 1 x Intel  | 12       | 26.67%  |
| 3 x AMD    | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 74.42%  |
| Proprietary | 11       | 25.58%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 31.11%  |
| 1.01-2.0   | 9        | 20%     |
| 0.01-0.5   | 8        | 17.78%  |
| 0.51-1.0   | 6        | 13.33%  |
| 7.01-8.0   | 3        | 6.67%   |
| 3.01-4.0   | 3        | 6.67%   |
| 5.01-6.0   | 1        | 2.22%   |
| 2.01-3.0   | 1        | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 20%     |
| Goldstar             | 8        | 20%     |
| Dell                 | 6        | 15%     |
| Acer                 | 4        | 10%     |
| ViewSonic            | 2        | 5%      |
| Philips              | 2        | 5%      |
| Ancor Communications | 2        | 5%      |
| Vestel Elektronik    | 1        | 2.5%    |
| Sanyo                | 1        | 2.5%    |
| MSI                  | 1        | 2.5%    |
| IBM                  | 1        | 2.5%    |
| HYO                  | 1        | 2.5%    |
| Eizo                 | 1        | 2.5%    |
| BenQ                 | 1        | 2.5%    |
| AOC                  | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 4        | 9.76%   |
| Goldstar LG 32 FHD GSM76FF 1920x1080 700x390mm 31.5-inch                | 2        | 4.88%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 2.44%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 2.44%   |
| Vestel Elektronik LCD Monitor VES3700 1920x540                          | 1        | 2.44%   |
| Sanyo LCD MONITOR SAN2213 1920x1080 474x296mm 22.0-inch                 | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 2.44%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 2.44%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 2.44%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1        | 2.44%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1        | 2.44%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                       | 1        | 2.44%   |
| IBM L191p IBM24CB 1280x1024 380x300mm 19.1-inch                         | 1        | 2.44%   |
| HYO DUAL-DVI HYO049B 2560x1440 597x336mm 27.0-inch                      | 1        | 2.44%   |
| Goldstar W2361 GSM56FA 1920x1080 510x290mm 23.1-inch                    | 1        | 2.44%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 1        | 2.44%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch              | 1        | 2.44%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1        | 2.44%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 1        | 2.44%   |
| Goldstar E2411 GSM583B 1920x1080 477x268mm 21.5-inch                    | 1        | 2.44%   |
| Eizo S1921 ENC1831 1280x1024 376x301mm 19.0-inch                        | 1        | 2.44%   |
| Dell U4320Q DEL41D6 3840x2160 940x530mm 42.5-inch                       | 1        | 2.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 1        | 2.44%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                   | 1        | 2.44%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                      | 1        | 2.44%   |
| Dell P2210 DEL404C 1680x1050 474x296mm 22.0-inch                        | 1        | 2.44%   |
| Dell E1913 DELD051 1440x900 408x255mm 18.9-inch                         | 1        | 2.44%   |
| BenQ GW2406Z BNQ78E1 1920x1080 527x296mm 23.8-inch                      | 1        | 2.44%   |
| AOC 2060W AOC2060 1600x900 430x240mm 19.4-inch                          | 1        | 2.44%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                          | 1        | 2.44%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch        | 1        | 2.44%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch   | 1        | 2.44%   |
| Acer XF240H ACR0472 1920x1080 530x300mm 24.0-inch                       | 1        | 2.44%   |
| Acer X203H ACR009D 1600x900 443x249mm 20.0-inch                         | 1        | 2.44%   |
| Acer HX1953L ACR038C 1600x900 432x239mm 19.4-inch                       | 1        | 2.44%   |
| Acer H243H ACR0074 1920x1080 530x290mm 23.8-inch                        | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 50%     |
| 1600x1200          | 4        | 10%     |
| 3840x2160 (4K)     | 3        | 7.5%    |
| 1366x768 (WXGA)    | 3        | 7.5%    |
| 1680x1050 (WSXGA+) | 2        | 5%      |
| 1600x900 (HD+)     | 2        | 5%      |
| 1440x900 (WXGA+)   | 2        | 5%      |
| 1280x1024 (SXGA)   | 2        | 5%      |
| 2560x1440 (QHD)    | 1        | 2.5%    |
| 1920x1200 (WUXGA)  | 1        | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 8        | 19.51%  |
| 24     | 7        | 17.07%  |
| 19     | 5        | 12.2%   |
| 27     | 4        | 9.76%   |
| 18     | 4        | 9.76%   |
| 23     | 3        | 7.32%   |
| 84     | 2        | 4.88%   |
| 65     | 2        | 4.88%   |
| 31     | 2        | 4.88%   |
| 20     | 2        | 4.88%   |
| 42     | 1        | 2.44%   |
| 22     | 1        | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 17       | 42.5%   |
| 501-600     | 14       | 35%     |
| 601-700     | 2        | 5%      |
| 351-400     | 2        | 5%      |
| 1501-2000   | 2        | 5%      |
| 1001-1500   | 2        | 5%      |
| 901-1000    | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 28       | 71.79%  |
| 16/10 | 5        | 12.82%  |
| 4/3   | 4        | 10.26%  |
| 5/4   | 2        | 5.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 45%     |
| 151-200        | 7        | 17.5%   |
| More than 1000 | 4        | 10%     |
| 301-350        | 4        | 10%     |
| 141-150        | 3        | 7.5%    |
| 351-500        | 2        | 5%      |
| 251-300        | 1        | 2.5%    |
| 501-1000       | 1        | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 76.92%  |
| 101-120 | 7        | 17.95%  |
| 1-50    | 2        | 5.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 92.86%  |
| 2     | 3        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 54.9%   |
| Intel                 | 11       | 21.57%  |
| Qualcomm Atheros      | 3        | 5.88%   |
| Broadcom              | 3        | 5.88%   |
| Ralink                | 2        | 3.92%   |
| Nvidia                | 1        | 1.96%   |
| D-Link System         | 1        | 1.96%   |
| Broadcom Limited      | 1        | 1.96%   |
| ASUSTek Computer      | 1        | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 43.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 5.26%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 1.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.75%   |
| Realtek 802.11ac NIC                                              | 1        | 1.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.75%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.75%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 1        | 1.75%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.75%   |
| Intel Wireless 7260                                               | 1        | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.75%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.75%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.75%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.75%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.75%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1        | 1.75%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]          | 1        | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 30.77%  |
| Ralink                | 2        | 15.38%  |
| Qualcomm Atheros      | 2        | 15.38%  |
| Intel                 | 2        | 15.38%  |
| Broadcom              | 2        | 15.38%  |
| ASUSTek Computer      | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 7.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 7.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 7.69%   |
| Realtek 802.11ac NIC                                       | 1        | 7.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 7.69%   |
| Ralink RT2800 802.11n PCI                                  | 1        | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 7.69%   |
| Qualcomm Atheros AR922X Wireless Network Adapter           | 1        | 7.69%   |
| Intel Wireless 7260                                        | 1        | 7.69%   |
| Intel Wi-Fi 6 AX200                                        | 1        | 7.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 7.69%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1        | 7.69%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]   | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 65.12%  |
| Intel                 | 10       | 23.26%  |
| Qualcomm Atheros      | 1        | 2.33%   |
| Nvidia                | 1        | 2.33%   |
| D-Link System         | 1        | 2.33%   |
| Broadcom Limited      | 1        | 2.33%   |
| Broadcom              | 1        | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 56.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 6.82%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.27%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.27%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.27%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.27%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 2.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.27%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 76.36%  |
| WiFi     | 13       | 23.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 76.47%  |
| WiFi     | 12       | 23.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 73.81%  |
| 2     | 10       | 23.81%  |
| 3     | 1        | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 92.86%  |
| Yes  | 3        | 7.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 2        | 28.57%  |
| Cambridge Silicon Radio         | 2        | 28.57%  |
| Qualcomm Atheros Communications | 1        | 14.29%  |
| Broadcom                        | 1        | 14.29%  |
| ASUSTek Computer                | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 14.29%  |
| ASUS BCM20702A0                                     | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 24       | 34.29%  |
| AMD                 | 21       | 30%     |
| Nvidia              | 16       | 22.86%  |
| Creative Labs       | 4        | 5.71%   |
| C-Media Electronics | 2        | 2.86%   |
| Tenx Technology     | 1        | 1.43%   |
| Logitech            | 1        | 1.43%   |
| JMTek               | 1        | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 7.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 6.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 6.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 3.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 3.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 2.44%   |
| Nvidia High Definition Audio Controller                                    | 2        | 2.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 2.44%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.44%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 2.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.44%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 2        | 2.44%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 2        | 2.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.44%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.44%   |
| Tenx Technology USB AUDIO                                                  | 1        | 1.22%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.22%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.22%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.22%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.22%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 1.22%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 1.22%   |
| Logitech G432 Gaming Headset                                               | 1        | 1.22%   |
| JMTek iTalk-02                                                             | 1        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.22%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.22%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.22%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.22%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.22%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 1.22%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.22%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.22%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.22%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.22%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.22%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 1        | 1.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 1.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10       | 22.73%  |
| Kingston            | 10       | 22.73%  |
| Corsair             | 7        | 15.91%  |
| SK Hynix            | 4        | 9.09%   |
| Samsung Electronics | 3        | 6.82%   |
| G.Skill             | 3        | 6.82%   |
| Patriot             | 2        | 4.55%   |
| Smart               | 1        | 2.27%   |
| RZX                 | 1        | 2.27%   |
| OCZ                 | 1        | 2.27%   |
| Crucial             | 1        | 2.27%   |
| Axiom               | 1        | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 3        | 5.88%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                | 2        | 3.92%   |
| SK Hynix RAM HYMP125U64CP8-S6 2048MB DIMM DDR2 49926MT/s  | 2        | 3.92%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                 | 1        | 1.96%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1        | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 1        | 1.96%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 1.96%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 1        | 1.96%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s               | 1        | 1.96%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                | 1        | 1.96%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s                | 1        | 1.96%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 1        | 1.96%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s       | 1        | 1.96%   |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s    | 1        | 1.96%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s      | 1        | 1.96%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 1        | 1.96%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1333MT/s       | 1        | 1.96%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s       | 1        | 1.96%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 1639MT/s   | 1        | 1.96%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 2048MT/s      | 1        | 1.96%   |
| RZX RAM D3D10M1600B-8G 8GB DIMM DDR3 1600MT/s             | 1        | 1.96%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s       | 1        | 1.96%   |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s        | 1        | 1.96%   |
| OCZ RAM OCZ2N800SR2G 2048MB DIMM DDR 800MT/s              | 1        | 1.96%   |
| Kingston RAM Module 4096MB DIMM DDR3 1600MT/s             | 1        | 1.96%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 1.96%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 1.96%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s         | 1        | 1.96%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s    | 1        | 1.96%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1867MT/s    | 1        | 1.96%   |
| Kingston RAM K531R8-ETB 4096MB DIMM DDR3 1600MT/s         | 1        | 1.96%   |
| Kingston RAM CL16-16-16 D4-2400 8192MB DIMM DDR4 2134MT/s | 1        | 1.96%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 1.96%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s  | 1        | 1.96%   |
| Kingston RAM 9965525-026.A00LF 8192MB DIMM DDR3 1333MT/s  | 1        | 1.96%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s        | 1        | 1.96%   |
| G.Skill RAM F3-2133C9-8GTX 8GB DIMM DDR3 2133MT/s         | 1        | 1.96%   |
| G.Skill RAM F3-1333C9-4GSL 4096MB SODIMM DDR3 1333MT/s    | 1        | 1.96%   |
| Crucial RAM CT51264BA160BJ.C8 4GB DIMM DDR3 1600MT/s      | 1        | 1.96%   |
| Corsair RAM CMX8GX3M1A1333C9 8192MB DIMM DDR3 1333MT/s    | 1        | 1.96%   |
| Corsair RAM CMW16GX4M1Z3600C18 16384MB DIMM DDR4 3000MT/s | 1        | 1.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 1.96%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 2400MT/s  | 1        | 1.96%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s     | 1        | 1.96%   |
| Corsair RAM CM4X8GD3200C16K4 8192MB DIMM DDR4 2133MT/s    | 1        | 1.96%   |
| Corsair RAM CM4X16GC3000C16K4D 16384MB DIMM DDR4 3000MT/s | 1        | 1.96%   |
| Axiom RAM 51264Y133IHYN 4GB DIMM DDR3 1333MT/s            | 1        | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 14       | 34.15%  |
| DDR4    | 11       | 26.83%  |
| DDR2    | 6        | 14.63%  |
| Unknown | 5        | 12.2%   |
| SDRAM   | 3        | 7.32%   |
| DDR     | 2        | 4.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 97.56%  |
| SODIMM | 1        | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 29.55%  |
| 8192  | 12       | 27.27%  |
| 2048  | 10       | 22.73%  |
| 1024  | 4        | 9.09%   |
| 16384 | 3        | 6.82%   |
| 32768 | 1        | 2.27%   |
| 512   | 1        | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 24%     |
| 1333    | 9        | 18%     |
| 3000    | 4        | 8%      |
| 2400    | 3        | 6%      |
| 800     | 3        | 6%      |
| 49926   | 2        | 4%      |
| 3200    | 2        | 4%      |
| 2133    | 2        | 4%      |
| 667     | 2        | 4%      |
| 333     | 2        | 4%      |
| 3600    | 1        | 2%      |
| 3466    | 1        | 2%      |
| 2048    | 1        | 2%      |
| 1867    | 1        | 2%      |
| 1639    | 1        | 2%      |
| 533     | 1        | 2%      |
| 400     | 1        | 2%      |
| 200     | 1        | 2%      |
| Unknown | 1        | 2%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Seiko Epson    | 1        | 50%     |
| Konica Minolta | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Seiko Epson L380 Series | 1        | 50%     |
| Konica Minolta 206      | 1        | 50%     |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 4        | 57.14%  |
| Microsoft              | 1        | 14.29%  |
| Huawei Technologies    | 1        | 14.29%  |
| Generalplus Technology | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Logitech Webcam C200      | 2        | 28.57%  |
| Microsoft LifeCam HD-3000 | 1        | 14.29%  |
| Logitech Webcam Pro 9000  | 1        | 14.29%  |
| Logitech Webcam C270      | 1        | 14.29%  |
| Huawei UVC Camera         | 1        | 14.29%  |
| Generalplus 808 Camera    | 1        | 14.29%  |

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
| 0     | 40       | 95.24%  |
| 3     | 1        | 2.38%   |
| 1     | 1        | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 1        | 25%     |
| Multimedia controller | 1        | 25%     |
| Graphics card         | 1        | 25%     |
| Camera                | 1        | 25%     |

