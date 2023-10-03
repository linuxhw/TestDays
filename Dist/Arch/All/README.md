Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 9955

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b85781f0d8](https://linux-hardware.org/?probe=b85781f0d8) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [493a83e70a](https://linux-hardware.org/?probe=493a83e70a) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6ee0910511](https://linux-hardware.org/?probe=6ee0910511) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| eMachines     | eME732Z                     | Notebook    | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [30268d41d2](https://linux-hardware.org/?probe=30268d41d2) | Sep 29, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [0536b81a43](https://linux-hardware.org/?probe=0536b81a43) | Sep 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6d725a3ede](https://linux-hardware.org/?probe=6d725a3ede) | Sep 29, 2023 |
| Google        | Lindar                      | Notebook    | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [451d8ac4ca](https://linux-hardware.org/?probe=451d8ac4ca) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |
| Dell          | Latitude 3540               | Notebook    | [eb8bf9b174](https://linux-hardware.org/?probe=eb8bf9b174) | Sep 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [c7e7205fff](https://linux-hardware.org/?probe=c7e7205fff) | Sep 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ef982a7d39](https://linux-hardware.org/?probe=ef982a7d39) | Sep 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d8f229b5d7](https://linux-hardware.org/?probe=d8f229b5d7) | Sep 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [0e80b66cb6](https://linux-hardware.org/?probe=0e80b66cb6) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [742cfeafb0](https://linux-hardware.org/?probe=742cfeafb0) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a7d0f8e075](https://linux-hardware.org/?probe=a7d0f8e075) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [fee8085d8d](https://linux-hardware.org/?probe=fee8085d8d) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1ce8f959f1](https://linux-hardware.org/?probe=1ce8f959f1) | Sep 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [549941d843](https://linux-hardware.org/?probe=549941d843) | Sep 25, 2023 |
| Samsung       | 750XDA                      | Notebook    | [dd03d00004](https://linux-hardware.org/?probe=dd03d00004) | Sep 25, 2023 |
| MSI           | Bravo 15 C7VF               | Notebook    | [ab0a5a435f](https://linux-hardware.org/?probe=ab0a5a435f) | Sep 25, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c50564e3bb](https://linux-hardware.org/?probe=c50564e3bb) | Sep 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [6185e37a03](https://linux-hardware.org/?probe=6185e37a03) | Sep 25, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1375d355a5](https://linux-hardware.org/?probe=1375d355a5) | Sep 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [efb0e356d6](https://linux-hardware.org/?probe=efb0e356d6) | Sep 24, 2023 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [ed2e5eed86](https://linux-hardware.org/?probe=ed2e5eed86) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [2075d98d66](https://linux-hardware.org/?probe=2075d98d66) | Sep 24, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [685f51111f](https://linux-hardware.org/?probe=685f51111f) | Sep 24, 2023 |
| ASRock        | H97 Anniversary             | Desktop     | [018c8fa4d1](https://linux-hardware.org/?probe=018c8fa4d1) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | Notebook    | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [234fc6a6fb](https://linux-hardware.org/?probe=234fc6a6fb) | Sep 24, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [903a13bdf8](https://linux-hardware.org/?probe=903a13bdf8) | Sep 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [109081e9e3](https://linux-hardware.org/?probe=109081e9e3) | Sep 23, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6353ffcdf5](https://linux-hardware.org/?probe=6353ffcdf5) | Sep 23, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [8327fd670f](https://linux-hardware.org/?probe=8327fd670f) | Sep 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [d18e2d8811](https://linux-hardware.org/?probe=d18e2d8811) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| Biostar       | B85MG                       | Desktop     | [f71d8a75fc](https://linux-hardware.org/?probe=f71d8a75fc) | Sep 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [900334906e](https://linux-hardware.org/?probe=900334906e) | Sep 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [010c663b72](https://linux-hardware.org/?probe=010c663b72) | Sep 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [0f097b1b88](https://linux-hardware.org/?probe=0f097b1b88) | Sep 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [162ff29125](https://linux-hardware.org/?probe=162ff29125) | Sep 22, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [d9d063b9e8](https://linux-hardware.org/?probe=d9d063b9e8) | Sep 22, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | Notebook    | [8c65f7a68a](https://linux-hardware.org/?probe=8c65f7a68a) | Sep 21, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [37990955f8](https://linux-hardware.org/?probe=37990955f8) | Sep 21, 2023 |
| MSI           | A88XM-E45                   | Desktop     | [99b5c7c976](https://linux-hardware.org/?probe=99b5c7c976) | Sep 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | Notebook    | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6c75af44c4](https://linux-hardware.org/?probe=6c75af44c4) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [5dae6d6eda](https://linux-hardware.org/?probe=5dae6d6eda) | Sep 21, 2023 |
| Lenovo        | ThinkPad L540 20AU006CRI    | Notebook    | [e8885911a0](https://linux-hardware.org/?probe=e8885911a0) | Sep 21, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bb796b1e6e](https://linux-hardware.org/?probe=bb796b1e6e) | Sep 21, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4d863063d6](https://linux-hardware.org/?probe=4d863063d6) | Sep 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [2310ddb9a7](https://linux-hardware.org/?probe=2310ddb9a7) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [ae062bd5ca](https://linux-hardware.org/?probe=ae062bd5ca) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2489245463](https://linux-hardware.org/?probe=2489245463) | Sep 21, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [6aae39a72b](https://linux-hardware.org/?probe=6aae39a72b) | Sep 21, 2023 |
| Unknown       | HX90                        | Desktop     | [a48f203afc](https://linux-hardware.org/?probe=a48f203afc) | Sep 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [3762f344e9](https://linux-hardware.org/?probe=3762f344e9) | Sep 21, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [7ee2b2178d](https://linux-hardware.org/?probe=7ee2b2178d) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [49ed4b61ff](https://linux-hardware.org/?probe=49ed4b61ff) | Sep 20, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [a2f44141ba](https://linux-hardware.org/?probe=a2f44141ba) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [91c2eeef2f](https://linux-hardware.org/?probe=91c2eeef2f) | Sep 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0d52c010c8](https://linux-hardware.org/?probe=0d52c010c8) | Sep 20, 2023 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [4959eecff1](https://linux-hardware.org/?probe=4959eecff1) | Sep 19, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [6ed76f72d7](https://linux-hardware.org/?probe=6ed76f72d7) | Sep 19, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [1c48bd9962](https://linux-hardware.org/?probe=1c48bd9962) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [58682c1938](https://linux-hardware.org/?probe=58682c1938) | Sep 19, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [1929f30e86](https://linux-hardware.org/?probe=1929f30e86) | Sep 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [85d131b5fc](https://linux-hardware.org/?probe=85d131b5fc) | Sep 18, 2023 |
| AZW           | GTR V02                     | Desktop     | [094b661573](https://linux-hardware.org/?probe=094b661573) | Sep 18, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8922ced8ec](https://linux-hardware.org/?probe=8922ced8ec) | Sep 18, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a7f191e99f](https://linux-hardware.org/?probe=a7f191e99f) | Sep 18, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [50a48f1548](https://linux-hardware.org/?probe=50a48f1548) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [07d34fd9b5](https://linux-hardware.org/?probe=07d34fd9b5) | Sep 18, 2023 |
| Dell          | Latitude 5501               | Notebook    | [66b2685ca5](https://linux-hardware.org/?probe=66b2685ca5) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f12a86bf92](https://linux-hardware.org/?probe=f12a86bf92) | Sep 18, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [cdb4402859](https://linux-hardware.org/?probe=cdb4402859) | Sep 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Gigabyte      | Z97P-D3                     | Desktop     | [3baa74b1a6](https://linux-hardware.org/?probe=3baa74b1a6) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [544f02c423](https://linux-hardware.org/?probe=544f02c423) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| Lenovo        | ThinkPad X220 4290LT8       | Notebook    | [56d2386012](https://linux-hardware.org/?probe=56d2386012) | Sep 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [ba8a270a86](https://linux-hardware.org/?probe=ba8a270a86) | Sep 17, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [eaffff1bae](https://linux-hardware.org/?probe=eaffff1bae) | Sep 17, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [959cef0f9e](https://linux-hardware.org/?probe=959cef0f9e) | Sep 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [33ec9c1d72](https://linux-hardware.org/?probe=33ec9c1d72) | Sep 16, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [0b88f9bfaa](https://linux-hardware.org/?probe=0b88f9bfaa) | Sep 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [0f3cba16d7](https://linux-hardware.org/?probe=0f3cba16d7) | Sep 16, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [afbaf99497](https://linux-hardware.org/?probe=afbaf99497) | Sep 16, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [bd6e35e433](https://linux-hardware.org/?probe=bd6e35e433) | Sep 16, 2023 |
| ASUSTek       | ROG Maximus Z790 APEX       | Desktop     | [76d354fede](https://linux-hardware.org/?probe=76d354fede) | Sep 16, 2023 |
| ASUSTek       | ROG Maximus Z790 APEX       | Desktop     | [ae35c7426c](https://linux-hardware.org/?probe=ae35c7426c) | Sep 16, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [c63f4e5865](https://linux-hardware.org/?probe=c63f4e5865) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [282def5c2a](https://linux-hardware.org/?probe=282def5c2a) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0f78dca6c4](https://linux-hardware.org/?probe=0f78dca6c4) | Sep 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dd637b6425](https://linux-hardware.org/?probe=dd637b6425) | Sep 15, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [51c7125a22](https://linux-hardware.org/?probe=51c7125a22) | Sep 15, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [354d2de54e](https://linux-hardware.org/?probe=354d2de54e) | Sep 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [fca517e53f](https://linux-hardware.org/?probe=fca517e53f) | Sep 15, 2023 |
| Timi          | A35S                        | Notebook    | [b229627e35](https://linux-hardware.org/?probe=b229627e35) | Sep 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3b3ba64d46](https://linux-hardware.org/?probe=3b3ba64d46) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [c3d0531198](https://linux-hardware.org/?probe=c3d0531198) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [c4b64b54dd](https://linux-hardware.org/?probe=c4b64b54dd) | Sep 14, 2023 |
| Lenovo        | ThinkPad T470 20HES6HC00    | Notebook    | [040dc9433a](https://linux-hardware.org/?probe=040dc9433a) | Sep 14, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [116c17dd99](https://linux-hardware.org/?probe=116c17dd99) | Sep 13, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bc40188dda](https://linux-hardware.org/?probe=bc40188dda) | Sep 13, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | Notebook    | [b8b03de96a](https://linux-hardware.org/?probe=b8b03de96a) | Sep 13, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ac50c36768](https://linux-hardware.org/?probe=ac50c36768) | Sep 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [93563efdab](https://linux-hardware.org/?probe=93563efdab) | Sep 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [87bcf1d18a](https://linux-hardware.org/?probe=87bcf1d18a) | Sep 13, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [74ab1950fb](https://linux-hardware.org/?probe=74ab1950fb) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0XL0... | Notebook    | [31e98e457c](https://linux-hardware.org/?probe=31e98e457c) | Sep 13, 2023 |
| Lenovo        | ThinkPad T450s 20BWS03F0... | Notebook    | [772c104a64](https://linux-hardware.org/?probe=772c104a64) | Sep 13, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [1df9430f46](https://linux-hardware.org/?probe=1df9430f46) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [23ded25239](https://linux-hardware.org/?probe=23ded25239) | Sep 12, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [c122d5178e](https://linux-hardware.org/?probe=c122d5178e) | Sep 12, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [3d297f7444](https://linux-hardware.org/?probe=3d297f7444) | Sep 12, 2023 |
| ECS           | A880GM-AD3                  | Desktop     | [828f89ff31](https://linux-hardware.org/?probe=828f89ff31) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [c8ef60f2e0](https://linux-hardware.org/?probe=c8ef60f2e0) | Sep 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [471faa50e0](https://linux-hardware.org/?probe=471faa50e0) | Sep 12, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [d5d9b73baa](https://linux-hardware.org/?probe=d5d9b73baa) | Sep 11, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [f1cff1b2ac](https://linux-hardware.org/?probe=f1cff1b2ac) | Sep 11, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [3aef7779ec](https://linux-hardware.org/?probe=3aef7779ec) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [afa0844d9f](https://linux-hardware.org/?probe=afa0844d9f) | Sep 11, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d5b7a64e3b](https://linux-hardware.org/?probe=d5b7a64e3b) | Sep 11, 2023 |
| HP            | 2B36                        | Desktop     | [ac92866980](https://linux-hardware.org/?probe=ac92866980) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [f7546a9d25](https://linux-hardware.org/?probe=f7546a9d25) | Sep 11, 2023 |
| ASRock        | X399M Taichi                | Desktop     | [00c370a89d](https://linux-hardware.org/?probe=00c370a89d) | Sep 11, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [41a8df4387](https://linux-hardware.org/?probe=41a8df4387) | Sep 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d561f541f6](https://linux-hardware.org/?probe=d561f541f6) | Sep 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [982a0e5ce2](https://linux-hardware.org/?probe=982a0e5ce2) | Sep 10, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8bc39de267](https://linux-hardware.org/?probe=8bc39de267) | Sep 10, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [a6c468e52d](https://linux-hardware.org/?probe=a6c468e52d) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [320bbb4e83](https://linux-hardware.org/?probe=320bbb4e83) | Sep 10, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [534003f1ab](https://linux-hardware.org/?probe=534003f1ab) | Sep 10, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [838e1d8f4a](https://linux-hardware.org/?probe=838e1d8f4a) | Sep 10, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b6a07d9f09](https://linux-hardware.org/?probe=b6a07d9f09) | Sep 10, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [227cff101d](https://linux-hardware.org/?probe=227cff101d) | Sep 10, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [fab8427f08](https://linux-hardware.org/?probe=fab8427f08) | Sep 09, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [3b97b2d662](https://linux-hardware.org/?probe=3b97b2d662) | Sep 09, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [be54d62e88](https://linux-hardware.org/?probe=be54d62e88) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [57e235e93d](https://linux-hardware.org/?probe=57e235e93d) | Sep 09, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [1715b12029](https://linux-hardware.org/?probe=1715b12029) | Sep 09, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [d8694d48fe](https://linux-hardware.org/?probe=d8694d48fe) | Sep 09, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [dd0683372d](https://linux-hardware.org/?probe=dd0683372d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [2e5644f065](https://linux-hardware.org/?probe=2e5644f065) | Sep 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [720beb724e](https://linux-hardware.org/?probe=720beb724e) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| Dell          | Latitude E5400              | Notebook    | [0ede91c6cd](https://linux-hardware.org/?probe=0ede91c6cd) | Sep 08, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [b3a181910f](https://linux-hardware.org/?probe=b3a181910f) | Sep 08, 2023 |
| HP            | Laptop 15s-fr1xxx           | Notebook    | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Dell          | Latitude E5400              | Notebook    | [727b5526f9](https://linux-hardware.org/?probe=727b5526f9) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [905f93bc0a](https://linux-hardware.org/?probe=905f93bc0a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e87517b925](https://linux-hardware.org/?probe=e87517b925) | Sep 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b6de5d8503](https://linux-hardware.org/?probe=b6de5d8503) | Sep 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b6686658dc](https://linux-hardware.org/?probe=b6686658dc) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [26448cf759](https://linux-hardware.org/?probe=26448cf759) | Sep 07, 2023 |
| HP            | Pavilion 15                 | Notebook    | [6ab4c7f2d8](https://linux-hardware.org/?probe=6ab4c7f2d8) | Sep 07, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c251475f43](https://linux-hardware.org/?probe=c251475f43) | Sep 07, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [32c21f0b73](https://linux-hardware.org/?probe=32c21f0b73) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f33c62ab06](https://linux-hardware.org/?probe=f33c62ab06) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [373ba724e4](https://linux-hardware.org/?probe=373ba724e4) | Sep 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c22fad9c67](https://linux-hardware.org/?probe=c22fad9c67) | Sep 06, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [307ca05754](https://linux-hardware.org/?probe=307ca05754) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | Notebook    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| Microsoft     | Surface Book 2              | Tablet      | [de36160f60](https://linux-hardware.org/?probe=de36160f60) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [ee70bf217a](https://linux-hardware.org/?probe=ee70bf217a) | Sep 06, 2023 |
| Pegatron      | 2AD3                        | Desktop     | [07cfb5b967](https://linux-hardware.org/?probe=07cfb5b967) | Sep 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [9c7d201848](https://linux-hardware.org/?probe=9c7d201848) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [cd4ccc8478](https://linux-hardware.org/?probe=cd4ccc8478) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| Samsung       | 750XDA                      | Notebook    | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [1fce93cab3](https://linux-hardware.org/?probe=1fce93cab3) | Sep 05, 2023 |
| Acer          | Veriton M480                | Desktop     | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ceade9f24f](https://linux-hardware.org/?probe=ceade9f24f) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4a93cea12b](https://linux-hardware.org/?probe=4a93cea12b) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | Notebook    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [81f816e956](https://linux-hardware.org/?probe=81f816e956) | Sep 03, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [d208a16a1b](https://linux-hardware.org/?probe=d208a16a1b) | Sep 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [2eed39fb24](https://linux-hardware.org/?probe=2eed39fb24) | Sep 03, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [d6be71642e](https://linux-hardware.org/?probe=d6be71642e) | Sep 03, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [79ca2081a1](https://linux-hardware.org/?probe=79ca2081a1) | Sep 03, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [b8aba55b59](https://linux-hardware.org/?probe=b8aba55b59) | Sep 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [99b1fcf2e9](https://linux-hardware.org/?probe=99b1fcf2e9) | Sep 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [56520c8e8d](https://linux-hardware.org/?probe=56520c8e8d) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [ad65335e8d](https://linux-hardware.org/?probe=ad65335e8d) | Sep 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9ab3e57ab7](https://linux-hardware.org/?probe=9ab3e57ab7) | Sep 02, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Dell          | 030VXY A02                  | Desktop     | [ff787e57bc](https://linux-hardware.org/?probe=ff787e57bc) | Sep 01, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f39e23df01](https://linux-hardware.org/?probe=f39e23df01) | Sep 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0c18cf228](https://linux-hardware.org/?probe=e0c18cf228) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [32d9616a38](https://linux-hardware.org/?probe=32d9616a38) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [2a0a234dbf](https://linux-hardware.org/?probe=2a0a234dbf) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| MSI           | MS-7E06                     | Notebook    | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [6d0b6e95ba](https://linux-hardware.org/?probe=6d0b6e95ba) | Aug 30, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [9327ae4f97](https://linux-hardware.org/?probe=9327ae4f97) | Aug 30, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [ce793ccb8d](https://linux-hardware.org/?probe=ce793ccb8d) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6dd95e8115](https://linux-hardware.org/?probe=6dd95e8115) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [f253067fa5](https://linux-hardware.org/?probe=f253067fa5) | Aug 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [aa23e296ad](https://linux-hardware.org/?probe=aa23e296ad) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7d74c2bc61](https://linux-hardware.org/?probe=7d74c2bc61) | Aug 29, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0b44043b10](https://linux-hardware.org/?probe=0b44043b10) | Aug 29, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [dcceb74a56](https://linux-hardware.org/?probe=dcceb74a56) | Aug 29, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [c5fb822b1c](https://linux-hardware.org/?probe=c5fb822b1c) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [baf0966633](https://linux-hardware.org/?probe=baf0966633) | Aug 29, 2023 |
| Acer          | One Z1402                   | Notebook    | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [f209f11620](https://linux-hardware.org/?probe=f209f11620) | Aug 29, 2023 |
| Huanan        | H610M-PLUS V1.2             | Desktop     | [083aaaf1eb](https://linux-hardware.org/?probe=083aaaf1eb) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0817c6178e](https://linux-hardware.org/?probe=0817c6178e) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0a2adee694](https://linux-hardware.org/?probe=0a2adee694) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [56692679f3](https://linux-hardware.org/?probe=56692679f3) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [c2c0708639](https://linux-hardware.org/?probe=c2c0708639) | Aug 28, 2023 |
| ECS           | G31T-M7                     | Desktop     | [f095887170](https://linux-hardware.org/?probe=f095887170) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [e178a50d54](https://linux-hardware.org/?probe=e178a50d54) | Aug 27, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [3c68838457](https://linux-hardware.org/?probe=3c68838457) | Aug 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4e7e2a9946](https://linux-hardware.org/?probe=4e7e2a9946) | Aug 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [b7020427e0](https://linux-hardware.org/?probe=b7020427e0) | Aug 27, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [2a25ad0be2](https://linux-hardware.org/?probe=2a25ad0be2) | Aug 27, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [9b94ab3887](https://linux-hardware.org/?probe=9b94ab3887) | Aug 27, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [e16786f57e](https://linux-hardware.org/?probe=e16786f57e) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7425d71f52](https://linux-hardware.org/?probe=7425d71f52) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [fc86b0463f](https://linux-hardware.org/?probe=fc86b0463f) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f30251883f](https://linux-hardware.org/?probe=f30251883f) | Aug 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [e3c32f6873](https://linux-hardware.org/?probe=e3c32f6873) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [555c7d17f0](https://linux-hardware.org/?probe=555c7d17f0) | Aug 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2668db7570](https://linux-hardware.org/?probe=2668db7570) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a86d43941](https://linux-hardware.org/?probe=3a86d43941) | Aug 25, 2023 |
| HP            | 1497                        | Desktop     | [32a8075d02](https://linux-hardware.org/?probe=32a8075d02) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [f5f6d366a1](https://linux-hardware.org/?probe=f5f6d366a1) | Aug 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [9d09e14624](https://linux-hardware.org/?probe=9d09e14624) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7486221845](https://linux-hardware.org/?probe=7486221845) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [60588f77af](https://linux-hardware.org/?probe=60588f77af) | Aug 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [368f9f947b](https://linux-hardware.org/?probe=368f9f947b) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Dell          | 07978V A10                  | Server      | [dcd73b2802](https://linux-hardware.org/?probe=dcd73b2802) | Aug 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [95b9733408](https://linux-hardware.org/?probe=95b9733408) | Aug 23, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [34532a7998](https://linux-hardware.org/?probe=34532a7998) | Aug 23, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6c9f647d44](https://linux-hardware.org/?probe=6c9f647d44) | Aug 23, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [6e915a1913](https://linux-hardware.org/?probe=6e915a1913) | Aug 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8e478e15da](https://linux-hardware.org/?probe=8e478e15da) | Aug 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [cdb0c49b6a](https://linux-hardware.org/?probe=cdb0c49b6a) | Aug 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4bc2673b83](https://linux-hardware.org/?probe=4bc2673b83) | Aug 21, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [f76b91821d](https://linux-hardware.org/?probe=f76b91821d) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS5WH0D     | Notebook    | [ae8a51b2f5](https://linux-hardware.org/?probe=ae8a51b2f5) | Aug 21, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [41ba06b203](https://linux-hardware.org/?probe=41ba06b203) | Aug 21, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [005b310c55](https://linux-hardware.org/?probe=005b310c55) | Aug 20, 2023 |
| AZW           | GTR V11                     | Desktop     | [9aefbc3e69](https://linux-hardware.org/?probe=9aefbc3e69) | Aug 20, 2023 |
| Intel         | X99                         | Desktop     | [c1ad35e185](https://linux-hardware.org/?probe=c1ad35e185) | Aug 20, 2023 |
| HP            | 2B29                        | Desktop     | [62f37a51ca](https://linux-hardware.org/?probe=62f37a51ca) | Aug 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [13bcbc11d7](https://linux-hardware.org/?probe=13bcbc11d7) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [19675df004](https://linux-hardware.org/?probe=19675df004) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [b156da40ac](https://linux-hardware.org/?probe=b156da40ac) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603VV... | Notebook    | [8b4709e684](https://linux-hardware.org/?probe=8b4709e684) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [778ea97c77](https://linux-hardware.org/?probe=778ea97c77) | Aug 20, 2023 |
| TYAN Compu... | S8010                       | Desktop     | [a381c313e3](https://linux-hardware.org/?probe=a381c313e3) | Aug 20, 2023 |
| Alienware     | m15 R4                      | Notebook    | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [5724c221b8](https://linux-hardware.org/?probe=5724c221b8) | Aug 19, 2023 |
| Alienware     | m15 R4                      | Notebook    | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [006d138f62](https://linux-hardware.org/?probe=006d138f62) | Aug 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [767b42eeca](https://linux-hardware.org/?probe=767b42eeca) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3c0bf7ce7b](https://linux-hardware.org/?probe=3c0bf7ce7b) | Aug 18, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [7a9ae970e6](https://linux-hardware.org/?probe=7a9ae970e6) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [1289521063](https://linux-hardware.org/?probe=1289521063) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [caae17275e](https://linux-hardware.org/?probe=caae17275e) | Aug 17, 2023 |
| Notebook      | NS50MU                      | Notebook    | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [94b9b057b4](https://linux-hardware.org/?probe=94b9b057b4) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [14ea4148dc](https://linux-hardware.org/?probe=14ea4148dc) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | Notebook    | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| CWWK          | N3050 P1                    | Desktop     | [dd3dfb0c02](https://linux-hardware.org/?probe=dd3dfb0c02) | Aug 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [bfe3223b92](https://linux-hardware.org/?probe=bfe3223b92) | Aug 17, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b9ce6dd48c](https://linux-hardware.org/?probe=b9ce6dd48c) | Aug 16, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [39a98650a3](https://linux-hardware.org/?probe=39a98650a3) | Aug 16, 2023 |
| Timi          | A35S                        | Notebook    | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [c8ed9b0cb2](https://linux-hardware.org/?probe=c8ed9b0cb2) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [24a5a21c43](https://linux-hardware.org/?probe=24a5a21c43) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [accdc886c7](https://linux-hardware.org/?probe=accdc886c7) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [96d94e5f6c](https://linux-hardware.org/?probe=96d94e5f6c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5652688ceb](https://linux-hardware.org/?probe=5652688ceb) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7463d795e8](https://linux-hardware.org/?probe=7463d795e8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [38e95ded09](https://linux-hardware.org/?probe=38e95ded09) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [651eae5b59](https://linux-hardware.org/?probe=651eae5b59) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d32a9fb8a4](https://linux-hardware.org/?probe=d32a9fb8a4) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5929bf1039](https://linux-hardware.org/?probe=5929bf1039) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ac0320b2ee](https://linux-hardware.org/?probe=ac0320b2ee) | Aug 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [78e30cb8ef](https://linux-hardware.org/?probe=78e30cb8ef) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e2a4a35103](https://linux-hardware.org/?probe=e2a4a35103) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5d52bf85ca](https://linux-hardware.org/?probe=5d52bf85ca) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f972a8359d](https://linux-hardware.org/?probe=f972a8359d) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ab0235d27c](https://linux-hardware.org/?probe=ab0235d27c) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [3446b719ab](https://linux-hardware.org/?probe=3446b719ab) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e53e56fcbc](https://linux-hardware.org/?probe=e53e56fcbc) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [b223cba859](https://linux-hardware.org/?probe=b223cba859) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| ECS           | G31T-M7                     | Desktop     | [2d35b5e140](https://linux-hardware.org/?probe=2d35b5e140) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Intel         | X79M-S                      | Desktop     | [043e072c46](https://linux-hardware.org/?probe=043e072c46) | Aug 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e6fe434dfa](https://linux-hardware.org/?probe=e6fe434dfa) | Aug 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| NZXT          | N7 B550                     | Desktop     | [6cf14ccbe3](https://linux-hardware.org/?probe=6cf14ccbe3) | Aug 13, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [a6212b25ea](https://linux-hardware.org/?probe=a6212b25ea) | Aug 13, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [494c725472](https://linux-hardware.org/?probe=494c725472) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [e03e2f8abc](https://linux-hardware.org/?probe=e03e2f8abc) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [8ef51956a9](https://linux-hardware.org/?probe=8ef51956a9) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [f7ab4aa00a](https://linux-hardware.org/?probe=f7ab4aa00a) | Aug 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [504746e40c](https://linux-hardware.org/?probe=504746e40c) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49662a8ac9](https://linux-hardware.org/?probe=49662a8ac9) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c946b79f5a](https://linux-hardware.org/?probe=c946b79f5a) | Aug 12, 2023 |
| Alienware     | 15                          | Notebook    | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3181a592ac](https://linux-hardware.org/?probe=3181a592ac) | Aug 12, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [144f77980e](https://linux-hardware.org/?probe=144f77980e) | Aug 11, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [e2ebf1941c](https://linux-hardware.org/?probe=e2ebf1941c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7fe6adce5e](https://linux-hardware.org/?probe=7fe6adce5e) | Aug 10, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | Notebook    | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | Notebook    | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6e7a8f72dd](https://linux-hardware.org/?probe=6e7a8f72dd) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [fdfeffb5f3](https://linux-hardware.org/?probe=fdfeffb5f3) | Aug 10, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [71424c4380](https://linux-hardware.org/?probe=71424c4380) | Aug 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84d6b99d2c](https://linux-hardware.org/?probe=84d6b99d2c) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [45da50b5c8](https://linux-hardware.org/?probe=45da50b5c8) | Aug 10, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [03cb2690f7](https://linux-hardware.org/?probe=03cb2690f7) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| HP            | Pavilion 17                 | Notebook    | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [939205ed85](https://linux-hardware.org/?probe=939205ed85) | Aug 09, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [afef0bb361](https://linux-hardware.org/?probe=afef0bb361) | Aug 09, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [3ecd6d3f74](https://linux-hardware.org/?probe=3ecd6d3f74) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [0b797c9368](https://linux-hardware.org/?probe=0b797c9368) | Aug 08, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [90fbc716ed](https://linux-hardware.org/?probe=90fbc716ed) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | Notebook    | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [608c3967b2](https://linux-hardware.org/?probe=608c3967b2) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [e6955ee04c](https://linux-hardware.org/?probe=e6955ee04c) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f772c670ff](https://linux-hardware.org/?probe=f772c670ff) | Aug 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fc8b72dd99](https://linux-hardware.org/?probe=fc8b72dd99) | Aug 07, 2023 |
| MSI           | H370M BAZOOKA               | Desktop     | [760051e27b](https://linux-hardware.org/?probe=760051e27b) | Aug 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| MSI           | Z270 TOMAHAWK OPT BOOST     | Desktop     | [6baabbdd21](https://linux-hardware.org/?probe=6baabbdd21) | Aug 06, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [01b9adfb02](https://linux-hardware.org/?probe=01b9adfb02) | Aug 05, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [21eaf09dc9](https://linux-hardware.org/?probe=21eaf09dc9) | Aug 05, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f6981c56b7](https://linux-hardware.org/?probe=f6981c56b7) | Aug 05, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9365c3de56](https://linux-hardware.org/?probe=9365c3de56) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [2f2d909df8](https://linux-hardware.org/?probe=2f2d909df8) | Aug 05, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c4d1667ffe](https://linux-hardware.org/?probe=c4d1667ffe) | Aug 05, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [da235e8c08](https://linux-hardware.org/?probe=da235e8c08) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [64810e5a10](https://linux-hardware.org/?probe=64810e5a10) | Aug 05, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [71ca443602](https://linux-hardware.org/?probe=71ca443602) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| HP            | 83E8                        | Desktop     | [0d285189b9](https://linux-hardware.org/?probe=0d285189b9) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| PC Special... | Lafite Pro III 17           | Notebook    | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [a251ad988c](https://linux-hardware.org/?probe=a251ad988c) | Aug 03, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [1d1937f1d6](https://linux-hardware.org/?probe=1d1937f1d6) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [67d851300e](https://linux-hardware.org/?probe=67d851300e) | Aug 03, 2023 |
| Timi          | A7S                         | Notebook    | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| LG Electro... | 16Z90R-K.ADB9U1             | Notebook    | [d3a9e05559](https://linux-hardware.org/?probe=d3a9e05559) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [2703b03104](https://linux-hardware.org/?probe=2703b03104) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [28f1074e0a](https://linux-hardware.org/?probe=28f1074e0a) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [8918c544fe](https://linux-hardware.org/?probe=8918c544fe) | Aug 01, 2023 |
| Dell          | Latitude 5590               | Notebook    | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [cb322d77a4](https://linux-hardware.org/?probe=cb322d77a4) | Aug 01, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [35f27e05c6](https://linux-hardware.org/?probe=35f27e05c6) | Jul 31, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [af6a2cb993](https://linux-hardware.org/?probe=af6a2cb993) | Jul 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Dell          | G15 5511                    | Notebook    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | Notebook    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [264f400d7e](https://linux-hardware.org/?probe=264f400d7e) | Jul 30, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e16ea772e1](https://linux-hardware.org/?probe=e16ea772e1) | Jul 30, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [28ff56233b](https://linux-hardware.org/?probe=28ff56233b) | Jul 30, 2023 |
| Dell          | Latitude 5421               | Notebook    | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [5e1021c76b](https://linux-hardware.org/?probe=5e1021c76b) | Jul 30, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [3bbfa332c0](https://linux-hardware.org/?probe=3bbfa332c0) | Jul 30, 2023 |
| HP            | 843B                        | Desktop     | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e43da17360](https://linux-hardware.org/?probe=e43da17360) | Jul 29, 2023 |
| Razer         | Blade                       | Notebook    | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e4efeb0276](https://linux-hardware.org/?probe=e4efeb0276) | Jul 29, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [30e5e63466](https://linux-hardware.org/?probe=30e5e63466) | Jul 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [6426edf740](https://linux-hardware.org/?probe=6426edf740) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | Notebook    | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8d3733b439](https://linux-hardware.org/?probe=8d3733b439) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [28bd5d7d66](https://linux-hardware.org/?probe=28bd5d7d66) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [aaa06048d5](https://linux-hardware.org/?probe=aaa06048d5) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire 5350                 | Notebook    | [698672b19c](https://linux-hardware.org/?probe=698672b19c) | Jul 28, 2023 |
| MSI           | Raider GE78HX 13VI          | Notebook    | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Google        | Atlas                       | Notebook    | [c3f0326575](https://linux-hardware.org/?probe=c3f0326575) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [407859fa58](https://linux-hardware.org/?probe=407859fa58) | Jul 27, 2023 |
| HP            | ProBook 4530s               | Notebook    | [46852380f2](https://linux-hardware.org/?probe=46852380f2) | Jul 27, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [2231e66b3d](https://linux-hardware.org/?probe=2231e66b3d) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [3516b91dc0](https://linux-hardware.org/?probe=3516b91dc0) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| MECHREVO      | F7BFD V1.0                  | Desktop     | [f9be0fc5a7](https://linux-hardware.org/?probe=f9be0fc5a7) | Jul 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8c8e7f5edd](https://linux-hardware.org/?probe=8c8e7f5edd) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6c978ec74d](https://linux-hardware.org/?probe=6c978ec74d) | Jul 26, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [864fcc639d](https://linux-hardware.org/?probe=864fcc639d) | Jul 25, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [787270abee](https://linux-hardware.org/?probe=787270abee) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [a326770d26](https://linux-hardware.org/?probe=a326770d26) | Jul 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [5399a2e19e](https://linux-hardware.org/?probe=5399a2e19e) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [6dbfb1d71e](https://linux-hardware.org/?probe=6dbfb1d71e) | Jul 24, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [b571da19fb](https://linux-hardware.org/?probe=b571da19fb) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | Notebook    | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [2a23928116](https://linux-hardware.org/?probe=2a23928116) | Jul 24, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [247870abec](https://linux-hardware.org/?probe=247870abec) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [f1db825d10](https://linux-hardware.org/?probe=f1db825d10) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [0e123e6d85](https://linux-hardware.org/?probe=0e123e6d85) | Jul 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [3dac76b45f](https://linux-hardware.org/?probe=3dac76b45f) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| ECS           | A780LM-M2                   | Desktop     | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [2f8efec736](https://linux-hardware.org/?probe=2f8efec736) | Jul 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| Biostar       | A320MH                      | Desktop     | [b4ad5e7452](https://linux-hardware.org/?probe=b4ad5e7452) | Jul 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [45065697ac](https://linux-hardware.org/?probe=45065697ac) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a96fbb9461](https://linux-hardware.org/?probe=a96fbb9461) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [d47c43e734](https://linux-hardware.org/?probe=d47c43e734) | Jul 22, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [a55a67fa01](https://linux-hardware.org/?probe=a55a67fa01) | Jul 22, 2023 |
| Acer          | Aspire V5-551               | Notebook    | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | Notebook    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [478fb56a7d](https://linux-hardware.org/?probe=478fb56a7d) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [cc9f1fdcd8](https://linux-hardware.org/?probe=cc9f1fdcd8) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [fc0fcad674](https://linux-hardware.org/?probe=fc0fcad674) | Jul 21, 2023 |
| Dell          | Latitude 5580               | Notebook    | [f115a04168](https://linux-hardware.org/?probe=f115a04168) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| Panasonic     | CFSZ5-3                     | Notebook    | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| ASUSTek       | VC66                        | Desktop     | [369cd2ba96](https://linux-hardware.org/?probe=369cd2ba96) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [9b44d7bd03](https://linux-hardware.org/?probe=9b44d7bd03) | Jul 19, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [7ab6252e08](https://linux-hardware.org/?probe=7ab6252e08) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | ZenBook UX562IA_UM562IA     | Convertible | [08b6a97698](https://linux-hardware.org/?probe=08b6a97698) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8a9fabbdc0](https://linux-hardware.org/?probe=8a9fabbdc0) | Jul 19, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [f145687601](https://linux-hardware.org/?probe=f145687601) | Jul 19, 2023 |
| AZW           | U59                         | Desktop     | [1c919967a8](https://linux-hardware.org/?probe=1c919967a8) | Jul 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [bf1f683383](https://linux-hardware.org/?probe=bf1f683383) | Jul 18, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c5475d0982](https://linux-hardware.org/?probe=c5475d0982) | Jul 18, 2023 |
| ONDA          | A320SD4-ITX Ver:2.00        | Desktop     | [ffe435deca](https://linux-hardware.org/?probe=ffe435deca) | Jul 18, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [7217058966](https://linux-hardware.org/?probe=7217058966) | Jul 18, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [e68c02f317](https://linux-hardware.org/?probe=e68c02f317) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [02f8df2129](https://linux-hardware.org/?probe=02f8df2129) | Jul 18, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7e056881b](https://linux-hardware.org/?probe=e7e056881b) | Jul 18, 2023 |
| Lenovo        | B50-45 20388                | Notebook    | [54b4137669](https://linux-hardware.org/?probe=54b4137669) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [50e78d6df5](https://linux-hardware.org/?probe=50e78d6df5) | Jul 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [53c97d91d4](https://linux-hardware.org/?probe=53c97d91d4) | Jul 18, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [4e4d74fab5](https://linux-hardware.org/?probe=4e4d74fab5) | Jul 17, 2023 |
| Dell          | 0TY565                      | Desktop     | [1d6edab344](https://linux-hardware.org/?probe=1d6edab344) | Jul 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [98acac35e7](https://linux-hardware.org/?probe=98acac35e7) | Jul 17, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [de9a7deb3b](https://linux-hardware.org/?probe=de9a7deb3b) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8464b9ef50](https://linux-hardware.org/?probe=8464b9ef50) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [5202874aa5](https://linux-hardware.org/?probe=5202874aa5) | Jul 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [7c39d851fd](https://linux-hardware.org/?probe=7c39d851fd) | Jul 16, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [3f15239dd2](https://linux-hardware.org/?probe=3f15239dd2) | Jul 16, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [cbab6d2236](https://linux-hardware.org/?probe=cbab6d2236) | Jul 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [01ed316904](https://linux-hardware.org/?probe=01ed316904) | Jul 16, 2023 |
| Lenovo        | M490s 20215                 | Notebook    | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e204dc6cf1](https://linux-hardware.org/?probe=e204dc6cf1) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4dc6731c7a](https://linux-hardware.org/?probe=4dc6731c7a) | Jul 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e32b594990](https://linux-hardware.org/?probe=e32b594990) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | Notebook    | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [1f05cae239](https://linux-hardware.org/?probe=1f05cae239) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S4NR00    | Notebook    | [281c5a429c](https://linux-hardware.org/?probe=281c5a429c) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a375f7685c](https://linux-hardware.org/?probe=a375f7685c) | Jul 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS0P300    | Notebook    | [2c96c19647](https://linux-hardware.org/?probe=2c96c19647) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [392b02a797](https://linux-hardware.org/?probe=392b02a797) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [222924f1c2](https://linux-hardware.org/?probe=222924f1c2) | Jul 12, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [ea9603099a](https://linux-hardware.org/?probe=ea9603099a) | Jul 12, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [39b5c3bb23](https://linux-hardware.org/?probe=39b5c3bb23) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b89cab90c0](https://linux-hardware.org/?probe=b89cab90c0) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| Dell          | Precision M4700             | Notebook    | [69a672ec44](https://linux-hardware.org/?probe=69a672ec44) | Jul 11, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [380c2c8a9e](https://linux-hardware.org/?probe=380c2c8a9e) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [54b445c5c1](https://linux-hardware.org/?probe=54b445c5c1) | Jul 10, 2023 |
| Acer          | SF714-52T                   | Notebook    | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| ASRock        | A75 Extreme6                | Desktop     | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| AYANEO        | AIR Pro                     | Tablet      | [90413e073a](https://linux-hardware.org/?probe=90413e073a) | Jul 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [ee5ef8132f](https://linux-hardware.org/?probe=ee5ef8132f) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [86c4d26a95](https://linux-hardware.org/?probe=86c4d26a95) | Jul 09, 2023 |
| Lenovo        | Legion R9000X ARHA7 82UG    | Notebook    | [5da53d3f61](https://linux-hardware.org/?probe=5da53d3f61) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| HP            | ProBook 6460b               | Notebook    | [af3006237f](https://linux-hardware.org/?probe=af3006237f) | Jul 09, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3540170054](https://linux-hardware.org/?probe=3540170054) | Jul 08, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6b4669ec61](https://linux-hardware.org/?probe=6b4669ec61) | Jul 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [dd8bd37036](https://linux-hardware.org/?probe=dd8bd37036) | Jul 08, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [cbea798725](https://linux-hardware.org/?probe=cbea798725) | Jul 08, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [af380bf3d8](https://linux-hardware.org/?probe=af380bf3d8) | Jul 07, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| ASRockRack    | E3C236D4U                   | Desktop     | [83ed95f0d3](https://linux-hardware.org/?probe=83ed95f0d3) | Jul 07, 2023 |
| Purism        | Librem 14                   | Notebook    | [18db47d3f6](https://linux-hardware.org/?probe=18db47d3f6) | Jul 07, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | Notebook    | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c199c7040b](https://linux-hardware.org/?probe=c199c7040b) | Jul 07, 2023 |
| Lenovo        | Legion R9000P2021 82JS      | Notebook    | [0376dd3cbd](https://linux-hardware.org/?probe=0376dd3cbd) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d908a5a02e](https://linux-hardware.org/?probe=d908a5a02e) | Jul 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [cf134cbdd9](https://linux-hardware.org/?probe=cf134cbdd9) | Jul 06, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [40d2eef376](https://linux-hardware.org/?probe=40d2eef376) | Jul 06, 2023 |
| Dell          | G3 3590                     | Notebook    | [e3cfb2968a](https://linux-hardware.org/?probe=e3cfb2968a) | Jul 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [0fc498ccfb](https://linux-hardware.org/?probe=0fc498ccfb) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e5539c7298](https://linux-hardware.org/?probe=e5539c7298) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Dell          | G3 3590                     | Notebook    | [35906fded9](https://linux-hardware.org/?probe=35906fded9) | Jul 05, 2023 |
| Dell          | Latitude 7350               | Notebook    | [bc00420bfc](https://linux-hardware.org/?probe=bc00420bfc) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3cf621f13b](https://linux-hardware.org/?probe=3cf621f13b) | Jul 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [eb325b1c2a](https://linux-hardware.org/?probe=eb325b1c2a) | Jul 04, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| Dell          | Latitude 7350               | Notebook    | [14d41ff667](https://linux-hardware.org/?probe=14d41ff667) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| HP            | 3047h                       | Desktop     | [7dfd0078f7](https://linux-hardware.org/?probe=7dfd0078f7) | Jul 03, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7ee43d9cad](https://linux-hardware.org/?probe=7ee43d9cad) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| Huanan        | H610M-PLUS V1.2             | Desktop     | [0bc6a5e828](https://linux-hardware.org/?probe=0bc6a5e828) | Jul 03, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [ae4fa28fb5](https://linux-hardware.org/?probe=ae4fa28fb5) | Jul 03, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [5af51ee197](https://linux-hardware.org/?probe=5af51ee197) | Jul 03, 2023 |
| MSI           | Z590 PRO WIFI               | Desktop     | [4fb1a41361](https://linux-hardware.org/?probe=4fb1a41361) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [364082f281](https://linux-hardware.org/?probe=364082f281) | Jul 03, 2023 |
| Pegatron      | 2AD3                        | Desktop     | [fd445e9894](https://linux-hardware.org/?probe=fd445e9894) | Jul 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [e578144ebb](https://linux-hardware.org/?probe=e578144ebb) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | Notebook    | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [83fd2dc626](https://linux-hardware.org/?probe=83fd2dc626) | Jul 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [5c3eb7ce7c](https://linux-hardware.org/?probe=5c3eb7ce7c) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | Notebook    | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | Notebook    | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | Notebook    | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | Notebook    | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [b4e7dadba8](https://linux-hardware.org/?probe=b4e7dadba8) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [07f04b7377](https://linux-hardware.org/?probe=07f04b7377) | Jul 01, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [65c2a81637](https://linux-hardware.org/?probe=65c2a81637) | Jul 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a57586f69b](https://linux-hardware.org/?probe=a57586f69b) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b49269ab3c](https://linux-hardware.org/?probe=b49269ab3c) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [f50a86955f](https://linux-hardware.org/?probe=f50a86955f) | Jul 01, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [9f1aec7e08](https://linux-hardware.org/?probe=9f1aec7e08) | Jul 01, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [ceb2b4c1c5](https://linux-hardware.org/?probe=ceb2b4c1c5) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a3c2f0155c](https://linux-hardware.org/?probe=a3c2f0155c) | Jun 30, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | Notebook    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Dell          | Latitude E5440              | Notebook    | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [f3482421c4](https://linux-hardware.org/?probe=f3482421c4) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [eccf186dfd](https://linux-hardware.org/?probe=eccf186dfd) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [86866241cd](https://linux-hardware.org/?probe=86866241cd) | Jun 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [722b0302f4](https://linux-hardware.org/?probe=722b0302f4) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [9814b54843](https://linux-hardware.org/?probe=9814b54843) | Jun 29, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [5b82e1dd39](https://linux-hardware.org/?probe=5b82e1dd39) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [c6402add6a](https://linux-hardware.org/?probe=c6402add6a) | Jun 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [d6d67cffd3](https://linux-hardware.org/?probe=d6d67cffd3) | Jun 28, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [133ed5cc64](https://linux-hardware.org/?probe=133ed5cc64) | Jun 28, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [238e77122e](https://linux-hardware.org/?probe=238e77122e) | Jun 28, 2023 |
| COLORFUL      | X16 Pro 23                  | Notebook    | [656cf52198](https://linux-hardware.org/?probe=656cf52198) | Jun 28, 2023 |
| Acer          | Veriton M490G               | Desktop     | [1f3da6e87f](https://linux-hardware.org/?probe=1f3da6e87f) | Jun 28, 2023 |
| MSI           | S3361                       | Server      | [81c0a2f5b6](https://linux-hardware.org/?probe=81c0a2f5b6) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd0c241308](https://linux-hardware.org/?probe=cd0c241308) | Jun 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [6615a04065](https://linux-hardware.org/?probe=6615a04065) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c0af461776](https://linux-hardware.org/?probe=c0af461776) | Jun 27, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [474833dcec](https://linux-hardware.org/?probe=474833dcec) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [85c3968edc](https://linux-hardware.org/?probe=85c3968edc) | Jun 26, 2023 |
| HP            | 18E7                        | Desktop     | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | Precision 5570              | Notebook    | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [00cf0b0faa](https://linux-hardware.org/?probe=00cf0b0faa) | Jun 26, 2023 |
| Dell          | XPS 9315                    | Notebook    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | Notebook    | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| MSI           | GS63 7RD                    | Notebook    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [0e22fb1d65](https://linux-hardware.org/?probe=0e22fb1d65) | Jun 24, 2023 |
| ASRock        | H55M                        | Desktop     | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Precision 3581              | Notebook    | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [4430ccf679](https://linux-hardware.org/?probe=4430ccf679) | Jun 23, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [4cfd97f850](https://linux-hardware.org/?probe=4cfd97f850) | Jun 23, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [856acf81ed](https://linux-hardware.org/?probe=856acf81ed) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [7bf78e33d4](https://linux-hardware.org/?probe=7bf78e33d4) | Jun 22, 2023 |
| IP3 Techno... | ACB19                       | Mini pc     | [db5c45e4f7](https://linux-hardware.org/?probe=db5c45e4f7) | Jun 22, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [e8391a9f3d](https://linux-hardware.org/?probe=e8391a9f3d) | Jun 22, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [928f167dee](https://linux-hardware.org/?probe=928f167dee) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26a3b9b3e9](https://linux-hardware.org/?probe=26a3b9b3e9) | Jun 21, 2023 |
| HP            | 21EF                        | Desktop     | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S14V00    | Notebook    | [6f81cc6d57](https://linux-hardware.org/?probe=6f81cc6d57) | Jun 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| HASEE Comp... | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2c0be5d314](https://linux-hardware.org/?probe=2c0be5d314) | Jun 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0f15219a46](https://linux-hardware.org/?probe=0f15219a46) | Jun 19, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [6a63f44627](https://linux-hardware.org/?probe=6a63f44627) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [1d1386c5e2](https://linux-hardware.org/?probe=1d1386c5e2) | Jun 18, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [cb20c2c912](https://linux-hardware.org/?probe=cb20c2c912) | Jun 18, 2023 |
| Acer          | Veriton M490G               | Desktop     | [f9405b8bd2](https://linux-hardware.org/?probe=f9405b8bd2) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [26e276dc29](https://linux-hardware.org/?probe=26e276dc29) | Jun 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [978e506718](https://linux-hardware.org/?probe=978e506718) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [676efbb266](https://linux-hardware.org/?probe=676efbb266) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [bfa70344e3](https://linux-hardware.org/?probe=bfa70344e3) | Jun 16, 2023 |
| Samsung       | 750XDA                      | Notebook    | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c338e10965](https://linux-hardware.org/?probe=c338e10965) | Jun 16, 2023 |
| Samsung       | 930QCG                      | Convertible | [339858c7c7](https://linux-hardware.org/?probe=339858c7c7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1150629ceb](https://linux-hardware.org/?probe=1150629ceb) | Jun 16, 2023 |
| Lenovo        | ThinkPad E480 20KNA047CD    | Notebook    | [918de7de03](https://linux-hardware.org/?probe=918de7de03) | Jun 16, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [ca0cba861a](https://linux-hardware.org/?probe=ca0cba861a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [2111a059f3](https://linux-hardware.org/?probe=2111a059f3) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | Notebook    | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [535950bae5](https://linux-hardware.org/?probe=535950bae5) | Jun 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [c05a02e77b](https://linux-hardware.org/?probe=c05a02e77b) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b548786e27](https://linux-hardware.org/?probe=b548786e27) | Jun 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [928063a305](https://linux-hardware.org/?probe=928063a305) | Jun 13, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [f0f0a1b2ac](https://linux-hardware.org/?probe=f0f0a1b2ac) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| Dell          | Inspiron 7786               | Convertible | [d6fa177357](https://linux-hardware.org/?probe=d6fa177357) | Jun 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [0fe4687002](https://linux-hardware.org/?probe=0fe4687002) | Jun 12, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [bac6eb2f16](https://linux-hardware.org/?probe=bac6eb2f16) | Jun 12, 2023 |
| Dell          | Inspiron 7786               | Convertible | [afd9c5a18f](https://linux-hardware.org/?probe=afd9c5a18f) | Jun 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [5678f7fb1f](https://linux-hardware.org/?probe=5678f7fb1f) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [41526d21bc](https://linux-hardware.org/?probe=41526d21bc) | Jun 12, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [6154060edd](https://linux-hardware.org/?probe=6154060edd) | Jun 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Acer          | Veriton M490G               | Desktop     | [78ff85b0a4](https://linux-hardware.org/?probe=78ff85b0a4) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e7d498373d](https://linux-hardware.org/?probe=e7d498373d) | Jun 11, 2023 |
| Medion        | E2291                       | Convertible | [4e834d645d](https://linux-hardware.org/?probe=4e834d645d) | Jun 11, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [823925da4a](https://linux-hardware.org/?probe=823925da4a) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | Notebook    | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc81f6c74c](https://linux-hardware.org/?probe=cc81f6c74c) | Jun 11, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [80bc2607fb](https://linux-hardware.org/?probe=80bc2607fb) | Jun 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [63c9d6c822](https://linux-hardware.org/?probe=63c9d6c822) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [a165849009](https://linux-hardware.org/?probe=a165849009) | Jun 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| MECHREVO      | Jiaolong16K Series GM6BG... | Notebook    | [05c07442a3](https://linux-hardware.org/?probe=05c07442a3) | Jun 09, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61a0a2ea5f](https://linux-hardware.org/?probe=61a0a2ea5f) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [bb7335618d](https://linux-hardware.org/?probe=bb7335618d) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [19c6b51f80](https://linux-hardware.org/?probe=19c6b51f80) | Jun 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3cfa2bccb7](https://linux-hardware.org/?probe=3cfa2bccb7) | Jun 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [ac292cca00](https://linux-hardware.org/?probe=ac292cca00) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [41dea00814](https://linux-hardware.org/?probe=41dea00814) | Jun 08, 2023 |
| Google        | Edgar                       | Notebook    | [bec197cb98](https://linux-hardware.org/?probe=bec197cb98) | Jun 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| HP            | 3396                        | Desktop     | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1f4ef72dbd](https://linux-hardware.org/?probe=1f4ef72dbd) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [db7f17cbe1](https://linux-hardware.org/?probe=db7f17cbe1) | Jun 07, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [9636ea4dc5](https://linux-hardware.org/?probe=9636ea4dc5) | Jun 07, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Arch Rolling           | 4081      | 57.56%  |
| Arch                   | 2982      | 42.06%  |
| Arch V20.4.11          | 3         | 0.04%   |
| Arch V19.11.3          | 3         | 0.04%   |
| Arch V20.5.7           | 2         | 0.03%   |
| Arch V20.3.4           | 2         | 0.03%   |
| Arch V19.04.4          | 2         | 0.03%   |
| Arch Workstation       | 1         | 0.01%   |
| Arch V6.9.2            | 1         | 0.01%   |
| Arch V19.09.1          | 1         | 0.01%   |
| Arch V19.07.9          | 1         | 0.01%   |
| Arch V19.07.11         | 1         | 0.01%   |
| Arch V19.06.1          | 1         | 0.01%   |
| Arch V19.05.2          | 1         | 0.01%   |
| Arch V19.01.4          | 1         | 0.01%   |
| Arch Breaking          | 1         | 0.01%   |
| Arch 23.0.0            | 1         | 0.01%   |
| Arch 22.10             | 1         | 0.01%   |
| Arch 20230723.0.166908 | 1         | 0.01%   |
| Arch 2020.09.05        | 1         | 0.01%   |
| Arch 20.08.3           | 1         | 0.01%   |
| Arch 2.7               | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 6903      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.04%   |
| 6.4.12-arch1-1  | 74        | 0.9%    |
| 6.0.2-arch1-1   | 71        | 0.87%   |
| 5.8.5-arch1-1   | 70        | 0.85%   |
| 5.9.14-arch1-1  | 61        | 0.74%   |
| 5.9.1-arch1-1   | 60        | 0.73%   |
| 5.17.5-arch1-1  | 53        | 0.65%   |
| 5.17.9-arch1-1  | 51        | 0.62%   |
| 5.8.12-arch1-1  | 48        | 0.59%   |
| 5.8.10-arch1-1  | 48        | 0.59%   |
| 5.8.14-arch1-1  | 47        | 0.57%   |
| 6.3.9-arch1-1   | 46        | 0.56%   |
| 6.1.1-arch1-1   | 46        | 0.56%   |
| 5.7.12-arch1-1  | 46        | 0.56%   |
| 6.2.8-arch1-1   | 45        | 0.55%   |
| 5.13.13-arch1-1 | 45        | 0.55%   |
| 6.0.12-arch1-1  | 43        | 0.53%   |
| 5.8.1-arch1-1   | 43        | 0.53%   |
| 6.0.9-arch1-1   | 42        | 0.51%   |
| 5.11.16-arch1-1 | 42        | 0.51%   |
| 6.3.2-arch1-1   | 38        | 0.46%   |
| 6.2.10-arch1-1  | 37        | 0.45%   |
| 6.1.12-arch1-1  | 37        | 0.45%   |
| 5.6.15-arch1-1  | 37        | 0.45%   |
| 6.5.3-arch1-1   | 36        | 0.44%   |
| 6.1.8-arch1-1   | 35        | 0.43%   |
| 6.4.10-arch1-1  | 34        | 0.42%   |
| 5.18.16-arch1-1 | 34        | 0.42%   |
| 5.11.6-arch1-1  | 34        | 0.42%   |
| 5.11.11-arch1-1 | 34        | 0.42%   |
| 6.3.5-arch1-1   | 33        | 0.4%    |
| 6.3.1-arch1-1   | 33        | 0.4%    |
| 6.2.12-arch1-1  | 33        | 0.4%    |
| 5.12.15-arch1-1 | 33        | 0.4%    |
| 5.10.16-arch1-1 | 33        | 0.4%    |
| 6.0.10-arch2-1  | 32        | 0.39%   |
| 5.19.13-arch1-1 | 32        | 0.39%   |
| 5.18.1-arch1-1  | 32        | 0.39%   |
| 6.2.2-arch1-1   | 31        | 0.38%   |
| 6.0.7-arch1-1   | 31        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.28%   |
| 5.8.5   | 92        | 1.12%   |
| 6.0.2   | 90        | 1.1%    |
| 6.4.12  | 86        | 1.05%   |
| 5.9.1   | 77        | 0.94%   |
| 5.8.12  | 73        | 0.89%   |
| 5.9.14  | 72        | 0.88%   |
| 5.17.5  | 70        | 0.85%   |
| 6.3.1   | 65        | 0.79%   |
| 5.8.14  | 63        | 0.77%   |
| 5.8.10  | 62        | 0.76%   |
| 5.17.9  | 61        | 0.74%   |
| 6.3.9   | 59        | 0.72%   |
| 6.1.1   | 57        | 0.7%    |
| 5.13.13 | 56        | 0.68%   |
| 6.2.2   | 54        | 0.66%   |
| 6.1.12  | 54        | 0.66%   |
| 6.4.3   | 53        | 0.65%   |
| 6.2.8   | 53        | 0.65%   |
| 5.8.1   | 53        | 0.65%   |
| 5.7.12  | 53        | 0.65%   |
| 6.5.3   | 52        | 0.64%   |
| 6.0.9   | 52        | 0.64%   |
| 6.0.12  | 52        | 0.64%   |
| 5.11.6  | 52        | 0.64%   |
| 6.3.2   | 51        | 0.62%   |
| 6.1.9   | 51        | 0.62%   |
| 5.11.16 | 51        | 0.62%   |
| 6.2.10  | 49        | 0.6%    |
| 6.3.5   | 48        | 0.59%   |
| 6.4.10  | 45        | 0.55%   |
| 6.1.8   | 44        | 0.54%   |
| 5.11.2  | 43        | 0.53%   |
| 6.0.8   | 42        | 0.51%   |
| 5.12.15 | 42        | 0.51%   |
| 5.10.16 | 42        | 0.51%   |
| 6.0.11  | 41        | 0.5%    |
| 5.19.7  | 41        | 0.5%    |
| 5.18.16 | 41        | 0.5%    |
| 5.11.11 | 41        | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 522       | 6.62%   |
| 6.1     | 487       | 6.18%   |
| 5.15    | 479       | 6.08%   |
| 6.4     | 416       | 5.28%   |
| 6.0     | 413       | 5.24%   |
| 6.2     | 387       | 4.91%   |
| 5.9     | 384       | 4.87%   |
| 5.18    | 367       | 4.65%   |
| 6.3     | 366       | 4.64%   |
| 5.10    | 355       | 4.5%    |
| 5.4     | 353       | 4.48%   |
| 5.11    | 350       | 4.44%   |
| 5.19    | 343       | 4.35%   |
| 5.17    | 342       | 4.34%   |
| 5.12    | 310       | 3.93%   |
| 5.16    | 305       | 3.87%   |
| 5.6     | 263       | 3.34%   |
| 5.7     | 260       | 3.3%    |
| 5.14    | 237       | 3.01%   |
| 5.13    | 234       | 2.97%   |
| 5.5     | 148       | 1.88%   |
| 6.5     | 122       | 1.55%   |
| 5.3     | 114       | 1.45%   |
| 4.19    | 56        | 0.71%   |
| 5.2     | 54        | 0.68%   |
| 5.0     | 41        | 0.52%   |
| 4.18    | 37        | 0.47%   |
| 5.1     | 32        | 0.41%   |
| 4.20    | 22        | 0.28%   |
| 4.17    | 19        | 0.24%   |
| 4.15    | 14        | 0.18%   |
| 4.14    | 10        | 0.13%   |
| 4.16    | 9         | 0.11%   |
| 4.9     | 5         | 0.06%   |
| 4.7     | 4         | 0.05%   |
| 4.6     | 4         | 0.05%   |
| 4.11    | 4         | 0.05%   |
| 4.8     | 3         | 0.04%   |
| 4.4     | 3         | 0.04%   |
| 4.13    | 3         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6897      | 99.91%  |
| i686    | 5         | 0.07%   |
| riscv64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 2282      | 31.72%  |
| KDE5                     | 1917      | 26.65%  |
| Unknown                  | 867       | 12.05%  |
| XFCE                     | 552       | 7.67%   |
| i3                       | 357       | 4.96%   |
| KDE                      | 299       | 4.16%   |
| X-Cinnamon               | 98        | 1.36%   |
| sway                     | 96        | 1.33%   |
| MATE                     | 87        | 1.21%   |
| Budgie                   | 84        | 1.17%   |
| Cinnamon                 | 81        | 1.13%   |
| Hyprland                 | 76        | 1.06%   |
| Deepin                   | 69        | 0.96%   |
| LXQt                     | 57        | 0.79%   |
| bspwm                    | 41        | 0.57%   |
| LXDE                     | 40        | 0.56%   |
| awesome                  | 35        | 0.49%   |
| openbox                  | 21        | 0.29%   |
| qtile                    | 19        | 0.26%   |
| DWM                      | 17        | 0.24%   |
| GNOME Flashback          | 15        | 0.21%   |
| xmonad                   | 14        | 0.19%   |
| Unity                    | 12        | 0.17%   |
| GNOME Classic            | 9         | 0.13%   |
| LeftWM                   | 6         | 0.08%   |
| i3-with-shmlog           | 6         | 0.08%   |
| Enlightenment            | 5         | 0.07%   |
| chadwm                   | 4         | 0.06%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| Wayfire                  | 2         | 0.03%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| GNOME-Classic            | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| X-Generic                | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4178      | 58.39%  |
| Wayland | 1824      | 25.49%  |
| Tty     | 652       | 9.11%   |
| Unknown | 500       | 6.99%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2953      | 41.46%  |
| SDDM    | 1711      | 24.02%  |
| GDM     | 1005      | 14.11%  |
| LightDM | 794       | 11.15%  |
| TDM     | 398       | 5.59%   |
| Ly      | 77        | 1.08%   |
| XDM     | 56        | 0.79%   |
| LXDM    | 53        | 0.74%   |
| SLiM    | 30        | 0.42%   |
| GREETD  | 23        | 0.32%   |
| LY-DM   | 8         | 0.11%   |
| EMPTTY  | 6         | 0.08%   |
| NODM    | 5         | 0.07%   |
| XINIT   | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 3443      | 48.78%  |
| Unknown    | 647       | 9.17%   |
| en_GB      | 416       | 5.89%   |
| C          | 380       | 5.38%   |
| de_DE      | 284       | 4.02%   |
| ru_RU      | 227       | 3.22%   |
| it_IT      | 217       | 3.07%   |
| pt_BR      | 193       | 2.73%   |
| fr_FR      | 165       | 2.34%   |
| pl_PL      | 90        | 1.28%   |
| zh_CN      | 83        | 1.18%   |
| en_CA      | 79        | 1.12%   |
| es_ES      | 76        | 1.08%   |
| en_IN      | 70        | 0.99%   |
| en_AU      | 70        | 0.99%   |
| en_IE      | 38        | 0.54%   |
| en_DK      | 31        | 0.44%   |
| es_MX      | 28        | 0.4%    |
| de_AT      | 22        | 0.31%   |
| hu_HU      | 21        | 0.3%    |
| pt_PT      | 20        | 0.28%   |
| es_AR      | 20        | 0.28%   |
| tr_TR      | 19        | 0.27%   |
| ja_JP      | 17        | 0.24%   |
| en_NZ      | 17        | 0.24%   |
| nl_NL      | 16        | 0.23%   |
| cs_CZ      | 16        | 0.23%   |
| es_CL      | 15        | 0.21%   |
| es_CO      | 14        | 0.2%    |
| en_DE      | 14        | 0.2%    |
| ru_UA      | 13        | 0.18%   |
| sv_SE      | 11        | 0.16%   |
| en_SG      | 11        | 0.16%   |
| en_ZA      | 10        | 0.14%   |
| en_US.UTF8 | 10        | 0.14%   |
| de_CH      | 10        | 0.14%   |
| lv_LV      | 9         | 0.13%   |
| fi_FI      | 9         | 0.13%   |
| en_AG      | 9         | 0.13%   |
| zh_TW      | 8         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4362      | 61.93%  |
| BIOS | 2682      | 38.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 4918      | 70.24%  |
| Btrfs               | 1529      | 21.84%  |
| Unknown             | 182       | 2.6%    |
| Xfs                 | 163       | 2.33%   |
| F2fs                | 91        | 1.3%    |
| Overlay             | 46        | 0.66%   |
| Zfs                 | 42        | 0.6%    |
| Tmpfs               | 9         | 0.13%   |
| Ext2                | 8         | 0.11%   |
| XXXXX               | 5         | 0.07%   |
| XXX4                | 2         | 0.03%   |
| Jfs                 | 2         | 0.03%   |
| Ext3                | 2         | 0.03%   |
| Reiserfs            | 1         | 0.01%   |
| Fuse.fuse-overlayfs | 1         | 0.01%   |
| Aufs                | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4452      | 63.55%  |
| Unknown | 1988      | 28.38%  |
| MBR     | 565       | 8.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6030      | 86.16%  |
| Yes       | 969       | 13.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4877      | 69.46%  |
| Yes       | 2144      | 30.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1348      | 19.53%  |
| Lenovo                 | 1255      | 18.18%  |
| Dell                   | 733       | 10.62%  |
| Hewlett-Packard        | 722       | 10.46%  |
| MSI                    | 573       | 8.3%    |
| Gigabyte Technology    | 552       | 8%      |
| ASRock                 | 342       | 4.95%   |
| Acer                   | 334       | 4.84%   |
| Apple                  | 108       | 1.56%   |
| Intel                  | 84        | 1.22%   |
| HUAWEI                 | 73        | 1.06%   |
| Samsung Electronics    | 62        | 0.9%    |
| Toshiba                | 47        | 0.68%   |
| Microsoft              | 38        | 0.55%   |
| Unknown                | 35        | 0.51%   |
| Notebook               | 34        | 0.49%   |
| Timi                   | 33        | 0.48%   |
| Google                 | 29        | 0.42%   |
| Sony                   | 24        | 0.35%   |
| Fujitsu                | 24        | 0.35%   |
| TUXEDO                 | 22        | 0.32%   |
| Framework              | 20        | 0.29%   |
| Alienware              | 20        | 0.29%   |
| Biostar                | 17        | 0.25%   |
| Razer                  | 15        | 0.22%   |
| ECS                    | 14        | 0.2%    |
| Medion                 | 13        | 0.19%   |
| LG Electronics         | 12        | 0.17%   |
| Pegatron               | 11        | 0.16%   |
| Avell High Performance | 11        | 0.16%   |
| System76               | 10        | 0.14%   |
| Schenker               | 10        | 0.14%   |
| Positivo               | 9         | 0.13%   |
| Packard Bell           | 9         | 0.13%   |
| MECHREVO               | 9         | 0.13%   |
| Chuwi                  | 9         | 0.13%   |
| Supermicro             | 8         | 0.12%   |
| Huanan                 | 8         | 0.12%   |
| ZOTAC                  | 6         | 0.09%   |
| HONOR                  | 6         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 66        | 0.96%   |
| Unknown                          | 59        | 0.85%   |
| MSI MS-7C37                      | 31        | 0.45%   |
| MSI MS-7C02                      | 31        | 0.45%   |
| ASUS TUF Gaming X570-PLUS        | 31        | 0.45%   |
| MSI MS-7B86                      | 25        | 0.36%   |
| Gigabyte B450M DS3H              | 22        | 0.32%   |
| ASUS ROG STRIX B550-F GAMING     | 20        | 0.29%   |
| MSI MS-7B89                      | 18        | 0.26%   |
| MSI MS-7B79                      | 18        | 0.26%   |
| Dell XPS 15 9570                 | 18        | 0.26%   |
| Dell XPS 15 9500                 | 18        | 0.26%   |
| ASUS PRIME X470-PRO              | 18        | 0.26%   |
| MSI MS-7C91                      | 17        | 0.25%   |
| MSI MS-7A34                      | 17        | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 17        | 0.25%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.25%   |
| HP Notebook                      | 16        | 0.23%   |
| Framework Laptop                 | 16        | 0.23%   |
| ASUS PRIME X370-PRO              | 16        | 0.23%   |
| ASUS PRIME B450M-A               | 16        | 0.23%   |
| MSI MS-7C56                      | 15        | 0.22%   |
| MSI MS-7A38                      | 15        | 0.22%   |
| Gigabyte X470 AORUS ULTRA GAMING | 14        | 0.2%    |
| Dell XPS 13 9360                 | 14        | 0.2%    |
| ASUS TUF Gaming B550-PLUS        | 13        | 0.19%   |
| ASUS ROG STRIX X570-E GAMING     | 13        | 0.19%   |
| ASRock X570 Taichi               | 12        | 0.17%   |
| ASRock B450M Pro4                | 12        | 0.17%   |
| Gigabyte B450 AORUS ELITE        | 11        | 0.16%   |
| Gigabyte 970A-DS3P               | 11        | 0.16%   |
| Dell XPS 13 9380                 | 11        | 0.16%   |
| ASUS ROG STRIX X470-F GAMING     | 11        | 0.16%   |
| ASUS PRIME A320M-K               | 11        | 0.16%   |
| MSI MS-7B98                      | 10        | 0.14%   |
| Lenovo ThinkBook 15 G2 ITL 20VE  | 10        | 0.14%   |
| HUAWEI NBLK-WAX9X                | 10        | 0.14%   |
| Gigabyte X570 I AORUS PRO WIFI   | 10        | 0.14%   |
| Dell XPS 15 7590                 | 10        | 0.14%   |
| Dell XPS 13 9310                 | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 677       | 9.81%   |
| ASUS ROG           | 267       | 3.87%   |
| ASUS PRIME         | 222       | 3.22%   |
| Lenovo IdeaPad     | 221       | 3.2%    |
| Acer Aspire        | 189       | 2.74%   |
| Dell Inspiron      | 185       | 2.68%   |
| Dell Latitude      | 168       | 2.43%   |
| Dell XPS           | 167       | 2.42%   |
| ASUS TUF           | 154       | 2.23%   |
| HP Pavilion        | 135       | 1.96%   |
| HP EliteBook       | 115       | 1.67%   |
| ASUS VivoBook      | 81        | 1.17%   |
| Lenovo Legion      | 79        | 1.14%   |
| HP Laptop          | 77        | 1.12%   |
| HP ENVY            | 69        | 1%      |
| ASUS All           | 66        | 0.96%   |
| Lenovo Yoga        | 63        | 0.91%   |
| HP ProBook         | 63        | 0.91%   |
| Dell Precision     | 61        | 0.88%   |
| Gigabyte X570      | 60        | 0.87%   |
| Dell OptiPlex      | 60        | 0.87%   |
| Unknown            | 59        | 0.85%   |
| Acer Nitro         | 50        | 0.72%   |
| ASUS ASUS          | 46        | 0.67%   |
| ASUS Zenbook       | 44        | 0.64%   |
| Acer Swift         | 40        | 0.58%   |
| Toshiba Satellite  | 38        | 0.55%   |
| Microsoft Surface  | 38        | 0.55%   |
| Gigabyte B450M     | 37        | 0.54%   |
| Lenovo ThinkBook   | 36        | 0.52%   |
| Dell Vostro        | 33        | 0.48%   |
| HP OMEN            | 32        | 0.46%   |
| MSI MS-7C37        | 31        | 0.45%   |
| MSI MS-7C02        | 31        | 0.45%   |
| HP Spectre         | 31        | 0.45%   |
| ASRock X570        | 31        | 0.45%   |
| Gigabyte B450      | 30        | 0.43%   |
| Lenovo ThinkCentre | 27        | 0.39%   |
| HP Compaq          | 26        | 0.38%   |
| MSI MS-7B86        | 25        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 978       | 14.17%  |
| 2019    | 942       | 13.65%  |
| 2020    | 889       | 12.88%  |
| 2021    | 642       | 9.3%    |
| 2017    | 566       | 8.2%    |
| 2016    | 385       | 5.58%   |
| 2012    | 373       | 5.4%    |
| 2014    | 358       | 5.19%   |
| 2013    | 343       | 4.97%   |
| 2022    | 342       | 4.95%   |
| 2015    | 332       | 4.81%   |
| 2011    | 282       | 4.09%   |
| 2010    | 166       | 2.4%    |
| 2008    | 97        | 1.41%   |
| 2009    | 89        | 1.29%   |
| 2023    | 67        | 0.97%   |
| 2007    | 33        | 0.48%   |
| 2006    | 11        | 0.16%   |
| Unknown | 4         | 0.06%   |
| 2005    | 3         | 0.04%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3778      | 54.73%  |
| Desktop        | 2662      | 38.56%  |
| Convertible    | 256       | 3.71%   |
| Tablet         | 76        | 1.1%    |
| Mini pc        | 58        | 0.84%   |
| All in one     | 43        | 0.62%   |
| Server         | 28        | 0.41%   |
| Stick pc       | 1         | 0.01%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6826      | 98.64%  |
| Enabled  | 94        | 1.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6850      | 99.23%  |
| Yes  | 53        | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1990      | 28.41%  |
| 8.01-16.0       | 1368      | 19.53%  |
| 4.01-8.0        | 1321      | 18.86%  |
| 32.01-64.0      | 1145      | 16.35%  |
| 3.01-4.0        | 555       | 7.92%   |
| 64.01-256.0     | 291       | 4.15%   |
| 24.01-32.0      | 191       | 2.73%   |
| 1.01-2.0        | 81        | 1.16%   |
| 2.01-3.0        | 38        | 0.54%   |
| 0.51-1.0        | 13        | 0.19%   |
| More than 256.0 | 9         | 0.13%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1850      | 24.25%  |
| 2.01-3.0    | 1782      | 23.36%  |
| 1.01-2.0    | 1569      | 20.57%  |
| 3.01-4.0    | 1266      | 16.59%  |
| 8.01-16.0   | 662       | 8.68%   |
| 0.51-1.0    | 261       | 3.42%   |
| 16.01-24.0  | 103       | 1.35%   |
| 0.01-0.5    | 70        | 0.92%   |
| 24.01-32.0  | 39        | 0.51%   |
| 32.01-64.0  | 23        | 0.3%    |
| 64.01-256.0 | 2         | 0.03%   |
| Unknown     | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3565      | 50.15%  |
| 2      | 1940      | 27.29%  |
| 3      | 784       | 11.03%  |
| 4      | 376       | 5.29%   |
| 5      | 213       | 3%      |
| 6      | 94        | 1.32%   |
| 7      | 54        | 0.76%   |
| 0      | 22        | 0.31%   |
| 8      | 20        | 0.28%   |
| 9      | 17        | 0.24%   |
| 12     | 5         | 0.07%   |
| 11     | 5         | 0.07%   |
| 10     | 4         | 0.06%   |
| 14     | 3         | 0.04%   |
| 13     | 3         | 0.04%   |
| 22     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |
| 15     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5515      | 79.42%  |
| Yes       | 1429      | 20.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5747      | 82.95%  |
| No        | 1181      | 17.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5416      | 78%     |
| No        | 1528      | 22%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4910      | 70.3%   |
| No        | 2074      | 29.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1296      | 18.65%  |
| Germany     | 668       | 9.61%   |
| Russia      | 467       | 6.72%   |
| Italy       | 363       | 5.22%   |
| Brazil      | 363       | 5.22%   |
| France      | 304       | 4.37%   |
| UK          | 271       | 3.9%    |
| India       | 210       | 3.02%   |
| Poland      | 203       | 2.92%   |
| Canada      | 189       | 2.72%   |
| Spain       | 153       | 2.2%    |
| Netherlands | 136       | 1.96%   |
| China       | 121       | 1.74%   |
| Australia   | 118       | 1.7%    |
| Sweden      | 102       | 1.47%   |
| Austria     | 99        | 1.42%   |
| Ukraine     | 93        | 1.34%   |
| Turkey      | 88        | 1.27%   |
| Finland     | 75        | 1.08%   |
| Switzerland | 64        | 0.92%   |
| Czechia     | 60        | 0.86%   |
| Mexico      | 58        | 0.83%   |
| Hungary     | 57        | 0.82%   |
| Romania     | 56        | 0.81%   |
| Indonesia   | 55        | 0.79%   |
| Argentina   | 53        | 0.76%   |
| Denmark     | 51        | 0.73%   |
| Belgium     | 49        | 0.71%   |
| Portugal    | 48        | 0.69%   |
| Japan       | 46        | 0.66%   |
| Norway      | 44        | 0.63%   |
| Greece      | 44        | 0.63%   |
| Chile       | 43        | 0.62%   |
| Vietnam     | 38        | 0.55%   |
| New Zealand | 36        | 0.52%   |
| Iran        | 36        | 0.52%   |
| Hong Kong   | 36        | 0.52%   |
| Colombia    | 34        | 0.49%   |
| Bulgaria    | 29        | 0.42%   |
| Taiwan      | 27        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 133       | 1.8%    |
| Paris             | 74        | 1%      |
| St Petersburg     | 71        | 0.96%   |
| Berlin            | 71        | 0.96%   |
| Sao Paulo         | 57        | 0.77%   |
| Warsaw            | 54        | 0.73%   |
| Vienna            | 54        | 0.73%   |
| Milan             | 54        | 0.73%   |
| Melbourne         | 46        | 0.62%   |
| Munich            | 43        | 0.58%   |
| Helsinki          | 40        | 0.54%   |
| Frankfurt am Main | 36        | 0.49%   |
| Amsterdam         | 36        | 0.49%   |
| Los Angeles       | 35        | 0.47%   |
| Sydney            | 34        | 0.46%   |
| New York          | 31        | 0.42%   |
| Istanbul          | 30        | 0.41%   |
| Valencia          | 29        | 0.39%   |
| Hamburg           | 29        | 0.39%   |
| Prague            | 28        | 0.38%   |
| Rome              | 27        | 0.37%   |
| London            | 27        | 0.37%   |
| Kyiv              | 26        | 0.35%   |
| Montreal          | 25        | 0.34%   |
| Budapest          | 25        | 0.34%   |
| Bengaluru         | 25        | 0.34%   |
| Madrid            | 24        | 0.33%   |
| Athens            | 24        | 0.33%   |
| Singapore         | 23        | 0.31%   |
| Seattle           | 23        | 0.31%   |
| Central           | 22        | 0.3%    |
| Krakow            | 21        | 0.28%   |
| Beijing           | 21        | 0.28%   |
| Dallas            | 20        | 0.27%   |
| Cologne           | 20        | 0.27%   |
| Zurich            | 19        | 0.26%   |
| Phoenix           | 19        | 0.26%   |
| Mexico City       | 19        | 0.26%   |
| Barcelona         | 19        | 0.26%   |
| Auckland          | 19        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2300      | 3627   | 20.12%  |
| WDC                         | 1552      | 2414   | 13.58%  |
| Seagate                     | 1347      | 2026   | 11.78%  |
| SanDisk                     | 802       | 1070   | 7.02%   |
| Toshiba                     | 701       | 939    | 6.13%   |
| Kingston                    | 600       | 795    | 5.25%   |
| Crucial                     | 483       | 690    | 4.22%   |
| SK hynix                    | 361       | 444    | 3.16%   |
| Intel                       | 331       | 440    | 2.9%    |
| Unknown                     | 284       | 342    | 2.48%   |
| Micron Technology           | 218       | 263    | 1.91%   |
| HGST                        | 191       | 246    | 1.67%   |
| Hitachi                     | 174       | 217    | 1.52%   |
| A-DATA Technology           | 168       | 232    | 1.47%   |
| Phison                      | 117       | 151    | 1.02%   |
| Micron/Crucial Technology   | 96        | 114    | 0.84%   |
| Phison Electronics          | 93        | 114    | 0.81%   |
| Silicon Motion              | 82        | 96     | 0.72%   |
| KIOXIA                      | 81        | 97     | 0.71%   |
| China                       | 81        | 104    | 0.71%   |
| Apple                       | 76        | 93     | 0.66%   |
| SPCC                        | 57        | 62     | 0.5%    |
| Kingston Technology Company | 56        | 60     | 0.49%   |
| OCZ                         | 55        | 73     | 0.48%   |
| Corsair                     | 50        | 64     | 0.44%   |
| PNY                         | 49        | 61     | 0.43%   |
| Transcend                   | 47        | 63     | 0.41%   |
| ADATA Technology            | 45        | 55     | 0.39%   |
| LITEON                      | 43        | 46     | 0.38%   |
| Patriot                     | 41        | 52     | 0.36%   |
| GOODRAM                     | 32        | 40     | 0.28%   |
| Realtek Semiconductor       | 31        | 38     | 0.27%   |
| JMicron Technology          | 28        | 45     | 0.24%   |
| XPG                         | 27        | 39     | 0.24%   |
| Team                        | 25        | 34     | 0.22%   |
| Plextor                     | 23        | 32     | 0.2%    |
| Intenso                     | 23        | 25     | 0.2%    |
| Hewlett-Packard             | 23        | 25     | 0.2%    |
| MAXIO Technology (Hangzhou) | 21        | 22     | 0.18%   |
| Lexar                       | 20        | 28     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 259       | 2%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 133       | 1.03%   |
| Samsung SSD 860 EVO 500GB                           | 122       | 0.94%   |
| Samsung SSD 850 EVO 500GB                           | 119       | 0.92%   |
| Kingston SA400S37240G 240GB SSD                     | 116       | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB                      | 104       | 0.8%    |
| Samsung SSD 850 EVO 250GB                           | 92        | 0.71%   |
| Samsung SSD 860 EVO 1TB                             | 90        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                      | 84        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                        | 82        | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB                        | 78        | 0.6%    |
| Crucial CT500MX500SSD1 500GB                        | 78        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                         | 78        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                      | 67        | 0.52%   |
| Samsung NVMe SSD Drive 1TB                          | 67        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                      | 65        | 0.5%    |
| Kingston SA400S37120G 120GB SSD                     | 65        | 0.5%    |
| Samsung NVMe SSD Drive 500GB                        | 64        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 61        | 0.47%   |
| Kingston SA400S37480G 480GB SSD                     | 60        | 0.46%   |
| HGST HTS721010A9E630 1TB                            | 60        | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 59        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 58        | 0.45%   |
| Toshiba MQ01ABD100 1TB                              | 58        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 56        | 0.43%   |
| Toshiba DT01ACA100 1TB                              | 53        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                          | 51        | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 50        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                        | 50        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                     | 49        | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 48        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                      | 47        | 0.36%   |
| Unknown MMC Card  64GB                              | 46        | 0.35%   |
| Toshiba MQ04ABF100 1TB                              | 46        | 0.35%   |
| Samsung SSD 860 QVO 1TB                             | 46        | 0.35%   |
| Unknown MMC Card  32GB                              | 45        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                      | 44        | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                       | 43        | 0.33%   |
| Samsung SSD 980 1TB                                 | 43        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 43        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1316      | 1976   | 36.13%  |
| WDC                 | 1207      | 1854   | 33.14%  |
| Toshiba             | 489       | 645    | 13.43%  |
| HGST                | 189       | 244    | 5.19%   |
| Hitachi             | 174       | 217    | 4.78%   |
| Samsung Electronics | 118       | 157    | 3.24%   |
| Unknown             | 28        | 36     | 0.77%   |
| Apple               | 26        | 26     | 0.71%   |
| SABRENT             | 16        | 17     | 0.44%   |
| Fujitsu             | 11        | 11     | 0.3%    |
| Maxtor              | 10        | 10     | 0.27%   |
| External            | 6         | 8      | 0.16%   |
| USB3.0              | 4         | 5      | 0.11%   |
| HGST HTS            | 4         | 4      | 0.11%   |
| ASMT                | 4         | 5      | 0.11%   |
| SSK                 | 3         | 3      | 0.08%   |
| LaCie               | 3         | 3      | 0.08%   |
| Generic-            | 3         | 4      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| SAGE                | 2         | 3      | 0.05%   |
| KESU                | 2         | 2      | 0.05%   |
| Hewlett-Packard     | 2         | 2      | 0.05%   |
| ASUSTOR             | 2         | 2      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| ACASIS              | 2         | 2      | 0.05%   |
| TDAS                | 1         | 4      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 11     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| NeoTech             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 16     | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| H/W                 | 1         | 1      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1029      | 1475   | 27.44%  |
| Kingston            | 462       | 597    | 12.32%  |
| Crucial             | 442       | 631    | 11.79%  |
| SanDisk             | 363       | 497    | 9.68%   |
| WDC                 | 245       | 319    | 6.53%   |
| A-DATA Technology   | 111       | 157    | 2.96%   |
| Intel               | 88        | 104    | 2.35%   |
| China               | 81        | 104    | 2.16%   |
| Toshiba             | 56        | 98     | 1.49%   |
| OCZ                 | 55        | 73     | 1.47%   |
| SK hynix            | 51        | 61     | 1.36%   |
| Micron Technology   | 51        | 61     | 1.36%   |
| SPCC                | 48        | 51     | 1.28%   |
| Transcend           | 44        | 60     | 1.17%   |
| PNY                 | 44        | 56     | 1.17%   |
| Patriot             | 41        | 52     | 1.09%   |
| LITEON              | 38        | 40     | 1.01%   |
| Apple               | 35        | 36     | 0.93%   |
| GOODRAM             | 30        | 38     | 0.8%    |
| Corsair             | 23        | 28     | 0.61%   |
| Intenso             | 22        | 24     | 0.59%   |
| Plextor             | 20        | 21     | 0.53%   |
| Team                | 19        | 21     | 0.51%   |
| Lexar               | 18        | 25     | 0.48%   |
| JMicron Technology  | 18        | 21     | 0.48%   |
| LITEONIT            | 17        | 17     | 0.45%   |
| KingSpec            | 15        | 16     | 0.4%    |
| Hewlett-Packard     | 12        | 13     | 0.32%   |
| ASMT                | 11        | 12     | 0.29%   |
| TO Exter            | 10        | 16     | 0.27%   |
| Netac               | 10        | 10     | 0.27%   |
| Mushkin             | 10        | 15     | 0.27%   |
| Gigabyte Technology | 10        | 11     | 0.27%   |
| Unknown             | 10        | 11     | 0.27%   |
| Seagate             | 7         | 7      | 0.19%   |
| KingDian            | 6         | 7      | 0.16%   |
| FORESEE             | 6         | 9      | 0.16%   |
| XrayDisk            | 5         | 6      | 0.13%   |
| Phison              | 5         | 5      | 0.13%   |
| Apacer              | 5         | 6      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3612      | 5363   | 35.82%  |
| SSD     | 3129      | 5032   | 31.03%  |
| HDD     | 2992      | 5286   | 29.67%  |
| MMC     | 240       | 286    | 2.38%   |
| Unknown | 110       | 133    | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4505      | 9953   | 51.63%  |
| NVMe | 3610      | 5350   | 41.38%  |
| SAS  | 370       | 511    | 4.24%   |
| MMC  | 240       | 286    | 2.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3211      | 5164   | 48.87%  |
| 0.51-1.0   | 2091      | 3060   | 31.83%  |
| 1.01-2.0   | 677       | 1035   | 10.3%   |
| 3.01-4.0   | 231       | 411    | 3.52%   |
| 4.01-10.0  | 178       | 340    | 2.71%   |
| 2.01-3.0   | 147       | 229    | 2.24%   |
| 10.01-20.0 | 34        | 78     | 0.52%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1556      | 21.57%  |
| 101-250        | 1495      | 20.72%  |
| 501-1000       | 1322      | 18.32%  |
| 1001-2000      | 990       | 13.72%  |
| More than 3000 | 772       | 10.7%   |
| 2001-3000      | 416       | 5.77%   |
| 51-100         | 263       | 3.65%   |
| Unknown        | 187       | 2.59%   |
| 21-50          | 109       | 1.51%   |
| 1-20           | 105       | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1410      | 18.75%  |
| 101-250        | 1307      | 17.38%  |
| 21-50          | 1048      | 13.93%  |
| 251-500        | 936       | 12.45%  |
| 51-100         | 909       | 12.09%  |
| 501-1000       | 774       | 10.29%  |
| 1001-2000      | 479       | 6.37%   |
| More than 3000 | 281       | 3.74%   |
| 2001-3000      | 189       | 2.51%   |
| Unknown        | 187       | 2.49%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 15        | 17     | 1.84%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 15        | 15     | 1.84%   |
| HGST HTS721010A9E630 1TB                                        | 12        | 12     | 1.47%   |
| HGST HTS541010A9E680 1TB                                        | 9         | 9      | 1.11%   |
| Seagate ST9500325AS 500GB                                       | 7         | 7      | 0.86%   |
| Seagate ST500LT012-1DG142 500GB                                 | 7         | 8      | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 7         | 10     | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 7         | 10     | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 7         | 11     | 0.86%   |
| Kingston SV300S37A120G 120GB SSD                                | 7         | 7      | 0.86%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 6         | 7      | 0.74%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 6         | 6      | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 6         | 8      | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 6         | 6      | 0.74%   |
| Toshiba MQ01ABD100 1TB                                          | 6         | 9      | 0.74%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 6         | 7      | 0.74%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 6         | 8      | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 6         | 8      | 0.74%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 256GB | 6         | 7      | 0.74%   |
| OCZ VERTEX4 256GB SSD                                           | 6         | 9      | 0.74%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 0.61%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 5         | 5      | 0.61%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.61%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 5         | 11     | 0.61%   |
| HGST HTS725050A7E630 500GB                                      | 5         | 5      | 0.61%   |
| HGST HTS545050A7E680 500GB                                      | 5         | 6      | 0.61%   |
| Crucial CT525MX300SSD1 528GB                                    | 5         | 7      | 0.61%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 4      | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB                                        | 4         | 4      | 0.49%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 4         | 4      | 0.49%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 4         | 6      | 0.49%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 4         | 5      | 0.49%   |
| Toshiba DT01ACA100 1TB                                          | 4         | 4      | 0.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 0.49%   |
| Seagate ST9250315AS 250GB                                       | 4         | 4      | 0.49%   |
| Seagate ST3500418AS 500GB                                       | 4         | 5      | 0.49%   |
| Seagate ST3320620AS 320GB                                       | 4         | 4      | 0.49%   |
| Seagate ST31000524AS 1TB                                        | 4         | 5      | 0.49%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 4         | 4      | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 4      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 215       | 266    | 27.63%  |
| WDC                         | 175       | 237    | 22.49%  |
| Samsung Electronics         | 70        | 93     | 9%      |
| Toshiba                     | 54        | 66     | 6.94%   |
| Hitachi                     | 43        | 46     | 5.53%   |
| HGST                        | 39        | 40     | 5.01%   |
| Kingston                    | 23        | 29     | 2.96%   |
| Intel                       | 21        | 24     | 2.7%    |
| Crucial                     | 21        | 25     | 2.7%    |
| SanDisk                     | 20        | 22     | 2.57%   |
| SK hynix                    | 13        | 14     | 1.67%   |
| OCZ                         | 11        | 18     | 1.41%   |
| A-DATA Technology           | 11        | 12     | 1.41%   |
| Micron Technology           | 6         | 7      | 0.77%   |
| LITEON                      | 5         | 5      | 0.64%   |
| Corsair                     | 4         | 4      | 0.51%   |
| Transcend                   | 3         | 11     | 0.39%   |
| Realtek Semiconductor       | 3         | 4      | 0.39%   |
| Maxtor                      | 3         | 3      | 0.39%   |
| Hewlett-Packard             | 3         | 3      | 0.39%   |
| Drevo                       | 3         | 4      | 0.39%   |
| ASMT                        | 3         | 3      | 0.39%   |
| Apple                       | 3         | 3      | 0.39%   |
| XrayDisk                    | 2         | 3      | 0.26%   |
| SSSTC                       | 2         | 2      | 0.26%   |
| SPCC                        | 2         | 3      | 0.26%   |
| PNY                         | 2         | 3      | 0.26%   |
| Plextor                     | 2         | 9      | 0.26%   |
| Patriot                     | 2         | 2      | 0.26%   |
| China                       | 2         | 2      | 0.26%   |
| VNYEZ                       | 1         | 1      | 0.13%   |
| TO Exter                    | 1         | 1      | 0.13%   |
| Silicon Motion              | 1         | 1      | 0.13%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.13%   |
| KingSpec                    | 1         | 1      | 0.13%   |
| Kingrich                    | 1         | 1      | 0.13%   |
| JMicron Technology          | 1         | 1      | 0.13%   |
| INNOVATION IT               | 1         | 1      | 0.13%   |
| GLOWAY                      | 1         | 1      | 0.13%   |
| Gigabyte Technology         | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 215       | 266    | 39.38%  |
| WDC                 | 168       | 228    | 30.77%  |
| Toshiba             | 48        | 60     | 8.79%   |
| Hitachi             | 43        | 46     | 7.88%   |
| HGST                | 39        | 40     | 7.14%   |
| Samsung Electronics | 23        | 28     | 4.21%   |
| Maxtor              | 3         | 3      | 0.55%   |
| Apple               | 3         | 3      | 0.55%   |
| ASMT                | 2         | 2      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 504       | 678    | 69.04%  |
| SSD  | 178       | 227    | 24.38%  |
| NVMe | 48        | 73     | 6.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 14.29%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 7.14%   |
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 7.14%   |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 7.14%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 7.14%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 7.14%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 7.14%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 4         | 5      | 28.57%  |
| WDC                     | 3         | 3      | 21.43%  |
| Seagate                 | 2         | 2      | 14.29%  |
| Kingston                | 2         | 2      | 14.29%  |
| Union Memory (Shenzhen) | 1         | 1      | 7.14%   |
| Transcend               | 1         | 1      | 7.14%   |
| Phison                  | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3706      | 8143   | 47.31%  |
| Detected | 3414      | 6963   | 43.58%  |
| Malfunc  | 698       | 978    | 8.91%   |
| Failed   | 14        | 15     | 0.18%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3796      | 38.59%  |
| AMD                              | 1851      | 18.82%  |
| Samsung Electronics              | 1438      | 14.62%  |
| SanDisk                          | 596       | 6.06%   |
| SK hynix                         | 307       | 3.12%   |
| Phison Electronics               | 254       | 2.58%   |
| Kingston Technology Company      | 199       | 2.02%   |
| ASMedia Technology               | 192       | 1.95%   |
| Micron Technology                | 173       | 1.76%   |
| Toshiba America Info Systems     | 156       | 1.59%   |
| Micron/Crucial Technology        | 133       | 1.35%   |
| ADATA Technology                 | 111       | 1.13%   |
| Silicon Motion                   | 102       | 1.04%   |
| KIOXIA                           | 84        | 0.85%   |
| Marvell Technology Group         | 76        | 0.77%   |
| Realtek Semiconductor            | 42        | 0.43%   |
| JMicron Technology               | 42        | 0.43%   |
| Union Memory (Shenzhen)          | 28        | 0.28%   |
| Solid State Storage Technology   | 21        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 21        | 0.21%   |
| Lite-On Technology               | 21        | 0.21%   |
| Broadcom / LSI                   | 21        | 0.21%   |
| Yangtze Memory Technologies      | 20        | 0.2%    |
| Nvidia                           | 19        | 0.19%   |
| Apple                            | 19        | 0.19%   |
| Seagate Technology               | 18        | 0.18%   |
| Lenovo                           | 18        | 0.18%   |
| Shenzhen Longsys Electronics     | 11        | 0.11%   |
| LSI Logic / Symbios Logic        | 11        | 0.11%   |
| Adaptec                          | 10        | 0.1%    |
| VIA Technologies                 | 7         | 0.07%   |
| Silicon Image                    | 7         | 0.07%   |
| Hewlett-Packard                  | 6         | 0.06%   |
| Silicon Integrated Systems [SiS] | 4         | 0.04%   |
| OCZ Technology Group             | 4         | 0.04%   |
| Netac Technology                 | 4         | 0.04%   |
| INNOGRIT                         | 3         | 0.03%   |
| Biwin Storage Technology         | 3         | 0.03%   |
| Integrated Technology Express    | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1397      | 12.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 816       | 7.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 424       | 3.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 355       | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 241       | 2.19%   |
| Samsung NVMe SSD Controller 980                                                | 229       | 2.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 227       | 2.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 218       | 1.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 203       | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 196       | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 195       | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 183       | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 177       | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 176       | 1.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 169       | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 161       | 1.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 155       | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 135       | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 133       | 1.21%   |
| Phison E12 NVMe Controller                                                     | 128       | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 128       | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 123       | 1.12%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 117       | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 117       | 1.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 114       | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 111       | 1.01%   |
| Intel SSD 660P Series                                                          | 109       | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 86        | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 83        | 0.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 83        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 78        | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 76        | 0.69%   |
| AMD 300 Series Chipset SATA Controller                                         | 75        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 71        | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 70        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 68        | 0.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 68        | 0.62%   |
| AMD X370 Series Chipset SATA Controller                                        | 64        | 0.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 62        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4970      | 52.39%  |
| NVMe | 3619      | 38.15%  |
| RAID | 531       | 5.6%    |
| IDE  | 334       | 3.52%   |
| SAS  | 24        | 0.25%   |
| SCSI | 8         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 4566      | 66.15%  |
| AMD        | 2336      | 33.84%  |
| thead,c906 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 118       | 1.7%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 111       | 1.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 103       | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 88        | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 88        | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 84        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 83        | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 79        | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 79        | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 78        | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 78        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 70        | 1.01%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 65        | 0.94%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 59        | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 56        | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 54        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 54        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 54        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 54        | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 53        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 52        | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 51        | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 50        | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 0.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 49        | 0.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 46        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 44        | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 44        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 41        | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 39        | 0.56%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 39        | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.55%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 38        | 0.55%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 38        | 0.55%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 38        | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 0.53%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 37        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 36        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1545      | 22.35%  |
| Intel Core i5           | 1437      | 20.79%  |
| AMD Ryzen 5             | 759       | 10.98%  |
| AMD Ryzen 7             | 710       | 10.27%  |
| Other                   | 540       | 7.81%   |
| Intel Core i3           | 314       | 4.54%   |
| AMD Ryzen 9             | 276       | 3.99%   |
| Intel Celeron           | 170       | 2.46%   |
| Intel Xeon              | 129       | 1.87%   |
| Intel Core 2 Duo        | 108       | 1.56%   |
| AMD Ryzen 3             | 100       | 1.45%   |
| Intel Pentium           | 93        | 1.35%   |
| AMD FX                  | 89        | 1.29%   |
| AMD Ryzen 7 PRO         | 76        | 1.1%    |
| Intel Core i9           | 73        | 1.06%   |
| Intel Atom              | 57        | 0.82%   |
| AMD A8                  | 36        | 0.52%   |
| AMD Ryzen Threadripper  | 34        | 0.49%   |
| AMD Ryzen 5 PRO         | 33        | 0.48%   |
| Intel Core 2 Quad       | 28        | 0.41%   |
| AMD A10                 | 28        | 0.41%   |
| AMD A6                  | 27        | 0.39%   |
| Intel Pentium Dual-Core | 21        | 0.3%    |
| AMD Athlon              | 21        | 0.3%    |
| AMD A4                  | 19        | 0.27%   |
| Intel Pentium Silver    | 18        | 0.26%   |
| AMD Phenom II X4        | 14        | 0.2%    |
| Intel Genuine           | 10        | 0.14%   |
| Intel Core m3           | 10        | 0.14%   |
| AMD E2                  | 10        | 0.14%   |
| AMD Athlon II X2        | 10        | 0.14%   |
| AMD Athlon II X4        | 9         | 0.13%   |
| AMD E                   | 8         | 0.12%   |
| Intel Core 2            | 7         | 0.1%    |
| AMD Phenom II X6        | 7         | 0.1%    |
| Intel Pentium Dual      | 6         | 0.09%   |
| AMD E1                  | 6         | 0.09%   |
| AMD Athlon 64 X2        | 6         | 0.09%   |
| Intel Core m5           | 5         | 0.07%   |
| AMD Athlon X4           | 5         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2534      | 36.63%  |
| 2       | 1734      | 25.07%  |
| 6       | 1110      | 16.05%  |
| 8       | 1020      | 14.75%  |
| 12      | 205       | 2.96%   |
| 16      | 117       | 1.69%   |
| 10      | 48        | 0.69%   |
| 14      | 45        | 0.65%   |
| 1       | 36        | 0.52%   |
| 3       | 29        | 0.42%   |
| 24      | 17        | 0.25%   |
| 32      | 7         | 0.1%    |
| 64      | 4         | 0.06%   |
| Unknown | 3         | 0.04%   |
| 28      | 2         | 0.03%   |
| 18      | 2         | 0.03%   |
| 40      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6864      | 99.44%  |
| 2       | 38        | 0.55%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5550      | 80.31%  |
| 1       | 1358      | 19.65%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6794      | 98.28%  |
| Unknown        | 115       | 1.66%   |
| 32-bit         | 4         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2619      | 36.42%  |
| 0x08701021 | 211       | 2.93%   |
| 0x306a9    | 208       | 2.89%   |
| 0x906ea    | 203       | 2.82%   |
| 0x306c3    | 201       | 2.79%   |
| 0x206a7    | 181       | 2.52%   |
| 0x906e9    | 172       | 2.39%   |
| 0x806ea    | 169       | 2.35%   |
| 0x0800820d | 151       | 2.1%    |
| 0x806ec    | 138       | 1.92%   |
| 0x806c1    | 136       | 1.89%   |
| 0x0a50000c | 127       | 1.77%   |
| 0x506e3    | 123       | 1.71%   |
| 0x406e3    | 111       | 1.54%   |
| 0x806e9    | 106       | 1.47%   |
| 0x08701013 | 99        | 1.38%   |
| 0x306d4    | 92        | 1.28%   |
| 0x08108102 | 90        | 1.25%   |
| 0x08600106 | 89        | 1.24%   |
| 0x40651    | 87        | 1.21%   |
| 0x08108109 | 82        | 1.14%   |
| 0x1067a    | 68        | 0.95%   |
| 0x08001138 | 64        | 0.89%   |
| 0xa0652    | 62        | 0.86%   |
| 0x0a201016 | 59        | 0.82%   |
| 0x08608103 | 54        | 0.75%   |
| 0x08600104 | 53        | 0.74%   |
| 0x20655    | 50        | 0.7%    |
| 0x0a201009 | 50        | 0.7%    |
| 0x806eb    | 46        | 0.64%   |
| 0x08600103 | 44        | 0.61%   |
| 0x0a50000d | 41        | 0.57%   |
| 0x0a404102 | 40        | 0.56%   |
| 0x0a601203 | 39        | 0.54%   |
| 0x706e5    | 38        | 0.53%   |
| 0x906ed    | 36        | 0.5%    |
| 0x0810100b | 36        | 0.5%    |
| 0x08001137 | 29        | 0.4%    |
| 0x06000852 | 29        | 0.4%    |
| 0x906a3    | 28        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1480      | 21.37%  |
| Zen 2            | 660       | 9.53%   |
| Haswell          | 510       | 7.37%   |
| Zen 3            | 453       | 6.54%   |
| Zen+             | 434       | 6.27%   |
| Skylake          | 402       | 5.81%   |
| Unknown          | 356       | 5.14%   |
| IvyBridge        | 338       | 4.88%   |
| SandyBridge      | 303       | 4.38%   |
| TigerLake        | 259       | 3.74%   |
| Zen              | 229       | 3.31%   |
| CometLake        | 198       | 2.86%   |
| Broadwell        | 163       | 2.35%   |
| Penryn           | 146       | 2.11%   |
| IceLake          | 119       | 1.72%   |
| Alderlake Hybrid | 117       | 1.69%   |
| Piledriver       | 110       | 1.59%   |
| Silvermont       | 108       | 1.56%   |
| Westmere         | 107       | 1.55%   |
| Goldmont plus    | 59        | 0.85%   |
| K10              | 54        | 0.78%   |
| Excavator        | 48        | 0.69%   |
| Core             | 45        | 0.65%   |
| Nehalem          | 42        | 0.61%   |
| Goldmont         | 33        | 0.48%   |
| Bobcat           | 21        | 0.3%    |
| K10 Llano        | 20        | 0.29%   |
| Bonnell          | 20        | 0.29%   |
| Steamroller      | 19        | 0.27%   |
| Puma             | 18        | 0.26%   |
| Jaguar           | 13        | 0.19%   |
| Tremont          | 11        | 0.16%   |
| K8 Hammer        | 10        | 0.14%   |
| NetBurst         | 7         | 0.1%    |
| Bulldozer        | 7         | 0.1%    |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3546      | 41.43%  |
| Nvidia                           | 2684      | 31.36%  |
| AMD                              | 2291      | 26.77%  |
| Matrox Electronics Systems       | 18        | 0.21%   |
| ASPEED Technology                | 11        | 0.13%   |
| Silicon Integrated Systems [SiS] | 4         | 0.05%   |
| ATI Technologies                 | 3         | 0.04%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 301       | 3.43%   |
| Intel UHD Graphics 620                                                                   | 253       | 2.89%   |
| AMD Renoir                                                                               | 237       | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 233       | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 230       | 2.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 216       | 2.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 202       | 2.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 201       | 2.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 184       | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 179       | 2.04%   |
| Intel HD Graphics 620                                                                    | 163       | 1.86%   |
| Intel HD Graphics 630                                                                    | 160       | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 154       | 1.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 144       | 1.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 136       | 1.55%   |
| Intel HD Graphics 5500                                                                   | 124       | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 113       | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 1.27%   |
| AMD Lucienne                                                                             | 107       | 1.22%   |
| Intel HD Graphics 530                                                                    | 102       | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 99        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 97        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 89        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 88        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 82        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 81        | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 77        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 76        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 74        | 0.84%   |
| AMD Rembrandt [Radeon 680M]                                                              | 70        | 0.8%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 69        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 63        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 62        | 0.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 61        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 60        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 57        | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 57        | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 57        | 0.65%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 57        | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 55        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2176      | 31.23%  |
| 1 x AMD                  | 1744      | 25.03%  |
| 1 x Nvidia               | 1286      | 18.46%  |
| Intel + Nvidia           | 1112      | 15.96%  |
| AMD + Nvidia             | 251       | 3.6%    |
| Intel + AMD              | 177       | 2.54%   |
| 2 x AMD                  | 123       | 1.77%   |
| 2 x Nvidia               | 35        | 0.5%    |
| 2 x Intel                | 15        | 0.22%   |
| 1 x Matrox               | 13        | 0.19%   |
| Other                    | 8         | 0.11%   |
| 1 x ASPEED               | 6         | 0.09%   |
| 1 x SiS                  | 4         | 0.06%   |
| AMD + ASPEED             | 4         | 0.06%   |
| Nvidia + Matrox          | 3         | 0.04%   |
| 2 x AMD + 1 x Nvidia     | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5005      | 71.73%  |
| Proprietary | 1899      | 27.21%  |
| Unknown     | 74        | 1.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3867      | 54.29%  |
| 7.01-8.0   | 682       | 9.57%   |
| 1.01-2.0   | 630       | 8.84%   |
| 0.01-0.5   | 547       | 7.68%   |
| 3.01-4.0   | 540       | 7.58%   |
| 0.51-1.0   | 284       | 3.99%   |
| 5.01-6.0   | 270       | 3.79%   |
| 8.01-16.0  | 221       | 3.1%    |
| 2.01-3.0   | 57        | 0.8%    |
| 16.01-24.0 | 21        | 0.29%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 930       | 11.09%  |
| Samsung Electronics     | 908       | 10.83%  |
| BOE                     | 762       | 9.09%   |
| Chimei Innolux          | 668       | 7.97%   |
| LG Display              | 639       | 7.62%   |
| Dell                    | 579       | 6.91%   |
| Goldstar                | 501       | 5.98%   |
| Acer                    | 325       | 3.88%   |
| AOC                     | 272       | 3.24%   |
| BenQ                    | 254       | 3.03%   |
| Hewlett-Packard         | 238       | 2.84%   |
| Sharp                   | 221       | 2.64%   |
| Ancor Communications    | 209       | 2.49%   |
| Philips                 | 158       | 1.88%   |
| Lenovo                  | 140       | 1.67%   |
| PANDA                   | 120       | 1.43%   |
| ViewSonic               | 105       | 1.25%   |
| ASUSTek Computer        | 100       | 1.19%   |
| Apple                   | 99        | 1.18%   |
| Iiyama                  | 91        | 1.09%   |
| InfoVision              | 61        | 0.73%   |
| LG Electronics          | 59        | 0.7%    |
| MSI                     | 51        | 0.61%   |
| CSO                     | 47        | 0.56%   |
| Sony                    | 46        | 0.55%   |
| Unknown                 | 44        | 0.52%   |
| Gigabyte Technology     | 37        | 0.44%   |
| NEC Computers           | 36        | 0.43%   |
| Eizo                    | 34        | 0.41%   |
| Chi Mei Optoelectronics | 34        | 0.41%   |
| Panasonic               | 24        | 0.29%   |
| TMX                     | 22        | 0.26%   |
| Fujitsu Siemens         | 22        | 0.26%   |
| Unknown                 | 21        | 0.25%   |
| Sceptre Tech            | 20        | 0.24%   |
| Toshiba                 | 16        | 0.19%   |
| HannStar                | 16        | 0.19%   |
| Vizio                   | 15        | 0.18%   |
| Valve                   | 15        | 0.18%   |
| Pixio                   | 14        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 51        | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 44        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 40        | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 39        | 0.45%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 34        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 33        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 31        | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 30        | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 29        | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 26        | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 26        | 0.3%    |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 24        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 23        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 22        | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 21        | 0.24%   |
| Unknown                                                              | 21        | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 20        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 19        | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 18        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 18        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 18        | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 17        | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 16        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.18%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 16        | 0.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 15        | 0.17%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 15        | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 15        | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.17%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                       | 15        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 14        | 0.16%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch          | 14        | 0.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 14        | 0.16%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch     | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 14        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3806      | 48.23%  |
| 1366x768 (WXGA)    | 906       | 11.48%  |
| 3840x2160 (4K)     | 631       | 8%      |
| 2560x1440 (QHD)    | 609       | 7.72%   |
| 1920x1200 (WUXGA)  | 229       | 2.9%    |
| 1600x900 (HD+)     | 203       | 2.57%   |
| 1680x1050 (WSXGA+) | 153       | 1.94%   |
| 3440x1440          | 142       | 1.8%    |
| Unknown            | 132       | 1.67%   |
| 1280x1024 (SXGA)   | 131       | 1.66%   |
| 1440x900 (WXGA+)   | 108       | 1.37%   |
| 2560x1600          | 96        | 1.22%   |
| 2560x1080          | 92        | 1.17%   |
| 1280x800 (WXGA)    | 60        | 0.76%   |
| 3840x1080          | 59        | 0.75%   |
| 2880x1800          | 58        | 0.74%   |
| 1360x768           | 49        | 0.62%   |
| 3840x2400          | 44        | 0.56%   |
| 2160x1440          | 26        | 0.33%   |
| 2256x1504          | 24        | 0.3%    |
| 3840x1600          | 22        | 0.28%   |
| 3200x1800 (QHD+)   | 22        | 0.28%   |
| 1920x540           | 20        | 0.25%   |
| 2736x1824          | 18        | 0.23%   |
| 3000x2000          | 13        | 0.16%   |
| 1600x1200          | 11        | 0.14%   |
| 7680x2160          | 10        | 0.13%   |
| 3200x2000          | 10        | 0.13%   |
| 3072x1920          | 10        | 0.13%   |
| 1920x1280          | 10        | 0.13%   |
| 5760x1080          | 9         | 0.11%   |
| 4480x1440          | 9         | 0.11%   |
| 2240x1400          | 9         | 0.11%   |
| 5120x1440          | 8         | 0.1%    |
| 1280x720 (HD)      | 8         | 0.1%    |
| 1024x600           | 8         | 0.1%    |
| 1024x768 (XGA)     | 7         | 0.09%   |
| 2520x1680          | 6         | 0.08%   |
| 2288x1287          | 6         | 0.08%   |
| 800x1280           | 5         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1871      | 22.44%  |
| 13      | 835       | 10.01%  |
| 27      | 824       | 9.88%   |
| 24      | 780       | 9.35%   |
| 14      | 715       | 8.57%   |
| 23      | 541       | 6.49%   |
| 21      | 467       | 5.6%    |
| Unknown | 412       | 4.94%   |
| 17      | 292       | 3.5%    |
| 34      | 194       | 2.33%   |
| 31      | 178       | 2.13%   |
| 19      | 159       | 1.91%   |
| 12      | 142       | 1.7%    |
| 18      | 114       | 1.37%   |
| 22      | 110       | 1.32%   |
| 16      | 93        | 1.12%   |
| 20      | 77        | 0.92%   |
| 11      | 60        | 0.72%   |
| 84      | 44        | 0.53%   |
| 72      | 43        | 0.52%   |
| 25      | 41        | 0.49%   |
| 54      | 29        | 0.35%   |
| 40      | 28        | 0.34%   |
| 32      | 27        | 0.32%   |
| 48      | 26        | 0.31%   |
| 26      | 25        | 0.3%    |
| 28      | 23        | 0.28%   |
| 10      | 21        | 0.25%   |
| 29      | 20        | 0.24%   |
| 37      | 19        | 0.23%   |
| 46      | 12        | 0.14%   |
| 35      | 11        | 0.13%   |
| 65      | 10        | 0.12%   |
| 33      | 10        | 0.12%   |
| 49      | 8         | 0.1%    |
| 43      | 7         | 0.08%   |
| 42      | 7         | 0.08%   |
| 39      | 7         | 0.08%   |
| 142     | 6         | 0.07%   |
| 74      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3038      | 37.65%  |
| 501-600        | 1915      | 23.73%  |
| 401-500        | 819       | 10.15%  |
| 201-300        | 680       | 8.43%   |
| Unknown        | 412       | 5.11%   |
| 351-400        | 371       | 4.6%    |
| 601-700        | 302       | 3.74%   |
| 701-800        | 234       | 2.9%    |
| 1001-1500      | 107       | 1.33%   |
| 1501-2000      | 93        | 1.15%   |
| 801-900        | 70        | 0.87%   |
| 901-1000       | 15        | 0.19%   |
| More than 2000 | 7         | 0.09%   |
| 1-100          | 4         | 0.05%   |
| 101-200        | 3         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5486      | 75.43%  |
| 16/10   | 842       | 11.58%  |
| Unknown | 352       | 4.84%   |
| 21/9    | 240       | 3.3%    |
| 5/4     | 131       | 1.8%    |
| 3/2     | 124       | 1.7%    |
| 4/3     | 35        | 0.48%   |
| 32/9    | 34        | 0.47%   |
| 1.00    | 6         | 0.08%   |
| 2.65    | 4         | 0.05%   |
| 6/5     | 3         | 0.04%   |
| 3.40    | 3         | 0.04%   |
| 2.00    | 3         | 0.04%   |
| 1.96    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |
| 0.57    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1858      | 22.63%  |
| 201-250        | 1486      | 18.1%   |
| 81-90          | 1172      | 14.27%  |
| 301-350        | 847       | 10.31%  |
| 351-500        | 441       | 5.37%   |
| Unknown        | 412       | 5.02%   |
| 71-80          | 374       | 4.55%   |
| 151-200        | 336       | 4.09%   |
| 251-300        | 282       | 3.43%   |
| 121-130        | 207       | 2.52%   |
| More than 1000 | 164       | 2%      |
| 141-150        | 147       | 1.79%   |
| 61-70          | 127       | 1.55%   |
| 501-1000       | 117       | 1.42%   |
| 111-120        | 90        | 1.1%    |
| 51-60          | 65        | 0.79%   |
| 131-140        | 31        | 0.38%   |
| 91-100         | 31        | 0.38%   |
| 41-50          | 19        | 0.23%   |
| 1-40           | 6         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2403      | 30.34%  |
| 51-100        | 2296      | 28.99%  |
| 101-120       | 1681      | 21.23%  |
| 161-240       | 699       | 8.83%   |
| Unknown       | 412       | 5.2%    |
| More than 240 | 295       | 3.73%   |
| 1-50          | 133       | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5130      | 72.53%  |
| 2     | 1520      | 21.49%  |
| 3     | 256       | 3.62%   |
| 0     | 140       | 1.98%   |
| 4     | 24        | 0.34%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3907      | 37.97%  |
| Realtek Semiconductor             | 3709      | 36.04%  |
| Qualcomm Atheros                  | 919       | 8.93%   |
| Broadcom                          | 367       | 3.57%   |
| MediaTek                          | 238       | 2.31%   |
| TP-Link                           | 105       | 1.02%   |
| Ralink Technology                 | 85        | 0.83%   |
| Microsoft                         | 69        | 0.67%   |
| Broadcom Limited                  | 68        | 0.66%   |
| Marvell Technology Group          | 62        | 0.6%    |
| ASIX Electronics                  | 57        | 0.55%   |
| Ralink                            | 51        | 0.5%    |
| Lenovo                            | 49        | 0.48%   |
| Qualcomm                          | 41        | 0.4%    |
| Sierra Wireless                   | 36        | 0.35%   |
| Samsung Electronics               | 35        | 0.34%   |
| Xiaomi                            | 33        | 0.32%   |
| DisplayLink                       | 30        | 0.29%   |
| Aquantia                          | 29        | 0.28%   |
| Ericsson Business Mobile Networks | 27        | 0.26%   |
| D-Link                            | 23        | 0.22%   |
| NetGear                           | 21        | 0.2%    |
| Dell                              | 19        | 0.18%   |
| Qualcomm Atheros Communications   | 18        | 0.17%   |
| Google                            | 18        | 0.17%   |
| Apple                             | 16        | 0.16%   |
| Nvidia                            | 15        | 0.15%   |
| Hewlett-Packard                   | 15        | 0.15%   |
| Mellanox Technologies             | 14        | 0.14%   |
| Huawei Technologies               | 14        | 0.14%   |
| Microchip Technology              | 11        | 0.11%   |
| ASUSTek Computer                  | 11        | 0.11%   |
| OPPO Electronics                  | 9         | 0.09%   |
| Motorola PCS                      | 9         | 0.09%   |
| Linksys                           | 8         | 0.08%   |
| D-Link System                     | 8         | 0.08%   |
| Cypress Semiconductor             | 8         | 0.08%   |
| Oculus VR                         | 7         | 0.07%   |
| Fibocom                           | 7         | 0.07%   |
| JMicron Technology                | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2604      | 21.45%  |
| Intel Wi-Fi 6 AX200                                               | 588       | 4.84%   |
| Intel I211 Gigabit Network Connection                             | 401       | 3.3%    |
| Intel Wireless 8265 / 8275                                        | 292       | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 266       | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 251       | 2.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 230       | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 196       | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 191       | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 175       | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 174       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 172       | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 166       | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 163       | 1.34%   |
| Intel Wireless 8260                                               | 155       | 1.28%   |
| Intel Wireless 7265                                               | 152       | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 138       | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 133       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 127       | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 117       | 0.96%   |
| Intel Wireless 7260                                               | 116       | 0.96%   |
| Intel Wireless-AC 9260                                            | 111       | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 109       | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 105       | 0.87%   |
| Intel Wireless 3165                                               | 99        | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 98        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 98        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 96        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 95        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 93        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 92        | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 91        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 89        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 74        | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 70        | 0.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 68        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 61        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 53        | 0.44%   |
| Intel Wireless 3160                                               | 52        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3068      | 54.1%   |
| Realtek Semiconductor                 | 798       | 14.07%  |
| Qualcomm Atheros                      | 722       | 12.73%  |
| Broadcom                              | 278       | 4.9%    |
| MediaTek                              | 234       | 4.13%   |
| TP-Link                               | 91        | 1.6%    |
| Ralink Technology                     | 85        | 1.5%    |
| Microsoft                             | 61        | 1.08%   |
| Ralink                                | 51        | 0.9%    |
| Broadcom Limited                      | 51        | 0.9%    |
| Sierra Wireless                       | 36        | 0.63%   |
| Qualcomm                              | 35        | 0.62%   |
| Marvell Technology Group              | 22        | 0.39%   |
| D-Link                                | 20        | 0.35%   |
| NetGear                               | 19        | 0.34%   |
| Qualcomm Atheros Communications       | 18        | 0.32%   |
| Dell                                  | 12        | 0.21%   |
| ASUSTek Computer                      | 11        | 0.19%   |
| Linksys                               | 8         | 0.14%   |
| Fibocom                               | 7         | 0.12%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| Edimax Technology                     | 6         | 0.11%   |
| D-Link System                         | 4         | 0.07%   |
| AVM                                   | 4         | 0.07%   |
| Wilocity                              | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| Belkin Components                     | 3         | 0.05%   |
| Xiaomi                                | 2         | 0.04%   |
| Tenda                                 | 2         | 0.04%   |
| Micro Star International              | 2         | 0.04%   |
| IMC Networks                          | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Yoctopuce Sarl                        | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| BUFFALO                               | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 588       | 10.32%  |
| Intel Wireless 8265 / 8275                                     | 292       | 5.13%   |
| Intel Wi-Fi 6 AX201                                            | 196       | 3.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 175       | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 174       | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 172       | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 163       | 2.86%   |
| Intel Wireless 8260                                            | 155       | 2.72%   |
| Intel Wireless 7265                                            | 152       | 2.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 138       | 2.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 133       | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 127       | 2.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 117       | 2.05%   |
| Intel Wireless 7260                                            | 116       | 2.04%   |
| Intel Wireless-AC 9260                                         | 111       | 1.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 105       | 1.84%   |
| Intel Wireless 3165                                            | 99        | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 98        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 98        | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 96        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 95        | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 93        | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 89        | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 89        | 1.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 70        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 68        | 1.19%   |
| Intel Wireless 3160                                            | 52        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 50        | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 49        | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 49        | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 43        | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 41        | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 39        | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 39        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 36        | 0.63%   |
| Realtek 802.11ac NIC                                           | 33        | 0.58%   |
| Microsoft Xbox 360 Wireless Adapter                            | 32        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                | 31        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3372      | 54.7%   |
| Intel                                  | 1929      | 31.29%  |
| Qualcomm Atheros                       | 262       | 4.25%   |
| Broadcom                               | 137       | 2.22%   |
| ASIX Electronics                       | 57        | 0.92%   |
| Lenovo                                 | 45        | 0.73%   |
| Marvell Technology Group               | 40        | 0.65%   |
| Samsung Electronics                    | 35        | 0.57%   |
| Xiaomi                                 | 31        | 0.5%    |
| DisplayLink                            | 30        | 0.49%   |
| Aquantia                               | 29        | 0.47%   |
| Broadcom Limited                       | 17        | 0.28%   |
| Google                                 | 16        | 0.26%   |
| Apple                                  | 16        | 0.26%   |
| Nvidia                                 | 15        | 0.24%   |
| TP-Link                                | 14        | 0.23%   |
| Mellanox Technologies                  | 12        | 0.19%   |
| OPPO Electronics                       | 9         | 0.15%   |
| Cypress Semiconductor                  | 8         | 0.13%   |
| Microsoft                              | 7         | 0.11%   |
| Huawei Technologies                    | 7         | 0.11%   |
| Qualcomm                               | 6         | 0.1%    |
| Motorola PCS                           | 6         | 0.1%    |
| JMicron Technology                     | 6         | 0.1%    |
| MediaTek                               | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.06%   |
| ICS Advent                             | 4         | 0.06%   |
| D-Link System                          | 4         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.05%   |
| QLogic                                 | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| NetGear                                | 2         | 0.03%   |
| IBM                                    | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Emulex                                 | 2         | 0.03%   |
| American Megatrends                    | 2         | 0.03%   |
| Xilinx                                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2604      | 41.2%   |
| Intel I211 Gigabit Network Connection                             | 401       | 6.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 266       | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 251       | 3.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 230       | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 191       | 3.02%   |
| Intel Ethernet Connection (2) I219-V                              | 166       | 2.63%   |
| Intel Ethernet Controller I225-V                                  | 109       | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 92        | 1.46%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 74        | 1.17%   |
| Intel Ethernet Connection (4) I219-V                              | 61        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 53        | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 48        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 48        | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 47        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 47        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 46        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 44        | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 43        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 42        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 36        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 32        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 31        | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 29        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 27        | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                             | 27        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 25        | 0.4%    |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.38%   |
| Intel 82574L Gigabit Network Connection                           | 24        | 0.38%   |
| Intel Ethernet Connection I219-V                                  | 23        | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5735      | 50.91%  |
| WiFi     | 5410      | 48.02%  |
| Modem    | 102       | 0.91%   |
| Unknown  | 18        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4142      | 56.88%  |
| Ethernet | 3138      | 43.09%  |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3657      | 52.73%  |
| 1     | 2974      | 42.88%  |
| 3     | 206       | 2.97%   |
| 0     | 59        | 0.85%   |
| 4     | 24        | 0.35%   |
| 5     | 7         | 0.1%    |
| 6     | 5         | 0.07%   |
| 10    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5749      | 81.95%  |
| Yes  | 1266      | 18.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2716      | 54.47%  |
| Realtek Semiconductor           | 441       | 8.84%   |
| Cambridge Silicon Radio         | 330       | 6.62%   |
| Qualcomm Atheros Communications | 286       | 5.74%   |
| IMC Networks                    | 194       | 3.89%   |
| Broadcom                        | 179       | 3.59%   |
| Foxconn / Hon Hai               | 157       | 3.15%   |
| Lite-On Technology              | 153       | 3.07%   |
| ASUSTek Computer                | 114       | 2.29%   |
| Apple                           | 99        | 1.99%   |
| MediaTek                        | 57        | 1.14%   |
| Realtek                         | 50        | 1%      |
| Dell                            | 34        | 0.68%   |
| TP-Link                         | 22        | 0.44%   |
| Marvell Semiconductor           | 20        | 0.4%    |
| Hewlett-Packard                 | 20        | 0.4%    |
| USI                             | 14        | 0.28%   |
| HTC (High Tech Computer)        | 14        | 0.28%   |
| Toshiba                         | 13        | 0.26%   |
| Ralink                          | 12        | 0.24%   |
| Foxconn International           | 8         | 0.16%   |
| Edimax Technology               | 8         | 0.16%   |
| Dynex                           | 6         | 0.12%   |
| Opticis                         | 5         | 0.1%    |
| Integrated System Solution      | 4         | 0.08%   |
| Smart Modular Technologies      | 3         | 0.06%   |
| Micro Star International        | 3         | 0.06%   |
| Chicony Electronics             | 3         | 0.06%   |
| Askey Computer                  | 3         | 0.06%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Ralink Technology               | 2         | 0.04%   |
| ISSC                            | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Alps Electric                   | 2         | 0.04%   |
| Actions                         | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 835       | 16.72%  |
| Intel AX200 Bluetooth                               | 565       | 11.31%  |
| Intel AX201 Bluetooth                               | 439       | 8.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 359       | 7.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 330       | 6.61%   |
| Realtek Bluetooth Radio                             | 285       | 5.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 152       | 3.04%   |
| Intel AX210 Bluetooth                               | 137       | 2.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 130       | 2.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 103       | 2.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 97        | 1.94%   |
| Intel Bluetooth Device                              | 97        | 1.94%   |
| IMC Networks Wireless_Device                        | 72        | 1.44%   |
| IMC Networks Bluetooth Radio                        | 65        | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 62        | 1.24%   |
| MediaTek Wireless_Device                            | 56        | 1.12%   |
| Apple Bluetooth Host Controller                     | 54        | 1.08%   |
| Realtek Bluetooth Radio                             | 50        | 1%      |
| Lite-On Bluetooth Device                            | 50        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 48        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 48        | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 44        | 0.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 44        | 0.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 39        | 0.78%   |
| IMC Networks Bluetooth Device                       | 37        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 0.62%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 31        | 0.62%   |
| Apple Bluetooth USB Host Controller                 | 27        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 26        | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 24        | 0.48%   |
| Lite-On Wireless_Device                             | 24        | 0.48%   |
| TP-Link UB5A Adapter                                | 22        | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                         | 19        | 0.38%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite        | 16        | 0.32%   |
| ASUS Bluetooth Radio                                | 15        | 0.3%    |
| USI Bluetooth Device                                | 14        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 4428      | 40.51%  |
| AMD                         | 2661      | 24.35%  |
| Nvidia                      | 2028      | 18.55%  |
| C-Media Electronics         | 252       | 2.31%   |
| Logitech                    | 124       | 1.13%   |
| Kingston Technology         | 92        | 0.84%   |
| Focusrite-Novation          | 74        | 0.68%   |
| Texas Instruments           | 73        | 0.67%   |
| JMTek                       | 67        | 0.61%   |
| SteelSeries ApS             | 62        | 0.57%   |
| Razer USA                   | 62        | 0.57%   |
| Realtek Semiconductor       | 59        | 0.54%   |
| Lenovo                      | 49        | 0.45%   |
| Creative Labs               | 46        | 0.42%   |
| Creative Technology         | 44        | 0.4%    |
| Corsair                     | 42        | 0.38%   |
| Blue Microphones            | 40        | 0.37%   |
| ASUSTek Computer            | 39        | 0.36%   |
| GN Netcom                   | 31        | 0.28%   |
| Samson Technologies         | 27        | 0.25%   |
| Valve Software              | 23        | 0.21%   |
| Generalplus Technology      | 23        | 0.21%   |
| Apple                       | 23        | 0.21%   |
| Yamaha                      | 22        | 0.2%    |
| GYROCOM C&C                 | 21        | 0.19%   |
| BEHRINGER International     | 20        | 0.18%   |
| Sony                        | 19        | 0.17%   |
| Plantronics                 | 16        | 0.15%   |
| RODE Microphones            | 15        | 0.14%   |
| Micro Star International    | 15        | 0.14%   |
| FiiO Electronics Technology | 15        | 0.14%   |
| Audio-Technica              | 15        | 0.14%   |
| XMOS                        | 14        | 0.13%   |
| SAVITECH                    | 14        | 0.13%   |
| M-Audio                     | 13        | 0.12%   |
| Microsoft                   | 11        | 0.1%    |
| Hewlett-Packard             | 11        | 0.1%    |
| DSEA A/S                    | 11        | 0.1%    |
| Cambridge Silicon Radio     | 11        | 0.1%    |
| Dell                        | 10        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 999       | 7.58%   |
| Intel Sunrise Point-LP HD Audio                                            | 629       | 4.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 598       | 4.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 498       | 3.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 367       | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 333       | 2.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 333       | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 302       | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 273       | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 263       | 1.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 259       | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 258       | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 236       | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 215       | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 195       | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 190       | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 186       | 1.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 185       | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 179       | 1.36%   |
| AMD Navi 10 HDMI Audio                                                     | 173       | 1.31%   |
| Nvidia GP106 High Definition Audio Controller                              | 148       | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 148       | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 147       | 1.12%   |
| Intel Broadwell-U Audio Controller                                         | 146       | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 145       | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 145       | 1.1%    |
| Intel 8 Series HD Audio Controller                                         | 145       | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 144       | 1.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 141       | 1.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 127       | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 127       | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 125       | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 120       | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 116       | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 111       | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 103       | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 101       | 0.77%   |
| AMD FCH Azalia Controller                                                  | 101       | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 100       | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 91        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1233      | 21.01%  |
| SK hynix                     | 930       | 15.85%  |
| Kingston                     | 732       | 12.47%  |
| Micron Technology            | 575       | 9.8%    |
| Corsair                      | 562       | 9.58%   |
| Crucial                      | 465       | 7.92%   |
| G.Skill                      | 363       | 6.19%   |
| Unknown                      | 300       | 5.11%   |
| A-DATA Technology            | 115       | 1.96%   |
| Ramaxel Technology           | 91        | 1.55%   |
| Team                         | 54        | 0.92%   |
| Elpida                       | 53        | 0.9%    |
| Patriot                      | 48        | 0.82%   |
| GOODRAM                      | 35        | 0.6%    |
| Nanya Technology             | 29        | 0.49%   |
| Unknown                      | 29        | 0.49%   |
| Unknown (ABCD)               | 22        | 0.37%   |
| Transcend                    | 19        | 0.32%   |
| Smart                        | 19        | 0.32%   |
| AMD                          | 17        | 0.29%   |
| PNY                          | 15        | 0.26%   |
| Apacer                       | 10        | 0.17%   |
| Goldkey                      | 9         | 0.15%   |
| Smart Brazil                 | 7         | 0.12%   |
| Teikon                       | 6         | 0.1%    |
| Golden Empire                | 6         | 0.1%    |
| Silicon Power                | 5         | 0.09%   |
| Kingmax                      | 5         | 0.09%   |
| GeIL                         | 5         | 0.09%   |
| Avant                        | 5         | 0.09%   |
| Wilk Elektronik              | 4         | 0.07%   |
| Neo Forza                    | 4         | 0.07%   |
| Wilk                         | 3         | 0.05%   |
| V-GeN                        | 3         | 0.05%   |
| V-Color                      | 3         | 0.05%   |
| Patriot Memory (PDP Systems) | 3         | 0.05%   |
| Lexar                        | 3         | 0.05%   |
| KLEVV                        | 3         | 0.05%   |
| GSkill                       | 3         | 0.05%   |
| ASint Technology             | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 73        | 1.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 66        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 66        | 1.05%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 62        | 0.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 54        | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 46        | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 37        | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 37        | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 33        | 0.53%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 33        | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s   | 31        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 30        | 0.48%   |
| Unknown                                                     | 29        | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 28        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 28        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 28        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 28        | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 27        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 27        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 26        | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 26        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 26        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 25        | 0.4%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 25        | 0.4%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 25        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 24        | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 24        | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 24        | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 23        | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 22        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 21        | 0.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 21        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 21        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 21        | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 21        | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 20        | 0.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 20        | 0.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 19        | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 19        | 0.3%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s         | 19        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 3107      | 61.56%  |
| DDR3    | 1180      | 23.38%  |
| LPDDR4  | 201       | 3.98%   |
| LPDDR3  | 150       | 2.97%   |
| DDR5    | 123       | 2.44%   |
| LPDDR5  | 74        | 1.47%   |
| Unknown | 68        | 1.35%   |
| SDRAM   | 64        | 1.27%   |
| DDR2    | 62        | 1.23%   |
| DDR     | 15        | 0.3%    |
| DRAM    | 3         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2652      | 52.5%   |
| DIMM         | 1903      | 37.68%  |
| Row Of Chips | 439       | 8.69%   |
| Chip         | 39        | 0.77%   |
| Unknown      | 15        | 0.3%    |
| RIMM         | 2         | 0.04%   |
| FB-DIMM      | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2531      | 46.21%  |
| 4096  | 1190      | 21.73%  |
| 16384 | 1057      | 19.3%   |
| 2048  | 357       | 6.52%   |
| 32768 | 275       | 5.02%   |
| 1024  | 59        | 1.08%   |
| 512   | 6         | 0.11%   |
| 65536 | 2         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 993       | 17.97%  |
| 2667    | 871       | 15.76%  |
| 1600    | 771       | 13.95%  |
| 2400    | 445       | 8.05%   |
| 3600    | 301       | 5.45%   |
| 2133    | 281       | 5.08%   |
| 1333    | 215       | 3.89%   |
| 1867    | 133       | 2.41%   |
| 4267    | 105       | 1.9%    |
| 1334    | 104       | 1.88%   |
| 3266    | 89        | 1.61%   |
| 4800    | 88        | 1.59%   |
| 6400    | 83        | 1.5%    |
| 3400    | 76        | 1.38%   |
| 3733    | 65        | 1.18%   |
| 3000    | 63        | 1.14%   |
| 3533    | 57        | 1.03%   |
| 2933    | 56        | 1.01%   |
| 3800    | 54        | 0.98%   |
| 667     | 49        | 0.89%   |
| 1866    | 41        | 0.74%   |
| 1067    | 38        | 0.69%   |
| 2666    | 35        | 0.63%   |
| Unknown | 35        | 0.63%   |
| 4266    | 32        | 0.58%   |
| 3866    | 32        | 0.58%   |
| 2800    | 32        | 0.58%   |
| 1066    | 31        | 0.56%   |
| 3666    | 30        | 0.54%   |
| 800     | 30        | 0.54%   |
| 3466    | 27        | 0.49%   |
| 1800    | 26        | 0.47%   |
| 4199    | 19        | 0.34%   |
| 8400    | 18        | 0.33%   |
| 400     | 12        | 0.22%   |
| 4000    | 11        | 0.2%    |
| 3333    | 11        | 0.2%    |
| 2733    | 11        | 0.2%    |
| 2048    | 10        | 0.18%   |
| 6000    | 9         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 37        | 37%     |
| Brother Industries       | 17        | 17%     |
| Samsung Electronics      | 13        | 13%     |
| Canon                    | 13        | 13%     |
| Seiko Epson              | 4         | 4%      |
| Prolific Technology      | 4         | 4%      |
| Dymo-CoStar              | 3         | 3%      |
| Zebra                    | 1         | 1%      |
| Xerox                    | 1         | 1%      |
| STMicroelectronics       | 1         | 1%      |
| Ricoh                    | 1         | 1%      |
| QinHeng Electronics      | 1         | 1%      |
| Philips (or NXP)         | 1         | 1%      |
| Magic Control Technology | 1         | 1%      |
| Fuji Xerox               | 1         | 1%      |
| Dell                     | 1         | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 4         | 4%      |
| Samsung M2070 Series                                      | 3         | 3%      |
| HP DeskJet 2130 series                                    | 3         | 3%      |
| Samsung SCX-4100 Scanner                                  | 2         | 2%      |
| HP Officejet Pro 8100                                     | 2         | 2%      |
| HP LaserJet P2015 series                                  | 2         | 2%      |
| HP LaserJet 1022                                          | 2         | 2%      |
| HP LaserJet 1018                                          | 2         | 2%      |
| HP LaserJet 1012                                          | 2         | 2%      |
| HP DeskJet F4200 series                                   | 2         | 2%      |
| HP DeskJet 840c                                           | 2         | 2%      |
| HP Deskjet 3050 J610 series                               | 2         | 2%      |
| HP DeskJet 2600 series                                    | 2         | 2%      |
| Dymo-CoStar LabelWriter 450                               | 2         | 2%      |
| Brother Printer                                           | 2         | 2%      |
| Brother HL-L2320D series                                  | 2         | 2%      |
| Brother HL-5370DW series                                  | 2         | 2%      |
| Brother DCP-1510                                          | 2         | 2%      |
| Zebra LP2844 Printer                                      | 1         | 1%      |
| Xerox Phaser 3020                                         | 1         | 1%      |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1%      |
| Seiko Epson XP-7100 Series                                | 1         | 1%      |
| Seiko Epson WF-2530 Series                                | 1         | 1%      |
| Seiko Epson Printer                                       | 1         | 1%      |
| Seiko Epson L3110 Series                                  | 1         | 1%      |
| Samsung SCX-4200 series                                   | 1         | 1%      |
| Samsung SCX-3200 Series                                   | 1         | 1%      |
| Samsung ML-216x Series Laser Printer                      | 1         | 1%      |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1%      |
| Samsung M267x 287x Series                                 | 1         | 1%      |
| Samsung M2020 Series                                      | 1         | 1%      |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1%      |
| Samsung C1860 Series                                      | 1         | 1%      |
| Ricoh SP 150SU                                            | 1         | 1%      |
| QinHeng CH340S                                            | 1         | 1%      |
| Philips (or NXP) USB Printer                              | 1         | 1%      |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1%      |
| HP PSC-1315/PSC-1317                                      | 1         | 1%      |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1%      |
| HP Officejet 4500 G510g-m                                 | 1         | 1%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 884       | 19.87%  |
| IMC Networks                           | 487       | 10.94%  |
| Logitech                               | 389       | 8.74%   |
| Microdia                               | 372       | 8.36%   |
| Realtek Semiconductor                  | 291       | 6.54%   |
| Bison Electronics                      | 291       | 6.54%   |
| Quanta                                 | 239       | 5.37%   |
| Sunplus Innovation Technology          | 193       | 4.34%   |
| Cheng Uei Precision Industry (Foxlink) | 141       | 3.17%   |
| Syntek                                 | 120       | 2.7%    |
| Lite-On Technology                     | 107       | 2.4%    |
| Acer                                   | 105       | 2.36%   |
| Apple                                  | 89        | 2%      |
| Luxvisions Innotech Limited            | 80        | 1.8%    |
| Suyin                                  | 66        | 1.48%   |
| Microsoft                              | 59        | 1.33%   |
| Samsung Electronics                    | 46        | 1.03%   |
| Alcor Micro                            | 43        | 0.97%   |
| Silicon Motion                         | 42        | 0.94%   |
| Sonix Technology                       | 34        | 0.76%   |
| Lenovo                                 | 31        | 0.7%    |
| Z-Star Microelectronics                | 23        | 0.52%   |
| SunplusIT                              | 20        | 0.45%   |
| Valve Software                         | 19        | 0.43%   |
| MacroSilicon                           | 19        | 0.43%   |
| ARC International                      | 15        | 0.34%   |
| Razer USA                              | 13        | 0.29%   |
| Importek                               | 13        | 0.29%   |
| Ricoh                                  | 11        | 0.25%   |
| KYE Systems (Mouse Systems)            | 11        | 0.25%   |
| Creative Technology                    | 11        | 0.25%   |
| ALi                                    | 11        | 0.25%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.2%    |
| Generalplus Technology                 | 9         | 0.2%    |
| LG Electronics                         | 8         | 0.18%   |
| Jieli Technology                       | 8         | 0.18%   |
| Primax Electronics                     | 7         | 0.16%   |
| Trust                                  | 6         | 0.13%   |
| Google                                 | 6         | 0.13%   |
| Unknown                                | 5         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 256       | 5.69%   |
| Microdia Integrated_Webcam_HD                                              | 185       | 4.11%   |
| IMC Networks Integrated Camera                                             | 162       | 3.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 149       | 3.31%   |
| Realtek Integrated_Webcam_HD                                               | 113       | 2.51%   |
| Bison Integrated Camera                                                    | 110       | 2.45%   |
| Logitech HD Pro Webcam C920                                                | 99        | 2.2%    |
| Sunplus Integrated_Webcam_HD                                               | 85        | 1.89%   |
| Chicony HD WebCam                                                          | 83        | 1.85%   |
| Syntek Integrated Camera                                                   | 82        | 1.82%   |
| Logitech Webcam C270                                                       | 61        | 1.36%   |
| Lite-On Integrated Camera                                                  | 53        | 1.18%   |
| Quanta HD User Facing                                                      | 52        | 1.16%   |
| Bison HD Webcam                                                            | 50        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 46        | 1.02%   |
| Bison SunplusIT Integrated Camera                                          | 46        | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 37        | 0.82%   |
| Chicony USB2.0 Camera                                                      | 37        | 0.82%   |
| Chicony HD User Facing                                                     | 37        | 0.82%   |
| Chicony Integrated Camera (1280x720@30)                                    | 36        | 0.8%    |
| Chicony HP Wide Vision HD Camera                                           | 35        | 0.78%   |
| Chicony HP HD Camera                                                       | 35        | 0.78%   |
| Apple FaceTime HD Camera (Built-in)                                        | 35        | 0.78%   |
| Logitech C922 Pro Stream Webcam                                            | 32        | 0.71%   |
| Microdia Integrated Webcam                                                 | 31        | 0.69%   |
| Quanta HP Wide Vision HD Camera                                            | 28        | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 28        | 0.62%   |
| Realtek USB Camera                                                         | 27        | 0.6%    |
| Sunplus HD WebCam                                                          | 26        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 26        | 0.58%   |
| IMC Networks ov9734_azurewave_camera                                       | 25        | 0.56%   |
| Chicony HP Truevision HD                                                   | 25        | 0.56%   |
| Acer Integrated Camera                                                     | 25        | 0.56%   |
| Microdia Webcam Vitade AF                                                  | 24        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 24        | 0.53%   |
| Chicony Integrated IR Camera                                               | 24        | 0.53%   |
| Realtek Integrated Webcam                                                  | 23        | 0.51%   |
| Quanta HP TrueVision HD Camera                                             | 23        | 0.51%   |
| Microdia USB 2.0 Camera                                                    | 23        | 0.51%   |
| Logitech BRIO                                                              | 23        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 357       | 37.27%  |
| Validity Sensors                   | 246       | 25.68%  |
| Shenzhen Goodix Technology         | 183       | 19.1%   |
| Elan Microelectronics              | 59        | 6.16%   |
| LighTuning Technology              | 33        | 3.44%   |
| Upek                               | 30        | 3.13%   |
| AuthenTec                          | 21        | 2.19%   |
| STMicroelectronics                 | 10        | 1.04%   |
| Samsung Electronics                | 6         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.42%   |
| Microsoft                          | 4         | 0.42%   |
| HOLTEK                             | 3         | 0.31%   |
| Focal-systems.Corp                 | 1         | 0.1%    |
| DigitalPersona                     | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 125       | 13.05%  |
| Shenzhen Goodix  Fingerprint Device                                        | 96        | 10.02%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 55        | 5.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 52        | 5.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 44        | 4.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 3.97%   |
| Validity Sensors Synaptics WBDI                                            | 35        | 3.65%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 3.65%   |
| Synaptics UWP WBDI                                                         | 33        | 3.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 2.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 27        | 2.82%   |
| Elan ELAN:Fingerprint                                                      | 27        | 2.82%   |
| Elan ELAN:ARM-M4                                                           | 23        | 2.4%    |
| Synaptics  WBDI                                                            | 22        | 2.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 20        | 2.09%   |
| Synaptics WBDI                                                             | 20        | 2.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 2.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 19        | 1.98%   |
| Synaptics Fingerprint reader [HP G6]                                       | 18        | 1.88%   |
| Synaptics UWP WBDI Device                                                  | 16        | 1.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.57%   |
| Validity Sensors VFS491                                                    | 13        | 1.36%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.15%   |
| AuthenTec AES2810                                                          | 11        | 1.15%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 1.04%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.94%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.63%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.42%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.42%   |
| Synaptics WBDI Device                                                      | 4         | 0.42%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.42%   |
| Microsoft Fingerprint Reader                                               | 4         | 0.42%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 145       | 40.17%  |
| Broadcom                          | 120       | 33.24%  |
| Upek                              | 24        | 6.65%   |
| Lenovo                            | 13        | 3.6%    |
| O2 Micro                          | 9         | 2.49%   |
| Clay Logic                        | 8         | 2.22%   |
| Gemalto (was Gemplus)             | 7         | 1.94%   |
| Yubico.com                        | 6         | 1.66%   |
| Advanced Card Systems             | 6         | 1.66%   |
| SCM Microsystems                  | 5         | 1.39%   |
| Reiner SCT Kartensysteme          | 4         | 1.11%   |
| Aladdin Knowledge Systems         | 3         | 0.83%   |
| OmniKey                           | 2         | 0.55%   |
| Aktiv                             | 2         | 0.55%   |
| VASCO Data Security International | 1         | 0.28%   |
| Realtek Semiconductor             | 1         | 0.28%   |
| Hewlett-Packard                   | 1         | 0.28%   |
| Fujitsu Siemens Computers         | 1         | 0.28%   |
| Chicony Electronics               | 1         | 0.28%   |
| C3PO                              | 1         | 0.28%   |
| Aladdin R.D.                      | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 143       | 39.61%  |
| Broadcom 5880                                                                | 33        | 9.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 8.31%   |
| Broadcom 58200                                                               | 28        | 7.76%   |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 7.48%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 6.65%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 3.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 2.22%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 1.66%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.83%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.83%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.83%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.83%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.83%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.83%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.55%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.55%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.55%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.55%   |
| Aktiv Rutoken lite                                                           | 2         | 0.55%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.28%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.28%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.28%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.28%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.28%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.28%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.28%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.28%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.28%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.28%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.28%   |
| C3PO LTC31v2                                                                 | 1         | 0.28%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.28%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.28%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4914      | 69.67%  |
| 1     | 1712      | 24.27%  |
| 2     | 342       | 4.85%   |
| 3     | 70        | 0.99%   |
| 4     | 11        | 0.16%   |
| 6     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 933       | 36.26%  |
| Graphics card            | 484       | 18.81%  |
| Chipcard                 | 305       | 11.85%  |
| Net/wireless             | 221       | 8.59%   |
| Multimedia controller    | 186       | 7.23%   |
| Camera                   | 132       | 5.13%   |
| Unassigned class         | 59        | 2.29%   |
| Bluetooth                | 51        | 1.98%   |
| Communication controller | 49        | 1.9%    |
| Sound                    | 38        | 1.48%   |
| Net/ethernet             | 27        | 1.05%   |
| Network                  | 25        | 0.97%   |
| Storage                  | 18        | 0.7%    |
| Card reader              | 14        | 0.54%   |
| Modem                    | 11        | 0.43%   |
| Dvb card                 | 8         | 0.31%   |
| Wireless                 | 2         | 0.08%   |
| Storage/raid             | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Flash memory             | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

