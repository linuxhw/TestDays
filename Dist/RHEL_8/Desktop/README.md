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

Total: 104

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Gigabyte      | Z97N-WIFI                   | [9d1a04cc28](https://linux-hardware.org/?probe=9d1a04cc28) | Dec 15, 2021 |
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
| HP            | 1905                        | [872e4ba303](https://linux-hardware.org/?probe=872e4ba303) | Nov 13, 2020 |
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
| ASUSTek       | P8Z77-V PRO                 | [1abce91d71](https://linux-hardware.org/?probe=1abce91d71) | May 08, 2020 |
| ASRockRack    | EP2C612 WS                  | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Gigabyte      | B75-D3V                     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | [1dd5200664](https://linux-hardware.org/?probe=1dd5200664) | Apr 07, 2020 |
| ASRockRack    | EP2C612 WS                  | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [b49a701ac3](https://linux-hardware.org/?probe=b49a701ac3) | Apr 01, 2020 |
| Alienware     | 0VDT73 A00                  | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [b5d3a3694d](https://linux-hardware.org/?probe=b5d3a3694d) | Feb 27, 2020 |
| Lenovo        | Board                       | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | Board                       | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| MSI           | B350M MORTAR                | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [5c93a8b972](https://linux-hardware.org/?probe=5c93a8b972) | Feb 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [7b9606b44d](https://linux-hardware.org/?probe=7b9606b44d) | Feb 03, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [f24757810e](https://linux-hardware.org/?probe=f24757810e) | Jan 28, 2020 |
| Dell          | 0XR1GT A00                  | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [bdeba33a9c](https://linux-hardware.org/?probe=bdeba33a9c) | Jan 19, 2020 |
| ASUSTek       | PRIME X470-PRO              | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a92733c45d](https://linux-hardware.org/?probe=a92733c45d) | Jan 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [4edc6c52b8](https://linux-hardware.org/?probe=4edc6c52b8) | Jan 17, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [372bb9dced](https://linux-hardware.org/?probe=372bb9dced) | Jan 15, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [61f2cf2ae4](https://linux-hardware.org/?probe=61f2cf2ae4) | Jan 12, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [458ececa20](https://linux-hardware.org/?probe=458ececa20) | Jan 12, 2020 |
| MSI           | B350M MORTAR                | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [2979b0995f](https://linux-hardware.org/?probe=2979b0995f) | Dec 21, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [2ce515411e](https://linux-hardware.org/?probe=2ce515411e) | Dec 13, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [2862a08f39](https://linux-hardware.org/?probe=2862a08f39) | Nov 29, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6d1db662fe](https://linux-hardware.org/?probe=6d1db662fe) | Nov 17, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [997d2ae2bf](https://linux-hardware.org/?probe=997d2ae2bf) | Nov 16, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Supermicro    | X7DWN+                      | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | [c0df153404](https://linux-hardware.org/?probe=c0df153404) | Oct 25, 2019 |
| Supermicro    | X7DWN+                      | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-305.el8.x86_64        | 7        | 11.11%  |
| 4.18.0-147.3.1.el8_1.x86_64  | 6        | 9.52%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4        | 6.35%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 4        | 6.35%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 3        | 4.76%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 4.76%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 3        | 4.76%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 3        | 4.76%   |
| 4.18.0-193.el8.x86_64        | 3        | 4.76%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3        | 4.76%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2        | 3.17%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 3.17%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2        | 3.17%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 2        | 3.17%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 2        | 3.17%   |
| 4.18.0-147.el8.x86_64        | 2        | 3.17%   |
| 5.10.6-1.el8.elrepo.x86_64   | 1        | 1.59%   |
| 4.19.150                     | 1        | 1.59%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 1        | 1.59%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 1        | 1.59%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1        | 1.59%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1        | 1.59%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 1        | 1.59%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1        | 1.59%   |
| 4.18.0-240.8.1.el8_3.x86_64  | 1        | 1.59%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 1        | 1.59%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 1        | 1.59%   |
| 4.18.0-147.0.3.el8_1.x86_64  | 1        | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.18.0   | 47       | 95.92%  |
| 5.10.6   | 1        | 2.04%   |
| 4.19.150 | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 47       | 95.92%  |
| 5.10    | 1        | 2.04%   |
| 4.19    | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 42       | 82.35%  |
| GNOME Classic | 3        | 5.88%   |
| KDE5          | 2        | 3.92%   |
| KDE           | 2        | 3.92%   |
| Unknown       | 2        | 3.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 30       | 57.69%  |
| Wayland | 21       | 40.38%  |
| Unknown | 1        | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 74.51%  |
| GDM     | 13       | 25.49%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 31       | 62%     |
| ru_RU   | 2        | 4%      |
| pl_PL   | 2        | 4%      |
| es_AR   | 2        | 4%      |
| en_IN   | 2        | 4%      |
| en_GB   | 2        | 4%      |
| de_DE   | 2        | 4%      |
| Unknown | 2        | 4%      |
| ko_KR   | 1        | 2%      |
| es_MX   | 1        | 2%      |
| es_ES   | 1        | 2%      |
| en_NZ   | 1        | 2%      |
| cs_CZ   | 1        | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 34       | 68%     |
| BIOS | 16       | 32%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 46       | 93.88%  |
| Ext4 | 3        | 6.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 68.63%  |
| GPT     | 12       | 23.53%  |
| MBR     | 4        | 7.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 95.92%  |
| Yes       | 2        | 4.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 88%     |
| Yes       | 6        | 12%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 24.49%  |
| Hewlett-Packard     | 8        | 16.33%  |
| Gigabyte Technology | 7        | 14.29%  |
| ASRock              | 5        | 10.2%   |
| MSI                 | 4        | 8.16%   |
| Lenovo              | 4        | 8.16%   |
| Dell                | 4        | 8.16%   |
| Supermicro          | 1        | 2.04%   |
| Intel               | 1        | 2.04%   |
| CX / Air Computers. | 1        | 2.04%   |
| Alienware           | 1        | 2.04%   |
| Unknown             | 1        | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 8.16%   |
| Supermicro X7DW3                    | 1        | 2.04%   |
| MSI MS-7B51                         | 1        | 2.04%   |
| MSI MS-7B33                         | 1        | 2.04%   |
| MSI MS-7A37                         | 1        | 2.04%   |
| MSI MS-7752                         | 1        | 2.04%   |
| Lenovo ThinkCentre M92p 3238AZ8     | 1        | 2.04%   |
| Lenovo ThinkCentre M920t 10SFS03200 | 1        | 2.04%   |
| Lenovo ThinkCentre M91p 0266RZ1     | 1        | 2.04%   |
| Lenovo 10SFS03200                   | 1        | 2.04%   |
| Intel DX79SR AAG57199-200           | 1        | 2.04%   |
| HP Z840 Workstation                 | 1        | 2.04%   |
| HP Z620 Workstation                 | 1        | 2.04%   |
| HP Z440 Workstation                 | 1        | 2.04%   |
| HP Z230 Tower Workstation           | 1        | 2.04%   |
| HP Z230 SFF Workstation             | 1        | 2.04%   |
| HP EliteDesk 800 G2 SFF             | 1        | 2.04%   |
| HP 290 G1 SFF Business PC           | 1        | 2.04%   |
| HP 260-P020il                       | 1        | 2.04%   |
| Gigabyte Z97N-WIFI                  | 1        | 2.04%   |
| Gigabyte Z490 GAMING X              | 1        | 2.04%   |
| Gigabyte Z390 AORUS ULTRA           | 1        | 2.04%   |
| Gigabyte B85M-D3V-A                 | 1        | 2.04%   |
| Gigabyte B75-D3V                    | 1        | 2.04%   |
| Gigabyte B150-HD3                   | 1        | 2.04%   |
| Gigabyte 970A-D3                    | 1        | 2.04%   |
| Dell Vostro 270                     | 1        | 2.04%   |
| Dell Precision Tower 3620           | 1        | 2.04%   |
| Dell Precision T7600                | 1        | 2.04%   |
| Dell Precision 3630 Tower           | 1        | 2.04%   |
| CX / Air Computers. H87-M1          | 1        | 2.04%   |
| ASUS Z10PE-D16 WS                   | 1        | 2.04%   |
| ASUS ROG STRIX B350-F GAMING        | 1        | 2.04%   |
| ASUS ROG Maximus X HERO             | 1        | 2.04%   |
| ASUS Pro WS X570-ACE                | 1        | 2.04%   |
| ASUS PRIME X470-PRO                 | 1        | 2.04%   |
| ASUS PRIME B360M-D                  | 1        | 2.04%   |
| ASUS PRIME B350M-A                  | 1        | 2.04%   |
| ASUS P8Z77-V PRO                    | 1        | 2.04%   |
| ASRock X99E-ITX/ac                  | 1        | 2.04%   |
| ASRock X570 Steel Legend            | 1        | 2.04%   |
| ASRock H91M-PLUS                    | 1        | 2.04%   |
| ASRock H270 Pro4                    | 1        | 2.04%   |
| ASRock A300M-STX                    | 1        | 2.04%   |
| Alienware Aurora R7                 | 1        | 2.04%   |
| Unknown                             | 1        | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All                   | 4        | 8.16%   |
| Lenovo ThinkCentre         | 3        | 6.12%   |
| Dell Precision             | 3        | 6.12%   |
| ASUS PRIME                 | 3        | 6.12%   |
| HP Z230                    | 2        | 4.08%   |
| ASUS ROG                   | 2        | 4.08%   |
| Supermicro X7DW3           | 1        | 2.04%   |
| MSI MS-7B51                | 1        | 2.04%   |
| MSI MS-7B33                | 1        | 2.04%   |
| MSI MS-7A37                | 1        | 2.04%   |
| MSI MS-7752                | 1        | 2.04%   |
| Lenovo 10SFS03200          | 1        | 2.04%   |
| Intel DX79SR               | 1        | 2.04%   |
| HP Z840                    | 1        | 2.04%   |
| HP Z620                    | 1        | 2.04%   |
| HP Z440                    | 1        | 2.04%   |
| HP EliteDesk               | 1        | 2.04%   |
| HP 290                     | 1        | 2.04%   |
| HP 260-P020il              | 1        | 2.04%   |
| Gigabyte Z97N-WIFI         | 1        | 2.04%   |
| Gigabyte Z490              | 1        | 2.04%   |
| Gigabyte Z390              | 1        | 2.04%   |
| Gigabyte B85M-D3V-A        | 1        | 2.04%   |
| Gigabyte B75-D3V           | 1        | 2.04%   |
| Gigabyte B150-HD3          | 1        | 2.04%   |
| Gigabyte 970A-D3           | 1        | 2.04%   |
| Dell Vostro                | 1        | 2.04%   |
| CX / Air Computers. H87-M1 | 1        | 2.04%   |
| ASUS Z10PE-D16             | 1        | 2.04%   |
| ASUS Pro                   | 1        | 2.04%   |
| ASUS P8Z77-V               | 1        | 2.04%   |
| ASRock X99E-ITX            | 1        | 2.04%   |
| ASRock X570                | 1        | 2.04%   |
| ASRock H91M-PLUS           | 1        | 2.04%   |
| ASRock H270                | 1        | 2.04%   |
| ASRock A300M-STX           | 1        | 2.04%   |
| Alienware Aurora           | 1        | 2.04%   |
| Unknown                    | 1        | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 20.41%  |
| 2012 | 8        | 16.33%  |
| 2017 | 7        | 14.29%  |
| 2019 | 5        | 10.2%   |
| 2015 | 5        | 10.2%   |
| 2013 | 5        | 10.2%   |
| 2020 | 3        | 6.12%   |
| 2016 | 3        | 6.12%   |
| 2021 | 1        | 2.04%   |
| 2014 | 1        | 2.04%   |
| 2009 | 1        | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 49       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 47       | 94%     |
| Enabled  | 3        | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 14       | 28%     |
| 4.01-8.0    | 8        | 16%     |
| 32.01-64.0  | 8        | 16%     |
| 16.01-24.0  | 8        | 16%     |
| 8.01-16.0   | 7        | 14%     |
| 24.01-32.0  | 5        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 19       | 33.33%  |
| 2.01-3.0  | 16       | 28.07%  |
| 8.01-16.0 | 11       | 19.3%   |
| 3.01-4.0  | 7        | 12.28%  |
| 1.01-2.0  | 4        | 7.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 38.89%  |
| 1      | 13       | 24.07%  |
| 3      | 9        | 16.67%  |
| 4      | 5        | 9.26%   |
| 5      | 3        | 5.56%   |
| 8      | 2        | 3.7%    |
| 6      | 1        | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 54%     |
| Yes       | 23       | 46%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 53.06%  |
| No        | 23       | 46.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 57.14%  |
| Yes       | 21       | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 8        | 16.33%  |
| Czechia      | 5        | 10.2%   |
| UK           | 3        | 6.12%   |
| Germany      | 3        | 6.12%   |
| Canada       | 3        | 6.12%   |
| Ukraine      | 2        | 4.08%   |
| South Korea  | 2        | 4.08%   |
| Russia       | 2        | 4.08%   |
| Poland       | 2        | 4.08%   |
| Italy        | 2        | 4.08%   |
| India        | 2        | 4.08%   |
| Argentina    | 2        | 4.08%   |
| Turkmenistan | 1        | 2.04%   |
| Switzerland  | 1        | 2.04%   |
| Sweden       | 1        | 2.04%   |
| Spain        | 1        | 2.04%   |
| New Zealand  | 1        | 2.04%   |
| Netherlands  | 1        | 2.04%   |
| Mexico       | 1        | 2.04%   |
| Lithuania    | 1        | 2.04%   |
| Indonesia    | 1        | 2.04%   |
| Egypt        | 1        | 2.04%   |
| China        | 1        | 2.04%   |
| Brazil       | 1        | 2.04%   |
| Belarus      | 1        | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Brno                  | 3        | 5.66%   |
| Kyiv                  | 2        | 3.77%   |
| Wiesbaden             | 1        | 1.89%   |
| Weybridge             | 1        | 1.89%   |
| Warsaw                | 1        | 1.89%   |
| Valmontone            | 1        | 1.89%   |
| Vaestra Froelunda     | 1        | 1.89%   |
| Toronto               | 1        | 1.89%   |
| Tauranga              | 1        | 1.89%   |
| Suwon                 | 1        | 1.89%   |
| Spokane               | 1        | 1.89%   |
| Seoul                 | 1        | 1.89%   |
| Saratov               | 1        | 1.89%   |
| San Jose              | 1        | 1.89%   |
| San Fernando          | 1        | 1.89%   |
| Salvador              | 1        | 1.89%   |
| Saltillo              | 1        | 1.89%   |
| Rosario               | 1        | 1.89%   |
| Prague                | 1        | 1.89%   |
| Poznan                | 1        | 1.89%   |
| Pernis                | 1        | 1.89%   |
| Paracuellos de Jarama | 1        | 1.89%   |
| Ostrow Mazowiecka     | 1        | 1.89%   |
| Musselburgh           | 1        | 1.89%   |
| Mragowo               | 1        | 1.89%   |
| Montreal              | 1        | 1.89%   |
| Mississauga           | 1        | 1.89%   |
| Minsk                 | 1        | 1.89%   |
| Milwaukee             | 1        | 1.89%   |
| Milan                 | 1        | 1.89%   |
| Lugano                | 1        | 1.89%   |
| Langfang              | 1        | 1.89%   |
| Huddersfield          | 1        | 1.89%   |
| Houghton              | 1        | 1.89%   |
| Gyami                 | 1        | 1.89%   |
| Dobrany               | 1        | 1.89%   |
| Dimitrovgrad          | 1        | 1.89%   |
| Des Moines            | 1        | 1.89%   |
| Coimbatore            | 1        | 1.89%   |
| Chicago               | 1        | 1.89%   |
| Cary                  | 1        | 1.89%   |
| Cairo                 | 1        | 1.89%   |
| Buenos Aires          | 1        | 1.89%   |
| Bonn                  | 1        | 1.89%   |
| Berlin                | 1        | 1.89%   |
| Bengaluru             | 1        | 1.89%   |
| Bandung               | 1        | 1.89%   |
| Å iauliai           | 1        | 1.89%   |
| Aurora                | 1        | 1.89%   |
| Albuquerque           | 1        | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 43     | 19.23%  |
| Seagate             | 15       | 27     | 14.42%  |
| Samsung Electronics | 13       | 28     | 12.5%   |
| Kingston            | 8        | 12     | 7.69%   |
| Toshiba             | 7        | 10     | 6.73%   |
| Sandisk             | 4        | 10     | 3.85%   |
| Crucial             | 4        | 8      | 3.85%   |
| Phison              | 3        | 7      | 2.88%   |
| Intel               | 3        | 5      | 2.88%   |
| Hitachi             | 3        | 3      | 2.88%   |
| A-DATA Technology   | 3        | 3      | 2.88%   |
| SK Hynix            | 2        | 3      | 1.92%   |
| PNY                 | 2        | 2      | 1.92%   |
| Corsair             | 2        | 5      | 1.92%   |
| XPG                 | 1        | 1      | 0.96%   |
| Western Digital     | 1        | 1      | 0.96%   |
| Unknown             | 1        | 1      | 0.96%   |
| T-FORCE             | 1        | 2      | 0.96%   |
| Silicon Motion      | 1        | 1      | 0.96%   |
| OCZ                 | 1        | 2      | 0.96%   |
| Micron Technology   | 1        | 1      | 0.96%   |
| KingFast            | 1        | 1      | 0.96%   |
| KINGBANK            | 1        | 1      | 0.96%   |
| HPT                 | 1        | 1      | 0.96%   |
| Hoodisk             | 1        | 1      | 0.96%   |
| HGST                | 1        | 1      | 0.96%   |
| Hewlett-Packard     | 1        | 1      | 0.96%   |
| Gigabyte Technology | 1        | 1      | 0.96%   |
| China               | 1        | 1      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB               | 3        | 2.38%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 2        | 1.59%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 1.59%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 2        | 1.59%   |
| Toshiba DT01ACA200 2TB                | 2        | 1.59%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 1.59%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 1.59%   |
| Samsung NVMe SSD Drive 512GB          | 2        | 1.59%   |
| Samsung NVMe SSD Drive 500GB          | 2        | 1.59%   |
| Kingston SUV500120G 120GB SSD         | 2        | 1.59%   |
| Corsair Force LE SSD 240GB            | 2        | 1.59%   |
| XPG NVMe SSD Drive 1024GB             | 1        | 0.79%   |
| Western Digital NVMe SSD Drive 960GB  | 1        | 0.79%   |
| WDC WDS250G2B0B-00YS70 250GB SSD      | 1        | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1        | 0.79%   |
| WDC WDS240G1G0A-00SS50 240GB SSD      | 1        | 0.79%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1        | 0.79%   |
| WDC WD7500BPKT-00PK4T0 752GB          | 1        | 0.79%   |
| WDC WD60 EFAX-68JH4N1 6TB             | 1        | 0.79%   |
| WDC WD60 EFAX-68JH4N0 6TB             | 1        | 0.79%   |
| WDC WD5003ABYZ-011FA0 500GB           | 1        | 0.79%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 0.79%   |
| WDC WD50 00LPVX-00V0TT0 500GB         | 1        | 0.79%   |
| WDC WD40PURZ-85TTDY0 4TB              | 1        | 0.79%   |
| WDC WD40EZRZ-19GXCB0 4TB              | 1        | 0.79%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 0.79%   |
| WDC WD4005FZBX-00K5WB0 4TB            | 1        | 0.79%   |
| WDC WD2500BEKT-75F3T0 250GB           | 1        | 0.79%   |
| WDC WD2500AAKX-083CA1 250GB           | 1        | 0.79%   |
| WDC WD20PURZ-85GU6Y0 2TB              | 1        | 0.79%   |
| WDC WD20EARS-22MVWB0 2TB              | 1        | 0.79%   |
| WDC WD2005FBYZ-01YCBB3 2TB            | 1        | 0.79%   |
| WDC WD2003FZEX-00SRLA0 2TB            | 1        | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1        | 0.79%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1        | 0.79%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 0.79%   |
| Unknown SD/MMC/MS PRO 16GB            | 1        | 0.79%   |
| Toshiba HDWT140 4TB                   | 1        | 0.79%   |
| Toshiba HDWQ140 4TB                   | 1        | 0.79%   |
| Toshiba HDWD120 2TB                   | 1        | 0.79%   |
| Toshiba DT01ACA300 3TB                | 1        | 0.79%   |
| Toshiba DT01ACA100 1TB                | 1        | 0.79%   |
| T-FORCE 1TB                           | 1        | 0.79%   |
| SK Hynix PC601 NVMe 512GB             | 1        | 0.79%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB SSD | 1        | 0.79%   |
| Silicon Motion NVMe SSD Drive 256GB   | 1        | 0.79%   |
| Seagate ST6000VN0033-2EE110 6TB       | 1        | 0.79%   |
| Seagate ST500LX025-1U717D 500GB       | 1        | 0.79%   |
| Seagate ST4000LM024-2AN17V 4TB        | 1        | 0.79%   |
| Seagate ST3250310AS 250GB             | 1        | 0.79%   |
| Seagate ST31000524AS 1TB              | 1        | 0.79%   |
| Seagate ST2000DM001-9YN164 2TB        | 1        | 0.79%   |
| Seagate ST1000VN002-2EY102 1TB        | 1        | 0.79%   |
| Seagate ST1000LX015-1U7172 1TB        | 1        | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB        | 1        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 0.79%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 39     | 40%     |
| Seagate             | 15       | 27     | 33.33%  |
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
| Samsung Electronics | 9        | 15     | 21.95%  |
| Kingston            | 8        | 12     | 19.51%  |
| Crucial             | 4        | 8      | 9.76%   |
| WDC                 | 3        | 4      | 7.32%   |
| A-DATA Technology   | 3        | 3      | 7.32%   |
| SanDisk             | 2        | 7      | 4.88%   |
| PNY                 | 2        | 2      | 4.88%   |
| Intel               | 2        | 3      | 4.88%   |
| Corsair             | 2        | 5      | 4.88%   |
| SK Hynix            | 1        | 2      | 2.44%   |
| OCZ                 | 1        | 2      | 2.44%   |
| Micron Technology   | 1        | 1      | 2.44%   |
| KINGBANK            | 1        | 1      | 2.44%   |
| Hoodisk             | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 36       | 81     | 40.91%  |
| SSD     | 35       | 67     | 39.77%  |
| NVMe    | 14       | 31     | 15.91%  |
| Unknown | 3        | 4      | 3.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 46       | 141    | 70.77%  |
| NVMe | 14       | 31     | 21.54%  |
| SAS  | 5        | 11     | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 73     | 41.25%  |
| 0.51-1.0   | 25       | 42     | 31.25%  |
| 1.01-2.0   | 13       | 16     | 16.25%  |
| 3.01-4.0   | 6        | 11     | 7.5%    |
| 4.01-10.0  | 2        | 5      | 2.5%    |
| 2.01-3.0   | 1        | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 21.82%  |
| 501-1000       | 11       | 20%     |
| More than 3000 | 10       | 18.18%  |
| 251-500        | 8        | 14.55%  |
| 1001-2000      | 8        | 14.55%  |
| 2001-3000      | 4        | 7.27%   |
| 51-100         | 2        | 3.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 14       | 23.73%  |
| 101-250        | 10       | 16.95%  |
| 1-20           | 9        | 15.25%  |
| 51-100         | 8        | 13.56%  |
| 1001-2000      | 5        | 8.47%   |
| 251-500        | 4        | 6.78%   |
| 501-1000       | 4        | 6.78%   |
| More than 3000 | 3        | 5.08%   |
| 2001-3000      | 2        | 3.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 33.33%  |
| Hitachi HDS722020ALA330 2TB           | 1        | 1      | 33.33%  |
| A-DATA Technology SU800NS38 256GB SSD | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 1        | 1      | 33.33%  |
| Hitachi           | 1        | 1      | 33.33%  |
| A-DATA Technology | 1        | 1      | 33.33%  |

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
| HDD  | 2        | 2      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Detected | 34       | 142    | 62.96%  |
| Works    | 17       | 38     | 31.48%  |
| Malfunc  | 3        | 3      | 5.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 40       | 52.63%  |
| AMD                          | 8        | 10.53%  |
| Samsung Electronics          | 7        | 9.21%   |
| Phison Electronics           | 3        | 3.95%   |
| Marvell Technology Group     | 3        | 3.95%   |
| ASMedia Technology           | 3        | 3.95%   |
| Toshiba America Info Systems | 2        | 2.63%   |
| LSI Logic / Symbios Logic    | 2        | 2.63%   |
| Broadcom / LSI               | 2        | 2.63%   |
| Western Digital              | 1        | 1.32%   |
| SK Hynix                     | 1        | 1.32%   |
| Silicon Motion               | 1        | 1.32%   |
| Sandisk                      | 1        | 1.32%   |
| HighPoint Technologies       | 1        | 1.32%   |
| ADATA Technology             | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 7.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 6.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 5.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 5.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 4.35%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 4.35%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 3.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.26%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 3.26%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2        | 2.17%   |
| Phison E12 NVMe Controller                                                              | 2        | 2.17%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 2.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 2.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.17%   |
| Western Digital Ultrastar DC SN640 NVMe SSD                                             | 1        | 1.09%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.09%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.09%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.09%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.09%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.09%   |
| Marvell Group 88NR2241 Non-Volatile memory controller                                   | 1        | 1.09%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                          | 1        | 1.09%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 1.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.09%   |
| Intel SSD 660P Series                                                                   | 1        | 1.09%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.09%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.09%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.09%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.09%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                  | 1        | 1.09%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.09%   |
| HighPoint RocketRAID 2720 SAS Controller                                                | 1        | 1.09%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 1.09%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 61.97%  |
| NVMe | 14       | 19.72%  |
| RAID | 6        | 8.45%   |
| IDE  | 4        | 5.63%   |
| SAS  | 3        | 4.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 41       | 83.67%  |
| AMD    | 8        | 16.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 8.16%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 6.12%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz         | 2        | 4.08%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2        | 4.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 4.08%   |
| Intel Xeon CPU E5472 @ 3.00GHz              | 1        | 2.04%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz         | 1        | 2.04%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 2.04%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 2.04%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 2.04%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 2.04%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1        | 2.04%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 2.04%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 2.04%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1        | 2.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2.04%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 2.04%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 2.04%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 2.04%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 2.04%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 2.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 2.04%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 2.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2.04%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.04%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 1        | 2.04%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 1        | 2.04%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 2.04%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 2.04%   |
| Intel Core i5-10600K CPU @ 4.10GHz          | 1        | 2.04%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 2.04%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 2.04%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 1        | 2.04%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 2.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 2.04%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 2.04%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 2.04%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 2.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.04%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.04%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 13       | 26.53%  |
| Intel Core i5      | 11       | 22.45%  |
| Intel Xeon         | 9        | 18.37%  |
| Intel Core i3      | 6        | 12.24%  |
| AMD Ryzen 9        | 3        | 6.12%   |
| Intel Pentium Gold | 2        | 4.08%   |
| AMD Ryzen 7        | 2        | 4.08%   |
| AMD Ryzen 5        | 1        | 2.04%   |
| AMD Ryzen 3        | 1        | 2.04%   |
| AMD FX             | 1        | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 38.78%  |
| 2      | 9        | 18.37%  |
| 6      | 8        | 16.33%  |
| 12     | 5        | 10.2%   |
| 8      | 4        | 8.16%   |
| 36     | 1        | 2.04%   |
| 24     | 1        | 2.04%   |
| 20     | 1        | 2.04%   |
| 16     | 1        | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 89.8%   |
| 2      | 5        | 10.2%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 35       | 70%     |
| 1      | 15       | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 97.96%  |
| Unknown        | 1        | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 9        | 18.37%  |
| 0x906ea    | 7        | 14.29%  |
| 0x306f2    | 4        | 8.16%   |
| 0x306a9    | 4        | 8.16%   |
| 0x906e9    | 3        | 6.12%   |
| 0x906ed    | 2        | 4.08%   |
| 0x506e3    | 2        | 4.08%   |
| 0x206d7    | 2        | 4.08%   |
| 0x08701021 | 2        | 4.08%   |
| 0xa0655    | 1        | 2.04%   |
| 0x906eb    | 1        | 2.04%   |
| 0x806e9    | 1        | 2.04%   |
| 0x406f1    | 1        | 2.04%   |
| 0x306e4    | 1        | 2.04%   |
| 0x206a7    | 1        | 2.04%   |
| 0x10676    | 1        | 2.04%   |
| 0x08701013 | 1        | 2.04%   |
| 0x08108102 | 1        | 2.04%   |
| 0x0810100b | 1        | 2.04%   |
| 0x08001138 | 1        | 2.04%   |
| 0x08001137 | 1        | 2.04%   |
| 0x06000852 | 1        | 2.04%   |
| Unknown    | 1        | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 14       | 28.57%  |
| Haswell     | 13       | 26.53%  |
| IvyBridge   | 6        | 12.24%  |
| Zen 2       | 3        | 6.12%   |
| Zen         | 3        | 6.12%   |
| SandyBridge | 3        | 6.12%   |
| Skylake     | 2        | 4.08%   |
| Zen+        | 1        | 2.04%   |
| Piledriver  | 1        | 2.04%   |
| Penryn      | 1        | 2.04%   |
| CometLake   | 1        | 2.04%   |
| Broadwell   | 1        | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 29       | 50%     |
| Intel  | 21       | 36.21%  |
| AMD    | 8        | 13.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 8.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5%      |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 3.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 3.33%   |
| Intel HD Graphics 630                                                       | 2        | 3.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.67%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 1.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.67%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.67%   |
| Nvidia GM204GL [Quadro M4000]                                               | 1        | 1.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.67%   |
| Nvidia GM107GL [NVS 810]                                                    | 1        | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.67%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 1.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.67%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.67%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.67%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.67%   |
| Nvidia G98 [Quadro NVS 295]                                                 | 1        | 1.67%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.67%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.67%   |
| Intel Iris Plus Graphics 640                                                | 1        | 1.67%   |
| Intel HD Graphics 530                                                       | 1        | 1.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.67%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.67%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.67%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.67%   |
| AMD ES1000                                                                  | 1        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 27       | 54%     |
| 1 x Intel      | 13       | 26%     |
| 1 x AMD        | 5        | 10%     |
| Intel + AMD    | 2        | 4%      |
| 2 x Nvidia     | 1        | 2%      |
| 2 x AMD        | 1        | 2%      |
| Intel + Nvidia | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 66%     |
| Proprietary | 16       | 32%     |
| Unknown     | 1        | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 39.62%  |
| 1.01-2.0   | 10       | 18.87%  |
| 7.01-8.0   | 6        | 11.32%  |
| 3.01-4.0   | 4        | 7.55%   |
| 5.01-6.0   | 3        | 5.66%   |
| 2.01-3.0   | 3        | 5.66%   |
| 0.01-0.5   | 3        | 5.66%   |
| 0.51-1.0   | 2        | 3.77%   |
| 8.01-16.0  | 1        | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 17.86%  |
| Goldstar             | 8        | 14.29%  |
| Lenovo               | 5        | 8.93%   |
| Hewlett-Packard      | 5        | 8.93%   |
| Dell                 | 5        | 8.93%   |
| BenQ                 | 3        | 5.36%   |
| Ancor Communications | 3        | 5.36%   |
| ViewSonic            | 2        | 3.57%   |
| Philips              | 2        | 3.57%   |
| Lenovo Group Limited | 2        | 3.57%   |
| Iiyama               | 2        | 3.57%   |
| Gigabyte Technology  | 2        | 3.57%   |
| Eizo                 | 2        | 3.57%   |
| Acer                 | 2        | 3.57%   |
| LG Electronics       | 1        | 1.79%   |
| Insignia             | 1        | 1.79%   |
| Unknown              | 1        | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 2        | 3.08%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2        | 3.08%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 2        | 3.08%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2        | 3.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 3.08%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1        | 1.54%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1        | 1.54%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1        | 1.54%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1        | 1.54%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 600x340mm 27.2-inch | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1        | 1.54%   |
| Samsung Electronics LCD Monitor S22B150                               | 1        | 1.54%   |
| Samsung Electronics LCD Monitor C49HG9x 3840x1080                     | 1        | 1.54%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1        | 1.54%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch     | 1        | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.54%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 1.54%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 1.54%   |
| LG Electronics LCD Monitor W2486 1920x1080                            | 1        | 1.54%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 1        | 1.54%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 1        | 1.54%   |
| Lenovo Group Limited LCD Monitor LEN T2324pA 3840x1080                | 1        | 1.54%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 9600x2160                | 1        | 1.54%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10 7680x2160                | 1        | 1.54%   |
| Lenovo Group Limited LCD Monitor LEN P27u-10                          | 1        | 1.54%   |
| Insignia HDMI BBY4000 1920x1080 1152x648mm 52.0-inch                  | 1        | 1.54%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 1        | 1.54%   |
| Hewlett-Packard LCD Monitor LA2306                                    | 1        | 1.54%   |
| Hewlett-Packard LA2405x HWP301F 1920x1200 518x324mm 24.1-inch         | 1        | 1.54%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch            | 1        | 1.54%   |
| Hewlett-Packard E233 HPN3460 1920x1080 509x286mm 23.0-inch            | 1        | 1.54%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                  | 1        | 1.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 1        | 1.54%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch              | 1        | 1.54%   |
| Goldstar LG ULTRAWIDE GSM76F6 3440x1440 800x340mm 34.2-inch           | 1        | 1.54%   |
| Goldstar 26LB75  GSM5673 1920x1080 700x390mm 31.5-inch                | 1        | 1.54%   |
| Goldstar 24GM77 GSM5A90 1920x1080 531x298mm 24.0-inch                 | 1        | 1.54%   |
| Goldstar 24GM77 GSM5A8F 1920x1080 531x298mm 24.0-inch                 | 1        | 1.54%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch      | 1        | 1.54%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 1        | 1.54%   |
| Eizo LCD Monitor EV2416W                                              | 1        | 1.54%   |
| Eizo CS2420 ENC2956 1920x1200 519x324mm 24.1-inch                     | 1        | 1.54%   |
| Dell UP2716D DEL40DD 2560x1440 597x336mm 27.0-inch                    | 1        | 1.54%   |
| Dell U2515H DELD06E 2560x1440 550x310mm 24.9-inch                     | 1        | 1.54%   |
| Dell S2719H DELD0CD 1920x1080 598x336mm 27.0-inch                     | 1        | 1.54%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 1        | 1.54%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 1        | 1.54%   |
| Dell LNKG H2VA001 LNKA001 1920x1080 880x500mm 39.8-inch               | 1        | 1.54%   |
| Dell LCD Monitor P2719H 1920x1080                                     | 1        | 1.54%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1        | 1.54%   |
| BenQ GL2250H BNQ78A1 1920x1080 477x268mm 21.5-inch                    | 1        | 1.54%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch               | 1        | 1.54%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 1        | 1.54%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1        | 1.54%   |
| Ancor Communications ASUS VH238 ACI23F9 1920x1080 510x290mm 23.1-inch | 1        | 1.54%   |
| Acer P205H ACR00D1 1600x900 443x249mm 20.0-inch                       | 1        | 1.54%   |
| Acer LCD Monitor S240HL 3840x1080                                     | 1        | 1.54%   |
| Unknown                                                               | 1        | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 27       | 50%     |
| 2560x1440 (QHD)   | 5        | 9.26%   |
| 3840x2160 (4K)    | 4        | 7.41%   |
| 3840x1080         | 3        | 5.56%   |
| 3440x1440         | 3        | 5.56%   |
| 1600x900 (HD+)    | 3        | 5.56%   |
| Unknown           | 3        | 5.56%   |
| 9600x2160         | 1        | 1.85%   |
| 7680x2160         | 1        | 1.85%   |
| 2560x1080         | 1        | 1.85%   |
| 1920x1200 (WUXGA) | 1        | 1.85%   |
| 1440x900 (WXGA+)  | 1        | 1.85%   |
| 1280x720 (HD)     | 1        | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 16.07%  |
| 24      | 8        | 14.29%  |
| 23      | 8        | 14.29%  |
| 27      | 7        | 12.5%   |
| 21      | 7        | 12.5%   |
| 31      | 4        | 7.14%   |
| 20      | 3        | 5.36%   |
| 54      | 2        | 3.57%   |
| 47      | 2        | 3.57%   |
| 34      | 2        | 3.57%   |
| 40      | 1        | 1.79%   |
| 39      | 1        | 1.79%   |
| 25      | 1        | 1.79%   |
| 18      | 1        | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 41.51%  |
| 401-500     | 10       | 18.87%  |
| Unknown     | 9        | 16.98%  |
| 601-700     | 4        | 7.55%   |
| 1001-1500   | 4        | 7.55%   |
| 801-900     | 2        | 3.77%   |
| 701-800     | 2        | 3.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 74.47%  |
| Unknown | 7        | 14.89%  |
| 16/10   | 3        | 6.38%   |
| 21/9    | 2        | 4.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 35.19%  |
| Unknown        | 9        | 16.67%  |
| 301-350        | 7        | 12.96%  |
| 351-500        | 6        | 11.11%  |
| 151-200        | 4        | 7.41%   |
| 501-1000       | 4        | 7.41%   |
| 251-300        | 3        | 5.56%   |
| More than 1000 | 2        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 51.85%  |
| 101-120 | 10       | 18.52%  |
| Unknown | 9        | 16.67%  |
| 1-50    | 4        | 7.41%   |
| 161-240 | 2        | 3.7%    |
| 121-160 | 1        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 71.7%   |
| 2     | 8        | 15.09%  |
| 3     | 4        | 7.55%   |
| 0     | 3        | 5.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 32       | 42.67%  |
| Realtek Semiconductor    | 21       | 28%     |
| Qualcomm Atheros         | 7        | 9.33%   |
| Broadcom                 | 4        | 5.33%   |
| ASIX Electronics         | 2        | 2.67%   |
| Ralink Technology        | 1        | 1.33%   |
| Ralink                   | 1        | 1.33%   |
| Microchip Technology     | 1        | 1.33%   |
| Micro Star International | 1        | 1.33%   |
| MediaTek                 | 1        | 1.33%   |
| Huawei Technologies      | 1        | 1.33%   |
| D-Link                   | 1        | 1.33%   |
| Broadcom Limited         | 1        | 1.33%   |
| Arduino SA               | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19       | 20%     |
| Intel I211 Gigabit Network Connection                                         | 6        | 6.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 5.26%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 3.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 3.16%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 3.16%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 3.16%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 3.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 2.11%   |
| Intel Wireless-AC 9260                                                        | 2        | 2.11%   |
| Intel Wi-Fi 6 AX200                                                           | 2        | 2.11%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 2.11%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.11%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 2.11%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 2.11%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 1.05%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.05%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.05%   |
| Microchip TrueRNG                                                             | 1        | 1.05%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 1.05%   |
| MediaTek Wireless                                                             | 1        | 1.05%   |
| Intel Wireless 7260                                                           | 1        | 1.05%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.05%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.05%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.05%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.05%   |
| Huawei Modem/Networkcard                                                      | 1        | 1.05%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]          | 1        | 1.05%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.05%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.05%   |
| Arduino SA Uno (CDC ACM)                                                      | 1        | 1.05%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 7        | 26.92%  |
| Qualcomm Atheros         | 6        | 23.08%  |
| Realtek Semiconductor    | 4        | 15.38%  |
| Broadcom                 | 4        | 15.38%  |
| Ralink Technology        | 1        | 3.85%   |
| Ralink                   | 1        | 3.85%   |
| Micro Star International | 1        | 3.85%   |
| MediaTek                 | 1        | 3.85%   |
| D-Link                   | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3        | 11.54%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2        | 7.69%   |
| Intel Wireless-AC 9260                                                     | 2        | 7.69%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 3.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 3.85%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 3.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1        | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1        | 3.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.85%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 3.85%   |
| MediaTek Wireless                                                          | 1        | 3.85%   |
| Intel Wireless 7260                                                        | 1        | 3.85%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 32       | 57.14%  |
| Realtek Semiconductor | 19       | 33.93%  |
| Qualcomm Atheros      | 2        | 3.57%   |
| ASIX Electronics      | 2        | 3.57%   |
| Broadcom Limited      | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19       | 28.79%  |
| Intel I211 Gigabit Network Connection                                         | 6        | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 7.58%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 4.55%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 4.55%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 3.03%   |
| Intel Ethernet Connection I217-V                                              | 2        | 3.03%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 3.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 3.03%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 3.03%   |
| Intel Ethernet Connection (2) I218-LM                                         | 2        | 3.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 1.52%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 1.52%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 1.52%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.52%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.52%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express               | 1        | 1.52%   |
| ASIX AX88772A Fast Ethernet                                                   | 1        | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 62.82%  |
| WiFi     | 26       | 33.33%  |
| Modem    | 3        | 3.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 46       | 73.02%  |
| WiFi     | 17       | 26.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 44%     |
| 2     | 16       | 32%     |
| 3     | 10       | 20%     |
| 6     | 1        | 2%      |
| 4     | 1        | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 84%     |
| Yes  | 8        | 16%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 6        | 28.57%  |
| Intel                           | 5        | 23.81%  |
| ASUSTek Computer                | 3        | 14.29%  |
| Realtek Semiconductor           | 2        | 9.52%   |
| Qualcomm Atheros Communications | 2        | 9.52%   |
| Micro Star International        | 1        | 4.76%   |
| IMC Networks                    | 1        | 4.76%   |
| Broadcom                        | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 28.57%  |
| Realtek Bluetooth Radio                               | 2        | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 9.52%   |
| ASUS BCM20702A0                                       | 2        | 9.52%   |
| Micro Star International Bluetooth Device             | 1        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 4.76%   |
| Intel Bluetooth wireless interface                    | 1        | 4.76%   |
| Intel AX200 Bluetooth                                 | 1        | 4.76%   |
| IMC Networks BCM20702A0                               | 1        | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 4.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 38       | 41.76%  |
| Nvidia              | 27       | 29.67%  |
| AMD                 | 11       | 12.09%  |
| Lenovo              | 3        | 3.3%    |
| Creative Labs       | 3        | 3.3%    |
| Texas Instruments   | 1        | 1.1%    |
| Tenx Technology     | 1        | 1.1%    |
| RODE Microphones    | 1        | 1.1%    |
| Plantronics         | 1        | 1.1%    |
| Logitech            | 1        | 1.1%    |
| JMTek               | 1        | 1.1%    |
| DYNEX               | 1        | 1.1%    |
| Creative Technology | 1        | 1.1%    |
| ASUSTek Computer    | 1        | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                 | 8        | 8%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 7%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 5%      |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 4%      |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 3%      |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 3%      |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                 | 3        | 3%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 3%      |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3%      |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2%      |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 2%      |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 2%      |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2%      |
| Intel 200 Series PCH HD Audio                                              | 2        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2%      |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 2%      |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1%      |
| Tenx Technology USB AUDIO                                                  | 1        | 1%      |
| RODE Microphones RODE NT-USB                                               | 1        | 1%      |
| Plantronics BT600                                                          | 1        | 1%      |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1%      |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1%      |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 1%      |
| Logitech H570e Mono                                                        | 1        | 1%      |
| JMTek USB Speaker                                                          | 1        | 1%      |
| Intel Sunrise Point-LP HD Audio                                            | 1        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1%      |
| DYNEX USB MIC Device                                                       | 1        | 1%      |
| Creative Technology Sound Blaster Tactic(3D) Alpha                         | 1        | 1%      |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1%      |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 1%      |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 1        | 1%      |
| ASUSTek Computer Xonar U3 sound card                                       | 1        | 1%      |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 1%      |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 20.83%  |
| Crucial             | 5        | 20.83%  |
| Kingston            | 3        | 12.5%   |
| Corsair             | 3        | 12.5%   |
| SK Hynix            | 2        | 8.33%   |
| Micron Technology   | 2        | 8.33%   |
| Unknown (0x0205)    | 1        | 4.17%   |
| Transcend           | 1        | 4.17%   |
| Patriot             | 1        | 4.17%   |
| GOODRAM             | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 2        | 7.14%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s   | 2        | 7.14%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s         | 1        | 3.57%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s  | 1        | 3.57%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s  | 1        | 3.57%   |
| SK Hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s     | 1        | 3.57%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                | 1        | 3.57%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 3.57%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 3.57%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s      | 1        | 3.57%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s         | 1        | 3.57%   |
| Micron RAM Module 4GB DIMM DDR4 2133MT/s                 | 1        | 3.57%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s     | 1        | 3.57%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s     | 1        | 3.57%   |
| Kingston RAM KHX2400C12D4/8GX 8GB DIMM DDR4 2400MT/s     | 1        | 3.57%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s  | 1        | 3.57%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Crucial RAM CT51264BA160BJ.M8F 4096MB DIMM DDR3 1600MT/s | 1        | 3.57%   |
| Crucial RAM CT4G4DFS824A.M8FG 4GB DIMM DDR4 2400MT/s     | 1        | 3.57%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 3.57%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s   | 1        | 3.57%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s    | 1        | 3.57%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s    | 1        | 3.57%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s    | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 12       | 63.16%  |
| DDR3  | 6        | 31.58%  |
| SDRAM | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 94.74%  |
| SODIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 31.82%  |
| 8192  | 6        | 27.27%  |
| 16384 | 5        | 22.73%  |
| 32768 | 3        | 13.64%  |
| 2048  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 5        | 23.81%  |
| 1600  | 5        | 23.81%  |
| 2667  | 3        | 14.29%  |
| 3600  | 2        | 9.52%   |
| 1333  | 2        | 9.52%   |
| 3200  | 1        | 4.76%   |
| 2933  | 1        | 4.76%   |
| 2666  | 1        | 4.76%   |
| 2133  | 1        | 4.76%   |

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
| Unknown                | 3        | 27.27%  |
| Logitech               | 2        | 18.18%  |
| Generalplus Technology | 2        | 18.18%  |
| Samsung Electronics    | 1        | 9.09%   |
| Ruision                | 1        | 9.09%   |
| Jieli Technology       | 1        | 9.09%   |
| ARC International      | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown FULL HD 1080P Webcam | 3        | 27.27%  |
| Generalplus GENERAL WEBCAM   | 2        | 18.18%  |
| Samsung Galaxy A5 (MTP)      | 1        | 9.09%   |
| Ruision UVC Camera           | 1        | 9.09%   |
| Logitech Webcam C270         | 1        | 9.09%   |
| Logitech HD Webcam C910      | 1        | 9.09%   |
| Jieli USB PHY 2.0            | 1        | 9.09%   |
| ARC International Camera     | 1        | 9.09%   |

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
| 0     | 40       | 80%     |
| 1     | 6        | 12%     |
| 2     | 3        | 6%      |
| 5     | 1        | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 6        | 40%     |
| Net/wireless             | 4        | 26.67%  |
| Storage/ide              | 1        | 6.67%   |
| Sound                    | 1        | 6.67%   |
| Graphics card            | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |
| Bluetooth                | 1        | 6.67%   |

