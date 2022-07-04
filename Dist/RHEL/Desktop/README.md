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

Total: 98

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| RHEL 8 | 51       | 79.69%  |
| RHEL 7 | 12       | 18.75%  |
| RHEL 9 | 1        | 1.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 64       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 9.09%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 7.79%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 5.19%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 5.19%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 5.19%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 3.9%    |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 3.9%    |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 3.9%    |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 3.9%    |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 3.9%    |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 2.6%    |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 2.6%    |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 2.6%    |
| 4.18.0-193.el8.x86_64        | 2        | 2.6%    |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 2.6%    |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 2.6%    |
| 4.18.0-147.el8.x86_64        | 2        | 2.6%    |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 1.3%    |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.3%    |
| 4.19.150                     | 1        | 1.3%    |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.3%    |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 1.3%    |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.3%    |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.3%    |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.3%    |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.3%    |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.3%    |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.3%    |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.3%    |
| 4.18.0-193.1.2.el8_2.x86_64  | 1        | 1.3%    |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.3%    |
| 3.10.0-957.5.1.el7.x86_64    | 1        | 1.3%    |
| 3.10.0-957.1.3.el7.x86_64    | 1        | 1.3%    |
| 3.10.0-862.9.1.el7.x86_64    | 1        | 1.3%    |
| 3.10.0-862.11.6.el7.x86_64   | 1        | 1.3%    |
| 3.10.0-693.11.6.el7.x86_64   | 1        | 1.3%    |
| 3.10.0-1160.45.1.el7.x86_64  | 1        | 1.3%    |
| 3.10.0-1127.10.1.el7.x86_64  | 1        | 1.3%    |
| 3.10.0-1062.4.3.el7.x86_64   | 1        | 1.3%    |
| 3.10.0-1062.18.1.el7.x86_64  | 1        | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 49       | 76.56%  |
| 3.10.0   | 12       | 18.75%  |
| 5.14.0   | 1        | 1.56%   |
| 5.10.6   | 1        | 1.56%   |
| 4.19.150 | 1        | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 49       | 76.56%  |
| 3.10    | 12       | 18.75%  |
| 5.14    | 1        | 1.56%   |
| 5.10    | 1        | 1.56%   |
| 4.19    | 1        | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 45       | 67.16%  |
| Unknown       | 14       | 20.9%   |
| GNOME Classic | 3        | 4.48%   |
| KDE5          | 2        | 2.99%   |
| KDE           | 2        | 2.99%   |
| MATE          | 1        | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 55.22%  |
| Wayland | 23       | 34.33%  |
| Unknown | 7        | 10.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 76.12%  |
| GDM     | 15       | 22.39%  |
| LightDM | 1        | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 33       | 50.77%  |
| Unknown | 13       | 20%     |
| ru_RU   | 3        | 4.62%   |
| en_GB   | 3        | 4.62%   |
| pl_PL   | 2        | 3.08%   |
| es_AR   | 2        | 3.08%   |
| en_IN   | 2        | 3.08%   |
| de_DE   | 2        | 3.08%   |
| ko_KR   | 1        | 1.54%   |
| es_MX   | 1        | 1.54%   |
| es_ES   | 1        | 1.54%   |
| en_NZ   | 1        | 1.54%   |
| cs_CZ   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 37       | 56.92%  |
| BIOS | 28       | 43.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 58       | 89.23%  |
| Ext4    | 4        | 6.15%   |
| Unknown | 3        | 4.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 56.72%  |
| GPT     | 17       | 25.37%  |
| MBR     | 12       | 17.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 78.46%  |
| Yes       | 14       | 21.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 90.77%  |
| Yes       | 6        | 9.23%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 16       | 25%     |
| ASUSTek Computer    | 12       | 18.75%  |
| Hewlett-Packard     | 10       | 15.63%  |
| Gigabyte Technology | 7        | 10.94%  |
| ASRock              | 6        | 9.38%   |
| MSI                 | 4        | 6.25%   |
| Lenovo              | 4        | 6.25%   |
| Supermicro          | 1        | 1.56%   |
| Intel               | 1        | 1.56%   |
| CX / Air Computers. | 1        | 1.56%   |
| Alienware           | 1        | 1.56%   |
| Unknown             | 1        | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 9.38%   |
| ASUS All Series                     | 4        | 6.25%   |
| HP Z620 Workstation                 | 2        | 3.13%   |
| Dell OptiPlex 9020                  | 2        | 3.13%   |
| Supermicro X7DW3                    | 1        | 1.56%   |
| MSI MS-7B51                         | 1        | 1.56%   |
| MSI MS-7B33                         | 1        | 1.56%   |
| MSI MS-7A37                         | 1        | 1.56%   |
| MSI MS-7752                         | 1        | 1.56%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.56%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.56%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.56%   |
| Lenovo 10SFS03200                   | 1        | 1.56%   |
| Intel DX79SR AAG57199-200           | 1        | 1.56%   |
| HP Z840 Workstation                 | 1        | 1.56%   |
| HP Z440 Workstation                 | 1        | 1.56%   |
| HP Z230 Tower Workstation           | 1        | 1.56%   |
| HP Z230 SFF Workstation             | 1        | 1.56%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.56%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.56%   |
| HP 290 G1 SFF Business PC           | 1        | 1.56%   |
| HP 260-P020il                       | 1        | 1.56%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.56%   |
| Gigabyte Z490 GAMING X              | 1        | 1.56%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.56%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.56%   |
| Gigabyte B75-D3V                    | 1        | 1.56%   |
| Gigabyte B150-HD3                   | 1        | 1.56%   |
| Gigabyte 970A-D3                    | 1        | 1.56%   |
| Dell Vostro 270                     | 1        | 1.56%   |
| Dell Studio XPS 9100                | 1        | 1.56%   |
| Dell Precision Tower 5810           | 1        | 1.56%   |
| Dell Precision Tower 3620           | 1        | 1.56%   |
| Dell Precision Tower 3420           | 1        | 1.56%   |
| Dell Precision T7600                | 1        | 1.56%   |
| Dell Precision 3630 Tower           | 1        | 1.56%   |
| Dell OptiPlex 760                   | 1        | 1.56%   |
| CX / Air Computers. H87-M1          | 1        | 1.56%   |
| ASUS Z10PE-D16 WS                   | 1        | 1.56%   |
| ASUS ROG STRIX B350-F GAMING        | 1        | 1.56%   |
| ASUS ROG Maximus X HERO             | 1        | 1.56%   |
| ASUS Pro WS X570-ACE                | 1        | 1.56%   |
| ASUS PRIME X470-PRO                 | 1        | 1.56%   |
| ASUS PRIME B360M-D                  | 1        | 1.56%   |
| ASUS PRIME B350M-A                  | 1        | 1.56%   |
| ASUS P8Z77-V PRO                    | 1        | 1.56%   |
| ASRock Z370 Professional Gaming i7  | 1        | 1.56%   |
| ASRock X99E-ITX/ac                  | 1        | 1.56%   |
| ASRock X570 Steel Legend            | 1        | 1.56%   |
| ASRock H91M-PLUS                    | 1        | 1.56%   |
| ASRock H270 Pro4                    | 1        | 1.56%   |
| ASRock A300M-STX                    | 1        | 1.56%   |
| Alienware Aurora R7                 | 1        | 1.56%   |
| Unknown                             | 1        | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell PowerEdge             | 6        | 9.38%   |
| Dell Precision             | 5        | 7.81%   |
| ASUS All                   | 4        | 6.25%   |
| Lenovo ThinkCentre         | 3        | 4.69%   |
| Dell OptiPlex              | 3        | 4.69%   |
| ASUS PRIME                 | 3        | 4.69%   |
| HP Z620                    | 2        | 3.13%   |
| HP Z230                    | 2        | 3.13%   |
| ASUS ROG                   | 2        | 3.13%   |
| Supermicro X7DW3           | 1        | 1.56%   |
| MSI MS-7B51                | 1        | 1.56%   |
| MSI MS-7B33                | 1        | 1.56%   |
| MSI MS-7A37                | 1        | 1.56%   |
| MSI MS-7752                | 1        | 1.56%   |
| Lenovo 10SFS03200          | 1        | 1.56%   |
| Intel DX79SR               | 1        | 1.56%   |
| HP Z840                    | 1        | 1.56%   |
| HP Z440                    | 1        | 1.56%   |
| HP ProLiant                | 1        | 1.56%   |
| HP EliteDesk               | 1        | 1.56%   |
| HP 290                     | 1        | 1.56%   |
| HP 260-P020il              | 1        | 1.56%   |
| Gigabyte Z97N-WIFI         | 1        | 1.56%   |
| Gigabyte Z490              | 1        | 1.56%   |
| Gigabyte Z390              | 1        | 1.56%   |
| Gigabyte B85M-D3V-A        | 1        | 1.56%   |
| Gigabyte B75-D3V           | 1        | 1.56%   |
| Gigabyte B150-HD3          | 1        | 1.56%   |
| Gigabyte 970A-D3           | 1        | 1.56%   |
| Dell Vostro                | 1        | 1.56%   |
| Dell Studio                | 1        | 1.56%   |
| CX / Air Computers. H87-M1 | 1        | 1.56%   |
| ASUS Z10PE-D16             | 1        | 1.56%   |
| ASUS Pro                   | 1        | 1.56%   |
| ASUS P8Z77-V               | 1        | 1.56%   |
| ASRock Z370                | 1        | 1.56%   |
| ASRock X99E-ITX            | 1        | 1.56%   |
| ASRock X570                | 1        | 1.56%   |
| ASRock H91M-PLUS           | 1        | 1.56%   |
| ASRock H270                | 1        | 1.56%   |
| ASRock A300M-STX           | 1        | 1.56%   |
| Alienware Aurora           | 1        | 1.56%   |
| Unknown                    | 1        | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 15.63%  |
| 2016 | 10       | 15.63%  |
| 2017 | 9        | 14.06%  |
| 2012 | 8        | 12.5%   |
| 2015 | 6        | 9.38%   |
| 2013 | 6        | 9.38%   |
| 2019 | 5        | 7.81%   |
| 2020 | 3        | 4.69%   |
| 2014 | 2        | 3.13%   |
| 2009 | 2        | 3.13%   |
| 2021 | 1        | 1.56%   |
| 2011 | 1        | 1.56%   |
| 2010 | 1        | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 64       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 61       | 93.85%  |
| Enabled  | 4        | 6.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 18       | 27.27%  |
| 16.01-24.0      | 11       | 16.67%  |
| 4.01-8.0        | 9        | 13.64%  |
| 32.01-64.0      | 9        | 13.64%  |
| 8.01-16.0       | 9        | 13.64%  |
| 24.01-32.0      | 7        | 10.61%  |
| More than 256.0 | 2        | 3.03%   |
| 2.01-3.0        | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 24       | 32.88%  |
| 2.01-3.0   | 18       | 24.66%  |
| 8.01-16.0  | 13       | 17.81%  |
| 3.01-4.0   | 9        | 12.33%  |
| 1.01-2.0   | 6        | 8.22%   |
| 24.01-32.0 | 1        | 1.37%   |
| 16.01-24.0 | 1        | 1.37%   |
| 0.51-1.0   | 1        | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 32.35%  |
| 1      | 16       | 23.53%  |
| 3      | 10       | 14.71%  |
| 5      | 8        | 11.76%  |
| 4      | 6        | 8.82%   |
| 12     | 3        | 4.41%   |
| 8      | 2        | 2.94%   |
| 6      | 1        | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 53.85%  |
| Yes       | 30       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 64       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 56.25%  |
| Yes       | 28       | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 65.63%  |
| Yes       | 22       | 34.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 13       | 20.31%  |
| Germany      | 9        | 14.06%  |
| Czechia      | 5        | 7.81%   |
| UK           | 4        | 6.25%   |
| Russia       | 3        | 4.69%   |
| Canada       | 3        | 4.69%   |
| Ukraine      | 2        | 3.13%   |
| South Korea  | 2        | 3.13%   |
| Poland       | 2        | 3.13%   |
| Italy        | 2        | 3.13%   |
| India        | 2        | 3.13%   |
| Argentina    | 2        | 3.13%   |
| Turkmenistan | 1        | 1.56%   |
| Switzerland  | 1        | 1.56%   |
| Sweden       | 1        | 1.56%   |
| Spain        | 1        | 1.56%   |
| New Zealand  | 1        | 1.56%   |
| Netherlands  | 1        | 1.56%   |
| Mexico       | 1        | 1.56%   |
| Lithuania    | 1        | 1.56%   |
| Indonesia    | 1        | 1.56%   |
| Egypt        | 1        | 1.56%   |
| China        | 1        | 1.56%   |
| Brazil       | 1        | 1.56%   |
| Belgium      | 1        | 1.56%   |
| Belarus      | 1        | 1.56%   |
| Austria      | 1        | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Langgons              | 6        | 8.96%   |
| Prague                | 4        | 5.97%   |
| Kyiv                  | 2        | 2.99%   |
| Chicago               | 2        | 2.99%   |
| Yorktown Heights      | 1        | 1.49%   |
| Yongin-si             | 1        | 1.49%   |
| Wiesbaden             | 1        | 1.49%   |
| Vienna                | 1        | 1.49%   |
| Vaglio                | 1        | 1.49%   |
| Toronto               | 1        | 1.49%   |
| Tiruchi               | 1        | 1.49%   |
| Tauranga              | 1        | 1.49%   |
| Stavropol             | 1        | 1.49%   |
| Spokane               | 1        | 1.49%   |
| Šiauliai             | 1        | 1.49%   |
| Saratov               | 1        | 1.49%   |
| San Jose              | 1        | 1.49%   |
| San Fernando          | 1        | 1.49%   |
| Salvador              | 1        | 1.49%   |
| Saltillo              | 1        | 1.49%   |
| Rosario               | 1        | 1.49%   |
| Rensselaer            | 1        | 1.49%   |
| Reading               | 1        | 1.49%   |
| Pernis                | 1        | 1.49%   |
| Paracuellos de Jarama | 1        | 1.49%   |
| Musselburgh           | 1        | 1.49%   |
| Montreal              | 1        | 1.49%   |
| Mississauga           | 1        | 1.49%   |
| Minsk                 | 1        | 1.49%   |
| Milwaukee             | 1        | 1.49%   |
| Milan                 | 1        | 1.49%   |
| Lodz                  | 1        | 1.49%   |
| Leuven                | 1        | 1.49%   |
| Langfang              | 1        | 1.49%   |
| Kielce                | 1        | 1.49%   |
| Inowlodz              | 1        | 1.49%   |
| Huddersfield          | 1        | 1.49%   |
| Holly Springs         | 1        | 1.49%   |
| Gyami                 | 1        | 1.49%   |
| Gothenburg            | 1        | 1.49%   |
| Gangnam-gu            | 1        | 1.49%   |
| Dobrany               | 1        | 1.49%   |
| Dimitrovgrad          | 1        | 1.49%   |
| Didcot                | 1        | 1.49%   |
| Des Moines            | 1        | 1.49%   |
| Corpus Christi        | 1        | 1.49%   |
| Chassell              | 1        | 1.49%   |
| Cairo                 | 1        | 1.49%   |
| Buenos Aires          | 1        | 1.49%   |
| Bonn                  | 1        | 1.49%   |
| Bethlehem             | 1        | 1.49%   |
| Berlin                | 1        | 1.49%   |
| Bengaluru             | 1        | 1.49%   |
| Bandung               | 1        | 1.49%   |
| Aurora                | 1        | 1.49%   |
| Albuquerque           | 1        | 1.49%   |
| Albuccione            | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 55     | 18.8%   |
| WDC                 | 24       | 48     | 18.05%  |
| Samsung Electronics | 14       | 27     | 10.53%  |
| Toshiba             | 10       | 15     | 7.52%   |
| Kingston            | 8        | 12     | 6.02%   |
| SanDisk             | 4        | 10     | 3.01%   |
| Phison              | 4        | 8      | 3.01%   |
| Hitachi             | 4        | 4      | 3.01%   |
| Dell                | 4        | 8      | 3.01%   |
| Crucial             | 4        | 7      | 3.01%   |
| SK hynix            | 3        | 5      | 2.26%   |
| Micron Technology   | 3        | 3      | 2.26%   |
| Intel               | 3        | 5      | 2.26%   |
| A-DATA Technology   | 3        | 3      | 2.26%   |
| PNY                 | 2        | 2      | 1.5%    |
| Corsair             | 2        | 5      | 1.5%    |
| XPG                 | 1        | 1      | 0.75%   |
| Western Digital     | 1        | 1      | 0.75%   |
| Unknown             | 1        | 1      | 0.75%   |
| T-FORCE             | 1        | 2      | 0.75%   |
| Silicon Motion      | 1        | 1      | 0.75%   |
| SCST_FIO            | 1        | 9      | 0.75%   |
| OCZ                 | 1        | 2      | 0.75%   |
| KingFast            | 1        | 1      | 0.75%   |
| KINGBANK            | 1        | 1      | 0.75%   |
| HPT                 | 1        | 1      | 0.75%   |
| Hoodisk             | 1        | 1      | 0.75%   |
| HGST                | 1        | 1      | 0.75%   |
| Hewlett-Packard     | 1        | 1      | 0.75%   |
| Gigabyte Technology | 1        | 1      | 0.75%   |
| China               | 1        | 1      | 0.75%   |
| Anobit              | 1        | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Dell MD34xx 26TB                       | 4        | 2.42%   |
| Samsung SSD 860 EVO 1TB                | 3        | 1.82%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 2        | 1.21%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 2        | 1.21%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 2        | 1.21%   |
| Toshiba DT01ACA200 2TB                 | 2        | 1.21%   |
| Toshiba AL14SEB18EQ 1.8TB              | 2        | 1.21%   |
| Seagate ST91000640NS 1TB               | 2        | 1.21%   |
| Seagate ST500DM002-1BD142 500GB        | 2        | 1.21%   |
| Seagate ST2000NX0433 2TB               | 2        | 1.21%   |
| Seagate ST2000NX0273 2TB               | 2        | 1.21%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 1.21%   |
| Seagate ST1000DM003-9YN162 1TB         | 2        | 1.21%   |
| Samsung SSD 860 EVO 500GB              | 2        | 1.21%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2        | 1.21%   |
| Samsung NVMe SSD Drive 512GB           | 2        | 1.21%   |
| Kingston SUV500120G 120GB SSD          | 2        | 1.21%   |
| Corsair Force LE SSD 240GB             | 2        | 1.21%   |
| XPG NVMe SSD Drive 1024GB              | 1        | 0.61%   |
| Western Digital NVMe SSD Drive 960GB   | 1        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1        | 0.61%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1        | 0.61%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1        | 0.61%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 1        | 0.61%   |
| WDC WD7500BPKT-00PK4T0 752GB           | 1        | 0.61%   |
| WDC WD60 EFAX-68JH4N1 6TB              | 1        | 0.61%   |
| WDC WD60 EFAX-68JH4N0 6TB              | 1        | 0.61%   |
| WDC WD5003ABYZ-011FA0 500GB            | 1        | 0.61%   |
| WDC WD5000HHTZ-04N21V0 500GB           | 1        | 0.61%   |
| WDC WD5000AAKX-75U6AA0 500GB           | 1        | 0.61%   |
| WDC WD50 00LPVX-00V0TT0 500GB          | 1        | 0.61%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1        | 0.61%   |
| WDC WD40EZRZ-19GXCB0 4TB               | 1        | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB               | 1        | 0.61%   |
| WDC WD4005FZBX-00K5WB0 4TB             | 1        | 0.61%   |
| WDC WD2500BEKT-75F3T0 250GB            | 1        | 0.61%   |
| WDC WD2500AAKX-083CA1 250GB            | 1        | 0.61%   |
| WDC WD20PURZ-85GU6Y0 2TB               | 1        | 0.61%   |
| WDC WD20EARS-22MVWB0 2TB               | 1        | 0.61%   |
| WDC WD2005FBYZ-01YCBB3 2TB             | 1        | 0.61%   |
| WDC WD2003FZEX-00SRLA0 2TB             | 1        | 0.61%   |
| WDC WD2002FFSX-68PF8N0 2TB             | 1        | 0.61%   |
| WDC WD10SPSX-00A6WT0 1TB               | 1        | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1        | 0.61%   |
| WDC WD10JPLX-00MBPT0 1TB               | 1        | 0.61%   |
| WDC WD10EZEX-75WN4A0 1TB               | 1        | 0.61%   |
| WDC WD10EZEX-22MFCA0 1TB               | 1        | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1        | 0.61%   |
| WDC WD10EALX-759BA1 1TB                | 1        | 0.61%   |
| Unknown SD/MMC/MS PRO 128GB            | 1        | 0.61%   |
| Toshiba MQ01ACF032 320GB               | 1        | 0.61%   |
| Toshiba HDWT140 4TB                    | 1        | 0.61%   |
| Toshiba HDWQ140 4TB                    | 1        | 0.61%   |
| Toshiba HDWD120 2TB                    | 1        | 0.61%   |
| Toshiba DT01ACA300 3TB                 | 1        | 0.61%   |
| Toshiba DT01ACA100 1TB                 | 1        | 0.61%   |
| T-FORCE 1TB                            | 1        | 0.61%   |
| SK hynix SC311 SATA 256GB SSD          | 1        | 0.61%   |
| SK hynix PC601 NVMe 512GB              | 1        | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 25       | 55     | 36.76%  |
| WDC                 | 22       | 43     | 32.35%  |
| Toshiba             | 8        | 12     | 11.76%  |
| Hitachi             | 4        | 4      | 5.88%   |
| Dell                | 4        | 8      | 5.88%   |
| Unknown             | 1        | 1      | 1.47%   |
| SCST_FIO            | 1        | 9      | 1.47%   |
| Samsung Electronics | 1        | 2      | 1.47%   |
| HGST                | 1        | 1      | 1.47%   |
| Hewlett-Packard     | 1        | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 15     | 21.28%  |
| Kingston            | 8        | 12     | 17.02%  |
| WDC                 | 4        | 5      | 8.51%   |
| Crucial             | 4        | 7      | 8.51%   |
| Micron Technology   | 3        | 3      | 6.38%   |
| A-DATA Technology   | 3        | 3      | 6.38%   |
| SK hynix            | 2        | 4      | 4.26%   |
| SanDisk             | 2        | 7      | 4.26%   |
| PNY                 | 2        | 2      | 4.26%   |
| Intel               | 2        | 3      | 4.26%   |
| Corsair             | 2        | 5      | 4.26%   |
| OCZ                 | 1        | 2      | 2.13%   |
| KINGBANK            | 1        | 1      | 2.13%   |
| Hoodisk             | 1        | 1      | 2.13%   |
| China               | 1        | 1      | 2.13%   |
| Anobit              | 1        | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 48       | 136    | 44.86%  |
| SSD     | 41       | 72     | 38.32%  |
| NVMe    | 15       | 31     | 14.02%  |
| Unknown | 3        | 4      | 2.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 61       | 193    | 71.76%  |
| NVMe | 15       | 31     | 17.65%  |
| SAS  | 9        | 19     | 10.59%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 42       | 86     | 40.38%  |
| 0.51-1.0   | 29       | 48     | 27.88%  |
| 1.01-2.0   | 18       | 42     | 17.31%  |
| 3.01-4.0   | 7        | 13     | 6.73%   |
| 20.01-50.0 | 4        | 8      | 3.85%   |
| 4.01-10.0  | 3        | 10     | 2.88%   |
| 2.01-3.0   | 1        | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 18.84%  |
| 501-1000       | 12       | 17.39%  |
| More than 3000 | 10       | 14.49%  |
| 251-500        | 9        | 13.04%  |
| Unknown        | 9        | 13.04%  |
| 1001-2000      | 8        | 11.59%  |
| 2001-3000      | 5        | 7.25%   |
| 51-100         | 3        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 16       | 21.33%  |
| 101-250        | 12       | 16%     |
| 1-20           | 11       | 14.67%  |
| 51-100         | 9        | 12%     |
| Unknown        | 9        | 12%     |
| 1001-2000      | 5        | 6.67%   |
| 251-500        | 4        | 5.33%   |
| 501-1000       | 4        | 5.33%   |
| More than 3000 | 3        | 4%      |
| 2001-3000      | 2        | 2.67%   |

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
| Detected | 37       | 144    | 52.11%  |
| Works    | 28       | 91     | 39.44%  |
| Malfunc  | 6        | 8      | 8.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 55       | 55%     |
| Samsung Electronics          | 8        | 8%      |
| Broadcom / LSI               | 8        | 8%      |
| AMD                          | 8        | 8%      |
| Phison Electronics           | 4        | 4%      |
| ASMedia Technology           | 4        | 4%      |
| Marvell Technology Group     | 3        | 3%      |
| Toshiba America Info Systems | 2        | 2%      |
| LSI Logic / Symbios Logic    | 2        | 2%      |
| Western Digital              | 1        | 1%      |
| SK hynix                     | 1        | 1%      |
| Silicon Motion               | 1        | 1%      |
| SanDisk                      | 1        | 1%      |
| HighPoint Technologies       | 1        | 1%      |
| ADATA Technology             | 1        | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 11       | 8.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 10       | 7.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 6.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 5.43%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 5.43%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 6        | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 3.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.88%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 3.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.1%    |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 4        | 3.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 3.1%    |
| Phison E12 NVMe Controller                                                              | 3        | 2.33%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 2.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2        | 1.55%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 1.55%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 1.55%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.55%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                             | 1        | 0.78%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.78%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.78%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.78%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 0.78%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 0.78%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 0.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.78%   |
| Intel SSD 660P Series                                                                   | 1        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.78%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 0.78%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.78%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 0.78%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.78%   |
| HighPoint RocketRAID 2720 SAS Controller                                                | 1        | 0.78%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.78%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 56%     |
| NVMe | 16       | 16%     |
| RAID | 15       | 15%     |
| SAS  | 8        | 8%      |
| IDE  | 5        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 56       | 87.5%   |
| AMD    | 8        | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 6.25%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 4.69%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 2        | 3.13%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 2        | 3.13%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 2        | 3.13%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 3.13%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 3.13%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 3.13%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 3.13%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 1.56%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.56%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 1.56%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 1.56%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 1.56%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz         | 1        | 1.56%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz         | 1        | 1.56%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 1.56%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.56%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1        | 1.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.56%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 1.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.56%   |
| Intel Core i7 CPU X 990 @ 3.47GHz           | 1        | 1.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.56%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.56%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.56%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 1.56%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 1.56%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 1.56%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.56%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 1        | 1.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.56%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.56%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 1        | 1.56%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 1.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.56%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.56%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 1.56%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 1.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 1.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 1.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 1.56%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 19       | 29.69%  |
| Intel Core i7      | 16       | 25%     |
| Intel Core i5      | 12       | 18.75%  |
| Intel Core i3      | 6        | 9.38%   |
| AMD Ryzen 9        | 3        | 4.69%   |
| Intel Pentium Gold | 2        | 3.13%   |
| AMD Ryzen 7        | 2        | 3.13%   |
| Intel Core 2 Duo   | 1        | 1.56%   |
| AMD Ryzen 5        | 1        | 1.56%   |
| AMD Ryzen 3        | 1        | 1.56%   |
| AMD FX             | 1        | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 24       | 37.5%   |
| 6      | 10       | 15.63%  |
| 2      | 10       | 15.63%  |
| 12     | 7        | 10.94%  |
| 8      | 6        | 9.38%   |
| 16     | 4        | 6.25%   |
| 36     | 1        | 1.56%   |
| 24     | 1        | 1.56%   |
| 20     | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 84.38%  |
| 2      | 10       | 15.63%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 72.31%  |
| 1      | 18       | 27.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 62       | 96.88%  |
| Unknown        | 2        | 3.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 17.19%  |
| 0x906ea    | 8        | 12.5%   |
| 0x306f2    | 8        | 12.5%   |
| 0x306a9    | 5        | 7.81%   |
| 0x906e9    | 3        | 4.69%   |
| 0x506e3    | 3        | 4.69%   |
| 0x406f1    | 3        | 4.69%   |
| 0x206d7    | 3        | 4.69%   |
| 0x906ed    | 2        | 3.13%   |
| 0x08701021 | 2        | 3.13%   |
| Unknown    | 2        | 3.13%   |
| 0xa0655    | 1        | 1.56%   |
| 0x906eb    | 1        | 1.56%   |
| 0x806e9    | 1        | 1.56%   |
| 0x306e4    | 1        | 1.56%   |
| 0x206c2    | 1        | 1.56%   |
| 0x206a7    | 1        | 1.56%   |
| 0x1067a    | 1        | 1.56%   |
| 0x10676    | 1        | 1.56%   |
| 0x08701013 | 1        | 1.56%   |
| 0x08108102 | 1        | 1.56%   |
| 0x0810100b | 1        | 1.56%   |
| 0x08001138 | 1        | 1.56%   |
| 0x08001137 | 1        | 1.56%   |
| 0x06000852 | 1        | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 20       | 31.25%  |
| KabyLake    | 15       | 23.44%  |
| IvyBridge   | 7        | 10.94%  |
| SandyBridge | 4        | 6.25%   |
| Zen 2       | 3        | 4.69%   |
| Zen         | 3        | 4.69%   |
| Skylake     | 3        | 4.69%   |
| Broadwell   | 3        | 4.69%   |
| Penryn      | 2        | 3.13%   |
| Zen+        | 1        | 1.56%   |
| Westmere    | 1        | 1.56%   |
| Piledriver  | 1        | 1.56%   |
| CometLake   | 1        | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 35       | 47.3%   |
| Intel                      | 23       | 31.08%  |
| AMD                        | 10       | 13.51%  |
| Matrox Electronics Systems | 6        | 8.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 7.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 6.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.9%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 2.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.6%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.6%    |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 2.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.6%    |
| Intel HD Graphics 630                                                       | 2        | 2.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.6%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.3%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.3%    |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.3%    |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.3%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.3%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.3%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.3%    |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.3%    |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.3%    |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.3%    |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.3%    |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.3%    |
| Nvidia GF119 [NVS 315]                                                      | 1        | 1.3%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.3%    |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.3%    |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.3%    |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.3%    |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.3%    |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.3%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.3%    |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.3%    |
| Intel Iris Plus Graphics 640                                                | 1        | 1.3%    |
| Intel HD Graphics 530                                                       | 1        | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.3%    |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.3%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.3%    |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.3%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.3%    |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.3%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.3%    |
| AMD ES1000                                                                  | 1        | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.3%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 31       | 47.69%  |
| 1 x Intel      | 14       | 21.54%  |
| 1 x AMD        | 7        | 10.77%  |
| 1 x Matrox     | 6        | 9.23%   |
| 2 x Nvidia     | 2        | 3.08%   |
| Intel + Nvidia | 2        | 3.08%   |
| Intel + AMD    | 2        | 3.08%   |
| 2 x AMD        | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 42       | 64.62%  |
| Proprietary | 17       | 26.15%  |
| Unknown     | 6        | 9.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 42.65%  |
| 1.01-2.0   | 12       | 17.65%  |
| 7.01-8.0   | 7        | 10.29%  |
| 0.51-1.0   | 6        | 8.82%   |
| 3.01-4.0   | 4        | 5.88%   |
| 5.01-6.0   | 3        | 4.41%   |
| 2.01-3.0   | 3        | 4.41%   |
| 0.01-0.5   | 3        | 4.41%   |
| 8.01-16.0  | 1        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 14       | 20.59%  |
| Samsung Electronics  | 12       | 17.65%  |
| Goldstar             | 9        | 13.24%  |
| Lenovo               | 5        | 7.35%   |
| Hewlett-Packard      | 5        | 7.35%   |
| BenQ                 | 3        | 4.41%   |
| Ancor Communications | 3        | 4.41%   |
| ViewSonic            | 2        | 2.94%   |
| Philips              | 2        | 2.94%   |
| Lenovo Group Limited | 2        | 2.94%   |
| Iiyama               | 2        | 2.94%   |
| Gigabyte Technology  | 2        | 2.94%   |
| Eizo                 | 2        | 2.94%   |
| Acer                 | 2        | 2.94%   |
| LG Electronics       | 1        | 1.47%   |
| Insignia             | 1        | 1.47%   |
| Unknown              | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell IDRAC DEL0001 1280x1024                                           | 6        | 7.59%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 2.53%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 2.53%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch               | 2        | 2.53%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 2.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 2.53%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 1.27%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 1.27%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 1.27%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 1.27%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch  | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 1.27%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 1.27%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 1.27%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 700x390mm 31.5-inch      | 1        | 1.27%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 1        | 1.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.27%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.27%   |
| LG Electronics LCD Monitor W2486 1920x1080                             | 1        | 1.27%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch               | 1        | 1.27%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 1.27%   |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                 | 1        | 1.27%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                 | 1        | 1.27%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                 | 1        | 1.27%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10                           | 1        | 1.27%   |
| Insignia HDMI BBY4000 1920x1080 1152x648mm 52.0-inch                   | 1        | 1.27%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch           | 1        | 1.27%   |
| Hewlett-Packard LCD Monitor LA2306                                     | 1        | 1.27%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch          | 1        | 1.27%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch             | 1        | 1.27%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch             | 1        | 1.27%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 1        | 1.27%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch               | 1        | 1.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1        | 1.27%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch               | 1        | 1.27%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                | 1        | 1.27%   |
| Goldstar 26LB75  GSM5673 1920x1080 700x390mm 31.5-inch                 | 1        | 1.27%   |
| Goldstar 24GM77 GSM5A90 1920x1080 531x298mm 24.0-inch                  | 1        | 1.27%   |
| Goldstar 24GM77 GSM5A8F 1920x1080 531x298mm 24.0-inch                  | 1        | 1.27%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch       | 1        | 1.27%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch        | 1        | 1.27%   |
| Eizo LCD Monitor EV2416W                                               | 1        | 1.27%   |
| Eizo CS2420 ENC2956 1920x1200 519x324mm 24.1-inch                      | 1        | 1.27%   |
| Dell UP2716D DEL40DD 2560x1440 597x336mm 27.0-inch                     | 1        | 1.27%   |
| Dell U2917W DEL40F9 2560x1080 673x284mm 28.8-inch                      | 1        | 1.27%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                      | 1        | 1.27%   |
| Dell U2312HM DEL4073 1920x1080 510x290mm 23.1-inch                     | 1        | 1.27%   |
| Dell S2719H DELD0CD 1920x1080 598x336mm 27.0-inch                      | 1        | 1.27%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                      | 1        | 1.27%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                      | 1        | 1.27%   |
| Dell LNKG H2VA001 LNKA001 1920x1080 880x500mm 39.8-inch                | 1        | 1.27%   |
| Dell LCD Monitor U2413 3840x1200                                       | 1        | 1.27%   |
| Dell LCD Monitor P2719H 1920x1080                                      | 1        | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 44.12%  |
| 1280x1024 (SXGA)   | 6        | 8.82%   |
| 3840x2160 (4K)     | 5        | 7.35%   |
| 2560x1440 (QHD)    | 5        | 7.35%   |
| 3840x1080          | 3        | 4.41%   |
| 3440x1440          | 3        | 4.41%   |
| 2560x1080          | 3        | 4.41%   |
| 1600x900 (HD+)     | 3        | 4.41%   |
| Unknown            | 3        | 4.41%   |
| 9600x2160          | 1        | 1.47%   |
| 7680x2160          | 1        | 1.47%   |
| 3840x1200          | 1        | 1.47%   |
| 1920x1200 (WUXGA)  | 1        | 1.47%   |
| 1680x1050 (WSXGA+) | 1        | 1.47%   |
| 1440x900 (WXGA+)   | 1        | 1.47%   |
| 1280x720 (HD)      | 1        | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 22.86%  |
| 23      | 10       | 14.29%  |
| 24      | 8        | 11.43%  |
| 21      | 8        | 11.43%  |
| 27      | 7        | 10%     |
| 31      | 4        | 5.71%   |
| 54      | 3        | 4.29%   |
| 34      | 3        | 4.29%   |
| 20      | 3        | 4.29%   |
| 47      | 2        | 2.86%   |
| 64      | 1        | 1.43%   |
| 40      | 1        | 1.43%   |
| 39      | 1        | 1.43%   |
| 28      | 1        | 1.43%   |
| 25      | 1        | 1.43%   |
| 18      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 35.82%  |
| Unknown     | 16       | 23.88%  |
| 401-500     | 11       | 16.42%  |
| 1001-1500   | 6        | 8.96%   |
| 601-700     | 5        | 7.46%   |
| 701-800     | 3        | 4.48%   |
| 801-900     | 2        | 2.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 63.33%  |
| Unknown | 8        | 13.33%  |
| 5/4     | 6        | 10%     |
| 21/9    | 4        | 6.67%   |
| 16/10   | 4        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 31.34%  |
| Unknown        | 16       | 23.88%  |
| 351-500        | 7        | 10.45%  |
| 301-350        | 7        | 10.45%  |
| More than 1000 | 4        | 5.97%   |
| 251-300        | 4        | 5.97%   |
| 151-200        | 4        | 5.97%   |
| 501-1000       | 4        | 5.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 32       | 48.48%  |
| Unknown | 16       | 24.24%  |
| 101-120 | 10       | 15.15%  |
| 1-50    | 5        | 7.58%   |
| 161-240 | 2        | 3.03%   |
| 121-160 | 1        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 72.06%  |
| 2     | 8        | 11.76%  |
| 0     | 6        | 8.82%   |
| 3     | 5        | 7.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 42       | 43.3%   |
| Realtek Semiconductor    | 24       | 24.74%  |
| Broadcom                 | 9        | 9.28%   |
| Qualcomm Atheros         | 7        | 7.22%   |
| Ralink Technology        | 2        | 2.06%   |
| Dell                     | 2        | 2.06%   |
| ASIX Electronics         | 2        | 2.06%   |
| Ralink                   | 1        | 1.03%   |
| Microchip Technology     | 1        | 1.03%   |
| Micro Star International | 1        | 1.03%   |
| MediaTek                 | 1        | 1.03%   |
| Huawei Technologies      | 1        | 1.03%   |
| D-Link                   | 1        | 1.03%   |
| Broadcom Limited         | 1        | 1.03%   |
| Arduino SA               | 1        | 1.03%   |
| Aquantia                 | 1        | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21       | 16.67%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.76%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.97%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 3.17%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 3.17%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 3.17%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 3.17%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.38%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 2.38%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 2.38%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 1.59%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 1.59%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.59%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.59%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 1.59%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 1.59%   |
| Dell iDRAC Virtual NIC                                                        | 2        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.79%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.79%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.79%   |
| Ralink RT5372 Wireless Adapter                                                | 1        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.79%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.79%   |
| Microchip TrueRNG                                                             | 1        | 0.79%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 0.79%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 0.79%   |
| Intel Wireless 7260                                                           | 1        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.79%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.79%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.79%   |
| Huawei Modem/Networkcard                                                      | 1        | 0.79%   |
| D-Link 802.11n WLAN Adapter                                                   | 1        | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.79%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 0.79%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.79%   |
| Arduino SA Uno (CDC ACM)                                                      | 1        | 0.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 8        | 28.57%  |
| Qualcomm Atheros         | 6        | 21.43%  |
| Realtek Semiconductor    | 4        | 14.29%  |
| Broadcom                 | 4        | 14.29%  |
| Ralink Technology        | 2        | 7.14%   |
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
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 10.71%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 7.14%   |
| Intel Wireless-AC 9260                                                     | 2        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 3.57%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 3.57%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 3.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.57%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.57%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 3.57%   |
| Intel Wireless 7260                                                        | 1        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 3.57%   |
| D-Link 802.11n WLAN Adapter                                                | 1        | 3.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 42       | 56%     |
| Realtek Semiconductor | 22       | 29.33%  |
| Broadcom              | 5        | 6.67%   |
| Qualcomm Atheros      | 2        | 2.67%   |
| ASIX Electronics      | 2        | 2.67%   |
| Broadcom Limited      | 1        | 1.33%   |
| Aquantia              | 1        | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 21       | 22.58%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 7.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 6.45%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 5.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 4.3%    |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 4.3%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 4.3%    |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.23%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 3.23%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3.23%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 3.23%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.15%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.15%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.15%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 2.15%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 2.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.08%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.08%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.08%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.08%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.08%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 65.98%  |
| WiFi     | 28       | 28.87%  |
| Modem    | 3        | 3.09%   |
| Unknown  | 2        | 2.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 83.08%  |
| WiFi     | 11       | 16.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 41.54%  |
| 2     | 17       | 26.15%  |
| 3     | 11       | 16.92%  |
| 6     | 5        | 7.69%   |
| 4     | 4        | 6.15%   |
| 5     | 1        | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 87.69%  |
| Yes  | 8        | 12.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 27.27%  |
| Cambridge Silicon Radio         | 6        | 27.27%  |
| ASUSTek Computer                | 3        | 13.64%  |
| Realtek Semiconductor           | 2        | 9.09%   |
| Qualcomm Atheros Communications | 2        | 9.09%   |
| Micro Star International        | 1        | 4.55%   |
| IMC Networks                    | 1        | 4.55%   |
| Broadcom                        | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 27.27%  |
| Realtek Bluetooth Radio                               | 2        | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 9.09%   |
| ASUS BCM20702A0                                       | 2        | 9.09%   |
| Micro Star International Bluetooth Device             | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.55%   |
| Intel Bluetooth wireless interface                    | 1        | 4.55%   |
| Intel AX200 Bluetooth                                 | 1        | 4.55%   |
| IMC Networks BCM20702A0                               | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 46       | 42.59%  |
| Nvidia                    | 33       | 30.56%  |
| AMD                       | 13       | 12.04%  |
| Lenovo                    | 3        | 2.78%   |
| Creative Labs             | 3        | 2.78%   |
| Texas Instruments         | 1        | 0.93%   |
| Tenx Technology           | 1        | 0.93%   |
| Sennheiser Communications | 1        | 0.93%   |
| RODE Microphones          | 1        | 0.93%   |
| Plantronics               | 1        | 0.93%   |
| Logitech                  | 1        | 0.93%   |
| JMTek                     | 1        | 0.93%   |
| Dynex                     | 1        | 0.93%   |
| Creative Technology       | 1        | 0.93%   |
| ASUSTek Computer          | 1        | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 7.56%   |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 6.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6        | 5.04%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 5        | 4.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 4.2%    |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 3.36%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 3.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 3.36%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.52%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 2.52%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 3        | 2.52%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.52%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2        | 1.68%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 1.68%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 1.68%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.84%   |
| Tenx Technology USB AUDIO                                                         | 1        | 0.84%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                         | 1        | 0.84%   |
| RODE Microphones RODE NT-USB                                                      | 1        | 0.84%   |
| Plantronics BT600                                                                 | 1        | 0.84%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 0.84%   |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.84%   |
| Nvidia GF114 HDMI Audio Controller                                                | 1        | 0.84%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.84%   |
| Logitech H570e Mono                                                               | 1        | 0.84%   |
| JMTek USB Speaker                                                                 | 1        | 0.84%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 0.84%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 0.84%   |
| Dynex USB MIC Device                                                              | 1        | 0.84%   |
| Creative Technology Sound Blaster Tactic(3D) Alpha                                | 1        | 0.84%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1        | 0.84%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 1        | 0.84%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                            | 1        | 0.84%   |
| ASUSTek Computer Xonar U3 sound card                                              | 1        | 0.84%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 1        | 0.84%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 18.92%  |
| Micron Technology   | 7        | 18.92%  |
| SK hynix            | 6        | 16.22%  |
| Crucial             | 6        | 16.22%  |
| Kingston            | 3        | 8.11%   |
| Corsair             | 3        | 8.11%   |
| Unknown (0x0205)    | 1        | 2.7%    |
| Unknown             | 1        | 2.7%    |
| Transcend           | 1        | 2.7%    |
| Patriot             | 1        | 2.7%    |
| Goodram             | 1        | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s    | 2        | 4.76%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16384MB DIMM DDR4 2133MT/s    | 2        | 4.76%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s        | 2        | 4.76%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s        | 2        | 4.76%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s      | 2        | 4.76%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1        | 2.38%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s          | 1        | 2.38%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s            | 1        | 2.38%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s     | 1        | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s     | 1        | 2.38%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s        | 1        | 2.38%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                   | 1        | 2.38%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 1        | 2.38%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                  | 1        | 2.38%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s        | 1        | 2.38%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 1        | 2.38%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s      | 1        | 2.38%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s         | 1        | 2.38%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s      | 1        | 2.38%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s            | 1        | 2.38%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 2.38%   |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s         | 1        | 2.38%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s        | 1        | 2.38%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s         | 1        | 2.38%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s         | 1        | 2.38%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 2.38%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s        | 1        | 2.38%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s     | 1        | 2.38%   |
| Goodram RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s        | 1        | 2.38%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s       | 1        | 2.38%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s        | 1        | 2.38%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16384MB DIMM DDR4 2933MT/s | 1        | 2.38%   |
| Crucial RAM BLT4G3D1608ET3LX0. 4GB DIMM DDR3 1600MT/s       | 1        | 2.38%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s      | 1        | 2.38%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s       | 1        | 2.38%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s       | 1        | 2.38%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s       | 1        | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 18       | 56.25%  |
| DDR3  | 8        | 25%     |
| SDRAM | 3        | 9.38%   |
| DRAM  | 2        | 6.25%   |
| DDR2  | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 29       | 93.55%  |
| SODIMM | 1        | 3.23%   |
| RIMM   | 1        | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 11       | 31.43%  |
| 8192  | 9        | 25.71%  |
| 4096  | 9        | 25.71%  |
| 32768 | 3        | 8.57%   |
| 2048  | 2        | 5.71%   |
| 1024  | 1        | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 8        | 23.53%  |
| 1600  | 8        | 23.53%  |
| 2133  | 6        | 17.65%  |
| 2667  | 3        | 8.82%   |
| 3600  | 2        | 5.88%   |
| 1333  | 2        | 5.88%   |
| 3200  | 1        | 2.94%   |
| 2933  | 1        | 2.94%   |
| 2666  | 1        | 2.94%   |
| 2048  | 1        | 2.94%   |
| 800   | 1        | 2.94%   |

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
| Unknown                | 3        | 23.08%  |
| Logitech               | 3        | 23.08%  |
| Generalplus Technology | 2        | 15.38%  |
| Samsung Electronics    | 1        | 7.69%   |
| Ruision                | 1        | 7.69%   |
| Microsoft              | 1        | 7.69%   |
| Jieli Technology       | 1        | 7.69%   |
| ARC International      | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown FULL HD 1080P Webcam            | 3        | 23.08%  |
| Generalplus GENERAL WEBCAM              | 2        | 15.38%  |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 7.69%   |
| Ruision UVC Camera                      | 1        | 7.69%   |
| Microsoft LifeCam HD-3000               | 1        | 7.69%   |
| Logitech Webcam C270                    | 1        | 7.69%   |
| Logitech Webcam C250                    | 1        | 7.69%   |
| Logitech HD Webcam C910                 | 1        | 7.69%   |
| Jieli USB PHY 2.0                       | 1        | 7.69%   |
| ARC International Camera                | 1        | 7.69%   |

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
| 0     | 45       | 69.23%  |
| 2     | 9        | 13.85%  |
| 1     | 9        | 13.85%  |
| 5     | 1        | 1.54%   |
| 3     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 13       | 39.39%  |
| Communication controller | 7        | 21.21%  |
| Graphics card            | 6        | 18.18%  |
| Net/wireless             | 4        | 12.12%  |
| Storage/ide              | 1        | 3.03%   |
| Sound                    | 1        | 3.03%   |
| Bluetooth                | 1        | 3.03%   |

