BigLinux - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for BigLinux.

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

Total: 89

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b81a572516](https://linux-hardware.org/?probe=b81a572516) | May 09, 2024 |
| MSI           | Cyborg 15 A12VF             | [1168634a54](https://linux-hardware.org/?probe=1168634a54) | May 06, 2024 |
| Itautec       | Itautec                     | [cb012e89fc](https://linux-hardware.org/?probe=cb012e89fc) | May 06, 2024 |
| Itautec       | Itautec                     | [e1d6b279b9](https://linux-hardware.org/?probe=e1d6b279b9) | May 06, 2024 |
| HP            | Victus by Gaming Laptop     | [7178fbf1eb](https://linux-hardware.org/?probe=7178fbf1eb) | Apr 23, 2024 |
| HP            | EliteBook Folio 9470m       | [72485d4ec0](https://linux-hardware.org/?probe=72485d4ec0) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [96271e0269](https://linux-hardware.org/?probe=96271e0269) | Apr 10, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [4fc00ab41f](https://linux-hardware.org/?probe=4fc00ab41f) | Apr 01, 2024 |
| Google        | Blooguard                   | [6c7218afa7](https://linux-hardware.org/?probe=6c7218afa7) | Mar 27, 2024 |
| Google        | Blooguard                   | [583f5aada6](https://linux-hardware.org/?probe=583f5aada6) | Mar 25, 2024 |
| ASUSTek       | X541SA                      | [4f1901506d](https://linux-hardware.org/?probe=4f1901506d) | Mar 22, 2024 |
| HP            | ENVY TS m7                  | [2b3732863e](https://linux-hardware.org/?probe=2b3732863e) | Mar 21, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [e660816556](https://linux-hardware.org/?probe=e660816556) | Mar 20, 2024 |
| HP            | Laptop 15-bs1xx             | [fa1b40fdce](https://linux-hardware.org/?probe=fa1b40fdce) | Mar 17, 2024 |
| Apple         | MacBookPro5,5               | [73b6e42771](https://linux-hardware.org/?probe=73b6e42771) | Mar 16, 2024 |
| Apple         | MacBookPro14,1              | [ad99c77be4](https://linux-hardware.org/?probe=ad99c77be4) | Mar 13, 2024 |
| Acer          | TravelMate 5740             | [b1366802c6](https://linux-hardware.org/?probe=b1366802c6) | Mar 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [270dd04b52](https://linux-hardware.org/?probe=270dd04b52) | Feb 28, 2024 |
| Acer          | Aspire E5-575G              | [3790ad9e05](https://linux-hardware.org/?probe=3790ad9e05) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [975b3a3b77](https://linux-hardware.org/?probe=975b3a3b77) | Feb 05, 2024 |
| Lenovo        | G50-80 80R0                 | [980165425e](https://linux-hardware.org/?probe=980165425e) | Jan 27, 2024 |
| Lenovo        | G50-80 80R0                 | [eeee227df0](https://linux-hardware.org/?probe=eeee227df0) | Jan 26, 2024 |
| Samsung       | 550XCJ/550XCR               | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| Acer          | Nitro AN515-51              | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| Toshiba       | IS 1412                     | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| HP            | 255 G6 Notebook PC          | [626135b546](https://linux-hardware.org/?probe=626135b546) | Dec 04, 2023 |
| Acer          | Aspire V5-472               | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | [561cad738d](https://linux-hardware.org/?probe=561cad738d) | Dec 02, 2023 |
| Unknown       | Unknown                     | [ecae393240](https://linux-hardware.org/?probe=ecae393240) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | [c5dd65037d](https://linux-hardware.org/?probe=c5dd65037d) | Nov 29, 2023 |
| Positivo      | C41TF                       | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| Dell          | Inspiron N5010              | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| HP            | Pavilion g4                 | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3113cdd229](https://linux-hardware.org/?probe=3113cdd229) | Nov 11, 2023 |
| Positivo      | C41TF                       | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Acer          | Aspire A315-42G             | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Acer          | Nitro AN515-51              | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [673113259c](https://linux-hardware.org/?probe=673113259c) | Oct 14, 2023 |
| Acer          | Nitro AN515-47              | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| HP            | ZBook 15 G3                 | [cd9071e2ad](https://linux-hardware.org/?probe=cd9071e2ad) | Oct 12, 2023 |
| Dell          | Latitude E6420              | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Dell          | Latitude E6420              | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Acer          | Aspire E5-411G              | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| ASUSTek       | X455LA                      | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| HP            | EliteBook 8760w             | [30ea6db008](https://linux-hardware.org/?probe=30ea6db008) | Jul 23, 2023 |
| Multilaser    | MLSH1H LINUX                | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| ASUSTek       | VX7SX                       | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Positivo      | Q464B                       | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Multilaser    | MLSH1H LINUX                | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Apple         | MacBookPro9,2               | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Samsung       | 300E5M/300E5L               | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Dell          | Inspiron 7460               | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| Dell          | G15 5520                    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| Acer          | Nitro AN517-54              | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| Clevo         | W340EU                      | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Avell High... | STORM TWO                   | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| Acer          | Aspire A315-53              | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| HP            | 255 G7 Notebook PC          | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| Toshiba       | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| Toshiba       | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | System XPS L502X            | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| ASUSTek       | X45U                        | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| Positivo      | C14RV01                     | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Sony          | VGN-NR230AE                 | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| Positivo      | C14RV01                     | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| Acer          | Predator G9-793             | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | System Inspiron N7110       | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| Acer          | Predator G9-793             | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Dell          | System Inspiron N7110       | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| Positivo      | C14RV01                     | [36efae3128](https://linux-hardware.org/?probe=36efae3128) | Feb 03, 2021 |
| Acer          | A315-41                     | [021dc9110e](https://linux-hardware.org/?probe=021dc9110e) | Nov 11, 2020 |
| Lenovo        | ThinkPad T410 25379N2       | [ed777f25b7](https://linux-hardware.org/?probe=ed777f25b7) | Nov 09, 2020 |
| Dell          | Inspiron 3480               | [1f0823c074](https://linux-hardware.org/?probe=1f0823c074) | Oct 13, 2020 |
| Acer          | Aspire A515-51G             | [8b89f99351](https://linux-hardware.org/?probe=8b89f99351) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | [07fb6950a2](https://linux-hardware.org/?probe=07fb6950a2) | Jul 11, 2020 |
| Lenovo        | IdeaPad Z470                | [3a8f141df4](https://linux-hardware.org/?probe=3a8f141df4) | Mar 28, 2020 |
| Alienware     | 17                          | [14abe97f88](https://linux-hardware.org/?probe=14abe97f88) | Oct 23, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| BigLinux                  | 22        | 30.99%  |
| BigLinux 20.04            | 6         | 8.45%   |
| BigLinux 23.0.0           | 3         | 4.23%   |
| BigLinux 22.0.0           | 3         | 4.23%   |
| BigLinux 2024-03-15_05-13 | 3         | 4.23%   |
| BigLinux 19.04            | 3         | 4.23%   |
| BigLinux 23.1.4           | 2         | 2.82%   |
| BigLinux 22.1.0           | 2         | 2.82%   |
| BigLinux 21.3.7           | 2         | 2.82%   |
| BigLinux 23.01.06         | 1         | 1.41%   |
| BigLinux 23.0.3           | 1         | 1.41%   |
| BigLinux 22.11.19         | 1         | 1.41%   |
| BigLinux 22.11.14         | 1         | 1.41%   |
| BigLinux 22.10.06         | 1         | 1.41%   |
| BigLinux 22.0.5           | 1         | 1.41%   |
| BigLinux 22.0.4           | 1         | 1.41%   |
| BigLinux 21.3.6           | 1         | 1.41%   |
| BigLinux 21.3.5           | 1         | 1.41%   |
| BigLinux 21.1.2           | 1         | 1.41%   |
| BigLinux 2024-05-03_00-50 | 1         | 1.41%   |
| BigLinux 2024-05-01_19-57 | 1         | 1.41%   |
| BigLinux 2024-03-08_05-13 | 1         | 1.41%   |
| BigLinux 2024-02-23_05-13 | 1         | 1.41%   |
| BigLinux 2024-02-02_05-14 | 1         | 1.41%   |
| BigLinux 2023-11-24_05-13 | 1         | 1.41%   |
| BigLinux 2023-11-21_03-11 | 1         | 1.41%   |
| BigLinux 2023-11-07_19-34 | 1         | 1.41%   |
| BigLinux 2023-10-14_01-04 | 1         | 1.41%   |
| BigLinux 2023-08-04_06-17 | 1         | 1.41%   |
| BigLinux 2023-06-30_08-01 | 1         | 1.41%   |
| BigLinux 2023-06-23_06-21 | 1         | 1.41%   |
| BigLinux 2023-06-03_00-55 | 1         | 1.41%   |
| BigLinux 2023-04-11_15-10 | 1         | 1.41%   |
| BigLinux 2023-03-17_19-23 | 1         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| BigLinux | 69        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 6.6.19-1-MANJARO           | 5         | 6.85%   |
| 6.1.55-1-MANJARO           | 4         | 5.48%   |
| 6.6.26-1-MANJARO           | 3         | 4.11%   |
| 6.1.64-1-MANJARO           | 3         | 4.11%   |
| 6.7.7-1-MANJARO            | 2         | 2.74%   |
| 6.5.5-1-MANJARO            | 2         | 2.74%   |
| 6.1.69-1-MANJARO           | 2         | 2.74%   |
| 6.1.62-1-MANJARO           | 2         | 2.74%   |
| 6.1.31-2-MANJARO           | 2         | 2.74%   |
| 6.1.23-1-MANJARO           | 2         | 2.74%   |
| 6.0.8-1-MANJARO            | 2         | 2.74%   |
| 5.8.0-43-generic           | 2         | 2.74%   |
| 5.2.8-xanmod8              | 2         | 2.74%   |
| 5.15.85-1-MANJARO          | 2         | 2.74%   |
| 5.15.102-1-MANJARO         | 2         | 2.74%   |
| 6.8.8-2-MANJARO            | 1         | 1.37%   |
| 6.8.5-1-MANJARO            | 1         | 1.37%   |
| 6.8.4-1-MANJARO            | 1         | 1.37%   |
| 6.8.0-1-MANJARO            | 1         | 1.37%   |
| 6.7.4-2-MANJARO            | 1         | 1.37%   |
| 6.6.3-1-MANJARO            | 1         | 1.37%   |
| 6.6.16-2-MANJARO           | 1         | 1.37%   |
| 6.6.10-1-MANJARO           | 1         | 1.37%   |
| 6.5.11-1-MANJARO           | 1         | 1.37%   |
| 6.5.10-x64v2-xanmod1-1     | 1         | 1.37%   |
| 6.4.6-1-MANJARO            | 1         | 1.37%   |
| 6.3.5-2-MANJARO            | 1         | 1.37%   |
| 6.3.5-1-MANJARO            | 1         | 1.37%   |
| 6.3.13-1-MANJARO           | 1         | 1.37%   |
| 6.2.12-1-MANJARO           | 1         | 1.37%   |
| 6.1.80-1-MANJARO           | 1         | 1.37%   |
| 6.1.71-1-MANJARO           | 1         | 1.37%   |
| 6.1.64-x64v2-xanmod1-1-lts | 1         | 1.37%   |
| 6.1.63-1-MANJARO           | 1         | 1.37%   |
| 6.1.60-1-MANJARO           | 1         | 1.37%   |
| 6.1.1-1-MANJARO            | 1         | 1.37%   |
| 5.9.3-xanmod1              | 1         | 1.37%   |
| 5.8.0-28-generic           | 1         | 1.37%   |
| 5.4.0-48-generic           | 1         | 1.37%   |
| 5.3.6-xanmod5              | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.6.19   | 5         | 6.85%   |
| 6.1.64   | 4         | 5.48%   |
| 6.1.55   | 4         | 5.48%   |
| 6.6.26   | 3         | 4.11%   |
| 5.8.0    | 3         | 4.11%   |
| 6.7.7    | 2         | 2.74%   |
| 6.5.5    | 2         | 2.74%   |
| 6.3.5    | 2         | 2.74%   |
| 6.1.69   | 2         | 2.74%   |
| 6.1.62   | 2         | 2.74%   |
| 6.1.31   | 2         | 2.74%   |
| 6.1.23   | 2         | 2.74%   |
| 6.0.8    | 2         | 2.74%   |
| 5.2.8    | 2         | 2.74%   |
| 5.15.85  | 2         | 2.74%   |
| 5.15.102 | 2         | 2.74%   |
| 6.8.8    | 1         | 1.37%   |
| 6.8.5    | 1         | 1.37%   |
| 6.8.4    | 1         | 1.37%   |
| 6.8.0    | 1         | 1.37%   |
| 6.7.4    | 1         | 1.37%   |
| 6.6.3    | 1         | 1.37%   |
| 6.6.16   | 1         | 1.37%   |
| 6.6.10   | 1         | 1.37%   |
| 6.5.11   | 1         | 1.37%   |
| 6.5.10   | 1         | 1.37%   |
| 6.4.6    | 1         | 1.37%   |
| 6.3.13   | 1         | 1.37%   |
| 6.2.12   | 1         | 1.37%   |
| 6.1.80   | 1         | 1.37%   |
| 6.1.71   | 1         | 1.37%   |
| 6.1.63   | 1         | 1.37%   |
| 6.1.60   | 1         | 1.37%   |
| 6.1.1    | 1         | 1.37%   |
| 5.9.3    | 1         | 1.37%   |
| 5.4.0    | 1         | 1.37%   |
| 5.3.6    | 1         | 1.37%   |
| 5.19.13  | 1         | 1.37%   |
| 5.15.94  | 1         | 1.37%   |
| 5.15.78  | 1         | 1.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 19        | 27.54%  |
| 6.6     | 11        | 15.94%  |
| 5.15    | 8         | 11.59%  |
| 6.8     | 4         | 5.8%    |
| 6.5     | 4         | 5.8%    |
| 5.10    | 4         | 5.8%    |
| 6.7     | 3         | 4.35%   |
| 6.3     | 3         | 4.35%   |
| 5.8     | 3         | 4.35%   |
| 6.0     | 2         | 2.9%    |
| 5.2     | 2         | 2.9%    |
| 6.4     | 1         | 1.45%   |
| 6.2     | 1         | 1.45%   |
| 5.9     | 1         | 1.45%   |
| 5.4     | 1         | 1.45%   |
| 5.3     | 1         | 1.45%   |
| 5.19    | 1         | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 64        | 92.75%  |
| KDE      | 2         | 2.9%    |
| XFCE     | 1         | 1.45%   |
| Cinnamon | 1         | 1.45%   |
| Unknown  | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 68        | 98.55%  |
| Wayland | 1         | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 41        | 59.42%  |
| Unknown | 25        | 36.23%  |
| LightDM | 3         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_BR   | 41        | 59.42%  |
| en_US   | 8         | 11.59%  |
| pl_PL   | 5         | 7.25%   |
| de_DE   | 3         | 4.35%   |
| es_MX   | 2         | 2.9%    |
| en_GB   | 2         | 2.9%    |
| el_GR   | 2         | 2.9%    |
| tr_TR   | 1         | 1.45%   |
| it_IT   | 1         | 1.45%   |
| fi_FI   | 1         | 1.45%   |
| es_CR   | 1         | 1.45%   |
| en_AU   | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 49        | 70%     |
| BIOS | 21        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 58        | 84.06%  |
| Ext4    | 7         | 10.14%  |
| Overlay | 3         | 4.35%   |
| Unknown | 1         | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 47.14%  |
| Unknown | 25        | 35.71%  |
| MBR     | 12        | 17.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 92.86%  |
| Yes       | 5         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 69.57%  |
| Yes       | 21        | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 11        | 15.94%  |
| Acer                   | 11        | 15.94%  |
| ASUSTek Computer       | 10        | 14.49%  |
| Hewlett-Packard        | 9         | 13.04%  |
| Dell                   | 7         | 10.14%  |
| Positivo               | 4         | 5.8%    |
| Apple                  | 3         | 4.35%   |
| Samsung Electronics    | 2         | 2.9%    |
| Google                 | 2         | 2.9%    |
| Toshiba                | 1         | 1.45%   |
| Sony                   | 1         | 1.45%   |
| Semp Toshiba           | 1         | 1.45%   |
| Multilaser             | 1         | 1.45%   |
| MSI                    | 1         | 1.45%   |
| Itautec                | 1         | 1.45%   |
| Clevo                  | 1         | 1.45%   |
| Avell High Performance | 1         | 1.45%   |
| Alienware              | 1         | 1.45%   |
| Unknown                | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Positivo C41TF                   | 2         | 2.9%    |
| Google Blooguard                 | 2         | 2.9%    |
| ASUS VivoBook_ASUSLaptop M5602RA | 2         | 2.9%    |
| Toshiba Satellite S55-A          | 1         | 1.45%   |
| Sony VGN-NR230AE                 | 1         | 1.45%   |
| Semp Toshiba IS 1412             | 1         | 1.45%   |
| Samsung 550XCJ/550XCR            | 1         | 1.45%   |
| Samsung 300E5M/300E5L            | 1         | 1.45%   |
| Positivo Q464B                   | 1         | 1.45%   |
| Positivo C14RV01                 | 1         | 1.45%   |
| Multilaser MLSH1H LINUX          | 1         | 1.45%   |
| MSI Cyborg 15 A12VF              | 1         | 1.45%   |
| Lenovo Yoga Slim 7 14ARE05 82A2  | 1         | 1.45%   |
| Lenovo ThinkPad T480s 20L70028US | 1         | 1.45%   |
| Lenovo ThinkPad T410 25379N2     | 1         | 1.45%   |
| Lenovo IdeaPad Z470              | 1         | 1.45%   |
| Lenovo IdeaPad S400 VIUS3        | 1         | 1.45%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 1         | 1.45%   |
| Lenovo IdeaPad 300-15ISK 80RS    | 1         | 1.45%   |
| Lenovo IdeaPad 3 15ITL6 82H8     | 1         | 1.45%   |
| Lenovo IdeaPad 3 15IGL05 82BU    | 1         | 1.45%   |
| Lenovo IdeaPad 3 15ABA7 82RN     | 1         | 1.45%   |
| Lenovo G50-80 80R0               | 1         | 1.45%   |
| Itautec Itautec                  | 1         | 1.45%   |
| HP ZBook 15 G3                   | 1         | 1.45%   |
| HP Victus by Gaming Laptop       | 1         | 1.45%   |
| HP Pavilion g4                   | 1         | 1.45%   |
| HP Laptop 15-bs1xx               | 1         | 1.45%   |
| HP ENVY TS m7                    | 1         | 1.45%   |
| HP EliteBook Folio 9470m         | 1         | 1.45%   |
| HP EliteBook 8760w               | 1         | 1.45%   |
| HP 255 G7 Notebook PC            | 1         | 1.45%   |
| HP 255 G6 Notebook PC            | 1         | 1.45%   |
| Dell System XPS L502X            | 1         | 1.45%   |
| Dell System Inspiron N7110       | 1         | 1.45%   |
| Dell Latitude E6420              | 1         | 1.45%   |
| Dell Inspiron N5010              | 1         | 1.45%   |
| Dell Inspiron 7460               | 1         | 1.45%   |
| Dell Inspiron 3480               | 1         | 1.45%   |
| Dell G15 5520                    | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 7         | 10.14%  |
| ASUS VivoBook                | 6         | 8.7%    |
| Acer Aspire                  | 5         | 7.25%   |
| Dell Inspiron                | 3         | 4.35%   |
| Acer Nitro                   | 3         | 4.35%   |
| Positivo C41TF               | 2         | 2.9%    |
| Lenovo ThinkPad              | 2         | 2.9%    |
| HP EliteBook                 | 2         | 2.9%    |
| HP 255                       | 2         | 2.9%    |
| Google Blooguard             | 2         | 2.9%    |
| Dell System                  | 2         | 2.9%    |
| Toshiba Satellite            | 1         | 1.45%   |
| Sony VGN-NR230AE             | 1         | 1.45%   |
| Semp Toshiba IS              | 1         | 1.45%   |
| Samsung 550XCJ               | 1         | 1.45%   |
| Samsung 300E5M               | 1         | 1.45%   |
| Positivo Q464B               | 1         | 1.45%   |
| Positivo C14RV01             | 1         | 1.45%   |
| Multilaser MLSH1H            | 1         | 1.45%   |
| MSI Cyborg                   | 1         | 1.45%   |
| Lenovo Yoga                  | 1         | 1.45%   |
| Lenovo G50-80                | 1         | 1.45%   |
| Itautec Itautec              | 1         | 1.45%   |
| HP ZBook                     | 1         | 1.45%   |
| HP Victus                    | 1         | 1.45%   |
| HP Pavilion                  | 1         | 1.45%   |
| HP Laptop                    | 1         | 1.45%   |
| HP ENVY                      | 1         | 1.45%   |
| Dell Latitude                | 1         | 1.45%   |
| Dell G15                     | 1         | 1.45%   |
| Clevo W340EU                 | 1         | 1.45%   |
| Avell High Performance STORM | 1         | 1.45%   |
| ASUS X541SA                  | 1         | 1.45%   |
| ASUS X45U                    | 1         | 1.45%   |
| ASUS X455LA                  | 1         | 1.45%   |
| ASUS VX7SX                   | 1         | 1.45%   |
| Apple MacBookPro9            | 1         | 1.45%   |
| Apple MacBookPro5            | 1         | 1.45%   |
| Apple MacBookPro14           | 1         | 1.45%   |
| Alienware 17                 | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 11.59%  |
| 2022 | 7         | 10.14%  |
| 2017 | 7         | 10.14%  |
| 2023 | 6         | 8.7%    |
| 2012 | 6         | 8.7%    |
| 2011 | 6         | 8.7%    |
| 2019 | 4         | 5.8%    |
| 2016 | 4         | 5.8%    |
| 2013 | 4         | 5.8%    |
| 2020 | 3         | 4.35%   |
| 2018 | 3         | 4.35%   |
| 2009 | 3         | 4.35%   |
| 2015 | 2         | 2.9%    |
| 2014 | 2         | 2.9%    |
| 2010 | 2         | 2.9%    |
| 2007 | 2         | 2.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 69        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 69        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 97.1%   |
| Yes  | 2         | 2.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 24.29%  |
| 3.01-4.0    | 17        | 24.29%  |
| 8.01-16.0   | 13        | 18.57%  |
| 16.01-24.0  | 9         | 12.86%  |
| 32.01-64.0  | 5         | 7.14%   |
| 1.01-2.0    | 5         | 7.14%   |
| 24.01-32.0  | 2         | 2.86%   |
| 2.01-3.0    | 1         | 1.43%   |
| 64.01-256.0 | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 30        | 42.25%  |
| 2.01-3.0  | 15        | 21.13%  |
| 3.01-4.0  | 12        | 16.9%   |
| 4.01-8.0  | 7         | 9.86%   |
| 0.51-1.0  | 6         | 8.45%   |
| 8.01-16.0 | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 73.91%  |
| 2      | 12        | 17.39%  |
| 3      | 5         | 7.25%   |
| 4      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 62.32%  |
| Yes       | 26        | 37.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 76.81%  |
| No        | 16        | 23.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 98.55%  |
| No        | 1         | 1.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 76.81%  |
| No        | 16        | 23.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 40        | 57.97%  |
| USA          | 7         | 10.14%  |
| Poland       | 4         | 5.8%    |
| UK           | 3         | 4.35%   |
| Greece       | 3         | 4.35%   |
| Germany      | 3         | 4.35%   |
| Mexico       | 2         | 2.9%    |
| Turkey       | 1         | 1.45%   |
| Saudi Arabia | 1         | 1.45%   |
| Portugal     | 1         | 1.45%   |
| Italy        | 1         | 1.45%   |
| Finland      | 1         | 1.45%   |
| Costa Rica   | 1         | 1.45%   |
| Australia    | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 3         | 4.29%   |
| Clarksville           | 3         | 4.29%   |
| Brasília             | 3         | 4.29%   |
| Curitiba              | 2         | 2.86%   |
| Castanhal             | 2         | 2.86%   |
| Campo Grande          | 2         | 2.86%   |
| Belo Horizonte        | 2         | 2.86%   |
| Zdzieszowice          | 1         | 1.43%   |
| Vitória da Conquista | 1         | 1.43%   |
| Tramandai             | 1         | 1.43%   |
| Thessaloniki          | 1         | 1.43%   |
| Szczyrk               | 1         | 1.43%   |
| Stralsund             | 1         | 1.43%   |
| Springfield           | 1         | 1.43%   |
| Sparti                | 1         | 1.43%   |
| Serafina Correa       | 1         | 1.43%   |
| Sao Paulo das Missoes | 1         | 1.43%   |
| Sao Jose do Rio Preto | 1         | 1.43%   |
| Sao Domingos do Capim | 1         | 1.43%   |
| San José             | 1         | 1.43%   |
| Salvador              | 1         | 1.43%   |
| Rio de Janeiro        | 1         | 1.43%   |
| Pevensey              | 1         | 1.43%   |
| Perth                 | 1         | 1.43%   |
| Mirassol              | 1         | 1.43%   |
| Minneapolis           | 1         | 1.43%   |
| Metepec               | 1         | 1.43%   |
| Marataizes            | 1         | 1.43%   |
| Maidstone             | 1         | 1.43%   |
| Londrina              | 1         | 1.43%   |
| Koszalin              | 1         | 1.43%   |
| Jundiaí              | 1         | 1.43%   |
| Joensuu               | 1         | 1.43%   |
| Joao Monlevade        | 1         | 1.43%   |
| Itatiba               | 1         | 1.43%   |
| Istanbul              | 1         | 1.43%   |
| Hortolândia          | 1         | 1.43%   |
| Hoffman               | 1         | 1.43%   |
| Guarai                | 1         | 1.43%   |
| Grimsby               | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 13        | 15     | 14.13%  |
| Samsung Electronics            | 8         | 8      | 8.7%    |
| Unknown                        | 7         | 7      | 7.61%   |
| Seagate                        | 6         | 6      | 6.52%   |
| Crucial                        | 6         | 6      | 6.52%   |
| Toshiba                        | 4         | 5      | 4.35%   |
| Micron Technology              | 4         | 4      | 4.35%   |
| MAXIO Technology (Hangzhou)    | 4         | 4      | 4.35%   |
| Kingston                       | 4         | 4      | 4.35%   |
| SK hynix                       | 3         | 3      | 3.26%   |
| SanDisk                        | 3         | 3      | 3.26%   |
| KingSpec                       | 3         | 3      | 3.26%   |
| ADATA Technology               | 3         | 3      | 3.26%   |
| Micron/Crucial Technology      | 2         | 2      | 2.17%   |
| LITEON                         | 2         | 3      | 2.17%   |
| Hitachi                        | 2         | 2      | 2.17%   |
| HGST                           | 2         | 2      | 2.17%   |
| China                          | 2         | 2      | 2.17%   |
| A-DATA Technology              | 2         | 2      | 2.17%   |
| T-FORCE                        | 1         | 1      | 1.09%   |
| Solid State Storage Technology | 1         | 1      | 1.09%   |
| Realtek Semiconductor          | 1         | 1      | 1.09%   |
| PNY                            | 1         | 2      | 1.09%   |
| NT-1TB                         | 1         | 1      | 1.09%   |
| Netac                          | 1         | 2      | 1.09%   |
| KIOXIA                         | 1         | 1      | 1.09%   |
| Kingston Technology Company    | 1         | 1      | 1.09%   |
| JMicron Technology             | 1         | 1      | 1.09%   |
| Inland                         | 1         | 1      | 1.09%   |
| GOODRAM                        | 1         | 3      | 1.09%   |
| EYOTA                          | 1         | 1      | 1.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                             | 4         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 4.35%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 3         | 3.26%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 3.26%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 3         | 3.26%   |
| Kingston SA400S37480G 480GB SSD                    | 2         | 2.17%   |
| KingSpec P3-512 512GB SSD                          | 2         | 2.17%   |
| Crucial CT500MX500SSD1 500GB                       | 2         | 2.17%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                     | 1         | 1.09%   |
| WDC WD7500BPKX-75HPJT0 752GB                       | 1         | 1.09%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 1         | 1.09%   |
| WDC WD5000LPVX-60V0TT0 500GB                       | 1         | 1.09%   |
| WDC WD5000LPVT-08G33T1 500GB                       | 1         | 1.09%   |
| WDC WD3200BPVT-00JJ5T0 320GB                       | 1         | 1.09%   |
| WDC WD1200BEVT-75ZCT2 120GB                        | 1         | 1.09%   |
| WDC WD10SPZX-75Z10T3 1TB                           | 1         | 1.09%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 1.09%   |
| WDC WD Blue SA510 2.5 1TB SSD                      | 1         | 1.09%   |
| Unknown xD/SD/M.S.                                 | 1         | 1.09%   |
| Unknown MMC Card  256GB                            | 1         | 1.09%   |
| Unknown MMC Card  128GB                            | 1         | 1.09%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.09%   |
| T-FORCE SSD 1TB                                    | 1         | 1.09%   |
| Solid State Storage SSSTC CL1-4D128 128GB          | 1         | 1.09%   |
| SK hynix HFS512GEJ9X125N 512GB                     | 1         | 1.09%   |
| SK hynix HFS256GEJ9X108N 256GB                     | 1         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 1         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 1         | 1.09%   |
| Seagate ST320LM001 HN-M320MBB 320GB                | 1         | 1.09%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 1         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.09%   |
| Seagate ST1000LM014-1EJ164 1TB                     | 1         | 1.09%   |
| Seagate Expansion HDD 12TB                         | 1         | 1.09%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB        | 1         | 1.09%   |
| SanDisk SDSSDH3256G 256GB                          | 1         | 1.09%   |
| SanDisk SD9SN8W-512G-1006 512GB SSD                | 1         | 1.09%   |
| Samsung SSD 870 QVO 4TB                            | 1         | 1.09%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.09%   |
| Samsung PSSD T7 500GB                              | 1         | 1.09%   |
| Samsung HM501II 500GB                              | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 13     | 42.31%  |
| Seagate             | 6         | 6      | 23.08%  |
| Toshiba             | 4         | 5      | 15.38%  |
| Hitachi             | 2         | 2      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 6      | 18.18%  |
| Kingston            | 4         | 4      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| KingSpec            | 3         | 3      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| SanDisk             | 2         | 2      | 6.06%   |
| Micron Technology   | 2         | 2      | 6.06%   |
| LITEON              | 2         | 3      | 6.06%   |
| China               | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| T-FORCE             | 1         | 1      | 3.03%   |
| PNY                 | 1         | 2      | 3.03%   |
| NT-1TB              | 1         | 1      | 3.03%   |
| Inland              | 1         | 1      | 3.03%   |
| GOODRAM             | 1         | 3      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 27        | 37     | 31.76%  |
| HDD     | 26        | 29     | 30.59%  |
| NVMe    | 23        | 25     | 27.06%  |
| MMC     | 6         | 6      | 7.06%   |
| Unknown | 3         | 3      | 3.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 65     | 60.24%  |
| NVMe | 23        | 25     | 27.71%  |
| MMC  | 6         | 6      | 7.23%   |
| SAS  | 4         | 4      | 4.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 34     | 50%     |
| 0.51-1.0   | 24        | 26     | 42.86%  |
| 1.01-2.0   | 2         | 4      | 3.57%   |
| 3.01-4.0   | 1         | 1      | 1.79%   |
| 10.01-20.0 | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 2001-3000      | 19        | 27.54%  |
| 1001-2000      | 14        | 20.29%  |
| 251-500        | 11        | 15.94%  |
| More than 3000 | 8         | 11.59%  |
| 101-250        | 7         | 10.14%  |
| 501-1000       | 6         | 8.7%    |
| 1-20           | 2         | 2.9%    |
| 51-100         | 2         | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 51-100         | 24        | 33.33%  |
| 21-50          | 17        | 23.61%  |
| 101-250        | 11        | 15.28%  |
| 1-20           | 7         | 9.72%   |
| 501-1000       | 5         | 6.94%   |
| 251-500        | 4         | 5.56%   |
| 2001-3000      | 2         | 2.78%   |
| More than 3000 | 1         | 1.39%   |
| 1001-2000      | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 14.29%  |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 14.29%  |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 14.29%  |
| Crucial CT500MX200SSD3 500GB           | 1         | 1      | 14.29%  |
| China SATA SSD 240GB                   | 1         | 1      | 14.29%  |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor           | Notebooks | Drives | Percent |
|------------------|-----------|--------|---------|
| Hitachi          | 2         | 2      | 28.57%  |
| WDC              | 1         | 3      | 14.29%  |
| Seagate          | 1         | 1      | 14.29%  |
| Crucial          | 1         | 1      | 14.29%  |
| China            | 1         | 1      | 14.29%  |
| ADATA Technology | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 50%     |
| WDC     | 1         | 3      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Detected | 43        | 57     | 57.33%  |
| Works    | 25        | 34     | 33.33%  |
| Malfunc  | 7         | 9      | 9.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 46        | 58.97%  |
| AMD                            | 7         | 8.97%   |
| MAXIO Technology (Hangzhou)    | 4         | 5.13%   |
| SK hynix                       | 3         | 3.85%   |
| Samsung Electronics            | 3         | 3.85%   |
| ADATA Technology               | 3         | 3.85%   |
| Micron/Crucial Technology      | 2         | 2.56%   |
| Micron Technology              | 2         | 2.56%   |
| Solid State Storage Technology | 1         | 1.28%   |
| SanDisk                        | 1         | 1.28%   |
| Realtek Semiconductor          | 1         | 1.28%   |
| Nvidia                         | 1         | 1.28%   |
| Netac Technology               | 1         | 1.28%   |
| KIOXIA                         | 1         | 1.28%   |
| Kingston Technology Company    | 1         | 1.28%   |
| JMicron Technology             | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 8.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 8.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 7.41%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 7.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 4.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 4.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 3.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 3         | 3.7%    |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 2         | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.47%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 1.23%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 1         | 1.23%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 1         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.23%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                            | 1         | 1.23%   |
| Realtek RTS5762 NVMe SSD Controller                                              | 1         | 1.23%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 1.23%   |
| Netac PCIe 4 INNOGRIT based NVMe SSD                                             | 1         | 1.23%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 1.23%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.23%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                         | 1         | 1.23%   |
| KIOXIA NVMe SSD Controller XG8                                                   | 1         | 1.23%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 1         | 1.23%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.23%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 60.76%  |
| NVMe | 22        | 27.85%  |
| RAID | 6         | 7.59%   |
| IDE  | 3         | 3.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 81.16%  |
| AMD    | 13        | 18.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 4.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 4.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 2.9%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 2.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.9%    |
| Intel Celeron N4120 CPU @ 1.10GHz           | 2         | 2.9%    |
| AMD Ryzen 7 6800H with Radeon Graphics      | 2         | 2.9%    |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.45%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 1.45%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.45%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.45%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.45%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.45%   |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 1         | 1.45%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.45%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1         | 1.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.45%   |
| Intel Core i3-2375M CPU @ 1.50GHz           | 1         | 1.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.45%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 1         | 1.45%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 23.19%  |
| Intel Core i7           | 13        | 18.84%  |
| Intel Core i3           | 8         | 11.59%  |
| Other                   | 7         | 10.14%  |
| Intel Celeron           | 7         | 10.14%  |
| AMD Ryzen 5             | 6         | 8.7%    |
| AMD Ryzen 7             | 4         | 5.8%    |
| Intel Pentium Silver    | 1         | 1.45%   |
| Intel Pentium Dual-Core | 1         | 1.45%   |
| Intel Pentium Dual      | 1         | 1.45%   |
| Intel Core 2 Duo        | 1         | 1.45%   |
| Intel Core 2            | 1         | 1.45%   |
| Intel Atom              | 1         | 1.45%   |
| AMD C-70                | 1         | 1.45%   |
| AMD C-60                | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 50.72%  |
| 4      | 22        | 31.88%  |
| 6      | 5         | 7.25%   |
| 8      | 3         | 4.35%   |
| 12     | 2         | 2.9%    |
| 14     | 1         | 1.45%   |
| 10     | 1         | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 73.91%  |
| 1      | 18        | 26.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 98.55%  |
| Unknown        | 1         | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 37.68%  |
| 0x206a7    | 6         | 8.7%    |
| 0x806e9    | 5         | 7.25%   |
| 0x306a9    | 3         | 4.35%   |
| 0x906a3    | 2         | 2.9%    |
| 0x806ea    | 2         | 2.9%    |
| 0x706a8    | 2         | 2.9%    |
| 0x506e3    | 2         | 2.9%    |
| 0x08108109 | 2         | 2.9%    |
| 0x05000119 | 2         | 2.9%    |
| 0xa0660    | 1         | 1.45%   |
| 0x906c0    | 1         | 1.45%   |
| 0x806ec    | 1         | 1.45%   |
| 0x806d1    | 1         | 1.45%   |
| 0x706e5    | 1         | 1.45%   |
| 0x6fd      | 1         | 1.45%   |
| 0x406e3    | 1         | 1.45%   |
| 0x406c4    | 1         | 1.45%   |
| 0x306d4    | 1         | 1.45%   |
| 0x306c3    | 1         | 1.45%   |
| 0x20655    | 1         | 1.45%   |
| 0x20652    | 1         | 1.45%   |
| 0x0a50000d | 1         | 1.45%   |
| 0x0a404102 | 1         | 1.45%   |
| 0x0a404101 | 1         | 1.45%   |
| 0x0810100b | 1         | 1.45%   |
| 0x06006705 | 1         | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 15.94%  |
| SandyBridge      | 8         | 11.59%  |
| Goldmont plus    | 6         | 8.7%    |
| IvyBridge        | 5         | 7.25%   |
| Alderlake Hybrid | 4         | 5.8%    |
| Unknown          | 4         | 5.8%    |
| Westmere         | 3         | 4.35%   |
| Skylake          | 3         | 4.35%   |
| Haswell          | 3         | 4.35%   |
| Zen+             | 2         | 2.9%    |
| Zen 3            | 2         | 2.9%    |
| Zen 2            | 2         | 2.9%    |
| Silvermont       | 2         | 2.9%    |
| Penryn           | 2         | 2.9%    |
| IceLake          | 2         | 2.9%    |
| Core             | 2         | 2.9%    |
| Bobcat           | 2         | 2.9%    |
| Zen              | 1         | 1.45%   |
| Tremont          | 1         | 1.45%   |
| TigerLake        | 1         | 1.45%   |
| Excavator        | 1         | 1.45%   |
| CometLake        | 1         | 1.45%   |
| Broadwell        | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 60.47%  |
| Nvidia | 18        | 20.93%  |
| AMD    | 16        | 18.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 6         | 6.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 6.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 6.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.37%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 3.37%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 2.25%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.25%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 2.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.12%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 1.12%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.12%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.12%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 1.12%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.12%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.12%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.12%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.12%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                                 | 1         | 1.12%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 1.12%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.12%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 1         | 1.12%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 1         | 1.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.12%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.12%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.12%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.12%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 44.93%  |
| Intel + Nvidia | 14        | 20.29%  |
| 1 x AMD        | 12        | 17.39%  |
| 2 x Intel      | 3         | 4.35%   |
| 1 x Nvidia     | 3         | 4.35%   |
| Other          | 2         | 2.9%    |
| Intel + AMD    | 2         | 2.9%    |
| 2 x AMD        | 1         | 1.45%   |
| AMD + Nvidia   | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 81.16%  |
| Proprietary | 12        | 17.39%  |
| Unknown     | 1         | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 71.01%  |
| 0.01-0.5   | 7         | 10.14%  |
| 1.01-2.0   | 6         | 8.7%    |
| 3.01-4.0   | 3         | 4.35%   |
| 0.51-1.0   | 2         | 2.9%    |
| 7.01-8.0   | 1         | 1.45%   |
| 2.01-3.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 23.75%  |
| BOE                     | 14        | 17.5%   |
| Chimei Innolux          | 13        | 16.25%  |
| LG Display              | 10        | 12.5%   |
| Samsung Electronics     | 5         | 6.25%   |
| Goldstar                | 4         | 5%      |
| Apple                   | 3         | 3.75%   |
| Panasonic               | 2         | 2.5%    |
| GDH                     | 2         | 2.5%    |
| Chi Mei Optoelectronics | 2         | 2.5%    |
| MTD                     | 1         | 1.25%   |
| LRX                     | 1         | 1.25%   |
| Lenovo                  | 1         | 1.25%   |
| Hewlett-Packard         | 1         | 1.25%   |
| Dell                    | 1         | 1.25%   |
| CSO                     | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 3.75%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 3         | 3.75%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                     | 2         | 2.5%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 2.5%    |
| GDH TV PHILCO GDH0030 3840x2160 708x398mm 32.0-inch                   | 2         | 2.5%    |
| BOE LCD Monitor BOE0913 1366x768 309x174mm 14.0-inch                  | 2         | 2.5%    |
| AU Optronics LCD Monitor AUOE495 2560x1600 344x215mm 16.0-inch        | 2         | 2.5%    |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 886x498mm 40.0-inch | 1         | 1.25%   |
| MTD LCD Monitor MTD0001 1280x800 303x190mm 14.1-inch                  | 1         | 1.25%   |
| LRX '' LRX2281 1024x768 341x256mm 16.8-inch                           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0506 1366x768 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.25%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.25%   |
| Hewlett-Packard 23tm HWP3110 1920x1080 509x286mm 23.0-inch            | 1         | 1.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 1.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.25%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 1         | 1.25%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 1         | 1.25%   |
| Dell P2314H DEL409A 1920x1080 509x286mm 23.0-inch                     | 1         | 1.25%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                 | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1550 1920x1080 344x193mm 15.5-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch      | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch       | 1         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 30        | 37.97%  |
| 1920x1080 (FHD) | 29        | 36.71%  |
| 1280x800 (WXGA) | 4         | 5.06%   |
| 3840x2160 (4K)  | 3         | 3.8%    |
| 2560x1080       | 3         | 3.8%    |
| 1600x900 (HD+)  | 3         | 3.8%    |
| 2880x1800       | 2         | 2.53%   |
| 2560x1600       | 2         | 2.53%   |
| 1920x540        | 2         | 2.53%   |
| 2560x1440 (QHD) | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 41.25%  |
| 14     | 13        | 16.25%  |
| 13     | 12        | 15%     |
| 17     | 7         | 8.75%   |
| 23     | 3         | 3.75%   |
| 16     | 3         | 3.75%   |
| 52     | 2         | 2.5%    |
| 34     | 2         | 2.5%    |
| 31     | 2         | 2.5%    |
| 40     | 1         | 1.25%   |
| 28     | 1         | 1.25%   |
| 21     | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 70.89%  |
| 351-400     | 8         | 10.13%  |
| 601-700     | 3         | 3.8%    |
| 501-600     | 3         | 3.8%    |
| 201-300     | 3         | 3.8%    |
| 701-800     | 2         | 2.53%   |
| 1001-1500   | 2         | 2.53%   |
| 801-900     | 1         | 1.27%   |
| 401-500     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 59        | 83.1%   |
| 16/10 | 8         | 11.27%  |
| 21/9  | 3         | 4.23%   |
| 4/3   | 1         | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 41.25%  |
| 81-90          | 24        | 30%     |
| 121-130        | 7         | 8.75%   |
| 351-500        | 4         | 5%      |
| 201-250        | 4         | 5%      |
| More than 1000 | 2         | 2.5%    |
| 111-120        | 2         | 2.5%    |
| 71-80          | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 131-140        | 1         | 1.25%   |
| 501-1000       | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 44.3%   |
| 121-160       | 25        | 31.65%  |
| 51-100        | 12        | 15.19%  |
| 161-240       | 3         | 3.8%    |
| More than 240 | 2         | 2.53%   |
| 1-50          | 2         | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 80%     |
| 2     | 14        | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 42.11%  |
| Intel                    | 24        | 21.05%  |
| Qualcomm Atheros         | 21        | 18.42%  |
| Broadcom                 | 8         | 7.02%   |
| MediaTek                 | 3         | 2.63%   |
| Ralink Technology        | 2         | 1.75%   |
| TP-Link                  | 1         | 0.88%   |
| Ralink                   | 1         | 0.88%   |
| Nvidia                   | 1         | 0.88%   |
| Marvell Technology Group | 1         | 0.88%   |
| JMicron Technology       | 1         | 0.88%   |
| Edimax Technology        | 1         | 0.88%   |
| Belkin Components        | 1         | 0.88%   |
| ASIX Electronics         | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 24        | 18.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 6.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 2.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.55%   |
| Realtek Killer E2600 GbE Controller                                     | 2         | 1.55%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.55%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.78%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.78%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.78%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.78%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 1         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 0.78%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 31.08%  |
| Qualcomm Atheros      | 18        | 24.32%  |
| Realtek Semiconductor | 17        | 22.97%  |
| Broadcom              | 7         | 9.46%   |
| MediaTek              | 3         | 4.05%   |
| Ralink Technology     | 2         | 2.7%    |
| TP-Link               | 1         | 1.35%   |
| Ralink                | 1         | 1.35%   |
| Edimax Technology     | 1         | 1.35%   |
| Belkin Components     | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 9.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 5.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 4%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 4%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 2.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 2.67%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 2.67%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 1.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.33%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.33%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.33%   |
| Intel Wireless 8260                                                     | 1         | 1.33%   |
| Intel Wireless 7265                                                     | 1         | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.33%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.33%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.33%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 1.33%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 69.81%  |
| Intel                    | 6         | 11.32%  |
| Qualcomm Atheros         | 4         | 7.55%   |
| Broadcom                 | 2         | 3.77%   |
| Nvidia                   | 1         | 1.89%   |
| Marvell Technology Group | 1         | 1.89%   |
| JMicron Technology       | 1         | 1.89%   |
| ASIX Electronics         | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 44.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 14.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 3.7%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 1.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.85%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.85%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 56.2%   |
| Ethernet | 53        | 43.8%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 85.07%  |
| Ethernet | 10        | 14.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 69.57%  |
| 1     | 18        | 26.09%  |
| 0     | 3         | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 60.87%  |
| Yes  | 27        | 39.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 37.74%  |
| Qualcomm Atheros Communications | 6         | 11.32%  |
| Lite-On Technology              | 6         | 11.32%  |
| IMC Networks                    | 6         | 11.32%  |
| Realtek Semiconductor           | 5         | 9.43%   |
| Foxconn / Hon Hai               | 3         | 5.66%   |
| Broadcom                        | 2         | 3.77%   |
| Apple                           | 2         | 3.77%   |
| Hewlett-Packard                 | 1         | 1.89%   |
| Dell                            | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 4         | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 4         | 7.55%   |
| Intel AX201 Bluetooth                            | 4         | 7.55%   |
| Realtek Bluetooth Radio                          | 3         | 5.66%   |
| Qualcomm Atheros  Bluetooth Device               | 3         | 5.66%   |
| Intel Wireless-AC 3168 Bluetooth                 | 3         | 5.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 3.77%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 2         | 3.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 2         | 3.77%   |
| Intel Bluetooth Device                           | 2         | 3.77%   |
| Intel AX200 Bluetooth                            | 2         | 3.77%   |
| IMC Networks Bluetooth Radio                     | 2         | 3.77%   |
| IMC Networks Bluetooth Device                    | 2         | 3.77%   |
| Foxconn / Hon Hai Wireless_Device                | 2         | 3.77%   |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 1.89%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 1.89%   |
| Lite-On Bluetooth Device                         | 1         | 1.89%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.89%   |
| Intel Bluetooth wireless interface               | 1         | 1.89%   |
| IMC Networks Wireless_Device                     | 1         | 1.89%   |
| IMC Networks BCM20702A0                          | 1         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                 | 1         | 1.89%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device  | 1         | 1.89%   |
| Dell DW375 Bluetooth Module                      | 1         | 1.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                      | 1         | 1.89%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter            | 1         | 1.89%   |
| Apple Bluetooth USB Host Controller              | 1         | 1.89%   |
| Apple Bluetooth Host Controller                  | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 54        | 65.06%  |
| Nvidia                 | 14        | 16.87%  |
| AMD                    | 14        | 16.87%  |
| Generalplus Technology | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 10%     |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 10%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 7%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 6%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 6%      |
| Nvidia Audio device                                                                               | 4         | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 4%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 3%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 3%      |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 3%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2%      |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1%      |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1%      |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1%      |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1%      |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1%      |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1%      |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1%      |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 29.17%  |
| Micron Technology   | 6         | 12.5%   |
| Smart               | 5         | 10.42%  |
| Unknown             | 4         | 8.33%   |
| SK hynix            | 4         | 8.33%   |
| Kingston            | 3         | 6.25%   |
| A-DATA Technology   | 2         | 4.17%   |
| Unknown             | 2         | 4.17%   |
| Walton Chaintech    | 1         | 2.08%   |
| Timetec             | 1         | 2.08%   |
| Teikon              | 1         | 2.08%   |
| Smart Brazil        | 1         | 2.08%   |
| Kembona             | 1         | 2.08%   |
| G.Skill             | 1         | 2.08%   |
| Crucial             | 1         | 2.08%   |
| Corsair             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 3.7%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s     | 2         | 3.7%    |
| Micron RAM MICRON/MT60B1G16HC-4 8GB SODIMM DDR5 4800MT/s     | 2         | 3.7%    |
| Unknown                                                      | 2         | 3.7%    |
| Walton Chaintech RAM AS2G732-800P005 2GB SODIMM DDR2 800MT/s | 1         | 1.85%   |
| Unknown RAM Module 512MB SODIMM DDR2                         | 1         | 1.85%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                  | 1         | 1.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                  | 1         | 1.85%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 1         | 1.85%   |
| Unknown RAM Module 1GB SODIMM SDRAM                          | 1         | 1.85%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.85%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s       | 1         | 1.85%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 1         | 1.85%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s        | 1         | 1.85%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s        | 1         | 1.85%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s        | 1         | 1.85%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s       | 1         | 1.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                 | 1         | 1.85%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s               | 1         | 1.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s        | 1         | 1.85%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s        | 1         | 1.85%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 2133MT/s                | 1         | 1.85%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s          | 1         | 1.85%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.85%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.85%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 1         | 1.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s           | 1         | 1.85%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.85%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4266MT/s           | 1         | 1.85%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.85%   |
| Micron RAM 16ATF2G64HZ-2G1B1 16384MB SODIMM DDR4 2133MT/s    | 1         | 1.85%   |
| Kingston RAM TSB1600D3S1ELD/4GE 4GB SODIMM DDR3 1600MT/s     | 1         | 1.85%   |
| Kingston RAM KF2666C15S4/16G 16GB SODIMM DDR4 2667MT/s       | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 39.02%  |
| DDR4   | 13        | 31.71%  |
| DDR5   | 6         | 14.63%  |
| LPDDR3 | 2         | 4.88%   |
| DDR2   | 2         | 4.88%   |
| SDRAM  | 1         | 2.44%   |
| LPDDR4 | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 92.68%  |
| Row Of Chips | 3         | 7.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 30.43%  |
| 4096  | 13        | 28.26%  |
| 2048  | 8         | 17.39%  |
| 16384 | 6         | 13.04%  |
| 32768 | 3         | 6.52%   |
| 1024  | 1         | 2.17%   |
| 512   | 1         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 21.74%  |
| 4800    | 6         | 13.04%  |
| 2667    | 5         | 10.87%  |
| 2400    | 5         | 10.87%  |
| 1334    | 4         | 8.7%    |
| 2133    | 3         | 6.52%   |
| 1333    | 3         | 6.52%   |
| 3200    | 2         | 4.35%   |
| 1067    | 2         | 4.35%   |
| Unknown | 2         | 4.35%   |
| 4266    | 1         | 2.17%   |
| 1066    | 1         | 2.17%   |
| 975     | 1         | 2.17%   |
| 800     | 1         | 2.17%   |

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
| Chicony Electronics                    | 9         | 15.25%  |
| Quanta                                 | 8         | 13.56%  |
| Sunplus Innovation Technology          | 5         | 8.47%   |
| Realtek Semiconductor                  | 4         | 6.78%   |
| IMC Networks                           | 4         | 6.78%   |
| Bison Electronics                      | 4         | 6.78%   |
| Microdia                               | 3         | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.08%   |
| Alcor Micro                            | 3         | 5.08%   |
| SunplusIT                              | 2         | 3.39%   |
| Luxvisions Innotech Limited            | 2         | 3.39%   |
| Apple                                  | 2         | 3.39%   |
| Acer                                   | 2         | 3.39%   |
| Y Media                                | 1         | 1.69%   |
| USB Camera CS                          | 1         | 1.69%   |
| Sonix Technology                       | 1         | 1.69%   |
| Silicon Motion                         | 1         | 1.69%   |
| Shine-optics                           | 1         | 1.69%   |
| Lite-On Technology                     | 1         | 1.69%   |
| Lenovo                                 | 1         | 1.69%   |
| ALi                                    | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                           | 3         | 5.08%   |
| Chicony Integrated Camera                                   | 3         | 5.08%   |
| SunplusIT MTD camera                                        | 2         | 3.39%   |
| Quanta HD Webcam                                            | 2         | 3.39%   |
| Microdia Integrated_Webcam_HD                               | 2         | 3.39%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 2         | 3.39%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 3.39%   |
| Chicony HD WebCam                                           | 2         | 3.39%   |
| Bison HD Webcam                                             | 2         | 3.39%   |
| Acer Lenovo EasyCamera                                      | 2         | 3.39%   |
| Y Media USB Camera                                          | 1         | 1.69%   |
| USB Camera CS USB Camera CS                                 | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.69%   |
| Sunplus Laptop Integrated Webcam FHD                        | 1         | 1.69%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 1.69%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.69%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 1.69%   |
| Silicon Motion Web Camera                                   | 1         | 1.69%   |
| Shine-optics USB2.0 HD UVC WebCam                           | 1         | 1.69%   |
| Realtek USB Camera                                          | 1         | 1.69%   |
| Realtek HP Webcam                                           | 1         | 1.69%   |
| Realtek HP Truevision HD                                    | 1         | 1.69%   |
| Realtek HD WebCam                                           | 1         | 1.69%   |
| Quanta Laptop_Integrated_Webcam_2HDM                        | 1         | 1.69%   |
| Quanta HD User Facing                                       | 1         | 1.69%   |
| Quanta ACER HD User Facing                                  | 1         | 1.69%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam              | 1         | 1.69%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.69%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 1.69%   |
| IMC Networks Integrated Camera                              | 1         | 1.69%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.69%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.69%   |
| Chicony FHD Webcam                                          | 1         | 1.69%   |
| Chicony 2.0M UVC WebCam                                     | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 1.69%   |
| Bison Lenovo EasyCamera                                     | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 2         | 40%     |
| Realtek USB2.0 Finger Print Bridge | 2         | 40%     |
| Synaptics                          | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 40%     |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 20%     |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Giesecke & Devrient | 1         | 50%     |
| Broadcom            | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Giesecke & Devrient StarSign CUT               | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 52        | 75.36%  |
| 1     | 14        | 20.29%  |
| 2     | 2         | 2.9%    |
| 3     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 25%     |
| Fingerprint reader    | 5         | 25%     |
| Net/wireless          | 4         | 20%     |
| Multimedia controller | 2         | 10%     |
| Chipcard              | 2         | 10%     |
| Tv card               | 1         | 5%      |
| Storage               | 1         | 5%      |

