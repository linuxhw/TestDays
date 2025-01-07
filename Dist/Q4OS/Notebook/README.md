Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

Total: 92

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AOD257                      | [cd57ba84bc](https://linux-hardware.org/?probe=cd57ba84bc) | Jan 03, 2025 |
| Apple         | MacBookAir5,1               | [3e859a02ef](https://linux-hardware.org/?probe=3e859a02ef) | Dec 26, 2024 |
| HP            | Stream Notebook PC 11       | [104ee26be6](https://linux-hardware.org/?probe=104ee26be6) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [341dc448fb](https://linux-hardware.org/?probe=341dc448fb) | Dec 25, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [bbc531ab55](https://linux-hardware.org/?probe=bbc531ab55) | Nov 29, 2024 |
| Toshiba       | Satellite M100              | [5e91fe5751](https://linux-hardware.org/?probe=5e91fe5751) | Nov 11, 2024 |
| Acer          | AOD270                      | [59b2793787](https://linux-hardware.org/?probe=59b2793787) | Nov 10, 2024 |
| Unknown       | E142                        | [e652a7e6d8](https://linux-hardware.org/?probe=e652a7e6d8) | Oct 31, 2024 |
| Dell          | Latitude E5540              | [a59dfdcd62](https://linux-hardware.org/?probe=a59dfdcd62) | Oct 03, 2024 |
| Dell          | Latitude E5540              | [44955d2b3b](https://linux-hardware.org/?probe=44955d2b3b) | Oct 03, 2024 |
| MicroByte     | ezbook                      | [79104622de](https://linux-hardware.org/?probe=79104622de) | Sep 24, 2024 |
| Lenovo        | ThinkPad X201 3249MJJ       | [04987f2d0e](https://linux-hardware.org/?probe=04987f2d0e) | Sep 23, 2024 |
| Toshiba       | Satellite L515              | [aa75424421](https://linux-hardware.org/?probe=aa75424421) | Sep 19, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8c7a3cb9ec](https://linux-hardware.org/?probe=8c7a3cb9ec) | Sep 16, 2024 |
| Acer          | Aspire 5920G                | [611ba26507](https://linux-hardware.org/?probe=611ba26507) | Sep 04, 2024 |
| Acer          | Aspire E1-470G              | [fd457f673c](https://linux-hardware.org/?probe=fd457f673c) | Aug 25, 2024 |
| HP            | 2000                        | [28e8a84a4a](https://linux-hardware.org/?probe=28e8a84a4a) | Aug 18, 2024 |
| HP            | Notebook                    | [a1f1e83afe](https://linux-hardware.org/?probe=a1f1e83afe) | Jul 23, 2024 |
| HP            | Notebook                    | [1df59c0265](https://linux-hardware.org/?probe=1df59c0265) | Jul 23, 2024 |
| Toshiba       | NB100                       | [3ca4d2b945](https://linux-hardware.org/?probe=3ca4d2b945) | Jun 16, 2024 |
| Apple         | MacBookAir6,2               | [396846baeb](https://linux-hardware.org/?probe=396846baeb) | May 31, 2024 |
| GFAST         | N-140                       | [43195fd09f](https://linux-hardware.org/?probe=43195fd09f) | May 16, 2024 |
| Acer          | Aspire V5-121               | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Samsung       | N150P/N210P/N220P           | [d6fca9f7f5](https://linux-hardware.org/?probe=d6fca9f7f5) | Apr 13, 2024 |
| HP            | ProBook 650 G1              | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| Panasonic     | CF-S10CWHDS                 | [a4c273ab7b](https://linux-hardware.org/?probe=a4c273ab7b) | Mar 19, 2024 |
| MSI           | Alpha 17 C7VF               | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Dell          | Latitude D530               | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c246a6b564](https://linux-hardware.org/?probe=c246a6b564) | Jan 30, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Matsushita... | CF-29LAQGZBM                | [433fd9b78e](https://linux-hardware.org/?probe=433fd9b78e) | Jan 11, 2024 |
| Toshiba       | Satellite L515              | [a7ec902190](https://linux-hardware.org/?probe=a7ec902190) | Jan 10, 2024 |
| Irbis         | NB264                       | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| Dell          | Latitude E6430              | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| ASUSTek       | K53SJ                       | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| IBM           | ThinkPad T42 2378FVU        | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Google        | Cave                        | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| Medion        | P6620                       | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                      | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b               | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                        | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                         | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 5 | 29        | 40.28%  |
| Q4OS 4 | 29        | 40.28%  |
| Q4OS 3 | 11        | 15.28%  |
| Q4OS 2 | 3         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 72        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-23-amd64       | 5         | 6.76%   |
| 6.1.0-18-amd64       | 4         | 5.41%   |
| 5.10.0-23-amd64      | 4         | 5.41%   |
| 6.1.0-27-amd64       | 3         | 4.05%   |
| 6.1.0-25-amd64       | 3         | 4.05%   |
| 5.10.0-21-amd64      | 3         | 4.05%   |
| 5.10.0-12-amd64      | 3         | 4.05%   |
| 4.19.0-17-amd64      | 3         | 4.05%   |
| 6.1.0-21-amd64       | 2         | 2.7%    |
| 6.1.0-17-686-pae     | 2         | 2.7%    |
| 6.1.0-13-amd64       | 2         | 2.7%    |
| 5.10.0-8-amd64       | 2         | 2.7%    |
| 5.10.0-14-686-pae    | 2         | 2.7%    |
| 6.6.8-x64v1-xanmod1  | 1         | 1.35%   |
| 6.5.0-4-amd64        | 1         | 1.35%   |
| 6.1.0-26-amd64       | 1         | 1.35%   |
| 6.1.0-26-686-pae     | 1         | 1.35%   |
| 6.1.0-17-amd64       | 1         | 1.35%   |
| 6.1.0-16-686-pae     | 1         | 1.35%   |
| 6.1.0-12-amd64       | 1         | 1.35%   |
| 6.1.0-12-686-pae     | 1         | 1.35%   |
| 6.1.0-11-686-pae     | 1         | 1.35%   |
| 6.1.0-10-686-pae     | 1         | 1.35%   |
| 5.9.0-5-amd64        | 1         | 1.35%   |
| 5.6.0-1-amd64        | 1         | 1.35%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.35%   |
| 5.10.0-9-amd64       | 1         | 1.35%   |
| 5.10.0-8-686-pae     | 1         | 1.35%   |
| 5.10.0-29-686-pae    | 1         | 1.35%   |
| 5.10.0-21-686-pae    | 1         | 1.35%   |
| 5.10.0-20-686        | 1         | 1.35%   |
| 5.10.0-17-amd64      | 1         | 1.35%   |
| 5.10.0-15-amd64      | 1         | 1.35%   |
| 5.10.0-15-686-pae    | 1         | 1.35%   |
| 5.10.0-13-amd64      | 1         | 1.35%   |
| 5.10.0-12-686-pae    | 1         | 1.35%   |
| 5.10.0-11-686-pae    | 1         | 1.35%   |
| 5.10.0-10-686-pae    | 1         | 1.35%   |
| 4.9.0-8-amd64        | 1         | 1.35%   |
| 4.9.0-14-686-pae     | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 27        | 37.5%   |
| 5.10.0  | 26        | 36.11%  |
| 4.19.0  | 11        | 15.28%  |
| 4.9.0   | 3         | 4.17%   |
| 6.6.8   | 1         | 1.39%   |
| 6.5.0   | 1         | 1.39%   |
| 5.9.0   | 1         | 1.39%   |
| 5.6.0   | 1         | 1.39%   |
| 5.18.0  | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 27        | 37.5%   |
| 5.10    | 26        | 36.11%  |
| 4.19    | 11        | 15.28%  |
| 4.9     | 3         | 4.17%   |
| 6.6     | 1         | 1.39%   |
| 6.5     | 1         | 1.39%   |
| 5.9     | 1         | 1.39%   |
| 5.6     | 1         | 1.39%   |
| 5.18    | 1         | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 72.22%  |
| i686   | 20        | 27.78%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Trinity  | 39        | 54.17%  |
| KDE5     | 30        | 41.67%  |
| MATE     | 1         | 1.39%   |
| KDE      | 1         | 1.39%   |
| Cinnamon | 1         | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 70        | 97.22%  |
| Wayland | 1         | 1.39%   |
| Tty     | 1         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| TDM  | 40        | 55.56%  |
| SDDM | 32        | 44.44%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 36        | 50%     |
| en_GB   | 6         | 8.33%   |
| fr_FR   | 4         | 5.56%   |
| de_DE   | 4         | 5.56%   |
| ru_RU   | 3         | 4.17%   |
| it_IT   | 3         | 4.17%   |
| hu_HU   | 3         | 4.17%   |
| es_ES   | 3         | 4.17%   |
| sv_SE   | 1         | 1.39%   |
| sl_SI   | 1         | 1.39%   |
| pl_PL   | 1         | 1.39%   |
| ja_JP   | 1         | 1.39%   |
| hr_HR   | 1         | 1.39%   |
| es_VE   | 1         | 1.39%   |
| en_SG   | 1         | 1.39%   |
| de_CH   | 1         | 1.39%   |
| C       | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 59.72%  |
| EFI  | 29        | 40.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 70        | 97.22%  |
| Overlay | 2         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 43        | 59.72%  |
| GPT     | 28        | 38.89%  |
| Unknown | 1         | 1.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 90.28%  |
| Yes       | 7         | 9.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 75%     |
| Yes       | 18        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 13        | 18.06%  |
| Lenovo                         | 7         | 9.72%   |
| ASUSTek Computer               | 7         | 9.72%   |
| Acer                           | 7         | 9.72%   |
| Toshiba                        | 6         | 8.33%   |
| Dell                           | 4         | 5.56%   |
| MSI                            | 3         | 4.17%   |
| Apple                          | 3         | 4.17%   |
| Sony                           | 2         | 2.78%   |
| Medion                         | 2         | 2.78%   |
| IBM                            | 2         | 2.78%   |
| Google                         | 2         | 2.78%   |
| Visual Land                    | 1         | 1.39%   |
| Qilive                         | 1         | 1.39%   |
| Phoenix/SiS                    | 1         | 1.39%   |
| Philco                         | 1         | 1.39%   |
| Panasonic                      | 1         | 1.39%   |
| Packard Bell                   | 1         | 1.39%   |
| Matsushita Electric Industrial | 1         | 1.39%   |
| JVC                            | 1         | 1.39%   |
| Irbis                          | 1         | 1.39%   |
| Fujitsu Siemens                | 1         | 1.39%   |
| Framework                      | 1         | 1.39%   |
| Chuwi                          | 1         | 1.39%   |
| AMI                            | 1         | 1.39%   |
| Unknown                        | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite C660                      | 2         | 2.78%   |
| HP ProBook 650 G1                           | 2         | 2.78%   |
| HP 2000                                     | 2         | 2.78%   |
| Unknown                                     | 2         | 2.78%   |
| Visual Land Premier 10                      | 1         | 1.39%   |
| Toshiba Satellite Pro L500                  | 1         | 1.39%   |
| Toshiba Satellite M70                       | 1         | 1.39%   |
| Toshiba Satellite L515                      | 1         | 1.39%   |
| Toshiba NB100                               | 1         | 1.39%   |
| Sony VGN-P11Z_Q                             | 1         | 1.39%   |
| Sony VGN-FW21Z                              | 1         | 1.39%   |
| Qilive QW19141AMSP                          | 1         | 1.39%   |
| Phoenix/SiS M720SR                          | 1         | 1.39%   |
| Philco 14I                                  | 1         | 1.39%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.39%   |
| Packard Bell EasyNote LM81                  | 1         | 1.39%   |
| MSI U90/U100                                | 1         | 1.39%   |
| MSI U210                                    | 1         | 1.39%   |
| MSI Alpha 17 C7VF                           | 1         | 1.39%   |
| Medion P6620                                | 1         | 1.39%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.39%   |
| Lenovo ThinkPad X201 3249MJJ                | 1         | 1.39%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 1.39%   |
| Lenovo ThinkPad 11e 20DAS0PS00              | 1         | 1.39%   |
| Lenovo IdeaPad S145-15AST 81N3              | 1         | 1.39%   |
| Lenovo IdeaPad 5 14IAL7 82SD                | 1         | 1.39%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 1.39%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 1.39%   |
| JVC J3N                                     | 1         | 1.39%   |
| Irbis NB264                                 | 1         | 1.39%   |
| IBM ThinkPad T43 1875DMU                    | 1         | 1.39%   |
| IBM ThinkPad T42 2378FVU                    | 1         | 1.39%   |
| HP Stream Notebook PC 11                    | 1         | 1.39%   |
| HP ProBook 6550b                            | 1         | 1.39%   |
| HP ProBook 450 G2                           | 1         | 1.39%   |
| HP Presario CQ56                            | 1         | 1.39%   |
| HP Pavilion dv1000 (EW489EA#ABZ)            | 1         | 1.39%   |
| HP OmniBook PC                              | 1         | 1.39%   |
| HP Notebook                                 | 1         | 1.39%   |
| HP Laptop 15s-fq2xxx                        | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite                           | 5         | 6.94%   |
| Acer Aspire                                 | 5         | 6.94%   |
| Lenovo IdeaPad                              | 4         | 5.56%   |
| HP ProBook                                  | 4         | 5.56%   |
| Dell Latitude                               | 4         | 5.56%   |
| Lenovo ThinkPad                             | 3         | 4.17%   |
| IBM ThinkPad                                | 2         | 2.78%   |
| HP 2000                                     | 2         | 2.78%   |
| ASUS VivoBook                               | 2         | 2.78%   |
| Unknown                                     | 2         | 2.78%   |
| Visual Land Premier                         | 1         | 1.39%   |
| Toshiba NB100                               | 1         | 1.39%   |
| Sony VGN-P11Z                               | 1         | 1.39%   |
| Sony VGN-FW21Z                              | 1         | 1.39%   |
| Qilive QW19141AMSP                          | 1         | 1.39%   |
| Phoenix/SiS M720SR                          | 1         | 1.39%   |
| Philco 14I                                  | 1         | 1.39%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.39%   |
| Packard Bell EasyNote                       | 1         | 1.39%   |
| MSI U90                                     | 1         | 1.39%   |
| MSI U210                                    | 1         | 1.39%   |
| MSI Alpha                                   | 1         | 1.39%   |
| Medion P6620                                | 1         | 1.39%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.39%   |
| JVC J3N                                     | 1         | 1.39%   |
| Irbis NB264                                 | 1         | 1.39%   |
| HP Stream                                   | 1         | 1.39%   |
| HP Presario                                 | 1         | 1.39%   |
| HP Pavilion                                 | 1         | 1.39%   |
| HP OmniBook                                 | 1         | 1.39%   |
| HP Notebook                                 | 1         | 1.39%   |
| HP Laptop                                   | 1         | 1.39%   |
| HP 250                                      | 1         | 1.39%   |
| Google Reks                                 | 1         | 1.39%   |
| Google Cave                                 | 1         | 1.39%   |
| Fujitsu Siemens AMILO                       | 1         | 1.39%   |
| Framework Laptop                            | 1         | 1.39%   |
| Chuwi GemiBook                              | 1         | 1.39%   |
| ASUS X540YA                                 | 1         | 1.39%   |
| ASUS T12Eg                                  | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 7         | 9.72%   |
| 2020    | 6         | 8.33%   |
| 2010    | 6         | 8.33%   |
| 2013    | 5         | 6.94%   |
| 2012    | 5         | 6.94%   |
| 2008    | 5         | 6.94%   |
| 2007    | 4         | 5.56%   |
| 2005    | 4         | 5.56%   |
| 2023    | 3         | 4.17%   |
| 2019    | 3         | 4.17%   |
| 2018    | 3         | 4.17%   |
| 2014    | 3         | 4.17%   |
| 2011    | 3         | 4.17%   |
| 2022    | 2         | 2.78%   |
| 2016    | 2         | 2.78%   |
| 2006    | 2         | 2.78%   |
| 2004    | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |
| 2024    | 1         | 1.39%   |
| 2021    | 1         | 1.39%   |
| 2017    | 1         | 1.39%   |
| 2015    | 1         | 1.39%   |
| 2003    | 1         | 1.39%   |

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
| Disabled | 67        | 93.06%  |
| Enabled  | 5         | 6.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 97.22%  |
| Yes  | 2         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 28        | 38.89%  |
| 4.01-8.0   | 11        | 15.28%  |
| 2.01-3.0   | 9         | 12.5%   |
| 1.01-2.0   | 8         | 11.11%  |
| 0.51-1.0   | 5         | 6.94%   |
| 8.01-16.0  | 4         | 5.56%   |
| 0.01-0.5   | 4         | 5.56%   |
| 16.01-24.0 | 2         | 2.78%   |
| 24.01-32.0 | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 35        | 47.95%  |
| 0.51-1.0 | 15        | 20.55%  |
| 2.01-3.0 | 12        | 16.44%  |
| 0.01-0.5 | 7         | 9.59%   |
| 4.01-8.0 | 2         | 2.74%   |
| 3.01-4.0 | 2         | 2.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 81.94%  |
| 2      | 11        | 15.28%  |
| 3      | 2         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 50%     |
| No        | 36        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 76.39%  |
| No        | 17        | 23.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 95.83%  |
| No        | 3         | 4.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 52.78%  |
| Yes       | 34        | 47.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 18        | 25%     |
| UK           | 6         | 8.33%   |
| Italy        | 4         | 5.56%   |
| Germany      | 4         | 5.56%   |
| Spain        | 3         | 4.17%   |
| Russia       | 3         | 4.17%   |
| Kenya        | 3         | 4.17%   |
| Hungary      | 3         | 4.17%   |
| France       | 3         | 4.17%   |
| Switzerland  | 2         | 2.78%   |
| Slovenia     | 2         | 2.78%   |
| Romania      | 2         | 2.78%   |
| Poland       | 2         | 2.78%   |
| Croatia      | 2         | 2.78%   |
| Venezuela    | 1         | 1.39%   |
| Turkey       | 1         | 1.39%   |
| Sweden       | 1         | 1.39%   |
| Singapore    | 1         | 1.39%   |
| Saudi Arabia | 1         | 1.39%   |
| Qatar        | 1         | 1.39%   |
| Mexico       | 1         | 1.39%   |
| Japan        | 1         | 1.39%   |
| Egypt        | 1         | 1.39%   |
| Canada       | 1         | 1.39%   |
| Brazil       | 1         | 1.39%   |
| Belgium      | 1         | 1.39%   |
| Belarus      | 1         | 1.39%   |
| Argentina    | 1         | 1.39%   |
| Algeria      | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Jacksonville          | 10        | 13.89%  |
| Nairobi               | 3         | 4.17%   |
| Swindon               | 2         | 2.78%   |
| Mesa                  | 2         | 2.78%   |
| Ljubljana             | 2         | 2.78%   |
| Drobeta-Turnu Severin | 2         | 2.78%   |
| Budapest              | 2         | 2.78%   |
| Zweidlen-Dorf         | 1         | 1.39%   |
| Zagreb                | 1         | 1.39%   |
| West Corinth          | 1         | 1.39%   |
| Volgograd             | 1         | 1.39%   |
| Tokyo                 | 1         | 1.39%   |
| Tenbury Wells         | 1         | 1.39%   |
| Tellico Plains        | 1         | 1.39%   |
| Sosnowiec             | 1         | 1.39%   |
| Sint-Pieters-Leeuw    | 1         | 1.39%   |
| Singapore             | 1         | 1.39%   |
| Sétif                | 1         | 1.39%   |
| Schermbeck            | 1         | 1.39%   |
| Salsomaggiore Terme   | 1         | 1.39%   |
| Rostov-on-Don         | 1         | 1.39%   |
| Rostock               | 1         | 1.39%   |
| Rijeka                | 1         | 1.39%   |
| Puerto Cumarebo       | 1         | 1.39%   |
| Nasr                  | 1         | 1.39%   |
| Moscow                | 1         | 1.39%   |
| Morelia               | 1         | 1.39%   |
| Mooresville           | 1         | 1.39%   |
| Moirans               | 1         | 1.39%   |
| Mogilev               | 1         | 1.39%   |
| Milano                | 1         | 1.39%   |
| Mar del Plata         | 1         | 1.39%   |
| Mannheim              | 1         | 1.39%   |
| Londrina              | 1         | 1.39%   |
| Little Current        | 1         | 1.39%   |
| Leipzig               | 1         | 1.39%   |
| Lausanne              | 1         | 1.39%   |
| Las Vegas             | 1         | 1.39%   |
| Klaudyn               | 1         | 1.39%   |
| Jönköping           | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 11        | 11     | 13.92%  |
| WDC                 | 10        | 10     | 12.66%  |
| Seagate             | 8         | 9      | 10.13%  |
| Samsung Electronics | 8         | 9      | 10.13%  |
| Toshiba             | 6         | 6      | 7.59%   |
| Hitachi             | 6         | 7      | 7.59%   |
| Kingston            | 5         | 5      | 6.33%   |
| SanDisk             | 3         | 3      | 3.8%    |
| HGST                | 3         | 3      | 3.8%    |
| Fujitsu             | 3         | 3      | 3.8%    |
| KESU                | 2         | 2      | 2.53%   |
| China               | 2         | 2      | 2.53%   |
| Apple               | 2         | 2      | 2.53%   |
| A-DATA Technology   | 2         | 2      | 2.53%   |
| SUNEAST             | 1         | 1      | 1.27%   |
| Silicon Motion      | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| Phison              | 1         | 1      | 1.27%   |
| KingSpec            | 1         | 1      | 1.27%   |
| KBG40ZNV            | 1         | 1      | 1.27%   |
| HEYGATE             | 1         | 1      | 1.27%   |
| Unknown             | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 2.53%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 2.53%   |
| Unknown S0J59X  128GB                | 2         | 2.53%   |
| Unknown G1J38E  64GB                 | 2         | 2.53%   |
| Samsung SSD 850 EVO 250GB            | 2         | 2.53%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 2.53%   |
| KESU USB 3.1 256GB                   | 2         | 2.53%   |
| A-DATA SU630 240GB SSD               | 2         | 2.53%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.27%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.27%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.27%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.27%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.27%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.27%   |
| Unknown USDU1  32GB                  | 1         | 1.27%   |
| Unknown SLD64G  64GB                 | 1         | 1.27%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.27%   |
| Unknown MMC Card  64GB               | 1         | 1.27%   |
| Unknown MBG4GC  32GB                 | 1         | 1.27%   |
| Unknown HAG2e  16GB                  | 1         | 1.27%   |
| Unknown 064G38  64GB                 | 1         | 1.27%   |
| Toshiba MK8032GAX 80GB               | 1         | 1.27%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.27%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.27%   |
| Toshiba MK3276GSX 320GB              | 1         | 1.27%   |
| Toshiba MK3252GSX 320GB              | 1         | 1.27%   |
| Toshiba MK1252GSX 120GB              | 1         | 1.27%   |
| SUNEAST SSD SE800 mSATA 256GB        | 1         | 1.27%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.27%   |
| Seagate ST96812AS 64GB               | 1         | 1.27%   |
| Seagate ST9500325AS 500GB            | 1         | 1.27%   |
| Seagate ST9120822AS 120GB            | 1         | 1.27%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.27%   |
| Seagate ST380012A 80GB               | 1         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.27%   |
| Seagate BUP RD 5TB                   | 1         | 1.27%   |
| Seagate Backup+ SL 2TB               | 1         | 1.27%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.27%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 1.27%   |
| SanDisk NVMe SSD Drive 250GB         | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 25%     |
| Seagate             | 7         | 8      | 19.44%  |
| Toshiba             | 6         | 6      | 16.67%  |
| Hitachi             | 6         | 7      | 16.67%  |
| HGST                | 3         | 3      | 8.33%   |
| Fujitsu             | 3         | 3      | 8.33%   |
| Unknown             | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 25%     |
| SanDisk             | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| China               | 2         | 2      | 10%     |
| Apple               | 2         | 2      | 10%     |
| A-DATA Technology   | 2         | 2      | 10%     |
| SUNEAST             | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| KingSpec            | 1         | 1      | 5%      |
| HEYGATE             | 1         | 1      | 5%      |
| Unknown             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 38     | 46.05%  |
| SSD     | 20        | 20     | 26.32%  |
| MMC     | 12        | 12     | 15.79%  |
| NVMe    | 6         | 9      | 7.89%   |
| Unknown | 3         | 3      | 3.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 56     | 68.83%  |
| MMC  | 12        | 12     | 15.58%  |
| SAS  | 6         | 6      | 7.79%   |
| NVMe | 6         | 8      | 7.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 52     | 90.74%  |
| 0.51-1.0   | 4         | 5      | 7.41%   |
| 4.01-10.0  | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 29.17%  |
| 51-100     | 18        | 25%     |
| 251-500    | 14        | 19.44%  |
| 21-50      | 6         | 8.33%   |
| 1-20       | 6         | 8.33%   |
| 501-1000   | 4         | 5.56%   |
| 1001-2000  | 2         | 2.78%   |
| Unknown    | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 52        | 70.27%  |
| 21-50    | 13        | 17.57%  |
| 51-100   | 4         | 5.41%   |
| 251-500  | 3         | 4.05%   |
| 501-1000 | 1         | 1.35%   |
| Unknown  | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB     | 1         | 1      | 5.88%   |
| WDC WD2500BEVT-60A23T0 250GB     | 1         | 1      | 5.88%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 5.88%   |
| Toshiba MK3252GSX 320GB          | 1         | 1      | 5.88%   |
| Toshiba MK1252GSX 120GB          | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 5.88%   |
| Seagate ST9120822AS 120GB        | 1         | 1      | 5.88%   |
| Samsung Electronics HM080GC 80GB | 1         | 1      | 5.88%   |
| PNY 1TB SATA SSD                 | 1         | 1      | 5.88%   |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9SA00 250GB    | 1         | 1      | 5.88%   |
| Hitachi DK23CA-20 20GB           | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB       | 1         | 1      | 5.88%   |
| HGST HTS545032A7E380 320GB       | 1         | 1      | 5.88%   |
| HGST HTS541075A9E680 752GB       | 1         | 1      | 5.88%   |
| Fujitsu MHZ2160BH G2 160GB       | 1         | 1      | 5.88%   |
| Fujitsu MHY2080BH 80GB           | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 17.65%  |
| Hitachi             | 3         | 3      | 17.65%  |
| HGST                | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Seagate             | 2         | 2      | 11.76%  |
| Fujitsu             | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |
| PNY                 | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 18.75%  |
| Hitachi             | 3         | 3      | 18.75%  |
| HGST                | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Seagate             | 2         | 2      | 12.5%   |
| Fujitsu             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 94.12%  |
| SSD  | 1         | 1      | 5.88%   |

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
| Works    | 41        | 48     | 55.41%  |
| Malfunc  | 17        | 17     | 22.97%  |
| Detected | 16        | 17     | 21.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 50        | 71.43%  |
| AMD                              | 9         | 12.86%  |
| Silicon Integrated Systems [SiS] | 3         | 4.29%   |
| Samsung Electronics              | 3         | 4.29%   |
| SanDisk                          | 2         | 2.86%   |
| Silicon Motion                   | 1         | 1.43%   |
| Phison Electronics               | 1         | 1.43%   |
| Marvell Technology Group         | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 7.41%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 7.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 6.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 6.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 4.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 4.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.94%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 3.7%    |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 3.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.47%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.47%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.23%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.23%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.23%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 1.23%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.23%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.23%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.23%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.23%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 46        | 59.74%  |
| IDE  | 22        | 28.57%  |
| NVMe | 6         | 7.79%   |
| RAID | 3         | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 81.94%  |
| AMD    | 13        | 18.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 4.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 4.17%   |
| Intel Atom CPU N270 @ 1.60GHz               | 3         | 4.17%   |
| Intel Pentium M processor 1.70GHz           | 2         | 2.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.78%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 2.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 2.78%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 2.78%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 2.78%   |
| AMD E-300 APU with Radeon HD Graphics       | 2         | 2.78%   |
| AMD C-70 APU with Radeon HD Graphics        | 2         | 2.78%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.39%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.39%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.39%   |
| Intel Pentium III (Coppermine)              | 1         | 1.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.39%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.39%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.39%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.39%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 1.39%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.39%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.39%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.39%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.39%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.39%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.39%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.39%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.39%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 1         | 1.39%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.39%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.39%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.39%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 12        | 16.67%  |
| Intel Core i5           | 9         | 12.5%   |
| Intel Core 2 Duo        | 9         | 12.5%   |
| Intel Atom              | 8         | 11.11%  |
| Intel Pentium M         | 5         | 6.94%   |
| Intel Core i3           | 5         | 6.94%   |
| Other                   | 2         | 2.78%   |
| Intel Pentium Dual-Core | 2         | 2.78%   |
| Intel Genuine           | 2         | 2.78%   |
| AMD E                   | 2         | 2.78%   |
| AMD C-70                | 2         | 2.78%   |
| Intel Pentium III       | 1         | 1.39%   |
| Intel Pentium 4         | 1         | 1.39%   |
| Intel Pentium           | 1         | 1.39%   |
| Intel Core m3           | 1         | 1.39%   |
| Intel Core 2            | 1         | 1.39%   |
| AMD V120                | 1         | 1.39%   |
| AMD Ryzen 9             | 1         | 1.39%   |
| AMD Ryzen 7 PRO         | 1         | 1.39%   |
| AMD Ryzen 7             | 1         | 1.39%   |
| AMD Mobile Sempron      | 1         | 1.39%   |
| AMD Athlon Neo          | 1         | 1.39%   |
| AMD A8                  | 1         | 1.39%   |
| AMD A6                  | 1         | 1.39%   |
| AMD A4                  | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 63.89%  |
| 1      | 15        | 20.83%  |
| 4      | 8         | 11.11%  |
| 16     | 1         | 1.39%   |
| 12     | 1         | 1.39%   |
| 8      | 1         | 1.39%   |

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
| 1      | 46        | 63.89%  |
| 2      | 26        | 36.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 79.17%  |
| 32-bit         | 15        | 20.83%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 10.96%  |
| 0x6fd      | 4         | 5.48%   |
| 0x206a7    | 4         | 5.48%   |
| 0x106c2    | 4         | 5.48%   |
| 0x1067a    | 4         | 5.48%   |
| 0x706a8    | 3         | 4.11%   |
| 0x406c4    | 3         | 4.11%   |
| 0x40651    | 3         | 4.11%   |
| 0x306a9    | 3         | 4.11%   |
| 0x30678    | 3         | 4.11%   |
| 0x05000119 | 3         | 4.11%   |
| 0x706a1    | 2         | 2.74%   |
| 0x6e8      | 2         | 2.74%   |
| 0x306c3    | 2         | 2.74%   |
| 0x20655    | 2         | 2.74%   |
| 0x10676    | 2         | 2.74%   |
| 0x06006705 | 2         | 2.74%   |
| 0xf27      | 1         | 1.37%   |
| 0x906a3    | 1         | 1.37%   |
| 0x806e9    | 1         | 1.37%   |
| 0x806c1    | 1         | 1.37%   |
| 0x6fb      | 1         | 1.37%   |
| 0x6f6      | 1         | 1.37%   |
| 0x6d8      | 1         | 1.37%   |
| 0x6d6      | 1         | 1.37%   |
| 0x695      | 1         | 1.37%   |
| 0x68a      | 1         | 1.37%   |
| 0x506c9    | 1         | 1.37%   |
| 0x406e3    | 1         | 1.37%   |
| 0x30661    | 1         | 1.37%   |
| 0x0a704103 | 1         | 1.37%   |
| 0x0a601203 | 1         | 1.37%   |
| 0x08108102 | 1         | 1.37%   |
| 0x07030106 | 1         | 1.37%   |
| 0x0500010d | 1         | 1.37%   |
| 0x010000c8 | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| P6            | 8         | 11.11%  |
| Silvermont    | 7         | 9.72%   |
| Penryn        | 6         | 8.33%   |
| Goldmont plus | 6         | 8.33%   |
| Core          | 6         | 8.33%   |
| Bonnell       | 6         | 8.33%   |
| Haswell       | 5         | 6.94%   |
| SandyBridge   | 4         | 5.56%   |
| Bobcat        | 4         | 5.56%   |
| IvyBridge     | 3         | 4.17%   |
| Unknown       | 3         | 4.17%   |
| Westmere      | 2         | 2.78%   |
| K8 Hammer     | 2         | 2.78%   |
| Excavator     | 2         | 2.78%   |
| Zen+          | 1         | 1.39%   |
| TigerLake     | 1         | 1.39%   |
| Skylake       | 1         | 1.39%   |
| Puma          | 1         | 1.39%   |
| NetBurst      | 1         | 1.39%   |
| KabyLake      | 1         | 1.39%   |
| K10           | 1         | 1.39%   |
| Goldmont      | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 65.33%  |
| AMD                              | 18        | 24%     |
| Nvidia                           | 4         | 5.33%   |
| Silicon Integrated Systems [SiS] | 3         | 4%      |
| S3 Graphics                      | 1         | 1.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 6         | 7.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 5         | 5.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 4         | 4.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 4         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 4         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 4         | 4.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 3         | 3.57%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 3         | 3.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 3         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 3         | 3.57%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 2.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 2         | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 2         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 2         | 2.38%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 2         | 2.38%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 2         | 2.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 2         | 2.38%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.19%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 1.19%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.19%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.19%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.19%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.19%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.19%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                            | 1         | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.19%   |
| Intel HD Graphics 610                                                                      | 1         | 1.19%   |
| Intel HD Graphics 515                                                                      | 1         | 1.19%   |
| Intel HD Graphics 500                                                                      | 1         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                        | 1         | 1.19%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 1         | 1.19%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 1         | 1.19%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.19%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.19%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.19%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 1.19%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 1.19%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                               | 1         | 1.19%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 38        | 52.78%  |
| 1 x AMD         | 16        | 22.22%  |
| 2 x Intel       | 8         | 11.11%  |
| 1 x SiS         | 3         | 4.17%   |
| 1 x Nvidia      | 2         | 2.78%   |
| Other           | 1         | 1.39%   |
| 1 x S3 Graphics | 1         | 1.39%   |
| Intel + Nvidia  | 1         | 1.39%   |
| Intel + AMD     | 1         | 1.39%   |
| AMD + Nvidia    | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 88.89%  |
| Unknown     | 5         | 6.94%   |
| Proprietary | 3         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 72.6%   |
| 0.01-0.5   | 18        | 24.66%  |
| 1.01-2.0   | 2         | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 23.81%  |
| Samsung Electronics     | 9         | 14.29%  |
| Chimei Innolux          | 9         | 14.29%  |
| LG Display              | 7         | 11.11%  |
| BOE                     | 6         | 9.52%   |
| Apple                   | 3         | 4.76%   |
| HannStar                | 2         | 3.17%   |
| Dell                    | 2         | 3.17%   |
| CPT                     | 2         | 3.17%   |
| Chi Mei Optoelectronics | 2         | 3.17%   |
| MQP                     | 1         | 1.59%   |
| LG Philips              | 1         | 1.59%   |
| Lenovo                  | 1         | 1.59%   |
| InfoVision              | 1         | 1.59%   |
| Hewlett-Packard         | 1         | 1.59%   |
| CSO                     | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 3.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 2         | 3.17%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 340x190mm 15.3-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch   | 1         | 1.59%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 1.59%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD03DD 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD01E6 1366x768 309x174mm 14.0-inch              | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.59%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 1.59%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 1.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 1.59%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 1.59%   |
| Dell UP2715K DEL40B6 2560x1440 600x340mm 27.2-inch                       | 1         | 1.59%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 1.59%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 380x210mm 17.1-inch                    | 1         | 1.59%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 1.59%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 1.59%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 1.59%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE08B2 1366x768 309x174mm 14.0-inch                     | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 27        | 43.55%  |
| 1920x1080 (FHD)   | 12        | 19.35%  |
| 1280x800 (WXGA)   | 8         | 12.9%   |
| 1024x600          | 4         | 6.45%   |
| 1600x900 (HD+)    | 3         | 4.84%   |
| 1920x1200 (WUXGA) | 2         | 3.23%   |
| 800x600           | 1         | 1.61%   |
| 2560x1440 (QHD)   | 1         | 1.61%   |
| 2256x1504         | 1         | 1.61%   |
| 2160x1440         | 1         | 1.61%   |
| 1440x900 (WXGA+)  | 1         | 1.61%   |
| 1024x768 (XGA)    | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 24        | 38.1%   |
| 13     | 9         | 14.29%  |
| 11     | 8         | 12.7%   |
| 14     | 6         | 9.52%   |
| 12     | 4         | 6.35%   |
| 10     | 3         | 4.76%   |
| 17     | 2         | 3.17%   |
| 46     | 1         | 1.59%   |
| 40     | 1         | 1.59%   |
| 27     | 1         | 1.59%   |
| 24     | 1         | 1.59%   |
| 23     | 1         | 1.59%   |
| 18     | 1         | 1.59%   |
| 8      | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 54.84%  |
| 201-300     | 18        | 29.03%  |
| 351-400     | 4         | 6.45%   |
| 501-600     | 3         | 4.84%   |
| 801-900     | 1         | 1.61%   |
| 101-200     | 1         | 1.61%   |
| 1001-1500   | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 46        | 76.67%  |
| 16/10 | 9         | 15%     |
| 3/2   | 3         | 5%      |
| 4/3   | 2         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 38.1%   |
| 81-90          | 15        | 23.81%  |
| 51-60          | 8         | 12.7%   |
| 61-70          | 3         | 4.76%   |
| 41-50          | 3         | 4.76%   |
| 121-130        | 2         | 3.17%   |
| 501-1000       | 2         | 3.17%   |
| 71-80          | 1         | 1.59%   |
| 1-40           | 1         | 1.59%   |
| 301-350        | 1         | 1.59%   |
| 251-300        | 1         | 1.59%   |
| 201-250        | 1         | 1.59%   |
| 141-150        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 44.44%  |
| 121-160 | 16        | 25.4%   |
| 51-100  | 12        | 19.05%  |
| 161-240 | 5         | 7.94%   |
| 1-50    | 2         | 3.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 88.89%  |
| 2     | 4         | 5.56%   |
| 0     | 4         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 39        | 33.62%  |
| Intel                            | 25        | 21.55%  |
| Qualcomm Atheros                 | 19        | 16.38%  |
| Broadcom                         | 11        | 9.48%   |
| Marvell Technology Group         | 5         | 4.31%   |
| Broadcom Limited                 | 4         | 3.45%   |
| Silicon Integrated Systems [SiS] | 3         | 2.59%   |
| Ralink Technology                | 2         | 1.72%   |
| Xiaomi                           | 1         | 0.86%   |
| Qualcomm Technologies            | 1         | 0.86%   |
| Motorola PCS                     | 1         | 0.86%   |
| MediaTek                         | 1         | 0.86%   |
| LG Electronics                   | 1         | 0.86%   |
| JMicron Technology               | 1         | 0.86%   |
| D-Link System                    | 1         | 0.86%   |
| Accton Technology                | 1         | 0.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 11.19%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 9         | 6.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 3.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 3.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.99%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.24%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 2.24%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.49%   |
| Intel Wireless 7265                                                     | 2         | 1.49%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.49%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.49%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.75%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.75%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.75%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.75%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1         | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.75%   |
| Motorola PCS moto g84 5G                                                | 1         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 30.99%  |
| Qualcomm Atheros      | 18        | 25.35%  |
| Realtek Semiconductor | 16        | 22.54%  |
| Broadcom              | 7         | 9.86%   |
| Broadcom Limited      | 3         | 4.23%   |
| Ralink Technology     | 2         | 2.82%   |
| Qualcomm Technologies | 1         | 1.41%   |
| MediaTek              | 1         | 1.41%   |
| D-Link System         | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 7.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 5         | 7.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 5         | 7.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 5.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 5.63%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 4         | 5.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 3         | 4.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 2         | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 2         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 2.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 2.82%   |
| Intel Wireless 7265                                                         | 2         | 2.82%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 2.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 2         | 2.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 2.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.41%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 1.41%   |
| Realtek RTL8187B Wireless Adapter                                           | 1         | 1.41%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.41%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                           | 1         | 1.41%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]            | 1         | 1.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter               | 1         | 1.41%   |
| Intel Wireless 7260                                                         | 1         | 1.41%   |
| Intel Wireless 3165                                                         | 1         | 1.41%   |
| Intel WiFi Link 5100                                                        | 1         | 1.41%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.41%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.41%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                        | 1         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.41%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 1.41%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter        | 1         | 1.41%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.41%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 1.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.41%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.41%   |
| Broadcom BCM4311 802.11b/g WLAN                                             | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 29        | 51.79%  |
| Intel                            | 9         | 16.07%  |
| Marvell Technology Group         | 5         | 8.93%   |
| Broadcom                         | 4         | 7.14%   |
| Silicon Integrated Systems [SiS] | 2         | 3.57%   |
| Xiaomi                           | 1         | 1.79%   |
| Qualcomm Atheros                 | 1         | 1.79%   |
| Motorola PCS                     | 1         | 1.79%   |
| LG Electronics                   | 1         | 1.79%   |
| JMicron Technology               | 1         | 1.79%   |
| Broadcom Limited                 | 1         | 1.79%   |
| Accton Technology                | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 26.79%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 16.07%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 5.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 3.57%   |
| Intel Ethernet Connection I217-V                                       | 2         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.79%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 1.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.79%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 1.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.79%   |
| Motorola PCS moto g84 5G                                               | 1         | 1.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.79%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 1.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.79%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                    | 1         | 1.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.79%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.79%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.79%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 1         | 1.79%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.79%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 1.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 1.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.79%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 1.79%   |
| Accton EN-1216 Ethernet Adapter                                        | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 52.67%  |
| Ethernet | 55        | 41.98%  |
| Modem    | 7         | 5.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 76.39%  |
| Ethernet | 17        | 23.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 65.28%  |
| 1     | 21        | 29.17%  |
| 0     | 3         | 4.17%   |
| 3     | 1         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 70.83%  |
| Yes  | 21        | 29.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 7         | 20%     |
| Qualcomm Atheros Communications | 7         | 20%     |
| Intel                           | 6         | 17.14%  |
| Apple                           | 3         | 8.57%   |
| IMC Networks                    | 2         | 5.71%   |
| Alps Electric                   | 2         | 5.71%   |
| Toshiba                         | 1         | 2.86%   |
| MediaTek                        | 1         | 2.86%   |
| Lite-On Technology              | 1         | 2.86%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Dell                            | 1         | 2.86%   |
| Broadcom                        | 1         | 2.86%   |
| ASUSTek Computer                | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 7         | 20%     |
| Qualcomm Atheros AR3011 Bluetooth              | 5         | 14.29%  |
| Intel Bluetooth wireless interface             | 3         | 8.57%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 5.71%   |
| Intel AX200 Bluetooth                          | 2         | 5.71%   |
| IMC Networks Bluetooth Radio                   | 2         | 5.71%   |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 5.71%   |
| Toshiba Askey for                              | 1         | 2.86%   |
| MediaTek Wireless_Device                       | 1         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 2.86%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 2.86%   |
| Dell Wireless 360 Bluetooth                    | 1         | 2.86%   |
| Broadcom HP Portable Bumble Bee                | 1         | 2.86%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 2.86%   |
| Apple Bluetooth USB Host Controller            | 1         | 2.86%   |
| Apple Bluetooth HCI                            | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 53        | 71.62%  |
| AMD                              | 16        | 21.62%  |
| Silicon Integrated Systems [SiS] | 3         | 4.05%   |
| Nvidia                           | 1         | 1.35%   |
| ESS Technology                   | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 7.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 6.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 5.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.4%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 4.4%    |
| AMD FCH Azalia Controller                                                                         | 4         | 4.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 3.3%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 3.3%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 3.3%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 3.3%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 3         | 3.3%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.2%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.2%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 2.2%    |
| AMD High Definition Audio Controller                                                              | 2         | 2.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.2%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.1%    |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.1%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.1%    |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.1%    |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.1%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 1.1%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.1%    |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 22        | 28.21%  |
| Samsung Electronics | 17        | 21.79%  |
| SK hynix            | 10        | 12.82%  |
| Kingston            | 7         | 8.97%   |
| Elpida              | 6         | 7.69%   |
| Unknown (ABCD)      | 5         | 6.41%   |
| Micron Technology   | 3         | 3.85%   |
| A-DATA Technology   | 2         | 2.56%   |
| Toshiba             | 1         | 1.28%   |
| Team                | 1         | 1.28%   |
| Ramaxel Technology  | 1         | 1.28%   |
| Crucial             | 1         | 1.28%   |
| Corsair             | 1         | 1.28%   |
| Unknown             | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 7.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 6.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 2.41%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 2.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.41%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.2%    |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.2%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.2%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.2%    |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.2%    |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.2%    |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.2%    |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s            | 1         | 1.2%    |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s             | 1         | 1.2%    |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.2%    |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.2%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.2%    |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 1.2%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.2%    |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 1.2%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 26        | 35.62%  |
| DDR2   | 17        | 23.29%  |
| DDR4   | 9         | 12.33%  |
| DDR    | 6         | 8.22%   |
| LPDDR4 | 5         | 6.85%   |
| SDRAM  | 4         | 5.48%   |
| LPDDR3 | 2         | 2.74%   |
| DRAM   | 2         | 2.74%   |
| DDR5   | 2         | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 94.44%  |
| Unknown      | 2         | 2.78%   |
| Row Of Chips | 1         | 1.39%   |
| DIMM         | 1         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 24        | 30.77%  |
| 4096  | 23        | 29.49%  |
| 8192  | 13        | 16.67%  |
| 1024  | 11        | 14.1%   |
| 512   | 4         | 5.13%   |
| 32768 | 1         | 1.28%   |
| 16384 | 1         | 1.28%   |
| 256   | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 20.27%  |
| Unknown | 15        | 20.27%  |
| 2400    | 8         | 10.81%  |
| 667     | 7         | 9.46%   |
| 1334    | 4         | 5.41%   |
| 1067    | 4         | 5.41%   |
| 3200    | 3         | 4.05%   |
| 1333    | 3         | 4.05%   |
| 5600    | 2         | 2.7%    |
| 3266    | 2         | 2.7%    |
| 2667    | 2         | 2.7%    |
| 1867    | 2         | 2.7%    |
| 533     | 2         | 2.7%    |
| 4199    | 1         | 1.35%   |
| 2048    | 1         | 1.35%   |
| 1066    | 1         | 1.35%   |
| 800     | 1         | 1.35%   |
| 266     | 1         | 1.35%   |

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
| IMC Networks                           | 6         | 13.33%  |
| Chicony Electronics                    | 6         | 13.33%  |
| Suyin                                  | 5         | 11.11%  |
| Microdia                               | 5         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 5         | 11.11%  |
| Bison Electronics                      | 5         | 11.11%  |
| Ricoh                                  | 3         | 6.67%   |
| USB Camera CS                          | 1         | 2.22%   |
| Sunplus Innovation Technology          | 1         | 2.22%   |
| Silicon Motion                         | 1         | 2.22%   |
| Realtek Semiconductor                  | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| Cubeternet                             | 1         | 2.22%   |
| Apple                                  | 1         | 2.22%   |
| ALi                                    | 1         | 2.22%   |
| Alcor Micro                            | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                                      | 2         | 4.44%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 4.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 4.44%   |
| Bison Integrated Camera                                     | 2         | 4.44%   |
| USB Camera CS USB Camera CS                                 | 1         | 2.22%   |
| Suyin HD WebCam                                             | 1         | 2.22%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 2.22%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.22%   |
| Sunplus HD WebCam                                           | 1         | 2.22%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 2.22%   |
| Ricoh Webcam 1000                                           | 1         | 2.22%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 2.22%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 2.22%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 2.22%   |
| Quanta Chromebook HD Camera                                 | 1         | 2.22%   |
| Microdia Webcam Vitade AF                                   | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 2.22%   |
| Microdia Integrated Webcam                                  | 1         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.22%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 2.22%   |
| IMC Networks Integrated Camera                              | 1         | 2.22%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 2.22%   |
| Cubeternet USB2.0 Camera                                    | 1         | 2.22%   |
| Chicony WebCam                                              | 1         | 2.22%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 2.22%   |
| Chicony Integrated Camera                                   | 1         | 2.22%   |
| Chicony HP Webcam                                           | 1         | 2.22%   |
| Chicony HP HD Webcam                                        | 1         | 2.22%   |
| Chicony CNF8029                                             | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 2.22%   |
| Bison USB Camera                                            | 1         | 2.22%   |
| Bison HD Webcam                                             | 1         | 2.22%   |
| Bison EasyCamera                                            | 1         | 2.22%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.22%   |
| ALi M5603 Video Camera Controller                           | 1         | 2.22%   |
| Alcor Micro USB 2.0 Camera                                  | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Synaptics                  | 1         | 20%     |
| STMicroelectronics         | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| STMicroelectronics Fingerprint Reader             | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 58        | 80.56%  |
| 2     | 7         | 9.72%   |
| 1     | 6         | 8.33%   |
| 4     | 1         | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 37.5%   |
| Fingerprint reader       | 5         | 20.83%  |
| Net/wireless             | 2         | 8.33%   |
| Flash memory             | 2         | 8.33%   |
| Communication controller | 2         | 8.33%   |
| Chipcard                 | 2         | 8.33%   |
| Camera                   | 2         | 8.33%   |

