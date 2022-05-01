Mageia - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Mageia/Desktop/README.md) and [notebooks](/Dist/Mageia/Notebook/README.md).

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

Total: 179

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Microsoft | Surface Pro 4               | Tablet      | [4e74006288](https://linux-hardware.org/?probe=4e74006288) | Apr 21, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | Notebook    | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte  | H81M-S2H                    | Desktop     | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| MSI       | Z590-A PRO                  | Desktop     | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Toshiba   | dynabook R73/A              | Notebook    | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Gigabyte  | GA-78LMT-USB3 SEx           | Desktop     | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Gigabyte  | G31M-S2C                    | Desktop     | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| Gigabyte  | H81M-S2H                    | Desktop     | [eac8a02717](https://linux-hardware.org/?probe=eac8a02717) | Mar 15, 2022 |
| Gigabyte  | X570 AORUS ELITE WIFI       | Desktop     | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| MSI       | Z590-A PRO                  | Desktop     | [5f37c84d61](https://linux-hardware.org/?probe=5f37c84d61) | Mar 06, 2022 |
| Gigabyte  | G31M-S2C                    | Desktop     | [d419223147](https://linux-hardware.org/?probe=d419223147) | Mar 06, 2022 |
| Gigabyte  | X570 AORUS ELITE WIFI       | Desktop     | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASRock    | M3A UCC                     | Desktop     | [eaa75fb3f4](https://linux-hardware.org/?probe=eaa75fb3f4) | Feb 20, 2022 |
| ASRock    | M3A UCC                     | Desktop     | [ce306a4c86](https://linux-hardware.org/?probe=ce306a4c86) | Feb 20, 2022 |
| MSI       | B250M BAZOOKA               | Desktop     | [4a8f0501a2](https://linux-hardware.org/?probe=4a8f0501a2) | Feb 11, 2022 |
| ASRock    | G41M-VS3                    | Desktop     | [825356bf6c](https://linux-hardware.org/?probe=825356bf6c) | Feb 02, 2022 |
| HP        | 1589                        | Desktop     | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Gigabyte  | H81M-DS2                    | Desktop     | [c0328d5402](https://linux-hardware.org/?probe=c0328d5402) | Jan 27, 2022 |
| Lenovo    | ThinkCentre M58e 7491B1G    | Desktop     | [568741947f](https://linux-hardware.org/?probe=568741947f) | Jan 12, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [d9856d52b0](https://linux-hardware.org/?probe=d9856d52b0) | Jan 11, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [8b8a13f3b4](https://linux-hardware.org/?probe=8b8a13f3b4) | Jan 11, 2022 |
| Gigabyte  | B450 AORUS M                | Desktop     | [0fa4a81a77](https://linux-hardware.org/?probe=0fa4a81a77) | Jan 09, 2022 |
| Lenovo    | ThinkCentre M58e 7491B1G    | Desktop     | [a77218c72c](https://linux-hardware.org/?probe=a77218c72c) | Jan 09, 2022 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [a1a7854f7a](https://linux-hardware.org/?probe=a1a7854f7a) | Jan 04, 2022 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [c44573411d](https://linux-hardware.org/?probe=c44573411d) | Dec 27, 2021 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [ceefdd4eac](https://linux-hardware.org/?probe=ceefdd4eac) | Dec 06, 2021 |
| Dell      | Latitude E5570              | Notebook    | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell      | Latitude E5570              | Notebook    | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell      | Precision 5530              | Notebook    | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Dell      | 0TP412                      | Desktop     | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [665331e075](https://linux-hardware.org/?probe=665331e075) | Nov 22, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [e18761a6b2](https://linux-hardware.org/?probe=e18761a6b2) | Sep 28, 2021 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Apple     | Mac-F42386C8 PVT            | All in one  | [3235b7d95a](https://linux-hardware.org/?probe=3235b7d95a) | Sep 24, 2021 |
| Dell      | 0TP412                      | Desktop     | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI       | MAG B460M MORTAR            | Desktop     | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [46740d8f33](https://linux-hardware.org/?probe=46740d8f33) | Aug 22, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [31e9013879](https://linux-hardware.org/?probe=31e9013879) | Aug 18, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [809f094941](https://linux-hardware.org/?probe=809f094941) | Aug 17, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | Desktop     | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Lenovo    | ThinkPad T61 6468AE2        | Notebook    | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| Dell      | 0TP412                      | Desktop     | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| ASUSTek   | PRIME X399-A                | Desktop     | [a2b6af1a6a](https://linux-hardware.org/?probe=a2b6af1a6a) | Jul 14, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Gigabyte  | Z68XP-UD3P                  | Desktop     | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [7619cf7632](https://linux-hardware.org/?probe=7619cf7632) | May 31, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [70f882a983](https://linux-hardware.org/?probe=70f882a983) | May 31, 2021 |
| Notebook  | NL40_50GU                   | Notebook    | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion    | DEFENDER P10                | Notebook    | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion    | DEFENDER P10                | Notebook    | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [1be802a26e](https://linux-hardware.org/?probe=1be802a26e) | Apr 18, 2021 |
| ECS       | IC780M-A2                   | Desktop     | [e3cbd0879b](https://linux-hardware.org/?probe=e3cbd0879b) | Apr 17, 2021 |
| ASUSTek   | Z170-P                      | Desktop     | [1ebcf0ea2c](https://linux-hardware.org/?probe=1ebcf0ea2c) | Apr 16, 2021 |
| ASUSTek   | Z170-P                      | Desktop     | [a95896e05e](https://linux-hardware.org/?probe=a95896e05e) | Apr 16, 2021 |
| Medion    | Z370H4-EM                   | Desktop     | [57435ad8fb](https://linux-hardware.org/?probe=57435ad8fb) | Apr 16, 2021 |
| ASUSTek   | SABERTOOTH P67              | Desktop     | [6d81c9d615](https://linux-hardware.org/?probe=6d81c9d615) | Apr 16, 2021 |
| Fujitsu   | LIFEBOOK E752               | Notebook    | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Gigabyte  | H61M-S2PV                   | Desktop     | [dce1091d81](https://linux-hardware.org/?probe=dce1091d81) | Apr 15, 2021 |
| Medion    | Z370H4-EM                   | Desktop     | [b88834e15d](https://linux-hardware.org/?probe=b88834e15d) | Apr 15, 2021 |
| Lenovo    | ThinkPad T430 2342A19       | Notebook    | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| HP        | 212B                        | Desktop     | [697e2f24f0](https://linux-hardware.org/?probe=697e2f24f0) | Apr 03, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [7da0db2567](https://linux-hardware.org/?probe=7da0db2567) | Apr 03, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| Intel     | STL2-bd A28808-302          | Desktop     | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP        | 212B                        | Desktop     | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| ASUSTek   | X556URK                     | Notebook    | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [a8e9bcdc07](https://linux-hardware.org/?probe=a8e9bcdc07) | Feb 23, 2021 |
| ASRock    | M3A UCC                     | Desktop     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP        | 339A                        | Desktop     | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| HP        | 339A                        | Desktop     | [39d23c03ca](https://linux-hardware.org/?probe=39d23c03ca) | Feb 13, 2021 |
| Dell      | Latitude E6530              | Notebook    | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [adabf5b11e](https://linux-hardware.org/?probe=adabf5b11e) | Jan 31, 2021 |
| Dell      | Inspiron 5480               | Notebook    | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [6e7c6b5d77](https://linux-hardware.org/?probe=6e7c6b5d77) | Jan 16, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [0b7e0d2152](https://linux-hardware.org/?probe=0b7e0d2152) | Jan 15, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [567ce23c0d](https://linux-hardware.org/?probe=567ce23c0d) | Jan 13, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [513ff22c6f](https://linux-hardware.org/?probe=513ff22c6f) | Jan 13, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [9136594961](https://linux-hardware.org/?probe=9136594961) | Jan 02, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [ea55725f98](https://linux-hardware.org/?probe=ea55725f98) | Dec 30, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek   | Z87-DELUXE                  | Desktop     | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek   | X751LN                      | Notebook    | [8399780a87](https://linux-hardware.org/?probe=8399780a87) | Dec 27, 2020 |
| ASUSTek   | X751LN                      | Notebook    | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| HP        | 339A                        | Desktop     | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [932603ce99](https://linux-hardware.org/?probe=932603ce99) | Dec 25, 2020 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte  | F2A88XM-DS2                 | Desktop     | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [3f948a0756](https://linux-hardware.org/?probe=3f948a0756) | Dec 03, 2020 |
| HP        | Spectre 13 Ultrabook        | Notebook    | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Gigabyte  | GA-78LMT-USB3 R2            | Desktop     | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [8f031786c5](https://linux-hardware.org/?probe=8f031786c5) | Nov 16, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [1bdc158142](https://linux-hardware.org/?probe=1bdc158142) | Nov 16, 2020 |
| ASUSTek   | PRIME B360-PLUS             | Desktop     | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP        | ProBook 445 G7              | Notebook    | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Acer      | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [a854973bf5](https://linux-hardware.org/?probe=a854973bf5) | Oct 25, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC     | Unknown                     | Desktop     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [1a7d01552e](https://linux-hardware.org/?probe=1a7d01552e) | Oct 04, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [8fa69c952c](https://linux-hardware.org/?probe=8fa69c952c) | Sep 15, 2020 |
| HP        | Unknown                     | Notebook    | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer      | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP        | Pavilion dv6                | Notebook    | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f6c7b24ad6](https://linux-hardware.org/?probe=f6c7b24ad6) | Aug 31, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [7fd8c75c95](https://linux-hardware.org/?probe=7fd8c75c95) | Aug 19, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [14955a6413](https://linux-hardware.org/?probe=14955a6413) | Aug 19, 2020 |
| Lenovo    | G480 20149                  | Notebook    | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock    | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP        | 339A                        | Desktop     | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP        | 339A                        | Desktop     | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [db83d53491](https://linux-hardware.org/?probe=db83d53491) | May 07, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| MSI       | B360M MORTAR                | Desktop     | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek   | H170M-PLUS                  | Desktop     | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke     | V1 Plus                     | Desktop     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [c61a5bbb12](https://linux-hardware.org/?probe=c61a5bbb12) | Mar 05, 2020 |
| ASRock    | X470 Taichi                 | Desktop     | [5125778e67](https://linux-hardware.org/?probe=5125778e67) | Mar 02, 2020 |
| Gigabyte  | B85M-D3H                    | Desktop     | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [71a967abf8](https://linux-hardware.org/?probe=71a967abf8) | Feb 22, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [52c3f45c8f](https://linux-hardware.org/?probe=52c3f45c8f) | Feb 22, 2020 |
| ASUSTek   | H170M-PLUS                  | Desktop     | [0ae790ac85](https://linux-hardware.org/?probe=0ae790ac85) | Feb 01, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [506294e8e9](https://linux-hardware.org/?probe=506294e8e9) | Jan 13, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [16e8d236b4](https://linux-hardware.org/?probe=16e8d236b4) | Jan 12, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [7df7d9c296](https://linux-hardware.org/?probe=7df7d9c296) | Dec 20, 2019 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [0c42dfc62c](https://linux-hardware.org/?probe=0c42dfc62c) | Dec 08, 2019 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [2ef79b672c](https://linux-hardware.org/?probe=2ef79b672c) | Nov 15, 2019 |
| ASUSTek   | A55BM-K                     | Desktop     | [d58dbcdd06](https://linux-hardware.org/?probe=d58dbcdd06) | Nov 08, 2019 |
| MSI       | Z97-G43                     | Desktop     | [87e4cd50ce](https://linux-hardware.org/?probe=87e4cd50ce) | Apr 26, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [14a8808d2b](https://linux-hardware.org/?probe=14a8808d2b) | Apr 26, 2019 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [28ea4213cb](https://linux-hardware.org/?probe=28ea4213cb) | Feb 25, 2019 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [b9c55f2790](https://linux-hardware.org/?probe=b9c55f2790) | Feb 25, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [7b6ec43d58](https://linux-hardware.org/?probe=7b6ec43d58) | Jan 08, 2019 |
| ASRock    | X470 Taichi                 | Desktop     | [117cb09799](https://linux-hardware.org/?probe=117cb09799) | Dec 31, 2018 |
| Gigabyte  | Z68X-UD3H-B3                | Desktop     | [0a61436f40](https://linux-hardware.org/?probe=0a61436f40) | Feb 15, 2018 |
| ASUSTek   | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |
| ASUSTek   | M4A78 PLUS                  | Desktop     | [ed9d8a148d](https://linux-hardware.org/?probe=ed9d8a148d) | Mar 06, 2016 |
| Lenovo    | G570 20079                  | Notebook    | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Mageia 8 | 48        | 52.75%  |
| Mageia 7 | 33        | 36.26%  |
| Mageia 9 | 5         | 5.49%   |
| Mageia 6 | 4         | 4.4%    |
| Mageia 5 | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Mageia | 79        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 14        | 10.85%  |
| 5.10.27-desktop-1.mga8 | 8         | 6.2%    |
| 5.7.19-desktop-1.mga7  | 7         | 5.43%   |
| 5.15.32-desktop-1.mga8 | 5         | 3.88%   |
| 5.6.14-desktop-2.mga7  | 4         | 3.1%    |
| 5.5.4-desktop-1.mga7   | 4         | 3.1%    |
| 5.10.25-desktop-1.mga8 | 4         | 3.1%    |
| 5.5.9-desktop-1.mga7   | 3         | 2.33%   |
| 5.15.23-desktop-1.mga8 | 3         | 2.33%   |
| 5.10.12-desktop-1.mga7 | 3         | 2.33%   |
| 5.7.14-desktop-1.mga7  | 2         | 1.55%   |
| 5.6.6-desktop-1.mga7   | 2         | 1.55%   |
| 5.3.7-desktop-4.mga7   | 2         | 1.55%   |
| 5.15.4-desktop-1.mga8  | 2         | 1.55%   |
| 5.15.16-desktop-1.mga8 | 2         | 1.55%   |
| 5.15.11-desktop-3.mga8 | 2         | 1.55%   |
| 5.10.60-desktop-2.mga8 | 2         | 1.55%   |
| 5.10.56-desktop-1.mga8 | 2         | 1.55%   |
| 5.10.52-desktop-1.mga8 | 2         | 1.55%   |
| 5.10.20-desktop-2.mga7 | 2         | 1.55%   |
| 5.10.14-desktop-1.mga7 | 2         | 1.55%   |
| 5.9.6-desktop-1.mga8   | 1         | 0.78%   |
| 5.9.3-desktop-1.mga8   | 1         | 0.78%   |
| 5.9.16-desktop-1.mga7  | 1         | 0.78%   |
| 5.9.11-desktop-3.mga8  | 1         | 0.78%   |
| 5.9.1-desktop-1.mga8   | 1         | 0.78%   |
| 5.8.5-desktop-2.mga8   | 1         | 0.78%   |
| 5.8.14-desktop-1.mga8  | 1         | 0.78%   |
| 5.7.8-desktop-1.mga8   | 1         | 0.78%   |
| 5.6.8-desktop-1.mga7   | 1         | 0.78%   |
| 5.5.6-desktop-2.mga7   | 1         | 0.78%   |
| 5.5.13-desktop-1.mga7  | 1         | 0.78%   |
| 5.4.8-desktop-1.mga7   | 1         | 0.78%   |
| 5.4.12-desktop-1.mga7  | 1         | 0.78%   |
| 5.3.13-desktop-2.mga7  | 1         | 0.78%   |
| 5.16.18-server-1.mga8  | 1         | 0.78%   |
| 5.16.18-desktop-1.mga8 | 1         | 0.78%   |
| 5.16.12-desktop-1.mga8 | 1         | 0.78%   |
| 5.16.10-desktop-2.mga8 | 1         | 0.78%   |
| 5.15.6-desktop-2.mga9  | 1         | 0.78%   |
| 5.15.6-desktop-2.mga8  | 1         | 0.78%   |
| 5.15.2-desktop-2.mga9  | 1         | 0.78%   |
| 5.15.18-desktop-2.mga8 | 1         | 0.78%   |
| 5.15.15-desktop-1.mga8 | 1         | 0.78%   |
| 5.15.10-desktop-1.mga9 | 1         | 0.78%   |
| 5.15.10-desktop-1.mga8 | 1         | 0.78%   |
| 5.14.9-desktop-1.mga9  | 1         | 0.78%   |
| 5.14.12-desktop-2.mga9 | 1         | 0.78%   |
| 5.14.10-desktop-1.mga8 | 1         | 0.78%   |
| 5.13.12-desktop-2.mga8 | 1         | 0.78%   |
| 5.12.15-desktop-1.mga8 | 1         | 0.78%   |
| 5.10.8-desktop-2.mga7  | 1         | 0.78%   |
| 5.10.78-desktop-1.mga8 | 1         | 0.78%   |
| 5.10.62-desktop-1.mga8 | 1         | 0.78%   |
| 5.10.6-desktop-1.mga7  | 1         | 0.78%   |
| 5.10.48-desktop-1.mga8 | 1         | 0.78%   |
| 5.10.46-desktop-1.mga8 | 1         | 0.78%   |
| 5.10.45-desktop-2.mga8 | 1         | 0.78%   |
| 5.10.37-desktop-2.mga8 | 1         | 0.78%   |
| 5.10.33-desktop-1.mga8 | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.19  | 18        | 14.29%  |
| 5.10.27 | 8         | 6.35%   |
| 5.15.32 | 5         | 3.97%   |
| 5.6.14  | 4         | 3.17%   |
| 5.5.4   | 4         | 3.17%   |
| 5.10.25 | 4         | 3.17%   |
| 5.10.12 | 4         | 3.17%   |
| 5.5.9   | 3         | 2.38%   |
| 5.15.23 | 3         | 2.38%   |
| 5.7.14  | 2         | 1.59%   |
| 5.6.6   | 2         | 1.59%   |
| 5.3.7   | 2         | 1.59%   |
| 5.16.18 | 2         | 1.59%   |
| 5.15.6  | 2         | 1.59%   |
| 5.15.4  | 2         | 1.59%   |
| 5.15.16 | 2         | 1.59%   |
| 5.15.11 | 2         | 1.59%   |
| 5.15.10 | 2         | 1.59%   |
| 5.10.60 | 2         | 1.59%   |
| 5.10.56 | 2         | 1.59%   |
| 5.10.52 | 2         | 1.59%   |
| 5.10.20 | 2         | 1.59%   |
| 5.10.16 | 2         | 1.59%   |
| 5.10.14 | 2         | 1.59%   |
| 5.9.6   | 1         | 0.79%   |
| 5.9.3   | 1         | 0.79%   |
| 5.9.16  | 1         | 0.79%   |
| 5.9.11  | 1         | 0.79%   |
| 5.9.1   | 1         | 0.79%   |
| 5.8.5   | 1         | 0.79%   |
| 5.8.14  | 1         | 0.79%   |
| 5.7.8   | 1         | 0.79%   |
| 5.6.8   | 1         | 0.79%   |
| 5.5.6   | 1         | 0.79%   |
| 5.5.13  | 1         | 0.79%   |
| 5.4.8   | 1         | 0.79%   |
| 5.4.12  | 1         | 0.79%   |
| 5.3.13  | 1         | 0.79%   |
| 5.16.12 | 1         | 0.79%   |
| 5.16.10 | 1         | 0.79%   |
| 5.15.2  | 1         | 0.79%   |
| 5.15.18 | 1         | 0.79%   |
| 5.15.15 | 1         | 0.79%   |
| 5.14.9  | 1         | 0.79%   |
| 5.14.12 | 1         | 0.79%   |
| 5.14.10 | 1         | 0.79%   |
| 5.13.12 | 1         | 0.79%   |
| 5.12.15 | 1         | 0.79%   |
| 5.10.8  | 1         | 0.79%   |
| 5.10.78 | 1         | 0.79%   |
| 5.10.62 | 1         | 0.79%   |
| 5.10.6  | 1         | 0.79%   |
| 5.10.48 | 1         | 0.79%   |
| 5.10.46 | 1         | 0.79%   |
| 5.10.45 | 1         | 0.79%   |
| 5.10.37 | 1         | 0.79%   |
| 5.10.33 | 1         | 0.79%   |
| 5.10.30 | 1         | 0.79%   |
| 5.10.3  | 1         | 0.79%   |
| 5.10.2  | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 25.47%  |
| 5.7     | 19        | 17.92%  |
| 5.15    | 19        | 17.92%  |
| 5.5     | 8         | 7.55%   |
| 5.6     | 7         | 6.6%    |
| 5.9     | 5         | 4.72%   |
| 5.16    | 3         | 2.83%   |
| 5.14    | 3         | 2.83%   |
| 4.14    | 3         | 2.83%   |
| 5.8     | 2         | 1.89%   |
| 5.4     | 2         | 1.89%   |
| 5.3     | 2         | 1.89%   |
| 5.13    | 1         | 0.94%   |
| 5.12    | 1         | 0.94%   |
| 5.1     | 1         | 0.94%   |
| 4.9     | 1         | 0.94%   |
| 4.19    | 1         | 0.94%   |
| 4.1     | 1         | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 77        | 97.47%  |
| i686   | 2         | 2.53%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 32        | 35.96%  |
| KDE           | 23        | 25.84%  |
| GNOME         | 9         | 10.11%  |
| Unknown       | 8         | 8.99%   |
| Cinnamon      | 5         | 5.62%   |
| XFCE          | 3         | 3.37%   |
| MATE          | 3         | 3.37%   |
| LXDE          | 3         | 3.37%   |
| LXQt          | 1         | 1.12%   |
| KDE4          | 1         | 1.12%   |
| GNOME Classic | 1         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 76        | 93.83%  |
| Wayland | 3         | 3.7%    |
| Tty     | 2         | 2.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 41        | 51.25%  |
| SDDM    | 31        | 38.75%  |
| TDM     | 3         | 3.75%   |
| LightDM | 3         | 3.75%   |
| XDM     | 1         | 1.25%   |
| GDM     | 1         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| fr_FR   | 15        | 18.52%  |
| en_US   | 15        | 18.52%  |
| de_DE   | 9         | 11.11%  |
| Unknown | 8         | 9.88%   |
| ru_RU   | 6         | 7.41%   |
| en_GB   | 5         | 6.17%   |
| pt_BR   | 4         | 4.94%   |
| it_IT   | 4         | 4.94%   |
| sv_SE   | 2         | 2.47%   |
| pl_PL   | 2         | 2.47%   |
| zh_TW   | 1         | 1.23%   |
| sl_SI   | 1         | 1.23%   |
| hu_HU   | 1         | 1.23%   |
| fr_BE   | 1         | 1.23%   |
| es_MX   | 1         | 1.23%   |
| es_GT   | 1         | 1.23%   |
| es_ES   | 1         | 1.23%   |
| es_AR   | 1         | 1.23%   |
| en_CA   | 1         | 1.23%   |
| cs_CZ   | 1         | 1.23%   |
| bg_BG   | 1         | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 48        | 57.83%  |
| EFI  | 35        | 42.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 65        | 80.25%  |
| Xfs      | 6         | 7.41%   |
| Unknown  | 6         | 7.41%   |
| Btrfs    | 3         | 3.7%    |
| Reiserfs | 1         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 40.24%  |
| GPT     | 31        | 37.8%   |
| MBR     | 18        | 21.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 86.08%  |
| Yes       | 11        | 13.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 79.01%  |
| Yes       | 17        | 20.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 21.52%  |
| Gigabyte Technology | 16        | 20.25%  |
| Hewlett-Packard     | 8         | 10.13%  |
| MSI                 | 6         | 7.59%   |
| Lenovo              | 6         | 7.59%   |
| Dell                | 6         | 7.59%   |
| ASRock              | 5         | 6.33%   |
| Medion              | 2         | 2.53%   |
| Acer                | 2         | 2.53%   |
| ZOTAC               | 1         | 1.27%   |
| Vorke               | 1         | 1.27%   |
| Toshiba             | 1         | 1.27%   |
| Notebook            | 1         | 1.27%   |
| Microsoft           | 1         | 1.27%   |
| Megaware            | 1         | 1.27%   |
| Kiano               | 1         | 1.27%   |
| Intel               | 1         | 1.27%   |
| Fujitsu             | 1         | 1.27%   |
| ECS                 | 1         | 1.27%   |
| Apple               | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Gigabyte Z68X-UD3H-B3                    | 2         | 2.53%   |
| Dell Precision WorkStation T3400         | 2         | 2.53%   |
| ASUS SABERTOOTH 990FX R2.0               | 2         | 2.53%   |
| Unknown                                  | 2         | 2.53%   |
| Vorke V1 Plus                            | 1         | 1.27%   |
| Toshiba dynabook R73/A                   | 1         | 1.27%   |
| Notebook NL40_50GU                       | 1         | 1.27%   |
| MSI MS-7D09                              | 1         | 1.27%   |
| MSI MS-7C82                              | 1         | 1.27%   |
| MSI MS-7C37                              | 1         | 1.27%   |
| MSI MS-7B23                              | 1         | 1.27%   |
| MSI MS-7A70                              | 1         | 1.27%   |
| MSI MS-7816                              | 1         | 1.27%   |
| Microsoft Surface Pro 4                  | 1         | 1.27%   |
| Megaware MW-G31T-M7                      | 1         | 1.27%   |
| Medion MD34161/C708                      | 1         | 1.27%   |
| Medion DEFENDER P10                      | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 1.27%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 1.27%   |
| Lenovo ThinkCentre M58e 7491B1G          | 1         | 1.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.27%   |
| Lenovo G480 20149                        | 1         | 1.27%   |
| Lenovo 70A4000HUX ThinkServer TS140      | 1         | 1.27%   |
| Kiano SlimNote 15.6                      | 1         | 1.27%   |
| Intel STL2                               | 1         | 1.27%   |
| HP Z440 Workstation                      | 1         | 1.27%   |
| HP Z420 Workstation                      | 1         | 1.27%   |
| HP Spectre 13 Ultrabook                  | 1         | 1.27%   |
| HP ProBook 445 G7                        | 1         | 1.27%   |
| HP Pavilion dv6                          | 1         | 1.27%   |
| HP EliteBook 840 G3                      | 1         | 1.27%   |
| HP Compaq Pro 6300 SFF                   | 1         | 1.27%   |
| Gigabyte Z87X-UD5H                       | 1         | 1.27%   |
| Gigabyte Z68XP-UD3P                      | 1         | 1.27%   |
| Gigabyte X570 AORUS ELITE WIFI           | 1         | 1.27%   |
| Gigabyte H81M-S2H                        | 1         | 1.27%   |
| Gigabyte H81M-DS2                        | 1         | 1.27%   |
| Gigabyte H61M-S2PV                       | 1         | 1.27%   |
| Gigabyte H170-D3H                        | 1         | 1.27%   |
| Gigabyte GA-78LMT-USB3 R2                | 1         | 1.27%   |
| Gigabyte GA-78LMT-USB3 6.0               | 1         | 1.27%   |
| Gigabyte G31M-ES2C                       | 1         | 1.27%   |
| Gigabyte F2A88XM-DS2                     | 1         | 1.27%   |
| Gigabyte B85M-D3H                        | 1         | 1.27%   |
| Gigabyte B450M DS3H                      | 1         | 1.27%   |
| Gigabyte B450 AORUS PRO WIFI             | 1         | 1.27%   |
| Fujitsu LIFEBOOK E752                    | 1         | 1.27%   |
| ECS IC780M-A2                            | 1         | 1.27%   |
| Dell Precision 5530                      | 1         | 1.27%   |
| Dell Latitude E6530                      | 1         | 1.27%   |
| Dell Latitude E5570                      | 1         | 1.27%   |
| Dell Inspiron 5480                       | 1         | 1.27%   |
| ASUS Z170-P                              | 1         | 1.27%   |
| ASUS X751LN                              | 1         | 1.27%   |
| ASUS X556URK                             | 1         | 1.27%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR     | 1         | 1.27%   |
| ASUS SABERTOOTH P67                      | 1         | 1.27%   |
| ASUS ROG ZENITH EXTREME                  | 1         | 1.27%   |
| ASUS PRIME X399-A                        | 1         | 1.27%   |
| ASUS PRIME B360-PLUS                     | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Precision         | 3         | 3.8%    |
| ASUS SABERTOOTH        | 3         | 3.8%    |
| ASUS PRIME             | 3         | 3.8%    |
| Lenovo ThinkPad        | 2         | 2.53%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 2.53%   |
| Gigabyte GA-78LMT-USB3 | 2         | 2.53%   |
| Dell Latitude          | 2         | 2.53%   |
| Acer Aspire            | 2         | 2.53%   |
| Unknown                | 2         | 2.53%   |
| Vorke V1               | 1         | 1.27%   |
| Toshiba dynabook       | 1         | 1.27%   |
| Notebook NL40          | 1         | 1.27%   |
| MSI MS-7D09            | 1         | 1.27%   |
| MSI MS-7C82            | 1         | 1.27%   |
| MSI MS-7C37            | 1         | 1.27%   |
| MSI MS-7B23            | 1         | 1.27%   |
| MSI MS-7A70            | 1         | 1.27%   |
| MSI MS-7816            | 1         | 1.27%   |
| Microsoft Surface      | 1         | 1.27%   |
| Megaware MW-G31T-M7    | 1         | 1.27%   |
| Medion MD34161         | 1         | 1.27%   |
| Medion DEFENDER        | 1         | 1.27%   |
| Lenovo ThinkCentre     | 1         | 1.27%   |
| Lenovo IdeaPad         | 1         | 1.27%   |
| Lenovo G480            | 1         | 1.27%   |
| Lenovo 70A4000HUX      | 1         | 1.27%   |
| Kiano SlimNote         | 1         | 1.27%   |
| Intel STL2             | 1         | 1.27%   |
| HP Z440                | 1         | 1.27%   |
| HP Z420                | 1         | 1.27%   |
| HP Spectre             | 1         | 1.27%   |
| HP ProBook             | 1         | 1.27%   |
| HP Pavilion            | 1         | 1.27%   |
| HP EliteBook           | 1         | 1.27%   |
| HP Compaq              | 1         | 1.27%   |
| Gigabyte Z87X-UD5H     | 1         | 1.27%   |
| Gigabyte Z68XP-UD3P    | 1         | 1.27%   |
| Gigabyte X570          | 1         | 1.27%   |
| Gigabyte H81M-S2H      | 1         | 1.27%   |
| Gigabyte H81M-DS2      | 1         | 1.27%   |
| Gigabyte H61M-S2PV     | 1         | 1.27%   |
| Gigabyte H170-D3H      | 1         | 1.27%   |
| Gigabyte G31M-ES2C     | 1         | 1.27%   |
| Gigabyte F2A88XM-DS2   | 1         | 1.27%   |
| Gigabyte B85M-D3H      | 1         | 1.27%   |
| Gigabyte B450M         | 1         | 1.27%   |
| Gigabyte B450          | 1         | 1.27%   |
| Fujitsu LIFEBOOK       | 1         | 1.27%   |
| ECS IC780M-A2          | 1         | 1.27%   |
| Dell Inspiron          | 1         | 1.27%   |
| ASUS Z170-P            | 1         | 1.27%   |
| ASUS X751LN            | 1         | 1.27%   |
| ASUS X556URK           | 1         | 1.27%   |
| ASUS VivoBook          | 1         | 1.27%   |
| ASUS ROG               | 1         | 1.27%   |
| ASUS P8H61-M           | 1         | 1.27%   |
| ASUS M5A97             | 1         | 1.27%   |
| ASUS M4A78             | 1         | 1.27%   |
| ASUS H170M-PLUS        | 1         | 1.27%   |
| ASUS All               | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 12        | 15.19%  |
| 2012 | 10        | 12.66%  |
| 2018 | 9         | 11.39%  |
| 2017 | 7         | 8.86%   |
| 2016 | 6         | 7.59%   |
| 2014 | 5         | 6.33%   |
| 2008 | 5         | 6.33%   |
| 2020 | 4         | 5.06%   |
| 2019 | 4         | 5.06%   |
| 2015 | 4         | 5.06%   |
| 2009 | 4         | 5.06%   |
| 2011 | 3         | 3.8%    |
| 2010 | 3         | 3.8%    |
| 2021 | 1         | 1.27%   |
| 2007 | 1         | 1.27%   |
| 2002 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 54        | 68.35%  |
| Notebook   | 23        | 29.11%  |
| Tablet     | 1         | 1.27%   |
| All in one | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 25.3%   |
| 8.01-16.0   | 17        | 20.48%  |
| 4.01-8.0    | 16        | 19.28%  |
| 32.01-64.0  | 11        | 13.25%  |
| 3.01-4.0    | 11        | 13.25%  |
| 64.01-256.0 | 4         | 4.82%   |
| 24.01-32.0  | 2         | 2.41%   |
| 2.01-3.0    | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 30        | 30.3%   |
| 1.01-2.0   | 24        | 24.24%  |
| 4.01-8.0   | 20        | 20.2%   |
| 3.01-4.0   | 14        | 14.14%  |
| 8.01-16.0  | 6         | 6.06%   |
| 0.51-1.0   | 4         | 4.04%   |
| 16.01-24.0 | 1         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 38.55%  |
| 2      | 21        | 25.3%   |
| 3      | 16        | 19.28%  |
| 5      | 6         | 7.23%   |
| 4      | 4         | 4.82%   |
| 6      | 2         | 2.41%   |
| 8      | 1         | 1.2%    |
| 7      | 1         | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 53.16%  |
| Yes       | 37        | 46.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 89.87%  |
| No        | 8         | 10.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 51.25%  |
| Yes       | 39        | 48.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 50.63%  |
| Yes       | 39        | 49.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| France     | 16        | 20.25%  |
| USA        | 12        | 15.19%  |
| Germany    | 9         | 11.39%  |
| UK         | 6         | 7.59%   |
| Italy      | 4         | 5.06%   |
| Brazil     | 4         | 5.06%   |
| Ukraine    | 3         | 3.8%    |
| Russia     | 3         | 3.8%    |
| Sweden     | 2         | 2.53%   |
| Poland     | 2         | 2.53%   |
| Greece     | 2         | 2.53%   |
| Canada     | 2         | 2.53%   |
| Taiwan     | 1         | 1.27%   |
| Slovenia   | 1         | 1.27%   |
| Romania    | 1         | 1.27%   |
| Mexico     | 1         | 1.27%   |
| Luxembourg | 1         | 1.27%   |
| Kenya      | 1         | 1.27%   |
| Indonesia  | 1         | 1.27%   |
| Guatemala  | 1         | 1.27%   |
| Czechia    | 1         | 1.27%   |
| Colombia   | 1         | 1.27%   |
| Bulgaria   | 1         | 1.27%   |
| Belgium    | 1         | 1.27%   |
| Belarus    | 1         | 1.27%   |
| Argentina  | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                         | Computers | Percent |
|------------------------------|-----------|---------|
| Paris                        | 4         | 3.96%   |
| Waterloo                     | 3         | 2.97%   |
| Mala Danylivka               | 3         | 2.97%   |
| Kharkiv                      | 3         | 2.97%   |
| Cologne                      | 3         | 2.97%   |
| Sao Paulo                    | 2         | 1.98%   |
| Rome                         | 2         | 1.98%   |
| Oakland                      | 2         | 1.98%   |
| Kingston upon Thames         | 2         | 1.98%   |
| Grants Pass                  | 2         | 1.98%   |
| Basingstoke                  | 2         | 1.98%   |
| Yakutsk                      | 1         | 0.99%   |
| Werl                         | 1         | 0.99%   |
| Voronezh                     | 1         | 0.99%   |
| Volos                        | 1         | 0.99%   |
| Tver                         | 1         | 0.99%   |
| Turin                        | 1         | 0.99%   |
| Tresserve                    | 1         | 0.99%   |
| Tours                        | 1         | 0.99%   |
| Thessaloniki                 | 1         | 0.99%   |
| Teddington                   | 1         | 0.99%   |
| Strasbourg                   | 1         | 0.99%   |
| Sternberk                    | 1         | 0.99%   |
| Sartrouville                 | 1         | 0.99%   |
| Sainte-GeneviÃ¨ve-des-Bois | 1         | 0.99%   |
| Saint-Michel-sur-Orge        | 1         | 0.99%   |
| Saint-DiГ©                 | 1         | 0.99%   |
| Rio de Janeiro               | 1         | 0.99%   |
| Poznan                       | 1         | 0.99%   |
| Pisa                         | 1         | 0.99%   |
| Penmarch                     | 1         | 0.99%   |
| Palermo                      | 1         | 0.99%   |
| Oxford                       | 1         | 0.99%   |
| Odenville                    | 1         | 0.99%   |
| Obernai                      | 1         | 0.99%   |
| Nova Vodolaha                | 1         | 0.99%   |
| Nova Gorica                  | 1         | 0.99%   |
| Nordenham                    | 1         | 0.99%   |
| Niedermodern                 | 1         | 0.99%   |
| New Taipei                   | 1         | 0.99%   |
| Nairobi                      | 1         | 0.99%   |
| Munich                       | 1         | 0.99%   |
| Miercurea-Ciuc               | 1         | 0.99%   |
| Mannheim                     | 1         | 0.99%   |
| Luxembourg                   | 1         | 0.99%   |
| Lumajang                     | 1         | 0.99%   |
| Londrina                     | 1         | 0.99%   |
| LiГЁge                     | 1         | 0.99%   |
| Lisieux                      | 1         | 0.99%   |
| León                        | 1         | 0.99%   |
| Le Plessis-Robinson          | 1         | 0.99%   |
| Kehychivka                   | 1         | 0.99%   |
| Kalisz                       | 1         | 0.99%   |
| Jena                         | 1         | 0.99%   |
| Huty                         | 1         | 0.99%   |
| Helsingborg                  | 1         | 0.99%   |
| Hammersmith                  | 1         | 0.99%   |
| Guatemala City               | 1         | 0.99%   |
| Fresno                       | 1         | 0.99%   |
| Frankfurt am Main            | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 39        | 154    | 24.22%  |
| Seagate                 | 24        | 43     | 14.91%  |
| Samsung Electronics     | 19        | 23     | 11.8%   |
| Kingston                | 13        | 21     | 8.07%   |
| Toshiba                 | 10        | 18     | 6.21%   |
| Sandisk                 | 8         | 14     | 4.97%   |
| Hitachi                 | 7         | 7      | 4.35%   |
| Unknown                 | 4         | 4      | 2.48%   |
| PNY                     | 4         | 6      | 2.48%   |
| HGST                    | 4         | 9      | 2.48%   |
| Crucial                 | 4         | 8      | 2.48%   |
| Intel                   | 3         | 3      | 1.86%   |
| SK Hynix                | 2         | 3      | 1.24%   |
| Phison                  | 2         | 3      | 1.24%   |
| OCZ-VERTEX              | 2         | 2      | 1.24%   |
| OCZ                     | 2         | 2      | 1.24%   |
| A-DATA Technology       | 2         | 5      | 1.24%   |
| XPG                     | 1         | 4      | 0.62%   |
| Verbatim                | 1         | 1      | 0.62%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.62%   |
| Transcend               | 1         | 1      | 0.62%   |
| TO Exter                | 1         | 1      | 0.62%   |
| Team                    | 1         | 1      | 0.62%   |
| LDLC                    | 1         | 1      | 0.62%   |
| HUAWEI                  | 1         | 1      | 0.62%   |
| FORESEE                 | 1         | 1      | 0.62%   |
| Corsair                 | 1         | 1      | 0.62%   |
| China                   | 1         | 1      | 0.62%   |
| Asmedia                 | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4         | 2.19%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3         | 1.64%   |
| Samsung SSD 860 EVO 250GB        | 3         | 1.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 1.09%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2         | 1.09%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 1.09%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2         | 1.09%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2         | 1.09%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2         | 1.09%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2         | 1.09%   |
| Toshiba HDWD120 2TB              | 2         | 1.09%   |
| Seagate ST3500418AS 500GB        | 2         | 1.09%   |
| Seagate ST32000644NS 2TB         | 2         | 1.09%   |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 1.09%   |
| SanDisk SDSSDA120G 120GB         | 2         | 1.09%   |
| SanDisk Extreme SSD 1TB          | 2         | 1.09%   |
| Samsung SSD 860 EVO 500GB        | 2         | 1.09%   |
| Samsung SSD 850 EVO 500GB        | 2         | 1.09%   |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2         | 1.09%   |
| Kingston SV300S37A240G 240GB SSD | 2         | 1.09%   |
| Kingston SH103S3120G 120GB SSD   | 2         | 1.09%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 1.09%   |
| Intel SSDSC2CW120A3 120GB        | 2         | 1.09%   |
| Hitachi HDS722020ALA330 2TB      | 2         | 1.09%   |
| HGST HUS726040ALE611 4TB         | 2         | 1.09%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 1.09%   |
| XPG NVMe SSD Drive 2TB           | 1         | 0.55%   |
| XPG NVMe SSD Drive 1024GB        | 1         | 0.55%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1         | 0.55%   |
| WDC WDS100T2B0A 1TB SSD          | 1         | 0.55%   |
| WDC WD800BB-00JHC0 80GB          | 1         | 0.55%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB      | 1         | 0.55%   |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.55%   |
| WDC WD4000FYYZ-01UL1B2 4TB       | 1         | 0.55%   |
| WDC WD3200KS-00PFB0 320GB        | 1         | 0.55%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1         | 0.55%   |
| WDC WD3200AAJS-00B4A0 320GB      | 1         | 0.55%   |
| WDC WD30PURX-64P6ZY0 3TB         | 1         | 0.55%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1         | 0.55%   |
| WDC WD30EZRX-00D8PB0 3TB         | 1         | 0.55%   |
| WDC WD3000GLFS-01F8U0 304GB      | 1         | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.55%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.55%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 0.55%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 0.55%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1         | 0.55%   |
| WDC WD141KRYZ-01C66B0 14TB       | 1         | 0.55%   |
| WDC WD10SPZX-75Z10T2 1TB         | 1         | 0.55%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1         | 0.55%   |
| WDC WD10EZRX-00L4HB0 1TB         | 1         | 0.55%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1         | 0.55%   |
| WDC WD10EZEX-22MFCA0 1TB         | 1         | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB          | 1         | 0.55%   |
| WDC WD10EARS-00MVWB0 1TB         | 1         | 0.55%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 0.55%   |
| WDC WD1001FAES-75W7A0 1TB        | 1         | 0.55%   |
| Verbatim USB External SSD 256GB  | 1         | 0.55%   |
| Unknown SD/MMC/MS PRO 16GB       | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 136    | 39.02%  |
| Seagate             | 23        | 39     | 28.05%  |
| Toshiba             | 9         | 17     | 10.98%  |
| Hitachi             | 7         | 7      | 8.54%   |
| Samsung Electronics | 4         | 6      | 4.88%   |
| HGST                | 4         | 9      | 4.88%   |
| Unknown             | 2         | 2      | 2.44%   |
| Asmedia             | 1         | 1      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 19.67%  |
| Kingston            | 10        | 16     | 16.39%  |
| WDC                 | 7         | 17     | 11.48%  |
| SanDisk             | 6         | 8      | 9.84%   |
| PNY                 | 4         | 6      | 6.56%   |
| Crucial             | 4         | 8      | 6.56%   |
| Intel               | 3         | 3      | 4.92%   |
| OCZ-VERTEX          | 2         | 2      | 3.28%   |
| OCZ                 | 2         | 2      | 3.28%   |
| A-DATA Technology   | 2         | 5      | 3.28%   |
| Verbatim            | 1         | 1      | 1.64%   |
| Transcend           | 1         | 1      | 1.64%   |
| TO Exter            | 1         | 1      | 1.64%   |
| Team                | 1         | 1      | 1.64%   |
| SK Hynix            | 1         | 1      | 1.64%   |
| LDLC                | 1         | 1      | 1.64%   |
| FORESEE             | 1         | 1      | 1.64%   |
| Corsair             | 1         | 1      | 1.64%   |
| China               | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 58        | 217    | 48.33%  |
| SSD     | 43        | 89     | 35.83%  |
| NVMe    | 15        | 27     | 12.5%   |
| MMC     | 2         | 2      | 1.67%   |
| Unknown | 2         | 5      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 291    | 73.47%  |
| NVMe | 15        | 27     | 15.31%  |
| SAS  | 9         | 20     | 9.18%   |
| MMC  | 2         | 2      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 108    | 47.58%  |
| 0.51-1.0   | 36        | 110    | 29.03%  |
| 1.01-2.0   | 15        | 29     | 12.1%   |
| 2.01-3.0   | 6         | 46     | 4.84%   |
| 3.01-4.0   | 5         | 7      | 4.03%   |
| 4.01-10.0  | 2         | 5      | 1.61%   |
| 10.01-20.0 | 1         | 1      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 20        | 23.81%  |
| More than 3000 | 16        | 19.05%  |
| 251-500        | 15        | 17.86%  |
| 101-250        | 12        | 14.29%  |
| 2001-3000      | 9         | 10.71%  |
| 1001-2000      | 8         | 9.52%   |
| 51-100         | 3         | 3.57%   |
| Unknown        | 1         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 19.78%  |
| 51-100         | 13        | 14.29%  |
| 1001-2000      | 12        | 13.19%  |
| 1-20           | 12        | 13.19%  |
| 251-500        | 10        | 10.99%  |
| 501-1000       | 10        | 10.99%  |
| More than 3000 | 7         | 7.69%   |
| 21-50          | 6         | 6.59%   |
| 2001-3000      | 2         | 2.2%    |
| Unknown        | 1         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 13.33%  |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 6.67%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 6.67%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 6.67%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 6.67%   |
| Seagate ST3250410AS 250GB             | 1         | 1      | 6.67%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 6.67%   |
| Seagate ST2000VN004-2E4164 2TB        | 1         | 1      | 6.67%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 6.67%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 35.71%  |
| WDC      | 2         | 3      | 14.29%  |
| Intel    | 2         | 2      | 14.29%  |
| Toshiba  | 1         | 1      | 7.14%   |
| SK Hynix | 1         | 1      | 7.14%   |
| OCZ      | 1         | 1      | 7.14%   |
| Hitachi  | 1         | 1      | 7.14%   |
| HGST     | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 50%     |
| WDC     | 2         | 3      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 11     | 69.23%  |
| SSD  | 4         | 4      | 30.77%  |

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
| Works    | 43        | 181    | 44.79%  |
| Detected | 40        | 144    | 41.67%  |
| Malfunc  | 13        | 15     | 13.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 52.43%  |
| AMD                          | 20        | 19.42%  |
| Marvell Technology Group     | 7         | 6.8%    |
| ASMedia Technology           | 5         | 4.85%   |
| Sandisk                      | 3         | 2.91%   |
| Samsung Electronics          | 3         | 2.91%   |
| Phison Electronics           | 3         | 2.91%   |
| Kingston Technology Company  | 3         | 2.91%   |
| Toshiba America Info Systems | 1         | 0.97%   |
| SK Hynix                     | 1         | 0.97%   |
| JMicron Technology           | 1         | 0.97%   |
| Broadcom                     | 1         | 0.97%   |
| ADATA Technology             | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 6.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 6.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 3.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 3.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 3.88%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 3.1%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 3.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 3.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 3.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 3.1%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 2.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.55%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 1.55%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.55%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.55%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.55%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.55%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2         | 1.55%   |
| AMD SB600 IDE                                                                           | 2         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.78%   |
| SK Hynix BC511                                                                          | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.78%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.78%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.78%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.78%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.78%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1         | 0.78%   |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                         | 1         | 0.78%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 0.78%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 0.78%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.78%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.78%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.78%   |
| Broadcom OSB4 IDE Controller                                                            | 1         | 0.78%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.78%   |
| AMD FCH SATA Controller D                                                               | 1         | 0.78%   |
| AMD FCH IDE Controller                                                                  | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 62.38%  |
| IDE  | 19        | 18.81%  |
| NVMe | 14        | 13.86%  |
| RAID | 4         | 3.96%   |
| SAS  | 1         | 0.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 73.42%  |
| AMD    | 21        | 26.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 3.75%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 2         | 2.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz                | 2         | 2.5%    |
| Intel Core i7-2600K CPU @ 3.40GHz               | 2         | 2.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 2.5%    |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2         | 2.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2         | 2.5%    |
| AMD FX-8350 Eight-Core Processor                | 2         | 2.5%    |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz              | 1         | 1.25%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1         | 1.25%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 1.25%   |
| Intel Pentium III (Coppermine)                  | 1         | 1.25%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1         | 1.25%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 1.25%   |
| Intel Pentium CPU G3450 @ 3.40GHz               | 1         | 1.25%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 1.25%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.25%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 1.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1         | 1.25%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1         | 1.25%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 1.25%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 1.25%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 1.25%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 1.25%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1         | 1.25%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1         | 1.25%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1         | 1.25%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 1.25%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1         | 1.25%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 1.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.25%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1         | 1.25%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 1.25%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 1.25%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1         | 1.25%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 1.25%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1         | 1.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1         | 1.25%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1         | 1.25%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 1.25%   |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 1         | 1.25%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 1.25%   |
| Intel Celeron CPU G1830 @ 2.80GHz               | 1         | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 1.25%   |
| Intel 11th Gen Core i9-11900 @ 2.50GHz          | 1         | 1.25%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 1         | 1.25%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1         | 1.25%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.25%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 1.25%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 1.25%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1         | 1.25%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 1.25%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 17        | 21.52%  |
| Intel Core i5           | 17        | 21.52%  |
| Intel Core i3           | 6         | 7.59%   |
| AMD FX                  | 5         | 6.33%   |
| AMD Ryzen 7             | 4         | 5.06%   |
| Intel Core 2 Duo        | 3         | 3.8%    |
| Intel Xeon              | 2         | 2.53%   |
| Intel Pentium Dual-Core | 2         | 2.53%   |
| Intel Pentium           | 2         | 2.53%   |
| Intel Celeron           | 2         | 2.53%   |
| AMD Ryzen Threadripper  | 2         | 2.53%   |
| AMD Ryzen 5             | 2         | 2.53%   |
| Other                   | 1         | 1.27%   |
| Intel Pentium Silver    | 1         | 1.27%   |
| Intel Pentium III       | 1         | 1.27%   |
| Intel Pentium Gold      | 1         | 1.27%   |
| Intel Core 2 Quad       | 1         | 1.27%   |
| Intel Core 2            | 1         | 1.27%   |
| Intel Atom              | 1         | 1.27%   |
| AMD Turion 64 X2 Mobile | 1         | 1.27%   |
| AMD Ryzen 9             | 1         | 1.27%   |
| AMD Ryzen 3             | 1         | 1.27%   |
| AMD Phenom II X6        | 1         | 1.27%   |
| AMD Phenom II X4        | 1         | 1.27%   |
| AMD Athlon II X3        | 1         | 1.27%   |
| AMD A8                  | 1         | 1.27%   |
| AMD A10                 | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 33        | 41.25%  |
| 2      | 31        | 38.75%  |
| 6      | 7         | 8.75%   |
| 8      | 4         | 5%      |
| 3      | 2         | 2.5%    |
| 32     | 1         | 1.25%   |
| 16     | 1         | 1.25%   |
| 12     | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 98.73%  |
| 2      | 1         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 50        | 63.29%  |
| 1      | 29        | 36.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 95.06%  |
| Unknown        | 3         | 3.7%    |
| 32-bit         | 1         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 19.54%  |
| 0x306c3    | 8         | 9.2%    |
| 0x206a7    | 6         | 6.9%    |
| 0x306a9    | 5         | 5.75%   |
| 0x1067a    | 4         | 4.6%    |
| 0x806e9    | 3         | 3.45%   |
| 0x406e3    | 3         | 3.45%   |
| 0x06000852 | 3         | 3.45%   |
| 0x906ea    | 2         | 2.3%    |
| 0x40651    | 2         | 2.3%    |
| 0x08701021 | 2         | 2.3%    |
| 0x08108109 | 2         | 2.3%    |
| 0x0800820d | 2         | 2.3%    |
| 0x010000c8 | 2         | 2.3%    |
| 0xa0671    | 1         | 1.15%   |
| 0xa0653    | 1         | 1.15%   |
| 0xa0652    | 1         | 1.15%   |
| 0x906eb    | 1         | 1.15%   |
| 0x906e9    | 1         | 1.15%   |
| 0x806eb    | 1         | 1.15%   |
| 0x706a1    | 1         | 1.15%   |
| 0x6fb      | 1         | 1.15%   |
| 0x6f6      | 1         | 1.15%   |
| 0x686      | 1         | 1.15%   |
| 0x506e3    | 1         | 1.15%   |
| 0x506c9    | 1         | 1.15%   |
| 0x406c4    | 1         | 1.15%   |
| 0x306f2    | 1         | 1.15%   |
| 0x206d7    | 1         | 1.15%   |
| 0x20655    | 1         | 1.15%   |
| 0x08701013 | 1         | 1.15%   |
| 0x08600106 | 1         | 1.15%   |
| 0x08108102 | 1         | 1.15%   |
| 0x08101016 | 1         | 1.15%   |
| 0x0800820b | 1         | 1.15%   |
| 0x08001137 | 1         | 1.15%   |
| 0x06003104 | 1         | 1.15%   |
| 0x06001119 | 1         | 1.15%   |
| 0x0600084f | 1         | 1.15%   |
| 0x010000bf | 1         | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 13        | 16.25%  |
| KabyLake      | 11        | 13.75%  |
| SandyBridge   | 7         | 8.75%   |
| Skylake       | 6         | 7.5%    |
| IvyBridge     | 6         | 7.5%    |
| Zen+          | 5         | 6.25%   |
| Piledriver    | 5         | 6.25%   |
| Zen 2         | 4         | 5%      |
| Penryn        | 4         | 5%      |
| K10           | 3         | 3.75%   |
| Core          | 3         | 3.75%   |
| Zen           | 2         | 2.5%    |
| CometLake     | 2         | 2.5%    |
| Westmere      | 1         | 1.25%   |
| Steamroller   | 1         | 1.25%   |
| Silvermont    | 1         | 1.25%   |
| P6            | 1         | 1.25%   |
| K8 Hammer     | 1         | 1.25%   |
| Icelake       | 1         | 1.25%   |
| Goldmont plus | 1         | 1.25%   |
| Goldmont      | 1         | 1.25%   |
| Bulldozer     | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 39        | 41.94%  |
| Intel  | 37        | 39.78%  |
| AMD    | 17        | 18.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 4.3%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 4         | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 4.3%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.23%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 3.23%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 2.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 2.15%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 2.15%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 2.15%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.15%   |
| Intel HD Graphics 620                                                                    | 2         | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.15%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 2         | 2.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.08%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                                         | 1         | 1.08%   |
| Nvidia GT218 [GeForce G210]                                                              | 1         | 1.08%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.08%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.08%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.08%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.08%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.08%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 1.08%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 1         | 1.08%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.08%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 1.08%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 1.08%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.08%   |
| Nvidia G73 [GeForce 7300 GT]                                                             | 1         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.08%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.08%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.08%   |
| Intel HD Graphics 630                                                                    | 1         | 1.08%   |
| Intel HD Graphics 530                                                                    | 1         | 1.08%   |
| Intel HD Graphics 500                                                                    | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.08%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1         | 1.08%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.08%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.08%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.08%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 1.08%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 1.08%   |
| AMD Renoir                                                                               | 1         | 1.08%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                                | 1         | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.08%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 28        | 35%     |
| 1 x Intel      | 25        | 31.25%  |
| 1 x AMD        | 15        | 18.75%  |
| Intel + Nvidia | 10        | 12.5%   |
| Intel + AMD    | 1         | 1.25%   |
| AMD + Nvidia   | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 55        | 67.07%  |
| Proprietary | 14        | 17.07%  |
| Unknown     | 13        | 15.85%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 37.35%  |
| 1.01-2.0   | 19        | 22.89%  |
| 0.51-1.0   | 13        | 15.66%  |
| 0.01-0.5   | 6         | 7.23%   |
| 3.01-4.0   | 5         | 6.02%   |
| 5.01-6.0   | 4         | 4.82%   |
| 7.01-8.0   | 2         | 2.41%   |
| 2.01-3.0   | 2         | 2.41%   |
| 8.01-16.0  | 1         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 8.7%    |
| Ancor Communications    | 8         | 8.7%    |
| Dell                    | 6         | 6.52%   |
| BOE                     | 6         | 6.52%   |
| Chimei Innolux          | 5         | 5.43%   |
| BenQ                    | 5         | 5.43%   |
| AOC                     | 5         | 5.43%   |
| Acer                    | 5         | 5.43%   |
| SNC                     | 4         | 4.35%   |
| LG Display              | 4         | 4.35%   |
| Goldstar                | 4         | 4.35%   |
| ViewSonic               | 3         | 3.26%   |
| Sony                    | 3         | 3.26%   |
| Philips                 | 3         | 3.26%   |
| LG Electronics          | 3         | 3.26%   |
| AU Optronics            | 3         | 3.26%   |
| Hewlett-Packard         | 2         | 2.17%   |
| Chi Mei Optoelectronics | 2         | 2.17%   |
| Unknown                 | 1         | 1.09%   |
| Sharp                   | 1         | 1.09%   |
| RTK                     | 1         | 1.09%   |
| QBell                   | 1         | 1.09%   |
| PKB                     | 1         | 1.09%   |
| ONKYO                   | 1         | 1.09%   |
| Medion                  | 1         | 1.09%   |
| Lenovo                  | 1         | 1.09%   |
| HannStar                | 1         | 1.09%   |
| Eizo                    | 1         | 1.09%   |
| Compal                  | 1         | 1.09%   |
| ASUSTek Computer        | 1         | 1.09%   |
| Apple                   | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4         | 3.96%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2         | 1.98%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2         | 1.98%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2         | 1.98%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1         | 0.99%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1         | 0.99%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1         | 0.99%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.99%   |
| Sony TV SNYF301 1920x1080                                             | 1         | 0.99%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1         | 0.99%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1         | 0.99%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.99%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch   | 1         | 0.99%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch    | 1         | 0.99%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1         | 0.99%   |
| Samsung Electronics LCD Monitor S24D330                               | 1         | 0.99%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.99%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.99%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1         | 0.99%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1         | 0.99%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1         | 0.99%   |
| Philips LCD Monitor PHLC0BF 1600x900 430x240mm 19.4-inch              | 1         | 0.99%   |
| Philips LCD Monitor FTV                                               | 1         | 0.99%   |
| ONKYO LCD Monitor TX-SR608 5760x2160                                  | 1         | 0.99%   |
| ONKYO LCD Monitor TX-SR608                                            | 1         | 0.99%   |
| ONKYO LCD Monitor AV Receiver 5760x2160                               | 1         | 0.99%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.99%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                        | 1         | 0.99%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1         | 0.99%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                           | 1         | 0.99%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch           | 1         | 0.99%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 0.99%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch         | 1         | 0.99%   |
| Hewlett-Packard w22 HWP26AE 1680x1050 470x300mm 22.0-inch             | 1         | 0.99%   |
| Hewlett-Packard LP1965 HWP2693 1280x1024 380x300mm 19.1-inch          | 1         | 0.99%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                  | 1         | 0.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.99%   |
| Goldstar 22BK55 GSM5A30 1680x1050 480x300mm 22.3-inch                 | 1         | 0.99%   |
| Eizo EV2436W ENC2384 1920x1200 519x324mm 24.1-inch                    | 1         | 0.99%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                     | 1         | 0.99%   |
| Dell P2715Q DEL40BF 3840x2160 597x336mm 27.0-inch                     | 1         | 0.99%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 1         | 0.99%   |
| Dell LCD Monitor U2715H 2560x1440                                     | 1         | 0.99%   |
| Dell LCD Monitor ST2420L                                              | 1         | 0.99%   |
| Dell LCD Monitor SP2309W                                              | 1         | 0.99%   |
| Dell LCD Monitor P190S 2560x1024                                      | 1         | 0.99%   |
| Compal TERRA 2450W WOR2450 1920x1080 341x256mm 16.8-inch              | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch       | 1         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch      | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 43.48%  |
| 1366x768 (WXGA)    | 10        | 10.87%  |
| Unknown            | 7         | 7.61%   |
| 3840x2160 (4K)     | 5         | 5.43%   |
| 1600x900 (HD+)     | 5         | 5.43%   |
| 1280x1024 (SXGA)   | 5         | 5.43%   |
| 1920x1200 (WUXGA)  | 4         | 4.35%   |
| 1680x1050 (WSXGA+) | 3         | 3.26%   |
| 3840x1080          | 2         | 2.17%   |
| 5760x2160          | 1         | 1.09%   |
| 4480x1440          | 1         | 1.09%   |
| 3520x1080          | 1         | 1.09%   |
| 3200x900           | 1         | 1.09%   |
| 2736x1824          | 1         | 1.09%   |
| 2560x1440 (QHD)    | 1         | 1.09%   |
| 2560x1024          | 1         | 1.09%   |
| 1440x900 (WXGA+)   | 1         | 1.09%   |
| 1360x768           | 1         | 1.09%   |
| 1280x800 (WXGA)    | 1         | 1.09%   |
| 1024x768 (XGA)     | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 12        | 13.48%  |
| 15      | 11        | 12.36%  |
| 27      | 9         | 10.11%  |
| 24      | 9         | 10.11%  |
| 21      | 8         | 8.99%   |
| 19      | 6         | 6.74%   |
| 17      | 6         | 6.74%   |
| 13      | 6         | 6.74%   |
| 18      | 4         | 4.49%   |
| 22      | 3         | 3.37%   |
| 14      | 3         | 3.37%   |
| 46      | 2         | 2.25%   |
| 25      | 2         | 2.25%   |
| 23      | 2         | 2.25%   |
| 72      | 1         | 1.12%   |
| 54      | 1         | 1.12%   |
| 42      | 1         | 1.12%   |
| 32      | 1         | 1.12%   |
| 20      | 1         | 1.12%   |
| 12      | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 21        | 23.86%  |
| 301-350     | 18        | 20.45%  |
| 401-500     | 17        | 19.32%  |
| Unknown     | 12        | 13.64%  |
| 351-400     | 9         | 10.23%  |
| 201-300     | 4         | 4.55%   |
| 1001-1500   | 3         | 3.41%   |
| 701-800     | 1         | 1.14%   |
| 601-700     | 1         | 1.14%   |
| 1501-2000   | 1         | 1.14%   |
| 901-1000    | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 54        | 65.06%  |
| Unknown | 12        | 14.46%  |
| 16/10   | 10        | 12.05%  |
| 5/4     | 5         | 6.02%   |
| 4/3     | 1         | 1.2%    |
| 3/2     | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 17.24%  |
| Unknown        | 12        | 13.79%  |
| 101-110        | 11        | 12.64%  |
| 301-350        | 9         | 10.34%  |
| 151-200        | 9         | 10.34%  |
| 81-90          | 6         | 6.9%    |
| 251-300        | 5         | 5.75%   |
| 141-150        | 5         | 5.75%   |
| 121-130        | 5         | 5.75%   |
| 501-1000       | 3         | 3.45%   |
| More than 1000 | 2         | 2.3%    |
| 71-80          | 2         | 2.3%    |
| 61-70          | 1         | 1.15%   |
| 351-500        | 1         | 1.15%   |
| 91-100         | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 40.48%  |
| 101-120       | 17        | 20.24%  |
| 121-160       | 13        | 15.48%  |
| Unknown       | 12        | 14.29%  |
| 1-50          | 4         | 4.76%   |
| 161-240       | 3         | 3.57%   |
| More than 240 | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 75%     |
| 2     | 20        | 25%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 36.94%  |
| Realtek Semiconductor    | 39        | 35.14%  |
| Qualcomm Atheros         | 10        | 9.01%   |
| Broadcom                 | 8         | 7.21%   |
| Marvell Technology Group | 3         | 2.7%    |
| Wilocity                 | 1         | 0.9%    |
| Ultimarc                 | 1         | 0.9%    |
| Sierra Wireless          | 1         | 0.9%    |
| MediaTek                 | 1         | 0.9%    |
| Huawei Technologies      | 1         | 0.9%    |
| Dell                     | 1         | 0.9%    |
| D-Link System            | 1         | 0.9%    |
| Broadcom Limited         | 1         | 0.9%    |
| ASIX Electronics         | 1         | 0.9%    |
| Aquantia                 | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 23.85%  |
| Intel I211 Gigabit Network Connection                             | 5         | 3.85%   |
| Intel Wireless 8260                                               | 4         | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.08%   |
| Intel Wireless 3165                                               | 3         | 2.31%   |
| Intel Ethernet Connection I217-V                                  | 3         | 2.31%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 1.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2         | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.54%   |
| Intel Wireless 7265                                               | 2         | 1.54%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.54%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.54%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.54%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.54%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.77%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1         | 0.77%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.77%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.77%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.77%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.77%   |
| MediaTek WiFi                                                     | 1         | 0.77%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.77%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.77%   |
| Intel Wireless-AC 9260                                            | 1         | 0.77%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.77%   |
| Intel Wireless 7260                                               | 1         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 0.77%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.77%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.77%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 50%     |
| Qualcomm Atheros         | 7         | 15.22%  |
| Realtek Semiconductor    | 6         | 13.04%  |
| Broadcom                 | 5         | 10.87%  |
| Wilocity                 | 1         | 2.17%   |
| Sierra Wireless          | 1         | 2.17%   |
| MediaTek                 | 1         | 2.17%   |
| Marvell Technology Group | 1         | 2.17%   |
| Dell                     | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 8%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 8%      |
| Intel Wireless 3165                                            | 3         | 6%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 4%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 4%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4%      |
| Intel Wireless 7265                                            | 2         | 4%      |
| Intel Wi-Fi 6 AX200                                            | 2         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 4%      |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 2%      |
| Sierra Wireless MC8305 Modem                                   | 1         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2%      |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2%      |
| MediaTek WiFi                                                  | 1         | 2%      |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 2%      |
| Intel Wireless-AC 9260                                         | 1         | 2%      |
| Intel Wireless 8265 / 8275                                     | 1         | 2%      |
| Intel Wireless 7260                                            | 1         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2%      |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 2%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 2%      |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2%      |
| Broadcom BCM4311 802.11a/b/g                                   | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 47.37%  |
| Intel                    | 27        | 35.53%  |
| Qualcomm Atheros         | 4         | 5.26%   |
| Broadcom                 | 3         | 3.95%   |
| Marvell Technology Group | 2         | 2.63%   |
| D-Link System            | 1         | 1.32%   |
| Broadcom Limited         | 1         | 1.32%   |
| ASIX Electronics         | 1         | 1.32%   |
| Aquantia                 | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 39.74%  |
| Intel I211 Gigabit Network Connection                             | 5         | 6.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.13%   |
| Intel Ethernet Connection I217-V                                  | 3         | 3.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.56%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.56%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 2.56%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 2.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.28%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.28%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.28%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.28%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.28%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.28%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.28%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.28%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.28%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 1.28%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.28%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.28%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.28%   |
| ASIX AX88772B                                                     | 1         | 1.28%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 62.83%  |
| WiFi     | 40        | 35.4%   |
| Modem    | 1         | 0.88%   |
| Unknown  | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 61.11%  |
| WiFi     | 34        | 37.78%  |
| Unknown  | 1         | 1.11%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 46        | 55.42%  |
| 2     | 30        | 36.14%  |
| 3     | 4         | 4.82%   |
| 0     | 2         | 2.41%   |
| 4     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 86.59%  |
| Yes  | 11        | 13.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 19        | 44.19%  |
| Cambridge Silicon Radio | 8         | 18.6%   |
| Broadcom                | 3         | 6.98%   |
| ASUSTek Computer        | 3         | 6.98%   |
| Realtek Semiconductor   | 2         | 4.65%   |
| IMC Networks            | 2         | 4.65%   |
| Marvell Semiconductor   | 1         | 2.33%   |
| Lite-On Technology      | 1         | 2.33%   |
| Hewlett-Packard         | 1         | 2.33%   |
| Foxconn / Hon Hai       | 1         | 2.33%   |
| Dell                    | 1         | 2.33%   |
| Apple                   | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 20.93%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 18.6%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 9.3%    |
| Realtek Bluetooth Radio                             | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.65%   |
| Intel AX200 Bluetooth                               | 2         | 4.65%   |
| IMC Networks Bluetooth Device                       | 2         | 4.65%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2.33%   |
| Lite-On Bluetooth Device                            | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.33%   |
| Intel Bluetooth Device                              | 1         | 2.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.33%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.33%   |
| Broadcom Bluetooth dongle                           | 1         | 2.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.33%   |
| ASUS Bluetooth Device                               | 1         | 2.33%   |
| ASUS BCM20702A0                                     | 1         | 2.33%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 45.16%  |
| Nvidia                     | 32        | 25.81%  |
| AMD                        | 23        | 18.55%  |
| C-Media Electronics        | 7         | 5.65%   |
| Samsung Electronics        | 1         | 0.81%   |
| Mackie Designs             | 1         | 0.81%   |
| Logitech                   | 1         | 0.81%   |
| Corsair                    | 1         | 0.81%   |
| BEHRINGER International    | 1         | 0.81%   |
| Altec Lansing Technologies | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 6.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 5.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 4.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 3.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 2.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.88%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 2.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.16%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3         | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.16%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.44%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.44%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.44%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.44%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.44%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.44%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.44%   |
| Samsung Electronics USB C Earphones                                        | 1         | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.72%   |
| Mackie Designs ProFX                                                       | 1         | 0.72%   |
| Logitech Headset H340                                                      | 1         | 0.72%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.72%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 0.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 0.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.72%   |
| Corsair Corsair ST100 Headset Output                                      | 1         | 0.72%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.72%   |
| BEHRINGER International UMC404HD 192k                                      | 1         | 0.72%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 0.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 13        | 24.53%  |
| Samsung Electronics | 8         | 15.09%  |
| Unknown             | 7         | 13.21%  |
| G.Skill             | 6         | 11.32%  |
| SK Hynix            | 4         | 7.55%   |
| Micron Technology   | 4         | 7.55%   |
| Corsair             | 3         | 5.66%   |
| Team                | 2         | 3.77%   |
| Crucial             | 2         | 3.77%   |
| Unknown (ABCD)      | 1         | 1.89%   |
| Smart               | 1         | 1.89%   |
| Nanya Technology    | 1         | 1.89%   |
| GOODRAM             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX2400C15/16G 16384MB DIMM DDR4 3334MT/s         | 2         | 3.45%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s        | 2         | 3.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 1         | 1.72%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1         | 1.72%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                         | 1         | 1.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 1.72%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 1         | 1.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                  | 1         | 1.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1         | 1.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1         | 1.72%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 1         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR3 2400MT/s | 1         | 1.72%   |
| Team RAM Elite-16 4GB DIMM DDR3 1600MT/s                       | 1         | 1.72%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                     | 1         | 1.72%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                   | 1         | 1.72%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.72%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.72%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1.72%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.72%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s            | 1         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.72%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.72%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s       | 1         | 1.72%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s           | 1         | 1.72%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s         | 1         | 1.72%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4096MB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 1         | 1.72%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s       | 1         | 1.72%   |
| Micron RAM 18JSF51272AZ-1G6M 4GB DIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s         | 1         | 1.72%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 1         | 1.72%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 1         | 1.72%   |
| Kingston RAM KHX2133C11D3/8GX 8GB DIMM DDR3 2133MT/s           | 1         | 1.72%   |
| Kingston RAM KHX1600C9D3/8G 8192MB DIMM DDR3 1600MT/s          | 1         | 1.72%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 1         | 1.72%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s               | 1         | 1.72%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 1.72%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s         | 1         | 1.72%   |
| Kingston RAM 99U5584-009.A00LF 4096MB DIMM DDR3 1600MT/s       | 1         | 1.72%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s           | 1         | 1.72%   |
| Kingston RAM 9905624-054.A00G 8GB SODIMM DDR4 2400MT/s         | 1         | 1.72%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 1.72%   |
| GOODRAM RAM GY1600D364L10/8G 8192MB DIMM DDR3 1600MT/s         | 1         | 1.72%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 1         | 1.72%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 1         | 1.72%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 1         | 1.72%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s             | 1         | 1.72%   |
| Crucial RAM CT51264BA1339.D16F 4GB DIMM DDR3 1333MT/s          | 1         | 1.72%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s     | 1         | 1.72%   |
| Corsair RAM CMZ32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s           | 1         | 1.72%   |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s      | 1         | 1.72%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s        | 1         | 1.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 44.68%  |
| DDR4    | 19        | 40.43%  |
| Unknown | 3         | 6.38%   |
| DDR2    | 2         | 4.26%   |
| LPDDR4  | 1         | 2.13%   |
| LPDDR3  | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 28        | 59.57%  |
| SODIMM       | 18        | 38.3%   |
| Row Of Chips | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 42%     |
| 4096  | 18        | 36%     |
| 16384 | 6         | 12%     |
| 2048  | 5         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 15        | 29.41%  |
| 2133  | 6         | 11.76%  |
| 2400  | 5         | 9.8%    |
| 3200  | 4         | 7.84%   |
| 1333  | 4         | 7.84%   |
| 3334  | 2         | 3.92%   |
| 2667  | 2         | 3.92%   |
| 1867  | 2         | 3.92%   |
| 667   | 2         | 3.92%   |
| 3733  | 1         | 1.96%   |
| 3600  | 1         | 1.96%   |
| 3500  | 1         | 1.96%   |
| 3466  | 1         | 1.96%   |
| 2933  | 1         | 1.96%   |
| 1334  | 1         | 1.96%   |
| 1066  | 1         | 1.96%   |
| 975   | 1         | 1.96%   |
| 800   | 1         | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Xerox               | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155   | 1         | 20%     |
| Samsung CLP-300 Series       | 1         | 20%     |
| HP OfficeJet 6950            | 1         | 20%     |
| Canon PIXMA MG3600 Series    | 1         | 20%     |
| Brother QL-570 Label Printer | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 1         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500]  | 1         | 33.33%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 29.41%  |
| Microdia                               | 5         | 14.71%  |
| Logitech                               | 4         | 11.76%  |
| Realtek Semiconductor                  | 2         | 5.88%   |
| Microsoft                              | 2         | 5.88%   |
| IMC Networks                           | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Apple                                  | 2         | 5.88%   |
| Suyin                                  | 1         | 2.94%   |
| Sunplus Innovation Technology          | 1         | 2.94%   |
| Primax Electronics                     | 1         | 2.94%   |
| Leap Motion                            | 1         | 2.94%   |
| Alcor Micro                            | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 3         | 8.57%   |
| Microdia Camera                                     | 2         | 5.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 5.71%   |
| Chicony USB2.0 Camera                               | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 5.71%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 2.86%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.86%   |
| Realtek USB Camera                                  | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.86%   |
| Primax HP Truevision FHD                            | 1         | 2.86%   |
| Microsoft LifeCam VX-800                            | 1         | 2.86%   |
| Microsoft LifeCam HD-3000                           | 1         | 2.86%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.86%   |
| Microdia Integrated Webcam                          | 1         | 2.86%   |
| Logitech Webcam C210                                | 1         | 2.86%   |
| Logitech Webcam C200                                | 1         | 2.86%   |
| Logitech Webcam C110                                | 1         | 2.86%   |
| Logitech QuickCam Pro 9000                          | 1         | 2.86%   |
| Leap Motion Controller                              | 1         | 2.86%   |
| Chicony TOSHIBA Web Camera - FHD                    | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                           | 1         | 2.86%   |
| Chicony Integrated IR Camera                        | 1         | 2.86%   |
| Chicony HD WebCam                                   | 1         | 2.86%   |
| Chicony FJ Camera                                   | 1         | 2.86%   |
| Chicony 1.3M HD WebCam                              | 1         | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 2.86%   |
| Apple Built-in iSight                               | 1         | 2.86%   |
| Alcor Micro USB 2.0 Web Camera                      | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 50%     |
| Shenzhen Goodix Technology | 2         | 33.33%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI            | 1         | 16.67%  |
| Validity Sensors Fingerprint scanner       | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader         | 1         | 16.67%  |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 50%     |
| O2 Micro | 1         | 25%     |
| Avtor    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Avtor SecureToken                                                            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 69.88%  |
| 1     | 20        | 24.1%   |
| 2     | 4         | 4.82%   |
| 3     | 1         | 1.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 37.04%  |
| Fingerprint reader       | 6         | 22.22%  |
| Chipcard                 | 4         | 14.81%  |
| Multimedia controller    | 3         | 11.11%  |
| Unassigned class         | 1         | 3.7%    |
| Sound                    | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |
| Camera                   | 1         | 3.7%    |

