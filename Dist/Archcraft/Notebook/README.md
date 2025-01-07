Archcraft - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Archcraft.

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

Total: 70

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | InsydeH2O EFI BIOS          | [1294da7ab3](https://linux-hardware.org/?probe=1294da7ab3) | Oct 21, 2024 |
| HP            | InsydeH2O EFI BIOS          | [738be8fc77](https://linux-hardware.org/?probe=738be8fc77) | Oct 14, 2024 |
| HP            | InsydeH2O EFI BIOS          | [d946696cbf](https://linux-hardware.org/?probe=d946696cbf) | Oct 07, 2024 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [c1be4d981d](https://linux-hardware.org/?probe=c1be4d981d) | Aug 24, 2024 |
| Google        | Blorb                       | [e78979a7d6](https://linux-hardware.org/?probe=e78979a7d6) | Aug 09, 2024 |
| Dell          | Vostro 3520                 | [290969f6d7](https://linux-hardware.org/?probe=290969f6d7) | Aug 07, 2024 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [a9c3d19fed](https://linux-hardware.org/?probe=a9c3d19fed) | Jul 15, 2024 |
| MSI           | Thin GF63 12UDX             | [8baf5df767](https://linux-hardware.org/?probe=8baf5df767) | May 21, 2024 |
| HUAWEI        | HLYL-WXX9                   | [479cc864f1](https://linux-hardware.org/?probe=479cc864f1) | May 20, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [2faf3d5ce2](https://linux-hardware.org/?probe=2faf3d5ce2) | Apr 28, 2024 |
| HP            | Laptop 15-da0xxx            | [81bca40901](https://linux-hardware.org/?probe=81bca40901) | Apr 27, 2024 |
| Dell          | Latitude 7290               | [b23f2a505a](https://linux-hardware.org/?probe=b23f2a505a) | Apr 10, 2024 |
| HP            | Pavilion Notebook           | [2cb306402a](https://linux-hardware.org/?probe=2cb306402a) | Feb 23, 2024 |
| SmbiosType... | N20                         | [0188c2ee35](https://linux-hardware.org/?probe=0188c2ee35) | Feb 05, 2024 |
| MouseCompu... | EGPN711R307                 | [fc34633537](https://linux-hardware.org/?probe=fc34633537) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [de15a66a8b](https://linux-hardware.org/?probe=de15a66a8b) | Oct 22, 2023 |
| Packard Be... | EasyNote TK85               | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Dell          | Vostro 3401                 | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| Packard Be... | EasyNote TK85               | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| AXDIA Inte... | WINPAD V10                  | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| AXDIA Inte... | WINPAD V10                  | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Dell          | Latitude E5420              | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Infinix       | INBook X1 Pro               | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| HP            | Notebook                    | [1ce7986145](https://linux-hardware.org/?probe=1ce7986145) | Jun 11, 2023 |
| HUAWEI        | NBD-WXX9                    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| HUAWEI        | BOHB-WAX9                   | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell          | Latitude 5490               | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI           | Alpha 15 B5EEK              | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines     | eME730                      | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| MSI           | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi         | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI           | GF63 Thin 10SC              | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| Dell          | Latitude E6420              | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple         | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple         | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP            | Laptop 15-dw0xxx            | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek       | X441SA                      | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer          | Swift SF113-31              | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo      | CHT14B                      | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| Framework     | Laptop                      | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard      | Unknown                     | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell          | Inspiron 3542               | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| Apple         | MacBookAir4,1               | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| Google        | Kindred                     | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP            | Laptop 15q-bu1xx            | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP            | Pavilion g4                 | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI           | GL65 Leopard 10SFK          | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 42        | 80.77%  |
| Archcraft         | 10        | 19.23%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Archcraft | 52        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.9.9-arch1-1          | 2         | 3.57%   |
| 6.9.1-arch1-1          | 2         | 3.57%   |
| 6.8.7-arch1-2          | 2         | 3.57%   |
| 6.6.10-arch1-1         | 2         | 3.57%   |
| 6.2.13-arch1-1         | 2         | 3.57%   |
| 5.18.16-arch1-1        | 2         | 3.57%   |
| 5.12.7-arch1-1         | 2         | 3.57%   |
| 6.8.4-zen1-1-zen       | 1         | 1.79%   |
| 6.7.5-arch1-1          | 1         | 1.79%   |
| 6.6.8-arch1-1          | 1         | 1.79%   |
| 6.5.5-zen1-1-zen       | 1         | 1.79%   |
| 6.4.7-arch1-1          | 1         | 1.79%   |
| 6.4.4-zen1-1-zen       | 1         | 1.79%   |
| 6.4.4-arch1-1          | 1         | 1.79%   |
| 6.4.10-zen2-1-zen      | 1         | 1.79%   |
| 6.4.10-arch1-1         | 1         | 1.79%   |
| 6.4.1-arch2-1          | 1         | 1.79%   |
| 6.3.9-arch1-1          | 1         | 1.79%   |
| 6.3.7-arch1-1-vfio     | 1         | 1.79%   |
| 6.3.6-arch1-1          | 1         | 1.79%   |
| 6.2.8-zen1-1-zen       | 1         | 1.79%   |
| 6.2.2-arch1-1          | 1         | 1.79%   |
| 6.2.12-arch1-1         | 1         | 1.79%   |
| 6.11.2-arch1-1         | 1         | 1.79%   |
| 6.10.5-arch1-1         | 1         | 1.79%   |
| 6.1.7-arch1-1          | 1         | 1.79%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 1.79%   |
| 6.1.1-arch1-1          | 1         | 1.79%   |
| 6.0.7-arch1-1          | 1         | 1.79%   |
| 6.0.2-arch1-1          | 1         | 1.79%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 1.79%   |
| 5.19.7-arch1-1         | 1         | 1.79%   |
| 5.19.6-arch1-1         | 1         | 1.79%   |
| 5.19.3-arch1-1         | 1         | 1.79%   |
| 5.19.13-arch1-1        | 1         | 1.79%   |
| 5.18.6-arch1-1         | 1         | 1.79%   |
| 5.18.14-zen1-1-zen     | 1         | 1.79%   |
| 5.17.9-arch1-1         | 1         | 1.79%   |
| 5.17.6-arch1-1         | 1         | 1.79%   |
| 5.17.5-arch1-1         | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.9.9   | 2         | 3.57%   |
| 6.9.1   | 2         | 3.57%   |
| 6.8.7   | 2         | 3.57%   |
| 6.6.10  | 2         | 3.57%   |
| 6.4.4   | 2         | 3.57%   |
| 6.4.10  | 2         | 3.57%   |
| 6.2.13  | 2         | 3.57%   |
| 5.18.16 | 2         | 3.57%   |
| 5.12.7  | 2         | 3.57%   |
| 6.8.4   | 1         | 1.79%   |
| 6.7.5   | 1         | 1.79%   |
| 6.6.8   | 1         | 1.79%   |
| 6.5.5   | 1         | 1.79%   |
| 6.4.7   | 1         | 1.79%   |
| 6.4.1   | 1         | 1.79%   |
| 6.3.9   | 1         | 1.79%   |
| 6.3.7   | 1         | 1.79%   |
| 6.3.6   | 1         | 1.79%   |
| 6.2.8   | 1         | 1.79%   |
| 6.2.2   | 1         | 1.79%   |
| 6.2.12  | 1         | 1.79%   |
| 6.11.2  | 1         | 1.79%   |
| 6.10.5  | 1         | 1.79%   |
| 6.1.7   | 1         | 1.79%   |
| 6.1.4   | 1         | 1.79%   |
| 6.1.1   | 1         | 1.79%   |
| 6.0.7   | 1         | 1.79%   |
| 6.0.2   | 1         | 1.79%   |
| 6.0.10  | 1         | 1.79%   |
| 5.19.7  | 1         | 1.79%   |
| 5.19.6  | 1         | 1.79%   |
| 5.19.3  | 1         | 1.79%   |
| 5.19.13 | 1         | 1.79%   |
| 5.18.6  | 1         | 1.79%   |
| 5.18.14 | 1         | 1.79%   |
| 5.17.9  | 1         | 1.79%   |
| 5.17.6  | 1         | 1.79%   |
| 5.17.5  | 1         | 1.79%   |
| 5.16.8  | 1         | 1.79%   |
| 5.16.7  | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 5         | 9.26%   |
| 6.2     | 5         | 9.26%   |
| 6.9     | 4         | 7.41%   |
| 5.19    | 4         | 7.41%   |
| 5.18    | 4         | 7.41%   |
| 5.12    | 4         | 7.41%   |
| 6.8     | 3         | 5.56%   |
| 6.6     | 3         | 5.56%   |
| 6.3     | 3         | 5.56%   |
| 6.1     | 3         | 5.56%   |
| 6.0     | 3         | 5.56%   |
| 5.17    | 3         | 5.56%   |
| 5.16    | 3         | 5.56%   |
| 6.7     | 1         | 1.85%   |
| 6.5     | 1         | 1.85%   |
| 6.11    | 1         | 1.85%   |
| 6.10    | 1         | 1.85%   |
| 5.15    | 1         | 1.85%   |
| 5.14    | 1         | 1.85%   |
| 5.10    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openbox  | 18        | 33.96%  |
| XFCE     | 15        | 28.3%   |
| bspwm    | 5         | 9.43%   |
| GNOME    | 3         | 5.66%   |
| sway     | 2         | 3.77%   |
| KDE6     | 2         | 3.77%   |
| i3       | 2         | 3.77%   |
| Hyprland | 2         | 3.77%   |
| xmonad   | 1         | 1.89%   |
| LXDE     | 1         | 1.89%   |
| dwm      | 1         | 1.89%   |
| Unknown  | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 88.68%  |
| Wayland | 6         | 11.32%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 36        | 67.92%  |
| Unknown | 10        | 18.87%  |
| LXDM    | 5         | 9.43%   |
| Ly      | 1         | 1.89%   |
| LightDM | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 26        | 50%     |
| es_MX | 5         | 9.62%   |
| en_IN | 5         | 9.62%   |
| es_ES | 4         | 7.69%   |
| en_ZA | 2         | 3.85%   |
| en_SG | 2         | 3.85%   |
| en_GB | 2         | 3.85%   |
| tr_TR | 1         | 1.92%   |
| pl_PL | 1         | 1.92%   |
| it_IT | 1         | 1.92%   |
| fr_FR | 1         | 1.92%   |
| en_PH | 1         | 1.92%   |
| de_AT | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 37        | 71.15%  |
| BIOS | 15        | 28.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 41        | 78.85%  |
| Btrfs | 9         | 17.31%  |
| Xfs   | 1         | 1.92%   |
| Tmpfs | 1         | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 38        | 73.08%  |
| Unknown | 9         | 17.31%  |
| MBR     | 5         | 9.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 84.62%  |
| Yes       | 8         | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 67.92%  |
| Yes       | 17        | 32.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 12        | 23.08%  |
| Dell                           | 9         | 17.31%  |
| MSI                            | 5         | 9.62%   |
| ASUSTek Computer               | 4         | 7.69%   |
| Lenovo                         | 3         | 5.77%   |
| HUAWEI                         | 3         | 5.77%   |
| Google                         | 2         | 3.85%   |
| Apple                          | 2         | 3.85%   |
| Acer                           | 2         | 3.85%   |
| Standard                       | 1         | 1.92%   |
| SmbiosType1_SystemManufacturer | 1         | 1.92%   |
| Positivo                       | 1         | 1.92%   |
| Packard Bell                   | 1         | 1.92%   |
| MouseComputer                  | 1         | 1.92%   |
| Infinix                        | 1         | 1.92%   |
| Framework                      | 1         | 1.92%   |
| eMachines                      | 1         | 1.92%   |
| Chuwi                          | 1         | 1.92%   |
| AXDIA International            | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| SmbiosType1_SystemManufacturer N20    | 1         | 1.92%   |
| Positivo CHT14B                       | 1         | 1.92%   |
| Packard Bell EasyNote TK85            | 1         | 1.92%   |
| MSI Thin GF63 12UDX                   | 1         | 1.92%   |
| MSI Katana GF66 11UE                  | 1         | 1.92%   |
| MSI GL65 Leopard 10SFK                | 1         | 1.92%   |
| MSI GF63 Thin 10SC                    | 1         | 1.92%   |
| MSI Alpha 15 B5EEK                    | 1         | 1.92%   |
| MouseComputer EGPN711R307             | 1         | 1.92%   |
| Lenovo ThinkPad X280 20KFCTO1WW       | 1         | 1.92%   |
| Lenovo ThinkPad T430 2351AK9          | 1         | 1.92%   |
| Lenovo IdeaPad 3 15IGL05 81WQ         | 1         | 1.92%   |
| Infinix INBook X1 Pro                 | 1         | 1.92%   |
| HUAWEI NBD-WXX9                       | 1         | 1.92%   |
| HUAWEI HLYL-WXX9                      | 1         | 1.92%   |
| HUAWEI BOHB-WAX9                      | 1         | 1.92%   |
| HP Stream Laptop 11-ak0xxx            | 1         | 1.92%   |
| HP Pavilion Notebook                  | 1         | 1.92%   |
| HP Pavilion Laptop 15-eh0xxx          | 1         | 1.92%   |
| HP Pavilion Laptop 15-cc1xx           | 1         | 1.92%   |
| HP Pavilion g4                        | 1         | 1.92%   |
| HP Notebook                           | 1         | 1.92%   |
| HP Laptop 15q-bu1xx                   | 1         | 1.92%   |
| HP Laptop 15-dy2xxx                   | 1         | 1.92%   |
| HP Laptop 15-dw0xxx                   | 1         | 1.92%   |
| HP Laptop 15-da0xxx                   | 1         | 1.92%   |
| HP InsydeH2O EFI BIOS                 | 1         | 1.92%   |
| HP Dragonfly 13.5 inch G4 Notebook PC | 1         | 1.92%   |
| Google Kindred                        | 1         | 1.92%   |
| Google Blorb                          | 1         | 1.92%   |
| Framework Laptop                      | 1         | 1.92%   |
| eMachines eME730                      | 1         | 1.92%   |
| Dell Vostro 3520                      | 1         | 1.92%   |
| Dell Vostro 3401                      | 1         | 1.92%   |
| Dell Latitude E7250                   | 1         | 1.92%   |
| Dell Latitude E6420                   | 1         | 1.92%   |
| Dell Latitude E5420                   | 1         | 1.92%   |
| Dell Latitude 7290                    | 1         | 1.92%   |
| Dell Latitude 5490                    | 1         | 1.92%   |
| Dell Inspiron 7559                    | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Dell Latitude                      | 5         | 9.62%   |
| HP Pavilion                        | 4         | 7.69%   |
| HP Laptop                          | 4         | 7.69%   |
| Lenovo ThinkPad                    | 2         | 3.85%   |
| Dell Vostro                        | 2         | 3.85%   |
| Dell Inspiron                      | 2         | 3.85%   |
| ASUS ROG                           | 2         | 3.85%   |
| SmbiosType1_SystemManufacturer N20 | 1         | 1.92%   |
| Positivo CHT14B                    | 1         | 1.92%   |
| Packard Bell EasyNote              | 1         | 1.92%   |
| MSI Thin                           | 1         | 1.92%   |
| MSI Katana                         | 1         | 1.92%   |
| MSI GL65                           | 1         | 1.92%   |
| MSI GF63                           | 1         | 1.92%   |
| MSI Alpha                          | 1         | 1.92%   |
| MouseComputer EGPN711R307          | 1         | 1.92%   |
| Lenovo IdeaPad                     | 1         | 1.92%   |
| Infinix INBook                     | 1         | 1.92%   |
| HUAWEI NBD-WXX9                    | 1         | 1.92%   |
| HUAWEI HLYL-WXX9                   | 1         | 1.92%   |
| HUAWEI BOHB-WAX9                   | 1         | 1.92%   |
| HP Stream                          | 1         | 1.92%   |
| HP Notebook                        | 1         | 1.92%   |
| HP InsydeH2O                       | 1         | 1.92%   |
| HP Dragonfly                       | 1         | 1.92%   |
| Google Kindred                     | 1         | 1.92%   |
| Google Blorb                       | 1         | 1.92%   |
| Framework Laptop                   | 1         | 1.92%   |
| eMachines eME730                   | 1         | 1.92%   |
| Chuwi GemiBook                     | 1         | 1.92%   |
| AXDIA International WINPAD         | 1         | 1.92%   |
| ASUS Zephyrus                      | 1         | 1.92%   |
| ASUS X441SA                        | 1         | 1.92%   |
| Apple MacBookAir4                  | 1         | 1.92%   |
| Apple MacBook4                     | 1         | 1.92%   |
| Acer Swift                         | 1         | 1.92%   |
| Acer Aspire                        | 1         | 1.92%   |
| Unknown                            | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 13        | 25%     |
| 2018 | 5         | 9.62%   |
| 2020 | 4         | 7.69%   |
| 2017 | 4         | 7.69%   |
| 2011 | 4         | 7.69%   |
| 2023 | 3         | 5.77%   |
| 2015 | 3         | 5.77%   |
| 2014 | 3         | 5.77%   |
| 2022 | 2         | 3.85%   |
| 2019 | 2         | 3.85%   |
| 2016 | 2         | 3.85%   |
| 2012 | 2         | 3.85%   |
| 2010 | 2         | 3.85%   |
| 2024 | 1         | 1.92%   |
| 2013 | 1         | 1.92%   |
| 2008 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 52        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 96.15%  |
| Yes  | 2         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 26.92%  |
| 3.01-4.0    | 10        | 19.23%  |
| 16.01-24.0  | 10        | 19.23%  |
| 8.01-16.0   | 8         | 15.38%  |
| 32.01-64.0  | 5         | 9.62%   |
| 1.01-2.0    | 3         | 5.77%   |
| 24.01-32.0  | 1         | 1.92%   |
| 64.01-256.0 | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 17        | 31.48%  |
| 2.01-3.0 | 14        | 25.93%  |
| 4.01-8.0 | 10        | 18.52%  |
| 3.01-4.0 | 9         | 16.67%  |
| 0.51-1.0 | 4         | 7.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 65.38%  |
| 2      | 16        | 30.77%  |
| 3      | 2         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 80.77%  |
| Yes       | 10        | 19.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 69.23%  |
| No        | 16        | 30.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 94.34%  |
| No        | 3         | 5.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 84.62%  |
| No        | 8         | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| India              | 7         | 13.46%  |
| USA                | 6         | 11.54%  |
| Spain              | 4         | 7.69%   |
| Mexico             | 4         | 7.69%   |
| Uruguay            | 2         | 3.85%   |
| UK                 | 2         | 3.85%   |
| South Africa       | 2         | 3.85%   |
| Russia             | 2         | 3.85%   |
| Malaysia           | 2         | 3.85%   |
| Italy              | 2         | 3.85%   |
| France             | 2         | 3.85%   |
| Brazil             | 2         | 3.85%   |
| Vietnam            | 1         | 1.92%   |
| Turkey             | 1         | 1.92%   |
| Tunisia            | 1         | 1.92%   |
| Thailand           | 1         | 1.92%   |
| Philippines        | 1         | 1.92%   |
| Japan              | 1         | 1.92%   |
| Indonesia          | 1         | 1.92%   |
| Finland            | 1         | 1.92%   |
| Ethiopia           | 1         | 1.92%   |
| Dominican Republic | 1         | 1.92%   |
| Colombia           | 1         | 1.92%   |
| Chile              | 1         | 1.92%   |
| Belarus            | 1         | 1.92%   |
| Austria            | 1         | 1.92%   |
| Argentina          | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Seremban           | 2         | 3.7%    |
| New Delhi          | 2         | 3.7%    |
| Montevideo         | 2         | 3.7%    |
| Madrid             | 2         | 3.7%    |
| Cape Town          | 2         | 3.7%    |
| Yomitan            | 1         | 1.85%   |
| Welwyn Garden City | 1         | 1.85%   |
| Vienna             | 1         | 1.85%   |
| Valencia           | 1         | 1.85%   |
| Turin              | 1         | 1.85%   |
| Torreón           | 1         | 1.85%   |
| Tirunelveli        | 1         | 1.85%   |
| Stevens Point      | 1         | 1.85%   |
| St Petersburg      | 1         | 1.85%   |
| Sousse             | 1         | 1.85%   |
| Sao Paulo          | 1         | 1.85%   |
| Santo Domingo Este | 1         | 1.85%   |
| Santiago           | 1         | 1.85%   |
| Santa Rosa         | 1         | 1.85%   |
| Rocca di Papa      | 1         | 1.85%   |
| Pune               | 1         | 1.85%   |
| Monterrey          | 1         | 1.85%   |
| Minsk              | 1         | 1.85%   |
| Mazatlán          | 1         | 1.85%   |
| Mar del Plata      | 1         | 1.85%   |
| Mangalore          | 1         | 1.85%   |
| Malang             | 1         | 1.85%   |
| Loskutova          | 1         | 1.85%   |
| London             | 1         | 1.85%   |
| Lannion            | 1         | 1.85%   |
| Kansas City        | 1         | 1.85%   |
| Jorge Negrete      | 1         | 1.85%   |
| Istanbul           | 1         | 1.85%   |
| Hyderabad          | 1         | 1.85%   |
| Huntersville       | 1         | 1.85%   |
| Helsinki           | 1         | 1.85%   |
| Hanoi              | 1         | 1.85%   |
| Gebze              | 1         | 1.85%   |
| Clifton Park       | 1         | 1.85%   |
| Brasília          | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 7         | 7      | 10.61%  |
| Unknown                     | 7         | 13     | 10.61%  |
| Samsung Electronics         | 6         | 7      | 9.09%   |
| Sandisk                     | 4         | 5      | 6.06%   |
| Seagate                     | 3         | 4      | 4.55%   |
| Phison Electronics          | 3         | 3      | 4.55%   |
| KIOXIA                      | 3         | 3      | 4.55%   |
| Toshiba                     | 2         | 2      | 3.03%   |
| SK hynix                    | 2         | 2      | 3.03%   |
| Micron/Crucial Technology   | 2         | 2      | 3.03%   |
| Kingston                    | 2         | 2      | 3.03%   |
| Intel                       | 2         | 2      | 3.03%   |
| Hitachi                     | 2         | 2      | 3.03%   |
| Crucial                     | 2         | 2      | 3.03%   |
| Unknown                     | 2         | 2      | 3.03%   |
| Yangtze Memory Technologies | 1         | 1      | 1.52%   |
| SPCC                        | 1         | 1      | 1.52%   |
| Solid State Storage         | 1         | 1      | 1.52%   |
| Realtek Semiconductor       | 1         | 1      | 1.52%   |
| Phison                      | 1         | 1      | 1.52%   |
| Patriot                     | 1         | 1      | 1.52%   |
| Netac                       | 1         | 1      | 1.52%   |
| Mushkin                     | 1         | 2      | 1.52%   |
| Kingston Technology Company | 1         | 2      | 1.52%   |
| KingFast                    | 1         | 2      | 1.52%   |
| Initio                      | 1         | 1      | 1.52%   |
| Hjwdz                       | 1         | 1      | 1.52%   |
| HGST                        | 1         | 1      | 1.52%   |
| Gigabyte Technology         | 1         | 2      | 1.52%   |
| EVM                         | 1         | 1      | 1.52%   |
| Apple                       | 1         | 1      | 1.52%   |
| ADATA Technology            | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 3         | 4.17%   |
| Seagate ST500LM030-2E717D 500GB                     | 2         | 2.78%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 2.78%   |
| Unknown                                             | 2         | 2.78%   |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 1.39%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 1.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.39%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 1.39%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1.39%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.39%   |
| WDC WD10SPCX-60KHST0 1TB                            | 1         | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.39%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 1.39%   |
| Unknown SC128  128GB                                | 1         | 1.39%   |
| Unknown MMC Card  64GB                              | 1         | 1.39%   |
| Unknown MMC Card  16GB                              | 1         | 1.39%   |
| Unknown MMC Card  128GB                             | 1         | 1.39%   |
| Unknown Essentiel B 1TB                             | 1         | 1.39%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.39%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.39%   |
| SPCC Solid State Disk 128GB                         | 1         | 1.39%   |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 1.39%   |
| SK hynix NVMe SSD Drive 128GB                       | 1         | 1.39%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.39%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.39%   |
| Seagate Expansion 1TB                               | 1         | 1.39%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 1.39%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 1.39%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.39%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 1         | 1.39%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB     | 1         | 1.39%   |
| Samsung SSD PM871 mSATA 256GB                       | 1         | 1.39%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1.39%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 1         | 1.39%   |
| Samsung MZVL4512HBLU-00BTW 512GB                    | 1         | 1.39%   |
| Realtek Teclast BD 512GB SSD                        | 1         | 1.39%   |
| Phison Sabrent Rocket 4.0 Plus 1TB                  | 1         | 1.39%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1         | 1.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 31.25%  |
| Seagate | 3         | 4      | 18.75%  |
| Unknown | 2         | 3      | 12.5%   |
| Toshiba | 2         | 2      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| Initio  | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 13.33%  |
| Unknown             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| SPCC                | 1         | 1      | 6.67%   |
| SK hynix            | 1         | 1      | 6.67%   |
| Patriot             | 1         | 1      | 6.67%   |
| Netac               | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Gigabyte Technology | 1         | 2      | 6.67%   |
| EVM                 | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 26        | 32     | 40.63%  |
| SSD     | 15        | 16     | 23.44%  |
| HDD     | 15        | 18     | 23.44%  |
| MMC     | 6         | 10     | 9.38%   |
| Unknown | 2         | 3      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 26        | 32     | 41.27%  |
| SATA | 26        | 31     | 41.27%  |
| MMC  | 6         | 10     | 9.52%   |
| SAS  | 5         | 6      | 7.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 20     | 60%     |
| 0.51-1.0   | 12        | 14     | 40%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 15        | 28.85%  |
| 101-250        | 14        | 26.92%  |
| 501-1000       | 8         | 15.38%  |
| 1001-2000      | 4         | 7.69%   |
| More than 3000 | 3         | 5.77%   |
| 21-50          | 3         | 5.77%   |
| 51-100         | 3         | 5.77%   |
| Unknown        | 2         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 18        | 33.33%  |
| 1-20     | 13        | 24.07%  |
| 51-100   | 9         | 16.67%  |
| 251-500  | 6         | 11.11%  |
| 101-250  | 3         | 5.56%   |
| 501-1000 | 3         | 5.56%   |
| Unknown  | 2         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS545032A7E380 320GB  | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 35        | 46     | 63.64%  |
| Detected | 17        | 30     | 30.91%  |
| Malfunc  | 3         | 3      | 5.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 36        | 57.14%  |
| SanDisk                        | 5         | 7.94%   |
| Samsung Electronics            | 4         | 6.35%   |
| Phison Electronics             | 3         | 4.76%   |
| Micron/Crucial Technology      | 3         | 4.76%   |
| KIOXIA                         | 3         | 4.76%   |
| Kingston Technology Company    | 2         | 3.17%   |
| Yangtze Memory Technologies    | 1         | 1.59%   |
| Solid State Storage Technology | 1         | 1.59%   |
| SK hynix                       | 1         | 1.59%   |
| Silicon Motion                 | 1         | 1.59%   |
| Realtek Semiconductor          | 1         | 1.59%   |
| AMD                            | 1         | 1.59%   |
| ADATA Technology               | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 6         | 8.82%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 3         | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.41%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 2         | 2.94%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 2         | 2.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 2         | 2.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 2.94%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 2.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 2.94%   |
| Intel Alder Lake-P SATA AHCI Controller                                      | 2         | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 2.94%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 1.47%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 1.47%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 1.47%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.47%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 1.47%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 1.47%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                        | 1         | 1.47%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                    | 1         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.47%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 1.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 1.47%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 1.47%   |
| Phison E18 PCIe4 NVMe Controller                                             | 1         | 1.47%   |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 1.47%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                         | 1         | 1.47%   |
| KIOXIA NVMe SSD Controller XG8                                               | 1         | 1.47%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.47%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 1.47%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                         | 1         | 1.47%   |
| Intel SSD 660P Series                                                        | 1         | 1.47%   |
| Intel Jasper Lake SATA AHCI Controller                                       | 1         | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 1.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 45.31%  |
| NVMe | 26        | 40.63%  |
| RAID | 8         | 12.5%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 86.54%  |
| AMD    | 7         | 13.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 5.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 5.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 5.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.85%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-2467M CPU @ 1.60GHz       | 1         | 1.92%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.92%   |
| Intel Core i5 CPU M 450 @ 2.40GHz       | 1         | 1.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.92%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 1         | 1.92%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 1         | 1.92%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 1         | 1.92%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 1         | 1.92%   |
| Intel Celeron N5095 @ 2.00GHz           | 1         | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 1         | 1.92%   |
| Intel Celeron 2957U @ 1.40GHz           | 1         | 1.92%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1         | 1.92%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 1         | 1.92%   |
| Intel 13th Gen Core i7-1355U            | 1         | 1.92%   |
| Intel 12th Gen Core i7-12650H           | 1         | 1.92%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.92%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.92%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 1         | 1.92%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 25%     |
| Other            | 9         | 17.31%  |
| Intel Core i7    | 7         | 13.46%  |
| Intel Celeron    | 7         | 13.46%  |
| Intel Core i3    | 5         | 9.62%   |
| AMD Ryzen 7      | 3         | 5.77%   |
| Intel Atom       | 2         | 3.85%   |
| AMD Ryzen 5      | 2         | 3.85%   |
| Intel Pentium    | 1         | 1.92%   |
| Intel Core 2 Duo | 1         | 1.92%   |
| AMD Ryzen 9      | 1         | 1.92%   |
| AMD A4           | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 42.31%  |
| 4      | 18        | 34.62%  |
| 8      | 6         | 11.54%  |
| 10     | 3         | 5.77%   |
| 6      | 3         | 5.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 75%     |
| 1      | 13        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 58.49%  |
| 0x706a8    | 3         | 5.66%   |
| 0xa0652    | 2         | 3.77%   |
| 0x806d1    | 2         | 3.77%   |
| 0x206a7    | 2         | 3.77%   |
| 0x806ec    | 1         | 1.89%   |
| 0x806ea    | 1         | 1.89%   |
| 0x506e3    | 1         | 1.89%   |
| 0x506c9    | 1         | 1.89%   |
| 0x406c4    | 1         | 1.89%   |
| 0x40651    | 1         | 1.89%   |
| 0x306d4    | 1         | 1.89%   |
| 0x306a9    | 1         | 1.89%   |
| 0x0a50000c | 1         | 1.89%   |
| 0x0a404102 | 1         | 1.89%   |
| 0x08600106 | 1         | 1.89%   |
| 0x08600104 | 1         | 1.89%   |
| 0x03000027 | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 19.23%  |
| IceLake          | 5         | 9.62%   |
| Goldmont plus    | 4         | 7.69%   |
| TigerLake        | 3         | 5.77%   |
| Silvermont       | 3         | 5.77%   |
| SandyBridge      | 3         | 5.77%   |
| Broadwell        | 3         | 5.77%   |
| Zen 3            | 2         | 3.85%   |
| Zen 2            | 2         | 3.85%   |
| Westmere         | 2         | 3.85%   |
| Haswell          | 2         | 3.85%   |
| CometLake        | 2         | 3.85%   |
| Alderlake Hybrid | 2         | 3.85%   |
| Unknown          | 2         | 3.85%   |
| Zen+             | 1         | 1.92%   |
| Tremont          | 1         | 1.92%   |
| Skylake          | 1         | 1.92%   |
| Penryn           | 1         | 1.92%   |
| K10 Llano        | 1         | 1.92%   |
| IvyBridge        | 1         | 1.92%   |
| Goldmont         | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 65.67%  |
| Nvidia | 13        | 19.4%   |
| AMD    | 10        | 14.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 5         | 7.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 5.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 4.29%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 4.29%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 2.86%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 2.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.86%   |
| Intel HD Graphics 620                                                                    | 2         | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.86%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 2.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.43%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.43%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.43%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.43%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.43%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.43%   |
| Nvidia GA107BM / GN20-P0-R-K2 [GeForce RTX 3050 6GB Laptop GPU]                          | 1         | 1.43%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.43%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.43%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.43%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.43%   |
| Intel HD Graphics 530                                                                    | 1         | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.43%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.43%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.43%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 59.62%  |
| Intel + Nvidia | 11        | 21.15%  |
| 1 x AMD        | 4         | 7.69%   |
| 2 x AMD        | 2         | 3.85%   |
| Intel + AMD    | 2         | 3.85%   |
| AMD + Nvidia   | 2         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 75%     |
| Proprietary | 12        | 23.08%  |
| Unknown     | 1         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 84.62%  |
| 0.01-0.5   | 5         | 9.62%   |
| 7.01-8.0   | 1         | 1.92%   |
| 5.01-6.0   | 1         | 1.92%   |
| 8.01-16.0  | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 11        | 18.33%  |
| BOE                 | 10        | 16.67%  |
| AU Optronics        | 10        | 16.67%  |
| LG Display          | 6         | 10%     |
| Samsung Electronics | 4         | 6.67%   |
| PANDA               | 4         | 6.67%   |
| Sharp               | 2         | 3.33%   |
| Dell                | 2         | 3.33%   |
| Apple               | 2         | 3.33%   |
| Mi                  | 1         | 1.67%   |
| Lenovo              | 1         | 1.67%   |
| JPN                 | 1         | 1.67%   |
| JLK                 | 1         | 1.67%   |
| InfoVision          | 1         | 1.67%   |
| HKC                 | 1         | 1.67%   |
| HJC                 | 1         | 1.67%   |
| ASUSTek Computer    | 1         | 1.67%   |
| AOC                 | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 3.33%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 2         | 3.33%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 3.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 3.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 3.33%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 1.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 1.67%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 1.67%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 1         | 1.67%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                     | 1         | 1.67%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 1.67%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 1.67%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 1.67%   |
| JPN IPS245FHDR165 JPN2500 1920x1080 552x314mm 25.0-inch              | 1         | 1.67%   |
| JLK F32FR1K-17B JLK3251 1920x1080 544x303mm 24.5-inch                | 1         | 1.67%   |
| InfoVision LCD Monitor IVO34D1 1920x1280 285x190mm 13.5-inch         | 1         | 1.67%   |
| HKC GM27H10C HKC0027 1920x1080 597x336mm 27.0-inch                   | 1         | 1.67%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                | 1         | 1.67%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                    | 1         | 1.67%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                  | 1         | 1.67%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1246 1920x1080 276x155mm 12.5-inch     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 1.67%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 1.67%   |
| BOE LCD Monitor BOE08E5 1366x768 344x194mm 15.5-inch                 | 1         | 1.67%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 26        | 47.27%  |
| 1366x768 (WXGA)  | 18        | 32.73%  |
| 2560x1440 (QHD)  | 2         | 3.64%   |
| 2256x1504        | 2         | 3.64%   |
| 3840x2160 (4K)   | 1         | 1.82%   |
| 3440x1440        | 1         | 1.82%   |
| 2160x1440        | 1         | 1.82%   |
| 1920x1280        | 1         | 1.82%   |
| 1600x900 (HD+)   | 1         | 1.82%   |
| 1440x900 (WXGA+) | 1         | 1.82%   |
| 1280x800 (WXGA)  | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 45%     |
| 13     | 9         | 15%     |
| 14     | 7         | 11.67%  |
| 24     | 4         | 6.67%   |
| 12     | 3         | 5%      |
| 27     | 2         | 3.33%   |
| 23     | 2         | 3.33%   |
| 11     | 2         | 3.33%   |
| 34     | 1         | 1.67%   |
| 25     | 1         | 1.67%   |
| 19     | 1         | 1.67%   |
| 16     | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 62.71%  |
| 201-300     | 11        | 18.64%  |
| 501-600     | 7         | 11.86%  |
| 701-800     | 1         | 1.69%   |
| 601-700     | 1         | 1.69%   |
| 401-500     | 1         | 1.69%   |
| 351-400     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 45        | 86.54%  |
| 3/2   | 4         | 7.69%   |
| 16/10 | 2         | 3.85%   |
| 21/9  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 46.67%  |
| 81-90          | 15        | 25%     |
| 251-300        | 4         | 6.67%   |
| 61-70          | 3         | 5%      |
| 201-250        | 3         | 5%      |
| 51-60          | 2         | 3.33%   |
| 301-350        | 2         | 3.33%   |
| 71-80          | 1         | 1.67%   |
| 351-500        | 1         | 1.67%   |
| 151-200        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 28        | 47.46%  |
| 101-120 | 16        | 27.12%  |
| 51-100  | 8         | 13.56%  |
| 161-240 | 7         | 11.86%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 82.69%  |
| 2     | 8         | 15.38%  |
| 3     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 41.56%  |
| Intel                    | 25        | 32.47%  |
| Qualcomm Atheros         | 5         | 6.49%   |
| Broadcom                 | 4         | 5.19%   |
| Ralink Technology        | 3         | 3.9%    |
| MediaTek                 | 3         | 3.9%    |
| TP-Link                  | 1         | 1.3%    |
| Marvell Technology Group | 1         | 1.3%    |
| DisplayLink              | 1         | 1.3%    |
| Broadcom Limited         | 1         | 1.3%    |
| ASIX Electronics         | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 17.2%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 7.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 5.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 2.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 2.15%   |
| Realtek 802.11ac NIC                                                   | 2         | 2.15%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 2.15%   |
| Intel Wireless 8265 / 8275                                             | 2         | 2.15%   |
| Intel Wireless 7265                                                    | 2         | 2.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 2.15%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 2.15%   |
| TP-Link 802.11ac WLAN Adapter                                          | 1         | 1.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 1.08%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.08%   |
| Ralink RT5572 Wireless Adapter                                         | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 1.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.08%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 1         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 1.08%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                         | 1         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 43.4%   |
| Realtek Semiconductor | 16        | 30.19%  |
| Qualcomm Atheros      | 5         | 9.43%   |
| Ralink Technology     | 3         | 5.66%   |
| Broadcom              | 3         | 5.66%   |
| MediaTek              | 2         | 3.77%   |
| TP-Link               | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 7         | 12.96%  |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 3.7%    |
| Realtek 802.11ac NIC                                          | 2         | 3.7%    |
| Ralink MT7601U Wireless Adapter                               | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                    | 2         | 3.7%    |
| Intel Wireless 7265                                           | 2         | 3.7%    |
| Intel Gemini Lake PCH CNVi WiFi                               | 2         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 3.7%    |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 1.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 1.85%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.85%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 1.85%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 1.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 1.85%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 1.85%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 1.85%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 24        | 63.16%  |
| Intel                    | 7         | 18.42%  |
| Broadcom                 | 2         | 5.26%   |
| MediaTek                 | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |
| DisplayLink              | 1         | 2.63%   |
| Broadcom Limited         | 1         | 2.63%   |
| ASIX Electronics         | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 41.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 12.82%  |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 7.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 5.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 2.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 2.56%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.56%   |
| DisplayLink USB3 TO HDMI                                               | 1         | 2.56%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 2.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 58.82%  |
| Ethernet | 35        | 41.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 86.79%  |
| Ethernet | 7         | 13.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 32        | 61.54%  |
| 1     | 18        | 34.62%  |
| 0     | 2         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 65.38%  |
| Yes  | 18        | 34.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 46.51%  |
| Realtek Semiconductor           | 9         | 20.93%  |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| IMC Networks                    | 3         | 6.98%   |
| Apple                           | 2         | 4.65%   |
| Realtek                         | 1         | 2.33%   |
| MediaTek                        | 1         | 2.33%   |
| Lite-On Technology              | 1         | 2.33%   |
| Foxconn / Hon Hai               | 1         | 2.33%   |
| Cambridge Silicon Radio         | 1         | 2.33%   |
| Broadcom                        | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 20.93%  |
| Realtek Bluetooth Radio                             | 6         | 13.95%  |
| Intel Bluetooth wireless interface                  | 4         | 9.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.65%   |
| Realtek Bluetooth Radio                             | 1         | 2.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.33%   |
| MediaTek Wireless_Device                            | 1         | 2.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.33%   |
| Intel AX211 Bluetooth                               | 1         | 2.33%   |
| Intel AX210 Bluetooth                               | 1         | 2.33%   |
| IMC Networks Wireless_Device                        | 1         | 2.33%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.33%   |
| IMC Networks Bluetooth Device                       | 1         | 2.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.33%   |
| Apple Bluetooth HCI                                 | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 43        | 72.88%  |
| AMD                                          | 8         | 13.56%  |
| Nvidia                                       | 7         | 11.86%  |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 9.86%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 6         | 8.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 5.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.23%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 4.23%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.23%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 2.82%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 2.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.82%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 1.41%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.41%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 23.08%  |
| SK hynix            | 9         | 17.31%  |
| Micron Technology   | 9         | 17.31%  |
| Kingston            | 8         | 15.38%  |
| Crucial             | 4         | 7.69%   |
| Unknown             | 2         | 3.85%   |
| Unknown (ABCD)      | 1         | 1.92%   |
| Teclast             | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| ff                  | 1         | 1.92%   |
| ChangXin Memory     | 1         | 1.92%   |
| A-DATA Technology   | 1         | 1.92%   |
| 4ea5                | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 3.64%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 1.82%   |
| Teclast RAM YTD48G26N10 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.82%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.82%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.82%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.82%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.82%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.82%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 1.82%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.82%   |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s                 | 1         | 1.82%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 1.82%   |
| Micron RAM K4A8G165WB-BCRC 8GB Row Of Chips LPDDR4 3333MT/s      | 1         | 1.82%   |
| Micron RAM 8KTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.82%   |
| Kingston RAM K821PJ-MID 16GB SODIMM DDR4 2400MT/s                | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 52.27%  |
| DDR3   | 14        | 31.82%  |
| LPDDR4 | 4         | 9.09%   |
| LPDDR5 | 1         | 2.27%   |
| DDR5   | 1         | 2.27%   |
| DDR2   | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 83.72%  |
| Row Of Chips | 6         | 13.95%  |
| Unknown      | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 37.5%   |
| 4096  | 11        | 22.92%  |
| 16384 | 8         | 16.67%  |
| 2048  | 6         | 12.5%   |
| 1024  | 3         | 6.25%   |
| 32768 | 2         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 18.75%  |
| 2667  | 9         | 18.75%  |
| 1600  | 9         | 18.75%  |
| 2400  | 5         | 10.42%  |
| 1333  | 4         | 8.33%   |
| 2933  | 2         | 4.17%   |
| 1334  | 2         | 4.17%   |
| 6400  | 1         | 2.08%   |
| 4800  | 1         | 2.08%   |
| 3733  | 1         | 2.08%   |
| 3333  | 1         | 2.08%   |
| 2133  | 1         | 2.08%   |
| 1866  | 1         | 2.08%   |
| 1067  | 1         | 2.08%   |
| 667   | 1         | 2.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 25.64%  |
| Microdia                               | 5         | 12.82%  |
| Quanta                                 | 4         | 10.26%  |
| IMC Networks                           | 3         | 7.69%   |
| Bison Electronics                      | 3         | 7.69%   |
| Suyin                                  | 2         | 5.13%   |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Realtek Semiconductor                  | 2         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.13%   |
| Apple                                  | 2         | 5.13%   |
| Ricoh                                  | 1         | 2.56%   |
| Luxvisions Innotech Limited            | 1         | 2.56%   |
| Lite-On Technology                     | 1         | 2.56%   |
| Alcor Micro                            | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 4         | 10.26%  |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 2         | 5.13%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 5.13%   |
| Quanta ov9734_techfront_camera                                  | 2         | 5.13%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 5.13%   |
| Chicony Integrated IR Camera                                    | 2         | 5.13%   |
| Chicony HP Truevision HD                                        | 2         | 5.13%   |
| Chicony HD User Facing                                          | 2         | 5.13%   |
| Bison HD Webcam                                                 | 2         | 5.13%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 2.56%   |
| Realtek HP Webcam                                               | 1         | 2.56%   |
| Realtek HD Webcam - Realtek                                     | 1         | 2.56%   |
| Microdia Webcam Vitade AF                                       | 1         | 2.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.56%   |
| Lite-On Integrated Camera                                       | 1         | 2.56%   |
| IMC Networks Integrated Camera                                  | 1         | 2.56%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 2.56%   |
| IMC Networks HD Camera                                          | 1         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 2.56%   |
| Chicony Integrated HD WebCam                                    | 1         | 2.56%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 2.56%   |
| Chicony HD Webcam                                               | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.56%   |
| Bison Integrated Camera                                         | 1         | 2.56%   |
| Apple FaceTime Camera                                           | 1         | 2.56%   |
| Apple Built-in iSight [Micron]                                  | 1         | 2.56%   |
| Alcor Micro USB 2.0 Camera                                      | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 40%     |
| Elan Microelectronics      | 2         | 40%     |
| LighTuning Technology      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                            | 2         | 40%     |
| Shenzhen Goodix  Fingerprint Device         | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader          | 1         | 20%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 2         | 66.67%  |
| Aladdin Knowledge Systems | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 76.92%  |
| 1     | 10        | 19.23%  |
| 2     | 2         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 35.71%  |
| Storage               | 2         | 14.29%  |
| Net/wireless          | 2         | 14.29%  |
| Multimedia controller | 2         | 14.29%  |
| Chipcard              | 2         | 14.29%  |
| Graphics card         | 1         | 7.14%   |

