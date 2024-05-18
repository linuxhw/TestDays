Archcraft - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Archcraft.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Archcraft/Desktop/README.md) and [notebooks](/Dist/Archcraft/Notebook/README.md).

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

Total: 94

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9daac6faa](https://linux-hardware.org/?probe=f9daac6faa) | May 04, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [2faf3d5ce2](https://linux-hardware.org/?probe=2faf3d5ce2) | Apr 28, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [81bca40901](https://linux-hardware.org/?probe=81bca40901) | Apr 27, 2024 |
| Dell          | Latitude 7290               | Notebook    | [b23f2a505a](https://linux-hardware.org/?probe=b23f2a505a) | Apr 10, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [2cb306402a](https://linux-hardware.org/?probe=2cb306402a) | Feb 23, 2024 |
| SmbiosType... | N20                         | Notebook    | [0188c2ee35](https://linux-hardware.org/?probe=0188c2ee35) | Feb 05, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [b77d6182e0](https://linux-hardware.org/?probe=b77d6182e0) | Jan 27, 2024 |
| MouseCompu... | EGPN711R307                 | Notebook    | [fc34633537](https://linux-hardware.org/?probe=fc34633537) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| HP            | 18E4                        | Desktop     | [db6b92644b](https://linux-hardware.org/?probe=db6b92644b) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [7ccf4ea5c0](https://linux-hardware.org/?probe=7ccf4ea5c0) | Dec 09, 2023 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | Desktop     | [82b916eb4a](https://linux-hardware.org/?probe=82b916eb4a) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [de15a66a8b](https://linux-hardware.org/?probe=de15a66a8b) | Oct 22, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [85f07c28fa](https://linux-hardware.org/?probe=85f07c28fa) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Dell          | 0KP561                      | Desktop     | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [08d5b71848](https://linux-hardware.org/?probe=08d5b71848) | Jul 22, 2023 |
| Dell          | Latitude E5420              | Notebook    | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2bdf7534ad](https://linux-hardware.org/?probe=2bdf7534ad) | Jul 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e3ad1f49b1](https://linux-hardware.org/?probe=e3ad1f49b1) | Jul 13, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [2499e68e07](https://linux-hardware.org/?probe=2499e68e07) | Jul 01, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [0efc49ca3a](https://linux-hardware.org/?probe=0efc49ca3a) | Jun 28, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [72514911c8](https://linux-hardware.org/?probe=72514911c8) | Jun 28, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| HP            | Notebook                    | Notebook    | [1ce7986145](https://linux-hardware.org/?probe=1ce7986145) | Jun 11, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines     | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [9ac134681b](https://linux-hardware.org/?probe=9ac134681b) | Aug 06, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Medion        | E3223                       | Convertible | [8d78a4424e](https://linux-hardware.org/?probe=8d78a4424e) | Jul 06, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo      | CHT14B                      | Notebook    | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| Framework     | Laptop                      | Notebook    | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard      | Unknown                     | Notebook    | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| ECS           | G31T-M                      | Desktop     | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | Desktop     | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | Desktop     | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |
| Google        | Kindred                     | Notebook    | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP            | Pavilion g4                 | Notebook    | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 61        | 84.72%  |
| Archcraft         | 11        | 15.28%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Archcraft | 72        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.18.16-arch1-1       | 4         | 5.19%   |
| 6.3.9-arch1-1         | 3         | 3.9%    |
| 5.19.13-arch1-1       | 3         | 3.9%    |
| 6.8.7-arch1-2         | 2         | 2.6%    |
| 6.4.4-zen1-1-zen      | 2         | 2.6%    |
| 6.4.1-arch2-1         | 2         | 2.6%    |
| 6.2.13-arch1-1        | 2         | 2.6%    |
| 5.12.7-arch1-1        | 2         | 2.6%    |
| 6.8.9-arch1-1         | 1         | 1.3%    |
| 6.8.4-zen1-1-zen      | 1         | 1.3%    |
| 6.7.5-arch1-1         | 1         | 1.3%    |
| 6.7.1-arch1-1         | 1         | 1.3%    |
| 6.6.8-arch1-1         | 1         | 1.3%    |
| 6.6.7-arch1-1         | 1         | 1.3%    |
| 6.6.6-arch1-1         | 1         | 1.3%    |
| 6.6.4-arch1-1         | 1         | 1.3%    |
| 6.6.10-arch1-1        | 1         | 1.3%    |
| 6.6.1-arch1-1         | 1         | 1.3%    |
| 6.5.5-zen1-1-zen      | 1         | 1.3%    |
| 6.5.4-arch2-1         | 1         | 1.3%    |
| 6.4.7-arch1-1         | 1         | 1.3%    |
| 6.4.4-arch1-1         | 1         | 1.3%    |
| 6.4.3-arch1-1         | 1         | 1.3%    |
| 6.4.12-arch1-1        | 1         | 1.3%    |
| 6.4.10-zen2-1-zen     | 1         | 1.3%    |
| 6.4.10-arch1-1        | 1         | 1.3%    |
| 6.3.8-arch1-1         | 1         | 1.3%    |
| 6.3.7-arch1-1-vfio    | 1         | 1.3%    |
| 6.3.6-arch1-1         | 1         | 1.3%    |
| 6.3.4-arch1-1         | 1         | 1.3%    |
| 6.3.10-1-clear        | 1         | 1.3%    |
| 6.2.8-zen1-1-zen      | 1         | 1.3%    |
| 6.2.2-arch1-1         | 1         | 1.3%    |
| 6.2.12-arch1-1        | 1         | 1.3%    |
| 6.1.9-x64v1-xanmod1-1 | 1         | 1.3%    |
| 6.1.7-arch1-1         | 1         | 1.3%    |
| 6.1.4-x64v1-xanmod1-1 | 1         | 1.3%    |
| 6.1.1-arch1-1         | 1         | 1.3%    |
| 6.0.7-arch1-1         | 1         | 1.3%    |
| 6.0.2-arch1-1         | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.16 | 4         | 5.19%   |
| 6.4.4   | 3         | 3.9%    |
| 6.3.9   | 3         | 3.9%    |
| 5.19.13 | 3         | 3.9%    |
| 6.8.7   | 2         | 2.6%    |
| 6.4.10  | 2         | 2.6%    |
| 6.4.1   | 2         | 2.6%    |
| 6.2.13  | 2         | 2.6%    |
| 5.12.7  | 2         | 2.6%    |
| 6.8.9   | 1         | 1.3%    |
| 6.8.4   | 1         | 1.3%    |
| 6.7.5   | 1         | 1.3%    |
| 6.7.1   | 1         | 1.3%    |
| 6.6.8   | 1         | 1.3%    |
| 6.6.7   | 1         | 1.3%    |
| 6.6.6   | 1         | 1.3%    |
| 6.6.4   | 1         | 1.3%    |
| 6.6.10  | 1         | 1.3%    |
| 6.6.1   | 1         | 1.3%    |
| 6.5.5   | 1         | 1.3%    |
| 6.5.4   | 1         | 1.3%    |
| 6.4.7   | 1         | 1.3%    |
| 6.4.3   | 1         | 1.3%    |
| 6.4.12  | 1         | 1.3%    |
| 6.3.8   | 1         | 1.3%    |
| 6.3.7   | 1         | 1.3%    |
| 6.3.6   | 1         | 1.3%    |
| 6.3.4   | 1         | 1.3%    |
| 6.3.10  | 1         | 1.3%    |
| 6.2.8   | 1         | 1.3%    |
| 6.2.2   | 1         | 1.3%    |
| 6.2.12  | 1         | 1.3%    |
| 6.1.9   | 1         | 1.3%    |
| 6.1.7   | 1         | 1.3%    |
| 6.1.4   | 1         | 1.3%    |
| 6.1.1   | 1         | 1.3%    |
| 6.0.7   | 1         | 1.3%    |
| 6.0.2   | 1         | 1.3%    |
| 6.0.12  | 1         | 1.3%    |
| 6.0.10  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 9         | 12%     |
| 6.3     | 8         | 10.67%  |
| 5.18    | 8         | 10.67%  |
| 5.19    | 7         | 9.33%   |
| 6.6     | 6         | 8%      |
| 6.2     | 5         | 6.67%   |
| 6.8     | 4         | 5.33%   |
| 6.1     | 4         | 5.33%   |
| 6.0     | 4         | 5.33%   |
| 5.16    | 4         | 5.33%   |
| 5.12    | 4         | 5.33%   |
| 5.17    | 3         | 4%      |
| 6.7     | 2         | 2.67%   |
| 6.5     | 2         | 2.67%   |
| 5.15    | 2         | 2.67%   |
| 5.14    | 2         | 2.67%   |
| 5.10    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 72        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Openbox  | 25        | 34.72%  |
| XFCE     | 22        | 30.56%  |
| bspwm    | 8         | 11.11%  |
| sway     | 3         | 4.17%   |
| KDE5     | 3         | 4.17%   |
| i3       | 2         | 2.78%   |
| GNOME    | 2         | 2.78%   |
| Unknown  | 2         | 2.78%   |
| qtile    | 1         | 1.39%   |
| LXDE     | 1         | 1.39%   |
| Hyprland | 1         | 1.39%   |
| dwm      | 1         | 1.39%   |
| awesome  | 1         | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 88.89%  |
| Wayland | 6         | 8.33%   |
| Unknown | 2         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 52        | 71.23%  |
| Unknown | 12        | 16.44%  |
| LXDM    | 5         | 6.85%   |
| LightDM | 3         | 4.11%   |
| Ly      | 1         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 38        | 52.78%  |
| es_MX | 6         | 8.33%   |
| en_IN | 6         | 8.33%   |
| es_ES | 5         | 6.94%   |
| en_GB | 5         | 6.94%   |
| en_ZA | 2         | 2.78%   |
| en_SG | 2         | 2.78%   |
| tr_TR | 1         | 1.39%   |
| pt_BR | 1         | 1.39%   |
| pl_PL | 1         | 1.39%   |
| it_IT | 1         | 1.39%   |
| fr_FR | 1         | 1.39%   |
| en_PH | 1         | 1.39%   |
| de_DE | 1         | 1.39%   |
| de_AT | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 53        | 73.61%  |
| BIOS | 19        | 26.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 54        | 75%     |
| Btrfs | 15        | 20.83%  |
| Xfs   | 3         | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 56        | 77.78%  |
| Unknown | 10        | 13.89%  |
| MBR     | 6         | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 81.94%  |
| Yes       | 13        | 18.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 66.67%  |
| Yes       | 24        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 14        | 19.44%  |
| Dell                           | 10        | 13.89%  |
| ASUSTek Computer               | 10        | 13.89%  |
| Lenovo                         | 7         | 9.72%   |
| MSI                            | 6         | 8.33%   |
| HUAWEI                         | 3         | 4.17%   |
| Gigabyte Technology            | 3         | 4.17%   |
| ASRock                         | 2         | 2.78%   |
| Apple                          | 2         | 2.78%   |
| Acer                           | 2         | 2.78%   |
| Standard                       | 1         | 1.39%   |
| SmbiosType1_SystemManufacturer | 1         | 1.39%   |
| Positivo                       | 1         | 1.39%   |
| Packard Bell                   | 1         | 1.39%   |
| MouseComputer                  | 1         | 1.39%   |
| Medion                         | 1         | 1.39%   |
| Infinix                        | 1         | 1.39%   |
| Google                         | 1         | 1.39%   |
| Framework                      | 1         | 1.39%   |
| eMachines                      | 1         | 1.39%   |
| ECS                            | 1         | 1.39%   |
| Chuwi                          | 1         | 1.39%   |
| AXDIA International            | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SmbiosType1_SystemManufacturer N20      | 1         | 1.39%   |
| Positivo CHT14B                         | 1         | 1.39%   |
| Packard Bell EasyNote TK85              | 1         | 1.39%   |
| MSI MS-7C91                             | 1         | 1.39%   |
| MSI MS-7C51                             | 1         | 1.39%   |
| MSI Katana GF66 11UE                    | 1         | 1.39%   |
| MSI GL65 Leopard 10SFK                  | 1         | 1.39%   |
| MSI GF63 Thin 10SC                      | 1         | 1.39%   |
| MSI Alpha 15 B5EEK                      | 1         | 1.39%   |
| MouseComputer EGPN711R307               | 1         | 1.39%   |
| Medion E3223                            | 1         | 1.39%   |
| Lenovo ThinkPad T430 2351AK9            | 1         | 1.39%   |
| Lenovo ThinkCentre M710q 10MR0047US     | 1         | 1.39%   |
| Lenovo ThinkCentre Edge72 3484HPU       | 1         | 1.39%   |
| Lenovo MIIX 310-10ICR 80SG              | 1         | 1.39%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9        | 1         | 1.39%   |
| Lenovo IdeaPad 3 15IGL05 81WQ           | 1         | 1.39%   |
| Lenovo IdeaCentre 510A-15ARR 90J00061US | 1         | 1.39%   |
| Infinix INBook X1 Pro                   | 1         | 1.39%   |
| HUAWEI NBD-WXX9                         | 1         | 1.39%   |
| HUAWEI HLYL-WXX9                        | 1         | 1.39%   |
| HUAWEI BOHB-WAX9                        | 1         | 1.39%   |
| HP Stream Laptop 11-ak0xxx              | 1         | 1.39%   |
| HP Spectre x360 Convertible 15-ch0xx    | 1         | 1.39%   |
| HP Pavilion Notebook                    | 1         | 1.39%   |
| HP Pavilion Laptop 15-eh0xxx            | 1         | 1.39%   |
| HP Pavilion Laptop 15-cc1xx             | 1         | 1.39%   |
| HP Pavilion g4                          | 1         | 1.39%   |
| HP Notebook                             | 1         | 1.39%   |
| HP Laptop 15q-bu1xx                     | 1         | 1.39%   |
| HP Laptop 15-dy2xxx                     | 1         | 1.39%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.39%   |
| HP Laptop 15-da0xxx                     | 1         | 1.39%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx    | 1         | 1.39%   |
| HP EliteDesk 800 G1 TWR                 | 1         | 1.39%   |
| HP Dragonfly 13.5 inch G4 Notebook PC   | 1         | 1.39%   |
| Google Kindred                          | 1         | 1.39%   |
| Gigabyte F2A68HM-DS2                    | 1         | 1.39%   |
| Gigabyte B650 AORUS ELITE AX            | 1         | 1.39%   |
| Gigabyte B550I AORUS PRO AX             | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Dell Latitude                      | 5         | 6.94%   |
| HP Pavilion                        | 4         | 5.56%   |
| HP Laptop                          | 4         | 5.56%   |
| ASUS ROG                           | 3         | 4.17%   |
| Lenovo ThinkCentre                 | 2         | 2.78%   |
| Dell Inspiron                      | 2         | 2.78%   |
| ASUS TUF                           | 2         | 2.78%   |
| SmbiosType1_SystemManufacturer N20 | 1         | 1.39%   |
| Positivo CHT14B                    | 1         | 1.39%   |
| Packard Bell EasyNote              | 1         | 1.39%   |
| MSI MS-7C91                        | 1         | 1.39%   |
| MSI MS-7C51                        | 1         | 1.39%   |
| MSI Katana                         | 1         | 1.39%   |
| MSI GL65                           | 1         | 1.39%   |
| MSI GF63                           | 1         | 1.39%   |
| MSI Alpha                          | 1         | 1.39%   |
| MouseComputer EGPN711R307          | 1         | 1.39%   |
| Medion E3223                       | 1         | 1.39%   |
| Lenovo ThinkPad                    | 1         | 1.39%   |
| Lenovo MIIX                        | 1         | 1.39%   |
| Lenovo IdeaPadFlex                 | 1         | 1.39%   |
| Lenovo IdeaPad                     | 1         | 1.39%   |
| Lenovo IdeaCentre                  | 1         | 1.39%   |
| Infinix INBook                     | 1         | 1.39%   |
| HUAWEI NBD-WXX9                    | 1         | 1.39%   |
| HUAWEI HLYL-WXX9                   | 1         | 1.39%   |
| HUAWEI BOHB-WAX9                   | 1         | 1.39%   |
| HP Stream                          | 1         | 1.39%   |
| HP Spectre                         | 1         | 1.39%   |
| HP Notebook                        | 1         | 1.39%   |
| HP ENVY                            | 1         | 1.39%   |
| HP EliteDesk                       | 1         | 1.39%   |
| HP Dragonfly                       | 1         | 1.39%   |
| Google Kindred                     | 1         | 1.39%   |
| Gigabyte F2A68HM-DS2               | 1         | 1.39%   |
| Gigabyte B650                      | 1         | 1.39%   |
| Gigabyte B550I                     | 1         | 1.39%   |
| Framework Laptop                   | 1         | 1.39%   |
| eMachines eME730                   | 1         | 1.39%   |
| ECS G31T-M                         | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 14        | 19.44%  |
| 2020 | 11        | 15.28%  |
| 2018 | 6         | 8.33%   |
| 2014 | 5         | 6.94%   |
| 2022 | 4         | 5.56%   |
| 2019 | 4         | 5.56%   |
| 2017 | 4         | 5.56%   |
| 2016 | 4         | 5.56%   |
| 2015 | 4         | 5.56%   |
| 2012 | 4         | 5.56%   |
| 2011 | 4         | 5.56%   |
| 2023 | 2         | 2.78%   |
| 2010 | 2         | 2.78%   |
| 2007 | 2         | 2.78%   |
| 2013 | 1         | 1.39%   |
| 2008 | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 46        | 63.89%  |
| Desktop     | 20        | 27.78%  |
| Convertible | 5         | 6.94%   |
| Tablet      | 1         | 1.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 71        | 98.61%  |
| Enabled  | 1         | 1.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 98.61%  |
| Yes  | 1         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 25%     |
| 8.01-16.0   | 13        | 18.06%  |
| 16.01-24.0  | 12        | 16.67%  |
| 3.01-4.0    | 11        | 15.28%  |
| 32.01-64.0  | 9         | 12.5%   |
| 1.01-2.0    | 4         | 5.56%   |
| 64.01-256.0 | 3         | 4.17%   |
| 24.01-32.0  | 1         | 1.39%   |
| 2.01-3.0    | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 31.08%  |
| 1.01-2.0  | 20        | 27.03%  |
| 4.01-8.0  | 12        | 16.22%  |
| 3.01-4.0  | 10        | 13.51%  |
| 0.51-1.0  | 6         | 8.11%   |
| 8.01-16.0 | 3         | 4.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 55.56%  |
| 2      | 22        | 30.56%  |
| 3      | 5         | 6.94%   |
| 5      | 2         | 2.78%   |
| 4      | 2         | 2.78%   |
| 7      | 1         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 81.94%  |
| Yes       | 13        | 18.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 72.22%  |
| No        | 20        | 27.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 82.19%  |
| No        | 13        | 17.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 70.83%  |
| No        | 21        | 29.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 14        | 19.44%  |
| India              | 8         | 11.11%  |
| Mexico             | 6         | 8.33%   |
| Spain              | 5         | 6.94%   |
| UK                 | 4         | 5.56%   |
| Germany            | 3         | 4.17%   |
| Brazil             | 3         | 4.17%   |
| Uruguay            | 2         | 2.78%   |
| Thailand           | 2         | 2.78%   |
| South Africa       | 2         | 2.78%   |
| Russia             | 2         | 2.78%   |
| Malaysia           | 2         | 2.78%   |
| Italy              | 2         | 2.78%   |
| Vietnam            | 1         | 1.39%   |
| Turkey             | 1         | 1.39%   |
| Slovakia           | 1         | 1.39%   |
| Poland             | 1         | 1.39%   |
| Philippines        | 1         | 1.39%   |
| Japan              | 1         | 1.39%   |
| Indonesia          | 1         | 1.39%   |
| Hungary            | 1         | 1.39%   |
| France             | 1         | 1.39%   |
| Finland            | 1         | 1.39%   |
| Dominican Republic | 1         | 1.39%   |
| Czechia            | 1         | 1.39%   |
| Colombia           | 1         | 1.39%   |
| Chile              | 1         | 1.39%   |
| Belarus            | 1         | 1.39%   |
| Austria            | 1         | 1.39%   |
| Argentina          | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Madrid             | 3         | 4.11%   |
| Seremban           | 2         | 2.74%   |
| New Delhi          | 2         | 2.74%   |
| Montevideo         | 2         | 2.74%   |
| Cape Town          | 2         | 2.74%   |
| Bangkok            | 2         | 2.74%   |
| Yomitan            | 1         | 1.37%   |
| Welwyn Garden City | 1         | 1.37%   |
| Vienna             | 1         | 1.37%   |
| Valencia           | 1         | 1.37%   |
| Ulm                | 1         | 1.37%   |
| Turin              | 1         | 1.37%   |
| Torreón           | 1         | 1.37%   |
| Tirunelveli        | 1         | 1.37%   |
| Theodore           | 1         | 1.37%   |
| Tábor             | 1         | 1.37%   |
| Stevens Point      | 1         | 1.37%   |
| St Petersburg      | 1         | 1.37%   |
| Sparta             | 1         | 1.37%   |
| Sao Paulo          | 1         | 1.37%   |
| Santo Domingo Este | 1         | 1.37%   |
| Santiago           | 1         | 1.37%   |
| Santa Rosa         | 1         | 1.37%   |
| Rocca di Papa      | 1         | 1.37%   |
| Pune               | 1         | 1.37%   |
| Paulista           | 1         | 1.37%   |
| Osasco             | 1         | 1.37%   |
| Nuremberg          | 1         | 1.37%   |
| Monterrey          | 1         | 1.37%   |
| Milton Keynes      | 1         | 1.37%   |
| Mesa               | 1         | 1.37%   |
| Mazatlán          | 1         | 1.37%   |
| Mar del Plata      | 1         | 1.37%   |
| Mangalore          | 1         | 1.37%   |
| Manchester         | 1         | 1.37%   |
| Malang             | 1         | 1.37%   |
| Loskutova          | 1         | 1.37%   |
| Lorain             | 1         | 1.37%   |
| London             | 1         | 1.37%   |
| Lannion            | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 13        | 15     | 12.04%  |
| Seagate                     | 10        | 15     | 9.26%   |
| Samsung Electronics         | 10        | 10     | 9.26%   |
| Sandisk                     | 8         | 10     | 7.41%   |
| Unknown                     | 7         | 14     | 6.48%   |
| Toshiba                     | 5         | 5      | 4.63%   |
| Phison Electronics          | 5         | 5      | 4.63%   |
| Hitachi                     | 5         | 5      | 4.63%   |
| KIOXIA                      | 4         | 4      | 3.7%    |
| Kingston                    | 4         | 4      | 3.7%    |
| Intel                       | 3         | 6      | 2.78%   |
| Crucial                     | 3         | 3      | 2.78%   |
| Unknown                     | 3         | 3      | 2.78%   |
| SK hynix                    | 2         | 2      | 1.85%   |
| Phison                      | 2         | 2      | 1.85%   |
| Micron/Crucial Technology   | 2         | 2      | 1.85%   |
| A-DATA Technology           | 2         | 3      | 1.85%   |
| Yangtze Memory Technologies | 1         | 1      | 0.93%   |
| SUNEAST                     | 1         | 1      | 0.93%   |
| SPCC                        | 1         | 1      | 0.93%   |
| Solid State Storage         | 1         | 1      | 0.93%   |
| ROG                         | 1         | 1      | 0.93%   |
| Realtek Semiconductor       | 1         | 1      | 0.93%   |
| Patriot                     | 1         | 1      | 0.93%   |
| Netac                       | 1         | 1      | 0.93%   |
| Mushkin                     | 1         | 2      | 0.93%   |
| Micron Technology           | 1         | 2      | 0.93%   |
| MaxDigital                  | 1         | 1      | 0.93%   |
| Kingston Technology Company | 1         | 2      | 0.93%   |
| KingFast                    | 1         | 2      | 0.93%   |
| Initio                      | 1         | 1      | 0.93%   |
| HGST                        | 1         | 1      | 0.93%   |
| Gigabyte Technology         | 1         | 2      | 0.93%   |
| EVM                         | 1         | 1      | 0.93%   |
| China                       | 1         | 2      | 0.93%   |
| Apple                       | 1         | 1      | 0.93%   |
| Apacer                      | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 3.33%   |
| Unknown MMC Card  32GB                            | 3         | 2.5%    |
| Unknown                                           | 3         | 2.5%    |
| Unknown MMC Card  64GB                            | 2         | 1.67%   |
| Seagate ST500LM030-2E717D 500GB                   | 2         | 1.67%   |
| Sandisk WD_BLACK SN770 1TB                        | 2         | 1.67%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 2         | 1.67%   |
| Phison PS5013 E13 NVMe Controller 512GB           | 2         | 1.67%   |
| Phison E16 PCIe4 NVMe Controller 1TB              | 2         | 1.67%   |
| Yangtze Memory YMTC PC005 256GB                   | 1         | 0.83%   |
| WDC WDS500G2B0C-00PXH0 500GB                      | 1         | 0.83%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.83%   |
| WDC WDS200T2B0B 2TB SSD                           | 1         | 0.83%   |
| WDC WD5000AAKX-75U6AA0 500GB                      | 1         | 0.83%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 1         | 0.83%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 1         | 0.83%   |
| WDC WD3200BPVT-22JJ5T0 320GB                      | 1         | 0.83%   |
| WDC WD20 EARX-00PASB0 2TB                         | 1         | 0.83%   |
| WDC WD10SPZX-75Z10T3 1TB                          | 1         | 0.83%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.83%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1         | 0.83%   |
| WDC WD10EZEX-22RKKA0 1TB                          | 1         | 0.83%   |
| WDC WD10EZEX-21M2NA0 1TB                          | 1         | 0.83%   |
| WDC WD10EARS-00MVWB0 1TB                          | 1         | 0.83%   |
| Unknown SD/MMC/MS PRO 128GB                       | 1         | 0.83%   |
| Unknown SC128  128GB                              | 1         | 0.83%   |
| Unknown MMC Card  16GB                            | 1         | 0.83%   |
| Unknown MMC Card  128GB                           | 1         | 0.83%   |
| Unknown Essentiel B 1TB                           | 1         | 0.83%   |
| Toshiba XG6 NVMe SSD Controller 1024GB            | 1         | 0.83%   |
| Toshiba MQ01ABF050 500GB                          | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.83%   |
| Toshiba DT01ACA200 2TB                            | 1         | 0.83%   |
| Toshiba DT01ACA100 1TB                            | 1         | 0.83%   |
| SUNEAST SSD SE800 128GB                           | 1         | 0.83%   |
| SPCC Solid State Disk 128GB                       | 1         | 0.83%   |
| Solid State Storage SSSTC CL1-4D256 256GB         | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 128GB                     | 1         | 0.83%   |
| SK hynix HFS128G39TND-N210A 128GB SSD             | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor     | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| WDC        | 10        | 12     | 29.41%  |
| Seagate    | 10        | 15     | 29.41%  |
| Hitachi    | 5         | 5      | 14.71%  |
| Toshiba    | 4         | 4      | 11.76%  |
| Unknown    | 2         | 3      | 5.88%   |
| MaxDigital | 1         | 1      | 2.94%   |
| Initio     | 1         | 1      | 2.94%   |
| HGST       | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 3         | 3      | 10.71%  |
| WDC                 | 2         | 2      | 7.14%   |
| SanDisk             | 2         | 2      | 7.14%   |
| Samsung Electronics | 2         | 2      | 7.14%   |
| Kingston            | 2         | 2      | 7.14%   |
| Intel               | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| A-DATA Technology   | 2         | 3      | 7.14%   |
| SUNEAST             | 1         | 1      | 3.57%   |
| SPCC                | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Phison              | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| Netac               | 1         | 1      | 3.57%   |
| Gigabyte Technology | 1         | 2      | 3.57%   |
| EVM                 | 1         | 1      | 3.57%   |
| China               | 1         | 2      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |
| Apacer              | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 35        | 47     | 38.04%  |
| HDD     | 25        | 42     | 27.17%  |
| SSD     | 24        | 31     | 26.09%  |
| MMC     | 6         | 11     | 6.52%   |
| Unknown | 2         | 3      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 66     | 45.45%  |
| NVMe | 35        | 47     | 39.77%  |
| SAS  | 7         | 10     | 7.95%   |
| MMC  | 6         | 11     | 6.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 40     | 52.73%  |
| 0.51-1.0   | 18        | 24     | 32.73%  |
| 1.01-2.0   | 4         | 5      | 7.27%   |
| 3.01-4.0   | 2         | 2      | 3.64%   |
| 2.01-3.0   | 1         | 1      | 1.82%   |
| 4.01-10.0  | 1         | 1      | 1.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 27.4%   |
| 251-500        | 18        | 24.66%  |
| 501-1000       | 11        | 15.07%  |
| 1001-2000      | 7         | 9.59%   |
| More than 3000 | 6         | 8.22%   |
| 51-100         | 4         | 5.48%   |
| Unknown        | 4         | 5.48%   |
| 21-50          | 2         | 2.74%   |
| 2001-3000      | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 21        | 28.38%  |
| 1-20           | 17        | 22.97%  |
| 51-100         | 10        | 13.51%  |
| 251-500        | 8         | 10.81%  |
| 101-250        | 7         | 9.46%   |
| 501-1000       | 4         | 5.41%   |
| Unknown        | 4         | 5.41%   |
| 1001-2000      | 2         | 2.7%    |
| More than 3000 | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB   | 1         | 1      | 12.5%   |
| WDC WD5000AAKX-60U6AA0 500GB   | 1         | 1      | 12.5%   |
| WDC WD10EARS-00MVWB0 1TB       | 1         | 1      | 12.5%   |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 12.5%   |
| MaxDigital MD4000GBDS 4TB      | 1         | 1      | 12.5%   |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 12.5%   |
| Hitachi HTS545032A7E380 320GB  | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor     | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| WDC        | 3         | 3      | 37.5%   |
| Hitachi    | 2         | 2      | 25%     |
| Seagate    | 1         | 1      | 12.5%   |
| MaxDigital | 1         | 1      | 12.5%   |
| HGST       | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor     | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| WDC        | 3         | 3      | 37.5%   |
| Hitachi    | 2         | 2      | 25%     |
| Seagate    | 1         | 1      | 12.5%   |
| MaxDigital | 1         | 1      | 12.5%   |
| HGST       | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500410AS 500GB | 1         | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 54        | 86     | 66.67%  |
| Detected | 19        | 36     | 23.46%  |
| Malfunc  | 7         | 8      | 8.64%   |
| Failed   | 1         | 4      | 1.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 43        | 45.74%  |
| AMD                            | 13        | 13.83%  |
| Samsung Electronics            | 8         | 8.51%   |
| SanDisk                        | 7         | 7.45%   |
| Phison Electronics             | 5         | 5.32%   |
| KIOXIA                         | 4         | 4.26%   |
| Micron/Crucial Technology      | 3         | 3.19%   |
| Kingston Technology Company    | 3         | 3.19%   |
| Yangtze Memory Technologies    | 1         | 1.06%   |
| Toshiba America Info Systems   | 1         | 1.06%   |
| Solid State Storage Technology | 1         | 1.06%   |
| SK hynix                       | 1         | 1.06%   |
| Silicon Motion                 | 1         | 1.06%   |
| Realtek Semiconductor          | 1         | 1.06%   |
| Micron Technology              | 1         | 1.06%   |
| ASMedia Technology             | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 7         | 6.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 5         | 4.72%   |
| AMD 500 Series Chipset SATA Controller                                        | 4         | 3.77%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 3         | 2.83%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 3         | 2.83%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 2.83%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.83%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 3         | 2.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 2.83%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 2         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 1.89%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 2         | 1.89%   |
| Phison E16 PCIe4 NVMe Controller                                              | 2         | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 1.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2         | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 2         | 1.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 1.89%   |
| Yangtze Memory PC005 NVMe SSD                                                 | 1         | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.94%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 0.94%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.94%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                    | 1         | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 1         | 0.94%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 1         | 0.94%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.94%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                             | 1         | 0.94%   |
| Phison E18 PCIe4 NVMe Controller                                              | 1         | 0.94%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.94%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.94%   |
| KIOXIA NVMe SSD Controller XG8                                                | 1         | 0.94%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 49        | 51.04%  |
| NVMe | 35        | 36.46%  |
| RAID | 8         | 8.33%   |
| IDE  | 4         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 73.61%  |
| AMD    | 19        | 26.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 3         | 4.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 4.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 2         | 2.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 2         | 2.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 2.78%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2         | 2.78%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2         | 2.78%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1         | 1.39%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.39%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 1.39%   |
| Intel Core i7-8705G CPU @ 3.10GHz              | 1         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i7-5500U CPU @ 2.40GHz              | 1         | 1.39%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.39%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1         | 1.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.39%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.39%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 1         | 1.39%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.39%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 1.39%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.39%   |
| Intel Core i5-2540M CPU @ 2.60GHz              | 1         | 1.39%   |
| Intel Core i5-2467M CPU @ 1.60GHz              | 1         | 1.39%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5 CPU M 450 @ 2.40GHz              | 1         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 1         | 1.39%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.39%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 1         | 1.39%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 1.39%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz             | 1         | 1.39%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.39%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz           | 1         | 1.39%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1         | 1.39%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 15        | 20.83%  |
| Intel Core i7        | 9         | 12.5%   |
| Other                | 8         | 11.11%  |
| AMD Ryzen 5          | 7         | 9.72%   |
| Intel Core i3        | 6         | 8.33%   |
| Intel Celeron        | 6         | 8.33%   |
| AMD Ryzen 7          | 6         | 8.33%   |
| Intel Core 2 Duo     | 3         | 4.17%   |
| Intel Atom           | 3         | 4.17%   |
| AMD Ryzen 9          | 3         | 4.17%   |
| AMD A10              | 2         | 2.78%   |
| Intel Xeon           | 1         | 1.39%   |
| Intel Pentium Silver | 1         | 1.39%   |
| Intel Pentium        | 1         | 1.39%   |
| AMD A4               | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 26        | 36.11%  |
| 2      | 25        | 34.72%  |
| 8      | 10        | 13.89%  |
| 6      | 7         | 9.72%   |
| 12     | 2         | 2.78%   |
| 28     | 1         | 1.39%   |
| 10     | 1         | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 72.22%  |
| 1      | 20        | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 72        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 50%     |
| 0x706a8    | 3         | 4.17%   |
| 0xa0652    | 2         | 2.78%   |
| 0x806d1    | 2         | 2.78%   |
| 0x506e3    | 2         | 2.78%   |
| 0x206a7    | 2         | 2.78%   |
| 0x906e9    | 1         | 1.39%   |
| 0x806ec    | 1         | 1.39%   |
| 0x806ea    | 1         | 1.39%   |
| 0x806c1    | 1         | 1.39%   |
| 0x6fd      | 1         | 1.39%   |
| 0x506c9    | 1         | 1.39%   |
| 0x50654    | 1         | 1.39%   |
| 0x406c4    | 1         | 1.39%   |
| 0x40651    | 1         | 1.39%   |
| 0x306d4    | 1         | 1.39%   |
| 0x306c3    | 1         | 1.39%   |
| 0x306a9    | 1         | 1.39%   |
| 0x0a601203 | 1         | 1.39%   |
| 0x0a50000c | 1         | 1.39%   |
| 0x0a404102 | 1         | 1.39%   |
| 0x0a201016 | 1         | 1.39%   |
| 0x0a201009 | 1         | 1.39%   |
| 0x08701030 | 1         | 1.39%   |
| 0x08701021 | 1         | 1.39%   |
| 0x08608104 | 1         | 1.39%   |
| 0x08600106 | 1         | 1.39%   |
| 0x08600104 | 1         | 1.39%   |
| 0x08108102 | 1         | 1.39%   |
| 0x06003106 | 1         | 1.39%   |
| 0x03000027 | 1         | 1.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 13.89%  |
| Zen 2            | 6         | 8.33%   |
| Zen 3            | 5         | 6.94%   |
| IceLake          | 5         | 6.94%   |
| TigerLake        | 4         | 5.56%   |
| Silvermont       | 4         | 5.56%   |
| SandyBridge      | 4         | 5.56%   |
| Haswell          | 4         | 5.56%   |
| Goldmont plus    | 4         | 5.56%   |
| Skylake          | 3         | 4.17%   |
| Broadwell        | 3         | 4.17%   |
| Unknown          | 3         | 4.17%   |
| Zen+             | 2         | 2.78%   |
| Westmere         | 2         | 2.78%   |
| Steamroller      | 2         | 2.78%   |
| IvyBridge        | 2         | 2.78%   |
| Core             | 2         | 2.78%   |
| CometLake        | 2         | 2.78%   |
| Tremont          | 1         | 1.39%   |
| Penryn           | 1         | 1.39%   |
| K10 Llano        | 1         | 1.39%   |
| Goldmont         | 1         | 1.39%   |
| Alderlake Hybrid | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 53.93%  |
| AMD    | 23        | 25.84%  |
| Nvidia | 18        | 20.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 4.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.16%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.16%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 3.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 3.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.11%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 2.11%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 2.11%   |
| Intel HD Graphics 630                                                                    | 2         | 2.11%   |
| Intel HD Graphics 530                                                                    | 2         | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.11%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.11%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 2.11%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 2.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 2.11%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.05%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 1.05%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1         | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.05%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.05%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.05%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.05%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.05%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.05%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.05%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.05%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 44.44%  |
| 1 x AMD        | 13        | 18.06%  |
| Intel + Nvidia | 11        | 15.28%  |
| 2 x AMD        | 5         | 6.94%   |
| 1 x Nvidia     | 5         | 6.94%   |
| Intel + AMD    | 3         | 4.17%   |
| AMD + Nvidia   | 2         | 2.78%   |
| 2 x Intel      | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 76.71%  |
| Proprietary | 16        | 21.92%  |
| Unknown     | 1         | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 64.38%  |
| 0.01-0.5   | 7         | 9.59%   |
| 7.01-8.0   | 6         | 8.22%   |
| 1.01-2.0   | 3         | 4.11%   |
| 5.01-6.0   | 2         | 2.74%   |
| 3.01-4.0   | 2         | 2.74%   |
| 16.01-24.0 | 2         | 2.74%   |
| 8.01-16.0  | 2         | 2.74%   |
| 0.51-1.0   | 2         | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 10        | 12.82%  |
| BOE                  | 10        | 12.82%  |
| AU Optronics         | 9         | 11.54%  |
| Samsung Electronics  | 7         | 8.97%   |
| LG Display           | 6         | 7.69%   |
| Dell                 | 5         | 6.41%   |
| Goldstar             | 4         | 5.13%   |
| Sharp                | 3         | 3.85%   |
| PANDA                | 3         | 3.85%   |
| Ancor Communications | 3         | 3.85%   |
| Lenovo               | 2         | 2.56%   |
| ASUSTek Computer     | 2         | 2.56%   |
| Apple                | 2         | 2.56%   |
| Acer                 | 2         | 2.56%   |
| Toshiba              | 1         | 1.28%   |
| Roku                 | 1         | 1.28%   |
| Mi                   | 1         | 1.28%   |
| JPN                  | 1         | 1.28%   |
| InfoVision           | 1         | 1.28%   |
| HJC                  | 1         | 1.28%   |
| Hewlett-Packard      | 1         | 1.28%   |
| BenQ                 | 1         | 1.28%   |
| AGO                  | 1         | 1.28%   |
| Unknown              | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 2         | 2.47%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 2.47%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 2.47%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 2.47%   |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 1.23%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| Sharp LCD Monitor SHP14F8 3840x2400 288x180mm 13.4-inch               | 1         | 1.23%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.23%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC416C 1920x1080 344x194mm 15.5-inch | 1         | 1.23%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.23%   |
| Roku TV RKU8518 1920x1080 698x392mm 31.5-inch                         | 1         | 1.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.23%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                      | 1         | 1.23%   |
| LG Display LCD Monitor LGD04B9 1920x1080 340x190mm 15.3-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 1.23%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1         | 1.23%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch               | 1         | 1.23%   |
| JPN IPS245FHDR165 JPN2500 1920x1080 552x314mm 25.0-inch               | 1         | 1.23%   |
| InfoVision LCD Monitor IVO34D1 1920x1280 285x190mm 13.5-inch          | 1         | 1.23%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                 | 1         | 1.23%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1         | 1.23%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1         | 1.23%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch               | 1         | 1.23%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch               | 1         | 1.23%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 1         | 1.23%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 1         | 1.23%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                   | 1         | 1.23%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                    | 1         | 1.23%   |
| Dell S2240T DELA094 1920x1080 477x268mm 21.5-inch                     | 1         | 1.23%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                     | 1         | 1.23%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                   | 1         | 1.23%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 35        | 46.05%  |
| 1366x768 (WXGA)  | 16        | 21.05%  |
| 2560x1440 (QHD)  | 4         | 5.26%   |
| 3840x2160 (4K)   | 3         | 3.95%   |
| 3440x1440        | 2         | 2.63%   |
| 2560x1080        | 2         | 2.63%   |
| 2256x1504        | 2         | 2.63%   |
| 1440x900 (WXGA+) | 2         | 2.63%   |
| 3840x2400        | 1         | 1.32%   |
| 3840x1080        | 1         | 1.32%   |
| 3200x1080        | 1         | 1.32%   |
| 2240x1400        | 1         | 1.32%   |
| 2160x1440        | 1         | 1.32%   |
| 1920x1280        | 1         | 1.32%   |
| 1600x900 (HD+)   | 1         | 1.32%   |
| 1280x800 (WXGA)  | 1         | 1.32%   |
| 1280x1024 (SXGA) | 1         | 1.32%   |
| Unknown          | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 30%     |
| 13      | 11        | 13.75%  |
| 14      | 9         | 11.25%  |
| 24      | 7         | 8.75%   |
| 34      | 4         | 5%      |
| 23      | 3         | 3.75%   |
| 21      | 3         | 3.75%   |
| 12      | 3         | 3.75%   |
| 31      | 2         | 2.5%    |
| 27      | 2         | 2.5%    |
| 19      | 2         | 2.5%    |
| 11      | 2         | 2.5%    |
| 74      | 1         | 1.25%   |
| 64      | 1         | 1.25%   |
| 48      | 1         | 1.25%   |
| 32      | 1         | 1.25%   |
| 25      | 1         | 1.25%   |
| 17      | 1         | 1.25%   |
| 16      | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 46.15%  |
| 201-300     | 13        | 16.67%  |
| 501-600     | 11        | 14.1%   |
| 701-800     | 5         | 6.41%   |
| 401-500     | 5         | 6.41%   |
| 601-700     | 3         | 3.85%   |
| 1001-1500   | 2         | 2.56%   |
| 351-400     | 1         | 1.28%   |
| 1501-2000   | 1         | 1.28%   |
| Unknown     | 1         | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 75.34%  |
| 16/10   | 6         | 8.22%   |
| 3/2     | 4         | 5.48%   |
| 21/9    | 4         | 5.48%   |
| 5/4     | 1         | 1.37%   |
| 4/3     | 1         | 1.37%   |
| 32/9    | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 32.91%  |
| 81-90          | 16        | 20.25%  |
| 201-250        | 9         | 11.39%  |
| 351-500        | 7         | 8.86%   |
| 71-80          | 4         | 5.06%   |
| 251-300        | 3         | 3.8%    |
| 151-200        | 3         | 3.8%    |
| More than 1000 | 2         | 2.53%   |
| 61-70          | 2         | 2.53%   |
| 51-60          | 2         | 2.53%   |
| 301-350        | 2         | 2.53%   |
| 141-150        | 1         | 1.27%   |
| 501-1000       | 1         | 1.27%   |
| Unknown        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 35.9%   |
| 51-100        | 19        | 24.36%  |
| 101-120       | 18        | 23.08%  |
| 161-240       | 9         | 11.54%  |
| More than 240 | 2         | 2.56%   |
| 1-50          | 1         | 1.28%   |
| Unknown       | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 81.94%  |
| 2     | 12        | 16.67%  |
| 3     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 42.16%  |
| Intel                    | 32        | 31.37%  |
| MediaTek                 | 6         | 5.88%   |
| Qualcomm Atheros         | 5         | 4.9%    |
| Ralink Technology        | 4         | 3.92%   |
| Broadcom                 | 4         | 3.92%   |
| Broadcom Limited         | 2         | 1.96%   |
| TP-Link                  | 1         | 0.98%   |
| OPPO Electronics         | 1         | 0.98%   |
| Marvell Technology Group | 1         | 0.98%   |
| DisplayLink              | 1         | 0.98%   |
| ASIX Electronics         | 1         | 0.98%   |
| Aquantia                 | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 23        | 18.85%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 4.1%    |
| Realtek 802.11ac NIC                                                   | 3         | 2.46%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 2.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 2.46%   |
| Intel Wireless 8265 / 8275                                             | 3         | 2.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.64%   |
| Intel Wireless 7265                                                    | 2         | 1.64%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.64%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.82%   |
| Ralink RT5572 Wireless Adapter                                         | 1         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.82%   |
| OPPO CPH2591                                                           | 1         | 0.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 0.82%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 42.86%  |
| Realtek Semiconductor | 17        | 26.98%  |
| MediaTek              | 6         | 9.52%   |
| Qualcomm Atheros      | 5         | 7.94%   |
| Ralink Technology     | 4         | 6.35%   |
| Broadcom              | 3         | 4.76%   |
| TP-Link               | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 7.69%   |
| Realtek 802.11ac NIC                                          | 3         | 4.62%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 4.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 4.62%   |
| Intel Wireless 8265 / 8275                                    | 3         | 4.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 4.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 3.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 3.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2         | 3.08%   |
| Intel Wireless 7265                                           | 2         | 3.08%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 3.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 2         | 3.08%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 2         | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 3.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 3.08%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 1.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1         | 1.54%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.54%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 1         | 1.54%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 1.54%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.54%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 1.54%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 1.54%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 62.96%  |
| Intel                    | 11        | 20.37%  |
| Broadcom Limited         | 2         | 3.7%    |
| Broadcom                 | 2         | 3.7%    |
| OPPO Electronics         | 1         | 1.85%   |
| Marvell Technology Group | 1         | 1.85%   |
| DisplayLink              | 1         | 1.85%   |
| ASIX Electronics         | 1         | 1.85%   |
| Aquantia                 | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 23        | 40.35%  |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 10.53%  |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 3.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 3.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.75%   |
| OPPO CPH2591                                                                   | 1         | 1.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.75%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.75%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.75%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.75%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 1.75%   |
| DisplayLink USB3 to HDMI                                                       | 1         | 1.75%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.75%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express                  | 1         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.75%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 54.05%  |
| Ethernet | 51        | 45.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 70.83%  |
| Ethernet | 21        | 29.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 50%     |
| 1     | 32        | 44.44%  |
| 0     | 3         | 4.17%   |
| 3     | 1         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 63.89%  |
| Yes  | 26        | 36.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 48%     |
| Realtek Semiconductor           | 8         | 16%     |
| IMC Networks                    | 4         | 8%      |
| Qualcomm Atheros Communications | 3         | 6%      |
| MediaTek                        | 2         | 4%      |
| Foxconn / Hon Hai               | 2         | 4%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Apple                           | 2         | 4%      |
| Realtek                         | 1         | 2%      |
| Lite-On Technology              | 1         | 2%      |
| Broadcom                        | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 18%     |
| Realtek Bluetooth Radio                             | 5         | 10%     |
| Intel Bluetooth Device                              | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4%      |
| MediaTek Wireless_Device                            | 2         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4%      |
| Intel Bluetooth wireless interface                  | 2         | 4%      |
| IMC Networks Wireless_Device                        | 2         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4%      |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2%      |
| Realtek Bluetooth Radio                             | 1         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2%      |
| Intel AX211 Bluetooth                               | 1         | 2%      |
| Intel AX210 Bluetooth                               | 1         | 2%      |
| Intel AX200 Bluetooth                               | 1         | 2%      |
| IMC Networks Bluetooth Radio                        | 1         | 2%      |
| IMC Networks Bluetooth Device                       | 1         | 2%      |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2%      |
| Apple Bluetooth HCI                                 | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 50        | 51.55%  |
| AMD                                          | 23        | 23.71%  |
| Nvidia                                       | 12        | 12.37%  |
| Logitech                                     | 3         | 3.09%   |
| C-Media Electronics                          | 2         | 2.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.03%   |
| Texas Instruments                            | 1         | 1.03%   |
| Oculus VR                                    | 1         | 1.03%   |
| Kingston Technology                          | 1         | 1.03%   |
| JMTek                                        | 1         | 1.03%   |
| DCMT Technology                              | 1         | 1.03%   |
| Blue Microphones                             | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 8.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 5.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 4.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 3.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.46%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 2.46%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.64%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.64%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2         | 1.64%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 0.82%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.82%   |
| Oculus VR Rift CV1 Audio                                                   | 1         | 0.82%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.82%   |
| Nvidia Audio device                                                        | 1         | 0.82%   |
| Logitech Logitech USB Microphone                                           | 1         | 0.82%   |
| Logitech H390 headset with microphone                                      | 1         | 0.82%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.82%   |
| Kingston Technology HyperX QuadCast                                        | 1         | 0.82%   |
| JMTek USB PnP Audio Device                                                 | 1         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 18.06%  |
| Kingston            | 13        | 18.06%  |
| Micron Technology   | 12        | 16.67%  |
| SK hynix            | 10        | 13.89%  |
| Crucial             | 6         | 8.33%   |
| Unknown             | 5         | 6.94%   |
| Unknown (ABCD)      | 2         | 2.78%   |
| Corsair             | 2         | 2.78%   |
| A-DATA Technology   | 2         | 2.78%   |
| Teclast             | 1         | 1.39%   |
| Team                | 1         | 1.39%   |
| Ramaxel Technology  | 1         | 1.39%   |
| Nanya Technology    | 1         | 1.39%   |
| G.Skill             | 1         | 1.39%   |
| ChangXin Memory     | 1         | 1.39%   |
| Unknown             | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.6%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 2.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.6%    |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 2.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.3%    |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.3%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.3%    |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 1.3%    |
| Teclast RAM YTD48G26N10 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.3%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 1.3%    |
| SK hynix RAM Module 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.3%    |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 1.3%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 1.3%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.3%    |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.3%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.3%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.3%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 1.3%    |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.3%    |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s          | 1         | 1.3%    |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 1.3%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.3%    |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.3%    |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s                 | 1         | 1.3%    |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 51.56%  |
| DDR3   | 19        | 29.69%  |
| LPDDR4 | 6         | 9.38%   |
| DDR5   | 2         | 3.13%   |
| DDR2   | 2         | 3.13%   |
| SDRAM  | 1         | 1.56%   |
| LPDDR5 | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 61.9%   |
| DIMM         | 16        | 25.4%   |
| Row Of Chips | 8         | 12.7%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 42.86%  |
| 4096  | 15        | 21.43%  |
| 2048  | 9         | 12.86%  |
| 16384 | 8         | 11.43%  |
| 32768 | 4         | 5.71%   |
| 1024  | 4         | 5.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 13        | 18.57%  |
| 1600    | 13        | 18.57%  |
| 3200    | 11        | 15.71%  |
| 1333    | 5         | 7.14%   |
| 2400    | 4         | 5.71%   |
| 2133    | 3         | 4.29%   |
| 4800    | 2         | 2.86%   |
| 4267    | 2         | 2.86%   |
| 3800    | 2         | 2.86%   |
| 3733    | 2         | 2.86%   |
| 2933    | 2         | 2.86%   |
| 1334    | 2         | 2.86%   |
| 49926   | 1         | 1.43%   |
| 6400    | 1         | 1.43%   |
| 3600    | 1         | 1.43%   |
| 3333    | 1         | 1.43%   |
| 1866    | 1         | 1.43%   |
| 1067    | 1         | 1.43%   |
| 800     | 1         | 1.43%   |
| 667     | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 4720 series | 1         | 100%    |

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
| Chicony Electronics                    | 10        | 22.22%  |
| Microdia                               | 5         | 11.11%  |
| Quanta                                 | 3         | 6.67%   |
| IMC Networks                           | 3         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.67%   |
| Suyin                                  | 2         | 4.44%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| Samsung Electronics                    | 2         | 4.44%   |
| Realtek Semiconductor                  | 2         | 4.44%   |
| Luxvisions Innotech Limited            | 2         | 4.44%   |
| Bison Electronics                      | 2         | 4.44%   |
| Apple                                  | 2         | 4.44%   |
| Alcor Micro                            | 2         | 4.44%   |
| Ricoh                                  | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Generalplus Technology                 | 1         | 2.22%   |
| ARC International                      | 1         | 2.22%   |
| Acer                                   | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                    | 4         | 8.89%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)      | 2         | 4.44%   |
| Sunplus Integrated_Webcam_HD                                     | 2         | 4.44%   |
| Samsung Galaxy series, misc. (MTP mode)                          | 2         | 4.44%   |
| Quanta ov9734_techfront_camera                                   | 2         | 4.44%   |
| Chicony Integrated IR Camera                                     | 2         | 4.44%   |
| Chicony HP Truevision HD                                         | 2         | 4.44%   |
| Chicony HD WebCam                                                | 2         | 4.44%   |
| Bison HD Webcam                                                  | 2         | 4.44%   |
| Ricoh Laptop_Integrated_Webcam_FHD                               | 1         | 2.22%   |
| Realtek HP Webcam                                                | 1         | 2.22%   |
| Realtek HD Webcam - Realtek                                      | 1         | 2.22%   |
| Quanta HP TrueVision HD Camera                                   | 1         | 2.22%   |
| Microdia Webcam Vitade AF                                        | 1         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera                    | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera              | 1         | 2.22%   |
| Logitech HD Pro Webcam C920                                      | 1         | 2.22%   |
| IMC Networks Integrated Camera                                   | 1         | 2.22%   |
| IMC Networks HP TrueVision HD Camera                             | 1         | 2.22%   |
| IMC Networks HD Camera                                           | 1         | 2.22%   |
| Generalplus GENERAL WEBCAM                                       | 1         | 2.22%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 1         | 2.22%   |
| Chicony HP Wide Vision HD Camera                                 | 1         | 2.22%   |
| Chicony HP True Vision 5MP Camera                                | 1         | 2.22%   |
| Chicony HD User Facing                                           | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera  | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera   | 1         | 2.22%   |
| ARC International Camera                                         | 1         | 2.22%   |
| Apple FaceTime Camera                                            | 1         | 2.22%   |
| Apple Built-in iSight [Micron]                                   | 1         | 2.22%   |
| Alcor Micro USB 2.0 PC cam                                       | 1         | 2.22%   |
| Alcor Micro USB 2.0 Camera                                       | 1         | 2.22%   |
| Acer Integrated Camera                                           | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 50%     |
| Elan Microelectronics      | 2         | 33.33%  |
| LighTuning Technology      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader          | 2         | 33.33%  |
| Elan ELAN:ARM-M4                            | 2         | 33.33%  |
| Shenzhen Goodix  Fingerprint Device         | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 2         | 66.67%  |
| Aladdin Knowledge Systems | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Broadcom 5880                                  | 1         | 33.33%  |
| Aladdin Knowledge Systems Token JC             | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 56        | 77.78%  |
| 1     | 13        | 18.06%  |
| 2     | 3         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 33.33%  |
| Graphics card         | 3         | 16.67%  |
| Storage               | 2         | 11.11%  |
| Net/wireless          | 2         | 11.11%  |
| Multimedia controller | 2         | 11.11%  |
| Chipcard              | 2         | 11.11%  |
| Unassigned class      | 1         | 5.56%   |

