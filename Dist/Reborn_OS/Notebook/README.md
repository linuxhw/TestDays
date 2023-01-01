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

Total: 91

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Reborn OS         | 59        | 92.19%  |
| Reborn OS Rolling | 5         | 7.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Reborn OS | 64        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-arch1-1     | 5         | 7.46%   |
| 5.9.10-arch1-1     | 3         | 4.48%   |
| 5.5.9-arch1-2      | 3         | 4.48%   |
| 5.9.1-arch1-1      | 2         | 2.99%   |
| 5.6.4-arch1-1      | 2         | 2.99%   |
| 5.5.2-arch1-1      | 2         | 2.99%   |
| 5.4.10-arch1-1     | 2         | 2.99%   |
| 6.0.8-arch1-1      | 1         | 1.49%   |
| 5.9.2-zen1-1-zen   | 1         | 1.49%   |
| 5.9.13-arch1-1     | 1         | 1.49%   |
| 5.9.11-arch2-1     | 1         | 1.49%   |
| 5.9.10-zen1-1-zen  | 1         | 1.49%   |
| 5.8.8-arch1-1      | 1         | 1.49%   |
| 5.8.5-arch1-1      | 1         | 1.49%   |
| 5.8.13-arch1-1     | 1         | 1.49%   |
| 5.7.8-arch1-1      | 1         | 1.49%   |
| 5.7.6-arch1-1      | 1         | 1.49%   |
| 5.7.5-arch1-1      | 1         | 1.49%   |
| 5.7.12-arch1-1     | 1         | 1.49%   |
| 5.7.11-arch1-1     | 1         | 1.49%   |
| 5.7.10-arch1-1     | 1         | 1.49%   |
| 5.6.13-arch1-1     | 1         | 1.49%   |
| 5.6.10-arch1-1     | 1         | 1.49%   |
| 5.4.8-arch1-1      | 1         | 1.49%   |
| 5.4.78-1-lts       | 1         | 1.49%   |
| 5.4.77-1-lts       | 1         | 1.49%   |
| 5.4.72-1-lts       | 1         | 1.49%   |
| 5.3.1-arch1-1-ARCH | 1         | 1.49%   |
| 5.2.9-arch1-1-ARCH | 1         | 1.49%   |
| 5.18.8-arch1-1     | 1         | 1.49%   |
| 5.18.12-arch1-1    | 1         | 1.49%   |
| 5.16.9-arch1-1     | 1         | 1.49%   |
| 5.15.7-arch1-1     | 1         | 1.49%   |
| 5.15.6-arch2-1     | 1         | 1.49%   |
| 5.15.21-1-lts      | 1         | 1.49%   |
| 5.14.16-arch1-1    | 1         | 1.49%   |
| 5.14.14-arch1-1    | 1         | 1.49%   |
| 5.13.13-arch1-1    | 1         | 1.49%   |
| 5.13.10-arch1-1    | 1         | 1.49%   |
| 5.12.8-arch1-1     | 1         | 1.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 5         | 7.46%   |
| 5.9.10  | 4         | 5.97%   |
| 5.5.9   | 3         | 4.48%   |
| 5.9.1   | 2         | 2.99%   |
| 5.6.4   | 2         | 2.99%   |
| 5.5.2   | 2         | 2.99%   |
| 5.4.10  | 2         | 2.99%   |
| 5.11.11 | 2         | 2.99%   |
| 6.0.8   | 1         | 1.49%   |
| 5.9.2   | 1         | 1.49%   |
| 5.9.13  | 1         | 1.49%   |
| 5.9.11  | 1         | 1.49%   |
| 5.8.8   | 1         | 1.49%   |
| 5.8.5   | 1         | 1.49%   |
| 5.8.13  | 1         | 1.49%   |
| 5.7.8   | 1         | 1.49%   |
| 5.7.6   | 1         | 1.49%   |
| 5.7.5   | 1         | 1.49%   |
| 5.7.12  | 1         | 1.49%   |
| 5.7.11  | 1         | 1.49%   |
| 5.7.10  | 1         | 1.49%   |
| 5.6.13  | 1         | 1.49%   |
| 5.6.10  | 1         | 1.49%   |
| 5.4.8   | 1         | 1.49%   |
| 5.4.78  | 1         | 1.49%   |
| 5.4.77  | 1         | 1.49%   |
| 5.4.72  | 1         | 1.49%   |
| 5.3.1   | 1         | 1.49%   |
| 5.2.9   | 1         | 1.49%   |
| 5.18.8  | 1         | 1.49%   |
| 5.18.12 | 1         | 1.49%   |
| 5.16.9  | 1         | 1.49%   |
| 5.15.7  | 1         | 1.49%   |
| 5.15.6  | 1         | 1.49%   |
| 5.15.21 | 1         | 1.49%   |
| 5.14.16 | 1         | 1.49%   |
| 5.14.14 | 1         | 1.49%   |
| 5.13.13 | 1         | 1.49%   |
| 5.13.10 | 1         | 1.49%   |
| 5.12.8  | 1         | 1.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9     | 14        | 21.21%  |
| 5.7     | 6         | 9.09%   |
| 5.4     | 6         | 9.09%   |
| 5.10    | 6         | 9.09%   |
| 5.5     | 5         | 7.58%   |
| 5.11    | 5         | 7.58%   |
| 5.6     | 4         | 6.06%   |
| 5.8     | 3         | 4.55%   |
| 5.15    | 3         | 4.55%   |
| 5.18    | 2         | 3.03%   |
| 5.14    | 2         | 3.03%   |
| 5.13    | 2         | 3.03%   |
| 5.12    | 2         | 3.03%   |
| 4.19    | 2         | 3.03%   |
| 6.0     | 1         | 1.52%   |
| 5.3     | 1         | 1.52%   |
| 5.2     | 1         | 1.52%   |
| 5.16    | 1         | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 16        | 24.62%  |
| XFCE              | 9         | 13.85%  |
| Deepin            | 9         | 13.85%  |
| KDE               | 8         | 12.31%  |
| KDE5              | 7         | 10.77%  |
| X-Cinnamon        | 5         | 7.69%   |
| Unknown           | 3         | 4.62%   |
| MATE              | 2         | 3.08%   |
| i3                | 2         | 3.08%   |
| Yaru:ubuntu:GNOME | 1         | 1.54%   |
| LXQt              | 1         | 1.54%   |
| Enlightenment     | 1         | 1.54%   |
| Budgie            | 1         | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 76.92%  |
| Wayland | 15        | 23.08%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 87.5%   |
| LightDM | 4         | 6.25%   |
| TDM     | 2         | 3.13%   |
| XDM     | 1         | 1.56%   |
| SDDM    | 1         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 20        | 31.25%  |
| pt_BR   | 8         | 12.5%   |
| en_AU   | 5         | 7.81%   |
| de_DE   | 4         | 6.25%   |
| ru_RU   | 3         | 4.69%   |
| en_CA   | 3         | 4.69%   |
| Unknown | 3         | 4.69%   |
| pl_PL   | 2         | 3.13%   |
| nl_NL   | 2         | 3.13%   |
| es_MX   | 2         | 3.13%   |
| es_ES   | 2         | 3.13%   |
| en_GB   | 2         | 3.13%   |
| sv_SE   | 1         | 1.56%   |
| fr_BE   | 1         | 1.56%   |
| fi_FI   | 1         | 1.56%   |
| es_CL   | 1         | 1.56%   |
| en_DK   | 1         | 1.56%   |
| de_CH   | 1         | 1.56%   |
| cs_CZ   | 1         | 1.56%   |
| C       | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 47        | 72.31%  |
| EFI  | 18        | 27.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 78.46%  |
| Tmpfs   | 5         | 7.69%   |
| Btrfs   | 4         | 6.15%   |
| Unknown | 3         | 4.62%   |
| Overlay | 1         | 1.54%   |
| Ext3    | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 87.5%   |
| GPT     | 5         | 7.81%   |
| MBR     | 3         | 4.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 96.88%  |
| Yes       | 2         | 3.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 98.44%  |
| Yes       | 1         | 1.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 20        | 31.25%  |
| Dell                   | 15        | 23.44%  |
| Hewlett-Packard        | 9         | 14.06%  |
| Acer                   | 8         | 12.5%   |
| ASUSTek Computer       | 5         | 7.81%   |
| Avell High Performance | 2         | 3.13%   |
| Toshiba                | 1         | 1.56%   |
| Sony                   | 1         | 1.56%   |
| Razer                  | 1         | 1.56%   |
| HUAWEI                 | 1         | 1.56%   |
| CyberPowerPC           | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 4.69%   |
| Dell Inspiron 5520                     | 3         | 4.69%   |
| Dell Latitude E6430                    | 2         | 3.13%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 3.13%   |
| Toshiba Satellite C850-C1S             | 1         | 1.56%   |
| Sony VPCEH10EB                         | 1         | 1.56%   |
| Razer Blade                            | 1         | 1.56%   |
| Lenovo Z70-80 80FG                     | 1         | 1.56%   |
| Lenovo Y50-70 20378                    | 1         | 1.56%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 1.56%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 1.56%   |
| Lenovo ThinkPad T410 253725G           | 1         | 1.56%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 1.56%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 1.56%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 1.56%   |
| Lenovo IdeaPad Y580                    | 1         | 1.56%   |
| Lenovo IdeaPad Y450                    | 1         | 1.56%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 1.56%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 1.56%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 1.56%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.56%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 1.56%   |
| Lenovo G570 20079                      | 1         | 1.56%   |
| Lenovo G470 20078                      | 1         | 1.56%   |
| HUAWEI MRC-WX0                         | 1         | 1.56%   |
| HP ProBook 6565b                       | 1         | 1.56%   |
| HP ProBook 6550b                       | 1         | 1.56%   |
| HP ProBook 640 G5                      | 1         | 1.56%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 1.56%   |
| HP Pavilion g7                         | 1         | 1.56%   |
| HP Pavilion dm1                        | 1         | 1.56%   |
| HP Pavilion 17                         | 1         | 1.56%   |
| HP EliteBook 8460p                     | 1         | 1.56%   |
| HP EliteBook 2560p                     | 1         | 1.56%   |
| Dell Studio 1747                       | 1         | 1.56%   |
| Dell Precision M4600                   | 1         | 1.56%   |
| Dell Latitude E6410                    | 1         | 1.56%   |
| Dell Latitude E6320                    | 1         | 1.56%   |
| Dell Latitude 5500                     | 1         | 1.56%   |
| Dell Latitude 3410                     | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 10        | 15.63%  |
| Lenovo ThinkPad              | 6         | 9.38%   |
| Dell Latitude                | 6         | 9.38%   |
| Acer Aspire                  | 6         | 9.38%   |
| Dell Inspiron                | 5         | 7.81%   |
| HP Pavilion                  | 4         | 6.25%   |
| HP ProBook                   | 3         | 4.69%   |
| HP EliteBook                 | 2         | 3.13%   |
| ASUS VivoBook                | 2         | 3.13%   |
| Toshiba Satellite            | 1         | 1.56%   |
| Sony VPCEH10EB               | 1         | 1.56%   |
| Razer Blade                  | 1         | 1.56%   |
| Lenovo Z70-80                | 1         | 1.56%   |
| Lenovo Y50-70                | 1         | 1.56%   |
| Lenovo G570                  | 1         | 1.56%   |
| Lenovo G470                  | 1         | 1.56%   |
| HUAWEI MRC-WX0               | 1         | 1.56%   |
| Dell Studio                  | 1         | 1.56%   |
| Dell Precision               | 1         | 1.56%   |
| Dell G7                      | 1         | 1.56%   |
| Dell G15                     | 1         | 1.56%   |
| CyberPowerPC Tracer          | 1         | 1.56%   |
| Avell High Performance G1550 | 1         | 1.56%   |
| Avell High Performance A62   | 1         | 1.56%   |
| ASUS X555YI                  | 1         | 1.56%   |
| ASUS X540SA                  | 1         | 1.56%   |
| ASUS UX430UAR                | 1         | 1.56%   |
| Acer Swift                   | 1         | 1.56%   |
| Acer Extensa                 | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 9         | 14.06%  |
| 2012 | 9         | 14.06%  |
| 2011 | 8         | 12.5%   |
| 2020 | 6         | 9.38%   |
| 2018 | 6         | 9.38%   |
| 2013 | 5         | 7.81%   |
| 2009 | 5         | 7.81%   |
| 2016 | 4         | 6.25%   |
| 2015 | 3         | 4.69%   |
| 2014 | 3         | 4.69%   |
| 2010 | 3         | 4.69%   |
| 2021 | 2         | 3.13%   |
| 2017 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 64        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 64        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 28        | 43.75%  |
| 8.01-16.0  | 13        | 20.31%  |
| 3.01-4.0   | 12        | 18.75%  |
| 16.01-24.0 | 7         | 10.94%  |
| 32.01-64.0 | 4         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 31        | 46.27%  |
| 2.01-3.0  | 22        | 32.84%  |
| 3.01-4.0  | 5         | 7.46%   |
| 0.51-1.0  | 4         | 5.97%   |
| 4.01-8.0  | 3         | 4.48%   |
| 8.01-16.0 | 2         | 2.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 76.92%  |
| 2      | 14        | 21.54%  |
| 3      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 54.69%  |
| Yes       | 29        | 45.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 82.81%  |
| No        | 11        | 17.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 73.44%  |
| No        | 17        | 26.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 15        | 23.44%  |
| Brazil      | 9         | 14.06%  |
| Germany     | 5         | 7.81%   |
| Russia      | 4         | 6.25%   |
| Australia   | 4         | 6.25%   |
| Spain       | 3         | 4.69%   |
| Canada      | 3         | 4.69%   |
| Turkey      | 2         | 3.13%   |
| Poland      | 2         | 3.13%   |
| Netherlands | 2         | 3.13%   |
| Mexico      | 2         | 3.13%   |
| Estonia     | 2         | 3.13%   |
| UK          | 1         | 1.56%   |
| Switzerland | 1         | 1.56%   |
| Sweden      | 1         | 1.56%   |
| Portugal    | 1         | 1.56%   |
| Malaysia    | 1         | 1.56%   |
| Finland     | 1         | 1.56%   |
| Czechia     | 1         | 1.56%   |
| Costa Rica  | 1         | 1.56%   |
| Chile       | 1         | 1.56%   |
| Benin       | 1         | 1.56%   |
| Belgium     | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Melbourne    | 3         | 4.62%   |
| Aleksandrov  | 3         | 4.62%   |
| Toronto      | 2         | 3.08%   |
| Tallinn      | 2         | 3.08%   |
| Zabrze       | 1         | 1.54%   |
| Yadrin       | 1         | 1.54%   |
| Warsaw       | 1         | 1.54%   |
| Villahermosa | 1         | 1.54%   |
| Tres Cantos  | 1         | 1.54%   |
| The Hague    | 1         | 1.54%   |
| St Louis     | 1         | 1.54%   |
| Sao Paulo    | 1         | 1.54%   |
| Santiago     | 1         | 1.54%   |
| Roebel       | 1         | 1.54%   |
| Reynoldsburg | 1         | 1.54%   |
| Potts Camp   | 1         | 1.54%   |
| Portsmouth   | 1         | 1.54%   |
| Porto Uniao  | 1         | 1.54%   |
| Orem         | 1         | 1.54%   |
| North Bay    | 1         | 1.54%   |
| Nijmegen     | 1         | 1.54%   |
| Newport News | 1         | 1.54%   |
| New Orleans  | 1         | 1.54%   |
| Mogi Mirim   | 1         | 1.54%   |
| Mexico City  | 1         | 1.54%   |
| Madrid       | 1         | 1.54%   |
| Limeira      | 1         | 1.54%   |
| Lagoa Santa  | 1         | 1.54%   |
| Kuala Lumpur | 1         | 1.54%   |
| Kestel       | 1         | 1.54%   |
| Kapellen     | 1         | 1.54%   |
| Jonschwil    | 1         | 1.54%   |
| Jever        | 1         | 1.54%   |
| Jacksonville | 1         | 1.54%   |
| Itauna       | 1         | 1.54%   |
| Istanbul     | 1         | 1.54%   |
| Irvine       | 1         | 1.54%   |
| Hobart       | 1         | 1.54%   |
| Heredia      | 1         | 1.54%   |
| Helsinki     | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 14.29%  |
| Seagate             | 11        | 13     | 14.29%  |
| Samsung Electronics | 11        | 15     | 14.29%  |
| Toshiba             | 7         | 8      | 9.09%   |
| Kingston            | 5         | 6      | 6.49%   |
| Unknown             | 4         | 4      | 5.19%   |
| HGST                | 4         | 4      | 5.19%   |
| Crucial             | 4         | 4      | 5.19%   |
| SK hynix            | 3         | 3      | 3.9%    |
| SanDisk             | 3         | 3      | 3.9%    |
| Intel               | 3         | 3      | 3.9%    |
| Transcend           | 1         | 1      | 1.3%    |
| SPCC                | 1         | 2      | 1.3%    |
| Patriot             | 1         | 1      | 1.3%    |
| OYUNKEY             | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEONIT            | 1         | 1      | 1.3%    |
| KIOXIA              | 1         | 1      | 1.3%    |
| Hitachi             | 1         | 1      | 1.3%    |
| Emtec               | 1         | 2      | 1.3%    |
| Dell                | 1         | 1      | 1.3%    |
| ADATA Technology    | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 3         | 3.75%   |
| Intel NVMe SSD Drive 512GB         | 3         | 3.75%   |
| HGST HTS725050A7E630 500GB         | 3         | 3.75%   |
| WDC WD10JPVT-08A1YT2 1TB           | 2         | 2.5%    |
| SK hynix NVMe SSD Drive 256GB      | 2         | 2.5%    |
| Seagate ST9500325AS 500GB          | 2         | 2.5%    |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2.5%    |
| Kingston SA400S37480G 480GB SSD    | 2         | 2.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 1.25%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 1.25%   |
| WDC WD7500LPCX-60HWST0 752GB       | 1         | 1.25%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1.25%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 1.25%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1.25%   |
| WDC WD10SPZX-22Z10T0 1TB           | 1         | 1.25%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1.25%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 1.25%   |
| Unknown SD/MMC/MS PRO 64GB         | 1         | 1.25%   |
| Transcend TS1TSSD230S 1024GB       | 1         | 1.25%   |
| Toshiba TR200 240GB SSD            | 1         | 1.25%   |
| Toshiba NVMe SSD Drive 512GB       | 1         | 1.25%   |
| Toshiba MQ01ABD100M 1TB            | 1         | 1.25%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1.25%   |
| Toshiba MK5065GSXN 500GB           | 1         | 1.25%   |
| Toshiba MK3265GSX 320GB            | 1         | 1.25%   |
| Toshiba KBG30ZMS256G NVMe 256GB    | 1         | 1.25%   |
| SPCC Solid State Disk 256GB        | 1         | 1.25%   |
| SK hynix PC711 NVMe 1TB            | 1         | 1.25%   |
| Seagate ST9500420AS 500GB          | 1         | 1.25%   |
| Seagate ST9320423AS 320GB          | 1         | 1.25%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1.25%   |
| Seagate ST1000LX015-1U7172 1TB     | 1         | 1.25%   |
| Seagate ST1000LM035-1RK1 1TB       | 1         | 1.25%   |
| Seagate Expansion 4TB              | 1         | 1.25%   |
| SanDisk SSD PLUS 240 GB            | 1         | 1.25%   |
| SanDisk SD9SN8W512G1002 512GB SSD  | 1         | 1.25%   |
| SanDisk SD8SBBU480G1122 480GB SSD  | 1         | 1.25%   |
| Samsung SSD 860 PRO 512GB          | 1         | 1.25%   |
| Samsung SSD 860 PRO 1TB            | 1         | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 35.48%  |
| WDC                 | 9         | 9      | 29.03%  |
| Toshiba             | 4         | 5      | 12.9%   |
| HGST                | 4         | 4      | 12.9%   |
| Unknown             | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Hitachi             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 24%     |
| Kingston            | 5         | 6      | 20%     |
| Crucial             | 4         | 4      | 16%     |
| SanDisk             | 3         | 3      | 12%     |
| WDC                 | 2         | 2      | 8%      |
| Transcend           | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| SPCC                | 1         | 2      | 4%      |
| Patriot             | 1         | 1      | 4%      |
| LITEONIT            | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 34     | 40.79%  |
| SSD     | 24        | 30     | 31.58%  |
| NVMe    | 15        | 16     | 19.74%  |
| MMC     | 3         | 3      | 3.95%   |
| Unknown | 3         | 4      | 3.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 63     | 70.42%  |
| NVMe | 15        | 16     | 21.13%  |
| SAS  | 3         | 5      | 4.23%   |
| MMC  | 3         | 3      | 4.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 39     | 62.07%  |
| 0.51-1.0   | 20        | 23     | 34.48%  |
| 3.01-4.0   | 1         | 1      | 1.72%   |
| 1.01-2.0   | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 28        | 41.18%  |
| 101-250    | 18        | 26.47%  |
| 501-1000   | 9         | 13.24%  |
| 51-100     | 6         | 8.82%   |
| 1001-2000  | 3         | 4.41%   |
| Unknown    | 3         | 4.41%   |
| 1-20       | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 26        | 38.24%  |
| 21-50    | 14        | 20.59%  |
| 101-250  | 12        | 17.65%  |
| 51-100   | 8         | 11.76%  |
| 251-500  | 4         | 5.88%   |
| Unknown  | 3         | 4.41%   |
| 501-1000 | 1         | 1.47%   |

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
| Detected | 59        | 79     | 89.39%  |
| Works    | 7         | 8      | 10.61%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 68.49%  |
| AMD                          | 11        | 15.07%  |
| Samsung Electronics          | 4         | 5.48%   |
| SK hynix                     | 3         | 4.11%   |
| Toshiba America Info Systems | 2         | 2.74%   |
| Micron Technology            | 1         | 1.37%   |
| KIOXIA                       | 1         | 1.37%   |
| ADATA Technology             | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 10        | 13.51%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 10.81%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 9.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 6.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 6.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 4.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4.05%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 2.7%    |
| Intel SSD 660P Series                                                                  | 2         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.35%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.35%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 1         | 1.35%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.35%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.35%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.35%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                            | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 55        | 75.34%  |
| NVMe | 14        | 19.18%  |
| RAID | 3         | 4.11%   |
| IDE  | 1         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 81.25%  |
| AMD    | 12        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 4.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 4.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 3.13%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.13%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.13%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 3.13%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.56%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.56%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.56%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.56%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.56%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.56%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 1.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.56%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.56%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.56%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.56%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.56%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.56%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 31.25%  |
| Intel Core i7           | 17        | 26.56%  |
| Intel Core i3           | 5         | 7.81%   |
| Intel Celeron           | 5         | 7.81%   |
| AMD Ryzen 5             | 4         | 6.25%   |
| Other                   | 2         | 3.13%   |
| Intel Pentium           | 2         | 3.13%   |
| AMD Ryzen 7             | 2         | 3.13%   |
| AMD A8                  | 2         | 3.13%   |
| Intel Pentium Dual-Core | 1         | 1.56%   |
| Intel Core 2 Duo        | 1         | 1.56%   |
| AMD Ryzen 3             | 1         | 1.56%   |
| AMD E                   | 1         | 1.56%   |
| AMD A6                  | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 53.13%  |
| 4      | 24        | 37.5%   |
| 6      | 5         | 7.81%   |
| 8      | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 50        | 78.13%  |
| 1      | 14        | 21.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 61        | 95.31%  |
| Unknown        | 3         | 4.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 40%     |
| 0x306a9    | 6         | 9.23%   |
| 0x206a7    | 5         | 7.69%   |
| 0x906ea    | 3         | 4.62%   |
| 0x806ec    | 2         | 3.08%   |
| 0x806eb    | 2         | 3.08%   |
| 0x806e9    | 2         | 3.08%   |
| 0x40651    | 2         | 3.08%   |
| 0x306c3    | 2         | 3.08%   |
| 0x20655    | 2         | 3.08%   |
| 0x1067a    | 2         | 3.08%   |
| 0x806ea    | 1         | 1.54%   |
| 0x806d1    | 1         | 1.54%   |
| 0x406c3    | 1         | 1.54%   |
| 0x306d4    | 1         | 1.54%   |
| 0x20652    | 1         | 1.54%   |
| 0x106e5    | 1         | 1.54%   |
| 0x08600102 | 1         | 1.54%   |
| 0x0810100b | 1         | 1.54%   |
| 0x07030106 | 1         | 1.54%   |
| 0x06006704 | 1         | 1.54%   |
| 0x05000119 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 21.88%  |
| SandyBridge   | 9         | 14.06%  |
| IvyBridge     | 9         | 14.06%  |
| Zen+          | 4         | 6.25%   |
| Westmere      | 4         | 6.25%   |
| Haswell       | 4         | 6.25%   |
| Goldmont plus | 3         | 4.69%   |
| Silvermont    | 2         | 3.13%   |
| Puma          | 2         | 3.13%   |
| Penryn        | 2         | 3.13%   |
| Zen 3         | 1         | 1.56%   |
| Zen 2         | 1         | 1.56%   |
| Zen           | 1         | 1.56%   |
| Skylake       | 1         | 1.56%   |
| Nehalem       | 1         | 1.56%   |
| K10 Llano     | 1         | 1.56%   |
| Icelake       | 1         | 1.56%   |
| Excavator     | 1         | 1.56%   |
| CometLake     | 1         | 1.56%   |
| Broadwell     | 1         | 1.56%   |
| Bobcat        | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 60%     |
| AMD    | 17        | 21.25%  |
| Nvidia | 15        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 10.98%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 9.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 4.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.88%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.66%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 3.66%   |
| Intel HD Graphics 620                                                                    | 2         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.44%   |
| Nvidia TU117M                                                                            | 1         | 1.22%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.22%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.22%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.22%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.22%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.22%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.22%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.22%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 1.22%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.22%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.22%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.22%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.22%   |
| Intel HD Graphics 530                                                                    | 1         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.22%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.22%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.22%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 50%     |
| Intel + Nvidia | 12        | 18.75%  |
| 1 x AMD        | 11        | 17.19%  |
| Intel + AMD    | 4         | 6.25%   |
| 1 x Nvidia     | 3         | 4.69%   |
| 2 x AMD        | 2         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 90.63%  |
| Proprietary | 6         | 9.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 75%     |
| 0.51-1.0   | 8         | 12.5%   |
| 0.01-0.5   | 5         | 7.81%   |
| 7.01-8.0   | 1         | 1.56%   |
| 3.01-4.0   | 1         | 1.56%   |
| 1.01-2.0   | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 29.17%  |
| LG Display              | 15        | 20.83%  |
| Samsung Electronics     | 8         | 11.11%  |
| BOE                     | 8         | 11.11%  |
| Chimei Innolux          | 7         | 9.72%   |
| Chi Mei Optoelectronics | 4         | 5.56%   |
| Sharp                   | 1         | 1.39%   |
| MStar                   | 1         | 1.39%   |
| Lenovo                  | 1         | 1.39%   |
| InfoVision              | 1         | 1.39%   |
| Hewlett-Packard         | 1         | 1.39%   |
| Goldstar                | 1         | 1.39%   |
| Dell                    | 1         | 1.39%   |
| CSO                     | 1         | 1.39%   |
| AOC                     | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 5.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 4.11%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 4.11%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 2.74%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 2.74%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 1.37%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 410x230mm 18.5-inch    | 1         | 1.37%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 1.37%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 1.37%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 1.37%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 1         | 1.37%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 1.37%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 1         | 1.37%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                    | 1         | 1.37%   |
| Dell ST2220L DELA065 1920x1080 477x268mm 21.5-inch                       | 1         | 1.37%   |
| CSO LCD Monitor CSO1602 2560x1600 344x215mm 16.0-inch                    | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch | 1         | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1107 1366x768 256x144mm 11.6-inch | 1         | 1.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 34        | 48.57%  |
| 1920x1080 (FHD)    | 22        | 31.43%  |
| 1600x900 (HD+)     | 7         | 10%     |
| 1680x1050 (WSXGA+) | 3         | 4.29%   |
| 1440x900 (WXGA+)   | 2         | 2.86%   |
| 3840x2160 (4K)     | 1         | 1.43%   |
| 2560x1600          | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 47.95%  |
| 14     | 12        | 16.44%  |
| 17     | 7         | 9.59%   |
| 13     | 7         | 9.59%   |
| 22     | 3         | 4.11%   |
| 21     | 2         | 2.74%   |
| 11     | 2         | 2.74%   |
| 54     | 1         | 1.37%   |
| 52     | 1         | 1.37%   |
| 27     | 1         | 1.37%   |
| 23     | 1         | 1.37%   |
| 16     | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 72.6%   |
| 351-400     | 7         | 9.59%   |
| 401-500     | 5         | 6.85%   |
| 201-300     | 4         | 5.48%   |
| 501-600     | 2         | 2.74%   |
| 1001-1500   | 2         | 2.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 61        | 91.04%  |
| 16/10 | 6         | 8.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 47.95%  |
| 81-90          | 17        | 23.29%  |
| 121-130        | 7         | 9.59%   |
| 201-250        | 6         | 8.22%   |
| More than 1000 | 2         | 2.74%   |
| 71-80          | 2         | 2.74%   |
| 51-60          | 2         | 2.74%   |
| 301-350        | 1         | 1.37%   |
| 111-120        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 36        | 49.32%  |
| 121-160 | 26        | 35.62%  |
| 51-100  | 8         | 10.96%  |
| 1-50    | 2         | 2.74%   |
| 161-240 | 1         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 87.5%   |
| 2     | 8         | 12.5%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 35        | 33.02%  |
| Intel                             | 30        | 28.3%   |
| Qualcomm Atheros                  | 21        | 19.81%  |
| Broadcom                          | 7         | 6.6%    |
| Huawei Technologies               | 3         | 2.83%   |
| Xiaomi                            | 1         | 0.94%   |
| TP-Link                           | 1         | 0.94%   |
| Spreadtrum Communications         | 1         | 0.94%   |
| Samsung Electronics               | 1         | 0.94%   |
| Ralink Technology                 | 1         | 0.94%   |
| Ralink                            | 1         | 0.94%   |
| Ericsson Business Mobile Networks | 1         | 0.94%   |
| DisplayLink                       | 1         | 0.94%   |
| Dell                              | 1         | 0.94%   |
| Broadcom Limited                  | 1         | 0.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 16.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.91%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 3.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.34%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.34%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.34%   |
| Huawei E353/E3131                                                 | 3         | 2.34%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.56%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.78%   |
| Spreadtrum Nokia G21                                              | 1         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.78%   |
| Intel Wireless-AC 9260                                            | 1         | 0.78%   |
| Intel Wireless 7265                                               | 1         | 0.78%   |
| Intel Wireless 7260                                               | 1         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 43.28%  |
| Qualcomm Atheros      | 20        | 29.85%  |
| Realtek Semiconductor | 9         | 13.43%  |
| Broadcom              | 5         | 7.46%   |
| TP-Link               | 1         | 1.49%   |
| Ralink Technology     | 1         | 1.49%   |
| Ralink                | 1         | 1.49%   |
| Broadcom Limited      | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 8.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 7.35%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 7.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 5.88%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 4.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 4.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.41%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 4.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.94%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.47%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.47%   |
| Intel Wireless-AC 9260                                         | 1         | 1.47%   |
| Intel Wireless 7265                                            | 1         | 1.47%   |
| Intel Wireless 7260                                            | 1         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.47%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.47%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 1.47%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 30        | 52.63%  |
| Intel                     | 13        | 22.81%  |
| Qualcomm Atheros          | 5         | 8.77%   |
| Huawei Technologies       | 3         | 5.26%   |
| Broadcom                  | 2         | 3.51%   |
| Xiaomi                    | 1         | 1.75%   |
| Spreadtrum Communications | 1         | 1.75%   |
| Samsung Electronics       | 1         | 1.75%   |
| DisplayLink               | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 36.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 13.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10.34%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 5.17%   |
| Huawei E353/E3131                                                 | 3         | 5.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 3.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.72%   |
| Spreadtrum Nokia G21                                              | 1         | 1.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.72%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.72%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 53.78%  |
| Ethernet | 53        | 44.54%  |
| Modem    | 2         | 1.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 69.12%  |
| Ethernet | 21        | 30.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 78.13%  |
| 1     | 14        | 21.88%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 90.63%  |
| Yes  | 6         | 9.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 36.17%  |
| Realtek Semiconductor           | 6         | 12.77%  |
| Qualcomm Atheros Communications | 6         | 12.77%  |
| Lite-On Technology              | 5         | 10.64%  |
| Dell                            | 3         | 6.38%   |
| Broadcom                        | 3         | 6.38%   |
| IMC Networks                    | 2         | 4.26%   |
| Hewlett-Packard                 | 2         | 4.26%   |
| Foxconn / Hon Hai               | 2         | 4.26%   |
| Foxconn International           | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 5         | 10.64%  |
| Realtek Bluetooth Radio                           | 4         | 8.51%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 8.51%   |
| Intel AX201 Bluetooth                             | 3         | 6.38%   |
| Intel AX200 Bluetooth                             | 3         | 6.38%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 4.26%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 4.26%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 4.26%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.13%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.13%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 2.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 2.13%   |
| Lite-On Qualcomm Atheros Bluetooth                | 1         | 2.13%   |
| Lite-On BCM43142A0                                | 1         | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 2.13%   |
| IMC Networks Bluetooth Radio                      | 1         | 2.13%   |
| IMC Networks Bluetooth Device                     | 1         | 2.13%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.13%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 1         | 2.13%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 2.13%   |
| Dell DW375 Bluetooth Module                       | 1         | 2.13%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.13%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 52        | 68.42%  |
| AMD       | 13        | 17.11%  |
| Nvidia    | 8         | 10.53%  |
| GN Netcom | 2         | 2.63%   |
| JMTek     | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 10.75%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 8.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 7.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 5.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 5.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 3         | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.15%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.08%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.08%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.08%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.08%   |
| GN Netcom Jabra Evolve2 40                                                                        | 1         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.08%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 3         | 33.33%  |
| Unknown             | 1         | 11.11%  |
| Team                | 1         | 11.11%  |
| Smart               | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Ramaxel Technology  | 1         | 11.11%  |
| Micron Technology   | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM 800MT/s                       | 1         | 10%     |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 10%     |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s       | 1         | 10%     |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s   | 1         | 10%     |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 10%     |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 10%     |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 10%     |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 10%     |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s     | 1         | 10%     |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 4         | 44.44%  |
| DDR3    | 4         | 44.44%  |
| Unknown | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 88.89%  |
| Row Of Chips | 1         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 40%     |
| 4096  | 3         | 30%     |
| 2048  | 2         | 20%     |
| 32768 | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 3         | 30%     |
| 1600  | 3         | 30%     |
| 2667  | 2         | 20%     |
| 1067  | 1         | 10%     |
| 800   | 1         | 10%     |

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
| Chicony Electronics                    | 14        | 22.58%  |
| Microdia                               | 11        | 17.74%  |
| Realtek Semiconductor                  | 6         | 9.68%   |
| IMC Networks                           | 6         | 9.68%   |
| Acer                                   | 6         | 9.68%   |
| Syntek                                 | 3         | 4.84%   |
| Suyin                                  | 3         | 4.84%   |
| Sunplus Innovation Technology          | 2         | 3.23%   |
| Quanta                                 | 2         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.23%   |
| Samsung Electronics                    | 1         | 1.61%   |
| Ricoh                                  | 1         | 1.61%   |
| Logitech                               | 1         | 1.61%   |
| Lite-On Technology                     | 1         | 1.61%   |
| Lenovo                                 | 1         | 1.61%   |
| Cubeternet                             | 1         | 1.61%   |
| Alcor Micro                            | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 5         | 8.06%   |
| Microdia Integrated_Webcam_HD                           | 4         | 6.45%   |
| Chicony Integrated Camera                               | 3         | 4.84%   |
| Acer EasyCamera                                         | 3         | 4.84%   |
| Syntek Integrated Camera                                | 2         | 3.23%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 3.23%   |
| IMC Networks Integrated Camera                          | 2         | 3.23%   |
| Chicony Integrated HP HD Webcam                         | 2         | 3.23%   |
| Acer Lenovo EasyCamera                                  | 2         | 3.23%   |
| Syntek Lenovo EasyCamera                                | 1         | 1.61%   |
| Suyin Sony Visual Communication Camera                  | 1         | 1.61%   |
| Suyin Lenovo EasyCamera                                 | 1         | 1.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 1.61%   |
| Sunplus USB 2.0 Camera                                  | 1         | 1.61%   |
| Sunplus HD WebCam                                       | 1         | 1.61%   |
| Samsung Galaxy A5 (MTP)                                 | 1         | 1.61%   |
| Ricoh HD Webcam                                         | 1         | 1.61%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.61%   |
| Realtek USB Camera                                      | 1         | 1.61%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                            | 1         | 1.61%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 1.61%   |
| Realtek HD WebCam                                       | 1         | 1.61%   |
| Quanta hm1091_techfront                                 | 1         | 1.61%   |
| Quanta HD User Facing                                   | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_E4HD                  | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_2M                    | 1         | 1.61%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 1.61%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 1.61%   |
| Microdia Dell Integrated HD Webcam                      | 1         | 1.61%   |
| Logitech HD Pro Webcam C920                             | 1         | 1.61%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 1.61%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 1         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 1.61%   |
| IMC Networks Lenovo EasyCamera                          | 1         | 1.61%   |
| IMC Networks EasyCamera                                 | 1         | 1.61%   |
| Cubeternet USB2.0 Camera                                | 1         | 1.61%   |
| Chicony TOSHIBA Web Camera                              | 1         | 1.61%   |
| Chicony Lenovo EasyCamera                               | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 63.64%  |
| Synaptics             | 2         | 18.18%  |
| Elan Microelectronics | 2         | 18.18%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 27.27%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 18.18%  |
| Elan ELAN:Fingerprint                                      | 2         | 18.18%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 9.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 9.09%   |

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
| 0     | 38        | 59.38%  |
| 1     | 21        | 32.81%  |
| 2     | 5         | 7.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 34.38%  |
| Net/wireless          | 6         | 18.75%  |
| Chipcard              | 6         | 18.75%  |
| Graphics card         | 4         | 12.5%   |
| Storage               | 2         | 6.25%   |
| Multimedia controller | 2         | 6.25%   |
| Camera                | 1         | 3.13%   |

