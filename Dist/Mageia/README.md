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

Total: 196

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek   | PRIME B450-PLUS             | Desktop     | [863f0b5c06](https://linux-hardware.org/?probe=863f0b5c06) | Dec 29, 2023 |
| Lenovo    | 317C SDK0J40700 WIN 3258... | Desktop     | [f24d5f341c](https://linux-hardware.org/?probe=f24d5f341c) | Dec 28, 2023 |
| Gigabyte  | H81M-S2H                    | Desktop     | [8dd5a975f9](https://linux-hardware.org/?probe=8dd5a975f9) | Dec 02, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K660... | Notebook    | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K660... | Notebook    | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| HP        | 255 15.6 inch G9 Noteboo... | Notebook    | [b1394cc278](https://linux-hardware.org/?probe=b1394cc278) | Oct 30, 2023 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [e18680d1f4](https://linux-hardware.org/?probe=e18680d1f4) | Oct 29, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [99aded4434](https://linux-hardware.org/?probe=99aded4434) | Oct 17, 2023 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [ff0a453a0e](https://linux-hardware.org/?probe=ff0a453a0e) | Oct 13, 2023 |
| Lenovo    | IdeaPad Slim 3 15AMN8 82... | Notebook    | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Lenovo    | IdeaPad Slim 3 15AMN8 82... | Notebook    | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [47987fd9dd](https://linux-hardware.org/?probe=47987fd9dd) | Oct 07, 2023 |
| Dell      | 0GK35Y A00                  | Desktop     | [d785138af0](https://linux-hardware.org/?probe=d785138af0) | Sep 03, 2023 |
| Fujitsu   | S6420                       | Notebook    | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| HP        | Pavilion Notebook           | Notebook    | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| Lenovo    | Yoga 720-15IKB 80X7         | Convertible | [b691f28c43](https://linux-hardware.org/?probe=b691f28c43) | Aug 10, 2023 |
| Dell      | Latitude E5470              | Notebook    | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| ASUSTek   | Q551LN                      | Notebook    | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Gigabyte  | Z87X-UD5H-CF                | Desktop     | [6f489ed497](https://linux-hardware.org/?probe=6f489ed497) | Jul 20, 2023 |
| HP        | Laptop 14-cm0xxx            | Notebook    | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| Compaq    | 420                         | Notebook    | [6f4350d53e](https://linux-hardware.org/?probe=6f4350d53e) | Jul 10, 2023 |
| ASUSTek   | K73SD                       | Notebook    | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | Desktop     | [a2b832afa2](https://linux-hardware.org/?probe=a2b832afa2) | Apr 30, 2023 |
| Gigabyte  | Z97-D3H-CF                  | Desktop     | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| Gigabyte  | Z97-D3H-CF                  | Desktop     | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Dell      | Latitude 7370               | Notebook    | [a254d0d7f1](https://linux-hardware.org/?probe=a254d0d7f1) | Apr 02, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Mageia 8 | 61        | 50%     |
| Mageia 7 | 33        | 27.05%  |
| Mageia 9 | 23        | 18.85%  |
| Mageia 6 | 4         | 3.28%   |
| Mageia 5 | 1         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Mageia | 109       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7  | 13        | 8.5%    |
| 5.10.27-desktop-1.mga8 | 8         | 5.23%   |
| 5.7.19-desktop-1.mga7  | 7         | 4.58%   |
| 5.15.32-desktop-1.mga8 | 5         | 3.27%   |
| 6.4.16-desktop-3.mga9  | 4         | 2.61%   |
| 5.6.14-desktop-2.mga7  | 4         | 2.61%   |
| 5.5.4-desktop-1.mga7   | 4         | 2.61%   |
| 5.15.23-desktop-1.mga8 | 4         | 2.61%   |
| 5.10.25-desktop-1.mga8 | 4         | 2.61%   |
| 6.4.9-desktop-4.mga9   | 3         | 1.96%   |
| 5.5.9-desktop-1.mga7   | 3         | 1.96%   |
| 5.10.12-desktop-1.mga7 | 3         | 1.96%   |
| 6.4.8-desktop-6.mga9   | 2         | 1.31%   |
| 5.6.6-desktop-1.mga7   | 2         | 1.31%   |
| 5.3.7-desktop-4.mga7   | 2         | 1.31%   |
| 5.17.4-desktop-2.mga8  | 2         | 1.31%   |
| 5.16.10-desktop-2.mga8 | 2         | 1.31%   |
| 5.15.98-desktop-1.mga8 | 2         | 1.31%   |
| 5.15.4-desktop-1.mga8  | 2         | 1.31%   |
| 5.15.35-desktop-2.mga8 | 2         | 1.31%   |
| 5.15.16-desktop-1.mga8 | 2         | 1.31%   |
| 5.15.11-desktop-3.mga8 | 2         | 1.31%   |
| 5.10.60-desktop-2.mga8 | 2         | 1.31%   |
| 5.10.52-desktop-1.mga8 | 2         | 1.31%   |
| 5.10.20-desktop-2.mga7 | 2         | 1.31%   |
| 5.10.14-desktop-1.mga7 | 2         | 1.31%   |
| 6.5.11-desktop-5.mga9  | 1         | 0.65%   |
| 6.4.6-desktop-2.mga9   | 1         | 0.65%   |
| 6.4.3-desktop-1.mga9   | 1         | 0.65%   |
| 6.2.6-desktop-1.mga9   | 1         | 0.65%   |
| 6.2.2-desktop-2.mga9   | 1         | 0.65%   |
| 6.1.6-desktop-1.mga8   | 1         | 0.65%   |
| 6.1.41-desktop-1.mga8  | 1         | 0.65%   |
| 6.1.23-desktop-1.mga8  | 1         | 0.65%   |
| 6.1.14-desktop-1.mga9  | 1         | 0.65%   |
| 6.0.10-desktop-1.mga9  | 1         | 0.65%   |
| 5.9.6-desktop-1.mga8   | 1         | 0.65%   |
| 5.9.3-desktop-1.mga8   | 1         | 0.65%   |
| 5.9.16-desktop-1.mga7  | 1         | 0.65%   |
| 5.9.11-desktop-3.mga8  | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.19  | 18        | 11.92%  |
| 5.10.27 | 8         | 5.3%    |
| 5.15.32 | 5         | 3.31%   |
| 6.4.16  | 4         | 2.65%   |
| 5.6.14  | 4         | 2.65%   |
| 5.5.4   | 4         | 2.65%   |
| 5.15.23 | 4         | 2.65%   |
| 5.10.25 | 4         | 2.65%   |
| 5.10.12 | 4         | 2.65%   |
| 6.4.9   | 3         | 1.99%   |
| 5.5.9   | 3         | 1.99%   |
| 6.4.8   | 2         | 1.32%   |
| 5.6.6   | 2         | 1.32%   |
| 5.3.7   | 2         | 1.32%   |
| 5.17.4  | 2         | 1.32%   |
| 5.16.18 | 2         | 1.32%   |
| 5.16.10 | 2         | 1.32%   |
| 5.15.98 | 2         | 1.32%   |
| 5.15.4  | 2         | 1.32%   |
| 5.15.35 | 2         | 1.32%   |
| 5.15.16 | 2         | 1.32%   |
| 5.15.11 | 2         | 1.32%   |
| 5.10.60 | 2         | 1.32%   |
| 5.10.52 | 2         | 1.32%   |
| 5.10.20 | 2         | 1.32%   |
| 5.10.16 | 2         | 1.32%   |
| 5.10.14 | 2         | 1.32%   |
| 6.5.11  | 1         | 0.66%   |
| 6.4.6   | 1         | 0.66%   |
| 6.4.3   | 1         | 0.66%   |
| 6.2.6   | 1         | 0.66%   |
| 6.2.2   | 1         | 0.66%   |
| 6.1.6   | 1         | 0.66%   |
| 6.1.41  | 1         | 0.66%   |
| 6.1.23  | 1         | 0.66%   |
| 6.1.14  | 1         | 0.66%   |
| 6.0.10  | 1         | 0.66%   |
| 5.9.6   | 1         | 0.66%   |
| 5.9.3   | 1         | 0.66%   |
| 5.9.16  | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 20.71%  |
| 5.10    | 27        | 19.29%  |
| 5.7     | 19        | 13.57%  |
| 6.4     | 11        | 7.86%   |
| 5.5     | 8         | 5.71%   |
| 5.6     | 7         | 5%      |
| 5.9     | 5         | 3.57%   |
| 6.1     | 4         | 2.86%   |
| 5.16    | 4         | 2.86%   |
| 4.14    | 3         | 2.14%   |
| 6.2     | 2         | 1.43%   |
| 5.8     | 2         | 1.43%   |
| 5.4     | 2         | 1.43%   |
| 5.3     | 2         | 1.43%   |
| 5.19    | 2         | 1.43%   |
| 5.17    | 2         | 1.43%   |
| 5.14    | 2         | 1.43%   |
| 6.5     | 1         | 0.71%   |
| 6.0     | 1         | 0.71%   |
| 5.18    | 1         | 0.71%   |
| 5.13    | 1         | 0.71%   |
| 5.12    | 1         | 0.71%   |
| 5.1     | 1         | 0.71%   |
| 4.9     | 1         | 0.71%   |
| 4.19    | 1         | 0.71%   |
| 4.1     | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 98.17%  |
| i686   | 2         | 1.83%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 50        | 41.67%  |
| KDE           | 24        | 20%     |
| GNOME         | 15        | 12.5%   |
| Unknown       | 9         | 7.5%    |
| XFCE          | 5         | 4.17%   |
| MATE          | 5         | 4.17%   |
| Cinnamon      | 5         | 4.17%   |
| LXDE          | 3         | 2.5%    |
| X-Cinnamon    | 1         | 0.83%   |
| LXQt          | 1         | 0.83%   |
| KDE4          | 1         | 0.83%   |
| GNOME Classic | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 100       | 90.91%  |
| Wayland | 9         | 8.18%   |
| Tty     | 1         | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 49.09%  |
| SDDM    | 40        | 36.36%  |
| LightDM | 7         | 6.36%   |
| GDM     | 5         | 4.55%   |
| TDM     | 3         | 2.73%   |
| XDM     | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| fr_FR   | 24        | 21.62%  |
| en_US   | 19        | 17.12%  |
| de_DE   | 11        | 9.91%   |
| en_GB   | 8         | 7.21%   |
| Unknown | 8         | 7.21%   |
| ru_RU   | 7         | 6.31%   |
| pt_BR   | 4         | 3.6%    |
| it_IT   | 4         | 3.6%    |
| en_CA   | 3         | 2.7%    |
| sv_SE   | 2         | 1.8%    |
| pl_PL   | 2         | 1.8%    |
| hu_HU   | 2         | 1.8%    |
| es_MX   | 2         | 1.8%    |
| es_GT   | 2         | 1.8%    |
| bg_BG   | 2         | 1.8%    |
| zh_TW   | 1         | 0.9%    |
| sl_SI   | 1         | 0.9%    |
| sk_SK   | 1         | 0.9%    |
| ro_RO   | 1         | 0.9%    |
| fr_BE   | 1         | 0.9%    |
| es_ES   | 1         | 0.9%    |
| es_CR   | 1         | 0.9%    |
| es_CO   | 1         | 0.9%    |
| es_CL   | 1         | 0.9%    |
| es_AR   | 1         | 0.9%    |
| cs_CZ   | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 63        | 55.26%  |
| EFI  | 51        | 44.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 92        | 82.88%  |
| Xfs      | 7         | 6.31%   |
| Unknown  | 6         | 5.41%   |
| Btrfs    | 4         | 3.6%    |
| Reiserfs | 1         | 0.9%    |
| Overlay  | 1         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 46        | 40.71%  |
| Unknown | 45        | 39.82%  |
| MBR     | 22        | 19.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 85.32%  |
| Yes       | 16        | 14.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 77.68%  |
| Yes       | 25        | 22.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 25        | 22.94%  |
| Gigabyte Technology | 19        | 17.43%  |
| Hewlett-Packard     | 13        | 11.93%  |
| Lenovo              | 11        | 10.09%  |
| Dell                | 9         | 8.26%   |
| MSI                 | 7         | 6.42%   |
| ASRock              | 6         | 5.5%    |
| Fujitsu             | 3         | 2.75%   |
| Notebook            | 2         | 1.83%   |
| Medion              | 2         | 1.83%   |
| Acer                | 2         | 1.83%   |
| ZOTAC               | 1         | 0.92%   |
| Vorke               | 1         | 0.92%   |
| Toshiba             | 1         | 0.92%   |
| Schenker            | 1         | 0.92%   |
| Microsoft           | 1         | 0.92%   |
| Megaware            | 1         | 0.92%   |
| Kiano               | 1         | 0.92%   |
| Intel               | 1         | 0.92%   |
| ECS                 | 1         | 0.92%   |
| Apple               | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 2.75%   |
| Gigabyte Z68X-UD3H-B3                    | 2         | 1.83%   |
| Gigabyte H81M-S2H                        | 2         | 1.83%   |
| Gigabyte B450M DS3H                      | 2         | 1.83%   |
| Dell Precision WorkStation T3400         | 2         | 1.83%   |
| ASUS SABERTOOTH 990FX R2.0               | 2         | 1.83%   |
| Vorke V1 Plus                            | 1         | 0.92%   |
| Toshiba dynabook R73/A                   | 1         | 0.92%   |
| Schenker VIA_14_SVI14E20                 | 1         | 0.92%   |
| Notebook NL40_50GU                       | 1         | 0.92%   |
| Notebook NH5x_NH7x_HHx_HJx_HKx           | 1         | 0.92%   |
| MSI MS-7D09                              | 1         | 0.92%   |
| MSI MS-7C82                              | 1         | 0.92%   |
| MSI MS-7C37                              | 1         | 0.92%   |
| MSI MS-7B31                              | 1         | 0.92%   |
| MSI MS-7B23                              | 1         | 0.92%   |
| MSI MS-7A70                              | 1         | 0.92%   |
| MSI MS-7816                              | 1         | 0.92%   |
| Microsoft Surface Pro 4                  | 1         | 0.92%   |
| Megaware MW-G31T-M7                      | 1         | 0.92%   |
| Medion MD34161/C708                      | 1         | 0.92%   |
| Medion DEFENDER P10                      | 1         | 0.92%   |
| Lenovo Yoga 720-15IKB 80X7               | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1741F | 1         | 0.92%   |
| Lenovo ThinkPad T430 2342A19             | 1         | 0.92%   |
| Lenovo ThinkCentre M92p 2992A7U          | 1         | 0.92%   |
| Lenovo ThinkCentre M58e 7491B1G          | 1         | 0.92%   |
| Lenovo ThinkCentre A57 970274G           | 1         | 0.92%   |
| Lenovo IdeaPad Slim 3 15AMN8 82XQ        | 1         | 0.92%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 0.92%   |
| Lenovo IdeaCentre 5 14IMB05 90NA0000US   | 1         | 0.92%   |
| Lenovo G480 20149                        | 1         | 0.92%   |
| Lenovo 70A4000HUX ThinkServer TS140      | 1         | 0.92%   |
| Kiano SlimNote 15.6                      | 1         | 0.92%   |
| Intel STL2                               | 1         | 0.92%   |
| HP Z440 Workstation                      | 1         | 0.92%   |
| HP Z420 Workstation                      | 1         | 0.92%   |
| HP Spectre 13 Ultrabook                  | 1         | 0.92%   |
| HP ProBook 5330m                         | 1         | 0.92%   |
| HP ProBook 445 G7                        | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Precision         | 4         | 3.67%   |
| Dell Latitude          | 4         | 3.67%   |
| ASUS PRIME             | 4         | 3.67%   |
| Lenovo ThinkCentre     | 3         | 2.75%   |
| ASUS SABERTOOTH        | 3         | 2.75%   |
| Unknown                | 3         | 2.75%   |
| Lenovo ThinkPad        | 2         | 1.83%   |
| Lenovo IdeaPad         | 2         | 1.83%   |
| HP ProBook             | 2         | 1.83%   |
| HP Pavilion            | 2         | 1.83%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 1.83%   |
| Gigabyte H81M-S2H      | 2         | 1.83%   |
| Gigabyte GA-78LMT-USB3 | 2         | 1.83%   |
| Gigabyte B450M         | 2         | 1.83%   |
| ASUS VivoBook          | 2         | 1.83%   |
| Acer Aspire            | 2         | 1.83%   |
| Vorke V1               | 1         | 0.92%   |
| Toshiba dynabook       | 1         | 0.92%   |
| Schenker VIA           | 1         | 0.92%   |
| Notebook NL40          | 1         | 0.92%   |
| Notebook NH5x          | 1         | 0.92%   |
| MSI MS-7D09            | 1         | 0.92%   |
| MSI MS-7C82            | 1         | 0.92%   |
| MSI MS-7C37            | 1         | 0.92%   |
| MSI MS-7B31            | 1         | 0.92%   |
| MSI MS-7B23            | 1         | 0.92%   |
| MSI MS-7A70            | 1         | 0.92%   |
| MSI MS-7816            | 1         | 0.92%   |
| Microsoft Surface      | 1         | 0.92%   |
| Megaware MW-G31T-M7    | 1         | 0.92%   |
| Medion MD34161         | 1         | 0.92%   |
| Medion DEFENDER        | 1         | 0.92%   |
| Lenovo Yoga            | 1         | 0.92%   |
| Lenovo IdeaCentre      | 1         | 0.92%   |
| Lenovo G480            | 1         | 0.92%   |
| Lenovo 70A4000HUX      | 1         | 0.92%   |
| Kiano SlimNote         | 1         | 0.92%   |
| Intel STL2             | 1         | 0.92%   |
| HP Z440                | 1         | 0.92%   |
| HP Z420                | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 14        | 12.84%  |
| 2012 | 13        | 11.93%  |
| 2013 | 11        | 10.09%  |
| 2017 | 9         | 8.26%   |
| 2014 | 8         | 7.34%   |
| 2016 | 7         | 6.42%   |
| 2008 | 7         | 6.42%   |
| 2020 | 6         | 5.5%    |
| 2019 | 6         | 5.5%    |
| 2011 | 6         | 5.5%    |
| 2021 | 4         | 3.67%   |
| 2015 | 4         | 3.67%   |
| 2010 | 4         | 3.67%   |
| 2009 | 4         | 3.67%   |
| 2022 | 2         | 1.83%   |
| 2007 | 2         | 1.83%   |
| 2023 | 1         | 0.92%   |
| 2002 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 68        | 62.39%  |
| Notebook    | 38        | 34.86%  |
| Tablet      | 1         | 0.92%   |
| Convertible | 1         | 0.92%   |
| All in one  | 1         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 23.01%  |
| 16.01-24.0  | 26        | 23.01%  |
| 8.01-16.0   | 22        | 19.47%  |
| 32.01-64.0  | 15        | 13.27%  |
| 3.01-4.0    | 15        | 13.27%  |
| 64.01-256.0 | 5         | 4.42%   |
| 24.01-32.0  | 2         | 1.77%   |
| 2.01-3.0    | 1         | 0.88%   |
| 1.01-2.0    | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 41        | 31.3%   |
| 1.01-2.0   | 31        | 23.66%  |
| 4.01-8.0   | 29        | 22.14%  |
| 3.01-4.0   | 18        | 13.74%  |
| 8.01-16.0  | 7         | 5.34%   |
| 0.51-1.0   | 3         | 2.29%   |
| 16.01-24.0 | 2         | 1.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 42.11%  |
| 2      | 30        | 26.32%  |
| 3      | 20        | 17.54%  |
| 5      | 7         | 6.14%   |
| 4      | 5         | 4.39%   |
| 6      | 2         | 1.75%   |
| 8      | 1         | 0.88%   |
| 7      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 51.38%  |
| Yes       | 53        | 48.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 88.99%  |
| No        | 12        | 11.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 58.18%  |
| No        | 46        | 41.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 55.05%  |
| No        | 49        | 44.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| France      | 25        | 22.94%  |
| USA         | 15        | 13.76%  |
| Germany     | 11        | 10.09%  |
| UK          | 8         | 7.34%   |
| Russia      | 4         | 3.67%   |
| Italy       | 4         | 3.67%   |
| Canada      | 4         | 3.67%   |
| Brazil      | 4         | 3.67%   |
| Ukraine     | 3         | 2.75%   |
| Sweden      | 2         | 1.83%   |
| Romania     | 2         | 1.83%   |
| Poland      | 2         | 1.83%   |
| Mexico      | 2         | 1.83%   |
| Guatemala   | 2         | 1.83%   |
| Greece      | 2         | 1.83%   |
| Colombia    | 2         | 1.83%   |
| Bulgaria    | 2         | 1.83%   |
| Taiwan      | 1         | 0.92%   |
| Slovenia    | 1         | 0.92%   |
| Slovakia    | 1         | 0.92%   |
| Netherlands | 1         | 0.92%   |
| Luxembourg  | 1         | 0.92%   |
| Kenya       | 1         | 0.92%   |
| Indonesia   | 1         | 0.92%   |
| Hungary     | 1         | 0.92%   |
| Czechia     | 1         | 0.92%   |
| Costa Rica  | 1         | 0.92%   |
| Chile       | 1         | 0.92%   |
| Belgium     | 1         | 0.92%   |
| Belarus     | 1         | 0.92%   |
| Australia   | 1         | 0.92%   |
| Argentina   | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Rommerskirchen        | 3         | 2.29%   |
| Paris                 | 3         | 2.29%   |
| Mala Danylivka        | 3         | 2.29%   |
| Kharkiv               | 3         | 2.29%   |
| Woking                | 2         | 1.53%   |
| Woincourt             | 2         | 1.53%   |
| Waterloo              | 2         | 1.53%   |
| Upper Norwood         | 2         | 1.53%   |
| Strasbourg            | 2         | 1.53%   |
| Sao Paulo             | 2         | 1.53%   |
| Oakland               | 2         | 1.53%   |
| Guatemala City        | 2         | 1.53%   |
| Grants Pass           | 2         | 1.53%   |
| Bogotá               | 2         | 1.53%   |
| Yakutsk               | 1         | 0.76%   |
| Wiwersheim            | 1         | 0.76%   |
| Voronezh              | 1         | 0.76%   |
| Vanves                | 1         | 0.76%   |
| Uzhhorod              | 1         | 0.76%   |
| Tver                  | 1         | 0.76%   |
| Turin                 | 1         | 0.76%   |
| Tours                 | 1         | 0.76%   |
| Toulouse              | 1         | 0.76%   |
| Thiais                | 1         | 0.76%   |
| Surabaya              | 1         | 0.76%   |
| Sternberk             | 1         | 0.76%   |
| Sofia                 | 1         | 0.76%   |
| Sartrouville          | 1         | 0.76%   |
| Santiago              | 1         | 0.76%   |
| Sant'Angelo Lodigiano | 1         | 0.76%   |
| San Isidro            | 1         | 0.76%   |
| San Antonio           | 1         | 0.76%   |
| Saint-Michel-sur-Orge | 1         | 0.76%   |
| Saint-Etienne         | 1         | 0.76%   |
| Rome                  | 1         | 0.76%   |
| Roehampton            | 1         | 0.76%   |
| Rio de Janeiro        | 1         | 0.76%   |
| Regina                | 1         | 0.76%   |
| Quincy                | 1         | 0.76%   |
| Quierschied           | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 48        | 135    | 22.64%  |
| Seagate                 | 30        | 53     | 14.15%  |
| Samsung Electronics     | 29        | 38     | 13.68%  |
| Toshiba                 | 14        | 22     | 6.6%    |
| Kingston                | 13        | 22     | 6.13%   |
| SanDisk                 | 8         | 14     | 3.77%   |
| Hitachi                 | 8         | 8      | 3.77%   |
| Crucial                 | 8         | 14     | 3.77%   |
| Unknown                 | 6         | 6      | 2.83%   |
| PNY                     | 5         | 8      | 2.36%   |
| HGST                    | 5         | 9      | 2.36%   |
| Intel                   | 4         | 4      | 1.89%   |
| A-DATA Technology       | 4         | 9      | 1.89%   |
| SK hynix                | 3         | 4      | 1.42%   |
| Phison Electronics      | 2         | 3      | 0.94%   |
| Phison                  | 2         | 3      | 0.94%   |
| OCZ-VERTEX              | 2         | 2      | 0.94%   |
| OCZ                     | 2         | 2      | 0.94%   |
| XPG                     | 1         | 4      | 0.47%   |
| Verbatim                | 1         | 1      | 0.47%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.47%   |
| Transcend               | 1         | 1      | 0.47%   |
| TO Exter                | 1         | 1      | 0.47%   |
| Team                    | 1         | 1      | 0.47%   |
| PNY CS90                | 1         | 1      | 0.47%   |
| LDLC                    | 1         | 1      | 0.47%   |
| KingFast                | 1         | 2      | 0.47%   |
| JMicron Technology      | 1         | 1      | 0.47%   |
| HUAWEI                  | 1         | 1      | 0.47%   |
| Hewlett-Packard         | 1         | 1      | 0.47%   |
| Gigabyte Technology     | 1         | 1      | 0.47%   |
| Fujitsu                 | 1         | 1      | 0.47%   |
| FORESEE                 | 1         | 1      | 0.47%   |
| Emtec                   | 1         | 1      | 0.47%   |
| Corsair                 | 1         | 1      | 0.47%   |
| China                   | 1         | 1      | 0.47%   |
| ASMedia                 | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| WDC WD2500BEVT-22ZCT0 250GB      | 4         | 1.68%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4         | 1.68%   |
| Samsung SSD 860 EVO 500GB        | 4         | 1.68%   |
| Toshiba HDWD110 1TB              | 3         | 1.26%   |
| Samsung SSD 860 EVO 250GB        | 3         | 1.26%   |
| Samsung SSD 850 EVO 500GB        | 3         | 1.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.84%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2         | 0.84%   |
| WDC WDS100T2B0A 1TB SSD          | 2         | 0.84%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 2         | 0.84%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2         | 0.84%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2         | 0.84%   |
| WDC WD10EFRX-68PJCN0 1TB         | 2         | 0.84%   |
| Toshiba MQ01ABF050 500GB         | 2         | 0.84%   |
| Toshiba HDWD120 2TB              | 2         | 0.84%   |
| Seagate ST3500418AS 500GB        | 2         | 0.84%   |
| Seagate ST32000644NS 2TB         | 2         | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB   | 2         | 0.84%   |
| SanDisk SDSSDA120G 120GB         | 2         | 0.84%   |
| SanDisk Extreme SSD 500GB        | 2         | 0.84%   |
| Samsung NVMe SSD Drive 500GB     | 2         | 0.84%   |
| PNY CS900 120GB SSD              | 2         | 0.84%   |
| OCZ-VERTEX PLUS R2 128GB SSD     | 2         | 0.84%   |
| Kingston SV300S37A240G 240GB SSD | 2         | 0.84%   |
| Kingston SH103S3120G 120GB SSD   | 2         | 0.84%   |
| Kingston SA400S37120G 120GB SSD  | 2         | 0.84%   |
| Intel SSDSC2CW120A3 120GB        | 2         | 0.84%   |
| Hitachi HDS722020ALA330 2TB      | 2         | 0.84%   |
| HGST HUS726040ALE611 4TB         | 2         | 0.84%   |
| Crucial CT500MX500SSD1 500GB     | 2         | 0.84%   |
| Crucial CT120BX500SSD1 120GB     | 2         | 0.84%   |
| XPG NVMe SSD Drive 2TB           | 1         | 0.42%   |
| XPG NVMe SSD Drive 1024GB        | 1         | 0.42%   |
| WDC WDS500G3XHC-00SJG0 500GB     | 1         | 0.42%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 0.42%   |
| WDC WD800BB-00JHC0 80GB          | 1         | 0.42%   |
| WDC WD50EFRX-68L0BN1 5TB         | 1         | 0.42%   |
| WDC WD5000LPLX-66ZNTT1 500GB     | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 115    | 37.5%   |
| Seagate             | 29        | 47     | 27.88%  |
| Toshiba             | 13        | 21     | 12.5%   |
| Hitachi             | 8         | 8      | 7.69%   |
| Samsung Electronics | 5         | 9      | 4.81%   |
| HGST                | 5         | 9      | 4.81%   |
| Unknown             | 2         | 2      | 1.92%   |
| TO Exter            | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| Fujitsu             | 1         | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 20.78%  |
| Kingston            | 10        | 16     | 12.99%  |
| WDC                 | 8         | 18     | 10.39%  |
| Crucial             | 8         | 14     | 10.39%  |
| SanDisk             | 6         | 8      | 7.79%   |
| PNY                 | 5         | 8      | 6.49%   |
| A-DATA Technology   | 4         | 9      | 5.19%   |
| Intel               | 3         | 3      | 3.9%    |
| OCZ-VERTEX          | 2         | 2      | 2.6%    |
| OCZ                 | 2         | 2      | 2.6%    |
| Verbatim            | 1         | 1      | 1.3%    |
| Transcend           | 1         | 1      | 1.3%    |
| Team                | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| PNY CS90            | 1         | 1      | 1.3%    |
| LDLC                | 1         | 1      | 1.3%    |
| KingFast            | 1         | 2      | 1.3%    |
| JMicron Technology  | 1         | 1      | 1.3%    |
| FORESEE             | 1         | 1      | 1.3%    |
| Emtec               | 1         | 1      | 1.3%    |
| Corsair             | 1         | 1      | 1.3%    |
| China               | 1         | 1      | 1.3%    |
| ASMedia             | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 75        | 214    | 45.73%  |
| SSD     | 57        | 112    | 34.76%  |
| NVMe    | 26        | 42     | 15.85%  |
| MMC     | 4         | 4      | 2.44%   |
| Unknown | 2         | 7      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 308    | 70%     |
| NVMe | 26        | 42     | 18.57%  |
| SAS  | 12        | 25     | 8.57%   |
| MMC  | 4         | 4      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 138    | 49.03%  |
| 0.51-1.0   | 43        | 103    | 27.74%  |
| 1.01-2.0   | 20        | 40     | 12.9%   |
| 3.01-4.0   | 6         | 8      | 3.87%   |
| 2.01-3.0   | 6         | 30     | 3.87%   |
| 4.01-10.0  | 3         | 6      | 1.94%   |
| 10.01-20.0 | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 28        | 24.14%  |
| 251-500        | 26        | 22.41%  |
| More than 3000 | 19        | 16.38%  |
| 101-250        | 18        | 15.52%  |
| 2001-3000      | 10        | 8.62%   |
| 1001-2000      | 10        | 8.62%   |
| 51-100         | 3         | 2.59%   |
| Unknown        | 2         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 16.67%  |
| 51-100         | 21        | 16.67%  |
| 1-20           | 19        | 15.08%  |
| 501-1000       | 15        | 11.9%   |
| 251-500        | 14        | 11.11%  |
| 1001-2000      | 12        | 9.52%   |
| 21-50          | 10        | 7.94%   |
| More than 3000 | 9         | 7.14%   |
| 2001-3000      | 3         | 2.38%   |
| Unknown        | 2         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 8.7%    |
| WDC WD20PURZ-85GU6Y0 2TB              | 1         | 1      | 4.35%   |
| WDC WD20PURZ-85AKKY0 2TB              | 1         | 1      | 4.35%   |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 1      | 4.35%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 4.35%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 4.35%   |
| WDC WD1001FAES-75W7A0 1TB             | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 4.35%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 4.35%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 4.35%   |
| Seagate ST3320820AS 320GB             | 1         | 1      | 4.35%   |
| Seagate ST3250410AS 250GB             | 1         | 3      | 4.35%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 4.35%   |
| Seagate ST2000VN004-2E4164 2TB        | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 4.35%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 4.35%   |
| Samsung Electronics HD400LD 400GB     | 1         | 1      | 4.35%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 4.35%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.35%   |
| Fujitsu MHZ2160BH G2 160GB            | 1         | 1      | 4.35%   |
| A-DATA Technology SU630 240GB SSD     | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 33.33%  |
| WDC                 | 4         | 6      | 19.05%  |
| Intel               | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |
| A-DATA Technology   | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 43.75%  |
| WDC                 | 4         | 6      | 25%     |
| Toshiba             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 20     | 75%     |
| SSD  | 5         | 5      | 25%     |

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
| Works    | 59        | 182    | 45.04%  |
| Detected | 53        | 172    | 40.46%  |
| Malfunc  | 19        | 25     | 14.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 71        | 50.35%  |
| AMD                          | 30        | 21.28%  |
| Samsung Electronics          | 9         | 6.38%   |
| Marvell Technology Group     | 7         | 4.96%   |
| ASMedia Technology           | 6         | 4.26%   |
| Phison Electronics           | 5         | 3.55%   |
| SanDisk                      | 4         | 2.84%   |
| Kingston Technology Company  | 3         | 2.13%   |
| SK hynix                     | 2         | 1.42%   |
| Toshiba America Info Systems | 1         | 0.71%   |
| JMicron Technology           | 1         | 0.71%   |
| Broadcom                     | 1         | 0.71%   |
| ADATA Technology             | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 8%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 5.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 3.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 3.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 3.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.86%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 2.29%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 2.29%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3         | 1.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 1.71%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.71%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 1.71%   |
| AMD SB600 IDE                                                                           | 3         | 1.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 1.14%   |
| Phison E12 NVMe Controller                                                              | 2         | 1.14%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2         | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.14%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.14%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.14%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.57%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 1         | 0.57%   |
| SK hynix BC511 NVMe SSD                                                                 | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 59.15%  |
| NVMe | 25        | 17.61%  |
| IDE  | 24        | 16.9%   |
| RAID | 8         | 5.63%   |
| SAS  | 1         | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 76        | 69.72%  |
| AMD    | 33        | 30.28%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 3.64%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 2.73%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2         | 1.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 1.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.82%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2         | 1.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2         | 1.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.82%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 1.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.82%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 2         | 1.82%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.82%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.82%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1         | 0.91%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.91%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.91%   |
| Intel Pentium III (Coppermine)              | 1         | 0.91%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1         | 0.91%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.91%   |
| Intel Pentium CPU G3450 @ 3.40GHz           | 1         | 0.91%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.91%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz            | 1         | 0.91%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.91%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.91%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.91%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.91%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.91%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.91%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 0.91%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.91%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.91%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.91%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 22        | 20.18%  |
| Intel Core i5           | 21        | 19.27%  |
| Intel Core i3           | 8         | 7.34%   |
| AMD FX                  | 6         | 5.5%    |
| Intel Core 2 Duo        | 5         | 4.59%   |
| AMD Ryzen 5             | 5         | 4.59%   |
| Other                   | 4         | 3.67%   |
| AMD Ryzen 7             | 4         | 3.67%   |
| AMD Ryzen 3             | 4         | 3.67%   |
| Intel Pentium           | 3         | 2.75%   |
| Intel Xeon              | 2         | 1.83%   |
| Intel Pentium Dual-Core | 2         | 1.83%   |
| Intel Celeron           | 2         | 1.83%   |
| AMD Turion 64 X2 Mobile | 2         | 1.83%   |
| AMD Ryzen Threadripper  | 2         | 1.83%   |
| AMD A8                  | 2         | 1.83%   |
| AMD A10                 | 2         | 1.83%   |
| Intel Pentium Silver    | 1         | 0.92%   |
| Intel Pentium III       | 1         | 0.92%   |
| Intel Pentium Gold      | 1         | 0.92%   |
| Intel Core m5           | 1         | 0.92%   |
| Intel Core 2 Quad       | 1         | 0.92%   |
| Intel Core 2            | 1         | 0.92%   |
| Intel Atom              | 1         | 0.92%   |
| AMD Ryzen 9             | 1         | 0.92%   |
| AMD Phenom II X6        | 1         | 0.92%   |
| AMD Phenom II X4        | 1         | 0.92%   |
| AMD Athlon II X3        | 1         | 0.92%   |
| AMD Athlon 64 X2        | 1         | 0.92%   |
| AMD A6                  | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 45        | 40.91%  |
| 2      | 43        | 39.09%  |
| 6      | 10        | 9.09%   |
| 8      | 7         | 6.36%   |
| 3      | 2         | 1.82%   |
| 32     | 1         | 0.91%   |
| 16     | 1         | 0.91%   |
| 12     | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 99.08%  |
| 2      | 1         | 0.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 70        | 64.22%  |
| 1      | 39        | 35.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 96.4%   |
| Unknown        | 3         | 2.7%    |
| 32-bit         | 1         | 0.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 29.06%  |
| 0x306c3    | 9         | 7.69%   |
| 0x206a7    | 7         | 5.98%   |
| 0x306a9    | 6         | 5.13%   |
| 0x406e3    | 4         | 3.42%   |
| 0x1067a    | 4         | 3.42%   |
| 0x806e9    | 3         | 2.56%   |
| 0x08701021 | 3         | 2.56%   |
| 0x06000852 | 3         | 2.56%   |
| 0x906ea    | 2         | 1.71%   |
| 0x906e9    | 2         | 1.71%   |
| 0x40651    | 2         | 1.71%   |
| 0x08108109 | 2         | 1.71%   |
| 0x0800820d | 2         | 1.71%   |
| 0x010000c8 | 2         | 1.71%   |
| 0xa0671    | 1         | 0.85%   |
| 0xa0653    | 1         | 0.85%   |
| 0xa0652    | 1         | 0.85%   |
| 0x906eb    | 1         | 0.85%   |
| 0x806ec    | 1         | 0.85%   |
| 0x806eb    | 1         | 0.85%   |
| 0x706a1    | 1         | 0.85%   |
| 0x6fb      | 1         | 0.85%   |
| 0x6f6      | 1         | 0.85%   |
| 0x686      | 1         | 0.85%   |
| 0x506e3    | 1         | 0.85%   |
| 0x506c9    | 1         | 0.85%   |
| 0x406c4    | 1         | 0.85%   |
| 0x306f2    | 1         | 0.85%   |
| 0x206d7    | 1         | 0.85%   |
| 0x20655    | 1         | 0.85%   |
| 0x10676    | 1         | 0.85%   |
| 0x0a50000d | 1         | 0.85%   |
| 0x08a00008 | 1         | 0.85%   |
| 0x08701030 | 1         | 0.85%   |
| 0x08701013 | 1         | 0.85%   |
| 0x08600106 | 1         | 0.85%   |
| 0x08108102 | 1         | 0.85%   |
| 0x08101016 | 1         | 0.85%   |
| 0x0810100b | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 16        | 14.55%  |
| KabyLake         | 14        | 12.73%  |
| SandyBridge      | 9         | 8.18%   |
| Skylake          | 8         | 7.27%   |
| IvyBridge        | 8         | 7.27%   |
| Zen 2            | 7         | 6.36%   |
| Piledriver       | 6         | 5.45%   |
| Penryn           | 6         | 5.45%   |
| Zen+             | 5         | 4.55%   |
| Zen              | 3         | 2.73%   |
| K8 Hammer        | 3         | 2.73%   |
| K10              | 3         | 2.73%   |
| Core             | 3         | 2.73%   |
| CometLake        | 3         | 2.73%   |
| Icelake          | 2         | 1.82%   |
| Excavator        | 2         | 1.82%   |
| Unknown          | 2         | 1.82%   |
| Zen 3            | 1         | 0.91%   |
| Westmere         | 1         | 0.91%   |
| Steamroller      | 1         | 0.91%   |
| Silvermont       | 1         | 0.91%   |
| P6               | 1         | 0.91%   |
| K10 Llano        | 1         | 0.91%   |
| Goldmont plus    | 1         | 0.91%   |
| Goldmont         | 1         | 0.91%   |
| Bulldozer        | 1         | 0.91%   |
| Alderlake Hybrid | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 40.91%  |
| Nvidia | 51        | 38.64%  |
| AMD    | 27        | 20.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 4.51%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.76%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4         | 3.01%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4         | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 3.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 3.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 2.26%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 2.26%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 2.26%   |
| Intel HD Graphics 620                                                       | 3         | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 2.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.26%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 3         | 2.26%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.5%    |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 1.5%    |
| Nvidia GK107 [GeForce GT 640]                                               | 2         | 1.5%    |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 1.5%    |
| Intel HD Graphics 630                                                       | 2         | 1.5%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.5%    |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 2         | 1.5%    |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                   | 2         | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 0.75%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                            | 1         | 0.75%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.75%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                       | 1         | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.75%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.75%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 0.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 1         | 0.75%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 0.75%   |
| Nvidia GK106M [GeForce GTX 760M]                                            | 1         | 0.75%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 33        | 30%     |
| 1 x Intel      | 32        | 29.09%  |
| 1 x AMD        | 23        | 20.91%  |
| Intel + Nvidia | 17        | 15.45%  |
| Intel + AMD    | 2         | 1.82%   |
| 2 x Intel      | 1         | 0.91%   |
| 2 x AMD        | 1         | 0.91%   |
| AMD + Nvidia   | 1         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 73.04%  |
| Unknown     | 16        | 13.91%  |
| Proprietary | 15        | 13.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 38.94%  |
| 1.01-2.0   | 25        | 22.12%  |
| 0.51-1.0   | 17        | 15.04%  |
| 0.01-0.5   | 10        | 8.85%   |
| 3.01-4.0   | 6         | 5.31%   |
| 5.01-6.0   | 4         | 3.54%   |
| 7.01-8.0   | 3         | 2.65%   |
| 2.01-3.0   | 3         | 2.65%   |
| 8.01-16.0  | 1         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 12.2%   |
| LG Display              | 8         | 6.5%    |
| BOE                     | 8         | 6.5%    |
| Ancor Communications    | 8         | 6.5%    |
| Dell                    | 7         | 5.69%   |
| Chimei Innolux          | 7         | 5.69%   |
| AU Optronics            | 7         | 5.69%   |
| Acer                    | 7         | 5.69%   |
| Goldstar                | 5         | 4.07%   |
| BenQ                    | 5         | 4.07%   |
| AOC                     | 5         | 4.07%   |
| SNC                     | 4         | 3.25%   |
| ViewSonic               | 3         | 2.44%   |
| Sony                    | 3         | 2.44%   |
| Philips                 | 3         | 2.44%   |
| LG Electronics          | 3         | 2.44%   |
| Hewlett-Packard         | 3         | 2.44%   |
| Sharp                   | 2         | 1.63%   |
| Iiyama                  | 2         | 1.63%   |
| Chi Mei Optoelectronics | 2         | 1.63%   |
| ASUSTek Computer        | 2         | 1.63%   |
| Unknown                 | 1         | 0.81%   |
| SANSUI                  | 1         | 0.81%   |
| RTK                     | 1         | 0.81%   |
| QBell                   | 1         | 0.81%   |
| PKB                     | 1         | 0.81%   |
| Onkyo                   | 1         | 0.81%   |
| Medion                  | 1         | 0.81%   |
| Lenovo                  | 1         | 0.81%   |
| Insignia                | 1         | 0.81%   |
| Idek Iiyama             | 1         | 0.81%   |
| HannStar                | 1         | 0.81%   |
| Eizo                    | 1         | 0.81%   |
| Compal                  | 1         | 0.81%   |
| Apple                   | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 4         | 2.94%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch | 2         | 1.47%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                 | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 2         | 1.47%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 2         | 1.47%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2         | 1.47%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch         | 1         | 0.74%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch         | 1         | 0.74%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                         | 1         | 0.74%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.74%   |
| Sony TV SNYF301 1920x1080                                             | 1         | 0.74%   |
| Sony TV SNYDC02 1920x1080 708x398mm 32.0-inch                         | 1         | 0.74%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                    | 1         | 0.74%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1461 3200x1800 294x165mm 13.3-inch               | 1         | 0.74%   |
| SANSUI ES-22F1 XEC3150 1920x1080 476x268mm 21.5-inch                  | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 600x340mm 27.2-inch  | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch   | 1         | 0.74%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 0.74%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch    | 1         | 0.74%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1         | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.74%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.74%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch     | 1         | 0.74%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3155 1920x1200 367x230mm 17.1-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor S24D330                               | 1         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.74%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.74%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch              | 1         | 0.74%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                  | 1         | 0.74%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch            | 1         | 0.74%   |
| Philips LCD Monitor FTV                                               | 1         | 0.74%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 0.74%   |
| Onkyo LCD Monitor TX-SR608 5760x2160                                  | 1         | 0.74%   |
| Onkyo LCD Monitor TX-SR608                                            | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 45.08%  |
| 1366x768 (WXGA)    | 13        | 10.66%  |
| Unknown            | 8         | 6.56%   |
| 3840x2160 (4K)     | 7         | 5.74%   |
| 1920x1200 (WUXGA)  | 6         | 4.92%   |
| 1600x900 (HD+)     | 6         | 4.92%   |
| 1280x1024 (SXGA)   | 6         | 4.92%   |
| 1680x1050 (WSXGA+) | 3         | 2.46%   |
| 3840x1080          | 2         | 1.64%   |
| 1440x900 (WXGA+)   | 2         | 1.64%   |
| 1280x800 (WXGA)    | 2         | 1.64%   |
| 5760x2160          | 1         | 0.82%   |
| 4480x1440          | 1         | 0.82%   |
| 3520x1080          | 1         | 0.82%   |
| 3200x900           | 1         | 0.82%   |
| 3200x1800 (QHD+)   | 1         | 0.82%   |
| 2736x1824          | 1         | 0.82%   |
| 2560x1440 (QHD)    | 1         | 0.82%   |
| 2560x1080          | 1         | 0.82%   |
| 2560x1024          | 1         | 0.82%   |
| 1920x540           | 1         | 0.82%   |
| 1360x768           | 1         | 0.82%   |
| 1024x768 (XGA)     | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 15.97%  |
| Unknown | 15        | 12.61%  |
| 24      | 12        | 10.08%  |
| 27      | 10        | 8.4%    |
| 21      | 9         | 7.56%   |
| 13      | 9         | 7.56%   |
| 17      | 8         | 6.72%   |
| 19      | 7         | 5.88%   |
| 23      | 5         | 4.2%    |
| 18      | 4         | 3.36%   |
| 14      | 4         | 3.36%   |
| 22      | 3         | 2.52%   |
| 54      | 2         | 1.68%   |
| 46      | 2         | 1.68%   |
| 25      | 2         | 1.68%   |
| 72      | 1         | 0.84%   |
| 48      | 1         | 0.84%   |
| 42      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 29      | 1         | 0.84%   |
| 20      | 1         | 0.84%   |
| 16      | 1         | 0.84%   |
| 12      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 25.42%  |
| 501-600     | 27        | 22.88%  |
| 401-500     | 18        | 15.25%  |
| Unknown     | 15        | 12.71%  |
| 351-400     | 12        | 10.17%  |
| 201-300     | 5         | 4.24%   |
| 1001-1500   | 5         | 4.24%   |
| 601-700     | 3         | 2.54%   |
| 701-800     | 1         | 0.85%   |
| 1501-2000   | 1         | 0.85%   |
| 901-1000    | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 66.37%  |
| Unknown | 15        | 13.27%  |
| 16/10   | 13        | 11.5%   |
| 5/4     | 6         | 5.31%   |
| 4/3     | 1         | 0.88%   |
| 3/2     | 1         | 0.88%   |
| 21/9    | 1         | 0.88%   |
| 1.96    | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 22        | 18.8%   |
| 101-110        | 19        | 16.24%  |
| Unknown        | 15        | 12.82%  |
| 301-350        | 11        | 9.4%    |
| 151-200        | 10        | 8.55%   |
| 81-90          | 9         | 7.69%   |
| 121-130        | 6         | 5.13%   |
| 251-300        | 5         | 4.27%   |
| 141-150        | 5         | 4.27%   |
| 501-1000       | 4         | 3.42%   |
| More than 1000 | 3         | 2.56%   |
| 71-80          | 3         | 2.56%   |
| 61-70          | 1         | 0.85%   |
| 351-500        | 1         | 0.85%   |
| 131-140        | 1         | 0.85%   |
| 111-120        | 1         | 0.85%   |
| 91-100         | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 37.72%  |
| 121-160       | 22        | 19.3%   |
| 101-120       | 22        | 19.3%   |
| Unknown       | 15        | 13.16%  |
| 1-50          | 6         | 5.26%   |
| More than 240 | 3         | 2.63%   |
| 161-240       | 3         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 80%     |
| 2     | 21        | 19.09%  |
| 3     | 1         | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 36.94%  |
| Intel                    | 55        | 35.03%  |
| Qualcomm Atheros         | 14        | 8.92%   |
| Broadcom                 | 10        | 6.37%   |
| Marvell Technology Group | 5         | 3.18%   |
| TP-Link                  | 2         | 1.27%   |
| Sierra Wireless          | 2         | 1.27%   |
| MediaTek                 | 2         | 1.27%   |
| Broadcom Limited         | 2         | 1.27%   |
| Wilocity                 | 1         | 0.64%   |
| Ultimarc                 | 1         | 0.64%   |
| Huawei Technologies      | 1         | 0.64%   |
| Dell                     | 1         | 0.64%   |
| D-Link System            | 1         | 0.64%   |
| ASIX Electronics         | 1         | 0.64%   |
| Aquantia                 | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 24.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.78%   |
| Intel Wireless 8260                                               | 5         | 2.7%    |
| Intel I211 Gigabit Network Connection                             | 5         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.16%   |
| Intel Wireless 3165                                               | 4         | 2.16%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.16%   |
| Intel Ethernet Connection I217-V                                  | 4         | 2.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.62%   |
| Sierra Wireless MC8305 Modem                                      | 2         | 1.08%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 1.08%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.08%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2         | 1.08%   |
| Intel Wireless-AC 9260                                            | 2         | 1.08%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.08%   |
| Intel Wireless 7265                                               | 2         | 1.08%   |
| Intel Wireless 7260                                               | 2         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.08%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.08%   |
| Broadcom BCM4311 802.11a/b/g                                      | 2         | 1.08%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.54%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1         | 0.54%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.54%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.54%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 46.58%  |
| Realtek Semiconductor    | 12        | 16.44%  |
| Qualcomm Atheros         | 11        | 15.07%  |
| Broadcom                 | 7         | 9.59%   |
| TP-Link                  | 2         | 2.74%   |
| Sierra Wireless          | 2         | 2.74%   |
| MediaTek                 | 2         | 2.74%   |
| Wilocity                 | 1         | 1.37%   |
| Marvell Technology Group | 1         | 1.37%   |
| Dell                     | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 6.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 5.19%   |
| Intel Wireless 3165                                            | 4         | 5.19%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 5.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 5.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 5.19%   |
| Sierra Wireless MC8305 Modem                                   | 2         | 2.6%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 2.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 2.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 2.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2         | 2.6%    |
| Intel Wireless-AC 9260                                         | 2         | 2.6%    |
| Intel Wireless 8265 / 8275                                     | 2         | 2.6%    |
| Intel Wireless 7265                                            | 2         | 2.6%    |
| Intel Wireless 7260                                            | 2         | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.6%    |
| Broadcom BCM4311 802.11a/b/g                                   | 2         | 2.6%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 1.3%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.3%    |
| TP-Link 802.11ac NIC                                           | 1         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1.3%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.3%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.3%    |
| MediaTek WiFi                                                  | 1         | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.3%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.3%    |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 51.46%  |
| Intel                    | 33        | 32.04%  |
| Qualcomm Atheros         | 5         | 4.85%   |
| Marvell Technology Group | 4         | 3.88%   |
| Broadcom                 | 3         | 2.91%   |
| Broadcom Limited         | 2         | 1.94%   |
| D-Link System            | 1         | 0.97%   |
| ASIX Electronics         | 1         | 0.97%   |
| Aquantia                 | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 45        | 42.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 6.6%    |
| Intel I211 Gigabit Network Connection                                         | 5         | 4.72%   |
| Intel Ethernet Connection I217-V                                              | 4         | 3.77%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 1.89%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 1.89%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 1.89%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 2         | 1.89%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 2         | 1.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                                         | 1         | 0.94%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.94%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.94%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.94%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.94%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1         | 0.94%   |
| Intel I210 Gigabit Network Connection                                         | 1         | 0.94%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.94%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.94%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.94%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.94%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.94%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.94%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.94%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 0.94%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1         | 0.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 0.94%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                | 1         | 0.94%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 0.94%   |
| ASIX AX88772B                                                                 | 1         | 0.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 59.15%  |
| WiFi     | 65        | 39.63%  |
| Modem    | 1         | 0.61%   |
| Unknown  | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 56.14%  |
| WiFi     | 50        | 43.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 55        | 48.67%  |
| 2     | 50        | 44.25%  |
| 3     | 5         | 4.42%   |
| 0     | 2         | 1.77%   |
| 4     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 78.57%  |
| Yes  | 24        | 21.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 26        | 40.63%  |
| Cambridge Silicon Radio | 9         | 14.06%  |
| Realtek Semiconductor   | 6         | 9.38%   |
| IMC Networks            | 4         | 6.25%   |
| Broadcom                | 4         | 6.25%   |
| Hewlett-Packard         | 3         | 4.69%   |
| Lite-On Technology      | 2         | 3.13%   |
| Foxconn / Hon Hai       | 2         | 3.13%   |
| Belkin Components       | 2         | 3.13%   |
| ASUSTek Computer        | 2         | 3.13%   |
| Taiyo Yuden             | 1         | 1.56%   |
| Marvell Semiconductor   | 1         | 1.56%   |
| Dell                    | 1         | 1.56%   |
| Apple                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 18.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 14.06%  |
| Realtek Bluetooth Radio                             | 5         | 7.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 6.25%   |
| Intel AX200 Bluetooth                               | 4         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.69%   |
| Lite-On Bluetooth Device                            | 2         | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 3.13%   |
| IMC Networks Bluetooth Device                       | 2         | 3.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.13%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 3.13%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.56%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.56%   |
| Intel Bluetooth Device                              | 1         | 1.56%   |
| IMC Networks Wireless_Device                        | 1         | 1.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.56%   |
| Broadcom Bluetooth dongle                           | 1         | 1.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.56%   |
| Broadcom BCM20702A0                                 | 1         | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.56%   |
| Belkin Components F8T013 Bluetooth Adapter          | 1         | 1.56%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 1.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.56%   |
| ASUS Bluetooth Device                               | 1         | 1.56%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 74        | 44.31%  |
| Nvidia                     | 40        | 23.95%  |
| AMD                        | 36        | 21.56%  |
| C-Media Electronics        | 9         | 5.39%   |
| Samsung Electronics        | 1         | 0.6%    |
| Mackie Designs             | 1         | 0.6%    |
| Logitech                   | 1         | 0.6%    |
| iCreate Technologies       | 1         | 0.6%    |
| Corsair                    | 1         | 0.6%    |
| BEHRINGER International    | 1         | 0.6%    |
| ASUSTek Computer           | 1         | 0.6%    |
| Altec Lansing Technologies | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 5.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 4.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 4.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 3.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 3.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 3.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 2.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.11%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.58%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3         | 1.58%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 3         | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.58%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.58%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.05%   |
| Nvidia Audio device                                                        | 2         | 1.05%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 1.05%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.05%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.05%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.05%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.05%   |
| Samsung Electronics USB C Earphones                                        | 1         | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.53%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 18        | 22.78%  |
| Samsung Electronics | 15        | 18.99%  |
| Unknown             | 12        | 15.19%  |
| SK hynix            | 8         | 10.13%  |
| G.Skill             | 6         | 7.59%   |
| Corsair             | 5         | 6.33%   |
| Micron Technology   | 4         | 5.06%   |
| Unknown (ABCD)      | 2         | 2.53%   |
| Team                | 2         | 2.53%   |
| Crucial             | 2         | 2.53%   |
| Smart               | 1         | 1.27%   |
| Ramaxel Technology  | 1         | 1.27%   |
| Nanya Technology    | 1         | 1.27%   |
| GOODRAM             | 1         | 1.27%   |
| A-DATA Technology   | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 3         | 3.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 2.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s          | 2         | 2.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 1.18%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM 533MT/s                            | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 1.18%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 1.18%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 1.18%   |
| Team RAM Elite-16 8GB DIMM DDR3 1600MT/s                         | 1         | 1.18%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 1         | 1.18%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.18%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s         | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 40.58%  |
| DDR4    | 26        | 37.68%  |
| DDR2    | 4         | 5.8%    |
| Unknown | 4         | 5.8%    |
| SDRAM   | 2         | 2.9%    |
| LPDDR4  | 2         | 2.9%    |
| LPDDR3  | 2         | 2.9%    |
| LPDDR5  | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 37        | 55.22%  |
| SODIMM       | 28        | 41.79%  |
| Row Of Chips | 2         | 2.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 43.84%  |
| 4096  | 24        | 32.88%  |
| 2048  | 9         | 12.33%  |
| 16384 | 8         | 10.96%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 22        | 29.33%  |
| 2400  | 7         | 9.33%   |
| 1333  | 6         | 8%      |
| 3200  | 5         | 6.67%   |
| 2133  | 5         | 6.67%   |
| 2667  | 4         | 5.33%   |
| 3334  | 3         | 4%      |
| 800   | 3         | 4%      |
| 3733  | 2         | 2.67%   |
| 3600  | 2         | 2.67%   |
| 1867  | 2         | 2.67%   |
| 1334  | 2         | 2.67%   |
| 667   | 2         | 2.67%   |
| 6400  | 1         | 1.33%   |
| 4199  | 1         | 1.33%   |
| 3500  | 1         | 1.33%   |
| 3466  | 1         | 1.33%   |
| 3400  | 1         | 1.33%   |
| 3266  | 1         | 1.33%   |
| 3000  | 1         | 1.33%   |
| 1066  | 1         | 1.33%   |
| 975   | 1         | 1.33%   |
| 533   | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 28.57%  |
| Xerox               | 1         | 14.29%  |
| Seiko Epson         | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155    | 1         | 14.29%  |
| Seiko Epson WF-2530 Series    | 1         | 14.29%  |
| Samsung CLP-300 Series        | 1         | 14.29%  |
| HP OfficeJet 6950             | 1         | 14.29%  |
| Canon PIXMA MG3600 Series     | 1         | 14.29%  |
| Brother QL-570 Label Printer  | 1         | 14.29%  |
| Brother HL-2030 Laser Printer | 1         | 14.29%  |

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
| Chicony Electronics                    | 13        | 25%     |
| Microdia                               | 5         | 9.62%   |
| Logitech                               | 5         | 9.62%   |
| Realtek Semiconductor                  | 4         | 7.69%   |
| IMC Networks                           | 3         | 5.77%   |
| Sunplus Innovation Technology          | 2         | 3.85%   |
| Microsoft                              | 2         | 3.85%   |
| Luxvisions Innotech Limited            | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| Apple                                  | 2         | 3.85%   |
| Alcor Micro                            | 2         | 3.85%   |
| WaveRider Communications               | 1         | 1.92%   |
| Suyin                                  | 1         | 1.92%   |
| Sunplus IT                             | 1         | 1.92%   |
| Sonix Technology                       | 1         | 1.92%   |
| Primax Electronics                     | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Leap Motion                            | 1         | 1.92%   |
| Huawei Technologies                    | 1         | 1.92%   |
| Bison Electronics                      | 1         | 1.92%   |
| Acer                                   | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 5.66%   |
| Chicony USB2.0 Camera                                                      | 3         | 5.66%   |
| Chicony Integrated Camera                                                  | 3         | 5.66%   |
| Microdia Camera                                                            | 2         | 3.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 3.77%   |
| Chicony FJ Camera                                                          | 2         | 3.77%   |
| WaveRider USB 2.0 Camera                                                   | 1         | 1.89%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 1.89%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                                         | 1         | 1.89%   |
| Sunplus WEBCAM ESSENTIELB W1                                               | 1         | 1.89%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 1.89%   |
| Sonix USB2.0 FHD UVC WebCam                                                | 1         | 1.89%   |
| Realtek USB Camera                                                         | 1         | 1.89%   |
| Primax HP Truevision FHD                                                   | 1         | 1.89%   |
| Microsoft LifeCam VX-800                                                   | 1         | 1.89%   |
| Microsoft LifeCam HD-3000                                                  | 1         | 1.89%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.89%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.89%   |
| Microdia Integrated Webcam                                                 | 1         | 1.89%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.89%   |
| Logitech Webcam C210                                                       | 1         | 1.89%   |
| Logitech Webcam C200                                                       | 1         | 1.89%   |
| Logitech Webcam C110                                                       | 1         | 1.89%   |
| Logitech QuickCam Pro 9000                                                 | 1         | 1.89%   |
| Logitech Fujitsu Webcam                                                    | 1         | 1.89%   |
| Lite-On HP Webcam                                                          | 1         | 1.89%   |
| Leap Motion Controller                                                     | 1         | 1.89%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 1.89%   |
| Huawei HiCamera                                                            | 1         | 1.89%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 1.89%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.89%   |
| Chicony Integrated IR Camera                                               | 1         | 1.89%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 1.89%   |
| Chicony HD WebCam                                                          | 1         | 1.89%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 1.89%   |
| Bison EasyCamera                                                           | 1         | 1.89%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 4         | 33.33%  |
| AuthenTec                          | 4         | 33.33%  |
| Shenzhen Goodix Technology         | 2         | 16.67%  |
| Synaptics                          | 1         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                            | 1         | 8.33%   |
| Synaptics  WBDI                                                 | 1         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                             | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 8.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 8.33%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 50%     |
| O2 Micro | 2         | 33.33%  |
| Avtor    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 78        | 68.42%  |
| 1     | 26        | 22.81%  |
| 2     | 7         | 6.14%   |
| 3     | 3         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 14        | 31.82%  |
| Fingerprint reader       | 12        | 27.27%  |
| Chipcard                 | 6         | 13.64%  |
| Net/wireless             | 4         | 9.09%   |
| Multimedia controller    | 3         | 6.82%   |
| Unassigned class         | 1         | 2.27%   |
| Storage                  | 1         | 2.27%   |
| Sound                    | 1         | 2.27%   |
| Communication controller | 1         | 2.27%   |
| Camera                   | 1         | 2.27%   |

