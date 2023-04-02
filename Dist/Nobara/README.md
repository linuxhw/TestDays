Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 507

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B450 GAMING PLUS            | Desktop     | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Unknown       | ACB20                       | Notebook    | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | Desktop     | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [eba8868f8b](https://linux-hardware.org/?probe=eba8868f8b) | Mar 20, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [ab9d7b857f](https://linux-hardware.org/?probe=ab9d7b857f) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [7659c07b7c](https://linux-hardware.org/?probe=7659c07b7c) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | Notebook    | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | Notebook    | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 36 | 247       | 63.99%  |
| Nobara 37 | 139       | 36.01%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 381       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 37        | 9.2%    |
| 6.0.14-201.fsync.fc36.x86_64  | 30        | 7.46%   |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 6.22%   |
| 5.19.14-201.fsync.fc36.x86_64 | 24        | 5.97%   |
| 6.1.11-201.fsync.fc37.x86_64  | 19        | 4.73%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 4.23%   |
| 6.2.6-201.fsync.fc37.x86_64   | 16        | 3.98%   |
| 6.1.4-203.fsync.fc37.x86_64   | 16        | 3.98%   |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 3.98%   |
| 5.19.7-204.fsync.fc36.x86_64  | 15        | 3.73%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 2.99%   |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 2.99%   |
| 6.0.5-201.fsync.fc36.x86_64   | 11        | 2.74%   |
| 6.0.16-301.fsync.fc37.x86_64  | 11        | 2.74%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 2.74%   |
| 6.1.6-203.fsync.fc37.x86_64   | 10        | 2.49%   |
| 6.1.8-202.fsync.fc37.x86_64   | 9         | 2.24%   |
| 6.0.9-201.fc36.x86_64         | 9         | 2.24%   |
| 5.19.12-201.fsync.fc36.x86_64 | 8         | 1.99%   |
| 5.19.10-201.fsync.fc36.x86_64 | 8         | 1.99%   |
| 5.19.4-201.fsync.fc36.x86_64  | 7         | 1.74%   |
| 5.18.16-201.fsync.fc36.x86_64 | 7         | 1.74%   |
| 5.19.15-202.fsync.fc36.x86_64 | 6         | 1.49%   |
| 5.19.11-201.fsync.fc36.x86_64 | 6         | 1.49%   |
| 5.18.17-201.fsync.fc36.x86_64 | 6         | 1.49%   |
| 6.2.8-200.fsync.fc37.x86_64   | 4         | 1%      |
| 6.1.6-201.fsync.fc37.x86_64   | 4         | 1%      |
| 6.0.9-202.fc36.x86_64         | 4         | 1%      |
| 6.0.8-201.fsync.fc36.x86_64   | 4         | 1%      |
| 6.0.7-202.fsync.fc36.x86_64   | 4         | 1%      |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 1%      |
| 5.18.19-201.fsync.fc36.x86_64 | 4         | 1%      |
| 6.1.8-201.fsync.fc37.x86_64   | 3         | 0.75%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3         | 0.75%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 0.5%    |
| 6.0.18-301.fsync.fc37.x86_64  | 2         | 0.5%    |
| 6.0.15-301.fsync.fc37.x86_64  | 2         | 0.5%    |
| 5.19.7-203.fsync.fc36.x86_64  | 2         | 0.5%    |
| 5.19.13-202.fsync.fc36.x86_64 | 2         | 0.5%    |
| 5.18.18-201.fsync.fc36.x86_64 | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.10  | 37        | 9.2%    |
| 6.0.14  | 30        | 7.46%   |
| 6.1.14  | 25        | 6.22%   |
| 5.19.14 | 24        | 5.97%   |
| 6.1.11  | 19        | 4.73%   |
| 6.1.9   | 17        | 4.23%   |
| 5.19.7  | 17        | 4.23%   |
| 6.2.6   | 16        | 3.98%   |
| 6.1.6   | 16        | 3.98%   |
| 6.1.4   | 16        | 3.98%   |
| 6.0.7   | 16        | 3.98%   |
| 5.19.9  | 16        | 3.98%   |
| 6.1.8   | 13        | 3.23%   |
| 6.0.9   | 13        | 3.23%   |
| 5.19.16 | 12        | 2.99%   |
| 6.0.5   | 11        | 2.74%   |
| 6.0.16  | 11        | 2.74%   |
| 5.18.13 | 11        | 2.74%   |
| 5.19.12 | 8         | 1.99%   |
| 5.19.10 | 8         | 1.99%   |
| 5.19.4  | 7         | 1.74%   |
| 5.18.16 | 7         | 1.74%   |
| 5.19.15 | 6         | 1.49%   |
| 5.19.11 | 6         | 1.49%   |
| 5.18.17 | 6         | 1.49%   |
| 6.2.8   | 4         | 1%      |
| 6.0.8   | 4         | 1%      |
| 5.19.8  | 4         | 1%      |
| 5.18.19 | 4         | 1%      |
| 5.19.13 | 3         | 0.75%   |
| 5.18.11 | 3         | 0.75%   |
| 6.0.18  | 2         | 0.5%    |
| 6.0.15  | 2         | 0.5%    |
| 5.18.18 | 2         | 0.5%    |
| 6.2.0   | 1         | 0.25%   |
| 6.1.12  | 1         | 0.25%   |
| 6.0.2   | 1         | 0.25%   |
| 6.0.13  | 1         | 0.25%   |
| 5.19.2  | 1         | 0.25%   |
| 5.18.9  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 124       | 31.23%  |
| 5.19    | 112       | 28.21%  |
| 6.1     | 106       | 26.7%   |
| 5.18    | 34        | 8.56%   |
| 6.2     | 21        | 5.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 381       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 280       | 73.11%  |
| KDE5          | 96        | 25.07%  |
| Unknown       | 4         | 1.04%   |
| GNOME Classic | 2         | 0.52%   |
| X-Cinnamon    | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 294       | 75.38%  |
| X11     | 91        | 23.33%  |
| Unknown | 4         | 1.03%   |
| Tty     | 1         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 317       | 82.34%  |
| GDM     | 42        | 10.91%  |
| SDDM    | 22        | 5.71%   |
| LightDM | 4         | 1.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 204       | 53.26%  |
| en_GB   | 30        | 7.83%   |
| es_ES   | 15        | 3.92%   |
| de_DE   | 14        | 3.66%   |
| ru_RU   | 10        | 2.61%   |
| es_MX   | 10        | 2.61%   |
| en_CA   | 9         | 2.35%   |
| pt_BR   | 8         | 2.09%   |
| es_AR   | 8         | 2.09%   |
| pl_PL   | 7         | 1.83%   |
| it_IT   | 7         | 1.83%   |
| fr_FR   | 6         | 1.57%   |
| de_AT   | 5         | 1.31%   |
| es_CO   | 4         | 1.04%   |
| en_NZ   | 4         | 1.04%   |
| en_IN   | 4         | 1.04%   |
| pt_PT   | 3         | 0.78%   |
| nl_NL   | 3         | 0.78%   |
| en_AU   | 3         | 0.78%   |
| Unknown | 3         | 0.78%   |
| tr_TR   | 2         | 0.52%   |
| sv_SE   | 2         | 0.52%   |
| fi_FI   | 2         | 0.52%   |
| en_PH   | 2         | 0.52%   |
| ar_SA   | 2         | 0.52%   |
| zh_TW   | 1         | 0.26%   |
| sk_SK   | 1         | 0.26%   |
| nb_NO   | 1         | 0.26%   |
| hu_HU   | 1         | 0.26%   |
| hr_HR   | 1         | 0.26%   |
| es_US   | 1         | 0.26%   |
| es_GT   | 1         | 0.26%   |
| es_EC   | 1         | 0.26%   |
| es_CR   | 1         | 0.26%   |
| es_CL   | 1         | 0.26%   |
| en_ZA   | 1         | 0.26%   |
| en_IL   | 1         | 0.26%   |
| en_IE   | 1         | 0.26%   |
| da_DK   | 1         | 0.26%   |
| cs_CZ   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 308       | 80.63%  |
| BIOS | 74        | 19.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 255       | 66.58%  |
| Ext4  | 126       | 32.9%   |
| Xfs   | 2         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 314       | 81.35%  |
| GPT     | 64        | 16.58%  |
| MBR     | 8         | 2.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 362       | 94.76%  |
| Yes       | 20        | 5.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 90.03%  |
| Yes       | 38        | 9.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 99        | 25.98%  |
| MSI                 | 50        | 13.12%  |
| Lenovo              | 44        | 11.55%  |
| Hewlett-Packard     | 42        | 11.02%  |
| Gigabyte Technology | 31        | 8.14%   |
| Dell                | 27        | 7.09%   |
| ASRock              | 20        | 5.25%   |
| Apple               | 13        | 3.41%   |
| Acer                | 13        | 3.41%   |
| Intel               | 6         | 1.57%   |
| Toshiba             | 3         | 0.79%   |
| Alienware           | 3         | 0.79%   |
| Positivo            | 2         | 0.52%   |
| Notebook            | 2         | 0.52%   |
| Biostar             | 2         | 0.52%   |
| AZW                 | 2         | 0.52%   |
| Unknown             | 2         | 0.52%   |
| ZOTAC               | 1         | 0.26%   |
| Valve               | 1         | 0.26%   |
| Sony                | 1         | 0.26%   |
| Schenker            | 1         | 0.26%   |
| Samsung Electronics | 1         | 0.26%   |
| Razer               | 1         | 0.26%   |
| ONE-NETBOOK         | 1         | 0.26%   |
| OEM                 | 1         | 0.26%   |
| Monster             | 1         | 0.26%   |
| Medion              | 1         | 0.26%   |
| HUAWEI              | 1         | 0.26%   |
| Gateway             | 1         | 0.26%   |
| Fujitsu             | 1         | 0.26%   |
| EVOO                | 1         | 0.26%   |
| eMachines           | 1         | 0.26%   |
| ECS                 | 1         | 0.26%   |
| Dynabook            | 1         | 0.26%   |
| Coradir             | 1         | 0.26%   |
| Casper              | 1         | 0.26%   |
| Acidanthera         | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7C91                         | 5         | 1.31%   |
| MSI MS-7B86                         | 5         | 1.31%   |
| Unknown                             | 5         | 1.31%   |
| MSI MS-7C37                         | 3         | 0.79%   |
| MSI MS-7C02                         | 3         | 0.79%   |
| ASUS PRIME A320M-K                  | 3         | 0.79%   |
| MSI MS-7C56                         | 2         | 0.52%   |
| MSI MS-7B79                         | 2         | 0.52%   |
| MSI MS-7693                         | 2         | 0.52%   |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.52%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 2         | 0.52%   |
| Lenovo IdeaPad C340-14API 81N6      | 2         | 0.52%   |
| Intel X79                           | 2         | 0.52%   |
| HP ZBook 15u G3                     | 2         | 0.52%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 0.52%   |
| HP EliteBook x360 1030 G2           | 2         | 0.52%   |
| Gigabyte Z590I VISION D             | 2         | 0.52%   |
| Gigabyte B450M DS3H                 | 2         | 0.52%   |
| Dell XPS 8700                       | 2         | 0.52%   |
| Dell Vostro 3400                    | 2         | 0.52%   |
| Dell OptiPlex 390                   | 2         | 0.52%   |
| Dell Inspiron 3542                  | 2         | 0.52%   |
| ASUS TUF Gaming B550-PLUS           | 2         | 0.52%   |
| ASUS ROG STRIX B550-F GAMING        | 2         | 0.52%   |
| ASUS ROG CROSSHAIR VIII HERO        | 2         | 0.52%   |
| ASUS PRIME X370-PRO                 | 2         | 0.52%   |
| ASUS PRIME B450M-A                  | 2         | 0.52%   |
| ASUS All Series                     | 2         | 0.52%   |
| ASRock X670E Steel Legend           | 2         | 0.52%   |
| Acer Aspire VX5-591G                | 2         | 0.52%   |
| ZOTAC ZBOX-CI320NANO series         | 1         | 0.26%   |
| Valve Jupiter                       | 1         | 0.26%   |
| Toshiba TECRA A50-A                 | 1         | 0.26%   |
| Toshiba Satellite L850              | 1         | 0.26%   |
| Toshiba Satellite L650              | 1         | 0.26%   |
| Sony SVF1521N6EW                    | 1         | 0.26%   |
| Schenker XMG NEO (M19, RTX 2070)    | 1         | 0.26%   |
| Samsung R520/R522/R620              | 1         | 0.26%   |
| Razer Blade                         | 1         | 0.26%   |
| Positivo N1250                      | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 27        | 7.09%   |
| ASUS PRIME         | 19        | 4.99%   |
| Lenovo IdeaPad     | 14        | 3.67%   |
| ASUS TUF           | 12        | 3.15%   |
| Lenovo ThinkPad    | 9         | 2.36%   |
| HP EliteBook       | 8         | 2.1%    |
| ASUS VivoBook      | 8         | 2.1%    |
| HP Pavilion        | 7         | 1.84%   |
| Acer Aspire        | 7         | 1.84%   |
| Lenovo Legion      | 6         | 1.57%   |
| MSI MS-7C91        | 5         | 1.31%   |
| MSI MS-7B86        | 5         | 1.31%   |
| HP ZBook           | 5         | 1.31%   |
| Dell Precision     | 5         | 1.31%   |
| Dell OptiPlex      | 5         | 1.31%   |
| Unknown            | 5         | 1.31%   |
| Lenovo ThinkCentre | 4         | 1.05%   |
| HP ENVY            | 4         | 1.05%   |
| Dell Inspiron      | 4         | 1.05%   |
| ASUS ASUS          | 4         | 1.05%   |
| MSI MS-7C37        | 3         | 0.79%   |
| MSI MS-7C02        | 3         | 0.79%   |
| HP EliteDesk       | 3         | 0.79%   |
| Gigabyte X570      | 3         | 0.79%   |
| Dell Vostro        | 3         | 0.79%   |
| Toshiba Satellite  | 2         | 0.52%   |
| MSI MS-7C56        | 2         | 0.52%   |
| MSI MS-7B79        | 2         | 0.52%   |
| MSI MS-7693        | 2         | 0.52%   |
| Lenovo G580        | 2         | 0.52%   |
| Intel X79          | 2         | 0.52%   |
| HP OMEN            | 2         | 0.52%   |
| HP Laptop          | 2         | 0.52%   |
| HP Compaq          | 2         | 0.52%   |
| Gigabyte Z590I     | 2         | 0.52%   |
| Gigabyte B550M     | 2         | 0.52%   |
| Gigabyte B450M     | 2         | 0.52%   |
| Gigabyte B450      | 2         | 0.52%   |
| Gigabyte AERO      | 2         | 0.52%   |
| Dell XPS           | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 53        | 13.91%  |
| 2021 | 51        | 13.39%  |
| 2019 | 49        | 12.86%  |
| 2018 | 39        | 10.24%  |
| 2022 | 30        | 7.87%   |
| 2013 | 28        | 7.35%   |
| 2017 | 26        | 6.82%   |
| 2014 | 24        | 6.3%    |
| 2012 | 23        | 6.04%   |
| 2016 | 16        | 4.2%    |
| 2011 | 13        | 3.41%   |
| 2015 | 10        | 2.62%   |
| 2010 | 7         | 1.84%   |
| 2009 | 5         | 1.31%   |
| 2008 | 4         | 1.05%   |
| 2023 | 2         | 0.52%   |
| 2007 | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 190       | 49.87%  |
| Notebook    | 172       | 45.14%  |
| Mini pc     | 8         | 2.1%    |
| Convertible | 5         | 1.31%   |
| All in one  | 5         | 1.31%   |
| Tablet      | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 381       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 381       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 115       | 30.18%  |
| 32.01-64.0  | 78        | 20.47%  |
| 8.01-16.0   | 66        | 17.32%  |
| 4.01-8.0    | 63        | 16.54%  |
| 3.01-4.0    | 32        | 8.4%    |
| 24.01-32.0  | 16        | 4.2%    |
| 64.01-256.0 | 9         | 2.36%   |
| 1.01-2.0    | 2         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 183       | 46.8%   |
| 3.01-4.0   | 92        | 23.53%  |
| 2.01-3.0   | 67        | 17.14%  |
| 8.01-16.0  | 38        | 9.72%   |
| 1.01-2.0   | 8         | 2.05%   |
| 16.01-24.0 | 2         | 0.51%   |
| 24.01-32.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 48.05%  |
| 2      | 100       | 25.97%  |
| 3      | 56        | 14.55%  |
| 4      | 20        | 5.19%   |
| 5      | 16        | 4.16%   |
| 6      | 4         | 1.04%   |
| 10     | 2         | 0.52%   |
| 7      | 2         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 304       | 79.58%  |
| Yes       | 78        | 20.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 89.53%  |
| No        | 40        | 10.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 77.75%  |
| No        | 85        | 22.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 267       | 69.9%   |
| No        | 115       | 30.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 118       | 30.97%  |
| Germany      | 23        | 6.04%   |
| UK           | 17        | 4.46%   |
| Spain        | 15        | 3.94%   |
| Canada       | 13        | 3.41%   |
| Russia       | 12        | 3.15%   |
| Poland       | 12        | 3.15%   |
| Brazil       | 12        | 3.15%   |
| Argentina    | 12        | 3.15%   |
| Italy        | 11        | 2.89%   |
| Mexico       | 10        | 2.62%   |
| France       | 10        | 2.62%   |
| Sweden       | 6         | 1.57%   |
| India        | 6         | 1.57%   |
| Austria      | 6         | 1.57%   |
| Portugal     | 5         | 1.31%   |
| Philippines  | 5         | 1.31%   |
| Colombia     | 5         | 1.31%   |
| Chile        | 5         | 1.31%   |
| New Zealand  | 4         | 1.05%   |
| Netherlands  | 4         | 1.05%   |
| Australia    | 4         | 1.05%   |
| Serbia       | 3         | 0.79%   |
| Saudi Arabia | 3         | 0.79%   |
| Romania      | 3         | 0.79%   |
| Norway       | 3         | 0.79%   |
| Indonesia    | 3         | 0.79%   |
| Hungary      | 3         | 0.79%   |
| Finland      | 3         | 0.79%   |
| Czechia      | 3         | 0.79%   |
| Croatia      | 3         | 0.79%   |
| Vietnam      | 2         | 0.52%   |
| Venezuela    | 2         | 0.52%   |
| Turkey       | 2         | 0.52%   |
| South Africa | 2         | 0.52%   |
| Estonia      | 2         | 0.52%   |
| Egypt        | 2         | 0.52%   |
| Belgium      | 2         | 0.52%   |
| Ukraine      | 1         | 0.26%   |
| Taiwan       | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| London       | 4         | 1.02%   |
| Guadalajara  | 4         | 1.02%   |
| Buenos Aires | 4         | 1.02%   |
| Wroclaw      | 3         | 0.77%   |
| Vienna       | 3         | 0.77%   |
| Perm         | 3         | 0.77%   |
| Auckland     | 3         | 0.77%   |
| Atlanta      | 3         | 0.77%   |
| Wasilla      | 2         | 0.51%   |
| Warsaw       | 2         | 0.51%   |
| Villa Nueva  | 2         | 0.51%   |
| Valladolid   | 2         | 0.51%   |
| Tucson       | 2         | 0.51%   |
| Stockholm    | 2         | 0.51%   |
| Springfield  | 2         | 0.51%   |
| Schmalkalden | 2         | 0.51%   |
| Sao Paulo    | 2         | 0.51%   |
| San Jose     | 2         | 0.51%   |
| San Diego    | 2         | 0.51%   |
| San Antonio  | 2         | 0.51%   |
| Salem        | 2         | 0.51%   |
| Rotterdam    | 2         | 0.51%   |
| Rome         | 2         | 0.51%   |
| Riyadh       | 2         | 0.51%   |
| Poznan       | 2         | 0.51%   |
| Plano        | 2         | 0.51%   |
| Philadelphia | 2         | 0.51%   |
| Pereira      | 2         | 0.51%   |
| Panama City  | 2         | 0.51%   |
| Ochsenfurt   | 2         | 0.51%   |
| Novosibirsk  | 2         | 0.51%   |
| Mumbai       | 2         | 0.51%   |
| Moscow       | 2         | 0.51%   |
| Milano       | 2         | 0.51%   |
| Milan        | 2         | 0.51%   |
| Melbourne    | 2         | 0.51%   |
| Mansfield    | 2         | 0.51%   |
| Madrid       | 2         | 0.51%   |
| Johannesburg | 2         | 0.51%   |
| Irvine       | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 119       | 177    | 17.95%  |
| WDC                         | 88        | 126    | 13.27%  |
| Seagate                     | 71        | 90     | 10.71%  |
| Kingston                    | 49        | 53     | 7.39%   |
| Toshiba                     | 40        | 45     | 6.03%   |
| Sandisk                     | 38        | 40     | 5.73%   |
| Crucial                     | 36        | 48     | 5.43%   |
| Intel                       | 21        | 28     | 3.17%   |
| Phison Electronics          | 16        | 17     | 2.41%   |
| Micron/Crucial Technology   | 16        | 23     | 2.41%   |
| SK hynix                    | 15        | 16     | 2.26%   |
| Micron Technology           | 14        | 14     | 2.11%   |
| PNY                         | 9         | 13     | 1.36%   |
| Hitachi                     | 9         | 13     | 1.36%   |
| China                       | 8         | 8      | 1.21%   |
| Apple                       | 8         | 9      | 1.21%   |
| Unknown                     | 7         | 9      | 1.06%   |
| Phison                      | 7         | 8      | 1.06%   |
| SPCC                        | 6         | 7      | 0.9%    |
| KIOXIA                      | 6         | 6      | 0.9%    |
| HGST                        | 6         | 6      | 0.9%    |
| Silicon Motion              | 5         | 5      | 0.75%   |
| ADATA Technology            | 5         | 5      | 0.75%   |
| Kingston Technology Company | 4         | 4      | 0.6%    |
| A-DATA Technology           | 4         | 4      | 0.6%    |
| Team                        | 3         | 3      | 0.45%   |
| Realtek Semiconductor       | 3         | 3      | 0.45%   |
| Unknown                     | 3         | 4      | 0.45%   |
| USB3.0                      | 2         | 2      | 0.3%    |
| Transcend                   | 2         | 2      | 0.3%    |
| Mushkin                     | 2         | 2      | 0.3%    |
| LITEON                      | 2         | 2      | 0.3%    |
| KingFast                    | 2         | 2      | 0.3%    |
| HS-SSD-C100                 | 2         | 2      | 0.3%    |
| Drevo                       | 2         | 2      | 0.3%    |
| Apacer                      | 2         | 2      | 0.3%    |
| XSTAR                       | 1         | 1      | 0.15%   |
| XPG                         | 1         | 1      | 0.15%   |
| Verbatim                    | 1         | 1      | 0.15%   |
| Union Memory                | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 21        | 2.77%   |
| Kingston SA400S37240G 240GB SSD                     | 18        | 2.38%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 13        | 1.72%   |
| Samsung SSD 860 EVO 500GB                           | 9         | 1.19%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 8         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 8         | 1.06%   |
| Phison E12 NVMe Controller 256GB                    | 8         | 1.06%   |
| Crucial CT1000MX500SSD1 1TB                         | 8         | 1.06%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.92%   |
| Intel SSD 660P Series 512GB                         | 7         | 0.92%   |
| Seagate ST2000DM008-2FR102 2TB                      | 6         | 0.79%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 0.79%   |
| Toshiba HDWD110 1TB                                 | 5         | 0.66%   |
| Toshiba DT01ACA100 1TB                              | 5         | 0.66%   |
| Seagate ST2000DM001-1ER164 2TB                      | 5         | 0.66%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 5         | 0.66%   |
| Samsung SSD 980 1TB                                 | 5         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 5         | 0.66%   |
| Phison PS5013 E13 NVMe Controller 256GB             | 5         | 0.66%   |
| Crucial CT1000BX500SSD1 1TB                         | 5         | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 4         | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 4         | 0.53%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.53%   |
| Toshiba DT01ACA200 2TB                              | 4         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4         | 0.53%   |
| Samsung SSD 980 500GB                               | 4         | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB                      | 4         | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 0.53%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB       | 4         | 0.53%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.53%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 0.53%   |
| Crucial CT2000MX500SSD1 2TB                         | 4         | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3         | 0.4%    |
| WDC WDBNCE5000PNC 500GB SSD                         | 3         | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3         | 0.4%    |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.4%    |
| SK hynix BC511 512GB                                | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 70        | 99     | 33.82%  |
| Seagate             | 70        | 87     | 33.82%  |
| Toshiba             | 33        | 37     | 15.94%  |
| Hitachi             | 9         | 13     | 4.35%   |
| Samsung Electronics | 7         | 13     | 3.38%   |
| HGST                | 6         | 6      | 2.9%    |
| Apple               | 5         | 5      | 2.42%   |
| USB3.0              | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |
| SABRENT             | 1         | 2      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |
| HGST HTS            | 1         | 1      | 0.48%   |
| Hewlett-Packard     | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 56        | 68     | 23.33%  |
| Kingston            | 37        | 40     | 15.42%  |
| Crucial             | 35        | 47     | 14.58%  |
| WDC                 | 18        | 19     | 7.5%    |
| SanDisk             | 14        | 14     | 5.83%   |
| PNY                 | 9         | 13     | 3.75%   |
| China               | 8         | 8      | 3.33%   |
| SPCC                | 6         | 7      | 2.5%    |
| Micron Technology   | 6         | 6      | 2.5%    |
| SK hynix            | 4         | 4      | 1.67%   |
| Intel               | 4         | 4      | 1.67%   |
| A-DATA Technology   | 4         | 4      | 1.67%   |
| Transcend           | 2         | 2      | 0.83%   |
| Toshiba             | 2         | 2      | 0.83%   |
| Team                | 2         | 2      | 0.83%   |
| Seagate             | 2         | 2      | 0.83%   |
| Mushkin             | 2         | 2      | 0.83%   |
| LITEON              | 2         | 2      | 0.83%   |
| KingFast            | 2         | 2      | 0.83%   |
| Drevo               | 2         | 2      | 0.83%   |
| Apple               | 2         | 2      | 0.83%   |
| Apacer              | 2         | 2      | 0.83%   |
| XSTAR               | 1         | 1      | 0.42%   |
| Verbatim            | 1         | 1      | 0.42%   |
| USB3.0              | 1         | 1      | 0.42%   |
| SuperSSpeed         | 1         | 1      | 0.42%   |
| Ramsta              | 1         | 1      | 0.42%   |
| PNY CS90            | 1         | 1      | 0.42%   |
| Patriot             | 1         | 1      | 0.42%   |
| ORTIAL              | 1         | 1      | 0.42%   |
| OCZ                 | 1         | 1      | 0.42%   |
| Neo                 | 1         | 1      | 0.42%   |
| MyDigitalSSD        | 1         | 1      | 0.42%   |
| LITEONIT            | 1         | 1      | 0.42%   |
| Lexar               | 1         | 1      | 0.42%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.42%   |
| Foxline             | 1         | 1      | 0.42%   |
| Emtec               | 1         | 1      | 0.42%   |
| Corsair             | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 198       | 274    | 34.14%  |
| NVMe    | 195       | 273    | 33.62%  |
| HDD     | 172       | 268    | 29.66%  |
| Unknown | 11        | 13     | 1.9%    |
| MMC     | 4         | 4      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 273       | 527    | 55.26%  |
| NVMe | 194       | 272    | 39.27%  |
| SAS  | 23        | 29     | 4.66%   |
| MMC  | 4         | 4      | 0.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 189       | 262    | 46.67%  |
| 0.51-1.0   | 130       | 169    | 32.1%   |
| 1.01-2.0   | 53        | 73     | 13.09%  |
| 3.01-4.0   | 11        | 11     | 2.72%   |
| 4.01-10.0  | 11        | 15     | 2.72%   |
| 2.01-3.0   | 7         | 7      | 1.73%   |
| 10.01-20.0 | 4         | 5      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 21.39%  |
| 501-1000       | 80        | 20.62%  |
| 251-500        | 77        | 19.85%  |
| 1001-2000      | 65        | 16.75%  |
| More than 3000 | 31        | 7.99%   |
| 2001-3000      | 18        | 4.64%   |
| Unknown        | 12        | 3.09%   |
| 21-50          | 11        | 2.84%   |
| 51-100         | 9         | 2.32%   |
| 1-20           | 2         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 107       | 27.16%  |
| 1-20           | 77        | 19.54%  |
| 101-250        | 55        | 13.96%  |
| 51-100         | 43        | 10.91%  |
| 251-500        | 41        | 10.41%  |
| 501-1000       | 28        | 7.11%   |
| 1001-2000      | 13        | 3.3%    |
| Unknown        | 12        | 3.05%   |
| More than 3000 | 10        | 2.54%   |
| 2001-3000      | 8         | 2.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 14.29%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 7.14%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 7.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 7.14%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 7.14%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 7.14%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 7.14%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 7.14%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 7.14%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 28.57%  |
| Seagate             | 3         | 3      | 21.43%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| SK hynix            | 1         | 1      | 7.14%   |
| Ramsta              | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 40%     |
| Seagate             | 3         | 3      | 30%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 71.43%  |
| SSD  | 3         | 3      | 21.43%  |
| NVMe | 1         | 1      | 7.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 320       | 677    | 79.6%   |
| Works    | 69        | 140    | 17.16%  |
| Malfunc  | 12        | 14     | 2.99%   |
| Limited  | 1         | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 206       | 35.7%   |
| AMD                            | 133       | 23.05%  |
| Samsung Electronics            | 74        | 12.82%  |
| SanDisk                        | 30        | 5.2%    |
| Phison Electronics             | 23        | 3.99%   |
| Micron/Crucial Technology      | 17        | 2.95%   |
| Kingston Technology Company    | 17        | 2.95%   |
| ASMedia Technology             | 15        | 2.6%    |
| SK hynix                       | 11        | 1.91%   |
| Micron Technology              | 8         | 1.39%   |
| Nvidia                         | 6         | 1.04%   |
| KIOXIA                         | 6         | 1.04%   |
| Silicon Motion                 | 5         | 0.87%   |
| ADATA Technology               | 5         | 0.87%   |
| Toshiba America Info Systems   | 4         | 0.69%   |
| Realtek Semiconductor          | 4         | 0.69%   |
| Marvell Technology Group       | 4         | 0.69%   |
| JMicron Technology             | 2         | 0.35%   |
| Union Memory (Shenzhen)        | 1         | 0.17%   |
| Solid State Storage Technology | 1         | 0.17%   |
| Silicon Image                  | 1         | 0.17%   |
| Shenzhen Longsys Electronics   | 1         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.17%   |
| Broadcom / LSI                 | 1         | 0.17%   |
| Apple                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 89        | 13.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 34        | 5.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 29        | 4.48%   |
| Samsung NVMe SSD Controller 980                                                | 20        | 3.09%   |
| AMD 500 Series Chipset SATA Controller                                         | 19        | 2.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 2.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 14        | 2.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 2.01%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 13        | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 1.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 1.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.55%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 1.39%   |
| Intel SSD 660P Series                                                          | 9         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.39%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.24%   |
| Micron NVMe Storage Controller                                                 | 8         | 1.24%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.08%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                | 6         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 6         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 0.77%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                               | 5         | 0.77%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.77%   |
| Intel Non-Volatile memory controller                                           | 5         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 306       | 55.33%  |
| NVMe | 194       | 35.08%  |
| RAID | 29        | 5.24%   |
| IDE  | 22        | 3.98%   |
| SAS  | 2         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 222       | 58.27%  |
| AMD    | 159       | 41.73%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 9         | 2.36%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8         | 2.1%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 8         | 2.1%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 6         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 1.31%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 5         | 1.31%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5         | 1.31%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 5         | 1.31%   |
| AMD FX-8350 Eight-Core Processor            | 5         | 1.31%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 1.05%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4         | 1.05%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.05%   |
| Intel 12th Gen Core i5-12600K               | 4         | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 4         | 1.05%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4         | 1.05%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 1.05%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4         | 1.05%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3         | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 3         | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.79%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 3         | 0.79%   |
| Intel 12th Gen Core i7-12700H               | 3         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 0.79%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 3         | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3         | 0.79%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3         | 0.79%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3         | 0.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.79%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3         | 0.79%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3         | 0.79%   |
| AMD FX-6300 Six-Core Processor              | 3         | 0.79%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 73        | 19.16%  |
| Intel Core i5           | 65        | 17.06%  |
| AMD Ryzen 5             | 60        | 15.75%  |
| AMD Ryzen 7             | 42        | 11.02%  |
| Other                   | 31        | 8.14%   |
| AMD Ryzen 9             | 22        | 5.77%   |
| Intel Core i3           | 20        | 5.25%   |
| AMD FX                  | 12        | 3.15%   |
| Intel Celeron           | 8         | 2.1%    |
| Intel Xeon              | 6         | 1.57%   |
| Intel Core 2 Duo        | 6         | 1.57%   |
| Intel Pentium           | 5         | 1.31%   |
| AMD Ryzen 3             | 5         | 1.31%   |
| Intel Core i9           | 4         | 1.05%   |
| AMD A10                 | 3         | 0.79%   |
| Intel Atom              | 2         | 0.52%   |
| AMD Phenom II X6        | 2         | 0.52%   |
| AMD A6                  | 2         | 0.52%   |
| Intel Pentium Dual-Core | 1         | 0.26%   |
| Intel Core m7           | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| AMD Ryzen 3 PRO         | 1         | 0.26%   |
| AMD PRO A10             | 1         | 0.26%   |
| AMD Phenom II X4        | 1         | 0.26%   |
| AMD Phenom              | 1         | 0.26%   |
| AMD G                   | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD Athlon X4           | 1         | 0.26%   |
| AMD Athlon II X2        | 1         | 0.26%   |
| AMD Athlon Dual Core    | 1         | 0.26%   |
| AMD A4                  | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 114       | 29.92%  |
| 6      | 87        | 22.83%  |
| 2      | 84        | 22.05%  |
| 8      | 60        | 15.75%  |
| 12     | 12        | 3.15%   |
| 16     | 9         | 2.36%   |
| 10     | 6         | 1.57%   |
| 3      | 4         | 1.05%   |
| 14     | 3         | 0.79%   |
| 1      | 2         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 380       | 99.74%  |
| 2      | 1         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 313       | 82.15%  |
| 1      | 68        | 17.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 381       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08701021 | 22        | 5.74%   |
| Unknown    | 20        | 5.22%   |
| 0x306c3    | 19        | 4.96%   |
| 0x306a9    | 19        | 4.96%   |
| 0x206a7    | 16        | 4.18%   |
| 0x0a50000c | 16        | 4.18%   |
| 0x906ea    | 15        | 3.92%   |
| 0x40651    | 13        | 3.39%   |
| 0xa0652    | 12        | 3.13%   |
| 0x906e9    | 12        | 3.13%   |
| 0x08108109 | 12        | 3.13%   |
| 0x506e3    | 9         | 2.35%   |
| 0x0800820d | 9         | 2.35%   |
| 0x906a3    | 8         | 2.09%   |
| 0x806c1    | 8         | 2.09%   |
| 0x06000822 | 8         | 2.09%   |
| 0x806e9    | 7         | 1.83%   |
| 0x08608103 | 7         | 1.83%   |
| 0xa0655    | 6         | 1.57%   |
| 0x90672    | 6         | 1.57%   |
| 0x0a601203 | 6         | 1.57%   |
| 0x0a201016 | 6         | 1.57%   |
| 0x906ed    | 5         | 1.31%   |
| 0x806d1    | 5         | 1.31%   |
| 0x406e3    | 5         | 1.31%   |
| 0x0a50000d | 5         | 1.31%   |
| 0x0a20120a | 5         | 1.31%   |
| 0x08001138 | 5         | 1.31%   |
| 0xa0653    | 4         | 1.04%   |
| 0x906ec    | 4         | 1.04%   |
| 0x206d7    | 4         | 1.04%   |
| 0x1067a    | 4         | 1.04%   |
| 0x0a201205 | 4         | 1.04%   |
| 0x0a201204 | 4         | 1.04%   |
| 0x08600106 | 4         | 1.04%   |
| 0x08600104 | 4         | 1.04%   |
| 0x806ea    | 3         | 0.78%   |
| 0x30678    | 3         | 0.78%   |
| 0x10676    | 3         | 0.78%   |
| 0x08701013 | 3         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 53        | 13.91%  |
| Zen 3            | 44        | 11.55%  |
| Haswell          | 36        | 9.45%   |
| Zen 2            | 35        | 9.19%   |
| Zen+             | 26        | 6.82%   |
| CometLake        | 22        | 5.77%   |
| SandyBridge      | 21        | 5.51%   |
| IvyBridge        | 21        | 5.51%   |
| Unknown          | 19        | 4.99%   |
| Skylake          | 15        | 3.94%   |
| Alderlake Hybrid | 14        | 3.67%   |
| Piledriver       | 12        | 3.15%   |
| Icelake          | 9         | 2.36%   |
| Zen              | 8         | 2.1%    |
| TigerLake        | 8         | 2.1%    |
| Penryn           | 7         | 1.84%   |
| K10              | 5         | 1.31%   |
| Silvermont       | 4         | 1.05%   |
| Steamroller      | 3         | 0.79%   |
| Excavator        | 3         | 0.79%   |
| Broadwell        | 3         | 0.79%   |
| Westmere         | 2         | 0.52%   |
| Goldmont plus    | 2         | 0.52%   |
| Bobcat           | 2         | 0.52%   |
| Puma             | 1         | 0.26%   |
| Nehalem          | 1         | 0.26%   |
| K8 Hammer        | 1         | 0.26%   |
| Goldmont         | 1         | 0.26%   |
| Core             | 1         | 0.26%   |
| Bulldozer        | 1         | 0.26%   |
| Bonnell          | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 185       | 37.68%  |
| AMD    | 156       | 31.77%  |
| Intel  | 150       | 30.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 18        | 3.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 15        | 2.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 14        | 2.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 14        | 2.77%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 13        | 2.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 2.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 11        | 2.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 1.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 9         | 1.78%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 9         | 1.78%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9         | 1.78%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 1.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 7         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 1.39%   |
| Intel HD Graphics 530                                                       | 7         | 1.39%   |
| AMD Renoir                                                                  | 7         | 1.39%   |
| AMD Lucienne                                                                | 7         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 6         | 1.19%   |
| Intel HD Graphics 630                                                       | 6         | 1.19%   |
| Intel HD Graphics 620                                                       | 6         | 1.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 6         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 6         | 1.19%   |
| AMD Raphael                                                                 | 6         | 1.19%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6         | 1.19%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6         | 1.19%   |
| Nvidia TU117M                                                               | 5         | 0.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5         | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 5         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 0.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4         | 0.79%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4         | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4         | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 0.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 0.79%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 111       | 29.13%  |
| 1 x Nvidia         | 96        | 25.2%   |
| 1 x Intel          | 65        | 17.06%  |
| Intel + Nvidia     | 63        | 16.54%  |
| AMD + Nvidia       | 23        | 6.04%   |
| 2 x AMD            | 10        | 2.62%   |
| Intel + AMD        | 10        | 2.62%   |
| 2 x Nvidia         | 2         | 0.52%   |
| Intel + 2 x Nvidia | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 61.62%  |
| Proprietary | 140       | 36.55%  |
| Unknown     | 7         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 43.9%   |
| 7.01-8.0   | 48        | 12.47%  |
| 0.01-0.5   | 42        | 10.91%  |
| 1.01-2.0   | 36        | 9.35%   |
| 3.01-4.0   | 30        | 7.79%   |
| 8.01-16.0  | 25        | 6.49%   |
| 0.51-1.0   | 19        | 4.94%   |
| 5.01-6.0   | 9         | 2.34%   |
| 16.01-24.0 | 4         | 1.04%   |
| 2.01-3.0   | 3         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 56        | 12.93%  |
| AU Optronics            | 44        | 10.16%  |
| Goldstar                | 30        | 6.93%   |
| BOE                     | 28        | 6.47%   |
| Chimei Innolux          | 24        | 5.54%   |
| LG Display              | 23        | 5.31%   |
| Acer                    | 20        | 4.62%   |
| Dell                    | 18        | 4.16%   |
| BenQ                    | 16        | 3.7%    |
| ASUSTek Computer        | 14        | 3.23%   |
| Ancor Communications    | 13        | 3%      |
| PANDA                   | 12        | 2.77%   |
| Hewlett-Packard         | 12        | 2.77%   |
| AOC                     | 12        | 2.77%   |
| Apple                   | 11        | 2.54%   |
| MSI                     | 10        | 2.31%   |
| ViewSonic               | 9         | 2.08%   |
| Vizio                   | 8         | 1.85%   |
| Sony                    | 7         | 1.62%   |
| Sharp                   | 7         | 1.62%   |
| Lenovo                  | 6         | 1.39%   |
| Philips                 | 5         | 1.15%   |
| InfoVision              | 5         | 1.15%   |
| Sceptre Tech            | 4         | 0.92%   |
| Gigabyte Technology     | 4         | 0.92%   |
| Toshiba                 | 3         | 0.69%   |
| Unknown                 | 2         | 0.46%   |
| Insignia                | 2         | 0.46%   |
| Iiyama                  | 2         | 0.46%   |
| HUAWEI                  | 2         | 0.46%   |
| Eizo                    | 2         | 0.46%   |
| Chi Mei Optoelectronics | 2         | 0.46%   |
| ___                     | 1         | 0.23%   |
| Valve                   | 1         | 0.23%   |
| Sun                     | 1         | 0.23%   |
| SNC                     | 1         | 0.23%   |
| SFX                     | 1         | 0.23%   |
| PRI                     | 1         | 0.23%   |
| Olevia                  | 1         | 0.23%   |
| OEM                     | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 0.89%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 3         | 0.67%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 3         | 0.67%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 0.67%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 3         | 0.67%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 3         | 0.67%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 2         | 0.44%   |
| Toshiba TV TSB0108 1920x540                                            | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.44%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 2         | 0.44%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                        | 2         | 0.44%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 0.44%   |
| Lenovo L2250p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch               | 2         | 0.44%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch           | 2         | 0.44%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.44%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 0.44%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 2         | 0.44%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                     | 2         | 0.44%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 0.44%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 0.44%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.44%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 2         | 0.44%   |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch     | 2         | 0.44%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch         | 2         | 0.44%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 2         | 0.44%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                        | 2         | 0.44%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 195       | 47.45%  |
| 2560x1440 (QHD)    | 46        | 11.19%  |
| 3840x2160 (4K)     | 45        | 10.95%  |
| 1366x768 (WXGA)    | 42        | 10.22%  |
| 1680x1050 (WSXGA+) | 9         | 2.19%   |
| 1440x900 (WXGA+)   | 9         | 2.19%   |
| 1920x1200 (WUXGA)  | 8         | 1.95%   |
| 3440x1440          | 7         | 1.7%    |
| 2560x1080          | 6         | 1.46%   |
| 1600x900 (HD+)     | 6         | 1.46%   |
| 1360x768           | 6         | 1.46%   |
| 1920x540           | 5         | 1.22%   |
| 2880x1800          | 4         | 0.97%   |
| 2560x1600          | 4         | 0.97%   |
| 1280x800 (WXGA)    | 3         | 0.73%   |
| 1280x1024 (SXGA)   | 3         | 0.73%   |
| 2240x1400          | 2         | 0.49%   |
| 800x1280           | 1         | 0.24%   |
| 5760x1080          | 1         | 0.24%   |
| 3840x2560          | 1         | 0.24%   |
| 3840x2400          | 1         | 0.24%   |
| 3840x1600          | 1         | 0.24%   |
| 3840x1080          | 1         | 0.24%   |
| 3200x1800 (QHD+)   | 1         | 0.24%   |
| 2520x1680          | 1         | 0.24%   |
| 2288x1287          | 1         | 0.24%   |
| 1600x2560          | 1         | 0.24%   |
| Unknown            | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 100       | 22.94%  |
| 27      | 57        | 13.07%  |
| 24      | 29        | 6.65%   |
| 31      | 28        | 6.42%   |
| 23      | 28        | 6.42%   |
| 21      | 23        | 5.28%   |
| 13      | 22        | 5.05%   |
| 17      | 21        | 4.82%   |
| 14      | 18        | 4.13%   |
| 34      | 10        | 2.29%   |
| 84      | 8         | 1.83%   |
| Unknown | 8         | 1.83%   |
| 20      | 7         | 1.61%   |
| 72      | 6         | 1.38%   |
| 48      | 6         | 1.38%   |
| 19      | 6         | 1.38%   |
| 26      | 5         | 1.15%   |
| 22      | 5         | 1.15%   |
| 16      | 5         | 1.15%   |
| 42      | 4         | 0.92%   |
| 18      | 4         | 0.92%   |
| 49      | 3         | 0.69%   |
| 40      | 3         | 0.69%   |
| 52      | 2         | 0.46%   |
| 38      | 2         | 0.46%   |
| 37      | 2         | 0.46%   |
| 33      | 2         | 0.46%   |
| 32      | 2         | 0.46%   |
| 29      | 2         | 0.46%   |
| 28      | 2         | 0.46%   |
| 12      | 2         | 0.46%   |
| 142     | 1         | 0.23%   |
| 75      | 1         | 0.23%   |
| 69      | 1         | 0.23%   |
| 60      | 1         | 0.23%   |
| 58      | 1         | 0.23%   |
| 57      | 1         | 0.23%   |
| 55      | 1         | 0.23%   |
| 54      | 1         | 0.23%   |
| 35      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 135       | 31.69%  |
| 501-600        | 104       | 24.41%  |
| 401-500        | 45        | 10.56%  |
| 601-700        | 38        | 8.92%   |
| 351-400        | 18        | 4.23%   |
| 201-300        | 17        | 3.99%   |
| 1501-2000      | 16        | 3.76%   |
| 1001-1500      | 16        | 3.76%   |
| 701-800        | 14        | 3.29%   |
| 801-900        | 8         | 1.88%   |
| Unknown        | 8         | 1.88%   |
| 901-1000       | 4         | 0.94%   |
| More than 2000 | 1         | 0.23%   |
| 101-200        | 1         | 0.23%   |
| 1-100          | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 298       | 80.32%  |
| 16/10   | 43        | 11.59%  |
| 21/9    | 14        | 3.77%   |
| 5/4     | 3         | 0.81%   |
| 32/9    | 3         | 0.81%   |
| 4/3     | 2         | 0.54%   |
| 3/2     | 2         | 0.54%   |
| Unknown | 2         | 0.54%   |
| 1.96    | 1         | 0.27%   |
| 1.00    | 1         | 0.27%   |
| 0.67    | 1         | 0.27%   |
| 0.62    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 23.33%  |
| 201-250        | 68        | 15.7%   |
| 301-350        | 62        | 14.32%  |
| 351-500        | 42        | 9.7%    |
| 81-90          | 31        | 7.16%   |
| More than 1000 | 30        | 6.93%   |
| 151-200        | 23        | 5.31%   |
| 121-130        | 16        | 3.7%    |
| 501-1000       | 14        | 3.23%   |
| 251-300        | 12        | 2.77%   |
| 71-80          | 8         | 1.85%   |
| Unknown        | 8         | 1.85%   |
| 141-150        | 5         | 1.15%   |
| 111-120        | 5         | 1.15%   |
| 61-70          | 2         | 0.46%   |
| 1-40           | 2         | 0.46%   |
| 131-140        | 2         | 0.46%   |
| 51-60          | 1         | 0.23%   |
| 41-50          | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 144       | 34.62%  |
| 121-160       | 107       | 25.72%  |
| 101-120       | 93        | 22.36%  |
| 161-240       | 27        | 6.49%   |
| 1-50          | 26        | 6.25%   |
| More than 240 | 11        | 2.64%   |
| Unknown       | 8         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 282       | 74.02%  |
| 2     | 72        | 18.9%   |
| 0     | 14        | 3.67%   |
| 3     | 12        | 3.15%   |
| 4     | 1         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 231       | 38.82%  |
| Intel                           | 196       | 32.94%  |
| Qualcomm Atheros                | 41        | 6.89%   |
| Broadcom                        | 32        | 5.38%   |
| MediaTek                        | 20        | 3.36%   |
| TP-Link                         | 13        | 2.18%   |
| Microsoft                       | 7         | 1.18%   |
| Ralink Technology               | 6         | 1.01%   |
| Broadcom Limited                | 5         | 0.84%   |
| Samsung Electronics             | 4         | 0.67%   |
| ASIX Electronics                | 4         | 0.67%   |
| Ralink                          | 3         | 0.5%    |
| Nvidia                          | 3         | 0.5%    |
| Xiaomi                          | 2         | 0.34%   |
| Qualcomm Atheros Communications | 2         | 0.34%   |
| Qualcomm                        | 2         | 0.34%   |
| Motorola PCS                    | 2         | 0.34%   |
| Marvell Technology Group        | 2         | 0.34%   |
| Hewlett-Packard                 | 2         | 0.34%   |
| ASUSTek Computer                | 2         | 0.34%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.17%   |
| Wacom                           | 1         | 0.17%   |
| T & A Mobile Phones             | 1         | 0.17%   |
| Sierra Wireless                 | 1         | 0.17%   |
| Panasonic (Matsushita)          | 1         | 0.17%   |
| Oculus VR                       | 1         | 0.17%   |
| Linksys                         | 1         | 0.17%   |
| Lenovo                          | 1         | 0.17%   |
| JMicron Technology              | 1         | 0.17%   |
| ICS Advent                      | 1         | 0.17%   |
| Holtek Semiconductor            | 1         | 0.17%   |
| Google                          | 1         | 0.17%   |
| D-Link System                   | 1         | 0.17%   |
| D-Link                          | 1         | 0.17%   |
| Aquantia                        | 1         | 0.17%   |
| Afatech                         | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 178       | 25.87%  |
| Intel Wi-Fi 6 AX200                                               | 34        | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 4.07%   |
| Intel I211 Gigabit Network Connection                             | 21        | 3.05%   |
| Intel Ethernet Controller I225-V                                  | 13        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 1.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.16%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.16%   |
| Intel Wireless 8260                                               | 8         | 1.16%   |
| Intel Wireless 7265                                               | 8         | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 1.02%   |
| Intel Wireless 7260                                               | 7         | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 0.73%   |
| Intel Wireless-AC 9260                                            | 5         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.58%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.58%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4         | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.58%   |
| TP-Link 802.11ac NIC                                              | 3         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 47.44%  |
| Realtek Semiconductor           | 49        | 15.71%  |
| Qualcomm Atheros                | 28        | 8.97%   |
| Broadcom                        | 26        | 8.33%   |
| MediaTek                        | 20        | 6.41%   |
| TP-Link                         | 12        | 3.85%   |
| Microsoft                       | 7         | 2.24%   |
| Ralink Technology               | 6         | 1.92%   |
| Ralink                          | 3         | 0.96%   |
| Broadcom Limited                | 3         | 0.96%   |
| Qualcomm Atheros Communications | 2         | 0.64%   |
| ASUSTek Computer                | 2         | 0.64%   |
| Wacom                           | 1         | 0.32%   |
| Sierra Wireless                 | 1         | 0.32%   |
| Panasonic (Matsushita)          | 1         | 0.32%   |
| Linksys                         | 1         | 0.32%   |
| D-Link System                   | 1         | 0.32%   |
| D-Link                          | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 34        | 10.86%  |
| Intel Cannon Lake PCH CNVi WiFi                               | 13        | 4.15%   |
| Intel Comet Lake PCH CNVi WiFi                                | 12        | 3.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 10        | 3.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 9         | 2.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 9         | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 8         | 2.56%   |
| Intel Wireless 8265 / 8275                                    | 8         | 2.56%   |
| Intel Wireless 8260                                           | 8         | 2.56%   |
| Intel Wireless 7265                                           | 8         | 2.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 7         | 2.24%   |
| Intel Wireless 7260                                           | 7         | 2.24%   |
| Intel Wi-Fi 6 AX201                                           | 7         | 2.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 7         | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 6         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 6         | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 6         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 5         | 1.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 5         | 1.6%    |
| Intel Wireless-AC 9260                                        | 5         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 5         | 1.6%    |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 1.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 4         | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4         | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 4         | 1.28%   |
| TP-Link 802.11ac NIC                                          | 3         | 0.96%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 0.96%   |
| Microsoft Xbox 360 Wireless Adapter                           | 3         | 0.96%   |
| Microsoft Wireless XBox Controller Dongle                     | 3         | 0.96%   |
| Intel Wireless 3160                                           | 3         | 0.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 3         | 0.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 3         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 0.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 0.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter               | 2         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 214       | 59.12%  |
| Intel                      | 92        | 25.41%  |
| Qualcomm Atheros           | 15        | 4.14%   |
| Broadcom                   | 11        | 3.04%   |
| ASIX Electronics           | 4         | 1.1%    |
| Samsung Electronics        | 3         | 0.83%   |
| Nvidia                     | 3         | 0.83%   |
| Xiaomi                     | 2         | 0.55%   |
| Qualcomm                   | 2         | 0.55%   |
| Motorola PCS               | 2         | 0.55%   |
| Marvell Technology Group   | 2         | 0.55%   |
| Hewlett-Packard            | 2         | 0.55%   |
| Broadcom Limited           | 2         | 0.55%   |
| ZTE WCDMA Technologies MSM | 1         | 0.28%   |
| TP-Link                    | 1         | 0.28%   |
| T & A Mobile Phones        | 1         | 0.28%   |
| Lenovo                     | 1         | 0.28%   |
| JMicron Technology         | 1         | 0.28%   |
| ICS Advent                 | 1         | 0.28%   |
| Google                     | 1         | 0.28%   |
| Aquantia                   | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 178       | 47.98%  |
| Realtek RTL8125 2.5GbE Controller                                 | 28        | 7.55%   |
| Intel I211 Gigabit Network Connection                             | 21        | 5.66%   |
| Intel Ethernet Controller I225-V                                  | 13        | 3.5%    |
| Intel Ethernet Connection (7) I219-V                              | 10        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.81%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.81%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.54%   |
| Motorola PCS moto g pure                                          | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.54%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.54%   |
| ZTE WCDMA MSM ZTE BLADE A530                                      | 1         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.27%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.27%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.27%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 343       | 53.51%  |
| WiFi     | 294       | 45.87%  |
| Modem    | 2         | 0.31%   |
| Unknown  | 2         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 206       | 50.74%  |
| WiFi     | 200       | 49.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 211       | 55.38%  |
| 1     | 159       | 41.73%  |
| 3     | 8         | 2.1%    |
| 0     | 3         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 266       | 69.27%  |
| Yes  | 118       | 30.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 143       | 53.16%  |
| Realtek Semiconductor           | 20        | 7.43%   |
| Cambridge Silicon Radio         | 19        | 7.06%   |
| Qualcomm Atheros Communications | 12        | 4.46%   |
| IMC Networks                    | 11        | 4.09%   |
| Broadcom                        | 11        | 4.09%   |
| Apple                           | 11        | 4.09%   |
| Foxconn / Hon Hai               | 10        | 3.72%   |
| Lite-On Technology              | 9         | 3.35%   |
| MediaTek                        | 6         | 2.23%   |
| TP-Link                         | 4         | 1.49%   |
| ASUSTek Computer                | 3         | 1.12%   |
| Edimax Technology               | 2         | 0.74%   |
| Toshiba                         | 1         | 0.37%   |
| Realtek                         | 1         | 0.37%   |
| Ralink                          | 1         | 0.37%   |
| Integrated System Solution      | 1         | 0.37%   |
| Foxconn International           | 1         | 0.37%   |
| Dynex                           | 1         | 0.37%   |
| Dell                            | 1         | 0.37%   |
| Unknown                         | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 41        | 15.24%  |
| Intel AX200 Bluetooth                                   | 35        | 13.01%  |
| Intel AX201 Bluetooth                                   | 24        | 8.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 19        | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 18        | 6.69%   |
| Realtek Bluetooth Radio                                 | 17        | 6.32%   |
| Intel AX210 Bluetooth                                   | 8         | 2.97%   |
| MediaTek Wireless_Device                                | 6         | 2.23%   |
| Intel Bluetooth Device                                  | 6         | 2.23%   |
| Apple Bluetooth Host Controller                         | 6         | 2.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 5         | 1.86%   |
| IMC Networks Wireless_Device                            | 5         | 1.86%   |
| IMC Networks Bluetooth Radio                            | 5         | 1.86%   |
| Foxconn / Hon Hai Wireless_Device                       | 5         | 1.86%   |
| TP-Link UB500 Adapter                                   | 4         | 1.49%   |
| Qualcomm Atheros  Bluetooth Device                      | 4         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                        | 4         | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3         | 1.12%   |
| ASUS ASUS USB-BT500                                     | 3         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2         | 0.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 2         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 2         | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 2         | 0.74%   |
| Lite-On Bluetooth Device                                | 2         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.74%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.74%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2         | 0.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 2         | 0.74%   |
| Apple Bluetooth USB Host Controller                     | 2         | 0.74%   |
| Toshiba Askey Bluetooth Module                          | 1         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 1         | 0.37%   |
| Realtek Bluetooth Radio                                 | 1         | 0.37%   |
| Ralink RT3290 Bluetooth                                 | 1         | 0.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1         | 0.37%   |
| Qualcomm Atheros Bluetooth (AR3011)                     | 1         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                       | 1         | 0.37%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 0.37%   |
| Lite-On Wireless_Device                                 | 1         | 0.37%   |
| Lite-On Bluetooth Radio                                 | 1         | 0.37%   |
| Lite-On BCM43142A0                                      | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 215       | 32.09%  |
| AMD                        | 189       | 28.21%  |
| Nvidia                     | 151       | 22.54%  |
| C-Media Electronics        | 20        | 2.99%   |
| Logitech                   | 13        | 1.94%   |
| Razer USA                  | 7         | 1.04%   |
| SteelSeries ApS            | 6         | 0.9%    |
| Kingston Technology        | 6         | 0.9%    |
| ASUSTek Computer           | 6         | 0.9%    |
| Plantronics                | 5         | 0.75%   |
| JMTek                      | 4         | 0.6%    |
| Creative Labs              | 4         | 0.6%    |
| Sony                       | 3         | 0.45%   |
| Focusrite-Novation         | 3         | 0.45%   |
| Corsair                    | 3         | 0.45%   |
| Blue Microphones           | 3         | 0.45%   |
| TTGK Technology            | 2         | 0.3%    |
| Samson Technologies        | 2         | 0.3%    |
| Realtek Semiconductor      | 2         | 0.3%    |
| Generalplus Technology     | 2         | 0.3%    |
| Creative Technology        | 2         | 0.3%    |
| Audio-Technica             | 2         | 0.3%    |
| Asahi Kasei Microsystems   | 2         | 0.3%    |
| Texas Instruments          | 1         | 0.15%   |
| Tenx Technology            | 1         | 0.15%   |
| SAVITECH                   | 1         | 0.15%   |
| Samsung Electronics        | 1         | 0.15%   |
| ROCCAT                     | 1         | 0.15%   |
| PreSonus Audio Electronics | 1         | 0.15%   |
| Positive Grid              | 1         | 0.15%   |
| Micro Star International   | 1         | 0.15%   |
| MCS                        | 1         | 0.15%   |
| Mark of the Unicorn        | 1         | 0.15%   |
| Lenovo                     | 1         | 0.15%   |
| Hewlett-Packard            | 1         | 0.15%   |
| GN Netcom                  | 1         | 0.15%   |
| Giga-Byte Technology       | 1         | 0.15%   |
| Elgato Systems             | 1         | 0.15%   |
| Cambridge Silicon Radio    | 1         | 0.15%   |
| Astro Gaming               | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 59        | 7.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 48        | 5.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 34        | 4.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 29        | 3.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 3.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 2.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18        | 2.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 17        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17        | 2.09%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 1.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 15        | 1.84%   |
| Nvidia GA104 High Definition Audio Controller                              | 15        | 1.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 1.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 1.84%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 1.35%   |
| AMD Navi 10 HDMI Audio                                                     | 10        | 1.23%   |
| Nvidia TU104 HD Audio Controller                                           | 9         | 1.11%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.98%   |
| Nvidia GA102 High Definition Audio Controller                              | 8         | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.86%   |
| AMD FCH Azalia Controller                                                  | 7         | 0.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.74%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 0.74%   |
| C-Media Electronics USB Audio Device                                       | 6         | 0.74%   |
| Logitech PRO X Wireless Gaming Headset                                     | 5         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 28.72%  |
| Micron Technology   | 13        | 13.83%  |
| SK hynix            | 12        | 12.77%  |
| Kingston            | 9         | 9.57%   |
| Corsair             | 9         | 9.57%   |
| G.Skill             | 5         | 5.32%   |
| Unknown             | 4         | 4.26%   |
| Team                | 4         | 4.26%   |
| Crucial             | 3         | 3.19%   |
| Unknown (ABCD)      | 2         | 2.13%   |
| Transcend           | 1         | 1.06%   |
| Ramaxel Technology  | 1         | 1.06%   |
| Nanya Technology    | 1         | 1.06%   |
| Hewlett-Packard     | 1         | 1.06%   |
| Elpida              | 1         | 1.06%   |
| Asgard              | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.94%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 2         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.96%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1.96%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 2         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.96%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 1.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.96%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.98%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 0.98%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 0.98%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s                    | 1         | 0.98%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.98%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.98%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.98%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 0.98%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.98%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 0.98%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.98%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 0.98%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.98%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 65.38%  |
| DDR3    | 16        | 20.51%  |
| LPDDR4  | 4         | 5.13%   |
| DDR5    | 3         | 3.85%   |
| Unknown | 2         | 2.56%   |
| SDRAM   | 1         | 1.28%   |
| DDR2    | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 51.25%  |
| DIMM         | 33        | 41.25%  |
| Row Of Chips | 6         | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 52.38%  |
| 4096  | 14        | 16.67%  |
| 16384 | 12        | 14.29%  |
| 2048  | 7         | 8.33%   |
| 32768 | 6         | 7.14%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 23.26%  |
| 1600  | 11        | 12.79%  |
| 2667  | 10        | 11.63%  |
| 2400  | 7         | 8.14%   |
| 3600  | 6         | 6.98%   |
| 3266  | 4         | 4.65%   |
| 1333  | 4         | 4.65%   |
| 4800  | 3         | 3.49%   |
| 3866  | 2         | 2.33%   |
| 3466  | 2         | 2.33%   |
| 2933  | 2         | 2.33%   |
| 2133  | 2         | 2.33%   |
| 1066  | 2         | 2.33%   |
| 6400  | 1         | 1.16%   |
| 4267  | 1         | 1.16%   |
| 4266  | 1         | 1.16%   |
| 3800  | 1         | 1.16%   |
| 3733  | 1         | 1.16%   |
| 3400  | 1         | 1.16%   |
| 3334  | 1         | 1.16%   |
| 3000  | 1         | 1.16%   |
| 2800  | 1         | 1.16%   |
| 975   | 1         | 1.16%   |
| 800   | 1         | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 50%     |
| Canon               | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Composite Device   | 1         | 16.67%  |
| Canon TR4500 series        | 1         | 16.67%  |
| Canon PIXMA MX370 Series   | 1         | 16.67%  |
| Brother MFC-L2710DN series | 1         | 16.67%  |
| Brother MFC-J460DW         | 1         | 16.67%  |
| Brother HL-L2370DW series  | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 19.4%   |
| IMC Networks                           | 25        | 12.44%  |
| Logitech                               | 20        | 9.95%   |
| Apple                                  | 15        | 7.46%   |
| Acer                                   | 13        | 6.47%   |
| Sunplus Innovation Technology          | 10        | 4.98%   |
| Microdia                               | 9         | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.48%   |
| Realtek Semiconductor                  | 8         | 3.98%   |
| Syntek                                 | 7         | 3.48%   |
| Quanta                                 | 6         | 2.99%   |
| Sonix Technology                       | 5         | 2.49%   |
| Suyin                                  | 4         | 1.99%   |
| Luxvisions Innotech Limited            | 4         | 1.99%   |
| Lite-On Technology                     | 4         | 1.99%   |
| Microsoft                              | 3         | 1.49%   |
| SunplusIT                              | 2         | 1%      |
| Samsung Electronics                    | 2         | 1%      |
| Hewlett-Packard                        | 2         | 1%      |
| Z-Star Microelectronics                | 1         | 0.5%    |
| YGTek                                  | 1         | 0.5%    |
| Tobii Technology AB                    | 1         | 0.5%    |
| Silicon Motion                         | 1         | 0.5%    |
| Razer USA                              | 1         | 0.5%    |
| Owon                                   | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| Intel                                  | 1         | 0.5%    |
| Importek                               | 1         | 0.5%    |
| Goodong Industry                       | 1         | 0.5%    |
| Generalplus Technology                 | 1         | 0.5%    |
| EVGA                                   | 1         | 0.5%    |
| ARC International                      | 1         | 0.5%    |
| ANYKA                                  | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 13        | 6.37%   |
| Chicony Integrated Camera                           | 9         | 4.41%   |
| Logitech C922 Pro Stream Webcam                     | 6         | 2.94%   |
| Chicony HD WebCam                                   | 6         | 2.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 6         | 2.94%   |
| Syntek Integrated Camera                            | 5         | 2.45%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 2.45%   |
| IMC Networks Integrated Camera                      | 5         | 2.45%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.96%   |
| Logitech HD Pro Webcam C920                         | 4         | 1.96%   |
| Acer Integrated Camera                              | 4         | 1.96%   |
| Acer HD Webcam                                      | 4         | 1.96%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.47%   |
| Realtek USB Camera                                  | 3         | 1.47%   |
| Logitech Webcam C270                                | 3         | 1.47%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.47%   |
| Chicony USB 2.0 Camera                              | 3         | 1.47%   |
| Chicony HP Truevision HD                            | 3         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.47%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.47%   |
| Apple Built-in iSight                               | 3         | 1.47%   |
| Sunplus HD WebCam                                   | 2         | 0.98%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.98%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 0.98%   |
| Realtek Integrated_Webcam_HD                        | 2         | 0.98%   |
| Microsoft LifeCam Cinema                            | 2         | 0.98%   |
| Microdia Integrated Camera                          | 2         | 0.98%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.98%   |
| Logitech StreamCam                                  | 2         | 0.98%   |
| Logitech QuickCam Pro 9000                          | 2         | 0.98%   |
| Lite-On HP HD Webcam                                | 2         | 0.98%   |
| Lite-On HP HD Camera                                | 2         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.98%   |
| Chicony USB2.0 Camera                               | 2         | 0.98%   |
| Chicony EasyCamera                                  | 2         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP IR Camera | 2         | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 0.98%   |
| Apple FaceTime HD Camera                            | 2         | 0.98%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.98%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 12        | 38.71%  |
| Synaptics                          | 8         | 25.81%  |
| Elan Microelectronics              | 5         | 16.13%  |
| Shenzhen Goodix Technology         | 4         | 12.9%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 6.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 19.35%  |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 9.68%   |
| Elan ELAN:Fingerprint                                           | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 6.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 6.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                | 2         | 6.45%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 3.23%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 3.23%   |
| Synaptics WBDI Device                                           | 1         | 3.23%   |
| Synaptics UWP WBDI Device                                       | 1         | 3.23%   |
| Synaptics UWP WBDI                                              | 1         | 3.23%   |
| Synaptics  WBDI                                                 | 1         | 3.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 57.14%  |
| Broadcom              | 2         | 28.57%  |
| Realtek Semiconductor | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 57.14%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 287       | 74.16%  |
| 1     | 79        | 20.41%  |
| 2     | 19        | 4.91%   |
| 3     | 2         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 34        | 27.64%  |
| Graphics card            | 33        | 26.83%  |
| Fingerprint reader       | 31        | 25.2%   |
| Multimedia controller    | 16        | 13.01%  |
| Unassigned class         | 2         | 1.63%   |
| Communication controller | 2         | 1.63%   |
| Bluetooth                | 2         | 1.63%   |
| Sound                    | 1         | 0.81%   |
| Modem                    | 1         | 0.81%   |
| Chipcard                 | 1         | 0.81%   |

