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

Total: 170

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek   | TUF Gaming B550M-PLUS       | Desktop     | [e45ad193f8](https://linux-hardware.org/?probe=e45ad193f8) | Apr 01, 2023 |
| Dell      | Latitude 7370               | Notebook    | [b8a0b25983](https://linux-hardware.org/?probe=b8a0b25983) | Mar 30, 2023 |
| MSI       | Z590-A PRO                  | Desktop     | [ad6a144db9](https://linux-hardware.org/?probe=ad6a144db9) | Mar 23, 2023 |
| ASUSTek   | M3A78-EMH HDMI              | Desktop     | [0aa8c2bf55](https://linux-hardware.org/?probe=0aa8c2bf55) | Mar 20, 2023 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [bb43961724](https://linux-hardware.org/?probe=bb43961724) | Mar 17, 2023 |
| HP        | ProBook 5330m               | Notebook    | [2ec50367d4](https://linux-hardware.org/?probe=2ec50367d4) | Mar 11, 2023 |
| Lenovo    | MAHOBAY                     | Desktop     | [d0541545c8](https://linux-hardware.org/?probe=d0541545c8) | Mar 11, 2023 |
| ASUSTek   | P8H61-M LE                  | Desktop     | [69713a19ea](https://linux-hardware.org/?probe=69713a19ea) | Feb 28, 2023 |
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
| Mageia 8 | 59        | 55.66%  |
| Mageia 7 | 33        | 31.13%  |
| Mageia 9 | 9         | 8.49%   |
| Mageia 6 | 4         | 3.77%   |
| Mageia 5 | 1         | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Mageia | 93        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 13        | 9.49%   |
| 5.10.27-desktop-1.mga8 | 8         | 5.84%   |
| 5.7.19-desktop-1.mga7  | 7         | 5.11%   |
| 5.15.32-desktop-1.mga8 | 5         | 3.65%   |
| 5.6.14-desktop-2.mga7  | 4         | 2.92%   |
| 5.5.4-desktop-1.mga7   | 4         | 2.92%   |
| 5.15.23-desktop-1.mga8 | 4         | 2.92%   |
| 5.10.25-desktop-1.mga8 | 4         | 2.92%   |
| 5.5.9-desktop-1.mga7   | 3         | 2.19%   |
| 5.10.12-desktop-1.mga7 | 3         | 2.19%   |
| 5.6.6-desktop-1.mga7   | 2         | 1.46%   |
| 5.3.7-desktop-4.mga7   | 2         | 1.46%   |
| 5.17.4-desktop-2.mga8  | 2         | 1.46%   |
| 5.16.10-desktop-2.mga8 | 2         | 1.46%   |
| 5.15.98-desktop-1.mga8 | 2         | 1.46%   |
| 5.15.4-desktop-1.mga8  | 2         | 1.46%   |
| 5.15.35-desktop-2.mga8 | 2         | 1.46%   |
| 5.15.16-desktop-1.mga8 | 2         | 1.46%   |
| 5.15.11-desktop-3.mga8 | 2         | 1.46%   |
| 5.10.60-desktop-2.mga8 | 2         | 1.46%   |
| 5.10.52-desktop-1.mga8 | 2         | 1.46%   |
| 5.10.20-desktop-2.mga7 | 2         | 1.46%   |
| 5.10.14-desktop-1.mga7 | 2         | 1.46%   |
| 6.2.6-desktop-1.mga9   | 1         | 0.73%   |
| 6.2.2-desktop-2.mga9   | 1         | 0.73%   |
| 6.1.6-desktop-1.mga8   | 1         | 0.73%   |
| 6.1.15-desktop-1.mga8  | 1         | 0.73%   |
| 6.0.10-desktop-1.mga9  | 1         | 0.73%   |
| 5.9.6-desktop-1.mga8   | 1         | 0.73%   |
| 5.9.3-desktop-1.mga8   | 1         | 0.73%   |
| 5.9.16-desktop-1.mga7  | 1         | 0.73%   |
| 5.9.11-desktop-3.mga8  | 1         | 0.73%   |
| 5.9.1-desktop-1.mga8   | 1         | 0.73%   |
| 5.8.5-desktop-2.mga8   | 1         | 0.73%   |
| 5.8.14-desktop-1.mga8  | 1         | 0.73%   |
| 5.7.8-desktop-1.mga8   | 1         | 0.73%   |
| 5.6.8-desktop-1.mga7   | 1         | 0.73%   |
| 5.5.13-desktop-1.mga7  | 1         | 0.73%   |
| 5.4.8-desktop-1.mga7   | 1         | 0.73%   |
| 5.4.12-desktop-1.mga7  | 1         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.19  | 18        | 13.33%  |
| 5.10.27 | 8         | 5.93%   |
| 5.15.32 | 5         | 3.7%    |
| 5.6.14  | 4         | 2.96%   |
| 5.5.4   | 4         | 2.96%   |
| 5.15.23 | 4         | 2.96%   |
| 5.10.25 | 4         | 2.96%   |
| 5.10.12 | 4         | 2.96%   |
| 5.5.9   | 3         | 2.22%   |
| 5.6.6   | 2         | 1.48%   |
| 5.3.7   | 2         | 1.48%   |
| 5.17.4  | 2         | 1.48%   |
| 5.16.18 | 2         | 1.48%   |
| 5.16.10 | 2         | 1.48%   |
| 5.15.98 | 2         | 1.48%   |
| 5.15.4  | 2         | 1.48%   |
| 5.15.35 | 2         | 1.48%   |
| 5.15.16 | 2         | 1.48%   |
| 5.15.11 | 2         | 1.48%   |
| 5.10.60 | 2         | 1.48%   |
| 5.10.52 | 2         | 1.48%   |
| 5.10.20 | 2         | 1.48%   |
| 5.10.16 | 2         | 1.48%   |
| 5.10.14 | 2         | 1.48%   |
| 6.2.6   | 1         | 0.74%   |
| 6.2.2   | 1         | 0.74%   |
| 6.1.6   | 1         | 0.74%   |
| 6.1.15  | 1         | 0.74%   |
| 6.0.10  | 1         | 0.74%   |
| 5.9.6   | 1         | 0.74%   |
| 5.9.3   | 1         | 0.74%   |
| 5.9.16  | 1         | 0.74%   |
| 5.9.11  | 1         | 0.74%   |
| 5.9.1   | 1         | 0.74%   |
| 5.8.5   | 1         | 0.74%   |
| 5.8.14  | 1         | 0.74%   |
| 5.7.8   | 1         | 0.74%   |
| 5.6.8   | 1         | 0.74%   |
| 5.5.13  | 1         | 0.74%   |
| 5.4.8   | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 21.77%  |
| 5.10    | 27        | 21.77%  |
| 5.7     | 19        | 15.32%  |
| 5.5     | 8         | 6.45%   |
| 5.6     | 7         | 5.65%   |
| 5.9     | 5         | 4.03%   |
| 5.16    | 4         | 3.23%   |
| 4.14    | 3         | 2.42%   |
| 6.2     | 2         | 1.61%   |
| 6.1     | 2         | 1.61%   |
| 5.8     | 2         | 1.61%   |
| 5.4     | 2         | 1.61%   |
| 5.3     | 2         | 1.61%   |
| 5.19    | 2         | 1.61%   |
| 5.17    | 2         | 1.61%   |
| 5.14    | 2         | 1.61%   |
| 6.0     | 1         | 0.81%   |
| 5.18    | 1         | 0.81%   |
| 5.13    | 1         | 0.81%   |
| 5.12    | 1         | 0.81%   |
| 5.1     | 1         | 0.81%   |
| 4.9     | 1         | 0.81%   |
| 4.19    | 1         | 0.81%   |
| 4.1     | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 91        | 97.85%  |
| i686   | 2         | 2.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 38        | 36.54%  |
| KDE           | 24        | 23.08%  |
| GNOME         | 12        | 11.54%  |
| Unknown       | 9         | 8.65%   |
| XFCE          | 5         | 4.81%   |
| Cinnamon      | 5         | 4.81%   |
| MATE          | 4         | 3.85%   |
| LXDE          | 3         | 2.88%   |
| X-Cinnamon    | 1         | 0.96%   |
| LXQt          | 1         | 0.96%   |
| KDE4          | 1         | 0.96%   |
| GNOME Classic | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 87        | 92.55%  |
| Wayland | 6         | 6.38%   |
| Tty     | 1         | 1.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 48        | 51.06%  |
| SDDM    | 35        | 37.23%  |
| LightDM | 5         | 5.32%   |
| TDM     | 3         | 3.19%   |
| GDM     | 2         | 2.13%   |
| XDM     | 1         | 1.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| fr_FR   | 19        | 20%     |
| en_US   | 17        | 17.89%  |
| de_DE   | 11        | 11.58%  |
| Unknown | 8         | 8.42%   |
| ru_RU   | 7         | 7.37%   |
| en_GB   | 7         | 7.37%   |
| pt_BR   | 4         | 4.21%   |
| it_IT   | 4         | 4.21%   |
| sv_SE   | 2         | 2.11%   |
| pl_PL   | 2         | 2.11%   |
| es_GT   | 2         | 2.11%   |
| en_CA   | 2         | 2.11%   |
| zh_TW   | 1         | 1.05%   |
| sl_SI   | 1         | 1.05%   |
| sk_SK   | 1         | 1.05%   |
| hu_HU   | 1         | 1.05%   |
| fr_BE   | 1         | 1.05%   |
| es_MX   | 1         | 1.05%   |
| es_ES   | 1         | 1.05%   |
| es_AR   | 1         | 1.05%   |
| cs_CZ   | 1         | 1.05%   |
| bg_BG   | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 57        | 58.76%  |
| EFI  | 40        | 41.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 78        | 82.11%  |
| Xfs      | 7         | 7.37%   |
| Unknown  | 6         | 6.32%   |
| Btrfs    | 3         | 3.16%   |
| Reiserfs | 1         | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 40.21%  |
| GPT     | 38        | 39.18%  |
| MBR     | 20        | 20.62%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 86.02%  |
| Yes       | 13        | 13.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 77.08%  |
| Yes       | 22        | 22.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 21        | 22.58%  |
| Gigabyte Technology | 16        | 17.2%   |
| Hewlett-Packard     | 10        | 10.75%  |
| Lenovo              | 8         | 8.6%    |
| MSI                 | 7         | 7.53%   |
| Dell                | 7         | 7.53%   |
| ASRock              | 6         | 6.45%   |
| Notebook            | 2         | 2.15%   |
| Medion              | 2         | 2.15%   |
| Fujitsu             | 2         | 2.15%   |
| Acer                | 2         | 2.15%   |
| ZOTAC               | 1         | 1.08%   |
| Vorke               | 1         | 1.08%   |
| Toshiba             | 1         | 1.08%   |
| Schenker            | 1         | 1.08%   |
| Microsoft           | 1         | 1.08%   |
| Megaware            | 1         | 1.08%   |
| Kiano               | 1         | 1.08%   |
| Intel               | 1         | 1.08%   |
| ECS                 | 1         | 1.08%   |
| Apple               | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 3.23%   |
| Gigabyte Z68X-UD3H-B3                    | 2         | 2.15%   |
| Dell Precision WorkStation T3400         | 2         | 2.15%   |
| ASUS SABERTOOTH 990FX R2.0               | 2         | 2.15%   |
| Vorke V1 Plus                            | 1         | 1.08%   |
| Toshiba dynabook R73/A                   | 1         | 1.08%   |
| Schenker VIA_14_SVI14E20                 | 1         | 1.08%   |
| Notebook NL40_50GU                       | 1         | 1.08%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 1.08%   |
| MSI MS-7D09                              | 1         | 1.08%   |
| MSI MS-7C82                              | 1         | 1.08%   |
| MSI MS-7C37                              | 1         | 1.08%   |
| MSI MS-7B31                              | 1         | 1.08%   |
| MSI MS-7B23                              | 1         | 1.08%   |
| MSI MS-7A70                              | 1         | 1.08%   |
| MSI MS-7816                              | 1         | 1.08%   |
| Microsoft Surface Pro 4                  | 1         | 1.08%   |
| Megaware MW-G31T-M7                      | 1         | 1.08%   |
| Medion MD34161/C708                      | 1         | 1.08%   |
| Medion DEFENDER P10                      | 1         | 1.08%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 1.08%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 1.08%   |
| Lenovo ThinkCentre M92p 2992A7U          | 1         | 1.08%   |
| Lenovo ThinkCentre M58e 7491B1G          | 1         | 1.08%   |
| Lenovo ThinkCentre A57 970274G           | 1         | 1.08%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.08%   |
| Lenovo G480 20149                        | 1         | 1.08%   |
| Lenovo 70A4000HUX ThinkServer TS140      | 1         | 1.08%   |
| Kiano SlimNote 15.6                      | 1         | 1.08%   |
| Intel STL2                               | 1         | 1.08%   |
| HP Z440 Workstation                      | 1         | 1.08%   |
| HP Z420 Workstation                      | 1         | 1.08%   |
| HP Spectre 13 Ultrabook                  | 1         | 1.08%   |
| HP ProBook 5330m                         | 1         | 1.08%   |
| HP ProBook 445 G7                        | 1         | 1.08%   |
| HP Pavilion dv6                          | 1         | 1.08%   |
| HP EliteBook 840 G3                      | 1         | 1.08%   |
| HP Compaq Pro 6300 SFF                   | 1         | 1.08%   |
| Gigabyte Z87X-UD5H                       | 1         | 1.08%   |
| Gigabyte Z68XP-UD3P                      | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkCentre     | 3         | 3.23%   |
| Dell Precision         | 3         | 3.23%   |
| Dell Latitude          | 3         | 3.23%   |
| ASUS SABERTOOTH        | 3         | 3.23%   |
| ASUS PRIME             | 3         | 3.23%   |
| Unknown                | 3         | 3.23%   |
| Lenovo ThinkPad        | 2         | 2.15%   |
| HP ProBook             | 2         | 2.15%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 2.15%   |
| Gigabyte GA-78LMT-USB3 | 2         | 2.15%   |
| Acer Aspire            | 2         | 2.15%   |
| Vorke V1               | 1         | 1.08%   |
| Toshiba dynabook       | 1         | 1.08%   |
| Schenker VIA           | 1         | 1.08%   |
| Notebook NL40          | 1         | 1.08%   |
| Notebook NH5x          | 1         | 1.08%   |
| MSI MS-7D09            | 1         | 1.08%   |
| MSI MS-7C82            | 1         | 1.08%   |
| MSI MS-7C37            | 1         | 1.08%   |
| MSI MS-7B31            | 1         | 1.08%   |
| MSI MS-7B23            | 1         | 1.08%   |
| MSI MS-7A70            | 1         | 1.08%   |
| MSI MS-7816            | 1         | 1.08%   |
| Microsoft Surface      | 1         | 1.08%   |
| Megaware MW-G31T-M7    | 1         | 1.08%   |
| Medion MD34161         | 1         | 1.08%   |
| Medion DEFENDER        | 1         | 1.08%   |
| Lenovo IdeaPad         | 1         | 1.08%   |
| Lenovo G480            | 1         | 1.08%   |
| Lenovo 70A4000HUX      | 1         | 1.08%   |
| Kiano SlimNote         | 1         | 1.08%   |
| Intel STL2             | 1         | 1.08%   |
| HP Z440                | 1         | 1.08%   |
| HP Z420                | 1         | 1.08%   |
| HP Spectre             | 1         | 1.08%   |
| HP Pavilion            | 1         | 1.08%   |
| HP EliteBook           | 1         | 1.08%   |
| HP Compaq              | 1         | 1.08%   |
| Gigabyte Z87X-UD5H     | 1         | 1.08%   |
| Gigabyte Z68XP-UD3P    | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 12        | 12.9%   |
| 2012 | 12        | 12.9%   |
| 2018 | 11        | 11.83%  |
| 2017 | 8         | 8.6%    |
| 2016 | 6         | 6.45%   |
| 2008 | 6         | 6.45%   |
| 2020 | 5         | 5.38%   |
| 2019 | 5         | 5.38%   |
| 2014 | 5         | 5.38%   |
| 2011 | 5         | 5.38%   |
| 2015 | 4         | 4.3%    |
| 2010 | 4         | 4.3%    |
| 2009 | 4         | 4.3%    |
| 2021 | 2         | 2.15%   |
| 2007 | 2         | 2.15%   |
| 2022 | 1         | 1.08%   |
| 2002 | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 62        | 66.67%  |
| Notebook   | 29        | 31.18%  |
| Tablet     | 1         | 1.08%   |
| All in one | 1         | 1.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 93        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 24        | 24.74%  |
| 4.01-8.0    | 19        | 19.59%  |
| 8.01-16.0   | 19        | 19.59%  |
| 32.01-64.0  | 14        | 14.43%  |
| 3.01-4.0    | 14        | 14.43%  |
| 64.01-256.0 | 4         | 4.12%   |
| 24.01-32.0  | 2         | 2.06%   |
| 2.01-3.0    | 1         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 35        | 30.7%   |
| 1.01-2.0   | 29        | 25.44%  |
| 4.01-8.0   | 21        | 18.42%  |
| 3.01-4.0   | 18        | 15.79%  |
| 8.01-16.0  | 6         | 5.26%   |
| 0.51-1.0   | 3         | 2.63%   |
| 16.01-24.0 | 2         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 38.78%  |
| 2      | 27        | 27.55%  |
| 3      | 19        | 19.39%  |
| 5      | 6         | 6.12%   |
| 4      | 4         | 4.08%   |
| 6      | 2         | 2.04%   |
| 8      | 1         | 1.02%   |
| 7      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 52.69%  |
| Yes       | 44        | 47.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 89.25%  |
| No        | 10        | 10.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 54.26%  |
| No        | 43        | 45.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 52.69%  |
| No        | 44        | 47.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 20        | 21.51%  |
| USA         | 14        | 15.05%  |
| Germany     | 11        | 11.83%  |
| UK          | 7         | 7.53%   |
| Russia      | 4         | 4.3%    |
| Italy       | 4         | 4.3%    |
| Brazil      | 4         | 4.3%    |
| Ukraine     | 3         | 3.23%   |
| Canada      | 3         | 3.23%   |
| Sweden      | 2         | 2.15%   |
| Poland      | 2         | 2.15%   |
| Guatemala   | 2         | 2.15%   |
| Greece      | 2         | 2.15%   |
| Taiwan      | 1         | 1.08%   |
| Slovenia    | 1         | 1.08%   |
| Slovakia    | 1         | 1.08%   |
| Romania     | 1         | 1.08%   |
| Netherlands | 1         | 1.08%   |
| Mexico      | 1         | 1.08%   |
| Luxembourg  | 1         | 1.08%   |
| Kenya       | 1         | 1.08%   |
| Indonesia   | 1         | 1.08%   |
| Czechia     | 1         | 1.08%   |
| Colombia    | 1         | 1.08%   |
| Bulgaria    | 1         | 1.08%   |
| Belgium     | 1         | 1.08%   |
| Belarus     | 1         | 1.08%   |
| Argentina   | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Rommerskirchen        | 3         | 2.61%   |
| Paris                 | 3         | 2.61%   |
| Mala Danylivka        | 3         | 2.61%   |
| Kharkiv               | 3         | 2.61%   |
| Woking                | 2         | 1.74%   |
| Woincourt             | 2         | 1.74%   |
| Waterloo              | 2         | 1.74%   |
| Upper Norwood         | 2         | 1.74%   |
| Strasbourg            | 2         | 1.74%   |
| Sao Paulo             | 2         | 1.74%   |
| Oakland               | 2         | 1.74%   |
| Guatemala City        | 2         | 1.74%   |
| Grants Pass           | 2         | 1.74%   |
| Yakutsk               | 1         | 0.87%   |
| Wiwersheim            | 1         | 0.87%   |
| Voronezh              | 1         | 0.87%   |
| Vanves                | 1         | 0.87%   |
| Uzhhorod              | 1         | 0.87%   |
| Tver                  | 1         | 0.87%   |
| Turin                 | 1         | 0.87%   |
| Tours                 | 1         | 0.87%   |
| Toulouse              | 1         | 0.87%   |
| Thiais                | 1         | 0.87%   |
| Surabaya              | 1         | 0.87%   |
| Sternberk             | 1         | 0.87%   |
| Sartrouville          | 1         | 0.87%   |
| Sant'Angelo Lodigiano | 1         | 0.87%   |
| San Isidro            | 1         | 0.87%   |
| San Antonio           | 1         | 0.87%   |
| Saint-Michel-sur-Orge | 1         | 0.87%   |
| Saint-Aubin-en-Bray   | 1         | 0.87%   |
| Rome                  | 1         | 0.87%   |
| Roehampton            | 1         | 0.87%   |
| Rio de Janeiro        | 1         | 0.87%   |
| Regina                | 1         | 0.87%   |
| Quincy                | 1         | 0.87%   |
| Quierschied           | 1         | 0.87%   |
| Quaregna              | 1         | 0.87%   |
| Poznan                | 1         | 0.87%   |
| Pouldergat            | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 43        | 123    | 23.24%  |
| Seagate                 | 27        | 50     | 14.59%  |
| Samsung Electronics     | 24        | 32     | 12.97%  |
| Kingston                | 13        | 22     | 7.03%   |
| Toshiba                 | 11        | 19     | 5.95%   |
| SanDisk                 | 8         | 14     | 4.32%   |
| Hitachi                 | 8         | 8      | 4.32%   |
| Unknown                 | 6         | 6      | 3.24%   |
| Crucial                 | 6         | 10     | 3.24%   |
| PNY                     | 5         | 8      | 2.7%    |
| HGST                    | 4         | 8      | 2.16%   |
| Intel                   | 3         | 3      | 1.62%   |
| SK hynix                | 2         | 3      | 1.08%   |
| Phison                  | 2         | 3      | 1.08%   |
| OCZ-VERTEX              | 2         | 2      | 1.08%   |
| OCZ                     | 2         | 2      | 1.08%   |
| A-DATA Technology       | 2         | 7      | 1.08%   |
| XPG                     | 1         | 4      | 0.54%   |
| Verbatim                | 1         | 1      | 0.54%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.54%   |
| Transcend               | 1         | 1      | 0.54%   |
| TO Exter                | 1         | 1      | 0.54%   |
| Team                    | 1         | 1      | 0.54%   |
| PNY CS90                | 1         | 1      | 0.54%   |
| LDLC                    | 1         | 1      | 0.54%   |
| KingFast                | 1         | 1      | 0.54%   |
| JMicron Technology      | 1         | 1      | 0.54%   |
| HUAWEI                  | 1         | 1      | 0.54%   |
| Hewlett-Packard         | 1         | 1      | 0.54%   |
| Gigabyte Technology     | 1         | 1      | 0.54%   |
| FORESEE                 | 1         | 1      | 0.54%   |
| Corsair                 | 1         | 1      | 0.54%   |
| China                   | 1         | 1      | 0.54%   |
| ASMedia                 | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4         | 1.91%   |
| WDC WD10EZEX-08WN4A0 1TB         | 3         | 1.44%   |
| Samsung SSD 860 EVO 500GB        | 3         | 1.44%   |
| Samsung SSD 860 EVO 250GB        | 3         | 1.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.96%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2         | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 0.96%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2         | 0.96%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2         | 0.96%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2         | 0.96%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2         | 0.96%   |
| Toshiba HDWD120 2TB              | 2         | 0.96%   |
| Seagate ST3500418AS 500GB        | 2         | 0.96%   |
| Seagate ST32000644NS 2TB         | 2         | 0.96%   |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 0.96%   |
| SanDisk SDSSDA120G 120GB         | 2         | 0.96%   |
| SanDisk Extreme SSD 500GB        | 2         | 0.96%   |
| Samsung SSD 850 EVO 500GB        | 2         | 0.96%   |
| Samsung NVMe SSD Drive 500GB     | 2         | 0.96%   |
| PNY CS900 120GB SSD              | 2         | 0.96%   |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2         | 0.96%   |
| Kingston SV300S37A240G 240GB SSD | 2         | 0.96%   |
| Kingston SH103S3120G 120GB SSD   | 2         | 0.96%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 0.96%   |
| Intel SSDSC2CW120A3 120GB        | 2         | 0.96%   |
| Hitachi HDS722020ALA330 2TB      | 2         | 0.96%   |
| HGST HUS726040ALE611 4TB         | 2         | 0.96%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.96%   |
| Crucial CT120BX500SSD1 120GB     | 2         | 0.96%   |
| XPG NVMe SSD Drive 2TB           | 1         | 0.48%   |
| XPG NVMe SSD Drive 1024GB        | 1         | 0.48%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1         | 0.48%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.48%   |
| WDC WDS100T2B0A 1TB SSD          | 1         | 0.48%   |
| WDC WD800BB-00JHC0 80GB          | 1         | 0.48%   |
| WDC WD50EFRX-68L0BN1 5TB         | 1         | 0.48%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.48%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 0.48%   |
| WDC WD5000AADS-00S9B0 500GB      | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB         | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 104    | 38.46%  |
| Seagate             | 26        | 44     | 28.57%  |
| Toshiba             | 10        | 18     | 10.99%  |
| Hitachi             | 8         | 8      | 8.79%   |
| Samsung Electronics | 5         | 9      | 5.49%   |
| HGST                | 4         | 8      | 4.4%    |
| Unknown             | 2         | 2      | 2.2%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 21.13%  |
| Kingston            | 10        | 16     | 14.08%  |
| WDC                 | 7         | 17     | 9.86%   |
| SanDisk             | 6         | 8      | 8.45%   |
| Crucial             | 6         | 10     | 8.45%   |
| PNY                 | 5         | 8      | 7.04%   |
| Intel               | 3         | 3      | 4.23%   |
| OCZ-VERTEX          | 2         | 2      | 2.82%   |
| OCZ                 | 2         | 2      | 2.82%   |
| A-DATA Technology   | 2         | 7      | 2.82%   |
| Verbatim            | 1         | 1      | 1.41%   |
| Transcend           | 1         | 1      | 1.41%   |
| TO Exter            | 1         | 1      | 1.41%   |
| Team                | 1         | 1      | 1.41%   |
| SK hynix            | 1         | 1      | 1.41%   |
| PNY CS90            | 1         | 1      | 1.41%   |
| LDLC                | 1         | 1      | 1.41%   |
| KingFast            | 1         | 1      | 1.41%   |
| JMicron Technology  | 1         | 1      | 1.41%   |
| FORESEE             | 1         | 1      | 1.41%   |
| Corsair             | 1         | 1      | 1.41%   |
| China               | 1         | 1      | 1.41%   |
| ASMedia             | 1         | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 65        | 194    | 46.1%   |
| SSD     | 51        | 102    | 36.17%  |
| NVMe    | 19        | 33     | 13.48%  |
| MMC     | 4         | 4      | 2.84%   |
| Unknown | 2         | 7      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 278    | 70.83%  |
| NVMe | 19        | 33     | 15.83%  |
| SAS  | 12        | 25     | 10%     |
| MMC  | 4         | 4      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 126    | 48.53%  |
| 0.51-1.0   | 38        | 93     | 27.94%  |
| 1.01-2.0   | 16        | 32     | 11.76%  |
| 3.01-4.0   | 6         | 8      | 4.41%   |
| 2.01-3.0   | 6         | 30     | 4.41%   |
| 4.01-10.0  | 3         | 6      | 2.21%   |
| 10.01-20.0 | 1         | 1      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 23        | 23%     |
| 251-500        | 22        | 22%     |
| More than 3000 | 17        | 17%     |
| 101-250        | 15        | 15%     |
| 1001-2000      | 10        | 10%     |
| 2001-3000      | 9         | 9%      |
| 51-100         | 3         | 3%      |
| Unknown        | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 19.44%  |
| 1-20           | 16        | 14.81%  |
| 51-100         | 16        | 14.81%  |
| 251-500        | 12        | 11.11%  |
| 1001-2000      | 12        | 11.11%  |
| 501-1000       | 11        | 10.19%  |
| 21-50          | 9         | 8.33%   |
| More than 3000 | 7         | 6.48%   |
| 2001-3000      | 3         | 2.78%   |
| Unknown        | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 11.11%  |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 5.56%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 5.56%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 5.56%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 5.56%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 5.56%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 5.56%   |
| Seagate ST3320820AS 320GB             | 1         | 1      | 5.56%   |
| Seagate ST3250410AS 250GB             | 1         | 3      | 5.56%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 5.56%   |
| Seagate ST2000VN004-2E4164 2TB        | 1         | 1      | 5.56%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 5.56%   |
| Samsung Electronics HD400LD 400GB     | 1         | 1      | 5.56%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 5.56%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 35.29%  |
| WDC                 | 3         | 4      | 17.65%  |
| Intel               | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| SK hynix            | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 8      | 46.15%  |
| WDC                 | 3         | 4      | 23.08%  |
| Toshiba             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 16     | 75%     |
| SSD  | 4         | 4      | 25%     |

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
| Works    | 51        | 158    | 45.13%  |
| Detected | 46        | 162    | 40.71%  |
| Malfunc  | 16        | 20     | 14.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 62        | 50.82%  |
| AMD                          | 26        | 21.31%  |
| Marvell Technology Group     | 7         | 5.74%   |
| ASMedia Technology           | 6         | 4.92%   |
| Samsung Electronics          | 5         | 4.1%    |
| SanDisk                      | 4         | 3.28%   |
| Phison Electronics           | 4         | 3.28%   |
| Kingston Technology Company  | 3         | 2.46%   |
| Toshiba America Info Systems | 1         | 0.82%   |
| SK hynix                     | 1         | 0.82%   |
| JMicron Technology           | 1         | 0.82%   |
| Broadcom                     | 1         | 0.82%   |
| ADATA Technology             | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 6.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 3.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 3.29%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 2.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3         | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.97%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 1.97%   |
| AMD SB600 IDE                                                                           | 3         | 1.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.32%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.32%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.32%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.32%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.32%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.32%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.66%   |
| SK hynix BC511                                                                          | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.66%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.66%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 61.98%  |
| IDE  | 23        | 19.01%  |
| NVMe | 18        | 14.88%  |
| RAID | 4         | 3.31%   |
| SAS  | 1         | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 70.97%  |
| AMD    | 27        | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 3.19%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 3.19%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2         | 2.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 2.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2         | 2.13%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2         | 2.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.13%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 2.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.13%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 2         | 2.13%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1         | 1.06%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 1.06%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.06%   |
| Intel Pentium III (Coppermine)              | 1         | 1.06%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1         | 1.06%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.06%   |
| Intel Pentium CPU G3450 @ 3.40GHz           | 1         | 1.06%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 1.06%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.06%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.06%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.06%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.06%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.06%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.06%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 1.06%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 1.06%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 1.06%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 1.06%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1         | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.06%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.06%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.06%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 21.51%  |
| Intel Core i7           | 19        | 20.43%  |
| Intel Core i3           | 6         | 6.45%   |
| AMD FX                  | 6         | 6.45%   |
| Intel Core 2 Duo        | 4         | 4.3%    |
| AMD Ryzen 7             | 4         | 4.3%    |
| AMD Ryzen 5             | 3         | 3.23%   |
| Other                   | 2         | 2.15%   |
| Intel Xeon              | 2         | 2.15%   |
| Intel Pentium Dual-Core | 2         | 2.15%   |
| Intel Pentium           | 2         | 2.15%   |
| Intel Celeron           | 2         | 2.15%   |
| AMD Turion 64 X2 Mobile | 2         | 2.15%   |
| AMD Ryzen Threadripper  | 2         | 2.15%   |
| AMD Ryzen 3             | 2         | 2.15%   |
| AMD A8                  | 2         | 2.15%   |
| Intel Pentium Silver    | 1         | 1.08%   |
| Intel Pentium III       | 1         | 1.08%   |
| Intel Pentium Gold      | 1         | 1.08%   |
| Intel Core m5           | 1         | 1.08%   |
| Intel Core 2 Quad       | 1         | 1.08%   |
| Intel Core 2            | 1         | 1.08%   |
| Intel Atom              | 1         | 1.08%   |
| AMD Ryzen 9             | 1         | 1.08%   |
| AMD Phenom II X6        | 1         | 1.08%   |
| AMD Phenom II X4        | 1         | 1.08%   |
| AMD Athlon II X3        | 1         | 1.08%   |
| AMD Athlon 64 X2        | 1         | 1.08%   |
| AMD A10                 | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 39        | 41.49%  |
| 2      | 36        | 38.3%   |
| 6      | 9         | 9.57%   |
| 8      | 5         | 5.32%   |
| 3      | 2         | 2.13%   |
| 32     | 1         | 1.06%   |
| 16     | 1         | 1.06%   |
| 12     | 1         | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 98.92%  |
| 2      | 1         | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 61.29%  |
| 1      | 36        | 38.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 95.79%  |
| Unknown        | 3         | 3.16%   |
| 32-bit         | 1         | 1.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 23.76%  |
| 0x306c3    | 8         | 7.92%   |
| 0x306a9    | 6         | 5.94%   |
| 0x206a7    | 6         | 5.94%   |
| 0x406e3    | 4         | 3.96%   |
| 0x1067a    | 4         | 3.96%   |
| 0x08701021 | 4         | 3.96%   |
| 0x806e9    | 3         | 2.97%   |
| 0x06000852 | 3         | 2.97%   |
| 0x906ea    | 2         | 1.98%   |
| 0x40651    | 2         | 1.98%   |
| 0x08108109 | 2         | 1.98%   |
| 0x0800820d | 2         | 1.98%   |
| 0x010000c8 | 2         | 1.98%   |
| 0xa0671    | 1         | 0.99%   |
| 0xa0653    | 1         | 0.99%   |
| 0xa0652    | 1         | 0.99%   |
| 0x906eb    | 1         | 0.99%   |
| 0x906e9    | 1         | 0.99%   |
| 0x806ec    | 1         | 0.99%   |
| 0x806eb    | 1         | 0.99%   |
| 0x706a1    | 1         | 0.99%   |
| 0x6fb      | 1         | 0.99%   |
| 0x6f6      | 1         | 0.99%   |
| 0x686      | 1         | 0.99%   |
| 0x506e3    | 1         | 0.99%   |
| 0x506c9    | 1         | 0.99%   |
| 0x406c4    | 1         | 0.99%   |
| 0x306f2    | 1         | 0.99%   |
| 0x206d7    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x10676    | 1         | 0.99%   |
| 0x08701013 | 1         | 0.99%   |
| 0x08600106 | 1         | 0.99%   |
| 0x08108102 | 1         | 0.99%   |
| 0x08101016 | 1         | 0.99%   |
| 0x0800820b | 1         | 0.99%   |
| 0x08001137 | 1         | 0.99%   |
| 0x06003104 | 1         | 0.99%   |
| 0x06001119 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 13.83%  |
| Haswell       | 13        | 13.83%  |
| SandyBridge   | 8         | 8.51%   |
| IvyBridge     | 8         | 8.51%   |
| Skylake       | 7         | 7.45%   |
| Zen 2         | 6         | 6.38%   |
| Piledriver    | 6         | 6.38%   |
| Zen+          | 5         | 5.32%   |
| Penryn        | 5         | 5.32%   |
| K8 Hammer     | 3         | 3.19%   |
| K10           | 3         | 3.19%   |
| Core          | 3         | 3.19%   |
| Zen           | 2         | 2.13%   |
| CometLake     | 2         | 2.13%   |
| Westmere      | 1         | 1.06%   |
| Steamroller   | 1         | 1.06%   |
| Silvermont    | 1         | 1.06%   |
| P6            | 1         | 1.06%   |
| K10 Llano     | 1         | 1.06%   |
| Icelake       | 1         | 1.06%   |
| Goldmont plus | 1         | 1.06%   |
| Goldmont      | 1         | 1.06%   |
| Bulldozer     | 1         | 1.06%   |
| Unknown       | 1         | 1.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 44        | 40.37%  |
| Intel  | 44        | 40.37%  |
| AMD    | 21        | 19.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 4.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 4.59%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 3.67%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4         | 3.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 2.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 2.75%   |
| Intel HD Graphics 620                                                       | 3         | 2.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 2.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.75%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3         | 2.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.83%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.83%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.83%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2         | 1.83%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.83%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2         | 1.83%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                   | 2         | 1.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.92%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1         | 0.92%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.92%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.92%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.92%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 0.92%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 1         | 0.92%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 0.92%   |
| Nvidia GK106M [GeForce GTX 760M]                                            | 1         | 0.92%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.92%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1         | 0.92%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 31        | 32.98%  |
| 1 x Intel      | 30        | 31.91%  |
| 1 x AMD        | 19        | 20.21%  |
| Intel + Nvidia | 12        | 12.77%  |
| Intel + AMD    | 1         | 1.06%   |
| AMD + Nvidia   | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 69        | 69.7%   |
| Proprietary | 15        | 15.15%  |
| Unknown     | 15        | 15.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 38.14%  |
| 1.01-2.0   | 21        | 21.65%  |
| 0.51-1.0   | 14        | 14.43%  |
| 0.01-0.5   | 9         | 9.28%   |
| 3.01-4.0   | 5         | 5.15%   |
| 5.01-6.0   | 4         | 4.12%   |
| 7.01-8.0   | 3         | 3.09%   |
| 2.01-3.0   | 3         | 3.09%   |
| 8.01-16.0  | 1         | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 10.38%  |
| Ancor Communications    | 8         | 7.55%   |
| Dell                    | 7         | 6.6%    |
| LG Display              | 6         | 5.66%   |
| Chimei Innolux          | 6         | 5.66%   |
| BOE                     | 6         | 5.66%   |
| Acer                    | 6         | 5.66%   |
| Goldstar                | 5         | 4.72%   |
| BenQ                    | 5         | 4.72%   |
| AOC                     | 5         | 4.72%   |
| SNC                     | 4         | 3.77%   |
| AU Optronics            | 4         | 3.77%   |
| ViewSonic               | 3         | 2.83%   |
| Sony                    | 3         | 2.83%   |
| Philips                 | 3         | 2.83%   |
| LG Electronics          | 3         | 2.83%   |
| Sharp                   | 2         | 1.89%   |
| Iiyama                  | 2         | 1.89%   |
| Hewlett-Packard         | 2         | 1.89%   |
| Chi Mei Optoelectronics | 2         | 1.89%   |
| Unknown                 | 1         | 0.94%   |
| RTK                     | 1         | 0.94%   |
| QBell                   | 1         | 0.94%   |
| PKB                     | 1         | 0.94%   |
| Onkyo                   | 1         | 0.94%   |
| Medion                  | 1         | 0.94%   |
| Lenovo                  | 1         | 0.94%   |
| Insignia                | 1         | 0.94%   |
| HannStar                | 1         | 0.94%   |
| Eizo                    | 1         | 0.94%   |
| Compal                  | 1         | 0.94%   |
| ASUSTek Computer        | 1         | 0.94%   |
| Apple                   | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4         | 3.42%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 700x390mm 31.5-inch | 2         | 1.71%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 2         | 1.71%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2         | 1.71%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2         | 1.71%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1         | 0.85%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 1         | 0.85%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1         | 0.85%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.85%   |
| Sony TV SNYF301 1920x1080                                             | 1         | 0.85%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1         | 0.85%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1         | 0.85%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch               | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 0.85%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch    | 1         | 0.85%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.85%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch     | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3155 1366x768 293x165mm 13.2-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1         | 0.85%   |
| Samsung Electronics LCD Monitor S24D330                               | 1         | 0.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.85%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.85%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1         | 0.85%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1         | 0.85%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1         | 0.85%   |
| Philips LCD Monitor FTV                                               | 1         | 0.85%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 0.85%   |
| Onkyo LCD Monitor TX-SR608 5760x2160                                  | 1         | 0.85%   |
| Onkyo LCD Monitor TX-SR608                                            | 1         | 0.85%   |
| Onkyo LCD Monitor AV Receiver 5760x2160                               | 1         | 0.85%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.85%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                        | 1         | 0.85%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1         | 0.85%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 44.34%  |
| 1366x768 (WXGA)    | 10        | 9.43%   |
| Unknown            | 7         | 6.6%    |
| 1280x1024 (SXGA)   | 6         | 5.66%   |
| 3840x2160 (4K)     | 5         | 4.72%   |
| 1920x1200 (WUXGA)  | 5         | 4.72%   |
| 1600x900 (HD+)     | 5         | 4.72%   |
| 1680x1050 (WSXGA+) | 3         | 2.83%   |
| 3840x1080          | 2         | 1.89%   |
| 1440x900 (WXGA+)   | 2         | 1.89%   |
| 1280x800 (WXGA)    | 2         | 1.89%   |
| 5760x2160          | 1         | 0.94%   |
| 4480x1440          | 1         | 0.94%   |
| 3520x1080          | 1         | 0.94%   |
| 3200x900           | 1         | 0.94%   |
| 3200x1800 (QHD+)   | 1         | 0.94%   |
| 2736x1824          | 1         | 0.94%   |
| 2560x1440 (QHD)    | 1         | 0.94%   |
| 2560x1080          | 1         | 0.94%   |
| 2560x1024          | 1         | 0.94%   |
| 1920x540           | 1         | 0.94%   |
| 1360x768           | 1         | 0.94%   |
| 1024x768 (XGA)     | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 13.46%  |
| Unknown | 14        | 13.46%  |
| 24      | 11        | 10.58%  |
| 27      | 9         | 8.65%   |
| 21      | 8         | 7.69%   |
| 13      | 8         | 7.69%   |
| 19      | 7         | 6.73%   |
| 17      | 7         | 6.73%   |
| 18      | 4         | 3.85%   |
| 23      | 3         | 2.88%   |
| 22      | 3         | 2.88%   |
| 14      | 3         | 2.88%   |
| 54      | 2         | 1.92%   |
| 46      | 2         | 1.92%   |
| 25      | 2         | 1.92%   |
| 72      | 1         | 0.96%   |
| 48      | 1         | 0.96%   |
| 42      | 1         | 0.96%   |
| 32      | 1         | 0.96%   |
| 29      | 1         | 0.96%   |
| 20      | 1         | 0.96%   |
| 12      | 1         | 0.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 24        | 23.3%   |
| 301-350     | 22        | 21.36%  |
| 401-500     | 17        | 16.5%   |
| Unknown     | 14        | 13.59%  |
| 351-400     | 11        | 10.68%  |
| 201-300     | 5         | 4.85%   |
| 1001-1500   | 5         | 4.85%   |
| 601-700     | 2         | 1.94%   |
| 701-800     | 1         | 0.97%   |
| 1501-2000   | 1         | 0.97%   |
| 901-1000    | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 63.27%  |
| Unknown | 14        | 14.29%  |
| 16/10   | 12        | 12.24%  |
| 5/4     | 6         | 6.12%   |
| 4/3     | 1         | 1.02%   |
| 3/2     | 1         | 1.02%   |
| 21/9    | 1         | 1.02%   |
| 1.96    | 1         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 19        | 18.63%  |
| 101-110        | 14        | 13.73%  |
| Unknown        | 14        | 13.73%  |
| 301-350        | 10        | 9.8%    |
| 151-200        | 9         | 8.82%   |
| 81-90          | 7         | 6.86%   |
| 251-300        | 5         | 4.9%    |
| 141-150        | 5         | 4.9%    |
| 121-130        | 5         | 4.9%    |
| 501-1000       | 4         | 3.92%   |
| More than 1000 | 3         | 2.94%   |
| 71-80          | 3         | 2.94%   |
| 61-70          | 1         | 0.98%   |
| 351-500        | 1         | 0.98%   |
| 131-140        | 1         | 0.98%   |
| 91-100         | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 40        | 40.4%   |
| 121-160       | 17        | 17.17%  |
| 101-120       | 17        | 17.17%  |
| Unknown       | 14        | 14.14%  |
| 1-50          | 6         | 6.06%   |
| 161-240       | 3         | 3.03%   |
| More than 240 | 2         | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 78.72%  |
| 2     | 20        | 21.28%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 48        | 35.56%  |
| Realtek Semiconductor    | 47        | 34.81%  |
| Qualcomm Atheros         | 13        | 9.63%   |
| Broadcom                 | 10        | 7.41%   |
| Marvell Technology Group | 4         | 2.96%   |
| Sierra Wireless          | 2         | 1.48%   |
| Broadcom Limited         | 2         | 1.48%   |
| Wilocity                 | 1         | 0.74%   |
| Ultimarc                 | 1         | 0.74%   |
| TP-Link                  | 1         | 0.74%   |
| MediaTek                 | 1         | 0.74%   |
| Huawei Technologies      | 1         | 0.74%   |
| Dell                     | 1         | 0.74%   |
| D-Link System            | 1         | 0.74%   |
| ASIX Electronics         | 1         | 0.74%   |
| Aquantia                 | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 23.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.49%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.21%   |
| Intel Wireless 8260                                               | 4         | 2.56%   |
| Intel Wireless 3165                                               | 4         | 2.56%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.56%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.92%   |
| Sierra Wireless MC8305 Modem                                      | 2         | 1.28%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.28%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 1.28%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2         | 1.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.28%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2         | 1.28%   |
| Intel Wireless 7265                                               | 2         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.28%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.28%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.28%   |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 1.28%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.64%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1         | 0.64%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.64%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.64%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 29        | 48.33%  |
| Qualcomm Atheros         | 10        | 16.67%  |
| Realtek Semiconductor    | 7         | 11.67%  |
| Broadcom                 | 7         | 11.67%  |
| Sierra Wireless          | 2         | 3.33%   |
| Wilocity                 | 1         | 1.67%   |
| TP-Link                  | 1         | 1.67%   |
| MediaTek                 | 1         | 1.67%   |
| Marvell Technology Group | 1         | 1.67%   |
| Dell                     | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 4         | 6.25%   |
| Intel Wireless 3165                                            | 4         | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 6.25%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 3.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 3.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 3.13%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 3.13%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2         | 3.13%   |
| Intel Wireless 7265                                            | 2         | 3.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 3.13%   |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 3.13%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 1.56%   |
| TP-Link 802.11ac NIC                                           | 1         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| MediaTek WiFi                                                  | 1         | 1.56%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.56%   |
| Intel Wireless-AC 9260                                         | 1         | 1.56%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.56%   |
| Intel Wireless 7260                                            | 1         | 1.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.56%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 1.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.56%   |
| Broadcom BCM4323 802.11abgn Wireless Adapter                   | 1         | 1.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 48.86%  |
| Intel                    | 30        | 34.09%  |
| Qualcomm Atheros         | 4         | 4.55%   |
| Marvell Technology Group | 3         | 3.41%   |
| Broadcom                 | 3         | 3.41%   |
| Broadcom Limited         | 2         | 2.27%   |
| D-Link System            | 1         | 1.14%   |
| ASIX Electronics         | 1         | 1.14%   |
| Aquantia                 | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 41.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 7.78%   |
| Intel I211 Gigabit Network Connection                             | 5         | 5.56%   |
| Intel Ethernet Connection I217-V                                  | 3         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.22%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.22%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 2.22%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.11%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.11%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.11%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.11%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 1.11%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.11%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.11%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.11%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.11%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 1.11%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.11%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.11%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.11%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.11%   |
| ASIX AX88772B                                                     | 1         | 1.11%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 60.58%  |
| WiFi     | 52        | 37.96%  |
| Modem    | 1         | 0.73%   |
| Unknown  | 1         | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 58.76%  |
| WiFi     | 40        | 41.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 53.61%  |
| 2     | 38        | 39.18%  |
| 3     | 4         | 4.12%   |
| 0     | 2         | 2.06%   |
| 4     | 1         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 81        | 84.38%  |
| Yes  | 15        | 15.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 23        | 43.4%   |
| Cambridge Silicon Radio | 8         | 15.09%  |
| Hewlett-Packard         | 3         | 5.66%   |
| Broadcom                | 3         | 5.66%   |
| ASUSTek Computer        | 3         | 5.66%   |
| Realtek Semiconductor   | 2         | 3.77%   |
| Lite-On Technology      | 2         | 3.77%   |
| IMC Networks            | 2         | 3.77%   |
| Foxconn / Hon Hai       | 2         | 3.77%   |
| Belkin Components       | 2         | 3.77%   |
| Marvell Semiconductor   | 1         | 1.89%   |
| Dell                    | 1         | 1.89%   |
| Apple                   | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 18.87%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 15.09%  |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 7.55%   |
| Intel AX200 Bluetooth                               | 4         | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5.66%   |
| Realtek Bluetooth Radio                             | 2         | 3.77%   |
| Lite-On Bluetooth Device                            | 2         | 3.77%   |
| IMC Networks Bluetooth Device                       | 2         | 3.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.77%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 3.77%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.89%   |
| Intel AX201 Bluetooth                               | 1         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.89%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.89%   |
| Broadcom Bluetooth dongle                           | 1         | 1.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.89%   |
| Belkin Components F8T013 Bluetooth Adapter          | 1         | 1.89%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.89%   |
| ASUS Bluetooth Device                               | 1         | 1.89%   |
| ASUS BCM20702A0                                     | 1         | 1.89%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 64        | 44.14%  |
| Nvidia                     | 36        | 24.83%  |
| AMD                        | 29        | 20%     |
| C-Media Electronics        | 8         | 5.52%   |
| Samsung Electronics        | 1         | 0.69%   |
| Mackie Designs             | 1         | 0.69%   |
| Logitech                   | 1         | 0.69%   |
| iCreate Technologies       | 1         | 0.69%   |
| Corsair                    | 1         | 0.69%   |
| BEHRINGER International    | 1         | 0.69%   |
| ASUSTek Computer           | 1         | 0.69%   |
| Altec Lansing Technologies | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 5.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 4.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 4.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 3.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 3.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 3.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.48%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.48%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3         | 1.86%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.24%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.24%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.24%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 1.24%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.24%   |
| Samsung Electronics USB C Earphones                                        | 1         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.62%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.62%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 16        | 24.24%  |
| Unknown             | 11        | 16.67%  |
| Samsung Electronics | 10        | 15.15%  |
| SK hynix            | 6         | 9.09%   |
| G.Skill             | 6         | 9.09%   |
| Micron Technology   | 4         | 6.06%   |
| Corsair             | 4         | 6.06%   |
| Unknown (ABCD)      | 2         | 3.03%   |
| Team                | 2         | 3.03%   |
| Crucial             | 2         | 3.03%   |
| Smart               | 1         | 1.52%   |
| Nanya Technology    | 1         | 1.52%   |
| Goodram             | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 2.78%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 2.78%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s          | 2         | 2.78%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.39%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 1.39%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 1.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.39%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 1.39%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 1.39%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 1.39%   |
| Team RAM Elite-16 8GB DIMM DDR3 1600MT/s                         | 1         | 1.39%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                            | 1         | 1.39%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.39%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.39%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s             | 1         | 1.39%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3600MT/s             | 1         | 1.39%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s              | 1         | 1.39%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1600MT/s               | 1         | 1.39%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 42.11%  |
| DDR4    | 22        | 38.6%   |
| DDR2    | 4         | 7.02%   |
| Unknown | 3         | 5.26%   |
| LPDDR4  | 2         | 3.51%   |
| LPDDR3  | 2         | 3.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 33        | 57.89%  |
| SODIMM       | 23        | 40.35%  |
| Row Of Chips | 1         | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 44.26%  |
| 4096  | 21        | 34.43%  |
| 2048  | 7         | 11.48%  |
| 16384 | 6         | 9.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 19        | 30.16%  |
| 2400  | 7         | 11.11%  |
| 2133  | 5         | 7.94%   |
| 1333  | 5         | 7.94%   |
| 3200  | 4         | 6.35%   |
| 2667  | 4         | 6.35%   |
| 800   | 3         | 4.76%   |
| 3600  | 2         | 3.17%   |
| 3334  | 2         | 3.17%   |
| 1867  | 2         | 3.17%   |
| 667   | 2         | 3.17%   |
| 3733  | 1         | 1.59%   |
| 3500  | 1         | 1.59%   |
| 3466  | 1         | 1.59%   |
| 3400  | 1         | 1.59%   |
| 3000  | 1         | 1.59%   |
| 1334  | 1         | 1.59%   |
| 1066  | 1         | 1.59%   |
| 975   | 1         | 1.59%   |

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
| Chicony Electronics                    | 13        | 31.71%  |
| Microdia                               | 5         | 12.2%   |
| Logitech                               | 4         | 9.76%   |
| Realtek Semiconductor                  | 3         | 7.32%   |
| Sunplus Innovation Technology          | 2         | 4.88%   |
| Microsoft                              | 2         | 4.88%   |
| IMC Networks                           | 2         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Apple                                  | 2         | 4.88%   |
| WaveRider Communications               | 1         | 2.44%   |
| Suyin                                  | 1         | 2.44%   |
| Primax Electronics                     | 1         | 2.44%   |
| Leap Motion                            | 1         | 2.44%   |
| Alcor Micro                            | 1         | 2.44%   |
| Acer                                   | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 3         | 7.14%   |
| Chicony Integrated Camera                                                  | 3         | 7.14%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.76%   |
| Microdia Camera                                                            | 2         | 4.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 4.76%   |
| Chicony FJ Camera                                                          | 2         | 4.76%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 2.38%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 2.38%   |
| Sunplus Full HD webcam                                                     | 1         | 2.38%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 2.38%   |
| Realtek USB Camera                                                         | 1         | 2.38%   |
| Primax HP Truevision FHD                                                   | 1         | 2.38%   |
| Microsoft LifeCam VX-800                                                   | 1         | 2.38%   |
| Microsoft LifeCam HD-3000                                                  | 1         | 2.38%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2.38%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.38%   |
| Microdia Integrated Webcam                                                 | 1         | 2.38%   |
| Logitech Webcam C210                                                       | 1         | 2.38%   |
| Logitech Webcam C200                                                       | 1         | 2.38%   |
| Logitech Webcam C110                                                       | 1         | 2.38%   |
| Logitech QuickCam Pro 9000                                                 | 1         | 2.38%   |
| Leap Motion Controller                                                     | 1         | 2.38%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 2.38%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.38%   |
| Chicony Integrated IR Camera                                               | 1         | 2.38%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 2.38%   |
| Chicony HD WebCam                                                          | 1         | 2.38%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 1         | 2.38%   |
| Apple Built-in iSight                                                      | 1         | 2.38%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 2.38%   |
| Acer BisonCam,NB Pro                                                       | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| AuthenTec                  | 3         | 33.33%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor       | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI            | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner       | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader         | 1         | 11.11%  |
| AuthenTec Fingerprint Sensor               | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 50%     |
| O2 Micro | 2         | 33.33%  |
| Avtor    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 33.33%  |
| Broadcom 5880                                                                | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Avtor SecureToken                                                            | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 66        | 68.04%  |
| 1     | 24        | 24.74%  |
| 2     | 5         | 5.15%   |
| 3     | 2         | 2.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 30.56%  |
| Fingerprint reader       | 9         | 25%     |
| Chipcard                 | 6         | 16.67%  |
| Net/wireless             | 3         | 8.33%   |
| Multimedia controller    | 3         | 8.33%   |
| Unassigned class         | 1         | 2.78%   |
| Sound                    | 1         | 2.78%   |
| Communication controller | 1         | 2.78%   |
| Camera                   | 1         | 2.78%   |

