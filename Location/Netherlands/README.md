Linux in Netherlands - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Netherlands.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Netherlands/Desktop/README.md) and [notebooks](/Location/Netherlands/Notebook/README.md).

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

Total: 5283

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [0043164762](https://linux-hardware.org/?probe=0043164762) | Feb 28, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [3b70c27ca4](https://linux-hardware.org/?probe=3b70c27ca4) | Feb 28, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| Sony          | VGN-FW11M                   | Notebook    | [06b355e1de](https://linux-hardware.org/?probe=06b355e1de) | Feb 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [6bf890e60c](https://linux-hardware.org/?probe=6bf890e60c) | Feb 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [979b4559fe](https://linux-hardware.org/?probe=979b4559fe) | Feb 27, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [323a03f1c6](https://linux-hardware.org/?probe=323a03f1c6) | Feb 27, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c16b58c7ce](https://linux-hardware.org/?probe=c16b58c7ce) | Feb 26, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [9d8016f80e](https://linux-hardware.org/?probe=9d8016f80e) | Feb 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8184285a7d](https://linux-hardware.org/?probe=8184285a7d) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3aae5788cf](https://linux-hardware.org/?probe=3aae5788cf) | Feb 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [8f46d24897](https://linux-hardware.org/?probe=8f46d24897) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2978ec71b8](https://linux-hardware.org/?probe=2978ec71b8) | Feb 25, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [ca2ef50547](https://linux-hardware.org/?probe=ca2ef50547) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3899b2f13e](https://linux-hardware.org/?probe=3899b2f13e) | Feb 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [926fcff980](https://linux-hardware.org/?probe=926fcff980) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bbce041f5](https://linux-hardware.org/?probe=2bbce041f5) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [f91140d700](https://linux-hardware.org/?probe=f91140d700) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [66b104fc61](https://linux-hardware.org/?probe=66b104fc61) | Feb 24, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [7233b168b4](https://linux-hardware.org/?probe=7233b168b4) | Feb 24, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [9398719812](https://linux-hardware.org/?probe=9398719812) | Feb 24, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [2cb9f58eae](https://linux-hardware.org/?probe=2cb9f58eae) | Feb 24, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fa08c93ecd](https://linux-hardware.org/?probe=fa08c93ecd) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a3d9851893](https://linux-hardware.org/?probe=a3d9851893) | Feb 23, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [f348e93361](https://linux-hardware.org/?probe=f348e93361) | Feb 23, 2023 |
| Dell          | 0YC03K A03                  | Desktop     | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [1cca7fe830](https://linux-hardware.org/?probe=1cca7fe830) | Feb 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [de79cbb975](https://linux-hardware.org/?probe=de79cbb975) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [5e92cdeee7](https://linux-hardware.org/?probe=5e92cdeee7) | Feb 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cd66af8994](https://linux-hardware.org/?probe=cd66af8994) | Feb 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1ecf49cbaf](https://linux-hardware.org/?probe=1ecf49cbaf) | Feb 21, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e1c694b371](https://linux-hardware.org/?probe=e1c694b371) | Feb 20, 2023 |
| Dell          | Latitude 7300               | Notebook    | [65690f7efc](https://linux-hardware.org/?probe=65690f7efc) | Feb 20, 2023 |
| Dell          | Latitude E6320              | Notebook    | [0b5bcfefc5](https://linux-hardware.org/?probe=0b5bcfefc5) | Feb 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8ca2b786db](https://linux-hardware.org/?probe=8ca2b786db) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [db95126414](https://linux-hardware.org/?probe=db95126414) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c2e0245ec5](https://linux-hardware.org/?probe=c2e0245ec5) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [8110ff7717](https://linux-hardware.org/?probe=8110ff7717) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5857177f10](https://linux-hardware.org/?probe=5857177f10) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c4a1fe4a4f](https://linux-hardware.org/?probe=c4a1fe4a4f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3886d9287f](https://linux-hardware.org/?probe=3886d9287f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [1b401aa3cf](https://linux-hardware.org/?probe=1b401aa3cf) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c59694e05c](https://linux-hardware.org/?probe=c59694e05c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [c614caec4a](https://linux-hardware.org/?probe=c614caec4a) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c273319d9d](https://linux-hardware.org/?probe=c273319d9d) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [4fe16ec4fe](https://linux-hardware.org/?probe=4fe16ec4fe) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [3de841fd56](https://linux-hardware.org/?probe=3de841fd56) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [130fe12846](https://linux-hardware.org/?probe=130fe12846) | Feb 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7ca9bf386b](https://linux-hardware.org/?probe=7ca9bf386b) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ddc2c7ec7a](https://linux-hardware.org/?probe=ddc2c7ec7a) | Feb 16, 2023 |
| HP            | 3031h                       | Desktop     | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [38c3a4311b](https://linux-hardware.org/?probe=38c3a4311b) | Feb 16, 2023 |
| HP            | 870C                        | Desktop     | [76ae5c62cf](https://linux-hardware.org/?probe=76ae5c62cf) | Feb 15, 2023 |
| Medion        | MS-7616                     | Desktop     | [0655a4e58c](https://linux-hardware.org/?probe=0655a4e58c) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [3039ccd4b0](https://linux-hardware.org/?probe=3039ccd4b0) | Feb 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d2754bf08f](https://linux-hardware.org/?probe=d2754bf08f) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [0d16c9013f](https://linux-hardware.org/?probe=0d16c9013f) | Feb 14, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [dcfa5b1fc5](https://linux-hardware.org/?probe=dcfa5b1fc5) | Feb 13, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [3a4a4dedc3](https://linux-hardware.org/?probe=3a4a4dedc3) | Feb 13, 2023 |
| Dell          | Latitude E5570              | Notebook    | [16e090c63c](https://linux-hardware.org/?probe=16e090c63c) | Feb 13, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [7c1423b767](https://linux-hardware.org/?probe=7c1423b767) | Feb 13, 2023 |
| Acer          | Aspire M1930                | Desktop     | [3b78f6fb4e](https://linux-hardware.org/?probe=3b78f6fb4e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [ea169af948](https://linux-hardware.org/?probe=ea169af948) | Feb 13, 2023 |
| HP            | 843F                        | Desktop     | [3047a0ff5b](https://linux-hardware.org/?probe=3047a0ff5b) | Feb 13, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [672b71db3e](https://linux-hardware.org/?probe=672b71db3e) | Feb 12, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [5629f3ed8c](https://linux-hardware.org/?probe=5629f3ed8c) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [95875d4afc](https://linux-hardware.org/?probe=95875d4afc) | Feb 11, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [f5a8290d38](https://linux-hardware.org/?probe=f5a8290d38) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| Dell          | Latitude 3120               | Convertible | [3bf2bfe867](https://linux-hardware.org/?probe=3bf2bfe867) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | Notebook    | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [353bd3a5b2](https://linux-hardware.org/?probe=353bd3a5b2) | Feb 09, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [f3eb8a2592](https://linux-hardware.org/?probe=f3eb8a2592) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| Medion        | MS-7797                     | Desktop     | [3421cd9be4](https://linux-hardware.org/?probe=3421cd9be4) | Feb 09, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [0779ef912a](https://linux-hardware.org/?probe=0779ef912a) | Feb 08, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [7091e6ba95](https://linux-hardware.org/?probe=7091e6ba95) | Feb 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [2513ec83c8](https://linux-hardware.org/?probe=2513ec83c8) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [bb851866ac](https://linux-hardware.org/?probe=bb851866ac) | Feb 08, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [e92a6b0131](https://linux-hardware.org/?probe=e92a6b0131) | Feb 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [20d7058e4f](https://linux-hardware.org/?probe=20d7058e4f) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b376c55e80](https://linux-hardware.org/?probe=b376c55e80) | Feb 07, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [cdc1678cae](https://linux-hardware.org/?probe=cdc1678cae) | Feb 07, 2023 |
| Dell          | Latitude E6320              | Notebook    | [6d1fe4f041](https://linux-hardware.org/?probe=6d1fe4f041) | Feb 06, 2023 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [5d737e59ae](https://linux-hardware.org/?probe=5d737e59ae) | Feb 06, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2e581dc622](https://linux-hardware.org/?probe=2e581dc622) | Feb 06, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3b4320a91a](https://linux-hardware.org/?probe=3b4320a91a) | Feb 06, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [33639358ab](https://linux-hardware.org/?probe=33639358ab) | Feb 06, 2023 |
| Standard      | Unknown                     | Notebook    | [c983c471de](https://linux-hardware.org/?probe=c983c471de) | Feb 05, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [b6333de3ab](https://linux-hardware.org/?probe=b6333de3ab) | Feb 05, 2023 |
| MSI           | MS-7376                     | Desktop     | [5f62748624](https://linux-hardware.org/?probe=5f62748624) | Feb 04, 2023 |
| MSI           | MS-7376                     | Desktop     | [33fa767f72](https://linux-hardware.org/?probe=33fa767f72) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [04c5cc4aec](https://linux-hardware.org/?probe=04c5cc4aec) | Feb 04, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [82a573d8cd](https://linux-hardware.org/?probe=82a573d8cd) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8dee1d9415](https://linux-hardware.org/?probe=8dee1d9415) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [1e38d08821](https://linux-hardware.org/?probe=1e38d08821) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b9e4e36496](https://linux-hardware.org/?probe=b9e4e36496) | Feb 03, 2023 |
| Gigabyte      | EP45-DS3                    | Desktop     | [ac1f8787af](https://linux-hardware.org/?probe=ac1f8787af) | Feb 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [2a25e1c4d6](https://linux-hardware.org/?probe=2a25e1c4d6) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [e68a009e8f](https://linux-hardware.org/?probe=e68a009e8f) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [66b96d9a0f](https://linux-hardware.org/?probe=66b96d9a0f) | Jan 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [798466ab86](https://linux-hardware.org/?probe=798466ab86) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4dbe55873b](https://linux-hardware.org/?probe=4dbe55873b) | Jan 31, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [30a093116e](https://linux-hardware.org/?probe=30a093116e) | Jan 30, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [2469884587](https://linux-hardware.org/?probe=2469884587) | Jan 30, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [bdb3c91476](https://linux-hardware.org/?probe=bdb3c91476) | Jan 29, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [debdb8208f](https://linux-hardware.org/?probe=debdb8208f) | Jan 29, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [d17dc00a8a](https://linux-hardware.org/?probe=d17dc00a8a) | Jan 29, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [8bee986aca](https://linux-hardware.org/?probe=8bee986aca) | Jan 28, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [fb0dcf8d7e](https://linux-hardware.org/?probe=fb0dcf8d7e) | Jan 28, 2023 |
| HP            | 17E2                        | Mini pc     | [41fdb27963](https://linux-hardware.org/?probe=41fdb27963) | Jan 28, 2023 |
| HP            | 0A08h                       | Desktop     | [f9b0168de1](https://linux-hardware.org/?probe=f9b0168de1) | Jan 28, 2023 |
| Dell          | 0599V5 A12                  | Server      | [14f503ae4a](https://linux-hardware.org/?probe=14f503ae4a) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [a50b0e3645](https://linux-hardware.org/?probe=a50b0e3645) | Jan 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [97d1ab1b7d](https://linux-hardware.org/?probe=97d1ab1b7d) | Jan 28, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [86e3285b31](https://linux-hardware.org/?probe=86e3285b31) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [b9793eca79](https://linux-hardware.org/?probe=b9793eca79) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [ee769c62bf](https://linux-hardware.org/?probe=ee769c62bf) | Jan 27, 2023 |
| HP            | 8055                        | Desktop     | [81fa44d8fa](https://linux-hardware.org/?probe=81fa44d8fa) | Jan 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b1079b0bf](https://linux-hardware.org/?probe=1b1079b0bf) | Jan 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c0468fe8fd](https://linux-hardware.org/?probe=c0468fe8fd) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [ab38ecfb97](https://linux-hardware.org/?probe=ab38ecfb97) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [cb8c4c9711](https://linux-hardware.org/?probe=cb8c4c9711) | Jan 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [076783b777](https://linux-hardware.org/?probe=076783b777) | Jan 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [b5cb34ea4d](https://linux-hardware.org/?probe=b5cb34ea4d) | Jan 26, 2023 |
| Toshiba       | Satellite C870-12F          | Notebook    | [fc9a6d3a7e](https://linux-hardware.org/?probe=fc9a6d3a7e) | Jan 25, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [4efa4db490](https://linux-hardware.org/?probe=4efa4db490) | Jan 25, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [dd2f21ab84](https://linux-hardware.org/?probe=dd2f21ab84) | Jan 25, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9b7c80b059](https://linux-hardware.org/?probe=9b7c80b059) | Jan 25, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [dad68fd07f](https://linux-hardware.org/?probe=dad68fd07f) | Jan 24, 2023 |
| MSI           | CX700ND/CX70 0NF/CX70 0N... | Notebook    | [b61b0f981e](https://linux-hardware.org/?probe=b61b0f981e) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47ff2a2e42](https://linux-hardware.org/?probe=47ff2a2e42) | Jan 24, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a3672f1d47](https://linux-hardware.org/?probe=a3672f1d47) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [3194fb8316](https://linux-hardware.org/?probe=3194fb8316) | Jan 24, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8e124bc501](https://linux-hardware.org/?probe=8e124bc501) | Jan 24, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [75362fb07d](https://linux-hardware.org/?probe=75362fb07d) | Jan 24, 2023 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [7630683952](https://linux-hardware.org/?probe=7630683952) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [8c427938e2](https://linux-hardware.org/?probe=8c427938e2) | Jan 24, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ca72b0d88](https://linux-hardware.org/?probe=5ca72b0d88) | Jan 24, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [5e4253b22d](https://linux-hardware.org/?probe=5e4253b22d) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b4b7ebe3f9](https://linux-hardware.org/?probe=b4b7ebe3f9) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [6e7a21c6d5](https://linux-hardware.org/?probe=6e7a21c6d5) | Jan 23, 2023 |
| Lenovo        | Erazer Z500 20226           | Notebook    | [7d6077c27c](https://linux-hardware.org/?probe=7d6077c27c) | Jan 23, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [54313c1c76](https://linux-hardware.org/?probe=54313c1c76) | Jan 23, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [459ab8ae3d](https://linux-hardware.org/?probe=459ab8ae3d) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0a3f1269f7](https://linux-hardware.org/?probe=0a3f1269f7) | Jan 23, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [b2792832c2](https://linux-hardware.org/?probe=b2792832c2) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [9beaa4240c](https://linux-hardware.org/?probe=9beaa4240c) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [733770beaf](https://linux-hardware.org/?probe=733770beaf) | Jan 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a3541758f7](https://linux-hardware.org/?probe=a3541758f7) | Jan 22, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [325f9e8310](https://linux-hardware.org/?probe=325f9e8310) | Jan 21, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [eeea0542b8](https://linux-hardware.org/?probe=eeea0542b8) | Jan 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5d606f2c60](https://linux-hardware.org/?probe=5d606f2c60) | Jan 21, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490 20N3S0E000    | Notebook    | [d324a863a5](https://linux-hardware.org/?probe=d324a863a5) | Jan 20, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [1a61029965](https://linux-hardware.org/?probe=1a61029965) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | Notebook                    | Notebook    | [63f0c0b90c](https://linux-hardware.org/?probe=63f0c0b90c) | Jan 19, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [da0d1f442a](https://linux-hardware.org/?probe=da0d1f442a) | Jan 19, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [3591fb1d6c](https://linux-hardware.org/?probe=3591fb1d6c) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [798a545fa8](https://linux-hardware.org/?probe=798a545fa8) | Jan 19, 2023 |
| Pegatron      | EVANS                       | Desktop     | [411db3ea66](https://linux-hardware.org/?probe=411db3ea66) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f0ce1e8b3f](https://linux-hardware.org/?probe=f0ce1e8b3f) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [62d01a5b26](https://linux-hardware.org/?probe=62d01a5b26) | Jan 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [09e31ee1c8](https://linux-hardware.org/?probe=09e31ee1c8) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f9325236bb](https://linux-hardware.org/?probe=f9325236bb) | Jan 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [fafa35ef88](https://linux-hardware.org/?probe=fafa35ef88) | Jan 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [2cc8923eb1](https://linux-hardware.org/?probe=2cc8923eb1) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [856324369f](https://linux-hardware.org/?probe=856324369f) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4da81f73f5](https://linux-hardware.org/?probe=4da81f73f5) | Jan 16, 2023 |
| Google        | Banon                       | Notebook    | [6bb3ed04f9](https://linux-hardware.org/?probe=6bb3ed04f9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Acer          | Aspire 5680                 | Notebook    | [dc5f6d7ac6](https://linux-hardware.org/?probe=dc5f6d7ac6) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [01c0e96288](https://linux-hardware.org/?probe=01c0e96288) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [895f75daf7](https://linux-hardware.org/?probe=895f75daf7) | Jan 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [57cd4eaca3](https://linux-hardware.org/?probe=57cd4eaca3) | Jan 15, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [bdfc087b4d](https://linux-hardware.org/?probe=bdfc087b4d) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | Latitude E5410              | Notebook    | [909ca0fd93](https://linux-hardware.org/?probe=909ca0fd93) | Jan 14, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [116b26047d](https://linux-hardware.org/?probe=116b26047d) | Jan 14, 2023 |
| Supermicro    | A1SA2-2750F                 | Server      | [e134d7a317](https://linux-hardware.org/?probe=e134d7a317) | Jan 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [c4cfa1aa47](https://linux-hardware.org/?probe=c4cfa1aa47) | Jan 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [67168cc8a9](https://linux-hardware.org/?probe=67168cc8a9) | Jan 13, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [85d6a0b721](https://linux-hardware.org/?probe=85d6a0b721) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [178c6f90fa](https://linux-hardware.org/?probe=178c6f90fa) | Jan 13, 2023 |
| Dell          | Latitude 3350               | Notebook    | [065c4a4a95](https://linux-hardware.org/?probe=065c4a4a95) | Jan 12, 2023 |
| Lenovo        | G770 1037                   | Notebook    | [da21020be1](https://linux-hardware.org/?probe=da21020be1) | Jan 12, 2023 |
| HP            | 8648                        | Desktop     | [df76c90c20](https://linux-hardware.org/?probe=df76c90c20) | Jan 12, 2023 |
| Notebook      | NS50MU                      | Notebook    | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| Standard      | Unknown                     | Notebook    | [b6f4b12847](https://linux-hardware.org/?probe=b6f4b12847) | Jan 12, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [77c659307a](https://linux-hardware.org/?probe=77c659307a) | Jan 11, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [0f8c99e8d7](https://linux-hardware.org/?probe=0f8c99e8d7) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [3696db52a7](https://linux-hardware.org/?probe=3696db52a7) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [379a5aa220](https://linux-hardware.org/?probe=379a5aa220) | Jan 11, 2023 |
| Sony          | VPCEB3L9E                   | Notebook    | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7588fecfe8](https://linux-hardware.org/?probe=7588fecfe8) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [69b3403f94](https://linux-hardware.org/?probe=69b3403f94) | Jan 10, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [27b63fd8b1](https://linux-hardware.org/?probe=27b63fd8b1) | Jan 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [16a4dc82f5](https://linux-hardware.org/?probe=16a4dc82f5) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [be24cf68d4](https://linux-hardware.org/?probe=be24cf68d4) | Jan 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1375baed6d](https://linux-hardware.org/?probe=1375baed6d) | Jan 09, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [4bbe8325bd](https://linux-hardware.org/?probe=4bbe8325bd) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5663965a51](https://linux-hardware.org/?probe=5663965a51) | Jan 09, 2023 |
| Gigabyte      | J1900N-D2H                  | Desktop     | [62be43a4a3](https://linux-hardware.org/?probe=62be43a4a3) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [1f97553f11](https://linux-hardware.org/?probe=1f97553f11) | Jan 08, 2023 |
| Dell          | 0WG855                      | Desktop     | [0a2e7733bf](https://linux-hardware.org/?probe=0a2e7733bf) | Jan 08, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39a58c2e6](https://linux-hardware.org/?probe=b39a58c2e6) | Jan 08, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [0d0c035342](https://linux-hardware.org/?probe=0d0c035342) | Jan 08, 2023 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [8ca4d7b38b](https://linux-hardware.org/?probe=8ca4d7b38b) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [782467ee8c](https://linux-hardware.org/?probe=782467ee8c) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e3c76a5b82](https://linux-hardware.org/?probe=e3c76a5b82) | Jan 05, 2023 |
| HP            | 8648                        | Desktop     | [2345926399](https://linux-hardware.org/?probe=2345926399) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| HP            | Pavilion 17                 | Notebook    | [fe325358d6](https://linux-hardware.org/?probe=fe325358d6) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4335d83dfc](https://linux-hardware.org/?probe=4335d83dfc) | Jan 04, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [0341a89f2f](https://linux-hardware.org/?probe=0341a89f2f) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f148d690a](https://linux-hardware.org/?probe=2f148d690a) | Jan 03, 2023 |
| ASUSTek       | F1A55-V                     | Desktop     | [fec2a24044](https://linux-hardware.org/?probe=fec2a24044) | Jan 03, 2023 |
| Acer          | Aspire E5-774               | Notebook    | [96c68886cf](https://linux-hardware.org/?probe=96c68886cf) | Jan 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [a316608c78](https://linux-hardware.org/?probe=a316608c78) | Jan 03, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| HP            | 3048h                       | Desktop     | [dabc36c98f](https://linux-hardware.org/?probe=dabc36c98f) | Jan 02, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [e93bf27a59](https://linux-hardware.org/?probe=e93bf27a59) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | Notebook    | [e8b6dd6f1f](https://linux-hardware.org/?probe=e8b6dd6f1f) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [d1f655b9b1](https://linux-hardware.org/?probe=d1f655b9b1) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [c87d61d0cd](https://linux-hardware.org/?probe=c87d61d0cd) | Dec 31, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bbf52af119](https://linux-hardware.org/?probe=bbf52af119) | Dec 31, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [fc108fb0d8](https://linux-hardware.org/?probe=fc108fb0d8) | Dec 31, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [9e794046d8](https://linux-hardware.org/?probe=9e794046d8) | Dec 30, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [c14cfe5386](https://linux-hardware.org/?probe=c14cfe5386) | Dec 29, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [9f431b484a](https://linux-hardware.org/?probe=9f431b484a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Alienware     | x17 R2                      | Notebook    | [5a7ea2683a](https://linux-hardware.org/?probe=5a7ea2683a) | Dec 28, 2022 |
| Gigabyte      | GB-BRR3H-4300               | Desktop     | [241d631981](https://linux-hardware.org/?probe=241d631981) | Dec 28, 2022 |
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| LG Electro... | 17Z90Q-G.AA79G              | Notebook    | [59d7266746](https://linux-hardware.org/?probe=59d7266746) | Dec 26, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [43c2d92e5f](https://linux-hardware.org/?probe=43c2d92e5f) | Dec 26, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5d95c28ac6](https://linux-hardware.org/?probe=5d95c28ac6) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a98ca87f6a](https://linux-hardware.org/?probe=a98ca87f6a) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [00af244895](https://linux-hardware.org/?probe=00af244895) | Dec 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5047d29893](https://linux-hardware.org/?probe=5047d29893) | Dec 24, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [82cc0b362d](https://linux-hardware.org/?probe=82cc0b362d) | Dec 23, 2022 |
| Intel         | X99                         | Desktop     | [191fefa053](https://linux-hardware.org/?probe=191fefa053) | Dec 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [313bf04928](https://linux-hardware.org/?probe=313bf04928) | Dec 22, 2022 |
| Lenovo        | IdeaPad 3 14IAU7 82RJ       | Notebook    | [b5c5aba33a](https://linux-hardware.org/?probe=b5c5aba33a) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | Notebook    | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [9b188c358e](https://linux-hardware.org/?probe=9b188c358e) | Dec 21, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6a6ba7eba1](https://linux-hardware.org/?probe=6a6ba7eba1) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Dell          | Latitude 5521               | Notebook    | [6fcbfd9271](https://linux-hardware.org/?probe=6fcbfd9271) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [4535cf0f5a](https://linux-hardware.org/?probe=4535cf0f5a) | Dec 20, 2022 |
| HP            | 3048h                       | Desktop     | [1d795fdd33](https://linux-hardware.org/?probe=1d795fdd33) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [8d876c21b0](https://linux-hardware.org/?probe=8d876c21b0) | Dec 18, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [71575f3d8c](https://linux-hardware.org/?probe=71575f3d8c) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [3b242628e4](https://linux-hardware.org/?probe=3b242628e4) | Dec 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06f90011b2](https://linux-hardware.org/?probe=06f90011b2) | Dec 18, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [64f5eb2f4b](https://linux-hardware.org/?probe=64f5eb2f4b) | Dec 17, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5681babfa5](https://linux-hardware.org/?probe=5681babfa5) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| Acer          | Aspire XC-1660 V:1.1        | Desktop     | [88aa1f841a](https://linux-hardware.org/?probe=88aa1f841a) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3fd939cef5](https://linux-hardware.org/?probe=3fd939cef5) | Dec 17, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [182e467ce6](https://linux-hardware.org/?probe=182e467ce6) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | Latitude 3120               | Notebook    | [e886df2722](https://linux-hardware.org/?probe=e886df2722) | Dec 16, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [cb963df304](https://linux-hardware.org/?probe=cb963df304) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bc8782be9a](https://linux-hardware.org/?probe=bc8782be9a) | Dec 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d320b71c77](https://linux-hardware.org/?probe=d320b71c77) | Dec 15, 2022 |
| HP            | 3048h                       | Desktop     | [63f57e3458](https://linux-hardware.org/?probe=63f57e3458) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b90d5cfed0](https://linux-hardware.org/?probe=b90d5cfed0) | Dec 14, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [de26ffa293](https://linux-hardware.org/?probe=de26ffa293) | Dec 14, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd65da9c9b](https://linux-hardware.org/?probe=dd65da9c9b) | Dec 14, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Gigabyte      | P35-DS4                     | Desktop     | [3f787740f8](https://linux-hardware.org/?probe=3f787740f8) | Dec 12, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [ee22896cd2](https://linux-hardware.org/?probe=ee22896cd2) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| HP            | 339A                        | Desktop     | [63c184fafd](https://linux-hardware.org/?probe=63c184fafd) | Dec 12, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f1aa6058e3](https://linux-hardware.org/?probe=f1aa6058e3) | Dec 12, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [56adac1fcb](https://linux-hardware.org/?probe=56adac1fcb) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2c52e941ea](https://linux-hardware.org/?probe=2c52e941ea) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| HP            | 3048h                       | Desktop     | [c2fd939c1f](https://linux-hardware.org/?probe=c2fd939c1f) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [25d5b5623b](https://linux-hardware.org/?probe=25d5b5623b) | Dec 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [869e2a9671](https://linux-hardware.org/?probe=869e2a9671) | Dec 09, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [503b61f120](https://linux-hardware.org/?probe=503b61f120) | Dec 09, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [e5ba0c8749](https://linux-hardware.org/?probe=e5ba0c8749) | Dec 09, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [1a4bdc4874](https://linux-hardware.org/?probe=1a4bdc4874) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [27dc9420ed](https://linux-hardware.org/?probe=27dc9420ed) | Dec 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9b7c1953a6](https://linux-hardware.org/?probe=9b7c1953a6) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Lenovo        | ThinkPad T510 4349AF5       | Notebook    | [a7d8d66fb7](https://linux-hardware.org/?probe=a7d8d66fb7) | Dec 07, 2022 |
| Dell          | XPS 9320                    | Notebook    | [34c3b0b6a0](https://linux-hardware.org/?probe=34c3b0b6a0) | Dec 06, 2022 |
| Medion        | E4251                       | Notebook    | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [da82fb083d](https://linux-hardware.org/?probe=da82fb083d) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c22a748043](https://linux-hardware.org/?probe=c22a748043) | Dec 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [86e9e1e21e](https://linux-hardware.org/?probe=86e9e1e21e) | Dec 05, 2022 |
| Acer          | Aspire V3-772               | Notebook    | [942312fe9e](https://linux-hardware.org/?probe=942312fe9e) | Dec 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [344b0c3082](https://linux-hardware.org/?probe=344b0c3082) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | Desktop     | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Intel         | Unknown                     | Desktop     | [d00187a52a](https://linux-hardware.org/?probe=d00187a52a) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | Notebook    | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c300b0a438](https://linux-hardware.org/?probe=c300b0a438) | Dec 03, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [b0437249b0](https://linux-hardware.org/?probe=b0437249b0) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [5864876eff](https://linux-hardware.org/?probe=5864876eff) | Dec 02, 2022 |
| Acer          | Iconia W4-820               | Notebook    | [cf25eeba85](https://linux-hardware.org/?probe=cf25eeba85) | Dec 01, 2022 |
| MSI           | GL62M 7RE                   | Notebook    | [5fcb394edb](https://linux-hardware.org/?probe=5fcb394edb) | Dec 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [df74bf8e13](https://linux-hardware.org/?probe=df74bf8e13) | Dec 01, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e8d75cbeed](https://linux-hardware.org/?probe=e8d75cbeed) | Dec 01, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b461d54421](https://linux-hardware.org/?probe=b461d54421) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [29c5e0f7b1](https://linux-hardware.org/?probe=29c5e0f7b1) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | Notebook    | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Gigabyte      | GB-BRR7H-4700               | Desktop     | [8398d00a16](https://linux-hardware.org/?probe=8398d00a16) | Nov 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d7025eb475](https://linux-hardware.org/?probe=d7025eb475) | Nov 30, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [729bb4ef87](https://linux-hardware.org/?probe=729bb4ef87) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | Desktop     | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [dae405ee81](https://linux-hardware.org/?probe=dae405ee81) | Nov 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9216162e85](https://linux-hardware.org/?probe=9216162e85) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [39e771bd92](https://linux-hardware.org/?probe=39e771bd92) | Nov 28, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | Notebook    | [43fa54b5bc](https://linux-hardware.org/?probe=43fa54b5bc) | Nov 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [219a616346](https://linux-hardware.org/?probe=219a616346) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [bcbdb4bf67](https://linux-hardware.org/?probe=bcbdb4bf67) | Nov 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [f77e444066](https://linux-hardware.org/?probe=f77e444066) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| HP            | ProBook 5330m               | Notebook    | [3763f505a0](https://linux-hardware.org/?probe=3763f505a0) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [bda395e731](https://linux-hardware.org/?probe=bda395e731) | Nov 26, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [0138561b29](https://linux-hardware.org/?probe=0138561b29) | Nov 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| ASUSTek       | A6R                         | Notebook    | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [8de1db7f12](https://linux-hardware.org/?probe=8de1db7f12) | Nov 25, 2022 |
| Dell          | Latitude 3120               | Convertible | [bb40e36093](https://linux-hardware.org/?probe=bb40e36093) | Nov 24, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [e2a8d64086](https://linux-hardware.org/?probe=e2a8d64086) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [4adc436e33](https://linux-hardware.org/?probe=4adc436e33) | Nov 23, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [84a0005ad3](https://linux-hardware.org/?probe=84a0005ad3) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| HP            | 3397                        | Desktop     | [eb8968148c](https://linux-hardware.org/?probe=eb8968148c) | Nov 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5d3424245f](https://linux-hardware.org/?probe=5d3424245f) | Nov 22, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [72406b1647](https://linux-hardware.org/?probe=72406b1647) | Nov 21, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [635e9fe863](https://linux-hardware.org/?probe=635e9fe863) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [e80e97466d](https://linux-hardware.org/?probe=e80e97466d) | Nov 21, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [12799c9216](https://linux-hardware.org/?probe=12799c9216) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| HP            | Unknown                     | Notebook    | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [52c86bac3f](https://linux-hardware.org/?probe=52c86bac3f) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [9c9af5a79e](https://linux-hardware.org/?probe=9c9af5a79e) | Nov 20, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [acb3ae70b9](https://linux-hardware.org/?probe=acb3ae70b9) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [1c931e307d](https://linux-hardware.org/?probe=1c931e307d) | Nov 20, 2022 |
| Unknown       | X99H                        | Desktop     | [06c69ccbcb](https://linux-hardware.org/?probe=06c69ccbcb) | Nov 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [3b5c35b319](https://linux-hardware.org/?probe=3b5c35b319) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [3e2911ed20](https://linux-hardware.org/?probe=3e2911ed20) | Nov 19, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3b08108f59](https://linux-hardware.org/?probe=3b08108f59) | Nov 19, 2022 |
| Intel         | X99                         | Desktop     | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| HP            | Notebook                    | Notebook    | [ded915d6cd](https://linux-hardware.org/?probe=ded915d6cd) | Nov 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Lenovo        | ThinkPad L560 20F2S2UR02    | Notebook    | [5170b27e5c](https://linux-hardware.org/?probe=5170b27e5c) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [62586ed7f9](https://linux-hardware.org/?probe=62586ed7f9) | Nov 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [d5a16ba775](https://linux-hardware.org/?probe=d5a16ba775) | Nov 16, 2022 |
| HP            | Pavilion dv9500             | Notebook    | [65a473401c](https://linux-hardware.org/?probe=65a473401c) | Nov 16, 2022 |
| Acer          | Aspire X3470                | Desktop     | [ccaec6d2cb](https://linux-hardware.org/?probe=ccaec6d2cb) | Nov 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [4a80ba0608](https://linux-hardware.org/?probe=4a80ba0608) | Nov 15, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [d2cf28fbb9](https://linux-hardware.org/?probe=d2cf28fbb9) | Nov 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e9182b2177](https://linux-hardware.org/?probe=e9182b2177) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [21a6415538](https://linux-hardware.org/?probe=21a6415538) | Nov 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [3ce2f9981f](https://linux-hardware.org/?probe=3ce2f9981f) | Nov 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3020a4edfc](https://linux-hardware.org/?probe=3020a4edfc) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [db1488b844](https://linux-hardware.org/?probe=db1488b844) | Nov 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [54afa1ee72](https://linux-hardware.org/?probe=54afa1ee72) | Nov 15, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [35f0fc8a5a](https://linux-hardware.org/?probe=35f0fc8a5a) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bcce834785](https://linux-hardware.org/?probe=bcce834785) | Nov 14, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [26fad3df24](https://linux-hardware.org/?probe=26fad3df24) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [85c469c069](https://linux-hardware.org/?probe=85c469c069) | Nov 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [dc86aa7d1e](https://linux-hardware.org/?probe=dc86aa7d1e) | Nov 13, 2022 |
| Acer          | Predator G3-710             | Desktop     | [4be3a9e016](https://linux-hardware.org/?probe=4be3a9e016) | Nov 13, 2022 |
| Dell          | Latitude 3380               | Notebook    | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b4f06e5e2f](https://linux-hardware.org/?probe=b4f06e5e2f) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [c852376664](https://linux-hardware.org/?probe=c852376664) | Nov 12, 2022 |
| HP            | Compaq 6820s                | Notebook    | [dee9dbd56f](https://linux-hardware.org/?probe=dee9dbd56f) | Nov 12, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [7e2577bf51](https://linux-hardware.org/?probe=7e2577bf51) | Nov 10, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [70d68c6ca1](https://linux-hardware.org/?probe=70d68c6ca1) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | Notebook    | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [89aa240b37](https://linux-hardware.org/?probe=89aa240b37) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [e7de2507a0](https://linux-hardware.org/?probe=e7de2507a0) | Nov 09, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8383f208a6](https://linux-hardware.org/?probe=8383f208a6) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| MSI           | MS-1688                     | Notebook    | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| Dell          | Precision 5550              | Notebook    | [16b375ce77](https://linux-hardware.org/?probe=16b375ce77) | Nov 08, 2022 |
| Dell          | Precision 5550              | Notebook    | [1499c28fe9](https://linux-hardware.org/?probe=1499c28fe9) | Nov 08, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [d29c069985](https://linux-hardware.org/?probe=d29c069985) | Nov 08, 2022 |
| Acer          | SW5-017                     | Notebook    | [d4ff3ee29e](https://linux-hardware.org/?probe=d4ff3ee29e) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [c383da71e1](https://linux-hardware.org/?probe=c383da71e1) | Nov 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| ASUSTek       | K56CA                       | Notebook    | [032fa97b2a](https://linux-hardware.org/?probe=032fa97b2a) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | Notebook    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [afeb473322](https://linux-hardware.org/?probe=afeb473322) | Nov 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2ff0e6e61e](https://linux-hardware.org/?probe=2ff0e6e61e) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [11d229ea2c](https://linux-hardware.org/?probe=11d229ea2c) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| HP            | 3646h                       | Desktop     | [e49a380102](https://linux-hardware.org/?probe=e49a380102) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [d1b0eff99b](https://linux-hardware.org/?probe=d1b0eff99b) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [020d8fd7e0](https://linux-hardware.org/?probe=020d8fd7e0) | Nov 03, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ece2f7351](https://linux-hardware.org/?probe=2ece2f7351) | Nov 02, 2022 |
| HP            | 1589                        | Desktop     | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | ProBook 4530s               | Notebook    | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| HP            | 3646h                       | Desktop     | [f88c9632b4](https://linux-hardware.org/?probe=f88c9632b4) | Nov 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [678ca55a4c](https://linux-hardware.org/?probe=678ca55a4c) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [3cb8d29f84](https://linux-hardware.org/?probe=3cb8d29f84) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [21aa0f31b3](https://linux-hardware.org/?probe=21aa0f31b3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [c54736f079](https://linux-hardware.org/?probe=c54736f079) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Lenovo        | Legion Y740-17ICHg 81HH     | Notebook    | [ea1c9e069e](https://linux-hardware.org/?probe=ea1c9e069e) | Oct 29, 2022 |
| Medion        | X682X                       | Notebook    | [f05dd25a08](https://linux-hardware.org/?probe=f05dd25a08) | Oct 29, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [856d32288b](https://linux-hardware.org/?probe=856d32288b) | Oct 29, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a0714fbb29](https://linux-hardware.org/?probe=a0714fbb29) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [1b93a2f7df](https://linux-hardware.org/?probe=1b93a2f7df) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [9a01d62b1e](https://linux-hardware.org/?probe=9a01d62b1e) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8e25520b70](https://linux-hardware.org/?probe=8e25520b70) | Oct 27, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [34d97b7ea2](https://linux-hardware.org/?probe=34d97b7ea2) | Oct 26, 2022 |
| Dell          | Inspiron 7773               | Notebook    | [c2cff54e7c](https://linux-hardware.org/?probe=c2cff54e7c) | Oct 26, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6cb48a4d86](https://linux-hardware.org/?probe=6cb48a4d86) | Oct 25, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [0cb3fb3efc](https://linux-hardware.org/?probe=0cb3fb3efc) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [28c38a498d](https://linux-hardware.org/?probe=28c38a498d) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d761710495](https://linux-hardware.org/?probe=d761710495) | Oct 25, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| HP            | 1589                        | Desktop     | [0be048ec45](https://linux-hardware.org/?probe=0be048ec45) | Oct 24, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [2c1e50d1a2](https://linux-hardware.org/?probe=2c1e50d1a2) | Oct 22, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [0fd183c6a8](https://linux-hardware.org/?probe=0fd183c6a8) | Oct 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2b377dce0a](https://linux-hardware.org/?probe=2b377dce0a) | Oct 21, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [b864fd7ffa](https://linux-hardware.org/?probe=b864fd7ffa) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | Desktop     | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [51f4793383](https://linux-hardware.org/?probe=51f4793383) | Oct 20, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [c37d6f2369](https://linux-hardware.org/?probe=c37d6f2369) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [e389da5691](https://linux-hardware.org/?probe=e389da5691) | Oct 20, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [ad9d78fb43](https://linux-hardware.org/?probe=ad9d78fb43) | Oct 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| Dell          | Latitude 3380               | Notebook    | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| Acer          | Aspire M1930                | Desktop     | [5b9cbd4f58](https://linux-hardware.org/?probe=5b9cbd4f58) | Oct 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [9b344fe820](https://linux-hardware.org/?probe=9b344fe820) | Oct 18, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [ff225777df](https://linux-hardware.org/?probe=ff225777df) | Oct 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7919e68317](https://linux-hardware.org/?probe=7919e68317) | Oct 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [8ba8f257d2](https://linux-hardware.org/?probe=8ba8f257d2) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | Notebook    | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [1117fe6b9e](https://linux-hardware.org/?probe=1117fe6b9e) | Oct 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [8d55df4648](https://linux-hardware.org/?probe=8d55df4648) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [d1b9bb0a39](https://linux-hardware.org/?probe=d1b9bb0a39) | Oct 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c19a6241e1](https://linux-hardware.org/?probe=c19a6241e1) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Acer          | Aspire M1930                | Desktop     | [9fa87ae442](https://linux-hardware.org/?probe=9fa87ae442) | Oct 16, 2022 |
| HP            | 3646h                       | Desktop     | [c7436e0f9e](https://linux-hardware.org/?probe=c7436e0f9e) | Oct 16, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Acer          | Predator G3-710             | Desktop     | [289b6c8a18](https://linux-hardware.org/?probe=289b6c8a18) | Oct 16, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [289b913df1](https://linux-hardware.org/?probe=289b913df1) | Oct 16, 2022 |
| Dell          | Latitude E7450              | Notebook    | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Dell          | 0JD6X3 A05                  | Server      | [746232aa34](https://linux-hardware.org/?probe=746232aa34) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c39709c3b2](https://linux-hardware.org/?probe=c39709c3b2) | Oct 12, 2022 |
| Lenovo        | Y310                        | Notebook    | [0fe2ca4221](https://linux-hardware.org/?probe=0fe2ca4221) | Oct 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [5f84ed0900](https://linux-hardware.org/?probe=5f84ed0900) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5be6738277](https://linux-hardware.org/?probe=5be6738277) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [f74cee10ac](https://linux-hardware.org/?probe=f74cee10ac) | Oct 11, 2022 |
| Standard      | X50-V2                      | Desktop     | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [11b9941d1c](https://linux-hardware.org/?probe=11b9941d1c) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| MSI           | GP60 2PE                    | Notebook    | [530a81df09](https://linux-hardware.org/?probe=530a81df09) | Oct 09, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [8858f6d8f3](https://linux-hardware.org/?probe=8858f6d8f3) | Oct 08, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [baed8b1258](https://linux-hardware.org/?probe=baed8b1258) | Oct 08, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [b3b9f964b7](https://linux-hardware.org/?probe=b3b9f964b7) | Oct 08, 2022 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [8ac874aef9](https://linux-hardware.org/?probe=8ac874aef9) | Oct 07, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [1ca9c6c574](https://linux-hardware.org/?probe=1ca9c6c574) | Oct 07, 2022 |
| Dell          | Latitude E6510              | Notebook    | [67f07a2413](https://linux-hardware.org/?probe=67f07a2413) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cdc6fdbc0](https://linux-hardware.org/?probe=0cdc6fdbc0) | Oct 07, 2022 |
| Intel         | NUC6CAYB J26842-410         | Mini pc     | [e86f93cf49](https://linux-hardware.org/?probe=e86f93cf49) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [2e2105c60b](https://linux-hardware.org/?probe=2e2105c60b) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [afeba82ecf](https://linux-hardware.org/?probe=afeba82ecf) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [7fe9bf7f20](https://linux-hardware.org/?probe=7fe9bf7f20) | Oct 05, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [55afdd2a98](https://linux-hardware.org/?probe=55afdd2a98) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| Lenovo        | ThinkPad T430s 2356B46      | Notebook    | [defefb2514](https://linux-hardware.org/?probe=defefb2514) | Oct 04, 2022 |
| Toshiba       | Satellite Pro P200          | Notebook    | [d08fe22261](https://linux-hardware.org/?probe=d08fe22261) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Samsung       | 550XED                      | Notebook    | [f2e8965164](https://linux-hardware.org/?probe=f2e8965164) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [971859f63e](https://linux-hardware.org/?probe=971859f63e) | Oct 02, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [23475045f2](https://linux-hardware.org/?probe=23475045f2) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6525098252](https://linux-hardware.org/?probe=6525098252) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [4c5134b8fc](https://linux-hardware.org/?probe=4c5134b8fc) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | Notebook    | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [73e2559339](https://linux-hardware.org/?probe=73e2559339) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [d5c0e2c5d3](https://linux-hardware.org/?probe=d5c0e2c5d3) | Sep 30, 2022 |
| Dell          | Latitude 5400               | Notebook    | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | Notebook    | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [b248539946](https://linux-hardware.org/?probe=b248539946) | Sep 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [10b723415e](https://linux-hardware.org/?probe=10b723415e) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Samsung       | 750XED                      | Notebook    | [dcb54d69f8](https://linux-hardware.org/?probe=dcb54d69f8) | Sep 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d0f8e8a0f6](https://linux-hardware.org/?probe=d0f8e8a0f6) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Dell          | Precision M6800             | Notebook    | [a2f07e79d3](https://linux-hardware.org/?probe=a2f07e79d3) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [ac1ee4aab2](https://linux-hardware.org/?probe=ac1ee4aab2) | Sep 25, 2022 |
| Dell          | Latitude 13                 | Notebook    | [28d623103e](https://linux-hardware.org/?probe=28d623103e) | Sep 25, 2022 |
| Dell          | Precision M6800             | Notebook    | [83c3e91298](https://linux-hardware.org/?probe=83c3e91298) | Sep 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [08bd4079f4](https://linux-hardware.org/?probe=08bd4079f4) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [e0eae2efbd](https://linux-hardware.org/?probe=e0eae2efbd) | Sep 24, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [977d73b98a](https://linux-hardware.org/?probe=977d73b98a) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [165b95bd2c](https://linux-hardware.org/?probe=165b95bd2c) | Sep 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [df18be69a3](https://linux-hardware.org/?probe=df18be69a3) | Sep 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [81612aa665](https://linux-hardware.org/?probe=81612aa665) | Sep 24, 2022 |
| Dell          | Latitude E6520              | Notebook    | [fc343204c6](https://linux-hardware.org/?probe=fc343204c6) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [2fa25ddedf](https://linux-hardware.org/?probe=2fa25ddedf) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [8e7d4a7aeb](https://linux-hardware.org/?probe=8e7d4a7aeb) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude E6520              | Notebook    | [79aa87fb47](https://linux-hardware.org/?probe=79aa87fb47) | Sep 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [985fa1c4c7](https://linux-hardware.org/?probe=985fa1c4c7) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [939f154314](https://linux-hardware.org/?probe=939f154314) | Sep 22, 2022 |
| Dell          | Latitude E6320              | Notebook    | [452304d040](https://linux-hardware.org/?probe=452304d040) | Sep 22, 2022 |
| Dell          | Latitude 3120               | Convertible | [524d713bc2](https://linux-hardware.org/?probe=524d713bc2) | Sep 22, 2022 |
| Dell          | XPS 9320                    | Notebook    | [6866f3105c](https://linux-hardware.org/?probe=6866f3105c) | Sep 22, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [efaa235d34](https://linux-hardware.org/?probe=efaa235d34) | Sep 22, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [a4ab03ccc4](https://linux-hardware.org/?probe=a4ab03ccc4) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3e80cdec5b](https://linux-hardware.org/?probe=3e80cdec5b) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [f4aade3998](https://linux-hardware.org/?probe=f4aade3998) | Sep 20, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [95c8201663](https://linux-hardware.org/?probe=95c8201663) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| HP            | 82B4                        | Desktop     | [f4b85399b3](https://linux-hardware.org/?probe=f4b85399b3) | Sep 19, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [6fd34fa73b](https://linux-hardware.org/?probe=6fd34fa73b) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [4c8883345d](https://linux-hardware.org/?probe=4c8883345d) | Sep 19, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [1abf3ddee3](https://linux-hardware.org/?probe=1abf3ddee3) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | 212B                        | Desktop     | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [c6ec4f6320](https://linux-hardware.org/?probe=c6ec4f6320) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [daa76ef1c9](https://linux-hardware.org/?probe=daa76ef1c9) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b0a2728114](https://linux-hardware.org/?probe=b0a2728114) | Sep 17, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [8c905d820d](https://linux-hardware.org/?probe=8c905d820d) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [cf4e574788](https://linux-hardware.org/?probe=cf4e574788) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [ca9e537823](https://linux-hardware.org/?probe=ca9e537823) | Sep 15, 2022 |
| Samsung       | 930MBE                      | Convertible | [7de986bc11](https://linux-hardware.org/?probe=7de986bc11) | Sep 14, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [c8abec750c](https://linux-hardware.org/?probe=c8abec750c) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54ea6ab133](https://linux-hardware.org/?probe=54ea6ab133) | Sep 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4105fc929e](https://linux-hardware.org/?probe=4105fc929e) | Sep 13, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b7eb07ec8d](https://linux-hardware.org/?probe=b7eb07ec8d) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7064ea27f5](https://linux-hardware.org/?probe=7064ea27f5) | Sep 11, 2022 |
| HP            | 82B4                        | Desktop     | [855d078f26](https://linux-hardware.org/?probe=855d078f26) | Sep 11, 2022 |
| HP            | 82B4                        | Desktop     | [e39fbcb897](https://linux-hardware.org/?probe=e39fbcb897) | Sep 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [37681cbc64](https://linux-hardware.org/?probe=37681cbc64) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [81653ec6fc](https://linux-hardware.org/?probe=81653ec6fc) | Sep 11, 2022 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [a008db4da9](https://linux-hardware.org/?probe=a008db4da9) | Sep 11, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| Packard Be... | EasyNote MH36               | Notebook    | [32025f0e69](https://linux-hardware.org/?probe=32025f0e69) | Sep 10, 2022 |
| HP            | 0AA8h                       | Desktop     | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [248f47cae7](https://linux-hardware.org/?probe=248f47cae7) | Sep 08, 2022 |
| SKIKK         | Standard                    | Notebook    | [3d7a0b8762](https://linux-hardware.org/?probe=3d7a0b8762) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| Alienware     | x15 R2                      | Notebook    | [28e491fc3f](https://linux-hardware.org/?probe=28e491fc3f) | Sep 07, 2022 |
| Alienware     | x15 R2                      | Notebook    | [8acf26b5a3](https://linux-hardware.org/?probe=8acf26b5a3) | Sep 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e7d57afa70](https://linux-hardware.org/?probe=e7d57afa70) | Sep 06, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | Notebook    | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [962cc1e746](https://linux-hardware.org/?probe=962cc1e746) | Sep 05, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [15c616f2ca](https://linux-hardware.org/?probe=15c616f2ca) | Sep 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [8aac8566b3](https://linux-hardware.org/?probe=8aac8566b3) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f502f30ee](https://linux-hardware.org/?probe=8f502f30ee) | Sep 03, 2022 |
| Dell          | Latitude 3120               | Notebook    | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [44a711d7ce](https://linux-hardware.org/?probe=44a711d7ce) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [cb976a52d2](https://linux-hardware.org/?probe=cb976a52d2) | Sep 02, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [52f8474c3a](https://linux-hardware.org/?probe=52f8474c3a) | Sep 01, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7140822520](https://linux-hardware.org/?probe=7140822520) | Sep 01, 2022 |
| HP            | ProBook 6460b               | Notebook    | [a0e3db2eed](https://linux-hardware.org/?probe=a0e3db2eed) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | Notebook    | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | 1906                        | Desktop     | [a23cef9946](https://linux-hardware.org/?probe=a23cef9946) | Aug 31, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2c72dfccbb](https://linux-hardware.org/?probe=2c72dfccbb) | Aug 30, 2022 |
| HP            | 2B38                        | Desktop     | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [dcdfb21686](https://linux-hardware.org/?probe=dcdfb21686) | Aug 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8286ea1021](https://linux-hardware.org/?probe=8286ea1021) | Aug 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [b14bf667d5](https://linux-hardware.org/?probe=b14bf667d5) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [df33320d10](https://linux-hardware.org/?probe=df33320d10) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | Notebook    | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a879fb8249](https://linux-hardware.org/?probe=a879fb8249) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [536742931b](https://linux-hardware.org/?probe=536742931b) | Aug 29, 2022 |
| Dell          | Latitude 3300               | Notebook    | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [2d4b907d84](https://linux-hardware.org/?probe=2d4b907d84) | Aug 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [5b0eba15c2](https://linux-hardware.org/?probe=5b0eba15c2) | Aug 29, 2022 |
| Shuttle       | XH310V2                     | Desktop     | [375b995195](https://linux-hardware.org/?probe=375b995195) | Aug 28, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3a7218e2b1](https://linux-hardware.org/?probe=3a7218e2b1) | Aug 27, 2022 |
| HP            | 805D                        | Desktop     | [419598ebba](https://linux-hardware.org/?probe=419598ebba) | Aug 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [717302bb55](https://linux-hardware.org/?probe=717302bb55) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| ASUSTek       | N76VB                       | Notebook    | [e488dd7682](https://linux-hardware.org/?probe=e488dd7682) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| Lenovo        | ThinkPad E580 20KS003GMH    | Notebook    | [5cadf3c5d2](https://linux-hardware.org/?probe=5cadf3c5d2) | Aug 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c42643096a](https://linux-hardware.org/?probe=c42643096a) | Aug 23, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| TEKNOSERVI... | PORTATIL TTL 15             | Notebook    | [054d000bb1](https://linux-hardware.org/?probe=054d000bb1) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e2f0008c16](https://linux-hardware.org/?probe=e2f0008c16) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Dell          | Latitude 7420               | Notebook    | [ebbef2bf39](https://linux-hardware.org/?probe=ebbef2bf39) | Aug 22, 2022 |
| Dell          | Latitude 3300               | Notebook    | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [eb81df27ce](https://linux-hardware.org/?probe=eb81df27ce) | Aug 22, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [1380621999](https://linux-hardware.org/?probe=1380621999) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| HP            | ENVY Notebook               | Notebook    | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| Dell          | Latitude E6420              | Notebook    | [588755599f](https://linux-hardware.org/?probe=588755599f) | Aug 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4817b02964](https://linux-hardware.org/?probe=4817b02964) | Aug 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9619850e97](https://linux-hardware.org/?probe=9619850e97) | Aug 18, 2022 |
| Dell          | Latitude 3380               | Notebook    | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| Dell          | Latitude 3310               | Notebook    | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [66053f0e50](https://linux-hardware.org/?probe=66053f0e50) | Aug 17, 2022 |
| Dell          | Latitude 3310               | Notebook    | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [bbbda98d21](https://linux-hardware.org/?probe=bbbda98d21) | Aug 15, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [ffe1757df5](https://linux-hardware.org/?probe=ffe1757df5) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [caf6393a95](https://linux-hardware.org/?probe=caf6393a95) | Aug 15, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| MSI           | CX705                       | Notebook    | [d2c7d43ba9](https://linux-hardware.org/?probe=d2c7d43ba9) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [c402ff86c1](https://linux-hardware.org/?probe=c402ff86c1) | Aug 13, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [913928c7ee](https://linux-hardware.org/?probe=913928c7ee) | Aug 13, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [bfc035a690](https://linux-hardware.org/?probe=bfc035a690) | Aug 13, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [f48110428f](https://linux-hardware.org/?probe=f48110428f) | Aug 11, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [43257ffabd](https://linux-hardware.org/?probe=43257ffabd) | Aug 11, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| HP            | 18E7                        | Desktop     | [531c621cdb](https://linux-hardware.org/?probe=531c621cdb) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c5ce4b0bff](https://linux-hardware.org/?probe=c5ce4b0bff) | Aug 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [bd5bfb000b](https://linux-hardware.org/?probe=bd5bfb000b) | Aug 10, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [613aea18b5](https://linux-hardware.org/?probe=613aea18b5) | Aug 09, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8558001fa2](https://linux-hardware.org/?probe=8558001fa2) | Aug 09, 2022 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [1d8a97ade8](https://linux-hardware.org/?probe=1d8a97ade8) | Aug 09, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [0afee77b44](https://linux-hardware.org/?probe=0afee77b44) | Aug 09, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [0ceb259a2f](https://linux-hardware.org/?probe=0ceb259a2f) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [9cdc2bc860](https://linux-hardware.org/?probe=9cdc2bc860) | Aug 08, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [254f5e8412](https://linux-hardware.org/?probe=254f5e8412) | Aug 08, 2022 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [942bd9a76d](https://linux-hardware.org/?probe=942bd9a76d) | Aug 08, 2022 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [0de18680fd](https://linux-hardware.org/?probe=0de18680fd) | Aug 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [54981e31fa](https://linux-hardware.org/?probe=54981e31fa) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [362398e54e](https://linux-hardware.org/?probe=362398e54e) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| Unknown       | Unknown                     | Soc         | [c66faf607d](https://linux-hardware.org/?probe=c66faf607d) | Aug 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| HP            | Notebook                    | Notebook    | [d9806ef95e](https://linux-hardware.org/?probe=d9806ef95e) | Aug 06, 2022 |
| Dell          | Precision 3570              | Notebook    | [fd1c9b5ad9](https://linux-hardware.org/?probe=fd1c9b5ad9) | Aug 06, 2022 |
| MP            | MS-7848                     | Desktop     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a0177bc58d](https://linux-hardware.org/?probe=a0177bc58d) | Aug 05, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [eedde9d976](https://linux-hardware.org/?probe=eedde9d976) | Aug 05, 2022 |
| MSI           | 2A9C                        | Desktop     | [d125bcbfe9](https://linux-hardware.org/?probe=d125bcbfe9) | Aug 05, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f52779262f](https://linux-hardware.org/?probe=f52779262f) | Aug 05, 2022 |
| Dell          | Latitude 3310               | Notebook    | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Dell          | 0KG317                      | Desktop     | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| Medion        | E7419 MD60990               | Notebook    | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Dell          | Latitude 3490               | Notebook    | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1b51c25d37](https://linux-hardware.org/?probe=1b51c25d37) | Aug 04, 2022 |
| Dell          | Latitude 3310               | Notebook    | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9a4f5806f8](https://linux-hardware.org/?probe=9a4f5806f8) | Aug 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [d3e0c77946](https://linux-hardware.org/?probe=d3e0c77946) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [dabb21caca](https://linux-hardware.org/?probe=dabb21caca) | Aug 04, 2022 |
| Standard      | X50-V2                      | Desktop     | [cb09d559a8](https://linux-hardware.org/?probe=cb09d559a8) | Aug 04, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [0886c5ef7f](https://linux-hardware.org/?probe=0886c5ef7f) | Aug 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [f0479b116f](https://linux-hardware.org/?probe=f0479b116f) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [245834865d](https://linux-hardware.org/?probe=245834865d) | Aug 03, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [87bf7fcb48](https://linux-hardware.org/?probe=87bf7fcb48) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Netherlands/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 567       | 14.92%  |
| Ubuntu 18.04                 | 303       | 7.97%   |
| OpenMandriva 4.3             | 195       | 5.13%   |
| Ubuntu 22.04                 | 167       | 4.39%   |
| Debian 11                    | 86        | 2.26%   |
| Zorin 16                     | 71        | 1.87%   |
| Linux Mint 20.3              | 70        | 1.84%   |
| Ubuntu 20.10                 | 66        | 1.74%   |
| Arch                         | 66        | 1.74%   |
| Xubuntu 20.04                | 55        | 1.45%   |
| OpenMandriva 4.2             | 54        | 1.42%   |
| KDE neon 20.04               | 54        | 1.42%   |
| Fedora 34                    | 53        | 1.39%   |
| Linux Mint 20.2              | 52        | 1.37%   |
| Ubuntu 21.10                 | 51        | 1.34%   |
| Fedora 36                    | 51        | 1.34%   |
| Manjaro                      | 49        | 1.29%   |
| Arch Rolling                 | 49        | 1.29%   |
| Ubuntu 21.04                 | 46        | 1.21%   |
| Linux Mint 20.1              | 46        | 1.21%   |
| Linux Mint 19.3              | 46        | 1.21%   |
| Ubuntu 19.10                 | 43        | 1.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 42        | 1.1%    |
| Pop!_OS 22.04                | 41        | 1.08%   |
| Pop!_OS 20.10                | 41        | 1.08%   |
| Fedora 33                    | 41        | 1.08%   |
| Pop!_OS 21.04                | 39        | 1.03%   |
| Pop!_OS 20.04                | 39        | 1.03%   |
| Fedora 35                    | 39        | 1.03%   |
| Kubuntu 20.04                | 38        | 1%      |
| Fedora 31                    | 38        | 1%      |
| Zorin 15                     | 37        | 0.97%   |
| Linux Mint 20                | 37        | 0.97%   |
| Ubuntu 19.04                 | 35        | 0.92%   |
| Pop!_OS 21.10                | 35        | 0.92%   |
| Fedora 32                    | 33        | 0.87%   |
| ArcoLinux Rolling            | 33        | 0.87%   |
| Fedora 37                    | 31        | 0.82%   |
| Ubuntu 22.10                 | 30        | 0.79%   |
| Debian 10                    | 30        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1281      | 35.57%  |
| Linux Mint    | 315       | 8.75%   |
| OpenMandriva  | 288       | 8%      |
| Fedora        | 259       | 7.19%   |
| Pop!_OS       | 187       | 5.19%   |
| Debian        | 139       | 3.86%   |
| Manjaro       | 137       | 3.8%    |
| Zorin         | 117       | 3.25%   |
| Arch          | 116       | 3.22%   |
| Xubuntu       | 94        | 2.61%   |
| Kubuntu       | 78        | 2.17%   |
| KDE neon      | 71        | 1.97%   |
| openSUSE      | 57        | 1.58%   |
| ArcoLinux     | 36        | 1%      |
| Gentoo        | 28        | 0.78%   |
| Kali          | 27        | 0.75%   |
| ROSA          | 26        | 0.72%   |
| Lubuntu       | 24        | 0.67%   |
| Elementary    | 24        | 0.67%   |
| EndeavourOS   | 23        | 0.64%   |
| Ubuntu Unity  | 22        | 0.61%   |
| Ubuntu MATE   | 20        | 0.56%   |
| Clear Linux   | 20        | 0.56%   |
| Endless       | 16        | 0.44%   |
| SteamOS       | 15        | 0.42%   |
| Ubuntu Budgie | 13        | 0.36%   |
| Parrot        | 12        | 0.33%   |
| MX            | 12        | 0.33%   |
| LMDE          | 12        | 0.33%   |
| Peppermint    | 10        | 0.28%   |
| CentOS        | 10        | 0.28%   |
| Raspbian      | 9         | 0.25%   |
| Garuda Linux  | 9         | 0.25%   |
| Solus         | 8         | 0.22%   |
| BlackPanther  | 6         | 0.17%   |
| Reborn OS     | 5         | 0.14%   |
| RHEL          | 4         | 0.11%   |
| Nobara        | 4         | 0.11%   |
| LinuxFX       | 4         | 0.11%   |
| Devuan        | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 194       | 4.6%    |
| 5.4.0-42-generic         | 69        | 1.64%   |
| 5.10.14-desktop-1omv4002 | 53        | 1.26%   |
| 5.4.0-58-generic         | 43        | 1.02%   |
| 5.8.0-50-generic         | 41        | 0.97%   |
| 5.15.0-58-generic        | 37        | 0.88%   |
| 5.4.0-52-generic         | 36        | 0.85%   |
| 5.4.0-48-generic         | 35        | 0.83%   |
| 5.15.0-56-generic        | 35        | 0.83%   |
| 5.11.0-38-generic        | 33        | 0.78%   |
| 5.15.0-46-generic        | 30        | 0.71%   |
| 5.8.0-43-generic         | 26        | 0.62%   |
| 5.13.0-28-generic        | 26        | 0.62%   |
| 5.11.0-27-generic        | 26        | 0.62%   |
| 5.4.0-77-generic         | 25        | 0.59%   |
| 5.4.0-26-generic         | 25        | 0.59%   |
| 5.15.0-52-generic        | 25        | 0.59%   |
| 6.1.1-desktop-1omv2290   | 24        | 0.57%   |
| 5.4.0-40-generic         | 24        | 0.57%   |
| 5.15.0-43-generic        | 24        | 0.57%   |
| 5.4.0-37-generic         | 22        | 0.52%   |
| 5.15.0-48-generic        | 22        | 0.52%   |
| 5.8.0-53-generic         | 21        | 0.5%    |
| 5.4.0-65-generic         | 21        | 0.5%    |
| 5.15.0-60-generic        | 21        | 0.5%    |
| 5.11.0-7620-generic      | 21        | 0.5%    |
| 5.8.0-7630-generic       | 20        | 0.47%   |
| 5.4.0-56-generic         | 20        | 0.47%   |
| 5.4.0-33-generic         | 20        | 0.47%   |
| 5.4.0-29-generic         | 20        | 0.47%   |
| 5.13.0-39-generic        | 20        | 0.47%   |
| 5.3.0-46-generic         | 19        | 0.45%   |
| 5.8.0-48-generic         | 18        | 0.43%   |
| 5.4.0-54-generic         | 18        | 0.43%   |
| 5.4.0-47-generic         | 18        | 0.43%   |
| 5.11.0-43-generic        | 18        | 0.43%   |
| 4.15.0-29-generic        | 18        | 0.43%   |
| 5.8.0-44-generic         | 17        | 0.4%    |
| 5.4.0-91-generic         | 17        | 0.4%    |
| 5.4.0-74-generic         | 17        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 706       | 17.88%  |
| 5.15.0  | 309       | 7.82%   |
| 5.8.0   | 284       | 7.19%   |
| 4.15.0  | 239       | 6.05%   |
| 5.11.0  | 235       | 5.95%   |
| 5.16.7  | 197       | 4.99%   |
| 5.13.0  | 195       | 4.94%   |
| 5.3.0   | 141       | 3.57%   |
| 5.0.0   | 106       | 2.68%   |
| 5.10.0  | 103       | 2.61%   |
| 4.18.0  | 72        | 1.82%   |
| 5.10.14 | 56        | 1.42%   |
| 5.19.0  | 51        | 1.29%   |
| 4.19.0  | 36        | 0.91%   |
| 6.1.1   | 28        | 0.71%   |
| 5.14.0  | 20        | 0.51%   |
| 4.4.0   | 18        | 0.46%   |
| 5.6.0   | 16        | 0.41%   |
| 5.16.11 | 16        | 0.41%   |
| 5.17.5  | 15        | 0.38%   |
| 6.0.6   | 14        | 0.35%   |
| 5.9.16  | 14        | 0.35%   |
| 6.0.0   | 11        | 0.28%   |
| 5.3.18  | 11        | 0.28%   |
| 5.18.0  | 11        | 0.28%   |
| 5.17.1  | 11        | 0.28%   |
| 5.16.0  | 10        | 0.25%   |
| 6.0.12  | 9         | 0.23%   |
| 5.9.8   | 9         | 0.23%   |
| 5.9.0   | 9         | 0.23%   |
| 5.8.16  | 9         | 0.23%   |
| 5.17.0  | 9         | 0.23%   |
| 5.16.19 | 9         | 0.23%   |
| 5.15.5  | 9         | 0.23%   |
| 5.15.12 | 9         | 0.23%   |
| 5.14.14 | 9         | 0.23%   |
| 6.1.0   | 8         | 0.2%    |
| 6.0.5   | 8         | 0.2%    |
| 5.4.8   | 8         | 0.2%    |
| 5.11.12 | 8         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 770       | 19.72%  |
| 5.15    | 416       | 10.65%  |
| 5.8     | 335       | 8.58%   |
| 5.11    | 281       | 7.2%    |
| 5.16    | 263       | 6.73%   |
| 4.15    | 240       | 6.15%   |
| 5.13    | 236       | 6.04%   |
| 5.10    | 225       | 5.76%   |
| 5.3     | 173       | 4.43%   |
| 5.0     | 110       | 2.82%   |
| 5.19    | 88        | 2.25%   |
| 4.18    | 86        | 2.2%    |
| 6.0     | 78        | 2%      |
| 6.1     | 75        | 1.92%   |
| 5.17    | 68        | 1.74%   |
| 5.18    | 61        | 1.56%   |
| 5.14    | 59        | 1.51%   |
| 5.9     | 56        | 1.43%   |
| 5.6     | 51        | 1.31%   |
| 4.19    | 49        | 1.25%   |
| 5.12    | 36        | 0.92%   |
| 5.7     | 32        | 0.82%   |
| 5.5     | 28        | 0.72%   |
| 4.9     | 26        | 0.67%   |
| 4.4     | 20        | 0.51%   |
| 5.2     | 9         | 0.23%   |
| 4.16    | 5         | 0.13%   |
| 4.10    | 5         | 0.13%   |
| 4.20    | 4         | 0.1%    |
| 4.14    | 4         | 0.1%    |
| 4.12    | 4         | 0.1%    |
| 4.1     | 2         | 0.05%   |
| 3.16    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 6.2     | 1         | 0.03%   |
| 5.17.1  | 1         | 0.03%   |
| 5.1     | 1         | 0.03%   |
| 4.7     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3356      | 95.83%  |
| i686    | 98        | 2.8%    |
| aarch64 | 39        | 1.11%   |
| armv7l  | 7         | 0.2%    |
| armv8l  | 1         | 0.03%   |
| armv6l  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1613      | 44.4%   |
| KDE5             | 611       | 16.82%  |
| Unknown          | 512       | 14.09%  |
| XFCE             | 260       | 7.16%   |
| X-Cinnamon       | 231       | 6.36%   |
| KDE              | 93        | 2.56%   |
| MATE             | 76        | 2.09%   |
| Cinnamon         | 34        | 0.94%   |
| LXQt             | 25        | 0.69%   |
| Pantheon         | 24        | 0.66%   |
| Unity            | 22        | 0.61%   |
| Budgie           | 22        | 0.61%   |
| LXDE             | 21        | 0.58%   |
| KDE4             | 15        | 0.41%   |
| i3               | 15        | 0.41%   |
| GNOME Flashback  | 10        | 0.28%   |
| Openbox          | 6         | 0.17%   |
| Deepin           | 6         | 0.17%   |
| sway             | 5         | 0.14%   |
| icewm            | 5         | 0.14%   |
| qtile            | 4         | 0.11%   |
| Enlightenment    | 4         | 0.11%   |
| awesome          | 4         | 0.11%   |
| trinity          | 2         | 0.06%   |
| lightdm-xsession | 2         | 0.06%   |
| GNOME Classic    | 2         | 0.06%   |
| xmonad           | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| jwm              | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| fluxbox          | 1         | 0.03%   |
| DWM              | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |
| Core             | 1         | 0.03%   |
| bspwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2745      | 76.53%  |
| Wayland | 516       | 14.39%  |
| Unknown | 252       | 7.03%   |
| Tty     | 73        | 2.04%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1900      | 52.47%  |
| SDDM    | 523       | 14.44%  |
| GDM     | 426       | 11.76%  |
| GDM3    | 351       | 9.69%   |
| LightDM | 293       | 8.09%   |
| TDM     | 94        | 2.6%    |
| KDM     | 14        | 0.39%   |
| XDM     | 7         | 0.19%   |
| Ly      | 4         | 0.11%   |
| SLiM    | 3         | 0.08%   |
| GREETD  | 3         | 0.08%   |
| NODM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1693      | 47.19%  |
| nl_NL       | 1027      | 28.62%  |
| Unknown     | 427       | 11.9%   |
| en_GB       | 146       | 4.07%   |
| C           | 58        | 1.62%   |
| de_DE       | 34        | 0.95%   |
| pl_PL       | 33        | 0.92%   |
| ru_RU       | 22        | 0.61%   |
| en_IE       | 13        | 0.36%   |
| fr_FR       | 10        | 0.28%   |
| en_NL       | 10        | 0.28%   |
| POSIX       | 9         | 0.25%   |
| en_CA       | 7         | 0.2%    |
| it_IT       | 6         | 0.17%   |
| en_IN       | 6         | 0.17%   |
| nl_BE       | 5         | 0.14%   |
| fr_BE       | 5         | 0.14%   |
| en_DK       | 5         | 0.14%   |
| ru_UA       | 4         | 0.11%   |
| pt_PT       | 4         | 0.11%   |
| es_ES       | 4         | 0.11%   |
| en_AG       | 4         | 0.11%   |
| de_AT       | 4         | 0.11%   |
| C.UTF8      | 4         | 0.11%   |
| sv_SE       | 3         | 0.08%   |
| sk_SK       | 3         | 0.08%   |
| es_MX       | 3         | 0.08%   |
| en_AU       | 3         | 0.08%   |
| cs_CZ       | 3         | 0.08%   |
| zh_CN       | 2         | 0.06%   |
| uk_UA       | 2         | 0.06%   |
| pt_BR       | 2         | 0.06%   |
| nl_AW       | 2         | 0.06%   |
| nb_NO       | 2         | 0.06%   |
| hu_HU       | 2         | 0.06%   |
| en_ZA       | 2         | 0.06%   |
| en_US.utf-8 | 2         | 0.06%   |
| en_SG       | 2         | 0.06%   |
| ar_KW       | 2         | 0.06%   |
| tr_TR       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1822      | 51.09%  |
| BIOS | 1744      | 48.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2719      | 76.21%  |
| Overlay | 332       | 9.3%    |
| Btrfs   | 280       | 7.85%   |
| Unknown | 125       | 3.5%    |
| Xfs     | 48        | 1.35%   |
| Zfs     | 35        | 0.98%   |
| Ext2    | 10        | 0.28%   |
| F2fs    | 8         | 0.22%   |
| Ext3    | 4         | 0.11%   |
| Tmpfs   | 3         | 0.08%   |
| Aufs    | 3         | 0.08%   |
| Jfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2046      | 57.5%   |
| GPT     | 1211      | 34.04%  |
| MBR     | 301       | 8.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3058      | 85.85%  |
| Yes       | 504       | 14.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2476      | 69.77%  |
| Yes       | 1073      | 30.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 575       | 16.45%  |
| Hewlett-Packard         | 553       | 15.82%  |
| ASUSTek Computer        | 500       | 14.31%  |
| Lenovo                  | 385       | 11.02%  |
| Acer                    | 217       | 6.21%   |
| MSI                     | 197       | 5.64%   |
| Gigabyte Technology     | 193       | 5.52%   |
| ASRock                  | 141       | 4.03%   |
| Apple                   | 105       | 3%      |
| Intel                   | 71        | 2.03%   |
| Medion                  | 55        | 1.57%   |
| Toshiba                 | 53        | 1.52%   |
| Notebook                | 45        | 1.29%   |
| Raspberry Pi Foundation | 41        | 1.17%   |
| Unknown                 | 27        | 0.77%   |
| Packard Bell            | 26        | 0.74%   |
| Samsung Electronics     | 23        | 0.66%   |
| Fujitsu                 | 20        | 0.57%   |
| Google                  | 17        | 0.49%   |
| Sony                    | 15        | 0.43%   |
| Microsoft               | 15        | 0.43%   |
| Valve                   | 13        | 0.37%   |
| HUAWEI                  | 12        | 0.34%   |
| Fujitsu Siemens         | 12        | 0.34%   |
| Foxconn                 | 10        | 0.29%   |
| Alienware               | 9         | 0.26%   |
| Supermicro              | 8         | 0.23%   |
| Pegatron                | 8         | 0.23%   |
| Biostar                 | 7         | 0.2%    |
| TUXEDO                  | 6         | 0.17%   |
| Timi                    | 6         | 0.17%   |
| Shuttle                 | 6         | 0.17%   |
| AMI                     | 5         | 0.14%   |
| ZOTAC                   | 4         | 0.11%   |
| System76                | 4         | 0.11%   |
| PC Specialist           | 4         | 0.11%   |
| Insyde                  | 4         | 0.11%   |
| Chuwi                   | 4         | 0.11%   |
| BESSTAR Tech            | 4         | 0.11%   |
| TrekStor                | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Latitude 3120                  | 55        | 1.57%   |
| Dell Latitude 3190 2-in-1           | 41        | 1.17%   |
| Unknown                             | 38        | 1.09%   |
| Dell Latitude 3310                  | 31        | 0.89%   |
| ASUS All Series                     | 27        | 0.77%   |
| RPi Raspberry Pi                    | 17        | 0.49%   |
| Valve Jupiter                       | 13        | 0.37%   |
| Dell XPS 15 7590                    | 11        | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 10        | 0.29%   |
| Dell OptiPlex 7010                  | 10        | 0.29%   |
| MSI MS-7C02                         | 9         | 0.26%   |
| HP Notebook                         | 9         | 0.26%   |
| HP ZBook Studio G5                  | 8         | 0.23%   |
| Dell XPS 15 9560                    | 8         | 0.23%   |
| Dell OptiPlex 3020                  | 8         | 0.23%   |
| Dell Latitude 3300                  | 8         | 0.23%   |
| ASRock B450M Pro4                   | 8         | 0.23%   |
| MSI MS-7C37                         | 7         | 0.2%    |
| MSI MS-7B86                         | 7         | 0.2%    |
| MSI MS-7817                         | 7         | 0.2%    |
| HP Pavilion Laptop 15-cw1xxx        | 7         | 0.2%    |
| HP Pavilion Gaming Laptop 15-cx0xxx | 7         | 0.2%    |
| HP Pavilion g7                      | 7         | 0.2%    |
| HP Pavilion g6                      | 7         | 0.2%    |
| HP Pavilion dv7                     | 7         | 0.2%    |
| Dell Latitude E6410                 | 7         | 0.2%    |
| Apple MacBookPro9,2                 | 7         | 0.2%    |
| MSI MS-7721                         | 6         | 0.17%   |
| Intel NUC8i3BEH                     | 6         | 0.17%   |
| HP ProBook 6570b                    | 6         | 0.17%   |
| HP Pavilion dv6                     | 6         | 0.17%   |
| HP EliteBook 8570w                  | 6         | 0.17%   |
| HP EliteBook 8460p                  | 6         | 0.17%   |
| HP Compaq dc7900 Small Form Factor  | 6         | 0.17%   |
| Dell XPS 15 9570                    | 6         | 0.17%   |
| Dell XPS 15 9550                    | 6         | 0.17%   |
| Dell XPS 15 9500                    | 6         | 0.17%   |
| Dell XPS 13 9360                    | 6         | 0.17%   |
| Dell XPS 13 9310                    | 6         | 0.17%   |
| Dell Latitude E6320                 | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 297       | 8.5%    |
| Lenovo ThinkPad       | 197       | 5.64%   |
| Acer Aspire           | 150       | 4.29%   |
| HP Pavilion           | 95        | 2.72%   |
| HP Compaq             | 94        | 2.69%   |
| HP EliteBook          | 90        | 2.58%   |
| Dell XPS              | 88        | 2.52%   |
| Lenovo IdeaPad        | 64        | 1.83%   |
| HP ProBook            | 63        | 1.8%    |
| Dell OptiPlex         | 60        | 1.72%   |
| ASUS PRIME            | 58        | 1.66%   |
| Toshiba Satellite     | 48        | 1.37%   |
| Dell Inspiron         | 46        | 1.32%   |
| ASUS ROG              | 44        | 1.26%   |
| RPi Raspberry         | 41        | 1.17%   |
| Unknown               | 38        | 1.09%   |
| HP ZBook              | 32        | 0.92%   |
| Dell Precision        | 32        | 0.92%   |
| Lenovo Yoga           | 29        | 0.83%   |
| HP ENVY               | 29        | 0.83%   |
| ASUS All              | 27        | 0.77%   |
| Lenovo Legion         | 22        | 0.63%   |
| ASUS VivoBook         | 20        | 0.57%   |
| Packard Bell EasyNote | 19        | 0.54%   |
| HP Laptop             | 19        | 0.54%   |
| Gigabyte X570         | 19        | 0.54%   |
| ASUS TUF              | 17        | 0.49%   |
| Microsoft Surface     | 15        | 0.43%   |
| Lenovo ThinkCentre    | 14        | 0.4%    |
| Valve Jupiter         | 13        | 0.37%   |
| Lenovo ThinkBook      | 12        | 0.34%   |
| Fujitsu LIFEBOOK      | 12        | 0.34%   |
| Acer TravelMate       | 12        | 0.34%   |
| Acer Swift            | 12        | 0.34%   |
| HP Spectre            | 11        | 0.31%   |
| HP ProDesk            | 11        | 0.31%   |
| ASUS ZenBook          | 11        | 0.31%   |
| ASRock B450M          | 11        | 0.31%   |
| Dell Studio           | 10        | 0.29%   |
| ASUS P8H61-M          | 10        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 419       | 11.99%  |
| 2018    | 311       | 8.9%    |
| 2020    | 270       | 7.73%   |
| 2012    | 266       | 7.61%   |
| 2021    | 251       | 7.18%   |
| 2011    | 241       | 6.9%    |
| 2013    | 225       | 6.44%   |
| 2017    | 217       | 6.21%   |
| 2014    | 190       | 5.44%   |
| 2010    | 178       | 5.09%   |
| 2016    | 177       | 5.06%   |
| 2015    | 174       | 4.98%   |
| 2009    | 144       | 4.12%   |
| 2008    | 143       | 4.09%   |
| 2007    | 107       | 3.06%   |
| 2022    | 69        | 1.97%   |
| 2006    | 49        | 1.4%    |
| Unknown | 43        | 1.23%   |
| 2005    | 11        | 0.31%   |
| 2004    | 6         | 0.17%   |
| 2003    | 2         | 0.06%   |
| 2023    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1849      | 52.9%   |
| Desktop        | 1231      | 35.22%  |
| Convertible    | 186       | 5.32%   |
| Mini pc        | 80        | 2.29%   |
| System on chip | 45        | 1.29%   |
| All in one     | 43        | 1.23%   |
| Tablet         | 36        | 1.03%   |
| Server         | 23        | 0.66%   |
| Phone          | 2         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3230      | 91.79%  |
| Enabled  | 289       | 8.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3472      | 99.34%  |
| Yes  | 23        | 0.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 842       | 23.7%   |
| 16.01-24.0      | 719       | 20.24%  |
| 3.01-4.0        | 663       | 18.67%  |
| 8.01-16.0       | 601       | 16.92%  |
| 32.01-64.0      | 350       | 9.85%   |
| 1.01-2.0        | 131       | 3.69%   |
| 64.01-256.0     | 86        | 2.42%   |
| 2.01-3.0        | 66        | 1.86%   |
| 24.01-32.0      | 61        | 1.72%   |
| 0.51-1.0        | 31        | 0.87%   |
| More than 256.0 | 1         | 0.03%   |
| 0.01-0.5        | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1457      | 37.84%  |
| 2.01-3.0    | 909       | 23.61%  |
| 4.01-8.0    | 496       | 12.88%  |
| 3.01-4.0    | 484       | 12.57%  |
| 0.51-1.0    | 249       | 6.47%   |
| 8.01-16.0   | 173       | 4.49%   |
| 0.01-0.5    | 36        | 0.94%   |
| 16.01-24.0  | 32        | 0.83%   |
| 32.01-64.0  | 10        | 0.26%   |
| 24.01-32.0  | 3         | 0.08%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2107      | 58.77%  |
| 2       | 889       | 24.8%   |
| 3       | 277       | 7.73%   |
| 4       | 137       | 3.82%   |
| 5       | 65        | 1.81%   |
| 0       | 47        | 1.31%   |
| 6       | 29        | 0.81%   |
| 7       | 18        | 0.5%    |
| 8       | 6         | 0.17%   |
| Unknown | 4         | 0.11%   |
| 9       | 3         | 0.08%   |
| 28      | 1         | 0.03%   |
| 27      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2183      | 61.88%  |
| Yes       | 1345      | 38.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2941      | 83.86%  |
| No        | 566       | 16.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2576      | 73.35%  |
| No        | 936       | 26.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2098      | 59.05%  |
| No        | 1455      | 40.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Netherlands | 3495      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Amsterdam              | 649       | 17.5%   |
| The Hague              | 179       | 4.83%   |
| Schagen                | 142       | 3.83%   |
| Rotterdam              | 119       | 3.21%   |
| Utrecht                | 90        | 2.43%   |
| Haarlem                | 75        | 2.02%   |
| Delft                  | 71        | 1.91%   |
| Groningen              | 63        | 1.7%    |
| Almere Stad            | 55        | 1.48%   |
| Eindhoven              | 54        | 1.46%   |
| Tilburg                | 43        | 1.16%   |
| Naaldwijk              | 42        | 1.13%   |
| Amersfoort             | 42        | 1.13%   |
| Leiden                 | 36        | 0.97%   |
| Enschede               | 34        | 0.92%   |
| Nijmegen               | 32        | 0.86%   |
| Zoetermeer             | 31        | 0.84%   |
| Arnhem                 | 30        | 0.81%   |
| Breda                  | 28        | 0.75%   |
| Apeldoorn              | 27        | 0.73%   |
| Almelo                 | 26        | 0.7%    |
| Amstelveen             | 24        | 0.65%   |
| Zwolle                 | 23        | 0.62%   |
| Hilversum              | 23        | 0.62%   |
| Zeist                  | 22        | 0.59%   |
| Capelle aan den IJssel | 21        | 0.57%   |
| Lelystad               | 20        | 0.54%   |
| Dordrecht              | 20        | 0.54%   |
| Assen                  | 20        | 0.54%   |
| 's-Hertogenbosch       | 19        | 0.51%   |
| Roosendaal             | 18        | 0.49%   |
| Maastricht             | 18        | 0.49%   |
| Schiedam               | 17        | 0.46%   |
| Alkmaar                | 16        | 0.43%   |
| Purmerend              | 15        | 0.4%    |
| Heerlen                | 15        | 0.4%    |
| Gouda                  | 15        | 0.4%    |
| Waalwijk               | 14        | 0.38%   |
| Rijswijk               | 14        | 0.38%   |
| Meppel                 | 14        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1154      | 1861   | 23.01%  |
| WDC                         | 667       | 1025   | 13.3%   |
| Seagate                     | 625       | 977    | 12.46%  |
| Kingston                    | 306       | 399    | 6.1%    |
| Toshiba                     | 280       | 386    | 5.58%   |
| SanDisk                     | 220       | 295    | 4.39%   |
| Crucial                     | 214       | 271    | 4.27%   |
| Unknown                     | 205       | 258    | 4.09%   |
| SK hynix                    | 177       | 207    | 3.53%   |
| Hitachi                     | 154       | 195    | 3.07%   |
| Intel                       | 151       | 204    | 3.01%   |
| HGST                        | 91        | 111    | 1.81%   |
| Micron Technology           | 61        | 72     | 1.22%   |
| A-DATA Technology           | 58        | 63     | 1.16%   |
| KIOXIA                      | 46        | 60     | 0.92%   |
| Apple                       | 44        | 59     | 0.88%   |
| LITEON                      | 40        | 50     | 0.8%    |
| Maxtor                      | 30        | 40     | 0.6%    |
| OCZ                         | 28        | 35     | 0.56%   |
| Phison                      | 26        | 37     | 0.52%   |
| Corsair                     | 26        | 34     | 0.52%   |
| China                       | 25        | 35     | 0.5%    |
| Transcend                   | 23        | 28     | 0.46%   |
| LITEONIT                    | 23        | 25     | 0.46%   |
| PNY                         | 20        | 24     | 0.4%    |
| Fujitsu                     | 20        | 22     | 0.4%    |
| SSSTC                       | 19        | 20     | 0.38%   |
| ASMT                        | 15        | 17     | 0.3%    |
| Gigabyte Technology         | 14        | 19     | 0.28%   |
| Kingston Technology Company | 12        | 13     | 0.24%   |
| Intenso                     | 12        | 12     | 0.24%   |
| Patriot                     | 11        | 14     | 0.22%   |
| Micron/Crucial Technology   | 11        | 15     | 0.22%   |
| KingFast                    | 11        | 15     | 0.22%   |
| GOODRAM                     | 11        | 12     | 0.22%   |
| SPCC                        | 10        | 11     | 0.2%    |
| JMicron Technology          | 9         | 15     | 0.18%   |
| XPG                         | 8         | 10     | 0.16%   |
| Silicon Motion              | 8         | 9      | 0.16%   |
| Unknown                     | 8         | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                            | 90        | 1.59%   |
| Samsung SSD 860 EVO 500GB                            | 63        | 1.12%   |
| Samsung SSD 850 EVO 500GB                            | 56        | 0.99%   |
| Samsung NVMe SSD Drive 500GB                         | 47        | 0.83%   |
| Samsung NVMe SSD Drive 1TB                           | 46        | 0.81%   |
| Kingston SA400S37240G 240GB SSD                      | 45        | 0.8%    |
| Kingston SA400S37120G 120GB SSD                      | 40        | 0.71%   |
| Samsung SSD 840 EVO 250GB                            | 38        | 0.67%   |
| Unknown MMC Card  32GB                               | 36        | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 35        | 0.62%   |
| Seagate Expansion 1TB                                | 31        | 0.55%   |
| Samsung SSD 840 EVO 120GB                            | 31        | 0.55%   |
| Samsung SSD 860 EVO 1TB                              | 29        | 0.51%   |
| Samsung SSD 970 EVO 1TB                              | 28        | 0.5%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 28        | 0.5%    |
| Unknown MMC Card  64GB                               | 27        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                         | 27        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB                       | 26        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                     | 26        | 0.46%   |
| HGST HTS721010A9E630 1TB                             | 26        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                      | 25        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                       | 25        | 0.44%   |
| Samsung NVMe SSD Drive 512GB                         | 25        | 0.44%   |
| Samsung SSD 980 1TB                                  | 23        | 0.41%   |
| SK hynix BC711 NVMe 128GB                            | 22        | 0.39%   |
| Seagate ST9500325AS 500GB                            | 22        | 0.39%   |
| Samsung NVMe SSD Drive 1024GB                        | 22        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB                          | 22        | 0.39%   |
| Toshiba MQ01ABF050 500GB                             | 21        | 0.37%   |
| Toshiba DT01ACA100 1TB                               | 21        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                         | 20        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 20        | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB                       | 19        | 0.34%   |
| Samsung SSD 860 QVO 1TB                              | 19        | 0.34%   |
| Samsung SSD 860 EVO 250GB                            | 19        | 0.34%   |
| Crucial CT240BX500SSD1 240GB                         | 19        | 0.34%   |
| Toshiba MQ01ABD100 1TB                               | 18        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                         | 18        | 0.32%   |
| Samsung SSD 870 QVO 1TB                              | 18        | 0.32%   |
| Samsung SSD 850 EVO 120GB                            | 17        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 617       | 962    | 33.81%  |
| WDC                 | 539       | 836    | 29.53%  |
| Toshiba             | 190       | 272    | 10.41%  |
| Hitachi             | 154       | 195    | 8.44%   |
| Samsung Electronics | 130       | 205    | 7.12%   |
| HGST                | 91        | 111    | 4.99%   |
| Maxtor              | 30        | 40     | 1.64%   |
| Fujitsu             | 20        | 22     | 1.1%    |
| Apple               | 10        | 12     | 0.55%   |
| Unknown             | 8         | 15     | 0.44%   |
| JMicron Technology  | 7         | 9      | 0.38%   |
| ASMT                | 5         | 7      | 0.27%   |
| Intenso             | 3         | 3      | 0.16%   |
| HGST HTS            | 3         | 4      | 0.16%   |
| SABRENT             | 2         | 2      | 0.11%   |
| KESU                | 2         | 2      | 0.11%   |
| IBM/Hitachi         | 2         | 2      | 0.11%   |
| ExcelStor           | 2         | 2      | 0.11%   |
| ASMedia             | 2         | 2      | 0.11%   |
| Synology            | 1         | 1      | 0.05%   |
| QNAP                | 1         | 1      | 0.05%   |
| NAS                 | 1         | 10     | 0.05%   |
| Maxtor 6            | 1         | 2      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LIO-ORG             | 1         | 4      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 616       | 917    | 34.11%  |
| Kingston            | 232       | 288    | 12.85%  |
| Crucial             | 204       | 261    | 11.3%   |
| SanDisk             | 148       | 182    | 8.19%   |
| WDC                 | 71        | 99     | 3.93%   |
| Intel               | 64        | 81     | 3.54%   |
| A-DATA Technology   | 49        | 54     | 2.71%   |
| SK hynix            | 40        | 50     | 2.21%   |
| LITEON              | 33        | 43     | 1.83%   |
| Micron Technology   | 32        | 40     | 1.77%   |
| OCZ                 | 28        | 35     | 1.55%   |
| Toshiba             | 25        | 30     | 1.38%   |
| China               | 25        | 35     | 1.38%   |
| Apple               | 24        | 27     | 1.33%   |
| LITEONIT            | 23        | 25     | 1.27%   |
| PNY                 | 20        | 24     | 1.11%   |
| Transcend           | 19        | 24     | 1.05%   |
| Corsair             | 19        | 26     | 1.05%   |
| Patriot             | 11        | 14     | 0.61%   |
| Goodram             | 11        | 12     | 0.61%   |
| SPCC                | 10        | 11     | 0.55%   |
| ASMT                | 10        | 10     | 0.55%   |
| Intenso             | 7         | 7      | 0.39%   |
| Mushkin             | 5         | 7      | 0.28%   |
| KingSpec            | 5         | 6      | 0.28%   |
| Gigabyte Technology | 5         | 9      | 0.28%   |
| Netac               | 4         | 4      | 0.22%   |
| KingFast            | 4         | 5      | 0.22%   |
| Apacer              | 4         | 4      | 0.22%   |
| ACASIS              | 4         | 4      | 0.22%   |
| SSSTC               | 3         | 3      | 0.17%   |
| Plextor             | 3         | 4      | 0.17%   |
| Leven               | 3         | 3      | 0.17%   |
| Unknown             | 3         | 5      | 0.17%   |
| Vaseky              | 2         | 2      | 0.11%   |
| Unknown             | 2         | 2      | 0.11%   |
| Team                | 2         | 4      | 0.11%   |
| Seagate             | 2         | 2      | 0.11%   |
| Phison              | 2         | 3      | 0.11%   |
| KingDian            | 2         | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1595      | 2400   | 35.05%  |
| HDD     | 1508      | 2724   | 33.14%  |
| NVMe    | 1201      | 1719   | 26.39%  |
| MMC     | 196       | 238    | 4.31%   |
| Unknown | 51        | 63     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2478      | 4876   | 60.85%  |
| NVMe | 1199      | 1712   | 29.44%  |
| SAS  | 199       | 318    | 4.89%   |
| MMC  | 196       | 238    | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2029      | 3148   | 62.51%  |
| 0.51-1.0        | 780       | 1179   | 24.03%  |
| 1.01-2.0        | 249       | 408    | 7.67%   |
| 3.01-4.0        | 73        | 153    | 2.25%   |
| 4.01-10.0       | 57        | 141    | 1.76%   |
| 2.01-3.0        | 55        | 80     | 1.69%   |
| More than 100.0 | 1         | 1      | 0.03%   |
| 20.01-50.0      | 1         | 1      | 0.03%   |
| 10.01-20.0      | 1         | 13     | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1003      | 27.12%  |
| 251-500        | 718       | 19.41%  |
| 501-1000       | 480       | 12.98%  |
| 1-20           | 390       | 10.54%  |
| 1001-2000      | 304       | 8.22%   |
| 51-100         | 240       | 6.49%   |
| More than 3000 | 204       | 5.52%   |
| 21-50          | 161       | 4.35%   |
| 2001-3000      | 105       | 2.84%   |
| Unknown        | 94        | 2.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1563      | 40.99%  |
| 21-50          | 552       | 14.48%  |
| 101-250        | 446       | 11.7%   |
| 51-100         | 406       | 10.65%  |
| 251-500        | 265       | 6.95%   |
| 501-1000       | 234       | 6.14%   |
| 1001-2000      | 115       | 3.02%   |
| Unknown        | 94        | 2.47%   |
| More than 3000 | 88        | 2.31%   |
| 2001-3000      | 48        | 1.26%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.86%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 4         | 4      | 1.86%   |
| WDC WD10EADS-22M2B0 1TB               | 3         | 3      | 1.4%    |
| Toshiba MQ01ABF050 500GB              | 3         | 3      | 1.4%    |
| Seagate ST9250410AS 250GB             | 3         | 3      | 1.4%    |
| Kingston SV300S37A120G 120GB SSD      | 3         | 4      | 1.4%    |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.4%    |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 1.4%    |
| Crucial CT128MX100SSD1 128GB          | 3         | 3      | 1.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.93%   |
| WDC WD60EFRX-68MYMN1 6TB              | 2         | 2      | 0.93%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.93%   |
| Toshiba MQ01ABD050 500GB              | 2         | 3      | 0.93%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 0.93%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.93%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.93%   |
| Seagate ST380011A 80GB                | 2         | 2      | 0.93%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.93%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 0.93%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 0.93%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.93%   |
| Samsung Electronics HM500JI 500GB     | 2         | 2      | 0.93%   |
| Samsung Electronics HD103UJ 1TB       | 2         | 2      | 0.93%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 0.93%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 3      | 0.93%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 0.93%   |
| Intel SSDSC2BW120A4 120GB             | 2         | 3      | 0.93%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 3      | 0.93%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 3      | 0.93%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.93%   |
| WDC WD800JD-00HKA0 80GB               | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-08HXZT3 752GB          | 1         | 1      | 0.47%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.47%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.47%   |
| WDC WD600UE-22HCT0 64GB               | 1         | 1      | 0.47%   |
| WDC WD5000HHTZ-04N21V0 500GB          | 1         | 1      | 0.47%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.47%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1      | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 0.47%   |
| WDC WD5000AAKS-75V0A0 500GB           | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 47        | 57     | 22.17%  |
| Seagate                     | 40        | 55     | 18.87%  |
| Samsung Electronics         | 15        | 16     | 7.08%   |
| Kingston                    | 14        | 16     | 6.6%    |
| Hitachi                     | 14        | 15     | 6.6%    |
| Intel                       | 13        | 18     | 6.13%   |
| Crucial                     | 12        | 18     | 5.66%   |
| Toshiba                     | 10        | 11     | 4.72%   |
| HGST                        | 10        | 11     | 4.72%   |
| SanDisk                     | 8         | 8      | 3.77%   |
| SK hynix                    | 5         | 5      | 2.36%   |
| Micron Technology           | 3         | 3      | 1.42%   |
| Maxtor                      | 3         | 5      | 1.42%   |
| Fujitsu                     | 3         | 3      | 1.42%   |
| OCZ                         | 2         | 2      | 0.94%   |
| LITEON                      | 2         | 4      | 0.94%   |
| Corsair                     | 2         | 3      | 0.94%   |
| A-DATA Technology           | 2         | 2      | 0.94%   |
| Patriot                     | 1         | 1      | 0.47%   |
| LITEONIT                    | 1         | 1      | 0.47%   |
| Kingston Technology Company | 1         | 1      | 0.47%   |
| GOODRAM                     | 1         | 1      | 0.47%   |
| C-Series                    | 1         | 1      | 0.47%   |
| Apple                       | 1         | 1      | 0.47%   |
| Anobit                      | 1         | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 45        | 55     | 34.09%  |
| Seagate             | 40        | 55     | 30.3%   |
| Hitachi             | 14        | 15     | 10.61%  |
| HGST                | 10        | 11     | 7.58%   |
| Toshiba             | 9         | 10     | 6.82%   |
| Samsung Electronics | 7         | 7      | 5.3%    |
| Maxtor              | 3         | 5      | 2.27%   |
| Fujitsu             | 3         | 3      | 2.27%   |
| Apple               | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 123       | 162    | 60.59%  |
| SSD  | 72        | 85     | 35.47%  |
| NVMe | 8         | 12     | 3.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22ZCT0 250GB       | 1         | 1      | 16.67%  |
| Toshiba MK5065GSXN 500GB          | 1         | 1      | 16.67%  |
| Seagate ST2000DL001-9VT156 2TB    | 1         | 1      | 16.67%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 16.67%  |
| Samsung Electronics HD161HJ 160GB | 1         | 1      | 16.67%  |
| Crucial M4-CT256M4SSD3 256GB      | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Seagate             | 1         | 1      | 16.67%  |
| Crucial             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2272      | 4731   | 61.21%  |
| Works    | 1240      | 2148   | 33.41%  |
| Malfunc  | 194       | 259    | 5.23%   |
| Failed   | 6         | 6      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2302      | 52.86%  |
| AMD                              | 549       | 12.61%  |
| Samsung Electronics              | 542       | 12.45%  |
| SanDisk                          | 138       | 3.17%   |
| SK hynix                         | 135       | 3.1%    |
| Kingston Technology Company      | 86        | 1.97%   |
| Toshiba America Info Systems     | 76        | 1.75%   |
| ASMedia Technology               | 64        | 1.47%   |
| Nvidia                           | 57        | 1.31%   |
| JMicron Technology               | 57        | 1.31%   |
| Phison Electronics               | 46        | 1.06%   |
| Marvell Technology Group         | 46        | 1.06%   |
| KIOXIA                           | 46        | 1.06%   |
| Micron Technology                | 30        | 0.69%   |
| Micron/Crucial Technology        | 19        | 0.44%   |
| Solid State Storage Technology   | 17        | 0.39%   |
| VIA Technologies                 | 15        | 0.34%   |
| Silicon Motion                   | 14        | 0.32%   |
| ADATA Technology                 | 14        | 0.32%   |
| Silicon Integrated Systems [SiS] | 13        | 0.3%    |
| Apple                            | 11        | 0.25%   |
| Lite-On Technology               | 10        | 0.23%   |
| Broadcom / LSI                   | 9         | 0.21%   |
| Silicon Image                    | 8         | 0.18%   |
| Seagate Technology               | 8         | 0.18%   |
| Realtek Semiconductor            | 8         | 0.18%   |
| LSI Logic / Symbios Logic        | 8         | 0.18%   |
| Union Memory (Shenzhen)          | 5         | 0.11%   |
| Hewlett-Packard                  | 4         | 0.09%   |
| Integrated Technology Express    | 3         | 0.07%   |
| Adaptec                          | 3         | 0.07%   |
| ULi Electronics                  | 2         | 0.05%   |
| Promise Technology               | 2         | 0.05%   |
| O2 Micro                         | 2         | 0.05%   |
| Transcend                        | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 349       | 6.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 280       | 5.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 165       | 3.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 162       | 3.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 155       | 3.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 142       | 2.81%   |
| Samsung NVMe SSD Controller 980                                                | 122       | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 106       | 2.1%    |
| AMD 400 Series Chipset SATA Controller                                         | 90        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 83        | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 82        | 1.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 70        | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 69        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 68        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 66        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 66        | 1.31%   |
| Intel SATA Controller [RAID mode]                                              | 64        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 62        | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 60        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 58        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 58        | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 56        | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 55        | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 55        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 52        | 1.03%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 51        | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 50        | 0.99%   |
| Intel Volume Management Device NVMe RAID Controller                            | 49        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 49        | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                | 48        | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 48        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 48        | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 47        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 47        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 44        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 44        | 0.87%   |
| Intel SSD 660P Series                                                          | 41        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 41        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 40        | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 39        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2368      | 53.49%  |
| NVMe | 1211      | 27.35%  |
| IDE  | 529       | 11.95%  |
| RAID | 306       | 6.91%   |
| SCSI | 7         | 0.16%   |
| SAS  | 6         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2745      | 78.54%  |
| AMD          | 700       | 20.03%  |
| ARM          | 47        | 1.34%   |
| CentaurHauls | 2         | 0.06%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 57        | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 42        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 1.11%   |
| ARM Processor                                 | 37        | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor             | 37        | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 31        | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 0.89%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 29        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 28        | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 24        | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 20        | 0.57%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 20        | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.54%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 19        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 18        | 0.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 0.51%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 18        | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 18        | 0.51%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 18        | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 17        | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 17        | 0.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 16        | 0.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 16        | 0.46%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 16        | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.43%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 14        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 773       | 22.09%  |
| Intel Core i7           | 707       | 20.21%  |
| Intel Core i3           | 271       | 7.75%   |
| Other                   | 198       | 5.66%   |
| AMD Ryzen 5             | 170       | 4.86%   |
| Intel Core 2 Duo        | 159       | 4.54%   |
| AMD Ryzen 7             | 156       | 4.46%   |
| Intel Celeron           | 120       | 3.43%   |
| Intel Pentium Silver    | 103       | 2.94%   |
| Intel Pentium           | 81        | 2.31%   |
| Intel Xeon              | 73        | 2.09%   |
| Intel Atom              | 72        | 2.06%   |
| Intel Pentium Dual-Core | 53        | 1.51%   |
| AMD Ryzen 9             | 44        | 1.26%   |
| Intel Core 2 Quad       | 41        | 1.17%   |
| AMD FX                  | 32        | 0.91%   |
| Intel Core i9           | 30        | 0.86%   |
| Intel Core 2            | 29        | 0.83%   |
| AMD A6                  | 25        | 0.71%   |
| Intel Pentium Dual      | 24        | 0.69%   |
| Intel Genuine           | 22        | 0.63%   |
| AMD Ryzen 7 PRO         | 21        | 0.6%    |
| AMD Ryzen 5 PRO         | 19        | 0.54%   |
| AMD Athlon 64 X2        | 19        | 0.54%   |
| AMD A8                  | 19        | 0.54%   |
| AMD Phenom II X4        | 16        | 0.46%   |
| AMD A4                  | 15        | 0.43%   |
| AMD A10                 | 15        | 0.43%   |
| AMD Ryzen 3             | 14        | 0.4%    |
| Intel Pentium D         | 13        | 0.37%   |
| Intel Pentium 4         | 13        | 0.37%   |
| AMD Athlon II X2        | 13        | 0.37%   |
| AMD E                   | 12        | 0.34%   |
| AMD E1                  | 10        | 0.29%   |
| ARM BCM                 | 9         | 0.26%   |
| AMD Athlon              | 8         | 0.23%   |
| AMD Ryzen Threadripper  | 7         | 0.2%    |
| AMD Athlon II X4        | 7         | 0.2%    |
| AMD E2                  | 6         | 0.17%   |
| Intel Core m3           | 5         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1393      | 39.79%  |
| 2       | 1329      | 37.96%  |
| 6       | 340       | 9.71%   |
| 8       | 239       | 6.83%   |
| 1       | 81        | 2.31%   |
| 12      | 52        | 1.49%   |
| 10      | 19        | 0.54%   |
| 16      | 15        | 0.43%   |
| 14      | 10        | 0.29%   |
| 3       | 9         | 0.26%   |
| 24      | 5         | 0.14%   |
| Unknown | 5         | 0.14%   |
| 64      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3463      | 99.08%  |
| 2       | 27        | 0.77%   |
| Unknown | 3         | 0.09%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2226      | 63.62%  |
| 1       | 1267      | 36.21%  |
| Unknown | 5         | 0.14%   |
| 16      | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3383      | 96.52%  |
| Unknown        | 91        | 2.6%    |
| 32-bit         | 28        | 0.8%    |
| 64-bit         | 3         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 824       | 22.8%   |
| 0x306a9    | 199       | 5.51%   |
| 0x206a7    | 188       | 5.2%    |
| 0x306c3    | 162       | 4.48%   |
| 0x1067a    | 135       | 3.74%   |
| 0x806ec    | 116       | 3.21%   |
| 0x906ea    | 104       | 2.88%   |
| 0x506e3    | 72        | 1.99%   |
| 0x406e3    | 72        | 1.99%   |
| 0x806ea    | 71        | 1.96%   |
| 0x806c1    | 71        | 1.96%   |
| 0x40651    | 68        | 1.88%   |
| 0x806e9    | 64        | 1.77%   |
| 0x20655    | 60        | 1.66%   |
| 0x906e9    | 59        | 1.63%   |
| 0x906c0    | 58        | 1.6%    |
| 0x6fd      | 56        | 1.55%   |
| 0x08701021 | 51        | 1.41%   |
| 0x306d4    | 46        | 1.27%   |
| 0x08600106 | 40        | 1.11%   |
| 0x30678    | 39        | 1.08%   |
| 0x706a8    | 38        | 1.05%   |
| 0x6fb      | 33        | 0.91%   |
| 0x010000c8 | 33        | 0.91%   |
| 0x0a50000c | 31        | 0.86%   |
| 0x08701013 | 31        | 0.86%   |
| 0x806eb    | 30        | 0.83%   |
| 0x10676    | 28        | 0.77%   |
| 0xa0652    | 26        | 0.72%   |
| 0x906ed    | 24        | 0.66%   |
| 0x706e5    | 24        | 0.66%   |
| 0x706a1    | 24        | 0.66%   |
| 0x106e5    | 24        | 0.66%   |
| 0x0800820d | 24        | 0.66%   |
| 0x20652    | 23        | 0.64%   |
| 0x08108102 | 23        | 0.64%   |
| 0x506c9    | 22        | 0.61%   |
| 0x406c4    | 22        | 0.61%   |
| 0x08108109 | 22        | 0.61%   |
| 0x6f6      | 21        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 615       | 17.58%  |
| Haswell          | 313       | 8.95%   |
| IvyBridge        | 252       | 7.2%    |
| SandyBridge      | 243       | 6.94%   |
| Penryn           | 196       | 5.6%    |
| Skylake          | 195       | 5.57%   |
| Zen 2            | 179       | 5.12%   |
| Core             | 145       | 4.14%   |
| Unknown          | 120       | 3.43%   |
| Westmere         | 117       | 3.34%   |
| Silvermont       | 107       | 3.06%   |
| Zen+             | 93        | 2.66%   |
| Zen 3            | 91        | 2.6%    |
| TigerLake        | 82        | 2.34%   |
| Broadwell        | 66        | 1.89%   |
| Goldmont plus    | 64        | 1.83%   |
| CometLake        | 61        | 1.74%   |
| K10              | 54        | 1.54%   |
| Tremont          | 51        | 1.46%   |
| Piledriver       | 51        | 1.46%   |
| Nehalem          | 50        | 1.43%   |
| Zen              | 49        | 1.4%    |
| IceLake          | 43        | 1.23%   |
| K8 Hammer        | 35        | 1%      |
| NetBurst         | 30        | 0.86%   |
| Goldmont         | 28        | 0.8%    |
| Alderlake Hybrid | 24        | 0.69%   |
| Excavator        | 22        | 0.63%   |
| Bobcat           | 20        | 0.57%   |
| Bonnell          | 19        | 0.54%   |
| K10 Llano        | 17        | 0.49%   |
| Jaguar           | 16        | 0.46%   |
| P6               | 15        | 0.43%   |
| Steamroller      | 11        | 0.31%   |
| Puma             | 9         | 0.26%   |
| K8 & K10 hybrid  | 8         | 0.23%   |
| Bulldozer        | 7         | 0.2%    |
| CannonLake       | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2058      | 50.53%  |
| Nvidia                           | 1143      | 28.06%  |
| AMD                              | 834       | 20.48%  |
| Matrox Electronics Systems       | 15        | 0.37%   |
| ASPEED Technology                | 8         | 0.2%    |
| VIA Technologies                 | 7         | 0.17%   |
| Silicon Integrated Systems [SiS] | 7         | 0.17%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 178       | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 149       | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 108       | 2.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 2.51%   |
| Intel UHD Graphics 620                                                                   | 78        | 1.87%   |
| AMD Renoir                                                                               | 76        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 75        | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 73        | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 1.75%   |
| Intel HD Graphics 620                                                                    | 68        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 67        | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 63        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 61        | 1.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 61        | 1.46%   |
| Intel JasperLake [UHD Graphics]                                                          | 60        | 1.44%   |
| Intel HD Graphics 630                                                                    | 59        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 57        | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 56        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 55        | 1.32%   |
| Intel HD Graphics 530                                                                    | 54        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 50        | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.17%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 46        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 1.01%   |
| Intel HD Graphics 5500                                                                   | 40        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 36        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 0.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 30        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 29        | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 29        | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 26        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 24        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 21        | 0.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1494      | 42.41%  |
| 1 x AMD                  | 689       | 19.56%  |
| 1 x Nvidia               | 645       | 18.31%  |
| Intel + Nvidia           | 448       | 12.72%  |
| Intel + AMD              | 67        | 1.9%    |
| Other                    | 52        | 1.48%   |
| 2 x AMD                  | 40        | 1.14%   |
| AMD + Nvidia             | 36        | 1.02%   |
| 1 x Matrox               | 12        | 0.34%   |
| 2 x Nvidia               | 9         | 0.26%   |
| 1 x VIA                  | 7         | 0.2%    |
| 1 x SiS                  | 7         | 0.2%    |
| 2 x Intel                | 4         | 0.11%   |
| Nvidia + ASPEED          | 4         | 0.11%   |
| 1 x ASPEED               | 3         | 0.09%   |
| Nvidia + Matrox          | 2         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.06%   |
| AMD + Matrox             | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2781      | 78.16%  |
| Proprietary | 606       | 17.03%  |
| Unknown     | 171       | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2062      | 57.33%  |
| 1.01-2.0   | 394       | 10.95%  |
| 0.01-0.5   | 364       | 10.12%  |
| 0.51-1.0   | 268       | 7.45%   |
| 3.01-4.0   | 237       | 6.59%   |
| 7.01-8.0   | 149       | 4.14%   |
| 5.01-6.0   | 72        | 2%      |
| 8.01-16.0  | 26        | 0.72%   |
| 2.01-3.0   | 24        | 0.67%   |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 510       | 13.18%  |
| Samsung Electronics     | 485       | 12.53%  |
| LG Display              | 322       | 8.32%   |
| BOE                     | 293       | 7.57%   |
| Chimei Innolux          | 257       | 6.64%   |
| Dell                    | 215       | 5.56%   |
| Goldstar                | 173       | 4.47%   |
| Philips                 | 172       | 4.44%   |
| Iiyama                  | 171       | 4.42%   |
| Hewlett-Packard         | 133       | 3.44%   |
| Acer                    | 119       | 3.07%   |
| Apple                   | 93        | 2.4%    |
| Sharp                   | 86        | 2.22%   |
| BenQ                    | 79        | 2.04%   |
| AOC                     | 78        | 2.02%   |
| Ancor Communications    | 57        | 1.47%   |
| Chi Mei Optoelectronics | 55        | 1.42%   |
| Lenovo                  | 45        | 1.16%   |
| LG Philips              | 33        | 0.85%   |
| Sony                    | 30        | 0.78%   |
| Medion                  | 30        | 0.78%   |
| Idek Iiyama             | 28        | 0.72%   |
| InfoVision              | 23        | 0.59%   |
| LG Electronics          | 22        | 0.57%   |
| Eizo                    | 19        | 0.49%   |
| PANDA                   | 16        | 0.41%   |
| Unknown                 | 14        | 0.36%   |
| MSI                     | 14        | 0.36%   |
| CSO                     | 14        | 0.36%   |
| ASUSTek Computer        | 14        | 0.36%   |
| Panasonic               | 12        | 0.31%   |
| Fujitsu Siemens         | 12        | 0.31%   |
| Packard Bell            | 11        | 0.28%   |
| ViewSonic               | 10        | 0.26%   |
| Vestel Elektronik       | 9         | 0.23%   |
| Toshiba                 | 9         | 0.23%   |
| NEC Computers           | 9         | 0.23%   |
| HannStar                | 9         | 0.23%   |
| Valve                   | 8         | 0.21%   |
| LGD                     | 8         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                      | 33        | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 25        | 0.62%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch            | 22        | 0.55%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch             | 18        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 17        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 15        | 0.37%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 14        | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 14        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 14        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 13        | 0.32%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                      | 13        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 12        | 0.3%    |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch             | 12        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 11        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 10        | 0.25%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 9         | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 9         | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 8         | 0.2%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 8         | 0.2%    |
| LGD LCD Monitor 1920x1080                                                 | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 8         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 8         | 0.2%    |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                      | 8         | 0.2%    |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                     | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 7         | 0.17%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 7         | 0.17%   |
| Iiyama PLT1931 IVM483F 1280x1024 376x301mm 19.0-inch                      | 7         | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 7         | 0.17%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                     | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 7         | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch            | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 7         | 0.17%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                         | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1575      | 42.19%  |
| 1366x768 (WXGA)    | 539       | 14.44%  |
| 3840x2160 (4K)     | 232       | 6.21%   |
| 2560x1440 (QHD)    | 211       | 5.65%   |
| 1600x900 (HD+)     | 162       | 4.34%   |
| 1280x1024 (SXGA)   | 140       | 3.75%   |
| 1680x1050 (WSXGA+) | 135       | 3.62%   |
| 1280x800 (WXGA)    | 104       | 2.79%   |
| 1920x1200 (WUXGA)  | 98        | 2.63%   |
| 1440x900 (WXGA+)   | 97        | 2.6%    |
| 3440x1440          | 56        | 1.5%    |
| Unknown            | 53        | 1.42%   |
| 2560x1080          | 41        | 1.1%    |
| 2560x1600          | 30        | 0.8%    |
| 1360x768           | 28        | 0.75%   |
| 2880x1800          | 24        | 0.64%   |
| 3840x2400          | 21        | 0.56%   |
| 3840x1080          | 18        | 0.48%   |
| 1024x768 (XGA)     | 18        | 0.48%   |
| 1920x540           | 13        | 0.35%   |
| 800x1280           | 12        | 0.32%   |
| 1280x720 (HD)      | 9         | 0.24%   |
| 2736x1824          | 8         | 0.21%   |
| 1600x1200          | 8         | 0.21%   |
| 2160x1440          | 7         | 0.19%   |
| 3600x1080          | 5         | 0.13%   |
| 3200x1800 (QHD+)   | 5         | 0.13%   |
| 1400x1050          | 5         | 0.13%   |
| 7680x2160          | 4         | 0.11%   |
| 5760x1080          | 4         | 0.11%   |
| 3840x1600          | 4         | 0.11%   |
| 3840x1200          | 4         | 0.11%   |
| 3456x2160          | 4         | 0.11%   |
| 3000x2000          | 4         | 0.11%   |
| 2048x1152          | 4         | 0.11%   |
| 1280x960           | 4         | 0.11%   |
| 1024x600           | 4         | 0.11%   |
| 3072x1920          | 3         | 0.08%   |
| 2256x1504          | 3         | 0.08%   |
| 5760x2160          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 860       | 22.22%  |
| 13      | 323       | 8.34%   |
| 17      | 313       | 8.09%   |
| 27      | 278       | 7.18%   |
| 24      | 277       | 7.16%   |
| 23      | 239       | 6.17%   |
| Unknown | 237       | 6.12%   |
| 14      | 228       | 5.89%   |
| 21      | 178       | 4.6%    |
| 11      | 138       | 3.56%   |
| 19      | 109       | 2.82%   |
| 22      | 85        | 2.2%    |
| 12      | 84        | 2.17%   |
| 34      | 78        | 2.01%   |
| 31      | 64        | 1.65%   |
| 20      | 54        | 1.39%   |
| 18      | 38        | 0.98%   |
| 25      | 32        | 0.83%   |
| 84      | 29        | 0.75%   |
| 16      | 23        | 0.59%   |
| 72      | 22        | 0.57%   |
| 40      | 22        | 0.57%   |
| 54      | 15        | 0.39%   |
| 10      | 14        | 0.36%   |
| 65      | 13        | 0.34%   |
| 32      | 10        | 0.26%   |
| 26      | 9         | 0.23%   |
| 33      | 8         | 0.21%   |
| 28      | 8         | 0.21%   |
| 29      | 7         | 0.18%   |
| 46      | 6         | 0.15%   |
| 37      | 6         | 0.15%   |
| 7       | 6         | 0.15%   |
| 58      | 5         | 0.13%   |
| 35      | 5         | 0.13%   |
| 57      | 4         | 0.1%    |
| 52      | 4         | 0.1%    |
| 47      | 4         | 0.1%    |
| 43      | 4         | 0.1%    |
| 42      | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1250      | 32.87%  |
| 501-600     | 759       | 19.96%  |
| 201-300     | 449       | 11.81%  |
| 401-500     | 380       | 9.99%   |
| 351-400     | 354       | 9.31%   |
| Unknown     | 237       | 6.23%   |
| 601-700     | 106       | 2.79%   |
| 701-800     | 95        | 2.5%    |
| 1001-1500   | 61        | 1.6%    |
| 1501-2000   | 53        | 1.39%   |
| 801-900     | 40        | 1.05%   |
| 901-1000    | 11        | 0.29%   |
| 1-100       | 6         | 0.16%   |
| 101-200     | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2470      | 70.41%  |
| 16/10   | 510       | 14.54%  |
| Unknown | 193       | 5.5%    |
| 5/4     | 132       | 3.76%   |
| 21/9    | 94        | 2.68%   |
| 4/3     | 41        | 1.17%   |
| 3/2     | 38        | 1.08%   |
| 0.62    | 8         | 0.23%   |
| 6/5     | 6         | 0.17%   |
| 32/9    | 6         | 0.17%   |
| 0.67    | 6         | 0.17%   |
| 3.40    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.45    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 854       | 22.23%  |
| 201-250        | 614       | 15.99%  |
| 81-90          | 371       | 9.66%   |
| 301-350        | 286       | 7.45%   |
| Unknown        | 237       | 6.17%   |
| 151-200        | 221       | 5.75%   |
| 121-130        | 201       | 5.23%   |
| 71-80          | 187       | 4.87%   |
| 351-500        | 179       | 4.66%   |
| 51-60          | 140       | 3.64%   |
| 251-300        | 133       | 3.46%   |
| More than 1000 | 101       | 2.63%   |
| 141-150        | 90        | 2.34%   |
| 61-70          | 73        | 1.9%    |
| 501-1000       | 59        | 1.54%   |
| 131-140        | 44        | 1.15%   |
| 111-120        | 26        | 0.68%   |
| 41-50          | 13        | 0.34%   |
| 1-40           | 8         | 0.21%   |
| 91-100         | 4         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1196      | 32.03%  |
| 121-160       | 1045      | 27.99%  |
| 101-120       | 803       | 21.51%  |
| Unknown       | 237       | 6.35%   |
| 161-240       | 233       | 6.24%   |
| More than 240 | 130       | 3.48%   |
| 1-50          | 90        | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2786      | 77.65%  |
| 2     | 574       | 16%     |
| 0     | 163       | 4.54%   |
| 3     | 60        | 1.67%   |
| 4     | 4         | 0.11%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1852      | 35.93%  |
| Realtek Semiconductor                 | 1689      | 32.77%  |
| Qualcomm Atheros                      | 516       | 10.01%  |
| Broadcom                              | 321       | 6.23%   |
| Broadcom Limited                      | 79        | 1.53%   |
| Marvell Technology Group              | 69        | 1.34%   |
| TP-Link                               | 65        | 1.26%   |
| Ralink Technology                     | 59        | 1.14%   |
| Ralink                                | 54        | 1.05%   |
| Nvidia                                | 45        | 0.87%   |
| MediaTek                              | 39        | 0.76%   |
| ASIX Electronics                      | 28        | 0.54%   |
| Dell                                  | 27        | 0.52%   |
| DisplayLink                           | 25        | 0.49%   |
| Hewlett-Packard                       | 24        | 0.47%   |
| Sitecom Europe                        | 15        | 0.29%   |
| Microsoft                             | 15        | 0.29%   |
| Huawei Technologies                   | 13        | 0.25%   |
| NetGear                               | 12        | 0.23%   |
| JMicron Technology                    | 12        | 0.23%   |
| Ericsson Business Mobile Networks     | 12        | 0.23%   |
| Sierra Wireless                       | 11        | 0.21%   |
| IMC Networks                          | 11        | 0.21%   |
| ASUSTek Computer                      | 11        | 0.21%   |
| Samsung Electronics                   | 10        | 0.19%   |
| Silicon Integrated Systems [SiS]      | 9         | 0.17%   |
| Lenovo                                | 8         | 0.16%   |
| Qualcomm                              | 7         | 0.14%   |
| VIA Technologies                      | 6         | 0.12%   |
| Gemtek                                | 6         | 0.12%   |
| Mellanox Technologies                 | 5         | 0.1%    |
| D-Link                                | 5         | 0.1%    |
| Aquantia                              | 5         | 0.1%    |
| Xiaomi                                | 4         | 0.08%   |
| Microchip Technology                  | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.08%   |
| ULi Electronics                       | 3         | 0.06%   |
| U-Blox                                | 3         | 0.06%   |
| Standard Microsystems                 | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1223      | 20.36%  |
| Intel Wi-Fi 6 AX200                                               | 186       | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148       | 2.46%   |
| Intel Wireless 8265 / 8275                                        | 147       | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 145       | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 120       | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 105       | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 87        | 1.45%   |
| Intel Wireless 7265                                               | 85        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 71        | 1.18%   |
| Intel Wi-Fi 6 AX201                                               | 66        | 1.1%    |
| Intel Wireless 7260                                               | 65        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 61        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 59        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 58        | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 57        | 0.95%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 57        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56        | 0.93%   |
| Intel Wireless 8260                                               | 55        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 53        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 47        | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 47        | 0.78%   |
| Intel Wireless 3165                                               | 44        | 0.73%   |
| Intel Wireless-AC 9260                                            | 43        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 42        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 42        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 41        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 41        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 38        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 35        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 35        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 35        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 30        | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.48%   |
| Intel Wireless 3160                                               | 29        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1411      | 51.93%  |
| Qualcomm Atheros                      | 410       | 15.09%  |
| Realtek Semiconductor                 | 317       | 11.67%  |
| Broadcom                              | 196       | 7.21%   |
| Ralink Technology                     | 59        | 2.17%   |
| TP-Link                               | 58        | 2.13%   |
| Ralink                                | 54        | 1.99%   |
| Broadcom Limited                      | 39        | 1.44%   |
| MediaTek                              | 27        | 0.99%   |
| Sitecom Europe                        | 15        | 0.55%   |
| Microsoft                             | 13        | 0.48%   |
| NetGear                               | 12        | 0.44%   |
| Marvell Technology Group              | 12        | 0.44%   |
| Sierra Wireless                       | 11        | 0.4%    |
| IMC Networks                          | 11        | 0.4%    |
| Dell                                  | 11        | 0.4%    |
| ASUSTek Computer                      | 11        | 0.4%    |
| Gemtek                                | 6         | 0.22%   |
| Qualcomm                              | 5         | 0.18%   |
| D-Link                                | 5         | 0.18%   |
| Hewlett-Packard                       | 4         | 0.15%   |
| Belkin Components                     | 4         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.15%   |
| Qualcomm Atheros Communications       | 3         | 0.11%   |
| Linksys                               | 3         | 0.11%   |
| FIBOCOM                               | 3         | 0.11%   |
| Edimax Technology                     | 3         | 0.11%   |
| Senao                                 | 2         | 0.07%   |
| Sagem                                 | 2         | 0.07%   |
| Wilocity                              | 1         | 0.04%   |
| Tenda                                 | 1         | 0.04%   |
| Samsung Electronics                   | 1         | 0.04%   |
| CyberTAN Technology                   | 1         | 0.04%   |
| Cinterion                             | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 186       | 6.82%   |
| Intel Wireless 8265 / 8275                                              | 147       | 5.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 105       | 3.85%   |
| Intel Wireless 7265                                                     | 85        | 3.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 71        | 2.6%    |
| Intel Wi-Fi 6 AX201                                                     | 66        | 2.42%   |
| Intel Wireless 7260                                                     | 65        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 59        | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 58        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 57        | 2.09%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 57        | 2.09%   |
| Intel Wireless 8260                                                     | 55        | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 53        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 47        | 1.72%   |
| Intel Wireless 3165                                                     | 44        | 1.61%   |
| Intel Wireless-AC 9260                                                  | 43        | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 42        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 41        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 35        | 1.28%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 1.28%   |
| Intel Wireless 3160                                                     | 29        | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 29        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 25        | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 25        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 22        | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 22        | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 21        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 20        | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 19        | 0.7%    |
| Intel Centrino Advanced-N 6235                                          | 19        | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 19        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1562      | 50%     |
| Intel                                  | 906       | 29%     |
| Broadcom                               | 171       | 5.47%   |
| Qualcomm Atheros                       | 167       | 5.35%   |
| Marvell Technology Group               | 57        | 1.82%   |
| Nvidia                                 | 44        | 1.41%   |
| Broadcom Limited                       | 40        | 1.28%   |
| ASIX Electronics                       | 28        | 0.9%    |
| DisplayLink                            | 25        | 0.8%    |
| JMicron Technology                     | 12        | 0.38%   |
| MediaTek                               | 11        | 0.35%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.29%   |
| Samsung Electronics                    | 9         | 0.29%   |
| Huawei Technologies                    | 9         | 0.29%   |
| Lenovo                                 | 8         | 0.26%   |
| TP-Link                                | 7         | 0.22%   |
| VIA Technologies                       | 6         | 0.19%   |
| Hewlett-Packard                        | 6         | 0.19%   |
| Aquantia                               | 5         | 0.16%   |
| Xiaomi                                 | 4         | 0.13%   |
| Mellanox Technologies                  | 4         | 0.13%   |
| Standard Microsystems                  | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 2         | 0.06%   |
| ULi Electronics                        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Qualcomm                               | 2         | 0.06%   |
| Motorola PCS                           | 2         | 0.06%   |
| MosChip Semiconductor                  | 2         | 0.06%   |
| Microsoft                              | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| ICS Advent                             | 2         | 0.06%   |
| Accton Technology                      | 2         | 0.06%   |
| 3Com                                   | 2         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Jolla Oy                               | 1         | 0.03%   |
| Google                                 | 1         | 0.03%   |
| Emulex                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1223      | 38.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 148       | 4.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 145       | 4.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 120       | 3.75%   |
| Intel I211 Gigabit Network Connection                             | 87        | 2.72%   |
| Intel Ethernet Connection (2) I219-V                              | 61        | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 56        | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 1.19%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 30        | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 26        | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 25        | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 23        | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 21        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 15        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 15        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 13        | 0.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 13        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2941      | 52.61%  |
| WiFi     | 2574      | 46.05%  |
| Modem    | 67        | 1.2%    |
| Unknown  | 8         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1973      | 53.82%  |
| Ethernet | 1692      | 46.15%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1836      | 52.38%  |
| 1     | 1491      | 42.54%  |
| 0     | 89        | 2.54%   |
| 3     | 63        | 1.8%    |
| 4     | 15        | 0.43%   |
| 5     | 4         | 0.11%   |
| 7     | 3         | 0.09%   |
| 6     | 3         | 0.09%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2908      | 81.23%  |
| Yes  | 672       | 18.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1121      | 52.9%   |
| Cambridge Silicon Radio         | 173       | 8.16%   |
| Realtek Semiconductor           | 138       | 6.51%   |
| Qualcomm Atheros Communications | 119       | 5.62%   |
| Broadcom                        | 96        | 4.53%   |
| Apple                           | 94        | 4.44%   |
| IMC Networks                    | 73        | 3.45%   |
| Lite-On Technology              | 61        | 2.88%   |
| Foxconn / Hon Hai               | 51        | 2.41%   |
| Hewlett-Packard                 | 41        | 1.93%   |
| ASUSTek Computer                | 37        | 1.75%   |
| Dell                            | 35        | 1.65%   |
| Toshiba                         | 19        | 0.9%    |
| Marvell Semiconductor           | 12        | 0.57%   |
| Ralink                          | 10        | 0.47%   |
| MediaTek                        | 10        | 0.47%   |
| Realtek                         | 5         | 0.24%   |
| TP-Link                         | 4         | 0.19%   |
| Alps Electric                   | 4         | 0.19%   |
| Ralink Technology               | 3         | 0.14%   |
| Sitecom Europe                  | 2         | 0.09%   |
| Micro Star International        | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Foxconn International           | 2         | 0.09%   |
| USI                             | 1         | 0.05%   |
| Roper                           | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 403       | 19%     |
| Intel AX201 Bluetooth                               | 205       | 9.67%   |
| Intel AX200 Bluetooth                               | 178       | 8.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 173       | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 169       | 7.97%   |
| Realtek Bluetooth Radio                             | 77        | 3.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 43        | 2.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 41        | 1.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 41        | 1.93%   |
| Apple Bluetooth Host Controller                     | 40        | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 30        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.32%   |
| Lite-On Bluetooth Device                            | 27        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 24        | 1.13%   |
| Intel AX210 Bluetooth                               | 23        | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 0.94%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.9%    |
| Intel Bluetooth Device                              | 18        | 0.85%   |
| IMC Networks Bluetooth Device                       | 18        | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 14        | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 14        | 0.66%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.57%   |
| IMC Networks Wireless_Device                        | 11        | 0.52%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.47%   |
| Marvell Bluetooth and Wireless LAN Composite        | 10        | 0.47%   |
| Apple Bluetooth HCI                                 | 10        | 0.47%   |
| MediaTek Wireless_Device                            | 9         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2578      | 53.8%   |
| AMD                              | 891       | 18.59%  |
| Nvidia                           | 806       | 16.82%  |
| C-Media Electronics              | 69        | 1.44%   |
| Logitech                         | 39        | 0.81%   |
| Realtek Semiconductor            | 34        | 0.71%   |
| Creative Labs                    | 31        | 0.65%   |
| GN Netcom                        | 24        | 0.5%    |
| Texas Instruments                | 21        | 0.44%   |
| Focusrite-Novation               | 17        | 0.35%   |
| Creative Technology              | 14        | 0.29%   |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| Plantronics                      | 12        | 0.25%   |
| SteelSeries ApS                  | 11        | 0.23%   |
| JMTek                            | 11        | 0.23%   |
| BEHRINGER International          | 11        | 0.23%   |
| VIA Technologies                 | 10        | 0.21%   |
| Kingston Technology              | 10        | 0.21%   |
| Corsair                          | 10        | 0.21%   |
| Hewlett-Packard                  | 8         | 0.17%   |
| Apple                            | 8         | 0.17%   |
| Sony                             | 7         | 0.15%   |
| GYROCOM C&C                      | 7         | 0.15%   |
| ASUSTek Computer                 | 7         | 0.15%   |
| RODE Microphones                 | 6         | 0.13%   |
| Razer USA                        | 6         | 0.13%   |
| DSEA A/S                         | 6         | 0.13%   |
| Yamaha                           | 5         | 0.1%    |
| Lenovo                           | 5         | 0.1%    |
| Generalplus Technology           | 5         | 0.1%    |
| XMOS                             | 4         | 0.08%   |
| SAVITECH                         | 4         | 0.08%   |
| Native Instruments               | 4         | 0.08%   |
| Cambridge Silicon Radio          | 4         | 0.08%   |
| Tenx Technology                  | 3         | 0.06%   |
| Sennheiser Communications        | 3         | 0.06%   |
| Samson Technologies              | 3         | 0.06%   |
| No brand                         | 3         | 0.06%   |
| M-Audio                          | 3         | 0.06%   |
| Guillemot                        | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 253       | 4.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 251       | 4.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 223       | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 221       | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 184       | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 152       | 2.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 140       | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 130       | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 130       | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 125       | 2.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 121       | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 116       | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 106       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 98        | 1.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 93        | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 82        | 1.47%   |
| AMD FCH Azalia Controller                                                  | 82        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 79        | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 75        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 75        | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 71        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 67        | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 65        | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 64        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 62        | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 62        | 1.11%   |
| Nvidia High Definition Audio Controller                                    | 61        | 1.09%   |
| Intel Jasper Lake HD Audio                                                 | 60        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 60        | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 59        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 58        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 56        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 51        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 51        | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 50        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 48        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 46        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                  | 45        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 44        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 43        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 435       | 22.48%  |
| Samsung Electronics | 380       | 19.64%  |
| Kingston            | 216       | 11.16%  |
| Micron Technology   | 205       | 10.59%  |
| Corsair             | 160       | 8.27%   |
| Unknown             | 150       | 7.75%   |
| Crucial             | 123       | 6.36%   |
| G.Skill             | 54        | 2.79%   |
| A-DATA Technology   | 32        | 1.65%   |
| Ramaxel Technology  | 27        | 1.4%    |
| Nanya Technology    | 26        | 1.34%   |
| Elpida              | 19        | 0.98%   |
| Transcend           | 11        | 0.57%   |
| Unknown             | 11        | 0.57%   |
| Unknown (ABCD)      | 7         | 0.36%   |
| Team                | 7         | 0.36%   |
| Qimonda             | 5         | 0.26%   |
| GOODRAM             | 5         | 0.26%   |
| ASint Technology    | 5         | 0.26%   |
| 48spaces            | 4         | 0.21%   |
| Wilk                | 3         | 0.16%   |
| GeIL                | 3         | 0.16%   |
| Axiom               | 3         | 0.16%   |
| Toshiba             | 2         | 0.1%    |
| TakeMS              | 2         | 0.1%    |
| Patriot             | 2         | 0.1%    |
| Goldkey             | 2         | 0.1%    |
| Atermiter           | 2         | 0.1%    |
| AMD                 | 2         | 0.1%    |
| A-DA                | 2         | 0.1%    |
| A Force             | 2         | 0.1%    |
| ZIFEI               | 1         | 0.05%   |
| zApacer             | 1         | 0.05%   |
| Unknown (AD8A)      | 1         | 0.05%   |
| Unknown (0x873E)    | 1         | 0.05%   |
| Unknown (08C8)      | 1         | 0.05%   |
| Timetec             | 1         | 0.05%   |
| Smart               | 1         | 0.05%   |
| SHARETRONIC         | 1         | 0.05%   |
| Sesame              | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s | 43        | 2.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 30        | 1.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 24        | 1.17%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 19        | 0.92%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s         | 17        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 16        | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 14        | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 13        | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 13        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 12        | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 12        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 11        | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 11        | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 11        | 0.53%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 11        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 11        | 0.53%   |
| Unknown                                                        | 11        | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s      | 10        | 0.49%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 10        | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 10        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 10        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 9         | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 9         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 8         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 8         | 0.39%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 8         | 0.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 8         | 0.39%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 8         | 0.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 7         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 7         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 7         | 0.34%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 7         | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 7         | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 7         | 0.34%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s          | 7         | 0.34%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s          | 7         | 0.34%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 6         | 0.29%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                    | 6         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 828       | 48.53%  |
| DDR3    | 524       | 30.72%  |
| LPDDR4  | 109       | 6.39%   |
| DDR2    | 72        | 4.22%   |
| LPDDR3  | 57        | 3.34%   |
| SDRAM   | 51        | 2.99%   |
| Unknown | 27        | 1.58%   |
| DDR5    | 15        | 0.88%   |
| DDR     | 12        | 0.7%    |
| LPDDR5  | 7         | 0.41%   |
| DRAM    | 3         | 0.18%   |
| EEPROM  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 991       | 58.23%  |
| DIMM         | 516       | 30.32%  |
| Row Of Chips | 177       | 10.4%   |
| Chip         | 8         | 0.47%   |
| Unknown      | 8         | 0.47%   |
| RIMM         | 1         | 0.06%   |
| FB-DIMM      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 721       | 39.06%  |
| 4096  | 486       | 26.33%  |
| 16384 | 274       | 14.84%  |
| 2048  | 231       | 12.51%  |
| 1024  | 71        | 3.85%   |
| 32768 | 51        | 2.76%   |
| 512   | 9         | 0.49%   |
| 256   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 1     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 318       | 17.55%  |
| 2667    | 276       | 15.23%  |
| 3200    | 253       | 13.96%  |
| 2400    | 141       | 7.78%   |
| 1333    | 118       | 6.51%   |
| 2133    | 100       | 5.52%   |
| 4267    | 82        | 4.53%   |
| 1334    | 55        | 3.04%   |
| 3600    | 53        | 2.92%   |
| 1867    | 47        | 2.59%   |
| 800     | 42        | 2.32%   |
| 667     | 41        | 2.26%   |
| Unknown | 30        | 1.66%   |
| 1066    | 17        | 0.94%   |
| 4800    | 14        | 0.77%   |
| 3400    | 14        | 0.77%   |
| 3000    | 14        | 0.77%   |
| 2933    | 14        | 0.77%   |
| 3466    | 13        | 0.72%   |
| 1067    | 13        | 0.72%   |
| 3266    | 12        | 0.66%   |
| 1866    | 12        | 0.66%   |
| 8400    | 11        | 0.61%   |
| 2048    | 10        | 0.55%   |
| 4199    | 8         | 0.44%   |
| 3866    | 8         | 0.44%   |
| 3800    | 8         | 0.44%   |
| 400     | 8         | 0.44%   |
| 6400    | 7         | 0.39%   |
| 1639    | 7         | 0.39%   |
| 4266    | 6         | 0.33%   |
| 3733    | 5         | 0.28%   |
| 2800    | 5         | 0.28%   |
| 533     | 5         | 0.28%   |
| 2666    | 4         | 0.22%   |
| 1800    | 4         | 0.22%   |
| 49926   | 3         | 0.17%   |
| 3333    | 3         | 0.17%   |
| 333     | 3         | 0.17%   |
| 6000    | 2         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 31.58%  |
| Brother Industries  | 15        | 19.74%  |
| Canon               | 14        | 18.42%  |
| Samsung Electronics | 9         | 11.84%  |
| Seiko Epson         | 5         | 6.58%   |
| Dymo-CoStar         | 5         | 6.58%   |
| Citizen             | 3         | 3.95%   |
| Prolific Technology | 1         | 1.32%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer           | 3         | 3.95%   |
| HP Deskjet 2540 series                       | 3         | 3.95%   |
| Dymo-CoStar LabelWriter 450                  | 3         | 3.95%   |
| Citizen Thermal Receipt Printer [CT-E351]    | 3         | 3.95%   |
| Samsung SCX-4600 Series                      | 2         | 2.63%   |
| Samsung ML-1640 Series Laser Printer         | 2         | 2.63%   |
| HP ENVY 5000 series                          | 2         | 2.63%   |
| Canon TS3100 series                          | 2         | 2.63%   |
| Canon PIXMA MX920 Series                     | 2         | 2.63%   |
| Canon MG5600 series                          | 2         | 2.63%   |
| Brother Printer                              | 2         | 2.63%   |
| Brother HL-2030 Laser Printer                | 2         | 2.63%   |
| Seiko Epson XP-200 Series                    | 1         | 1.32%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 1.32%   |
| Seiko Epson Printer                          | 1         | 1.32%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.32%   |
| Seiko Epson ET-2720 Series                   | 1         | 1.32%   |
| Samsung SCX-4300 Series                      | 1         | 1.32%   |
| Samsung ML-2240 Series                       | 1         | 1.32%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.32%   |
| Samsung C48x Series                          | 1         | 1.32%   |
| Samsung C43x Series                          | 1         | 1.32%   |
| Prolific PL2305 Parallel Port                | 1         | 1.32%   |
| HP Printing Support                          | 1         | 1.32%   |
| HP OfficeJet Pro 8020 series                 | 1         | 1.32%   |
| HP OfficeJet 6950                            | 1         | 1.32%   |
| HP OfficeJet 3830 series                     | 1         | 1.32%   |
| HP LaserJet Professional P1102w              | 1         | 1.32%   |
| HP LaserJet P1005                            | 1         | 1.32%   |
| HP LaserJet 1320                             | 1         | 1.32%   |
| HP Laser 107w                                | 1         | 1.32%   |
| HP DeskJet F2100 Printer series              | 1         | 1.32%   |
| HP Deskjet D1500 series                      | 1         | 1.32%   |
| HP DeskJet 916C                              | 1         | 1.32%   |
| HP DeskJet 6940 series                       | 1         | 1.32%   |
| HP DeskJet 3630 series                       | 1         | 1.32%   |
| HP DeskJet 2700 series                       | 1         | 1.32%   |
| HP designjet 30/130 series                   | 1         | 1.32%   |
| HP ColorLaserJet M253-M254                   | 1         | 1.32%   |
| Dymo-CoStar LabelWriter 400                  | 1         | 1.32%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 23        | 63.89%  |
| Seiko Epson     | 7         | 19.44%  |
| Mustek Systems  | 3         | 8.33%   |
| Hewlett-Packard | 2         | 5.56%   |
| Plustek         | 1         | 2.78%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                       | 4         | 10.81%  |
| Canon CanoScan LiDE 210                       | 4         | 10.81%  |
| Mustek Systems ScanExpress 1200 UB            | 3         | 8.11%   |
| Seiko Epson Scanner                           | 2         | 5.41%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 2         | 5.41%   |
| Seiko Epson GT-X770 [Perfection V500]         | 2         | 5.41%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 5.41%   |
| Canon CanoScan N650U/N656U                    | 2         | 5.41%   |
| Canon CanoScan LiDE 200                       | 2         | 5.41%   |
| Canon CanoScan LiDE 120                       | 2         | 5.41%   |
| Canon CanoScan LiDE 110                       | 2         | 5.41%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 2.7%    |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 2.7%    |
| Plustek 600dpi USB Scanner                    | 1         | 2.7%    |
| HP ScanJet 5590                               | 1         | 2.7%    |
| HP ScanJet 3300c                              | 1         | 2.7%    |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 2.7%    |
| Canon CanoScan LiDE 60                        | 1         | 2.7%    |
| Canon CanoScan FB630U                         | 1         | 2.7%    |
| Canon CanoScan 9000F Mark II                  | 1         | 2.7%    |
| Canon CanoScan 5600F                          | 1         | 2.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 448       | 21.05%  |
| Microdia                               | 249       | 11.7%   |
| Realtek Semiconductor                  | 211       | 9.92%   |
| IMC Networks                           | 167       | 7.85%   |
| Sunplus Innovation Technology          | 152       | 7.14%   |
| Acer                                   | 136       | 6.39%   |
| Logitech                               | 132       | 6.2%    |
| Cheng Uei Precision Industry (Foxlink) | 96        | 4.51%   |
| Apple                                  | 86        | 4.04%   |
| Quanta                                 | 67        | 3.15%   |
| Suyin                                  | 66        | 3.1%    |
| Lite-On Technology                     | 42        | 1.97%   |
| Syntek                                 | 27        | 1.27%   |
| Samsung Electronics                    | 21        | 0.99%   |
| Silicon Motion                         | 20        | 0.94%   |
| Luxvisions Innotech Limited            | 20        | 0.94%   |
| Ricoh                                  | 17        | 0.8%    |
| Microsoft                              | 14        | 0.66%   |
| Primax Electronics                     | 13        | 0.61%   |
| Lenovo                                 | 13        | 0.61%   |
| Alcor Micro                            | 13        | 0.61%   |
| Trust                                  | 10        | 0.47%   |
| Jieli Technology                       | 6         | 0.28%   |
| Importek                               | 6         | 0.28%   |
| Generalplus Technology                 | 6         | 0.28%   |
| Sonix Technology                       | 5         | 0.23%   |
| MacroSilicon                           | 5         | 0.23%   |
| Creative Technology                    | 4         | 0.19%   |
| ARC International                      | 4         | 0.19%   |
| Z-Star Microelectronics                | 3         | 0.14%   |
| Y Media                                | 3         | 0.14%   |
| Sweex                                  | 3         | 0.14%   |
| SunplusIT                              | 3         | 0.14%   |
| LG Electronics                         | 3         | 0.14%   |
| Genesys Logic                          | 3         | 0.14%   |
| Bison Electronics                      | 3         | 0.14%   |
| ALi                                    | 3         | 0.14%   |
| Valve Software                         | 2         | 0.09%   |
| Unknown                                | 2         | 0.09%   |
| Tobii Technology AB                    | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 154       | 7.07%   |
| Realtek Integrated_Webcam_HD                                               | 80        | 3.67%   |
| Chicony Integrated Camera                                                  | 71        | 3.26%   |
| Realtek Integrated_Webcam_5M                                               | 67        | 3.08%   |
| Sunplus Integrated_Webcam_HD                                               | 65        | 2.99%   |
| Chicony HD Webcam                                                          | 62        | 2.85%   |
| IMC Networks Integrated Camera                                             | 57        | 2.62%   |
| Acer Integrated Camera                                                     | 37        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 34        | 1.56%   |
| Chicony HP HD Camera                                                       | 28        | 1.29%   |
| Apple Built-in iSight                                                      | 26        | 1.19%   |
| Logitech Webcam C270                                                       | 25        | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 23        | 1.06%   |
| Chicony USB2.0 Camera                                                      | 22        | 1.01%   |
| Samsung Galaxy A5 (MTP)                                                    | 21        | 0.96%   |
| Microdia Integrated_Webcam_5M                                              | 20        | 0.92%   |
| Logitech HD Pro Webcam C920                                                | 20        | 0.92%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.92%   |
| Apple FaceTime HD Camera (Built-in)                                        | 18        | 0.83%   |
| Chicony USB 2.0 Camera                                                     | 17        | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                                            | 17        | 0.78%   |
| Acer BisonCam,NB Pro                                                       | 17        | 0.78%   |
| Sunplus HD WebCam                                                          | 16        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 16        | 0.73%   |
| Syntek Integrated Camera                                                   | 15        | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 15        | 0.69%   |
| Apple FaceTime HD Camera                                                   | 15        | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 14        | 0.64%   |
| Logitech Webcam C310                                                       | 14        | 0.64%   |
| Realtek USB Camera                                                         | 13        | 0.6%    |
| Microdia Integrated Webcam                                                 | 13        | 0.6%    |
| Lite-On Integrated Camera                                                  | 12        | 0.55%   |
| IMC Networks Integrated Webcam                                             | 12        | 0.55%   |
| Chicony Integrated HP HD Webcam                                            | 12        | 0.55%   |
| Acer SunplusIT Integrated Camera                                           | 12        | 0.55%   |
| Acer BisonCam, NB Pro                                                      | 12        | 0.55%   |
| Quanta HP Wide Vision HD Camera                                            | 11        | 0.51%   |
| Quanta HD User Facing                                                      | 11        | 0.51%   |
| Primax HP HD Webcam [Fixed]                                                | 11        | 0.51%   |
| Logitech HD Webcam C525                                                    | 11        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 140       | 33.33%  |
| Synaptics                  | 134       | 31.9%   |
| Shenzhen Goodix Technology | 52        | 12.38%  |
| AuthenTec                  | 31        | 7.38%   |
| Elan Microelectronics      | 23        | 5.48%   |
| Upek                       | 18        | 4.29%   |
| LighTuning Technology      | 18        | 4.29%   |
| STMicroelectronics         | 3         | 0.71%   |
| Samsung Electronics        | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 47        | 11.19%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 10.95%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 9.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 21        | 5%      |
| Validity Sensors VFS491                                                    | 18        | 4.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 4.29%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 4.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.62%   |
| Synaptics  WBDI                                                            | 11        | 2.62%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 2.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.14%   |
| AuthenTec AES2810                                                          | 8         | 1.9%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.43%   |
| AuthenTec AES1600                                                          | 6         | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.95%   |
| Synaptics WBDI Device                                                      | 4         | 0.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 0.95%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.71%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.71%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.71%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.48%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.48%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.24%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.24%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.24%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 101       | 52.6%   |
| Alcor Micro                       | 48        | 25%     |
| O2 Micro                          | 23        | 11.98%  |
| Upek                              | 6         | 3.13%   |
| Lenovo                            | 6         | 3.13%   |
| VASCO Data Security International | 1         | 0.52%   |
| SCM Microsystems                  | 1         | 0.52%   |
| OmniKey                           | 1         | 0.52%   |
| Gemalto (was Gemplus)             | 1         | 0.52%   |
| Fujitsu Siemens Computers         | 1         | 0.52%   |
| Clay Logic                        | 1         | 0.52%   |
| Chicony Electronics               | 1         | 0.52%   |
| Advanced Card Systems             | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 48        | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 17.71%  |
| Broadcom 58200                                                               | 28        | 14.58%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.94%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 10.42%  |
| Broadcom 5880                                                                | 19        | 9.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.13%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.13%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.04%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.52%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.52%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.52%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.52%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.52%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.52%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2439      | 67.98%  |
| 1     | 894       | 24.92%  |
| 2     | 207       | 5.77%   |
| 3     | 31        | 0.86%   |
| 4     | 10        | 0.28%   |
| 5     | 4         | 0.11%   |
| 6     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 415       | 29.41%  |
| Graphics card            | 298       | 21.12%  |
| Chipcard                 | 169       | 11.98%  |
| Net/wireless             | 140       | 9.92%   |
| Multimedia controller    | 130       | 9.21%   |
| Communication controller | 56        | 3.97%   |
| Camera                   | 43        | 3.05%   |
| Bluetooth                | 27        | 1.91%   |
| Unassigned class         | 26        | 1.84%   |
| Sound                    | 22        | 1.56%   |
| Storage                  | 19        | 1.35%   |
| Network                  | 14        | 0.99%   |
| Card reader              | 14        | 0.99%   |
| Net/ethernet             | 13        | 0.92%   |
| Flash memory             | 8         | 0.57%   |
| Storage/ide              | 4         | 0.28%   |
| Storage/ata              | 4         | 0.28%   |
| Tv card                  | 2         | 0.14%   |
| Storage/nvme             | 2         | 0.14%   |
| Modem                    | 2         | 0.14%   |
| Storage/raid             | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

