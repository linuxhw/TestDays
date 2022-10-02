Linux in China - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in China.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/China/Desktop/README.md) and [notebooks](/Location/China/Notebook/README.md).

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

Total: 1412

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Xiaobao Nas I               | Soc         | [d74d764466](https://linux-hardware.org/?probe=d74d764466) | Oct 01, 2022 |
| OEM           | Unknown                     | Desktop     | [e5a425c399](https://linux-hardware.org/?probe=e5a425c399) | Sep 30, 2022 |
| Phytium       | FT2000/4                    | Server      | [c8aa4d1457](https://linux-hardware.org/?probe=c8aa4d1457) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [703687bcd7](https://linux-hardware.org/?probe=703687bcd7) | Sep 30, 2022 |
| OEM           | Unknown                     | Desktop     | [21b3a0929b](https://linux-hardware.org/?probe=21b3a0929b) | Sep 29, 2022 |
| OEM           | Unknown                     | Desktop     | [68b7e03b06](https://linux-hardware.org/?probe=68b7e03b06) | Sep 29, 2022 |
| Phytium       | FT2000/4                    | Server      | [ff17710900](https://linux-hardware.org/?probe=ff17710900) | Sep 29, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Timi          | TM1612                      | Notebook    | [ad37b74e1e](https://linux-hardware.org/?probe=ad37b74e1e) | Sep 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2A... | Notebook    | [ce132fc63e](https://linux-hardware.org/?probe=ce132fc63e) | Sep 27, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [2cc7eefe57](https://linux-hardware.org/?probe=2cc7eefe57) | Sep 26, 2022 |
| AZW           | SER V01                     | Mini pc     | [b6337c3dc4](https://linux-hardware.org/?probe=b6337c3dc4) | Sep 26, 2022 |
| Timi          | TM1612                      | Notebook    | [a7c23ad10b](https://linux-hardware.org/?probe=a7c23ad10b) | Sep 26, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [5cff3798b0](https://linux-hardware.org/?probe=5cff3798b0) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [fabe173a5d](https://linux-hardware.org/?probe=fabe173a5d) | Sep 25, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f35b53ca7c](https://linux-hardware.org/?probe=f35b53ca7c) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| NEC Comput... | PC-VK25LCZDM                | Notebook    | [97ab1f723e](https://linux-hardware.org/?probe=97ab1f723e) | Sep 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [aa0a31a88d](https://linux-hardware.org/?probe=aa0a31a88d) | Sep 23, 2022 |
| Mbenben       | Mai II                      | Notebook    | [2cfb10385b](https://linux-hardware.org/?probe=2cfb10385b) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| Inspur        | CE520F                      | Soc         | [b8ea59e9f8](https://linux-hardware.org/?probe=b8ea59e9f8) | Sep 21, 2022 |
| Timi          | TM1612                      | Notebook    | [3d9866e9ff](https://linux-hardware.org/?probe=3d9866e9ff) | Sep 20, 2022 |
| ASRock        | E3V5 Performance Gaming/... | Desktop     | [3653dbd804](https://linux-hardware.org/?probe=3653dbd804) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| GreatWall     | Unknown                     | Notebook    | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| GreatWall     | TN140A2                     | Notebook    | [2c4ddb8e4b](https://linux-hardware.org/?probe=2c4ddb8e4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | Notebook    | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| AZW           | GK55                        | Desktop     | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| Lenovo        | ThinkPad E480 20KNA040CD    | Notebook    | [8cd233ffbb](https://linux-hardware.org/?probe=8cd233ffbb) | Sep 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [fab82ec455](https://linux-hardware.org/?probe=fab82ec455) | Sep 18, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| Timi          | TM1604                      | Notebook    | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [1b7cb7f0d2](https://linux-hardware.org/?probe=1b7cb7f0d2) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [0ac056f016](https://linux-hardware.org/?probe=0ac056f016) | Sep 14, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [81ebde1d65](https://linux-hardware.org/?probe=81ebde1d65) | Sep 13, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [2de3999743](https://linux-hardware.org/?probe=2de3999743) | Sep 13, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [d666daaeb2](https://linux-hardware.org/?probe=d666daaeb2) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Unknown       | Unknown                     | Other       | [abccb6d05a](https://linux-hardware.org/?probe=abccb6d05a) | Sep 12, 2022 |
| Unknown       | Unknown                     | Other       | [1e94b50834](https://linux-hardware.org/?probe=1e94b50834) | Sep 12, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9f244f4236](https://linux-hardware.org/?probe=9f244f4236) | Sep 12, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| Colorful T... | H510M-D M.2 V20 V20         | Desktop     | [9b25859acf](https://linux-hardware.org/?probe=9b25859acf) | Sep 11, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [697d152bcc](https://linux-hardware.org/?probe=697d152bcc) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| ONDA          | M3 miniPC VER               | Desktop     | [40f73e6e82](https://linux-hardware.org/?probe=40f73e6e82) | Sep 07, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| Dell          | Precision 3571              | Notebook    | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Timi          | TM1709                      | Notebook    | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E450 20DCA087CD    | Notebook    | [26928f83da](https://linux-hardware.org/?probe=26928f83da) | Sep 04, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [a20f64b93b](https://linux-hardware.org/?probe=a20f64b93b) | Sep 02, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | Notebook    | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Dell          | Precision 7720              | Notebook    | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [3c6266b13d](https://linux-hardware.org/?probe=3c6266b13d) | Aug 23, 2022 |
| retsamarre... | Unknown                     | Desktop     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | Desktop     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c0372aaa91](https://linux-hardware.org/?probe=c0372aaa91) | Aug 22, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [be6beefb03](https://linux-hardware.org/?probe=be6beefb03) | Aug 22, 2022 |
| Lenovo        | 36FB SDK0L77769 WIN 3423... | All in one  | [c65b675fc8](https://linux-hardware.org/?probe=c65b675fc8) | Aug 22, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| BBEN          | G16                         | Notebook    | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| Biostar       | B550M-SILVER                | Desktop     | [d3a371bce6](https://linux-hardware.org/?probe=d3a371bce6) | Aug 20, 2022 |
| Lenovo        | 3102 SDK0L77767 WIN 3423... | Desktop     | [5d884c320f](https://linux-hardware.org/?probe=5d884c320f) | Aug 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [058273fa11](https://linux-hardware.org/?probe=058273fa11) | Aug 14, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [baf348cae9](https://linux-hardware.org/?probe=baf348cae9) | Aug 12, 2022 |
| HP            | 8183                        | Desktop     | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| HP            | 8183                        | Desktop     | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| Timi          | TM1709                      | Notebook    | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Unknown       | Unknown                     | Other       | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [1d8eaa7564](https://linux-hardware.org/?probe=1d8eaa7564) | Aug 08, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d2ea1146a](https://linux-hardware.org/?probe=7d2ea1146a) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [c1d23f2838](https://linux-hardware.org/?probe=c1d23f2838) | Aug 06, 2022 |
| Unknown       | Unknown                     | Other       | [8330cc179c](https://linux-hardware.org/?probe=8330cc179c) | Aug 04, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [28eaeed6dd](https://linux-hardware.org/?probe=28eaeed6dd) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | Notebook    | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | 102F NO DPK                 | Desktop     | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | Desktop     | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [052379f89e](https://linux-hardware.org/?probe=052379f89e) | Aug 04, 2022 |
| Google        | Dratini                     | Notebook    | [e61c92a95b](https://linux-hardware.org/?probe=e61c92a95b) | Aug 04, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [68434806c3](https://linux-hardware.org/?probe=68434806c3) | Aug 03, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [7716e60398](https://linux-hardware.org/?probe=7716e60398) | Aug 03, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [d01d805978](https://linux-hardware.org/?probe=d01d805978) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [dd8b9dc221](https://linux-hardware.org/?probe=dd8b9dc221) | Aug 02, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [20ff37511f](https://linux-hardware.org/?probe=20ff37511f) | Jul 30, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [08a5cff3a6](https://linux-hardware.org/?probe=08a5cff3a6) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | Desktop     | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [a0a4abeb19](https://linux-hardware.org/?probe=a0a4abeb19) | Jul 28, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [2ed7d049e7](https://linux-hardware.org/?probe=2ed7d049e7) | Jul 27, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [a8dc9cfc07](https://linux-hardware.org/?probe=a8dc9cfc07) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| Phytium       | D2000                       | Server      | [7e0be651b1](https://linux-hardware.org/?probe=7e0be651b1) | Jul 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [52764ae22f](https://linux-hardware.org/?probe=52764ae22f) | Jul 26, 2022 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [ce9121a53b](https://linux-hardware.org/?probe=ce9121a53b) | Jul 25, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5e4ca4abd6](https://linux-hardware.org/?probe=5e4ca4abd6) | Jul 23, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | Desktop     | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| X79-1356      | Unknown                     | Desktop     | [2db70d0471](https://linux-hardware.org/?probe=2db70d0471) | Jul 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7a5b89e10c](https://linux-hardware.org/?probe=7a5b89e10c) | Jul 22, 2022 |
| Supermicro    | X11DPi-N                    | Server      | [38ae00936b](https://linux-hardware.org/?probe=38ae00936b) | Jul 22, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [1a0ea0050f](https://linux-hardware.org/?probe=1a0ea0050f) | Jul 22, 2022 |
| Lenovo        | NOK                         | Desktop     | [a47a727578](https://linux-hardware.org/?probe=a47a727578) | Jul 22, 2022 |
| METAPHYUNI    | MetamechBook                | Notebook    | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [f2bfdb1f13](https://linux-hardware.org/?probe=f2bfdb1f13) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6ff44b9490](https://linux-hardware.org/?probe=6ff44b9490) | Jul 15, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [92c267f273](https://linux-hardware.org/?probe=92c267f273) | Jul 15, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [845432a1d3](https://linux-hardware.org/?probe=845432a1d3) | Jul 15, 2022 |
| Lenovo        | V470 HuronRiver Platform    | Notebook    | [021fb24a0a](https://linux-hardware.org/?probe=021fb24a0a) | Jul 14, 2022 |
| Lenovo        | V470 HuronRiver Platform    | Notebook    | [f3b112e72a](https://linux-hardware.org/?probe=f3b112e72a) | Jul 14, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| HP            | 829E                        | Mini pc     | [27c2c68afb](https://linux-hardware.org/?probe=27c2c68afb) | Jul 13, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [3ae3afeece](https://linux-hardware.org/?probe=3ae3afeece) | Jul 13, 2022 |
| MSI           | Z370-OC PRO                 | Desktop     | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| Colorful T... | H310M-T PRO V21             | Desktop     | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| Fujitsu       | FMVNP7HER                   | Notebook    | [e87161bce7](https://linux-hardware.org/?probe=e87161bce7) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [179ad71f6a](https://linux-hardware.org/?probe=179ad71f6a) | Jul 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [7cfc308ed6](https://linux-hardware.org/?probe=7cfc308ed6) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [15b290d046](https://linux-hardware.org/?probe=15b290d046) | Jul 07, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [dc3ab840d6](https://linux-hardware.org/?probe=dc3ab840d6) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7b1c72c3e7](https://linux-hardware.org/?probe=7b1c72c3e7) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [ad60f0abf2](https://linux-hardware.org/?probe=ad60f0abf2) | Jul 04, 2022 |
| Dell          | Vostro 3549                 | Notebook    | [d23ff685fc](https://linux-hardware.org/?probe=d23ff685fc) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [253c441703](https://linux-hardware.org/?probe=253c441703) | Jul 02, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| MSI           | Z68A-GD80                   | Desktop     | [2e2ca703b0](https://linux-hardware.org/?probe=2e2ca703b0) | Jun 30, 2022 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [4b2106c800](https://linux-hardware.org/?probe=4b2106c800) | Jun 29, 2022 |
| Gigabyte      | EP45-UD3                    | Desktop     | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1a50f7c080](https://linux-hardware.org/?probe=1a50f7c080) | Jun 27, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| Dell          | Precision 3541              | Notebook    | [816c91b81b](https://linux-hardware.org/?probe=816c91b81b) | Jun 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eaf51fc79f](https://linux-hardware.org/?probe=eaf51fc79f) | Jun 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| IPASON        | SMN86A                      | Notebook    | [834382148b](https://linux-hardware.org/?probe=834382148b) | Jun 21, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [8b520f803c](https://linux-hardware.org/?probe=8b520f803c) | Jun 21, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [385b65c320](https://linux-hardware.org/?probe=385b65c320) | Jun 19, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [fb120ddb6d](https://linux-hardware.org/?probe=fb120ddb6d) | Jun 19, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [43ddcf21fb](https://linux-hardware.org/?probe=43ddcf21fb) | Jun 17, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [8d56f09226](https://linux-hardware.org/?probe=8d56f09226) | Jun 17, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| Timi          | TM1701                      | Notebook    | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Timi          | A7S                         | Notebook    | [a43809f0a8](https://linux-hardware.org/?probe=a43809f0a8) | Jun 12, 2022 |
| Lenovo        | MIIX710-12IKB 80W1          | Tablet      | [50d3528425](https://linux-hardware.org/?probe=50d3528425) | Jun 12, 2022 |
| Lenovo        | MIIX710-12IKB 80W1          | Tablet      | [6e29236ae6](https://linux-hardware.org/?probe=6e29236ae6) | Jun 11, 2022 |
| Acer          | Aspire T5000                | Notebook    | [38e164657d](https://linux-hardware.org/?probe=38e164657d) | Jun 11, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [6e70632a8c](https://linux-hardware.org/?probe=6e70632a8c) | Jun 10, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Unknown       | Unknown                     | Other       | [d1d5741aff](https://linux-hardware.org/?probe=d1d5741aff) | Jun 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [96dfe73713](https://linux-hardware.org/?probe=96dfe73713) | Jun 07, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [ecef8fb98e](https://linux-hardware.org/?probe=ecef8fb98e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [5f55de3d8e](https://linux-hardware.org/?probe=5f55de3d8e) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [db08be8e6c](https://linux-hardware.org/?probe=db08be8e6c) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [818930c012](https://linux-hardware.org/?probe=818930c012) | Jun 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c36218f66](https://linux-hardware.org/?probe=4c36218f66) | Jun 04, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [a9c714d138](https://linux-hardware.org/?probe=a9c714d138) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| Acer          | Aspire T5000                | Notebook    | [55aaebdab5](https://linux-hardware.org/?probe=55aaebdab5) | May 31, 2022 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4698d909e](https://linux-hardware.org/?probe=d4698d909e) | May 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2855e4c95](https://linux-hardware.org/?probe=e2855e4c95) | May 31, 2022 |
| Acer          | Aspire T5000                | Notebook    | [7bdeb5fb3b](https://linux-hardware.org/?probe=7bdeb5fb3b) | May 31, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [3d58c27cd7](https://linux-hardware.org/?probe=3d58c27cd7) | May 31, 2022 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [63eab4a6b5](https://linux-hardware.org/?probe=63eab4a6b5) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [24a7b3121f](https://linux-hardware.org/?probe=24a7b3121f) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [5e77f9d2f9](https://linux-hardware.org/?probe=5e77f9d2f9) | May 29, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [3ddc17645b](https://linux-hardware.org/?probe=3ddc17645b) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1da299e36e](https://linux-hardware.org/?probe=1da299e36e) | May 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [91306ce19f](https://linux-hardware.org/?probe=91306ce19f) | May 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [114a036605](https://linux-hardware.org/?probe=114a036605) | May 28, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [fe6eb17434](https://linux-hardware.org/?probe=fe6eb17434) | May 25, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c0fe1740e0](https://linux-hardware.org/?probe=c0fe1740e0) | May 25, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| Dell          | Latitude 5300               | Notebook    | [b2e8f91f15](https://linux-hardware.org/?probe=b2e8f91f15) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [1ebb900517](https://linux-hardware.org/?probe=1ebb900517) | May 22, 2022 |
| Dell          | Latitude 3490               | Notebook    | [36a2ce11ef](https://linux-hardware.org/?probe=36a2ce11ef) | May 22, 2022 |
| Google        | Atlas                       | Notebook    | [d9406ed20d](https://linux-hardware.org/?probe=d9406ed20d) | May 21, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| Lenovo        | NOK                         | Desktop     | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [a60048a58a](https://linux-hardware.org/?probe=a60048a58a) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | Notebook    | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [e5c6c46d14](https://linux-hardware.org/?probe=e5c6c46d14) | May 18, 2022 |
| MECHREVO      | X10Ti-S Series GM7MPHS      | Notebook    | [3af043f369](https://linux-hardware.org/?probe=3af043f369) | May 17, 2022 |
| MAXSUN        | MS-M3A78EL                  | Desktop     | [98d8c5a6ee](https://linux-hardware.org/?probe=98d8c5a6ee) | May 14, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [2b7a0725f0](https://linux-hardware.org/?probe=2b7a0725f0) | May 14, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | Notebook    | [a4ba7cbcfa](https://linux-hardware.org/?probe=a4ba7cbcfa) | May 13, 2022 |
| Google        | Atlas                       | Notebook    | [ae85df2f65](https://linux-hardware.org/?probe=ae85df2f65) | May 12, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [b0db2e2b60](https://linux-hardware.org/?probe=b0db2e2b60) | May 11, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [f62715aee5](https://linux-hardware.org/?probe=f62715aee5) | May 11, 2022 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [3c126b8a1d](https://linux-hardware.org/?probe=3c126b8a1d) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [428f653301](https://linux-hardware.org/?probe=428f653301) | May 05, 2022 |
| Timi          | Redmi G                     | Notebook    | [a2738a4d6e](https://linux-hardware.org/?probe=a2738a4d6e) | May 05, 2022 |
| Dell          | Latitude 7420               | Notebook    | [7fd2239abb](https://linux-hardware.org/?probe=7fd2239abb) | May 05, 2022 |
| Google        | Atlas                       | Notebook    | [dce87f3691](https://linux-hardware.org/?probe=dce87f3691) | May 05, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| Dell          | Latitude 5300               | Notebook    | [fa0246b764](https://linux-hardware.org/?probe=fa0246b764) | May 04, 2022 |
| Dell          | Precision 3541              | Notebook    | [feaee0b7ff](https://linux-hardware.org/?probe=feaee0b7ff) | May 04, 2022 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [b812cd9eb1](https://linux-hardware.org/?probe=b812cd9eb1) | May 04, 2022 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [690c12e995](https://linux-hardware.org/?probe=690c12e995) | May 03, 2022 |
| HP            | G42                         | Notebook    | [6ee2b19fc7](https://linux-hardware.org/?probe=6ee2b19fc7) | May 01, 2022 |
| HP            | G42                         | Notebook    | [731ba8d968](https://linux-hardware.org/?probe=731ba8d968) | May 01, 2022 |
| HP            | G42                         | Notebook    | [e23740df6e](https://linux-hardware.org/?probe=e23740df6e) | Apr 30, 2022 |
| HP            | G42                         | Notebook    | [f6ca4559f5](https://linux-hardware.org/?probe=f6ca4559f5) | Apr 30, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [0c0af6919d](https://linux-hardware.org/?probe=0c0af6919d) | Apr 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ff9b46fd29](https://linux-hardware.org/?probe=ff9b46fd29) | Apr 29, 2022 |
| OEM           | V1.0                        | Desktop     | [167ee50568](https://linux-hardware.org/?probe=167ee50568) | Apr 29, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [8e5289a5e7](https://linux-hardware.org/?probe=8e5289a5e7) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Lenovo        | AILZx                       | Notebook    | [efa15d667f](https://linux-hardware.org/?probe=efa15d667f) | Apr 26, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [07ccc93cd4](https://linux-hardware.org/?probe=07ccc93cd4) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Timi          | TM1612                      | Notebook    | [9e6b6f4737](https://linux-hardware.org/?probe=9e6b6f4737) | Apr 24, 2022 |
| GreatWall     | TN140A2                     | Notebook    | [69043361cf](https://linux-hardware.org/?probe=69043361cf) | Apr 24, 2022 |
| Dell          | Latitude 5290               | Notebook    | [e373cb6fa1](https://linux-hardware.org/?probe=e373cb6fa1) | Apr 23, 2022 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5f78518f42](https://linux-hardware.org/?probe=5f78518f42) | Apr 21, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [c4561b1073](https://linux-hardware.org/?probe=c4561b1073) | Apr 18, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3faf048414](https://linux-hardware.org/?probe=3faf048414) | Apr 18, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| J&W           | J1900T                      | Desktop     | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e29970db9c](https://linux-hardware.org/?probe=e29970db9c) | Apr 16, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [7e346154a5](https://linux-hardware.org/?probe=7e346154a5) | Apr 16, 2022 |
| Timi          | A34                         | Notebook    | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| Unknown       | Xiaobao Nas I               | Soc         | [0acc620cac](https://linux-hardware.org/?probe=0acc620cac) | Apr 13, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | Desktop     | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | Notebook    | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [e8e6eefea7](https://linux-hardware.org/?probe=e8e6eefea7) | Apr 09, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [10654de5c8](https://linux-hardware.org/?probe=10654de5c8) | Apr 08, 2022 |
| HP            | Tablet 11-be0xxx            | Tablet      | [e3bcbaf593](https://linux-hardware.org/?probe=e3bcbaf593) | Apr 08, 2022 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [60cd34cb85](https://linux-hardware.org/?probe=60cd34cb85) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Lenovo        | ThinkPad S2 5th Gen 20R7... | Notebook    | [4e1cbba139](https://linux-hardware.org/?probe=4e1cbba139) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| Timi          | TM1701                      | Notebook    | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| Lenovo        | ThinkPad L470 20J5A240CD    | Notebook    | [2c7d1c1f02](https://linux-hardware.org/?probe=2c7d1c1f02) | Apr 04, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [9c1fd6c304](https://linux-hardware.org/?probe=9c1fd6c304) | Apr 04, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [f1f8a33de1](https://linux-hardware.org/?probe=f1f8a33de1) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | Desktop     | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| Gigabyte      | P65                         | Notebook    | [28a10c32cf](https://linux-hardware.org/?probe=28a10c32cf) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | Desktop     | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| MECHREVO      | X10 Pro Series GM7TG8S      | Notebook    | [eceb9b69ed](https://linux-hardware.org/?probe=eceb9b69ed) | Apr 01, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [802940c8ef](https://linux-hardware.org/?probe=802940c8ef) | Mar 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [51f7153768](https://linux-hardware.org/?probe=51f7153768) | Mar 30, 2022 |
| Gigabyte      | AERO 15WV8                  | Notebook    | [8fdae867c0](https://linux-hardware.org/?probe=8fdae867c0) | Mar 30, 2022 |
| Unknown       | X133                        | Notebook    | [996dfaa50f](https://linux-hardware.org/?probe=996dfaa50f) | Mar 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [b9bbb89cca](https://linux-hardware.org/?probe=b9bbb89cca) | Mar 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [6385010257](https://linux-hardware.org/?probe=6385010257) | Mar 28, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | Notebook    | [f760bbcc2f](https://linux-hardware.org/?probe=f760bbcc2f) | Mar 27, 2022 |
| Lenovo        | ThinkPad R400 2784A48       | Notebook    | [b7093f8912](https://linux-hardware.org/?probe=b7093f8912) | Mar 27, 2022 |
| Acer          | Swift SF314-510G            | Notebook    | [a105ea5158](https://linux-hardware.org/?probe=a105ea5158) | Mar 27, 2022 |
| Inspur        | NF5270M3                    | Desktop     | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | Desktop     | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | Notebook    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Timi          | A7S                         | Notebook    | [c39211692e](https://linux-hardware.org/?probe=c39211692e) | Mar 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| Dell          | 0D61XP A02                  | Server      | [87f57e757f](https://linux-hardware.org/?probe=87f57e757f) | Mar 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4A... | Notebook    | [a257719dcf](https://linux-hardware.org/?probe=a257719dcf) | Mar 23, 2022 |
| Dell          | 0NT78X A08                  | Server      | [99cdcd7a9d](https://linux-hardware.org/?probe=99cdcd7a9d) | Mar 23, 2022 |
| HUAWEI        | FRD-WX9                     | Notebook    | [e027a60ac6](https://linux-hardware.org/?probe=e027a60ac6) | Mar 23, 2022 |
| IBM           | Unknown                     | Notebook    | [2bcbb8a946](https://linux-hardware.org/?probe=2bcbb8a946) | Mar 21, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [c99fae499f](https://linux-hardware.org/?probe=c99fae499f) | Mar 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [ee813d0051](https://linux-hardware.org/?probe=ee813d0051) | Mar 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [6adea9d280](https://linux-hardware.org/?probe=6adea9d280) | Mar 19, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [c06992ac2b](https://linux-hardware.org/?probe=c06992ac2b) | Mar 18, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [cddad9e5c8](https://linux-hardware.org/?probe=cddad9e5c8) | Mar 17, 2022 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [7e92a522e9](https://linux-hardware.org/?probe=7e92a522e9) | Mar 16, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [4c4039754c](https://linux-hardware.org/?probe=4c4039754c) | Mar 13, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [70a5dc4f94](https://linux-hardware.org/?probe=70a5dc4f94) | Mar 12, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [8fdeae3b33](https://linux-hardware.org/?probe=8fdeae3b33) | Mar 12, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [9c61029e1f](https://linux-hardware.org/?probe=9c61029e1f) | Mar 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo        | 3187 SDK0L77769 WIN 3423... | Desktop     | [545b878c51](https://linux-hardware.org/?probe=545b878c51) | Mar 10, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [2b4cd63d88](https://linux-hardware.org/?probe=2b4cd63d88) | Mar 10, 2022 |
| Samsung       | 500R5L/501R5L/500R5P/550... | Notebook    | [8d792e6db0](https://linux-hardware.org/?probe=8d792e6db0) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3edcfcdf53](https://linux-hardware.org/?probe=3edcfcdf53) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | Notebook    | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Toshiba       | Satellite C850-C008         | Notebook    | [d18b844729](https://linux-hardware.org/?probe=d18b844729) | Mar 07, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [e1da80ec6f](https://linux-hardware.org/?probe=e1da80ec6f) | Mar 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c697a91a8e](https://linux-hardware.org/?probe=c697a91a8e) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| Dell          | Latitude 7285               | Notebook    | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [f2fb3da876](https://linux-hardware.org/?probe=f2fb3da876) | Mar 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2511c4e555](https://linux-hardware.org/?probe=2511c4e555) | Feb 28, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [05c2b02bd3](https://linux-hardware.org/?probe=05c2b02bd3) | Feb 26, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [93aca5cd19](https://linux-hardware.org/?probe=93aca5cd19) | Feb 25, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | TM1709                      | Notebook    | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| LG Electro... | 16Z90P-G.AA56C              | Notebook    | [f4b91cfb92](https://linux-hardware.org/?probe=f4b91cfb92) | Feb 22, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a07d445338](https://linux-hardware.org/?probe=a07d445338) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [215889b22b](https://linux-hardware.org/?probe=215889b22b) | Feb 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [b91f497b74](https://linux-hardware.org/?probe=b91f497b74) | Feb 19, 2022 |
| Lenovo        | NOK                         | Desktop     | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| MSI           | A88XM-E45                   | Desktop     | [b58bd64798](https://linux-hardware.org/?probe=b58bd64798) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 14IHU 2021 82... | Notebook    | [d994752dc6](https://linux-hardware.org/?probe=d994752dc6) | Feb 15, 2022 |
| MSI           | WT72 2OM                    | Notebook    | [e266645b4a](https://linux-hardware.org/?probe=e266645b4a) | Feb 14, 2022 |
| Dell          | System Inspiron N4110       | Notebook    | [695b7bb3dd](https://linux-hardware.org/?probe=695b7bb3dd) | Feb 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2fe2235d74](https://linux-hardware.org/?probe=2fe2235d74) | Feb 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [fa14786b94](https://linux-hardware.org/?probe=fa14786b94) | Feb 13, 2022 |
| Acer          | Swift SF314-510G            | Notebook    | [6c4dbc81d8](https://linux-hardware.org/?probe=6c4dbc81d8) | Feb 12, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [62bdd11635](https://linux-hardware.org/?probe=62bdd11635) | Feb 11, 2022 |
| Dell          | G7 7500                     | Notebook    | [61f4625e4c](https://linux-hardware.org/?probe=61f4625e4c) | Feb 11, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [27bb88805d](https://linux-hardware.org/?probe=27bb88805d) | Feb 10, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [6f558be780](https://linux-hardware.org/?probe=6f558be780) | Feb 10, 2022 |
| Lenovo        | ThinkPad T61p 64608VU       | Notebook    | [73fddf3dcc](https://linux-hardware.org/?probe=73fddf3dcc) | Feb 10, 2022 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [502457cef5](https://linux-hardware.org/?probe=502457cef5) | Feb 09, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [b9019fac00](https://linux-hardware.org/?probe=b9019fac00) | Feb 09, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [beb9e79811](https://linux-hardware.org/?probe=beb9e79811) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76733NJ        | Notebook    | [42dec79e1d](https://linux-hardware.org/?probe=42dec79e1d) | Feb 08, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [a154ac8369](https://linux-hardware.org/?probe=a154ac8369) | Feb 08, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [0e264c593f](https://linux-hardware.org/?probe=0e264c593f) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| HUAWEI        | KLV-WX9                     | Notebook    | [80eec7db33](https://linux-hardware.org/?probe=80eec7db33) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Dell          | Inspiron 3476               | Notebook    | [468adecdcc](https://linux-hardware.org/?probe=468adecdcc) | Feb 05, 2022 |
| Lenovo        | ThinkPad E450 20DCA07JCD    | Notebook    | [ce693a499b](https://linux-hardware.org/?probe=ce693a499b) | Feb 05, 2022 |
| Timi          | TM1612                      | Notebook    | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Synology      | DS216+                      | Notebook    | [f4d851d128](https://linux-hardware.org/?probe=f4d851d128) | Feb 04, 2022 |
| ECS           | BSWI-DA                     | Desktop     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [927ed071b3](https://linux-hardware.org/?probe=927ed071b3) | Jan 30, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [b79cd8c2b0](https://linux-hardware.org/?probe=b79cd8c2b0) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [5802ec7cbc](https://linux-hardware.org/?probe=5802ec7cbc) | Jan 30, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | Notebook    | [d2d9c64d63](https://linux-hardware.org/?probe=d2d9c64d63) | Jan 30, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [fe6b8cb2e4](https://linux-hardware.org/?probe=fe6b8cb2e4) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [0bef76b548](https://linux-hardware.org/?probe=0bef76b548) | Jan 28, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [e578c5f173](https://linux-hardware.org/?probe=e578c5f173) | Jan 28, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [fb7e1fcf47](https://linux-hardware.org/?probe=fb7e1fcf47) | Jan 28, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Unknown       | 0XWDCF A01                  | Server      | [f5f07bffc2](https://linux-hardware.org/?probe=f5f07bffc2) | Jan 24, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [a3aa535c25](https://linux-hardware.org/?probe=a3aa535c25) | Jan 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8d72f7a752](https://linux-hardware.org/?probe=8d72f7a752) | Jan 23, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [d22caa9915](https://linux-hardware.org/?probe=d22caa9915) | Jan 23, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fb18e68215](https://linux-hardware.org/?probe=fb18e68215) | Jan 22, 2022 |
| Intel         | G41 V1.0                    | Desktop     | [e1f1c99851](https://linux-hardware.org/?probe=e1f1c99851) | Jan 22, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [794a06d193](https://linux-hardware.org/?probe=794a06d193) | Jan 22, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [8c817d64a7](https://linux-hardware.org/?probe=8c817d64a7) | Jan 21, 2022 |
| Timi          | A7S                         | Notebook    | [9c419e0bab](https://linux-hardware.org/?probe=9c419e0bab) | Jan 20, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [7c07d2e27d](https://linux-hardware.org/?probe=7c07d2e27d) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [90b4523b21](https://linux-hardware.org/?probe=90b4523b21) | Jan 19, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [152a75acd0](https://linux-hardware.org/?probe=152a75acd0) | Jan 19, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [75c70d6dee](https://linux-hardware.org/?probe=75c70d6dee) | Jan 19, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [51d6b35ddf](https://linux-hardware.org/?probe=51d6b35ddf) | Jan 17, 2022 |
| MSI           | H310M-S03                   | Desktop     | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| Lenovo        | ThinkPad T470 20HDA022CD    | Notebook    | [3b3eeaa6b7](https://linux-hardware.org/?probe=3b3eeaa6b7) | Jan 14, 2022 |
| Synology      | DS216+                      | Notebook    | [8650ca59f1](https://linux-hardware.org/?probe=8650ca59f1) | Jan 10, 2022 |
| Dell          | Latitude E6400              | Notebook    | [ba6b82b98b](https://linux-hardware.org/?probe=ba6b82b98b) | Jan 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [45d678095f](https://linux-hardware.org/?probe=45d678095f) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b3a76ceb99](https://linux-hardware.org/?probe=b3a76ceb99) | Dec 31, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8d56c47c8d](https://linux-hardware.org/?probe=8d56c47c8d) | Dec 31, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [08d5ba6a97](https://linux-hardware.org/?probe=08d5ba6a97) | Dec 30, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [ad94c90825](https://linux-hardware.org/?probe=ad94c90825) | Dec 29, 2021 |
| Samsung       | 500R5L/501R5L/500R5P/550... | Notebook    | [1f24ba261b](https://linux-hardware.org/?probe=1f24ba261b) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| HP            | EliteBook 8470w             | Notebook    | [87c1cb1da7](https://linux-hardware.org/?probe=87c1cb1da7) | Dec 23, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [70703de094](https://linux-hardware.org/?probe=70703de094) | Dec 22, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [a7cc31a69f](https://linux-hardware.org/?probe=a7cc31a69f) | Dec 22, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [50d0f206e1](https://linux-hardware.org/?probe=50d0f206e1) | Dec 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c2474eed31](https://linux-hardware.org/?probe=c2474eed31) | Dec 21, 2021 |
| Microsoft     | Surface Go 3                | Tablet      | [1081ed2c15](https://linux-hardware.org/?probe=1081ed2c15) | Dec 20, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| Lenovo        | Unknown                     | Desktop     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [e3c15cfedb](https://linux-hardware.org/?probe=e3c15cfedb) | Dec 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [5559a99303](https://linux-hardware.org/?probe=5559a99303) | Dec 14, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [c029d9c42b](https://linux-hardware.org/?probe=c029d9c42b) | Dec 14, 2021 |
| ASUSTek       | B85M-F                      | Desktop     | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| Lenovo        | [9532AC1] STC               | Server      | [78113d1370](https://linux-hardware.org/?probe=78113d1370) | Dec 13, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [ce9a3f2c74](https://linux-hardware.org/?probe=ce9a3f2c74) | Dec 13, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | Desktop     | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [877a0414c3](https://linux-hardware.org/?probe=877a0414c3) | Dec 12, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [c4efae322a](https://linux-hardware.org/?probe=c4efae322a) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [bd4021ec3d](https://linux-hardware.org/?probe=bd4021ec3d) | Dec 11, 2021 |
| Insyde        | CherryTrail                 | Notebook    | [1525831810](https://linux-hardware.org/?probe=1525831810) | Dec 11, 2021 |
| Lenovo        | Legion Y9000X 2020 81YY     | Notebook    | [acd0b9c831](https://linux-hardware.org/?probe=acd0b9c831) | Dec 11, 2021 |
| HASEE Comp... | E400                        | Notebook    | [32bee165ba](https://linux-hardware.org/?probe=32bee165ba) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| Lenovo        | Unknown                     | Convertible | [fac9e252e4](https://linux-hardware.org/?probe=fac9e252e4) | Dec 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [fe97757850](https://linux-hardware.org/?probe=fe97757850) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [fe3a7ec790](https://linux-hardware.org/?probe=fe3a7ec790) | Dec 10, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [c6f3827cb1](https://linux-hardware.org/?probe=c6f3827cb1) | Dec 09, 2021 |
| Fujitsu       | FMVNQ8P9                    | Notebook    | [04ca55ea2b](https://linux-hardware.org/?probe=04ca55ea2b) | Dec 09, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| OEM           | TOP77D Ver1.0               | Desktop     | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | Desktop     | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Supermicro    | X10DRL-i                    | Server      | [e7819a0518](https://linux-hardware.org/?probe=e7819a0518) | Dec 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [b62c884aec](https://linux-hardware.org/?probe=b62c884aec) | Dec 05, 2021 |
| AOC           | A815HB                      | Desktop     | [b1aec8b16c](https://linux-hardware.org/?probe=b1aec8b16c) | Dec 04, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [63dade9d7b](https://linux-hardware.org/?probe=63dade9d7b) | Dec 01, 2021 |
| OEM           | TOP77D Ver1.0               | Desktop     | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| HUAWEI        | BC11SPCC V100R001C10        | Server      | [eb5771b190](https://linux-hardware.org/?probe=eb5771b190) | Nov 29, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Timi          | A7S                         | Notebook    | [625bafd45f](https://linux-hardware.org/?probe=625bafd45f) | Nov 27, 2021 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [109d14527f](https://linux-hardware.org/?probe=109d14527f) | Nov 27, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| Jemper        | EZPAD WS_reserve            | Notebook    | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| ASUSTek       | B85M-G PLUS                 | Desktop     | [e198df930c](https://linux-hardware.org/?probe=e198df930c) | Nov 23, 2021 |
| ASUSTek       | B85M-G PLUS                 | Desktop     | [023ab776cd](https://linux-hardware.org/?probe=023ab776cd) | Nov 23, 2021 |
| Google        | Panther                     | Desktop     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [53462f848a](https://linux-hardware.org/?probe=53462f848a) | Nov 20, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [69c06885de](https://linux-hardware.org/?probe=69c06885de) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [bdd3471fa2](https://linux-hardware.org/?probe=bdd3471fa2) | Nov 17, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [4d73c8557a](https://linux-hardware.org/?probe=4d73c8557a) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | Notebook    | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| AOC           | A815HB                      | Desktop     | [e56b509a5a](https://linux-hardware.org/?probe=e56b509a5a) | Nov 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | Notebook    | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 7447               | Notebook    | [4ca16063da](https://linux-hardware.org/?probe=4ca16063da) | Nov 12, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [51d1a5ac24](https://linux-hardware.org/?probe=51d1a5ac24) | Nov 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| Shanghai Z... | EA170_ TBD                  | Desktop     | [edc1846e0f](https://linux-hardware.org/?probe=edc1846e0f) | Nov 10, 2021 |
| Shanghai Z... | EA170_ TBD                  | Desktop     | [9f839630ac](https://linux-hardware.org/?probe=9f839630ac) | Nov 10, 2021 |
| Jumper        | EZbook                      | Notebook    | [f1391c1f4b](https://linux-hardware.org/?probe=f1391c1f4b) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [67670eea60](https://linux-hardware.org/?probe=67670eea60) | Nov 07, 2021 |
| Dell          | G15 5515                    | Notebook    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [7aa37239c1](https://linux-hardware.org/?probe=7aa37239c1) | Nov 03, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [127b977658](https://linux-hardware.org/?probe=127b977658) | Oct 31, 2021 |
| Timi          | A34R                        | Notebook    | [f5385d6b10](https://linux-hardware.org/?probe=f5385d6b10) | Oct 31, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [8a74691ba9](https://linux-hardware.org/?probe=8a74691ba9) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [cafc4421b2](https://linux-hardware.org/?probe=cafc4421b2) | Oct 29, 2021 |
| Dell          | G3 3500                     | Notebook    | [a2d09beb8d](https://linux-hardware.org/?probe=a2d09beb8d) | Oct 25, 2021 |
| Toshiba       | dynabook Satellite T772/... | Notebook    | [070723f36c](https://linux-hardware.org/?probe=070723f36c) | Oct 24, 2021 |
| Lenovo        | 3107 SDK0L77769 WIN 3423... | Desktop     | [6a7a621271](https://linux-hardware.org/?probe=6a7a621271) | Oct 22, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [9f2d69e4c4](https://linux-hardware.org/?probe=9f2d69e4c4) | Oct 20, 2021 |
| Dell          | 0H21J3 A07                  | Server      | [c7b39e92ca](https://linux-hardware.org/?probe=c7b39e92ca) | Oct 19, 2021 |
| Dell          | 0H21J3 A07                  | Server      | [9b3a90c143](https://linux-hardware.org/?probe=9b3a90c143) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fb1797d3d](https://linux-hardware.org/?probe=2fb1797d3d) | Oct 19, 2021 |
| Dell          | G3 3500                     | Notebook    | [ec734562a6](https://linux-hardware.org/?probe=ec734562a6) | Oct 19, 2021 |
| Timi          | A34                         | Notebook    | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T2A... | Notebook    | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4aa5287a00](https://linux-hardware.org/?probe=4aa5287a00) | Oct 15, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [050314f62a](https://linux-hardware.org/?probe=050314f62a) | Oct 13, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Dell          | 0C96W1 A02                  | Desktop     | [edb83b3d2f](https://linux-hardware.org/?probe=edb83b3d2f) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [3eb7a24e5a](https://linux-hardware.org/?probe=3eb7a24e5a) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [38bb1cfdc4](https://linux-hardware.org/?probe=38bb1cfdc4) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [bce3e39f4c](https://linux-hardware.org/?probe=bce3e39f4c) | Oct 10, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [1c4fbe0fa4](https://linux-hardware.org/?probe=1c4fbe0fa4) | Oct 10, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [d63fd746be](https://linux-hardware.org/?probe=d63fd746be) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [bc9337f46e](https://linux-hardware.org/?probe=bc9337f46e) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [abd011c6b2](https://linux-hardware.org/?probe=abd011c6b2) | Oct 06, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | Notebook    | [0f58e969f6](https://linux-hardware.org/?probe=0f58e969f6) | Oct 03, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| Timi          | TM1613                      | Notebook    | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | Notebook    | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1b471b415d](https://linux-hardware.org/?probe=1b471b415d) | Sep 29, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [5f5ae3035b](https://linux-hardware.org/?probe=5f5ae3035b) | Sep 29, 2021 |
| ASRock        | TRX40 Creator               | Desktop     | [c7b8fcc312](https://linux-hardware.org/?probe=c7b8fcc312) | Sep 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c18e17d7d](https://linux-hardware.org/?probe=4c18e17d7d) | Sep 29, 2021 |
| Soyo          | SY-Thin Mini H110           | Mini pc     | [ca900f89d0](https://linux-hardware.org/?probe=ca900f89d0) | Sep 28, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8adcff21a2](https://linux-hardware.org/?probe=8adcff21a2) | Sep 27, 2021 |
| Lenovo        | XiaoXinAir 14ALC 2021 82... | Notebook    | [df352fba0f](https://linux-hardware.org/?probe=df352fba0f) | Sep 27, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| Terrans Fo... | AMD                         | Notebook    | [db4b9e36ab](https://linux-hardware.org/?probe=db4b9e36ab) | Sep 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASRockRack    | EPC621D8A                   | Server      | [2244eb7809](https://linux-hardware.org/?probe=2244eb7809) | Sep 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [be9156bd20](https://linux-hardware.org/?probe=be9156bd20) | Sep 24, 2021 |
| Lenovo        | XiaoXin-15IWL 2019 81QS     | Notebook    | [f726b13948](https://linux-hardware.org/?probe=f726b13948) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [0a99b9ac87](https://linux-hardware.org/?probe=0a99b9ac87) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [ea86578390](https://linux-hardware.org/?probe=ea86578390) | Sep 22, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [508bab38ae](https://linux-hardware.org/?probe=508bab38ae) | Sep 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTA0... | Notebook    | [9a59e3a4f1](https://linux-hardware.org/?probe=9a59e3a4f1) | Sep 20, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [8b09747789](https://linux-hardware.org/?probe=8b09747789) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | Desktop     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | B360M-BASALT                | Desktop     | [f1783ce369](https://linux-hardware.org/?probe=f1783ce369) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [18cbc8a35f](https://linux-hardware.org/?probe=18cbc8a35f) | Sep 18, 2021 |
| Lenovo        | ThinkPad X200 74574AC       | Notebook    | [5debd35710](https://linux-hardware.org/?probe=5debd35710) | Sep 18, 2021 |
| GXNOVA Com... | GX2                         | Notebook    | [ab148b2b4e](https://linux-hardware.org/?probe=ab148b2b4e) | Sep 14, 2021 |
| Lenovo        | NOK                         | Desktop     | [61a15d9531](https://linux-hardware.org/?probe=61a15d9531) | Sep 14, 2021 |
| Notebook      | P65xHP                      | Notebook    | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Intel         | AST2600EVB                  | Server      | [aead99f55d](https://linux-hardware.org/?probe=aead99f55d) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAA... | Notebook    | [ebcb7d7982](https://linux-hardware.org/?probe=ebcb7d7982) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| HP            | 431                         | Notebook    | [c2510d05b4](https://linux-hardware.org/?probe=c2510d05b4) | Sep 12, 2021 |
| HP            | 431                         | Notebook    | [d19b47e4d8](https://linux-hardware.org/?probe=d19b47e4d8) | Sep 12, 2021 |
| Sony          | SVT11215CGW                 | Notebook    | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [35ee76ca1b](https://linux-hardware.org/?probe=35ee76ca1b) | Sep 08, 2021 |
| Intel         | EAGLESTREAM E63448-400      | Server      | [7c59811abb](https://linux-hardware.org/?probe=7c59811abb) | Sep 08, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [35ee0ea8e4](https://linux-hardware.org/?probe=35ee0ea8e4) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [025d2a8ddb](https://linux-hardware.org/?probe=025d2a8ddb) | Sep 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9bbf3f2d82](https://linux-hardware.org/?probe=9bbf3f2d82) | Sep 05, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Timi          | TM1613                      | Notebook    | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [5996acf813](https://linux-hardware.org/?probe=5996acf813) | Aug 31, 2021 |
| GPD           | G1618-03                    | Notebook    | [d680dd4360](https://linux-hardware.org/?probe=d680dd4360) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | Notebook    | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [08b5160307](https://linux-hardware.org/?probe=08b5160307) | Aug 27, 2021 |
| Lenovo        | K4450 20229                 | Notebook    | [70e7af9fae](https://linux-hardware.org/?probe=70e7af9fae) | Aug 26, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [4563619600](https://linux-hardware.org/?probe=4563619600) | Aug 25, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [33cc1aba5f](https://linux-hardware.org/?probe=33cc1aba5f) | Aug 25, 2021 |
| Lenovo        | K4450 20229                 | Notebook    | [e1c019df72](https://linux-hardware.org/?probe=e1c019df72) | Aug 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [e0e805180d](https://linux-hardware.org/?probe=e0e805180d) | Aug 22, 2021 |
| Lenovo        | ThinkPad E455 20DEA027CD    | Notebook    | [8edb3642cb](https://linux-hardware.org/?probe=8edb3642cb) | Aug 22, 2021 |
| Timi          | TM1612                      | Notebook    | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [ce37ed52aa](https://linux-hardware.org/?probe=ce37ed52aa) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18f0785e64](https://linux-hardware.org/?probe=18f0785e64) | Aug 19, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [321cf3c58f](https://linux-hardware.org/?probe=321cf3c58f) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [753b5b706d](https://linux-hardware.org/?probe=753b5b706d) | Aug 18, 2021 |
| Acer          | Nitro AN515-57              | Notebook    | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Alienware     | m17                         | Notebook    | [5fdd4a64a3](https://linux-hardware.org/?probe=5fdd4a64a3) | Aug 17, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| Lenovo        | ThinkPad L430 2466EY7       | Notebook    | [b93128f327](https://linux-hardware.org/?probe=b93128f327) | Aug 12, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [aaef52aca2](https://linux-hardware.org/?probe=aaef52aca2) | Aug 10, 2021 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [98a65d0b3b](https://linux-hardware.org/?probe=98a65d0b3b) | Aug 10, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.01    | Desktop     | [ad2f5f75d8](https://linux-hardware.org/?probe=ad2f5f75d8) | Aug 10, 2021 |
| TSINGHUA T... | B460-N2                     | Desktop     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| ASUSTek       | Z97-PRO                     | Desktop     | [a0e65d5ee7](https://linux-hardware.org/?probe=a0e65d5ee7) | Aug 08, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [8eff816347](https://linux-hardware.org/?probe=8eff816347) | Aug 08, 2021 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| GPD           | G1618-03                    | Notebook    | [25a0b540aa](https://linux-hardware.org/?probe=25a0b540aa) | Aug 07, 2021 |
| Dell          | Inspiron 11-3168            | Notebook    | [67552d79ac](https://linux-hardware.org/?probe=67552d79ac) | Aug 05, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [30526e56ab](https://linux-hardware.org/?probe=30526e56ab) | Aug 05, 2021 |
| Lenovo        | ZHAOYANG K3-ITL 82E3        | Notebook    | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [07e9ee8610](https://linux-hardware.org/?probe=07e9ee8610) | Aug 02, 2021 |
| Chuwi         | UBook                       | Tablet      | [1da6b43703](https://linux-hardware.org/?probe=1da6b43703) | Aug 02, 2021 |
| Lenovo        | MIIX 2 8 20326              | Tablet      | [205a7c853a](https://linux-hardware.org/?probe=205a7c853a) | Jul 31, 2021 |
| Gigabyte      | MZ71-CE1-00 01000100        | Server      | [c6e1e678f5](https://linux-hardware.org/?probe=c6e1e678f5) | Jul 30, 2021 |
| Gigabyte      | MZ71-CE1-00 01000100        | Server      | [8d9705bd2a](https://linux-hardware.org/?probe=8d9705bd2a) | Jul 30, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [124425a1ed](https://linux-hardware.org/?probe=124425a1ed) | Jul 28, 2021 |
| MSI           | GT62VR 7RE                  | Notebook    | [5f02658195](https://linux-hardware.org/?probe=5f02658195) | Jul 27, 2021 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [e411a84d3c](https://linux-hardware.org/?probe=e411a84d3c) | Jul 26, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | Notebook    | [1722982c29](https://linux-hardware.org/?probe=1722982c29) | Jul 26, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e4d71ee9a8](https://linux-hardware.org/?probe=e4d71ee9a8) | Jul 24, 2021 |
| Intel         | Corbett Park CRB Revisio... | Notebook    | [17f1a1e73e](https://linux-hardware.org/?probe=17f1a1e73e) | Jul 21, 2021 |
| Lenovo        | Legion R70002020 82B6       | Notebook    | [d620ec97eb](https://linux-hardware.org/?probe=d620ec97eb) | Jul 21, 2021 |
| Lenovo        | G50-70m 20423               | Notebook    | [0b1a40c724](https://linux-hardware.org/?probe=0b1a40c724) | Jul 21, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [f282cf1244](https://linux-hardware.org/?probe=f282cf1244) | Jul 18, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [06221fa5e9](https://linux-hardware.org/?probe=06221fa5e9) | Jul 16, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [9f2fb87684](https://linux-hardware.org/?probe=9f2fb87684) | Jul 16, 2021 |
| Toshiba       | NB300                       | Notebook    | [03b62f85cb](https://linux-hardware.org/?probe=03b62f85cb) | Jul 15, 2021 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [dd73dac900](https://linux-hardware.org/?probe=dd73dac900) | Jul 15, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [82c1959e49](https://linux-hardware.org/?probe=82c1959e49) | Jul 13, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [60c8b3011a](https://linux-hardware.org/?probe=60c8b3011a) | Jul 12, 2021 |
| AMD           | BL2 V2.3                    | Desktop     | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| HASEE Comp... | Computer                    | Notebook    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| Clevo         | P7xxTM(1)                   | Notebook    | [98eeef735f](https://linux-hardware.org/?probe=98eeef735f) | Jul 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9d18d07e36](https://linux-hardware.org/?probe=9d18d07e36) | Jul 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [d90c6cbf04](https://linux-hardware.org/?probe=d90c6cbf04) | Jul 04, 2021 |
| Quanta        | Winterfell                  | Server      | [e0ef143493](https://linux-hardware.org/?probe=e0ef143493) | Jul 03, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| Dell          | 0GX297                      | Desktop     | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | Notebook    | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| HP            | 18E7                        | Desktop     | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| Terrans Fo... | X511                        | Notebook    | [7c131d9b3c](https://linux-hardware.org/?probe=7c131d9b3c) | Jun 27, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c9180096a8](https://linux-hardware.org/?probe=c9180096a8) | Jun 26, 2021 |
| Toshiba       | Satellite C600              | Notebook    | [2be9935e22](https://linux-hardware.org/?probe=2be9935e22) | Jun 25, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [48335e0b08](https://linux-hardware.org/?probe=48335e0b08) | Jun 24, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| Dell          | G7 7500                     | Notebook    | [fc4a38d0b1](https://linux-hardware.org/?probe=fc4a38d0b1) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [6c83856ca5](https://linux-hardware.org/?probe=6c83856ca5) | Jun 22, 2021 |
| Toshiba       | Satellite C850-C008         | Notebook    | [91fc03f063](https://linux-hardware.org/?probe=91fc03f063) | Jun 21, 2021 |
| Timi          | TM1612                      | Notebook    | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f1200f8ad1](https://linux-hardware.org/?probe=f1200f8ad1) | Jun 20, 2021 |
| Timi          | TM1612                      | Notebook    | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [4373344c26](https://linux-hardware.org/?probe=4373344c26) | Jun 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [43ef80b625](https://linux-hardware.org/?probe=43ef80b625) | Jun 19, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [439593d28e](https://linux-hardware.org/?probe=439593d28e) | Jun 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [45b203fa1d](https://linux-hardware.org/?probe=45b203fa1d) | Jun 19, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [7535868db2](https://linux-hardware.org/?probe=7535868db2) | Jun 18, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [c9a19ce57f](https://linux-hardware.org/?probe=c9a19ce57f) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [c8249a8836](https://linux-hardware.org/?probe=c8249a8836) | Jun 17, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [c095a4437c](https://linux-hardware.org/?probe=c095a4437c) | Jun 17, 2021 |
| Hampoo        | Cherry Trail CR V300        | Notebook    | [344ff5676f](https://linux-hardware.org/?probe=344ff5676f) | Jun 16, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | Desktop     | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | Legion Y9000K 2019 SE 81... | Notebook    | [374ace3f30](https://linux-hardware.org/?probe=374ace3f30) | Jun 15, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [54128eb7cf](https://linux-hardware.org/?probe=54128eb7cf) | Jun 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9e0e3015c3](https://linux-hardware.org/?probe=9e0e3015c3) | Jun 13, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [c178189191](https://linux-hardware.org/?probe=c178189191) | Jun 12, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [82334ce2ee](https://linux-hardware.org/?probe=82334ce2ee) | Jun 12, 2021 |
| Lenovo        | H310                        | Desktop     | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [8834a1f44c](https://linux-hardware.org/?probe=8834a1f44c) | Jun 11, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [41d143b254](https://linux-hardware.org/?probe=41d143b254) | Jun 09, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [72f511586b](https://linux-hardware.org/?probe=72f511586b) | Jun 09, 2021 |
| HASEE Comp... | CW67S                       | Notebook    | [3012373a54](https://linux-hardware.org/?probe=3012373a54) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | Desktop     | [e9ee5e90e8](https://linux-hardware.org/?probe=e9ee5e90e8) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | Desktop     | [2fd059f38d](https://linux-hardware.org/?probe=2fd059f38d) | Jun 08, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [2ddd57f551](https://linux-hardware.org/?probe=2ddd57f551) | Jun 06, 2021 |
| Lenovo        | H310                        | Desktop     | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [efb0b681f0](https://linux-hardware.org/?probe=efb0b681f0) | Jun 05, 2021 |
| Timi          | TM1612                      | Notebook    | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [173f1c74f4](https://linux-hardware.org/?probe=173f1c74f4) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | Desktop     | [2a8b1a08bc](https://linux-hardware.org/?probe=2a8b1a08bc) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | Desktop     | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | Desktop     | [37534d085b](https://linux-hardware.org/?probe=37534d085b) | Jun 04, 2021 |
| Lenovo        | ThinkPad X230 23257Y1       | Notebook    | [d507dfaef3](https://linux-hardware.org/?probe=d507dfaef3) | Jun 02, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [7a11677611](https://linux-hardware.org/?probe=7a11677611) | Jun 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [eed35a825a](https://linux-hardware.org/?probe=eed35a825a) | May 31, 2021 |
| Lenovo        | ZHAOYANG K29 20186          | Notebook    | [f02d15e805](https://linux-hardware.org/?probe=f02d15e805) | May 31, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [b6047b1557](https://linux-hardware.org/?probe=b6047b1557) | May 31, 2021 |
| Huanghe       | PRO H410M-C                 | Desktop     | [1c92e63940](https://linux-hardware.org/?probe=1c92e63940) | May 31, 2021 |
| Supermicro    | X8DTH                       | Server      | [d9ed4f04a3](https://linux-hardware.org/?probe=d9ed4f04a3) | May 30, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [32ca60dcea](https://linux-hardware.org/?probe=32ca60dcea) | May 30, 2021 |
| HUAWEI        | KPR-WX9                     | Notebook    | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [83d261308f](https://linux-hardware.org/?probe=83d261308f) | May 26, 2021 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a22fbcde28](https://linux-hardware.org/?probe=a22fbcde28) | May 26, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| Centerm       | C92                         | Desktop     | [fe4761d2b2](https://linux-hardware.org/?probe=fe4761d2b2) | May 25, 2021 |
| Acer          | Aspire TC-606               | Desktop     | [db910234a6](https://linux-hardware.org/?probe=db910234a6) | May 25, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [c4842eda94](https://linux-hardware.org/?probe=c4842eda94) | May 24, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [5dca660f7e](https://linux-hardware.org/?probe=5dca660f7e) | May 22, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [c9e7ae41ba](https://linux-hardware.org/?probe=c9e7ae41ba) | May 21, 2021 |
| Lenovo        | ThinkPad X220 4290BB8       | Notebook    | [e147d7b57e](https://linux-hardware.org/?probe=e147d7b57e) | May 21, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [72904aba23](https://linux-hardware.org/?probe=72904aba23) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [c04c98c26f](https://linux-hardware.org/?probe=c04c98c26f) | May 19, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [fa2352afac](https://linux-hardware.org/?probe=fa2352afac) | May 19, 2021 |
| HP            | Laptop 14s-fr0xxx           | Notebook    | [ee4105df76](https://linux-hardware.org/?probe=ee4105df76) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| Dell          | Vostro 13 5310              | Notebook    | [ed812af95a](https://linux-hardware.org/?probe=ed812af95a) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [41fbd83170](https://linux-hardware.org/?probe=41fbd83170) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | Desktop     | [d418b8e0e9](https://linux-hardware.org/?probe=d418b8e0e9) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | Desktop     | [b04d956c6e](https://linux-hardware.org/?probe=b04d956c6e) | May 17, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [ee3ff1a75d](https://linux-hardware.org/?probe=ee3ff1a75d) | May 15, 2021 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [96c74bb052](https://linux-hardware.org/?probe=96c74bb052) | May 14, 2021 |
| Jumper        | EZbook                      | Notebook    | [8a28589e34](https://linux-hardware.org/?probe=8a28589e34) | May 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| Jumper        | EZbook                      | Notebook    | [9c48c2d8c5](https://linux-hardware.org/?probe=9c48c2d8c5) | May 07, 2021 |
| HP            | EliteBook 745 G5            | Notebook    | [21422647b7](https://linux-hardware.org/?probe=21422647b7) | May 06, 2021 |
| Jumper        | EZbook                      | Notebook    | [741a5fbc51](https://linux-hardware.org/?probe=741a5fbc51) | May 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9e86c8ede5](https://linux-hardware.org/?probe=9e86c8ede5) | May 05, 2021 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [f813c25e0d](https://linux-hardware.org/?probe=f813c25e0d) | May 05, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [b3ffc8d1cb](https://linux-hardware.org/?probe=b3ffc8d1cb) | May 04, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [321f62efb9](https://linux-hardware.org/?probe=321f62efb9) | May 04, 2021 |
| Lenovo        | ThinkPad E480 20KN000UCD    | Notebook    | [f665cfa22e](https://linux-hardware.org/?probe=f665cfa22e) | May 04, 2021 |
| Lenovo        | ThinkPad E14 20RA002JCD     | Notebook    | [ca3b61c51a](https://linux-hardware.org/?probe=ca3b61c51a) | May 04, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [e769a18f8a](https://linux-hardware.org/?probe=e769a18f8a) | May 04, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [586195f9e8](https://linux-hardware.org/?probe=586195f9e8) | May 03, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0f71a5127c](https://linux-hardware.org/?probe=0f71a5127c) | May 01, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | Notebook    | [8647f6f8fb](https://linux-hardware.org/?probe=8647f6f8fb) | Apr 29, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [6ee00932dc](https://linux-hardware.org/?probe=6ee00932dc) | Apr 29, 2021 |
| HASEE Comp... | QTC6                        | Notebook    | [7f1f85fd8c](https://linux-hardware.org/?probe=7f1f85fd8c) | Apr 28, 2021 |
| Dell          | Inspiron 3482               | Notebook    | [a8ab0451de](https://linux-hardware.org/?probe=a8ab0451de) | Apr 27, 2021 |
| Lenovo        | ZHAOYANG K43c-80 81HX       | Notebook    | [de6628af88](https://linux-hardware.org/?probe=de6628af88) | Apr 27, 2021 |
| Lenovo        | No DPK                      | Desktop     | [15a0f7dbe3](https://linux-hardware.org/?probe=15a0f7dbe3) | Apr 27, 2021 |
| ELSKY         | M219F-6C                    | Desktop     | [85ce077799](https://linux-hardware.org/?probe=85ce077799) | Apr 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [5f7bac315c](https://linux-hardware.org/?probe=5f7bac315c) | Apr 19, 2021 |
| Acer          | Swift SF313-52              | Notebook    | [0f4028c401](https://linux-hardware.org/?probe=0f4028c401) | Apr 19, 2021 |
| Samsung       | 535U4C                      | Notebook    | [1bdb581e3d](https://linux-hardware.org/?probe=1bdb581e3d) | Apr 17, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [ee1c82a186](https://linux-hardware.org/?probe=ee1c82a186) | Apr 15, 2021 |
| Samsung       | 535U4C                      | Notebook    | [1f61906add](https://linux-hardware.org/?probe=1f61906add) | Apr 15, 2021 |
| HASEE Comp... | Unknown                     | Notebook    | [5abcc341b3](https://linux-hardware.org/?probe=5abcc341b3) | Apr 14, 2021 |
| HASEE Comp... | Unknown                     | Notebook    | [76f3519f3f](https://linux-hardware.org/?probe=76f3519f3f) | Apr 14, 2021 |
| Lenovo        | ThinkPad T410s 2912B99      | Notebook    | [cce75356c4](https://linux-hardware.org/?probe=cce75356c4) | Apr 11, 2021 |
| Unknown       | Unknown                     | Phone       | [1fb0779a5b](https://linux-hardware.org/?probe=1fb0779a5b) | Apr 10, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [4b01a44998](https://linux-hardware.org/?probe=4b01a44998) | Apr 10, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [7c883d58c6](https://linux-hardware.org/?probe=7c883d58c6) | Apr 10, 2021 |
| Lenovo        | V10 ThinkPad X63            | Notebook    | [60ee0c7112](https://linux-hardware.org/?probe=60ee0c7112) | Apr 08, 2021 |
| Lenovo        | V10 ThinkPad X63            | Notebook    | [dfa1081980](https://linux-hardware.org/?probe=dfa1081980) | Apr 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [e03bf9d1a9](https://linux-hardware.org/?probe=e03bf9d1a9) | Apr 07, 2021 |
| MECHREVO      | S3 Pro                      | Notebook    | [a8656190d7](https://linux-hardware.org/?probe=a8656190d7) | Apr 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e15be45763](https://linux-hardware.org/?probe=e15be45763) | Apr 04, 2021 |
| Dell          | 0H21J3 A09                  | Server      | [51fb8fee00](https://linux-hardware.org/?probe=51fb8fee00) | Apr 04, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [c557439d9f](https://linux-hardware.org/?probe=c557439d9f) | Apr 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [66d76dda01](https://linux-hardware.org/?probe=66d76dda01) | Apr 03, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [8406dee7f4](https://linux-hardware.org/?probe=8406dee7f4) | Apr 02, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [6e403bbf50](https://linux-hardware.org/?probe=6e403bbf50) | Apr 02, 2021 |
| GPD           | P2 MAX                      | Notebook    | [b07bc1f694](https://linux-hardware.org/?probe=b07bc1f694) | Apr 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [aa8f00686c](https://linux-hardware.org/?probe=aa8f00686c) | Apr 01, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [7ffd62b3fa](https://linux-hardware.org/?probe=7ffd62b3fa) | Mar 31, 2021 |
| ASUSTek       | UX370UAF                    | Convertible | [6570252e3e](https://linux-hardware.org/?probe=6570252e3e) | Mar 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [98ed905fb1](https://linux-hardware.org/?probe=98ed905fb1) | Mar 28, 2021 |
| ASUSTek       | UX370UAF                    | Convertible | [5965f6dec2](https://linux-hardware.org/?probe=5965f6dec2) | Mar 28, 2021 |
| Lenovo        | ThinkPad X230 2324DM2       | Notebook    | [2cf882da9e](https://linux-hardware.org/?probe=2cf882da9e) | Mar 28, 2021 |
| Dell          | Latitude E6400              | Notebook    | [ac6d60eaa9](https://linux-hardware.org/?probe=ac6d60eaa9) | Mar 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [7b97516ad8](https://linux-hardware.org/?probe=7b97516ad8) | Mar 26, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [4ff6ff15fc](https://linux-hardware.org/?probe=4ff6ff15fc) | Mar 26, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [16f1d9e647](https://linux-hardware.org/?probe=16f1d9e647) | Mar 18, 2021 |
| HP            | ZHAN 99 G2 Mobile Workst... | Notebook    | [d16fc044eb](https://linux-hardware.org/?probe=d16fc044eb) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [a95086c30b](https://linux-hardware.org/?probe=a95086c30b) | Mar 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [d98e2dea30](https://linux-hardware.org/?probe=d98e2dea30) | Mar 17, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [e10243fa5c](https://linux-hardware.org/?probe=e10243fa5c) | Mar 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b96252ab8f](https://linux-hardware.org/?probe=b96252ab8f) | Mar 15, 2021 |
| SYWZ          | S210H Series                | Desktop     | [2e8183b6eb](https://linux-hardware.org/?probe=2e8183b6eb) | Mar 14, 2021 |
| SYWZ          | S210H Series                | Desktop     | [d0f36756ab](https://linux-hardware.org/?probe=d0f36756ab) | Mar 14, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [d73ebe56eb](https://linux-hardware.org/?probe=d73ebe56eb) | Mar 11, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [4202717644](https://linux-hardware.org/?probe=4202717644) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [3b64f161c0](https://linux-hardware.org/?probe=3b64f161c0) | Mar 05, 2021 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [f3cfea77ac](https://linux-hardware.org/?probe=f3cfea77ac) | Mar 04, 2021 |
| Lenovo        | ThinkPad X220 4291HL8       | Notebook    | [f8dd5d3807](https://linux-hardware.org/?probe=f8dd5d3807) | Mar 02, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [229409a8dc](https://linux-hardware.org/?probe=229409a8dc) | Feb 25, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [336e949796](https://linux-hardware.org/?probe=336e949796) | Feb 24, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [96a3577708](https://linux-hardware.org/?probe=96a3577708) | Feb 24, 2021 |
| HP            | 1000                        | Notebook    | [2ab8891f42](https://linux-hardware.org/?probe=2ab8891f42) | Feb 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [93e1220042](https://linux-hardware.org/?probe=93e1220042) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [78ec6d58ba](https://linux-hardware.org/?probe=78ec6d58ba) | Feb 22, 2021 |
| Dell          | 03CPWF A00                  | Desktop     | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [0ac46a588c](https://linux-hardware.org/?probe=0ac46a588c) | Feb 21, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [bbace409ed](https://linux-hardware.org/?probe=bbace409ed) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [df1e1e308b](https://linux-hardware.org/?probe=df1e1e308b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [94362e140c](https://linux-hardware.org/?probe=94362e140c) | Feb 18, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [6e1c4be9d8](https://linux-hardware.org/?probe=6e1c4be9d8) | Feb 17, 2021 |
| HASEE Comp... | E460                        | Notebook    | [5af90fef31](https://linux-hardware.org/?probe=5af90fef31) | Feb 17, 2021 |
| Gigabyte      | B85M-D2V-SI                 | Desktop     | [a0779807a2](https://linux-hardware.org/?probe=a0779807a2) | Feb 15, 2021 |
| Timi          | TM1703                      | Notebook    | [53183984c3](https://linux-hardware.org/?probe=53183984c3) | Feb 14, 2021 |
| Dell          | 04VF8V A01                  | Desktop     | [14d2de53c9](https://linux-hardware.org/?probe=14d2de53c9) | Feb 14, 2021 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [5b5df6dbfc](https://linux-hardware.org/?probe=5b5df6dbfc) | Feb 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [3792a88564](https://linux-hardware.org/?probe=3792a88564) | Feb 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [797c58c227](https://linux-hardware.org/?probe=797c58c227) | Feb 08, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [d844c4f50e](https://linux-hardware.org/?probe=d844c4f50e) | Feb 05, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [5c23d11a52](https://linux-hardware.org/?probe=5c23d11a52) | Feb 05, 2021 |
| Lenovo        | Unknown                     | Convertible | [1dad570af9](https://linux-hardware.org/?probe=1dad570af9) | Feb 04, 2021 |
| HUAWEI        | SP1PGUM M1020               | Desktop     | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d538017b75](https://linux-hardware.org/?probe=d538017b75) | Feb 04, 2021 |
| HP            | 81C6 MVB 0C                 | Server      | [279b8964e5](https://linux-hardware.org/?probe=279b8964e5) | Feb 03, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1ed34422ce](https://linux-hardware.org/?probe=1ed34422ce) | Feb 02, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [02cd7a5160](https://linux-hardware.org/?probe=02cd7a5160) | Feb 02, 2021 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [b8558ad233](https://linux-hardware.org/?probe=b8558ad233) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [c0cd6afd03](https://linux-hardware.org/?probe=c0cd6afd03) | Feb 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2135ddb8dd](https://linux-hardware.org/?probe=2135ddb8dd) | Feb 02, 2021 |
| Dell          | 06JWJY A00                  | Desktop     | [1f2099e9d3](https://linux-hardware.org/?probe=1f2099e9d3) | Feb 02, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [8db56c19da](https://linux-hardware.org/?probe=8db56c19da) | Feb 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [5b274af228](https://linux-hardware.org/?probe=5b274af228) | Feb 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [39c3dd1edd](https://linux-hardware.org/?probe=39c3dd1edd) | Feb 02, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [9c21c30887](https://linux-hardware.org/?probe=9c21c30887) | Jan 30, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [32ba9cc321](https://linux-hardware.org/?probe=32ba9cc321) | Jan 29, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [35d97e2d21](https://linux-hardware.org/?probe=35d97e2d21) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [5e7f5ea64a](https://linux-hardware.org/?probe=5e7f5ea64a) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [81aa504e98](https://linux-hardware.org/?probe=81aa504e98) | Jan 28, 2021 |
| Dell          | 0CYTN6 A00                  | All in one  | [48d68a1579](https://linux-hardware.org/?probe=48d68a1579) | Jan 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [11db0c5d50](https://linux-hardware.org/?probe=11db0c5d50) | Jan 27, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [a7106e3642](https://linux-hardware.org/?probe=a7106e3642) | Jan 27, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a1c263681f](https://linux-hardware.org/?probe=a1c263681f) | Jan 26, 2021 |
| ASUSTek       | PRIME H310M-F R2.0          | Desktop     | [3c4d584c27](https://linux-hardware.org/?probe=3c4d584c27) | Jan 26, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [f888388942](https://linux-hardware.org/?probe=f888388942) | Jan 23, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [583f0d9ea2](https://linux-hardware.org/?probe=583f0d9ea2) | Jan 22, 2021 |
| Dell          | 0CYTN6 A00                  | All in one  | [e77cf82db6](https://linux-hardware.org/?probe=e77cf82db6) | Jan 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1b100a591d](https://linux-hardware.org/?probe=1b100a591d) | Jan 19, 2021 |
| Dell          | Precision 5750              | Notebook    | [11a4cc2ef1](https://linux-hardware.org/?probe=11a4cc2ef1) | Jan 19, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [66efbfed55](https://linux-hardware.org/?probe=66efbfed55) | Jan 19, 2021 |
| Lenovo        | 317E SDK0L77767 WIN 3423... | Desktop     | [6e82572f07](https://linux-hardware.org/?probe=6e82572f07) | Jan 17, 2021 |
| Lenovo        | IdeaPad 320C-15IKB 81FU     | Notebook    | [32af8085e3](https://linux-hardware.org/?probe=32af8085e3) | Jan 15, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [edbfbb65b8](https://linux-hardware.org/?probe=edbfbb65b8) | Jan 15, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [1e5e57866d](https://linux-hardware.org/?probe=1e5e57866d) | Jan 14, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [4149fbf824](https://linux-hardware.org/?probe=4149fbf824) | Jan 14, 2021 |
| Lenovo        | Unknown                     | Notebook    | [38c41d5178](https://linux-hardware.org/?probe=38c41d5178) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [ca1391c20d](https://linux-hardware.org/?probe=ca1391c20d) | Jan 13, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [1a4ee1ce22](https://linux-hardware.org/?probe=1a4ee1ce22) | Jan 13, 2021 |
| HP            | ZHAN 66 Pro 15 G3           | Notebook    | [309b0b4383](https://linux-hardware.org/?probe=309b0b4383) | Jan 12, 2021 |
| HP            | ProBook 6565b               | Notebook    | [517e898344](https://linux-hardware.org/?probe=517e898344) | Jan 12, 2021 |
| Lenovo        | 3107 NOK                    | Desktop     | [902ea74b31](https://linux-hardware.org/?probe=902ea74b31) | Jan 08, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [8b678d540d](https://linux-hardware.org/?probe=8b678d540d) | Jan 06, 2021 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [95eb2199fd](https://linux-hardware.org/?probe=95eb2199fd) | Jan 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [584259b642](https://linux-hardware.org/?probe=584259b642) | Jan 02, 2021 |
| Lenovo        | Unknown                     | Notebook    | [bfa46b3e89](https://linux-hardware.org/?probe=bfa46b3e89) | Jan 01, 2021 |
| Google        | Zako                        | Desktop     | [d8df4eefd6](https://linux-hardware.org/?probe=d8df4eefd6) | Jan 01, 2021 |
| Dell          | G3 3579                     | Notebook    | [200c758b4b](https://linux-hardware.org/?probe=200c758b4b) | Jan 01, 2021 |
| Google        | Zako                        | Desktop     | [6bedd150e9](https://linux-hardware.org/?probe=6bedd150e9) | Jan 01, 2021 |
| HP            | 82A4                        | Desktop     | [bf686ef745](https://linux-hardware.org/?probe=bf686ef745) | Jan 01, 2021 |
| ASUSTek       | F81Se                       | Notebook    | [78420c272f](https://linux-hardware.org/?probe=78420c272f) | Dec 30, 2020 |
| ASUSTek       | F81Se                       | Notebook    | [f88933df38](https://linux-hardware.org/?probe=f88933df38) | Dec 30, 2020 |
| Lenovo        | G580 20150                  | Notebook    | [3e777432b1](https://linux-hardware.org/?probe=3e777432b1) | Dec 29, 2020 |
| Lenovo        | Unknown                     | Notebook    | [d789a34be2](https://linux-hardware.org/?probe=d789a34be2) | Dec 29, 2020 |
| Lenovo        | Unknown                     | Notebook    | [9ea48b71d6](https://linux-hardware.org/?probe=9ea48b71d6) | Dec 29, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [258a4745bf](https://linux-hardware.org/?probe=258a4745bf) | Dec 29, 2020 |
| Timi          | RedmiBook 14 II             | Notebook    | [6d6ce6a47a](https://linux-hardware.org/?probe=6d6ce6a47a) | Dec 29, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [c9a2d0d9e0](https://linux-hardware.org/?probe=c9a2d0d9e0) | Dec 28, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [dc8521e74c](https://linux-hardware.org/?probe=dc8521e74c) | Dec 28, 2020 |
| Lenovo        | 1.0                         | Desktop     | [897523f5fd](https://linux-hardware.org/?probe=897523f5fd) | Dec 27, 2020 |
| Lenovo        | 1.0                         | Desktop     | [53a763dc24](https://linux-hardware.org/?probe=53a763dc24) | Dec 27, 2020 |
| ASUSTek       | F81Se                       | Notebook    | [f33f999200](https://linux-hardware.org/?probe=f33f999200) | Dec 26, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [fd025ae38b](https://linux-hardware.org/?probe=fd025ae38b) | Dec 23, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a141f2ed51](https://linux-hardware.org/?probe=a141f2ed51) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | Notebook    | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Lenovo        | MIIX 520-12IKB 20M4         | Tablet      | [f78d607b1f](https://linux-hardware.org/?probe=f78d607b1f) | Dec 18, 2020 |
| HASEE Comp... | PF4WN2F                     | Notebook    | [9855617493](https://linux-hardware.org/?probe=9855617493) | Dec 15, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [224c36cf4d](https://linux-hardware.org/?probe=224c36cf4d) | Dec 15, 2020 |
| ASRock        | Z170 Gaming K4              | Desktop     | [a246612b17](https://linux-hardware.org/?probe=a246612b17) | Dec 13, 2020 |
| Lenovo        | ThinkPad X230 2325DV4       | Notebook    | [03eaed4dcb](https://linux-hardware.org/?probe=03eaed4dcb) | Dec 11, 2020 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [0c0911cd7b](https://linux-hardware.org/?probe=0c0911cd7b) | Dec 11, 2020 |
| GPD           | P2 MAX                      | Notebook    | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [87cfa2982d](https://linux-hardware.org/?probe=87cfa2982d) | Dec 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [8b7c746735](https://linux-hardware.org/?probe=8b7c746735) | Dec 08, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b20c8c639e](https://linux-hardware.org/?probe=b20c8c639e) | Dec 08, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [290c53b26c](https://linux-hardware.org/?probe=290c53b26c) | Dec 08, 2020 |
| HUAWEI        | Kunpeng Desktop             | Desktop     | [cbd268b858](https://linux-hardware.org/?probe=cbd268b858) | Dec 04, 2020 |
| HUAWEI        | Kunpeng Desktop             | Desktop     | [da163e34c7](https://linux-hardware.org/?probe=da163e34c7) | Dec 04, 2020 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [7eb641e51d](https://linux-hardware.org/?probe=7eb641e51d) | Dec 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [216a0f765e](https://linux-hardware.org/?probe=216a0f765e) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | Desktop     | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Lenovo        | ThinkPad P53 20QQA004CD     | Notebook    | [a9e2438f51](https://linux-hardware.org/?probe=a9e2438f51) | Nov 28, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [d1c0a8df13](https://linux-hardware.org/?probe=d1c0a8df13) | Nov 23, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [7975ba3888](https://linux-hardware.org/?probe=7975ba3888) | Nov 23, 2020 |
| Unknown       | Unknown                     | Desktop     | [d58e8b793e](https://linux-hardware.org/?probe=d58e8b793e) | Nov 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [c0e8909067](https://linux-hardware.org/?probe=c0e8909067) | Nov 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [c0d7c657b1](https://linux-hardware.org/?probe=c0d7c657b1) | Nov 22, 2020 |
| Gigabyte      | 970-GAMING                  | Desktop     | [44f42f7676](https://linux-hardware.org/?probe=44f42f7676) | Nov 21, 2020 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [2aa8c29fb4](https://linux-hardware.org/?probe=2aa8c29fb4) | Nov 21, 2020 |
| Dell          | 028PX1 A00                  | Server      | [00fda23065](https://linux-hardware.org/?probe=00fda23065) | Nov 20, 2020 |
| Colorful T... | C.H110M-K PRO V21           | Desktop     | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [73c5a8bd67](https://linux-hardware.org/?probe=73c5a8bd67) | Nov 19, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [23418fe6cc](https://linux-hardware.org/?probe=23418fe6cc) | Nov 19, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0999a52054](https://linux-hardware.org/?probe=0999a52054) | Nov 18, 2020 |
| Apple         | MacBookPro11,3              | Notebook    | [a01b45c371](https://linux-hardware.org/?probe=a01b45c371) | Nov 17, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [37dbdd4b85](https://linux-hardware.org/?probe=37dbdd4b85) | Nov 16, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [5182cf15a5](https://linux-hardware.org/?probe=5182cf15a5) | Nov 16, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Lenovo        | Y430P 20435                 | Notebook    | [2ee9b87c44](https://linux-hardware.org/?probe=2ee9b87c44) | Nov 15, 2020 |
| HASEE Comp... | QTH6                        | Notebook    | [a2a60413b1](https://linux-hardware.org/?probe=a2a60413b1) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | Notebook    | [a1bd3a60dc](https://linux-hardware.org/?probe=a1bd3a60dc) | Nov 13, 2020 |
| HASEE Comp... | QL9S                        | Notebook    | [799ba586bd](https://linux-hardware.org/?probe=799ba586bd) | Nov 13, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [d68d6cdf18](https://linux-hardware.org/?probe=d68d6cdf18) | Nov 13, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [069182cff6](https://linux-hardware.org/?probe=069182cff6) | Nov 12, 2020 |
| Dell          | Latitude 5490               | Notebook    | [894bd38b38](https://linux-hardware.org/?probe=894bd38b38) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [28c7cf4458](https://linux-hardware.org/?probe=28c7cf4458) | Nov 11, 2020 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [b4fbf1f2e6](https://linux-hardware.org/?probe=b4fbf1f2e6) | Nov 11, 2020 |
| Dell          | Precision 7510              | Notebook    | [5cb1751259](https://linux-hardware.org/?probe=5cb1751259) | Nov 11, 2020 |
| Sony          | VPCZ115FC                   | Notebook    | [7e886b81d0](https://linux-hardware.org/?probe=7e886b81d0) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c9dbcdd42b](https://linux-hardware.org/?probe=c9dbcdd42b) | Nov 09, 2020 |
| Lenovo        | Unknown                     | Notebook    | [d689908218](https://linux-hardware.org/?probe=d689908218) | Nov 08, 2020 |
| Lenovo        | ThinkPad X250 20CLA272CD    | Notebook    | [a9075402e1](https://linux-hardware.org/?probe=a9075402e1) | Nov 08, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [ed3c250112](https://linux-hardware.org/?probe=ed3c250112) | Nov 03, 2020 |
| HP            | 8455                        | Desktop     | [8fbf07649a](https://linux-hardware.org/?probe=8fbf07649a) | Nov 03, 2020 |
| Lenovo        | Legion R7000P2020H 82GR     | Notebook    | [907de62181](https://linux-hardware.org/?probe=907de62181) | Oct 31, 2020 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [105a5c3241](https://linux-hardware.org/?probe=105a5c3241) | Oct 31, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d69c97a2c3](https://linux-hardware.org/?probe=d69c97a2c3) | Oct 30, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [1affea93fd](https://linux-hardware.org/?probe=1affea93fd) | Oct 27, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [e930aac9b6](https://linux-hardware.org/?probe=e930aac9b6) | Oct 27, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [cf48a4f7b0](https://linux-hardware.org/?probe=cf48a4f7b0) | Oct 26, 2020 |
| Intel         | SKYBAY                      | Desktop     | [ebc35582c8](https://linux-hardware.org/?probe=ebc35582c8) | Oct 23, 2020 |
| Intel         | SKYBAY                      | Desktop     | [ce89df6806](https://linux-hardware.org/?probe=ce89df6806) | Oct 23, 2020 |
| Lenovo        | M5400 20281                 | Notebook    | [08fa33ca8e](https://linux-hardware.org/?probe=08fa33ca8e) | Oct 22, 2020 |
| HP            | ZHAN 66 Pro 15 G2           | Notebook    | [adb6a00cd2](https://linux-hardware.org/?probe=adb6a00cd2) | Oct 22, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [f101c9246f](https://linux-hardware.org/?probe=f101c9246f) | Oct 17, 2020 |
| Dell          | G3 3500                     | Notebook    | [5cb1ce307e](https://linux-hardware.org/?probe=5cb1ce307e) | Oct 16, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [6faf6514f5](https://linux-hardware.org/?probe=6faf6514f5) | Oct 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5af00a6f4a](https://linux-hardware.org/?probe=5af00a6f4a) | Oct 13, 2020 |
| Unknown       | Unknown                     | Notebook    | [b4ead91a12](https://linux-hardware.org/?probe=b4ead91a12) | Oct 05, 2020 |
| HP            | ZHAN 66 Pro 14 G2           | Notebook    | [b690ea4e11](https://linux-hardware.org/?probe=b690ea4e11) | Oct 03, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Acidanther... | Mac-DB15BD556843C820 iMa... | All in one  | [ca7807180d](https://linux-hardware.org/?probe=ca7807180d) | Sep 30, 2020 |
| Lenovo        | ThinkPad E580 20KS002BCD    | Notebook    | [e89a66365d](https://linux-hardware.org/?probe=e89a66365d) | Sep 29, 2020 |
| Lenovo        | M5400 20281                 | Notebook    | [839f6b0ddc](https://linux-hardware.org/?probe=839f6b0ddc) | Sep 28, 2020 |
| Dell          | Inspiron 7720               | Notebook    | [cafa640700](https://linux-hardware.org/?probe=cafa640700) | Sep 27, 2020 |
| Gigabyte      | B85M-D2V                    | Desktop     | [3393bfd809](https://linux-hardware.org/?probe=3393bfd809) | Sep 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/China/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 157       | 15%     |
| Ubuntu 18.04                 | 127       | 12.13%  |
| Arch                         | 50        | 4.78%   |
| Debian 11                    | 42        | 4.01%   |
| Arch Rolling                 | 32        | 3.06%   |
| Ubuntu 22.04                 | 26        | 2.48%   |
| Ubuntu 19.04                 | 21        | 2.01%   |
| OpenMandriva 4.2             | 20        | 1.91%   |
| Debian 10                    | 20        | 1.91%   |
| OpenMandriva 4.3             | 18        | 1.72%   |
| Manjaro                      | 18        | 1.72%   |
| UOS 20                       | 17        | 1.62%   |
| KDE neon 20.04               | 17        | 1.62%   |
| Ubuntu 21.10                 | 16        | 1.53%   |
| Gentoo 2.7                   | 16        | 1.53%   |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 1.43%   |
| Ubuntu 21.04                 | 14        | 1.34%   |
| Ubuntu 19.10                 | 14        | 1.34%   |
| Gentoo 2.8                   | 13        | 1.24%   |
| Fedora 33                    | 13        | 1.24%   |
| Ubuntu 16.04                 | 12        | 1.15%   |
| Linux Mint 20.1              | 12        | 1.15%   |
| Linux Mint 20.3              | 10        | 0.96%   |
| CentOS 7                     | 10        | 0.96%   |
| Gentoo 2.6                   | 9         | 0.86%   |
| Fedora 35                    | 9         | 0.86%   |
| CentOS 8                     | 9         | 0.86%   |
| Ubuntu 20.10                 | 8         | 0.76%   |
| Linux Mint 20.2              | 8         | 0.76%   |
| Fedora 34                    | 8         | 0.76%   |
| Fedora 32                    | 8         | 0.76%   |
| ROSA R10                     | 7         | 0.67%   |
| OpenMandriva 4.50            | 7         | 0.67%   |
| Linux Mint 20                | 7         | 0.67%   |
| Kylin V10                    | 7         | 0.67%   |
| Debian Testing               | 7         | 0.67%   |
| Atz 11.3                     | 6         | 0.57%   |
| ArcoLinux Rolling            | 6         | 0.57%   |
| Ubuntu Unity 16.04           | 5         | 0.48%   |
| Manjaro 18.1.4               | 5         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 391       | 38.41%  |
| Debian       | 82        | 8.06%   |
| Arch         | 80        | 7.86%   |
| Manjaro      | 56        | 5.5%    |
| Fedora       | 48        | 4.72%   |
| OpenMandriva | 47        | 4.62%   |
| Linux Mint   | 41        | 4.03%   |
| Gentoo       | 36        | 3.54%   |
| Deepin       | 28        | 2.75%   |
| KDE neon     | 19        | 1.87%   |
| CentOS       | 19        | 1.87%   |
| openSUSE     | 18        | 1.77%   |
| Pop!_OS      | 13        | 1.28%   |
| Kubuntu      | 13        | 1.28%   |
| Ubuntu Unity | 11        | 1.08%   |
| ROSA         | 11        | 1.08%   |
| Atz          | 11        | 1.08%   |
| Kylin        | 9         | 0.88%   |
| Xubuntu      | 8         | 0.79%   |
| Kali         | 8         | 0.79%   |
| Clear Linux  | 8         | 0.79%   |
| Elementary   | 7         | 0.69%   |
| ArcoLinux    | 7         | 0.69%   |
| BlackPanther | 4         | 0.39%   |
| Android      | 4         | 0.39%   |
| Zorin        | 3         | 0.29%   |
| Ubuntu MATE  | 3         | 0.29%   |
| Ubuntu Kylin | 2         | 0.2%    |
| Trisquel     | 2         | 0.2%    |
| RHEL         | 2         | 0.2%    |
| RedFlag      | 2         | 0.2%    |
| NFS Desktop  | 2         | 0.2%    |
| MX           | 2         | 0.2%    |
| LMDE         | 2         | 0.2%    |
| Guix         | 2         | 0.2%    |
| Endless      | 2         | 0.2%    |
| SteamOS      | 1         | 0.1%    |
| Solus        | 1         | 0.1%    |
| Rocky Linux  | 1         | 0.1%    |
| RED          | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 19        | 1.71%   |
| 5.16.7-desktop-1omv4003  | 17        | 1.53%   |
| 5.4.0-42-generic         | 14        | 1.26%   |
| 5.10.0-8-amd64           | 10        | 0.9%    |
| 5.15.0-46-generic        | 9         | 0.81%   |
| 5.13.0-30-generic        | 9         | 0.81%   |
| 5.0.0-23-generic         | 9         | 0.81%   |
| 5.11.0-43-generic        | 8         | 0.72%   |
| 4.18.0-25-generic        | 8         | 0.72%   |
| 5.4.0-58-generic         | 7         | 0.63%   |
| 5.0.0-13-generic         | 7         | 0.63%   |
| 4.18.0-16-generic        | 7         | 0.63%   |
| 5.8.0-50-generic         | 6         | 0.54%   |
| 5.4.0-74-generic         | 6         | 0.54%   |
| 5.4.0-73-generic         | 6         | 0.54%   |
| 5.4.0-48-generic         | 6         | 0.54%   |
| 5.4.0-33-generic         | 6         | 0.54%   |
| 5.4.0-29-generic         | 6         | 0.54%   |
| 5.3.0-46-generic         | 6         | 0.54%   |
| 5.15.0-41-generic        | 6         | 0.54%   |
| 5.15.0-25-generic        | 6         | 0.54%   |
| 5.12.4-desktop-1omv4050  | 6         | 0.54%   |
| 5.11.0-34-generic        | 6         | 0.54%   |
| 5.11.0-27-generic        | 6         | 0.54%   |
| 5.8.0-63-generic         | 5         | 0.45%   |
| 5.8.0-43-generic         | 5         | 0.45%   |
| 5.4.0-77-generic         | 5         | 0.45%   |
| 5.4.0-54-generic         | 5         | 0.45%   |
| 5.4.0-52-generic         | 5         | 0.45%   |
| 5.3.0-28-generic         | 5         | 0.45%   |
| 5.15.0-2-amd64           | 5         | 0.45%   |
| 5.13.0-35-generic        | 5         | 0.45%   |
| 5.13.0-22-generic        | 5         | 0.45%   |
| 5.11.0-41-generic        | 5         | 0.45%   |
| 5.11.0-40-generic        | 5         | 0.45%   |
| 5.11.0-37-generic        | 5         | 0.45%   |
| 5.10.41-amd64-desktop    | 5         | 0.45%   |
| 5.0.0-25-generic         | 5         | 0.45%   |
| 4.18.0-15-generic        | 5         | 0.45%   |
| 5.8.0-55-generic         | 4         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 137       | 12.73%  |
| 5.11.0  | 58        | 5.39%   |
| 4.15.0  | 57        | 5.3%    |
| 5.13.0  | 51        | 4.74%   |
| 5.10.0  | 50        | 4.65%   |
| 5.8.0   | 45        | 4.18%   |
| 4.18.0  | 45        | 4.18%   |
| 5.0.0   | 43        | 4%      |
| 5.15.0  | 41        | 3.81%   |
| 5.3.0   | 35        | 3.25%   |
| 4.19.0  | 24        | 2.23%   |
| 5.10.14 | 19        | 1.77%   |
| 5.16.7  | 18        | 1.67%   |
| 3.10.0  | 9         | 0.84%   |
| 5.16.0  | 8         | 0.74%   |
| 5.6.14  | 7         | 0.65%   |
| 5.4.18  | 6         | 0.56%   |
| 5.18.12 | 6         | 0.56%   |
| 5.14.0  | 6         | 0.56%   |
| 5.12.4  | 6         | 0.56%   |
| 5.6.0   | 5         | 0.46%   |
| 5.19.0  | 5         | 0.46%   |
| 5.18.0  | 5         | 0.46%   |
| 5.17.0  | 5         | 0.46%   |
| 5.10.41 | 5         | 0.46%   |
| 5.10.36 | 5         | 0.46%   |
| 4.9.60  | 5         | 0.46%   |
| 5.9.16  | 4         | 0.37%   |
| 5.9.11  | 4         | 0.37%   |
| 5.7.7   | 4         | 0.37%   |
| 5.4.2   | 4         | 0.37%   |
| 5.17.5  | 4         | 0.37%   |
| 5.17.1  | 4         | 0.37%   |
| 5.14.6  | 4         | 0.37%   |
| 5.10.27 | 4         | 0.37%   |
| 5.8.18  | 3         | 0.28%   |
| 5.19.5  | 3         | 0.28%   |
| 5.18.9  | 3         | 0.28%   |
| 5.18.5  | 3         | 0.28%   |
| 5.18.16 | 3         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 170       | 16.01%  |
| 5.10    | 120       | 11.3%   |
| 5.15    | 83        | 7.82%   |
| 5.11    | 75        | 7.06%   |
| 5.13    | 62        | 5.84%   |
| 5.8     | 61        | 5.74%   |
| 4.15    | 57        | 5.37%   |
| 5.0     | 47        | 4.43%   |
| 4.18    | 47        | 4.43%   |
| 5.3     | 42        | 3.95%   |
| 5.16    | 39        | 3.67%   |
| 5.18    | 31        | 2.92%   |
| 4.19    | 31        | 2.92%   |
| 5.17    | 24        | 2.26%   |
| 5.14    | 23        | 2.17%   |
| 5.12    | 23        | 2.17%   |
| 5.9     | 20        | 1.88%   |
| 5.6     | 19        | 1.79%   |
| 5.19    | 13        | 1.22%   |
| 5.7     | 12        | 1.13%   |
| 4.9     | 12        | 1.13%   |
| 3.10    | 11        | 1.04%   |
| 5.5     | 8         | 0.75%   |
| 5.1     | 5         | 0.47%   |
| 4.1     | 5         | 0.47%   |
| 4.14    | 4         | 0.38%   |
| 4.4     | 3         | 0.28%   |
| 4.13    | 3         | 0.28%   |
| 5.2     | 2         | 0.19%   |
| 4.20    | 2         | 0.19%   |
| 3.4     | 2         | 0.19%   |
| 6.0     | 1         | 0.09%   |
| 4.6     | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 943       | 94.96%  |
| aarch64 | 25        | 2.52%   |
| i686    | 8         | 0.81%   |
| riscv64 | 7         | 0.7%    |
| ppc64   | 3         | 0.3%    |
| armv7l  | 2         | 0.2%    |
| sh4a    | 1         | 0.1%    |
| ppc64le | 1         | 0.1%    |
| mips64  | 1         | 0.1%    |
| armv8l  | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 421       | 41.32%  |
| Unknown         | 197       | 19.33%  |
| KDE5            | 152       | 14.92%  |
| XFCE            | 63        | 6.18%   |
| KDE             | 34        | 3.34%   |
| X-Cinnamon      | 33        | 3.24%   |
| Deepin          | 27        | 2.65%   |
| i3              | 15        | 1.47%   |
| MATE            | 13        | 1.28%   |
| Unity           | 10        | 0.98%   |
| UKUI            | 9         | 0.88%   |
| Pantheon        | 7         | 0.69%   |
| Cinnamon        | 7         | 0.69%   |
| LXDE            | 6         | 0.59%   |
| KDE4            | 5         | 0.49%   |
| GNOME Flashback | 4         | 0.39%   |
| Budgie          | 4         | 0.39%   |
| GNOME Classic   | 3         | 0.29%   |
| GNUstep         | 2         | 0.2%    |
| xmonad          | 1         | 0.1%    |
| sway            | 1         | 0.1%    |
| qtile           | 1         | 0.1%    |
| Openbox         | 1         | 0.1%    |
| LXQt            | 1         | 0.1%    |
| bspwm           | 1         | 0.1%    |
| awesome         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 738       | 72.57%  |
| Wayland | 126       | 12.39%  |
| Unknown | 98        | 9.64%   |
| Tty     | 55        | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 476       | 46.9%   |
| GDM     | 154       | 15.17%  |
| SDDM    | 137       | 13.5%   |
| LightDM | 106       | 10.44%  |
| GDM3    | 90        | 8.87%   |
| TDM     | 43        | 4.24%   |
| KDM     | 4         | 0.39%   |
| XDM     | 2         | 0.2%    |
| LXDM    | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| zh_CN       | 430       | 42.53%  |
| en_US       | 357       | 35.31%  |
| Unknown     | 166       | 16.42%  |
| C           | 17        | 1.68%   |
| en_GB       | 10        | 0.99%   |
| en_HK       | 8         | 0.79%   |
| mn_CN       | 4         | 0.4%    |
| en_AU       | 3         | 0.3%    |
| C.UTF8      | 3         | 0.3%    |
| ja_JP       | 2         | 0.2%    |
| fr_FR       | 2         | 0.2%    |
| de_DE       | 2         | 0.2%    |
| th_TH       | 1         | 0.1%    |
| ru_RU       | 1         | 0.1%    |
| POSIX       | 1         | 0.1%    |
| en_ZA       | 1         | 0.1%    |
| en_US.utf-8 | 1         | 0.1%    |
| en_SG       | 1         | 0.1%    |
| .en_US      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 651       | 64.65%  |
| BIOS | 356       | 35.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 801       | 79.62%  |
| Btrfs      | 73        | 7.26%   |
| Overlay    | 43        | 4.27%   |
| Xfs        | 41        | 4.08%   |
| Unknown    | 31        | 3.08%   |
| Zfs        | 9         | 0.89%   |
| F2fs       | 4         | 0.4%    |
| Tmpfs      | 1         | 0.1%    |
| Rootfs     | 1         | 0.1%    |
| Reiserfs   | 1         | 0.1%    |
| Fuse.sshfs | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 463       | 46.3%   |
| Unknown | 453       | 45.3%   |
| MBR     | 84        | 8.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 862       | 85.35%  |
| Yes       | 148       | 14.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 603       | 60.36%  |
| Yes       | 396       | 39.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 266       | 26.81%  |
| Dell                           | 111       | 11.19%  |
| ASUSTek Computer               | 93        | 9.38%   |
| Hewlett-Packard                | 80        | 8.06%   |
| Gigabyte Technology            | 45        | 4.54%   |
| HUAWEI                         | 44        | 4.44%   |
| MSI                            | 42        | 4.23%   |
| Timi                           | 31        | 3.13%   |
| Unknown                        | 28        | 2.82%   |
| Intel                          | 27        | 2.72%   |
| Acer                           | 24        | 2.42%   |
| HASEE Computer                 | 12        | 1.21%   |
| ASRock                         | 12        | 1.21%   |
| Apple                          | 10        | 1.01%   |
| Raspberry Pi Foundation        | 7         | 0.71%   |
| Phytium                        | 7         | 0.71%   |
| Microsoft                      | 7         | 0.71%   |
| MECHREVO                       | 7         | 0.71%   |
| Toshiba                        | 6         | 0.6%    |
| Supermicro                     | 6         | 0.6%    |
| Sony                           | 6         | 0.6%    |
| Google                         | 6         | 0.6%    |
| AMI                            | 6         | 0.6%    |
| TSINGHUA TONGFANG COMPUTER     | 5         | 0.5%    |
| Samsung Electronics            | 4         | 0.4%    |
| GPD                            | 4         | 0.4%    |
| Fujitsu                        | 4         | 0.4%    |
| Colorful Technology            | 4         | 0.4%    |
| OEM                            | 3         | 0.3%    |
| Notebook                       | 3         | 0.3%    |
| Intel Client Systems           | 3         | 0.3%    |
| Huanan                         | 3         | 0.3%    |
| GreatWall                      | 3         | 0.3%    |
| win element                    | 2         | 0.2%    |
| Terrans Force                  | 2         | 0.2%    |
| Soyo                           | 2         | 0.2%    |
| Shanghai Zhaoxin Semiconductor | 2         | 0.2%    |
| ONDA                           | 2         | 0.2%    |
| LG Electronics                 | 2         | 0.2%    |
| Jumper                         | 2         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 42        | 4.23%   |
| ASUS All Series                   | 10        | 1.01%   |
| HUAWEI HLY-WX9XX                  | 8         | 0.81%   |
| MSI MS-7B89                       | 6         | 0.6%    |
| Lenovo Legion R9000P2021H 82JQ    | 6         | 0.6%    |
| TSINGHUA TONGFANG COMPUTER E500   | 5         | 0.5%    |
| Timi TM1701                       | 5         | 0.5%    |
| Lenovo Legion R7000 2020 82B6     | 5         | 0.5%    |
| Phytium FT-2000/4                 | 4         | 0.4%    |
| MSI MS-7C94                       | 4         | 0.4%    |
| Lenovo ThinkBook 15p Gen 2 21B1   | 4         | 0.4%    |
| HUAWEI NBLK-WAX9X                 | 4         | 0.4%    |
| HUAWEI BOHK-WAX9X                 | 4         | 0.4%    |
| AMI Aptio CRB                     | 4         | 0.4%    |
| Timi TM1709                       | 3         | 0.3%    |
| Timi RedmiBook Pro 15S            | 3         | 0.3%    |
| Timi RedmiBook 14 II              | 3         | 0.3%    |
| Supermicro Super Server           | 3         | 0.3%    |
| Microsoft Surface Go              | 3         | 0.3%    |
| Lenovo ZHAOYANG K4e-ITL 82F8      | 3         | 0.3%    |
| Lenovo Yoga 14cACN 2021 82N7      | 3         | 0.3%    |
| Lenovo XiaoXinPro-13IML 2019 81XB | 3         | 0.3%    |
| Lenovo XiaoXinPro-13ARE 2020 82DM | 3         | 0.3%    |
| Lenovo XiaoXinAir-14ARE 2020 81YN | 3         | 0.3%    |
| Lenovo XiaoXin-15ARE 2020 81YR    | 3         | 0.3%    |
| Lenovo ThinkBook 14 G2 ITL 20VD   | 3         | 0.3%    |
| Lenovo Legion Y7000 81FW          | 3         | 0.3%    |
| Intel Client Systems LAPKC71F     | 3         | 0.3%    |
| HUAWEI KPRC-WX0                   | 3         | 0.3%    |
| HUAWEI KPR-WX9                    | 3         | 0.3%    |
| HUAWEI KPL-W0X                    | 3         | 0.3%    |
| HP ENVY Laptop 13-ad1xx           | 3         | 0.3%    |
| Dell XPS 15 9570                  | 3         | 0.3%    |
| ASUS TUF Gaming B550M-PLUS        | 3         | 0.3%    |
| ASUS M5A78L-M LX3 PLUS            | 3         | 0.3%    |
| Acer Swift SF314-42               | 3         | 0.3%    |
| win element MoreFine S500+        | 2         | 0.2%    |
| Timi TM1613                       | 2         | 0.2%    |
| Timi TM1604                       | 2         | 0.2%    |
| Timi Mi Laptop Pro 15             | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 92        | 9.27%   |
| Unknown                         | 42        | 4.23%   |
| Lenovo Legion                   | 30        | 3.02%   |
| Dell Inspiron                   | 30        | 3.02%   |
| Dell Latitude                   | 19        | 1.92%   |
| Lenovo ThinkBook                | 15        | 1.51%   |
| ASUS PRIME                      | 15        | 1.51%   |
| HP ZHAN                         | 14        | 1.41%   |
| HP EliteBook                    | 14        | 1.41%   |
| Dell OptiPlex                   | 14        | 1.41%   |
| Dell XPS                        | 13        | 1.31%   |
| Dell Precision                  | 13        | 1.31%   |
| Acer Aspire                     | 13        | 1.31%   |
| Lenovo ZHAOYANG                 | 12        | 1.21%   |
| ASUS TUF                        | 12        | 1.21%   |
| Lenovo Yoga                     | 11        | 1.11%   |
| Lenovo ThinkCentre              | 11        | 1.11%   |
| Lenovo IdeaPad                  | 11        | 1.11%   |
| HP OMEN                         | 10        | 1.01%   |
| ASUS All                        | 10        | 1.01%   |
| Dell PowerEdge                  | 9         | 0.91%   |
| ASUS ROG                        | 9         | 0.91%   |
| Lenovo ThinkStation             | 8         | 0.81%   |
| HUAWEI HLY-WX9XX                | 8         | 0.81%   |
| Timi RedmiBook                  | 7         | 0.71%   |
| RPi Raspberry                   | 7         | 0.71%   |
| Microsoft Surface               | 7         | 0.71%   |
| HP ProBook                      | 7         | 0.71%   |
| HP ENVY                         | 7         | 0.71%   |
| Acer Swift                      | 7         | 0.71%   |
| MSI MS-7B89                     | 6         | 0.6%    |
| TSINGHUA TONGFANG COMPUTER E500 | 5         | 0.5%    |
| Timi TM1701                     | 5         | 0.5%    |
| Lenovo XiaoXin                  | 5         | 0.5%    |
| Dell Vostro                     | 5         | 0.5%    |
| Toshiba Satellite               | 4         | 0.4%    |
| Phytium FT-2000                 | 4         | 0.4%    |
| MSI MS-7C94                     | 4         | 0.4%    |
| Lenovo ZHENGJIUZHE              | 4         | 0.4%    |
| HUAWEI NBLK-WAX9X               | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 145       | 14.62%  |
| 2019    | 126       | 12.7%   |
| 2018    | 126       | 12.7%   |
| 2021    | 121       | 12.2%   |
| 2017    | 79        | 7.96%   |
| 2015    | 65        | 6.55%   |
| 2013    | 50        | 5.04%   |
| 2016    | 48        | 4.84%   |
| 2014    | 47        | 4.74%   |
| 2012    | 46        | 4.64%   |
| 2011    | 37        | 3.73%   |
| 2022    | 28        | 2.82%   |
| Unknown | 27        | 2.72%   |
| 2009    | 15        | 1.51%   |
| 2010    | 13        | 1.31%   |
| 2008    | 11        | 1.11%   |
| 2007    | 7         | 0.71%   |
| 2006    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 582       | 58.67%  |
| Desktop        | 295       | 29.74%  |
| Server         | 38        | 3.83%   |
| Mini pc        | 23        | 2.32%   |
| Tablet         | 17        | 1.71%   |
| Convertible    | 16        | 1.61%   |
| System on chip | 11        | 1.11%   |
| All in one     | 5         | 0.5%    |
| Phone          | 3         | 0.3%    |
| Other          | 2         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 912       | 91.38%  |
| Enabled  | 86        | 8.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 986       | 99.4%   |
| Yes  | 6         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 244       | 24.35%  |
| 4.01-8.0        | 226       | 22.55%  |
| 8.01-16.0       | 219       | 21.86%  |
| 3.01-4.0        | 106       | 10.58%  |
| 32.01-64.0      | 100       | 9.98%   |
| 64.01-256.0     | 45        | 4.49%   |
| 24.01-32.0      | 21        | 2.1%    |
| 1.01-2.0        | 20        | 2%      |
| 0.51-1.0        | 8         | 0.8%    |
| Unknown         | 6         | 0.6%    |
| More than 256.0 | 5         | 0.5%    |
| 2.01-3.0        | 1         | 0.1%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 308       | 28.62%  |
| 2.01-3.0    | 273       | 25.37%  |
| 4.01-8.0    | 178       | 16.54%  |
| 3.01-4.0    | 154       | 14.31%  |
| 0.51-1.0    | 64        | 5.95%   |
| 8.01-16.0   | 46        | 4.28%   |
| 0.01-0.5    | 26        | 2.42%   |
| Unknown     | 10        | 0.93%   |
| 16.01-24.0  | 9         | 0.84%   |
| 32.01-64.0  | 4         | 0.37%   |
| 24.01-32.0  | 2         | 0.19%   |
| 64.01-256.0 | 2         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 556       | 55.21%  |
| 2       | 318       | 31.58%  |
| 3       | 72        | 7.15%   |
| 4       | 27        | 2.68%   |
| 5       | 13        | 1.29%   |
| 0       | 8         | 0.79%   |
| 6       | 4         | 0.4%    |
| 10      | 3         | 0.3%    |
| 9       | 2         | 0.2%    |
| 46      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 11      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 858       | 86.06%  |
| Yes       | 139       | 13.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 790       | 79.24%  |
| No        | 207       | 20.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 772       | 77.51%  |
| No        | 224       | 22.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 650       | 64.87%  |
| No        | 352       | 35.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 992       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 196       | 18.77%  |
| Shanghai         | 86        | 8.24%   |
| Shenzhen         | 83        | 7.95%   |
| Guangzhou        | 73        | 6.99%   |
| Chengdu          | 36        | 3.45%   |
| Hangzhou         | 32        | 3.07%   |
| Wuhan            | 30        | 2.87%   |
| Nanjing          | 21        | 2.01%   |
| Xi'an            | 19        | 1.82%   |
| Xuhui            | 17        | 1.63%   |
| Tianjin          | 16        | 1.53%   |
| Zhengzhou        | 13        | 1.25%   |
| Huangpu          | 12        | 1.15%   |
| Chongqing        | 12        | 1.15%   |
| Suzhou           | 11        | 1.05%   |
| Hefei            | 11        | 1.05%   |
| Haidian          | 11        | 1.05%   |
| Dongguan         | 11        | 1.05%   |
| Qingdao          | 10        | 0.96%   |
| Nanning          | 10        | 0.96%   |
| Jinan            | 10        | 0.96%   |
| Foshan           | 10        | 0.96%   |
| Dalian           | 10        | 0.96%   |
| Changsha         | 9         | 0.86%   |
| Shenyang         | 8         | 0.77%   |
| Putuo            | 8         | 0.77%   |
| Kunming          | 8         | 0.77%   |
| Fuzhou           | 8         | 0.77%   |
| Xiamen           | 7         | 0.67%   |
| Hohhot           | 7         | 0.67%   |
| Guiyang          | 7         | 0.67%   |
| Xicheng District | 6         | 0.57%   |
| Hongkou          | 6         | 0.57%   |
| Changchun        | 6         | 0.57%   |
| Xining           | 5         | 0.48%   |
| Pudong           | 5         | 0.48%   |
| Jinrongjie       | 5         | 0.48%   |
| Jiangmen         | 5         | 0.48%   |
| Zhenjiang        | 4         | 0.38%   |
| Taiyuan          | 4         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 261       | 330    | 17.49%  |
| WDC                 | 206       | 267    | 13.81%  |
| Seagate             | 185       | 292    | 12.4%   |
| Toshiba             | 98        | 120    | 6.57%   |
| SanDisk             | 69        | 80     | 4.62%   |
| Unknown             | 67        | 92     | 4.49%   |
| Intel               | 52        | 76     | 3.49%   |
| SK hynix            | 45        | 56     | 3.02%   |
| Kingston            | 42        | 51     | 2.82%   |
| HGST                | 33        | 49     | 2.21%   |
| Plextor             | 26        | 30     | 1.74%   |
| Micron Technology   | 26        | 26     | 1.74%   |
| Silicon Motion      | 20        | 23     | 1.34%   |
| Lenovo              | 17        | 24     | 1.14%   |
| Hitachi             | 17        | 27     | 1.14%   |
| LITEON              | 15        | 19     | 1.01%   |
| Crucial             | 15        | 18     | 1.01%   |
| A-DATA Technology   | 14        | 17     | 0.94%   |
| Phison              | 12        | 16     | 0.8%    |
| FORESEE             | 11        | 13     | 0.74%   |
| GALAX               | 10        | 10     | 0.67%   |
| Netac               | 9         | 10     | 0.6%    |
| KIOXIA              | 9         | 12     | 0.6%    |
| JMicron Technology  | 9         | 7      | 0.6%    |
| Colorful            | 9         | 11     | 0.6%    |
| Unknown             | 9         | 11     | 0.6%    |
| Hikvision           | 8         | 8      | 0.54%   |
| Hewlett-Packard     | 8         | 9      | 0.54%   |
| Apple               | 8         | 8      | 0.54%   |
| Teclast             | 7         | 7      | 0.47%   |
| KIOXIA-EXCERIA      | 7         | 10     | 0.47%   |
| GLOWAY              | 7         | 7      | 0.47%   |
| China               | 7         | 10     | 0.47%   |
| ZHITAI              | 6         | 6      | 0.4%    |
| Transcend           | 6         | 7      | 0.4%    |
| Lite-On             | 6         | 8      | 0.4%    |
| Fujitsu             | 6         | 6      | 0.4%    |
| Pear 2TB            | 5         | 5      | 0.34%   |
| KINGBANK            | 5         | 8      | 0.34%   |
| Faspeed             | 5         | 5      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB           | 23        | 1.42%   |
| WDC WD10EZEX-08WN4A0 1TB               | 17        | 1.05%   |
| SanDisk NVMe SSD Drive 512GB           | 16        | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB         | 15        | 0.92%   |
| Samsung MZVLB512HBJQ-000L2 512GB       | 14        | 0.86%   |
| HGST HTS721010A9E630 1TB               | 14        | 0.86%   |
| Seagate ST1000LM048-2E7172 1TB         | 12        | 0.74%   |
| Seagate ST1000DM003-1SB102 1TB         | 12        | 0.74%   |
| Samsung NVMe SSD Drive 256GB           | 12        | 0.74%   |
| Samsung NVMe SSD Drive 1024GB          | 12        | 0.74%   |
| Samsung SSD 860 EVO 500GB              | 11        | 0.68%   |
| WDC WDS100T2B0C-00PXH0 1TB             | 10        | 0.62%   |
| SK hynix NVMe SSD Drive 512GB          | 10        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB        | 10        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB         | 10        | 0.62%   |
| SanDisk NVMe SSD Drive 1TB             | 9         | 0.55%   |
| Unknown                                | 9         | 0.55%   |
| Unknown MMC Card  64GB                 | 8         | 0.49%   |
| Toshiba NVMe SSD Drive 128GB           | 8         | 0.49%   |
| Seagate ST500DM002-1BD142 500GB        | 8         | 0.49%   |
| Seagate ST2000LM007-1R8174 2TB         | 8         | 0.49%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 8         | 0.49%   |
| Samsung MZVLB512HAJQ-00000 512GB       | 8         | 0.49%   |
| Plextor PX-128M6S 128GB SSD            | 8         | 0.49%   |
| Toshiba MQ01ABD100 1TB                 | 7         | 0.43%   |
| Seagate ST500LM021-1KJ152 500GB        | 7         | 0.43%   |
| Samsung NVMe SSD Drive 1TB             | 7         | 0.43%   |
| Samsung NVMe SSD Drive 128GB           | 7         | 0.43%   |
| WDC WD10EZEX-08M2NA0 1TB               | 6         | 0.37%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB   | 6         | 0.37%   |
| Toshiba DT01ACA200 2TB                 | 6         | 0.37%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB | 6         | 0.37%   |
| Seagate ST3500418AS 500GB              | 6         | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 6         | 0.37%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.37%   |
| Samsung NVMe SSD Drive 500GB           | 6         | 0.37%   |
| JMicron Generic 120GB                  | 6         | 0.37%   |
| HGST HTS725050A7E630 500GB             | 6         | 0.37%   |
| GALAX TA1D0240A 240GB                  | 6         | 0.37%   |
| Unknown MMC Card  32GB                 | 5         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 184       | 290    | 41.26%  |
| WDC                 | 145       | 183    | 32.51%  |
| Toshiba             | 41        | 52     | 9.19%   |
| HGST                | 33        | 49     | 7.4%    |
| Hitachi             | 17        | 27     | 3.81%   |
| Samsung Electronics | 9         | 10     | 2.02%   |
| Fujitsu             | 6         | 6      | 1.35%   |
| Pear 2TB            | 5         | 5      | 1.12%   |
| ACASIS              | 2         | 2      | 0.45%   |
| LIO-ORG             | 1         | 9      | 0.22%   |
| IBM H0              | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| Unknown             | 1         | 2      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 86        | 105    | 20.43%  |
| Kingston            | 27        | 34     | 6.41%   |
| SanDisk             | 26        | 28     | 6.18%   |
| Toshiba             | 25        | 28     | 5.94%   |
| Plextor             | 23        | 26     | 5.46%   |
| Intel               | 19        | 26     | 4.51%   |
| WDC                 | 15        | 17     | 3.56%   |
| LITEON              | 14        | 18     | 3.33%   |
| Crucial             | 12        | 15     | 2.85%   |
| A-DATA Technology   | 12        | 15     | 2.85%   |
| Micron Technology   | 11        | 11     | 2.61%   |
| Lenovo              | 11        | 13     | 2.61%   |
| GALAX               | 10        | 10     | 2.38%   |
| Netac               | 8         | 9      | 1.9%    |
| Teclast             | 7         | 7      | 1.66%   |
| China               | 7         | 10     | 1.66%   |
| FORESEE             | 6         | 6      | 1.43%   |
| Transcend           | 5         | 6      | 1.19%   |
| SK hynix            | 5         | 5      | 1.19%   |
| GLOWAY              | 5         | 5      | 1.19%   |
| Colorful            | 4         | 4      | 0.95%   |
| Apple               | 4         | 4      | 0.95%   |
| Unknown             | 4         | 5      | 0.95%   |
| Unknown             | 3         | 4      | 0.71%   |
| LITEONIT            | 3         | 3      | 0.71%   |
| Lexar               | 3         | 3      | 0.71%   |
| Kingchuxing         | 3         | 3      | 0.71%   |
| ZHITAI              | 2         | 2      | 0.48%   |
| Vaseky              | 2         | 2      | 0.48%   |
| tigo                | 2         | 2      | 0.48%   |
| Q200                | 2         | 5      | 0.48%   |
| Phison              | 2         | 3      | 0.48%   |
| Pear                | 2         | 2      | 0.48%   |
| OCZ                 | 2         | 2      | 0.48%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.48%   |
| KingShare           | 2         | 2      | 0.48%   |
| KINGBANK            | 2         | 2      | 0.48%   |
| Hewlett-Packard     | 2         | 3      | 0.48%   |
| Galaxy              | 2         | 2      | 0.48%   |
| Faspeed             | 2         | 2      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 481       | 664    | 35.76%  |
| HDD     | 389       | 637    | 28.92%  |
| SSD     | 367       | 520    | 27.29%  |
| MMC     | 60        | 80     | 4.46%   |
| Unknown | 48        | 57     | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 608       | 1143   | 49.92%  |
| NVMe | 479       | 651    | 39.33%  |
| SAS  | 71        | 84     | 5.83%   |
| MMC  | 60        | 80     | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 407       | 632    | 52.99%  |
| 0.51-1.0   | 249       | 308    | 32.42%  |
| 1.01-2.0   | 61        | 75     | 7.94%   |
| 3.01-4.0   | 17        | 29     | 2.21%   |
| 4.01-10.0  | 15        | 78     | 1.95%   |
| 2.01-3.0   | 14        | 25     | 1.82%   |
| 10.01-20.0 | 5         | 10     | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 251       | 24.42%  |
| 251-500        | 246       | 23.93%  |
| 501-1000       | 156       | 15.18%  |
| 51-100         | 94        | 9.14%   |
| 1001-2000      | 80        | 7.78%   |
| 1-20           | 56        | 5.45%   |
| More than 3000 | 49        | 4.77%   |
| 21-50          | 42        | 4.09%   |
| 2001-3000      | 29        | 2.82%   |
| Unknown        | 25        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 420       | 39.7%   |
| 21-50          | 169       | 15.97%  |
| 101-250        | 141       | 13.33%  |
| 51-100         | 111       | 10.49%  |
| 251-500        | 90        | 8.51%   |
| 501-1000       | 46        | 4.35%   |
| 1001-2000      | 29        | 2.74%   |
| Unknown        | 25        | 2.36%   |
| More than 3000 | 14        | 1.32%   |
| 2001-3000      | 13        | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                       | 2         | 2      | 3.64%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 3.64%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 2      | 3.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 3.64%   |
| Crucial CT240M500SSD1 240GB                  | 2         | 2      | 3.64%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1      | 1.82%   |
| WDC WD5003ABYZ-011FA0 500GB                  | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-08ERMA0 500GB                 | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-00PWEA0 500GB                 | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-0 500GB                       | 1         | 1      | 1.82%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.82%   |
| WDC WD10SPZX-60Z10T0 1TB                     | 1         | 1      | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.82%   |
| Toshiba MK3259GSXP 320GB                     | 1         | 1      | 1.82%   |
| Toshiba MK2555GSX 250GB                      | 1         | 1      | 1.82%   |
| Toshiba DT01ACA300 3TB                       | 1         | 1      | 1.82%   |
| Seagate ST980811AS 80GB                      | 1         | 1      | 1.82%   |
| Seagate ST750LM028-1KK162 752GB              | 1         | 1      | 1.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.82%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 2      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.82%   |
| Seagate ST500DM009-2DM14C 500GB              | 1         | 1      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.82%   |
| Seagate ST5000AS0011-1L5178 5TB              | 1         | 1      | 1.82%   |
| Seagate ST31000524AS 1TB                     | 1         | 1      | 1.82%   |
| SanDisk SSD U100 128GB                       | 1         | 1      | 1.82%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD          | 1         | 1      | 1.82%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 1.82%   |
| Samsung Electronics MZVLW512HMJP-00000 512GB | 1         | 1      | 1.82%   |
| Plextor PX-256M6S+ 256GB SSD                 | 1         | 1      | 1.82%   |
| Plextor PX-128M6S 128GB SSD                  | 1         | 1      | 1.82%   |
| Netac SSD 120GB                              | 1         | 1      | 1.82%   |
| Lenovo SSD SL700 120G                        | 1         | 1      | 1.82%   |
| Intel SSDSC2KW240H6 240GB                    | 1         | 1      | 1.82%   |
| Intel SSDSC2BW360H6 360GB                    | 1         | 1      | 1.82%   |
| Intel SSDPEKKF256G7H 256GB                   | 1         | 1      | 1.82%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 1.82%   |
| Hitachi HTS541060G9SA00 64GB                 | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 16     | 25.93%  |
| WDC                 | 10        | 10     | 18.52%  |
| Toshiba             | 5         | 5      | 9.26%   |
| Intel               | 3         | 3      | 5.56%   |
| Hitachi             | 3         | 3      | 5.56%   |
| Crucial             | 3         | 3      | 5.56%   |
| SanDisk             | 2         | 2      | 3.7%    |
| Samsung Electronics | 2         | 2      | 3.7%    |
| Plextor             | 2         | 2      | 3.7%    |
| HGST                | 2         | 2      | 3.7%    |
| Fujitsu             | 2         | 2      | 3.7%    |
| A-DATA Technology   | 2         | 3      | 3.7%    |
| Netac               | 1         | 1      | 1.85%   |
| Lenovo              | 1         | 1      | 1.85%   |
| GLOWAY              | 1         | 1      | 1.85%   |
| Colorful            | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 16     | 40%     |
| WDC     | 9         | 9      | 25.71%  |
| Toshiba | 5         | 5      | 14.29%  |
| Hitachi | 3         | 3      | 8.57%   |
| HGST    | 2         | 2      | 5.71%   |
| Fujitsu | 2         | 2      | 5.71%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 37     | 66.67%  |
| SSD  | 14        | 17     | 27.45%  |
| NVMe | 3         | 3      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST31500341AS 1TB          | 1         | 1      | 25%     |
| Samsung Electronics HS06THB 64GB  | 1         | 1      | 25%     |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 25%     |
| Phison ESO128GTLC9-E8C-2 128GB    | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 50%     |
| Seagate             | 1         | 1      | 25%     |
| Phison              | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 535       | 1001   | 50.38%  |
| Works    | 474       | 896    | 44.63%  |
| Malfunc  | 49        | 57     | 4.61%   |
| Failed   | 4         | 4      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 599       | 45.76%  |
| Samsung Electronics              | 178       | 13.6%   |
| AMD                              | 150       | 11.46%  |
| SanDisk                          | 92        | 7.03%   |
| SK hynix                         | 40        | 3.06%   |
| Toshiba America Info Systems     | 35        | 2.67%   |
| Silicon Motion                   | 34        | 2.6%    |
| Phison Electronics               | 18        | 1.38%   |
| Marvell Technology Group         | 18        | 1.38%   |
| KIOXIA                           | 16        | 1.22%   |
| Micron Technology                | 15        | 1.15%   |
| Kingston Technology Company      | 15        | 1.15%   |
| ASMedia Technology               | 11        | 0.84%   |
| LSI Logic / Symbios Logic        | 8         | 0.61%   |
| Broadcom / LSI                   | 8         | 0.61%   |
| Lite-On Technology               | 7         | 0.53%   |
| Shenzhen Longsys Electronics     | 6         | 0.46%   |
| Yangtze Memory Technologies      | 5         | 0.38%   |
| JMicron Technology               | 5         | 0.38%   |
| ADATA Technology                 | 5         | 0.38%   |
| Union Memory (Shenzhen)          | 4         | 0.31%   |
| Solid State Storage Technology   | 4         | 0.31%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.31%   |
| Apple                            | 4         | 0.31%   |
| Zhaoxin                          | 3         | 0.23%   |
| Silicon Integrated Systems [SiS] | 3         | 0.23%   |
| Micron/Crucial Technology        | 3         | 0.23%   |
| Huawei Technologies              | 3         | 0.23%   |
| Mylex                            | 2         | 0.15%   |
| Biwin Storage Technology         | 2         | 0.15%   |
| Beijing Starblaze Technology     | 2         | 0.15%   |
| Silicon Image                    | 1         | 0.08%   |
| Seagate Technology               | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Nvidia                           | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Lenovo                           | 1         | 0.08%   |
| IBM                              | 1         | 0.08%   |
| HighPoint Technologies           | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 118       | 8.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 103       | 7.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 63        | 4.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 3.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 37        | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 2.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 30        | 2.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 26        | 1.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 26        | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 22        | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 22        | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 22        | 1.52%   |
| SK hynix Gold P31 SSD                                                          | 21        | 1.45%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 1.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 1.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 20        | 1.38%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 19        | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 17        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 1.11%   |
| SanDisk Non-Volatile memory controller                                         | 15        | 1.04%   |
| Micron Non-Volatile memory controller                                          | 15        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 1.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 13        | 0.9%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 13        | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12        | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 11        | 0.76%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 11        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 11        | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 0.69%   |
| SK hynix Non-Volatile memory controller                                        | 9         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                              | 9         | 0.62%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 671       | 51.38%  |
| NVMe | 483       | 36.98%  |
| RAID | 74        | 5.67%   |
| IDE  | 68        | 5.21%   |
| SAS  | 7         | 0.54%   |
| SCSI | 3         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 730       | 73.59%  |
| AMD               | 218       | 21.98%  |
| PHYTIUM           | 12        | 1.21%   |
| ARM               | 10        | 1.01%   |
| Unknown           | 8         | 0.81%   |
| sifive,bullet0    | 3         | 0.3%    |
| CentaurHauls      | 3         | 0.3%    |
| sifive,u74-mc     | 2         | 0.2%    |
| QUALCOMM          | 2         | 0.2%    |
| CHRP IBM,9131-52A | 2         | 0.2%    |
| PowerNV FP5466G2  | 1         | 0.1%    |
| CHRP IBM,8233-E8B | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 24        | 2.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 1.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 10        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.91%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 8         | 0.81%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 8         | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.81%   |
| ARM Processor                                 | 8         | 0.81%   |
|                                               | 8         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 7         | 0.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 7         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.7%    |
| AMD Ryzen 5 4600U with Radeon Graphics        | 7         | 0.7%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 7         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.6%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz              | 6         | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.6%    |
| Intel Celeron CPU J1900 @ 1.99GHz             | 6         | 0.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.6%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 0.6%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 5         | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.5%    |
| Intel Core i7-10700 CPU @ 2.90GHz             | 5         | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 221       | 22.28%  |
| Intel Core i7           | 213       | 21.47%  |
| Other                   | 113       | 11.39%  |
| AMD Ryzen 5             | 76        | 7.66%   |
| AMD Ryzen 7             | 66        | 6.65%   |
| Intel Xeon              | 49        | 4.94%   |
| Intel Core i3           | 49        | 4.94%   |
| Intel Celeron           | 32        | 3.23%   |
| Intel Pentium           | 20        | 2.02%   |
| Intel Core 2 Duo        | 16        | 1.61%   |
| Intel Atom              | 15        | 1.51%   |
| AMD Ryzen 7 PRO         | 13        | 1.31%   |
| Intel Core i9           | 9         | 0.91%   |
| AMD Ryzen 9             | 8         | 0.81%   |
| AMD FX                  | 6         | 0.6%    |
| AMD Athlon II X2        | 6         | 0.6%    |
| AMD A8                  | 6         | 0.6%    |
| AMD A6                  | 6         | 0.6%    |
| AMD A10                 | 6         | 0.6%    |
| Intel Core m3           | 5         | 0.5%    |
| AMD Ryzen 5 PRO         | 5         | 0.5%    |
| Intel Xeon Silver       | 4         | 0.4%    |
| Intel Pentium Dual      | 4         | 0.4%    |
| Intel Xeon Gold         | 3         | 0.3%    |
| Intel Pentium Silver    | 3         | 0.3%    |
| Intel Pentium Dual-Core | 3         | 0.3%    |
| Intel Genuine           | 3         | 0.3%    |
| AMD Athlon              | 3         | 0.3%    |
| Intel Core M            | 2         | 0.2%    |
| Intel Core 2 Quad       | 2         | 0.2%    |
| Intel Core 2            | 2         | 0.2%    |
| AMD Ryzen 3             | 2         | 0.2%    |
| AMD EPYC                | 2         | 0.2%    |
| AMD Athlon X4           | 2         | 0.2%    |
| QUALCOMM AArch64        | 1         | 0.1%    |
| Intel Xeon Platinum     | 1         | 0.1%    |
| Intel Xeon Bronze       | 1         | 0.1%    |
| Intel Pentium M         | 1         | 0.1%    |
| Intel Core m5           | 1         | 0.1%    |
| Intel Core Duo          | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 392       | 39.44%  |
| 2       | 267       | 26.86%  |
| 6       | 131       | 13.18%  |
| 8       | 122       | 12.27%  |
| 12      | 18        | 1.81%   |
| 1       | 13        | 1.31%   |
| 16      | 10        | 1.01%   |
| Unknown | 8         | 0.8%    |
| 24      | 7         | 0.7%    |
| 14      | 6         | 0.6%    |
| 10      | 6         | 0.6%    |
| 32      | 4         | 0.4%    |
| 96      | 2         | 0.2%    |
| 20      | 2         | 0.2%    |
| 64      | 1         | 0.1%    |
| 40      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 949       | 95.57%  |
| 2       | 33        | 3.32%   |
| Unknown | 8         | 0.81%   |
| 6       | 1         | 0.1%    |
| 4       | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 749       | 75.35%  |
| 1       | 235       | 23.64%  |
| Unknown | 8         | 0.8%    |
| 4       | 2         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 958       | 96.38%  |
| Unknown        | 30        | 3.02%   |
| 32-bit         | 4         | 0.4%    |
| 64-bit         | 2         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 214       | 21.08%  |
| 0x906ea    | 51        | 5.02%   |
| 0x306c3    | 47        | 4.63%   |
| 0x306a9    | 44        | 4.33%   |
| 0x806ea    | 34        | 3.35%   |
| 0x206a7    | 34        | 3.35%   |
| 0x806e9    | 31        | 3.05%   |
| 0x0a50000c | 31        | 3.05%   |
| 0x806ec    | 30        | 2.96%   |
| 0x506e3    | 30        | 2.96%   |
| 0x806c1    | 28        | 2.76%   |
| 0x906e9    | 27        | 2.66%   |
| 0x08600106 | 25        | 2.46%   |
| 0x40651    | 21        | 2.07%   |
| 0x306d4    | 19        | 1.87%   |
| 0x406e3    | 16        | 1.58%   |
| 0x08108102 | 15        | 1.48%   |
| 0x1067a    | 13        | 1.28%   |
| 0xa0652    | 12        | 1.18%   |
| 0x08600104 | 12        | 1.18%   |
| 0x806d1    | 11        | 1.08%   |
| 0x08108109 | 11        | 1.08%   |
| 0xa0655    | 9         | 0.89%   |
| 0x906a3    | 9         | 0.89%   |
| 0x706e5    | 8         | 0.79%   |
| 0x08701013 | 8         | 0.79%   |
| 0xa0660    | 7         | 0.69%   |
| 0x50654    | 7         | 0.69%   |
| 0x306e4    | 7         | 0.69%   |
| 0x30678    | 7         | 0.69%   |
| 0x706a1    | 6         | 0.59%   |
| 0x306f2    | 6         | 0.59%   |
| 0x08600103 | 6         | 0.59%   |
| 0x0810100b | 6         | 0.59%   |
| 0x806eb    | 5         | 0.49%   |
| 0x6fd      | 5         | 0.49%   |
| 0x406c3    | 5         | 0.49%   |
| 0x06001119 | 5         | 0.49%   |
| 0xa0653    | 4         | 0.39%   |
| 0x906ed    | 4         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 228       | 22.94%  |
| Haswell          | 92        | 9.26%   |
| Zen 2            | 68        | 6.84%   |
| Skylake          | 67        | 6.74%   |
| Unknown          | 61        | 6.14%   |
| IvyBridge        | 60        | 6.04%   |
| Zen 3            | 47        | 4.73%   |
| SandyBridge      | 41        | 4.12%   |
| CometLake        | 41        | 4.12%   |
| TigerLake        | 40        | 4.02%   |
| Zen+             | 34        | 3.42%   |
| Silvermont       | 26        | 2.62%   |
| Broadwell        | 26        | 2.62%   |
| Penryn           | 21        | 2.11%   |
| IceLake          | 21        | 2.11%   |
| Zen              | 19        | 1.91%   |
| Alderlake Hybrid | 11        | 1.11%   |
| Westmere         | 10        | 1.01%   |
| Piledriver       | 10        | 1.01%   |
| Goldmont plus    | 10        | 1.01%   |
| Core             | 9         | 0.91%   |
| K10              | 8         | 0.8%    |
| Steamroller      | 6         | 0.6%    |
| Goldmont         | 5         | 0.5%    |
| Bonnell          | 5         | 0.5%    |
| Nehalem          | 4         | 0.4%    |
| Excavator        | 4         | 0.4%    |
| Tremont          | 3         | 0.3%    |
| Puma             | 3         | 0.3%    |
| Sapphire Rapids  | 2         | 0.2%    |
| P6               | 2         | 0.2%    |
| K10 Llano        | 2         | 0.2%    |
| Jaguar           | 2         | 0.2%    |
| Bulldozer        | 2         | 0.2%    |
| Bobcat           | 2         | 0.2%    |
| NetBurst         | 1         | 0.1%    |
| K8 Hammer        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 587       | 47.22%  |
| Nvidia                           | 338       | 27.19%  |
| AMD                              | 284       | 22.85%  |
| Matrox Electronics Systems       | 14        | 1.13%   |
| ASPEED Technology                | 12        | 0.97%   |
| Zhaoxin                          | 3         | 0.24%   |
| Silicon Integrated Systems [SiS] | 2         | 0.16%   |
| Phytium Technology               | 1         | 0.08%   |
| Loongson Technology              | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 45        | 3.55%   |
| Intel UHD Graphics 620                                                                   | 41        | 3.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 3.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 2.76%   |
| AMD Cezanne                                                                              | 34        | 2.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 2.21%   |
| Intel HD Graphics 630                                                                    | 25        | 1.97%   |
| Intel HD Graphics 530                                                                    | 24        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 1.82%   |
| Intel HD Graphics 620                                                                    | 22        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 1.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 1.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 1.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.18%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 1.1%    |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.95%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 0.95%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 11        | 0.87%   |
| Nvidia TU117M [GeForce MX450]                                                            | 10        | 0.79%   |
| Nvidia TU117M                                                                            | 10        | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 10        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 0.79%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 10        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 9         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 8         | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.63%   |
| Intel Comet Lake UHD Graphics                                                            | 8         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 351       | 35.17%  |
| 1 x AMD                      | 201       | 20.14%  |
| Intel + Nvidia               | 181       | 18.14%  |
| 1 x Nvidia                   | 126       | 12.63%  |
| Intel + AMD                  | 41        | 4.11%   |
| AMD + Nvidia                 | 24        | 2.4%    |
| Other                        | 19        | 1.9%    |
| 2 x AMD                      | 13        | 1.3%    |
| 1 x Matrox                   | 12        | 1.2%    |
| 1 x ASPEED                   | 7         | 0.7%    |
| 2 x Nvidia                   | 3         | 0.3%    |
| 2 x Intel                    | 3         | 0.3%    |
| 1 x Zhaoxin                  | 3         | 0.3%    |
| AMD + ASPEED                 | 3         | 0.3%    |
| 1 x SiS                      | 2         | 0.2%    |
| Nvidia + ASPEED              | 2         | 0.2%    |
| AMD + Matrox                 | 2         | 0.2%    |
| 1 x Phytium Technology       | 1         | 0.1%    |
| Nvidia + Huawei Technologies | 1         | 0.1%    |
| 1 x Loongson Technology      | 1         | 0.1%    |
| 1 x Intel + 3 x Nvidia       | 1         | 0.1%    |
| Intel + 2 x Nvidia           | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 746       | 74.38%  |
| Proprietary | 174       | 17.35%  |
| Unknown     | 83        | 8.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 553       | 54.81%  |
| 1.01-2.0   | 137       | 13.58%  |
| 0.01-0.5   | 84        | 8.33%   |
| 0.51-1.0   | 81        | 8.03%   |
| 3.01-4.0   | 61        | 6.05%   |
| 5.01-6.0   | 36        | 3.57%   |
| 7.01-8.0   | 35        | 3.47%   |
| 8.01-16.0  | 10        | 0.99%   |
| 2.01-3.0   | 6         | 0.59%   |
| 4.01-5.0   | 2         | 0.2%    |
| 24.01-32.0 | 2         | 0.2%    |
| 16.01-24.0 | 2         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 122       | 12.14%  |
| AU Optronics            | 99        | 9.85%   |
| LG Display              | 95        | 9.45%   |
| Chimei Innolux          | 93        | 9.25%   |
| Dell                    | 84        | 8.36%   |
| Samsung Electronics     | 55        | 5.47%   |
| Lenovo                  | 55        | 5.47%   |
| AOC                     | 53        | 5.27%   |
| Sharp                   | 38        | 3.78%   |
| Philips                 | 28        | 2.79%   |
| Goldstar                | 23        | 2.29%   |
| CSO                     | 22        | 2.19%   |
| Hewlett-Packard         | 20        | 1.99%   |
| ViewSonic               | 13        | 1.29%   |
| BenQ                    | 13        | 1.29%   |
| PANDA                   | 11        | 1.09%   |
| InfoVision              | 10        | 1%      |
| Apple                   | 10        | 1%      |
| Acer                    | 10        | 1%      |
| Xiaomi                  | 8         | 0.8%    |
| HKC                     | 8         | 0.8%    |
| TMX                     | 5         | 0.5%    |
| SGT                     | 5         | 0.5%    |
| Unknown                 | 4         | 0.4%    |
| Mi                      | 4         | 0.4%    |
| IPS                     | 4         | 0.4%    |
| CHD                     | 4         | 0.4%    |
| RTK                     | 3         | 0.3%    |
| Panasonic               | 3         | 0.3%    |
| LGD                     | 3         | 0.3%    |
| KOIOS                   | 3         | 0.3%    |
| JDI                     | 3         | 0.3%    |
| HannStar                | 3         | 0.3%    |
| CHR                     | 3         | 0.3%    |
| Chi Mei Optoelectronics | 3         | 0.3%    |
| BOE Technology Group    | 3         | 0.3%    |
| ASUSTek Computer        | 3         | 0.3%    |
| Ancor Communications    | 3         | 0.3%    |
| TFC                     | 2         | 0.2%    |
| Sony                    | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 10        | 0.97%   |
| Xiaomi Mi TV XMD004A 3840x2160 1110x620mm 50.1-inch                  | 7         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 7         | 0.68%   |
| Dell P2422H DELA1C5 1920x1080 527x296mm 23.8-inch                    | 6         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 6         | 0.58%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 6         | 0.58%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 6         | 0.58%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 6         | 0.58%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch              | 5         | 0.49%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 5         | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 5         | 0.49%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch              | 4         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 4         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 0.39%   |
| Lenovo L2250p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 4         | 0.39%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch         | 4         | 0.39%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 4         | 0.39%   |
| CHD CHHWJT CHD0030 1920x1080 934x532mm 42.3-inch                     | 4         | 0.39%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 4         | 0.39%   |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                    | 4         | 0.39%   |
| AOC 2491W AOC2491 1920x1080 521x293mm 23.5-inch                      | 4         | 0.39%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch              | 3         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 309x174mm 14.0-inch | 3         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.29%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 3         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 0.29%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 3         | 0.29%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                     | 3         | 0.29%   |
| LG Display LCD Monitor LGD0618 1920x1080 344x194mm 15.5-inch         | 3         | 0.29%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch         | 3         | 0.29%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 3         | 0.29%   |
| Lenovo LEN T2254A LEN60CD 1680x1050 474x296mm 22.0-inch              | 3         | 0.29%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch              | 3         | 0.29%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 504       | 52.39%  |
| 1366x768 (WXGA)    | 107       | 11.12%  |
| 3840x2160 (4K)     | 84        | 8.73%   |
| 2560x1440 (QHD)    | 59        | 6.13%   |
| 2560x1600          | 28        | 2.91%   |
| 1440x900 (WXGA+)   | 26        | 2.7%    |
| 1600x900 (HD+)     | 20        | 2.08%   |
| 1920x1200 (WUXGA)  | 15        | 1.56%   |
| 1680x1050 (WSXGA+) | 13        | 1.35%   |
| 1280x1024 (SXGA)   | 12        | 1.25%   |
| 2160x1440          | 9         | 0.94%   |
| Unknown            | 9         | 0.94%   |
| 3440x1440          | 7         | 0.73%   |
| 1280x800 (WXGA)    | 7         | 0.73%   |
| 2880x1800          | 6         | 0.62%   |
| 3200x2000          | 4         | 0.42%   |
| 3000x2000          | 3         | 0.31%   |
| 2560x1080          | 3         | 0.31%   |
| 2240x1400          | 3         | 0.31%   |
| 1800x1200          | 3         | 0.31%   |
| 3840x2400          | 2         | 0.21%   |
| 3360x1080          | 2         | 0.21%   |
| 3286x1080          | 2         | 0.21%   |
| 3072x1920          | 2         | 0.21%   |
| 2736x1824          | 2         | 0.21%   |
| 2288x1287          | 2         | 0.21%   |
| 2256x1504          | 2         | 0.21%   |
| 2200x1650          | 2         | 0.21%   |
| 2160x1350          | 2         | 0.21%   |
| 1920x1280          | 2         | 0.21%   |
| 1400x1050          | 2         | 0.21%   |
| 1024x768 (XGA)     | 2         | 0.21%   |
| 1024x600           | 2         | 0.21%   |
| 5206x1080          | 1         | 0.1%    |
| 4480x1440          | 1         | 0.1%    |
| 4382x1080          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 3600x1080          | 1         | 0.1%    |
| 3520x1080          | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 193       | 19.24%  |
| 13      | 154       | 15.35%  |
| 14      | 124       | 12.36%  |
| 23      | 86        | 8.57%   |
| 24      | 72        | 7.18%   |
| 27      | 69        | 6.88%   |
| 21      | 44        | 4.39%   |
| Unknown | 40        | 3.99%   |
| 12      | 32        | 3.19%   |
| 17      | 31        | 3.09%   |
| 16      | 28        | 2.79%   |
| 19      | 20        | 1.99%   |
| 18      | 15        | 1.5%    |
| 31      | 12        | 1.2%    |
| 22      | 11        | 1.1%    |
| 65      | 8         | 0.8%    |
| 25      | 8         | 0.8%    |
| 20      | 8         | 0.8%    |
| 34      | 7         | 0.7%    |
| 11      | 7         | 0.7%    |
| 10      | 6         | 0.6%    |
| 40      | 5         | 0.5%    |
| 63      | 4         | 0.4%    |
| 32      | 3         | 0.3%    |
| 28      | 3         | 0.3%    |
| 26      | 3         | 0.3%    |
| 142     | 2         | 0.2%    |
| 43      | 2         | 0.2%    |
| 66      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 46      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 406       | 40.97%  |
| 501-600        | 217       | 21.9%   |
| 201-300        | 130       | 13.12%  |
| 401-500        | 91        | 9.18%   |
| 351-400        | 44        | 4.44%   |
| Unknown        | 40        | 4.04%   |
| 601-700        | 27        | 2.72%   |
| 1001-1500      | 14        | 1.41%   |
| 701-800        | 10        | 1.01%   |
| 801-900        | 7         | 0.71%   |
| 901-1000       | 3         | 0.3%    |
| More than 2000 | 2         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 695       | 76.63%  |
| 16/10   | 120       | 13.23%  |
| Unknown | 38        | 4.19%   |
| 3/2     | 25        | 2.76%   |
| 5/4     | 13        | 1.43%   |
| 21/9    | 8         | 0.88%   |
| 4/3     | 5         | 0.55%   |
| 1.00    | 2         | 0.22%   |
| 0.45    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 206       | 20.6%   |
| 101-110        | 199       | 19.9%   |
| 201-250        | 168       | 16.8%   |
| 71-80          | 76        | 7.6%    |
| 301-350        | 73        | 7.3%    |
| 151-200        | 63        | 6.3%    |
| Unknown        | 40        | 4%      |
| 61-70          | 26        | 2.6%    |
| 251-300        | 26        | 2.6%    |
| 351-500        | 24        | 2.4%    |
| 121-130        | 23        | 2.3%    |
| 111-120        | 18        | 1.8%    |
| More than 1000 | 16        | 1.6%    |
| 141-150        | 13        | 1.3%    |
| 501-1000       | 11        | 1.1%    |
| 51-60          | 8         | 0.8%    |
| 41-50          | 5         | 0.5%    |
| 91-100         | 5         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 331       | 33.5%   |
| 51-100        | 257       | 26.01%  |
| 101-120       | 170       | 17.21%  |
| 161-240       | 138       | 13.97%  |
| Unknown       | 40        | 4.05%   |
| More than 240 | 37        | 3.74%   |
| 1-50          | 15        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 766       | 75.77%  |
| 2     | 138       | 13.65%  |
| 0     | 98        | 9.69%   |
| 3     | 9         | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 554       | 38.39%  |
| Realtek Semiconductor            | 544       | 37.7%   |
| Qualcomm Atheros                 | 125       | 8.66%   |
| Broadcom                         | 41        | 2.84%   |
| MediaTek                         | 24        | 1.66%   |
| Broadcom Limited                 | 20        | 1.39%   |
| Ralink Technology                | 18        | 1.25%   |
| Huawei Technologies              | 13        | 0.9%    |
| ASIX Electronics                 | 13        | 0.9%    |
| Xiaomi                           | 12        | 0.83%   |
| Marvell Technology Group         | 8         | 0.55%   |
| Microsoft                        | 7         | 0.49%   |
| Ralink                           | 5         | 0.35%   |
| Qualcomm                         | 4         | 0.28%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.21%   |
| TP-Link                          | 3         | 0.21%   |
| Tenda                            | 3         | 0.21%   |
| Samsung Electronics              | 3         | 0.21%   |
| Quectel Wireless Solutions       | 3         | 0.21%   |
| Qualcomm Atheros Communications  | 3         | 0.21%   |
| Dell                             | 3         | 0.21%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Sierra Wireless                  | 2         | 0.14%   |
| OPPO Electronics                 | 2         | 0.14%   |
| NetGear                          | 2         | 0.14%   |
| IBM                              | 2         | 0.14%   |
| D-Link                           | 2         | 0.14%   |
| Aquantia                         | 2         | 0.14%   |
| Wilocity                         | 1         | 0.07%   |
| vivo                             | 1         | 0.07%   |
| ST-Ericsson                      | 1         | 0.07%   |
| Shenzhen Goodix Technology       | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.07%   |
| Oculus VR                        | 1         | 0.07%   |
| Nvidia                           | 1         | 0.07%   |
| NetXen Incorporated              | 1         | 0.07%   |
| Mellanox Technologies            | 1         | 0.07%   |
| Meizu                            | 1         | 0.07%   |
| Loongson Technology              | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 359       | 21.36%  |
| Intel Wi-Fi 6 AX200                                               | 74        | 4.4%    |
| Intel Wireless 8265 / 8275                                        | 49        | 2.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 43        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 26        | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 25        | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 1.49%   |
| Intel Wireless 7265                                               | 24        | 1.43%   |
| Intel Wireless 7260                                               | 22        | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 1.13%   |
| Intel Wireless 3165                                               | 19        | 1.13%   |
| Intel Wireless 8260                                               | 18        | 1.07%   |
| Intel I211 Gigabit Network Connection                             | 18        | 1.07%   |
| Realtek 802.11ac NIC                                              | 16        | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 15        | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 12        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10        | 0.59%   |
| Intel Wireless 3160                                               | 10        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 10        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 10        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 444       | 55.16%  |
| Realtek Semiconductor           | 141       | 17.52%  |
| Qualcomm Atheros                | 98        | 12.17%  |
| Broadcom                        | 26        | 3.23%   |
| MediaTek                        | 24        | 2.98%   |
| Ralink Technology               | 18        | 2.24%   |
| Broadcom Limited                | 15        | 1.86%   |
| Ralink                          | 5         | 0.62%   |
| Xiaomi                          | 3         | 0.37%   |
| TP-Link                         | 3         | 0.37%   |
| Tenda                           | 3         | 0.37%   |
| Quectel Wireless Solutions      | 3         | 0.37%   |
| Qualcomm Atheros Communications | 3         | 0.37%   |
| Microsoft                       | 3         | 0.37%   |
| Sierra Wireless                 | 2         | 0.25%   |
| Qualcomm                        | 2         | 0.25%   |
| NetGear                         | 2         | 0.25%   |
| Marvell Technology Group        | 2         | 0.25%   |
| Dell                            | 2         | 0.25%   |
| D-Link                          | 2         | 0.25%   |
| Wilocity                        | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Fibocom                         | 1         | 0.12%   |
| D-Link System                   | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 74        | 9.14%   |
| Intel Wireless 8265 / 8275                                              | 49        | 6.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 43        | 5.31%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 3.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 3.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 3.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 25        | 3.09%   |
| Intel Wireless 7265                                                     | 24        | 2.96%   |
| Intel Wireless 7260                                                     | 22        | 2.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 20        | 2.47%   |
| Intel Wireless 3165                                                     | 19        | 2.35%   |
| Intel Wireless 8260                                                     | 18        | 2.22%   |
| Realtek 802.11ac NIC                                                    | 16        | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 14        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 13        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.6%    |
| Ralink MT7601U Wireless Adapter                                         | 12        | 1.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 12        | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.23%   |
| Intel Wireless 3160                                                     | 10        | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.11%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 0.86%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 6         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.74%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 6         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 6         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 5         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 464       | 56.31%  |
| Intel                            | 239       | 29%     |
| Qualcomm Atheros                 | 34        | 4.13%   |
| Broadcom                         | 16        | 1.94%   |
| ASIX Electronics                 | 13        | 1.58%   |
| Huawei Technologies              | 12        | 1.46%   |
| Xiaomi                           | 9         | 1.09%   |
| Marvell Technology Group         | 6         | 0.73%   |
| Broadcom Limited                 | 5         | 0.61%   |
| Samsung Electronics              | 3         | 0.36%   |
| Microsoft                        | 3         | 0.36%   |
| Silicon Integrated Systems [SiS] | 2         | 0.24%   |
| OPPO Electronics                 | 2         | 0.24%   |
| IBM                              | 2         | 0.24%   |
| Aquantia                         | 2         | 0.24%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.12%   |
| Qualcomm                         | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.12%   |
| Nvidia                           | 1         | 0.12%   |
| NetXen Incorporated              | 1         | 0.12%   |
| Mellanox Technologies            | 1         | 0.12%   |
| Loongson Technology              | 1         | 0.12%   |
| ICS Advent                       | 1         | 0.12%   |
| Google                           | 1         | 0.12%   |
| DisplayLink                      | 1         | 0.12%   |
| Attansic Technology              | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 359       | 41.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45        | 5.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 2.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 2.21%   |
| Intel I211 Gigabit Network Connection                             | 18        | 2.1%    |
| Intel Ethernet Connection (2) I219-V                              | 15        | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.4%    |
| Intel Ethernet Controller I225-V                                  | 10        | 1.17%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 1.17%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1.17%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 1.05%   |
| Huawei YAL-L21                                                    | 9         | 1.05%   |
| Intel I350 Gigabit Network Connection                             | 8         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.82%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.82%   |
| Intel Ethernet Connection (12) I219-V                             | 7         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.58%   |
| Intel Ethernet Connection X722 for 1GbE                           | 5         | 0.58%   |
| Intel Ethernet Connection (3) I219-LM                             | 5         | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.58%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.58%   |
| ASIX AX88772B                                                     | 5         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 786       | 50.03%  |
| WiFi     | 772       | 49.14%  |
| Unknown  | 8         | 0.51%   |
| Modem    | 5         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 579       | 58.43%  |
| Ethernet | 411       | 41.47%  |
| Unknown  | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 497       | 50.05%  |
| 1     | 408       | 41.09%  |
| 0     | 43        | 4.33%   |
| 3     | 29        | 2.92%   |
| 4     | 10        | 1.01%   |
| 6     | 4         | 0.4%    |
| 8     | 1         | 0.1%    |
| 5     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 878       | 87.1%   |
| Yes  | 130       | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 388       | 59.24%  |
| Realtek Semiconductor           | 58        | 8.85%   |
| Qualcomm Atheros Communications | 51        | 7.79%   |
| Cambridge Silicon Radio         | 37        | 5.65%   |
| Realtek                         | 25        | 3.82%   |
| Broadcom                        | 21        | 3.21%   |
| Foxconn / Hon Hai               | 16        | 2.44%   |
| IMC Networks                    | 10        | 1.53%   |
| Lite-On Technology              | 8         | 1.22%   |
| Apple                           | 8         | 1.22%   |
| ASUSTek Computer                | 5         | 0.76%   |
| Opticis                         | 4         | 0.61%   |
| MediaTek                        | 4         | 0.61%   |
| Dell                            | 4         | 0.61%   |
| Ralink                          | 3         | 0.46%   |
| Foxconn International           | 3         | 0.46%   |
| Toshiba                         | 2         | 0.31%   |
| Taiyo Yuden                     | 2         | 0.31%   |
| Marvell Semiconductor           | 2         | 0.31%   |
| Hewlett-Packard                 | 2         | 0.31%   |
| Alps Electric                   | 2         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 143       | 21.83%  |
| Intel AX201 Bluetooth                               | 75        | 11.45%  |
| Intel AX200 Bluetooth                               | 71        | 10.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 54        | 8.24%   |
| Realtek Bluetooth Radio                             | 42        | 6.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37        | 5.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 36        | 5.5%    |
| Realtek Bluetooth Radio                             | 25        | 3.82%   |
| Intel AX210 Bluetooth                               | 12        | 1.83%   |
| Intel Bluetooth Device                              | 9         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.07%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.07%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.76%   |
| Opticis Bluetooth Radio                             | 4         | 0.61%   |
| MediaTek Wireless_Device                            | 4         | 0.61%   |
| Lite-On Bluetooth Device                            | 4         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.61%   |
| IMC Networks Bluetooth Device                       | 4         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 4         | 0.61%   |
| Apple Bluetooth Host Controller                     | 4         | 0.61%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.46%   |
| IMC Networks Wireless_Device                        | 3         | 0.46%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.46%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.46%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.46%   |
| Taiyo Yuden Bluetooth Device                        | 2         | 0.31%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.31%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.31%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]         | 2         | 0.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.31%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.31%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 687       | 55.54%  |
| AMD                                          | 278       | 22.47%  |
| Nvidia                                       | 206       | 16.65%  |
| C-Media Electronics                          | 9         | 0.73%   |
| Realtek Semiconductor                        | 5         | 0.4%    |
| Creative Labs                                | 5         | 0.4%    |
| XMOS                                         | 4         | 0.32%   |
| Apple                                        | 4         | 0.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.24%   |
| Zhaoxin                                      | 3         | 0.24%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.24%   |
| Huawei Technologies                          | 3         | 0.24%   |
| Generalplus Technology                       | 3         | 0.24%   |
| Texas Instruments                            | 2         | 0.16%   |
| Dell                                         | 2         | 0.16%   |
| Unknown                                      | 1         | 0.08%   |
| TerraTec Electronic                          | 1         | 0.08%   |
| Specialix                                    | 1         | 0.08%   |
| Sony                                         | 1         | 0.08%   |
| Polycom                                      | 1         | 0.08%   |
| Phytium Technology                           | 1         | 0.08%   |
| NXP Semiconductors                           | 1         | 0.08%   |
| Loongson Technology                          | 1         | 0.08%   |
| JMTek                                        | 1         | 0.08%   |
| Giga-Byte Technology                         | 1         | 0.08%   |
| Fry's Electronics                            | 1         | 0.08%   |
| ESI                                          | 1         | 0.08%   |
| DSEA A/S                                     | 1         | 0.08%   |
| Creative Technology                          | 1         | 0.08%   |
| Cambridge Silicon Radio                      | 1         | 0.08%   |
| BY EDIFIER                                   | 1         | 0.08%   |
| AudioQuest                                   | 1         | 0.08%   |
| Atmel                                        | 1         | 0.08%   |
| Actions Semiconductor                        | 1         | 0.08%   |
| ACTIONS                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 141       | 9.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 97        | 6.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 69        | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 55        | 3.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 55        | 3.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 3.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 42        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 40        | 2.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 39        | 2.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36        | 2.42%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.61%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.61%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                   | 22        | 1.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 1.34%   |
| AMD FCH Azalia Controller                                                  | 20        | 1.34%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 19        | 1.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 18        | 1.21%   |
| Nvidia GA106 High Definition Audio Controller                              | 17        | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 16        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 15        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                | 15        | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 15        | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 14        | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 199       | 29.7%   |
| SK hynix            | 124       | 18.51%  |
| Kingston            | 114       | 17.01%  |
| Micron Technology   | 69        | 10.3%   |
| Unknown             | 38        | 5.67%   |
| A-DATA Technology   | 25        | 3.73%   |
| Ramaxel Technology  | 20        | 2.99%   |
| Crucial             | 15        | 2.24%   |
| Corsair             | 7         | 1.04%   |
| Elpida              | 6         | 0.9%    |
| Unknown             | 6         | 0.9%    |
| Transcend           | 5         | 0.75%   |
| Unknown (ABCD)      | 4         | 0.6%    |
| Team                | 4         | 0.6%    |
| G.Skill             | 3         | 0.45%   |
| Apacer              | 3         | 0.45%   |
| Lenovo              | 2         | 0.3%    |
| Kingmax             | 2         | 0.3%    |
| Unknown (08C8)      | 1         | 0.15%   |
| Unknown (08B5)      | 1         | 0.15%   |
| UniIC               | 1         | 0.15%   |
| tigo                | 1         | 0.15%   |
| Thermaltake         | 1         | 0.15%   |
| Shenzhen WODPOSIT   | 1         | 0.15%   |
| Shenzhen Longsys    | 1         | 0.15%   |
| SHARETRONIC         | 1         | 0.15%   |
| Ramsta              | 1         | 0.15%   |
| Nanya Technology    | 1         | 0.15%   |
| MTASE               | 1         | 0.15%   |
| Mircon              | 1         | 0.15%   |
| MAXSUN              | 1         | 0.15%   |
| Lexar Co Limited    | 1         | 0.15%   |
| KLEVV               | 1         | 0.15%   |
| KINGBANK            | 1         | 0.15%   |
| Kimtigo             | 1         | 0.15%   |
| Juhor               | 1         | 0.15%   |
| JEDEC ID: 0000h     | 1         | 0.15%   |
| GLOWAY              | 1         | 0.15%   |
| GeIL                | 1         | 0.15%   |
| Essencore           | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 1.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.24%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 8         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.83%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 6         | 0.83%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 6         | 0.83%   |
| Unknown                                                          | 6         | 0.83%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 5         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.69%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 5         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.69%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 5         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 4         | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.55%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.55%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.55%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 4         | 0.55%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                   | 4         | 0.55%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.55%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.55%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.55%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 4         | 0.55%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 4         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.41%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.41%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 334       | 55.95%  |
| DDR3    | 158       | 26.47%  |
| LPDDR3  | 33        | 5.53%   |
| LPDDR4  | 29        | 4.86%   |
| Unknown | 12        | 2.01%   |
| SDRAM   | 10        | 1.68%   |
| DDR5    | 9         | 1.51%   |
| DDR2    | 9         | 1.51%   |
| LPDDR5  | 2         | 0.34%   |
| DDR     | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 323       | 53.92%  |
| DIMM         | 169       | 28.21%  |
| Row Of Chips | 103       | 17.2%   |
| Chip         | 3         | 0.5%    |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 275       | 43.58%  |
| 4096  | 161       | 25.52%  |
| 16384 | 117       | 18.54%  |
| 2048  | 37        | 5.86%   |
| 32768 | 29        | 4.6%    |
| 1024  | 8         | 1.27%   |
| 65536 | 3         | 0.48%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 123       | 19.28%  |
| 3200    | 116       | 18.18%  |
| 1600    | 113       | 17.71%  |
| 2400    | 45        | 7.05%   |
| 2133    | 40        | 6.27%   |
| 1333    | 27        | 4.23%   |
| 1867    | 18        | 2.82%   |
| 4267    | 17        | 2.66%   |
| 2666    | 16        | 2.51%   |
| 4800    | 12        | 1.88%   |
| 3600    | 12        | 1.88%   |
| 800     | 10        | 1.57%   |
| 1334    | 7         | 1.1%    |
| 3266    | 6         | 0.94%   |
| 2668    | 6         | 0.94%   |
| 2933    | 5         | 0.78%   |
| 1066    | 5         | 0.78%   |
| 667     | 5         | 0.78%   |
| Unknown | 5         | 0.78%   |
| 3733    | 4         | 0.63%   |
| 3466    | 4         | 0.63%   |
| 3000    | 4         | 0.63%   |
| 1866    | 4         | 0.63%   |
| 1067    | 4         | 0.63%   |
| 8400    | 3         | 0.47%   |
| 4266    | 3         | 0.47%   |
| 4199    | 3         | 0.47%   |
| 3400    | 3         | 0.47%   |
| 6400    | 2         | 0.31%   |
| 2800    | 2         | 0.31%   |
| 1800    | 2         | 0.31%   |
| 266     | 2         | 0.31%   |
| 4133    | 1         | 0.16%   |
| 3800    | 1         | 0.16%   |
| 3500    | 1         | 0.16%   |
| 3467    | 1         | 0.16%   |
| 2200    | 1         | 0.16%   |
| 2187    | 1         | 0.16%   |
| 2048    | 1         | 0.16%   |
| 533     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 3         | 42.86%  |
| Canon                              | 2         | 28.57%  |
| Brother Industries                 | 1         | 14.29%  |
| BeiJing LanXum Computer Technology | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                        | 2         | 28.57%  |
| HP Officejet 4500 G510g-m                               | 1         | 14.29%  |
| Canon PIXMA MP280                                       | 1         | 14.29%  |
| Canon iP1100 series                                     | 1         | 14.29%  |
| Brother HL-5440D series                                 | 1         | 14.29%  |
| BeiJing LanXum Technology Black and White Laser Printer | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 110       | 19.93%  |
| IMC Networks                           | 87        | 15.76%  |
| Acer                                   | 59        | 10.69%  |
| Microdia                               | 40        | 7.25%   |
| Realtek Semiconductor                  | 38        | 6.88%   |
| Sunplus Innovation Technology          | 34        | 6.16%   |
| Quanta                                 | 28        | 5.07%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 4.89%   |
| Syntek                                 | 20        | 3.62%   |
| Suyin                                  | 15        | 2.72%   |
| Lite-On Technology                     | 13        | 2.36%   |
| Luxvisions Innotech Limited            | 11        | 1.99%   |
| Logitech                               | 9         | 1.63%   |
| Apple                                  | 9         | 1.63%   |
| Alcor Micro                            | 8         | 1.45%   |
| Silicon Motion                         | 7         | 1.27%   |
| Ricoh                                  | 4         | 0.72%   |
| Lenovo                                 | 4         | 0.72%   |
| Z-Star Microelectronics                | 3         | 0.54%   |
| Importek                               | 3         | 0.54%   |
| SN0002                                 | 2         | 0.36%   |
| Nebraska Furniture Mart                | 2         | 0.36%   |
| Google                                 | 2         | 0.36%   |
| GEMBIRD                                | 2         | 0.36%   |
| Y Media                                | 1         | 0.18%   |
| Unknown                                | 1         | 0.18%   |
| U0AS01A-0                              | 1         | 0.18%   |
| SunplusIT                              | 1         | 0.18%   |
| Sonix Technology                       | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |
| Mitsumi                                | 1         | 0.18%   |
| Microsoft                              | 1         | 0.18%   |
| MacroSilicon                           | 1         | 0.18%   |
| icSpring                               | 1         | 0.18%   |
| Goodong Industry                       | 1         | 0.18%   |
| Genesys Logic                          | 1         | 0.18%   |
| Cypress Semiconductor                  | 1         | 0.18%   |
| Cubeternet                             | 1         | 0.18%   |
| ARC International                      | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 47        | 8.42%   |
| IMC Networks Integrated Camera                                             | 36        | 6.45%   |
| Acer Integrated Camera                                                     | 25        | 4.48%   |
| Microdia Integrated_Webcam_HD                                              | 24        | 4.3%    |
| IMC Networks ov9734_azurewave_camera                                       | 20        | 3.58%   |
| Syntek Integrated Camera                                                   | 13        | 2.33%   |
| Chicony HD Webcam                                                          | 13        | 2.33%   |
| Realtek Integrated_Webcam_HD                                               | 12        | 2.15%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 12        | 2.15%   |
| Sunplus Integrated_Webcam_HD                                               | 11        | 1.97%   |
| Quanta hm1091_techfront                                                    | 7         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 1.25%   |
| IMC Networks HD Camera                                                     | 7         | 1.25%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 7         | 1.25%   |
| Apple iPhone5/5C/5S/6                                                      | 7         | 1.25%   |
| Sunplus HD WebCam                                                          | 6         | 1.08%   |
| Realtek Integrated Webcam                                                  | 6         | 1.08%   |
| Quanta HP HD Camera                                                        | 6         | 1.08%   |
| Quanta HD User Facing                                                      | 6         | 1.08%   |
| Luxvisions Innotech Limited Integrated Camera                              | 6         | 1.08%   |
| Acer BisonCam, NB Pro                                                      | 6         | 1.08%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 5         | 0.9%    |
| Silicon Motion 300k Pixel Camera                                           | 5         | 0.9%    |
| Realtek HP Wide Vision HD Camera                                           | 5         | 0.9%    |
| Lite-On Integrated Camera                                                  | 5         | 0.9%    |
| Acer SunplusIT Integrated Camera                                           | 5         | 0.9%    |
| Acer Lenovo EasyCamera                                                     | 5         | 0.9%    |
| Syntek Lenovo EasyCamera                                                   | 4         | 0.72%   |
| Lite-On HP HD Camera                                                       | 4         | 0.72%   |
| IMC Networks Lenovo EasyCamera                                             | 4         | 0.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.72%   |
| Chicony Integrated Camera (1280x720@30)                                    | 4         | 0.72%   |
| Chicony HP Wide Vision HD Camera                                           | 4         | 0.72%   |
| Chicony HP HD Camera                                                       | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 0.72%   |
| Suyin 1.3M HD WebCam                                                       | 3         | 0.54%   |
| Sunplus HP Wide Vision HD                                                  | 3         | 0.54%   |
| Realtek USB Camera                                                         | 3         | 0.54%   |
| Microdia Webcam Vitade AF                                                  | 3         | 0.54%   |
| Microdia USB2.0 Camera                                                     | 3         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 53        | 33.13%  |
| Synaptics                  | 41        | 25.63%  |
| Validity Sensors           | 40        | 25%     |
| Elan Microelectronics      | 12        | 7.5%    |
| Upek                       | 8         | 5%      |
| AuthenTec                  | 3         | 1.88%   |
| LighTuning Technology      | 2         | 1.25%   |
| STMicroelectronics         | 1         | 0.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 17.5%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 14.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 12.5%   |
| Elan ELAN:Fingerprint                                                      | 11        | 6.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 5%      |
| Unknown                                                                    | 8         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 4.38%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.5%    |
| Validity Sensors VFS491                                                    | 3         | 1.88%   |
| Synaptics WBDI Device                                                      | 3         | 1.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 1.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.25%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.63%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.63%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.63%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.63%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.63%   |
| AuthenTec AES2810                                                          | 1         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 70.59%  |
| Clay Logic  | 2         | 11.76%  |
| Alcor Micro | 2         | 11.76%  |
| Upek        | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| Clay Logic CanoKey Pigeon                                                    | 2         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 11.76%  |
| Broadcom 58200                                                               | 2         | 11.76%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 605       | 59.43%  |
| 1     | 322       | 31.63%  |
| 2     | 60        | 5.89%   |
| 3     | 12        | 1.18%   |
| 4     | 11        | 1.08%   |
| 5     | 5         | 0.49%   |
| 8     | 2         | 0.2%    |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 157       | 29.79%  |
| Graphics card            | 128       | 24.29%  |
| Net/wireless             | 58        | 11.01%  |
| Communication controller | 41        | 7.78%   |
| Multimedia controller    | 30        | 5.69%   |
| Unassigned class         | 23        | 4.36%   |
| Sound                    | 22        | 4.17%   |
| Bluetooth                | 18        | 3.42%   |
| Chipcard                 | 15        | 2.85%   |
| Camera                   | 11        | 2.09%   |
| Network                  | 6         | 1.14%   |
| Net/ethernet             | 6         | 1.14%   |
| Storage/raid             | 3         | 0.57%   |
| Storage                  | 3         | 0.57%   |
| Card reader              | 3         | 0.57%   |
| Storage/ata              | 1         | 0.19%   |
| Modem                    | 1         | 0.19%   |
| Dvb card                 | 1         | 0.19%   |

