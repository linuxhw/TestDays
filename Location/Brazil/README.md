Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 17598

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8H61-M LX                  | Desktop     | [5721cbc403](https://linux-hardware.org/?probe=5721cbc403) | Feb 28, 2023 |
| Philco        | 10D                         | Notebook    | [dd709d35db](https://linux-hardware.org/?probe=dd709d35db) | Feb 28, 2023 |
| Samsung       | 370E4K                      | Notebook    | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ee8e20d95e](https://linux-hardware.org/?probe=ee8e20d95e) | Feb 27, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [52a17bf9c1](https://linux-hardware.org/?probe=52a17bf9c1) | Feb 27, 2023 |
| Samsung       | 370E4K                      | Notebook    | [d66bcd2bc8](https://linux-hardware.org/?probe=d66bcd2bc8) | Feb 27, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [04c721038a](https://linux-hardware.org/?probe=04c721038a) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| HP            | 430                         | Notebook    | [f90c967f06](https://linux-hardware.org/?probe=f90c967f06) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | Notebook    | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [47eff629e0](https://linux-hardware.org/?probe=47eff629e0) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| FIC           | PTM33 PCB                   | Desktop     | [b70b076cda](https://linux-hardware.org/?probe=b70b076cda) | Feb 26, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [2168c2bb5c](https://linux-hardware.org/?probe=2168c2bb5c) | Feb 26, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Dell          | G15 5520                    | Notebook    | [d68c28ea8d](https://linux-hardware.org/?probe=d68c28ea8d) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [0a5dfbb9e6](https://linux-hardware.org/?probe=0a5dfbb9e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [75e601b927](https://linux-hardware.org/?probe=75e601b927) | Feb 26, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [5911354b82](https://linux-hardware.org/?probe=5911354b82) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| Dell          | G7 7588                     | Notebook    | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [faee032e6c](https://linux-hardware.org/?probe=faee032e6c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [af95b24466](https://linux-hardware.org/?probe=af95b24466) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [37bcb5eb45](https://linux-hardware.org/?probe=37bcb5eb45) | Feb 25, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| HP            | 2AA2                        | Desktop     | [b9411eadb7](https://linux-hardware.org/?probe=b9411eadb7) | Feb 25, 2023 |
| ASUSTek       | Z450LA                      | Notebook    | [304be04748](https://linux-hardware.org/?probe=304be04748) | Feb 25, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [dff66700c0](https://linux-hardware.org/?probe=dff66700c0) | Feb 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [15b5511875](https://linux-hardware.org/?probe=15b5511875) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [23c0509d46](https://linux-hardware.org/?probe=23c0509d46) | Feb 25, 2023 |
| Sony          | VPCCW13FB                   | Notebook    | [1772a3987b](https://linux-hardware.org/?probe=1772a3987b) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [6d03ea4905](https://linux-hardware.org/?probe=6d03ea4905) | Feb 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [d3354bd88c](https://linux-hardware.org/?probe=d3354bd88c) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [eda674b9a5](https://linux-hardware.org/?probe=eda674b9a5) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [5c7e454884](https://linux-hardware.org/?probe=5c7e454884) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [2a8b727725](https://linux-hardware.org/?probe=2a8b727725) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c0af9c8bdb](https://linux-hardware.org/?probe=c0af9c8bdb) | Feb 24, 2023 |
| Positivo      | N1103                       | Notebook    | [b89c4551aa](https://linux-hardware.org/?probe=b89c4551aa) | Feb 24, 2023 |
| Positivo      | Q464C-O                     | Notebook    | [cda1faecb1](https://linux-hardware.org/?probe=cda1faecb1) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5b4def0870](https://linux-hardware.org/?probe=5b4def0870) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Dell          | Latitude 3420               | Notebook    | [86fd73d1e3](https://linux-hardware.org/?probe=86fd73d1e3) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| System76      | Gazelle                     | Notebook    | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [05f7c375b7](https://linux-hardware.org/?probe=05f7c375b7) | Feb 23, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | Desktop     | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [fd084cb513](https://linux-hardware.org/?probe=fd084cb513) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| Positivo      | Q464C                       | Notebook    | [1b08f16a08](https://linux-hardware.org/?probe=1b08f16a08) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | Notebook    | [5b173518b5](https://linux-hardware.org/?probe=5b173518b5) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | Notebook    | [107bd5b235](https://linux-hardware.org/?probe=107bd5b235) | Feb 22, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [f02c3d5895](https://linux-hardware.org/?probe=f02c3d5895) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Positivo      | S14SL01                     | Notebook    | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [ad766a4190](https://linux-hardware.org/?probe=ad766a4190) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Positivo      | S14CT01                     | Notebook    | [af73fc0481](https://linux-hardware.org/?probe=af73fc0481) | Feb 22, 2023 |
| Samsung       | 767XCL                      | Notebook    | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [ff88bcbafc](https://linux-hardware.org/?probe=ff88bcbafc) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [818012d7ef](https://linux-hardware.org/?probe=818012d7ef) | Feb 21, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [d1c356a1c7](https://linux-hardware.org/?probe=d1c356a1c7) | Feb 21, 2023 |
| INET          | Z12B                        | Mini pc     | [0baa359181](https://linux-hardware.org/?probe=0baa359181) | Feb 21, 2023 |
| INET          | Z12B                        | Mini pc     | [cc6d503d94](https://linux-hardware.org/?probe=cc6d503d94) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ae2e7a22a0](https://linux-hardware.org/?probe=ae2e7a22a0) | Feb 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [08eab2bac4](https://linux-hardware.org/?probe=08eab2bac4) | Feb 21, 2023 |
| Avell High... | 1513                        | Notebook    | [0b46cb6de1](https://linux-hardware.org/?probe=0b46cb6de1) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Compaq        | 430                         | Notebook    | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| HP            | 1000                        | Notebook    | [91faf9460d](https://linux-hardware.org/?probe=91faf9460d) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASRock        | AM1B-MH                     | Desktop     | [d67d348d90](https://linux-hardware.org/?probe=d67d348d90) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Win elemen... | M600                        | Desktop     | [76c26f5ebb](https://linux-hardware.org/?probe=76c26f5ebb) | Feb 20, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e7e12370af](https://linux-hardware.org/?probe=e7e12370af) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [cccf0ea7f3](https://linux-hardware.org/?probe=cccf0ea7f3) | Feb 20, 2023 |
| AMD           | A78FX VER                   | Desktop     | [36eb566c26](https://linux-hardware.org/?probe=36eb566c26) | Feb 20, 2023 |
| Intel         | H55                         | Desktop     | [6102979c67](https://linux-hardware.org/?probe=6102979c67) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [8c8ae38704](https://linux-hardware.org/?probe=8c8ae38704) | Feb 19, 2023 |
| Dell          | 04YP6J A03                  | Desktop     | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| HP            | Compaq Presario CQ42        | Notebook    | [001f2f1a86](https://linux-hardware.org/?probe=001f2f1a86) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [ca537a9b24](https://linux-hardware.org/?probe=ca537a9b24) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [d5dbc5770a](https://linux-hardware.org/?probe=d5dbc5770a) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [e06b3509f1](https://linux-hardware.org/?probe=e06b3509f1) | Feb 19, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [6be03ad579](https://linux-hardware.org/?probe=6be03ad579) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Avell High... | B.ON                        | Notebook    | [d7f2dafd5e](https://linux-hardware.org/?probe=d7f2dafd5e) | Feb 18, 2023 |
| Acer          | Spin SP315-51               | Convertible | [7a3814b168](https://linux-hardware.org/?probe=7a3814b168) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [889231ad64](https://linux-hardware.org/?probe=889231ad64) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [beff031939](https://linux-hardware.org/?probe=beff031939) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Intel         | H61                         | Desktop     | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [f3c66a583b](https://linux-hardware.org/?probe=f3c66a583b) | Feb 17, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [daf6a78f6f](https://linux-hardware.org/?probe=daf6a78f6f) | Feb 17, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [de9c98193e](https://linux-hardware.org/?probe=de9c98193e) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9d88e03390](https://linux-hardware.org/?probe=9d88e03390) | Feb 17, 2023 |
| Samsung       | 550XDA                      | Notebook    | [d7f1482689](https://linux-hardware.org/?probe=d7f1482689) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Intel         | B75                         | All in one  | [5d2d67dec2](https://linux-hardware.org/?probe=5d2d67dec2) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [9200702bb7](https://linux-hardware.org/?probe=9200702bb7) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| DIEBOLD       | H55H-CM                     | Desktop     | [fdfc5c5e92](https://linux-hardware.org/?probe=fdfc5c5e92) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [cf5749e5be](https://linux-hardware.org/?probe=cf5749e5be) | Feb 16, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Positivo      | CHT14B                      | Notebook    | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [b66ca441a7](https://linux-hardware.org/?probe=b66ca441a7) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [37674ee96e](https://linux-hardware.org/?probe=37674ee96e) | Feb 16, 2023 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | Notebook    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| HP            | 8434 11                     | Desktop     | [2f4023e5f3](https://linux-hardware.org/?probe=2f4023e5f3) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e42ed53dcf](https://linux-hardware.org/?probe=e42ed53dcf) | Feb 15, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [35fcd679e5](https://linux-hardware.org/?probe=35fcd679e5) | Feb 15, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [8385999199](https://linux-hardware.org/?probe=8385999199) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Acer          | Predator G3-572             | Notebook    | [410a9aae8c](https://linux-hardware.org/?probe=410a9aae8c) | Feb 14, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [a401dfe086](https://linux-hardware.org/?probe=a401dfe086) | Feb 14, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [3569214674](https://linux-hardware.org/?probe=3569214674) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [5fefbd2419](https://linux-hardware.org/?probe=5fefbd2419) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [0b0a816ecc](https://linux-hardware.org/?probe=0b0a816ecc) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [4785d6d596](https://linux-hardware.org/?probe=4785d6d596) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [60794bd7c3](https://linux-hardware.org/?probe=60794bd7c3) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [ed4d687c32](https://linux-hardware.org/?probe=ed4d687c32) | Feb 14, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [805931ad5f](https://linux-hardware.org/?probe=805931ad5f) | Feb 14, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [39564bbf72](https://linux-hardware.org/?probe=39564bbf72) | Feb 13, 2023 |
| Positivo      | CHT14B                      | Notebook    | [859e8a3c17](https://linux-hardware.org/?probe=859e8a3c17) | Feb 13, 2023 |
| Positivo      | CHT14B                      | Notebook    | [2d5b910ed3](https://linux-hardware.org/?probe=2d5b910ed3) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | Notebook    | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | Desktop     | [56411004d4](https://linux-hardware.org/?probe=56411004d4) | Feb 13, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [e4b1d6656b](https://linux-hardware.org/?probe=e4b1d6656b) | Feb 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| Intel         | H61                         | Desktop     | [f220565e36](https://linux-hardware.org/?probe=f220565e36) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [75f2859a68](https://linux-hardware.org/?probe=75f2859a68) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [ec0e0c6dc2](https://linux-hardware.org/?probe=ec0e0c6dc2) | Feb 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9fa2cd7dfb](https://linux-hardware.org/?probe=9fa2cd7dfb) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [800d3a961c](https://linux-hardware.org/?probe=800d3a961c) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [7a6e4d8211](https://linux-hardware.org/?probe=7a6e4d8211) | Feb 12, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [f1b285512e](https://linux-hardware.org/?probe=f1b285512e) | Feb 12, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [d2fec952ae](https://linux-hardware.org/?probe=d2fec952ae) | Feb 12, 2023 |
| Colorful T... | CVN B450M GAMING V14        | Desktop     | [fdedcd0d4a](https://linux-hardware.org/?probe=fdedcd0d4a) | Feb 11, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1623076357](https://linux-hardware.org/?probe=1623076357) | Feb 11, 2023 |
| Compaq        | Presario CQ-14              | Desktop     | [515b629bbc](https://linux-hardware.org/?probe=515b629bbc) | Feb 11, 2023 |
| Samsung       | 767XCL                      | Notebook    | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [e32070b494](https://linux-hardware.org/?probe=e32070b494) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [594e3be773](https://linux-hardware.org/?probe=594e3be773) | Feb 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [2dca851444](https://linux-hardware.org/?probe=2dca851444) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d85a564e73](https://linux-hardware.org/?probe=d85a564e73) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | Desktop     | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [e3ad5a0e88](https://linux-hardware.org/?probe=e3ad5a0e88) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [52125d1623](https://linux-hardware.org/?probe=52125d1623) | Feb 10, 2023 |
| Samsung       | 550XDA                      | Notebook    | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| Lenovo        | Unknown                     | Desktop     | [253bcab6fa](https://linux-hardware.org/?probe=253bcab6fa) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [0f111bd12b](https://linux-hardware.org/?probe=0f111bd12b) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [2c17efbcd7](https://linux-hardware.org/?probe=2c17efbcd7) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c5c9fb9b41](https://linux-hardware.org/?probe=c5c9fb9b41) | Feb 09, 2023 |
| Acer          | Aspire A315-53G             | Notebook    | [e2a551b06b](https://linux-hardware.org/?probe=e2a551b06b) | Feb 09, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [452c65c04b](https://linux-hardware.org/?probe=452c65c04b) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5e1eb34232](https://linux-hardware.org/?probe=5e1eb34232) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [fe84bf2bc9](https://linux-hardware.org/?probe=fe84bf2bc9) | Feb 09, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [43968e7a27](https://linux-hardware.org/?probe=43968e7a27) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [74f2ac0aeb](https://linux-hardware.org/?probe=74f2ac0aeb) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Dell          | 0TW904                      | Desktop     | [01c887764a](https://linux-hardware.org/?probe=01c887764a) | Feb 08, 2023 |
| Dell          | G15 5515                    | Notebook    | [3b0208199f](https://linux-hardware.org/?probe=3b0208199f) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Intel         | H61                         | Desktop     | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Dell          | 0TW904                      | Desktop     | [f88778be48](https://linux-hardware.org/?probe=f88778be48) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7e020b928e](https://linux-hardware.org/?probe=7e020b928e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0a94d67455](https://linux-hardware.org/?probe=0a94d67455) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [2a34c65a5d](https://linux-hardware.org/?probe=2a34c65a5d) | Feb 06, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [0b35653efd](https://linux-hardware.org/?probe=0b35653efd) | Feb 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a2378e95f6](https://linux-hardware.org/?probe=a2378e95f6) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cfdb3767fb](https://linux-hardware.org/?probe=cfdb3767fb) | Feb 06, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [986d240b5d](https://linux-hardware.org/?probe=986d240b5d) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [f0aa46956b](https://linux-hardware.org/?probe=f0aa46956b) | Feb 06, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0e0bd23571](https://linux-hardware.org/?probe=0e0bd23571) | Feb 05, 2023 |
| Quanta        | TWS                         | Notebook    | [275ccf1b58](https://linux-hardware.org/?probe=275ccf1b58) | Feb 05, 2023 |
| Dell          | G15 5510                    | Notebook    | [41bbdf84c2](https://linux-hardware.org/?probe=41bbdf84c2) | Feb 05, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5c63c52fd4](https://linux-hardware.org/?probe=5c63c52fd4) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [02d439f664](https://linux-hardware.org/?probe=02d439f664) | Feb 05, 2023 |
| LG Electro... | R590-U.BE57P1               | Desktop     | [7de316c06f](https://linux-hardware.org/?probe=7de316c06f) | Feb 05, 2023 |
| ASRock        | H61M-HP4                    | Desktop     | [826a81ae2e](https://linux-hardware.org/?probe=826a81ae2e) | Feb 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | G400s VILG1                 | Notebook    | [426348e103](https://linux-hardware.org/?probe=426348e103) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| Dell          | G15 5515                    | Notebook    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| Evolute       | SFX-65                      | Notebook    | [7b37b32f92](https://linux-hardware.org/?probe=7b37b32f92) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [7cd8292c5f](https://linux-hardware.org/?probe=7cd8292c5f) | Feb 04, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | Desktop     | [01a8e618f5](https://linux-hardware.org/?probe=01a8e618f5) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7659183894](https://linux-hardware.org/?probe=7659183894) | Feb 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [de29ca3277](https://linux-hardware.org/?probe=de29ca3277) | Feb 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0185beaec6](https://linux-hardware.org/?probe=0185beaec6) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | Notebook    | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Dell          | Precision M4600             | Notebook    | [a0d6749416](https://linux-hardware.org/?probe=a0d6749416) | Feb 04, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6f3ba6b805](https://linux-hardware.org/?probe=6f3ba6b805) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | Notebook    | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| HP            | 3048h                       | Desktop     | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [5c7d71b636](https://linux-hardware.org/?probe=5c7d71b636) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [f99e3aa76d](https://linux-hardware.org/?probe=f99e3aa76d) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Dell          | 0TW904                      | Desktop     | [83d5b82840](https://linux-hardware.org/?probe=83d5b82840) | Feb 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [656df2cea9](https://linux-hardware.org/?probe=656df2cea9) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [a99bd855d2](https://linux-hardware.org/?probe=a99bd855d2) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [b82450078c](https://linux-hardware.org/?probe=b82450078c) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [17a4a2e5fd](https://linux-hardware.org/?probe=17a4a2e5fd) | Feb 02, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [92d639c0f4](https://linux-hardware.org/?probe=92d639c0f4) | Feb 02, 2023 |
| Dell          | Latitude 7480               | Notebook    | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de08972b9](https://linux-hardware.org/?probe=2de08972b9) | Feb 02, 2023 |
| Positivo      | Mobile                      | Notebook    | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [516e83f7e6](https://linux-hardware.org/?probe=516e83f7e6) | Feb 02, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [721bc8fb78](https://linux-hardware.org/?probe=721bc8fb78) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [1d26f2fcbc](https://linux-hardware.org/?probe=1d26f2fcbc) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [895cb06490](https://linux-hardware.org/?probe=895cb06490) | Feb 02, 2023 |
| Insyde        | Braswell                    | Notebook    | [928b461a5b](https://linux-hardware.org/?probe=928b461a5b) | Feb 02, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [e296e8530f](https://linux-hardware.org/?probe=e296e8530f) | Feb 02, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [9a5e6fd61e](https://linux-hardware.org/?probe=9a5e6fd61e) | Feb 02, 2023 |
| Philco        | 14I                         | Notebook    | [8f9833285e](https://linux-hardware.org/?probe=8f9833285e) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [c4e6e989f5](https://linux-hardware.org/?probe=c4e6e989f5) | Feb 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [b2dd8d93c7](https://linux-hardware.org/?probe=b2dd8d93c7) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6aa10285fe](https://linux-hardware.org/?probe=6aa10285fe) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fa4104f438](https://linux-hardware.org/?probe=fa4104f438) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [ec80fcb8a5](https://linux-hardware.org/?probe=ec80fcb8a5) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | Desktop     | [20868d90a7](https://linux-hardware.org/?probe=20868d90a7) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | Desktop     | [d67831dc82](https://linux-hardware.org/?probe=d67831dc82) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [aa3b7e2dc8](https://linux-hardware.org/?probe=aa3b7e2dc8) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f6f4bc8c7](https://linux-hardware.org/?probe=2f6f4bc8c7) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [3f497311dd](https://linux-hardware.org/?probe=3f497311dd) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Dell          | 06HR05 A00                  | Desktop     | [b80c55d90d](https://linux-hardware.org/?probe=b80c55d90d) | Jan 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d8d386cb1d](https://linux-hardware.org/?probe=d8d386cb1d) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [bb5d758714](https://linux-hardware.org/?probe=bb5d758714) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e5dc585024](https://linux-hardware.org/?probe=e5dc585024) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [95fe94d9f4](https://linux-hardware.org/?probe=95fe94d9f4) | Jan 30, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [88db10e257](https://linux-hardware.org/?probe=88db10e257) | Jan 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [79e7fde988](https://linux-hardware.org/?probe=79e7fde988) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | Notebook    | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Avell High... | B.ON                        | Notebook    | [721fbbdeb2](https://linux-hardware.org/?probe=721fbbdeb2) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [1c62beb905](https://linux-hardware.org/?probe=1c62beb905) | Jan 29, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [ca82a3e5a7](https://linux-hardware.org/?probe=ca82a3e5a7) | Jan 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [51245400df](https://linux-hardware.org/?probe=51245400df) | Jan 29, 2023 |
| Intel         | H61                         | Desktop     | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [0e6a170715](https://linux-hardware.org/?probe=0e6a170715) | Jan 29, 2023 |
| Intel         | H61                         | Desktop     | [0ce404915f](https://linux-hardware.org/?probe=0ce404915f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Positivo      | Q464C-O                     | Notebook    | [e61f2d0622](https://linux-hardware.org/?probe=e61f2d0622) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [8dee7ae6ec](https://linux-hardware.org/?probe=8dee7ae6ec) | Jan 28, 2023 |
| Dell          | G15 5520                    | Notebook    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [ca72045652](https://linux-hardware.org/?probe=ca72045652) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [de8739d9d5](https://linux-hardware.org/?probe=de8739d9d5) | Jan 28, 2023 |
| ASUSTek       | A58M-A/BR                   | Desktop     | [2e6e55e6ea](https://linux-hardware.org/?probe=2e6e55e6ea) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [fd9d67e4b8](https://linux-hardware.org/?probe=fd9d67e4b8) | Jan 27, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ee2e6ab56](https://linux-hardware.org/?probe=3ee2e6ab56) | Jan 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [c74ea31148](https://linux-hardware.org/?probe=c74ea31148) | Jan 27, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| HP            | Compaq 6530b                | Notebook    | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [93be3d62c4](https://linux-hardware.org/?probe=93be3d62c4) | Jan 27, 2023 |
| Compaq        | 430                         | Notebook    | [069fa715b9](https://linux-hardware.org/?probe=069fa715b9) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [b4d0bbaf56](https://linux-hardware.org/?probe=b4d0bbaf56) | Jan 27, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [d155136857](https://linux-hardware.org/?probe=d155136857) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [05dac90dec](https://linux-hardware.org/?probe=05dac90dec) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [0697311f5f](https://linux-hardware.org/?probe=0697311f5f) | Jan 27, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [5a333d4e71](https://linux-hardware.org/?probe=5a333d4e71) | Jan 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [90de00d686](https://linux-hardware.org/?probe=90de00d686) | Jan 26, 2023 |
| Dell          | G3 3500                     | Notebook    | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| HP            | 225E                        | Desktop     | [bace147a01](https://linux-hardware.org/?probe=bace147a01) | Jan 26, 2023 |
| HP            | 8299                        | Desktop     | [d73eaeeb81](https://linux-hardware.org/?probe=d73eaeeb81) | Jan 26, 2023 |
| HP            | 8299                        | Desktop     | [47b5f3fdef](https://linux-hardware.org/?probe=47b5f3fdef) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Dell          | Vostro 3458                 | Notebook    | [3beffe6710](https://linux-hardware.org/?probe=3beffe6710) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| Multilaser    | PC150                       | Notebook    | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b392e71ce5](https://linux-hardware.org/?probe=b392e71ce5) | Jan 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6eafb4ceab](https://linux-hardware.org/?probe=6eafb4ceab) | Jan 25, 2023 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [b8045702e2](https://linux-hardware.org/?probe=b8045702e2) | Jan 25, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [5e044ca68b](https://linux-hardware.org/?probe=5e044ca68b) | Jan 25, 2023 |
| HP            | G60                         | Notebook    | [8fe616c588](https://linux-hardware.org/?probe=8fe616c588) | Jan 25, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [a123c38d76](https://linux-hardware.org/?probe=a123c38d76) | Jan 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [cea7204c4b](https://linux-hardware.org/?probe=cea7204c4b) | Jan 25, 2023 |
| HP            | Folio 13                    | Notebook    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [2fbe64570f](https://linux-hardware.org/?probe=2fbe64570f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [7de7df58a3](https://linux-hardware.org/?probe=7de7df58a3) | Jan 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [fce5f618d8](https://linux-hardware.org/?probe=fce5f618d8) | Jan 24, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [02491de92f](https://linux-hardware.org/?probe=02491de92f) | Jan 24, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [418e5a2787](https://linux-hardware.org/?probe=418e5a2787) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Insyde        | Braswell                    | Notebook    | [6abab0adc1](https://linux-hardware.org/?probe=6abab0adc1) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [62aa75f57a](https://linux-hardware.org/?probe=62aa75f57a) | Jan 23, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [30967bc549](https://linux-hardware.org/?probe=30967bc549) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [4a97e29245](https://linux-hardware.org/?probe=4a97e29245) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [54ebd7c5f8](https://linux-hardware.org/?probe=54ebd7c5f8) | Jan 23, 2023 |
| Dell          | Latitude 3420               | Notebook    | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [08f11b861b](https://linux-hardware.org/?probe=08f11b861b) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f0c7e0be](https://linux-hardware.org/?probe=e7f0c7e0be) | Jan 23, 2023 |
| Alienware     | m15 R7                      | Notebook    | [e57302bf60](https://linux-hardware.org/?probe=e57302bf60) | Jan 23, 2023 |
| HP            | 540                         | Notebook    | [a4a7b26f42](https://linux-hardware.org/?probe=a4a7b26f42) | Jan 23, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [885f180987](https://linux-hardware.org/?probe=885f180987) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Unknown       | G41T-M7                     | Desktop     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7d4406c9bc](https://linux-hardware.org/?probe=7d4406c9bc) | Jan 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| Biostar       | A320MH                      | Desktop     | [4c75d6c079](https://linux-hardware.org/?probe=4c75d6c079) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [697fbcd8d1](https://linux-hardware.org/?probe=697fbcd8d1) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [b066912bf8](https://linux-hardware.org/?probe=b066912bf8) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [e5fff0ebe0](https://linux-hardware.org/?probe=e5fff0ebe0) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [42e0ba4db2](https://linux-hardware.org/?probe=42e0ba4db2) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [8a3035382a](https://linux-hardware.org/?probe=8a3035382a) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [6ddc2793d7](https://linux-hardware.org/?probe=6ddc2793d7) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [ae4c9eaa9c](https://linux-hardware.org/?probe=ae4c9eaa9c) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Philco        | OEM                         | Notebook    | [a39f50ccfd](https://linux-hardware.org/?probe=a39f50ccfd) | Jan 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f94d5172](https://linux-hardware.org/?probe=e7f94d5172) | Jan 21, 2023 |
| Lenovo        | 3148 SDK0L22692 WIN 3792... | Desktop     | [f66c33020e](https://linux-hardware.org/?probe=f66c33020e) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [fa251ca13c](https://linux-hardware.org/?probe=fa251ca13c) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [965d1fa09f](https://linux-hardware.org/?probe=965d1fa09f) | Jan 20, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [a37e873516](https://linux-hardware.org/?probe=a37e873516) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | Desktop     | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Intel         | B75                         | Desktop     | [40da372747](https://linux-hardware.org/?probe=40da372747) | Jan 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6364be5249](https://linux-hardware.org/?probe=6364be5249) | Jan 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [46e35da681](https://linux-hardware.org/?probe=46e35da681) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [2d420c3acb](https://linux-hardware.org/?probe=2d420c3acb) | Jan 20, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [c158cd6095](https://linux-hardware.org/?probe=c158cd6095) | Jan 20, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [97987f88e7](https://linux-hardware.org/?probe=97987f88e7) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33a3aac223](https://linux-hardware.org/?probe=33a3aac223) | Jan 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3447d19b00](https://linux-hardware.org/?probe=3447d19b00) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1320f35331](https://linux-hardware.org/?probe=1320f35331) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [c2f25e54e6](https://linux-hardware.org/?probe=c2f25e54e6) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [d4480b6267](https://linux-hardware.org/?probe=d4480b6267) | Jan 19, 2023 |
| Intel         | H110                        | Desktop     | [532f2a340e](https://linux-hardware.org/?probe=532f2a340e) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [41138327da](https://linux-hardware.org/?probe=41138327da) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [183de4d0f6](https://linux-hardware.org/?probe=183de4d0f6) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62aa341472](https://linux-hardware.org/?probe=62aa341472) | Jan 19, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [c2ed0fe829](https://linux-hardware.org/?probe=c2ed0fe829) | Jan 19, 2023 |
| Digitron      | G31T-M7                     | Desktop     | [ee9978ae25](https://linux-hardware.org/?probe=ee9978ae25) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| Compal        | Unknown                     | Notebook    | [81abfdb7d5](https://linux-hardware.org/?probe=81abfdb7d5) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Compal        | Unknown                     | Notebook    | [14cc4178d9](https://linux-hardware.org/?probe=14cc4178d9) | Jan 18, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| Intel         | H61                         | Desktop     | [be9b2384b0](https://linux-hardware.org/?probe=be9b2384b0) | Jan 18, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [80022afba6](https://linux-hardware.org/?probe=80022afba6) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3f0d644eaf](https://linux-hardware.org/?probe=3f0d644eaf) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [84479cfc00](https://linux-hardware.org/?probe=84479cfc00) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [22d07dfddf](https://linux-hardware.org/?probe=22d07dfddf) | Jan 18, 2023 |
| Toshiba       | STI 014293                  | Desktop     | [8e47b89089](https://linux-hardware.org/?probe=8e47b89089) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [032ac1d52e](https://linux-hardware.org/?probe=032ac1d52e) | Jan 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [1a8a1eea59](https://linux-hardware.org/?probe=1a8a1eea59) | Jan 17, 2023 |
| Login Info... | LOG-H110M-G3                | Desktop     | [74defcfa62](https://linux-hardware.org/?probe=74defcfa62) | Jan 17, 2023 |
| AZW           | SER V01                     | Mini pc     | [6048d12291](https://linux-hardware.org/?probe=6048d12291) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [0b7d83316f](https://linux-hardware.org/?probe=0b7d83316f) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [cd9cdce064](https://linux-hardware.org/?probe=cd9cdce064) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM                    | Desktop     | [e08287f623](https://linux-hardware.org/?probe=e08287f623) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM                    | Desktop     | [c4dbd0f9fe](https://linux-hardware.org/?probe=c4dbd0f9fe) | Jan 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a35e962cca](https://linux-hardware.org/?probe=a35e962cca) | Jan 17, 2023 |
| Positivo      | N1103                       | Notebook    | [e5b41b9ed2](https://linux-hardware.org/?probe=e5b41b9ed2) | Jan 17, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [f680ea1d22](https://linux-hardware.org/?probe=f680ea1d22) | Jan 17, 2023 |
| Acer          | Aspire E1-572P              | Notebook    | [72afaf995e](https://linux-hardware.org/?probe=72afaf995e) | Jan 17, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [23a3b53ebd](https://linux-hardware.org/?probe=23a3b53ebd) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69e87b6d65](https://linux-hardware.org/?probe=69e87b6d65) | Jan 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [57aec688e4](https://linux-hardware.org/?probe=57aec688e4) | Jan 17, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a7970f0c50](https://linux-hardware.org/?probe=a7970f0c50) | Jan 16, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [bf5d9763f7](https://linux-hardware.org/?probe=bf5d9763f7) | Jan 16, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [2de561e7f5](https://linux-hardware.org/?probe=2de561e7f5) | Jan 16, 2023 |
| Toshiba       | STI 007030                  | Desktop     | [c0eb39ae66](https://linux-hardware.org/?probe=c0eb39ae66) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [b53dd87f87](https://linux-hardware.org/?probe=b53dd87f87) | Jan 16, 2023 |
| Unknown       | X133                        | Notebook    | [8d28e5a95e](https://linux-hardware.org/?probe=8d28e5a95e) | Jan 16, 2023 |
| Positivo      | CHT14B                      | Notebook    | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Biostar       | A320MH                      | Desktop     | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| Intel         | JSL MRD                     | Desktop     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| MSI           | 2A9C                        | Desktop     | [7a4c26c267](https://linux-hardware.org/?probe=7a4c26c267) | Jan 15, 2023 |
| Lenovo        | ThinkCentre M58e 7303BZ2    | Desktop     | [af99ffb577](https://linux-hardware.org/?probe=af99ffb577) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [a4ec4fedeb](https://linux-hardware.org/?probe=a4ec4fedeb) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e7b345f3e0](https://linux-hardware.org/?probe=e7b345f3e0) | Jan 15, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [34a7d43639](https://linux-hardware.org/?probe=34a7d43639) | Jan 15, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [029812488b](https://linux-hardware.org/?probe=029812488b) | Jan 15, 2023 |
| ASUSTek       | X45C                        | Notebook    | [677c0ac809](https://linux-hardware.org/?probe=677c0ac809) | Jan 15, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [1dab471d62](https://linux-hardware.org/?probe=1dab471d62) | Jan 15, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [656b21ed21](https://linux-hardware.org/?probe=656b21ed21) | Jan 14, 2023 |
| Biostar       | A320MH                      | Desktop     | [3fb3a04230](https://linux-hardware.org/?probe=3fb3a04230) | Jan 14, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [4eecdbd79d](https://linux-hardware.org/?probe=4eecdbd79d) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | Desktop     | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| Lenovo        | SKYBAY 31900002 WIN 1801... | All in one  | [9fb52e1195](https://linux-hardware.org/?probe=9fb52e1195) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [c0728b5e41](https://linux-hardware.org/?probe=c0728b5e41) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df889b6674](https://linux-hardware.org/?probe=df889b6674) | Jan 14, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [99f51ba1ef](https://linux-hardware.org/?probe=99f51ba1ef) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| Sony          | VPCEH10EB                   | Notebook    | [c9127c6375](https://linux-hardware.org/?probe=c9127c6375) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| Intel         | H55                         | Desktop     | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | Desktop     | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [0c15b80c58](https://linux-hardware.org/?probe=0c15b80c58) | Jan 13, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [57e454fc85](https://linux-hardware.org/?probe=57e454fc85) | Jan 13, 2023 |
| Samsung       | 530XBB                      | Notebook    | [99a0fe43da](https://linux-hardware.org/?probe=99a0fe43da) | Jan 13, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [dc7954e720](https://linux-hardware.org/?probe=dc7954e720) | Jan 13, 2023 |
| Dell          | Latitude 3490               | Notebook    | [facb8b4852](https://linux-hardware.org/?probe=facb8b4852) | Jan 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b2c96e31d9](https://linux-hardware.org/?probe=b2c96e31d9) | Jan 13, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [e2030307c8](https://linux-hardware.org/?probe=e2030307c8) | Jan 13, 2023 |
| Toshiba       | STI NA 1401                 | Notebook    | [8ac3087e41](https://linux-hardware.org/?probe=8ac3087e41) | Jan 13, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [7b8d494edb](https://linux-hardware.org/?probe=7b8d494edb) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| Intel         | H61                         | Desktop     | [fde46524d3](https://linux-hardware.org/?probe=fde46524d3) | Jan 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [07a70b62af](https://linux-hardware.org/?probe=07a70b62af) | Jan 13, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [06851118fe](https://linux-hardware.org/?probe=06851118fe) | Jan 13, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [ebfd029f41](https://linux-hardware.org/?probe=ebfd029f41) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| ASUSTek       | X45C                        | Notebook    | [0cf650bc7b](https://linux-hardware.org/?probe=0cf650bc7b) | Jan 13, 2023 |
| Positivo      | Smash2                      | Notebook    | [d160522fb3](https://linux-hardware.org/?probe=d160522fb3) | Jan 13, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [8e81067cd2](https://linux-hardware.org/?probe=8e81067cd2) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| Pegatron      | IPM31G                      | Desktop     | [04e04dc57b](https://linux-hardware.org/?probe=04e04dc57b) | Jan 12, 2023 |
| HP            | 3047h                       | Desktop     | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| Dell          | G15 5520                    | Notebook    | [1aeaf74f9a](https://linux-hardware.org/?probe=1aeaf74f9a) | Jan 12, 2023 |
| HP            | 3047h                       | Desktop     | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Dell          | 01W9FG A01                  | Server      | [1a2ee8a8d5](https://linux-hardware.org/?probe=1a2ee8a8d5) | Jan 12, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [66d71f6da1](https://linux-hardware.org/?probe=66d71f6da1) | Jan 12, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [e14d589500](https://linux-hardware.org/?probe=e14d589500) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| HP            | Compaq 6530b                | Notebook    | [8ebd66e8e6](https://linux-hardware.org/?probe=8ebd66e8e6) | Jan 12, 2023 |
| Lenovo        | ThinkPad X230 2325AH7       | Notebook    | [c1080083c4](https://linux-hardware.org/?probe=c1080083c4) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [b106ffdf11](https://linux-hardware.org/?probe=b106ffdf11) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [6081f3b43a](https://linux-hardware.org/?probe=6081f3b43a) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e2c3a94f39](https://linux-hardware.org/?probe=e2c3a94f39) | Jan 11, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [acc9ea9c40](https://linux-hardware.org/?probe=acc9ea9c40) | Jan 11, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [28e0a94885](https://linux-hardware.org/?probe=28e0a94885) | Jan 11, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [43c14a1e54](https://linux-hardware.org/?probe=43c14a1e54) | Jan 11, 2023 |
| HP            | Presario C700               | Notebook    | [3674a9a180](https://linux-hardware.org/?probe=3674a9a180) | Jan 11, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0ddeecd2b8](https://linux-hardware.org/?probe=0ddeecd2b8) | Jan 11, 2023 |
| Daten Tecn... | DA3UP DC                    | Mini pc     | [bf33d14564](https://linux-hardware.org/?probe=bf33d14564) | Jan 11, 2023 |
| HP            | 82A2                        | Desktop     | [21321971f7](https://linux-hardware.org/?probe=21321971f7) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c79ad1fc10](https://linux-hardware.org/?probe=c79ad1fc10) | Jan 11, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0851440887](https://linux-hardware.org/?probe=0851440887) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [97f4c3c67a](https://linux-hardware.org/?probe=97f4c3c67a) | Jan 11, 2023 |
| LG Electro... | P420-G.BC44P1               | Notebook    | [7dd7c0d6e8](https://linux-hardware.org/?probe=7dd7c0d6e8) | Jan 11, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [d6a7454695](https://linux-hardware.org/?probe=d6a7454695) | Jan 11, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [77e844abaf](https://linux-hardware.org/?probe=77e844abaf) | Jan 11, 2023 |
| Compaq        | 420                         | Notebook    | [65070f85d5](https://linux-hardware.org/?probe=65070f85d5) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a33cdf7213](https://linux-hardware.org/?probe=a33cdf7213) | Jan 11, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [f4d9052764](https://linux-hardware.org/?probe=f4d9052764) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [83f2f14d5c](https://linux-hardware.org/?probe=83f2f14d5c) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [dc3e0fffe7](https://linux-hardware.org/?probe=dc3e0fffe7) | Jan 10, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0239336b7c](https://linux-hardware.org/?probe=0239336b7c) | Jan 10, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [e5ef8ca744](https://linux-hardware.org/?probe=e5ef8ca744) | Jan 10, 2023 |
| HP            | Mini 110-1000               | Notebook    | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [53d6bec0e8](https://linux-hardware.org/?probe=53d6bec0e8) | Jan 10, 2023 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [26747becd2](https://linux-hardware.org/?probe=26747becd2) | Jan 10, 2023 |
| ASUSTek       | M2A-VM HDMI                 | Desktop     | [02524a1989](https://linux-hardware.org/?probe=02524a1989) | Jan 10, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [f5d1f04d89](https://linux-hardware.org/?probe=f5d1f04d89) | Jan 10, 2023 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [91caa09e7b](https://linux-hardware.org/?probe=91caa09e7b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b89e68d5ab](https://linux-hardware.org/?probe=b89e68d5ab) | Jan 10, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [52164aa403](https://linux-hardware.org/?probe=52164aa403) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [d4ea636610](https://linux-hardware.org/?probe=d4ea636610) | Jan 10, 2023 |
| Avell High... | B.ON                        | Notebook    | [23b5b8565e](https://linux-hardware.org/?probe=23b5b8565e) | Jan 10, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [b572e2679d](https://linux-hardware.org/?probe=b572e2679d) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [a786a0640f](https://linux-hardware.org/?probe=a786a0640f) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [f540a5f964](https://linux-hardware.org/?probe=f540a5f964) | Jan 09, 2023 |
| Intel         | B75                         | Desktop     | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [6c7320f939](https://linux-hardware.org/?probe=6c7320f939) | Jan 09, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [fbb23cdb65](https://linux-hardware.org/?probe=fbb23cdb65) | Jan 09, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [45e73c7052](https://linux-hardware.org/?probe=45e73c7052) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [699eb66c12](https://linux-hardware.org/?probe=699eb66c12) | Jan 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [395c417f92](https://linux-hardware.org/?probe=395c417f92) | Jan 09, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0f91e4728c](https://linux-hardware.org/?probe=0f91e4728c) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ee26fd6a5c](https://linux-hardware.org/?probe=ee26fd6a5c) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [36f64a3242](https://linux-hardware.org/?probe=36f64a3242) | Jan 09, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [54ad46d626](https://linux-hardware.org/?probe=54ad46d626) | Jan 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| HP            | ProBook 6465b               | Notebook    | [336f10e70b](https://linux-hardware.org/?probe=336f10e70b) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [1f38721115](https://linux-hardware.org/?probe=1f38721115) | Jan 08, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [6b8430c407](https://linux-hardware.org/?probe=6b8430c407) | Jan 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [76c7287e2e](https://linux-hardware.org/?probe=76c7287e2e) | Jan 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a43647cad6](https://linux-hardware.org/?probe=a43647cad6) | Jan 08, 2023 |
| Dell          | 0N820C A02                  | Desktop     | [6fa7639fd2](https://linux-hardware.org/?probe=6fa7639fd2) | Jan 07, 2023 |
| Gateway       | NE570                       | Notebook    | [3f65734a89](https://linux-hardware.org/?probe=3f65734a89) | Jan 07, 2023 |
| Standard      | MB40II                      | Notebook    | [4abb5712cc](https://linux-hardware.org/?probe=4abb5712cc) | Jan 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f33ea77f0b](https://linux-hardware.org/?probe=f33ea77f0b) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e9dadf5a23](https://linux-hardware.org/?probe=e9dadf5a23) | Jan 07, 2023 |
| ASUSTek       | X45C                        | Notebook    | [6366228fb2](https://linux-hardware.org/?probe=6366228fb2) | Jan 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [173b427c35](https://linux-hardware.org/?probe=173b427c35) | Jan 07, 2023 |
| Notebook      | P17SM                       | Notebook    | [1822a60f02](https://linux-hardware.org/?probe=1822a60f02) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [843a02520e](https://linux-hardware.org/?probe=843a02520e) | Jan 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dcca84c5eb](https://linux-hardware.org/?probe=dcca84c5eb) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [313f5897bd](https://linux-hardware.org/?probe=313f5897bd) | Jan 07, 2023 |
| Dell          | G15 5510                    | Notebook    | [210d9c1c73](https://linux-hardware.org/?probe=210d9c1c73) | Jan 07, 2023 |
| Dell          | G15 5510                    | Notebook    | [7009360ecf](https://linux-hardware.org/?probe=7009360ecf) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7f2254139c](https://linux-hardware.org/?probe=7f2254139c) | Jan 07, 2023 |
| LG Electro... | U460-G.BG31P1               | Notebook    | [dea7419ce8](https://linux-hardware.org/?probe=dea7419ce8) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [79c60c460a](https://linux-hardware.org/?probe=79c60c460a) | Jan 07, 2023 |
| LG Electro... | A530-U.BE54P1               | Notebook    | [39c702d864](https://linux-hardware.org/?probe=39c702d864) | Jan 06, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [511e5df827](https://linux-hardware.org/?probe=511e5df827) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1e24b872bd](https://linux-hardware.org/?probe=1e24b872bd) | Jan 06, 2023 |
| Biostar       | G31-M7 TE                   | Desktop     | [16dd478d1e](https://linux-hardware.org/?probe=16dd478d1e) | Jan 06, 2023 |
| LG Electro... | 24V570 FAB1                 | All in one  | [994158f4ce](https://linux-hardware.org/?probe=994158f4ce) | Jan 06, 2023 |
| Dell          | G15 5515                    | Notebook    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [999663daee](https://linux-hardware.org/?probe=999663daee) | Jan 06, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [122079f900](https://linux-hardware.org/?probe=122079f900) | Jan 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [758acf54ff](https://linux-hardware.org/?probe=758acf54ff) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caa3df2f1c](https://linux-hardware.org/?probe=caa3df2f1c) | Jan 05, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [c1375455dc](https://linux-hardware.org/?probe=c1375455dc) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [28af5637ef](https://linux-hardware.org/?probe=28af5637ef) | Jan 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1d25f1df44](https://linux-hardware.org/?probe=1d25f1df44) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [4605f322cb](https://linux-hardware.org/?probe=4605f322cb) | Jan 05, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [22b6517ed2](https://linux-hardware.org/?probe=22b6517ed2) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | G15 5510                    | Notebook    | [e0282d77f8](https://linux-hardware.org/?probe=e0282d77f8) | Jan 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a84ac79f2b](https://linux-hardware.org/?probe=a84ac79f2b) | Jan 05, 2023 |
| Avell High... | B.ON                        | Notebook    | [99a8cc2270](https://linux-hardware.org/?probe=99a8cc2270) | Jan 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [39f45e87d1](https://linux-hardware.org/?probe=39f45e87d1) | Jan 04, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [2f4bb5b17d](https://linux-hardware.org/?probe=2f4bb5b17d) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [5b13eb0dad](https://linux-hardware.org/?probe=5b13eb0dad) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [26165b2acb](https://linux-hardware.org/?probe=26165b2acb) | Jan 04, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [1fd86a44c5](https://linux-hardware.org/?probe=1fd86a44c5) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [1e69c79d74](https://linux-hardware.org/?probe=1e69c79d74) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Sony          | VJF153                      | Notebook    | [f3643923cc](https://linux-hardware.org/?probe=f3643923cc) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| HP            | G42                         | Notebook    | [a1e6624ba4](https://linux-hardware.org/?probe=a1e6624ba4) | Jan 03, 2023 |
| Dell          | 0P99M4 A01                  | Desktop     | [0b6a911c16](https://linux-hardware.org/?probe=0b6a911c16) | Jan 03, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a502c849f](https://linux-hardware.org/?probe=8a502c849f) | Jan 03, 2023 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [31d3e37e7f](https://linux-hardware.org/?probe=31d3e37e7f) | Jan 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [37cbf7c1a4](https://linux-hardware.org/?probe=37cbf7c1a4) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | Desktop     | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| JGINYUE       | B85I PLUS V2.0              | Desktop     | [28a07cbbe1](https://linux-hardware.org/?probe=28a07cbbe1) | Jan 02, 2023 |
| JGINYUE       | B85I PLUS V2.0              | Desktop     | [3cde9738e7](https://linux-hardware.org/?probe=3cde9738e7) | Jan 02, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [a795f33f7a](https://linux-hardware.org/?probe=a795f33f7a) | Jan 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4b4ca0ec08](https://linux-hardware.org/?probe=4b4ca0ec08) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Positivo      | H14CU01                     | Notebook    | [f668eee758](https://linux-hardware.org/?probe=f668eee758) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [073d682146](https://linux-hardware.org/?probe=073d682146) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [4d7f89dc6d](https://linux-hardware.org/?probe=4d7f89dc6d) | Dec 31, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [97da60caa9](https://linux-hardware.org/?probe=97da60caa9) | Dec 31, 2022 |
| HP            | Folio 13                    | Notebook    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | Notebook    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| Dell          | 0VR8V9 A01                  | Desktop     | [0e7d4ac326](https://linux-hardware.org/?probe=0e7d4ac326) | Dec 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [18827f3f77](https://linux-hardware.org/?probe=18827f3f77) | Dec 31, 2022 |
| ASRock        | B360M Performance           | Desktop     | [679d25f9be](https://linux-hardware.org/?probe=679d25f9be) | Dec 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3710331d81](https://linux-hardware.org/?probe=3710331d81) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Acer          | Predator G3-572             | Notebook    | [ab03199a79](https://linux-hardware.org/?probe=ab03199a79) | Dec 30, 2022 |
| Compaq        | CQ-27                       | Notebook    | [fc5b98e1db](https://linux-hardware.org/?probe=fc5b98e1db) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a295f18c9f](https://linux-hardware.org/?probe=a295f18c9f) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| Dell          | G5 5590                     | Notebook    | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| Acer          | Predator G3-572             | Notebook    | [f99480426f](https://linux-hardware.org/?probe=f99480426f) | Dec 29, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [35f6da18cc](https://linux-hardware.org/?probe=35f6da18cc) | Dec 29, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [754ba4696d](https://linux-hardware.org/?probe=754ba4696d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [296961ae2d](https://linux-hardware.org/?probe=296961ae2d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4239e2fa3c](https://linux-hardware.org/?probe=4239e2fa3c) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | G5 5590                     | Notebook    | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [83608f4248](https://linux-hardware.org/?probe=83608f4248) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ec0ad4d293](https://linux-hardware.org/?probe=ec0ad4d293) | Dec 28, 2022 |
| Lenovo        | 100-14IBY 80R7              | Notebook    | [92b2614ac2](https://linux-hardware.org/?probe=92b2614ac2) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| Samsung       | 550XDA                      | Notebook    | [6d744c7602](https://linux-hardware.org/?probe=6d744c7602) | Dec 28, 2022 |
| Samsung       | 550XDA                      | Notebook    | [b463fa7a54](https://linux-hardware.org/?probe=b463fa7a54) | Dec 28, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5383fb814b](https://linux-hardware.org/?probe=5383fb814b) | Dec 28, 2022 |
| Positivo      | Hendrix                     | Notebook    | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [15e48d4c24](https://linux-hardware.org/?probe=15e48d4c24) | Dec 27, 2022 |
| Itautec       | ST 4265                     | Desktop     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [22540f4247](https://linux-hardware.org/?probe=22540f4247) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [b47449f70f](https://linux-hardware.org/?probe=b47449f70f) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | Desktop     | [8658fa0fa3](https://linux-hardware.org/?probe=8658fa0fa3) | Dec 27, 2022 |
| ASRock        | H61M-HG4                    | Desktop     | [cf7ba71c5e](https://linux-hardware.org/?probe=cf7ba71c5e) | Dec 27, 2022 |
| Unknown       | Unknown                     | Phone       | [1bf74daa90](https://linux-hardware.org/?probe=1bf74daa90) | Dec 27, 2022 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | Desktop     | [868a87a1f8](https://linux-hardware.org/?probe=868a87a1f8) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [d32b30987a](https://linux-hardware.org/?probe=d32b30987a) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [669e014ee6](https://linux-hardware.org/?probe=669e014ee6) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| Itautec       | ST 4265                     | Desktop     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [a1638729b2](https://linux-hardware.org/?probe=a1638729b2) | Dec 26, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [97677e7c79](https://linux-hardware.org/?probe=97677e7c79) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [67fee9ab39](https://linux-hardware.org/?probe=67fee9ab39) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | Notebook    | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| HP            | ProBook 6465b               | Notebook    | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| LG Electro... | 22V270 2                    | All in one  | [04d33628a1](https://linux-hardware.org/?probe=04d33628a1) | Dec 25, 2022 |
| LG Electro... | 22V270 2                    | All in one  | [8408ee3692](https://linux-hardware.org/?probe=8408ee3692) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e12a45a65f](https://linux-hardware.org/?probe=e12a45a65f) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [4f28247dcb](https://linux-hardware.org/?probe=4f28247dcb) | Dec 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5977afc830](https://linux-hardware.org/?probe=5977afc830) | Dec 25, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4a77067c41](https://linux-hardware.org/?probe=4a77067c41) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [ccd5d4bac3](https://linux-hardware.org/?probe=ccd5d4bac3) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d66db29328](https://linux-hardware.org/?probe=d66db29328) | Dec 25, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a5d26c4498](https://linux-hardware.org/?probe=a5d26c4498) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c95a4418f0](https://linux-hardware.org/?probe=c95a4418f0) | Dec 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [0d59e2b098](https://linux-hardware.org/?probe=0d59e2b098) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [28b89e2321](https://linux-hardware.org/?probe=28b89e2321) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| Dell          | XPS L322X                   | Notebook    | [c127721464](https://linux-hardware.org/?probe=c127721464) | Dec 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [27612d2f72](https://linux-hardware.org/?probe=27612d2f72) | Dec 24, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b0a9f1ed91](https://linux-hardware.org/?probe=b0a9f1ed91) | Dec 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [39f35288d4](https://linux-hardware.org/?probe=39f35288d4) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [a38f241e2e](https://linux-hardware.org/?probe=a38f241e2e) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| Positivo      | Mobile                      | Notebook    | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [2979740651](https://linux-hardware.org/?probe=2979740651) | Dec 24, 2022 |
| Avell High... | B.ON                        | Notebook    | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Positivo      | H14BT58                     | Notebook    | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8f4eea6be8](https://linux-hardware.org/?probe=8f4eea6be8) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Samsung       | 730QED                      | Convertible | [0c36621efa](https://linux-hardware.org/?probe=0c36621efa) | Dec 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d5625e9592](https://linux-hardware.org/?probe=d5625e9592) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | Notebook    | [22eafd12e4](https://linux-hardware.org/?probe=22eafd12e4) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | Notebook    | [f250052dff](https://linux-hardware.org/?probe=f250052dff) | Dec 23, 2022 |
| Positivo      | C4128E-S                    | Notebook    | [2fce43e57f](https://linux-hardware.org/?probe=2fce43e57f) | Dec 23, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [7efb2defb9](https://linux-hardware.org/?probe=7efb2defb9) | Dec 23, 2022 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [a847e86a17](https://linux-hardware.org/?probe=a847e86a17) | Dec 22, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [5307c53c91](https://linux-hardware.org/?probe=5307c53c91) | Dec 22, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [2d85a576e1](https://linux-hardware.org/?probe=2d85a576e1) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3a87279be6](https://linux-hardware.org/?probe=3a87279be6) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [37f100cf13](https://linux-hardware.org/?probe=37f100cf13) | Dec 22, 2022 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [a582c04486](https://linux-hardware.org/?probe=a582c04486) | Dec 22, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [4e4cf63a0a](https://linux-hardware.org/?probe=4e4cf63a0a) | Dec 22, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [08539171a8](https://linux-hardware.org/?probe=08539171a8) | Dec 22, 2022 |
| Dell          | System XPS L502X            | Notebook    | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| Dell          | G3 3590                     | Notebook    | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| PERTOSA       | IPMSBA                      | Desktop     | [8cd4fff2ce](https://linux-hardware.org/?probe=8cd4fff2ce) | Dec 22, 2022 |
| Positivo      | S14SL01                     | Notebook    | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | Notebook    | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | Notebook    | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | Notebook    | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| LG Electro... | 22V270 2                    | All in one  | [f743a68647](https://linux-hardware.org/?probe=f743a68647) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Positivo      | C14CR21                     | Notebook    | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [428c861575](https://linux-hardware.org/?probe=428c861575) | Dec 21, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [20c96ed6dd](https://linux-hardware.org/?probe=20c96ed6dd) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Dell          | G3 3590                     | Notebook    | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Intel         | B75                         | Desktop     | [368e71afd7](https://linux-hardware.org/?probe=368e71afd7) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | Desktop     | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Dell          | Latitude 3420               | Notebook    | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| Intel         | H81                         | Desktop     | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4c6ab7c16e](https://linux-hardware.org/?probe=4c6ab7c16e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Positivo      | Master N8340                | Notebook    | [643f2e00e0](https://linux-hardware.org/?probe=643f2e00e0) | Dec 20, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [e1d9b06871](https://linux-hardware.org/?probe=e1d9b06871) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Acer          | Extensa 5230                | Notebook    | [0cfe897a2b](https://linux-hardware.org/?probe=0cfe897a2b) | Dec 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [68731f4d29](https://linux-hardware.org/?probe=68731f4d29) | Dec 20, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [79cf1b618f](https://linux-hardware.org/?probe=79cf1b618f) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Multilaser    | UB23X LINUX                 | Notebook    | [9f7503d89d](https://linux-hardware.org/?probe=9f7503d89d) | Dec 20, 2022 |
| ECS           | G31T-M7                     | Desktop     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [751834957d](https://linux-hardware.org/?probe=751834957d) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Multilaser    | UB23X LINUX                 | Notebook    | [502d9cd6ce](https://linux-hardware.org/?probe=502d9cd6ce) | Dec 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [533bf9eafc](https://linux-hardware.org/?probe=533bf9eafc) | Dec 19, 2022 |
| Sony          | VPCEA23FB                   | Notebook    | [a374bedbed](https://linux-hardware.org/?probe=a374bedbed) | Dec 19, 2022 |
| Acer          | Extensa 5230                | Notebook    | [dfe70c9fdc](https://linux-hardware.org/?probe=dfe70c9fdc) | Dec 19, 2022 |
| HP            | ProBook 4530s               | Notebook    | [2c6a27a08d](https://linux-hardware.org/?probe=2c6a27a08d) | Dec 19, 2022 |
| HP            | ProBook 4530s               | Notebook    | [19892439d6](https://linux-hardware.org/?probe=19892439d6) | Dec 19, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [5254697dbb](https://linux-hardware.org/?probe=5254697dbb) | Dec 19, 2022 |
| Alienware     | m15 R7                      | Notebook    | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| ASUSTek       | X451CAP                     | Notebook    | [358fa50e0c](https://linux-hardware.org/?probe=358fa50e0c) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6870f7c47f](https://linux-hardware.org/?probe=6870f7c47f) | Dec 18, 2022 |
| Intel         | HM570                       | Desktop     | [627a39bc3f](https://linux-hardware.org/?probe=627a39bc3f) | Dec 18, 2022 |
| Intel         | HM570                       | Desktop     | [303e68f585](https://linux-hardware.org/?probe=303e68f585) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7b1655d054](https://linux-hardware.org/?probe=7b1655d054) | Dec 18, 2022 |
| Dell          | 0UY894 A02                  | Desktop     | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [07ae580adc](https://linux-hardware.org/?probe=07ae580adc) | Dec 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a80a6922d4](https://linux-hardware.org/?probe=a80a6922d4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | Notebook    | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [150f4e3dbc](https://linux-hardware.org/?probe=150f4e3dbc) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5c0150b6ae](https://linux-hardware.org/?probe=5c0150b6ae) | Dec 17, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [dcf4e8200b](https://linux-hardware.org/?probe=dcf4e8200b) | Dec 17, 2022 |
| Sony          | VPCCW21FX                   | Notebook    | [9d82e3655b](https://linux-hardware.org/?probe=9d82e3655b) | Dec 17, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [a61b5c0129](https://linux-hardware.org/?probe=a61b5c0129) | Dec 17, 2022 |
| Samsung       | 730QED                      | Convertible | [8ac065bd83](https://linux-hardware.org/?probe=8ac065bd83) | Dec 17, 2022 |
| Avell High... | B.ON                        | Notebook    | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [96ae6bc093](https://linux-hardware.org/?probe=96ae6bc093) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [9dede41c5d](https://linux-hardware.org/?probe=9dede41c5d) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [a30cdfc558](https://linux-hardware.org/?probe=a30cdfc558) | Dec 16, 2022 |
| Digibras      | US41II1                     | Notebook    | [6b1d584ff8](https://linux-hardware.org/?probe=6b1d584ff8) | Dec 16, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [6da143680b](https://linux-hardware.org/?probe=6da143680b) | Dec 16, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| Intel         | H55                         | Desktop     | [c034f3b3db](https://linux-hardware.org/?probe=c034f3b3db) | Dec 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [43e6598fd7](https://linux-hardware.org/?probe=43e6598fd7) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4676cf2979](https://linux-hardware.org/?probe=4676cf2979) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1509      | 12.05%  |
| Ubuntu 18.04       | 1029      | 8.21%   |
| Ubuntu 22.04       | 367       | 2.93%   |
| OpenMandriva 4.2   | 337       | 2.69%   |
| Pop!_OS 20.04      | 318       | 2.54%   |
| Linux Mint 20      | 314       | 2.51%   |
| Linux Mint 19.3    | 284       | 2.27%   |
| OpenMandriva 4.3   | 280       | 2.24%   |
| Linux Mint 19.1    | 235       | 1.88%   |
| Ubuntu 19.04       | 218       | 1.74%   |
| KDE neon 20.04     | 213       | 1.7%    |
| Linux Mint 20.3    | 208       | 1.66%   |
| Linux Mint 20.1    | 205       | 1.64%   |
| Arch               | 189       | 1.51%   |
| Linux Mint 20.2    | 181       | 1.44%   |
| Manjaro            | 180       | 1.44%   |
| Zorin 16           | 176       | 1.4%    |
| Ubuntu 19.10       | 173       | 1.38%   |
| Pop!_OS 22.04      | 161       | 1.29%   |
| Debian 11          | 161       | 1.29%   |
| Debian 10          | 155       | 1.24%   |
| Zorin 15           | 149       | 1.19%   |
| Pop!_OS 21.04      | 127       | 1.01%   |
| Pop!_OS 20.10      | 127       | 1.01%   |
| Arch Rolling       | 127       | 1.01%   |
| Fedora 34          | 120       | 0.96%   |
| Fedora 36          | 117       | 0.93%   |
| Xubuntu 20.04      | 115       | 0.92%   |
| Fedora 32          | 111       | 0.89%   |
| Pop!_OS 21.10      | 110       | 0.88%   |
| Fedora 35          | 110       | 0.88%   |
| OpenMandriva 23.01 | 105       | 0.84%   |
| Fedora 33          | 105       | 0.84%   |
| Linux Mint 19.2    | 103       | 0.82%   |
| Kubuntu 20.04      | 101       | 0.81%   |
| Ubuntu MATE 20.04  | 99        | 0.79%   |
| Ubuntu 20.10       | 98        | 0.78%   |
| Linux Mint 21      | 98        | 0.78%   |
| Fedora 37          | 84        | 0.67%   |
| Ubuntu 18.10       | 83        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3600      | 30.06%  |
| Linux Mint    | 1650      | 13.78%  |
| Endless       | 1019      | 8.51%   |
| Pop!_OS       | 809       | 6.76%   |
| OpenMandriva  | 780       | 6.51%   |
| Fedora        | 680       | 5.68%   |
| Debian        | 415       | 3.47%   |
| Manjaro       | 357       | 2.98%   |
| Zorin         | 334       | 2.79%   |
| Arch          | 303       | 2.53%   |
| KDE neon      | 261       | 2.18%   |
| Xubuntu       | 221       | 1.85%   |
| Kubuntu       | 201       | 1.68%   |
| Ubuntu MATE   | 133       | 1.11%   |
| ROSA          | 125       | 1.04%   |
| openSUSE      | 109       | 0.91%   |
| Lubuntu       | 101       | 0.84%   |
| Elementary    | 93        | 0.78%   |
| Ubuntu Unity  | 83        | 0.69%   |
| LMDE          | 64        | 0.53%   |
| Kali          | 56        | 0.47%   |
| Deepin        | 45        | 0.38%   |
| ArcoLinux     | 41        | 0.34%   |
| Ubuntu Budgie | 40        | 0.33%   |
| LinuxFX       | 40        | 0.33%   |
| Clear Linux   | 35        | 0.29%   |
| CentOS        | 30        | 0.25%   |
| BlackPanther  | 30        | 0.25%   |
| BigLinux      | 26        | 0.22%   |
| EndeavourOS   | 21        | 0.18%   |
| Gentoo        | 17        | 0.14%   |
| Parrot        | 16        | 0.13%   |
| Peppermint    | 14        | 0.12%   |
| MX            | 14        | 0.12%   |
| Garuda Linux  | 14        | 0.12%   |
| UbuntuDDE     | 12        | 0.1%    |
| Linux Lite    | 12        | 0.1%    |
| Solus         | 11        | 0.09%   |
| Reborn OS     | 10        | 0.08%   |
| Slackware     | 9         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 5.26%   |
| 5.10.14-desktop-1omv4002 | 326       | 2.42%   |
| 5.8.0-14-generic         | 312       | 2.31%   |
| 5.16.7-desktop-1omv4003  | 266       | 1.97%   |
| 4.15.0-46-generic        | 156       | 1.16%   |
| 5.3.0-28-generic         | 146       | 1.08%   |
| 5.4.0-48-generic         | 138       | 1.02%   |
| 5.4.0-19-generic         | 138       | 1.02%   |
| 5.4.0-7634-generic       | 123       | 0.91%   |
| 5.4.0-40-generic         | 111       | 0.82%   |
| 5.4.0-58-generic         | 108       | 0.8%    |
| 5.4.0-26-generic         | 105       | 0.78%   |
| 5.11.0-35-generic        | 105       | 0.78%   |
| 5.4.0-52-generic         | 101       | 0.75%   |
| 6.1.1-desktop-1omv2290   | 97        | 0.72%   |
| 4.18.0-15-generic        | 97        | 0.72%   |
| 5.4.0-47-generic         | 96        | 0.71%   |
| 5.15.0-56-generic        | 95        | 0.7%    |
| 5.3.0-40-generic         | 89        | 0.66%   |
| 5.11.0-7620-generic      | 78        | 0.58%   |
| 5.0.0-32-generic         | 78        | 0.58%   |
| 5.3.0-46-generic         | 77        | 0.57%   |
| 5.0.0-37-generic         | 72        | 0.53%   |
| 4.15.0-20-generic        | 72        | 0.53%   |
| 5.4.0-70-generic         | 71        | 0.53%   |
| 5.4.0-72-generic         | 68        | 0.5%    |
| 5.15.0-46-generic        | 66        | 0.49%   |
| 5.4.0-91-generic         | 65        | 0.48%   |
| 5.15.0-52-generic        | 65        | 0.48%   |
| 5.4.0-80-generic         | 63        | 0.47%   |
| 5.3.0-23-generic         | 63        | 0.47%   |
| 5.4.0-29-generic         | 62        | 0.46%   |
| 4.18.0-16-generic        | 62        | 0.46%   |
| 5.4.0-65-generic         | 61        | 0.45%   |
| 5.4.0-37-generic         | 61        | 0.45%   |
| 5.4.0-39-generic         | 60        | 0.44%   |
| 5.0.0-25-generic         | 60        | 0.44%   |
| 5.4.0-74-generic         | 59        | 0.44%   |
| 5.8.0-7630-generic       | 58        | 0.43%   |
| 5.3.0-19-generic         | 58        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3016      | 23.62%  |
| 4.15.0  | 941       | 7.37%   |
| 5.8.0   | 894       | 7%      |
| 5.3.0   | 799       | 6.26%   |
| 5.15.0  | 705       | 5.52%   |
| 5.11.0  | 696       | 5.45%   |
| 5.0.0   | 563       | 4.41%   |
| 5.13.0  | 460       | 3.6%    |
| 4.18.0  | 416       | 3.26%   |
| 5.10.14 | 328       | 2.57%   |
| 5.16.7  | 266       | 2.08%   |
| 5.10.0  | 216       | 1.69%   |
| 4.19.0  | 184       | 1.44%   |
| 5.19.0  | 118       | 0.92%   |
| 6.1.1   | 107       | 0.84%   |
| 5.17.5  | 59        | 0.46%   |
| 5.7.9   | 47        | 0.37%   |
| 4.4.0   | 45        | 0.35%   |
| 6.0.12  | 40        | 0.31%   |
| 5.16.11 | 40        | 0.31%   |
| 5.14.0  | 39        | 0.31%   |
| 4.9.0   | 38        | 0.3%    |
| 5.15.5  | 31        | 0.24%   |
| 5.7.0   | 30        | 0.23%   |
| 5.15.15 | 30        | 0.23%   |
| 5.9.16  | 28        | 0.22%   |
| 5.6.19  | 27        | 0.21%   |
| 4.9.60  | 27        | 0.21%   |
| 5.3.18  | 25        | 0.2%    |
| 4.18.16 | 25        | 0.2%    |
| 5.13.19 | 24        | 0.19%   |
| 5.11.12 | 24        | 0.19%   |
| 6.0.0   | 23        | 0.18%   |
| 5.18.12 | 23        | 0.18%   |
| 5.7.10  | 22        | 0.17%   |
| 6.0.6   | 21        | 0.16%   |
| 5.16.15 | 21        | 0.16%   |
| 5.18.10 | 20        | 0.16%   |
| 5.16.13 | 20        | 0.16%   |
| 5.15.8  | 20        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3141      | 24.9%   |
| 5.8     | 1007      | 7.98%   |
| 5.15    | 965       | 7.65%   |
| 4.15    | 941       | 7.46%   |
| 5.3     | 870       | 6.9%    |
| 5.11    | 792       | 6.28%   |
| 5.10    | 735       | 5.83%   |
| 5.0     | 605       | 4.8%    |
| 5.13    | 552       | 4.38%   |
| 5.16    | 450       | 3.57%   |
| 4.18    | 449       | 3.56%   |
| 4.19    | 220       | 1.74%   |
| 5.19    | 214       | 1.7%    |
| 6.1     | 193       | 1.53%   |
| 6.0     | 180       | 1.43%   |
| 5.7     | 172       | 1.36%   |
| 5.17    | 156       | 1.24%   |
| 5.18    | 136       | 1.08%   |
| 5.14    | 131       | 1.04%   |
| 5.6     | 126       | 1%      |
| 5.12    | 113       | 0.9%    |
| 5.9     | 110       | 0.87%   |
| 4.9     | 104       | 0.82%   |
| 4.4     | 51        | 0.4%    |
| 5.5     | 50        | 0.4%    |
| 5.1     | 39        | 0.31%   |
| 5.2     | 29        | 0.23%   |
| 3.10    | 15        | 0.12%   |
| 4.13    | 13        | 0.1%    |
| 4.1     | 12        | 0.1%    |
| 4.20    | 10        | 0.08%   |
| 4.10    | 8         | 0.06%   |
| 4.12    | 6         | 0.05%   |
| 6.2     | 5         | 0.04%   |
| 4.14    | 5         | 0.04%   |
| 4.8     | 3         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 11140     | 97.15%  |
| i686    | 298       | 2.6%    |
| aarch64 | 18        | 0.16%   |
| armv7l  | 11        | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 5461      | 45.58%  |
| Unknown                  | 1807      | 15.08%  |
| KDE5                     | 1473      | 12.29%  |
| X-Cinnamon               | 975       | 8.14%   |
| XFCE                     | 796       | 6.64%   |
| MATE                     | 345       | 2.88%   |
| KDE                      | 311       | 2.6%    |
| Cinnamon                 | 221       | 1.84%   |
| LXQt                     | 97        | 0.81%   |
| Unity                    | 85        | 0.71%   |
| Pantheon                 | 81        | 0.68%   |
| KDE4                     | 66        | 0.55%   |
| Budgie                   | 58        | 0.48%   |
| Deepin                   | 57        | 0.48%   |
| LXDE                     | 51        | 0.43%   |
| i3                       | 32        | 0.27%   |
| GNOME Flashback          | 16        | 0.13%   |
| GNOME Classic            | 13        | 0.11%   |
| awesome                  | 10        | 0.08%   |
| sway                     | 5         | 0.04%   |
| Enlightenment            | 5         | 0.04%   |
| Openbox                  | 4         | 0.03%   |
| bspwm                    | 3         | 0.03%   |
| qtile                    | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| icewm                    | 1         | 0.01%   |
| GNUstep                  | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9635      | 82.05%  |
| Wayland | 1142      | 9.72%   |
| Unknown | 886       | 7.54%   |
| Tty     | 78        | 0.66%   |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7470      | 63.01%  |
| SDDM    | 1300      | 10.96%  |
| GDM     | 1203      | 10.15%  |
| GDM3    | 670       | 5.65%   |
| LightDM | 589       | 4.97%   |
| TDM     | 538       | 4.54%   |
| KDM     | 66        | 0.56%   |
| XDM     | 9         | 0.08%   |
| SLiM    | 5         | 0.04%   |
| LXDM    | 3         | 0.03%   |
| MDM     | 2         | 0.02%   |
| SLIMSKI | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 7701      | 65.67%  |
| en_US       | 2011      | 17.15%  |
| Unknown     | 1697      | 14.47%  |
| C           | 167       | 1.42%   |
| en_GB       | 47        | 0.4%    |
| pt_PT       | 44        | 0.38%   |
| es_ES       | 17        | 0.14%   |
| en_CA       | 7         | 0.06%   |
| fr_FR       | 6         | 0.05%   |
| de_DE       | 5         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| pt_BRutf8   | 2         | 0.02%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| C.UTF8      | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6683      | 56.95%  |
| EFI  | 5051      | 43.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 9107      | 77.64%  |
| Overlay | 936       | 7.98%   |
| Btrfs   | 778       | 6.63%   |
| Unknown | 703       | 5.99%   |
| Xfs     | 85        | 0.72%   |
| Zfs     | 42        | 0.36%   |
| Tmpfs   | 24        | 0.2%    |
| Ext3    | 21        | 0.18%   |
| Ext2    | 17        | 0.14%   |
| F2fs    | 13        | 0.11%   |
| Aufs    | 4         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7831      | 66.67%  |
| GPT     | 2612      | 22.24%  |
| MBR     | 1303      | 11.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10278     | 88.34%  |
| Yes       | 1356      | 11.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8628      | 74.06%  |
| Yes       | 3022      | 25.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1850      | 16.14%  |
| ASUSTek Computer        | 1533      | 13.38%  |
| Acer                    | 1363      | 11.89%  |
| Lenovo                  | 974       | 8.5%    |
| Gigabyte Technology     | 748       | 6.53%   |
| Positivo                | 659       | 5.75%   |
| Hewlett-Packard         | 613       | 5.35%   |
| Samsung Electronics     | 588       | 5.13%   |
| Intel                   | 412       | 3.6%    |
| ASRock                  | 379       | 3.31%   |
| Unknown                 | 219       | 1.91%   |
| MSI                     | 200       | 1.75%   |
| Sony                    | 151       | 1.32%   |
| LG Electronics          | 124       | 1.08%   |
| Apple                   | 116       | 1.01%   |
| PCWare                  | 108       | 0.94%   |
| Semp Toshiba            | 105       | 0.92%   |
| Itautec                 | 105       | 0.92%   |
| Biostar                 | 84        | 0.73%   |
| Avell High Performance  | 72        | 0.63%   |
| Pegatron                | 70        | 0.61%   |
| Digibras                | 67        | 0.58%   |
| ECS                     | 61        | 0.53%   |
| Philco                  | 49        | 0.43%   |
| OEM                     | 48        | 0.42%   |
| Multilaser              | 47        | 0.41%   |
| Compaq                  | 40        | 0.35%   |
| Positivo Bahia - VAIO   | 35        | 0.31%   |
| Toshiba                 | 34        | 0.3%    |
| Megaware                | 30        | 0.26%   |
| Huanan                  | 29        | 0.25%   |
| Foxconn                 | 27        | 0.24%   |
| Notebook                | 25        | 0.22%   |
| Clevo                   | 22        | 0.19%   |
| Login Informatica       | 21        | 0.18%   |
| Gateway                 | 21        | 0.18%   |
| Compal                  | 19        | 0.17%   |
| Raspberry Pi Foundation | 17        | 0.15%   |
| Supermicro              | 15        | 0.13%   |
| Google                  | 15        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 276       | 2.41%   |
| ASUS All Series                             | 140       | 1.22%   |
| Acer Nitro AN515-54                         | 135       | 1.18%   |
| Positivo Mobile                             | 119       | 1.04%   |
| Acer Nitro AN515-44                         | 79        | 0.69%   |
| Intel H61                                   | 77        | 0.67%   |
| Acer Aspire A315-53                         | 68        | 0.59%   |
| Samsung 340XAA/350XAA/550XAA                | 67        | 0.58%   |
| Dell Inspiron 5566                          | 61        | 0.53%   |
| Lenovo IdeaPad S145-15API 81V7              | 60        | 0.52%   |
| ASUS PRIME B450M-GAMING/BR                  | 59        | 0.51%   |
| Dell Inspiron 3583                          | 58        | 0.51%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 54        | 0.47%   |
| Acer Aspire A315-34                         | 53        | 0.46%   |
| Dell Inspiron 15-3567                       | 52        | 0.45%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 51        | 0.45%   |
| Acer Nitro AN517-51                         | 51        | 0.45%   |
| ASRock A320M-HD                             | 50        | 0.44%   |
| ASUS PRIME A320M-K/BR                       | 48        | 0.42%   |
| Acer Aspire A515-51                         | 48        | 0.42%   |
| Acer Nitro AN515-43                         | 45        | 0.39%   |
| Intel H55                                   | 44        | 0.38%   |
| ASUS M5A78L-M LX/BR                         | 44        | 0.38%   |
| Semp Toshiba STI                            | 43        | 0.38%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 42        | 0.37%   |
| HP G42                                      | 40        | 0.35%   |
| Samsung 300E5M/300E5L                       | 39        | 0.34%   |
| Dell Inspiron N4050                         | 38        | 0.33%   |
| Positivo S14CT01                            | 37        | 0.32%   |
| Itautec Infoway                             | 37        | 0.32%   |
| Gigabyte H61M-S1                            | 37        | 0.32%   |
| Dell Inspiron 3442                          | 37        | 0.32%   |
| Dell Inspiron 3421                          | 37        | 0.32%   |
| Acer Nitro AN515-52                         | 36        | 0.31%   |
| Gigabyte B75M-D3H                           | 33        | 0.29%   |
| Dell Inspiron 7520                          | 33        | 0.29%   |
| ASRock B450M Steel Legend                   | 33        | 0.29%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 32        | 0.28%   |
| Samsung 550XDA                              | 32        | 0.28%   |
| Gigabyte A320M-S2H                          | 32        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1065      | 9.29%   |
| Acer Aspire        | 883       | 7.71%   |
| Lenovo IdeaPad     | 478       | 4.17%   |
| Acer Nitro         | 382       | 3.33%   |
| Unknown            | 276       | 2.41%   |
| Dell Vostro        | 227       | 1.98%   |
| ASUS PRIME         | 222       | 1.94%   |
| Lenovo ThinkPad    | 194       | 1.69%   |
| HP Pavilion        | 186       | 1.62%   |
| Dell Latitude      | 167       | 1.46%   |
| Dell OptiPlex      | 152       | 1.33%   |
| ASUS All           | 140       | 1.22%   |
| Positivo Mobile    | 119       | 1.04%   |
| ASUS M5A78L-M      | 114       | 0.99%   |
| ASUS VivoBook      | 108       | 0.94%   |
| ASUS TUF           | 102       | 0.89%   |
| Itautec Infoway    | 100       | 0.87%   |
| HP Compaq          | 96        | 0.84%   |
| ASUS P8H61-M       | 82        | 0.72%   |
| Intel H61          | 79        | 0.69%   |
| Samsung 340XAA     | 67        | 0.58%   |
| Lenovo ThinkCentre | 58        | 0.51%   |
| Dell G3            | 53        | 0.46%   |
| ASRock A320M-HD    | 51        | 0.45%   |
| Semp Toshiba STI   | 50        | 0.44%   |
| ASUS ROG           | 50        | 0.44%   |
| Dell XPS           | 49        | 0.43%   |
| HP ProBook         | 47        | 0.41%   |
| Samsung RV411      | 45        | 0.39%   |
| Intel H55          | 44        | 0.38%   |
| HP G42             | 40        | 0.35%   |
| Samsung 300E5M     | 39        | 0.34%   |
| Positivo S14CT01   | 37        | 0.32%   |
| Gigabyte H61M-S1   | 37        | 0.32%   |
| Dell System        | 37        | 0.32%   |
| HP EliteBook       | 35        | 0.31%   |
| ASRock B450M       | 34        | 0.3%    |
| Acer Predator      | 34        | 0.3%    |
| Gigabyte B75M-D3H  | 33        | 0.29%   |
| Gigabyte B450M     | 33        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1210      | 10.56%  |
| 2012    | 1175      | 10.25%  |
| 2011    | 1095      | 9.55%   |
| 2018    | 1071      | 9.35%   |
| 2017    | 920       | 8.03%   |
| 2013    | 890       | 7.77%   |
| 2010    | 745       | 6.5%    |
| 2016    | 719       | 6.27%   |
| 2014    | 684       | 5.97%   |
| 2020    | 602       | 5.25%   |
| 2009    | 501       | 4.37%   |
| 2008    | 485       | 4.23%   |
| 2015    | 439       | 3.83%   |
| 2021    | 398       | 3.47%   |
| 2007    | 283       | 2.47%   |
| 2006    | 95        | 0.83%   |
| 2022    | 64        | 0.56%   |
| Unknown | 48        | 0.42%   |
| 2005    | 26        | 0.23%   |
| 2004    | 9         | 0.08%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6838      | 59.67%  |
| Desktop        | 4330      | 37.78%  |
| All in one     | 94        | 0.82%   |
| Convertible    | 75        | 0.65%   |
| Mini pc        | 42        | 0.37%   |
| Server         | 33        | 0.29%   |
| System on chip | 26        | 0.23%   |
| Tablet         | 20        | 0.17%   |
| Phone          | 1         | 0.01%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10356     | 89.78%  |
| Enabled  | 1179      | 10.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11442     | 99.84%  |
| Yes  | 18        | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3152      | 27.04%  |
| 3.01-4.0        | 3091      | 26.52%  |
| 8.01-16.0       | 2024      | 17.36%  |
| 16.01-24.0      | 1753      | 15.04%  |
| 1.01-2.0        | 787       | 6.75%   |
| 32.01-64.0      | 347       | 2.98%   |
| 2.01-3.0        | 257       | 2.2%    |
| 24.01-32.0      | 98        | 0.84%   |
| 64.01-256.0     | 78        | 0.67%   |
| 0.51-1.0        | 59        | 0.51%   |
| More than 256.0 | 6         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 4766      | 37.71%  |
| 2.01-3.0    | 3406      | 26.95%  |
| 3.01-4.0    | 1590      | 12.58%  |
| 4.01-8.0    | 1467      | 11.61%  |
| 0.51-1.0    | 958       | 7.58%   |
| 8.01-16.0   | 289       | 2.29%   |
| 0.01-0.5    | 120       | 0.95%   |
| 16.01-24.0  | 25        | 0.2%    |
| 32.01-64.0  | 5         | 0.04%   |
| 24.01-32.0  | 5         | 0.04%   |
| Unknown     | 5         | 0.04%   |
| 64.01-256.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7329      | 62.36%  |
| 2       | 3203      | 27.25%  |
| 3       | 688       | 5.85%   |
| 4       | 263       | 2.24%   |
| 0       | 115       | 0.98%   |
| 5       | 81        | 0.69%   |
| 6       | 48        | 0.41%   |
| 7       | 10        | 0.09%   |
| 8       | 7         | 0.06%   |
| 9       | 5         | 0.04%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7104      | 61.54%  |
| Yes       | 4440      | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10534     | 91.78%  |
| No        | 944       | 8.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8398      | 72.79%  |
| No        | 3140      | 27.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5791      | 50.04%  |
| No        | 5781      | 49.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 11460     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1497      | 12.48%  |
| Rio de Janeiro        | 689       | 5.74%   |
| Brasília             | 363       | 3.03%   |
| Belo Horizonte        | 333       | 2.78%   |
| Curitiba              | 325       | 2.71%   |
| Porto Alegre          | 260       | 2.17%   |
| Fortaleza             | 251       | 2.09%   |
| Salvador              | 177       | 1.48%   |
| Campinas              | 174       | 1.45%   |
| Recife                | 154       | 1.28%   |
| Goiânia              | 137       | 1.14%   |
| Florianópolis        | 132       | 1.1%    |
| Santo André          | 130       | 1.08%   |
| Natal                 | 107       | 0.89%   |
| Manaus                | 97        | 0.81%   |
| Osasco                | 91        | 0.76%   |
| Niterói              | 90        | 0.75%   |
| Guarulhos             | 90        | 0.75%   |
| Sao José dos Campos  | 88        | 0.73%   |
| Campo Grande          | 87        | 0.73%   |
| Sao Luís             | 81        | 0.68%   |
| Maringá              | 79        | 0.66%   |
| Belém                | 77        | 0.64%   |
| Sorocaba              | 76        | 0.63%   |
| Joinville             | 73        | 0.61%   |
| Londrina              | 71        | 0.59%   |
| Teresina              | 70        | 0.58%   |
| Joao Pessoa           | 70        | 0.58%   |
| Uberlândia           | 62        | 0.52%   |
| Ribeirao Preto        | 62        | 0.52%   |
| Maceió               | 61        | 0.51%   |
| Juiz de Fora          | 61        | 0.51%   |
| Aracaju               | 58        | 0.48%   |
| Sao Jose              | 55        | 0.46%   |
| Serra                 | 54        | 0.45%   |
| Cuiabá               | 54        | 0.45%   |
| Vitória              | 52        | 0.43%   |
| Duque de Caxias       | 52        | 0.43%   |
| Sao Carlos            | 50        | 0.42%   |
| Sao Bernardo do Campo | 50        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3268      | 4177   | 20.69%  |
| Seagate                        | 3093      | 4333   | 19.58%  |
| Kingston                       | 1601      | 2064   | 10.14%  |
| Samsung Electronics            | 1583      | 2179   | 10.02%  |
| Toshiba                        | 925       | 1079   | 5.86%   |
| SanDisk                        | 810       | 1090   | 5.13%   |
| Unknown                        | 482       | 654    | 3.05%   |
| A-DATA Technology              | 438       | 550    | 2.77%   |
| Hitachi                        | 374       | 459    | 2.37%   |
| China                          | 332       | 391    | 2.1%    |
| Intel                          | 302       | 369    | 1.91%   |
| Crucial                        | 284       | 370    | 1.8%    |
| Silicon Motion                 | 158       | 201    | 1%      |
| ADATA Technology               | 154       | 182    | 0.98%   |
| HGST                           | 134       | 159    | 0.85%   |
| SK hynix                       | 128       | 172    | 0.81%   |
| LITEON                         | 122       | 142    | 0.77%   |
| Maxtor                         | 120       | 140    | 0.76%   |
| KingSpec                       | 95        | 110    | 0.6%    |
| Lexar                          | 89        | 103    | 0.56%   |
| Realtek Semiconductor          | 69        | 86     | 0.44%   |
| Phison                         | 67        | 89     | 0.42%   |
| Corsair                        | 62        | 74     | 0.39%   |
| JMicron Technology             | 59        | 68     | 0.37%   |
| XPG                            | 58        | 71     | 0.37%   |
| Fujitsu                        | 53        | 61     | 0.34%   |
| Netac                          | 49        | 60     | 0.31%   |
| PNY                            | 43        | 51     | 0.27%   |
| Hewlett-Packard                | 42        | 50     | 0.27%   |
| Patriot                        | 40        | 53     | 0.25%   |
| Apple                          | 37        | 54     | 0.23%   |
| SSSTC                          | 35        | 36     | 0.22%   |
| Gigabyte Technology            | 34        | 46     | 0.22%   |
| Solid State Storage Technology | 32        | 43     | 0.2%    |
| XrayDisk                       | 29        | 36     | 0.18%   |
| KIOXIA                         | 29        | 34     | 0.18%   |
| Solid State Storage            | 28        | 31     | 0.18%   |
| Unknown                        | 28        | 29     | 0.18%   |
| KingDian                       | 27        | 34     | 0.17%   |
| Smart                          | 26        | 30     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 548       | 3.25%   |
| WDC WD10SPZX-21Z10T0 1TB            | 474       | 2.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 301       | 1.79%   |
| Kingston SA400S37120G 120GB SSD     | 292       | 1.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 279       | 1.66%   |
| Kingston SA400S37480G 480GB SSD     | 270       | 1.6%    |
| Seagate ST500DM002-1BD142 500GB     | 246       | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB      | 196       | 1.16%   |
| Toshiba MQ01ABD100 1TB              | 149       | 0.88%   |
| Kingston SV300S37A120G 120GB SSD    | 142       | 0.84%   |
| Unknown MMC Card  32GB              | 137       | 0.81%   |
| SanDisk SSD PLUS 240GB              | 134       | 0.8%    |
| WDC WD10SPZX-24Z10 1TB              | 132       | 0.78%   |
| Samsung HD322HJ 320GB               | 117       | 0.69%   |
| Seagate Expansion 1TB               | 116       | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 112       | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB            | 107       | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 103       | 0.61%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.61%   |
| Samsung HD161HJ 160GB               | 101       | 0.6%    |
| Samsung HM321HI 320GB               | 99        | 0.59%   |
| Samsung HD502HJ 500GB               | 98        | 0.58%   |
| SanDisk SSD PLUS 120GB              | 97        | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB      | 95        | 0.56%   |
| Samsung HD502HI 500GB               | 95        | 0.56%   |
| Crucial CT240BX500SSD1 240GB        | 95        | 0.56%   |
| Seagate ST9500325AS 500GB           | 88        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 88        | 0.52%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 88        | 0.52%   |
| WDC WD10SPZX-75Z10T2 1TB            | 81        | 0.48%   |
| Toshiba MQ01ABF050 500GB            | 80        | 0.47%   |
| SanDisk SDSSDA240G 240GB            | 78        | 0.46%   |
| WDC WD5000AAKX-003CA0 500GB         | 77        | 0.46%   |
| Toshiba MQ04ABF100 1TB              | 76        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB        | 71        | 0.42%   |
| Intel SSDPEKKW256G7 256GB           | 71        | 0.42%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 70        | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB             | 68        | 0.4%    |
| Seagate ST3500418AS 500GB           | 68        | 0.4%    |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3079      | 4302   | 35.02%  |
| WDC                 | 2921      | 3646   | 33.22%  |
| Samsung Electronics | 1091      | 1425   | 12.41%  |
| Toshiba             | 878       | 1023   | 9.99%   |
| Hitachi             | 374       | 459    | 4.25%   |
| HGST                | 134       | 159    | 1.52%   |
| Maxtor              | 111       | 130    | 1.26%   |
| JMicron Technology  | 53        | 62     | 0.6%    |
| Fujitsu             | 52        | 59     | 0.59%   |
| Unknown             | 33        | 37     | 0.38%   |
| Apple               | 17        | 28     | 0.19%   |
| Hewlett-Packard     | 16        | 18     | 0.18%   |
| ExcelStor           | 10        | 11     | 0.11%   |
| SAGE                | 5         | 9      | 0.06%   |
| HPE                 | 4         | 4      | 0.05%   |
| USB3.0              | 2         | 2      | 0.02%   |
| SABRENT             | 1         | 1      | 0.01%   |
| Phison              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1544      | 1974   | 33.03%  |
| SanDisk             | 611       | 848    | 13.07%  |
| WDC                 | 350       | 431    | 7.49%   |
| China               | 331       | 390    | 7.08%   |
| Samsung Electronics | 325       | 494    | 6.95%   |
| Crucial             | 270       | 352    | 5.78%   |
| A-DATA Technology   | 262       | 317    | 5.6%    |
| LITEON              | 108       | 127    | 2.31%   |
| KingSpec            | 94        | 109    | 2.01%   |
| Lexar               | 87        | 101    | 1.86%   |
| Corsair             | 50        | 59     | 1.07%   |
| Intel               | 49        | 61     | 1.05%   |
| PNY                 | 41        | 49     | 0.88%   |
| Patriot             | 38        | 50     | 0.81%   |
| Netac               | 38        | 48     | 0.81%   |
| Gigabyte Technology | 27        | 38     | 0.58%   |
| Smart               | 26        | 30     | 0.56%   |
| KingDian            | 26        | 33     | 0.56%   |
| Unknown             | 22        | 24     | 0.47%   |
| SK hynix            | 20        | 24     | 0.43%   |
| Apple               | 20        | 24     | 0.43%   |
| Hewlett-Packard     | 19        | 23     | 0.41%   |
| Toshiba             | 17        | 20     | 0.36%   |
| Unknown             | 17        | 18     | 0.36%   |
| Seagate             | 16        | 19     | 0.34%   |
| OCZ                 | 15        | 15     | 0.32%   |
| BHT                 | 14        | 18     | 0.3%    |
| XrayDisk            | 13        | 15     | 0.28%   |
| LITEONIT            | 13        | 19     | 0.28%   |
| Micron Technology   | 10        | 12     | 0.21%   |
| Maxtor              | 9         | 10     | 0.19%   |
| Team                | 8         | 18     | 0.17%   |
| walram              | 7         | 7      | 0.15%   |
| RZX                 | 7         | 12     | 0.15%   |
| Plextor             | 7         | 8      | 0.15%   |
| HUSKY               | 7         | 7      | 0.15%   |
| S3+                 | 6         | 6      | 0.13%   |
| HS-SSD-C100         | 6         | 6      | 0.13%   |
| Colorful            | 6         | 7      | 0.13%   |
| BIWIN               | 6         | 6      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7796      | 11391  | 54.31%  |
| SSD     | 4242      | 5992   | 29.55%  |
| NVMe    | 1823      | 2440   | 12.7%   |
| MMC     | 367       | 523    | 2.56%   |
| Unknown | 127       | 165    | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 10093     | 17076  | 79.91%  |
| NVMe | 1821      | 2437   | 14.42%  |
| MMC  | 367       | 523    | 2.91%   |
| SAS  | 349       | 475    | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7666      | 11459  | 63.81%  |
| 0.51-1.0   | 3701      | 4950   | 30.81%  |
| 1.01-2.0   | 451       | 631    | 3.75%   |
| 3.01-4.0   | 76        | 165    | 0.63%   |
| 2.01-3.0   | 65        | 96     | 0.54%   |
| 4.01-10.0  | 50        | 75     | 0.42%   |
| 10.01-20.0 | 4         | 6      | 0.03%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3384      | 27.96%  |
| 251-500        | 2935      | 24.25%  |
| 501-1000       | 1995      | 16.48%  |
| 1-20           | 929       | 7.68%   |
| 1001-2000      | 852       | 7.04%   |
| 51-100         | 776       | 6.41%   |
| 21-50          | 560       | 4.63%   |
| 2001-3000      | 241       | 1.99%   |
| Unknown        | 220       | 1.82%   |
| More than 3000 | 210       | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4820      | 38.52%  |
| 21-50          | 2660      | 21.26%  |
| 101-250        | 1552      | 12.4%   |
| 51-100         | 1505      | 12.03%  |
| 251-500        | 830       | 6.63%   |
| 501-1000       | 559       | 4.47%   |
| 1001-2000      | 248       | 1.98%   |
| Unknown        | 220       | 1.76%   |
| 2001-3000      | 63        | 0.5%    |
| More than 3000 | 56        | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 45        | 48     | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 38        | 41     | 3.12%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 29        | 31     | 2.38%   |
| WDC WD5000AAKX-003CA0 500GB         | 24        | 24     | 1.97%   |
| Seagate ST9500325AS 500GB           | 24        | 26     | 1.97%   |
| Samsung Electronics HD322HJ 320GB   | 21        | 28     | 1.73%   |
| Samsung Electronics HD161HJ 160GB   | 19        | 20     | 1.56%   |
| Samsung Electronics HD502HI 500GB   | 16        | 19     | 1.31%   |
| Samsung Electronics HD502HJ 500GB   | 14        | 14     | 1.15%   |
| Toshiba MQ01ABD100 1TB              | 13        | 13     | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 13     | 1.07%   |
| WDC WD10EARS-00Y5B1 1TB             | 12        | 15     | 0.99%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 13     | 0.99%   |
| Toshiba MQ01ABD050 500GB            | 11        | 11     | 0.9%    |
| Seagate ST500LT012-9WS142 500GB     | 11        | 13     | 0.9%    |
| Seagate ST9320325AS 320GB           | 10        | 10     | 0.82%   |
| Seagate ST3500418AS 500GB           | 10        | 14     | 0.82%   |
| Maxtor STM3160215AS 160GB           | 10        | 11     | 0.82%   |
| WDC WD3200AAJS-00L7A0 320GB         | 9         | 9      | 0.74%   |
| Seagate ST3320418AS 320GB           | 9         | 13     | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 12     | 0.74%   |
| Samsung Electronics HD250HJ 250GB   | 9         | 10     | 0.74%   |
| Samsung Electronics HD080HJ 80GB    | 9         | 11     | 0.74%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.74%   |
| Samsung Electronics HM321HI 320GB   | 8         | 8      | 0.66%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.66%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 8      | 0.66%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 12     | 0.66%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.58%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.58%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.58%   |
| Seagate ST31000524AS 1TB            | 7         | 7      | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB      | 7         | 9      | 0.58%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7         | 8      | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 9      | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 6         | 6      | 0.49%   |
| WDC WD5000AAKX-083CA1 500GB         | 6         | 6      | 0.49%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6         | 7      | 0.49%   |
| Toshiba MQ01ABD032 320GB            | 6         | 7      | 0.49%   |
| Seagate ST3500413AS 500GB           | 6         | 7      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 388       | 463    | 33.42%  |
| WDC                 | 258       | 293    | 22.22%  |
| Samsung Electronics | 176       | 219    | 15.16%  |
| Toshiba             | 98        | 106    | 8.44%   |
| Hitachi             | 60        | 63     | 5.17%   |
| Kingston            | 46        | 54     | 3.96%   |
| Maxtor              | 21        | 23     | 1.81%   |
| SanDisk             | 17        | 17     | 1.46%   |
| China               | 17        | 18     | 1.46%   |
| A-DATA Technology   | 11        | 11     | 0.95%   |
| HGST                | 9         | 9      | 0.78%   |
| Intel               | 6         | 6      | 0.52%   |
| XPG                 | 5         | 5      | 0.43%   |
| Fujitsu             | 5         | 6      | 0.43%   |
| PNY                 | 4         | 6      | 0.34%   |
| Crucial             | 4         | 4      | 0.34%   |
| OCZ                 | 3         | 3      | 0.26%   |
| KingSpec            | 3         | 3      | 0.26%   |
| Apple               | 3         | 3      | 0.26%   |
| XrayDisk            | 2         | 2      | 0.17%   |
| walram              | 2         | 2      | 0.17%   |
| LITEON              | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |
| Corsair             | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| SK hynix            | 1         | 1      | 0.09%   |
| ShiJi               | 1         | 1      | 0.09%   |
| QIANGHE             | 1         | 1      | 0.09%   |
| Plextor             | 1         | 1      | 0.09%   |
| OCZ-VERTEX3         | 1         | 1      | 0.09%   |
| Netac               | 1         | 1      | 0.09%   |
| Mushkin             | 1         | 1      | 0.09%   |
| Micron Technology   | 1         | 1      | 0.09%   |
| LITEONIT            | 1         | 2      | 0.09%   |
| JMicron Technology  | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| FEASSO              | 1         | 2      | 0.09%   |
| ExcelStor           | 1         | 2      | 0.09%   |
| EGON                | 1         | 1      | 0.09%   |
| ADATA Technology    | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 388       | 463    | 38.72%  |
| WDC                 | 245       | 280    | 24.45%  |
| Samsung Electronics | 170       | 213    | 16.97%  |
| Toshiba             | 97        | 105    | 9.68%   |
| Hitachi             | 60        | 63     | 5.99%   |
| Maxtor              | 21        | 23     | 2.1%    |
| HGST                | 9         | 9      | 0.9%    |
| Fujitsu             | 5         | 6      | 0.5%    |
| Hewlett-Packard     | 2         | 2      | 0.2%    |
| Apple               | 2         | 2      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| FEASSO              | 1         | 2      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 916       | 1171   | 85.29%  |
| SSD  | 137       | 150    | 12.76%  |
| NVMe | 21        | 21     | 1.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 11.11%  |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 7.41%   |
| Samsung Electronics HD502HJ 500GB                | 2         | 4      | 7.41%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 3.7%    |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 3.7%    |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 3.7%    |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.7%    |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 3.7%    |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 3.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 3.7%    |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 3.7%    |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 3.7%    |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 3.7%    |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 3.7%    |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 3.7%    |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 3.7%    |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 3.7%    |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 3.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 37.04%  |
| Seagate             | 8         | 8      | 29.63%  |
| WDC                 | 4         | 4      | 14.81%  |
| Toshiba             | 3         | 3      | 11.11%  |
| Maxtor              | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8168      | 14419  | 67.04%  |
| Works    | 2948      | 4720   | 24.2%   |
| Malfunc  | 1039      | 1342   | 8.53%   |
| Failed   | 27        | 29     | 0.22%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8757      | 67.44%  |
| AMD                              | 1845      | 14.21%  |
| ADATA Technology                 | 360       | 2.77%   |
| Nvidia                           | 256       | 1.97%   |
| SanDisk                          | 252       | 1.94%   |
| Samsung Electronics              | 213       | 1.64%   |
| Silicon Motion                   | 182       | 1.4%    |
| Solid State Storage Technology   | 108       | 0.83%   |
| Realtek Semiconductor            | 103       | 0.79%   |
| Silicon Integrated Systems [SiS] | 102       | 0.79%   |
| SK hynix                         | 101       | 0.78%   |
| Phison Electronics               | 99        | 0.76%   |
| Marvell Technology Group         | 81        | 0.62%   |
| JMicron Technology               | 80        | 0.62%   |
| Kingston Technology Company      | 76        | 0.59%   |
| VIA Technologies                 | 72        | 0.55%   |
| ASMedia Technology               | 67        | 0.52%   |
| Micron/Crucial Technology        | 36        | 0.28%   |
| KIOXIA                           | 29        | 0.22%   |
| Lite-On Technology               | 26        | 0.2%    |
| Toshiba America Info Systems     | 24        | 0.18%   |
| LSI Logic / Symbios Logic        | 21        | 0.16%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.11%   |
| Broadcom / LSI                   | 12        | 0.09%   |
| Micron Technology                | 11        | 0.08%   |
| Union Memory (Shenzhen)          | 7         | 0.05%   |
| Silicon Image                    | 6         | 0.05%   |
| Beijing Starblaze Technology     | 6         | 0.05%   |
| Seagate Technology               | 5         | 0.04%   |
| Netac Technology                 | 5         | 0.04%   |
| Shenzhen Longsys Electronics     | 4         | 0.03%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| Apple                            | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1123      | 7.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 969       | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 824       | 5.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 621       | 3.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 577       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 465       | 2.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 449       | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 399       | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 377       | 2.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 368       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 315       | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 307       | 1.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 303       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 291       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 243       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 243       | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 242       | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 235       | 1.48%   |
| AMD FCH SATA Controller D                                                               | 215       | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 212       | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 211       | 1.33%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 204       | 1.28%   |
| Nvidia MCP61 SATA Controller                                                            | 178       | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 168       | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 165       | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 160       | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 156       | 0.98%   |
| Nvidia MCP61 IDE                                                                        | 145       | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 145       | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 144       | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 143       | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 142       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 137       | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 136       | 0.85%   |
| ADATA Non-Volatile memory controller                                                    | 133       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 127       | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 125       | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 124       | 0.78%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 123       | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 119       | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8785      | 64.36%  |
| IDE  | 2323      | 17.02%  |
| NVMe | 1833      | 13.43%  |
| RAID | 688       | 5.04%   |
| SCSI | 14        | 0.1%    |
| SAS  | 7         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 9325      | 81.37%  |
| AMD          | 2101      | 18.33%  |
| ARM          | 27        | 0.24%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 1         | 0.01%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 250       | 2.18%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 160       | 1.39%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 144       | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 142       | 1.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 135       | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 127       | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 125       | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 120       | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 118       | 1.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 116       | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 111       | 0.97%   |
| AMD FX-6300 Six-Core Processor                | 93        | 0.81%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 91        | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 90        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 88        | 0.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 88        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 86        | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 85        | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 84        | 0.73%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 84        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 83        | 0.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 81        | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 81        | 0.71%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 81        | 0.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 78        | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 77        | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 75        | 0.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 75        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 72        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 71        | 0.62%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 64        | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 64        | 0.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 64        | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 64        | 0.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 63        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 61        | 0.53%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 60        | 0.52%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 60        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 58        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2805      | 24.43%  |
| Intel Core i7           | 1835      | 15.98%  |
| Intel Core i3           | 1601      | 13.94%  |
| Intel Celeron           | 784       | 6.83%   |
| AMD Ryzen 5             | 511       | 4.45%   |
| Intel Core 2 Duo        | 509       | 4.43%   |
| Intel Pentium Dual-Core | 310       | 2.7%    |
| AMD Ryzen 7             | 301       | 2.62%   |
| Intel Atom              | 294       | 2.56%   |
| Other                   | 282       | 2.46%   |
| Intel Pentium           | 272       | 2.37%   |
| AMD FX                  | 254       | 2.21%   |
| Intel Xeon              | 213       | 1.86%   |
| Intel Pentium Dual      | 145       | 1.26%   |
| AMD Ryzen 3             | 102       | 0.89%   |
| Intel Core 2 Quad       | 96        | 0.84%   |
| AMD Phenom II X4        | 78        | 0.68%   |
| AMD Athlon II X2        | 71        | 0.62%   |
| AMD A4                  | 62        | 0.54%   |
| AMD A10                 | 57        | 0.5%    |
| AMD E                   | 55        | 0.48%   |
| Intel Core 2            | 53        | 0.46%   |
| AMD Athlon 64 X2        | 49        | 0.43%   |
| AMD A6                  | 49        | 0.43%   |
| AMD A8                  | 46        | 0.4%    |
| Intel Genuine           | 41        | 0.36%   |
| AMD C-60                | 41        | 0.36%   |
| AMD Athlon              | 41        | 0.36%   |
| AMD Ryzen 9             | 38        | 0.33%   |
| AMD E1                  | 34        | 0.3%    |
| AMD Sempron             | 31        | 0.27%   |
| Intel Pentium 4         | 29        | 0.25%   |
| AMD Phenom II X6        | 26        | 0.23%   |
| AMD C-70                | 26        | 0.23%   |
| Intel Pentium Gold      | 23        | 0.2%    |
| Intel Core i9           | 21        | 0.18%   |
| AMD Athlon II X4        | 18        | 0.16%   |
| AMD Phenom II X2        | 17        | 0.15%   |
| AMD C-50                | 17        | 0.15%   |
| Intel Celeron Dual-Core | 16        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6169      | 53.73%  |
| 4       | 3610      | 31.44%  |
| 6       | 755       | 6.58%   |
| 8       | 355       | 3.09%   |
| 1       | 328       | 2.86%   |
| 3       | 137       | 1.19%   |
| 12      | 51        | 0.44%   |
| 10      | 22        | 0.19%   |
| 16      | 17        | 0.15%   |
| Unknown | 15        | 0.13%   |
| 14      | 10        | 0.09%   |
| 20      | 6         | 0.05%   |
| 24      | 3         | 0.03%   |
| 5       | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11420     | 99.64%  |
| 2       | 38        | 0.33%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7399      | 64.51%  |
| 1       | 4054      | 35.34%  |
| Unknown | 15        | 0.13%   |
| 8       | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10875     | 94.34%  |
| Unknown        | 542       | 4.7%    |
| 32-bit         | 62        | 0.54%   |
| 64-bit         | 48        | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2214      | 18.68%  |
| 0x306a9    | 986       | 8.32%   |
| 0x206a7    | 964       | 8.13%   |
| 0x1067a    | 631       | 5.32%   |
| 0x906ea    | 406       | 3.43%   |
| 0x806e9    | 401       | 3.38%   |
| 0x20655    | 363       | 3.06%   |
| 0x306c3    | 361       | 3.05%   |
| 0x40651    | 337       | 2.84%   |
| 0x806ec    | 322       | 2.72%   |
| 0x306d4    | 275       | 2.32%   |
| 0x406e3    | 273       | 2.3%    |
| 0x806ea    | 249       | 2.1%    |
| 0x6fd      | 245       | 2.07%   |
| 0x906e9    | 212       | 1.79%   |
| 0x406c4    | 176       | 1.48%   |
| 0x806c1    | 162       | 1.37%   |
| 0x06000852 | 151       | 1.27%   |
| 0x08108109 | 146       | 1.23%   |
| 0x010000c8 | 130       | 1.1%    |
| 0x30678    | 128       | 1.08%   |
| 0x05000119 | 94        | 0.79%   |
| 0x20652    | 93        | 0.78%   |
| 0x906ed    | 87        | 0.73%   |
| 0x08600103 | 81        | 0.68%   |
| 0x0800820d | 80        | 0.67%   |
| 0x08108102 | 79        | 0.67%   |
| 0x10676    | 78        | 0.66%   |
| 0x706e5    | 75        | 0.63%   |
| 0x506e3    | 74        | 0.62%   |
| 0x706a1    | 73        | 0.62%   |
| 0x08701021 | 73        | 0.62%   |
| 0x6fb      | 65        | 0.55%   |
| 0x106ca    | 61        | 0.51%   |
| 0x806eb    | 56        | 0.47%   |
| 0x706a8    | 56        | 0.47%   |
| 0x406c3    | 56        | 0.47%   |
| 0x08701013 | 53        | 0.45%   |
| 0x10661    | 49        | 0.41%   |
| 0x0600611a | 49        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2114      | 18.43%  |
| IvyBridge        | 1200      | 10.46%  |
| SandyBridge      | 1149      | 10.02%  |
| Haswell          | 876       | 7.64%   |
| Penryn           | 819       | 7.14%   |
| Westmere         | 545       | 4.75%   |
| Core             | 464       | 4.05%   |
| Silvermont       | 444       | 3.87%   |
| Skylake          | 423       | 3.69%   |
| Zen+             | 391       | 3.41%   |
| Broadwell        | 328       | 2.86%   |
| K10              | 295       | 2.57%   |
| Piledriver       | 275       | 2.4%    |
| Zen 2            | 256       | 2.23%   |
| Zen              | 220       | 1.92%   |
| TigerLake        | 201       | 1.75%   |
| Bobcat           | 164       | 1.43%   |
| Goldmont plus    | 146       | 1.27%   |
| CometLake        | 142       | 1.24%   |
| Bonnell          | 123       | 1.07%   |
| IceLake          | 115       | 1%      |
| Unknown          | 109       | 0.95%   |
| K8 Hammer        | 105       | 0.92%   |
| Zen 3            | 89        | 0.78%   |
| Excavator        | 75        | 0.65%   |
| Nehalem          | 74        | 0.65%   |
| NetBurst         | 50        | 0.44%   |
| Goldmont         | 48        | 0.42%   |
| K10 Llano        | 46        | 0.4%    |
| Steamroller      | 41        | 0.36%   |
| Bulldozer        | 41        | 0.36%   |
| Jaguar           | 39        | 0.34%   |
| P6               | 26        | 0.23%   |
| Alderlake Hybrid | 15        | 0.13%   |
| K8 & K10 hybrid  | 11        | 0.1%    |
| Puma             | 7         | 0.06%   |
| Tremont          | 3         | 0.03%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7758      | 56.57%  |
| Nvidia                           | 3379      | 24.64%  |
| AMD                              | 2384      | 17.38%  |
| Silicon Integrated Systems [SiS] | 99        | 0.72%   |
| VIA Technologies                 | 55        | 0.4%    |
| Matrox Electronics Systems       | 24        | 0.18%   |
| ASPEED Technology                | 7         | 0.05%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 3         | 0.02%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 953       | 6.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 716       | 5.1%    |
| Intel HD Graphics 620                                                                    | 496       | 3.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 470       | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 394       | 2.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 371       | 2.64%   |
| Intel HD Graphics 5500                                                                   | 298       | 2.12%   |
| Intel UHD Graphics 620                                                                   | 284       | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 283       | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 282       | 2.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 272       | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 271       | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 260       | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 249       | 1.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 238       | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 181       | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 172       | 1.22%   |
| Intel HD Graphics 630                                                                    | 169       | 1.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 167       | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 163       | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 162       | 1.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 158       | 1.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 157       | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 146       | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 142       | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 141       | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 131       | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 131       | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 101       | 0.72%   |
| AMD Renoir                                                                               | 100       | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 97        | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 96        | 0.68%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 96        | 0.68%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 93        | 0.66%   |
| Nvidia TU117M                                                                            | 93        | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 90        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 87        | 0.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 83        | 0.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 81        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 5706      | 49.48%  |
| 1 x AMD                 | 1723      | 14.94%  |
| 1 x Nvidia              | 1619      | 14.04%  |
| Intel + Nvidia          | 1571      | 13.62%  |
| Intel + AMD             | 400       | 3.47%   |
| AMD + Nvidia            | 160       | 1.39%   |
| 2 x AMD                 | 106       | 0.92%   |
| 1 x SiS                 | 99        | 0.86%   |
| 1 x VIA                 | 54        | 0.47%   |
| Other                   | 31        | 0.27%   |
| 1 x Matrox              | 23        | 0.2%    |
| 2 x Nvidia              | 15        | 0.13%   |
| 2 x Intel               | 10        | 0.09%   |
| 1 x ASPEED              | 6         | 0.05%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9180      | 79.19%  |
| Proprietary | 1959      | 16.9%   |
| Unknown     | 454       | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7076      | 60.28%  |
| 1.01-2.0   | 1688      | 14.38%  |
| 0.01-0.5   | 1020      | 8.69%   |
| 0.51-1.0   | 778       | 6.63%   |
| 3.01-4.0   | 735       | 6.26%   |
| 7.01-8.0   | 180       | 1.53%   |
| 5.01-6.0   | 179       | 1.52%   |
| 2.01-3.0   | 58        | 0.49%   |
| 8.01-16.0  | 21        | 0.18%   |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1787      | 14.45%  |
| Goldstar                | 1591      | 12.86%  |
| AU Optronics            | 1519      | 12.28%  |
| BOE                     | 1465      | 11.84%  |
| Chimei Innolux          | 1153      | 9.32%   |
| LG Display              | 1097      | 8.87%   |
| AOC                     | 818       | 6.61%   |
| Dell                    | 515       | 4.16%   |
| Philips                 | 328       | 2.65%   |
| Acer                    | 190       | 1.54%   |
| Chi Mei Optoelectronics | 153       | 1.24%   |
| LG Electronics          | 148       | 1.2%    |
| InfoVision              | 121       | 0.98%   |
| Hewlett-Packard         | 120       | 0.97%   |
| PANDA                   | 109       | 0.88%   |
| Lenovo                  | 102       | 0.82%   |
| Apple                   | 100       | 0.81%   |
| Sony                    | 83        | 0.67%   |
| BenQ                    | 65        | 0.53%   |
| Unknown                 | 58        | 0.47%   |
| HannStar                | 48        | 0.39%   |
| CPT                     | 47        | 0.38%   |
| RTK                     | 46        | 0.37%   |
| Positivo                | 41        | 0.33%   |
| LG Philips              | 35        | 0.28%   |
| Panasonic               | 32        | 0.26%   |
| InnoLux Display         | 29        | 0.23%   |
| SLD                     | 27        | 0.22%   |
| ASUSTek Computer        | 27        | 0.22%   |
| Ancor Communications    | 24        | 0.19%   |
| Sharp                   | 23        | 0.19%   |
| NCS                     | 20        | 0.16%   |
| Toshiba                 | 19        | 0.15%   |
| GDH                     | 19        | 0.15%   |
| MTD                     | 18        | 0.15%   |
| HB@                     | 17        | 0.14%   |
| STA                     | 15        | 0.12%   |
| SKY                     | 15        | 0.12%   |
| AGO                     | 15        | 0.12%   |
| VIE                     | 14        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 164       | 1.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 118       | 0.93%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 116       | 0.91%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 108       | 0.85%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 102       | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 101       | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 98        | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 96        | 0.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 96        | 0.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 79        | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 77        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 74        | 0.58%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 0.56%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 68        | 0.53%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 66        | 0.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 64        | 0.5%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 64        | 0.5%    |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 63        | 0.5%    |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 60        | 0.47%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 58        | 0.46%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 57        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 57        | 0.45%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 55        | 0.43%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.42%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 54        | 0.42%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 54        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 51        | 0.4%    |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 51        | 0.4%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 50        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 50        | 0.39%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 46        | 0.36%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 44        | 0.35%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.35%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 43        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 42        | 0.33%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 42        | 0.33%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 41        | 0.32%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 41        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4864      | 40.36%  |
| 1920x1080 (FHD)    | 3779      | 31.36%  |
| 1600x900 (HD+)     | 502       | 4.17%   |
| 1440x900 (WXGA+)   | 397       | 3.29%   |
| 2560x1080          | 379       | 3.14%   |
| 1360x768           | 335       | 2.78%   |
| 1280x1024 (SXGA)   | 333       | 2.76%   |
| 1280x800 (WXGA)    | 298       | 2.47%   |
| 3840x2160 (4K)     | 268       | 2.22%   |
| 1680x1050 (WSXGA+) | 186       | 1.54%   |
| 1024x768 (XGA)     | 117       | 0.97%   |
| 2560x1440 (QHD)    | 105       | 0.87%   |
| Unknown            | 104       | 0.86%   |
| 1920x1200 (WUXGA)  | 62        | 0.51%   |
| 1280x720 (HD)      | 48        | 0.4%    |
| 1024x600           | 41        | 0.34%   |
| 1920x540           | 36        | 0.3%    |
| 3840x1080          | 29        | 0.24%   |
| 2288x1287          | 20        | 0.17%   |
| 3440x1440          | 14        | 0.12%   |
| 2560x1600          | 11        | 0.09%   |
| 1152x864           | 9         | 0.07%   |
| 4480x1080          | 6         | 0.05%   |
| 5760x1080          | 5         | 0.04%   |
| 3360x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 3200x1080          | 5         | 0.04%   |
| 1600x1200          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 2880x1800          | 4         | 0.03%   |
| 2736x1824          | 4         | 0.03%   |
| 3840x2400          | 3         | 0.02%   |
| 3520x1080          | 3         | 0.02%   |
| 3200x1800 (QHD+)   | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 800x1280           | 2         | 0.02%   |
| 6400x1080          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3691      | 29.72%  |
| 14      | 1492      | 12.01%  |
| 13      | 1321      | 10.64%  |
| 18      | 821       | 6.61%   |
| 21      | 769       | 6.19%   |
| 23      | 718       | 5.78%   |
| 17      | 512       | 4.12%   |
| Unknown | 495       | 3.99%   |
| 24      | 356       | 2.87%   |
| 34      | 327       | 2.63%   |
| 20      | 302       | 2.43%   |
| 19      | 291       | 2.34%   |
| 27      | 278       | 2.24%   |
| 31      | 130       | 1.05%   |
| 22      | 117       | 0.94%   |
| 11      | 113       | 0.91%   |
| 12      | 78        | 0.63%   |
| 40      | 67        | 0.54%   |
| 72      | 61        | 0.49%   |
| 32      | 56        | 0.45%   |
| 28      | 54        | 0.43%   |
| 10      | 47        | 0.38%   |
| 84      | 45        | 0.36%   |
| 54      | 45        | 0.36%   |
| 16      | 39        | 0.31%   |
| 26      | 34        | 0.27%   |
| 52      | 31        | 0.25%   |
| 46      | 28        | 0.23%   |
| 47      | 16        | 0.13%   |
| 37      | 12        | 0.1%    |
| 142     | 9         | 0.07%   |
| 48      | 9         | 0.07%   |
| 25      | 7         | 0.06%   |
| 58      | 6         | 0.05%   |
| 65      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 43      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |
| 50      | 3         | 0.02%   |
| 38      | 3         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6418      | 52.46%  |
| 401-500        | 2178      | 17.8%   |
| 501-600        | 1296      | 10.59%  |
| Unknown        | 495       | 4.05%   |
| 201-300        | 450       | 3.68%   |
| 351-400        | 432       | 3.53%   |
| 701-800        | 384       | 3.14%   |
| 601-700        | 217       | 1.77%   |
| 1001-1500      | 150       | 1.23%   |
| 1501-2000      | 107       | 0.87%   |
| 801-900        | 87        | 0.71%   |
| 901-1000       | 10        | 0.08%   |
| More than 2000 | 9         | 0.07%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8946      | 79.83%  |
| 16/10   | 901       | 8.04%   |
| Unknown | 419       | 3.74%   |
| 21/9    | 363       | 3.24%   |
| 5/4     | 329       | 2.94%   |
| 4/3     | 175       | 1.56%   |
| 3/2     | 52        | 0.46%   |
| 1.00    | 11        | 0.1%    |
| 32/9    | 4         | 0.04%   |
| 0.67    | 2         | 0.02%   |
| 6/5     | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3649      | 29.53%  |
| 81-90          | 2647      | 21.42%  |
| 201-250        | 1657      | 13.41%  |
| 141-150        | 1008      | 8.16%   |
| 151-200        | 853       | 6.9%    |
| 351-500        | 529       | 4.28%   |
| Unknown        | 495       | 4.01%   |
| 301-350        | 287       | 2.32%   |
| More than 1000 | 220       | 1.78%   |
| 71-80          | 170       | 1.38%   |
| 501-1000       | 145       | 1.17%   |
| 251-300        | 143       | 1.16%   |
| 121-130        | 136       | 1.1%    |
| 131-140        | 117       | 0.95%   |
| 51-60          | 113       | 0.91%   |
| 91-100         | 52        | 0.42%   |
| 41-50          | 47        | 0.38%   |
| 61-70          | 43        | 0.35%   |
| 111-120        | 42        | 0.34%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5053      | 42.07%  |
| 51-100        | 3940      | 32.8%   |
| 121-160       | 2022      | 16.83%  |
| Unknown       | 496       | 4.13%   |
| 1-50          | 323       | 2.69%   |
| 161-240       | 154       | 1.28%   |
| More than 240 | 24        | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 9315      | 79.58%  |
| 2     | 1823      | 15.57%  |
| 0     | 472       | 4.03%   |
| 3     | 89        | 0.76%   |
| 4     | 6         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8163      | 44.81%  |
| Qualcomm Atheros                  | 3613      | 19.84%  |
| Intel                             | 3043      | 16.71%  |
| Broadcom                          | 838       | 4.6%    |
| Ralink Technology                 | 409       | 2.25%   |
| Marvell Technology Group          | 231       | 1.27%   |
| Nvidia                            | 214       | 1.17%   |
| JMicron Technology                | 211       | 1.16%   |
| Ralink                            | 210       | 1.15%   |
| Broadcom Limited                  | 185       | 1.02%   |
| TP-Link                           | 177       | 0.97%   |
| Qualcomm Atheros Communications   | 130       | 0.71%   |
| Samsung Electronics               | 107       | 0.59%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.55%   |
| D-Link                            | 70        | 0.38%   |
| VIA Technologies                  | 69        | 0.38%   |
| Motorola PCS                      | 47        | 0.26%   |
| Xiaomi                            | 46        | 0.25%   |
| Microsoft                         | 43        | 0.24%   |
| D-Link System                     | 39        | 0.21%   |
| MediaTek                          | 34        | 0.19%   |
| ASIX Electronics                  | 33        | 0.18%   |
| ICS Advent                        | 18        | 0.1%    |
| Motorola                          | 14        | 0.08%   |
| DisplayLink                       | 11        | 0.06%   |
| Huawei Technologies               | 10        | 0.05%   |
| Edimax Technology                 | 8         | 0.04%   |
| Qualcomm                          | 7         | 0.04%   |
| LG Electronics                    | 7         | 0.04%   |
| ASUSTek Computer                  | 7         | 0.04%   |
| Microchip Technology              | 6         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| Dell                              | 6         | 0.03%   |
| Lenovo                            | 5         | 0.03%   |
| Arduino SA                        | 5         | 0.03%   |
| 3Com                              | 5         | 0.03%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| Ericsson Business Mobile Networks | 4         | 0.02%   |
| Attansic Technology               | 4         | 0.02%   |
| AMD                               | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5357      | 26.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1785      | 8.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 836       | 4.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 743       | 3.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 643       | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 363       | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 323       | 1.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 313       | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 304       | 1.53%   |
| Ralink MT7601U Wireless Adapter                                   | 229       | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 210       | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 185       | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 0.86%   |
| Intel Wireless 7265                                               | 165       | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 163       | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 158       | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 150       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 148       | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 139       | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                   | 116       | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 116       | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 115       | 0.58%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 113       | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 110       | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 104       | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 104       | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 99        | 0.5%    |
| Intel Wireless 7260                                               | 99        | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 98        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 97        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 96        | 0.48%   |
| Intel Wireless 3165                                               | 94        | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.47%   |
| Intel Ethernet Connection (2) I219-V                              | 89        | 0.45%   |
| Ralink RT5370 Wireless Adapter                                    | 84        | 0.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 83        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 81        | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 79        | 0.4%    |
| Intel I211 Gigabit Network Connection                             | 78        | 0.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 77        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3162      | 36.2%   |
| Intel                                 | 2337      | 26.75%  |
| Realtek Semiconductor                 | 1489      | 17.04%  |
| Broadcom                              | 515       | 5.9%    |
| Ralink Technology                     | 409       | 4.68%   |
| Ralink                                | 210       | 2.4%    |
| TP-Link                               | 163       | 1.87%   |
| Qualcomm Atheros Communications       | 130       | 1.49%   |
| Broadcom Limited                      | 103       | 1.18%   |
| D-Link                                | 70        | 0.8%    |
| Microsoft                             | 43        | 0.49%   |
| MediaTek                              | 26        | 0.3%    |
| D-Link System                         | 26        | 0.3%    |
| Edimax Technology                     | 8         | 0.09%   |
| Marvell Technology Group              | 7         | 0.08%   |
| Mercucys                              | 6         | 0.07%   |
| NetGear                               | 3         | 0.03%   |
| Micro Star International              | 3         | 0.03%   |
| Encore Electronics                    | 3         | 0.03%   |
| Dell                                  | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| Linksys                               | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Ericsson Business Mobile Networks     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 836       | 9.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 743       | 8.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 643       | 7.31%   |
| Intel Wi-Fi 6 AX200                                                     | 363       | 4.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 323       | 3.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 313       | 3.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 304       | 3.46%   |
| Ralink MT7601U Wireless Adapter                                         | 229       | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 210       | 2.39%   |
| Intel Wi-Fi 6 AX201                                                     | 185       | 2.1%    |
| Intel Wireless 7265                                                     | 165       | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 163       | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 139       | 1.58%   |
| Qualcomm Atheros AR9271 802.11n                                         | 116       | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 116       | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 115       | 1.31%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 113       | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 104       | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 104       | 1.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 99        | 1.13%   |
| Intel Wireless 7260                                                     | 99        | 1.13%   |
| Intel Wireless 3165                                                     | 94        | 1.07%   |
| Ralink RT5370 Wireless Adapter                                          | 84        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 77        | 0.88%   |
| Intel Wireless 3160                                                     | 77        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 77        | 0.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 77        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 68        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 66        | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 65        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 65        | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 64        | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 63        | 0.72%   |
| Intel Centrino Advanced-N 6235                                          | 62        | 0.71%   |
| Realtek 802.11ac NIC                                                    | 61        | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 61        | 0.69%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 57        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 53        | 0.6%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 52        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7500      | 68.76%  |
| Intel                             | 1052      | 9.65%   |
| Qualcomm Atheros                  | 695       | 6.37%   |
| Broadcom                          | 399       | 3.66%   |
| Marvell Technology Group          | 224       | 2.05%   |
| Nvidia                            | 213       | 1.95%   |
| JMicron Technology                | 211       | 1.93%   |
| Samsung Electronics               | 106       | 0.97%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.92%   |
| Broadcom Limited                  | 88        | 0.81%   |
| VIA Technologies                  | 68        | 0.62%   |
| Xiaomi                            | 46        | 0.42%   |
| Motorola PCS                      | 36        | 0.33%   |
| ASIX Electronics                  | 33        | 0.3%    |
| ICS Advent                        | 18        | 0.17%   |
| TP-Link                           | 14        | 0.13%   |
| D-Link System                     | 13        | 0.12%   |
| DisplayLink                       | 11        | 0.1%    |
| MediaTek                          | 7         | 0.06%   |
| Qualcomm                          | 6         | 0.06%   |
| Microchip Technology              | 5         | 0.05%   |
| LG Electronics                    | 5         | 0.05%   |
| Lenovo                            | 5         | 0.05%   |
| Huawei Technologies               | 5         | 0.05%   |
| ASUSTek Computer                  | 5         | 0.05%   |
| 3Com                              | 5         | 0.05%   |
| Sundance Technology Inc / IC Plus | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| OPPO                              | 3         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| Dell                              | 2         | 0.02%   |
| Aquantia                          | 2         | 0.02%   |
| Apple                             | 2         | 0.02%   |
| Accton Technology                 | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5357      | 48.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1785      | 16.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 1.56%   |
| Nvidia MCP61 Ethernet                                             | 158       | 1.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 150       | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 148       | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 110       | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 98        | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 97        | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 96        | 0.87%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 89        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 81        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 79        | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 78        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 76        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 76        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 73        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 72        | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 69        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 65        | 0.59%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 61        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 53        | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 51        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 48        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 48        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 43        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 40        | 0.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 38        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 36        | 0.33%   |
| Motorola PCS moto g(8) plus                                       | 36        | 0.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 36        | 0.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 36        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 35        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33        | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.28%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 29        | 0.26%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 27        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10522     | 55.39%  |
| WiFi     | 8394      | 44.19%  |
| Modem    | 57        | 0.3%    |
| Unknown  | 23        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6905      | 58.11%  |
| Ethernet | 4976      | 41.87%  |
| Unknown  | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6659      | 57.88%  |
| 1     | 4400      | 38.25%  |
| 0     | 348       | 3.03%   |
| 3     | 74        | 0.64%   |
| 4     | 17        | 0.15%   |
| 10    | 3         | 0.03%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9176      | 78.1%   |
| Yes  | 2573      | 21.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1994      | 34.22%  |
| Qualcomm Atheros Communications | 1522      | 26.12%  |
| Lite-On Technology              | 643       | 11.03%  |
| Cambridge Silicon Radio         | 488       | 8.37%   |
| Realtek Semiconductor           | 228       | 3.91%   |
| Broadcom                        | 225       | 3.86%   |
| IMC Networks                    | 129       | 2.21%   |
| Foxconn / Hon Hai               | 119       | 2.04%   |
| Apple                           | 119       | 2.04%   |
| Dell                            | 77        | 1.32%   |
| Hewlett-Packard                 | 53        | 0.91%   |
| Ralink                          | 48        | 0.82%   |
| Unknown                         | 43        | 0.74%   |
| Qcom                            | 26        | 0.45%   |
| ASUSTek Computer                | 22        | 0.38%   |
| Ralink Technology               | 16        | 0.27%   |
| Alps Electric                   | 13        | 0.22%   |
| Foxconn International           | 12        | 0.21%   |
| MediaTek                        | 9         | 0.15%   |
| Integrated System Solution      | 8         | 0.14%   |
| Askey Computer                  | 8         | 0.14%   |
| Toshiba                         | 4         | 0.07%   |
| Micro Star International        | 4         | 0.07%   |
| Opticis                         | 3         | 0.05%   |
| Conwise Technology              | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Marvell Semiconductor           | 2         | 0.03%   |
| Syntek                          | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 866       | 14.86%  |
| Intel Bluetooth wireless interface                                                  | 664       | 11.39%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 510       | 8.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 488       | 8.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 366       | 6.28%   |
| Intel AX200 Bluetooth                                                               | 352       | 6.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 237       | 4.07%   |
| Intel AX201 Bluetooth                                                               | 184       | 3.16%   |
| Realtek Bluetooth Radio                                                             | 167       | 2.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 145       | 2.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 135       | 2.32%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 121       | 2.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 91        | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 89        | 1.53%   |
| Lite-On Bluetooth Device                                                            | 87        | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 75        | 1.29%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 63        | 1.08%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 58        | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 56        | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 55        | 0.94%   |
| Ralink RT3290 Bluetooth                                                             | 48        | 0.82%   |
| Apple Bluetooth Host Controller                                                     | 44        | 0.75%   |
| Unknown Bluetooth Device                                                            | 43        | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 38        | 0.65%   |
| Apple Bluetooth USB Host Controller                                                 | 37        | 0.63%   |
| Dell Wireless 365 Bluetooth                                                         | 33        | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 32        | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 29        | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 27        | 0.46%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.41%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 21        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 20        | 0.34%   |
| Intel AX210 Bluetooth                                                               | 19        | 0.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 19        | 0.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 17        | 0.29%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.29%   |
| Apple Bluetooth HCI                                                                 | 16        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 8882      | 60.63%  |
| AMD                                             | 2328      | 15.89%  |
| Nvidia                                          | 2268      | 15.48%  |
| C-Media Electronics                             | 243       | 1.66%   |
| Generalplus Technology                          | 117       | 0.8%    |
| Silicon Integrated Systems [SiS]                | 101       | 0.69%   |
| Logitech                                        | 84        | 0.57%   |
| VIA Technologies                                | 74        | 0.51%   |
| JMTek                                           | 65        | 0.44%   |
| Kingston Technology                             | 47        | 0.32%   |
| Texas Instruments                               | 41        | 0.28%   |
| Creative Labs                                   | 37        | 0.25%   |
| Corsair                                         | 29        | 0.2%    |
| Microsoft                                       | 23        | 0.16%   |
| Plantronics                                     | 19        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 16        | 0.11%   |
| GN Netcom                                       | 16        | 0.11%   |
| Tenx Technology                                 | 14        | 0.1%    |
| Razer USA                                       | 14        | 0.1%    |
| BEHRINGER International                         | 14        | 0.1%    |
| Sony                                            | 12        | 0.08%   |
| Realtek Semiconductor                           | 11        | 0.08%   |
| Dell                                            | 9         | 0.06%   |
| M-Audio                                         | 8         | 0.05%   |
| Goldvish                                        | 8         | 0.05%   |
| Focusrite-Novation                              | 8         | 0.05%   |
| SteelSeries ApS                                 | 7         | 0.05%   |
| JBL                                             | 7         | 0.05%   |
| BY EDIFIER                                      | 7         | 0.05%   |
| Samsung Electronics                             | 6         | 0.04%   |
| Samson Technologies                             | 6         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| Fry's Electronics                               | 6         | 0.04%   |
| Creative Technology                             | 6         | 0.04%   |
| Cirrus Logic                                    | 5         | 0.03%   |
| Turtle Beach                                    | 4         | 0.03%   |
| Tdlasunnic                                      | 4         | 0.03%   |
| Meizu                                           | 4         | 0.03%   |
| Lenovo                                          | 4         | 0.03%   |
| Jieli Technology                                | 4         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1168      | 6.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1129      | 6.63%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1111      | 6.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 681       | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 588       | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 578       | 3.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 535       | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 517       | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 394       | 2.32%   |
| Intel 8 Series HD Audio Controller                                                                | 394       | 2.32%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 390       | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 355       | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 354       | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 317       | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 316       | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 314       | 1.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 302       | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 281       | 1.65%   |
| AMD FCH Azalia Controller                                                                         | 254       | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 250       | 1.47%   |
| Nvidia High Definition Audio Controller                                                           | 232       | 1.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 210       | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 201       | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 200       | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 199       | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 184       | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 179       | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 176       | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 172       | 1.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 166       | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 161       | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 146       | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 146       | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 138       | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 137       | 0.8%    |
| Intel 200 Series PCH HD Audio                                                                     | 136       | 0.8%    |
| Generalplus Technology USB Audio Device                                                           | 117       | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 114       | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 113       | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 108       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 865       | 17.85%  |
| Kingston            | 784       | 16.18%  |
| Smart               | 657       | 13.56%  |
| Samsung Electronics | 440       | 9.08%   |
| SK hynix            | 323       | 6.67%   |
| A-DATA Technology   | 283       | 5.84%   |
| Corsair             | 228       | 4.71%   |
| Teikon              | 170       | 3.51%   |
| Crucial             | 166       | 3.43%   |
| Micron Technology   | 158       | 3.26%   |
| Smart Brazil        | 104       | 2.15%   |
| High Bridge         | 61        | 1.26%   |
| Unknown             | 52        | 1.07%   |
| Elpida              | 49        | 1.01%   |
| Team                | 45        | 0.93%   |
| Multilaser          | 43        | 0.89%   |
| G.Skill             | 36        | 0.74%   |
| Unknown (ABCD)      | 31        | 0.64%   |
| Apacer              | 28        | 0.58%   |
| Patriot             | 26        | 0.54%   |
| Nanya Technology    | 21        | 0.43%   |
| Kllisre             | 17        | 0.35%   |
| Atermiter           | 14        | 0.29%   |
| Ramaxel Technology  | 13        | 0.27%   |
| Avant               | 13        | 0.27%   |
| PUSKILL             | 12        | 0.25%   |
| HT Micron           | 11        | 0.23%   |
| RZX                 | 10        | 0.21%   |
| Kreton              | 10        | 0.21%   |
| Smart Modular       | 9         | 0.19%   |
| HBS                 | 9         | 0.19%   |
| CSX                 | 9         | 0.19%   |
| Kingmax             | 7         | 0.14%   |
| GeIL                | 7         | 0.14%   |
| Unknown (82B5)      | 6         | 0.12%   |
| Positivo            | 6         | 0.12%   |
| Carry               | 6         | 0.12%   |
| Hewlett-Packard     | 5         | 0.1%    |
| GLOWAY              | 5         | 0.1%    |
| Unknown (0x0B5E)    | 4         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 75        | 1.41%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 53        | 1%      |
| Unknown                                                          | 52        | 0.98%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 47        | 0.88%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 45        | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 42        | 0.79%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 41        | 0.77%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 39        | 0.73%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 36        | 0.68%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 36        | 0.68%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 35        | 0.66%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 33        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 32        | 0.6%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 32        | 0.6%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 32        | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 30        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 30        | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 29        | 0.55%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 27        | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.45%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 22        | 0.41%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 21        | 0.4%    |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 20        | 0.38%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 20        | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.38%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 20        | 0.38%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 19        | 0.36%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 19        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 18        | 0.34%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 18        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s         | 18        | 0.34%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 17        | 0.32%   |
| Smart RAM SH564128FH8N6TNSQG 4096MB DIMM DDR3 1600MT/s           | 17        | 0.32%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                      | 17        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 16        | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2                                 | 16        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1786      | 43.45%  |
| DDR4         | 1486      | 36.16%  |
| DDR2         | 280       | 6.81%   |
| Unknown      | 193       | 4.7%    |
| SDRAM        | 183       | 4.45%   |
| LPDDR4       | 74        | 1.8%    |
| DDR          | 44        | 1.07%   |
| LPDDR3       | 29        | 0.71%   |
| DRAM         | 19        | 0.46%   |
| DDR5         | 11        | 0.27%   |
| LPDDR5       | 3         | 0.07%   |
| RAM          | 1         | 0.02%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2235      | 54.81%  |
| DIMM         | 1733      | 42.5%   |
| Row Of Chips | 92        | 2.26%   |
| Unknown      | 10        | 0.25%   |
| RIMM         | 3         | 0.07%   |
| FB-DIMM      | 3         | 0.07%   |
| Chip         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1732      | 37.27%  |
| 8192  | 1320      | 28.41%  |
| 2048  | 948       | 20.4%   |
| 16384 | 397       | 8.54%   |
| 1024  | 155       | 3.34%   |
| 32768 | 75        | 1.61%   |
| 512   | 16        | 0.34%   |
| 256   | 2         | 0.04%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1016      | 22.13%  |
| 1333    | 599       | 13.05%  |
| 2667    | 580       | 12.63%  |
| 2400    | 432       | 9.41%   |
| Unknown | 245       | 5.34%   |
| 1334    | 227       | 4.94%   |
| 3200    | 220       | 4.79%   |
| 800     | 155       | 3.38%   |
| 2133    | 142       | 3.09%   |
| 667     | 139       | 3.03%   |
| 1066    | 71        | 1.55%   |
| 3400    | 67        | 1.46%   |
| 1067    | 60        | 1.31%   |
| 3000    | 59        | 1.29%   |
| 3600    | 57        | 1.24%   |
| 1867    | 51        | 1.11%   |
| 4199    | 39        | 0.85%   |
| 3466    | 35        | 0.76%   |
| 533     | 35        | 0.76%   |
| 1866    | 33        | 0.72%   |
| 4267    | 29        | 0.63%   |
| 2800    | 28        | 0.61%   |
| 975     | 21        | 0.46%   |
| 2048    | 20        | 0.44%   |
| 3733    | 19        | 0.41%   |
| 2933    | 19        | 0.41%   |
| 2666    | 19        | 0.41%   |
| 400     | 19        | 0.41%   |
| 3151    | 16        | 0.35%   |
| 333     | 15        | 0.33%   |
| 3266    | 14        | 0.3%    |
| 3800    | 12        | 0.26%   |
| 4800    | 11        | 0.24%   |
| 3334    | 9         | 0.2%    |
| 8400    | 6         | 0.13%   |
| 3333    | 6         | 0.13%   |
| 1200    | 5         | 0.11%   |
| 41632   | 4         | 0.09%   |
| 6400    | 3         | 0.07%   |
| 3066    | 3         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 112       | 44.62%  |
| Seiko Epson           | 68        | 27.09%  |
| Samsung Electronics   | 22        | 8.76%   |
| Canon                 | 19        | 7.57%   |
| Brother Industries    | 17        | 6.77%   |
| Lexmark International | 3         | 1.2%    |
| QinHeng Electronics   | 2         | 0.8%    |
| Apple                 | 2         | 0.8%    |
| Xerox                 | 1         | 0.4%    |
| Ricoh                 | 1         | 0.4%    |
| Prolific Technology   | 1         | 0.4%    |
| Oki Data              | 1         | 0.4%    |
| MIIIW                 | 1         | 0.4%    |
| ARGOX                 | 1         | 0.4%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 13        | 5.16%   |
| Seiko Epson L396 Series                      | 11        | 4.37%   |
| Seiko Epson L355 Series                      | 9         | 3.57%   |
| HP Ink Tank Wireless 410 series              | 9         | 3.57%   |
| HP DeskJet 2130 series                       | 9         | 3.57%   |
| Seiko Epson L365 Series                      | 7         | 2.78%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.78%   |
| HP DeskJet 2700 series                       | 7         | 2.78%   |
| HP Deskjet 2540 series                       | 7         | 2.78%   |
| HP LaserJet 1020                             | 6         | 2.38%   |
| Canon G3010 series                           | 6         | 2.38%   |
| Samsung SCX-4200 series                      | 5         | 1.98%   |
| HP LaserJet Professional P1102w              | 5         | 1.98%   |
| HP DeskJet F4100 Printer series              | 5         | 1.98%   |
| Samsung M2070 Series                         | 4         | 1.59%   |
| Samsung M2020 Series                         | 4         | 1.59%   |
| HP LaserJet P1005                            | 4         | 1.59%   |
| HP DeskJet F4200 series                      | 4         | 1.59%   |
| HP DeskJet 3630 series                       | 4         | 1.59%   |
| HP DeskJet 2620 All-in-One Printer           | 4         | 1.59%   |
| HP Deskjet 2050 J510                         | 4         | 1.59%   |
| Seiko Epson L220 Series                      | 3         | 1.19%   |
| Seiko Epson L210 Series                      | 3         | 1.19%   |
| HP LaserJet 1018                             | 3         | 1.19%   |
| HP Deskjet F4400 series                      | 3         | 1.19%   |
| Brother HL-1200 series                       | 3         | 1.19%   |
| Seiko Epson XP-243 245 247 Series            | 2         | 0.79%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2         | 0.79%   |
| Seiko Epson L375 Series                      | 2         | 0.79%   |
| Seiko Epson L3110 Series                     | 2         | 0.79%   |
| Seiko Epson ET-3750 Series                   | 2         | 0.79%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.79%   |
| Samsung SCX-3200 Series                      | 2         | 0.79%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.79%   |
| QinHeng CH340S                               | 2         | 0.79%   |
| HP Printing Support                          | 2         | 0.79%   |
| HP DeskJet D1360                             | 2         | 0.79%   |
| HP Deskjet 4620 series                       | 2         | 0.79%   |
| HP DeskJet 2300 series                       | 2         | 0.79%   |
| Canon PIXMA MG3000 series                    | 2         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 45%     |
| Hewlett-Packard | 8         | 40%     |
| Seiko Epson     | 2         | 10%     |
| Mustek Systems  | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 25%     |
| Canon CanoScan LIDE 25                                  | 4         | 20%     |
| Canon CanoScan LiDE 110                                 | 2         | 10%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5%      |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5%      |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5%      |
| HP ScanJet G4050                                        | 1         | 5%      |
| HP ScanJet 3800c                                        | 1         | 5%      |
| HP Scanjet 200                                          | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5%      |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5%      |
| Canon CanoScan LiDE 210                                 | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1385      | 19.53%  |
| Microdia                               | 796       | 11.23%  |
| Realtek Semiconductor                  | 653       | 9.21%   |
| Quanta                                 | 587       | 8.28%   |
| Silicon Motion                         | 531       | 7.49%   |
| Sunplus Innovation Technology          | 494       | 6.97%   |
| Acer                                   | 442       | 6.23%   |
| IMC Networks                           | 297       | 4.19%   |
| Suyin                                  | 272       | 3.84%   |
| Logitech                               | 261       | 3.68%   |
| Syntek                                 | 204       | 2.88%   |
| Alcor Micro                            | 142       | 2%      |
| Apple                                  | 110       | 1.55%   |
| Samsung Electronics                    | 87        | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) | 78        | 1.1%    |
| Z-Star Microelectronics                | 60        | 0.85%   |
| Generalplus Technology                 | 59        | 0.83%   |
| Microsoft                              | 51        | 0.72%   |
| Ricoh                                  | 47        | 0.66%   |
| ALi                                    | 43        | 0.61%   |
| Unknown                                | 31        | 0.44%   |
| Sonix Technology                       | 30        | 0.42%   |
| Aveo Technology                        | 28        | 0.39%   |
| Lite-On Technology                     | 23        | 0.32%   |
| GEMBIRD                                | 23        | 0.32%   |
| OmniVision Technologies                | 22        | 0.31%   |
| Importek                               | 22        | 0.31%   |
| Pixart Imaging                         | 20        | 0.28%   |
| Jieli Technology                       | 19        | 0.27%   |
| LG Electronics                         | 18        | 0.25%   |
| Cubeternet                             | 17        | 0.24%   |
| Lenovo                                 | 16        | 0.23%   |
| SunplusIT                              | 15        | 0.21%   |
| icSpring                               | 15        | 0.21%   |
| Y Media                                | 12        | 0.17%   |
| Bison Electronics                      | 11        | 0.16%   |
| Intel                                  | 10        | 0.14%   |
| Genesys Logic                          | 10        | 0.14%   |
| Sunplus Technology                     | 9         | 0.13%   |
| Camera                                 | 9         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 296       | 4.17%   |
| Realtek Integrated_Webcam_HD              | 286       | 4.03%   |
| Chicony HD WebCam                         | 255       | 3.59%   |
| Quanta HD User Facing                     | 250       | 3.52%   |
| Chicony HD User Facing                    | 207       | 2.91%   |
| Silicon Motion Web Camera                 | 192       | 2.7%    |
| Sunplus Integrated_Webcam_HD              | 191       | 2.69%   |
| Quanta VGA WebCam                         | 176       | 2.48%   |
| Chicony Integrated Camera                 | 142       | 2%      |
| Chicony VGA WebCam                        | 137       | 1.93%   |
| Syntek Integrated Camera                  | 114       | 1.61%   |
| Sunplus HD WebCam                         | 101       | 1.42%   |
| Realtek Integrated Webcam                 | 101       | 1.42%   |
| Quanta HD Webcam                          | 99        | 1.39%   |
| Logitech Webcam C270                      | 97        | 1.37%   |
| Chicony USB 2.0 Camera                    | 91        | 1.28%   |
| Alcor Micro USB Camera                    | 88        | 1.24%   |
| Samsung Galaxy A5 (MTP)                   | 86        | 1.21%   |
| Microdia Laptop_Integrated_Webcam_HD      | 80        | 1.13%   |
| Acer BisonCam, NB Pro                     | 72        | 1.01%   |
| Acer Lenovo EasyCamera                    | 64        | 0.9%    |
| Acer EasyCamera                           | 58        | 0.82%   |
| Microdia Dell Laptop Integrated Webcam HD | 54        | 0.76%   |
| Logitech HD Pro Webcam C920               | 54        | 0.76%   |
| Acer HD Webcam                            | 54        | 0.76%   |
| IMC Networks Integrated Camera            | 53        | 0.75%   |
| Silicon Motion WebCam SC-10HDD12636N      | 50        | 0.7%    |
| Microdia Integrated Webcam HD             | 47        | 0.66%   |
| Realtek USB Camera                        | 46        | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 43        | 0.61%   |
| Acer VGA WebCam                           | 43        | 0.61%   |
| Generalplus GENERAL WEBCAM                | 42        | 0.59%   |
| Acer Integrated Camera                    | 42        | 0.59%   |
| Silicon Motion WebCam SCB-1100N           | 41        | 0.58%   |
| Realtek HD WebCam                         | 41        | 0.58%   |
| Chicony EasyCamera                        | 41        | 0.58%   |
| Silicon Motion WebCam SC-13HDL11939N      | 39        | 0.55%   |
| Syntek EasyCamera                         | 38        | 0.54%   |
| Suyin Integrated_Webcam_HD                | 38        | 0.54%   |
| Silicon Motion WebCam SC-0311139N         | 37        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 275       | 47.17%  |
| Synaptics                  | 68        | 11.66%  |
| Shenzhen Goodix Technology | 63        | 10.81%  |
| AuthenTec                  | 58        | 9.95%   |
| Upek                       | 54        | 9.26%   |
| LighTuning Technology      | 29        | 4.97%   |
| Samsung Electronics        | 16        | 2.74%   |
| Elan Microelectronics      | 8         | 1.37%   |
| STMicroelectronics         | 4         | 0.69%   |
| Futronic Technology        | 2         | 0.34%   |
| Focal-systems.Corp         | 2         | 0.34%   |
| Dell                       | 2         | 0.34%   |
| Next Biometrics            | 1         | 0.17%   |
| DigitalPersona             | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 104       | 17.84%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 7.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 7.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 4.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.46%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 4.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 24        | 4.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 3.95%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.09%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.74%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 2.74%   |
| Samsung Fingerprint Device                                                 | 16        | 2.74%   |
| Synaptics  WBDI                                                            | 15        | 2.57%   |
| AuthenTec AES2810                                                          | 14        | 2.4%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.4%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.06%   |
| Validity Sensors VFS491                                                    | 11        | 1.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 1.72%   |
| AuthenTec Fingerprint Sensor                                               | 10        | 1.72%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.37%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.37%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.2%    |
| Unknown                                                                    | 7         | 1.2%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.03%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.34%   |
| Futronic FS81 Fingerprint Scanner Module                                   | 2         | 0.34%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.34%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.34%   |
| AuthenTec AES1600                                                          | 2         | 0.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 78        | 42.86%  |
| Alcor Micro                       | 27        | 14.84%  |
| Gemalto (was Gemplus)             | 15        | 8.24%   |
| Lenovo                            | 13        | 7.14%   |
| Giesecke & Devrient               | 11        | 6.04%   |
| Upek                              | 9         | 4.95%   |
| Watchdata                         | 7         | 3.85%   |
| Aladdin Knowledge Systems         | 6         | 3.3%    |
| SCM Microsystems                  | 4         | 2.2%    |
| OmniKey                           | 3         | 1.65%   |
| O2 Micro                          | 3         | 1.65%   |
| Chicony Electronics               | 3         | 1.65%   |
| VASCO Data Security International | 1         | 0.55%   |
| Realtek Semiconductor             | 1         | 0.55%   |
| Advanced Card Systems             | 1         | 0.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 14.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 11.54%  |
| Broadcom 5880                                                                | 20        | 10.99%  |
| Broadcom 58200                                                               | 20        | 10.99%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 9.34%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 14        | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 4.95%   |
| Watchdata USB Key                                                            | 7         | 3.85%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.3%    |
| Aladdin Knowledge Systems Token JC                                           | 6         | 3.3%    |
| Giesecke & Devrient StarSign CUT S                                           | 5         | 2.75%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.65%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.1%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.1%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.1%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.1%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.55%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.55%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.55%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.55%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 9247      | 79.36%  |
| 1     | 2106      | 18.07%  |
| 2     | 240       | 2.06%   |
| 3     | 33        | 0.28%   |
| 4     | 17        | 0.15%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.03%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 846       | 31.46%  |
| Fingerprint reader       | 579       | 21.53%  |
| Net/wireless             | 346       | 12.87%  |
| Multimedia controller    | 233       | 8.66%   |
| Chipcard                 | 153       | 5.69%   |
| Communication controller | 102       | 3.79%   |
| Bluetooth                | 86        | 3.2%    |
| Camera                   | 72        | 2.68%   |
| Sound                    | 58        | 2.16%   |
| Unassigned class         | 51        | 1.9%    |
| Storage                  | 41        | 1.52%   |
| Net/ethernet             | 34        | 1.26%   |
| Modem                    | 24        | 0.89%   |
| Flash memory             | 20        | 0.74%   |
| Card reader              | 14        | 0.52%   |
| Network                  | 9         | 0.33%   |
| Storage/ide              | 7         | 0.26%   |
| Firewire controller      | 5         | 0.19%   |
| Storage/raid             | 4         | 0.15%   |
| Wireless                 | 1         | 0.04%   |
| Video                    | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

