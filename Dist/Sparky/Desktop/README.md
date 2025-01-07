Sparky - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 67

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| MSI      | B450-A PRO           | [fa8374d09c](https://linux-hardware.org/?probe=fa8374d09c) | Jan 01, 2025 |
| Medion   | Cattle24 -1M         | [61c76bd6c0](https://linux-hardware.org/?probe=61c76bd6c0) | Dec 12, 2024 |
| Gigabyte | B75M-D3V             | [cd9edd2505](https://linux-hardware.org/?probe=cd9edd2505) | Dec 01, 2024 |
| Gigabyte | MCMLUCB-00           | [399b34534b](https://linux-hardware.org/?probe=399b34534b) | Nov 30, 2024 |
| Gigabyte | G41MT-S2P            | [03b66cc4a0](https://linux-hardware.org/?probe=03b66cc4a0) | Nov 11, 2024 |
| Acer     | Aspire XC-330        | [7edd74c7bc](https://linux-hardware.org/?probe=7edd74c7bc) | Nov 02, 2024 |
| HP       | 83E9                 | [a8c7212eec](https://linux-hardware.org/?probe=a8c7212eec) | Oct 26, 2024 |
| ASRock   | 880G Extreme3        | [a11c4a176b](https://linux-hardware.org/?probe=a11c4a176b) | Oct 16, 2024 |
| HP       | 83E9                 | [a26f6b9e1d](https://linux-hardware.org/?probe=a26f6b9e1d) | Oct 09, 2024 |
| Dell     | 0782GW A01           | [d1ed50314a](https://linux-hardware.org/?probe=d1ed50314a) | Oct 03, 2024 |
| HP       | 1497                 | [e347f83774](https://linux-hardware.org/?probe=e347f83774) | Sep 30, 2024 |
| Dell     | 03NVJ6 A02           | [42eb12cacb](https://linux-hardware.org/?probe=42eb12cacb) | Sep 29, 2024 |
| HP       | 3396                 | [82e508aef8](https://linux-hardware.org/?probe=82e508aef8) | Sep 25, 2024 |
| HP       | 8055                 | [556b046357](https://linux-hardware.org/?probe=556b046357) | Sep 25, 2024 |
| HP       | 339A                 | [21dd06c3ca](https://linux-hardware.org/?probe=21dd06c3ca) | Sep 23, 2024 |
| Dell     | 0NW6H5 A00           | [c5244dca84](https://linux-hardware.org/?probe=c5244dca84) | Sep 23, 2024 |
| Gigabyte | MCMLUCB-00           | [1ffefdd590](https://linux-hardware.org/?probe=1ffefdd590) | Sep 23, 2024 |
| Dell     | 0782GW A01           | [a37ebb47f3](https://linux-hardware.org/?probe=a37ebb47f3) | Sep 23, 2024 |
| Dell     | 0YXT71 A03           | [f102a6007a](https://linux-hardware.org/?probe=f102a6007a) | Sep 23, 2024 |
| HP       | 8298                 | [4c6705e4c4](https://linux-hardware.org/?probe=4c6705e4c4) | Sep 11, 2024 |
| ASUSTek  | PRIME H510M-K        | [fc06ed6b10](https://linux-hardware.org/?probe=fc06ed6b10) | Feb 20, 2024 |
| Lenovo   | 315F NOK             | [620272c63f](https://linux-hardware.org/?probe=620272c63f) | Feb 13, 2024 |
| HP       | 212B                 | [cb5e65ba08](https://linux-hardware.org/?probe=cb5e65ba08) | Jan 21, 2024 |
| Acer     | Aspire X3950         | [09dfa7ff4b](https://linux-hardware.org/?probe=09dfa7ff4b) | Jan 04, 2024 |
| Acer     | FIH57                | [0edb232edf](https://linux-hardware.org/?probe=0edb232edf) | Dec 16, 2023 |
| HP       | 0A80h                | [5e6a479e17](https://linux-hardware.org/?probe=5e6a479e17) | Dec 01, 2023 |
| ASUSTek  | P7H55-M              | [ad3f143871](https://linux-hardware.org/?probe=ad3f143871) | Oct 20, 2023 |
| Dell     | 0YXT71 A01           | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| ASUSTek  | M5A78L-M LX/BR       | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Dell     | 0GDG8Y A00           | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| ASUSTek  | M4N68T-M             | [f0b58c9f4e](https://linux-hardware.org/?probe=f0b58c9f4e) | Jun 12, 2023 |
| ASRock   | FM2A58M-VG3+ R2.0    | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| HP       | 1589                 | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| HP       | 1589                 | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| HP       | 0A5Ch                | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Acer     | Aspire X3470         | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| Foxconn  | 2ABF                 | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Foxconn  | 2ABF                 | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| Foxconn  | 2ABF                 | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| ASUSTek  | G20AJ                | [7e1557713a](https://linux-hardware.org/?probe=7e1557713a) | Sep 06, 2022 |
| Gigabyte | X570S AORUS PRO AX   | [4fb948980f](https://linux-hardware.org/?probe=4fb948980f) | Aug 25, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel    | H61                  | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| HP       | 3641h                | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| Intel    | H55                  | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| ASUSTek  | CROSSHAIR VI HERO    | [39dcd3854f](https://linux-hardware.org/?probe=39dcd3854f) | Feb 03, 2022 |
| MSI      | B450 GAMING PLUS MAX | [47eae3d6b2](https://linux-hardware.org/?probe=47eae3d6b2) | Jan 19, 2022 |
| MSI      | H310M PRO-VDH PLUS   | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| MSI      | H310M PRO-VDH PLUS   | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP       | 805B                 | [d6c2730444](https://linux-hardware.org/?probe=d6c2730444) | Jul 12, 2021 |
| Gigabyte | H97-Gaming 3         | [d8b0632698](https://linux-hardware.org/?probe=d8b0632698) | May 23, 2021 |
| MSI      | A68HM-E33 V2         | [82a06b4bea](https://linux-hardware.org/?probe=82a06b4bea) | Feb 21, 2021 |
| Gigabyte | H410M H              | [ee13368ccf](https://linux-hardware.org/?probe=ee13368ccf) | Feb 18, 2021 |
| Pegatron | 2AC2A                | [8a5448bc07](https://linux-hardware.org/?probe=8a5448bc07) | Jan 17, 2021 |
| Pegatron | 2AC2A                | [c76bbefc71](https://linux-hardware.org/?probe=c76bbefc71) | Jan 09, 2021 |
| Pegatron | 2AC2A                | [95ead72109](https://linux-hardware.org/?probe=95ead72109) | Dec 17, 2020 |
| HP       | 8056                 | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Intel    | DG41TY AAE47335-300  | [e3457f83fa](https://linux-hardware.org/?probe=e3457f83fa) | Oct 22, 2020 |
| Gigabyte | M68M-S2P             | [0e4bab3503](https://linux-hardware.org/?probe=0e4bab3503) | Oct 05, 2020 |
| Unknown  | 4CoreDX90-VSTA       | [31dbedff45](https://linux-hardware.org/?probe=31dbedff45) | Sep 10, 2020 |
| Gigabyte | G41M-ES2L            | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte | G41M-ES2L            | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Dell     | 039VR8 A00           | [d386006ad9](https://linux-hardware.org/?probe=d386006ad9) | Jun 15, 2020 |
| Vorke    | V1 Plus              | [e371a7cf42](https://linux-hardware.org/?probe=e371a7cf42) | Mar 29, 2020 |
| Intel    | DG43RK AAE78175-402  | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| ASRock   | H61M-VG4             | [93ae8e7a8c](https://linux-hardware.org/?probe=93ae8e7a8c) | Aug 18, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Sparky 7.5  | 13       | 24.53%  |
| Sparky 6    | 7        | 13.21%  |
| Sparky 7    | 5        | 9.43%   |
| Sparky 8    | 4        | 7.55%   |
| Sparky 7.1  | 3        | 5.66%   |
| Sparky 6.7  | 3        | 5.66%   |
| Sparky 5.12 | 3        | 5.66%   |
| Sparky 7.0  | 2        | 3.77%   |
| Sparky 6.3  | 2        | 3.77%   |
| Sparky 6.2  | 2        | 3.77%   |
| Sparky 6.1  | 2        | 3.77%   |
| Sparky 7.6  | 1        | 1.89%   |
| Sparky 7.4  | 1        | 1.89%   |
| Sparky 7.2  | 1        | 1.89%   |
| Sparky 6.6  | 1        | 1.89%   |
| Sparky 6.5  | 1        | 1.89%   |
| Sparky 6.0  | 1        | 1.89%   |
| Sparky 5.10 | 1        | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Sparky | 51       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 6.1.0-25-amd64            | 9        | 16.36%  |
| 6.1.0-13-amd64            | 3        | 5.45%   |
| 6.1.0-26-amd64            | 2        | 3.64%   |
| 6.6.68-x64v3-xanmod1      | 1        | 1.82%   |
| 6.6.15-amd64              | 1        | 1.82%   |
| 6.6.13-amd64              | 1        | 1.82%   |
| 6.4.0-1-amd64             | 1        | 1.82%   |
| 6.12.1-sparky-amd64       | 1        | 1.82%   |
| 6.11.6-sparky-amd64       | 1        | 1.82%   |
| 6.11.3-sparky-amd64       | 1        | 1.82%   |
| 6.1.0-9-amd64             | 1        | 1.82%   |
| 6.1.0-7-amd64             | 1        | 1.82%   |
| 6.1.0-3-amd64             | 1        | 1.82%   |
| 6.1.0-28-amd64            | 1        | 1.82%   |
| 6.1.0-27-amd64            | 1        | 1.82%   |
| 6.1.0-23-amd64            | 1        | 1.82%   |
| 6.1.0-17-amd64            | 1        | 1.82%   |
| 6.1.0-11-amd64            | 1        | 1.82%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1        | 1.82%   |
| 6.0.0-5-amd64             | 1        | 1.82%   |
| 5.9.13-sparky-amd64       | 1        | 1.82%   |
| 5.7.2-sparky-amd64        | 1        | 1.82%   |
| 5.6.0-2-amd64             | 1        | 1.82%   |
| 5.18.3-sparky-amd64       | 1        | 1.82%   |
| 5.18.0-4-amd64            | 1        | 1.82%   |
| 5.18.0-2-amd64            | 1        | 1.82%   |
| 5.17.3-sparky-amd64       | 1        | 1.82%   |
| 5.16.5-sparky-amd64       | 1        | 1.82%   |
| 5.10.0-9-amd64            | 1        | 1.82%   |
| 5.10.0-8-amd64            | 1        | 1.82%   |
| 5.10.0-7-amd64            | 1        | 1.82%   |
| 5.10.0-6-amd64            | 1        | 1.82%   |
| 5.10.0-3-amd64            | 1        | 1.82%   |
| 5.10.0-26-amd64           | 1        | 1.82%   |
| 5.10.0-23-amd64           | 1        | 1.82%   |
| 5.10.0-21-amd64           | 1        | 1.82%   |
| 5.10.0-2-amd64            | 1        | 1.82%   |
| 5.10.0-14-amd64           | 1        | 1.82%   |
| 5.10.0-12-amd64           | 1        | 1.82%   |
| 5.10.0-11-686             | 1        | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.0   | 21       | 38.89%  |
| 5.10.0  | 12       | 22.22%  |
| 4.19.0  | 4        | 7.41%   |
| 5.18.0  | 2        | 3.7%    |
| 6.6.68  | 1        | 1.85%   |
| 6.6.15  | 1        | 1.85%   |
| 6.6.13  | 1        | 1.85%   |
| 6.4.0   | 1        | 1.85%   |
| 6.12.1  | 1        | 1.85%   |
| 6.11.6  | 1        | 1.85%   |
| 6.11.3  | 1        | 1.85%   |
| 6.0.11  | 1        | 1.85%   |
| 6.0.0   | 1        | 1.85%   |
| 5.9.13  | 1        | 1.85%   |
| 5.7.2   | 1        | 1.85%   |
| 5.6.0   | 1        | 1.85%   |
| 5.18.3  | 1        | 1.85%   |
| 5.17.3  | 1        | 1.85%   |
| 5.16.5  | 1        | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 21       | 39.62%  |
| 5.10    | 12       | 22.64%  |
| 4.19    | 4        | 7.55%   |
| 6.6     | 3        | 5.66%   |
| 5.18    | 3        | 5.66%   |
| 6.11    | 2        | 3.77%   |
| 6.4     | 1        | 1.89%   |
| 6.12    | 1        | 1.89%   |
| 6.0     | 1        | 1.89%   |
| 5.9     | 1        | 1.89%   |
| 5.7     | 1        | 1.89%   |
| 5.6     | 1        | 1.89%   |
| 5.17    | 1        | 1.89%   |
| 5.16    | 1        | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 96.08%  |
| i686   | 2        | 3.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 20       | 39.22%  |
| X-Cinnamon       | 11       | 21.57%  |
| LXQt             | 9        | 17.65%  |
| KDE5             | 3        | 5.88%   |
| MATE             | 1        | 1.96%   |
| LXDE             | 1        | 1.96%   |
| lightdm-xsession | 1        | 1.96%   |
| ICEWM            | 1        | 1.96%   |
| GNOME Flashback  | 1        | 1.96%   |
| GNOME            | 1        | 1.96%   |
| Budgie           | 1        | 1.96%   |
| Unknown          | 1        | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 51       | 98.08%  |
| Tty  | 1        | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 43.14%  |
| LightDM | 13       | 25.49%  |
| SDDM    | 9        | 17.65%  |
| TDM     | 6        | 11.76%  |
| GDM     | 1        | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 20       | 39.22%  |
| pt_BR | 5        | 9.8%    |
| en_GB | 4        | 7.84%   |
| pl_PL | 3        | 5.88%   |
| fr_FR | 3        | 5.88%   |
| es_ES | 3        | 5.88%   |
| de_DE | 2        | 3.92%   |
| sv_SE | 1        | 1.96%   |
| ru_RU | 1        | 1.96%   |
| lt_LT | 1        | 1.96%   |
| it_IT | 1        | 1.96%   |
| es_US | 1        | 1.96%   |
| es_AR | 1        | 1.96%   |
| en_ZA | 1        | 1.96%   |
| en_DK | 1        | 1.96%   |
| en_CA | 1        | 1.96%   |
| de_CH | 1        | 1.96%   |
| cs_CZ | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 37       | 72.55%  |
| EFI  | 14       | 27.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 48       | 94.12%  |
| Btrfs | 2        | 3.92%   |
| Zfs   | 1        | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 43.14%  |
| GPT     | 15       | 29.41%  |
| MBR     | 14       | 27.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 82.35%  |
| Yes       | 9        | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 72.55%  |
| Yes       | 14       | 27.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 13       | 25.49%  |
| Gigabyte Technology | 8        | 15.69%  |
| Dell                | 7        | 13.73%  |
| ASUSTek Computer    | 6        | 11.76%  |
| MSI                 | 4        | 7.84%   |
| Intel               | 4        | 7.84%   |
| Acer                | 4        | 7.84%   |
| Medion              | 1        | 1.96%   |
| Lenovo              | 1        | 1.96%   |
| Foxconn             | 1        | 1.96%   |
| ASRock              | 1        | 1.96%   |
| Unknown             | 1        | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B86                         | 2        | 3.92%   |
| Dell OptiPlex 7010                  | 2        | 3.92%   |
| MSI MS-7C09                         | 1        | 1.96%   |
| MSI MS-7721                         | 1        | 1.96%   |
| Medion P961x                        | 1        | 1.96%   |
| Lenovo ThinkCentre M90s 11D2CTO1WW  | 1        | 1.96%   |
| Intel H61                           | 1        | 1.96%   |
| Intel H55                           | 1        | 1.96%   |
| Intel DG43RK AAE78175-402           | 1        | 1.96%   |
| Intel DG41TY AAE47335-300           | 1        | 1.96%   |
| HP Z440 Workstation                 | 1        | 1.96%   |
| HP Z420 Workstation                 | 1        | 1.96%   |
| HP t5740                            | 1        | 1.96%   |
| HP rp5700 Business System           | 1        | 1.96%   |
| HP EliteDesk 800 G3 TWR             | 1        | 1.96%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 1.96%   |
| HP EliteDesk 800 G2 DM 35W          | 1        | 1.96%   |
| HP EliteDesk 705 G4 DM 65W (TAA)    | 1        | 1.96%   |
| HP EliteDesk 705 G2 MINI            | 1        | 1.96%   |
| HP Compaq Pro 6300 SFF              | 1        | 1.96%   |
| HP Compaq Elite 8300 CMT            | 1        | 1.96%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 1.96%   |
| HP Compaq 6200 Pro SFF PC           | 1        | 1.96%   |
| Gigabyte X570S AORUS PRO AX         | 1        | 1.96%   |
| Gigabyte M68M-S2P                   | 1        | 1.96%   |
| Gigabyte H97-Gaming 3               | 1        | 1.96%   |
| Gigabyte H410M H                    | 1        | 1.96%   |
| Gigabyte G41MT-S2P                  | 1        | 1.96%   |
| Gigabyte G41M-ES2L                  | 1        | 1.96%   |
| Gigabyte BRi3(H)-10110              | 1        | 1.96%   |
| Gigabyte B75M-D3V                   | 1        | 1.96%   |
| Foxconn p6-2010fr                   | 1        | 1.96%   |
| Dell OptiPlex 780                   | 1        | 1.96%   |
| Dell OptiPlex 7050                  | 1        | 1.96%   |
| Dell OptiPlex 580                   | 1        | 1.96%   |
| Dell OptiPlex 5050                  | 1        | 1.96%   |
| Dell Inspiron 620                   | 1        | 1.96%   |
| ASUS PRIME H510M-K                  | 1        | 1.96%   |
| ASUS P7H55-M                        | 1        | 1.96%   |
| ASUS M5A78L-M LX/BR                 | 1        | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 6        | 11.76%  |
| HP EliteDesk           | 5        | 9.8%    |
| HP Compaq              | 4        | 7.84%   |
| Acer Aspire            | 4        | 7.84%   |
| MSI MS-7B86            | 2        | 3.92%   |
| MSI MS-7C09            | 1        | 1.96%   |
| MSI MS-7721            | 1        | 1.96%   |
| Medion P961x           | 1        | 1.96%   |
| Lenovo ThinkCentre     | 1        | 1.96%   |
| Intel H61              | 1        | 1.96%   |
| Intel H55              | 1        | 1.96%   |
| Intel DG43RK           | 1        | 1.96%   |
| Intel DG41TY           | 1        | 1.96%   |
| HP Z440                | 1        | 1.96%   |
| HP Z420                | 1        | 1.96%   |
| HP t5740               | 1        | 1.96%   |
| HP rp5700              | 1        | 1.96%   |
| Gigabyte X570S         | 1        | 1.96%   |
| Gigabyte M68M-S2P      | 1        | 1.96%   |
| Gigabyte H97-Gaming    | 1        | 1.96%   |
| Gigabyte H410M         | 1        | 1.96%   |
| Gigabyte G41MT-S2P     | 1        | 1.96%   |
| Gigabyte G41M-ES2L     | 1        | 1.96%   |
| Gigabyte BRi3(H)-10110 | 1        | 1.96%   |
| Gigabyte B75M-D3V      | 1        | 1.96%   |
| Foxconn p6-2010fr      | 1        | 1.96%   |
| Dell Inspiron          | 1        | 1.96%   |
| ASUS PRIME             | 1        | 1.96%   |
| ASUS P7H55-M           | 1        | 1.96%   |
| ASUS M5A78L-M          | 1        | 1.96%   |
| ASUS M4N68T-M          | 1        | 1.96%   |
| ASUS G20AJ             | 1        | 1.96%   |
| ASUS CROSSHAIR         | 1        | 1.96%   |
| ASRock 880G            | 1        | 1.96%   |
| Unknown                | 1        | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 7        | 13.73%  |
| 2009 | 6        | 11.76%  |
| 2017 | 5        | 9.8%    |
| 2012 | 5        | 9.8%    |
| 2011 | 5        | 9.8%    |
| 2021 | 4        | 7.84%   |
| 2014 | 4        | 7.84%   |
| 2019 | 3        | 5.88%   |
| 2015 | 3        | 5.88%   |
| 2007 | 3        | 5.88%   |
| 2018 | 2        | 3.92%   |
| 2013 | 2        | 3.92%   |
| 2020 | 1        | 1.96%   |
| 2016 | 1        | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 51       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 50       | 98.04%  |
| Enabled  | 1        | 1.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 14       | 27.45%  |
| 16.01-24.0  | 8        | 15.69%  |
| 8.01-16.0   | 8        | 15.69%  |
| 32.01-64.0  | 7        | 13.73%  |
| 24.01-32.0  | 6        | 11.76%  |
| 4.01-8.0    | 4        | 7.84%   |
| 1.01-2.0    | 2        | 3.92%   |
| 2.01-3.0    | 1        | 1.96%   |
| 64.01-256.0 | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 23       | 43.4%   |
| 2.01-3.0   | 12       | 22.64%  |
| 4.01-8.0   | 5        | 9.43%   |
| 8.01-16.0  | 5        | 9.43%   |
| 16.01-24.0 | 4        | 7.55%   |
| 3.01-4.0   | 2        | 3.77%   |
| 0.51-1.0   | 2        | 3.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 42.59%  |
| 2      | 14       | 25.93%  |
| 4      | 5        | 9.26%   |
| 6      | 4        | 7.41%   |
| 3      | 4        | 7.41%   |
| 7      | 2        | 3.7%    |
| 5      | 2        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 53.85%  |
| Yes       | 24       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 96.08%  |
| No        | 2        | 3.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 58.82%  |
| Yes       | 21       | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 80.39%  |
| Yes       | 10       | 19.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 10       | 19.61%  |
| France       | 5        | 9.8%    |
| Brazil       | 5        | 9.8%    |
| UK           | 3        | 5.88%   |
| Sweden       | 3        | 5.88%   |
| Poland       | 3        | 5.88%   |
| Germany      | 3        | 5.88%   |
| Spain        | 2        | 3.92%   |
| Indonesia    | 2        | 3.92%   |
| Argentina    | 2        | 3.92%   |
| Venezuela    | 1        | 1.96%   |
| Switzerland  | 1        | 1.96%   |
| South Africa | 1        | 1.96%   |
| Russia       | 1        | 1.96%   |
| Netherlands  | 1        | 1.96%   |
| Mexico       | 1        | 1.96%   |
| Lithuania    | 1        | 1.96%   |
| Lebanon      | 1        | 1.96%   |
| Italy        | 1        | 1.96%   |
| Hungary      | 1        | 1.96%   |
| Czechia      | 1        | 1.96%   |
| Canada       | 1        | 1.96%   |
| Belgium      | 1        | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Echelon             | 9        | 16.98%  |
| Wrzesnia            | 1        | 1.89%   |
| Woking              | 1        | 1.89%   |
| West Palm Beach     | 1        | 1.89%   |
| Vilnius             | 1        | 1.89%   |
| Uppsala             | 1        | 1.89%   |
| Trelaze             | 1        | 1.89%   |
| Surabaya            | 1        | 1.89%   |
| Sin el Fil          | 1        | 1.89%   |
| San Cristóbal      | 1        | 1.89%   |
| Rudnik              | 1        | 1.89%   |
| Rosario             | 1        | 1.89%   |
| Rio de Janeiro      | 1        | 1.89%   |
| Rio Claro           | 1        | 1.89%   |
| Rheinbach           | 1        | 1.89%   |
| Presidente Prudente | 1        | 1.89%   |
| Posadas             | 1        | 1.89%   |
| Norrköping         | 1        | 1.89%   |
| Moscow              | 1        | 1.89%   |
| Montriond           | 1        | 1.89%   |
| Montreuil           | 1        | 1.89%   |
| Mnisek pod Brdy     | 1        | 1.89%   |
| Kirkcaldy           | 1        | 1.89%   |
| Kage                | 1        | 1.89%   |
| Harlow              | 1        | 1.89%   |
| Guadalajara         | 1        | 1.89%   |
| Grabs               | 1        | 1.89%   |
| Fuveau              | 1        | 1.89%   |
| Frankfurt (Oder)    | 1        | 1.89%   |
| Everswinkel         | 1        | 1.89%   |
| Enfield             | 1        | 1.89%   |
| Duque de Caxias     | 1        | 1.89%   |
| Dartmouth           | 1        | 1.89%   |
| Czeladz             | 1        | 1.89%   |
| Choisy-le-Roi       | 1        | 1.89%   |
| Carapicuiba         | 1        | 1.89%   |
| Cape Town           | 1        | 1.89%   |
| Campomarino         | 1        | 1.89%   |
| Calanda             | 1        | 1.89%   |
| Budapest            | 1        | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 16     | 15.69%  |
| Seagate             | 15       | 19     | 14.71%  |
| Samsung Electronics | 14       | 28     | 13.73%  |
| TO Exter            | 7        | 13     | 6.86%   |
| Hitachi             | 7        | 7      | 6.86%   |
| External            | 7        | 14     | 6.86%   |
| Toshiba             | 5        | 5      | 4.9%    |
| Kingston            | 5        | 6      | 4.9%    |
| JMicron Technology  | 5        | 8      | 4.9%    |
| Sandisk             | 3        | 5      | 2.94%   |
| Patriot             | 2        | 2      | 1.96%   |
| Crucial             | 2        | 2      | 1.96%   |
| XPG                 | 1        | 1      | 0.98%   |
| Team                | 1        | 1      | 0.98%   |
| SK hynix            | 1        | 1      | 0.98%   |
| PNY                 | 1        | 1      | 0.98%   |
| Phison Electronics  | 1        | 1      | 0.98%   |
| OCZ                 | 1        | 1      | 0.98%   |
| Intel               | 1        | 1      | 0.98%   |
| HGST                | 1        | 1      | 0.98%   |
| GOODRAM             | 1        | 2      | 0.98%   |
| Gigabyte Technology | 1        | 1      | 0.98%   |
| China               | 1        | 1      | 0.98%   |
| ASMedia             | 1        | 1      | 0.98%   |
| A-DATA Technology   | 1        | 1      | 0.98%   |
| Unknown             | 1        | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| TO Exter nal USB 3.0 1024GB                         | 7        | 6.31%   |
| JMicron Generic 500GB                               | 5        | 4.5%    |
| External USB3.0 1TB                                 | 5        | 4.5%    |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 2.7%    |
| External USB 3.0 500GB                              | 3        | 2.7%    |
| WDC WD3200AAKS-75L9A0 320GB                         | 2        | 1.8%    |
| Toshiba DT01ACA100 1TB                              | 2        | 1.8%    |
| Seagate ST500LT012-1DG142 500GB                     | 2        | 1.8%    |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2        | 1.8%    |
| Samsung HD161GJ 160GB                               | 2        | 1.8%    |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.8%    |
| Hitachi HDS721050CLA 500GB                          | 2        | 1.8%    |
| XPG GAMMIX S11 Pro 512GB                            | 1        | 0.9%    |
| WDC WD800JD-08MSA1 80GB                             | 1        | 0.9%    |
| WDC WD6400AAKS-22A7B2 640GB                         | 1        | 0.9%    |
| WDC WD5000AVVS-63ZWB0 500GB                         | 1        | 0.9%    |
| WDC WD5000AAKS-75V0A0 500GB                         | 1        | 0.9%    |
| WDC WD50 00LPLX-08ZNTT0 500GB                       | 1        | 0.9%    |
| WDC WD2500AAKX-07U6AA0 250GB                        | 1        | 0.9%    |
| WDC WD2500AAJS-00L7A0 250GB                         | 1        | 0.9%    |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 0.9%    |
| WDC WD1600BEVT-22ZCT0 160GB                         | 1        | 0.9%    |
| WDC WD1600BEVS-00VAT0 160GB                         | 1        | 0.9%    |
| WDC WD1600AAJS-08L7A0 160GB                         | 1        | 0.9%    |
| WDC WD10SPCX-16KHST0 1TB                            | 1        | 0.9%    |
| WDC WD10EZEX-60WN4A0 1TB                            | 1        | 0.9%    |
| WDC WD10EADS-00M2B0 1TB                             | 1        | 0.9%    |
| Toshiba MQ01ACF032 320GB                            | 1        | 0.9%    |
| Toshiba MQ01ABD075 752GB                            | 1        | 0.9%    |
| Toshiba DT01ACA050 500GB                            | 1        | 0.9%    |
| Team TM8PS7256G 256GB SSD                           | 1        | 0.9%    |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 1        | 0.9%    |
| Seagate ST975042 0AS 752GB                          | 1        | 0.9%    |
| Seagate ST9250315AS 250GB                           | 1        | 0.9%    |
| Seagate ST500DM0 02-1BD142 500GB                    | 1        | 0.9%    |
| Seagate ST3500418AS 500GB                           | 1        | 0.9%    |
| Seagate ST3500413AS 500GB                           | 1        | 0.9%    |
| Seagate ST3500312CS 500GB                           | 1        | 0.9%    |
| Seagate ST3320418AS 320GB                           | 1        | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 16     | 23.53%  |
| Seagate             | 15       | 18     | 22.06%  |
| TO Exter            | 7        | 13     | 10.29%  |
| Hitachi             | 7        | 7      | 10.29%  |
| External            | 7        | 14     | 10.29%  |
| Toshiba             | 5        | 5      | 7.35%   |
| Samsung Electronics | 5        | 12     | 7.35%   |
| JMicron Technology  | 5        | 8      | 7.35%   |
| HGST                | 1        | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 12     | 26.09%  |
| Kingston            | 4        | 5      | 17.39%  |
| Patriot             | 2        | 2      | 8.7%    |
| Team                | 1        | 1      | 4.35%   |
| PNY                 | 1        | 1      | 4.35%   |
| OCZ                 | 1        | 1      | 4.35%   |
| Intel               | 1        | 1      | 4.35%   |
| GOODRAM             | 1        | 2      | 4.35%   |
| Gigabyte Technology | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| ASMedia             | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |
| Unknown             | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 94     | 57.75%  |
| SSD  | 20       | 31     | 28.17%  |
| NVMe | 10       | 15     | 14.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 47       | 80     | 68.12%  |
| SAS  | 12       | 45     | 17.39%  |
| NVMe | 10       | 15     | 14.49%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 71     | 56.16%  |
| 0.51-1.0   | 18       | 32     | 24.66%  |
| 1.01-2.0   | 13       | 21     | 17.81%  |
| 2.01-3.0   | 1        | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 11       | 21.15%  |
| 101-250        | 9        | 17.31%  |
| 501-1000       | 9        | 17.31%  |
| More than 3000 | 8        | 15.38%  |
| 2001-3000      | 6        | 11.54%  |
| 1001-2000      | 3        | 5.77%   |
| 51-100         | 3        | 5.77%   |
| 21-50          | 1        | 1.92%   |
| 1-20           | 1        | 1.92%   |
| Unknown        | 1        | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 28.85%  |
| 21-50          | 8        | 15.38%  |
| 1001-2000      | 6        | 11.54%  |
| 251-500        | 5        | 9.62%   |
| 2001-3000      | 5        | 9.62%   |
| 101-250        | 4        | 7.69%   |
| 501-1000       | 4        | 7.69%   |
| More than 3000 | 2        | 3.85%   |
| 51-100         | 2        | 3.85%   |
| Unknown        | 1        | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63ZWB0 500GB    | 1        | 1      | 11.11%  |
| WDC WD1600AAJS-08L7A0 160GB    | 1        | 1      | 11.11%  |
| WDC WD10SPCX-16KHST0 1TB       | 1        | 1      | 11.11%  |
| WDC WD10EADS-00M2B0 1TB        | 1        | 1      | 11.11%  |
| Toshiba DT01ACA100 1TB         | 1        | 1      | 11.11%  |
| Seagate ST9250315AS 250GB      | 1        | 1      | 11.11%  |
| Seagate ST3500413AS 500GB      | 1        | 1      | 11.11%  |
| Seagate ST2000DM008-2FR102 2TB | 1        | 1      | 11.11%  |
| Unknown                        | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 44.44%  |
| Seagate | 3        | 3      | 33.33%  |
| Toshiba | 1        | 1      | 11.11%  |
| Unknown | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 50%     |
| Seagate | 3        | 3      | 37.5%   |
| Toshiba | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 8      | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

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
| Works    | 26       | 38     | 44.83%  |
| Detected | 23       | 93     | 39.66%  |
| Malfunc  | 9        | 9      | 15.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 36       | 52.94%  |
| AMD                         | 12       | 17.65%  |
| Samsung Electronics         | 4        | 5.88%   |
| SanDisk                     | 3        | 4.41%   |
| Nvidia                      | 2        | 2.94%   |
| VIA Technologies            | 1        | 1.47%   |
| SK hynix                    | 1        | 1.47%   |
| Seagate Technology          | 1        | 1.47%   |
| Promise Technology          | 1        | 1.47%   |
| Phison Electronics          | 1        | 1.47%   |
| Micron/Crucial Technology   | 1        | 1.47%   |
| Marvell Technology Group    | 1        | 1.47%   |
| LSI Logic / Symbios Logic   | 1        | 1.47%   |
| Kingston Technology Company | 1        | 1.47%   |
| ASMedia Technology          | 1        | 1.47%   |
| ADATA Technology            | 1        | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 9        | 10.47%  |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 4        | 4.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 4        | 4.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 4        | 4.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3        | 3.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 3        | 3.49%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 3        | 3.49%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 2        | 2.33%   |
| Nvidia MCP61 SATA Controller                                                  | 2        | 2.33%   |
| Nvidia MCP61 IDE                                                              | 2        | 2.33%   |
| Intel SATA Controller [RAID mode]                                             | 2        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2        | 2.33%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 2        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2        | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                        | 2        | 2.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 1.16%   |
| VIA VT8237A SATA 2-Port Controller                                            | 1        | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1        | 1.16%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1        | 1.16%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                    | 1        | 1.16%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1        | 1.16%   |
| Promise PDC20771 [FastTrak TX2300]                                            | 1        | 1.16%   |
| Phison E12 NVMe Controller                                                    | 1        | 1.16%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 1.16%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                     | 1        | 1.16%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                | 1        | 1.16%   |
| Kingston Company NV1 NVMe SSD [E13T] (DRAM-less)                              | 1        | 1.16%   |
| Intel sSATA Controller [RAID Mode]                                            | 1        | 1.16%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1        | 1.16%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1        | 1.16%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1        | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1        | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                    | 1        | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                    | 1        | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1        | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 37       | 52.86%  |
| IDE  | 17       | 24.29%  |
| NVMe | 10       | 14.29%  |
| RAID | 4        | 5.71%   |
| SAS  | 1        | 1.43%   |
| SCSI | 1        | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 72.55%  |
| AMD    | 14       | 27.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz                | 4        | 7.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 3.92%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 3.92%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz             | 1        | 1.96%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz             | 1        | 1.96%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz          | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz     | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 1.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.96%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1        | 1.96%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 1.96%   |
| Intel Core i5-7500T CPU @ 2.70GHz               | 1        | 1.96%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1        | 1.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 1.96%   |
| Intel Core i5-3570K CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 1.96%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 1.96%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.96%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1        | 1.96%   |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 1        | 1.96%   |
| Intel Core i3 CPU 530 @ 2.93GHz                 | 1        | 1.96%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 1.96%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.96%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.96%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 1        | 1.96%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 1.96%   |
| Intel Core 2 CPU 6300 @ 1.86GHz                 | 1        | 1.96%   |
| Intel Atom CPU N280 @ 1.66GHz                   | 1        | 1.96%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 1.96%   |
| AMD Sempron 145 Processor                       | 1        | 1.96%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 1.96%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 1.96%   |
| AMD Ryzen 7 1800X Eight-Core Processor          | 1        | 1.96%   |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 1        | 1.96%   |
| AMD Ryzen 3 3100 4-Core Processor               | 1        | 1.96%   |
| AMD PRO A8-8600B R6, 10 Compute Cores 4C+6G     | 1        | 1.96%   |
| AMD Phenom II X6 1045T Processor                | 1        | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 29.41%  |
| Intel Core i7           | 5        | 9.8%    |
| Intel Pentium Dual-Core | 3        | 5.88%   |
| Intel Core i3           | 3        | 5.88%   |
| Intel Core 2 Duo        | 3        | 5.88%   |
| Intel Xeon              | 2        | 3.92%   |
| Intel Core 2 Quad       | 2        | 3.92%   |
| AMD Ryzen 7             | 2        | 3.92%   |
| AMD A6                  | 2        | 3.92%   |
| Other                   | 1        | 1.96%   |
| Intel Pentium Gold      | 1        | 1.96%   |
| Intel Core 2            | 1        | 1.96%   |
| Intel Atom              | 1        | 1.96%   |
| AMD Sempron             | 1        | 1.96%   |
| AMD Ryzen 9             | 1        | 1.96%   |
| AMD Ryzen 5 PRO         | 1        | 1.96%   |
| AMD Ryzen 3             | 1        | 1.96%   |
| AMD PRO A8              | 1        | 1.96%   |
| AMD Phenom II X6        | 1        | 1.96%   |
| AMD Phenom II X4        | 1        | 1.96%   |
| AMD Athlon II X3        | 1        | 1.96%   |
| AMD Athlon II X2        | 1        | 1.96%   |
| AMD A4                  | 1        | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 23       | 45.1%   |
| 2      | 15       | 29.41%  |
| 8      | 5        | 9.8%    |
| 6      | 3        | 5.88%   |
| 1      | 3        | 5.88%   |
| 12     | 1        | 1.96%   |
| 3      | 1        | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 51       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 58.82%  |
| 2      | 21       | 41.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 50       | 98.04%  |
| 32-bit         | 1        | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 35.29%  |
| 0x1067a    | 4        | 7.84%   |
| 0x20652    | 3        | 5.88%   |
| 0x506e3    | 2        | 3.92%   |
| 0x306c3    | 2        | 3.92%   |
| 0x306a9    | 2        | 3.92%   |
| 0x206a7    | 2        | 3.92%   |
| 0x0600611a | 2        | 3.92%   |
| 0xa0653    | 1        | 1.96%   |
| 0x6fd      | 1        | 1.96%   |
| 0x6fb      | 1        | 1.96%   |
| 0x6f2      | 1        | 1.96%   |
| 0x406f1    | 1        | 1.96%   |
| 0x206d7    | 1        | 1.96%   |
| 0x106e5    | 1        | 1.96%   |
| 0x0a50000d | 1        | 1.96%   |
| 0x0a201016 | 1        | 1.96%   |
| 0x08701021 | 1        | 1.96%   |
| 0x08001138 | 1        | 1.96%   |
| 0x06006705 | 1        | 1.96%   |
| 0x03000027 | 1        | 1.96%   |
| 0x010000dc | 1        | 1.96%   |
| 0x010000db | 1        | 1.96%   |
| 0x010000c8 | 1        | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 6        | 11.76%  |
| IvyBridge   | 6        | 11.76%  |
| K10         | 5        | 9.8%    |
| Skylake     | 4        | 7.84%   |
| SandyBridge | 4        | 7.84%   |
| Westmere    | 3        | 5.88%   |
| KabyLake    | 3        | 5.88%   |
| Excavator   | 3        | 5.88%   |
| Core        | 3        | 5.88%   |
| Zen 3       | 2        | 3.92%   |
| Zen         | 2        | 3.92%   |
| Haswell     | 2        | 3.92%   |
| CometLake   | 2        | 3.92%   |
| Zen 2       | 1        | 1.96%   |
| Nehalem     | 1        | 1.96%   |
| K10 Llano   | 1        | 1.96%   |
| Broadwell   | 1        | 1.96%   |
| Bonnell     | 1        | 1.96%   |
| Unknown     | 1        | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 24       | 44.44%  |
| AMD              | 17       | 31.48%  |
| Nvidia           | 12       | 22.22%  |
| VIA Technologies | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 7.27%   |
| Intel HD Graphics 530                                                       | 4        | 7.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 7.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 3.64%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 3.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 3.64%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.82%   |
| Nvidia GT218 [GeForce 310]                                                  | 1        | 1.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.82%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1        | 1.82%   |
| Nvidia GT200GL [Quadro FX 3800]                                             | 1        | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.82%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.82%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.82%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.82%   |
| Nvidia G96CGL [Quadro FX 580]                                               | 1        | 1.82%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1        | 1.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.82%   |
| Intel HD Graphics 630                                                       | 1        | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1        | 1.82%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.82%   |
| AMD Turks GL [FirePro V4900]                                                | 1        | 1.82%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 1        | 1.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1        | 1.82%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.82%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 1.82%   |
| AMD Redwood LE [Radeon HD 5550/5570/5630/6390/6490/7570]                    | 1        | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.82%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.82%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.82%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 1.82%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.82%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 1        | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 20       | 39.22%  |
| 1 x AMD        | 16       | 31.37%  |
| 1 x Nvidia     | 11       | 21.57%  |
| 2 x Intel      | 2        | 3.92%   |
| 1 x VIA        | 1        | 1.96%   |
| Intel + Nvidia | 1        | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 44       | 86.27%  |
| Unknown     | 4        | 7.84%   |
| Proprietary | 3        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 59.62%  |
| 0.51-1.0   | 7        | 13.46%  |
| 0.01-0.5   | 7        | 13.46%  |
| 3.01-4.0   | 3        | 5.77%   |
| 7.01-8.0   | 2        | 3.85%   |
| 1.01-2.0   | 2        | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 21.74%  |
| Sceptre Tech         | 8        | 17.39%  |
| Dell                 | 6        | 13.04%  |
| Goldstar             | 5        | 10.87%  |
| AOC                  | 3        | 6.52%   |
| Acer                 | 3        | 6.52%   |
| Hewlett-Packard      | 2        | 4.35%   |
| BenQ                 | 2        | 4.35%   |
| Unknown              | 1        | 2.17%   |
| Toshiba              | 1        | 2.17%   |
| Philips              | 1        | 2.17%   |
| Medion               | 1        | 2.17%   |
| JCH                  | 1        | 2.17%   |
| ASUSTek Computer     | 1        | 2.17%   |
| Ancor Communications | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch        | 5        | 10.2%   |
| Sceptre Tech Sceptre H43 SPT1104 1920x1080 575x323mm 26.0-inch        | 3        | 6.12%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 2.04%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1        | 2.04%   |
| Samsung Electronics T22C350 SAM0AB7 1920x1080 477x268mm 21.5-inch     | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM0581 1920x1080 477x268mm 21.5-inch  | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1        | 2.04%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch     | 1        | 2.04%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 2.04%   |
| Samsung Electronics S27E370D SAM0CF3 1920x1080 598x336mm 27.0-inch    | 1        | 2.04%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch     | 1        | 2.04%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 2.04%   |
| Samsung Electronics S22C450 SAM09C5 1920x1080 477x268mm 21.5-inch     | 1        | 2.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 2.04%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 2.04%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1        | 2.04%   |
| JCH F24 JCH1919 1920x1080 520x310mm 23.8-inch                         | 1        | 2.04%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 2.04%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 1        | 2.04%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 1        | 2.04%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                  | 1        | 2.04%   |
| Goldstar TV GSM9CF6 1360x768 700x392mm 31.6-inch                      | 1        | 2.04%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1        | 2.04%   |
| Goldstar L1953H GSM4B3D 1280x1024 338x270mm 17.0-inch                 | 1        | 2.04%   |
| Goldstar L1953H GSM4B3C 1280x1024 338x270mm 17.0-inch                 | 1        | 2.04%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1        | 2.04%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 2.04%   |
| Dell U2410 DELF014 1920x1200 518x324mm 24.1-inch                      | 1        | 2.04%   |
| Dell LNKG H2VA001 LNKA001 1920x1080 880x500mm 39.8-inch               | 1        | 2.04%   |
| Dell LCD Monitor S2715H 3840x1080                                     | 1        | 2.04%   |
| Dell LCD Monitor S2715H                                               | 1        | 2.04%   |
| Dell IN1930 DELF03B 1366x768 410x230mm 18.5-inch                      | 1        | 2.04%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 2.04%   |
| BenQ FP202WA BNQ76C2 1680x1050 376x301mm 19.0-inch                    | 1        | 2.04%   |
| BenQ E900HD BNQ7910 1366x768 410x230mm 18.5-inch                      | 1        | 2.04%   |
| ASUSTek Computer VP289Q AUS28E0 3840x2160 621x341mm 27.9-inch         | 1        | 2.04%   |
| AOC LM729 AOCA784 1280x1024 340x270mm 17.1-inch                       | 1        | 2.04%   |
| AOC 2475W1 AOC2475 1920x1080 527x296mm 23.8-inch                      | 1        | 2.04%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 2.04%   |
| Ancor Communications ASUS VA325 ACI32FA 1920x1080 698x393mm 31.5-inch | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 22       | 45.83%  |
| 3840x2160 (4K)     | 6        | 12.5%   |
| 1920x1200 (WUXGA)  | 3        | 6.25%   |
| 1680x1050 (WSXGA+) | 3        | 6.25%   |
| 1366x768 (WXGA)    | 3        | 6.25%   |
| 1280x1024 (SXGA)   | 3        | 6.25%   |
| 3840x1080          | 1        | 2.08%   |
| 2288x1287          | 1        | 2.08%   |
| 1600x900 (HD+)     | 1        | 2.08%   |
| 1440x900 (WXGA+)   | 1        | 2.08%   |
| 1360x768           | 1        | 2.08%   |
| 1280x960           | 1        | 2.08%   |
| 1024x768 (XGA)     | 1        | 2.08%   |
| Unknown            | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 32      | 6        | 12.77%  |
| 24      | 5        | 10.64%  |
| 23      | 5        | 10.64%  |
| 21      | 5        | 10.64%  |
| 27      | 4        | 8.51%   |
| 26      | 3        | 6.38%   |
| 20      | 3        | 6.38%   |
| 17      | 3        | 6.38%   |
| 18      | 2        | 4.26%   |
| 142     | 1        | 2.13%   |
| 74      | 1        | 2.13%   |
| 72      | 1        | 2.13%   |
| 39      | 1        | 2.13%   |
| 31      | 1        | 2.13%   |
| 22      | 1        | 2.13%   |
| 19      | 1        | 2.13%   |
| 16      | 1        | 2.13%   |
| 15      | 1        | 2.13%   |
| 13      | 1        | 2.13%   |
| Unknown | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 16       | 34.04%  |
| 401-500        | 12       | 25.53%  |
| 701-800        | 6        | 12.77%  |
| 301-350        | 5        | 10.64%  |
| 601-700        | 2        | 4.26%   |
| 1501-2000      | 2        | 4.26%   |
| More than 2000 | 1        | 2.13%   |
| 801-900        | 1        | 2.13%   |
| 201-300        | 1        | 2.13%   |
| Unknown        | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 65.22%  |
| 16/10   | 9        | 19.57%  |
| 5/4     | 3        | 6.52%   |
| 4/3     | 2        | 4.35%   |
| 1.00    | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 19.15%  |
| 351-500        | 7        | 14.89%  |
| 251-300        | 7        | 14.89%  |
| 151-200        | 7        | 14.89%  |
| 141-150        | 5        | 10.64%  |
| 301-350        | 4        | 8.51%   |
| More than 1000 | 3        | 6.38%   |
| 81-90          | 1        | 2.13%   |
| 121-130        | 1        | 2.13%   |
| 101-110        | 1        | 2.13%   |
| 501-1000       | 1        | 2.13%   |
| Unknown        | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 65.22%  |
| 121-160 | 6        | 13.04%  |
| 101-120 | 6        | 13.04%  |
| 1-50    | 3        | 6.52%   |
| Unknown | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 88.24%  |
| 2     | 4        | 7.84%   |
| 0     | 2        | 3.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 23       | 34.85%  |
| Intel                 | 21       | 31.82%  |
| Ralink Technology     | 4        | 6.06%   |
| Qualcomm Atheros      | 4        | 6.06%   |
| Broadcom              | 3        | 4.55%   |
| TP-Link               | 2        | 3.03%   |
| Nvidia                | 2        | 3.03%   |
| Broadcom Limited      | 2        | 3.03%   |
| VIA Technologies      | 1        | 1.52%   |
| NetGear               | 1        | 1.52%   |
| MediaTek              | 1        | 1.52%   |
| D-Link System         | 1        | 1.52%   |
| ASUSTek Computer      | 1        | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                      | 18       | 24.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                       | 6        | 8.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                    | 2        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                       | 2        | 2.7%    |
| Nvidia MCP61 Ethernet                                                                       | 2        | 2.7%    |
| Intel Wireless 8260                                                                         | 2        | 2.7%    |
| Intel Ethernet Connection (5) I219-LM                                                       | 2        | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                                                       | 2        | 2.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                                                | 1        | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                 | 1        | 1.35%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                 | 1        | 1.35%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 1.35%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 1.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                       | 1        | 1.35%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                   | 1        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 1.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                               | 1        | 1.35%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 1.35%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                               | 1        | 1.35%   |
| Intel Wireless 8265 / 8275                                                                  | 1        | 1.35%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 1.35%   |
| Intel I211 Gigabit Network Connection                                                       | 1        | 1.35%   |
| Intel Ethernet Controller I225-V                                                            | 1        | 1.35%   |
| Intel Ethernet Connection (6) I219-V                                                        | 1        | 1.35%   |
| Intel Ethernet Connection (5) I219-V                                                        | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                                                        | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-LM                                                       | 1        | 1.35%   |
| Intel Ethernet Connection (11) I219-LM                                                      | 1        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                            | 1        | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                              | 1        | 1.35%   |
| Intel 82578DC Gigabit Network Connection                                                    | 1        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                                  | 1        | 1.35%   |
| Intel 82566DM Gigabit Network Connection                                                    | 1        | 1.35%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                        | 1        | 1.35%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 26.09%  |
| Realtek Semiconductor | 5        | 21.74%  |
| Ralink Technology     | 4        | 17.39%  |
| TP-Link               | 2        | 8.7%    |
| Qualcomm Atheros      | 2        | 8.7%    |
| NetGear               | 1        | 4.35%   |
| MediaTek              | 1        | 4.35%   |
| D-Link System         | 1        | 4.35%   |
| ASUSTek Computer      | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                       | Desktops | Percent |
|---------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                    | 2        | 8.7%    |
| Intel Wireless 8260                                                                         | 2        | 8.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                 | 1        | 4.35%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                         | 1        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                          | 1        | 4.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                    | 1        | 4.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                 | 1        | 4.35%   |
| Ralink RT5370 Wireless Adapter                                                              | 1        | 4.35%   |
| Ralink RT3072 Wireless Adapter                                                              | 1        | 4.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                       | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                                             | 1        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                            | 1        | 4.35%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]               | 1        | 4.35%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                                           | 1        | 4.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                               | 1        | 4.35%   |
| Intel Wireless 8265 / 8275                                                                  | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                         | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                            | 1        | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                              | 1        | 4.35%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104] | 1        | 4.35%   |
| ASUS 802.11ac NIC                                                                           | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 41.18%  |
| Realtek Semiconductor | 20       | 39.22%  |
| Broadcom              | 3        | 5.88%   |
| Qualcomm Atheros      | 2        | 3.92%   |
| Nvidia                | 2        | 3.92%   |
| Broadcom Limited      | 2        | 3.92%   |
| VIA Technologies      | 1        | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18       | 35.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 3.92%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 3.92%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 3.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.92%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 1.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.96%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1        | 1.96%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 1.96%   |
| Intel Ethernet Controller I225-V                                       | 1        | 1.96%   |
| Intel Ethernet Connection (6) I219-V                                   | 1        | 1.96%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.96%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.96%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 1.96%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 1.96%   |
| Intel 82578DC Gigabit Network Connection                               | 1        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.96%   |
| Intel 82566DM Gigabit Network Connection                               | 1        | 1.96%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                   | 1        | 1.96%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 1.96%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1        | 1.96%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                | 1        | 1.96%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 1.96%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                | 1        | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 69.01%  |
| WiFi     | 22       | 30.99%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 74.55%  |
| WiFi     | 14       | 25.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 74.51%  |
| 2     | 13       | 25.49%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 74.51%  |
| Yes  | 13       | 25.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 60%     |
| IMC Networks                    | 2        | 20%     |
| Qualcomm Atheros Communications | 1        | 10%     |
| Cambridge Silicon Radio         | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 30%     |
| Qualcomm Atheros Bluetooth                          | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| Intel AX201 Bluetooth                               | 1        | 10%     |
| Intel AX200 Bluetooth                               | 1        | 10%     |
| IMC Networks Bluetooth Radio                        | 1        | 10%     |
| IMC Networks Bluetooth Module                       | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 34       | 44.16%  |
| AMD                 | 19       | 24.68%  |
| Nvidia              | 11       | 14.29%  |
| Tenx Technology     | 8        | 10.39%  |
| VIA Technologies    | 1        | 1.3%    |
| Plantronics         | 1        | 1.3%    |
| Focusrite-Novation  | 1        | 1.3%    |
| Creative Labs       | 1        | 1.3%    |
| C-Media Electronics | 1        | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Tenx Technology USB AUDIO                                                  | 8        | 9.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 4.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 4.6%    |
| Intel 200 Series PCH HD Audio                                              | 4        | 4.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 3.45%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 2.3%    |
| Nvidia High Definition Audio Controller                                    | 2        | 2.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 2.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 2.3%    |
| AMD FCH Azalia Controller                                                  | 2        | 2.3%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 2        | 2.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 2.3%    |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 2        | 2.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 1.15%   |
| Plantronics USB DSP v4 Audio Interface                                     | 1        | 1.15%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.15%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.15%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.15%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1        | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.15%   |
| Focusrite-Novation Speedio                                                 | 1        | 1.15%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 1.15%   |
| C-Media Electronics USB Audio Device                                       | 1        | 1.15%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 8        | 22.86%  |
| Samsung Electronics | 5        | 14.29%  |
| Kingston            | 5        | 14.29%  |
| SK hynix            | 3        | 8.57%   |
| Micron Technology   | 3        | 8.57%   |
| G.Skill             | 2        | 5.71%   |
| Corsair             | 2        | 5.71%   |
| Unifosa             | 1        | 2.86%   |
| Toshiba             | 1        | 2.86%   |
| Ramaxel Technology  | 1        | 2.86%   |
| GOODRAM             | 1        | 2.86%   |
| Elpida              | 1        | 2.86%   |
| Crucial             | 1        | 2.86%   |
| Avant               | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM 800MT/s                | 2        | 5.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s              | 1        | 2.7%    |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 1        | 2.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 2.7%    |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 2.7%    |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s     | 1        | 2.7%    |
| Toshiba RAM 9905474-012.A00LF 2GB DIMM DDR3 1333MT/s  | 1        | 2.7%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s  | 1        | 2.7%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s  | 1        | 2.7%    |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s     | 1        | 2.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 2.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s | 1        | 2.7%    |
| Samsung RAM M393A2K40BB1-CRC 16GB DIMM DDR4 2400MT/s  | 1        | 2.7%    |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s   | 1        | 2.7%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s   | 1        | 2.7%    |
| Samsung RAM M3 78T2863RZS-CE6 1GB DIMM DDR2 667MT/s   | 1        | 2.7%    |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s  | 1        | 2.7%    |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s | 1        | 2.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s        | 1        | 2.7%    |
| Micron RAM 4ATF51264AZ-2G3H1R 4GB DIMM DDR4 2400MT/s  | 1        | 2.7%    |
| Micron RAM 16KTF1G64AZ-1G9P1 8GB DIMM DDR3 1866MT/s   | 1        | 2.7%    |
| Kingston RAM Module 8GB DIMM DDR3 1600MT/s            | 1        | 2.7%    |
| Kingston RAM Module 16GB SODIMM DDR4 2133MT/s         | 1        | 2.7%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s   | 1        | 2.7%    |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s | 1        | 2.7%    |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s | 1        | 2.7%    |
| GOODRAM RAM Module 16GB DIMM DDR4 2133MT/s            | 1        | 2.7%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 2.7%    |
| G.Skill RAM F2-6400CL4-1GBPK 1GB DIMM DDR2 800MT/s    | 1        | 2.7%    |
| Elpida RAM EBJ41UF8BCF0-DJ-F 4GB DIMM DDR3 1333MT/s   | 1        | 2.7%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s | 1        | 2.7%    |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s   | 1        | 2.7%    |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s | 1        | 2.7%    |
| Avant RAM W641GU49J2320N6 8GB DIMM DDR4 2666MT/s      | 1        | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 13       | 41.94%  |
| DDR4    | 7        | 22.58%  |
| Unknown | 4        | 12.9%   |
| DDR2    | 3        | 9.68%   |
| SDRAM   | 2        | 6.45%   |
| DRAM    | 1        | 3.23%   |
| DDR     | 1        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 26       | 86.67%  |
| SODIMM | 4        | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 11       | 32.35%  |
| 8192  | 9        | 26.47%  |
| 4096  | 7        | 20.59%  |
| 16384 | 4        | 11.76%  |
| 1024  | 3        | 8.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 7        | 20.59%  |
| 1600    | 5        | 14.71%  |
| 800     | 4        | 11.76%  |
| 2400    | 3        | 8.82%   |
| 2133    | 2        | 5.88%   |
| 3800    | 1        | 2.94%   |
| 3666    | 1        | 2.94%   |
| 3200    | 1        | 2.94%   |
| 2666    | 1        | 2.94%   |
| 2048    | 1        | 2.94%   |
| 1867    | 1        | 2.94%   |
| 1866    | 1        | 2.94%   |
| 1800    | 1        | 2.94%   |
| 1639    | 1        | 2.94%   |
| 1067    | 1        | 2.94%   |
| 667     | 1        | 2.94%   |
| 400     | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung CLP-325 Color Laser Printer | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 28.57%  |
| Alcor Micro         | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| JOURIST-DC80        | 1        | 14.29%  |
| Guillemot           | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 14.29%  |
| Logitech Webcam C270                    | 1        | 14.29%  |
| Logitech QuickCam Notebook Pro          | 1        | 14.29%  |
| JOURIST-DC80 JOURIST-DC80               | 1        | 14.29%  |
| Guillemot Hercules Dualpix Exchange     | 1        | 14.29%  |
| Alcor Micro USB 2.0 PC Camera           | 1        | 14.29%  |
| Alcor Micro HD Webcam                   | 1        | 14.29%  |

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
| 0     | 39       | 76.47%  |
| 1     | 11       | 21.57%  |
| 2     | 1        | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 7        | 53.85%  |
| Net/wireless          | 3        | 23.08%  |
| Unassigned class      | 1        | 7.69%   |
| Multimedia controller | 1        | 7.69%   |
| Camera                | 1        | 7.69%   |

