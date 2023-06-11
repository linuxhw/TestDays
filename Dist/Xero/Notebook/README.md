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

Total: 98

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Acer     | Aspire E5-573G              | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Acer     | Aspire E1-572               | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo   | Legion 5 15ACH6H 82JU       | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo   | Legion 5 15ACH6H 82JU       | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| Lenovo   | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP       | Victus by Laptop 16-e0xx... | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell     | G5 5500                     | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo   | IdeaPad S340-15IIL 81VW     | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo   | IdeaPad S340-15IIL 81VW     | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| Dell     | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek  | TUF Gaming FX505DY_FX505... | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple    | MacBookPro11,3              | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo   | ThinkPad P51 20HJS11Y00     | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo   | IdeaPad S540-15IML D 81N... | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Dell     | Inspiron 3505               | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
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
| Xero Rolling | 69        | 89.61%  |
| Xero         | 8         | 10.39%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.0.12-arch1-1   | 4         | 4.94%   |
| 5.16.15-arch1-1  | 4         | 4.94%   |
| 6.2.6-arch1-1    | 3         | 3.7%    |
| 6.1.1-arch1-1    | 3         | 3.7%    |
| 6.2.7-arch1-1    | 2         | 2.47%   |
| 6.0.7-arch1-1    | 2         | 2.47%   |
| 5.18.16-arch1-1  | 2         | 2.47%   |
| 5.18.11-arch1-1  | 2         | 2.47%   |
| 5.17.9-arch1-1   | 2         | 2.47%   |
| 5.16.8-arch1-1   | 2         | 2.47%   |
| 5.16.2-arch1-1   | 2         | 2.47%   |
| 5.16.1-arch1-1   | 2         | 2.47%   |
| 5.15.33-1-lts    | 2         | 2.47%   |
| 5.14.14-arch1-1  | 2         | 2.47%   |
| 6.3.6-arch1-1    | 1         | 1.23%   |
| 6.3.4-arch1-1    | 1         | 1.23%   |
| 6.2.8-arch1-1    | 1         | 1.23%   |
| 6.2.2-arch2-1    | 1         | 1.23%   |
| 6.1.8-arch1-1    | 1         | 1.23%   |
| 6.1.7-arch1-1    | 1         | 1.23%   |
| 6.1.6-arch1-1    | 1         | 1.23%   |
| 6.1.4-arch1-1    | 1         | 1.23%   |
| 6.1.3-zen1-1-zen | 1         | 1.23%   |
| 6.1.15-1-lts     | 1         | 1.23%   |
| 6.1.12-arch1-1   | 1         | 1.23%   |
| 6.0.9-arch1-1    | 1         | 1.23%   |
| 6.0.8-zen1-1-zen | 1         | 1.23%   |
| 6.0.8-arch1-1    | 1         | 1.23%   |
| 6.0.6-arch1-1    | 1         | 1.23%   |
| 6.0.2-arch1-1    | 1         | 1.23%   |
| 6.0.11-arch1-1   | 1         | 1.23%   |
| 5.19.9-arch1-1   | 1         | 1.23%   |
| 5.19.3-arch1-1   | 1         | 1.23%   |
| 5.19.13-arch1-1  | 1         | 1.23%   |
| 5.19.12-arch1-1  | 1         | 1.23%   |
| 5.19.1-arch2-1   | 1         | 1.23%   |
| 5.18.3-arch1-1   | 1         | 1.23%   |
| 5.17.7-arch1-1   | 1         | 1.23%   |
| 5.17.1-arch1-1   | 1         | 1.23%   |
| 5.16.16-arch1-1  | 1         | 1.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.12  | 4         | 4.94%   |
| 5.16.15 | 4         | 4.94%   |
| 6.2.6   | 3         | 3.7%    |
| 6.1.1   | 3         | 3.7%    |
| 5.14.16 | 3         | 3.7%    |
| 5.14.14 | 3         | 3.7%    |
| 6.2.7   | 2         | 2.47%   |
| 6.0.8   | 2         | 2.47%   |
| 6.0.7   | 2         | 2.47%   |
| 5.18.16 | 2         | 2.47%   |
| 5.18.11 | 2         | 2.47%   |
| 5.17.9  | 2         | 2.47%   |
| 5.16.8  | 2         | 2.47%   |
| 5.16.2  | 2         | 2.47%   |
| 5.16.1  | 2         | 2.47%   |
| 5.15.33 | 2         | 2.47%   |
| 5.14.8  | 2         | 2.47%   |
| 6.3.6   | 1         | 1.23%   |
| 6.3.4   | 1         | 1.23%   |
| 6.2.8   | 1         | 1.23%   |
| 6.2.2   | 1         | 1.23%   |
| 6.1.8   | 1         | 1.23%   |
| 6.1.7   | 1         | 1.23%   |
| 6.1.6   | 1         | 1.23%   |
| 6.1.4   | 1         | 1.23%   |
| 6.1.3   | 1         | 1.23%   |
| 6.1.15  | 1         | 1.23%   |
| 6.1.12  | 1         | 1.23%   |
| 6.0.9   | 1         | 1.23%   |
| 6.0.6   | 1         | 1.23%   |
| 6.0.2   | 1         | 1.23%   |
| 6.0.11  | 1         | 1.23%   |
| 5.19.9  | 1         | 1.23%   |
| 5.19.3  | 1         | 1.23%   |
| 5.19.13 | 1         | 1.23%   |
| 5.19.12 | 1         | 1.23%   |
| 5.19.1  | 1         | 1.23%   |
| 5.18.3  | 1         | 1.23%   |
| 5.17.7  | 1         | 1.23%   |
| 5.17.1  | 1         | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 14        | 17.72%  |
| 6.0     | 12        | 15.19%  |
| 6.1     | 9         | 11.39%  |
| 5.15    | 9         | 11.39%  |
| 5.14    | 9         | 11.39%  |
| 6.2     | 7         | 8.86%   |
| 5.19    | 5         | 6.33%   |
| 5.18    | 5         | 6.33%   |
| 5.17    | 4         | 5.06%   |
| 5.10    | 3         | 3.8%    |
| 6.3     | 2         | 2.53%   |

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


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| KDE5   | 70        | 90.91%  |
| GNOME  | 3         | 3.9%    |
| XFCE   | 2         | 2.6%    |
| LeftWM | 1         | 1.3%    |
| KDE    | 1         | 1.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 67        | 87.01%  |
| Wayland | 10        | 12.99%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 54        | 68.35%  |
| Unknown | 14        | 17.72%  |
| LightDM | 10        | 12.66%  |
| GDM     | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 41        | 53.25%  |
| en_IN | 9         | 11.69%  |
| pl_PL | 4         | 5.19%   |
| C     | 4         | 5.19%   |
| ru_RU | 3         | 3.9%    |
| it_IT | 3         | 3.9%    |
| de_DE | 3         | 3.9%    |
| fr_FR | 2         | 2.6%    |
| es_MX | 2         | 2.6%    |
| en_AU | 2         | 2.6%    |
| vi_VN | 1         | 1.3%    |
| es_CL | 1         | 1.3%    |
| en_GB | 1         | 1.3%    |
| en_AG | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 66.23%  |
| BIOS | 26        | 33.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 35        | 45.45%  |
| Xfs     | 28        | 36.36%  |
| Ext4    | 10        | 12.99%  |
| Overlay | 4         | 5.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 54        | 70.13%  |
| Unknown | 14        | 18.18%  |
| MBR     | 9         | 11.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 81.01%  |
| Yes       | 15        | 18.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 64.94%  |
| Yes       | 27        | 35.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 22        | 28.95%  |
| ASUSTek Computer | 16        | 21.05%  |
| Dell             | 13        | 17.11%  |
| Hewlett-Packard  | 10        | 13.16%  |
| Acer             | 4         | 5.26%   |
| MSI              | 3         | 3.95%   |
| HUAWEI           | 2         | 2.63%   |
| Apple            | 2         | 2.63%   |
| Toshiba          | 1         | 1.32%   |
| Pegatron         | 1         | 1.32%   |
| Medion           | 1         | 1.32%   |
| Aquarius         | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 3.95%   |
| Toshiba TECRA A11                          | 1         | 1.32%   |
| Pegatron D15K                              | 1         | 1.32%   |
| MSI Katana GF66 11UE                       | 1         | 1.32%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.32%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.32%   |
| Medion P6816                               | 1         | 1.32%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.32%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.32%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.32%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.32%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 1.32%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.32%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 1.32%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.32%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 1.32%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 1.32%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.32%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.32%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.32%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 1.32%   |
| Lenovo IdeaPad S540-15IML D 81NG           | 1         | 1.32%   |
| Lenovo IdeaPad S340-15IIL 81VW             | 1         | 1.32%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.32%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.32%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.32%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.32%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.32%   |
| Lenovo IdeaPad 3 14IGL05 81WH              | 1         | 1.32%   |
| HUAWEI WRT-WX9                             | 1         | 1.32%   |
| HUAWEI BOM-WXX9                            | 1         | 1.32%   |
| HP ZBook 15 G4                             | 1         | 1.32%   |
| HP Victus by Laptop 16-e0xxx               | 1         | 1.32%   |
| HP ProBook 6565b                           | 1         | 1.32%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 1.32%   |
| HP Notebook                                | 1         | 1.32%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.32%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.32%   |
| HP Laptop 15-da0xxx                        | 1         | 1.32%   |
| HP ENVY Sleekbook 4                        | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 11.84%  |
| Lenovo IdeaPad     | 8         | 10.53%  |
| Dell Latitude      | 5         | 6.58%   |
| Lenovo Legion      | 4         | 5.26%   |
| ASUS VivoBook      | 4         | 5.26%   |
| Acer Aspire        | 4         | 5.26%   |
| HP Laptop          | 3         | 3.95%   |
| Dell Precision     | 3         | 3.95%   |
| ASUS ASUS          | 3         | 3.95%   |
| Dell Inspiron      | 2         | 2.63%   |
| ASUS ROG           | 2         | 2.63%   |
| Toshiba TECRA      | 1         | 1.32%   |
| Pegatron D15K      | 1         | 1.32%   |
| MSI Katana         | 1         | 1.32%   |
| MSI GP73           | 1         | 1.32%   |
| MSI GF63           | 1         | 1.32%   |
| Medion P6816       | 1         | 1.32%   |
| Lenovo Y520-15IKBN | 1         | 1.32%   |
| HUAWEI WRT-WX9     | 1         | 1.32%   |
| HUAWEI BOM-WXX9    | 1         | 1.32%   |
| HP ZBook           | 1         | 1.32%   |
| HP Victus          | 1         | 1.32%   |
| HP ProBook         | 1         | 1.32%   |
| HP Pavilion        | 1         | 1.32%   |
| HP Notebook        | 1         | 1.32%   |
| HP ENVY            | 1         | 1.32%   |
| HP 245             | 1         | 1.32%   |
| Dell Vostro        | 1         | 1.32%   |
| Dell Venue         | 1         | 1.32%   |
| Dell G5            | 1         | 1.32%   |
| ASUS ZenBook       | 1         | 1.32%   |
| ASUS X540LA        | 1         | 1.32%   |
| ASUS X510UNR       | 1         | 1.32%   |
| ASUS UX303LN       | 1         | 1.32%   |
| ASUS TUF           | 1         | 1.32%   |
| ASUS K53SJ         | 1         | 1.32%   |
| ASUS G551JM        | 1         | 1.32%   |
| Aquarius NS585     | 1         | 1.32%   |
| Apple MacBookPro11 | 1         | 1.32%   |
| Apple MacBookAir6  | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 19.74%  |
| 2020 | 12        | 15.79%  |
| 2021 | 10        | 13.16%  |
| 2013 | 7         | 9.21%   |
| 2012 | 7         | 9.21%   |
| 2018 | 6         | 7.89%   |
| 2017 | 5         | 6.58%   |
| 2015 | 4         | 5.26%   |
| 2011 | 3         | 3.95%   |
| 2016 | 2         | 2.63%   |
| 2014 | 2         | 2.63%   |
| 2022 | 1         | 1.32%   |
| 2010 | 1         | 1.32%   |
| 2008 | 1         | 1.32%   |

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


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 36.84%  |
| 16.01-24.0  | 16        | 21.05%  |
| 8.01-16.0   | 14        | 18.42%  |
| 3.01-4.0    | 12        | 15.79%  |
| 32.01-64.0  | 3         | 3.95%   |
| 24.01-32.0  | 2         | 2.63%   |
| 64.01-256.0 | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 28        | 35.44%  |
| 1.01-2.0   | 19        | 24.05%  |
| 4.01-8.0   | 17        | 21.52%  |
| 3.01-4.0   | 12        | 15.19%  |
| 16.01-24.0 | 1         | 1.27%   |
| 8.01-16.0  | 1         | 1.27%   |
| 0.51-1.0   | 1         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 68.83%  |
| 2      | 22        | 28.57%  |
| 4      | 1         | 1.3%    |
| 3      | 1         | 1.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 81.58%  |
| Yes       | 14        | 18.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 73.68%  |
| No        | 20        | 26.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 96.05%  |
| No        | 3         | 3.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 85.53%  |
| No        | 11        | 14.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 16.88%  |
| India                  | 11        | 14.29%  |
| Germany                | 6         | 7.79%   |
| France                 | 5         | 6.49%   |
| Poland                 | 4         | 5.19%   |
| Italy                  | 4         | 5.19%   |
| Russia                 | 3         | 3.9%    |
| Turkey                 | 2         | 2.6%    |
| Pakistan               | 2         | 2.6%    |
| Norway                 | 2         | 2.6%    |
| Greece                 | 2         | 2.6%    |
| Chile                  | 2         | 2.6%    |
| Canada                 | 2         | 2.6%    |
| Australia              | 2         | 2.6%    |
| Zambia                 | 1         | 1.3%    |
| Vietnam                | 1         | 1.3%    |
| Togo                   | 1         | 1.3%    |
| Sweden                 | 1         | 1.3%    |
| Romania                | 1         | 1.3%    |
| Palestinian Territory  | 1         | 1.3%    |
| Netherlands            | 1         | 1.3%    |
| Morocco                | 1         | 1.3%    |
| Mongolia               | 1         | 1.3%    |
| Mexico                 | 1         | 1.3%    |
| Malaysia               | 1         | 1.3%    |
| Lebanon                | 1         | 1.3%    |
| Indonesia              | 1         | 1.3%    |
| Hungary                | 1         | 1.3%    |
| Egypt                  | 1         | 1.3%    |
| Colombia               | 1         | 1.3%    |
| Bosnia and Herzegovina | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Longmont     | 3         | 3.9%    |
| Pune         | 2         | 2.6%    |
| Madurai      | 2         | 2.6%    |
| Istanbul     | 2         | 2.6%    |
| Zenica       | 1         | 1.3%    |
| Warsaw       | 1         | 1.3%    |
| Ulan Bator   | 1         | 1.3%    |
| Ufa          | 1         | 1.3%    |
| Toronto      | 1         | 1.3%    |
| Taranto      | 1         | 1.3%    |
| Tangerang    | 1         | 1.3%    |
| Stuttgart    | 1         | 1.3%    |
| Stockholm    | 1         | 1.3%    |
| Stavropol    | 1         | 1.3%    |
| Stagno       | 1         | 1.3%    |
| Seattle      | 1         | 1.3%    |
| Santa Cruz   | 1         | 1.3%    |
| Ramallah     | 1         | 1.3%    |
| Poznan       | 1         | 1.3%    |
| Porcia       | 1         | 1.3%    |
| Pirmasens    | 1         | 1.3%    |
| Phoenix      | 1         | 1.3%    |
| Perth        | 1         | 1.3%    |
| Pavia        | 1         | 1.3%    |
| Paris        | 1         | 1.3%    |
| Oslo         | 1         | 1.3%    |
| Neu-Ulm      | 1         | 1.3%    |
| Mumbai       | 1         | 1.3%    |
| Melbourne    | 1         | 1.3%    |
| Medellín    | 1         | 1.3%    |
| Magdeburg    | 1         | 1.3%    |
| Lyon         | 1         | 1.3%    |
| Lusaka       | 1         | 1.3%    |
| Lucknow      | 1         | 1.3%    |
| Lublin       | 1         | 1.3%    |
| Longvic      | 1         | 1.3%    |
| Lomé        | 1         | 1.3%    |
| Lamia        | 1         | 1.3%    |
| Lahore       | 1         | 1.3%    |
| Kuala Lumpur | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 19        | 20     | 18.81%  |
| Seagate                     | 16        | 19     | 15.84%  |
| WDC                         | 8         | 9      | 7.92%   |
| Toshiba                     | 7         | 7      | 6.93%   |
| Kingston                    | 5         | 6      | 4.95%   |
| Intel                       | 5         | 5      | 4.95%   |
| SanDisk                     | 4         | 4      | 3.96%   |
| HGST                        | 4         | 4      | 3.96%   |
| SK hynix                    | 3         | 3      | 2.97%   |
| Micron Technology           | 3         | 4      | 2.97%   |
| KIOXIA                      | 3         | 4      | 2.97%   |
| Unknown                     | 2         | 2      | 1.98%   |
| Transcend                   | 2         | 2      | 1.98%   |
| Crucial                     | 2         | 2      | 1.98%   |
| Apple                       | 2         | 2      | 1.98%   |
| Vaseky                      | 1         | 1      | 0.99%   |
| Plextor                     | 1         | 1      | 0.99%   |
| Phison Electronics          | 1         | 1      | 0.99%   |
| Phison                      | 1         | 1      | 0.99%   |
| OSCOO                       | 1         | 1      | 0.99%   |
| Micron/Crucial Technology   | 1         | 1      | 0.99%   |
| LITEONIT                    | 1         | 1      | 0.99%   |
| LITEON                      | 1         | 1      | 0.99%   |
| Kingston Technology Company | 1         | 1      | 0.99%   |
| Intenso                     | 1         | 1      | 0.99%   |
| Inateck                     | 1         | 1      | 0.99%   |
| Hitachi                     | 1         | 1      | 0.99%   |
| GOODRAM                     | 1         | 1      | 0.99%   |
| China                       | 1         | 1      | 0.99%   |
| Biostar                     | 1         | 1      | 0.99%   |
| Apacer                      | 1         | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 2.94%   |
| Seagate One Touch HDD 5TB                           | 3         | 2.94%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.96%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 1.96%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 1.96%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 1.96%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.98%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.98%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.98%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 0.98%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB                | 1         | 0.98%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB                | 1         | 0.98%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.98%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB                | 1         | 0.98%   |
| Vaseky V800/256G 256GB SSD                          | 1         | 0.98%   |
| Unknown MMC Card  64GB                              | 1         | 0.98%   |
| Unknown G1J38E  64GB                                | 1         | 0.98%   |
| Transcend TS512GMTS430S 512GB SSD                   | 1         | 0.98%   |
| Transcend TS256GMTS400 256GB SSD                    | 1         | 0.98%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 0.98%   |
| Toshiba MQ01ABF050M 500GB                           | 1         | 0.98%   |
| Toshiba MK2555GSX 250GB                             | 1         | 0.98%   |
| Toshiba KBG40ZNT512G MEMORY 512GB                   | 1         | 0.98%   |
| Toshiba KBG30ZMV256G 256GB                          | 1         | 0.98%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.98%   |
| SK hynix BC711 NVMe 512GB                           | 1         | 0.98%   |
| SK hynix BC711 NVMe 128GB                           | 1         | 0.98%   |
| Seagate ST9500325AS 500GB                           | 1         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 0.98%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 0.98%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 0.98%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB          | 1         | 0.98%   |
| Seagate Expansion 1TB                               | 1         | 0.98%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB        | 1         | 0.98%   |
| SanDisk SD8SB8U-256G-1006 256GB SSD                 | 1         | 0.98%   |
| Sandisk PC SN520 NVMe SSD 256GB                     | 1         | 0.98%   |
| SanDisk NVMe SSD Drive 256GB                        | 1         | 0.98%   |
| Samsung SSD SM841 mSATA 128GB                       | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 18     | 59.26%  |
| Toshiba | 4         | 4      | 14.81%  |
| HGST    | 4         | 4      | 14.81%  |
| WDC     | 2         | 2      | 7.41%   |
| Hitachi | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 25%     |
| Transcend           | 2         | 2      | 7.14%   |
| Kingston            | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| Apple               | 2         | 2      | 7.14%   |
| WDC                 | 1         | 1      | 3.57%   |
| Vaseky              | 1         | 1      | 3.57%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Plextor             | 1         | 1      | 3.57%   |
| OSCOO               | 1         | 1      | 3.57%   |
| LITEONIT            | 1         | 1      | 3.57%   |
| LITEON              | 1         | 1      | 3.57%   |
| Intenso             | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| GOODRAM             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| Biostar             | 1         | 1      | 3.57%   |
| Apacer              | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 40        | 50     | 43.48%  |
| HDD  | 26        | 29     | 28.26%  |
| SSD  | 24        | 28     | 26.09%  |
| MMC  | 2         | 2      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 53     | 47.78%  |
| NVMe | 40        | 49     | 44.44%  |
| SAS  | 5         | 5      | 5.56%   |
| MMC  | 2         | 2      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 23        | 25     | 46%     |
| 0.01-0.5   | 23        | 28     | 46%     |
| 4.01-10.0  | 3         | 3      | 6%      |
| 1.01-2.0   | 1         | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 17.95%  |
| More than 3000 | 13        | 16.67%  |
| 1001-2000      | 13        | 16.67%  |
| 101-250        | 11        | 14.1%   |
| 501-1000       | 8         | 10.26%  |
| Unknown        | 7         | 8.97%   |
| 51-100         | 6         | 7.69%   |
| 1-20           | 3         | 3.85%   |
| 21-50          | 2         | 2.56%   |
| 2001-3000      | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 19.23%  |
| 51-100         | 15        | 19.23%  |
| 1-20           | 14        | 17.95%  |
| 21-50          | 12        | 15.38%  |
| Unknown        | 7         | 8.97%   |
| 251-500        | 6         | 7.69%   |
| 501-1000       | 4         | 5.13%   |
| 2001-3000      | 3         | 3.85%   |
| More than 3000 | 1         | 1.28%   |
| 1001-2000      | 1         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 10%     |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 10%     |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 10%     |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 10%     |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 10%     |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 10%     |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 10%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 10%     |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 10%     |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 40%     |
| Toshiba             | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| Toshiba | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 90%     |
| NVMe | 1         | 1      | 10%     |

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
| Works    | 55        | 73     | 67.07%  |
| Detected | 17        | 26     | 20.73%  |
| Malfunc  | 10        | 10     | 12.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 57        | 53.77%  |
| Samsung Electronics          | 14        | 13.21%  |
| AMD                          | 8         | 7.55%   |
| SanDisk                      | 7         | 6.6%    |
| Kingston Technology Company  | 4         | 3.77%   |
| Toshiba America Info Systems | 3         | 2.83%   |
| SK hynix                     | 3         | 2.83%   |
| Micron Technology            | 3         | 2.83%   |
| KIOXIA                       | 3         | 2.83%   |
| Phison Electronics           | 2         | 1.89%   |
| Seagate Technology           | 1         | 0.94%   |
| Micron/Crucial Technology    | 1         | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 7.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 6.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 5.5%    |
| Samsung NVMe SSD Controller 980                                                | 5         | 4.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.67%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 2.75%   |
| Micron NVMe Storage Controller                                                 | 3         | 2.75%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 2.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.75%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.83%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.83%   |
| SanDisk NVMe Controller                                                        | 2         | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.83%   |
| Samsung Apple PCIe SSD                                                         | 2         | 1.83%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.83%   |
| Intel SSD 660P Series                                                          | 2         | 1.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.92%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.92%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.92%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.92%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.92%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.92%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.92%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 50%     |
| NVMe | 40        | 37.74%  |
| RAID | 13        | 12.26%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 82.89%  |
| AMD    | 13        | 17.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 3.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 3.95%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 3.95%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 2.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 2.63%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 2.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 2.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.63%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 2.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.32%   |
| Intel Core i7-4960HQ CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.32%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.32%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.32%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.32%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 1.32%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 23        | 30.26%  |
| Intel Core i5    | 22        | 28.95%  |
| Other            | 10        | 13.16%  |
| AMD Ryzen 5      | 6         | 7.89%   |
| Intel Core i3    | 5         | 6.58%   |
| AMD Ryzen 7      | 3         | 3.95%   |
| Intel Celeron    | 2         | 2.63%   |
| AMD Ryzen 3      | 2         | 2.63%   |
| Intel Core 2 Duo | 1         | 1.32%   |
| AMD A6           | 1         | 1.32%   |
| AMD A4           | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 35        | 46.05%  |
| 2      | 29        | 38.16%  |
| 6      | 7         | 9.21%   |
| 8      | 4         | 5.26%   |
| 14     | 1         | 1.32%   |

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
| 2      | 70        | 90.91%  |
| 1      | 7         | 9.09%   |

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
| Unknown    | 23        | 29.49%  |
| 0x806c1    | 7         | 8.97%   |
| 0x806ec    | 6         | 7.69%   |
| 0x306a9    | 4         | 5.13%   |
| 0x906ea    | 3         | 3.85%   |
| 0x906e9    | 3         | 3.85%   |
| 0x806e9    | 3         | 3.85%   |
| 0x206a7    | 3         | 3.85%   |
| 0x08108109 | 3         | 3.85%   |
| 0x806eb    | 2         | 2.56%   |
| 0x706a8    | 2         | 2.56%   |
| 0x40651    | 2         | 2.56%   |
| 0xa0652    | 1         | 1.28%   |
| 0x906ed    | 1         | 1.28%   |
| 0x906eb    | 1         | 1.28%   |
| 0x906a3    | 1         | 1.28%   |
| 0x806d1    | 1         | 1.28%   |
| 0x706e5    | 1         | 1.28%   |
| 0x406e3    | 1         | 1.28%   |
| 0x40661    | 1         | 1.28%   |
| 0x306d4    | 1         | 1.28%   |
| 0x306c3    | 1         | 1.28%   |
| 0x20652    | 1         | 1.28%   |
| 0x1067a    | 1         | 1.28%   |
| 0x08608103 | 1         | 1.28%   |
| 0x08600106 | 1         | 1.28%   |
| 0x08108102 | 1         | 1.28%   |
| 0x06006705 | 1         | 1.28%   |
| 0x03000027 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 28.95%  |
| Haswell          | 10        | 13.16%  |
| TigerLake        | 8         | 10.53%  |
| IvyBridge        | 6         | 7.89%   |
| Zen+             | 5         | 6.58%   |
| Zen 2            | 3         | 3.95%   |
| SandyBridge      | 3         | 3.95%   |
| IceLake          | 3         | 3.95%   |
| Broadwell        | 3         | 3.95%   |
| Zen 3            | 2         | 2.63%   |
| Goldmont plus    | 2         | 2.63%   |
| CometLake        | 2         | 2.63%   |
| Westmere         | 1         | 1.32%   |
| Skylake          | 1         | 1.32%   |
| Penryn           | 1         | 1.32%   |
| K10 Llano        | 1         | 1.32%   |
| Excavator        | 1         | 1.32%   |
| Alderlake Hybrid | 1         | 1.32%   |
| Unknown          | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 53.45%  |
| Nvidia | 39        | 33.62%  |
| AMD    | 15        | 12.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 2.56%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.56%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 2.56%   |
| Intel UHD Graphics 620                                                    | 3         | 2.56%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.56%   |
| Intel HD Graphics 630                                                     | 3         | 2.56%   |
| Intel HD Graphics 620                                                     | 3         | 2.56%   |
| Intel HD Graphics 5500                                                    | 3         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.56%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.71%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.71%   |
| AMD Renoir                                                                | 2         | 1.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.71%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.85%   |
| Nvidia TU117M                                                             | 1         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.85%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.85%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.85%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.85%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.85%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 32        | 42.11%  |
| 1 x Intel      | 26        | 34.21%  |
| 1 x AMD        | 6         | 7.89%   |
| AMD + Nvidia   | 5         | 6.58%   |
| Intel + AMD    | 3         | 3.95%   |
| 1 x Nvidia     | 2         | 2.63%   |
| 2 x Intel      | 1         | 1.32%   |
| 2 x AMD        | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 66.23%  |
| Proprietary | 26        | 33.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 72.73%  |
| 1.01-2.0   | 9         | 11.69%  |
| 0.01-0.5   | 5         | 6.49%   |
| 5.01-6.0   | 3         | 3.9%    |
| 3.01-4.0   | 3         | 3.9%    |
| 0.51-1.0   | 1         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 19        | 21.11%  |
| Chimei Innolux      | 14        | 15.56%  |
| BOE                 | 14        | 15.56%  |
| LG Display          | 13        | 14.44%  |
| Samsung Electronics | 10        | 11.11%  |
| PANDA               | 3         | 3.33%   |
| Apple               | 3         | 3.33%   |
| Sharp               | 2         | 2.22%   |
| Dell                | 2         | 2.22%   |
| Toshiba             | 1         | 1.11%   |
| TMX                 | 1         | 1.11%   |
| Sceptre Tech        | 1         | 1.11%   |
| LGD                 | 1         | 1.11%   |
| Lenovo              | 1         | 1.11%   |
| ITE                 | 1         | 1.11%   |
| Goldstar            | 1         | 1.11%   |
| CSO                 | 1         | 1.11%   |
| BenQ                | 1         | 1.11%   |
| Acer                | 1         | 1.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 3.33%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 2.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 2.22%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 2.22%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 1.11%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 1.11%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.11%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.11%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.11%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.11%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 1.11%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 1.11%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 1.11%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.11%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 1.11%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.11%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 1.11%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 1.11%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.11%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.11%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.11%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 1.11%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.11%   |
| ITE DP2VGA V207 ITE6516 1680x1050 600x340mm 27.2-inch                   | 1         | 1.11%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                   | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 62.35%  |
| 1366x768 (WXGA)    | 18        | 21.18%  |
| 3840x2160 (4K)     | 3         | 3.53%   |
| 1600x900 (HD+)     | 3         | 3.53%   |
| 3840x2400          | 1         | 1.18%   |
| 3200x1800 (QHD+)   | 1         | 1.18%   |
| 2880x1800          | 1         | 1.18%   |
| 2560x1080          | 1         | 1.18%   |
| 2160x1440          | 1         | 1.18%   |
| 1920x1200 (WUXGA)  | 1         | 1.18%   |
| 1680x1050 (WSXGA+) | 1         | 1.18%   |
| 1440x900 (WXGA+)   | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 53.93%  |
| 14      | 11        | 12.36%  |
| 13      | 9         | 10.11%  |
| 23      | 4         | 4.49%   |
| 84      | 3         | 3.37%   |
| 27      | 2         | 2.25%   |
| 21      | 2         | 2.25%   |
| 17      | 2         | 2.25%   |
| 72      | 1         | 1.12%   |
| 31      | 1         | 1.12%   |
| 28      | 1         | 1.12%   |
| 24      | 1         | 1.12%   |
| 18      | 1         | 1.12%   |
| 16      | 1         | 1.12%   |
| 12      | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 72.22%  |
| 501-600     | 7         | 7.78%   |
| 401-500     | 4         | 4.44%   |
| 201-300     | 4         | 4.44%   |
| 1501-2000   | 4         | 4.44%   |
| 351-400     | 3         | 3.33%   |
| 601-700     | 2         | 2.22%   |
| Unknown     | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 70        | 90.91%  |
| 16/10   | 4         | 5.19%   |
| 3/2     | 1         | 1.3%    |
| 21/9    | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 55.68%  |
| 81-90          | 18        | 20.45%  |
| 201-250        | 6         | 6.82%   |
| More than 1000 | 4         | 4.55%   |
| 71-80          | 2         | 2.27%   |
| 301-350        | 2         | 2.27%   |
| 121-130        | 2         | 2.27%   |
| 61-70          | 1         | 1.14%   |
| 351-500        | 1         | 1.14%   |
| 251-300        | 1         | 1.14%   |
| 141-150        | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 54.55%  |
| 101-120       | 19        | 21.59%  |
| 51-100        | 13        | 14.77%  |
| 161-240       | 4         | 4.55%   |
| More than 240 | 2         | 2.27%   |
| 1-50          | 1         | 1.14%   |
| Unknown       | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 62        | 81.58%  |
| 2     | 13        | 17.11%  |
| 3     | 1         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 47        | 42.73%  |
| Realtek Semiconductor             | 38        | 34.55%  |
| Qualcomm Atheros                  | 7         | 6.36%   |
| Broadcom Limited                  | 4         | 3.64%   |
| MediaTek                          | 3         | 2.73%   |
| ASIX Electronics                  | 3         | 2.73%   |
| Samsung Electronics               | 2         | 1.82%   |
| Ericsson Business Mobile Networks | 2         | 1.82%   |
| Broadcom                          | 2         | 1.82%   |
| Ralink                            | 1         | 0.91%   |
| Marvell Technology Group          | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 27        | 20%     |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 6         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 5         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 5         | 3.7%    |
| Intel Wireless 7260                                                | 5         | 3.7%    |
| Intel Wireless 8265 / 8275                                         | 4         | 2.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 4         | 2.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 3         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 3         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 2.22%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 2.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.48%   |
| Intel Wi-Fi 6 AX200                                                | 2         | 1.48%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.48%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.48%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller               | 1         | 0.74%   |
| Intel Wireless-AC 9260                                             | 1         | 0.74%   |
| Intel Wireless 8260                                                | 1         | 0.74%   |
| Intel Wireless 7265                                                | 1         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 0.74%   |
| Intel Ethernet Connection I219-V                                   | 1         | 0.74%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                               | 1         | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                              | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 63.01%  |
| Realtek Semiconductor | 12        | 16.44%  |
| Qualcomm Atheros      | 6         | 8.22%   |
| Broadcom Limited      | 4         | 5.48%   |
| MediaTek              | 3         | 4.11%   |
| Ralink                | 1         | 1.37%   |
| Broadcom              | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 6         | 8.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 6.85%   |
| Intel Wireless 7260                                           | 5         | 6.85%   |
| Intel Wireless 8265 / 8275                                    | 4         | 5.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 5.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 5.48%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 5.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 4.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 4.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 4.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 2.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 2.74%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 2.74%   |
| Intel Centrino Wireless-N 2230                                | 2         | 2.74%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 2         | 2.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.37%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.37%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 1.37%   |
| Intel Wireless-AC 9260                                        | 1         | 1.37%   |
| Intel Wireless 8260                                           | 1         | 1.37%   |
| Intel Wireless 7265                                           | 1         | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.37%   |
| Intel Centrino Wireless-N 2200                                | 1         | 1.37%   |
| Intel Centrino Wireless-N 100                                 | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 1.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 1.37%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 1.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1         | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 34        | 59.65%  |
| Intel                    | 17        | 29.82%  |
| ASIX Electronics         | 3         | 5.26%   |
| Qualcomm Atheros         | 1         | 1.75%   |
| Marvell Technology Group | 1         | 1.75%   |
| Broadcom                 | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 46.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10.34%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 8.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.72%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.72%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.72%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.72%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 54.89%  |
| Ethernet | 56        | 42.11%  |
| Modem    | 4         | 3.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 82.05%  |
| Ethernet | 14        | 17.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 61.84%  |
| 1     | 28        | 36.84%  |
| 0     | 1         | 1.32%   |

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
| Intel                           | 36        | 55.38%  |
| Realtek Semiconductor           | 7         | 10.77%  |
| IMC Networks                    | 5         | 7.69%   |
| Broadcom                        | 5         | 7.69%   |
| Qualcomm Atheros Communications | 3         | 4.62%   |
| Lite-On Technology              | 2         | 3.08%   |
| Foxconn / Hon Hai               | 2         | 3.08%   |
| Apple                           | 2         | 3.08%   |
| Toshiba                         | 1         | 1.54%   |
| Realtek                         | 1         | 1.54%   |
| Dell                            | 1         | 1.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 14        | 21.54%  |
| Intel Bluetooth wireless interface             | 9         | 13.85%  |
| Intel AX201 Bluetooth                          | 8         | 12.31%  |
| Realtek Bluetooth Radio                        | 4         | 6.15%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 4.62%   |
| Qualcomm Atheros  Bluetooth Device             | 3         | 4.62%   |
| IMC Networks Bluetooth Radio                   | 3         | 4.62%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 2         | 3.08%   |
| Intel AX200 Bluetooth                          | 2         | 3.08%   |
| IMC Networks Wireless_Device                   | 2         | 3.08%   |
| Broadcom BCM20702A0 Bluetooth                  | 2         | 3.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 3.08%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 1.54%   |
| Realtek Bluetooth Radio                        | 1         | 1.54%   |
| Lite-On Bluetooth Device                       | 1         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.54%   |
| Dell BCM20702A0 Bluetooth Module               | 1         | 1.54%   |
| Broadcom BCM2045A0                             | 1         | 1.54%   |
| Apple Bluetooth USB Host Controller            | 1         | 1.54%   |
| Apple Bluetooth Host Controller                | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 63        | 60.58%  |
| Nvidia                     | 20        | 19.23%  |
| AMD                        | 13        | 12.5%   |
| GN Netcom                  | 2         | 1.92%   |
| Samsung Electronics        | 1         | 0.96%   |
| Realtek Semiconductor      | 1         | 0.96%   |
| PreSonus Audio Electronics | 1         | 0.96%   |
| Lenovo                     | 1         | 0.96%   |
| Barco Display Systems      | 1         | 0.96%   |
| ASUSTek Computer           | 1         | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 7.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 6.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 3.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 3.97%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.38%   |
| Intel CM238 HD Audio Controller                                            | 3         | 2.38%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.59%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.79%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.79%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.79%   |
| Nvidia Audio device                                                        | 1         | 0.79%   |
| Lenovo USB Headset                                                         | 1         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.79%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 35.9%   |
| SK hynix            | 23        | 29.49%  |
| Micron Technology   | 10        | 12.82%  |
| Crucial             | 7         | 8.97%   |
| Ramaxel Technology  | 4         | 5.13%   |
| Kingston            | 3         | 3.85%   |
| Nanya Technology    | 1         | 1.28%   |
| Elpida              | 1         | 1.28%   |
| Corsair             | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 4.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 3.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 2.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.47%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 2.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 2.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.23%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.23%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.23%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.23%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.23%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.23%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.23%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 1.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.23%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.23%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.23%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 38        | 59.38%  |
| DDR3   | 19        | 29.69%  |
| LPDDR4 | 2         | 3.13%   |
| LPDDR3 | 2         | 3.13%   |
| SDRAM  | 1         | 1.56%   |
| DDR5   | 1         | 1.56%   |
| DDR    | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 84.85%  |
| Row Of Chips | 10        | 15.15%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 34        | 49.28%  |
| 4096  | 24        | 34.78%  |
| 16384 | 8         | 11.59%  |
| 2048  | 3         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 25        | 33.78%  |
| 1600  | 15        | 20.27%  |
| 3200  | 14        | 18.92%  |
| 3266  | 4         | 5.41%   |
| 2400  | 3         | 4.05%   |
| 2133  | 3         | 4.05%   |
| 1333  | 3         | 4.05%   |
| 4267  | 2         | 2.7%    |
| 4800  | 1         | 1.35%   |
| 4199  | 1         | 1.35%   |
| 1334  | 1         | 1.35%   |
| 1067  | 1         | 1.35%   |
| 800   | 1         | 1.35%   |

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
| IMC Networks                           | 18        | 25.35%  |
| Chicony Electronics                    | 13        | 18.31%  |
| Realtek Semiconductor                  | 6         | 8.45%   |
| Acer                                   | 6         | 8.45%   |
| Syntek                                 | 5         | 7.04%   |
| Quanta                                 | 4         | 5.63%   |
| Microdia                               | 4         | 5.63%   |
| Sunplus Innovation Technology          | 3         | 4.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.23%   |
| Bison Electronics                      | 3         | 4.23%   |
| Suyin                                  | 1         | 1.41%   |
| Sonix Technology                       | 1         | 1.41%   |
| Ricoh                                  | 1         | 1.41%   |
| Luxvisions Innotech Limited            | 1         | 1.41%   |
| Lite-On Technology                     | 1         | 1.41%   |
| Alpha Imaging Technology               | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 5         | 7.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 7.04%   |
| IMC Networks Integrated Camera                      | 5         | 7.04%   |
| Realtek Integrated_Webcam_HD                        | 3         | 4.23%   |
| Quanta HP TrueVision HD Camera                      | 3         | 4.23%   |
| Chicony Integrated Camera                           | 3         | 4.23%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.82%   |
| Bison ThinkPad Integrated Camera                    | 2         | 2.82%   |
| Acer Integrated Camera                              | 2         | 2.82%   |
| Acer HD Webcam                                      | 2         | 2.82%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.41%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.41%   |
| Sunplus HP Truevision HD                            | 1         | 1.41%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.41%   |
| Ricoh Integrated Webcam                             | 1         | 1.41%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.41%   |
| Realtek Integrated Webcam                           | 1         | 1.41%   |
| Realtek Built-In Video Camera                       | 1         | 1.41%   |
| Quanta HD User Facing                               | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.41%   |
| Lite-On Integrated Camera                           | 1         | 1.41%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.41%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.41%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.41%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.41%   |
| IMC Networks HD Camera                              | 1         | 1.41%   |
| IMC Networks EasyCamera                             | 1         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.41%   |
| Chicony USB2.0 UVC WebCam                           | 1         | 1.41%   |
| Chicony USB 2.0 Camera                              | 1         | 1.41%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.41%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.41%   |
| Chicony HP Webcam                                   | 1         | 1.41%   |
| Chicony HD WebCam (Acer)                            | 1         | 1.41%   |
| Chicony HD WebCam                                   | 1         | 1.41%   |
| Chicony HD User Facing                              | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Elan Microelectronics      | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 2         | 22.22%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 11.11%  |
| Synaptics WBDI                                    | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 11.11%  |
| Elan ELAN:Fingerprint                             | 1         | 11.11%  |
| AuthenTec Fingerprint Sensor                      | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 33.33%  |
| Upek        | 2         | 22.22%  |
| Alcor Micro | 2         | 22.22%  |
| Yubico.com  | 1         | 11.11%  |
| Clay Logic  | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 22.22%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 11.11%  |
| Clay Logic Nitrokey Pro                                    | 1         | 11.11%  |
| Broadcom 58200                                             | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 51        | 66.23%  |
| 1     | 20        | 25.97%  |
| 2     | 6         | 7.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 28.13%  |
| Graphics card         | 8         | 25%     |
| Chipcard              | 7         | 21.88%  |
| Multimedia controller | 4         | 12.5%   |
| Camera                | 2         | 6.25%   |
| Storage               | 1         | 3.13%   |
| Network               | 1         | 3.13%   |

