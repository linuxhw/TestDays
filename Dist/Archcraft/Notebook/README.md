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

Total: 75

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [583752550a](https://linux-hardware.org/?probe=583752550a) | Dec 02, 2025 |
| HP            | Victus by Laptop 16-e0xx... | [16d3dda677](https://linux-hardware.org/?probe=16d3dda677) | Oct 13, 2025 |
| MSI           | Bravo 15 A4DDR              | [8cecfff5e4](https://linux-hardware.org/?probe=8cecfff5e4) | Jul 28, 2025 |
| Dell          | Inspiron 3501               | [f15af61211](https://linux-hardware.org/?probe=f15af61211) | Apr 15, 2025 |
| Apple         | MacBookPro9,2               | [0cb1a83784](https://linux-hardware.org/?probe=0cb1a83784) | Jan 17, 2025 |
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
| Archcraft Rolling | 46        | 82.14%  |
| Archcraft         | 10        | 17.86%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Archcraft | 56        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.9.9-arch1-1          | 2         | 3.33%   |
| 6.9.1-arch1-1          | 2         | 3.33%   |
| 6.8.7-arch1-2          | 2         | 3.33%   |
| 6.6.10-arch1-1         | 2         | 3.33%   |
| 6.2.13-arch1-1         | 2         | 3.33%   |
| 5.18.16-arch1-1        | 2         | 3.33%   |
| 5.12.7-arch1-1         | 2         | 3.33%   |
| 6.8.4-zen1-1-zen       | 1         | 1.67%   |
| 6.7.5-arch1-1          | 1         | 1.67%   |
| 6.6.8-arch1-1          | 1         | 1.67%   |
| 6.5.5-zen1-1-zen       | 1         | 1.67%   |
| 6.4.7-arch1-1          | 1         | 1.67%   |
| 6.4.4-zen1-1-zen       | 1         | 1.67%   |
| 6.4.4-arch1-1          | 1         | 1.67%   |
| 6.4.10-zen2-1-zen      | 1         | 1.67%   |
| 6.4.10-arch1-1         | 1         | 1.67%   |
| 6.4.1-arch2-1          | 1         | 1.67%   |
| 6.3.9-arch1-1          | 1         | 1.67%   |
| 6.3.7-arch1-1-vfio     | 1         | 1.67%   |
| 6.3.6-arch1-1          | 1         | 1.67%   |
| 6.2.8-zen1-1-zen       | 1         | 1.67%   |
| 6.2.2-arch1-1          | 1         | 1.67%   |
| 6.2.12-arch1-1         | 1         | 1.67%   |
| 6.17.9-arch1-1         | 1         | 1.67%   |
| 6.17.1-arch1-1         | 1         | 1.67%   |
| 6.15.8-zen1-1-zen      | 1         | 1.67%   |
| 6.12.9-zen1-1-zen      | 1         | 1.67%   |
| 6.11.2-arch1-1         | 1         | 1.67%   |
| 6.10.5-arch1-1         | 1         | 1.67%   |
| 6.1.7-arch1-1          | 1         | 1.67%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 1.67%   |
| 6.1.1-arch1-1          | 1         | 1.67%   |
| 6.0.7-arch1-1          | 1         | 1.67%   |
| 6.0.2-arch1-1          | 1         | 1.67%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 1.67%   |
| 5.19.7-arch1-1         | 1         | 1.67%   |
| 5.19.6-arch1-1         | 1         | 1.67%   |
| 5.19.3-arch1-1         | 1         | 1.67%   |
| 5.19.13-arch1-1        | 1         | 1.67%   |
| 5.18.6-arch1-1         | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.9.9   | 2         | 3.33%   |
| 6.9.1   | 2         | 3.33%   |
| 6.8.7   | 2         | 3.33%   |
| 6.6.10  | 2         | 3.33%   |
| 6.4.4   | 2         | 3.33%   |
| 6.4.10  | 2         | 3.33%   |
| 6.2.13  | 2         | 3.33%   |
| 5.18.16 | 2         | 3.33%   |
| 5.12.7  | 2         | 3.33%   |
| 6.8.4   | 1         | 1.67%   |
| 6.7.5   | 1         | 1.67%   |
| 6.6.8   | 1         | 1.67%   |
| 6.5.5   | 1         | 1.67%   |
| 6.4.7   | 1         | 1.67%   |
| 6.4.1   | 1         | 1.67%   |
| 6.3.9   | 1         | 1.67%   |
| 6.3.7   | 1         | 1.67%   |
| 6.3.6   | 1         | 1.67%   |
| 6.2.8   | 1         | 1.67%   |
| 6.2.2   | 1         | 1.67%   |
| 6.2.12  | 1         | 1.67%   |
| 6.17.9  | 1         | 1.67%   |
| 6.17.1  | 1         | 1.67%   |
| 6.15.8  | 1         | 1.67%   |
| 6.12.9  | 1         | 1.67%   |
| 6.11.2  | 1         | 1.67%   |
| 6.10.5  | 1         | 1.67%   |
| 6.1.7   | 1         | 1.67%   |
| 6.1.4   | 1         | 1.67%   |
| 6.1.1   | 1         | 1.67%   |
| 6.0.7   | 1         | 1.67%   |
| 6.0.2   | 1         | 1.67%   |
| 6.0.10  | 1         | 1.67%   |
| 5.19.7  | 1         | 1.67%   |
| 5.19.6  | 1         | 1.67%   |
| 5.19.3  | 1         | 1.67%   |
| 5.19.13 | 1         | 1.67%   |
| 5.18.6  | 1         | 1.67%   |
| 5.18.14 | 1         | 1.67%   |
| 5.17.9  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 5         | 8.62%   |
| 6.2     | 5         | 8.62%   |
| 6.9     | 4         | 6.9%    |
| 5.19    | 4         | 6.9%    |
| 5.18    | 4         | 6.9%    |
| 5.12    | 4         | 6.9%    |
| 6.8     | 3         | 5.17%   |
| 6.6     | 3         | 5.17%   |
| 6.3     | 3         | 5.17%   |
| 6.1     | 3         | 5.17%   |
| 6.0     | 3         | 5.17%   |
| 5.17    | 3         | 5.17%   |
| 5.16    | 3         | 5.17%   |
| 6.17    | 2         | 3.45%   |
| 6.7     | 1         | 1.72%   |
| 6.5     | 1         | 1.72%   |
| 6.15    | 1         | 1.72%   |
| 6.12    | 1         | 1.72%   |
| 6.11    | 1         | 1.72%   |
| 6.10    | 1         | 1.72%   |
| 5.15    | 1         | 1.72%   |
| 5.14    | 1         | 1.72%   |
| 5.10    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 56        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openbox  | 18        | 31.58%  |
| XFCE     | 16        | 28.07%  |
| bspwm    | 6         | 10.53%  |
| Hyprland | 4         | 7.02%   |
| GNOME    | 3         | 5.26%   |
| sway     | 2         | 3.51%   |
| KDE6     | 2         | 3.51%   |
| i3       | 2         | 3.51%   |
| xmonad   | 1         | 1.75%   |
| LXDE     | 1         | 1.75%   |
| dwm      | 1         | 1.75%   |
| Unknown  | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 49        | 85.96%  |
| Wayland | 7         | 12.28%  |
| Unknown | 1         | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 40        | 70.18%  |
| Unknown | 10        | 17.54%  |
| LXDM    | 5         | 8.77%   |
| Ly      | 1         | 1.75%   |
| LightDM | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 28        | 50%     |
| en_IN | 6         | 10.71%  |
| es_MX | 5         | 8.93%   |
| es_ES | 4         | 7.14%   |
| en_ZA | 2         | 3.57%   |
| en_SG | 2         | 3.57%   |
| en_GB | 2         | 3.57%   |
| tr_TR | 1         | 1.79%   |
| pl_PL | 1         | 1.79%   |
| it_IT | 1         | 1.79%   |
| fr_FR | 1         | 1.79%   |
| en_PH | 1         | 1.79%   |
| en_AU | 1         | 1.79%   |
| de_AT | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 73.21%  |
| BIOS | 15        | 26.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 45        | 80.36%  |
| Btrfs | 9         | 16.07%  |
| Xfs   | 1         | 1.79%   |
| Tmpfs | 1         | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 42        | 75%     |
| Unknown | 9         | 16.07%  |
| MBR     | 5         | 8.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 83.93%  |
| Yes       | 9         | 16.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 66.67%  |
| Yes       | 19        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 13        | 23.21%  |
| Dell                           | 9         | 16.07%  |
| MSI                            | 6         | 10.71%  |
| ASUSTek Computer               | 5         | 8.93%   |
| Lenovo                         | 3         | 5.36%   |
| HUAWEI                         | 3         | 5.36%   |
| Apple                          | 3         | 5.36%   |
| Google                         | 2         | 3.57%   |
| Acer                           | 2         | 3.57%   |
| Standard                       | 1         | 1.79%   |
| SmbiosType1_SystemManufacturer | 1         | 1.79%   |
| Positivo                       | 1         | 1.79%   |
| Packard Bell                   | 1         | 1.79%   |
| MouseComputer                  | 1         | 1.79%   |
| Infinix                        | 1         | 1.79%   |
| Framework                      | 1         | 1.79%   |
| eMachines                      | 1         | 1.79%   |
| Chuwi                          | 1         | 1.79%   |
| AXDIA International            | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| SmbiosType1_SystemManufacturer N20    | 1         | 1.79%   |
| Positivo CHT14B                       | 1         | 1.79%   |
| Packard Bell EasyNote TK85            | 1         | 1.79%   |
| MSI Thin GF63 12UDX                   | 1         | 1.79%   |
| MSI Katana GF66 11UE                  | 1         | 1.79%   |
| MSI GL65 Leopard 10SFK                | 1         | 1.79%   |
| MSI GF63 Thin 10SC                    | 1         | 1.79%   |
| MSI Bravo 15 A4DDR                    | 1         | 1.79%   |
| MSI Alpha 15 B5EEK                    | 1         | 1.79%   |
| MouseComputer EGPN711R307             | 1         | 1.79%   |
| Lenovo ThinkPad X280 20KFCTO1WW       | 1         | 1.79%   |
| Lenovo ThinkPad T430 2351AK9          | 1         | 1.79%   |
| Lenovo IdeaPad 3 15IGL05 81WQ         | 1         | 1.79%   |
| Infinix INBook X1 Pro                 | 1         | 1.79%   |
| HUAWEI NBD-WXX9                       | 1         | 1.79%   |
| HUAWEI HLYL-WXX9                      | 1         | 1.79%   |
| HUAWEI BOHB-WAX9                      | 1         | 1.79%   |
| HP Victus by Laptop 16-e0xxx          | 1         | 1.79%   |
| HP Stream Laptop 11-ak0xxx            | 1         | 1.79%   |
| HP Pavilion Notebook                  | 1         | 1.79%   |
| HP Pavilion Laptop 15-eh0xxx          | 1         | 1.79%   |
| HP Pavilion Laptop 15-cc1xx           | 1         | 1.79%   |
| HP Pavilion g4                        | 1         | 1.79%   |
| HP Notebook                           | 1         | 1.79%   |
| HP Laptop 15q-bu1xx                   | 1         | 1.79%   |
| HP Laptop 15-dy2xxx                   | 1         | 1.79%   |
| HP Laptop 15-dw0xxx                   | 1         | 1.79%   |
| HP Laptop 15-da0xxx                   | 1         | 1.79%   |
| HP InsydeH2O EFI BIOS                 | 1         | 1.79%   |
| HP Dragonfly 13.5 inch G4 Notebook PC | 1         | 1.79%   |
| Google Kindred                        | 1         | 1.79%   |
| Google Blorb                          | 1         | 1.79%   |
| Framework Laptop                      | 1         | 1.79%   |
| eMachines eME730                      | 1         | 1.79%   |
| Dell Vostro 3520                      | 1         | 1.79%   |
| Dell Vostro 3401                      | 1         | 1.79%   |
| Dell Latitude E7250                   | 1         | 1.79%   |
| Dell Latitude E6420                   | 1         | 1.79%   |
| Dell Latitude E5420                   | 1         | 1.79%   |
| Dell Latitude 7290                    | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Dell Latitude                      | 5         | 8.93%   |
| HP Pavilion                        | 4         | 7.14%   |
| HP Laptop                          | 4         | 7.14%   |
| Lenovo ThinkPad                    | 2         | 3.57%   |
| Dell Vostro                        | 2         | 3.57%   |
| Dell Inspiron                      | 2         | 3.57%   |
| ASUS ROG                           | 2         | 3.57%   |
| SmbiosType1_SystemManufacturer N20 | 1         | 1.79%   |
| Positivo CHT14B                    | 1         | 1.79%   |
| Packard Bell EasyNote              | 1         | 1.79%   |
| MSI Thin                           | 1         | 1.79%   |
| MSI Katana                         | 1         | 1.79%   |
| MSI GL65                           | 1         | 1.79%   |
| MSI GF63                           | 1         | 1.79%   |
| MSI Bravo                          | 1         | 1.79%   |
| MSI Alpha                          | 1         | 1.79%   |
| MouseComputer EGPN711R307          | 1         | 1.79%   |
| Lenovo IdeaPad                     | 1         | 1.79%   |
| Infinix INBook                     | 1         | 1.79%   |
| HUAWEI NBD-WXX9                    | 1         | 1.79%   |
| HUAWEI HLYL-WXX9                   | 1         | 1.79%   |
| HUAWEI BOHB-WAX9                   | 1         | 1.79%   |
| HP Victus                          | 1         | 1.79%   |
| HP Stream                          | 1         | 1.79%   |
| HP Notebook                        | 1         | 1.79%   |
| HP InsydeH2O                       | 1         | 1.79%   |
| HP Dragonfly                       | 1         | 1.79%   |
| Google Kindred                     | 1         | 1.79%   |
| Google Blorb                       | 1         | 1.79%   |
| Framework Laptop                   | 1         | 1.79%   |
| eMachines eME730                   | 1         | 1.79%   |
| Chuwi GemiBook                     | 1         | 1.79%   |
| AXDIA International WINPAD         | 1         | 1.79%   |
| ASUS Zephyrus                      | 1         | 1.79%   |
| ASUS X441SA                        | 1         | 1.79%   |
| ASUS ASUS                          | 1         | 1.79%   |
| Apple MacBookPro9                  | 1         | 1.79%   |
| Apple MacBookAir4                  | 1         | 1.79%   |
| Apple MacBook4                     | 1         | 1.79%   |
| Acer Swift                         | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 25%     |
| 2020 | 5         | 8.93%   |
| 2018 | 5         | 8.93%   |
| 2017 | 4         | 7.14%   |
| 2011 | 4         | 7.14%   |
| 2023 | 3         | 5.36%   |
| 2015 | 3         | 5.36%   |
| 2014 | 3         | 5.36%   |
| 2012 | 3         | 5.36%   |
| 2024 | 2         | 3.57%   |
| 2022 | 2         | 3.57%   |
| 2019 | 2         | 3.57%   |
| 2016 | 2         | 3.57%   |
| 2010 | 2         | 3.57%   |
| 2013 | 1         | 1.79%   |
| 2008 | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 56        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 56        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 96.43%  |
| Yes  | 2         | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 25%     |
| 16.01-24.0  | 11        | 19.64%  |
| 3.01-4.0    | 10        | 17.86%  |
| 8.01-16.0   | 10        | 17.86%  |
| 32.01-64.0  | 5         | 8.93%   |
| 1.01-2.0    | 3         | 5.36%   |
| 24.01-32.0  | 2         | 3.57%   |
| 64.01-256.0 | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 18        | 31.03%  |
| 2.01-3.0 | 14        | 24.14%  |
| 3.01-4.0 | 12        | 20.69%  |
| 4.01-8.0 | 10        | 17.24%  |
| 0.51-1.0 | 4         | 6.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 62.5%   |
| 2      | 18        | 32.14%  |
| 3      | 3         | 5.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 82.14%  |
| Yes       | 10        | 17.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 69.64%  |
| No        | 17        | 30.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 92.98%  |
| No        | 4         | 7.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 83.93%  |
| No        | 9         | 16.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| India              | 8         | 14.29%  |
| USA                | 7         | 12.5%   |
| Spain              | 4         | 7.14%   |
| Mexico             | 4         | 7.14%   |
| Uruguay            | 2         | 3.57%   |
| UK                 | 2         | 3.57%   |
| Turkey             | 2         | 3.57%   |
| South Africa       | 2         | 3.57%   |
| Russia             | 2         | 3.57%   |
| Malaysia           | 2         | 3.57%   |
| Italy              | 2         | 3.57%   |
| France             | 2         | 3.57%   |
| Brazil             | 2         | 3.57%   |
| Vietnam            | 1         | 1.79%   |
| Tunisia            | 1         | 1.79%   |
| Thailand           | 1         | 1.79%   |
| Philippines        | 1         | 1.79%   |
| Japan              | 1         | 1.79%   |
| Indonesia          | 1         | 1.79%   |
| Finland            | 1         | 1.79%   |
| Ethiopia           | 1         | 1.79%   |
| Dominican Republic | 1         | 1.79%   |
| Colombia           | 1         | 1.79%   |
| Chile              | 1         | 1.79%   |
| Belarus            | 1         | 1.79%   |
| Austria            | 1         | 1.79%   |
| Australia          | 1         | 1.79%   |
| Argentina          | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Seremban           | 2         | 3.45%   |
| New Delhi          | 2         | 3.45%   |
| Montevideo         | 2         | 3.45%   |
| Madrid             | 2         | 3.45%   |
| Cape Town          | 2         | 3.45%   |
| Yomitan            | 1         | 1.72%   |
| Welwyn Garden City | 1         | 1.72%   |
| Vienna             | 1         | 1.72%   |
| Valencia           | 1         | 1.72%   |
| Turin              | 1         | 1.72%   |
| Torreón           | 1         | 1.72%   |
| Tirunelveli        | 1         | 1.72%   |
| Sydney             | 1         | 1.72%   |
| Stevens Point      | 1         | 1.72%   |
| St Petersburg      | 1         | 1.72%   |
| Sousse             | 1         | 1.72%   |
| Sao Paulo          | 1         | 1.72%   |
| Santo Domingo Este | 1         | 1.72%   |
| Santiago           | 1         | 1.72%   |
| Santa Rosa         | 1         | 1.72%   |
| Rocca di Papa      | 1         | 1.72%   |
| Pune               | 1         | 1.72%   |
| Monterrey          | 1         | 1.72%   |
| Minsk              | 1         | 1.72%   |
| Mazatlán          | 1         | 1.72%   |
| Mar del Plata      | 1         | 1.72%   |
| Mangalore          | 1         | 1.72%   |
| Malang             | 1         | 1.72%   |
| Loskutova          | 1         | 1.72%   |
| London             | 1         | 1.72%   |
| Leander            | 1         | 1.72%   |
| Lannion            | 1         | 1.72%   |
| Kansas City        | 1         | 1.72%   |
| Jorge Negrete      | 1         | 1.72%   |
| Istanbul           | 1         | 1.72%   |
| Hyderabad          | 1         | 1.72%   |
| Huntersville       | 1         | 1.72%   |
| Helsinki           | 1         | 1.72%   |
| Hanoi              | 1         | 1.72%   |
| Gebze              | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 8         | 14     | 10.67%  |
| WDC                         | 7         | 7      | 9.33%   |
| Samsung Electronics         | 7         | 8      | 9.33%   |
| Sandisk                     | 5         | 6      | 6.67%   |
| Seagate                     | 3         | 4      | 4%      |
| Phison Electronics          | 3         | 3      | 4%      |
| Micron Technology           | 3         | 3      | 4%      |
| KIOXIA                      | 3         | 3      | 4%      |
| Toshiba                     | 2         | 2      | 2.67%   |
| SK hynix                    | 2         | 2      | 2.67%   |
| Micron/Crucial Technology   | 2         | 2      | 2.67%   |
| Kingston Technology Company | 2         | 3      | 2.67%   |
| Kingston                    | 2         | 2      | 2.67%   |
| Intel                       | 2         | 2      | 2.67%   |
| Hitachi                     | 2         | 2      | 2.67%   |
| Crucial                     | 2         | 2      | 2.67%   |
| Apple                       | 2         | 2      | 2.67%   |
| Unknown                     | 2         | 2      | 2.67%   |
| Yangtze Memory Technologies | 1         | 1      | 1.33%   |
| SPCC                        | 1         | 1      | 1.33%   |
| Solid State Storage         | 1         | 1      | 1.33%   |
| Realtek Semiconductor       | 1         | 1      | 1.33%   |
| Phison                      | 1         | 1      | 1.33%   |
| Patriot                     | 1         | 1      | 1.33%   |
| Netac                       | 1         | 1      | 1.33%   |
| Mushkin                     | 1         | 2      | 1.33%   |
| KingFast                    | 1         | 2      | 1.33%   |
| Initio                      | 1         | 1      | 1.33%   |
| Hjwdz                       | 1         | 1      | 1.33%   |
| HGST                        | 1         | 1      | 1.33%   |
| Gigabyte Technology         | 1         | 2      | 1.33%   |
| Fanxiang                    | 1         | 1      | 1.33%   |
| EVM                         | 1         | 1      | 1.33%   |
| ADATA Technology            | 1         | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                               | 3         | 3.7%    |
| Unknown MMC Card  64GB                               | 2         | 2.47%   |
| Seagate ST500LM030-2E717D 500GB                      | 2         | 2.47%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 2         | 2.47%   |
| Unknown                                              | 2         | 2.47%   |
| Yangtze Memory YMTC PC005 256GB                      | 1         | 1.23%   |
| WDC WDS500G2B0C-00PXH0 500GB                         | 1         | 1.23%   |
| WDC WDS500G2B0A-00SM50 500GB                         | 1         | 1.23%   |
| WDC WD10SPZX-75Z10T3 1TB                             | 1         | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 1.23%   |
| WDC WD10SPZX-24Z10T0 1TB                             | 1         | 1.23%   |
| WDC WD10SPCX-60KHST0 1TB                             | 1         | 1.23%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 1         | 1.23%   |
| Unknown SD/MMC/MS PRO 2GB                            | 1         | 1.23%   |
| Unknown SC128  128GB                                 | 1         | 1.23%   |
| Unknown MMC Card  16GB                               | 1         | 1.23%   |
| Unknown MMC Card  128GB                              | 1         | 1.23%   |
| Unknown Essentiel B 1TB                              | 1         | 1.23%   |
| Toshiba MQ01ABF050 500GB                             | 1         | 1.23%   |
| Toshiba MQ01ABD100 1TB                               | 1         | 1.23%   |
| SPCC Solid State Disk 128GB                          | 1         | 1.23%   |
| Solid State Storage SSSTC CL1-4D256 256GB            | 1         | 1.23%   |
| SK hynix NVMe SSD Drive 128GB                        | 1         | 1.23%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                | 1         | 1.23%   |
| Seagate ST1000LM048-2E7172 1TB                       | 1         | 1.23%   |
| Seagate Expansion 2TB                                | 1         | 1.23%   |
| Sandisk WD_BLACK SN770 1TB                           | 1         | 1.23%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB          | 1         | 1.23%   |
| Sandisk WD Blue SN570 1TB                            | 1         | 1.23%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 1         | 1.23%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB      | 1         | 1.23%   |
| Sandisk PC SN530 NVMe WDC 256GB                      | 1         | 1.23%   |
| Samsung SSD PM871 mSATA 256GB                        | 1         | 1.23%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 1         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less) 256GB    | 1         | 1.23%   |
| Samsung MZVLQ512HBLU-00B00 512GB                     | 1         | 1.23%   |
| Samsung MZVL4512HBLU-00BTW 512GB                     | 1         | 1.23%   |
| Realtek Teclast BD 512GB SSD                         | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 29.41%  |
| Seagate | 3         | 4      | 17.65%  |
| Unknown | 2         | 3      | 11.76%  |
| Toshiba | 2         | 2      | 11.76%  |
| Hitachi | 2         | 2      | 11.76%  |
| Initio  | 1         | 1      | 5.88%   |
| HGST    | 1         | 1      | 5.88%   |
| Apple   | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 12.5%   |
| Unknown             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| SPCC                | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Patriot             | 1         | 1      | 6.25%   |
| Netac               | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Gigabyte Technology | 1         | 2      | 6.25%   |
| Fanxiang            | 1         | 1      | 6.25%   |
| EVM                 | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |
| Apple               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 38     | 42.25%  |
| SSD     | 16        | 17     | 22.54%  |
| HDD     | 16        | 19     | 22.54%  |
| MMC     | 7         | 11     | 9.86%   |
| Unknown | 2         | 3      | 2.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 30        | 38     | 43.48%  |
| SATA | 27        | 33     | 39.13%  |
| MMC  | 7         | 11     | 10.14%  |
| SAS  | 5         | 6      | 7.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 20     | 54.55%  |
| 0.51-1.0   | 12        | 13     | 36.36%  |
| 1.01-2.0   | 3         | 3      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 28.57%  |
| 101-250        | 14        | 25%     |
| 501-1000       | 10        | 17.86%  |
| 1001-2000      | 5         | 8.93%   |
| More than 3000 | 3         | 5.36%   |
| 21-50          | 3         | 5.36%   |
| 51-100         | 3         | 5.36%   |
| Unknown        | 2         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 18        | 31.03%  |
| 1-20     | 14        | 24.14%  |
| 51-100   | 9         | 15.52%  |
| 251-500  | 7         | 12.07%  |
| 101-250  | 5         | 8.62%   |
| 501-1000 | 3         | 5.17%   |
| Unknown  | 2         | 3.45%   |

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
| Works    | 40        | 53     | 65.57%  |
| Detected | 18        | 32     | 29.51%  |
| Malfunc  | 3         | 3      | 4.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 37        | 53.62%  |
| SanDisk                        | 5         | 7.25%   |
| Samsung Electronics            | 5         | 7.25%   |
| Phison Electronics             | 3         | 4.35%   |
| Micron/Crucial Technology      | 3         | 4.35%   |
| Micron Technology              | 3         | 4.35%   |
| KIOXIA                         | 3         | 4.35%   |
| Kingston Technology Company    | 3         | 4.35%   |
| Yangtze Memory Technologies    | 1         | 1.45%   |
| Solid State Storage Technology | 1         | 1.45%   |
| SK hynix                       | 1         | 1.45%   |
| Silicon Motion                 | 1         | 1.45%   |
| Realtek Semiconductor          | 1         | 1.45%   |
| AMD                            | 1         | 1.45%   |
| ADATA Technology               | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 6         | 8.11%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 3         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.05%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 2         | 2.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 2         | 2.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 2         | 2.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 2         | 2.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 2.7%    |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 2.7%    |
| Intel Alder Lake-P SATA AHCI Controller                                      | 2         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 2.7%    |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 1.35%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 1.35%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 1.35%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 1.35%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                 | 1         | 1.35%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 1.35%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                        | 1         | 1.35%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                    | 1         | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 1.35%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 1.35%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 1.35%   |
| Phison E18 PCIe4 NVMe Controller                                             | 1         | 1.35%   |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 1.35%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                         | 1         | 1.35%   |
| Micron 2550 NVMe SSD (DRAM-less)                                             | 1         | 1.35%   |
| Micron 2500 NVMe SSD (DRAM-less)                                             | 1         | 1.35%   |
| Micron 2300 NVMe SSD [Santana]                                               | 1         | 1.35%   |
| KIOXIA NVMe SSD Controller XG8                                               | 1         | 1.35%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 1         | 1.35%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 1.35%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 44.12%  |
| NVMe | 29        | 42.65%  |
| RAID | 8         | 11.76%  |
| IDE  | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 82.14%  |
| AMD    | 10        | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 5.36%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 5.36%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 5.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 3.57%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1.79%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 1.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.79%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 1         | 1.79%   |
| Intel Core i5-2467M CPU @ 1.60GHz       | 1         | 1.79%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 1.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.79%   |
| Intel Core i5 CPU M 450 @ 2.40GHz       | 1         | 1.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.79%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.79%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 1         | 1.79%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 1         | 1.79%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 1         | 1.79%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 1         | 1.79%   |
| Intel Celeron N5095 @ 2.00GHz           | 1         | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 1         | 1.79%   |
| Intel Celeron 2957U @ 1.40GHz           | 1         | 1.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 1         | 1.79%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 1         | 1.79%   |
| Intel 13th Gen Core i7-1355U            | 1         | 1.79%   |
| Intel 12th Gen Core i7-12650H           | 1         | 1.79%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.79%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 25%     |
| Other            | 10        | 17.86%  |
| Intel Core i7    | 7         | 12.5%   |
| Intel Celeron    | 7         | 12.5%   |
| Intel Core i3    | 5         | 8.93%   |
| AMD Ryzen 5      | 4         | 7.14%   |
| AMD Ryzen 7      | 3         | 5.36%   |
| Intel Atom       | 2         | 3.57%   |
| Intel Pentium    | 1         | 1.79%   |
| Intel Core 2 Duo | 1         | 1.79%   |
| AMD Ryzen 9      | 1         | 1.79%   |
| AMD A4           | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 41.07%  |
| 4      | 18        | 32.14%  |
| 8      | 6         | 10.71%  |
| 6      | 5         | 8.93%   |
| 10     | 3         | 5.36%   |
| 12     | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 43        | 76.79%  |
| 1      | 13        | 23.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 61.4%   |
| 0x706a8    | 3         | 5.26%   |
| 0xa0652    | 2         | 3.51%   |
| 0x806d1    | 2         | 3.51%   |
| 0x206a7    | 2         | 3.51%   |
| 0x806ec    | 1         | 1.75%   |
| 0x806ea    | 1         | 1.75%   |
| 0x506e3    | 1         | 1.75%   |
| 0x506c9    | 1         | 1.75%   |
| 0x406c4    | 1         | 1.75%   |
| 0x40651    | 1         | 1.75%   |
| 0x306d4    | 1         | 1.75%   |
| 0x306a9    | 1         | 1.75%   |
| 0x0a50000c | 1         | 1.75%   |
| 0x0a404102 | 1         | 1.75%   |
| 0x08600106 | 1         | 1.75%   |
| 0x08600104 | 1         | 1.75%   |
| 0x03000027 | 1         | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 17.86%  |
| IceLake          | 5         | 8.93%   |
| Goldmont plus    | 4         | 7.14%   |
| Zen 3            | 3         | 5.36%   |
| Zen 2            | 3         | 5.36%   |
| TigerLake        | 3         | 5.36%   |
| Silvermont       | 3         | 5.36%   |
| SandyBridge      | 3         | 5.36%   |
| Broadwell        | 3         | 5.36%   |
| Unknown          | 3         | 5.36%   |
| Westmere         | 2         | 3.57%   |
| IvyBridge        | 2         | 3.57%   |
| Haswell          | 2         | 3.57%   |
| CometLake        | 2         | 3.57%   |
| Alderlake Hybrid | 2         | 3.57%   |
| Zen+             | 1         | 1.79%   |
| Tremont          | 1         | 1.79%   |
| Skylake          | 1         | 1.79%   |
| Penryn           | 1         | 1.79%   |
| K10 Llano        | 1         | 1.79%   |
| Goldmont         | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 62.5%   |
| Nvidia | 14        | 19.44%  |
| AMD    | 13        | 18.06%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 6.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 5.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 3.95%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.95%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 3.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 3.95%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 2.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.63%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 2.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.32%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.32%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.32%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.32%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.32%   |
| Nvidia GA107BM / GN20-P0-R-K2 [GeForce RTX 3050 6GB Laptop GPU]                          | 1         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.32%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.32%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 1         | 1.32%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.32%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.32%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.32%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.32%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1.32%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 57.14%  |
| Intel + Nvidia | 11        | 19.64%  |
| 1 x AMD        | 5         | 8.93%   |
| 2 x AMD        | 3         | 5.36%   |
| AMD + Nvidia   | 3         | 5.36%   |
| Intel + AMD    | 2         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 45        | 80.36%  |
| Proprietary | 10        | 17.86%  |
| Unknown     | 1         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 80.36%  |
| 0.01-0.5   | 7         | 12.5%   |
| 7.01-8.0   | 1         | 1.79%   |
| 5.01-6.0   | 1         | 1.79%   |
| 3.01-4.0   | 1         | 1.79%   |
| 8.01-16.0  | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 12        | 18.46%  |
| AU Optronics        | 11        | 16.92%  |
| BOE                 | 10        | 15.38%  |
| Samsung Electronics | 6         | 9.23%   |
| LG Display          | 6         | 9.23%   |
| PANDA               | 4         | 6.15%   |
| Apple               | 3         | 4.62%   |
| Sharp               | 2         | 3.08%   |
| Dell                | 2         | 3.08%   |
| Mi                  | 1         | 1.54%   |
| Lenovo              | 1         | 1.54%   |
| JPN                 | 1         | 1.54%   |
| JLK                 | 1         | 1.54%   |
| InfoVision          | 1         | 1.54%   |
| HKC                 | 1         | 1.54%   |
| HJC                 | 1         | 1.54%   |
| ASUSTek Computer    | 1         | 1.54%   |
| AOC                 | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 2         | 3.08%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch            | 2         | 3.08%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 3.08%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch         | 2         | 3.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 3.08%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 2         | 3.08%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 1.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 1.54%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch   | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch   | 1         | 1.54%   |
| Samsung Electronics ATNA60CL10-0 SDC41AF 2880x1800 344x215mm 16.0-inch | 1         | 1.54%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch                | 1         | 1.54%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 1         | 1.54%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                       | 1         | 1.54%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch           | 1         | 1.54%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch            | 1         | 1.54%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch                | 1         | 1.54%   |
| JPN IPS245FHDR165 JPN2500 1920x1080 552x314mm 25.0-inch                | 1         | 1.54%   |
| JLK F32FR1K-17B JLK3251 1920x1080 544x303mm 24.5-inch                  | 1         | 1.54%   |
| InfoVision LCD Monitor IVO34D1 1920x1280 285x190mm 13.5-inch           | 1         | 1.54%   |
| HKC GM27X5QIPS HKC0027 2560x1440 597x336mm 27.0-inch                   | 1         | 1.54%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                  | 1         | 1.54%   |
| Dell P2319H DELD0D7 1920x1080 509x286mm 23.0-inch                      | 1         | 1.54%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                    | 1         | 1.54%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN161A 1920x1080 355x199mm 16.0-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch        | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch       | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1246 1920x1080 276x155mm 12.5-inch       | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 28        | 46.67%  |
| 1366x768 (WXGA)  | 18        | 30%     |
| 2560x1440 (QHD)  | 3         | 5%      |
| 2256x1504        | 2         | 3.33%   |
| 1280x800 (WXGA)  | 2         | 3.33%   |
| 3840x2160 (4K)   | 1         | 1.67%   |
| 3440x1440        | 1         | 1.67%   |
| 2880x1800        | 1         | 1.67%   |
| 2160x1440        | 1         | 1.67%   |
| 1920x1280        | 1         | 1.67%   |
| 1600x900 (HD+)   | 1         | 1.67%   |
| 1440x900 (WXGA+) | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 41.54%  |
| 13     | 10        | 15.38%  |
| 14     | 7         | 10.77%  |
| 24     | 5         | 7.69%   |
| 16     | 3         | 4.62%   |
| 12     | 3         | 4.62%   |
| 27     | 2         | 3.08%   |
| 23     | 2         | 3.08%   |
| 11     | 2         | 3.08%   |
| 34     | 1         | 1.54%   |
| 25     | 1         | 1.54%   |
| 21     | 1         | 1.54%   |
| 19     | 1         | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 59.38%  |
| 201-300     | 12        | 18.75%  |
| 501-600     | 8         | 12.5%   |
| 401-500     | 2         | 3.13%   |
| 351-400     | 2         | 3.13%   |
| 701-800     | 1         | 1.56%   |
| 601-700     | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 83.93%  |
| 3/2   | 4         | 7.14%   |
| 16/10 | 4         | 7.14%   |
| 21/9  | 1         | 1.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 44.62%  |
| 81-90          | 16        | 24.62%  |
| 201-250        | 5         | 7.69%   |
| 251-300        | 4         | 6.15%   |
| 61-70          | 3         | 4.62%   |
| 51-60          | 2         | 3.08%   |
| 301-350        | 2         | 3.08%   |
| 71-80          | 1         | 1.54%   |
| 351-500        | 1         | 1.54%   |
| 151-200        | 1         | 1.54%   |
| 111-120        | 1         | 1.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 29        | 45.31%  |
| 101-120 | 18        | 28.13%  |
| 51-100  | 9         | 14.06%  |
| 161-240 | 8         | 12.5%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 82.14%  |
| 2     | 9         | 16.07%  |
| 3     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 41.46%  |
| Intel                    | 25        | 30.49%  |
| Qualcomm Atheros         | 5         | 6.1%    |
| MediaTek                 | 5         | 6.1%    |
| Broadcom                 | 5         | 6.1%    |
| Ralink Technology        | 3         | 3.66%   |
| TP-Link                  | 1         | 1.22%   |
| Marvell Technology Group | 1         | 1.22%   |
| DisplayLink              | 1         | 1.22%   |
| Broadcom Limited         | 1         | 1.22%   |
| ASIX Electronics         | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 18        | 18%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 7         | 7%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 5         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                               | 3         | 3%      |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 3         | 3%      |
| Intel Ethernet Connection (4) I219-LM                                           | 3         | 3%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 2         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 2         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 2         | 2%      |
| Realtek 802.11ac NIC                                                            | 2         | 2%      |
| Ralink MT7601U Wireless Adapter                                                 | 2         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 2         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 2         | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 2         | 2%      |
| Intel Wireless 8265 / 8275                                                      | 2         | 2%      |
| Intel Wireless 7265                                                             | 2         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                                 | 2         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 2         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 2         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                                  | 2         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 2         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 2         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                 | 2         | 2%      |
| TP-Link 802.11ac WLAN Adapter                                                   | 1         | 1%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 1         | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 1         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                                      | 1         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 1         | 1%      |
| Ralink RT5572 Wireless Adapter                                                  | 1         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 1         | 1%      |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 1         | 1%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 1         | 1%      |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 1         | 1%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                         | 1         | 1%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 1         | 1%      |
| Intel Wi-Fi 6 AX201                                                             | 1         | 1%      |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 1         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 1         | 1%      |
| Intel Ethernet Controller I225-V                                                | 1         | 1%      |
| Intel Ethernet Connection (3) I218-LM                                           | 1         | 1%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 39.29%  |
| Realtek Semiconductor | 16        | 28.57%  |
| Qualcomm Atheros      | 5         | 8.93%   |
| MediaTek              | 5         | 8.93%   |
| Broadcom              | 4         | 7.14%   |
| Ralink Technology     | 3         | 5.36%   |
| TP-Link               | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 7         | 12.28%  |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 3         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 2         | 3.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 2         | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 2         | 3.51%   |
| Realtek 802.11ac NIC                                                            | 2         | 3.51%   |
| Ralink MT7601U Wireless Adapter                                                 | 2         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 2         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 2         | 3.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 2         | 3.51%   |
| Intel Wireless 8265 / 8275                                                      | 2         | 3.51%   |
| Intel Wireless 7265                                                             | 2         | 3.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                                 | 2         | 3.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 2         | 3.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 2         | 3.51%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 2         | 3.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 2         | 3.51%   |
| TP-Link 802.11ac WLAN Adapter                                                   | 1         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 1         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                                      | 1         | 1.75%   |
| Ralink RT5572 Wireless Adapter                                                  | 1         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 1         | 1.75%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 1         | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 1         | 1.75%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 1         | 1.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                             | 1         | 1.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 1         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                                  | 1         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                                  | 1         | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                                   | 1         | 1.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                                 | 1         | 1.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                                  | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 64.29%  |
| Intel                    | 8         | 19.05%  |
| Broadcom                 | 3         | 7.14%   |
| Marvell Technology Group | 1         | 2.38%   |
| DisplayLink              | 1         | 2.38%   |
| Broadcom Limited         | 1         | 2.38%   |
| ASIX Electronics         | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 18        | 41.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 11.63%  |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 6.98%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 6.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 4.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 2.33%   |
| Intel Ethernet Controller I225-V                                       | 1         | 2.33%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 2.33%   |
| DisplayLink USB3 to HDMI                                               | 1         | 2.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 2.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 2.33%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 58.24%  |
| Ethernet | 38        | 41.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 82.46%  |
| Ethernet | 10        | 17.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 62.5%   |
| 1     | 19        | 33.93%  |
| 0     | 2         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 66.07%  |
| Yes  | 19        | 33.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 43.48%  |
| Realtek Semiconductor           | 10        | 21.74%  |
| Qualcomm Atheros Communications | 3         | 6.52%   |
| IMC Networks                    | 3         | 6.52%   |
| Apple                           | 3         | 6.52%   |
| MediaTek                        | 2         | 4.35%   |
| Realtek                         | 1         | 2.17%   |
| Lite-On Technology              | 1         | 2.17%   |
| Foxconn / Hon Hai               | 1         | 2.17%   |
| Cambridge Silicon Radio         | 1         | 2.17%   |
| Broadcom                        | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 9         | 19.57%  |
| Realtek Bluetooth Radio                             | 7         | 15.22%  |
| Intel Bluetooth wireless interface                  | 4         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.52%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 4.35%   |
| MediaTek Wireless_Device                            | 2         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.35%   |
| Realtek Bluetooth Radio                             | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.17%   |
| Intel Bluetooth Device                              | 1         | 2.17%   |
| Intel AX210 Bluetooth                               | 1         | 2.17%   |
| IMC Networks Wireless_Device                        | 1         | 2.17%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.17%   |
| IMC Networks Bluetooth Device                       | 1         | 2.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 2.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.17%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.17%   |
| Apple Bluetooth HCI                                 | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 44        | 67.69%  |
| AMD                                          | 11        | 16.92%  |
| Nvidia                                       | 8         | 12.31%  |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.54%   |
| Logitech                                     | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 9         | 11.39%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 8.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.06%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 4         | 5.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 3.8%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.8%    |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 2.53%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.53%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 2.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.53%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.53%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 2.53%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Logitech Logitech G PRO X Gaming Headset                                                          | 1         | 1.27%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 1.27%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.27%   |
| AMD Radeon High Definition Audio Controller                                                       | 1         | 1.27%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 1.27%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 23.21%  |
| Micron Technology   | 10        | 17.86%  |
| SK hynix            | 9         | 16.07%  |
| Kingston            | 9         | 16.07%  |
| Crucial             | 5         | 8.93%   |
| Unknown             | 2         | 3.57%   |
| Unknown (ABCD)      | 1         | 1.79%   |
| Teclast             | 1         | 1.79%   |
| Nanya Technology    | 1         | 1.79%   |
| ff                  | 1         | 1.79%   |
| ChangXin Memory     | 1         | 1.79%   |
| A-DATA Technology   | 1         | 1.79%   |
| 4ea5                | 1         | 1.79%   |
| Unknown             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 3.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.39%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 3.39%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.69%   |
| Teclast RAM YTD48G26N10 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.69%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.69%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 1.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.69%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 1         | 1.69%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.69%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.69%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 1.69%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 1.69%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.69%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GiB SODIMM LPDDR5 7500MT/s      | 1         | 1.69%   |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s                 | 1         | 1.69%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 1.69%   |
| Micron RAM K4A8G165WB-BCRC 2GB Row Of Chips LPDDR4 3333MT/s      | 1         | 1.69%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 51.02%  |
| DDR3   | 15        | 30.61%  |
| LPDDR4 | 4         | 8.16%   |
| LPDDR5 | 2         | 4.08%   |
| SDRAM  | 1         | 2.04%   |
| DDR5   | 1         | 2.04%   |
| DDR2   | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 85.11%  |
| Row Of Chips | 6         | 12.77%  |
| Unknown      | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 44.23%  |
| 4096  | 10        | 19.23%  |
| 16384 | 7         | 13.46%  |
| 2048  | 6         | 11.54%  |
| 32768 | 3         | 5.77%   |
| 1024  | 3         | 5.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 12        | 22.64%  |
| 1600  | 10        | 18.87%  |
| 2667  | 8         | 15.09%  |
| 2400  | 5         | 9.43%   |
| 1333  | 4         | 7.55%   |
| 2933  | 2         | 3.77%   |
| 8400  | 1         | 1.89%   |
| 7500  | 1         | 1.89%   |
| 6400  | 1         | 1.89%   |
| 4800  | 1         | 1.89%   |
| 4199  | 1         | 1.89%   |
| 3733  | 1         | 1.89%   |
| 3333  | 1         | 1.89%   |
| 2133  | 1         | 1.89%   |
| 1866  | 1         | 1.89%   |
| 1334  | 1         | 1.89%   |
| 1067  | 1         | 1.89%   |
| 667   | 1         | 1.89%   |

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
| Chicony Electronics                    | 12        | 27.91%  |
| Microdia                               | 5         | 11.63%  |
| Quanta                                 | 4         | 9.3%    |
| IMC Networks                           | 3         | 6.98%   |
| Bison Electronics                      | 3         | 6.98%   |
| Apple                                  | 3         | 6.98%   |
| Suyin                                  | 2         | 4.65%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Realtek Semiconductor                  | 2         | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.65%   |
| Shinetech                              | 1         | 2.33%   |
| Ricoh                                  | 1         | 2.33%   |
| Luxvisions Innotech Limited            | 1         | 2.33%   |
| Lite-On Technology                     | 1         | 2.33%   |
| Alcor Micro                            | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 4         | 9.3%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 2         | 4.65%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 4.65%   |
| Quanta ov9734_techfront_camera                                  | 2         | 4.65%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 4.65%   |
| Chicony Integrated IR Camera                                    | 2         | 4.65%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 4.65%   |
| Chicony HP Truevision HD                                        | 2         | 4.65%   |
| Chicony HD WebCam                                               | 2         | 4.65%   |
| Chicony HD User Facing                                          | 2         | 4.65%   |
| Bison HD Webcam                                                 | 2         | 4.65%   |
| Shinetech ASUS FHD webcam                                       | 1         | 2.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 2.33%   |
| Realtek HP Webcam                                               | 1         | 2.33%   |
| Realtek HD Webcam - Realtek                                     | 1         | 2.33%   |
| Microdia Webcam Vitade AF                                       | 1         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 2.33%   |
| Lite-On Integrated Camera                                       | 1         | 2.33%   |
| IMC Networks Integrated Camera                                  | 1         | 2.33%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 2.33%   |
| IMC Networks HD Camera                                          | 1         | 2.33%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 2.33%   |
| Chicony USB 2.0 Webcam Device                                   | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 2.33%   |
| Bison Integrated Camera                                         | 1         | 2.33%   |
| Apple FaceTime HD Camera                                        | 1         | 2.33%   |
| Apple FaceTime Camera                                           | 1         | 2.33%   |
| Apple Built-in iSight [Micron]                                  | 1         | 2.33%   |
| Alcor Micro USB 2.0 Camera                                      | 1         | 2.33%   |

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
| 0     | 43        | 76.79%  |
| 1     | 11        | 19.64%  |
| 2     | 2         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 31.25%  |
| Graphics card         | 3         | 18.75%  |
| Storage               | 2         | 12.5%   |
| Net/wireless          | 2         | 12.5%   |
| Multimedia controller | 2         | 12.5%   |
| Chipcard              | 2         | 12.5%   |

