Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 7480

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7548               | Notebook    | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [88d774df0d](https://linux-hardware.org/?probe=88d774df0d) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [87d4b56fee](https://linux-hardware.org/?probe=87d4b56fee) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [a418b302b9](https://linux-hardware.org/?probe=a418b302b9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [00fe705be0](https://linux-hardware.org/?probe=00fe705be0) | Apr 27, 2023 |
| Lenovo        | 318D                        | All in one  | [8cf49b59a5](https://linux-hardware.org/?probe=8cf49b59a5) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [6d981e0d7c](https://linux-hardware.org/?probe=6d981e0d7c) | Apr 25, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2e4cd9799b](https://linux-hardware.org/?probe=2e4cd9799b) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | Notebook    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [7609d632a4](https://linux-hardware.org/?probe=7609d632a4) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| Intel         | NUC7i7DNB J83500-206        | Mini pc     | [b00fa62f7c](https://linux-hardware.org/?probe=b00fa62f7c) | Apr 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | Notebook    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Shuttle       | FG45 V10                    | Desktop     | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [e76fb532be](https://linux-hardware.org/?probe=e76fb532be) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [3193403ef5](https://linux-hardware.org/?probe=3193403ef5) | Apr 19, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [80ee2192b6](https://linux-hardware.org/?probe=80ee2192b6) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [8858427eed](https://linux-hardware.org/?probe=8858427eed) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d076bcd8a5](https://linux-hardware.org/?probe=d076bcd8a5) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [8c450d2469](https://linux-hardware.org/?probe=8c450d2469) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | Notebook    | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [d5212d6298](https://linux-hardware.org/?probe=d5212d6298) | Apr 13, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | Notebook    | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | Notebook    | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0ba5f3a06e](https://linux-hardware.org/?probe=0ba5f3a06e) | Apr 12, 2023 |
| HP            | 3396                        | Desktop     | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1589                        | Desktop     | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | Notebook    | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Gigabyte      | B75-D3V                     | Desktop     | [fe025c9491](https://linux-hardware.org/?probe=fe025c9491) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | 1998                        | Desktop     | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| AMI           | Intel                       | Desktop     | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| Dell          | Latitude E5550              | Notebook    | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| HP            | 1998                        | Desktop     | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | Notebook    | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Packard Be... | IMEDIA S2870 V1.0           | Desktop     | [61e1ab6733](https://linux-hardware.org/?probe=61e1ab6733) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| Dell          | Latitude E4200              | Notebook    | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| HP            | 1998                        | Desktop     | [4830678f31](https://linux-hardware.org/?probe=4830678f31) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | VM42                        | Desktop     | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | Notebook    | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [0a39d6faec](https://linux-hardware.org/?probe=0a39d6faec) | Apr 04, 2023 |
| Medion        | E2221T MD61083              | Convertible | [daa63988bd](https://linux-hardware.org/?probe=daa63988bd) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [151ffca106](https://linux-hardware.org/?probe=151ffca106) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [fb78fdb60c](https://linux-hardware.org/?probe=fb78fdb60c) | Apr 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Google        | Snappy                      | Notebook    | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | Notebook    | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c767575f27](https://linux-hardware.org/?probe=c767575f27) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [bb72de54b6](https://linux-hardware.org/?probe=bb72de54b6) | Mar 31, 2023 |
| HP            | 1998                        | Desktop     | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Dell          | G15 5515                    | Notebook    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ed35fbea6c](https://linux-hardware.org/?probe=ed35fbea6c) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Primux Tec... | A173                        | All in one  | [f31f5f63b9](https://linux-hardware.org/?probe=f31f5f63b9) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| Primux Tec... | A173                        | All in one  | [95e3fd6b4b](https://linux-hardware.org/?probe=95e3fd6b4b) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | Desktop     | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [307a8bce3e](https://linux-hardware.org/?probe=307a8bce3e) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [b924b0ff06](https://linux-hardware.org/?probe=b924b0ff06) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | Notebook    | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | Notebook    | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | Notebook    | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| MSI           | MS-AA8B 100                 | All in one  | [8f698075ee](https://linux-hardware.org/?probe=8f698075ee) | Mar 27, 2023 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| IP3 Tech      | GB3B                        | Mini pc     | [58b3789af3](https://linux-hardware.org/?probe=58b3789af3) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | Notebook    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [6a3fedcc68](https://linux-hardware.org/?probe=6a3fedcc68) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | Notebook    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | Notebook    | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [8a0cc5a4cb](https://linux-hardware.org/?probe=8a0cc5a4cb) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | Notebook    | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| HP            | 1790                        | Desktop     | [1a468c1b1c](https://linux-hardware.org/?probe=1a468c1b1c) | Mar 24, 2023 |
| Dell          | G15 5515                    | Notebook    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [81273bd2b0](https://linux-hardware.org/?probe=81273bd2b0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2db2fb4a5a](https://linux-hardware.org/?probe=2db2fb4a5a) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [79cbdbc9c1](https://linux-hardware.org/?probe=79cbdbc9c1) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | Notebook    | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fc5894dcb4](https://linux-hardware.org/?probe=fc5894dcb4) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| ASUSTek       | PB60                        | Desktop     | [ec438486aa](https://linux-hardware.org/?probe=ec438486aa) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [c2bab115eb](https://linux-hardware.org/?probe=c2bab115eb) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [aab84f14ed](https://linux-hardware.org/?probe=aab84f14ed) | Mar 21, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [deaf7b9049](https://linux-hardware.org/?probe=deaf7b9049) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| HP            | 250 G4                      | Notebook    | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Supermicro    | X10SRL-F                    | Server      | [96e896465a](https://linux-hardware.org/?probe=96e896465a) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | Notebook    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [09fac43b8e](https://linux-hardware.org/?probe=09fac43b8e) | Mar 17, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c94efea21b](https://linux-hardware.org/?probe=c94efea21b) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [afd7547cd1](https://linux-hardware.org/?probe=afd7547cd1) | Mar 16, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| Acer          | FIH57                       | Desktop     | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| Intel         | Unknown                     | Desktop     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | Notebook    | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [c436834b30](https://linux-hardware.org/?probe=c436834b30) | Mar 14, 2023 |
| ZOTAC         | ZBOX-ID41                   | Mini pc     | [620812fe84](https://linux-hardware.org/?probe=620812fe84) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cf5cbabe11](https://linux-hardware.org/?probe=cf5cbabe11) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| MSI           | MS-B1831                    | Desktop     | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [86a3944105](https://linux-hardware.org/?probe=86a3944105) | Mar 11, 2023 |
| AZW           | SER                         | Mini pc     | [96c3aadd1e](https://linux-hardware.org/?probe=96c3aadd1e) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | Notebook    | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [18134c0dc1](https://linux-hardware.org/?probe=18134c0dc1) | Mar 10, 2023 |
| Intel         | S2600WT2R H21573-372        | Server      | [572cded7f3](https://linux-hardware.org/?probe=572cded7f3) | Mar 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [5df81d1297](https://linux-hardware.org/?probe=5df81d1297) | Mar 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a40a70a964](https://linux-hardware.org/?probe=a40a70a964) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [946f48cdf6](https://linux-hardware.org/?probe=946f48cdf6) | Mar 09, 2023 |
| FriendlyEl... | NanoPC-T4                   | Soc         | [901194d1e1](https://linux-hardware.org/?probe=901194d1e1) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | Notebook    | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | Notebook    | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | Notebook    | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | Desktop     | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7c17068a98](https://linux-hardware.org/?probe=7c17068a98) | Mar 08, 2023 |
| HP            | 0AA8h                       | Desktop     | [6552e8b371](https://linux-hardware.org/?probe=6552e8b371) | Mar 07, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [4e2cd40175](https://linux-hardware.org/?probe=4e2cd40175) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| HP            | 2B0A                        | All in one  | [35f88e8f33](https://linux-hardware.org/?probe=35f88e8f33) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | Notebook    | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | Notebook    | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| HP            | 87A4 10100                  | All in one  | [6b92aede76](https://linux-hardware.org/?probe=6b92aede76) | Mar 05, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c6bb0ba4a6](https://linux-hardware.org/?probe=c6bb0ba4a6) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | Notebook    | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f4cf2185ea](https://linux-hardware.org/?probe=f4cf2185ea) | Mar 04, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Intel         | powered classmate PC        | Notebook    | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [49462bd855](https://linux-hardware.org/?probe=49462bd855) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c7cee84058](https://linux-hardware.org/?probe=c7cee84058) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [5033b7233d](https://linux-hardware.org/?probe=5033b7233d) | Mar 03, 2023 |
| Chuwi         | UBook                       | Tablet      | [6cbfc99f43](https://linux-hardware.org/?probe=6cbfc99f43) | Mar 03, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | Notebook    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [0a38248462](https://linux-hardware.org/?probe=0a38248462) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| ASRock        | Q1900M Pro3                 | Desktop     | [ef9e90045e](https://linux-hardware.org/?probe=ef9e90045e) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [84a1a2c71e](https://linux-hardware.org/?probe=84a1a2c71e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | Notebook    | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [72d16085b5](https://linux-hardware.org/?probe=72d16085b5) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f03ce01ac3](https://linux-hardware.org/?probe=f03ce01ac3) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [24952b3b19](https://linux-hardware.org/?probe=24952b3b19) | Feb 27, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [d3e84076c7](https://linux-hardware.org/?probe=d3e84076c7) | Feb 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc7b5cb76e](https://linux-hardware.org/?probe=dc7b5cb76e) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | Notebook    | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | Notebook    | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | Notebook    | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3c27f298a3](https://linux-hardware.org/?probe=3c27f298a3) | Feb 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d8bafec2da](https://linux-hardware.org/?probe=d8bafec2da) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [804306660e](https://linux-hardware.org/?probe=804306660e) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | Notebook    | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| Acer          | H57M01                      | Desktop     | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [3f26c5e55c](https://linux-hardware.org/?probe=3f26c5e55c) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | Notebook    | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | 371C No DPK                 | All in one  | [02248f5982](https://linux-hardware.org/?probe=02248f5982) | Feb 16, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [5d03d010f4](https://linux-hardware.org/?probe=5d03d010f4) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | Notebook    | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Intel         | X79M-S                      | Desktop     | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e5b971a4b0](https://linux-hardware.org/?probe=e5b971a4b0) | Feb 14, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [3f40aab3d2](https://linux-hardware.org/?probe=3f40aab3d2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4211a6a7f4](https://linux-hardware.org/?probe=4211a6a7f4) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f3e396ccc3](https://linux-hardware.org/?probe=f3e396ccc3) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | Notebook    | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [0bd59541f9](https://linux-hardware.org/?probe=0bd59541f9) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | Notebook    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Lenovo        | 3741 NOK                    | Desktop     | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Unknown       | Intel X79                   | Desktop     | [2ad659fd7a](https://linux-hardware.org/?probe=2ad659fd7a) | Feb 06, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | Desktop     | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bede5aa93c](https://linux-hardware.org/?probe=bede5aa93c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | Notebook    | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | Notebook    | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X8DTL                       | Server      | [a3be5cdf41](https://linux-hardware.org/?probe=a3be5cdf41) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [0bd8186d9e](https://linux-hardware.org/?probe=0bd8186d9e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | Notebook    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | 805D                        | Desktop     | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | Notebook    | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [838de293f2](https://linux-hardware.org/?probe=838de293f2) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | Desktop     | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | Notebook    | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| HP            | G62                         | Notebook    | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | Notebook    | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | Notebook    | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | Notebook    | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [854a69817d](https://linux-hardware.org/?probe=854a69817d) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | Desktop     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| MSI           | MS-7383                     | Desktop     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | Desktop     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | Notebook    | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b2aecb083b](https://linux-hardware.org/?probe=b2aecb083b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [73779874bd](https://linux-hardware.org/?probe=73779874bd) | Jan 23, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [39f5980c8d](https://linux-hardware.org/?probe=39f5980c8d) | Jan 22, 2023 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [70bd257f2c](https://linux-hardware.org/?probe=70bd257f2c) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [05c0d355e1](https://linux-hardware.org/?probe=05c0d355e1) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | Notebook    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| AZW           | U59                         | Desktop     | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| MSI           | H170 GAMING M3              | Desktop     | [2fe05693b8](https://linux-hardware.org/?probe=2fe05693b8) | Jan 20, 2023 |
| Toshiba       | NB520                       | Notebook    | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [26e47819f8](https://linux-hardware.org/?probe=26e47819f8) | Jan 18, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [bb86adb1ed](https://linux-hardware.org/?probe=bb86adb1ed) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [4d510de3d8](https://linux-hardware.org/?probe=4d510de3d8) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6b721444d5](https://linux-hardware.org/?probe=6b721444d5) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [8b665c7b84](https://linux-hardware.org/?probe=8b665c7b84) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| Eii           | GB01                        | Desktop     | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [407f5b7997](https://linux-hardware.org/?probe=407f5b7997) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | Desktop     | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | Notebook    | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [be72db11da](https://linux-hardware.org/?probe=be72db11da) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [92f9f48219](https://linux-hardware.org/?probe=92f9f48219) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | Notebook    | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | Notebook    | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [af87fe7cb0](https://linux-hardware.org/?probe=af87fe7cb0) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| HP            | 8433 11                     | Desktop     | [bc44066299](https://linux-hardware.org/?probe=bc44066299) | Jan 13, 2023 |
| HP            | 212A                        | Desktop     | [92f32467ec](https://linux-hardware.org/?probe=92f32467ec) | Jan 13, 2023 |
| eMachines     | E725                        | Notebook    | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| Biostar       | B250MHC                     | Desktop     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0402d5609b](https://linux-hardware.org/?probe=0402d5609b) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [287fab2142](https://linux-hardware.org/?probe=287fab2142) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | Notebook    | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | Desktop     | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Dell          | 0FM586                      | Desktop     | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [64d4a8c163](https://linux-hardware.org/?probe=64d4a8c163) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | Notebook    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [89397e1c47](https://linux-hardware.org/?probe=89397e1c47) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | Notebook    | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | PRO A320M-B                 | Desktop     | [3ffa3cf6f0](https://linux-hardware.org/?probe=3ffa3cf6f0) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| Medion        | AXA                         | All in one  | [37a1a1bc8b](https://linux-hardware.org/?probe=37a1a1bc8b) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | Notebook    | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [60f83cacd0](https://linux-hardware.org/?probe=60f83cacd0) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [f56cccfdc7](https://linux-hardware.org/?probe=f56cccfdc7) | Jan 09, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [1905ffef34](https://linux-hardware.org/?probe=1905ffef34) | Jan 09, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | Notebook    | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3698ce3c60](https://linux-hardware.org/?probe=3698ce3c60) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| Samsung       | 950QED                      | Convertible | [186e8cc52c](https://linux-hardware.org/?probe=186e8cc52c) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Pyramid       | CPYSKI0002 A                | Desktop     | [0b20d79be6](https://linux-hardware.org/?probe=0b20d79be6) | Jan 09, 2023 |
| Dell          | Studio 1558                 | Notebook    | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [10efec9ea3](https://linux-hardware.org/?probe=10efec9ea3) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | Aspire C24-860              | All in one  | [ab25618998](https://linux-hardware.org/?probe=ab25618998) | Jan 07, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | Notebook    | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [7831fb0431](https://linux-hardware.org/?probe=7831fb0431) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [46c8437a45](https://linux-hardware.org/?probe=46c8437a45) | Jan 05, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Unknown       | AM02                        | Mini pc     | [6f6c81bf78](https://linux-hardware.org/?probe=6f6c81bf78) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0FM586                      | Desktop     | [7e181126bc](https://linux-hardware.org/?probe=7e181126bc) | Jan 03, 2023 |
| Dell          | 0FM586                      | Desktop     | [fff469554f](https://linux-hardware.org/?probe=fff469554f) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | Notebook    | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b557b201c4](https://linux-hardware.org/?probe=b557b201c4) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [b0e7bc419b](https://linux-hardware.org/?probe=b0e7bc419b) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| MSI           | Boston                      | Desktop     | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | Notebook    | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | Notebook    | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [328cfe3747](https://linux-hardware.org/?probe=328cfe3747) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Teclast       | TbooK 16 Power              | Tablet      | [c8a0dcd956](https://linux-hardware.org/?probe=c8a0dcd956) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | Notebook    | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | Notebook    | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| Lenovo        | 318D                        | All in one  | [1bc8e7088b](https://linux-hardware.org/?probe=1bc8e7088b) | Dec 24, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | MS-B1421                    | Desktop     | [58968767bd](https://linux-hardware.org/?probe=58968767bd) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7502622c61](https://linux-hardware.org/?probe=7502622c61) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | Notebook    | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [405443fc24](https://linux-hardware.org/?probe=405443fc24) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2c931919d](https://linux-hardware.org/?probe=d2c931919d) | Dec 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [e048dd7a4e](https://linux-hardware.org/?probe=e048dd7a4e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| HP            | 8597                        | Desktop     | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | Notebook    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [b6c7b47859](https://linux-hardware.org/?probe=b6c7b47859) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Lenovo        | 318D                        | All in one  | [da52280286](https://linux-hardware.org/?probe=da52280286) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [bbf59c4c2a](https://linux-hardware.org/?probe=bbf59c4c2a) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [33d60ebbbe](https://linux-hardware.org/?probe=33d60ebbbe) | Dec 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7d1ece638c](https://linux-hardware.org/?probe=7d1ece638c) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Pro-B         | INSYS                       | Desktop     | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9d665864a0](https://linux-hardware.org/?probe=9d665864a0) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [0af09d12d5](https://linux-hardware.org/?probe=0af09d12d5) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | Desktop     | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [238bda76a3](https://linux-hardware.org/?probe=238bda76a3) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [7870cee549](https://linux-hardware.org/?probe=7870cee549) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | Notebook    | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | Notebook    | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | Notebook    | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [e088d4027d](https://linux-hardware.org/?probe=e088d4027d) | Dec 10, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [aefce63130](https://linux-hardware.org/?probe=aefce63130) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [c72c2382b3](https://linux-hardware.org/?probe=c72c2382b3) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [e098953c51](https://linux-hardware.org/?probe=e098953c51) | Dec 09, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [314ed3ea05](https://linux-hardware.org/?probe=314ed3ea05) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 723       | 13.29%  |
| Ubuntu 18.04                 | 508       | 9.34%   |
| Ubuntu 22.04                 | 239       | 4.39%   |
| Debian 11                    | 231       | 4.25%   |
| OpenMandriva 4.2             | 182       | 3.35%   |
| OpenMandriva 4.3             | 120       | 2.21%   |
| KDE neon 20.04               | 112       | 2.06%   |
| Zorin 16                     | 94        | 1.73%   |
| Debian 10                    | 83        | 1.53%   |
| Manjaro                      | 82        | 1.51%   |
| OpenMandriva 23.01           | 81        | 1.49%   |
| Linux Mint 20.3              | 79        | 1.45%   |
| Ubuntu 20.10                 | 72        | 1.32%   |
| Linux Mint 19.3              | 71        | 1.31%   |
| Arch Rolling                 | 69        | 1.27%   |
| Arch                         | 65        | 1.2%    |
| Xubuntu 20.04                | 61        | 1.12%   |
| Ubuntu 19.04                 | 61        | 1.12%   |
| Ubuntu 19.10                 | 58        | 1.07%   |
| Linux Mint 20.1              | 58        | 1.07%   |
| Fedora 36                    | 54        | 0.99%   |
| Ubuntu 21.04                 | 53        | 0.97%   |
| Linux Mint 20                | 52        | 0.96%   |
| Ubuntu 21.10                 | 50        | 0.92%   |
| Linux Mint 21.1              | 49        | 0.9%    |
| Fedora 37                    | 49        | 0.9%    |
| Linux Mint 20.2              | 47        | 0.86%   |
| Fedora 35                    | 47        | 0.86%   |
| Xubuntu 18.04                | 46        | 0.85%   |
| ROSA R10                     | 43        | 0.79%   |
| Kubuntu 20.04                | 43        | 0.79%   |
| Ubuntu 22.10                 | 40        | 0.74%   |
| Fedora 34                    | 40        | 0.74%   |
| Zorin 15                     | 39        | 0.72%   |
| Linux Mint 21                | 38        | 0.7%    |
| Fedora 33                    | 38        | 0.7%    |
| Pop!_OS 20.04                | 37        | 0.68%   |
| Ubuntu 18.10                 | 33        | 0.61%   |
| Pop!_OS 22.04                | 33        | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 32        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1787      | 34.77%  |
| Linux Mint    | 429       | 8.35%   |
| OpenMandriva  | 423       | 8.23%   |
| Debian        | 380       | 7.39%   |
| Fedora        | 256       | 4.98%   |
| Manjaro       | 192       | 3.74%   |
| KDE neon      | 147       | 2.86%   |
| Zorin         | 138       | 2.68%   |
| Arch          | 132       | 2.57%   |
| Xubuntu       | 126       | 2.45%   |
| Endless       | 123       | 2.39%   |
| Pop!_OS       | 117       | 2.28%   |
| ROSA          | 109       | 2.12%   |
| Kubuntu       | 108       | 2.1%    |
| Ubuntu MATE   | 57        | 1.11%   |
| Elementary    | 54        | 1.05%   |
| openSUSE      | 50        | 0.97%   |
| Gentoo        | 47        | 0.91%   |
| Ubuntu Unity  | 40        | 0.78%   |
| ArcoLinux     | 40        | 0.78%   |
| Kali          | 34        | 0.66%   |
| Lubuntu       | 30        | 0.58%   |
| BlackPanther  | 28        | 0.54%   |
| SteamOS       | 24        | 0.47%   |
| LMDE          | 23        | 0.45%   |
| Parrot        | 19        | 0.37%   |
| MX            | 19        | 0.37%   |
| EndeavourOS   | 19        | 0.37%   |
| Clear Linux   | 16        | 0.31%   |
| Nobara        | 15        | 0.29%   |
| Ubuntu Budgie | 12        | 0.23%   |
| Garuda Linux  | 10        | 0.19%   |
| CentOS        | 10        | 0.19%   |
| Reborn OS     | 8         | 0.16%   |
| Deepin        | 6         | 0.12%   |
| Ubuntu Studio | 5         | 0.1%    |
| Solus         | 5         | 0.1%    |
| RHEL          | 5         | 0.1%    |
| Peppermint    | 5         | 0.1%    |
| Slackware     | 4         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 178       | 3%      |
| 5.16.7-desktop-1omv4003         | 117       | 1.97%   |
| 5.4.0-42-generic                | 96        | 1.62%   |
| 6.1.1-desktop-1omv2290          | 76        | 1.28%   |
| 5.15.0-56-generic               | 63        | 1.06%   |
| 5.4.0-58-generic                | 60        | 1.01%   |
| 5.10.0-8-amd64                  | 56        | 0.94%   |
| 5.4.0-52-generic                | 49        | 0.83%   |
| 5.4.0-54-generic                | 48        | 0.81%   |
| 5.4.0-26-generic                | 47        | 0.79%   |
| 5.15.0-52-generic               | 44        | 0.74%   |
| 5.3.0-28-generic                | 42        | 0.71%   |
| 5.15.0-58-generic               | 41        | 0.69%   |
| 5.4.0-48-generic                | 39        | 0.66%   |
| 5.3.0-40-generic                | 37        | 0.62%   |
| 5.11.0-27-generic               | 37        | 0.62%   |
| 5.0.0-37-generic                | 36        | 0.61%   |
| 5.4.0-29-generic                | 34        | 0.57%   |
| 5.4.0-65-generic                | 32        | 0.54%   |
| 5.3.0-46-generic                | 32        | 0.54%   |
| 5.13.0-30-generic               | 32        | 0.54%   |
| 5.11.0-43-generic               | 32        | 0.54%   |
| 5.19.0-35-generic               | 31        | 0.52%   |
| 5.15.0-60-generic               | 31        | 0.52%   |
| 5.10.0-18-amd64                 | 31        | 0.52%   |
| 5.10.0-21-amd64                 | 30        | 0.51%   |
| 5.0.0-32-generic                | 30        | 0.51%   |
| 5.4.0-72-generic                | 29        | 0.49%   |
| 5.4.0-40-generic                | 29        | 0.49%   |
| 5.15.0-48-generic               | 29        | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.49%   |
| 6.2.6-desktop-1omv2390          | 27        | 0.45%   |
| 5.4.0-47-generic                | 27        | 0.45%   |
| 5.4.0-37-generic                | 27        | 0.45%   |
| 5.3.0-51-generic                | 27        | 0.45%   |
| 5.19.0-38-generic               | 26        | 0.44%   |
| 5.15.0-53-generic               | 26        | 0.44%   |
| 5.13.0-39-generic               | 26        | 0.44%   |
| 5.13.0-28-generic               | 26        | 0.44%   |
| 5.11.0-41-generic               | 26        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 949       | 17.02%  |
| 5.15.0  | 432       | 7.75%   |
| 4.15.0  | 416       | 7.46%   |
| 5.11.0  | 276       | 4.95%   |
| 5.10.0  | 274       | 4.91%   |
| 5.8.0   | 266       | 4.77%   |
| 5.3.0   | 254       | 4.56%   |
| 5.13.0  | 242       | 4.34%   |
| 5.0.0   | 198       | 3.55%   |
| 5.10.14 | 180       | 3.23%   |
| 5.19.0  | 143       | 2.57%   |
| 5.16.7  | 121       | 2.17%   |
| 4.18.0  | 114       | 2.04%   |
| 6.1.1   | 86        | 1.54%   |
| 4.19.0  | 85        | 1.52%   |
| 4.9.60  | 33        | 0.59%   |
| 6.2.6   | 31        | 0.56%   |
| 6.0.0   | 26        | 0.47%   |
| 6.1.0   | 24        | 0.43%   |
| 4.4.0   | 22        | 0.39%   |
| 4.18.16 | 22        | 0.39%   |
| 5.18.0  | 20        | 0.36%   |
| 5.14.0  | 20        | 0.36%   |
| 6.0.12  | 15        | 0.27%   |
| 5.9.16  | 15        | 0.27%   |
| 5.17.5  | 15        | 0.27%   |
| 5.9.0   | 13        | 0.23%   |
| 6.1.11  | 12        | 0.22%   |
| 5.7.0   | 12        | 0.22%   |
| 5.3.18  | 12        | 0.22%   |
| 5.16.11 | 12        | 0.22%   |
| 5.16.0  | 12        | 0.22%   |
| 5.12.4  | 12        | 0.22%   |
| 4.9.20  | 12        | 0.22%   |
| 6.1.12  | 11        | 0.2%    |
| 5.15.6  | 11        | 0.2%    |
| 6.0.8   | 10        | 0.18%   |
| 6.0.10  | 10        | 0.18%   |
| 5.8.11  | 10        | 0.18%   |
| 5.6.0   | 10        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1013      | 18.4%   |
| 5.15    | 555       | 10.08%  |
| 5.10    | 535       | 9.72%   |
| 4.15    | 416       | 7.56%   |
| 5.11    | 333       | 6.05%   |
| 5.8     | 326       | 5.92%   |
| 5.3     | 282       | 5.12%   |
| 5.13    | 280       | 5.09%   |
| 5.19    | 203       | 3.69%   |
| 5.0     | 202       | 3.67%   |
| 6.1     | 185       | 3.36%   |
| 5.16    | 185       | 3.36%   |
| 4.18    | 137       | 2.49%   |
| 6.0     | 105       | 1.91%   |
| 4.19    | 100       | 1.82%   |
| 4.9     | 80        | 1.45%   |
| 5.14    | 75        | 1.36%   |
| 6.2     | 73        | 1.33%   |
| 5.18    | 66        | 1.2%    |
| 5.9     | 52        | 0.94%   |
| 5.6     | 51        | 0.93%   |
| 5.17    | 48        | 0.87%   |
| 5.7     | 45        | 0.82%   |
| 5.12    | 44        | 0.8%    |
| 5.5     | 26        | 0.47%   |
| 4.4     | 26        | 0.47%   |
| 4.1     | 9         | 0.16%   |
| 5.2     | 8         | 0.15%   |
| 3.10    | 8         | 0.15%   |
| 5.1     | 7         | 0.13%   |
| 4.16    | 6         | 0.11%   |
| 4.20    | 4         | 0.07%   |
| 4.17    | 4         | 0.07%   |
| 4.13    | 4         | 0.07%   |
| 4.8     | 3         | 0.05%   |
| 4.14    | 3         | 0.05%   |
| 3.16    | 3         | 0.05%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4751      | 95.77%  |
| i686    | 178       | 3.59%   |
| aarch64 | 24        | 0.48%   |
| armv7l  | 7         | 0.14%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2202      | 42.22%  |
| KDE5             | 927       | 17.77%  |
| Unknown          | 650       | 12.46%  |
| XFCE             | 387       | 7.42%   |
| X-Cinnamon       | 335       | 6.42%   |
| KDE              | 157       | 3.01%   |
| MATE             | 154       | 2.95%   |
| Cinnamon         | 53        | 1.02%   |
| Pantheon         | 50        | 0.96%   |
| LXQt             | 49        | 0.94%   |
| KDE4             | 48        | 0.92%   |
| Unity            | 39        | 0.75%   |
| i3               | 33        | 0.63%   |
| Budgie           | 24        | 0.46%   |
| LXDE             | 20        | 0.38%   |
| Deepin           | 19        | 0.36%   |
| GNOME Flashback  | 15        | 0.29%   |
| openbox          | 10        | 0.19%   |
| GNOME Classic    | 7         | 0.13%   |
| bspwm            | 7         | 0.13%   |
| qtile            | 4         | 0.08%   |
| DWM              | 4         | 0.08%   |
| xmonad           | 3         | 0.06%   |
| Enlightenment    | 3         | 0.06%   |
| trinity          | 2         | 0.04%   |
| LeftWM           | 2         | 0.04%   |
| ICEWM            | 2         | 0.04%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| i3-with-shmlog   | 1         | 0.02%   |
| Hyprland         | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| chadwm           | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4012      | 78.54%  |
| Wayland | 668       | 13.08%  |
| Unknown | 348       | 6.81%   |
| Tty     | 80        | 1.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2691      | 52.2%   |
| SDDM    | 805       | 15.62%  |
| GDM     | 569       | 11.04%  |
| GDM3    | 459       | 8.9%    |
| LightDM | 403       | 7.82%   |
| TDM     | 150       | 2.91%   |
| KDM     | 48        | 0.93%   |
| XDM     | 13        | 0.25%   |
| LXDM    | 7         | 0.14%   |
| SLiM    | 5         | 0.1%    |
| Ly      | 5         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2985      | 58.36%  |
| en_US          | 868       | 16.97%  |
| Unknown        | 646       | 12.63%  |
| ca_ES          | 187       | 3.66%   |
| en_GB          | 108       | 2.11%   |
| C              | 51        | 1%      |
| gl_ES          | 33        | 0.65%   |
| de_DE          | 33        | 0.65%   |
| eu_ES          | 25        | 0.49%   |
| fr_FR          | 20        | 0.39%   |
| ru_RU          | 18        | 0.35%   |
| it_IT          | 15        | 0.29%   |
| an_ES          | 13        | 0.25%   |
| es_MX          | 10        | 0.2%    |
| es_AR          | 9         | 0.18%   |
| ca_AD          | 7         | 0.14%   |
| pt_BR          | 6         | 0.12%   |
| en_IE          | 6         | 0.12%   |
| pl_PL          | 5         | 0.1%    |
| en_AG          | 5         | 0.1%    |
| ca_ES@valencia | 5         | 0.1%    |
| C.UTF8         | 5         | 0.1%    |
| ro_RO          | 4         | 0.08%   |
| es_ES.UTF8     | 4         | 0.08%   |
| pt_PT          | 3         | 0.06%   |
| POSIX          | 3         | 0.06%   |
| nl_NL          | 3         | 0.06%   |
| fr_BE          | 3         | 0.06%   |
| de_AT          | 3         | 0.06%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2606      | 51.4%   |
| EFI  | 2464      | 48.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3903      | 76.68%  |
| Overlay  | 450       | 8.84%   |
| Btrfs    | 349       | 6.86%   |
| Unknown  | 212       | 4.17%   |
| Xfs      | 69        | 1.36%   |
| Ext3     | 34        | 0.67%   |
| Zfs      | 27        | 0.53%   |
| Tmpfs    | 19        | 0.37%   |
| Ext2     | 16        | 0.31%   |
| Reiserfs | 4         | 0.08%   |
| Jfs      | 3         | 0.06%   |
| Aufs     | 3         | 0.06%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2858      | 56.2%   |
| GPT     | 1675      | 32.94%  |
| MBR     | 552       | 10.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4233      | 83.44%  |
| Yes       | 840       | 16.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3363      | 66.53%  |
| Yes       | 1692      | 33.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 956       | 19.28%  |
| Hewlett-Packard         | 702       | 14.16%  |
| Lenovo                  | 585       | 11.8%   |
| MSI                     | 435       | 8.77%   |
| Gigabyte Technology     | 413       | 8.33%   |
| Acer                    | 326       | 6.57%   |
| Dell                    | 311       | 6.27%   |
| ASRock                  | 120       | 2.42%   |
| Apple                   | 117       | 2.36%   |
| Toshiba                 | 109       | 2.2%    |
| Intel                   | 80        | 1.61%   |
| Unknown                 | 66        | 1.33%   |
| Packard Bell            | 45        | 0.91%   |
| HUAWEI                  | 44        | 0.89%   |
| Sony                    | 41        | 0.83%   |
| Medion                  | 39        | 0.79%   |
| Chuwi                   | 38        | 0.77%   |
| Samsung Electronics     | 32        | 0.65%   |
| Notebook                | 30        | 0.6%    |
| SLIMBOOK                | 27        | 0.54%   |
| LG Electronics          | 21        | 0.42%   |
| Valve                   | 20        | 0.4%    |
| Raspberry Pi Foundation | 20        | 0.4%    |
| Fujitsu                 | 20        | 0.4%    |
| Pegatron                | 18        | 0.36%   |
| eMachines               | 18        | 0.36%   |
| ECS                     | 17        | 0.34%   |
| BESSTAR Tech            | 17        | 0.34%   |
| Teclast                 | 14        | 0.28%   |
| AMI                     | 14        | 0.28%   |
| Fujitsu Siemens         | 13        | 0.26%   |
| Timi                    | 12        | 0.24%   |
| Foxconn                 | 12        | 0.24%   |
| Supermicro              | 11        | 0.22%   |
| Huanan                  | 10        | 0.2%    |
| AZW                     | 10        | 0.2%    |
| Microsoft               | 8         | 0.16%   |
| Dynabook                | 8         | 0.16%   |
| Clevo                   | 8         | 0.16%   |
| Shuttle                 | 7         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 92        | 1.86%   |
| ASUS All Series                            | 53        | 1.07%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.44%   |
| HP Pavilion g6                             | 22        | 0.44%   |
| Valve Jupiter                              | 20        | 0.4%    |
| HP Pavilion dv6                            | 20        | 0.4%    |
| HP Notebook                                | 19        | 0.38%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.36%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.3%    |
| Gigabyte B450M DS3H                        | 14        | 0.28%   |
| MSI MS-7C37                                | 11        | 0.22%   |
| HP G62                                     | 11        | 0.22%   |
| ASUS P5G41T-M LX                           | 11        | 0.22%   |
| RPi Raspberry Pi                           | 10        | 0.2%    |
| MSI MS-7817                                | 10        | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.2%    |
| HP Pavilion 15                             | 10        | 0.2%    |
| HP Laptop 15-da0xxx                        | 10        | 0.2%    |
| Gigabyte 970A-DS3P                         | 10        | 0.2%    |
| Dell XPS 13 7390                           | 10        | 0.2%    |
| HUAWEI BOHK-WAX9X                          | 9         | 0.18%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.18%   |
| Gigabyte H110M-S2H                         | 9         | 0.18%   |
| ASUS PRIME A320M-K                         | 9         | 0.18%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.16%   |
| MSI MS-7C02                                | 8         | 0.16%   |
| MSI MS-7B79                                | 8         | 0.16%   |
| HP Laptop 15-bw0xx                         | 8         | 0.16%   |
| HP EliteDesk 800 G1 SFF                    | 8         | 0.16%   |
| HP Compaq Elite 8300 SFF                   | 8         | 0.16%   |
| Gigabyte H61M-DS2                          | 8         | 0.16%   |
| Gigabyte B450 AORUS M                      | 8         | 0.16%   |
| Chuwi GemiBook Pro                         | 8         | 0.16%   |
| ASUS X555LAB                               | 8         | 0.16%   |
| ASUS X550VX                                | 8         | 0.16%   |
| ASUS X540NA                                | 8         | 0.16%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.16%   |
| ASUS PRIME B450M-A                         | 8         | 0.16%   |
| Acer Aspire 5750G                          | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 236       | 4.76%   |
| Lenovo ThinkPad       | 190       | 3.83%   |
| HP Pavilion           | 146       | 2.94%   |
| Lenovo IdeaPad        | 137       | 2.76%   |
| HP Compaq             | 94        | 1.9%    |
| Dell Latitude         | 92        | 1.86%   |
| Unknown               | 92        | 1.86%   |
| ASUS PRIME            | 86        | 1.73%   |
| Toshiba Satellite     | 85        | 1.71%   |
| ASUS VivoBook         | 80        | 1.61%   |
| HP Laptop             | 71        | 1.43%   |
| ASUS ROG              | 67        | 1.35%   |
| HP EliteBook          | 66        | 1.33%   |
| ASUS TUF              | 66        | 1.33%   |
| Dell XPS              | 59        | 1.19%   |
| Lenovo ThinkCentre    | 56        | 1.13%   |
| ASUS All              | 53        | 1.07%   |
| Dell OptiPlex         | 50        | 1.01%   |
| Dell Inspiron         | 43        | 0.87%   |
| HP ProBook            | 40        | 0.81%   |
| ASUS ZenBook          | 38        | 0.77%   |
| Packard Bell EasyNote | 32        | 0.65%   |
| HP 250                | 31        | 0.63%   |
| MSI Prestige          | 26        | 0.52%   |
| Lenovo Legion         | 25        | 0.5%    |
| MSI Modern            | 24        | 0.48%   |
| Lenovo Yoga           | 24        | 0.48%   |
| HP OMEN               | 24        | 0.48%   |
| Dell Precision        | 24        | 0.48%   |
| Gigabyte B450M        | 23        | 0.46%   |
| Gigabyte X570         | 21        | 0.42%   |
| Valve Jupiter         | 20        | 0.4%    |
| RPi Raspberry         | 20        | 0.4%    |
| Acer Extensa          | 20        | 0.4%    |
| HP Notebook           | 19        | 0.38%   |
| HP ENVY               | 19        | 0.38%   |
| HP EliteDesk          | 19        | 0.38%   |
| ASUS ASUS             | 19        | 0.38%   |
| Acer TravelMate       | 19        | 0.38%   |
| Lenovo ThinkBook      | 18        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 508       | 10.24%  |
| 2019    | 472       | 9.52%   |
| 2020    | 413       | 8.33%   |
| 2014    | 337       | 6.8%    |
| 2021    | 326       | 6.57%   |
| 2012    | 309       | 6.23%   |
| 2013    | 308       | 6.21%   |
| 2017    | 300       | 6.05%   |
| 2015    | 293       | 5.91%   |
| 2011    | 286       | 5.77%   |
| 2010    | 259       | 5.22%   |
| 2009    | 238       | 4.8%    |
| 2016    | 231       | 4.66%   |
| 2008    | 229       | 4.62%   |
| 2007    | 165       | 3.33%   |
| 2022    | 131       | 2.64%   |
| 2006    | 85        | 1.71%   |
| Unknown | 31        | 0.63%   |
| 2005    | 22        | 0.44%   |
| 2004    | 7         | 0.14%   |
| 2003    | 3         | 0.06%   |
| 2023    | 2         | 0.04%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2742      | 55.29%  |
| Desktop        | 1871      | 37.73%  |
| All in one     | 89        | 1.79%   |
| Convertible    | 77        | 1.55%   |
| Mini pc        | 77        | 1.55%   |
| Tablet         | 43        | 0.87%   |
| System on chip | 28        | 0.56%   |
| Server         | 28        | 0.56%   |
| Phone          | 3         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4660      | 93.42%  |
| Enabled  | 328       | 6.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4951      | 99.84%  |
| Yes  | 8         | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1116      | 22.13%  |
| 3.01-4.0        | 1042      | 20.66%  |
| 16.01-24.0      | 1032      | 20.46%  |
| 8.01-16.0       | 920       | 18.24%  |
| 32.01-64.0      | 430       | 8.52%   |
| 1.01-2.0        | 229       | 4.54%   |
| 2.01-3.0        | 81        | 1.61%   |
| 64.01-256.0     | 69        | 1.37%   |
| 0.51-1.0        | 60        | 1.19%   |
| 24.01-32.0      | 56        | 1.11%   |
| More than 256.0 | 6         | 0.12%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2130      | 38.69%  |
| 2.01-3.0   | 1385      | 25.16%  |
| 4.01-8.0   | 693       | 12.59%  |
| 3.01-4.0   | 603       | 10.95%  |
| 0.51-1.0   | 429       | 7.79%   |
| 8.01-16.0  | 177       | 3.22%   |
| 0.01-0.5   | 62        | 1.13%   |
| 16.01-24.0 | 13        | 0.24%   |
| 24.01-32.0 | 10        | 0.18%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3055      | 59.47%  |
| 2       | 1291      | 25.13%  |
| 3       | 416       | 8.1%    |
| 4       | 180       | 3.5%    |
| 5       | 73        | 1.42%   |
| 0       | 44        | 0.86%   |
| 6       | 37        | 0.72%   |
| 7       | 15        | 0.29%   |
| 9       | 8         | 0.16%   |
| 8       | 7         | 0.14%   |
| 10      | 4         | 0.08%   |
| 12      | 2         | 0.04%   |
| 11      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3003      | 59.96%  |
| Yes       | 2005      | 40.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4291      | 86.25%  |
| No        | 684       | 13.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3738      | 74.79%  |
| No        | 1260      | 25.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2851      | 56.8%   |
| No        | 2168      | 43.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4959      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 825       | 15.22%  |
| Barcelona                  | 554       | 10.22%  |
| Seville                    | 188       | 3.47%   |
| Valencia                   | 181       | 3.34%   |
| Zaragoza                   | 80        | 1.48%   |
| Málaga                    | 80        | 1.48%   |
| Granada                    | 73        | 1.35%   |
| Valladolid                 | 58        | 1.07%   |
| Palma                      | 53        | 0.98%   |
| Bilbao                     | 52        | 0.96%   |
| Vigo                       | 51        | 0.94%   |
| Sabadell                   | 51        | 0.94%   |
| Alcobendas                 | 51        | 0.94%   |
| Las Palmas de Gran Canaria | 49        | 0.9%    |
| Córdoba                   | 49        | 0.9%    |
| Ourense                    | 42        | 0.77%   |
| Murcia                     | 37        | 0.68%   |
| Oviedo                     | 36        | 0.66%   |
| Pamplona                   | 34        | 0.63%   |
| Alcalá de Henares         | 34        | 0.63%   |
| Donostia / San Sebastian   | 33        | 0.61%   |
| Alicante                   | 32        | 0.59%   |
| A Coruña                  | 31        | 0.57%   |
| Santa Cruz de Tenerife     | 28        | 0.52%   |
| León                      | 28        | 0.52%   |
| Almería                   | 28        | 0.52%   |
| Gijón                     | 27        | 0.5%    |
| Santiago de Compostela     | 25        | 0.46%   |
| Mostoles                   | 25        | 0.46%   |
| Burgos                     | 25        | 0.46%   |
| Salamanca                  | 23        | 0.42%   |
| Barakaldo                  | 23        | 0.42%   |
| Vitoria-Gasteiz            | 22        | 0.41%   |
| Terrassa                   | 22        | 0.41%   |
| Albacete                   | 22        | 0.41%   |
| Santander                  | 21        | 0.39%   |
| Fuenlabrada                | 20        | 0.37%   |
| Cartagena                  | 20        | 0.37%   |
| Badalona                   | 20        | 0.37%   |
| Lugo                       | 19        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1237      | 1903   | 17.02%  |
| WDC                         | 1015      | 1488   | 13.97%  |
| Samsung Electronics         | 957       | 1376   | 13.17%  |
| Kingston                    | 820       | 1123   | 11.28%  |
| Toshiba                     | 522       | 799    | 7.18%   |
| SanDisk                     | 393       | 525    | 5.41%   |
| Unknown                     | 278       | 358    | 3.82%   |
| Crucial                     | 277       | 390    | 3.81%   |
| Hitachi                     | 223       | 263    | 3.07%   |
| SK hynix                    | 166       | 215    | 2.28%   |
| Intel                       | 153       | 199    | 2.11%   |
| HGST                        | 125       | 157    | 1.72%   |
| Micron Technology           | 113       | 140    | 1.55%   |
| China                       | 69        | 92     | 0.95%   |
| Phison                      | 55        | 61     | 0.76%   |
| Fujitsu                     | 44        | 50     | 0.61%   |
| KIOXIA                      | 43        | 54     | 0.59%   |
| Micron/Crucial Technology   | 41        | 51     | 0.56%   |
| Apple                       | 39        | 53     | 0.54%   |
| Maxtor                      | 38        | 51     | 0.52%   |
| OCZ                         | 33        | 45     | 0.45%   |
| Silicon Motion              | 28        | 34     | 0.39%   |
| JMicron Technology          | 25        | 27     | 0.34%   |
| Transcend                   | 24        | 46     | 0.33%   |
| Phison Electronics          | 24        | 26     | 0.33%   |
| Netac                       | 23        | 36     | 0.32%   |
| KIOXIA-EXCERIA              | 23        | 31     | 0.32%   |
| Kingston Technology Company | 22        | 29     | 0.3%    |
| A-DATA Technology           | 22        | 31     | 0.3%    |
| Unknown                     | 21        | 23     | 0.29%   |
| KingSpec                    | 20        | 26     | 0.28%   |
| Corsair                     | 20        | 25     | 0.28%   |
| LITEON                      | 19        | 20     | 0.26%   |
| KingDian                    | 17        | 20     | 0.23%   |
| USB30                       | 16        | 34     | 0.22%   |
| PNY                         | 16        | 26     | 0.22%   |
| Emtec                       | 16        | 20     | 0.22%   |
| Intenso                     | 14        | 21     | 0.19%   |
| Patriot                     | 12        | 19     | 0.17%   |
| Teclast                     | 10        | 10     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 265       | 3.32%   |
| Kingston SA400S37480G 480GB SSD                   | 118       | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB                    | 95        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                   | 85        | 1.06%   |
| Seagate ST500DM002-1BD142 500GB                   | 84        | 1.05%   |
| Kingston SV300S37A120G 120GB SSD                  | 72        | 0.9%    |
| Seagate ST3500418AS 500GB                         | 64        | 0.8%    |
| Samsung SSD 860 EVO 500GB                         | 60        | 0.75%   |
| Unknown MMC Card  64GB                            | 54        | 0.68%   |
| Unknown MMC Card  32GB                            | 50        | 0.63%   |
| Crucial CT500MX500SSD1 500GB                      | 49        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB                    | 48        | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB                    | 48        | 0.6%    |
| Samsung SSD 850 EVO 250GB                         | 47        | 0.59%   |
| Samsung SSD 850 EVO 500GB                         | 46        | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                   | 45        | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB                    | 44        | 0.55%   |
| Toshiba DT01ACA100 1TB                            | 43        | 0.54%   |
| Kingston SUV400S37240G 240GB SSD                  | 43        | 0.54%   |
| Toshiba MQ01ABD100 1TB                            | 42        | 0.53%   |
| Seagate ST9500325AS 500GB                         | 41        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 39        | 0.49%   |
| Seagate ST1000LM035-1RK172 970GB                  | 38        | 0.48%   |
| HGST HTS721010A9E630 1TB                          | 38        | 0.48%   |
| SanDisk SSD PLUS 480GB                            | 37        | 0.46%   |
| Samsung NVMe SSD Drive 512GB                      | 36        | 0.45%   |
| Samsung NVMe SSD Drive 500GB                      | 36        | 0.45%   |
| Toshiba MQ01ABF050 500GB                          | 34        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                     | 34        | 0.43%   |
| Seagate ST31000528AS 1TB                          | 34        | 0.43%   |
| Kingston SV300S37A240G 240GB SSD                  | 33        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                      | 32        | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 32        | 0.4%    |
| Unknown SD/MMC/MS PRO 249GB                       | 30        | 0.38%   |
| Unknown MMC Card  128GB                           | 30        | 0.38%   |
| Toshiba MQ01ABD050 500GB                          | 30        | 0.38%   |
| Intel NVMe SSD Drive 512GB                        | 30        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB                          | 29        | 0.36%   |
| Seagate Expansion 4TB                             | 29        | 0.36%   |
| Crucial CT480BX500SSD1 480GB                      | 29        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1226      | 1887   | 40.38%  |
| WDC                 | 792       | 1154   | 26.09%  |
| Toshiba             | 374       | 540    | 12.32%  |
| Hitachi             | 223       | 263    | 7.35%   |
| Samsung Electronics | 125       | 153    | 4.12%   |
| HGST                | 125       | 157    | 4.12%   |
| Fujitsu             | 43        | 49     | 1.42%   |
| Maxtor              | 33        | 44     | 1.09%   |
| Unknown             | 30        | 36     | 0.99%   |
| JMicron Technology  | 17        | 18     | 0.56%   |
| Apple               | 17        | 21     | 0.56%   |
| USB3.0              | 6         | 6      | 0.2%    |
| ASMT                | 5         | 9      | 0.16%   |
| Hewlett-Packard     | 3         | 4      | 0.1%    |
| Intenso             | 2         | 3      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM-207x            | 1         | 8      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| HPE                 | 1         | 2      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 745       | 1020   | 30.21%  |
| Samsung Electronics | 433       | 600    | 17.56%  |
| Crucial             | 250       | 350    | 10.14%  |
| SanDisk             | 229       | 290    | 9.29%   |
| WDC                 | 128       | 185    | 5.19%   |
| Toshiba             | 95        | 175    | 3.85%   |
| China               | 67        | 90     | 2.72%   |
| SK hynix            | 40        | 44     | 1.62%   |
| Intel               | 37        | 53     | 1.5%    |
| OCZ                 | 33        | 45     | 1.34%   |
| Micron Technology   | 33        | 42     | 1.34%   |
| Transcend           | 23        | 45     | 0.93%   |
| Netac               | 23        | 36     | 0.93%   |
| KingSpec            | 20        | 26     | 0.81%   |
| A-DATA Technology   | 19        | 28     | 0.77%   |
| LITEON              | 18        | 18     | 0.73%   |
| USB30               | 16        | 34     | 0.65%   |
| KIOXIA-EXCERIA      | 16        | 20     | 0.65%   |
| KingDian            | 16        | 19     | 0.65%   |
| Apple               | 15        | 18     | 0.61%   |
| Emtec               | 14        | 17     | 0.57%   |
| Intenso             | 12        | 16     | 0.49%   |
| Patriot             | 11        | 18     | 0.45%   |
| Teclast             | 10        | 10     | 0.41%   |
| PNY                 | 10        | 20     | 0.41%   |
| FORESEE             | 10        | 14     | 0.41%   |
| Unknown             | 10        | 10     | 0.41%   |
| Corsair             | 8         | 11     | 0.32%   |
| Drevo               | 7         | 9      | 0.28%   |
| LITEONIT            | 6         | 7      | 0.24%   |
| GOODRAM             | 6         | 8      | 0.24%   |
| BAITITON            | 6         | 6      | 0.24%   |
| Maxtor              | 5         | 7      | 0.2%    |
| Dogfish             | 5         | 5      | 0.2%    |
| SPCC                | 4         | 4      | 0.16%   |
| Hoodisk             | 4         | 5      | 0.16%   |
| Unknown             | 3         | 3      | 0.12%   |
| TCSUNBOW            | 3         | 3      | 0.12%   |
| Plextor             | 3         | 4      | 0.12%   |
| KingFast            | 3         | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2579      | 4367   | 39.87%  |
| SSD     | 2126      | 3405   | 32.87%  |
| NVMe    | 1425      | 1997   | 22.03%  |
| MMC     | 256       | 338    | 3.96%   |
| Unknown | 82        | 101    | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3750      | 7566   | 66.16%  |
| NVMe | 1421      | 1988   | 25.07%  |
| MMC  | 256       | 338    | 4.52%   |
| SAS  | 241       | 316    | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2990      | 4927   | 61.71%  |
| 0.51-1.0   | 1285      | 1890   | 26.52%  |
| 1.01-2.0   | 343       | 566    | 7.08%   |
| 3.01-4.0   | 106       | 163    | 2.19%   |
| 2.01-3.0   | 77        | 125    | 1.59%   |
| 4.01-10.0  | 41        | 91     | 0.85%   |
| 10.01-20.0 | 3         | 10     | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1465      | 27.71%  |
| 251-500        | 1237      | 23.4%   |
| 501-1000       | 702       | 13.28%  |
| 1-20           | 419       | 7.93%   |
| 1001-2000      | 361       | 6.83%   |
| 51-100         | 354       | 6.7%    |
| 21-50          | 224       | 4.24%   |
| More than 3000 | 207       | 3.92%   |
| 2001-3000      | 183       | 3.46%   |
| Unknown        | 135       | 2.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2146      | 39.15%  |
| 21-50          | 920       | 16.78%  |
| 101-250        | 706       | 12.88%  |
| 51-100         | 577       | 10.53%  |
| 251-500        | 409       | 7.46%   |
| 501-1000       | 286       | 5.22%   |
| 1001-2000      | 166       | 3.03%   |
| Unknown        | 135       | 2.46%   |
| More than 3000 | 76        | 1.39%   |
| 2001-3000      | 59        | 1.08%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 15        | 15     | 3.14%   |
| Seagate ST3500418AS 500GB          | 14        | 20     | 2.93%   |
| Kingston SV300S37A120G 120GB SSD   | 13        | 19     | 2.72%   |
| Seagate ST9500325AS 500GB          | 9         | 11     | 1.88%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 1.46%   |
| SanDisk SSD PLUS 480GB             | 7         | 9      | 1.46%   |
| Seagate ST3500320AS 500GB          | 6         | 9      | 1.26%   |
| Seagate ST31000528AS 1TB           | 6         | 7      | 1.26%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 6      | 1.05%   |
| HGST HTS545050A7E680 500GB         | 5         | 7      | 1.05%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 0.84%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 0.84%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 0.84%   |
| Seagate ST31500341AS 1TB           | 4         | 4      | 0.84%   |
| Seagate ST1000LM035-1RK172 970GB   | 4         | 4      | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 0.84%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 0.84%   |
| Kingston SUV400S37240G 240GB SSD   | 4         | 6      | 0.84%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 0.84%   |
| Drevo X1 SSD 120GB                 | 4         | 6      | 0.84%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 3         | 3      | 0.63%   |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.63%   |
| WDC WD20EARX-00PASB0 2TB           | 3         | 5      | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.63%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.63%   |
| Seagate ST3200822A 200GB           | 3         | 3      | 0.63%   |
| Seagate ST2000DL003-9VT166 2TB     | 3         | 4      | 0.63%   |
| Samsung Electronics HD501LJ 500GB  | 3         | 3      | 0.63%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 6      | 0.63%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.63%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.63%   |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.63%   |
| China G521N256GB                   | 3         | 4      | 0.63%   |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.42%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.42%   |
| WDC WD5000AAKS-402AA0 500GB        | 2         | 2      | 0.42%   |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.42%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.42%   |
| WDC WD3200BEKT-60V5T1 320GB        | 2         | 2      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 205    | 34.69%  |
| WDC                 | 82        | 102    | 17.56%  |
| Toshiba             | 32        | 36     | 6.85%   |
| Hitachi             | 32        | 34     | 6.85%   |
| Samsung Electronics | 31        | 33     | 6.64%   |
| Kingston            | 25        | 36     | 5.35%   |
| HGST                | 18        | 21     | 3.85%   |
| SanDisk             | 13        | 15     | 2.78%   |
| Crucial             | 11        | 13     | 2.36%   |
| Intel               | 10        | 11     | 2.14%   |
| Maxtor              | 9         | 9      | 1.93%   |
| Fujitsu             | 7         | 8      | 1.5%    |
| China               | 6         | 8      | 1.28%   |
| Drevo               | 5         | 7      | 1.07%   |
| SK hynix            | 3         | 3      | 0.64%   |
| OCZ                 | 3         | 3      | 0.64%   |
| Micron Technology   | 3         | 4      | 0.64%   |
| KingDian            | 2         | 2      | 0.43%   |
| Transcend           | 1         | 6      | 0.21%   |
| Patriot             | 1         | 1      | 0.21%   |
| Netac               | 1         | 1      | 0.21%   |
| Intenso             | 1         | 1      | 0.21%   |
| IBM                 | 1         | 1      | 0.21%   |
| Hypertec            | 1         | 1      | 0.21%   |
| HPE                 | 1         | 2      | 0.21%   |
| Dogfish             | 1         | 1      | 0.21%   |
| Corsair             | 1         | 1      | 0.21%   |
| ASMT                | 1         | 2      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |
| A-DATA Technology   | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 205    | 45.13%  |
| WDC                 | 80        | 100    | 22.28%  |
| Hitachi             | 32        | 34     | 8.91%   |
| Toshiba             | 27        | 31     | 7.52%   |
| Samsung Electronics | 19        | 21     | 5.29%   |
| HGST                | 18        | 21     | 5.01%   |
| Maxtor              | 9         | 9      | 2.51%   |
| Fujitsu             | 7         | 8      | 1.95%   |
| IBM                 | 1         | 1      | 0.28%   |
| HPE                 | 1         | 2      | 0.28%   |
| China               | 1         | 1      | 0.28%   |
| ASMT                | 1         | 2      | 0.28%   |
| Apple               | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 335       | 436    | 76.48%  |
| SSD  | 93        | 123    | 21.23%  |
| NVMe | 10        | 11     | 2.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 15.38%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 7.69%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 7.69%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 53.85%  |
| Samsung Electronics | 3         | 3      | 23.08%  |
| WDC                 | 1         | 1      | 7.69%   |
| Toshiba             | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3134      | 6302   | 58.02%  |
| Works    | 1834      | 3323   | 33.95%  |
| Malfunc  | 421       | 570    | 7.79%   |
| Failed   | 13        | 13     | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3367      | 55.53%  |
| AMD                              | 851       | 14.04%  |
| Samsung Electronics              | 467       | 7.7%    |
| SanDisk                          | 275       | 4.54%   |
| SK hynix                         | 117       | 1.93%   |
| Kingston Technology Company      | 106       | 1.75%   |
| Nvidia                           | 105       | 1.73%   |
| Phison Electronics               | 100       | 1.65%   |
| JMicron Technology               | 85        | 1.4%    |
| Micron Technology                | 82        | 1.35%   |
| ASMedia Technology               | 82        | 1.35%   |
| Micron/Crucial Technology        | 66        | 1.09%   |
| Marvell Technology Group         | 65        | 1.07%   |
| Toshiba America Info Systems     | 60        | 0.99%   |
| KIOXIA                           | 56        | 0.92%   |
| Silicon Motion                   | 37        | 0.61%   |
| VIA Technologies                 | 34        | 0.56%   |
| Silicon Integrated Systems [SiS] | 22        | 0.36%   |
| LSI Logic / Symbios Logic        | 14        | 0.23%   |
| Union Memory (Shenzhen)          | 10        | 0.16%   |
| Hewlett-Packard                  | 6         | 0.1%    |
| Apple                            | 6         | 0.1%    |
| Silicon Image                    | 5         | 0.08%   |
| Realtek Semiconductor            | 4         | 0.07%   |
| Broadcom / LSI                   | 4         | 0.07%   |
| ADATA Technology                 | 4         | 0.07%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| O2 Micro                         | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Adaptec                          | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Seagate Technology               | 2         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 600       | 8.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 258       | 3.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 251       | 3.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 246       | 3.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 152       | 2.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 146       | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 131       | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                         | 131       | 1.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 125       | 1.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 124       | 1.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 121       | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 119       | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 107       | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 98        | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 97        | 1.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 96        | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 96        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 93        | 1.31%   |
| Samsung NVMe SSD Controller 980                                                | 89        | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 89        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 88        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 88        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 81        | 1.14%   |
| Micron NVMe Storage Controller                                                 | 80        | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 80        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 79        | 1.11%   |
| Intel SATA Controller [RAID mode]                                              | 78        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 75        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 70        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 69        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 67        | 0.94%   |
| Intel SSD 660P Series                                                          | 64        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 64        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 60        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 54        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 54        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 53        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 53        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 50        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3534      | 56.99%  |
| NVMe | 1435      | 23.14%  |
| IDE  | 830       | 13.38%  |
| RAID | 382       | 6.16%   |
| SAS  | 11        | 0.18%   |
| SCSI | 9         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3844      | 77.52%  |
| AMD          | 1082      | 21.82%  |
| ARM          | 30        | 0.6%    |
| QUALCOMM     | 2         | 0.04%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 62        | 1.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 53        | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 42        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 41        | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 41        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 38        | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 36        | 0.72%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 35        | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 31        | 0.62%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 29        | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 28        | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 27        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.54%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 26        | 0.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 23        | 0.46%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 22        | 0.44%   |
| ARM Processor                                 | 22        | 0.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.4%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 20        | 0.4%    |
| AMD Custom APU 0405                           | 20        | 0.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 945       | 19.01%  |
| Intel Core i7           | 927       | 18.65%  |
| Intel Core i3           | 397       | 7.99%   |
| Other                   | 335       | 6.74%   |
| Intel Celeron           | 312       | 6.28%   |
| AMD Ryzen 5             | 266       | 5.35%   |
| Intel Core 2 Duo        | 245       | 4.93%   |
| AMD Ryzen 7             | 233       | 4.69%   |
| Intel Atom              | 145       | 2.92%   |
| Intel Xeon              | 107       | 2.15%   |
| Intel Pentium           | 94        | 1.89%   |
| Intel Pentium Dual-Core | 81        | 1.63%   |
| Intel Core 2 Quad       | 74        | 1.49%   |
| AMD FX                  | 60        | 1.21%   |
| Intel Pentium Dual      | 53        | 1.07%   |
| Intel Core 2            | 52        | 1.05%   |
| AMD Ryzen 9             | 46        | 0.93%   |
| AMD A4                  | 46        | 0.93%   |
| AMD Ryzen 3             | 43        | 0.87%   |
| AMD A6                  | 36        | 0.72%   |
| AMD A10                 | 35        | 0.7%    |
| Intel Genuine           | 34        | 0.68%   |
| AMD A8                  | 32        | 0.64%   |
| Intel Core i9           | 29        | 0.58%   |
| Intel Pentium 4         | 25        | 0.5%    |
| AMD Athlon 64 X2        | 24        | 0.48%   |
| AMD E1                  | 22        | 0.44%   |
| AMD Athlon II X2        | 22        | 0.44%   |
| AMD Athlon              | 20        | 0.4%    |
| AMD Phenom II X4        | 14        | 0.28%   |
| AMD E                   | 14        | 0.28%   |
| AMD Ryzen 7 PRO         | 11        | 0.22%   |
| Intel Pentium D         | 10        | 0.2%    |
| AMD Phenom              | 10        | 0.2%    |
| Intel Pentium Silver    | 9         | 0.18%   |
| Intel Pentium M         | 9         | 0.18%   |
| Intel Pentium Gold      | 8         | 0.16%   |
| Intel Celeron M         | 8         | 0.16%   |
| AMD Ryzen Threadripper  | 8         | 0.16%   |
| AMD Phenom II X6        | 8         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2036      | 40.92%  |
| 4       | 1758      | 35.33%  |
| 6       | 471       | 9.47%   |
| 8       | 350       | 7.03%   |
| 1       | 186       | 3.74%   |
| 12      | 58        | 1.17%   |
| 14      | 27        | 0.54%   |
| 10      | 24        | 0.48%   |
| 16      | 21        | 0.42%   |
| 3       | 21        | 0.42%   |
| Unknown | 13        | 0.26%   |
| 20      | 3         | 0.06%   |
| 64      | 2         | 0.04%   |
| 32      | 2         | 0.04%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4917      | 99.13%  |
| 2       | 40        | 0.81%   |
| Unknown | 3         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3109      | 62.52%  |
| 1       | 1850      | 37.2%   |
| Unknown | 13        | 0.26%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4774      | 95.71%  |
| Unknown        | 114       | 2.29%   |
| 32-bit         | 66        | 1.32%   |
| 64-bit         | 34        | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1059      | 20.59%  |
| 0x306c3    | 255       | 4.96%   |
| 0x206a7    | 238       | 4.63%   |
| 0x306a9    | 219       | 4.26%   |
| 0x1067a    | 180       | 3.5%    |
| 0x906ea    | 147       | 2.86%   |
| 0x806ea    | 123       | 2.39%   |
| 0x806c1    | 114       | 2.22%   |
| 0x506e3    | 111       | 2.16%   |
| 0x6fd      | 106       | 2.06%   |
| 0x806ec    | 102       | 1.98%   |
| 0x40651    | 102       | 1.98%   |
| 0x20655    | 97        | 1.89%   |
| 0x806e9    | 92        | 1.79%   |
| 0x406e3    | 90        | 1.75%   |
| 0x306d4    | 77        | 1.5%    |
| 0x906e9    | 76        | 1.48%   |
| 0x08108109 | 73        | 1.42%   |
| 0x30678    | 59        | 1.15%   |
| 0x10676    | 56        | 1.09%   |
| 0x6fb      | 53        | 1.03%   |
| 0x20652    | 51        | 0.99%   |
| 0x08701021 | 50        | 0.97%   |
| 0x0a50000c | 49        | 0.95%   |
| 0x706a1    | 46        | 0.89%   |
| 0x406c4    | 44        | 0.86%   |
| 0x0800820d | 44        | 0.86%   |
| 0x706e5    | 42        | 0.82%   |
| 0x506c9    | 42        | 0.82%   |
| 0xa0652    | 40        | 0.78%   |
| 0x06006705 | 37        | 0.72%   |
| 0x6f6      | 36        | 0.7%    |
| 0x08600106 | 36        | 0.7%    |
| 0x706a8    | 35        | 0.68%   |
| 0x08108102 | 35        | 0.68%   |
| 0x106ca    | 34        | 0.66%   |
| 0x06000852 | 33        | 0.64%   |
| 0x010000c8 | 33        | 0.64%   |
| 0x906ed    | 32        | 0.62%   |
| 0x806eb    | 32        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 778       | 15.65%  |
| Haswell          | 471       | 9.47%   |
| Penryn           | 302       | 6.08%   |
| SandyBridge      | 301       | 6.06%   |
| IvyBridge        | 265       | 5.33%   |
| Core             | 264       | 5.31%   |
| Skylake          | 248       | 4.99%   |
| Zen+             | 195       | 3.92%   |
| Zen 2            | 188       | 3.78%   |
| Westmere         | 177       | 3.56%   |
| Silvermont       | 171       | 3.44%   |
| TigerLake        | 156       | 3.14%   |
| Unknown          | 141       | 2.84%   |
| Zen 3            | 117       | 2.35%   |
| Broadwell        | 109       | 2.19%   |
| CometLake        | 107       | 2.15%   |
| Goldmont plus    | 98        | 1.97%   |
| Piledriver       | 90        | 1.81%   |
| K10              | 90        | 1.81%   |
| Zen              | 89        | 1.79%   |
| Icelake          | 76        | 1.53%   |
| Bonnell          | 72        | 1.45%   |
| Excavator        | 65        | 1.31%   |
| K8 Hammer        | 53        | 1.07%   |
| Goldmont         | 49        | 0.99%   |
| Nehalem          | 48        | 0.97%   |
| Alderlake Hybrid | 41        | 0.82%   |
| NetBurst         | 38        | 0.76%   |
| Puma             | 32        | 0.64%   |
| P6               | 30        | 0.6%    |
| Jaguar           | 27        | 0.54%   |
| Steamroller      | 26        | 0.52%   |
| Bobcat           | 23        | 0.46%   |
| Tremont          | 12        | 0.24%   |
| K10 Llano        | 10        | 0.2%    |
| Bulldozer        | 8         | 0.16%   |
| K8 & K10 hybrid  | 3         | 0.06%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2855      | 48.66%  |
| Nvidia                                       | 1715      | 29.23%  |
| AMD                                          | 1237      | 21.08%  |
| Matrox Electronics Systems                   | 22        | 0.37%   |
| Silicon Integrated Systems [SiS]             | 14        | 0.24%   |
| VIA Technologies                             | 11        | 0.19%   |
| ASPEED Technology                            | 10        | 0.17%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 206       | 3.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 150       | 2.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 135       | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 133       | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 124       | 2.05%   |
| Intel UHD Graphics 620                                                                   | 123       | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 119       | 1.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 103       | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 101       | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 99        | 1.63%   |
| Intel HD Graphics 620                                                                    | 97        | 1.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 95        | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 91        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 89        | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 89        | 1.47%   |
| AMD Renoir                                                                               | 89        | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 88        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 82        | 1.35%   |
| Intel HD Graphics 5500                                                                   | 78        | 1.29%   |
| Intel HD Graphics 530                                                                    | 77        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 76        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 71        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 69        | 1.14%   |
| Intel HD Graphics 630                                                                    | 69        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 67        | 1.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 66        | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 61        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 61        | 1.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 52        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 51        | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 49        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 0.79%   |
| Intel HD Graphics 500                                                                    | 47        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 46        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 46        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 45        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 43        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 40        | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 2034      | 40.7%   |
| 1 x AMD                | 973       | 19.47%  |
| 1 x Nvidia             | 952       | 19.05%  |
| Intel + Nvidia         | 655       | 13.11%  |
| Intel + AMD            | 100       | 2%      |
| AMD + Nvidia           | 91        | 1.82%   |
| 2 x AMD                | 73        | 1.46%   |
| Other                  | 36        | 0.72%   |
| 1 x Matrox             | 19        | 0.38%   |
| 2 x Nvidia             | 14        | 0.28%   |
| 1 x SiS                | 14        | 0.28%   |
| 1 x VIA                | 11        | 0.22%   |
| 2 x Intel              | 7         | 0.14%   |
| 1 x ASPEED             | 6         | 0.12%   |
| Nvidia + ASPEED        | 4         | 0.08%   |
| Nvidia + Matrox        | 3         | 0.06%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3997      | 79.27%  |
| Proprietary | 833       | 16.52%  |
| Unknown     | 212       | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2727      | 53.3%   |
| 1.01-2.0   | 683       | 13.35%  |
| 0.01-0.5   | 609       | 11.9%   |
| 3.01-4.0   | 383       | 7.49%   |
| 0.51-1.0   | 372       | 7.27%   |
| 7.01-8.0   | 181       | 3.54%   |
| 5.01-6.0   | 94        | 1.84%   |
| 2.01-3.0   | 30        | 0.59%   |
| 8.01-16.0  | 29        | 0.57%   |
| 16.01-24.0 | 8         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 622       | 11.74%  |
| AU Optronics            | 546       | 10.3%   |
| Chimei Innolux          | 511       | 9.64%   |
| LG Display              | 437       | 8.25%   |
| BOE                     | 382       | 7.21%   |
| Goldstar                | 369       | 6.96%   |
| Hewlett-Packard         | 264       | 4.98%   |
| Dell                    | 214       | 4.04%   |
| BenQ                    | 213       | 4.02%   |
| Acer                    | 184       | 3.47%   |
| Ancor Communications    | 153       | 2.89%   |
| Philips                 | 145       | 2.74%   |
| AOC                     | 111       | 2.09%   |
| Apple                   | 103       | 1.94%   |
| Chi Mei Optoelectronics | 97        | 1.83%   |
| Sharp                   | 92        | 1.74%   |
| Lenovo                  | 83        | 1.57%   |
| PANDA                   | 62        | 1.17%   |
| LG Electronics          | 55        | 1.04%   |
| Sony                    | 50        | 0.94%   |
| Unknown                 | 47        | 0.89%   |
| LG Philips              | 43        | 0.81%   |
| HannStar                | 41        | 0.77%   |
| ASUSTek Computer        | 35        | 0.66%   |
| ViewSonic               | 27        | 0.51%   |
| InfoVision              | 21        | 0.4%    |
| MSI                     | 19        | 0.36%   |
| CPT                     | 14        | 0.26%   |
| Eizo                    | 13        | 0.25%   |
| Valve                   | 11        | 0.21%   |
| Toshiba                 | 11        | 0.21%   |
| OEM                     | 11        | 0.21%   |
| Panasonic               | 10        | 0.19%   |
| NEC Computers           | 10        | 0.19%   |
| Fujitsu Siemens         | 10        | 0.19%   |
| CSO                     | 10        | 0.19%   |
| ___                     | 9         | 0.17%   |
| Vestel Elektronik       | 9         | 0.17%   |
| Packard Bell            | 9         | 0.17%   |
| Hitachi                 | 9         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 1.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 37        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 31        | 0.57%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 23        | 0.42%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 21        | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 19        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 17        | 0.31%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 16        | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 15        | 0.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 15        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 15        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.24%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 13        | 0.24%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch    | 13        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 12        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 12        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.22%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 11        | 0.2%    |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 11        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2196      | 43.5%   |
| 1366x768 (WXGA)    | 1039      | 20.58%  |
| 3840x2160 (4K)     | 236       | 4.68%   |
| 1280x1024 (SXGA)   | 214       | 4.24%   |
| 2560x1440 (QHD)    | 182       | 3.61%   |
| 1280x800 (WXGA)    | 165       | 3.27%   |
| 1680x1050 (WSXGA+) | 155       | 3.07%   |
| 1440x900 (WXGA+)   | 141       | 2.79%   |
| 1600x900 (HD+)     | 117       | 2.32%   |
| 1920x1200 (WUXGA)  | 86        | 1.7%    |
| Unknown            | 61        | 1.21%   |
| 2560x1080          | 57        | 1.13%   |
| 1360x768           | 47        | 0.93%   |
| 1024x600           | 43        | 0.85%   |
| 3440x1440          | 35        | 0.69%   |
| 2560x1600          | 28        | 0.55%   |
| 2160x1440          | 27        | 0.53%   |
| 1024x768 (XGA)     | 26        | 0.52%   |
| 800x1280           | 17        | 0.34%   |
| 3840x1080          | 17        | 0.34%   |
| 1600x1200          | 14        | 0.28%   |
| 2880x1800          | 13        | 0.26%   |
| 1920x540           | 13        | 0.26%   |
| 3200x1800 (QHD+)   | 8         | 0.16%   |
| 2288x1287          | 7         | 0.14%   |
| 3840x2400          | 6         | 0.12%   |
| 3200x1080          | 6         | 0.12%   |
| 1920x1280          | 5         | 0.1%    |
| 4480x1080          | 4         | 0.08%   |
| 2736x1824          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3360x1080          | 3         | 0.06%   |
| 2960x1050          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1400x1050          | 3         | 0.06%   |
| 7680x2160          | 2         | 0.04%   |
| 5760x2160          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1528      | 28.87%  |
| 13      | 402       | 7.6%    |
| 24      | 376       | 7.11%   |
| 21      | 376       | 7.11%   |
| 27      | 338       | 6.39%   |
| 23      | 306       | 5.78%   |
| Unknown | 304       | 5.74%   |
| 14      | 278       | 5.25%   |
| 17      | 277       | 5.23%   |
| 19      | 157       | 2.97%   |
| 18      | 125       | 2.36%   |
| 22      | 88        | 1.66%   |
| 34      | 82        | 1.55%   |
| 20      | 81        | 1.53%   |
| 31      | 76        | 1.44%   |
| 12      | 69        | 1.3%    |
| 10      | 54        | 1.02%   |
| 11      | 52        | 0.98%   |
| 84      | 43        | 0.81%   |
| 16      | 43        | 0.81%   |
| 25      | 25        | 0.47%   |
| 54      | 24        | 0.45%   |
| 32      | 24        | 0.45%   |
| 72      | 23        | 0.43%   |
| 26      | 22        | 0.42%   |
| 40      | 18        | 0.34%   |
| 7       | 11        | 0.21%   |
| 65      | 10        | 0.19%   |
| 28      | 8         | 0.15%   |
| 52      | 7         | 0.13%   |
| 46      | 7         | 0.13%   |
| 142     | 6         | 0.11%   |
| 48      | 5         | 0.09%   |
| 60      | 4         | 0.08%   |
| 36      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 38      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2079      | 40%     |
| 501-600        | 954       | 18.35%  |
| 401-500        | 743       | 14.29%  |
| 201-300        | 412       | 7.93%   |
| Unknown        | 304       | 5.85%   |
| 351-400        | 286       | 5.5%    |
| 601-700        | 122       | 2.35%   |
| 701-800        | 109       | 2.1%    |
| 1501-2000      | 68        | 1.31%   |
| 1001-1500      | 64        | 1.23%   |
| 801-900        | 29        | 0.56%   |
| 1-100          | 13        | 0.25%   |
| More than 2000 | 6         | 0.12%   |
| 901-1000       | 5         | 0.1%    |
| 101-200        | 4         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3514      | 73.32%  |
| 16/10   | 593       | 12.37%  |
| Unknown | 251       | 5.24%   |
| 5/4     | 197       | 4.11%   |
| 21/9    | 87        | 1.82%   |
| 3/2     | 58        | 1.21%   |
| 4/3     | 56        | 1.17%   |
| 0.67    | 11        | 0.23%   |
| 0.62    | 8         | 0.17%   |
| 1.00    | 6         | 0.13%   |
| 32/9    | 4         | 0.08%   |
| 6/5     | 3         | 0.06%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1531      | 29.16%  |
| 201-250        | 940       | 17.9%   |
| 81-90          | 489       | 9.31%   |
| 151-200        | 352       | 6.7%    |
| 301-350        | 347       | 6.61%   |
| Unknown        | 304       | 5.79%   |
| 141-150        | 221       | 4.21%   |
| 71-80          | 193       | 3.68%   |
| 351-500        | 190       | 3.62%   |
| More than 1000 | 127       | 2.42%   |
| 121-130        | 125       | 2.38%   |
| 251-300        | 119       | 2.27%   |
| 61-70          | 59        | 1.12%   |
| 41-50          | 54        | 1.03%   |
| 51-60          | 52        | 0.99%   |
| 501-1000       | 48        | 0.91%   |
| 131-140        | 35        | 0.67%   |
| 111-120        | 30        | 0.57%   |
| 91-100         | 18        | 0.34%   |
| 1-40           | 17        | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1777      | 34.82%  |
| 101-120       | 1401      | 27.45%  |
| 121-160       | 1194      | 23.39%  |
| Unknown       | 304       | 5.96%   |
| 161-240       | 255       | 5%      |
| 1-50          | 103       | 2.02%   |
| More than 240 | 70        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4028      | 79.29%  |
| 2     | 729       | 14.35%  |
| 0     | 233       | 4.59%   |
| 3     | 84        | 1.65%   |
| 4     | 6         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2834      | 37.76%  |
| Intel                             | 2135      | 28.45%  |
| Qualcomm Atheros                  | 930       | 12.39%  |
| Broadcom                          | 461       | 6.14%   |
| TP-Link                           | 122       | 1.63%   |
| Ralink Technology                 | 118       | 1.57%   |
| Marvell Technology Group          | 114       | 1.52%   |
| Broadcom Limited                  | 98        | 1.31%   |
| Nvidia                            | 88        | 1.17%   |
| Ralink                            | 79        | 1.05%   |
| MediaTek                          | 64        | 0.85%   |
| Qualcomm Atheros Communications   | 42        | 0.56%   |
| Xiaomi                            | 32        | 0.43%   |
| Samsung Electronics               | 29        | 0.39%   |
| ASIX Electronics                  | 28        | 0.37%   |
| D-Link                            | 23        | 0.31%   |
| Silicon Integrated Systems [SiS]  | 20        | 0.27%   |
| VIA Technologies                  | 18        | 0.24%   |
| D-Link System                     | 17        | 0.23%   |
| ASUSTek Computer                  | 17        | 0.23%   |
| DisplayLink                       | 15        | 0.2%    |
| Qualcomm                          | 14        | 0.19%   |
| JMicron Technology                | 14        | 0.19%   |
| Dell                              | 14        | 0.19%   |
| Sierra Wireless                   | 12        | 0.16%   |
| Lenovo                            | 12        | 0.16%   |
| Hewlett-Packard                   | 12        | 0.16%   |
| Ericsson Business Mobile Networks | 12        | 0.16%   |
| Belkin Components                 | 12        | 0.16%   |
| Microsoft                         | 9         | 0.12%   |
| Huawei Technologies               | 9         | 0.12%   |
| Edimax Technology                 | 7         | 0.09%   |
| ZyDAS                             | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| NetGear                           | 4         | 0.05%   |
| LSI                               | 4         | 0.05%   |
| Gemtek                            | 4         | 0.05%   |
| Attansic Technology               | 4         | 0.05%   |
| Arduino SA                        | 4         | 0.05%   |
| Accton Technology                 | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1924      | 22.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 308       | 3.56%   |
| Intel Wi-Fi 6 AX200                                                     | 196       | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 151       | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 129       | 1.49%   |
| Intel Wireless 8265 / 8275                                              | 124       | 1.43%   |
| Intel Wi-Fi 6 AX201                                                     | 119       | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 114       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 110       | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 1.27%   |
| Intel Wireless 7265                                                     | 106       | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 105       | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 103       | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 103       | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 95        | 1.1%    |
| Intel Wireless 3165                                                     | 92        | 1.06%   |
| Intel Ethernet Connection (2) I219-V                                    | 90        | 1.04%   |
| Intel I211 Gigabit Network Connection                                   | 84        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                       | 76        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 76        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 0.81%   |
| Intel Wireless 7260                                                     | 67        | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 57        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 47        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 45        | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 44        | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 43        | 0.5%    |
| Intel Wireless 8260                                                     | 43        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 0.49%   |
| Intel WiFi Link 5100                                                    | 42        | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 0.49%   |
| Intel Ethernet Connection I217-LM                                       | 41        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 0.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 41        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1602      | 40.34%  |
| Realtek Semiconductor                 | 757       | 19.06%  |
| Qualcomm Atheros                      | 714       | 17.98%  |
| Broadcom                              | 288       | 7.25%   |
| Ralink Technology                     | 118       | 2.97%   |
| TP-Link                               | 103       | 2.59%   |
| Ralink                                | 79        | 1.99%   |
| Broadcom Limited                      | 66        | 1.66%   |
| MediaTek                              | 62        | 1.56%   |
| Qualcomm Atheros Communications       | 42        | 1.06%   |
| D-Link                                | 23        | 0.58%   |
| ASUSTek Computer                      | 17        | 0.43%   |
| Belkin Components                     | 12        | 0.3%    |
| D-Link System                         | 11        | 0.28%   |
| Microsoft                             | 8         | 0.2%    |
| Dell                                  | 8         | 0.2%    |
| Edimax Technology                     | 7         | 0.18%   |
| Marvell Technology Group              | 6         | 0.15%   |
| ZyDAS                                 | 5         | 0.13%   |
| Sierra Wireless                       | 5         | 0.13%   |
| Qualcomm                              | 4         | 0.1%    |
| NetGear                               | 4         | 0.1%    |
| Hewlett-Packard                       | 4         | 0.1%    |
| Gemtek                                | 4         | 0.1%    |
| Texas Instruments                     | 3         | 0.08%   |
| Sitecom Europe                        | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| Accton Technology                     | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Standard Microsystems                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| AirTies Wireless Networks             | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |
| 3Com                                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 196       | 4.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 129       | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 124       | 3.1%    |
| Intel Wi-Fi 6 AX201                                                     | 119       | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 110       | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 2.75%   |
| Intel Wireless 7265                                                     | 106       | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 105       | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 103       | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 103       | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 95        | 2.38%   |
| Intel Wireless 3165                                                     | 92        | 2.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 76        | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 1.75%   |
| Intel Wireless 7260                                                     | 67        | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 57        | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 47        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 44        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 43        | 1.08%   |
| Intel Wireless 8260                                                     | 43        | 1.08%   |
| Intel WiFi Link 5100                                                    | 42        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 41        | 1.03%   |
| Intel Wireless 3160                                                     | 40        | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 39        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 39        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 37        | 0.93%   |
| Realtek 802.11ac NIC                                                    | 36        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 36        | 0.9%    |
| Intel Wireless-AC 9260                                                  | 34        | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 33        | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 33        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2511      | 55.92%  |
| Intel                                  | 972       | 21.65%  |
| Qualcomm Atheros                       | 297       | 6.61%   |
| Broadcom                               | 225       | 5.01%   |
| Marvell Technology Group               | 109       | 2.43%   |
| Nvidia                                 | 88        | 1.96%   |
| Broadcom Limited                       | 34        | 0.76%   |
| Xiaomi                                 | 31        | 0.69%   |
| ASIX Electronics                       | 28        | 0.62%   |
| TP-Link                                | 20        | 0.45%   |
| Silicon Integrated Systems [SiS]       | 20        | 0.45%   |
| Samsung Electronics                    | 19        | 0.42%   |
| VIA Technologies                       | 18        | 0.4%    |
| DisplayLink                            | 15        | 0.33%   |
| JMicron Technology                     | 14        | 0.31%   |
| Lenovo                                 | 12        | 0.27%   |
| Qualcomm                               | 10        | 0.22%   |
| Sierra Wireless                        | 7         | 0.16%   |
| D-Link System                          | 6         | 0.13%   |
| LSI                                    | 4         | 0.09%   |
| Huawei Technologies                    | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Attansic Technology                    | 4         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| IBM                                    | 3         | 0.07%   |
| Aquantia                               | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.04%   |
| MediaTek                               | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| Davicom Semiconductor                  | 2         | 0.04%   |
| ADMtek                                 | 2         | 0.04%   |
| Accton Technology                      | 2         | 0.04%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1924      | 42%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 308       | 6.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 151       | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 114       | 2.49%   |
| Intel Ethernet Connection (2) I219-V                              | 90        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 84        | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 76        | 1.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 40        | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 40        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 37        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 32        | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 31        | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 28        | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 25        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25        | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 25        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 25        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 24        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 22        | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 21        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 20        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4286      | 52.98%  |
| WiFi     | 3735      | 46.17%  |
| Modem    | 63        | 0.78%   |
| Unknown  | 6         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2835      | 54.8%   |
| Ethernet | 2337      | 45.18%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2671      | 53.6%   |
| 1     | 2098      | 42.1%   |
| 0     | 117       | 2.35%   |
| 3     | 73        | 1.46%   |
| 4     | 16        | 0.32%   |
| 6     | 4         | 0.08%   |
| 5     | 4         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4800      | 96.39%  |
| Yes  | 180       | 3.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1279      | 44.27%  |
| Realtek Semiconductor           | 334       | 11.56%  |
| Cambridge Silicon Radio         | 247       | 8.55%   |
| IMC Networks                    | 181       | 6.27%   |
| Qualcomm Atheros Communications | 156       | 5.4%    |
| Broadcom                        | 120       | 4.15%   |
| Apple                           | 115       | 3.98%   |
| Lite-On Technology              | 97        | 3.36%   |
| Foxconn / Hon Hai               | 89        | 3.08%   |
| ASUSTek Computer                | 53        | 1.83%   |
| Realtek                         | 39        | 1.35%   |
| Toshiba                         | 36        | 1.25%   |
| Dell                            | 29        | 1%      |
| Hewlett-Packard                 | 23        | 0.8%    |
| Ralink                          | 17        | 0.59%   |
| Alps Electric                   | 13        | 0.45%   |
| MediaTek                        | 9         | 0.31%   |
| Belkin Components               | 9         | 0.31%   |
| Integrated System Solution      | 8         | 0.28%   |
| Foxconn International           | 8         | 0.28%   |
| TP-Link                         | 6         | 0.21%   |
| Ralink Technology               | 4         | 0.14%   |
| Marvell Semiconductor           | 4         | 0.14%   |
| Edimax Technology               | 3         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.07%   |
| Roper                           | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 472       | 16.34%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 247       | 8.55%   |
| Realtek Bluetooth Radio                             | 235       | 8.13%   |
| Intel AX201 Bluetooth                               | 234       | 8.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 213       | 7.37%   |
| Intel AX200 Bluetooth                               | 189       | 6.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 101       | 3.5%    |
| IMC Networks Bluetooth Radio                        | 85        | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 62        | 2.15%   |
| IMC Networks Bluetooth Device                       | 51        | 1.77%   |
| Apple Bluetooth Host Controller                     | 50        | 1.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 46        | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 40        | 1.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.14%   |
| Intel AX210 Bluetooth                               | 32        | 1.11%   |
| Realtek 802.11ac WLAN Adapter                       | 28        | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 28        | 0.97%   |
| Intel Bluetooth Device                              | 27        | 0.93%   |
| IMC Networks Wireless_Device                        | 27        | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 0.87%   |
| Lite-On Bluetooth Device                            | 25        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 19        | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 18        | 0.62%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.59%   |
| Apple Bluetooth HCI                                 | 16        | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 12        | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.42%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.42%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.38%   |
| Realtek Bluetooth Radio                             | 11        | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3627      | 54.08%  |
| AMD                                  | 1308      | 19.5%   |
| Nvidia                               | 1173      | 17.49%  |
| C-Media Electronics                  | 108       | 1.61%   |
| Creative Labs                        | 38        | 0.57%   |
| Logitech                             | 37        | 0.55%   |
| Texas Instruments                    | 27        | 0.4%    |
| JMTek                                | 24        | 0.36%   |
| Silicon Integrated Systems [SiS]     | 22        | 0.33%   |
| VIA Technologies                     | 20        | 0.3%    |
| Plantronics                          | 20        | 0.3%    |
| GN Netcom                            | 20        | 0.3%    |
| Kingston Technology                  | 18        | 0.27%   |
| Corsair                              | 16        | 0.24%   |
| ASUSTek Computer                     | 15        | 0.22%   |
| Lenovo                               | 14        | 0.21%   |
| Focusrite-Novation                   | 13        | 0.19%   |
| Realtek Semiconductor                | 12        | 0.18%   |
| Creative Technology                  | 12        | 0.18%   |
| SteelSeries ApS                      | 11        | 0.16%   |
| Generalplus Technology               | 11        | 0.16%   |
| Sennheiser Communications            | 7         | 0.1%    |
| Dell                                 | 7         | 0.1%    |
| M-Audio                              | 6         | 0.09%   |
| Ensoniq                              | 6         | 0.09%   |
| BEHRINGER International              | 6         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.07%   |
| Hewlett-Packard                      | 5         | 0.07%   |
| Apple                                | 5         | 0.07%   |
| Yamaha                               | 4         | 0.06%   |
| Tenx Technology                      | 4         | 0.06%   |
| Razer USA                            | 4         | 0.06%   |
| Micro Star International             | 4         | 0.06%   |
| Blue Microphones                     | 4         | 0.06%   |
| XMOS                                 | 3         | 0.04%   |
| Sony                                 | 3         | 0.04%   |
| SAVITECH                             | 3         | 0.04%   |
| QinHeng Electronics                  | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |
| Guillemot                            | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 377       | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 338       | 4.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 277       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 276       | 3.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 260       | 3.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 227       | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 212       | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 195       | 2.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 193       | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 193       | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 158       | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 157       | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 156       | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 152       | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 148       | 1.87%   |
| AMD FCH Azalia Controller                                                  | 142       | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 135       | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 134       | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 134       | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 133       | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 119       | 1.5%    |
| Intel 200 Series PCH HD Audio                                              | 110       | 1.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 109       | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 106       | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 106       | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 103       | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 101       | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 98        | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 93        | 1.17%   |
| Nvidia High Definition Audio Controller                                    | 89        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 83        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 69        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 68        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 67        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 63        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 62        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 62        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 59        | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 58        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 52        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 641       | 22.49%  |
| SK hynix                                         | 455       | 15.96%  |
| Kingston                                         | 438       | 15.37%  |
| Unknown                                          | 308       | 10.81%  |
| Micron Technology                                | 270       | 9.47%   |
| Crucial                                          | 197       | 6.91%   |
| Corsair                                          | 124       | 4.35%   |
| G.Skill                                          | 85        | 2.98%   |
| Ramaxel Technology                               | 67        | 2.35%   |
| Unknown (ABCD)                                   | 39        | 1.37%   |
| Elpida                                           | 39        | 1.37%   |
| Nanya Technology                                 | 26        | 0.91%   |
| A-DATA Technology                                | 25        | 0.88%   |
| Silicon Power                                    | 14        | 0.49%   |
| Unknown                                          | 14        | 0.49%   |
| Goodram                                          | 12        | 0.42%   |
| Team                                             | 9         | 0.32%   |
| Transcend                                        | 8         | 0.28%   |
| Apacer                                           | 8         | 0.28%   |
| Unifosa                                          | 6         | 0.21%   |
| Wilk                                             | 4         | 0.14%   |
| Patriot                                          | 4         | 0.14%   |
| Kllisre                                          | 4         | 0.14%   |
| ASint Technology                                 | 4         | 0.14%   |
| Timetec                                          | 3         | 0.11%   |
| Atermiter                                        | 3         | 0.11%   |
| Toshiba                                          | 2         | 0.07%   |
| SHARETRONIC                                      | 2         | 0.07%   |
| Qimonda                                          | 2         | 0.07%   |
| PNY                                              | 2         | 0.07%   |
| Neo Forza                                        | 2         | 0.07%   |
| Micron/Elpida                                    | 2         | 0.07%   |
| KomputerBay                                      | 2         | 0.07%   |
| Innodisk                                         | 2         | 0.07%   |
| Exceleram                                        | 2         | 0.07%   |
| Avant                                            | 2         | 0.07%   |
| Unknown (AB)                                     | 1         | 0.04%   |
| Unknown (0x5846)                                 | 1         | 0.04%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.04%   |
| Unknown (0x0B45)                                 | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 32        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 25        | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 19        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.49%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 15        | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 14        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 0.46%   |
| Unknown                                                          | 14        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.42%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 13        | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 11        | 0.36%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.36%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 11        | 0.36%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.33%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 10        | 0.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.33%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1174      | 47.3%   |
| DDR3    | 791       | 31.87%  |
| DDR2    | 143       | 5.76%   |
| LPDDR4  | 101       | 4.07%   |
| Unknown | 77        | 3.1%    |
| SDRAM   | 76        | 3.06%   |
| LPDDR3  | 61        | 2.46%   |
| DDR5    | 28        | 1.13%   |
| DDR     | 18        | 0.73%   |
| DRAM    | 7         | 0.28%   |
| LPDDR5  | 6         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1454      | 58.61%  |
| DIMM         | 839       | 33.82%  |
| Row Of Chips | 172       | 6.93%   |
| Chip         | 9         | 0.36%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1028      | 38.2%   |
| 4096  | 740       | 27.5%   |
| 16384 | 373       | 13.86%  |
| 2048  | 361       | 13.42%  |
| 1024  | 117       | 4.35%   |
| 32768 | 57        | 2.12%   |
| 512   | 8         | 0.3%    |
| 65536 | 4         | 0.15%   |
| 256   | 2         | 0.07%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 496       | 18.42%  |
| 2667    | 397       | 14.75%  |
| 3200    | 386       | 14.34%  |
| 2400    | 217       | 8.06%   |
| 1333    | 180       | 6.69%   |
| 2133    | 135       | 5.01%   |
| 667     | 94        | 3.49%   |
| 1334    | 81        | 3.01%   |
| 800     | 75        | 2.79%   |
| 3600    | 65        | 2.41%   |
| 1867    | 59        | 2.19%   |
| Unknown | 59        | 2.19%   |
| 4267    | 36        | 1.34%   |
| 8400    | 33        | 1.23%   |
| 1067    | 30        | 1.11%   |
| 3466    | 26        | 0.97%   |
| 4800    | 23        | 0.85%   |
| 3266    | 22        | 0.82%   |
| 2933    | 20        | 0.74%   |
| 1866    | 20        | 0.74%   |
| 1066    | 20        | 0.74%   |
| 3400    | 19        | 0.71%   |
| 533     | 17        | 0.63%   |
| 2048    | 16        | 0.59%   |
| 3000    | 15        | 0.56%   |
| 3733    | 14        | 0.52%   |
| 4199    | 13        | 0.48%   |
| 2733    | 13        | 0.48%   |
| 2666    | 9         | 0.33%   |
| 6400    | 8         | 0.3%    |
| 2800    | 8         | 0.3%    |
| 3800    | 7         | 0.26%   |
| 4266    | 6         | 0.22%   |
| 1639    | 6         | 0.22%   |
| 400     | 6         | 0.22%   |
| 975     | 5         | 0.19%   |
| 5200    | 4         | 0.15%   |
| 3933    | 4         | 0.15%   |
| 3534    | 4         | 0.15%   |
| 3500    | 4         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 64        | 49.61%  |
| Brother Industries       | 23        | 17.83%  |
| Canon                    | 13        | 10.08%  |
| Samsung Electronics      | 9         | 6.98%   |
| Seiko Epson              | 8         | 6.2%    |
| Oki Data                 | 3         | 2.33%   |
| Dymo-CoStar              | 2         | 1.55%   |
| Ricoh                    | 1         | 0.78%   |
| Prolific Technology      | 1         | 0.78%   |
| Magic Control Technology | 1         | 0.78%   |
| Lexmark International    | 1         | 0.78%   |
| Kyocera                  | 1         | 0.78%   |
| Konica Minolta           | 1         | 0.78%   |
| Apple                    | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 3.85%   |
| Brother HL-2030 Laser Printer                   | 5         | 3.85%   |
| HP DeskJet 2620 All-in-One Printer              | 4         | 3.08%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.08%   |
| Oki Data USB Device                             | 3         | 2.31%   |
| HP LaserJet 1020                                | 3         | 2.31%   |
| HP ENVY 5540 series                             | 3         | 2.31%   |
| HP DeskJet F2492 All-in-One                     | 3         | 2.31%   |
| HP DeskJet 2700 series                          | 3         | 2.31%   |
| HP Deskjet 1050 J410                            | 3         | 2.31%   |
| Canon LiDE 400                                  | 3         | 2.31%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.54%   |
| Samsung M2070 Series                            | 2         | 1.54%   |
| HP LaserJet 1010                                | 2         | 1.54%   |
| HP ENVY 5000 series                             | 2         | 1.54%   |
| HP ENVY 4520 series                             | 2         | 1.54%   |
| HP DeskJet 5550                                 | 2         | 1.54%   |
| HP DeskJet 3630 series                          | 2         | 1.54%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.54%   |
| Brother Printer                                 | 2         | 1.54%   |
| Brother MFC-J5330DW                             | 2         | 1.54%   |
| Brother DCP-1510                                | 2         | 1.54%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.77%   |
| Seiko Epson XP-230 Series                       | 1         | 0.77%   |
| Seiko Epson XP-225 Series                       | 1         | 0.77%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.77%   |
| Seiko Epson Printer                             | 1         | 0.77%   |
| Seiko Epson L555 Series                         | 1         | 0.77%   |
| Seiko Epson L1300 Series                        | 1         | 0.77%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.77%   |
| Samsung SCX-4300 Series                         | 1         | 0.77%   |
| Samsung SCX-3400 Series                         | 1         | 0.77%   |
| Samsung SCX-3200 Series                         | 1         | 0.77%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.77%   |
| Samsung M267x 287x Series                       | 1         | 0.77%   |
| Ricoh SP 112                                    | 1         | 0.77%   |
| Prolific PL2305 Parallel Port                   | 1         | 0.77%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.77%   |
| Lexmark International B2236dw                   | 1         | 0.77%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.77%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 651       | 22.72%  |
| IMC Networks                           | 312       | 10.89%  |
| Realtek Semiconductor                  | 184       | 6.42%   |
| Microdia                               | 183       | 6.39%   |
| Bison Electronics                      | 137       | 4.78%   |
| Acer                                   | 134       | 4.68%   |
| Logitech                               | 133       | 4.64%   |
| Quanta                                 | 129       | 4.5%    |
| Sunplus Innovation Technology          | 126       | 4.4%    |
| Suyin                                  | 121       | 4.22%   |
| Cheng Uei Precision Industry (Foxlink) | 99        | 3.46%   |
| Syntek                                 | 80        | 2.79%   |
| Apple                                  | 80        | 2.79%   |
| Alcor Micro                            | 52        | 1.82%   |
| Lite-On Technology                     | 43        | 1.5%    |
| Luxvisions Innotech Limited            | 40        | 1.4%    |
| Ricoh                                  | 31        | 1.08%   |
| Silicon Motion                         | 21        | 0.73%   |
| Samsung Electronics                    | 21        | 0.73%   |
| Creative Technology                    | 18        | 0.63%   |
| Z-Star Microelectronics                | 17        | 0.59%   |
| Microsoft                              | 17        | 0.59%   |
| GEMBIRD                                | 14        | 0.49%   |
| Sonix Technology                       | 13        | 0.45%   |
| Generalplus Technology                 | 13        | 0.45%   |
| Lenovo                                 | 11        | 0.38%   |
| icSpring                               | 10        | 0.35%   |
| KYE Systems (Mouse Systems)            | 9         | 0.31%   |
| Importek                               | 9         | 0.31%   |
| ALi                                    | 9         | 0.31%   |
| Sunplus Technology                     | 8         | 0.28%   |
| Cubeternet                             | 8         | 0.28%   |
| ARC International                      | 8         | 0.28%   |
| Jieli Technology                       | 7         | 0.24%   |
| Intel                                  | 7         | 0.24%   |
| Genesys Logic                          | 7         | 0.24%   |
| SunplusIT                              | 6         | 0.21%   |
| Primax Electronics                     | 6         | 0.21%   |
| 2M UVC CAMERA                          | 6         | 0.21%   |
| Trust                                  | 5         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 84        | 2.92%   |
| Chicony HD WebCam                                       | 72        | 2.5%    |
| Chicony integrated camera                               | 69        | 2.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.33%   |
| Microdia Integrated_Webcam_HD                           | 62        | 2.15%   |
| Bison HD Webcam                                         | 51        | 1.77%   |
| IMC Networks Integrated Camera                          | 49        | 1.7%    |
| Acer Integrated Camera                                  | 45        | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                           | 42        | 1.46%   |
| Realtek Integrated_Webcam_HD                            | 35        | 1.21%   |
| Apple Built-in iSight                                   | 35        | 1.21%   |
| Logitech Webcam C270                                    | 33        | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 32        | 1.11%   |
| Syntek Integrated Camera                                | 31        | 1.08%   |
| Sunplus HD WebCam                                       | 31        | 1.08%   |
| Realtek USB Camera                                      | 30        | 1.04%   |
| Quanta HP TrueVision HD Camera                          | 30        | 1.04%   |
| Chicony EasyCamera                                      | 29        | 1.01%   |
| Microdia Webcam Vitade AF                               | 26        | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 0.9%    |
| Chicony USB 2.0 Camera                                  | 25        | 0.87%   |
| Chicony USB2.0 Camera                                   | 22        | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 21        | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                            | 20        | 0.69%   |
| Syntek EasyCamera                                       | 19        | 0.66%   |
| Chicony HP Truevision HD                                | 19        | 0.66%   |
| Bison HD Camera                                         | 19        | 0.66%   |
| Apple FaceTime HD Camera (Built-in)                     | 19        | 0.66%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.62%   |
| Lite-On Integrated Camera                               | 18        | 0.62%   |
| Chicony VGA Webcam                                      | 18        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)                 | 18        | 0.62%   |
| Chicony HP TrueVision HD Camera                         | 18        | 0.62%   |
| Chicony HP HD Camera                                    | 18        | 0.62%   |
| Bison Integrated Camera                                 | 18        | 0.62%   |
| Realtek Lenovo EasyCamera                               | 17        | 0.59%   |
| Logitech HD Pro Webcam C920                             | 17        | 0.59%   |
| IMC Networks ov9734_azurewave_camera                    | 17        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 17        | 0.59%   |
| Alcor Micro Asus Integrated Webcam                      | 17        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 125       | 30.64%  |
| Validity Sensors           | 93        | 22.79%  |
| Shenzhen Goodix Technology | 69        | 16.91%  |
| Elan Microelectronics      | 39        | 9.56%   |
| AuthenTec                  | 36        | 8.82%   |
| Upek                       | 26        | 6.37%   |
| LighTuning Technology      | 13        | 3.19%   |
| STMicroelectronics         | 7         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 50        | 12.25%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 36        | 8.82%   |
| Elan ELAN:Fingerprint                                                      | 35        | 8.58%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 7.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 5.15%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 3.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.7%    |
| Synaptics  WBDI                                                            | 10        | 2.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.21%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.96%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.72%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.47%   |
| AuthenTec AES1600                                                          | 6         | 1.47%   |
| Validity Sensors VFS491                                                    | 5         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.23%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.23%   |
| Synaptics WBDI                                                             | 5         | 1.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.23%   |
| AuthenTec AES2810                                                          | 5         | 1.23%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.23%   |
| Synaptics UWP WBDI                                                         | 4         | 0.98%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 0.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.98%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.98%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.74%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.74%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.74%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.49%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 71        | 34.63%  |
| Broadcom                  | 56        | 27.32%  |
| O2 Micro                  | 23        | 11.22%  |
| Lenovo                    | 9         | 4.39%   |
| Advanced Card Systems     | 8         | 3.9%    |
| Chicony Electronics       | 6         | 2.93%   |
| Realtek Semiconductor     | 5         | 2.44%   |
| Cherry                    | 5         | 2.44%   |
| C3PO                      | 5         | 2.44%   |
| Upek                      | 4         | 1.95%   |
| SCM Microsystems          | 3         | 1.46%   |
| Gemalto (was Gemplus)     | 3         | 1.46%   |
| OmniKey                   | 2         | 0.98%   |
| Hewlett-Packard           | 2         | 0.98%   |
| In Focus Systems          | 1         | 0.49%   |
| Fujitsu Siemens Computers | 1         | 0.49%   |
| Bit4id                    | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 67        | 32.68%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 10.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 9.76%   |
| Broadcom 5880                                                                | 16        | 7.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 4.88%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.39%   |
| Broadcom 58200                                                               | 9         | 4.39%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 2.93%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 2.93%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 2.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 1.95%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 1.95%   |
| C3PO LTC31v2                                                                 | 4         | 1.95%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.95%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.98%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.98%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 0.98%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.98%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.49%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.49%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.49%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.49%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.49%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.49%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.49%   |
| Bit4id miniLector-s                                                          | 1         | 0.49%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.49%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3708      | 72.89%  |
| 1     | 1095      | 21.53%  |
| 2     | 236       | 4.64%   |
| 3     | 31        | 0.61%   |
| 4     | 8         | 0.16%   |
| 5     | 5         | 0.1%    |
| 6     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 439       | 26.35%  |
| Fingerprint reader       | 399       | 23.95%  |
| Net/wireless             | 243       | 14.59%  |
| Chipcard                 | 166       | 9.96%   |
| Multimedia controller    | 103       | 6.18%   |
| Camera                   | 56        | 3.36%   |
| Communication controller | 53        | 3.18%   |
| Bluetooth                | 41        | 2.46%   |
| Unassigned class         | 31        | 1.86%   |
| Storage                  | 26        | 1.56%   |
| Sound                    | 25        | 1.5%    |
| Card reader              | 22        | 1.32%   |
| Net/ethernet             | 15        | 0.9%    |
| Network                  | 14        | 0.84%   |
| Flash memory             | 10        | 0.6%    |
| Modem                    | 9         | 0.54%   |
| Dvb card                 | 6         | 0.36%   |
| Firewire controller      | 4         | 0.24%   |
| Tv card                  | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

