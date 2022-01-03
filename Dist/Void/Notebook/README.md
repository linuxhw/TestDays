Void - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Void.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X751LD                      | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Acer          | Aspire E1-531               | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Acer          | Aspire E1-531               | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| Samsung       | 275E4E/275E5E               | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| Lenovo        | G50-45 80E3                 | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| HP            | Laptop 14-dk0xxx            | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| Acer          | Aspire SW5-015              | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| Dell          | Inspiron 11 - 3148          | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| Acer          | AO722                       | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| Acer          | Nitro AN715-51              | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| Acer          | AO722                       | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| Dell          | Inspiron 1501               | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Google        | Chell                       | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| Digibras      | NH4CU03                     | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| Positivo      | Mobile                      | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.13.19_1           | 4         | 7.55%   |
| 5.8.12_1            | 3         | 5.66%   |
| 5.3.9_1             | 3         | 5.66%   |
| 5.10.17_1           | 3         | 5.66%   |
| 5.8.18_1            | 2         | 3.77%   |
| 5.4.24_1            | 2         | 3.77%   |
| 5.13.13_1           | 2         | 3.77%   |
| 5.12.10_1           | 2         | 3.77%   |
| 5.9.16_1            | 1         | 1.89%   |
| 5.9.14_1            | 1         | 1.89%   |
| 5.9.0-rc8_2         | 1         | 1.89%   |
| 5.8.9_1             | 1         | 1.89%   |
| 5.8.8_1             | 1         | 1.89%   |
| 5.8.7_1             | 1         | 1.89%   |
| 5.8.6_1             | 1         | 1.89%   |
| 5.8.12_2            | 1         | 1.89%   |
| 5.7.16_1            | 1         | 1.89%   |
| 5.4.35_1            | 1         | 1.89%   |
| 5.4.21_1            | 1         | 1.89%   |
| 5.4.13_2            | 1         | 1.89%   |
| 5.2.13_1            | 1         | 1.89%   |
| 5.14.0_1            | 1         | 1.89%   |
| 5.13.18_1           | 1         | 1.89%   |
| 5.13.15_1           | 1         | 1.89%   |
| 5.13.12_1           | 1         | 1.89%   |
| 5.13.10_1           | 1         | 1.89%   |
| 5.12.7_1            | 1         | 1.89%   |
| 5.12.6              | 1         | 1.89%   |
| 5.12.3-tkg-MuQSS_22 | 1         | 1.89%   |
| 5.12.19_1           | 1         | 1.89%   |
| 5.12.14_1           | 1         | 1.89%   |
| 5.11.16_1           | 1         | 1.89%   |
| 5.10.9_1            | 1         | 1.89%   |
| 5.10.80_1           | 1         | 1.89%   |
| 5.10.46_1           | 1         | 1.89%   |
| 5.10.23_1           | 1         | 1.89%   |
| 5.1.17_1            | 1         | 1.89%   |
| 5.1.10_1            | 1         | 1.89%   |
| 4.4.177_1           | 1         | 1.89%   |
| 4.14.163_1          | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.8.12   | 4         | 7.55%   |
| 5.13.19  | 4         | 7.55%   |
| 5.3.9    | 3         | 5.66%   |
| 5.10.17  | 3         | 5.66%   |
| 5.8.18   | 2         | 3.77%   |
| 5.4.24   | 2         | 3.77%   |
| 5.13.13  | 2         | 3.77%   |
| 5.12.10  | 2         | 3.77%   |
| 5.9.16   | 1         | 1.89%   |
| 5.9.14   | 1         | 1.89%   |
| 5.9.0    | 1         | 1.89%   |
| 5.8.9    | 1         | 1.89%   |
| 5.8.8    | 1         | 1.89%   |
| 5.8.7    | 1         | 1.89%   |
| 5.8.6    | 1         | 1.89%   |
| 5.7.16   | 1         | 1.89%   |
| 5.4.35   | 1         | 1.89%   |
| 5.4.21   | 1         | 1.89%   |
| 5.4.13   | 1         | 1.89%   |
| 5.2.13   | 1         | 1.89%   |
| 5.14.0   | 1         | 1.89%   |
| 5.13.18  | 1         | 1.89%   |
| 5.13.15  | 1         | 1.89%   |
| 5.13.12  | 1         | 1.89%   |
| 5.13.10  | 1         | 1.89%   |
| 5.12.7   | 1         | 1.89%   |
| 5.12.6   | 1         | 1.89%   |
| 5.12.3   | 1         | 1.89%   |
| 5.12.19  | 1         | 1.89%   |
| 5.12.14  | 1         | 1.89%   |
| 5.11.16  | 1         | 1.89%   |
| 5.10.9   | 1         | 1.89%   |
| 5.10.80  | 1         | 1.89%   |
| 5.10.46  | 1         | 1.89%   |
| 5.10.23  | 1         | 1.89%   |
| 5.1.17   | 1         | 1.89%   |
| 5.1.10   | 1         | 1.89%   |
| 4.4.177  | 1         | 1.89%   |
| 4.14.163 | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.8     | 10        | 19.23%  |
| 5.13    | 10        | 19.23%  |
| 5.12    | 7         | 13.46%  |
| 5.10    | 7         | 13.46%  |
| 5.4     | 5         | 9.62%   |
| 5.9     | 3         | 5.77%   |
| 5.3     | 3         | 5.77%   |
| 5.7     | 1         | 1.92%   |
| 5.2     | 1         | 1.92%   |
| 5.14    | 1         | 1.92%   |
| 5.11    | 1         | 1.92%   |
| 5.1     | 1         | 1.92%   |
| 4.4     | 1         | 1.92%   |
| 4.14    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 45        | 91.84%  |
| i686    | 2         | 4.08%   |
| aarch64 | 2         | 4.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 46.15%  |
| MATE       | 6         | 11.54%  |
| KDE        | 6         | 11.54%  |
| XFCE       | 5         | 9.62%   |
| i3         | 4         | 7.69%   |
| GNOME      | 3         | 5.77%   |
| bspwm      | 2         | 3.85%   |
| X-Cinnamon | 1         | 1.92%   |
| Lumina     | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 36        | 72%     |
| Tty     | 7         | 14%     |
| Wayland | 5         | 10%     |
| Unknown | 2         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 98%     |
| SDDM    | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 30        | 58.82%  |
| Unknown | 6         | 11.76%  |
| en_GB   | 4         | 7.84%   |
| de_DE   | 2         | 3.92%   |
| ru_UA   | 1         | 1.96%   |
| ru_RU   | 1         | 1.96%   |
| pt_BR   | 1         | 1.96%   |
| nb_NO   | 1         | 1.96%   |
| es_DO   | 1         | 1.96%   |
| en_NZ   | 1         | 1.96%   |
| en_DK   | 1         | 1.96%   |
| en_CA   | 1         | 1.96%   |
| en_AU   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 28        | 56%     |
| BIOS | 22        | 44%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 30        | 60%     |
| Btrfs   | 11        | 22%     |
| Unknown | 4         | 8%      |
| Xfs     | 2         | 4%      |
| Zfs     | 1         | 2%      |
| F2fs    | 1         | 2%      |
| Ext3    | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 54.9%   |
| Unknown | 16        | 31.37%  |
| MBR     | 7         | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 89.8%   |
| Yes       | 5         | 10.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 75.51%  |
| Yes       | 12        | 24.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Acer                | 11        | 22.45%  |
| Lenovo              | 9         | 18.37%  |
| ASUSTek Computer    | 9         | 18.37%  |
| Dell                | 6         | 12.24%  |
| Hewlett-Packard     | 5         | 10.2%   |
| Samsung Electronics | 1         | 2.04%   |
| Positivo            | 1         | 2.04%   |
| Pine Microsystems   | 1         | 2.04%   |
| MSI                 | 1         | 2.04%   |
| Google              | 1         | 2.04%   |
| Getac               | 1         | 2.04%   |
| Digibras            | 1         | 2.04%   |
| Chuwi               | 1         | 2.04%   |
| Unknown             | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung 275E4E/275E5E                     | 1         | 2.04%   |
| Positivo Mobile                           | 1         | 2.04%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 2.04%   |
| MSI Bravo 15 A4DDR                        | 1         | 2.04%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 2.04%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 2.04%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 2.04%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 2.04%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 2.04%   |
| Lenovo ThinkPad T14 Gen 1 20UES1Y200      | 1         | 2.04%   |
| Lenovo IdeaPad Z570 10246ZG               | 1         | 2.04%   |
| Lenovo IdeaPad 710S-13IKB 80VQ            | 1         | 2.04%   |
| Lenovo G50-45 80E3                        | 1         | 2.04%   |
| HP Pavilion Notebook                      | 1         | 2.04%   |
| HP Laptop 15-bw0xx                        | 1         | 2.04%   |
| HP Laptop 14-dk0xxx                       | 1         | 2.04%   |
| HP Laptop 14-bs0xx                        | 1         | 2.04%   |
| HP 15                                     | 1         | 2.04%   |
| Google Chell                              | 1         | 2.04%   |
| Getac V110                                | 1         | 2.04%   |
| Digibras NH4CU03                          | 1         | 2.04%   |
| Dell Precision 3530                       | 1         | 2.04%   |
| Dell Latitude E4300                       | 1         | 2.04%   |
| Dell Inspiron 5555                        | 1         | 2.04%   |
| Dell Inspiron 1501                        | 1         | 2.04%   |
| Dell Inspiron 11 - 3148                   | 1         | 2.04%   |
| Dell G3 3579                              | 1         | 2.04%   |
| Chuwi GemiBook Pro                        | 1         | 2.04%   |
| ASUS X751LD                               | 1         | 2.04%   |
| ASUS X555UJ                               | 1         | 2.04%   |
| ASUS X510UAR                              | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X512FL_X512FL    | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA    | 1         | 2.04%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA   | 1         | 2.04%   |
| ASUS VivoBook 15_ASUS Laptop X540UB       | 1         | 2.04%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 2.04%   |
| ASUS ASUS TUF Gaming A15 FA506IV_TUF506IV | 1         | 2.04%   |
| Acer Swift SF314-42                       | 1         | 2.04%   |
| Acer Nitro AN715-51                       | 1         | 2.04%   |
| Acer Aspire SW5-015                       | 1         | 2.04%   |
| Acer Aspire E5-575G                       | 1         | 2.04%   |
| Acer Aspire E5-521                        | 1         | 2.04%   |
| Acer Aspire E1-570G                       | 1         | 2.04%   |
| Acer Aspire E1-531                        | 1         | 2.04%   |
| Acer Aspire A515-54G                      | 1         | 2.04%   |
| Acer Aspire A315-55G                      | 1         | 2.04%   |
| Acer AOA150                               | 1         | 2.04%   |
| Acer AO722                                | 1         | 2.04%   |
| Unknown                                   | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Acer Aspire              | 7         | 14.29%  |
| Lenovo ThinkPad          | 6         | 12.24%  |
| ASUS VivoBook            | 4         | 8.16%   |
| HP Laptop                | 3         | 6.12%   |
| Dell Inspiron            | 3         | 6.12%   |
| Lenovo IdeaPad           | 2         | 4.08%   |
| Samsung 275E4E           | 1         | 2.04%   |
| Positivo Mobile          | 1         | 2.04%   |
| Pine Microsystems Pine64 | 1         | 2.04%   |
| MSI Bravo                | 1         | 2.04%   |
| Lenovo G50-45            | 1         | 2.04%   |
| HP Pavilion              | 1         | 2.04%   |
| HP 15                    | 1         | 2.04%   |
| Google Chell             | 1         | 2.04%   |
| Getac V110               | 1         | 2.04%   |
| Digibras NH4CU03         | 1         | 2.04%   |
| Dell Precision           | 1         | 2.04%   |
| Dell Latitude            | 1         | 2.04%   |
| Dell G3                  | 1         | 2.04%   |
| Chuwi GemiBook           | 1         | 2.04%   |
| ASUS X751LD              | 1         | 2.04%   |
| ASUS X555UJ              | 1         | 2.04%   |
| ASUS X510UAR             | 1         | 2.04%   |
| ASUS TUF                 | 1         | 2.04%   |
| ASUS ASUS                | 1         | 2.04%   |
| Acer Swift               | 1         | 2.04%   |
| Acer Nitro               | 1         | 2.04%   |
| Acer AOA150              | 1         | 2.04%   |
| Acer AO722               | 1         | 2.04%   |
| Unknown                  | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 12        | 24.49%  |
| 2019    | 7         | 14.29%  |
| 2018    | 5         | 10.2%   |
| 2015    | 5         | 10.2%   |
| 2014    | 4         | 8.16%   |
| 2013    | 4         | 8.16%   |
| 2021    | 2         | 4.08%   |
| 2016    | 2         | 4.08%   |
| 2011    | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| 2012    | 1         | 2.04%   |
| 2009    | 1         | 2.04%   |
| 2008    | 1         | 2.04%   |
| 2007    | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 32%     |
| 3.01-4.0   | 14        | 28%     |
| 8.01-16.0  | 8         | 16%     |
| 16.01-24.0 | 6         | 12%     |
| 1.01-2.0   | 4         | 8%      |
| 32.01-64.0 | 2         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 20        | 37.74%  |
| 2.01-3.0  | 13        | 24.53%  |
| 0.51-1.0  | 10        | 18.87%  |
| 3.01-4.0  | 4         | 7.55%   |
| 4.01-8.0  | 3         | 5.66%   |
| 0.01-0.5  | 2         | 3.77%   |
| 8.01-16.0 | 1         | 1.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 77.55%  |
| 2      | 11        | 22.45%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 61.22%  |
| Yes       | 19        | 38.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 81.63%  |
| No        | 9         | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 93.88%  |
| No        | 3         | 6.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 79.59%  |
| No        | 10        | 20.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 9         | 18.37%  |
| India              | 5         | 10.2%   |
| Germany            | 5         | 10.2%   |
| Ukraine            | 4         | 8.16%   |
| Brazil             | 4         | 8.16%   |
| Russia             | 3         | 6.12%   |
| UK                 | 2         | 4.08%   |
| Switzerland        | 2         | 4.08%   |
| Bulgaria           | 2         | 4.08%   |
| Vietnam            | 1         | 2.04%   |
| Turkey             | 1         | 2.04%   |
| Peru               | 1         | 2.04%   |
| Norway             | 1         | 2.04%   |
| New Zealand        | 1         | 2.04%   |
| Netherlands        | 1         | 2.04%   |
| Greece             | 1         | 2.04%   |
| France             | 1         | 2.04%   |
| Ecuador            | 1         | 2.04%   |
| Dominican Republic | 1         | 2.04%   |
| Denmark            | 1         | 2.04%   |
| Canada             | 1         | 2.04%   |
| Australia          | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Zurich                  | 1         | 1.96%   |
| Yambol                  | 1         | 1.96%   |
| Vlaardingen             | 1         | 1.96%   |
| Viby                    | 1         | 1.96%   |
| Varna                   | 1         | 1.96%   |
| Uzhhorod                | 1         | 1.96%   |
| Trujillo                | 1         | 1.96%   |
| Toulouse                | 1         | 1.96%   |
| Toms River              | 1         | 1.96%   |
| Syktyvkar               | 1         | 1.96%   |
| St Petersburg           | 1         | 1.96%   |
| Schwabhausen            | 1         | 1.96%   |
| Saxtons River           | 1         | 1.96%   |
| Rostock                 | 1         | 1.96%   |
| Regensburg              | 1         | 1.96%   |
| Pune                    | 1         | 1.96%   |
| Porto Alegre            | 1         | 1.96%   |
| Phoenix                 | 1         | 1.96%   |
| Peckham                 | 1         | 1.96%   |
| Nagua                   | 1         | 1.96%   |
| Munich                  | 1         | 1.96%   |
| Mossoro                 | 1         | 1.96%   |
| Moscow                  | 1         | 1.96%   |
| Mesa                    | 1         | 1.96%   |
| Matos Costa             | 1         | 1.96%   |
| Malvern                 | 1         | 1.96%   |
| Los Angeles             | 1         | 1.96%   |
| London                  | 1         | 1.96%   |
| Lakewood                | 1         | 1.96%   |
| Krynychky               | 1         | 1.96%   |
| Kremenchug              | 1         | 1.96%   |
| Izmir                   | 1         | 1.96%   |
| Itanhaem                | 1         | 1.96%   |
| Ho Chi Minh City        | 1         | 1.96%   |
| Guayaquil               | 1         | 1.96%   |
| Geneva                  | 1         | 1.96%   |
| Ernakulam               | 1         | 1.96%   |
| Erlangen                | 1         | 1.96%   |
| Dublin                  | 1         | 1.96%   |
| Drammen                 | 1         | 1.96%   |
| Dnipropetrovsk          | 1         | 1.96%   |
| Delhi                   | 1         | 1.96%   |
| Chennai                 | 1         | 1.96%   |
| Champlain               | 1         | 1.96%   |
| Bengaluru               | 1         | 1.96%   |
| Azle                    | 1         | 1.96%   |
| Auckland                | 1         | 1.96%   |
| Athens                  | 1         | 1.96%   |
| Amsterdam               | 1         | 1.96%   |
| Alzenau in Unterfranken | 1         | 1.96%   |
| Albuquerque             | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 17.54%  |
| Seagate             | 10        | 11     | 17.54%  |
| Samsung Electronics | 9         | 10     | 15.79%  |
| Unknown             | 4         | 7      | 7.02%   |
| Toshiba             | 4         | 4      | 7.02%   |
| Intel               | 4         | 5      | 7.02%   |
| HGST                | 4         | 5      | 7.02%   |
| SanDisk             | 3         | 4      | 5.26%   |
| SK Hynix            | 2         | 2      | 3.51%   |
| Transcend           | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| Kingston            | 1         | 1      | 1.75%   |
| Hitachi             | 1         | 1      | 1.75%   |
| Crucial             | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| BHT                 | 1         | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 3         | 5%      |
| Toshiba MQ01ABF050 500GB                | 2         | 3.33%   |
| SK Hynix SKHynix_HFS001TD9TNI-L2B0B 1TB | 2         | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 3.33%   |
| Intel SSDPEKNW512G8 512GB               | 2         | 3.33%   |
| HGST HTS545050A7E680 500GB              | 2         | 3.33%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 1.67%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 1.67%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 1.67%   |
| WDC WD1600BEVS-60VAT0 160GB             | 1         | 1.67%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 1.67%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 1.67%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 1.67%   |
| WDC WD Elements 500GB                   | 1         | 1.67%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB      | 1         | 1.67%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 1.67%   |
| Unknown SD512  512MB                    | 1         | 1.67%   |
| Unknown SD16G  16GB                     | 1         | 1.67%   |
| Unknown MMC Card  8GB                   | 1         | 1.67%   |
| Unknown MMC Card  128GB                 | 1         | 1.67%   |
| Unknown MMC Card                        | 1         | 1.67%   |
| Unknown CWBC3R  64GB                    | 1         | 1.67%   |
| Transcend TS128GMTS800 128GB SSD        | 1         | 1.67%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.67%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 1         | 1.67%   |
| Seagate ST98823AS 80GB                  | 1         | 1.67%   |
| Seagate ST9750420AS 752GB               | 1         | 1.67%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.67%   |
| Seagate Expansion Desk 8TB              | 1         | 1.67%   |
| SanDisk SD9SN8W128G1102 128GB SSD       | 1         | 1.67%   |
| SanDisk SD8SN8U1T001122 1024GB SSD      | 1         | 1.67%   |
| Sandisk NVMe SSD Drive 512GB            | 1         | 1.67%   |
| Sandisk NVMe SSD Drive 500GB            | 1         | 1.67%   |
| Samsung SSD PM871 M.2 2280 512GB SED    | 1         | 1.67%   |
| Samsung SSD 970 PRO 1TB                 | 1         | 1.67%   |
| Samsung SSD 970 EVO Plus 250GB          | 1         | 1.67%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.67%   |
| Samsung SSD 850 EVO 500GB               | 1         | 1.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB  | 1         | 1.67%   |
| Samsung MZVLB1T0HBLR-000L7 1TB          | 1         | 1.67%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD    | 1         | 1.67%   |
| Samsung HM641JI 640GB                   | 1         | 1.67%   |
| Patriot Burst 120GB SSD                 | 1         | 1.67%   |
| Kingston NVMe SSD Drive 512GB           | 1         | 1.67%   |
| Intel SSDSC2KF256H6L 256GB              | 1         | 1.67%   |
| Intel SSDPEKNW010T8 1TB                 | 1         | 1.67%   |
| Hitachi HTS543216L9A300 160GB           | 1         | 1.67%   |
| HGST HTS541010B7E610 1TB                | 1         | 1.67%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.67%   |
| Crucial CT500MX500SSD1 500GB            | 1         | 1.67%   |
| China SSD 256GB                         | 1         | 1.67%   |
| BHT WR202I0064G E70290F5 64GB           | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 38.46%  |
| WDC                 | 7         | 7      | 26.92%  |
| HGST                | 4         | 5      | 15.38%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 33.33%  |
| SanDisk             | 2         | 2      | 16.67%  |
| Transcend           | 1         | 1      | 8.33%   |
| Patriot             | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| China               | 1         | 1      | 8.33%   |
| BHT                 | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 28     | 45.45%  |
| NVMe    | 13        | 18     | 23.64%  |
| SSD     | 12        | 12     | 21.82%  |
| MMC     | 4         | 7      | 7.27%   |
| Unknown | 1         | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 39     | 64.15%  |
| NVMe | 13        | 18     | 24.53%  |
| MMC  | 4         | 7      | 7.55%   |
| SAS  | 2         | 2      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 24     | 56.76%  |
| 0.51-1.0   | 14        | 14     | 37.84%  |
| 1.01-2.0   | 1         | 1      | 2.7%    |
| 4.01-10.0  | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 15        | 29.41%  |
| 501-1000       | 13        | 25.49%  |
| 101-250        | 8         | 15.69%  |
| Unknown        | 5         | 9.8%    |
| 51-100         | 3         | 5.88%   |
| 21-50          | 2         | 3.92%   |
| 1001-2000      | 2         | 3.92%   |
| 1-20           | 2         | 3.92%   |
| More than 3000 | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 27.45%  |
| 1-20           | 12        | 23.53%  |
| 21-50          | 10        | 19.61%  |
| 51-100         | 5         | 9.8%    |
| Unknown        | 5         | 9.8%    |
| 251-500        | 4         | 7.84%   |
| More than 3000 | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD1600BEVS-60VAT0 160GB         | 1         | 1      | 12.5%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 12.5%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 12.5%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 12.5%   |
| Hitachi HTS543216L9A300 160GB       | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 12.5%   |
| HGST HTS541010A9E680 1TB            | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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
| Works    | 27        | 32     | 48.21%  |
| Detected | 21        | 26     | 37.5%   |
| Malfunc  | 8         | 8      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 50.91%  |
| AMD                              | 15        | 27.27%  |
| Samsung Electronics              | 4         | 7.27%   |
| Sandisk                          | 3         | 5.45%   |
| SK Hynix                         | 2         | 3.64%   |
| Toshiba America Info Systems     | 1         | 1.82%   |
| Silicon Integrated Systems [SiS] | 1         | 1.82%   |
| Kingston Technology Company      | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 22.41%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 13.79%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 6.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 6.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 6.9%    |
| Intel SSD 660P Series                                                            | 3         | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 5.17%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 3.45%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 3.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.45%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.72%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.72%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.72%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.72%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.72%   |
| AMD SB600 IDE                                                                    | 1         | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 37        | 66.07%  |
| NVMe | 13        | 23.21%  |
| RAID | 3         | 5.36%   |
| IDE  | 3         | 5.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 61.22%  |
| AMD    | 17        | 34.69%  |
| ARM    | 2         | 4.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 4.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 4.08%   |
| ARM Processor                                 | 2         | 4.08%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 4.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 4.08%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.04%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 2.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.04%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz          | 1         | 2.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.04%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 2.04%   |
| Intel Celeron CPU 1005M @ 1.90GHz             | 1         | 2.04%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 1         | 2.04%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile Technology TL-50      | 1         | 2.04%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.04%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD E2-6110 APU with AMD Radeon R2 Graphics   | 1         | 2.04%   |
| AMD E1-1500 APU with Radeon HD Graphics       | 1         | 2.04%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 2.04%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.04%   |
| AMD A9-9410 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.04%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.04%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2.04%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 24.49%  |
| Intel Core i7           | 6         | 12.24%  |
| Intel Core i3           | 5         | 10.2%   |
| Other                   | 4         | 8.16%   |
| Intel Celeron           | 3         | 6.12%   |
| AMD Ryzen 7             | 3         | 6.12%   |
| AMD Ryzen 5             | 3         | 6.12%   |
| Intel Atom              | 2         | 4.08%   |
| AMD Ryzen 7 PRO         | 2         | 4.08%   |
| AMD A8                  | 2         | 4.08%   |
| Intel Genuine           | 1         | 2.04%   |
| Intel Core 2 Duo        | 1         | 2.04%   |
| AMD Turion 64 X2 Mobile | 1         | 2.04%   |
| AMD E2                  | 1         | 2.04%   |
| AMD E1                  | 1         | 2.04%   |
| AMD C-60                | 1         | 2.04%   |
| AMD A4                  | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 46.94%  |
| 4      | 17        | 34.69%  |
| 8      | 4         | 8.16%   |
| 6      | 3         | 6.12%   |
| 1      | 2         | 4.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 97.96%  |
| 2      | 1         | 2.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 61.22%  |
| 1      | 19        | 38.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 85.71%  |
| Unknown        | 4         | 8.16%   |
| 64-bit         | 2         | 4.08%   |
| 32-bit         | 1         | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 33.33%  |
| 0x40651    | 4         | 7.84%   |
| 0x806e9    | 3         | 5.88%   |
| 0x306a9    | 3         | 5.88%   |
| 0x906ea    | 2         | 3.92%   |
| 0x806ec    | 2         | 3.92%   |
| 0x406e3    | 2         | 3.92%   |
| 0x08600104 | 2         | 3.92%   |
| 0x08108102 | 2         | 3.92%   |
| 0x07030105 | 2         | 3.92%   |
| 0x05000119 | 2         | 3.92%   |
| 0x806eb    | 1         | 1.96%   |
| 0x806ea    | 1         | 1.96%   |
| 0x30678    | 1         | 1.96%   |
| 0x206a7    | 1         | 1.96%   |
| 0x106c2    | 1         | 1.96%   |
| 0x08600106 | 1         | 1.96%   |
| 0x08600102 | 1         | 1.96%   |
| 0x08101007 | 1         | 1.96%   |
| 0x07030104 | 1         | 1.96%   |
| 0x06006705 | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 24.49%  |
| Zen 2         | 5         | 10.2%   |
| Skylake       | 4         | 8.16%   |
| Haswell       | 4         | 8.16%   |
| Puma          | 3         | 6.12%   |
| IvyBridge     | 3         | 6.12%   |
| Excavator     | 3         | 6.12%   |
| Zen+          | 2         | 4.08%   |
| SandyBridge   | 2         | 4.08%   |
| Bobcat        | 2         | 4.08%   |
| Unknown       | 2         | 4.08%   |
| Zen           | 1         | 2.04%   |
| Silvermont    | 1         | 2.04%   |
| Penryn        | 1         | 2.04%   |
| K8 Hammer     | 1         | 2.04%   |
| Goldmont plus | 1         | 2.04%   |
| Core          | 1         | 2.04%   |
| Bonnell       | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 46.77%  |
| AMD                              | 17        | 27.42%  |
| Nvidia                           | 15        | 24.19%  |
| Silicon Integrated Systems [SiS] | 1         | 1.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                    | 5         | 7.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 6.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 6.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 4.62%   |
| Intel HD Graphics 620                                                         | 3         | 4.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 4.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 3         | 4.62%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 3.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.08%   |
| Intel UHD Graphics 620                                                        | 2         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 3.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 2         | 3.08%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 1.54%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.54%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                          | 1         | 1.54%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 1.54%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.54%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 1.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.54%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 6290]                                                 | 1         | 1.54%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                        | 1         | 1.54%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                       | 1         | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 1.54%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 1.54%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 32.65%  |
| Intel + Nvidia | 13        | 26.53%  |
| 1 x AMD        | 13        | 26.53%  |
| Other          | 2         | 4.08%   |
| 2 x AMD        | 2         | 4.08%   |
| AMD + Nvidia   | 2         | 4.08%   |
| 1 x SiS        | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 35        | 71.43%  |
| Proprietary | 11        | 22.45%  |
| Unknown     | 3         | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 63.46%  |
| 0.01-0.5   | 8         | 15.38%  |
| 0.51-1.0   | 5         | 9.62%   |
| 1.01-2.0   | 4         | 7.69%   |
| 5.01-6.0   | 1         | 1.92%   |
| 3.01-4.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 12        | 23.53%  |
| Chimei Innolux      | 10        | 19.61%  |
| LG Display          | 9         | 17.65%  |
| BOE                 | 6         | 11.76%  |
| Samsung Electronics | 2         | 3.92%   |
| PANDA               | 2         | 3.92%   |
| Hewlett-Packard     | 2         | 3.92%   |
| AOC                 | 2         | 3.92%   |
| STD                 | 1         | 1.96%   |
| Philips             | 1         | 1.96%   |
| LG Philips          | 1         | 1.96%   |
| Lenovo              | 1         | 1.96%   |
| CHR                 | 1         | 1.96%   |
| Apple               | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 5.77%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch         | 2         | 3.85%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                        | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SAM029D 1360x768                     | 1         | 1.92%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1         | 1.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.92%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 1         | 1.92%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 1.92%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch              | 1         | 1.92%   |
| CHR VGA DISPLAY CHRC378 1920x1080 880x500mm 39.8-inch                | 1         | 1.92%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch     | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 340x190mm 15.3-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch     | 1         | 1.92%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE06F1 1920x1080 344x194mm 15.5-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                | 1         | 1.92%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 1         | 1.92%   |
| BOE LCD Monitor BOE0618 1366x768 277x156mm 12.5-inch                 | 1         | 1.92%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO13EC 1366x768 344x193mm 15.5-inch        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 1.92%   |
| Apple Color LCD APPA010 1366x768 256x144mm 11.6-inch                 | 1         | 1.92%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 1         | 1.92%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 22        | 44.9%   |
| 1366x768 (WXGA)   | 17        | 34.69%  |
| 1920x1200 (WUXGA) | 2         | 4.08%   |
| 1600x900 (HD+)    | 2         | 4.08%   |
| 1280x800 (WXGA)   | 2         | 4.08%   |
| 2560x1440 (QHD)   | 1         | 2.04%   |
| 2160x1440         | 1         | 2.04%   |
| 1360x768          | 1         | 2.04%   |
| 1024x600          | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 24        | 47.06%  |
| 13      | 7         | 13.73%  |
| 14      | 6         | 11.76%  |
| 24      | 2         | 3.92%   |
| 23      | 2         | 3.92%   |
| 12      | 2         | 3.92%   |
| 11      | 2         | 3.92%   |
| 39      | 1         | 1.96%   |
| 33      | 1         | 1.96%   |
| 18      | 1         | 1.96%   |
| 17      | 1         | 1.96%   |
| 8       | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 64.71%  |
| 201-300     | 8         | 15.69%  |
| 501-600     | 4         | 7.84%   |
| 801-900     | 1         | 1.96%   |
| 701-800     | 1         | 1.96%   |
| 401-500     | 1         | 1.96%   |
| 351-400     | 1         | 1.96%   |
| 101-200     | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 87.23%  |
| 16/10 | 5         | 10.64%  |
| 3/2   | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 46.15%  |
| 81-90          | 11        | 21.15%  |
| 71-80          | 3         | 5.77%   |
| 61-70          | 2         | 3.85%   |
| 51-60          | 2         | 3.85%   |
| 251-300        | 2         | 3.85%   |
| 201-250        | 2         | 3.85%   |
| 351-500        | 1         | 1.92%   |
| 1-40           | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |
| 131-140        | 1         | 1.92%   |
| 501-1000       | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 43.14%  |
| 101-120 | 15        | 29.41%  |
| 51-100  | 9         | 17.65%  |
| 161-240 | 4         | 7.84%   |
| Unknown | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 77.55%  |
| 2     | 9         | 18.37%  |
| 0     | 2         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 36.23%  |
| Intel                            | 18        | 26.09%  |
| Qualcomm Atheros                 | 13        | 18.84%  |
| Broadcom                         | 5         | 7.25%   |
| Cypress Semiconductor            | 2         | 2.9%    |
| TP-Link                          | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] | 1         | 1.45%   |
| Sierra Wireless                  | 1         | 1.45%   |
| Ralink Technology                | 1         | 1.45%   |
| Ralink                           | 1         | 1.45%   |
| Broadcom Limited                 | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 19.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 6.82%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 6.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 4.55%   |
| Intel Wireless 8265 / 8275                                        | 4         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 3.41%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.27%   |
| Cypress K38231_03                                                 | 2         | 2.27%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 1.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.14%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.14%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.14%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.14%   |
| Intel Wireless-AC 9260                                            | 1         | 1.14%   |
| Intel Wireless 8260                                               | 1         | 1.14%   |
| Intel Wireless 7260                                               | 1         | 1.14%   |
| Intel WiFi Link 5100                                              | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.14%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.14%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.14%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.14%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 37.5%   |
| Qualcomm Atheros      | 12        | 25%     |
| Realtek Semiconductor | 11        | 22.92%  |
| Broadcom              | 3         | 6.25%   |
| Sierra Wireless       | 1         | 2.08%   |
| Ralink Technology     | 1         | 2.08%   |
| Ralink                | 1         | 2.08%   |
| Broadcom Limited      | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 6         | 12.5%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 8.33%   |
| Intel Wireless 8265 / 8275                                 | 4         | 8.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 3         | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 3         | 6.25%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 4.17%   |
| Sierra Wireless EM7305 Modem                               | 1         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 2.08%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter   | 1         | 2.08%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.08%   |
| Intel Wireless-AC 9260                                     | 1         | 2.08%   |
| Intel Wireless 8260                                        | 1         | 2.08%   |
| Intel Wireless 7260                                        | 1         | 2.08%   |
| Intel WiFi Link 5100                                       | 1         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 2.08%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.08%   |
| Broadcom BCM4311 802.11b/g WLAN                            | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 60%     |
| Intel                            | 7         | 17.5%   |
| Broadcom                         | 3         | 7.5%    |
| Qualcomm Atheros                 | 2         | 5%      |
| Cypress Semiconductor            | 2         | 5%      |
| TP-Link                          | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 42.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 15%     |
| Cypress K38231_03                                                 | 2         | 5%      |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.5%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 53.49%  |
| Ethernet | 40        | 46.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 60.27%  |
| Ethernet | 29        | 39.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 67.35%  |
| 1     | 12        | 24.49%  |
| 0     | 3         | 6.12%   |
| 3     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 88.24%  |
| Yes  | 6         | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 40%     |
| Realtek Semiconductor           | 7         | 17.5%   |
| Lite-On Technology              | 5         | 12.5%   |
| Qualcomm Atheros Communications | 3         | 7.5%    |
| IMC Networks                    | 3         | 7.5%    |
| Foxconn / Hon Hai               | 2         | 5%      |
| Broadcom                        | 2         | 5%      |
| Dell                            | 1         | 2.5%    |
| Cambridge Silicon Radio         | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 15%     |
| Intel AX200 Bluetooth                               | 6         | 15%     |
| Realtek Bluetooth Radio                             | 4         | 10%     |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 7.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5%      |
| IMC Networks Bluetooth Radio                        | 2         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.5%    |
| Intel AX201 Bluetooth                               | 1         | 2.5%    |
| IMC Networks Bluetooth Device                       | 1         | 2.5%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 2.5%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.5%    |
| Dell Wireless 365 Bluetooth                         | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 28        | 51.85%  |
| AMD                              | 17        | 31.48%  |
| Nvidia                           | 5         | 9.26%   |
| Texas Instruments                | 2         | 3.7%    |
| Silicon Integrated Systems [SiS] | 1         | 1.85%   |
| Creative Technology              | 1         | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 12.33%  |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 8         | 10.96%  |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5.48%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 5.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 5.48%   |
| AMD FCH Azalia Controller                                                  | 4         | 5.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 4.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 4.11%   |
| AMD High Definition Audio Controller                                       | 3         | 4.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 4.11%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 2.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.74%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.74%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.37%   |
| Creative Technology Sound Blaster Play! 3                                  | 1         | 1.37%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 13        | 30.23%  |
| Samsung Electronics | 13        | 30.23%  |
| Micron Technology   | 7         | 16.28%  |
| Kingston            | 3         | 6.98%   |
| A-DATA Technology   | 3         | 6.98%   |
| Unknown             | 1         | 2.33%   |
| Transcend           | 1         | 2.33%   |
| Elpida              | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 4.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 4.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 4.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 4.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 2.17%   |
| Transcend RAM TS512MSK64W6H 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.17%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 2.17%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.17%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.17%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.17%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 2.17%   |
| SK Hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.17%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 2.17%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB SODIMM DDR4 3200MT/s    | 1         | 2.17%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s    | 1         | 2.17%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 2.17%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.17%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 2.17%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 2.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.17%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 2.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 2.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 2.17%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s       | 1         | 2.17%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.17%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s     | 1         | 2.17%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s      | 1         | 2.17%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s      | 1         | 2.17%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s         | 1         | 2.17%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.17%   |
| Kingston RAM Module 1024MB SODIMM DDR2 533MT/s               | 1         | 2.17%   |
| Kingston RAM ACR26D4S9S1KA-4 4GB SODIMM DDR4 2667MT/s        | 1         | 2.17%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s       | 1         | 2.17%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 1         | 2.17%   |
| Elpida RAM BA92-09550A 2GB SODIMM DDR3 1600MT/s              | 1         | 2.17%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s      | 1         | 2.17%   |
| A-DATA RAM AO1P21FC4R1-B2MS 4GB SODIMM DDR4 2133MT/s         | 1         | 2.17%   |
| A-DATA RAM AM1U16BC4P2-B19B 4GB SODIMM DDR3 1600MT/s         | 1         | 2.17%   |
| A-DATA RAM AM1L16BC4R1-B1GS 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 45.71%  |
| DDR3   | 15        | 42.86%  |
| LPDDR4 | 2         | 5.71%   |
| LPDDR3 | 1         | 2.86%   |
| DDR2   | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 97.06%  |
| Row Of Chips | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 16        | 42.11%  |
| 8192  | 14        | 36.84%  |
| 16384 | 3         | 7.89%   |
| 2048  | 3         | 7.89%   |
| 1024  | 1         | 2.63%   |
| 512   | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 35.14%  |
| 2667  | 9         | 24.32%  |
| 3200  | 4         | 10.81%  |
| 1334  | 3         | 8.11%   |
| 2400  | 2         | 5.41%   |
| 2133  | 2         | 5.41%   |
| 3733  | 1         | 2.7%    |
| 1867  | 1         | 2.7%    |
| 1333  | 1         | 2.7%    |
| 533   | 1         | 2.7%    |

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
| Chicony Electronics                    | 12        | 26.67%  |
| IMC Networks                           | 9         | 20%     |
| Microdia                               | 6         | 13.33%  |
| Realtek Semiconductor                  | 4         | 8.89%   |
| Quanta                                 | 4         | 8.89%   |
| Acer                                   | 4         | 8.89%   |
| Sunplus Innovation Technology          | 3         | 6.67%   |
| Silicon Motion                         | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 8.7%    |
| Chicony Integrated Camera                     | 3         | 6.52%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 4.35%   |
| Quanta HD User Facing                         | 2         | 4.35%   |
| Microdia HP Integrated Webcam                 | 2         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 4.35%   |
| Chicony HD WebCam                             | 2         | 4.35%   |
| Sunplus HP Wide Vision HD                     | 1         | 2.17%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 2.17%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 2.17%   |
| Realtek USB Camera                            | 1         | 2.17%   |
| Realtek Integrated Webcam HD                  | 1         | 2.17%   |
| Realtek HD WebCam                             | 1         | 2.17%   |
| Quanta VGA WebCam                             | 1         | 2.17%   |
| Quanta HP TrueVision HD Camera                | 1         | 2.17%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 2.17%   |
| Microdia Integrated_Webcam_HD                 | 1         | 2.17%   |
| Microdia Integrated_Webcam_2M                 | 1         | 2.17%   |
| Microdia HD Webcam USB                        | 1         | 2.17%   |
| Logitech C505 HD Webcam                       | 1         | 2.17%   |
| IMC Networks VGA UVC WebCam                   | 1         | 2.17%   |
| IMC Networks HP TrueVision HD Camera          | 1         | 2.17%   |
| IMC Networks EasyCamera                       | 1         | 2.17%   |
| Chicony WebCam                                | 1         | 2.17%   |
| Chicony USB 5M WebCam                         | 1         | 2.17%   |
| Chicony USB 2.0 Camera                        | 1         | 2.17%   |
| Chicony thinkpad t430s camera                 | 1         | 2.17%   |
| Chicony Lenovo EasyCamera                     | 1         | 2.17%   |
| Chicony HP TrueVision HD Camera               | 1         | 2.17%   |
| Chicony HD WebCam (Acer)                      | 1         | 2.17%   |
| Chicony HD User Facing                        | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.17%   |
| Acer ThinkPad P50 Integrated Camera           | 1         | 2.17%   |
| Acer SunplusIT Integrated Camera              | 1         | 2.17%   |
| Acer OrbiCam                                  | 1         | 2.17%   |
| Acer Lenovo EasyCamera                        | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Synaptics        | 4         | 80%     |
| Validity Sensors | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 60%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 76%     |
| 1     | 9         | 18%     |
| 2     | 2         | 4%      |
| 3     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 33.33%  |
| Net/wireless          | 3         | 20%     |
| Chipcard              | 3         | 20%     |
| Graphics card         | 2         | 13.33%  |
| Net/ethernet          | 1         | 6.67%   |
| Multimedia controller | 1         | 6.67%   |

