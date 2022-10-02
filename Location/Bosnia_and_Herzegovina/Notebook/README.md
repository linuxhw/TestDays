Linux in Bosnia and Herzegovina - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

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
| HP            | ProBook 650 G1              | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| HP            | ProBook 6560b               | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fc99c10d57](https://linux-hardware.org/?probe=fc99c10d57) | Jul 13, 2022 |
| Dell          | Latitude E6410              | [cde668d556](https://linux-hardware.org/?probe=cde668d556) | Jul 12, 2022 |
| Dell          | Latitude E6410              | [a15b38ef5e](https://linux-hardware.org/?probe=a15b38ef5e) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Acer          | Aspire F5-573G              | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| Dell          | Inspiron 5323               | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | EliteBook 8470p             | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| HP            | ProBook 470 G0              | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Dell          | G3 3590                     | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| eMachines     | eME728                      | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| Dell          | Latitude E7470              | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| HP            | EliteBook 8560p             | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| Dell          | System Inspiron N7110       | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| HP            | EliteBook 8460p             | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| Dell          | G3 3590                     | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| Acer          | AO756                       | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| Acer          | Aspire 7741                 | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| Unknown       | Unknown                     | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ASUSTek       | X75VBP                      | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Lenovo        | G505 20240                  | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| HP            | ENVY TS 15                  | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| HP            | EliteBook 8470p             | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| HP            | Compaq CQ58                 | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| HP            | 255 G2                      | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Acer          | Aspire 9300                 | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| ASUSTek       | X751MD                      | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| Dell          | Inspiron 3521               | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Sony          | VGN-BX41VN                  | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 13        | 17.33%  |
| Pop!_OS 21.04          | 6         | 8%      |
| Ubuntu 22.04           | 4         | 5.33%   |
| Ubuntu 18.04           | 4         | 5.33%   |
| Linux Mint 20.2        | 4         | 5.33%   |
| Zorin 16               | 3         | 4%      |
| Manjaro                | 3         | 4%      |
| Ubuntu 20.10           | 2         | 2.67%   |
| Ubuntu 19.04           | 2         | 2.67%   |
| Pop!_OS 20.04          | 2         | 2.67%   |
| OpenMandriva 4.3       | 2         | 2.67%   |
| Lubuntu 19.10          | 2         | 2.67%   |
| Linux Mint 19.3        | 2         | 2.67%   |
| ArcoLinux Rolling      | 2         | 2.67%   |
| Zorin 15               | 1         | 1.33%   |
| Xubuntu 20.04          | 1         | 1.33%   |
| Xubuntu 18.04          | 1         | 1.33%   |
| Ubuntu 21.10           | 1         | 1.33%   |
| Ubuntu 21.04           | 1         | 1.33%   |
| Ubuntu 16.04           | 1         | 1.33%   |
| ROSA R10               | 1         | 1.33%   |
| PureOS 9.0             | 1         | 1.33%   |
| Pop!_OS 21.10          | 1         | 1.33%   |
| Pop!_OS 20.10          | 1         | 1.33%   |
| Manjaro 21.2.5         | 1         | 1.33%   |
| Manjaro 21.0.7         | 1         | 1.33%   |
| Linux Mint 20          | 1         | 1.33%   |
| Kubuntu 22.04          | 1         | 1.33%   |
| KDE neon 20.04         | 1         | 1.33%   |
| Fedora 36              | 1         | 1.33%   |
| Fedora 32              | 1         | 1.33%   |
| Endless 3.7.8          | 1         | 1.33%   |
| Endless 3.5.1          | 1         | 1.33%   |
| Endless 3.3.19-nexthw1 | 1         | 1.33%   |
| Debian Testing         | 1         | 1.33%   |
| Debian 10              | 1         | 1.33%   |
| Arch Rolling           | 1         | 1.33%   |
| Arch                   | 1         | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 27        | 36.99%  |
| Pop!_OS      | 10        | 13.7%   |
| Linux Mint   | 6         | 8.22%   |
| Manjaro      | 5         | 6.85%   |
| Zorin        | 4         | 5.48%   |
| Endless      | 3         | 4.11%   |
| Xubuntu      | 2         | 2.74%   |
| OpenMandriva | 2         | 2.74%   |
| Lubuntu      | 2         | 2.74%   |
| Fedora       | 2         | 2.74%   |
| Debian       | 2         | 2.74%   |
| ArcoLinux    | 2         | 2.74%   |
| Arch         | 2         | 2.74%   |
| ROSA         | 1         | 1.37%   |
| PureOS       | 1         | 1.37%   |
| Kubuntu      | 1         | 1.37%   |
| KDE neon     | 1         | 1.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 3         | 4%      |
| 5.3.0-28-generic         | 3         | 4%      |
| 5.4.0-89-generic         | 2         | 2.67%   |
| 5.4.0-52-generic         | 2         | 2.67%   |
| 5.16.7-desktop-1omv4003  | 2         | 2.67%   |
| 5.15.0-48-generic        | 2         | 2.67%   |
| 5.15.0-39-generic        | 2         | 2.67%   |
| 5.13.0-7620-generic      | 2         | 2.67%   |
| 5.13.0-7614-generic      | 2         | 2.67%   |
| 5.13.0-39-generic        | 2         | 2.67%   |
| 5.11.0-40-generic        | 2         | 2.67%   |
| 5.9.0-3-amd64            | 1         | 1.33%   |
| 5.8.9-200.fc32.x86_64    | 1         | 1.33%   |
| 5.8.0-7630-generic       | 1         | 1.33%   |
| 5.8.0-53-generic         | 1         | 1.33%   |
| 5.8.0-49-generic         | 1         | 1.33%   |
| 5.8.0-44-generic         | 1         | 1.33%   |
| 5.8.0-34-generic         | 1         | 1.33%   |
| 5.8.0-26-generic         | 1         | 1.33%   |
| 5.7.0-1-librem5          | 1         | 1.33%   |
| 5.4.52-1-MANJARO         | 1         | 1.33%   |
| 5.4.33-3-MANJARO         | 1         | 1.33%   |
| 5.4.23-1-MANJARO         | 1         | 1.33%   |
| 5.4.0-90-generic         | 1         | 1.33%   |
| 5.4.0-80-generic         | 1         | 1.33%   |
| 5.4.0-7625-generic       | 1         | 1.33%   |
| 5.4.0-72-generic         | 1         | 1.33%   |
| 5.4.0-67-generic         | 1         | 1.33%   |
| 5.4.0-58-generic         | 1         | 1.33%   |
| 5.4.0-54-generic         | 1         | 1.33%   |
| 5.4.0-48-generic         | 1         | 1.33%   |
| 5.4.0-33-generic         | 1         | 1.33%   |
| 5.4.0-26-generic         | 1         | 1.33%   |
| 5.3.0-51-generic         | 1         | 1.33%   |
| 5.19.8-200.fc36.x86_64   | 1         | 1.33%   |
| 5.16.14-1-MANJARO        | 1         | 1.33%   |
| 5.16.11-arch1-1          | 1         | 1.33%   |
| 5.15.23-76051523-generic | 1         | 1.33%   |
| 5.15.11-76051511-generic | 1         | 1.33%   |
| 5.15.0-25-generic        | 1         | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 14        | 18.67%  |
| 5.13.0  | 10        | 13.33%  |
| 5.3.0   | 7         | 9.33%   |
| 5.8.0   | 6         | 8%      |
| 5.11.0  | 6         | 8%      |
| 5.15.0  | 5         | 6.67%   |
| 4.15.0  | 4         | 5.33%   |
| 5.0.0   | 3         | 4%      |
| 5.16.7  | 2         | 2.67%   |
| 5.9.0   | 1         | 1.33%   |
| 5.8.9   | 1         | 1.33%   |
| 5.7.0   | 1         | 1.33%   |
| 5.4.52  | 1         | 1.33%   |
| 5.4.33  | 1         | 1.33%   |
| 5.4.23  | 1         | 1.33%   |
| 5.19.8  | 1         | 1.33%   |
| 5.16.14 | 1         | 1.33%   |
| 5.16.11 | 1         | 1.33%   |
| 5.15.23 | 1         | 1.33%   |
| 5.15.11 | 1         | 1.33%   |
| 5.13.9  | 1         | 1.33%   |
| 5.11.18 | 1         | 1.33%   |
| 5.10.42 | 1         | 1.33%   |
| 5.10.37 | 1         | 1.33%   |
| 5.10.0  | 1         | 1.33%   |
| 4.9.60  | 1         | 1.33%   |
| 4.18.0  | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 17        | 22.67%  |
| 5.13    | 11        | 14.67%  |
| 5.8     | 7         | 9.33%   |
| 5.3     | 7         | 9.33%   |
| 5.15    | 7         | 9.33%   |
| 5.11    | 7         | 9.33%   |
| 5.16    | 4         | 5.33%   |
| 4.15    | 4         | 5.33%   |
| 5.10    | 3         | 4%      |
| 5.0     | 3         | 4%      |
| 5.9     | 1         | 1.33%   |
| 5.7     | 1         | 1.33%   |
| 5.19    | 1         | 1.33%   |
| 4.9     | 1         | 1.33%   |
| 4.18    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 68        | 94.44%  |
| i686    | 3         | 4.17%   |
| aarch64 | 1         | 1.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 43        | 58.9%   |
| XFCE       | 9         | 12.33%  |
| KDE5       | 7         | 9.59%   |
| Unknown    | 6         | 8.22%   |
| X-Cinnamon | 2         | 2.74%   |
| LXQt       | 2         | 2.74%   |
| MATE       | 1         | 1.37%   |
| KDE4       | 1         | 1.37%   |
| KDE        | 1         | 1.37%   |
| bspwm      | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 57        | 78.08%  |
| Wayland | 11        | 15.07%  |
| Unknown | 5         | 6.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 46        | 61.33%  |
| SDDM    | 9         | 12%     |
| GDM     | 8         | 10.67%  |
| GDM3    | 6         | 8%      |
| LightDM | 5         | 6.67%   |
| KDM     | 1         | 1.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 55        | 75.34%  |
| Unknown | 6         | 8.22%   |
| hr_HR   | 4         | 5.48%   |
| bs_BA   | 3         | 4.11%   |
| C       | 2         | 2.74%   |
| en_GB   | 1         | 1.37%   |
| en_AU   | 1         | 1.37%   |
| de_CH   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 48        | 65.75%  |
| EFI  | 25        | 34.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 86.11%  |
| Btrfs   | 4         | 5.56%   |
| Overlay | 3         | 4.17%   |
| Unknown | 3         | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 71.62%  |
| GPT     | 15        | 20.27%  |
| MBR     | 6         | 8.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 94.44%  |
| Yes       | 4         | 5.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 80.56%  |
| Yes       | 14        | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 22        | 30.56%  |
| Lenovo           | 13        | 18.06%  |
| ASUSTek Computer | 11        | 15.28%  |
| Acer             | 10        | 13.89%  |
| Dell             | 9         | 12.5%   |
| Toshiba          | 1         | 1.39%   |
| Sony             | 1         | 1.39%   |
| NEC Computers    | 1         | 1.39%   |
| HUAWEI           | 1         | 1.39%   |
| Fujitsu Siemens  | 1         | 1.39%   |
| eMachines        | 1         | 1.39%   |
| Unknown          | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 8460p                     | 2         | 2.78%   |
| Dell G3 3590                           | 2         | 2.78%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA | 2         | 2.78%   |
| Toshiba Satellite C850-1GF             | 1         | 1.39%   |
| Sony VGN-BX41VN                        | 1         | 1.39%   |
| NEC Computers VERSAP550 NN951700753    | 1         | 1.39%   |
| Lenovo ThinkPad X301 277418G           | 1         | 1.39%   |
| Lenovo ThinkPad T430 2349G2G           | 1         | 1.39%   |
| Lenovo ThinkPad T420 4180WAP           | 1         | 1.39%   |
| Lenovo ThinkPad T14s Gen 1 20UH0056SC  | 1         | 1.39%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ     | 1         | 1.39%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC   | 1         | 1.39%   |
| Lenovo Legion 7 15IMHg05 81YU          | 1         | 1.39%   |
| Lenovo IdeaPad Y570 20091              | 1         | 1.39%   |
| Lenovo IdeaPad L340-15IWL 81LG         | 1         | 1.39%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1.39%   |
| Lenovo IdeaPad 320-15IKB 81BG          | 1         | 1.39%   |
| Lenovo IdeaPad 110S-11IBR 80WG         | 1         | 1.39%   |
| Lenovo G505 20240                      | 1         | 1.39%   |
| HUAWEI BOHK-WAX9X                      | 1         | 1.39%   |
| HP ProBook 6560b                       | 1         | 1.39%   |
| HP ProBook 650 G1                      | 1         | 1.39%   |
| HP ProBook 4710s                       | 1         | 1.39%   |
| HP ProBook 470 G2                      | 1         | 1.39%   |
| HP ProBook 470 G0                      | 1         | 1.39%   |
| HP Pavilion Gaming Laptop 15-dk2xxx    | 1         | 1.39%   |
| HP Laptop 15-rb0xx                     | 1         | 1.39%   |
| HP ENVY TS 15                          | 1         | 1.39%   |
| HP ENVY 6                              | 1         | 1.39%   |
| HP EliteBook 8560p                     | 1         | 1.39%   |
| HP EliteBook 850 G8 Notebook PC        | 1         | 1.39%   |
| HP EliteBook 850 G3                    | 1         | 1.39%   |
| HP EliteBook 8470p                     | 1         | 1.39%   |
| HP EliteBook 840 G1                    | 1         | 1.39%   |
| HP EliteBook 2560p                     | 1         | 1.39%   |
| HP Compaq CQ58                         | 1         | 1.39%   |
| HP 550                                 | 1         | 1.39%   |
| HP 255 G2                              | 1         | 1.39%   |
| HP 250 G7 Notebook PC                  | 1         | 1.39%   |
| HP 250 G6 Notebook PC                  | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 8         | 11.11%  |
| Acer Aspire             | 7         | 9.72%   |
| Lenovo ThinkPad         | 6         | 8.33%   |
| Lenovo IdeaPad          | 5         | 6.94%   |
| HP ProBook              | 5         | 6.94%   |
| ASUS VivoBook           | 4         | 5.56%   |
| HP ENVY                 | 2         | 2.78%   |
| HP 250                  | 2         | 2.78%   |
| Dell XPS                | 2         | 2.78%   |
| Dell Latitude           | 2         | 2.78%   |
| Dell Inspiron           | 2         | 2.78%   |
| Dell G3                 | 2         | 2.78%   |
| Toshiba Satellite       | 1         | 1.39%   |
| Sony VGN-BX41VN         | 1         | 1.39%   |
| NEC Computers VERSAP550 | 1         | 1.39%   |
| Lenovo Legion           | 1         | 1.39%   |
| Lenovo G505             | 1         | 1.39%   |
| HUAWEI BOHK-WAX9X       | 1         | 1.39%   |
| HP Pavilion             | 1         | 1.39%   |
| HP Laptop               | 1         | 1.39%   |
| HP Compaq               | 1         | 1.39%   |
| HP 550                  | 1         | 1.39%   |
| HP 255                  | 1         | 1.39%   |
| Fujitsu Siemens AMILO   | 1         | 1.39%   |
| eMachines eME728        | 1         | 1.39%   |
| Dell System             | 1         | 1.39%   |
| ASUS ZenBook            | 1         | 1.39%   |
| ASUS X75VBP             | 1         | 1.39%   |
| ASUS X751MD             | 1         | 1.39%   |
| ASUS X550ZE             | 1         | 1.39%   |
| ASUS X540SAA            | 1         | 1.39%   |
| ASUS TUF                | 1         | 1.39%   |
| ASUS ROG                | 1         | 1.39%   |
| Acer Switch             | 1         | 1.39%   |
| Acer AO756              | 1         | 1.39%   |
| Acer AO725              | 1         | 1.39%   |
| Unknown                 | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 11        | 15.28%  |
| 2012    | 8         | 11.11%  |
| 2019    | 7         | 9.72%   |
| 2013    | 7         | 9.72%   |
| 2016    | 6         | 8.33%   |
| 2020    | 5         | 6.94%   |
| 2018    | 5         | 6.94%   |
| 2017    | 4         | 5.56%   |
| 2014    | 4         | 5.56%   |
| 2010    | 3         | 4.17%   |
| 2021    | 2         | 2.78%   |
| 2009    | 2         | 2.78%   |
| 2007    | 2         | 2.78%   |
| 2022    | 1         | 1.39%   |
| 2015    | 1         | 1.39%   |
| 2008    | 1         | 1.39%   |
| 2006    | 1         | 1.39%   |
| 2005    | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

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
| Disabled | 70        | 97.22%  |
| Enabled  | 2         | 2.78%   |

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


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 31.94%  |
| 3.01-4.0    | 16        | 22.22%  |
| 16.01-24.0  | 10        | 13.89%  |
| 1.01-2.0    | 9         | 12.5%   |
| 8.01-16.0   | 9         | 12.5%   |
| 2.01-3.0    | 2         | 2.78%   |
| 32.01-64.0  | 1         | 1.39%   |
| 64.01-256.0 | 1         | 1.39%   |
| 0.51-1.0    | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 28        | 37.84%  |
| 2.01-3.0  | 21        | 28.38%  |
| 3.01-4.0  | 8         | 10.81%  |
| 0.51-1.0  | 8         | 10.81%  |
| 4.01-8.0  | 6         | 8.11%   |
| 8.01-16.0 | 2         | 2.7%    |
| 0.01-0.5  | 1         | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 79.17%  |
| 2      | 15        | 20.83%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 54.17%  |
| Yes       | 33        | 45.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 80.82%  |
| No        | 14        | 19.18%  |

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
| Yes       | 54        | 73.97%  |
| No        | 19        | 26.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 72        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 26        | 35.14%  |
| Banja Luka        | 14        | 18.92%  |
| Tuzla             | 5         | 6.76%   |
| Gracanica         | 3         | 4.05%   |
| Srebrenik         | 2         | 2.7%    |
| Maglaj            | 2         | 2.7%    |
| Zivinice          | 1         | 1.35%   |
| Zepce             | 1         | 1.35%   |
| Zenica            | 1         | 1.35%   |
| Velika KladuÅ¡a | 1         | 1.35%   |
| Trebinje          | 1         | 1.35%   |
| Teslic            | 1         | 1.35%   |
| Stjepan-Polje     | 1         | 1.35%   |
| Solina            | 1         | 1.35%   |
| Prijedor          | 1         | 1.35%   |
| Posusje           | 1         | 1.35%   |
| Pale              | 1         | 1.35%   |
| Orahovica Donja   | 1         | 1.35%   |
| Novi Travnik      | 1         | 1.35%   |
| Nevesinje         | 1         | 1.35%   |
| Mostar            | 1         | 1.35%   |
| Lukavac           | 1         | 1.35%   |
| Ljubuski          | 1         | 1.35%   |
| Ilidza            | 1         | 1.35%   |
| Grude             | 1         | 1.35%   |
| Doboj             | 1         | 1.35%   |
| Brcko             | 1         | 1.35%   |
| Banovici          | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 11        | 11     | 12.94%  |
| Kingston            | 11        | 11     | 12.94%  |
| SanDisk             | 9         | 11     | 10.59%  |
| Samsung Electronics | 9         | 10     | 10.59%  |
| Hitachi             | 8         | 8      | 9.41%   |
| SK hynix            | 7         | 8      | 8.24%   |
| WDC                 | 6         | 7      | 7.06%   |
| Seagate             | 6         | 9      | 7.06%   |
| Unknown             | 3         | 3      | 3.53%   |
| Intel               | 3         | 3      | 3.53%   |
| A-DATA Technology   | 2         | 2      | 2.35%   |
| Vaseky              | 1         | 1      | 1.18%   |
| Team                | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 2      | 1.18%   |
| Micron Technology   | 1         | 1      | 1.18%   |
| KIOXIA              | 1         | 1      | 1.18%   |
| Intenso             | 1         | 1      | 1.18%   |
| HGST                | 1         | 1      | 1.18%   |
| GOODRAM             | 1         | 1      | 1.18%   |
| Crucial             | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                 | 5         | 5.81%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 3.49%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 3.49%   |
| Unknown MMC Card  32GB                 | 2         | 2.33%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 2.33%   |
| Kingston SHFS37A240G 240GB SSD         | 2         | 2.33%   |
| Kingston SHFS37A120G 120GB SSD         | 2         | 2.33%   |
| WDC WDS240G1G0A-00SS50 240GB SSD       | 1         | 1.16%   |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 1.16%   |
| WDC WD7500BPVT-24HXZT3 752GB           | 1         | 1.16%   |
| WDC WD5000LPVT-75G33T0 500GB           | 1         | 1.16%   |
| WDC WD5000BEKT-22KA9T0 500GB           | 1         | 1.16%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 1         | 1.16%   |
| Vaseky V800/128G 128GB                 | 1         | 1.16%   |
| Unknown SD/MMC/MS PRO 2GB              | 1         | 1.16%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 1.16%   |
| Toshiba MQ01ABF050 500GB               | 1         | 1.16%   |
| Toshiba MK3263GSX 320GB                | 1         | 1.16%   |
| Toshiba MK3261GSYN 320GB               | 1         | 1.16%   |
| Toshiba MK3259GSXP 320GB               | 1         | 1.16%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 1.16%   |
| Team T253X1120G 120GB SSD              | 1         | 1.16%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 1         | 1.16%   |
| SK hynix SC300 M.2 2280 256GB SSD      | 1         | 1.16%   |
| SK hynix PC801 NVMe 1TB                | 1         | 1.16%   |
| SK hynix HFM001TD3JX013N 1024GB        | 1         | 1.16%   |
| SK hynix BC501 NVMe 512GB              | 1         | 1.16%   |
| Seagate ST9120817AS 120GB              | 1         | 1.16%   |
| Seagate ST500LT012-9WS142 500GB        | 1         | 1.16%   |
| Seagate ST500LM000-1EJ162 500GB        | 1         | 1.16%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1.16%   |
| SanDisk SSD PLUS 120GB                 | 1         | 1.16%   |
| SanDisk SD9SB8W256G1002 256GB SSD      | 1         | 1.16%   |
| SanDisk SD8SBAT128G1002 128GB SSD      | 1         | 1.16%   |
| SanDisk SD7TB3Q-128G-1006 128GB SSD    | 1         | 1.16%   |
| SanDisk NVMe SSD Drive 512GB           | 1         | 1.16%   |
| SanDisk NVMe SSD Drive 1024GB          | 1         | 1.16%   |
| SanDisk DF4032  32GB                   | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 10        | 10     | 32.26%  |
| Hitachi | 8         | 8      | 25.81%  |
| Seagate | 6         | 9      | 19.35%  |
| WDC     | 5         | 6      | 16.13%  |
| Unknown | 1         | 1      | 3.23%   |
| HGST    | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 10     | 30.3%   |
| Samsung Electronics | 6         | 6      | 18.18%  |
| SanDisk             | 4         | 5      | 12.12%  |
| Intel               | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| Vaseky              | 1         | 1      | 3.03%   |
| Team                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 2      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| GOODRAM             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 32        | 35     | 38.1%   |
| HDD  | 31        | 35     | 36.9%   |
| NVMe | 18        | 21     | 21.43%  |
| MMC  | 3         | 3      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 69     | 70.67%  |
| NVMe | 18        | 21     | 24%     |
| MMC  | 3         | 3      | 4%      |
| SAS  | 1         | 1      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 57     | 80%     |
| 0.51-1.0   | 11        | 11     | 18.33%  |
| 1.01-2.0   | 1         | 2      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 38.36%  |
| 251-500        | 20        | 27.4%   |
| 21-50          | 8         | 10.96%  |
| 501-1000       | 7         | 9.59%   |
| 51-100         | 5         | 6.85%   |
| 1-20           | 2         | 2.74%   |
| More than 3000 | 1         | 1.37%   |
| 2001-3000      | 1         | 1.37%   |
| Unknown        | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 30        | 38.96%  |
| 21-50    | 25        | 32.47%  |
| 51-100   | 13        | 16.88%  |
| 101-250  | 4         | 5.19%   |
| 501-1000 | 3         | 3.9%    |
| 251-500  | 1         | 1.3%    |
| Unknown  | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD | 1         | 1      | 50%     |
| Crucial CT500P1SSD8 500GB                     | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Crucial             | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| SSD  | 1         | 1      | 50%     |

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
| Detected | 54        | 72     | 72.97%  |
| Works    | 18        | 20     | 24.32%  |
| Malfunc  | 2         | 2      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 66.67%  |
| AMD                          | 8         | 9.88%   |
| SK hynix                     | 6         | 7.41%   |
| SanDisk                      | 4         | 4.94%   |
| Samsung Electronics          | 3         | 3.7%    |
| Toshiba America Info Systems | 1         | 1.23%   |
| Nvidia                       | 1         | 1.23%   |
| Micron/Crucial Technology    | 1         | 1.23%   |
| KIOXIA                       | 1         | 1.23%   |
| Kingston Technology Company  | 1         | 1.23%   |
| JMicron Technology           | 1         | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 11.63%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 9.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 9.3%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 4.65%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 3.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 3.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 3.49%   |
| SK hynix Gold P31 SSD                                                            | 2         | 2.33%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 2.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.16%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 1.16%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 1.16%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.16%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 1.16%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 1.16%   |
| Nvidia MCP51 IDE                                                                 | 1         | 1.16%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 1.16%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.16%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 1.16%   |
| JMicron JMB363 SATA/IDE Controller                                               | 1         | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.16%   |
| Intel SSD 600P Series                                                            | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.16%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 54        | 64.29%  |
| NVMe | 18        | 21.43%  |
| RAID | 6         | 7.14%   |
| IDE  | 6         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 80.56%  |
| AMD    | 13        | 18.06%  |
| ARM    | 1         | 1.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 4.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 2.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 2.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 2.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.78%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.78%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 2.78%   |
| Intel Pentium M processor 1.73GHz             | 1         | 1.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.39%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 1.39%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.39%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.39%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.39%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 1.39%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.39%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.39%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.39%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.39%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.39%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.39%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.39%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.39%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.39%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.39%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.39%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.39%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 1         | 1.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 25%     |
| Intel Core i5           | 16        | 22.22%  |
| Intel Celeron           | 6         | 8.33%   |
| Other                   | 5         | 6.94%   |
| Intel Core i3           | 5         | 6.94%   |
| Intel Core 2 Duo        | 4         | 5.56%   |
| AMD Ryzen 5             | 3         | 4.17%   |
| AMD E1                  | 3         | 4.17%   |
| Intel Pentium M         | 1         | 1.39%   |
| Intel Pentium Dual-Core | 1         | 1.39%   |
| Intel Pentium Dual      | 1         | 1.39%   |
| Intel Pentium           | 1         | 1.39%   |
| Intel Atom              | 1         | 1.39%   |
| AMD Turion 64 Mobile    | 1         | 1.39%   |
| AMD Ryzen 9             | 1         | 1.39%   |
| AMD Ryzen 7             | 1         | 1.39%   |
| AMD Ryzen 5 PRO         | 1         | 1.39%   |
| AMD E2                  | 1         | 1.39%   |
| AMD C-60                | 1         | 1.39%   |
| AMD A10                 | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 55.56%  |
| 4      | 23        | 31.94%  |
| 6      | 4         | 5.56%   |
| 8      | 2         | 2.78%   |
| 1      | 2         | 2.78%   |
| 14     | 1         | 1.39%   |

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
| 2      | 50        | 69.44%  |
| 1      | 22        | 30.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 94.44%  |
| Unknown        | 3         | 4.17%   |
| 32-bit         | 1         | 1.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 28.77%  |
| 0x206a7    | 8         | 10.96%  |
| 0x306a9    | 7         | 9.59%   |
| 0x406e3    | 3         | 4.11%   |
| 0x806ea    | 2         | 2.74%   |
| 0x806c1    | 2         | 2.74%   |
| 0x40651    | 2         | 2.74%   |
| 0x306c3    | 2         | 2.74%   |
| 0x10676    | 2         | 2.74%   |
| 0x05000119 | 2         | 2.74%   |
| 0xa0652    | 1         | 1.37%   |
| 0x906ea    | 1         | 1.37%   |
| 0x906a3    | 1         | 1.37%   |
| 0x806ec    | 1         | 1.37%   |
| 0x806eb    | 1         | 1.37%   |
| 0x806e9    | 1         | 1.37%   |
| 0x706e5    | 1         | 1.37%   |
| 0x6fd      | 1         | 1.37%   |
| 0x6fa      | 1         | 1.37%   |
| 0x6d8      | 1         | 1.37%   |
| 0x506c9    | 1         | 1.37%   |
| 0x406c4    | 1         | 1.37%   |
| 0x406c3    | 1         | 1.37%   |
| 0x30678    | 1         | 1.37%   |
| 0x20655    | 1         | 1.37%   |
| 0x106e5    | 1         | 1.37%   |
| 0x1067a    | 1         | 1.37%   |
| 0x0a50000c | 1         | 1.37%   |
| 0x08600106 | 1         | 1.37%   |
| 0x08108109 | 1         | 1.37%   |
| 0x08108102 | 1         | 1.37%   |
| 0x0700010f | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 11        | 15.28%  |
| KabyLake         | 11        | 15.28%  |
| IvyBridge        | 8         | 11.11%  |
| Haswell          | 5         | 6.94%   |
| Zen+             | 4         | 5.56%   |
| Silvermont       | 4         | 5.56%   |
| TigerLake        | 3         | 4.17%   |
| Skylake          | 3         | 4.17%   |
| Penryn           | 3         | 4.17%   |
| Core             | 3         | 4.17%   |
| Jaguar           | 2         | 2.78%   |
| Bobcat           | 2         | 2.78%   |
| Zen 3            | 1         | 1.39%   |
| Zen 2            | 1         | 1.39%   |
| Westmere         | 1         | 1.39%   |
| Steamroller      | 1         | 1.39%   |
| P6               | 1         | 1.39%   |
| Nehalem          | 1         | 1.39%   |
| K8 Hammer        | 1         | 1.39%   |
| IceLake          | 1         | 1.39%   |
| Goldmont         | 1         | 1.39%   |
| Excavator        | 1         | 1.39%   |
| CometLake        | 1         | 1.39%   |
| Alderlake Hybrid | 1         | 1.39%   |
| Unknown          | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 52.17%  |
| AMD    | 24        | 26.09%  |
| Nvidia | 20        | 21.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 8.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 7.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.16%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 3.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 3.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.11%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.11%   |
| Intel HD Graphics 620                                                                    | 2         | 2.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.11%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 2.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.11%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 2.11%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 1.05%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.05%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.05%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.05%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.05%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.05%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.05%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 1.05%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.05%   |
| Intel HD Graphics 500                                                                    | 1         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 38.89%  |
| 1 x AMD        | 17        | 23.61%  |
| Intel + Nvidia | 16        | 22.22%  |
| Intel + AMD    | 4         | 5.56%   |
| 1 x Nvidia     | 3         | 4.17%   |
| 2 x AMD        | 2         | 2.78%   |
| Other          | 1         | 1.39%   |
| AMD + Nvidia   | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 80.56%  |
| Proprietary | 11        | 15.28%  |
| Unknown     | 3         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 55.41%  |
| 1.01-2.0   | 11        | 14.86%  |
| 0.01-0.5   | 9         | 12.16%  |
| 0.51-1.0   | 7         | 9.46%   |
| 3.01-4.0   | 3         | 4.05%   |
| 5.01-6.0   | 2         | 2.7%    |
| 7.01-8.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 23.29%  |
| AU Optronics            | 17        | 23.29%  |
| Chimei Innolux          | 9         | 12.33%  |
| BOE                     | 8         | 10.96%  |
| Samsung Electronics     | 6         | 8.22%   |
| Sharp                   | 2         | 2.74%   |
| LG Philips              | 2         | 2.74%   |
| Chi Mei Optoelectronics | 2         | 2.74%   |
| AOC                     | 2         | 2.74%   |
| Philips                 | 1         | 1.37%   |
| PANDA                   | 1         | 1.37%   |
| NEC Computers           | 1         | 1.37%   |
| Mi                      | 1         | 1.37%   |
| Lenovo                  | 1         | 1.37%   |
| InfoVision              | 1         | 1.37%   |
| Goldstar                | 1         | 1.37%   |
| Dell                    | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 5.33%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 3         | 4%      |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch              | 2         | 2.67%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch               | 2         | 2.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 2.67%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 2         | 2.67%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 1.33%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.33%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                          | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch      | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch      | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch      | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch      | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 1         | 1.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 1.33%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                   | 1         | 1.33%   |
| NEC Computers LCD1770NX NEC6664 1280x1024 338x270mm 17.0-inch             | 1         | 1.33%   |
| Mi Monitor XMI3446 3440x1440 797x334mm 34.0-inch                          | 1         | 1.33%   |
| Mi Monitor XMI3445 3440x1440 797x334mm 34.0-inch                          | 1         | 1.33%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 1         | 1.33%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 1         | 1.33%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch              | 1         | 1.33%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch              | 1         | 1.33%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 1.33%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch               | 1         | 1.33%   |
| Lenovo LCD Monitor LEN4074 1440x900 287x180mm 13.3-inch                   | 1         | 1.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 1         | 1.33%   |
| Goldstar ULTRAGEAR GSM5BB1 1920x1080 527x296mm 23.8-inch                  | 1         | 1.33%   |
| Dell 1704FPT DEL4004 1280x1024 340x270mm 17.1-inch                        | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch          | 1         | 1.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 1.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch  | 1         | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 31        | 43.66%  |
| 1366x768 (WXGA)  | 20        | 28.17%  |
| 1600x900 (HD+)   | 11        | 15.49%  |
| 1440x900 (WXGA+) | 3         | 4.23%   |
| 1280x800 (WXGA)  | 2         | 2.82%   |
| 1280x1024 (SXGA) | 2         | 2.82%   |
| 3440x1440        | 1         | 1.41%   |
| 2560x1440 (QHD)  | 1         | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 38        | 52.05%  |
| 17      | 10        | 13.7%   |
| 14      | 8         | 10.96%  |
| 13      | 6         | 8.22%   |
| 11      | 3         | 4.11%   |
| 34      | 1         | 1.37%   |
| 33      | 1         | 1.37%   |
| 24      | 1         | 1.37%   |
| 23      | 1         | 1.37%   |
| 21      | 1         | 1.37%   |
| 18      | 1         | 1.37%   |
| 12      | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 69.44%  |
| 351-400     | 8         | 11.11%  |
| 201-300     | 7         | 9.72%   |
| 701-800     | 2         | 2.78%   |
| 501-600     | 2         | 2.78%   |
| 401-500     | 2         | 2.78%   |
| Unknown     | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 60        | 88.24%  |
| 16/10 | 5         | 7.35%   |
| 5/4   | 2         | 2.94%   |
| 21/9  | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 51.39%  |
| 81-90          | 11        | 15.28%  |
| 121-130        | 6         | 8.33%   |
| 71-80          | 3         | 4.17%   |
| 51-60          | 3         | 4.17%   |
| 351-500        | 2         | 2.78%   |
| 201-250        | 2         | 2.78%   |
| 141-150        | 2         | 2.78%   |
| 131-140        | 2         | 2.78%   |
| 61-70          | 1         | 1.39%   |
| 151-200        | 1         | 1.39%   |
| 91-100         | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 36        | 50%     |
| 101-120 | 25        | 34.72%  |
| 51-100  | 9         | 12.5%   |
| 161-240 | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 62        | 86.11%  |
| 2     | 6         | 8.33%   |
| 0     | 3         | 4.17%   |
| 3     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 35        | 31.82%  |
| Intel                           | 28        | 25.45%  |
| Qualcomm Atheros                | 23        | 20.91%  |
| Broadcom                        | 9         | 8.18%   |
| Ralink                          | 3         | 2.73%   |
| Ralink Technology               | 2         | 1.82%   |
| Marvell Technology Group        | 2         | 1.82%   |
| TP-Link                         | 1         | 0.91%   |
| Qualcomm Atheros Communications | 1         | 0.91%   |
| Nvidia                          | 1         | 0.91%   |
| MediaTek                        | 1         | 0.91%   |
| HTC (High Tech Computer)        | 1         | 0.91%   |
| Hewlett-Packard                 | 1         | 0.91%   |
| D-Link                          | 1         | 0.91%   |
| Broadcom Limited                | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 22        | 16.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 5.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 5.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 4.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.46%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.46%   |
| Intel Wireless 8260                                                     | 2         | 1.46%   |
| Intel Wireless 7260                                                     | 2         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.46%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 1.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.46%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.73%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.73%   |
| Realtek Realtek Network controller                                      | 1         | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.73%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.73%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                 | 1         | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.73%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 33.78%  |
| Qualcomm Atheros                | 21        | 28.38%  |
| Realtek Semiconductor           | 11        | 14.86%  |
| Broadcom                        | 8         | 10.81%  |
| Ralink                          | 3         | 4.05%   |
| Ralink Technology               | 2         | 2.7%    |
| TP-Link                         | 1         | 1.35%   |
| Qualcomm Atheros Communications | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| D-Link                          | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 9.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 8.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 8.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 5.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 4.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 4.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 4.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 4.05%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.7%    |
| Intel Wireless 8260                                                     | 2         | 2.7%    |
| Intel Wireless 7260                                                     | 2         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.35%   |
| Realtek Realtek Network controller                                      | 1         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.35%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.35%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.35%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.35%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.35%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.35%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.35%   |
| D-Link GO-USB-N150 N Adapter                                            | 1         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.35%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 55.93%  |
| Intel                    | 15        | 25.42%  |
| Qualcomm Atheros         | 5         | 8.47%   |
| Marvell Technology Group | 2         | 3.39%   |
| Broadcom                 | 2         | 3.39%   |
| Nvidia                   | 1         | 1.69%   |
| Broadcom Limited         | 1         | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 36.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.33%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.67%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 1.67%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.67%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.67%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 52.67%  |
| Ethernet | 59        | 45.04%  |
| Modem    | 3         | 2.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 81.08%  |
| Ethernet | 13        | 17.57%  |
| Modem    | 1         | 1.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 77.78%  |
| 1     | 14        | 19.44%  |
| 0     | 2         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 69        | 95.83%  |
| Yes  | 3         | 4.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 22.22%  |
| Qualcomm Atheros Communications | 9         | 16.67%  |
| IMC Networks                    | 7         | 12.96%  |
| Realtek Semiconductor           | 5         | 9.26%   |
| Broadcom                        | 5         | 9.26%   |
| Lite-On Technology              | 4         | 7.41%   |
| Ralink                          | 3         | 5.56%   |
| Hewlett-Packard                 | 2         | 3.7%    |
| Foxconn / Hon Hai               | 2         | 3.7%    |
| Toshiba                         | 1         | 1.85%   |
| Realtek                         | 1         | 1.85%   |
| Dell                            | 1         | 1.85%   |
| Cambridge Silicon Radio         | 1         | 1.85%   |
| Alps Electric                   | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 5         | 9.26%   |
| Intel Bluetooth wireless interface                  | 4         | 7.41%   |
| IMC Networks Bluetooth Radio                        | 4         | 7.41%   |
| Realtek Bluetooth Radio                             | 3         | 5.56%   |
| Ralink RT3290 Bluetooth                             | 3         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 5.56%   |
| Intel AX201 Bluetooth                               | 3         | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 3.7%    |
| IMC Networks Bluetooth Device                       | 2         | 3.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.7%    |
| Toshiba RT Bluetooth Radio                          | 1         | 1.85%   |
| Realtek Bluetooth Radio                             | 1         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.85%   |
| Intel Bluetooth Device                              | 1         | 1.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.85%   |
| Intel AX200 Bluetooth                               | 1         | 1.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.85%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.85%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.85%   |
| Broadcom HP Portable Valentine                      | 1         | 1.85%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.85%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.85%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 57        | 66.28%  |
| AMD               | 18        | 20.93%  |
| Nvidia            | 8         | 9.3%    |
| Logitech          | 2         | 2.33%   |
| Texas Instruments | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 9.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 7.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.83%   |
| AMD FCH Azalia Controller                                                                         | 5         | 4.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.91%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.94%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.94%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.94%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.97%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.97%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.97%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.97%   |
| Logitech 960 Headset                                                                              | 1         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.97%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.97%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.97%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 29.03%  |
| Micron Technology   | 8         | 25.81%  |
| Samsung Electronics | 6         | 19.35%  |
| Kingston            | 4         | 12.9%   |
| A-DATA Technology   | 2         | 6.45%   |
| Crucial             | 1         | 3.23%   |
| Corsair             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 5.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 5.88%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 5.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 2.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 1         | 2.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.94%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM 4800MT/s            | 1         | 2.94%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s       | 1         | 2.94%   |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 1         | 2.94%   |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s      | 1         | 2.94%   |
| Micron RAM 16JSF25664HY-1G1D1 2048MB SODIMM 1066MT/s           | 1         | 2.94%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s          | 1         | 2.94%   |
| Kingston RAM KKN2NM-MIE 4GB SODIMM DDR4 2667MT/s               | 1         | 2.94%   |
| Kingston RAM HP16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s          | 1         | 2.94%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Kingston RAM 99U5428-017.A00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Crucial RAM CT51264BF160BJ.M8F 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.94%   |
| Corsair RAM CMSX4GX3M1A1600C9 4096MB SODIMM DDR3 1600MT/s      | 1         | 2.94%   |
| A-DATA RAM AO1P24HC8T1-BQXS 8GB SODIMM DDR4 2400MT/s           | 1         | 2.94%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 51.85%  |
| DDR4    | 10        | 37.04%  |
| LPDDR4  | 1         | 3.7%    |
| LPDDR3  | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 92.59%  |
| Row Of Chips | 2         | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 15        | 53.57%  |
| 8192  | 9         | 32.14%  |
| 2048  | 2         | 7.14%   |
| 32768 | 1         | 3.57%   |
| 16384 | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 12        | 41.38%  |
| 3200  | 4         | 13.79%  |
| 2667  | 4         | 13.79%  |
| 2400  | 2         | 6.9%    |
| 2133  | 2         | 6.9%    |
| 1334  | 2         | 6.9%    |
| 4800  | 1         | 3.45%   |
| 1333  | 1         | 3.45%   |
| 1066  | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lexmark International | 1         | 50%     |
| Hewlett-Packard       | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 50%     |
| HP LaserJet 1000                           | 1         | 50%     |

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
| Chicony Electronics                    | 15        | 25%     |
| Realtek Semiconductor                  | 8         | 13.33%  |
| IMC Networks                           | 7         | 11.67%  |
| Sunplus Innovation Technology          | 4         | 6.67%   |
| Microdia                               | 4         | 6.67%   |
| Acer                                   | 4         | 6.67%   |
| Suyin                                  | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Syntek                                 | 2         | 3.33%   |
| Ricoh                                  | 2         | 3.33%   |
| Lite-On Technology                     | 2         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.33%   |
| Primax Electronics                     | 1         | 1.67%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Lenovo                                 | 1         | 1.67%   |
| ALi                                    | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 4         | 6.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 4         | 6.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 3.33%   |
| Realtek HD WebCam                                           | 2         | 3.33%   |
| Lite-On HP HD Webcam                                        | 2         | 3.33%   |
| Chicony HP Truevision HD                                    | 2         | 3.33%   |
| Acer EasyCamera                                             | 2         | 3.33%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.67%   |
| Syntek Integrated Camera                                    | 1         | 1.67%   |
| Suyin HP TrueVision HD                                      | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.67%   |
| Sunplus HP Universal Camera                                 | 1         | 1.67%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.67%   |
| Sunplus HD WebCam                                           | 1         | 1.67%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.67%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 1.67%   |
| Realtek VGA WebCam                                          | 1         | 1.67%   |
| Realtek USB Camera                                          | 1         | 1.67%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.67%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.67%   |
| Realtek Integrated Webcam HD                                | 1         | 1.67%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.67%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.67%   |
| Quanta HP Webcam                                            | 1         | 1.67%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.67%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 1.67%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.67%   |
| Lenovo UVC Camera                                           | 1         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.67%   |
| IMC Networks ov9734_azurewave_camera                        | 1         | 1.67%   |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 1.67%   |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.67%   |
| Chicony thinkpad t430s camera                               | 1         | 1.67%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.67%   |
| Chicony Integrated HP HD Webcam                             | 1         | 1.67%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.67%   |
| Chicony integrated camera                                   | 1         | 1.67%   |
| Chicony HP Truevision HD camera                             | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 60%     |
| Synaptics                  | 2         | 13.33%  |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| LighTuning Technology      | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 4         | 26.67%  |
| Validity Sensors VFS471 Fingerprint Reader        | 4         | 26.67%  |
| Shenzhen Goodix  FingerPrint Device               | 2         | 13.33%  |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 6.67%   |
| LighTuning Fingerprint Reader                     | 1         | 6.67%   |
| AuthenTec AES2810                                 | 1         | 6.67%   |
| Unknown                                           | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Upek        | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 40        | 54.79%  |
| 1     | 28        | 38.36%  |
| 2     | 4         | 5.48%   |
| 3     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 41.67%  |
| Graphics card         | 7         | 19.44%  |
| Net/wireless          | 4         | 11.11%  |
| Chipcard              | 4         | 11.11%  |
| Bluetooth             | 3         | 8.33%   |
| Sound                 | 1         | 2.78%   |
| Multimedia controller | 1         | 2.78%   |
| Modem                 | 1         | 2.78%   |

