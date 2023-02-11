Xero - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 81

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP       | ProBook 6565b               | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP       | 245 G7 Notebook PC          | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI   | BOM-WXX9                    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| Lenovo   | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| ASUSTek  | X540LA                      | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI   | BOM-WXX9                    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI   | BOM-WXX9                    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP       | Pavilion Gaming Laptop 1... | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP       | ZBook 15 G4                 | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP       | ZBook 15 G4                 | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP       | Pavilion Gaming Laptop 1... | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo   | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek  | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion   | P6816                       | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| Dell     | Latitude E6530              | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba  | TECRA A11                   | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo   | ThinkPad L450 20DT0000GE    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X421... | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek  | K53SJ                       | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| ASUSTek  | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP       | Laptop 15s-fq2xxx           | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| ASUSTek  | ZenBook UX433FN_UX433FN     | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| MSI      | Katana GF66 11UE            | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| Lenovo   | ThinkPad T430s 2356FG9      | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius | NS585                       | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Lenovo   | IdeaPad S145-15AST 81N3     | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek  | G551JM                      | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek  | G551JM                      | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASUSTek  | UX303LN                     | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| Dell     | Inspiron 1545               | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo   | IdeaPad 330-17IKB 81DM      | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell     | Precision M3800             | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell     | Precision M3800             | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo   | ThinkPad X230 2325HR9       | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| Acer     | Aspire A515-54G             | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| Dell     | Precision M3800             | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| Dell     | Precision M3800             | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI      | GF63 Thin 9SCX              | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell     | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| HUAWEI   | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell     | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple    | MacBookAir6,2               | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP       | Laptop 15-da0xxx            | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo   | IdeaPad 3 15IML05 81WR      | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| Lenovo   | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Dell     | Venue 11 Pro 7130 vPro      | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo   | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell     | Latitude E6430              | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo   | Legion Y740-15IRHg 81UH     | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer     | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell     | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| HP       | Laptop 15s-eq0xxx           | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Lenovo   | Legion Y540-15IRH-PG0 81... | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| Dell     | Vostro 3590                 | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP       | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASUSTek  | X510UNR                     | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron | D15K                        | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| MSI      | GP73 Leopard 8RD            | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer     | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer     | Aspire A315-58G             | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo   | ThinkPad W530 24384CU       | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| Acer     | Aspire A315-58G             | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP       | ENVY Sleekbook 4            | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo   | IdeaPad 5 15ITL05 82FG      | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo   | Y520-15IKBN 80WK            | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Xero Rolling | 56        | 87.5%   |
| Xero         | 8         | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 63        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.16.15-arch1-1   | 4         | 5.88%   |
| 6.1.1-arch1-1     | 3         | 4.41%   |
| 6.0.7-arch1-1     | 2         | 2.94%   |
| 6.0.12-arch1-1    | 2         | 2.94%   |
| 5.18.16-arch1-1   | 2         | 2.94%   |
| 5.18.11-arch1-1   | 2         | 2.94%   |
| 5.17.9-arch1-1    | 2         | 2.94%   |
| 5.16.8-arch1-1    | 2         | 2.94%   |
| 5.16.2-arch1-1    | 2         | 2.94%   |
| 5.16.1-arch1-1    | 2         | 2.94%   |
| 5.15.33-1-lts     | 2         | 2.94%   |
| 5.14.14-arch1-1   | 2         | 2.94%   |
| 6.1.8-arch1-1     | 1         | 1.47%   |
| 6.1.7-arch1-1     | 1         | 1.47%   |
| 6.1.6-arch1-1     | 1         | 1.47%   |
| 6.1.4-arch1-1     | 1         | 1.47%   |
| 6.1.3-zen1-1-zen  | 1         | 1.47%   |
| 6.0.9-arch1-1     | 1         | 1.47%   |
| 6.0.8-zen1-1-zen  | 1         | 1.47%   |
| 6.0.8-arch1-1     | 1         | 1.47%   |
| 6.0.6-arch1-1     | 1         | 1.47%   |
| 6.0.2-arch1-1     | 1         | 1.47%   |
| 6.0.11-arch1-1    | 1         | 1.47%   |
| 5.19.9-arch1-1    | 1         | 1.47%   |
| 5.19.3-arch1-1    | 1         | 1.47%   |
| 5.19.13-arch1-1   | 1         | 1.47%   |
| 5.19.12-arch1-1   | 1         | 1.47%   |
| 5.19.1-arch2-1    | 1         | 1.47%   |
| 5.18.3-arch1-1    | 1         | 1.47%   |
| 5.17.7-arch1-1    | 1         | 1.47%   |
| 5.17.1-arch1-1    | 1         | 1.47%   |
| 5.16.16-arch1-1   | 1         | 1.47%   |
| 5.16.14-arch1-1   | 1         | 1.47%   |
| 5.16.13-arch1-1   | 1         | 1.47%   |
| 5.16.10-arch1-1   | 1         | 1.47%   |
| 5.15.8-zen1-1-zen | 1         | 1.47%   |
| 5.15.6-arch2-1    | 1         | 1.47%   |
| 5.15.35-1-lts     | 1         | 1.47%   |
| 5.15.26-1-lts     | 1         | 1.47%   |
| 5.15.13-arch1-1   | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.15 | 4         | 5.88%   |
| 6.1.1   | 3         | 4.41%   |
| 5.14.16 | 3         | 4.41%   |
| 5.14.14 | 3         | 4.41%   |
| 6.0.8   | 2         | 2.94%   |
| 6.0.7   | 2         | 2.94%   |
| 6.0.12  | 2         | 2.94%   |
| 5.18.16 | 2         | 2.94%   |
| 5.18.11 | 2         | 2.94%   |
| 5.17.9  | 2         | 2.94%   |
| 5.16.8  | 2         | 2.94%   |
| 5.16.2  | 2         | 2.94%   |
| 5.16.1  | 2         | 2.94%   |
| 5.15.33 | 2         | 2.94%   |
| 5.14.8  | 2         | 2.94%   |
| 6.1.8   | 1         | 1.47%   |
| 6.1.7   | 1         | 1.47%   |
| 6.1.6   | 1         | 1.47%   |
| 6.1.4   | 1         | 1.47%   |
| 6.1.3   | 1         | 1.47%   |
| 6.0.9   | 1         | 1.47%   |
| 6.0.6   | 1         | 1.47%   |
| 6.0.2   | 1         | 1.47%   |
| 6.0.11  | 1         | 1.47%   |
| 5.19.9  | 1         | 1.47%   |
| 5.19.3  | 1         | 1.47%   |
| 5.19.13 | 1         | 1.47%   |
| 5.19.12 | 1         | 1.47%   |
| 5.19.1  | 1         | 1.47%   |
| 5.18.3  | 1         | 1.47%   |
| 5.17.7  | 1         | 1.47%   |
| 5.17.1  | 1         | 1.47%   |
| 5.16.16 | 1         | 1.47%   |
| 5.16.14 | 1         | 1.47%   |
| 5.16.13 | 1         | 1.47%   |
| 5.16.10 | 1         | 1.47%   |
| 5.15.8  | 1         | 1.47%   |
| 5.15.6  | 1         | 1.47%   |
| 5.15.35 | 1         | 1.47%   |
| 5.15.26 | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 14        | 21.21%  |
| 6.0     | 10        | 15.15%  |
| 5.15    | 9         | 13.64%  |
| 5.14    | 9         | 13.64%  |
| 6.1     | 7         | 10.61%  |
| 5.19    | 5         | 7.58%   |
| 5.18    | 5         | 7.58%   |
| 5.17    | 4         | 6.06%   |
| 5.10    | 3         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| KDE5   | 58        | 90.63%  |
| XFCE   | 2         | 3.13%   |
| GNOME  | 2         | 3.13%   |
| LeftWM | 1         | 1.56%   |
| KDE    | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 84.38%  |
| Wayland | 10        | 15.63%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 44        | 66.67%  |
| Unknown | 11        | 16.67%  |
| LightDM | 10        | 15.15%  |
| GDM     | 1         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 35        | 54.69%  |
| en_IN | 6         | 9.38%   |
| pl_PL | 3         | 4.69%   |
| it_IT | 3         | 4.69%   |
| de_DE | 3         | 4.69%   |
| C     | 3         | 4.69%   |
| ru_RU | 2         | 3.13%   |
| fr_FR | 2         | 3.13%   |
| es_MX | 2         | 3.13%   |
| en_AU | 2         | 3.13%   |
| vi_VN | 1         | 1.56%   |
| en_GB | 1         | 1.56%   |
| en_AG | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 64.06%  |
| BIOS | 23        | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 34        | 53.13%  |
| Xfs     | 18        | 28.13%  |
| Ext4    | 9         | 14.06%  |
| Overlay | 3         | 4.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 44        | 68.75%  |
| Unknown | 11        | 17.19%  |
| MBR     | 9         | 14.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 81.82%  |
| Yes       | 12        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 65.63%  |
| Yes       | 22        | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 17        | 26.98%  |
| ASUSTek Computer | 15        | 23.81%  |
| Dell             | 10        | 15.87%  |
| Hewlett-Packard  | 9         | 14.29%  |
| MSI              | 3         | 4.76%   |
| HUAWEI           | 2         | 3.17%   |
| Acer             | 2         | 3.17%   |
| Toshiba          | 1         | 1.59%   |
| Pegatron         | 1         | 1.59%   |
| Medion           | 1         | 1.59%   |
| Aquarius         | 1         | 1.59%   |
| Apple            | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 4.76%   |
| Toshiba TECRA A11                          | 1         | 1.59%   |
| Pegatron D15K                              | 1         | 1.59%   |
| MSI Katana GF66 11UE                       | 1         | 1.59%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.59%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.59%   |
| Medion P6816                               | 1         | 1.59%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.59%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.59%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.59%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 1.59%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.59%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.59%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 1.59%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.59%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.59%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.59%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.59%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.59%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.59%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.59%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.59%   |
| Lenovo IdeaPad 3 14IGL05 81WH              | 1         | 1.59%   |
| HUAWEI WRT-WX9                             | 1         | 1.59%   |
| HUAWEI BOM-WXX9                            | 1         | 1.59%   |
| HP ZBook 15 G4                             | 1         | 1.59%   |
| HP ProBook 6565b                           | 1         | 1.59%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 1.59%   |
| HP Notebook                                | 1         | 1.59%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.59%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.59%   |
| HP Laptop 15-da0xxx                        | 1         | 1.59%   |
| HP ENVY Sleekbook 4                        | 1         | 1.59%   |
| HP 245 G7 Notebook PC                      | 1         | 1.59%   |
| Dell Vostro 3590                           | 1         | 1.59%   |
| Dell Venue 11 Pro 7130 vPro                | 1         | 1.59%   |
| Dell Latitude E6530                        | 1         | 1.59%   |
| Dell Latitude E6520                        | 1         | 1.59%   |
| Dell Latitude E6430                        | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 7         | 11.11%  |
| Lenovo IdeaPad     | 6         | 9.52%   |
| Dell Latitude      | 4         | 6.35%   |
| ASUS VivoBook      | 4         | 6.35%   |
| Lenovo Legion      | 3         | 4.76%   |
| HP Laptop          | 3         | 4.76%   |
| Dell Precision     | 3         | 4.76%   |
| ASUS ASUS          | 3         | 4.76%   |
| ASUS ROG           | 2         | 3.17%   |
| Acer Aspire        | 2         | 3.17%   |
| Toshiba TECRA      | 1         | 1.59%   |
| Pegatron D15K      | 1         | 1.59%   |
| MSI Katana         | 1         | 1.59%   |
| MSI GP73           | 1         | 1.59%   |
| MSI GF63           | 1         | 1.59%   |
| Medion P6816       | 1         | 1.59%   |
| Lenovo Y520-15IKBN | 1         | 1.59%   |
| HUAWEI WRT-WX9     | 1         | 1.59%   |
| HUAWEI BOM-WXX9    | 1         | 1.59%   |
| HP ZBook           | 1         | 1.59%   |
| HP ProBook         | 1         | 1.59%   |
| HP Pavilion        | 1         | 1.59%   |
| HP Notebook        | 1         | 1.59%   |
| HP ENVY            | 1         | 1.59%   |
| HP 245             | 1         | 1.59%   |
| Dell Vostro        | 1         | 1.59%   |
| Dell Venue         | 1         | 1.59%   |
| Dell Inspiron      | 1         | 1.59%   |
| ASUS ZenBook       | 1         | 1.59%   |
| ASUS X540LA        | 1         | 1.59%   |
| ASUS X510UNR       | 1         | 1.59%   |
| ASUS UX303LN       | 1         | 1.59%   |
| ASUS K53SJ         | 1         | 1.59%   |
| ASUS G551JM        | 1         | 1.59%   |
| Aquarius NS585     | 1         | 1.59%   |
| Apple MacBookAir6  | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 12        | 19.05%  |
| 2020 | 10        | 15.87%  |
| 2021 | 8         | 12.7%   |
| 2012 | 7         | 11.11%  |
| 2018 | 5         | 7.94%   |
| 2017 | 4         | 6.35%   |
| 2013 | 4         | 6.35%   |
| 2015 | 3         | 4.76%   |
| 2011 | 3         | 4.76%   |
| 2016 | 2         | 3.17%   |
| 2014 | 2         | 3.17%   |
| 2022 | 1         | 1.59%   |
| 2010 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 36.51%  |
| 3.01-4.0    | 12        | 19.05%  |
| 16.01-24.0  | 12        | 19.05%  |
| 8.01-16.0   | 11        | 17.46%  |
| 32.01-64.0  | 2         | 3.17%   |
| 24.01-32.0  | 2         | 3.17%   |
| 64.01-256.0 | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 36.36%  |
| 1.01-2.0   | 18        | 27.27%  |
| 4.01-8.0   | 12        | 18.18%  |
| 3.01-4.0   | 10        | 15.15%  |
| 16.01-24.0 | 1         | 1.52%   |
| 0.51-1.0   | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 68.75%  |
| 2      | 18        | 28.13%  |
| 4      | 1         | 1.56%   |
| 3      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 79.37%  |
| Yes       | 13        | 20.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 71.43%  |
| No        | 18        | 28.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 95.24%  |
| No        | 3         | 4.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 82.54%  |
| No        | 11        | 17.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 11        | 17.19%  |
| India                  | 8         | 12.5%   |
| Germany                | 6         | 9.38%   |
| France                 | 4         | 6.25%   |
| Poland                 | 3         | 4.69%   |
| Italy                  | 3         | 4.69%   |
| Turkey                 | 2         | 3.13%   |
| Russia                 | 2         | 3.13%   |
| Pakistan               | 2         | 3.13%   |
| Norway                 | 2         | 3.13%   |
| Greece                 | 2         | 3.13%   |
| Australia              | 2         | 3.13%   |
| Zambia                 | 1         | 1.56%   |
| Vietnam                | 1         | 1.56%   |
| Togo                   | 1         | 1.56%   |
| Sweden                 | 1         | 1.56%   |
| Romania                | 1         | 1.56%   |
| Palestinian Territory  | 1         | 1.56%   |
| Netherlands            | 1         | 1.56%   |
| Morocco                | 1         | 1.56%   |
| Mongolia               | 1         | 1.56%   |
| Mexico                 | 1         | 1.56%   |
| Malaysia               | 1         | 1.56%   |
| Lebanon                | 1         | 1.56%   |
| Indonesia              | 1         | 1.56%   |
| Hungary                | 1         | 1.56%   |
| Chile                  | 1         | 1.56%   |
| Canada                 | 1         | 1.56%   |
| Bosnia and Herzegovina | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Longmont     | 3         | 4.69%   |
| Madurai      | 2         | 3.13%   |
| Istanbul     | 2         | 3.13%   |
| Zenica       | 1         | 1.56%   |
| Ulan Bator   | 1         | 1.56%   |
| Ufa          | 1         | 1.56%   |
| Toronto      | 1         | 1.56%   |
| Taranto      | 1         | 1.56%   |
| Tangerang    | 1         | 1.56%   |
| Stuttgart    | 1         | 1.56%   |
| Stockholm    | 1         | 1.56%   |
| Stavropol    | 1         | 1.56%   |
| Seattle      | 1         | 1.56%   |
| Santa Cruz   | 1         | 1.56%   |
| Ramallah     | 1         | 1.56%   |
| Pune         | 1         | 1.56%   |
| Poznan       | 1         | 1.56%   |
| Porcia       | 1         | 1.56%   |
| Pirmasens    | 1         | 1.56%   |
| Perth        | 1         | 1.56%   |
| Pavia        | 1         | 1.56%   |
| Paris        | 1         | 1.56%   |
| Oslo         | 1         | 1.56%   |
| Neu-Ulm      | 1         | 1.56%   |
| Mumbai       | 1         | 1.56%   |
| Melbourne    | 1         | 1.56%   |
| Magdeburg    | 1         | 1.56%   |
| Lusaka       | 1         | 1.56%   |
| Lucknow      | 1         | 1.56%   |
| Lublin       | 1         | 1.56%   |
| Longvic      | 1         | 1.56%   |
| Lomé        | 1         | 1.56%   |
| Lamia        | 1         | 1.56%   |
| Lahore       | 1         | 1.56%   |
| Kuala Lumpur | 1         | 1.56%   |
| Kristiansand | 1         | 1.56%   |
| Kolkata      | 1         | 1.56%   |
| Islamabad    | 1         | 1.56%   |
| Ioannina     | 1         | 1.56%   |
| Iasi         | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 17        | 18     | 20.24%  |
| Seagate                     | 16        | 19     | 19.05%  |
| WDC                         | 7         | 8      | 8.33%   |
| Toshiba                     | 5         | 5      | 5.95%   |
| Intel                       | 5         | 5      | 5.95%   |
| Kingston                    | 4         | 5      | 4.76%   |
| HGST                        | 4         | 4      | 4.76%   |
| Micron Technology           | 3         | 4      | 3.57%   |
| Unknown                     | 2         | 2      | 2.38%   |
| SanDisk                     | 2         | 2      | 2.38%   |
| KIOXIA                      | 2         | 3      | 2.38%   |
| Vaseky                      | 1         | 1      | 1.19%   |
| Transcend                   | 1         | 1      | 1.19%   |
| Plextor                     | 1         | 1      | 1.19%   |
| Phison                      | 1         | 1      | 1.19%   |
| OSCOO                       | 1         | 1      | 1.19%   |
| LITEONIT                    | 1         | 1      | 1.19%   |
| LITEON                      | 1         | 1      | 1.19%   |
| Kingston Technology Company | 1         | 1      | 1.19%   |
| Intenso                     | 1         | 1      | 1.19%   |
| Inateck                     | 1         | 1      | 1.19%   |
| Hitachi                     | 1         | 1      | 1.19%   |
| GOODRAM                     | 1         | 1      | 1.19%   |
| Crucial                     | 1         | 1      | 1.19%   |
| China                       | 1         | 1      | 1.19%   |
| Biostar                     | 1         | 1      | 1.19%   |
| Apple                       | 1         | 1      | 1.19%   |
| Apacer                      | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                       | 3         | 3.53%   |
| Seagate ST1000LM035-1RK172 1TB                       | 3         | 3.53%   |
| Seagate One Touch HDD 5TB                            | 3         | 3.53%   |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 2         | 2.35%   |
| Samsung SSD 860 EVO 250GB                            | 2         | 2.35%   |
| WDC WDS100T1X0E-00AFY0 1TB                           | 1         | 1.18%   |
| WDC WDBNCE0010PNC 1TB SSD                            | 1         | 1.18%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 1         | 1.18%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB                 | 1         | 1.18%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB                 | 1         | 1.18%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                 | 1         | 1.18%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB                 | 1         | 1.18%   |
| Vaseky V800/256G 256GB SSD                           | 1         | 1.18%   |
| Unknown MMC Card  64GB                               | 1         | 1.18%   |
| Unknown G1J38E  64GB                                 | 1         | 1.18%   |
| Transcend TS256GMTS400 256GB SSD                     | 1         | 1.18%   |
| Toshiba XG6 NVMe SSD Controller 512GB                | 1         | 1.18%   |
| Toshiba MQ04ABF100 1TB                               | 1         | 1.18%   |
| Toshiba MQ01ABF050M 500GB                            | 1         | 1.18%   |
| Toshiba KBG40ZNT512G MEMORY 512GB                    | 1         | 1.18%   |
| Toshiba KBG30ZMV256G 256GB                           | 1         | 1.18%   |
| Seagate ST9500325AS 500GB                            | 1         | 1.18%   |
| Seagate ST500LT012-9WS142 500GB                      | 1         | 1.18%   |
| Seagate ST500LM000-SSHD-8GB                          | 1         | 1.18%   |
| Seagate ST1000LM048-2E7172 1TB                       | 1         | 1.18%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB           | 1         | 1.18%   |
| Seagate Expansion 240GB                              | 1         | 1.18%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD                  | 1         | 1.18%   |
| SanDisk NVMe SSD Drive 256GB                         | 1         | 1.18%   |
| Samsung SSD SM841 mSATA 128GB                        | 1         | 1.18%   |
| Samsung SSD 980 1TB                                  | 1         | 1.18%   |
| Samsung SSD 860 EVO 1TB                              | 1         | 1.18%   |
| Samsung SSD 850 PRO 512GB                            | 1         | 1.18%   |
| Samsung SSD 850 EVO 250GB                            | 1         | 1.18%   |
| Samsung PM961 NVMe 1024GB                            | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 1         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 1         | 1.18%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 1         | 1.18%   |
| Samsung MZVLQ1T0HBLB-00B00 1024GB                    | 1         | 1.18%   |
| Samsung MZVLB1T0HBLR-00000 1TB                       | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 18     | 66.67%  |
| HGST    | 4         | 4      | 16.67%  |
| Toshiba | 2         | 2      | 8.33%   |
| WDC     | 1         | 1      | 4.17%   |
| Hitachi | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 29.17%  |
| WDC                 | 1         | 1      | 4.17%   |
| Vaseky              | 1         | 1      | 4.17%   |
| Transcend           | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| OSCOO               | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| GOODRAM             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| Biostar             | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |
| Apacer              | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 31        | 40     | 40.26%  |
| HDD  | 23        | 26     | 29.87%  |
| SSD  | 21        | 24     | 27.27%  |
| MMC  | 2         | 2      | 2.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 46     | 49.33%  |
| NVMe | 31        | 39     | 41.33%  |
| SAS  | 5         | 5      | 6.67%   |
| MMC  | 2         | 2      | 2.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 26     | 48.84%  |
| 0.51-1.0   | 19        | 21     | 44.19%  |
| 4.01-10.0  | 3         | 3      | 6.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 13        | 20%     |
| 1001-2000      | 13        | 20%     |
| 251-500        | 12        | 18.46%  |
| 501-1000       | 7         | 10.77%  |
| 101-250        | 6         | 9.23%   |
| Unknown        | 6         | 9.23%   |
| 51-100         | 4         | 6.15%   |
| 1-20           | 2         | 3.08%   |
| 21-50          | 1         | 1.54%   |
| 2001-3000      | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 21.54%  |
| 1-20           | 12        | 18.46%  |
| 51-100         | 12        | 18.46%  |
| 251-500        | 6         | 9.23%   |
| 21-50          | 6         | 9.23%   |
| Unknown        | 6         | 9.23%   |
| 501-1000       | 4         | 6.15%   |
| 2001-3000      | 3         | 4.62%   |
| More than 3000 | 1         | 1.54%   |
| 1001-2000      | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 12.5%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 12.5%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 12.5%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 12.5%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 12.5%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 12.5%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 50%     |
| HGST                | 2         | 2      | 25%     |
| Toshiba             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| HGST    | 2         | 2      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 87.5%   |
| NVMe | 1         | 1      | 12.5%   |

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
| Works    | 47        | 62     | 69.12%  |
| Detected | 13        | 22     | 19.12%  |
| Malfunc  | 8         | 8      | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 58.14%  |
| Samsung Electronics          | 11        | 12.79%  |
| AMD                          | 6         | 6.98%   |
| SanDisk                      | 5         | 5.81%   |
| Kingston Technology Company  | 4         | 4.65%   |
| Toshiba America Info Systems | 3         | 3.49%   |
| Micron Technology            | 3         | 3.49%   |
| KIOXIA                       | 2         | 2.33%   |
| Seagate Technology           | 1         | 1.16%   |
| Phison Electronics           | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 6.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.74%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 6.74%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 5.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 5.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 4.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 4.49%   |
| Micron Non-Volatile memory controller                                          | 3         | 3.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 3.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.25%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.25%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 2.25%   |
| Intel SSD 660P Series                                                          | 2         | 2.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.12%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.12%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.12%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.12%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.12%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.12%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.12%   |
| Samsung Apple PCIe SSD                                                         | 1         | 1.12%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.12%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.12%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.12%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.12%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.12%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 1.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 51.72%  |
| NVMe | 31        | 35.63%  |
| RAID | 11        | 12.64%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 85.71%  |
| AMD    | 9         | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 4.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 4.76%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 4.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 3.17%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 3.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 3.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 3.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 3.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 3.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 3.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 3.17%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 3.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.59%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.59%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.59%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.59%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.59%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.59%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.59%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.59%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.59%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.59%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.59%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 1         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 1         | 1.59%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 1         | 1.59%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 1         | 1.59%   |
| Intel Core i3-5020U CPU @ 2.20GHz       | 1         | 1.59%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 1.59%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 1         | 1.59%   |
| Intel 12th Gen Core i7-12700H           | 1         | 1.59%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 20        | 31.75%  |
| Intel Core i5    | 18        | 28.57%  |
| Other            | 9         | 14.29%  |
| Intel Core i3    | 4         | 6.35%   |
| AMD Ryzen 7      | 3         | 4.76%   |
| AMD Ryzen 5      | 3         | 4.76%   |
| Intel Celeron    | 2         | 3.17%   |
| Intel Core 2 Duo | 1         | 1.59%   |
| AMD Ryzen 3      | 1         | 1.59%   |
| AMD A6           | 1         | 1.59%   |
| AMD A4           | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 29        | 46.03%  |
| 2      | 25        | 39.68%  |
| 8      | 4         | 6.35%   |
| 6      | 4         | 6.35%   |
| 14     | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 89.06%  |
| 1      | 7         | 10.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 22.73%  |
| 0x806c1    | 7         | 10.61%  |
| 0x806ec    | 5         | 7.58%   |
| 0x306a9    | 4         | 6.06%   |
| 0x906ea    | 3         | 4.55%   |
| 0x806e9    | 3         | 4.55%   |
| 0x206a7    | 3         | 4.55%   |
| 0x08108109 | 3         | 4.55%   |
| 0x906e9    | 2         | 3.03%   |
| 0x806eb    | 2         | 3.03%   |
| 0x706a8    | 2         | 3.03%   |
| 0x40651    | 2         | 3.03%   |
| 0xa0652    | 1         | 1.52%   |
| 0x906ed    | 1         | 1.52%   |
| 0x906eb    | 1         | 1.52%   |
| 0x906a3    | 1         | 1.52%   |
| 0x806d1    | 1         | 1.52%   |
| 0x706e5    | 1         | 1.52%   |
| 0x406e3    | 1         | 1.52%   |
| 0x306d4    | 1         | 1.52%   |
| 0x306c3    | 1         | 1.52%   |
| 0x20652    | 1         | 1.52%   |
| 0x1067a    | 1         | 1.52%   |
| 0x08608103 | 1         | 1.52%   |
| 0x08600106 | 1         | 1.52%   |
| 0x06006705 | 1         | 1.52%   |
| 0x03000027 | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 31.75%  |
| TigerLake        | 7         | 11.11%  |
| Haswell          | 7         | 11.11%  |
| IvyBridge        | 6         | 9.52%   |
| Zen+             | 3         | 4.76%   |
| Zen 2            | 3         | 4.76%   |
| SandyBridge      | 3         | 4.76%   |
| IceLake          | 2         | 3.17%   |
| Goldmont plus    | 2         | 3.17%   |
| Broadwell        | 2         | 3.17%   |
| Westmere         | 1         | 1.59%   |
| Skylake          | 1         | 1.59%   |
| Penryn           | 1         | 1.59%   |
| K10 Llano        | 1         | 1.59%   |
| Excavator        | 1         | 1.59%   |
| CometLake        | 1         | 1.59%   |
| Alderlake Hybrid | 1         | 1.59%   |
| Unknown          | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 55.21%  |
| Nvidia | 32        | 33.33%  |
| AMD    | 11        | 11.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 5.21%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 5.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 4.17%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 3.13%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 3.13%   |
| Intel UHD Graphics 620                                                    | 3         | 3.13%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 3.13%   |
| Intel HD Graphics 620                                                     | 3         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.08%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 2.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 2.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 2.08%   |
| Intel HD Graphics 630                                                     | 2         | 2.08%   |
| Intel HD Graphics 5500                                                    | 2         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.08%   |
| AMD Renoir                                                                | 2         | 2.08%   |
| Nvidia TU117M                                                             | 1         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.04%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 1.04%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.04%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 1.04%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.04%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 1.04%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 1.04%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.04%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 1.04%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 1.04%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 1.04%   |
| Nvidia GF119M [GeForce GT 520M]                                           | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 27        | 42.86%  |
| 1 x Intel      | 22        | 34.92%  |
| 1 x AMD        | 5         | 7.94%   |
| Intel + AMD    | 3         | 4.76%   |
| AMD + Nvidia   | 3         | 4.76%   |
| 1 x Nvidia     | 2         | 3.17%   |
| 2 x Intel      | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 67.19%  |
| Proprietary | 21        | 32.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 70.31%  |
| 1.01-2.0   | 8         | 12.5%   |
| 0.01-0.5   | 5         | 7.81%   |
| 5.01-6.0   | 3         | 4.69%   |
| 3.01-4.0   | 2         | 3.13%   |
| 0.51-1.0   | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 22.67%  |
| Chimei Innolux      | 12        | 16%     |
| BOE                 | 12        | 16%     |
| Samsung Electronics | 9         | 12%     |
| LG Display          | 9         | 12%     |
| Sharp               | 2         | 2.67%   |
| PANDA               | 2         | 2.67%   |
| Dell                | 2         | 2.67%   |
| Apple               | 2         | 2.67%   |
| TMX                 | 1         | 1.33%   |
| Sceptre Tech        | 1         | 1.33%   |
| LGD                 | 1         | 1.33%   |
| Lenovo              | 1         | 1.33%   |
| Goldstar            | 1         | 1.33%   |
| CSO                 | 1         | 1.33%   |
| BenQ                | 1         | 1.33%   |
| Acer                | 1         | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 4%      |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 2         | 2.67%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 2.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 2.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 2.67%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 1.33%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.33%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.33%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.33%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 1.33%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch   | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.33%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.33%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 1.33%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 1.33%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 1.33%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 1.33%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.33%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.33%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch             | 1         | 1.33%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.33%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.33%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 1.33%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.33%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                   | 1         | 1.33%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 1.33%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 1         | 1.33%   |
| CSO LCD Monitor CSO1403 3840x2400 302x189mm 14.0-inch                   | 1         | 1.33%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch        | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 293x165mm 13.2-inch        | 1         | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 43        | 61.43%  |
| 1366x768 (WXGA)   | 15        | 21.43%  |
| 3840x2160 (4K)    | 3         | 4.29%   |
| 1600x900 (HD+)    | 3         | 4.29%   |
| 3840x2400         | 1         | 1.43%   |
| 3200x1800 (QHD+)  | 1         | 1.43%   |
| 2560x1080         | 1         | 1.43%   |
| 2160x1440         | 1         | 1.43%   |
| 1920x1200 (WUXGA) | 1         | 1.43%   |
| 1440x900 (WXGA+)  | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 52.7%   |
| 14      | 10        | 13.51%  |
| 13      | 8         | 10.81%  |
| 23      | 4         | 5.41%   |
| 84      | 3         | 4.05%   |
| 17      | 2         | 2.7%    |
| 31      | 1         | 1.35%   |
| 28      | 1         | 1.35%   |
| 27      | 1         | 1.35%   |
| 24      | 1         | 1.35%   |
| 21      | 1         | 1.35%   |
| 18      | 1         | 1.35%   |
| 12      | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 72%     |
| 501-600     | 6         | 8%      |
| 201-300     | 4         | 5.33%   |
| 401-500     | 3         | 4%      |
| 1501-2000   | 3         | 4%      |
| 601-700     | 2         | 2.67%   |
| 351-400     | 2         | 2.67%   |
| Unknown     | 1         | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 59        | 90.77%  |
| 16/10   | 3         | 4.62%   |
| 3/2     | 1         | 1.54%   |
| 21/9    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 52.7%   |
| 81-90          | 16        | 21.62%  |
| 201-250        | 6         | 8.11%   |
| More than 1000 | 3         | 4.05%   |
| 71-80          | 2         | 2.7%    |
| 121-130        | 2         | 2.7%    |
| 61-70          | 1         | 1.35%   |
| 351-500        | 1         | 1.35%   |
| 301-350        | 1         | 1.35%   |
| 251-300        | 1         | 1.35%   |
| 141-150        | 1         | 1.35%   |
| Unknown        | 1         | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 54.05%  |
| 101-120       | 17        | 22.97%  |
| 51-100        | 11        | 14.86%  |
| 161-240       | 3         | 4.05%   |
| More than 240 | 2         | 2.7%    |
| Unknown       | 1         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 52        | 81.25%  |
| 2     | 11        | 17.19%  |
| 3     | 1         | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 43        | 46.74%  |
| Realtek Semiconductor             | 31        | 33.7%   |
| Broadcom Limited                  | 4         | 4.35%   |
| Qualcomm Atheros                  | 3         | 3.26%   |
| ASIX Electronics                  | 3         | 3.26%   |
| Samsung Electronics               | 2         | 2.17%   |
| MediaTek                          | 2         | 2.17%   |
| Ericsson Business Mobile Networks | 2         | 2.17%   |
| Ralink                            | 1         | 1.09%   |
| Marvell Technology Group          | 1         | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 22        | 19.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 6         | 5.41%   |
| Intel Wi-Fi 6 AX201                                                | 5         | 4.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4         | 3.6%    |
| Intel Wireless 7260                                                | 4         | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 3.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 4         | 3.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 3.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.7%    |
| Intel Wireless 8265 / 8275                                         | 3         | 2.7%    |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 2.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 1.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.8%    |
| Intel Wi-Fi 6 AX200                                                | 2         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.8%    |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.8%    |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.8%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.9%    |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller               | 1         | 0.9%    |
| Intel Wireless-AC 9260                                             | 1         | 0.9%    |
| Intel Wireless 8260                                                | 1         | 0.9%    |
| Intel Wireless 7265                                                | 1         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 0.9%    |
| Intel Ethernet Connection I219-V                                   | 1         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                               | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 0.9%    |
| Intel Ethernet Connection (3) I218-V                               | 1         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                              | 1         | 0.9%    |
| Intel Ethernet Connection (16) I219-LM                             | 1         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 70%     |
| Realtek Semiconductor | 9         | 15%     |
| Broadcom Limited      | 4         | 6.67%   |
| Qualcomm Atheros      | 2         | 3.33%   |
| MediaTek              | 2         | 3.33%   |
| Ralink                | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 5         | 8.33%   |
| Intel Wireless 7260                                           | 4         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 6.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 5%      |
| Intel Wireless 8265 / 8275                                    | 3         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 3.33%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 3.33%   |
| Intel Centrino Wireless-N 2230                                | 2         | 3.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 2         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.67%   |
| Intel Wireless-AC 9260                                        | 1         | 1.67%   |
| Intel Wireless 8260                                           | 1         | 1.67%   |
| Intel Wireless 7265                                           | 1         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.67%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Intel Centrino Wireless-N 2200                                | 1         | 1.67%   |
| Intel Centrino Wireless-N 100                                 | 1         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 1.67%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 56.25%  |
| Intel                    | 14        | 29.17%  |
| ASIX Electronics         | 3         | 6.25%   |
| Samsung Electronics      | 2         | 4.17%   |
| Qualcomm Atheros         | 1         | 2.08%   |
| Marvell Technology Group | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 44.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 12.24%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 8.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 6.12%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.04%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 2.04%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 56.07%  |
| Ethernet | 45        | 42.06%  |
| Modem    | 2         | 1.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 80%     |
| Ethernet | 13        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 58.73%  |
| 1     | 25        | 39.68%  |
| 0     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 69.84%  |
| Yes  | 19        | 30.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 61.54%  |
| Realtek Semiconductor           | 5         | 9.62%   |
| Broadcom                        | 5         | 9.62%   |
| IMC Networks                    | 4         | 7.69%   |
| Toshiba                         | 1         | 1.92%   |
| Realtek                         | 1         | 1.92%   |
| Qualcomm Atheros Communications | 1         | 1.92%   |
| Lite-On Technology              | 1         | 1.92%   |
| Dell                            | 1         | 1.92%   |
| Apple                           | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 13        | 25%     |
| Intel Bluetooth wireless interface             | 7         | 13.46%  |
| Intel Bluetooth Device                         | 7         | 13.46%  |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 5.77%   |
| Realtek Bluetooth Radio                        | 2         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 2         | 3.85%   |
| Intel AX200 Bluetooth                          | 2         | 3.85%   |
| IMC Networks Wireless_Device                   | 2         | 3.85%   |
| IMC Networks Bluetooth Radio                   | 2         | 3.85%   |
| Broadcom BCM20702A0 Bluetooth                  | 2         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 3.85%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 1.92%   |
| Realtek Bluetooth Radio                        | 1         | 1.92%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.92%   |
| Lite-On Bluetooth Device                       | 1         | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.92%   |
| Dell BCM20702A0 Bluetooth Module               | 1         | 1.92%   |
| Broadcom BCM2045A0                             | 1         | 1.92%   |
| Apple Bluetooth USB Host Controller            | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 54        | 65.85%  |
| Nvidia                     | 14        | 17.07%  |
| AMD                        | 9         | 10.98%  |
| Samsung Electronics        | 1         | 1.22%   |
| Realtek Semiconductor      | 1         | 1.22%   |
| PreSonus Audio Electronics | 1         | 1.22%   |
| Barco Display Systems      | 1         | 1.22%   |
| ASUSTek Computer           | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 7.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 7.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 7.22%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 6.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 5.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 5.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 4.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.09%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.06%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 2.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.06%   |
| Intel CM238 HD Audio Controller                                            | 2         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.06%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.06%   |
| Samsung Electronics USBC Headset                                           | 1         | 1.03%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.03%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.03%   |
| Nvidia Audio device                                                        | 1         | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.03%   |
| Barco Display Systems USBFC1-A                                             | 1         | 1.03%   |
| ASUSTek Computer C-Media Audio                                             | 1         | 1.03%   |
| AMD High Definition Audio Controller                                       | 1         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 35.38%  |
| SK hynix            | 21        | 32.31%  |
| Micron Technology   | 7         | 10.77%  |
| Crucial             | 6         | 9.23%   |
| Kingston            | 3         | 4.62%   |
| Ramaxel Technology  | 2         | 3.08%   |
| Nanya Technology    | 1         | 1.54%   |
| Elpida              | 1         | 1.54%   |
| Corsair             | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 4.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 4.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 2.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.94%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.47%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.47%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.47%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.47%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 1.47%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 1.47%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.47%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.47%   |
| Ramaxel RAM RMT3020EC58E9F1333 4096MB SODIMM DDR3 4199MT/s       | 1         | 1.47%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.47%   |
| Nanya RAM M2S2G64CB88B5N-CG 2GB SODIMM DDR3 1333MT/s             | 1         | 1.47%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 32        | 59.26%  |
| DDR3   | 15        | 27.78%  |
| LPDDR4 | 2         | 3.7%    |
| LPDDR3 | 2         | 3.7%    |
| SDRAM  | 1         | 1.85%   |
| DDR5   | 1         | 1.85%   |
| DDR    | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 83.64%  |
| Row Of Chips | 9         | 16.36%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 49.15%  |
| 4096  | 22        | 37.29%  |
| 16384 | 5         | 8.47%   |
| 2048  | 3         | 5.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 21        | 33.87%  |
| 3200  | 11        | 17.74%  |
| 1600  | 11        | 17.74%  |
| 3266  | 3         | 4.84%   |
| 2400  | 3         | 4.84%   |
| 2133  | 3         | 4.84%   |
| 1333  | 3         | 4.84%   |
| 4267  | 2         | 3.23%   |
| 4800  | 1         | 1.61%   |
| 4199  | 1         | 1.61%   |
| 1334  | 1         | 1.61%   |
| 1067  | 1         | 1.61%   |
| 800   | 1         | 1.61%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 15        | 25%     |
| Chicony Electronics                    | 9         | 15%     |
| Acer                                   | 8         | 13.33%  |
| Realtek Semiconductor                  | 6         | 10%     |
| Syntek                                 | 4         | 6.67%   |
| Quanta                                 | 4         | 6.67%   |
| Microdia                               | 3         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5%      |
| Sunplus Innovation Technology          | 2         | 3.33%   |
| Suyin                                  | 1         | 1.67%   |
| Sonix Technology                       | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Alpha Imaging Technology               | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                       | 4         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 4         | 6.67%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 5%      |
| Quanta HP TrueVision HD Camera                                 | 3         | 5%      |
| IMC Networks Integrated Camera                                 | 3         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam                             | 2         | 3.33%   |
| Chicony Integrated Camera                                      | 2         | 3.33%   |
| Acer ThinkPad Integrated Camera                                | 2         | 3.33%   |
| Acer HD Webcam                                                 | 2         | 3.33%   |
| Suyin Asus Integrated Webcam                                   | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.67%   |
| Sunplus HP Truevision HD                                       | 1         | 1.67%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 1.67%   |
| Ricoh Integrated Webcam                                        | 1         | 1.67%   |
| Realtek Integrated Webcam_HD                                   | 1         | 1.67%   |
| Realtek Integrated Webcam                                      | 1         | 1.67%   |
| Realtek Built-In Video Camera                                  | 1         | 1.67%   |
| Quanta HD User Facing                                          | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.67%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.67%   |
| Lite-On Integrated Camera                                      | 1         | 1.67%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 1.67%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.67%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 1         | 1.67%   |
| IMC Networks HD Camera                                         | 1         | 1.67%   |
| IMC Networks EasyCamera                                        | 1         | 1.67%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.67%   |
| Chicony USB2.0 UVC WebCam                                      | 1         | 1.67%   |
| Chicony USB 2.0 Camera                                         | 1         | 1.67%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.67%   |
| Chicony HP Webcam                                              | 1         | 1.67%   |
| Chicony HD User Facing                                         | 1         | 1.67%   |
| Chicony EasyCamera                                             | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 1         | 1.67%   |
| Alpha Imaging Integrated_Webcam_8M                             | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 28.57%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |
| Synaptics                  | 1         | 14.29%  |
| Elan Microelectronics      | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 28.57%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Elan ELAN:Fingerprint                             | 1         | 14.29%  |
| AuthenTec Fingerprint Sensor                      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 28.57%  |
| Broadcom    | 2         | 28.57%  |
| Yubico.com  | 1         | 14.29%  |
| Clay Logic  | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 28.57%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 14.29%  |
| Clay Logic Nitrokey Pro                                    | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 44        | 68.75%  |
| 1     | 16        | 25%     |
| 2     | 4         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 29.17%  |
| Graphics card         | 6         | 25%     |
| Chipcard              | 5         | 20.83%  |
| Multimedia controller | 2         | 8.33%   |
| Camera                | 2         | 8.33%   |
| Storage               | 1         | 4.17%   |
| Network               | 1         | 4.17%   |

