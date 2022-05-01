Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 77

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell     | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell     | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo   | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI      | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer     | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI      | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell     | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek  | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell     | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP       | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek  | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI      | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell     | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek  | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI   | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell     | Latitude 7480               | Notebook    | [1083fec58a](https://linux-hardware.org/?probe=1083fec58a) | Mar 19, 2022 |
| Dell     | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple    | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP       | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo   | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo   | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI      | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell     | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo   | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell     | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo   | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek  | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer     | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell     | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo   | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP       | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo   | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP       | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP       | 2179                        | All in one  | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell     | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP       | 2179                        | All in one  | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP       | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek  | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [3e4f21099d](https://linux-hardware.org/?probe=3e4f21099d) | Dec 17, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI      | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo   | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer     | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP       | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo   | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell     | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock   | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [203afc45fd](https://linux-hardware.org/?probe=203afc45fd) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 48        | 82.76%  |
| Xero         | 10        | 17.24%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.15-arch1-1              | 6         | 9.38%   |
| 5.16.2-arch1-1               | 3         | 4.69%   |
| 5.16.1-arch1-1               | 3         | 4.69%   |
| 5.15.33-1-lts                | 3         | 4.69%   |
| 5.14.14-arch1-1              | 3         | 4.69%   |
| 5.17.1-arch1-1               | 2         | 3.13%   |
| 5.16.8-arch1-1               | 2         | 3.13%   |
| 5.16.16-arch1-1              | 2         | 3.13%   |
| 5.16.13-arch1-1              | 2         | 3.13%   |
| 5.16.12-arch1-1              | 2         | 3.13%   |
| 5.14.8-zen1-1-zen            | 2         | 3.13%   |
| 5.16.16-zen1-1-zen           | 1         | 1.56%   |
| 5.16.14-arch1-1              | 1         | 1.56%   |
| 5.16.10-arch1-1              | 1         | 1.56%   |
| 5.15.9-AMD                   | 1         | 1.56%   |
| 5.15.8-zen1-1-zen            | 1         | 1.56%   |
| 5.15.6-arch2-1               | 1         | 1.56%   |
| 5.15.4-arch1-1               | 1         | 1.56%   |
| 5.15.35-1-lts                | 1         | 1.56%   |
| 5.15.3-zen1-1-zen            | 1         | 1.56%   |
| 5.15.26-1-lts                | 1         | 1.56%   |
| 5.15.13-arch1-1              | 1         | 1.56%   |
| 5.15.13-AMD                  | 1         | 1.56%   |
| 5.15.12-zen1-1-zen           | 1         | 1.56%   |
| 5.15.12-arch1-1-surface      | 1         | 1.56%   |
| 5.15.12-arch1-1              | 1         | 1.56%   |
| 5.15.11-arch2-1-surface      | 1         | 1.56%   |
| 5.15.11-arch2-1              | 1         | 1.56%   |
| 5.15.10-arch1-1              | 1         | 1.56%   |
| 5.14.9-zen2-1-zen            | 1         | 1.56%   |
| 5.14.8-arch1-1               | 1         | 1.56%   |
| 5.14.16-zen1-1-zen           | 1         | 1.56%   |
| 5.14.16-arch1-2-surface      | 1         | 1.56%   |
| 5.14.16-arch1-1              | 1         | 1.56%   |
| 5.14.15-zen1-1-zen           | 1         | 1.56%   |
| 5.14.14-zen1-1-zen           | 1         | 1.56%   |
| 5.14.12-arch1-1              | 1         | 1.56%   |
| 5.14.11-hardened1-1-hardened | 1         | 1.56%   |
| 5.13.4-zen1-1-zen            | 1         | 1.56%   |
| 5.13.13-AMD                  | 1         | 1.56%   |
| 5.12.5-AMD                   | 1         | 1.56%   |
| 5.11.16-zen1-1-zen           | 1         | 1.56%   |
| 5.10.88-1-lts                | 1         | 1.56%   |
| 5.10.80-1-lts                | 1         | 1.56%   |
| 5.10.71-1-lts                | 1         | 1.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 9.38%   |
| 5.14.14 | 4         | 6.25%   |
| 5.16.2  | 3         | 4.69%   |
| 5.16.16 | 3         | 4.69%   |
| 5.16.1  | 3         | 4.69%   |
| 5.15.33 | 3         | 4.69%   |
| 5.15.12 | 3         | 4.69%   |
| 5.14.8  | 3         | 4.69%   |
| 5.14.16 | 3         | 4.69%   |
| 5.17.1  | 2         | 3.13%   |
| 5.16.8  | 2         | 3.13%   |
| 5.16.13 | 2         | 3.13%   |
| 5.16.12 | 2         | 3.13%   |
| 5.15.13 | 2         | 3.13%   |
| 5.15.11 | 2         | 3.13%   |
| 5.16.14 | 1         | 1.56%   |
| 5.16.10 | 1         | 1.56%   |
| 5.15.9  | 1         | 1.56%   |
| 5.15.8  | 1         | 1.56%   |
| 5.15.6  | 1         | 1.56%   |
| 5.15.4  | 1         | 1.56%   |
| 5.15.35 | 1         | 1.56%   |
| 5.15.3  | 1         | 1.56%   |
| 5.15.26 | 1         | 1.56%   |
| 5.15.10 | 1         | 1.56%   |
| 5.14.9  | 1         | 1.56%   |
| 5.14.15 | 1         | 1.56%   |
| 5.14.12 | 1         | 1.56%   |
| 5.14.11 | 1         | 1.56%   |
| 5.13.4  | 1         | 1.56%   |
| 5.13.13 | 1         | 1.56%   |
| 5.12.5  | 1         | 1.56%   |
| 5.11.16 | 1         | 1.56%   |
| 5.10.88 | 1         | 1.56%   |
| 5.10.80 | 1         | 1.56%   |
| 5.10.71 | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 37.1%   |
| 5.15    | 17        | 27.42%  |
| 5.14    | 13        | 20.97%  |
| 5.10    | 3         | 4.84%   |
| 5.17    | 2         | 3.23%   |
| 5.13    | 2         | 3.23%   |
| 5.12    | 1         | 1.61%   |
| 5.11    | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 53        | 89.83%  |
| XFCE  | 4         | 6.78%   |
| GNOME | 2         | 3.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 45        | 78.95%  |
| Wayland | 10        | 17.54%  |
| Tty     | 2         | 3.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 34        | 55.74%  |
| LightDM | 15        | 24.59%  |
| Unknown | 10        | 16.39%  |
| TDM     | 1         | 1.64%   |
| GDM     | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 34        | 58.62%  |
| en_IN | 5         | 8.62%   |
| C     | 5         | 8.62%   |
| pl_PL | 3         | 5.17%   |
| it_IT | 2         | 3.45%   |
| en_GB | 2         | 3.45%   |
| en_AU | 2         | 3.45%   |
| de_DE | 2         | 3.45%   |
| en_IL | 1         | 1.72%   |
| en_CA | 1         | 1.72%   |
| de_AT | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 39        | 67.24%  |
| BIOS | 19        | 32.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 46        | 77.97%  |
| Ext4    | 8         | 13.56%  |
| Overlay | 5         | 8.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 68.97%  |
| Unknown | 10        | 17.24%  |
| MBR     | 8         | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 84.75%  |
| Yes       | 9         | 15.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 66.67%  |
| Yes       | 19        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 14        | 24.56%  |
| Lenovo              | 11        | 19.3%   |
| Dell                | 9         | 15.79%  |
| Hewlett-Packard     | 7         | 12.28%  |
| MSI                 | 5         | 8.77%   |
| Acer                | 3         | 5.26%   |
| Pegatron            | 2         | 3.51%   |
| Gigabyte Technology | 2         | 3.51%   |
| ASRock              | 2         | 3.51%   |
| HUAWEI              | 1         | 1.75%   |
| Apple               | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Precision M3800                     | 3         | 5.26%   |
| MSI MS-7971                              | 2         | 3.51%   |
| ASUS TUF GAMING X570-PLUS                | 2         | 3.51%   |
| Pegatron p6-2026                         | 1         | 1.75%   |
| Pegatron D15K                            | 1         | 1.75%   |
| MSI MS-7B61                              | 1         | 1.75%   |
| MSI GP73 Leopard 8RD                     | 1         | 1.75%   |
| MSI GF63 Thin 9SCX                       | 1         | 1.75%   |
| Lenovo Yoga 710-15IKB 80V5               | 1         | 1.75%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.75%   |
| Lenovo ThinkPad X230 2325HR9             | 1         | 1.75%   |
| Lenovo ThinkPad W530 24384CU             | 1         | 1.75%   |
| Lenovo ThinkPad T460 20FMS1XX00          | 1         | 1.75%   |
| Lenovo Legion Y740-15IRHg 81UH           | 1         | 1.75%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 1.75%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.75%   |
| Lenovo IdeaPad S145-15IIL 81W8           | 1         | 1.75%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 1.75%   |
| Lenovo IdeaPad 3 15IML05 81WR            | 1         | 1.75%   |
| HUAWEI WRT-WX9                           | 1         | 1.75%   |
| HP Z230 SFF Workstation                  | 1         | 1.75%   |
| HP ProOne 400 G1 AiO                     | 1         | 1.75%   |
| HP Pavilion Desktop 590-p0xxx            | 1         | 1.75%   |
| HP Notebook                              | 1         | 1.75%   |
| HP Laptop 15s-eq0xxx                     | 1         | 1.75%   |
| HP Laptop 15-da0xxx                      | 1         | 1.75%   |
| HP ENVY Sleekbook 4                      | 1         | 1.75%   |
| Gigabyte Z170X-UD3                       | 1         | 1.75%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.75%   |
| Dell Vostro 3590                         | 1         | 1.75%   |
| Dell Venue 11 Pro 7130 vPro              | 1         | 1.75%   |
| Dell Precision T1500                     | 1         | 1.75%   |
| Dell Latitude E6520                      | 1         | 1.75%   |
| Dell Latitude E6430                      | 1         | 1.75%   |
| Dell Latitude 7480                       | 1         | 1.75%   |
| ASUS X510UNR                             | 1         | 1.75%   |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ   | 1         | 1.75%   |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA  | 1         | 1.75%   |
| ASUS TUF Z390-PLUS GAMING                | 1         | 1.75%   |
| ASUS TUF Gaming B550M-PLUS               | 1         | 1.75%   |
| ASUS TUF B360M-PLUS GAMING/BR            | 1         | 1.75%   |
| ASUS ROG CROSSHAIR VIII HERO             | 1         | 1.75%   |
| ASUS PRIME A320M-K                       | 1         | 1.75%   |
| ASUS P5Q PRO TURBO                       | 1         | 1.75%   |
| ASUS Maximus IX HERO                     | 1         | 1.75%   |
| ASUS ASUS TUF Gaming F15 FX506LU_FX506LU | 1         | 1.75%   |
| ASUS ASUS EXPERTBOOK B9400CEA_B9450CEA   | 1         | 1.75%   |
| ASRock X570 Taichi                       | 1         | 1.75%   |
| ASRock B450M Pro4                        | 1         | 1.75%   |
| Apple MacBookAir6,2                      | 1         | 1.75%   |
| Acer Aspire X5950                        | 1         | 1.75%   |
| Acer Aspire A515-54G                     | 1         | 1.75%   |
| Acer Aspire A315-58G                     | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS TUF           | 5         | 8.77%   |
| Dell Precision     | 4         | 7.02%   |
| Lenovo ThinkPad    | 3         | 5.26%   |
| Lenovo Legion      | 3         | 5.26%   |
| Lenovo IdeaPad     | 3         | 5.26%   |
| Dell Latitude      | 3         | 5.26%   |
| Acer Aspire        | 3         | 5.26%   |
| MSI MS-7971        | 2         | 3.51%   |
| HP Laptop          | 2         | 3.51%   |
| ASUS VivoBook      | 2         | 3.51%   |
| ASUS ASUS          | 2         | 3.51%   |
| Pegatron p6-2026   | 1         | 1.75%   |
| Pegatron D15K      | 1         | 1.75%   |
| MSI MS-7B61        | 1         | 1.75%   |
| MSI GP73           | 1         | 1.75%   |
| MSI GF63           | 1         | 1.75%   |
| Lenovo Yoga        | 1         | 1.75%   |
| Lenovo Y520-15IKBN | 1         | 1.75%   |
| HUAWEI WRT-WX9     | 1         | 1.75%   |
| HP Z230            | 1         | 1.75%   |
| HP ProOne          | 1         | 1.75%   |
| HP Pavilion        | 1         | 1.75%   |
| HP Notebook        | 1         | 1.75%   |
| HP ENVY            | 1         | 1.75%   |
| Gigabyte Z170X-UD3 | 1         | 1.75%   |
| Gigabyte X570      | 1         | 1.75%   |
| Dell Vostro        | 1         | 1.75%   |
| Dell Venue         | 1         | 1.75%   |
| ASUS X510UNR       | 1         | 1.75%   |
| ASUS ROG           | 1         | 1.75%   |
| ASUS PRIME         | 1         | 1.75%   |
| ASUS P5Q           | 1         | 1.75%   |
| ASUS Maximus       | 1         | 1.75%   |
| ASRock X570        | 1         | 1.75%   |
| ASRock B450M       | 1         | 1.75%   |
| Apple MacBookAir6  | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 12        | 21.05%  |
| 2020 | 8         | 14.04%  |
| 2018 | 7         | 12.28%  |
| 2017 | 6         | 10.53%  |
| 2015 | 4         | 7.02%   |
| 2014 | 4         | 7.02%   |
| 2012 | 4         | 7.02%   |
| 2021 | 3         | 5.26%   |
| 2016 | 2         | 3.51%   |
| 2013 | 2         | 3.51%   |
| 2011 | 2         | 3.51%   |
| 2010 | 2         | 3.51%   |
| 2009 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 34        | 59.65%  |
| Desktop     | 21        | 36.84%  |
| Convertible | 1         | 1.75%   |
| All in one  | 1         | 1.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 18        | 31.58%  |
| 16.01-24.0  | 16        | 28.07%  |
| 8.01-16.0   | 9         | 15.79%  |
| 32.01-64.0  | 6         | 10.53%  |
| 3.01-4.0    | 5         | 8.77%   |
| 24.01-32.0  | 2         | 3.51%   |
| 64.01-256.0 | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 19        | 29.69%  |
| 1.01-2.0   | 16        | 25%     |
| 4.01-8.0   | 14        | 21.88%  |
| 3.01-4.0   | 8         | 12.5%   |
| 8.01-16.0  | 2         | 3.13%   |
| 0.51-1.0   | 2         | 3.13%   |
| 0.01-0.5   | 2         | 3.13%   |
| 16.01-24.0 | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 52.63%  |
| 2      | 15        | 26.32%  |
| 3      | 6         | 10.53%  |
| 4      | 3         | 5.26%   |
| 6      | 2         | 3.51%   |
| 7      | 1         | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 80.7%   |
| Yes       | 11        | 19.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 84.21%  |
| No        | 9         | 15.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 82.46%  |
| No        | 10        | 17.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 13        | 22.81%  |
| India                 | 7         | 12.28%  |
| Germany               | 4         | 7.02%   |
| Poland                | 3         | 5.26%   |
| Italy                 | 3         | 5.26%   |
| Greece                | 3         | 5.26%   |
| France                | 2         | 3.51%   |
| Canada                | 2         | 3.51%   |
| Australia             | 2         | 3.51%   |
| UK                    | 1         | 1.75%   |
| Turkey                | 1         | 1.75%   |
| Sweden                | 1         | 1.75%   |
| Spain                 | 1         | 1.75%   |
| Portugal              | 1         | 1.75%   |
| Palestinian Territory | 1         | 1.75%   |
| Pakistan              | 1         | 1.75%   |
| Norway                | 1         | 1.75%   |
| Morocco               | 1         | 1.75%   |
| Mongolia              | 1         | 1.75%   |
| Mexico                | 1         | 1.75%   |
| Malaysia              | 1         | 1.75%   |
| Lebanon               | 1         | 1.75%   |
| Israel                | 1         | 1.75%   |
| Hungary               | 1         | 1.75%   |
| Colombia              | 1         | 1.75%   |
| Brazil                | 1         | 1.75%   |
| Austria               | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Longmont        | 3         | 5.08%   |
| Melbourne       | 2         | 3.39%   |
| Athens          | 2         | 3.39%   |
| Zell am See     | 1         | 1.69%   |
| Wrexham         | 1         | 1.69%   |
| Wells           | 1         | 1.69%   |
| Warsaw          | 1         | 1.69%   |
| Vannes          | 1         | 1.69%   |
| Ulan Bator      | 1         | 1.69%   |
| Toronto         | 1         | 1.69%   |
| Tel Aviv        | 1         | 1.69%   |
| Taranto         | 1         | 1.69%   |
| Stuttgart       | 1         | 1.69%   |
| Springfield     | 1         | 1.69%   |
| Salt Lake City  | 1         | 1.69%   |
| Ramallah        | 1         | 1.69%   |
| Poznan          | 1         | 1.69%   |
| Pirmasens       | 1         | 1.69%   |
| Phoenix         | 1         | 1.69%   |
| Passos          | 1         | 1.69%   |
| Panchkula       | 1         | 1.69%   |
| Oslo            | 1         | 1.69%   |
| Oberursel       | 1         | 1.69%   |
| Neu-Ulm         | 1         | 1.69%   |
| Mumbai          | 1         | 1.69%   |
| Montreal        | 1         | 1.69%   |
| Monterrey       | 1         | 1.69%   |
| Madurai         | 1         | 1.69%   |
| Lucknow         | 1         | 1.69%   |
| Longview        | 1         | 1.69%   |
| Lisbon          | 1         | 1.69%   |
| Lamia           | 1         | 1.69%   |
| Kuala Lumpur    | 1         | 1.69%   |
| Kista           | 1         | 1.69%   |
| Istanbul        | 1         | 1.69%   |
| Islamabad       | 1         | 1.69%   |
| Granollers      | 1         | 1.69%   |
| Genoa           | 1         | 1.69%   |
| Gdansk          | 1         | 1.69%   |
| Ernakulam       | 1         | 1.69%   |
| East Malvern    | 1         | 1.69%   |
| Dunkirk         | 1         | 1.69%   |
| Denver          | 1         | 1.69%   |
| Danville        | 1         | 1.69%   |
| Chicago         | 1         | 1.69%   |
| Chennai         | 1         | 1.69%   |
| Casablanca      | 1         | 1.69%   |
| Budapest        | 1         | 1.69%   |
| Brisbane        | 1         | 1.69%   |
| Bogotá         | 1         | 1.69%   |
| Blairsville     | 1         | 1.69%   |
| Bhubaneswar     | 1         | 1.69%   |
| Beirut          | 1         | 1.69%   |
| Bari            | 1         | 1.69%   |
| Aix-en-Provence | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 20        | 32     | 20.41%  |
| WDC                       | 16        | 20     | 16.33%  |
| Samsung Electronics       | 16        | 27     | 16.33%  |
| Toshiba                   | 7         | 9      | 7.14%   |
| Kingston                  | 5         | 7      | 5.1%    |
| HGST                      | 4         | 4      | 4.08%   |
| Sandisk                   | 3         | 3      | 3.06%   |
| Phison                    | 3         | 3      | 3.06%   |
| Unknown                   | 2         | 2      | 2.04%   |
| Micron Technology         | 2         | 3      | 2.04%   |
| LITEON                    | 2         | 2      | 2.04%   |
| Intel                     | 2         | 3      | 2.04%   |
| China                     | 2         | 2      | 2.04%   |
| XPG                       | 1         | 1      | 1.02%   |
| PNY                       | 1         | 1      | 1.02%   |
| PLEXTOR                   | 1         | 1      | 1.02%   |
| Micron/Crucial Technology | 1         | 1      | 1.02%   |
| LITEONIT                  | 1         | 1      | 1.02%   |
| KIOXIA                    | 1         | 1      | 1.02%   |
| Intenso                   | 1         | 1      | 1.02%   |
| Hitachi                   | 1         | 1      | 1.02%   |
| GOODRAM                   | 1         | 1      | 1.02%   |
| Crucial                   | 1         | 1      | 1.02%   |
| Apple                     | 1         | 1      | 1.02%   |
| Apacer                    | 1         | 1      | 1.02%   |
| A-DATA Technology         | 1         | 1      | 1.02%   |
| 2-Power                   | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Seagate One Touch HDD 5TB                  | 3         | 2.68%   |
| Toshiba MQ04ABF100 1TB                     | 2         | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB             | 2         | 1.79%   |
| Seagate ST1000LM048-2E7172 1TB             | 2         | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 1.79%   |
| Samsung SSD 970 EVO 1TB                    | 2         | 1.79%   |
| Samsung SSD 860 EVO 1TB                    | 2         | 1.79%   |
| Kingston SA400S37240G 240GB SSD            | 2         | 1.79%   |
| HGST HTS545050A7E680 500GB                 | 2         | 1.79%   |
| XPG GAMMIX S50 1TB                         | 1         | 0.89%   |
| WDC WDS500G3XHC-00SJG0 500GB               | 1         | 0.89%   |
| WDC WDS500G3X0C-00SJG0 500GB               | 1         | 0.89%   |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1         | 0.89%   |
| WDC WDBNCE0010PNC 1TB SSD                  | 1         | 0.89%   |
| WDC WD800JD-00MSA1 80GB                    | 1         | 0.89%   |
| WDC WD7500BPKT-75PK4T0 752GB               | 1         | 0.89%   |
| WDC WD6400AAKS-22A7B2 640GB                | 1         | 0.89%   |
| WDC WD5000AAVS-00ZTB0 500GB                | 1         | 0.89%   |
| WDC WD5000AAKX-60U6AA0 500GB               | 1         | 0.89%   |
| WDC WD2500BEVT-60ZCT1 250GB                | 1         | 0.89%   |
| WDC WD2003FZEX-00SRLA0 2TB                 | 1         | 0.89%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1         | 0.89%   |
| WDC WD10EZEX-22MFCA0 1TB                   | 1         | 0.89%   |
| WDC WD1002FAEX-00Z3A0 1TB                  | 1         | 0.89%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB       | 1         | 0.89%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB       | 1         | 0.89%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 0.89%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB       | 1         | 0.89%   |
| Unknown MMC Card  64GB                     | 1         | 0.89%   |
| Unknown G1J38E  64GB                       | 1         | 0.89%   |
| Toshiba MQ01ABF050M 500GB                  | 1         | 0.89%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 0.89%   |
| Toshiba MK4058GSX 400GB                    | 1         | 0.89%   |
| Toshiba KBG40ZNT512G MEMORY 512GB          | 1         | 0.89%   |
| Toshiba KBG30ZMV256G 256GB                 | 1         | 0.89%   |
| Toshiba HDWR160 6TB                        | 1         | 0.89%   |
| Toshiba HDWE160 6TB                        | 1         | 0.89%   |
| Seagate ST9500325AS 500GB                  | 1         | 0.89%   |
| Seagate ST500LT012-9WS142 500GB            | 1         | 0.89%   |
| Seagate ST500LM000-SSHD-8GB                | 1         | 0.89%   |
| Seagate ST3500418AS 500GB                  | 1         | 0.89%   |
| Seagate ST250DM000-1BD141 250GB            | 1         | 0.89%   |
| Seagate ST2000DX001-1CM164 2TB             | 1         | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB             | 1         | 0.89%   |
| Seagate ST2000DM006-2DM164 2TB             | 1         | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB             | 1         | 0.89%   |
| Seagate ST1000VN002-2EY102 1TB             | 1         | 0.89%   |
| Seagate ST1000DX001-SSHD-8GB               | 1         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB             | 1         | 0.89%   |
| Seagate ST1000DM003-1SB102 1TB             | 1         | 0.89%   |
| Seagate ST10000NE0008-2JM101 10TB          | 1         | 0.89%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB | 1         | 0.89%   |
| Seagate Expansion+ 2TB                     | 1         | 0.89%   |
| Seagate Backup+ Hub BK 4TB                 | 1         | 0.89%   |
| SanDisk SDSSDH31024G 1TB                   | 1         | 0.89%   |
| Sandisk NVMe SSD Drive 500GB               | 1         | 0.89%   |
| Sandisk NVMe SSD Drive 256GB               | 1         | 0.89%   |
| Samsung SSD SM841 mSATA 128GB              | 1         | 0.89%   |
| Samsung SSD 980 PRO 2TB                    | 1         | 0.89%   |
| Samsung SSD 980 PRO 1TB                    | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 31     | 50%     |
| WDC                 | 9         | 11     | 22.5%   |
| Toshiba             | 5         | 7      | 12.5%   |
| HGST                | 4         | 4      | 10%     |
| Samsung Electronics | 1         | 1      | 2.5%    |
| Hitachi             | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 32%     |
| Kingston            | 3         | 4      | 12%     |
| LITEON              | 2         | 2      | 8%      |
| China               | 2         | 2      | 8%      |
| WDC                 | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| PLEXTOR             | 1         | 1      | 4%      |
| LITEONIT            | 1         | 1      | 4%      |
| GOODRAM             | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |
| Apacer              | 1         | 1      | 4%      |
| 2-Power             | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 32        | 55     | 37.65%  |
| NVMe    | 28        | 44     | 32.94%  |
| SSD     | 22        | 29     | 25.88%  |
| MMC     | 2         | 2      | 2.35%   |
| Unknown | 1         | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 80     | 54.55%  |
| NVMe | 28        | 44     | 36.36%  |
| SAS  | 5         | 5      | 6.49%   |
| MMC  | 2         | 2      | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 40     | 44.83%  |
| 0.51-1.0   | 21        | 29     | 36.21%  |
| 1.01-2.0   | 5         | 8      | 8.62%   |
| 4.01-10.0  | 5         | 6      | 8.62%   |
| 3.01-4.0   | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 18        | 29.51%  |
| 1001-2000      | 15        | 24.59%  |
| 501-1000       | 8         | 13.11%  |
| 251-500        | 5         | 8.2%    |
| Unknown        | 4         | 6.56%   |
| 1-20           | 3         | 4.92%   |
| 51-100         | 3         | 4.92%   |
| 2001-3000      | 2         | 3.28%   |
| 101-250        | 2         | 3.28%   |
| 21-50          | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 32.26%  |
| 51-100         | 15        | 24.19%  |
| 1-20           | 9         | 14.52%  |
| 501-1000       | 4         | 6.45%   |
| Unknown        | 4         | 6.45%   |
| 251-500        | 3         | 4.84%   |
| 1001-2000      | 3         | 4.84%   |
| 2001-3000      | 2         | 3.23%   |
| More than 3000 | 1         | 1.61%   |
| 21-50          | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 1      | 7.14%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 2      | 7.14%   |
| Toshiba MQ01ABF050M 500GB        | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 7.14%   |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 7.14%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 7.14%   |
| Seagate ST500LM000-SSHD-8GB      | 1         | 1      | 7.14%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 7.14%   |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 1      | 7.14%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 1      | 7.14%   |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 7.14%   |
| Hitachi HTS725050A9A364 500GB    | 1         | 1      | 7.14%   |
| HGST HTS725032A7E630 320GB       | 1         | 1      | 7.14%   |
| China SATA3 240GB SSD            | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 38.46%  |
| WDC      | 2         | 3      | 15.38%  |
| Toshiba  | 2         | 3      | 15.38%  |
| Kingston | 1         | 1      | 7.69%   |
| Hitachi  | 1         | 1      | 7.69%   |
| HGST     | 1         | 1      | 7.69%   |
| China    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 45.45%  |
| WDC     | 2         | 3      | 18.18%  |
| Toshiba | 2         | 3      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 84.62%  |
| SSD  | 2         | 2      | 15.38%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 44        | 88     | 62.86%  |
| Detected | 13        | 28     | 18.57%  |
| Malfunc  | 13        | 15     | 18.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 52.94%  |
| Samsung Electronics          | 9         | 10.59%  |
| AMD                          | 9         | 10.59%  |
| Sandisk                      | 8         | 9.41%   |
| Phison Electronics           | 3         | 3.53%   |
| Toshiba America Info Systems | 2         | 2.35%   |
| Micron Technology            | 2         | 2.35%   |
| Kingston Technology Company  | 2         | 2.35%   |
| Seagate Technology           | 1         | 1.18%   |
| Realtek Semiconductor        | 1         | 1.18%   |
| Micron/Crucial Technology    | 1         | 1.18%   |
| KIOXIA                       | 1         | 1.18%   |
| ADATA Technology             | 1         | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 8.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 5.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 5.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 4.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 4.35%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 3.26%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 3.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 3.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 3.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 2.17%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.17%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.17%   |
| Micron Non-Volatile memory controller                                          | 2         | 2.17%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.17%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 2.17%   |
| Intel SSD 660P Series                                                          | 2         | 2.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.17%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.09%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.09%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.09%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.09%   |
| Samsung Apple PCIe SSD                                                         | 1         | 1.09%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.09%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.09%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.09%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.09%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.09%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.09%   |
| AMD FCH SATA Controller D                                                      | 1         | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.09%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.09%   |
| ADATA Non-Volatile memory controller                                           | 1         | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 55.95%  |
| NVMe | 28        | 33.33%  |
| RAID | 9         | 10.71%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 82.46%  |
| AMD    | 10        | 17.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 5.26%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 3         | 5.26%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 3.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 3.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 3.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.51%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1         | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 1.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.75%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.75%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 1.75%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.75%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.75%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 1         | 1.75%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.75%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1         | 1.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.75%   |
| Intel Core i5-4670 CPU @ 3.40GHz              | 1         | 1.75%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 1.75%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 1.75%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.75%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1         | 1.75%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1         | 1.75%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.75%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz         | 1         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.75%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.75%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 1.75%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.75%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 19        | 33.33%  |
| Intel Core i5     | 18        | 31.58%  |
| AMD Ryzen 5       | 5         | 8.77%   |
| Intel Core i3     | 4         | 7.02%   |
| Other             | 3         | 5.26%   |
| AMD Ryzen 7       | 2         | 3.51%   |
| Intel Genuine     | 1         | 1.75%   |
| Intel Core 2 Quad | 1         | 1.75%   |
| Intel Celeron     | 1         | 1.75%   |
| AMD Ryzen 9       | 1         | 1.75%   |
| AMD Ryzen 3       | 1         | 1.75%   |
| AMD Athlon        | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 27        | 47.37%  |
| 2      | 16        | 28.07%  |
| 6      | 9         | 15.79%  |
| 8      | 4         | 7.02%   |
| 12     | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 82.76%  |
| 1      | 10        | 17.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 22.03%  |
| 0x906ea    | 4         | 6.78%   |
| 0x806ec    | 4         | 6.78%   |
| 0x806e9    | 4         | 6.78%   |
| 0x806c1    | 3         | 5.08%   |
| 0x506e3    | 3         | 5.08%   |
| 0x306a9    | 3         | 5.08%   |
| 0x08701021 | 3         | 5.08%   |
| 0x906ed    | 2         | 3.39%   |
| 0x906e9    | 2         | 3.39%   |
| 0x306c3    | 2         | 3.39%   |
| 0x0a201016 | 2         | 3.39%   |
| 0xa0652    | 1         | 1.69%   |
| 0x906eb    | 1         | 1.69%   |
| 0x806eb    | 1         | 1.69%   |
| 0x706e5    | 1         | 1.69%   |
| 0x706a8    | 1         | 1.69%   |
| 0x406e3    | 1         | 1.69%   |
| 0x40651    | 1         | 1.69%   |
| 0x206a7    | 1         | 1.69%   |
| 0x20655    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08701013 | 1         | 1.69%   |
| 0x08600106 | 1         | 1.69%   |
| 0x08108109 | 1         | 1.69%   |
| 0x0810100b | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 36.84%  |
| Haswell       | 7         | 12.28%  |
| Zen 2         | 5         | 8.77%   |
| Skylake       | 4         | 7.02%   |
| IvyBridge     | 4         | 7.02%   |
| TigerLake     | 3         | 5.26%   |
| Zen+          | 2         | 3.51%   |
| Zen 3         | 2         | 3.51%   |
| SandyBridge   | 2         | 3.51%   |
| Zen           | 1         | 1.75%   |
| Westmere      | 1         | 1.75%   |
| Penryn        | 1         | 1.75%   |
| Nehalem       | 1         | 1.75%   |
| IceLake       | 1         | 1.75%   |
| Goldmont plus | 1         | 1.75%   |
| CometLake     | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 46.25%  |
| Nvidia | 31        | 38.75%  |
| AMD    | 12        | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 5%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 5%      |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 3         | 3.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 3.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 3.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 3         | 3.75%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 2.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 2.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 2         | 2.5%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 2.5%    |
| Intel UHD Graphics 620                                                                | 2         | 2.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 2.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.25%   |
| Nvidia TU117M                                                                         | 1         | 1.25%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 1.25%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.25%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 1.25%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 1.25%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 1         | 1.25%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 1.25%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.25%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 1.25%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.25%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 1         | 1.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 1         | 1.25%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 1.25%   |
| Nvidia GK107 [GeForce GT 740]                                                         | 1         | 1.25%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 1.25%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.25%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                        | 1         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 1.25%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 1.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.25%   |
| Intel HD Graphics 630                                                                 | 1         | 1.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.25%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                      | 1         | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.25%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                    | 1         | 1.25%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.25%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 1.25%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 1         | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 1         | 1.25%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                      | 1         | 1.25%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 19        | 33.33%  |
| 1 x Intel      | 14        | 24.56%  |
| 1 x Nvidia     | 12        | 21.05%  |
| 1 x AMD        | 9         | 15.79%  |
| Intel + AMD    | 3         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 55.17%  |
| Proprietary | 24        | 41.38%  |
| Unknown     | 2         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 58.62%  |
| 1.01-2.0   | 11        | 18.97%  |
| 7.01-8.0   | 5         | 8.62%   |
| 5.01-6.0   | 4         | 6.9%    |
| 0.01-0.5   | 2         | 3.45%   |
| 3.01-4.0   | 1         | 1.72%   |
| 8.01-16.0  | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 18.18%  |
| BOE                  | 8         | 12.12%  |
| AU Optronics         | 8         | 12.12%  |
| Chimei Innolux       | 6         | 9.09%   |
| LG Display           | 5         | 7.58%   |
| Sharp                | 3         | 4.55%   |
| Ancor Communications | 3         | 4.55%   |
| Hewlett-Packard      | 2         | 3.03%   |
| Goldstar             | 2         | 3.03%   |
| Dell                 | 2         | 3.03%   |
| Apple                | 2         | 3.03%   |
| AOC                  | 2         | 3.03%   |
| Acer                 | 2         | 3.03%   |
| Sceptre Tech         | 1         | 1.52%   |
| PANDA                | 1         | 1.52%   |
| Lenovo               | 1         | 1.52%   |
| Kogan                | 1         | 1.52%   |
| KOC                  | 1         | 1.52%   |
| Idek Iiyama          | 1         | 1.52%   |
| Hitachi              | 1         | 1.52%   |
| Gigabyte Technology  | 1         | 1.52%   |
| ASUSTek Computer     | 1         | 1.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 2.99%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 2.99%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 1.49%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.49%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.49%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 1.49%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 1.49%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.49%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 1.49%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 1.49%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.49%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.49%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.49%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.49%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch                | 1         | 1.49%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 1.49%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                               | 1         | 1.49%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 1         | 1.49%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch             | 1         | 1.49%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 1         | 1.49%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 1         | 1.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1         | 1.49%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch          | 1         | 1.49%   |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                       | 1         | 1.49%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 1.49%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.49%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                   | 1         | 1.49%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                   | 1         | 1.49%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 1.49%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 1         | 1.49%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 1         | 1.49%   |
| BOE LCD Monitor BOE06D1 1366x768 309x173mm 13.9-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 1         | 1.49%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.49%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch          | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.49%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch          | 1         | 1.49%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 1         | 1.49%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                   | 1         | 1.49%   |
| AOC 27G2G4 AOC2702 1920x1080 600x340mm 27.2-inch                        | 1         | 1.49%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                        | 1         | 1.49%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch        | 1         | 1.49%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch   | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 31        | 50%     |
| 3840x2160 (4K)    | 8         | 12.9%   |
| 1366x768 (WXGA)   | 7         | 11.29%  |
| 2560x1440 (QHD)   | 4         | 6.45%   |
| 3440x1440         | 3         | 4.84%   |
| 3840x1080         | 1         | 1.61%   |
| 3200x1800 (QHD+)  | 1         | 1.61%   |
| 2560x1080         | 1         | 1.61%   |
| 2160x1440         | 1         | 1.61%   |
| 1920x540          | 1         | 1.61%   |
| 1920x1200 (WUXGA) | 1         | 1.61%   |
| 1600x900 (HD+)    | 1         | 1.61%   |
| 1440x900 (WXGA+)  | 1         | 1.61%   |
| 1280x1024 (SXGA)  | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 36.92%  |
| 27      | 5         | 7.69%   |
| 84      | 4         | 6.15%   |
| 14      | 4         | 6.15%   |
| 13      | 4         | 6.15%   |
| 34      | 3         | 4.62%   |
| 31      | 3         | 4.62%   |
| 24      | 3         | 4.62%   |
| 23      | 3         | 4.62%   |
| 21      | 3         | 4.62%   |
| 18      | 2         | 3.08%   |
| Unknown | 2         | 3.08%   |
| 54      | 1         | 1.54%   |
| 48      | 1         | 1.54%   |
| 28      | 1         | 1.54%   |
| 17      | 1         | 1.54%   |
| 12      | 1         | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 46.15%  |
| 501-600     | 10        | 15.38%  |
| 401-500     | 5         | 7.69%   |
| 601-700     | 4         | 6.15%   |
| 1501-2000   | 4         | 6.15%   |
| 701-800     | 3         | 4.62%   |
| 201-300     | 3         | 4.62%   |
| 351-400     | 2         | 3.08%   |
| 1001-1500   | 2         | 3.08%   |
| Unknown     | 2         | 3.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 47        | 82.46%  |
| 21/9    | 4         | 7.02%   |
| 16/10   | 2         | 3.51%   |
| 5/4     | 1         | 1.75%   |
| 32/9    | 1         | 1.75%   |
| 3/2     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 37.5%   |
| 201-250        | 8         | 12.5%   |
| 81-90          | 7         | 10.94%  |
| 351-500        | 6         | 9.38%   |
| More than 1000 | 5         | 7.81%   |
| 301-350        | 5         | 7.81%   |
| Unknown        | 2         | 3.13%   |
| 71-80          | 1         | 1.56%   |
| 61-70          | 1         | 1.56%   |
| 251-300        | 1         | 1.56%   |
| 151-200        | 1         | 1.56%   |
| 141-150        | 1         | 1.56%   |
| 121-130        | 1         | 1.56%   |
| 501-1000       | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 40.98%  |
| 51-100        | 15        | 24.59%  |
| 101-120       | 13        | 21.31%  |
| 161-240       | 3         | 4.92%   |
| More than 240 | 2         | 3.28%   |
| Unknown       | 2         | 3.28%   |
| 1-50          | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 75.86%  |
| 2     | 11        | 18.97%  |
| 0     | 2         | 3.45%   |
| 3     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 35        | 42.17%  |
| Realtek Semiconductor             | 30        | 36.14%  |
| Qualcomm Atheros                  | 4         | 4.82%   |
| Broadcom Limited                  | 3         | 3.61%   |
| ASIX Electronics                  | 3         | 3.61%   |
| Broadcom                          | 2         | 2.41%   |
| TP-Link                           | 1         | 1.2%    |
| Samsung Electronics               | 1         | 1.2%    |
| Qualcomm                          | 1         | 1.2%    |
| NetGear                           | 1         | 1.2%    |
| Microsoft                         | 1         | 1.2%    |
| Ericsson Business Mobile Networks | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 22        | 21.78%  |
| Intel Wi-Fi 6 AX200                                                       | 5         | 4.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 4.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 4         | 3.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 2.97%   |
| Realtek RTL8125 2.5GbE Controller                                         | 3         | 2.97%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 2.97%   |
| Intel I211 Gigabit Network Connection                                     | 3         | 2.97%   |
| Intel Ethernet Connection (2) I219-V                                      | 3         | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 2.97%   |
| ASIX AX88179 Gigabit Ethernet                                             | 3         | 2.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 2         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 1.98%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.98%   |
| Intel Wireless 8265 / 8275                                                | 2         | 1.98%   |
| Intel Ethernet Connection (7) I219-V                                      | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 1.98%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 1.98%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 0.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1         | 0.99%   |
| Qualcomm Mobile Router                                                    | 1         | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1         | 0.99%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.99%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.99%   |
| Intel Wireless 8260                                                       | 1         | 0.99%   |
| Intel Wireless 7260                                                       | 1         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.99%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.99%   |
| Intel Ethernet Connection I217-LM                                         | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                     | 1         | 0.99%   |
| Intel Ethernet Connection (13) I219-V                                     | 1         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 0.99%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 0.99%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 0.99%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module        | 1         | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1         | 0.99%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 0.99%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 62.5%   |
| Realtek Semiconductor | 7         | 14.58%  |
| Qualcomm Atheros      | 3         | 6.25%   |
| Broadcom Limited      | 3         | 6.25%   |
| Broadcom              | 2         | 4.17%   |
| TP-Link               | 1         | 2.08%   |
| NetGear               | 1         | 2.08%   |
| Microsoft             | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 5         | 10.42%  |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 10.42%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 6.25%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 6.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 4.17%   |
| Intel Wireless-AC 9260                                                    | 2         | 4.17%   |
| Intel Wireless 8265 / 8275                                                | 2         | 4.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 4.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 4.17%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 4.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 2.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 2.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 2.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 2.08%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 2.08%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 2.08%   |
| Intel Wireless 8260                                                       | 1         | 2.08%   |
| Intel Wireless 7260                                                       | 1         | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 2.08%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 2.08%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 2.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 2.08%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 53.85%  |
| Intel                 | 16        | 30.77%  |
| ASIX Electronics      | 3         | 5.77%   |
| Qualcomm Atheros      | 2         | 3.85%   |
| Samsung Electronics   | 1         | 1.92%   |
| Qualcomm              | 1         | 1.92%   |
| Broadcom              | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 42.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.77%   |
| Intel I211 Gigabit Network Connection                             | 3         | 5.77%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 5.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 5.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.85%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 3.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.92%   |
| Qualcomm Mobile Router                                            | 1         | 1.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.92%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.92%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 50%     |
| WiFi     | 47        | 48.96%  |
| Modem    | 1         | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 61.9%   |
| Ethernet | 24        | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 50.88%  |
| 1     | 25        | 43.86%  |
| 3     | 2         | 3.51%   |
| 0     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 74.14%  |
| Yes  | 15        | 25.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 55.56%  |
| Broadcom                        | 6         | 13.33%  |
| Realtek Semiconductor           | 5         | 11.11%  |
| IMC Networks                    | 2         | 4.44%   |
| Cambridge Silicon Radio         | 2         | 4.44%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |
| Lite-On Technology              | 1         | 2.22%   |
| Dell                            | 1         | 2.22%   |
| ASUSTek Computer                | 1         | 2.22%   |
| Apple                           | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 24.44%  |
| Intel AX200 Bluetooth                               | 5         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 6.67%   |
| Intel Bluetooth wireless interface                  | 3         | 6.67%   |
| Intel Bluetooth Device                              | 3         | 6.67%   |
| Realtek Bluetooth Radio                             | 2         | 4.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4.44%   |
| IMC Networks Bluetooth Radio                        | 2         | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.44%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 4.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.22%   |
| Lite-On Bluetooth Device                            | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.22%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.22%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.22%   |
| Broadcom BCM2045A0                                  | 1         | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.22%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 47        | 52.22%  |
| Nvidia                 | 18        | 20%     |
| AMD                    | 12        | 13.33%  |
| Razer USA              | 2         | 2.22%   |
| Corsair                | 2         | 2.22%   |
| C-Media Electronics    | 2         | 2.22%   |
| Tenx Technology        | 1         | 1.11%   |
| Samsung Electronics    | 1         | 1.11%   |
| Plantronics            | 1         | 1.11%   |
| Logitech               | 1         | 1.11%   |
| Kingston Technology    | 1         | 1.11%   |
| Hewlett-Packard        | 1         | 1.11%   |
| Generalplus Technology | 1         | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 6.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 6.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 4.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.91%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 2.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.94%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.94%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.94%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.97%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.97%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1         | 0.97%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.97%   |
| Plantronics C320-M                                                         | 1         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.97%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.97%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.97%   |
| Logitech G633 Gaming Headset                                               | 1         | 0.97%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.97%   |
| Hewlett-Packard E240C                                                      | 1         | 0.97%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.97%   |
| Corsair Slipstream Multi-Device Receiver                                   | 1         | 0.97%   |
| Corsair HS60 PRO Surround USB Sound Adapter                                | 1         | 0.97%   |
| C-Media Electronics USB Modi Device                                        | 1         | 0.97%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 0.97%   |
| C-Media Electronics Blue Snowball                                          | 1         | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 25.42%  |
| Samsung Electronics | 13        | 22.03%  |
| Micron Technology   | 6         | 10.17%  |
| G.Skill             | 5         | 8.47%   |
| Corsair             | 5         | 8.47%   |
| Kingston            | 4         | 6.78%   |
| Crucial             | 4         | 6.78%   |
| Unknown             | 2         | 3.39%   |
| Ramaxel Technology  | 2         | 3.39%   |
| Unifosa             | 1         | 1.69%   |
| Team                | 1         | 1.69%   |
| PNY                 | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 4.84%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 3.23%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 3.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.61%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.61%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 1.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s             | 1         | 1.61%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.61%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.61%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.61%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 1.61%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.61%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 1.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.61%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s              | 1         | 1.61%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.61%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.61%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 1.61%   |
| Kingston RAM KHYXPX-MID 8192MB SODIMM DDR4 2667MT/s              | 1         | 1.61%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s              | 1         | 1.61%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Kingston RAM 99U5428-069.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.61%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s              | 1         | 1.61%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 1         | 1.61%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s           | 1         | 1.61%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 1         | 1.61%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s             | 1         | 1.61%   |
| G.Skill RAM F4-3200C16-8GTZKO 8GB DIMM DDR4 3200MT/s             | 1         | 1.61%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s          | 1         | 1.61%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4096MB DIMM DDR4 2400MT/s         | 1         | 1.61%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s            | 1         | 1.61%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 1.61%   |
| Corsair RAM CMSO16GX4M2A2133C15 8GB SODIMM DDR4 2667MT/s         | 1         | 1.61%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s             | 1         | 1.61%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 1         | 1.61%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s            | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 68.75%  |
| DDR3   | 11        | 22.92%  |
| SDRAM  | 1         | 2.08%   |
| LPDDR4 | 1         | 2.08%   |
| LPDDR3 | 1         | 2.08%   |
| DDR2   | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 55.1%   |
| DIMM         | 17        | 34.69%  |
| Row Of Chips | 5         | 10.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 48.08%  |
| 4096  | 17        | 32.69%  |
| 16384 | 8         | 15.38%  |
| 2048  | 2         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 15        | 27.78%  |
| 1600  | 9         | 16.67%  |
| 3200  | 8         | 14.81%  |
| 2400  | 4         | 7.41%   |
| 3266  | 2         | 3.7%    |
| 4400  | 1         | 1.85%   |
| 4267  | 1         | 1.85%   |
| 4199  | 1         | 1.85%   |
| 4133  | 1         | 1.85%   |
| 3800  | 1         | 1.85%   |
| 3600  | 1         | 1.85%   |
| 3400  | 1         | 1.85%   |
| 3067  | 1         | 1.85%   |
| 2933  | 1         | 1.85%   |
| 2747  | 1         | 1.85%   |
| 2666  | 1         | 1.85%   |
| 2176  | 1         | 1.85%   |
| 2133  | 1         | 1.85%   |
| 1450  | 1         | 1.85%   |
| 1333  | 1         | 1.85%   |
| 800   | 1         | 1.85%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 18.42%  |
| Realtek Semiconductor                  | 6         | 15.79%  |
| IMC Networks                           | 6         | 15.79%  |
| Acer                                   | 4         | 10.53%  |
| Quanta                                 | 3         | 7.89%   |
| Syntek                                 | 2         | 5.26%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Microdia                               | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.26%   |
| Logitech                               | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| Generalplus Technology                 | 1         | 2.63%   |
| Alpha Imaging Technology               | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                         | 3         | 7.89%   |
| Syntek Integrated Camera                                             | 2         | 5.26%   |
| Quanta HP TrueVision HD Camera                                       | 2         | 5.26%   |
| IMC Networks USB2.0 VGA UVC WebCam                                   | 2         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                                    | 2         | 5.26%   |
| Chicony Integrated Camera                                            | 2         | 5.26%   |
| Chicony EasyCamera                                                   | 2         | 5.26%   |
| Acer ThinkPad Integrated Camera                                      | 2         | 5.26%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 2.63%   |
| Sunplus HP Truevision HD                                             | 1         | 2.63%   |
| Realtek Integrated Webcam_HD                                         | 1         | 2.63%   |
| Realtek Integrated Webcam                                            | 1         | 2.63%   |
| Realtek Built-In Video Camera                                        | 1         | 2.63%   |
| Quanta HD User Facing                                                | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD                                        | 1         | 2.63%   |
| Microdia Dell Integrated HD Webcam                                   | 1         | 2.63%   |
| Logitech Webcam C600                                                 | 1         | 2.63%   |
| Lite-On Integrated Camera                                            | 1         | 2.63%   |
| IMC Networks VGA UVC WebCam                                          | 1         | 2.63%   |
| IMC Networks Integrated Camera                                       | 1         | 2.63%   |
| Generalplus GENERAL WEBCAM                                           | 1         | 2.63%   |
| Chicony HP Webcam                                                    | 1         | 2.63%   |
| Chicony HP High Definition 1MP Webcam                                | 1         | 2.63%   |
| Chicony HD User Facing                                               | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                     | 1         | 2.63%   |
| Alpha Imaging Integrated_Webcam_8M                                   | 1         | 2.63%   |
| Acer SunplusIT Integrated Camera                                     | 1         | 2.63%   |
| Acer HD Webcam                                                       | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Elan Microelectronics      | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 1         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device | 1         | 33.33%  |
| Elan ELAN:Fingerprint               | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 42        | 72.41%  |
| 1     | 13        | 22.41%  |
| 2     | 3         | 5.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 26.32%  |
| Fingerprint reader    | 3         | 15.79%  |
| Chipcard              | 3         | 15.79%  |
| Camera                | 2         | 10.53%  |
| Bluetooth             | 2         | 10.53%  |
| Storage               | 1         | 5.26%   |
| Network               | 1         | 5.26%   |
| Net/wireless          | 1         | 5.26%   |
| Multimedia controller | 1         | 5.26%   |

