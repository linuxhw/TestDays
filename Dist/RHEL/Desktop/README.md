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

Total: 104

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z590I VISION D              | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| Acer          | Aspire XC-330               | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
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
| RHEL 8 | 52       | 75.36%  |
| RHEL 7 | 12       | 17.39%  |
| RHEL 9 | 5        | 7.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 69       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 8.54%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 7.32%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 4.88%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 4.88%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 4.88%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 3.66%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 3.66%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 3.66%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 3.66%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 3.66%   |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 3.66%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 2.44%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 2.44%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 2.44%   |
| 4.18.0-193.el8.x86_64        | 2        | 2.44%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 2.44%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 2.44%   |
| 4.18.0-147.el8.x86_64        | 2        | 2.44%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 1.22%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 1.22%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.22%   |
| 4.19.150                     | 1        | 1.22%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.22%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 1.22%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1        | 1.22%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.22%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.22%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.22%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.22%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.22%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.22%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.22%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1        | 1.22%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.22%   |
| 3.10.0-957.5.1.el7.x86_64    | 1        | 1.22%   |
| 3.10.0-957.1.3.el7.x86_64    | 1        | 1.22%   |
| 3.10.0-862.9.1.el7.x86_64    | 1        | 1.22%   |
| 3.10.0-862.11.6.el7.x86_64   | 1        | 1.22%   |
| 3.10.0-693.11.6.el7.x86_64   | 1        | 1.22%   |
| 3.10.0-1160.45.1.el7.x86_64  | 1        | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 50       | 72.46%  |
| 3.10.0   | 12       | 17.39%  |
| 5.14.0   | 5        | 7.25%   |
| 5.10.6   | 1        | 1.45%   |
| 4.19.150 | 1        | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 50       | 72.46%  |
| 3.10    | 12       | 17.39%  |
| 5.14    | 5        | 7.25%   |
| 5.10    | 1        | 1.45%   |
| 4.19    | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 69       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 49       | 68.06%  |
| Unknown       | 14       | 19.44%  |
| GNOME Classic | 4        | 5.56%   |
| KDE5          | 2        | 2.78%   |
| KDE           | 2        | 2.78%   |
| MATE          | 1        | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 40       | 55.56%  |
| Wayland | 25       | 34.72%  |
| Unknown | 7        | 9.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 54       | 75%     |
| GDM     | 17       | 23.61%  |
| LightDM | 1        | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 35       | 50%     |
| Unknown | 13       | 18.57%  |
| en_GB   | 5        | 7.14%   |
| ru_RU   | 3        | 4.29%   |
| en_IN   | 3        | 4.29%   |
| pl_PL   | 2        | 2.86%   |
| es_AR   | 2        | 2.86%   |
| de_DE   | 2        | 2.86%   |
| ko_KR   | 1        | 1.43%   |
| es_MX   | 1        | 1.43%   |
| es_ES   | 1        | 1.43%   |
| en_NZ   | 1        | 1.43%   |
| cs_CZ   | 1        | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 41       | 58.57%  |
| BIOS | 29       | 41.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 63       | 90%     |
| Ext4    | 4        | 5.71%   |
| Unknown | 3        | 4.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 55.56%  |
| GPT     | 20       | 27.78%  |
| MBR     | 12       | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 77.14%  |
| Yes       | 16       | 22.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 90%     |
| Yes       | 7        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 16       | 23.19%  |
| ASUSTek Computer    | 12       | 17.39%  |
| Hewlett-Packard     | 10       | 14.49%  |
| Gigabyte Technology | 8        | 11.59%  |
| ASRock              | 6        | 8.7%    |
| MSI                 | 4        | 5.8%    |
| Lenovo              | 4        | 5.8%    |
| Unknown             | 3        | 4.35%   |
| Intel               | 2        | 2.9%    |
| Supermicro          | 1        | 1.45%   |
| CX / Air Computers. | 1        | 1.45%   |
| Alienware           | 1        | 1.45%   |
| Acer                | 1        | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 8.7%    |
| ASUS All Series                     | 4        | 5.8%    |
| Unknown                             | 3        | 4.35%   |
| HP Z620 Workstation                 | 2        | 2.9%    |
| Dell OptiPlex 9020                  | 2        | 2.9%    |
| Supermicro X7DW3                    | 1        | 1.45%   |
| MSI MS-7B51                         | 1        | 1.45%   |
| MSI MS-7B33                         | 1        | 1.45%   |
| MSI MS-7A37                         | 1        | 1.45%   |
| MSI MS-7752                         | 1        | 1.45%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.45%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.45%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.45%   |
| Lenovo 10SFS03200                   | 1        | 1.45%   |
| Intel H81                           | 1        | 1.45%   |
| Intel DX79SR AAG57199-200           | 1        | 1.45%   |
| HP Z840 Workstation                 | 1        | 1.45%   |
| HP Z440 Workstation                 | 1        | 1.45%   |
| HP Z230 Tower Workstation           | 1        | 1.45%   |
| HP Z230 SFF Workstation             | 1        | 1.45%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.45%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.45%   |
| HP 290 G1 SFF Business PC           | 1        | 1.45%   |
| HP 260-P020il                       | 1        | 1.45%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.45%   |
| Gigabyte Z590I VISION D             | 1        | 1.45%   |
| Gigabyte Z490 GAMING X              | 1        | 1.45%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.45%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.45%   |
| Gigabyte B75-D3V                    | 1        | 1.45%   |
| Gigabyte B150-HD3                   | 1        | 1.45%   |
| Gigabyte 970A-D3                    | 1        | 1.45%   |
| Dell Vostro 270                     | 1        | 1.45%   |
| Dell Studio XPS 9100                | 1        | 1.45%   |
| Dell Precision Tower 5810           | 1        | 1.45%   |
| Dell Precision Tower 3620           | 1        | 1.45%   |
| Dell Precision Tower 3420           | 1        | 1.45%   |
| Dell Precision T7600                | 1        | 1.45%   |
| Dell Precision 3630 Tower           | 1        | 1.45%   |
| Dell OptiPlex 760                   | 1        | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell PowerEdge             | 6        | 8.7%    |
| Dell Precision             | 5        | 7.25%   |
| ASUS All                   | 4        | 5.8%    |
| Lenovo ThinkCentre         | 3        | 4.35%   |
| Dell OptiPlex              | 3        | 4.35%   |
| ASUS PRIME                 | 3        | 4.35%   |
| Unknown                    | 3        | 4.35%   |
| HP Z620                    | 2        | 2.9%    |
| HP Z230                    | 2        | 2.9%    |
| ASUS ROG                   | 2        | 2.9%    |
| Supermicro X7DW3           | 1        | 1.45%   |
| MSI MS-7B51                | 1        | 1.45%   |
| MSI MS-7B33                | 1        | 1.45%   |
| MSI MS-7A37                | 1        | 1.45%   |
| MSI MS-7752                | 1        | 1.45%   |
| Lenovo 10SFS03200          | 1        | 1.45%   |
| Intel H81                  | 1        | 1.45%   |
| Intel DX79SR               | 1        | 1.45%   |
| HP Z840                    | 1        | 1.45%   |
| HP Z440                    | 1        | 1.45%   |
| HP ProLiant                | 1        | 1.45%   |
| HP EliteDesk               | 1        | 1.45%   |
| HP 290                     | 1        | 1.45%   |
| HP 260-P020il              | 1        | 1.45%   |
| Gigabyte Z97N-WIFI         | 1        | 1.45%   |
| Gigabyte Z590I             | 1        | 1.45%   |
| Gigabyte Z490              | 1        | 1.45%   |
| Gigabyte Z390              | 1        | 1.45%   |
| Gigabyte B85M-D3V-A        | 1        | 1.45%   |
| Gigabyte B75-D3V           | 1        | 1.45%   |
| Gigabyte B150-HD3          | 1        | 1.45%   |
| Gigabyte 970A-D3           | 1        | 1.45%   |
| Dell Vostro                | 1        | 1.45%   |
| Dell Studio                | 1        | 1.45%   |
| CX / Air Computers. H87-M1 | 1        | 1.45%   |
| ASUS Z10PE-D16             | 1        | 1.45%   |
| ASUS Pro                   | 1        | 1.45%   |
| ASUS P8Z77-V               | 1        | 1.45%   |
| ASRock Z370                | 1        | 1.45%   |
| ASRock X99E-ITX            | 1        | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 14.49%  |
| 2017 | 10       | 14.49%  |
| 2016 | 10       | 14.49%  |
| 2012 | 8        | 11.59%  |
| 2019 | 6        | 8.7%    |
| 2015 | 6        | 8.7%    |
| 2013 | 6        | 8.7%    |
| 2020 | 4        | 5.8%    |
| 2021 | 2        | 2.9%    |
| 2014 | 2        | 2.9%    |
| 2009 | 2        | 2.9%    |
| 2022 | 1        | 1.45%   |
| 2011 | 1        | 1.45%   |
| 2010 | 1        | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 69       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 92.86%  |
| Enabled  | 5        | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 69       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 18       | 25.35%  |
| 4.01-8.0        | 11       | 15.49%  |
| 16.01-24.0      | 11       | 15.49%  |
| 32.01-64.0      | 10       | 14.08%  |
| 8.01-16.0       | 10       | 14.08%  |
| 24.01-32.0      | 7        | 9.86%   |
| More than 256.0 | 2        | 2.82%   |
| 3.01-4.0        | 1        | 1.41%   |
| 2.01-3.0        | 1        | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 24       | 30.77%  |
| 2.01-3.0   | 21       | 26.92%  |
| 8.01-16.0  | 13       | 16.67%  |
| 3.01-4.0   | 9        | 11.54%  |
| 1.01-2.0   | 8        | 10.26%  |
| 24.01-32.0 | 1        | 1.28%   |
| 16.01-24.0 | 1        | 1.28%   |
| 0.51-1.0   | 1        | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 35.62%  |
| 1      | 17       | 23.29%  |
| 3      | 10       | 13.7%   |
| 5      | 8        | 10.96%  |
| 4      | 6        | 8.22%   |
| 12     | 3        | 4.11%   |
| 8      | 2        | 2.74%   |
| 6      | 1        | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 57.14%  |
| Yes       | 30       | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 53.62%  |
| Yes       | 32       | 46.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 62.32%  |
| Yes       | 26       | 37.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 13       | 18.84%  |
| Germany      | 9        | 13.04%  |
| UK           | 6        | 8.7%    |
| Czechia      | 5        | 7.25%   |
| India        | 4        | 5.8%    |
| Russia       | 3        | 4.35%   |
| Canada       | 3        | 4.35%   |
| Ukraine      | 2        | 2.9%    |
| South Korea  | 2        | 2.9%    |
| Poland       | 2        | 2.9%    |
| Italy        | 2        | 2.9%    |
| Argentina    | 2        | 2.9%    |
| Turkmenistan | 1        | 1.45%   |
| Switzerland  | 1        | 1.45%   |
| Sweden       | 1        | 1.45%   |
| Spain        | 1        | 1.45%   |
| New Zealand  | 1        | 1.45%   |
| Netherlands  | 1        | 1.45%   |
| Mexico       | 1        | 1.45%   |
| Lithuania    | 1        | 1.45%   |
| Indonesia    | 1        | 1.45%   |
| Finland      | 1        | 1.45%   |
| Egypt        | 1        | 1.45%   |
| China        | 1        | 1.45%   |
| Brazil       | 1        | 1.45%   |
| Belgium      | 1        | 1.45%   |
| Belarus      | 1        | 1.45%   |
| Austria      | 1        | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Langgons              | 6        | 8.33%   |
| Prague                | 4        | 5.56%   |
| Kyiv                  | 2        | 2.78%   |
| Chicago               | 2        | 2.78%   |
| Yorktown Heights      | 1        | 1.39%   |
| Yongin-si             | 1        | 1.39%   |
| Wiesbaden             | 1        | 1.39%   |
| Vienna                | 1        | 1.39%   |
| Vaglio                | 1        | 1.39%   |
| Turku                 | 1        | 1.39%   |
| Toronto               | 1        | 1.39%   |
| Tiruchi               | 1        | 1.39%   |
| Tauranga              | 1        | 1.39%   |
| Sutton                | 1        | 1.39%   |
| Stavropol             | 1        | 1.39%   |
| Spokane               | 1        | 1.39%   |
| Šiauliai             | 1        | 1.39%   |
| Saratov               | 1        | 1.39%   |
| San Jose              | 1        | 1.39%   |
| San Fernando          | 1        | 1.39%   |
| Salvador              | 1        | 1.39%   |
| Saltillo              | 1        | 1.39%   |
| Rosario               | 1        | 1.39%   |
| Rensselaer            | 1        | 1.39%   |
| Reading               | 1        | 1.39%   |
| Pernis                | 1        | 1.39%   |
| Paracuellos de Jarama | 1        | 1.39%   |
| Oldham                | 1        | 1.39%   |
| Musselburgh           | 1        | 1.39%   |
| Montreal              | 1        | 1.39%   |
| Mississauga           | 1        | 1.39%   |
| Minsk                 | 1        | 1.39%   |
| Milwaukee             | 1        | 1.39%   |
| Milan                 | 1        | 1.39%   |
| Lodz                  | 1        | 1.39%   |
| Leuven                | 1        | 1.39%   |
| Langfang              | 1        | 1.39%   |
| Kielce                | 1        | 1.39%   |
| Inowlodz              | 1        | 1.39%   |
| Huddersfield          | 1        | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 56     | 18.31%  |
| WDC                 | 24       | 48     | 16.9%   |
| Samsung Electronics | 15       | 28     | 10.56%  |
| Toshiba             | 10       | 15     | 7.04%   |
| Kingston            | 8        | 12     | 5.63%   |
| Phison              | 5        | 9      | 3.52%   |
| SanDisk             | 4        | 10     | 2.82%   |
| Hitachi             | 4        | 4      | 2.82%   |
| Dell                | 4        | 8      | 2.82%   |
| Crucial             | 4        | 7      | 2.82%   |
| SK hynix            | 3        | 5      | 2.11%   |
| Micron Technology   | 3        | 3      | 2.11%   |
| Intel               | 3        | 5      | 2.11%   |
| China               | 3        | 3      | 2.11%   |
| A-DATA Technology   | 3        | 3      | 2.11%   |
| Unknown             | 2        | 2      | 1.41%   |
| PNY                 | 2        | 2      | 1.41%   |
| Gigabyte Technology | 2        | 2      | 1.41%   |
| Corsair             | 2        | 5      | 1.41%   |
| XUM                 | 1        | 1      | 0.7%    |
| XPG                 | 1        | 1      | 0.7%    |
| Western Digital     | 1        | 1      | 0.7%    |
| T-FORCE             | 1        | 2      | 0.7%    |
| Silicon Motion      | 1        | 1      | 0.7%    |
| SCST_FIO            | 1        | 9      | 0.7%    |
| OCZ                 | 1        | 2      | 0.7%    |
| KingSpec            | 1        | 1      | 0.7%    |
| KingFast            | 1        | 1      | 0.7%    |
| KINGBANK            | 1        | 1      | 0.7%    |
| HPT                 | 1        | 1      | 0.7%    |
| Hoodisk             | 1        | 1      | 0.7%    |
| HGST                | 1        | 1      | 0.7%    |
| Hewlett-Packard     | 1        | 1      | 0.7%    |
| Anobit              | 1        | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell MD34xx 26TB                     | 4        | 2.3%    |
| Samsung SSD 860 EVO 1TB              | 3        | 1.72%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2        | 1.15%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2        | 1.15%   |
| Unknown SD/MMC/MS PRO 2GB            | 2        | 1.15%   |
| Toshiba NVMe SSD Drive 256GB         | 2        | 1.15%   |
| Toshiba DT01ACA200 2TB               | 2        | 1.15%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2        | 1.15%   |
| Seagate ST91000640NS 1TB             | 2        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 1.15%   |
| Seagate ST2000NX0433 2TB             | 2        | 1.15%   |
| Seagate ST2000NX0273 2TB             | 2        | 1.15%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 1.15%   |
| Seagate ST1000DM003-9YN162 1TB       | 2        | 1.15%   |
| Samsung SSD 860 EVO 500GB            | 2        | 1.15%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 1.15%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.15%   |
| Kingston SUV500120G 120GB SSD        | 2        | 1.15%   |
| Corsair Force LE SSD 240GB           | 2        | 1.15%   |
| XUM HX256GSSDSATA3 256GB             | 1        | 0.57%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.57%   |
| Western Digital NVMe SSD Drive 960GB | 1        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.57%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.57%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1        | 0.57%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.57%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1        | 0.57%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1        | 0.57%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1        | 0.57%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1        | 0.57%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1        | 0.57%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.57%   |
| WDC WD50 00LPVX-00V0TT0 500GB        | 1        | 0.57%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 0.57%   |
| WDC WD40EZRZ-19GXCB0 4TB             | 1        | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.57%   |
| WDC WD4005FZBX-00K5WB0 4TB           | 1        | 0.57%   |
| WDC WD2500BEKT-75F3T0 250GB          | 1        | 0.57%   |
| WDC WD2500AAKX-083CA1 250GB          | 1        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 56     | 37.14%  |
| WDC                 | 22       | 43     | 31.43%  |
| Toshiba             | 8        | 12     | 11.43%  |
| Hitachi             | 4        | 4      | 5.71%   |
| Dell                | 4        | 8      | 5.71%   |
| Unknown             | 2        | 2      | 2.86%   |
| SCST_FIO            | 1        | 9      | 1.43%   |
| Samsung Electronics | 1        | 2      | 1.43%   |
| HGST                | 1        | 1      | 1.43%   |
| Hewlett-Packard     | 1        | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 16     | 21.15%  |
| Kingston            | 8        | 12     | 15.38%  |
| WDC                 | 4        | 5      | 7.69%   |
| Crucial             | 4        | 7      | 7.69%   |
| Micron Technology   | 3        | 3      | 5.77%   |
| China               | 3        | 3      | 5.77%   |
| A-DATA Technology   | 3        | 3      | 5.77%   |
| SK hynix            | 2        | 4      | 3.85%   |
| SanDisk             | 2        | 7      | 3.85%   |
| PNY                 | 2        | 2      | 3.85%   |
| Intel               | 2        | 3      | 3.85%   |
| Corsair             | 2        | 5      | 3.85%   |
| XUM                 | 1        | 1      | 1.92%   |
| OCZ                 | 1        | 2      | 1.92%   |
| KingSpec            | 1        | 1      | 1.92%   |
| KINGBANK            | 1        | 1      | 1.92%   |
| Hoodisk             | 1        | 1      | 1.92%   |
| Anobit              | 1        | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 50       | 138    | 43.1%   |
| SSD     | 46       | 77     | 39.66%  |
| NVMe    | 17       | 33     | 14.66%  |
| Unknown | 3        | 4      | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 66       | 199    | 70.97%  |
| NVMe | 17       | 33     | 18.28%  |
| SAS  | 10       | 20     | 10.75%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 45       | 91     | 41.28%  |
| 0.51-1.0   | 31       | 50     | 28.44%  |
| 1.01-2.0   | 18       | 42     | 16.51%  |
| 3.01-4.0   | 7        | 13     | 6.42%   |
| 20.01-50.0 | 4        | 8      | 3.67%   |
| 4.01-10.0  | 3        | 10     | 2.75%   |
| 2.01-3.0   | 1        | 1      | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 15       | 20.27%  |
| 501-1000       | 13       | 17.57%  |
| 251-500        | 11       | 14.86%  |
| More than 3000 | 10       | 13.51%  |
| Unknown        | 9        | 12.16%  |
| 1001-2000      | 8        | 10.81%  |
| 2001-3000      | 5        | 6.76%   |
| 51-100         | 3        | 4.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 17       | 21.25%  |
| 1-20           | 14       | 17.5%   |
| 101-250        | 12       | 15%     |
| 51-100         | 10       | 12.5%   |
| Unknown        | 9        | 11.25%  |
| 1001-2000      | 5        | 6.25%   |
| 251-500        | 4        | 5%      |
| 501-1000       | 4        | 5%      |
| More than 3000 | 3        | 3.75%   |
| 2001-3000      | 2        | 2.5%    |

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
| Detected | 39       | 148    | 51.32%  |
| Works    | 31       | 96     | 40.79%  |
| Malfunc  | 6        | 8      | 7.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 59       | 55.14%  |
| AMD                          | 9        | 8.41%   |
| Samsung Electronics          | 8        | 7.48%   |
| Broadcom / LSI               | 8        | 7.48%   |
| Phison Electronics           | 6        | 5.61%   |
| ASMedia Technology           | 4        | 3.74%   |
| Marvell Technology Group     | 3        | 2.8%    |
| Toshiba America Info Systems | 2        | 1.87%   |
| LSI Logic / Symbios Logic    | 2        | 1.87%   |
| Western Digital              | 1        | 0.93%   |
| SK hynix                     | 1        | 0.93%   |
| Silicon Motion               | 1        | 0.93%   |
| SanDisk                      | 1        | 0.93%   |
| HighPoint Technologies       | 1        | 0.93%   |
| ADATA Technology             | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 11       | 8.09%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 10       | 7.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8        | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7        | 5.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 4.41%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 6        | 4.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 3.68%   |
| Intel SATA Controller [RAID mode]                                                | 4        | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4        | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4        | 2.94%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 4        | 2.94%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 2.94%   |
| Phison E12 NVMe Controller                                                       | 3        | 2.21%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3        | 2.21%   |
| AMD 300 Series Chipset SATA Controller                                           | 3        | 2.21%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2        | 1.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 2        | 1.47%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2        | 1.47%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2        | 1.47%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 2        | 1.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2        | 1.47%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                      | 1        | 0.74%   |
| SK hynix Non-Volatile memory controller                                          | 1        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1        | 0.74%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 0.74%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1        | 0.74%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                            | 1        | 0.74%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                   | 1        | 0.74%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                             | 1        | 0.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1        | 0.74%   |
| Intel SSD 660P Series                                                            | 1        | 0.74%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1        | 0.74%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                       | 1        | 0.74%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 61       | 57.01%  |
| NVMe | 18       | 16.82%  |
| RAID | 15       | 14.02%  |
| SAS  | 8        | 7.48%   |
| IDE  | 5        | 4.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 60       | 86.96%  |
| AMD    | 9        | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz       | 4        | 5.8%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 3        | 4.35%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz    | 2        | 2.9%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz    | 2        | 2.9%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 2        | 2.9%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz    | 2        | 2.9%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 2        | 2.9%    |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 2.9%    |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 2.9%    |
| Intel Core i3-4130 CPU @ 3.40GHz       | 2        | 2.9%    |
| Intel Xeon CPU E5472 @ 3.00GHz         | 1        | 1.45%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz    | 1        | 1.45%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1        | 1.45%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 1.45%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz    | 1        | 1.45%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 1        | 1.45%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz    | 1        | 1.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz    | 1        | 1.45%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz    | 1        | 1.45%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz    | 1        | 1.45%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz    | 1        | 1.45%   |
| Intel Core i7-9700F CPU @ 3.00GHz      | 1        | 1.45%   |
| Intel Core i7-7560U CPU @ 2.40GHz      | 1        | 1.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 1        | 1.45%   |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 1.45%   |
| Intel Core i7-3820 CPU @ 3.60GHz       | 1        | 1.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 1        | 1.45%   |
| Intel Core i7 CPU X 990 @ 3.47GHz      | 1        | 1.45%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 1        | 1.45%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 1.45%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 1        | 1.45%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 1.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 1.45%   |
| Intel Core i5-3570K CPU @ 3.40GHz      | 1        | 1.45%   |
| Intel Core i5-3550 CPU @ 3.30GHz       | 1        | 1.45%   |
| Intel Core i5-3470T CPU @ 2.90GHz      | 1        | 1.45%   |
| Intel Core i5-3470S CPU @ 2.90GHz      | 1        | 1.45%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 19       | 27.54%  |
| Intel Core i7      | 16       | 23.19%  |
| Intel Core i5      | 13       | 18.84%  |
| Intel Core i3      | 7        | 10.14%  |
| AMD Ryzen 9        | 3        | 4.35%   |
| Intel Pentium Gold | 2        | 2.9%    |
| AMD Ryzen 7        | 2        | 2.9%    |
| Other              | 1        | 1.45%   |
| Intel Core 2 Duo   | 1        | 1.45%   |
| Intel Celeron      | 1        | 1.45%   |
| AMD Ryzen 5        | 1        | 1.45%   |
| AMD Ryzen 3        | 1        | 1.45%   |
| AMD FX             | 1        | 1.45%   |
| AMD A4             | 1        | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 37.68%  |
| 2      | 12       | 17.39%  |
| 6      | 10       | 14.49%  |
| 12     | 7        | 10.14%  |
| 8      | 7        | 10.14%  |
| 16     | 4        | 5.8%    |
| 36     | 1        | 1.45%   |
| 24     | 1        | 1.45%   |
| 20     | 1        | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 85.51%  |
| 2      | 10       | 14.49%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 49       | 70%     |
| 1      | 21       | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 67       | 97.1%   |
| Unknown        | 2        | 2.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 17.39%  |
| 0x906ea    | 8        | 11.59%  |
| 0x306f2    | 8        | 11.59%  |
| 0x306a9    | 6        | 8.7%    |
| 0x906e9    | 3        | 4.35%   |
| 0x506e3    | 3        | 4.35%   |
| 0x406f1    | 3        | 4.35%   |
| 0x206d7    | 3        | 4.35%   |
| 0x906ed    | 2        | 2.9%    |
| 0x08701021 | 2        | 2.9%    |
| Unknown    | 2        | 2.9%    |
| 0xa0671    | 1        | 1.45%   |
| 0xa0655    | 1        | 1.45%   |
| 0x906eb    | 1        | 1.45%   |
| 0x906c0    | 1        | 1.45%   |
| 0x806e9    | 1        | 1.45%   |
| 0x306e4    | 1        | 1.45%   |
| 0x206c2    | 1        | 1.45%   |
| 0x206a7    | 1        | 1.45%   |
| 0x1067a    | 1        | 1.45%   |
| 0x10676    | 1        | 1.45%   |
| 0x08701013 | 1        | 1.45%   |
| 0x08108102 | 1        | 1.45%   |
| 0x0810100b | 1        | 1.45%   |
| 0x08001138 | 1        | 1.45%   |
| 0x08001137 | 1        | 1.45%   |
| 0x06006705 | 1        | 1.45%   |
| 0x06000852 | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 21       | 30.43%  |
| KabyLake    | 15       | 21.74%  |
| IvyBridge   | 8        | 11.59%  |
| SandyBridge | 4        | 5.8%    |
| Zen 2       | 3        | 4.35%   |
| Zen         | 3        | 4.35%   |
| Skylake     | 3        | 4.35%   |
| Broadwell   | 3        | 4.35%   |
| Penryn      | 2        | 2.9%    |
| Zen+        | 1        | 1.45%   |
| Westmere    | 1        | 1.45%   |
| Tremont     | 1        | 1.45%   |
| Piledriver  | 1        | 1.45%   |
| Icelake     | 1        | 1.45%   |
| Excavator   | 1        | 1.45%   |
| CometLake   | 1        | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 36       | 45.57%  |
| Intel                      | 26       | 32.91%  |
| AMD                        | 11       | 13.92%  |
| Matrox Electronics Systems | 6        | 7.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 7.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 6.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.66%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.44%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.44%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 2.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.44%   |
| Intel HD Graphics 630                                                       | 2        | 2.44%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.22%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.22%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.22%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.22%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.22%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.22%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.22%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.22%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.22%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.22%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.22%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.22%   |
| Nvidia GF119 [NVS 315]                                                      | 1        | 1.22%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.22%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.22%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.22%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.22%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.22%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.22%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.22%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.22%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 32       | 45.71%  |
| 1 x Intel      | 17       | 24.29%  |
| 1 x AMD        | 8        | 11.43%  |
| 1 x Matrox     | 6        | 8.57%   |
| 2 x Nvidia     | 2        | 2.86%   |
| Intel + Nvidia | 2        | 2.86%   |
| Intel + AMD    | 2        | 2.86%   |
| 2 x AMD        | 1        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 65.71%  |
| Proprietary | 17       | 24.29%  |
| Unknown     | 7        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 43.84%  |
| 1.01-2.0   | 12       | 16.44%  |
| 7.01-8.0   | 7        | 9.59%   |
| 0.51-1.0   | 7        | 9.59%   |
| 3.01-4.0   | 4        | 5.48%   |
| 0.01-0.5   | 4        | 5.48%   |
| 5.01-6.0   | 3        | 4.11%   |
| 2.01-3.0   | 3        | 4.11%   |
| 8.01-16.0  | 1        | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 15       | 20.83%  |
| Samsung Electronics  | 12       | 16.67%  |
| Goldstar             | 9        | 12.5%   |
| Lenovo               | 6        | 8.33%   |
| Hewlett-Packard      | 5        | 6.94%   |
| BenQ                 | 3        | 4.17%   |
| Ancor Communications | 3        | 4.17%   |
| ViewSonic            | 2        | 2.78%   |
| Philips              | 2        | 2.78%   |
| Lenovo Group Limited | 2        | 2.78%   |
| Iiyama               | 2        | 2.78%   |
| Gigabyte Technology  | 2        | 2.78%   |
| Eizo                 | 2        | 2.78%   |
| Acer                 | 2        | 2.78%   |
| STD                  | 1        | 1.39%   |
| OUT                  | 1        | 1.39%   |
| LG Electronics       | 1        | 1.39%   |
| Insignia             | 1        | 1.39%   |
| Unknown              | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell IDRAC DEL0001 1280x1024                                           | 6        | 7.23%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 2.41%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 2.41%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch               | 2        | 2.41%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 2.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 2.41%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 1.2%    |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 1.2%    |
| STD LED STD0110 1366x768 410x230mm 18.5-inch                           | 1        | 1.2%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 1.2%    |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 1.2%    |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x290mm 23.1-inch   | 1        | 1.2%    |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 1.2%    |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 1.2%    |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 1210x680mm 54.6-inch | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 1.2%    |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 1.2%    |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 1.2%    |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 1.2%    |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch      | 1        | 1.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.2%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.2%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.2%    |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 1.2%    |
| LG Electronics LCD Monitor W2486 1920x1080                             | 1        | 1.2%    |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                   | 1        | 1.2%    |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch               | 1        | 1.2%    |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 1.2%    |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                 | 1        | 1.2%    |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                 | 1        | 1.2%    |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                 | 1        | 1.2%    |
| Lenovo Group Limited LCD Monitor LEN P27u-10                           | 1        | 1.2%    |
| Insignia NS-32D511NA15 BBY4000 1920x1080 591x355mm 27.1-inch           | 1        | 1.2%    |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch           | 1        | 1.2%    |
| Hewlett-Packard LCD Monitor LA2306                                     | 1        | 1.2%    |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch          | 1        | 1.2%    |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch             | 1        | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 43.06%  |
| 1280x1024 (SXGA)   | 7        | 9.72%   |
| 2560x1440 (QHD)    | 6        | 8.33%   |
| 3840x2160 (4K)     | 5        | 6.94%   |
| 3840x1080          | 3        | 4.17%   |
| 3440x1440          | 3        | 4.17%   |
| 2560x1080          | 3        | 4.17%   |
| 1600x900 (HD+)     | 3        | 4.17%   |
| Unknown            | 3        | 4.17%   |
| 9600x2160          | 1        | 1.39%   |
| 7680x2160          | 1        | 1.39%   |
| 3840x1200          | 1        | 1.39%   |
| 1920x1200 (WUXGA)  | 1        | 1.39%   |
| 1680x1050 (WSXGA+) | 1        | 1.39%   |
| 1440x900 (WXGA+)   | 1        | 1.39%   |
| 1280x768           | 1        | 1.39%   |
| 1280x720 (HD)      | 1        | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 21.62%  |
| 23      | 10       | 13.51%  |
| 27      | 8        | 10.81%  |
| 24      | 8        | 10.81%  |
| 21      | 8        | 10.81%  |
| 31      | 4        | 5.41%   |
| 54      | 3        | 4.05%   |
| 34      | 3        | 4.05%   |
| 20      | 3        | 4.05%   |
| 47      | 2        | 2.7%    |
| 18      | 2        | 2.7%    |
| 64      | 1        | 1.35%   |
| 40      | 1        | 1.35%   |
| 39      | 1        | 1.35%   |
| 28      | 1        | 1.35%   |
| 25      | 1        | 1.35%   |
| 19      | 1        | 1.35%   |
| 16      | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 33.8%   |
| Unknown     | 16       | 22.54%  |
| 401-500     | 12       | 16.9%   |
| 601-700     | 6        | 8.45%   |
| 1001-1500   | 6        | 8.45%   |
| 701-800     | 3        | 4.23%   |
| 801-900     | 2        | 2.82%   |
| 351-400     | 1        | 1.41%   |
| 301-350     | 1        | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 62.5%   |
| Unknown | 8        | 12.5%   |
| 5/4     | 7        | 10.94%  |
| 21/9    | 4        | 6.25%   |
| 16/10   | 4        | 6.25%   |
| 4/3     | 1        | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 29.58%  |
| Unknown        | 16       | 22.54%  |
| 301-350        | 8        | 11.27%  |
| 351-500        | 7        | 9.86%   |
| 151-200        | 5        | 7.04%   |
| More than 1000 | 4        | 5.63%   |
| 251-300        | 4        | 5.63%   |
| 501-1000       | 4        | 5.63%   |
| 141-150        | 1        | 1.41%   |
| 131-140        | 1        | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 35       | 50%     |
| Unknown | 16       | 22.86%  |
| 101-120 | 11       | 15.71%  |
| 1-50    | 5        | 7.14%   |
| 161-240 | 2        | 2.86%   |
| 121-160 | 1        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 72.6%   |
| 2     | 8        | 10.96%  |
| 0     | 7        | 9.59%   |
| 3     | 5        | 6.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 45       | 43.69%  |
| Realtek Semiconductor    | 27       | 26.21%  |
| Broadcom                 | 9        | 8.74%   |
| Qualcomm Atheros         | 7        | 6.8%    |
| Ralink Technology        | 2        | 1.94%   |
| Dell                     | 2        | 1.94%   |
| ASIX Electronics         | 2        | 1.94%   |
| Ralink                   | 1        | 0.97%   |
| Microchip Technology     | 1        | 0.97%   |
| Micro Star International | 1        | 0.97%   |
| MediaTek                 | 1        | 0.97%   |
| Huawei Technologies      | 1        | 0.97%   |
| D-Link                   | 1        | 0.97%   |
| Broadcom Limited         | 1        | 0.97%   |
| Arduino SA               | 1        | 0.97%   |
| Aquantia                 | 1        | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22       | 16.18%  |
| Intel I211 Gigabit Network Connection                             | 7        | 5.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.41%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.68%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 3.68%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.94%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 4        | 2.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 4        | 2.94%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 2.21%   |
| Intel I350 Gigabit Network Connection                             | 3        | 2.21%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 2.21%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 2.21%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.21%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.47%   |
| Intel Wireless-AC 9260                                            | 2        | 1.47%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.47%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.47%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.47%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 2        | 1.47%   |
| Dell iDRAC Virtual NIC                                            | 2        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.74%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.74%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.74%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 11       | 34.38%  |
| Qualcomm Atheros         | 6        | 18.75%  |
| Realtek Semiconductor    | 5        | 15.63%  |
| Broadcom                 | 4        | 12.5%   |
| Ralink Technology        | 2        | 6.25%   |
| Ralink                   | 1        | 3.13%   |
| Micro Star International | 1        | 3.13%   |
| MediaTek                 | 1        | 3.13%   |
| D-Link                   | 1        | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 3        | 9.38%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 9.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 6.25%   |
| Intel Wireless-AC 9260                                                     | 2        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 6.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 3.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 3.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 3.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 3.13%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 3.13%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 3.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 3.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.13%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.13%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 3.13%   |
| Intel Wireless 7260                                                        | 1        | 3.13%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1        | 3.13%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 3.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 45       | 55.56%  |
| Realtek Semiconductor | 25       | 30.86%  |
| Broadcom              | 5        | 6.17%   |
| Qualcomm Atheros      | 2        | 2.47%   |
| ASIX Electronics      | 2        | 2.47%   |
| Broadcom Limited      | 1        | 1.23%   |
| Aquantia              | 1        | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 22       | 22.22%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 7.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 6.06%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 5.05%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 5.05%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 4.04%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 4.04%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 4.04%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.03%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3.03%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 2.02%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.02%   |
| Intel Ethernet Controller I225-V                                              | 2        | 2.02%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.02%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.02%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 2.02%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 2.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.01%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.01%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.01%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.01%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.01%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.01%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.01%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.01%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.01%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 65.09%  |
| WiFi     | 32       | 30.19%  |
| Modem    | 3        | 2.83%   |
| Unknown  | 2        | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 82.86%  |
| WiFi     | 12       | 17.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 41.43%  |
| 2     | 19       | 27.14%  |
| 3     | 12       | 17.14%  |
| 6     | 5        | 7.14%   |
| 4     | 4        | 5.71%   |
| 5     | 1        | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 61       | 87.14%  |
| Yes  | 9        | 12.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 34.62%  |
| Cambridge Silicon Radio         | 7        | 26.92%  |
| ASUSTek Computer                | 3        | 11.54%  |
| Realtek Semiconductor           | 2        | 7.69%   |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| Micro Star International        | 1        | 3.85%   |
| IMC Networks                    | 1        | 3.85%   |
| Broadcom                        | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 26.92%  |
| Realtek Bluetooth Radio                               | 2        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 7.69%   |
| Intel AX200 Bluetooth                                 | 2        | 7.69%   |
| ASUS BCM20702A0                                       | 2        | 7.69%   |
| Micro Star International Bluetooth Device             | 1        | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 3.85%   |
| Intel Bluetooth wireless interface                    | 1        | 3.85%   |
| Intel AX201 Bluetooth                                 | 1        | 3.85%   |
| IMC Networks BCM20702A0                               | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 3.85%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 50       | 42.37%  |
| Nvidia                                       | 34       | 28.81%  |
| AMD                                          | 14       | 11.86%  |
| Lenovo                                       | 3        | 2.54%   |
| Creative Labs                                | 3        | 2.54%   |
| Texas Instruments                            | 2        | 1.69%   |
| Plantronics                                  | 2        | 1.69%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.85%   |
| Tenx Technology                              | 1        | 0.85%   |
| Sennheiser Communications                    | 1        | 0.85%   |
| RODE Microphones                             | 1        | 0.85%   |
| Logitech                                     | 1        | 0.85%   |
| JMTek                                        | 1        | 0.85%   |
| Giga-Byte Technology                         | 1        | 0.85%   |
| Dynex                                        | 1        | 0.85%   |
| Creative Technology                          | 1        | 0.85%   |
| ASUSTek Computer                             | 1        | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 7.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 6.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 4.58%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 4.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 3.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 3.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 3.05%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 3.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 2.29%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.29%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 2.29%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.29%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.53%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.53%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.53%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.76%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.76%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                  | 1        | 0.76%   |
| RODE Microphones RODE NT-USB                                               | 1        | 0.76%   |
| Plantronics Poly BT700                                                     | 1        | 0.76%   |
| Plantronics BT600                                                          | 1        | 0.76%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.76%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.76%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 20%     |
| SK hynix            | 7        | 17.5%   |
| Micron Technology   | 7        | 17.5%   |
| Crucial             | 6        | 15%     |
| Kingston            | 4        | 10%     |
| Corsair             | 3        | 7.5%    |
| Unknown (0x0205)    | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |
| Transcend           | 1        | 2.5%    |
| Patriot             | 1        | 2.5%    |
| GOODRAM             | 1        | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s    | 2        | 4.44%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s       | 2        | 4.44%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s        | 2        | 4.44%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s        | 2        | 4.44%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s      | 2        | 4.44%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1        | 2.22%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s          | 1        | 2.22%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s            | 1        | 2.22%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s       | 1        | 2.22%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s     | 1        | 2.22%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 2.22%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s        | 1        | 2.22%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                   | 1        | 2.22%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 1        | 2.22%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                  | 1        | 2.22%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s        | 1        | 2.22%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 1        | 2.22%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s         | 1        | 2.22%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s      | 1        | 2.22%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s         | 1        | 2.22%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s      | 1        | 2.22%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s            | 1        | 2.22%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 2.22%   |
| Micron RAM 9ASF51272PZ-2G3B1 4096MB RIMM DDR4 2400MT/s      | 1        | 2.22%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s        | 1        | 2.22%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s         | 1        | 2.22%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s         | 1        | 2.22%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 2.22%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s        | 1        | 2.22%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1        | 2.22%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s     | 1        | 2.22%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.22%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s       | 1        | 2.22%   |
| Crucial RAM CT4G4DFS824A.M8FG 4096MB DIMM DDR4 2400MT/s     | 1        | 2.22%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16384MB DIMM DDR4 2933MT/s | 1        | 2.22%   |
| Crucial RAM BLT4G3D1608ET3LX0. 4GB DIMM DDR3 1600MT/s       | 1        | 2.22%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s      | 1        | 2.22%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4096MB DIMM DDR4 2472MT/s    | 1        | 2.22%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s       | 1        | 2.22%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s    | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 19       | 54.29%  |
| DDR3   | 9        | 25.71%  |
| SDRAM  | 3        | 8.57%   |
| DRAM   | 2        | 5.71%   |
| LPDDR4 | 1        | 2.86%   |
| DDR2   | 1        | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 31       | 91.18%  |
| SODIMM       | 1        | 2.94%   |
| Row Of Chips | 1        | 2.94%   |
| RIMM         | 1        | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 12       | 31.58%  |
| 4096  | 10       | 26.32%  |
| 8192  | 9        | 23.68%  |
| 32768 | 4        | 10.53%  |
| 2048  | 2        | 5.26%   |
| 1024  | 1        | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 8        | 21.05%  |
| 1600  | 8        | 21.05%  |
| 2133  | 6        | 15.79%  |
| 2667  | 3        | 7.89%   |
| 3600  | 2        | 5.26%   |
| 3200  | 2        | 5.26%   |
| 2933  | 2        | 5.26%   |
| 1333  | 2        | 5.26%   |
| 2666  | 1        | 2.63%   |
| 2472  | 1        | 2.63%   |
| 2048  | 1        | 2.63%   |
| 1867  | 1        | 2.63%   |
| 800   | 1        | 2.63%   |

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


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown FULL HD 1080P Webcam | 3        | 21.43%  |
| Generalplus GENERAL WEBCAM   | 2        | 14.29%  |
| Samsung Galaxy A5 (MTP)      | 1        | 7.14%   |
| Ruision UVC Camera           | 1        | 7.14%   |
| Microsoft LifeCam HD-3000    | 1        | 7.14%   |
| Logitech Webcam C270         | 1        | 7.14%   |
| Logitech Webcam C250         | 1        | 7.14%   |
| Logitech HD Webcam C910      | 1        | 7.14%   |
| Jieli USB PHY 2.0            | 1        | 7.14%   |
| IMC Networks XHC Camera      | 1        | 7.14%   |
| ARC International Camera     | 1        | 7.14%   |

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
| 0     | 49       | 70%     |
| 1     | 10       | 14.29%  |
| 2     | 9        | 12.86%  |
| 5     | 1        | 1.43%   |
| 3     | 1        | 1.43%   |

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

