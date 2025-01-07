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

Total: 109

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [6d2e60df3c](https://linux-hardware.org/?probe=6d2e60df3c) | Nov 12, 2024 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [ce62db7f6c](https://linux-hardware.org/?probe=ce62db7f6c) | Nov 09, 2024 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [1294da7ab3](https://linux-hardware.org/?probe=1294da7ab3) | Oct 21, 2024 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [738be8fc77](https://linux-hardware.org/?probe=738be8fc77) | Oct 14, 2024 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [d946696cbf](https://linux-hardware.org/?probe=d946696cbf) | Oct 07, 2024 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [e49fade822](https://linux-hardware.org/?probe=e49fade822) | Sep 29, 2024 |
| Intel         | powered classmate PC        | Tablet      | [0545cc60de](https://linux-hardware.org/?probe=0545cc60de) | Sep 06, 2024 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [c1be4d981d](https://linux-hardware.org/?probe=c1be4d981d) | Aug 24, 2024 |
| Google        | Blorb                       | Notebook    | [e78979a7d6](https://linux-hardware.org/?probe=e78979a7d6) | Aug 09, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [290969f6d7](https://linux-hardware.org/?probe=290969f6d7) | Aug 07, 2024 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [a9c3d19fed](https://linux-hardware.org/?probe=a9c3d19fed) | Jul 15, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [b97d8e4203](https://linux-hardware.org/?probe=b97d8e4203) | Jun 23, 2024 |
| MSI           | Thin GF63 12UDX             | Notebook    | [8baf5df767](https://linux-hardware.org/?probe=8baf5df767) | May 21, 2024 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [479cc864f1](https://linux-hardware.org/?probe=479cc864f1) | May 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [86c5400c85](https://linux-hardware.org/?probe=86c5400c85) | May 13, 2024 |
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
| Archcraft Rolling | 68        | 80.95%  |
| Archcraft         | 16        | 19.05%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Archcraft | 84        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.18.16-arch1-1    | 4         | 4.44%   |
| 6.3.9-arch1-1      | 3         | 3.33%   |
| 5.19.13-arch1-1    | 3         | 3.33%   |
| 6.9.9-arch1-1      | 2         | 2.22%   |
| 6.9.1-arch1-1      | 2         | 2.22%   |
| 6.8.7-arch1-2      | 2         | 2.22%   |
| 6.6.10-arch1-1     | 2         | 2.22%   |
| 6.4.4-zen1-1-zen   | 2         | 2.22%   |
| 6.4.1-arch2-1      | 2         | 2.22%   |
| 6.2.13-arch1-1     | 2         | 2.22%   |
| 5.12.7-arch1-1     | 2         | 2.22%   |
| 6.9.7-arch1-1      | 1         | 1.11%   |
| 6.8.9-zen1-2-zen   | 1         | 1.11%   |
| 6.8.9-arch1-1      | 1         | 1.11%   |
| 6.8.4-zen1-1-zen   | 1         | 1.11%   |
| 6.8.4-arch1-1      | 1         | 1.11%   |
| 6.7.5-arch1-1      | 1         | 1.11%   |
| 6.7.1-arch1-1      | 1         | 1.11%   |
| 6.6.8-arch1-1      | 1         | 1.11%   |
| 6.6.7-arch1-1      | 1         | 1.11%   |
| 6.6.6-arch1-1      | 1         | 1.11%   |
| 6.6.4-arch1-1      | 1         | 1.11%   |
| 6.6.1-arch1-1      | 1         | 1.11%   |
| 6.5.5-zen1-1-zen   | 1         | 1.11%   |
| 6.5.4-arch2-1      | 1         | 1.11%   |
| 6.4.7-arch1-1      | 1         | 1.11%   |
| 6.4.4-arch1-1      | 1         | 1.11%   |
| 6.4.3-arch1-1      | 1         | 1.11%   |
| 6.4.12-arch1-1     | 1         | 1.11%   |
| 6.4.10-zen2-1-zen  | 1         | 1.11%   |
| 6.4.10-arch1-1     | 1         | 1.11%   |
| 6.3.8-arch1-1      | 1         | 1.11%   |
| 6.3.7-arch1-1-vfio | 1         | 1.11%   |
| 6.3.6-arch1-1      | 1         | 1.11%   |
| 6.3.4-arch1-1      | 1         | 1.11%   |
| 6.3.10-1-clear     | 1         | 1.11%   |
| 6.2.8-zen1-1-zen   | 1         | 1.11%   |
| 6.2.2-arch1-1      | 1         | 1.11%   |
| 6.2.12-arch1-1     | 1         | 1.11%   |
| 6.11.2-arch1-1     | 1         | 1.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.16 | 4         | 4.44%   |
| 6.4.4   | 3         | 3.33%   |
| 6.3.9   | 3         | 3.33%   |
| 5.19.13 | 3         | 3.33%   |
| 6.9.9   | 2         | 2.22%   |
| 6.9.1   | 2         | 2.22%   |
| 6.8.9   | 2         | 2.22%   |
| 6.8.7   | 2         | 2.22%   |
| 6.8.4   | 2         | 2.22%   |
| 6.6.10  | 2         | 2.22%   |
| 6.4.10  | 2         | 2.22%   |
| 6.4.1   | 2         | 2.22%   |
| 6.2.13  | 2         | 2.22%   |
| 5.12.7  | 2         | 2.22%   |
| 6.9.7   | 1         | 1.11%   |
| 6.7.5   | 1         | 1.11%   |
| 6.7.1   | 1         | 1.11%   |
| 6.6.8   | 1         | 1.11%   |
| 6.6.7   | 1         | 1.11%   |
| 6.6.6   | 1         | 1.11%   |
| 6.6.4   | 1         | 1.11%   |
| 6.6.1   | 1         | 1.11%   |
| 6.5.5   | 1         | 1.11%   |
| 6.5.4   | 1         | 1.11%   |
| 6.4.7   | 1         | 1.11%   |
| 6.4.3   | 1         | 1.11%   |
| 6.4.12  | 1         | 1.11%   |
| 6.3.8   | 1         | 1.11%   |
| 6.3.7   | 1         | 1.11%   |
| 6.3.6   | 1         | 1.11%   |
| 6.3.4   | 1         | 1.11%   |
| 6.3.10  | 1         | 1.11%   |
| 6.2.8   | 1         | 1.11%   |
| 6.2.2   | 1         | 1.11%   |
| 6.2.12  | 1         | 1.11%   |
| 6.11.2  | 1         | 1.11%   |
| 6.11.1  | 1         | 1.11%   |
| 6.10.8  | 1         | 1.11%   |
| 6.10.5  | 1         | 1.11%   |
| 6.10.10 | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 9         | 10.23%  |
| 6.3     | 8         | 9.09%   |
| 5.18    | 8         | 9.09%   |
| 6.6     | 7         | 7.95%   |
| 5.19    | 7         | 7.95%   |
| 6.8     | 6         | 6.82%   |
| 6.9     | 5         | 5.68%   |
| 6.2     | 5         | 5.68%   |
| 6.1     | 4         | 4.55%   |
| 6.0     | 4         | 4.55%   |
| 5.16    | 4         | 4.55%   |
| 5.12    | 4         | 4.55%   |
| 6.10    | 3         | 3.41%   |
| 5.17    | 3         | 3.41%   |
| 6.7     | 2         | 2.27%   |
| 6.5     | 2         | 2.27%   |
| 6.11    | 2         | 2.27%   |
| 5.15    | 2         | 2.27%   |
| 5.14    | 2         | 2.27%   |
| 5.10    | 1         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Openbox  | 27        | 31.76%  |
| XFCE     | 23        | 27.06%  |
| bspwm    | 9         | 10.59%  |
| sway     | 3         | 3.53%   |
| KDE5     | 3         | 3.53%   |
| i3       | 3         | 3.53%   |
| GNOME    | 3         | 3.53%   |
| Unknown  | 3         | 3.53%   |
| KDE6     | 2         | 2.35%   |
| Hyprland | 2         | 2.35%   |
| dwm      | 2         | 2.35%   |
| xmonad   | 1         | 1.18%   |
| qtile    | 1         | 1.18%   |
| LXDE     | 1         | 1.18%   |
| Budgie   | 1         | 1.18%   |
| awesome  | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 74        | 87.06%  |
| Wayland | 9         | 10.59%  |
| Unknown | 2         | 2.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 58        | 68.24%  |
| Unknown | 17        | 20%     |
| LXDM    | 5         | 5.88%   |
| LightDM | 4         | 4.71%   |
| Ly      | 1         | 1.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 47        | 55.95%  |
| es_MX   | 6         | 7.14%   |
| en_IN   | 6         | 7.14%   |
| es_ES   | 5         | 5.95%   |
| en_GB   | 5         | 5.95%   |
| fr_FR   | 2         | 2.38%   |
| en_ZA   | 2         | 2.38%   |
| en_SG   | 2         | 2.38%   |
| tr_TR   | 1         | 1.19%   |
| pt_BR   | 1         | 1.19%   |
| pl_PL   | 1         | 1.19%   |
| it_IT   | 1         | 1.19%   |
| es_VE   | 1         | 1.19%   |
| en_PH   | 1         | 1.19%   |
| de_DE   | 1         | 1.19%   |
| de_AT   | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 60        | 71.43%  |
| BIOS | 24        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 62        | 73.81%  |
| Btrfs | 17        | 20.24%  |
| Xfs   | 4         | 4.76%   |
| Tmpfs | 1         | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 64        | 76.19%  |
| Unknown | 14        | 16.67%  |
| MBR     | 6         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 79.76%  |
| Yes       | 17        | 20.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 64.71%  |
| Yes       | 30        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 15        | 17.86%  |
| ASUSTek Computer               | 12        | 14.29%  |
| Dell                           | 11        | 13.1%   |
| MSI                            | 8         | 9.52%   |
| Lenovo                         | 8         | 9.52%   |
| Gigabyte Technology            | 4         | 4.76%   |
| HUAWEI                         | 3         | 3.57%   |
| ASRock                         | 3         | 3.57%   |
| Intel                          | 2         | 2.38%   |
| Google                         | 2         | 2.38%   |
| Apple                          | 2         | 2.38%   |
| Acer                           | 2         | 2.38%   |
| Standard                       | 1         | 1.19%   |
| SmbiosType1_SystemManufacturer | 1         | 1.19%   |
| Positivo                       | 1         | 1.19%   |
| Packard Bell                   | 1         | 1.19%   |
| MouseComputer                  | 1         | 1.19%   |
| Medion                         | 1         | 1.19%   |
| Infinix                        | 1         | 1.19%   |
| Framework                      | 1         | 1.19%   |
| eMachines                      | 1         | 1.19%   |
| ECS                            | 1         | 1.19%   |
| Chuwi                          | 1         | 1.19%   |
| AXDIA International            | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SmbiosType1_SystemManufacturer N20      | 1         | 1.19%   |
| Positivo CHT14B                         | 1         | 1.19%   |
| Packard Bell EasyNote TK85              | 1         | 1.19%   |
| MSI Thin GF63 12UDX                     | 1         | 1.19%   |
| MSI MS-7C91                             | 1         | 1.19%   |
| MSI MS-7C51                             | 1         | 1.19%   |
| MSI MS-7B93                             | 1         | 1.19%   |
| MSI Katana GF66 11UE                    | 1         | 1.19%   |
| MSI GL65 Leopard 10SFK                  | 1         | 1.19%   |
| MSI GF63 Thin 10SC                      | 1         | 1.19%   |
| MSI Alpha 15 B5EEK                      | 1         | 1.19%   |
| MouseComputer EGPN711R307               | 1         | 1.19%   |
| Medion E3223                            | 1         | 1.19%   |
| Lenovo ThinkPad X280 20KFCTO1WW         | 1         | 1.19%   |
| Lenovo ThinkPad T430 2351AK9            | 1         | 1.19%   |
| Lenovo ThinkCentre M710q 10MR0047US     | 1         | 1.19%   |
| Lenovo ThinkCentre Edge72 3484HPU       | 1         | 1.19%   |
| Lenovo MIIX 310-10ICR 80SG              | 1         | 1.19%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9        | 1         | 1.19%   |
| Lenovo IdeaPad 3 15IGL05 81WQ           | 1         | 1.19%   |
| Lenovo IdeaCentre 510A-15ARR 90J00061US | 1         | 1.19%   |
| Intel powered classmate PC              | 1         | 1.19%   |
| Intel NUC11BTMi7                        | 1         | 1.19%   |
| Infinix INBook X1 Pro                   | 1         | 1.19%   |
| HUAWEI NBD-WXX9                         | 1         | 1.19%   |
| HUAWEI HLYL-WXX9                        | 1         | 1.19%   |
| HUAWEI BOHB-WAX9                        | 1         | 1.19%   |
| HP Stream Laptop 11-ak0xxx              | 1         | 1.19%   |
| HP Spectre x360 Convertible 15-ch0xx    | 1         | 1.19%   |
| HP Pavilion Notebook                    | 1         | 1.19%   |
| HP Pavilion Laptop 15-eh0xxx            | 1         | 1.19%   |
| HP Pavilion Laptop 15-cc1xx             | 1         | 1.19%   |
| HP Pavilion g4                          | 1         | 1.19%   |
| HP Notebook                             | 1         | 1.19%   |
| HP Laptop 15q-bu1xx                     | 1         | 1.19%   |
| HP Laptop 15-dy2xxx                     | 1         | 1.19%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.19%   |
| HP Laptop 15-da0xxx                     | 1         | 1.19%   |
| HP InsydeH2O EFI BIOS                   | 1         | 1.19%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx    | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Dell Latitude                      | 5         | 5.95%   |
| HP Pavilion                        | 4         | 4.76%   |
| HP Laptop                          | 4         | 4.76%   |
| ASUS TUF                           | 3         | 3.57%   |
| ASUS ROG                           | 3         | 3.57%   |
| Lenovo ThinkPad                    | 2         | 2.38%   |
| Lenovo ThinkCentre                 | 2         | 2.38%   |
| Dell Vostro                        | 2         | 2.38%   |
| Dell Inspiron                      | 2         | 2.38%   |
| SmbiosType1_SystemManufacturer N20 | 1         | 1.19%   |
| Positivo CHT14B                    | 1         | 1.19%   |
| Packard Bell EasyNote              | 1         | 1.19%   |
| MSI Thin                           | 1         | 1.19%   |
| MSI MS-7C91                        | 1         | 1.19%   |
| MSI MS-7C51                        | 1         | 1.19%   |
| MSI MS-7B93                        | 1         | 1.19%   |
| MSI Katana                         | 1         | 1.19%   |
| MSI GL65                           | 1         | 1.19%   |
| MSI GF63                           | 1         | 1.19%   |
| MSI Alpha                          | 1         | 1.19%   |
| MouseComputer EGPN711R307          | 1         | 1.19%   |
| Medion E3223                       | 1         | 1.19%   |
| Lenovo MIIX                        | 1         | 1.19%   |
| Lenovo IdeaPadFlex                 | 1         | 1.19%   |
| Lenovo IdeaPad                     | 1         | 1.19%   |
| Lenovo IdeaCentre                  | 1         | 1.19%   |
| Intel powered                      | 1         | 1.19%   |
| Intel NUC11BTMi7                   | 1         | 1.19%   |
| Infinix INBook                     | 1         | 1.19%   |
| HUAWEI NBD-WXX9                    | 1         | 1.19%   |
| HUAWEI HLYL-WXX9                   | 1         | 1.19%   |
| HUAWEI BOHB-WAX9                   | 1         | 1.19%   |
| HP Stream                          | 1         | 1.19%   |
| HP Spectre                         | 1         | 1.19%   |
| HP Notebook                        | 1         | 1.19%   |
| HP InsydeH2O                       | 1         | 1.19%   |
| HP ENVY                            | 1         | 1.19%   |
| HP EliteDesk                       | 1         | 1.19%   |
| HP Dragonfly                       | 1         | 1.19%   |
| Google Kindred                     | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 14        | 16.67%  |
| 2020 | 10        | 11.9%   |
| 2018 | 8         | 9.52%   |
| 2019 | 7         | 8.33%   |
| 2022 | 6         | 7.14%   |
| 2017 | 5         | 5.95%   |
| 2015 | 5         | 5.95%   |
| 2014 | 5         | 5.95%   |
| 2023 | 4         | 4.76%   |
| 2016 | 4         | 4.76%   |
| 2012 | 4         | 4.76%   |
| 2011 | 4         | 4.76%   |
| 2013 | 2         | 2.38%   |
| 2010 | 2         | 2.38%   |
| 2007 | 2         | 2.38%   |
| 2024 | 1         | 1.19%   |
| 2008 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 52        | 61.9%   |
| Desktop     | 24        | 28.57%  |
| Convertible | 5         | 5.95%   |
| Tablet      | 2         | 2.38%   |
| Mini pc     | 1         | 1.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 83        | 98.81%  |
| Enabled  | 1         | 1.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 97.62%  |
| Yes  | 2         | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 23.81%  |
| 32.01-64.0  | 14        | 16.67%  |
| 16.01-24.0  | 14        | 16.67%  |
| 8.01-16.0   | 13        | 15.48%  |
| 3.01-4.0    | 12        | 14.29%  |
| 1.01-2.0    | 5         | 5.95%   |
| 64.01-256.0 | 4         | 4.76%   |
| 24.01-32.0  | 1         | 1.19%   |
| 2.01-3.0    | 1         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 23        | 26.44%  |
| 1.01-2.0  | 22        | 25.29%  |
| 4.01-8.0  | 18        | 20.69%  |
| 3.01-4.0  | 13        | 14.94%  |
| 0.51-1.0  | 7         | 8.05%   |
| 8.01-16.0 | 4         | 4.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 54.76%  |
| 2      | 22        | 26.19%  |
| 3      | 7         | 8.33%   |
| 4      | 4         | 4.76%   |
| 5      | 2         | 2.38%   |
| 8      | 1         | 1.19%   |
| 7      | 1         | 1.19%   |
| 6      | 1         | 1.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 84.52%  |
| Yes       | 13        | 15.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 75%     |
| No        | 21        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 82.35%  |
| No        | 15        | 17.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 75%     |
| No        | 21        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 18        | 21.43%  |
| India              | 8         | 9.52%   |
| Mexico             | 6         | 7.14%   |
| Brazil             | 6         | 7.14%   |
| Spain              | 5         | 5.95%   |
| UK                 | 4         | 4.76%   |
| Germany            | 3         | 3.57%   |
| France             | 3         | 3.57%   |
| Uruguay            | 2         | 2.38%   |
| Thailand           | 2         | 2.38%   |
| South Africa       | 2         | 2.38%   |
| Russia             | 2         | 2.38%   |
| Malaysia           | 2         | 2.38%   |
| Italy              | 2         | 2.38%   |
| Vietnam            | 1         | 1.19%   |
| Venezuela          | 1         | 1.19%   |
| Turkey             | 1         | 1.19%   |
| Tunisia            | 1         | 1.19%   |
| Slovakia           | 1         | 1.19%   |
| Poland             | 1         | 1.19%   |
| Philippines        | 1         | 1.19%   |
| Japan              | 1         | 1.19%   |
| Indonesia          | 1         | 1.19%   |
| Hungary            | 1         | 1.19%   |
| Finland            | 1         | 1.19%   |
| Ethiopia           | 1         | 1.19%   |
| Dominican Republic | 1         | 1.19%   |
| Czechia            | 1         | 1.19%   |
| Colombia           | 1         | 1.19%   |
| Chile              | 1         | 1.19%   |
| Belarus            | 1         | 1.19%   |
| Austria            | 1         | 1.19%   |
| Argentina          | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Madrid             | 3         | 3.49%   |
| Seremban           | 2         | 2.33%   |
| Sao Paulo          | 2         | 2.33%   |
| New Delhi          | 2         | 2.33%   |
| Montevideo         | 2         | 2.33%   |
| Cape Town          | 2         | 2.33%   |
| Bangkok            | 2         | 2.33%   |
| Yomitan            | 1         | 1.16%   |
| Welwyn Garden City | 1         | 1.16%   |
| Vienna             | 1         | 1.16%   |
| Valencia           | 1         | 1.16%   |
| Ulm                | 1         | 1.16%   |
| Turin              | 1         | 1.16%   |
| Torreón           | 1         | 1.16%   |
| Tirunelveli        | 1         | 1.16%   |
| Theodore           | 1         | 1.16%   |
| Tábor             | 1         | 1.16%   |
| Stevens Point      | 1         | 1.16%   |
| St Petersburg      | 1         | 1.16%   |
| Sparta             | 1         | 1.16%   |
| Sousse             | 1         | 1.16%   |
| Santo Domingo Este | 1         | 1.16%   |
| Santiago           | 1         | 1.16%   |
| Santa Rosa         | 1         | 1.16%   |
| Rocca di Papa      | 1         | 1.16%   |
| Pune               | 1         | 1.16%   |
| Paulista           | 1         | 1.16%   |
| Osasco             | 1         | 1.16%   |
| Nuremberg          | 1         | 1.16%   |
| Monterrey          | 1         | 1.16%   |
| Minsk              | 1         | 1.16%   |
| Milton Keynes      | 1         | 1.16%   |
| Mesa               | 1         | 1.16%   |
| Mazatlán          | 1         | 1.16%   |
| Mar del Plata      | 1         | 1.16%   |
| Mangalore          | 1         | 1.16%   |
| Manchester         | 1         | 1.16%   |
| Malang             | 1         | 1.16%   |
| Loskutova          | 1         | 1.16%   |
| Lorain             | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 15        | 17     | 11.19%  |
| Seagate                     | 13        | 19     | 9.7%    |
| Samsung Electronics         | 13        | 16     | 9.7%    |
| Sandisk                     | 12        | 15     | 8.96%   |
| Unknown                     | 9         | 16     | 6.72%   |
| Kingston                    | 6         | 10     | 4.48%   |
| Toshiba                     | 5         | 5      | 3.73%   |
| Phison Electronics          | 5         | 5      | 3.73%   |
| Hitachi                     | 5         | 5      | 3.73%   |
| KIOXIA                      | 4         | 4      | 2.99%   |
| Intel                       | 4         | 7      | 2.99%   |
| Micron/Crucial Technology   | 3         | 3      | 2.24%   |
| Crucial                     | 3         | 3      | 2.24%   |
| Unknown                     | 3         | 3      | 2.24%   |
| SPCC                        | 2         | 2      | 1.49%   |
| SK hynix                    | 2         | 2      | 1.49%   |
| Phison                      | 2         | 2      | 1.49%   |
| Patriot                     | 2         | 2      | 1.49%   |
| ADATA Technology            | 2         | 2      | 1.49%   |
| A-DATA Technology           | 2         | 3      | 1.49%   |
| Yangtze Memory Technologies | 1         | 1      | 0.75%   |
| SUNEAST                     | 1         | 1      | 0.75%   |
| Solid State Storage         | 1         | 1      | 0.75%   |
| SABRENT                     | 1         | 1      | 0.75%   |
| ROG                         | 1         | 1      | 0.75%   |
| Realtek Semiconductor       | 1         | 1      | 0.75%   |
| Netac                       | 1         | 1      | 0.75%   |
| Mushkin                     | 1         | 2      | 0.75%   |
| Micron Technology           | 1         | 2      | 0.75%   |
| MaxDigital                  | 1         | 1      | 0.75%   |
| Kingston Technology Company | 1         | 2      | 0.75%   |
| KingFast                    | 1         | 2      | 0.75%   |
| Initio                      | 1         | 1      | 0.75%   |
| Inateck                     | 1         | 1      | 0.75%   |
| Hjwdz                       | 1         | 1      | 0.75%   |
| HGST                        | 1         | 1      | 0.75%   |
| Gigabyte Technology         | 1         | 2      | 0.75%   |
| EVM                         | 1         | 1      | 0.75%   |
| China                       | 1         | 2      | 0.75%   |
| ASMT                        | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 6         | 4%      |
| Unknown MMC Card  32GB                              | 4         | 2.67%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 2%      |
| Unknown                                             | 3         | 2%      |
| Unknown MMC Card  64GB                              | 2         | 1.33%   |
| Seagate ST500LM030-2E717D 500GB                     | 2         | 1.33%   |
| Sandisk WD_BLACK SN770 1TB                          | 2         | 1.33%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 2         | 1.33%   |
| Samsung SSD 980 1TB                                 | 2         | 1.33%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 1.33%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2         | 1.33%   |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 0.67%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.67%   |
| WDC WDS200T2B0B 2TB SSD                             | 1         | 0.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 0.67%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1         | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.67%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 0.67%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.67%   |
| WDC WD20 EARX-00PASB0 2TB                           | 1         | 0.67%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.67%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.67%   |
| WDC WD10SPCX-60KHST0 1TB                            | 1         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.67%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1         | 0.67%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1         | 0.67%   |
| WDC WD10EARS-00MVWB0 1TB                            | 1         | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.67%   |
| Unknown SC128  128GB                                | 1         | 0.67%   |
| Unknown NVMe SSD Drive 2TB                          | 1         | 0.67%   |
| Unknown MMC Card  16GB                              | 1         | 0.67%   |
| Unknown MMC Card  128GB                             | 1         | 0.67%   |
| Unknown Essentiel B 1TB                             | 1         | 0.67%   |
| Toshiba XG6 NVMe SSD Controller 1024GB              | 1         | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.67%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.67%   |
| Toshiba DT01ACA200 2TB                              | 1         | 0.67%   |
| Toshiba DT01ACA100 1TB                              | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor     | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| Seagate    | 13        | 19     | 32.5%   |
| WDC        | 11        | 13     | 27.5%   |
| Hitachi    | 5         | 5      | 12.5%   |
| Toshiba    | 4         | 4      | 10%     |
| Unknown    | 2         | 3      | 5%      |
| SABRENT    | 1         | 1      | 2.5%    |
| MaxDigital | 1         | 1      | 2.5%    |
| Initio     | 1         | 1      | 2.5%    |
| HGST       | 1         | 1      | 2.5%    |
| ASMT       | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 6      | 12.12%  |
| WDC                 | 3         | 3      | 9.09%   |
| SanDisk             | 3         | 4      | 9.09%   |
| Unknown             | 3         | 3      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| Patriot             | 2         | 2      | 6.06%   |
| Intel               | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 3      | 6.06%   |
| SUNEAST             | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Phison              | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 2      | 3.03%   |
| EVM                 | 1         | 1      | 3.03%   |
| China               | 1         | 2      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| Apacer              | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 65     | 39.29%  |
| HDD     | 30        | 49     | 26.79%  |
| SSD     | 28        | 39     | 25%     |
| MMC     | 7         | 12     | 6.25%   |
| Unknown | 3         | 4      | 2.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 77     | 42.99%  |
| NVMe | 44        | 64     | 41.12%  |
| SAS  | 10        | 16     | 9.35%   |
| MMC  | 7         | 12     | 6.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 50     | 53.97%  |
| 0.51-1.0   | 19        | 26     | 30.16%  |
| 1.01-2.0   | 5         | 7      | 7.94%   |
| 3.01-4.0   | 2         | 2      | 3.17%   |
| 4.01-10.0  | 2         | 2      | 3.17%   |
| 2.01-3.0   | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 24.71%  |
| 101-250        | 21        | 24.71%  |
| 501-1000       | 14        | 16.47%  |
| More than 3000 | 8         | 9.41%   |
| 1001-2000      | 8         | 9.41%   |
| Unknown        | 5         | 5.88%   |
| 51-100         | 4         | 4.71%   |
| 21-50          | 3         | 3.53%   |
| 2001-3000      | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 22        | 25.29%  |
| 1-20           | 20        | 22.99%  |
| 51-100         | 14        | 16.09%  |
| 251-500        | 10        | 11.49%  |
| 101-250        | 8         | 9.2%    |
| Unknown        | 5         | 5.75%   |
| 501-1000       | 4         | 4.6%    |
| More than 3000 | 2         | 2.3%    |
| 1001-2000      | 2         | 2.3%    |

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
| Works    | 60        | 101    | 61.86%  |
| Detected | 29        | 56     | 29.9%   |
| Malfunc  | 7         | 8      | 7.22%   |
| Failed   | 1         | 4      | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 48        | 40.68%  |
| AMD                            | 17        | 14.41%  |
| Samsung Electronics            | 11        | 9.32%   |
| SanDisk                        | 10        | 8.47%   |
| Phison Electronics             | 5         | 4.24%   |
| Kingston Technology Company    | 5         | 4.24%   |
| Micron/Crucial Technology      | 4         | 3.39%   |
| KIOXIA                         | 4         | 3.39%   |
| ASMedia Technology             | 3         | 2.54%   |
| ADATA Technology               | 2         | 1.69%   |
| Yangtze Memory Technologies    | 1         | 0.85%   |
| Toshiba America Info Systems   | 1         | 0.85%   |
| Solidigm                       | 1         | 0.85%   |
| Solid State Storage Technology | 1         | 0.85%   |
| SK hynix                       | 1         | 0.85%   |
| Silicon Motion                 | 1         | 0.85%   |
| Realtek Semiconductor          | 1         | 0.85%   |
| Micron Technology              | 1         | 0.85%   |
| INNOGRIT                       | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 11        | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 7         | 5.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 6         | 4.55%   |
| AMD 500 Series Chipset SATA Controller                                        | 4         | 3.03%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 3         | 2.27%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 3         | 2.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 3         | 2.27%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 3         | 2.27%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.27%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 3         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 3         | 2.27%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 2         | 1.52%   |
| Phison E16 PCIe4 NVMe Controller                                              | 2         | 1.52%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                          | 2         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 1.52%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 2         | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 2         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 1.52%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 2         | 1.52%   |
| AMD 400 Series Chipset SATA Controller                                        | 2         | 1.52%   |
| Yangtze Memory PC005 NVMe SSD                                                 | 1         | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 0.76%   |
| Solidigm P44 Pro NVMe SSD [Hollywood Beach]                                   | 1         | 0.76%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 1         | 0.76%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.76%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                    | 1         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 1         | 0.76%   |
| Sandisk WD Black SN850X NVMe SSD                                              | 1         | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 1         | 0.76%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                     | 1         | 0.76%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 50%     |
| NVMe | 44        | 38.6%   |
| RAID | 9         | 7.89%   |
| IDE  | 4         | 3.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 71.43%  |
| AMD    | 24        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 3         | 3.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 3         | 3.57%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 3.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 2         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 2.38%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2         | 2.38%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2         | 2.38%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2         | 2.38%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1         | 1.19%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.19%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 1.19%   |
| Intel Core i7-8705G CPU @ 3.10GHz              | 1         | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.19%   |
| Intel Core i7-5500U CPU @ 2.40GHz              | 1         | 1.19%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.19%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1         | 1.19%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.19%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz             | 1         | 1.19%   |
| Intel Core i5-8350U CPU @ 1.70GHz              | 1         | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 1         | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 1.19%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 1.19%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.19%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 1.19%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.19%   |
| Intel Core i5-2540M CPU @ 2.60GHz              | 1         | 1.19%   |
| Intel Core i5-2467M CPU @ 1.60GHz              | 1         | 1.19%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.19%   |
| Intel Core i5 CPU M 450 @ 2.40GHz              | 1         | 1.19%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 1         | 1.19%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.19%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 1         | 1.19%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 1.19%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz             | 1         | 1.19%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 20.24%  |
| Other                | 11        | 13.1%   |
| AMD Ryzen 7          | 10        | 11.9%   |
| Intel Core i7        | 9         | 10.71%  |
| Intel Celeron        | 8         | 9.52%   |
| AMD Ryzen 5          | 7         | 8.33%   |
| Intel Core i3        | 6         | 7.14%   |
| AMD Ryzen 9          | 4         | 4.76%   |
| Intel Core 2 Duo     | 3         | 3.57%   |
| Intel Atom           | 3         | 3.57%   |
| AMD A10              | 2         | 2.38%   |
| Intel Xeon           | 1         | 1.19%   |
| Intel Pentium Silver | 1         | 1.19%   |
| Intel Pentium        | 1         | 1.19%   |
| AMD A4               | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 28        | 33.33%  |
| 2      | 28        | 33.33%  |
| 8      | 14        | 16.67%  |
| 6      | 7         | 8.33%   |
| 10     | 3         | 3.57%   |
| 12     | 2         | 2.38%   |
| 28     | 1         | 1.19%   |
| 16     | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 73.81%  |
| 1      | 22        | 26.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 57.65%  |
| 0x706a8    | 3         | 3.53%   |
| 0xa0652    | 2         | 2.35%   |
| 0x806d1    | 2         | 2.35%   |
| 0x506e3    | 2         | 2.35%   |
| 0x206a7    | 2         | 2.35%   |
| 0x906e9    | 1         | 1.18%   |
| 0x806ec    | 1         | 1.18%   |
| 0x806ea    | 1         | 1.18%   |
| 0x806c1    | 1         | 1.18%   |
| 0x6fd      | 1         | 1.18%   |
| 0x506c9    | 1         | 1.18%   |
| 0x50654    | 1         | 1.18%   |
| 0x406c4    | 1         | 1.18%   |
| 0x40651    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x306c3    | 1         | 1.18%   |
| 0x306a9    | 1         | 1.18%   |
| 0x0a601203 | 1         | 1.18%   |
| 0x0a50000c | 1         | 1.18%   |
| 0x0a404102 | 1         | 1.18%   |
| 0x0a201016 | 1         | 1.18%   |
| 0x0a201009 | 1         | 1.18%   |
| 0x08701030 | 1         | 1.18%   |
| 0x08701021 | 1         | 1.18%   |
| 0x08608104 | 1         | 1.18%   |
| 0x08600106 | 1         | 1.18%   |
| 0x08600104 | 1         | 1.18%   |
| 0x08108102 | 1         | 1.18%   |
| 0x06003106 | 1         | 1.18%   |
| 0x03000027 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 14.29%  |
| Zen 2            | 9         | 10.71%  |
| Zen 3            | 6         | 7.14%   |
| Icelake          | 6         | 7.14%   |
| Silvermont       | 5         | 5.95%   |
| Goldmont plus    | 5         | 5.95%   |
| TigerLake        | 4         | 4.76%   |
| SandyBridge      | 4         | 4.76%   |
| Haswell          | 4         | 4.76%   |
| Unknown          | 4         | 4.76%   |
| Zen+             | 3         | 3.57%   |
| Skylake          | 3         | 3.57%   |
| Broadwell        | 3         | 3.57%   |
| Westmere         | 2         | 2.38%   |
| Steamroller      | 2         | 2.38%   |
| IvyBridge        | 2         | 2.38%   |
| Core             | 2         | 2.38%   |
| CometLake        | 2         | 2.38%   |
| Alderlake Hybrid | 2         | 2.38%   |
| Tremont          | 1         | 1.19%   |
| Penryn           | 1         | 1.19%   |
| K10 Llano        | 1         | 1.19%   |
| Goldmont         | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 52.43%  |
| AMD    | 26        | 25.24%  |
| Nvidia | 23        | 22.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 5         | 4.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 2.75%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.75%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 2.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 2.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.83%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.83%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 1.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 2         | 1.83%   |
| Intel HD Graphics 630                                                                    | 2         | 1.83%   |
| Intel HD Graphics 620                                                                    | 2         | 1.83%   |
| Intel HD Graphics 530                                                                    | 2         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.83%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 2         | 1.83%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 1.83%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.92%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.92%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.92%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1         | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.92%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.92%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.92%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.92%   |
| Nvidia GA107BM / GN20-P0-R-K2 [GeForce RTX 3050 6GB Laptop GPU]                          | 1         | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 44.05%  |
| 1 x AMD        | 15        | 17.86%  |
| Intel + Nvidia | 12        | 14.29%  |
| 1 x Nvidia     | 8         | 9.52%   |
| 2 x AMD        | 5         | 5.95%   |
| Intel + AMD    | 3         | 3.57%   |
| AMD + Nvidia   | 3         | 3.57%   |
| 2 x Intel      | 1         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 74.12%  |
| Proprietary | 21        | 24.71%  |
| Unknown     | 1         | 1.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 63.53%  |
| 7.01-8.0   | 9         | 10.59%  |
| 0.01-0.5   | 7         | 8.24%   |
| 16.01-24.0 | 3         | 3.53%   |
| 1.01-2.0   | 3         | 3.53%   |
| 8.01-16.0  | 3         | 3.53%   |
| 5.01-6.0   | 2         | 2.35%   |
| 3.01-4.0   | 2         | 2.35%   |
| 0.51-1.0   | 2         | 2.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 12        | 12.5%   |
| Chimei Innolux       | 11        | 11.46%  |
| Samsung Electronics  | 10        | 10.42%  |
| AU Optronics         | 10        | 10.42%  |
| LG Display           | 6         | 6.25%   |
| Goldstar             | 6         | 6.25%   |
| Dell                 | 6         | 6.25%   |
| PANDA                | 5         | 5.21%   |
| Sharp                | 3         | 3.13%   |
| Ancor Communications | 3         | 3.13%   |
| Acer                 | 3         | 3.13%   |
| Lenovo               | 2         | 2.08%   |
| ASUSTek Computer     | 2         | 2.08%   |
| Apple                | 2         | 2.08%   |
| AOC                  | 2         | 2.08%   |
| Toshiba              | 1         | 1.04%   |
| Roku                 | 1         | 1.04%   |
| Mi                   | 1         | 1.04%   |
| JPN                  | 1         | 1.04%   |
| JLK                  | 1         | 1.04%   |
| InfoVision           | 1         | 1.04%   |
| HUAWEI               | 1         | 1.04%   |
| HKC                  | 1         | 1.04%   |
| HJC                  | 1         | 1.04%   |
| Hewlett-Packard      | 1         | 1.04%   |
| BenQ                 | 1         | 1.04%   |
| AGO                  | 1         | 1.04%   |
| Unknown              | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 2         | 2.02%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 2.02%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 2.02%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 2.02%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 1.01%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| Sharp LCD Monitor SHP14F8 3840x2400 288x180mm 13.4-inch               | 1         | 1.01%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.01%   |
| Samsung Electronics S34CG50 SAM730F 3440x1440 798x334mm 34.1-inch     | 1         | 1.01%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.01%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC416C 1920x1080 344x194mm 15.5-inch | 1         | 1.01%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 1         | 1.01%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 1.01%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 1.01%   |
| Roku TV RKU8518 1920x1080 698x392mm 31.5-inch                         | 1         | 1.01%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                      | 1         | 1.01%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 1.01%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1         | 1.01%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch               | 1         | 1.01%   |
| JPN IPS245FHDR165 JPN2500 1920x1080 552x314mm 25.0-inch               | 1         | 1.01%   |
| JLK F32FR1K-17B JLK3251 1920x1080 544x303mm 24.5-inch                 | 1         | 1.01%   |
| InfoVision LCD Monitor IVO34D1 1920x1280 285x190mm 13.5-inch          | 1         | 1.01%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                  | 1         | 1.01%   |
| HKC GM27H10C HKC0027 1920x1080 597x336mm 27.0-inch                    | 1         | 1.01%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                 | 1         | 1.01%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1         | 1.01%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1         | 1.01%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch               | 1         | 1.01%   |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch               | 1         | 1.01%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 40        | 44.44%  |
| 1366x768 (WXGA)  | 19        | 21.11%  |
| 3840x2160 (4K)   | 6         | 6.67%   |
| 2560x1440 (QHD)  | 5         | 5.56%   |
| 3440x1440        | 3         | 3.33%   |
| 3840x1080        | 2         | 2.22%   |
| 2560x1080        | 2         | 2.22%   |
| 2256x1504        | 2         | 2.22%   |
| 1440x900 (WXGA+) | 2         | 2.22%   |
| 3840x2400        | 1         | 1.11%   |
| 3200x1080        | 1         | 1.11%   |
| 2240x1400        | 1         | 1.11%   |
| 2160x1440        | 1         | 1.11%   |
| 1920x1280        | 1         | 1.11%   |
| 1600x900 (HD+)   | 1         | 1.11%   |
| 1280x800 (WXGA)  | 1         | 1.11%   |
| 1280x1024 (SXGA) | 1         | 1.11%   |
| Unknown          | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 29.59%  |
| 13      | 11        | 11.22%  |
| 24      | 9         | 9.18%   |
| 14      | 9         | 9.18%   |
| 34      | 6         | 6.12%   |
| 23      | 5         | 5.1%    |
| 31      | 4         | 4.08%   |
| 27      | 4         | 4.08%   |
| 12      | 4         | 4.08%   |
| 21      | 3         | 3.06%   |
| 48      | 2         | 2.04%   |
| 19      | 2         | 2.04%   |
| 11      | 2         | 2.04%   |
| 74      | 1         | 1.02%   |
| 64      | 1         | 1.02%   |
| 32      | 1         | 1.02%   |
| 25      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 17      | 1         | 1.02%   |
| 16      | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 43.16%  |
| 501-600     | 16        | 16.84%  |
| 201-300     | 14        | 14.74%  |
| 701-800     | 7         | 7.37%   |
| 401-500     | 6         | 6.32%   |
| 601-700     | 5         | 5.26%   |
| 1001-1500   | 3         | 3.16%   |
| 351-400     | 1         | 1.05%   |
| 1501-2000   | 1         | 1.05%   |
| Unknown     | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 75.29%  |
| 21/9    | 6         | 7.06%   |
| 16/10   | 6         | 7.06%   |
| 3/2     | 4         | 4.71%   |
| 32/9    | 2         | 2.35%   |
| 5/4     | 1         | 1.18%   |
| 4/3     | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 31.96%  |
| 81-90          | 16        | 16.49%  |
| 351-500        | 11        | 11.34%  |
| 201-250        | 11        | 11.34%  |
| 251-300        | 5         | 5.15%   |
| 71-80          | 4         | 4.12%   |
| 301-350        | 4         | 4.12%   |
| 61-70          | 3         | 3.09%   |
| 151-200        | 3         | 3.09%   |
| More than 1000 | 2         | 2.06%   |
| 51-60          | 2         | 2.06%   |
| 141-150        | 2         | 2.06%   |
| 501-1000       | 2         | 2.06%   |
| Unknown        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 34.04%  |
| 51-100        | 26        | 27.66%  |
| 101-120       | 22        | 23.4%   |
| 161-240       | 10        | 10.64%  |
| More than 240 | 2         | 2.13%   |
| 1-50          | 1         | 1.06%   |
| Unknown       | 1         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 66        | 78.57%  |
| 2     | 16        | 19.05%  |
| 3     | 2         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 42.86%  |
| Intel                    | 39        | 32.77%  |
| MediaTek                 | 6         | 5.04%   |
| Qualcomm Atheros         | 5         | 4.2%    |
| Ralink Technology        | 4         | 3.36%   |
| Broadcom                 | 4         | 3.36%   |
| Broadcom Limited         | 2         | 1.68%   |
| TP-Link                  | 1         | 0.84%   |
| Prolific Technology      | 1         | 0.84%   |
| OPPO Electronics         | 1         | 0.84%   |
| Microsoft                | 1         | 0.84%   |
| Marvell Technology Group | 1         | 0.84%   |
| DisplayLink              | 1         | 0.84%   |
| ASIX Electronics         | 1         | 0.84%   |
| Aquantia                 | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 19.59%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.05%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 2.03%   |
| Realtek 802.11ac NIC                                                   | 3         | 2.03%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 2.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 2.03%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 2.03%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 2.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 2.03%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 2.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.35%   |
| Intel Wireless 7265                                                    | 2         | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.35%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.35%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                         | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.68%   |
| Prolific USB-Serial Controller                                         | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 45.95%  |
| Realtek Semiconductor | 21        | 28.38%  |
| Qualcomm Atheros      | 5         | 6.76%   |
| MediaTek              | 5         | 6.76%   |
| Ralink Technology     | 4         | 5.41%   |
| Broadcom              | 3         | 4.05%   |
| TP-Link               | 1         | 1.35%   |
| Microsoft             | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 8         | 10.53%  |
| Intel Wireless 8265 / 8275                                    | 4         | 5.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 3.95%   |
| Realtek 802.11ac NIC                                          | 3         | 3.95%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 3.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 3.95%   |
| Intel Wi-Fi 6 AX200                                           | 3         | 3.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 3         | 3.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 3.95%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 3         | 3.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 2.63%   |
| Intel Wireless 7265                                           | 2         | 2.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 2         | 2.63%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 2.63%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.32%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1         | 1.32%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.32%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 1         | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.32%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 1.32%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 1.32%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 1.32%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 62.69%  |
| Intel                    | 15        | 22.39%  |
| Broadcom Limited         | 2         | 2.99%   |
| Broadcom                 | 2         | 2.99%   |
| OPPO Electronics         | 1         | 1.49%   |
| MediaTek                 | 1         | 1.49%   |
| Marvell Technology Group | 1         | 1.49%   |
| DisplayLink              | 1         | 1.49%   |
| ASIX Electronics         | 1         | 1.49%   |
| Aquantia                 | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 29        | 40.85%  |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 8.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 8.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 4.23%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 4.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 2.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 2.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 1.41%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.41%   |
| OPPO CPH2477                                                                   | 1         | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.41%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.41%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 1.41%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.41%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 1.41%   |
| DisplayLink USB3 TO HDMI                                                       | 1         | 1.41%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.41%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express                  | 1         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.41%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 52.63%  |
| Ethernet | 62        | 46.62%  |
| Modem    | 1         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 71.43%  |
| Ethernet | 24        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 54.76%  |
| 1     | 34        | 40.48%  |
| 0     | 3         | 3.57%   |
| 3     | 1         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 63.1%   |
| Yes  | 31        | 36.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 49.21%  |
| Realtek Semiconductor           | 11        | 17.46%  |
| IMC Networks                    | 5         | 7.94%   |
| Qualcomm Atheros Communications | 3         | 4.76%   |
| Cambridge Silicon Radio         | 3         | 4.76%   |
| MediaTek                        | 2         | 3.17%   |
| Foxconn / Hon Hai               | 2         | 3.17%   |
| Apple                           | 2         | 3.17%   |
| Realtek                         | 1         | 1.59%   |
| Lite-On Technology              | 1         | 1.59%   |
| Broadcom                        | 1         | 1.59%   |
| Actions                         | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 10        | 15.87%  |
| Realtek Bluetooth Radio                             | 7         | 11.11%  |
| Intel Bluetooth wireless interface                  | 6         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 4.76%   |
| Intel AX200 Bluetooth                               | 3         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.17%   |
| MediaTek Wireless_Device                            | 2         | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.17%   |
| Intel AX210 Bluetooth                               | 2         | 3.17%   |
| IMC Networks Wireless_Device                        | 2         | 3.17%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.17%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.59%   |
| Realtek Bluetooth Radio                             | 1         | 1.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.59%   |
| Intel AX211 Bluetooth                               | 1         | 1.59%   |
| IMC Networks Bluetooth Device                       | 1         | 1.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.59%   |
| Apple Bluetooth HCI                                 | 1         | 1.59%   |
| Actions general adapter                             | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 56        | 47.46%  |
| AMD                                          | 28        | 23.73%  |
| Nvidia                                       | 17        | 14.41%  |
| Logitech                                     | 3         | 2.54%   |
| Kingston Technology                          | 2         | 1.69%   |
| C-Media Electronics                          | 2         | 1.69%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.85%   |
| Texas Instruments                            | 1         | 0.85%   |
| Samson Technologies                          | 1         | 0.85%   |
| Realtek Semiconductor                        | 1         | 0.85%   |
| Oculus VR                                    | 1         | 0.85%   |
| KTMicro                                      | 1         | 0.85%   |
| JMTek                                        | 1         | 0.85%   |
| Focusrite-Novation                           | 1         | 0.85%   |
| Blue Microphones                             | 1         | 0.85%   |
| Astro Gaming                                 | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 11        | 7.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 6.16%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.42%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.05%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.05%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 2.05%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.37%   |
| Nvidia GA107 High Definition Audio Controller                              | 2         | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.37%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.37%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.37%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 1.37%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 1.37%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2         | 1.37%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 0.68%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.68%   |
| Samson Technologies C01U condenser microphone                              | 1         | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.68%   |
| Oculus VR Rift CV1 Audio                                                   | 1         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 17.28%  |
| Kingston            | 13        | 16.05%  |
| Micron Technology   | 12        | 14.81%  |
| SK hynix            | 10        | 12.35%  |
| Crucial             | 7         | 8.64%   |
| Unknown             | 6         | 7.41%   |
| A-DATA Technology   | 4         | 4.94%   |
| Unknown (ABCD)      | 2         | 2.47%   |
| Team                | 2         | 2.47%   |
| G.Skill             | 2         | 2.47%   |
| Corsair             | 2         | 2.47%   |
| Teclast             | 1         | 1.23%   |
| Ramaxel Technology  | 1         | 1.23%   |
| Nanya Technology    | 1         | 1.23%   |
| ff                  | 1         | 1.23%   |
| ChangXin Memory     | 1         | 1.23%   |
| 4ea5                | 1         | 1.23%   |
| Unknown             | 1         | 1.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 2.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 2.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.33%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 2.33%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.16%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.16%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 1.16%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 1.16%   |
| Teclast RAM YTD48G26N10 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.16%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 1.16%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 1.16%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.16%   |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 1.16%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 1         | 1.16%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.16%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.16%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.16%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.16%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.16%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.16%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.16%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s          | 1         | 1.16%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 1.16%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 54.93%  |
| DDR3   | 19        | 26.76%  |
| LPDDR4 | 7         | 9.86%   |
| DDR5   | 2         | 2.82%   |
| DDR2   | 2         | 2.82%   |
| SDRAM  | 1         | 1.41%   |
| LPDDR5 | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 60%     |
| DIMM         | 19        | 27.14%  |
| Row Of Chips | 8         | 11.43%  |
| Unknown      | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 38.96%  |
| 4096  | 15        | 19.48%  |
| 16384 | 13        | 16.88%  |
| 2048  | 9         | 11.69%  |
| 32768 | 5         | 6.49%   |
| 1024  | 5         | 6.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 14        | 18.18%  |
| 3200    | 13        | 16.88%  |
| 1600    | 13        | 16.88%  |
| 2400    | 6         | 7.79%   |
| 1333    | 5         | 6.49%   |
| 3600    | 3         | 3.9%    |
| 2133    | 3         | 3.9%    |
| 4800    | 2         | 2.6%    |
| 4267    | 2         | 2.6%    |
| 3800    | 2         | 2.6%    |
| 3733    | 2         | 2.6%    |
| 2933    | 2         | 2.6%    |
| 1334    | 2         | 2.6%    |
| 49926   | 1         | 1.3%    |
| 6400    | 1         | 1.3%    |
| 3333    | 1         | 1.3%    |
| 1866    | 1         | 1.3%    |
| 1067    | 1         | 1.3%    |
| 800     | 1         | 1.3%    |
| 667     | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

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
| Chicony Electronics                    | 11        | 22%     |
| Microdia                               | 6         | 12%     |
| Quanta                                 | 4         | 8%      |
| IMC Networks                           | 3         | 6%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6%      |
| Bison Electronics                      | 3         | 6%      |
| Suyin                                  | 2         | 4%      |
| Sunplus Innovation Technology          | 2         | 4%      |
| Samsung Electronics                    | 2         | 4%      |
| Realtek Semiconductor                  | 2         | 4%      |
| Luxvisions Innotech Limited            | 2         | 4%      |
| Generalplus Technology                 | 2         | 4%      |
| Apple                                  | 2         | 4%      |
| Alcor Micro                            | 2         | 4%      |
| Ricoh                                  | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| ARC International                      | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                    | 5         | 10%     |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)      | 2         | 4%      |
| Sunplus Integrated_Webcam_HD                                     | 2         | 4%      |
| Samsung Galaxy series, misc. (MTP mode)                          | 2         | 4%      |
| Quanta ov9734_techfront_camera                                   | 2         | 4%      |
| Quanta HP TrueVision HD Camera                                   | 2         | 4%      |
| Chicony Integrated IR Camera                                     | 2         | 4%      |
| Chicony HP Truevision HD                                         | 2         | 4%      |
| Chicony HD User Facing                                           | 2         | 4%      |
| Bison HD Webcam                                                  | 2         | 4%      |
| Ricoh Laptop_Integrated_Webcam_FHD                               | 1         | 2%      |
| Realtek HP Webcam                                                | 1         | 2%      |
| Realtek HD Webcam - Realtek                                      | 1         | 2%      |
| Microdia Webcam Vitade AF                                        | 1         | 2%      |
| Luxvisions Innotech Limited Integrated Camera                    | 1         | 2%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera              | 1         | 2%      |
| Logitech HD Pro Webcam C920                                      | 1         | 2%      |
| Lite-On Integrated Camera                                        | 1         | 2%      |
| IMC Networks Integrated Camera                                   | 1         | 2%      |
| IMC Networks HP TrueVision HD Camera                             | 1         | 2%      |
| IMC Networks HD Camera                                           | 1         | 2%      |
| Generalplus GENERAL WEBCAM                                       | 1         | 2%      |
| Generalplus 808 Camera #9 (web-cam mode)                         | 1         | 2%      |
| Chicony USB2.0 VGA UVC WebCam                                    | 1         | 2%      |
| Chicony Integrated HD WebCam                                     | 1         | 2%      |
| Chicony HP Wide Vision HD Camera                                 | 1         | 2%      |
| Chicony HP True Vision 5MP Camera                                | 1         | 2%      |
| Chicony HD Webcam                                                | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera  | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera   | 1         | 2%      |
| Bison Integrated Camera                                          | 1         | 2%      |
| ARC International Camera                                         | 1         | 2%      |
| Apple FaceTime Camera                                            | 1         | 2%      |
| Apple Built-in iSight [Micron]                                   | 1         | 2%      |
| Alcor Micro USB 2.0 Camera                                       | 1         | 2%      |
| Alcor Micro HD Webcam                                            | 1         | 2%      |

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
| 0     | 68        | 80.95%  |
| 1     | 13        | 15.48%  |
| 2     | 3         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 33.33%  |
| Net/wireless          | 3         | 16.67%  |
| Storage               | 2         | 11.11%  |
| Multimedia controller | 2         | 11.11%  |
| Graphics card         | 2         | 11.11%  |
| Chipcard              | 2         | 11.11%  |
| Unassigned class      | 1         | 5.56%   |

