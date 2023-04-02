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

Total: 119

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X670E AORUS MASTER          | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Gigabyte      | X570 UD                     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Gigabyte      | H510M H                     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Unknown       | Unknown                     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| Gigabyte      | Z590I VISION D              | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| HP            | 8591                        | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
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
| RHEL 8 | 54       | 68.35%  |
| RHEL 9 | 13       | 16.46%  |
| RHEL 7 | 12       | 15.19%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| RHEL | 79       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 7.53%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 6.45%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 5.38%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 4        | 4.3%    |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 4.3%    |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 4.3%    |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 3.23%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 3.23%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 3.23%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 3.23%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 3.23%   |
| 3.10.0-862.3.2.el7.x86_64    | 3        | 3.23%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 2.15%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 2.15%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 2.15%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 2.15%   |
| 4.18.0-193.el8.x86_64        | 2        | 2.15%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 2.15%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 2.15%   |
| 4.18.0-147.el8.x86_64        | 2        | 2.15%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 1.08%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1        | 1.08%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 1        | 1.08%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.08%   |
| 4.19.150                     | 1        | 1.08%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.08%   |
| 4.18.0-425.3.1.el8.x86_64    | 1        | 1.08%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 1        | 1.08%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 1.08%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 1        | 1.08%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1        | 1.08%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.08%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.08%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.08%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.08%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.08%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.08%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.08%   |
| 4.18.0-193.1.2.el8_2.x86_64  | 1        | 1.08%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 52       | 65.82%  |
| 5.14.0   | 13       | 16.46%  |
| 3.10.0   | 12       | 15.19%  |
| 5.10.6   | 1        | 1.27%   |
| 4.19.150 | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 52       | 65.82%  |
| 5.14    | 13       | 16.46%  |
| 3.10    | 12       | 15.19%  |
| 5.10    | 1        | 1.27%   |
| 4.19    | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 79       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 57       | 69.51%  |
| Unknown       | 16       | 19.51%  |
| GNOME Classic | 4        | 4.88%   |
| KDE5          | 2        | 2.44%   |
| KDE           | 2        | 2.44%   |
| MATE          | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 42       | 51.22%  |
| Wayland | 32       | 39.02%  |
| Unknown | 7        | 8.54%   |
| Tty     | 1        | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 71.95%  |
| GDM     | 22       | 26.83%  |
| LightDM | 1        | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 41       | 51.25%  |
| Unknown | 13       | 16.25%  |
| en_GB   | 6        | 7.5%    |
| en_IN   | 4        | 5%      |
| ru_RU   | 3        | 3.75%   |
| pl_PL   | 2        | 2.5%    |
| es_AR   | 2        | 2.5%    |
| de_DE   | 2        | 2.5%    |
| sl_SI   | 1        | 1.25%   |
| ko_KR   | 1        | 1.25%   |
| ja_JP   | 1        | 1.25%   |
| es_MX   | 1        | 1.25%   |
| es_ES   | 1        | 1.25%   |
| en_NZ   | 1        | 1.25%   |
| cs_CZ   | 1        | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 48       | 60%     |
| BIOS | 32       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 72       | 90%     |
| Ext4    | 5        | 6.25%   |
| Unknown | 3        | 3.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 53.66%  |
| GPT     | 26       | 31.71%  |
| MBR     | 12       | 14.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 77.5%   |
| Yes       | 18       | 22.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 88.75%  |
| Yes       | 9        | 11.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 16       | 20.25%  |
| ASUSTek Computer    | 14       | 17.72%  |
| Hewlett-Packard     | 11       | 13.92%  |
| Gigabyte Technology | 11       | 13.92%  |
| MSI                 | 6        | 7.59%   |
| ASRock              | 6        | 7.59%   |
| Lenovo              | 4        | 5.06%   |
| Unknown             | 4        | 5.06%   |
| Intel               | 2        | 2.53%   |
| Supermicro          | 1        | 1.27%   |
| Hardkernel          | 1        | 1.27%   |
| CX / Air Computers. | 1        | 1.27%   |
| Alienware           | 1        | 1.27%   |
| Acer                | 1        | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell PowerEdge FC630                | 6        | 7.59%   |
| ASUS All Series                     | 4        | 5.06%   |
| Unknown                             | 4        | 5.06%   |
| HP Z620 Workstation                 | 2        | 2.53%   |
| Dell OptiPlex 9020                  | 2        | 2.53%   |
| Supermicro X7DW3                    | 1        | 1.27%   |
| MSI MS-7C95                         | 1        | 1.27%   |
| MSI MS-7B89                         | 1        | 1.27%   |
| MSI MS-7B51                         | 1        | 1.27%   |
| MSI MS-7B33                         | 1        | 1.27%   |
| MSI MS-7A37                         | 1        | 1.27%   |
| MSI MS-7752                         | 1        | 1.27%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 1.27%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 1.27%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 1.27%   |
| Lenovo 10SFS03200                   | 1        | 1.27%   |
| Intel H81                           | 1        | 1.27%   |
| Intel DX79SR AAG57199-200           | 1        | 1.27%   |
| HP Z840 Workstation                 | 1        | 1.27%   |
| HP Z440 Workstation                 | 1        | 1.27%   |
| HP Z230 Tower Workstation           | 1        | 1.27%   |
| HP Z230 SFF Workstation             | 1        | 1.27%   |
| HP Z1 Entry Tower G5                | 1        | 1.27%   |
| HP ProLiant MicroServer Gen8        | 1        | 1.27%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.27%   |
| HP 290 G1 SFF Business PC           | 1        | 1.27%   |
| HP 260-P020il                       | 1        | 1.27%   |
| Hardkernel ODROID-H3                | 1        | 1.27%   |
| Gigabyte Z97N-WIFI                  | 1        | 1.27%   |
| Gigabyte Z590I VISION D             | 1        | 1.27%   |
| Gigabyte Z490 GAMING X              | 1        | 1.27%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 1.27%   |
| Gigabyte X670E AORUS MASTER         | 1        | 1.27%   |
| Gigabyte X570 UD                    | 1        | 1.27%   |
| Gigabyte H510M H                    | 1        | 1.27%   |
| Gigabyte B85M-D3V-A                 | 1        | 1.27%   |
| Gigabyte B75-D3V                    | 1        | 1.27%   |
| Gigabyte B150-HD3                   | 1        | 1.27%   |
| Gigabyte 970A-D3                    | 1        | 1.27%   |
| Dell Vostro 270                     | 1        | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell PowerEdge       | 6        | 7.59%   |
| Dell Precision       | 5        | 6.33%   |
| ASUS PRIME           | 5        | 6.33%   |
| ASUS All             | 4        | 5.06%   |
| Unknown              | 4        | 5.06%   |
| Lenovo ThinkCentre   | 3        | 3.8%    |
| Dell OptiPlex        | 3        | 3.8%    |
| HP Z620              | 2        | 2.53%   |
| HP Z230              | 2        | 2.53%   |
| ASUS ROG             | 2        | 2.53%   |
| Supermicro X7DW3     | 1        | 1.27%   |
| MSI MS-7C95          | 1        | 1.27%   |
| MSI MS-7B89          | 1        | 1.27%   |
| MSI MS-7B51          | 1        | 1.27%   |
| MSI MS-7B33          | 1        | 1.27%   |
| MSI MS-7A37          | 1        | 1.27%   |
| MSI MS-7752          | 1        | 1.27%   |
| Lenovo 10SFS03200    | 1        | 1.27%   |
| Intel H81            | 1        | 1.27%   |
| Intel DX79SR         | 1        | 1.27%   |
| HP Z840              | 1        | 1.27%   |
| HP Z440              | 1        | 1.27%   |
| HP Z1                | 1        | 1.27%   |
| HP ProLiant          | 1        | 1.27%   |
| HP EliteDesk         | 1        | 1.27%   |
| HP 290               | 1        | 1.27%   |
| HP 260-P020il        | 1        | 1.27%   |
| Hardkernel ODROID-H3 | 1        | 1.27%   |
| Gigabyte Z97N-WIFI   | 1        | 1.27%   |
| Gigabyte Z590I       | 1        | 1.27%   |
| Gigabyte Z490        | 1        | 1.27%   |
| Gigabyte Z390        | 1        | 1.27%   |
| Gigabyte X670E       | 1        | 1.27%   |
| Gigabyte X570        | 1        | 1.27%   |
| Gigabyte H510M       | 1        | 1.27%   |
| Gigabyte B85M-D3V-A  | 1        | 1.27%   |
| Gigabyte B75-D3V     | 1        | 1.27%   |
| Gigabyte B150-HD3    | 1        | 1.27%   |
| Gigabyte 970A-D3     | 1        | 1.27%   |
| Dell Vostro          | 1        | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 12       | 15.19%  |
| 2018 | 10       | 12.66%  |
| 2019 | 9        | 11.39%  |
| 2017 | 8        | 10.13%  |
| 2012 | 8        | 10.13%  |
| 2015 | 6        | 7.59%   |
| 2013 | 6        | 7.59%   |
| 2021 | 5        | 6.33%   |
| 2020 | 5        | 6.33%   |
| 2022 | 3        | 3.8%    |
| 2014 | 2        | 2.53%   |
| 2009 | 2        | 2.53%   |
| 2023 | 1        | 1.27%   |
| 2011 | 1        | 1.27%   |
| 2010 | 1        | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 79       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 74       | 92.5%   |
| Enabled  | 6        | 7.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 79       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 20       | 24.39%  |
| 32.01-64.0      | 15       | 18.29%  |
| 8.01-16.0       | 13       | 15.85%  |
| 4.01-8.0        | 12       | 14.63%  |
| 16.01-24.0      | 11       | 13.41%  |
| 24.01-32.0      | 7        | 8.54%   |
| More than 256.0 | 2        | 2.44%   |
| 3.01-4.0        | 1        | 1.22%   |
| 2.01-3.0        | 1        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 26       | 29.21%  |
| 4.01-8.0   | 25       | 28.09%  |
| 3.01-4.0   | 13       | 14.61%  |
| 8.01-16.0  | 13       | 14.61%  |
| 1.01-2.0   | 8        | 8.99%   |
| 16.01-24.0 | 2        | 2.25%   |
| 24.01-32.0 | 1        | 1.12%   |
| 0.51-1.0   | 1        | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 32.14%  |
| 1      | 21       | 25%     |
| 3      | 13       | 15.48%  |
| 5      | 9        | 10.71%  |
| 4      | 8        | 9.52%   |
| 12     | 3        | 3.57%   |
| 8      | 2        | 2.38%   |
| 6      | 1        | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 60%     |
| Yes       | 32       | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 51.9%   |
| Yes       | 38       | 48.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 60.76%  |
| Yes       | 31       | 39.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 15       | 18.99%  |
| Germany      | 10       | 12.66%  |
| UK           | 7        | 8.86%   |
| India        | 6        | 7.59%   |
| Czechia      | 5        | 6.33%   |
| Canada       | 5        | 6.33%   |
| Russia       | 3        | 3.8%    |
| Ukraine      | 2        | 2.53%   |
| South Korea  | 2        | 2.53%   |
| Poland       | 2        | 2.53%   |
| Italy        | 2        | 2.53%   |
| Argentina    | 2        | 2.53%   |
| Turkmenistan | 1        | 1.27%   |
| Switzerland  | 1        | 1.27%   |
| Sweden       | 1        | 1.27%   |
| Spain        | 1        | 1.27%   |
| Slovenia     | 1        | 1.27%   |
| New Zealand  | 1        | 1.27%   |
| Netherlands  | 1        | 1.27%   |
| Mexico       | 1        | 1.27%   |
| Lithuania    | 1        | 1.27%   |
| Japan        | 1        | 1.27%   |
| Indonesia    | 1        | 1.27%   |
| Finland      | 1        | 1.27%   |
| Egypt        | 1        | 1.27%   |
| China        | 1        | 1.27%   |
| Brazil       | 1        | 1.27%   |
| Belgium      | 1        | 1.27%   |
| Belarus      | 1        | 1.27%   |
| Austria      | 1        | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Langgons              | 6        | 7.32%   |
| Prague                | 4        | 4.88%   |
| Kyiv                  | 2        | 2.44%   |
| Chicago               | 2        | 2.44%   |
| Bengaluru             | 2        | 2.44%   |
| Yorktown Heights      | 1        | 1.22%   |
| Yongin-si             | 1        | 1.22%   |
| Wiesbaden             | 1        | 1.22%   |
| Vienna                | 1        | 1.22%   |
| Vaglio                | 1        | 1.22%   |
| Turku                 | 1        | 1.22%   |
| Toronto               | 1        | 1.22%   |
| Tiruchi               | 1        | 1.22%   |
| Tauranga              | 1        | 1.22%   |
| Sutton                | 1        | 1.22%   |
| Stavropol             | 1        | 1.22%   |
| Spokane               | 1        | 1.22%   |
| Šiauliai             | 1        | 1.22%   |
| Saratov               | 1        | 1.22%   |
| San Jose              | 1        | 1.22%   |
| San Fernando          | 1        | 1.22%   |
| Salvador              | 1        | 1.22%   |
| Saltillo              | 1        | 1.22%   |
| Sainte-Marie          | 1        | 1.22%   |
| Rosario               | 1        | 1.22%   |
| Rensselaer            | 1        | 1.22%   |
| Reading               | 1        | 1.22%   |
| Pforzheim             | 1        | 1.22%   |
| Pernis                | 1        | 1.22%   |
| Paracuellos de Jarama | 1        | 1.22%   |
| Oldham                | 1        | 1.22%   |
| Musselburgh           | 1        | 1.22%   |
| Morton                | 1        | 1.22%   |
| Montreal              | 1        | 1.22%   |
| Mississauga           | 1        | 1.22%   |
| Minsk                 | 1        | 1.22%   |
| Milwaukee             | 1        | 1.22%   |
| Milan                 | 1        | 1.22%   |
| Lodz                  | 1        | 1.22%   |
| Ljutomer              | 1        | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 29       | 60     | 17.68%  |
| WDC                       | 28       | 53     | 17.07%  |
| Samsung Electronics       | 20       | 35     | 12.2%   |
| Toshiba                   | 10       | 15     | 6.1%    |
| Kingston                  | 9        | 13     | 5.49%   |
| SanDisk                   | 6        | 12     | 3.66%   |
| Phison                    | 5        | 9      | 3.05%   |
| Crucial                   | 5        | 9      | 3.05%   |
| SK hynix                  | 4        | 6      | 2.44%   |
| Hitachi                   | 4        | 4      | 2.44%   |
| Dell                      | 4        | 8      | 2.44%   |
| A-DATA Technology         | 4        | 4      | 2.44%   |
| Micron Technology         | 3        | 3      | 1.83%   |
| Intel                     | 3        | 5      | 1.83%   |
| Gigabyte Technology       | 3        | 4      | 1.83%   |
| China                     | 3        | 3      | 1.83%   |
| Unknown                   | 2        | 2      | 1.22%   |
| PNY                       | 2        | 2      | 1.22%   |
| Micron/Crucial Technology | 2        | 2      | 1.22%   |
| Corsair                   | 2        | 5      | 1.22%   |
| XUM                       | 1        | 1      | 0.61%   |
| XPG                       | 1        | 1      | 0.61%   |
| Western Digital           | 1        | 1      | 0.61%   |
| T-FORCE                   | 1        | 2      | 0.61%   |
| Silicon Motion            | 1        | 1      | 0.61%   |
| SCST_FIO                  | 1        | 9      | 0.61%   |
| OCZ                       | 1        | 2      | 0.61%   |
| KingSpec                  | 1        | 1      | 0.61%   |
| KingFast                  | 1        | 1      | 0.61%   |
| KINGBANK                  | 1        | 1      | 0.61%   |
| HPT                       | 1        | 1      | 0.61%   |
| Hoodisk                   | 1        | 1      | 0.61%   |
| HGST                      | 1        | 1      | 0.61%   |
| Hewlett-Packard           | 1        | 1      | 0.61%   |
| Anobit                    | 1        | 1      | 0.61%   |
| ADATA Technology          | 1        | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Dell MD34xx 26TB                     | 4        | 2.02%   |
| Samsung SSD 860 EVO 1TB              | 3        | 1.52%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 2        | 1.01%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 2        | 1.01%   |
| Unknown SD/MMC/MS PRO 64GB           | 2        | 1.01%   |
| Toshiba NVMe SSD Drive 256GB         | 2        | 1.01%   |
| Toshiba DT01ACA200 2TB               | 2        | 1.01%   |
| Toshiba AL14SEB18EQ 1.8TB            | 2        | 1.01%   |
| Seagate ST91000640NS 1TB             | 2        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 1.01%   |
| Seagate ST2000NX0433 2TB             | 2        | 1.01%   |
| Seagate ST2000NX0273 2TB             | 2        | 1.01%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 1.01%   |
| Seagate ST1000DM003-9YN162 1TB       | 2        | 1.01%   |
| Samsung SSD 860 EVO 500GB            | 2        | 1.01%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 1.01%   |
| Samsung NVMe SSD Drive 500GB         | 2        | 1.01%   |
| Kingston SUV500120G 120GB SSD        | 2        | 1.01%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 1.01%   |
| Crucial CT240BX500SSD1 240GB         | 2        | 1.01%   |
| Corsair Force LE SSD 240GB           | 2        | 1.01%   |
| XUM HX256GSSDSATA3 256GB             | 1        | 0.51%   |
| XPG NVMe SSD Drive 1024GB            | 1        | 0.51%   |
| Western Digital NVMe SSD Drive 960GB | 1        | 0.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.51%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.51%   |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 1        | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1        | 0.51%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1        | 0.51%   |
| WDC WD60 EFAX-68JH4N1 6TB            | 1        | 0.51%   |
| WDC WD60 EFAX-68JH4N0 6TB            | 1        | 0.51%   |
| WDC WD5003ABYZ-011FA0 500GB          | 1        | 0.51%   |
| WDC WD5000HHTZ-04N21V0 500GB         | 1        | 0.51%   |
| WDC WD5000AVCS-632DY1 500GB          | 1        | 0.51%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 0.51%   |
| WDC WD50 00LPVX-00V0TT0 500GB        | 1        | 0.51%   |
| WDC WD40PURZ-85TTDY0 4TB             | 1        | 0.51%   |
| WDC WD40EZRZ-19GXCB0 4TB             | 1        | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB             | 1        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 60     | 37.66%  |
| WDC                 | 26       | 48     | 33.77%  |
| Toshiba             | 8        | 12     | 10.39%  |
| Hitachi             | 4        | 4      | 5.19%   |
| Dell                | 4        | 8      | 5.19%   |
| Unknown             | 2        | 2      | 2.6%    |
| SCST_FIO            | 1        | 9      | 1.3%    |
| Samsung Electronics | 1        | 2      | 1.3%    |
| HGST                | 1        | 1      | 1.3%    |
| Hewlett-Packard     | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 19     | 22.41%  |
| Kingston            | 9        | 13     | 15.52%  |
| Crucial             | 5        | 9      | 8.62%   |
| WDC                 | 4        | 5      | 6.9%    |
| SanDisk             | 3        | 8      | 5.17%   |
| Micron Technology   | 3        | 3      | 5.17%   |
| China               | 3        | 3      | 5.17%   |
| A-DATA Technology   | 3        | 3      | 5.17%   |
| SK hynix            | 2        | 4      | 3.45%   |
| PNY                 | 2        | 2      | 3.45%   |
| Intel               | 2        | 3      | 3.45%   |
| Corsair             | 2        | 5      | 3.45%   |
| XUM                 | 1        | 1      | 1.72%   |
| OCZ                 | 1        | 2      | 1.72%   |
| KingSpec            | 1        | 1      | 1.72%   |
| KINGBANK            | 1        | 1      | 1.72%   |
| Hoodisk             | 1        | 1      | 1.72%   |
| Gigabyte Technology | 1        | 1      | 1.72%   |
| Anobit              | 1        | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 56       | 147    | 41.48%  |
| SSD     | 51       | 85     | 37.78%  |
| NVMe    | 25       | 44     | 18.52%  |
| Unknown | 3        | 4      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 73       | 216    | 67.59%  |
| NVMe | 25       | 44     | 23.15%  |
| SAS  | 10       | 20     | 9.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 50       | 98     | 41.67%  |
| 0.51-1.0   | 34       | 55     | 28.33%  |
| 1.01-2.0   | 19       | 44     | 15.83%  |
| 3.01-4.0   | 8        | 14     | 6.67%   |
| 20.01-50.0 | 4        | 8      | 3.33%   |
| 4.01-10.0  | 3        | 10     | 2.5%    |
| 2.01-3.0   | 1        | 1      | 0.83%   |
| 10.01-20.0 | 1        | 2      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 21.43%  |
| 501-1000       | 16       | 19.05%  |
| 251-500        | 13       | 15.48%  |
| More than 3000 | 11       | 13.1%   |
| 1001-2000      | 9        | 10.71%  |
| Unknown        | 9        | 10.71%  |
| 2001-3000      | 5        | 5.95%   |
| 51-100         | 3        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 19       | 21.11%  |
| 1-20           | 19       | 21.11%  |
| 101-250        | 13       | 14.44%  |
| 51-100         | 10       | 11.11%  |
| Unknown        | 9        | 10%     |
| 251-500        | 6        | 6.67%   |
| 1001-2000      | 5        | 5.56%   |
| 501-1000       | 4        | 4.44%   |
| More than 3000 | 3        | 3.33%   |
| 2001-3000      | 2        | 2.22%   |

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
| Detected | 45       | 166    | 52.33%  |
| Works    | 35       | 106    | 40.7%   |
| Malfunc  | 6        | 8      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 65       | 51.59%  |
| AMD                          | 13       | 10.32%  |
| Samsung Electronics          | 11       | 8.73%   |
| Broadcom / LSI               | 8        | 6.35%   |
| Phison Electronics           | 6        | 4.76%   |
| ASMedia Technology           | 4        | 3.17%   |
| Marvell Technology Group     | 3        | 2.38%   |
| ADATA Technology             | 3        | 2.38%   |
| Toshiba America Info Systems | 2        | 1.59%   |
| SK hynix                     | 2        | 1.59%   |
| SanDisk                      | 2        | 1.59%   |
| Micron/Crucial Technology    | 2        | 1.59%   |
| LSI Logic / Symbios Logic    | 2        | 1.59%   |
| Western Digital              | 1        | 0.79%   |
| Silicon Motion               | 1        | 0.79%   |
| HighPoint Technologies       | 1        | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 11       | 7.05%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 10       | 6.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 6.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9        | 5.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9        | 5.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6        | 3.85%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 6        | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 3.21%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.56%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 4        | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 2.56%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 1.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.92%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2        | 1.28%   |
| SK hynix Non-Volatile memory controller                                        | 2        | 1.28%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 1.28%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.28%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 1.28%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2        | 1.28%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 2        | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.28%   |
| ADATA ADATA XPG GAMMIXS1 1L Media                                              | 2        | 1.28%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                    | 1        | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.64%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.64%   |
| Micron/Crucial NVMe Storage Controller                                         | 1        | 0.64%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 0.64%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 1        | 0.64%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                          | 1        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 56.35%  |
| NVMe | 26       | 20.63%  |
| RAID | 16       | 12.7%   |
| SAS  | 8        | 6.35%   |
| IDE  | 5        | 3.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 66       | 83.54%  |
| AMD    | 13       | 16.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz        | 4        | 5.06%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 4        | 5.06%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz     | 2        | 2.53%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 2        | 2.53%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 2        | 2.53%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 2        | 2.53%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 2        | 2.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2        | 2.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2        | 2.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 2        | 2.53%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2        | 2.53%   |
| Intel Xeon CPU E5472 @ 3.00GHz          | 1        | 1.27%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz     | 1        | 1.27%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 1.27%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1        | 1.27%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz     | 1        | 1.27%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1        | 1.27%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz     | 1        | 1.27%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz     | 1        | 1.27%   |
| Intel Xeon CPU E3-1280 V2 @ 3.60GHz     | 1        | 1.27%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz     | 1        | 1.27%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz     | 1        | 1.27%   |
| Intel Pentium Silver N6005 @ 2.00GHz    | 1        | 1.27%   |
| Intel Core i9-9900 CPU @ 3.10GHz        | 1        | 1.27%   |
| Intel Core i7-9700F CPU @ 3.00GHz       | 1        | 1.27%   |
| Intel Core i7-7560U CPU @ 2.40GHz       | 1        | 1.27%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 1.27%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1        | 1.27%   |
| Intel Core i7-3820 CPU @ 3.60GHz        | 1        | 1.27%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 1        | 1.27%   |
| Intel Core i7 CPU X 990 @ 3.47GHz       | 1        | 1.27%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1        | 1.27%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1        | 1.27%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1        | 1.27%   |
| Intel Core i5-4690 CPU @ 3.50GHz        | 1        | 1.27%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1        | 1.27%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1        | 1.27%   |
| Intel Core i5-3570K CPU @ 3.40GHz       | 1        | 1.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1        | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Intel Xeon           | 19       | 24.05%  |
| Intel Core i7        | 16       | 20.25%  |
| Intel Core i5        | 14       | 17.72%  |
| Intel Core i3        | 7        | 8.86%   |
| AMD Ryzen 9          | 5        | 6.33%   |
| Other                | 4        | 5.06%   |
| AMD Ryzen 5          | 3        | 3.8%    |
| Intel Pentium Gold   | 2        | 2.53%   |
| AMD Ryzen 7          | 2        | 2.53%   |
| Intel Pentium Silver | 1        | 1.27%   |
| Intel Core i9        | 1        | 1.27%   |
| Intel Core 2 Duo     | 1        | 1.27%   |
| Intel Celeron        | 1        | 1.27%   |
| AMD Ryzen 3          | 1        | 1.27%   |
| AMD FX               | 1        | 1.27%   |
| AMD A4               | 1        | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 28       | 35.44%  |
| 6      | 12       | 15.19%  |
| 2      | 12       | 15.19%  |
| 8      | 10       | 12.66%  |
| 12     | 9        | 11.39%  |
| 16     | 4        | 5.06%   |
| 36     | 1        | 1.27%   |
| 24     | 1        | 1.27%   |
| 20     | 1        | 1.27%   |
| 14     | 1        | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 87.34%  |
| 2      | 10       | 12.66%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 71.25%  |
| 1      | 23       | 28.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 97.47%  |
| Unknown        | 2        | 2.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 12       | 15.19%  |
| 0x906ea    | 8        | 10.13%  |
| 0x306f2    | 8        | 10.13%  |
| 0x306a9    | 7        | 8.86%   |
| 0xa0671    | 3        | 3.8%    |
| 0x906ed    | 3        | 3.8%    |
| 0x906e9    | 3        | 3.8%    |
| 0x506e3    | 3        | 3.8%    |
| 0x406f1    | 3        | 3.8%    |
| 0x206d7    | 3        | 3.8%    |
| 0x08701021 | 3        | 3.8%    |
| 0x906c0    | 2        | 2.53%   |
| 0x08701013 | 2        | 2.53%   |
| Unknown    | 2        | 2.53%   |
| 0xb0671    | 1        | 1.27%   |
| 0xa0655    | 1        | 1.27%   |
| 0x906eb    | 1        | 1.27%   |
| 0x806e9    | 1        | 1.27%   |
| 0x306e4    | 1        | 1.27%   |
| 0x206c2    | 1        | 1.27%   |
| 0x206a7    | 1        | 1.27%   |
| 0x1067a    | 1        | 1.27%   |
| 0x10676    | 1        | 1.27%   |
| 0x0a601203 | 1        | 1.27%   |
| 0x0a50000c | 1        | 1.27%   |
| 0x08108102 | 1        | 1.27%   |
| 0x0810100b | 1        | 1.27%   |
| 0x08001138 | 1        | 1.27%   |
| 0x08001137 | 1        | 1.27%   |
| 0x06006705 | 1        | 1.27%   |
| 0x06000852 | 1        | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 26.58%  |
| KabyLake         | 16       | 20.25%  |
| IvyBridge        | 9        | 11.39%  |
| Zen 2            | 5        | 6.33%   |
| SandyBridge      | 4        | 5.06%   |
| Zen              | 3        | 3.8%    |
| Skylake          | 3        | 3.8%    |
| Icelake          | 3        | 3.8%    |
| Broadwell        | 3        | 3.8%    |
| Tremont          | 2        | 2.53%   |
| Penryn           | 2        | 2.53%   |
| Zen+             | 1        | 1.27%   |
| Zen 3            | 1        | 1.27%   |
| Westmere         | 1        | 1.27%   |
| Piledriver       | 1        | 1.27%   |
| Excavator        | 1        | 1.27%   |
| CometLake        | 1        | 1.27%   |
| Alderlake Hybrid | 1        | 1.27%   |
| Unknown          | 1        | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 42       | 46.15%  |
| Intel                      | 30       | 32.97%  |
| AMD                        | 13       | 14.29%  |
| Matrox Electronics Systems | 6        | 6.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Matrox Electronics Systems G200eR2                                          | 6        | 6.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 6.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 3.16%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 3.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.16%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.16%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 2.11%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.11%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.11%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 2.11%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 2.11%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 2.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.11%   |
| Intel HD Graphics 630                                                       | 2        | 2.11%   |
| Nvidia TU117GL [T400 4GB]                                                   | 1        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.05%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.05%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 1.05%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.05%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.05%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.05%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.05%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.05%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.05%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.05%   |
| Nvidia GF119 [NVS 315]                                                      | 1        | 1.05%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.05%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.05%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 36       | 44.44%  |
| 1 x Intel      | 20       | 24.69%  |
| 1 x AMD        | 9        | 11.11%  |
| 1 x Matrox     | 6        | 7.41%   |
| Intel + Nvidia | 4        | 4.94%   |
| 2 x Nvidia     | 2        | 2.47%   |
| 2 x AMD        | 2        | 2.47%   |
| Intel + AMD    | 2        | 2.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 67.5%   |
| Proprietary | 19       | 23.75%  |
| Unknown     | 7        | 8.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 41.67%  |
| 1.01-2.0   | 13       | 15.48%  |
| 7.01-8.0   | 11       | 13.1%   |
| 0.51-1.0   | 7        | 8.33%   |
| 3.01-4.0   | 5        | 5.95%   |
| 0.01-0.5   | 5        | 5.95%   |
| 5.01-6.0   | 3        | 3.57%   |
| 2.01-3.0   | 3        | 3.57%   |
| 8.01-16.0  | 2        | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 17       | 20.73%  |
| Samsung Electronics  | 13       | 15.85%  |
| Goldstar             | 10       | 12.2%   |
| Lenovo               | 6        | 7.32%   |
| Hewlett-Packard      | 6        | 7.32%   |
| BenQ                 | 4        | 4.88%   |
| Ancor Communications | 3        | 3.66%   |
| Acer                 | 3        | 3.66%   |
| ViewSonic            | 2        | 2.44%   |
| Philips              | 2        | 2.44%   |
| Lenovo Group Limited | 2        | 2.44%   |
| Iiyama               | 2        | 2.44%   |
| Gigabyte Technology  | 2        | 2.44%   |
| Eizo                 | 2        | 2.44%   |
| STD                  | 1        | 1.22%   |
| Sony                 | 1        | 1.22%   |
| OUT                  | 1        | 1.22%   |
| Microstep            | 1        | 1.22%   |
| LG Electronics       | 1        | 1.22%   |
| Insignia             | 1        | 1.22%   |
| Haier                | 1        | 1.22%   |
| Unknown              | 1        | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Dell LCD Monitor DEL0001 1280x1024                                     | 6        | 6.45%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                 | 2        | 2.15%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch               | 2        | 2.15%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch               | 2        | 2.15%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                   | 2        | 2.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 2.15%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 1.08%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch          | 1        | 1.08%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1        | 1.08%   |
| Sony TV SNYD703 1360x768                                               | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                       | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch    | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 1.08%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 1.08%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch      | 1        | 1.08%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch  | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor S22B150                                | 1        | 1.08%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                      | 1        | 1.08%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch      | 1        | 1.08%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch      | 1        | 1.08%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 1.08%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 1.08%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.08%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 1.08%   |
| Microstep LCD Monitor MSI AG32CV 1920x1080                             | 1        | 1.08%   |
| LG Electronics LCD Monitor W2486 1920x1080                             | 1        | 1.08%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                   | 1        | 1.08%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch               | 1        | 1.08%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                   | 1        | 1.08%   |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                 | 1        | 1.08%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                 | 1        | 1.08%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                 | 1        | 1.08%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10                           | 1        | 1.08%   |
| Insignia NS-40D420NA16 BBY4000 1920x1080 1210x680mm 54.6-inch          | 1        | 1.08%   |
| Hewlett-Packard Z38c HPN3411 3840x1600 880x367mm 37.5-inch             | 1        | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 45.12%  |
| 1280x1024 (SXGA)   | 7        | 8.54%   |
| 3840x2160 (4K)     | 6        | 7.32%   |
| 2560x1440 (QHD)    | 6        | 7.32%   |
| 1600x900 (HD+)     | 4        | 4.88%   |
| 3840x1080          | 3        | 3.66%   |
| 3440x1440          | 3        | 3.66%   |
| 2560x1080          | 3        | 3.66%   |
| Unknown            | 3        | 3.66%   |
| 1680x1050 (WSXGA+) | 2        | 2.44%   |
| 9600x2160          | 1        | 1.22%   |
| 7680x2160          | 1        | 1.22%   |
| 3840x1600          | 1        | 1.22%   |
| 3840x1200          | 1        | 1.22%   |
| 1920x1200 (WUXGA)  | 1        | 1.22%   |
| 1440x900 (WXGA+)   | 1        | 1.22%   |
| 1280x768           | 1        | 1.22%   |
| 1280x720 (HD)      | 1        | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 20.24%  |
| 21      | 11       | 13.1%   |
| 27      | 10       | 11.9%   |
| 23      | 10       | 11.9%   |
| 24      | 8        | 9.52%   |
| 31      | 5        | 5.95%   |
| 20      | 4        | 4.76%   |
| 54      | 3        | 3.57%   |
| 34      | 3        | 3.57%   |
| 47      | 2        | 2.38%   |
| 72      | 1        | 1.19%   |
| 64      | 1        | 1.19%   |
| 52      | 1        | 1.19%   |
| 40      | 1        | 1.19%   |
| 39      | 1        | 1.19%   |
| 37      | 1        | 1.19%   |
| 28      | 1        | 1.19%   |
| 25      | 1        | 1.19%   |
| 19      | 1        | 1.19%   |
| 18      | 1        | 1.19%   |
| 16      | 1        | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 26       | 32.1%   |
| Unknown     | 17       | 20.99%  |
| 401-500     | 15       | 18.52%  |
| 601-700     | 7        | 8.64%   |
| 1001-1500   | 7        | 8.64%   |
| 801-900     | 3        | 3.7%    |
| 701-800     | 3        | 3.7%    |
| 351-400     | 1        | 1.23%   |
| 301-350     | 1        | 1.23%   |
| 1501-2000   | 1        | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 47       | 64.38%  |
| Unknown | 9        | 12.33%  |
| 5/4     | 7        | 9.59%   |
| 21/9    | 5        | 6.85%   |
| 16/10   | 4        | 5.48%   |
| 4/3     | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 29.27%  |
| Unknown        | 17       | 20.73%  |
| 301-350        | 10       | 12.2%   |
| 351-500        | 8        | 9.76%   |
| 151-200        | 7        | 8.54%   |
| More than 1000 | 6        | 7.32%   |
| 501-1000       | 5        | 6.1%    |
| 251-300        | 4        | 4.88%   |
| 131-140        | 1        | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 47.5%   |
| Unknown | 17       | 21.25%  |
| 101-120 | 15       | 18.75%  |
| 1-50    | 7        | 8.75%   |
| 161-240 | 2        | 2.5%    |
| 121-160 | 1        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 73.49%  |
| 2     | 9        | 10.84%  |
| 0     | 8        | 9.64%   |
| 3     | 5        | 6.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 50       | 42.74%  |
| Realtek Semiconductor    | 35       | 29.91%  |
| Broadcom                 | 9        | 7.69%   |
| Qualcomm Atheros         | 7        | 5.98%   |
| Ralink Technology        | 2        | 1.71%   |
| Dell                     | 2        | 1.71%   |
| ASIX Electronics         | 2        | 1.71%   |
| Ralink                   | 1        | 0.85%   |
| Microchip Technology     | 1        | 0.85%   |
| Micro Star International | 1        | 0.85%   |
| MediaTek                 | 1        | 0.85%   |
| Huawei Technologies      | 1        | 0.85%   |
| D-Link                   | 1        | 0.85%   |
| Broadcom Limited         | 1        | 0.85%   |
| ASUSTek Computer         | 1        | 0.85%   |
| Arduino SA               | 1        | 0.85%   |
| Aquantia                 | 1        | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 16.77%  |
| Intel I211 Gigabit Network Connection                             | 7        | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.87%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 3.87%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.23%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 2.58%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.58%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 4        | 2.58%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 4        | 2.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.94%   |
| Intel I350 Gigabit Network Connection                             | 3        | 1.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.94%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.94%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 1.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.29%   |
| Intel Wireless-AC 9260                                            | 2        | 1.29%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.29%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.29%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.29%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 1.29%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 2        | 1.29%   |
| Dell iDRAC Virtual NIC                                            | 2        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.65%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.65%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.65%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 0.65%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.65%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 15       | 38.46%  |
| Realtek Semiconductor    | 7        | 17.95%  |
| Qualcomm Atheros         | 6        | 15.38%  |
| Broadcom                 | 4        | 10.26%  |
| Ralink Technology        | 2        | 5.13%   |
| Ralink                   | 1        | 2.56%   |
| Micro Star International | 1        | 2.56%   |
| MediaTek                 | 1        | 2.56%   |
| D-Link                   | 1        | 2.56%   |
| ASUSTek Computer         | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 3        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 3        | 7.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 7.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 5.13%   |
| Intel Wireless-AC 9260                                                     | 2        | 5.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 2.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 2.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 2.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 2.56%   |
| Realtek 802.11n WLAN Adapter                                               | 1        | 2.56%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 2.56%   |
| Ralink RT5372 Wireless Adapter                                             | 1        | 2.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 2.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 2.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 2.56%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 2.56%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1        | 2.56%   |
| Intel Wireless 7260                                                        | 1        | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 2.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1        | 2.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1        | 2.56%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 2.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 2.56%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                        | 1        | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 48       | 51.06%  |
| Realtek Semiconductor | 33       | 35.11%  |
| Broadcom              | 5        | 5.32%   |
| Qualcomm Atheros      | 2        | 2.13%   |
| Dell                  | 2        | 2.13%   |
| ASIX Electronics      | 2        | 2.13%   |
| Broadcom Limited      | 1        | 1.06%   |
| Aquantia              | 1        | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 26       | 23.01%  |
| Intel I211 Gigabit Network Connection                                         | 7        | 6.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 5.31%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 5.31%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 4.42%   |
| Intel Ethernet Controller I225-V                                              | 4        | 3.54%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4        | 3.54%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 3.54%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 4        | 3.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4        | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 2.65%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 2.65%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 1.77%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 1.77%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.77%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.77%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 1.77%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                         | 2        | 1.77%   |
| Dell iDRAC Virtual NIC                                                        | 2        | 1.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.88%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.88%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.88%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.88%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.88%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 0.88%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 0.88%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 65.83%  |
| WiFi     | 38       | 31.67%  |
| Modem    | 3        | 2.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 82.72%  |
| WiFi     | 14       | 17.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 41.25%  |
| 2     | 24       | 30%     |
| 3     | 12       | 15%     |
| 6     | 5        | 6.25%   |
| 4     | 5        | 6.25%   |
| 5     | 1        | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 68       | 85%     |
| Yes  | 12       | 15%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 40.63%  |
| Cambridge Silicon Radio         | 8        | 25%     |
| ASUSTek Computer                | 3        | 9.38%   |
| Realtek Semiconductor           | 2        | 6.25%   |
| Qualcomm Atheros Communications | 2        | 6.25%   |
| Micro Star International        | 1        | 3.13%   |
| Integrated System Solution      | 1        | 3.13%   |
| IMC Networks                    | 1        | 3.13%   |
| Broadcom                        | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 25%     |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 9.38%   |
| Realtek Bluetooth Radio                               | 2        | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 6.25%   |
| Intel AX201 Bluetooth                                 | 2        | 6.25%   |
| Intel AX200 Bluetooth                                 | 2        | 6.25%   |
| ASUS BCM20702A0                                       | 2        | 6.25%   |
| Micro Star International Bluetooth Device             | 1        | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 3.13%   |
| Intel Bluetooth wireless interface                    | 1        | 3.13%   |
| Intel AX210 Bluetooth                                 | 1        | 3.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.13%   |
| IMC Networks BCM20702A0                               | 1        | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 3.13%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 56       | 41.48%  |
| Nvidia                                       | 39       | 28.89%  |
| AMD                                          | 18       | 13.33%  |
| Lenovo                                       | 3        | 2.22%   |
| Creative Labs                                | 3        | 2.22%   |
| Texas Instruments                            | 2        | 1.48%   |
| Plantronics                                  | 2        | 1.48%   |
| Logitech                                     | 2        | 1.48%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.74%   |
| Tenx Technology                              | 1        | 0.74%   |
| SteelSeries ApS                              | 1        | 0.74%   |
| Sennheiser Communications                    | 1        | 0.74%   |
| RODE Microphones                             | 1        | 0.74%   |
| JMTek                                        | 1        | 0.74%   |
| Giga-Byte Technology                         | 1        | 0.74%   |
| Dynex                                        | 1        | 0.74%   |
| Creative Technology                          | 1        | 0.74%   |
| ASUSTek Computer                             | 1        | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 6.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 5.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.97%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 3.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 3.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 3.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 3.31%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 2.65%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.99%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 1.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 1.99%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.99%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.32%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.32%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.32%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.66%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.66%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.66%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                  | 1        | 0.66%   |
| RODE Microphones RODE NT-USB                                               | 1        | 0.66%   |
| Plantronics Poly BT700                                                     | 1        | 0.66%   |
| Plantronics BT600                                                          | 1        | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 17.78%  |
| SK hynix            | 7        | 15.56%  |
| Micron Technology   | 7        | 15.56%  |
| Crucial             | 7        | 15.56%  |
| Kingston            | 5        | 11.11%  |
| Corsair             | 4        | 8.89%   |
| Unknown             | 2        | 4.44%   |
| Unknown (0x0205)    | 1        | 2.22%   |
| Transcend           | 1        | 2.22%   |
| Patriot             | 1        | 2.22%   |
| GOODRAM             | 1        | 2.22%   |
| G.Skill             | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s | 2        | 4%      |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s    | 2        | 4%      |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 2        | 4%      |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s     | 2        | 4%      |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s   | 2        | 4%      |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 2%      |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 1        | 2%      |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s       | 1        | 2%      |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s         | 1        | 2%      |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s    | 1        | 2%      |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s  | 1        | 2%      |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s  | 1        | 2%      |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s     | 1        | 2%      |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 2%      |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 2%      |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 2%      |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s     | 1        | 2%      |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s      | 1        | 2%      |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s      | 1        | 2%      |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 2%      |
| Samsung RAM M3 78T2863EHS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 2%      |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s         | 1        | 2%      |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                 | 1        | 2%      |
| Micron RAM 9ASF51272PZ-2G3B1 4GB RIMM DDR4 2400MT/s      | 1        | 2%      |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s     | 1        | 2%      |
| Micron RAM 16JTF1G64AZ-1G6E1 8192MB DIMM DDR3 1600MT/s   | 1        | 2%      |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s      | 1        | 2%      |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 2%      |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s     | 1        | 2%      |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2%      |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3266MT/s    | 1        | 2%      |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s  | 1        | 2%      |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s     | 1        | 2%      |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s     | 1        | 2%      |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s    | 1        | 2%      |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s     | 1        | 2%      |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 2%      |
| Crucial RAM BLT4G3D1608ET3LX0. 4GB DIMM 1600MT/s         | 1        | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 22       | 55%     |
| DDR3   | 10       | 25%     |
| SDRAM  | 3        | 7.5%    |
| DRAM   | 2        | 5%      |
| LPDDR4 | 1        | 2.5%    |
| DDR5   | 1        | 2.5%    |
| DDR2   | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 35       | 89.74%  |
| SODIMM       | 2        | 5.13%   |
| Row Of Chips | 1        | 2.56%   |
| RIMM         | 1        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 13       | 30.23%  |
| 8192  | 13       | 30.23%  |
| 4096  | 10       | 23.26%  |
| 32768 | 4        | 9.3%    |
| 2048  | 2        | 4.65%   |
| 1024  | 1        | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 9        | 20.45%  |
| 1600  | 8        | 18.18%  |
| 2133  | 6        | 13.64%  |
| 3600  | 4        | 9.09%   |
| 1333  | 3        | 6.82%   |
| 3266  | 2        | 4.55%   |
| 3200  | 2        | 4.55%   |
| 2933  | 2        | 4.55%   |
| 2667  | 2        | 4.55%   |
| 6400  | 1        | 2.27%   |
| 2666  | 1        | 2.27%   |
| 2472  | 1        | 2.27%   |
| 2048  | 1        | 2.27%   |
| 1867  | 1        | 2.27%   |
| 800   | 1        | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 33.33%  |
| Canon              | 2        | 33.33%  |
| Hewlett-Packard    | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series       | 1        | 16.67%  |
| Seiko Epson WF-3520 Series       | 1        | 16.67%  |
| HP LaserJet Professional P 1102w | 1        | 16.67%  |
| Canon E560 series                | 1        | 16.67%  |
| Canon CanoScan LiDE 300          | 1        | 16.67%  |
| Brother DCP-1610W                | 1        | 16.67%  |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 3        | 20%     |
| Hopewin Electronic Material | 3        | 20%     |
| Generalplus Technology      | 2        | 13.33%  |
| Samsung Electronics         | 1        | 6.67%   |
| Ruision                     | 1        | 6.67%   |
| Microsoft                   | 1        | 6.67%   |
| Microdia                    | 1        | 6.67%   |
| Jieli Technology            | 1        | 6.67%   |
| IMC Networks                | 1        | 6.67%   |
| ARC International           | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Hopewin Electronic Material FULL HD 1080P Webcam | 3        | 20%     |
| Generalplus GENERAL WEBCAM                       | 2        | 13.33%  |
| Samsung Galaxy A5 (MTP)                          | 1        | 6.67%   |
| Ruision UVC Camera                               | 1        | 6.67%   |
| Microsoft LifeCam HD-3000                        | 1        | 6.67%   |
| Microdia USB 2.0 Camera                          | 1        | 6.67%   |
| Logitech Webcam C270                             | 1        | 6.67%   |
| Logitech Webcam C250                             | 1        | 6.67%   |
| Logitech HD Webcam C910                          | 1        | 6.67%   |
| Jieli USB PHY 2.0                                | 1        | 6.67%   |
| IMC Networks XHC Camera                          | 1        | 6.67%   |
| ARC International Camera                         | 1        | 6.67%   |

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
| 0     | 58       | 72.5%   |
| 2     | 11       | 13.75%  |
| 1     | 9        | 11.25%  |
| 5     | 1        | 1.25%   |
| 3     | 1        | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 13       | 37.14%  |
| Graphics card            | 7        | 20%     |
| Communication controller | 7        | 20%     |
| Net/wireless             | 5        | 14.29%  |
| Storage/ide              | 1        | 2.86%   |
| Sound                    | 1        | 2.86%   |
| Bluetooth                | 1        | 2.86%   |

