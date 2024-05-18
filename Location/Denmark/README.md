Linux in Denmark - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Denmark/Desktop/README.md) and [notebooks](/Location/Denmark/Notebook/README.md).

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

Total: 1671

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro9,1               | Notebook    | [6d6aee3150](https://linux-hardware.org/?probe=6d6aee3150) | May 09, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [2c63121414](https://linux-hardware.org/?probe=2c63121414) | May 09, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1a1e8edc3b](https://linux-hardware.org/?probe=1a1e8edc3b) | May 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [c87a91f892](https://linux-hardware.org/?probe=c87a91f892) | May 07, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [6ee8d65521](https://linux-hardware.org/?probe=6ee8d65521) | May 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [2fdf2caa36](https://linux-hardware.org/?probe=2fdf2caa36) | May 05, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [9c6cf56bbb](https://linux-hardware.org/?probe=9c6cf56bbb) | May 05, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5975b5df1b](https://linux-hardware.org/?probe=5975b5df1b) | May 04, 2024 |
| Lenovo        | ThinkPad T450 20BUS2SS00    | Notebook    | [5d764e707b](https://linux-hardware.org/?probe=5d764e707b) | May 04, 2024 |
| Supermicro    | X13DAI-T                    | Server      | [a261fe87ad](https://linux-hardware.org/?probe=a261fe87ad) | May 03, 2024 |
| Intel         | DP45SG AAE27733-405         | Desktop     | [a255bc14ce](https://linux-hardware.org/?probe=a255bc14ce) | May 03, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [ad5d8cbdf2](https://linux-hardware.org/?probe=ad5d8cbdf2) | May 03, 2024 |
| Lenovo        | ThinkPad T480S 20L7001PM... | Notebook    | [4baef88334](https://linux-hardware.org/?probe=4baef88334) | May 03, 2024 |
| ASUSTek       | PRO H410T                   | Desktop     | [88ac4bb06e](https://linux-hardware.org/?probe=88ac4bb06e) | May 01, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [901ee2545c](https://linux-hardware.org/?probe=901ee2545c) | Apr 30, 2024 |
| Acer          | Aspire 7741                 | Notebook    | [69f109864f](https://linux-hardware.org/?probe=69f109864f) | Apr 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3f5beab74c](https://linux-hardware.org/?probe=3f5beab74c) | Apr 28, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [923b49223a](https://linux-hardware.org/?probe=923b49223a) | Apr 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [66f95f549d](https://linux-hardware.org/?probe=66f95f549d) | Apr 27, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7011148205](https://linux-hardware.org/?probe=7011148205) | Apr 27, 2024 |
| ASUSTek       | PRO H410T                   | Desktop     | [9111d77eb9](https://linux-hardware.org/?probe=9111d77eb9) | Apr 26, 2024 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [6d342ea232](https://linux-hardware.org/?probe=6d342ea232) | Apr 26, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [0aeb871159](https://linux-hardware.org/?probe=0aeb871159) | Apr 22, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [967c710a95](https://linux-hardware.org/?probe=967c710a95) | Apr 19, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [ab7744c990](https://linux-hardware.org/?probe=ab7744c990) | Apr 19, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [f2d598a8a4](https://linux-hardware.org/?probe=f2d598a8a4) | Apr 19, 2024 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [58afd7824e](https://linux-hardware.org/?probe=58afd7824e) | Apr 19, 2024 |
| Dell          | 0VD5HY A07                  | Desktop     | [2ebf9fa814](https://linux-hardware.org/?probe=2ebf9fa814) | Apr 18, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [8c7365ffeb](https://linux-hardware.org/?probe=8c7365ffeb) | Apr 17, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [3b4a5c61ff](https://linux-hardware.org/?probe=3b4a5c61ff) | Apr 17, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [5e92237577](https://linux-hardware.org/?probe=5e92237577) | Apr 16, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [a00d0bb1b4](https://linux-hardware.org/?probe=a00d0bb1b4) | Apr 16, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [31768a3251](https://linux-hardware.org/?probe=31768a3251) | Apr 13, 2024 |
| ASUSTek       | P6X58D-E                    | Desktop     | [143efb64e8](https://linux-hardware.org/?probe=143efb64e8) | Apr 12, 2024 |
| ASUSTek       | EB1503                      | Notebook    | [21afa9fbb5](https://linux-hardware.org/?probe=21afa9fbb5) | Apr 10, 2024 |
| Samsung       | 930XCJ/931XCJ/930XCR        | Notebook    | [c08adc1120](https://linux-hardware.org/?probe=c08adc1120) | Apr 09, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [9868b5573c](https://linux-hardware.org/?probe=9868b5573c) | Apr 07, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | Notebook    | [1658229b9a](https://linux-hardware.org/?probe=1658229b9a) | Apr 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a93a4109d7](https://linux-hardware.org/?probe=a93a4109d7) | Apr 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b51e077a23](https://linux-hardware.org/?probe=b51e077a23) | Apr 07, 2024 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [0bb98b6d5d](https://linux-hardware.org/?probe=0bb98b6d5d) | Apr 06, 2024 |
| Dell          | Latitude E7440              | Notebook    | [dbc6236ae1](https://linux-hardware.org/?probe=dbc6236ae1) | Apr 06, 2024 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [a2838e8dc8](https://linux-hardware.org/?probe=a2838e8dc8) | Apr 06, 2024 |
| Unknown       | TK23D                       | Notebook    | [47ffc66996](https://linux-hardware.org/?probe=47ffc66996) | Apr 05, 2024 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [a7245399da](https://linux-hardware.org/?probe=a7245399da) | Apr 05, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [09a8421999](https://linux-hardware.org/?probe=09a8421999) | Apr 04, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [63429edd54](https://linux-hardware.org/?probe=63429edd54) | Apr 01, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [10b376d6b8](https://linux-hardware.org/?probe=10b376d6b8) | Apr 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [77d2d8ef3e](https://linux-hardware.org/?probe=77d2d8ef3e) | Mar 31, 2024 |
| HP            | 1495                        | Desktop     | [dd31afc968](https://linux-hardware.org/?probe=dd31afc968) | Mar 29, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [070fdbee15](https://linux-hardware.org/?probe=070fdbee15) | Mar 29, 2024 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [bc2f245e57](https://linux-hardware.org/?probe=bc2f245e57) | Mar 28, 2024 |
| HP            | 829A                        | Mini pc     | [7a40583e00](https://linux-hardware.org/?probe=7a40583e00) | Mar 26, 2024 |
| HP            | 829A                        | Mini pc     | [20b59f532b](https://linux-hardware.org/?probe=20b59f532b) | Mar 26, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [4aa12cd64e](https://linux-hardware.org/?probe=4aa12cd64e) | Mar 24, 2024 |
| HP            | 1495                        | Desktop     | [36d31b0971](https://linux-hardware.org/?probe=36d31b0971) | Mar 24, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [45e2102834](https://linux-hardware.org/?probe=45e2102834) | Mar 23, 2024 |
| HP            | Pavilion dv9700             | Notebook    | [6851f7a21a](https://linux-hardware.org/?probe=6851f7a21a) | Mar 22, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [3764bad531](https://linux-hardware.org/?probe=3764bad531) | Mar 21, 2024 |
| Razer         | Blade Stealth               | Notebook    | [427d6b97d0](https://linux-hardware.org/?probe=427d6b97d0) | Mar 20, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [a72ccae833](https://linux-hardware.org/?probe=a72ccae833) | Mar 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5bfcaa91cf](https://linux-hardware.org/?probe=5bfcaa91cf) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9DL0... | Notebook    | [0df7e53a5b](https://linux-hardware.org/?probe=0df7e53a5b) | Mar 19, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fc818b5a1b](https://linux-hardware.org/?probe=fc818b5a1b) | Mar 18, 2024 |
| Lenovo        | ThinkPad T410 2537PW4       | Notebook    | [29306b301d](https://linux-hardware.org/?probe=29306b301d) | Mar 15, 2024 |
| Dell          | Precision 7530              | Notebook    | [d78921804c](https://linux-hardware.org/?probe=d78921804c) | Mar 15, 2024 |
| Radxa         | ROCK 5B                     | Soc         | [196e6ef733](https://linux-hardware.org/?probe=196e6ef733) | Mar 13, 2024 |
| Intel         | X79G-A V2.0                 | Desktop     | [87e5ff547d](https://linux-hardware.org/?probe=87e5ff547d) | Mar 12, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [f18604dfcc](https://linux-hardware.org/?probe=f18604dfcc) | Mar 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [66ebc0d790](https://linux-hardware.org/?probe=66ebc0d790) | Mar 11, 2024 |
| ASRock        | Z170 Gaming-ITX/ac          | Desktop     | [7531c7cfa0](https://linux-hardware.org/?probe=7531c7cfa0) | Mar 09, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [2e420dae7e](https://linux-hardware.org/?probe=2e420dae7e) | Mar 09, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [cdf2cddb43](https://linux-hardware.org/?probe=cdf2cddb43) | Mar 08, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [321f40d2d0](https://linux-hardware.org/?probe=321f40d2d0) | Mar 08, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [16b3359307](https://linux-hardware.org/?probe=16b3359307) | Mar 07, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4d569e557d](https://linux-hardware.org/?probe=4d569e557d) | Mar 07, 2024 |
| ASUSTek       | EP121                       | Notebook    | [6f48afbbb5](https://linux-hardware.org/?probe=6f48afbbb5) | Mar 04, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [3a49dcc141](https://linux-hardware.org/?probe=3a49dcc141) | Mar 02, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6678e6f966](https://linux-hardware.org/?probe=6678e6f966) | Mar 01, 2024 |
| ASRock        | Z170 Gaming-ITX/ac          | Desktop     | [0e48c7f78f](https://linux-hardware.org/?probe=0e48c7f78f) | Mar 01, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [6573368c36](https://linux-hardware.org/?probe=6573368c36) | Mar 01, 2024 |
| ASRock        | H97M Pro4                   | Desktop     | [a23d199357](https://linux-hardware.org/?probe=a23d199357) | Feb 29, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [e64f4ad280](https://linux-hardware.org/?probe=e64f4ad280) | Feb 29, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [d8df626171](https://linux-hardware.org/?probe=d8df626171) | Feb 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c011a124eb](https://linux-hardware.org/?probe=c011a124eb) | Feb 24, 2024 |
| MSI           | MS-6657                     | All in one  | [5ee9e014c8](https://linux-hardware.org/?probe=5ee9e014c8) | Feb 24, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [63323ac7cf](https://linux-hardware.org/?probe=63323ac7cf) | Feb 23, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [5f1e566662](https://linux-hardware.org/?probe=5f1e566662) | Feb 22, 2024 |
| Lenovo        | ThinkPad T570 20H9001EMD    | Notebook    | [0841df80ee](https://linux-hardware.org/?probe=0841df80ee) | Feb 21, 2024 |
| Lenovo        | ThinkPad T460 20FMS4E900    | Notebook    | [c8b5b2db19](https://linux-hardware.org/?probe=c8b5b2db19) | Feb 20, 2024 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [e79901c3be](https://linux-hardware.org/?probe=e79901c3be) | Feb 19, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [52b073c49b](https://linux-hardware.org/?probe=52b073c49b) | Feb 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [bf621b6156](https://linux-hardware.org/?probe=bf621b6156) | Feb 18, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [0e347d9f9e](https://linux-hardware.org/?probe=0e347d9f9e) | Feb 17, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [a3c86997db](https://linux-hardware.org/?probe=a3c86997db) | Feb 11, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [ea6f15d115](https://linux-hardware.org/?probe=ea6f15d115) | Feb 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [2d7a44f48a](https://linux-hardware.org/?probe=2d7a44f48a) | Feb 09, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [26118c8441](https://linux-hardware.org/?probe=26118c8441) | Feb 09, 2024 |
| Lenovo        | ThinkPad L440 20AT0020US    | Notebook    | [1b7b76a553](https://linux-hardware.org/?probe=1b7b76a553) | Feb 09, 2024 |
| Lenovo        | ThinkPad T470 20HES20V02    | Notebook    | [58ebcebabd](https://linux-hardware.org/?probe=58ebcebabd) | Feb 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [86d506e6eb](https://linux-hardware.org/?probe=86d506e6eb) | Feb 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [49de677b38](https://linux-hardware.org/?probe=49de677b38) | Feb 08, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [521842d39b](https://linux-hardware.org/?probe=521842d39b) | Feb 07, 2024 |
| Lenovo        | ThinkPad L440 20AT0020US    | Notebook    | [31fe816ba8](https://linux-hardware.org/?probe=31fe816ba8) | Feb 05, 2024 |
| HP            | 8876 11                     | Desktop     | [79f1a90d1b](https://linux-hardware.org/?probe=79f1a90d1b) | Feb 04, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [a52e3353f6](https://linux-hardware.org/?probe=a52e3353f6) | Feb 03, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [74173e2c0a](https://linux-hardware.org/?probe=74173e2c0a) | Feb 01, 2024 |
| ASUSTek       | K54C                        | Notebook    | [59e4e733f0](https://linux-hardware.org/?probe=59e4e733f0) | Feb 01, 2024 |
| ASUSTek       | T-P5G31A                    | Desktop     | [ca450a3a63](https://linux-hardware.org/?probe=ca450a3a63) | Jan 28, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [d8ab9529f3](https://linux-hardware.org/?probe=d8ab9529f3) | Jan 27, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | Notebook    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [789bbeb50a](https://linux-hardware.org/?probe=789bbeb50a) | Jan 24, 2024 |
| MSI           | Z170A TOMAHAWK AC           | Desktop     | [bd66397010](https://linux-hardware.org/?probe=bd66397010) | Jan 23, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e9bc4f9199](https://linux-hardware.org/?probe=e9bc4f9199) | Jan 22, 2024 |
| ASUSTek       | K56CB                       | Notebook    | [5cc6df781d](https://linux-hardware.org/?probe=5cc6df781d) | Jan 20, 2024 |
| HP            | 829A                        | Mini pc     | [e2d69ba528](https://linux-hardware.org/?probe=e2d69ba528) | Jan 19, 2024 |
| HP            | 829A                        | Mini pc     | [ee6750b80c](https://linux-hardware.org/?probe=ee6750b80c) | Jan 19, 2024 |
| Toshiba       | Satellite C855D-11X         | Notebook    | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b98e94bfb3](https://linux-hardware.org/?probe=b98e94bfb3) | Jan 13, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [f26cc3860a](https://linux-hardware.org/?probe=f26cc3860a) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [b521a115f8](https://linux-hardware.org/?probe=b521a115f8) | Jan 12, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7d95af598c](https://linux-hardware.org/?probe=7d95af598c) | Jan 12, 2024 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [7049dd3f9a](https://linux-hardware.org/?probe=7049dd3f9a) | Jan 12, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [739397b2fd](https://linux-hardware.org/?probe=739397b2fd) | Jan 10, 2024 |
| Lenovo        | ThinkPad T560 20FH001BMD    | Notebook    | [aefb2eccb9](https://linux-hardware.org/?probe=aefb2eccb9) | Jan 09, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [052f307ab5](https://linux-hardware.org/?probe=052f307ab5) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [70681bd4a7](https://linux-hardware.org/?probe=70681bd4a7) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [bbe152d4f5](https://linux-hardware.org/?probe=bbe152d4f5) | Jan 07, 2024 |
| Apple         | MacBookPro13,2              | Notebook    | [c7e8eb2475](https://linux-hardware.org/?probe=c7e8eb2475) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [af48a525ff](https://linux-hardware.org/?probe=af48a525ff) | Jan 06, 2024 |
| HP            | 1495                        | Desktop     | [90db2bac77](https://linux-hardware.org/?probe=90db2bac77) | Jan 05, 2024 |
| HP            | 18E4                        | Desktop     | [e89784f165](https://linux-hardware.org/?probe=e89784f165) | Jan 05, 2024 |
| HP            | 8158 A01                    | Mini pc     | [c9978d8ea8](https://linux-hardware.org/?probe=c9978d8ea8) | Jan 04, 2024 |
| ASUSTek       | A4320A6420                  | Desktop     | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Notebook      | N14xWU                      | Notebook    | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | Notebook    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HP            | Compaq 2510p                | Notebook    | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [344f1c919a](https://linux-hardware.org/?probe=344f1c919a) | Dec 27, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [c55e7a4304](https://linux-hardware.org/?probe=c55e7a4304) | Dec 26, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [fa299ed27d](https://linux-hardware.org/?probe=fa299ed27d) | Dec 26, 2023 |
| MSI           | MS-B090                     | All in one  | [0f3dce1bfb](https://linux-hardware.org/?probe=0f3dce1bfb) | Dec 26, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [fb78f052e1](https://linux-hardware.org/?probe=fb78f052e1) | Dec 25, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2feb704b34](https://linux-hardware.org/?probe=2feb704b34) | Dec 19, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [31b0444771](https://linux-hardware.org/?probe=31b0444771) | Dec 18, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| HP            | 829A                        | Mini pc     | [f7866b4175](https://linux-hardware.org/?probe=f7866b4175) | Dec 16, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | Notebook    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [279ade4fb0](https://linux-hardware.org/?probe=279ade4fb0) | Dec 16, 2023 |
| Medion        | P7624                       | Notebook    | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| HP            | 1497                        | Desktop     | [f2951d81c8](https://linux-hardware.org/?probe=f2951d81c8) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Dell          | Latitude E6540              | Notebook    | [0d56fcda0e](https://linux-hardware.org/?probe=0d56fcda0e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| Unknown       | TK23D                       | Notebook    | [27c0f3c1f6](https://linux-hardware.org/?probe=27c0f3c1f6) | Dec 07, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [f47146cdb9](https://linux-hardware.org/?probe=f47146cdb9) | Dec 07, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | Notebook    | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Acer          | Aspire V5-573               | Notebook    | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | Notebook    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a8e3339ba9](https://linux-hardware.org/?probe=a8e3339ba9) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [d1e2c905e1](https://linux-hardware.org/?probe=d1e2c905e1) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Gigabyte      | B650M DS3H                  | Notebook    | [dfcb329b5a](https://linux-hardware.org/?probe=dfcb329b5a) | Nov 23, 2023 |
| MSI           | IONA                        | Desktop     | [ccadf6afaf](https://linux-hardware.org/?probe=ccadf6afaf) | Nov 21, 2023 |
| ADLINK Tec... | MXE5400                     | Desktop     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| Sony          | SVE14A2M6EW                 | Notebook    | [9f444d1508](https://linux-hardware.org/?probe=9f444d1508) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| HP            | 829A                        | Mini pc     | [54421db755](https://linux-hardware.org/?probe=54421db755) | Nov 12, 2023 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [bdba8f221d](https://linux-hardware.org/?probe=bdba8f221d) | Nov 12, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [f5f9243038](https://linux-hardware.org/?probe=f5f9243038) | Nov 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [5d950043f1](https://linux-hardware.org/?probe=5d950043f1) | Nov 10, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [0940fc528f](https://linux-hardware.org/?probe=0940fc528f) | Nov 09, 2023 |
| Dell          | Precision M4600             | Notebook    | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| HP            | 1495                        | Desktop     | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | Notebook    | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| Dell          | Precision 5750              | Notebook    | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f54d8e7dea](https://linux-hardware.org/?probe=f54d8e7dea) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9a2f1f7750](https://linux-hardware.org/?probe=9a2f1f7750) | Nov 01, 2023 |
| Intel         | NUC11ATBPE M49844-400       | Mini pc     | [78fabfef55](https://linux-hardware.org/?probe=78fabfef55) | Oct 31, 2023 |
| Intel         | NUC11ATBPE M49844-400       | Mini pc     | [623c5e86d7](https://linux-hardware.org/?probe=623c5e86d7) | Oct 31, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [e8252549f4](https://linux-hardware.org/?probe=e8252549f4) | Oct 29, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [783a3b6555](https://linux-hardware.org/?probe=783a3b6555) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Packard Be... | IMEDIA S2380                | Desktop     | [905b7ea7f0](https://linux-hardware.org/?probe=905b7ea7f0) | Oct 20, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [999de2ca37](https://linux-hardware.org/?probe=999de2ca37) | Oct 16, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [95ef83d6fd](https://linux-hardware.org/?probe=95ef83d6fd) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [81ece14527](https://linux-hardware.org/?probe=81ece14527) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [1323f200dd](https://linux-hardware.org/?probe=1323f200dd) | Oct 01, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9c2ba935b9](https://linux-hardware.org/?probe=9c2ba935b9) | Sep 29, 2023 |
| Google        | Lindar                      | Notebook    | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| Google        | Droid                       | Notebook    | [fa5f650f3a](https://linux-hardware.org/?probe=fa5f650f3a) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf4e6d50dd](https://linux-hardware.org/?probe=cf4e6d50dd) | Sep 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0YE0... | Notebook    | [20c9a90aca](https://linux-hardware.org/?probe=20c9a90aca) | Sep 24, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [d663285ae0](https://linux-hardware.org/?probe=d663285ae0) | Sep 19, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [72c4bdf239](https://linux-hardware.org/?probe=72c4bdf239) | Sep 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd9d93d90d](https://linux-hardware.org/?probe=fd9d93d90d) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [72fe934225](https://linux-hardware.org/?probe=72fe934225) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6467570d4](https://linux-hardware.org/?probe=f6467570d4) | Sep 11, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| ASUSTek       | Strix GL504GM_GL504GM       | Notebook    | [3297d8f0aa](https://linux-hardware.org/?probe=3297d8f0aa) | Sep 10, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | Notebook    | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [653fbbb509](https://linux-hardware.org/?probe=653fbbb509) | Sep 04, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [b423b914f7](https://linux-hardware.org/?probe=b423b914f7) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [8bd315f814](https://linux-hardware.org/?probe=8bd315f814) | Aug 30, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [52306fce15](https://linux-hardware.org/?probe=52306fce15) | Aug 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8b3456ba84](https://linux-hardware.org/?probe=8b3456ba84) | Aug 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [484e6e6997](https://linux-hardware.org/?probe=484e6e6997) | Aug 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [3f7455be45](https://linux-hardware.org/?probe=3f7455be45) | Aug 27, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [595afb8cf0](https://linux-hardware.org/?probe=595afb8cf0) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| HP            | 1905                        | Desktop     | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [7a89f9b5a7](https://linux-hardware.org/?probe=7a89f9b5a7) | Aug 26, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [c2e1396370](https://linux-hardware.org/?probe=c2e1396370) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | Notebook    | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [d68939adcf](https://linux-hardware.org/?probe=d68939adcf) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| HP            | Pavilion dv9500             | Notebook    | [d5cc7639c3](https://linux-hardware.org/?probe=d5cc7639c3) | Aug 21, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5ae66b0d4a](https://linux-hardware.org/?probe=5ae66b0d4a) | Aug 18, 2023 |
| Dell          | Latitude 5540               | Notebook    | [d1f00897b3](https://linux-hardware.org/?probe=d1f00897b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | Notebook    | [0c47627604](https://linux-hardware.org/?probe=0c47627604) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [70eda3a12d](https://linux-hardware.org/?probe=70eda3a12d) | Aug 18, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a77f908bb5](https://linux-hardware.org/?probe=a77f908bb5) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [508611b16c](https://linux-hardware.org/?probe=508611b16c) | Aug 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [3474fa639e](https://linux-hardware.org/?probe=3474fa639e) | Aug 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G3 3590                     | Notebook    | [56d5cdc390](https://linux-hardware.org/?probe=56d5cdc390) | Aug 04, 2023 |
| Sony          | SVF1521G1EW                 | Notebook    | [b46b664a9e](https://linux-hardware.org/?probe=b46b664a9e) | Aug 03, 2023 |
| HP            | 844C                        | Desktop     | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| ASUSTek       | K95VM                       | Notebook    | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [3f09ac4cae](https://linux-hardware.org/?probe=3f09ac4cae) | Jul 29, 2023 |
| MSI           | Raider GE78HX 13VI          | Notebook    | [0b179ca997](https://linux-hardware.org/?probe=0b179ca997) | Jul 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS22905    | Notebook    | [f95fe4ced5](https://linux-hardware.org/?probe=f95fe4ced5) | Jul 28, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8744428bf6](https://linux-hardware.org/?probe=8744428bf6) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | Desktop     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [f440759b5b](https://linux-hardware.org/?probe=f440759b5b) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [2e7199aa1a](https://linux-hardware.org/?probe=2e7199aa1a) | Jul 17, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [9a14a53c9c](https://linux-hardware.org/?probe=9a14a53c9c) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [0c4b8e49f8](https://linux-hardware.org/?probe=0c4b8e49f8) | Jul 15, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [72af2d01c0](https://linux-hardware.org/?probe=72af2d01c0) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a8c3d57d88](https://linux-hardware.org/?probe=a8c3d57d88) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [81a034858f](https://linux-hardware.org/?probe=81a034858f) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a3c2f0155c](https://linux-hardware.org/?probe=a3c2f0155c) | Jun 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | Notebook    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | Notebook    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b27125a1e2](https://linux-hardware.org/?probe=b27125a1e2) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| ASUSTek       | 1225B                       | Notebook    | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | Notebook    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [848d0db1b2](https://linux-hardware.org/?probe=848d0db1b2) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [72ba449391](https://linux-hardware.org/?probe=72ba449391) | May 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a712c6b44a](https://linux-hardware.org/?probe=a712c6b44a) | May 13, 2023 |
| Lenovo        | ThinkPad P50 20EN0037MD     | Notebook    | [f1a58d3a7f](https://linux-hardware.org/?probe=f1a58d3a7f) | May 11, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | Notebook    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Acidanther... | Mac-4B682C642B45593E iMa... | All in one  | [5ff8444666](https://linux-hardware.org/?probe=5ff8444666) | May 04, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [11e8fb1ecd](https://linux-hardware.org/?probe=11e8fb1ecd) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2675aa56c4](https://linux-hardware.org/?probe=2675aa56c4) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | Notebook    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | Notebook    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | Notebook    | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | Notebook    | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| HP            | 339A                        | Desktop     | [1be48a395d](https://linux-hardware.org/?probe=1be48a395d) | Apr 21, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [d31e8d7c7d](https://linux-hardware.org/?probe=d31e8d7c7d) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [245db62c73](https://linux-hardware.org/?probe=245db62c73) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [ad23efbf03](https://linux-hardware.org/?probe=ad23efbf03) | Apr 14, 2023 |
| HP            | 339A                        | Desktop     | [57e1af32cd](https://linux-hardware.org/?probe=57e1af32cd) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | Notebook    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [51b13ad2b6](https://linux-hardware.org/?probe=51b13ad2b6) | Apr 11, 2023 |
| eMachines     | E725                        | Notebook    | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| HP            | 3398                        | Desktop     | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [21cf1ad0bb](https://linux-hardware.org/?probe=21cf1ad0bb) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | Notebook    | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | Notebook    | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3d591cd190](https://linux-hardware.org/?probe=3d591cd190) | Mar 21, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| Acer          | Extensa 7620                | Notebook    | [59bb9967c2](https://linux-hardware.org/?probe=59bb9967c2) | Mar 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [4012d2fb1f](https://linux-hardware.org/?probe=4012d2fb1f) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [f2f8796262](https://linux-hardware.org/?probe=f2f8796262) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | Notebook    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [b3ac863457](https://linux-hardware.org/?probe=b3ac863457) | Mar 15, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| Samsung       | NP770                       | Notebook    | [ab2677e28e](https://linux-hardware.org/?probe=ab2677e28e) | Mar 12, 2023 |
| Acer          | Aspire X1935                | Desktop     | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8995f4a3b0](https://linux-hardware.org/?probe=8995f4a3b0) | Mar 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | Notebook    | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [05e7af9004](https://linux-hardware.org/?probe=05e7af9004) | Mar 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [63863d9f0c](https://linux-hardware.org/?probe=63863d9f0c) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3d8c3db030](https://linux-hardware.org/?probe=3d8c3db030) | Feb 26, 2023 |
| HP            | 3032h                       | Desktop     | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [7380033a44](https://linux-hardware.org/?probe=7380033a44) | Feb 22, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [0dd1f15a92](https://linux-hardware.org/?probe=0dd1f15a92) | Feb 21, 2023 |
| HP            | 1497                        | Desktop     | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [5fd9a2f9c5](https://linux-hardware.org/?probe=5fd9a2f9c5) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| HP            | Notebook                    | Notebook    | [682935bcda](https://linux-hardware.org/?probe=682935bcda) | Feb 16, 2023 |
| HP            | Notebook                    | Notebook    | [1ea98ae976](https://linux-hardware.org/?probe=1ea98ae976) | Feb 16, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aa3655a17e](https://linux-hardware.org/?probe=aa3655a17e) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [b744809cc2](https://linux-hardware.org/?probe=b744809cc2) | Feb 14, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [20c0b96948](https://linux-hardware.org/?probe=20c0b96948) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [dea7831935](https://linux-hardware.org/?probe=dea7831935) | Feb 10, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a55211363f](https://linux-hardware.org/?probe=a55211363f) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| HP            | Notebook                    | Notebook    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e64e08ebd4](https://linux-hardware.org/?probe=e64e08ebd4) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | Notebook    | [5a7e90c12d](https://linux-hardware.org/?probe=5a7e90c12d) | Feb 03, 2023 |
| HP            | 1905                        | Desktop     | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | Notebook    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | Notebook    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | Notebook    | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | Notebook    | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | Notebook    | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| Medion        | P7621                       | Notebook    | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | Notebook    | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | Desktop     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [cc6834a359](https://linux-hardware.org/?probe=cc6834a359) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | Notebook    | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | Notebook    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Acer          | Aspire 5810T                | Notebook    | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | Notebook    | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [e4401c7591](https://linux-hardware.org/?probe=e4401c7591) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [48916ecbfa](https://linux-hardware.org/?probe=48916ecbfa) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | Notebook    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [38763f3628](https://linux-hardware.org/?probe=38763f3628) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | Notebook    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7afd10a1a7](https://linux-hardware.org/?probe=7afd10a1a7) | Nov 09, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [de347eb300](https://linux-hardware.org/?probe=de347eb300) | Nov 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | Notebook    | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | Notebook    | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | Notebook    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [42fb435775](https://linux-hardware.org/?probe=42fb435775) | Oct 18, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | Notebook    | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| HP            | ProBook 6550b               | Notebook    | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | Desktop     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | Desktop     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Acer          | Aspire M3-581TG             | Notebook    | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| Dell          | 0V0D45 A01                  | All in one  | [7d2f0e045d](https://linux-hardware.org/?probe=7d2f0e045d) | Aug 05, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | Desktop     | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| MSI           | MS-AF151 100                | All in one  | [cd5a32135a](https://linux-hardware.org/?probe=cd5a32135a) | Jul 07, 2022 |
| MSI           | MS-AF151 100                | All in one  | [55deb5fb81](https://linux-hardware.org/?probe=55deb5fb81) | Jul 07, 2022 |
| Medion        | Iron238KR                   | All in one  | [ff6bf1bc47](https://linux-hardware.org/?probe=ff6bf1bc47) | Jul 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| HP            | 805D                        | Desktop     | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | Notebook    | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| Notebook      | PB50_70DFx,DDx              | Notebook    | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | Notebook    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | Notebook    | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | Notebook    | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Dell          | 09CGW2 A11                  | Server      | [27b873f279](https://linux-hardware.org/?probe=27b873f279) | May 27, 2022 |
| HP            | ProBook 6450b               | Notebook    | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | Notebook    | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | Notebook    | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [60a16a0a17](https://linux-hardware.org/?probe=60a16a0a17) | May 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | Desktop     | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [49df794b0b](https://linux-hardware.org/?probe=49df794b0b) | May 20, 2022 |
| SLIMBOOK      | PROX14-10                   | Notebook    | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | Notebook    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| Dell          | Precision 5750              | Notebook    | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| MSI           | MS-1T11                     | Desktop     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | Desktop     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | Notebook    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e48e9d93d](https://linux-hardware.org/?probe=5e48e9d93d) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [67b9d43387](https://linux-hardware.org/?probe=67b9d43387) | Apr 03, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | Notebook    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | Desktop     | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | Notebook    | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Shuttle       | X50V2PLUS V1.00             | Desktop     | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | Notebook    | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | Notebook    | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | Notebook    | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | Notebook    | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | Desktop     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Medion        | P7612                       | Notebook    | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | Notebook    | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| Medion        | P7612                       | Notebook    | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | Notebook    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| Acer          | Predator G6-710             | Desktop     | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | Notebook    | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | Notebook    | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | Notebook    | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [39affa759d](https://linux-hardware.org/?probe=39affa759d) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c38d256cab](https://linux-hardware.org/?probe=c38d256cab) | Dec 29, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | Desktop     | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | Notebook    | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| HP            | 3031h                       | Desktop     | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | Desktop     | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | Notebook    | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [99c299c85b](https://linux-hardware.org/?probe=99c299c85b) | Dec 11, 2021 |
| Toshiba       | Satellite P850              | Notebook    | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [22f7fc3dbe](https://linux-hardware.org/?probe=22f7fc3dbe) | Dec 04, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [26541caf1e](https://linux-hardware.org/?probe=26541caf1e) | Dec 03, 2021 |
| HP            | 3031h                       | Desktop     | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | Desktop     | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| DukaPC        | Notebook                    | Notebook    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| HP            | 8299                        | Desktop     | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | Desktop     | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [0574fefb71](https://linux-hardware.org/?probe=0574fefb71) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Razer         | Blade Stealth               | Notebook    | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Acer          | Aspire X3995                | Desktop     | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | Desktop     | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | Notebook    | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [10262b5305](https://linux-hardware.org/?probe=10262b5305) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2d7b8c665b](https://linux-hardware.org/?probe=2d7b8c665b) | Nov 09, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [47d8931073](https://linux-hardware.org/?probe=47d8931073) | Nov 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | Notebook    | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| HP            | 1589                        | Desktop     | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | Desktop     | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [8add857c1a](https://linux-hardware.org/?probe=8add857c1a) | Oct 15, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | Notebook    | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | Notebook    | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Microsoft     | Surface Book 3              | Tablet      | [5fdb7aebb9](https://linux-hardware.org/?probe=5fdb7aebb9) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | Notebook    | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | Notebook    | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| HP            | ZBook 15                    | Notebook    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | Notebook    | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | Notebook    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d7c3904aa](https://linux-hardware.org/?probe=5d7c3904aa) | Sep 09, 2021 |
| ASRock        | P55M Pro                    | Desktop     | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | Notebook    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | Notebook    | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | Notebook    | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Medion        | MS-7616                     | Desktop     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| HP            | 212B                        | Desktop     | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 152       | 12.29%  |
| Ubuntu 18.04                 | 84        | 6.79%   |
| Ubuntu 22.04                 | 75        | 6.06%   |
| Arch Rolling                 | 42        | 3.4%    |
| Pop!_OS 22.04                | 33        | 2.67%   |
| Ubuntu 21.10                 | 25        | 2.02%   |
| OpenMandriva 4.2             | 25        | 2.02%   |
| Zorin 16                     | 24        | 1.94%   |
| Fedora 38                    | 24        | 1.94%   |
| Debian 11                    | 24        | 1.94%   |
| Manjaro                      | 20        | 1.62%   |
| Debian 12                    | 18        | 1.46%   |
| Linux Mint 21.2              | 17        | 1.37%   |
| Fedora 34                    | 16        | 1.29%   |
| Ubuntu 20.10                 | 15        | 1.21%   |
| Linux Mint 21.1              | 15        | 1.21%   |
| Fedora 39                    | 15        | 1.21%   |
| Ubuntu 19.04                 | 14        | 1.13%   |
| Pop!_OS 21.04                | 14        | 1.13%   |
| OpenMandriva 23.03           | 14        | 1.13%   |
| Linux Mint 20.2              | 14        | 1.13%   |
| ArcoLinux Rolling            | 14        | 1.13%   |
| OpenMandriva 4.3             | 13        | 1.05%   |
| Linux Mint 20.3              | 13        | 1.05%   |
| Linux Mint 20.1              | 13        | 1.05%   |
| Arch                         | 13        | 1.05%   |
| Ubuntu 22.10                 | 12        | 0.97%   |
| Fedora 36                    | 12        | 0.97%   |
| Fedora 32                    | 12        | 0.97%   |
| Zorin 15                     | 11        | 0.89%   |
| KDE neon 20.04               | 11        | 0.89%   |
| Ubuntu 19.10                 | 10        | 0.81%   |
| Pop!_OS 20.04                | 10        | 0.81%   |
| Debian 10                    | 10        | 0.81%   |
| Pop!_OS 21.10                | 9         | 0.73%   |
| Pop!_OS 20.10                | 9         | 0.73%   |
| Fedora 37                    | 9         | 0.73%   |
| Ubuntu 23.10                 | 8         | 0.65%   |
| Ubuntu 23.04                 | 8         | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 397       | 34.19%  |
| Fedora        | 107       | 9.22%   |
| Linux Mint    | 102       | 8.79%   |
| Pop!_OS       | 74        | 6.37%   |
| OpenMandriva  | 66        | 5.68%   |
| Debian        | 58        | 5%      |
| Arch          | 53        | 4.57%   |
| Manjaro       | 45        | 3.88%   |
| Zorin         | 43        | 3.7%    |
| Kubuntu       | 26        | 2.24%   |
| KDE neon      | 20        | 1.72%   |
| ArcoLinux     | 17        | 1.46%   |
| Xubuntu       | 14        | 1.21%   |
| Ubuntu MATE   | 9         | 0.78%   |
| ROSA          | 9         | 0.78%   |
| openSUSE      | 9         | 0.78%   |
| EndeavourOS   | 9         | 0.78%   |
| Elementary    | 9         | 0.78%   |
| SteamOS       | 8         | 0.69%   |
| Kali          | 7         | 0.6%    |
| Ubuntu Unity  | 6         | 0.52%   |
| Gentoo        | 6         | 0.52%   |
| Garuda Linux  | 6         | 0.52%   |
| Void Linux    | 5         | 0.43%   |
| Parrot        | 5         | 0.43%   |
| Nobara        | 5         | 0.43%   |
| MX            | 4         | 0.34%   |
| Lubuntu       | 4         | 0.34%   |
| Endless       | 4         | 0.34%   |
| Clear Linux   | 4         | 0.34%   |
| Xero          | 3         | 0.26%   |
| Raspbian      | 3         | 0.26%   |
| NixOS         | 3         | 0.26%   |
| LMDE          | 3         | 0.26%   |
| BlackPanther  | 3         | 0.26%   |
| TUXEDO OS     | 2         | 0.17%   |
| antiX         | 2         | 0.17%   |
| Ubuntu Kylin  | 1         | 0.09%   |
| Ubuntu Budgie | 1         | 0.09%   |
| Solus         | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 1.7%    |
| 5.4.0-42-generic         | 19        | 1.4%    |
| 6.2.6-desktop-1omv2390   | 14        | 1.03%   |
| 5.16.7-desktop-1omv4003  | 13        | 0.96%   |
| 5.4.0-52-generic         | 12        | 0.89%   |
| 5.15.0-56-generic        | 12        | 0.89%   |
| 5.4.0-26-generic         | 10        | 0.74%   |
| 6.2.6-76060206-generic   | 8         | 0.59%   |
| 5.4.0-58-generic         | 8         | 0.59%   |
| 5.4.0-48-generic         | 8         | 0.59%   |
| 5.3.0-28-generic         | 8         | 0.59%   |
| 5.19.0-35-generic        | 8         | 0.59%   |
| 5.15.0-58-generic        | 8         | 0.59%   |
| 6.1.0-18-amd64           | 7         | 0.52%   |
| 5.8.0-43-generic         | 7         | 0.52%   |
| 5.4.0-29-generic         | 7         | 0.52%   |
| 5.19.0-38-generic        | 7         | 0.52%   |
| 5.15.0-46-generic        | 7         | 0.52%   |
| 5.15.0-43-generic        | 7         | 0.52%   |
| 5.11.0-41-generic        | 7         | 0.52%   |
| 5.11.0-27-generic        | 7         | 0.52%   |
| 6.4.11-desktop-1omv2390  | 6         | 0.44%   |
| 5.4.0-91-generic         | 6         | 0.44%   |
| 5.4.0-7634-generic       | 6         | 0.44%   |
| 5.3.0-40-generic         | 6         | 0.44%   |
| 5.19.0-76051900-generic  | 6         | 0.44%   |
| 5.15.0-88-generic        | 6         | 0.44%   |
| 5.15.0-53-generic        | 6         | 0.44%   |
| 5.13.0-39-generic        | 6         | 0.44%   |
| 5.11.0-7620-generic      | 6         | 0.44%   |
| 5.11.0-40-generic        | 6         | 0.44%   |
| 4.15.0-45-generic        | 6         | 0.44%   |
| 6.5.0-26-generic         | 5         | 0.37%   |
| 6.5.0-14-generic         | 5         | 0.37%   |
| 6.4.6-76060406-generic   | 5         | 0.37%   |
| 6.2.0-26-generic         | 5         | 0.37%   |
| 5.8.0-41-generic         | 5         | 0.37%   |
| 5.4.0-47-generic         | 5         | 0.37%   |
| 5.15.0-52-generic        | 5         | 0.37%   |
| 5.13.12-200.fc34.x86_64  | 5         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 158       | 12.37%  |
| 5.15.0  | 106       | 8.3%    |
| 4.15.0  | 67        | 5.25%   |
| 5.13.0  | 60        | 4.7%    |
| 5.11.0  | 59        | 4.62%   |
| 5.8.0   | 56        | 4.39%   |
| 5.19.0  | 47        | 3.68%   |
| 6.5.0   | 40        | 3.13%   |
| 5.3.0   | 37        | 2.9%    |
| 6.2.0   | 29        | 2.27%   |
| 5.0.0   | 27        | 2.11%   |
| 6.2.6   | 26        | 2.04%   |
| 5.10.0  | 24        | 1.88%   |
| 5.10.14 | 23        | 1.8%    |
| 6.1.0   | 22        | 1.72%   |
| 4.18.0  | 18        | 1.41%   |
| 5.16.7  | 13        | 1.02%   |
| 4.19.0  | 11        | 0.86%   |
| 6.5.5   | 6         | 0.47%   |
| 6.4.6   | 6         | 0.47%   |
| 6.4.11  | 6         | 0.47%   |
| 6.1.1   | 6         | 0.47%   |
| 6.6.2   | 5         | 0.39%   |
| 6.3.8   | 5         | 0.39%   |
| 5.4.18  | 5         | 0.39%   |
| 5.16.0  | 5         | 0.39%   |
| 5.13.12 | 5         | 0.39%   |
| 6.8.7   | 4         | 0.31%   |
| 6.6.8   | 4         | 0.31%   |
| 6.6.7   | 4         | 0.31%   |
| 6.6.10  | 4         | 0.31%   |
| 6.5.9   | 4         | 0.31%   |
| 6.5.6   | 4         | 0.31%   |
| 6.5.3   | 4         | 0.31%   |
| 6.4.8   | 4         | 0.31%   |
| 6.3.9   | 4         | 0.31%   |
| 6.1.7   | 4         | 0.31%   |
| 6.0.6   | 4         | 0.31%   |
| 6.0.0   | 4         | 0.31%   |
| 5.9.0   | 4         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 174       | 13.84%  |
| 5.15    | 137       | 10.9%   |
| 5.8     | 76        | 6.05%   |
| 5.11    | 72        | 5.73%   |
| 5.13    | 70        | 5.57%   |
| 4.15    | 67        | 5.33%   |
| 6.5     | 64        | 5.09%   |
| 6.2     | 63        | 5.01%   |
| 5.19    | 62        | 4.93%   |
| 5.10    | 59        | 4.69%   |
| 6.1     | 53        | 4.22%   |
| 5.3     | 37        | 2.94%   |
| 5.16    | 34        | 2.7%    |
| 5.0     | 28        | 2.23%   |
| 6.6     | 27        | 2.15%   |
| 6.4     | 23        | 1.83%   |
| 6.0     | 20        | 1.59%   |
| 4.18    | 20        | 1.59%   |
| 6.3     | 18        | 1.43%   |
| 5.6     | 17        | 1.35%   |
| 5.14    | 17        | 1.35%   |
| 6.7     | 15        | 1.19%   |
| 5.17    | 13        | 1.03%   |
| 4.19    | 13        | 1.03%   |
| 5.9     | 12        | 0.95%   |
| 5.7     | 12        | 0.95%   |
| 6.8     | 10        | 0.8%    |
| 5.18    | 9         | 0.72%   |
| 5.12    | 9         | 0.72%   |
| 5.1     | 6         | 0.48%   |
| 4.9     | 6         | 0.48%   |
| 4.4     | 3         | 0.24%   |
| 6.9     | 2         | 0.16%   |
| 5.2     | 2         | 0.16%   |
| 4.14    | 2         | 0.16%   |
| 4.17    | 1         | 0.08%   |
| 4.16    | 1         | 0.08%   |
| 4.13    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1079      | 96.51%  |
| i686    | 24        | 2.15%   |
| aarch64 | 12        | 1.07%   |
| armv7l  | 3         | 0.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 551       | 46.97%  |
| KDE5            | 195       | 16.62%  |
| Unknown         | 151       | 12.87%  |
| X-Cinnamon      | 80        | 6.82%   |
| XFCE            | 76        | 6.48%   |
| MATE            | 26        | 2.22%   |
| KDE             | 23        | 1.96%   |
| i3              | 9         | 0.77%   |
| Pantheon        | 8         | 0.68%   |
| LXQt            | 8         | 0.68%   |
| Cinnamon        | 8         | 0.68%   |
| Unity           | 6         | 0.51%   |
| KDE6            | 6         | 0.51%   |
| sway            | 3         | 0.26%   |
| GNOME Flashback | 3         | 0.26%   |
| LXDE            | 2         | 0.17%   |
| KDE4            | 2         | 0.17%   |
| icewm           | 2         | 0.17%   |
| Deepin          | 2         | 0.17%   |
| UKUI            | 1         | 0.09%   |
| ubuntu          | 1         | 0.09%   |
| qtile-default   | 1         | 0.09%   |
| openbox         | 1         | 0.09%   |
| LeftWM          | 1         | 0.09%   |
| Hyprland        | 1         | 0.09%   |
| fluxbox         | 1         | 0.09%   |
| enlightenment   | 1         | 0.09%   |
| Endless:GNOME   | 1         | 0.09%   |
| Budgie          | 1         | 0.09%   |
| bspwm           | 1         | 0.09%   |
| awesome         | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 816       | 69.98%  |
| Wayland | 252       | 21.61%  |
| Unknown | 70        | 6%      |
| Tty     | 28        | 2.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 607       | 52.46%  |
| SDDM    | 157       | 13.57%  |
| GDM3    | 156       | 13.48%  |
| GDM     | 117       | 10.11%  |
| LightDM | 80        | 6.91%   |
| TDM     | 29        | 2.51%   |
| SLiM    | 2         | 0.17%   |
| KDM     | 2         | 0.17%   |
| GREETD  | 2         | 0.17%   |
| XDM     | 1         | 0.09%   |
| SLIMSKI | 1         | 0.09%   |
| LY-DM   | 1         | 0.09%   |
| Ly      | 1         | 0.09%   |
| LXDM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 413       | 35.76%  |
| da_DK      | 356       | 30.82%  |
| en_DK      | 145       | 12.55%  |
| Unknown    | 113       | 9.78%   |
| en_GB      | 63        | 5.45%   |
| C          | 20        | 1.73%   |
| de_DE      | 16        | 1.39%   |
| pl_PL      | 5         | 0.43%   |
| it_IT      | 3         | 0.26%   |
| sv_SE      | 2         | 0.17%   |
| ru_RU      | 2         | 0.17%   |
| es_ES      | 2         | 0.17%   |
| en_AG      | 2         | 0.17%   |
| de_CH      | 2         | 0.17%   |
| zh_TW      | 1         | 0.09%   |
| pt_BR      | 1         | 0.09%   |
| nl_NL      | 1         | 0.09%   |
| is_IS      | 1         | 0.09%   |
| io_001     | 1         | 0.09%   |
| fr_FR      | 1         | 0.09%   |
| en_US.UTF8 | 1         | 0.09%   |
| en_IE      | 1         | 0.09%   |
| en_CA      | 1         | 0.09%   |
| en_AU      | 1         | 0.09%   |
| de_AT      | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 572       | 50.18%  |
| EFI  | 568       | 49.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 841       | 72.56%  |
| Btrfs   | 153       | 13.2%   |
| Overlay | 62        | 5.35%   |
| Tmpfs   | 44        | 3.8%    |
| Unknown | 37        | 3.19%   |
| Zfs     | 13        | 1.12%   |
| Xfs     | 5         | 0.43%   |
| Ext2    | 3         | 0.26%   |
| F2fs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 628       | 54.47%  |
| GPT     | 430       | 37.29%  |
| MBR     | 95        | 8.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 978       | 85.71%  |
| Yes       | 163       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 870       | 76.52%  |
| Yes       | 267       | 23.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 294       | 26.32%  |
| ASUSTek Computer        | 201       | 17.99%  |
| Hewlett-Packard         | 136       | 12.18%  |
| Dell                    | 77        | 6.89%   |
| Acer                    | 57        | 5.1%    |
| Gigabyte Technology     | 52        | 4.66%   |
| MSI                     | 51        | 4.57%   |
| Apple                   | 41        | 3.67%   |
| ASRock                  | 38        | 3.4%    |
| Medion                  | 17        | 1.52%   |
| Intel                   | 15        | 1.34%   |
| Toshiba                 | 12        | 1.07%   |
| Raspberry Pi Foundation | 12        | 1.07%   |
| Notebook                | 10        | 0.9%    |
| HUAWEI                  | 6         | 0.54%   |
| Google                  | 6         | 0.54%   |
| AMI                     | 6         | 0.54%   |
| Valve                   | 5         | 0.45%   |
| Samsung Electronics     | 5         | 0.45%   |
| Fujitsu                 | 5         | 0.45%   |
| Unknown                 | 5         | 0.45%   |
| Shuttle                 | 4         | 0.36%   |
| Razer                   | 4         | 0.36%   |
| Pegatron                | 4         | 0.36%   |
| Packard Bell            | 4         | 0.36%   |
| Microsoft               | 4         | 0.36%   |
| TUXEDO                  | 3         | 0.27%   |
| eMachines               | 3         | 0.27%   |
| Timi                    | 2         | 0.18%   |
| Supermicro              | 2         | 0.18%   |
| Sony                    | 2         | 0.18%   |
| Quanta                  | 2         | 0.18%   |
| GPD                     | 2         | 0.18%   |
| Fujitsu Siemens         | 2         | 0.18%   |
| BESSTAR Tech            | 2         | 0.18%   |
| Alienware               | 2         | 0.18%   |
| Tactus                  | 1         | 0.09%   |
| T-bao                   | 1         | 0.09%   |
| System76                | 1         | 0.09%   |
| Standard                | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 12        | 1.07%   |
| ASUS All Series                         | 6         | 0.54%   |
| Valve Jupiter                           | 5         | 0.45%   |
| RPi Raspberry Pi                        | 5         | 0.45%   |
| HP Pavilion dv7                         | 5         | 0.45%   |
| ASUS ROG STRIX B450-E GAMING            | 5         | 0.45%   |
| RPi Raspberry Pi 4 Model B Rev 1.1      | 4         | 0.36%   |
| MSI MS-7C37                             | 4         | 0.36%   |
| Dell XPS 15 9570                        | 4         | 0.36%   |
| Dell XPS 13 9370                        | 4         | 0.36%   |
| ASUS Z170 PRO GAMING                    | 4         | 0.36%   |
| ASUS TUF Gaming X570-PLUS               | 4         | 0.36%   |
| ASUS ROG STRIX B550-F GAMING            | 4         | 0.36%   |
| MSI MS-7C02                             | 3         | 0.27%   |
| Lenovo ThinkPad T530 24295L4            | 3         | 0.27%   |
| HP Pavilion g7                          | 3         | 0.27%   |
| HP OMEN by Laptop                       | 3         | 0.27%   |
| HP Notebook                             | 3         | 0.27%   |
| HP EliteBook 820 G3                     | 3         | 0.27%   |
| Gigabyte X570 AORUS MASTER              | 3         | 0.27%   |
| Dell XPS 15 9560                        | 3         | 0.27%   |
| Dell OptiPlex 9020                      | 3         | 0.27%   |
| Dell Latitude E7440                     | 3         | 0.27%   |
| Dell Latitude 7480                      | 3         | 0.27%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK   | 3         | 0.27%   |
| ASUS ROG STRIX X570-E GAMING            | 3         | 0.27%   |
| ASUS PRIME Z390-A                       | 3         | 0.27%   |
| ASUS PRIME X570-P                       | 3         | 0.27%   |
| Apple MacBookPro9,2                     | 3         | 0.27%   |
| Apple MacBookPro5,5                     | 3         | 0.27%   |
| Apple iMac12,1                          | 3         | 0.27%   |
| Toshiba Satellite P850                  | 2         | 0.18%   |
| Toshiba Satellite L40                   | 2         | 0.18%   |
| Razer Blade Stealth                     | 2         | 0.18%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3 | 2         | 0.18%   |
| Quanta MW1/HW1                          | 2         | 0.18%   |
| Notebook W54_55SU1,SUW                  | 2         | 0.18%   |
| MSI MS-7B79                             | 2         | 0.18%   |
| MSI MS-7A34                             | 2         | 0.18%   |
| MSI MS-7693                             | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 178       | 15.94%  |
| ASUS ROG            | 43        | 3.85%   |
| Acer Aspire         | 40        | 3.58%   |
| ASUS PRIME          | 31        | 2.78%   |
| HP Pavilion         | 29        | 2.6%    |
| Dell Latitude       | 25        | 2.24%   |
| Lenovo IdeaPad      | 24        | 2.15%   |
| HP EliteBook        | 24        | 2.15%   |
| ASUS TUF            | 18        | 1.61%   |
| Lenovo ThinkCentre  | 17        | 1.52%   |
| HP Compaq           | 17        | 1.52%   |
| Dell XPS            | 17        | 1.52%   |
| Lenovo Yoga         | 16        | 1.43%   |
| Toshiba Satellite   | 12        | 1.07%   |
| RPi Raspberry       | 12        | 1.07%   |
| HP ProBook          | 12        | 1.07%   |
| Unknown             | 12        | 1.07%   |
| HP Laptop           | 10        | 0.9%    |
| Dell Inspiron       | 10        | 0.9%    |
| ASUS ZenBook        | 10        | 0.9%    |
| Dell OptiPlex       | 9         | 0.81%   |
| Lenovo Legion       | 8         | 0.72%   |
| Gigabyte X570       | 8         | 0.72%   |
| Lenovo ThinkStation | 7         | 0.63%   |
| HP OMEN             | 7         | 0.63%   |
| Dell Precision      | 7         | 0.63%   |
| ASUS VivoBook       | 7         | 0.63%   |
| ASUS All            | 6         | 0.54%   |
| Valve Jupiter       | 5         | 0.45%   |
| Lenovo ThinkBook    | 5         | 0.45%   |
| Lenovo IdeaCentre   | 5         | 0.45%   |
| HP ENVY             | 5         | 0.45%   |
| Apple MacBookPro11  | 5         | 0.45%   |
| Acer Swift          | 5         | 0.45%   |
| Razer Blade         | 4         | 0.36%   |
| MSI MS-7C37         | 4         | 0.36%   |
| Microsoft Surface   | 4         | 0.36%   |
| HP Spectre          | 4         | 0.36%   |
| HP ProLiant         | 4         | 0.36%   |
| HP EliteDesk        | 4         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 105       | 9.4%    |
| 2020    | 100       | 8.95%   |
| 2019    | 95        | 8.5%    |
| 2017    | 88        | 7.88%   |
| 2021    | 85        | 7.61%   |
| 2013    | 83        | 7.43%   |
| 2015    | 73        | 6.54%   |
| 2012    | 71        | 6.36%   |
| 2011    | 71        | 6.36%   |
| 2016    | 69        | 6.18%   |
| 2014    | 52        | 4.66%   |
| 2022    | 46        | 4.12%   |
| 2010    | 42        | 3.76%   |
| 2009    | 37        | 3.31%   |
| 2008    | 33        | 2.95%   |
| 2007    | 27        | 2.42%   |
| 2023    | 19        | 1.7%    |
| Unknown | 13        | 1.16%   |
| 2006    | 7         | 0.63%   |
| 2003    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 629       | 56.31%  |
| Desktop        | 388       | 34.74%  |
| Convertible    | 29        | 2.6%    |
| Mini pc        | 24        | 2.15%   |
| All in one     | 20        | 1.79%   |
| System on chip | 13        | 1.16%   |
| Tablet         | 8         | 0.72%   |
| Server         | 4         | 0.36%   |
| Phone          | 2         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1029      | 91.55%  |
| Enabled  | 95        | 8.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1110      | 99.37%  |
| Yes  | 7         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 259       | 22.74%  |
| 16.01-24.0      | 251       | 22.04%  |
| 8.01-16.0       | 202       | 17.73%  |
| 3.01-4.0        | 152       | 13.35%  |
| 32.01-64.0      | 148       | 12.99%  |
| 64.01-256.0     | 45        | 3.95%   |
| 24.01-32.0      | 35        | 3.07%   |
| 1.01-2.0        | 23        | 2.02%   |
| 2.01-3.0        | 15        | 1.32%   |
| 0.51-1.0        | 6         | 0.53%   |
| More than 256.0 | 2         | 0.18%   |
| 0.01-0.5        | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 375       | 30.22%  |
| 2.01-3.0    | 325       | 26.19%  |
| 4.01-8.0    | 236       | 19.02%  |
| 3.01-4.0    | 176       | 14.18%  |
| 8.01-16.0   | 50        | 4.03%   |
| 0.51-1.0    | 46        | 3.71%   |
| 0.01-0.5    | 16        | 1.29%   |
| 24.01-32.0  | 7         | 0.56%   |
| 16.01-24.0  | 6         | 0.48%   |
| 32.01-64.0  | 3         | 0.24%   |
| 64.01-256.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 722       | 62.78%  |
| 2      | 241       | 20.96%  |
| 3      | 94        | 8.17%   |
| 4      | 42        | 3.65%   |
| 5      | 24        | 2.09%   |
| 0      | 11        | 0.96%   |
| 6      | 9         | 0.78%   |
| 8      | 3         | 0.26%   |
| 7      | 3         | 0.26%   |
| 9      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 757       | 67.17%  |
| Yes       | 370       | 32.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 974       | 86.73%  |
| No        | 149       | 13.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 894       | 79.54%  |
| No        | 230       | 20.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 750       | 66.25%  |
| No        | 382       | 33.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Denmark | 1117      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Copenhagen               | 262       | 22.11%  |
| Frederiksberg            | 73        | 6.16%   |
| Odense                   | 65        | 5.49%   |
| Aarhus                   | 37        | 3.12%   |
| Bronshoj                 | 27        | 2.28%   |
| Silkeborg                | 24        | 2.03%   |
| Horsens                  | 24        | 2.03%   |
| Aalborg                  | 24        | 2.03%   |
| Slagelse                 | 23        | 1.94%   |
| Valby                    | 21        | 1.77%   |
| Esbjerg                  | 19        | 1.6%    |
| Glostrup Municipality    | 15        | 1.27%   |
| Aabenraa                 | 15        | 1.27%   |
| Kongens Lyngby           | 14        | 1.18%   |
| Holstebro                | 13        | 1.1%    |
| Taastrup                 | 12        | 1.01%   |
| Roskilde                 | 12        | 1.01%   |
| Norresundby              | 11        | 0.93%   |
| Risskov                  | 10        | 0.84%   |
| Nyborg                   | 10        | 0.84%   |
| Hvidovre                 | 10        | 0.84%   |
| Gentofte Municipality    | 10        | 0.84%   |
| Skanderborg              | 9         | 0.76%   |
| Kolding                  | 9         | 0.76%   |
| Herlev                   | 9         | 0.76%   |
| Vejle                    | 8         | 0.68%   |
| Kastrup                  | 8         | 0.68%   |
| Viby J                   | 7         | 0.59%   |
| Tilst                    | 7         | 0.59%   |
| Naestved                 | 7         | 0.59%   |
| Køge                    | 7         | 0.59%   |
| Hjørring                | 7         | 0.59%   |
| Fredericia               | 7         | 0.59%   |
| Viborg                   | 6         | 0.51%   |
| Vanlose                  | 6         | 0.51%   |
| Vaerlose                 | 6         | 0.51%   |
| Svendborg                | 6         | 0.51%   |
| Elsinore                 | 6         | 0.51%   |
| Brønderslev             | 6         | 0.51%   |
| Albertslund Municipality | 6         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 381       | 584    | 23.69%  |
| WDC                         | 186       | 274    | 11.57%  |
| Seagate                     | 183       | 258    | 11.38%  |
| Kingston                    | 135       | 199    | 8.4%    |
| Toshiba                     | 85        | 114    | 5.29%   |
| Sandisk                     | 72        | 94     | 4.48%   |
| Unknown                     | 61        | 72     | 3.79%   |
| SK hynix                    | 55        | 71     | 3.42%   |
| Intel                       | 54        | 66     | 3.36%   |
| Crucial                     | 43        | 53     | 2.67%   |
| Hitachi                     | 42        | 57     | 2.61%   |
| Micron Technology           | 33        | 39     | 2.05%   |
| HGST                        | 24        | 33     | 1.49%   |
| Intenso                     | 22        | 27     | 1.37%   |
| Apple                       | 18        | 27     | 1.12%   |
| LITEON                      | 16        | 32     | 1%      |
| PNY                         | 15        | 18     | 0.93%   |
| A-DATA Technology           | 15        | 16     | 0.93%   |
| Phison Electronics          | 12        | 20     | 0.75%   |
| Corsair                     | 11        | 14     | 0.68%   |
| OCZ                         | 10        | 10     | 0.62%   |
| Phison                      | 9         | 13     | 0.56%   |
| Kingston Technology Company | 9         | 9      | 0.56%   |
| KIOXIA                      | 7         | 8      | 0.44%   |
| Verbatim                    | 6         | 11     | 0.37%   |
| Micron/Crucial Technology   | 6         | 6      | 0.37%   |
| LITEONIT                    | 6         | 7      | 0.37%   |
| Lenovo                      | 5         | 6      | 0.31%   |
| Fujitsu                     | 5         | 10     | 0.31%   |
| China                       | 5         | 6      | 0.31%   |
| JMicron Technology          | 4         | 4      | 0.25%   |
| XPG                         | 3         | 3      | 0.19%   |
| USB3.0                      | 3         | 3      | 0.19%   |
| Transcend                   | 3         | 3      | 0.19%   |
| Team                        | 3         | 3      | 0.19%   |
| Silicon Motion              | 3         | 3      | 0.19%   |
| Patriot                     | 3         | 4      | 0.19%   |
| Hewlett-Packard             | 3         | 6      | 0.19%   |
| Unknown                     | 3         | 5      | 0.19%   |
| Union Memory                | 2         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 28        | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 24        | 1.34%   |
| Kingston SA400S37480G 480GB SSD                    | 24        | 1.34%   |
| Samsung SSD 850 EVO 250GB                          | 20        | 1.12%   |
| Samsung SSD 850 EVO 500GB                          | 18        | 1.01%   |
| Kingston SA400S37240G 240GB SSD                    | 16        | 0.9%    |
| Kingston SV300S37A120G 120GB SSD                   | 14        | 0.78%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 13        | 0.73%   |
| Unknown MMC Card  32GB                             | 12        | 0.67%   |
| Samsung SSD 860 EVO 500GB                          | 12        | 0.67%   |
| Samsung SSD 860 QVO 1TB                            | 11        | 0.62%   |
| Samsung SSD 860 EVO 1TB                            | 11        | 0.62%   |
| Samsung SSD 840 EVO 250GB                          | 11        | 0.62%   |
| Unknown MMC Card  64GB                             | 10        | 0.56%   |
| Samsung NVMe SSD Drive 512GB                       | 10        | 0.56%   |
| Samsung NVMe SSD Drive 500GB                       | 10        | 0.56%   |
| Samsung NVMe SSD Drive 1TB                         | 10        | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB                     | 9         | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 9         | 0.5%    |
| Kingston SA400S37120G 120GB SSD                    | 9         | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                    | 8         | 0.45%   |
| Kingston SV300S37A240G 240GB SSD                   | 8         | 0.45%   |
| HGST HTS721010A9E630 1TB                           | 8         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB                       | 7         | 0.39%   |
| SK hynix NVMe SSD Drive 512GB                      | 7         | 0.39%   |
| PNY CS900 120GB SSD                                | 7         | 0.39%   |
| Kingston SUV400S37120G 120GB SSD                   | 7         | 0.39%   |
| Toshiba NVMe SSD Drive 512GB                       | 6         | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB                     | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                       | 6         | 0.34%   |
| Phison E12 NVMe Controller 2TB                     | 6         | 0.34%   |
| Kingston SUV400S37240G 240GB SSD                   | 6         | 0.34%   |
| Kingston SKC3000D2048G 2TB                         | 6         | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                        | 6         | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 5         | 0.28%   |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 5         | 0.28%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 0.28%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 5         | 0.28%   |
| Seagate ST2000LM015-2E8174 2TB                     | 5         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 177       | 249    | 38.15%  |
| WDC                 | 134       | 212    | 28.88%  |
| Toshiba             | 44        | 55     | 9.48%   |
| Hitachi             | 42        | 57     | 9.05%   |
| HGST                | 24        | 33     | 5.17%   |
| Samsung Electronics | 16        | 24     | 3.45%   |
| Fujitsu             | 5         | 10     | 1.08%   |
| Unknown             | 4         | 5      | 0.86%   |
| JMicron Technology  | 4         | 4      | 0.86%   |
| Apple               | 4         | 8      | 0.86%   |
| Maxtor              | 2         | 2      | 0.43%   |
| Hewlett-Packard     | 2         | 5      | 0.43%   |
| Unknown             | 2         | 4      | 0.43%   |
| Unknown (CF)        | 1         | 1      | 0.22%   |
| Intenso             | 1         | 2      | 0.22%   |
| ASMT109x            | 1         | 1      | 0.22%   |
| Apricorn            | 1         | 2      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 202       | 297    | 33.28%  |
| Kingston            | 109       | 152    | 17.96%  |
| Crucial             | 36        | 46     | 5.93%   |
| SanDisk             | 32        | 37     | 5.27%   |
| Intel               | 23        | 30     | 3.79%   |
| WDC                 | 22        | 26     | 3.62%   |
| Intenso             | 17        | 19     | 2.8%    |
| PNY                 | 15        | 18     | 2.47%   |
| Micron Technology   | 15        | 17     | 2.47%   |
| LITEON              | 15        | 31     | 2.47%   |
| Toshiba             | 14        | 16     | 2.31%   |
| SK hynix            | 12        | 14     | 1.98%   |
| Apple               | 12        | 13     | 1.98%   |
| A-DATA Technology   | 12        | 12     | 1.98%   |
| OCZ                 | 10        | 10     | 1.65%   |
| Verbatim            | 6         | 11     | 0.99%   |
| LITEONIT            | 6         | 7      | 0.99%   |
| Corsair             | 6         | 7      | 0.99%   |
| China               | 5         | 6      | 0.82%   |
| USB3.0              | 3         | 3      | 0.49%   |
| Team                | 3         | 3      | 0.49%   |
| Patriot             | 3         | 4      | 0.49%   |
| Transcend           | 2         | 2      | 0.33%   |
| Leven               | 2         | 2      | 0.33%   |
| GOODRAM             | 2         | 6      | 0.33%   |
| AFOX                | 2         | 2      | 0.33%   |
| Vaseky              | 1         | 1      | 0.16%   |
| USB                 | 1         | 1      | 0.16%   |
| Teclast             | 1         | 1      | 0.16%   |
| Supersonic          | 1         | 1      | 0.16%   |
| SPCC                | 1         | 1      | 0.16%   |
| Shark               | 1         | 1      | 0.16%   |
| Ramaxel Technology  | 1         | 1      | 0.16%   |
| Plextor             | 1         | 1      | 0.16%   |
| OCZ-VERTEX3         | 1         | 3      | 0.16%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.16%   |
| KingFast            | 1         | 1      | 0.16%   |
| KingDian            | 1         | 1      | 0.16%   |
| Kingchuxing         | 1         | 1      | 0.16%   |
| KING                | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 534       | 815    | 36.98%  |
| NVMe    | 448       | 674    | 31.02%  |
| HDD     | 385       | 674    | 26.66%  |
| MMC     | 57        | 63     | 3.95%   |
| Unknown | 20        | 22     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 759       | 1426   | 57.2%   |
| NVMe | 447       | 673    | 33.69%  |
| SAS  | 64        | 86     | 4.82%   |
| MMC  | 57        | 63     | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 588       | 920    | 60.43%  |
| 0.51-1.0   | 222       | 306    | 22.82%  |
| 1.01-2.0   | 80        | 128    | 8.22%   |
| 4.01-10.0  | 27        | 51     | 2.77%   |
| 2.01-3.0   | 24        | 38     | 2.47%   |
| 3.01-4.0   | 23        | 31     | 2.36%   |
| 10.01-20.0 | 9         | 15     | 0.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 305       | 25.57%  |
| 251-500        | 242       | 20.28%  |
| 501-1000       | 187       | 15.67%  |
| 1001-2000      | 102       | 8.55%   |
| 1-20           | 80        | 6.71%   |
| More than 3000 | 71        | 5.95%   |
| 51-100         | 63        | 5.28%   |
| Unknown        | 56        | 4.69%   |
| 21-50          | 46        | 3.86%   |
| 2001-3000      | 41        | 3.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 444       | 36.39%  |
| 21-50          | 203       | 16.64%  |
| 101-250        | 146       | 11.97%  |
| 51-100         | 122       | 10%     |
| 251-500        | 107       | 8.77%   |
| 501-1000       | 73        | 5.98%   |
| Unknown        | 56        | 4.59%   |
| 1001-2000      | 37        | 3.03%   |
| More than 3000 | 22        | 1.8%    |
| 2001-3000      | 10        | 0.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 4.23%   |
| Kingston SHPM2280P2H 480G SSD         | 3         | 3      | 4.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 2.82%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 2.82%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2      | 2.82%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 2.82%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 1.41%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 1.41%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 1      | 1.41%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 1.41%   |
| WDC WD1600BEVT-00M9YT0 160GB          | 1         | 2      | 1.41%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 1.41%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1         | 1      | 1.41%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 1.41%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1         | 1      | 1.41%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 1.41%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 1.41%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 1.41%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.41%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 1.41%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.41%   |
| SK hynix SC308 SATA 256GB SSD         | 1         | 1      | 1.41%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.41%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.41%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.41%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.41%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.41%   |
| Seagate ST380013AS 80GB               | 1         | 1      | 1.41%   |
| Seagate ST3400633AS 400GB             | 1         | 1      | 1.41%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 1.41%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.41%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.41%   |
| Seagate ST3200822AS 200GB             | 1         | 1      | 1.41%   |
| Seagate ST31500341AS 1TB              | 1         | 1      | 1.41%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.41%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 1      | 1.41%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 1.41%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 2      | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 1      | 1.41%   |
| SanDisk SSD U100 24GB                 | 1         | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 22.73%  |
| WDC                 | 11        | 13     | 16.67%  |
| Kingston            | 10        | 12     | 15.15%  |
| Toshiba             | 5         | 5      | 7.58%   |
| Samsung Electronics | 4         | 5      | 6.06%   |
| HGST                | 4         | 4      | 6.06%   |
| SK hynix            | 3         | 3      | 4.55%   |
| SanDisk             | 2         | 2      | 3.03%   |
| OCZ                 | 2         | 2      | 3.03%   |
| Micron Technology   | 2         | 2      | 3.03%   |
| Intel               | 2         | 2      | 3.03%   |
| Hitachi             | 2         | 4      | 3.03%   |
| Leven               | 1         | 1      | 1.52%   |
| Crucial             | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |
| Unknown             | 1         | 2      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 18     | 40.54%  |
| WDC                 | 9         | 11     | 24.32%  |
| HGST                | 4         | 4      | 10.81%  |
| Toshiba             | 3         | 3      | 8.11%   |
| Samsung Electronics | 2         | 3      | 5.41%   |
| Hitachi             | 2         | 4      | 5.41%   |
| Apple               | 1         | 1      | 2.7%    |
| Unknown             | 1         | 2      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 46     | 54.1%   |
| SSD  | 26        | 29     | 42.62%  |
| NVMe | 2         | 2      | 3.28%   |

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
| Detected | 744       | 1426   | 61.13%  |
| Works    | 413       | 745    | 33.94%  |
| Malfunc  | 60        | 77     | 4.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 686       | 47.25%  |
| Samsung Electronics              | 202       | 13.91%  |
| AMD                              | 202       | 13.91%  |
| SanDisk                          | 65        | 4.48%   |
| SK hynix                         | 42        | 2.89%   |
| Kingston Technology Company      | 42        | 2.89%   |
| ASMedia Technology               | 28        | 1.93%   |
| Toshiba America Info Systems     | 26        | 1.79%   |
| Phison Electronics               | 26        | 1.79%   |
| Nvidia                           | 23        | 1.58%   |
| Micron Technology                | 18        | 1.24%   |
| Marvell Technology Group         | 15        | 1.03%   |
| JMicron Technology               | 14        | 0.96%   |
| Micron/Crucial Technology        | 12        | 0.83%   |
| Silicon Motion                   | 7         | 0.48%   |
| KIOXIA                           | 7         | 0.48%   |
| ADATA Technology                 | 7         | 0.48%   |
| Seagate Technology               | 5         | 0.34%   |
| Lenovo                           | 5         | 0.34%   |
| Union Memory (Shenzhen)          | 3         | 0.21%   |
| VIA Technologies                 | 2         | 0.14%   |
| Solid State Storage Technology   | 2         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.14%   |
| Hewlett-Packard                  | 2         | 0.14%   |
| Apple                            | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Silicon Image                    | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| LSI Logic / Symbios Logic        | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| HighPoint Technologies           | 1         | 0.07%   |
| Broadcom / LSI                   | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 143       | 8.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 104       | 6.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 62        | 3.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 52        | 3.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 46        | 2.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 39        | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 2.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 2%      |
| AMD 400 Series Chipset SATA Controller                                         | 31        | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 1.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29        | 1.76%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 26        | 1.58%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 24        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 21        | 1.28%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 20        | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 19        | 1.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 19        | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 19        | 1.15%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 18        | 1.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 17        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 16        | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 15        | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 14        | 0.85%   |
| Phison E12 NVMe Controller                                                     | 13        | 0.79%   |
| Intel SSD 660P Series                                                          | 13        | 0.79%   |
| Intel SATA Controller [RAID mode]                                              | 13        | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 13        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 12        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 11        | 0.67%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 11        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 11        | 0.67%   |
| AMD 600 Series Chipset SATA Controller                                         | 11        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 809       | 56.02%  |
| NVMe | 450       | 31.16%  |
| IDE  | 115       | 7.96%   |
| RAID | 69        | 4.78%   |
| SAS  | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 824       | 73.77%  |
| AMD      | 278       | 24.89%  |
| ARM      | 14        | 1.25%   |
| QUALCOMM | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 17        | 1.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 16        | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 14        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 11        | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor          | 11        | 0.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 10        | 0.89%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 10        | 0.89%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 10        | 0.89%   |
| ARM Processor                              | 10        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 9         | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz          | 9         | 0.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 9         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz          | 8         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 8         | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 8         | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 8         | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 8         | 0.71%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 8         | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 8         | 0.71%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 8         | 0.71%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 8         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 7         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 7         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 7         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 7         | 0.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 7         | 0.63%   |
| Intel Core i7-8665U CPU @ 1.90GHz          | 6         | 0.54%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 6         | 0.54%   |
| Intel Core i7-7600U CPU @ 2.80GHz          | 6         | 0.54%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 6         | 0.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 6         | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 6         | 0.54%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 6         | 0.54%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 6         | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 6         | 0.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 6         | 0.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 5         | 0.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 5         | 0.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 5         | 0.45%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 5         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 278       | 24.87%  |
| Intel Core i7           | 256       | 22.9%   |
| Other                   | 76        | 6.8%    |
| AMD Ryzen 7             | 72        | 6.44%   |
| Intel Core i3           | 53        | 4.74%   |
| AMD Ryzen 5             | 53        | 4.74%   |
| Intel Core 2 Duo        | 44        | 3.94%   |
| AMD Ryzen 9             | 36        | 3.22%   |
| Intel Celeron           | 32        | 2.86%   |
| Intel Xeon              | 19        | 1.7%    |
| Intel Pentium           | 15        | 1.34%   |
| AMD Ryzen 7 PRO         | 14        | 1.25%   |
| Intel Core i9           | 13        | 1.16%   |
| Intel Atom              | 12        | 1.07%   |
| AMD Ryzen 3             | 11        | 0.98%   |
| AMD FX                  | 11        | 0.98%   |
| AMD A6                  | 11        | 0.98%   |
| Intel Pentium Dual-Core | 9         | 0.81%   |
| AMD A8                  | 9         | 0.81%   |
| Intel Pentium Silver    | 6         | 0.54%   |
| AMD Ryzen Threadripper  | 6         | 0.54%   |
| Intel Core 2 Quad       | 5         | 0.45%   |
| AMD A10                 | 5         | 0.45%   |
| Intel Core 2            | 4         | 0.36%   |
| ARM BCM                 | 4         | 0.36%   |
| AMD Turion 64 X2 Mobile | 4         | 0.36%   |
| AMD Ryzen 5 PRO         | 4         | 0.36%   |
| AMD Phenom II X4        | 4         | 0.36%   |
| AMD E1                  | 4         | 0.36%   |
| AMD E                   | 4         | 0.36%   |
| AMD Athlon 64 X2        | 4         | 0.36%   |
| AMD A4                  | 4         | 0.36%   |
| Intel Pentium M         | 3         | 0.27%   |
| Intel Pentium Dual      | 3         | 0.27%   |
| Intel Core m5           | 3         | 0.27%   |
| AMD Athlon II X4        | 3         | 0.27%   |
| AMD Athlon              | 3         | 0.27%   |
| Intel Genuine           | 2         | 0.18%   |
| Intel Core m3           | 2         | 0.18%   |
| AMD Athlon II Neo       | 2         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 408       | 36.46%  |
| 4       | 392       | 35.03%  |
| 8       | 120       | 10.72%  |
| 6       | 111       | 9.92%   |
| 12      | 28        | 2.5%    |
| 1       | 20        | 1.79%   |
| 16      | 19        | 1.7%    |
| 10      | 7         | 0.63%   |
| 24      | 4         | 0.36%   |
| 14      | 3         | 0.27%   |
| Unknown | 3         | 0.27%   |
| 32      | 2         | 0.18%   |
| 64      | 1         | 0.09%   |
| 3       | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1108      | 99.19%  |
| 2       | 6         | 0.54%   |
| Unknown | 3         | 0.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 809       | 72.43%  |
| 1       | 304       | 27.22%  |
| Unknown | 3         | 0.27%   |
| 4       | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1084      | 96.61%  |
| Unknown        | 30        | 2.67%   |
| 32-bit         | 6         | 0.53%   |
| 64-bit         | 2         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 400       | 34.39%  |
| 0x306a9    | 47        | 4.04%   |
| 0x206a7    | 45        | 3.87%   |
| 0x306c3    | 44        | 3.78%   |
| 0x40651    | 32        | 2.75%   |
| 0x1067a    | 29        | 2.49%   |
| 0x906ea    | 28        | 2.41%   |
| 0x406e3    | 28        | 2.41%   |
| 0x806e9    | 25        | 2.15%   |
| 0x506e3    | 24        | 2.06%   |
| 0x806ea    | 23        | 1.98%   |
| 0x906e9    | 18        | 1.55%   |
| 0x806ec    | 18        | 1.55%   |
| 0x20655    | 16        | 1.38%   |
| 0x08600106 | 16        | 1.38%   |
| 0x0a50000c | 14        | 1.2%    |
| 0x0800820d | 13        | 1.12%   |
| 0x806c1    | 12        | 1.03%   |
| 0x08701021 | 12        | 1.03%   |
| 0x906ed    | 11        | 0.95%   |
| 0x6fd      | 10        | 0.86%   |
| 0x08001138 | 9         | 0.77%   |
| 0x90672    | 8         | 0.69%   |
| 0x806eb    | 8         | 0.69%   |
| 0x20652    | 8         | 0.69%   |
| 0x706e5    | 7         | 0.6%    |
| 0x306d4    | 7         | 0.6%    |
| 0x10676    | 7         | 0.6%    |
| 0x0a601203 | 7         | 0.6%    |
| 0x08701013 | 7         | 0.6%    |
| 0x0810100b | 7         | 0.6%    |
| 0x010000c8 | 7         | 0.6%    |
| 0x406c3    | 6         | 0.52%   |
| 0x0a404102 | 6         | 0.52%   |
| 0x0a201009 | 6         | 0.52%   |
| 0x08608103 | 6         | 0.52%   |
| 0x08600104 | 6         | 0.52%   |
| 0x08108109 | 6         | 0.52%   |
| 0x07030105 | 6         | 0.52%   |
| 0x08108102 | 5         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 207       | 18.5%   |
| Haswell          | 117       | 10.46%  |
| Skylake          | 87        | 7.77%   |
| SandyBridge      | 72        | 6.43%   |
| Unknown          | 72        | 6.43%   |
| IvyBridge        | 69        | 6.17%   |
| Zen 2            | 62        | 5.54%   |
| Penryn           | 51        | 4.56%   |
| Zen 3            | 48        | 4.29%   |
| Westmere         | 31        | 2.77%   |
| Zen+             | 29        | 2.59%   |
| TigerLake        | 24        | 2.14%   |
| Broadwell        | 24        | 2.14%   |
| Core             | 23        | 2.06%   |
| Zen              | 21        | 1.88%   |
| CometLake        | 20        | 1.79%   |
| Alderlake Hybrid | 20        | 1.79%   |
| Silvermont       | 18        | 1.61%   |
| Piledriver       | 13        | 1.16%   |
| K10              | 12        | 1.07%   |
| IceLake          | 12        | 1.07%   |
| Puma             | 9         | 0.8%    |
| Nehalem          | 9         | 0.8%    |
| K8 Hammer        | 9         | 0.8%    |
| Goldmont plus    | 9         | 0.8%    |
| Excavator        | 8         | 0.71%   |
| Steamroller      | 6         | 0.54%   |
| Goldmont         | 6         | 0.54%   |
| Bonnell          | 6         | 0.54%   |
| Bobcat           | 6         | 0.54%   |
| P6               | 5         | 0.45%   |
| Jaguar           | 4         | 0.36%   |
| K8 & K10 hybrid  | 3         | 0.27%   |
| K10 Llano        | 3         | 0.27%   |
| Bulldozer        | 3         | 0.27%   |
| Sapphire Rapids  | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 612       | 46.97%  |
| Nvidia                           | 404       | 31.01%  |
| AMD                              | 280       | 21.49%  |
| ASPEED Technology                | 4         | 0.31%   |
| Matrox Electronics Systems       | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 54        | 4.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 42        | 3.14%   |
| Intel UHD Graphics 620                                                                   | 36        | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 36        | 2.69%   |
| Intel HD Graphics 620                                                                    | 31        | 2.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 2.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 26        | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.87%   |
| Intel HD Graphics 630                                                                    | 23        | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.57%   |
| Intel HD Graphics 530                                                                    | 19        | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 16        | 1.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.05%   |
| Intel HD Graphics 5500                                                                   | 13        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 0.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.82%   |
| AMD Lucienne                                                                             | 11        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10        | 0.75%   |
| AMD Rembrandt [Radeon 680M]                                                              | 10        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 9         | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 9         | 0.67%   |
| AMD Raphael                                                                              | 9         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 0.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 438       | 39%     |
| 1 x Nvidia      | 243       | 21.64%  |
| 1 x AMD         | 212       | 18.88%  |
| Intel + Nvidia  | 134       | 11.93%  |
| 2 x AMD         | 23        | 2.05%   |
| Intel + AMD     | 22        | 1.96%   |
| AMD + Nvidia    | 22        | 1.96%   |
| Other           | 17        | 1.51%   |
| 2 x Intel       | 3         | 0.27%   |
| Nvidia + ASPEED | 3         | 0.27%   |
| 2 x Nvidia      | 2         | 0.18%   |
| 1 x Matrox      | 2         | 0.18%   |
| 1 x SiS         | 1         | 0.09%   |
| 1 x ASPEED      | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 861       | 75.73%  |
| Proprietary | 232       | 20.4%   |
| Unknown     | 44        | 3.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 656       | 57.49%  |
| 1.01-2.0   | 135       | 11.83%  |
| 0.01-0.5   | 115       | 10.08%  |
| 7.01-8.0   | 62        | 5.43%   |
| 3.01-4.0   | 54        | 4.73%   |
| 0.51-1.0   | 48        | 4.21%   |
| 5.01-6.0   | 35        | 3.07%   |
| 8.01-16.0  | 22        | 1.93%   |
| 2.01-3.0   | 7         | 0.61%   |
| 16.01-24.0 | 6         | 0.53%   |
| 4.01-5.0   | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 176       | 13.96%  |
| AU Optronics            | 157       | 12.45%  |
| LG Display              | 118       | 9.36%   |
| BOE                     | 90        | 7.14%   |
| Chimei Innolux          | 84        | 6.66%   |
| Dell                    | 75        | 5.95%   |
| Lenovo                  | 64        | 5.08%   |
| AOC                     | 43        | 3.41%   |
| Hewlett-Packard         | 41        | 3.25%   |
| Philips                 | 39        | 3.09%   |
| Apple                   | 38        | 3.01%   |
| Ancor Communications    | 31        | 2.46%   |
| BenQ                    | 28        | 2.22%   |
| Acer                    | 28        | 2.22%   |
| Goldstar                | 27        | 2.14%   |
| ASUSTek Computer        | 23        | 1.82%   |
| Sharp                   | 21        | 1.67%   |
| Sony                    | 15        | 1.19%   |
| Chi Mei Optoelectronics | 15        | 1.19%   |
| InfoVision              | 10        | 0.79%   |
| Medion                  | 9         | 0.71%   |
| PANDA                   | 8         | 0.63%   |
| Panasonic               | 8         | 0.63%   |
| MSI                     | 7         | 0.56%   |
| Unknown                 | 6         | 0.48%   |
| Lenovo Group Limited    | 6         | 0.48%   |
| Valve                   | 5         | 0.4%    |
| Packard Bell            | 5         | 0.4%    |
| IBM                     | 5         | 0.4%    |
| CSO                     | 5         | 0.4%    |
| ViewSonic               | 4         | 0.32%   |
| LG Philips              | 4         | 0.32%   |
| LG Electronics          | 4         | 0.32%   |
| Gigabyte Technology     | 4         | 0.32%   |
| Fujitsu Siemens         | 4         | 0.32%   |
| Vestel Elektronik       | 3         | 0.24%   |
| TMX                     | 2         | 0.16%   |
| Tech Concepts           | 2         | 0.16%   |
| Seiko/Epson             | 2         | 0.16%   |
| RTK                     | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 9         | 0.68%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 8         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.6%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.53%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6         | 0.45%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.38%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                     | 5         | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 0.3%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 4         | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.3%    |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 4         | 0.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.3%    |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 4         | 0.3%    |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch        | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch        | 4         | 0.3%    |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 4         | 0.3%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.3%    |
| AOC 2790WG5 AOC2790 1920x1080 598x336mm 27.0-inch                     | 4         | 0.3%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 4         | 0.3%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 4         | 0.3%    |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 4         | 0.3%    |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 3         | 0.23%   |
| Sony TV SNYEE01 1920x1080                                             | 3         | 0.23%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 3         | 0.23%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 3         | 0.23%   |
| Packard Bell Maestro223DXL PKB01B2 1920x1080 477x268mm 21.5-inch      | 3         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.23%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 545       | 45.15%  |
| 1366x768 (WXGA)    | 120       | 9.94%   |
| 3840x2160 (4K)     | 109       | 9.03%   |
| 2560x1440 (QHD)    | 99        | 8.2%    |
| 1600x900 (HD+)     | 63        | 5.22%   |
| 1680x1050 (WSXGA+) | 35        | 2.9%    |
| 1920x1200 (WUXGA)  | 30        | 2.49%   |
| 1280x800 (WXGA)    | 24        | 1.99%   |
| 1440x900 (WXGA+)   | 23        | 1.91%   |
| 1280x1024 (SXGA)   | 23        | 1.91%   |
| 3440x1440          | 20        | 1.66%   |
| Unknown            | 19        | 1.57%   |
| 2560x1600          | 16        | 1.33%   |
| 2880x1800          | 11        | 0.91%   |
| 3840x1080          | 10        | 0.83%   |
| 800x1280           | 5         | 0.41%   |
| 1360x768           | 5         | 0.41%   |
| 3200x1800 (QHD+)   | 4         | 0.33%   |
| 1920x540           | 4         | 0.33%   |
| 3840x1200          | 3         | 0.25%   |
| 2160x1440          | 3         | 0.25%   |
| 1400x1050          | 3         | 0.25%   |
| 3840x2400          | 2         | 0.17%   |
| 3840x1600          | 2         | 0.17%   |
| 3840x1100          | 2         | 0.17%   |
| 3000x2000          | 2         | 0.17%   |
| 2560x1080          | 2         | 0.17%   |
| 1920x1280          | 2         | 0.17%   |
| 1024x600           | 2         | 0.17%   |
| 9840x3840          | 1         | 0.08%   |
| 6400x2160          | 1         | 0.08%   |
| 5760x1440          | 1         | 0.08%   |
| 5760x1080          | 1         | 0.08%   |
| 5120x1440          | 1         | 0.08%   |
| 4608x1440          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 3280x1080          | 1         | 0.08%   |
| 3200x1200          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 266       | 21.09%  |
| 27      | 134       | 10.63%  |
| 14      | 133       | 10.55%  |
| 13      | 125       | 9.91%   |
| 24      | 105       | 8.33%   |
| Unknown | 69        | 5.47%   |
| 23      | 64        | 5.08%   |
| 17      | 60        | 4.76%   |
| 31      | 45        | 3.57%   |
| 21      | 41        | 3.25%   |
| 12      | 31        | 2.46%   |
| 22      | 24        | 1.9%    |
| 19      | 23        | 1.82%   |
| 34      | 19        | 1.51%   |
| 20      | 15        | 1.19%   |
| 72      | 14        | 1.11%   |
| 84      | 13        | 1.03%   |
| 16      | 8         | 0.63%   |
| 11      | 8         | 0.63%   |
| 18      | 6         | 0.48%   |
| 40      | 5         | 0.4%    |
| 32      | 5         | 0.4%    |
| 25      | 5         | 0.4%    |
| 48      | 4         | 0.32%   |
| 7       | 4         | 0.32%   |
| 35      | 3         | 0.24%   |
| 10      | 3         | 0.24%   |
| 74      | 2         | 0.16%   |
| 55      | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 38      | 2         | 0.16%   |
| 37      | 2         | 0.16%   |
| 33      | 2         | 0.16%   |
| 29      | 2         | 0.16%   |
| 28      | 2         | 0.16%   |
| 85      | 1         | 0.08%   |
| 75      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 455       | 36.99%  |
| 501-600     | 268       | 21.79%  |
| 201-300     | 111       | 9.02%   |
| 401-500     | 92        | 7.48%   |
| 351-400     | 80        | 6.5%    |
| Unknown     | 69        | 5.61%   |
| 601-700     | 65        | 5.28%   |
| 1501-2000   | 31        | 2.52%   |
| 701-800     | 26        | 2.11%   |
| 801-900     | 13        | 1.06%   |
| 1001-1500   | 13        | 1.06%   |
| 1-100       | 5         | 0.41%   |
| 901-1000    | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 837       | 74.07%  |
| 16/10   | 157       | 13.89%  |
| Unknown | 57        | 5.04%   |
| 21/9    | 26        | 2.3%    |
| 5/4     | 21        | 1.86%   |
| 3/2     | 13        | 1.15%   |
| 32/9    | 6         | 0.53%   |
| 4/3     | 5         | 0.44%   |
| 0.67    | 4         | 0.35%   |
| 3.40    | 2         | 0.18%   |
| 6/5     | 1         | 0.09%   |
| 3.20    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 263       | 21.06%  |
| 81-90          | 202       | 16.17%  |
| 201-250        | 181       | 14.49%  |
| 301-350        | 134       | 10.73%  |
| 351-500        | 76        | 6.08%   |
| Unknown        | 69        | 5.52%   |
| 71-80          | 55        | 4.4%    |
| 251-300        | 45        | 3.6%    |
| 151-200        | 45        | 3.6%    |
| 121-130        | 44        | 3.52%   |
| More than 1000 | 39        | 3.12%   |
| 61-70          | 27        | 2.16%   |
| 501-1000       | 17        | 1.36%   |
| 131-140        | 12        | 0.96%   |
| 51-60          | 10        | 0.8%    |
| 141-150        | 10        | 0.8%    |
| 111-120        | 9         | 0.72%   |
| 1-40           | 5         | 0.4%    |
| 41-50          | 3         | 0.24%   |
| 91-100         | 3         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 360       | 29.9%   |
| 121-160       | 359       | 29.82%  |
| 101-120       | 258       | 21.43%  |
| 161-240       | 90        | 7.48%   |
| Unknown       | 69        | 5.73%   |
| More than 240 | 46        | 3.82%   |
| 1-50          | 22        | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 867       | 75.72%  |
| 2     | 200       | 17.47%  |
| 0     | 45        | 3.93%   |
| 3     | 31        | 2.71%   |
| 4     | 2         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 638       | 38.14%  |
| Realtek Semiconductor                  | 514       | 30.72%  |
| Qualcomm Atheros                       | 138       | 8.25%   |
| Broadcom                               | 91        | 5.44%   |
| MediaTek                               | 29        | 1.73%   |
| Broadcom Limited                       | 22        | 1.32%   |
| Lenovo                                 | 21        | 1.26%   |
| Nvidia                                 | 19        | 1.14%   |
| Ralink                                 | 17        | 1.02%   |
| Sierra Wireless                        | 15        | 0.9%    |
| Ralink Technology                      | 15        | 0.9%    |
| Ericsson Business Mobile Networks      | 12        | 0.72%   |
| TP-Link                                | 11        | 0.66%   |
| Aquantia                               | 10        | 0.6%    |
| Marvell Technology Group               | 9         | 0.54%   |
| DisplayLink                            | 9         | 0.54%   |
| ASIX Electronics                       | 8         | 0.48%   |
| Samsung Electronics                    | 7         | 0.42%   |
| ASUSTek Computer                       | 7         | 0.42%   |
| Qualcomm                               | 6         | 0.36%   |
| Microsoft                              | 6         | 0.36%   |
| NetGear                                | 5         | 0.3%    |
| Huawei Technologies                    | 5         | 0.3%    |
| Dell                                   | 5         | 0.3%    |
| Qualcomm Atheros Communications        | 4         | 0.24%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.24%   |
| IMC Networks                           | 4         | 0.24%   |
| Edimax Technology                      | 4         | 0.24%   |
| D-Link System                          | 4         | 0.24%   |
| Xiaomi                                 | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| D-Link                                 | 3         | 0.18%   |
| ZyXEL Communications                   | 2         | 0.12%   |
| Standard Microsystems                  | 2         | 0.12%   |
| Microchip Technology                   | 2         | 0.12%   |
| Linksys                                | 2         | 0.12%   |
| Hewlett-Packard                        | 2         | 0.12%   |
| Unknown                                | 1         | 0.06%   |
| Texas Instruments                      | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 357       | 17.41%  |
| Intel Wi-Fi 6 AX200                                                    | 63        | 3.07%   |
| Intel Wireless 8265 / 8275                                             | 56        | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 48        | 2.34%   |
| Intel Wireless 7260                                                    | 41        | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 1.9%    |
| Intel Wireless 8260                                                    | 35        | 1.71%   |
| Intel I211 Gigabit Network Connection                                  | 34        | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                      | 33        | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 29        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                   | 28        | 1.37%   |
| Intel Wireless 7265                                                    | 27        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 26        | 1.27%   |
| Intel Ethernet Connection I217-LM                                      | 25        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                                  | 23        | 1.12%   |
| Intel Wi-Fi 6 AX201                                                    | 19        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 19        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 17        | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 17        | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 17        | 0.83%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 17        | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 16        | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 16        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 0.68%   |
| Intel Centrino Wireless-N 2230                                         | 14        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 13        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                         | 13        | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 12        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 12        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 0.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 11        | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 11        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 503       | 53.12%  |
| Realtek Semiconductor           | 116       | 12.25%  |
| Qualcomm Atheros                | 107       | 11.3%   |
| Broadcom                        | 66        | 6.97%   |
| MediaTek                        | 28        | 2.96%   |
| Ralink                          | 17        | 1.8%    |
| Broadcom Limited                | 16        | 1.69%   |
| Sierra Wireless                 | 15        | 1.58%   |
| Ralink Technology               | 15        | 1.58%   |
| TP-Link                         | 11        | 1.16%   |
| ASUSTek Computer                | 7         | 0.74%   |
| Microsoft                       | 6         | 0.63%   |
| Qualcomm                        | 5         | 0.53%   |
| NetGear                         | 5         | 0.53%   |
| Qualcomm Atheros Communications | 4         | 0.42%   |
| IMC Networks                    | 4         | 0.42%   |
| Edimax Technology               | 4         | 0.42%   |
| Dell                            | 4         | 0.42%   |
| D-Link System                   | 4         | 0.42%   |
| D-Link                          | 3         | 0.32%   |
| ZyXEL Communications            | 2         | 0.21%   |
| Marvell Technology Group        | 2         | 0.21%   |
| Philips (or NXP)                | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| FIBOCOM                         | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 63        | 6.62%   |
| Intel Wireless 8265 / 8275                                     | 56        | 5.89%   |
| Intel Wireless 7260                                            | 41        | 4.31%   |
| Intel Wireless 8260                                            | 35        | 3.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 29        | 3.05%   |
| Intel Wireless 7265                                            | 27        | 2.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 2.73%   |
| Intel Wi-Fi 6 AX201                                            | 19        | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 17        | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 1.79%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 17        | 1.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 16        | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 1.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 1.47%   |
| Intel Centrino Wireless-N 2230                                 | 14        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.37%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.26%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 12        | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 0.95%   |
| Intel Wireless 3165                                            | 9         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 0.95%   |
| Sierra Wireless EM7455                                         | 8         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 0.84%   |
| Realtek 802.11ac NIC                                           | 8         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                 | 8         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 0.84%   |
| Intel Wireless 3160                                            | 8         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 7         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.74%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 466       | 44.25%  |
| Intel                                  | 389       | 36.94%  |
| Qualcomm Atheros                       | 43        | 4.08%   |
| Broadcom                               | 41        | 3.89%   |
| Lenovo                                 | 21        | 1.99%   |
| Nvidia                                 | 19        | 1.8%    |
| Aquantia                               | 10        | 0.95%   |
| DisplayLink                            | 9         | 0.85%   |
| ASIX Electronics                       | 8         | 0.76%   |
| Samsung Electronics                    | 7         | 0.66%   |
| Marvell Technology Group               | 7         | 0.66%   |
| Broadcom Limited                       | 6         | 0.57%   |
| Xiaomi                                 | 3         | 0.28%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.28%   |
| ICS Advent                             | 3         | 0.28%   |
| Standard Microsystems                  | 2         | 0.19%   |
| Microchip Technology                   | 2         | 0.19%   |
| Huawei Technologies                    | 2         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Solarflare Communications              | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.09%   |
| Qualcomm                               | 1         | 0.09%   |
| Motorola PCS                           | 1         | 0.09%   |
| MediaTek                               | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| JMicron Technology                     | 1         | 0.09%   |
| Insyde Software                        | 1         | 0.09%   |
| HMD Global                             | 1         | 0.09%   |
| Hewlett-Packard                        | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 357       | 33.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 48        | 4.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 39        | 3.62%   |
| Intel I211 Gigabit Network Connection                                          | 34        | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                              | 33        | 3.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 31        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                                           | 28        | 2.6%    |
| Intel Ethernet Connection I217-LM                                              | 25        | 2.32%   |
| Intel Ethernet Connection (4) I219-LM                                          | 23        | 2.14%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.58%   |
| Intel Ethernet Connection (7) I219-V                                           | 17        | 1.58%   |
| Intel Ethernet Controller I225-V                                               | 16        | 1.49%   |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.21%   |
| Intel Ethernet Connection (4) I219-V                                           | 13        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 1.12%   |
| Intel Ethernet Connection I219-V                                               | 11        | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 11        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                                          | 8         | 0.74%   |
| Intel 82579V Gigabit Network Connection                                        | 8         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 0.65%   |
| Intel I210 Gigabit Network Connection                                          | 7         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 0.65%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.56%   |
| Lenovo ThinkPad Lan                                                            | 6         | 0.56%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                          | 6         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                                          | 6         | 0.56%   |
| Intel 82566MM Gigabit Network Connection                                       | 6         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 0.56%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 6         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 5         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 5         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 5         | 0.46%   |
| Lenovo USB-C Dock Ethernet                                                     | 5         | 0.46%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 5         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 971       | 51.43%  |
| WiFi     | 893       | 47.3%   |
| Modem    | 20        | 1.06%   |
| Unknown  | 4         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 681       | 58.11%  |
| Ethernet | 491       | 41.89%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 664       | 59.13%  |
| 1     | 396       | 35.26%  |
| 3     | 34        | 3.03%   |
| 0     | 24        | 2.14%   |
| 4     | 3         | 0.27%   |
| 5     | 2         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1057      | 94.12%  |
| Yes  | 66        | 5.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 409       | 53.75%  |
| Broadcom                        | 53        | 6.96%   |
| Realtek Semiconductor           | 50        | 6.57%   |
| Cambridge Silicon Radio         | 39        | 5.12%   |
| Qualcomm Atheros Communications | 37        | 4.86%   |
| Apple                           | 36        | 4.73%   |
| IMC Networks                    | 33        | 4.34%   |
| Foxconn / Hon Hai               | 23        | 3.02%   |
| Lite-On Technology              | 21        | 2.76%   |
| ASUSTek Computer                | 14        | 1.84%   |
| Hewlett-Packard                 | 11        | 1.45%   |
| MediaTek                        | 8         | 1.05%   |
| USI                             | 4         | 0.53%   |
| Marvell Semiconductor           | 3         | 0.39%   |
| Dell                            | 3         | 0.39%   |
| Realtek                         | 2         | 0.26%   |
| Ralink Technology               | 2         | 0.26%   |
| Ralink                          | 2         | 0.26%   |
| Belkin Components               | 2         | 0.26%   |
| Toshiba                         | 1         | 0.13%   |
| Taiyo Yuden                     | 1         | 0.13%   |
| Integrated System Solution      | 1         | 0.13%   |
| HTC (High Tech Computer)        | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |
| Actions                         | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 93        | 12.22%  |
| Intel Bluetooth Device                              | 86        | 11.3%   |
| Intel AX200 Bluetooth                               | 58        | 7.62%   |
| Intel AX201 Bluetooth                               | 48        | 6.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 44        | 5.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 5.12%   |
| Realtek Bluetooth Radio                             | 27        | 3.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 21        | 2.76%   |
| Apple Bluetooth Host Controller                     | 20        | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 2.37%   |
| Intel AX210 Bluetooth                               | 17        | 2.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 1.84%   |
| IMC Networks Bluetooth Radio                        | 14        | 1.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.71%   |
| Intel AX211 Bluetooth                               | 12        | 1.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 1.45%   |
| IMC Networks Wireless_Device                        | 11        | 1.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.31%   |
| MediaTek Wireless_Device                            | 8         | 1.05%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 7         | 0.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.79%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.79%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 5         | 0.66%   |
| USI Bluetooth Device                                | 4         | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.53%   |
| Lite-On Bluetooth Device                            | 4         | 0.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.53%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.39%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 785       | 47.32%  |
| Nvidia                               | 327       | 19.71%  |
| AMD                                  | 317       | 19.11%  |
| C-Media Electronics                  | 19        | 1.15%   |
| Kingston Technology                  | 18        | 1.08%   |
| Lenovo                               | 17        | 1.02%   |
| SteelSeries ApS                      | 16        | 0.96%   |
| Logitech                             | 15        | 0.9%    |
| GN Netcom                            | 13        | 0.78%   |
| Creative Technology                  | 12        | 0.72%   |
| ASUSTek Computer                     | 12        | 0.72%   |
| Creative Labs                        | 10        | 0.6%    |
| XMOS                                 | 5         | 0.3%    |
| Realtek Semiconductor                | 5         | 0.3%    |
| Razer USA                            | 5         | 0.3%    |
| Hewlett-Packard                      | 5         | 0.3%    |
| Texas Instruments                    | 4         | 0.24%   |
| RODE Microphones                     | 4         | 0.24%   |
| Focusrite-Novation                   | 4         | 0.24%   |
| Corsair                              | 4         | 0.24%   |
| BEHRINGER International              | 4         | 0.24%   |
| VIA Technologies                     | 3         | 0.18%   |
| Plantronics                          | 3         | 0.18%   |
| JMTek                                | 3         | 0.18%   |
| DSEA A/S                             | 3         | 0.18%   |
| Yamaha                               | 2         | 0.12%   |
| Trust                                | 2         | 0.12%   |
| Tenx Technology                      | 2         | 0.12%   |
| Sony                                 | 2         | 0.12%   |
| Astro Gaming                         | 2         | 0.12%   |
| Valve Software                       | 1         | 0.06%   |
| Turtle Beach                         | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| TerraTec Electronic                  | 1         | 0.06%   |
| Syntek                               | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.06%   |
| Shure                                | 1         | 0.06%   |
| Setek Elektronik                     | 1         | 0.06%   |
| SAVITECH                             | 1         | 0.06%   |
| Samsung Electronics                  | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 118       | 5.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 109       | 5.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 70        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 66        | 3.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 62        | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 60        | 3.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 53        | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 50        | 2.53%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 44        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 40        | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34        | 1.72%   |
| Intel 200 Series PCH HD Audio                                              | 30        | 1.52%   |
| AMD FCH Azalia Controller                                                  | 29        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 25        | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 24        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 21        | 1.06%   |
| Intel Broadwell-U Audio Controller                                         | 21        | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 20        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 19        | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 18        | 0.91%   |
| AMD Navi 10 HDMI Audio                                                     | 18        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 17        | 0.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 17        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17        | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 16        | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 15        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 15        | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 0.76%   |
| Intel CM238 HD Audio Controller                                            | 15        | 0.76%   |
| Kingston Technology HyperX 7.1 Audio                                       | 14        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 144       | 23%     |
| SK hynix            | 108       | 17.25%  |
| Kingston            | 81        | 12.94%  |
| Micron Technology   | 69        | 11.02%  |
| Corsair             | 59        | 9.42%   |
| Unknown             | 46        | 7.35%   |
| G.Skill             | 38        | 6.07%   |
| Crucial             | 29        | 4.63%   |
| Elpida              | 14        | 2.24%   |
| Ramaxel Technology  | 9         | 1.44%   |
| Nanya Technology    | 7         | 1.12%   |
| A-DATA Technology   | 3         | 0.48%   |
| Unknown (ABCD)      | 2         | 0.32%   |
| Patriot             | 2         | 0.32%   |
| ff                  | 2         | 0.32%   |
| 4ea5                | 2         | 0.32%   |
| Unknown             | 2         | 0.32%   |
| Unifosa             | 1         | 0.16%   |
| Transcend           | 1         | 0.16%   |
| Team                | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| Neo Forza           | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| fef5                | 1         | 0.16%   |
| Avant               | 1         | 0.16%   |
| Apacer              | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 9         | 1.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 9         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 8         | 1.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 7         | 1.07%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 7         | 1.07%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 7         | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 0.91%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 6         | 0.91%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 5         | 0.76%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 4         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 4         | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.61%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 4         | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 0.61%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s       | 4         | 0.61%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 4         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 3         | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.46%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 3         | 0.46%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 3         | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 3         | 0.46%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.46%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s | 3         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.46%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 3         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 3         | 0.46%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 3         | 0.46%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s       | 3         | 0.46%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 3         | 0.46%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 0.46%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 3         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 2         | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                      | 2         | 0.3%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                         | 2         | 0.3%    |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 281       | 51.09%  |
| DDR3    | 157       | 28.55%  |
| LPDDR3  | 26        | 4.73%   |
| DDR5    | 20        | 3.64%   |
| LPDDR4  | 18        | 3.27%   |
| Unknown | 15        | 2.73%   |
| DDR2    | 13        | 2.36%   |
| SDRAM   | 10        | 1.82%   |
| LPDDR5  | 6         | 1.09%   |
| DDR     | 3         | 0.55%   |
| DRAM    | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 302       | 54.91%  |
| DIMM         | 196       | 35.64%  |
| Row Of Chips | 39        | 7.09%   |
| Chip         | 7         | 1.27%   |
| Unknown      | 5         | 0.91%   |
| FB-DIMM      | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 242       | 41.3%   |
| 16384 | 127       | 21.67%  |
| 4096  | 126       | 21.5%   |
| 2048  | 51        | 8.7%    |
| 32768 | 27        | 4.61%   |
| 1024  | 10        | 1.71%   |
| 512   | 3         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 110       | 18.93%  |
| 3200    | 85        | 14.63%  |
| 2667    | 80        | 13.77%  |
| 2400    | 35        | 6.02%   |
| 2133    | 35        | 6.02%   |
| 1333    | 27        | 4.65%   |
| 3600    | 26        | 4.48%   |
| 1867    | 18        | 3.1%    |
| 1334    | 15        | 2.58%   |
| 667     | 12        | 2.07%   |
| 1067    | 10        | 1.72%   |
| 3800    | 9         | 1.55%   |
| 4267    | 8         | 1.38%   |
| 6400    | 7         | 1.2%    |
| Unknown | 7         | 1.2%    |
| 4800    | 6         | 1.03%   |
| 3866    | 5         | 0.86%   |
| 3733    | 5         | 0.86%   |
| 3400    | 5         | 0.86%   |
| 3266    | 5         | 0.86%   |
| 2933    | 5         | 0.86%   |
| 1800    | 5         | 0.86%   |
| 6000    | 4         | 0.69%   |
| 5600    | 4         | 0.69%   |
| 5200    | 4         | 0.69%   |
| 4266    | 4         | 0.69%   |
| 3666    | 4         | 0.69%   |
| 3000    | 4         | 0.69%   |
| 3534    | 3         | 0.52%   |
| 2666    | 3         | 0.52%   |
| 3500    | 2         | 0.34%   |
| 3466    | 2         | 0.34%   |
| 3066    | 2         | 0.34%   |
| 2800    | 2         | 0.34%   |
| 2048    | 2         | 0.34%   |
| 1866    | 2         | 0.34%   |
| 1639    | 2         | 0.34%   |
| 1066    | 2         | 0.34%   |
| 800     | 2         | 0.34%   |
| 20306   | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 43.48%  |
| Brother Industries  | 6         | 26.09%  |
| Canon               | 4         | 17.39%  |
| Xerox               | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| Prolific Technology | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother DCP-J140W             | 2         | 8.7%    |
| Xerox Phaser 6125N            | 1         | 4.35%   |
| Samsung M2020 Series          | 1         | 4.35%   |
| Prolific PL2305 Parallel Port | 1         | 4.35%   |
| HP Officejet Pro 6230         | 1         | 4.35%   |
| HP LaserJet 1020              | 1         | 4.35%   |
| HP ENVY Photo 6200 series     | 1         | 4.35%   |
| HP ENVY 4520 series           | 1         | 4.35%   |
| HP Deskjet D4300 series       | 1         | 4.35%   |
| HP DeskJet 990c               | 1         | 4.35%   |
| HP DeskJet 5940               | 1         | 4.35%   |
| HP DeskJet 5550               | 1         | 4.35%   |
| HP DeskJet 3700 series        | 1         | 4.35%   |
| HP DeskJet 2600 series        | 1         | 4.35%   |
| Canon PIXMA MX370 Series      | 1         | 4.35%   |
| Canon PIXMA MP280             | 1         | 4.35%   |
| Canon LiDE 400                | 1         | 4.35%   |
| Canon iP7200 series           | 1         | 4.35%   |
| Brother HL-5250DN Printer     | 1         | 4.35%   |
| Brother HL-2240D series       | 1         | 4.35%   |
| Brother HL-2030 Laser Printer | 1         | 4.35%   |
| Brother HL-1210W series       | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 20%     |
| HP ScanJet 5470c/5490c                           | 1         | 20%     |
| HP PSC 1200                                      | 1         | 20%     |
| Canon CanoScan LiDE 600F                         | 1         | 20%     |
| Canon CanoScan LiDE 60                           | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 171       | 25.95%  |
| IMC Networks                           | 63        | 9.56%   |
| Bison Electronics                      | 51        | 7.74%   |
| Realtek Semiconductor                  | 44        | 6.68%   |
| Logitech                               | 40        | 6.07%   |
| Microdia                               | 29        | 4.4%    |
| Apple                                  | 29        | 4.4%    |
| Acer                                   | 28        | 4.25%   |
| Syntek                                 | 25        | 3.79%   |
| Quanta                                 | 25        | 3.79%   |
| Sunplus Innovation Technology          | 22        | 3.34%   |
| Suyin                                  | 21        | 3.19%   |
| Lite-On Technology                     | 21        | 3.19%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 2.73%   |
| Luxvisions Innotech Limited            | 11        | 1.67%   |
| Lenovo                                 | 9         | 1.37%   |
| Microsoft                              | 8         | 1.21%   |
| Silicon Motion                         | 5         | 0.76%   |
| Samsung Electronics                    | 5         | 0.76%   |
| Sonix Technology                       | 4         | 0.61%   |
| Trust                                  | 3         | 0.46%   |
| Primax Electronics                     | 3         | 0.46%   |
| Creative Technology                    | 3         | 0.46%   |
| GEMBIRD                                | 2         | 0.3%    |
| Alcor Micro                            | 2         | 0.3%    |
| Z-Star Microelectronics                | 1         | 0.15%   |
| Valve Software                         | 1         | 0.15%   |
| Tripath Technology                     | 1         | 0.15%   |
| ShineTech                              | 1         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.15%   |
| Ricoh                                  | 1         | 0.15%   |
| Oculus VR                              | 1         | 0.15%   |
| MacroSilicon                           | 1         | 0.15%   |
| Jieli Technology                       | 1         | 0.15%   |
| Intel                                  | 1         | 0.15%   |
| Hewlett-Packard                        | 1         | 0.15%   |
| GenesysLogic Technology                | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| Foxconn / Hon Hai                      | 1         | 0.15%   |
| eMeet                                  | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 58        | 8.73%   |
| IMC Networks Integrated Camera           | 23        | 3.46%   |
| Realtek Integrated_Webcam_HD             | 17        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam        | 17        | 2.56%   |
| Chicony HD WebCam                        | 17        | 2.56%   |
| Bison Integrated Camera                  | 17        | 2.56%   |
| Syntek Integrated Camera                 | 13        | 1.96%   |
| Microdia Integrated_Webcam_HD            | 13        | 1.96%   |
| Lite-On Integrated Camera                | 13        | 1.96%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 10        | 1.51%   |
| Apple Built-in iSight                    | 10        | 1.51%   |
| Syntek Lenovo EasyCamera                 | 8         | 1.2%    |
| Bison SunplusIT Integrated Camera        | 8         | 1.2%    |
| Apple FaceTime HD Camera (Built-in)      | 8         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)  | 7         | 1.05%   |
| Bison Lenovo EasyCamera                  | 7         | 1.05%   |
| Acer ThinkPad P50 Integrated Camera      | 7         | 1.05%   |
| Quanta HD User Facing                    | 6         | 0.9%    |
| Chicony HP HD Camera                     | 6         | 0.9%    |
| Apple FaceTime HD Camera                 | 6         | 0.9%    |
| Acer Integrated Camera                   | 6         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 0.75%   |
| Microdia Integrated Webcam               | 5         | 0.75%   |
| Luxvisions Innotech Limited HP HD Camera | 5         | 0.75%   |
| Logitech StreamCam                       | 5         | 0.75%   |
| Logitech HD Pro Webcam C920              | 5         | 0.75%   |
| IMC Networks USB Camera                  | 5         | 0.75%   |
| Chicony Integrated Camera [ThinkPad]     | 5         | 0.75%   |
| Chicony HP Truevision HD                 | 5         | 0.75%   |
| Chicony EasyCamera                       | 5         | 0.75%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 5         | 0.75%   |
| Realtek Integrated Webcam HD             | 4         | 0.6%    |
| Realtek Integrated Camera                | 4         | 0.6%    |
| Quanta USB2.0 HD UVC WebCam              | 4         | 0.6%    |
| Quanta HP Webcam                         | 4         | 0.6%    |
| Quanta HD Webcam                         | 4         | 0.6%    |
| Logitech Webcam C270                     | 4         | 0.6%    |
| Lenovo Integrated Webcam                 | 4         | 0.6%    |
| Chicony USB 2.0 Camera                   | 4         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 68        | 36.17%  |
| Validity Sensors           | 65        | 34.57%  |
| Upek                       | 17        | 9.04%   |
| Shenzhen Goodix Technology | 14        | 7.45%   |
| AuthenTec                  | 12        | 6.38%   |
| Elan Microelectronics      | 6         | 3.19%   |
| STMicroelectronics         | 3         | 1.6%    |
| LighTuning Technology      | 2         | 1.06%   |
| Samsung Electronics        | 1         | 0.53%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 16.49%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 11.17%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 9.04%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 6.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 4.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 3.72%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.19%   |
| Synaptics UWP WBDI Device                                                  | 6         | 3.19%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.66%   |
| Synaptics  WBDI                                                            | 5         | 2.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.13%   |
| Synaptics WBDI                                                             | 4         | 2.13%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.13%   |
| AuthenTec AES2810                                                          | 4         | 2.13%   |
| Synaptics UWP WBDI                                                         | 3         | 1.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.6%    |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.6%    |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.6%    |
| Validity Sensors VFS491                                                    | 2         | 1.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.06%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.06%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.06%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.53%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.53%   |
| Synaptics TouchPad                                                         | 1         | 0.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.53%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.53%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 55        | 63.22%  |
| Broadcom              | 21        | 24.14%  |
| Upek                  | 6         | 6.9%    |
| Lenovo                | 4         | 4.6%    |
| Advanced Card Systems | 1         | 1.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 63.22%  |
| Broadcom 5880                                                                | 10        | 11.49%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 6.9%    |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 6.9%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.45%   |
| Broadcom 58200                                                               | 2         | 2.3%    |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 740       | 64.8%   |
| 1     | 299       | 26.18%  |
| 2     | 80        | 7.01%   |
| 3     | 14        | 1.23%   |
| 4     | 5         | 0.44%   |
| 6     | 3         | 0.26%   |
| 10    | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 186       | 36.05%  |
| Graphics card            | 89        | 17.25%  |
| Chipcard                 | 78        | 15.12%  |
| Net/wireless             | 46        | 8.91%   |
| Multimedia controller    | 37        | 7.17%   |
| Communication controller | 15        | 2.91%   |
| Card reader              | 13        | 2.52%   |
| Camera                   | 11        | 2.13%   |
| Sound                    | 10        | 1.94%   |
| Bluetooth                | 8         | 1.55%   |
| Unassigned class         | 7         | 1.36%   |
| Net/ethernet             | 6         | 1.16%   |
| Storage                  | 5         | 0.97%   |
| Storage/raid             | 2         | 0.39%   |
| Wireless                 | 1         | 0.19%   |
| Network                  | 1         | 0.19%   |
| Modem                    | 1         | 0.19%   |

