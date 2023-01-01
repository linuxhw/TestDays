RHEL 8 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for RHEL 8.

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

Total: 88

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z590I VISION D              | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| HP            | 8591                        | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Gigabyte      | Z590I VISION D              | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Dell          | 02K9CR A03                  | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| ASRock        | X99E-ITX/ac                 | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| ASRock        | X570 Steel Legend           | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Gigabyte      | B150-HD3-CF                 | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Gigabyte      | Z97N-WIFI                   | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | PRIME B360M-D               | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Lenovo        | MAHOBAY                     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| ASUSTek       | PRIME B350M-A               | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| ASUSTek       | Z87-DELUXE                  | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| HP            | 212B                        | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte      | Z97N-WIFI                   | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo        | MAHOBAY                     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek       | PRIME B350M-A               | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte      | 970A-D3                     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Gigabyte      | Z490 GAMING X               | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell          | 0MWYPT A02                  | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Intel         | DX79SR AAG57199-200         | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| HP            | 1906                        | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| HP            | 2129                        | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| HP            | 8054                        | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| ASUSTek       | PRIME B360M-D               | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| ASRock        | A300M-STX                   | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell          | 0NNNCT A01                  | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASRock        | H270 Pro4                   | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Unknown       | SKYBAY                      | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| HP            | 1905                        | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| Dell          | 082WXT A01                  | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| Dell          | 082WXT A01                  | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| MSI           | H310M PRO-VD                | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| HP            | 1905                        | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek       | Z10PE-D16 WS                | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP            | 1905                        | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| HP            | 843F                        | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| HP            | 843F                        | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASRockRack    | EP2C612 WS                  | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Gigabyte      | B75-D3V                     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Alienware     | 0VDT73 A00                  | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| MSI           | B350M MORTAR                | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Dell          | 0XR1GT A00                  | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| MSI           | B350M MORTAR                | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Supermicro    | X7DWN+                      | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 10.45%  |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 8.96%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 5.97%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 5.97%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 5.97%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 4.48%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 4.48%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 4.48%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 4.48%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 2.99%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 2.99%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 2.99%   |
| 4.18.0-193.el8.x86_64        | 2        | 2.99%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 2.99%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 2.99%   |
| 4.18.0-147.el8.x86_64        | 2        | 2.99%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.49%   |
| 4.19.150                     | 1        | 1.49%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.49%   |
| 4.18.0-425.3.1.el8.x86_64    | 1        | 1.49%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 1.49%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 1        | 1.49%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1        | 1.49%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.49%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.49%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.49%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.49%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.49%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.49%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.49%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1        | 1.49%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 51       | 96.23%  |
| 5.10.6   | 1        | 1.89%   |
| 4.19.150 | 1        | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 51       | 96.23%  |
| 5.10    | 1        | 1.89%   |
| 4.19    | 1        | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 53       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 44       | 78.57%  |
| Unknown       | 4        | 7.14%   |
| GNOME Classic | 3        | 5.36%   |
| KDE5          | 2        | 3.57%   |
| KDE           | 2        | 3.57%   |
| MATE          | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 31       | 55.36%  |
| Wayland | 24       | 42.86%  |
| Unknown | 1        | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 71.43%  |
| GDM     | 15       | 26.79%  |
| LightDM | 1        | 1.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 33       | 61.11%  |
| Unknown | 3        | 5.56%   |
| ru_RU   | 2        | 3.7%    |
| pl_PL   | 2        | 3.7%    |
| es_AR   | 2        | 3.7%    |
| en_IN   | 2        | 3.7%    |
| en_GB   | 2        | 3.7%    |
| de_DE   | 2        | 3.7%    |
| sl_SI   | 1        | 1.85%   |
| ko_KR   | 1        | 1.85%   |
| es_MX   | 1        | 1.85%   |
| es_ES   | 1        | 1.85%   |
| en_NZ   | 1        | 1.85%   |
| cs_CZ   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 38       | 70.37%  |
| BIOS | 16       | 29.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 49       | 90.74%  |
| Ext4    | 3        | 5.56%   |
| Unknown | 2        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 64.29%  |
| GPT     | 16       | 28.57%  |
| MBR     | 4        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 88.89%  |
| Yes       | 6        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 87.04%  |
| Yes       | 7        | 12.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 22.64%  |
| Hewlett-Packard     | 9        | 16.98%  |
| Gigabyte Technology | 8        | 15.09%  |
| Dell                | 6        | 11.32%  |
| ASRock              | 5        | 9.43%   |
| MSI                 | 4        | 7.55%   |
| Lenovo              | 4        | 7.55%   |
| Supermicro          | 1        | 1.89%   |
| Intel               | 1        | 1.89%   |
| CX / Air Computers. | 1        | 1.89%   |
| Alienware           | 1        | 1.89%   |
| Unknown             | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 7.55%   |
| Supermicro X7DW3                    | 1        | 1.89%   |
| MSI MS-7B51                         | 1        | 1.89%   |
| MSI MS-7B33                         | 1        | 1.89%   |
| MSI MS-7A37                         | 1        | 1.89%   |
| MSI MS-7752                         | 1        | 1.89%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.89%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.89%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.89%   |
| Lenovo 10SFS03200                   | 1        | 1.89%   |
| Intel DX79SR AAG57199-200           | 1        | 1.89%   |
| HP Z840 Workstation                 | 1        | 1.89%   |
| HP Z620 Workstation                 | 1        | 1.89%   |
| HP Z440 Workstation                 | 1        | 1.89%   |
| HP Z230 Tower Workstation           | 1        | 1.89%   |
| HP Z230 SFF Workstation             | 1        | 1.89%   |
| HP Z1 Entry Tower G5                | 1        | 1.89%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.89%   |
| HP 290 G1 SFF Business PC           | 1        | 1.89%   |
| HP 260-P020il                       | 1        | 1.89%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.89%   |
| Gigabyte Z590I VISION D             | 1        | 1.89%   |
| Gigabyte Z490 GAMING X              | 1        | 1.89%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.89%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.89%   |
| Gigabyte B75-D3V                    | 1        | 1.89%   |
| Gigabyte B150-HD3                   | 1        | 1.89%   |
| Gigabyte 970A-D3                    | 1        | 1.89%   |
| Dell Vostro 270                     | 1        | 1.89%   |
| Dell Precision Tower 3620           | 1        | 1.89%   |
| Dell Precision Tower 3420           | 1        | 1.89%   |
| Dell Precision T7600                | 1        | 1.89%   |
| Dell Precision 3630 Tower           | 1        | 1.89%   |
| Dell OptiPlex 9020                  | 1        | 1.89%   |
| CX / Air Computers. H87-M1          | 1        | 1.89%   |
| ASUS Z10PE-D16 WS                   | 1        | 1.89%   |
| ASUS ROG STRIX B350-F GAMING        | 1        | 1.89%   |
| ASUS ROG Maximus X HERO             | 1        | 1.89%   |
| ASUS Pro WS X570-ACE                | 1        | 1.89%   |
| ASUS PRIME X470-PRO                 | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell Precision             | 4        | 7.55%   |
| ASUS All                   | 4        | 7.55%   |
| Lenovo ThinkCentre         | 3        | 5.66%   |
| ASUS PRIME                 | 3        | 5.66%   |
| HP Z230                    | 2        | 3.77%   |
| ASUS ROG                   | 2        | 3.77%   |
| Supermicro X7DW3           | 1        | 1.89%   |
| MSI MS-7B51                | 1        | 1.89%   |
| MSI MS-7B33                | 1        | 1.89%   |
| MSI MS-7A37                | 1        | 1.89%   |
| MSI MS-7752                | 1        | 1.89%   |
| Lenovo 10SFS03200          | 1        | 1.89%   |
| Intel DX79SR               | 1        | 1.89%   |
| HP Z840                    | 1        | 1.89%   |
| HP Z620                    | 1        | 1.89%   |
| HP Z440                    | 1        | 1.89%   |
| HP Z1                      | 1        | 1.89%   |
| HP EliteDesk               | 1        | 1.89%   |
| HP 290                     | 1        | 1.89%   |
| HP 260-P020il              | 1        | 1.89%   |
| Gigabyte Z97N-WIFI         | 1        | 1.89%   |
| Gigabyte Z590I             | 1        | 1.89%   |
| Gigabyte Z490              | 1        | 1.89%   |
| Gigabyte Z390              | 1        | 1.89%   |
| Gigabyte B85M-D3V-A        | 1        | 1.89%   |
| Gigabyte B75-D3V           | 1        | 1.89%   |
| Gigabyte B150-HD3          | 1        | 1.89%   |
| Gigabyte 970A-D3           | 1        | 1.89%   |
| Dell Vostro                | 1        | 1.89%   |
| Dell OptiPlex              | 1        | 1.89%   |
| CX / Air Computers. H87-M1 | 1        | 1.89%   |
| ASUS Z10PE-D16             | 1        | 1.89%   |
| ASUS Pro                   | 1        | 1.89%   |
| ASUS P8Z77-V               | 1        | 1.89%   |
| ASRock X99E-ITX            | 1        | 1.89%   |
| ASRock X570                | 1        | 1.89%   |
| ASRock H91M-PLUS           | 1        | 1.89%   |
| ASRock H270                | 1        | 1.89%   |
| ASRock A300M-STX           | 1        | 1.89%   |
| Alienware Aurora           | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 18.87%  |
| 2017 | 7        | 13.21%  |
| 2012 | 7        | 13.21%  |
| 2019 | 6        | 11.32%  |
| 2015 | 6        | 11.32%  |
| 2013 | 5        | 9.43%   |
| 2016 | 4        | 7.55%   |
| 2020 | 3        | 5.66%   |
| 2021 | 2        | 3.77%   |
| 2014 | 1        | 1.89%   |
| 2011 | 1        | 1.89%   |
| 2009 | 1        | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 49       | 90.74%  |
| Enabled  | 5        | 9.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 15       | 26.79%  |
| 32.01-64.0  | 11       | 19.64%  |
| 16.01-24.0  | 10       | 17.86%  |
| 4.01-8.0    | 8        | 14.29%  |
| 8.01-16.0   | 7        | 12.5%   |
| 24.01-32.0  | 5        | 8.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 18       | 28.57%  |
| 2.01-3.0  | 18       | 28.57%  |
| 8.01-16.0 | 12       | 19.05%  |
| 3.01-4.0  | 10       | 15.87%  |
| 1.01-2.0  | 5        | 7.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 37.93%  |
| 1      | 15       | 25.86%  |
| 3      | 10       | 17.24%  |
| 4      | 5        | 8.62%   |
| 5      | 3        | 5.17%   |
| 8      | 2        | 3.45%   |
| 6      | 1        | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 53.7%   |
| Yes       | 25       | 46.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 52.83%  |
| No        | 25       | 47.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 56.6%   |
| Yes       | 23       | 43.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 9        | 16.98%  |
| Czechia      | 5        | 9.43%   |
| UK           | 4        | 7.55%   |
| Germany      | 3        | 5.66%   |
| Canada       | 3        | 5.66%   |
| Ukraine      | 2        | 3.77%   |
| South Korea  | 2        | 3.77%   |
| Russia       | 2        | 3.77%   |
| Poland       | 2        | 3.77%   |
| Italy        | 2        | 3.77%   |
| India        | 2        | 3.77%   |
| Argentina    | 2        | 3.77%   |
| Turkmenistan | 1        | 1.89%   |
| Switzerland  | 1        | 1.89%   |
| Sweden       | 1        | 1.89%   |
| Spain        | 1        | 1.89%   |
| Slovenia     | 1        | 1.89%   |
| New Zealand  | 1        | 1.89%   |
| Netherlands  | 1        | 1.89%   |
| Mexico       | 1        | 1.89%   |
| Lithuania    | 1        | 1.89%   |
| Indonesia    | 1        | 1.89%   |
| Finland      | 1        | 1.89%   |
| Egypt        | 1        | 1.89%   |
| China        | 1        | 1.89%   |
| Brazil       | 1        | 1.89%   |
| Belarus      | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Prague                | 4        | 7.14%   |
| Kyiv                  | 2        | 3.57%   |
| Yongin-si             | 1        | 1.79%   |
| Wiesbaden             | 1        | 1.79%   |
| Vaglio                | 1        | 1.79%   |
| Turku                 | 1        | 1.79%   |
| Toronto               | 1        | 1.79%   |
| Tiruchi               | 1        | 1.79%   |
| Tauranga              | 1        | 1.79%   |
| Spokane               | 1        | 1.79%   |
| Šiauliai             | 1        | 1.79%   |
| Saratov               | 1        | 1.79%   |
| San Jose              | 1        | 1.79%   |
| San Fernando          | 1        | 1.79%   |
| Salvador              | 1        | 1.79%   |
| Saltillo              | 1        | 1.79%   |
| Rosario               | 1        | 1.79%   |
| Reading               | 1        | 1.79%   |
| Pernis                | 1        | 1.79%   |
| Paracuellos de Jarama | 1        | 1.79%   |
| Musselburgh           | 1        | 1.79%   |
| Montreal              | 1        | 1.79%   |
| Mississauga           | 1        | 1.79%   |
| Minsk                 | 1        | 1.79%   |
| Milwaukee             | 1        | 1.79%   |
| Milan                 | 1        | 1.79%   |
| Lodz                  | 1        | 1.79%   |
| Ljutomer              | 1        | 1.79%   |
| Langfang              | 1        | 1.79%   |
| Kielce                | 1        | 1.79%   |
| Inowlodz              | 1        | 1.79%   |
| Huddersfield          | 1        | 1.79%   |
| Holly Springs         | 1        | 1.79%   |
| Gyami                 | 1        | 1.79%   |
| Gothenburg            | 1        | 1.79%   |
| Gangnam-gu            | 1        | 1.79%   |
| Dobrany               | 1        | 1.79%   |
| Dimitrovgrad          | 1        | 1.79%   |
| Didcot                | 1        | 1.79%   |
| Des Moines            | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 41     | 18.18%  |
| Seagate             | 15       | 26     | 13.64%  |
| Samsung Electronics | 14       | 28     | 12.73%  |
| Kingston            | 8        | 12     | 7.27%   |
| Toshiba             | 7        | 10     | 6.36%   |
| SanDisk             | 4        | 10     | 3.64%   |
| Crucial             | 4        | 7      | 3.64%   |
| A-DATA Technology   | 4        | 4      | 3.64%   |
| SK hynix            | 3        | 4      | 2.73%   |
| Phison              | 3        | 7      | 2.73%   |
| Micron Technology   | 3        | 3      | 2.73%   |
| Intel               | 3        | 5      | 2.73%   |
| Hitachi             | 3        | 3      | 2.73%   |
| PNY                 | 2        | 2      | 1.82%   |
| Gigabyte Technology | 2        | 3      | 1.82%   |
| Corsair             | 2        | 5      | 1.82%   |
| XPG                 | 1        | 1      | 0.91%   |
| Western Digital     | 1        | 1      | 0.91%   |
| Unknown             | 1        | 1      | 0.91%   |
| T-FORCE             | 1        | 2      | 0.91%   |
| Silicon Motion      | 1        | 1      | 0.91%   |
| OCZ                 | 1        | 2      | 0.91%   |
| KingFast            | 1        | 1      | 0.91%   |
| KINGBANK            | 1        | 1      | 0.91%   |
| HPT                 | 1        | 1      | 0.91%   |
| Hoodisk             | 1        | 1      | 0.91%   |
| HGST                | 1        | 1      | 0.91%   |
| Hewlett-Packard     | 1        | 1      | 0.91%   |
| China               | 1        | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB              | 3        | 2.27%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2        | 1.52%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2        | 1.52%   |
| Toshiba NVMe SSD Drive 256GB         | 2        | 1.52%   |
| Toshiba DT01ACA200 2TB               | 2        | 1.52%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 1.52%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 1.52%   |
| Seagate ST1000DM003-9YN162 1TB       | 2        | 1.52%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 1.52%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.52%   |
| Kingston SUV500120G 120GB SSD        | 2        | 1.52%   |
| Corsair Force LE SSD 240GB           | 2        | 1.52%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.76%   |
| Western Digital NVMe SSD Drive 960GB | 1        | 0.76%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.76%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1        | 0.76%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.76%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1        | 0.76%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1        | 0.76%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1        | 0.76%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1        | 0.76%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.76%   |
| WDC WD50 00LPVX-00V0TT0 500GB        | 1        | 0.76%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 0.76%   |
| WDC WD40EZRZ-19GXCB0 4TB             | 1        | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.76%   |
| WDC WD4005FZBX-00K5WB0 4TB           | 1        | 0.76%   |
| WDC WD2500BEKT-75F3T0 250GB          | 1        | 0.76%   |
| WDC WD2500AAKX-083CA1 250GB          | 1        | 0.76%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 1        | 0.76%   |
| WDC WD20EARS-22MVWB0 2TB             | 1        | 0.76%   |
| WDC WD2005FBYZ-01YCBB3 2TB           | 1        | 0.76%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1        | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1        | 0.76%   |
| WDC WD10EZEX-75WN4A0 1TB             | 1        | 0.76%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.76%   |
| Unknown SD/MMC/MS PRO 64GB           | 1        | 0.76%   |
| Toshiba HDWT140 4TB                  | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 37     | 40%     |
| Seagate             | 15       | 26     | 33.33%  |
| Toshiba             | 5        | 7      | 11.11%  |
| Hitachi             | 3        | 3      | 6.67%   |
| Unknown             | 1        | 1      | 2.22%   |
| Samsung Electronics | 1        | 2      | 2.22%   |
| HGST                | 1        | 1      | 2.22%   |
| Hewlett-Packard     | 1        | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 16     | 22.73%  |
| Kingston            | 8        | 12     | 18.18%  |
| Crucial             | 4        | 7      | 9.09%   |
| WDC                 | 3        | 4      | 6.82%   |
| Micron Technology   | 3        | 3      | 6.82%   |
| A-DATA Technology   | 3        | 3      | 6.82%   |
| SanDisk             | 2        | 7      | 4.55%   |
| PNY                 | 2        | 2      | 4.55%   |
| Intel               | 2        | 3      | 4.55%   |
| Corsair             | 2        | 5      | 4.55%   |
| SK hynix            | 1        | 2      | 2.27%   |
| OCZ                 | 1        | 2      | 2.27%   |
| KINGBANK            | 1        | 1      | 2.27%   |
| Hoodisk             | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 38       | 69     | 40.86%  |
| HDD     | 36       | 78     | 38.71%  |
| NVMe    | 16       | 34     | 17.2%   |
| Unknown | 3        | 4      | 3.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 140    | 70%     |
| NVMe | 16       | 34     | 22.86%  |
| SAS  | 5        | 11     | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 72     | 42.17%  |
| 0.51-1.0   | 26       | 42     | 31.33%  |
| 1.01-2.0   | 13       | 16     | 15.66%  |
| 3.01-4.0   | 6        | 11     | 7.23%   |
| 4.01-10.0  | 2        | 5      | 2.41%   |
| 2.01-3.0   | 1        | 1      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 20.69%  |
| 501-1000       | 12       | 20.69%  |
| More than 3000 | 11       | 18.97%  |
| 251-500        | 8        | 13.79%  |
| 1001-2000      | 8        | 13.79%  |
| 2001-3000      | 4        | 6.9%    |
| 51-100         | 2        | 3.45%   |
| Unknown        | 1        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 14       | 21.88%  |
| 101-250        | 11       | 17.19%  |
| 1-20           | 11       | 17.19%  |
| 51-100         | 9        | 14.06%  |
| 1001-2000      | 5        | 7.81%   |
| 251-500        | 4        | 6.25%   |
| 501-1000       | 4        | 6.25%   |
| More than 3000 | 3        | 4.69%   |
| 2001-3000      | 2        | 3.13%   |
| Unknown        | 1        | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 25%     |
| Micron Technology M510_2.5 7MM 256GB SSD | 1        | 1      | 25%     |
| Hitachi HDS722020ALA330 2TB              | 1        | 1      | 25%     |
| A-DATA Technology SU800NS38 256GB SSD    | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 1        | 1      | 25%     |
| Micron Technology | 1        | 1      | 25%     |
| Hitachi           | 1        | 1      | 25%     |
| A-DATA Technology | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Hitachi | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 2      | 50%     |
| HDD  | 2        | 2      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 35       | 136    | 60.34%  |
| Works    | 19       | 45     | 32.76%  |
| Malfunc  | 4        | 4      | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 44       | 53.01%  |
| AMD                          | 8        | 9.64%   |
| Samsung Electronics          | 7        | 8.43%   |
| Phison Electronics           | 4        | 4.82%   |
| Marvell Technology Group     | 3        | 3.61%   |
| ASMedia Technology           | 3        | 3.61%   |
| Toshiba America Info Systems | 2        | 2.41%   |
| SK hynix                     | 2        | 2.41%   |
| LSI Logic / Symbios Logic    | 2        | 2.41%   |
| Broadcom / LSI               | 2        | 2.41%   |
| ADATA Technology             | 2        | 2.41%   |
| Western Digital              | 1        | 1.2%    |
| Silicon Motion               | 1        | 1.2%    |
| SanDisk                      | 1        | 1.2%    |
| HighPoint Technologies       | 1        | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 7.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 5.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 4.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 4.04%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 3.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.03%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 3.03%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2        | 2.02%   |
| SK hynix Non-Volatile memory controller                                                 | 2        | 2.02%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 2.02%   |
| Phison E12 NVMe Controller                                                              | 2        | 2.02%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 2.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 2.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.02%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                             | 1        | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.01%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.01%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.01%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 1.01%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 1.01%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 1.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.01%   |
| Intel SSD 660P Series                                                                   | 1        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.01%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.01%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.01%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 1.01%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 59.74%  |
| NVMe | 16       | 20.78%  |
| RAID | 8        | 10.39%  |
| IDE  | 4        | 5.19%   |
| SAS  | 3        | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 45       | 84.91%  |
| AMD    | 8        | 15.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz        | 4        | 7.55%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3        | 5.66%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 2        | 3.77%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2        | 3.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 3.77%   |
| Intel Xeon CPU E5472 @ 3.00GHz          | 1        | 1.89%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz     | 1        | 1.89%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1        | 1.89%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz     | 1        | 1.89%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1        | 1.89%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1        | 1.89%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz     | 1        | 1.89%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 1.89%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1        | 1.89%   |
| Intel Core i7-9700F CPU @ 3.00GHz       | 1        | 1.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1        | 1.89%   |
| Intel Core i7-7560U CPU @ 2.40GHz       | 1        | 1.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 1.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.89%   |
| Intel Core i7-3820 CPU @ 3.60GHz        | 1        | 1.89%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 1        | 1.89%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 1.89%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1        | 1.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 1.89%   |
| Intel Core i5-4690 CPU @ 3.50GHz        | 1        | 1.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1        | 1.89%   |
| Intel Core i5-3570K CPU @ 3.40GHz       | 1        | 1.89%   |
| Intel Core i5-3550 CPU @ 3.30GHz        | 1        | 1.89%   |
| Intel Core i5-3470T CPU @ 2.90GHz       | 1        | 1.89%   |
| Intel Core i5-3450 CPU @ 3.10GHz        | 1        | 1.89%   |
| Intel Core i5-2400S CPU @ 2.50GHz       | 1        | 1.89%   |
| Intel Core i5-10600K CPU @ 4.10GHz      | 1        | 1.89%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 1        | 1.89%   |
| Intel Core i3-6100T CPU @ 3.20GHz       | 1        | 1.89%   |
| Intel Core i3-4330 CPU @ 3.50GHz        | 1        | 1.89%   |
| Intel Core i3-4170 CPU @ 3.70GHz        | 1        | 1.89%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1        | 1.89%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1        | 1.89%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1        | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 14       | 26.42%  |
| Intel Core i5      | 11       | 20.75%  |
| Intel Xeon         | 10       | 18.87%  |
| Intel Core i3      | 6        | 11.32%  |
| AMD Ryzen 9        | 3        | 5.66%   |
| Intel Pentium Gold | 2        | 3.77%   |
| AMD Ryzen 7        | 2        | 3.77%   |
| Other              | 1        | 1.89%   |
| Intel Core i9      | 1        | 1.89%   |
| AMD Ryzen 5        | 1        | 1.89%   |
| AMD Ryzen 3        | 1        | 1.89%   |
| AMD FX             | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 39.62%  |
| 2      | 9        | 16.98%  |
| 6      | 8        | 15.09%  |
| 8      | 6        | 11.32%  |
| 12     | 5        | 9.43%   |
| 36     | 1        | 1.89%   |
| 24     | 1        | 1.89%   |
| 20     | 1        | 1.89%   |
| 16     | 1        | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 90.57%  |
| 2      | 5        | 9.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 38       | 70.37%  |
| 1      | 16       | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 52       | 98.11%  |
| Unknown        | 1        | 1.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 10       | 18.87%  |
| 0x906ea    | 7        | 13.21%  |
| 0x306f2    | 4        | 7.55%   |
| 0x306a9    | 4        | 7.55%   |
| 0x906ed    | 3        | 5.66%   |
| 0x906e9    | 3        | 5.66%   |
| 0x506e3    | 3        | 5.66%   |
| 0x206d7    | 2        | 3.77%   |
| 0x08701021 | 2        | 3.77%   |
| 0xa0671    | 1        | 1.89%   |
| 0xa0655    | 1        | 1.89%   |
| 0x906eb    | 1        | 1.89%   |
| 0x806e9    | 1        | 1.89%   |
| 0x406f1    | 1        | 1.89%   |
| 0x306e4    | 1        | 1.89%   |
| 0x206a7    | 1        | 1.89%   |
| 0x10676    | 1        | 1.89%   |
| 0x08701013 | 1        | 1.89%   |
| 0x08108102 | 1        | 1.89%   |
| 0x0810100b | 1        | 1.89%   |
| 0x08001138 | 1        | 1.89%   |
| 0x08001137 | 1        | 1.89%   |
| 0x06000852 | 1        | 1.89%   |
| Unknown    | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 15       | 28.3%   |
| Haswell     | 14       | 26.42%  |
| IvyBridge   | 6        | 11.32%  |
| Zen 2       | 3        | 5.66%   |
| Zen         | 3        | 5.66%   |
| Skylake     | 3        | 5.66%   |
| SandyBridge | 3        | 5.66%   |
| Zen+        | 1        | 1.89%   |
| Piledriver  | 1        | 1.89%   |
| Penryn      | 1        | 1.89%   |
| Icelake     | 1        | 1.89%   |
| CometLake   | 1        | 1.89%   |
| Broadwell   | 1        | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 32       | 50%     |
| Intel  | 23       | 35.94%  |
| AMD    | 9        | 14.06%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 9.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.55%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 3.03%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.03%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.03%   |
| Intel HD Graphics 630                                                       | 2        | 3.03%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.52%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.52%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.52%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.52%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.52%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.52%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.52%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.52%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.52%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.52%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.52%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.52%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.52%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.52%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.52%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.52%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.52%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.52%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.52%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.52%   |
| Intel Iris Plus Graphics 640                                                | 1        | 1.52%   |
| Intel HD Graphics 530                                                       | 1        | 1.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.52%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 28       | 50.91%  |
| 1 x Intel      | 14       | 25.45%  |
| 1 x AMD        | 6        | 10.91%  |
| Intel + Nvidia | 3        | 5.45%   |
| Intel + AMD    | 2        | 3.64%   |
| 2 x Nvidia     | 1        | 1.82%   |
| 2 x AMD        | 1        | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 35       | 64.81%  |
| Proprietary | 17       | 31.48%  |
| Unknown     | 2        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 37.93%  |
| 1.01-2.0   | 11       | 18.97%  |
| 7.01-8.0   | 8        | 13.79%  |
| 3.01-4.0   | 4        | 6.9%    |
| 5.01-6.0   | 3        | 5.17%   |
| 2.01-3.0   | 3        | 5.17%   |
| 0.51-1.0   | 3        | 5.17%   |
| 0.01-0.5   | 3        | 5.17%   |
| 8.01-16.0  | 1        | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 16.67%  |
| Goldstar             | 8        | 13.33%  |
| Dell                 | 7        | 11.67%  |
| Lenovo               | 6        | 10%     |
| Hewlett-Packard      | 6        | 10%     |
| BenQ                 | 3        | 5%      |
| Ancor Communications | 3        | 5%      |
| ViewSonic            | 2        | 3.33%   |
| Philips              | 2        | 3.33%   |
| Lenovo Group Limited | 2        | 3.33%   |
| Iiyama               | 2        | 3.33%   |
| Gigabyte Technology  | 2        | 3.33%   |
| Eizo                 | 2        | 3.33%   |
| Acer                 | 2        | 3.33%   |
| LG Electronics       | 1        | 1.67%   |
| Insignia             | 1        | 1.67%   |
| Unknown              | 1        | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 2        | 2.9%    |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2        | 2.9%    |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 2        | 2.9%    |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2        | 2.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 2.9%    |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1        | 1.45%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1        | 1.45%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1        | 1.45%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1        | 1.45%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 1        | 1.45%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 1        | 1.45%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1        | 1.45%   |
| Samsung Electronics LCD Monitor S22B150                               | 1        | 1.45%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1        | 1.45%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1        | 1.45%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1        | 1.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.45%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 1.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 1.45%   |
| LG Electronics LCD Monitor W2486 1920x1080                            | 1        | 1.45%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                  | 1        | 1.45%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 1        | 1.45%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1        | 1.45%   |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                | 1        | 1.45%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                | 1        | 1.45%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                | 1        | 1.45%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10                          | 1        | 1.45%   |
| Insignia NS-32D511NA15 BBY4000 1920x1080 591x355mm 27.1-inch          | 1        | 1.45%   |
| Hewlett-Packard Z38c HPN3411 3840x1600 880x367mm 37.5-inch            | 1        | 1.45%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 1        | 1.45%   |
| Hewlett-Packard LCD Monitor LA2306                                    | 1        | 1.45%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch         | 1        | 1.45%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch            | 1        | 1.45%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch            | 1        | 1.45%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                  | 1        | 1.45%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1        | 1.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 1        | 1.45%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch              | 1        | 1.45%   |
| Goldstar 26LB75 GSM5673 1920x1080 700x390mm 31.5-inch                 | 1        | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 28       | 48.28%  |
| 2560x1440 (QHD)   | 6        | 10.34%  |
| 3840x2160 (4K)    | 4        | 6.9%    |
| 3840x1080         | 3        | 5.17%   |
| 3440x1440         | 3        | 5.17%   |
| 1600x900 (HD+)    | 3        | 5.17%   |
| Unknown           | 3        | 5.17%   |
| 9600x2160         | 1        | 1.72%   |
| 7680x2160         | 1        | 1.72%   |
| 3840x1600         | 1        | 1.72%   |
| 3840x1200         | 1        | 1.72%   |
| 2560x1080         | 1        | 1.72%   |
| 1920x1200 (WUXGA) | 1        | 1.72%   |
| 1440x900 (WXGA+)  | 1        | 1.72%   |
| 1280x720 (HD)     | 1        | 1.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 16.67%  |
| 23      | 9        | 15%     |
| 27      | 8        | 13.33%  |
| 24      | 8        | 13.33%  |
| 21      | 7        | 11.67%  |
| 31      | 4        | 6.67%   |
| 20      | 3        | 5%      |
| 54      | 2        | 3.33%   |
| 47      | 2        | 3.33%   |
| 34      | 2        | 3.33%   |
| 40      | 1        | 1.67%   |
| 39      | 1        | 1.67%   |
| 37      | 1        | 1.67%   |
| 25      | 1        | 1.67%   |
| 18      | 1        | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 23       | 40.35%  |
| 401-500     | 10       | 17.54%  |
| Unknown     | 10       | 17.54%  |
| 601-700     | 5        | 8.77%   |
| 1001-1500   | 4        | 7.02%   |
| 801-900     | 3        | 5.26%   |
| 701-800     | 2        | 3.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 37       | 72.55%  |
| Unknown | 8        | 15.69%  |
| 21/9    | 3        | 5.88%   |
| 16/10   | 3        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 35.59%  |
| Unknown        | 10       | 16.95%  |
| 301-350        | 8        | 13.56%  |
| 351-500        | 6        | 10.17%  |
| 501-1000       | 5        | 8.47%   |
| 151-200        | 4        | 6.78%   |
| 251-300        | 3        | 5.08%   |
| More than 1000 | 2        | 3.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 50%     |
| 101-120 | 12       | 20.69%  |
| Unknown | 10       | 17.24%  |
| 1-50    | 4        | 6.9%    |
| 161-240 | 2        | 3.45%   |
| 121-160 | 1        | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 73.68%  |
| 2     | 8        | 14.04%  |
| 3     | 4        | 7.02%   |
| 0     | 3        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 36       | 44.44%  |
| Realtek Semiconductor    | 23       | 28.4%   |
| Qualcomm Atheros         | 7        | 8.64%   |
| Broadcom                 | 4        | 4.94%   |
| ASIX Electronics         | 2        | 2.47%   |
| Ralink Technology        | 1        | 1.23%   |
| Ralink                   | 1        | 1.23%   |
| Microchip Technology     | 1        | 1.23%   |
| Micro Star International | 1        | 1.23%   |
| MediaTek                 | 1        | 1.23%   |
| Huawei Technologies      | 1        | 1.23%   |
| D-Link                   | 1        | 1.23%   |
| Broadcom Limited         | 1        | 1.23%   |
| Arduino SA               | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 19       | 18.45%  |
| Intel I211 Gigabit Network Connection                                      | 6        | 5.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5        | 4.85%   |
| Intel Ethernet Connection (7) I219-LM                                      | 4        | 3.88%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.91%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 2.91%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 2.91%   |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 2.91%   |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 2.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3        | 2.91%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 2.91%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 2.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 2        | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 1.94%   |
| Intel Wireless-AC 9260                                                     | 2        | 1.94%   |
| Intel I210 Gigabit Network Connection                                      | 2        | 1.94%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.94%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 1.94%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 0.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                          | 1        | 0.97%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 0.97%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.97%   |
| Microchip TrueRNG                                                          | 1        | 0.97%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 0.97%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 0.97%   |
| Intel Wireless 7260                                                        | 1        | 0.97%   |
| Intel I350 Gigabit Network Connection                                      | 1        | 0.97%   |
| Intel Ethernet Controller I225-V                                           | 1        | 0.97%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 32.14%  |
| Qualcomm Atheros         | 6        | 21.43%  |
| Realtek Semiconductor    | 4        | 14.29%  |
| Broadcom                 | 4        | 14.29%  |
| Ralink Technology        | 1        | 3.57%   |
| Ralink                   | 1        | 3.57%   |
| Micro Star International | 1        | 3.57%   |
| MediaTek                 | 1        | 3.57%   |
| D-Link                   | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 3        | 10.71%  |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3        | 10.71%  |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 10.71%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 7.14%   |
| Intel Wireless-AC 9260                                                     | 2        | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 3.57%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 3.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.57%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.57%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 3.57%   |
| Intel Wireless 7260                                                        | 1        | 3.57%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 3.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 36       | 58.06%  |
| Realtek Semiconductor | 21       | 33.87%  |
| Qualcomm Atheros      | 2        | 3.23%   |
| ASIX Electronics      | 2        | 3.23%   |
| Broadcom Limited      | 1        | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19       | 26.39%  |
| Intel I211 Gigabit Network Connection                                         | 6        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 6.94%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 5.56%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 4.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 4.17%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 4.17%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 2.78%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.78%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.78%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 2.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.39%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.39%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.39%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.39%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.39%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.39%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.39%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 63.1%   |
| WiFi     | 28       | 33.33%  |
| Modem    | 3        | 3.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 81.48%  |
| WiFi     | 10       | 18.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 44.44%  |
| 2     | 18       | 33.33%  |
| 3     | 10       | 18.52%  |
| 6     | 1        | 1.85%   |
| 4     | 1        | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 83.33%  |
| Yes  | 9        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 30.43%  |
| Cambridge Silicon Radio         | 6        | 26.09%  |
| ASUSTek Computer                | 3        | 13.04%  |
| Realtek Semiconductor           | 2        | 8.7%    |
| Qualcomm Atheros Communications | 2        | 8.7%    |
| Micro Star International        | 1        | 4.35%   |
| IMC Networks                    | 1        | 4.35%   |
| Broadcom                        | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 26.09%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 13.04%  |
| Realtek Bluetooth Radio                               | 2        | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 8.7%    |
| Intel AX200 Bluetooth                                 | 2        | 8.7%    |
| ASUS BCM20702A0                                       | 2        | 8.7%    |
| Micro Star International Bluetooth Device             | 1        | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.35%   |
| Intel Bluetooth wireless interface                    | 1        | 4.35%   |
| IMC Networks BCM20702A0                               | 1        | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 42       | 41.18%  |
| Nvidia                    | 30       | 29.41%  |
| AMD                       | 12       | 11.76%  |
| Lenovo                    | 3        | 2.94%   |
| Creative Labs             | 3        | 2.94%   |
| Plantronics               | 2        | 1.96%   |
| Texas Instruments         | 1        | 0.98%   |
| Tenx Technology           | 1        | 0.98%   |
| Sennheiser Communications | 1        | 0.98%   |
| RODE Microphones          | 1        | 0.98%   |
| Logitech                  | 1        | 0.98%   |
| JMTek                     | 1        | 0.98%   |
| Giga-Byte Technology      | 1        | 0.98%   |
| Dynex                     | 1        | 0.98%   |
| Creative Technology       | 1        | 0.98%   |
| ASUSTek Computer          | 1        | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                              | 9        | 8.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 8        | 7.21%   |
| Intel C610/X99 series chipset HD Audio Controller                       | 5        | 4.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 5        | 4.5%    |
| Nvidia GP107GL High Definition Audio Controller                         | 4        | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 4        | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 4        | 3.6%    |
| Nvidia GP106 High Definition Audio Controller                           | 3        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                           | 3        | 2.7%    |
| Nvidia GF108 High Definition Audio Controller                           | 3        | 2.7%    |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                              | 3        | 2.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller          | 3        | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                | 3        | 2.7%    |
| Nvidia TU116 High Definition Audio Controller                           | 2        | 1.8%    |
| Nvidia TU106 High Definition Audio Controller                           | 2        | 1.8%    |
| Nvidia TU104 HD Audio Controller                                        | 2        | 1.8%    |
| Nvidia GM204 High Definition Audio Controller                           | 2        | 1.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 2        | 1.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2        | 1.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                       | 2        | 1.8%    |
| Intel 200 Series PCH HD Audio                                           | 2        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 2        | 1.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2        | 1.8%    |
| AMD Family 17h/19h HD Audio Controller                                  | 2        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 2        | 1.8%    |
| Texas Instruments PCM2902 Audio Codec                                   | 1        | 0.9%    |
| Tenx Technology USB AUDIO                                               | 1        | 0.9%    |
| Sennheiser Communications EPOS ADAPT 1x5T                               | 1        | 0.9%    |
| RODE Microphones RODE NT-USB                                            | 1        | 0.9%    |
| Plantronics Poly BT700                                                  | 1        | 0.9%    |
| Plantronics BT600                                                       | 1        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                      | 1        | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 0.9%    |
| Nvidia GK106 HDMI Audio Controller                                      | 1        | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                      | 1        | 0.9%    |
| Nvidia GF114 HDMI Audio Controller                                      | 1        | 0.9%    |
| Nvidia GF110 High Definition Audio Controller                           | 1        | 0.9%    |
| Logitech H570e Mono                                                     | 1        | 0.9%    |
| JMTek USB Speaker                                                       | 1        | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 18.52%  |
| Crucial             | 5        | 18.52%  |
| Micron Technology   | 4        | 14.81%  |
| Kingston            | 4        | 14.81%  |
| Corsair             | 3        | 11.11%  |
| SK hynix            | 2        | 7.41%   |
| Unknown (0x0205)    | 1        | 3.7%    |
| Transcend           | 1        | 3.7%    |
| Patriot             | 1        | 3.7%    |
| GOODRAM             | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s      | 2        | 6.45%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s    | 2        | 6.45%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s        | 1        | 3.23%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s          | 1        | 3.23%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s   | 1        | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s   | 1        | 3.23%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s      | 1        | 3.23%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                 | 1        | 3.23%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                 | 1        | 3.23%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                | 1        | 3.23%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s       | 1        | 3.23%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 3.23%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s          | 1        | 3.23%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 3.23%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s      | 1        | 3.23%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s       | 1        | 3.23%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s       | 1        | 3.23%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s      | 1        | 3.23%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s      | 1        | 3.23%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s     | 1        | 3.23%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s   | 1        | 3.23%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s      | 1        | 3.23%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 3.23%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s      | 1        | 3.23%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s  | 1        | 3.23%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4096MB DIMM DDR4 2400MT/s | 1        | 3.23%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s     | 1        | 3.23%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s     | 1        | 3.23%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s     | 1        | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 14       | 63.64%  |
| DDR3  | 6        | 27.27%  |
| SDRAM | 2        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 95.45%  |
| SODIMM | 1        | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 32%     |
| 4096  | 7        | 28%     |
| 16384 | 5        | 20%     |
| 32768 | 4        | 16%     |
| 2048  | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 24%     |
| 2400  | 5        | 20%     |
| 2667  | 3        | 12%     |
| 3600  | 2        | 8%      |
| 3200  | 2        | 8%      |
| 2133  | 2        | 8%      |
| 1333  | 2        | 8%      |
| 2933  | 1        | 4%      |
| 2666  | 1        | 4%      |
| 2472  | 1        | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 2        | 50%     |
| Hewlett-Packard    | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP LaserJet Professional P 1102w | 1        | 25%     |
| Canon E560 series                | 1        | 25%     |
| Canon CanoScan LiDE 300          | 1        | 25%     |
| Brother DCP-1610W                | 1        | 25%     |

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
| Unknown                | 3        | 25%     |
| Logitech               | 2        | 16.67%  |
| Generalplus Technology | 2        | 16.67%  |
| Samsung Electronics    | 1        | 8.33%   |
| Ruision                | 1        | 8.33%   |
| Microsoft              | 1        | 8.33%   |
| Jieli Technology       | 1        | 8.33%   |
| ARC International      | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown FULL HD 1080P Webcam | 3        | 25%     |
| Generalplus GENERAL WEBCAM   | 2        | 16.67%  |
| Samsung Galaxy A5 (MTP)      | 1        | 8.33%   |
| Ruision UVC Camera           | 1        | 8.33%   |
| Microsoft LifeCam HD-3000    | 1        | 8.33%   |
| Logitech Webcam C270         | 1        | 8.33%   |
| Logitech HD Webcam C910      | 1        | 8.33%   |
| Jieli USB PHY 2.0            | 1        | 8.33%   |
| ARC International Camera     | 1        | 8.33%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 43       | 79.63%  |
| 1     | 7        | 12.96%  |
| 2     | 3        | 5.56%   |
| 5     | 1        | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 6        | 37.5%   |
| Net/wireless             | 4        | 25%     |
| Graphics card            | 2        | 12.5%   |
| Storage/ide              | 1        | 6.25%   |
| Sound                    | 1        | 6.25%   |
| Communication controller | 1        | 6.25%   |
| Bluetooth                | 1        | 6.25%   |

