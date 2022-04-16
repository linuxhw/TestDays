Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 128

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Modern 14 B4MW              | Notebook    | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6a9e2b3174](https://linux-hardware.org/?probe=6a9e2b3174) | Apr 16, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | Notebook    | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Unknown       | Unknown                     | Other       | [a786d1f74e](https://linux-hardware.org/?probe=a786d1f74e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [22a1a17a81](https://linux-hardware.org/?probe=22a1a17a81) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [abe538f1ed](https://linux-hardware.org/?probe=abe538f1ed) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [25ffe3d211](https://linux-hardware.org/?probe=25ffe3d211) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | Notebook    | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [d1b267f496](https://linux-hardware.org/?probe=d1b267f496) | Apr 13, 2022 |
| Unknown       | Unknown                     | Soc         | [43769378a7](https://linux-hardware.org/?probe=43769378a7) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1beed0e9b](https://linux-hardware.org/?probe=c1beed0e9b) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e5a9e99dbc](https://linux-hardware.org/?probe=e5a9e99dbc) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | Desktop     | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [8421f0505f](https://linux-hardware.org/?probe=8421f0505f) | Apr 13, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [33b4ba0b02](https://linux-hardware.org/?probe=33b4ba0b02) | Apr 13, 2022 |
| Dell          | 00NH4P A14                  | Server      | [274931609f](https://linux-hardware.org/?probe=274931609f) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [7349c76e13](https://linux-hardware.org/?probe=7349c76e13) | Apr 11, 2022 |
| Intel         | W7650                       | Notebook    | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | Notebook    | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [84927bf894](https://linux-hardware.org/?probe=84927bf894) | Apr 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5b861faffd](https://linux-hardware.org/?probe=5b861faffd) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| Biostar       | B550MH                      | Desktop     | [abd373497b](https://linux-hardware.org/?probe=abd373497b) | Apr 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [1a4b90c894](https://linux-hardware.org/?probe=1a4b90c894) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [92966a1240](https://linux-hardware.org/?probe=92966a1240) | Apr 06, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [45a343796d](https://linux-hardware.org/?probe=45a343796d) | Apr 06, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [f0472bcf0d](https://linux-hardware.org/?probe=f0472bcf0d) | Apr 05, 2022 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [9ee2f76c12](https://linux-hardware.org/?probe=9ee2f76c12) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1cc5b6fbc3](https://linux-hardware.org/?probe=1cc5b6fbc3) | Apr 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [718a7d42cc](https://linux-hardware.org/?probe=718a7d42cc) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | Notebook    | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [f7946783ea](https://linux-hardware.org/?probe=f7946783ea) | Mar 31, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | Notebook    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7879818528](https://linux-hardware.org/?probe=7879818528) | Mar 30, 2022 |
| HP            | EliteBook x360 830 G5       | Convertible | [d384ca307e](https://linux-hardware.org/?probe=d384ca307e) | Mar 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [fd1c735c98](https://linux-hardware.org/?probe=fd1c735c98) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [927252e84e](https://linux-hardware.org/?probe=927252e84e) | Mar 20, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [be2a3fd33b](https://linux-hardware.org/?probe=be2a3fd33b) | Mar 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [efdb29ff92](https://linux-hardware.org/?probe=efdb29ff92) | Mar 07, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0efde9a187](https://linux-hardware.org/?probe=0efde9a187) | Mar 03, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [841ab4ffe2](https://linux-hardware.org/?probe=841ab4ffe2) | Mar 01, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [809200ad60](https://linux-hardware.org/?probe=809200ad60) | Jan 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [f09a7c7125](https://linux-hardware.org/?probe=f09a7c7125) | Dec 06, 2021 |
| Lenovo        | ThinkPad 10 20C10027SP      | Tablet      | [1c4e6ab62b](https://linux-hardware.org/?probe=1c4e6ab62b) | Nov 29, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f1a1a21c56](https://linux-hardware.org/?probe=f1a1a21c56) | Oct 26, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a072a33607](https://linux-hardware.org/?probe=a072a33607) | Oct 12, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | Notebook    | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [bcf7dcdd2c](https://linux-hardware.org/?probe=bcf7dcdd2c) | Oct 09, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [0b3691d096](https://linux-hardware.org/?probe=0b3691d096) | Oct 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [95229554a9](https://linux-hardware.org/?probe=95229554a9) | Sep 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [d235dcf0d1](https://linux-hardware.org/?probe=d235dcf0d1) | Sep 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ad5f2b8ea5](https://linux-hardware.org/?probe=ad5f2b8ea5) | Sep 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f191342fa8](https://linux-hardware.org/?probe=f191342fa8) | Sep 02, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [270961aa02](https://linux-hardware.org/?probe=270961aa02) | Aug 30, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [1257d6c6f4](https://linux-hardware.org/?probe=1257d6c6f4) | Aug 27, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [373f7e6861](https://linux-hardware.org/?probe=373f7e6861) | Aug 22, 2021 |
| HP            | 304Ah                       | Desktop     | [047d1b0887](https://linux-hardware.org/?probe=047d1b0887) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 29        | 30.21%  |
| 5.17.2-300.fc36.x86_64                                        | 23        | 23.96%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 15        | 15.63%  |
| 5.17.0-300.fc36.x86_64                                        | 4         | 4.17%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 4         | 4.17%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 2         | 2.08%   |
| 5.14.0-0.rc5.20210813gitf8e6dfc64f61.46.fc36.x86_64           | 2         | 2.08%   |
| 5.17.3-300.fc36.aarch64                                       | 1         | 1.04%   |
| 5.17.2-300.fc36.aarch64                                       | 1         | 1.04%   |
| 5.17.1-xanmod1                                                | 1         | 1.04%   |
| 5.17.0-0.rc0.20220112gitdaadb3bd0e8d.63.fc36.x86_64           | 1         | 1.04%   |
| 5.16.9-200.fc35.x86_64                                        | 1         | 1.04%   |
| 5.16.17-200.fc35.x86_64                                       | 1         | 1.04%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 1.04%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 1.04%   |
| 5.16.0-0.rc2.20211126gita4849f6000e2.21.fc36.x86_64           | 1         | 1.04%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 1.04%   |
| 5.15.0-0.rc6.47.fc36.x86_64                                   | 1         | 1.04%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.vanilla.1.fc36.x86_64 | 1         | 1.04%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 1.04%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 1.04%   |
| 5.15.0-0.rc0.20210831gitb91db6a0b52e.1.fc36.x86_64            | 1         | 1.04%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 1.04%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 30        | 31.58%  |
| 5.17.2  | 24        | 25.26%  |
| 5.17.0  | 24        | 25.26%  |
| 5.15.0  | 7         | 7.37%   |
| 5.16.0  | 2         | 2.11%   |
| 5.14.0  | 2         | 2.11%   |
| 5.17.3  | 1         | 1.05%   |
| 5.16.9  | 1         | 1.05%   |
| 5.16.17 | 1         | 1.05%   |
| 5.16.16 | 1         | 1.05%   |
| 5.14.14 | 1         | 1.05%   |
| 5.14.10 | 1         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17    | 77        | 82.8%   |
| 5.15    | 7         | 7.53%   |
| 5.16    | 5         | 5.38%   |
| 5.14    | 4         | 4.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 89        | 97.8%   |
| aarch64 | 2         | 2.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 78        | 84.78%  |
| Unknown | 7         | 7.61%   |
| KDE5    | 6         | 6.52%   |
| i3      | 1         | 1.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 73        | 80.22%  |
| X11     | 11        | 12.09%  |
| Tty     | 4         | 4.4%    |
| Unknown | 3         | 3.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 50        | 54.95%  |
| Unknown | 33        | 36.26%  |
| SDDM    | 6         | 6.59%   |
| LightDM | 2         | 2.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 49        | 53.85%  |
| en_GB | 9         | 9.89%   |
| ru_RU | 4         | 4.4%    |
| pl_PL | 4         | 4.4%    |
| de_DE | 4         | 4.4%    |
| pt_BR | 3         | 3.3%    |
| fr_FR | 3         | 3.3%    |
| es_ES | 3         | 3.3%    |
| cs_CZ | 2         | 2.2%    |
| pt_PT | 1         | 1.1%    |
| it_IT | 1         | 1.1%    |
| hu_HU | 1         | 1.1%    |
| hr_HR | 1         | 1.1%    |
| fi_FI | 1         | 1.1%    |
| es_UY | 1         | 1.1%    |
| es_CO | 1         | 1.1%    |
| es_AR | 1         | 1.1%    |
| en_CA | 1         | 1.1%    |
| C     | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 78        | 85.71%  |
| BIOS | 13        | 14.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 63        | 69.23%  |
| Ext4  | 22        | 24.18%  |
| Xfs   | 6         | 6.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 55        | 59.78%  |
| Unknown | 31        | 33.7%   |
| MBR     | 6         | 6.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 79.12%  |
| Yes       | 19        | 20.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 62.64%  |
| Yes       | 34        | 37.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 21        | 23.08%  |
| Gigabyte Technology    | 14        | 15.38%  |
| Dell                   | 13        | 14.29%  |
| MSI                    | 9         | 9.89%   |
| Hewlett-Packard        | 8         | 8.79%   |
| ASUSTek Computer       | 6         | 6.59%   |
| Acer                   | 4         | 4.4%    |
| Unknown                | 3         | 3.3%    |
| Biostar                | 2         | 2.2%    |
| VALE                   | 1         | 1.1%    |
| Toshiba                | 1         | 1.1%    |
| Sony                   | 1         | 1.1%    |
| Positivo               | 1         | 1.1%    |
| Notebook               | 1         | 1.1%    |
| Microsoft              | 1         | 1.1%    |
| Intel                  | 1         | 1.1%    |
| Framework              | 1         | 1.1%    |
| Chuwi                  | 1         | 1.1%    |
| Avell High Performance | 1         | 1.1%    |
| Apple                  | 1         | 1.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Unknown                                         | 3         | 3.3%    |
| Gigabyte B450 AORUS M                           | 2         | 2.2%    |
| VALE Notebook Slim S132                         | 1         | 1.1%    |
| Toshiba Satellite U840                          | 1         | 1.1%    |
| Sony VGN-FW21E                                  | 1         | 1.1%    |
| Positivo CHT12CP                                | 1         | 1.1%    |
| Notebook PCx0Dx                                 | 1         | 1.1%    |
| MSI Prestige 14Evo A11M                         | 1         | 1.1%    |
| MSI MS-7D06                                     | 1         | 1.1%    |
| MSI MS-7C95                                     | 1         | 1.1%    |
| MSI MS-7A38                                     | 1         | 1.1%    |
| MSI MS-7968                                     | 1         | 1.1%    |
| MSI MS-7792                                     | 1         | 1.1%    |
| MSI MS-7721                                     | 1         | 1.1%    |
| MSI Modern 14 B4MW                              | 1         | 1.1%    |
| MSI GS66 Stealth 10UH                           | 1         | 1.1%    |
| Microsoft Surface Pro                           | 1         | 1.1%    |
| Lenovo Yoga 6 13ALC6 82ND                       | 1         | 1.1%    |
| Lenovo ThinkPad X260 20F5S0HK1J                 | 1         | 1.1%    |
| Lenovo ThinkPad X12 Detachable Gen 1 20UW0013US | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00        | 1         | 1.1%    |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S0P        | 1         | 1.1%    |
| Lenovo ThinkPad T495 20NJ000XIX                 | 1         | 1.1%    |
| Lenovo ThinkPad P15 Gen 1 20STS0J500            | 1         | 1.1%    |
| Lenovo ThinkPad P14s Gen 1 20Y1000SUK           | 1         | 1.1%    |
| Lenovo ThinkPad L14 Gen 2 20X10044EQ            | 1         | 1.1%    |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00            | 1         | 1.1%    |
| Lenovo ThinkPad 10 20C10027SP                   | 1         | 1.1%    |
| Lenovo ThinkBook 15 G2 ITL 20VE                 | 1         | 1.1%    |
| Lenovo ThinkBook 14 G3 ACL 21A2                 | 1         | 1.1%    |
| Lenovo ThinkBook 13s G3 ACN 20YA                | 1         | 1.1%    |
| Lenovo Legion Y540-15IRH 81SX                   | 1         | 1.1%    |
| Lenovo IdeaPadFlex 14 20308                     | 1         | 1.1%    |
| Lenovo IdeaPad Yoga 13 20175                    | 1         | 1.1%    |
| Lenovo IdeaPad L340-15IRH Gaming 81TR           | 1         | 1.1%    |
| Lenovo IdeaPad 530S-14IKB 81EU                  | 1         | 1.1%    |
| Lenovo IdeaPad 530S-14ARR 81H1                  | 1         | 1.1%    |
| Lenovo IdeaPad 320S-13IKB 81AK                  | 1         | 1.1%    |
| Intel NUC8i7HVK                                 | 1         | 1.1%    |
| HP ZBook Fury 15 G7 Mobile Workstation          | 1         | 1.1%    |
| HP ProBook 4740s                                | 1         | 1.1%    |
| HP ProBook 455 G8 Notebook PC                   | 1         | 1.1%    |
| HP Pavilion 15                                  | 1         | 1.1%    |
| HP Laptop 15-dw3xxx                             | 1         | 1.1%    |
| HP ENVY x360 Convertible 15-cp0xxx              | 1         | 1.1%    |
| HP EliteBook x360 830 G5                        | 1         | 1.1%    |
| HP Compaq 8100 Elite SFF PC                     | 1         | 1.1%    |
| Gigabyte Z490 UD                                | 1         | 1.1%    |
| Gigabyte Z170N-Gaming 5                         | 1         | 1.1%    |
| Gigabyte Z170MX-Gaming 5                        | 1         | 1.1%    |
| Gigabyte Z170-D3H                               | 1         | 1.1%    |
| Gigabyte H81M-S2H                               | 1         | 1.1%    |
| Gigabyte H370M-DS3H                             | 1         | 1.1%    |
| Gigabyte H110M-H                                | 1         | 1.1%    |
| Gigabyte EP45-DS3L                              | 1         | 1.1%    |
| Gigabyte B85M-D3V-A                             | 1         | 1.1%    |
| Gigabyte B550I AORUS PRO AX                     | 1         | 1.1%    |
| Gigabyte B550 AORUS ELITE                       | 1         | 1.1%    |
| Gigabyte 970A-DS3P                              | 1         | 1.1%    |
| Framework Laptop                                | 1         | 1.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 10        | 10.99%  |
| Lenovo IdeaPad              | 5         | 5.49%   |
| Dell XPS                    | 5         | 5.49%   |
| Lenovo ThinkBook            | 3         | 3.3%    |
| Dell Inspiron               | 3         | 3.3%    |
| Unknown                     | 3         | 3.3%    |
| HP ProBook                  | 2         | 2.2%    |
| Gigabyte B450               | 2         | 2.2%    |
| Dell Precision              | 2         | 2.2%    |
| ASUS VivoBook               | 2         | 2.2%    |
| Acer Swift                  | 2         | 2.2%    |
| Acer Aspire                 | 2         | 2.2%    |
| VALE Notebook               | 1         | 1.1%    |
| Toshiba Satellite           | 1         | 1.1%    |
| Sony VGN-FW21E              | 1         | 1.1%    |
| Positivo CHT12CP            | 1         | 1.1%    |
| Notebook PCx0Dx             | 1         | 1.1%    |
| MSI Prestige                | 1         | 1.1%    |
| MSI MS-7D06                 | 1         | 1.1%    |
| MSI MS-7C95                 | 1         | 1.1%    |
| MSI MS-7A38                 | 1         | 1.1%    |
| MSI MS-7968                 | 1         | 1.1%    |
| MSI MS-7792                 | 1         | 1.1%    |
| MSI MS-7721                 | 1         | 1.1%    |
| MSI Modern                  | 1         | 1.1%    |
| MSI GS66                    | 1         | 1.1%    |
| Microsoft Surface           | 1         | 1.1%    |
| Lenovo Yoga                 | 1         | 1.1%    |
| Lenovo Legion               | 1         | 1.1%    |
| Lenovo IdeaPadFlex          | 1         | 1.1%    |
| Intel NUC8i7HVK             | 1         | 1.1%    |
| HP ZBook                    | 1         | 1.1%    |
| HP Pavilion                 | 1         | 1.1%    |
| HP Laptop                   | 1         | 1.1%    |
| HP ENVY                     | 1         | 1.1%    |
| HP EliteBook                | 1         | 1.1%    |
| HP Compaq                   | 1         | 1.1%    |
| Gigabyte Z490               | 1         | 1.1%    |
| Gigabyte Z170N-Gaming       | 1         | 1.1%    |
| Gigabyte Z170MX-Gaming      | 1         | 1.1%    |
| Gigabyte Z170-D3H           | 1         | 1.1%    |
| Gigabyte H81M-S2H           | 1         | 1.1%    |
| Gigabyte H370M-DS3H         | 1         | 1.1%    |
| Gigabyte H110M-H            | 1         | 1.1%    |
| Gigabyte EP45-DS3L          | 1         | 1.1%    |
| Gigabyte B85M-D3V-A         | 1         | 1.1%    |
| Gigabyte B550I              | 1         | 1.1%    |
| Gigabyte B550               | 1         | 1.1%    |
| Gigabyte 970A-DS3P          | 1         | 1.1%    |
| Framework Laptop            | 1         | 1.1%    |
| Dell Studio                 | 1         | 1.1%    |
| Dell PowerEdge              | 1         | 1.1%    |
| Dell OptiPlex               | 1         | 1.1%    |
| Chuwi Hi10                  | 1         | 1.1%    |
| Biostar H55                 | 1         | 1.1%    |
| Biostar B550MH              | 1         | 1.1%    |
| Avell High Performance B.ON | 1         | 1.1%    |
| ASUS TUF                    | 1         | 1.1%    |
| ASUS ROG                    | 1         | 1.1%    |
| ASUS P8P67                  | 1         | 1.1%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 20.88%  |
| 2020    | 18        | 19.78%  |
| 2018    | 11        | 12.09%  |
| 2019    | 8         | 8.79%   |
| 2013    | 8         | 8.79%   |
| 2016    | 5         | 5.49%   |
| 2015    | 5         | 5.49%   |
| 2017    | 4         | 4.4%    |
| 2012    | 3         | 3.3%    |
| 2008    | 3         | 3.3%    |
| 2014    | 2         | 2.2%    |
| 2022    | 1         | 1.1%    |
| 2011    | 1         | 1.1%    |
| 2010    | 1         | 1.1%    |
| 2009    | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 49        | 53.85%  |
| Desktop        | 30        | 32.97%  |
| Convertible    | 4         | 4.4%    |
| Tablet         | 3         | 3.3%    |
| Other          | 1         | 1.1%    |
| System on chip | 1         | 1.1%    |
| Mini pc        | 1         | 1.1%    |
| All in one     | 1         | 1.1%    |
| Server         | 1         | 1.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 72        | 79.12%  |
| Enabled  | 19        | 20.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 23.08%  |
| 8.01-16.0   | 20        | 21.98%  |
| 4.01-8.0    | 19        | 20.88%  |
| 32.01-64.0  | 15        | 16.48%  |
| 3.01-4.0    | 9         | 9.89%   |
| 64.01-256.0 | 5         | 5.49%   |
| 24.01-32.0  | 1         | 1.1%    |
| 0.51-1.0    | 1         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 29        | 30.85%  |
| 4.01-8.0   | 26        | 27.66%  |
| 2.01-3.0   | 22        | 23.4%   |
| 1.01-2.0   | 8         | 8.51%   |
| 8.01-16.0  | 5         | 5.32%   |
| 0.51-1.0   | 2         | 2.13%   |
| 24.01-32.0 | 1         | 1.06%   |
| 0.01-0.5   | 1         | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 54.35%  |
| 2      | 22        | 23.91%  |
| 3      | 10        | 10.87%  |
| 4      | 7         | 7.61%   |
| 5      | 2         | 2.17%   |
| 7      | 1         | 1.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 81.32%  |
| Yes       | 17        | 18.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 69.23%  |
| No        | 28        | 30.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 81.32%  |
| No        | 17        | 18.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 68.13%  |
| No        | 29        | 31.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 19        | 20.88%  |
| UK           | 7         | 7.69%   |
| Brazil       | 6         | 6.59%   |
| Poland       | 5         | 5.49%   |
| Germany      | 5         | 5.49%   |
| Italy        | 4         | 4.4%    |
| France       | 4         | 4.4%    |
| Spain        | 3         | 3.3%    |
| Russia       | 3         | 3.3%    |
| Netherlands  | 3         | 3.3%    |
| Belarus      | 3         | 3.3%    |
| Sweden       | 2         | 2.2%    |
| Romania      | 2         | 2.2%    |
| Norway       | 2         | 2.2%    |
| Czechia      | 2         | 2.2%    |
| Uzbekistan   | 1         | 1.1%    |
| Turkey       | 1         | 1.1%    |
| Switzerland  | 1         | 1.1%    |
| Slovakia     | 1         | 1.1%    |
| Saudi Arabia | 1         | 1.1%    |
| Portugal     | 1         | 1.1%    |
| Nepal        | 1         | 1.1%    |
| Latvia       | 1         | 1.1%    |
| Indonesia    | 1         | 1.1%    |
| India        | 1         | 1.1%    |
| Iceland      | 1         | 1.1%    |
| Hungary      | 1         | 1.1%    |
| Finland      | 1         | 1.1%    |
| Estonia      | 1         | 1.1%    |
| Croatia      | 1         | 1.1%    |
| Colombia     | 1         | 1.1%    |
| Canada       | 1         | 1.1%    |
| Belgium      | 1         | 1.1%    |
| Bangladesh   | 1         | 1.1%    |
| Austria      | 1         | 1.1%    |
| Argentina    | 1         | 1.1%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 3         | 3.3%    |
| Sao Paulo                 | 3         | 3.3%    |
| Minsk                     | 3         | 3.3%    |
| Allen                     | 3         | 3.3%    |
| Moscow                    | 2         | 2.2%    |
| Halstead                  | 2         | 2.2%    |
| Folsom                    | 2         | 2.2%    |
| Zurich                    | 1         | 1.1%    |
| Zagreb                    | 1         | 1.1%    |
| Warrington                | 1         | 1.1%    |
| Vigodarzere               | 1         | 1.1%    |
| Vegarshei                 | 1         | 1.1%    |
| Vancouver                 | 1         | 1.1%    |
| Turku                     | 1         | 1.1%    |
| Tulsa                     | 1         | 1.1%    |
| Trzciel                   | 1         | 1.1%    |
| Trier                     | 1         | 1.1%    |
| TorrejÃ³n de Ardoz      | 1         | 1.1%    |
| Tashkent                  | 1         | 1.1%    |
| Tarragona                 | 1         | 1.1%    |
| Tallinn                   | 1         | 1.1%    |
| St Petersburg             | 1         | 1.1%    |
| Sollentuna                | 1         | 1.1%    |
| Solihull                  | 1         | 1.1%    |
| Soddy-Daisy               | 1         | 1.1%    |
| Scorrano                  | 1         | 1.1%    |
| San Antonio               | 1         | 1.1%    |
| Rozmital pod Tremsinem    | 1         | 1.1%    |
| Riga                      | 1         | 1.1%    |
| Reykjavik                 | 1         | 1.1%    |
| Princeton                 | 1         | 1.1%    |
| Porto                     | 1         | 1.1%    |
| Portland                  | 1         | 1.1%    |
| Paris                     | 1         | 1.1%    |
| Oslo                      | 1         | 1.1%    |
| Newport                   | 1         | 1.1%    |
| Mölten                   | 1         | 1.1%    |
| Milicz                    | 1         | 1.1%    |
| Meitingen                 | 1         | 1.1%    |
| Marseille                 | 1         | 1.1%    |
| Macaiba                   | 1         | 1.1%    |
| Lyme                      | 1         | 1.1%    |
| Liverpool                 | 1         | 1.1%    |
| Leiderdorp                | 1         | 1.1%    |
| Las Vegas                 | 1         | 1.1%    |
| Kathmandu                 | 1         | 1.1%    |
| Kasten bei Boeheimkirchen | 1         | 1.1%    |
| Kanne                     | 1         | 1.1%    |
| Joinville                 | 1         | 1.1%    |
| Jakarta                   | 1         | 1.1%    |
| Istanbul                  | 1         | 1.1%    |
| Iasi                      | 1         | 1.1%    |
| Houston                   | 1         | 1.1%    |
| Hoofddorp                 | 1         | 1.1%    |
| Holmes Chapel             | 1         | 1.1%    |
| Gyomro                    | 1         | 1.1%    |
| Goiânia                  | 1         | 1.1%    |
| Fort Collins              | 1         | 1.1%    |
| Enebyberg                 | 1         | 1.1%    |
| El Segundo                | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 55     | 27.66%  |
| WDC                 | 18        | 27     | 12.77%  |
| Seagate             | 12        | 13     | 8.51%   |
| Kingston            | 12        | 15     | 8.51%   |
| Toshiba             | 9         | 9      | 6.38%   |
| Unknown             | 8         | 10     | 5.67%   |
| SK Hynix            | 4         | 4      | 2.84%   |
| Sandisk             | 4         | 4      | 2.84%   |
| Phison              | 4         | 4      | 2.84%   |
| A-DATA Technology   | 4         | 4      | 2.84%   |
| PNY                 | 3         | 5      | 2.13%   |
| Unknown             | 3         | 3      | 2.13%   |
| XPG                 | 2         | 3      | 1.42%   |
| KIOXIA              | 2         | 3      | 1.42%   |
| Crucial             | 2         | 2      | 1.42%   |
| WDC WDS2            | 1         | 1      | 0.71%   |
| Transcend           | 1         | 1      | 0.71%   |
| Silicon Motion      | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 1      | 0.71%   |
| Mass                | 1         | 1      | 0.71%   |
| Leven               | 1         | 1      | 0.71%   |
| KingDian            | 1         | 1      | 0.71%   |
| Intel               | 1         | 1      | 0.71%   |
| Hitachi             | 1         | 1      | 0.71%   |
| HGST                | 1         | 1      | 0.71%   |
| G-CB0166            | 1         | 1      | 0.71%   |
| Fujitsu             | 1         | 1      | 0.71%   |
| EAGET               | 1         | 1      | 0.71%   |
| China               | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB         | 4         | 2.6%    |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.95%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 1.95%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 1.95%   |
| Samsung SSD 870 QVO 2TB              | 3         | 1.95%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.95%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.95%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.95%   |
| Unknown                              | 3         | 1.95%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 2         | 1.3%    |
| Unknown MMC Card  64GB               | 2         | 1.3%    |
| Samsung SSD 980 1TB                  | 2         | 1.3%    |
| Samsung SSD 970 EVO 250GB            | 2         | 1.3%    |
| Samsung SSD 860 EVO 500GB            | 2         | 1.3%    |
| Samsung SSD 850 EVO 500GB            | 2         | 1.3%    |
| Samsung NVMe SSD Drive 512GB         | 2         | 1.3%    |
| Samsung NVMe SSD Drive 1TB           | 2         | 1.3%    |
| Phison Sabrent 1TB                   | 2         | 1.3%    |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.3%    |
| XPG NVMe SSD Drive 1024GB            | 1         | 0.65%   |
| XPG GAMMIX S11 Pro 512GB             | 1         | 0.65%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.65%   |
| WDC WDS500G1B0C-00S6U0 500GB         | 1         | 0.65%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.65%   |
| WDC WDS2 40G2G0B-00EP 240GB SSD      | 1         | 0.65%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.65%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.65%   |
| WDC WD5000LPLX-75ZNTT0 500GB         | 1         | 0.65%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 0.65%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 1         | 0.65%   |
| WDC WD30EZRX-00SPEB0 3TB             | 1         | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.65%   |
| WDC WD20EARS-00MVWB0 2TB             | 1         | 0.65%   |
| WDC WD2003FYYS-02W0B1 2TB            | 1         | 0.65%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-00ZF5A0 1TB             | 1         | 0.65%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.65%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.65%   |
| Unknown SU32G  32GB                  | 1         | 0.65%   |
| Unknown SM32G  32GB                  | 1         | 0.65%   |
| Unknown SD/MMC/MS PRO 394GB          | 1         | 0.65%   |
| Unknown MMC64G  64GB                 | 1         | 0.65%   |
| Unknown MMC Card  32GB               | 1         | 0.65%   |
| Unknown ED2S5  128GB                 | 1         | 0.65%   |
| Transcend TS240GMTS420S 240GB SSD    | 1         | 0.65%   |
| Toshiba TR200 240GB SSD              | 1         | 0.65%   |
| Toshiba THNSNJ128GCSU 128GB SSD      | 1         | 0.65%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 0.65%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.65%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.65%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.65%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.65%   |
| Toshiba HDWD120 2TB                  | 1         | 0.65%   |
| Toshiba HDWD110 1TB                  | 1         | 0.65%   |
| SK Hynix PC401 NVMe 256GB            | 1         | 0.65%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 0.65%   |
| SK Hynix NVMe SSD Drive 256GB        | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 13     | 38.71%  |
| WDC     | 10        | 18     | 32.26%  |
| Toshiba | 4         | 4      | 12.9%   |
| Unknown | 1         | 1      | 3.23%   |
| Hitachi | 1         | 1      | 3.23%   |
| HGST    | 1         | 1      | 3.23%   |
| Fujitsu | 1         | 1      | 3.23%   |
| Apple   | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 28     | 42.86%  |
| Kingston            | 8         | 10     | 19.05%  |
| WDC                 | 5         | 5      | 11.9%   |
| Toshiba             | 2         | 2      | 4.76%   |
| PNY                 | 2         | 3      | 4.76%   |
| WDC WDS2            | 1         | 1      | 2.38%   |
| Transcend           | 1         | 1      | 2.38%   |
| Leven               | 1         | 1      | 2.38%   |
| EAGET               | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 53        | 65     | 41.09%  |
| SSD     | 35        | 55     | 27.13%  |
| HDD     | 28        | 40     | 21.71%  |
| MMC     | 10        | 13     | 7.75%   |
| Unknown | 3         | 3      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 53        | 65     | 46.9%   |
| SATA | 45        | 93     | 39.82%  |
| MMC  | 10        | 13     | 8.85%   |
| SAS  | 5         | 5      | 4.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 46     | 46.97%  |
| 0.51-1.0   | 20        | 23     | 30.3%   |
| 1.01-2.0   | 10        | 20     | 15.15%  |
| 3.01-4.0   | 3         | 4      | 4.55%   |
| 2.01-3.0   | 1         | 1      | 1.52%   |
| 4.01-10.0  | 1         | 1      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 19        | 20.88%  |
| 1-20           | 18        | 19.78%  |
| 101-250        | 13        | 14.29%  |
| 501-1000       | 13        | 14.29%  |
| 1001-2000      | 10        | 10.99%  |
| More than 3000 | 8         | 8.79%   |
| 51-100         | 4         | 4.4%    |
| 2001-3000      | 3         | 3.3%    |
| Unknown        | 2         | 2.2%    |
| 21-50          | 1         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 38        | 41.76%  |
| 21-50          | 12        | 13.19%  |
| 251-500        | 8         | 8.79%   |
| 101-250        | 8         | 8.79%   |
| 51-100         | 8         | 8.79%   |
| 1001-2000      | 6         | 6.59%   |
| 501-1000       | 5         | 5.49%   |
| More than 3000 | 2         | 2.2%    |
| 2001-3000      | 2         | 2.2%    |
| Unknown        | 2         | 2.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00SPEB0 3TB            | 1         | 1      | 16.67%  |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1      | 16.67%  |
| WDC WD2003FYYS-02W0B1 2TB           | 1         | 6      | 16.67%  |
| Seagate ST31000528AS 1TB            | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 870 EVO 2TB | 1         | 1      | 16.67%  |
| Fujitsu MJA2500BH G1 500GB          | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 8      | 50%     |
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Fujitsu             | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 8      | 60%     |
| Seagate | 1         | 1      | 20%     |
| Fujitsu | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 10     | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Works    | 55        | 91     | 54.46%  |
| Detected | 40        | 74     | 39.6%   |
| Malfunc  | 6         | 11     | 5.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 43        | 35.25%  |
| Samsung Electronics          | 23        | 18.85%  |
| AMD                          | 17        | 13.93%  |
| Sandisk                      | 7         | 5.74%   |
| Phison Electronics           | 5         | 4.1%    |
| ADATA Technology             | 5         | 4.1%    |
| SK Hynix                     | 4         | 3.28%   |
| Kingston Technology Company  | 4         | 3.28%   |
| Toshiba America Info Systems | 3         | 2.46%   |
| KIOXIA                       | 2         | 1.64%   |
| ASMedia Technology           | 2         | 1.64%   |
| VIA Technologies             | 1         | 0.82%   |
| Silicon Motion               | 1         | 0.82%   |
| Micron/Crucial Technology    | 1         | 0.82%   |
| Micron Technology            | 1         | 0.82%   |
| Marvell Technology Group     | 1         | 0.82%   |
| LSI Logic / Symbios Logic    | 1         | 0.82%   |
| JMicron Technology           | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 8.27%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.27%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 6.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 5.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 3.76%   |
| Phison E12 NVMe Controller                                                     | 4         | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 2.26%   |
| Sandisk Non-Volatile memory controller                                         | 3         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.26%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 2.26%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 1.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                          | 2         | 1.5%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.5%    |
| KIOXIA Non-Volatile memory controller                                          | 2         | 1.5%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.5%    |
| ADATA Non-Volatile memory controller                                           | 2         | 1.5%    |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.75%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.75%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.75%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.75%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.75%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1         | 0.75%   |
| Marvell Group 88SE912x IDE Controller                                          | 1         | 0.75%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                        | 1         | 0.75%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.75%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.75%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 0.75%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 0.75%   |
| JMicron JMB368 IDE controller                                                  | 1         | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.75%   |
| Intel SSD 600P Series                                                          | 1         | 0.75%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.75%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1         | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 0.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 0.75%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                         | 1         | 0.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 0.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 54        | 46.15%  |
| NVMe | 53        | 45.3%   |
| RAID | 5         | 4.27%   |
| IDE  | 5         | 4.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 64        | 70.33%  |
| AMD     | 25        | 27.47%  |
| ARM     | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 4.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.3%    |
| Intel Core i7-10870H CPU @ 2.20GHz            | 2         | 2.2%    |
| Intel Core i5-6600K CPU @ 3.50GHz             | 2         | 2.2%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 2.2%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 2.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 2.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.2%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 2.2%    |
| Intel Xeon CPU X5660 @ 2.80GHz                | 1         | 1.1%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 1.1%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.1%    |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.1%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 1.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.1%    |
| Intel Core i7-8809G CPU @ 3.10GHz             | 1         | 1.1%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.1%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.1%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 1.1%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.1%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.1%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.1%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.1%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.1%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 1.1%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.1%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 1.1%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.1%    |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.1%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.1%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.1%    |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1         | 1.1%    |
| Intel Core i5-10600K CPU @ 4.10GHz            | 1         | 1.1%    |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1         | 1.1%    |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 1.1%    |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.1%    |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 1.1%    |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.1%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 1.1%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 1         | 1.1%    |
| Intel Celeron N5100 @ 1.10GHz                 | 1         | 1.1%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.1%    |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 1.1%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 1.1%    |
| Intel Atom CPU Z3795 @ 1.60GHz                | 1         | 1.1%    |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 1.1%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.1%    |
| Intel 11th Gen Core i7-11700 @ 2.50GHz        | 1         | 1.1%    |
| Intel 11th Gen Core i7-1160G7 @ 1.20GHz       | 1         | 1.1%    |
| ARM Processor                                 | 1         | 1.1%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 1.1%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 1.1%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 1.1%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 21        | 23.08%  |
| Intel Core i7        | 15        | 16.48%  |
| Other                | 14        | 15.38%  |
| AMD Ryzen 5          | 10        | 10.99%  |
| AMD Ryzen 7          | 7         | 7.69%   |
| Intel Core i3        | 4         | 4.4%    |
| Intel Core 2 Duo     | 3         | 3.3%    |
| Intel Celeron        | 3         | 3.3%    |
| Intel Xeon           | 2         | 2.2%    |
| Intel Atom           | 2         | 2.2%    |
| AMD Ryzen 9          | 2         | 2.2%    |
| Intel Pentium Silver | 1         | 1.1%    |
| Intel Pentium        | 1         | 1.1%    |
| AMD Ryzen 7 PRO      | 1         | 1.1%    |
| AMD Ryzen 5 PRO      | 1         | 1.1%    |
| AMD Ryzen 3          | 1         | 1.1%    |
| AMD Phenom II X4     | 1         | 1.1%    |
| AMD Athlon X4        | 1         | 1.1%    |
| AMD A8               | 1         | 1.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 42        | 46.15%  |
| 2       | 19        | 20.88%  |
| 8       | 14        | 15.38%  |
| 6       | 11        | 12.09%  |
| 12      | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| 16      | 1         | 1.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 87        | 95.6%   |
| 2       | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 67        | 73.63%  |
| 1       | 22        | 24.18%  |
| Unknown | 2         | 2.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 9         | 9.89%   |
| Unknown    | 6         | 6.59%   |
| 0x806ea    | 5         | 5.49%   |
| 0xa0652    | 4         | 4.4%    |
| 0x906e9    | 4         | 4.4%    |
| 0x506e3    | 4         | 4.4%    |
| 0x306c3    | 4         | 4.4%    |
| 0x0a50000c | 4         | 4.4%    |
| 0x906ea    | 3         | 3.3%    |
| 0x40651    | 3         | 3.3%    |
| 0x306a9    | 3         | 3.3%    |
| 0x08108109 | 3         | 3.3%    |
| 0x706a8    | 2         | 2.2%    |
| 0x10676    | 2         | 2.2%    |
| 0x08701021 | 2         | 2.2%    |
| 0x08608103 | 2         | 2.2%    |
| 0x0810100b | 2         | 2.2%    |
| 0x0800820d | 2         | 2.2%    |
| 0xa0671    | 1         | 1.1%    |
| 0xa0660    | 1         | 1.1%    |
| 0xa0655    | 1         | 1.1%    |
| 0xa0653    | 1         | 1.1%    |
| 0x906ed    | 1         | 1.1%    |
| 0x906c0    | 1         | 1.1%    |
| 0x806ec    | 1         | 1.1%    |
| 0x806e9    | 1         | 1.1%    |
| 0x806d1    | 1         | 1.1%    |
| 0x506c9    | 1         | 1.1%    |
| 0x406e3    | 1         | 1.1%    |
| 0x406c4    | 1         | 1.1%    |
| 0x306f2    | 1         | 1.1%    |
| 0x306d4    | 1         | 1.1%    |
| 0x30678    | 1         | 1.1%    |
| 0x206a7    | 1         | 1.1%    |
| 0x20655    | 1         | 1.1%    |
| 0x20652    | 1         | 1.1%    |
| 0x1067a    | 1         | 1.1%    |
| 0x0a201205 | 1         | 1.1%    |
| 0x0a201016 | 1         | 1.1%    |
| 0x08608102 | 1         | 1.1%    |
| 0x08600106 | 1         | 1.1%    |
| 0x08600104 | 1         | 1.1%    |
| 0x08108102 | 1         | 1.1%    |
| 0x06001119 | 1         | 1.1%    |
| 0x010000c6 | 1         | 1.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 16.48%  |
| TigerLake     | 10        | 10.99%  |
| Haswell       | 8         | 8.79%   |
| Zen 3         | 7         | 7.69%   |
| CometLake     | 7         | 7.69%   |
| Zen+          | 6         | 6.59%   |
| Skylake       | 5         | 5.49%   |
| Unknown       | 5         | 5.49%   |
| Zen 2         | 4         | 4.4%    |
| Westmere      | 3         | 3.3%    |
| Penryn        | 3         | 3.3%    |
| IvyBridge     | 3         | 3.3%    |
| Zen           | 2         | 2.2%    |
| Silvermont    | 2         | 2.2%    |
| Piledriver    | 2         | 2.2%    |
| Icelake       | 2         | 2.2%    |
| Goldmont plus | 2         | 2.2%    |
| Tremont       | 1         | 1.1%    |
| SandyBridge   | 1         | 1.1%    |
| K10           | 1         | 1.1%    |
| Goldmont      | 1         | 1.1%    |
| Broadwell     | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 46.67%  |
| AMD                        | 31        | 29.52%  |
| Nvidia                     | 24        | 22.86%  |
| Matrox Electronics Systems | 1         | 0.95%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 8.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 5.71%   |
| Intel UHD Graphics 620                                                                   | 5         | 4.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 3.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.81%   |
| AMD Cezanne                                                                              | 4         | 3.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.86%   |
| AMD Lucienne                                                                             | 3         | 2.86%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 1.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.9%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 1.9%    |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2         | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.9%    |
| AMD Renoir                                                                               | 2         | 1.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.9%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.95%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.95%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.95%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 1         | 0.95%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.95%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.95%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 0.95%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 0.95%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1         | 0.95%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.95%   |
| Intel Tiger Lake Iris Xe Graphics                                                        | 1         | 0.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.95%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.95%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.95%   |
| Intel HD Graphics 630                                                                    | 1         | 0.95%   |
| Intel HD Graphics 620                                                                    | 1         | 0.95%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.95%   |
| Intel HD Graphics 530                                                                    | 1         | 0.95%   |
| Intel HD Graphics 500                                                                    | 1         | 0.95%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.95%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.95%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                              | 1         | 0.95%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.95%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.95%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                                                  | 1         | 0.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 37.36%  |
| 1 x AMD        | 28        | 30.77%  |
| 1 x Nvidia     | 13        | 14.29%  |
| Intel + Nvidia | 10        | 10.99%  |
| Other          | 2         | 2.2%    |
| Intel + AMD    | 2         | 2.2%    |
| 1 x Matrox     | 1         | 1.1%    |
| AMD + Nvidia   | 1         | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 85.87%  |
| Proprietary | 10        | 10.87%  |
| Unknown     | 3         | 3.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 50.55%  |
| 1.01-2.0   | 14        | 15.38%  |
| 3.01-4.0   | 12        | 13.19%  |
| 0.01-0.5   | 7         | 7.69%   |
| 7.01-8.0   | 5         | 5.49%   |
| 0.51-1.0   | 3         | 3.3%    |
| 5.01-6.0   | 2         | 2.2%    |
| 2.01-3.0   | 1         | 1.1%    |
| 8.01-16.0  | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 17        | 16.5%   |
| LG Display           | 9         | 8.74%   |
| BOE                  | 9         | 8.74%   |
| Chimei Innolux       | 8         | 7.77%   |
| Samsung Electronics  | 7         | 6.8%    |
| Goldstar             | 7         | 6.8%    |
| Philips              | 5         | 4.85%   |
| AOC                  | 5         | 4.85%   |
| Ancor Communications | 5         | 4.85%   |
| Sharp                | 4         | 3.88%   |
| Hewlett-Packard      | 4         | 3.88%   |
| InfoVision           | 3         | 2.91%   |
| Dell                 | 3         | 2.91%   |
| Marantz              | 2         | 1.94%   |
| Lenovo               | 2         | 1.94%   |
| BenQ                 | 2         | 1.94%   |
| Acer                 | 2         | 1.94%   |
| Vizio                | 1         | 0.97%   |
| PANDA                | 1         | 0.97%   |
| Medion               | 1         | 0.97%   |
| Insignia             | 1         | 0.97%   |
| Iiyama               | 1         | 0.97%   |
| Gigabyte Technology  | 1         | 0.97%   |
| DMG                  | 1         | 0.97%   |
| Apple                | 1         | 0.97%   |
| Aosiman              | 1         | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Marantz AVR MJI0031 1920x1080 2210x1250mm 100.0-inch                 | 2         | 1.9%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch         | 2         | 1.9%    |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch           | 2         | 1.9%    |
| Goldstar W2442 GSM56D9 1920x1080 531x299mm 24.0-inch                 | 2         | 1.9%    |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                  | 2         | 1.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.9%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 2         | 1.9%    |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                    | 1         | 0.95%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 0.95%   |
| Sharp LQ156M1JW23 SHP1514 1920x1080 344x194mm 15.5-inch              | 1         | 0.95%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 0.95%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch              | 1         | 0.95%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM049B 1920x1080 477x268mm 21.5-inch | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 0.95%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch   | 1         | 0.95%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 0.95%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 0.95%   |
| Philips PHL BDM3470UP PHL08DA 3440x1440 800x335mm 34.1-inch          | 1         | 0.95%   |
| Philips PHL 278E1 PHLC217 3840x2160 597x336mm 27.0-inch              | 1         | 0.95%   |
| Philips PHL 276E8V PHLC18F 1920x1080 597x336mm 27.0-inch             | 1         | 0.95%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1         | 0.95%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1         | 0.95%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch              | 1         | 0.95%   |
| Medion MD21473 MED461C 2560x1440 597x336mm 27.0-inch                 | 1         | 0.95%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch          | 1         | 0.95%   |
| Lenovo M14 LEN61DD 1920x1080 309x174mm 14.0-inch                     | 1         | 0.95%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch             | 1         | 0.95%   |
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                  | 1         | 0.95%   |
| Insignia DX-19L150A11 BBY1911 1360x768 410x230mm 18.5-inch           | 1         | 0.95%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 0.95%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch         | 1         | 0.95%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 0.95%   |
| Iiyama PL3270Q IVM7608 2560x1440 698x393mm 31.5-inch                 | 1         | 0.95%   |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch           | 1         | 0.95%   |
| Hewlett-Packard E223 HPN345B 1920x1080 480x270mm 21.7-inch           | 1         | 0.95%   |
| Goldstar ULTRAWIDE GSM76FC 3840x1600 874x366mm 37.3-inch             | 1         | 0.95%   |
| Goldstar ULTRAGEAR GSM773B 2560x1080 798x334mm 34.1-inch             | 1         | 0.95%   |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                | 1         | 0.95%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch       | 1         | 0.95%   |
| DMG 34CHR DMGFFFF 3440x1440 797x334mm 34.0-inch                      | 1         | 0.95%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 1         | 0.95%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 1         | 0.95%   |
| Dell E2216H DELF069 1920x1080 480x270mm 21.7-inch                    | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch     | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1345 1920x1080 293x165mm 13.2-inch     | 1         | 0.95%   |
| Chimei Innolux LCD Monitor CMN1249 1920x1280 259x172mm 12.2-inch     | 1         | 0.95%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 0.95%   |
| BOE LCD Monitor BOE0922 1920x550                                     | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 60.42%  |
| 2560x1440 (QHD)    | 7         | 7.29%   |
| 3840x2160 (4K)     | 6         | 6.25%   |
| 1366x768 (WXGA)    | 6         | 6.25%   |
| 1920x1200 (WUXGA)  | 4         | 4.17%   |
| 1600x900 (HD+)     | 3         | 3.13%   |
| 3440x1440          | 2         | 2.08%   |
| 3840x2400          | 1         | 1.04%   |
| 3840x1600          | 1         | 1.04%   |
| 3840x1080          | 1         | 1.04%   |
| 2736x1824          | 1         | 1.04%   |
| 2560x1080          | 1         | 1.04%   |
| 2256x1504          | 1         | 1.04%   |
| 1920x550           | 1         | 1.04%   |
| 1920x1280          | 1         | 1.04%   |
| 1680x1050 (WSXGA+) | 1         | 1.04%   |
| 1360x768           | 1         | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 18.63%  |
| 13      | 18        | 17.65%  |
| 27      | 10        | 9.8%    |
| 24      | 10        | 9.8%    |
| 14      | 9         | 8.82%   |
| 23      | 7         | 6.86%   |
| 21      | 7         | 6.86%   |
| 31      | 4         | 3.92%   |
| 12      | 3         | 2.94%   |
| 100     | 2         | 1.96%   |
| 72      | 2         | 1.96%   |
| 34      | 2         | 1.96%   |
| 17      | 2         | 1.96%   |
| 48      | 1         | 0.98%   |
| 37      | 1         | 0.98%   |
| 20      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 11      | 1         | 0.98%   |
| 10      | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 33        | 33.33%  |
| 501-600        | 24        | 24.24%  |
| 201-300        | 16        | 16.16%  |
| 401-500        | 10        | 10.1%   |
| 601-700        | 4         | 4.04%   |
| 351-400        | 3         | 3.03%   |
| More than 2000 | 2         | 2.02%   |
| 701-800        | 2         | 2.02%   |
| 1501-2000      | 2         | 2.02%   |
| 801-900        | 1         | 1.01%   |
| 1001-1500      | 1         | 1.01%   |
| Unknown        | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 82.95%  |
| 16/10 | 6         | 6.82%   |
| 3/2   | 4         | 4.55%   |
| 21/9  | 3         | 3.41%   |
| 32/9  | 2         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 19.19%  |
| 81-90          | 17        | 17.17%  |
| 201-250        | 17        | 17.17%  |
| 71-80          | 11        | 11.11%  |
| 301-350        | 10        | 10.1%   |
| 351-500        | 6         | 6.06%   |
| More than 1000 | 4         | 4.04%   |
| 151-200        | 4         | 4.04%   |
| 61-70          | 2         | 2.02%   |
| 251-300        | 2         | 2.02%   |
| 121-130        | 2         | 2.02%   |
| 51-60          | 1         | 1.01%   |
| 41-50          | 1         | 1.01%   |
| 141-150        | 1         | 1.01%   |
| 501-1000       | 1         | 1.01%   |
| Unknown        | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 35.71%  |
| 51-100        | 29        | 29.59%  |
| 161-240       | 16        | 16.33%  |
| 101-120       | 14        | 14.29%  |
| 1-50          | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |
| Unknown       | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 76.09%  |
| 2     | 11        | 11.96%  |
| 0     | 7         | 7.61%   |
| 3     | 2         | 2.17%   |
| 5     | 1         | 1.09%   |
| 4     | 1         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 52        | 40.31%  |
| Realtek Semiconductor             | 44        | 34.11%  |
| Qualcomm Atheros                  | 10        | 7.75%   |
| Broadcom                          | 5         | 3.88%   |
| MEDIATEK                          | 3         | 2.33%   |
| Ralink Technology                 | 2         | 1.55%   |
| Microsoft                         | 2         | 1.55%   |
| Marvell Technology Group          | 2         | 1.55%   |
| Belkin Components                 | 2         | 1.55%   |
| TP-Link                           | 1         | 0.78%   |
| NetGear                           | 1         | 0.78%   |
| MicroPython                       | 1         | 0.78%   |
| Microchip Technology              | 1         | 0.78%   |
| Ericsson Business Mobile Networks | 1         | 0.78%   |
| DisplayLink                       | 1         | 0.78%   |
| ASUSTek Computer                  | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 30        | 20.41%  |
| Intel Wi-Fi 6 AX200                                                | 9         | 6.12%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.08%   |
| Intel Wireless 8265 / 8275                                         | 4         | 2.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 3         | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                  | 3         | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 3         | 2.04%   |
| Intel Wireless 7260                                                | 3         | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 2         | 1.36%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2         | 1.36%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.36%   |
| Intel Wireless 8260                                                | 2         | 1.36%   |
| Intel Wireless 3165                                                | 2         | 1.36%   |
| Intel WiFi Link 5100                                               | 2         | 1.36%   |
| Intel Ethernet Connection I217-LM                                  | 2         | 1.36%   |
| Intel Ethernet Connection (2) I219-V                               | 2         | 1.36%   |
| Intel Ethernet Connection (13) I219-V                              | 2         | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 2         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.36%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 1.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.68%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 0.68%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                  | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 0.68%   |
| NetGear A6210                                                      | 1         | 0.68%   |
| MicroPython Board in FS mode                                       | 1         | 0.68%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                      | 1         | 0.68%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1         | 0.68%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                  | 1         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 0.68%   |
| Intel Wireless-AC 9260                                             | 1         | 0.68%   |
| Intel Wireless 3160                                                | 1         | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 0.68%   |
| Intel I210 Gigabit Network Connection                              | 1         | 0.68%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 0.68%   |
| Intel Ethernet Controller I225-V                                   | 1         | 0.68%   |
| Intel Ethernet controller                                          | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                               | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                              | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                              | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 57.69%  |
| Realtek Semiconductor    | 11        | 14.1%   |
| Qualcomm Atheros         | 6         | 7.69%   |
| MEDIATEK                 | 3         | 3.85%   |
| Broadcom                 | 3         | 3.85%   |
| Ralink Technology        | 2         | 2.56%   |
| Microsoft                | 2         | 2.56%   |
| Belkin Components        | 2         | 2.56%   |
| TP-Link                  | 1         | 1.28%   |
| NetGear                  | 1         | 1.28%   |
| Marvell Technology Group | 1         | 1.28%   |
| ASUSTek Computer         | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                | 9         | 11.54%  |
| Intel Wi-Fi 6 AX201                                                | 6         | 7.69%   |
| Intel Wireless 8265 / 8275                                         | 4         | 5.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 3.85%   |
| Intel Wireless 7260                                                | 3         | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3         | 3.85%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 2.56%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2         | 2.56%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 2.56%   |
| Intel Wireless 8260                                                | 2         | 2.56%   |
| Intel Wireless 3165                                                | 2         | 2.56%   |
| Intel WiFi Link 5100                                               | 2         | 2.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 2         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 2.56%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 2         | 2.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.28%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 1.28%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1         | 1.28%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 1.28%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                  | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.28%   |
| NetGear A6210                                                      | 1         | 1.28%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                      | 1         | 1.28%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                  | 1         | 1.28%   |
| Intel Wireless-AC 9260                                             | 1         | 1.28%   |
| Intel Wireless 3160                                                | 1         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 1.28%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 1         | 1.28%   |
| Intel Centrino Wireless-N 2230                                     | 1         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 1         | 1.28%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 1.28%   |
| Broadcom BCM43222 802.11abgn Wireless Network Adapter              | 1         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                      | 1         | 1.28%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 58.46%  |
| Intel                    | 17        | 26.15%  |
| Qualcomm Atheros         | 4         | 6.15%   |
| Broadcom                 | 3         | 4.62%   |
| Microchip Technology     | 1         | 1.54%   |
| Marvell Technology Group | 1         | 1.54%   |
| DisplayLink              | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.99%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.99%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.99%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.49%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 1.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.49%   |
| Intel Ethernet controller                                         | 1         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.49%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.49%   |
| DisplayLink GIQ Triple-display Mini Docking station               | 1         | 1.49%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 53.24%  |
| Ethernet | 63        | 45.32%  |
| Modem    | 2         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 67.71%  |
| Ethernet | 31        | 32.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 49.45%  |
| 2     | 38        | 41.76%  |
| 0     | 4         | 4.4%    |
| 3     | 3         | 3.3%    |
| 4     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 65        | 71.43%  |
| Yes  | 26        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 62.9%   |
| Realtek Semiconductor           | 5         | 8.06%   |
| Qualcomm Atheros Communications | 4         | 6.45%   |
| Lite-On Technology              | 2         | 3.23%   |
| IMC Networks                    | 2         | 3.23%   |
| Foxconn / Hon Hai               | 2         | 3.23%   |
| TP-Link                         | 1         | 1.61%   |
| MediaTek                        | 1         | 1.61%   |
| Marvell Semiconductor           | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |
| Cambridge Silicon Radio         | 1         | 1.61%   |
| Broadcom                        | 1         | 1.61%   |
| ASUSTek Computer                | 1         | 1.61%   |
| Apple                           | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 19.35%  |
| Intel Bluetooth Device                              | 9         | 14.52%  |
| Intel AX200 Bluetooth                               | 9         | 14.52%  |
| Realtek Bluetooth Radio                             | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.84%   |
| Intel AX210 Bluetooth                               | 3         | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.23%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.23%   |
| TP-Link UB500 Adapter                               | 1         | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.61%   |
| MediaTek Wireless_Device                            | 1         | 1.61%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.61%   |
| Lite-On Wireless_Device                             | 1         | 1.61%   |
| Lite-On Bluetooth Device                            | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.61%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.61%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.61%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 59        | 45.74%  |
| AMD                      | 32        | 24.81%  |
| Nvidia                   | 21        | 16.28%  |
| C-Media Electronics      | 3         | 2.33%   |
| Logitech                 | 2         | 1.55%   |
| Creative Labs            | 2         | 1.55%   |
| XMOS                     | 1         | 0.78%   |
| Turtle Beach             | 1         | 0.78%   |
| Texas Instruments        | 1         | 0.78%   |
| Sony                     | 1         | 0.78%   |
| Plantronics              | 1         | 0.78%   |
| Micro Star International | 1         | 0.78%   |
| KORG                     | 1         | 0.78%   |
| Focusrite-Novation       | 1         | 0.78%   |
| fifinemicrophone.com     | 1         | 0.78%   |
| Corsair                  | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 9.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 6.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.77%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 3.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5         | 3.21%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 2.56%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.92%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.28%   |
| Nvidia Audio device                                                        | 2         | 1.28%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.28%   |
| C-Media Electronics USB Audio Device                                       | 2         | 1.28%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.28%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 0.64%   |
| Turtle Beach Elite SuperAmp PC                                             | 1         | 0.64%   |
| Texas Instruments PCM2903B Audio CODEC                                     | 1         | 0.64%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.64%   |
| Plantronics Blackwire 325.1                                                | 1         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.64%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.64%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.64%   |
| Micro Star International USB Audio                                         | 1         | 0.64%   |
| Logitech PRO X Wireless Gaming Headset                                     | 1         | 0.64%   |
| Logitech Blue Snowball                                                     | 1         | 0.64%   |
| KORG microKEY-37                                                           | 1         | 0.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.64%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.64%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.64%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.64%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 0.64%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 0.64%   |
| Focusrite-Novation Scarlett 2i4 USB                                        | 1         | 0.64%   |
| fifinemicrophone.com FIFINE Microphone                                     | 1         | 0.64%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 0.64%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 1         | 0.64%   |
| Corsair VOID PRO Wireless Gaming Headset                                   | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 20%     |
| Micron Technology   | 12        | 16%     |
| SK Hynix            | 11        | 14.67%  |
| Crucial             | 8         | 10.67%  |
| Kingston            | 7         | 9.33%   |
| Unknown             | 5         | 6.67%   |
| G.Skill             | 4         | 5.33%   |
| Unknown (ABCD)      | 2         | 2.67%   |
| V-GeN               | 1         | 1.33%   |
| Silicon Power       | 1         | 1.33%   |
| Sesame              | 1         | 1.33%   |
| Samsung 1           | 1         | 1.33%   |
| Patriot             | 1         | 1.33%   |
| Mushkin             | 1         | 1.33%   |
| Hikvision           | 1         | 1.33%   |
| GOODRAM             | 1         | 1.33%   |
| Corsair             | 1         | 1.33%   |
| A-TECH              | 1         | 1.33%   |
| A-DATA Technology   | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 2.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 2.6%    |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s                       | 1         | 1.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.3%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 1.3%    |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 1         | 1.3%    |
| Unknown RAM 3460-1664 8GB DIMM DDR3 1600MT/s                        | 1         | 1.3%    |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                       | 1         | 1.3%    |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 1.3%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.3%    |
| SK Hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s                | 1         | 1.3%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.3%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.3%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s           | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.3%    |
| SK Hynix RAM HMA451R7MFR8N-TF 4GB RIMM 2133MT/s                     | 1         | 1.3%    |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.3%    |
| SK Hynix RAM H5TC8G63AMR-PBR 4GB SODIMM DDR3 1600MT/s               | 1         | 1.3%    |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.3%    |
| Samsung RAM U7H704AM-JGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.3%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 1.3%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                 | 1         | 1.3%    |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 1.3%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.3%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                 | 1         | 1.3%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.3%    |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s        | 1         | 1.3%    |
| Samsung 1 RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s               | 1         | 1.3%    |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s                  | 1         | 1.3%    |
| Mushkin RAM MR[A/B]4U266GHHF8G 8GB DIMM DDR4 2133MT/s               | 1         | 1.3%    |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.3%    |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                          | 1         | 1.3%    |
| Micron RAM Module 3GB Row Of Chips LPDDR4 1867MT/s                  | 1         | 1.3%    |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM 2133MT/s                      | 1         | 1.3%    |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 1         | 1.3%    |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s                 | 1         | 1.3%    |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 1         | 1.3%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.3%    |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.3%    |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s                | 1         | 1.3%    |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.3%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 1         | 1.3%    |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s              | 1         | 1.3%    |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s               | 1         | 1.3%    |
| Kingston RAM 99U5471-034.A 4GB DIMM DDR3 667MT/s                    | 1         | 1.3%    |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 1.3%    |
| Kingston RAM 9905700-072.A01G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.3%    |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.3%    |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.3%    |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s                | 1         | 1.3%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s               | 1         | 1.3%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                 | 1         | 1.3%    |
| G.Skill RAM F4-2400C15-16GVR 16GB DIMM DDR4 2400MT/s                | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 53.33%  |
| DDR3    | 14        | 23.33%  |
| LPDDR4  | 8         | 13.33%  |
| LPDDR3  | 4         | 6.67%   |
| DDR2    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 49.18%  |
| DIMM         | 19        | 31.15%  |
| Row Of Chips | 11        | 18.03%  |
| RIMM         | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 34.78%  |
| 4096  | 23        | 33.33%  |
| 16384 | 12        | 17.39%  |
| 2048  | 6         | 8.7%    |
| 32768 | 3         | 4.35%   |
| 3072  | 1         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 15        | 22.73%  |
| 1600    | 9         | 13.64%  |
| 2667    | 8         | 12.12%  |
| 2400    | 7         | 10.61%  |
| 2133    | 7         | 10.61%  |
| 4267    | 5         | 7.58%   |
| 1867    | 4         | 6.06%   |
| 1333    | 3         | 4.55%   |
| 3266    | 2         | 3.03%   |
| 3866    | 1         | 1.52%   |
| 2933    | 1         | 1.52%   |
| 1066    | 1         | 1.52%   |
| 800     | 1         | 1.52%   |
| 667     | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP Neverstop Laser 100x | 1         | 50%     |
| Brother Printer         | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 200 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 13        | 22.41%  |
| IMC Networks                  | 7         | 12.07%  |
| Realtek Semiconductor         | 6         | 10.34%  |
| Acer                          | 6         | 10.34%  |
| Syntek                        | 4         | 6.9%    |
| Microdia                      | 4         | 6.9%    |
| Logitech                      | 3         | 5.17%   |
| Ricoh                         | 2         | 3.45%   |
| Quanta                        | 2         | 3.45%   |
| Lite-On Technology            | 2         | 3.45%   |
| USB Camera                    | 1         | 1.72%   |
| Sunplus Innovation Technology | 1         | 1.72%   |
| Samsung Electronics           | 1         | 1.72%   |
| Primax Electronics            | 1         | 1.72%   |
| Microsoft                     | 1         | 1.72%   |
| Luxvisions Innotech Limited   | 1         | 1.72%   |
| KYE Systems (Mouse Systems)   | 1         | 1.72%   |
| Apple                         | 1         | 1.72%   |
| Alcor Micro                   | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 5         | 8.47%   |
| Microdia Integrated_Webcam_HD             | 4         | 6.78%   |
| IMC Networks Integrated Camera            | 4         | 6.78%   |
| Realtek Integrated_Webcam_HD              | 3         | 5.08%   |
| Syntek Integrated Camera                  | 2         | 3.39%   |
| Lite-On Integrated Camera                 | 2         | 3.39%   |
| IMC Networks USB2.0 HD UVC WebCam         | 2         | 3.39%   |
| Chicony HP TrueVision HD Camera           | 2         | 3.39%   |
| Chicony HD WebCam                         | 2         | 3.39%   |
| Acer Integrated Camera                    | 2         | 3.39%   |
| USB Camera USB Camera                     | 1         | 1.69%   |
| Syntek Lenovo EasyCamera                  | 1         | 1.69%   |
| Syntek Integrated RGB Camera              | 1         | 1.69%   |
| Sunplus HD 720P webcam                    | 1         | 1.69%   |
| Samsung Galaxy A5 (MTP)                   | 1         | 1.69%   |
| Ricoh Sony Vaio Integrated Webcam         | 1         | 1.69%   |
| Ricoh Integrated Webcam                   | 1         | 1.69%   |
| Realtek Thronmax Stream Go Pro Webcam     | 1         | 1.69%   |
| Realtek Integrated Webcam                 | 1         | 1.69%   |
| Realtek Front Camera                      | 1         | 1.69%   |
| Realtek Back Camera                       | 1         | 1.69%   |
| Quanta HP HD Camera                       | 1         | 1.69%   |
| Quanta HD User Facing                     | 1         | 1.69%   |
| Primax HP HD Webcam [Fixed]               | 1         | 1.69%   |
| Microsoft LifeCam Cinema                  | 1         | 1.69%   |
| Luxvisions Innotech Limited HP HD Camera  | 1         | 1.69%   |
| Logitech QuickCam Communicate Deluxe      | 1         | 1.69%   |
| Logitech HD Webcam C615                   | 1         | 1.69%   |
| Logitech B525 HD Webcam                   | 1         | 1.69%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1         | 1.69%   |
| IMC Networks EasyCamera                   | 1         | 1.69%   |
| Chicony TOSHIBA Web Camera - MP           | 1         | 1.69%   |
| Chicony Integrated Camera (1280x720@30)   | 1         | 1.69%   |
| Chicony HP Wide Vision FHD Camera         | 1         | 1.69%   |
| Chicony HP HD Camera                      | 1         | 1.69%   |
| Apple FaceTime HD Camera (Built-in)       | 1         | 1.69%   |
| Alcor Micro USB 2.0 Web Camera            | 1         | 1.69%   |
| Acer Lenovo EasyCamera                    | 1         | 1.69%   |
| Acer HD Webcam                            | 1         | 1.69%   |
| Acer HD Camera                            | 1         | 1.69%   |
| Acer BisonCam,NB Pro                      | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 55%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| LighTuning Technology      | 2         | 10%     |
| Validity Sensors           | 1         | 5%      |
| Elan Microelectronics      | 1         | 5%      |
| DigitalPersona             | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 6         | 30%     |
| Shenzhen Goodix  Fingerprint Device                        | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor                | 2         | 10%     |
| Unknown                                                    | 2         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 5%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 5%      |
| Elan ELAN:Fingerprint                                      | 1         | 5%      |
| DigitalPersona Fingerprint Reader                          | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 80%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 4         | 80%     |
| Broadcom 58200                      | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 63.04%  |
| 1     | 25        | 27.17%  |
| 2     | 6         | 6.52%   |
| 3     | 3         | 3.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 19        | 47.5%   |
| Graphics card         | 9         | 22.5%   |
| Multimedia controller | 5         | 12.5%   |
| Net/wireless          | 3         | 7.5%    |
| Unassigned class      | 1         | 2.5%    |
| Sound                 | 1         | 2.5%    |
| Card reader           | 1         | 2.5%    |
| Bluetooth             | 1         | 2.5%    |

