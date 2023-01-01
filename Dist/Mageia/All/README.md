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

Total: 162

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP        | Unknown                     | Notebook    | [702ed67add](https://linux-hardware.org/?probe=702ed67add) | Dec 17, 2022 |
| HP        | Unknown                     | Notebook    | [d952fd785e](https://linux-hardware.org/?probe=d952fd785e) | Dec 17, 2022 |
| Fujitsu   | CELSIUS H720                | Notebook    | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| Lenovo    | ThinkCentre A57 970274G     | Desktop     | [809e137f17](https://linux-hardware.org/?probe=809e137f17) | Nov 02, 2022 |
| MSI       | B360I GMAING PRO AC         | Desktop     | [2584a31610](https://linux-hardware.org/?probe=2584a31610) | Oct 12, 2022 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [8d0d1ba821](https://linux-hardware.org/?probe=8d0d1ba821) | Oct 12, 2022 |
| MSI       | B360I GMAING PRO AC         | Desktop     | [bbdf7b4f77](https://linux-hardware.org/?probe=bbdf7b4f77) | Oct 01, 2022 |
| Irbis     | NB264                       | Notebook    | [103ca2d20b](https://linux-hardware.org/?probe=103ca2d20b) | Sep 16, 2022 |
| ASRock    | B550M-HDV                   | Desktop     | [c786c365d5](https://linux-hardware.org/?probe=c786c365d5) | Sep 06, 2022 |
| ASUSTek   | X751LN                      | Notebook    | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| ASUSTek   | M5A99FX PRO R2.0            | Desktop     | [d14ad254ca](https://linux-hardware.org/?probe=d14ad254ca) | Jul 05, 2022 |
| Schenker  | VIA_14_SVI14E20             | Notebook    | [3adb69bbf5](https://linux-hardware.org/?probe=3adb69bbf5) | Jun 03, 2022 |
| Notebook  | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [e30e3da709](https://linux-hardware.org/?probe=e30e3da709) | May 18, 2022 |
| Dell      | Latitude E5570              | Notebook    | [ec640c6644](https://linux-hardware.org/?probe=ec640c6644) | May 12, 2022 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [9f255eb7d5](https://linux-hardware.org/?probe=9f255eb7d5) | May 06, 2022 |
| ASUSTek   | F1A75-M LE                  | Desktop     | [93232d0716](https://linux-hardware.org/?probe=93232d0716) | May 01, 2022 |
| Microsoft | Surface Pro 4               | Tablet      | [4e74006288](https://linux-hardware.org/?probe=4e74006288) | Apr 21, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | Notebook    | [086a94d83c](https://linux-hardware.org/?probe=086a94d83c) | Apr 15, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Megaware  | MW-G31T-M7                  | Desktop     | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte  | H81M-S2H                    | Desktop     | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| MSI       | Z590-A PRO                  | Desktop     | [229ed42b3d](https://linux-hardware.org/?probe=229ed42b3d) | Apr 03, 2022 |
| Toshiba   | dynabook R73/A              | Notebook    | [42b60c90c7](https://linux-hardware.org/?probe=42b60c90c7) | Apr 01, 2022 |
| Gigabyte  | GA-78LMT-USB3 SEx           | Desktop     | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Gigabyte  | G31M-S2C                    | Desktop     | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
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
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Dell      | Latitude E5570              | Notebook    | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell      | Latitude E5570              | Notebook    | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell      | Precision 5530              | Notebook    | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Dell      | 0TP412                      | Desktop     | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Apple     | Mac-F42386C8 PVT            | All in one  | [3235b7d95a](https://linux-hardware.org/?probe=3235b7d95a) | Sep 24, 2021 |
| Dell      | 0TP412                      | Desktop     | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI       | MAG B460M MORTAR            | Desktop     | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
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
| ASUSTek   | X751LN                      | Notebook    | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| Intel     | STL2-bd A28808-302          | Desktop     | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP        | 212B                        | Desktop     | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| ASUSTek   | X556URK                     | Notebook    | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASUSTek   | X751LN                      | Notebook    | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| ASRock    | M3A UCC                     | Desktop     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP        | 339A                        | Desktop     | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| Dell      | Latitude E6530              | Notebook    | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Gigabyte  | H81M-S2H                    | Desktop     | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Dell      | Inspiron 5480               | Notebook    | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano     | SlimNote 15.6               | Notebook    | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek   | Z87-DELUXE                  | Desktop     | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek   | X751LN                      | Notebook    | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| HP        | 339A                        | Desktop     | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| ASUSTek   | ROG ZENITH EXTREME          | Desktop     | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock    | H87M Pro4                   | Desktop     | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte  | F2A88XM-DS2                 | Desktop     | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| HP        | Spectre 13 Ultrabook        | Notebook    | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| Gigabyte  | H81M-S2H                    | Desktop     | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Gigabyte  | GA-78LMT-USB3 R2            | Desktop     | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| ASUSTek   | PRIME B360-PLUS             | Desktop     | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | Notebook    | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP        | ProBook 445 G7              | Notebook    | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| MSI       | MPG X570 GAMING EDGE WIF... | Desktop     | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Acer      | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Dell      | Inspiron 5480               | Notebook    | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC     | Unknown                     | Desktop     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte  | H170-D3H-CF                 | Desktop     | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Lenovo    | ThinkServer TS140           | Desktop     | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| HP        | Unknown                     | Notebook    | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer      | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP        | Pavilion dv6                | Notebook    | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock    | M3A UCC                     | Desktop     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Lenovo    | G480 20149                  | Notebook    | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock    | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP        | 339A                        | Desktop     | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP        | 339A                        | Desktop     | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| MSI       | B360M MORTAR                | Desktop     | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | Desktop     | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek   | H170M-PLUS                  | Desktop     | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek   | PRIME A320M-K               | Desktop     | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke     | V1 Plus                     | Desktop     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
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

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Mageia 8 | 55        | 55%     |
| Mageia 7 | 33        | 33%     |
| Mageia 9 | 7         | 7%      |
| Mageia 6 | 4         | 4%      |
| Mageia 5 | 1         | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Mageia | 88        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 13        | 10.08%  |
| 5.10.27-desktop-1.mga8 | 8         | 6.2%    |
| 5.7.19-desktop-1.mga7  | 7         | 5.43%   |
| 5.15.32-desktop-1.mga8 | 5         | 3.88%   |
| 5.6.14-desktop-2.mga7  | 4         | 3.1%    |
| 5.5.4-desktop-1.mga7   | 4         | 3.1%    |
| 5.15.23-desktop-1.mga8 | 4         | 3.1%    |
| 5.10.25-desktop-1.mga8 | 4         | 3.1%    |
| 5.5.9-desktop-1.mga7   | 3         | 2.33%   |
| 5.10.12-desktop-1.mga7 | 3         | 2.33%   |
| 5.6.6-desktop-1.mga7   | 2         | 1.55%   |
| 5.3.7-desktop-4.mga7   | 2         | 1.55%   |
| 5.17.4-desktop-2.mga8  | 2         | 1.55%   |
| 5.16.10-desktop-2.mga8 | 2         | 1.55%   |
| 5.15.4-desktop-1.mga8  | 2         | 1.55%   |
| 5.15.35-desktop-2.mga8 | 2         | 1.55%   |
| 5.15.16-desktop-1.mga8 | 2         | 1.55%   |
| 5.15.11-desktop-3.mga8 | 2         | 1.55%   |
| 5.10.60-desktop-2.mga8 | 2         | 1.55%   |
| 5.10.52-desktop-1.mga8 | 2         | 1.55%   |
| 5.10.20-desktop-2.mga7 | 2         | 1.55%   |
| 5.10.14-desktop-1.mga7 | 2         | 1.55%   |
| 6.0.10-desktop-1.mga9  | 1         | 0.78%   |
| 5.9.6-desktop-1.mga8   | 1         | 0.78%   |
| 5.9.3-desktop-1.mga8   | 1         | 0.78%   |
| 5.9.16-desktop-1.mga7  | 1         | 0.78%   |
| 5.9.11-desktop-3.mga8  | 1         | 0.78%   |
| 5.9.1-desktop-1.mga8   | 1         | 0.78%   |
| 5.8.5-desktop-2.mga8   | 1         | 0.78%   |
| 5.8.14-desktop-1.mga8  | 1         | 0.78%   |
| 5.7.8-desktop-1.mga8   | 1         | 0.78%   |
| 5.6.8-desktop-1.mga7   | 1         | 0.78%   |
| 5.5.13-desktop-1.mga7  | 1         | 0.78%   |
| 5.4.8-desktop-1.mga7   | 1         | 0.78%   |
| 5.4.12-desktop-1.mga7  | 1         | 0.78%   |
| 5.3.13-desktop-2.mga7  | 1         | 0.78%   |
| 5.19.12-desktop-1.mga9 | 1         | 0.78%   |
| 5.18.15-desktop-1.mga8 | 1         | 0.78%   |
| 5.16.18-server-1.mga8  | 1         | 0.78%   |
| 5.16.18-desktop-1.mga8 | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.19  | 18        | 14.17%  |
| 5.10.27 | 8         | 6.3%    |
| 5.15.32 | 5         | 3.94%   |
| 5.6.14  | 4         | 3.15%   |
| 5.5.4   | 4         | 3.15%   |
| 5.15.23 | 4         | 3.15%   |
| 5.10.25 | 4         | 3.15%   |
| 5.10.12 | 4         | 3.15%   |
| 5.5.9   | 3         | 2.36%   |
| 5.6.6   | 2         | 1.57%   |
| 5.3.7   | 2         | 1.57%   |
| 5.17.4  | 2         | 1.57%   |
| 5.16.18 | 2         | 1.57%   |
| 5.16.10 | 2         | 1.57%   |
| 5.15.4  | 2         | 1.57%   |
| 5.15.35 | 2         | 1.57%   |
| 5.15.16 | 2         | 1.57%   |
| 5.15.11 | 2         | 1.57%   |
| 5.10.60 | 2         | 1.57%   |
| 5.10.52 | 2         | 1.57%   |
| 5.10.20 | 2         | 1.57%   |
| 5.10.16 | 2         | 1.57%   |
| 5.10.14 | 2         | 1.57%   |
| 6.0.10  | 1         | 0.79%   |
| 5.9.6   | 1         | 0.79%   |
| 5.9.3   | 1         | 0.79%   |
| 5.9.16  | 1         | 0.79%   |
| 5.9.11  | 1         | 0.79%   |
| 5.9.1   | 1         | 0.79%   |
| 5.8.5   | 1         | 0.79%   |
| 5.8.14  | 1         | 0.79%   |
| 5.7.8   | 1         | 0.79%   |
| 5.6.8   | 1         | 0.79%   |
| 5.5.13  | 1         | 0.79%   |
| 5.4.8   | 1         | 0.79%   |
| 5.4.12  | 1         | 0.79%   |
| 5.3.13  | 1         | 0.79%   |
| 5.19.12 | 1         | 0.79%   |
| 5.18.15 | 1         | 0.79%   |
| 5.15.79 | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 23.08%  |
| 5.15    | 25        | 21.37%  |
| 5.7     | 19        | 16.24%  |
| 5.5     | 8         | 6.84%   |
| 5.6     | 7         | 5.98%   |
| 5.9     | 5         | 4.27%   |
| 5.16    | 4         | 3.42%   |
| 4.14    | 3         | 2.56%   |
| 5.8     | 2         | 1.71%   |
| 5.4     | 2         | 1.71%   |
| 5.3     | 2         | 1.71%   |
| 5.17    | 2         | 1.71%   |
| 5.14    | 2         | 1.71%   |
| 6.0     | 1         | 0.85%   |
| 5.19    | 1         | 0.85%   |
| 5.18    | 1         | 0.85%   |
| 5.13    | 1         | 0.85%   |
| 5.12    | 1         | 0.85%   |
| 5.1     | 1         | 0.85%   |
| 4.9     | 1         | 0.85%   |
| 4.19    | 1         | 0.85%   |
| 4.1     | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 86        | 97.73%  |
| i686   | 2         | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 36        | 36.36%  |
| KDE           | 23        | 23.23%  |
| GNOME         | 10        | 10.1%   |
| Unknown       | 9         | 9.09%   |
| XFCE          | 5         | 5.05%   |
| Cinnamon      | 5         | 5.05%   |
| MATE          | 4         | 4.04%   |
| LXDE          | 3         | 3.03%   |
| X-Cinnamon    | 1         | 1.01%   |
| LXQt          | 1         | 1.01%   |
| KDE4          | 1         | 1.01%   |
| GNOME Classic | 1         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 84        | 94.38%  |
| Wayland | 4         | 4.49%   |
| Tty     | 1         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 52.81%  |
| SDDM    | 32        | 35.96%  |
| LightDM | 5         | 5.62%   |
| TDM     | 3         | 3.37%   |
| XDM     | 1         | 1.12%   |
| GDM     | 1         | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| fr_FR   | 18        | 20%     |
| en_US   | 15        | 16.67%  |
| de_DE   | 10        | 11.11%  |
| Unknown | 8         | 8.89%   |
| ru_RU   | 7         | 7.78%   |
| en_GB   | 7         | 7.78%   |
| pt_BR   | 4         | 4.44%   |
| it_IT   | 4         | 4.44%   |
| sv_SE   | 2         | 2.22%   |
| pl_PL   | 2         | 2.22%   |
| es_GT   | 2         | 2.22%   |
| en_CA   | 2         | 2.22%   |
| zh_TW   | 1         | 1.11%   |
| sl_SI   | 1         | 1.11%   |
| hu_HU   | 1         | 1.11%   |
| fr_BE   | 1         | 1.11%   |
| es_MX   | 1         | 1.11%   |
| es_ES   | 1         | 1.11%   |
| es_AR   | 1         | 1.11%   |
| cs_CZ   | 1         | 1.11%   |
| bg_BG   | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 57.61%  |
| EFI  | 39        | 42.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 73        | 81.11%  |
| Xfs      | 7         | 7.78%   |
| Unknown  | 6         | 6.67%   |
| Btrfs    | 3         | 3.33%   |
| Reiserfs | 1         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 41.3%   |
| GPT     | 35        | 38.04%  |
| MBR     | 19        | 20.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 85.23%  |
| Yes       | 13        | 14.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 78.02%  |
| Yes       | 20        | 21.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 19        | 21.59%  |
| Gigabyte Technology | 16        | 18.18%  |
| Hewlett-Packard     | 9         | 10.23%  |
| MSI                 | 7         | 7.95%   |
| Lenovo              | 7         | 7.95%   |
| Dell                | 6         | 6.82%   |
| ASRock              | 6         | 6.82%   |
| Notebook            | 2         | 2.27%   |
| Medion              | 2         | 2.27%   |
| Fujitsu             | 2         | 2.27%   |
| Acer                | 2         | 2.27%   |
| ZOTAC               | 1         | 1.14%   |
| Vorke               | 1         | 1.14%   |
| Toshiba             | 1         | 1.14%   |
| Schenker            | 1         | 1.14%   |
| Microsoft           | 1         | 1.14%   |
| Megaware            | 1         | 1.14%   |
| Kiano               | 1         | 1.14%   |
| Intel               | 1         | 1.14%   |
| ECS                 | 1         | 1.14%   |
| Apple               | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 3.41%   |
| Gigabyte Z68X-UD3H-B3                    | 2         | 2.27%   |
| Dell Precision WorkStation T3400         | 2         | 2.27%   |
| ASUS SABERTOOTH 990FX R2.0               | 2         | 2.27%   |
| Vorke V1 Plus                            | 1         | 1.14%   |
| Toshiba dynabook R73/A                   | 1         | 1.14%   |
| Schenker VIA_14_SVI14E20                 | 1         | 1.14%   |
| Notebook NL40_50GU                       | 1         | 1.14%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 1.14%   |
| MSI MS-7D09                              | 1         | 1.14%   |
| MSI MS-7C82                              | 1         | 1.14%   |
| MSI MS-7C37                              | 1         | 1.14%   |
| MSI MS-7B31                              | 1         | 1.14%   |
| MSI MS-7B23                              | 1         | 1.14%   |
| MSI MS-7A70                              | 1         | 1.14%   |
| MSI MS-7816                              | 1         | 1.14%   |
| Microsoft Surface Pro 4                  | 1         | 1.14%   |
| Megaware MW-G31T-M7                      | 1         | 1.14%   |
| Medion MD34161/C708                      | 1         | 1.14%   |
| Medion DEFENDER P10                      | 1         | 1.14%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 1.14%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 1.14%   |
| Lenovo ThinkCentre M58e 7491B1G          | 1         | 1.14%   |
| Lenovo ThinkCentre A57 970274G           | 1         | 1.14%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.14%   |
| Lenovo G480 20149                        | 1         | 1.14%   |
| Lenovo 70A4000HUX ThinkServer TS140      | 1         | 1.14%   |
| Kiano SlimNote 15.6                      | 1         | 1.14%   |
| Intel STL2                               | 1         | 1.14%   |
| HP Z440 Workstation                      | 1         | 1.14%   |
| HP Z420 Workstation                      | 1         | 1.14%   |
| HP Spectre 13 Ultrabook                  | 1         | 1.14%   |
| HP ProBook 445 G7                        | 1         | 1.14%   |
| HP Pavilion dv6                          | 1         | 1.14%   |
| HP EliteBook 840 G3                      | 1         | 1.14%   |
| HP Compaq Pro 6300 SFF                   | 1         | 1.14%   |
| Gigabyte Z87X-UD5H                       | 1         | 1.14%   |
| Gigabyte Z68XP-UD3P                      | 1         | 1.14%   |
| Gigabyte X570 AORUS ELITE WIFI           | 1         | 1.14%   |
| Gigabyte H81M-S2H                        | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Precision         | 3         | 3.41%   |
| ASUS SABERTOOTH        | 3         | 3.41%   |
| ASUS PRIME             | 3         | 3.41%   |
| Unknown                | 3         | 3.41%   |
| Lenovo ThinkPad        | 2         | 2.27%   |
| Lenovo ThinkCentre     | 2         | 2.27%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 2.27%   |
| Gigabyte GA-78LMT-USB3 | 2         | 2.27%   |
| Dell Latitude          | 2         | 2.27%   |
| Acer Aspire            | 2         | 2.27%   |
| Vorke V1               | 1         | 1.14%   |
| Toshiba dynabook       | 1         | 1.14%   |
| Schenker VIA           | 1         | 1.14%   |
| Notebook NL40          | 1         | 1.14%   |
| Notebook NH5x          | 1         | 1.14%   |
| MSI MS-7D09            | 1         | 1.14%   |
| MSI MS-7C82            | 1         | 1.14%   |
| MSI MS-7C37            | 1         | 1.14%   |
| MSI MS-7B31            | 1         | 1.14%   |
| MSI MS-7B23            | 1         | 1.14%   |
| MSI MS-7A70            | 1         | 1.14%   |
| MSI MS-7816            | 1         | 1.14%   |
| Microsoft Surface      | 1         | 1.14%   |
| Megaware MW-G31T-M7    | 1         | 1.14%   |
| Medion MD34161         | 1         | 1.14%   |
| Medion DEFENDER        | 1         | 1.14%   |
| Lenovo IdeaPad         | 1         | 1.14%   |
| Lenovo G480            | 1         | 1.14%   |
| Lenovo 70A4000HUX      | 1         | 1.14%   |
| Kiano SlimNote         | 1         | 1.14%   |
| Intel STL2             | 1         | 1.14%   |
| HP Z440                | 1         | 1.14%   |
| HP Z420                | 1         | 1.14%   |
| HP Spectre             | 1         | 1.14%   |
| HP ProBook             | 1         | 1.14%   |
| HP Pavilion            | 1         | 1.14%   |
| HP EliteBook           | 1         | 1.14%   |
| HP Compaq              | 1         | 1.14%   |
| Gigabyte Z87X-UD5H     | 1         | 1.14%   |
| Gigabyte Z68XP-UD3P    | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 12        | 13.64%  |
| 2012 | 12        | 13.64%  |
| 2018 | 10        | 11.36%  |
| 2017 | 7         | 7.95%   |
| 2016 | 6         | 6.82%   |
| 2008 | 6         | 6.82%   |
| 2020 | 5         | 5.68%   |
| 2019 | 5         | 5.68%   |
| 2014 | 5         | 5.68%   |
| 2015 | 4         | 4.55%   |
| 2011 | 4         | 4.55%   |
| 2009 | 4         | 4.55%   |
| 2010 | 3         | 3.41%   |
| 2021 | 2         | 2.27%   |
| 2007 | 2         | 2.27%   |
| 2002 | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 59        | 67.05%  |
| Notebook   | 27        | 30.68%  |
| Tablet     | 1         | 1.14%   |
| All in one | 1         | 1.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 88        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 24        | 26.09%  |
| 4.01-8.0    | 18        | 19.57%  |
| 8.01-16.0   | 17        | 18.48%  |
| 32.01-64.0  | 13        | 14.13%  |
| 3.01-4.0    | 13        | 14.13%  |
| 64.01-256.0 | 4         | 4.35%   |
| 24.01-32.0  | 2         | 2.17%   |
| 2.01-3.0    | 1         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 29.63%  |
| 1.01-2.0   | 29        | 26.85%  |
| 4.01-8.0   | 20        | 18.52%  |
| 3.01-4.0   | 17        | 15.74%  |
| 8.01-16.0  | 6         | 5.56%   |
| 0.51-1.0   | 3         | 2.78%   |
| 16.01-24.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 38.71%  |
| 2      | 25        | 26.88%  |
| 3      | 18        | 19.35%  |
| 5      | 6         | 6.45%   |
| 4      | 4         | 4.3%    |
| 6      | 2         | 2.15%   |
| 8      | 1         | 1.08%   |
| 7      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 52.27%  |
| Yes       | 42        | 47.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 89.77%  |
| No        | 9         | 10.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 53.93%  |
| No        | 41        | 46.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 52.27%  |
| No        | 42        | 47.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 19        | 21.59%  |
| USA         | 12        | 13.64%  |
| Germany     | 10        | 11.36%  |
| UK          | 7         | 7.95%   |
| Russia      | 4         | 4.55%   |
| Italy       | 4         | 4.55%   |
| Brazil      | 4         | 4.55%   |
| Ukraine     | 3         | 3.41%   |
| Canada      | 3         | 3.41%   |
| Sweden      | 2         | 2.27%   |
| Poland      | 2         | 2.27%   |
| Guatemala   | 2         | 2.27%   |
| Greece      | 2         | 2.27%   |
| Taiwan      | 1         | 1.14%   |
| Slovenia    | 1         | 1.14%   |
| Romania     | 1         | 1.14%   |
| Netherlands | 1         | 1.14%   |
| Mexico      | 1         | 1.14%   |
| Luxembourg  | 1         | 1.14%   |
| Kenya       | 1         | 1.14%   |
| Indonesia   | 1         | 1.14%   |
| Czechia     | 1         | 1.14%   |
| Colombia    | 1         | 1.14%   |
| Bulgaria    | 1         | 1.14%   |
| Belgium     | 1         | 1.14%   |
| Belarus     | 1         | 1.14%   |
| Argentina   | 1         | 1.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Rommerskirchen        | 3         | 2.73%   |
| Paris                 | 3         | 2.73%   |
| Mala Danylivka        | 3         | 2.73%   |
| Kharkiv               | 3         | 2.73%   |
| Woking                | 2         | 1.82%   |
| Woincourt             | 2         | 1.82%   |
| Waterloo              | 2         | 1.82%   |
| Upper Norwood         | 2         | 1.82%   |
| Strasbourg            | 2         | 1.82%   |
| Sao Paulo             | 2         | 1.82%   |
| Oakland               | 2         | 1.82%   |
| Guatemala City        | 2         | 1.82%   |
| Grants Pass           | 2         | 1.82%   |
| Yakutsk               | 1         | 0.91%   |
| Wiwersheim            | 1         | 0.91%   |
| Voronezh              | 1         | 0.91%   |
| Vanves                | 1         | 0.91%   |
| Uzhhorod              | 1         | 0.91%   |
| Tver                  | 1         | 0.91%   |
| Turin                 | 1         | 0.91%   |
| Tours                 | 1         | 0.91%   |
| Toulouse              | 1         | 0.91%   |
| Thiais                | 1         | 0.91%   |
| Surabaya              | 1         | 0.91%   |
| Sternberk             | 1         | 0.91%   |
| Sartrouville          | 1         | 0.91%   |
| Sant'Angelo Lodigiano | 1         | 0.91%   |
| San Isidro            | 1         | 0.91%   |
| Saint-Michel-sur-Orge | 1         | 0.91%   |
| Rome                  | 1         | 0.91%   |
| Roehampton            | 1         | 0.91%   |
| Rio de Janeiro        | 1         | 0.91%   |
| Regina                | 1         | 0.91%   |
| Quierschied           | 1         | 0.91%   |
| Quaregna              | 1         | 0.91%   |
| Poznan                | 1         | 0.91%   |
| Pouldergat            | 1         | 0.91%   |
| Pont-l'Abbe-d'Arnoult | 1         | 0.91%   |
| Perm                  | 1         | 0.91%   |
| Oxford                | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 40        | 118    | 22.73%  |
| Seagate                 | 26        | 45     | 14.77%  |
| Samsung Electronics     | 24        | 30     | 13.64%  |
| Kingston                | 13        | 22     | 7.39%   |
| Toshiba                 | 10        | 18     | 5.68%   |
| SanDisk                 | 8         | 14     | 4.55%   |
| Hitachi                 | 7         | 7      | 3.98%   |
| Unknown                 | 6         | 6      | 3.41%   |
| Crucial                 | 6         | 10     | 3.41%   |
| PNY                     | 5         | 7      | 2.84%   |
| HGST                    | 4         | 8      | 2.27%   |
| Intel                   | 3         | 3      | 1.7%    |
| SK hynix                | 2         | 3      | 1.14%   |
| Phison                  | 2         | 3      | 1.14%   |
| OCZ-VERTEX              | 2         | 2      | 1.14%   |
| OCZ                     | 2         | 2      | 1.14%   |
| A-DATA Technology       | 2         | 5      | 1.14%   |
| XPG                     | 1         | 4      | 0.57%   |
| Verbatim                | 1         | 1      | 0.57%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.57%   |
| Transcend               | 1         | 1      | 0.57%   |
| TO Exter                | 1         | 1      | 0.57%   |
| Team                    | 1         | 1      | 0.57%   |
| PNY CS90                | 1         | 1      | 0.57%   |
| LDLC                    | 1         | 1      | 0.57%   |
| JMicron Technology      | 1         | 1      | 0.57%   |
| HUAWEI                  | 1         | 1      | 0.57%   |
| FORESEE                 | 1         | 1      | 0.57%   |
| Corsair                 | 1         | 1      | 0.57%   |
| China                   | 1         | 1      | 0.57%   |
| ASMedia                 | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4         | 2%      |
| WDC WD10EZEX-08WN4A0 1TB         | 3         | 1.5%    |
| Samsung SSD 860 EVO 500GB        | 3         | 1.5%    |
| Samsung SSD 860 EVO 250GB        | 3         | 1.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 1%      |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2         | 1%      |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 1%      |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2         | 1%      |
| WDC WD20EFRX-68EUZN0 2TB         | 2         | 1%      |
| WDC WD10EZRZ-00HTKB0 1TB         | 2         | 1%      |
| WDC WD10EFRX-68PJCN0 1TB         | 2         | 1%      |
| Toshiba HDWD120 2TB              | 2         | 1%      |
| Seagate ST3500418AS 500GB        | 2         | 1%      |
| Seagate ST32000644NS 2TB         | 2         | 1%      |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 1%      |
| SanDisk SDSSDA120G 120GB         | 2         | 1%      |
| SanDisk Extreme SSD 500GB        | 2         | 1%      |
| Samsung SSD 850 EVO 500GB        | 2         | 1%      |
| Samsung NVMe SSD Drive 500GB     | 2         | 1%      |
| PNY CS900 120GB SSD              | 2         | 1%      |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2         | 1%      |
| Kingston SV300S37A240G 240GB SSD | 2         | 1%      |
| Kingston SH103S3120G 120GB SSD   | 2         | 1%      |
| Kingston SA400S37120G 120GB SSD  | 2         | 1%      |
| Intel SSDSC2CW120A3 120GB        | 2         | 1%      |
| Hitachi HDS722020ALA330 2TB      | 2         | 1%      |
| HGST HUS726040ALE611 4TB         | 2         | 1%      |
| Crucial CT500MX500SSD1 500GB     | 2         | 1%      |
| Crucial CT120BX500SSD1 120GB     | 2         | 1%      |
| XPG NVMe SSD Drive 2TB           | 1         | 0.5%    |
| XPG NVMe SSD Drive 1024GB        | 1         | 0.5%    |
| WDC WDS500G3XHC-00SJG0 500GB     | 1         | 0.5%    |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.5%    |
| WDC WDS100T2B0A 1TB SSD          | 1         | 0.5%    |
| WDC WD800BB-00JHC0 80GB          | 1         | 0.5%    |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 0.5%    |
| WDC WD5000AADS-00S9B0 500GB      | 1         | 0.5%    |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.5%    |
| WDC WD4000FYYZ-01UL1B2 4TB       | 1         | 0.5%    |
| WDC WD3200KS-00PFB0 320GB        | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 99     | 38.1%   |
| Seagate             | 25        | 41     | 29.76%  |
| Toshiba             | 9         | 17     | 10.71%  |
| Hitachi             | 7         | 7      | 8.33%   |
| Samsung Electronics | 5         | 7      | 5.95%   |
| HGST                | 4         | 8      | 4.76%   |
| Unknown             | 2         | 2      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 21.43%  |
| Kingston            | 10        | 16     | 14.29%  |
| WDC                 | 7         | 17     | 10%     |
| SanDisk             | 6         | 8      | 8.57%   |
| Crucial             | 6         | 10     | 8.57%   |
| PNY                 | 5         | 7      | 7.14%   |
| Intel               | 3         | 3      | 4.29%   |
| OCZ-VERTEX          | 2         | 2      | 2.86%   |
| OCZ                 | 2         | 2      | 2.86%   |
| A-DATA Technology   | 2         | 5      | 2.86%   |
| Verbatim            | 1         | 1      | 1.43%   |
| Transcend           | 1         | 1      | 1.43%   |
| TO Exter            | 1         | 1      | 1.43%   |
| Team                | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| PNY CS90            | 1         | 1      | 1.43%   |
| LDLC                | 1         | 1      | 1.43%   |
| JMicron Technology  | 1         | 1      | 1.43%   |
| FORESEE             | 1         | 1      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| ASMedia             | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 61        | 181    | 45.19%  |
| SSD     | 50        | 98     | 37.04%  |
| NVMe    | 18        | 32     | 13.33%  |
| MMC     | 4         | 4      | 2.96%   |
| Unknown | 2         | 5      | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 262    | 70.8%   |
| NVMe | 18        | 32     | 15.93%  |
| SAS  | 11        | 22     | 9.73%   |
| MMC  | 4         | 4      | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 117    | 48.84%  |
| 0.51-1.0   | 37        | 89     | 28.68%  |
| 1.01-2.0   | 14        | 22     | 10.85%  |
| 3.01-4.0   | 6         | 15     | 4.65%   |
| 2.01-3.0   | 6         | 30     | 4.65%   |
| 4.01-10.0  | 2         | 5      | 1.55%   |
| 10.01-20.0 | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 22.58%  |
| 501-1000       | 21        | 22.58%  |
| More than 3000 | 16        | 17.2%   |
| 101-250        | 14        | 15.05%  |
| 2001-3000      | 9         | 9.68%   |
| 1001-2000      | 8         | 8.6%    |
| 51-100         | 3         | 3.23%   |
| Unknown        | 1         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 19.61%  |
| 51-100         | 16        | 15.69%  |
| 1-20           | 14        | 13.73%  |
| 251-500        | 12        | 11.76%  |
| 1001-2000      | 12        | 11.76%  |
| 501-1000       | 10        | 9.8%    |
| 21-50          | 8         | 7.84%   |
| More than 3000 | 7         | 6.86%   |
| 2001-3000      | 2         | 1.96%   |
| Unknown        | 1         | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 11.76%  |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 5.88%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 5.88%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 5.88%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 5.88%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 5.88%   |
| Seagate ST3320820AS 320GB             | 1         | 1      | 5.88%   |
| Seagate ST3250410AS 250GB             | 1         | 1      | 5.88%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 5.88%   |
| Seagate ST2000VN004-2E4164 2TB        | 1         | 1      | 5.88%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 5.88%   |
| Samsung Electronics HD400LD 400GB     | 1         | 1      | 5.88%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 5.88%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| WDC                 | 2         | 3      | 12.5%   |
| Intel               | 2         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| OCZ                 | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| WDC                 | 2         | 3      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 73.33%  |
| SSD  | 4         | 4      | 26.67%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 47        | 149    | 43.93%  |
| Detected | 45        | 154    | 42.06%  |
| Malfunc  | 15        | 17     | 14.02%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 59        | 50.86%  |
| AMD                          | 24        | 20.69%  |
| Marvell Technology Group     | 7         | 6.03%   |
| ASMedia Technology           | 6         | 5.17%   |
| Samsung Electronics          | 5         | 4.31%   |
| SanDisk                      | 4         | 3.45%   |
| Phison Electronics           | 3         | 2.59%   |
| Kingston Technology Company  | 3         | 2.59%   |
| Toshiba America Info Systems | 1         | 0.86%   |
| SK hynix                     | 1         | 0.86%   |
| JMicron Technology           | 1         | 0.86%   |
| Broadcom                     | 1         | 0.86%   |
| ADATA Technology             | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 6.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 5.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 3.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 3.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 3.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 3.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 3.47%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 2.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 2.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.08%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 2.08%   |
| AMD SB600 IDE                                                                           | 3         | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.39%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.39%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.39%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.69%   |
| SK hynix BC511                                                                          | 1         | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.69%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.69%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.69%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1         | 0.69%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 71        | 62.28%  |
| IDE  | 21        | 18.42%  |
| NVMe | 17        | 14.91%  |
| RAID | 4         | 3.51%   |
| SAS  | 1         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 71.59%  |
| AMD    | 25        | 28.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 3.37%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 3.37%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2         | 2.25%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 2.25%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2         | 2.25%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2         | 2.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.25%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 2.25%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.25%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 2         | 2.25%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1         | 1.12%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 1.12%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.12%   |
| Intel Pentium III (Coppermine)              | 1         | 1.12%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1         | 1.12%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.12%   |
| Intel Pentium CPU G3450 @ 3.40GHz           | 1         | 1.12%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.12%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.12%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.12%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.12%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.12%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.12%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.12%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.12%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.12%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.12%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 1.12%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1         | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.12%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.12%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.12%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 21.59%  |
| Intel Core i5           | 18        | 20.45%  |
| Intel Core i3           | 6         | 6.82%   |
| AMD FX                  | 6         | 6.82%   |
| Intel Core 2 Duo        | 4         | 4.55%   |
| AMD Ryzen 7             | 4         | 4.55%   |
| AMD Ryzen 5             | 3         | 3.41%   |
| Other                   | 2         | 2.27%   |
| Intel Xeon              | 2         | 2.27%   |
| Intel Pentium Dual-Core | 2         | 2.27%   |
| Intel Pentium           | 2         | 2.27%   |
| Intel Celeron           | 2         | 2.27%   |
| AMD Turion 64 X2 Mobile | 2         | 2.27%   |
| AMD Ryzen Threadripper  | 2         | 2.27%   |
| AMD A8                  | 2         | 2.27%   |
| Intel Pentium Silver    | 1         | 1.14%   |
| Intel Pentium III       | 1         | 1.14%   |
| Intel Pentium Gold      | 1         | 1.14%   |
| Intel Core 2 Quad       | 1         | 1.14%   |
| Intel Core 2            | 1         | 1.14%   |
| Intel Atom              | 1         | 1.14%   |
| AMD Ryzen 9             | 1         | 1.14%   |
| AMD Ryzen 3             | 1         | 1.14%   |
| AMD Phenom II X6        | 1         | 1.14%   |
| AMD Phenom II X4        | 1         | 1.14%   |
| AMD Athlon II X3        | 1         | 1.14%   |
| AMD A10                 | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 37        | 41.57%  |
| 2      | 33        | 37.08%  |
| 6      | 9         | 10.11%  |
| 8      | 5         | 5.62%   |
| 3      | 2         | 2.25%   |
| 32     | 1         | 1.12%   |
| 16     | 1         | 1.12%   |
| 12     | 1         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 98.86%  |
| 2      | 1         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 61.36%  |
| 1      | 34        | 38.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 86        | 95.56%  |
| Unknown        | 3         | 3.33%   |
| 32-bit         | 1         | 1.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 21.05%  |
| 0x306c3    | 8         | 8.42%   |
| 0x306a9    | 6         | 6.32%   |
| 0x206a7    | 6         | 6.32%   |
| 0x1067a    | 4         | 4.21%   |
| 0x806e9    | 3         | 3.16%   |
| 0x406e3    | 3         | 3.16%   |
| 0x08701021 | 3         | 3.16%   |
| 0x06000852 | 3         | 3.16%   |
| 0x906ea    | 2         | 2.11%   |
| 0x40651    | 2         | 2.11%   |
| 0x08108109 | 2         | 2.11%   |
| 0x0800820d | 2         | 2.11%   |
| 0x010000c8 | 2         | 2.11%   |
| 0xa0671    | 1         | 1.05%   |
| 0xa0653    | 1         | 1.05%   |
| 0xa0652    | 1         | 1.05%   |
| 0x906eb    | 1         | 1.05%   |
| 0x906e9    | 1         | 1.05%   |
| 0x806ec    | 1         | 1.05%   |
| 0x806eb    | 1         | 1.05%   |
| 0x706a1    | 1         | 1.05%   |
| 0x6fb      | 1         | 1.05%   |
| 0x6f6      | 1         | 1.05%   |
| 0x686      | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x506c9    | 1         | 1.05%   |
| 0x406c4    | 1         | 1.05%   |
| 0x306f2    | 1         | 1.05%   |
| 0x206d7    | 1         | 1.05%   |
| 0x20655    | 1         | 1.05%   |
| 0x10676    | 1         | 1.05%   |
| 0x08701013 | 1         | 1.05%   |
| 0x08600106 | 1         | 1.05%   |
| 0x08108102 | 1         | 1.05%   |
| 0x08101016 | 1         | 1.05%   |
| 0x0800820b | 1         | 1.05%   |
| 0x08001137 | 1         | 1.05%   |
| 0x06003104 | 1         | 1.05%   |
| 0x06001119 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 14.61%  |
| Haswell       | 13        | 14.61%  |
| SandyBridge   | 7         | 7.87%   |
| IvyBridge     | 7         | 7.87%   |
| Skylake       | 6         | 6.74%   |
| Piledriver    | 6         | 6.74%   |
| Zen+          | 5         | 5.62%   |
| Zen 2         | 5         | 5.62%   |
| Penryn        | 5         | 5.62%   |
| K10           | 3         | 3.37%   |
| Core          | 3         | 3.37%   |
| Zen           | 2         | 2.25%   |
| K8 Hammer     | 2         | 2.25%   |
| CometLake     | 2         | 2.25%   |
| Westmere      | 1         | 1.12%   |
| Steamroller   | 1         | 1.12%   |
| Silvermont    | 1         | 1.12%   |
| P6            | 1         | 1.12%   |
| K10 Llano     | 1         | 1.12%   |
| Icelake       | 1         | 1.12%   |
| Goldmont plus | 1         | 1.12%   |
| Goldmont      | 1         | 1.12%   |
| Bulldozer     | 1         | 1.12%   |
| Unknown       | 1         | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 43        | 41.35%  |
| Intel  | 42        | 40.38%  |
| AMD    | 19        | 18.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 4.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 3.85%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 2.88%   |
| Intel HD Graphics 620                                                       | 3         | 2.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 2.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.88%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3         | 2.88%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.92%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.92%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.92%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2         | 1.92%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.92%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2         | 1.92%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                   | 2         | 1.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.96%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1         | 0.96%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.96%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.96%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.96%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 0.96%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 1         | 0.96%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 0.96%   |
| Nvidia GK106M [GeForce GTX 760M]                                            | 1         | 0.96%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.96%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1         | 0.96%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 30        | 33.71%  |
| 1 x Intel      | 28        | 31.46%  |
| 1 x AMD        | 17        | 19.1%   |
| Intel + Nvidia | 12        | 13.48%  |
| Intel + AMD    | 1         | 1.12%   |
| AMD + Nvidia   | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 68.48%  |
| Proprietary | 15        | 16.3%   |
| Unknown     | 14        | 15.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 38.04%  |
| 1.01-2.0   | 21        | 22.83%  |
| 0.51-1.0   | 13        | 14.13%  |
| 0.01-0.5   | 8         | 8.7%    |
| 3.01-4.0   | 5         | 5.43%   |
| 5.01-6.0   | 4         | 4.35%   |
| 2.01-3.0   | 3         | 3.26%   |
| 7.01-8.0   | 2         | 2.17%   |
| 8.01-16.0  | 1         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 7.92%   |
| Dell                    | 8         | 7.92%   |
| Ancor Communications    | 8         | 7.92%   |
| LG Display              | 6         | 5.94%   |
| Chimei Innolux          | 6         | 5.94%   |
| BOE                     | 6         | 5.94%   |
| Acer                    | 6         | 5.94%   |
| Goldstar                | 5         | 4.95%   |
| BenQ                    | 5         | 4.95%   |
| AOC                     | 5         | 4.95%   |
| SNC                     | 4         | 3.96%   |
| AU Optronics            | 4         | 3.96%   |
| ViewSonic               | 3         | 2.97%   |
| Sony                    | 3         | 2.97%   |
| Philips                 | 3         | 2.97%   |
| LG Electronics          | 3         | 2.97%   |
| Hewlett-Packard         | 2         | 1.98%   |
| Chi Mei Optoelectronics | 2         | 1.98%   |
| Unknown                 | 1         | 0.99%   |
| Sharp                   | 1         | 0.99%   |
| RTK                     | 1         | 0.99%   |
| QBell                   | 1         | 0.99%   |
| PKB                     | 1         | 0.99%   |
| Onkyo                   | 1         | 0.99%   |
| Medion                  | 1         | 0.99%   |
| Lenovo                  | 1         | 0.99%   |
| Iiyama                  | 1         | 0.99%   |
| HannStar                | 1         | 0.99%   |
| Eizo                    | 1         | 0.99%   |
| Compal                  | 1         | 0.99%   |
| ASUSTek Computer        | 1         | 0.99%   |
| Apple                   | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4         | 3.6%    |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 2         | 1.8%    |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2         | 1.8%    |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2         | 1.8%    |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1         | 0.9%    |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1         | 0.9%    |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1         | 0.9%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.9%    |
| Sony TV SNYF301 1920x1080                                             | 1         | 0.9%    |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1         | 0.9%    |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1         | 0.9%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch   | 1         | 0.9%    |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 0.9%    |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch    | 1         | 0.9%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor S24D330                               | 1         | 0.9%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.9%    |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.9%    |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1         | 0.9%    |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1         | 0.9%    |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1         | 0.9%    |
| Philips LCD Monitor FTV                                               | 1         | 0.9%    |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 0.9%    |
| Onkyo LCD Monitor TX-SR608 5760x2160                                  | 1         | 0.9%    |
| Onkyo LCD Monitor TX-SR608                                            | 1         | 0.9%    |
| Onkyo LCD Monitor AV Receiver 5760x2160                               | 1         | 0.9%    |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.9%    |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                        | 1         | 0.9%    |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1         | 0.9%    |
| LG Electronics LCD Monitor 23MB35 1920x1080                           | 1         | 0.9%    |
| LG Display LCD Monitor LGD066A 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 45.54%  |
| 1366x768 (WXGA)    | 10        | 9.9%    |
| Unknown            | 7         | 6.93%   |
| 1280x1024 (SXGA)   | 6         | 5.94%   |
| 3840x2160 (4K)     | 5         | 4.95%   |
| 1600x900 (HD+)     | 5         | 4.95%   |
| 1920x1200 (WUXGA)  | 4         | 3.96%   |
| 1680x1050 (WSXGA+) | 3         | 2.97%   |
| 3840x1080          | 2         | 1.98%   |
| 1280x800 (WXGA)    | 2         | 1.98%   |
| 5760x2160          | 1         | 0.99%   |
| 4480x1440          | 1         | 0.99%   |
| 3520x1080          | 1         | 0.99%   |
| 3200x900           | 1         | 0.99%   |
| 2736x1824          | 1         | 0.99%   |
| 2560x1440 (QHD)    | 1         | 0.99%   |
| 2560x1080          | 1         | 0.99%   |
| 2560x1024          | 1         | 0.99%   |
| 1440x900 (WXGA+)   | 1         | 0.99%   |
| 1360x768           | 1         | 0.99%   |
| 1024x768 (XGA)     | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 14.29%  |
| Unknown | 13        | 13.27%  |
| 24      | 10        | 10.2%   |
| 27      | 9         | 9.18%   |
| 21      | 8         | 8.16%   |
| 19      | 7         | 7.14%   |
| 13      | 7         | 7.14%   |
| 17      | 6         | 6.12%   |
| 18      | 4         | 4.08%   |
| 23      | 3         | 3.06%   |
| 22      | 3         | 3.06%   |
| 14      | 3         | 3.06%   |
| 46      | 2         | 2.04%   |
| 25      | 2         | 2.04%   |
| 72      | 1         | 1.02%   |
| 54      | 1         | 1.02%   |
| 42      | 1         | 1.02%   |
| 32      | 1         | 1.02%   |
| 29      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 23        | 23.71%  |
| 301-350     | 22        | 22.68%  |
| 401-500     | 17        | 17.53%  |
| Unknown     | 13        | 13.4%   |
| 351-400     | 10        | 10.31%  |
| 201-300     | 4         | 4.12%   |
| 1001-1500   | 3         | 3.09%   |
| 601-700     | 2         | 2.06%   |
| 701-800     | 1         | 1.03%   |
| 1501-2000   | 1         | 1.03%   |
| 901-1000    | 1         | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 59        | 64.13%  |
| Unknown | 13        | 14.13%  |
| 16/10   | 11        | 11.96%  |
| 5/4     | 6         | 6.52%   |
| 4/3     | 1         | 1.09%   |
| 3/2     | 1         | 1.09%   |
| 21/9    | 1         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 18        | 18.75%  |
| 101-110        | 14        | 14.58%  |
| Unknown        | 13        | 13.54%  |
| 301-350        | 10        | 10.42%  |
| 151-200        | 9         | 9.38%   |
| 81-90          | 7         | 7.29%   |
| 251-300        | 5         | 5.21%   |
| 141-150        | 5         | 5.21%   |
| 121-130        | 5         | 5.21%   |
| 501-1000       | 3         | 3.13%   |
| More than 1000 | 2         | 2.08%   |
| 71-80          | 2         | 2.08%   |
| 61-70          | 1         | 1.04%   |
| 351-500        | 1         | 1.04%   |
| 91-100         | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 41.94%  |
| 101-120       | 17        | 18.28%  |
| 121-160       | 16        | 17.2%   |
| Unknown       | 13        | 13.98%  |
| 1-50          | 4         | 4.3%    |
| 161-240       | 3         | 3.23%   |
| More than 240 | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 69        | 77.53%  |
| 2     | 20        | 22.47%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 45        | 35.16%  |
| Realtek Semiconductor    | 44        | 34.38%  |
| Qualcomm Atheros         | 13        | 10.16%  |
| Broadcom                 | 9         | 7.03%   |
| Marvell Technology Group | 4         | 3.13%   |
| Sierra Wireless          | 2         | 1.56%   |
| Broadcom Limited         | 2         | 1.56%   |
| Wilocity                 | 1         | 0.78%   |
| Ultimarc                 | 1         | 0.78%   |
| TP-Link                  | 1         | 0.78%   |
| MediaTek                 | 1         | 0.78%   |
| Huawei Technologies      | 1         | 0.78%   |
| Dell                     | 1         | 0.78%   |
| D-Link System            | 1         | 0.78%   |
| ASIX Electronics         | 1         | 0.78%   |
| Aquantia                 | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 24.32%  |
| Intel I211 Gigabit Network Connection                             | 5         | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.38%   |
| Intel Wireless 8260                                               | 4         | 2.7%    |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.7%    |
| Intel Wireless 3165                                               | 3         | 2.03%   |
| Intel Ethernet Connection I217-V                                  | 3         | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.03%   |
| Sierra Wireless MC8305 Modem                                      | 2         | 1.35%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 1.35%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.35%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2         | 1.35%   |
| Intel Wireless 7265                                               | 2         | 1.35%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.35%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.35%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.35%   |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 1.35%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.68%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1         | 0.68%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 27        | 48.21%  |
| Qualcomm Atheros         | 10        | 17.86%  |
| Realtek Semiconductor    | 6         | 10.71%  |
| Broadcom                 | 6         | 10.71%  |
| Sierra Wireless          | 2         | 3.57%   |
| Wilocity                 | 1         | 1.79%   |
| TP-Link                  | 1         | 1.79%   |
| MediaTek                 | 1         | 1.79%   |
| Marvell Technology Group | 1         | 1.79%   |
| Dell                     | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 6.67%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 6.67%   |
| Intel Wireless 3165                                            | 3         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5%      |
| Sierra Wireless MC8305 Modem                                   | 2         | 3.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 3.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 3.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 3.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2         | 3.33%   |
| Intel Wireless 7265                                            | 2         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.33%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 3.33%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 1.67%   |
| TP-Link 802.11ac NIC                                           | 1         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| MediaTek WiFi                                                  | 1         | 1.67%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.67%   |
| Intel Wireless-AC 9260                                         | 1         | 1.67%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.67%   |
| Intel Wireless 7260                                            | 1         | 1.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.67%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 48.81%  |
| Intel                    | 28        | 33.33%  |
| Qualcomm Atheros         | 4         | 4.76%   |
| Marvell Technology Group | 3         | 3.57%   |
| Broadcom                 | 3         | 3.57%   |
| Broadcom Limited         | 2         | 2.38%   |
| D-Link System            | 1         | 1.19%   |
| ASIX Electronics         | 1         | 1.19%   |
| Aquantia                 | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 41.86%  |
| Intel I211 Gigabit Network Connection                             | 5         | 5.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.81%   |
| Intel Ethernet Connection I217-V                                  | 3         | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.33%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 2.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 2.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.16%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.16%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.16%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.16%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 1.16%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.16%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.16%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.16%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.16%   |
| ASIX AX88772B                                                     | 1         | 1.16%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 60.77%  |
| WiFi     | 49        | 37.69%  |
| Modem    | 1         | 0.77%   |
| Unknown  | 1         | 0.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 54        | 58.7%   |
| WiFi     | 38        | 41.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 52.17%  |
| 2     | 37        | 40.22%  |
| 3     | 4         | 4.35%   |
| 0     | 2         | 2.17%   |
| 4     | 1         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 86.81%  |
| Yes  | 12        | 13.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 22        | 44%     |
| Cambridge Silicon Radio | 8         | 16%     |
| Broadcom                | 3         | 6%      |
| ASUSTek Computer        | 3         | 6%      |
| Realtek Semiconductor   | 2         | 4%      |
| Lite-On Technology      | 2         | 4%      |
| IMC Networks            | 2         | 4%      |
| Hewlett-Packard         | 2         | 4%      |
| Foxconn / Hon Hai       | 2         | 4%      |
| Marvell Semiconductor   | 1         | 2%      |
| Dell                    | 1         | 2%      |
| Belkin Components       | 1         | 2%      |
| Apple                   | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 18%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 16%     |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 8%      |
| Intel AX200 Bluetooth                               | 4         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6%      |
| Realtek Bluetooth Radio                             | 2         | 4%      |
| Lite-On Bluetooth Device                            | 2         | 4%      |
| IMC Networks Bluetooth Device                       | 2         | 4%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 4%      |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 4%      |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2%      |
| Intel AX201 Bluetooth                               | 1         | 2%      |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2%      |
| Broadcom Bluetooth dongle                           | 1         | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2%      |
| Belkin Components F8T013 Bluetooth Adapter          | 1         | 2%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2%      |
| ASUS Bluetooth Device                               | 1         | 2%      |
| ASUS BCM20702A0                                     | 1         | 2%      |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 61        | 43.88%  |
| Nvidia                     | 36        | 25.9%   |
| AMD                        | 27        | 19.42%  |
| C-Media Electronics        | 8         | 5.76%   |
| Samsung Electronics        | 1         | 0.72%   |
| Mackie Designs             | 1         | 0.72%   |
| Logitech                   | 1         | 0.72%   |
| iCreate Technologies       | 1         | 0.72%   |
| Corsair                    | 1         | 0.72%   |
| BEHRINGER International    | 1         | 0.72%   |
| Altec Lansing Technologies | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 5.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 4.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 3.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.6%    |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.6%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 2.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.6%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3         | 1.95%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.95%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.3%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.3%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.3%    |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.3%    |
| Samsung Electronics USB C Earphones                                        | 1         | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.65%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 15        | 24.59%  |
| Unknown             | 9         | 14.75%  |
| Samsung Electronics | 9         | 14.75%  |
| G.Skill             | 6         | 9.84%   |
| SK hynix            | 5         | 8.2%    |
| Micron Technology   | 4         | 6.56%   |
| Corsair             | 4         | 6.56%   |
| Unknown (ABCD)      | 2         | 3.28%   |
| Team                | 2         | 3.28%   |
| Crucial             | 2         | 3.28%   |
| Smart               | 1         | 1.64%   |
| Nanya Technology    | 1         | 1.64%   |
| Goodram             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 3.03%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s          | 2         | 3.03%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.52%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 1.52%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 1.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.52%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.52%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 1.52%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.52%   |
| Team RAM Elite-16 4GB DIMM DDR3 1600MT/s                         | 1         | 1.52%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 1         | 1.52%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 1.52%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.52%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.52%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.52%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s             | 1         | 1.52%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s             | 1         | 1.52%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 1         | 1.52%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1600MT/s               | 1         | 1.52%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 1         | 1.52%   |
| Micron RAM 18JSF51272AZ-1G6M 4GB DIMM DDR3 1600MT/s              | 1         | 1.52%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 43.4%   |
| DDR4    | 21        | 39.62%  |
| DDR2    | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |
| LPDDR4  | 2         | 3.77%   |
| LPDDR3  | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 31        | 58.49%  |
| SODIMM       | 21        | 39.62%  |
| Row Of Chips | 1         | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 45.61%  |
| 4096  | 19        | 33.33%  |
| 16384 | 6         | 10.53%  |
| 2048  | 6         | 10.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 28.81%  |
| 2400  | 6         | 10.17%  |
| 2133  | 6         | 10.17%  |
| 1333  | 5         | 8.47%   |
| 3200  | 4         | 6.78%   |
| 2667  | 4         | 6.78%   |
| 3334  | 2         | 3.39%   |
| 1867  | 2         | 3.39%   |
| 800   | 2         | 3.39%   |
| 667   | 2         | 3.39%   |
| 3733  | 1         | 1.69%   |
| 3600  | 1         | 1.69%   |
| 3500  | 1         | 1.69%   |
| 3466  | 1         | 1.69%   |
| 3400  | 1         | 1.69%   |
| 3000  | 1         | 1.69%   |
| 1334  | 1         | 1.69%   |
| 1066  | 1         | 1.69%   |
| 975   | 1         | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 30.77%  |
| Microdia                               | 5         | 12.82%  |
| Logitech                               | 4         | 10.26%  |
| Sunplus Innovation Technology          | 2         | 5.13%   |
| Realtek Semiconductor                  | 2         | 5.13%   |
| Microsoft                              | 2         | 5.13%   |
| IMC Networks                           | 2         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.13%   |
| Apple                                  | 2         | 5.13%   |
| WaveRider Communications               | 1         | 2.56%   |
| Suyin                                  | 1         | 2.56%   |
| Primax Electronics                     | 1         | 2.56%   |
| Leap Motion                            | 1         | 2.56%   |
| Alcor Micro                            | 1         | 2.56%   |
| Acer                                   | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 3         | 7.5%    |
| Chicony Integrated Camera                                                  | 3         | 7.5%    |
| Microdia Camera                                                            | 2         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 5%      |
| Chicony FJ Camera                                                          | 2         | 5%      |
| WaveRider USB 2.0 Camera                                                   | 1         | 2.5%    |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.5%    |
| Sunplus Full HD webcam                                                     | 1         | 2.5%    |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 2.5%    |
| Realtek USB Camera                                                         | 1         | 2.5%    |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.5%    |
| Primax HP Truevision FHD                                                   | 1         | 2.5%    |
| Microsoft LifeCam VX-800                                                   | 1         | 2.5%    |
| Microsoft LifeCam HD-3000                                                  | 1         | 2.5%    |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2.5%    |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.5%    |
| Microdia Integrated Webcam                                                 | 1         | 2.5%    |
| Logitech Webcam C210                                                       | 1         | 2.5%    |
| Logitech Webcam C200                                                       | 1         | 2.5%    |
| Logitech Webcam C110                                                       | 1         | 2.5%    |
| Logitech QuickCam Pro 9000                                                 | 1         | 2.5%    |
| Leap Motion Controller                                                     | 1         | 2.5%    |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.5%    |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.5%    |
| Chicony Integrated IR Camera                                               | 1         | 2.5%    |
| Chicony HD WebCam                                                          | 1         | 2.5%    |
| Chicony 1.3M HD WebCam                                                     | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.5%    |
| Apple iPhone5/5C/5S/6                                                      | 1         | 2.5%    |
| Apple Built-in iSight                                                      | 1         | 2.5%    |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.5%    |
| Acer BisonCam,NB Pro                                                       | 1         | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| AuthenTec                  | 3         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor       | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI            | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner       | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device        | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader         | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor               | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| O2 Micro | 2         | 40%     |
| Broadcom | 2         | 40%     |
| Avtor    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Avtor SecureToken                                                            | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 64        | 69.57%  |
| 1     | 22        | 23.91%  |
| 2     | 4         | 4.35%   |
| 3     | 2         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 34.38%  |
| Fingerprint reader       | 8         | 25%     |
| Chipcard                 | 5         | 15.63%  |
| Multimedia controller    | 3         | 9.38%   |
| Unassigned class         | 1         | 3.13%   |
| Sound                    | 1         | 3.13%   |
| Net/wireless             | 1         | 3.13%   |
| Communication controller | 1         | 3.13%   |
| Camera                   | 1         | 3.13%   |

