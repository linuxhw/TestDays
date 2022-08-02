RHEL - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for RHEL.

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

Total: 102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Intel         | H81                         | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Dell          | 02K9CR A03                  | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| ASRock        | Z370 Professional Gaming... | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
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
| HP            | ProLiant MicroServer Gen... | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
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
| Dell          | PowerEdge FC630             | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | PowerEdge FC630             | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
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
| Dell          | 00V62H A01                  | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
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
| Dell          | 0G919G A00                  | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Supermicro    | X7DWN+                      | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Dell          | 0HHV7N A00                  | [9e55c4bdee](https://linux-hardware.org/?probe=9e55c4bdee) | Apr 05, 2019 |
| HP            | 158A                        | [6924d366ab](https://linux-hardware.org/?probe=6924d366ab) | Jan 09, 2019 |
| Dell          | 05DN3X A00                  | [4be9ce0f72](https://linux-hardware.org/?probe=4be9ce0f72) | Dec 20, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| RHEL 8 | 51       | 76.12%  |
| RHEL 7 | 12       | 17.91%  |
| RHEL 9 | 4        | 5.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 67       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 8.75%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 7.5%    |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 5%      |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 5%      |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 5%      |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 3.75%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 3.75%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 3.75%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 3.75%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 3.75%   |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 3.75%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 2.5%    |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 2.5%    |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 2.5%    |
| 4.18.0-193.el8.x86_64        | 2        | 2.5%    |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 2.5%    |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 2.5%    |
| 4.18.0-147.el8.x86_64        | 2        | 2.5%    |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 1.25%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.25%   |
| 4.19.150                     | 1        | 1.25%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.25%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 1.25%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.25%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.25%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.25%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.25%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.25%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.25%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.25%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1        | 1.25%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.25%   |
| 3.10.0-957.5.1.el7.x86_64    | 1        | 1.25%   |
| 3.10.0-957.1.3.el7.x86_64    | 1        | 1.25%   |
| 3.10.0-862.9.1.el7.x86_64    | 1        | 1.25%   |
| 3.10.0-862.11.6.el7.x86_64   | 1        | 1.25%   |
| 3.10.0-693.11.6.el7.x86_64   | 1        | 1.25%   |
| 3.10.0-1160.45.1.el7.x86_64  | 1        | 1.25%   |
| 3.10.0-1127.10.1.el7.x86_64  | 1        | 1.25%   |
| 3.10.0-1062.4.3.el7.x86_64   | 1        | 1.25%   |
| 3.10.0-1062.18.1.el7.x86_64  | 1        | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 49       | 73.13%  |
| 3.10.0   | 12       | 17.91%  |
| 5.14.0   | 4        | 5.97%   |
| 5.10.6   | 1        | 1.49%   |
| 4.19.150 | 1        | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 49       | 73.13%  |
| 3.10    | 12       | 17.91%  |
| 5.14    | 4        | 5.97%   |
| 5.10    | 1        | 1.49%   |
| 4.19    | 1        | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 67       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 47       | 67.14%  |
| Unknown       | 14       | 20%     |
| GNOME Classic | 4        | 5.71%   |
| KDE5          | 2        | 2.86%   |
| KDE           | 2        | 2.86%   |
| MATE          | 1        | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 40       | 57.14%  |
| Wayland | 23       | 32.86%  |
| Unknown | 7        | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 53       | 75.71%  |
| GDM     | 16       | 22.86%  |
| LightDM | 1        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 34       | 50%     |
| Unknown | 13       | 19.12%  |
| en_GB   | 4        | 5.88%   |
| ru_RU   | 3        | 4.41%   |
| en_IN   | 3        | 4.41%   |
| pl_PL   | 2        | 2.94%   |
| es_AR   | 2        | 2.94%   |
| de_DE   | 2        | 2.94%   |
| ko_KR   | 1        | 1.47%   |
| es_MX   | 1        | 1.47%   |
| es_ES   | 1        | 1.47%   |
| en_NZ   | 1        | 1.47%   |
| cs_CZ   | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 57.35%  |
| BIOS | 29       | 42.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 61       | 89.71%  |
| Ext4    | 4        | 5.88%   |
| Unknown | 3        | 4.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 39       | 55.71%  |
| GPT     | 19       | 27.14%  |
| MBR     | 12       | 17.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 76.47%  |
| Yes       | 16       | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 91.18%  |
| Yes       | 6        | 8.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 16       | 23.88%  |
| ASUSTek Computer    | 12       | 17.91%  |
| Hewlett-Packard     | 10       | 14.93%  |
| Gigabyte Technology | 7        | 10.45%  |
| ASRock              | 6        | 8.96%   |
| MSI                 | 4        | 5.97%   |
| Lenovo              | 4        | 5.97%   |
| Unknown             | 3        | 4.48%   |
| Intel               | 2        | 2.99%   |
| Supermicro          | 1        | 1.49%   |
| CX / Air Computers. | 1        | 1.49%   |
| Alienware           | 1        | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 8.96%   |
| ASUS All Series                     | 4        | 5.97%   |
| Unknown                             | 3        | 4.48%   |
| HP Z620 Workstation                 | 2        | 2.99%   |
| Dell OptiPlex 9020                  | 2        | 2.99%   |
| Supermicro X7DW3                    | 1        | 1.49%   |
| MSI MS-7B51                         | 1        | 1.49%   |
| MSI MS-7B33                         | 1        | 1.49%   |
| MSI MS-7A37                         | 1        | 1.49%   |
| MSI MS-7752                         | 1        | 1.49%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.49%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.49%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.49%   |
| Lenovo 10SFS03200                   | 1        | 1.49%   |
| Intel H81                           | 1        | 1.49%   |
| Intel DX79SR AAG57199-200           | 1        | 1.49%   |
| HP Z840 Workstation                 | 1        | 1.49%   |
| HP Z440 Workstation                 | 1        | 1.49%   |
| HP Z230 Tower Workstation           | 1        | 1.49%   |
| HP Z230 SFF Workstation             | 1        | 1.49%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.49%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.49%   |
| HP 290 G1 SFF Business PC           | 1        | 1.49%   |
| HP 260-P020il                       | 1        | 1.49%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.49%   |
| Gigabyte Z490 GAMING X              | 1        | 1.49%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.49%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.49%   |
| Gigabyte B75-D3V                    | 1        | 1.49%   |
| Gigabyte B150-HD3                   | 1        | 1.49%   |
| Gigabyte 970A-D3                    | 1        | 1.49%   |
| Dell Vostro 270                     | 1        | 1.49%   |
| Dell Studio XPS 9100                | 1        | 1.49%   |
| Dell Precision Tower 5810           | 1        | 1.49%   |
| Dell Precision Tower 3620           | 1        | 1.49%   |
| Dell Precision Tower 3420           | 1        | 1.49%   |
| Dell Precision T7600                | 1        | 1.49%   |
| Dell Precision 3630 Tower           | 1        | 1.49%   |
| Dell OptiPlex 760                   | 1        | 1.49%   |
| CX / Air Computers. H87-M1          | 1        | 1.49%   |
| ASUS Z10PE-D16 WS                   | 1        | 1.49%   |
| ASUS ROG STRIX B350-F GAMING        | 1        | 1.49%   |
| ASUS ROG Maximus X HERO             | 1        | 1.49%   |
| ASUS Pro WS X570-ACE                | 1        | 1.49%   |
| ASUS PRIME X470-PRO                 | 1        | 1.49%   |
| ASUS PRIME B360M-D                  | 1        | 1.49%   |
| ASUS PRIME B350M-A                  | 1        | 1.49%   |
| ASUS P8Z77-V PRO                    | 1        | 1.49%   |
| ASRock Z370 Professional Gaming i7  | 1        | 1.49%   |
| ASRock X99E-ITX/ac                  | 1        | 1.49%   |
| ASRock X570 Steel Legend            | 1        | 1.49%   |
| ASRock H91M-PLUS                    | 1        | 1.49%   |
| ASRock H270 Pro4                    | 1        | 1.49%   |
| ASRock A300M-STX                    | 1        | 1.49%   |
| Alienware Aurora R7                 | 1        | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell PowerEdge             | 6        | 8.96%   |
| Dell Precision             | 5        | 7.46%   |
| ASUS All                   | 4        | 5.97%   |
| Lenovo ThinkCentre         | 3        | 4.48%   |
| Dell OptiPlex              | 3        | 4.48%   |
| ASUS PRIME                 | 3        | 4.48%   |
| Unknown                    | 3        | 4.48%   |
| HP Z620                    | 2        | 2.99%   |
| HP Z230                    | 2        | 2.99%   |
| ASUS ROG                   | 2        | 2.99%   |
| Supermicro X7DW3           | 1        | 1.49%   |
| MSI MS-7B51                | 1        | 1.49%   |
| MSI MS-7B33                | 1        | 1.49%   |
| MSI MS-7A37                | 1        | 1.49%   |
| MSI MS-7752                | 1        | 1.49%   |
| Lenovo 10SFS03200          | 1        | 1.49%   |
| Intel H81                  | 1        | 1.49%   |
| Intel DX79SR               | 1        | 1.49%   |
| HP Z840                    | 1        | 1.49%   |
| HP Z440                    | 1        | 1.49%   |
| HP ProLiant                | 1        | 1.49%   |
| HP EliteDesk               | 1        | 1.49%   |
| HP 290                     | 1        | 1.49%   |
| HP 260-P020il              | 1        | 1.49%   |
| Gigabyte Z97N-WIFI         | 1        | 1.49%   |
| Gigabyte Z490              | 1        | 1.49%   |
| Gigabyte Z390              | 1        | 1.49%   |
| Gigabyte B85M-D3V-A        | 1        | 1.49%   |
| Gigabyte B75-D3V           | 1        | 1.49%   |
| Gigabyte B150-HD3          | 1        | 1.49%   |
| Gigabyte 970A-D3           | 1        | 1.49%   |
| Dell Vostro                | 1        | 1.49%   |
| Dell Studio                | 1        | 1.49%   |
| CX / Air Computers. H87-M1 | 1        | 1.49%   |
| ASUS Z10PE-D16             | 1        | 1.49%   |
| ASUS Pro                   | 1        | 1.49%   |
| ASUS P8Z77-V               | 1        | 1.49%   |
| ASRock Z370                | 1        | 1.49%   |
| ASRock X99E-ITX            | 1        | 1.49%   |
| ASRock X570                | 1        | 1.49%   |
| ASRock H91M-PLUS           | 1        | 1.49%   |
| ASRock H270                | 1        | 1.49%   |
| ASRock A300M-STX           | 1        | 1.49%   |
| Alienware Aurora           | 1        | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 14.93%  |
| 2016 | 10       | 14.93%  |
| 2017 | 9        | 13.43%  |
| 2012 | 8        | 11.94%  |
| 2019 | 6        | 8.96%   |
| 2015 | 6        | 8.96%   |
| 2013 | 6        | 8.96%   |
| 2020 | 4        | 5.97%   |
| 2014 | 2        | 2.99%   |
| 2009 | 2        | 2.99%   |
| 2022 | 1        | 1.49%   |
| 2021 | 1        | 1.49%   |
| 2011 | 1        | 1.49%   |
| 2010 | 1        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 67       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 64       | 94.12%  |
| Enabled  | 4        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 18       | 26.09%  |
| 4.01-8.0        | 11       | 15.94%  |
| 16.01-24.0      | 11       | 15.94%  |
| 8.01-16.0       | 10       | 14.49%  |
| 32.01-64.0      | 9        | 13.04%  |
| 24.01-32.0      | 7        | 10.14%  |
| More than 256.0 | 2        | 2.9%    |
| 2.01-3.0        | 1        | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 24       | 31.58%  |
| 2.01-3.0   | 19       | 25%     |
| 8.01-16.0  | 13       | 17.11%  |
| 3.01-4.0   | 9        | 11.84%  |
| 1.01-2.0   | 8        | 10.53%  |
| 24.01-32.0 | 1        | 1.32%   |
| 16.01-24.0 | 1        | 1.32%   |
| 0.51-1.0   | 1        | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 33.8%   |
| 1      | 17       | 23.94%  |
| 3      | 10       | 14.08%  |
| 5      | 8        | 11.27%  |
| 4      | 6        | 8.45%   |
| 12     | 3        | 4.23%   |
| 8      | 2        | 2.82%   |
| 6      | 1        | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 55.88%  |
| Yes       | 30       | 44.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 55.22%  |
| Yes       | 30       | 44.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 64.18%  |
| Yes       | 24       | 35.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 13       | 19.4%   |
| Germany      | 9        | 13.43%  |
| UK           | 5        | 7.46%   |
| Czechia      | 5        | 7.46%   |
| India        | 4        | 5.97%   |
| Russia       | 3        | 4.48%   |
| Canada       | 3        | 4.48%   |
| Ukraine      | 2        | 2.99%   |
| South Korea  | 2        | 2.99%   |
| Poland       | 2        | 2.99%   |
| Italy        | 2        | 2.99%   |
| Argentina    | 2        | 2.99%   |
| Turkmenistan | 1        | 1.49%   |
| Switzerland  | 1        | 1.49%   |
| Sweden       | 1        | 1.49%   |
| Spain        | 1        | 1.49%   |
| New Zealand  | 1        | 1.49%   |
| Netherlands  | 1        | 1.49%   |
| Mexico       | 1        | 1.49%   |
| Lithuania    | 1        | 1.49%   |
| Indonesia    | 1        | 1.49%   |
| Egypt        | 1        | 1.49%   |
| China        | 1        | 1.49%   |
| Brazil       | 1        | 1.49%   |
| Belgium      | 1        | 1.49%   |
| Belarus      | 1        | 1.49%   |
| Austria      | 1        | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Langgons              | 6        | 8.57%   |
| Prague                | 4        | 5.71%   |
| Kyiv                  | 2        | 2.86%   |
| Chicago               | 2        | 2.86%   |
| Yorktown Heights      | 1        | 1.43%   |
| Yongin-si             | 1        | 1.43%   |
| Wiesbaden             | 1        | 1.43%   |
| Vienna                | 1        | 1.43%   |
| Vaglio                | 1        | 1.43%   |
| Toronto               | 1        | 1.43%   |
| Tiruchi               | 1        | 1.43%   |
| Tauranga              | 1        | 1.43%   |
| Sutton                | 1        | 1.43%   |
| Stavropol             | 1        | 1.43%   |
| Spokane               | 1        | 1.43%   |
| Šiauliai             | 1        | 1.43%   |
| Saratov               | 1        | 1.43%   |
| San Jose              | 1        | 1.43%   |
| San Fernando          | 1        | 1.43%   |
| Salvador              | 1        | 1.43%   |
| Saltillo              | 1        | 1.43%   |
| Rosario               | 1        | 1.43%   |
| Rensselaer            | 1        | 1.43%   |
| Reading               | 1        | 1.43%   |
| Pernis                | 1        | 1.43%   |
| Paracuellos de Jarama | 1        | 1.43%   |
| Musselburgh           | 1        | 1.43%   |
| Montreal              | 1        | 1.43%   |
| Mississauga           | 1        | 1.43%   |
| Minsk                 | 1        | 1.43%   |
| Milwaukee             | 1        | 1.43%   |
| Milan                 | 1        | 1.43%   |
| Lodz                  | 1        | 1.43%   |
| Leuven                | 1        | 1.43%   |
| Langfang              | 1        | 1.43%   |
| Kielce                | 1        | 1.43%   |
| Inowlodz              | 1        | 1.43%   |
| Huddersfield          | 1        | 1.43%   |
| Holly Springs         | 1        | 1.43%   |
| Gyami                 | 1        | 1.43%   |
| Gothenburg            | 1        | 1.43%   |
| Ghaziabad             | 1        | 1.43%   |
| Gangnam-gu            | 1        | 1.43%   |
| Ernakulam             | 1        | 1.43%   |
| Dobrany               | 1        | 1.43%   |
| Dimitrovgrad          | 1        | 1.43%   |
| Didcot                | 1        | 1.43%   |
| Des Moines            | 1        | 1.43%   |
| Corpus Christi        | 1        | 1.43%   |
| Chassell              | 1        | 1.43%   |
| Cairo                 | 1        | 1.43%   |
| Buenos Aires          | 1        | 1.43%   |
| Bonn                  | 1        | 1.43%   |
| Bethlehem             | 1        | 1.43%   |
| Berlin                | 1        | 1.43%   |
| Bengaluru             | 1        | 1.43%   |
| Bandung               | 1        | 1.43%   |
| Aurora                | 1        | 1.43%   |
| Albuquerque           | 1        | 1.43%   |
| Albuccione            | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 56     | 18.84%  |
| WDC                 | 24       | 48     | 17.39%  |
| Samsung Electronics | 14       | 27     | 10.14%  |
| Toshiba             | 10       | 15     | 7.25%   |
| Kingston            | 8        | 12     | 5.8%    |
| Phison              | 5        | 9      | 3.62%   |
| SanDisk             | 4        | 10     | 2.9%    |
| Hitachi             | 4        | 4      | 2.9%    |
| Dell                | 4        | 8      | 2.9%    |
| Crucial             | 4        | 7      | 2.9%    |
| SK hynix            | 3        | 5      | 2.17%   |
| Micron Technology   | 3        | 3      | 2.17%   |
| Intel               | 3        | 5      | 2.17%   |
| China               | 3        | 3      | 2.17%   |
| A-DATA Technology   | 3        | 3      | 2.17%   |
| PNY                 | 2        | 2      | 1.45%   |
| Corsair             | 2        | 5      | 1.45%   |
| XPG                 | 1        | 1      | 0.72%   |
| Western Digital     | 1        | 1      | 0.72%   |
| Unknown             | 1        | 1      | 0.72%   |
| T-FORCE             | 1        | 2      | 0.72%   |
| Silicon Motion      | 1        | 1      | 0.72%   |
| SCST_FIO            | 1        | 9      | 0.72%   |
| OCZ                 | 1        | 2      | 0.72%   |
| KingSpec            | 1        | 1      | 0.72%   |
| KingFast            | 1        | 1      | 0.72%   |
| KINGBANK            | 1        | 1      | 0.72%   |
| HPT                 | 1        | 1      | 0.72%   |
| Hoodisk             | 1        | 1      | 0.72%   |
| HGST                | 1        | 1      | 0.72%   |
| Hewlett-Packard     | 1        | 1      | 0.72%   |
| Gigabyte Technology | 1        | 1      | 0.72%   |
| Anobit              | 1        | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell MD34xx 26TB                     | 4        | 2.35%   |
| Samsung SSD 860 EVO 1TB              | 3        | 1.76%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2        | 1.18%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2        | 1.18%   |
| Toshiba NVMe SSD Drive 256GB         | 2        | 1.18%   |
| Toshiba DT01ACA200 2TB               | 2        | 1.18%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2        | 1.18%   |
| Seagate ST91000640NS 1TB             | 2        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 1.18%   |
| Seagate ST2000NX0433 2TB             | 2        | 1.18%   |
| Seagate ST2000NX0273 2TB             | 2        | 1.18%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 1.18%   |
| Seagate ST1000DM003-9YN162 1TB       | 2        | 1.18%   |
| Samsung SSD 860 EVO 500GB            | 2        | 1.18%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 1.18%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.18%   |
| Kingston SUV500120G 120GB SSD        | 2        | 1.18%   |
| Corsair Force LE SSD 240GB           | 2        | 1.18%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.59%   |
| Western Digital NVMe SSD Drive 960GB | 1        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.59%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.59%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1        | 0.59%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.59%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1        | 0.59%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1        | 0.59%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1        | 0.59%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1        | 0.59%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1        | 0.59%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.59%   |
| WDC WD50 00LPVX-00V0TT0 500GB        | 1        | 0.59%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 0.59%   |
| WDC WD40EZRZ-19GXCB0 4TB             | 1        | 0.59%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.59%   |
| WDC WD4005FZBX-00K5WB0 4TB           | 1        | 0.59%   |
| WDC WD2500BEKT-75F3T0 250GB          | 1        | 0.59%   |
| WDC WD2500AAKX-083CA1 250GB          | 1        | 0.59%   |
| WDC WD20PURZ-85GU6Y0 2TB             | 1        | 0.59%   |
| WDC WD20EARS-22MVWB0 2TB             | 1        | 0.59%   |
| WDC WD2005FBYZ-01YCBB3 2TB           | 1        | 0.59%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1        | 0.59%   |
| WDC WD2002FFSX-68PF8N0 2TB           | 1        | 0.59%   |
| WDC WD10SPSX-00A6WT0 1TB             | 1        | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1        | 0.59%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1        | 0.59%   |
| WDC WD10EZEX-75WN4A0 1TB             | 1        | 0.59%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.59%   |
| WDC WD10EALX-759BA1 1TB              | 1        | 0.59%   |
| Unknown SD/MMC/MS PRO 64GB           | 1        | 0.59%   |
| Toshiba MQ01ACF032 320GB             | 1        | 0.59%   |
| Toshiba HDWT140 4TB                  | 1        | 0.59%   |
| Toshiba HDWQ140 4TB                  | 1        | 0.59%   |
| Toshiba HDWD120 2TB                  | 1        | 0.59%   |
| Toshiba DT01ACA300 3TB               | 1        | 0.59%   |
| Toshiba DT01ACA100 1TB               | 1        | 0.59%   |
| T-FORCE 1TB                          | 1        | 0.59%   |
| SK hynix SC311 SATA 256GB SSD        | 1        | 0.59%   |
| SK hynix PC601 NVMe 512GB            | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 56     | 37.68%  |
| WDC                 | 22       | 43     | 31.88%  |
| Toshiba             | 8        | 12     | 11.59%  |
| Hitachi             | 4        | 4      | 5.8%    |
| Dell                | 4        | 8      | 5.8%    |
| Unknown             | 1        | 1      | 1.45%   |
| SCST_FIO            | 1        | 9      | 1.45%   |
| Samsung Electronics | 1        | 2      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| Hewlett-Packard     | 1        | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 15     | 20%     |
| Kingston            | 8        | 12     | 16%     |
| WDC                 | 4        | 5      | 8%      |
| Crucial             | 4        | 7      | 8%      |
| Micron Technology   | 3        | 3      | 6%      |
| China               | 3        | 3      | 6%      |
| A-DATA Technology   | 3        | 3      | 6%      |
| SK hynix            | 2        | 4      | 4%      |
| SanDisk             | 2        | 7      | 4%      |
| PNY                 | 2        | 2      | 4%      |
| Intel               | 2        | 3      | 4%      |
| Corsair             | 2        | 5      | 4%      |
| OCZ                 | 1        | 2      | 2%      |
| KingSpec            | 1        | 1      | 2%      |
| KINGBANK            | 1        | 1      | 2%      |
| Hoodisk             | 1        | 1      | 2%      |
| Anobit              | 1        | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 137    | 43.75%  |
| SSD     | 44       | 75     | 39.29%  |
| NVMe    | 16       | 32     | 14.29%  |
| Unknown | 3        | 4      | 2.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 197    | 71.91%  |
| NVMe | 16       | 32     | 17.98%  |
| SAS  | 9        | 19     | 10.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 44       | 89     | 41.12%  |
| 0.51-1.0   | 30       | 49     | 28.04%  |
| 1.01-2.0   | 18       | 42     | 16.82%  |
| 3.01-4.0   | 7        | 13     | 6.54%   |
| 20.01-50.0 | 4        | 8      | 3.74%   |
| 4.01-10.0  | 3        | 10     | 2.8%    |
| 2.01-3.0   | 1        | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 14       | 19.44%  |
| 501-1000       | 12       | 16.67%  |
| 251-500        | 11       | 15.28%  |
| More than 3000 | 10       | 13.89%  |
| Unknown        | 9        | 12.5%   |
| 1001-2000      | 8        | 11.11%  |
| 2001-3000      | 5        | 6.94%   |
| 51-100         | 3        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 17       | 21.79%  |
| 101-250        | 12       | 15.38%  |
| 1-20           | 12       | 15.38%  |
| 51-100         | 10       | 12.82%  |
| Unknown        | 9        | 11.54%  |
| 1001-2000      | 5        | 6.41%   |
| 251-500        | 4        | 5.13%   |
| 501-1000       | 4        | 5.13%   |
| More than 3000 | 3        | 3.85%   |
| 2001-3000      | 2        | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD10EALX-759BA1 1TB                  | 1        | 2      | 16.67%  |
| Seagate ST91000640NS 1TB                 | 1        | 2      | 16.67%  |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 16.67%  |
| Micron Technology M510_2.5 7MM 256GB SSD | 1        | 1      | 16.67%  |
| Hitachi HDS722020ALA330 2TB              | 1        | 1      | 16.67%  |
| A-DATA Technology SU800NS38 256GB SSD    | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 2        | 3      | 33.33%  |
| WDC               | 1        | 2      | 16.67%  |
| Micron Technology | 1        | 1      | 16.67%  |
| Hitachi           | 1        | 1      | 16.67%  |
| A-DATA Technology | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 3      | 50%     |
| WDC     | 1        | 2      | 25%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 6      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Detected | 38       | 146    | 51.35%  |
| Works    | 30       | 94     | 40.54%  |
| Malfunc  | 6        | 8      | 8.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 58       | 55.77%  |
| Samsung Electronics          | 8        | 7.69%   |
| Broadcom / LSI               | 8        | 7.69%   |
| AMD                          | 8        | 7.69%   |
| Phison Electronics           | 5        | 4.81%   |
| ASMedia Technology           | 4        | 3.85%   |
| Marvell Technology Group     | 3        | 2.88%   |
| Toshiba America Info Systems | 2        | 1.92%   |
| LSI Logic / Symbios Logic    | 2        | 1.92%   |
| Western Digital              | 1        | 0.96%   |
| SK hynix                     | 1        | 0.96%   |
| Silicon Motion               | 1        | 0.96%   |
| SanDisk                      | 1        | 0.96%   |
| HighPoint Technologies       | 1        | 0.96%   |
| ADATA Technology             | 1        | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 11       | 8.27%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 10       | 7.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 6.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 4.51%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 6        | 4.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.76%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.01%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 4        | 3.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 3.01%   |
| Phison E12 NVMe Controller                                                              | 3        | 2.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 2.26%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.26%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2        | 1.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.5%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 1.5%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 1.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.5%    |
| Western Digital Ultrastar DC SN640 NVMe SSD                                             | 1        | 0.75%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.75%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.75%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.75%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 0.75%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 0.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.75%   |
| Intel SSD 660P Series                                                                   | 1        | 0.75%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.75%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 0.75%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.75%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 0.75%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.75%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.75%   |
| HighPoint RocketRAID 2720 SAS Controller                                                | 1        | 0.75%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.75%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 0.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 59       | 56.73%  |
| NVMe | 17       | 16.35%  |
| RAID | 15       | 14.42%  |
| SAS  | 8        | 7.69%   |
| IDE  | 5        | 4.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 59       | 88.06%  |
| AMD    | 8        | 11.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 5.97%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 4.48%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 2        | 2.99%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2        | 2.99%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 2        | 2.99%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 2.99%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 2.99%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 2.99%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 2.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.99%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 1.49%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.49%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 1.49%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 1.49%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz         | 1        | 1.49%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz         | 1        | 1.49%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 1.49%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.49%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1        | 1.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.49%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.49%   |
| Intel Core i7 CPU X 990 @ 3.47GHz           | 1        | 1.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.49%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.49%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.49%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.49%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.49%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.49%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1.49%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 1.49%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.49%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 1        | 1.49%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.49%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 1        | 1.49%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 1.49%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 1.49%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.49%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 1.49%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 1.49%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 1.49%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 1.49%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 19       | 28.36%  |
| Intel Core i7      | 16       | 23.88%  |
| Intel Core i5      | 13       | 19.4%   |
| Intel Core i3      | 7        | 10.45%  |
| AMD Ryzen 9        | 3        | 4.48%   |
| Intel Pentium Gold | 2        | 2.99%   |
| AMD Ryzen 7        | 2        | 2.99%   |
| Intel Core 2 Duo   | 1        | 1.49%   |
| Intel Celeron      | 1        | 1.49%   |
| AMD Ryzen 5        | 1        | 1.49%   |
| AMD Ryzen 3        | 1        | 1.49%   |
| AMD FX             | 1        | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 38.81%  |
| 2      | 11       | 16.42%  |
| 6      | 10       | 14.93%  |
| 12     | 7        | 10.45%  |
| 8      | 6        | 8.96%   |
| 16     | 4        | 5.97%   |
| 36     | 1        | 1.49%   |
| 24     | 1        | 1.49%   |
| 20     | 1        | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 57       | 85.07%  |
| 2      | 10       | 14.93%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 70.59%  |
| 1      | 20       | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 97.01%  |
| Unknown        | 2        | 2.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 17.91%  |
| 0x906ea    | 8        | 11.94%  |
| 0x306f2    | 8        | 11.94%  |
| 0x306a9    | 6        | 8.96%   |
| 0x906e9    | 3        | 4.48%   |
| 0x506e3    | 3        | 4.48%   |
| 0x406f1    | 3        | 4.48%   |
| 0x206d7    | 3        | 4.48%   |
| 0x906ed    | 2        | 2.99%   |
| 0x08701021 | 2        | 2.99%   |
| Unknown    | 2        | 2.99%   |
| 0xa0655    | 1        | 1.49%   |
| 0x906eb    | 1        | 1.49%   |
| 0x906c0    | 1        | 1.49%   |
| 0x806e9    | 1        | 1.49%   |
| 0x306e4    | 1        | 1.49%   |
| 0x206c2    | 1        | 1.49%   |
| 0x206a7    | 1        | 1.49%   |
| 0x1067a    | 1        | 1.49%   |
| 0x10676    | 1        | 1.49%   |
| 0x08701013 | 1        | 1.49%   |
| 0x08108102 | 1        | 1.49%   |
| 0x0810100b | 1        | 1.49%   |
| 0x08001138 | 1        | 1.49%   |
| 0x08001137 | 1        | 1.49%   |
| 0x06000852 | 1        | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 21       | 31.34%  |
| KabyLake    | 15       | 22.39%  |
| IvyBridge   | 8        | 11.94%  |
| SandyBridge | 4        | 5.97%   |
| Zen 2       | 3        | 4.48%   |
| Zen         | 3        | 4.48%   |
| Skylake     | 3        | 4.48%   |
| Broadwell   | 3        | 4.48%   |
| Penryn      | 2        | 2.99%   |
| Zen+        | 1        | 1.49%   |
| Westmere    | 1        | 1.49%   |
| Tremont     | 1        | 1.49%   |
| Piledriver  | 1        | 1.49%   |
| CometLake   | 1        | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 36       | 46.75%  |
| Intel                      | 25       | 32.47%  |
| AMD                        | 10       | 12.99%  |
| Matrox Electronics Systems | 6        | 7.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 7.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.75%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 2.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.5%    |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.5%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.5%    |
| Intel HD Graphics 630                                                       | 2        | 2.5%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.25%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.25%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.25%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.25%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.25%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.25%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.25%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.25%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.25%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.25%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.25%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.25%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.25%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.25%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.25%   |
| Nvidia GF119 [NVS 315]                                                      | 1        | 1.25%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.25%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.25%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.25%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.25%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.25%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.25%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.25%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.25%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.25%   |
| Intel Iris Plus Graphics 640                                                | 1        | 1.25%   |
| Intel HD Graphics 530                                                       | 1        | 1.25%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.25%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.25%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.25%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.25%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.25%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.25%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.25%   |
| AMD ES1000                                                                  | 1        | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.25%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 32       | 47.06%  |
| 1 x Intel      | 16       | 23.53%  |
| 1 x AMD        | 7        | 10.29%  |
| 1 x Matrox     | 6        | 8.82%   |
| 2 x Nvidia     | 2        | 2.94%   |
| Intel + Nvidia | 2        | 2.94%   |
| Intel + AMD    | 2        | 2.94%   |
| 2 x AMD        | 1        | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 44       | 64.71%  |
| Proprietary | 17       | 25%     |
| Unknown     | 7        | 10.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 43.66%  |
| 1.01-2.0   | 12       | 16.9%   |
| 7.01-8.0   | 7        | 9.86%   |
| 0.51-1.0   | 7        | 9.86%   |
| 3.01-4.0   | 4        | 5.63%   |
| 5.01-6.0   | 3        | 4.23%   |
| 2.01-3.0   | 3        | 4.23%   |
| 0.01-0.5   | 3        | 4.23%   |
| 8.01-16.0  | 1        | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 14       | 20%     |
| Samsung Electronics  | 12       | 17.14%  |
| Goldstar             | 9        | 12.86%  |
| Lenovo               | 5        | 7.14%   |
| Hewlett-Packard      | 5        | 7.14%   |
| BenQ                 | 3        | 4.29%   |
| Ancor Communications | 3        | 4.29%   |
| ViewSonic            | 2        | 2.86%   |
| Philips              | 2        | 2.86%   |
| Lenovo Group Limited | 2        | 2.86%   |
| Iiyama               | 2        | 2.86%   |
| Gigabyte Technology  | 2        | 2.86%   |
| Eizo                 | 2        | 2.86%   |
| Acer                 | 2        | 2.86%   |
| STD                  | 1        | 1.43%   |
| OUT                  | 1        | 1.43%   |
| LG Electronics       | 1        | 1.43%   |
| Insignia             | 1        | 1.43%   |
| Unknown              | 1        | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell IDRAC DEL0001 1280x1024                                           | 6        | 7.41%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 2.47%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 2.47%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch               | 2        | 2.47%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 2.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 2.47%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 1.23%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 1.23%   |
| STD LED STD0110 1366x768 410x230mm 18.5-inch                           | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 1.23%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 1.23%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 440x250mm 19.9-inch       | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 1.23%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 1.23%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 1.23%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 1.23%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 1        | 1.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.23%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.23%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 1.23%   |
| LG Electronics LCD Monitor W2486 1920x1080                             | 1        | 1.23%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch               | 1        | 1.23%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                 | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                 | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                 | 1        | 1.23%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10                           | 1        | 1.23%   |
| Insignia HDMI BBY4000 1920x1080 1152x648mm 52.0-inch                   | 1        | 1.23%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch           | 1        | 1.23%   |
| Hewlett-Packard LCD Monitor LA2306                                     | 1        | 1.23%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch          | 1        | 1.23%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch             | 1        | 1.23%   |
| Hewlett-Packard E233 HPN3460 1920x1080 510x290mm 23.1-inch             | 1        | 1.23%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 1        | 1.23%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch               | 1        | 1.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1        | 1.23%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch               | 1        | 1.23%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                | 1        | 1.23%   |
| Goldstar 26LB75  GSM5673 1920x1080 700x390mm 31.5-inch                 | 1        | 1.23%   |
| Goldstar 24GM77 GSM5A90 1920x1080 531x298mm 24.0-inch                  | 1        | 1.23%   |
| Goldstar 24GM77 GSM5A8F 1920x1080 531x298mm 24.0-inch                  | 1        | 1.23%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch       | 1        | 1.23%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch        | 1        | 1.23%   |
| Eizo LCD Monitor EV2416W                                               | 1        | 1.23%   |
| Eizo CS2420 ENC2956 1920x1200 519x324mm 24.1-inch                      | 1        | 1.23%   |
| Dell UP2716D DEL40DD 2560x1440 597x336mm 27.0-inch                     | 1        | 1.23%   |
| Dell U2917W DEL40F9 2560x1080 673x284mm 28.8-inch                      | 1        | 1.23%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                      | 1        | 1.23%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                     | 1        | 1.23%   |
| Dell S2719H DELD0CD 1920x1080 598x336mm 27.0-inch                      | 1        | 1.23%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                      | 1        | 1.23%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                      | 1        | 1.23%   |
| Dell LNKG H2VA001 LNKA001 1920x1080 880x500mm 39.8-inch                | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 44.29%  |
| 1280x1024 (SXGA)   | 6        | 8.57%   |
| 3840x2160 (4K)     | 5        | 7.14%   |
| 2560x1440 (QHD)    | 5        | 7.14%   |
| 3840x1080          | 3        | 4.29%   |
| 3440x1440          | 3        | 4.29%   |
| 2560x1080          | 3        | 4.29%   |
| 1600x900 (HD+)     | 3        | 4.29%   |
| Unknown            | 3        | 4.29%   |
| 9600x2160          | 1        | 1.43%   |
| 7680x2160          | 1        | 1.43%   |
| 3840x1200          | 1        | 1.43%   |
| 1920x1200 (WUXGA)  | 1        | 1.43%   |
| 1680x1050 (WSXGA+) | 1        | 1.43%   |
| 1440x900 (WXGA+)   | 1        | 1.43%   |
| 1280x768           | 1        | 1.43%   |
| 1280x720 (HD)      | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 22.22%  |
| 23      | 10       | 13.89%  |
| 24      | 8        | 11.11%  |
| 21      | 8        | 11.11%  |
| 27      | 7        | 9.72%   |
| 31      | 4        | 5.56%   |
| 54      | 3        | 4.17%   |
| 34      | 3        | 4.17%   |
| 20      | 3        | 4.17%   |
| 47      | 2        | 2.78%   |
| 18      | 2        | 2.78%   |
| 64      | 1        | 1.39%   |
| 40      | 1        | 1.39%   |
| 39      | 1        | 1.39%   |
| 28      | 1        | 1.39%   |
| 25      | 1        | 1.39%   |
| 16      | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 34.78%  |
| Unknown     | 16       | 23.19%  |
| 401-500     | 12       | 17.39%  |
| 1001-1500   | 6        | 8.7%    |
| 601-700     | 5        | 7.25%   |
| 701-800     | 3        | 4.35%   |
| 801-900     | 2        | 2.9%    |
| 301-350     | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 62.9%   |
| Unknown | 8        | 12.9%   |
| 5/4     | 6        | 9.68%   |
| 21/9    | 4        | 6.45%   |
| 16/10   | 4        | 6.45%   |
| 4/3     | 1        | 1.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 30.43%  |
| Unknown        | 16       | 23.19%  |
| 351-500        | 7        | 10.14%  |
| 301-350        | 7        | 10.14%  |
| More than 1000 | 4        | 5.8%    |
| 251-300        | 4        | 5.8%    |
| 151-200        | 4        | 5.8%    |
| 501-1000       | 4        | 5.8%    |
| 141-150        | 1        | 1.45%   |
| 131-140        | 1        | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 34       | 50%     |
| Unknown | 16       | 23.53%  |
| 101-120 | 10       | 14.71%  |
| 1-50    | 5        | 7.35%   |
| 161-240 | 2        | 2.94%   |
| 121-160 | 1        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 71.83%  |
| 2     | 8        | 11.27%  |
| 0     | 7        | 9.86%   |
| 3     | 5        | 7.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 43       | 43%     |
| Realtek Semiconductor    | 26       | 26%     |
| Broadcom                 | 9        | 9%      |
| Qualcomm Atheros         | 7        | 7%      |
| Ralink Technology        | 2        | 2%      |
| Dell                     | 2        | 2%      |
| ASIX Electronics         | 2        | 2%      |
| Ralink                   | 1        | 1%      |
| Microchip Technology     | 1        | 1%      |
| Micro Star International | 1        | 1%      |
| MediaTek                 | 1        | 1%      |
| Huawei Technologies      | 1        | 1%      |
| D-Link                   | 1        | 1%      |
| Broadcom Limited         | 1        | 1%      |
| Arduino SA               | 1        | 1%      |
| Aquantia                 | 1        | 1%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21       | 16.03%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 5.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.58%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.82%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 3.05%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 3.05%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 3.05%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 3.05%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.29%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 2.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 2.29%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 2.29%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.53%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 1.53%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.53%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.53%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.53%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.53%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 1.53%   |
| Dell iDRAC Virtual NIC                                                        | 2        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.76%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.76%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.76%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.76%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.76%   |
| Microchip TrueRNG                                                             | 1        | 0.76%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 0.76%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 0.76%   |
| Intel Wireless 7260                                                           | 1        | 0.76%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1        | 0.76%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.76%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.76%   |
| Huawei Modem/Networkcard                                                      | 1        | 0.76%   |
| D-Link 802.11n WLAN Adapter                                                   | 1        | 0.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.76%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 0.76%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 30%     |
| Qualcomm Atheros         | 6        | 20%     |
| Realtek Semiconductor    | 5        | 16.67%  |
| Broadcom                 | 4        | 13.33%  |
| Ralink Technology        | 2        | 6.67%   |
| Ralink                   | 1        | 3.33%   |
| Micro Star International | 1        | 3.33%   |
| MediaTek                 | 1        | 3.33%   |
| D-Link                   | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 10%     |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 6.67%   |
| Intel Wireless-AC 9260                                                     | 2        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 3.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 3.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 3.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 3.33%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 3.33%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 3.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.33%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.33%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 3.33%   |
| Intel Wireless 7260                                                        | 1        | 3.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 3.33%   |
| D-Link 802.11n WLAN Adapter                                                | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 43       | 55.13%  |
| Realtek Semiconductor | 24       | 30.77%  |
| Broadcom              | 5        | 6.41%   |
| Qualcomm Atheros      | 2        | 2.56%   |
| ASIX Electronics      | 2        | 2.56%   |
| Broadcom Limited      | 1        | 1.28%   |
| Aquantia              | 1        | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21       | 21.88%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 7.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 6.25%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 5.21%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 4.17%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.17%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 4.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 4.17%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.13%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 2.08%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.08%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.08%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 2.08%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 2.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.04%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.04%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.04%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.04%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.04%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.04%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 65.69%  |
| WiFi     | 30       | 29.41%  |
| Modem    | 3        | 2.94%   |
| Unknown  | 2        | 1.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 83.82%  |
| WiFi     | 11       | 16.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 42.65%  |
| 2     | 18       | 26.47%  |
| 3     | 11       | 16.18%  |
| 6     | 5        | 7.35%   |
| 4     | 4        | 5.88%   |
| 5     | 1        | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 88.24%  |
| Yes  | 8        | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 29.17%  |
| Cambridge Silicon Radio         | 7        | 29.17%  |
| ASUSTek Computer                | 3        | 12.5%   |
| Realtek Semiconductor           | 2        | 8.33%   |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| Micro Star International        | 1        | 4.17%   |
| IMC Networks                    | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 29.17%  |
| Realtek Bluetooth Radio                               | 2        | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 8.33%   |
| ASUS BCM20702A0                                       | 2        | 8.33%   |
| Micro Star International Bluetooth Device             | 1        | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.17%   |
| Intel Bluetooth wireless interface                    | 1        | 4.17%   |
| Intel Bluetooth Device                                | 1        | 4.17%   |
| Intel AX201 Bluetooth                                 | 1        | 4.17%   |
| Intel AX200 Bluetooth                                 | 1        | 4.17%   |
| IMC Networks BCM20702A0                               | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.17%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 49       | 42.98%  |
| Nvidia                                       | 34       | 29.82%  |
| AMD                                          | 13       | 11.4%   |
| Lenovo                                       | 3        | 2.63%   |
| Creative Labs                                | 3        | 2.63%   |
| Texas Instruments                            | 2        | 1.75%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.88%   |
| Tenx Technology                              | 1        | 0.88%   |
| Sennheiser Communications                    | 1        | 0.88%   |
| RODE Microphones                             | 1        | 0.88%   |
| Plantronics                                  | 1        | 0.88%   |
| Logitech                                     | 1        | 0.88%   |
| JMTek                                        | 1        | 0.88%   |
| Dynex                                        | 1        | 0.88%   |
| Creative Technology                          | 1        | 0.88%   |
| ASUSTek Computer                             | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 7.94%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 6.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 4.76%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6        | 4.76%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 3.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 3.97%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 3.17%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 3.17%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.38%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 2.38%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 3        | 2.38%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.38%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2        | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 1.59%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 1.59%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 0.79%   |
| Tenx Technology USB AUDIO                                                         | 1        | 0.79%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                         | 1        | 0.79%   |
| RODE Microphones RODE NT-USB                                                      | 1        | 0.79%   |
| Plantronics BT600                                                                 | 1        | 0.79%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.79%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.79%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.79%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1        | 0.79%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.79%   |
| Logitech H570e Mono                                                               | 1        | 0.79%   |
| JMTek USB Speaker                                                                 | 1        | 0.79%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1        | 0.79%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.79%   |
| Dynex USB MIC Device                                                              | 1        | 0.79%   |
| Creative Technology Sound Blaster Tactic(3D) Alpha                                | 1        | 0.79%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1        | 0.79%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 1        | 0.79%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                            | 1        | 0.79%   |
| ASUSTek Computer Xonar U3 sound card                                              | 1        | 0.79%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 1        | 0.79%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 0.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 20.51%  |
| SK hynix            | 7        | 17.95%  |
| Micron Technology   | 7        | 17.95%  |
| Crucial             | 6        | 15.38%  |
| Kingston            | 3        | 7.69%   |
| Corsair             | 3        | 7.69%   |
| Unknown (0x0205)    | 1        | 2.56%   |
| Unknown             | 1        | 2.56%   |
| Transcend           | 1        | 2.56%   |
| Patriot             | 1        | 2.56%   |
| Goodram             | 1        | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s    | 2        | 4.55%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16384MB DIMM DDR4 2133MT/s    | 2        | 4.55%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s     | 2        | 4.55%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s        | 2        | 4.55%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s      | 2        | 4.55%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1        | 2.27%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s          | 1        | 2.27%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s            | 1        | 2.27%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s       | 1        | 2.27%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s     | 1        | 2.27%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 2.27%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s        | 1        | 2.27%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                   | 1        | 2.27%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 1        | 2.27%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                  | 1        | 2.27%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s        | 1        | 2.27%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 1        | 2.27%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s         | 1        | 2.27%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s         | 1        | 2.27%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s         | 1        | 2.27%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s      | 1        | 2.27%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s            | 1        | 2.27%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 2.27%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s         | 1        | 2.27%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s        | 1        | 2.27%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8192MB DIMM DDR3 1600MT/s      | 1        | 2.27%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s         | 1        | 2.27%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 2.27%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s        | 1        | 2.27%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s     | 1        | 2.27%   |
| Goodram RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.27%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s       | 1        | 2.27%   |
| Crucial RAM CT4G4DFS824A.M8FG 4096MB DIMM DDR4 2400MT/s     | 1        | 2.27%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16384MB DIMM DDR4 2933MT/s | 1        | 2.27%   |
| Crucial RAM BLT4G3D1608ET3LX0. 4GB DIMM DDR3 1600MT/s       | 1        | 2.27%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s      | 1        | 2.27%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s       | 1        | 2.27%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s       | 1        | 2.27%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s    | 1        | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 18       | 52.94%  |
| DDR3   | 9        | 26.47%  |
| SDRAM  | 3        | 8.82%   |
| DRAM   | 2        | 5.88%   |
| LPDDR4 | 1        | 2.94%   |
| DDR2   | 1        | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 30       | 90.91%  |
| SODIMM       | 1        | 3.03%   |
| Row Of Chips | 1        | 3.03%   |
| RIMM         | 1        | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 12       | 32.43%  |
| 4096  | 10       | 27.03%  |
| 8192  | 9        | 24.32%  |
| 32768 | 3        | 8.11%   |
| 2048  | 2        | 5.41%   |
| 1024  | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 8        | 22.22%  |
| 1600  | 8        | 22.22%  |
| 2133  | 6        | 16.67%  |
| 2667  | 3        | 8.33%   |
| 3600  | 2        | 5.56%   |
| 2933  | 2        | 5.56%   |
| 1333  | 2        | 5.56%   |
| 3200  | 1        | 2.78%   |
| 2666  | 1        | 2.78%   |
| 2048  | 1        | 2.78%   |
| 1867  | 1        | 2.78%   |
| 800   | 1        | 2.78%   |

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
| Canon LiDE 300                   | 1        | 25%     |
| Canon E560 series                | 1        | 25%     |
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
| Unknown                | 3        | 21.43%  |
| Logitech               | 3        | 21.43%  |
| Generalplus Technology | 2        | 14.29%  |
| Samsung Electronics    | 1        | 7.14%   |
| Ruision                | 1        | 7.14%   |
| Microsoft              | 1        | 7.14%   |
| Jieli Technology       | 1        | 7.14%   |
| IMC Networks           | 1        | 7.14%   |
| ARC International      | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown FULL HD 1080P Webcam   | 3        | 21.43%  |
| Generalplus WEB CAM            | 2        | 14.29%  |
| Samsung Galaxy A5 (MTP)        | 1        | 7.14%   |
| Ruision UVC Camera             | 1        | 7.14%   |
| Microsoft LifeCam HD-3000      | 1        | 7.14%   |
| Logitech Webcam C270           | 1        | 7.14%   |
| Logitech Webcam C250           | 1        | 7.14%   |
| Logitech HD Webcam C910        | 1        | 7.14%   |
| Jieli USB PHY 2.0              | 1        | 7.14%   |
| IMC Networks Integrated Camera | 1        | 7.14%   |
| ARC International Camera       | 1        | 7.14%   |

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
| 0     | 47       | 69.12%  |
| 1     | 10       | 14.71%  |
| 2     | 9        | 13.24%  |
| 5     | 1        | 1.47%   |
| 3     | 1        | 1.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 13       | 38.24%  |
| Graphics card            | 7        | 20.59%  |
| Communication controller | 7        | 20.59%  |
| Net/wireless             | 4        | 11.76%  |
| Storage/ide              | 1        | 2.94%   |
| Sound                    | 1        | 2.94%   |
| Bluetooth                | 1        | 2.94%   |

