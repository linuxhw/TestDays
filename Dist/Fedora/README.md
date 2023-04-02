Fedora - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Fedora.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora/Desktop/README.md) and [notebooks](/Dist/Fedora/Notebook/README.md).

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

Total: 16504

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B250M-A               | Desktop     | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [41353f6a59](https://linux-hardware.org/?probe=41353f6a59) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [ca8ae50d80](https://linux-hardware.org/?probe=ca8ae50d80) | Mar 31, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e18d9530c1](https://linux-hardware.org/?probe=e18d9530c1) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [bb2f5a2276](https://linux-hardware.org/?probe=bb2f5a2276) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | Notebook    | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | Desktop     | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fcb2279eb0](https://linux-hardware.org/?probe=fcb2279eb0) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [162132b606](https://linux-hardware.org/?probe=162132b606) | Mar 30, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| HP            | 18E7                        | Desktop     | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [21eb6fba07](https://linux-hardware.org/?probe=21eb6fba07) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Dell          | Latitude 5580               | Notebook    | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | Notebook    | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | Notebook    | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | Desktop     | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | Notebook    | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [042e72aea5](https://linux-hardware.org/?probe=042e72aea5) | Mar 28, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | Notebook    | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [e5644591de](https://linux-hardware.org/?probe=e5644591de) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [35510eaf63](https://linux-hardware.org/?probe=35510eaf63) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | Desktop     | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | Desktop     | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| HP            | Compaq 6720s                | Notebook    | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fc1af1a499](https://linux-hardware.org/?probe=fc1af1a499) | Mar 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ccc0edffff](https://linux-hardware.org/?probe=ccc0edffff) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| Dell          | Latitude E5250              | Notebook    | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Alienware     | 17 R4                       | Notebook    | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Acer          | Aspire M3910                | Desktop     | [8cc87c48d1](https://linux-hardware.org/?probe=8cc87c48d1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Dell          | Latitude 7410               | Convertible | [59c5a72671](https://linux-hardware.org/?probe=59c5a72671) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | Desktop     | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| MSI           | 2AE0                        | Desktop     | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | Notebook    | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | Notebook    | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [55f0bb1013](https://linux-hardware.org/?probe=55f0bb1013) | Mar 24, 2023 |
| Dell          | Precision 3551              | Notebook    | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | Notebook    | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [01cac0e411](https://linux-hardware.org/?probe=01cac0e411) | Mar 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [88900a37b9](https://linux-hardware.org/?probe=88900a37b9) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| PCWare        | IPMH310G                    | Desktop     | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3769ec9ab5](https://linux-hardware.org/?probe=3769ec9ab5) | Mar 24, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [1ee3769d23](https://linux-hardware.org/?probe=1ee3769d23) | Mar 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Itautec       | ST 4265                     | Desktop     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | Notebook    | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [85accc79b1](https://linux-hardware.org/?probe=85accc79b1) | Mar 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ff60b91842](https://linux-hardware.org/?probe=ff60b91842) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | Notebook    | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | Desktop     | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [950e4b69e8](https://linux-hardware.org/?probe=950e4b69e8) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aad036448d](https://linux-hardware.org/?probe=aad036448d) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [80e6d9af10](https://linux-hardware.org/?probe=80e6d9af10) | Mar 22, 2023 |
| Lenovo        | ThinkPad L380 20M6S3Q000    | Notebook    | [aab8aada0e](https://linux-hardware.org/?probe=aab8aada0e) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [5298c41263](https://linux-hardware.org/?probe=5298c41263) | Mar 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7b899e790a](https://linux-hardware.org/?probe=7b899e790a) | Mar 22, 2023 |
| Intel         | NUC6CAYB J23203-402         | Mini pc     | [5d6fe54adf](https://linux-hardware.org/?probe=5d6fe54adf) | Mar 22, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [ac5768cd3f](https://linux-hardware.org/?probe=ac5768cd3f) | Mar 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| HP            | 158A                        | Desktop     | [4bcb73e1bf](https://linux-hardware.org/?probe=4bcb73e1bf) | Mar 22, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [386f37d114](https://linux-hardware.org/?probe=386f37d114) | Mar 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8dfc670e24](https://linux-hardware.org/?probe=8dfc670e24) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| NZXT          | N7 B550                     | Desktop     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [dbbcf4a29a](https://linux-hardware.org/?probe=dbbcf4a29a) | Mar 21, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [87bce00c67](https://linux-hardware.org/?probe=87bce00c67) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e7ff5cdaae](https://linux-hardware.org/?probe=e7ff5cdaae) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| Notebook      | W51XTU                      | Notebook    | [de60f3fcba](https://linux-hardware.org/?probe=de60f3fcba) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [e7eb855568](https://linux-hardware.org/?probe=e7eb855568) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [1686ba2df4](https://linux-hardware.org/?probe=1686ba2df4) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [b5a517c552](https://linux-hardware.org/?probe=b5a517c552) | Mar 20, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [3c0b6b8fdf](https://linux-hardware.org/?probe=3c0b6b8fdf) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Win elemen... | M600                        | Desktop     | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [58900f0caa](https://linux-hardware.org/?probe=58900f0caa) | Mar 19, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cb27b0fbaf](https://linux-hardware.org/?probe=cb27b0fbaf) | Mar 19, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [4ad2d5c249](https://linux-hardware.org/?probe=4ad2d5c249) | Mar 19, 2023 |
| Prestigio     | PSB141C01BFH                | Notebook    | [9190e0a0e7](https://linux-hardware.org/?probe=9190e0a0e7) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [1ff56ed31f](https://linux-hardware.org/?probe=1ff56ed31f) | Mar 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| HONOR         | GLO-FX6P                    | Notebook    | [0fb3ebc365](https://linux-hardware.org/?probe=0fb3ebc365) | Mar 19, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [972b8e8c3c](https://linux-hardware.org/?probe=972b8e8c3c) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| Unknown       | V00                         | Mini pc     | [6a0c74a051](https://linux-hardware.org/?probe=6a0c74a051) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [d84f3134b9](https://linux-hardware.org/?probe=d84f3134b9) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [08df29b00e](https://linux-hardware.org/?probe=08df29b00e) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7dd8257bc8](https://linux-hardware.org/?probe=7dd8257bc8) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| ZOTAC         | H67ITX-C-E                  | Desktop     | [1da59d5440](https://linux-hardware.org/?probe=1da59d5440) | Mar 17, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8d2db4b0fe](https://linux-hardware.org/?probe=8d2db4b0fe) | Mar 17, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [4e6f4d1197](https://linux-hardware.org/?probe=4e6f4d1197) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [ed14fd6e80](https://linux-hardware.org/?probe=ed14fd6e80) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [b09959cc0b](https://linux-hardware.org/?probe=b09959cc0b) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [7ee3dac323](https://linux-hardware.org/?probe=7ee3dac323) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [fc2a6e486c](https://linux-hardware.org/?probe=fc2a6e486c) | Mar 17, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [47a9ec2aa1](https://linux-hardware.org/?probe=47a9ec2aa1) | Mar 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d00b579583](https://linux-hardware.org/?probe=d00b579583) | Mar 16, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [f2b9853f35](https://linux-hardware.org/?probe=f2b9853f35) | Mar 16, 2023 |
| Medion        | B550A4-EM                   | Desktop     | [458aea611f](https://linux-hardware.org/?probe=458aea611f) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS1N00... | Notebook    | [03b210c1f8](https://linux-hardware.org/?probe=03b210c1f8) | Mar 16, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [73eb93b06f](https://linux-hardware.org/?probe=73eb93b06f) | Mar 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | Notebook    | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [d36124f8d9](https://linux-hardware.org/?probe=d36124f8d9) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [ea6af9ac0b](https://linux-hardware.org/?probe=ea6af9ac0b) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [56c7261b06](https://linux-hardware.org/?probe=56c7261b06) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | Desktop     | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [c483268c88](https://linux-hardware.org/?probe=c483268c88) | Mar 16, 2023 |
| Unknown       | V00                         | Mini pc     | [3a2e981385](https://linux-hardware.org/?probe=3a2e981385) | Mar 16, 2023 |
| Dell          | Latitude E6430              | Notebook    | [e48fceb5f2](https://linux-hardware.org/?probe=e48fceb5f2) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [8f1af30bba](https://linux-hardware.org/?probe=8f1af30bba) | Mar 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | Notebook    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| Dell          | Latitude 7430               | Notebook    | [58024877c3](https://linux-hardware.org/?probe=58024877c3) | Mar 15, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [79c13317c6](https://linux-hardware.org/?probe=79c13317c6) | Mar 15, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1e802bfcd0](https://linux-hardware.org/?probe=1e802bfcd0) | Mar 15, 2023 |
| Dell          | Latitude 5530               | Notebook    | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [3d1c928bcb](https://linux-hardware.org/?probe=3d1c928bcb) | Mar 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [6c73c46184](https://linux-hardware.org/?probe=6c73c46184) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [7bd981d445](https://linux-hardware.org/?probe=7bd981d445) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [430599b2da](https://linux-hardware.org/?probe=430599b2da) | Mar 14, 2023 |
| Lenovo        | ThinkPad T490 20N3S3UL00    | Notebook    | [a9db94aee2](https://linux-hardware.org/?probe=a9db94aee2) | Mar 14, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [112d979fc6](https://linux-hardware.org/?probe=112d979fc6) | Mar 14, 2023 |
| MSI           | MS-AEA11                    | All in one  | [b1afba007b](https://linux-hardware.org/?probe=b1afba007b) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Intel         | W2600CR G21602-308          | Server      | [96cda648c2](https://linux-hardware.org/?probe=96cda648c2) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [eac2f2ae40](https://linux-hardware.org/?probe=eac2f2ae40) | Mar 14, 2023 |
| System76      | Gazelle                     | Notebook    | [d45f36e46f](https://linux-hardware.org/?probe=d45f36e46f) | Mar 14, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [37edbdcce5](https://linux-hardware.org/?probe=37edbdcce5) | Mar 14, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [e6792912bf](https://linux-hardware.org/?probe=e6792912bf) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [047e561901](https://linux-hardware.org/?probe=047e561901) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [6ecc8f0bad](https://linux-hardware.org/?probe=6ecc8f0bad) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [13f42eb616](https://linux-hardware.org/?probe=13f42eb616) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [70de894994](https://linux-hardware.org/?probe=70de894994) | Mar 13, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [815dfc26ec](https://linux-hardware.org/?probe=815dfc26ec) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Acer          | Aspire R7-371T              | Notebook    | [b6aef449b6](https://linux-hardware.org/?probe=b6aef449b6) | Mar 13, 2023 |
| Lenovo        | Yoga 6-13ALC7 82UD          | Convertible | [6e3643ecb4](https://linux-hardware.org/?probe=6e3643ecb4) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | Notebook    | [1e037723cc](https://linux-hardware.org/?probe=1e037723cc) | Mar 12, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [000c3e4761](https://linux-hardware.org/?probe=000c3e4761) | Mar 12, 2023 |
| Acer          | One S1003                   | Tablet      | [89fff0b13a](https://linux-hardware.org/?probe=89fff0b13a) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Insyde        | BayTrail                    | Notebook    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1875fd875d](https://linux-hardware.org/?probe=1875fd875d) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f70aee3bd6](https://linux-hardware.org/?probe=f70aee3bd6) | Mar 12, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [03c104f5f3](https://linux-hardware.org/?probe=03c104f5f3) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a8b88087b](https://linux-hardware.org/?probe=8a8b88087b) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [8aff6217a5](https://linux-hardware.org/?probe=8aff6217a5) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2a0539c2b1](https://linux-hardware.org/?probe=2a0539c2b1) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | Desktop     | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [5d69c96eca](https://linux-hardware.org/?probe=5d69c96eca) | Mar 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | Notebook    | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [d822a4112f](https://linux-hardware.org/?probe=d822a4112f) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [fd29c0dc4e](https://linux-hardware.org/?probe=fd29c0dc4e) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Proline       | V146SH                      | Notebook    | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [d3b7f2f978](https://linux-hardware.org/?probe=d3b7f2f978) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| ASUSTek       | G752VL                      | Notebook    | [4a4ea6f987](https://linux-hardware.org/?probe=4a4ea6f987) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [01025c7c43](https://linux-hardware.org/?probe=01025c7c43) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f9cf8b06f6](https://linux-hardware.org/?probe=f9cf8b06f6) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | Notebook    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [80ecfacebf](https://linux-hardware.org/?probe=80ecfacebf) | Mar 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [56b4f8a1a9](https://linux-hardware.org/?probe=56b4f8a1a9) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d35772b8bc](https://linux-hardware.org/?probe=d35772b8bc) | Mar 09, 2023 |
| HP            | Notebook                    | Notebook    | [b5ee32f085](https://linux-hardware.org/?probe=b5ee32f085) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [2dbb99bbb2](https://linux-hardware.org/?probe=2dbb99bbb2) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [2664be8926](https://linux-hardware.org/?probe=2664be8926) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [dc915e443d](https://linux-hardware.org/?probe=dc915e443d) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [7d6aa1edeb](https://linux-hardware.org/?probe=7d6aa1edeb) | Mar 08, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [5ffa875792](https://linux-hardware.org/?probe=5ffa875792) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [89adccae04](https://linux-hardware.org/?probe=89adccae04) | Mar 08, 2023 |
| Lenovo        | ThinkPad T450s 20BX0013G... | Notebook    | [11cf435bfe](https://linux-hardware.org/?probe=11cf435bfe) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | Notebook    | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| Dell          | Latitude 5400               | Notebook    | [3d2504745e](https://linux-hardware.org/?probe=3d2504745e) | Mar 08, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [7f4678dcf1](https://linux-hardware.org/?probe=7f4678dcf1) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [5a706c6543](https://linux-hardware.org/?probe=5a706c6543) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| Dell          | Latitude 7290               | Notebook    | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1aaf3d1b9f](https://linux-hardware.org/?probe=1aaf3d1b9f) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | Desktop     | [0dd36bc615](https://linux-hardware.org/?probe=0dd36bc615) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| Acer          | One S1001                   | Notebook    | [b43d7f0a84](https://linux-hardware.org/?probe=b43d7f0a84) | Mar 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [f5a1ceaa74](https://linux-hardware.org/?probe=f5a1ceaa74) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [c36bf90efb](https://linux-hardware.org/?probe=c36bf90efb) | Mar 06, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [72af4386e5](https://linux-hardware.org/?probe=72af4386e5) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [98a2c9f264](https://linux-hardware.org/?probe=98a2c9f264) | Mar 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4b6c93e678](https://linux-hardware.org/?probe=4b6c93e678) | Mar 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [0fca5ee94e](https://linux-hardware.org/?probe=0fca5ee94e) | Mar 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d256faa9fc](https://linux-hardware.org/?probe=d256faa9fc) | Mar 06, 2023 |
| Dell          | 0RY007                      | Desktop     | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | Desktop     | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [5d94a30450](https://linux-hardware.org/?probe=5d94a30450) | Mar 05, 2023 |
| MSI           | B550M PRO                   | Desktop     | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [f33f04396c](https://linux-hardware.org/?probe=f33f04396c) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [ebd1e9103e](https://linux-hardware.org/?probe=ebd1e9103e) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [8078d7ca28](https://linux-hardware.org/?probe=8078d7ca28) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Google        | Lillipup                    | Notebook    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [d42a19d17b](https://linux-hardware.org/?probe=d42a19d17b) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eeb75c7723](https://linux-hardware.org/?probe=eeb75c7723) | Mar 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [08f74aef46](https://linux-hardware.org/?probe=08f74aef46) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [fb996384c6](https://linux-hardware.org/?probe=fb996384c6) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e2ad6f0e57](https://linux-hardware.org/?probe=e2ad6f0e57) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a28f5eeec0](https://linux-hardware.org/?probe=a28f5eeec0) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [bd0163923e](https://linux-hardware.org/?probe=bd0163923e) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | Notebook    | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6f7115f084](https://linux-hardware.org/?probe=6f7115f084) | Mar 04, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [d24552db45](https://linux-hardware.org/?probe=d24552db45) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| Purism        | Librem 14                   | Notebook    | [fbae41cbd5](https://linux-hardware.org/?probe=fbae41cbd5) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bd5e51c339](https://linux-hardware.org/?probe=bd5e51c339) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1ee7b087a8](https://linux-hardware.org/?probe=1ee7b087a8) | Mar 03, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [196e49402d](https://linux-hardware.org/?probe=196e49402d) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4b20311834](https://linux-hardware.org/?probe=4b20311834) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [dd60a9c73b](https://linux-hardware.org/?probe=dd60a9c73b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5906e1b848](https://linux-hardware.org/?probe=5906e1b848) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [886538fe37](https://linux-hardware.org/?probe=886538fe37) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e5b411431c](https://linux-hardware.org/?probe=e5b411431c) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6b7925d129](https://linux-hardware.org/?probe=6b7925d129) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | Desktop     | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| HP            | 255 G3                      | Notebook    | [78c4cd0a9c](https://linux-hardware.org/?probe=78c4cd0a9c) | Mar 01, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [43deb753b9](https://linux-hardware.org/?probe=43deb753b9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | Desktop     | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [915d5fcb1d](https://linux-hardware.org/?probe=915d5fcb1d) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [94809b7bc2](https://linux-hardware.org/?probe=94809b7bc2) | Mar 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [4d1bdc90ea](https://linux-hardware.org/?probe=4d1bdc90ea) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [d0ce638961](https://linux-hardware.org/?probe=d0ce638961) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [165c0356a5](https://linux-hardware.org/?probe=165c0356a5) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [40516fd80e](https://linux-hardware.org/?probe=40516fd80e) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude E7270              | Notebook    | [2718026d03](https://linux-hardware.org/?probe=2718026d03) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [93ee76f198](https://linux-hardware.org/?probe=93ee76f198) | Feb 28, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a897f5d7c](https://linux-hardware.org/?probe=9a897f5d7c) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3d003c6d17](https://linux-hardware.org/?probe=3d003c6d17) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| Standard      | Unknown                     | Notebook    | [63732ac2da](https://linux-hardware.org/?probe=63732ac2da) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| Dell          | Precision 5570              | Notebook    | [7e8d7c37cb](https://linux-hardware.org/?probe=7e8d7c37cb) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [b1ef7c7ea1](https://linux-hardware.org/?probe=b1ef7c7ea1) | Feb 27, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [43602775cd](https://linux-hardware.org/?probe=43602775cd) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1c1dc86eb1](https://linux-hardware.org/?probe=1c1dc86eb1) | Feb 27, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [91405b88cc](https://linux-hardware.org/?probe=91405b88cc) | Feb 27, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [11aeca0c24](https://linux-hardware.org/?probe=11aeca0c24) | Feb 27, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c96506f38](https://linux-hardware.org/?probe=4c96506f38) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7e55bb97e](https://linux-hardware.org/?probe=d7e55bb97e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [058ecdce01](https://linux-hardware.org/?probe=058ecdce01) | Feb 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [7f7bdeae7c](https://linux-hardware.org/?probe=7f7bdeae7c) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| Lenovo        | ThinkPad X395 20NL0006US    | Notebook    | [9030fac261](https://linux-hardware.org/?probe=9030fac261) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fe8735a027](https://linux-hardware.org/?probe=fe8735a027) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [da6968c8ac](https://linux-hardware.org/?probe=da6968c8ac) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | Desktop     | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | Notebook    | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Timi          | TM1612                      | Notebook    | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [f589c3687b](https://linux-hardware.org/?probe=f589c3687b) | Feb 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d610badec8](https://linux-hardware.org/?probe=d610badec8) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [e981803528](https://linux-hardware.org/?probe=e981803528) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [8db23a7237](https://linux-hardware.org/?probe=8db23a7237) | Feb 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d6805fb81b](https://linux-hardware.org/?probe=d6805fb81b) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| Gigabyte      | H310M D3H                   | Desktop     | [058fac57c2](https://linux-hardware.org/?probe=058fac57c2) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | Notebook    | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7ae4fe9340](https://linux-hardware.org/?probe=7ae4fe9340) | Feb 25, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [4402838fb3](https://linux-hardware.org/?probe=4402838fb3) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [87df24d8c2](https://linux-hardware.org/?probe=87df24d8c2) | Feb 25, 2023 |
| Google        | Voxel                       | Notebook    | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [be0b15660e](https://linux-hardware.org/?probe=be0b15660e) | Feb 25, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [52924074db](https://linux-hardware.org/?probe=52924074db) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | Desktop     | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Dell          | Precision 5520              | Notebook    | [c41014658b](https://linux-hardware.org/?probe=c41014658b) | Feb 25, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [af9891267d](https://linux-hardware.org/?probe=af9891267d) | Feb 24, 2023 |
| HP            | 84EF 01100                  | All in one  | [d69b1aab65](https://linux-hardware.org/?probe=d69b1aab65) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [787270bc9e](https://linux-hardware.org/?probe=787270bc9e) | Feb 24, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [ade006d016](https://linux-hardware.org/?probe=ade006d016) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [362c88435e](https://linux-hardware.org/?probe=362c88435e) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f7063f868f](https://linux-hardware.org/?probe=f7063f868f) | Feb 24, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [7686bcd76d](https://linux-hardware.org/?probe=7686bcd76d) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [1fb6ff6899](https://linux-hardware.org/?probe=1fb6ff6899) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [1f43871064](https://linux-hardware.org/?probe=1f43871064) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [c570bb75bf](https://linux-hardware.org/?probe=c570bb75bf) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | Notebook    | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0f251d6bbf](https://linux-hardware.org/?probe=0f251d6bbf) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [d8475e4c48](https://linux-hardware.org/?probe=d8475e4c48) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [becb5b0ba1](https://linux-hardware.org/?probe=becb5b0ba1) | Feb 22, 2023 |
| CyberPower... | Tracer IV GM5MQ8W           | Notebook    | [284e8a4fb1](https://linux-hardware.org/?probe=284e8a4fb1) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| Dell          | Latitude E5570              | Notebook    | [338538c1c9](https://linux-hardware.org/?probe=338538c1c9) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [0b32a33625](https://linux-hardware.org/?probe=0b32a33625) | Feb 22, 2023 |
| Alienware     | x14                         | Notebook    | [04094754b6](https://linux-hardware.org/?probe=04094754b6) | Feb 22, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3e5166108a](https://linux-hardware.org/?probe=3e5166108a) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | Desktop     | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Samsung       | 767XCL                      | Notebook    | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| Dell          | Latitude 5491               | Notebook    | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [7ead9488ae](https://linux-hardware.org/?probe=7ead9488ae) | Feb 21, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [b9117f0c6f](https://linux-hardware.org/?probe=b9117f0c6f) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c0733771d5](https://linux-hardware.org/?probe=c0733771d5) | Feb 21, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [039bb422e0](https://linux-hardware.org/?probe=039bb422e0) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9989903f85](https://linux-hardware.org/?probe=9989903f85) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2b329d108f](https://linux-hardware.org/?probe=2b329d108f) | Feb 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [53737369e8](https://linux-hardware.org/?probe=53737369e8) | Feb 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [b8c4b41baf](https://linux-hardware.org/?probe=b8c4b41baf) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a813f73ea2](https://linux-hardware.org/?probe=a813f73ea2) | Feb 20, 2023 |
| MSI           | Bravo 15 B5ED               | Notebook    | [a0b7f1b5f8](https://linux-hardware.org/?probe=a0b7f1b5f8) | Feb 20, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [c3f49d4cee](https://linux-hardware.org/?probe=c3f49d4cee) | Feb 20, 2023 |
| Lenovo        | ThinkPad T530 239265U       | Notebook    | [9f60ca6bf5](https://linux-hardware.org/?probe=9f60ca6bf5) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [6f456ca669](https://linux-hardware.org/?probe=6f456ca669) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [057dcdc86b](https://linux-hardware.org/?probe=057dcdc86b) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [89eb85b36f](https://linux-hardware.org/?probe=89eb85b36f) | Feb 19, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [f347582e5c](https://linux-hardware.org/?probe=f347582e5c) | Feb 19, 2023 |
| Samsung       | 930QED                      | Convertible | [f72fed80df](https://linux-hardware.org/?probe=f72fed80df) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [b1d168b6ce](https://linux-hardware.org/?probe=b1d168b6ce) | Feb 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | Notebook    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f9314a0aa9](https://linux-hardware.org/?probe=f9314a0aa9) | Feb 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [ee24b75c39](https://linux-hardware.org/?probe=ee24b75c39) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| Google        | Kled                        | Notebook    | [788d726509](https://linux-hardware.org/?probe=788d726509) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [b835147a32](https://linux-hardware.org/?probe=b835147a32) | Feb 18, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [fb2cbe3576](https://linux-hardware.org/?probe=fb2cbe3576) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [e7988c5ab6](https://linux-hardware.org/?probe=e7988c5ab6) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [6d2b283e83](https://linux-hardware.org/?probe=6d2b283e83) | Feb 18, 2023 |
| Dell          | Precision 5560              | Notebook    | [24e5de4a3d](https://linux-hardware.org/?probe=24e5de4a3d) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| Samsung       | 730QDA                      | Convertible | [902b86cb84](https://linux-hardware.org/?probe=902b86cb84) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | Notebook    | [53ef9ffad8](https://linux-hardware.org/?probe=53ef9ffad8) | Feb 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| Hardkernel    | ODROID-N2                   | Soc         | [9a8138252f](https://linux-hardware.org/?probe=9a8138252f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [c1abb80cb1](https://linux-hardware.org/?probe=c1abb80cb1) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [8ade075157](https://linux-hardware.org/?probe=8ade075157) | Feb 16, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4657fc266d](https://linux-hardware.org/?probe=4657fc266d) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [218e0f7ad6](https://linux-hardware.org/?probe=218e0f7ad6) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| Samsung       | 940XFG                      | Notebook    | [56f236f8ab](https://linux-hardware.org/?probe=56f236f8ab) | Feb 16, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [66dbe64897](https://linux-hardware.org/?probe=66dbe64897) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [5a3b0950b3](https://linux-hardware.org/?probe=5a3b0950b3) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [159244d1a4](https://linux-hardware.org/?probe=159244d1a4) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [d112d85387](https://linux-hardware.org/?probe=d112d85387) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3916d619ed](https://linux-hardware.org/?probe=3916d619ed) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [90114a4fe4](https://linux-hardware.org/?probe=90114a4fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bc4811db07](https://linux-hardware.org/?probe=bc4811db07) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude E7270              | Notebook    | [03199b7612](https://linux-hardware.org/?probe=03199b7612) | Feb 14, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | Notebook    | [008d06fbf8](https://linux-hardware.org/?probe=008d06fbf8) | Feb 14, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [561e1a6160](https://linux-hardware.org/?probe=561e1a6160) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | Latitude 7430               | Notebook    | [82dcb0a8a2](https://linux-hardware.org/?probe=82dcb0a8a2) | Feb 14, 2023 |
| Dell          | G3 3579                     | Notebook    | [35c8b69b8c](https://linux-hardware.org/?probe=35c8b69b8c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a3b0220b10](https://linux-hardware.org/?probe=a3b0220b10) | Feb 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2f78b0c253](https://linux-hardware.org/?probe=2f78b0c253) | Feb 14, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0033422c4d](https://linux-hardware.org/?probe=0033422c4d) | Feb 14, 2023 |
| HP            | 8714                        | Desktop     | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [ac71e5b8ef](https://linux-hardware.org/?probe=ac71e5b8ef) | Feb 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [1f0e965483](https://linux-hardware.org/?probe=1f0e965483) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f701208fd4](https://linux-hardware.org/?probe=f701208fd4) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [3b7765dfcc](https://linux-hardware.org/?probe=3b7765dfcc) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6add161dbe](https://linux-hardware.org/?probe=6add161dbe) | Feb 13, 2023 |
| Dell          | Latitude 5511               | Notebook    | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [7e90fe56d1](https://linux-hardware.org/?probe=7e90fe56d1) | Feb 13, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [abd464b0d3](https://linux-hardware.org/?probe=abd464b0d3) | Feb 13, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [7fdcffc633](https://linux-hardware.org/?probe=7fdcffc633) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0560a363b8](https://linux-hardware.org/?probe=0560a363b8) | Feb 12, 2023 |
| Dell          | Venue 10 Pro 5055           | Notebook    | [7afcfff799](https://linux-hardware.org/?probe=7afcfff799) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [cde8e637d2](https://linux-hardware.org/?probe=cde8e637d2) | Feb 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [a3ac4db738](https://linux-hardware.org/?probe=a3ac4db738) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [cdd913ae48](https://linux-hardware.org/?probe=cdd913ae48) | Feb 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3c8717baf4](https://linux-hardware.org/?probe=3c8717baf4) | Feb 12, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [8f74caf33e](https://linux-hardware.org/?probe=8f74caf33e) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b569293b7b](https://linux-hardware.org/?probe=b569293b7b) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1e3ceef5e6](https://linux-hardware.org/?probe=1e3ceef5e6) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [729f2b5250](https://linux-hardware.org/?probe=729f2b5250) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [155c8fa16e](https://linux-hardware.org/?probe=155c8fa16e) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [365b6606cd](https://linux-hardware.org/?probe=365b6606cd) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [321710ca2d](https://linux-hardware.org/?probe=321710ca2d) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [de54b14304](https://linux-hardware.org/?probe=de54b14304) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [2beb0c0b30](https://linux-hardware.org/?probe=2beb0c0b30) | Feb 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | Desktop     | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d8a854baec](https://linux-hardware.org/?probe=d8a854baec) | Feb 11, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c684709755](https://linux-hardware.org/?probe=c684709755) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | Notebook    | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6c1d31a394](https://linux-hardware.org/?probe=6c1d31a394) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [d77cac7fb6](https://linux-hardware.org/?probe=d77cac7fb6) | Feb 10, 2023 |
| HP            | 8714                        | Desktop     | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| Lenovo        | ThinkPad T590 20N5S4R800    | Notebook    | [6a55f84594](https://linux-hardware.org/?probe=6a55f84594) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| HP            | 83E4                        | All in one  | [cdefba9e55](https://linux-hardware.org/?probe=cdefba9e55) | Feb 09, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [0b05e41c64](https://linux-hardware.org/?probe=0b05e41c64) | Feb 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8d2e488f38](https://linux-hardware.org/?probe=8d2e488f38) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1adfd2bb79](https://linux-hardware.org/?probe=1adfd2bb79) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| HP            | 2000                        | Notebook    | [f76b7389d7](https://linux-hardware.org/?probe=f76b7389d7) | Feb 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [78d55087bb](https://linux-hardware.org/?probe=78d55087bb) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3482c24991](https://linux-hardware.org/?probe=3482c24991) | Feb 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc2ea675c8](https://linux-hardware.org/?probe=bc2ea675c8) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [0b2a31bed4](https://linux-hardware.org/?probe=0b2a31bed4) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [9bf97a14cf](https://linux-hardware.org/?probe=9bf97a14cf) | Feb 08, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [b440353d20](https://linux-hardware.org/?probe=b440353d20) | Feb 08, 2023 |
| Google        | Delbin                      | Notebook    | [268fbe9849](https://linux-hardware.org/?probe=268fbe9849) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [147b5315c5](https://linux-hardware.org/?probe=147b5315c5) | Feb 08, 2023 |
| Google        | Delbin                      | Notebook    | [1afd4fec8d](https://linux-hardware.org/?probe=1afd4fec8d) | Feb 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [5e5ec021d0](https://linux-hardware.org/?probe=5e5ec021d0) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0376f0c65f](https://linux-hardware.org/?probe=0376f0c65f) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [325806b7cc](https://linux-hardware.org/?probe=325806b7cc) | Feb 07, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [870a2912c9](https://linux-hardware.org/?probe=870a2912c9) | Feb 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Fedora 36 | 2091      | 18.08%  |
| Fedora 37 | 1756      | 15.18%  |
| Fedora 35 | 1647      | 14.24%  |
| Fedora 34 | 1593      | 13.77%  |
| Fedora 33 | 1566      | 13.54%  |
| Fedora 32 | 1371      | 11.85%  |
| Fedora 31 | 910       | 7.87%   |
| Fedora 30 | 313       | 2.71%   |
| Fedora 29 | 172       | 1.49%   |
| Fedora 38 | 58        | 0.5%    |
| Fedora 28 | 43        | 0.37%   |
| Fedora 27 | 19        | 0.16%   |
| Fedora 39 | 7         | 0.06%   |
| Fedora 24 | 6         | 0.05%   |
| Fedora 21 | 6         | 0.05%   |
| Fedora 25 | 4         | 0.03%   |
| Fedora 4  | 1         | 0.01%   |
| Fedora 17 | 1         | 0.01%   |
| Fedora 14 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Fedora | 10228     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64  | 179       | 1.37%   |
| 5.16.18-200.fc35.x86_64 | 162       | 1.24%   |
| 5.9.16-200.fc33.x86_64  | 159       | 1.22%   |
| 6.0.15-300.fc37.x86_64  | 131       | 1%      |
| 5.14.10-300.fc35.x86_64 | 129       | 0.99%   |
| 6.0.7-301.fc37.x86_64   | 123       | 0.94%   |
| 5.11.12-300.fc34.x86_64 | 123       | 0.94%   |
| 6.0.5-200.fc36.x86_64   | 116       | 0.89%   |
| 5.18.13-200.fc36.x86_64 | 112       | 0.86%   |
| 6.0.12-300.fc37.x86_64  | 107       | 0.82%   |
| 5.8.4-200.fc32.x86_64   | 101       | 0.77%   |
| 5.8.15-301.fc33.x86_64  | 100       | 0.77%   |
| 5.8.16-300.fc33.x86_64  | 97        | 0.74%   |
| 6.1.14-200.fc37.x86_64  | 96        | 0.73%   |
| 5.19.16-200.fc36.x86_64 | 96        | 0.73%   |
| 5.13.12-200.fc34.x86_64 | 96        | 0.73%   |
| 5.18.11-200.fc36.x86_64 | 90        | 0.69%   |
| 6.1.18-200.fc37.x86_64  | 88        | 0.67%   |
| 5.19.9-200.fc36.x86_64  | 87        | 0.67%   |
| 6.0.9-300.fc37.x86_64   | 85        | 0.65%   |
| 6.0.8-300.fc37.x86_64   | 85        | 0.65%   |
| 5.18.16-200.fc36.x86_64 | 85        | 0.65%   |
| 5.8.18-300.fc33.x86_64  | 81        | 0.62%   |
| 6.1.7-200.fc37.x86_64   | 79        | 0.6%    |
| 5.15.6-200.fc35.x86_64  | 78        | 0.6%    |
| 5.12.13-300.fc34.x86_64 | 78        | 0.6%    |
| 5.9.8-200.fc33.x86_64   | 77        | 0.59%   |
| 5.18.5-200.fc36.x86_64  | 75        | 0.57%   |
| 5.16.16-200.fc35.x86_64 | 75        | 0.57%   |
| 5.17.6-300.fc36.x86_64  | 74        | 0.57%   |
| 5.11.11-200.fc33.x86_64 | 73        | 0.56%   |
| 5.17.11-300.fc36.x86_64 | 72        | 0.55%   |
| 5.9.11-200.fc33.x86_64  | 71        | 0.54%   |
| 5.17.4-200.fc35.x86_64  | 71        | 0.54%   |
| 6.0.11-300.fc37.x86_64  | 70        | 0.54%   |
| 6.1.8-200.fc37.x86_64   | 69        | 0.53%   |
| 5.3.16-300.fc31.x86_64  | 68        | 0.52%   |
| 5.14.16-301.fc35.x86_64 | 68        | 0.52%   |
| 6.1.11-200.fc37.x86_64  | 67        | 0.51%   |
| 5.19.8-200.fc36.x86_64  | 67        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 233       | 1.79%   |
| 5.9.16  | 176       | 1.35%   |
| 5.16.18 | 174       | 1.33%   |
| 6.0.7   | 151       | 1.16%   |
| 5.8.15  | 151       | 1.16%   |
| 6.0.15  | 148       | 1.13%   |
| 5.19.16 | 146       | 1.12%   |
| 5.14.10 | 140       | 1.07%   |
| 5.11.12 | 133       | 1.02%   |
| 5.8.16  | 131       | 1%      |
| 6.0.5   | 127       | 0.97%   |
| 6.0.12  | 125       | 0.96%   |
| 5.8.18  | 121       | 0.93%   |
| 5.11.11 | 119       | 0.91%   |
| 5.18.13 | 117       | 0.9%    |
| 6.0.9   | 111       | 0.85%   |
| 6.0.8   | 110       | 0.84%   |
| 6.1.14  | 103       | 0.79%   |
| 5.19.9  | 103       | 0.79%   |
| 5.13.12 | 102       | 0.78%   |
| 5.8.4   | 101       | 0.77%   |
| 5.14.18 | 96        | 0.74%   |
| 5.18.11 | 94        | 0.72%   |
| 6.1.18  | 91        | 0.7%    |
| 5.18.16 | 90        | 0.69%   |
| 5.15.6  | 88        | 0.67%   |
| 5.9.8   | 86        | 0.66%   |
| 5.19.8  | 86        | 0.66%   |
| 5.17.6  | 86        | 0.66%   |
| 6.1.7   | 85        | 0.65%   |
| 5.18.5  | 85        | 0.65%   |
| 5.17.11 | 85        | 0.65%   |
| 5.17.4  | 83        | 0.64%   |
| 5.12.13 | 83        | 0.64%   |
| 6.0.10  | 82        | 0.63%   |
| 5.6.6   | 82        | 0.63%   |
| 5.14.16 | 81        | 0.62%   |
| 5.9.11  | 78        | 0.6%    |
| 5.16.16 | 78        | 0.6%    |
| 6.0.11  | 77        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 1076      | 8.66%   |
| 5.8     | 843       | 6.78%   |
| 5.17    | 838       | 6.74%   |
| 5.11    | 791       | 6.36%   |
| 5.19    | 782       | 6.29%   |
| 6.1     | 777       | 6.25%   |
| 5.18    | 735       | 5.91%   |
| 5.16    | 663       | 5.33%   |
| 5.14    | 657       | 5.29%   |
| 5.9     | 563       | 4.53%   |
| 5.10    | 548       | 4.41%   |
| 5.13    | 543       | 4.37%   |
| 5.15    | 530       | 4.26%   |
| 5.6     | 522       | 4.2%    |
| 5.12    | 506       | 4.07%   |
| 5.7     | 423       | 3.4%    |
| 5.3     | 331       | 2.66%   |
| 5.4     | 323       | 2.6%    |
| 5.5     | 319       | 2.57%   |
| 6.2     | 159       | 1.28%   |
| 5.0     | 119       | 0.96%   |
| 5.2     | 110       | 0.89%   |
| 5.1     | 75        | 0.6%    |
| 4.19    | 56        | 0.45%   |
| 4.18    | 49        | 0.39%   |
| 4.20    | 39        | 0.31%   |
| 4.16    | 9         | 0.07%   |
| 4.15    | 6         | 0.05%   |
| 6.3     | 5         | 0.04%   |
| 4.17    | 5         | 0.04%   |
| 4.14    | 5         | 0.04%   |
| 4.11    | 5         | 0.04%   |
| 4.1     | 4         | 0.03%   |
| 3.17    | 3         | 0.02%   |
| 4.8     | 2         | 0.02%   |
| 4.13    | 2         | 0.02%   |
| Unknown | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10189     | 99.6%   |
| aarch64 | 25        | 0.24%   |
| i686    | 9         | 0.09%   |
| armv7l  | 5         | 0.05%   |
| Unknown | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 7487      | 71.12%  |
| KDE5                         | 1201      | 11.41%  |
| Unknown                      | 640       | 6.08%   |
| KDE                          | 270       | 2.56%   |
| XFCE                         | 230       | 2.18%   |
| X-Cinnamon                   | 160       | 1.52%   |
| MATE                         | 147       | 1.4%    |
| Cinnamon                     | 139       | 1.32%   |
| GNOME Classic                | 49        | 0.47%   |
| i3                           | 42        | 0.4%    |
| LXQt                         | 34        | 0.32%   |
| LXDE                         | 27        | 0.26%   |
| Deepin                       | 25        | 0.24%   |
| sway                         | 18        | 0.17%   |
| KDE4                         | 10        | 0.09%   |
| awesome                      | 7         | 0.07%   |
| Pantheon                     | 5         | 0.05%   |
| openbox                      | 5         | 0.05%   |
| DWM                          | 5         | 0.05%   |
| GNOME Flashback              | 4         | 0.04%   |
| Budgie                       | 4         | 0.04%   |
| bspwm                        | 4         | 0.04%   |
| qtile                        | 3         | 0.03%   |
| fluxbox                      | 3         | 0.03%   |
| xinit-compat                 | 2         | 0.02%   |
| xmonad                       | 1         | 0.01%   |
| Phosh:GNOME                  | 1         | 0.01%   |
| NsCDE                        | 1         | 0.01%   |
| KDE:old                      | 1         | 0.01%   |
| GNUstep                      | 1         | 0.01%   |
| GNOME-Classic                | 1         | 0.01%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 6385      | 59.86%  |
| X11     | 3693      | 34.62%  |
| Unknown | 371       | 3.48%   |
| Tty     | 212       | 1.99%   |
| Web     | 6         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5454      | 51.83%  |
| GDM     | 3671      | 34.89%  |
| SDDM    | 764       | 7.26%   |
| LightDM | 420       | 3.99%   |
| TDM     | 169       | 1.61%   |
| XDM     | 18        | 0.17%   |
| KDM     | 15        | 0.14%   |
| LXDM    | 8         | 0.08%   |
| SLiM    | 2         | 0.02%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 5194      | 49.77%  |
| en_GB   | 718       | 6.88%   |
| Unknown | 666       | 6.38%   |
| pt_BR   | 465       | 4.46%   |
| ru_RU   | 455       | 4.36%   |
| de_DE   | 415       | 3.98%   |
| fr_FR   | 313       | 3%      |
| it_IT   | 257       | 2.46%   |
| en_CA   | 217       | 2.08%   |
| en_AU   | 193       | 1.85%   |
| pl_PL   | 160       | 1.53%   |
| es_ES   | 153       | 1.47%   |
| en_IN   | 105       | 1.01%   |
| es_MX   | 77        | 0.74%   |
| cs_CZ   | 71        | 0.68%   |
| en_NZ   | 48        | 0.46%   |
| es_AR   | 47        | 0.45%   |
| nl_NL   | 43        | 0.41%   |
| es_CL   | 43        | 0.41%   |
| tr_TR   | 41        | 0.39%   |
| zh_CN   | 39        | 0.37%   |
| C       | 38        | 0.36%   |
| sv_SE   | 36        | 0.34%   |
| hu_HU   | 32        | 0.31%   |
| es_CO   | 32        | 0.31%   |
| de_AT   | 32        | 0.31%   |
| en_IE   | 31        | 0.3%    |
| en_DK   | 27        | 0.26%   |
| pt_PT   | 26        | 0.25%   |
| fi_FI   | 26        | 0.25%   |
| fr_CA   | 21        | 0.2%    |
| ru_UA   | 20        | 0.19%   |
| uk_UA   | 18        | 0.17%   |
| nl_BE   | 18        | 0.17%   |
| ja_JP   | 18        | 0.17%   |
| en_ZA   | 18        | 0.17%   |
| de_CH   | 18        | 0.17%   |
| sk_SK   | 16        | 0.15%   |
| fr_BE   | 16        | 0.15%   |
| nb_NO   | 15        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 7788      | 75.06%  |
| BIOS | 2588      | 24.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Btrfs               | 5900      | 56.22%  |
| Ext4                | 3837      | 36.56%  |
| Xfs                 | 366       | 3.49%   |
| Unknown             | 350       | 3.34%   |
| Overlay             | 18        | 0.17%   |
| Ext3                | 7         | 0.07%   |
| Zfs                 | 6         | 0.06%   |
| F2fs                | 6         | 0.06%   |
| Fuse.fuse-overlayfs | 4         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5360      | 51.08%  |
| GPT     | 4354      | 41.49%  |
| MBR     | 779       | 7.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9216      | 88.58%  |
| Yes       | 1188      | 11.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8349      | 80.42%  |
| Yes       | 2033      | 19.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 2096      | 20.49%  |
| ASUSTek Computer        | 1649      | 16.12%  |
| Dell                    | 1396      | 13.65%  |
| Hewlett-Packard         | 1236      | 12.08%  |
| Gigabyte Technology     | 681       | 6.66%   |
| MSI                     | 645       | 6.31%   |
| Acer                    | 459       | 4.49%   |
| ASRock                  | 354       | 3.46%   |
| Apple                   | 225       | 2.2%    |
| Intel                   | 128       | 1.25%   |
| HUAWEI                  | 119       | 1.16%   |
| Samsung Electronics     | 92        | 0.9%    |
| Toshiba                 | 85        | 0.83%   |
| Unknown                 | 74        | 0.72%   |
| Microsoft               | 57        | 0.56%   |
| Sony                    | 48        | 0.47%   |
| Notebook                | 47        | 0.46%   |
| Timi                    | 39        | 0.38%   |
| Fujitsu                 | 39        | 0.38%   |
| Alienware               | 32        | 0.31%   |
| Positivo                | 31        | 0.3%    |
| Framework               | 30        | 0.29%   |
| Supermicro              | 29        | 0.28%   |
| Google                  | 28        | 0.27%   |
| System76                | 22        | 0.22%   |
| Pegatron                | 22        | 0.22%   |
| BESSTAR Tech            | 20        | 0.2%    |
| LG Electronics          | 19        | 0.19%   |
| TUXEDO                  | 18        | 0.18%   |
| Chuwi                   | 17        | 0.17%   |
| Biostar                 | 17        | 0.17%   |
| Razer                   | 15        | 0.15%   |
| ECS                     | 15        | 0.15%   |
| Raspberry Pi Foundation | 14        | 0.14%   |
| Medion                  | 14        | 0.14%   |
| Huanan                  | 13        | 0.13%   |
| AZW                     | 13        | 0.13%   |
| Packard Bell            | 11        | 0.11%   |
| Foxconn                 | 11        | 0.11%   |
| AMI                     | 11        | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 104       | 1.02%   |
| Unknown                                    | 97        | 0.95%   |
| MSI MS-7C37                                | 37        | 0.36%   |
| HP Notebook                                | 30        | 0.29%   |
| ASUS TUF Gaming X570-PLUS                  | 27        | 0.26%   |
| Dell XPS 15 9570                           | 25        | 0.24%   |
| Gigabyte B450M DS3H                        | 23        | 0.22%   |
| Framework Laptop                           | 23        | 0.22%   |
| Dell XPS 15 7590                           | 22        | 0.22%   |
| MSI MS-7C02                                | 21        | 0.21%   |
| MSI MS-7A38                                | 21        | 0.21%   |
| Dell XPS 13 9370                           | 21        | 0.21%   |
| Dell Latitude 7490                         | 21        | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2          | 20        | 0.2%    |
| Dell XPS 15 9560                           | 19        | 0.19%   |
| Dell XPS 13 9360                           | 19        | 0.19%   |
| Dell OptiPlex 7010                         | 19        | 0.19%   |
| MSI MS-7B86                                | 18        | 0.18%   |
| HP EliteBook 840 G6                        | 18        | 0.18%   |
| Dell XPS 13 9310                           | 18        | 0.18%   |
| Dell XPS 13 7390                           | 18        | 0.18%   |
| HP Pavilion dv6                            | 17        | 0.17%   |
| MSI MS-7C56                                | 16        | 0.16%   |
| Dell XPS 15 9550                           | 16        | 0.16%   |
| ASUS ROG STRIX B550-F GAMING               | 16        | 0.16%   |
| MSI MS-7C91                                | 15        | 0.15%   |
| HP Pavilion 15                             | 15        | 0.15%   |
| Dell XPS 15 9500                           | 15        | 0.15%   |
| Dell Latitude E7450                        | 15        | 0.15%   |
| ASUS PRIME X370-PRO                        | 15        | 0.15%   |
| MSI MS-7B79                                | 14        | 0.14%   |
| HP Laptop 15-da0xxx                        | 14        | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx         | 14        | 0.14%   |
| Dell XPS 13 9300                           | 14        | 0.14%   |
| Dell OptiPlex 9020                         | 14        | 0.14%   |
| ASUS ROG STRIX B450-F GAMING               | 14        | 0.14%   |
| MSI MS-7C84                                | 13        | 0.13%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.13%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 13        | 0.13%   |
| HP Pavilion Notebook                       | 13        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1152      | 11.26%  |
| Dell Inspiron      | 366       | 3.58%   |
| Lenovo IdeaPad     | 357       | 3.49%   |
| Dell Latitude      | 338       | 3.3%    |
| ASUS ROG           | 304       | 2.97%   |
| Dell XPS           | 291       | 2.85%   |
| Acer Aspire        | 284       | 2.78%   |
| HP Pavilion        | 222       | 2.17%   |
| ASUS PRIME         | 200       | 1.96%   |
| HP EliteBook       | 189       | 1.85%   |
| HP ProBook         | 142       | 1.39%   |
| ASUS TUF           | 140       | 1.37%   |
| Dell Precision     | 131       | 1.28%   |
| Lenovo Yoga        | 128       | 1.25%   |
| Dell OptiPlex      | 125       | 1.22%   |
| HP Laptop          | 123       | 1.2%    |
| ASUS VivoBook      | 119       | 1.16%   |
| HP ENVY            | 106       | 1.04%   |
| ASUS All           | 104       | 1.02%   |
| Unknown            | 97        | 0.95%   |
| Toshiba Satellite  | 73        | 0.71%   |
| Lenovo Legion      | 72        | 0.7%    |
| Lenovo ThinkCentre | 71        | 0.69%   |
| Lenovo ThinkBook   | 67        | 0.66%   |
| Gigabyte X570      | 62        | 0.61%   |
| Dell Vostro        | 59        | 0.58%   |
| ASUS ZenBook       | 58        | 0.57%   |
| Microsoft Surface  | 57        | 0.56%   |
| ASUS ASUS          | 53        | 0.52%   |
| Acer Nitro         | 52        | 0.51%   |
| HP ZBook           | 49        | 0.48%   |
| HP Compaq          | 49        | 0.48%   |
| Lenovo IdeaPadFlex | 42        | 0.41%   |
| Gigabyte B450      | 42        | 0.41%   |
| Acer Swift         | 41        | 0.4%    |
| MSI MS-7C37        | 37        | 0.36%   |
| Gigabyte B450M     | 37        | 0.36%   |
| HP Spectre         | 35        | 0.34%   |
| HP EliteDesk       | 34        | 0.33%   |
| Apple MacBookPro11 | 31        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1348      | 13.18%  |
| 2020    | 1339      | 13.09%  |
| 2018    | 1223      | 11.96%  |
| 2021    | 967       | 9.45%   |
| 2017    | 866       | 8.47%   |
| 2012    | 624       | 6.1%    |
| 2015    | 594       | 5.81%   |
| 2013    | 579       | 5.66%   |
| 2016    | 570       | 5.57%   |
| 2014    | 537       | 5.25%   |
| 2011    | 456       | 4.46%   |
| 2022    | 396       | 3.87%   |
| 2010    | 259       | 2.53%   |
| 2009    | 184       | 1.8%    |
| 2008    | 171       | 1.67%   |
| 2007    | 60        | 0.59%   |
| 2006    | 25        | 0.24%   |
| Unknown | 15        | 0.15%   |
| 2023    | 10        | 0.1%    |
| 2005    | 4         | 0.04%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5911      | 57.79%  |
| Desktop        | 3399      | 33.23%  |
| Convertible    | 455       | 4.45%   |
| Tablet         | 145       | 1.42%   |
| Mini pc        | 142       | 1.39%   |
| All in one     | 105       | 1.03%   |
| Server         | 45        | 0.44%   |
| System on chip | 26        | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8664      | 83.47%  |
| Enabled  | 1716      | 16.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10184     | 99.57%  |
| Yes  | 44        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2705      | 25.99%  |
| 4.01-8.0        | 2403      | 23.09%  |
| 8.01-16.0       | 1974      | 18.96%  |
| 32.01-64.0      | 1536      | 14.76%  |
| 3.01-4.0        | 913       | 8.77%   |
| 64.01-256.0     | 392       | 3.77%   |
| 24.01-32.0      | 241       | 2.32%   |
| 1.01-2.0        | 169       | 1.62%   |
| 2.01-3.0        | 43        | 0.41%   |
| 0.51-1.0        | 19        | 0.18%   |
| More than 256.0 | 8         | 0.08%   |
| Unknown         | 6         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 3208      | 27.51%  |
| 2.01-3.0    | 3119      | 26.75%  |
| 3.01-4.0    | 2411      | 20.68%  |
| 1.01-2.0    | 1600      | 13.72%  |
| 8.01-16.0   | 929       | 7.97%   |
| 0.51-1.0    | 160       | 1.37%   |
| 16.01-24.0  | 131       | 1.12%   |
| 24.01-32.0  | 43        | 0.37%   |
| 0.01-0.5    | 25        | 0.21%   |
| 32.01-64.0  | 23        | 0.2%    |
| Unknown     | 8         | 0.07%   |
| 64.01-256.0 | 3         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5999      | 56.76%  |
| 2       | 2735      | 25.88%  |
| 3       | 927       | 8.77%   |
| 4       | 421       | 3.98%   |
| 5       | 205       | 1.94%   |
| 6       | 107       | 1.01%   |
| 0       | 57        | 0.54%   |
| 7       | 52        | 0.49%   |
| 8       | 26        | 0.25%   |
| 9       | 13        | 0.12%   |
| 10      | 7         | 0.07%   |
| 12      | 4         | 0.04%   |
| 11      | 4         | 0.04%   |
| 36      | 2         | 0.02%   |
| 15      | 2         | 0.02%   |
| 14      | 2         | 0.02%   |
| 27      | 1         | 0.01%   |
| 24      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 13      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7715      | 74.84%  |
| Yes       | 2594      | 25.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8227      | 80.07%  |
| No        | 2048      | 19.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8228      | 79.97%  |
| No        | 2061      | 20.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7146      | 68.85%  |
| No        | 3233      | 31.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 2055      | 19.91%  |
| Germany     | 768       | 7.44%   |
| Brazil      | 703       | 6.81%   |
| Russia      | 646       | 6.26%   |
| Italy       | 444       | 4.3%    |
| France      | 404       | 3.91%   |
| UK          | 376       | 3.64%   |
| Canada      | 351       | 3.4%    |
| India       | 299       | 2.9%    |
| Poland      | 296       | 2.87%   |
| Netherlands | 267       | 2.59%   |
| Spain       | 248       | 2.4%    |
| Australia   | 232       | 2.25%   |
| Czechia     | 165       | 1.6%    |
| Sweden      | 155       | 1.5%    |
| Mexico      | 144       | 1.4%    |
| Turkey      | 130       | 1.26%   |
| Switzerland | 129       | 1.25%   |
| Austria     | 129       | 1.25%   |
| Belgium     | 106       | 1.03%   |
| Ukraine     | 99        | 0.96%   |
| Finland     | 93        | 0.9%    |
| Argentina   | 93        | 0.9%    |
| Romania     | 89        | 0.86%   |
| Norway      | 87        | 0.84%   |
| Portugal    | 81        | 0.78%   |
| Hungary     | 76        | 0.74%   |
| Indonesia   | 72        | 0.7%    |
| Chile       | 66        | 0.64%   |
| Denmark     | 65        | 0.63%   |
| New Zealand | 58        | 0.56%   |
| China       | 56        | 0.54%   |
| Greece      | 55        | 0.53%   |
| Colombia    | 55        | 0.53%   |
| Japan       | 52        | 0.5%    |
| Slovakia    | 47        | 0.46%   |
| Israel      | 46        | 0.45%   |
| Belarus     | 46        | 0.45%   |
| Bulgaria    | 41        | 0.4%    |
| Iran        | 40        | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 196       | 1.78%   |
| St Petersburg     | 92        | 0.83%   |
| Sao Paulo         | 91        | 0.82%   |
| Berlin            | 85        | 0.77%   |
| Vienna            | 83        | 0.75%   |
| Sydney            | 81        | 0.73%   |
| Warsaw            | 71        | 0.64%   |
| Paris             | 70        | 0.63%   |
| Prague            | 64        | 0.58%   |
| Milan             | 61        | 0.55%   |
| Amsterdam         | 59        | 0.53%   |
| Istanbul          | 56        | 0.51%   |
| Melbourne         | 54        | 0.49%   |
| Madrid            | 54        | 0.49%   |
| Munich            | 49        | 0.44%   |
| Helsinki          | 47        | 0.43%   |
| Zurich            | 43        | 0.39%   |
| Brisbane          | 43        | 0.39%   |
| Bengaluru         | 43        | 0.39%   |
| Hamburg           | 42        | 0.38%   |
| Oslo              | 40        | 0.36%   |
| Montreal          | 39        | 0.35%   |
| Rome              | 38        | 0.34%   |
| Rio de Janeiro    | 38        | 0.34%   |
| London            | 38        | 0.34%   |
| Mexico City       | 37        | 0.34%   |
| Budapest          | 37        | 0.34%   |
| Toronto           | 35        | 0.32%   |
| Frankfurt am Main | 34        | 0.31%   |
| Bucharest         | 34        | 0.31%   |
| Auckland          | 34        | 0.31%   |
| Delft             | 33        | 0.3%    |
| Portland          | 32        | 0.29%   |
| Athens            | 32        | 0.29%   |
| Los Angeles       | 31        | 0.28%   |
| Seattle           | 30        | 0.27%   |
| Kyiv              | 30        | 0.27%   |
| Denver            | 30        | 0.27%   |
| Chicago           | 30        | 0.27%   |
| Buenos Aires      | 30        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 3131      | 5184   | 20.08%  |
| WDC                       | 2133      | 3571   | 13.68%  |
| Seagate                   | 1787      | 2979   | 11.46%  |
| Toshiba                   | 945       | 1290   | 6.06%   |
| SanDisk                   | 941       | 1270   | 6.03%   |
| Kingston                  | 866       | 1206   | 5.55%   |
| Crucial                   | 619       | 896    | 3.97%   |
| Unknown                   | 577       | 808    | 3.7%    |
| SK hynix                  | 572       | 713    | 3.67%   |
| Intel                     | 533       | 816    | 3.42%   |
| Micron Technology         | 293       | 395    | 1.88%   |
| Hitachi                   | 267       | 394    | 1.71%   |
| A-DATA Technology         | 239       | 304    | 1.53%   |
| HGST                      | 236       | 379    | 1.51%   |
| Phison                    | 164       | 213    | 1.05%   |
| KIOXIA                    | 154       | 231    | 0.99%   |
| Apple                     | 120       | 152    | 0.77%   |
| China                     | 98        | 121    | 0.63%   |
| LITEON                    | 94        | 103    | 0.6%    |
| SPCC                      | 84        | 123    | 0.54%   |
| Silicon Motion            | 82        | 110    | 0.53%   |
| Corsair                   | 77        | 111    | 0.49%   |
| Micron/Crucial Technology | 76        | 97     | 0.49%   |
| PNY                       | 73        | 99     | 0.47%   |
| Transcend                 | 62        | 91     | 0.4%    |
| Phison Electronics        | 59        | 82     | 0.38%   |
| OCZ                       | 52        | 66     | 0.33%   |
| Patriot                   | 51        | 77     | 0.33%   |
| XPG                       | 47        | 67     | 0.3%    |
| LITEONIT                  | 36        | 44     | 0.23%   |
| Intenso                   | 36        | 47     | 0.23%   |
| Unknown                   | 36        | 40     | 0.23%   |
| Team                      | 35        | 48     | 0.22%   |
| Hewlett-Packard           | 35        | 58     | 0.22%   |
| ADATA Technology          | 35        | 38     | 0.22%   |
| JMicron Technology        | 34        | 49     | 0.22%   |
| Realtek Semiconductor     | 33        | 41     | 0.21%   |
| Gigabyte Technology       | 33        | 50     | 0.21%   |
| Plextor                   | 29        | 38     | 0.19%   |
| GOODRAM                   | 29        | 41     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 174       | 0.99%   |
| Samsung SSD 850 EVO 250GB                           | 167       | 0.95%   |
| Samsung SSD 860 EVO 500GB                           | 154       | 0.88%   |
| Samsung NVMe SSD Drive 512GB                        | 148       | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 142       | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                      | 137       | 0.78%   |
| Samsung NVMe SSD Drive 500GB                        | 132       | 0.75%   |
| Samsung SSD 850 EVO 500GB                           | 125       | 0.71%   |
| Samsung NVMe SSD Drive 1TB                          | 119       | 0.68%   |
| Samsung SSD 860 EVO 1TB                             | 115       | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 115       | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 105       | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                      | 97        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 94        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                        | 93        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 93        | 0.53%   |
| Unknown MMC Card  32GB                              | 89        | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB                      | 89        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 85        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 82        | 0.47%   |
| Crucial CT500MX500SSD1 500GB                        | 82        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                         | 81        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                     | 75        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB                      | 74        | 0.42%   |
| Unknown MMC Card  64GB                              | 72        | 0.41%   |
| Toshiba MQ01ABD100 1TB                              | 71        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 70        | 0.4%    |
| Samsung NVMe SSD Drive 1024GB                       | 70        | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 69        | 0.39%   |
| Intel NVMe SSD Drive 512GB                          | 69        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 66        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 65        | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 65        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 65        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 64        | 0.36%   |
| SanDisk NVMe SSD Drive 500GB                        | 64        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                       | 61        | 0.35%   |
| Unknown MMC Card  128GB                             | 55        | 0.31%   |
| Seagate Expansion+ 2TB                              | 55        | 0.31%   |
| Kingston SV300S37A120G 120GB SSD                    | 55        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1732      | 2879   | 36.94%  |
| WDC                 | 1514      | 2644   | 32.29%  |
| Toshiba             | 573       | 780    | 12.22%  |
| Hitachi             | 267       | 394    | 5.69%   |
| HGST                | 235       | 378    | 5.01%   |
| Samsung Electronics | 148       | 232    | 3.16%   |
| Unknown             | 43        | 59     | 0.92%   |
| Apple               | 29        | 31     | 0.62%   |
| SABRENT             | 24        | 26     | 0.51%   |
| Maxtor              | 23        | 26     | 0.49%   |
| Fujitsu             | 21        | 23     | 0.45%   |
| ASMT                | 18        | 19     | 0.38%   |
| Hewlett-Packard     | 7         | 27     | 0.15%   |
| USB3.0              | 6         | 6      | 0.13%   |
| JMicron Technology  | 5         | 14     | 0.11%   |
| Intenso             | 5         | 8      | 0.11%   |
| LIO-ORG             | 4         | 21     | 0.09%   |
| USB                 | 3         | 3      | 0.06%   |
| MaxDigital          | 3         | 3      | 0.06%   |
| LaCie               | 3         | 6      | 0.06%   |
| External            | 3         | 3      | 0.06%   |
| Synology            | 2         | 3      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| H/W                 | 2         | 4      | 0.04%   |
| ASMT109x            | 2         | 2      | 0.04%   |
| USB 3.0             | 1         | 3      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Phison              | 1         | 2      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| IET                 | 1         | 1      | 0.02%   |
| IB-AC703            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| ASMT106x            | 1         | 2      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1409      | 2294   | 26.89%  |
| Kingston            | 670       | 939    | 12.79%  |
| Crucial             | 553       | 815    | 10.56%  |
| SanDisk             | 471       | 635    | 8.99%   |
| WDC                 | 319       | 446    | 6.09%   |
| A-DATA Technology   | 179       | 232    | 3.42%   |
| Intel               | 167       | 286    | 3.19%   |
| Micron Technology   | 111       | 144    | 2.12%   |
| China               | 97        | 120    | 1.85%   |
| SK hynix            | 93        | 111    | 1.78%   |
| Toshiba             | 82        | 110    | 1.57%   |
| LITEON              | 79        | 88     | 1.51%   |
| PNY                 | 71        | 95     | 1.36%   |
| Apple               | 69        | 79     | 1.32%   |
| SPCC                | 66        | 96     | 1.26%   |
| Transcend           | 55        | 78     | 1.05%   |
| OCZ                 | 51        | 65     | 0.97%   |
| Patriot             | 46        | 70     | 0.88%   |
| Corsair             | 44        | 62     | 0.84%   |
| LITEONIT            | 36        | 44     | 0.69%   |
| Intenso             | 28        | 35     | 0.53%   |
| GOODRAM             | 28        | 40     | 0.53%   |
| Team                | 27        | 40     | 0.52%   |
| Plextor             | 25        | 33     | 0.48%   |
| KingSpec            | 25        | 35     | 0.48%   |
| Seagate             | 24        | 27     | 0.46%   |
| Gigabyte Technology | 24        | 34     | 0.46%   |
| Apacer              | 22        | 35     | 0.42%   |
| Netac               | 19        | 23     | 0.36%   |
| Unknown             | 18        | 18     | 0.34%   |
| JMicron Technology  | 16        | 18     | 0.31%   |
| Hewlett-Packard     | 16        | 18     | 0.31%   |
| Lexar               | 15        | 27     | 0.29%   |
| KingDian            | 15        | 16     | 0.29%   |
| Mushkin             | 12        | 27     | 0.23%   |
| Leven               | 10        | 11     | 0.19%   |
| Verbatim            | 9         | 12     | 0.17%   |
| KIOXIA-EXCERIA      | 7         | 7      | 0.13%   |
| Dogfish             | 7         | 10     | 0.13%   |
| BIWIN               | 7         | 8      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 4882      | 7326   | 34.92%  |
| SSD     | 4512      | 7574   | 32.27%  |
| HDD     | 3882      | 7612   | 27.76%  |
| MMC     | 505       | 714    | 3.61%   |
| Unknown | 201       | 280    | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6485      | 14595  | 52.08%  |
| NVMe | 4878      | 7304   | 39.17%  |
| SAS  | 585       | 893    | 4.7%    |
| MMC  | 505       | 714    | 4.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4689      | 8076   | 52.25%  |
| 0.51-1.0        | 2815      | 4434   | 31.37%  |
| 1.01-2.0        | 804       | 1295   | 8.96%   |
| 3.01-4.0        | 269       | 506    | 3%      |
| 4.01-10.0       | 193       | 449    | 2.15%   |
| 2.01-3.0        | 171       | 350    | 1.91%   |
| 10.01-20.0      | 28        | 67     | 0.31%   |
| More than 100.0 | 4         | 7      | 0.04%   |
| 0               | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 2145      | 19.78%  |
| 251-500        | 2122      | 19.57%  |
| 101-250        | 1822      | 16.8%   |
| 1001-2000      | 1392      | 12.84%  |
| 1-20           | 945       | 8.71%   |
| More than 3000 | 716       | 6.6%    |
| Unknown        | 664       | 6.12%   |
| 2001-3000      | 435       | 4.01%   |
| 51-100         | 394       | 3.63%   |
| 21-50          | 210       | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2901      | 25.47%  |
| 21-50          | 1811      | 15.9%   |
| 101-250        | 1700      | 14.93%  |
| 51-100         | 1421      | 12.48%  |
| 251-500        | 1170      | 10.27%  |
| 501-1000       | 881       | 7.73%   |
| Unknown        | 664       | 5.83%   |
| 1001-2000      | 473       | 4.15%   |
| More than 3000 | 214       | 1.88%   |
| 2001-3000      | 153       | 1.34%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 16        | 41     | 1.99%   |
| Seagate ST500LT012-1DG142 500GB                | 13        | 13     | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 10        | 20     | 1.24%   |
| HGST HTS721010A9E630 1TB                       | 9         | 12     | 1.12%   |
| Seagate ST3500418AS 500GB                      | 8         | 13     | 0.99%   |
| HGST HTS545050A7E680 500GB                     | 8         | 8      | 0.99%   |
| Toshiba MQ01ABD100 1TB                         | 7         | 7      | 0.87%   |
| Seagate ST9500325AS 500GB                      | 7         | 9      | 0.87%   |
| Seagate ST31000528AS 1TB                       | 7         | 9      | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 0.87%   |
| Samsung Electronics SSD 870 EVO 1TB            | 7         | 8      | 0.87%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 6         | 6      | 0.74%   |
| Toshiba MQ01ABD050 500GB                       | 6         | 7      | 0.74%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 0.74%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 0.74%   |
| Toshiba MQ01ABD075 752GB                       | 5         | 5      | 0.62%   |
| Seagate ST500LM021-1KJ152 500GB                | 5         | 7      | 0.62%   |
| Seagate ST31000524AS 1TB                       | 5         | 5      | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                 | 5         | 5      | 0.62%   |
| Samsung Electronics SSD 870 EVO 500GB          | 5         | 9      | 0.62%   |
| Samsung Electronics HD322HJ 320GB              | 5         | 7      | 0.62%   |
| Kingston SV300S37A120G 120GB SSD               | 5         | 5      | 0.62%   |
| Intel SSDSC2CT120A3 120GB                      | 5         | 26     | 0.62%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                       | 4         | 5      | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 4      | 0.5%    |
| Seagate ST31500341AS 1TB                       | 4         | 4      | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB                 | 4         | 4      | 0.5%    |
| Samsung Electronics HD501LJ 500GB              | 4         | 29     | 0.5%    |
| Hitachi HTS545050B9A300 500GB                  | 4         | 4      | 0.5%    |
| Crucial CT275MX300SSD1 275GB                   | 4         | 4      | 0.5%    |
| Crucial CT240M500SSD1 240GB                    | 4         | 4      | 0.5%    |
| Crucial CT128MX100SSD1 128GB                   | 4         | 6      | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 3         | 3      | 0.37%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 3         | 3      | 0.37%   |
| WDC WD20EZRX-00D8PB0 2TB                       | 3         | 4      | 0.37%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 3         | 3      | 0.37%   |
| WDC WD10EADS-00L5B1 1TB                        | 3         | 3      | 0.37%   |
| WDC WD1002FAEX-00Z3A0 1TB                      | 3         | 3      | 0.37%   |
| Toshiba MK3275GSX 320GB                        | 3         | 4      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 187       | 289    | 24.16%  |
| WDC                 | 156       | 224    | 20.16%  |
| Samsung Electronics | 67        | 106    | 8.66%   |
| Toshiba             | 61        | 67     | 7.88%   |
| Hitachi             | 57        | 73     | 7.36%   |
| Intel               | 34        | 69     | 4.39%   |
| HGST                | 31        | 38     | 4.01%   |
| Crucial             | 29        | 38     | 3.75%   |
| SanDisk             | 24        | 26     | 3.1%    |
| SK hynix            | 17        | 18     | 2.2%    |
| Kingston            | 17        | 18     | 2.2%    |
| Micron Technology   | 15        | 18     | 1.94%   |
| A-DATA Technology   | 14        | 14     | 1.81%   |
| LITEON              | 8         | 8      | 1.03%   |
| Maxtor              | 6         | 6      | 0.78%   |
| Corsair             | 6         | 9      | 0.78%   |
| Fujitsu             | 5         | 5      | 0.65%   |
| SPCC                | 4         | 5      | 0.52%   |
| OCZ                 | 4         | 5      | 0.52%   |
| OCZ-VERTEX3         | 3         | 3      | 0.39%   |
| Apple               | 3         | 3      | 0.39%   |
| Unknown             | 2         | 2      | 0.26%   |
| PNY                 | 2         | 2      | 0.26%   |
| LITEONIT            | 2         | 3      | 0.26%   |
| walram              | 1         | 1      | 0.13%   |
| Verbatim            | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 1      | 0.13%   |
| Teclast             | 1         | 1      | 0.13%   |
| Team                | 1         | 4      | 0.13%   |
| SSD                 | 1         | 1      | 0.13%   |
| Plextor             | 1         | 1      | 0.13%   |
| Origin              | 1         | 1      | 0.13%   |
| ORICO               | 1         | 1      | 0.13%   |
| Lenovo              | 1         | 2      | 0.13%   |
| KingDian            | 1         | 1      | 0.13%   |
| HGST HTS            | 1         | 1      | 0.13%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |
| China               | 1         | 1      | 0.13%   |
| BIWIN               | 1         | 1      | 0.13%   |
| ASMT                | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 187       | 289    | 35.28%  |
| WDC                 | 152       | 220    | 28.68%  |
| Toshiba             | 59        | 65     | 11.13%  |
| Hitachi             | 57        | 73     | 10.75%  |
| HGST                | 31        | 38     | 5.85%   |
| Samsung Electronics | 29        | 60     | 5.47%   |
| Maxtor              | 6         | 6      | 1.13%   |
| Fujitsu             | 5         | 5      | 0.94%   |
| HGST HTS            | 1         | 1      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMT                | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 495       | 760    | 67.16%  |
| SSD  | 205       | 273    | 27.82%  |
| NVMe | 37        | 41     | 5.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB                | 2         | 3      | 13.33%  |
| WDC WD5000BEVT-00ZAT0 500GB                      | 1         | 2      | 6.67%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 6.67%   |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 6.67%   |
| Toshiba HDWD130 3TB                              | 1         | 1      | 6.67%   |
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 6.67%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 2      | 6.67%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 6      | 6.67%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 33.33%  |
| Seagate             | 3         | 3      | 20%     |
| WDC                 | 2         | 3      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| SPCC                | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 6      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5895      | 13236  | 52.11%  |
| Works    | 4687      | 9173   | 41.43%  |
| Malfunc  | 716       | 1074   | 6.33%   |
| Failed   | 14        | 23     | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 6021      | 43.86%  |
| AMD                            | 2142      | 15.6%   |
| Samsung Electronics            | 1875      | 13.66%  |
| SanDisk                        | 819       | 5.97%   |
| SK hynix                       | 462       | 3.37%   |
| Toshiba America Info Systems   | 298       | 2.17%   |
| Phison Electronics             | 265       | 1.93%   |
| ASMedia Technology             | 231       | 1.68%   |
| Kingston Technology Company    | 230       | 1.68%   |
| Micron Technology              | 186       | 1.35%   |
| KIOXIA                         | 165       | 1.2%    |
| Micron/Crucial Technology      | 139       | 1.01%   |
| ADATA Technology               | 124       | 0.9%    |
| Marvell Technology Group       | 120       | 0.87%   |
| Silicon Motion                 | 111       | 0.81%   |
| JMicron Technology             | 87        | 0.63%   |
| Nvidia                         | 81        | 0.59%   |
| Realtek Semiconductor          | 49        | 0.36%   |
| Union Memory (Shenzhen)        | 41        | 0.3%    |
| Lite-On Technology             | 37        | 0.27%   |
| LSI Logic / Symbios Logic      | 27        | 0.2%    |
| Solid State Storage Technology | 25        | 0.18%   |
| Broadcom / LSI                 | 25        | 0.18%   |
| Seagate Technology             | 24        | 0.17%   |
| Lenovo                         | 23        | 0.17%   |
| Apple                          | 19        | 0.14%   |
| MAXIO Technology (Hangzhou)    | 14        | 0.1%    |
| Silicon Image                  | 12        | 0.09%   |
| VIA Technologies               | 10        | 0.07%   |
| Shenzhen Longsys Electronics   | 8         | 0.06%   |
| Hewlett-Packard                | 8         | 0.06%   |
| Yangtze Memory Technologies    | 7         | 0.05%   |
| Adaptec                        | 7         | 0.05%   |
| Integrated Technology Express  | 4         | 0.03%   |
| Biwin Storage Technology       | 4         | 0.03%   |
| ULi Electronics                | 3         | 0.02%   |
| Netac Technology               | 3         | 0.02%   |
| Lite-On IT Corp. / Plextor     | 3         | 0.02%   |
| INNOGRIT                       | 3         | 0.02%   |
| 3ware                          | 3         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1609      | 10.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1024      | 6.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 693       | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 406       | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 395       | 2.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 372       | 2.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 363       | 2.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 318       | 2.08%   |
| Samsung NVMe SSD Controller 980                                                | 306       | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 275       | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 244       | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 238       | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 232       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 225       | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 221       | 1.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 219       | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 212       | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 211       | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 200       | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 190       | 1.24%   |
| Micron NVMe Storage Controller                                                 | 183       | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 168       | 1.1%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 164       | 1.07%   |
| Intel SATA Controller [RAID mode]                                              | 163       | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 157       | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 156       | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 153       | 1%      |
| Intel SSD 660P Series                                                          | 150       | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 149       | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 146       | 0.95%   |
| Phison E12 NVMe Controller                                                     | 140       | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 139       | 0.91%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 136       | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 133       | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 119       | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 109       | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                            | 104       | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                         | 101       | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 98        | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 93        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7029      | 51.75%  |
| NVMe | 4885      | 35.97%  |
| RAID | 968       | 7.13%   |
| IDE  | 642       | 4.73%   |
| SAS  | 43        | 0.32%   |
| SCSI | 15        | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 7439      | 72.73%  |
| AMD      | 2758      | 26.97%  |
| ARM      | 27        | 0.26%   |
| Unknown  | 3         | 0.03%   |
| QUALCOMM | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 181       | 1.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 165       | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 162       | 1.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 152       | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 128       | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor             | 122       | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 116       | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 115       | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 112       | 1.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 109       | 1.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 105       | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 104       | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 103       | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 92        | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 91        | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 87        | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 84        | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 74        | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 72        | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 70        | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 70        | 0.68%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 70        | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 65        | 0.63%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 64        | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 62        | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 61        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 61        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 60        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 60        | 0.59%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 59        | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 57        | 0.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 56        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 53        | 0.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 52        | 0.51%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 52        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 50        | 0.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 49        | 0.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 49        | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 48        | 0.47%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 48        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2556      | 24.97%  |
| Intel Core i5           | 2316      | 22.62%  |
| AMD Ryzen 5             | 883       | 8.62%   |
| Other                   | 828       | 8.09%   |
| AMD Ryzen 7             | 716       | 6.99%   |
| Intel Core i3           | 575       | 5.62%   |
| AMD Ryzen 9             | 291       | 2.84%   |
| Intel Xeon              | 221       | 2.16%   |
| Intel Celeron           | 206       | 2.01%   |
| Intel Core 2 Duo        | 178       | 1.74%   |
| Intel Atom              | 159       | 1.55%   |
| Intel Pentium           | 136       | 1.33%   |
| AMD FX                  | 127       | 1.24%   |
| AMD Ryzen 3             | 107       | 1.05%   |
| Intel Core i9           | 104       | 1.02%   |
| AMD Ryzen 7 PRO         | 93        | 0.91%   |
| AMD Ryzen 5 PRO         | 61        | 0.6%    |
| AMD A6                  | 56        | 0.55%   |
| AMD A10                 | 55        | 0.54%   |
| AMD A8                  | 51        | 0.5%    |
| Intel Core 2 Quad       | 47        | 0.46%   |
| AMD Ryzen Threadripper  | 41        | 0.4%    |
| Intel Pentium Dual-Core | 37        | 0.36%   |
| AMD Phenom II X4        | 31        | 0.3%    |
| AMD A4                  | 30        | 0.29%   |
| Intel Pentium Silver    | 28        | 0.27%   |
| AMD Athlon              | 25        | 0.24%   |
| AMD Athlon II X2        | 19        | 0.19%   |
| Intel Core 2            | 18        | 0.18%   |
| AMD Phenom II X6        | 16        | 0.16%   |
| Intel Core m3           | 14        | 0.14%   |
| AMD Phenom              | 12        | 0.12%   |
| AMD Athlon 64 X2        | 12        | 0.12%   |
| AMD A12                 | 12        | 0.12%   |
| Intel Pentium Dual      | 11        | 0.11%   |
| AMD E1                  | 11        | 0.11%   |
| AMD E                   | 11        | 0.11%   |
| Intel Genuine           | 10        | 0.1%    |
| Intel Core m5           | 8         | 0.08%   |
| AMD Athlon X4           | 8         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 4212      | 41.12%  |
| 2       | 2910      | 28.41%  |
| 6       | 1371      | 13.38%  |
| 8       | 1103      | 10.77%  |
| 12      | 247       | 2.41%   |
| 16      | 119       | 1.16%   |
| 10      | 73        | 0.71%   |
| 14      | 62        | 0.61%   |
| 1       | 52        | 0.51%   |
| 3       | 50        | 0.49%   |
| 24      | 16        | 0.16%   |
| 32      | 10        | 0.1%    |
| Unknown | 7         | 0.07%   |
| 20      | 3         | 0.03%   |
| 36      | 2         | 0.02%   |
| 96      | 1         | 0.01%   |
| 72      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10147     | 99.19%  |
| 2       | 73        | 0.71%   |
| Unknown | 7         | 0.07%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8173      | 79.76%  |
| 1       | 2067      | 20.17%  |
| Unknown | 7         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9979      | 97.14%  |
| Unknown        | 282       | 2.75%   |
| 64-bit         | 8         | 0.08%   |
| 32-bit         | 4         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 723       | 6.91%   |
| 0x306a9    | 556       | 5.32%   |
| 0x306c3    | 501       | 4.79%   |
| 0x806ea    | 463       | 4.43%   |
| 0x806ec    | 456       | 4.36%   |
| 0x206a7    | 436       | 4.17%   |
| 0x906ea    | 414       | 3.96%   |
| 0x806c1    | 414       | 3.96%   |
| 0x806e9    | 347       | 3.32%   |
| 0x506e3    | 301       | 2.88%   |
| 0x406e3    | 298       | 2.85%   |
| 0x08701021 | 267       | 2.55%   |
| 0x906e9    | 266       | 2.54%   |
| 0x40651    | 232       | 2.22%   |
| 0x306d4    | 222       | 2.12%   |
| 0x0a50000c | 222       | 2.12%   |
| 0x1067a    | 166       | 1.59%   |
| 0xa0652    | 165       | 1.58%   |
| 0x08108109 | 159       | 1.52%   |
| 0x08600106 | 155       | 1.48%   |
| 0x0800820d | 142       | 1.36%   |
| 0x706e5    | 139       | 1.33%   |
| 0x08108102 | 123       | 1.18%   |
| 0x08701013 | 118       | 1.13%   |
| 0x906ed    | 114       | 1.09%   |
| 0x20655    | 113       | 1.08%   |
| 0x906a3    | 103       | 0.99%   |
| 0x806eb    | 99        | 0.95%   |
| 0x30678    | 99        | 0.95%   |
| 0x08608103 | 91        | 0.87%   |
| 0x08600104 | 87        | 0.83%   |
| 0x406c4    | 74        | 0.71%   |
| 0x0a201016 | 74        | 0.71%   |
| 0x06000852 | 73        | 0.7%    |
| 0x0810100b | 65        | 0.62%   |
| 0x0a201009 | 63        | 0.6%    |
| 0x08001138 | 60        | 0.57%   |
| 0x806d1    | 59        | 0.56%   |
| 0x08600103 | 56        | 0.54%   |
| 0x90672    | 53        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2360      | 23.03%  |
| Haswell          | 843       | 8.23%   |
| Zen 2            | 753       | 7.35%   |
| Skylake          | 661       | 6.45%   |
| IvyBridge        | 612       | 5.97%   |
| SandyBridge      | 497       | 4.85%   |
| Zen 3            | 493       | 4.81%   |
| Zen+             | 475       | 4.64%   |
| TigerLake        | 469       | 4.58%   |
| CometLake        | 292       | 2.85%   |
| Unknown          | 281       | 2.74%   |
| Zen              | 280       | 2.73%   |
| Broadwell        | 243       | 2.37%   |
| IceLake          | 239       | 2.33%   |
| Penryn           | 237       | 2.31%   |
| Silvermont       | 234       | 2.28%   |
| Alderlake Hybrid | 216       | 2.11%   |
| Westmere         | 180       | 1.76%   |
| Piledriver       | 162       | 1.58%   |
| K10              | 108       | 1.05%   |
| Core             | 90        | 0.88%   |
| Excavator        | 85        | 0.83%   |
| Goldmont plus    | 84        | 0.82%   |
| Nehalem          | 80        | 0.78%   |
| Goldmont         | 47        | 0.46%   |
| Puma             | 35        | 0.34%   |
| Steamroller      | 34        | 0.33%   |
| Jaguar           | 25        | 0.24%   |
| K8 Hammer        | 23        | 0.22%   |
| Bulldozer        | 23        | 0.22%   |
| Bobcat           | 21        | 0.2%    |
| K10 Llano        | 17        | 0.17%   |
| Tremont          | 16        | 0.16%   |
| Bonnell          | 15        | 0.15%   |
| NetBurst         | 8         | 0.08%   |
| K8 & K10 hybrid  | 5         | 0.05%   |
| P6               | 3         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5999      | 47.97%  |
| Nvidia                           | 3453      | 27.61%  |
| AMD                              | 3008      | 24.05%  |
| Matrox Electronics Systems       | 21        | 0.17%   |
| ASPEED Technology                | 21        | 0.17%   |
| ATI Technologies                 | 3         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 477       | 3.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 425       | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 354       | 2.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 351       | 2.75%   |
| AMD Renoir                                                                               | 344       | 2.69%   |
| Intel HD Graphics 620                                                                    | 333       | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 321       | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 300       | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 297       | 2.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 286       | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 268       | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 254       | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 243       | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 235       | 1.84%   |
| Intel HD Graphics 530                                                                    | 199       | 1.56%   |
| Intel HD Graphics 630                                                                    | 198       | 1.55%   |
| Intel HD Graphics 5500                                                                   | 198       | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 171       | 1.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 158       | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 148       | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 129       | 1.01%   |
| AMD Lucienne                                                                             | 126       | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 122       | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 121       | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 111       | 0.87%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 108       | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 106       | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 100       | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 99        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 98        | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 96        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 87        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 86        | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 84        | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 84        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 82        | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                              | 77        | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 71        | 0.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 67        | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 4000      | 38.82%  |
| 1 x AMD                  | 2336      | 22.67%  |
| 1 x Nvidia               | 1601      | 15.54%  |
| Intel + Nvidia           | 1580      | 15.33%  |
| Intel + AMD              | 271       | 2.63%   |
| AMD + Nvidia             | 239       | 2.32%   |
| 2 x AMD                  | 159       | 1.54%   |
| Other                    | 34        | 0.33%   |
| 2 x Nvidia               | 22        | 0.21%   |
| 1 x Matrox               | 15        | 0.15%   |
| 1 x ASPEED               | 15        | 0.15%   |
| 2 x Intel                | 10        | 0.1%    |
| Nvidia + Matrox          | 4         | 0.04%   |
| Nvidia + ASPEED          | 3         | 0.03%   |
| Intel + 2 x Nvidia       | 3         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.02%   |
| AMD + Matrox             | 2         | 0.02%   |
| AMD + ASPEED             | 2         | 0.02%   |
| 3 x AMD                  | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.01%   |
| 1 x SiS                  | 1         | 0.01%   |
| 1 x S3 Graphics          | 1         | 0.01%   |
| Intel + 2 x AMD          | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 8433      | 81.29%  |
| Proprietary | 1716      | 16.54%  |
| Unknown     | 225       | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5539      | 52.72%  |
| 1.01-2.0   | 1328      | 12.64%  |
| 0.01-0.5   | 985       | 9.38%   |
| 3.01-4.0   | 816       | 7.77%   |
| 0.51-1.0   | 688       | 6.55%   |
| 7.01-8.0   | 630       | 6%      |
| 5.01-6.0   | 251       | 2.39%   |
| 8.01-16.0  | 186       | 1.77%   |
| 2.01-3.0   | 73        | 0.69%   |
| 16.01-24.0 | 10        | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1379      | 11.31%  |
| Samsung Electronics     | 1246      | 10.22%  |
| BOE                     | 1172      | 9.61%   |
| Chimei Innolux          | 1067      | 8.75%   |
| LG Display              | 1060      | 8.69%   |
| Dell                    | 949       | 7.78%   |
| Goldstar                | 735       | 6.03%   |
| Hewlett-Packard         | 390       | 3.2%    |
| Acer                    | 390       | 3.2%    |
| Sharp                   | 368       | 3.02%   |
| AOC                     | 331       | 2.71%   |
| BenQ                    | 318       | 2.61%   |
| Ancor Communications    | 265       | 2.17%   |
| Lenovo                  | 260       | 2.13%   |
| Philips                 | 251       | 2.06%   |
| Apple                   | 200       | 1.64%   |
| ViewSonic               | 146       | 1.2%    |
| PANDA                   | 141       | 1.16%   |
| Iiyama                  | 128       | 1.05%   |
| ASUSTek Computer        | 110       | 0.9%    |
| InfoVision              | 96        | 0.79%   |
| CSO                     | 86        | 0.71%   |
| Chi Mei Optoelectronics | 79        | 0.65%   |
| Sony                    | 61        | 0.5%    |
| MSI                     | 51        | 0.42%   |
| Eizo                    | 48        | 0.39%   |
| Sceptre Tech            | 46        | 0.38%   |
| Panasonic               | 41        | 0.34%   |
| HannStar                | 37        | 0.3%    |
| Gigabyte Technology     | 35        | 0.29%   |
| Unknown                 | 33        | 0.27%   |
| NEC Computers           | 33        | 0.27%   |
| Vizio                   | 27        | 0.22%   |
| TMX                     | 27        | 0.22%   |
| Toshiba                 | 22        | 0.18%   |
| Fujitsu Siemens         | 21        | 0.17%   |
| Mi                      | 19        | 0.16%   |
| JDI                     | 19        | 0.16%   |
| Insignia                | 19        | 0.16%   |
| RTK                     | 17        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 73        | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 60        | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 58        | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 55        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 47        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 44        | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 43        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 41        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 38        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 38        | 0.3%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 38        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 36        | 0.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 35        | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 34        | 0.27%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 34        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 32        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 32        | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 32        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 32        | 0.25%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 28        | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 27        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 27        | 0.21%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 27        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 27        | 0.21%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch         | 25        | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 25        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 25        | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 25        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 24        | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 23        | 0.18%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 23        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 22        | 0.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 22        | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 22        | 0.17%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 22        | 0.17%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 22        | 0.17%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 21        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 21        | 0.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 21        | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 21        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5603      | 49.31%  |
| 1366x768 (WXGA)    | 1450      | 12.76%  |
| 3840x2160 (4K)     | 932       | 8.2%    |
| 2560x1440 (QHD)    | 808       | 7.11%   |
| 1920x1200 (WUXGA)  | 357       | 3.14%   |
| 1600x900 (HD+)     | 325       | 2.86%   |
| 1280x1024 (SXGA)   | 203       | 1.79%   |
| 1680x1050 (WSXGA+) | 201       | 1.77%   |
| 3440x1440          | 191       | 1.68%   |
| 2560x1080          | 167       | 1.47%   |
| 1440x900 (WXGA+)   | 164       | 1.44%   |
| 2560x1600          | 141       | 1.24%   |
| 1280x800 (WXGA)    | 103       | 0.91%   |
| 2880x1800          | 88        | 0.77%   |
| 1360x768           | 66        | 0.58%   |
| 3840x2400          | 56        | 0.49%   |
| 2160x1440          | 50        | 0.44%   |
| 3840x1080          | 41        | 0.36%   |
| Unknown            | 40        | 0.35%   |
| 2256x1504          | 35        | 0.31%   |
| 3200x1800 (QHD+)   | 33        | 0.29%   |
| 2736x1824          | 26        | 0.23%   |
| 1600x1200          | 25        | 0.22%   |
| 3000x2000          | 23        | 0.2%    |
| 1920x1280          | 21        | 0.18%   |
| 1920x540           | 20        | 0.18%   |
| 1024x768 (XGA)     | 20        | 0.18%   |
| 2288x1287          | 16        | 0.14%   |
| 3840x1600          | 10        | 0.09%   |
| 3456x2160          | 9         | 0.08%   |
| 3200x2000          | 9         | 0.08%   |
| 3072x1920          | 9         | 0.08%   |
| 2520x1680          | 9         | 0.08%   |
| 2240x1400          | 9         | 0.08%   |
| 1280x720 (HD)      | 9         | 0.08%   |
| 2048x1152          | 7         | 0.06%   |
| 2160x1350          | 6         | 0.05%   |
| 1280x960           | 6         | 0.05%   |
| 1024x600           | 5         | 0.04%   |
| 3240x2160          | 4         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2847      | 23.27%  |
| 13      | 1420      | 11.6%   |
| 27      | 1168      | 9.54%   |
| 14      | 1137      | 9.29%   |
| 24      | 1080      | 8.83%   |
| 23      | 795       | 6.5%    |
| 21      | 679       | 5.55%   |
| 17      | 443       | 3.62%   |
| 34      | 308       | 2.52%   |
| 31      | 290       | 2.37%   |
| 12      | 243       | 1.99%   |
| 19      | 232       | 1.9%    |
| 18      | 204       | 1.67%   |
| 22      | 163       | 1.33%   |
| Unknown | 149       | 1.22%   |
| 20      | 145       | 1.18%   |
| 16      | 120       | 0.98%   |
| 11      | 78        | 0.64%   |
| 32      | 72        | 0.59%   |
| 25      | 72        | 0.59%   |
| 84      | 68        | 0.56%   |
| 72      | 61        | 0.5%    |
| 40      | 58        | 0.47%   |
| 26      | 42        | 0.34%   |
| 54      | 36        | 0.29%   |
| 48      | 34        | 0.28%   |
| 10      | 29        | 0.24%   |
| 29      | 28        | 0.23%   |
| 42      | 26        | 0.21%   |
| 35      | 19        | 0.16%   |
| 28      | 19        | 0.16%   |
| 36      | 15        | 0.12%   |
| 37      | 14        | 0.11%   |
| 142     | 13        | 0.11%   |
| 52      | 13        | 0.11%   |
| 39      | 13        | 0.11%   |
| 46      | 12        | 0.1%    |
| 49      | 11        | 0.09%   |
| 65      | 10        | 0.08%   |
| 43      | 9         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4778      | 40.01%  |
| 501-600        | 2786      | 23.33%  |
| 401-500        | 1247      | 10.44%  |
| 201-300        | 1070      | 8.96%   |
| 351-400        | 605       | 5.07%   |
| 601-700        | 461       | 3.86%   |
| 701-800        | 401       | 3.36%   |
| Unknown        | 149       | 1.25%   |
| 1501-2000      | 143       | 1.2%    |
| 1001-1500      | 137       | 1.15%   |
| 801-900        | 104       | 0.87%   |
| 901-1000       | 43        | 0.36%   |
| More than 2000 | 15        | 0.13%   |
| 101-200        | 1         | 0.01%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8300      | 78.85%  |
| 16/10   | 1228      | 11.67%  |
| 21/9    | 355       | 3.37%   |
| 5/4     | 199       | 1.89%   |
| 3/2     | 194       | 1.84%   |
| Unknown | 93        | 0.88%   |
| 4/3     | 74        | 0.7%    |
| 32/9    | 37        | 0.35%   |
| 6/5     | 15        | 0.14%   |
| 1.00    | 13        | 0.12%   |
| 1.96    | 5         | 0.05%   |
| 0.89    | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.40    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2848      | 23.59%  |
| 201-250        | 2076      | 17.19%  |
| 81-90          | 1946      | 16.12%  |
| 301-350        | 1205      | 9.98%   |
| 351-500        | 713       | 5.9%    |
| 71-80          | 620       | 5.13%   |
| 151-200        | 589       | 4.88%   |
| 251-300        | 423       | 3.5%    |
| 121-130        | 356       | 2.95%   |
| More than 1000 | 241       | 2%      |
| 141-150        | 221       | 1.83%   |
| 61-70          | 216       | 1.79%   |
| 501-1000       | 194       | 1.61%   |
| Unknown        | 149       | 1.23%   |
| 111-120        | 105       | 0.87%   |
| 51-60          | 85        | 0.7%    |
| 131-140        | 38        | 0.31%   |
| 91-100         | 24        | 0.2%    |
| 41-50          | 23        | 0.19%   |
| 1-40           | 3         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 3678      | 31.49%  |
| 51-100        | 3493      | 29.91%  |
| 101-120       | 2610      | 22.35%  |
| 161-240       | 1066      | 9.13%   |
| More than 240 | 475       | 4.07%   |
| 1-50          | 208       | 1.78%   |
| Unknown       | 149       | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7641      | 72.18%  |
| 2     | 2279      | 21.53%  |
| 0     | 338       | 3.19%   |
| 3     | 291       | 2.75%   |
| 4     | 31        | 0.29%   |
| 5     | 6         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5883      | 39.11%  |
| Realtek Semiconductor             | 5143      | 34.19%  |
| Qualcomm Atheros                  | 1396      | 9.28%   |
| Broadcom                          | 583       | 3.88%   |
| MediaTek                          | 268       | 1.78%   |
| TP-Link                           | 169       | 1.12%   |
| Ralink Technology                 | 129       | 0.86%   |
| Broadcom Limited                  | 107       | 0.71%   |
| Lenovo                            | 96        | 0.64%   |
| Marvell Technology Group          | 89        | 0.59%   |
| Ralink                            | 88        | 0.59%   |
| ASIX Electronics                  | 82        | 0.55%   |
| Sierra Wireless                   | 67        | 0.45%   |
| Nvidia                            | 64        | 0.43%   |
| Microsoft                         | 53        | 0.35%   |
| DisplayLink                       | 49        | 0.33%   |
| Aquantia                          | 48        | 0.32%   |
| Samsung Electronics               | 46        | 0.31%   |
| Dell                              | 45        | 0.3%    |
| ASUSTek Computer                  | 44        | 0.29%   |
| Qualcomm                          | 43        | 0.29%   |
| Xiaomi                            | 37        | 0.25%   |
| Qualcomm Atheros Communications   | 36        | 0.24%   |
| D-Link                            | 33        | 0.22%   |
| Huawei Technologies               | 31        | 0.21%   |
| Ericsson Business Mobile Networks | 30        | 0.2%    |
| NetGear                           | 29        | 0.19%   |
| Hewlett-Packard                   | 27        | 0.18%   |
| Google                            | 22        | 0.15%   |
| Edimax Technology                 | 22        | 0.15%   |
| Apple                             | 22        | 0.15%   |
| Linksys                           | 18        | 0.12%   |
| D-Link System                     | 15        | 0.1%    |
| FIBOCOM                           | 14        | 0.09%   |
| Motorola PCS                      | 12        | 0.08%   |
| Mellanox Technologies             | 11        | 0.07%   |
| JMicron Technology                | 11        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.06%   |
| ICS Advent                        | 9         | 0.06%   |
| Belkin Components                 | 9         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3476      | 19.3%   |
| Intel Wi-Fi 6 AX200                                               | 814       | 4.52%   |
| Intel Wireless 8265 / 8275                                        | 516       | 2.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 432       | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 430       | 2.39%   |
| Intel Wi-Fi 6 AX201                                               | 372       | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 367       | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 348       | 1.93%   |
| Intel Wireless 8260                                               | 275       | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 274       | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 268       | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 257       | 1.43%   |
| Intel Wireless 7265                                               | 238       | 1.32%   |
| Intel Wireless 7260                                               | 238       | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 225       | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 216       | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 216       | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 214       | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 188       | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 177       | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 171       | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 170       | 0.94%   |
| Intel Wireless-AC 9260                                            | 168       | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 166       | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 155       | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 154       | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 154       | 0.86%   |
| Intel Wireless 3165                                               | 148       | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 148       | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 146       | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 140       | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 129       | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 128       | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 119       | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 111       | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 109       | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 101       | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 100       | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 97        | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 89        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4805      | 55.39%  |
| Realtek Semiconductor                 | 1175      | 13.54%  |
| Qualcomm Atheros                      | 1134      | 13.07%  |
| Broadcom                              | 408       | 4.7%    |
| MediaTek                              | 261       | 3.01%   |
| TP-Link                               | 148       | 1.71%   |
| Ralink Technology                     | 129       | 1.49%   |
| Ralink                                | 88        | 1.01%   |
| Broadcom Limited                      | 79        | 0.91%   |
| Sierra Wireless                       | 67        | 0.77%   |
| Microsoft                             | 49        | 0.56%   |
| ASUSTek Computer                      | 41        | 0.47%   |
| Qualcomm Atheros Communications       | 36        | 0.41%   |
| Dell                                  | 34        | 0.39%   |
| Qualcomm                              | 29        | 0.33%   |
| Marvell Technology Group              | 29        | 0.33%   |
| NetGear                               | 27        | 0.31%   |
| D-Link                                | 25        | 0.29%   |
| Edimax Technology                     | 22        | 0.25%   |
| Linksys                               | 16        | 0.18%   |
| Fibocom                               | 14        | 0.16%   |
| D-Link System                         | 12        | 0.14%   |
| Belkin Components                     | 9         | 0.1%    |
| Hewlett-Packard                       | 7         | 0.08%   |
| AVM                                   | 5         | 0.06%   |
| Wilocity                              | 4         | 0.05%   |
| IMC Networks                          | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Xiaomi                                | 2         | 0.02%   |
| BUFFALO                               | 2         | 0.02%   |
| AboCom Systems                        | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Toshiba                               | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Quectel Wireless Solutions            | 1         | 0.01%   |
| PLANEX                                | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 814       | 9.32%   |
| Intel Wireless 8265 / 8275                                     | 516       | 5.91%   |
| Intel Wi-Fi 6 AX201                                            | 372       | 4.26%   |
| Intel Wireless 8260                                            | 275       | 3.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 274       | 3.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 268       | 3.07%   |
| Intel Wireless 7265                                            | 238       | 2.73%   |
| Intel Wireless 7260                                            | 238       | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 225       | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 216       | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 214       | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 188       | 2.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 177       | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 171       | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 170       | 1.95%   |
| Intel Wireless-AC 9260                                         | 168       | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 166       | 1.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 154       | 1.76%   |
| Intel Wireless 3165                                            | 148       | 1.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 148       | 1.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 146       | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 140       | 1.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 129       | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 119       | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 109       | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 89        | 1.02%   |
| Intel Wireless 3160                                            | 80        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 80        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 78        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 70        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 66        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 62        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                  | 57        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 54        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 53        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 52        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                | 47        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 46        | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 45        | 0.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 45        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4619      | 52.07%  |
| Intel                                  | 2878      | 32.44%  |
| Qualcomm Atheros                       | 368       | 4.15%   |
| Broadcom                               | 257       | 2.9%    |
| Lenovo                                 | 94        | 1.06%   |
| ASIX Electronics                       | 82        | 0.92%   |
| Nvidia                                 | 64        | 0.72%   |
| Marvell Technology Group               | 60        | 0.68%   |
| DisplayLink                            | 49        | 0.55%   |
| Aquantia                               | 48        | 0.54%   |
| Samsung Electronics                    | 45        | 0.51%   |
| Xiaomi                                 | 35        | 0.39%   |
| Broadcom Limited                       | 28        | 0.32%   |
| TP-Link                                | 23        | 0.26%   |
| Google                                 | 22        | 0.25%   |
| Apple                                  | 22        | 0.25%   |
| Huawei Technologies                    | 18        | 0.2%    |
| Qualcomm                               | 14        | 0.16%   |
| JMicron Technology                     | 11        | 0.12%   |
| Mellanox Technologies                  | 10        | 0.11%   |
| Motorola PCS                           | 9         | 0.1%    |
| ICS Advent                             | 9         | 0.1%    |
| OPPO Electronics                       | 8         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 8         | 0.09%   |
| D-Link                                 | 8         | 0.09%   |
| MediaTek                               | 7         | 0.08%   |
| HMD Global                             | 6         | 0.07%   |
| Hewlett-Packard                        | 6         | 0.07%   |
| Cypress Semiconductor                  | 5         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.05%   |
| MosChip Semiconductor                  | 3         | 0.03%   |
| Microsoft                              | 3         | 0.03%   |
| D-Link System                          | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| ADMtek                                 | 3         | 0.03%   |
| vivo                                   | 2         | 0.02%   |
| VIA Technologies                       | 2         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.02%   |
| Standard Microsystems                  | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3476      | 38.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 432       | 4.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 430       | 4.71%   |
| Intel I211 Gigabit Network Connection                             | 367       | 4.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 348       | 3.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 257       | 2.81%   |
| Intel Ethernet Connection (2) I219-V                              | 216       | 2.36%   |
| Intel Ethernet Connection (4) I219-LM                             | 155       | 1.7%    |
| Intel Ethernet Controller I225-V                                  | 154       | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 128       | 1.4%    |
| Intel Ethernet Connection (7) I219-V                              | 111       | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 101       | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 100       | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 97        | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 87        | 0.95%   |
| Intel Ethernet Connection (10) I219-V                             | 77        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 76        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 72        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 72        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 65        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 63        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 59        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 54        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 54        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 53        | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                             | 52        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50        | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 45        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 45        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 43        | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 42        | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 41        | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 39        | 0.43%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 38        | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 38        | 0.42%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 38        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 35        | 0.38%   |
| Intel Ethernet Connection (13) I219-V                             | 34        | 0.37%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 34        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 8230      | 49.63%  |
| Ethernet | 8212      | 49.52%  |
| Modem    | 120       | 0.72%   |
| Unknown  | 20        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6596      | 60.95%  |
| Ethernet | 4224      | 39.03%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5417      | 52.66%  |
| 1     | 4293      | 41.73%  |
| 3     | 309       | 3%      |
| 0     | 202       | 1.96%   |
| 4     | 39        | 0.38%   |
| 5     | 16        | 0.16%   |
| 6     | 6         | 0.06%   |
| 8     | 3         | 0.03%   |
| 9     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 8603      | 82.27%  |
| Yes     | 1848      | 17.67%  |
| Unknown | 6         | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4117      | 56.84%  |
| Realtek Semiconductor           | 640       | 8.84%   |
| Qualcomm Atheros Communications | 514       | 7.1%    |
| Cambridge Silicon Radio         | 365       | 5.04%   |
| Broadcom                        | 280       | 3.87%   |
| IMC Networks                    | 247       | 3.41%   |
| Lite-On Technology              | 204       | 2.82%   |
| Foxconn / Hon Hai               | 203       | 2.8%    |
| Apple                           | 203       | 2.8%    |
| ASUSTek Computer                | 124       | 1.71%   |
| Realtek                         | 58        | 0.8%    |
| Dell                            | 42        | 0.58%   |
| MediaTek                        | 41        | 0.57%   |
| Marvell Semiconductor           | 30        | 0.41%   |
| Hewlett-Packard                 | 29        | 0.4%    |
| Ralink                          | 27        | 0.37%   |
| TP-Link                         | 24        | 0.33%   |
| Toshiba                         | 23        | 0.32%   |
| Foxconn International           | 9         | 0.12%   |
| Belkin Components               | 7         | 0.1%    |
| USI                             | 6         | 0.08%   |
| HTC (High Tech Computer)        | 6         | 0.08%   |
| Edimax Technology               | 6         | 0.08%   |
| Opticis                         | 5         | 0.07%   |
| Ralink Technology               | 4         | 0.06%   |
| Integrated System Solution      | 4         | 0.06%   |
| Dynex                           | 4         | 0.06%   |
| Smart Modular Technologies      | 3         | 0.04%   |
| Chicony Electronics             | 3         | 0.04%   |
| Alps Electric                   | 3         | 0.04%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Taiyo Yuden                     | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Kensington                      | 1         | 0.01%   |
| D-Link System                   | 1         | 0.01%   |
| Creative Technology             | 1         | 0.01%   |
| Corsair                         | 1         | 0.01%   |
| BUFFALO                         | 1         | 0.01%   |
| Askey Computer                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1385      | 19.1%   |
| Intel AX200 Bluetooth                               | 783       | 10.8%   |
| Intel AX201 Bluetooth                               | 767       | 10.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 552       | 7.61%   |
| Realtek Bluetooth Radio                             | 390       | 5.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 365       | 5.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 286       | 3.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 153       | 2.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 151       | 2.08%   |
| Intel AX210 Bluetooth                               | 148       | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 144       | 1.99%   |
| Apple Bluetooth Host Controller                     | 118       | 1.63%   |
| Intel Bluetooth Device                              | 102       | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 92        | 1.27%   |
| Foxconn / Hon Hai Wireless_Device                   | 91        | 1.25%   |
| IMC Networks Wireless_Device                        | 89        | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 75        | 1.03%   |
| IMC Networks Bluetooth Radio                        | 73        | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 72        | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 66        | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 64        | 0.88%   |
| Realtek Bluetooth Radio                             | 58        | 0.8%    |
| Lite-On Bluetooth Device                            | 54        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 50        | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 49        | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 45        | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 44        | 0.61%   |
| IMC Networks Bluetooth Device                       | 42        | 0.58%   |
| Apple Bluetooth USB Host Controller                 | 42        | 0.58%   |
| MediaTek Wireless_Device                            | 41        | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 30        | 0.41%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.34%   |
| TP-Link UB500 Adapter                               | 24        | 0.33%   |
| Realtek RTL8723B Bluetooth                          | 23        | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite        | 23        | 0.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 7151      | 47.64%  |
| AMD                         | 3252      | 21.66%  |
| Nvidia                      | 2474      | 16.48%  |
| C-Media Electronics         | 303       | 2.02%   |
| Logitech                    | 167       | 1.11%   |
| Lenovo                      | 114       | 0.76%   |
| Realtek Semiconductor       | 103       | 0.69%   |
| GN Netcom                   | 83        | 0.55%   |
| Creative Labs               | 73        | 0.49%   |
| JMTek                       | 71        | 0.47%   |
| Kingston Technology         | 63        | 0.42%   |
| Texas Instruments           | 62        | 0.41%   |
| Plantronics                 | 62        | 0.41%   |
| SteelSeries ApS             | 59        | 0.39%   |
| Creative Technology         | 58        | 0.39%   |
| Corsair                     | 58        | 0.39%   |
| Razer USA                   | 53        | 0.35%   |
| Focusrite-Novation          | 51        | 0.34%   |
| Generalplus Technology      | 41        | 0.27%   |
| Blue Microphones            | 33        | 0.22%   |
| ASUSTek Computer            | 33        | 0.22%   |
| Hewlett-Packard             | 30        | 0.2%    |
| Samson Technologies         | 27        | 0.18%   |
| Sony                        | 26        | 0.17%   |
| GYROCOM C&C                 | 25        | 0.17%   |
| RODE Microphones            | 21        | 0.14%   |
| XMOS                        | 19        | 0.13%   |
| Dell                        | 19        | 0.13%   |
| Sennheiser Communications   | 17        | 0.11%   |
| Apple                       | 17        | 0.11%   |
| Tenx Technology             | 15        | 0.1%    |
| Cambridge Silicon Radio     | 15        | 0.1%    |
| SAVITECH                    | 13        | 0.09%   |
| PreSonus Audio Electronics  | 12        | 0.08%   |
| Micro Star International    | 12        | 0.08%   |
| Giga-Byte Technology        | 12        | 0.08%   |
| Conexant Systems            | 12        | 0.08%   |
| M-Audio                     | 11        | 0.07%   |
| FiiO Electronics Technology | 11        | 0.07%   |
| Yamaha                      | 10        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1273      | 7.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 1177      | 6.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 693       | 3.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 588       | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 579       | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 494       | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 468       | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 461       | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 456       | 2.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 390       | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 344       | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 343       | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 331       | 1.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 318       | 1.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 303       | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                               | 279       | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 276       | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 239       | 1.32%   |
| Intel 8 Series HD Audio Controller                                         | 239       | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 230       | 1.28%   |
| Intel 200 Series PCH HD Audio                                              | 225       | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 221       | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 218       | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 211       | 1.17%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 200       | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 198       | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 188       | 1.04%   |
| AMD FCH Azalia Controller                                                  | 180       | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 176       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                     | 165       | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 154       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 154       | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 150       | 0.83%   |
| Intel CM238 HD Audio Controller                                            | 148       | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 147       | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 138       | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 130       | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 120       | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 113       | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 110       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1420      | 23.09%  |
| SK hynix            | 1107      | 18%     |
| Micron Technology   | 713       | 11.59%  |
| Kingston            | 707       | 11.49%  |
| Unknown             | 423       | 6.88%   |
| Crucial             | 380       | 6.18%   |
| Corsair             | 376       | 6.11%   |
| G.Skill             | 260       | 4.23%   |
| A-DATA Technology   | 132       | 2.15%   |
| Ramaxel Technology  | 112       | 1.82%   |
| Team                | 57        | 0.93%   |
| Patriot             | 51        | 0.83%   |
| Elpida              | 48        | 0.78%   |
| Unknown (ABCD)      | 38        | 0.62%   |
| Smart               | 36        | 0.59%   |
| Nanya Technology    | 32        | 0.52%   |
| Unknown             | 24        | 0.39%   |
| GOODRAM             | 19        | 0.31%   |
| Transcend           | 15        | 0.24%   |
| Avant               | 12        | 0.2%    |
| Teikon              | 11        | 0.18%   |
| Smart Brazil        | 11        | 0.18%   |
| Silicon Power       | 9         | 0.15%   |
| PNY                 | 8         | 0.13%   |
| GeIL                | 8         | 0.13%   |
| AMD                 | 8         | 0.13%   |
| Goldkey             | 7         | 0.11%   |
| Apacer              | 7         | 0.11%   |
| Qimonda             | 6         | 0.1%    |
| CSX                 | 5         | 0.08%   |
| Timetec             | 4         | 0.07%   |
| Qumo                | 4         | 0.07%   |
| PUSKILL             | 4         | 0.07%   |
| Kllisre             | 4         | 0.07%   |
| Unifosa             | 3         | 0.05%   |
| Sesame              | 3         | 0.05%   |
| OnBoard             | 3         | 0.05%   |
| Micron/Elpida       | 3         | 0.05%   |
| Golden Empire       | 3         | 0.05%   |
| Gold Key            | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 76        | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 75        | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 62        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 53        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 41        | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 40        | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 34        | 0.52%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 34        | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.49%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 31        | 0.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 30        | 0.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 29        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 29        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 27        | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 27        | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 26        | 0.4%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 26        | 0.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 25        | 0.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 24        | 0.37%   |
| Unknown                                                          | 24        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 23        | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 23        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 22        | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 22        | 0.34%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 3039      | 57.48%  |
| DDR3    | 1378      | 26.06%  |
| LPDDR3  | 238       | 4.5%    |
| LPDDR4  | 237       | 4.48%   |
| DDR2    | 105       | 1.99%   |
| Unknown | 100       | 1.89%   |
| DDR5    | 68        | 1.29%   |
| SDRAM   | 55        | 1.04%   |
| LPDDR5  | 53        | 1%      |
| DDR     | 13        | 0.25%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3061      | 57.45%  |
| DIMM         | 1605      | 30.12%  |
| Row Of Chips | 583       | 10.94%  |
| Chip         | 54        | 1.01%   |
| Unknown      | 13        | 0.24%   |
| RIMM         | 8         | 0.15%   |
| FB-DIMM      | 4         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2433      | 42.63%  |
| 4096   | 1412      | 24.74%  |
| 16384  | 1072      | 18.78%  |
| 2048   | 469       | 8.22%   |
| 32768  | 227       | 3.98%   |
| 1024   | 83        | 1.45%   |
| 512    | 5         | 0.09%   |
| 3072   | 2         | 0.04%   |
| 129408 | 1         | 0.02%   |
| 32767  | 1         | 0.02%   |
| 256    | 1         | 0.02%   |
| 64     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 1089      | 19.11%  |
| 2667    | 1006      | 17.65%  |
| 1600    | 913       | 16.02%  |
| 2400    | 442       | 7.75%   |
| 2133    | 381       | 6.68%   |
| 1333    | 278       | 4.88%   |
| 3600    | 172       | 3.02%   |
| 1867    | 142       | 2.49%   |
| 4267    | 122       | 2.14%   |
| 1334    | 102       | 1.79%   |
| 3266    | 77        | 1.35%   |
| 800     | 68        | 1.19%   |
| 667     | 66        | 1.16%   |
| 4800    | 61        | 1.07%   |
| Unknown | 56        | 0.98%   |
| 6400    | 55        | 0.96%   |
| 3400    | 53        | 0.93%   |
| 3000    | 49        | 0.86%   |
| 1067    | 49        | 0.86%   |
| 3466    | 47        | 0.82%   |
| 1066    | 47        | 0.82%   |
| 3733    | 43        | 0.75%   |
| 2666    | 32        | 0.56%   |
| 3800    | 28        | 0.49%   |
| 8400    | 25        | 0.44%   |
| 4266    | 25        | 0.44%   |
| 1866    | 25        | 0.44%   |
| 3866    | 24        | 0.42%   |
| 2933    | 24        | 0.42%   |
| 2800    | 22        | 0.39%   |
| 4199    | 15        | 0.26%   |
| 1800    | 15        | 0.26%   |
| 3666    | 13        | 0.23%   |
| 3333    | 8         | 0.14%   |
| 3100    | 8         | 0.14%   |
| 533     | 8         | 0.14%   |
| 5200    | 7         | 0.12%   |
| 2000    | 6         | 0.11%   |
| 3334    | 5         | 0.09%   |
| 2733    | 5         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 73        | 35.44%  |
| Brother Industries    | 47        | 22.82%  |
| Canon                 | 28        | 13.59%  |
| Samsung Electronics   | 18        | 8.74%   |
| Seiko Epson           | 15        | 7.28%   |
| Prolific Technology   | 7         | 3.4%    |
| Lexmark International | 4         | 1.94%   |
| Xerox                 | 2         | 0.97%   |
| Kyocera               | 2         | 0.97%   |
| Star Micronics        | 1         | 0.49%   |
| Ricoh                 | 1         | 0.49%   |
| QinHeng Electronics   | 1         | 0.49%   |
| Pantum                | 1         | 0.49%   |
| NXP Semiconductors    | 1         | 0.49%   |
| MiiiW                 | 1         | 0.49%   |
| Graphtec America      | 1         | 0.49%   |
| Dymo-CoStar           | 1         | 0.49%   |
| Dell                  | 1         | 0.49%   |
| Boca Systems          | 1         | 0.49%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                | 7         | 3.38%   |
| Samsung M2070 Series                         | 5         | 2.42%   |
| HP LaserJet Professional P 1102w             | 4         | 1.93%   |
| Brother Printer                              | 4         | 1.93%   |
| Brother HL-L2340D series                     | 4         | 1.93%   |
| Seiko Epson Printer                          | 3         | 1.45%   |
| HP ENVY 5000 series                          | 3         | 1.45%   |
| HP ENVY 4520 series                          | 3         | 1.45%   |
| HP DeskJet F300 series                       | 3         | 1.45%   |
| HP DeskJet 3630 series                       | 3         | 1.45%   |
| HP DeskJet 2130 series                       | 3         | 1.45%   |
| Brother HL-2030 Laser Printer                | 3         | 1.45%   |
| Brother HL-1110 series                       | 3         | 1.45%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.97%   |
| HP OfficeJet 6950                            | 2         | 0.97%   |
| HP DeskJet 3700 series                       | 2         | 0.97%   |
| HP Deskjet 3510 series                       | 2         | 0.97%   |
| HP DeskJet 2600 series                       | 2         | 0.97%   |
| Canon TS3300 series                          | 2         | 0.97%   |
| Canon TR4500 series                          | 2         | 0.97%   |
| Canon CanoScan LiDE 300                      | 2         | 0.97%   |
| Brother MFC-9330CDW                          | 2         | 0.97%   |
| Brother HL-5250DN Printer                    | 2         | 0.97%   |
| Brother HL-2230 series                       | 2         | 0.97%   |
| Xerox Phaser 6500DN                          | 1         | 0.48%   |
| Xerox Phaser 3010                            | 1         | 0.48%   |
| Star Micronics TUP592 (STR_T-001)            | 1         | 0.48%   |
| Seiko Epson XP-100 Series                    | 1         | 0.48%   |
| Seiko Epson WP-4020 Series                   | 1         | 0.48%   |
| Seiko Epson WF-2860 Series                   | 1         | 0.48%   |
| Seiko Epson WF-2830 Series                   | 1         | 0.48%   |
| Seiko Epson WF-2510 Series                   | 1         | 0.48%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.48%   |
| Seiko Epson L3110 Series                     | 1         | 0.48%   |
| Seiko Epson L300 Series                      | 1         | 0.48%   |
| Seiko Epson L220 Series                      | 1         | 0.48%   |
| Seiko Epson L200 Series                      | 1         | 0.48%   |
| Seiko Epson L100 Series                      | 1         | 0.48%   |
| Seiko Epson ET-2710 Series                   | 1         | 0.48%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1         | 0.48%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 29        | 53.7%   |
| Seiko Epson     | 18        | 33.33%  |
| Hewlett-Packard | 5         | 9.26%   |
| UMAX            | 1         | 1.85%   |
| Mustek Systems  | 1         | 1.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 6         | 11.11%  |
| Canon CanoScan LiDE 220                                  | 5         | 9.26%   |
| Canon CanoScan LiDE 210                                  | 5         | 9.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 4         | 7.41%   |
| Canon CanoScan LIDE 25                                   | 3         | 5.56%   |
| Canon CanoScan LiDE 110                                  | 3         | 5.56%   |
| Canon CanoScan LiDE 100                                  | 3         | 5.56%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 2         | 3.7%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 2         | 3.7%    |
| Seiko Epson GT-6600U [Perfection 610]                    | 2         | 3.7%    |
| UMAX Astra 2200/2200SU                                   | 1         | 1.85%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]         | 1         | 1.85%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1         | 1.85%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1         | 1.85%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 1.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 1.85%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 1.85%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1         | 1.85%   |
| HP ScanJet G4050                                         | 1         | 1.85%   |
| HP ScanJet 5590                                          | 1         | 1.85%   |
| HP ScanJet 3400cse                                       | 1         | 1.85%   |
| HP Scanjet 300                                           | 1         | 1.85%   |
| HP ScanJet 2400c                                         | 1         | 1.85%   |
| Canon CanoScan N650U/N656U                               | 1         | 1.85%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 1.85%   |
| Canon CanoScan LiDE 70                                   | 1         | 1.85%   |
| Canon CanoScan LiDE 200                                  | 1         | 1.85%   |
| Canon CanoScan LiDE 120                                  | 1         | 1.85%   |
| Canon CanoScan 4400F                                     | 1         | 1.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1522      | 21.58%  |
| IMC Networks                           | 744       | 10.55%  |
| Microdia                               | 587       | 8.32%   |
| Logitech                               | 564       | 8%      |
| Realtek Semiconductor                  | 549       | 7.78%   |
| Acer                                   | 504       | 7.15%   |
| Quanta                                 | 355       | 5.03%   |
| Sunplus Innovation Technology          | 337       | 4.78%   |
| Cheng Uei Precision Industry (Foxlink) | 249       | 3.53%   |
| Apple                                  | 202       | 2.86%   |
| Syntek                                 | 188       | 2.67%   |
| Lite-On Technology                     | 182       | 2.58%   |
| Luxvisions Innotech Limited            | 112       | 1.59%   |
| Microsoft                              | 101       | 1.43%   |
| Suyin                                  | 93        | 1.32%   |
| Silicon Motion                         | 71        | 1.01%   |
| Samsung Electronics                    | 69        | 0.98%   |
| Bison Electronics                      | 64        | 0.91%   |
| Alcor Micro                            | 47        | 0.67%   |
| Ricoh                                  | 34        | 0.48%   |
| Sonix Technology                       | 30        | 0.43%   |
| Lenovo                                 | 27        | 0.38%   |
| KYE Systems (Mouse Systems)            | 27        | 0.38%   |
| Z-Star Microelectronics                | 22        | 0.31%   |
| Generalplus Technology                 | 21        | 0.3%    |
| Primax Electronics                     | 20        | 0.28%   |
| SunplusIT                              | 18        | 0.26%   |
| Creative Technology                    | 18        | 0.26%   |
| ARC International                      | 18        | 0.26%   |
| MacroSilicon                           | 14        | 0.2%    |
| Importek                               | 14        | 0.2%    |
| Cubeternet                             | 12        | 0.17%   |
| Razer USA                              | 11        | 0.16%   |
| Jieli Technology                       | 11        | 0.16%   |
| webcam                                 | 10        | 0.14%   |
| Intel                                  | 10        | 0.14%   |
| Hewlett-Packard                        | 10        | 0.14%   |
| USB Camera                             | 8         | 0.11%   |
| AVerMedia Technologies                 | 8         | 0.11%   |
| LG Electronics                         | 7         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 535       | 7.48%   |
| Microdia Integrated_Webcam_HD                       | 305       | 4.27%   |
| IMC Networks Integrated Camera                      | 303       | 4.24%   |
| Realtek Integrated_Webcam_HD                        | 245       | 3.43%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 192       | 2.69%   |
| Acer Integrated Camera                              | 150       | 2.1%    |
| Chicony HD WebCam                                   | 141       | 1.97%   |
| Sunplus Integrated_Webcam_HD                        | 135       | 1.89%   |
| Syntek Integrated Camera                            | 130       | 1.82%   |
| Logitech HD Pro Webcam C920                         | 128       | 1.79%   |
| Logitech Webcam C270                                | 122       | 1.71%   |
| Chicony Integrated Camera (1280x720@30)             | 82        | 1.15%   |
| Lite-On Integrated Camera                           | 79        | 1.1%    |
| Quanta HD User Facing                               | 71        | 0.99%   |
| Samsung Galaxy A5 (MTP)                             | 68        | 0.95%   |
| Chicony HP HD Camera                                | 68        | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 68        | 0.95%   |
| Acer SunplusIT Integrated Camera                    | 60        | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                 | 56        | 0.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 55        | 0.77%   |
| Chicony HP Wide Vision HD Camera                    | 53        | 0.74%   |
| Acer Lenovo EasyCamera                              | 53        | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 49        | 0.69%   |
| Apple Built-in iSight                               | 45        | 0.63%   |
| IMC Networks HD Camera                              | 44        | 0.62%   |
| Quanta HP HD Camera                                 | 43        | 0.6%    |
| Chicony USB2.0 Camera                               | 43        | 0.6%    |
| Acer HD Webcam                                      | 43        | 0.6%    |
| Logitech C922 Pro Stream Webcam                     | 42        | 0.59%   |
| Microdia Integrated Webcam                          | 41        | 0.57%   |
| Lite-On HP HD Camera                                | 38        | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 38        | 0.53%   |
| Realtek USB Camera                                  | 37        | 0.52%   |
| Chicony Integrated IR Camera                        | 37        | 0.52%   |
| Acer EasyCamera                                     | 37        | 0.52%   |
| Chicony EasyCamera                                  | 35        | 0.49%   |
| Bison Integrated Camera                             | 35        | 0.49%   |
| Microdia Webcam Vitade AF                           | 34        | 0.48%   |
| Chicony HP TrueVision HD Camera                     | 34        | 0.48%   |
| Realtek Integrated Webcam                           | 33        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 674       | 39.48%  |
| Validity Sensors                   | 484       | 28.35%  |
| Shenzhen Goodix Technology         | 281       | 16.46%  |
| Elan Microelectronics              | 98        | 5.74%   |
| LighTuning Technology              | 56        | 3.28%   |
| Upek                               | 55        | 3.22%   |
| AuthenTec                          | 32        | 1.87%   |
| Samsung Electronics                | 10        | 0.59%   |
| STMicroelectronics                 | 4         | 0.23%   |
| Focal-systems.Corp                 | 4         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.18%   |
| DigitalPersona                     | 3         | 0.18%   |
| Dell                               | 2         | 0.12%   |
| Microsoft                          | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 272       | 15.93%  |
| Shenzhen Goodix  Fingerprint Device                                        | 143       | 8.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 101       | 5.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 89        | 5.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 85        | 4.98%   |
| Shenzhen Goodix Fingerprint Reader                                         | 84        | 4.92%   |
| Validity Sensors Synaptics WBDI                                            | 63        | 3.69%   |
| Elan ELAN:Fingerprint                                                      | 60        | 3.51%   |
| Synaptics  WBDI                                                            | 56        | 3.28%   |
| Shenzhen Goodix FingerPrint                                                | 54        | 3.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 53        | 3.1%    |
| Synaptics WBDI                                                             | 48        | 2.81%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 45        | 2.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 41        | 2.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 40        | 2.34%   |
| Synaptics UWP WBDI                                                         | 40        | 2.34%   |
| Elan ELAN:ARM-M4                                                           | 35        | 2.05%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 29        | 1.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 29        | 1.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 28        | 1.64%   |
| Validity Sensors VFS491                                                    | 25        | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 23        | 1.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 21        | 1.23%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 1%      |
| Synaptics UWP WBDI Device                                                  | 17        | 1%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1%      |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 0.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 15        | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 14        | 0.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.64%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.47%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 7         | 0.41%   |
| Samsung Fingerprint Device                                                 | 7         | 0.41%   |
| AuthenTec AES2810                                                          | 7         | 0.41%   |
| Unknown                                                                    | 7         | 0.41%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.35%   |
| Synaptics WBDI Device                                                      | 6         | 0.35%   |
| LighTuning Fingerprint Sensor                                              | 6         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 247       | 40.69%  |
| Broadcom                          | 226       | 37.23%  |
| Upek                              | 36        | 5.93%   |
| Lenovo                            | 30        | 4.94%   |
| O2 Micro                          | 12        | 1.98%   |
| Gemalto (was Gemplus)             | 8         | 1.32%   |
| Yubico.com                        | 7         | 1.15%   |
| SCM Microsystems                  | 7         | 1.15%   |
| OmniKey                           | 7         | 1.15%   |
| Realtek Semiconductor             | 6         | 0.99%   |
| VASCO Data Security International | 3         | 0.49%   |
| Aladdin Knowledge Systems         | 3         | 0.49%   |
| Reiner SCT Kartensysteme          | 2         | 0.33%   |
| Chicony Electronics               | 2         | 0.33%   |
| Aktiv                             | 2         | 0.33%   |
| Advanced Card Systems             | 2         | 0.33%   |
| Purism, SPC                       | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Fujitsu Siemens Computers         | 1         | 0.16%   |
| Feitian Technologies              | 1         | 0.16%   |
| Clay Logic                        | 1         | 0.16%   |
| Cherry                            | 1         | 0.16%   |
| Athena Smartcard Solutions        | 1         | 0.16%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 244       | 40.2%   |
| Broadcom 5880                                                                | 75        | 12.36%  |
| Broadcom 58200                                                               | 61        | 10.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 52        | 8.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 5.93%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 5.93%   |
| Lenovo Integrated Smart Card Reader                                          | 29        | 4.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 1.48%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 0.99%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 0.82%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.82%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 0.66%   |
| OmniKey CardMan 1021                                                         | 3         | 0.49%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.49%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.49%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.49%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.33%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.33%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.33%   |
| Aktiv Rutoken lite                                                           | 2         | 0.33%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.16%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.16%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.16%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.16%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.16%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.16%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.16%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.16%   |
| Purism, SPC Librem Key                                                       | 1         | 0.16%   |
| OmniKey CardMan 4321                                                         | 1         | 0.16%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.16%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.16%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.16%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.16%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.16%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.16%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.16%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.16%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7068      | 67.23%  |
| 1     | 2833      | 26.95%  |
| 2     | 502       | 4.78%   |
| 3     | 68        | 0.65%   |
| 4     | 17        | 0.16%   |
| 5     | 12        | 0.11%   |
| 6     | 6         | 0.06%   |
| 7     | 5         | 0.05%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1687      | 42.01%  |
| Graphics card            | 736       | 18.33%  |
| Net/wireless             | 397       | 9.89%   |
| Multimedia controller    | 379       | 9.44%   |
| Chipcard                 | 205       | 5.1%    |
| Camera                   | 151       | 3.76%   |
| Bluetooth                | 73        | 1.82%   |
| Communication controller | 72        | 1.79%   |
| Unassigned class         | 70        | 1.74%   |
| Sound                    | 56        | 1.39%   |
| Card reader              | 49        | 1.22%   |
| Storage                  | 46        | 1.15%   |
| Network                  | 33        | 0.82%   |
| Net/ethernet             | 23        | 0.57%   |
| Modem                    | 14        | 0.35%   |
| Storage/raid             | 12        | 0.3%    |
| Firewire controller      | 3         | 0.07%   |
| Dvb card                 | 3         | 0.07%   |
| Storage/ata              | 2         | 0.05%   |
| Flash memory             | 2         | 0.05%   |
| Wireless                 | 1         | 0.02%   |
| Video                    | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |

