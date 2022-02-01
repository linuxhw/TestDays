Reborn OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Reborn OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| HP            | EliteBook 8460p             | [634f320f1e](https://linux-hardware.org/?probe=634f320f1e) | May 14, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | Y50-70 20378                | [3bb0e32d6c](https://linux-hardware.org/?probe=3bb0e32d6c) | Apr 02, 2021 |
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
| Lenovo        | IdeaPad S145-15IWL 81MV     | [461cbdb5c5](https://linux-hardware.org/?probe=461cbdb5c5) | Jan 12, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [8d913c63e5](https://linux-hardware.org/?probe=8d913c63e5) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| ASUSTek       | X555YI                      | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Lenovo        | G570 20079                  | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.9.14-arch1-1      | 5         | 8.06%   |
| 5.9.10-arch1-1      | 3         | 4.84%   |
| 5.5.9-arch1-2       | 3         | 4.84%   |
| 5.9.1-arch1-1       | 2         | 3.23%   |
| 5.6.4-arch1-1       | 2         | 3.23%   |
| 5.5.2-arch1-1       | 2         | 3.23%   |
| 5.4.10-arch1-1      | 2         | 3.23%   |
| 5.11.10-arch1-1     | 2         | 3.23%   |
| 5.9.2-zen1-1-zen    | 1         | 1.61%   |
| 5.9.13-arch1-1      | 1         | 1.61%   |
| 5.9.11-arch2-1      | 1         | 1.61%   |
| 5.9.10-zen1-1-zen   | 1         | 1.61%   |
| 5.8.8-arch1-1       | 1         | 1.61%   |
| 5.8.5-arch1-1       | 1         | 1.61%   |
| 5.8.13-arch1-1      | 1         | 1.61%   |
| 5.7.8-arch1-1       | 1         | 1.61%   |
| 5.7.6-arch1-1       | 1         | 1.61%   |
| 5.7.5-arch1-1       | 1         | 1.61%   |
| 5.7.12-arch1-1      | 1         | 1.61%   |
| 5.7.11-arch1-1      | 1         | 1.61%   |
| 5.7.10-arch1-1      | 1         | 1.61%   |
| 5.6.13-arch1-1      | 1         | 1.61%   |
| 5.6.10-arch1-1      | 1         | 1.61%   |
| 5.4.8-arch1-1       | 1         | 1.61%   |
| 5.4.78-1-lts        | 1         | 1.61%   |
| 5.4.77-1-lts        | 1         | 1.61%   |
| 5.4.72-1-lts        | 1         | 1.61%   |
| 5.3.1-arch1-1-ARCH  | 1         | 1.61%   |
| 5.2.9-arch1-1-ARCH  | 1         | 1.61%   |
| 5.15.7-arch1-1      | 1         | 1.61%   |
| 5.15.6-arch2-1      | 1         | 1.61%   |
| 5.14.16-arch1-1     | 1         | 1.61%   |
| 5.14.14-arch1-1     | 1         | 1.61%   |
| 5.13.13-arch1-1     | 1         | 1.61%   |
| 5.13.10-arch1-1     | 1         | 1.61%   |
| 5.12.8-arch1-1      | 1         | 1.61%   |
| 5.12.3-arch1-1      | 1         | 1.61%   |
| 5.11.6-arch1-1      | 1         | 1.61%   |
| 5.11.2-arch1-1      | 1         | 1.61%   |
| 5.11.11-arch1-1     | 1         | 1.61%   |
| 5.11.1-arch1-1      | 1         | 1.61%   |
| 5.10.9-arch1-1      | 1         | 1.61%   |
| 5.10.7-arch1-1      | 1         | 1.61%   |
| 5.10.56-1-lts       | 1         | 1.61%   |
| 5.10.42-1-lts       | 1         | 1.61%   |
| 5.10.23-1-lts       | 1         | 1.61%   |
| 5.10.10-arch1-1     | 1         | 1.61%   |
| 4.19.91-1-lts       | 1         | 1.61%   |
| 4.19.4-arch1-1-ARCH | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 5         | 8.06%   |
| 5.9.10  | 4         | 6.45%   |
| 5.5.9   | 3         | 4.84%   |
| 5.9.1   | 2         | 3.23%   |
| 5.6.4   | 2         | 3.23%   |
| 5.5.2   | 2         | 3.23%   |
| 5.4.10  | 2         | 3.23%   |
| 5.11.10 | 2         | 3.23%   |
| 5.9.2   | 1         | 1.61%   |
| 5.9.13  | 1         | 1.61%   |
| 5.9.11  | 1         | 1.61%   |
| 5.8.8   | 1         | 1.61%   |
| 5.8.5   | 1         | 1.61%   |
| 5.8.13  | 1         | 1.61%   |
| 5.7.8   | 1         | 1.61%   |
| 5.7.6   | 1         | 1.61%   |
| 5.7.5   | 1         | 1.61%   |
| 5.7.12  | 1         | 1.61%   |
| 5.7.11  | 1         | 1.61%   |
| 5.7.10  | 1         | 1.61%   |
| 5.6.13  | 1         | 1.61%   |
| 5.6.10  | 1         | 1.61%   |
| 5.4.8   | 1         | 1.61%   |
| 5.4.78  | 1         | 1.61%   |
| 5.4.77  | 1         | 1.61%   |
| 5.4.72  | 1         | 1.61%   |
| 5.3.1   | 1         | 1.61%   |
| 5.2.9   | 1         | 1.61%   |
| 5.15.7  | 1         | 1.61%   |
| 5.15.6  | 1         | 1.61%   |
| 5.14.16 | 1         | 1.61%   |
| 5.14.14 | 1         | 1.61%   |
| 5.13.13 | 1         | 1.61%   |
| 5.13.10 | 1         | 1.61%   |
| 5.12.8  | 1         | 1.61%   |
| 5.12.3  | 1         | 1.61%   |
| 5.11.6  | 1         | 1.61%   |
| 5.11.2  | 1         | 1.61%   |
| 5.11.11 | 1         | 1.61%   |
| 5.11.1  | 1         | 1.61%   |
| 5.10.9  | 1         | 1.61%   |
| 5.10.7  | 1         | 1.61%   |
| 5.10.56 | 1         | 1.61%   |
| 5.10.42 | 1         | 1.61%   |
| 5.10.23 | 1         | 1.61%   |
| 5.10.10 | 1         | 1.61%   |
| 4.19.91 | 1         | 1.61%   |
| 4.19.4  | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9     | 14        | 22.95%  |
| 5.7     | 6         | 9.84%   |
| 5.4     | 6         | 9.84%   |
| 5.10    | 6         | 9.84%   |
| 5.5     | 5         | 8.2%    |
| 5.11    | 5         | 8.2%    |
| 5.6     | 4         | 6.56%   |
| 5.8     | 3         | 4.92%   |
| 5.15    | 2         | 3.28%   |
| 5.14    | 2         | 3.28%   |
| 5.13    | 2         | 3.28%   |
| 5.12    | 2         | 3.28%   |
| 4.19    | 2         | 3.28%   |
| 5.3     | 1         | 1.64%   |
| 5.2     | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 16        | 26.67%  |
| Deepin            | 9         | 15%     |
| XFCE              | 8         | 13.33%  |
| KDE               | 8         | 13.33%  |
| X-Cinnamon        | 5         | 8.33%   |
| KDE5              | 3         | 5%      |
| Unknown           | 3         | 5%      |
| MATE              | 2         | 3.33%   |
| i3                | 2         | 3.33%   |
| Yaru:ubuntu:GNOME | 1         | 1.67%   |
| LXQt              | 1         | 1.67%   |
| Enlightenment     | 1         | 1.67%   |
| Budgie            | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 48        | 80%     |
| Wayland | 12        | 20%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 88.14%  |
| LightDM | 3         | 5.08%   |
| TDM     | 2         | 3.39%   |
| XDM     | 1         | 1.69%   |
| SDDM    | 1         | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 30.51%  |
| pt_BR   | 8         | 13.56%  |
| en_AU   | 5         | 8.47%   |
| de_DE   | 4         | 6.78%   |
| ru_RU   | 3         | 5.08%   |
| Unknown | 3         | 5.08%   |
| pl_PL   | 2         | 3.39%   |
| nl_NL   | 2         | 3.39%   |
| es_MX   | 2         | 3.39%   |
| es_ES   | 2         | 3.39%   |
| en_GB   | 2         | 3.39%   |
| en_CA   | 2         | 3.39%   |
| sv_SE   | 1         | 1.69%   |
| fr_BE   | 1         | 1.69%   |
| fi_FI   | 1         | 1.69%   |
| es_CL   | 1         | 1.69%   |
| en_DK   | 1         | 1.69%   |
| cs_CZ   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 71.67%  |
| EFI  | 17        | 28.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 47        | 78.33%  |
| Tmpfs   | 5         | 8.33%   |
| Btrfs   | 4         | 6.67%   |
| Unknown | 3         | 5%      |
| Ext3    | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 88.14%  |
| GPT     | 4         | 6.78%   |
| MBR     | 3         | 5.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 98.31%  |
| Yes       | 1         | 1.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 19        | 32.2%   |
| Dell                   | 13        | 22.03%  |
| Hewlett-Packard        | 8         | 13.56%  |
| Acer                   | 8         | 13.56%  |
| ASUSTek Computer       | 4         | 6.78%   |
| Avell High Performance | 2         | 3.39%   |
| Toshiba                | 1         | 1.69%   |
| Sony                   | 1         | 1.69%   |
| Razer                  | 1         | 1.69%   |
| HUAWEI                 | 1         | 1.69%   |
| CyberPowerPC           | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 5.08%   |
| Dell Inspiron 5520                     | 3         | 5.08%   |
| Dell Latitude E6430                    | 2         | 3.39%   |
| Toshiba Satellite C850-C1S             | 1         | 1.69%   |
| Sony VPCEH10EB                         | 1         | 1.69%   |
| Razer Blade                            | 1         | 1.69%   |
| Lenovo Z70-80 80FG                     | 1         | 1.69%   |
| Lenovo Y50-70 20378                    | 1         | 1.69%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 1.69%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 1.69%   |
| Lenovo ThinkPad T410 253725G           | 1         | 1.69%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 1.69%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 1.69%   |
| Lenovo IdeaPad Y580                    | 1         | 1.69%   |
| Lenovo IdeaPad Y450                    | 1         | 1.69%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 1.69%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 1.69%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 1.69%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.69%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 1.69%   |
| Lenovo G570 20079                      | 1         | 1.69%   |
| Lenovo G470 20078                      | 1         | 1.69%   |
| HUAWEI MRC-WX0                         | 1         | 1.69%   |
| HP ProBook 6550b                       | 1         | 1.69%   |
| HP ProBook 640 G5                      | 1         | 1.69%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 1.69%   |
| HP Pavilion g7                         | 1         | 1.69%   |
| HP Pavilion dm1                        | 1         | 1.69%   |
| HP Pavilion 17                         | 1         | 1.69%   |
| HP EliteBook 8460p                     | 1         | 1.69%   |
| HP EliteBook 2560p                     | 1         | 1.69%   |
| Dell Studio 1747                       | 1         | 1.69%   |
| Dell Precision M4600                   | 1         | 1.69%   |
| Dell Latitude E6410                    | 1         | 1.69%   |
| Dell Latitude E6320                    | 1         | 1.69%   |
| Dell Latitude 5500                     | 1         | 1.69%   |
| Dell Inspiron 5584                     | 1         | 1.69%   |
| Dell Inspiron 5421                     | 1         | 1.69%   |
| Dell G7 7588                           | 1         | 1.69%   |
| CyberPowerPC Tracer Series             | 1         | 1.69%   |
| Avell High Performance G1550 FOX       | 1         | 1.69%   |
| Avell High Performance A62 LIV         | 1         | 1.69%   |
| ASUS X555YI                            | 1         | 1.69%   |
| ASUS X540SA                            | 1         | 1.69%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 1.69%   |
| ASUS UX430UAR                          | 1         | 1.69%   |
| Acer Swift SF314-42                    | 1         | 1.69%   |
| Acer Extensa 5635Z                     | 1         | 1.69%   |
| Acer Aspire V3-111P                    | 1         | 1.69%   |
| Acer Aspire F5-573G                    | 1         | 1.69%   |
| Acer Aspire E5-571G                    | 1         | 1.69%   |
| Acer Aspire E5-523                     | 1         | 1.69%   |
| Acer Aspire E1-572                     | 1         | 1.69%   |
| Acer Aspire E1-571                     | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 10        | 16.95%  |
| Acer Aspire                  | 6         | 10.17%  |
| Lenovo ThinkPad              | 5         | 8.47%   |
| Dell Latitude                | 5         | 8.47%   |
| Dell Inspiron                | 5         | 8.47%   |
| HP Pavilion                  | 4         | 6.78%   |
| HP ProBook                   | 2         | 3.39%   |
| HP EliteBook                 | 2         | 3.39%   |
| Toshiba Satellite            | 1         | 1.69%   |
| Sony VPCEH10EB               | 1         | 1.69%   |
| Razer Blade                  | 1         | 1.69%   |
| Lenovo Z70-80                | 1         | 1.69%   |
| Lenovo Y50-70                | 1         | 1.69%   |
| Lenovo G570                  | 1         | 1.69%   |
| Lenovo G470                  | 1         | 1.69%   |
| HUAWEI MRC-WX0               | 1         | 1.69%   |
| Dell Studio                  | 1         | 1.69%   |
| Dell Precision               | 1         | 1.69%   |
| Dell G7                      | 1         | 1.69%   |
| CyberPowerPC Tracer          | 1         | 1.69%   |
| Avell High Performance G1550 | 1         | 1.69%   |
| Avell High Performance A62   | 1         | 1.69%   |
| ASUS X555YI                  | 1         | 1.69%   |
| ASUS X540SA                  | 1         | 1.69%   |
| ASUS VivoBook                | 1         | 1.69%   |
| ASUS UX430UAR                | 1         | 1.69%   |
| Acer Swift                   | 1         | 1.69%   |
| Acer Extensa                 | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 8         | 13.56%  |
| 2012 | 8         | 13.56%  |
| 2011 | 8         | 13.56%  |
| 2020 | 5         | 8.47%   |
| 2018 | 5         | 8.47%   |
| 2013 | 5         | 8.47%   |
| 2010 | 4         | 6.78%   |
| 2009 | 4         | 6.78%   |
| 2016 | 3         | 5.08%   |
| 2015 | 3         | 5.08%   |
| 2014 | 3         | 5.08%   |
| 2017 | 2         | 3.39%   |
| 2021 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 59        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 45.76%  |
| 3.01-4.0   | 12        | 20.34%  |
| 8.01-16.0  | 12        | 20.34%  |
| 16.01-24.0 | 5         | 8.47%   |
| 32.01-64.0 | 3         | 5.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 45.9%   |
| 2.01-3.0  | 20        | 32.79%  |
| 3.01-4.0  | 5         | 8.2%    |
| 0.51-1.0  | 4         | 6.56%   |
| 4.01-8.0  | 3         | 4.92%   |
| 8.01-16.0 | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 78.33%  |
| 2      | 12        | 20%     |
| 3      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 52.54%  |
| Yes       | 28        | 47.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 83.05%  |
| No        | 10        | 16.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 72.88%  |
| No        | 16        | 27.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 13        | 22.03%  |
| Brazil      | 9         | 15.25%  |
| Germany     | 5         | 8.47%   |
| Russia      | 4         | 6.78%   |
| Australia   | 4         | 6.78%   |
| Spain       | 3         | 5.08%   |
| Turkey      | 2         | 3.39%   |
| Poland      | 2         | 3.39%   |
| Netherlands | 2         | 3.39%   |
| Mexico      | 2         | 3.39%   |
| Estonia     | 2         | 3.39%   |
| Canada      | 2         | 3.39%   |
| UK          | 1         | 1.69%   |
| Sweden      | 1         | 1.69%   |
| Portugal    | 1         | 1.69%   |
| Finland     | 1         | 1.69%   |
| Czechia     | 1         | 1.69%   |
| Costa Rica  | 1         | 1.69%   |
| Chile       | 1         | 1.69%   |
| Benin       | 1         | 1.69%   |
| Belgium     | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Melbourne         | 3         | 5%      |
| Aleksandrov       | 3         | 5%      |
| Tallinn           | 2         | 3.33%   |
| Madrid            | 2         | 3.33%   |
| Ankara            | 2         | 3.33%   |
| Zabrze            | 1         | 1.67%   |
| Yadrin            | 1         | 1.67%   |
| Warsaw            | 1         | 1.67%   |
| Waren             | 1         | 1.67%   |
| Vitória          | 1         | 1.67%   |
| Villahermosa      | 1         | 1.67%   |
| Toronto           | 1         | 1.67%   |
| The Hague         | 1         | 1.67%   |
| São Paulo        | 1         | 1.67%   |
| Stabroek          | 1         | 1.67%   |
| Schorndorf        | 1         | 1.67%   |
| Puente Alto       | 1         | 1.67%   |
| Portsmouth        | 1         | 1.67%   |
| Porto União      | 1         | 1.67%   |
| Orem              | 1         | 1.67%   |
| North Bay         | 1         | 1.67%   |
| Newport News      | 1         | 1.67%   |
| New Orleans       | 1         | 1.67%   |
| Mogi Mirim        | 1         | 1.67%   |
| Mexico City       | 1         | 1.67%   |
| Limeira           | 1         | 1.67%   |
| Launceston        | 1         | 1.67%   |
| Lagoa Santa       | 1         | 1.67%   |
| Jalpa de Mendez   | 1         | 1.67%   |
| Jacksonville      | 1         | 1.67%   |
| Itauna            | 1         | 1.67%   |
| Irvine            | 1         | 1.67%   |
| Irun              | 1         | 1.67%   |
| Holly Springs     | 1         | 1.67%   |
| Heredia           | 1         | 1.67%   |
| Helsinki          | 1         | 1.67%   |
| Havlíčkův Brod | 1         | 1.67%   |
| Haarlem           | 1         | 1.67%   |
| Frankfurt am Main | 1         | 1.67%   |
| Esposende         | 1         | 1.67%   |
| Erie              | 1         | 1.67%   |
| Embu              | 1         | 1.67%   |
| Eksjoe            | 1         | 1.67%   |
| Compton           | 1         | 1.67%   |
| Columbus          | 1         | 1.67%   |
| Chagrin Falls     | 1         | 1.67%   |
| Buffalo           | 1         | 1.67%   |
| Bras?�lia         | 1         | 1.67%   |
| Binghamton        | 1         | 1.67%   |
| Berlin            | 1         | 1.67%   |
| Barrow            | 1         | 1.67%   |
| Bad Zwischenahn   | 1         | 1.67%   |
| Abomey-Calavi     | 1         | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 15.71%  |
| Seagate             | 11        | 13     | 15.71%  |
| Samsung Electronics | 10        | 14     | 14.29%  |
| Toshiba             | 7         | 8      | 10%     |
| Unknown             | 4         | 4      | 5.71%   |
| Kingston            | 4         | 5      | 5.71%   |
| Crucial             | 4         | 4      | 5.71%   |
| SanDisk             | 3         | 3      | 4.29%   |
| HGST                | 3         | 3      | 4.29%   |
| Intel               | 2         | 2      | 2.86%   |
| Transcend           | 1         | 1      | 1.43%   |
| SPCC                | 1         | 2      | 1.43%   |
| SK Hynix            | 1         | 1      | 1.43%   |
| Patriot             | 1         | 1      | 1.43%   |
| oyunkey             | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| Hitachi             | 1         | 1      | 1.43%   |
| EMTEC               | 1         | 2      | 1.43%   |
| Dell                | 1         | 1      | 1.43%   |
| ADATA Technology    | 1         | 1      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 3         | 4.11%   |
| WDC WD10JPVT-08A1YT2 1TB             | 2         | 2.74%   |
| Seagate ST9500325AS 500GB            | 2         | 2.74%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2.74%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 2.74%   |
| Intel NVMe SSD Drive 512GB           | 2         | 2.74%   |
| HGST HTS725050A7E630 500GB           | 2         | 2.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 1.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1.37%   |
| WDC WD7500LPCX-60HWST0 752GB         | 1         | 1.37%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.37%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 1.37%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.37%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 1.37%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.37%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1.37%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.37%   |
| Transcend TS1TSSD230S 1024GB         | 1         | 1.37%   |
| Toshiba TR200 240GB SSD              | 1         | 1.37%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 1.37%   |
| Toshiba MQ01ABD100M 1TB              | 1         | 1.37%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1.37%   |
| Toshiba MK5065GSXN 500GB             | 1         | 1.37%   |
| Toshiba MK3265GSX 320GB              | 1         | 1.37%   |
| Toshiba KBG30ZMS256G NVMe 256GB      | 1         | 1.37%   |
| SPCC Solid State Disk 256GB          | 1         | 1.37%   |
| SK Hynix NVMe SSD Drive 256GB        | 1         | 1.37%   |
| Seagate ST9500420AS 500GB            | 1         | 1.37%   |
| Seagate ST9320423AS 320GB            | 1         | 1.37%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1.37%   |
| Seagate ST1000LX015-1U7172 1TB       | 1         | 1.37%   |
| Seagate ST1000LM035-1RK1 1TB         | 1         | 1.37%   |
| Seagate Expansion 1TB                | 1         | 1.37%   |
| SanDisk SSD PLUS 240 GB              | 1         | 1.37%   |
| SanDisk SD9SN8W512G1002 512GB SSD    | 1         | 1.37%   |
| SanDisk SD8SBBU480G1122 480GB SSD    | 1         | 1.37%   |
| Samsung SSD 860 PRO 512GB            | 1         | 1.37%   |
| Samsung SSD 860 PRO 1TB              | 1         | 1.37%   |
| Samsung SSD 850 EVO 250GB            | 1         | 1.37%   |
| Samsung SSD 840 PRO Series 128GB     | 1         | 1.37%   |
| Samsung SSD 840 EVO 120GB            | 1         | 1.37%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 1.37%   |
| Samsung NVMe SSD Drive 500GB         | 1         | 1.37%   |
| Samsung NVMe SSD Drive 256GB         | 1         | 1.37%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 1.37%   |
| Samsung MZVLB512HBJQ-000L2 512GB     | 1         | 1.37%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 1         | 1.37%   |
| Samsung HM321HI 320GB                | 1         | 1.37%   |
| Patriot Burst 480GB SSD              | 1         | 1.37%   |
| oyunkey 480GB                        | 1         | 1.37%   |
| Micron NVMe SSD Drive 256GB          | 1         | 1.37%   |
| LITEONIT LCS-256M6S 256GB SSD        | 1         | 1.37%   |
| Kingston SV300S37A240G 240GB SSD     | 1         | 1.37%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 1.37%   |
| Hitachi HTS725032A9A364 320GB        | 1         | 1.37%   |
| HGST HTS541010B7E610 1TB             | 1         | 1.37%   |
| EMTEC X200 256GB                     | 1         | 1.37%   |
| Dell SD1-U0250 256GB                 | 1         | 1.37%   |
| Crucial CT525MX300SSD4 528GB         | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 36.67%  |
| WDC                 | 9         | 9      | 30%     |
| Toshiba             | 4         | 5      | 13.33%  |
| HGST                | 3         | 3      | 10%     |
| Unknown             | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 21.74%  |
| Kingston            | 4         | 5      | 17.39%  |
| Crucial             | 4         | 4      | 17.39%  |
| SanDisk             | 3         | 3      | 13.04%  |
| WDC                 | 2         | 2      | 8.7%    |
| Transcend           | 1         | 1      | 4.35%   |
| Toshiba             | 1         | 1      | 4.35%   |
| SPCC                | 1         | 2      | 4.35%   |
| Patriot             | 1         | 1      | 4.35%   |
| LITEONIT            | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 30        | 33     | 43.48%  |
| SSD     | 22        | 28     | 31.88%  |
| NVMe    | 11        | 12     | 15.94%  |
| MMC     | 3         | 3      | 4.35%   |
| Unknown | 3         | 4      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 60     | 73.44%  |
| NVMe | 11        | 12     | 17.19%  |
| SAS  | 3         | 5      | 4.69%   |
| MMC  | 3         | 3      | 4.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 37     | 62.96%  |
| 0.51-1.0   | 19        | 23     | 35.19%  |
| 1.01-2.0   | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 26        | 41.27%  |
| 101-250    | 16        | 25.4%   |
| 501-1000   | 9         | 14.29%  |
| 51-100     | 6         | 9.52%   |
| 1001-2000  | 3         | 4.76%   |
| Unknown    | 3         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 24        | 38.1%   |
| 21-50    | 12        | 19.05%  |
| 101-250  | 11        | 17.46%  |
| 51-100   | 8         | 12.7%   |
| 251-500  | 4         | 6.35%   |
| Unknown  | 3         | 4.76%   |
| 501-1000 | 1         | 1.59%   |

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
| Detected | 55        | 73     | 90.16%  |
| Works    | 6         | 7      | 9.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 71.88%  |
| AMD                          | 9         | 14.06%  |
| Samsung Electronics          | 4         | 6.25%   |
| Toshiba America Info Systems | 2         | 3.13%   |
| SK Hynix                     | 1         | 1.56%   |
| Micron Technology            | 1         | 1.56%   |
| ADATA Technology             | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 12.31%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 12.31%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 10.77%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 7.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 6.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 6.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 1.54%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 1.54%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 1         | 1.54%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.54%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.54%   |
| Intel SSD 660P Series                                                                  | 1         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.54%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 78.13%  |
| NVMe | 10        | 15.63%  |
| RAID | 3         | 4.69%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 83.05%  |
| AMD    | 10        | 16.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 5.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 5.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 3.39%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 3.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 3.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 3.39%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.69%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.69%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.69%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.69%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.69%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.69%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.69%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.69%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.69%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.69%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.69%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.69%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.69%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.69%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.69%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.69%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.69%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.69%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.69%   |
| Intel Celeron CPU B820 @ 1.70GHz              | 1         | 1.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.69%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.69%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.69%   |
| AMD A9-9410 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 1.69%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 1.69%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 30.51%  |
| Intel Core i7           | 17        | 28.81%  |
| Intel Core i3           | 5         | 8.47%   |
| Intel Celeron           | 5         | 8.47%   |
| AMD Ryzen 5             | 4         | 6.78%   |
| Intel Pentium           | 2         | 3.39%   |
| AMD A8                  | 2         | 3.39%   |
| Other                   | 1         | 1.69%   |
| Intel Pentium Dual-Core | 1         | 1.69%   |
| Intel Core 2 Duo        | 1         | 1.69%   |
| AMD Ryzen 7             | 1         | 1.69%   |
| AMD Ryzen 3             | 1         | 1.69%   |
| AMD E                   | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 34        | 57.63%  |
| 4      | 20        | 33.9%   |
| 6      | 5         | 8.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 77.97%  |
| 1      | 13        | 22.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 56        | 94.92%  |
| Unknown        | 3         | 5.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 36.67%  |
| 0x306a9    | 6         | 10%     |
| 0x206a7    | 5         | 8.33%   |
| 0x906ea    | 3         | 5%      |
| 0x806ec    | 2         | 3.33%   |
| 0x806eb    | 2         | 3.33%   |
| 0x806e9    | 2         | 3.33%   |
| 0x40651    | 2         | 3.33%   |
| 0x306c3    | 2         | 3.33%   |
| 0x20655    | 2         | 3.33%   |
| 0x1067a    | 2         | 3.33%   |
| 0x806ea    | 1         | 1.67%   |
| 0x406c3    | 1         | 1.67%   |
| 0x306d4    | 1         | 1.67%   |
| 0x20652    | 1         | 1.67%   |
| 0x106e5    | 1         | 1.67%   |
| 0x08600102 | 1         | 1.67%   |
| 0x0810100b | 1         | 1.67%   |
| 0x07030106 | 1         | 1.67%   |
| 0x06006704 | 1         | 1.67%   |
| 0x05000119 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 20.34%  |
| SandyBridge   | 9         | 15.25%  |
| IvyBridge     | 9         | 15.25%  |
| Westmere      | 4         | 6.78%   |
| Haswell       | 4         | 6.78%   |
| Zen+          | 3         | 5.08%   |
| Goldmont plus | 3         | 5.08%   |
| Silvermont    | 2         | 3.39%   |
| Puma          | 2         | 3.39%   |
| Penryn        | 2         | 3.39%   |
| Zen 3         | 1         | 1.69%   |
| Zen 2         | 1         | 1.69%   |
| Zen           | 1         | 1.69%   |
| Skylake       | 1         | 1.69%   |
| Nehalem       | 1         | 1.69%   |
| Excavator     | 1         | 1.69%   |
| CometLake     | 1         | 1.69%   |
| Broadwell     | 1         | 1.69%   |
| Bobcat        | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 60.81%  |
| AMD    | 15        | 20.27%  |
| Nvidia | 14        | 18.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 11.84%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 10.53%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.95%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 3.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.95%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 3.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.95%   |
| Intel HD Graphics 620                                                                    | 2         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.63%   |
| Nvidia TU117M                                                                            | 1         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.32%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.32%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.32%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.32%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 1.32%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.32%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.32%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.32%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 1.32%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.32%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.32%   |
| Intel HD Graphics 530                                                                    | 1         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.32%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.32%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.32%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 1.32%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 1         | 1.32%   |
| AMD Renoir                                                                               | 1         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.32%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.32%   |
| AMD Cezanne                                                                              | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 50.85%  |
| Intel + Nvidia | 11        | 18.64%  |
| 1 x AMD        | 9         | 15.25%  |
| Intel + AMD    | 4         | 6.78%   |
| 1 x Nvidia     | 3         | 5.08%   |
| 2 x AMD        | 2         | 3.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 90%     |
| Proprietary | 6         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 72.88%  |
| 0.51-1.0   | 8         | 13.56%  |
| 0.01-0.5   | 5         | 8.47%   |
| 7.01-8.0   | 1         | 1.69%   |
| 3.01-4.0   | 1         | 1.69%   |
| 1.01-2.0   | 1         | 1.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 30.3%   |
| LG Display              | 14        | 21.21%  |
| Samsung Electronics     | 7         | 10.61%  |
| BOE                     | 7         | 10.61%  |
| Chimei Innolux          | 6         | 9.09%   |
| Chi Mei Optoelectronics | 4         | 6.06%   |
| Sharp                   | 1         | 1.52%   |
| Lenovo                  | 1         | 1.52%   |
| InfoVision              | 1         | 1.52%   |
| Hewlett-Packard         | 1         | 1.52%   |
| Goldstar                | 1         | 1.52%   |
| Dell                    | 1         | 1.52%   |
| CSO                     | 1         | 1.52%   |
| AOC                     | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 5.97%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 4.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 2.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 2.99%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 2.99%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 1.49%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch    | 1         | 1.49%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch             | 1         | 1.49%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 1         | 1.49%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 1.49%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 1         | 1.49%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                    | 1         | 1.49%   |
| Dell ST2220L DELA065 1920x1080 477x268mm 21.5-inch                       | 1         | 1.49%   |
| CSO LCD Monitor CSO1602 2560x1600 344x215mm 16.0-inch                    | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1107 1366x768 256x144mm 11.6-inch | 1         | 1.49%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE06B0 1366x768 344x194mm 15.5-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO4147 1440x900 303x189mm 14.1-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO233E 1600x900 309x174mm 14.0-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO159E 1600x900 380x210mm 17.1-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO149D 1920x1080 381x214mm 17.2-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch            | 1         | 1.49%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 32        | 50%     |
| 1920x1080 (FHD)    | 19        | 29.69%  |
| 1600x900 (HD+)     | 7         | 10.94%  |
| 1680x1050 (WSXGA+) | 3         | 4.69%   |
| 1440x900 (WXGA+)   | 2         | 3.13%   |
| 2560x1600          | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 47.76%  |
| 14     | 11        | 16.42%  |
| 17     | 7         | 10.45%  |
| 13     | 6         | 8.96%   |
| 22     | 3         | 4.48%   |
| 21     | 2         | 2.99%   |
| 11     | 2         | 2.99%   |
| 54     | 1         | 1.49%   |
| 27     | 1         | 1.49%   |
| 23     | 1         | 1.49%   |
| 16     | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 71.64%  |
| 351-400     | 7         | 10.45%  |
| 401-500     | 5         | 7.46%   |
| 201-300     | 4         | 5.97%   |
| 501-600     | 2         | 2.99%   |
| 1001-1500   | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 90.32%  |
| 16/10 | 6         | 9.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 47.76%  |
| 81-90          | 15        | 22.39%  |
| 121-130        | 7         | 10.45%  |
| 201-250        | 5         | 7.46%   |
| 71-80          | 2         | 2.99%   |
| 51-60          | 2         | 2.99%   |
| More than 1000 | 1         | 1.49%   |
| 301-350        | 1         | 1.49%   |
| 151-200        | 1         | 1.49%   |
| 111-120        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 34        | 50.75%  |
| 121-160 | 23        | 34.33%  |
| 51-100  | 8         | 11.94%  |
| 1-50    | 1         | 1.49%   |
| 161-240 | 1         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 52        | 88.14%  |
| 2     | 7         | 11.86%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 30        | 30.93%  |
| Intel                             | 27        | 27.84%  |
| Qualcomm Atheros                  | 21        | 21.65%  |
| Broadcom                          | 6         | 6.19%   |
| Huawei Technologies               | 3         | 3.09%   |
| Xiaomi                            | 1         | 1.03%   |
| TP-Link                           | 1         | 1.03%   |
| Spreadtrum Communications         | 1         | 1.03%   |
| Samsung Electronics               | 1         | 1.03%   |
| Ralink Technology                 | 1         | 1.03%   |
| Ralink                            | 1         | 1.03%   |
| Ericsson Business Mobile Networks | 1         | 1.03%   |
| DisplayLink                       | 1         | 1.03%   |
| Dell                              | 1         | 1.03%   |
| Broadcom Limited                  | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.13%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 4.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 3.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 3.42%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.56%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.56%   |
| Huawei E353/E3131                                                 | 3         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.71%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.85%   |
| Spreadtrum Nokia C30                                              | 1         | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.85%   |
| Intel Wireless 7265                                               | 1         | 0.85%   |
| Intel Wireless 7260                                               | 1         | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.85%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.85%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 0.85%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.85%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.85%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 0.85%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.85%   |
| Dell DW5560 miniPCIe HSPA+ Mobile Broadband Modem                 | 1         | 0.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 1         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 42.62%  |
| Qualcomm Atheros      | 20        | 32.79%  |
| Realtek Semiconductor | 7         | 11.48%  |
| Broadcom              | 4         | 6.56%   |
| TP-Link               | 1         | 1.64%   |
| Ralink Technology     | 1         | 1.64%   |
| Ralink                | 1         | 1.64%   |
| Broadcom Limited      | 1         | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 9.68%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 8.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 6.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 6.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 6.45%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 4.84%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 4.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 4.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 3.23%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.61%   |
| Intel Wireless 7265                                            | 1         | 1.61%   |
| Intel Wireless 7260                                            | 1         | 1.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.61%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.61%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 26        | 49.06%  |
| Intel                     | 13        | 24.53%  |
| Qualcomm Atheros          | 5         | 9.43%   |
| Huawei Technologies       | 3         | 5.66%   |
| Broadcom                  | 2         | 3.77%   |
| Xiaomi                    | 1         | 1.89%   |
| Spreadtrum Communications | 1         | 1.89%   |
| Samsung Electronics       | 1         | 1.89%   |
| DisplayLink               | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18        | 33.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 15.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 11.32%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 5.66%   |
| Huawei E353/E3131                                                 | 3         | 5.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 3.77%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.89%   |
| Spreadtrum Nokia C30                                              | 1         | 1.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.89%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.89%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.89%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 53.64%  |
| Ethernet | 49        | 44.55%  |
| Modem    | 2         | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 55.45%  |
| Ethernet | 45        | 44.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 77.97%  |
| 1     | 13        | 22.03%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 93.22%  |
| Yes  | 4         | 6.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 32.56%  |
| Realtek Semiconductor           | 6         | 13.95%  |
| Qualcomm Atheros Communications | 6         | 13.95%  |
| Lite-On Technology              | 5         | 11.63%  |
| Dell                            | 3         | 6.98%   |
| Broadcom                        | 3         | 6.98%   |
| IMC Networks                    | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Hewlett-Packard                 | 1         | 2.33%   |
| Foxconn International           | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                            | 7         | 16.28%  |
| Realtek Bluetooth Radio                           | 4         | 9.3%    |
| Qualcomm Atheros  Bluetooth Device                | 4         | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 9.3%    |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 4.65%   |
| Intel Bluetooth wireless interface                | 2         | 4.65%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 4.65%   |
| Realtek RTL8723B Bluetooth                        | 1         | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 2.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 2.33%   |
| Lite-On Qualcomm Atheros Bluetooth                | 1         | 2.33%   |
| Lite-On BCM43142A0                                | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 2.33%   |
| IMC Networks Bluetooth Radio                      | 1         | 2.33%   |
| IMC Networks Bluetooth Device                     | 1         | 2.33%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 2.33%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 2.33%   |
| Dell DW375 Bluetooth Module                       | 1         | 2.33%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 2.33%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 49        | 70%     |
| AMD       | 11        | 15.71%  |
| Nvidia    | 7         | 10%     |
| GN Netcom | 2         | 2.86%   |
| JMTek     | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 9.41%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 6         | 7.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 5.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 4.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 4.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.53%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.35%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.18%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.18%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.18%   |
| GN Netcom Jabra Evolve2 40                                                                        | 1         | 1.18%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.18%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 2         | 25%     |
| Unknown             | 1         | 12.5%   |
| Team                | 1         | 12.5%   |
| Smart               | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Ramaxel Technology  | 1         | 12.5%   |
| Micron Technology   | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM 800MT/s                       | 1         | 11.11%  |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 11.11%  |
| Smart RAM SH564128FJ8NZRNSDR 4096MB SODIMM DDR3 1600MT/s    | 1         | 11.11%  |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 11.11%  |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 11.11%  |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 1         | 11.11%  |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 1         | 11.11%  |
| Ramaxel RAM RMT1970ED48E8F1066 2048MB SODIMM DDR3 1066MT/s  | 1         | 11.11%  |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 4         | 50%     |
| DDR4    | 3         | 37.5%   |
| Unknown | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 87.5%   |
| Row Of Chips | 1         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 3         | 33.33%  |
| 4096  | 3         | 33.33%  |
| 2048  | 2         | 22.22%  |
| 32768 | 1         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 3         | 33.33%  |
| 3200  | 2         | 22.22%  |
| 2667  | 2         | 22.22%  |
| 1066  | 1         | 11.11%  |
| 800   | 1         | 11.11%  |

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
| Chicony Electronics                    | 13        | 22.81%  |
| Microdia                               | 9         | 15.79%  |
| Realtek Semiconductor                  | 6         | 10.53%  |
| IMC Networks                           | 6         | 10.53%  |
| Acer                                   | 6         | 10.53%  |
| Syntek                                 | 3         | 5.26%   |
| Suyin                                  | 3         | 5.26%   |
| Quanta                                 | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.51%   |
| Sunplus Innovation Technology          | 1         | 1.75%   |
| Samsung Electronics                    | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Logitech                               | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Lenovo                                 | 1         | 1.75%   |
| Alcor Micro                            | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                          | 5         | 8.77%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 5.26%   |
| Chicony Integrated Camera                                                  | 3         | 5.26%   |
| Acer EasyCamera                                                            | 3         | 5.26%   |
| Syntek Integrated Camera                                                   | 2         | 3.51%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.51%   |
| IMC Networks Integrated Camera                                             | 2         | 3.51%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 3.51%   |
| Acer Lenovo EasyCamera                                                     | 2         | 3.51%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.75%   |
| Suyin Sony Visual Communication Camera                                     | 1         | 1.75%   |
| Suyin Lenovo EasyCamera                                                    | 1         | 1.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.75%   |
| Sunplus HD WebCam                                                          | 1         | 1.75%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.75%   |
| Ricoh HD Webcam                                                            | 1         | 1.75%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.75%   |
| Realtek USB Camera                                                         | 1         | 1.75%   |
| Realtek Laptop_Integrated_Webcam_HD                                        | 1         | 1.75%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.75%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.75%   |
| Realtek HD WebCam                                                          | 1         | 1.75%   |
| Quanta hm1091_techfront                                                    | 1         | 1.75%   |
| Quanta HD User Facing                                                      | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.75%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 1.75%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 1.75%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.75%   |
| Logitech HD Pro Webcam C920                                                | 1         | 1.75%   |
| Lite-On HP Wide Vision HD Camera                                           | 1         | 1.75%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.75%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.75%   |
| IMC Networks EasyCamera                                                    | 1         | 1.75%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.75%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.75%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 1         | 1.75%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.75%   |
| Acer HD Webcam                                                             | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 66.67%  |
| Elan Microelectronics | 2         | 22.22%  |
| Synaptics             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 22.22%  |
| Elan ELAN:Fingerprint                                      | 2         | 22.22%  |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 11.11%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |

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
| 0     | 36        | 61.02%  |
| 1     | 19        | 32.2%   |
| 2     | 4         | 6.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 32.14%  |
| Chipcard              | 6         | 21.43%  |
| Net/wireless          | 5         | 17.86%  |
| Graphics card         | 3         | 10.71%  |
| Storage               | 2         | 7.14%   |
| Multimedia controller | 2         | 7.14%   |
| Camera                | 1         | 3.57%   |

