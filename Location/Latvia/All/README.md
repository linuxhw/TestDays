Linux in Latvia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Latvia/Desktop/README.md) and [notebooks](/Location/Latvia/Notebook/README.md).

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

Total: 385

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8440p             | Notebook    | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [4384be22c4](https://linux-hardware.org/?probe=4384be22c4) | Aug 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [2f45536688](https://linux-hardware.org/?probe=2f45536688) | Aug 12, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [219dd022c6](https://linux-hardware.org/?probe=219dd022c6) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [78415dc6be](https://linux-hardware.org/?probe=78415dc6be) | Jul 25, 2022 |
| Acer          | Aspire 5730                 | Notebook    | [b4877f21ad](https://linux-hardware.org/?probe=b4877f21ad) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [3aa2d086b9](https://linux-hardware.org/?probe=3aa2d086b9) | Jul 23, 2022 |
| Wortmann      | CR700                       | Notebook    | [27d04b5577](https://linux-hardware.org/?probe=27d04b5577) | Jul 23, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1775f75940](https://linux-hardware.org/?probe=1775f75940) | Jul 22, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e9aa6d6be1](https://linux-hardware.org/?probe=e9aa6d6be1) | Jul 06, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Gigabyte      | G33M-S2                     | Desktop     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [fab553a2b2](https://linux-hardware.org/?probe=fab553a2b2) | Jun 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e75d068a21](https://linux-hardware.org/?probe=e75d068a21) | Jun 02, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | Notebook    | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [cd2a742b8c](https://linux-hardware.org/?probe=cd2a742b8c) | May 18, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e854926e0](https://linux-hardware.org/?probe=8e854926e0) | May 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [3a940a3394](https://linux-hardware.org/?probe=3a940a3394) | May 11, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| HP            | 2AAC                        | Desktop     | [1f6b08507e](https://linux-hardware.org/?probe=1f6b08507e) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [e483a6e634](https://linux-hardware.org/?probe=e483a6e634) | Apr 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | Notebook    | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [83df25aace](https://linux-hardware.org/?probe=83df25aace) | Feb 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [9dfc1ac601](https://linux-hardware.org/?probe=9dfc1ac601) | Feb 12, 2022 |
| ASRock        | X79 Extreme9                | Desktop     | [0848fdb73f](https://linux-hardware.org/?probe=0848fdb73f) | Feb 12, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [36f709712b](https://linux-hardware.org/?probe=36f709712b) | Feb 08, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [834bc65728](https://linux-hardware.org/?probe=834bc65728) | Feb 04, 2022 |
| ASUSTek       | P5Q-EM                      | Desktop     | [887e40e6c7](https://linux-hardware.org/?probe=887e40e6c7) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| MSI           | P55-GD65                    | Desktop     | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | Notebook    | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [a864c07042](https://linux-hardware.org/?probe=a864c07042) | Dec 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | Notebook    | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | Notebook    | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| HP            | 304Bh                       | Desktop     | [643a84ae14](https://linux-hardware.org/?probe=643a84ae14) | Oct 26, 2021 |
| HP            | 304Bh                       | Desktop     | [b7bd300808](https://linux-hardware.org/?probe=b7bd300808) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | Notebook    | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [5b32c9197c](https://linux-hardware.org/?probe=5b32c9197c) | Aug 28, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [8cd8b7faa5](https://linux-hardware.org/?probe=8cd8b7faa5) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | Notebook    | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | Notebook    | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | Notebook    | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | Notebook    | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | Notebook    | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | Notebook    | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | Notebook    | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | Notebook    | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | Notebook    | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | Notebook    | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| MSI           | H310M PRO-VD                | Desktop     | [42ade7f952](https://linux-hardware.org/?probe=42ade7f952) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| Dell          | Latitude 5520               | Notebook    | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [25a9c64af7](https://linux-hardware.org/?probe=25a9c64af7) | May 29, 2021 |
| Acer          | AO725                       | Notebook    | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [2d479e2946](https://linux-hardware.org/?probe=2d479e2946) | May 15, 2021 |
| MSI           | H81M-E35                    | Desktop     | [621d19b1f1](https://linux-hardware.org/?probe=621d19b1f1) | May 15, 2021 |
| ASUSTek       | Z97-K R2.0                  | Desktop     | [796bb8e1b8](https://linux-hardware.org/?probe=796bb8e1b8) | May 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4d87fd7e46](https://linux-hardware.org/?probe=4d87fd7e46) | Apr 13, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d2a175100f](https://linux-hardware.org/?probe=d2a175100f) | Mar 22, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | Notebook    | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [344b4339b4](https://linux-hardware.org/?probe=344b4339b4) | Mar 17, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1194a50093](https://linux-hardware.org/?probe=1194a50093) | Mar 16, 2021 |
| HP            | 18E7                        | Desktop     | [d0fb912292](https://linux-hardware.org/?probe=d0fb912292) | Mar 09, 2021 |
| Acer          | F671CR R01-C0               | Desktop     | [7a4637f10b](https://linux-hardware.org/?probe=7a4637f10b) | Mar 06, 2021 |
| Dell          | Latitude E5400              | Notebook    | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [0ac539b524](https://linux-hardware.org/?probe=0ac539b524) | Mar 04, 2021 |
| Dell          | 0HH807                      | Desktop     | [dbde42fa23](https://linux-hardware.org/?probe=dbde42fa23) | Mar 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a49a1ff054](https://linux-hardware.org/?probe=a49a1ff054) | Feb 27, 2021 |
| HP            | 304Bh                       | Desktop     | [92c6653702](https://linux-hardware.org/?probe=92c6653702) | Feb 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3bc6f280d8](https://linux-hardware.org/?probe=3bc6f280d8) | Feb 19, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [0cfdd76052](https://linux-hardware.org/?probe=0cfdd76052) | Feb 08, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | Notebook    | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| ASUSTek       | P5GD1-VM                    | Desktop     | [863b2fd0bf](https://linux-hardware.org/?probe=863b2fd0bf) | Jan 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb2b38d97f](https://linux-hardware.org/?probe=cb2b38d97f) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [5b1abefa3c](https://linux-hardware.org/?probe=5b1abefa3c) | Jan 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [e734d18206](https://linux-hardware.org/?probe=e734d18206) | Jan 06, 2021 |
| MSI           | 970A-G46                    | Desktop     | [b85445cf41](https://linux-hardware.org/?probe=b85445cf41) | Jan 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [81b3dbf5fd](https://linux-hardware.org/?probe=81b3dbf5fd) | Jan 02, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c3b94fff22](https://linux-hardware.org/?probe=c3b94fff22) | Dec 31, 2020 |
| ASUSTek       | N56VM                       | Notebook    | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [2eede62ff5](https://linux-hardware.org/?probe=2eede62ff5) | Dec 26, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8cf512e3a9](https://linux-hardware.org/?probe=8cf512e3a9) | Dec 26, 2020 |
| ASUSTek       | P5K PRO                     | Desktop     | [0e58a56cfb](https://linux-hardware.org/?probe=0e58a56cfb) | Dec 26, 2020 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [bb01071f16](https://linux-hardware.org/?probe=bb01071f16) | Dec 15, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | Notebook    | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| Acer          | Aspire E5-774G              | Notebook    | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | Notebook    | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| MSI           | B75A-G43                    | Desktop     | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| ASUSTek       | F9S                         | Notebook    | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | Notebook    | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f2ff00472b](https://linux-hardware.org/?probe=f2ff00472b) | Nov 07, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bdb367a3b2](https://linux-hardware.org/?probe=bdb367a3b2) | Nov 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [5139c9e029](https://linux-hardware.org/?probe=5139c9e029) | Nov 01, 2020 |
| Acer          | Aspire E1-570               | Notebook    | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7ac6a6dab5](https://linux-hardware.org/?probe=7ac6a6dab5) | Oct 27, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [3ea3e1a644](https://linux-hardware.org/?probe=3ea3e1a644) | Oct 26, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [c9a44de2e0](https://linux-hardware.org/?probe=c9a44de2e0) | Oct 26, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [4e526c6262](https://linux-hardware.org/?probe=4e526c6262) | Oct 14, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [a37fe628b4](https://linux-hardware.org/?probe=a37fe628b4) | Oct 04, 2020 |
| ASUSTek       | PRIME H310T                 | Desktop     | [c6cf49892e](https://linux-hardware.org/?probe=c6cf49892e) | Oct 04, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [a6c2ba4977](https://linux-hardware.org/?probe=a6c2ba4977) | Oct 04, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ebefa289ab](https://linux-hardware.org/?probe=ebefa289ab) | Sep 30, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [2702ecbebe](https://linux-hardware.org/?probe=2702ecbebe) | Sep 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [177f17803c](https://linux-hardware.org/?probe=177f17803c) | Aug 24, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | Notebook    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b68bc64592](https://linux-hardware.org/?probe=b68bc64592) | Aug 02, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d5429ba62e](https://linux-hardware.org/?probe=d5429ba62e) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | Notebook    | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [625d32881c](https://linux-hardware.org/?probe=625d32881c) | May 29, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | Notebook    | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6d6cb669e](https://linux-hardware.org/?probe=d6d6cb669e) | Apr 29, 2020 |
| Acer          | Aspire ES1-512              | Notebook    | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [31631f3ea5](https://linux-hardware.org/?probe=31631f3ea5) | Apr 23, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Biostar       | NF61D-A2                    | Desktop     | [8f1f828d49](https://linux-hardware.org/?probe=8f1f828d49) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [95e2b82808](https://linux-hardware.org/?probe=95e2b82808) | Mar 26, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [9fcf5501fb](https://linux-hardware.org/?probe=9fcf5501fb) | Mar 26, 2020 |
| IBM           | 8215ZCL                     | Desktop     | [8f44ceaa1e](https://linux-hardware.org/?probe=8f44ceaa1e) | Mar 26, 2020 |
| Dell          | Latitude E6230              | Notebook    | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | Notebook    | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | Notebook    | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | Notebook    | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | Notebook    | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [2d568b2e9d](https://linux-hardware.org/?probe=2d568b2e9d) | Feb 19, 2020 |
| ASUSTek       | BU401LAV                    | Notebook    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| MSI           | Z370 SLI PLUS               | Desktop     | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | Notebook    | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | Notebook    | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [9deccd0d74](https://linux-hardware.org/?probe=9deccd0d74) | Jan 24, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e005197c6c](https://linux-hardware.org/?probe=e005197c6c) | Jan 09, 2020 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5af3a0243a](https://linux-hardware.org/?probe=5af3a0243a) | Jan 06, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [70297101fe](https://linux-hardware.org/?probe=70297101fe) | Dec 31, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Dell          | 0RJ290                      | Desktop     | [21ae6dbdf0](https://linux-hardware.org/?probe=21ae6dbdf0) | Dec 16, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | Notebook    | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bab2716ff6](https://linux-hardware.org/?probe=bab2716ff6) | Dec 02, 2019 |
| Dell          | Latitude D630               | Notebook    | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | Notebook    | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | Notebook    | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | Notebook    | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | Notebook    | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | Notebook    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Dell          | Latitude E5510              | Notebook    | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | Notebook    | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a6d137277e](https://linux-hardware.org/?probe=a6d137277e) | Sep 18, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [2fc2bdd742](https://linux-hardware.org/?probe=2fc2bdd742) | Sep 14, 2019 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [5110001e92](https://linux-hardware.org/?probe=5110001e92) | Sep 14, 2019 |
| Gigabyte      | Z87P-D3                     | Desktop     | [a7e732af2a](https://linux-hardware.org/?probe=a7e732af2a) | Aug 26, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [5c290c18c9](https://linux-hardware.org/?probe=5c290c18c9) | Aug 18, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | 0A60h                       | Desktop     | [b031cf2f9c](https://linux-hardware.org/?probe=b031cf2f9c) | Jul 30, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | Notebook    | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | Notebook    | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| MSI           | FM2-A55M-E33                | Desktop     | [426ae68b93](https://linux-hardware.org/?probe=426ae68b93) | Jun 29, 2019 |
| MSI           | B85-G41 PC Mate             | Desktop     | [0f3dccfe4e](https://linux-hardware.org/?probe=0f3dccfe4e) | Jun 26, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | Notebook    | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | Notebook    | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | Notebook    | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | Notebook    | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | Notebook    | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | Notebook    | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | Notebook    | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [5e414bc536](https://linux-hardware.org/?probe=5e414bc536) | Mar 14, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | Notebook    | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | Notebook    | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| ASUSTek       | M2N-VM DVI                  | Desktop     | [3437fc1ab6](https://linux-hardware.org/?probe=3437fc1ab6) | Feb 12, 2019 |
| MSI           | H310M PRO-VD                | Desktop     | [f08ce9bd47](https://linux-hardware.org/?probe=f08ce9bd47) | Jan 09, 2019 |
| Dell          | Inspiron 1720               | Notebook    | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | Notebook    | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | Notebook    | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | Notebook    | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | Notebook    | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | Notebook    | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Dell          | 0WK833                      | Desktop     | [17e742f811](https://linux-hardware.org/?probe=17e742f811) | Jul 11, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | Notebook    | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Dell          | 0WK833                      | Desktop     | [d118bf168b](https://linux-hardware.org/?probe=d118bf168b) | Jun 28, 2018 |
| Dell          | 0WK833                      | Desktop     | [0e39368786](https://linux-hardware.org/?probe=0e39368786) | Jun 28, 2018 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [c401108ba6](https://linux-hardware.org/?probe=c401108ba6) | Jun 20, 2018 |
| Acer          | Aspire V5-552G              | Notebook    | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | Notebook    | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Gigabyte      | H55M-D2H                    | Desktop     | [e4e92393a0](https://linux-hardware.org/?probe=e4e92393a0) | Mar 08, 2018 |
| Dell          | XPS MXC062                  | Notebook    | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | Notebook    | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [f4d998043d](https://linux-hardware.org/?probe=f4d998043d) | Jan 29, 2018 |
| ASUSTek       | K73BE                       | Notebook    | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| ASUSTek       | A88XM-A                     | Desktop     | [f7b8e36550](https://linux-hardware.org/?probe=f7b8e36550) | Jan 21, 2018 |
| Acer          | F671CR R01-C0               | Desktop     | [a5b92562b9](https://linux-hardware.org/?probe=a5b92562b9) | Dec 26, 2017 |
| MSI           | MS-7519                     | Desktop     | [81563b0ef8](https://linux-hardware.org/?probe=81563b0ef8) | Nov 18, 2017 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | Notebook    | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| MSI           | MS-7519                     | Desktop     | [5e4728fda0](https://linux-hardware.org/?probe=5e4728fda0) | Sep 17, 2017 |
| ASUSTek       | X553MA                      | Notebook    | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | Notebook    | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | Notebook    | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| ASRock        | G31M-GS                     | Desktop     | [7a4eee4480](https://linux-hardware.org/?probe=7a4eee4480) | May 31, 2017 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [bfab333807](https://linux-hardware.org/?probe=bfab333807) | May 03, 2017 |
| Acer          | EG31M R01-A2                | Desktop     | [018dafc2d0](https://linux-hardware.org/?probe=018dafc2d0) | Apr 27, 2017 |
| eMachines     | Unknown                     | Notebook    | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | Notebook    | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | F9S                         | Notebook    | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | P5Q                         | Desktop     | [26e2520232](https://linux-hardware.org/?probe=26e2520232) | Nov 11, 2016 |
| ASUSTek       | K53SD                       | Notebook    | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | Notebook    | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | Notebook    | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 31        | 11.23%  |
| ROSA R11            | 19        | 6.88%   |
| Ubuntu 18.04        | 15        | 5.43%   |
| ROSA R10            | 12        | 4.35%   |
| ROSA R9             | 10        | 3.62%   |
| KDE neon 20.04      | 8         | 2.9%    |
| ROSA R8.1           | 7         | 2.54%   |
| Arch                | 7         | 2.54%   |
| ROSA R11.1          | 6         | 2.17%   |
| Linux Mint 20.1     | 6         | 2.17%   |
| Debian 11           | 6         | 2.17%   |
| Arch Rolling        | 6         | 2.17%   |
| ROSA R8             | 5         | 1.81%   |
| Pop!_OS 21.04       | 5         | 1.81%   |
| Pop!_OS 20.10       | 5         | 1.81%   |
| Manjaro             | 5         | 1.81%   |
| Ubuntu 22.04        | 4         | 1.45%   |
| Ubuntu 19.10        | 4         | 1.45%   |
| Linux Mint 20.3     | 4         | 1.45%   |
| Linux Mint 19       | 4         | 1.45%   |
| Debian Testing      | 4         | 1.45%   |
| Xubuntu 20.04       | 3         | 1.09%   |
| Ubuntu 21.04        | 3         | 1.09%   |
| Ubuntu 16.04        | 3         | 1.09%   |
| ROSA 12.2           | 3         | 1.09%   |
| ROSA 12.1           | 3         | 1.09%   |
| OpenMandriva 4.50   | 3         | 1.09%   |
| OpenMandriva 4.2    | 3         | 1.09%   |
| Linux Mint 20.2     | 3         | 1.09%   |
| Linux Mint 20       | 3         | 1.09%   |
| Linux Mint 18.3     | 3         | 1.09%   |
| Fedora 35           | 3         | 1.09%   |
| Fedora 30           | 3         | 1.09%   |
| ArcoLinux Rolling   | 3         | 1.09%   |
| Ubuntu 21.10        | 2         | 0.72%   |
| Ubuntu 20.10        | 2         | 0.72%   |
| Pop!_OS 21.10       | 2         | 0.72%   |
| OpenMandriva 4.3    | 2         | 0.72%   |
| Manjaro 20.2.1      | 2         | 0.72%   |
| Linux Mint 19.3     | 2         | 0.72%   |
| Fedora 34           | 2         | 0.72%   |
| Debian 10           | 2         | 0.72%   |
| Zorin 16            | 1         | 0.36%   |
| Xubuntu 21.04       | 1         | 0.36%   |
| Xubuntu 18.04       | 1         | 0.36%   |
| Ubuntu MATE 20.04   | 1         | 0.36%   |
| Ubuntu Budgie 16.04 | 1         | 0.36%   |
| Ubuntu 19.04        | 1         | 0.36%   |
| Ubuntu 18.10        | 1         | 0.36%   |
| Ubuntu              | 1         | 0.36%   |
| SteamOS 3.2         | 1         | 0.36%   |
| Solus 4.1           | 1         | 0.36%   |
| ROSA R12            | 1         | 0.36%   |
| Pop!_OS 22.04       | 1         | 0.36%   |
| Pop!_OS 20.04       | 1         | 0.36%   |
| Peppermint 10       | 1         | 0.36%   |
| Parrot 4.10         | 1         | 0.36%   |
| MX 19               | 1         | 0.36%   |
| Manjaro 20.2        | 1         | 0.36%   |
| Manjaro 20.1.2      | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 66        | 26.51%  |
| ROSA          | 49        | 19.68%  |
| Linux Mint    | 26        | 10.44%  |
| Pop!_OS       | 13        | 5.22%   |
| Arch          | 13        | 5.22%   |
| Debian        | 11        | 4.42%   |
| Manjaro       | 10        | 4.02%   |
| Fedora        | 10        | 4.02%   |
| OpenMandriva  | 8         | 3.21%   |
| KDE neon      | 8         | 3.21%   |
| Xubuntu       | 5         | 2.01%   |
| ArcoLinux     | 4         | 1.61%   |
| Kali          | 3         | 1.2%    |
| Endless       | 3         | 1.2%    |
| Elementary    | 3         | 1.2%    |
| Garuda Linux  | 2         | 0.8%    |
| Clear Linux   | 2         | 0.8%    |
| Zorin         | 1         | 0.4%    |
| Ubuntu MATE   | 1         | 0.4%    |
| Ubuntu Budgie | 1         | 0.4%    |
| SteamOS       | 1         | 0.4%    |
| Solus         | 1         | 0.4%    |
| Peppermint    | 1         | 0.4%    |
| Parrot        | 1         | 0.4%    |
| MX            | 1         | 0.4%    |
| Lubuntu       | 1         | 0.4%    |
| LMDE          | 1         | 0.4%    |
| Kubuntu       | 1         | 0.4%    |
| GNOME OS      | 1         | 0.4%    |
| EndeavourOS   | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 10        | 3.29%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 9         | 2.96%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 8         | 2.63%   |
| 5.4.0-42-generic                   | 6         | 1.97%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 1.64%   |
| 5.4.0-58-generic                   | 4         | 1.32%   |
| 5.4.0-122-generic                  | 4         | 1.32%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 4         | 1.32%   |
| 5.8.0-7630-generic                 | 3         | 0.99%   |
| 5.4.83-generic-2rosa-x86_64        | 3         | 0.99%   |
| 5.4.0-80-generic                   | 3         | 0.99%   |
| 5.4.0-66-generic                   | 3         | 0.99%   |
| 5.4.0-54-generic                   | 3         | 0.99%   |
| 5.4.0-52-generic                   | 3         | 0.99%   |
| 5.13.0-25-generic                  | 3         | 0.99%   |
| 5.12.4-desktop-1omv4050            | 3         | 0.99%   |
| 5.10.14-desktop-1omv4002           | 3         | 0.99%   |
| 5.0.0-37-generic                   | 3         | 0.99%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 0.99%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 0.99%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 0.99%   |
| 5.8.0-48-generic                   | 2         | 0.66%   |
| 5.8.0-25-generic                   | 2         | 0.66%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.66%   |
| 5.4.0-67-generic                   | 2         | 0.66%   |
| 5.4.0-26-generic                   | 2         | 0.66%   |
| 5.4.0-100-generic                  | 2         | 0.66%   |
| 5.3.0-23-generic                   | 2         | 0.66%   |
| 5.16.7-desktop-1omv4003            | 2         | 0.66%   |
| 5.15.0-46-generic                  | 2         | 0.66%   |
| 5.13.6-arch1-1                     | 2         | 0.66%   |
| 5.13.0-39-generic                  | 2         | 0.66%   |
| 5.13.0-28-generic                  | 2         | 0.66%   |
| 5.11.0-7620-generic                | 2         | 0.66%   |
| 5.11.0-43-generic                  | 2         | 0.66%   |
| 5.11.0-38-generic                  | 2         | 0.66%   |
| 5.10.0-8-amd64                     | 2         | 0.66%   |
| 5.10.0-13-amd64                    | 2         | 0.66%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 0.66%   |
| 4.9.76-nrj-desktop-1rosa-x86_64    | 2         | 0.66%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.66%   |
| 4.18.0-18-generic                  | 2         | 0.66%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 0.66%   |
| 4.15.0-54-generic                  | 2         | 0.66%   |
| 4.10.0-38-generic                  | 2         | 0.66%   |
| 5.9.8-2-MANJARO                    | 1         | 0.33%   |
| 5.9.13-1006.native                 | 1         | 0.33%   |
| 5.9.0-kali1-amd64                  | 1         | 0.33%   |
| 5.9.0-5-amd64                      | 1         | 0.33%   |
| 5.8.5-arch1-1                      | 1         | 0.33%   |
| 5.8.16-2-MANJARO                   | 1         | 0.33%   |
| 5.8.13-050813-generic              | 1         | 0.33%   |
| 5.8.12-arch1-1                     | 1         | 0.33%   |
| 5.8.0-7625-generic                 | 1         | 0.33%   |
| 5.8.0-53-generic                   | 1         | 0.33%   |
| 5.8.0-50-generic                   | 1         | 0.33%   |
| 5.8.0-45-generic                   | 1         | 0.33%   |
| 5.8.0-44-generic                   | 1         | 0.33%   |
| 5.8.0-33-generic                   | 1         | 0.33%   |
| 5.8.0-29-generic                   | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 48        | 16.67%  |
| 4.15.0  | 31        | 10.76%  |
| 5.13.0  | 15        | 5.21%   |
| 5.8.0   | 14        | 4.86%   |
| 5.11.0  | 14        | 4.86%   |
| 4.9.20  | 11        | 3.82%   |
| 5.3.0   | 10        | 3.47%   |
| 4.9.60  | 8         | 2.78%   |
| 5.15.0  | 7         | 2.43%   |
| 5.10.0  | 7         | 2.43%   |
| 5.0.0   | 6         | 2.08%   |
| 5.10.74 | 5         | 1.74%   |
| 4.18.0  | 5         | 1.74%   |
| 4.9.155 | 4         | 1.39%   |
| 4.1.34  | 4         | 1.39%   |
| 5.4.83  | 3         | 1.04%   |
| 5.17.1  | 3         | 1.04%   |
| 5.14.0  | 3         | 1.04%   |
| 5.12.4  | 3         | 1.04%   |
| 5.10.14 | 3         | 1.04%   |
| 4.9.41  | 3         | 1.04%   |
| 5.9.0   | 2         | 0.69%   |
| 5.4.72  | 2         | 0.69%   |
| 5.4.32  | 2         | 0.69%   |
| 5.17.5  | 2         | 0.69%   |
| 5.16.7  | 2         | 0.69%   |
| 5.16.15 | 2         | 0.69%   |
| 5.13.6  | 2         | 0.69%   |
| 5.13.12 | 2         | 0.69%   |
| 5.12.14 | 2         | 0.69%   |
| 4.9.9   | 2         | 0.69%   |
| 4.9.76  | 2         | 0.69%   |
| 4.9.124 | 2         | 0.69%   |
| 4.4.0   | 2         | 0.69%   |
| 4.10.0  | 2         | 0.69%   |
| 4.1.38  | 2         | 0.69%   |
| 5.9.8   | 1         | 0.35%   |
| 5.9.13  | 1         | 0.35%   |
| 5.8.5   | 1         | 0.35%   |
| 5.8.16  | 1         | 0.35%   |
| 5.8.13  | 1         | 0.35%   |
| 5.8.12  | 1         | 0.35%   |
| 5.7.5   | 1         | 0.35%   |
| 5.6.3   | 1         | 0.35%   |
| 5.6.18  | 1         | 0.35%   |
| 5.5.5   | 1         | 0.35%   |
| 5.5.16  | 1         | 0.35%   |
| 5.5.13  | 1         | 0.35%   |
| 5.4.33  | 1         | 0.35%   |
| 5.4.18  | 1         | 0.35%   |
| 5.2.9   | 1         | 0.35%   |
| 5.2.17  | 1         | 0.35%   |
| 5.2.14  | 1         | 0.35%   |
| 5.19.1  | 1         | 0.35%   |
| 5.18.3  | 1         | 0.35%   |
| 5.18.19 | 1         | 0.35%   |
| 5.18.12 | 1         | 0.35%   |
| 5.18.10 | 1         | 0.35%   |
| 5.17.0  | 1         | 0.35%   |
| 5.16.18 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 55        | 19.78%  |
| 4.15    | 31        | 11.15%  |
| 4.9     | 27        | 9.71%   |
| 5.13    | 19        | 6.83%   |
| 5.10    | 19        | 6.83%   |
| 5.8     | 18        | 6.47%   |
| 5.11    | 18        | 6.47%   |
| 5.15    | 13        | 4.68%   |
| 5.3     | 10        | 3.6%    |
| 5.12    | 8         | 2.88%   |
| 5.17    | 6         | 2.16%   |
| 5.16    | 6         | 2.16%   |
| 5.0     | 6         | 2.16%   |
| 5.14    | 5         | 1.8%    |
| 4.18    | 5         | 1.8%    |
| 4.1     | 5         | 1.8%    |
| 5.9     | 4         | 1.44%   |
| 5.18    | 4         | 1.44%   |
| 5.5     | 3         | 1.08%   |
| 5.2     | 3         | 1.08%   |
| 5.6     | 2         | 0.72%   |
| 4.4     | 2         | 0.72%   |
| 4.19    | 2         | 0.72%   |
| 4.10    | 2         | 0.72%   |
| 5.7     | 1         | 0.36%   |
| 5.19    | 1         | 0.36%   |
| 4.8     | 1         | 0.36%   |
| 4.20    | 1         | 0.36%   |
| 4.13    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 225       | 94.14%  |
| i686    | 12        | 5.02%   |
| aarch64 | 2         | 0.84%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 91        | 35%     |
| KDE5       | 44        | 16.92%  |
| KDE4       | 34        | 13.08%  |
| Unknown    | 25        | 9.62%   |
| XFCE       | 16        | 6.15%   |
| MATE       | 13        | 5%      |
| X-Cinnamon | 10        | 3.85%   |
| KDE        | 9         | 3.46%   |
| Cinnamon   | 4         | 1.54%   |
| Budgie     | 4         | 1.54%   |
| Pantheon   | 3         | 1.15%   |
| Unity      | 2         | 0.77%   |
| LXQt       | 2         | 0.77%   |
| Deepin     | 2         | 0.77%   |
| LXDE       | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 202       | 81.78%  |
| Wayland | 29        | 11.74%  |
| Unknown | 11        | 4.45%   |
| Tty     | 5         | 2.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 41.18%  |
| SDDM    | 41        | 16.08%  |
| GDM     | 36        | 14.12%  |
| KDM     | 34        | 13.33%  |
| TDM     | 15        | 5.88%   |
| LightDM | 14        | 5.49%   |
| GDM3    | 8         | 3.14%   |
| SLiM    | 1         | 0.39%   |
| MDM     | 1         | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 104       | 41.43%  |
| Unknown     | 64        | 25.5%   |
| lv_LV       | 32        | 12.75%  |
| ru_RU       | 28        | 11.16%  |
| en_GB       | 11        | 4.38%   |
| C           | 6         | 2.39%   |
| ru_RU.UTF_8 | 2         | 0.8%    |
| de_DE       | 2         | 0.8%    |
| osa_US      | 1         | 0.4%    |
| cv_RU       | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 140       | 57.85%  |
| EFI  | 102       | 42.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 190       | 76.31%  |
| Unknown | 28        | 11.24%  |
| Btrfs   | 17        | 6.83%   |
| Overlay | 11        | 4.42%   |
| Zfs     | 1         | 0.4%    |
| Xfs     | 1         | 0.4%    |
| Ext3    | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 48.59%  |
| GPT     | 76        | 30.52%  |
| MBR     | 52        | 20.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 88.89%  |
| Yes       | 28        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 177       | 71.66%  |
| Yes       | 70        | 28.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 43        | 17.99%  |
| Lenovo                  | 39        | 16.32%  |
| Hewlett-Packard         | 33        | 13.81%  |
| Dell                    | 29        | 12.13%  |
| Acer                    | 22        | 9.21%   |
| Gigabyte Technology     | 15        | 6.28%   |
| MSI                     | 14        | 5.86%   |
| ASRock                  | 7         | 2.93%   |
| Toshiba                 | 5         | 2.09%   |
| Samsung Electronics     | 4         | 1.67%   |
| Intel                   | 4         | 1.67%   |
| Raspberry Pi Foundation | 2         | 0.84%   |
| HUAWEI                  | 2         | 0.84%   |
| Fujitsu Siemens         | 2         | 0.84%   |
| Apple                   | 2         | 0.84%   |
| Wortmann AG             | 1         | 0.42%   |
| Valve                   | 1         | 0.42%   |
| Timi                    | 1         | 0.42%   |
| Sony                    | 1         | 0.42%   |
| Razer                   | 1         | 0.42%   |
| Quanta                  | 1         | 0.42%   |
| Packard Bell            | 1         | 0.42%   |
| IBM                     | 1         | 0.42%   |
| Hardkernel              | 1         | 0.42%   |
| Fujitsu                 | 1         | 0.42%   |
| Foxconn                 | 1         | 0.42%   |
| eMachines               | 1         | 0.42%   |
| Biostar                 | 1         | 0.42%   |
| Advent                  | 1         | 0.42%   |
| Acidanthera             | 1         | 0.42%   |
| ABIT                    | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 4         | 1.67%   |
| HP EliteBook 840 G3                                   | 3         | 1.26%   |
| Toshiba Satellite C660                                | 2         | 0.84%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.84%   |
| MSI MS-7721                                           | 2         | 0.84%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 0.84%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 0.84%   |
| HP EliteBook 8440p                                    | 2         | 0.84%   |
| HP 250 G6 Notebook PC                                 | 2         | 0.84%   |
| Gigabyte G33M-S2                                      | 2         | 0.84%   |
| Gigabyte B550 AORUS PRO V2                            | 2         | 0.84%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 0.84%   |
| ASUS X551MA                                           | 2         | 0.84%   |
| Wortmann AG CR700                                     | 1         | 0.42%   |
| Valve Jupiter                                         | 1         | 0.42%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.42%   |
| Toshiba Satellite L750                                | 1         | 0.42%   |
| Toshiba Satellite C50D-B                              | 1         | 0.42%   |
| Timi A35S                                             | 1         | 0.42%   |
| Sony VPCCW2S8E                                        | 1         | 0.42%   |
| Samsung R528/R728                                     | 1         | 0.42%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.42%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.42%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.42%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.42%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.42%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.42%   |
| MSI MS-7C52                                           | 1         | 0.42%   |
| MSI MS-7B46                                           | 1         | 0.42%   |
| MSI MS-7B33                                           | 1         | 0.42%   |
| MSI MS-7996                                           | 1         | 0.42%   |
| MSI MS-7850                                           | 1         | 0.42%   |
| MSI MS-7846                                           | 1         | 0.42%   |
| MSI MS-7758                                           | 1         | 0.42%   |
| MSI MS-7693                                           | 1         | 0.42%   |
| MSI MS-7583                                           | 1         | 0.42%   |
| MSI MS-7519                                           | 1         | 0.42%   |
| MSI GT62VR 6RE                                        | 1         | 0.42%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.42%   |
| Lenovo Yoga C940-14IIL 81Q9                           | 1         | 0.42%   |
| Lenovo Yoga C640-13IML 81UE                           | 1         | 0.42%   |
| Lenovo Y50-70 20378                                   | 1         | 0.42%   |
| Lenovo V110-15IAP 80TG                                | 1         | 0.42%   |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.42%   |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.42%   |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.42%   |
| Lenovo ThinkPad X220 4291Q50                          | 1         | 0.42%   |
| Lenovo ThinkPad X201 Tablet 311396U                   | 1         | 0.42%   |
| Lenovo ThinkPad T60 8741W3M                           | 1         | 0.42%   |
| Lenovo ThinkPad T495 20NK000HMH                       | 1         | 0.42%   |
| Lenovo ThinkPad T430 2347HM4                          | 1         | 0.42%   |
| Lenovo ThinkPad T420 4180ED3                          | 1         | 0.42%   |
| Lenovo ThinkPad T410 2537HN3                          | 1         | 0.42%   |
| Lenovo ThinkPad T400 6475GC8                          | 1         | 0.42%   |
| Lenovo ThinkPad T15 Gen 1 20S6005JMH                  | 1         | 0.42%   |
| Lenovo ThinkPad P71 20HK0005PB                        | 1         | 0.42%   |
| Lenovo ThinkPad P70 20ER0035MH                        | 1         | 0.42%   |
| Lenovo ThinkPad P14s Gen 1 20Y1000HMH                 | 1         | 0.42%   |
| Lenovo ThinkPad L390 20NRCTO1WW                       | 1         | 0.42%   |
| Lenovo ThinkPad E580 20KS001RMH                       | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 20        | 8.37%   |
| Acer Aspire           | 13        | 5.44%   |
| HP EliteBook          | 11        | 4.6%    |
| Dell Inspiron         | 10        | 4.18%   |
| Dell Latitude         | 9         | 3.77%   |
| Lenovo IdeaPad        | 8         | 3.35%   |
| Toshiba Satellite     | 5         | 2.09%   |
| HP ProBook            | 5         | 2.09%   |
| Dell OptiPlex         | 5         | 2.09%   |
| HP Pavilion           | 4         | 1.67%   |
| ASUS VivoBook         | 4         | 1.67%   |
| ASUS All              | 4         | 1.67%   |
| HP 250                | 3         | 1.26%   |
| ASUS PRIME            | 3         | 1.26%   |
| RPi Raspberry         | 2         | 0.84%   |
| MSI MS-7721           | 2         | 0.84%   |
| Lenovo Yoga           | 2         | 0.84%   |
| Lenovo Legion         | 2         | 0.84%   |
| HP Laptop             | 2         | 0.84%   |
| HP Compaq             | 2         | 0.84%   |
| Gigabyte G33M-S2      | 2         | 0.84%   |
| Gigabyte B550         | 2         | 0.84%   |
| Dell XPS              | 2         | 0.84%   |
| ASUS ZenBook          | 2         | 0.84%   |
| ASUS X551MA           | 2         | 0.84%   |
| ASUS TUF              | 2         | 0.84%   |
| ASUS ROG              | 2         | 0.84%   |
| Acer Nitro            | 2         | 0.84%   |
| Wortmann AG CR700     | 1         | 0.42%   |
| Valve Jupiter         | 1         | 0.42%   |
| Timi A35S             | 1         | 0.42%   |
| Sony VPCCW2S8E        | 1         | 0.42%   |
| Samsung R528          | 1         | 0.42%   |
| Samsung 355V4C        | 1         | 0.42%   |
| Samsung 350V5C        | 1         | 0.42%   |
| Samsung 300V3A        | 1         | 0.42%   |
| Razer Blade           | 1         | 0.42%   |
| Quanta TW8            | 1         | 0.42%   |
| Packard Bell EasyNote | 1         | 0.42%   |
| MSI MS-7C52           | 1         | 0.42%   |
| MSI MS-7B46           | 1         | 0.42%   |
| MSI MS-7B33           | 1         | 0.42%   |
| MSI MS-7996           | 1         | 0.42%   |
| MSI MS-7850           | 1         | 0.42%   |
| MSI MS-7846           | 1         | 0.42%   |
| MSI MS-7758           | 1         | 0.42%   |
| MSI MS-7693           | 1         | 0.42%   |
| MSI MS-7583           | 1         | 0.42%   |
| MSI MS-7519           | 1         | 0.42%   |
| MSI GT62VR            | 1         | 0.42%   |
| MSI GP75              | 1         | 0.42%   |
| Lenovo Y50-70         | 1         | 0.42%   |
| Lenovo V110-15IAP     | 1         | 0.42%   |
| Lenovo ThinkBook      | 1         | 0.42%   |
| Lenovo G70-80         | 1         | 0.42%   |
| Lenovo G550           | 1         | 0.42%   |
| Lenovo G50-80         | 1         | 0.42%   |
| Lenovo G50-70         | 1         | 0.42%   |
| Intel NUC6i7KYB       | 1         | 0.42%   |
| Intel DQ87PG          | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 28        | 11.72%  |
| 2019    | 23        | 9.62%   |
| 2018    | 17        | 7.11%   |
| 2012    | 17        | 7.11%   |
| 2020    | 16        | 6.69%   |
| 2015    | 16        | 6.69%   |
| 2007    | 16        | 6.69%   |
| 2014    | 15        | 6.28%   |
| 2011    | 14        | 5.86%   |
| 2008    | 14        | 5.86%   |
| 2010    | 13        | 5.44%   |
| 2017    | 12        | 5.02%   |
| 2009    | 11        | 4.6%    |
| 2016    | 9         | 3.77%   |
| 2021    | 7         | 2.93%   |
| 2006    | 6         | 2.51%   |
| 2022    | 2         | 0.84%   |
| Unknown | 2         | 0.84%   |
| 2004    | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 158       | 66.11%  |
| Desktop        | 74        | 30.96%  |
| Convertible    | 3         | 1.26%   |
| System on chip | 2         | 0.84%   |
| Mini pc        | 2         | 0.84%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 226       | 93.39%  |
| Enabled  | 16        | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 238       | 99.58%  |
| Yes  | 1         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 68        | 27.87%  |
| 4.01-8.0    | 59        | 24.18%  |
| 8.01-16.0   | 42        | 17.21%  |
| 16.01-24.0  | 32        | 13.11%  |
| 32.01-64.0  | 17        | 6.97%   |
| 2.01-3.0    | 9         | 3.69%   |
| 1.01-2.0    | 9         | 3.69%   |
| 24.01-32.0  | 5         | 2.05%   |
| 0.51-1.0    | 2         | 0.82%   |
| 64.01-256.0 | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 31.75%  |
| 2.01-3.0   | 69        | 25.18%  |
| 0.51-1.0   | 42        | 15.33%  |
| 4.01-8.0   | 33        | 12.04%  |
| 3.01-4.0   | 29        | 10.58%  |
| 8.01-16.0  | 9         | 3.28%   |
| 16.01-24.0 | 3         | 1.09%   |
| 24.01-32.0 | 1         | 0.36%   |
| 0.01-0.5   | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 151       | 60.89%  |
| 2      | 64        | 25.81%  |
| 3      | 20        | 8.06%   |
| 4      | 9         | 3.63%   |
| 6      | 2         | 0.81%   |
| 0      | 2         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 56.15%  |
| Yes       | 107       | 43.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 91.7%   |
| No        | 20        | 8.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 75.42%  |
| No        | 59        | 24.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 57.2%   |
| No        | 104       | 42.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Latvia  | 239       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Riga                    | 175       | 69.17%  |
| Jelgava                 | 9         | 3.56%   |
| Daugavpils              | 8         | 3.16%   |
| Liepāja                | 6         | 2.37%   |
| Jūrmala                | 5         | 1.98%   |
| Adazi                   | 5         | 1.98%   |
| Ventspils               | 4         | 1.58%   |
| Salaspils               | 3         | 1.19%   |
| Limbaži                | 3         | 1.19%   |
| Valmiera                | 2         | 0.79%   |
| Talsi                   | 2         | 0.79%   |
| Saulkrasti              | 2         | 0.79%   |
| Kuldīga                | 2         | 0.79%   |
| Jaunmarupe              | 2         | 0.79%   |
| Iecava                  | 2         | 0.79%   |
| Cēsis                  | 2         | 0.79%   |
| Zvejniekciems           | 1         | 0.4%    |
| Ulbroka                 | 1         | 0.4%    |
| Tukums                  | 1         | 0.4%    |
| Tiraine                 | 1         | 0.4%    |
| Saldus                  | 1         | 0.4%    |
| Ragana                  | 1         | 0.4%    |
| Pļaviņas              | 1         | 0.4%    |
| Ogre                    | 1         | 0.4%    |
| Malpils                 | 1         | 0.4%    |
| Lielvārde              | 1         | 0.4%    |
| Jēkabpils Municipality | 1         | 0.4%    |
| Jēkabpils              | 1         | 0.4%    |
| Gulbene                 | 1         | 0.4%    |
| Garciems                | 1         | 0.4%    |
| Dreilini                | 1         | 0.4%    |
| Dobele                  | 1         | 0.4%    |
| Carnikava               | 1         | 0.4%    |
| Brankas                 | 1         | 0.4%    |
| Bauska                  | 1         | 0.4%    |
| Aizpute                 | 1         | 0.4%    |
| Aizkraukle              | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 58        | 80     | 16.86%  |
| Samsung Electronics     | 55        | 79     | 15.99%  |
| WDC                     | 54        | 81     | 15.7%   |
| Kingston                | 34        | 45     | 9.88%   |
| Toshiba                 | 25        | 28     | 7.27%   |
| Hitachi                 | 16        | 21     | 4.65%   |
| Crucial                 | 12        | 16     | 3.49%   |
| Unknown                 | 8         | 12     | 2.33%   |
| Intel                   | 8         | 14     | 2.33%   |
| SK hynix                | 7         | 7      | 2.03%   |
| SanDisk                 | 7         | 13     | 2.03%   |
| HGST                    | 7         | 15     | 2.03%   |
| Micron Technology       | 6         | 6      | 1.74%   |
| A-DATA Technology       | 6         | 8      | 1.74%   |
| Patriot                 | 5         | 9      | 1.45%   |
| OCZ                     | 3         | 4      | 0.87%   |
| KIOXIA                  | 3         | 4      | 0.87%   |
| GOODRAM                 | 3         | 5      | 0.87%   |
| Phison                  | 2         | 2      | 0.58%   |
| LITEON                  | 2         | 2      | 0.58%   |
| China                   | 2         | 2      | 0.58%   |
| XPG                     | 1         | 1      | 0.29%   |
| Verbatim                | 1         | 1      | 0.29%   |
| USB                     | 1         | 1      | 0.29%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.29%   |
| Realtek Semiconductor   | 1         | 1      | 0.29%   |
| Realtek                 | 1         | 1      | 0.29%   |
| PNY                     | 1         | 1      | 0.29%   |
| Plextor                 | 1         | 1      | 0.29%   |
| Netac                   | 1         | 1      | 0.29%   |
| Mushkin                 | 1         | 2      | 0.29%   |
| Maxtor                  | 1         | 1      | 0.29%   |
| LITEONIT                | 1         | 1      | 0.29%   |
| KingSpec                | 1         | 1      | 0.29%   |
| KingFast                | 1         | 2      | 0.29%   |
| Kingchuxing             | 1         | 1      | 0.29%   |
| Intenso                 | 1         | 1      | 0.29%   |
| Integral                | 1         | 1      | 0.29%   |
| IBM/Hitachi             | 1         | 1      | 0.29%   |
| Hrdtac                  | 1         | 1      | 0.29%   |
| GLOWAY                  | 1         | 1      | 0.29%   |
| Fujitsu                 | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 9         | 2.41%   |
| Seagate ST500LT012-1DG142 500GB         | 5         | 1.34%   |
| Samsung SSD 850 EVO 500GB               | 5         | 1.34%   |
| Toshiba MQ01ABF050 500GB                | 4         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB          | 4         | 1.07%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.07%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 1.07%   |
| WDC WD2000JD-00HBB0 200GB               | 3         | 0.8%    |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.8%    |
| Seagate ST500DM005 HD502HJ 500GB        | 3         | 0.8%    |
| Seagate ST1000LM048-2E7172 1TB          | 3         | 0.8%    |
| Samsung SSD 970 EVO Plus 500GB          | 3         | 0.8%    |
| Samsung SSD 650 120GB                   | 3         | 0.8%    |
| Samsung NVMe SSD Drive 500GB            | 3         | 0.8%    |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.8%    |
| Patriot Burst 240GB SSD                 | 3         | 0.8%    |
| Kingston SV300S37A60G 64GB SSD          | 3         | 0.8%    |
| Hitachi HTS547575A9E384 752GB           | 3         | 0.8%    |
| Hitachi HTS545050B9A300 500GB           | 3         | 0.8%    |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.8%    |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.8%    |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.54%   |
| WDC WD5002AALX-00J37A0 500GB            | 2         | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 0.54%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 2         | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 2         | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB             | 2         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB                | 2         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.54%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.54%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.54%   |
| SK hynix HFM512GDJTNG-8310A 512GB       | 2         | 0.54%   |
| SK hynix BC511 NVMe 256GB               | 2         | 0.54%   |
| Seagate ST9160821AS 160GB               | 2         | 0.54%   |
| Seagate ST3500418AS 500GB               | 2         | 0.54%   |
| Seagate ST250DM000-1BD141 250GB         | 2         | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB          | 2         | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.54%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 0.54%   |
| Seagate ST1000DM003-1SB102 1TB          | 2         | 0.54%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD     | 2         | 0.54%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB            | 2         | 0.54%   |
| Samsung SSD 860 PRO 256GB               | 2         | 0.54%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.54%   |
| Samsung SP2504C 250GB                   | 2         | 0.54%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 2         | 0.54%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.54%   |
| Samsung HM321HI 320GB                   | 2         | 0.54%   |
| Samsung HD501LJ 500GB                   | 2         | 0.54%   |
| Samsung HD103UJ 1TB                     | 2         | 0.54%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.54%   |
| Kingston SV300S37A240G 240GB SSD        | 2         | 0.54%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.54%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.54%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 0.54%   |
| HGST HTS725032A7E630 320GB              | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 80     | 34.94%  |
| WDC                 | 45        | 68     | 27.11%  |
| Toshiba             | 21        | 24     | 12.65%  |
| Hitachi             | 16        | 21     | 9.64%   |
| Samsung Electronics | 15        | 19     | 9.04%   |
| HGST                | 7         | 15     | 4.22%   |
| USB                 | 1         | 1      | 0.6%    |
| Maxtor              | 1         | 1      | 0.6%    |
| IBM/Hitachi         | 1         | 1      | 0.6%    |
| Fujitsu             | 1         | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 31        | 41     | 26.96%  |
| Samsung Electronics | 28        | 35     | 24.35%  |
| Crucial             | 12        | 16     | 10.43%  |
| A-DATA Technology   | 6         | 8      | 5.22%   |
| Patriot             | 5         | 9      | 4.35%   |
| WDC                 | 4         | 5      | 3.48%   |
| SanDisk             | 3         | 4      | 2.61%   |
| OCZ                 | 3         | 4      | 2.61%   |
| Micron Technology   | 3         | 3      | 2.61%   |
| Intel               | 3         | 6      | 2.61%   |
| GOODRAM             | 3         | 5      | 2.61%   |
| LITEON              | 2         | 2      | 1.74%   |
| China               | 2         | 2      | 1.74%   |
| Verbatim            | 1         | 1      | 0.87%   |
| PNY                 | 1         | 1      | 0.87%   |
| Plextor             | 1         | 1      | 0.87%   |
| Mushkin             | 1         | 2      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| KingSpec            | 1         | 1      | 0.87%   |
| KingFast            | 1         | 2      | 0.87%   |
| Intenso             | 1         | 1      | 0.87%   |
| Integral            | 1         | 1      | 0.87%   |
| GLOWAY              | 1         | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 140       | 231    | 46.2%   |
| SSD     | 100       | 152    | 33%     |
| NVMe    | 55        | 80     | 18.15%  |
| MMC     | 6         | 10     | 1.98%   |
| Unknown | 2         | 3      | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 196       | 377    | 73.68%  |
| NVMe | 55        | 79     | 20.68%  |
| SAS  | 9         | 10     | 3.38%   |
| MMC  | 6         | 10     | 2.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 159       | 267    | 65.43%  |
| 0.51-1.0   | 70        | 99     | 28.81%  |
| 1.01-2.0   | 9         | 12     | 3.7%    |
| 2.01-3.0   | 2         | 2      | 0.82%   |
| 4.01-10.0  | 2         | 2      | 0.82%   |
| 3.01-4.0   | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 30.97%  |
| 251-500        | 60        | 22.39%  |
| 501-1000       | 32        | 11.94%  |
| 1001-2000      | 24        | 8.96%   |
| 51-100         | 22        | 8.21%   |
| 1-20           | 15        | 5.6%    |
| 21-50          | 11        | 4.1%    |
| 2001-3000      | 9         | 3.36%   |
| More than 3000 | 6         | 2.24%   |
| Unknown        | 6         | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 113       | 41.39%  |
| 21-50     | 39        | 14.29%  |
| 101-250   | 35        | 12.82%  |
| 51-100    | 28        | 10.26%  |
| 251-500   | 26        | 9.52%   |
| 501-1000  | 16        | 5.86%   |
| 1001-2000 | 7         | 2.56%   |
| Unknown   | 6         | 2.2%    |
| 2001-3000 | 3         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2         | 3      | 4.08%   |
| WDC WD2000JD-00HBB0 200GB             | 2         | 4      | 4.08%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 4      | 4.08%   |
| Samsung Electronics SP2504C 250GB     | 2         | 2      | 4.08%   |
| Samsung Electronics HD501LJ 500GB     | 2         | 4      | 4.08%   |
| Kingston SV300S37A60G 64GB SSD        | 2         | 2      | 4.08%   |
| A-DATA Technology SU800NS38 512GB SSD | 2         | 3      | 4.08%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1         | 1      | 2.04%   |
| WDC WD800JD-60MSA1 80GB               | 1         | 1      | 2.04%   |
| WDC WD5002AALX-00J37A0 500GB          | 1         | 1      | 2.04%   |
| WDC WD5001AALS-00E3A0 500GB           | 1         | 1      | 2.04%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1      | 2.04%   |
| WDC WD3200BEVT-75ZCT0 320GB           | 1         | 4      | 2.04%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1         | 1      | 2.04%   |
| WDC WD1600BEVS-60RST0 160GB           | 1         | 1      | 2.04%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1         | 1      | 2.04%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 2.04%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 2.04%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.04%   |
| Seagate ST9500325AS 500GB             | 1         | 3      | 2.04%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 2.04%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 2.04%   |
| Seagate ST3500413AS 500GB             | 1         | 1      | 2.04%   |
| Seagate ST3500312CS 500GB             | 1         | 1      | 2.04%   |
| Seagate ST3250620AS 250GB             | 1         | 1      | 2.04%   |
| Seagate ST3250312AS 250GB             | 1         | 1      | 2.04%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 2.04%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 2.04%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 2.04%   |
| Seagate ST1000DX001-1CM162 1TB        | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.04%   |
| Samsung Electronics HN-M750MBB 752GB  | 1         | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 2.04%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.04%   |
| Hitachi HTS542525K9A300 250GB         | 1         | 1      | 2.04%   |
| Hitachi HTS542516K9SA00 160GB         | 1         | 1      | 2.04%   |
| HGST HTS725032A7E630 320GB            | 1         | 2      | 2.04%   |
| HGST HTS721010A9E630 1TB              | 1         | 2      | 2.04%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.04%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 2.04%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 18     | 27.66%  |
| WDC                 | 12        | 19     | 25.53%  |
| Samsung Electronics | 6         | 8      | 12.77%  |
| HGST                | 5         | 7      | 10.64%  |
| Toshiba             | 3         | 3      | 6.38%   |
| Kingston            | 3         | 3      | 6.38%   |
| Hitachi             | 3         | 3      | 6.38%   |
| A-DATA Technology   | 2         | 3      | 4.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 18     | 32.5%   |
| WDC                 | 11        | 18     | 27.5%   |
| Samsung Electronics | 5         | 7      | 12.5%   |
| HGST                | 5         | 7      | 12.5%   |
| Toshiba             | 3         | 3      | 7.5%    |
| Hitachi             | 3         | 3      | 7.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 56     | 82.05%  |
| SSD  | 5         | 6      | 12.82%  |
| NVMe | 2         | 2      | 5.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 115       | 212    | 42.91%  |
| Works    | 113       | 198    | 42.16%  |
| Malfunc  | 38        | 64     | 14.18%  |
| Failed   | 2         | 2      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 62.41%  |
| AMD                              | 36        | 12.41%  |
| Samsung Electronics              | 19        | 6.55%   |
| SanDisk                          | 10        | 3.45%   |
| SK hynix                         | 7         | 2.41%   |
| JMicron Technology               | 7         | 2.41%   |
| Nvidia                           | 4         | 1.38%   |
| Marvell Technology Group         | 4         | 1.38%   |
| KIOXIA                           | 4         | 1.38%   |
| Toshiba America Info Systems     | 3         | 1.03%   |
| Micron Technology                | 3         | 1.03%   |
| Kingston Technology Company      | 3         | 1.03%   |
| Union Memory (Shenzhen)          | 2         | 0.69%   |
| Phison Electronics               | 2         | 0.69%   |
| ADATA Technology                 | 2         | 0.69%   |
| Silicon Motion                   | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Realtek Semiconductor            | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 7.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 4.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 4.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 3.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 2.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 1.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.76%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.47%   |
| JMicron JMB368 IDE controller                                                    | 5         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.18%   |
| Intel SSD 660P Series                                                            | 4         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 1.18%   |
| AMD FCH IDE Controller                                                           | 4         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.18%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.88%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3         | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 3         | 0.88%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 3         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.88%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 0.59%   |
| SK hynix BC511                                                                   | 2         | 0.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.59%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.59%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.59%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.59%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.59%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 0.59%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                          | 2         | 0.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 0.59%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]              | 2         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.59%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                     | 2         | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 182       | 61.07%  |
| NVMe | 58        | 19.46%  |
| IDE  | 47        | 15.77%  |
| RAID | 11        | 3.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 189       | 79.08%  |
| AMD    | 48        | 20.08%  |
| ARM    | 2         | 0.84%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.09%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 2.09%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.26%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.26%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 1.26%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.26%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 1.26%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.26%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.26%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.84%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 2         | 0.84%   |
| Intel Pentium D CPU 3.40GHz                   | 2         | 0.84%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.84%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.84%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.84%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.84%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.84%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.84%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.84%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2         | 0.84%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.84%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2         | 0.84%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2         | 0.84%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.84%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2         | 0.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.84%   |
| ARM Processor                                 | 2         | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.84%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2         | 0.84%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 2         | 0.84%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 0.42%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1         | 0.42%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 1         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.42%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.42%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.42%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 0.42%   |
| Intel Pentium 4 CPU 2.66GHz                   | 1         | 0.42%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.42%   |
| Intel Genuine CPU T2060 @ 1.60GHz             | 1         | 0.42%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.42%   |
| Intel Genuine CPU 575 @ 2.00GHz               | 1         | 0.42%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.42%   |
| Intel Core i7-8700T CPU @ 2.40GHz             | 1         | 0.42%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 23.43%  |
| Intel Core i7           | 40        | 16.74%  |
| Intel Core i3           | 24        | 10.04%  |
| Intel Core 2 Duo        | 18        | 7.53%   |
| Other                   | 12        | 5.02%   |
| Intel Celeron           | 12        | 5.02%   |
| AMD Ryzen 5             | 12        | 5.02%   |
| AMD Ryzen 7             | 7         | 2.93%   |
| AMD A8                  | 7         | 2.93%   |
| Intel Pentium Dual-Core | 6         | 2.51%   |
| Intel Pentium           | 5         | 2.09%   |
| Intel Core 2            | 5         | 2.09%   |
| Intel Pentium D         | 4         | 1.67%   |
| Intel Pentium Dual      | 3         | 1.26%   |
| Intel Genuine           | 3         | 1.26%   |
| Intel Core 2 Quad       | 3         | 1.26%   |
| AMD Athlon 64 X2        | 3         | 1.26%   |
| AMD Ryzen 3             | 2         | 0.84%   |
| AMD FX                  | 2         | 0.84%   |
| AMD E1                  | 2         | 0.84%   |
| AMD Athlon II X2        | 2         | 0.84%   |
| AMD A10                 | 2         | 0.84%   |
| Intel Xeon              | 1         | 0.42%   |
| Intel Pentium 4         | 1         | 0.42%   |
| Intel Atom              | 1         | 0.42%   |
| AMD Turion 64 X2 Mobile | 1         | 0.42%   |
| AMD Ryzen Threadripper  | 1         | 0.42%   |
| AMD Ryzen 7 PRO         | 1         | 0.42%   |
| AMD Ryzen 5 PRO         | 1         | 0.42%   |
| AMD E2                  | 1         | 0.42%   |
| AMD C-70                | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 133       | 55.19%  |
| 4       | 73        | 30.29%  |
| 6       | 15        | 6.22%   |
| 8       | 8         | 3.32%   |
| 1       | 5         | 2.07%   |
| 3       | 3         | 1.24%   |
| Unknown | 2         | 0.83%   |
| 24      | 1         | 0.41%   |
| 14      | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 238       | 99.58%  |
| Unknown | 1         | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 148       | 61.41%  |
| 1       | 91        | 37.76%  |
| Unknown | 2         | 0.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 98.33%  |
| Unknown        | 3         | 1.26%   |
| 32-bit         | 1         | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 16.73%  |
| 0x306c3    | 14        | 5.71%   |
| 0x306a9    | 13        | 5.31%   |
| 0x206a7    | 13        | 5.31%   |
| 0x1067a    | 13        | 5.31%   |
| 0x406e3    | 10        | 4.08%   |
| 0x906ea    | 8         | 3.27%   |
| 0x6fd      | 7         | 2.86%   |
| 0x20655    | 7         | 2.86%   |
| 0x10676    | 7         | 2.86%   |
| 0x806ec    | 6         | 2.45%   |
| 0x306d4    | 6         | 2.45%   |
| 0x30678    | 6         | 2.45%   |
| 0x06001119 | 6         | 2.45%   |
| 0x806c1    | 5         | 2.04%   |
| 0x506e3    | 5         | 2.04%   |
| 0x40651    | 4         | 1.63%   |
| 0x08108102 | 4         | 1.63%   |
| 0x906e9    | 3         | 1.22%   |
| 0x806ea    | 3         | 1.22%   |
| 0x806e9    | 3         | 1.22%   |
| 0x6f6      | 3         | 1.22%   |
| 0x20652    | 3         | 1.22%   |
| 0x08701021 | 3         | 1.22%   |
| 0xf47      | 2         | 0.82%   |
| 0xa0652    | 2         | 0.82%   |
| 0x906ed    | 2         | 0.82%   |
| 0x706a1    | 2         | 0.82%   |
| 0x6fb      | 2         | 0.82%   |
| 0x6f2      | 2         | 0.82%   |
| 0x406c3    | 2         | 0.82%   |
| 0x106e5    | 2         | 0.82%   |
| 0x0a201009 | 2         | 0.82%   |
| 0x08600103 | 2         | 0.82%   |
| 0x08108109 | 2         | 0.82%   |
| 0x06003106 | 2         | 0.82%   |
| 0x05000119 | 2         | 0.82%   |
| 0x010000c8 | 2         | 0.82%   |
| 0xf65      | 1         | 0.41%   |
| 0xf64      | 1         | 0.41%   |
| 0xf41      | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |
| 0x806d1    | 1         | 0.41%   |
| 0x706e5    | 1         | 0.41%   |
| 0x706a8    | 1         | 0.41%   |
| 0x6fa      | 1         | 0.41%   |
| 0x6ec      | 1         | 0.41%   |
| 0x506c9    | 1         | 0.41%   |
| 0x30673    | 1         | 0.41%   |
| 0x206d6    | 1         | 0.41%   |
| 0x10661    | 1         | 0.41%   |
| 0x0a50000c | 1         | 0.41%   |
| 0x08600106 | 1         | 0.41%   |
| 0x08001137 | 1         | 0.41%   |
| 0x08001126 | 1         | 0.41%   |
| 0x07030106 | 1         | 0.41%   |
| 0x07030105 | 1         | 0.41%   |
| 0x0700010f | 1         | 0.41%   |
| 0x06006705 | 1         | 0.41%   |
| 0x06006704 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 13.39%  |
| Haswell       | 23        | 9.62%   |
| Penryn        | 20        | 8.37%   |
| Core          | 18        | 7.53%   |
| Skylake       | 17        | 7.11%   |
| IvyBridge     | 16        | 6.69%   |
| SandyBridge   | 15        | 6.28%   |
| Westmere      | 11        | 4.6%    |
| Zen 2         | 10        | 4.18%   |
| Silvermont    | 9         | 3.77%   |
| Zen+          | 8         | 3.35%   |
| Piledriver    | 7         | 2.93%   |
| Broadwell     | 6         | 2.51%   |
| TigerLake     | 5         | 2.09%   |
| NetBurst      | 5         | 2.09%   |
| Zen 3         | 4         | 1.67%   |
| K8 Hammer     | 4         | 1.67%   |
| Unknown       | 4         | 1.67%   |
| Goldmont plus | 3         | 1.26%   |
| Zen           | 2         | 0.84%   |
| Steamroller   | 2         | 0.84%   |
| Puma          | 2         | 0.84%   |
| Nehalem       | 2         | 0.84%   |
| K10           | 2         | 0.84%   |
| Icelake       | 2         | 0.84%   |
| Excavator     | 2         | 0.84%   |
| CometLake     | 2         | 0.84%   |
| Bobcat        | 2         | 0.84%   |
| P6            | 1         | 0.42%   |
| Jaguar        | 1         | 0.42%   |
| Goldmont      | 1         | 0.42%   |
| Bulldozer     | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 139       | 49.29%  |
| Nvidia | 83        | 29.43%  |
| AMD    | 60        | 21.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 3.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 3.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.04%   |
| AMD Renoir                                                                               | 6         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.7%    |
| Intel HD Graphics 5500                                                                   | 5         | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.36%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.02%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2         | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.68%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.68%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.68%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.68%   |
| Intel HD Graphics 620                                                                    | 2         | 0.68%   |
| Intel HD Graphics 530                                                                    | 2         | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.68%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.68%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.68%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.68%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.68%   |
| AMD Richland [Radeon HD 8570D]                                                           | 2         | 0.68%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.68%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.68%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.34%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.34%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.34%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.34%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1         | 0.34%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                                 | 1         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 40.83%  |
| 1 x Nvidia     | 48        | 20%     |
| 1 x AMD        | 43        | 17.92%  |
| Intel + Nvidia | 32        | 13.33%  |
| 2 x AMD        | 7         | 2.92%   |
| Intel + AMD    | 7         | 2.92%   |
| Other          | 2         | 0.83%   |
| AMD + Nvidia   | 2         | 0.83%   |
| 2 x Nvidia     | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 192       | 77.73%  |
| Proprietary | 46        | 18.62%  |
| Unknown     | 9         | 3.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 43.78%  |
| 1.01-2.0   | 42        | 16.87%  |
| 0.01-0.5   | 42        | 16.87%  |
| 0.51-1.0   | 24        | 9.64%   |
| 3.01-4.0   | 16        | 6.43%   |
| 5.01-6.0   | 9         | 3.61%   |
| 7.01-8.0   | 6         | 2.41%   |
| 2.01-3.0   | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 16.92%  |
| Samsung Electronics     | 40        | 15.38%  |
| LG Display              | 30        | 11.54%  |
| BOE                     | 21        | 8.08%   |
| Dell                    | 19        | 7.31%   |
| Chimei Innolux          | 17        | 6.54%   |
| Goldstar                | 15        | 5.77%   |
| BenQ                    | 11        | 4.23%   |
| Philips                 | 9         | 3.46%   |
| Lenovo                  | 6         | 2.31%   |
| Hewlett-Packard         | 5         | 1.92%   |
| AOC                     | 4         | 1.54%   |
| Ancor Communications    | 4         | 1.54%   |
| PANDA                   | 3         | 1.15%   |
| ViewSonic               | 2         | 0.77%   |
| Unknown                 | 2         | 0.77%   |
| Sony                    | 2         | 0.77%   |
| Seiko/Epson             | 2         | 0.77%   |
| NEC Computers           | 2         | 0.77%   |
| LG Electronics          | 2         | 0.77%   |
| InfoVision              | 2         | 0.77%   |
| Hitachi                 | 2         | 0.77%   |
| Chi Mei Optoelectronics | 2         | 0.77%   |
| Arnos Instruments       | 2         | 0.77%   |
| Tianma XM               | 1         | 0.38%   |
| Sharp                   | 1         | 0.38%   |
| Quanta Display          | 1         | 0.38%   |
| Plain Tree Systems      | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| LGD                     | 1         | 0.38%   |
| LG Philips              | 1         | 0.38%   |
| HYO                     | 1         | 0.38%   |
| FUS                     | 1         | 0.38%   |
| Apple                   | 1         | 0.38%   |
| ANX                     | 1         | 0.38%   |
| Acer                    | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.46%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 1.09%   |
| Goldstar L194WT GSM4B06 1440x900 410x260mm 19.1-inch                  | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 1.09%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 2         | 0.73%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2         | 0.73%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 2         | 0.73%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2         | 0.73%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.73%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.73%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.73%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 2         | 0.73%   |
| Dell LCD Monitor U2414H                                               | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.73%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 2         | 0.73%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 2         | 0.73%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2         | 0.73%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.73%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1         | 0.36%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1         | 0.36%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1         | 0.36%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1         | 0.36%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.36%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                 | 1         | 0.36%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.36%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.36%   |
| Seiko/Epson LCD Monitor 1366x768                                      | 1         | 0.36%   |
| Seiko/Epson LCD Monitor 1280x800                                      | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x343mm 25.5-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 338x270mm 17.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.36%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1         | 0.36%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.36%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1         | 0.36%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.36%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 86        | 34.96%  |
| 1366x768 (WXGA)    | 58        | 23.58%  |
| 1600x900 (HD+)     | 16        | 6.5%    |
| 1280x1024 (SXGA)   | 13        | 5.28%   |
| 2560x1440 (QHD)    | 11        | 4.47%   |
| 3840x2160 (4K)     | 10        | 4.07%   |
| 1280x800 (WXGA)    | 10        | 4.07%   |
| 1680x1050 (WSXGA+) | 9         | 3.66%   |
| 1440x900 (WXGA+)   | 9         | 3.66%   |
| 1920x1200 (WUXGA)  | 5         | 2.03%   |
| Unknown            | 4         | 1.63%   |
| 3440x1440          | 2         | 0.81%   |
| 1024x768 (XGA)     | 2         | 0.81%   |
| 800x1280           | 1         | 0.41%   |
| 7680x2160          | 1         | 0.41%   |
| 4480x1440          | 1         | 0.41%   |
| 3840x1080          | 1         | 0.41%   |
| 3520x1200          | 1         | 0.41%   |
| 3456x2160          | 1         | 0.41%   |
| 3000x2000          | 1         | 0.41%   |
| 2960x1050          | 1         | 0.41%   |
| 2160x1440          | 1         | 0.41%   |
| 1280x960           | 1         | 0.41%   |
| 1280x720 (HD)      | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 92        | 35.38%  |
| 17      | 22        | 8.46%   |
| 14      | 18        | 6.92%   |
| 24      | 17        | 6.54%   |
| 13      | 17        | 6.54%   |
| 27      | 15        | 5.77%   |
| Unknown | 15        | 5.77%   |
| 23      | 11        | 4.23%   |
| 12      | 10        | 3.85%   |
| 19      | 9         | 3.46%   |
| 22      | 6         | 2.31%   |
| 21      | 6         | 2.31%   |
| 20      | 4         | 1.54%   |
| 25      | 3         | 1.15%   |
| 18      | 3         | 1.15%   |
| 11      | 3         | 1.15%   |
| 40      | 2         | 0.77%   |
| 84      | 1         | 0.38%   |
| 43      | 1         | 0.38%   |
| 35      | 1         | 0.38%   |
| 34      | 1         | 0.38%   |
| 33      | 1         | 0.38%   |
| 31      | 1         | 0.38%   |
| 26      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 123       | 48.62%  |
| 501-600     | 42        | 16.6%   |
| 351-400     | 24        | 9.49%   |
| 401-500     | 21        | 8.3%    |
| 201-300     | 20        | 7.91%   |
| Unknown     | 15        | 5.93%   |
| 801-900     | 3         | 1.19%   |
| 701-800     | 2         | 0.79%   |
| 601-700     | 1         | 0.4%    |
| 1501-2000   | 1         | 0.4%    |
| 901-1000    | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 166       | 70.94%  |
| 16/10   | 32        | 13.68%  |
| 5/4     | 14        | 5.98%   |
| Unknown | 14        | 5.98%   |
| 3/2     | 3         | 1.28%   |
| 4/3     | 2         | 0.85%   |
| 21/9    | 2         | 0.85%   |
| 0.62    | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 35.02%  |
| 201-250        | 36        | 14.01%  |
| 81-90          | 31        | 12.06%  |
| 151-200        | 16        | 6.23%   |
| 301-350        | 15        | 5.84%   |
| Unknown        | 15        | 5.84%   |
| 121-130        | 12        | 4.67%   |
| 61-70          | 10        | 3.89%   |
| 141-150        | 8         | 3.11%   |
| 251-300        | 5         | 1.95%   |
| 71-80          | 4         | 1.56%   |
| 351-500        | 4         | 1.56%   |
| 51-60          | 3         | 1.17%   |
| 501-1000       | 3         | 1.17%   |
| 131-140        | 2         | 0.78%   |
| 91-100         | 2         | 0.78%   |
| More than 1000 | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 77        | 30.43%  |
| 121-160       | 74        | 29.25%  |
| 101-120       | 73        | 28.85%  |
| Unknown       | 15        | 5.93%   |
| 161-240       | 9         | 3.56%   |
| More than 240 | 3         | 1.19%   |
| 1-50          | 2         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 201       | 83.06%  |
| 2     | 32        | 13.22%  |
| 0     | 5         | 2.07%   |
| 3     | 4         | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 129       | 36.34%  |
| Intel                            | 109       | 30.7%   |
| Qualcomm Atheros                 | 44        | 12.39%  |
| Broadcom                         | 21        | 5.92%   |
| Broadcom Limited                 | 9         | 2.54%   |
| Ralink                           | 7         | 1.97%   |
| Marvell Technology Group         | 7         | 1.97%   |
| TP-Link                          | 5         | 1.41%   |
| Nvidia                           | 4         | 1.13%   |
| Xiaomi                           | 2         | 0.56%   |
| Samsung Electronics              | 2         | 0.56%   |
| Ralink Technology                | 2         | 0.56%   |
| Qualcomm Atheros Communications  | 2         | 0.56%   |
| MediaTek                         | 2         | 0.56%   |
| Hewlett-Packard                  | 2         | 0.56%   |
| ASIX Electronics                 | 2         | 0.56%   |
| U-Blox                           | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Lenovo                           | 1         | 0.28%   |
| Huawei Technologies              | 1         | 0.28%   |
| Aquantia                         | 1         | 0.28%   |
| 3Com                             | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 92        | 21.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 22        | 5.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 2.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.89%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.89%   |
| Intel Wireless 8260                                                     | 7         | 1.65%   |
| Intel Wireless 3160                                                     | 7         | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 1.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.18%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.95%   |
| Intel Wireless 7260                                                     | 4         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.71%   |
| Intel Wireless 7265                                                     | 3         | 0.71%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.71%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.47%   |
| TP-Link TL-WN722N v2                                                    | 2         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.47%   |
| Nvidia MCP61 Ethernet                                                   | 2         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 2         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 2         | 0.47%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.47%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.47%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.47%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 48.92%  |
| Qualcomm Atheros                | 34        | 18.28%  |
| Realtek Semiconductor           | 26        | 13.98%  |
| Broadcom                        | 14        | 7.53%   |
| Ralink                          | 7         | 3.76%   |
| TP-Link                         | 5         | 2.69%   |
| Broadcom Limited                | 4         | 2.15%   |
| Ralink Technology               | 2         | 1.08%   |
| Qualcomm Atheros Communications | 2         | 1.08%   |
| MediaTek                        | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.3%    |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.3%    |
| Intel Wireless 8260                                                     | 7         | 3.76%   |
| Intel Wireless 3160                                                     | 7         | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.69%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.15%   |
| Intel Wireless 7260                                                     | 4         | 2.15%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.15%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.61%   |
| Intel Wireless 7265                                                     | 3         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 1.08%   |
| TP-Link TL-WN722N v2                                                    | 2         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.08%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.08%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.08%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.54%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.54%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.54%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.54%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.54%   |
| Intel WiFi Link 5100                                                    | 1         | 0.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 123       | 53.25%  |
| Intel                            | 52        | 22.51%  |
| Qualcomm Atheros                 | 16        | 6.93%   |
| Broadcom                         | 11        | 4.76%   |
| Marvell Technology Group         | 7         | 3.03%   |
| Broadcom Limited                 | 5         | 2.16%   |
| Nvidia                           | 4         | 1.73%   |
| Xiaomi                           | 2         | 0.87%   |
| Samsung Electronics              | 2         | 0.87%   |
| ASIX Electronics                 | 2         | 0.87%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| MediaTek                         | 1         | 0.43%   |
| Lenovo                           | 1         | 0.43%   |
| Huawei Technologies              | 1         | 0.43%   |
| Hewlett-Packard                  | 1         | 0.43%   |
| Aquantia                         | 1         | 0.43%   |
| 3Com                             | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 39.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 9.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.7%    |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.7%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.7%    |
| Intel Ethernet Connection I217-V                                  | 3         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.85%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.85%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2         | 0.85%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.85%   |
| ASIX AX88772B                                                     | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.43%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.43%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.43%   |
| MediaTek Infinix HOT 9                                            | 1         | 0.43%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.43%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.43%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.43%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.43%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.43%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.43%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.43%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1         | 0.43%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 221       | 54.7%   |
| WiFi     | 181       | 44.8%   |
| Modem    | 2         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 61.63%  |
| Ethernet | 94        | 38.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 154       | 64.44%  |
| 1     | 77        | 32.22%  |
| 3     | 4         | 1.67%   |
| 0     | 4         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 229       | 95.82%  |
| Yes  | 10        | 4.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 41.01%  |
| Realtek Semiconductor           | 16        | 11.51%  |
| Qualcomm Atheros Communications | 10        | 7.19%   |
| Lite-On Technology              | 10        | 7.19%   |
| IMC Networks                    | 10        | 7.19%   |
| Broadcom                        | 9         | 6.47%   |
| Cambridge Silicon Radio         | 6         | 4.32%   |
| Dell                            | 5         | 3.6%    |
| Hewlett-Packard                 | 4         | 2.88%   |
| Toshiba                         | 3         | 2.16%   |
| Apple                           | 3         | 2.16%   |
| Ralink                          | 2         | 1.44%   |
| ASUSTek Computer                | 2         | 1.44%   |
| Qcom                            | 1         | 0.72%   |
| Foxconn / Hon Hai               | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 17.27%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 7.19%   |
| Realtek Bluetooth Radio                                                             | 8         | 5.76%   |
| Intel AX200 Bluetooth                                                               | 8         | 5.76%   |
| Intel AX201 Bluetooth                                                               | 7         | 5.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 3.6%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.88%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.16%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.44%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.44%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.44%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 1.44%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.44%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.44%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.44%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.44%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 1.44%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.44%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 1.44%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.72%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.72%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.72%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.72%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.72%   |
| Intel Bluetooth Device                                                              | 1         | 0.72%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.72%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.72%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.72%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.72%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.72%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.72%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.72%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.72%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.72%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 187       | 57.72%  |
| AMD                              | 57        | 17.59%  |
| Nvidia                           | 53        | 16.36%  |
| C-Media Electronics              | 8         | 2.47%   |
| Yamaha                           | 2         | 0.62%   |
| Logitech                         | 2         | 0.62%   |
| Creative Technology              | 2         | 0.62%   |
| Creative Labs                    | 2         | 0.62%   |
| Unknown                          | 1         | 0.31%   |
| Syntek                           | 1         | 0.31%   |
| SteelSeries ApS                  | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Realtek Semiconductor            | 1         | 0.31%   |
| Microsoft                        | 1         | 0.31%   |
| Lenovo                           | 1         | 0.31%   |
| JMTek                            | 1         | 0.31%   |
| GYROCOM C&C                      | 1         | 0.31%   |
| GN Netcom                        | 1         | 0.31%   |
| Apple                            | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 5.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 3.17%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 2.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.58%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.58%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.32%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.79%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.79%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.79%   |
| Yamaha Steinberg UR22mkII                                                                         | 2         | 0.53%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.53%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.53%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.53%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.53%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                                                 | 2         | 0.53%   |
| C-Media Electronics Trust USB microphone                                                          | 2         | 0.53%   |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.53%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.53%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.53%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 19.89%  |
| Kingston            | 33        | 18.75%  |
| SK hynix            | 32        | 18.18%  |
| Unknown             | 29        | 16.48%  |
| Micron Technology   | 14        | 7.95%   |
| Crucial             | 10        | 5.68%   |
| Corsair             | 7         | 3.98%   |
| G.Skill             | 6         | 3.41%   |
| Elpida              | 3         | 1.7%    |
| Ramaxel Technology  | 2         | 1.14%   |
| A-DATA Technology   | 2         | 1.14%   |
| Toshiba             | 1         | 0.57%   |
| Ramos Technology    | 1         | 0.57%   |
| Goodram             | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 4         | 2.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 3         | 1.55%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 3         | 1.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 1.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 2         | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 2         | 1.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2         | 1.04%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                    | 2         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.04%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 1.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 2         | 1.04%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s  | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.04%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.04%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s     | 2         | 1.04%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s    | 2         | 1.04%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s    | 2         | 1.04%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s   | 2         | 1.04%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s   | 2         | 1.04%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s               | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                | 1         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s             | 1         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s             | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s               | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s             | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DRAM                        | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR3                        | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR                      | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s             | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                   | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM                            | 1         | 0.52%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s            | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 1         | 0.52%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s        | 1         | 0.52%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s         | 1         | 0.52%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.52%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 1         | 0.52%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 1         | 0.52%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s     | 1         | 0.52%   |
| SK hynix RAM HYMP564S64CP6-Y5 512MB SODIMM DDR 667MT/s    | 1         | 0.52%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s     | 1         | 0.52%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 59        | 41.55%  |
| DDR4    | 52        | 36.62%  |
| DDR2    | 12        | 8.45%   |
| Unknown | 7         | 4.93%   |
| SDRAM   | 5         | 3.52%   |
| LPDDR4  | 3         | 2.11%   |
| DDR     | 3         | 2.11%   |
| DRAM    | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 69.5%   |
| DIMM         | 40        | 28.37%  |
| Row Of Chips | 3         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 56        | 34.78%  |
| 8192  | 48        | 29.81%  |
| 2048  | 32        | 19.88%  |
| 16384 | 13        | 8.07%   |
| 1024  | 8         | 4.97%   |
| 32768 | 2         | 1.24%   |
| 512   | 2         | 1.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 23.03%  |
| 2667    | 23        | 13.94%  |
| 2133    | 13        | 7.88%   |
| 1333    | 13        | 7.88%   |
| 667     | 13        | 7.88%   |
| 3200    | 10        | 6.06%   |
| 1334    | 9         | 5.45%   |
| 2400    | 8         | 4.85%   |
| Unknown | 6         | 3.64%   |
| 800     | 4         | 2.42%   |
| 1867    | 3         | 1.82%   |
| 1066    | 3         | 1.82%   |
| 4267    | 2         | 1.21%   |
| 3466    | 2         | 1.21%   |
| 3266    | 2         | 1.21%   |
| 3000    | 2         | 1.21%   |
| 1067    | 2         | 1.21%   |
| 533     | 2         | 1.21%   |
| 4199    | 1         | 0.61%   |
| 3866    | 1         | 0.61%   |
| 3600    | 1         | 0.61%   |
| 2448    | 1         | 0.61%   |
| 2134    | 1         | 0.61%   |
| 1866    | 1         | 0.61%   |
| 1800    | 1         | 0.61%   |
| 1639    | 1         | 0.61%   |
| 975     | 1         | 0.61%   |
| 200     | 1         | 0.61%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 3         | 33.33%  |
| Canon               | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Samsung SCX-4216F Scanner | 1         | 11.11%  |
| Samsung SCX-4100 Scanner  | 1         | 11.11%  |
| Samsung SCX-3200 Series   | 1         | 11.11%  |
| HP Officejet 4500 G510g-m | 1         | 11.11%  |
| HP LaserJet 1018          | 1         | 11.11%  |
| HP LaserJet 1010          | 1         | 11.11%  |
| HP DeskJet 5940           | 1         | 11.11%  |
| Canon PIXMA MG3000 series | 1         | 11.11%  |
| Brother DCP-L2510D series | 1         | 11.11%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 23.27%  |
| IMC Networks                           | 19        | 11.95%  |
| Realtek Semiconductor                  | 14        | 8.81%   |
| Microdia                               | 10        | 6.29%   |
| Logitech                               | 8         | 5.03%   |
| Acer                                   | 8         | 5.03%   |
| Sunplus Innovation Technology          | 7         | 4.4%    |
| Quanta                                 | 7         | 4.4%    |
| Suyin                                  | 6         | 3.77%   |
| Lite-On Technology                     | 6         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.77%   |
| Syntek                                 | 5         | 3.14%   |
| Z-Star Microelectronics                | 3         | 1.89%   |
| Silicon Motion                         | 3         | 1.89%   |
| Luxvisions Innotech Limited            | 3         | 1.89%   |
| Samsung Electronics                    | 2         | 1.26%   |
| Ricoh                                  | 2         | 1.26%   |
| Genesys Logic                          | 2         | 1.26%   |
| Apple                                  | 2         | 1.26%   |
| Primax Electronics                     | 1         | 0.63%   |
| Pixart Imaging                         | 1         | 0.63%   |
| OmniVision Technologies                | 1         | 0.63%   |
| Microsoft                              | 1         | 0.63%   |
| Lenovo                                 | 1         | 0.63%   |
| KYE Systems (Mouse Systems)            | 1         | 0.63%   |
| GEMBIRD                                | 1         | 0.63%   |
| DigiTech                               | 1         | 0.63%   |
| Cubeternet                             | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam        | 6         | 3.73%   |
| Realtek Integrated_Webcam_HD             | 5         | 3.11%   |
| Chicony Integrated Camera                | 5         | 3.11%   |
| IMC Networks Integrated Camera           | 4         | 2.48%   |
| Chicony HD WebCam                        | 4         | 2.48%   |
| Lite-On Integrated Camera                | 3         | 1.86%   |
| Chicony HP HD Camera                     | 3         | 1.86%   |
| Chicony HD User Facing                   | 3         | 1.86%   |
| Acer Lenovo EasyCamera                   | 3         | 1.86%   |
| Acer Integrated Camera                   | 3         | 1.86%   |
| Z-Star A4 TECH HD PC Camera              | 2         | 1.24%   |
| Suyin HD WebCam                          | 2         | 1.24%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.24%   |
| Sunplus ASUS USB2.0 Webcam               | 2         | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 1.24%   |
| Realtek USB Camera                       | 2         | 1.24%   |
| Realtek Integrated Webcam                | 2         | 1.24%   |
| Realtek HP Webcam                        | 2         | 1.24%   |
| Quanta HD Webcam                         | 2         | 1.24%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.24%   |
| Microdia Integrated Webcam               | 2         | 1.24%   |
| Logitech Webcam C270                     | 2         | 1.24%   |
| Logitech Webcam C170                     | 2         | 1.24%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 2         | 1.24%   |
| IMC Networks USB2.0 UVC HD Webcam        | 2         | 1.24%   |
| Genesys Logic Camera                     | 2         | 1.24%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 1.24%   |
| Chicony USB2.0 HD UVC WebCam             | 2         | 1.24%   |
| Chicony TOSHIBA Web Camera - HD          | 2         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)  | 2         | 1.24%   |
| Chicony HP HD Webcam                     | 2         | 1.24%   |
| Chicony CNF9055 Toshiba Webcam           | 2         | 1.24%   |
| Apple iPhone 5/5C/5S/6/SE                | 2         | 1.24%   |
| Z-Star Vega USB 2.0 Camera               | 1         | 0.62%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S     | 1         | 0.62%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera    | 1         | 0.62%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.62%   |
| Syntek Integrated Camera                 | 1         | 0.62%   |
| Syntek EasyCamera                        | 1         | 0.62%   |
| Suyin HD Video WebCam                    | 1         | 0.62%   |
| Suyin Acer CrystalEye Webcam             | 1         | 0.62%   |
| Sunplus Integrated_Webcam_HD             | 1         | 0.62%   |
| Sunplus Integrated_Webcam_FHD            | 1         | 0.62%   |
| Sunplus HP HD Webcam [Fixed]             | 1         | 0.62%   |
| Sunplus HD WebCam                        | 1         | 0.62%   |
| Sunplus ASUS Webcam                      | 1         | 0.62%   |
| Silicon Motion WebCam SCB-1100N          | 1         | 0.62%   |
| Silicon Motion WebCam SC-03FFL11939N     | 1         | 0.62%   |
| Silicon Motion HP Webcam-101             | 1         | 0.62%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.62%   |
| Ricoh Integrated Webcam                  | 1         | 0.62%   |
| Realtek USB2.0 VGA UVC WebCam            | 1         | 0.62%   |
| Realtek Lenovo EasyCamera                | 1         | 0.62%   |
| Realtek HD WebCam                        | 1         | 0.62%   |
| Quanta VGA WebCam                        | 1         | 0.62%   |
| Quanta USB Webcam                        | 1         | 0.62%   |
| Quanta Laptop_Integrated_Webcam_2HDM     | 1         | 0.62%   |
| Quanta Integrated_Webcam_2M              | 1         | 0.62%   |
| Quanta HP Webcam                         | 1         | 0.62%   |
| Primax HP HD Webcam [Fixed]              | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 42.86%  |
| Synaptics                  | 8         | 22.86%  |
| AuthenTec                  | 3         | 8.57%   |
| Upek                       | 2         | 5.71%   |
| STMicroelectronics         | 2         | 5.71%   |
| Shenzhen Goodix Technology | 2         | 5.71%   |
| Elan Microelectronics      | 2         | 5.71%   |
| LighTuning Technology      | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 11.43%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 8.57%   |
| Validity Sensors VFS491                                                    | 2         | 5.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.71%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 5.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 5.71%   |
| Unknown                                                                    | 2         | 5.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.86%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.86%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.86%   |
| AuthenTec AES1600                                                          | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 11        | 55%     |
| Broadcom    | 5         | 25%     |
| Lenovo      | 2         | 10%     |
| Upek        | 1         | 5%      |
| O2 Micro    | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 11        | 55%     |
| Broadcom 58200                                             | 4         | 20%     |
| Lenovo Integrated Smart Card Reader                        | 2         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 5%      |
| Broadcom 5880                                              | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 177       | 71.66%  |
| 1     | 52        | 21.05%  |
| 2     | 17        | 6.88%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 35        | 41.18%  |
| Graphics card            | 16        | 18.82%  |
| Chipcard                 | 16        | 18.82%  |
| Net/wireless             | 7         | 8.24%   |
| Multimedia controller    | 3         | 3.53%   |
| Communication controller | 2         | 2.35%   |
| Camera                   | 2         | 2.35%   |
| Bluetooth                | 2         | 2.35%   |
| Net/ethernet             | 1         | 1.18%   |
| Card reader              | 1         | 1.18%   |

