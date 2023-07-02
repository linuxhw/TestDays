Kubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 93

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | G3 3779                     | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| ASUSTek   | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP        | Laptop 14s-dq2xxx           | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| HP        | ZBook Studio 15.6 inch G... | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek   | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google    | Kohaku                      | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple     | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple     | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo    | ThinkPad L15 Gen 2a 20X7... | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo    | ThinkPad L15 Gen 2a 20X7... | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| HP        | Laptop 14s-dq2xxx           | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP        | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| ASUSTek   | ASUS EXPERTBOOK B9400CBA... | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Framework | Laptop (12th Gen Intel C... | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| HP        | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo    | IdeaPad S340-14IIL 81VV     | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Dell      | Latitude E6420              | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Dell      | G3 3779                     | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Apple     | MacBookAir5,1               | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple     | MacBookAir5,1               | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple     | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo    | Slim 7 ProX 14ARH7 82V2     | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo    | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| Lenovo    | Slim 7 ProX 14ARH7 82V2     | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Lenovo    | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek   | K50IJ                       | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte  | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP        | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP        | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte  | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| ASUSTek   | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| MSI       | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer      | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo    | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo    | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo    | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Google    | Bluebird                    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple     | MacBookPro9,1               | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| Lenovo    | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME   | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek   | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer      | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo    | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Acer      | Swift SFX14-41G             | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP        | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI    | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP        | ENVY TS 15                  | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP        | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI    | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell      | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Lenovo    | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP        | Laptop 15-da2xxx            | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP        | Pavilion Laptop 15-eg0xx... | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| ASUSTek   | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google    | Lars                        | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| HP        | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion    | E11201                      | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo    | ThinkPad E14 Gen 4 21ECS... | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Lenovo    | IdeaPad 3 15IAU7 82RK       | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP        | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Lenovo    | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo    | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek   | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo    | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Samsung   | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo    | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP        | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo    | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP        | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell      | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell      | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte  | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell      | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte  | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell      | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| ASUSTek   | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Acer      | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Apple     | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI    | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| ASUSTek   | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell      | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI       | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI       | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 49        | 62.82%  |
| 6.2.0-23-generic        | 9         | 11.54%  |
| 6.2.0-18-generic        | 3         | 3.85%   |
| 6.2.0-1005-lowlatency   | 2         | 2.56%   |
| 6.3.8-x64v3-xanmod1     | 1         | 1.28%   |
| 6.3.8                   | 1         | 1.28%   |
| 6.3.6-custom            | 1         | 1.28%   |
| 6.3.4-060304-generic    | 1         | 1.28%   |
| 6.3.3-060303-generic    | 1         | 1.28%   |
| 6.3.1-060301-generic    | 1         | 1.28%   |
| 6.2.10-060210-generic   | 1         | 1.28%   |
| 6.2.0-21-generic        | 1         | 1.28%   |
| 6.1.12-060112-generic   | 1         | 1.28%   |
| 6.1.0-14-generic        | 1         | 1.28%   |
| 6.1.0-060100rc4-generic | 1         | 1.28%   |
| 5.19.0-42-generic       | 1         | 1.28%   |
| 5.19.0-40-generic       | 1         | 1.28%   |
| 5.19.0-28-generic       | 1         | 1.28%   |
| 5.19.0-21-generic       | 1         | 1.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 63        | 81.82%  |
| 5.19.0  | 4         | 5.19%   |
| 6.3.8   | 2         | 2.6%    |
| 6.1.0   | 2         | 2.6%    |
| 6.3.6   | 1         | 1.3%    |
| 6.3.4   | 1         | 1.3%    |
| 6.3.3   | 1         | 1.3%    |
| 6.3.1   | 1         | 1.3%    |
| 6.2.10  | 1         | 1.3%    |
| 6.1.12  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 64        | 83.12%  |
| 6.3     | 6         | 7.79%   |
| 5.19    | 4         | 5.19%   |
| 6.1     | 3         | 3.9%    |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 73        | 96.05%  |
| KDE   | 2         | 2.63%   |
| GNOME | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 62        | 81.58%  |
| Wayland | 14        | 18.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 41        | 53.95%  |
| Unknown | 30        | 39.47%  |
| GDM3    | 3         | 3.95%   |
| LightDM | 2         | 2.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 38        | 50%     |
| de_DE  | 6         | 7.89%   |
| ru_RU  | 4         | 5.26%   |
| pl_PL  | 4         | 5.26%   |
| it_IT  | 3         | 3.95%   |
| fr_FR  | 3         | 3.95%   |
| en_GB  | 3         | 3.95%   |
| en_NZ  | 2         | 2.63%   |
| en_AU  | 2         | 2.63%   |
| pt_PT  | 1         | 1.32%   |
| pt_BR  | 1         | 1.32%   |
| nl_NL  | 1         | 1.32%   |
| hu_HU  | 1         | 1.32%   |
| fr_BE  | 1         | 1.32%   |
| es_ES  | 1         | 1.32%   |
| es_CR  | 1         | 1.32%   |
| es_CL  | 1         | 1.32%   |
| es_419 | 1         | 1.32%   |
| en_IN  | 1         | 1.32%   |
| C      | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 40        | 51.95%  |
| EFI  | 37        | 48.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 69.23%  |
| Tmpfs   | 13        | 16.67%  |
| Btrfs   | 5         | 6.41%   |
| Overlay | 3         | 3.85%   |
| Zfs     | 2         | 2.56%   |
| Xfs     | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 45        | 59.21%  |
| Unknown | 30        | 39.47%  |
| MBR     | 1         | 1.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 73.68%  |
| Yes       | 20        | 26.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 25%     |
| Hewlett-Packard     | 13        | 17.11%  |
| ASUSTek Computer    | 13        | 17.11%  |
| Dell                | 7         | 9.21%   |
| Apple               | 4         | 5.26%   |
| Acer                | 4         | 5.26%   |
| MSI                 | 3         | 3.95%   |
| HUAWEI              | 3         | 3.95%   |
| Google              | 3         | 3.95%   |
| Gigabyte Technology | 3         | 3.95%   |
| Samsung Electronics | 1         | 1.32%   |
| Medion              | 1         | 1.32%   |
| Framework           | 1         | 1.32%   |
| BOSGAME             | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Dell G3 3779                                       | 2         | 2.63%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI           | 2         | 2.63%   |
| Samsung 950XED                                     | 1         | 1.32%   |
| MSI Titan GT77HX 13VH                              | 1         | 1.32%   |
| MSI Raider GE67HX 12UGS                            | 1         | 1.32%   |
| MSI Bravo 17 A4DDK                                 | 1         | 1.32%   |
| Medion E11201                                      | 1         | 1.32%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW        | 1         | 1.32%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01             | 1         | 1.32%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00              | 1         | 1.32%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE                | 1         | 1.32%   |
| Lenovo ThinkPad L15 Gen 2a 20X7S05600              | 1         | 1.32%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100               | 1         | 1.32%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW               | 1         | 1.32%   |
| Lenovo ThinkPad E15 Gen 2 20TD00GSPB               | 1         | 1.32%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000               | 1         | 1.32%   |
| Lenovo ThinkPad E14 Gen 3 20YDS02D00               | 1         | 1.32%   |
| Lenovo ThinkBook 14 G4 ABA 21DK                    | 1         | 1.32%   |
| Lenovo Slim 7 ProX 14ARH7 82V2                     | 1         | 1.32%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                   | 1         | 1.32%   |
| Lenovo IdeaPad Y700-15ISK 80NV                     | 1         | 1.32%   |
| Lenovo IdeaPad S340-14IIL 81VV                     | 1         | 1.32%   |
| Lenovo IdeaPad 700-17ISK 80RV                      | 1         | 1.32%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN                   | 1         | 1.32%   |
| Lenovo IdeaPad 3 15IAU7 82RK                       | 1         | 1.32%   |
| Lenovo IdeaPad 3 15ALC6 82MF                       | 1         | 1.32%   |
| HUAWEI NBD-WXX9                                    | 1         | 1.32%   |
| HUAWEI HN-WX9X                                     | 1         | 1.32%   |
| HUAWEI BOHB-WAX9                                   | 1         | 1.32%   |
| HP ZBook Studio 15.6 inch G8 Mobile Workstation PC | 1         | 1.32%   |
| HP ProBook 650 G1                                  | 1         | 1.32%   |
| HP ProBook 440 G5                                  | 1         | 1.32%   |
| HP Pavilion Notebook                               | 1         | 1.32%   |
| HP Pavilion Laptop 15-eh1xxx                       | 1         | 1.32%   |
| HP Pavilion Laptop 15-eg0xxx                       | 1         | 1.32%   |
| HP Pavilion Laptop 14-ce2xxx                       | 1         | 1.32%   |
| HP Laptop 15-da2xxx                                | 1         | 1.32%   |
| HP Laptop 14s-dq2xxx                               | 1         | 1.32%   |
| HP ENVY TS 15                                      | 1         | 1.32%   |
| HP EliteBook 8760w                                 | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 13.16%  |
| Lenovo IdeaPad    | 6         | 7.89%   |
| HP Pavilion       | 4         | 5.26%   |
| Dell Latitude     | 3         | 3.95%   |
| ASUS ROG          | 3         | 3.95%   |
| ASUS ASUS         | 3         | 3.95%   |
| Acer Aspire       | 3         | 3.95%   |
| HP ProBook        | 2         | 2.63%   |
| HP Laptop         | 2         | 2.63%   |
| HP EliteBook      | 2         | 2.63%   |
| Gigabyte G5       | 2         | 2.63%   |
| Dell G3           | 2         | 2.63%   |
| ASUS Zenbook      | 2         | 2.63%   |
| ASUS VivoBook     | 2         | 2.63%   |
| Apple MacBookPro9 | 2         | 2.63%   |
| Samsung 950XED    | 1         | 1.32%   |
| MSI Titan         | 1         | 1.32%   |
| MSI Raider        | 1         | 1.32%   |
| MSI Bravo         | 1         | 1.32%   |
| Medion E11201     | 1         | 1.32%   |
| Lenovo ThinkBook  | 1         | 1.32%   |
| Lenovo Slim       | 1         | 1.32%   |
| Lenovo Legion     | 1         | 1.32%   |
| HUAWEI NBD-WXX9   | 1         | 1.32%   |
| HUAWEI HN-WX9X    | 1         | 1.32%   |
| HUAWEI BOHB-WAX9  | 1         | 1.32%   |
| HP ZBook          | 1         | 1.32%   |
| HP ENVY           | 1         | 1.32%   |
| HP Compaq         | 1         | 1.32%   |
| Google Lars       | 1         | 1.32%   |
| Google Kohaku     | 1         | 1.32%   |
| Google Bluebird   | 1         | 1.32%   |
| Gigabyte AORUS    | 1         | 1.32%   |
| Framework Laptop  | 1         | 1.32%   |
| Dell Precision    | 1         | 1.32%   |
| Dell Inspiron     | 1         | 1.32%   |
| BOSGAME B95       | 1         | 1.32%   |
| ASUS X51RL        | 1         | 1.32%   |
| ASUS K50IJ        | 1         | 1.32%   |
| ASUS G551JM       | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 20        | 26.32%  |
| 2021 | 17        | 22.37%  |
| 2019 | 6         | 7.89%   |
| 2023 | 5         | 6.58%   |
| 2020 | 5         | 6.58%   |
| 2012 | 5         | 6.58%   |
| 2016 | 3         | 3.95%   |
| 2011 | 3         | 3.95%   |
| 2018 | 2         | 2.63%   |
| 2017 | 2         | 2.63%   |
| 2015 | 2         | 2.63%   |
| 2014 | 2         | 2.63%   |
| 2013 | 2         | 2.63%   |
| 2009 | 1         | 1.32%   |
| 2007 | 1         | 1.32%   |

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
| Disabled | 70        | 92.11%  |
| Enabled  | 6         | 7.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 96.05%  |
| Yes  | 3         | 3.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 23        | 30.26%  |
| 16.01-24.0  | 14        | 18.42%  |
| 4.01-8.0    | 13        | 17.11%  |
| 32.01-64.0  | 10        | 13.16%  |
| 3.01-4.0    | 10        | 13.16%  |
| 64.01-256.0 | 3         | 3.95%   |
| 24.01-32.0  | 2         | 2.63%   |
| 2.01-3.0    | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 33.33%  |
| 2.01-3.0   | 21        | 26.92%  |
| 1.01-2.0   | 14        | 17.95%  |
| 3.01-4.0   | 12        | 15.38%  |
| 8.01-16.0  | 4         | 5.13%   |
| 32.01-64.0 | 1         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 72.73%  |
| 2      | 18        | 23.38%  |
| 3      | 3         | 3.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 85.53%  |
| Yes       | 11        | 14.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 69.74%  |
| No        | 23        | 30.26%  |

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
| Yes       | 67        | 88.16%  |
| No        | 9         | 11.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 15        | 19.74%  |
| Germany      | 9         | 11.84%  |
| Russia       | 5         | 6.58%   |
| Poland       | 5         | 6.58%   |
| UK           | 4         | 5.26%   |
| Belgium      | 4         | 5.26%   |
| Italy        | 3         | 3.95%   |
| France       | 3         | 3.95%   |
| Turkey       | 2         | 2.63%   |
| Portugal     | 2         | 2.63%   |
| New Zealand  | 2         | 2.63%   |
| Netherlands  | 2         | 2.63%   |
| India        | 2         | 2.63%   |
| Canada       | 2         | 2.63%   |
| Australia    | 2         | 2.63%   |
| Sweden       | 1         | 1.32%   |
| Spain        | 1         | 1.32%   |
| Saudi Arabia | 1         | 1.32%   |
| Mexico       | 1         | 1.32%   |
| Lithuania    | 1         | 1.32%   |
| Ivory Coast  | 1         | 1.32%   |
| Israel       | 1         | 1.32%   |
| Hungary      | 1         | 1.32%   |
| Costa Rica   | 1         | 1.32%   |
| Colombia     | 1         | 1.32%   |
| Chile        | 1         | 1.32%   |
| Bulgaria     | 1         | 1.32%   |
| Brazil       | 1         | 1.32%   |
| Argentina    | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Munich                  | 2         | 2.63%   |
| Moscow                  | 2         | 2.63%   |
| Istanbul                | 2         | 2.63%   |
| Brussels                | 2         | 2.63%   |
| Berlin                  | 2         | 2.63%   |
| West Des Moines         | 1         | 1.32%   |
| Warsaw                  | 1         | 1.32%   |
| Waianae                 | 1         | 1.32%   |
| Vsevolozhsk             | 1         | 1.32%   |
| Viña del Mar           | 1         | 1.32%   |
| Vilnius                 | 1         | 1.32%   |
| Villa Dominico          | 1         | 1.32%   |
| Vienna                  | 1         | 1.32%   |
| Valley Center           | 1         | 1.32%   |
| Thunder Bay             | 1         | 1.32%   |
| Theydon Bois            | 1         | 1.32%   |
| Tel Aviv                | 1         | 1.32%   |
| Szczecin                | 1         | 1.32%   |
| Sydney                  | 1         | 1.32%   |
| Sumter                  | 1         | 1.32%   |
| Stavropol               | 1         | 1.32%   |
| Shumen                  | 1         | 1.32%   |
| Sherbrooke              | 1         | 1.32%   |
| Santa Maria di Sala     | 1         | 1.32%   |
| Salt Lake City          | 1         | 1.32%   |
| Saint-Georges-sur-Meuse | 1         | 1.32%   |
| Roubaix                 | 1         | 1.32%   |
| Rewal                   | 1         | 1.32%   |
| Remeteszolos            | 1         | 1.32%   |
| Raleigh                 | 1         | 1.32%   |
| Poznan                  | 1         | 1.32%   |
| Portimao                | 1         | 1.32%   |
| Phoenix                 | 1         | 1.32%   |
| Philadelphia            | 1         | 1.32%   |
| Paris                   | 1         | 1.32%   |
| Oldenburg               | 1         | 1.32%   |
| Olathe                  | 1         | 1.32%   |
| New York                | 1         | 1.32%   |
| Nashik                  | 1         | 1.32%   |
| Münster                | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 20        | 24     | 20.2%   |
| Micron Technology       | 9         | 9      | 9.09%   |
| SanDisk                 | 8         | 8      | 8.08%   |
| SK hynix                | 7         | 7      | 7.07%   |
| Intel                   | 7         | 8      | 7.07%   |
| Toshiba                 | 6         | 7      | 6.06%   |
| Crucial                 | 5         | 5      | 5.05%   |
| WDC                     | 4         | 4      | 4.04%   |
| Seagate                 | 4         | 4      | 4.04%   |
| Phison Electronics      | 4         | 4      | 4.04%   |
| Unknown                 | 3         | 3      | 3.03%   |
| Kingston                | 3         | 3      | 3.03%   |
| UMIS                    | 2         | 3      | 2.02%   |
| Solid State Storage     | 2         | 2      | 2.02%   |
| Silicon Motion          | 2         | 2      | 2.02%   |
| Hitachi                 | 2         | 2      | 2.02%   |
| WALRAM                  | 1         | 1      | 1.01%   |
| Union Memory (Shenzhen) | 1         | 1      | 1.01%   |
| SSSTC                   | 1         | 1      | 1.01%   |
| SSDPR-CX                | 1         | 1      | 1.01%   |
| Phison                  | 1         | 1      | 1.01%   |
| Patriot                 | 1         | 1      | 1.01%   |
| Lenovo                  | 1         | 1      | 1.01%   |
| JMicron Technology      | 1         | 1      | 1.01%   |
| HGST                    | 1         | 1      | 1.01%   |
| FURY                    | 1         | 2      | 1.01%   |
| A-DATA Technology       | 1         | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel SSD 660P Series 512GB                         | 4         | 4%      |
| Phison E16 PCIe4 NVMe Controller 1TB                | 3         | 3%      |
| Unknown MMC Card  32GB                              | 2         | 2%      |
| UMIS RPJTJ512MGE1QDQ 512GB                          | 2         | 2%      |
| SanDisk NVMe SSD Drive 2TB                          | 2         | 2%      |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 2%      |
| Samsung MZVLQ256HAJD-000H1 256GB                    | 2         | 2%      |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 2         | 2%      |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 2%      |
| WDC WDBNCE5000PNC 500GB SSD                         | 1         | 1%      |
| WDC WD16 00AVBB-63SYA0 160GB                        | 1         | 1%      |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1%      |
| WDC WD10 JPVX-00JC3T0 1TB                           | 1         | 1%      |
| WALRAM 240G                                         | 1         | 1%      |
| Unknown Biwin  64GB                                 | 1         | 1%      |
| Union Memory (Shenzhen) RPFTJ256PDD2MWX 256GB       | 1         | 1%      |
| Toshiba XG6 NVMe SSD Controller 2TB                 | 1         | 1%      |
| Toshiba MQ04ABF100 1TB                              | 1         | 1%      |
| Toshiba MQ02ABF100 1TB                              | 1         | 1%      |
| Toshiba MQ01ACF050 500GB                            | 1         | 1%      |
| Toshiba MQ01ABD075 752GB                            | 1         | 1%      |
| Toshiba KXG60ZNV512G 512GB                          | 1         | 1%      |
| SSSTC CL4-4D512-Q79 512GB                           | 1         | 1%      |
| SSDPR-CX 400-256-G2 256GB                           | 1         | 1%      |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 1%      |
| Solid State Storage SSSTC CL1-3D256 256GB           | 1         | 1%      |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 1         | 1%      |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 1         | 1%      |
| SK hynix SHGP31-1000GM 1TB                          | 1         | 1%      |
| SK hynix HFS256G32MND-2900A 256GB SSD               | 1         | 1%      |
| SK hynix HFM512GD3JX016N 512GB                      | 1         | 1%      |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 1%      |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1%      |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB | 1         | 1%      |
| Silicon Motion PCIe-8 SSD 256GB                     | 1         | 1%      |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1%      |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1%      |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1%      |
| Seagate BUP Slim BK 1TB                             | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 28.57%  |
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 3         | 3      | 21.43%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 5         | 5      | 25%     |
| Micron Technology   | 3         | 3      | 15%     |
| Samsung Electronics | 2         | 2      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Intel               | 2         | 3      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Patriot             | 1         | 1      | 5%      |
| Lenovo              | 1         | 1      | 5%      |
| FURY                | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 53        | 66     | 57.61%  |
| SSD     | 19        | 21     | 20.65%  |
| HDD     | 14        | 14     | 15.22%  |
| MMC     | 3         | 3      | 3.26%   |
| Unknown | 3         | 3      | 3.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 52        | 65     | 59.09%  |
| SATA | 28        | 34     | 31.82%  |
| SAS  | 5         | 5      | 5.68%   |
| MMC  | 3         | 3      | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 54.84%  |
| 0.51-1.0   | 12        | 14     | 38.71%  |
| 1.01-2.0   | 2         | 2      | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 29.87%  |
| 501-1000       | 19        | 24.68%  |
| 251-500        | 11        | 14.29%  |
| 1001-2000      | 8         | 10.39%  |
| More than 3000 | 4         | 5.19%   |
| 1-20           | 4         | 5.19%   |
| 2001-3000      | 3         | 3.9%    |
| 51-100         | 3         | 3.9%    |
| 21-50          | 2         | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 21        | 26.25%  |
| 1-20           | 19        | 23.75%  |
| 101-250        | 12        | 15%     |
| 51-100         | 8         | 10%     |
| 251-500        | 7         | 8.75%   |
| 1001-2000      | 6         | 7.5%    |
| 501-1000       | 5         | 6.25%   |
| More than 3000 | 1         | 1.25%   |
| 2001-3000      | 1         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 50%     |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 1         | 1      | 50%     |
| SK hynix | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 49        | 72     | 62.03%  |
| Works    | 28        | 33     | 35.44%  |
| Malfunc  | 2         | 2      | 2.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 39        | 38.24%  |
| Samsung Electronics            | 18        | 17.65%  |
| AMD                            | 9         | 8.82%   |
| SanDisk                        | 7         | 6.86%   |
| SK hynix                       | 6         | 5.88%   |
| Micron Technology              | 6         | 5.88%   |
| Phison Electronics             | 5         | 4.9%    |
| Union Memory (Shenzhen)        | 3         | 2.94%   |
| Solid State Storage Technology | 3         | 2.94%   |
| Toshiba America Info Systems   | 2         | 1.96%   |
| Silicon Motion                 | 2         | 1.96%   |
| Kingston Technology Company    | 1         | 0.98%   |
| ADATA Technology               | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 7.48%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 6.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 5.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 5.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 4.67%   |
| Micron NVMe Storage Controller                                                 | 5         | 4.67%   |
| Intel SSD 660P Series                                                          | 4         | 3.74%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.8%    |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.8%    |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 2         | 1.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.87%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.87%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.87%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.93%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.93%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.93%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.93%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.93%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.93%   |
| Samsung NVMe SSD Controller PM9B1                                              | 1         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.93%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 0.93%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.93%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 52        | 52%     |
| SATA | 40        | 40%     |
| RAID | 7         | 7%      |
| IDE  | 1         | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 69.74%  |
| AMD    | 23        | 30.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 5.26%   |
| AMD Ryzen 7 6800H with Radeon Graphics      | 3         | 3.95%   |
| AMD Ryzen 7 5825U with Radeon Graphics      | 3         | 3.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 2.63%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 2.63%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.32%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 1.32%   |
| Intel N95                                   | 1         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.32%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.32%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.32%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.32%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.32%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.32%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.32%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.32%   |
| Intel Core i3-6157U CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz        | 1         | 1.32%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.32%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 1.32%   |
| Intel Celeron CPU B830 @ 1.80GHz            | 1         | 1.32%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 1         | 1.32%   |
| Intel 13th Gen Core i9-13980HX              | 1         | 1.32%   |
| Intel 13th Gen Core i7-1365U                | 1         | 1.32%   |
| Intel 12th Gen Core i9-12900H               | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 18        | 23.68%  |
| Intel Core i5           | 15        | 19.74%  |
| Intel Core i7           | 12        | 15.79%  |
| AMD Ryzen 7             | 10        | 13.16%  |
| AMD Ryzen 5             | 8         | 10.53%  |
| Intel Celeron           | 4         | 5.26%   |
| AMD Ryzen 9             | 3         | 3.95%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Pentium           | 1         | 1.32%   |
| Intel Core i3           | 1         | 1.32%   |
| Intel Core 2 Duo        | 1         | 1.32%   |
| AMD Ryzen 5 PRO         | 1         | 1.32%   |
| AMD A4                  | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 23        | 30.26%  |
| 2      | 18        | 23.68%  |
| 8      | 15        | 19.74%  |
| 6      | 11        | 14.47%  |
| 10     | 3         | 3.95%   |
| 14     | 2         | 2.63%   |
| 12     | 2         | 2.63%   |
| 24     | 1         | 1.32%   |
| 16     | 1         | 1.32%   |

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
| 2      | 66        | 86.84%  |
| 1      | 10        | 13.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 81.82%  |
| 0x0a50000c | 5         | 6.49%   |
| 0x0a404102 | 4         | 5.19%   |
| 0x0a404101 | 2         | 2.6%    |
| 0x90672    | 1         | 1.3%    |
| 0x08600104 | 1         | 1.3%    |
| 0x08108109 | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 17        | 22.37%  |
| KabyLake         | 10        | 13.16%  |
| Zen 3            | 8         | 10.53%  |
| Alderlake Hybrid | 7         | 9.21%   |
| Skylake          | 6         | 7.89%   |
| TigerLake        | 5         | 6.58%   |
| IvyBridge        | 5         | 6.58%   |
| SandyBridge      | 4         | 5.26%   |
| Haswell          | 3         | 3.95%   |
| Zen 2            | 2         | 2.63%   |
| CometLake        | 2         | 2.63%   |
| Zen+             | 1         | 1.32%   |
| Puma             | 1         | 1.32%   |
| Penryn           | 1         | 1.32%   |
| IceLake          | 1         | 1.32%   |
| Goldmont plus    | 1         | 1.32%   |
| Goldmont         | 1         | 1.32%   |
| Core             | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 49.04%  |
| Nvidia | 27        | 25.96%  |
| AMD    | 26        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt [Radeon 680M]                                               | 7         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 4         | 3.81%   |
| AMD Lucienne                                                              | 4         | 3.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.81%   |
| AMD Barcelo                                                               | 4         | 3.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 2.86%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 2.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 2.86%   |
| Intel HD Graphics 530                                                     | 3         | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.86%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 1.9%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 1.9%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.9%    |
| AMD Renoir                                                                | 2         | 1.9%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                      | 1         | 0.95%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.95%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                    | 1         | 0.95%   |
| Nvidia GP108GLM [Quadro P520]                                             | 1         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.95%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.95%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.95%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.95%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.95%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 0.95%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.95%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.95%   |
| Nvidia GA107BM [GeForce RTX 3050 Mobile]                                  | 1         | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.95%   |
| Nvidia AD104M [GeForce RTX 4080 Max-Q / Mobile]                           | 1         | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 0.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 0.95%   |
| Intel Raptor Lake-S UHD Graphics                                          | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 38.16%  |
| Intel + Nvidia | 20        | 26.32%  |
| 1 x AMD        | 17        | 22.37%  |
| AMD + Nvidia   | 7         | 9.21%   |
| Other          | 1         | 1.32%   |
| 2 x AMD        | 1         | 1.32%   |
| Intel + AMD    | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 70.13%  |
| Proprietary | 22        | 28.57%  |
| Unknown     | 1         | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 71.43%  |
| 3.01-4.0   | 8         | 10.39%  |
| 0.01-0.5   | 5         | 6.49%   |
| 0.51-1.0   | 4         | 5.19%   |
| 1.01-2.0   | 3         | 3.9%    |
| 7.01-8.0   | 2         | 2.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 20%     |
| BOE                     | 17        | 18.89%  |
| Samsung Electronics     | 15        | 16.67%  |
| Chimei Innolux          | 11        | 12.22%  |
| LG Display              | 5         | 5.56%   |
| Goldstar                | 5         | 5.56%   |
| Apple                   | 4         | 4.44%   |
| PANDA                   | 3         | 3.33%   |
| Sharp                   | 2         | 2.22%   |
| UGD                     | 1         | 1.11%   |
| Panasonic               | 1         | 1.11%   |
| LOE                     | 1         | 1.11%   |
| Lenovo                  | 1         | 1.11%   |
| KDC                     | 1         | 1.11%   |
| KDB                     | 1         | 1.11%   |
| Denver                  | 1         | 1.11%   |
| Dell                    | 1         | 1.11%   |
| CSO                     | 1         | 1.11%   |
| Chi Mei Optoelectronics | 1         | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 3.33%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 2.22%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 1.11%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.11%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 1.11%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 1.11%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 1.11%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 1.11%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 1         | 1.11%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.11%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 1.11%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.11%   |
| PANDA LCD Monitor NCP003F 1920x1080 344x194mm 15.5-inch               | 1         | 1.11%   |
| Panasonic TV MEIA081 1280x720 698x392mm 31.5-inch                     | 1         | 1.11%   |
| LOE LOEWE HDMI TV LOE0610 1280x720 700x394mm 31.6-inch                | 1         | 1.11%   |
| LG Display LCD Monitor LGD06DA 1920x1080 344x194mm 15.5-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.11%   |
| Lenovo P24h-2L LEN62B2 2560x1440 527x296mm 23.8-inch                  | 1         | 1.11%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 1         | 1.11%   |
| KDB LCD Monitor KDB0101 1366x768 256x144mm 11.6-inch                  | 1         | 1.11%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1         | 1.11%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 1         | 1.11%   |
| Goldstar TV SSCR2 GSM8080 3840x2160                                   | 1         | 1.11%   |
| Goldstar LG ULTRAWIDE GSM59F2 2560x1080 800x340mm 34.2-inch           | 1         | 1.11%   |
| Goldstar FHD GSM5BC9 1920x1080 480x270mm 21.7-inch                    | 1         | 1.11%   |
| Denver M24-FHD-165 LHC2400 1920x1080 527x296mm 23.8-inch              | 1         | 1.11%   |
| Dell E2318HX DELF097 1920x1080 509x286mm 23.0-inch                    | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 48.24%  |
| 1366x768 (WXGA)   | 13        | 15.29%  |
| 3840x2160 (4K)    | 5         | 5.88%   |
| 2560x1440 (QHD)   | 5         | 5.88%   |
| 1600x900 (HD+)    | 3         | 3.53%   |
| 2880x1800         | 2         | 2.35%   |
| 2560x1600         | 2         | 2.35%   |
| 2560x1080         | 2         | 2.35%   |
| 1280x800 (WXGA)   | 2         | 2.35%   |
| 3840x2400         | 1         | 1.18%   |
| 3840x1100         | 1         | 1.18%   |
| 3440x1440         | 1         | 1.18%   |
| 3072x1920         | 1         | 1.18%   |
| 2256x1504         | 1         | 1.18%   |
| 2160x1440         | 1         | 1.18%   |
| 1920x540          | 1         | 1.18%   |
| 1920x1200 (WUXGA) | 1         | 1.18%   |
| 1440x900 (WXGA+)  | 1         | 1.18%   |
| 1280x720 (HD)     | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 38.2%   |
| 13      | 12        | 13.48%  |
| 14      | 11        | 12.36%  |
| 17      | 10        | 11.24%  |
| 23      | 4         | 4.49%   |
| 16      | 4         | 4.49%   |
| 31      | 3         | 3.37%   |
| 11      | 3         | 3.37%   |
| 34      | 2         | 2.25%   |
| 72      | 1         | 1.12%   |
| 40      | 1         | 1.12%   |
| 24      | 1         | 1.12%   |
| 21      | 1         | 1.12%   |
| 20      | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 61.36%  |
| 351-400     | 11        | 12.5%   |
| 201-300     | 8         | 9.09%   |
| 501-600     | 5         | 5.68%   |
| 601-700     | 3         | 3.41%   |
| 701-800     | 2         | 2.27%   |
| 401-500     | 2         | 2.27%   |
| 801-900     | 1         | 1.14%   |
| 1501-2000   | 1         | 1.14%   |
| Unknown     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 81.25%  |
| 16/10 | 10        | 12.5%   |
| 3/2   | 2         | 2.5%    |
| 21/9  | 2         | 2.5%    |
| 3.40  | 1         | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 38.2%   |
| 81-90          | 18        | 20.22%  |
| 121-130        | 10        | 11.24%  |
| 201-250        | 6         | 6.74%   |
| 351-500        | 5         | 5.62%   |
| 51-60          | 4         | 4.49%   |
| 111-120        | 4         | 4.49%   |
| 71-80          | 2         | 2.25%   |
| 91-100         | 2         | 2.25%   |
| More than 1000 | 1         | 1.12%   |
| 151-200        | 1         | 1.12%   |
| 501-1000       | 1         | 1.12%   |
| Unknown        | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 51.16%  |
| 101-120       | 13        | 15.12%  |
| 51-100        | 12        | 13.95%  |
| 161-240       | 9         | 10.47%  |
| More than 240 | 6         | 6.98%   |
| 1-50          | 1         | 1.16%   |
| Unknown       | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 78.95%  |
| 2     | 14        | 18.42%  |
| 3     | 1         | 1.32%   |
| 0     | 1         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 38.74%  |
| Intel                 | 38        | 34.23%  |
| MediaTek              | 11        | 9.91%   |
| Qualcomm Atheros      | 5         | 4.5%    |
| Broadcom              | 5         | 4.5%    |
| Hewlett-Packard       | 2         | 1.8%    |
| ASIX Electronics      | 2         | 1.8%    |
| Samsung Electronics   | 1         | 0.9%    |
| Ralink                | 1         | 0.9%    |
| Lenovo                | 1         | 0.9%    |
| Google                | 1         | 0.9%    |
| Broadcom Limited      | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 25        | 18.52%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 5.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 3.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 2.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.96%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 2.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 1.48%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.48%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.48%   |
| Intel Wireless 8260                                                     | 2         | 1.48%   |
| Intel Wireless 7260                                                     | 2         | 1.48%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.48%   |
| ASIX AX88179 Gigabit Ethernet                                           | 2         | 1.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.74%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.74%   |
| Lenovo USB-C Dock Ethernet                                              | 1         | 0.74%   |
| Intel Wireless 7265                                                     | 1         | 0.74%   |
| Intel Wireless 3165                                                     | 1         | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.74%   |
| Intel Ethernet Controller I225-V                                        | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 49.35%  |
| Realtek Semiconductor | 16        | 20.78%  |
| MediaTek              | 11        | 14.29%  |
| Qualcomm Atheros      | 5         | 6.49%   |
| Broadcom              | 4         | 5.19%   |
| Ralink                | 1         | 1.3%    |
| Hewlett-Packard       | 1         | 1.3%    |
| Broadcom Limited      | 1         | 1.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 9.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 6.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 6.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 5.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 5.19%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 5.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 3.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 3.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 3.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.6%    |
| Intel Wireless 8265 / 8275                                              | 2         | 2.6%    |
| Intel Wireless 8260                                                     | 2         | 2.6%    |
| Intel Wireless 7260                                                     | 2         | 2.6%    |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 2.6%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.3%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.3%    |
| Intel Wireless 7265                                                     | 1         | 1.3%    |
| Intel Wireless 3165                                                     | 1         | 1.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.3%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.3%    |
| Intel Alder Lake-U CNVi: Wireless-AC                                    | 1         | 1.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 1         | 1.3%    |
| Intel 700 Series Chipset Family Wi-Fi                                   | 1         | 1.3%    |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.3%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 1.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 36        | 64.29%  |
| Intel                 | 10        | 17.86%  |
| Broadcom              | 4         | 7.14%   |
| ASIX Electronics      | 2         | 3.57%   |
| Samsung Electronics   | 1         | 1.79%   |
| Qualcomm Atheros      | 1         | 1.79%   |
| Lenovo                | 1         | 1.79%   |
| Google                | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 43.86%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 7.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.75%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.75%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.75%   |
| Google Pixel 7 Pro                                                | 1         | 1.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 58.91%  |
| Ethernet | 52        | 40.31%  |
| Modem    | 1         | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 88%     |
| Ethernet | 9         | 12%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 63.16%  |
| 1     | 28        | 36.84%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 69.74%  |
| Yes  | 23        | 30.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 50.75%  |
| Realtek Semiconductor           | 13        | 19.4%   |
| IMC Networks                    | 4         | 5.97%   |
| Foxconn / Hon Hai               | 4         | 5.97%   |
| Apple                           | 4         | 5.97%   |
| Lite-On Technology              | 3         | 4.48%   |
| Toshiba                         | 1         | 1.49%   |
| Realtek                         | 1         | 1.49%   |
| Qualcomm Atheros Communications | 1         | 1.49%   |
| Dell                            | 1         | 1.49%   |
| Broadcom                        | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 12        | 17.91%  |
| Intel Bluetooth wireless interface             | 8         | 11.94%  |
| Intel Bluetooth Device                         | 7         | 10.45%  |
| Intel AX201 Bluetooth                          | 7         | 10.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 5.97%   |
| Intel AX200 Bluetooth                          | 4         | 5.97%   |
| IMC Networks Wireless_Device                   | 4         | 5.97%   |
| Intel AX210 Bluetooth                          | 3         | 4.48%   |
| Lite-On Wireless_Device                        | 2         | 2.99%   |
| Foxconn / Hon Hai Wireless_Device              | 2         | 2.99%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 2         | 2.99%   |
| Apple Bluetooth USB Host Controller            | 2         | 2.99%   |
| Toshiba RT Bluetooth Radio                     | 1         | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.49%   |
| Realtek Bluetooth Radio                        | 1         | 1.49%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.49%   |
| Dell DW375 Bluetooth Module                    | 1         | 1.49%   |
| Broadcom BCM20702A0                            | 1         | 1.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 1.49%   |
| Apple Bluetooth Host Controller                | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 52        | 53.06%  |
| AMD                      | 25        | 25.51%  |
| Nvidia                   | 16        | 16.33%  |
| Hewlett-Packard          | 2         | 2.04%   |
| Realtek Semiconductor    | 1         | 1.02%   |
| Nordic Semiconductor ASA | 1         | 1.02%   |
| Lenovo                   | 1         | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 22        | 18.03%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 9.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 4.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 4.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 4.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 3.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.46%   |
| Nvidia Audio device                                                        | 3         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.46%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.64%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.82%   |
| Nordic Semiconductor ASA BLE Remote                                        | 1         | 0.82%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.82%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.82%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                             | 1         | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 0.82%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.82%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1         | 0.82%   |
| Hewlett-Packard USB Audio                                                  | 1         | 0.82%   |
| Hewlett-Packard HyperX Cloud Alpha Wireless                                | 1         | 0.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 34.78%  |
| SK hynix            | 10        | 21.74%  |
| Micron Technology   | 8         | 17.39%  |
| Ramaxel Technology  | 3         | 6.52%   |
| Crucial             | 3         | 6.52%   |
| Kingston            | 2         | 4.35%   |
| Unknown (ABCD)      | 1         | 2.17%   |
| Transcend           | 1         | 2.17%   |
| Corsair             | 1         | 2.17%   |
| 4ea5                | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 6.25%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 2.08%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 2.08%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 2.08%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.08%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.08%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 2.08%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.08%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 2.08%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.08%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 2.08%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.08%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 2.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.08%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.08%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM 4800MT/s              | 1         | 2.08%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.08%   |
| Samsung RAM K4F6E3S4HM-MGCJ 2GB LPDDR4 2400MT/s                  | 1         | 2.08%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 2.08%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 2.08%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 2.08%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s         | 1         | 2.08%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.08%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 1         | 2.08%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.08%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 2.08%   |
| Micron RAM MICRON/MT60B1G16HC-4 8GB SODIMM DDR5 4800MT/s         | 1         | 2.08%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 2.08%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.08%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 2.08%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 1         | 2.08%   |
| Kingston RAM 9905703-002.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 2.08%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.08%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 16        | 43.24%  |
| LPDDR5 | 7         | 18.92%  |
| DDR3   | 6         | 16.22%  |
| DDR5   | 4         | 10.81%  |
| LPDDR4 | 3         | 8.11%   |
| LPDDR3 | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 71.79%  |
| Row Of Chips | 10        | 25.64%  |
| Unknown      | 1         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 47.5%   |
| 4096  | 11        | 27.5%   |
| 16384 | 6         | 15%     |
| 32768 | 2         | 5%      |
| 2048  | 2         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 28.95%  |
| 6400  | 7         | 18.42%  |
| 4800  | 4         | 10.53%  |
| 2400  | 4         | 10.53%  |
| 1600  | 4         | 10.53%  |
| 2667  | 3         | 7.89%   |
| 2133  | 2         | 5.26%   |
| 4267  | 1         | 2.63%   |
| 1334  | 1         | 2.63%   |
| 1333  | 1         | 2.63%   |

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
| Canon PIXMA MX490 Series | 1         | 100%    |

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
| Chicony Electronics                    | 12        | 19.05%  |
| Quanta                                 | 8         | 12.7%   |
| IMC Networks                           | 7         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 5         | 7.94%   |
| Bison Electronics                      | 5         | 7.94%   |
| Realtek Semiconductor                  | 4         | 6.35%   |
| Apple                                  | 4         | 6.35%   |
| Acer                                   | 4         | 6.35%   |
| Syntek                                 | 3         | 4.76%   |
| Sunplus Innovation Technology          | 3         | 4.76%   |
| Luxvisions Innotech Limited            | 3         | 4.76%   |
| Microdia                               | 2         | 3.17%   |
| SunplusIT                              | 1         | 1.59%   |
| OYT Tech                               | 1         | 1.59%   |
| Logitech                               | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 7.69%   |
| Chicony Integrated Camera                                                  | 4         | 6.15%   |
| Apple FaceTime HD Camera                                                   | 3         | 4.62%   |
| Acer Integrated Camera                                                     | 3         | 4.62%   |
| Syntek Integrated Camera                                                   | 2         | 3.08%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 3.08%   |
| Realtek HP Truevision HD                                                   | 2         | 3.08%   |
| Quanta USB2.0 HD UVC WebCam                                                | 2         | 3.08%   |
| Chicony HD WebCam                                                          | 2         | 3.08%   |
| Chicony 720p HD Camera                                                     | 2         | 3.08%   |
| Bison Integrated RGB Camera                                                | 2         | 3.08%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.54%   |
| SunplusIT 1080p FHD Camera                                                 | 1         | 1.54%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.54%   |
| Realtek Laptop Camera                                                      | 1         | 1.54%   |
| Realtek Integrated Webcam                                                  | 1         | 1.54%   |
| Quanta ov9734_techfront_camera                                             | 1         | 1.54%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 1.54%   |
| Quanta HP HD Camera                                                        | 1         | 1.54%   |
| Quanta HP 5MP Camera                                                       | 1         | 1.54%   |
| Quanta HD User Facing                                                      | 1         | 1.54%   |
| Quanta HD Camera                                                           | 1         | 1.54%   |
| OYT Tech OYV1RDFF1                                                         | 1         | 1.54%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.54%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.54%   |
| Logitech Webcam C925e                                                      | 1         | 1.54%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 1.54%   |
| IMC Networks Integrated Camera                                             | 1         | 1.54%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.54%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.54%   |
| Chicony HP Truevision HD                                                   | 1         | 1.54%   |
| Chicony HD User Facing                                                     | 1         | 1.54%   |
| Chicony 8M Camera                                                          | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 4         | 30.77%  |
| Shenzhen Goodix Technology         | 4         | 30.77%  |
| Validity Sensors                   | 3         | 23.08%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 7.69%   |
| Elan Microelectronics              | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 3         | 23.08%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 15.38%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 7.69%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                                | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 65.79%  |
| 1     | 19        | 25%     |
| 2     | 7         | 9.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 39.39%  |
| Chipcard              | 5         | 15.15%  |
| Multimedia controller | 4         | 12.12%  |
| Camera                | 4         | 12.12%  |
| Graphics card         | 3         | 9.09%   |
| Net/wireless          | 2         | 6.06%   |
| Storage               | 1         | 3.03%   |
| Card reader           | 1         | 3.03%   |

