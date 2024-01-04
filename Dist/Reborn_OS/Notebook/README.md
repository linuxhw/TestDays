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

Total: 106

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Z50-70 20354                | [ba354037ff](https://linux-hardware.org/?probe=ba354037ff) | Dec 07, 2023 |
| HP            | EliteBook 8460p             | [a8792eb2aa](https://linux-hardware.org/?probe=a8792eb2aa) | Nov 07, 2023 |
| Apple         | MacBookPro9,2               | [01c73b9338](https://linux-hardware.org/?probe=01c73b9338) | Oct 18, 2023 |
| Dell          | Inspiron 3537               | [2b79052692](https://linux-hardware.org/?probe=2b79052692) | Aug 28, 2023 |
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
| Reborn OS         | 66        | 86.84%  |
| Reborn OS Rolling | 10        | 13.16%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Reborn OS | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-arch1-1     | 5         | 6.33%   |
| 5.9.10-arch1-1     | 3         | 3.8%    |
| 5.5.9-arch1-2      | 3         | 3.8%    |
| 5.9.1-arch1-1      | 2         | 2.53%   |
| 5.6.4-arch1-1      | 2         | 2.53%   |
| 5.5.2-arch1-1      | 2         | 2.53%   |
| 5.4.10-arch1-1     | 2         | 2.53%   |
| 6.6.4-zen1-1-zen   | 1         | 1.27%   |
| 6.5.7-arch1-1      | 1         | 1.27%   |
| 6.4.3-arch1-2      | 1         | 1.27%   |
| 6.4.12-zen1-1-zen  | 1         | 1.27%   |
| 6.3.4-arch1-1      | 1         | 1.27%   |
| 6.2.8-arch1-1      | 1         | 1.27%   |
| 6.2.7-arch1-1      | 1         | 1.27%   |
| 6.2.2-zen1-1-zen   | 1         | 1.27%   |
| 6.2.2-arch1-1      | 1         | 1.27%   |
| 6.1.61-1-lts       | 1         | 1.27%   |
| 6.1.33-1-lts       | 1         | 1.27%   |
| 6.1.12-arch1-1     | 1         | 1.27%   |
| 6.0.8-arch1-1      | 1         | 1.27%   |
| 5.9.2-zen1-1-zen   | 1         | 1.27%   |
| 5.9.13-arch1-1     | 1         | 1.27%   |
| 5.9.11-arch2-1     | 1         | 1.27%   |
| 5.9.10-zen1-1-zen  | 1         | 1.27%   |
| 5.8.8-arch1-1      | 1         | 1.27%   |
| 5.8.5-arch1-1      | 1         | 1.27%   |
| 5.8.13-arch1-1     | 1         | 1.27%   |
| 5.7.8-arch1-1      | 1         | 1.27%   |
| 5.7.6-arch1-1      | 1         | 1.27%   |
| 5.7.5-arch1-1      | 1         | 1.27%   |
| 5.7.12-arch1-1     | 1         | 1.27%   |
| 5.7.11-arch1-1     | 1         | 1.27%   |
| 5.7.10-arch1-1     | 1         | 1.27%   |
| 5.6.13-arch1-1     | 1         | 1.27%   |
| 5.6.10-arch1-1     | 1         | 1.27%   |
| 5.4.8-arch1-1      | 1         | 1.27%   |
| 5.4.78-1-lts       | 1         | 1.27%   |
| 5.4.77-1-lts       | 1         | 1.27%   |
| 5.4.72-1-lts       | 1         | 1.27%   |
| 5.3.1-arch1-1-ARCH | 1         | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 5         | 6.33%   |
| 5.9.10  | 4         | 5.06%   |
| 5.5.9   | 3         | 3.8%    |
| 6.2.2   | 2         | 2.53%   |
| 5.9.1   | 2         | 2.53%   |
| 5.6.4   | 2         | 2.53%   |
| 5.5.2   | 2         | 2.53%   |
| 5.4.10  | 2         | 2.53%   |
| 5.11.11 | 2         | 2.53%   |
| 6.6.4   | 1         | 1.27%   |
| 6.5.7   | 1         | 1.27%   |
| 6.4.3   | 1         | 1.27%   |
| 6.4.12  | 1         | 1.27%   |
| 6.3.4   | 1         | 1.27%   |
| 6.2.8   | 1         | 1.27%   |
| 6.2.7   | 1         | 1.27%   |
| 6.1.61  | 1         | 1.27%   |
| 6.1.33  | 1         | 1.27%   |
| 6.1.12  | 1         | 1.27%   |
| 6.0.8   | 1         | 1.27%   |
| 5.9.2   | 1         | 1.27%   |
| 5.9.13  | 1         | 1.27%   |
| 5.9.11  | 1         | 1.27%   |
| 5.8.8   | 1         | 1.27%   |
| 5.8.5   | 1         | 1.27%   |
| 5.8.13  | 1         | 1.27%   |
| 5.7.8   | 1         | 1.27%   |
| 5.7.6   | 1         | 1.27%   |
| 5.7.5   | 1         | 1.27%   |
| 5.7.12  | 1         | 1.27%   |
| 5.7.11  | 1         | 1.27%   |
| 5.7.10  | 1         | 1.27%   |
| 5.6.13  | 1         | 1.27%   |
| 5.6.10  | 1         | 1.27%   |
| 5.4.8   | 1         | 1.27%   |
| 5.4.78  | 1         | 1.27%   |
| 5.4.77  | 1         | 1.27%   |
| 5.4.72  | 1         | 1.27%   |
| 5.3.1   | 1         | 1.27%   |
| 5.2.9   | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9     | 14        | 17.95%  |
| 5.7     | 6         | 7.69%   |
| 5.4     | 6         | 7.69%   |
| 5.10    | 6         | 7.69%   |
| 5.5     | 5         | 6.41%   |
| 5.11    | 5         | 6.41%   |
| 6.2     | 4         | 5.13%   |
| 5.6     | 4         | 5.13%   |
| 6.1     | 3         | 3.85%   |
| 5.8     | 3         | 3.85%   |
| 5.15    | 3         | 3.85%   |
| 6.4     | 2         | 2.56%   |
| 5.18    | 2         | 2.56%   |
| 5.14    | 2         | 2.56%   |
| 5.13    | 2         | 2.56%   |
| 5.12    | 2         | 2.56%   |
| 4.19    | 2         | 2.56%   |
| 6.6     | 1         | 1.28%   |
| 6.5     | 1         | 1.28%   |
| 6.3     | 1         | 1.28%   |
| 6.0     | 1         | 1.28%   |
| 5.3     | 1         | 1.28%   |
| 5.2     | 1         | 1.28%   |
| 5.16    | 1         | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 19        | 24.68%  |
| KDE5              | 14        | 18.18%  |
| XFCE              | 10        | 12.99%  |
| Deepin            | 9         | 11.69%  |
| KDE               | 8         | 10.39%  |
| X-Cinnamon        | 6         | 7.79%   |
| Unknown           | 3         | 3.9%    |
| MATE              | 2         | 2.6%    |
| i3                | 2         | 2.6%    |
| Yaru:ubuntu:GNOME | 1         | 1.3%    |
| LXQt              | 1         | 1.3%    |
| Enlightenment     | 1         | 1.3%    |
| Budgie            | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 59        | 76.62%  |
| Wayland | 18        | 23.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 63        | 82.89%  |
| LightDM | 6         | 7.89%   |
| SDDM    | 4         | 5.26%   |
| TDM     | 2         | 2.63%   |
| XDM     | 1         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 28        | 36.84%  |
| pt_BR   | 8         | 10.53%  |
| en_AU   | 5         | 6.58%   |
| de_DE   | 5         | 6.58%   |
| en_GB   | 4         | 5.26%   |
| ru_RU   | 3         | 3.95%   |
| en_CA   | 3         | 3.95%   |
| Unknown | 3         | 3.95%   |
| pl_PL   | 2         | 2.63%   |
| nl_NL   | 2         | 2.63%   |
| es_MX   | 2         | 2.63%   |
| es_ES   | 2         | 2.63%   |
| sv_SE   | 1         | 1.32%   |
| fr_BE   | 1         | 1.32%   |
| fi_FI   | 1         | 1.32%   |
| es_CO   | 1         | 1.32%   |
| es_CL   | 1         | 1.32%   |
| en_DK   | 1         | 1.32%   |
| de_CH   | 1         | 1.32%   |
| cs_CZ   | 1         | 1.32%   |
| C       | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 55        | 71.43%  |
| EFI  | 22        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 58        | 75.32%  |
| Btrfs   | 7         | 9.09%   |
| Tmpfs   | 6         | 7.79%   |
| Unknown | 4         | 5.19%   |
| Overlay | 1         | 1.3%    |
| Ext3    | 1         | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 63        | 82.89%  |
| GPT     | 10        | 13.16%  |
| MBR     | 3         | 3.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 97.37%  |
| Yes       | 2         | 2.63%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 96.05%  |
| Yes       | 3         | 3.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 28.95%  |
| Dell                   | 17        | 22.37%  |
| Hewlett-Packard        | 13        | 17.11%  |
| Acer                   | 8         | 10.53%  |
| ASUSTek Computer       | 5         | 6.58%   |
| Avell High Performance | 2         | 2.63%   |
| Toshiba                | 1         | 1.32%   |
| Timi                   | 1         | 1.32%   |
| Sony                   | 1         | 1.32%   |
| Razer                  | 1         | 1.32%   |
| Medion                 | 1         | 1.32%   |
| HUAWEI                 | 1         | 1.32%   |
| CyberPowerPC           | 1         | 1.32%   |
| Chuwi                  | 1         | 1.32%   |
| Apple                  | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 3.95%   |
| Dell Inspiron 5520                     | 3         | 3.95%   |
| HP EliteBook 8460p                     | 2         | 2.63%   |
| Dell Latitude E6430                    | 2         | 2.63%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 2.63%   |
| Toshiba Satellite C850-C1S             | 1         | 1.32%   |
| Timi A35S                              | 1         | 1.32%   |
| Sony VPCEH10EB                         | 1         | 1.32%   |
| Razer Blade                            | 1         | 1.32%   |
| Medion X6816                           | 1         | 1.32%   |
| Lenovo Z70-80 80FG                     | 1         | 1.32%   |
| Lenovo Z50-70 20354                    | 1         | 1.32%   |
| Lenovo Y50-70 20378                    | 1         | 1.32%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 1.32%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 1.32%   |
| Lenovo ThinkPad T410 253725G           | 1         | 1.32%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 1.32%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 1.32%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 1.32%   |
| Lenovo IdeaPad Y580                    | 1         | 1.32%   |
| Lenovo IdeaPad Y450                    | 1         | 1.32%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 1.32%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 1.32%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 1.32%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 1.32%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.32%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 1.32%   |
| Lenovo G570 20079                      | 1         | 1.32%   |
| Lenovo G470 20078                      | 1         | 1.32%   |
| HUAWEI MRC-WX0                         | 1         | 1.32%   |
| HP ProBook 6565b                       | 1         | 1.32%   |
| HP ProBook 6550b                       | 1         | 1.32%   |
| HP ProBook 640 G5                      | 1         | 1.32%   |
| HP Pavilion Notebook                   | 1         | 1.32%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 1.32%   |
| HP Pavilion Laptop 15-cc6xx            | 1         | 1.32%   |
| HP Pavilion g7                         | 1         | 1.32%   |
| HP Pavilion dm1                        | 1         | 1.32%   |
| HP Pavilion 17                         | 1         | 1.32%   |
| HP EliteBook Folio 9470m               | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 11        | 14.47%  |
| Lenovo ThinkPad              | 6         | 7.89%   |
| HP Pavilion                  | 6         | 7.89%   |
| Dell Latitude                | 6         | 7.89%   |
| Dell Inspiron                | 6         | 7.89%   |
| Acer Aspire                  | 6         | 7.89%   |
| HP EliteBook                 | 4         | 5.26%   |
| HP ProBook                   | 3         | 3.95%   |
| ASUS VivoBook                | 2         | 2.63%   |
| Toshiba Satellite            | 1         | 1.32%   |
| Timi A35S                    | 1         | 1.32%   |
| Sony VPCEH10EB               | 1         | 1.32%   |
| Razer Blade                  | 1         | 1.32%   |
| Medion X6816                 | 1         | 1.32%   |
| Lenovo Z70-80                | 1         | 1.32%   |
| Lenovo Z50-70                | 1         | 1.32%   |
| Lenovo Y50-70                | 1         | 1.32%   |
| Lenovo G570                  | 1         | 1.32%   |
| Lenovo G470                  | 1         | 1.32%   |
| HUAWEI MRC-WX0               | 1         | 1.32%   |
| Dell XPS                     | 1         | 1.32%   |
| Dell Studio                  | 1         | 1.32%   |
| Dell Precision               | 1         | 1.32%   |
| Dell G7                      | 1         | 1.32%   |
| Dell G15                     | 1         | 1.32%   |
| CyberPowerPC Tracer          | 1         | 1.32%   |
| Chuwi GemiBook               | 1         | 1.32%   |
| Avell High Performance G1550 | 1         | 1.32%   |
| Avell High Performance A62   | 1         | 1.32%   |
| ASUS X555YI                  | 1         | 1.32%   |
| ASUS X540SA                  | 1         | 1.32%   |
| ASUS UX430UAR                | 1         | 1.32%   |
| Apple MacBookPro9            | 1         | 1.32%   |
| Acer Swift                   | 1         | 1.32%   |
| Acer Extensa                 | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 11        | 14.47%  |
| 2011 | 11        | 14.47%  |
| 2019 | 10        | 13.16%  |
| 2018 | 8         | 10.53%  |
| 2020 | 6         | 7.89%   |
| 2021 | 5         | 6.58%   |
| 2014 | 5         | 6.58%   |
| 2013 | 5         | 6.58%   |
| 2009 | 5         | 6.58%   |
| 2016 | 4         | 5.26%   |
| 2010 | 3         | 3.95%   |
| 2015 | 2         | 2.63%   |
| 2017 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 76        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 76        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 35        | 46.05%  |
| 8.01-16.0  | 16        | 21.05%  |
| 3.01-4.0   | 12        | 15.79%  |
| 16.01-24.0 | 9         | 11.84%  |
| 32.01-64.0 | 4         | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 33        | 41.77%  |
| 2.01-3.0  | 27        | 34.18%  |
| 4.01-8.0  | 6         | 7.59%   |
| 3.01-4.0  | 6         | 7.59%   |
| 0.51-1.0  | 4         | 5.06%   |
| 8.01-16.0 | 3         | 3.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 76.62%  |
| 2      | 17        | 22.08%  |
| 3      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 56.58%  |
| Yes       | 33        | 43.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 82.89%  |
| No        | 13        | 17.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 73.68%  |
| No        | 20        | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 18        | 23.68%  |
| Brazil      | 10        | 13.16%  |
| Germany     | 7         | 9.21%   |
| Russia      | 4         | 5.26%   |
| Australia   | 4         | 5.26%   |
| Spain       | 3         | 3.95%   |
| Canada      | 3         | 3.95%   |
| UK          | 2         | 2.63%   |
| Turkey      | 2         | 2.63%   |
| Poland      | 2         | 2.63%   |
| Netherlands | 2         | 2.63%   |
| Mexico      | 2         | 2.63%   |
| Estonia     | 2         | 2.63%   |
| Switzerland | 1         | 1.32%   |
| Sweden      | 1         | 1.32%   |
| Romania     | 1         | 1.32%   |
| Portugal    | 1         | 1.32%   |
| Malaysia    | 1         | 1.32%   |
| Ireland     | 1         | 1.32%   |
| Hungary     | 1         | 1.32%   |
| Finland     | 1         | 1.32%   |
| Czechia     | 1         | 1.32%   |
| Costa Rica  | 1         | 1.32%   |
| Colombia    | 1         | 1.32%   |
| Chile       | 1         | 1.32%   |
| Benin       | 1         | 1.32%   |
| Belgium     | 1         | 1.32%   |
| Barbados    | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Melbourne    | 3         | 3.9%    |
| Aleksandrov  | 3         | 3.9%    |
| Toronto      | 2         | 2.6%    |
| Tallinn      | 2         | 2.6%    |
| Sao Paulo    | 2         | 2.6%    |
| Zabrze       | 1         | 1.3%    |
| Yadrin       | 1         | 1.3%    |
| Warsaw       | 1         | 1.3%    |
| Villahermosa | 1         | 1.3%    |
| Tres Cantos  | 1         | 1.3%    |
| The Hague    | 1         | 1.3%    |
| Tatabánya   | 1         | 1.3%    |
| St Louis     | 1         | 1.3%    |
| Santiago     | 1         | 1.3%    |
| Roebel       | 1         | 1.3%    |
| Reynoldsburg | 1         | 1.3%    |
| Rainham      | 1         | 1.3%    |
| Potts Camp   | 1         | 1.3%    |
| Portsmouth   | 1         | 1.3%    |
| Porto Uniao  | 1         | 1.3%    |
| Paderborn    | 1         | 1.3%    |
| Orem         | 1         | 1.3%    |
| North Bay    | 1         | 1.3%    |
| Nijmegen     | 1         | 1.3%    |
| Newport News | 1         | 1.3%    |
| New Orleans  | 1         | 1.3%    |
| Mogi Mirim   | 1         | 1.3%    |
| Mexico City  | 1         | 1.3%    |
| Mesa         | 1         | 1.3%    |
| Madrid       | 1         | 1.3%    |
| Limeira      | 1         | 1.3%    |
| Lawley       | 1         | 1.3%    |
| Lagoa Santa  | 1         | 1.3%    |
| Kuala Lumpur | 1         | 1.3%    |
| Kestel       | 1         | 1.3%    |
| Kapellen     | 1         | 1.3%    |
| Jonschwil    | 1         | 1.3%    |
| Jever        | 1         | 1.3%    |
| Jacksonville | 1         | 1.3%    |
| Itauna       | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 14.29%  |
| WDC                 | 12        | 12     | 13.19%  |
| Seagate             | 11        | 13     | 12.09%  |
| Toshiba             | 8         | 9      | 8.79%   |
| Kingston            | 8         | 9      | 8.79%   |
| Unknown             | 5         | 5      | 5.49%   |
| HGST                | 4         | 4      | 4.4%    |
| Crucial             | 4         | 4      | 4.4%    |
| SK hynix            | 3         | 3      | 3.3%    |
| SanDisk             | 3         | 3      | 3.3%    |
| Intel               | 3         | 3      | 3.3%    |
| Transcend           | 2         | 2      | 2.2%    |
| SPCC                | 2         | 3      | 2.2%    |
| Micron Technology   | 2         | 2      | 2.2%    |
| Patriot             | 1         | 1      | 1.1%    |
| OYUNKEY             | 1         | 1      | 1.1%    |
| Netac               | 1         | 1      | 1.1%    |
| LITEONIT            | 1         | 1      | 1.1%    |
| KIOXIA              | 1         | 1      | 1.1%    |
| Hitachi             | 1         | 1      | 1.1%    |
| Emtec               | 1         | 2      | 1.1%    |
| Dell                | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |
| ADATA Technology    | 1         | 1      | 1.1%    |
| A-DATA Technology   | 1         | 2      | 1.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                | 4         | 4.21%   |
| Kingston SA400S37480G 480GB SSD       | 3         | 3.16%   |
| Intel NVMe SSD Drive 512GB            | 3         | 3.16%   |
| HGST HTS725050A7E630 500GB            | 3         | 3.16%   |
| WDC WD10JPVT-08A1YT2 1TB              | 2         | 2.11%   |
| SK hynix NVMe SSD Drive 256GB         | 2         | 2.11%   |
| Seagate ST9500325AS 500GB             | 2         | 2.11%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2.11%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2.11%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 1.05%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1.05%   |
| WDC WD7500LPCX-60HWST0 752GB          | 1         | 1.05%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1.05%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 1.05%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 1.05%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 1.05%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1.05%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1.05%   |
| Unknown SD/MMC/MS PRO 512GB           | 1         | 1.05%   |
| Transcend TS1TSSD230S 1TB             | 1         | 1.05%   |
| Transcend TS128GMSA370 128GB SSD      | 1         | 1.05%   |
| Toshiba XG6 NVMe SSD Controller 512GB | 1         | 1.05%   |
| Toshiba TR200 240GB SSD               | 1         | 1.05%   |
| Toshiba NVMe SSD Drive 512GB          | 1         | 1.05%   |
| Toshiba MQ01ABD100M 1TB               | 1         | 1.05%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1.05%   |
| Toshiba MK5065GSXN 500GB              | 1         | 1.05%   |
| Toshiba MK3265GSX 320GB               | 1         | 1.05%   |
| Toshiba KBG30ZMS256G NVMe 256GB       | 1         | 1.05%   |
| SPCC Solid State Disk 512GB           | 1         | 1.05%   |
| SPCC Solid State Disk 256GB           | 1         | 1.05%   |
| SK hynix PC711 NVMe 1TB               | 1         | 1.05%   |
| Seagate ST9500420AS 500GB             | 1         | 1.05%   |
| Seagate ST9320423AS 320GB             | 1         | 1.05%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1.05%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1.05%   |
| Seagate ST1000LM035-1RK1 1TB          | 1         | 1.05%   |
| Seagate Expansion 2TB                 | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 33.33%  |
| WDC                 | 10        | 10     | 30.3%   |
| Toshiba             | 4         | 5      | 12.12%  |
| HGST                | 4         | 4      | 12.12%  |
| Unknown             | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 8         | 9      | 24.24%  |
| Samsung Electronics | 7         | 10     | 21.21%  |
| Crucial             | 4         | 4      | 12.12%  |
| SanDisk             | 3         | 3      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| Transcend           | 2         | 2      | 6.06%   |
| SPCC                | 2         | 3      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 2      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 36     | 36.67%  |
| SSD     | 32        | 39     | 35.56%  |
| NVMe    | 18        | 19     | 20%     |
| MMC     | 4         | 4      | 4.44%   |
| Unknown | 3         | 4      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 74     | 70.24%  |
| NVMe | 18        | 19     | 21.43%  |
| MMC  | 4         | 4      | 4.76%   |
| SAS  | 3         | 5      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 46     | 62.32%  |
| 0.51-1.0   | 25        | 28     | 36.23%  |
| 1.01-2.0   | 1         | 1      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 30        | 37.5%   |
| 101-250    | 23        | 28.75%  |
| 501-1000   | 12        | 15%     |
| 51-100     | 6         | 7.5%    |
| 1001-2000  | 4         | 5%      |
| Unknown    | 3         | 3.75%   |
| 2001-3000  | 1         | 1.25%   |
| 1-20       | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 28        | 35%     |
| 21-50    | 17        | 21.25%  |
| 101-250  | 13        | 16.25%  |
| 51-100   | 12        | 15%     |
| 251-500  | 5         | 6.25%   |
| Unknown  | 3         | 3.75%   |
| 501-1000 | 2         | 2.5%    |

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
| Detected | 67        | 90     | 85.9%   |
| Works    | 11        | 12     | 14.1%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 58        | 67.44%  |
| AMD                          | 13        | 15.12%  |
| Samsung Electronics          | 5         | 5.81%   |
| Toshiba America Info Systems | 3         | 3.49%   |
| SK hynix                     | 3         | 3.49%   |
| Micron Technology            | 2         | 2.33%   |
| KIOXIA                       | 1         | 1.16%   |
| ADATA Technology             | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 12        | 13.64%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 10        | 11.36%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 8         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 6.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 5.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 2.27%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 2.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 2         | 2.27%   |
| Intel SSD 660P Series                                                                  | 2         | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 2.27%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 1         | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 1.14%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 1         | 1.14%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 1         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 1         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.14%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.14%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                             | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 64        | 74.42%  |
| NVMe | 17        | 19.77%  |
| RAID | 3         | 3.49%   |
| IDE  | 2         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 80.26%  |
| AMD    | 15        | 19.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 5.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 3.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 3.95%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 3.95%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 2.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 2.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.63%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 2.63%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.63%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.32%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.32%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.32%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.32%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.32%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.32%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.32%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 30.26%  |
| Intel Core i7           | 20        | 26.32%  |
| Intel Core i3           | 7         | 9.21%   |
| Intel Celeron           | 6         | 7.89%   |
| AMD Ryzen 5             | 5         | 6.58%   |
| AMD Ryzen 7             | 3         | 3.95%   |
| Other                   | 2         | 2.63%   |
| Intel Pentium           | 2         | 2.63%   |
| AMD A8                  | 2         | 2.63%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Core 2 Duo        | 1         | 1.32%   |
| AMD Ryzen 3             | 1         | 1.32%   |
| AMD E                   | 1         | 1.32%   |
| AMD A6                  | 1         | 1.32%   |
| AMD A4                  | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 51.32%  |
| 4      | 29        | 38.16%  |
| 6      | 6         | 7.89%   |
| 8      | 2         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 78.95%  |
| 1      | 16        | 21.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 73        | 96.05%  |
| Unknown        | 3         | 3.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 46.75%  |
| 0x306a9    | 6         | 7.79%   |
| 0x206a7    | 5         | 6.49%   |
| 0x906ea    | 3         | 3.9%    |
| 0x806ec    | 2         | 2.6%    |
| 0x806eb    | 2         | 2.6%    |
| 0x806e9    | 2         | 2.6%    |
| 0x40651    | 2         | 2.6%    |
| 0x306c3    | 2         | 2.6%    |
| 0x20655    | 2         | 2.6%    |
| 0x1067a    | 2         | 2.6%    |
| 0x07030106 | 2         | 2.6%    |
| 0x806ea    | 1         | 1.3%    |
| 0x806d1    | 1         | 1.3%    |
| 0x406c3    | 1         | 1.3%    |
| 0x306d4    | 1         | 1.3%    |
| 0x20652    | 1         | 1.3%    |
| 0x106e5    | 1         | 1.3%    |
| 0x0a50000c | 1         | 1.3%    |
| 0x08600102 | 1         | 1.3%    |
| 0x0810100b | 1         | 1.3%    |
| 0x06006704 | 1         | 1.3%    |
| 0x05000119 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 21.05%  |
| SandyBridge   | 11        | 14.47%  |
| IvyBridge     | 11        | 14.47%  |
| Haswell       | 6         | 7.89%   |
| Zen+          | 4         | 5.26%   |
| Westmere      | 4         | 5.26%   |
| Goldmont plus | 4         | 5.26%   |
| Zen 3         | 3         | 3.95%   |
| Puma          | 3         | 3.95%   |
| Silvermont    | 2         | 2.63%   |
| Penryn        | 2         | 2.63%   |
| Zen 2         | 1         | 1.32%   |
| Zen           | 1         | 1.32%   |
| Skylake       | 1         | 1.32%   |
| Nehalem       | 1         | 1.32%   |
| K10 Llano     | 1         | 1.32%   |
| Icelake       | 1         | 1.32%   |
| Excavator     | 1         | 1.32%   |
| CometLake     | 1         | 1.32%   |
| Broadwell     | 1         | 1.32%   |
| Bobcat        | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 58.95%  |
| AMD    | 21        | 22.11%  |
| Nvidia | 18        | 18.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 10.31%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 10.31%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 5.15%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 4.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.09%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 3.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 3.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.06%   |
| Intel HD Graphics 620                                                                    | 2         | 2.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.06%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 2.06%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 1.03%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.03%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 1.03%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.03%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 1.03%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.03%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.03%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 1.03%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.03%   |
| Nvidia GF106M [GeForce GT 555M]                                                          | 1         | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.03%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.03%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1         | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.03%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.03%   |
| Intel HD Graphics 530                                                                    | 1         | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 50%     |
| Intel + Nvidia | 14        | 18.42%  |
| 1 x AMD        | 14        | 18.42%  |
| Intel + AMD    | 4         | 5.26%   |
| 1 x Nvidia     | 3         | 3.95%   |
| 2 x AMD        | 2         | 2.63%   |
| AMD + Nvidia   | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 90.79%  |
| Proprietary | 7         | 9.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 76.32%  |
| 0.51-1.0   | 9         | 11.84%  |
| 0.01-0.5   | 6         | 7.89%   |
| 7.01-8.0   | 1         | 1.32%   |
| 3.01-4.0   | 1         | 1.32%   |
| 1.01-2.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 29.76%  |
| LG Display              | 18        | 21.43%  |
| Samsung Electronics     | 9         | 10.71%  |
| BOE                     | 9         | 10.71%  |
| Chimei Innolux          | 8         | 9.52%   |
| Chi Mei Optoelectronics | 4         | 4.76%   |
| Sharp                   | 2         | 2.38%   |
| MStar                   | 1         | 1.19%   |
| Lenovo                  | 1         | 1.19%   |
| InfoVision              | 1         | 1.19%   |
| Hewlett-Packard         | 1         | 1.19%   |
| Goldstar                | 1         | 1.19%   |
| Dell                    | 1         | 1.19%   |
| CSO                     | 1         | 1.19%   |
| Apple                   | 1         | 1.19%   |
| AOC                     | 1         | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 4.71%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 3.53%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 3.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 2.35%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 2.35%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 1.18%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 1.18%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 1.18%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 1.18%   |
| Samsung Electronics SMS22A300B SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch    | 1         | 1.18%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 1         | 1.18%   |
| LG Display LCD Monitor LGD1325 1600x900 382x215mm 17.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD03D2 1366x768 309x174mm 14.0-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.18%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 1         | 1.18%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 1.18%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 1         | 1.18%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                    | 1         | 1.18%   |
| Dell ST2220L DELA065 1920x1080 477x268mm 21.5-inch                       | 1         | 1.18%   |
| CSO LCD Monitor CSO1602 2560x1600 344x215mm 16.0-inch                    | 1         | 1.18%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 37        | 45.12%  |
| 1920x1080 (FHD)    | 25        | 30.49%  |
| 1600x900 (HD+)     | 9         | 10.98%  |
| 1680x1050 (WSXGA+) | 3         | 3.66%   |
| 3840x2160 (4K)     | 2         | 2.44%   |
| 1440x900 (WXGA+)   | 2         | 2.44%   |
| 3456x2160          | 1         | 1.22%   |
| 2560x1600          | 1         | 1.22%   |
| 2160x1440          | 1         | 1.22%   |
| 1280x800 (WXGA)    | 1         | 1.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 41        | 48.24%  |
| 14     | 15        | 17.65%  |
| 13     | 9         | 10.59%  |
| 17     | 8         | 9.41%   |
| 22     | 3         | 3.53%   |
| 21     | 2         | 2.35%   |
| 11     | 2         | 2.35%   |
| 54     | 1         | 1.18%   |
| 52     | 1         | 1.18%   |
| 27     | 1         | 1.18%   |
| 23     | 1         | 1.18%   |
| 16     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 71.76%  |
| 351-400     | 8         | 9.41%   |
| 201-300     | 7         | 8.24%   |
| 401-500     | 5         | 5.88%   |
| 501-600     | 2         | 2.35%   |
| 1001-1500   | 2         | 2.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 70        | 88.61%  |
| 16/10 | 8         | 10.13%  |
| 3/2   | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 48.24%  |
| 81-90          | 21        | 24.71%  |
| 121-130        | 8         | 9.41%   |
| 201-250        | 6         | 7.06%   |
| 71-80          | 3         | 3.53%   |
| More than 1000 | 2         | 2.35%   |
| 51-60          | 2         | 2.35%   |
| 301-350        | 1         | 1.18%   |
| 111-120        | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 48.24%  |
| 121-160       | 30        | 35.29%  |
| 51-100        | 8         | 9.41%   |
| More than 240 | 2         | 2.35%   |
| 1-50          | 2         | 2.35%   |
| 161-240       | 2         | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 88.16%  |
| 2     | 9         | 11.84%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 43        | 35.25%  |
| Intel                             | 35        | 28.69%  |
| Qualcomm Atheros                  | 23        | 18.85%  |
| Broadcom                          | 8         | 6.56%   |
| Huawei Technologies               | 3         | 2.46%   |
| Xiaomi                            | 1         | 0.82%   |
| TP-Link                           | 1         | 0.82%   |
| Spreadtrum Communications         | 1         | 0.82%   |
| Samsung Electronics               | 1         | 0.82%   |
| Ralink Technology                 | 1         | 0.82%   |
| Ralink                            | 1         | 0.82%   |
| Ericsson Business Mobile Networks | 1         | 0.82%   |
| DisplayLink                       | 1         | 0.82%   |
| Dell                              | 1         | 0.82%   |
| Broadcom Limited                  | 1         | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 16.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 3.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 3.97%   |
| Intel Centrino Ultimate-N 6300                                    | 6         | 3.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.65%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.99%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.99%   |
| Huawei E353/E3131                                                 | 3         | 1.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.32%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.32%   |
| Intel Wireless 7265                                               | 2         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.66%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.66%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.66%   |
| Intel Wireless-AC 9260                                            | 1         | 0.66%   |
| Intel Wireless 7260                                               | 1         | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 34        | 42.5%   |
| Qualcomm Atheros                  | 22        | 27.5%   |
| Realtek Semiconductor             | 13        | 16.25%  |
| Broadcom                          | 6         | 7.5%    |
| TP-Link                           | 1         | 1.25%   |
| Ralink Technology                 | 1         | 1.25%   |
| Ralink                            | 1         | 1.25%   |
| Ericsson Business Mobile Networks | 1         | 1.25%   |
| Broadcom Limited                  | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 7.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 7.32%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 7.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 6.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.88%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 3.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.66%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 3.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 2.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.44%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.44%   |
| Intel Wireless 7265                                            | 2         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.22%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.22%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.22%   |
| Intel Wireless-AC 9260                                         | 1         | 1.22%   |
| Intel Wireless 7260                                            | 1         | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.22%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.22%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 1.22%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.22%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.22%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.22%   |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 37        | 56.06%  |
| Intel                     | 15        | 22.73%  |
| Qualcomm Atheros          | 5         | 7.58%   |
| Huawei Technologies       | 3         | 4.55%   |
| Broadcom                  | 3         | 4.55%   |
| Xiaomi                    | 1         | 1.52%   |
| Spreadtrum Communications | 1         | 1.52%   |
| DisplayLink               | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 37.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 14.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 11.94%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.48%   |
| Huawei E353/E3131                                                 | 3         | 4.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.49%   |
| Spreadtrum Unisoc Phone                                           | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.49%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.49%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 1.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 53.9%   |
| Ethernet | 63        | 44.68%  |
| Modem    | 2         | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 72.5%   |
| Ethernet | 22        | 27.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 77.63%  |
| 1     | 17        | 22.37%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 88.16%  |
| Yes  | 9         | 11.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 37.5%   |
| Realtek Semiconductor           | 9         | 16.07%  |
| Qualcomm Atheros Communications | 6         | 10.71%  |
| Lite-On Technology              | 5         | 8.93%   |
| Hewlett-Packard                 | 3         | 5.36%   |
| Dell                            | 3         | 5.36%   |
| Broadcom                        | 3         | 5.36%   |
| IMC Networks                    | 2         | 3.57%   |
| Foxconn / Hon Hai               | 2         | 3.57%   |
| Foxconn International           | 1         | 1.79%   |
| Apple                           | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                           | 6         | 10.71%  |
| Intel Bluetooth wireless interface                | 6         | 10.71%  |
| Qualcomm Atheros  Bluetooth Device                | 4         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 7.14%   |
| Intel AX200 Bluetooth                             | 4         | 7.14%   |
| Intel Bluetooth Device                            | 3         | 5.36%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 5.36%   |
| Realtek RTL8723B Bluetooth                        | 2         | 3.57%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 3.57%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 1.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 1.79%   |
| Lite-On Qualcomm Atheros Bluetooth                | 1         | 1.79%   |
| Lite-On BCM43142A0                                | 1         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.79%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.79%   |
| IMC Networks Bluetooth Device                     | 1         | 1.79%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.79%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 1         | 1.79%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 1.79%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.79%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.79%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 61        | 67.78%  |
| AMD       | 17        | 18.89%  |
| Nvidia    | 9         | 10%     |
| GN Netcom | 2         | 2.22%   |
| JMTek     | 1         | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 8.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 5.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 4.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.89%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.89%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.89%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.89%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.89%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.89%   |
| GN Netcom Jabra Evolve2 40                                                                        | 1         | 0.89%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.89%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 28.57%  |
| Samsung Electronics | 4         | 28.57%  |
| Unknown (ABCD)      | 1         | 7.14%   |
| Unknown             | 1         | 7.14%   |
| Team                | 1         | 7.14%   |
| Smart               | 1         | 7.14%   |
| Ramaxel Technology  | 1         | 7.14%   |
| Micron Technology   | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 6.25%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 6.25%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 6.25%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 6.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 6.25%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 6.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 6.25%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 6.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 6.25%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 6.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 6.25%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 6.25%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 6.25%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 6         | 42.86%  |
| DDR4    | 5         | 35.71%  |
| LPDDR4  | 1         | 7.14%   |
| LPDDR3  | 1         | 7.14%   |
| Unknown | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 78.57%  |
| Row Of Chips | 3         | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 43.75%  |
| 4096  | 5         | 31.25%  |
| 2048  | 3         | 18.75%  |
| 32768 | 1         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 33.33%  |
| 3200  | 4         | 26.67%  |
| 2667  | 2         | 13.33%  |
| 2400  | 1         | 6.67%   |
| 2133  | 1         | 6.67%   |
| 1067  | 1         | 6.67%   |
| 800   | 1         | 6.67%   |

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
| Chicony Electronics                    | 16        | 21.92%  |
| Microdia                               | 12        | 16.44%  |
| Realtek Semiconductor                  | 9         | 12.33%  |
| IMC Networks                           | 7         | 9.59%   |
| Syntek                                 | 4         | 5.48%   |
| Acer                                   | 4         | 5.48%   |
| Suyin                                  | 3         | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.11%   |
| Bison Electronics                      | 3         | 4.11%   |
| Sunplus Innovation Technology          | 2         | 2.74%   |
| Quanta                                 | 2         | 2.74%   |
| Samsung Electronics                    | 1         | 1.37%   |
| Ricoh                                  | 1         | 1.37%   |
| Logitech                               | 1         | 1.37%   |
| Lite-On Technology                     | 1         | 1.37%   |
| Lenovo                                 | 1         | 1.37%   |
| Cubeternet                             | 1         | 1.37%   |
| Apple                                  | 1         | 1.37%   |
| Alcor Micro                            | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 5         | 6.85%   |
| Microdia Integrated_Webcam_HD                           | 4         | 5.48%   |
| Microdia Laptop_Integrated_Webcam_E4HD                  | 3         | 4.11%   |
| Chicony Integrated HP HD Webcam                         | 3         | 4.11%   |
| Chicony Integrated Camera                               | 3         | 4.11%   |
| Acer EasyCamera                                         | 3         | 4.11%   |
| Syntek Lenovo EasyCamera                                | 2         | 2.74%   |
| Syntek Integrated Camera                                | 2         | 2.74%   |
| Realtek Integrated_Webcam_HD                            | 2         | 2.74%   |
| IMC Networks Integrated Camera                          | 2         | 2.74%   |
| Suyin Sony Visual Communication Camera                  | 1         | 1.37%   |
| Suyin Lenovo EasyCamera                                 | 1         | 1.37%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 1.37%   |
| Sunplus USB 2.0 Camera                                  | 1         | 1.37%   |
| Sunplus HD WebCam                                       | 1         | 1.37%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 1.37%   |
| Ricoh HD Webcam                                         | 1         | 1.37%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.37%   |
| Realtek USB Camera                                      | 1         | 1.37%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 1.37%   |
| Realtek HP Wide Vision FHD Camera                       | 1         | 1.37%   |
| Realtek HP Truevision HD                                | 1         | 1.37%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 1.37%   |
| Realtek HD WebCam                                       | 1         | 1.37%   |
| Quanta hm1091_techfront                                 | 1         | 1.37%   |
| Quanta HD User Facing                                   | 1         | 1.37%   |
| Microdia Webcam Vitade AF                               | 1         | 1.37%   |
| Microdia Laptop_Integrated_Webcam_2M                    | 1         | 1.37%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 1.37%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 1.37%   |
| Microdia Dell Integrated HD Webcam                      | 1         | 1.37%   |
| Logitech HD Pro Webcam C920                             | 1         | 1.37%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 1.37%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.37%   |
| IMC Networks XiaoMi Webcam                              | 1         | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 1         | 1.37%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 1.37%   |
| IMC Networks Lenovo EasyCamera                          | 1         | 1.37%   |
| IMC Networks EasyCamera                                 | 1         | 1.37%   |
| Cubeternet USB2.0 Camera                                | 1         | 1.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 64.29%  |
| Synaptics             | 2         | 14.29%  |
| Elan Microelectronics | 2         | 14.29%  |
| Upek                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader             | 4         | 28.57%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 14.29%  |
| Elan ELAN:Fingerprint                                  | 2         | 14.29%  |
| Validity Sensors VFS491                                | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.14%   |

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
| 0     | 44        | 57.89%  |
| 1     | 27        | 35.53%  |
| 2     | 5         | 6.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 37.84%  |
| Net/wireless          | 7         | 18.92%  |
| Chipcard              | 6         | 16.22%  |
| Graphics card         | 4         | 10.81%  |
| Multimedia controller | 3         | 8.11%   |
| Storage               | 2         | 5.41%   |
| Camera                | 1         | 2.7%    |

