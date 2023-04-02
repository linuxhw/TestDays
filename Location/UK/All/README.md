Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 10436

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | H57M01                      | Desktop     | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [1146b0ebfc](https://linux-hardware.org/?probe=1146b0ebfc) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9a7a6ccf6](https://linux-hardware.org/?probe=d9a7a6ccf6) | Mar 31, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Desktop     | [49917003da](https://linux-hardware.org/?probe=49917003da) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [3bf5fd0cfd](https://linux-hardware.org/?probe=3bf5fd0cfd) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | Notebook    | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | Notebook    | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [40a3ae2220](https://linux-hardware.org/?probe=40a3ae2220) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a37020a71d](https://linux-hardware.org/?probe=a37020a71d) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [645c8515a1](https://linux-hardware.org/?probe=645c8515a1) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5dcd20300a](https://linux-hardware.org/?probe=5dcd20300a) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | Desktop     | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | Desktop     | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | Notebook    | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | Notebook    | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Notebook      | W510LU                      | Notebook    | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [d32441b2c3](https://linux-hardware.org/?probe=d32441b2c3) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | Notebook    | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [87e3ca6a56](https://linux-hardware.org/?probe=87e3ca6a56) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [63a8165aff](https://linux-hardware.org/?probe=63a8165aff) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [972b8e8c3c](https://linux-hardware.org/?probe=972b8e8c3c) | Mar 19, 2023 |
| HP            | 3397                        | Desktop     | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Dell          | Inspiron 15 7510            | Notebook    | [f7aebbae36](https://linux-hardware.org/?probe=f7aebbae36) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [6a0c74a051](https://linux-hardware.org/?probe=6a0c74a051) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [d84f3134b9](https://linux-hardware.org/?probe=d84f3134b9) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [06d89bd973](https://linux-hardware.org/?probe=06d89bd973) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [63dba9dd56](https://linux-hardware.org/?probe=63dba9dd56) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [e4eb6f31af](https://linux-hardware.org/?probe=e4eb6f31af) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [9861151d08](https://linux-hardware.org/?probe=9861151d08) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ccd15bcfae](https://linux-hardware.org/?probe=ccd15bcfae) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [0ee987e184](https://linux-hardware.org/?probe=0ee987e184) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [ad4d45d3fa](https://linux-hardware.org/?probe=ad4d45d3fa) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [3d0b03a361](https://linux-hardware.org/?probe=3d0b03a361) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [e2f98f4fd2](https://linux-hardware.org/?probe=e2f98f4fd2) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9331f6026e](https://linux-hardware.org/?probe=9331f6026e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7e90a81e0b](https://linux-hardware.org/?probe=7e90a81e0b) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [1ad8d706ff](https://linux-hardware.org/?probe=1ad8d706ff) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| Google        | Teemo                       | Desktop     | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [2124288941](https://linux-hardware.org/?probe=2124288941) | Mar 13, 2023 |
| Dell          | 02M8NY A02                  | Desktop     | [b3c31072bb](https://linux-hardware.org/?probe=b3c31072bb) | Mar 13, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [12277151fa](https://linux-hardware.org/?probe=12277151fa) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | Desktop     | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8c344866da](https://linux-hardware.org/?probe=8c344866da) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [fdb6080ba5](https://linux-hardware.org/?probe=fdb6080ba5) | Mar 13, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [686fb235ce](https://linux-hardware.org/?probe=686fb235ce) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | Notebook    | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2be528d875](https://linux-hardware.org/?probe=2be528d875) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [f6c972404c](https://linux-hardware.org/?probe=f6c972404c) | Mar 12, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [d841d9761a](https://linux-hardware.org/?probe=d841d9761a) | Mar 11, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [d822a4112f](https://linux-hardware.org/?probe=d822a4112f) | Mar 11, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [382901fcd7](https://linux-hardware.org/?probe=382901fcd7) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [2f86f93df5](https://linux-hardware.org/?probe=2f86f93df5) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | Desktop     | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Google        | Ampton                      | Notebook    | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [354cdf8592](https://linux-hardware.org/?probe=354cdf8592) | Mar 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4cc4ff572](https://linux-hardware.org/?probe=d4cc4ff572) | Mar 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [9bcfd20d80](https://linux-hardware.org/?probe=9bcfd20d80) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| Dell          | Latitude 7285               | Notebook    | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | MINI S                      | Desktop     | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [69564be379](https://linux-hardware.org/?probe=69564be379) | Mar 08, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [519310d05f](https://linux-hardware.org/?probe=519310d05f) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Entroware     | Apollo                      | Notebook    | [d1576010b3](https://linux-hardware.org/?probe=d1576010b3) | Mar 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [1851a5388e](https://linux-hardware.org/?probe=1851a5388e) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [5582ce4ba9](https://linux-hardware.org/?probe=5582ce4ba9) | Mar 08, 2023 |
| Foxconn       | ETON                        | Desktop     | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [30b6242c17](https://linux-hardware.org/?probe=30b6242c17) | Mar 07, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [54d0c16597](https://linux-hardware.org/?probe=54d0c16597) | Mar 07, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [99d2997b98](https://linux-hardware.org/?probe=99d2997b98) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ccd90a8ac4](https://linux-hardware.org/?probe=ccd90a8ac4) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| Gigabyte      | Z690 GAMING X               | Desktop     | [b8dc3dd82b](https://linux-hardware.org/?probe=b8dc3dd82b) | Mar 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c5809ffd96](https://linux-hardware.org/?probe=c5809ffd96) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8812bcfc2b](https://linux-hardware.org/?probe=8812bcfc2b) | Mar 06, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [f9f277d226](https://linux-hardware.org/?probe=f9f277d226) | Mar 06, 2023 |
| ASUSTek       | Z97-DELUXE/USB              | Desktop     | [46d851b146](https://linux-hardware.org/?probe=46d851b146) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6c973a00f](https://linux-hardware.org/?probe=f6c973a00f) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [73eb839f5b](https://linux-hardware.org/?probe=73eb839f5b) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | Notebook    | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [6a0179b36e](https://linux-hardware.org/?probe=6a0179b36e) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [f6863db7ca](https://linux-hardware.org/?probe=f6863db7ca) | Mar 05, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [c777bd0be1](https://linux-hardware.org/?probe=c777bd0be1) | Mar 05, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [53d547f79c](https://linux-hardware.org/?probe=53d547f79c) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [d1ada89fd6](https://linux-hardware.org/?probe=d1ada89fd6) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | Notebook    | [3c8e62e276](https://linux-hardware.org/?probe=3c8e62e276) | Mar 04, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [3b1c7f5e26](https://linux-hardware.org/?probe=3b1c7f5e26) | Mar 04, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [b53bbf2061](https://linux-hardware.org/?probe=b53bbf2061) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | Notebook    | [5c059744df](https://linux-hardware.org/?probe=5c059744df) | Mar 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [89de1a18fe](https://linux-hardware.org/?probe=89de1a18fe) | Mar 04, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [621391a7e0](https://linux-hardware.org/?probe=621391a7e0) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | Notebook    | [2aa5383e7e](https://linux-hardware.org/?probe=2aa5383e7e) | Mar 04, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [48f407dbf7](https://linux-hardware.org/?probe=48f407dbf7) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c19189c929](https://linux-hardware.org/?probe=c19189c929) | Mar 04, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [11572533c2](https://linux-hardware.org/?probe=11572533c2) | Mar 03, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3edae4d4f7](https://linux-hardware.org/?probe=3edae4d4f7) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [5af7b05e04](https://linux-hardware.org/?probe=5af7b05e04) | Mar 02, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [2629f1915d](https://linux-hardware.org/?probe=2629f1915d) | Mar 02, 2023 |
| Dell          | Latitude E6410              | Notebook    | [3b99fd709e](https://linux-hardware.org/?probe=3b99fd709e) | Mar 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [83cbea47d9](https://linux-hardware.org/?probe=83cbea47d9) | Mar 02, 2023 |
| Acer          | Aspire A315-32              | Notebook    | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| HP            | 1998                        | Desktop     | [269c6134f1](https://linux-hardware.org/?probe=269c6134f1) | Mar 01, 2023 |
| Dell          | Latitude E7250              | Notebook    | [970d46cc83](https://linux-hardware.org/?probe=970d46cc83) | Mar 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [bfe7635484](https://linux-hardware.org/?probe=bfe7635484) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [2d1ec6c994](https://linux-hardware.org/?probe=2d1ec6c994) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [784ef5ef12](https://linux-hardware.org/?probe=784ef5ef12) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [cd39348090](https://linux-hardware.org/?probe=cd39348090) | Mar 01, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [b1744130eb](https://linux-hardware.org/?probe=b1744130eb) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Umbrel        | Home                        | Mini pc     | [f4afc80a6c](https://linux-hardware.org/?probe=f4afc80a6c) | Feb 28, 2023 |
| Alienware     | 15 R2                       | Notebook    | [f242145858](https://linux-hardware.org/?probe=f242145858) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [bbc0d58ef1](https://linux-hardware.org/?probe=bbc0d58ef1) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [48e150f274](https://linux-hardware.org/?probe=48e150f274) | Feb 28, 2023 |
| AZW           | Speed S                     | Desktop     | [e44ff0faf0](https://linux-hardware.org/?probe=e44ff0faf0) | Feb 28, 2023 |
| HP            | 83E2                        | Desktop     | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [5175558c99](https://linux-hardware.org/?probe=5175558c99) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [506d56faff](https://linux-hardware.org/?probe=506d56faff) | Feb 28, 2023 |
| AZW           | SEi                         | Notebook    | [6d0814dc9f](https://linux-hardware.org/?probe=6d0814dc9f) | Feb 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b3c4d2985e](https://linux-hardware.org/?probe=b3c4d2985e) | Feb 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b5a08d19e9](https://linux-hardware.org/?probe=b5a08d19e9) | Feb 27, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [626e67df35](https://linux-hardware.org/?probe=626e67df35) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [c2b3e01a45](https://linux-hardware.org/?probe=c2b3e01a45) | Feb 27, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f15e5303f6](https://linux-hardware.org/?probe=f15e5303f6) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1213e49ca8](https://linux-hardware.org/?probe=1213e49ca8) | Feb 26, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | Notebook    | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [15b2fe94ae](https://linux-hardware.org/?probe=15b2fe94ae) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [d6805fb81b](https://linux-hardware.org/?probe=d6805fb81b) | Feb 25, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [64f304d41e](https://linux-hardware.org/?probe=64f304d41e) | Feb 25, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [4f9e90413b](https://linux-hardware.org/?probe=4f9e90413b) | Feb 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [87df24d8c2](https://linux-hardware.org/?probe=87df24d8c2) | Feb 25, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [d78e737aaf](https://linux-hardware.org/?probe=d78e737aaf) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [af9891267d](https://linux-hardware.org/?probe=af9891267d) | Feb 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [cf2ff6c04b](https://linux-hardware.org/?probe=cf2ff6c04b) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [df96e94417](https://linux-hardware.org/?probe=df96e94417) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [123771dbb2](https://linux-hardware.org/?probe=123771dbb2) | Feb 24, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [7f29da1b6c](https://linux-hardware.org/?probe=7f29da1b6c) | Feb 24, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [e7edf0f7c3](https://linux-hardware.org/?probe=e7edf0f7c3) | Feb 23, 2023 |
| HP            | 1497                        | Desktop     | [478a5730f6](https://linux-hardware.org/?probe=478a5730f6) | Feb 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [7780f02f45](https://linux-hardware.org/?probe=7780f02f45) | Feb 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [8679998ec0](https://linux-hardware.org/?probe=8679998ec0) | Feb 23, 2023 |
| PC Special... | PD5x_7xPNP_PNN_PNT          | Notebook    | [cd71ec0b21](https://linux-hardware.org/?probe=cd71ec0b21) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f307a87e5](https://linux-hardware.org/?probe=8f307a87e5) | Feb 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [781c058256](https://linux-hardware.org/?probe=781c058256) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [c570bb75bf](https://linux-hardware.org/?probe=c570bb75bf) | Feb 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c3d9b18f7c](https://linux-hardware.org/?probe=c3d9b18f7c) | Feb 23, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [d19ee09dd3](https://linux-hardware.org/?probe=d19ee09dd3) | Feb 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [7bd9274f23](https://linux-hardware.org/?probe=7bd9274f23) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d88dce11ff](https://linux-hardware.org/?probe=d88dce11ff) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | Notebook    | [3a2c22e22b](https://linux-hardware.org/?probe=3a2c22e22b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | Notebook    | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | Notebook    | [06c8604990](https://linux-hardware.org/?probe=06c8604990) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Google        | Droid                       | Notebook    | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [c51d4ef82a](https://linux-hardware.org/?probe=c51d4ef82a) | Feb 20, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [6799113f3e](https://linux-hardware.org/?probe=6799113f3e) | Feb 20, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [640cad4ab6](https://linux-hardware.org/?probe=640cad4ab6) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b184665592](https://linux-hardware.org/?probe=b184665592) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [2ccbfb422e](https://linux-hardware.org/?probe=2ccbfb422e) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [375a3684e2](https://linux-hardware.org/?probe=375a3684e2) | Feb 19, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [0bcbc517ca](https://linux-hardware.org/?probe=0bcbc517ca) | Feb 19, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [f347582e5c](https://linux-hardware.org/?probe=f347582e5c) | Feb 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e7e9625ffc](https://linux-hardware.org/?probe=e7e9625ffc) | Feb 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f3552f5183](https://linux-hardware.org/?probe=f3552f5183) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | Notebook    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [2c41f563a1](https://linux-hardware.org/?probe=2c41f563a1) | Feb 19, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c32182253e](https://linux-hardware.org/?probe=c32182253e) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | Desktop     | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [03952a6c01](https://linux-hardware.org/?probe=03952a6c01) | Feb 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [ff9cd473da](https://linux-hardware.org/?probe=ff9cd473da) | Feb 18, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [22b75dc114](https://linux-hardware.org/?probe=22b75dc114) | Feb 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d0bb58e003](https://linux-hardware.org/?probe=d0bb58e003) | Feb 18, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [595103a203](https://linux-hardware.org/?probe=595103a203) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | Notebook    | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0cd82bf0c0](https://linux-hardware.org/?probe=0cd82bf0c0) | Feb 17, 2023 |
| AAEON         | PICO-APL3 V1.0              | Desktop     | [4ef4f86a2e](https://linux-hardware.org/?probe=4ef4f86a2e) | Feb 17, 2023 |
| Acer          | Batman A01                  | Desktop     | [d7aaa8f1c8](https://linux-hardware.org/?probe=d7aaa8f1c8) | Feb 17, 2023 |
| Dell          | Latitude E5450              | Notebook    | [cd7e5d61f2](https://linux-hardware.org/?probe=cd7e5d61f2) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Dell          | Latitude E6410              | Notebook    | [58d4c40618](https://linux-hardware.org/?probe=58d4c40618) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3042108dae](https://linux-hardware.org/?probe=3042108dae) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [62503d2494](https://linux-hardware.org/?probe=62503d2494) | Feb 16, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [146c38cbdf](https://linux-hardware.org/?probe=146c38cbdf) | Feb 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [cec962a8f4](https://linux-hardware.org/?probe=cec962a8f4) | Feb 16, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [ba59b583d2](https://linux-hardware.org/?probe=ba59b583d2) | Feb 16, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [37eb433eb3](https://linux-hardware.org/?probe=37eb433eb3) | Feb 15, 2023 |
| HP            | 1497                        | Desktop     | [1d55830595](https://linux-hardware.org/?probe=1d55830595) | Feb 15, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [5b6ce8f332](https://linux-hardware.org/?probe=5b6ce8f332) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [178ef8e028](https://linux-hardware.org/?probe=178ef8e028) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [88703a5913](https://linux-hardware.org/?probe=88703a5913) | Feb 15, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [02bd82be1d](https://linux-hardware.org/?probe=02bd82be1d) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [6650047151](https://linux-hardware.org/?probe=6650047151) | Feb 15, 2023 |
| Linx          | LINX1010B                   | Notebook    | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac367ae940](https://linux-hardware.org/?probe=ac367ae940) | Feb 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a5e9084f61](https://linux-hardware.org/?probe=a5e9084f61) | Feb 14, 2023 |
| Unknown       | T3 MRD                      | Notebook    | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [84a46ec9ce](https://linux-hardware.org/?probe=84a46ec9ce) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [e362a7551c](https://linux-hardware.org/?probe=e362a7551c) | Feb 14, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [636997044b](https://linux-hardware.org/?probe=636997044b) | Feb 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [ed459f2bf2](https://linux-hardware.org/?probe=ed459f2bf2) | Feb 13, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [dfb5b14f25](https://linux-hardware.org/?probe=dfb5b14f25) | Feb 13, 2023 |
| Dell          | Latitude E6530              | Notebook    | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [2cb0dc3d69](https://linux-hardware.org/?probe=2cb0dc3d69) | Feb 13, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [6ab285c781](https://linux-hardware.org/?probe=6ab285c781) | Feb 13, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [bb037d75a7](https://linux-hardware.org/?probe=bb037d75a7) | Feb 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [762dd6fa2e](https://linux-hardware.org/?probe=762dd6fa2e) | Feb 13, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [dcf82ccac5](https://linux-hardware.org/?probe=dcf82ccac5) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [cd29998b19](https://linux-hardware.org/?probe=cd29998b19) | Feb 13, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [8407710a28](https://linux-hardware.org/?probe=8407710a28) | Feb 12, 2023 |
| Acer          | H57M01                      | Desktop     | [4efe549cf2](https://linux-hardware.org/?probe=4efe549cf2) | Feb 12, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [4f04a42167](https://linux-hardware.org/?probe=4f04a42167) | Feb 12, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Toshiba       | Satellite Pro C850-10N      | Notebook    | [d45ac3e79c](https://linux-hardware.org/?probe=d45ac3e79c) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [60fed002e2](https://linux-hardware.org/?probe=60fed002e2) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| HP            | 82A2                        | Desktop     | [fe327d8caa](https://linux-hardware.org/?probe=fe327d8caa) | Feb 11, 2023 |
| Acer          | TravelMate P253             | Notebook    | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [61d03fad19](https://linux-hardware.org/?probe=61d03fad19) | Feb 10, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [ddde9bf34e](https://linux-hardware.org/?probe=ddde9bf34e) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| Dell          | Precision M4700             | Notebook    | [74f62c6131](https://linux-hardware.org/?probe=74f62c6131) | Feb 10, 2023 |
| Dell          | Precision M4700             | Notebook    | [797b766595](https://linux-hardware.org/?probe=797b766595) | Feb 10, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a166b37ae5](https://linux-hardware.org/?probe=a166b37ae5) | Feb 10, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [c9ed530a00](https://linux-hardware.org/?probe=c9ed530a00) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | Notebook    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [3209372a9d](https://linux-hardware.org/?probe=3209372a9d) | Feb 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f1a3a69ca](https://linux-hardware.org/?probe=9f1a3a69ca) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [9523b275e8](https://linux-hardware.org/?probe=9523b275e8) | Feb 09, 2023 |
| Dell          | Latitude 5511               | Notebook    | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [c9dd7aae2e](https://linux-hardware.org/?probe=c9dd7aae2e) | Feb 08, 2023 |
| Dell          | Latitude E6330              | Notebook    | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [a1c831925b](https://linux-hardware.org/?probe=a1c831925b) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [86c4416049](https://linux-hardware.org/?probe=86c4416049) | Feb 08, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [fa77bac136](https://linux-hardware.org/?probe=fa77bac136) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [35cb1bce53](https://linux-hardware.org/?probe=35cb1bce53) | Feb 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| Dell          | 0CRH6C A00                  | Desktop     | [fe0e64b291](https://linux-hardware.org/?probe=fe0e64b291) | Feb 08, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [de9e7b35a2](https://linux-hardware.org/?probe=de9e7b35a2) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [ce120b023c](https://linux-hardware.org/?probe=ce120b023c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| HP            | 85A0                        | All in one  | [8b7cfba471](https://linux-hardware.org/?probe=8b7cfba471) | Feb 07, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [397ff2069f](https://linux-hardware.org/?probe=397ff2069f) | Feb 07, 2023 |
| Dell          | 08DM12 A00                  | Server      | [4fcfb3fb2a](https://linux-hardware.org/?probe=4fcfb3fb2a) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | Notebook    | [aea2246107](https://linux-hardware.org/?probe=aea2246107) | Feb 06, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | Notebook    | [24d1d2fa52](https://linux-hardware.org/?probe=24d1d2fa52) | Feb 06, 2023 |
| Google        | Samus                       | Notebook    | [0817ec0be1](https://linux-hardware.org/?probe=0817ec0be1) | Feb 06, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [0be0961649](https://linux-hardware.org/?probe=0be0961649) | Feb 06, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5e59abda6e](https://linux-hardware.org/?probe=5e59abda6e) | Feb 06, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [a50f302f00](https://linux-hardware.org/?probe=a50f302f00) | Feb 06, 2023 |
| Acer          | TravelMate P253             | Notebook    | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [6c09a62b19](https://linux-hardware.org/?probe=6c09a62b19) | Feb 06, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [67d2b1fd55](https://linux-hardware.org/?probe=67d2b1fd55) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ba0666ad0b](https://linux-hardware.org/?probe=ba0666ad0b) | Feb 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [770e825eba](https://linux-hardware.org/?probe=770e825eba) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [5755b9feb0](https://linux-hardware.org/?probe=5755b9feb0) | Feb 05, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [bb6bee6af9](https://linux-hardware.org/?probe=bb6bee6af9) | Feb 05, 2023 |
| AZW           | SER                         | Mini pc     | [dd0c654d95](https://linux-hardware.org/?probe=dd0c654d95) | Feb 04, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [4d2872e685](https://linux-hardware.org/?probe=4d2872e685) | Feb 04, 2023 |
| GEO           | GeoBook 240                 | Notebook    | [861adcda52](https://linux-hardware.org/?probe=861adcda52) | Feb 04, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [b85e438d00](https://linux-hardware.org/?probe=b85e438d00) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| GEO           | GeoBook 140                 | Notebook    | [a91fdaa5da](https://linux-hardware.org/?probe=a91fdaa5da) | Feb 04, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [a4b17f9deb](https://linux-hardware.org/?probe=a4b17f9deb) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | Notebook    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [495ff876cf](https://linux-hardware.org/?probe=495ff876cf) | Feb 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [395e2c6424](https://linux-hardware.org/?probe=395e2c6424) | Feb 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [e23aca8e4b](https://linux-hardware.org/?probe=e23aca8e4b) | Feb 03, 2023 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [ea223a4d57](https://linux-hardware.org/?probe=ea223a4d57) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [1d3a68b4a0](https://linux-hardware.org/?probe=1d3a68b4a0) | Feb 03, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [3fb480c029](https://linux-hardware.org/?probe=3fb480c029) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [198a217d13](https://linux-hardware.org/?probe=198a217d13) | Feb 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [019540839e](https://linux-hardware.org/?probe=019540839e) | Feb 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f544702336](https://linux-hardware.org/?probe=f544702336) | Feb 03, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [21227757d0](https://linux-hardware.org/?probe=21227757d0) | Feb 02, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [457faa2485](https://linux-hardware.org/?probe=457faa2485) | Feb 02, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [8bec95eb42](https://linux-hardware.org/?probe=8bec95eb42) | Feb 02, 2023 |
| Alienware     | M14xR2                      | Notebook    | [d7e3d61744](https://linux-hardware.org/?probe=d7e3d61744) | Feb 02, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [edf1e65f78](https://linux-hardware.org/?probe=edf1e65f78) | Feb 02, 2023 |
| HP            | 2ADE                        | Desktop     | [b3735eb6c9](https://linux-hardware.org/?probe=b3735eb6c9) | Feb 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a440e41d7](https://linux-hardware.org/?probe=6a440e41d7) | Feb 02, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0811d3d2f0](https://linux-hardware.org/?probe=0811d3d2f0) | Feb 02, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [33f2d92922](https://linux-hardware.org/?probe=33f2d92922) | Feb 02, 2023 |
| Acer          | Aspire one 1-132            | Notebook    | [d66a972aa9](https://linux-hardware.org/?probe=d66a972aa9) | Feb 02, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | Notebook    | [d7a5b537d9](https://linux-hardware.org/?probe=d7a5b537d9) | Feb 01, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [b13dd2d455](https://linux-hardware.org/?probe=b13dd2d455) | Feb 01, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [162e744903](https://linux-hardware.org/?probe=162e744903) | Feb 01, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3f9519f358](https://linux-hardware.org/?probe=3f9519f358) | Jan 31, 2023 |
| HP            | Sona                        | Notebook    | [36a3d72172](https://linux-hardware.org/?probe=36a3d72172) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [b029e941fb](https://linux-hardware.org/?probe=b029e941fb) | Jan 30, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [6c66b66a78](https://linux-hardware.org/?probe=6c66b66a78) | Jan 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [9568a6f43d](https://linux-hardware.org/?probe=9568a6f43d) | Jan 30, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8d62c84240](https://linux-hardware.org/?probe=8d62c84240) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7743588036](https://linux-hardware.org/?probe=7743588036) | Jan 30, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a05f6f2f6c](https://linux-hardware.org/?probe=a05f6f2f6c) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0082cca600](https://linux-hardware.org/?probe=0082cca600) | Jan 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [6d867d07e1](https://linux-hardware.org/?probe=6d867d07e1) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [bb0384d993](https://linux-hardware.org/?probe=bb0384d993) | Jan 30, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [380088c986](https://linux-hardware.org/?probe=380088c986) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [04ed0bd8b1](https://linux-hardware.org/?probe=04ed0bd8b1) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [873725bb74](https://linux-hardware.org/?probe=873725bb74) | Jan 29, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f489fe4f5d](https://linux-hardware.org/?probe=f489fe4f5d) | Jan 29, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [91ef57c9e5](https://linux-hardware.org/?probe=91ef57c9e5) | Jan 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a7b54907f](https://linux-hardware.org/?probe=5a7b54907f) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [845b3c6990](https://linux-hardware.org/?probe=845b3c6990) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d7469767f6](https://linux-hardware.org/?probe=d7469767f6) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [baf61affa2](https://linux-hardware.org/?probe=baf61affa2) | Jan 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c4877a8bc3](https://linux-hardware.org/?probe=c4877a8bc3) | Jan 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | Notebook    | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f447127e74](https://linux-hardware.org/?probe=f447127e74) | Jan 28, 2023 |
| HP            | 2B17                        | Desktop     | [8746c148c7](https://linux-hardware.org/?probe=8746c148c7) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [6d4ecb5a00](https://linux-hardware.org/?probe=6d4ecb5a00) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [f395c475c9](https://linux-hardware.org/?probe=f395c475c9) | Jan 27, 2023 |
| Dell          | 0CU409                      | Desktop     | [5da09834b4](https://linux-hardware.org/?probe=5da09834b4) | Jan 27, 2023 |
| Dell          | 0CU409                      | Desktop     | [06b8ea0f8e](https://linux-hardware.org/?probe=06b8ea0f8e) | Jan 27, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [4611591cc9](https://linux-hardware.org/?probe=4611591cc9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [e171a529b9](https://linux-hardware.org/?probe=e171a529b9) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [a0b14899a8](https://linux-hardware.org/?probe=a0b14899a8) | Jan 27, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [3963660171](https://linux-hardware.org/?probe=3963660171) | Jan 27, 2023 |
| HP            | 212A                        | Desktop     | [5b9c217d02](https://linux-hardware.org/?probe=5b9c217d02) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | Notebook    | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | 1497                        | Desktop     | [21a3e07346](https://linux-hardware.org/?probe=21a3e07346) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [de8222900d](https://linux-hardware.org/?probe=de8222900d) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | Notebook    | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [7fb86baa0e](https://linux-hardware.org/?probe=7fb86baa0e) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [fb83192f84](https://linux-hardware.org/?probe=fb83192f84) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [6faa58b4a1](https://linux-hardware.org/?probe=6faa58b4a1) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [f437e45107](https://linux-hardware.org/?probe=f437e45107) | Jan 26, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [3386aa1dce](https://linux-hardware.org/?probe=3386aa1dce) | Jan 25, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9dfb8ac7b0](https://linux-hardware.org/?probe=9dfb8ac7b0) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [64ccdd32f5](https://linux-hardware.org/?probe=64ccdd32f5) | Jan 25, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [68c58308b8](https://linux-hardware.org/?probe=68c58308b8) | Jan 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [0d073c35f4](https://linux-hardware.org/?probe=0d073c35f4) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c8c9f53754](https://linux-hardware.org/?probe=c8c9f53754) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [3ffb5ed458](https://linux-hardware.org/?probe=3ffb5ed458) | Jan 24, 2023 |
| ASUSTek       | Z87-WS                      | Desktop     | [da3028df45](https://linux-hardware.org/?probe=da3028df45) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [97ca64cad1](https://linux-hardware.org/?probe=97ca64cad1) | Jan 23, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e9124adb70](https://linux-hardware.org/?probe=e9124adb70) | Jan 23, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [e1eeca8eab](https://linux-hardware.org/?probe=e1eeca8eab) | Jan 23, 2023 |
| Dell          | 0TP406                      | Desktop     | [e169f52d32](https://linux-hardware.org/?probe=e169f52d32) | Jan 23, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [4a6f5a78f9](https://linux-hardware.org/?probe=4a6f5a78f9) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f0cce92dd4](https://linux-hardware.org/?probe=f0cce92dd4) | Jan 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ac375e0fa7](https://linux-hardware.org/?probe=ac375e0fa7) | Jan 23, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [e4a2f02d89](https://linux-hardware.org/?probe=e4a2f02d89) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| HP            | 1905                        | Desktop     | [aaa3a9557c](https://linux-hardware.org/?probe=aaa3a9557c) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6419184e6e](https://linux-hardware.org/?probe=6419184e6e) | Jan 21, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [cf65d9f981](https://linux-hardware.org/?probe=cf65d9f981) | Jan 21, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d971cd0912](https://linux-hardware.org/?probe=d971cd0912) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fe4b24bf26](https://linux-hardware.org/?probe=fe4b24bf26) | Jan 21, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [db131543b4](https://linux-hardware.org/?probe=db131543b4) | Jan 21, 2023 |
| Lenovo        | 31900058 STD                | All in one  | [a079d28341](https://linux-hardware.org/?probe=a079d28341) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [97b14c6835](https://linux-hardware.org/?probe=97b14c6835) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | Notebook    | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [4269f0e624](https://linux-hardware.org/?probe=4269f0e624) | Jan 20, 2023 |
| HP            | Unknown                     | Notebook    | [b82faadc9d](https://linux-hardware.org/?probe=b82faadc9d) | Jan 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9301fd6936](https://linux-hardware.org/?probe=9301fd6936) | Jan 19, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [17e254a9ec](https://linux-hardware.org/?probe=17e254a9ec) | Jan 19, 2023 |
| HP            | 2AF3                        | Desktop     | [ac7c491076](https://linux-hardware.org/?probe=ac7c491076) | Jan 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [958e372993](https://linux-hardware.org/?probe=958e372993) | Jan 19, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [72e46e7bad](https://linux-hardware.org/?probe=72e46e7bad) | Jan 18, 2023 |
| Toshiba       | Satellite L70-C-12H         | Notebook    | [aa6340dd48](https://linux-hardware.org/?probe=aa6340dd48) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [bf606ed50a](https://linux-hardware.org/?probe=bf606ed50a) | Jan 18, 2023 |
| HP            | 3396                        | Desktop     | [456080afe8](https://linux-hardware.org/?probe=456080afe8) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4545e31cd2](https://linux-hardware.org/?probe=4545e31cd2) | Jan 18, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0ccab4b1e3](https://linux-hardware.org/?probe=0ccab4b1e3) | Jan 18, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [ff6ad7bf11](https://linux-hardware.org/?probe=ff6ad7bf11) | Jan 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [4b8096c4d2](https://linux-hardware.org/?probe=4b8096c4d2) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [6d93895cac](https://linux-hardware.org/?probe=6d93895cac) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [be9f4d6758](https://linux-hardware.org/?probe=be9f4d6758) | Jan 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [03c7a9b8a1](https://linux-hardware.org/?probe=03c7a9b8a1) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | Latitude E5440              | Notebook    | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [658ed38b10](https://linux-hardware.org/?probe=658ed38b10) | Jan 17, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [44f839ccbd](https://linux-hardware.org/?probe=44f839ccbd) | Jan 17, 2023 |
| Dell          | 07PXPY A02                  | Server      | [d56ca4a374](https://linux-hardware.org/?probe=d56ca4a374) | Jan 17, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [5012a7ccfc](https://linux-hardware.org/?probe=5012a7ccfc) | Jan 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [3dbc34a913](https://linux-hardware.org/?probe=3dbc34a913) | Jan 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d05225350d](https://linux-hardware.org/?probe=d05225350d) | Jan 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [aea2d1af0a](https://linux-hardware.org/?probe=aea2d1af0a) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [6445b08ce9](https://linux-hardware.org/?probe=6445b08ce9) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5ff11074e0](https://linux-hardware.org/?probe=5ff11074e0) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1c05ac2e28](https://linux-hardware.org/?probe=1c05ac2e28) | Jan 17, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ccce363b13](https://linux-hardware.org/?probe=ccce363b13) | Jan 17, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [83b98e5580](https://linux-hardware.org/?probe=83b98e5580) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [a75cdaa463](https://linux-hardware.org/?probe=a75cdaa463) | Jan 16, 2023 |
| Dell          | 0KRC95 A01                  | Desktop     | [4d39406938](https://linux-hardware.org/?probe=4d39406938) | Jan 16, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [64b395004f](https://linux-hardware.org/?probe=64b395004f) | Jan 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [5928caba96](https://linux-hardware.org/?probe=5928caba96) | Jan 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [798a9f2d30](https://linux-hardware.org/?probe=798a9f2d30) | Jan 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1644be7e2e](https://linux-hardware.org/?probe=1644be7e2e) | Jan 16, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [b1581dd523](https://linux-hardware.org/?probe=b1581dd523) | Jan 16, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [39b18604bf](https://linux-hardware.org/?probe=39b18604bf) | Jan 16, 2023 |
| Biostar       | H310MHP                     | Desktop     | [6495c0927b](https://linux-hardware.org/?probe=6495c0927b) | Jan 16, 2023 |
| Gigabyte      | EP45-DS4                    | Desktop     | [ef63262326](https://linux-hardware.org/?probe=ef63262326) | Jan 16, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [b73dacceb7](https://linux-hardware.org/?probe=b73dacceb7) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [31cf03aadd](https://linux-hardware.org/?probe=31cf03aadd) | Jan 15, 2023 |
| Gigabyte      | EP45-DS4                    | Desktop     | [9feae23438](https://linux-hardware.org/?probe=9feae23438) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | Notebook    | [3660b874bc](https://linux-hardware.org/?probe=3660b874bc) | Jan 15, 2023 |
| Sony          | VGN-NW26M                   | Notebook    | [5b62bf0146](https://linux-hardware.org/?probe=5b62bf0146) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [dca583bf2e](https://linux-hardware.org/?probe=dca583bf2e) | Jan 15, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [9ec7c970da](https://linux-hardware.org/?probe=9ec7c970da) | Jan 15, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0b80c9ddfb](https://linux-hardware.org/?probe=0b80c9ddfb) | Jan 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ba3e47247a](https://linux-hardware.org/?probe=ba3e47247a) | Jan 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [38d732c237](https://linux-hardware.org/?probe=38d732c237) | Jan 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [85048ce95d](https://linux-hardware.org/?probe=85048ce95d) | Jan 15, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [ca73cb526c](https://linux-hardware.org/?probe=ca73cb526c) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [0579b343cb](https://linux-hardware.org/?probe=0579b343cb) | Jan 15, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [2c4864375c](https://linux-hardware.org/?probe=2c4864375c) | Jan 14, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [20625ce99d](https://linux-hardware.org/?probe=20625ce99d) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [d113da489f](https://linux-hardware.org/?probe=d113da489f) | Jan 14, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [6b0992e510](https://linux-hardware.org/?probe=6b0992e510) | Jan 14, 2023 |
| Dell          | Inspiron 15 7510            | Notebook    | [67f4d14824](https://linux-hardware.org/?probe=67f4d14824) | Jan 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [4d74819919](https://linux-hardware.org/?probe=4d74819919) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| HP            | 805A                        | Desktop     | [5fdeec8d8a](https://linux-hardware.org/?probe=5fdeec8d8a) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [da829cbbc7](https://linux-hardware.org/?probe=da829cbbc7) | Jan 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [e4e7a1d245](https://linux-hardware.org/?probe=e4e7a1d245) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [c7baf1a126](https://linux-hardware.org/?probe=c7baf1a126) | Jan 14, 2023 |
| Alienware     | 17 R3                       | Notebook    | [d4cf3c4f4d](https://linux-hardware.org/?probe=d4cf3c4f4d) | Jan 14, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [0d1982257b](https://linux-hardware.org/?probe=0d1982257b) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [4e45aef7b0](https://linux-hardware.org/?probe=4e45aef7b0) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| Gigabyte      | B650E AORUS MASTER          | Desktop     | [7a9514375b](https://linux-hardware.org/?probe=7a9514375b) | Jan 13, 2023 |
| Dell          | Vostro 3549                 | Notebook    | [b6970533c4](https://linux-hardware.org/?probe=b6970533c4) | Jan 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [bb92fab8d3](https://linux-hardware.org/?probe=bb92fab8d3) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [41e26fa7a1](https://linux-hardware.org/?probe=41e26fa7a1) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| AZW           | Green G3                    | Desktop     | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [15129f4c39](https://linux-hardware.org/?probe=15129f4c39) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | Notebook    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [8309c81fdf](https://linux-hardware.org/?probe=8309c81fdf) | Jan 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [508efb9c99](https://linux-hardware.org/?probe=508efb9c99) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | Notebook    | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [76d5a2b12b](https://linux-hardware.org/?probe=76d5a2b12b) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ee7b0c337b](https://linux-hardware.org/?probe=ee7b0c337b) | Jan 12, 2023 |
| Google        | Link                        | Notebook    | [f73704d47a](https://linux-hardware.org/?probe=f73704d47a) | Jan 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c3b6b8b400](https://linux-hardware.org/?probe=c3b6b8b400) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [606cb1231b](https://linux-hardware.org/?probe=606cb1231b) | Jan 12, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [c10a0ccff5](https://linux-hardware.org/?probe=c10a0ccff5) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [2dadad3f74](https://linux-hardware.org/?probe=2dadad3f74) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [566725e667](https://linux-hardware.org/?probe=566725e667) | Jan 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [0001dd4164](https://linux-hardware.org/?probe=0001dd4164) | Jan 12, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a1f2661396](https://linux-hardware.org/?probe=a1f2661396) | Jan 11, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [96d07a0f9d](https://linux-hardware.org/?probe=96d07a0f9d) | Jan 11, 2023 |
| Lenovo        | ThinkPad W510 439123G       | Notebook    | [4fd1a4a217](https://linux-hardware.org/?probe=4fd1a4a217) | Jan 11, 2023 |
| Toshiba       | Satellite P50-C             | Notebook    | [1da161195b](https://linux-hardware.org/?probe=1da161195b) | Jan 11, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [680b0adb7b](https://linux-hardware.org/?probe=680b0adb7b) | Jan 11, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f0ba373485](https://linux-hardware.org/?probe=f0ba373485) | Jan 11, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [a25c10f2dd](https://linux-hardware.org/?probe=a25c10f2dd) | Jan 11, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [d079d53d80](https://linux-hardware.org/?probe=d079d53d80) | Jan 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [f91cb1b0e7](https://linux-hardware.org/?probe=f91cb1b0e7) | Jan 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [74cafb7a17](https://linux-hardware.org/?probe=74cafb7a17) | Jan 10, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [2dc4c5a4d8](https://linux-hardware.org/?probe=2dc4c5a4d8) | Jan 10, 2023 |
| HP            | ProBook 645 G2              | Notebook    | [1298e3efb0](https://linux-hardware.org/?probe=1298e3efb0) | Jan 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d1c53542d8](https://linux-hardware.org/?probe=d1c53542d8) | Jan 10, 2023 |
| Google        | Sparky360                   | Notebook    | [68e8848fba](https://linux-hardware.org/?probe=68e8848fba) | Jan 10, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Gigabyte      | H61N-USB3                   | Desktop     | [fd5a06c33f](https://linux-hardware.org/?probe=fd5a06c33f) | Jan 09, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [cae316a9ad](https://linux-hardware.org/?probe=cae316a9ad) | Jan 09, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [c434b0e62f](https://linux-hardware.org/?probe=c434b0e62f) | Jan 09, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f1edf0ce01](https://linux-hardware.org/?probe=f1edf0ce01) | Jan 09, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d903601066](https://linux-hardware.org/?probe=d903601066) | Jan 09, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [e86a06caea](https://linux-hardware.org/?probe=e86a06caea) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [22df883df4](https://linux-hardware.org/?probe=22df883df4) | Jan 09, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [0e705ced6f](https://linux-hardware.org/?probe=0e705ced6f) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [46ae333889](https://linux-hardware.org/?probe=46ae333889) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ab227bc376](https://linux-hardware.org/?probe=ab227bc376) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ff6d324723](https://linux-hardware.org/?probe=ff6d324723) | Jan 08, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [652db107e8](https://linux-hardware.org/?probe=652db107e8) | Jan 08, 2023 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a2a9c2e730](https://linux-hardware.org/?probe=a2a9c2e730) | Jan 08, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [c343ff064d](https://linux-hardware.org/?probe=c343ff064d) | Jan 08, 2023 |
| Gateway       | MX8716B                     | Notebook    | [b8b9890719](https://linux-hardware.org/?probe=b8b9890719) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [c7fc660dd7](https://linux-hardware.org/?probe=c7fc660dd7) | Jan 08, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9f15bde3f6](https://linux-hardware.org/?probe=9f15bde3f6) | Jan 08, 2023 |
| Dell          | Latitude 5290               | Notebook    | [1cd20e22fc](https://linux-hardware.org/?probe=1cd20e22fc) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [24b5e0ba8e](https://linux-hardware.org/?probe=24b5e0ba8e) | Jan 07, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f70583b34b](https://linux-hardware.org/?probe=f70583b34b) | Jan 07, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [57433162a0](https://linux-hardware.org/?probe=57433162a0) | Jan 07, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [9a59c21db0](https://linux-hardware.org/?probe=9a59c21db0) | Jan 07, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [e7ee03968d](https://linux-hardware.org/?probe=e7ee03968d) | Jan 07, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f6d81f424d](https://linux-hardware.org/?probe=f6d81f424d) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f9fe18f923](https://linux-hardware.org/?probe=f9fe18f923) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [ae3de33f00](https://linux-hardware.org/?probe=ae3de33f00) | Jan 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1239be31f9](https://linux-hardware.org/?probe=1239be31f9) | Jan 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [17c9c6288e](https://linux-hardware.org/?probe=17c9c6288e) | Jan 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e2304eaaf2](https://linux-hardware.org/?probe=e2304eaaf2) | Jan 07, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [f489c93a99](https://linux-hardware.org/?probe=f489c93a99) | Jan 06, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a456485950](https://linux-hardware.org/?probe=a456485950) | Jan 06, 2023 |
| Intel         | NUC8BEB J72693-305          | Mini pc     | [ad64106497](https://linux-hardware.org/?probe=ad64106497) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [ae45dfd30e](https://linux-hardware.org/?probe=ae45dfd30e) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cf94b53a8b](https://linux-hardware.org/?probe=cf94b53a8b) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b063be9f2e](https://linux-hardware.org/?probe=b063be9f2e) | Jan 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [4c54844f40](https://linux-hardware.org/?probe=4c54844f40) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [19a3a4f1c3](https://linux-hardware.org/?probe=19a3a4f1c3) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c1a3bf015a](https://linux-hardware.org/?probe=c1a3bf015a) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [abbff7d42a](https://linux-hardware.org/?probe=abbff7d42a) | Jan 04, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [5253826cac](https://linux-hardware.org/?probe=5253826cac) | Jan 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [671b852e29](https://linux-hardware.org/?probe=671b852e29) | Jan 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [73de62ce79](https://linux-hardware.org/?probe=73de62ce79) | Jan 03, 2023 |
| HP            | 83F3                        | Desktop     | [d53e207581](https://linux-hardware.org/?probe=d53e207581) | Jan 03, 2023 |
| MSI           | 2A9C                        | Desktop     | [48fc400420](https://linux-hardware.org/?probe=48fc400420) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [5ccb37c1d7](https://linux-hardware.org/?probe=5ccb37c1d7) | Jan 03, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [bd49b43116](https://linux-hardware.org/?probe=bd49b43116) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [aa875f1083](https://linux-hardware.org/?probe=aa875f1083) | Jan 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ed57548b6](https://linux-hardware.org/?probe=9ed57548b6) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [a3d030fdc2](https://linux-hardware.org/?probe=a3d030fdc2) | Jan 02, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [6a90fa6693](https://linux-hardware.org/?probe=6a90fa6693) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [ae42b505d4](https://linux-hardware.org/?probe=ae42b505d4) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [4a79c65764](https://linux-hardware.org/?probe=4a79c65764) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [6326869c9e](https://linux-hardware.org/?probe=6326869c9e) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [72a2446cd3](https://linux-hardware.org/?probe=72a2446cd3) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [03ca911bb7](https://linux-hardware.org/?probe=03ca911bb7) | Jan 01, 2023 |
| Advent        | Modena M201 Blue            | Notebook    | [abaae97a6f](https://linux-hardware.org/?probe=abaae97a6f) | Jan 01, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [8e5b57a9f8](https://linux-hardware.org/?probe=8e5b57a9f8) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| Packard Be... | EasyNote TM97               | Notebook    | [fad44d67ab](https://linux-hardware.org/?probe=fad44d67ab) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [10366e2627](https://linux-hardware.org/?probe=10366e2627) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [c0fb48bccb](https://linux-hardware.org/?probe=c0fb48bccb) | Dec 31, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [0749146323](https://linux-hardware.org/?probe=0749146323) | Dec 31, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [7c96c6776e](https://linux-hardware.org/?probe=7c96c6776e) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | 840A                        | Desktop     | [ad51866fe9](https://linux-hardware.org/?probe=ad51866fe9) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [294144217a](https://linux-hardware.org/?probe=294144217a) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [74b3157c61](https://linux-hardware.org/?probe=74b3157c61) | Dec 30, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [858fd62d74](https://linux-hardware.org/?probe=858fd62d74) | Dec 30, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [465d2da36b](https://linux-hardware.org/?probe=465d2da36b) | Dec 30, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [6aa950201f](https://linux-hardware.org/?probe=6aa950201f) | Dec 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7a685e175c](https://linux-hardware.org/?probe=7a685e175c) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [f6f61f1841](https://linux-hardware.org/?probe=f6f61f1841) | Dec 30, 2022 |
| Toshiba       | Satellite C850-1GL          | Notebook    | [796edd73f6](https://linux-hardware.org/?probe=796edd73f6) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [e7a5c8704b](https://linux-hardware.org/?probe=e7a5c8704b) | Dec 30, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [fa210be351](https://linux-hardware.org/?probe=fa210be351) | Dec 30, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [da812c8fa2](https://linux-hardware.org/?probe=da812c8fa2) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [d560c94d76](https://linux-hardware.org/?probe=d560c94d76) | Dec 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [08682d735c](https://linux-hardware.org/?probe=08682d735c) | Dec 30, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [9d71d087d8](https://linux-hardware.org/?probe=9d71d087d8) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [23d1e04f4c](https://linux-hardware.org/?probe=23d1e04f4c) | Dec 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [7b8f5e4379](https://linux-hardware.org/?probe=7b8f5e4379) | Dec 29, 2022 |
| Samsung       | NB30/N146                   | Notebook    | [7f9b976789](https://linux-hardware.org/?probe=7f9b976789) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c7bea2d0f](https://linux-hardware.org/?probe=0c7bea2d0f) | Dec 29, 2022 |
| PC Special... | PCX0DX                      | Notebook    | [0a33ad889c](https://linux-hardware.org/?probe=0a33ad889c) | Dec 28, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e9a313bb81](https://linux-hardware.org/?probe=e9a313bb81) | Dec 28, 2022 |
| HP            | 840A                        | Desktop     | [85b8b7f9b1](https://linux-hardware.org/?probe=85b8b7f9b1) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Alienware     | M11x R2                     | Notebook    | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [23c5689182](https://linux-hardware.org/?probe=23c5689182) | Dec 28, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [8e9e780028](https://linux-hardware.org/?probe=8e9e780028) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | 0AE4h                       | Desktop     | [c44d06efa6](https://linux-hardware.org/?probe=c44d06efa6) | Dec 28, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c62ee60963](https://linux-hardware.org/?probe=c62ee60963) | Dec 27, 2022 |
| Acer          | Swift SFX14-51G             | Notebook    | [16c5f2a610](https://linux-hardware.org/?probe=16c5f2a610) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [db0586ef7b](https://linux-hardware.org/?probe=db0586ef7b) | Dec 27, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [b74460d91c](https://linux-hardware.org/?probe=b74460d91c) | Dec 27, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1ab930dc6](https://linux-hardware.org/?probe=a1ab930dc6) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7a3513a2e1](https://linux-hardware.org/?probe=7a3513a2e1) | Dec 27, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [92825b79ee](https://linux-hardware.org/?probe=92825b79ee) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | Desktop     | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Alienware     | 07JNH0 A00                  | Desktop     | [41c418873b](https://linux-hardware.org/?probe=41c418873b) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c516dc209](https://linux-hardware.org/?probe=1c516dc209) | Dec 26, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Teclast       | X4                          | Tablet      | [d0b2244f5e](https://linux-hardware.org/?probe=d0b2244f5e) | Dec 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [cb4b71069c](https://linux-hardware.org/?probe=cb4b71069c) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c44d3c60da](https://linux-hardware.org/?probe=c44d3c60da) | Dec 25, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a46d6a7706](https://linux-hardware.org/?probe=a46d6a7706) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| Lenovo        | ThinkPad T450 20BUS3GN01    | Notebook    | [e88a11d2bb](https://linux-hardware.org/?probe=e88a11d2bb) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | Desktop     | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [778c642778](https://linux-hardware.org/?probe=778c642778) | Dec 25, 2022 |
| Dell          | 0D6H9T A00                  | Desktop     | [ef62b12cdb](https://linux-hardware.org/?probe=ef62b12cdb) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [91fb8b9a21](https://linux-hardware.org/?probe=91fb8b9a21) | Dec 24, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [ad65fe187a](https://linux-hardware.org/?probe=ad65fe187a) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [f540a3a892](https://linux-hardware.org/?probe=f540a3a892) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [85a74e99ff](https://linux-hardware.org/?probe=85a74e99ff) | Dec 23, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [0ca6dca505](https://linux-hardware.org/?probe=0ca6dca505) | Dec 23, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [7123056cea](https://linux-hardware.org/?probe=7123056cea) | Dec 23, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [a9e701a27a](https://linux-hardware.org/?probe=a9e701a27a) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | Notebook    | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [53678dec76](https://linux-hardware.org/?probe=53678dec76) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| Acer          | Aspire V5-571               | Notebook    | [b4de144f3e](https://linux-hardware.org/?probe=b4de144f3e) | Dec 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [877545dd5c](https://linux-hardware.org/?probe=877545dd5c) | Dec 22, 2022 |
| System76      | Lemur Pro                   | Notebook    | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [74f0c818d6](https://linux-hardware.org/?probe=74f0c818d6) | Dec 21, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [d63c07df34](https://linux-hardware.org/?probe=d63c07df34) | Dec 21, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [51b3c3725e](https://linux-hardware.org/?probe=51b3c3725e) | Dec 21, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [d565332e52](https://linux-hardware.org/?probe=d565332e52) | Dec 21, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [d2850b2e08](https://linux-hardware.org/?probe=d2850b2e08) | Dec 21, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [dbb80c6a3c](https://linux-hardware.org/?probe=dbb80c6a3c) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [422faa5041](https://linux-hardware.org/?probe=422faa5041) | Dec 20, 2022 |
| RM Educati... | RM                          | Notebook    | [758b521362](https://linux-hardware.org/?probe=758b521362) | Dec 20, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [5ab7ccb4cc](https://linux-hardware.org/?probe=5ab7ccb4cc) | Dec 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [870c784f85](https://linux-hardware.org/?probe=870c784f85) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Toshiba       | EQUIUM A300D                | Notebook    | [ffde5ccef4](https://linux-hardware.org/?probe=ffde5ccef4) | Dec 19, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [fdf00892eb](https://linux-hardware.org/?probe=fdf00892eb) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [0690e94fd6](https://linux-hardware.org/?probe=0690e94fd6) | Dec 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [0644973fc3](https://linux-hardware.org/?probe=0644973fc3) | Dec 19, 2022 |
| HP            | 620                         | Notebook    | [c5ed6ae3bf](https://linux-hardware.org/?probe=c5ed6ae3bf) | Dec 19, 2022 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [86cedc585c](https://linux-hardware.org/?probe=86cedc585c) | Dec 19, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [6c6dcce3d8](https://linux-hardware.org/?probe=6c6dcce3d8) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [e8b08e9f68](https://linux-hardware.org/?probe=e8b08e9f68) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [03db07e80d](https://linux-hardware.org/?probe=03db07e80d) | Dec 18, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [28dc03a1bc](https://linux-hardware.org/?probe=28dc03a1bc) | Dec 18, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5fee494e26](https://linux-hardware.org/?probe=5fee494e26) | Dec 17, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [d2076f2a7a](https://linux-hardware.org/?probe=d2076f2a7a) | Dec 17, 2022 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [b882d3e249](https://linux-hardware.org/?probe=b882d3e249) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [ec4188fb59](https://linux-hardware.org/?probe=ec4188fb59) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [d47eae36fe](https://linux-hardware.org/?probe=d47eae36fe) | Dec 17, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [2f27a6ddd3](https://linux-hardware.org/?probe=2f27a6ddd3) | Dec 16, 2022 |
| Intel         | X79M-S                      | Desktop     | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3a9c3088c9](https://linux-hardware.org/?probe=3a9c3088c9) | Dec 16, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [7c5cc51ed4](https://linux-hardware.org/?probe=7c5cc51ed4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0fe564693b](https://linux-hardware.org/?probe=0fe564693b) | Dec 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [bb07a9abda](https://linux-hardware.org/?probe=bb07a9abda) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [302ea6f1dd](https://linux-hardware.org/?probe=302ea6f1dd) | Dec 14, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [aac750d7d1](https://linux-hardware.org/?probe=aac750d7d1) | Dec 14, 2022 |
| HP            | 355 G2                      | Notebook    | [c826d17369](https://linux-hardware.org/?probe=c826d17369) | Dec 14, 2022 |
| HP            | 355 G2                      | Notebook    | [f785946641](https://linux-hardware.org/?probe=f785946641) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [9330717977](https://linux-hardware.org/?probe=9330717977) | Dec 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [719a73ae26](https://linux-hardware.org/?probe=719a73ae26) | Dec 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [ca2ba2d622](https://linux-hardware.org/?probe=ca2ba2d622) | Dec 13, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [47d6df705b](https://linux-hardware.org/?probe=47d6df705b) | Dec 13, 2022 |
| ECS           | GeForce7050M-M              | Desktop     | [118a28442e](https://linux-hardware.org/?probe=118a28442e) | Dec 13, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [16d5f27d87](https://linux-hardware.org/?probe=16d5f27d87) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [221e900b1c](https://linux-hardware.org/?probe=221e900b1c) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4be6aa4b7a](https://linux-hardware.org/?probe=4be6aa4b7a) | Dec 13, 2022 |
| Lenovo        | ThinkPad T400 647419G       | Notebook    | [a73b681605](https://linux-hardware.org/?probe=a73b681605) | Dec 13, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [bc4a9d103c](https://linux-hardware.org/?probe=bc4a9d103c) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [5357e778aa](https://linux-hardware.org/?probe=5357e778aa) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [d198c7fc5e](https://linux-hardware.org/?probe=d198c7fc5e) | Dec 11, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [eb171830a5](https://linux-hardware.org/?probe=eb171830a5) | Dec 11, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5073afb493](https://linux-hardware.org/?probe=5073afb493) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Acer          | Aspire V5-573               | Notebook    | [1d88db5ee2](https://linux-hardware.org/?probe=1d88db5ee2) | Dec 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1126      | 15.24%  |
| Ubuntu 18.04       | 598       | 8.09%   |
| Ubuntu 22.04       | 350       | 4.74%   |
| Zorin 16           | 182       | 2.46%   |
| Debian 11          | 152       | 2.06%   |
| OpenMandriva 4.3   | 139       | 1.88%   |
| OpenMandriva 4.2   | 133       | 1.8%    |
| Arch Rolling       | 128       | 1.73%   |
| Linux Mint 20.3    | 113       | 1.53%   |
| Linux Mint 20.2    | 112       | 1.52%   |
| Linux Mint 19.3    | 111       | 1.5%    |
| KDE neon 20.04     | 111       | 1.5%    |
| Pop!_OS 22.04      | 110       | 1.49%   |
| Pop!_OS 20.04      | 108       | 1.46%   |
| Manjaro            | 108       | 1.46%   |
| Ubuntu 19.04       | 105       | 1.42%   |
| Ubuntu 20.10       | 100       | 1.35%   |
| Pop!_OS 21.04      | 100       | 1.35%   |
| Arch               | 97        | 1.31%   |
| Ubuntu 21.10       | 94        | 1.27%   |
| ArcoLinux Rolling  | 93        | 1.26%   |
| Zorin 15           | 91        | 1.23%   |
| Ubuntu 19.10       | 89        | 1.2%    |
| Pop!_OS 20.10      | 86        | 1.16%   |
| Linux Mint 20.1    | 85        | 1.15%   |
| Ubuntu 21.04       | 81        | 1.1%    |
| OpenMandriva 23.01 | 77        | 1.04%   |
| Xubuntu 20.04      | 76        | 1.03%   |
| Linux Mint 20      | 67        | 0.91%   |
| Fedora 36          | 66        | 0.89%   |
| Fedora 34          | 60        | 0.81%   |
| Pop!_OS 21.10      | 57        | 0.77%   |
| Fedora 35          | 57        | 0.77%   |
| Ubuntu 18.10       | 56        | 0.76%   |
| Kubuntu 20.04      | 56        | 0.76%   |
| Fedora 37          | 56        | 0.76%   |
| Linux Mint 21.1    | 53        | 0.72%   |
| Linux Mint 21      | 48        | 0.65%   |
| Fedora 33          | 48        | 0.65%   |
| Fedora 31          | 48        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2566      | 36.5%   |
| Linux Mint    | 618       | 8.79%   |
| Pop!_OS       | 438       | 6.23%   |
| OpenMandriva  | 403       | 5.73%   |
| Fedora        | 376       | 5.35%   |
| Zorin         | 283       | 4.03%   |
| Debian        | 250       | 3.56%   |
| Manjaro       | 224       | 3.19%   |
| Arch          | 223       | 3.17%   |
| Kubuntu       | 149       | 2.12%   |
| KDE neon      | 143       | 2.03%   |
| Xubuntu       | 141       | 2.01%   |
| ArcoLinux     | 96        | 1.37%   |
| SteamOS       | 81        | 1.15%   |
| ROSA          | 77        | 1.1%    |
| Elementary    | 71        | 1.01%   |
| Gentoo        | 67        | 0.95%   |
| openSUSE      | 64        | 0.91%   |
| Ubuntu MATE   | 63        | 0.9%    |
| Endless       | 54        | 0.77%   |
| Lubuntu       | 51        | 0.73%   |
| Ubuntu Unity  | 49        | 0.7%    |
| Clear Linux   | 45        | 0.64%   |
| Kali          | 43        | 0.61%   |
| BlackPanther  | 41        | 0.58%   |
| CentOS        | 26        | 0.37%   |
| LMDE          | 25        | 0.36%   |
| MX            | 23        | 0.33%   |
| EndeavourOS   | 23        | 0.33%   |
| Ubuntu Budgie | 22        | 0.31%   |
| Garuda Linux  | 21        | 0.3%    |
| Raspbian      | 20        | 0.28%   |
| Nobara        | 17        | 0.24%   |
| RHEL          | 16        | 0.23%   |
| Peppermint    | 16        | 0.23%   |
| Parrot        | 13        | 0.18%   |
| Slackware     | 12        | 0.17%   |
| NixOS         | 10        | 0.14%   |
| Alpine        | 9         | 0.13%   |
| Reborn OS     | 7         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.85%   |
| 5.16.7-desktop-1omv4003  | 133       | 1.61%   |
| 5.10.14-desktop-1omv4002 | 130       | 1.58%   |
| 5.4.0-48-generic         | 81        | 0.98%   |
| 5.4.0-52-generic         | 76        | 0.92%   |
| 5.4.0-29-generic         | 73        | 0.89%   |
| 5.15.0-56-generic        | 73        | 0.89%   |
| 5.4.0-26-generic         | 70        | 0.85%   |
| 6.1.1-desktop-1omv2290   | 69        | 0.84%   |
| 5.3.0-28-generic         | 65        | 0.79%   |
| 5.15.0-52-generic        | 65        | 0.79%   |
| 5.15.0-46-generic        | 64        | 0.78%   |
| 5.15.0-58-generic        | 63        | 0.76%   |
| 5.3.0-40-generic         | 60        | 0.73%   |
| 5.4.0-40-generic         | 53        | 0.64%   |
| 5.4.0-37-generic         | 51        | 0.62%   |
| 5.11.0-27-generic        | 51        | 0.62%   |
| 5.4.0-58-generic         | 50        | 0.61%   |
| 5.4.0-65-generic         | 45        | 0.55%   |
| 5.4.0-33-generic         | 45        | 0.55%   |
| 5.11.0-38-generic        | 45        | 0.55%   |
| 5.0.0-32-generic         | 45        | 0.55%   |
| 5.4.0-91-generic         | 43        | 0.52%   |
| 5.13.0-7614-generic      | 43        | 0.52%   |
| 5.11.0-25-generic        | 43        | 0.52%   |
| 5.19.0-35-generic        | 42        | 0.51%   |
| 5.4.0-7634-generic       | 41        | 0.5%    |
| 5.4.0-54-generic         | 41        | 0.5%    |
| 5.3.0-46-generic         | 41        | 0.5%    |
| 5.4.0-74-generic         | 40        | 0.49%   |
| 5.4.0-66-generic         | 40        | 0.49%   |
| 5.8.0-7630-generic       | 39        | 0.47%   |
| 5.8.0-43-generic         | 39        | 0.47%   |
| 5.11.0-7620-generic      | 39        | 0.47%   |
| 5.0.0-37-generic         | 39        | 0.47%   |
| 5.15.0-48-generic        | 38        | 0.46%   |
| 5.13.0-28-generic        | 38        | 0.46%   |
| 5.11.0-40-generic        | 38        | 0.46%   |
| 5.3.0-42-generic         | 37        | 0.45%   |
| 5.11.0-43-generic        | 37        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1495      | 19.53%  |
| 5.15.0  | 621       | 8.11%   |
| 5.11.0  | 455       | 5.95%   |
| 5.8.0   | 448       | 5.85%   |
| 5.13.0  | 444       | 5.8%    |
| 4.15.0  | 417       | 5.45%   |
| 5.3.0   | 374       | 4.89%   |
| 5.0.0   | 244       | 3.19%   |
| 4.18.0  | 181       | 2.37%   |
| 5.10.0  | 177       | 2.31%   |
| 5.19.0  | 149       | 1.95%   |
| 5.16.7  | 134       | 1.75%   |
| 5.10.14 | 130       | 1.7%    |
| 6.1.1   | 74        | 0.97%   |
| 4.19.0  | 57        | 0.74%   |
| 5.17.5  | 35        | 0.46%   |
| 5.14.0  | 33        | 0.43%   |
| 4.18.16 | 32        | 0.42%   |
| 6.0.0   | 29        | 0.38%   |
| 6.0.12  | 26        | 0.34%   |
| 4.9.60  | 26        | 0.34%   |
| 6.0.6   | 25        | 0.33%   |
| 5.9.16  | 25        | 0.33%   |
| 5.18.0  | 22        | 0.29%   |
| 4.4.0   | 21        | 0.27%   |
| 6.2.6   | 19        | 0.25%   |
| 5.17.1  | 19        | 0.25%   |
| 5.18.12 | 18        | 0.24%   |
| 5.16.11 | 18        | 0.24%   |
| 5.15.12 | 17        | 0.22%   |
| 5.13.12 | 17        | 0.22%   |
| 5.7.0   | 16        | 0.21%   |
| 5.16.13 | 16        | 0.21%   |
| 5.16.0  | 16        | 0.21%   |
| 4.9.20  | 16        | 0.21%   |
| 6.1.9   | 15        | 0.2%    |
| 5.6.14  | 15        | 0.2%    |
| 5.17.0  | 15        | 0.2%    |
| 5.15.15 | 15        | 0.2%    |
| 5.12.4  | 15        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1586      | 21.01%  |
| 5.15    | 809       | 10.72%  |
| 5.8     | 535       | 7.09%   |
| 5.13    | 530       | 7.02%   |
| 5.11    | 513       | 6.8%    |
| 5.10    | 440       | 5.83%   |
| 5.3     | 424       | 5.62%   |
| 4.15    | 419       | 5.55%   |
| 5.0     | 254       | 3.37%   |
| 5.16    | 243       | 3.22%   |
| 5.19    | 238       | 3.15%   |
| 4.18    | 216       | 2.86%   |
| 6.1     | 184       | 2.44%   |
| 6.0     | 149       | 1.97%   |
| 5.17    | 106       | 1.4%    |
| 5.14    | 102       | 1.35%   |
| 5.9     | 95        | 1.26%   |
| 5.18    | 93        | 1.23%   |
| 4.19    | 89        | 1.18%   |
| 5.12    | 88        | 1.17%   |
| 5.6     | 76        | 1.01%   |
| 4.9     | 72        | 0.95%   |
| 5.7     | 68        | 0.9%    |
| 6.2     | 58        | 0.77%   |
| 5.5     | 42        | 0.56%   |
| 4.4     | 25        | 0.33%   |
| 5.2     | 23        | 0.3%    |
| 5.1     | 16        | 0.21%   |
| 4.14    | 10        | 0.13%   |
| 4.1     | 9         | 0.12%   |
| 3.10    | 8         | 0.11%   |
| 4.20    | 5         | 0.07%   |
| 4.13    | 5         | 0.07%   |
| 3.13    | 4         | 0.05%   |
| 4.16    | 3         | 0.04%   |
| 4.12    | 3         | 0.04%   |
| 4.8     | 2         | 0.03%   |
| 6.3     | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| 4.6     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6485      | 96.09%  |
| i686    | 174       | 2.58%   |
| aarch64 | 65        | 0.96%   |
| armv7l  | 24        | 0.36%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3230      | 45.62%  |
| KDE5             | 1084      | 15.31%  |
| Unknown          | 931       | 13.15%  |
| X-Cinnamon       | 498       | 7.03%   |
| XFCE             | 466       | 6.58%   |
| MATE             | 181       | 2.56%   |
| KDE              | 175       | 2.47%   |
| Cinnamon         | 86        | 1.21%   |
| Pantheon         | 67        | 0.95%   |
| Unity            | 51        | 0.72%   |
| LXDE             | 47        | 0.66%   |
| LXQt             | 46        | 0.65%   |
| KDE4             | 36        | 0.51%   |
| Budgie           | 31        | 0.44%   |
| i3               | 29        | 0.41%   |
| GNOME Flashback  | 25        | 0.35%   |
| Deepin           | 13        | 0.18%   |
| sway             | 12        | 0.17%   |
| Openbox          | 11        | 0.16%   |
| GNOME Classic    | 9         | 0.13%   |
| qtile            | 8         | 0.11%   |
| awesome          | 8         | 0.11%   |
| lightdm-xsession | 7         | 0.1%    |
| xmonad           | 5         | 0.07%   |
| bspwm            | 5         | 0.07%   |
| trinity          | 3         | 0.04%   |
| DWM              | 3         | 0.04%   |
| i3-with-shmlog   | 2         | 0.03%   |
| enlightenment    | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |
| icewm            | 1         | 0.01%   |
| Hyprland         | 1         | 0.01%   |
| GNUstep          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5422      | 78.23%  |
| Wayland | 883       | 12.74%  |
| Unknown | 461       | 6.65%   |
| Tty     | 164       | 2.37%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3978      | 56.5%   |
| SDDM    | 903       | 12.82%  |
| GDM     | 695       | 9.87%   |
| GDM3    | 640       | 9.09%   |
| LightDM | 554       | 7.87%   |
| TDM     | 197       | 2.8%    |
| KDM     | 35        | 0.5%    |
| XDM     | 15        | 0.21%   |
| LXDM    | 8         | 0.11%   |
| Ly      | 6         | 0.09%   |
| SLiM    | 4         | 0.06%   |
| GREETD  | 2         | 0.03%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 4969      | 71.82%  |
| en_US          | 828       | 11.97%  |
| Unknown        | 812       | 11.74%  |
| C              | 102       | 1.47%   |
| pl_PL          | 56        | 0.81%   |
| ru_RU          | 13        | 0.19%   |
| POSIX          | 13        | 0.19%   |
| de_DE          | 12        | 0.17%   |
| it_IT          | 10        | 0.14%   |
| en_IE          | 10        | 0.14%   |
| en_CA          | 10        | 0.14%   |
| fr_FR          | 9         | 0.13%   |
| ro_RO          | 6         | 0.09%   |
| en_IN          | 6         | 0.09%   |
| cs_CZ          | 6         | 0.09%   |
| hu_HU          | 5         | 0.07%   |
| es_ES          | 5         | 0.07%   |
| en_AU          | 5         | 0.07%   |
| pt_PT          | 4         | 0.06%   |
| C.UTF8         | 4         | 0.06%   |
| zh_CN          | 3         | 0.04%   |
| sk_SK          | 3         | 0.04%   |
| pt_BR          | 3         | 0.04%   |
| uk_UA          | 2         | 0.03%   |
| nl_NL          | 2         | 0.03%   |
| lt_LT          | 2         | 0.03%   |
| en_GB.iso88591 | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.01%   |
| tr_TR          | 1         | 0.01%   |
| ru_UA          | 1         | 0.01%   |
| nl_BE          | 1         | 0.01%   |
| fi_FI          | 1         | 0.01%   |
| et_EE          | 1         | 0.01%   |
| en_ZA          | 1         | 0.01%   |
| en_US.utf-8    | 1         | 0.01%   |
| en_IL          | 1         | 0.01%   |
| en_HK          | 1         | 0.01%   |
| en_GG          | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3650      | 52.92%  |
| EFI  | 3247      | 47.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5431      | 78.51%  |
| Btrfs    | 566       | 8.18%   |
| Overlay  | 471       | 6.81%   |
| Unknown  | 233       | 3.37%   |
| Xfs      | 99        | 1.43%   |
| Zfs      | 59        | 0.85%   |
| Ext2     | 20        | 0.29%   |
| Tmpfs    | 14        | 0.2%    |
| Ext3     | 11        | 0.16%   |
| F2fs     | 9         | 0.13%   |
| Aufs     | 2         | 0.03%   |
| Reiserfs | 1         | 0.01%   |
| Lvm      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4133      | 59.7%   |
| GPT     | 2168      | 31.32%  |
| MBR     | 622       | 8.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5858      | 84.95%  |
| Yes       | 1038      | 15.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4993      | 72.69%  |
| Yes       | 1876      | 27.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1063      | 15.76%  |
| ASUSTek Computer        | 977       | 14.49%  |
| Hewlett-Packard         | 851       | 12.62%  |
| Lenovo                  | 817       | 12.11%  |
| Gigabyte Technology     | 496       | 7.35%   |
| MSI                     | 371       | 5.5%    |
| Acer                    | 326       | 4.83%   |
| ASRock                  | 206       | 3.05%   |
| Apple                   | 197       | 2.92%   |
| Toshiba                 | 158       | 2.34%   |
| Intel                   | 120       | 1.78%   |
| Samsung Electronics     | 80        | 1.19%   |
| Valve                   | 73        | 1.08%   |
| Raspberry Pi Foundation | 71        | 1.05%   |
| Sony                    | 57        | 0.85%   |
| Unknown                 | 49        | 0.73%   |
| Fujitsu                 | 43        | 0.64%   |
| PC Specialist           | 42        | 0.62%   |
| HUAWEI                  | 41        | 0.61%   |
| Microsoft               | 40        | 0.59%   |
| Packard Bell            | 35        | 0.52%   |
| Google                  | 35        | 0.52%   |
| Notebook                | 30        | 0.44%   |
| Foxconn                 | 30        | 0.44%   |
| Alienware               | 26        | 0.39%   |
| Pegatron                | 21        | 0.31%   |
| Fujitsu Siemens         | 20        | 0.3%    |
| Star Labs               | 19        | 0.28%   |
| Razer                   | 19        | 0.28%   |
| AZW                     | 19        | 0.28%   |
| Medion                  | 17        | 0.25%   |
| GEO                     | 17        | 0.25%   |
| Biostar                 | 16        | 0.24%   |
| Linx                    | 14        | 0.21%   |
| Entroware               | 14        | 0.21%   |
| Dixonsxp                | 14        | 0.21%   |
| AMI                     | 13        | 0.19%   |
| TUXEDO                  | 11        | 0.16%   |
| Supermicro              | 10        | 0.15%   |
| Clevo                   | 10        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 73        | 1.08%   |
| Unknown                            | 72        | 1.07%   |
| ASUS All Series                    | 68        | 1.01%   |
| Dell OptiPlex 7010                 | 29        | 0.43%   |
| MSI MS-7C02                        | 26        | 0.39%   |
| RPi Raspberry Pi                   | 23        | 0.34%   |
| HP Pavilion g6                     | 23        | 0.34%   |
| Dell OptiPlex 755                  | 20        | 0.3%    |
| MSI MS-7C37                        | 19        | 0.28%   |
| HP Pavilion 15                     | 19        | 0.28%   |
| Dell OptiPlex 780                  | 19        | 0.28%   |
| ASUS TUF Gaming X570-PLUS          | 19        | 0.28%   |
| ASUS M5A78L-M/USB3                 | 19        | 0.28%   |
| ASUS ROG STRIX B450-F GAMING       | 18        | 0.27%   |
| Dell OptiPlex 790                  | 17        | 0.25%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 16        | 0.24%   |
| HP Notebook                        | 16        | 0.24%   |
| HP Pavilion Notebook               | 15        | 0.22%   |
| Dell XPS 15 7590                   | 15        | 0.22%   |
| Dell Inspiron 1545                 | 15        | 0.22%   |
| Gigabyte X570 AORUS ELITE          | 13        | 0.19%   |
| Gigabyte 970A-DS3P                 | 13        | 0.19%   |
| Dell XPS 15 9560                   | 13        | 0.19%   |
| Dell XPS 13 9370                   | 13        | 0.19%   |
| ASUS PRIME A320M-K                 | 13        | 0.19%   |
| Dell XPS 15 9570                   | 12        | 0.18%   |
| Dell XPS 13 9380                   | 12        | 0.18%   |
| Dell XPS 13 9360                   | 12        | 0.18%   |
| Dell Latitude E6400                | 12        | 0.18%   |
| Lenovo V145-15AST 81MT             | 11        | 0.16%   |
| Gigabyte GA-78LMT-USB3             | 11        | 0.16%   |
| Dell XPS 13 7390                   | 11        | 0.16%   |
| Dell OptiPlex 3020                 | 11        | 0.16%   |
| Dell Latitude E6410                | 11        | 0.16%   |
| Toshiba Satellite C660             | 10        | 0.15%   |
| MSI MS-7C91                        | 10        | 0.15%   |
| Microsoft Surface Pro 4            | 10        | 0.15%   |
| HP ProLiant MicroServer            | 10        | 0.15%   |
| Gigabyte GA-78LMT-USB3 6.0         | 10        | 0.15%   |
| Gigabyte A320M-S2H                 | 10        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 380       | 5.63%   |
| Dell Latitude          | 241       | 3.57%   |
| Acer Aspire            | 236       | 3.5%    |
| Dell Inspiron          | 225       | 3.34%   |
| Dell OptiPlex          | 191       | 2.83%   |
| Dell XPS               | 175       | 2.59%   |
| ASUS ROG               | 149       | 2.21%   |
| HP Pavilion            | 147       | 2.18%   |
| Toshiba Satellite      | 139       | 2.06%   |
| Lenovo IdeaPad         | 126       | 1.87%   |
| ASUS PRIME             | 118       | 1.75%   |
| HP EliteBook           | 100       | 1.48%   |
| Dell Precision         | 97        | 1.44%   |
| HP Compaq              | 92        | 1.36%   |
| Valve Jupiter          | 73        | 1.08%   |
| Unknown                | 72        | 1.07%   |
| RPi Raspberry          | 71        | 1.05%   |
| ASUS All               | 68        | 1.01%   |
| Lenovo ThinkCentre     | 64        | 0.95%   |
| HP Laptop              | 58        | 0.86%   |
| HP ProBook             | 57        | 0.85%   |
| ASUS TUF               | 54        | 0.8%    |
| ASUS VivoBook          | 51        | 0.76%   |
| HP ENVY                | 50        | 0.74%   |
| Dell Vostro            | 45        | 0.67%   |
| Lenovo Yoga            | 43        | 0.64%   |
| Microsoft Surface      | 40        | 0.59%   |
| HP ProLiant            | 34        | 0.5%    |
| Gigabyte X570          | 34        | 0.5%    |
| HP EliteDesk           | 28        | 0.42%   |
| ASUS M5A78L-M          | 28        | 0.42%   |
| MSI MS-7C02            | 26        | 0.39%   |
| HP Stream              | 26        | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 26        | 0.39%   |
| ASUS ZenBook           | 26        | 0.39%   |
| HP Spectre             | 25        | 0.37%   |
| Acer Swift             | 24        | 0.36%   |
| Lenovo ThinkBook       | 20        | 0.3%    |
| Lenovo Legion          | 20        | 0.3%    |
| Dell PowerEdge         | 20        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 657       | 9.74%   |
| 2019    | 593       | 8.79%   |
| 2020    | 551       | 8.17%   |
| 2012    | 542       | 8.04%   |
| 2013    | 480       | 7.12%   |
| 2011    | 455       | 6.75%   |
| 2017    | 452       | 6.7%    |
| 2014    | 417       | 6.18%   |
| 2021    | 374       | 5.55%   |
| 2010    | 369       | 5.47%   |
| 2015    | 365       | 5.41%   |
| 2016    | 341       | 5.06%   |
| 2009    | 281       | 4.17%   |
| 2008    | 271       | 4.02%   |
| 2022    | 213       | 3.16%   |
| 2007    | 185       | 2.74%   |
| 2006    | 82        | 1.22%   |
| Unknown | 70        | 1.04%   |
| 2005    | 26        | 0.39%   |
| 2023    | 8         | 0.12%   |
| 2004    | 6         | 0.09%   |
| 2003    | 3         | 0.04%   |
| 2002    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3424      | 50.77%  |
| Desktop        | 2711      | 40.2%   |
| Convertible    | 134       | 1.99%   |
| Mini pc        | 129       | 1.91%   |
| All in one     | 114       | 1.69%   |
| Tablet         | 90        | 1.33%   |
| System on chip | 82        | 1.22%   |
| Server         | 55        | 0.82%   |
| Phone          | 4         | 0.06%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6261      | 92.07%  |
| Enabled  | 539       | 7.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6689      | 99.18%  |
| Yes  | 55        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1513      | 22.04%  |
| 16.01-24.0      | 1470      | 21.41%  |
| 8.01-16.0       | 1201      | 17.49%  |
| 3.01-4.0        | 1193      | 17.38%  |
| 32.01-64.0      | 710       | 10.34%  |
| 1.01-2.0        | 302       | 4.4%    |
| 64.01-256.0     | 187       | 2.72%   |
| 2.01-3.0        | 120       | 1.75%   |
| 24.01-32.0      | 99        | 1.44%   |
| 0.51-1.0        | 56        | 0.82%   |
| More than 256.0 | 10        | 0.15%   |
| 0.01-0.5        | 5         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2833      | 37.45%  |
| 2.01-3.0    | 1855      | 24.52%  |
| 4.01-8.0    | 1002      | 13.25%  |
| 3.01-4.0    | 900       | 11.9%   |
| 0.51-1.0    | 494       | 6.53%   |
| 8.01-16.0   | 292       | 3.86%   |
| 0.01-0.5    | 105       | 1.39%   |
| 16.01-24.0  | 41        | 0.54%   |
| 24.01-32.0  | 19        | 0.25%   |
| 32.01-64.0  | 16        | 0.21%   |
| Unknown     | 4         | 0.05%   |
| 64.01-256.0 | 3         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3934      | 56.33%  |
| 2       | 1740      | 24.91%  |
| 3       | 573       | 8.2%    |
| 4       | 309       | 4.42%   |
| 5       | 169       | 2.42%   |
| 6       | 89        | 1.27%   |
| 0       | 72        | 1.03%   |
| 7       | 38        | 0.54%   |
| 8       | 15        | 0.21%   |
| 9       | 14        | 0.2%    |
| Unknown | 8         | 0.11%   |
| 11      | 7         | 0.1%    |
| 12      | 5         | 0.07%   |
| 10      | 5         | 0.07%   |
| 13      | 3         | 0.04%   |
| 21      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4016      | 58.89%  |
| Yes       | 2803      | 41.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5694      | 84.27%  |
| No        | 1063      | 15.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5143      | 75.6%   |
| No        | 1660      | 24.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3933      | 57.58%  |
| No        | 2898      | 42.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 6744      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 471       | 6.34%   |
| Manchester          | 162       | 2.18%   |
| Birmingham          | 124       | 1.67%   |
| Bristol             | 120       | 1.62%   |
| Glasgow             | 107       | 1.44%   |
| Edinburgh           | 99        | 1.33%   |
| Nottingham          | 94        | 1.27%   |
| Sheffield           | 93        | 1.25%   |
| Liverpool           | 85        | 1.14%   |
| Leeds               | 83        | 1.12%   |
| Reading             | 64        | 0.86%   |
| Norwich             | 61        | 0.82%   |
| Cambridge           | 61        | 0.82%   |
| Islington           | 59        | 0.79%   |
| Milton Keynes       | 53        | 0.71%   |
| Southampton         | 51        | 0.69%   |
| Derby               | 49        | 0.66%   |
| Croydon             | 48        | 0.65%   |
| Coventry            | 45        | 0.61%   |
| Leicester           | 42        | 0.57%   |
| Newcastle upon Tyne | 41        | 0.55%   |
| Aberdeen            | 41        | 0.55%   |
| Cardiff             | 40        | 0.54%   |
| Bradford            | 39        | 0.52%   |
| Wolverhampton       | 38        | 0.51%   |
| Oxford              | 38        | 0.51%   |
| Swindon             | 37        | 0.5%    |
| Gloucester          | 36        | 0.48%   |
| Brighton            | 36        | 0.48%   |
| York                | 35        | 0.47%   |
| Hackney             | 35        | 0.47%   |
| Wigan               | 34        | 0.46%   |
| Plymouth            | 34        | 0.46%   |
| Bolton              | 33        | 0.44%   |
| Walsall             | 31        | 0.42%   |
| Sunderland          | 31        | 0.42%   |
| Kensington          | 31        | 0.42%   |
| Harrow              | 30        | 0.4%    |
| Clapham             | 30        | 0.4%    |
| Stoke-on-Trent      | 29        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1551      | 2423   | 15.22%  |
| Seagate                     | 1538      | 2560   | 15.09%  |
| WDC                         | 1432      | 2354   | 14.05%  |
| Toshiba                     | 689       | 942    | 6.76%   |
| SanDisk                     | 604       | 812    | 5.93%   |
| Unknown                     | 553       | 755    | 5.43%   |
| Crucial                     | 541       | 776    | 5.31%   |
| Kingston                    | 428       | 583    | 4.2%    |
| Hitachi                     | 384       | 533    | 3.77%   |
| Intel                       | 210       | 285    | 2.06%   |
| SK hynix                    | 208       | 248    | 2.04%   |
| HGST                        | 161       | 235    | 1.58%   |
| Phison                      | 151       | 202    | 1.48%   |
| Micron Technology           | 108       | 129    | 1.06%   |
| Apple                       | 103       | 141    | 1.01%   |
| China                       | 100       | 137    | 0.98%   |
| A-DATA Technology           | 95        | 123    | 0.93%   |
| OCZ                         | 62        | 71     | 0.61%   |
| KIOXIA                      | 62        | 81     | 0.61%   |
| PNY                         | 61        | 76     | 0.6%    |
| Maxtor                      | 57        | 86     | 0.56%   |
| LITEON                      | 54        | 64     | 0.53%   |
| Silicon Motion              | 53        | 67     | 0.52%   |
| Transcend                   | 49        | 59     | 0.48%   |
| Corsair                     | 49        | 68     | 0.48%   |
| Phison Electronics          | 46        | 69     | 0.45%   |
| Fujitsu                     | 42        | 59     | 0.41%   |
| Micron/Crucial Technology   | 39        | 50     | 0.38%   |
| Unknown                     | 39        | 50     | 0.38%   |
| LITEONIT                    | 30        | 37     | 0.29%   |
| Integral                    | 26        | 31     | 0.26%   |
| JMicron Technology          | 25        | 37     | 0.25%   |
| Netac                       | 24        | 29     | 0.24%   |
| ASMT                        | 23        | 53     | 0.23%   |
| Patriot                     | 22        | 34     | 0.22%   |
| SABRENT                     | 21        | 23     | 0.21%   |
| Gigabyte Technology         | 19        | 26     | 0.19%   |
| SPCC                        | 17        | 29     | 0.17%   |
| Drevo                       | 17        | 28     | 0.17%   |
| Kingston Technology Company | 16        | 16     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 114       | 0.99%   |
| Samsung SSD 850 EVO 250GB                           | 87        | 0.76%   |
| Seagate ST3500312CS 500GB                           | 86        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 84        | 0.73%   |
| Samsung SSD 850 EVO 500GB                           | 75        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 73        | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                         | 72        | 0.63%   |
| Unknown MMC Card  64GB                              | 71        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 70        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                        | 69        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB                      | 66        | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 63        | 0.55%   |
| Samsung NVMe SSD Drive 500GB                        | 63        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 63        | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                      | 62        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                     | 58        | 0.51%   |
| Samsung SSD 860 EVO 1TB                             | 58        | 0.51%   |
| Unknown MMC Card  128GB                             | 57        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                        | 55        | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 54        | 0.47%   |
| Samsung NVMe SSD Drive 512GB                        | 54        | 0.47%   |
| Samsung NVMe SSD Drive 1TB                          | 50        | 0.44%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 49        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 48        | 0.42%   |
| Unknown SD/MMC/MS PRO 64GB                          | 42        | 0.37%   |
| Crucial CT250MX500SSD1 250GB                        | 42        | 0.37%   |
| Samsung SSD 840 EVO 250GB                           | 40        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 39        | 0.34%   |
| Unknown                                             | 39        | 0.34%   |
| Seagate Expansion+ 2TB                              | 38        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 38        | 0.33%   |
| HGST HTS721010A9E630 1TB                            | 37        | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 35        | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB                      | 35        | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB                      | 35        | 0.31%   |
| SanDisk SSD PLUS 240GB                              | 35        | 0.31%   |
| SanDisk NVMe SSD Drive 1TB                          | 35        | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 34        | 0.3%    |
| Toshiba MQ01ABF050 500GB                            | 34        | 0.3%    |
| Unknown MMC Card  16GB                              | 33        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1489      | 2455   | 35.72%  |
| WDC                 | 1122      | 1901   | 26.91%  |
| Toshiba             | 507       | 697    | 12.16%  |
| Hitachi             | 383       | 531    | 9.19%   |
| Samsung Electronics | 213       | 299    | 5.11%   |
| HGST                | 159       | 232    | 3.81%   |
| Unknown             | 49        | 65     | 1.18%   |
| Maxtor              | 47        | 75     | 1.13%   |
| Apple               | 47        | 57     | 1.13%   |
| Fujitsu             | 42        | 59     | 1.01%   |
| ASMT                | 22        | 52     | 0.53%   |
| SABRENT             | 20        | 22     | 0.48%   |
| Hewlett-Packard     | 15        | 50     | 0.36%   |
| USB3.0              | 9         | 14     | 0.22%   |
| ASMedia             | 7         | 13     | 0.17%   |
| WD MediaMax         | 3         | 3      | 0.07%   |
| USB                 | 3         | 3      | 0.07%   |
| HPE                 | 3         | 5      | 0.07%   |
| ASMT109x            | 3         | 5      | 0.07%   |
| LaCie               | 2         | 2      | 0.05%   |
| KESU                | 2         | 6      | 0.05%   |
| JMicron Technology  | 2         | 4      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 4      | 0.05%   |
| TrueNAS             | 1         | 3      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| External            | 1         | 1      | 0.02%   |
| Advantech           | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 779       | 1161   | 22.78%  |
| Crucial             | 496       | 722    | 14.5%   |
| SanDisk             | 410       | 525    | 11.99%  |
| Kingston            | 363       | 491    | 10.61%  |
| WDC                 | 187       | 257    | 5.47%   |
| China               | 95        | 132    | 2.78%   |
| Intel               | 86        | 98     | 2.51%   |
| A-DATA Technology   | 73        | 93     | 2.13%   |
| OCZ                 | 62        | 71     | 1.81%   |
| Toshiba             | 60        | 74     | 1.75%   |
| PNY                 | 58        | 69     | 1.7%    |
| Micron Technology   | 56        | 67     | 1.64%   |
| SK hynix            | 53        | 66     | 1.55%   |
| LITEON              | 53        | 63     | 1.55%   |
| Apple               | 46        | 60     | 1.35%   |
| Transcend           | 45        | 55     | 1.32%   |
| LITEONIT            | 30        | 37     | 0.88%   |
| Corsair             | 30        | 43     | 0.88%   |
| Integral            | 26        | 31     | 0.76%   |
| Netac               | 23        | 26     | 0.67%   |
| Patriot             | 22        | 34     | 0.64%   |
| Seagate             | 20        | 24     | 0.58%   |
| Drevo               | 17        | 28     | 0.5%    |
| Unknown             | 14        | 19     | 0.41%   |
| Gigabyte Technology | 14        | 19     | 0.41%   |
| Team                | 13        | 14     | 0.38%   |
| SPCC                | 13        | 25     | 0.38%   |
| Lexar               | 13        | 15     | 0.38%   |
| JMicron Technology  | 12        | 18     | 0.35%   |
| Vaseky              | 11        | 16     | 0.32%   |
| TO Exter            | 11        | 13     | 0.32%   |
| TCSUNBOW            | 11        | 17     | 0.32%   |
| KIOXIA-EXCERIA      | 11        | 15     | 0.32%   |
| ORTIAL              | 10        | 10     | 0.29%   |
| Maxtor              | 10        | 11     | 0.29%   |
| Unknown             | 8         | 9      | 0.23%   |
| KingDian            | 7         | 10     | 0.2%    |
| Star                | 6         | 7      | 0.18%   |
| Plextor             | 6         | 9      | 0.18%   |
| NGFF                | 6         | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3375      | 6584   | 37.87%  |
| SSD     | 2896      | 4657   | 32.49%  |
| NVMe    | 1993      | 2896   | 22.36%  |
| MMC     | 505       | 675    | 5.67%   |
| Unknown | 144       | 212    | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5074      | 10701  | 63.3%   |
| NVMe | 1988      | 2880   | 24.8%   |
| MMC  | 505       | 675    | 6.3%    |
| SAS  | 449       | 768    | 5.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3802      | 6292   | 56.1%   |
| 0.51-1.0        | 1786      | 2759   | 26.35%  |
| 1.01-2.0        | 654       | 1106   | 9.65%   |
| 3.01-4.0        | 182       | 351    | 2.69%   |
| 4.01-10.0       | 167       | 373    | 2.46%   |
| 2.01-3.0        | 164       | 302    | 2.42%   |
| 10.01-20.0      | 19        | 55     | 0.28%   |
| More than 100.0 | 2         | 2      | 0.03%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1938      | 27.01%  |
| 251-500        | 1409      | 19.64%  |
| 501-1000       | 1072      | 14.94%  |
| 1001-2000      | 562       | 7.83%   |
| 1-20           | 499       | 6.96%   |
| 51-100         | 464       | 6.47%   |
| More than 3000 | 440       | 6.13%   |
| 21-50          | 335       | 4.67%   |
| 2001-3000      | 228       | 3.18%   |
| Unknown        | 227       | 3.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2965      | 39.77%  |
| 21-50          | 1204      | 16.15%  |
| 101-250        | 880       | 11.8%   |
| 51-100         | 774       | 10.38%  |
| 251-500        | 543       | 7.28%   |
| 501-1000       | 370       | 4.96%   |
| 1001-2000      | 243       | 3.26%   |
| Unknown        | 227       | 3.04%   |
| More than 3000 | 163       | 2.19%   |
| 2001-3000      | 86        | 1.15%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 8         | 12     | 1.56%   |
| Seagate ST9500325AS 500GB                | 7         | 11     | 1.37%   |
| Seagate ST3500418AS 500GB                | 6         | 6      | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1.17%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.17%   |
| Seagate ST500DM002-1BD142 500GB          | 5         | 5      | 0.98%   |
| Seagate ST3500312CS 500GB                | 5         | 7      | 0.98%   |
| Samsung Electronics HD103UJ 1TB          | 5         | 7      | 0.98%   |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.78%   |
| Hitachi HTS547575A9E384 752GB            | 4         | 6      | 0.78%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.78%   |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.78%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 0.78%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.59%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.59%   |
| Toshiba MK1656GSY 160GB                  | 3         | 3      | 0.59%   |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB          | 3         | 3      | 0.59%   |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.59%   |
| Seagate ST2000DM001-1CH164 2TB           | 3         | 4      | 0.59%   |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.59%   |
| Samsung Electronics SSD 960 EVO 250GB    | 3         | 4      | 0.59%   |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.59%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 0.59%   |
| Intel SSDPEKKW512G7 512GB                | 3         | 5      | 0.59%   |
| Hitachi HUA723030ALA640 3TB              | 3         | 4      | 0.59%   |
| Hitachi HTS542512K9SA00 120GB            | 3         | 3      | 0.59%   |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.59%   |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.59%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.59%   |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.59%   |
| Crucial CT480M500SSD1 480GB              | 3         | 3      | 0.59%   |
| WDC WD800JD-00HKA0 80GB                  | 2         | 2      | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB              | 2         | 2      | 0.39%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2         | 2      | 0.39%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 2         | 3      | 0.39%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2         | 2      | 0.39%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.39%   |
| WDC WD2500BEVT-80A23T0 250GB             | 2         | 4      | 0.39%   |
| WDC WD2002FYPS-02W3B0 2TB                | 2         | 9      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 161    | 26.32%  |
| WDC                 | 99        | 156    | 20.04%  |
| Hitachi             | 61        | 85     | 12.35%  |
| Samsung Electronics | 42        | 54     | 8.5%    |
| Toshiba             | 31        | 37     | 6.28%   |
| Crucial             | 25        | 31     | 5.06%   |
| HGST                | 17        | 20     | 3.44%   |
| Intel               | 15        | 23     | 3.04%   |
| SanDisk             | 12        | 16     | 2.43%   |
| Kingston            | 8         | 10     | 1.62%   |
| SK hynix            | 6         | 6      | 1.21%   |
| Micron Technology   | 5         | 5      | 1.01%   |
| LITEON              | 5         | 5      | 1.01%   |
| A-DATA Technology   | 5         | 5      | 1.01%   |
| Maxtor              | 4         | 4      | 0.81%   |
| Fujitsu             | 4         | 4      | 0.81%   |
| Hewlett-Packard     | 3         | 3      | 0.61%   |
| Corsair             | 3         | 7      | 0.61%   |
| Unknown             | 2         | 2      | 0.4%    |
| OCZ                 | 2         | 2      | 0.4%    |
| Drevo               | 2         | 8      | 0.4%    |
| Zheino              | 1         | 2      | 0.2%    |
| WD MediaMax         | 1         | 1      | 0.2%    |
| VENO                | 1         | 1      | 0.2%    |
| Team                | 1         | 1      | 0.2%    |
| faspeed             | 1         | 1      | 0.2%    |
| China               | 1         | 1      | 0.2%    |
| BIWIN               | 1         | 1      | 0.2%    |
| BAITITON            | 1         | 4      | 0.2%    |
| Apple               | 1         | 2      | 0.2%    |
| Apacer              | 1         | 1      | 0.2%    |
| AGI                 | 1         | 1      | 0.2%    |
| 2-Power             | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 130       | 161    | 35.23%  |
| WDC                 | 97        | 154    | 26.29%  |
| Hitachi             | 61        | 85     | 16.53%  |
| Toshiba             | 30        | 36     | 8.13%   |
| Samsung Electronics | 19        | 26     | 5.15%   |
| HGST                | 17        | 20     | 4.61%   |
| Maxtor              | 4         | 4      | 1.08%   |
| Fujitsu             | 4         | 4      | 1.08%   |
| Hewlett-Packard     | 3         | 3      | 0.81%   |
| Unknown             | 2         | 2      | 0.54%   |
| WD MediaMax         | 1         | 1      | 0.27%   |
| Apple               | 1         | 2      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 332       | 498    | 72.65%  |
| SSD  | 106       | 137    | 23.19%  |
| NVMe | 19        | 27     | 4.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB  | 2         | 3      | 25%     |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 12.5%   |
| Toshiba DT01ACA100 1TB            | 1         | 1      | 12.5%   |
| Seagate ST3160815AS 160GB         | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 12.5%   |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 5      | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| Seagate             | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4557      | 9916   | 62.79%  |
| Works    | 2250      | 4437   | 31%     |
| Malfunc  | 444       | 662    | 6.12%   |
| Failed   | 7         | 9      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4252      | 50.31%  |
| AMD                              | 1454      | 17.21%  |
| Samsung Electronics              | 763       | 9.03%   |
| SanDisk                          | 335       | 3.96%   |
| Phison Electronics               | 222       | 2.63%   |
| ASMedia Technology               | 168       | 1.99%   |
| SK hynix                         | 150       | 1.77%   |
| Nvidia                           | 148       | 1.75%   |
| Toshiba America Info Systems     | 139       | 1.64%   |
| Marvell Technology Group         | 113       | 1.34%   |
| JMicron Technology               | 85        | 1.01%   |
| Micron/Crucial Technology        | 81        | 0.96%   |
| Kingston Technology Company      | 81        | 0.96%   |
| Silicon Motion                   | 60        | 0.71%   |
| KIOXIA                           | 58        | 0.69%   |
| Micron Technology                | 55        | 0.65%   |
| ADATA Technology                 | 39        | 0.46%   |
| LSI Logic / Symbios Logic        | 33        | 0.39%   |
| Broadcom / LSI                   | 23        | 0.27%   |
| VIA Technologies                 | 21        | 0.25%   |
| Seagate Technology               | 20        | 0.24%   |
| Silicon Image                    | 19        | 0.22%   |
| Silicon Integrated Systems [SiS] | 15        | 0.18%   |
| Hewlett-Packard                  | 15        | 0.18%   |
| Apple                            | 15        | 0.18%   |
| O2 Micro                         | 11        | 0.13%   |
| Adaptec                          | 10        | 0.12%   |
| Realtek Semiconductor            | 9         | 0.11%   |
| Lenovo                           | 9         | 0.11%   |
| Union Memory (Shenzhen)          | 8         | 0.09%   |
| Solid State Storage Technology   | 8         | 0.09%   |
| Shenzhen Longsys Electronics     | 6         | 0.07%   |
| Lite-On Technology               | 5         | 0.06%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Solidigm                         | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 983       | 9.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 403       | 4.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 282       | 2.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 277       | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 251       | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 234       | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                         | 202       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 177       | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 171       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 170       | 1.71%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 161       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 159       | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 158       | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 137       | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 129       | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 125       | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 124       | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 122       | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 122       | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 120       | 1.21%   |
| Phison E12 NVMe Controller                                                     | 113       | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 109       | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 108       | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 107       | 1.08%   |
| Samsung NVMe SSD Controller 980                                                | 105       | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 105       | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 98        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 94        | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 90        | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 88        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 85        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 81        | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 80        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 78        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 74        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 70        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 69        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 67        | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 61        | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 60        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4794      | 56.27%  |
| NVMe | 2008      | 23.57%  |
| IDE  | 1076      | 12.63%  |
| RAID | 581       | 6.82%   |
| SAS  | 36        | 0.42%   |
| SCSI | 25        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 4906      | 72.75%  |
| AMD          | 1749      | 25.93%  |
| ARM          | 87        | 1.29%   |
| QUALCOMM     | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 76        | 1.12%   |
| AMD Custom APU 0405                     | 73        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 65        | 0.96%   |
| ARM Processor                           | 63        | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 59        | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 52        | 0.77%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 49        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 48        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 44        | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 44        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 43        | 0.64%   |
| AMD FX-8350 Eight-Core Processor        | 41        | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 40        | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 40        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 39        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 39        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 39        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 39        | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 38        | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 38        | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 37        | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 37        | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 37        | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 35        | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 35        | 0.52%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 35        | 0.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 34        | 0.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 34        | 0.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor  | 34        | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 33        | 0.49%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 33        | 0.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 31        | 0.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 30        | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 30        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 29        | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 29        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 28        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 28        | 0.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 0.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 26        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1353      | 20.02%  |
| Intel Core i7           | 1276      | 18.88%  |
| Other                   | 448       | 6.63%   |
| Intel Core i3           | 425       | 6.29%   |
| AMD Ryzen 5             | 348       | 5.15%   |
| Intel Celeron           | 332       | 4.91%   |
| Intel Core 2 Duo        | 305       | 4.51%   |
| AMD Ryzen 7             | 292       | 4.32%   |
| Intel Xeon              | 196       | 2.9%    |
| Intel Pentium           | 177       | 2.62%   |
| AMD FX                  | 143       | 2.12%   |
| AMD Ryzen 9             | 132       | 1.95%   |
| Intel Atom              | 120       | 1.78%   |
| AMD Ryzen 3             | 78        | 1.15%   |
| AMD A8                  | 78        | 1.15%   |
| AMD A6                  | 76        | 1.12%   |
| Intel Pentium Dual-Core | 74        | 1.09%   |
| Intel Core 2 Quad       | 65        | 0.96%   |
| AMD A10                 | 55        | 0.81%   |
| Intel Core 2            | 54        | 0.8%    |
| Intel Core i9           | 50        | 0.74%   |
| Intel Pentium Dual      | 42        | 0.62%   |
| AMD A4                  | 41        | 0.61%   |
| AMD Athlon II X2        | 38        | 0.56%   |
| AMD Phenom II X4        | 33        | 0.49%   |
| Intel Genuine           | 26        | 0.38%   |
| AMD Ryzen Threadripper  | 25        | 0.37%   |
| AMD Athlon 64 X2        | 25        | 0.37%   |
| Intel Pentium 4         | 23        | 0.34%   |
| ARM BCM                 | 23        | 0.34%   |
| AMD E1                  | 23        | 0.34%   |
| AMD Athlon              | 23        | 0.34%   |
| AMD E                   | 21        | 0.31%   |
| Intel Celeron Dual-Core | 19        | 0.28%   |
| Intel Pentium Silver    | 17        | 0.25%   |
| Intel Pentium D         | 17        | 0.25%   |
| AMD Athlon II X4        | 17        | 0.25%   |
| Intel Celeron M         | 14        | 0.21%   |
| AMD Phenom              | 14        | 0.21%   |
| AMD Phenom II X6        | 13        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2750      | 40.69%  |
| 4       | 2383      | 35.26%  |
| 6       | 631       | 9.34%   |
| 8       | 479       | 7.09%   |
| 1       | 178       | 2.63%   |
| 12      | 118       | 1.75%   |
| 16      | 76        | 1.12%   |
| 3       | 58        | 0.86%   |
| 14      | 27        | 0.4%    |
| 10      | 26        | 0.38%   |
| 24      | 13        | 0.19%   |
| 32      | 6         | 0.09%   |
| Unknown | 3         | 0.04%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 64      | 1         | 0.01%   |
| 44      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6648      | 98.58%  |
| 2       | 88        | 1.3%    |
| 4       | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 3       | 2         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4308      | 63.82%  |
| 1       | 2439      | 36.13%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6520      | 96.29%  |
| Unknown        | 173       | 2.56%   |
| 32-bit         | 73        | 1.08%   |
| 64-bit         | 5         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1681      | 24%     |
| 0x306a9    | 366       | 5.23%   |
| 0x206a7    | 359       | 5.13%   |
| 0x306c3    | 299       | 4.27%   |
| 0x1067a    | 264       | 3.77%   |
| 0x906ea    | 158       | 2.26%   |
| 0x806ea    | 140       | 2%      |
| 0x506e3    | 138       | 1.97%   |
| 0x08701021 | 134       | 1.91%   |
| 0x806ec    | 125       | 1.78%   |
| 0x806e9    | 122       | 1.74%   |
| 0x406e3    | 121       | 1.73%   |
| 0x40651    | 119       | 1.7%    |
| 0x20655    | 115       | 1.64%   |
| 0x906e9    | 108       | 1.54%   |
| 0x806c1    | 107       | 1.53%   |
| 0x306d4    | 104       | 1.49%   |
| 0x6fd      | 93        | 1.33%   |
| 0x406c4    | 87        | 1.24%   |
| 0x010000c8 | 79        | 1.13%   |
| 0x06000852 | 75        | 1.07%   |
| 0x30678    | 71        | 1.01%   |
| 0x06001119 | 65        | 0.93%   |
| 0x10676    | 61        | 0.87%   |
| 0x0800820d | 60        | 0.86%   |
| 0x08108109 | 57        | 0.81%   |
| 0x08701013 | 55        | 0.79%   |
| 0xa0652    | 51        | 0.73%   |
| 0x6fb      | 50        | 0.71%   |
| 0x706e5    | 49        | 0.7%    |
| 0x506c9    | 49        | 0.7%    |
| 0x20652    | 46        | 0.66%   |
| 0x906ed    | 45        | 0.64%   |
| 0x06006705 | 44        | 0.63%   |
| 0x406c3    | 42        | 0.6%    |
| 0x0a50000c | 40        | 0.57%   |
| 0x08108102 | 39        | 0.56%   |
| 0x706a1    | 38        | 0.54%   |
| 0x206c2    | 37        | 0.53%   |
| 0x06003106 | 37        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 969       | 14.33%  |
| Haswell          | 559       | 8.27%   |
| SandyBridge      | 474       | 7.01%   |
| IvyBridge        | 471       | 6.97%   |
| Penryn           | 383       | 5.67%   |
| Zen 2            | 338       | 5%      |
| Skylake          | 338       | 5%      |
| Unknown          | 270       | 3.99%   |
| Core             | 252       | 3.73%   |
| Silvermont       | 248       | 3.67%   |
| Westmere         | 240       | 3.55%   |
| Zen+             | 219       | 3.24%   |
| Piledriver       | 191       | 2.83%   |
| K10              | 171       | 2.53%   |
| Zen 3            | 157       | 2.32%   |
| Broadwell        | 149       | 2.2%    |
| Zen              | 147       | 2.17%   |
| TigerLake        | 142       | 2.1%    |
| CometLake        | 123       | 1.82%   |
| Excavator        | 110       | 1.63%   |
| IceLake          | 96        | 1.42%   |
| Goldmont plus    | 84        | 1.24%   |
| Nehalem          | 78        | 1.15%   |
| Goldmont         | 60        | 0.89%   |
| K8 Hammer        | 58        | 0.86%   |
| Alderlake Hybrid | 57        | 0.84%   |
| Puma             | 55        | 0.81%   |
| Steamroller      | 53        | 0.78%   |
| Bobcat           | 46        | 0.68%   |
| NetBurst         | 45        | 0.67%   |
| Bonnell          | 43        | 0.64%   |
| P6               | 39        | 0.58%   |
| Jaguar           | 28        | 0.41%   |
| Bulldozer        | 27        | 0.4%    |
| Tremont          | 13        | 0.19%   |
| K8 & K10 hybrid  | 12        | 0.18%   |
| K10 Llano        | 11        | 0.16%   |
| K6               | 4         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3708      | 48.71%  |
| Nvidia                                       | 2097      | 27.55%  |
| AMD                                          | 1727      | 22.69%  |
| Matrox Electronics Systems                   | 38        | 0.5%    |
| Silicon Integrated Systems [SiS]             | 15        | 0.2%    |
| ASPEED Technology                            | 11        | 0.14%   |
| ATI Technologies                             | 8         | 0.11%   |
| VIA Technologies                             | 5         | 0.07%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 349       | 4.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 260       | 3.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 159       | 2.02%   |
| Intel UHD Graphics 620                                                                   | 154       | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 148       | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 147       | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 147       | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 147       | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 147       | 1.87%   |
| Intel HD Graphics 620                                                                    | 130       | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 128       | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 125       | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 124       | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 121       | 1.54%   |
| Intel HD Graphics 5500                                                                   | 104       | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 103       | 1.31%   |
| Intel HD Graphics 630                                                                    | 101       | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 97        | 1.23%   |
| Intel HD Graphics 530                                                                    | 94        | 1.19%   |
| AMD Renoir                                                                               | 89        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 87        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 86        | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 79        | 1%      |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 73        | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 70        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 65        | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 62        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 61        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 59        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 57        | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 56        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 53        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 0.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 50        | 0.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 50        | 0.64%   |
| Intel HD Graphics 500                                                                    | 48        | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 48        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 46        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 2881      | 42.3%   |
| 1 x AMD                              | 1470      | 21.58%  |
| 1 x Nvidia                           | 1348      | 19.79%  |
| Intel + Nvidia                       | 632       | 9.28%   |
| Intel + AMD                          | 101       | 1.48%   |
| Other                                | 98        | 1.44%   |
| 2 x AMD                              | 79        | 1.16%   |
| AMD + Nvidia                         | 75        | 1.1%    |
| 1 x Matrox                           | 33        | 0.48%   |
| 2 x Nvidia                           | 30        | 0.44%   |
| 2 x Intel                            | 15        | 0.22%   |
| 1 x SiS                              | 14        | 0.21%   |
| Nvidia + ASPEED                      | 6         | 0.09%   |
| 1 x VIA                              | 5         | 0.07%   |
| 1 x ASPEED                           | 5         | 0.07%   |
| Nvidia + Matrox                      | 4         | 0.06%   |
| Intel + AMD + 1 x Nvidia             | 3         | 0.04%   |
| 2 x AMD + 1 x Nvidia                 | 2         | 0.03%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.01%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.01%   |
| 1 x XGI                              | 1         | 0.01%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.01%   |
| 1 x Huawei Technologies              | 1         | 0.01%   |
| AMD + SiS                            | 1         | 0.01%   |
| AMD + ASPEED                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5326      | 77.46%  |
| Proprietary | 1208      | 17.57%  |
| Unknown     | 342       | 4.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3901      | 55.94%  |
| 0.01-0.5   | 796       | 11.41%  |
| 1.01-2.0   | 744       | 10.67%  |
| 0.51-1.0   | 490       | 7.03%   |
| 3.01-4.0   | 407       | 5.84%   |
| 7.01-8.0   | 318       | 4.56%   |
| 5.01-6.0   | 158       | 2.27%   |
| 8.01-16.0  | 104       | 1.49%   |
| 2.01-3.0   | 49        | 0.7%    |
| 16.01-24.0 | 4         | 0.06%   |
| 4.01-5.0   | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |
| 0          | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 837       | 11.82%  |
| AU Optronics            | 773       | 10.92%  |
| LG Display              | 614       | 8.67%   |
| Dell                    | 499       | 7.05%   |
| Chimei Innolux          | 456       | 6.44%   |
| BOE                     | 436       | 6.16%   |
| Acer                    | 309       | 4.36%   |
| Goldstar                | 237       | 3.35%   |
| Hewlett-Packard         | 234       | 3.31%   |
| AOC                     | 220       | 3.11%   |
| BenQ                    | 218       | 3.08%   |
| Sharp                   | 212       | 2.99%   |
| Apple                   | 157       | 2.22%   |
| Iiyama                  | 148       | 2.09%   |
| Ancor Communications    | 131       | 1.85%   |
| Lenovo                  | 129       | 1.82%   |
| Philips                 | 113       | 1.6%    |
| ViewSonic               | 82        | 1.16%   |
| Chi Mei Optoelectronics | 78        | 1.1%    |
| Sony                    | 76        | 1.07%   |
| Unknown                 | 65        | 0.92%   |
| ASUSTek Computer        | 62        | 0.88%   |
| HannStar                | 59        | 0.83%   |
| PANDA                   | 56        | 0.79%   |
| Panasonic               | 52        | 0.73%   |
| LG Philips              | 45        | 0.64%   |
| Toshiba                 | 44        | 0.62%   |
| Vestel Elektronik       | 40        | 0.56%   |
| LG Electronics          | 39        | 0.55%   |
| InfoVision              | 38        | 0.54%   |
| NEC Computers           | 32        | 0.45%   |
| Valve                   | 30        | 0.42%   |
| MSI                     | 30        | 0.42%   |
| Analogix                | 26        | 0.37%   |
| Gigabyte Technology     | 18        | 0.25%   |
| OEM                     | 17        | 0.24%   |
| Hitachi                 | 17        | 0.24%   |
| MiTAC                   | 15        | 0.21%   |
| Fujitsu Siemens         | 14        | 0.2%    |
| LGD                     | 13        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 41        | 0.56%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 40        | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 31        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 30        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 30        | 0.41%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 28        | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 28        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 27        | 0.37%   |
| Analogix ANX7530 U ANX7539 800x1280                                    | 26        | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 25        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 24        | 0.33%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 22        | 0.3%    |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 20        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 19        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 18        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 18        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 17        | 0.23%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 16        | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 16        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch        | 16        | 0.22%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 16        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 15        | 0.2%    |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch           | 15        | 0.2%    |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch          | 15        | 0.2%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 14        | 0.19%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 13        | 0.18%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch   | 13        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 13        | 0.18%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 13        | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 13        | 0.18%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 13        | 0.18%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 12        | 0.16%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 12        | 0.16%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch           | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 12        | 0.16%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 12        | 0.16%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 12        | 0.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 12        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2795      | 40.86%  |
| 1366x768 (WXGA)    | 1172      | 17.13%  |
| 3840x2160 (4K)     | 522       | 7.63%   |
| 2560x1440 (QHD)    | 360       | 5.26%   |
| 1280x1024 (SXGA)   | 239       | 3.49%   |
| 1280x800 (WXGA)    | 198       | 2.89%   |
| 1600x900 (HD+)     | 185       | 2.7%    |
| 1680x1050 (WSXGA+) | 180       | 2.63%   |
| 1440x900 (WXGA+)   | 179       | 2.62%   |
| 1920x1200 (WUXGA)  | 153       | 2.24%   |
| Unknown            | 106       | 1.55%   |
| 3440x1440          | 87        | 1.27%   |
| 1360x768           | 57        | 0.83%   |
| 800x1280           | 52        | 0.76%   |
| 2560x1080          | 52        | 0.76%   |
| 3840x1080          | 46        | 0.67%   |
| 1920x540           | 45        | 0.66%   |
| 2560x1600          | 43        | 0.63%   |
| 3840x2400          | 31        | 0.45%   |
| 1024x768 (XGA)     | 29        | 0.42%   |
| 3200x1800 (QHD+)   | 24        | 0.35%   |
| 2880x1800          | 22        | 0.32%   |
| 2736x1824          | 22        | 0.32%   |
| 1600x1200          | 22        | 0.32%   |
| 2160x1440          | 19        | 0.28%   |
| 1280x720 (HD)      | 18        | 0.26%   |
| 1024x600           | 18        | 0.26%   |
| 2288x1287          | 10        | 0.15%   |
| 1920x1280          | 9         | 0.13%   |
| 5120x1440          | 8         | 0.12%   |
| 5760x1080          | 7         | 0.1%    |
| 3840x1200          | 6         | 0.09%   |
| 3072x1920          | 6         | 0.09%   |
| 2256x1504          | 6         | 0.09%   |
| 7680x2160          | 5         | 0.07%   |
| 3200x1080          | 5         | 0.07%   |
| 2880x1920          | 5         | 0.07%   |
| 1680x945           | 5         | 0.07%   |
| 5760x2160          | 4         | 0.06%   |
| 3840x1600          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1595      | 22.65%  |
| 13      | 673       | 9.56%   |
| 27      | 542       | 7.7%    |
| Unknown | 506       | 7.19%   |
| 24      | 493       | 7%      |
| 23      | 440       | 6.25%   |
| 14      | 393       | 5.58%   |
| 21      | 392       | 5.57%   |
| 17      | 359       | 5.1%    |
| 12      | 208       | 2.95%   |
| 19      | 189       | 2.68%   |
| 31      | 145       | 2.06%   |
| 11      | 109       | 1.55%   |
| 84      | 107       | 1.52%   |
| 22      | 106       | 1.51%   |
| 34      | 103       | 1.46%   |
| 18      | 88        | 1.25%   |
| 20      | 72        | 1.02%   |
| 72      | 55        | 0.78%   |
| 26      | 42        | 0.6%    |
| 25      | 39        | 0.55%   |
| 10      | 35        | 0.5%    |
| 32      | 34        | 0.48%   |
| 16      | 34        | 0.48%   |
| 54      | 28        | 0.4%    |
| 7       | 28        | 0.4%    |
| 40      | 19        | 0.27%   |
| 33      | 19        | 0.27%   |
| 48      | 17        | 0.24%   |
| 65      | 16        | 0.23%   |
| 39      | 15        | 0.21%   |
| 28      | 15        | 0.21%   |
| 60      | 11        | 0.16%   |
| 46      | 11        | 0.16%   |
| 52      | 10        | 0.14%   |
| 55      | 9         | 0.13%   |
| 43      | 8         | 0.11%   |
| 35      | 8         | 0.11%   |
| 142     | 7         | 0.1%    |
| 47      | 7         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2335      | 33.61%  |
| 501-600        | 1383      | 19.91%  |
| 201-300        | 763       | 10.98%  |
| 401-500        | 734       | 10.57%  |
| Unknown        | 506       | 7.28%   |
| 351-400        | 425       | 6.12%   |
| 601-700        | 248       | 3.57%   |
| 1501-2000      | 164       | 2.36%   |
| 701-800        | 158       | 2.27%   |
| 1001-1500      | 129       | 1.86%   |
| 801-900        | 46        | 0.66%   |
| 1-100          | 28        | 0.4%    |
| 901-1000       | 13        | 0.19%   |
| More than 2000 | 9         | 0.13%   |
| 101-200        | 6         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4661      | 72%     |
| 16/10   | 796       | 12.3%   |
| Unknown | 421       | 6.5%    |
| 5/4     | 221       | 3.41%   |
| 21/9    | 122       | 1.88%   |
| 3/2     | 91        | 1.41%   |
| 4/3     | 63        | 0.97%   |
| 0.67    | 28        | 0.43%   |
| 0.62    | 27        | 0.42%   |
| 32/9    | 19        | 0.29%   |
| 1.00    | 11        | 0.17%   |
| 6/5     | 10        | 0.15%   |
| 3.20    | 2         | 0.03%   |
| 3.40    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1593      | 22.84%  |
| 201-250        | 1140      | 16.34%  |
| 81-90          | 714       | 10.24%  |
| 301-350        | 572       | 8.2%    |
| Unknown        | 506       | 7.25%   |
| 151-200        | 402       | 5.76%   |
| 71-80          | 365       | 5.23%   |
| 351-500        | 320       | 4.59%   |
| More than 1000 | 264       | 3.78%   |
| 121-130        | 206       | 2.95%   |
| 251-300        | 190       | 2.72%   |
| 61-70          | 183       | 2.62%   |
| 141-150        | 163       | 2.34%   |
| 51-60          | 114       | 1.63%   |
| 501-1000       | 90        | 1.29%   |
| 131-140        | 43        | 0.62%   |
| 1-40           | 34        | 0.49%   |
| 111-120        | 32        | 0.46%   |
| 41-50          | 31        | 0.44%   |
| 91-100         | 13        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2147      | 31.57%  |
| 101-120       | 1697      | 24.96%  |
| 121-160       | 1588      | 23.35%  |
| Unknown       | 506       | 7.44%   |
| 161-240       | 465       | 6.84%   |
| More than 240 | 208       | 3.06%   |
| 1-50          | 189       | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5557      | 80.35%  |
| 2     | 909       | 13.14%  |
| 0     | 343       | 4.96%   |
| 3     | 97        | 1.4%    |
| 4     | 9         | 0.13%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3363      | 33.5%   |
| Intel                             | 3329      | 33.16%  |
| Qualcomm Atheros                  | 1032      | 10.28%  |
| Broadcom                          | 703       | 7%      |
| Ralink Technology                 | 198       | 1.97%   |
| Marvell Technology Group          | 160       | 1.59%   |
| Broadcom Limited                  | 146       | 1.45%   |
| Nvidia                            | 120       | 1.2%    |
| TP-Link                           | 107       | 1.07%   |
| Ralink                            | 107       | 1.07%   |
| MediaTek                          | 76        | 0.76%   |
| ASIX Electronics                  | 39        | 0.39%   |
| Ericsson Business Mobile Networks | 38        | 0.38%   |
| DisplayLink                       | 38        | 0.38%   |
| Samsung Electronics               | 36        | 0.36%   |
| Microsoft                         | 36        | 0.36%   |
| Dell                              | 36        | 0.36%   |
| Belkin Components                 | 28        | 0.28%   |
| NetGear                           | 27        | 0.27%   |
| Qualcomm Atheros Communications   | 26        | 0.26%   |
| Lenovo                            | 25        | 0.25%   |
| Edimax Technology                 | 24        | 0.24%   |
| Huawei Technologies               | 23        | 0.23%   |
| Aquantia                          | 19        | 0.19%   |
| Hewlett-Packard                   | 18        | 0.18%   |
| Qualcomm                          | 17        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.15%   |
| ASUSTek Computer                  | 13        | 0.13%   |
| Sierra Wireless                   | 11        | 0.11%   |
| Microchip Technology              | 11        | 0.11%   |
| JMicron Technology                | 11        | 0.11%   |
| Xiaomi                            | 10        | 0.1%    |
| VIA Technologies                  | 10        | 0.1%    |
| Mellanox Technologies             | 10        | 0.1%    |
| D-Link                            | 9         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 8         | 0.08%   |
| Apple                             | 8         | 0.08%   |
| Google                            | 7         | 0.07%   |
| D-Link System                     | 7         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2174      | 18.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 402       | 3.39%   |
| Intel Wi-Fi 6 AX200                                               | 324       | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 283       | 2.39%   |
| Intel I211 Gigabit Network Connection                             | 227       | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 193       | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 1.46%   |
| Intel Wireless 7265                                               | 159       | 1.34%   |
| Intel Wireless 7260                                               | 155       | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 143       | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 139       | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 133       | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 127       | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 126       | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 125       | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 118       | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 116       | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 112       | 0.94%   |
| Intel Wireless 3165                                               | 110       | 0.93%   |
| Intel Wireless 8260                                               | 109       | 0.92%   |
| Intel Wi-Fi 6 AX201                                               | 97        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 95        | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 86        | 0.72%   |
| Intel Wireless-AC 9260                                            | 86        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 84        | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 78        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 71        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 71        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 71        | 0.6%    |
| Realtek 802.11ac NIC                                              | 69        | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 69        | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 68        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 66        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 64        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 63        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 63        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 61        | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 60        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2398      | 43.66%  |
| Realtek Semiconductor           | 956       | 17.4%   |
| Qualcomm Atheros                | 839       | 15.27%  |
| Broadcom                        | 440       | 8.01%   |
| Ralink Technology               | 198       | 3.6%    |
| Ralink                          | 106       | 1.93%   |
| Broadcom Limited                | 104       | 1.89%   |
| TP-Link                         | 101       | 1.84%   |
| MediaTek                        | 66        | 1.2%    |
| Microsoft                       | 34        | 0.62%   |
| Marvell Technology Group        | 31        | 0.56%   |
| Belkin Components               | 28        | 0.51%   |
| NetGear                         | 27        | 0.49%   |
| Qualcomm Atheros Communications | 26        | 0.47%   |
| Edimax Technology               | 24        | 0.44%   |
| Dell                            | 21        | 0.38%   |
| ASUSTek Computer                | 12        | 0.22%   |
| Sierra Wireless                 | 11        | 0.2%    |
| D-Link                          | 9         | 0.16%   |
| Qualcomm                        | 8         | 0.15%   |
| Micro Star International        | 6         | 0.11%   |
| D-Link System                   | 6         | 0.11%   |
| IMC Networks                    | 5         | 0.09%   |
| ZyDAS                           | 4         | 0.07%   |
| Wacom                           | 3         | 0.05%   |
| TRENDnet                        | 3         | 0.05%   |
| Sitecom Europe                  | 3         | 0.05%   |
| Linksys                         | 3         | 0.05%   |
| Gemtek                          | 3         | 0.05%   |
| FIBOCOM                         | 3         | 0.05%   |
| Wilocity                        | 2         | 0.04%   |
| Hewlett-Packard                 | 2         | 0.04%   |
| Texas Instruments               | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| Philips (or NXP)                | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| CyberTAN Technology             | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 324       | 5.85%   |
| Intel Wireless 8265 / 8275                                              | 193       | 3.48%   |
| Intel Wireless 7265                                                     | 159       | 2.87%   |
| Intel Wireless 7260                                                     | 155       | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 143       | 2.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 139       | 2.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 133       | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 127       | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 126       | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 112       | 2.02%   |
| Intel Wireless 3165                                                     | 110       | 1.98%   |
| Intel Wireless 8260                                                     | 109       | 1.97%   |
| Intel Wi-Fi 6 AX201                                                     | 97        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 86        | 1.55%   |
| Intel Wireless-AC 9260                                                  | 86        | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 84        | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 78        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 71        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 71        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 71        | 1.28%   |
| Realtek 802.11ac NIC                                                    | 69        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 69        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                         | 68        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 66        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 63        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 61        | 1.1%    |
| Intel Wireless 3160                                                     | 55        | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 54        | 0.97%   |
| Ralink RT5370 Wireless Adapter                                          | 53        | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 52        | 0.94%   |
| Intel WiFi Link 5100                                                    | 49        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 43        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 43        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 41        | 0.74%   |
| Intel Centrino Advanced-N 6200                                          | 41        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 40        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2935      | 48.62%  |
| Intel                                  | 1813      | 30.03%  |
| Broadcom                               | 368       | 6.1%    |
| Qualcomm Atheros                       | 286       | 4.74%   |
| Marvell Technology Group               | 129       | 2.14%   |
| Nvidia                                 | 120       | 1.99%   |
| Broadcom Limited                       | 45        | 0.75%   |
| ASIX Electronics                       | 39        | 0.65%   |
| DisplayLink                            | 38        | 0.63%   |
| Samsung Electronics                    | 35        | 0.58%   |
| Lenovo                                 | 24        | 0.4%    |
| Huawei Technologies                    | 19        | 0.31%   |
| Aquantia                               | 19        | 0.31%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.23%   |
| JMicron Technology                     | 11        | 0.18%   |
| Xiaomi                                 | 10        | 0.17%   |
| VIA Technologies                       | 10        | 0.17%   |
| Microchip Technology                   | 10        | 0.17%   |
| Qualcomm                               | 9         | 0.15%   |
| Mellanox Technologies                  | 9         | 0.15%   |
| MediaTek                               | 9         | 0.15%   |
| OnePlus Technology (Shenzhen)          | 7         | 0.12%   |
| Google                                 | 7         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.1%    |
| TP-Link                                | 6         | 0.1%    |
| OPPO Electronics                       | 6         | 0.1%    |
| Motorola PCS                           | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| Attansic Technology                    | 5         | 0.08%   |
| ICS Advent                             | 4         | 0.07%   |
| Hewlett-Packard                        | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| HTC (High Tech Computer)               | 3         | 0.05%   |
| 3Com                                   | 3         | 0.05%   |
| Standard Microsystems                  | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Emulex                                 | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2174      | 35.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 402       | 6.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 283       | 4.58%   |
| Intel I211 Gigabit Network Connection                             | 227       | 3.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 173       | 2.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 125       | 2.02%   |
| Intel Ethernet Connection (2) I219-V                              | 118       | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 95        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 64        | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 64        | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 60        | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 54        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 54        | 0.87%   |
| Nvidia MCP61 Ethernet                                             | 51        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 50        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 41        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 41        | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 41        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 40        | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 40        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 35        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 35        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 35        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 34        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 33        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 32        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 30        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 29        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26        | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 26        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 24        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5688      | 51.88%  |
| WiFi     | 5136      | 46.85%  |
| Modem    | 123       | 1.12%   |
| Unknown  | 16        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3984      | 57.19%  |
| Ethernet | 2981      | 42.79%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3551      | 52.28%  |
| 1     | 2839      | 41.8%   |
| 0     | 187       | 2.75%   |
| 3     | 150       | 2.21%   |
| 4     | 39        | 0.57%   |
| 5     | 17        | 0.25%   |
| 6     | 7         | 0.1%    |
| 8     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6008      | 87.78%  |
| Yes  | 836       | 12.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1845      | 46.18%  |
| Cambridge Silicon Radio         | 314       | 7.86%   |
| Realtek Semiconductor           | 311       | 7.78%   |
| Qualcomm Atheros Communications | 288       | 7.21%   |
| Broadcom                        | 267       | 6.68%   |
| Apple                           | 183       | 4.58%   |
| IMC Networks                    | 171       | 4.28%   |
| Foxconn / Hon Hai               | 100       | 2.5%    |
| Lite-On Technology              | 98        | 2.45%   |
| Dell                            | 75        | 1.88%   |
| ASUSTek Computer                | 70        | 1.75%   |
| Toshiba                         | 51        | 1.28%   |
| Hewlett-Packard                 | 41        | 1.03%   |
| Marvell Semiconductor           | 29        | 0.73%   |
| Realtek                         | 20        | 0.5%    |
| Alps Electric                   | 18        | 0.45%   |
| Belkin Components               | 17        | 0.43%   |
| MediaTek                        | 14        | 0.35%   |
| Foxconn International           | 14        | 0.35%   |
| TP-Link                         | 10        | 0.25%   |
| Ralink                          | 9         | 0.23%   |
| Integrated System Solution      | 9         | 0.23%   |
| Ralink Technology               | 6         | 0.15%   |
| Askey Computer                  | 6         | 0.15%   |
| Taiyo Yuden                     | 5         | 0.13%   |
| Micro Star International        | 5         | 0.13%   |
| Logitech                        | 4         | 0.1%    |
| HTC (High Tech Computer)        | 4         | 0.1%    |
| Edimax Technology               | 3         | 0.08%   |
| USI                             | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Cypress Semiconductor           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 736       | 18.42%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 314       | 7.86%   |
| Intel AX200 Bluetooth                               | 298       | 7.46%   |
| Intel AX201 Bluetooth                               | 279       | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 198       | 4.95%   |
| Realtek Bluetooth Radio                             | 185       | 4.63%   |
| IMC Networks Bluetooth Radio                        | 110       | 2.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 107       | 2.68%   |
| Apple Bluetooth Host Controller                     | 88        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 81        | 2.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 77        | 1.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 72        | 1.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 67        | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 67        | 1.68%   |
| Intel AX210 Bluetooth                               | 64        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 55        | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 54        | 1.35%   |
| Apple Bluetooth USB Host Controller                 | 47        | 1.18%   |
| Intel Bluetooth Device                              | 40        | 1%      |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 38        | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 0.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 0.68%   |
| IMC Networks Bluetooth Device                       | 26        | 0.65%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.65%   |
| Marvell Bluetooth and Wireless LAN Composite        | 25        | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 25        | 0.63%   |
| Lite-On Bluetooth Device                            | 24        | 0.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.53%   |
| Realtek Bluetooth Radio                             | 20        | 0.5%    |
| Apple Bluetooth HCI                                 | 20        | 0.5%    |
| Realtek RTL8821A Bluetooth                          | 19        | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.48%   |
| IMC Networks Wireless_Device                        | 18        | 0.45%   |
| Toshiba Bluetooth Device                            | 15        | 0.38%   |
| Realtek RTL8723B Bluetooth                          | 15        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4641      | 49.64%  |
| AMD                                  | 1981      | 21.19%  |
| Nvidia                               | 1648      | 17.63%  |
| C-Media Electronics                  | 169       | 1.81%   |
| Creative Labs                        | 89        | 0.95%   |
| Logitech                             | 60        | 0.64%   |
| Texas Instruments                    | 52        | 0.56%   |
| JMTek                                | 35        | 0.37%   |
| Realtek Semiconductor                | 34        | 0.36%   |
| Focusrite-Novation                   | 33        | 0.35%   |
| Creative Technology                  | 30        | 0.32%   |
| Razer USA                            | 28        | 0.3%    |
| SteelSeries ApS                      | 26        | 0.28%   |
| GN Netcom                            | 26        | 0.28%   |
| ASUSTek Computer                     | 26        | 0.28%   |
| Plantronics                          | 25        | 0.27%   |
| Corsair                              | 21        | 0.22%   |
| Blue Microphones                     | 19        | 0.2%    |
| VIA Technologies                     | 18        | 0.19%   |
| Micro Star International             | 18        | 0.19%   |
| Kingston Technology                  | 18        | 0.19%   |
| Lenovo                               | 17        | 0.18%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.16%   |
| Generalplus Technology               | 15        | 0.16%   |
| Apple                                | 14        | 0.15%   |
| Sennheiser Communications            | 11        | 0.12%   |
| Tenx Technology                      | 10        | 0.11%   |
| Dell                                 | 10        | 0.11%   |
| ATI Technologies                     | 9         | 0.1%    |
| Sony                                 | 8         | 0.09%   |
| GYROCOM C&C                          | 8         | 0.09%   |
| BEHRINGER International              | 8         | 0.09%   |
| AKAI Professional M.I.               | 8         | 0.09%   |
| XMOS                                 | 7         | 0.07%   |
| Hewlett-Packard                      | 7         | 0.07%   |
| Conexant Systems                     | 7         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.06%   |
| Microsoft                            | 6         | 0.06%   |
| DSEA A/S                             | 6         | 0.06%   |
| Yamaha                               | 5         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 467       | 4.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 458       | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 413       | 3.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 397       | 3.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 317       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 310       | 2.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 279       | 2.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 274       | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 248       | 2.24%   |
| AMD FCH Azalia Controller                                                                         | 241       | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 235       | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 230       | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 174       | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 170       | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 169       | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 166       | 1.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 164       | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 149       | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 148       | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 147       | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 146       | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 141       | 1.28%   |
| Intel 200 Series PCH HD Audio                                                                     | 138       | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 136       | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 135       | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 129       | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 120       | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 105       | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 105       | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 102       | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 101       | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 99        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 98        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 95        | 0.86%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 94        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 93        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 91        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 83        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 81        | 0.73%   |
| Nvidia High Definition Audio Controller                                                           | 81        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 717       | 19.65%  |
| SK hynix            | 641       | 17.57%  |
| Corsair             | 440       | 12.06%  |
| Micron Technology   | 367       | 10.06%  |
| Crucial             | 359       | 9.84%   |
| Unknown             | 357       | 9.78%   |
| Kingston            | 321       | 8.8%    |
| Ramaxel Technology  | 57        | 1.56%   |
| Elpida              | 47        | 1.29%   |
| A-DATA Technology   | 46        | 1.26%   |
| Nanya Technology    | 44        | 1.21%   |
| G.Skill             | 35        | 0.96%   |
| Unknown (ABCD)      | 31        | 0.85%   |
| Team                | 28        | 0.77%   |
| Patriot             | 19        | 0.52%   |
| Unknown             | 11        | 0.3%    |
| Transcend           | 9         | 0.25%   |
| Hewlett-Packard     | 9         | 0.25%   |
| Qimonda             | 8         | 0.22%   |
| ASint Technology    | 7         | 0.19%   |
| Toshiba             | 6         | 0.16%   |
| A Force             | 6         | 0.16%   |
| Timetec             | 5         | 0.14%   |
| GOODRAM             | 5         | 0.14%   |
| Apacer              | 5         | 0.14%   |
| GSkill              | 4         | 0.11%   |
| KLEVV               | 3         | 0.08%   |
| Axiom               | 3         | 0.08%   |
| V-Color             | 2         | 0.05%   |
| Unknown (F301)      | 2         | 0.05%   |
| Unknown (0x0702)    | 2         | 0.05%   |
| Unknown (0B38)      | 2         | 0.05%   |
| Neo Forza           | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |
| Essencore           | 2         | 0.05%   |
| CSX                 | 2         | 0.05%   |
| Avant               | 2         | 0.05%   |
| ATP                 | 2         | 0.05%   |
| Wilk Elektronik     | 1         | 0.03%   |
| Uroad               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 40        | 1.01%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 38        | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.46%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 18        | 0.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 17        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 16        | 0.41%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 16        | 0.41%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 16        | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.36%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 14        | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 13        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 12        | 0.3%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.3%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 11        | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.28%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.28%   |
| Unknown                                                          | 11        | 0.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 10        | 0.25%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 10        | 0.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1429      | 44.94%  |
| DDR3    | 1054      | 33.14%  |
| DDR2    | 178       | 5.6%    |
| LPDDR4  | 129       | 4.06%   |
| LPDDR3  | 109       | 3.43%   |
| Unknown | 108       | 3.4%    |
| SDRAM   | 97        | 3.05%   |
| DDR5    | 35        | 1.1%    |
| DDR     | 24        | 0.75%   |
| LPDDR5  | 9         | 0.28%   |
| DRAM    | 8         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1647      | 52.45%  |
| DIMM         | 1216      | 38.73%  |
| Row Of Chips | 230       | 7.32%   |
| Chip         | 20        | 0.64%   |
| Unknown      | 17        | 0.54%   |
| RIMM         | 6         | 0.19%   |
| FB-DIMM      | 4         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1282      | 37.42%  |
| 4096   | 946       | 27.61%  |
| 16384  | 492       | 14.36%  |
| 2048   | 439       | 12.81%  |
| 1024   | 141       | 4.12%   |
| 32768  | 104       | 3.04%   |
| 512    | 17        | 0.5%    |
| 256    | 2         | 0.06%   |
| 131072 | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 695       | 20.13%  |
| 2667    | 457       | 13.24%  |
| 3200    | 391       | 11.33%  |
| 2400    | 277       | 8.02%   |
| 1333    | 254       | 7.36%   |
| 2133    | 175       | 5.07%   |
| 3600    | 106       | 3.07%   |
| 667     | 98        | 2.84%   |
| 1867    | 91        | 2.64%   |
| 1334    | 84        | 2.43%   |
| 800     | 83        | 2.4%    |
| Unknown | 60        | 1.74%   |
| 4267    | 52        | 1.51%   |
| 1067    | 45        | 1.3%    |
| 3400    | 43        | 1.25%   |
| 3266    | 38        | 1.1%    |
| 3000    | 37        | 1.07%   |
| 1066    | 37        | 1.07%   |
| 3733    | 31        | 0.9%    |
| 2048    | 30        | 0.87%   |
| 4800    | 28        | 0.81%   |
| 1866    | 28        | 0.81%   |
| 2800    | 23        | 0.67%   |
| 4199    | 21        | 0.61%   |
| 2933    | 20        | 0.58%   |
| 533     | 20        | 0.58%   |
| 3466    | 19        | 0.55%   |
| 2666    | 18        | 0.52%   |
| 400     | 16        | 0.46%   |
| 4266    | 14        | 0.41%   |
| 1800    | 14        | 0.41%   |
| 975     | 12        | 0.35%   |
| 3800    | 11        | 0.32%   |
| 6400    | 9         | 0.26%   |
| 1639    | 7         | 0.2%    |
| 49926   | 6         | 0.17%   |
| 8400    | 6         | 0.17%   |
| 3534    | 6         | 0.17%   |
| 3100    | 6         | 0.17%   |
| 2000    | 6         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 66        | 41.51%  |
| Canon                 | 28        | 17.61%  |
| Samsung Electronics   | 15        | 9.43%   |
| Seiko Epson           | 14        | 8.81%   |
| Brother Industries    | 13        | 8.18%   |
| Prolific Technology   | 5         | 3.14%   |
| Lexmark International | 4         | 2.52%   |
| STMicroelectronics    | 2         | 1.26%   |
| QinHeng Electronics   | 2         | 1.26%   |
| Oki Data              | 2         | 1.26%   |
| Kyocera               | 2         | 1.26%   |
| Dymo-CoStar           | 2         | 1.26%   |
| Seiko Instruments     | 1         | 0.63%   |
| Ricoh                 | 1         | 0.63%   |
| Dell                  | 1         | 0.63%   |
| Apple                 | 1         | 0.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 6         | 3.73%   |
| HP ENVY 4520 series                                       | 6         | 3.73%   |
| Prolific PL2305 Parallel Port                             | 5         | 3.11%   |
| HP ENVY 5000 series                                       | 5         | 3.11%   |
| Canon PIXMA MG2500 Series                                 | 5         | 3.11%   |
| HP DeskJet 2600 series                                    | 4         | 2.48%   |
| HP DeskJet 2130 series                                    | 3         | 1.86%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.24%   |
| Seiko Epson XP-243 245 247 Series                         | 2         | 1.24%   |
| Seiko Epson XP-200 Series                                 | 2         | 1.24%   |
| Samsung ML-2250 Series                                    | 2         | 1.24%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.24%   |
| Samsung C43x Series                                       | 2         | 1.24%   |
| QinHeng CH340S                                            | 2         | 1.24%   |
| Oki Data USB Device                                       | 2         | 1.24%   |
| HP LaserJet P2015 series                                  | 2         | 1.24%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.24%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.24%   |
| HP Deskjet F2280 series                                   | 2         | 1.24%   |
| HP DeskJet 3630 series                                    | 2         | 1.24%   |
| HP Deskjet 2540 series                                    | 2         | 1.24%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.24%   |
| HP Color LaserJet CP1215                                  | 2         | 1.24%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.24%   |
| Canon PIXMA MP495                                         | 2         | 1.24%   |
| Canon MG5700 series                                       | 2         | 1.24%   |
| Canon iP7200 series                                       | 2         | 1.24%   |
| Canon CanoScan LiDE 300                                   | 2         | 1.24%   |
| Brother HL-3140CW series                                  | 2         | 1.24%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.24%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.62%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.62%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.62%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.62%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.62%   |
| Seiko Epson L355 Series                                   | 1         | 0.62%   |
| Samsung SCX-4300 Series                                   | 1         | 0.62%   |
| Samsung SCX-4200 series                                   | 1         | 0.62%   |
| Samsung SCX-3400 Series                                   | 1         | 0.62%   |
| Samsung ML-1865                                           | 1         | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 24        | 63.16%  |
| Seiko Epson        | 8         | 21.05%  |
| Ultima Electronics | 2         | 5.26%   |
| Hewlett-Packard    | 2         | 5.26%   |
| Mustek Systems     | 1         | 2.63%   |
| AGFA-Gevaert NV    | 1         | 2.63%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 13.16%  |
| Canon CanoScan LiDE 220                                                               | 4         | 10.53%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 7.89%   |
| Canon CanoScan LiDE 200                                                               | 3         | 7.89%   |
| Canon CanoScan LiDE 110                                                               | 3         | 7.89%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5.26%   |
| Seiko Epson Scanner                                                                   | 2         | 5.26%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 5.26%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.63%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.63%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.63%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.63%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.63%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.63%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.63%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.63%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.63%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.63%   |
| Canon CanoScan LiDE 210                                                               | 1         | 2.63%   |
| Canon CanoScan LiDE 100                                                               | 1         | 2.63%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.63%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 815       | 21.22%  |
| Microdia                               | 403       | 10.49%  |
| Realtek Semiconductor                  | 309       | 8.04%   |
| IMC Networks                           | 269       | 7%      |
| Logitech                               | 265       | 6.9%    |
| Acer                                   | 197       | 5.13%   |
| Sunplus Innovation Technology          | 179       | 4.66%   |
| Apple                                  | 153       | 3.98%   |
| Cheng Uei Precision Industry (Foxlink) | 133       | 3.46%   |
| Quanta                                 | 125       | 3.25%   |
| Suyin                                  | 114       | 2.97%   |
| Lite-On Technology                     | 91        | 2.37%   |
| Microsoft                              | 78        | 2.03%   |
| Syntek                                 | 70        | 1.82%   |
| Silicon Motion                         | 59        | 1.54%   |
| Alcor Micro                            | 51        | 1.33%   |
| Samsung Electronics                    | 45        | 1.17%   |
| Ricoh                                  | 43        | 1.12%   |
| Lenovo                                 | 36        | 0.94%   |
| Bison Electronics                      | 33        | 0.86%   |
| Z-Star Microelectronics                | 28        | 0.73%   |
| Luxvisions Innotech Limited            | 27        | 0.7%    |
| ARC International                      | 26        | 0.68%   |
| Generalplus Technology                 | 23        | 0.6%    |
| GEMBIRD                                | 20        | 0.52%   |
| MacroSilicon                           | 16        | 0.42%   |
| Creative Technology                    | 15        | 0.39%   |
| ALi                                    | 13        | 0.34%   |
| Sonix Technology                       | 12        | 0.31%   |
| Primax Electronics                     | 12        | 0.31%   |
| SunplusIT                              | 10        | 0.26%   |
| Razer USA                              | 10        | 0.26%   |
| Aveo Technology                        | 10        | 0.26%   |
| Huawei Technologies                    | 8         | 0.21%   |
| Hewlett-Packard                        | 8         | 0.21%   |
| Genesys Logic                          | 7         | 0.18%   |
| Sunplus Technology                     | 6         | 0.16%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.16%   |
| OmniVision Technologies                | 6         | 0.16%   |
| Importek                               | 6         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 172       | 4.43%   |
| Chicony Integrated Camera                               | 138       | 3.55%   |
| Realtek Integrated_Webcam_HD                            | 104       | 2.68%   |
| Logitech HD Pro Webcam C920                             | 79        | 2.03%   |
| IMC Networks Integrated Camera                          | 79        | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 70        | 1.8%    |
| Chicony HD WebCam                                       | 62        | 1.6%    |
| Sunplus Integrated_Webcam_HD                            | 55        | 1.42%   |
| Logitech Webcam C270                                    | 50        | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                         | 47        | 1.21%   |
| Samsung Galaxy A5 (MTP)                                 | 45        | 1.16%   |
| Apple Built-in iSight                                   | 45        | 1.16%   |
| Apple FaceTime HD Camera (Built-in)                     | 44        | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 39        | 1%      |
| Chicony USB2.0 Camera                                   | 38        | 0.98%   |
| Microdia Integrated Webcam                              | 36        | 0.93%   |
| Microdia Webcam Vitade AF                               | 33        | 0.85%   |
| Microsoft LifeCam HD-3000                               | 32        | 0.82%   |
| Chicony USB 2.0 Camera                                  | 32        | 0.82%   |
| Microdia USB 2.0 Camera                                 | 31        | 0.8%    |
| Lite-On Integrated Camera                               | 31        | 0.8%    |
| Realtek USB Camera                                      | 30        | 0.77%   |
| Acer BisonCam,NB Pro                                    | 30        | 0.77%   |
| Chicony HP TrueVision HD Camera                         | 29        | 0.75%   |
| Chicony HP Truevision HD                                | 28        | 0.72%   |
| Chicony HP HD Camera                                    | 26        | 0.67%   |
| ARC International Camera                                | 26        | 0.67%   |
| Acer Integrated Camera                                  | 26        | 0.67%   |
| Syntek Lenovo EasyCamera                                | 24        | 0.62%   |
| Chicony VGA WebCam                                      | 24        | 0.62%   |
| Chicony HP Wide Vision HD Camera                        | 24        | 0.62%   |
| Chicony EasyCamera                                      | 24        | 0.62%   |
| Syntek Integrated Camera                                | 23        | 0.59%   |
| Microsoft LifeCam Cinema                                | 23        | 0.59%   |
| Acer SunplusIT Integrated Camera                        | 23        | 0.59%   |
| Apple FaceTime HD Camera                                | 22        | 0.57%   |
| Acer Lenovo EasyCamera                                  | 22        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)                 | 21        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 21        | 0.54%   |
| Quanta HD User Facing                                   | 20        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 198       | 30.37%  |
| Synaptics                          | 176       | 26.99%  |
| Shenzhen Goodix Technology         | 103       | 15.8%   |
| Upek                               | 47        | 7.21%   |
| AuthenTec                          | 46        | 7.06%   |
| Elan Microelectronics              | 31        | 4.75%   |
| LighTuning Technology              | 30        | 4.6%    |
| STMicroelectronics                 | 15        | 2.3%    |
| Samsung Electronics                | 2         | 0.31%   |
| HOLTEK                             | 2         | 0.31%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 55        | 8.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 7.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 5.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 5.83%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 5.06%   |
| Synaptics UWP WBDI                                                         | 29        | 4.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 3.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 3.68%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 3.53%   |
| Validity Sensors Synaptics WBDI                                            | 19        | 2.91%   |
| Synaptics  WBDI                                                            | 18        | 2.76%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 2.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.3%    |
| Validity Sensors VFS491                                                    | 14        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.15%   |
| Elan ELAN:Fingerprint                                                      | 14        | 2.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 1.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 1.99%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.99%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.84%   |
| AuthenTec AES2810                                                          | 11        | 1.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.53%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 1.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.38%   |
| Unknown                                                                    | 9         | 1.38%   |
| Synaptics WBDI Device                                                      | 8         | 1.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.07%   |
| Elan ELAN:ARM-M4                                                           | 7         | 1.07%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.07%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.77%   |
| Synaptics WBDI                                                             | 5         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.77%   |
| AuthenTec AES1600                                                          | 5         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.61%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 163       | 51.75%  |
| Alcor Micro               | 69        | 21.9%   |
| Upek                      | 24        | 7.62%   |
| Lenovo                    | 23        | 7.3%    |
| O2 Micro                  | 21        | 6.67%   |
| Gemalto (was Gemplus)     | 4         | 1.27%   |
| SCM Microsystems          | 3         | 0.95%   |
| Yubico.com                | 1         | 0.32%   |
| Purism, SPC               | 1         | 0.32%   |
| OmniKey                   | 1         | 0.32%   |
| Hewlett-Packard           | 1         | 0.32%   |
| Clay Logic                | 1         | 0.32%   |
| Chicony Electronics       | 1         | 0.32%   |
| BIT4ID                    | 1         | 0.32%   |
| Aladdin Knowledge Systems | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 21.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 65        | 20.63%  |
| Broadcom 5880                                                                | 43        | 13.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 8.89%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 7.62%   |
| Broadcom 58200                                                               | 23        | 7.3%    |
| Lenovo Integrated Smart Card Reader                                          | 21        | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 5.08%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.59%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.95%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.63%   |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.32%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.32%   |
| Purism, SPC Librem Key                                                       | 1         | 0.32%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.32%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.32%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.32%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.32%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.32%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4896      | 70.66%  |
| 1     | 1596      | 23.03%  |
| 2     | 354       | 5.11%   |
| 3     | 59        | 0.85%   |
| 4     | 13        | 0.19%   |
| 5     | 5         | 0.07%   |
| 7     | 3         | 0.04%   |
| 6     | 2         | 0.03%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 635       | 25.71%  |
| Graphics card            | 548       | 22.19%  |
| Net/wireless             | 393       | 15.91%  |
| Chipcard                 | 285       | 11.54%  |
| Multimedia controller    | 142       | 5.75%   |
| Communication controller | 112       | 4.53%   |
| Unassigned class         | 55        | 2.23%   |
| Sound                    | 54        | 2.19%   |
| Camera                   | 48        | 1.94%   |
| Bluetooth                | 47        | 1.9%    |
| Storage                  | 38        | 1.54%   |
| Net/ethernet             | 23        | 0.93%   |
| Card reader              | 21        | 0.85%   |
| Modem                    | 18        | 0.73%   |
| Network                  | 15        | 0.61%   |
| Storage/raid             | 9         | 0.36%   |
| Flash memory             | 8         | 0.32%   |
| Dvb card                 | 6         | 0.24%   |
| Firewire controller      | 5         | 0.2%    |
| Storage/ide              | 4         | 0.16%   |
| Storage/nvme             | 3         | 0.12%   |
| Unclassified device      | 1         | 0.04%   |

