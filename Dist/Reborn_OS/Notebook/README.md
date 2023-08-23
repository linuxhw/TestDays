Reborn OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Reborn OS.

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

Total: 102

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Notebook           | [8c5385a962](https://linux-hardware.org/?probe=8c5385a962) | Jul 17, 2023 |
| HP            | EliteBook Folio 9470m       | [8503c5d0fe](https://linux-hardware.org/?probe=8503c5d0fe) | Jun 21, 2023 |
| HP            | EliteBook Folio 9470m       | [ab83a7d817](https://linux-hardware.org/?probe=ab83a7d817) | Jun 11, 2023 |
| Chuwi         | GemiBook Pro                | [772d1f8765](https://linux-hardware.org/?probe=772d1f8765) | Jun 03, 2023 |
| Timi          | A35S                        | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Dell          | XPS 13 9380                 | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [bd0af3660b](https://linux-hardware.org/?probe=bd0af3660b) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [12d1ccac8d](https://linux-hardware.org/?probe=12d1ccac8d) | Mar 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [57edb37217](https://linux-hardware.org/?probe=57edb37217) | Mar 08, 2023 |
| Medion        | X6816                       | [3f05d06600](https://linux-hardware.org/?probe=3f05d06600) | Feb 18, 2023 |
| Medion        | X6816                       | [fe99854800](https://linux-hardware.org/?probe=fe99854800) | Feb 17, 2023 |
| Dell          | G15 5511                    | [d2c2cb8454](https://linux-hardware.org/?probe=d2c2cb8454) | Nov 30, 2022 |
| Dell          | G15 5511                    | [f9e456efd0](https://linux-hardware.org/?probe=f9e456efd0) | Nov 30, 2022 |
| Dell          | Latitude 3410               | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| HP            | ProBook 6565b               | [2d35057d85](https://linux-hardware.org/?probe=2d35057d85) | Jul 03, 2022 |
| HP            | ProBook 6565b               | [947c54ac42](https://linux-hardware.org/?probe=947c54ac42) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| HP            | ProBook 6550b               | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| HUAWEI        | MRC-WX0                     | [714f759476](https://linux-hardware.org/?probe=714f759476) | Dec 06, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| Lenovo        | IdeaPad Y580                | [409fb80ae5](https://linux-hardware.org/?probe=409fb80ae5) | Sep 10, 2021 |
| Acer          | Aspire V3-111P              | [8c38c04148](https://linux-hardware.org/?probe=8c38c04148) | Sep 05, 2021 |
| Acer          | Aspire V3-111P              | [af61c27b54](https://linux-hardware.org/?probe=af61c27b54) | Sep 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [13aee77624](https://linux-hardware.org/?probe=13aee77624) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [19226582d9](https://linux-hardware.org/?probe=19226582d9) | May 31, 2021 |
| HP            | EliteBook 8460p             | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [989604544a](https://linux-hardware.org/?probe=989604544a) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1b1d0bc44f](https://linux-hardware.org/?probe=1b1d0bc44f) | Mar 27, 2021 |
| CyberPower... | Tracer Series               | [295977bfa3](https://linux-hardware.org/?probe=295977bfa3) | Mar 24, 2021 |
| Acer          | Extensa 5635Z               | [890d530c6a](https://linux-hardware.org/?probe=890d530c6a) | Mar 18, 2021 |
| Dell          | Latitude E6320              | [9439943a67](https://linux-hardware.org/?probe=9439943a67) | Mar 15, 2021 |
| Avell High... | A62 LIV                     | [1f0a994797](https://linux-hardware.org/?probe=1f0a994797) | Mar 08, 2021 |
| Dell          | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Dell          | Precision M4600             | [661670d030](https://linux-hardware.org/?probe=661670d030) | Jan 27, 2021 |
| HP            | EliteBook 2560p             | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| Acer          | Aspire E1-572               | [cb03a43d6b](https://linux-hardware.org/?probe=cb03a43d6b) | Jan 18, 2021 |
| Dell          | Studio 1747                 | [b07052df59](https://linux-hardware.org/?probe=b07052df59) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Acer          | Aspire E5-523               | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| HP            | Pavilion g7                 | [4df7168c54](https://linux-hardware.org/?probe=4df7168c54) | Dec 27, 2020 |
| HP            | Pavilion g7                 | [e2b98139df](https://linux-hardware.org/?probe=e2b98139df) | Dec 27, 2020 |
| Acer          | Aspire E5-523               | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | ThinkPad E570 20H50048US    | [db0d5b5a47](https://linux-hardware.org/?probe=db0d5b5a47) | Dec 15, 2020 |
| Acer          | Swift SF314-42              | [c5a5070a6f](https://linux-hardware.org/?probe=c5a5070a6f) | Dec 10, 2020 |
| Acer          | Swift SF314-42              | [f5429557cc](https://linux-hardware.org/?probe=f5429557cc) | Dec 10, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [6ea56336d8](https://linux-hardware.org/?probe=6ea56336d8) | Dec 03, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [a4e4cd792d](https://linux-hardware.org/?probe=a4e4cd792d) | Dec 02, 2020 |
| Lenovo        | IdeaPad Y450                | [a5ec379304](https://linux-hardware.org/?probe=a5ec379304) | Dec 01, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [67aeba9d99](https://linux-hardware.org/?probe=67aeba9d99) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y450                | [300a14fb31](https://linux-hardware.org/?probe=300a14fb31) | Nov 29, 2020 |
| HP            | ProBook 640 G5              | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| Lenovo        | G470 20078                  | [98c4778da6](https://linux-hardware.org/?probe=98c4778da6) | Nov 18, 2020 |
| Acer          | Aspire F5-573G              | [9153f43376](https://linux-hardware.org/?probe=9153f43376) | Nov 02, 2020 |
| Acer          | Aspire E5-571G              | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Dell          | Latitude 5500               | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| Sony          | VPCEH10EB                   | [167720fe57](https://linux-hardware.org/?probe=167720fe57) | Oct 25, 2020 |
| Razer         | Blade                       | [14ed46b628](https://linux-hardware.org/?probe=14ed46b628) | Oct 04, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | [6141f19045](https://linux-hardware.org/?probe=6141f19045) | Sep 17, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | [a34a40a5ff](https://linux-hardware.org/?probe=a34a40a5ff) | Sep 17, 2020 |
| Dell          | Latitude E6430              | [4fcaaadd6e](https://linux-hardware.org/?probe=4fcaaadd6e) | Sep 12, 2020 |
| HP            | 630                         | [baf66f73a2](https://linux-hardware.org/?probe=baf66f73a2) | Aug 14, 2020 |
| HP            | 630                         | [1f0b52b96d](https://linux-hardware.org/?probe=1f0b52b96d) | Aug 12, 2020 |
| Dell          | Inspiron 5520               | [27ed844469](https://linux-hardware.org/?probe=27ed844469) | Aug 08, 2020 |
| Dell          | Inspiron 5520               | [d40ce43d66](https://linux-hardware.org/?probe=d40ce43d66) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | [3b431d9c9a](https://linux-hardware.org/?probe=3b431d9c9a) | Jul 31, 2020 |
| Dell          | Inspiron 5520               | [3fea05b48d](https://linux-hardware.org/?probe=3fea05b48d) | Jul 30, 2020 |
| Dell          | Latitude E6430              | [d14e88e089](https://linux-hardware.org/?probe=d14e88e089) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [56cc69c796](https://linux-hardware.org/?probe=56cc69c796) | Jun 27, 2020 |
| ASUSTek       | X540SA                      | [a1aaa82c04](https://linux-hardware.org/?probe=a1aaa82c04) | Jun 25, 2020 |
| ASUSTek       | X540SA                      | [1bab33423f](https://linux-hardware.org/?probe=1bab33423f) | Jun 25, 2020 |
| Lenovo        | ThinkPad T510 4349BS9       | [c525e8d7d2](https://linux-hardware.org/?probe=c525e8d7d2) | May 18, 2020 |
| ASUSTek       | UX430UAR                    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [cd1f7d692d](https://linux-hardware.org/?probe=cd1f7d692d) | May 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [ddff2712b8](https://linux-hardware.org/?probe=ddff2712b8) | Apr 17, 2020 |
| Dell          | G7 7588                     | [68c487eb50](https://linux-hardware.org/?probe=68c487eb50) | Apr 15, 2020 |
| Lenovo        | Z70-80 80FG                 | [c27fa8aa9c](https://linux-hardware.org/?probe=c27fa8aa9c) | Apr 06, 2020 |
| Dell          | Latitude E6410              | [9d64ff0beb](https://linux-hardware.org/?probe=9d64ff0beb) | Mar 22, 2020 |
| Dell          | Inspiron 5421               | [2d8871e6ac](https://linux-hardware.org/?probe=2d8871e6ac) | Mar 19, 2020 |
| HP            | Pavilion 17                 | [5d3ccb9ed7](https://linux-hardware.org/?probe=5d3ccb9ed7) | Feb 24, 2020 |
| HP            | Pavilion dm1                | [e2e4a2c41f](https://linux-hardware.org/?probe=e2e4a2c41f) | Feb 13, 2020 |
| HP            | Pavilion 17                 | [26bdca3832](https://linux-hardware.org/?probe=26bdca3832) | Feb 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [48487463eb](https://linux-hardware.org/?probe=48487463eb) | Feb 09, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [9c202df9eb](https://linux-hardware.org/?probe=9c202df9eb) | Jan 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| ASUSTek       | X555YI                      | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Lenovo        | G570 20079                  | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Reborn OS         | 63        | 87.5%   |
| Reborn OS Rolling | 9         | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Reborn OS | 72        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-arch1-1     | 5         | 6.67%   |
| 5.9.10-arch1-1     | 3         | 4%      |
| 5.5.9-arch1-2      | 3         | 4%      |
| 5.9.1-arch1-1      | 2         | 2.67%   |
| 5.6.4-arch1-1      | 2         | 2.67%   |
| 5.5.2-arch1-1      | 2         | 2.67%   |
| 5.4.10-arch1-1     | 2         | 2.67%   |
| 6.4.3-arch1-2      | 1         | 1.33%   |
| 6.3.4-arch1-1      | 1         | 1.33%   |
| 6.2.8-arch1-1      | 1         | 1.33%   |
| 6.2.7-arch1-1      | 1         | 1.33%   |
| 6.2.2-zen1-1-zen   | 1         | 1.33%   |
| 6.2.2-arch1-1      | 1         | 1.33%   |
| 6.1.33-1-lts       | 1         | 1.33%   |
| 6.1.12-arch1-1     | 1         | 1.33%   |
| 6.0.8-arch1-1      | 1         | 1.33%   |
| 5.9.2-zen1-1-zen   | 1         | 1.33%   |
| 5.9.13-arch1-1     | 1         | 1.33%   |
| 5.9.11-arch2-1     | 1         | 1.33%   |
| 5.9.10-zen1-1-zen  | 1         | 1.33%   |
| 5.8.8-arch1-1      | 1         | 1.33%   |
| 5.8.5-arch1-1      | 1         | 1.33%   |
| 5.8.13-arch1-1     | 1         | 1.33%   |
| 5.7.8-arch1-1      | 1         | 1.33%   |
| 5.7.6-arch1-1      | 1         | 1.33%   |
| 5.7.5-arch1-1      | 1         | 1.33%   |
| 5.7.12-arch1-1     | 1         | 1.33%   |
| 5.7.11-arch1-1     | 1         | 1.33%   |
| 5.7.10-arch1-1     | 1         | 1.33%   |
| 5.6.13-arch1-1     | 1         | 1.33%   |
| 5.6.10-arch1-1     | 1         | 1.33%   |
| 5.4.8-arch1-1      | 1         | 1.33%   |
| 5.4.78-1-lts       | 1         | 1.33%   |
| 5.4.77-1-lts       | 1         | 1.33%   |
| 5.4.72-1-lts       | 1         | 1.33%   |
| 5.3.1-arch1-1-ARCH | 1         | 1.33%   |
| 5.2.9-arch1-1-ARCH | 1         | 1.33%   |
| 5.18.8-arch1-1     | 1         | 1.33%   |
| 5.18.12-arch1-1    | 1         | 1.33%   |
| 5.16.9-arch1-1     | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 5         | 6.67%   |
| 5.9.10  | 4         | 5.33%   |
| 5.5.9   | 3         | 4%      |
| 6.2.2   | 2         | 2.67%   |
| 5.9.1   | 2         | 2.67%   |
| 5.6.4   | 2         | 2.67%   |
| 5.5.2   | 2         | 2.67%   |
| 5.4.10  | 2         | 2.67%   |
| 5.11.11 | 2         | 2.67%   |
| 6.4.3   | 1         | 1.33%   |
| 6.3.4   | 1         | 1.33%   |
| 6.2.8   | 1         | 1.33%   |
| 6.2.7   | 1         | 1.33%   |
| 6.1.33  | 1         | 1.33%   |
| 6.1.12  | 1         | 1.33%   |
| 6.0.8   | 1         | 1.33%   |
| 5.9.2   | 1         | 1.33%   |
| 5.9.13  | 1         | 1.33%   |
| 5.9.11  | 1         | 1.33%   |
| 5.8.8   | 1         | 1.33%   |
| 5.8.5   | 1         | 1.33%   |
| 5.8.13  | 1         | 1.33%   |
| 5.7.8   | 1         | 1.33%   |
| 5.7.6   | 1         | 1.33%   |
| 5.7.5   | 1         | 1.33%   |
| 5.7.12  | 1         | 1.33%   |
| 5.7.11  | 1         | 1.33%   |
| 5.7.10  | 1         | 1.33%   |
| 5.6.13  | 1         | 1.33%   |
| 5.6.10  | 1         | 1.33%   |
| 5.4.8   | 1         | 1.33%   |
| 5.4.78  | 1         | 1.33%   |
| 5.4.77  | 1         | 1.33%   |
| 5.4.72  | 1         | 1.33%   |
| 5.3.1   | 1         | 1.33%   |
| 5.2.9   | 1         | 1.33%   |
| 5.18.8  | 1         | 1.33%   |
| 5.18.12 | 1         | 1.33%   |
| 5.16.9  | 1         | 1.33%   |
| 5.15.7  | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9     | 14        | 18.92%  |
| 5.7     | 6         | 8.11%   |
| 5.4     | 6         | 8.11%   |
| 5.10    | 6         | 8.11%   |
| 5.5     | 5         | 6.76%   |
| 5.11    | 5         | 6.76%   |
| 6.2     | 4         | 5.41%   |
| 5.6     | 4         | 5.41%   |
| 5.8     | 3         | 4.05%   |
| 5.15    | 3         | 4.05%   |
| 6.1     | 2         | 2.7%    |
| 5.18    | 2         | 2.7%    |
| 5.14    | 2         | 2.7%    |
| 5.13    | 2         | 2.7%    |
| 5.12    | 2         | 2.7%    |
| 4.19    | 2         | 2.7%    |
| 6.4     | 1         | 1.35%   |
| 6.3     | 1         | 1.35%   |
| 6.0     | 1         | 1.35%   |
| 5.3     | 1         | 1.35%   |
| 5.2     | 1         | 1.35%   |
| 5.16    | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 72        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 16        | 21.92%  |
| KDE5              | 14        | 19.18%  |
| XFCE              | 10        | 13.7%   |
| Deepin            | 9         | 12.33%  |
| KDE               | 8         | 10.96%  |
| X-Cinnamon        | 5         | 6.85%   |
| Unknown           | 3         | 4.11%   |
| MATE              | 2         | 2.74%   |
| i3                | 2         | 2.74%   |
| Yaru:ubuntu:GNOME | 1         | 1.37%   |
| LXQt              | 1         | 1.37%   |
| Enlightenment     | 1         | 1.37%   |
| Budgie            | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 75.34%  |
| Wayland | 18        | 24.66%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 83.33%  |
| LightDM | 5         | 6.94%   |
| SDDM    | 4         | 5.56%   |
| TDM     | 2         | 2.78%   |
| XDM     | 1         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 26        | 36.11%  |
| pt_BR   | 8         | 11.11%  |
| en_AU   | 5         | 6.94%   |
| de_DE   | 5         | 6.94%   |
| ru_RU   | 3         | 4.17%   |
| en_GB   | 3         | 4.17%   |
| en_CA   | 3         | 4.17%   |
| Unknown | 3         | 4.17%   |
| pl_PL   | 2         | 2.78%   |
| nl_NL   | 2         | 2.78%   |
| es_MX   | 2         | 2.78%   |
| es_ES   | 2         | 2.78%   |
| sv_SE   | 1         | 1.39%   |
| fr_BE   | 1         | 1.39%   |
| fi_FI   | 1         | 1.39%   |
| es_CL   | 1         | 1.39%   |
| en_DK   | 1         | 1.39%   |
| de_CH   | 1         | 1.39%   |
| cs_CZ   | 1         | 1.39%   |
| C       | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 52        | 71.23%  |
| EFI  | 21        | 28.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 75.34%  |
| Tmpfs   | 6         | 8.22%   |
| Btrfs   | 6         | 8.22%   |
| Unknown | 4         | 5.48%   |
| Overlay | 1         | 1.37%   |
| Ext3    | 1         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 60        | 83.33%  |
| GPT     | 9         | 12.5%   |
| MBR     | 3         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 97.22%  |
| Yes       | 2         | 2.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 95.83%  |
| Yes       | 3         | 4.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 21        | 29.17%  |
| Dell                   | 16        | 22.22%  |
| Hewlett-Packard        | 12        | 16.67%  |
| Acer                   | 8         | 11.11%  |
| ASUSTek Computer       | 5         | 6.94%   |
| Avell High Performance | 2         | 2.78%   |
| Toshiba                | 1         | 1.39%   |
| Timi                   | 1         | 1.39%   |
| Sony                   | 1         | 1.39%   |
| Razer                  | 1         | 1.39%   |
| Medion                 | 1         | 1.39%   |
| HUAWEI                 | 1         | 1.39%   |
| CyberPowerPC           | 1         | 1.39%   |
| Chuwi                  | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 4.17%   |
| Dell Inspiron 5520                     | 3         | 4.17%   |
| Dell Latitude E6430                    | 2         | 2.78%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 2.78%   |
| Toshiba Satellite C850-C1S             | 1         | 1.39%   |
| Timi A35S                              | 1         | 1.39%   |
| Sony VPCEH10EB                         | 1         | 1.39%   |
| Razer Blade                            | 1         | 1.39%   |
| Medion X6816                           | 1         | 1.39%   |
| Lenovo Z70-80 80FG                     | 1         | 1.39%   |
| Lenovo Y50-70 20378                    | 1         | 1.39%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 1.39%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 1.39%   |
| Lenovo ThinkPad T410 253725G           | 1         | 1.39%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 1.39%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 1.39%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 1.39%   |
| Lenovo IdeaPad Y580                    | 1         | 1.39%   |
| Lenovo IdeaPad Y450                    | 1         | 1.39%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 1.39%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 1.39%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 1.39%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 1.39%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.39%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 1.39%   |
| Lenovo G570 20079                      | 1         | 1.39%   |
| Lenovo G470 20078                      | 1         | 1.39%   |
| HUAWEI MRC-WX0                         | 1         | 1.39%   |
| HP ProBook 6565b                       | 1         | 1.39%   |
| HP ProBook 6550b                       | 1         | 1.39%   |
| HP ProBook 640 G5                      | 1         | 1.39%   |
| HP Pavilion Notebook                   | 1         | 1.39%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 1.39%   |
| HP Pavilion Laptop 15-cc6xx            | 1         | 1.39%   |
| HP Pavilion g7                         | 1         | 1.39%   |
| HP Pavilion dm1                        | 1         | 1.39%   |
| HP Pavilion 17                         | 1         | 1.39%   |
| HP EliteBook Folio 9470m               | 1         | 1.39%   |
| HP EliteBook 8460p                     | 1         | 1.39%   |
| HP EliteBook 2560p                     | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 11        | 15.28%  |
| Lenovo ThinkPad              | 6         | 8.33%   |
| HP Pavilion                  | 6         | 8.33%   |
| Dell Latitude                | 6         | 8.33%   |
| Acer Aspire                  | 6         | 8.33%   |
| Dell Inspiron                | 5         | 6.94%   |
| HP ProBook                   | 3         | 4.17%   |
| HP EliteBook                 | 3         | 4.17%   |
| ASUS VivoBook                | 2         | 2.78%   |
| Toshiba Satellite            | 1         | 1.39%   |
| Timi A35S                    | 1         | 1.39%   |
| Sony VPCEH10EB               | 1         | 1.39%   |
| Razer Blade                  | 1         | 1.39%   |
| Medion X6816                 | 1         | 1.39%   |
| Lenovo Z70-80                | 1         | 1.39%   |
| Lenovo Y50-70                | 1         | 1.39%   |
| Lenovo G570                  | 1         | 1.39%   |
| Lenovo G470                  | 1         | 1.39%   |
| HUAWEI MRC-WX0               | 1         | 1.39%   |
| Dell XPS                     | 1         | 1.39%   |
| Dell Studio                  | 1         | 1.39%   |
| Dell Precision               | 1         | 1.39%   |
| Dell G7                      | 1         | 1.39%   |
| Dell G15                     | 1         | 1.39%   |
| CyberPowerPC Tracer          | 1         | 1.39%   |
| Chuwi GemiBook               | 1         | 1.39%   |
| Avell High Performance G1550 | 1         | 1.39%   |
| Avell High Performance A62   | 1         | 1.39%   |
| ASUS X555YI                  | 1         | 1.39%   |
| ASUS X540SA                  | 1         | 1.39%   |
| ASUS UX430UAR                | 1         | 1.39%   |
| Acer Swift                   | 1         | 1.39%   |
| Acer Extensa                 | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 13.89%  |
| 2011 | 10        | 13.89%  |
| 2012 | 9         | 12.5%   |
| 2018 | 8         | 11.11%  |
| 2020 | 6         | 8.33%   |
| 2021 | 5         | 6.94%   |
| 2013 | 5         | 6.94%   |
| 2009 | 5         | 6.94%   |
| 2016 | 4         | 5.56%   |
| 2015 | 3         | 4.17%   |
| 2014 | 3         | 4.17%   |
| 2010 | 3         | 4.17%   |
| 2017 | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 72        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 47.22%  |
| 8.01-16.0  | 15        | 20.83%  |
| 3.01-4.0   | 12        | 16.67%  |
| 16.01-24.0 | 7         | 9.72%   |
| 32.01-64.0 | 4         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 33        | 44%     |
| 2.01-3.0  | 25        | 33.33%  |
| 4.01-8.0  | 5         | 6.67%   |
| 3.01-4.0  | 5         | 6.67%   |
| 0.51-1.0  | 4         | 5.33%   |
| 8.01-16.0 | 3         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 78.08%  |
| 2      | 15        | 20.55%  |
| 3      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 56.94%  |
| Yes       | 31        | 43.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 81.94%  |
| No        | 13        | 18.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 73.61%  |
| No        | 19        | 26.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 23.61%  |
| Brazil      | 10        | 13.89%  |
| Germany     | 7         | 9.72%   |
| Russia      | 4         | 5.56%   |
| Australia   | 4         | 5.56%   |
| Spain       | 3         | 4.17%   |
| Canada      | 3         | 4.17%   |
| UK          | 2         | 2.78%   |
| Turkey      | 2         | 2.78%   |
| Poland      | 2         | 2.78%   |
| Netherlands | 2         | 2.78%   |
| Mexico      | 2         | 2.78%   |
| Estonia     | 2         | 2.78%   |
| Switzerland | 1         | 1.39%   |
| Sweden      | 1         | 1.39%   |
| Portugal    | 1         | 1.39%   |
| Malaysia    | 1         | 1.39%   |
| Ireland     | 1         | 1.39%   |
| Finland     | 1         | 1.39%   |
| Czechia     | 1         | 1.39%   |
| Costa Rica  | 1         | 1.39%   |
| Chile       | 1         | 1.39%   |
| Benin       | 1         | 1.39%   |
| Belgium     | 1         | 1.39%   |
| Barbados    | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Melbourne    | 3         | 4.11%   |
| Aleksandrov  | 3         | 4.11%   |
| Toronto      | 2         | 2.74%   |
| Tallinn      | 2         | 2.74%   |
| Sao Paulo    | 2         | 2.74%   |
| Zabrze       | 1         | 1.37%   |
| Yadrin       | 1         | 1.37%   |
| Warsaw       | 1         | 1.37%   |
| Villahermosa | 1         | 1.37%   |
| Tres Cantos  | 1         | 1.37%   |
| The Hague    | 1         | 1.37%   |
| St Louis     | 1         | 1.37%   |
| Santiago     | 1         | 1.37%   |
| Roebel       | 1         | 1.37%   |
| Reynoldsburg | 1         | 1.37%   |
| Rainham      | 1         | 1.37%   |
| Potts Camp   | 1         | 1.37%   |
| Portsmouth   | 1         | 1.37%   |
| Porto Uniao  | 1         | 1.37%   |
| Paderborn    | 1         | 1.37%   |
| Orem         | 1         | 1.37%   |
| North Bay    | 1         | 1.37%   |
| Nijmegen     | 1         | 1.37%   |
| Newport News | 1         | 1.37%   |
| New Orleans  | 1         | 1.37%   |
| Mogi Mirim   | 1         | 1.37%   |
| Mexico City  | 1         | 1.37%   |
| Mesa         | 1         | 1.37%   |
| Madrid       | 1         | 1.37%   |
| Limeira      | 1         | 1.37%   |
| Lagoa Santa  | 1         | 1.37%   |
| Kuala Lumpur | 1         | 1.37%   |
| Kestel       | 1         | 1.37%   |
| Kapellen     | 1         | 1.37%   |
| Jonschwil    | 1         | 1.37%   |
| Jever        | 1         | 1.37%   |
| Jacksonville | 1         | 1.37%   |
| Itauna       | 1         | 1.37%   |
| Istanbul     | 1         | 1.37%   |
| Irvine       | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 15.12%  |
| WDC                 | 12        | 12     | 13.95%  |
| Seagate             | 11        | 13     | 12.79%  |
| Toshiba             | 8         | 9      | 9.3%    |
| Kingston            | 6         | 7      | 6.98%   |
| Unknown             | 5         | 5      | 5.81%   |
| HGST                | 4         | 4      | 4.65%   |
| Crucial             | 4         | 4      | 4.65%   |
| SK hynix            | 3         | 3      | 3.49%   |
| SanDisk             | 3         | 3      | 3.49%   |
| Intel               | 3         | 3      | 3.49%   |
| Transcend           | 2         | 2      | 2.33%   |
| Micron Technology   | 2         | 2      | 2.33%   |
| SPCC                | 1         | 2      | 1.16%   |
| Patriot             | 1         | 1      | 1.16%   |
| OYUNKEY             | 1         | 1      | 1.16%   |
| Netac               | 1         | 1      | 1.16%   |
| LITEONIT            | 1         | 1      | 1.16%   |
| KIOXIA              | 1         | 1      | 1.16%   |
| Hitachi             | 1         | 1      | 1.16%   |
| Emtec               | 1         | 2      | 1.16%   |
| Dell                | 1         | 1      | 1.16%   |
| ADATA Technology    | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                | 4         | 4.49%   |
| Intel NVMe SSD Drive 512GB            | 3         | 3.37%   |
| HGST HTS725050A7E630 500GB            | 3         | 3.37%   |
| WDC WD10JPVT-08A1YT2 1TB              | 2         | 2.25%   |
| SK hynix NVMe SSD Drive 256GB         | 2         | 2.25%   |
| Seagate ST9500325AS 500GB             | 2         | 2.25%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2.25%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 1.12%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1.12%   |
| WDC WD7500LPCX-60HWST0 752GB          | 1         | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1.12%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 1.12%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1.12%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 1.12%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1.12%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.12%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1.12%   |
| Unknown SD/MMC/MS PRO 128GB           | 1         | 1.12%   |
| Transcend TS1TSSD230S 1TB             | 1         | 1.12%   |
| Transcend TS128GMSA370 128GB SSD      | 1         | 1.12%   |
| Toshiba XG6 NVMe SSD Controller 512GB | 1         | 1.12%   |
| Toshiba TR200 240GB SSD               | 1         | 1.12%   |
| Toshiba NVMe SSD Drive 512GB          | 1         | 1.12%   |
| Toshiba MQ01ABD100M 1TB               | 1         | 1.12%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1.12%   |
| Toshiba MK5065GSXN 500GB              | 1         | 1.12%   |
| Toshiba MK3265GSX 320GB               | 1         | 1.12%   |
| Toshiba KBG30ZMS256G NVMe 256GB       | 1         | 1.12%   |
| SPCC Solid State Disk 256GB           | 1         | 1.12%   |
| SK hynix PC711 NVMe 1TB               | 1         | 1.12%   |
| Seagate ST9500420AS 500GB             | 1         | 1.12%   |
| Seagate ST9320423AS 320GB             | 1         | 1.12%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1.12%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1.12%   |
| Seagate ST1000LM035-1RK1 1TB          | 1         | 1.12%   |
| Seagate Expansion 1TB                 | 1         | 1.12%   |
| SanDisk SSD PLUS 240 GB               | 1         | 1.12%   |
| SanDisk SD9SN8W512G1002 512GB SSD     | 1         | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 34.38%  |
| WDC                 | 10        | 10     | 31.25%  |
| Toshiba             | 4         | 5      | 12.5%   |
| HGST                | 4         | 4      | 12.5%   |
| Unknown             | 1         | 1      | 3.13%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| Hitachi             | 1         | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 24.14%  |
| Kingston            | 6         | 7      | 20.69%  |
| Crucial             | 4         | 4      | 13.79%  |
| SanDisk             | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| Transcend           | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| SPCC                | 1         | 2      | 3.45%   |
| Patriot             | 1         | 1      | 3.45%   |
| Netac               | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 32        | 35     | 37.65%  |
| SSD     | 28        | 34     | 32.94%  |
| NVMe    | 18        | 19     | 21.18%  |
| MMC     | 4         | 4      | 4.71%   |
| Unknown | 3         | 4      | 3.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 68     | 68.75%  |
| NVMe | 18        | 19     | 22.5%   |
| MMC  | 4         | 4      | 5%      |
| SAS  | 3         | 5      | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 43     | 64.52%  |
| 0.51-1.0   | 22        | 26     | 35.48%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 30        | 39.47%  |
| 101-250    | 22        | 28.95%  |
| 501-1000   | 10        | 13.16%  |
| 51-100     | 6         | 7.89%   |
| 1001-2000  | 4         | 5.26%   |
| Unknown    | 3         | 3.95%   |
| 1-20       | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 28        | 36.84%  |
| 21-50    | 16        | 21.05%  |
| 101-250  | 13        | 17.11%  |
| 51-100   | 10        | 13.16%  |
| 251-500  | 4         | 5.26%   |
| Unknown  | 3         | 3.95%   |
| 501-1000 | 2         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 64        | 85     | 86.49%  |
| Works    | 10        | 11     | 13.51%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 65.85%  |
| AMD                          | 13        | 15.85%  |
| Samsung Electronics          | 5         | 6.1%    |
| Toshiba America Info Systems | 3         | 3.66%   |
| SK hynix                     | 3         | 3.66%   |
| Micron Technology            | 2         | 2.44%   |
| KIOXIA                       | 1         | 1.22%   |
| ADATA Technology             | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 14.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 7.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 5.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 2.38%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 2.38%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.38%   |
| Intel SSD 660P Series                                                                  | 2         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 2.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.19%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 1.19%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 1         | 1.19%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 1         | 1.19%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 1         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.19%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 1         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.19%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                            | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 60        | 73.17%  |
| NVMe | 17        | 20.73%  |
| RAID | 3         | 3.66%   |
| IDE  | 2         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 79.17%  |
| AMD    | 15        | 20.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 4.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 4.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 4.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 4.17%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 2.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 2.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.78%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.78%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.78%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.39%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.39%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.39%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.39%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.39%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.39%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.39%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.39%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 1.39%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.39%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.39%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.39%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.39%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.39%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 29.17%  |
| Intel Core i7           | 20        | 27.78%  |
| Intel Celeron           | 6         | 8.33%   |
| Intel Core i3           | 5         | 6.94%   |
| AMD Ryzen 5             | 5         | 6.94%   |
| AMD Ryzen 7             | 3         | 4.17%   |
| Other                   | 2         | 2.78%   |
| Intel Pentium           | 2         | 2.78%   |
| AMD A8                  | 2         | 2.78%   |
| Intel Pentium Dual-Core | 1         | 1.39%   |
| Intel Core 2 Duo        | 1         | 1.39%   |
| AMD Ryzen 3             | 1         | 1.39%   |
| AMD E                   | 1         | 1.39%   |
| AMD A6                  | 1         | 1.39%   |
| AMD A4                  | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 48.61%  |
| 4      | 29        | 40.28%  |
| 6      | 6         | 8.33%   |
| 8      | 2         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 77.78%  |
| 1      | 16        | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 95.83%  |
| Unknown        | 3         | 4.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 43.84%  |
| 0x306a9    | 6         | 8.22%   |
| 0x206a7    | 5         | 6.85%   |
| 0x906ea    | 3         | 4.11%   |
| 0x806ec    | 2         | 2.74%   |
| 0x806eb    | 2         | 2.74%   |
| 0x806e9    | 2         | 2.74%   |
| 0x40651    | 2         | 2.74%   |
| 0x306c3    | 2         | 2.74%   |
| 0x20655    | 2         | 2.74%   |
| 0x1067a    | 2         | 2.74%   |
| 0x07030106 | 2         | 2.74%   |
| 0x806ea    | 1         | 1.37%   |
| 0x806d1    | 1         | 1.37%   |
| 0x406c3    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x20652    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x0a50000c | 1         | 1.37%   |
| 0x08600102 | 1         | 1.37%   |
| 0x0810100b | 1         | 1.37%   |
| 0x06006704 | 1         | 1.37%   |
| 0x05000119 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 22.22%  |
| SandyBridge   | 10        | 13.89%  |
| IvyBridge     | 10        | 13.89%  |
| Zen+          | 4         | 5.56%   |
| Westmere      | 4         | 5.56%   |
| Haswell       | 4         | 5.56%   |
| Goldmont plus | 4         | 5.56%   |
| Zen 3         | 3         | 4.17%   |
| Puma          | 3         | 4.17%   |
| Silvermont    | 2         | 2.78%   |
| Penryn        | 2         | 2.78%   |
| Zen 2         | 1         | 1.39%   |
| Zen           | 1         | 1.39%   |
| Skylake       | 1         | 1.39%   |
| Nehalem       | 1         | 1.39%   |
| K10 Llano     | 1         | 1.39%   |
| Icelake       | 1         | 1.39%   |
| Excavator     | 1         | 1.39%   |
| CometLake     | 1         | 1.39%   |
| Broadwell     | 1         | 1.39%   |
| Bobcat        | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 58.89%  |
| AMD    | 20        | 22.22%  |
| Nvidia | 17        | 18.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 10.87%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 9.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 5.43%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.26%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 3.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 3.26%   |
| Intel HD Graphics 620                                                                    | 2         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.09%   |
| Nvidia TU117M                                                                            | 1         | 1.09%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.09%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.09%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.09%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.09%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 1.09%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.09%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.09%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.09%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.09%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 1.09%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.09%   |
| Nvidia GF106M [GeForce GT 555M]                                                          | 1         | 1.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.09%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.09%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.09%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.09%   |
| Intel HD Graphics 530                                                                    | 1         | 1.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 50%     |
| Intel + Nvidia | 13        | 18.06%  |
| 1 x AMD        | 13        | 18.06%  |
| Intel + AMD    | 4         | 5.56%   |
| 1 x Nvidia     | 3         | 4.17%   |
| 2 x AMD        | 2         | 2.78%   |
| AMD + Nvidia   | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 66        | 91.67%  |
| Proprietary | 6         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 75%     |
| 0.51-1.0   | 9         | 12.5%   |
| 0.01-0.5   | 6         | 8.33%   |
| 7.01-8.0   | 1         | 1.39%   |
| 3.01-4.0   | 1         | 1.39%   |
| 1.01-2.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 28.75%  |
| LG Display              | 18        | 22.5%   |
| Samsung Electronics     | 9         | 11.25%  |
| Chimei Innolux          | 8         | 10%     |
| BOE                     | 8         | 10%     |
| Chi Mei Optoelectronics | 4         | 5%      |
| Sharp                   | 2         | 2.5%    |
| MStar                   | 1         | 1.25%   |
| Lenovo                  | 1         | 1.25%   |
| InfoVision              | 1         | 1.25%   |
| Hewlett-Packard         | 1         | 1.25%   |
| Goldstar                | 1         | 1.25%   |
| Dell                    | 1         | 1.25%   |
| CSO                     | 1         | 1.25%   |
| AOC                     | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 4.94%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 3.7%    |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 3.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 2.47%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 2.47%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 1.23%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 1.23%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch    | 1         | 1.23%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 1.23%   |
| LG Display LCD Monitor LGD1325 1600x900 382x215mm 17.3-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD03D2 1366x768 309x174mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 1         | 1.23%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 1.23%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 1         | 1.23%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                    | 1         | 1.23%   |
| Dell ST2220L DELA065 1920x1080 477x268mm 21.5-inch                       | 1         | 1.23%   |
| CSO LCD Monitor CSO1602 2560x1600 344x215mm 16.0-inch                    | 1         | 1.23%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 46.15%  |
| 1920x1080 (FHD)    | 24        | 30.77%  |
| 1600x900 (HD+)     | 8         | 10.26%  |
| 1680x1050 (WSXGA+) | 3         | 3.85%   |
| 3840x2160 (4K)     | 2         | 2.56%   |
| 1440x900 (WXGA+)   | 2         | 2.56%   |
| 3456x2160          | 1         | 1.28%   |
| 2560x1600          | 1         | 1.28%   |
| 2160x1440          | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 39        | 48.15%  |
| 14     | 14        | 17.28%  |
| 17     | 8         | 9.88%   |
| 13     | 8         | 9.88%   |
| 22     | 3         | 3.7%    |
| 21     | 2         | 2.47%   |
| 11     | 2         | 2.47%   |
| 54     | 1         | 1.23%   |
| 52     | 1         | 1.23%   |
| 27     | 1         | 1.23%   |
| 23     | 1         | 1.23%   |
| 16     | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 71.6%   |
| 351-400     | 8         | 9.88%   |
| 201-300     | 6         | 7.41%   |
| 401-500     | 5         | 6.17%   |
| 501-600     | 2         | 2.47%   |
| 1001-1500   | 2         | 2.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 67        | 89.33%  |
| 16/10 | 7         | 9.33%   |
| 3/2   | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 48.15%  |
| 81-90          | 19        | 23.46%  |
| 121-130        | 8         | 9.88%   |
| 201-250        | 6         | 7.41%   |
| 71-80          | 3         | 3.7%    |
| More than 1000 | 2         | 2.47%   |
| 51-60          | 2         | 2.47%   |
| 301-350        | 1         | 1.23%   |
| 111-120        | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 48.15%  |
| 121-160       | 28        | 34.57%  |
| 51-100        | 8         | 9.88%   |
| More than 240 | 2         | 2.47%   |
| 1-50          | 2         | 2.47%   |
| 161-240       | 2         | 2.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 87.5%   |
| 2     | 9         | 12.5%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 41        | 35.04%  |
| Intel                             | 34        | 29.06%  |
| Qualcomm Atheros                  | 22        | 18.8%   |
| Broadcom                          | 7         | 5.98%   |
| Huawei Technologies               | 3         | 2.56%   |
| Xiaomi                            | 1         | 0.85%   |
| TP-Link                           | 1         | 0.85%   |
| Spreadtrum Communications         | 1         | 0.85%   |
| Samsung Electronics               | 1         | 0.85%   |
| Ralink Technology                 | 1         | 0.85%   |
| Ralink                            | 1         | 0.85%   |
| Ericsson Business Mobile Networks | 1         | 0.85%   |
| DisplayLink                       | 1         | 0.85%   |
| Dell                              | 1         | 0.85%   |
| Broadcom Limited                  | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 16.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 6.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 4.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 4.23%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 3.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 2.82%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.11%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.11%   |
| Huawei E353/E3131                                                 | 3         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 2.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.41%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.41%   |
| Intel Wireless 7265                                               | 2         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.7%    |
| Spreadtrum Spreadtrum Phone                                       | 1         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.7%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.7%    |
| Intel Wireless-AC 9260                                            | 1         | 0.7%    |
| Intel Wireless 7260                                               | 1         | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 43.42%  |
| Qualcomm Atheros                  | 21        | 27.63%  |
| Realtek Semiconductor             | 12        | 15.79%  |
| Broadcom                          | 5         | 6.58%   |
| TP-Link                           | 1         | 1.32%   |
| Ralink Technology                 | 1         | 1.32%   |
| Ralink                            | 1         | 1.32%   |
| Ericsson Business Mobile Networks | 1         | 1.32%   |
| Broadcom Limited                  | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 7.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 7.79%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 6.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 5.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 5.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 5.19%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 5.19%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 3.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.6%    |
| Intel Wireless 8265 / 8275                                     | 2         | 2.6%    |
| Intel Wireless 7265                                            | 2         | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.3%    |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.3%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.3%    |
| Intel Wireless-AC 9260                                         | 1         | 1.3%    |
| Intel Wireless 7260                                            | 1         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.3%    |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.3%    |
| Intel Centrino Wireless-N 2200                                 | 1         | 1.3%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.3%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.3%    |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.3%    |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 1.3%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 35        | 56.45%  |
| Intel                     | 14        | 22.58%  |
| Qualcomm Atheros          | 5         | 8.06%   |
| Huawei Technologies       | 3         | 4.84%   |
| Broadcom                  | 2         | 3.23%   |
| Xiaomi                    | 1         | 1.61%   |
| Spreadtrum Communications | 1         | 1.61%   |
| DisplayLink               | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 38.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 14.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.11%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.76%   |
| Huawei E353/E3131                                                 | 3         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.59%   |
| Spreadtrum Spreadtrum Phone                                       | 1         | 1.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.59%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.59%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 54.14%  |
| Ethernet | 59        | 44.36%  |
| Modem    | 2         | 1.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 71.05%  |
| Ethernet | 22        | 28.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 55        | 76.39%  |
| 1     | 17        | 23.61%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 87.5%   |
| Yes  | 9         | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 39.62%  |
| Realtek Semiconductor           | 8         | 15.09%  |
| Qualcomm Atheros Communications | 6         | 11.32%  |
| Lite-On Technology              | 5         | 9.43%   |
| Dell                            | 3         | 5.66%   |
| Broadcom                        | 3         | 5.66%   |
| IMC Networks                    | 2         | 3.77%   |
| Hewlett-Packard                 | 2         | 3.77%   |
| Foxconn / Hon Hai               | 2         | 3.77%   |
| Foxconn International           | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                           | 6         | 11.32%  |
| Intel Bluetooth wireless interface                | 6         | 11.32%  |
| Qualcomm Atheros  Bluetooth Device                | 4         | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 7.55%   |
| Intel AX200 Bluetooth                             | 4         | 7.55%   |
| Intel AX201 Bluetooth                             | 3         | 5.66%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 3.77%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 3.77%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 3.77%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 3.77%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 1.89%   |
| Lite-On Qualcomm Atheros Bluetooth                | 1         | 1.89%   |
| Lite-On BCM43142A0                                | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.89%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.89%   |
| IMC Networks Bluetooth Device                     | 1         | 1.89%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.89%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 1         | 1.89%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 1.89%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.89%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.89%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 57        | 67.06%  |
| AMD       | 16        | 18.82%  |
| Nvidia    | 9         | 10.59%  |
| GN Netcom | 2         | 2.35%   |
| JMTek     | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 10.48%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 8.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 5.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 5.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 4.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.81%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.9%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.95%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.95%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.95%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.95%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.95%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.95%   |
| GN Netcom Jabra Evolve2 40                                                                        | 1         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.95%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.95%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 30.77%  |
| Samsung Electronics | 3         | 23.08%  |
| Unknown (ABCD)      | 1         | 7.69%   |
| Unknown             | 1         | 7.69%   |
| Team                | 1         | 7.69%   |
| Smart               | 1         | 7.69%   |
| Ramaxel Technology  | 1         | 7.69%   |
| Micron Technology   | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 6.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 6.67%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 6.67%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 6.67%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 6.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 6.67%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 6.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 6.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 6.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 6.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 6.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 6.67%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 6.67%   |
| Ramaxel RAM RMT1970ED48E8F1066 2048MB SODIMM DDR3 1067MT/s       | 1         | 6.67%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 5         | 38.46%  |
| DDR3    | 5         | 38.46%  |
| LPDDR4  | 1         | 7.69%   |
| LPDDR3  | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 76.92%  |
| Row Of Chips | 3         | 23.08%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 46.67%  |
| 4096  | 4         | 26.67%  |
| 2048  | 3         | 20%     |
| 32768 | 1         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 4         | 28.57%  |
| 1600  | 4         | 28.57%  |
| 2667  | 2         | 14.29%  |
| 2400  | 1         | 7.14%   |
| 2133  | 1         | 7.14%   |
| 1067  | 1         | 7.14%   |
| 800   | 1         | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon PIXMA MX920 Series | 1         | 100%    |

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
| Chicony Electronics                    | 15        | 21.74%  |
| Microdia                               | 12        | 17.39%  |
| Realtek Semiconductor                  | 8         | 11.59%  |
| IMC Networks                           | 7         | 10.14%  |
| Acer                                   | 5         | 7.25%   |
| Syntek                                 | 3         | 4.35%   |
| Suyin                                  | 3         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.35%   |
| Sunplus Innovation Technology          | 2         | 2.9%    |
| Quanta                                 | 2         | 2.9%    |
| Bison Electronics                      | 2         | 2.9%    |
| Samsung Electronics                    | 1         | 1.45%   |
| Ricoh                                  | 1         | 1.45%   |
| Logitech                               | 1         | 1.45%   |
| Lite-On Technology                     | 1         | 1.45%   |
| Lenovo                                 | 1         | 1.45%   |
| Cubeternet                             | 1         | 1.45%   |
| Alcor Micro                            | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 5         | 7.25%   |
| Microdia Integrated_Webcam_HD                           | 4         | 5.8%    |
| Microdia Laptop_Integrated_Webcam_E4HD                  | 3         | 4.35%   |
| Chicony Integrated Camera                               | 3         | 4.35%   |
| Acer EasyCamera                                         | 3         | 4.35%   |
| Syntek Integrated Camera                                | 2         | 2.9%    |
| IMC Networks Integrated Camera                          | 2         | 2.9%    |
| Chicony Integrated HP HD Webcam                         | 2         | 2.9%    |
| Syntek Lenovo EasyCamera                                | 1         | 1.45%   |
| Suyin Sony Visual Communication Camera                  | 1         | 1.45%   |
| Suyin Lenovo EasyCamera                                 | 1         | 1.45%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 1.45%   |
| Sunplus USB 2.0 Camera                                  | 1         | 1.45%   |
| Sunplus HD WebCam                                       | 1         | 1.45%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 1.45%   |
| Ricoh HD Webcam                                         | 1         | 1.45%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.45%   |
| Realtek USB Camera                                      | 1         | 1.45%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 1.45%   |
| Realtek Integrated_Webcam_HD                            | 1         | 1.45%   |
| Realtek HP Wide Vision FHD Camera                       | 1         | 1.45%   |
| Realtek HP Truevision HD                                | 1         | 1.45%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 1.45%   |
| Realtek HD WebCam                                       | 1         | 1.45%   |
| Quanta hm1091_techfront                                 | 1         | 1.45%   |
| Quanta HD User Facing                                   | 1         | 1.45%   |
| Microdia Webcam Vitade AF                               | 1         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_2M                    | 1         | 1.45%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 1.45%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 1.45%   |
| Microdia Dell Integrated HD Webcam                      | 1         | 1.45%   |
| Logitech HD Pro Webcam C920                             | 1         | 1.45%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 1.45%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.45%   |
| IMC Networks XiaoMi Webcam                              | 1         | 1.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 1         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 1.45%   |
| IMC Networks Lenovo EasyCamera                          | 1         | 1.45%   |
| IMC Networks EasyCamera                                 | 1         | 1.45%   |
| Cubeternet USB2.0 Camera                                | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 61.54%  |
| Synaptics             | 2         | 15.38%  |
| Elan Microelectronics | 2         | 15.38%  |
| Upek                  | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 23.08%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 15.38%  |
| Elan ELAN:Fingerprint                                  | 2         | 15.38%  |
| Validity Sensors VFS491                                | 1         | 7.69%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.69%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 43        | 59.72%  |
| 1     | 24        | 33.33%  |
| 2     | 5         | 6.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 37.14%  |
| Net/wireless          | 6         | 17.14%  |
| Chipcard              | 6         | 17.14%  |
| Graphics card         | 4         | 11.43%  |
| Multimedia controller | 3         | 8.57%   |
| Storage               | 2         | 5.71%   |
| Camera                | 1         | 2.86%   |

