Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 802

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4a6383e886](https://linux-hardware.org/?probe=4a6383e886) | Nov 04, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [b84c515650](https://linux-hardware.org/?probe=b84c515650) | Nov 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [d802042506](https://linux-hardware.org/?probe=d802042506) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [cdda6b5094](https://linux-hardware.org/?probe=cdda6b5094) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [5bec5815bb](https://linux-hardware.org/?probe=5bec5815bb) | Oct 31, 2023 |
| ASRock        | H77 Pro4-M                  | Desktop     | [83aeda3c64](https://linux-hardware.org/?probe=83aeda3c64) | Oct 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [0ff396f5c2](https://linux-hardware.org/?probe=0ff396f5c2) | Oct 29, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bf5f9098d7](https://linux-hardware.org/?probe=bf5f9098d7) | Oct 28, 2023 |
| Intel         | H55                         | Desktop     | [f8788bcc72](https://linux-hardware.org/?probe=f8788bcc72) | Oct 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [92c4516951](https://linux-hardware.org/?probe=92c4516951) | Oct 27, 2023 |
| Acer          | Predator PH317-51           | Notebook    | [941e333a3b](https://linux-hardware.org/?probe=941e333a3b) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [50b7d4272d](https://linux-hardware.org/?probe=50b7d4272d) | Oct 26, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4b2be75f68](https://linux-hardware.org/?probe=4b2be75f68) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4323d57b2f](https://linux-hardware.org/?probe=4323d57b2f) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [959fc54e2b](https://linux-hardware.org/?probe=959fc54e2b) | Oct 23, 2023 |
| Lenovo        | ThinkPad T460s 20F90060G... | Notebook    | [b44ed99aff](https://linux-hardware.org/?probe=b44ed99aff) | Oct 22, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [73fdacf30c](https://linux-hardware.org/?probe=73fdacf30c) | Oct 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [5902fdf35f](https://linux-hardware.org/?probe=5902fdf35f) | Oct 18, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [e30927f66e](https://linux-hardware.org/?probe=e30927f66e) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [52151555cb](https://linux-hardware.org/?probe=52151555cb) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [d1ce4588e7](https://linux-hardware.org/?probe=d1ce4588e7) | Oct 11, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [bc5016980d](https://linux-hardware.org/?probe=bc5016980d) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [49d0e884bb](https://linux-hardware.org/?probe=49d0e884bb) | Oct 08, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3d613c96a8](https://linux-hardware.org/?probe=3d613c96a8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [61579851ef](https://linux-hardware.org/?probe=61579851ef) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9410b590b4](https://linux-hardware.org/?probe=9410b590b4) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [2a6facae05](https://linux-hardware.org/?probe=2a6facae05) | Oct 05, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [e7906b9cd7](https://linux-hardware.org/?probe=e7906b9cd7) | Oct 04, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [1c7bef5950](https://linux-hardware.org/?probe=1c7bef5950) | Oct 04, 2023 |
| Intel         | X99                         | Desktop     | [67ec0ac8d0](https://linux-hardware.org/?probe=67ec0ac8d0) | Oct 02, 2023 |
| Unknown       | TB-5000                     | Desktop     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| AMI           | Intel                       | Notebook    | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| HP            | 1998                        | Desktop     | [60208f6be9](https://linux-hardware.org/?probe=60208f6be9) | Sep 22, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [5995975e04](https://linux-hardware.org/?probe=5995975e04) | Sep 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [623cd3e438](https://linux-hardware.org/?probe=623cd3e438) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [78ddadfb89](https://linux-hardware.org/?probe=78ddadfb89) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [3145861387](https://linux-hardware.org/?probe=3145861387) | Sep 12, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [b037f9322d](https://linux-hardware.org/?probe=b037f9322d) | Sep 10, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [647634e7fb](https://linux-hardware.org/?probe=647634e7fb) | Sep 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5330a96ef6](https://linux-hardware.org/?probe=5330a96ef6) | Sep 07, 2023 |
| Matsushita... | CF-74JCJBDAM                | Notebook    | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9441e027c6](https://linux-hardware.org/?probe=9441e027c6) | Sep 04, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [10951f0a65](https://linux-hardware.org/?probe=10951f0a65) | Sep 01, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [ac6c5c8969](https://linux-hardware.org/?probe=ac6c5c8969) | Sep 01, 2023 |
| MOTION        | NVX00                       | Notebook    | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5d571876c8](https://linux-hardware.org/?probe=5d571876c8) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fde9e1a454](https://linux-hardware.org/?probe=fde9e1a454) | Aug 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [4a81412fdd](https://linux-hardware.org/?probe=4a81412fdd) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [0657120653](https://linux-hardware.org/?probe=0657120653) | Aug 19, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | Notebook    | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [9c90e63339](https://linux-hardware.org/?probe=9c90e63339) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f0b1f6f364](https://linux-hardware.org/?probe=f0b1f6f364) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ef08441bc9](https://linux-hardware.org/?probe=ef08441bc9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [68fff65eee](https://linux-hardware.org/?probe=68fff65eee) | Aug 10, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [81a2d0415e](https://linux-hardware.org/?probe=81a2d0415e) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [de06cea570](https://linux-hardware.org/?probe=de06cea570) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [4275d43a74](https://linux-hardware.org/?probe=4275d43a74) | Aug 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [65343a7900](https://linux-hardware.org/?probe=65343a7900) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [af88e64084](https://linux-hardware.org/?probe=af88e64084) | Aug 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b736ced64](https://linux-hardware.org/?probe=6b736ced64) | Aug 03, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [4d98867c44](https://linux-hardware.org/?probe=4d98867c44) | Aug 02, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [675811747f](https://linux-hardware.org/?probe=675811747f) | Aug 02, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ba2cec8099](https://linux-hardware.org/?probe=ba2cec8099) | Aug 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [cdbcf58dcb](https://linux-hardware.org/?probe=cdbcf58dcb) | Jul 30, 2023 |
| HP            | ENVY Notebook               | Notebook    | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2dbda5ea48](https://linux-hardware.org/?probe=2dbda5ea48) | Jul 29, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| Alienware     | 13 R3                       | Notebook    | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| Biostar       | B350GT3                     | Desktop     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Alienware     | 07W25T A00                  | Desktop     | [24dade96af](https://linux-hardware.org/?probe=24dade96af) | Jul 21, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5d2c798252](https://linux-hardware.org/?probe=5d2c798252) | Jul 21, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [79ab32a714](https://linux-hardware.org/?probe=79ab32a714) | Jul 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [228fca7e43](https://linux-hardware.org/?probe=228fca7e43) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [eb85c87997](https://linux-hardware.org/?probe=eb85c87997) | Jul 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| HP            | 8053                        | Desktop     | [4241a715e6](https://linux-hardware.org/?probe=4241a715e6) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [5e8900dde2](https://linux-hardware.org/?probe=5e8900dde2) | Jul 02, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [b819a1fb21](https://linux-hardware.org/?probe=b819a1fb21) | Jul 02, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [fe1c9de1b6](https://linux-hardware.org/?probe=fe1c9de1b6) | Jul 02, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [529873f796](https://linux-hardware.org/?probe=529873f796) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [047aac4298](https://linux-hardware.org/?probe=047aac4298) | Jun 25, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [88e2f62c6d](https://linux-hardware.org/?probe=88e2f62c6d) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2278cd4d03](https://linux-hardware.org/?probe=2278cd4d03) | Jun 17, 2023 |
| Biostar       | B350GT3                     | Desktop     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| Dell          | Latitude E6510              | Notebook    | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Dell          | Precision 5520              | Notebook    | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | Desktop     | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| MICROBYTE     | ezbook                      | Notebook    | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Win elemen... | M600                        | Desktop     | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | Notebook    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | Notebook    | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [182acb48b9](https://linux-hardware.org/?probe=182acb48b9) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a0e44bf0d1](https://linux-hardware.org/?probe=a0e44bf0d1) | Apr 13, 2023 |
| Win elemen... | M600                        | Desktop     | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | 8053                        | Desktop     | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | 8053                        | Desktop     | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| HP            | 8053                        | Desktop     | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | Desktop     | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | Desktop     | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| HP            | Unknown                     | Notebook    | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| MobileDema... | xTablet T1200               | Notebook    | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | Notebook    | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | Notebook    | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | Notebook    | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | Notebook    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [1c406a3696](https://linux-hardware.org/?probe=1c406a3696) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [08ac155787](https://linux-hardware.org/?probe=08ac155787) | Dec 31, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Intel         | H61                         | Desktop     | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8fe5127ba0](https://linux-hardware.org/?probe=8fe5127ba0) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| Alienware     | m15 R7                      | Notebook    | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a7f86279b6](https://linux-hardware.org/?probe=a7f86279b6) | Dec 04, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [2a5b05500a](https://linux-hardware.org/?probe=2a5b05500a) | Nov 11, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [f0b3051737](https://linux-hardware.org/?probe=f0b3051737) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | Notebook    | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | Desktop     | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1c50c72b71](https://linux-hardware.org/?probe=1c50c72b71) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | Notebook    | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f9fbb00a0b](https://linux-hardware.org/?probe=f9fbb00a0b) | Aug 23, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [822e93c1db](https://linux-hardware.org/?probe=822e93c1db) | Aug 02, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Garuda_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 349       | 63.8%   |
| Garuda Linux         | 107       | 19.56%  |
| Garuda Linux Rolling | 91        | 16.64%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 538       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.1.1-zen1-1-zen   | 13        | 2.09%   |
| 6.0.2-zen1-1-zen   | 11        | 1.77%   |
| 6.4.12-zen1-1-zen  | 9         | 1.44%   |
| 6.2.13-zen-1-zen   | 9         | 1.44%   |
| 5.17.1-zen1-1-zen  | 9         | 1.44%   |
| 6.5.9-zen2-1-zen   | 7         | 1.12%   |
| 6.4.10-zen2-1-zen  | 7         | 1.12%   |
| 5.15.2-zen1-1-zen  | 7         | 1.12%   |
| 5.14.14-zen1-1-zen | 7         | 1.12%   |
| 6.2.10-zen1-1-zen  | 6         | 0.96%   |
| 5.17.9-zen1-1-zen  | 6         | 0.96%   |
| 5.16.4-zen1-1-zen  | 6         | 0.96%   |
| 6.5.5-zen1-1-zen   | 5         | 0.8%    |
| 6.3.8-zen1-1-zen   | 5         | 0.8%    |
| 6.2.7-zen1-1-zen   | 5         | 0.8%    |
| 6.2.12-zen1-1-zen  | 5         | 0.8%    |
| 6.1.7-zen1-1-zen   | 5         | 0.8%    |
| 6.0.9-zen1-1-zen   | 5         | 0.8%    |
| 6.0.8-zen1-1-zen   | 5         | 0.8%    |
| 6.0.12-zen1-1-zen  | 5         | 0.8%    |
| 5.18.16-zen1-1-zen | 5         | 0.8%    |
| 5.15.7-zen1-1-zen  | 5         | 0.8%    |
| 5.15.13-zen1-1-zen | 5         | 0.8%    |
| 5.15.12-zen1-1-zen | 5         | 0.8%    |
| 5.13.9-zen1-1-zen  | 5         | 0.8%    |
| 5.13.13-zen1-1-zen | 5         | 0.8%    |
| 5.11.16-zen1-1-zen | 5         | 0.8%    |
| 5.11.11-zen1-1-zen | 5         | 0.8%    |
| 6.5.7-zen2-1-zen   | 4         | 0.64%   |
| 6.5.2-zen1-1-zen   | 4         | 0.64%   |
| 6.4.9-zen1-1-zen   | 4         | 0.64%   |
| 6.4.11-zen2-1-zen  | 4         | 0.64%   |
| 6.3.2-zen1-1-zen   | 4         | 0.64%   |
| 6.1.12-zen1-1-zen  | 4         | 0.64%   |
| 6.0.6-zen1-1-zen   | 4         | 0.64%   |
| 6.0.11-zen1-1-zen  | 4         | 0.64%   |
| 6.0.10-zen2-1-zen  | 4         | 0.64%   |
| 5.19.7-zen2-1-zen  | 4         | 0.64%   |
| 5.18.6-zen1-1-zen  | 4         | 0.64%   |
| 5.18.12-zen1-1-zen | 4         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.1   | 14        | 2.25%   |
| 6.0.2   | 12        | 1.93%   |
| 5.17.1  | 11        | 1.77%   |
| 6.4.12  | 9         | 1.44%   |
| 6.2.13  | 9         | 1.44%   |
| 6.5.9   | 8         | 1.28%   |
| 6.4.10  | 8         | 1.28%   |
| 6.5.5   | 7         | 1.12%   |
| 6.2.10  | 7         | 1.12%   |
| 5.15.2  | 7         | 1.12%   |
| 5.14.14 | 7         | 1.12%   |
| 6.2.7   | 6         | 0.96%   |
| 6.1.9   | 6         | 0.96%   |
| 6.0.8   | 6         | 0.96%   |
| 5.18.16 | 6         | 0.96%   |
| 5.17.9  | 6         | 0.96%   |
| 5.17.5  | 6         | 0.96%   |
| 5.17.3  | 6         | 0.96%   |
| 5.16.4  | 6         | 0.96%   |
| 5.15.7  | 6         | 0.96%   |
| 5.11.11 | 6         | 0.96%   |
| 5.10.4  | 6         | 0.96%   |
| 6.5.7   | 5         | 0.8%    |
| 6.4.3   | 5         | 0.8%    |
| 6.4.11  | 5         | 0.8%    |
| 6.3.8   | 5         | 0.8%    |
| 6.3.1   | 5         | 0.8%    |
| 6.2.12  | 5         | 0.8%    |
| 6.1.7   | 5         | 0.8%    |
| 6.0.9   | 5         | 0.8%    |
| 6.0.12  | 5         | 0.8%    |
| 6.0.11  | 5         | 0.8%    |
| 6.0.10  | 5         | 0.8%    |
| 5.19.7  | 5         | 0.8%    |
| 5.16.5  | 5         | 0.8%    |
| 5.16.2  | 5         | 0.8%    |
| 5.15.13 | 5         | 0.8%    |
| 5.15.12 | 5         | 0.8%    |
| 5.13.9  | 5         | 0.8%    |
| 5.13.13 | 5         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 60        | 9.97%   |
| 5.15    | 54        | 8.97%   |
| 6.4     | 50        | 8.31%   |
| 6.0     | 48        | 7.97%   |
| 6.2     | 41        | 6.81%   |
| 5.16    | 41        | 6.81%   |
| 5.18    | 36        | 5.98%   |
| 5.10    | 36        | 5.98%   |
| 6.5     | 33        | 5.48%   |
| 5.19    | 32        | 5.32%   |
| 5.17    | 31        | 5.15%   |
| 5.14    | 27        | 4.49%   |
| 6.3     | 24        | 3.99%   |
| 5.12    | 23        | 3.82%   |
| 5.11    | 23        | 3.82%   |
| 5.13    | 21        | 3.49%   |
| 5.9     | 13        | 2.16%   |
| 5.8     | 5         | 0.83%   |
| 6.6     | 2         | 0.33%   |
| 5.6     | 1         | 0.17%   |
| 5.4     | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 538       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 376       | 68.74%  |
| GNOME             | 66        | 12.07%  |
| KDE               | 35        | 6.4%    |
| XFCE              | 27        | 4.94%   |
| X-Cinnamon        | 13        | 2.38%   |
| sway              | 7         | 1.28%   |
| LXQt              | 3         | 0.55%   |
| Deepin            | 3         | 0.55%   |
| Unknown           | 3         | 0.55%   |
| qtile-default     | 2         | 0.37%   |
| qtile             | 2         | 0.37%   |
| MATE              | 2         | 0.37%   |
| i3                | 2         | 0.37%   |
| Yaru:ubuntu:GNOME | 1         | 0.18%   |
| Unity             | 1         | 0.18%   |
| Hyprland          | 1         | 0.18%   |
| Cinnamon          | 1         | 0.18%   |
| Budgie            | 1         | 0.18%   |
| awesome           | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 477       | 87.2%   |
| Wayland | 50        | 9.14%   |
| Tty     | 10        | 1.83%   |
| Unknown | 10        | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 259       | 47.52%  |
| Unknown | 193       | 35.41%  |
| LightDM | 50        | 9.17%   |
| GDM     | 37        | 6.79%   |
| GREETD  | 6         | 1.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 276       | 50.92%  |
| en_GB | 54        | 9.96%   |
| de_DE | 40        | 7.38%   |
| en_IN | 24        | 4.43%   |
| en_CA | 19        | 3.51%   |
| it_IT | 18        | 3.32%   |
| pt_BR | 12        | 2.21%   |
| es_ES | 10        | 1.85%   |
| pl_PL | 8         | 1.48%   |
| nl_NL | 7         | 1.29%   |
| ru_RU | 6         | 1.11%   |
| es_MX | 6         | 1.11%   |
| fr_FR | 5         | 0.92%   |
| tr_TR | 4         | 0.74%   |
| en_AU | 4         | 0.74%   |
| en_ZA | 3         | 0.55%   |
| en_DK | 3         | 0.55%   |
| de_AT | 3         | 0.55%   |
| sv_SE | 2         | 0.37%   |
| sk_SK | 2         | 0.37%   |
| ja_JP | 2         | 0.37%   |
| fr_BE | 2         | 0.37%   |
| fi_FI | 2         | 0.37%   |
| es_VE | 2         | 0.37%   |
| es_EC | 2         | 0.37%   |
| es_CO | 2         | 0.37%   |
| es_AR | 2         | 0.37%   |
| en_AG | 2         | 0.37%   |
| da_DK | 2         | 0.37%   |
| zh_CN | 1         | 0.18%   |
| uk_UA | 1         | 0.18%   |
| nl_BE | 1         | 0.18%   |
| nb_NO | 1         | 0.18%   |
| ko_KR | 1         | 0.18%   |
| iu_CA | 1         | 0.18%   |
| hu_HU | 1         | 0.18%   |
| fr_CA | 1         | 0.18%   |
| es_PE | 1         | 0.18%   |
| es_CL | 1         | 0.18%   |
| es_BO | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 331       | 61.07%  |
| BIOS | 211       | 38.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 521       | 96.84%  |
| Overlay | 9         | 1.67%   |
| Tmpfs   | 3         | 0.56%   |
| Ext4    | 2         | 0.37%   |
| XXXXX   | 1         | 0.19%   |
| Xfs     | 1         | 0.19%   |
| F2fs    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 331       | 61.07%  |
| Unknown | 190       | 35.06%  |
| MBR     | 21        | 3.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 466       | 85.35%  |
| Yes       | 80        | 14.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 365       | 66.73%  |
| Yes       | 182       | 33.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 110       | 20.45%  |
| Lenovo                               | 76        | 14.13%  |
| Hewlett-Packard                      | 74        | 13.75%  |
| MSI                                  | 48        | 8.92%   |
| Dell                                 | 46        | 8.55%   |
| Gigabyte Technology                  | 38        | 7.06%   |
| Acer                                 | 34        | 6.32%   |
| ASRock                               | 23        | 4.28%   |
| Apple                                | 13        | 2.42%   |
| Samsung Electronics                  | 5         | 0.93%   |
| Intel                                | 5         | 0.93%   |
| HUAWEI                               | 5         | 0.93%   |
| Alienware                            | 5         | 0.93%   |
| Unknown                              | 5         | 0.93%   |
| Notebook                             | 4         | 0.74%   |
| Fujitsu                              | 4         | 0.74%   |
| Razer                                | 3         | 0.56%   |
| Medion                               | 3         | 0.56%   |
| AZW                                  | 3         | 0.56%   |
| XIAOMI                               | 2         | 0.37%   |
| Toshiba                              | 2         | 0.37%   |
| Sony                                 | 2         | 0.37%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.37%   |
| Pegatron                             | 2         | 0.37%   |
| HONOR                                | 2         | 0.37%   |
| Biostar                              | 2         | 0.37%   |
| Win element                          | 1         | 0.19%   |
| T-bao                                | 1         | 0.19%   |
| Standard                             | 1         | 0.19%   |
| PC Specialist                        | 1         | 0.19%   |
| Panasonic                            | 1         | 0.19%   |
| OEM                                  | 1         | 0.19%   |
| MOTION                               | 1         | 0.19%   |
| Monster                              | 1         | 0.19%   |
| MobileDemand                         | 1         | 0.19%   |
| Microsoft                            | 1         | 0.19%   |
| MICROBYTE                            | 1         | 0.19%   |
| Matsushita Electric Industrial       | 1         | 0.19%   |
| Kogan                                | 1         | 0.19%   |
| GPU Company                          | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 9         | 1.67%   |
| ASUS TUF Gaming X570-PLUS             | 7         | 1.3%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 5         | 0.93%   |
| Apple MacBookPro9,2                   | 4         | 0.74%   |
| MSI MS-7C91                           | 3         | 0.56%   |
| MSI MS-7B86                           | 3         | 0.56%   |
| AZW SER                               | 3         | 0.56%   |
| ASUS All Series                       | 3         | 0.56%   |
| XIAOMI Redmi Book Pro 15 2023         | 2         | 0.37%   |
| MSI MS-7D75                           | 2         | 0.37%   |
| MSI MS-7C37                           | 2         | 0.37%   |
| MSI MS-7C02                           | 2         | 0.37%   |
| Lenovo ThinkPad W530 24474KG          | 2         | 0.37%   |
| HUAWEI HVY-WXX9                       | 2         | 0.37%   |
| HP ProDesk 600 G1 SFF                 | 2         | 0.37%   |
| HP ProBook 640 G1                     | 2         | 0.37%   |
| HP Pavilion Laptop 15-cc1xx           | 2         | 0.37%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 2         | 0.37%   |
| HP Pavilion Gaming Desktop 690-00xx   | 2         | 0.37%   |
| HP Pavilion dv6                       | 2         | 0.37%   |
| HP OMEN Laptop 15-en0xxx              | 2         | 0.37%   |
| HP OMEN by Laptop 15-dh1xxx           | 2         | 0.37%   |
| HP Notebook                           | 2         | 0.37%   |
| HP Laptop 15-dy2xxx                   | 2         | 0.37%   |
| HP Laptop 15-da0xxx                   | 2         | 0.37%   |
| HP EliteDesk 800 G1 SFF               | 2         | 0.37%   |
| Gigabyte X570 AORUS PRO WIFI          | 2         | 0.37%   |
| Gigabyte G5 MD                        | 2         | 0.37%   |
| Gigabyte B550 AORUS PRO AC            | 2         | 0.37%   |
| Gigabyte AB350-Gaming 3               | 2         | 0.37%   |
| Dell XPS 15 9500                      | 2         | 0.37%   |
| Dell OptiPlex 7010                    | 2         | 0.37%   |
| Dell Latitude E6420                   | 2         | 0.37%   |
| Dell Inspiron 3668                    | 2         | 0.37%   |
| Dell Inspiron 15 7000 Gaming          | 2         | 0.37%   |
| ASUS TUF Gaming FX505DT_FX505DT       | 2         | 0.37%   |
| ASUS TUF Gaming B550-PLUS WIFI II     | 2         | 0.37%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR | 2         | 0.37%   |
| ASUS ROG STRIX X570-E GAMING          | 2         | 0.37%   |
| ASUS ROG STRIX B550-F GAMING          | 2         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 26        | 4.83%   |
| Lenovo ThinkPad    | 23        | 4.28%   |
| Lenovo IdeaPad     | 21        | 3.9%    |
| Acer Aspire        | 19        | 3.53%   |
| HP Pavilion        | 18        | 3.35%   |
| Dell Inspiron      | 17        | 3.16%   |
| ASUS TUF           | 17        | 3.16%   |
| ASUS PRIME         | 16        | 2.97%   |
| ASUS VivoBook      | 12        | 2.23%   |
| Lenovo Legion      | 11        | 2.04%   |
| HP Laptop          | 10        | 1.86%   |
| Dell Latitude      | 10        | 1.86%   |
| Unknown            | 9         | 1.67%   |
| HP OMEN            | 8         | 1.49%   |
| Dell XPS           | 6         | 1.12%   |
| Dell Precision     | 6         | 1.12%   |
| Acer Nitro         | 6         | 1.12%   |
| Lenovo Yoga        | 5         | 0.93%   |
| Lenovo ThinkCentre | 5         | 0.93%   |
| HP EliteBook       | 5         | 0.93%   |
| Gigabyte X570      | 5         | 0.93%   |
| Dell OptiPlex      | 5         | 0.93%   |
| Apple MacBookPro9  | 5         | 0.93%   |
| HP ENVY            | 4         | 0.74%   |
| HP EliteDesk       | 4         | 0.74%   |
| Gigabyte B550      | 4         | 0.74%   |
| ASUS Zenbook       | 4         | 0.74%   |
| Acer Swift         | 4         | 0.74%   |
| Razer Blade        | 3         | 0.56%   |
| MSI MS-7C91        | 3         | 0.56%   |
| MSI MS-7B86        | 3         | 0.56%   |
| HP ProBook         | 3         | 0.56%   |
| HP Compaq          | 3         | 0.56%   |
| Gigabyte G5        | 3         | 0.56%   |
| Gigabyte B450      | 3         | 0.56%   |
| AZW SER            | 3         | 0.56%   |
| ASUS ASUS          | 3         | 0.56%   |
| ASUS All           | 3         | 0.56%   |
| XIAOMI Redmi       | 2         | 0.37%   |
| Toshiba Satellite  | 2         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 83        | 15.43%  |
| 2021    | 72        | 13.38%  |
| 2019    | 61        | 11.34%  |
| 2018    | 49        | 9.11%   |
| 2017    | 44        | 8.18%   |
| 2022    | 40        | 7.43%   |
| 2013    | 34        | 6.32%   |
| 2012    | 33        | 6.13%   |
| 2016    | 28        | 5.2%    |
| 2014    | 28        | 5.2%    |
| 2011    | 18        | 3.35%   |
| 2015    | 16        | 2.97%   |
| 2023    | 8         | 1.49%   |
| 2010    | 8         | 1.49%   |
| 2009    | 7         | 1.3%    |
| 2008    | 5         | 0.93%   |
| 2007    | 3         | 0.56%   |
| Unknown | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 294       | 54.65%  |
| Desktop     | 213       | 39.59%  |
| Convertible | 17        | 3.16%   |
| Mini pc     | 6         | 1.12%   |
| All in one  | 5         | 0.93%   |
| Tablet      | 3         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 538       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 537       | 99.81%  |
| Yes  | 1         | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 136       | 25.05%  |
| 8.01-16.0   | 115       | 21.18%  |
| 4.01-8.0    | 113       | 20.81%  |
| 32.01-64.0  | 103       | 18.97%  |
| 3.01-4.0    | 30        | 5.52%   |
| 24.01-32.0  | 24        | 4.42%   |
| 64.01-256.0 | 21        | 3.87%   |
| 2.01-3.0    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 208       | 35.74%  |
| 3.01-4.0    | 139       | 23.88%  |
| 2.01-3.0    | 122       | 20.96%  |
| 8.01-16.0   | 60        | 10.31%  |
| 1.01-2.0    | 39        | 6.7%    |
| 16.01-24.0  | 10        | 1.72%   |
| 32.01-64.0  | 2         | 0.34%   |
| 64.01-256.0 | 1         | 0.17%   |
| 0.51-1.0    | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 239       | 43.22%  |
| 2      | 168       | 30.38%  |
| 3      | 75        | 13.56%  |
| 4      | 34        | 6.15%   |
| 5      | 19        | 3.44%   |
| 6      | 8         | 1.45%   |
| 9      | 4         | 0.72%   |
| 7      | 2         | 0.36%   |
| 18     | 1         | 0.18%   |
| 14     | 1         | 0.18%   |
| 11     | 1         | 0.18%   |
| 0      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 411       | 75.69%  |
| Yes       | 132       | 24.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 451       | 83.67%  |
| No        | 88        | 16.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 444       | 81.62%  |
| No        | 100       | 18.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 399       | 73.48%  |
| No        | 144       | 26.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 152       | 28.1%   |
| Germany      | 60        | 11.09%  |
| Italy        | 30        | 5.55%   |
| India        | 29        | 5.36%   |
| UK           | 28        | 5.18%   |
| Canada       | 27        | 4.99%   |
| Brazil       | 18        | 3.33%   |
| Poland       | 16        | 2.96%   |
| Spain        | 12        | 2.22%   |
| Netherlands  | 12        | 2.22%   |
| France       | 9         | 1.66%   |
| Turkey       | 8         | 1.48%   |
| Sweden       | 8         | 1.48%   |
| Russia       | 8         | 1.48%   |
| Mexico       | 8         | 1.48%   |
| Romania      | 7         | 1.29%   |
| Belgium      | 7         | 1.29%   |
| Denmark      | 6         | 1.11%   |
| Australia    | 5         | 0.92%   |
| Switzerland  | 4         | 0.74%   |
| South Africa | 4         | 0.74%   |
| Japan        | 4         | 0.74%   |
| Finland      | 4         | 0.74%   |
| Austria      | 4         | 0.74%   |
| Singapore    | 3         | 0.55%   |
| Serbia       | 3         | 0.55%   |
| Norway       | 3         | 0.55%   |
| Latvia       | 3         | 0.55%   |
| Czechia      | 3         | 0.55%   |
| Colombia     | 3         | 0.55%   |
| Argentina    | 3         | 0.55%   |
| Venezuela    | 2         | 0.37%   |
| Slovenia     | 2         | 0.37%   |
| Slovakia     | 2         | 0.37%   |
| Puerto Rico  | 2         | 0.37%   |
| Portugal     | 2         | 0.37%   |
| Philippines  | 2         | 0.37%   |
| Lithuania    | 2         | 0.37%   |
| Kuwait       | 2         | 0.37%   |
| Kenya        | 2         | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Berlin             | 7         | 1.24%   |
| Milan              | 5         | 0.89%   |
| London             | 5         | 0.89%   |
| Warsaw             | 4         | 0.71%   |
| Mississauga        | 4         | 0.71%   |
| Istanbul           | 4         | 0.71%   |
| Hyderabad          | 4         | 0.71%   |
| Frankfurt am Main  | 4         | 0.71%   |
| Düsseldorf        | 4         | 0.71%   |
| Dallas             | 4         | 0.71%   |
| Copenhagen         | 4         | 0.71%   |
| Cape Town          | 4         | 0.71%   |
| Toronto            | 3         | 0.53%   |
| Singapore          | 3         | 0.53%   |
| San Jose           | 3         | 0.53%   |
| Riga               | 3         | 0.53%   |
| Prague             | 3         | 0.53%   |
| Portland           | 3         | 0.53%   |
| Mumbai             | 3         | 0.53%   |
| Montreal           | 3         | 0.53%   |
| Los Angeles        | 3         | 0.53%   |
| Kansas City        | 3         | 0.53%   |
| Florence           | 3         | 0.53%   |
| Fayetteville       | 3         | 0.53%   |
| Drums              | 3         | 0.53%   |
| Chicago            | 3         | 0.53%   |
| Bengaluru          | 3         | 0.53%   |
| Belo Horizonte     | 3         | 0.53%   |
| Atlanta            | 3         | 0.53%   |
| Wroclaw            | 2         | 0.35%   |
| Wasmes             | 2         | 0.35%   |
| Valencia           | 2         | 0.35%   |
| Turin              | 2         | 0.35%   |
| Timișoara         | 2         | 0.35%   |
| Sydney             | 2         | 0.35%   |
| Sulzbach-Rosenberg | 2         | 0.35%   |
| Stockholm          | 2         | 0.35%   |
| St Louis           | 2         | 0.35%   |
| Southwark          | 2         | 0.35%   |
| Seattle            | 2         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 165       | 280    | 16.65%  |
| Seagate                     | 130       | 185    | 13.12%  |
| WDC                         | 126       | 189    | 12.71%  |
| SanDisk                     | 71        | 88     | 7.16%   |
| Toshiba                     | 59        | 78     | 5.95%   |
| Kingston                    | 44        | 59     | 4.44%   |
| SK hynix                    | 38        | 51     | 3.83%   |
| Crucial                     | 37        | 47     | 3.73%   |
| Intel                       | 26        | 35     | 2.62%   |
| Unknown                     | 24        | 25     | 2.42%   |
| HGST                        | 20        | 26     | 2.02%   |
| Hitachi                     | 19        | 20     | 1.92%   |
| Micron Technology           | 17        | 19     | 1.72%   |
| Micron/Crucial Technology   | 14        | 18     | 1.41%   |
| Silicon Motion              | 13        | 13     | 1.31%   |
| Phison Electronics          | 13        | 17     | 1.31%   |
| SPCC                        | 10        | 11     | 1.01%   |
| Phison                      | 10        | 11     | 1.01%   |
| KIOXIA                      | 9         | 11     | 0.91%   |
| A-DATA Technology           | 9         | 13     | 0.91%   |
| PNY                         | 8         | 8      | 0.81%   |
| China                       | 8         | 11     | 0.81%   |
| Kingston Technology Company | 7         | 7      | 0.71%   |
| ADATA Technology            | 7         | 9      | 0.71%   |
| Intenso                     | 5         | 6      | 0.5%    |
| Hewlett-Packard             | 5         | 5      | 0.5%    |
| Apple                       | 5         | 6      | 0.5%    |
| Patriot                     | 4         | 5      | 0.4%    |
| OCZ                         | 4         | 4      | 0.4%    |
| LITEONIT                    | 4         | 4      | 0.4%    |
| LITEON                      | 4         | 4      | 0.4%    |
| Corsair                     | 4         | 7      | 0.4%    |
| XPG                         | 3         | 4      | 0.3%    |
| Transcend                   | 3         | 3      | 0.3%    |
| Team                        | 3         | 4      | 0.3%    |
| SABRENT                     | 3         | 6      | 0.3%    |
| Realtek Semiconductor       | 3         | 5      | 0.3%    |
| MAXIO Technology (Hangzhou) | 3         | 3      | 0.3%    |
| JMicron Technology          | 3         | 3      | 0.3%    |
| Emtec                       | 3         | 5      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                 | 24        | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 15        | 1.34%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 14        | 1.25%   |
| Samsung NVMe SSD Drive 1TB                                        | 12        | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 10        | 0.9%    |
| Samsung SSD 860 EVO 500GB                                         | 10        | 0.9%    |
| Crucial CT1000MX500SSD1 1TB                                       | 10        | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                                    | 9         | 0.81%   |
| Samsung SSD 850 EVO 250GB                                         | 9         | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 8         | 0.72%   |
| Samsung SSD 860 EVO 1TB                                           | 8         | 0.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB                 | 7         | 0.63%   |
| Samsung SSD 980 1TB                                               | 7         | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 7         | 0.63%   |
| HGST HTS721010A9E630 1TB                                          | 7         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 6         | 0.54%   |
| SanDisk SSD PLUS 1000GB                                           | 6         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB                                    | 6         | 0.54%   |
| Kingston SA400S37240G 240GB SSD                                   | 6         | 0.54%   |
| Intel SSD 660P Series 1024GB                                      | 6         | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 6         | 0.54%   |
| Unknown MMC Card  64GB                                            | 5         | 0.45%   |
| Toshiba HDWD110 1TB                                               | 5         | 0.45%   |
| Toshiba DT01ACA100 1TB                                            | 5         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 5         | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB                                    | 5         | 0.45%   |
| Samsung SSD 860 QVO 1TB                                           | 5         | 0.45%   |
| Samsung SSD 860 EVO 250GB                                         | 5         | 0.45%   |
| Samsung SSD 850 EVO 500GB                                         | 5         | 0.45%   |
| Samsung NVMe SSD Drive 500GB                                      | 5         | 0.45%   |
| Phison E16 PCIe4 NVMe Controller 500GB                            | 5         | 0.45%   |
| Kingston SA400S37120G 120GB SSD                                   | 5         | 0.45%   |
| Intel SSDPEKNU512GZ 512GB                                         | 5         | 0.45%   |
| Crucial CT500MX500SSD1 500GB                                      | 5         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB                                          | 4         | 0.36%   |
| WDC WD10EZEX-60WN4A0 1TB                                          | 4         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                                          | 4         | 0.36%   |
| Toshiba MQ01ABD100 1TB                                            | 4         | 0.36%   |
| Toshiba DT01ACA050 500GB                                          | 4         | 0.36%   |
| SPCC Solid State Disk 512GB                                       | 4         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 124       | 174    | 38.75%  |
| WDC                 | 93        | 152    | 29.06%  |
| Toshiba             | 45        | 57     | 14.06%  |
| HGST                | 20        | 26     | 6.25%   |
| Hitachi             | 19        | 20     | 5.94%   |
| Samsung Electronics | 6         | 6      | 1.88%   |
| Unknown             | 3         | 3      | 0.94%   |
| Intenso             | 3         | 4      | 0.94%   |
| Apple               | 2         | 2      | 0.63%   |
| SSK                 | 1         | 1      | 0.31%   |
| LaCie               | 1         | 1      | 0.31%   |
| KESU                | 1         | 1      | 0.31%   |
| Hewlett-Packard     | 1         | 1      | 0.31%   |
| ASMedia             | 1         | 2      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 109    | 25%     |
| Crucial             | 32        | 40     | 10.81%  |
| Kingston            | 30        | 38     | 10.14%  |
| SanDisk             | 26        | 37     | 8.78%   |
| WDC                 | 16        | 17     | 5.41%   |
| SPCC                | 9         | 10     | 3.04%   |
| SK hynix            | 9         | 13     | 3.04%   |
| A-DATA Technology   | 9         | 13     | 3.04%   |
| Toshiba             | 8         | 12     | 2.7%    |
| China               | 8         | 11     | 2.7%    |
| PNY                 | 7         | 7      | 2.36%   |
| Micron Technology   | 6         | 7      | 2.03%   |
| OCZ                 | 4         | 4      | 1.35%   |
| LITEONIT            | 4         | 4      | 1.35%   |
| LITEON              | 4         | 4      | 1.35%   |
| Transcend           | 3         | 3      | 1.01%   |
| Team                | 3         | 4      | 1.01%   |
| SABRENT             | 3         | 6      | 1.01%   |
| Patriot             | 3         | 4      | 1.01%   |
| Hewlett-Packard     | 3         | 3      | 1.01%   |
| Emtec               | 3         | 5      | 1.01%   |
| TO Exter            | 2         | 2      | 0.68%   |
| Mushkin             | 2         | 2      | 0.68%   |
| FORESEE             | 2         | 2      | 0.68%   |
| WODPOSIT            | 1         | 2      | 0.34%   |
| WDC WDS             | 1         | 1      | 0.34%   |
| VisionTek           | 1         | 2      | 0.34%   |
| USB30               | 1         | 2      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |
| T-FORCE             | 1         | 1      | 0.34%   |
| SATAFIRM            | 1         | 1      | 0.34%   |
| Qumo                | 1         | 1      | 0.34%   |
| PNY CS90            | 1         | 1      | 0.34%   |
| Plextor             | 1         | 1      | 0.34%   |
| OWC                 | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| Neo                 | 1         | 1      | 0.34%   |
| Lexar               | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.34%   |
| Intenso             | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 309       | 481    | 36.48%  |
| HDD     | 253       | 450    | 29.87%  |
| SSD     | 244       | 386    | 28.81%  |
| Unknown | 21        | 21     | 2.48%   |
| MMC     | 20        | 21     | 2.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 361       | 780    | 48.46%  |
| NVMe | 307       | 478    | 41.21%  |
| SAS  | 57        | 80     | 7.65%   |
| MMC  | 20        | 21     | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 233       | 365    | 42.13%  |
| 0.51-1.0   | 191       | 267    | 34.54%  |
| 1.01-2.0   | 78        | 120    | 14.1%   |
| 2.01-3.0   | 18        | 29     | 3.25%   |
| 3.01-4.0   | 17        | 30     | 3.07%   |
| 4.01-10.0  | 14        | 22     | 2.53%   |
| 10.01-20.0 | 2         | 3      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 250       | 45.45%  |
| 1001-2000      | 101       | 18.36%  |
| 501-1000       | 74        | 13.45%  |
| 2001-3000      | 57        | 10.36%  |
| 251-500        | 26        | 4.73%   |
| Unknown        | 22        | 4%      |
| 1-20           | 14        | 2.55%   |
| 101-250        | 6         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 132       | 23.12%  |
| 251-500        | 94        | 16.46%  |
| 501-1000       | 85        | 14.89%  |
| 1001-2000      | 68        | 11.91%  |
| 51-100         | 60        | 10.51%  |
| More than 3000 | 55        | 9.63%   |
| 2001-3000      | 36        | 6.3%    |
| Unknown        | 22        | 3.85%   |
| 1-20           | 15        | 2.63%   |
| 21-50          | 4         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB              | 2         | 2      | 3.28%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 3.28%   |
| Intenso USB 3.0 device 5TB            | 2         | 2      | 3.28%   |
| HGST HTS725050A7E630 500GB            | 2         | 5      | 3.28%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 3.28%   |
| WDC WD6400AAKS-65A7B0 640GB           | 1         | 1      | 1.64%   |
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 1.64%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.64%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 2      | 1.64%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 1.64%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 1.64%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 2      | 1.64%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 1.64%   |
| WDC WD2002FAEX-007BA0 2TB             | 1         | 1      | 1.64%   |
| WDC WD15EADS-22P8B0 1TB               | 1         | 2      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.64%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 1.64%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 1.64%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 1.64%   |
| WDC WD10EALX-009BA0 1TB               | 1         | 1      | 1.64%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 1.64%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.64%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.64%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 1.64%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB | 1         | 3      | 1.64%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.64%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.64%   |
| Seagate ST4000DM004-2CV104 4TB        | 1         | 1      | 1.64%   |
| Seagate ST3000DM003-1F216N 3TB        | 1         | 1      | 1.64%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1         | 1      | 1.64%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 2      | 1.64%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 1.64%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.64%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.64%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 1.64%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 980 1TB       | 1         | 7      | 1.64%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 5      | 1.64%   |
| Samsung Electronics SSD 850 PRO 512GB | 1         | 2      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 17        | 22     | 29.82%  |
| Seagate               | 10        | 11     | 17.54%  |
| Hitachi               | 5         | 5      | 8.77%   |
| HGST                  | 5         | 11     | 8.77%   |
| Toshiba               | 3         | 3      | 5.26%   |
| Samsung Electronics   | 3         | 15     | 5.26%   |
| SK hynix              | 2         | 4      | 3.51%   |
| SanDisk               | 2         | 2      | 3.51%   |
| Kingston              | 2         | 2      | 3.51%   |
| Intenso               | 2         | 2      | 3.51%   |
| Realtek Semiconductor | 1         | 2      | 1.75%   |
| OCZ                   | 1         | 1      | 1.75%   |
| Hewlett-Packard       | 1         | 1      | 1.75%   |
| Crucial               | 1         | 1      | 1.75%   |
| Apple                 | 1         | 1      | 1.75%   |
| A-DATA Technology     | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 17        | 22     | 39.53%  |
| Seagate | 10        | 11     | 23.26%  |
| Hitachi | 5         | 5      | 11.63%  |
| HGST    | 5         | 11     | 11.63%  |
| Toshiba | 3         | 3      | 6.98%   |
| Intenso | 2         | 2      | 4.65%   |
| Apple   | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 55     | 73.08%  |
| SSD  | 9         | 10     | 17.31%  |
| NVMe | 5         | 19     | 9.62%   |

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
| Works    | 291       | 631    | 46.56%  |
| Detected | 285       | 644    | 45.6%   |
| Malfunc  | 49        | 84     | 7.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 293       | 36.08%  |
| AMD                            | 170       | 20.94%  |
| Samsung Electronics            | 100       | 12.32%  |
| SanDisk                        | 61        | 7.51%   |
| SK hynix                       | 29        | 3.57%   |
| Phison Electronics             | 27        | 3.33%   |
| Kingston Technology Company    | 23        | 2.83%   |
| Micron/Crucial Technology      | 17        | 2.09%   |
| Silicon Motion                 | 14        | 1.72%   |
| ASMedia Technology             | 13        | 1.6%    |
| Micron Technology              | 10        | 1.23%   |
| ADATA Technology               | 9         | 1.11%   |
| KIOXIA                         | 8         | 0.99%   |
| Toshiba America Info Systems   | 7         | 0.86%   |
| Marvell Technology Group       | 6         | 0.74%   |
| Union Memory (Shenzhen)        | 5         | 0.62%   |
| Realtek Semiconductor          | 4         | 0.49%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.37%   |
| Seagate Technology             | 2         | 0.25%   |
| JMicron Technology             | 2         | 0.25%   |
| Apple                          | 2         | 0.25%   |
| Yangtze Memory Technologies    | 1         | 0.12%   |
| Solid State Storage Technology | 1         | 0.12%   |
| Shenzhen Longsys Electronics   | 1         | 0.12%   |
| Nvidia                         | 1         | 0.12%   |
| LSI Logic / Symbios Logic      | 1         | 0.12%   |
| Lenovo                         | 1         | 0.12%   |
| Broadcom / LSI                 | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 125       | 13.72%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 61        | 6.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 26        | 2.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 24        | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 24        | 2.63%   |
| AMD 400 Series Chipset SATA Controller                                         | 24        | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 23        | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 2.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 1.87%   |
| Phison E12 NVMe Controller                                                     | 14        | 1.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 13        | 1.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 12        | 1.32%   |
| Intel SSD 660P Series                                                          | 11        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.21%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 8         | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                               | 7         | 0.77%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 7         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 0.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                         | 7         | 0.77%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 0.66%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 0.66%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 6         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 399       | 51.09%  |
| NVMe | 305       | 39.05%  |
| RAID | 52        | 6.66%   |
| IDE  | 24        | 3.07%   |
| SAS  | 1         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 318       | 59.11%  |
| AMD    | 220       | 40.89%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 1.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 1.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.67%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8         | 1.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.3%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.3%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.11%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 6         | 1.11%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 1.11%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 1.11%   |
| Intel 12th Gen Core i5-12600K                 | 5         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.93%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 5         | 0.93%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.93%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.74%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.74%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.74%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 0.74%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 4         | 0.74%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 0.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.74%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 4         | 0.74%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.74%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.74%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 3         | 0.56%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 106       | 19.7%   |
| Intel Core i5           | 91        | 16.91%  |
| AMD Ryzen 7             | 78        | 14.5%   |
| AMD Ryzen 5             | 64        | 11.9%   |
| Other                   | 48        | 8.92%   |
| Intel Core i3           | 35        | 6.51%   |
| AMD Ryzen 9             | 28        | 5.2%    |
| Intel Celeron           | 13        | 2.42%   |
| AMD Ryzen 3             | 10        | 1.86%   |
| AMD FX                  | 8         | 1.49%   |
| Intel Xeon              | 7         | 1.3%    |
| Intel Pentium           | 5         | 0.93%   |
| Intel Core 2 Duo        | 5         | 0.93%   |
| AMD Ryzen 7 PRO         | 5         | 0.93%   |
| AMD A8                  | 5         | 0.93%   |
| AMD A10                 | 5         | 0.93%   |
| Intel Pentium Dual-Core | 3         | 0.56%   |
| Intel Core i9           | 3         | 0.56%   |
| AMD Ryzen Threadripper  | 3         | 0.56%   |
| AMD A6                  | 3         | 0.56%   |
| Intel Pentium Silver    | 2         | 0.37%   |
| AMD Phenom II X6        | 2         | 0.37%   |
| AMD A4                  | 2         | 0.37%   |
| Intel Core m3           | 1         | 0.19%   |
| Intel Core 2 Quad       | 1         | 0.19%   |
| AMD Turion              | 1         | 0.19%   |
| AMD Phenom II X4        | 1         | 0.19%   |
| AMD Phenom II X2        | 1         | 0.19%   |
| AMD Athlon X4           | 1         | 0.19%   |
| AMD Athlon              | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 170       | 31.6%   |
| 2      | 136       | 25.28%  |
| 8      | 105       | 19.52%  |
| 6      | 87        | 16.17%  |
| 12     | 15        | 2.79%   |
| 16     | 8         | 1.49%   |
| 10     | 8         | 1.49%   |
| 14     | 5         | 0.93%   |
| 24     | 2         | 0.37%   |
| 20     | 1         | 0.19%   |
| 3      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 536       | 99.63%  |
| 2      | 2         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 454       | 84.39%  |
| 1      | 84        | 15.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 538       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 283       | 51.27%  |
| 0x306a9    | 18        | 3.26%   |
| 0x0a50000c | 17        | 3.08%   |
| 0x206a7    | 14        | 2.54%   |
| 0x08108109 | 12        | 2.17%   |
| 0x306c3    | 11        | 1.99%   |
| 0x08701021 | 11        | 1.99%   |
| 0x806c1    | 10        | 1.81%   |
| 0x906ea    | 9         | 1.63%   |
| 0x0a601203 | 8         | 1.45%   |
| 0x08600106 | 8         | 1.45%   |
| 0x0800820d | 8         | 1.45%   |
| 0x906e9    | 7         | 1.27%   |
| 0x506e3    | 7         | 1.27%   |
| 0xa0652    | 6         | 1.09%   |
| 0x0a50000d | 6         | 1.09%   |
| 0x0a404102 | 6         | 1.09%   |
| 0x0a20120a | 6         | 1.09%   |
| 0x806ea    | 5         | 0.91%   |
| 0x806e9    | 4         | 0.72%   |
| 0x08608103 | 4         | 0.72%   |
| 0x08600103 | 4         | 0.72%   |
| 0xa0653    | 3         | 0.54%   |
| 0x806ec    | 3         | 0.54%   |
| 0x406e3    | 3         | 0.54%   |
| 0x40651    | 3         | 0.54%   |
| 0x0a50000b | 3         | 0.54%   |
| 0x0a201025 | 3         | 0.54%   |
| 0x0a201009 | 3         | 0.54%   |
| 0x08600104 | 3         | 0.54%   |
| 0x08108102 | 3         | 0.54%   |
| 0x08001137 | 3         | 0.54%   |
| 0x06006705 | 3         | 0.54%   |
| 0x906ed    | 2         | 0.36%   |
| 0x906a3    | 2         | 0.36%   |
| 0x90672    | 2         | 0.36%   |
| 0x106e5    | 2         | 0.36%   |
| 0x1067a    | 2         | 0.36%   |
| 0x0a704103 | 2         | 0.36%   |
| 0x0a201204 | 2         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 14.47%  |
| Zen 3            | 59        | 10.95%  |
| Zen 2            | 50        | 9.28%   |
| Unknown          | 43        | 7.98%   |
| Zen+             | 38        | 7.05%   |
| IvyBridge        | 38        | 7.05%   |
| Haswell          | 36        | 6.68%   |
| Skylake          | 27        | 5.01%   |
| SandyBridge      | 27        | 5.01%   |
| CometLake        | 22        | 4.08%   |
| TigerLake        | 18        | 3.34%   |
| Zen              | 14        | 2.6%    |
| Alderlake Hybrid | 11        | 2.04%   |
| Piledriver       | 10        | 1.86%   |
| Broadwell        | 10        | 1.86%   |
| Penryn           | 8         | 1.48%   |
| IceLake          | 8         | 1.48%   |
| Excavator        | 6         | 1.11%   |
| Westmere         | 5         | 0.93%   |
| Puma             | 5         | 0.93%   |
| Goldmont plus    | 5         | 0.93%   |
| Steamroller      | 4         | 0.74%   |
| Nehalem          | 4         | 0.74%   |
| K10              | 4         | 0.74%   |
| Silvermont       | 3         | 0.56%   |
| Goldmont         | 3         | 0.56%   |
| K8 & K10 hybrid  | 1         | 0.19%   |
| Jaguar           | 1         | 0.19%   |
| Core             | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 254       | 36.08%  |
| Nvidia | 235       | 33.38%  |
| AMD    | 215       | 30.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 27        | 3.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 23        | 3.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 23        | 3.17%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 22        | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 19        | 2.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19        | 2.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 16        | 2.21%   |
| Intel UHD Graphics 620                                                      | 15        | 2.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15        | 2.07%   |
| Intel HD Graphics 630                                                       | 14        | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 14        | 1.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 14        | 1.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11        | 1.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11        | 1.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 10        | 1.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 10        | 1.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 10        | 1.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 10        | 1.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 10        | 1.38%   |
| Intel HD Graphics 620                                                       | 9         | 1.24%   |
| AMD Rembrandt [Radeon 680M]                                                 | 9         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 8         | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8         | 1.1%    |
| AMD Raphael                                                                 | 8         | 1.1%    |
| AMD Lucienne                                                                | 8         | 1.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 7         | 0.97%   |
| Intel HD Graphics 5500                                                      | 7         | 0.97%   |
| Intel HD Graphics 530                                                       | 7         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 0.97%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 6         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 5         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 5         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 5         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 5         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 0.69%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 0.69%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 146       | 26.89%  |
| 1 x Intel          | 137       | 25.23%  |
| Intel + Nvidia     | 93        | 17.13%  |
| 1 x Nvidia         | 90        | 16.57%  |
| AMD + Nvidia       | 47        | 8.66%   |
| Intel + AMD        | 12        | 2.21%   |
| 2 x AMD            | 11        | 2.03%   |
| 2 x Nvidia         | 3         | 0.55%   |
| 2 x Intel          | 2         | 0.37%   |
| Intel + 2 x Nvidia | 2         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 351       | 64.4%   |
| Proprietary | 193       | 35.41%  |
| Unknown     | 1         | 0.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 311       | 56.34%  |
| 0.01-0.5   | 55        | 9.96%   |
| 7.01-8.0   | 42        | 7.61%   |
| 1.01-2.0   | 40        | 7.25%   |
| 3.01-4.0   | 34        | 6.16%   |
| 8.01-16.0  | 30        | 5.43%   |
| 5.01-6.0   | 18        | 3.26%   |
| 0.51-1.0   | 14        | 2.54%   |
| 16.01-24.0 | 5         | 0.91%   |
| 2.01-3.0   | 3         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 74        | 11.28%  |
| AU Optronics            | 69        | 10.52%  |
| BOE                     | 58        | 8.84%   |
| Chimei Innolux          | 52        | 7.93%   |
| LG Display              | 46        | 7.01%   |
| Dell                    | 36        | 5.49%   |
| Goldstar                | 33        | 5.03%   |
| Acer                    | 30        | 4.57%   |
| AOC                     | 25        | 3.81%   |
| Hewlett-Packard         | 19        | 2.9%    |
| BenQ                    | 16        | 2.44%   |
| Sharp                   | 14        | 2.13%   |
| PANDA                   | 14        | 2.13%   |
| Ancor Communications    | 12        | 1.83%   |
| Apple                   | 11        | 1.68%   |
| Philips                 | 10        | 1.52%   |
| Lenovo                  | 10        | 1.52%   |
| ASUSTek Computer        | 10        | 1.52%   |
| ViewSonic               | 8         | 1.22%   |
| Unknown                 | 7         | 1.07%   |
| Sony                    | 7         | 1.07%   |
| MSI                     | 7         | 1.07%   |
| Iiyama                  | 6         | 0.91%   |
| NEC Computers           | 5         | 0.76%   |
| Gigabyte Technology     | 5         | 0.76%   |
| Mi                      | 4         | 0.61%   |
| InfoVision              | 4         | 0.61%   |
| Vizio                   | 3         | 0.46%   |
| Insignia                | 3         | 0.46%   |
| CSO                     | 3         | 0.46%   |
| Chi Mei Optoelectronics | 3         | 0.46%   |
| Toshiba                 | 2         | 0.3%    |
| TMX                     | 2         | 0.3%    |
| Tianma XM               | 2         | 0.3%    |
| LGD                     | 2         | 0.3%    |
| LG Electronics          | 2         | 0.3%    |
| HKC                     | 2         | 0.3%    |
| Eizo                    | 2         | 0.3%    |
| Unknown                 | 2         | 0.3%    |
| ___                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.88%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.59%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.59%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.44%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.44%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3         | 0.44%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 2         | 0.29%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch         | 2         | 0.29%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 2         | 0.29%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 2         | 0.29%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.29%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.29%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2         | 0.29%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2         | 0.29%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |
| MSI G273 MSI3CA7 1920x1080 590x330mm 26.6-inch                        | 2         | 0.29%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 2         | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.29%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 2         | 0.29%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 2         | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2         | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.29%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                    | 2         | 0.29%   |
| Dell SE2719HR DELF115 1920x1080 600x340mm 27.2-inch                   | 2         | 0.29%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                    | 2         | 0.29%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 311       | 49.92%  |
| 1366x768 (WXGA)    | 62        | 9.95%   |
| 3840x2160 (4K)     | 54        | 8.67%   |
| 2560x1440 (QHD)    | 40        | 6.42%   |
| 1920x1200 (WUXGA)  | 18        | 2.89%   |
| 1600x900 (HD+)     | 17        | 2.73%   |
| 3440x1440          | 16        | 2.57%   |
| 1680x1050 (WSXGA+) | 15        | 2.41%   |
| Unknown            | 11        | 1.77%   |
| 2560x1600          | 8         | 1.28%   |
| 1440x900 (WXGA+)   | 8         | 1.28%   |
| 2560x1080          | 7         | 1.12%   |
| 1280x1024 (SXGA)   | 7         | 1.12%   |
| 1280x800 (WXGA)    | 6         | 0.96%   |
| 3840x1080          | 5         | 0.8%    |
| 2880x1800          | 5         | 0.8%    |
| 1360x768           | 3         | 0.48%   |
| 7680x2160          | 2         | 0.32%   |
| 3840x1200          | 2         | 0.32%   |
| 3200x2000          | 2         | 0.32%   |
| 3000x2000          | 2         | 0.32%   |
| 2256x1504          | 2         | 0.32%   |
| 1920x540           | 2         | 0.32%   |
| 1280x720 (HD)      | 2         | 0.32%   |
| 9600x2160          | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 3840x2400          | 1         | 0.16%   |
| 3520x1080          | 1         | 0.16%   |
| 3360x1050          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2880x1440          | 1         | 0.16%   |
| 2736x1824          | 1         | 0.16%   |
| 2288x1287          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 2048x1152          | 1         | 0.16%   |
| 1680x945           | 1         | 0.16%   |
| 1600x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x768           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 180       | 27.82%  |
| 27      | 67        | 10.36%  |
| 24      | 46        | 7.11%   |
| 14      | 44        | 6.8%    |
| Unknown | 44        | 6.8%    |
| 13      | 38        | 5.87%   |
| 23      | 33        | 5.1%    |
| 21      | 29        | 4.48%   |
| 17      | 26        | 4.02%   |
| 31      | 21        | 3.25%   |
| 34      | 16        | 2.47%   |
| 16      | 13        | 2.01%   |
| 22      | 11        | 1.7%    |
| 18      | 10        | 1.55%   |
| 20      | 9         | 1.39%   |
| 19      | 9         | 1.39%   |
| 72      | 8         | 1.24%   |
| 25      | 4         | 0.62%   |
| 54      | 3         | 0.46%   |
| 43      | 3         | 0.46%   |
| 40      | 3         | 0.46%   |
| 28      | 3         | 0.46%   |
| 26      | 3         | 0.46%   |
| 74      | 2         | 0.31%   |
| 49      | 2         | 0.31%   |
| 48      | 2         | 0.31%   |
| 35      | 2         | 0.31%   |
| 29      | 2         | 0.31%   |
| 12      | 2         | 0.31%   |
| 11      | 2         | 0.31%   |
| 142     | 1         | 0.15%   |
| 85      | 1         | 0.15%   |
| 84      | 1         | 0.15%   |
| 58      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 50      | 1         | 0.15%   |
| 47      | 1         | 0.15%   |
| 46      | 1         | 0.15%   |
| 33      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 242       | 38.35%  |
| 501-600        | 133       | 21.08%  |
| 401-500        | 61        | 9.67%   |
| Unknown        | 44        | 6.97%   |
| 351-400        | 35        | 5.55%   |
| 601-700        | 34        | 5.39%   |
| 201-300        | 31        | 4.91%   |
| 701-800        | 18        | 2.85%   |
| 1001-1500      | 13        | 2.06%   |
| 1501-2000      | 12        | 1.9%    |
| 801-900        | 5         | 0.79%   |
| 901-1000       | 2         | 0.32%   |
| More than 2000 | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 431       | 74.96%  |
| 16/10   | 65        | 11.3%   |
| Unknown | 38        | 6.61%   |
| 21/9    | 19        | 3.3%    |
| 5/4     | 7         | 1.22%   |
| 3/2     | 6         | 1.04%   |
| 4/3     | 3         | 0.52%   |
| 32/9    | 3         | 0.52%   |
| 3.20    | 1         | 0.17%   |
| 2.00    | 1         | 0.17%   |
| 1.00    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 181       | 28.55%  |
| 201-250        | 91        | 14.35%  |
| 301-350        | 69        | 10.88%  |
| 81-90          | 64        | 10.09%  |
| 351-500        | 45        | 7.1%    |
| Unknown        | 44        | 6.94%   |
| 121-130        | 25        | 3.94%   |
| 151-200        | 24        | 3.79%   |
| More than 1000 | 21        | 3.31%   |
| 251-300        | 18        | 2.84%   |
| 71-80          | 17        | 2.68%   |
| 141-150        | 10        | 1.58%   |
| 501-1000       | 10        | 1.58%   |
| 111-120        | 7         | 1.1%    |
| 91-100         | 3         | 0.47%   |
| 61-70          | 2         | 0.32%   |
| 51-60          | 2         | 0.32%   |
| 131-140        | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 189       | 31.09%  |
| 51-100        | 174       | 28.62%  |
| 101-120       | 124       | 20.39%  |
| Unknown       | 44        | 7.24%   |
| 161-240       | 42        | 6.91%   |
| More than 240 | 19        | 3.13%   |
| 1-50          | 16        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 405       | 73.64%  |
| 2     | 118       | 21.45%  |
| 3     | 20        | 3.64%   |
| 0     | 5         | 0.91%   |
| 4     | 2         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 324       | 38.12%  |
| Intel                             | 283       | 33.29%  |
| Qualcomm Atheros                  | 70        | 8.24%   |
| MediaTek                          | 41        | 4.82%   |
| Broadcom                          | 36        | 4.24%   |
| TP-Link                           | 9         | 1.06%   |
| NetGear                           | 8         | 0.94%   |
| Samsung Electronics               | 7         | 0.82%   |
| Ralink Technology                 | 7         | 0.82%   |
| ASIX Electronics                  | 5         | 0.59%   |
| Xiaomi                            | 4         | 0.47%   |
| Microsoft                         | 4         | 0.47%   |
| Linksys                           | 4         | 0.47%   |
| DisplayLink                       | 4         | 0.47%   |
| Qualcomm                          | 3         | 0.35%   |
| Dell                              | 3         | 0.35%   |
| Aquantia                          | 3         | 0.35%   |
| Wacom                             | 2         | 0.24%   |
| Ralink                            | 2         | 0.24%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.24%   |
| D-Link                            | 2         | 0.24%   |
| AVM                               | 2         | 0.24%   |
| ASUSTek Computer                  | 2         | 0.24%   |
| Unknown                           | 2         | 0.24%   |
| ZyXEL Communications              | 1         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.12%   |
| Sitecom Europe                    | 1         | 0.12%   |
| Sierra Wireless                   | 1         | 0.12%   |
| Shenzhen Goodix Technology        | 1         | 0.12%   |
| Qualcomm Atheros Communications   | 1         | 0.12%   |
| Nvidia                            | 1         | 0.12%   |
| Motorola PCS                      | 1         | 0.12%   |
| Marvell Technology Group          | 1         | 0.12%   |
| Lenovo                            | 1         | 0.12%   |
| InterBiometrics                   | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| Holtek Semiconductor              | 1         | 0.12%   |
| Google                            | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 218       | 22.13%  |
| Intel Wi-Fi 6 AX200                                               | 51        | 5.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 3.76%   |
| Intel I211 Gigabit Network Connection                             | 25        | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 1.83%   |
| Intel Ethernet Controller I225-V                                  | 17        | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 1.52%   |
| Intel Wireless 7265                                               | 15        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 1.42%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 11        | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 1.12%   |
| Intel Wireless-AC 9260                                            | 10        | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.91%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 9         | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 8         | 0.81%   |
| Intel Wireless 7260                                               | 8         | 0.81%   |
| Intel Wireless 3165                                               | 8         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 0.61%   |
| Intel Wireless 8260                                               | 6         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 227       | 47.59%  |
| Realtek Semiconductor           | 75        | 15.72%  |
| Qualcomm Atheros                | 56        | 11.74%  |
| MediaTek                        | 38        | 7.97%   |
| Broadcom                        | 30        | 6.29%   |
| TP-Link                         | 8         | 1.68%   |
| NetGear                         | 8         | 1.68%   |
| Ralink Technology               | 7         | 1.47%   |
| Microsoft                       | 4         | 0.84%   |
| Linksys                         | 4         | 0.84%   |
| Wacom                           | 2         | 0.42%   |
| Ralink                          | 2         | 0.42%   |
| D-Link                          | 2         | 0.42%   |
| AVM                             | 2         | 0.42%   |
| ASUSTek Computer                | 2         | 0.42%   |
| Unknown                         | 2         | 0.42%   |
| ZyXEL Communications            | 1         | 0.21%   |
| Sitecom Europe                  | 1         | 0.21%   |
| Sierra Wireless                 | 1         | 0.21%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| Qualcomm                        | 1         | 0.21%   |
| Dell                            | 1         | 0.21%   |
| Broadcom Limited                | 1         | 0.21%   |
| Accton Technology               | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 51        | 10.63%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 4.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 3.13%   |
| Intel Wireless 7265                                            | 15        | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15        | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 2.92%   |
| Intel Wireless 8265 / 8275                                     | 13        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 2.29%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 2.29%   |
| Intel Wireless-AC 9260                                         | 10        | 2.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 1.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8         | 1.67%   |
| Intel Wireless 7260                                            | 8         | 1.67%   |
| Intel Wireless 3165                                            | 8         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.46%   |
| Intel Wireless 8260                                            | 6         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.63%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 3         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.63%   |
| NetGear A6210                                                  | 3         | 0.63%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 290       | 59.92%  |
| Intel                         | 117       | 24.17%  |
| Qualcomm Atheros              | 23        | 4.75%   |
| Broadcom                      | 16        | 3.31%   |
| Samsung Electronics           | 7         | 1.45%   |
| ASIX Electronics              | 5         | 1.03%   |
| Xiaomi                        | 4         | 0.83%   |
| DisplayLink                   | 4         | 0.83%   |
| MediaTek                      | 3         | 0.62%   |
| Aquantia                      | 3         | 0.62%   |
| Qualcomm                      | 2         | 0.41%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.21%   |
| TP-Link                       | 1         | 0.21%   |
| OnePlus Technology (Shenzhen) | 1         | 0.21%   |
| Nvidia                        | 1         | 0.21%   |
| Marvell Technology Group      | 1         | 0.21%   |
| Lenovo                        | 1         | 0.21%   |
| ICS Advent                    | 1         | 0.21%   |
| Google                        | 1         | 0.21%   |
| Belkin Components             | 1         | 0.21%   |
| Alteon Networks               | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 218       | 44.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 7.47%   |
| Intel I211 Gigabit Network Connection                             | 25        | 5.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 4.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.64%   |
| Intel Ethernet Controller I225-V                                  | 17        | 3.43%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 1.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 1.21%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.81%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.61%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.61%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.4%    |
| MediaTek Wiko U316AT                                              | 2         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.4%    |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.4%    |
| DisplayLink USB-C Dual-4K Dock                                    | 2         | 0.4%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 450       | 49.78%  |
| WiFi     | 444       | 49.12%  |
| Modem    | 6         | 0.66%   |
| Unknown  | 4         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 338       | 60.47%  |
| Ethernet | 221       | 39.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 294       | 54.24%  |
| 1     | 221       | 40.77%  |
| 3     | 20        | 3.69%   |
| 0     | 4         | 0.74%   |
| 6     | 2         | 0.37%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 396       | 72.79%  |
| Yes  | 148       | 27.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 197       | 48.88%  |
| Realtek Semiconductor           | 51        | 12.66%  |
| Qualcomm Atheros Communications | 32        | 7.94%   |
| Cambridge Silicon Radio         | 21        | 5.21%   |
| IMC Networks                    | 20        | 4.96%   |
| MediaTek                        | 15        | 3.72%   |
| Foxconn / Hon Hai               | 13        | 3.23%   |
| Lite-On Technology              | 12        | 2.98%   |
| Broadcom                        | 12        | 2.98%   |
| Apple                           | 11        | 2.73%   |
| ASUSTek Computer                | 8         | 1.99%   |
| Dell                            | 3         | 0.74%   |
| Hewlett-Packard                 | 2         | 0.5%    |
| USI                             | 1         | 0.25%   |
| Realtek                         | 1         | 0.25%   |
| Edimax Technology               | 1         | 0.25%   |
| Dynex                           | 1         | 0.25%   |
| Alps Electric                   | 1         | 0.25%   |
| AboCom Systems                  | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 46        | 11.41%  |
| Intel Bluetooth wireless interface                  | 45        | 11.17%  |
| Intel AX201 Bluetooth                               | 38        | 9.43%   |
| Realtek Bluetooth Radio                             | 32        | 7.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 5.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 5.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 3.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 3.72%   |
| MediaTek Wireless_Device                            | 14        | 3.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 2.98%   |
| Intel AX210 Bluetooth                               | 12        | 2.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 2.48%   |
| IMC Networks Wireless_Device                        | 10        | 2.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 2.23%   |
| Intel Bluetooth Device                              | 8         | 1.99%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.99%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.74%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.99%   |
| Apple Bluetooth Host Controller                     | 4         | 0.99%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.74%   |
| Lite-On Wireless_Device                             | 3         | 0.74%   |
| Lite-On Bluetooth Device                            | 3         | 0.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.5%    |
| Dell DW375 Bluetooth Module                         | 2         | 0.5%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.5%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.5%    |
| ASUS Bluetooth Radio                                | 2         | 0.5%    |
| ASUS ASUS USB-BT500                                 | 2         | 0.5%    |
| USI Bluetooth Device                                | 1         | 0.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.25%   |
| Realtek Bluetooth Radio                             | 1         | 0.25%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 317       | 37.43%  |
| AMD                       | 240       | 28.34%  |
| Nvidia                    | 171       | 20.19%  |
| C-Media Electronics       | 20        | 2.36%   |
| Logitech                  | 14        | 1.65%   |
| Kingston Technology       | 6         | 0.71%   |
| JMTek                     | 5         | 0.59%   |
| Blue Microphones          | 5         | 0.59%   |
| Texas Instruments         | 4         | 0.47%   |
| Sony                      | 4         | 0.47%   |
| Creative Technology       | 4         | 0.47%   |
| Trust                     | 3         | 0.35%   |
| RODE Microphones          | 3         | 0.35%   |
| Focusrite-Novation        | 3         | 0.35%   |
| Yamaha                    | 2         | 0.24%   |
| Razer USA                 | 2         | 0.24%   |
| Micro Star International  | 2         | 0.24%   |
| M-Audio                   | 2         | 0.24%   |
| Generalplus Technology    | 2         | 0.24%   |
| DSEA A/S                  | 2         | 0.24%   |
| Digidesign                | 2         | 0.24%   |
| Creative Labs             | 2         | 0.24%   |
| Corsair                   | 2         | 0.24%   |
| XMOS                      | 1         | 0.12%   |
| Turtle Beach              | 1         | 0.12%   |
| Tenx Technology           | 1         | 0.12%   |
| SteelSeries ApS           | 1         | 0.12%   |
| Sennheiser Communications | 1         | 0.12%   |
| Samson Technologies       | 1         | 0.12%   |
| ROCCAT                    | 1         | 0.12%   |
| Realtek Semiconductor     | 1         | 0.12%   |
| Plantronics               | 1         | 0.12%   |
| Phison Electronics        | 1         | 0.12%   |
| KORG                      | 1         | 0.12%   |
| Jieli Technology          | 1         | 0.12%   |
| Huawei Technologies       | 1         | 0.12%   |
| Hewlett-Packard           | 1         | 0.12%   |
| Harman International      | 1         | 0.12%   |
| GN Netcom                 | 1         | 0.12%   |
| FX200                     | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 114       | 10.73%  |
| AMD Starship/Matisse HD Audio Controller                                   | 51        | 4.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 49        | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 3.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 3.48%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 1.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20        | 1.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 19        | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 1.6%    |
| Intel Comet Lake PCH cAVS                                                  | 16        | 1.51%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12        | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 1.13%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.13%   |
| AMD FCH Azalia Controller                                                  | 12        | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 11        | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 1.04%   |
| Nvidia Audio device                                                        | 11        | 1.04%   |
| AMD Navi 10 HDMI Audio                                                     | 11        | 1.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 0.94%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 9         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8         | 0.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 0.75%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.75%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 0.75%   |
| Nvidia TU104 HD Audio Controller                                           | 7         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 87        | 20.96%  |
| SK hynix                                | 72        | 17.35%  |
| Micron Technology                       | 45        | 10.84%  |
| G.Skill                                 | 32        | 7.71%   |
| Crucial                                 | 32        | 7.71%   |
| Kingston                                | 31        | 7.47%   |
| Corsair                                 | 25        | 6.02%   |
| Unknown                                 | 14        | 3.37%   |
| Ramaxel Technology                      | 11        | 2.65%   |
| A-DATA Technology                       | 10        | 2.41%   |
| Patriot                                 | 9         | 2.17%   |
| Unknown (ABCD)                          | 5         | 1.2%    |
| Team                                    | 5         | 1.2%    |
| Nanya Technology                        | 5         | 1.2%    |
| Unknown                                 | 5         | 1.2%    |
| Patriot Memory (PDP Systems)            | 4         | 0.96%   |
| Smart                                   | 3         | 0.72%   |
| Hewlett-Packard                         | 3         | 0.72%   |
| Transcend                               | 2         | 0.48%   |
| Timetec                                 | 2         | 0.48%   |
| Elpida                                  | 2         | 0.48%   |
| Wilk                                    | 1         | 0.24%   |
| Silicon Power Computer & Communications | 1         | 0.24%   |
| Sesame                                  | 1         | 0.24%   |
| PNY                                     | 1         | 0.24%   |
| GOODRAM                                 | 1         | 0.24%   |
| Essencore                               | 1         | 0.24%   |
| CSX                                     | 1         | 0.24%   |
| Avant                                   | 1         | 0.24%   |
| ASint Technology                        | 1         | 0.24%   |
| Apacer                                  | 1         | 0.24%   |
| 48spaces                                | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 2.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.36%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.13%   |
| Unknown                                                          | 5         | 1.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.91%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 4         | 0.91%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.68%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 0.68%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s                       | 3         | 0.68%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.68%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s              | 3         | 0.68%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.68%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 3         | 0.68%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2         | 0.45%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.45%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.45%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.45%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 2         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.45%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 227       | 63.41%  |
| DDR3    | 78        | 21.79%  |
| DDR5    | 19        | 5.31%   |
| LPDDR4  | 15        | 4.19%   |
| LPDDR3  | 6         | 1.68%   |
| Unknown | 5         | 1.4%    |
| DDR2    | 4         | 1.12%   |
| LPDDR5  | 3         | 0.84%   |
| SDRAM   | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 218       | 60.39%  |
| DIMM         | 119       | 32.96%  |
| Row Of Chips | 22        | 6.09%   |
| Chip         | 1         | 0.28%   |
| Unknown      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 197       | 49.62%  |
| 4096  | 90        | 22.67%  |
| 16384 | 79        | 19.9%   |
| 32768 | 20        | 5.04%   |
| 2048  | 10        | 2.52%   |
| 1024  | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 96        | 24.24%  |
| 1600  | 58        | 14.65%  |
| 2667  | 56        | 14.14%  |
| 2400  | 32        | 8.08%   |
| 3600  | 25        | 6.31%   |
| 2133  | 13        | 3.28%   |
| 4800  | 11        | 2.78%   |
| 1333  | 10        | 2.53%   |
| 1334  | 7         | 1.77%   |
| 4266  | 6         | 1.52%   |
| 3666  | 5         | 1.26%   |
| 3266  | 5         | 1.26%   |
| 2933  | 5         | 1.26%   |
| 6400  | 4         | 1.01%   |
| 5600  | 4         | 1.01%   |
| 3733  | 4         | 1.01%   |
| 3533  | 4         | 1.01%   |
| 2666  | 4         | 1.01%   |
| 1800  | 4         | 1.01%   |
| 4267  | 3         | 0.76%   |
| 3000  | 3         | 0.76%   |
| 2800  | 3         | 0.76%   |
| 1867  | 3         | 0.76%   |
| 1866  | 3         | 0.76%   |
| 800   | 3         | 0.76%   |
| 3866  | 2         | 0.51%   |
| 3800  | 2         | 0.51%   |
| 3466  | 2         | 0.51%   |
| 667   | 2         | 0.51%   |
| 8400  | 1         | 0.25%   |
| 6000  | 1         | 0.25%   |
| 5808  | 1         | 0.25%   |
| 5200  | 1         | 0.25%   |
| 4200  | 1         | 0.25%   |
| 4199  | 1         | 0.25%   |
| 4000  | 1         | 0.25%   |
| 3534  | 1         | 0.25%   |
| 3400  | 1         | 0.25%   |
| 3151  | 1         | 0.25%   |
| 2200  | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 30.77%  |
| Brother Industries  | 3         | 23.08%  |
| Samsung Electronics | 2         | 15.38%  |
| Dymo-CoStar         | 2         | 15.38%  |
| Kyocera             | 1         | 7.69%   |
| Fuji Xerox          | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450      | 2         | 15.38%  |
| Brother HL-5370DW series         | 2         | 15.38%  |
| Samsung M337x 387x 407x Series   | 1         | 7.69%   |
| Samsung M267x 287x Series        | 1         | 7.69%   |
| Kyocera FS-1030D printer         | 1         | 7.69%   |
| HP OfficeJet Pro 8020 series     | 1         | 7.69%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 7.69%   |
| HP DeskJet Plus 4100 series      | 1         | 7.69%   |
| HP Deskjet 2050 J510             | 1         | 7.69%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 7.69%   |
| Brother MFC Composite Device     | 1         | 7.69%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 20.24%  |
| IMC Networks                           | 42        | 12.69%  |
| Logitech                               | 27        | 8.16%   |
| Quanta                                 | 23        | 6.95%   |
| Realtek Semiconductor                  | 21        | 6.34%   |
| Microdia                               | 20        | 6.04%   |
| Sunplus Innovation Technology          | 18        | 5.44%   |
| Bison Electronics                      | 14        | 4.23%   |
| Luxvisions Innotech Limited            | 11        | 3.32%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.32%   |
| Syntek                                 | 10        | 3.02%   |
| Microsoft                              | 9         | 2.72%   |
| Apple                                  | 9         | 2.72%   |
| Suyin                                  | 7         | 2.11%   |
| Acer                                   | 5         | 1.51%   |
| Lite-On Technology                     | 4         | 1.21%   |
| Sonix Technology                       | 3         | 0.91%   |
| Silicon Motion                         | 3         | 0.91%   |
| Jieli Technology                       | 3         | 0.91%   |
| SunplusIT                              | 2         | 0.6%    |
| Primax Electronics                     | 2         | 0.6%    |
| Generalplus Technology                 | 2         | 0.6%    |
| Creative Technology                    | 2         | 0.6%    |
| Alcor Micro                            | 2         | 0.6%    |
| Z-Star Microelectronics                | 1         | 0.3%    |
| WaveRider Communications               | 1         | 0.3%    |
| Trust                                  | 1         | 0.3%    |
| ShineTech                              | 1         | 0.3%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.3%    |
| Samsung Electronics                    | 1         | 0.3%    |
| Razer USA                              | 1         | 0.3%    |
| MacroSilicon                           | 1         | 0.3%    |
| Lenovo                                 | 1         | 0.3%    |
| Importek                               | 1         | 0.3%    |
| Genesys Logic                          | 1         | 0.3%    |
| GEMBIRD                                | 1         | 0.3%    |
| DigiTech                               | 1         | 0.3%    |
| Unknown                                | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 21        | 6.31%   |
| IMC Networks Integrated Camera                       | 13        | 3.9%    |
| Microdia Integrated_Webcam_HD                        | 10        | 3%      |
| Chicony Integrated Camera                            | 10        | 3%      |
| Chicony HD WebCam                                    | 10        | 3%      |
| Syntek Integrated Camera                             | 8         | 2.4%    |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.8%    |
| Quanta HD User Facing                                | 6         | 1.8%    |
| Chicony HP Wide Vision HD Camera                     | 6         | 1.8%    |
| Chicony HD User Facing                               | 6         | 1.8%    |
| Apple FaceTime HD Camera                             | 6         | 1.8%    |
| Realtek Integrated_Webcam_HD                         | 5         | 1.5%    |
| Quanta HP Wide Vision HD Camera                      | 5         | 1.5%    |
| Logitech Webcam C270                                 | 5         | 1.5%    |
| Logitech HD Pro Webcam C920                          | 5         | 1.5%    |
| Bison HD Webcam                                      | 5         | 1.5%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 1.2%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 1.2%    |
| Logitech BRIO Ultra HD Webcam                        | 4         | 1.2%    |
| Chicony USB2.0 Camera                                | 4         | 1.2%    |
| Acer Integrated Camera                               | 4         | 1.2%    |
| Microsoft LifeCam HD-3000                            | 3         | 0.9%    |
| Logitech Webcam C930e                                | 3         | 0.9%    |
| Lite-On HP Wide Vision HD Camera                     | 3         | 0.9%    |
| Jieli USB PHY 2.0                                    | 3         | 0.9%    |
| Chicony Integrated HD WebCam                         | 3         | 0.9%    |
| Chicony HP Truevision HD                             | 3         | 0.9%    |
| Chicony EasyCamera                                   | 3         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 3         | 0.9%    |
| SunplusIT XiaoMi USB 2.0 Webcam                      | 2         | 0.6%    |
| Sunplus AUSDOM FHD Camera                            | 2         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.6%    |
| Silicon Motion Web Camera                            | 2         | 0.6%    |
| Realtek USB Camera                                   | 2         | 0.6%    |
| Realtek HP Truevision HD                             | 2         | 0.6%    |
| Realtek Full HD webcam                               | 2         | 0.6%    |
| Quanta HP TrueVision HD Camera                       | 2         | 0.6%    |
| Quanta HD Camera                                     | 2         | 0.6%    |
| Primax HP HD Webcam [Fixed]                          | 2         | 0.6%    |
| Microsoft LifeCam HD-5000                            | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 26.32%  |
| Synaptics                  | 14        | 24.56%  |
| Elan Microelectronics      | 10        | 17.54%  |
| Shenzhen Goodix Technology | 8         | 14.04%  |
| LighTuning Technology      | 5         | 8.77%   |
| AuthenTec                  | 3         | 5.26%   |
| Samsung Electronics        | 1         | 1.75%   |
| Focal-systems.Corp         | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 6         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 7.02%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 7.02%   |
| Elan ELAN:Fingerprint                                                      | 4         | 7.02%   |
| Synaptics UWP WBDI                                                         | 3         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.51%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.51%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 3.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 3.51%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors VFS491                                                    | 1         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.75%   |
| Synaptics WBDI Device                                                      | 1         | 1.75%   |
| Synaptics WBDI                                                             | 1         | 1.75%   |
| Synaptics  WBDI                                                            | 1         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.75%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.75%   |
| AuthenTec AES2810                                                          | 1         | 1.75%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.75%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 12        | 57.14%  |
| Alcor Micro      | 5         | 23.81%  |
| Upek             | 1         | 4.76%   |
| SCM Microsystems | 1         | 4.76%   |
| O2 Micro         | 1         | 4.76%   |
| Lenovo           | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 23.81%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 23.81%  |
| Broadcom 5880                                                                | 4         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.76%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 265       | 48.18%  |
| 0     | 188       | 34.18%  |
| 2     | 80        | 14.55%  |
| 3     | 16        | 2.91%   |
| 4     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 304       | 63.47%  |
| Fingerprint reader       | 56        | 11.69%  |
| Graphics card            | 31        | 6.47%   |
| Net/wireless             | 27        | 5.64%   |
| Chipcard                 | 20        | 4.18%   |
| Multimedia controller    | 13        | 2.71%   |
| Net/ethernet             | 8         | 1.67%   |
| Camera                   | 7         | 1.46%   |
| Unassigned class         | 3         | 0.63%   |
| Storage                  | 3         | 0.63%   |
| Network                  | 3         | 0.63%   |
| Bluetooth                | 2         | 0.42%   |
| Wireless                 | 1         | 0.21%   |
| Sound                    | 1         | 0.21%   |

