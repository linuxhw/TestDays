ChimeraOS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ChimeraOS/Desktop/README.md) and [notebooks](/Dist/ChimeraOS/Notebook/README.md).

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

Total: 192

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [f39c1ef04f](https://linux-hardware.org/?probe=f39c1ef04f) | Jan 27, 2024 |
| Gateway       | IPISB-VR                    | Desktop     | [31d92a1fe6](https://linux-hardware.org/?probe=31d92a1fe6) | Jan 25, 2024 |
| Intel         | H61                         | Desktop     | [d3895696ad](https://linux-hardware.org/?probe=d3895696ad) | Jan 23, 2024 |
| ASUSTek       | AM1M-A                      | Desktop     | [6b24e4acaf](https://linux-hardware.org/?probe=6b24e4acaf) | Jan 22, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0a04043949](https://linux-hardware.org/?probe=0a04043949) | Jan 22, 2024 |
| Acer          | Aspire V3-772G              | Notebook    | [e9bc1c5d68](https://linux-hardware.org/?probe=e9bc1c5d68) | Jan 19, 2024 |
| Dell          | Latitude 7310               | Notebook    | [664667c69b](https://linux-hardware.org/?probe=664667c69b) | Jan 19, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [85f96ac567](https://linux-hardware.org/?probe=85f96ac567) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [3885b0cee8](https://linux-hardware.org/?probe=3885b0cee8) | Jan 12, 2024 |
| HP            | Pavilion 15                 | Notebook    | [dad46e573f](https://linux-hardware.org/?probe=dad46e573f) | Jan 07, 2024 |
| HP            | 885F A                      | Desktop     | [3050f4d975](https://linux-hardware.org/?probe=3050f4d975) | Jan 05, 2024 |
| HP            | 885F A                      | Desktop     | [7f484d8166](https://linux-hardware.org/?probe=7f484d8166) | Jan 05, 2024 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [36d3fe7f0a](https://linux-hardware.org/?probe=36d3fe7f0a) | Jan 03, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [544a799ce8](https://linux-hardware.org/?probe=544a799ce8) | Jan 02, 2024 |
| ASRock        | Z77 Professional            | Desktop     | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [d492f561d9](https://linux-hardware.org/?probe=d492f561d9) | Dec 31, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [dffaa09f84](https://linux-hardware.org/?probe=dffaa09f84) | Dec 29, 2023 |
| Sony          | SVS13A25PLB                 | Notebook    | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Valve         | Galileo                     | Notebook    | [355d2e1a38](https://linux-hardware.org/?probe=355d2e1a38) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0018284858](https://linux-hardware.org/?probe=0018284858) | Dec 17, 2023 |
| AYANEO        | 2                           | Tablet      | [78a21ff7fb](https://linux-hardware.org/?probe=78a21ff7fb) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f65efa02b6](https://linux-hardware.org/?probe=f65efa02b6) | Dec 16, 2023 |
| Shenzhen M... | F7BSD                       | Mini pc     | [10527fec61](https://linux-hardware.org/?probe=10527fec61) | Dec 16, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [69de9d26c7](https://linux-hardware.org/?probe=69de9d26c7) | Dec 15, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ea510ad39c](https://linux-hardware.org/?probe=ea510ad39c) | Dec 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [108ddf7f8e](https://linux-hardware.org/?probe=108ddf7f8e) | Dec 07, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [34d2104b8a](https://linux-hardware.org/?probe=34d2104b8a) | Dec 06, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [37ba613bd3](https://linux-hardware.org/?probe=37ba613bd3) | Dec 01, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [91cd726063](https://linux-hardware.org/?probe=91cd726063) | Nov 30, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [9672d50090](https://linux-hardware.org/?probe=9672d50090) | Nov 28, 2023 |
| Dell          | Latitude E5540              | Notebook    | [33e3a21810](https://linux-hardware.org/?probe=33e3a21810) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | Notebook    | [7cb8811992](https://linux-hardware.org/?probe=7cb8811992) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | Notebook    | [9d2fdb067c](https://linux-hardware.org/?probe=9d2fdb067c) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [606a157eb4](https://linux-hardware.org/?probe=606a157eb4) | Nov 24, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [f641738a49](https://linux-hardware.org/?probe=f641738a49) | Nov 23, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [4048fd2631](https://linux-hardware.org/?probe=4048fd2631) | Nov 22, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [742d987926](https://linux-hardware.org/?probe=742d987926) | Nov 21, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | Notebook    | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [d4fe05dcab](https://linux-hardware.org/?probe=d4fe05dcab) | Nov 20, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [abba035964](https://linux-hardware.org/?probe=abba035964) | Nov 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [84a46af7ee](https://linux-hardware.org/?probe=84a46af7ee) | Nov 19, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [694b0754fa](https://linux-hardware.org/?probe=694b0754fa) | Nov 18, 2023 |
| Dell          | 0DY62R A01                  | Desktop     | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| HP            | 8464                        | Desktop     | [2eae0556b2](https://linux-hardware.org/?probe=2eae0556b2) | Nov 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [7db396afcd](https://linux-hardware.org/?probe=7db396afcd) | Nov 16, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | Notebook    | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [10e26870d7](https://linux-hardware.org/?probe=10e26870d7) | Nov 13, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [aff29d99aa](https://linux-hardware.org/?probe=aff29d99aa) | Nov 12, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b15037e662](https://linux-hardware.org/?probe=b15037e662) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [6f0980a8f2](https://linux-hardware.org/?probe=6f0980a8f2) | Nov 07, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| Dell          | G15 5510                    | Notebook    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d7fb2de5a7](https://linux-hardware.org/?probe=d7fb2de5a7) | Oct 30, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| Dell          | Precision 7520              | Notebook    | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| GMKtec        | NucBox K4                   | Desktop     | [b0f8dc54f3](https://linux-hardware.org/?probe=b0f8dc54f3) | Oct 20, 2023 |
| AZW           | SER V1                      | Desktop     | [eca53f2271](https://linux-hardware.org/?probe=eca53f2271) | Oct 18, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [257a13e71a](https://linux-hardware.org/?probe=257a13e71a) | Oct 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [48f4eb15cc](https://linux-hardware.org/?probe=48f4eb15cc) | Oct 02, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| Alienware     | 17 R2                       | Notebook    | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | Notebook    | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Notebook    | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [27d1633bc3](https://linux-hardware.org/?probe=27d1633bc3) | Sep 11, 2023 |
| HP            | 18E7                        | Desktop     | [1b966d0110](https://linux-hardware.org/?probe=1b966d0110) | Sep 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [4934bfa1a8](https://linux-hardware.org/?probe=4934bfa1a8) | Sep 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Notebook    | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Gigabyte      | Z490 GAMING X AX y.y        | Desktop     | [94a6d62c4b](https://linux-hardware.org/?probe=94a6d62c4b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [5afb05e780](https://linux-hardware.org/?probe=5afb05e780) | Aug 27, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [64b9dbafae](https://linux-hardware.org/?probe=64b9dbafae) | Aug 16, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| Anbernic      | Win600                      | Notebook    | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [3f3195be63](https://linux-hardware.org/?probe=3f3195be63) | Aug 12, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [80c27f0ac1](https://linux-hardware.org/?probe=80c27f0ac1) | Aug 12, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b1b6854522](https://linux-hardware.org/?probe=b1b6854522) | Jul 29, 2023 |
| AZW           | SER V01                     | Mini pc     | [a3b4c40b6e](https://linux-hardware.org/?probe=a3b4c40b6e) | Jul 28, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [f8a02ab68e](https://linux-hardware.org/?probe=f8a02ab68e) | Jul 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8a41127a9](https://linux-hardware.org/?probe=c8a41127a9) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9186fec300](https://linux-hardware.org/?probe=9186fec300) | Jul 23, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [80e44d8594](https://linux-hardware.org/?probe=80e44d8594) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Acer          | Veriton X6610G              | Desktop     | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| HP            | 1791                        | Desktop     | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| AMI           | Unknown                     | Notebook    | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [d7b5162532](https://linux-hardware.org/?probe=d7b5162532) | Jun 09, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| AYANEO        | 2                           | Tablet      | [672b480b96](https://linux-hardware.org/?probe=672b480b96) | May 05, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| AYANEO        | 2                           | Tablet      | [4db5d91519](https://linux-hardware.org/?probe=4db5d91519) | Apr 21, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | Notebook    | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP            | 1998                        | Desktop     | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [d721c7ae17](https://linux-hardware.org/?probe=d721c7ae17) | Dec 27, 2022 |
| Lenovo        | ThinkCentre M70e 0832B1U    | Desktop     | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [9bec9e1625](https://linux-hardware.org/?probe=9bec9e1625) | Oct 01, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [501a588f11](https://linux-hardware.org/?probe=501a588f11) | Oct 01, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| ChimeraOS 44-1 | 61        | 38.85%  |
| ChimeraOS 43-1 | 25        | 15.92%  |
| ChimeraOS 42   | 18        | 11.46%  |
| ChimeraOS 39   | 15        | 9.55%   |
| ChimeraOS 41   | 11        | 7.01%   |
| ChimeraOS 43   | 8         | 5.1%    |
| ChimeraOS 38   | 6         | 3.82%   |
| ChimeraOS 44   | 5         | 3.18%   |
| ChimeraOS 37   | 4         | 2.55%   |
| ChimeraOS 45   | 2         | 1.27%   |
| ChimeraOS 35   | 1         | 0.64%   |
| ChimeraOS      | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 155       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.5.6-chos1-chimeraos-1 | 60        | 37.97%  |
| 6.3.9-chimeraos-1       | 32        | 20.25%  |
| 6.1.27-1-lts            | 18        | 11.39%  |
| 6.1.11-arch1-1          | 15        | 9.49%   |
| 6.1.21-1-lts            | 11        | 6.96%   |
| 6.1.1-arch1-1           | 6         | 3.8%    |
| 6.5.3-chos1-chimeraos-1 | 5         | 3.16%   |
| 6.0.8-arch1-1           | 4         | 2.53%   |
| 6.6.7-chos4-chimeraos-1 | 1         | 0.63%   |
| 6.6.6-arch1-1           | 1         | 0.63%   |
| 6.6.1-chos3-chimeraos-1 | 1         | 0.63%   |
| 6.4.9-0-generic         | 1         | 0.63%   |
| 6.3.3-arch1-1           | 1         | 0.63%   |
| 6.3.1-arch2-1           | 1         | 0.63%   |
| 5.19.6-arch1-1          | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.6   | 60        | 37.97%  |
| 6.3.9   | 32        | 20.25%  |
| 6.1.27  | 18        | 11.39%  |
| 6.1.11  | 15        | 9.49%   |
| 6.1.21  | 11        | 6.96%   |
| 6.1.1   | 6         | 3.8%    |
| 6.5.3   | 5         | 3.16%   |
| 6.0.8   | 4         | 2.53%   |
| 6.6.7   | 1         | 0.63%   |
| 6.6.6   | 1         | 0.63%   |
| 6.6.1   | 1         | 0.63%   |
| 6.4.9   | 1         | 0.63%   |
| 6.3.3   | 1         | 0.63%   |
| 6.3.1   | 1         | 0.63%   |
| 5.19.6  | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 65        | 41.67%  |
| 6.1     | 49        | 31.41%  |
| 6.3     | 33        | 21.15%  |
| 6.0     | 4         | 2.56%   |
| 6.6     | 3         | 1.92%   |
| 6.4     | 1         | 0.64%   |
| 5.19    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 155       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 154       | 99.35%  |
| steamos | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 149       | 96.13%  |
| X11     | 6         | 3.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 133       | 85.81%  |
| es_ES | 5         | 3.23%   |
| pt_BR | 4         | 2.58%   |
| fr_FR | 3         | 1.94%   |
| de_DE | 3         | 1.94%   |
| it_IT | 2         | 1.29%   |
| ja_JP | 1         | 0.65%   |
| fr_CA | 1         | 0.65%   |
| es_AR | 1         | 0.65%   |
| en_GB | 1         | 0.65%   |
| C     | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 155       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 154       | 99.35%  |
| Ext4  | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 34        | 21.94%  |
| Gigabyte Technology                  | 25        | 16.13%  |
| Dell                                 | 20        | 12.9%   |
| Hewlett-Packard                      | 12        | 7.74%   |
| Acer                                 | 10        | 6.45%   |
| MSI                                  | 8         | 5.16%   |
| Lenovo                               | 7         | 4.52%   |
| ASRock                               | 7         | 4.52%   |
| Shenzhen Meigao Electronic Equipment | 3         | 1.94%   |
| ONE-NETBOOK                          | 3         | 1.94%   |
| AYANEO                               | 3         | 1.94%   |
| Razer                                | 2         | 1.29%   |
| ONE-NETBOOK TECHNOLOGY               | 2         | 1.29%   |
| Intel                                | 2         | 1.29%   |
| AZW                                  | 2         | 1.29%   |
| ZOTAC                                | 1         | 0.65%   |
| Valve                                | 1         | 0.65%   |
| Sony                                 | 1         | 0.65%   |
| Notebook                             | 1         | 0.65%   |
| Microsoft                            | 1         | 0.65%   |
| Micro Electronics                    | 1         | 0.65%   |
| MACHINIST                            | 1         | 0.65%   |
| GPD                                  | 1         | 0.65%   |
| Google                               | 1         | 0.65%   |
| GMKtec                               | 1         | 0.65%   |
| Gateway                              | 1         | 0.65%   |
| Apple                                | 1         | 0.65%   |
| Anbernic                             | 1         | 0.65%   |
| AMI                                  | 1         | 0.65%   |
| Alienware                            | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Gigabyte B550I AORUS PRO AX                       | 4         | 2.58%   |
| Shenzhen Meigao Electronic Equipment Venus series | 3         | 1.94%   |
| Dell OptiPlex 3060                                | 3         | 1.94%   |
| AYANEO 2                                          | 3         | 1.94%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER                | 2         | 1.29%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                    | 2         | 1.29%   |
| HP EliteDesk 800 G1 SFF                           | 2         | 1.29%   |
| Gigabyte A520I AC                                 | 2         | 1.29%   |
| Dell OptiPlex 5055 Ryzen APU                      | 2         | 1.29%   |
| Dell OptiPlex 3070                                | 2         | 1.29%   |
| AZW SER                                           | 2         | 1.29%   |
| ASUS ROG STRIX B550-F GAMING                      | 2         | 1.29%   |
| Acer Aspire V3-772G                               | 2         | 1.29%   |
| Unknown                                           | 2         | 1.29%   |
| ZOTAC ZBOX-ECM73070C/53060C                       | 1         | 0.65%   |
| Valve Galileo                                     | 1         | 0.65%   |
| Sony SVS13A25PLB                                  | 1         | 0.65%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329       | 1         | 0.65%   |
| Razer Blade 14 - RZ09-0370                        | 1         | 0.65%   |
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P               | 1         | 0.65%   |
| Notebook P15SM-A/SM1-A                            | 1         | 0.65%   |
| MSI MS-7D78                                       | 1         | 0.65%   |
| MSI MS-7D73                                       | 1         | 0.65%   |
| MSI MS-7C91                                       | 1         | 0.65%   |
| MSI MS-7C56                                       | 1         | 0.65%   |
| MSI MS-7B86                                       | 1         | 0.65%   |
| MSI MS-7850                                       | 1         | 0.65%   |
| MSI GE75 Raider 10SF                              | 1         | 0.65%   |
| MSI CX62 6QD                                      | 1         | 0.65%   |
| Microsoft Surface Book                            | 1         | 0.65%   |
| Micro MG-VCP17I-3070                              | 1         | 0.65%   |
| MACHINIST X99-RS9 V2.0                            | 1         | 0.65%   |
| Lenovo Y50-70 20378                               | 1         | 0.65%   |
| Lenovo ThinkPad E15 20RD0011IX                    | 1         | 0.65%   |
| Lenovo ThinkCentre M70e 0832B1U                   | 1         | 0.65%   |
| Lenovo Legion Y540-15IRH 81SX                     | 1         | 0.65%   |
| Lenovo IdeaPad 700-15ISK 80RU                     | 1         | 0.65%   |
| Lenovo IdeaPad 320-15IKB 80YH                     | 1         | 0.65%   |
| Lenovo IdeaPad 3 15ADA05 81W1                     | 1         | 0.65%   |
| Intel H61                                         | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell OptiPlex                              | 11        | 7.1%    |
| ASUS ROG                                   | 9         | 5.81%   |
| Acer Aspire                                | 7         | 4.52%   |
| ASUS PRIME                                 | 5         | 3.23%   |
| Gigabyte B550I                             | 4         | 2.58%   |
| ASUS TUF                                   | 4         | 2.58%   |
| Shenzhen Meigao Electronic Equipment Venus | 3         | 1.94%   |
| ONE-NETBOOK ONEXPLAYER                     | 3         | 1.94%   |
| Lenovo IdeaPad                             | 3         | 1.94%   |
| HP EliteDesk                               | 3         | 1.94%   |
| Dell Latitude                              | 3         | 1.94%   |
| Dell Inspiron                              | 3         | 1.94%   |
| AYANEO 2                                   | 3         | 1.94%   |
| Razer Blade                                | 2         | 1.29%   |
| ONE-NETBOOK TECHNOLOGY ONE                 | 2         | 1.29%   |
| HP Victus                                  | 2         | 1.29%   |
| Gigabyte X570                              | 2         | 1.29%   |
| Gigabyte B450                              | 2         | 1.29%   |
| Gigabyte A520I                             | 2         | 1.29%   |
| Dell Precision                             | 2         | 1.29%   |
| AZW SER                                    | 2         | 1.29%   |
| ASUS ASUS                                  | 2         | 1.29%   |
| Acer Nitro                                 | 2         | 1.29%   |
| Unknown                                    | 2         | 1.29%   |
| ZOTAC ZBOX-ECM73070C                       | 1         | 0.65%   |
| Valve Galileo                              | 1         | 0.65%   |
| Sony SVS13A25PLB                           | 1         | 0.65%   |
| Notebook P15SM-A                           | 1         | 0.65%   |
| MSI MS-7D78                                | 1         | 0.65%   |
| MSI MS-7D73                                | 1         | 0.65%   |
| MSI MS-7C91                                | 1         | 0.65%   |
| MSI MS-7C56                                | 1         | 0.65%   |
| MSI MS-7B86                                | 1         | 0.65%   |
| MSI MS-7850                                | 1         | 0.65%   |
| MSI GE75                                   | 1         | 0.65%   |
| MSI CX62                                   | 1         | 0.65%   |
| Microsoft Surface                          | 1         | 0.65%   |
| Micro MG-VCP17I-3070                       | 1         | 0.65%   |
| MACHINIST X99-RS9                          | 1         | 0.65%   |
| Lenovo Y50-70                              | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 25        | 16.13%  |
| 2021 | 22        | 14.19%  |
| 2023 | 15        | 9.68%   |
| 2022 | 15        | 9.68%   |
| 2017 | 12        | 7.74%   |
| 2013 | 12        | 7.74%   |
| 2019 | 11        | 7.1%    |
| 2018 | 10        | 6.45%   |
| 2012 | 10        | 6.45%   |
| 2015 | 7         | 4.52%   |
| 2016 | 6         | 3.87%   |
| 2014 | 6         | 3.87%   |
| 2011 | 3         | 1.94%   |
| 2010 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 85        | 54.84%  |
| Notebook    | 53        | 34.19%  |
| Tablet      | 7         | 4.52%   |
| Mini pc     | 6         | 3.87%   |
| All in one  | 3         | 1.94%   |
| Convertible | 1         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 155       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 154       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 40        | 25.81%  |
| 32.01-64.0  | 38        | 24.52%  |
| 8.01-16.0   | 27        | 17.42%  |
| 4.01-8.0    | 23        | 14.84%  |
| 24.01-32.0  | 16        | 10.32%  |
| 3.01-4.0    | 7         | 4.52%   |
| 64.01-256.0 | 4         | 2.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 63        | 40.13%  |
| 1.01-2.0   | 40        | 25.48%  |
| 4.01-8.0   | 26        | 16.56%  |
| 3.01-4.0   | 26        | 16.56%  |
| 16.01-24.0 | 1         | 0.64%   |
| 8.01-16.0  | 1         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 48.41%  |
| 2      | 49        | 31.21%  |
| 3      | 19        | 12.1%   |
| 4      | 6         | 3.82%   |
| 5      | 3         | 1.91%   |
| 6      | 2         | 1.27%   |
| 8      | 1         | 0.64%   |
| 7      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 81.94%  |
| Yes       | 28        | 18.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 90.32%  |
| No        | 15        | 9.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 80%     |
| No        | 31        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 70.32%  |
| No        | 46        | 29.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 66        | 42.58%  |
| Germany      | 11        | 7.1%    |
| UK           | 10        | 6.45%   |
| Brazil       | 10        | 6.45%   |
| Vietnam      | 4         | 2.58%   |
| Spain        | 4         | 2.58%   |
| Russia       | 4         | 2.58%   |
| France       | 4         | 2.58%   |
| Canada       | 4         | 2.58%   |
| Australia    | 4         | 2.58%   |
| Italy        | 3         | 1.94%   |
| Turkey       | 2         | 1.29%   |
| Switzerland  | 2         | 1.29%   |
| Saudi Arabia | 2         | 1.29%   |
| Poland       | 2         | 1.29%   |
| Netherlands  | 2         | 1.29%   |
| Japan        | 2         | 1.29%   |
| Hungary      | 2         | 1.29%   |
| Romania      | 1         | 0.65%   |
| Peru         | 1         | 0.65%   |
| Norway       | 1         | 0.65%   |
| New Zealand  | 1         | 0.65%   |
| Malaysia     | 1         | 0.65%   |
| Macao        | 1         | 0.65%   |
| Iceland      | 1         | 0.65%   |
| Honduras     | 1         | 0.65%   |
| Finland      | 1         | 0.65%   |
| Estonia      | 1         | 0.65%   |
| Czechia      | 1         | 0.65%   |
| Costa Rica   | 1         | 0.65%   |
| Colombia     | 1         | 0.65%   |
| Chile        | 1         | 0.65%   |
| Belgium      | 1         | 0.65%   |
| Argentina    | 1         | 0.65%   |
| Algeria      | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Springfield              | 2         | 1.28%   |
| Sanford                  | 2         | 1.28%   |
| San Jose                 | 2         | 1.28%   |
| Salvador                 | 2         | 1.28%   |
| Melbourne                | 2         | 1.28%   |
| London                   | 2         | 1.28%   |
| Las Vegas                | 2         | 1.28%   |
| Istanbul                 | 2         | 1.28%   |
| Gelsenkirchen            | 2         | 1.28%   |
| Chattanooga              | 2         | 1.28%   |
| Yekaterinburg            | 1         | 0.64%   |
| Yaroslavl                | 1         | 0.64%   |
| Wroclaw                  | 1         | 0.64%   |
| Wiesbaden                | 1         | 0.64%   |
| Watsonville              | 1         | 0.64%   |
| Warsaw                   | 1         | 0.64%   |
| Vũng Tàu               | 1         | 0.64%   |
| Virginia Beach           | 1         | 0.64%   |
| Vila-seca                | 1         | 0.64%   |
| Valence                  | 1         | 0.64%   |
| Umeda                    | 1         | 0.64%   |
| Tulcea                   | 1         | 0.64%   |
| Toronto                  | 1         | 0.64%   |
| Tegucigalpa              | 1         | 0.64%   |
| Tampa                    | 1         | 0.64%   |
| Tallinn                  | 1         | 0.64%   |
| Sydney                   | 1         | 0.64%   |
| Sumaré                  | 1         | 0.64%   |
| Steyning                 | 1         | 0.64%   |
| St Louis                 | 1         | 0.64%   |
| Soldotna                 | 1         | 0.64%   |
| Shelbyville              | 1         | 0.64%   |
| Seattle                  | 1         | 0.64%   |
| Sao Paulo                | 1         | 0.64%   |
| Santiago                 | 1         | 0.64%   |
| Santa Cruz das Palmeiras | 1         | 0.64%   |
| San Leandro              | 1         | 0.64%   |
| Samara                   | 1         | 0.64%   |
| Saltillo                 | 1         | 0.64%   |
| Round Rock               | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 34        | 48     | 12.78%  |
| WDC                          | 29        | 38     | 10.9%   |
| Seagate                      | 29        | 34     | 10.9%   |
| SanDisk                      | 18        | 23     | 6.77%   |
| Kingston                     | 17        | 17     | 6.39%   |
| Micron/Crucial Technology    | 12        | 13     | 4.51%   |
| Unknown                      | 10        | 10     | 3.76%   |
| Micron Technology            | 10        | 12     | 3.76%   |
| Crucial                      | 10        | 12     | 3.76%   |
| Toshiba                      | 9         | 10     | 3.38%   |
| Phison Electronics           | 9         | 9      | 3.38%   |
| Intel                        | 9         | 11     | 3.38%   |
| SK hynix                     | 8         | 8      | 3.01%   |
| KIOXIA                       | 5         | 5      | 1.88%   |
| Realtek Semiconductor        | 4         | 4      | 1.5%    |
| Kingston Technology Company  | 4         | 4      | 1.5%    |
| Hitachi                      | 4         | 4      | 1.5%    |
| China                        | 4         | 4      | 1.5%    |
| ADATA Technology             | 4         | 5      | 1.5%    |
| Silicon Motion               | 3         | 3      | 1.13%   |
| Shenzhen Longsys Electronics | 3         | 3      | 1.13%   |
| HGST                         | 3         | 3      | 1.13%   |
| PNY                          | 2         | 2      | 0.75%   |
| Fanxiang                     | 2         | 2      | 0.75%   |
| A-DATA Technology            | 2         | 2      | 0.75%   |
| Unknown                      | 2         | 2      | 0.75%   |
| WDC PC S                     | 1         | 1      | 0.38%   |
| TO Exter                     | 1         | 1      | 0.38%   |
| Team                         | 1         | 1      | 0.38%   |
| SSSTC                        | 1         | 1      | 0.38%   |
| Realtek                      | 1         | 1      | 0.38%   |
| O2 Micro                     | 1         | 1      | 0.38%   |
| NT-1TB                       | 1         | 1      | 0.38%   |
| Netac                        | 1         | 1      | 0.38%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.38%   |
| Lenovo                       | 1         | 1      | 0.38%   |
| KingFast                     | 1         | 1      | 0.38%   |
| KingDian                     | 1         | 3      | 0.38%   |
| JMicron Technology           | 1         | 1      | 0.38%   |
| Hewlett-Packard              | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 10        | 3.52%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 10        | 3.52%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 5         | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB              | 4         | 1.41%   |
| Samsung SSD 860 EVO 1TB                                         | 3         | 1.06%   |
| Phison PS5013 E13 NVMe Controller 256GB                         | 3         | 1.06%   |
| Phison E12 NVMe Controller 1TB                                  | 3         | 1.06%   |
| Kingston SA400S37120G 120GB SSD                                 | 3         | 1.06%   |
| WDC WDBNCE5000PNC 500GB SSD                                     | 2         | 0.7%    |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 2         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB                                        | 2         | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB                                        | 2         | 0.7%    |
| Unknown SD/MMC/MS PRO 256GB                                     | 2         | 0.7%    |
| Unknown NVMe SSD Drive 2TB                                      | 2         | 0.7%    |
| Unknown MMC Card  64GB                                          | 2         | 0.7%    |
| Unknown MMC Card  512GB                                         | 2         | 0.7%    |
| Toshiba MQ04ABF100 1TB                                          | 2         | 0.7%    |
| SK hynix HFM512GD3JX016N 512GB                                  | 2         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB           | 2         | 0.7%    |
| Seagate ST500DM002-1BD142 500GB                                 | 2         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB                                  | 2         | 0.7%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB                            | 2         | 0.7%    |
| Samsung SSD 870 QVO 2TB                                         | 2         | 0.7%    |
| Samsung SSD 850 EVO 250GB                                       | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB             | 2         | 0.7%    |
| Micron/Crucial CT1000P5PSSD8 1TB                                | 2         | 0.7%    |
| Micron 1100 SATA 256GB SSD                                      | 2         | 0.7%    |
| KIOXIA KBG40ZNS256G NVMe 256GB                                  | 2         | 0.7%    |
| Kingston Company SNV2S1000G 1TB                                 | 2         | 0.7%    |
| Kingston SV300S37A120G 120GB SSD                                | 2         | 0.7%    |
| Kingston SNVS500G 500GB                                         | 2         | 0.7%    |
| Kingston SA400S37480G 480GB SSD                                 | 2         | 0.7%    |
| Intel SSDPEKNU512GZ 512GB                                       | 2         | 0.7%    |
| Intel SSD 660P Series 1024GB                                    | 2         | 0.7%    |
| HGST HTS541010A9E680 1TB                                        | 2         | 0.7%    |
| Crucial CT500MX500SSD1 500GB                                    | 2         | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                                     | 2         | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 2         | 0.7%    |
| Unknown                                                         | 2         | 0.7%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                                | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 32     | 39.44%  |
| WDC                 | 24        | 27     | 33.8%   |
| Toshiba             | 7         | 8      | 9.86%   |
| Hitachi             | 4         | 4      | 5.63%   |
| HGST                | 3         | 3      | 4.23%   |
| Unknown             | 2         | 2      | 2.82%   |
| TO Exter            | 1         | 1      | 1.41%   |
| Samsung Electronics | 1         | 1      | 1.41%   |
| Apple               | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 22     | 18.6%   |
| Kingston            | 12        | 12     | 13.95%  |
| Crucial             | 10        | 12     | 11.63%  |
| WDC                 | 8         | 11     | 9.3%    |
| SanDisk             | 8         | 10     | 9.3%    |
| Micron Technology   | 6         | 8      | 6.98%   |
| China               | 4         | 4      | 4.65%   |
| Intel               | 3         | 4      | 3.49%   |
| SK hynix            | 2         | 2      | 2.33%   |
| PNY                 | 2         | 2      | 2.33%   |
| Fanxiang            | 2         | 2      | 2.33%   |
| A-DATA Technology   | 2         | 2      | 2.33%   |
| Team                | 1         | 1      | 1.16%   |
| SSSTC               | 1         | 1      | 1.16%   |
| Seagate             | 1         | 1      | 1.16%   |
| NT-1TB              | 1         | 1      | 1.16%   |
| Netac               | 1         | 1      | 1.16%   |
| KingDian            | 1         | 3      | 1.16%   |
| Hewlett-Packard     | 1         | 1      | 1.16%   |
| GALAX               | 1         | 1      | 1.16%   |
| Corsair             | 1         | 1      | 1.16%   |
| ASMedia             | 1         | 1      | 1.16%   |
| AMD                 | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 96        | 116    | 41.03%  |
| SSD     | 69        | 104    | 29.49%  |
| HDD     | 58        | 79     | 24.79%  |
| MMC     | 6         | 6      | 2.56%   |
| Unknown | 5         | 5      | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 177    | 46.95%  |
| NVMe | 96        | 115    | 45.07%  |
| SAS  | 11        | 12     | 5.16%   |
| MMC  | 6         | 6      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 102    | 47.73%  |
| 0.51-1.0   | 44        | 51     | 33.33%  |
| 1.01-2.0   | 15        | 17     | 11.36%  |
| 4.01-10.0  | 4         | 4      | 3.03%   |
| 3.01-4.0   | 3         | 6      | 2.27%   |
| 10.01-20.0 | 2         | 2      | 1.52%   |
| 2.01-3.0   | 1         | 1      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 62        | 39.74%  |
| 1001-2000      | 46        | 29.49%  |
| 501-1000       | 23        | 14.74%  |
| 2001-3000      | 12        | 7.69%   |
| 251-500        | 11        | 7.05%   |
| 101-250        | 2         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 47        | 29.94%  |
| 51-100         | 24        | 15.29%  |
| 101-250        | 21        | 13.38%  |
| 501-1000       | 19        | 12.1%   |
| 251-500        | 15        | 9.55%   |
| 1001-2000      | 14        | 8.92%   |
| More than 3000 | 10        | 6.37%   |
| 2001-3000      | 6         | 3.82%   |
| 1-20           | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 156       | 310    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 83        | 34.87%  |
| AMD                          | 49        | 20.59%  |
| Samsung Electronics          | 20        | 8.4%    |
| Micron/Crucial Technology    | 12        | 5.04%   |
| Sandisk                      | 11        | 4.62%   |
| Phison Electronics           | 9         | 3.78%   |
| Kingston Technology Company  | 9         | 3.78%   |
| SK hynix                     | 6         | 2.52%   |
| KIOXIA                       | 5         | 2.1%    |
| Realtek Semiconductor        | 4         | 1.68%   |
| Micron Technology            | 4         | 1.68%   |
| ASMedia Technology           | 4         | 1.68%   |
| ADATA Technology             | 4         | 1.68%   |
| Silicon Motion               | 3         | 1.26%   |
| Shenzhen Longsys Electronics | 3         | 1.26%   |
| Toshiba America Info Systems | 2         | 0.84%   |
| Solidigm                     | 2         | 0.84%   |
| Biwin Storage Technology     | 2         | 0.84%   |
| VIA Technologies             | 1         | 0.42%   |
| O2 Micro                     | 1         | 0.42%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.42%   |
| Marvell Technology Group     | 1         | 0.42%   |
| Lenovo                       | 1         | 0.42%   |
| INNOGRIT                     | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 9.16%   |
| AMD 500 Series Chipset SATA Controller                                         | 17        | 6.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 4.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.67%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 2.67%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.91%   |
| AMD 600 Series Chipset SATA Controller                                         | 5         | 1.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.53%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.53%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 1.15%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.15%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 3         | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.15%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.15%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                           | 2         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.76%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                              | 2         | 0.76%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.76%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.76%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.76%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2         | 0.76%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 2         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.76%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 110       | 47.41%  |
| NVMe | 96        | 41.38%  |
| RAID | 20        | 8.62%   |
| IDE  | 6         | 2.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 88        | 56.77%  |
| AMD    | 67        | 43.23%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 6         | 3.85%   |
| AMD Ryzen 7 6800U with Radeon Graphics          | 5         | 3.21%   |
| AMD Ryzen 5 3600 6-Core Processor               | 5         | 3.21%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 4         | 2.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3         | 1.92%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 3         | 1.92%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics      | 3         | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.28%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2         | 1.28%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 1.28%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 2         | 1.28%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2         | 1.28%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2         | 1.28%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.28%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz         | 2         | 1.28%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 2         | 1.28%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 2         | 1.28%   |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2         | 1.28%   |
| AMD Ryzen 7 7700X 8-Core Processor              | 2         | 1.28%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 2         | 1.28%   |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 2         | 1.28%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 2         | 1.28%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.28%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 2         | 1.28%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1         | 0.64%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz             | 1         | 0.64%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz             | 1         | 0.64%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.64%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 1         | 0.64%   |
| Intel Core m3-8100Y CPU @ 1.10GHz               | 1         | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.64%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1         | 0.64%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 0.64%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.64%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 35        | 22.44%  |
| AMD Ryzen 7       | 25        | 16.03%  |
| Intel Core i7     | 23        | 14.74%  |
| AMD Ryzen 5       | 23        | 14.74%  |
| Other             | 14        | 8.97%   |
| AMD Ryzen 9       | 11        | 7.05%   |
| Intel Core i3     | 8         | 5.13%   |
| Intel Xeon        | 3         | 1.92%   |
| Intel Pentium     | 2         | 1.28%   |
| Intel Celeron     | 2         | 1.28%   |
| AMD Ryzen 5 PRO   | 2         | 1.28%   |
| AMD Athlon        | 2         | 1.28%   |
| Intel Core m3     | 1         | 0.64%   |
| Intel Core 2 Quad | 1         | 0.64%   |
| Intel Atom        | 1         | 0.64%   |
| AMD PRO A10       | 1         | 0.64%   |
| AMD FX            | 1         | 0.64%   |
| AMD A10           | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 56        | 35.9%   |
| 6      | 35        | 22.44%  |
| 8      | 34        | 21.79%  |
| 2      | 21        | 13.46%  |
| 16     | 3         | 1.92%   |
| 12     | 3         | 1.92%   |
| 10     | 2         | 1.28%   |
| 24     | 1         | 0.64%   |
| 14     | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 155       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 122       | 78.71%  |
| 1      | 33        | 21.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 155       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 29        | 18.71%  |
| Zen 3       | 23        | 14.84%  |
| KabyLake    | 22        | 14.19%  |
| Haswell     | 18        | 11.61%  |
| CometLake   | 12        | 7.74%   |
| Zen 2       | 8         | 5.16%   |
| Zen+        | 7         | 4.52%   |
| Skylake     | 7         | 4.52%   |
| IvyBridge   | 7         | 4.52%   |
| SandyBridge | 6         | 3.87%   |
| Zen         | 5         | 3.23%   |
| TigerLake   | 3         | 1.94%   |
| Piledriver  | 2         | 1.29%   |
| Silvermont  | 1         | 0.65%   |
| Penryn      | 1         | 0.65%   |
| Jaguar      | 1         | 0.65%   |
| Goldmont    | 1         | 0.65%   |
| Excavator   | 1         | 0.65%   |
| Broadwell   | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 73        | 36.87%  |
| Nvidia | 67        | 33.84%  |
| Intel  | 58        | 29.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 2.99%   |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 2.99%   |
| AMD Phoenix1                                                                | 6         | 2.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 2.49%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5         | 2.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 2.49%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 4         | 1.99%   |
| Intel HD Graphics 630                                                       | 4         | 1.99%   |
| Intel HD Graphics 530                                                       | 4         | 1.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.99%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4         | 1.99%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4         | 1.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 1.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4         | 1.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.49%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 1.49%   |
| AMD Raphael                                                                 | 3         | 1.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3         | 1.49%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2         | 1%      |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1%      |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 1%      |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2         | 1%      |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2         | 1%      |
| Intel UHD Graphics 620                                                      | 2         | 1%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1%      |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1%      |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1%      |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 1%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1%      |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 59        | 37.82%  |
| 1 x Nvidia     | 37        | 23.72%  |
| Intel + Nvidia | 25        | 16.03%  |
| 1 x Intel      | 22        | 14.1%   |
| Intel + AMD    | 5         | 3.21%   |
| AMD + Nvidia   | 5         | 3.21%   |
| 2 x AMD        | 2         | 1.28%   |
| Other          | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 104       | 67.1%   |
| Proprietary | 36        | 23.23%  |
| Unknown     | 15        | 9.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 98.06%  |
| 3.01-4.0   | 2         | 1.29%   |
| 8.01-16.0  | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 20        | 14.08%  |
| BOE                  | 12        | 8.45%   |
| Chimei Innolux       | 11        | 7.75%   |
| LG Display           | 10        | 7.04%   |
| AU Optronics         | 9         | 6.34%   |
| Goldstar             | 7         | 4.93%   |
| Dell                 | 5         | 3.52%   |
| Vizio                | 4         | 2.82%   |
| Unknown (XXX)        | 3         | 2.11%   |
| Sharp                | 3         | 2.11%   |
| Philips              | 3         | 2.11%   |
| MSI                  | 3         | 2.11%   |
| Insignia             | 3         | 2.11%   |
| Hewlett-Packard      | 3         | 2.11%   |
| BenQ                 | 3         | 2.11%   |
| ASUSTek Computer     | 3         | 2.11%   |
| Acer                 | 3         | 2.11%   |
| Toshiba              | 2         | 1.41%   |
| TMX                  | 2         | 1.41%   |
| Sony                 | 2         | 1.41%   |
| SANYO                | 2         | 1.41%   |
| Lenovo               | 2         | 1.41%   |
| DENON                | 2         | 1.41%   |
| AYANEO               | 2         | 1.41%   |
| Ancor Communications | 2         | 1.41%   |
| ViewSonic            | 1         | 0.7%    |
| VIE                  | 1         | 0.7%    |
| Valve                | 1         | 0.7%    |
| Sceptre Tech         | 1         | 0.7%    |
| RTK                  | 1         | 0.7%    |
| PXO                  | 1         | 0.7%    |
| PANDA                | 1         | 0.7%    |
| Panasonic            | 1         | 0.7%    |
| Onkyo                | 1         | 0.7%    |
| ITE                  | 1         | 0.7%    |
| HJW                  | 1         | 0.7%    |
| Hitachi              | 1         | 0.7%    |
| Gigabyte Technology  | 1         | 0.7%    |
| Gateway              | 1         | 0.7%    |
| GameMax              | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                   | 3         | 2.1%    |
| Unknown (XXX) Beyond TV XXX2851 2560x1440 1209x680mm 54.6-inch          | 2         | 1.4%    |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch       | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch        | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.4%    |
| AYANEO AYANEOWUXGA AYA0105 1200x1920                                    | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.4%    |
| Vizio OLED65-H1 VIZ1040 3840x2160 1428x803mm 64.5-inch                  | 1         | 0.7%    |
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                      | 1         | 0.7%    |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                      | 1         | 0.7%    |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                     | 1         | 0.7%    |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch                 | 1         | 0.7%    |
| VIE EZCOOL EZ24 VIE2380 1920x1080 598x336mm 27.0-inch                   | 1         | 0.7%    |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                     | 1         | 0.7%    |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.7%    |
| Toshiba TV TSB0206 1920x1080                                            | 1         | 0.7%    |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                       | 1         | 0.7%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 0.7%    |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                  | 1         | 0.7%    |
| Sony TV SNYEE01 1920x1080                                               | 1         | 0.7%    |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                          | 1         | 0.7%    |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch                 | 1         | 0.7%    |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 0.7%    |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                       | 1         | 0.7%    |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch          | 1         | 0.7%    |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                          | 1         | 0.7%    |
| SANYO LED MONITOR SAN3219 1360x768 304x228mm 15.0-inch                  | 1         | 0.7%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch    | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM01AC 1600x1200 312x234mm 15.4-inch    | 1         | 0.7%    |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch     | 1         | 0.7%    |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch       | 1         | 0.7%    |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1         | 0.7%    |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch       | 1         | 0.7%    |
| Samsung Electronics Odyssey G52A SAM7181 2560x1440 597x336mm 27.0-inch  | 1         | 0.7%    |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 69        | 49.64%  |
| 3840x2160 (4K)     | 20        | 14.39%  |
| 2560x1440 (QHD)    | 12        | 8.63%   |
| 1366x768 (WXGA)    | 10        | 7.19%   |
| 1200x1920          | 4         | 2.88%   |
| 3440x1440          | 3         | 2.16%   |
| 1600x900 (HD+)     | 3         | 2.16%   |
| 1600x2560          | 3         | 2.16%   |
| 800x1280           | 2         | 1.44%   |
| 2560x1080          | 2         | 1.44%   |
| 1920x540           | 2         | 1.44%   |
| 1680x1050 (WSXGA+) | 2         | 1.44%   |
| 3840x1600          | 1         | 0.72%   |
| 3840x1080          | 1         | 0.72%   |
| 1920x1200 (WUXGA)  | 1         | 0.72%   |
| 1600x1200          | 1         | 0.72%   |
| 1360x768           | 1         | 0.72%   |
| 1280x960           | 1         | 0.72%   |
| 1280x768           | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 19.01%  |
| 27      | 20        | 14.08%  |
| 17      | 8         | 5.63%   |
| Unknown | 8         | 5.63%   |
| 84      | 7         | 4.93%   |
| 31      | 7         | 4.93%   |
| 23      | 7         | 4.93%   |
| 24      | 5         | 3.52%   |
| 54      | 4         | 2.82%   |
| 34      | 4         | 2.82%   |
| 21      | 4         | 2.82%   |
| 14      | 4         | 2.82%   |
| 72      | 3         | 2.11%   |
| 13      | 3         | 2.11%   |
| 8       | 3         | 2.11%   |
| 49      | 2         | 1.41%   |
| 48      | 2         | 1.41%   |
| 40      | 2         | 1.41%   |
| 22      | 2         | 1.41%   |
| 20      | 2         | 1.41%   |
| 7       | 2         | 1.41%   |
| 74      | 1         | 0.7%    |
| 64      | 1         | 0.7%    |
| 57      | 1         | 0.7%    |
| 52      | 1         | 0.7%    |
| 47      | 1         | 0.7%    |
| 46      | 1         | 0.7%    |
| 38      | 1         | 0.7%    |
| 37      | 1         | 0.7%    |
| 35      | 1         | 0.7%    |
| 29      | 1         | 0.7%    |
| 28      | 1         | 0.7%    |
| 26      | 1         | 0.7%    |
| 18      | 1         | 0.7%    |
| 16      | 1         | 0.7%    |
| 12      | 1         | 0.7%    |
| 11      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 22.86%  |
| 501-600     | 29        | 20.71%  |
| 601-700     | 12        | 8.57%   |
| 1001-1500   | 12        | 8.57%   |
| 1501-2000   | 10        | 7.14%   |
| 401-500     | 9         | 6.43%   |
| 351-400     | 9         | 6.43%   |
| Unknown     | 8         | 5.71%   |
| 801-900     | 5         | 3.57%   |
| 701-800     | 5         | 3.57%   |
| 201-300     | 4         | 2.86%   |
| 101-200     | 4         | 2.86%   |
| 1-100       | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 106       | 79.7%   |
| 0.62  | 9         | 6.77%   |
| 21/9  | 6         | 4.51%   |
| 16/10 | 6         | 4.51%   |
| 4/3   | 2         | 1.5%    |
| 32/9  | 2         | 1.5%    |
| 1.96  | 1         | 0.75%   |
| 0.56  | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 19.57%  |
| 301-350        | 22        | 15.94%  |
| More than 1000 | 18        | 13.04%  |
| 201-250        | 16        | 11.59%  |
| 351-500        | 11        | 7.97%   |
| 501-1000       | 9         | 6.52%   |
| 121-130        | 8         | 5.8%    |
| Unknown        | 8         | 5.8%    |
| 81-90          | 5         | 3.62%   |
| 1-40           | 5         | 3.62%   |
| 71-80          | 3         | 2.17%   |
| 151-200        | 3         | 2.17%   |
| 51-60          | 1         | 0.72%   |
| 141-150        | 1         | 0.72%   |
| 111-120        | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 53        | 38.41%  |
| 121-160       | 34        | 24.64%  |
| 101-120       | 18        | 13.04%  |
| 1-50          | 11        | 7.97%   |
| 161-240       | 9         | 6.52%   |
| Unknown       | 8         | 5.8%    |
| More than 240 | 5         | 3.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 119       | 76.28%  |
| 0     | 19        | 12.18%  |
| 2     | 16        | 10.26%  |
| 3     | 2         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 101       | 39.3%   |
| Intel                           | 79        | 30.74%  |
| Qualcomm Atheros                | 22        | 8.56%   |
| MediaTek                        | 16        | 6.23%   |
| Broadcom                        | 7         | 2.72%   |
| TP-Link                         | 6         | 2.33%   |
| Microsoft                       | 6         | 2.33%   |
| Broadcom Limited                | 3         | 1.17%   |
| Samsung Electronics             | 2         | 0.78%   |
| Ralink Technology               | 2         | 0.78%   |
| Ralink                          | 2         | 0.78%   |
| Qualcomm Atheros Communications | 2         | 0.78%   |
| Qualcomm                        | 2         | 0.78%   |
| Marvell Technology Group        | 2         | 0.78%   |
| ASIX Electronics                | 2         | 0.78%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.39%   |
| Edimax Technology               | 1         | 0.39%   |
| Aquantia                        | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 64        | 22.07%  |
| Realtek RTL8125 2.5GbE Controller                                      | 22        | 7.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 14        | 4.83%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 2.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 7         | 2.41%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 2.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 2.07%   |
| Intel Ethernet Controller I225-V                                       | 6         | 2.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6         | 2.07%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5         | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.72%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 5         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.72%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.38%   |
| Intel Wireless 3165                                                    | 4         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 1.38%   |
| TP-Link Archer T4U ver.3                                               | 3         | 1.03%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 3         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.03%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.03%   |
| Intel Wireless 7265                                                    | 3         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 0.69%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 0.69%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2         | 0.69%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 43.38%  |
| Qualcomm Atheros                | 18        | 13.24%  |
| Realtek Semiconductor           | 17        | 12.5%   |
| MediaTek                        | 16        | 11.76%  |
| TP-Link                         | 6         | 4.41%   |
| Microsoft                       | 6         | 4.41%   |
| Broadcom                        | 4         | 2.94%   |
| Ralink Technology               | 2         | 1.47%   |
| Ralink                          | 2         | 1.47%   |
| Qualcomm Atheros Communications | 2         | 1.47%   |
| Qualcomm                        | 1         | 0.74%   |
| Marvell Technology Group        | 1         | 0.74%   |
| Edimax Technology               | 1         | 0.74%   |
| Broadcom Limited                | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 14        | 9.93%   |
| Intel Wi-Fi 6 AX200                                           | 8         | 5.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 7         | 4.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 6         | 4.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 6         | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5         | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.55%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 5         | 3.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5         | 3.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 4         | 2.84%   |
| Intel Wireless 3165                                           | 4         | 2.84%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 2.84%   |
| TP-Link Archer T4U ver.3                                      | 3         | 2.13%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 3         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 2.13%   |
| Intel Wireless 8265 / 8275                                    | 3         | 2.13%   |
| Intel Wireless 7265                                           | 3         | 2.13%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.42%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 0.71%   |
| TP-Link 802.11ac NIC                                          | 1         | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.71%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.71%   |
| Realtek RTL8187 Wireless Adapter                              | 1         | 0.71%   |
| Realtek 802.11ac NIC                                          | 1         | 0.71%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1         | 0.71%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 0.71%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 95        | 65.07%  |
| Intel                    | 33        | 22.6%   |
| Qualcomm Atheros         | 5         | 3.42%   |
| Broadcom                 | 4         | 2.74%   |
| Samsung Electronics      | 2         | 1.37%   |
| Broadcom Limited         | 2         | 1.37%   |
| ASIX Electronics         | 2         | 1.37%   |
| Qualcomm                 | 1         | 0.68%   |
| Marvell Technology Group | 1         | 0.68%   |
| Aquantia                 | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 64        | 43.24%  |
| Realtek RTL8125 2.5GbE Controller                                               | 22        | 14.86%  |
| Intel I211 Gigabit Network Connection                                           | 7         | 4.73%   |
| Intel Ethernet Controller I225-V                                                | 6         | 4.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 5         | 3.38%   |
| Intel Ethernet Connection I217-LM                                               | 5         | 3.38%   |
| Intel Ethernet Connection (2) I219-V                                            | 4         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2         | 1.35%   |
| Realtek PCIe GbE Family Controller                                              | 2         | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2         | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                                           | 2         | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 2         | 1.35%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                | 2         | 1.35%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 2         | 1.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                     | 1         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 1         | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 1         | 0.68%   |
| Realtek Killer E2600 GbE Controller                                             | 1         | 0.68%   |
| Qualcomm MDM9207-MTP _SN:F0565CAE                                               | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                       | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 1         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 1         | 0.68%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                         | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                               | 1         | 0.68%   |
| Intel Ethernet Connection I217-V                                                | 1         | 0.68%   |
| Intel Ethernet Connection (14) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (12) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-V                                           | 1         | 0.68%   |
| Intel Ethernet Connection (11) I219-LM                                          | 1         | 0.68%   |
| Intel 82579V Gigabit Network Connection                                         | 1         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 1         | 0.68%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                 | 1         | 0.68%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 139       | 52.85%  |
| WiFi     | 123       | 46.77%  |
| Unknown  | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 59.75%  |
| Ethernet | 64        | 40.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 88        | 56.77%  |
| 1     | 62        | 40%     |
| 3     | 5         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 97        | 62.18%  |
| Yes  | 59        | 37.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 50.45%  |
| Cambridge Silicon Radio         | 10        | 9.01%   |
| MediaTek                        | 9         | 8.11%   |
| Realtek Semiconductor           | 7         | 6.31%   |
| Qualcomm Atheros Communications | 7         | 6.31%   |
| IMC Networks                    | 7         | 6.31%   |
| Lite-On Technology              | 5         | 4.5%    |
| Foxconn / Hon Hai               | 3         | 2.7%    |
| ASUSTek Computer                | 2         | 1.8%    |
| Apple                           | 2         | 1.8%    |
| TP-Link                         | 1         | 0.9%    |
| Realtek                         | 1         | 0.9%    |
| Actions                         | 1         | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX210 Bluetooth                               | 14        | 12.5%   |
| Intel Bluetooth wireless interface                  | 11        | 9.82%   |
| Intel AX201 Bluetooth                               | 11        | 9.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 8.93%   |
| MediaTek Wireless_Device                            | 9         | 8.04%   |
| Realtek Bluetooth Radio                             | 7         | 6.25%   |
| Intel AX200 Bluetooth                               | 7         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 5.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.57%   |
| IMC Networks Wireless_Device                        | 3         | 2.68%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.79%   |
| Lite-On Bluetooth Device                            | 2         | 1.79%   |
| Intel Bluetooth Device                              | 2         | 1.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.79%   |
| TP-Link UB500 Adapter                               | 1         | 0.89%   |
| Realtek Bluetooth Radio                             | 1         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.89%   |
| Lite-On Wireless_Device                             | 1         | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.89%   |
| IMC Networks Bluetooth Device                       | 1         | 0.89%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.89%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.89%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.89%   |
| Apple Bluetooth Host Controller                     | 1         | 0.89%   |
| Actions general adapter                             | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| AMD                      | 86        | 33.08%  |
| Intel                    | 84        | 32.31%  |
| Nvidia                   | 53        | 20.38%  |
| Sony                     | 5         | 1.92%   |
| Logitech                 | 5         | 1.92%   |
| Kingston Technology      | 5         | 1.92%   |
| SteelSeries ApS          | 2         | 0.77%   |
| Razer USA                | 2         | 0.77%   |
| Hewlett-Packard          | 2         | 0.77%   |
| C-Media Electronics      | 2         | 0.77%   |
| ASUSTek Computer         | 2         | 0.77%   |
| Astro Gaming             | 2         | 0.77%   |
| Texas Instruments        | 1         | 0.38%   |
| Realtek Semiconductor    | 1         | 0.38%   |
| Micro Star International | 1         | 0.38%   |
| JMTek                    | 1         | 0.38%   |
| Google                   | 1         | 0.38%   |
| Generalplus Technology   | 1         | 0.38%   |
| Focusrite-Novation       | 1         | 0.38%   |
| Creative Labs            | 1         | 0.38%   |
| Comtrue                  | 1         | 0.38%   |
| Blue Microphones         | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 32        | 9.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 23        | 6.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 4.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 4.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14        | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 3.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 2.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 2.13%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.82%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 6         | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.52%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.52%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.52%   |
| Nvidia Audio device                                                        | 4         | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.91%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3         | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.91%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.91%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 2         | 0.61%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2         | 0.61%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.61%   |
| Razer USA Razer Seiren Mini                                                | 2         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 12        | 23.08%  |
| Microdia                      | 9         | 17.31%  |
| Sunplus Innovation Technology | 6         | 11.54%  |
| IMC Networks                  | 5         | 9.62%   |
| Logitech                      | 4         | 7.69%   |
| Realtek Semiconductor         | 3         | 5.77%   |
| Quanta                        | 2         | 3.85%   |
| Bison Electronics             | 2         | 3.85%   |
| Apple                         | 2         | 3.85%   |
| YT-221117-J                   | 1         | 1.92%   |
| Syntek                        | 1         | 1.92%   |
| Suyin                         | 1         | 1.92%   |
| Sonix Technology              | 1         | 1.92%   |
| Silicon Motion                | 1         | 1.92%   |
| Samsung Electronics           | 1         | 1.92%   |
| Acer                          | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Sunplus HD WebCam                       | 3         | 5.77%   |
| IMC Networks Integrated Camera          | 3         | 5.77%   |
| Microdia Integrated_Webcam_FHD          | 2         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam       | 2         | 3.85%   |
| Chicony Integrated Camera               | 2         | 3.85%   |
| Chicony HD WebCam                       | 2         | 3.85%   |
| Chicony HD User Facing                  | 2         | 3.85%   |
| Bison Lenovo EasyCamera                 | 2         | 3.85%   |
| YT-221117-J USB2.0 Camera               | 1         | 1.92%   |
| Syntek USB2.0 Camera                    | 1         | 1.92%   |
| Suyin HP Truevision HD                  | 1         | 1.92%   |
| Sunplus Integrated_Webcam_HD            | 1         | 1.92%   |
| Sunplus HD 720P webcam                  | 1         | 1.92%   |
| Sunplus ASUS Webcam                     | 1         | 1.92%   |
| Sonix USB2.0 HD UVC WebCam              | 1         | 1.92%   |
| Silicon Motion 300k Pixel Camera        | 1         | 1.92%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD            | 1         | 1.92%   |
| Realtek Integrated_Webcam_FHD           | 1         | 1.92%   |
| Realtek Integrated Webcam               | 1         | 1.92%   |
| Quanta HP HD Camera                     | 1         | 1.92%   |
| Quanta HD User Facing                   | 1         | 1.92%   |
| Microdia Webcam Vitade AF               | 1         | 1.92%   |
| Microdia USB Camera                     | 1         | 1.92%   |
| Microdia USB 2.0 Camera                 | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1         | 1.92%   |
| Microdia Integrated_Webcam_HD           | 1         | 1.92%   |
| Microdia HP Webcam                      | 1         | 1.92%   |
| Microdia Camera                         | 1         | 1.92%   |
| Logitech Webcam C930e                   | 1         | 1.92%   |
| Logitech Webcam C270                    | 1         | 1.92%   |
| Logitech Webcam C200                    | 1         | 1.92%   |
| Logitech Logi Webcam C920e              | 1         | 1.92%   |
| Chicony USB2.0 FHD Camera               | 1         | 1.92%   |
| Chicony USB2.0 0.3M UVC WebCam          | 1         | 1.92%   |
| Chicony HP Wide Vision HD Camera        | 1         | 1.92%   |
| Chicony HP Truevision HD                | 1         | 1.92%   |
| Chicony HP HD Webcam [Fixed]            | 1         | 1.92%   |
| Chicony EasyCamera                      | 1         | 1.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |
| AuthenTec                  | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 25%     |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model          | Computers | Percent |
|----------------|-----------|---------|
| Broadcom 5880  | 1         | 50%     |
| Broadcom 58200 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 92        | 59.35%  |
| 1     | 58        | 37.42%  |
| 2     | 5         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 34        | 50%     |
| Network               | 9         | 13.24%  |
| Net/ethernet          | 7         | 10.29%  |
| Multimedia controller | 7         | 10.29%  |
| Net/wireless          | 4         | 5.88%   |
| Fingerprint reader    | 4         | 5.88%   |
| Chipcard              | 2         | 2.94%   |
| Storage/nvme          | 1         | 1.47%   |

