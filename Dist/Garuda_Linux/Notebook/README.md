Garuda Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 468

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V3-571               | [0819197709](https://linux-hardware.org/?probe=0819197709) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| Lenovo        | V14-ADA 82C6                | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [30fc775598](https://linux-hardware.org/?probe=30fc775598) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [19d43a41f8](https://linux-hardware.org/?probe=19d43a41f8) | Dec 17, 2023 |
| HC            | HCAR357-MI                  | [daaf3e0f5f](https://linux-hardware.org/?probe=daaf3e0f5f) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| HP            | ProBook 450 G4              | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| Dell          | Inspiron 17-7779            | [16c9e2b55c](https://linux-hardware.org/?probe=16c9e2b55c) | Dec 04, 2023 |
| Dell          | Inspiron 5515               | [e099b86288](https://linux-hardware.org/?probe=e099b86288) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cf6dd1eb40](https://linux-hardware.org/?probe=cf6dd1eb40) | Dec 01, 2023 |
| Samsung       | R530/R730                   | [d307e11a95](https://linux-hardware.org/?probe=d307e11a95) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3aa5e4bed1](https://linux-hardware.org/?probe=3aa5e4bed1) | Nov 30, 2023 |
| Dell          | Vostro 3583                 | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Acer          | Nitro AN515-58              | [2ddc688d1d](https://linux-hardware.org/?probe=2ddc688d1d) | Nov 28, 2023 |
| HP            | Laptop 14-dk0xxx            | [9e97507512](https://linux-hardware.org/?probe=9e97507512) | Nov 27, 2023 |
| Lenovo        | G50-30 80G0                 | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Dell          | Latitude E5520              | [7c773e173a](https://linux-hardware.org/?probe=7c773e173a) | Nov 21, 2023 |
| HP            | ZBook 15                    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| Dell          | Vostro 3583                 | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| Samsung       | R530/R730                   | [e1177626c4](https://linux-hardware.org/?probe=e1177626c4) | Nov 11, 2023 |
| HP            | Laptop 15-ef2xxx            | [dd143f192c](https://linux-hardware.org/?probe=dd143f192c) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Dell          | Inspiron 3521               | [cdda6b5094](https://linux-hardware.org/?probe=cdda6b5094) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | [5bec5815bb](https://linux-hardware.org/?probe=5bec5815bb) | Oct 31, 2023 |
| Acer          | Predator PH317-51           | [941e333a3b](https://linux-hardware.org/?probe=941e333a3b) | Oct 27, 2023 |
| HP            | EliteBook 820 G1            | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| HP            | EliteBook 820 G1            | [959fc54e2b](https://linux-hardware.org/?probe=959fc54e2b) | Oct 23, 2023 |
| Lenovo        | ThinkPad T460s 20F90060G... | [b44ed99aff](https://linux-hardware.org/?probe=b44ed99aff) | Oct 22, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| Acer          | Aspire A715-42G             | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| Apple         | MacBookPro9,2               | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [bc5016980d](https://linux-hardware.org/?probe=bc5016980d) | Oct 10, 2023 |
| HP            | Laptop 15-ef2xxx            | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [e7906b9cd7](https://linux-hardware.org/?probe=e7906b9cd7) | Oct 04, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [1c7bef5950](https://linux-hardware.org/?probe=1c7bef5950) | Oct 04, 2023 |
| Acer          | Aspire A515-56              | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| AMI           | Intel                       | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| ASUSTek       | X455LD                      | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| MSI           | Stealth 14Studio A13VE      | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [78ddadfb89](https://linux-hardware.org/?probe=78ddadfb89) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [3145861387](https://linux-hardware.org/?probe=3145861387) | Sep 12, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| Matsushita... | CF-74JCJBDAM                | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Unknown       | Unknown                     | [9441e027c6](https://linux-hardware.org/?probe=9441e027c6) | Sep 04, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [10951f0a65](https://linux-hardware.org/?probe=10951f0a65) | Sep 01, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [ac6c5c8969](https://linux-hardware.org/?probe=ac6c5c8969) | Sep 01, 2023 |
| MOTION        | NVX00                       | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5d571876c8](https://linux-hardware.org/?probe=5d571876c8) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| ASUSTek       | GL552VW                     | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| Acer          | Nitro AN517-54              | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| HP            | Laptop 14-dq1xxx            | [68fff65eee](https://linux-hardware.org/?probe=68fff65eee) | Aug 10, 2023 |
| HP            | Laptop 14-dq1xxx            | [81a2d0415e](https://linux-hardware.org/?probe=81a2d0415e) | Aug 10, 2023 |
| Dell          | Precision 5530              | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Apple         | MacBookPro9,1               | [65343a7900](https://linux-hardware.org/?probe=65343a7900) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | [4d98867c44](https://linux-hardware.org/?probe=4d98867c44) | Aug 02, 2023 |
| HP            | Laptop 14-dq1xxx            | [675811747f](https://linux-hardware.org/?probe=675811747f) | Aug 02, 2023 |
| Apple         | MacBookPro8,2               | [ba2cec8099](https://linux-hardware.org/?probe=ba2cec8099) | Aug 01, 2023 |
| HP            | Dev One Notebook PC         | [cdbcf58dcb](https://linux-hardware.org/?probe=cdbcf58dcb) | Jul 30, 2023 |
| HP            | ENVY Notebook               | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [2dbda5ea48](https://linux-hardware.org/?probe=2dbda5ea48) | Jul 29, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| Alienware     | 13 R3                       | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [5d2c798252](https://linux-hardware.org/?probe=5d2c798252) | Jul 21, 2023 |
| ASUSTek       | GL502VM                     | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | [79ab32a714](https://linux-hardware.org/?probe=79ab32a714) | Jul 17, 2023 |
| Apple         | MacBookPro9,2               | [228fca7e43](https://linux-hardware.org/?probe=228fca7e43) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [047aac4298](https://linux-hardware.org/?probe=047aac4298) | Jun 25, 2023 |
| Notebook      | P870DM                      | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Apple         | MacBookPro11,2              | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| HUAWEI        | MACH-WX9                    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| Dell          | Latitude E6510              | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| Apple         | MacBookPro14,1              | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Dell          | Precision 5520              | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| Apple         | MacBookPro9,2               | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| MICROBYTE     | ezbook                      | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Acer          | Extensa 215-52              | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| HP            | OMEN by Laptop              | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Acer          | Aspire 5750G                | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Acer          | Extensa 215-52              | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| Monster       | TULPAR T5 V21.7             | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| MSI           | Stealth 15M B12UE           | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HUAWEI        | HVY-WXX9                    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| HP            | EliteBook 8560w             | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| ASUSTek       | GL753VE                     | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| Lenovo        | V15-IIL 82C5                | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Acer          | Aspire A515-46              | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| Acer          | Aspire E5-575G              | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| HP            | Unknown                     | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| Dell          | Precision 7710              | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| MobileDema... | xTablet T1200               | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 8560w             | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Standard      | Unknown                     | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| HP            | Pavilion dv6                | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| HP            | ProBook 6570b               | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| Acer          | Aspire A515-46              | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| HP            | ProBook 6570b               | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Gigabyte      | G5 MD                       | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Acer          | Aspire F5-572G              | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| HP            | Compaq CQ58                 | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| Alienware     | m15 R7                      | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| ASUSTek       | X541UV                      | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| Dell          | Inspiron 7737               | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| Gigabyte      | G5 MD                       | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| HP            | Notebook                    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| HP            | Notebook                    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | Sword 15 A11UD              | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Dell          | Latitude E5450              | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | Pavilion dv6                | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| HP            | Laptop 15-ef0xxx            | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Acer          | Swift SF315-41              | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Razer         | Blade                       | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| HP            | Laptop 15-bs0xx             | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| Casper        | EXCALIBUR G770              | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Dell          | Latitude E7250              | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| Toshiba       | Satellite E45DW-C           | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| HONOR         | HLYL-WXX9                   | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Unknown       | Unknown                     | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| Acer          | Aspire F5-573G              | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire A515-51G             | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASUSTek       | K53SD                       | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Panasonic     | CF-191HYAX1M                | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Razer         | Blade                       | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| Google        | Kindred                     | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| ASUSTek       | G750JZ                      | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| PC Special... | GK5NPFO                     | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| HP            | EliteBook 8540p             | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Alienware     | 17 R3                       | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| Acer          | Nitro AN515-44              | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| Medion        | E7419 MD60025               | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| Dell          | System XPS L702X            | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| HP            | EliteBook 8540p             | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| HP            | EliteBook 8540p             | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Dell          | Latitude E6520              | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| Dell          | XPS 15 9500                 | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | Compaq 6735b                | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| HP            | EliteBook 8540p             | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| Dell          | Latitude E6430              | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Unknown       | Unknown                     | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| HP            | Laptop 17-ak0xx             | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| Dell          | Latitude E6430              | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| HP            | 450                         | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 220       | 68.75%  |
| Garuda Linux Rolling | 54        | 16.88%  |
| Garuda Linux         | 46        | 14.38%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 316       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 6.1.1-zen1-1-zen   | 8         | 2.23%   |
| 6.0.2-zen1-1-zen   | 8         | 2.23%   |
| 6.5.9-zen2-1-zen   | 6         | 1.67%   |
| 6.4.12-zen1-1-zen  | 6         | 1.67%   |
| 6.2.13-zen-1-zen   | 6         | 1.67%   |
| 5.17.9-zen1-1-zen  | 6         | 1.67%   |
| 6.6.2-zen1-1-zen   | 4         | 1.11%   |
| 6.4.11-zen2-1-zen  | 4         | 1.11%   |
| 6.1.7-zen1-1-zen   | 4         | 1.11%   |
| 6.0.9-zen1-1-zen   | 4         | 1.11%   |
| 6.0.10-zen2-1-zen  | 4         | 1.11%   |
| 5.16.16-zen1-1-zen | 4         | 1.11%   |
| 5.14.14-zen1-1-zen | 4         | 1.11%   |
| 5.13.13-zen1-1-zen | 4         | 1.11%   |
| 6.6.3-zen1-1-zen   | 3         | 0.84%   |
| 6.6.1-zen1-1-zen   | 3         | 0.84%   |
| 6.5.3-zen1-1-zen   | 3         | 0.84%   |
| 6.4.8-zen1-1-zen   | 3         | 0.84%   |
| 6.3.8-zen1-1-zen   | 3         | 0.84%   |
| 6.2.12-zen1-1-zen  | 3         | 0.84%   |
| 6.1.11-zen1-1-zen  | 3         | 0.84%   |
| 6.0.8-zen1-1-zen   | 3         | 0.84%   |
| 6.0.6-zen1-1-zen   | 3         | 0.84%   |
| 5.19.7-zen2-1-zen  | 3         | 0.84%   |
| 5.19.13-zen1-1-zen | 3         | 0.84%   |
| 5.19.10-zen1-1-zen | 3         | 0.84%   |
| 5.18.16-zen1-1-zen | 3         | 0.84%   |
| 5.17.3-zen1-1-zen  | 3         | 0.84%   |
| 5.17.1-zen1-1-zen  | 3         | 0.84%   |
| 5.16.4-zen1-1-zen  | 3         | 0.84%   |
| 5.16.2-zen1-1-zen  | 3         | 0.84%   |
| 5.15.6-zen2-1-zen  | 3         | 0.84%   |
| 5.15.2-zen1-1-zen  | 3         | 0.84%   |
| 5.15.12-zen1-1-zen | 3         | 0.84%   |
| 5.14.6-zen1-1-zen  | 3         | 0.84%   |
| 5.13.9-zen1-1-zen  | 3         | 0.84%   |
| 5.11.11-zen1-1-zen | 3         | 0.84%   |
| 5.10.1-103-tkg-bmq | 3         | 0.84%   |
| 6.6.7-zen1-1-zen   | 2         | 0.56%   |
| 6.6.6-zen1-1-zen   | 2         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.2   | 9         | 2.51%   |
| 6.1.1   | 8         | 2.23%   |
| 6.5.9   | 7         | 1.95%   |
| 6.4.12  | 6         | 1.67%   |
| 6.2.13  | 6         | 1.67%   |
| 5.17.9  | 6         | 1.67%   |
| 6.1.9   | 5         | 1.39%   |
| 6.0.10  | 5         | 1.39%   |
| 6.6.3   | 4         | 1.11%   |
| 6.6.2   | 4         | 1.11%   |
| 6.6.1   | 4         | 1.11%   |
| 6.4.11  | 4         | 1.11%   |
| 6.3.1   | 4         | 1.11%   |
| 6.1.7   | 4         | 1.11%   |
| 6.0.9   | 4         | 1.11%   |
| 6.0.8   | 4         | 1.11%   |
| 5.19.7  | 4         | 1.11%   |
| 5.18.16 | 4         | 1.11%   |
| 5.17.3  | 4         | 1.11%   |
| 5.17.1  | 4         | 1.11%   |
| 5.16.16 | 4         | 1.11%   |
| 5.14.14 | 4         | 1.11%   |
| 5.13.13 | 4         | 1.11%   |
| 5.11.11 | 4         | 1.11%   |
| 6.6.6   | 3         | 0.84%   |
| 6.5.7   | 3         | 0.84%   |
| 6.5.3   | 3         | 0.84%   |
| 6.4.8   | 3         | 0.84%   |
| 6.4.4   | 3         | 0.84%   |
| 6.3.8   | 3         | 0.84%   |
| 6.2.7   | 3         | 0.84%   |
| 6.2.12  | 3         | 0.84%   |
| 6.1.11  | 3         | 0.84%   |
| 6.0.6   | 3         | 0.84%   |
| 5.19.2  | 3         | 0.84%   |
| 5.19.13 | 3         | 0.84%   |
| 5.19.10 | 3         | 0.84%   |
| 5.18.3  | 3         | 0.84%   |
| 5.17.5  | 3         | 0.84%   |
| 5.16.4  | 3         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 32        | 9.17%   |
| 5.15    | 32        | 9.17%   |
| 6.0     | 31        | 8.88%   |
| 6.4     | 23        | 6.59%   |
| 6.2     | 23        | 6.59%   |
| 5.19    | 22        | 6.3%    |
| 5.16    | 21        | 6.02%   |
| 5.10    | 20        | 5.73%   |
| 5.14    | 19        | 5.44%   |
| 6.6     | 18        | 5.16%   |
| 6.5     | 18        | 5.16%   |
| 5.18    | 18        | 5.16%   |
| 5.17    | 18        | 5.16%   |
| 6.3     | 13        | 3.72%   |
| 5.12    | 12        | 3.44%   |
| 5.11    | 12        | 3.44%   |
| 5.13    | 11        | 3.15%   |
| 5.9     | 4         | 1.15%   |
| 5.6     | 1         | 0.29%   |
| 5.4     | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 316       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 221       | 69.28%  |
| GNOME             | 37        | 11.6%   |
| XFCE              | 17        | 5.33%   |
| KDE               | 14        | 4.39%   |
| X-Cinnamon        | 8         | 2.51%   |
| sway              | 5         | 1.57%   |
| qtile-default     | 3         | 0.94%   |
| qtile             | 2         | 0.63%   |
| i3                | 2         | 0.63%   |
| Deepin            | 2         | 0.63%   |
| Cinnamon          | 2         | 0.63%   |
| Yaru:ubuntu:GNOME | 1         | 0.31%   |
| Unity             | 1         | 0.31%   |
| MATE              | 1         | 0.31%   |
| Hyprland          | 1         | 0.31%   |
| awesome           | 1         | 0.31%   |
| Unknown           | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 278       | 86.88%  |
| Wayland | 31        | 9.69%   |
| Unknown | 7         | 2.19%   |
| Tty     | 4         | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 161       | 50.31%  |
| Unknown | 101       | 31.56%  |
| LightDM | 31        | 9.69%   |
| GDM     | 24        | 7.5%    |
| GREETD  | 3         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 160       | 50.31%  |
| en_GB   | 36        | 11.32%  |
| en_IN   | 22        | 6.92%   |
| de_DE   | 21        | 6.6%    |
| it_IT   | 11        | 3.46%   |
| pt_BR   | 9         | 2.83%   |
| en_CA   | 9         | 2.83%   |
| pl_PL   | 6         | 1.89%   |
| tr_TR   | 4         | 1.26%   |
| es_MX   | 4         | 1.26%   |
| ru_RU   | 3         | 0.94%   |
| nl_NL   | 3         | 0.94%   |
| es_CO   | 3         | 0.94%   |
| fr_FR   | 2         | 0.63%   |
| fi_FI   | 2         | 0.63%   |
| es_ES   | 2         | 0.63%   |
| es_EC   | 2         | 0.63%   |
| en_ZA   | 2         | 0.63%   |
| en_DK   | 2         | 0.63%   |
| en_AG   | 2         | 0.63%   |
| de_AT   | 2         | 0.63%   |
| zh_CN   | 1         | 0.31%   |
| uk_UA   | 1         | 0.31%   |
| sv_SE   | 1         | 0.31%   |
| ko_KR   | 1         | 0.31%   |
| ja_JP   | 1         | 0.31%   |
| es_VE   | 1         | 0.31%   |
| es_PE   | 1         | 0.31%   |
| es_BO   | 1         | 0.31%   |
| es_AR   | 1         | 0.31%   |
| bg_BG   | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 204       | 63.95%  |
| BIOS | 115       | 36.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 307       | 97.15%  |
| Overlay | 6         | 1.9%    |
| XXXXX   | 1         | 0.32%   |
| Xfs     | 1         | 0.32%   |
| F2fs    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 206       | 64.78%  |
| Unknown | 98        | 30.82%  |
| MBR     | 14        | 4.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 287       | 89.97%  |
| Yes       | 32        | 10.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 218       | 68.13%  |
| Yes       | 102       | 31.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 68        | 21.52%  |
| Hewlett-Packard                | 57        | 18.04%  |
| ASUSTek Computer               | 44        | 13.92%  |
| Dell                           | 39        | 12.34%  |
| Acer                           | 31        | 9.81%   |
| MSI                            | 12        | 3.8%    |
| Apple                          | 10        | 3.16%   |
| HUAWEI                         | 6         | 1.9%    |
| Samsung Electronics            | 4         | 1.27%   |
| Notebook                       | 4         | 1.27%   |
| Unknown                        | 4         | 1.27%   |
| Razer                          | 3         | 0.95%   |
| Gigabyte Technology            | 3         | 0.95%   |
| Alienware                      | 3         | 0.95%   |
| XIAOMI                         | 2         | 0.63%   |
| Toshiba                        | 2         | 0.63%   |
| Sony                           | 2         | 0.63%   |
| Medion                         | 2         | 0.63%   |
| HONOR                          | 2         | 0.63%   |
| Fujitsu                        | 2         | 0.63%   |
| Standard                       | 1         | 0.32%   |
| PC Specialist                  | 1         | 0.32%   |
| Panasonic                      | 1         | 0.32%   |
| MOTION                         | 1         | 0.32%   |
| Monster                        | 1         | 0.32%   |
| MobileDemand                   | 1         | 0.32%   |
| MICROBYTE                      | 1         | 0.32%   |
| Matsushita Electric Industrial | 1         | 0.32%   |
| Kogan                          | 1         | 0.32%   |
| HC                             | 1         | 0.32%   |
| GPU Company                    | 1         | 0.32%   |
| Google                         | 1         | 0.32%   |
| Fujitsu Siemens                | 1         | 0.32%   |
| Chuwi                          | 1         | 0.32%   |
| Casper                         | 1         | 0.32%   |
| AMI                            | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 2.22%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 5         | 1.58%   |
| Apple MacBookPro9,2                        | 5         | 1.58%   |
| XIAOMI Redmi Book Pro 15 2023              | 2         | 0.63%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.63%   |
| HUAWEI HVY-WXX9                            | 2         | 0.63%   |
| HP ProBook 640 G1                          | 2         | 0.63%   |
| HP Pavilion Laptop 15-cc1xx                | 2         | 0.63%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.63%   |
| HP Pavilion dv6                            | 2         | 0.63%   |
| HP OMEN Laptop 15-en0xxx                   | 2         | 0.63%   |
| HP OMEN by Laptop 15-dh1xxx                | 2         | 0.63%   |
| HP Notebook                                | 2         | 0.63%   |
| HP Laptop 15-ef2xxx                        | 2         | 0.63%   |
| HP Laptop 15-dy2xxx                        | 2         | 0.63%   |
| HP Laptop 15-da0xxx                        | 2         | 0.63%   |
| Gigabyte G5 MD                             | 2         | 0.63%   |
| Dell XPS 15 9500                           | 2         | 0.63%   |
| Dell Latitude E6420                        | 2         | 0.63%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.63%   |
| ASUS TUF Gaming FX505DT_FX505DT            | 2         | 0.63%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR      | 2         | 0.63%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.63%   |
| Acer Nitro AN515-44                        | 2         | 0.63%   |
| Acer Aspire A515-51G                       | 2         | 0.63%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.32%   |
| Toshiba Satellite C55-A                    | 1         | 0.32%   |
| Sony VPCSB1C5E                             | 1         | 0.32%   |
| Sony SVF1521Q1EW                           | 1         | 0.32%   |
| Samsung R530/R730                          | 1         | 0.32%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.32%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.32%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.32%   |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.32%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.32%   |
| Razer Blade                                | 1         | 0.32%   |
| PC Specialist GK5NPFO                      | 1         | 0.32%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.32%   |
| Notebook W54_W550SU2                       | 1         | 0.32%   |
| Notebook P870DM                            | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 24        | 7.59%   |
| Lenovo IdeaPad        | 23        | 7.28%   |
| Acer Aspire           | 17        | 5.38%   |
| HP Pavilion           | 14        | 4.43%   |
| Dell Inspiron         | 13        | 4.11%   |
| HP Laptop             | 12        | 3.8%    |
| ASUS VivoBook         | 12        | 3.8%    |
| Dell Latitude         | 11        | 3.48%   |
| Lenovo Legion         | 10        | 3.16%   |
| ASUS ROG              | 10        | 3.16%   |
| HP OMEN               | 8         | 2.53%   |
| Dell XPS              | 7         | 2.22%   |
| Acer Nitro            | 7         | 2.22%   |
| Unknown               | 7         | 2.22%   |
| Apple MacBookPro9     | 6         | 1.9%    |
| HP EliteBook          | 5         | 1.58%   |
| Dell Precision        | 5         | 1.58%   |
| HP ProBook            | 4         | 1.27%   |
| Acer Swift            | 4         | 1.27%   |
| Razer Blade           | 3         | 0.95%   |
| Gigabyte G5           | 3         | 0.95%   |
| ASUS Zenbook          | 3         | 0.95%   |
| ASUS TUF              | 3         | 0.95%   |
| ASUS ASUS             | 3         | 0.95%   |
| XIAOMI Redmi          | 2         | 0.63%   |
| Toshiba Satellite     | 2         | 0.63%   |
| MSI Stealth           | 2         | 0.63%   |
| MSI GF63              | 2         | 0.63%   |
| HUAWEI HVY-WXX9       | 2         | 0.63%   |
| HP ZBook              | 2         | 0.63%   |
| HP Victus             | 2         | 0.63%   |
| HP Notebook           | 2         | 0.63%   |
| HP Compaq             | 2         | 0.63%   |
| Sony VPCSB1C5E        | 1         | 0.32%   |
| Sony SVF1521Q1EW      | 1         | 0.32%   |
| Samsung R530          | 1         | 0.32%   |
| Samsung 550XCJ        | 1         | 0.32%   |
| Samsung 340XAA        | 1         | 0.32%   |
| Samsung 300V3A        | 1         | 0.32%   |
| PC Specialist GK5NPFO | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 56        | 17.72%  |
| 2020    | 55        | 17.41%  |
| 2019    | 26        | 8.23%   |
| 2017    | 25        | 7.91%   |
| 2018    | 20        | 6.33%   |
| 2013    | 20        | 6.33%   |
| 2016    | 19        | 6.01%   |
| 2012    | 19        | 6.01%   |
| 2022    | 17        | 5.38%   |
| 2014    | 14        | 4.43%   |
| 2011    | 12        | 3.8%    |
| 2015    | 11        | 3.48%   |
| 2023    | 6         | 1.9%    |
| 2010    | 4         | 1.27%   |
| 2009    | 4         | 1.27%   |
| 2008    | 4         | 1.27%   |
| 2007    | 3         | 0.95%   |
| Unknown | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 316       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 316       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 315       | 99.68%  |
| Yes  | 1         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 98        | 30.82%  |
| 8.01-16.0   | 76        | 23.9%   |
| 16.01-24.0  | 74        | 23.27%  |
| 32.01-64.0  | 32        | 10.06%  |
| 3.01-4.0    | 24        | 7.55%   |
| 24.01-32.0  | 9         | 2.83%   |
| 64.01-256.0 | 4         | 1.26%   |
| 2.01-3.0    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 109       | 31.96%  |
| 3.01-4.0   | 93        | 27.27%  |
| 2.01-3.0   | 80        | 23.46%  |
| 1.01-2.0   | 31        | 9.09%   |
| 8.01-16.0  | 25        | 7.33%   |
| 32.01-64.0 | 1         | 0.29%   |
| 16.01-24.0 | 1         | 0.29%   |
| 0.51-1.0   | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 61.11%  |
| 2      | 102       | 31.48%  |
| 3      | 20        | 6.17%   |
| 4      | 3         | 0.93%   |
| 0      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 246       | 77.36%  |
| Yes       | 72        | 22.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 74.45%  |
| No        | 81        | 25.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 99.05%  |
| No        | 3         | 0.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 285       | 89.91%  |
| No        | 32        | 10.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 80        | 25.08%  |
| Germany            | 31        | 9.72%   |
| India              | 25        | 7.84%   |
| UK                 | 19        | 5.96%   |
| Italy              | 17        | 5.33%   |
| Canada             | 15        | 4.7%    |
| Brazil             | 13        | 4.08%   |
| Poland             | 12        | 3.76%   |
| Turkey             | 7         | 2.19%   |
| France             | 6         | 1.88%   |
| Spain              | 5         | 1.57%   |
| Netherlands        | 5         | 1.57%   |
| Mexico             | 5         | 1.57%   |
| Russia             | 4         | 1.25%   |
| Romania            | 4         | 1.25%   |
| Colombia           | 4         | 1.25%   |
| Switzerland        | 3         | 0.94%   |
| South Africa       | 3         | 0.94%   |
| Indonesia          | 3         | 0.94%   |
| Finland            | 3         | 0.94%   |
| Denmark            | 3         | 0.94%   |
| Belgium            | 3         | 0.94%   |
| Sweden             | 2         | 0.63%   |
| Slovenia           | 2         | 0.63%   |
| Singapore          | 2         | 0.63%   |
| Serbia             | 2         | 0.63%   |
| Pakistan           | 2         | 0.63%   |
| Japan              | 2         | 0.63%   |
| Ecuador            | 2         | 0.63%   |
| Czechia            | 2         | 0.63%   |
| China              | 2         | 0.63%   |
| Austria            | 2         | 0.63%   |
| Australia          | 2         | 0.63%   |
| Argentina          | 2         | 0.63%   |
| Vietnam            | 1         | 0.31%   |
| Venezuela          | 1         | 0.31%   |
| Tunisia            | 1         | 0.31%   |
| Thailand           | 1         | 0.31%   |
| St Kitts and Nevis | 1         | 0.31%   |
| South Korea        | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 4         | 1.19%   |
| Istanbul           | 4         | 1.19%   |
| Hyderabad          | 4         | 1.19%   |
| Berlin             | 4         | 1.19%   |
| Warsaw             | 3         | 0.89%   |
| Mumbai             | 3         | 0.89%   |
| Mississauga        | 3         | 0.89%   |
| Milan              | 3         | 0.89%   |
| Frankfurt am Main  | 3         | 0.89%   |
| Düsseldorf        | 3         | 0.89%   |
| Drums              | 3         | 0.89%   |
| Copenhagen         | 3         | 0.89%   |
| Cape Town          | 3         | 0.89%   |
| Bengaluru          | 3         | 0.89%   |
| Wroclaw            | 2         | 0.59%   |
| Valencia           | 2         | 0.59%   |
| Turin              | 2         | 0.59%   |
| Toronto            | 2         | 0.59%   |
| Sulzbach-Rosenberg | 2         | 0.59%   |
| Southwark          | 2         | 0.59%   |
| Singapore          | 2         | 0.59%   |
| San Jose           | 2         | 0.59%   |
| Prague             | 2         | 0.59%   |
| Portland           | 2         | 0.59%   |
| Peterborough       | 2         | 0.59%   |
| Palermo            | 2         | 0.59%   |
| Noida              | 2         | 0.59%   |
| New York           | 2         | 0.59%   |
| Los Angeles        | 2         | 0.59%   |
| Lancaster          | 2         | 0.59%   |
| Kansas City        | 2         | 0.59%   |
| Helsinki           | 2         | 0.59%   |
| Germantown         | 2         | 0.59%   |
| Delhi              | 2         | 0.59%   |
| Columbus           | 2         | 0.59%   |
| Chennai            | 2         | 0.59%   |
| Bogotá            | 2         | 0.59%   |
| Big Bend           | 2         | 0.59%   |
| Belo Horizonte     | 2         | 0.59%   |
| Belgrade           | 2         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 77        | 96     | 17.19%  |
| Seagate                     | 46        | 50     | 10.27%  |
| SanDisk                     | 37        | 44     | 8.26%   |
| WDC                         | 35        | 38     | 7.81%   |
| SK hynix                    | 33        | 44     | 7.37%   |
| Toshiba                     | 23        | 27     | 5.13%   |
| Unknown                     | 20        | 21     | 4.46%   |
| Intel                       | 20        | 26     | 4.46%   |
| Micron Technology           | 15        | 17     | 3.35%   |
| HGST                        | 15        | 15     | 3.35%   |
| Crucial                     | 12        | 15     | 2.68%   |
| Kingston                    | 10        | 10     | 2.23%   |
| Phison Electronics          | 9         | 11     | 2.01%   |
| KIOXIA                      | 8         | 10     | 1.79%   |
| Hitachi                     | 8         | 8      | 1.79%   |
| SPCC                        | 5         | 5      | 1.12%   |
| Silicon Motion              | 4         | 4      | 0.89%   |
| Kingston Technology Company | 4         | 4      | 0.89%   |
| PNY                         | 3         | 3      | 0.67%   |
| Phison                      | 3         | 3      | 0.67%   |
| Micron/Crucial Technology   | 3         | 3      | 0.67%   |
| LITEON                      | 3         | 3      | 0.67%   |
| Hewlett-Packard             | 3         | 3      | 0.67%   |
| Corsair                     | 3         | 3      | 0.67%   |
| China                       | 3         | 3      | 0.67%   |
| Apple                       | 3         | 4      | 0.67%   |
| ADATA Technology            | 3         | 4      | 0.67%   |
| A-DATA Technology           | 3         | 4      | 0.67%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.45%   |
| SABRENT                     | 2         | 4      | 0.45%   |
| Patriot                     | 2         | 4      | 0.45%   |
| LITEONIT                    | 2         | 2      | 0.45%   |
| JMicron Technology          | 2         | 2      | 0.45%   |
| Intenso                     | 2         | 2      | 0.45%   |
| FORESEE                     | 2         | 2      | 0.45%   |
| Yangtze Memory Technologies | 1         | 1      | 0.22%   |
| WODPOSIT                    | 1         | 2      | 0.22%   |
| WDC WDS                     | 1         | 1      | 0.22%   |
| VisionTek                   | 1         | 2      | 0.22%   |
| Union Memory                | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 10        | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 1.71%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 8         | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 7         | 1.5%    |
| Samsung NVMe SSD Drive 1TB                          | 6         | 1.28%   |
| HGST HTS721010A9E630 1TB                            | 6         | 1.28%   |
| Unknown MMC Card  64GB                              | 5         | 1.07%   |
| Seagate ST1000LM049-2GH172 1TB                      | 5         | 1.07%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 4         | 0.85%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.85%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 4         | 0.85%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 0.85%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 4         | 0.85%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 0.85%   |
| Intel SSD 660P Series 512GB                         | 4         | 0.85%   |
| Toshiba MQ04ABD200 2TB                              | 3         | 0.64%   |
| SPCC Solid State Disk 512GB                         | 3         | 0.64%   |
| SK hynix HFM001TD3JX013N 1TB                        | 3         | 0.64%   |
| Seagate ST2000LM015-2E8174 2TB                      | 3         | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 3         | 0.64%   |
| Samsung SSD 870 EVO 1TB                             | 3         | 0.64%   |
| Phison E12 NVMe Controller 512GB                    | 3         | 0.64%   |
| Hitachi HTS545050B9A300 500GB                       | 3         | 0.64%   |
| HGST HTS725050A7E630 500GB                          | 3         | 0.64%   |
| HP SSD S700 500GB                                   | 3         | 0.64%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.64%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 2         | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 2         | 0.43%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                | 2         | 0.43%   |
| Unknown MMC Card  32GB                              | 2         | 0.43%   |
| Unknown MMC Card  16GB                              | 2         | 0.43%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 0.43%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 0.43%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                       | 2         | 0.43%   |
| SK hynix HFM512GD3JX013N 512GB                      | 2         | 0.43%   |
| Seagate BUP Slim BK 1TB                             | 2         | 0.43%   |
| SanDisk X400 M.2 2280 128GB SSD                     | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 47     | 44.44%  |
| WDC                 | 15        | 17     | 15.15%  |
| HGST                | 15        | 15     | 15.15%  |
| Toshiba             | 13        | 15     | 13.13%  |
| Hitachi             | 8         | 8      | 8.08%   |
| Unknown             | 1         | 1      | 1.01%   |
| Samsung Electronics | 1         | 1      | 1.01%   |
| KESU                | 1         | 1      | 1.01%   |
| Apple               | 1         | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 25.98%  |
| SanDisk             | 12        | 17     | 9.45%   |
| Crucial             | 11        | 14     | 8.66%   |
| WDC                 | 7         | 8      | 5.51%   |
| SK hynix            | 7         | 9      | 5.51%   |
| Kingston            | 6         | 6      | 4.72%   |
| Micron Technology   | 5         | 6      | 3.94%   |
| SPCC                | 4         | 4      | 3.15%   |
| Toshiba             | 3         | 3      | 2.36%   |
| PNY                 | 3         | 3      | 2.36%   |
| LITEON              | 3         | 3      | 2.36%   |
| Hewlett-Packard     | 3         | 3      | 2.36%   |
| China               | 3         | 3      | 2.36%   |
| A-DATA Technology   | 3         | 4      | 2.36%   |
| Patriot             | 2         | 4      | 1.57%   |
| LITEONIT            | 2         | 2      | 1.57%   |
| FORESEE             | 2         | 2      | 1.57%   |
| WODPOSIT            | 1         | 2      | 0.79%   |
| WDC WDS             | 1         | 1      | 0.79%   |
| VisionTek           | 1         | 2      | 0.79%   |
| Transcend           | 1         | 1      | 0.79%   |
| SATAFIRM            | 1         | 1      | 0.79%   |
| PNY CS90            | 1         | 1      | 0.79%   |
| OWC                 | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| Mushkin             | 1         | 1      | 0.79%   |
| Lexar               | 1         | 1      | 0.79%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| Intenso             | 1         | 1      | 0.79%   |
| Emtec               | 1         | 1      | 0.79%   |
| Corsair             | 1         | 1      | 0.79%   |
| ASMT                | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| Unknown             | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 178       | 239    | 42.48%  |
| SSD     | 120       | 149    | 28.64%  |
| HDD     | 94        | 106    | 22.43%  |
| MMC     | 20        | 21     | 4.77%   |
| Unknown | 7         | 7      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 177       | 235    | 45.27%  |
| SATA | 169       | 237    | 43.22%  |
| SAS  | 25        | 29     | 6.39%   |
| MMC  | 20        | 21     | 5.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 130    | 51.64%  |
| 0.51-1.0   | 87        | 107    | 40.85%  |
| 1.01-2.0   | 14        | 16     | 6.57%   |
| 3.01-4.0   | 1         | 1      | 0.47%   |
| 4.01-10.0  | 1         | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 123       | 37.85%  |
| 1001-2000      | 70        | 21.54%  |
| 501-1000       | 56        | 17.23%  |
| 2001-3000      | 31        | 9.54%   |
| 251-500        | 15        | 4.62%   |
| Unknown        | 15        | 4.62%   |
| 1-20           | 11        | 3.38%   |
| 101-250        | 4         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 98        | 29.25%  |
| 251-500        | 57        | 17.01%  |
| 501-1000       | 50        | 14.93%  |
| 51-100         | 43        | 12.84%  |
| 1001-2000      | 35        | 10.45%  |
| Unknown        | 15        | 4.48%   |
| More than 3000 | 14        | 4.18%   |
| 2001-3000      | 12        | 3.58%   |
| 1-20           | 11        | 3.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 2         | 2      | 13.33%  |
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 6.67%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB | 1         | 3      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 6.67%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 6.67%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 6.67%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 6.67%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 6.67%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 6.67%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 26.67%  |
| HGST     | 4         | 4      | 26.67%  |
| WDC      | 2         | 2      | 13.33%  |
| SK hynix | 2         | 4      | 13.33%  |
| Hitachi  | 2         | 2      | 13.33%  |
| SanDisk  | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| HGST    | 4         | 4      | 33.33%  |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 80%     |
| NVMe | 2         | 4      | 13.33%  |
| SSD  | 1         | 1      | 6.67%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 174       | 258    | 49.86%  |
| Detected | 160       | 247    | 45.85%  |
| Malfunc  | 15        | 17     | 4.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 201       | 46.85%  |
| AMD                            | 51        | 11.89%  |
| Samsung Electronics            | 47        | 10.96%  |
| SanDisk                        | 35        | 8.16%   |
| SK hynix                       | 26        | 6.06%   |
| Phison Electronics             | 15        | 3.5%    |
| Micron Technology              | 9         | 2.1%    |
| KIOXIA                         | 8         | 1.86%   |
| Kingston Technology Company    | 8         | 1.86%   |
| Toshiba America Info Systems   | 7         | 1.63%   |
| Union Memory (Shenzhen)        | 4         | 0.93%   |
| Silicon Motion                 | 4         | 0.93%   |
| Micron/Crucial Technology      | 4         | 0.93%   |
| ADATA Technology               | 3         | 0.7%    |
| Solid State Storage Technology | 2         | 0.47%   |
| Yangtze Memory Technologies    | 1         | 0.23%   |
| Nvidia                         | 1         | 0.23%   |
| Marvell Technology Group       | 1         | 0.23%   |
| Lenovo                         | 1         | 0.23%   |
| Apple                          | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50        | 11.04%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 5.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 5.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 4.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 22        | 4.86%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 16        | 3.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15        | 3.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 2.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 12        | 2.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 1.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 1.77%   |
| Intel SSD 660P Series                                                          | 8         | 1.77%   |
| Phison E12 NVMe Controller                                                     | 7         | 1.55%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.32%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 6         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 1.32%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 5         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.1%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.88%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 4         | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3         | 0.66%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.66%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 2         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 207       | 48.36%  |
| NVMe | 175       | 40.89%  |
| RAID | 40        | 9.35%   |
| IDE  | 6         | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 219       | 69.3%   |
| AMD    | 97        | 30.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 3.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 3.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 2.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 2.53%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 2.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 2.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 2.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 1.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.9%    |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 1.58%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.58%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 5         | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.27%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.27%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.27%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 1.27%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 1.27%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.27%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.95%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.95%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.95%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.95%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 3         | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.95%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 0.95%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.95%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 82        | 25.95%  |
| Intel Core i5           | 60        | 18.99%  |
| AMD Ryzen 7             | 35        | 11.08%  |
| Other                   | 33        | 10.44%  |
| AMD Ryzen 5             | 32        | 10.13%  |
| Intel Core i3           | 20        | 6.33%   |
| Intel Celeron           | 10        | 3.16%   |
| AMD Ryzen 9             | 6         | 1.9%    |
| Intel Pentium           | 5         | 1.58%   |
| AMD Ryzen 7 PRO         | 5         | 1.58%   |
| Intel Core 2 Duo        | 4         | 1.27%   |
| AMD A8                  | 4         | 1.27%   |
| AMD Ryzen 3             | 3         | 0.95%   |
| AMD A6                  | 3         | 0.95%   |
| AMD A10                 | 3         | 0.95%   |
| Intel Pentium Silver    | 2         | 0.63%   |
| Intel Pentium Dual-Core | 2         | 0.63%   |
| Intel Xeon              | 1         | 0.32%   |
| Intel Core m3           | 1         | 0.32%   |
| Intel Core i9           | 1         | 0.32%   |
| AMD Turion              | 1         | 0.32%   |
| AMD FX                  | 1         | 0.32%   |
| AMD Athlon              | 1         | 0.32%   |
| AMD A4                  | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 35.44%  |
| 4      | 99        | 31.33%  |
| 8      | 50        | 15.82%  |
| 6      | 47        | 14.87%  |
| 14     | 3         | 0.95%   |
| 12     | 2         | 0.63%   |
| 16     | 1         | 0.32%   |
| 10     | 1         | 0.32%   |
| 1      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 316       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 281       | 88.92%  |
| 1      | 35        | 11.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 316       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 177       | 54.29%  |
| 0x0a50000c | 12        | 3.68%   |
| 0x306a9    | 11        | 3.37%   |
| 0x206a7    | 9         | 2.76%   |
| 0x08108109 | 8         | 2.45%   |
| 0x806c1    | 7         | 2.15%   |
| 0xa0652    | 6         | 1.84%   |
| 0x906ea    | 6         | 1.84%   |
| 0x08600106 | 6         | 1.84%   |
| 0x906e9    | 5         | 1.53%   |
| 0x806ea    | 5         | 1.53%   |
| 0x806e9    | 5         | 1.53%   |
| 0x506e3    | 4         | 1.23%   |
| 0x306c3    | 4         | 1.23%   |
| 0x08600103 | 4         | 1.23%   |
| 0x806ec    | 3         | 0.92%   |
| 0x406e3    | 3         | 0.92%   |
| 0x40651    | 3         | 0.92%   |
| 0x0a50000d | 3         | 0.92%   |
| 0x0a404102 | 3         | 0.92%   |
| 0x08608103 | 3         | 0.92%   |
| 0x08600104 | 3         | 0.92%   |
| 0x08108102 | 3         | 0.92%   |
| 0x06006705 | 3         | 0.92%   |
| 0x906a3    | 2         | 0.61%   |
| 0x106e5    | 2         | 0.61%   |
| 0x0a704103 | 2         | 0.61%   |
| 0x0a601203 | 2         | 0.61%   |
| 0x0a50000b | 2         | 0.61%   |
| 0x08101007 | 2         | 0.61%   |
| 0xa0660    | 1         | 0.31%   |
| 0x806d1    | 1         | 0.31%   |
| 0x706e5    | 1         | 0.31%   |
| 0x706a8    | 1         | 0.31%   |
| 0x706a1    | 1         | 0.31%   |
| 0x506c9    | 1         | 0.31%   |
| 0x406c4    | 1         | 0.31%   |
| 0x306d4    | 1         | 0.31%   |
| 0x20655    | 1         | 0.31%   |
| 0x20652    | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 18.99%  |
| Unknown          | 30        | 9.49%   |
| Zen 3            | 22        | 6.96%   |
| Zen 2            | 21        | 6.65%   |
| Skylake          | 21        | 6.65%   |
| IvyBridge        | 21        | 6.65%   |
| Haswell          | 20        | 6.33%   |
| Zen+             | 17        | 5.38%   |
| SandyBridge      | 17        | 5.38%   |
| TigerLake        | 14        | 4.43%   |
| CometLake        | 14        | 4.43%   |
| Broadwell        | 8         | 2.53%   |
| IceLake          | 6         | 1.9%    |
| Excavator        | 6         | 1.9%    |
| Penryn           | 5         | 1.58%   |
| Goldmont plus    | 5         | 1.58%   |
| Alderlake Hybrid | 5         | 1.58%   |
| Westmere         | 4         | 1.27%   |
| Puma             | 4         | 1.27%   |
| Silvermont       | 3         | 0.95%   |
| Goldmont         | 3         | 0.95%   |
| Zen              | 2         | 0.63%   |
| Piledriver       | 2         | 0.63%   |
| Nehalem          | 2         | 0.63%   |
| Steamroller      | 1         | 0.32%   |
| K8 & K10 hybrid  | 1         | 0.32%   |
| Jaguar           | 1         | 0.32%   |
| Core             | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 205       | 44.76%  |
| Nvidia | 148       | 32.31%  |
| AMD    | 105       | 22.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 21        | 4.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 21        | 4.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 19        | 4.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 18        | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 17        | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 16        | 3.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 14        | 3%      |
| Intel UHD Graphics 620                                                        | 13        | 2.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 12        | 2.57%   |
| Intel HD Graphics 630                                                         | 11        | 2.36%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 10        | 2.14%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 10        | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 10        | 2.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 10        | 2.14%   |
| AMD Lucienne                                                                  | 10        | 2.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 9         | 1.93%   |
| Intel HD Graphics 620                                                         | 9         | 1.93%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 8         | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 8         | 1.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 7         | 1.5%    |
| Intel HD Graphics 5500                                                        | 7         | 1.5%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 6         | 1.28%   |
| Intel HD Graphics 530                                                         | 6         | 1.28%   |
| AMD Rembrandt [Radeon 680M]                                                   | 6         | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 5         | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.07%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 5         | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 5         | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 5         | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 4         | 0.86%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 4         | 0.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 0.86%   |
| Nvidia GM108M [GeForce MX110]                                                 | 3         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                  | 3         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.64%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 3         | 0.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 0.64%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 103       | 32.49%  |
| Intel + Nvidia     | 92        | 29.02%  |
| 1 x AMD            | 54        | 17.03%  |
| AMD + Nvidia       | 40        | 12.62%  |
| 1 x Nvidia         | 14        | 4.42%   |
| Intel + AMD        | 8         | 2.52%   |
| 2 x AMD            | 3         | 0.95%   |
| Intel + 2 x Nvidia | 2         | 0.63%   |
| 2 x Intel          | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 204       | 63.75%  |
| Proprietary | 116       | 36.25%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 231       | 71.08%  |
| 0.01-0.5   | 45        | 13.85%  |
| 1.01-2.0   | 22        | 6.77%   |
| 5.01-6.0   | 9         | 2.77%   |
| 3.01-4.0   | 7         | 2.15%   |
| 0.51-1.0   | 6         | 1.85%   |
| 7.01-8.0   | 5         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 18.8%   |
| Chimei Innolux          | 57        | 15.53%  |
| BOE                     | 54        | 14.71%  |
| LG Display              | 46        | 12.53%  |
| Samsung Electronics     | 31        | 8.45%   |
| Sharp                   | 15        | 4.09%   |
| PANDA                   | 14        | 3.81%   |
| Apple                   | 10        | 2.72%   |
| Dell                    | 9         | 2.45%   |
| Lenovo                  | 7         | 1.91%   |
| Goldstar                | 6         | 1.63%   |
| Acer                    | 5         | 1.36%   |
| Sony                    | 3         | 0.82%   |
| InfoVision              | 3         | 0.82%   |
| CSO                     | 3         | 0.82%   |
| Chi Mei Optoelectronics | 3         | 0.82%   |
| AOC                     | 3         | 0.82%   |
| ViewSonic               | 2         | 0.54%   |
| TMX                     | 2         | 0.54%   |
| Tianma XM               | 2         | 0.54%   |
| Philips                 | 2         | 0.54%   |
| Mi                      | 2         | 0.54%   |
| LGD                     | 2         | 0.54%   |
| Hewlett-Packard         | 2         | 0.54%   |
| BenQ                    | 2         | 0.54%   |
| Vizio                   | 1         | 0.27%   |
| SDC                     | 1         | 0.27%   |
| OUT                     | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |
| InnoLux Display         | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| HKC                     | 1         | 0.27%   |
| G-Story                 | 1         | 0.27%   |
| Eizo                    | 1         | 0.27%   |
| CTO                     | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| BOE Technology Group    | 1         | 0.27%   |
| ASUSTek Computer        | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 1.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 4         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.81%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 0.81%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.81%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.81%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 2         | 0.54%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 2         | 0.54%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 2         | 0.54%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.54%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.54%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 2         | 0.54%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 0.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 2         | 0.54%   |
| BOE LCD Monitor BOE0A1C 1920x1080 344x194mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 0.54%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.54%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 189       | 54.47%  |
| 1366x768 (WXGA)    | 60        | 17.29%  |
| 2560x1440 (QHD)    | 16        | 4.61%   |
| 3840x2160 (4K)     | 15        | 4.32%   |
| 1600x900 (HD+)     | 12        | 3.46%   |
| 1920x1200 (WUXGA)  | 8         | 2.31%   |
| 2560x1600          | 7         | 2.02%   |
| 1280x800 (WXGA)    | 7         | 2.02%   |
| 1680x1050 (WSXGA+) | 6         | 1.73%   |
| 2880x1800          | 5         | 1.44%   |
| 3440x1440          | 3         | 0.86%   |
| 3200x2000          | 2         | 0.58%   |
| 3000x2000          | 2         | 0.58%   |
| 2160x1440          | 2         | 0.58%   |
| 1440x900 (WXGA+)   | 2         | 0.58%   |
| 3840x2400          | 1         | 0.29%   |
| 3520x1080          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 2880x1440          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 1680x945           | 1         | 0.29%   |
| 1600x1200          | 1         | 0.29%   |
| 1280x768           | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |
| 1280x1024 (SXGA)   | 1         | 0.29%   |
| Unknown            | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 188       | 51.23%  |
| 14      | 43        | 11.72%  |
| 13      | 30        | 8.17%   |
| 17      | 25        | 6.81%   |
| 27      | 13        | 3.54%   |
| 16      | 12        | 3.27%   |
| 24      | 9         | 2.45%   |
| 21      | 7         | 1.91%   |
| Unknown | 6         | 1.63%   |
| 18      | 5         | 1.36%   |
| 31      | 4         | 1.09%   |
| 23      | 4         | 1.09%   |
| 72      | 2         | 0.54%   |
| 54      | 2         | 0.54%   |
| 34      | 2         | 0.54%   |
| 22      | 2         | 0.54%   |
| 20      | 2         | 0.54%   |
| 19      | 2         | 0.54%   |
| 11      | 2         | 0.54%   |
| 85      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 43      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 35      | 1         | 0.27%   |
| 28      | 1         | 0.27%   |
| 12      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 246       | 67.4%   |
| 351-400     | 31        | 8.49%   |
| 501-600     | 25        | 6.85%   |
| 201-300     | 23        | 6.3%    |
| 401-500     | 17        | 4.66%   |
| 601-700     | 6         | 1.64%   |
| Unknown     | 6         | 1.64%   |
| 1501-2000   | 3         | 0.82%   |
| 1001-1500   | 3         | 0.82%   |
| 801-900     | 2         | 0.55%   |
| 701-800     | 2         | 0.55%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 276       | 83.38%  |
| 16/10   | 39        | 11.78%  |
| 3/2     | 5         | 1.51%   |
| Unknown | 4         | 1.21%   |
| 21/9    | 3         | 0.91%   |
| 4/3     | 2         | 0.6%    |
| 5/4     | 1         | 0.3%    |
| 2.00    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 190       | 52.05%  |
| 81-90          | 63        | 17.26%  |
| 121-130        | 25        | 6.85%   |
| 201-250        | 18        | 4.93%   |
| 301-350        | 13        | 3.56%   |
| 71-80          | 9         | 2.47%   |
| 351-500        | 8         | 2.19%   |
| 111-120        | 7         | 1.92%   |
| More than 1000 | 6         | 1.64%   |
| Unknown        | 6         | 1.64%   |
| 141-150        | 5         | 1.37%   |
| 151-200        | 4         | 1.1%    |
| 251-300        | 3         | 0.82%   |
| 51-60          | 2         | 0.55%   |
| 501-1000       | 2         | 0.55%   |
| 91-100         | 2         | 0.55%   |
| 61-70          | 1         | 0.27%   |
| 131-140        | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 179       | 49.72%  |
| 101-120       | 86        | 23.89%  |
| 51-100        | 36        | 10%     |
| 161-240       | 30        | 8.33%   |
| More than 240 | 17        | 4.72%   |
| 1-50          | 6         | 1.67%   |
| Unknown       | 6         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 261       | 81.06%  |
| 2     | 58        | 18.01%  |
| 3     | 2         | 0.62%   |
| 0     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 183       | 35.67%  |
| Intel                             | 174       | 33.92%  |
| Qualcomm Atheros                  | 60        | 11.7%   |
| Broadcom                          | 28        | 5.46%   |
| MediaTek                          | 22        | 4.29%   |
| TP-Link                           | 4         | 0.78%   |
| Samsung Electronics               | 4         | 0.78%   |
| Xiaomi                            | 3         | 0.58%   |
| Qualcomm                          | 3         | 0.58%   |
| NetGear                           | 3         | 0.58%   |
| Dell                              | 3         | 0.58%   |
| Wacom                             | 2         | 0.39%   |
| Ralink Technology                 | 2         | 0.39%   |
| DisplayLink                       | 2         | 0.39%   |
| ASUSTek Computer                  | 2         | 0.39%   |
| ASIX Electronics                  | 2         | 0.39%   |
| Unknown                           | 2         | 0.39%   |
| ZyXEL Communications              | 1         | 0.19%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.19%   |
| Sierra Wireless                   | 1         | 0.19%   |
| Shenzhen Goodix Technology        | 1         | 0.19%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.19%   |
| Nvidia                            | 1         | 0.19%   |
| Motorola PCS                      | 1         | 0.19%   |
| Marvell Technology Group          | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| ICS Advent                        | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Dresden Elektronik                | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115       | 19.39%  |
| Intel Wi-Fi 6 AX200                                               | 31        | 5.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 2.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 2.19%   |
| Intel Wireless 7265                                               | 12        | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 10        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.52%   |
| Intel Wireless 7260                                               | 9         | 1.52%   |
| Intel Wireless 3165                                               | 8         | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 7         | 1.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.84%   |
| Intel Wireless 8260                                               | 5         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 167       | 49.85%  |
| Qualcomm Atheros      | 53        | 15.82%  |
| Realtek Semiconductor | 52        | 15.52%  |
| Broadcom              | 23        | 6.87%   |
| MediaTek              | 20        | 5.97%   |
| TP-Link               | 4         | 1.19%   |
| NetGear               | 3         | 0.9%    |
| Wacom                 | 2         | 0.6%    |
| Ralink Technology     | 2         | 0.6%    |
| ASUSTek Computer      | 2         | 0.6%    |
| Unknown               | 2         | 0.6%    |
| ZyXEL Communications  | 1         | 0.3%    |
| Sierra Wireless       | 1         | 0.3%    |
| Qualcomm              | 1         | 0.3%    |
| Hewlett-Packard       | 1         | 0.3%    |
| Dell                  | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31        | 9.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 5.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 4.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 3.85%   |
| Intel Wireless 7265                                            | 12        | 3.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 3.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 3.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 3.25%   |
| Intel Wireless 8265 / 8275                                     | 10        | 2.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 2.66%   |
| Intel Wireless 7260                                            | 9         | 2.66%   |
| Intel Wireless 3165                                            | 8         | 2.37%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 2.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 2.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 2.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.48%   |
| Intel Wireless 8260                                            | 5         | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 0.89%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.89%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 2         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 154       | 63.37%  |
| Intel                      | 44        | 18.11%  |
| Qualcomm Atheros           | 15        | 6.17%   |
| Broadcom                   | 13        | 5.35%   |
| Xiaomi                     | 3         | 1.23%   |
| Qualcomm                   | 2         | 0.82%   |
| MediaTek                   | 2         | 0.82%   |
| DisplayLink                | 2         | 0.82%   |
| ASIX Electronics           | 2         | 0.82%   |
| ZTE WCDMA Technologies MSM | 1         | 0.41%   |
| Samsung Electronics        | 1         | 0.41%   |
| Nvidia                     | 1         | 0.41%   |
| Marvell Technology Group   | 1         | 0.41%   |
| Lenovo                     | 1         | 0.41%   |
| ICS Advent                 | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 115       | 47.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 7.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 2.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 2.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 2.05%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.82%   |
| MediaTek X55                                                      | 2         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.82%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.82%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.41%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.41%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.41%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 313       | 55.89%  |
| Ethernet | 236       | 42.14%  |
| Modem    | 8         | 1.43%   |
| Unknown  | 3         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 271       | 82.87%  |
| Ethernet | 55        | 16.82%  |
| Modem    | 1         | 0.31%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 214       | 67.51%  |
| 1     | 98        | 30.91%  |
| 3     | 4         | 1.26%   |
| 0     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 227       | 70.72%  |
| Yes  | 94        | 29.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 144       | 50.35%  |
| Realtek Semiconductor           | 39        | 13.64%  |
| Qualcomm Atheros Communications | 29        | 10.14%  |
| IMC Networks                    | 16        | 5.59%   |
| Lite-On Technology              | 12        | 4.2%    |
| Foxconn / Hon Hai               | 12        | 4.2%    |
| Apple                           | 9         | 3.15%   |
| Broadcom                        | 8         | 2.8%    |
| Dell                            | 4         | 1.4%    |
| MediaTek                        | 3         | 1.05%   |
| Cambridge Silicon Radio         | 3         | 1.05%   |
| Hewlett-Packard                 | 2         | 0.7%    |
| USI                             | 1         | 0.35%   |
| Realtek                         | 1         | 0.35%   |
| ASUSTek Computer                | 1         | 0.35%   |
| Alps Electric                   | 1         | 0.35%   |
| AboCom Systems                  | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 14.69%  |
| Intel AX201 Bluetooth                               | 31        | 10.84%  |
| Intel AX200 Bluetooth                               | 29        | 10.14%  |
| Realtek Bluetooth Radio                             | 24        | 8.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 4.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 3.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 3.15%   |
| IMC Networks Wireless_Device                        | 8         | 2.8%    |
| Intel AX210 Bluetooth                               | 6         | 2.1%    |
| IMC Networks Bluetooth Radio                        | 6         | 2.1%    |
| Realtek 802.11ac WLAN Adapter                       | 5         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.75%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.4%    |
| Intel Bluetooth Device                              | 4         | 1.4%    |
| Apple Bluetooth Host Controller                     | 4         | 1.4%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 1.05%   |
| Lite-On Wireless_Device                             | 3         | 1.05%   |
| Lite-On Bluetooth Device                            | 3         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.05%   |
| Dell DW375 Bluetooth Module                         | 3         | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.7%    |
| MediaTek Wireless_Device                            | 2         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.7%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.7%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.7%    |
| USI Bluetooth Device                                | 1         | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.35%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.35%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.35%   |
| MediaTek MT7630e Bluetooth Adapter                  | 1         | 0.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.35%   |
| IMC Networks Bluetooth Device                       | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 218       | 52.4%   |
| AMD                       | 98        | 23.56%  |
| Nvidia                    | 80        | 19.23%  |
| RODE Microphones          | 2         | 0.48%   |
| JMTek                     | 2         | 0.48%   |
| Corsair                   | 2         | 0.48%   |
| C-Media Electronics       | 2         | 0.48%   |
| Turtle Beach              | 1         | 0.24%   |
| Texas Instruments         | 1         | 0.24%   |
| Sennheiser Communications | 1         | 0.24%   |
| Realtek Semiconductor     | 1         | 0.24%   |
| Phison Electronics        | 1         | 0.24%   |
| M-Audio                   | 1         | 0.24%   |
| Logitech                  | 1         | 0.24%   |
| Huawei Technologies       | 1         | 0.24%   |
| GN Netcom                 | 1         | 0.24%   |
| Generalplus Technology    | 1         | 0.24%   |
| FX200                     | 1         | 0.24%   |
| BR25                      | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 81        | 15.67%  |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 6.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 6.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 4.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 2.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 2.51%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 2.51%   |
| Intel CM238 HD Audio Controller                                            | 12        | 2.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 2.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 1.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 1.93%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 1.93%   |
| Nvidia Audio device                                                        | 9         | 1.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.55%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 1.55%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 4         | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 75        | 27.47%  |
| SK hynix            | 63        | 23.08%  |
| Micron Technology   | 40        | 14.65%  |
| Crucial             | 20        | 7.33%   |
| Kingston            | 16        | 5.86%   |
| Ramaxel Technology  | 10        | 3.66%   |
| A-DATA Technology   | 7         | 2.56%   |
| Unknown             | 6         | 2.2%    |
| Unknown (ABCD)      | 5         | 1.83%   |
| Nanya Technology    | 5         | 1.83%   |
| Corsair             | 4         | 1.47%   |
| Smart               | 3         | 1.1%    |
| Transcend           | 2         | 0.73%   |
| Hewlett-Packard     | 2         | 0.73%   |
| Unknown             | 2         | 0.73%   |
| Wilk                | 1         | 0.37%   |
| Timetec             | 1         | 0.37%   |
| Team                | 1         | 0.37%   |
| Smart Brazil        | 1         | 0.37%   |
| Sesame              | 1         | 0.37%   |
| PNY                 | 1         | 0.37%   |
| Patriot             | 1         | 0.37%   |
| GOODRAM             | 1         | 0.37%   |
| G.Skill             | 1         | 0.37%   |
| Elpida              | 1         | 0.37%   |
| CSX                 | 1         | 0.37%   |
| Avant               | 1         | 0.37%   |
| 48spaces            | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 2.09%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 2.09%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.05%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 1.05%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.05%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 3         | 1.05%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s                       | 3         | 1.05%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 1.05%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.05%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s        | 2         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.7%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.7%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.7%    |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 2         | 0.7%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 2         | 0.7%    |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 0.7%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.7%    |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 137       | 60.35%  |
| DDR3   | 55        | 24.23%  |
| LPDDR4 | 12        | 5.29%   |
| DDR5   | 9         | 3.96%   |
| LPDDR3 | 6         | 2.64%   |
| LPDDR5 | 4         | 1.76%   |
| DDR2   | 3         | 1.32%   |
| SDRAM  | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 209       | 90.48%  |
| Row Of Chips | 20        | 8.66%   |
| Chip         | 1         | 0.43%   |
| Unknown      | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 126       | 50%     |
| 4096  | 71        | 28.17%  |
| 16384 | 42        | 16.67%  |
| 2048  | 7         | 2.78%   |
| 32768 | 6         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 72        | 28.8%   |
| 2667  | 53        | 21.2%   |
| 1600  | 45        | 18%     |
| 2400  | 25        | 10%     |
| 2133  | 11        | 4.4%    |
| 4800  | 7         | 2.8%    |
| 1334  | 7         | 2.8%    |
| 4266  | 5         | 2%      |
| 1333  | 5         | 2%      |
| 6400  | 3         | 1.2%    |
| 3266  | 3         | 1.2%    |
| 5600  | 2         | 0.8%    |
| 1867  | 2         | 0.8%    |
| 800   | 2         | 0.8%    |
| 667   | 2         | 0.8%    |
| 8400  | 1         | 0.4%    |
| 7467  | 1         | 0.4%    |
| 4199  | 1         | 0.4%    |
| 3733  | 1         | 0.4%    |
| 2933  | 1         | 0.4%    |
| 1866  | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Kyocera             | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series  | 1         | 33.33%  |
| Kyocera FS-1030D printer        | 1         | 33.33%  |
| HP LaserJet 200 colorMFP M275nw | 1         | 33.33%  |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 68        | 24.2%   |
| IMC Networks                           | 39        | 13.88%  |
| Quanta                                 | 23        | 8.19%   |
| Microdia                               | 21        | 7.47%   |
| Realtek Semiconductor                  | 20        | 7.12%   |
| Sunplus Innovation Technology          | 15        | 5.34%   |
| Bison Electronics                      | 15        | 5.34%   |
| Luxvisions Innotech Limited            | 11        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.91%   |
| Syntek                                 | 9         | 3.2%    |
| Apple                                  | 9         | 3.2%    |
| Suyin                                  | 6         | 2.14%   |
| Logitech                               | 5         | 1.78%   |
| Sonix Technology                       | 3         | 1.07%   |
| Silicon Motion                         | 3         | 1.07%   |
| Lite-On Technology                     | 3         | 1.07%   |
| Acer                                   | 3         | 1.07%   |
| SunplusIT                              | 2         | 0.71%   |
| Primax Electronics                     | 2         | 0.71%   |
| Microsoft                              | 2         | 0.71%   |
| Alcor Micro                            | 2         | 0.71%   |
| WaveRider Communications               | 1         | 0.36%   |
| ShineTech                              | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| Lenovo                                 | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| Genesys Logic                          | 1         | 0.36%   |
| GEMBIRD                                | 1         | 0.36%   |
| DigiTech                               | 1         | 0.36%   |
| Creative Technology                    | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 18        | 6.38%   |
| IMC Networks Integrated Camera                       | 13        | 4.61%   |
| Microdia Integrated_Webcam_HD                        | 12        | 4.26%   |
| Chicony Integrated Camera                            | 12        | 4.26%   |
| Chicony HD WebCam                                    | 10        | 3.55%   |
| Syntek Integrated Camera                             | 7         | 2.48%   |
| Sunplus Integrated_Webcam_HD                         | 7         | 2.48%   |
| Apple FaceTime HD Camera                             | 7         | 2.48%   |
| Quanta HD User Facing                                | 6         | 2.13%   |
| Chicony HD User Facing                               | 6         | 2.13%   |
| Quanta HP Wide Vision HD Camera                      | 5         | 1.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 1.77%   |
| Chicony HP Wide Vision HD Camera                     | 5         | 1.77%   |
| Bison Integrated Camera                              | 5         | 1.77%   |
| Bison HD Webcam                                      | 5         | 1.77%   |
| Realtek Integrated_Webcam_HD                         | 4         | 1.42%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 1.42%   |
| Chicony USB2.0 Camera                                | 4         | 1.42%   |
| Realtek USB Camera                                   | 3         | 1.06%   |
| Logitech HD Pro Webcam C920                          | 3         | 1.06%   |
| IMC Networks HD Camera                               | 3         | 1.06%   |
| Chicony Integrated HD WebCam                         | 3         | 1.06%   |
| Chicony HP Truevision HD                             | 3         | 1.06%   |
| Chicony EasyCamera                                   | 3         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 3         | 1.06%   |
| SunplusIT XiaoMi USB 2.0 Webcam                      | 2         | 0.71%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.71%   |
| Silicon Motion Web Camera                            | 2         | 0.71%   |
| Realtek Laptop_Integrated_Webcam_HD                  | 2         | 0.71%   |
| Realtek HP Truevision HD                             | 2         | 0.71%   |
| Quanta HP TrueVision HD Camera                       | 2         | 0.71%   |
| Quanta HD Camera                                     | 2         | 0.71%   |
| Primax HP HD Webcam [Fixed]                          | 2         | 0.71%   |
| Microdia Webcam Vitade AF                            | 2         | 0.71%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.71%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                         | 2         | 0.71%   |
| Chicony Lenovo EasyCamera                            | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 36.73%  |
| Elan Microelectronics      | 9         | 18.37%  |
| Synaptics                  | 8         | 16.33%  |
| Shenzhen Goodix Technology | 5         | 10.2%   |
| LighTuning Technology      | 5         | 10.2%   |
| AuthenTec                  | 3         | 6.12%   |
| Focal-systems.Corp         | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 6         | 12.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 8.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6.12%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 6.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 6.12%   |
| Elan ELAN:Fingerprint                                                      | 3         | 6.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 4.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 4.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.08%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 4.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 4.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS491                                                    | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Synaptics WBDI Device                                                      | 1         | 2.04%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.04%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 2.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.04%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.04%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.04%   |
| AuthenTec AES2810                                                          | 1         | 2.04%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 12        | 57.14%  |
| Alcor Micro      | 6         | 28.57%  |
| Upek             | 1         | 4.76%   |
| SCM Microsystems | 1         | 4.76%   |
| Lenovo           | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 23.81%  |
| Broadcom 5880                                                                | 4         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.76%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 51.24%  |
| 0     | 75        | 23.29%  |
| 2     | 67        | 20.81%  |
| 3     | 14        | 4.35%   |
| 4     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 210       | 60.34%  |
| Fingerprint reader       | 49        | 14.08%  |
| Graphics card            | 24        | 6.9%    |
| Chipcard                 | 20        | 5.75%   |
| Net/wireless             | 12        | 3.45%   |
| Multimedia controller    | 12        | 3.45%   |
| Camera                   | 6         | 1.72%   |
| Net/ethernet             | 5         | 1.44%   |
| Storage                  | 4         | 1.15%   |
| Network                  | 3         | 0.86%   |
| Bluetooth                | 2         | 0.57%   |
| Wireless                 | 1         | 0.29%   |

