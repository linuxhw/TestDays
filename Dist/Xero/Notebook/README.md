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

Total: 96

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Xero Rolling | 67        | 89.33%  |
| Xero         | 8         | 10.67%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 74        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.0.12-arch1-1   | 4         | 5.06%   |
| 5.16.15-arch1-1  | 4         | 5.06%   |
| 6.2.6-arch1-1    | 3         | 3.8%    |
| 6.1.1-arch1-1    | 3         | 3.8%    |
| 6.2.7-arch1-1    | 2         | 2.53%   |
| 6.0.7-arch1-1    | 2         | 2.53%   |
| 5.18.16-arch1-1  | 2         | 2.53%   |
| 5.18.11-arch1-1  | 2         | 2.53%   |
| 5.17.9-arch1-1   | 2         | 2.53%   |
| 5.16.8-arch1-1   | 2         | 2.53%   |
| 5.16.2-arch1-1   | 2         | 2.53%   |
| 5.16.1-arch1-1   | 2         | 2.53%   |
| 5.15.33-1-lts    | 2         | 2.53%   |
| 5.14.14-arch1-1  | 2         | 2.53%   |
| 6.2.8-arch1-1    | 1         | 1.27%   |
| 6.2.2-arch2-1    | 1         | 1.27%   |
| 6.1.8-arch1-1    | 1         | 1.27%   |
| 6.1.7-arch1-1    | 1         | 1.27%   |
| 6.1.6-arch1-1    | 1         | 1.27%   |
| 6.1.4-arch1-1    | 1         | 1.27%   |
| 6.1.3-zen1-1-zen | 1         | 1.27%   |
| 6.1.15-1-lts     | 1         | 1.27%   |
| 6.1.12-arch1-1   | 1         | 1.27%   |
| 6.0.9-arch1-1    | 1         | 1.27%   |
| 6.0.8-zen1-1-zen | 1         | 1.27%   |
| 6.0.8-arch1-1    | 1         | 1.27%   |
| 6.0.6-arch1-1    | 1         | 1.27%   |
| 6.0.2-arch1-1    | 1         | 1.27%   |
| 6.0.11-arch1-1   | 1         | 1.27%   |
| 5.19.9-arch1-1   | 1         | 1.27%   |
| 5.19.3-arch1-1   | 1         | 1.27%   |
| 5.19.13-arch1-1  | 1         | 1.27%   |
| 5.19.12-arch1-1  | 1         | 1.27%   |
| 5.19.1-arch2-1   | 1         | 1.27%   |
| 5.18.3-arch1-1   | 1         | 1.27%   |
| 5.17.7-arch1-1   | 1         | 1.27%   |
| 5.17.1-arch1-1   | 1         | 1.27%   |
| 5.16.16-arch1-1  | 1         | 1.27%   |
| 5.16.14-arch1-1  | 1         | 1.27%   |
| 5.16.13-arch1-1  | 1         | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.12  | 4         | 5.06%   |
| 5.16.15 | 4         | 5.06%   |
| 6.2.6   | 3         | 3.8%    |
| 6.1.1   | 3         | 3.8%    |
| 5.14.16 | 3         | 3.8%    |
| 5.14.14 | 3         | 3.8%    |
| 6.2.7   | 2         | 2.53%   |
| 6.0.8   | 2         | 2.53%   |
| 6.0.7   | 2         | 2.53%   |
| 5.18.16 | 2         | 2.53%   |
| 5.18.11 | 2         | 2.53%   |
| 5.17.9  | 2         | 2.53%   |
| 5.16.8  | 2         | 2.53%   |
| 5.16.2  | 2         | 2.53%   |
| 5.16.1  | 2         | 2.53%   |
| 5.15.33 | 2         | 2.53%   |
| 5.14.8  | 2         | 2.53%   |
| 6.2.8   | 1         | 1.27%   |
| 6.2.2   | 1         | 1.27%   |
| 6.1.8   | 1         | 1.27%   |
| 6.1.7   | 1         | 1.27%   |
| 6.1.6   | 1         | 1.27%   |
| 6.1.4   | 1         | 1.27%   |
| 6.1.3   | 1         | 1.27%   |
| 6.1.15  | 1         | 1.27%   |
| 6.1.12  | 1         | 1.27%   |
| 6.0.9   | 1         | 1.27%   |
| 6.0.6   | 1         | 1.27%   |
| 6.0.2   | 1         | 1.27%   |
| 6.0.11  | 1         | 1.27%   |
| 5.19.9  | 1         | 1.27%   |
| 5.19.3  | 1         | 1.27%   |
| 5.19.13 | 1         | 1.27%   |
| 5.19.12 | 1         | 1.27%   |
| 5.19.1  | 1         | 1.27%   |
| 5.18.3  | 1         | 1.27%   |
| 5.17.7  | 1         | 1.27%   |
| 5.17.1  | 1         | 1.27%   |
| 5.16.16 | 1         | 1.27%   |
| 5.16.14 | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 14        | 18.18%  |
| 6.0     | 12        | 15.58%  |
| 6.1     | 9         | 11.69%  |
| 5.15    | 9         | 11.69%  |
| 5.14    | 9         | 11.69%  |
| 6.2     | 7         | 9.09%   |
| 5.19    | 5         | 6.49%   |
| 5.18    | 5         | 6.49%   |
| 5.17    | 4         | 5.19%   |
| 5.10    | 3         | 3.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 74        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| KDE5   | 68        | 90.67%  |
| GNOME  | 3         | 4%      |
| XFCE   | 2         | 2.67%   |
| LeftWM | 1         | 1.33%   |
| KDE    | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 65        | 86.67%  |
| Wayland | 10        | 13.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 52        | 67.53%  |
| Unknown | 14        | 18.18%  |
| LightDM | 10        | 12.99%  |
| GDM     | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 40        | 53.33%  |
| en_IN | 9         | 12%     |
| pl_PL | 4         | 5.33%   |
| C     | 4         | 5.33%   |
| ru_RU | 3         | 4%      |
| it_IT | 3         | 4%      |
| de_DE | 3         | 4%      |
| fr_FR | 2         | 2.67%   |
| es_MX | 2         | 2.67%   |
| en_AU | 2         | 2.67%   |
| vi_VN | 1         | 1.33%   |
| en_GB | 1         | 1.33%   |
| en_AG | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 49        | 65.33%  |
| BIOS | 26        | 34.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 35        | 46.67%  |
| Xfs     | 26        | 34.67%  |
| Ext4    | 10        | 13.33%  |
| Overlay | 4         | 5.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 52        | 69.33%  |
| Unknown | 14        | 18.67%  |
| MBR     | 9         | 12%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 81.82%  |
| Yes       | 14        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 48        | 64%     |
| Yes       | 27        | 36%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 22        | 29.73%  |
| ASUSTek Computer | 16        | 21.62%  |
| Dell             | 13        | 17.57%  |
| Hewlett-Packard  | 10        | 13.51%  |
| MSI              | 3         | 4.05%   |
| HUAWEI           | 2         | 2.7%    |
| Apple            | 2         | 2.7%    |
| Acer             | 2         | 2.7%    |
| Toshiba          | 1         | 1.35%   |
| Pegatron         | 1         | 1.35%   |
| Medion           | 1         | 1.35%   |
| Aquarius         | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 4.05%   |
| Toshiba TECRA A11                          | 1         | 1.35%   |
| Pegatron D15K                              | 1         | 1.35%   |
| MSI Katana GF66 11UE                       | 1         | 1.35%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.35%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.35%   |
| Medion P6816                               | 1         | 1.35%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.35%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.35%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.35%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 1.35%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.35%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 1.35%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.35%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 1.35%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 1.35%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.35%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.35%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.35%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 1.35%   |
| Lenovo IdeaPad S540-15IML D 81NG           | 1         | 1.35%   |
| Lenovo IdeaPad S340-15IIL 81VW             | 1         | 1.35%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.35%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.35%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.35%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.35%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.35%   |
| Lenovo IdeaPad 3 14IGL05 81WH              | 1         | 1.35%   |
| HUAWEI WRT-WX9                             | 1         | 1.35%   |
| HUAWEI BOM-WXX9                            | 1         | 1.35%   |
| HP ZBook 15 G4                             | 1         | 1.35%   |
| HP Victus by Laptop 16-e0xxx               | 1         | 1.35%   |
| HP ProBook 6565b                           | 1         | 1.35%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 1.35%   |
| HP Notebook                                | 1         | 1.35%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.35%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.35%   |
| HP Laptop 15-da0xxx                        | 1         | 1.35%   |
| HP ENVY Sleekbook 4                        | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 9         | 12.16%  |
| Lenovo IdeaPad     | 8         | 10.81%  |
| Dell Latitude      | 5         | 6.76%   |
| Lenovo Legion      | 4         | 5.41%   |
| ASUS VivoBook      | 4         | 5.41%   |
| HP Laptop          | 3         | 4.05%   |
| Dell Precision     | 3         | 4.05%   |
| ASUS ASUS          | 3         | 4.05%   |
| Dell Inspiron      | 2         | 2.7%    |
| ASUS ROG           | 2         | 2.7%    |
| Acer Aspire        | 2         | 2.7%    |
| Toshiba TECRA      | 1         | 1.35%   |
| Pegatron D15K      | 1         | 1.35%   |
| MSI Katana         | 1         | 1.35%   |
| MSI GP73           | 1         | 1.35%   |
| MSI GF63           | 1         | 1.35%   |
| Medion P6816       | 1         | 1.35%   |
| Lenovo Y520-15IKBN | 1         | 1.35%   |
| HUAWEI WRT-WX9     | 1         | 1.35%   |
| HUAWEI BOM-WXX9    | 1         | 1.35%   |
| HP ZBook           | 1         | 1.35%   |
| HP Victus          | 1         | 1.35%   |
| HP ProBook         | 1         | 1.35%   |
| HP Pavilion        | 1         | 1.35%   |
| HP Notebook        | 1         | 1.35%   |
| HP ENVY            | 1         | 1.35%   |
| HP 245             | 1         | 1.35%   |
| Dell Vostro        | 1         | 1.35%   |
| Dell Venue         | 1         | 1.35%   |
| Dell G5            | 1         | 1.35%   |
| ASUS ZenBook       | 1         | 1.35%   |
| ASUS X540LA        | 1         | 1.35%   |
| ASUS X510UNR       | 1         | 1.35%   |
| ASUS UX303LN       | 1         | 1.35%   |
| ASUS TUF           | 1         | 1.35%   |
| ASUS K53SJ         | 1         | 1.35%   |
| ASUS G551JM        | 1         | 1.35%   |
| Aquarius NS585     | 1         | 1.35%   |
| Apple MacBookPro11 | 1         | 1.35%   |
| Apple MacBookAir6  | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 20.27%  |
| 2020 | 12        | 16.22%  |
| 2021 | 10        | 13.51%  |
| 2012 | 7         | 9.46%   |
| 2018 | 6         | 8.11%   |
| 2013 | 6         | 8.11%   |
| 2017 | 5         | 6.76%   |
| 2015 | 3         | 4.05%   |
| 2011 | 3         | 4.05%   |
| 2016 | 2         | 2.7%    |
| 2014 | 2         | 2.7%    |
| 2022 | 1         | 1.35%   |
| 2010 | 1         | 1.35%   |
| 2008 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 74        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 27        | 36.49%  |
| 16.01-24.0  | 15        | 20.27%  |
| 8.01-16.0   | 14        | 18.92%  |
| 3.01-4.0    | 12        | 16.22%  |
| 32.01-64.0  | 3         | 4.05%   |
| 24.01-32.0  | 2         | 2.7%    |
| 64.01-256.0 | 1         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 27        | 35.06%  |
| 1.01-2.0   | 19        | 24.68%  |
| 4.01-8.0   | 17        | 22.08%  |
| 3.01-4.0   | 11        | 14.29%  |
| 16.01-24.0 | 1         | 1.3%    |
| 8.01-16.0  | 1         | 1.3%    |
| 0.51-1.0   | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 68%     |
| 2      | 22        | 29.33%  |
| 4      | 1         | 1.33%   |
| 3      | 1         | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 82.43%  |
| Yes       | 13        | 17.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 72.97%  |
| No        | 20        | 27.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 95.95%  |
| No        | 3         | 4.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 85.14%  |
| No        | 11        | 14.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 17.33%  |
| India                  | 11        | 14.67%  |
| Germany                | 6         | 8%      |
| France                 | 5         | 6.67%   |
| Poland                 | 4         | 5.33%   |
| Italy                  | 4         | 5.33%   |
| Russia                 | 3         | 4%      |
| Turkey                 | 2         | 2.67%   |
| Pakistan               | 2         | 2.67%   |
| Norway                 | 2         | 2.67%   |
| Greece                 | 2         | 2.67%   |
| Australia              | 2         | 2.67%   |
| Zambia                 | 1         | 1.33%   |
| Vietnam                | 1         | 1.33%   |
| Togo                   | 1         | 1.33%   |
| Sweden                 | 1         | 1.33%   |
| Romania                | 1         | 1.33%   |
| Palestinian Territory  | 1         | 1.33%   |
| Netherlands            | 1         | 1.33%   |
| Morocco                | 1         | 1.33%   |
| Mongolia               | 1         | 1.33%   |
| Mexico                 | 1         | 1.33%   |
| Malaysia               | 1         | 1.33%   |
| Lebanon                | 1         | 1.33%   |
| Indonesia              | 1         | 1.33%   |
| Hungary                | 1         | 1.33%   |
| Egypt                  | 1         | 1.33%   |
| Colombia               | 1         | 1.33%   |
| Chile                  | 1         | 1.33%   |
| Canada                 | 1         | 1.33%   |
| Bosnia and Herzegovina | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Longmont     | 3         | 4%      |
| Pune         | 2         | 2.67%   |
| Madurai      | 2         | 2.67%   |
| Istanbul     | 2         | 2.67%   |
| Zenica       | 1         | 1.33%   |
| Warsaw       | 1         | 1.33%   |
| Ulan Bator   | 1         | 1.33%   |
| Ufa          | 1         | 1.33%   |
| Toronto      | 1         | 1.33%   |
| Taranto      | 1         | 1.33%   |
| Tangerang    | 1         | 1.33%   |
| Stuttgart    | 1         | 1.33%   |
| Stockholm    | 1         | 1.33%   |
| Stavropol    | 1         | 1.33%   |
| Seattle      | 1         | 1.33%   |
| Santa Cruz   | 1         | 1.33%   |
| Ramallah     | 1         | 1.33%   |
| Queens       | 1         | 1.33%   |
| Poznan       | 1         | 1.33%   |
| Porcia       | 1         | 1.33%   |
| Pirmasens    | 1         | 1.33%   |
| Phoenix      | 1         | 1.33%   |
| Perth        | 1         | 1.33%   |
| Pavia        | 1         | 1.33%   |
| Paris        | 1         | 1.33%   |
| Oslo         | 1         | 1.33%   |
| Neu-Ulm      | 1         | 1.33%   |
| Mumbai       | 1         | 1.33%   |
| Melbourne    | 1         | 1.33%   |
| Medellín    | 1         | 1.33%   |
| Magdeburg    | 1         | 1.33%   |
| Lyon         | 1         | 1.33%   |
| Lusaka       | 1         | 1.33%   |
| Lucknow      | 1         | 1.33%   |
| Lublin       | 1         | 1.33%   |
| Longvic      | 1         | 1.33%   |
| Lomé        | 1         | 1.33%   |
| Lamia        | 1         | 1.33%   |
| Lahore       | 1         | 1.33%   |
| Kuala Lumpur | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 19        | 20     | 19.19%  |
| Seagate                     | 16        | 19     | 16.16%  |
| WDC                         | 8         | 9      | 8.08%   |
| Toshiba                     | 6         | 6      | 6.06%   |
| Intel                       | 5         | 5      | 5.05%   |
| Sandisk                     | 4         | 4      | 4.04%   |
| Kingston                    | 4         | 5      | 4.04%   |
| HGST                        | 4         | 4      | 4.04%   |
| SK hynix                    | 3         | 3      | 3.03%   |
| Micron Technology           | 3         | 4      | 3.03%   |
| KIOXIA                      | 3         | 4      | 3.03%   |
| Unknown                     | 2         | 2      | 2.02%   |
| Transcend                   | 2         | 2      | 2.02%   |
| Crucial                     | 2         | 2      | 2.02%   |
| Apple                       | 2         | 2      | 2.02%   |
| Vaseky                      | 1         | 1      | 1.01%   |
| Plextor                     | 1         | 1      | 1.01%   |
| Phison Electronics          | 1         | 1      | 1.01%   |
| Phison                      | 1         | 1      | 1.01%   |
| OSCOO                       | 1         | 1      | 1.01%   |
| Micron/Crucial Technology   | 1         | 1      | 1.01%   |
| LITEONIT                    | 1         | 1      | 1.01%   |
| LITEON                      | 1         | 1      | 1.01%   |
| Kingston Technology Company | 1         | 1      | 1.01%   |
| Intenso                     | 1         | 1      | 1.01%   |
| Inateck                     | 1         | 1      | 1.01%   |
| Hitachi                     | 1         | 1      | 1.01%   |
| GOODRAM                     | 1         | 1      | 1.01%   |
| China                       | 1         | 1      | 1.01%   |
| Biostar                     | 1         | 1      | 1.01%   |
| Apacer                      | 1         | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                    | 3         | 3%      |
| Seagate ST1000LM035-1RK172 970GB                  | 3         | 3%      |
| Seagate One Touch HDD 4TB                         | 3         | 3%      |
| Toshiba MQ04ABF100 1TB                            | 2         | 2%      |
| Seagate ST750LM022 HN-M750MBB 752GB               | 2         | 2%      |
| Samsung SSD 860 EVO 250GB                         | 2         | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2%      |
| WDC WDS100T1X0E-00AFY0 1TB                        | 1         | 1%      |
| WDC WDBNCE0010PNC 1TB SSD                         | 1         | 1%      |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 1%      |
| WDC WD10SPZX-24Z10 1TB                            | 1         | 1%      |
| WDC PC SN720 SDAPNTW-512G-1027 512GB              | 1         | 1%      |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB              | 1         | 1%      |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1%      |
| WDC PC SN520 SDAPMUW-256G-1101 256GB              | 1         | 1%      |
| Vaseky V800/256G 256GB SSD                        | 1         | 1%      |
| Unknown MMC Card  64GB                            | 1         | 1%      |
| Unknown G1J38E  64GB                              | 1         | 1%      |
| Transcend TS512GMTS430S 512GB SSD                 | 1         | 1%      |
| Transcend TS256GMTS400 256GB SSD                  | 1         | 1%      |
| Toshiba XG6 NVMe SSD Controller 1024GB            | 1         | 1%      |
| Toshiba MQ01ABF050M 500GB                         | 1         | 1%      |
| Toshiba KBG40ZNT512G MEMORY 512GB                 | 1         | 1%      |
| Toshiba KBG30ZMV256G 256GB                        | 1         | 1%      |
| SK hynix PC711 HFS512GDE9X073N 512GB              | 1         | 1%      |
| SK hynix BC711 NVMe 512GB                         | 1         | 1%      |
| SK hynix BC711 NVMe 128GB                         | 1         | 1%      |
| Seagate ST9500325AS 500GB                         | 1         | 1%      |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1%      |
| Seagate ST500LM000-SSHD-8GB                       | 1         | 1%      |
| Seagate ST1000LM048-2E7172 1TB                    | 1         | 1%      |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB        | 1         | 1%      |
| Seagate Expansion 4TB                             | 1         | 1%      |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1%      |
| SanDisk SD8SB8U-256G-1006 256GB SSD               | 1         | 1%      |
| Sandisk PC SN520 NVMe SSD 512GB                   | 1         | 1%      |
| SanDisk NVMe SSD Drive 256GB                      | 1         | 1%      |
| Samsung SSD SM841 mSATA 128GB                     | 1         | 1%      |
| Samsung SSD 980 1TB                               | 1         | 1%      |
| Samsung SSD 860 EVO 1TB                           | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 18     | 61.54%  |
| HGST    | 4         | 4      | 15.38%  |
| Toshiba | 3         | 3      | 11.54%  |
| WDC     | 2         | 2      | 7.69%   |
| Hitachi | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 25.93%  |
| Transcend           | 2         | 2      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| Apple               | 2         | 2      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Vaseky              | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| Plextor             | 1         | 1      | 3.7%    |
| OSCOO               | 1         | 1      | 3.7%    |
| LITEONIT            | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Kingston            | 1         | 1      | 3.7%    |
| Intenso             | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| GOODRAM             | 1         | 1      | 3.7%    |
| China               | 1         | 1      | 3.7%    |
| Biostar             | 1         | 1      | 3.7%    |
| Apacer              | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 40        | 50     | 44.44%  |
| HDD  | 25        | 28     | 27.78%  |
| SSD  | 23        | 27     | 25.56%  |
| MMC  | 2         | 2      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 51     | 46.59%  |
| NVMe | 40        | 49     | 45.45%  |
| SAS  | 5         | 5      | 5.68%   |
| MMC  | 2         | 2      | 2.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 22        | 24     | 45.83%  |
| 0.01-0.5   | 21        | 26     | 43.75%  |
| 3.01-4.0   | 4         | 4      | 8.33%   |
| 1.01-2.0   | 1         | 1      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 18.42%  |
| More than 3000 | 13        | 17.11%  |
| 1001-2000      | 13        | 17.11%  |
| 101-250        | 10        | 13.16%  |
| 501-1000       | 8         | 10.53%  |
| Unknown        | 7         | 9.21%   |
| 51-100         | 6         | 7.89%   |
| 1-20           | 3         | 3.95%   |
| 21-50          | 1         | 1.32%   |
| 2001-3000      | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 19.74%  |
| 51-100         | 15        | 19.74%  |
| 1-20           | 14        | 18.42%  |
| 21-50          | 10        | 13.16%  |
| Unknown        | 7         | 9.21%   |
| 251-500        | 6         | 7.89%   |
| 501-1000       | 4         | 5.26%   |
| 2001-3000      | 3         | 3.95%   |
| More than 3000 | 1         | 1.32%   |
| 1001-2000      | 1         | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 11.11%  |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 11.11%  |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 11.11%  |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 11.11%  |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 500GB | 1         | 1      | 11.11%  |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 44.44%  |
| HGST                | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Toshiba | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 88.89%  |
| NVMe | 1         | 1      | 11.11%  |

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
| Works    | 54        | 72     | 67.5%   |
| Detected | 17        | 26     | 21.25%  |
| Malfunc  | 9         | 9      | 11.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 55        | 52.88%  |
| Samsung Electronics          | 14        | 13.46%  |
| AMD                          | 8         | 7.69%   |
| SanDisk                      | 7         | 6.73%   |
| Kingston Technology Company  | 4         | 3.85%   |
| Toshiba America Info Systems | 3         | 2.88%   |
| SK hynix                     | 3         | 2.88%   |
| Micron Technology            | 3         | 2.88%   |
| KIOXIA                       | 3         | 2.88%   |
| Phison Electronics           | 2         | 1.92%   |
| Seagate Technology           | 1         | 0.96%   |
| Micron/Crucial Technology    | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 7.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 6.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 5.61%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 2.8%    |
| Micron NVMe Storage Controller                                                 | 3         | 2.8%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.8%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.8%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.87%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.87%   |
| SanDisk NVMe Controller                                                        | 2         | 1.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.87%   |
| Samsung Apple PCIe SSD                                                         | 2         | 1.87%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.87%   |
| Intel SSD 660P Series                                                          | 2         | 1.87%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.93%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.93%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.93%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.93%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 49.04%  |
| NVMe | 40        | 38.46%  |
| RAID | 13        | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 82.43%  |
| AMD    | 13        | 17.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 4.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 4.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 4.05%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 4.05%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 2.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 2.7%    |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 2.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 2.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.7%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 2.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.35%   |
| Intel Core i7-4960HQ CPU @ 2.60GHz            | 1         | 1.35%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.35%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 1.35%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.35%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.35%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.35%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.35%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.35%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 1.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.35%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 1.35%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.35%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.35%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1         | 1.35%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 23        | 31.08%  |
| Intel Core i5    | 21        | 28.38%  |
| Other            | 10        | 13.51%  |
| AMD Ryzen 5      | 6         | 8.11%   |
| Intel Core i3    | 4         | 5.41%   |
| AMD Ryzen 7      | 3         | 4.05%   |
| Intel Celeron    | 2         | 2.7%    |
| AMD Ryzen 3      | 2         | 2.7%    |
| Intel Core 2 Duo | 1         | 1.35%   |
| AMD A6           | 1         | 1.35%   |
| AMD A4           | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 35        | 47.3%   |
| 2      | 27        | 36.49%  |
| 6      | 7         | 9.46%   |
| 8      | 4         | 5.41%   |
| 14     | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 68        | 90.67%  |
| 1      | 7         | 9.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 27.63%  |
| 0x806c1    | 7         | 9.21%   |
| 0x806ec    | 6         | 7.89%   |
| 0x306a9    | 4         | 5.26%   |
| 0x906ea    | 3         | 3.95%   |
| 0x906e9    | 3         | 3.95%   |
| 0x806e9    | 3         | 3.95%   |
| 0x206a7    | 3         | 3.95%   |
| 0x08108109 | 3         | 3.95%   |
| 0x806eb    | 2         | 2.63%   |
| 0x706a8    | 2         | 2.63%   |
| 0x40651    | 2         | 2.63%   |
| 0xa0652    | 1         | 1.32%   |
| 0x906ed    | 1         | 1.32%   |
| 0x906eb    | 1         | 1.32%   |
| 0x906a3    | 1         | 1.32%   |
| 0x806d1    | 1         | 1.32%   |
| 0x706e5    | 1         | 1.32%   |
| 0x406e3    | 1         | 1.32%   |
| 0x40661    | 1         | 1.32%   |
| 0x306d4    | 1         | 1.32%   |
| 0x306c3    | 1         | 1.32%   |
| 0x20652    | 1         | 1.32%   |
| 0x1067a    | 1         | 1.32%   |
| 0x08608103 | 1         | 1.32%   |
| 0x08600106 | 1         | 1.32%   |
| 0x08108102 | 1         | 1.32%   |
| 0x06006705 | 1         | 1.32%   |
| 0x03000027 | 1         | 1.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 29.73%  |
| Haswell          | 9         | 12.16%  |
| TigerLake        | 8         | 10.81%  |
| IvyBridge        | 6         | 8.11%   |
| Zen+             | 5         | 6.76%   |
| Zen 2            | 3         | 4.05%   |
| SandyBridge      | 3         | 4.05%   |
| IceLake          | 3         | 4.05%   |
| Zen 3            | 2         | 2.7%    |
| Goldmont plus    | 2         | 2.7%    |
| CometLake        | 2         | 2.7%    |
| Broadwell        | 2         | 2.7%    |
| Westmere         | 1         | 1.35%   |
| Skylake          | 1         | 1.35%   |
| Penryn           | 1         | 1.35%   |
| K10 Llano        | 1         | 1.35%   |
| Excavator        | 1         | 1.35%   |
| Alderlake Hybrid | 1         | 1.35%   |
| Unknown          | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 60        | 53.1%   |
| Nvidia | 38        | 33.63%  |
| AMD    | 15        | 13.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 2.63%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.63%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 2.63%   |
| Intel UHD Graphics 620                                                    | 3         | 2.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.63%   |
| Intel HD Graphics 630                                                     | 3         | 2.63%   |
| Intel HD Graphics 620                                                     | 3         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.63%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.75%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.75%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.75%   |
| Intel HD Graphics 5500                                                    | 2         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.75%   |
| AMD Renoir                                                                | 2         | 1.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.88%   |
| Nvidia TU117M                                                             | 1         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.88%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.88%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.88%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                     | 1         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 31        | 41.89%  |
| 1 x Intel      | 25        | 33.78%  |
| 1 x AMD        | 6         | 8.11%   |
| AMD + Nvidia   | 5         | 6.76%   |
| Intel + AMD    | 3         | 4.05%   |
| 1 x Nvidia     | 2         | 2.7%    |
| 2 x Intel      | 1         | 1.35%   |
| 2 x AMD        | 1         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 50        | 66.67%  |
| Proprietary | 25        | 33.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 72%     |
| 1.01-2.0   | 9         | 12%     |
| 0.01-0.5   | 5         | 6.67%   |
| 5.01-6.0   | 3         | 4%      |
| 3.01-4.0   | 3         | 4%      |
| 0.51-1.0   | 1         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 19        | 22.09%  |
| BOE                 | 14        | 16.28%  |
| Chimei Innolux      | 13        | 15.12%  |
| LG Display          | 12        | 13.95%  |
| Samsung Electronics | 10        | 11.63%  |
| PANDA               | 3         | 3.49%   |
| Apple               | 3         | 3.49%   |
| Sharp               | 2         | 2.33%   |
| Dell                | 2         | 2.33%   |
| TMX                 | 1         | 1.16%   |
| Sceptre Tech        | 1         | 1.16%   |
| LGD                 | 1         | 1.16%   |
| Lenovo              | 1         | 1.16%   |
| Goldstar            | 1         | 1.16%   |
| CSO                 | 1         | 1.16%   |
| BenQ                | 1         | 1.16%   |
| Acer                | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 3.49%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 2.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 2.33%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 2.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.33%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 1.16%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.16%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.16%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.16%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 1.16%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 1.16%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 1.16%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.16%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 1.16%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 1.16%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 1.16%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.16%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 1.16%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.16%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                   | 1         | 1.16%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 1.16%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 1         | 1.16%   |
| CSO LCD Monitor CSO1403 3840x2400 302x189mm 14.0-inch                   | 1         | 1.16%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 62.96%  |
| 1366x768 (WXGA)    | 16        | 19.75%  |
| 3840x2160 (4K)     | 3         | 3.7%    |
| 1600x900 (HD+)     | 3         | 3.7%    |
| 3840x2400          | 1         | 1.23%   |
| 3200x1800 (QHD+)   | 1         | 1.23%   |
| 2880x1800          | 1         | 1.23%   |
| 2560x1080          | 1         | 1.23%   |
| 2160x1440          | 1         | 1.23%   |
| 1920x1200 (WUXGA)  | 1         | 1.23%   |
| 1680x1050 (WSXGA+) | 1         | 1.23%   |
| 1440x900 (WXGA+)   | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 46        | 54.12%  |
| 14      | 11        | 12.94%  |
| 13      | 9         | 10.59%  |
| 23      | 4         | 4.71%   |
| 84      | 3         | 3.53%   |
| 21      | 2         | 2.35%   |
| 17      | 2         | 2.35%   |
| 31      | 1         | 1.18%   |
| 28      | 1         | 1.18%   |
| 27      | 1         | 1.18%   |
| 24      | 1         | 1.18%   |
| 18      | 1         | 1.18%   |
| 16      | 1         | 1.18%   |
| 12      | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 73.26%  |
| 501-600     | 6         | 6.98%   |
| 401-500     | 4         | 4.65%   |
| 201-300     | 4         | 4.65%   |
| 351-400     | 3         | 3.49%   |
| 1501-2000   | 3         | 3.49%   |
| 601-700     | 2         | 2.33%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 90.67%  |
| 16/10   | 4         | 5.33%   |
| 3/2     | 1         | 1.33%   |
| 21/9    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 55.95%  |
| 81-90          | 18        | 21.43%  |
| 201-250        | 6         | 7.14%   |
| More than 1000 | 3         | 3.57%   |
| 71-80          | 2         | 2.38%   |
| 121-130        | 2         | 2.38%   |
| 61-70          | 1         | 1.19%   |
| 351-500        | 1         | 1.19%   |
| 301-350        | 1         | 1.19%   |
| 251-300        | 1         | 1.19%   |
| 141-150        | 1         | 1.19%   |
| Unknown        | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 57.14%  |
| 101-120       | 18        | 21.43%  |
| 51-100        | 11        | 13.1%   |
| 161-240       | 4         | 4.76%   |
| More than 240 | 2         | 2.38%   |
| Unknown       | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 62        | 83.78%  |
| 2     | 11        | 14.86%  |
| 3     | 1         | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 47        | 44.34%  |
| Realtek Semiconductor             | 37        | 34.91%  |
| Qualcomm Atheros                  | 5         | 4.72%   |
| Broadcom Limited                  | 4         | 3.77%   |
| MediaTek                          | 3         | 2.83%   |
| ASIX Electronics                  | 3         | 2.83%   |
| Samsung Electronics               | 2         | 1.89%   |
| Ericsson Business Mobile Networks | 2         | 1.89%   |
| Ralink                            | 1         | 0.94%   |
| Marvell Technology Group          | 1         | 0.94%   |
| Broadcom                          | 1         | 0.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 26        | 19.85%  |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 6         | 4.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 5         | 3.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 5         | 3.82%   |
| Intel Wireless 7260                                                | 5         | 3.82%   |
| Intel Wireless 8265 / 8275                                         | 4         | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 3.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 4         | 3.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 3         | 2.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 2.29%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 2.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.53%   |
| Intel Wi-Fi 6 AX200                                                | 2         | 1.53%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.53%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.53%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller               | 1         | 0.76%   |
| Intel Wireless-AC 9260                                             | 1         | 0.76%   |
| Intel Wireless 8260                                                | 1         | 0.76%   |
| Intel Wireless 7265                                                | 1         | 0.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                   | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                               | 1         | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                              | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 64.79%  |
| Realtek Semiconductor | 12        | 16.9%   |
| Qualcomm Atheros      | 4         | 5.63%   |
| Broadcom Limited      | 4         | 5.63%   |
| MediaTek              | 3         | 4.23%   |
| Ralink                | 1         | 1.41%   |
| Broadcom              | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                           | 6         | 8.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 7.04%   |
| Intel Wireless 7260                                           | 5         | 7.04%   |
| Intel Wireless 8265 / 8275                                    | 4         | 5.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 5.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 5.63%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 5.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 4.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 4.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 2.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 2.82%   |
| Intel Wi-Fi 6 AX200                                           | 2         | 2.82%   |
| Intel Centrino Wireless-N 2230                                | 2         | 2.82%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 2         | 2.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 1.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.41%   |
| Intel Wireless-AC 9260                                        | 1         | 1.41%   |
| Intel Wireless 8260                                           | 1         | 1.41%   |
| Intel Wireless 7265                                           | 1         | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 1.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.41%   |
| Intel Centrino Wireless-N 2200                                | 1         | 1.41%   |
| Intel Centrino Wireless-N 100                                 | 1         | 1.41%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 1.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 1.41%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                       | 1         | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 60%     |
| Intel                    | 17        | 30.91%  |
| ASIX Electronics         | 3         | 5.45%   |
| Qualcomm Atheros         | 1         | 1.82%   |
| Marvell Technology Group | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 46.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 10.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 8.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.36%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.79%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.79%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 55.04%  |
| Ethernet | 54        | 41.86%  |
| Modem    | 4         | 3.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 81.58%  |
| Ethernet | 14        | 18.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 60.81%  |
| 1     | 28        | 37.84%  |
| 0     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 70.27%  |
| Yes  | 22        | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 57.14%  |
| Realtek Semiconductor           | 7         | 11.11%  |
| IMC Networks                    | 5         | 7.94%   |
| Broadcom                        | 5         | 7.94%   |
| Qualcomm Atheros Communications | 3         | 4.76%   |
| Apple                           | 2         | 3.17%   |
| Toshiba                         | 1         | 1.59%   |
| Realtek                         | 1         | 1.59%   |
| Lite-On Technology              | 1         | 1.59%   |
| Foxconn / Hon Hai               | 1         | 1.59%   |
| Dell                            | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 14        | 22.22%  |
| Intel Bluetooth wireless interface             | 9         | 14.29%  |
| Intel AX201 Bluetooth                          | 8         | 12.7%   |
| Realtek Bluetooth Radio                        | 4         | 6.35%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device             | 3         | 4.76%   |
| IMC Networks Bluetooth Radio                   | 3         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 2         | 3.17%   |
| Intel AX200 Bluetooth                          | 2         | 3.17%   |
| IMC Networks Wireless_Device                   | 2         | 3.17%   |
| Broadcom BCM20702A0 Bluetooth                  | 2         | 3.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 3.17%   |
| Toshiba Integrated Bluetooth HCI               | 1         | 1.59%   |
| Realtek 802.11ac WLAN Adapter                  | 1         | 1.59%   |
| Lite-On Bluetooth Device                       | 1         | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.59%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.59%   |
| Dell BCM20702A0 Bluetooth Module               | 1         | 1.59%   |
| Broadcom BCM2045A0                             | 1         | 1.59%   |
| Apple Bluetooth USB Host Controller            | 1         | 1.59%   |
| Apple Bluetooth Host Controller                | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 61        | 60.4%   |
| Nvidia                     | 19        | 18.81%  |
| AMD                        | 13        | 12.87%  |
| GN Netcom                  | 2         | 1.98%   |
| Samsung Electronics        | 1         | 0.99%   |
| Realtek Semiconductor      | 1         | 0.99%   |
| PreSonus Audio Electronics | 1         | 0.99%   |
| Lenovo                     | 1         | 0.99%   |
| Barco Display Systems      | 1         | 0.99%   |
| ASUSTek Computer           | 1         | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 8.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 4.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.31%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 3.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.31%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.48%   |
| Intel CM238 HD Audio Controller                                            | 3         | 2.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.65%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.65%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.65%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.83%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.83%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.83%   |
| Nvidia Audio device                                                        | 1         | 0.83%   |
| Lenovo USB Headset                                                         | 1         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.83%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.83%   |
| GN Netcom Jabra Link 370                                                   | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 36%     |
| SK hynix            | 22        | 29.33%  |
| Micron Technology   | 10        | 13.33%  |
| Crucial             | 6         | 8%      |
| Ramaxel Technology  | 4         | 5.33%   |
| Kingston            | 3         | 4%      |
| Nanya Technology    | 1         | 1.33%   |
| Elpida              | 1         | 1.33%   |
| Corsair             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 5.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 3.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 2.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 2.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 2.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.28%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.28%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.28%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.28%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.28%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 1.28%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 1.28%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.28%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 38        | 61.29%  |
| DDR3   | 17        | 27.42%  |
| LPDDR4 | 2         | 3.23%   |
| LPDDR3 | 2         | 3.23%   |
| SDRAM  | 1         | 1.61%   |
| DDR5   | 1         | 1.61%   |
| DDR    | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 84.38%  |
| Row Of Chips | 10        | 15.63%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 49.25%  |
| 4096  | 24        | 35.82%  |
| 16384 | 7         | 10.45%  |
| 2048  | 3         | 4.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 25        | 34.72%  |
| 3200  | 14        | 19.44%  |
| 1600  | 13        | 18.06%  |
| 3266  | 4         | 5.56%   |
| 2400  | 3         | 4.17%   |
| 2133  | 3         | 4.17%   |
| 1333  | 3         | 4.17%   |
| 4267  | 2         | 2.78%   |
| 4800  | 1         | 1.39%   |
| 4199  | 1         | 1.39%   |
| 1334  | 1         | 1.39%   |
| 1067  | 1         | 1.39%   |
| 800   | 1         | 1.39%   |

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
| IMC Networks                           | 18        | 26.09%  |
| Chicony Electronics                    | 11        | 15.94%  |
| Realtek Semiconductor                  | 6         | 8.7%    |
| Syntek                                 | 5         | 7.25%   |
| Acer                                   | 5         | 7.25%   |
| Quanta                                 | 4         | 5.8%    |
| Microdia                               | 4         | 5.8%    |
| Bison Electronics                      | 4         | 5.8%    |
| Sunplus Innovation Technology          | 3         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.35%   |
| Suyin                                  | 1         | 1.45%   |
| Sonix Technology                       | 1         | 1.45%   |
| Ricoh                                  | 1         | 1.45%   |
| Luxvisions Innotech Limited            | 1         | 1.45%   |
| Lite-On Technology                     | 1         | 1.45%   |
| Alpha Imaging Technology               | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                       | 5         | 7.25%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 5         | 7.25%   |
| IMC Networks Integrated Camera                                 | 5         | 7.25%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 4.35%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 4.35%   |
| Chicony Integrated Camera                                      | 3         | 4.35%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 2.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 2         | 2.9%    |
| Bison Integrated Camera                                        | 2         | 2.9%    |
| Acer ThinkPad Integrated Camera                                | 2         | 2.9%    |
| Suyin Asus Integrated Webcam                                   | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.45%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 1.45%   |
| Sunplus HP Truevision HD                                       | 1         | 1.45%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 1.45%   |
| Ricoh Integrated Webcam                                        | 1         | 1.45%   |
| Realtek Integrated Webcam_HD                                   | 1         | 1.45%   |
| Realtek Integrated Webcam                                      | 1         | 1.45%   |
| Realtek Built-In Video Camera                                  | 1         | 1.45%   |
| Quanta HD User Facing                                          | 1         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 1         | 1.45%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.45%   |
| Lite-On Integrated Camera                                      | 1         | 1.45%   |
| IMC Networks VGA UVC WebCam                                    | 1         | 1.45%   |
| IMC Networks UVC VGA Webcam                                    | 1         | 1.45%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.45%   |
| IMC Networks USB2.0 HD IR UVC WebCam                           | 1         | 1.45%   |
| IMC Networks HD Camera                                         | 1         | 1.45%   |
| IMC Networks EasyCamera                                        | 1         | 1.45%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.45%   |
| Chicony USB2.0 UVC WebCam                                      | 1         | 1.45%   |
| Chicony USB 2.0 Camera                                         | 1         | 1.45%   |
| Chicony Integrated HP HD Webcam                                | 1         | 1.45%   |
| Chicony HP Wide Vision HD Camera                               | 1         | 1.45%   |
| Chicony HP Webcam                                              | 1         | 1.45%   |
| Chicony HD User Facing                                         | 1         | 1.45%   |
| Chicony EasyCamera                                             | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 1.45%   |

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
| 0     | 49        | 65.33%  |
| 1     | 20        | 26.67%  |
| 2     | 6         | 8%      |

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

