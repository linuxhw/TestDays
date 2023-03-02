Ubuntu MATE 22.04 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 335

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | Desktop     | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e1a9b1b0fa](https://linux-hardware.org/?probe=e1a9b1b0fa) | Feb 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | Notebook    | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | Notebook    | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [eb2e4b24cc](https://linux-hardware.org/?probe=eb2e4b24cc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [9536b9eedc](https://linux-hardware.org/?probe=9536b9eedc) | Jan 22, 2023 |
| Google        | Relm                        | Notebook    | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [571389ffa0](https://linux-hardware.org/?probe=571389ffa0) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [e652633643](https://linux-hardware.org/?probe=e652633643) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [c2b8de2fdf](https://linux-hardware.org/?probe=c2b8de2fdf) | Jan 17, 2023 |
| Dell          | Latitude 5410               | Notebook    | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | Notebook    | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | Notebook    | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [433ba8749a](https://linux-hardware.org/?probe=433ba8749a) | Jan 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | Notebook    | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | Notebook    | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [531e60d101](https://linux-hardware.org/?probe=531e60d101) | Dec 30, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.15.0-56-generic                      | 26        | 12.62%  |
| 5.15.0-47-generic                      | 18        | 8.74%   |
| 5.15.0-48-generic                      | 13        | 6.31%   |
| 5.15.0-58-generic                      | 12        | 5.83%   |
| 5.15.0-52-generic                      | 11        | 5.34%   |
| 5.15.0-46-generic                      | 11        | 5.34%   |
| 5.15.0-60-generic                      | 10        | 4.85%   |
| 5.15.0-40-generic                      | 9         | 4.37%   |
| 5.15.0-43-generic                      | 8         | 3.88%   |
| 5.15.0-25-generic                      | 8         | 3.88%   |
| 5.15.0-53-generic                      | 7         | 3.4%    |
| 5.15.0-27-generic                      | 7         | 3.4%    |
| 5.15.0-50-generic                      | 6         | 2.91%   |
| 5.15.0-41-generic                      | 6         | 2.91%   |
| 5.15.0-57-generic                      | 5         | 2.43%   |
| 5.19.0-32-generic                      | 4         | 1.94%   |
| 5.15.0-30-generic                      | 4         | 1.94%   |
| 5.15.0-37-generic                      | 3         | 1.46%   |
| 5.15.0-58-lowlatency                   | 2         | 0.97%   |
| 5.15.0-56-lowlatency                   | 2         | 0.97%   |
| 5.15.0-52-lowlatency                   | 2         | 0.97%   |
| 5.15.0-39-generic                      | 2         | 0.97%   |
| 5.15.0-35-generic                      | 2         | 0.97%   |
| 5.14.0-1054-oem                        | 2         | 0.97%   |
| 6.1.8-x64v1-xanmod1                    | 1         | 0.49%   |
| 6.0.8-x64v1-xanmod1                    | 1         | 0.49%   |
| 5.18.0-odroid-arm64                    | 1         | 0.49%   |
| 5.18.0-1-generic                       | 1         | 0.49%   |
| 5.18.0-051800-generic                  | 1         | 0.49%   |
| 5.17.1-051701-generic                  | 1         | 0.49%   |
| 5.17.0-rc4-next-20220217-g21d89a4d51a7 | 1         | 0.49%   |
| 5.17.0-1003-oem                        | 1         | 0.49%   |
| 5.15.0-66-generic                      | 1         | 0.49%   |
| 5.15.0-59-generic                      | 1         | 0.49%   |
| 5.15.0-46-lowlatency                   | 1         | 0.49%   |
| 5.15.0-33-generic                      | 1         | 0.49%   |
| 5.15.0-23-generic                      | 1         | 0.49%   |
| 5.15.0-22-generic                      | 1         | 0.49%   |
| 5.15.0-18-generic                      | 1         | 0.49%   |
| 5.15.0-11-generic                      | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 169       | 90.86%  |
| 5.19.0  | 4         | 2.15%   |
| 5.18.0  | 3         | 1.61%   |
| 5.17.0  | 2         | 1.08%   |
| 5.14.0  | 2         | 1.08%   |
| 5.13.0  | 2         | 1.08%   |
| 6.1.8   | 1         | 0.54%   |
| 6.0.8   | 1         | 0.54%   |
| 5.17.1  | 1         | 0.54%   |
| 4.9.337 | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 169       | 90.86%  |
| 5.19    | 4         | 2.15%   |
| 5.18    | 3         | 1.61%   |
| 5.17    | 3         | 1.61%   |
| 5.14    | 2         | 1.08%   |
| 5.13    | 2         | 1.08%   |
| 6.1     | 1         | 0.54%   |
| 6.0     | 1         | 0.54%   |
| 4.9     | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 178       | 97.27%  |
| aarch64 | 4         | 2.19%   |
| armv7l  | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| MATE   | 179       | 97.81%  |
| KDE5   | 2         | 1.09%   |
| GNOME  | 1         | 0.55%   |
| Budgie | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 175       | 95.63%  |
| Wayland | 4         | 2.19%   |
| Tty     | 4         | 2.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 152       | 81.72%  |
| GDM3    | 18        | 9.68%   |
| Unknown | 15        | 8.06%   |
| SDDM    | 1         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 69        | 37.3%   |
| de_DE | 22        | 11.89%  |
| fr_FR | 21        | 11.35%  |
| it_IT | 14        | 7.57%   |
| ru_RU | 7         | 3.78%   |
| en_CA | 7         | 3.78%   |
| pt_BR | 5         | 2.7%    |
| en_GB | 5         | 2.7%    |
| en_AU | 5         | 2.7%    |
| C     | 5         | 2.7%    |
| fi_FI | 3         | 1.62%   |
| es_ES | 3         | 1.62%   |
| de_CH | 3         | 1.62%   |
| pl_PL | 2         | 1.08%   |
| hu_HU | 2         | 1.08%   |
| hr_HR | 2         | 1.08%   |
| zh_CN | 1         | 0.54%   |
| pt_PT | 1         | 0.54%   |
| nl_NL | 1         | 0.54%   |
| es_PE | 1         | 0.54%   |
| es_MX | 1         | 0.54%   |
| es_AR | 1         | 0.54%   |
| en_IL | 1         | 0.54%   |
| el_GR | 1         | 0.54%   |
| de_AT | 1         | 0.54%   |
| da_DK | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 97        | 51.05%  |
| EFI  | 93        | 48.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 167       | 90.76%  |
| Overlay | 5         | 2.72%   |
| Btrfs   | 5         | 2.72%   |
| Zfs     | 4         | 2.17%   |
| Xfs     | 2         | 1.09%   |
| Jfs     | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 131       | 69.68%  |
| Unknown | 37        | 19.68%  |
| MBR     | 20        | 10.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 81.97%  |
| Yes       | 33        | 18.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 62.37%  |
| Yes       | 70        | 37.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 34        | 18.58%  |
| Hewlett-Packard         | 33        | 18.03%  |
| Lenovo                  | 23        | 12.57%  |
| Dell                    | 20        | 10.93%  |
| MSI                     | 10        | 5.46%   |
| Gigabyte Technology     | 8         | 4.37%   |
| Acer                    | 8         | 4.37%   |
| Apple                   | 6         | 3.28%   |
| Intel                   | 5         | 2.73%   |
| ASRock                  | 5         | 2.73%   |
| Sony                    | 4         | 2.19%   |
| Toshiba                 | 2         | 1.09%   |
| Raspberry Pi Foundation | 2         | 1.09%   |
| HUAWEI                  | 2         | 1.09%   |
| Hardkernel              | 2         | 1.09%   |
| Google                  | 2         | 1.09%   |
| Unknown                 | 2         | 1.09%   |
| TYAN Computer           | 1         | 0.55%   |
| TrekStor                | 1         | 0.55%   |
| SLIMBOOK                | 1         | 0.55%   |
| Notebook                | 1         | 0.55%   |
| Microsoft               | 1         | 0.55%   |
| MicroByte               | 1         | 0.55%   |
| Medion                  | 1         | 0.55%   |
| LincPlus                | 1         | 0.55%   |
| LG Electronics          | 1         | 0.55%   |
| IPASON                  | 1         | 0.55%   |
| HYPERPC                 | 1         | 0.55%   |
| HONOR                   | 1         | 0.55%   |
| Compaq                  | 1         | 0.55%   |
| Chuwi                   | 1         | 0.55%   |
| AZW                     | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Compaq Elite 8300 SFF             | 2         | 1.09%   |
| Hardkernel ODROID-N2Plus             | 2         | 1.09%   |
| Unknown                              | 2         | 1.09%   |
| TYAN S7012                           | 1         | 0.55%   |
| TrekStor Surfbook A13B               | 1         | 0.55%   |
| Toshiba Satellite P50-B-10Z          | 1         | 0.55%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.55%   |
| Sony VPCEH1E1E                       | 1         | 0.55%   |
| Sony VPCEB2Z1E                       | 1         | 0.55%   |
| Sony VPCEA36FG                       | 1         | 0.55%   |
| Sony VGN-Z21WRN_B                    | 1         | 0.55%   |
| SLIMBOOK TITAN                       | 1         | 0.55%   |
| RPi Raspberry Pi 400 Rev 1.1         | 1         | 0.55%   |
| RPi Raspberry Pi                     | 1         | 0.55%   |
| Notebook NJx0MU                      | 1         | 0.55%   |
| MSI p6-2330                          | 1         | 0.55%   |
| MSI MS-7C56                          | 1         | 0.55%   |
| MSI MS-7C52                          | 1         | 0.55%   |
| MSI MS-7C09                          | 1         | 0.55%   |
| MSI MS-7C02                          | 1         | 0.55%   |
| MSI MS-7982                          | 1         | 0.55%   |
| MSI MS-7817                          | 1         | 0.55%   |
| MSI MS-7758                          | 1         | 0.55%   |
| MSI MS-7599                          | 1         | 0.55%   |
| MSI B02311                           | 1         | 0.55%   |
| Microsoft Surface 2                  | 1         | 0.55%   |
| MicroByte ezbook                     | 1         | 0.55%   |
| Medion MS-7797                       | 1         | 0.55%   |
| LincPlus LINNCPLUS P1                | 1         | 0.55%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.55%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.55%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.55%   |
| Lenovo ThinkPad T430 2347G5U         | 1         | 0.55%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.55%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00 | 1         | 0.55%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.55%   |
| Lenovo ThinkPad SL 2746AHG           | 1         | 0.55%   |
| Lenovo ThinkPad R61 8918DEG          | 1         | 0.55%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 9         | 4.92%   |
| Dell Latitude            | 6         | 3.28%   |
| Lenovo IdeaPad           | 5         | 2.73%   |
| HP Pavilion              | 5         | 2.73%   |
| Dell Precision           | 5         | 2.73%   |
| Dell Inspiron            | 5         | 2.73%   |
| ASUS PRIME               | 5         | 2.73%   |
| Acer Aspire              | 5         | 2.73%   |
| HP Compaq                | 4         | 2.19%   |
| ASUS ROG                 | 4         | 2.19%   |
| HP EliteDesk             | 3         | 1.64%   |
| HP EliteBook             | 3         | 1.64%   |
| ASUS VivoBook            | 3         | 1.64%   |
| Toshiba Satellite        | 2         | 1.09%   |
| RPi Raspberry            | 2         | 1.09%   |
| Lenovo ThinkCentre       | 2         | 1.09%   |
| Lenovo ThinkBook         | 2         | 1.09%   |
| HP ZBook                 | 2         | 1.09%   |
| HP ProLiant              | 2         | 1.09%   |
| HP ProBook               | 2         | 1.09%   |
| HP Laptop                | 2         | 1.09%   |
| HP ENVY                  | 2         | 1.09%   |
| HP 15                    | 2         | 1.09%   |
| Hardkernel ODROID-N2Plus | 2         | 1.09%   |
| Dell XPS                 | 2         | 1.09%   |
| Dell OptiPlex            | 2         | 1.09%   |
| ASUS TUF                 | 2         | 1.09%   |
| ASUS ASUS                | 2         | 1.09%   |
| Acer TravelMate          | 2         | 1.09%   |
| Unknown                  | 2         | 1.09%   |
| TYAN S7012               | 1         | 0.55%   |
| TrekStor Surfbook        | 1         | 0.55%   |
| Sony VPCEH1E1E           | 1         | 0.55%   |
| Sony VPCEB2Z1E           | 1         | 0.55%   |
| Sony VPCEA36FG           | 1         | 0.55%   |
| Sony VGN-Z21WRN          | 1         | 0.55%   |
| SLIMBOOK TITAN           | 1         | 0.55%   |
| Notebook NJx0MU          | 1         | 0.55%   |
| MSI p6-2330              | 1         | 0.55%   |
| MSI MS-7C56              | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 28        | 15.3%   |
| 2018    | 18        | 9.84%   |
| 2020    | 17        | 9.29%   |
| 2012    | 16        | 8.74%   |
| 2019    | 12        | 6.56%   |
| 2013    | 12        | 6.56%   |
| 2014    | 11        | 6.01%   |
| 2022    | 10        | 5.46%   |
| 2011    | 10        | 5.46%   |
| 2010    | 10        | 5.46%   |
| 2016    | 7         | 3.83%   |
| 2009    | 7         | 3.83%   |
| 2017    | 6         | 3.28%   |
| 2015    | 5         | 2.73%   |
| 2008    | 5         | 2.73%   |
| Unknown | 4         | 2.19%   |
| 2007    | 3         | 1.64%   |
| 2006    | 2         | 1.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 96        | 52.46%  |
| Desktop        | 68        | 37.16%  |
| System on chip | 4         | 2.19%   |
| Mini pc        | 4         | 2.19%   |
| All in one     | 4         | 2.19%   |
| Tablet         | 3         | 1.64%   |
| Convertible    | 3         | 1.64%   |
| Server         | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 174       | 93.55%  |
| Enabled  | 12        | 6.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 181       | 98.91%  |
| Yes  | 2         | 1.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 22.4%   |
| 3.01-4.0    | 38        | 20.77%  |
| 8.01-16.0   | 34        | 18.58%  |
| 16.01-24.0  | 30        | 16.39%  |
| 32.01-64.0  | 24        | 13.11%  |
| 64.01-256.0 | 7         | 3.83%   |
| 24.01-32.0  | 4         | 2.19%   |
| 1.01-2.0    | 3         | 1.64%   |
| 2.01-3.0    | 2         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 30.26%  |
| 2.01-3.0   | 55        | 28.21%  |
| 4.01-8.0   | 35        | 17.95%  |
| 3.01-4.0   | 24        | 12.31%  |
| 8.01-16.0  | 10        | 5.13%   |
| 0.51-1.0   | 10        | 5.13%   |
| 24.01-32.0 | 2         | 1.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 111       | 60.66%  |
| 2      | 33        | 18.03%  |
| 3      | 20        | 10.93%  |
| 4      | 11        | 6.01%   |
| 6      | 4         | 2.19%   |
| 5      | 2         | 1.09%   |
| 20     | 1         | 0.55%   |
| 7      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 53.55%  |
| Yes       | 85        | 46.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 81.42%  |
| No        | 34        | 18.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 80.33%  |
| No        | 36        | 19.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 64.67%  |
| No        | 65        | 35.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 31        | 16.94%  |
| Germany     | 24        | 13.11%  |
| France      | 20        | 10.93%  |
| Italy       | 17        | 9.29%   |
| Spain       | 7         | 3.83%   |
| Brazil      | 7         | 3.83%   |
| Russia      | 6         | 3.28%   |
| Canada      | 6         | 3.28%   |
| UK          | 5         | 2.73%   |
| Turkey      | 4         | 2.19%   |
| Hungary     | 4         | 2.19%   |
| Finland     | 4         | 2.19%   |
| Australia   | 4         | 2.19%   |
| Switzerland | 3         | 1.64%   |
| Portugal    | 3         | 1.64%   |
| Greece      | 3         | 1.64%   |
| Croatia     | 3         | 1.64%   |
| Belgium     | 3         | 1.64%   |
| Ukraine     | 2         | 1.09%   |
| Serbia      | 2         | 1.09%   |
| Poland      | 2         | 1.09%   |
| Estonia     | 2         | 1.09%   |
| Austria     | 2         | 1.09%   |
| Thailand    | 1         | 0.55%   |
| Slovenia    | 1         | 0.55%   |
| Romania     | 1         | 0.55%   |
| Peru        | 1         | 0.55%   |
| Paraguay    | 1         | 0.55%   |
| New Zealand | 1         | 0.55%   |
| Netherlands | 1         | 0.55%   |
| Mexico      | 1         | 0.55%   |
| Libya       | 1         | 0.55%   |
| Israel      | 1         | 0.55%   |
| Isle of Man | 1         | 0.55%   |
| India       | 1         | 0.55%   |
| Georgia     | 1         | 0.55%   |
| Denmark     | 1         | 0.55%   |
| Colombia    | 1         | 0.55%   |
| China       | 1         | 0.55%   |
| Chile       | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 3         | 1.59%   |
| Mannheim         | 3         | 1.59%   |
| Berlin           | 3         | 1.59%   |
| Zagreb           | 2         | 1.06%   |
| West Stockbridge | 2         | 1.06%   |
| Warsaw           | 2         | 1.06%   |
| Vancouver        | 2         | 1.06%   |
| Turku            | 2         | 1.06%   |
| Sao Paulo        | 2         | 1.06%   |
| Rome             | 2         | 1.06%   |
| Olathe           | 2         | 1.06%   |
| Moscow           | 2         | 1.06%   |
| Melbourne        | 2         | 1.06%   |
| Madrid           | 2         | 1.06%   |
| Lansdale         | 2         | 1.06%   |
| Cologne          | 2         | 1.06%   |
| Belgrade         | 2         | 1.06%   |
| Zottegem         | 1         | 0.53%   |
| York             | 1         | 0.53%   |
| Xining           | 1         | 0.53%   |
| Whanganui        | 1         | 0.53%   |
| Washington       | 1         | 0.53%   |
| Viroflay         | 1         | 0.53%   |
| Villeurbanne     | 1         | 0.53%   |
| Victoria         | 1         | 0.53%   |
| Viana do Castelo | 1         | 0.53%   |
| Velyki Mosty     | 1         | 0.53%   |
| Vaudoy-en-Brie   | 1         | 0.53%   |
| Varna            | 1         | 0.53%   |
| Valenciennes     | 1         | 0.53%   |
| Tula             | 1         | 0.53%   |
| Tripoli          | 1         | 0.53%   |
| Trenton          | 1         | 0.53%   |
| Toulouse         | 1         | 0.53%   |
| Toulon           | 1         | 0.53%   |
| Torring          | 1         | 0.53%   |
| Thane            | 1         | 0.53%   |
| Terrace          | 1         | 0.53%   |
| Tel Aviv         | 1         | 0.53%   |
| Tartu            | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 47        | 78     | 17.28%  |
| WDC                   | 34        | 52     | 12.5%   |
| Seagate               | 33        | 55     | 12.13%  |
| SanDisk               | 16        | 21     | 5.88%   |
| Crucial               | 16        | 20     | 5.88%   |
| Unknown               | 14        | 20     | 5.15%   |
| Toshiba               | 14        | 25     | 5.15%   |
| Kingston              | 12        | 17     | 4.41%   |
| SK hynix              | 7         | 7      | 2.57%   |
| A-DATA Technology     | 6         | 6      | 2.21%   |
| Phison                | 5         | 5      | 1.84%   |
| Hitachi               | 5         | 5      | 1.84%   |
| SPCC                  | 4         | 6      | 1.47%   |
| KIOXIA                | 3         | 3      | 1.1%    |
| KingSpec              | 3         | 3      | 1.1%    |
| Intel                 | 3         | 3      | 1.1%    |
| HGST                  | 3         | 3      | 1.1%    |
| China                 | 3         | 3      | 1.1%    |
| Unknown               | 3         | 3      | 1.1%    |
| Phison Electronics    | 2         | 2      | 0.74%   |
| Netac                 | 2         | 2      | 0.74%   |
| Micron Technology     | 2         | 2      | 0.74%   |
| Hewlett-Packard       | 2         | 3      | 0.74%   |
| Corsair               | 2         | 2      | 0.74%   |
| WDC WDS2              | 1         | 1      | 0.37%   |
| Verbatim              | 1         | 3      | 0.37%   |
| UMIS                  | 1         | 2      | 0.37%   |
| SSSTC                 | 1         | 1      | 0.37%   |
| RZX                   | 1         | 1      | 0.37%   |
| Realtek Semiconductor | 1         | 2      | 0.37%   |
| PNY                   | 1         | 1      | 0.37%   |
| Patriot               | 1         | 1      | 0.37%   |
| OCZ                   | 1         | 1      | 0.37%   |
| NGFF                  | 1         | 1      | 0.37%   |
| Maxtor                | 1         | 1      | 0.37%   |
| LITEONIT              | 1         | 1      | 0.37%   |
| LITEON                | 1         | 1      | 0.37%   |
| Lenovo                | 1         | 1      | 0.37%   |
| Kston                 | 1         | 1      | 0.37%   |
| KIOXIA-EXCERIA        | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 1.28%   |
| Crucial CT1000BX500SSD1 1TB                         | 4         | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.96%   |
| Unknown MMC Card  32GB                              | 3         | 0.96%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                     | 3         | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3         | 0.96%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 0.96%   |
| Samsung SSD 870 QVO 1TB                             | 3         | 0.96%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.96%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.96%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 0.96%   |
| Crucial CT2000MX500SSD1 2TB                         | 3         | 0.96%   |
| Unknown                                             | 3         | 0.96%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2         | 0.64%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2         | 0.64%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.64%   |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2         | 0.64%   |
| SanDisk SSD PLUS 480GB                              | 2         | 0.64%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.64%   |
| Samsung SSD 980 1TB                                 | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2         | 0.64%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.64%   |
| Samsung SSD 870 EVO 500GB                           | 2         | 0.64%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.64%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.64%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.64%   |
| Crucial CT480BX500SSD1 480GB                        | 2         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.32%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                     | 1         | 0.32%   |
| WDC WDS100T2B0C 1TB                                 | 1         | 0.32%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.32%   |
| WDC WD800JD-22JNC0 69GB                             | 1         | 0.32%   |
| WDC WD8001FZBX-00ASYA0 8TB                          | 1         | 0.32%   |
| WDC WD6400AAKS-00E4A0 640GB                         | 1         | 0.32%   |
| WDC WD60 EFAX-68JH4N1 6TB                           | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 55     | 35.87%  |
| WDC                 | 31        | 47     | 33.7%   |
| Toshiba             | 11        | 21     | 11.96%  |
| Hitachi             | 5         | 5      | 5.43%   |
| Samsung Electronics | 3         | 6      | 3.26%   |
| HGST                | 3         | 3      | 3.26%   |
| Maxtor              | 1         | 1      | 1.09%   |
| KESU                | 1         | 1      | 1.09%   |
| JMicron Technology  | 1         | 1      | 1.09%   |
| Hewlett-Packard     | 1         | 2      | 1.09%   |
| DAS                 | 1         | 6      | 1.09%   |
| ASMedia             | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 31     | 24%     |
| Crucial             | 16        | 20     | 16%     |
| SanDisk             | 11        | 14     | 11%     |
| Kingston            | 9         | 13     | 9%      |
| A-DATA Technology   | 5         | 5      | 5%      |
| SPCC                | 3         | 5      | 3%      |
| KingSpec            | 3         | 3      | 3%      |
| China               | 3         | 3      | 3%      |
| WDC                 | 2         | 2      | 2%      |
| WDC WDS2            | 1         | 1      | 1%      |
| Verbatim            | 1         | 3      | 1%      |
| Unknown             | 1         | 1      | 1%      |
| Toshiba             | 1         | 2      | 1%      |
| SK hynix            | 1         | 1      | 1%      |
| RZX                 | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| Patriot             | 1         | 1      | 1%      |
| OCZ                 | 1         | 1      | 1%      |
| NGFF                | 1         | 1      | 1%      |
| Netac               | 1         | 1      | 1%      |
| Micron Technology   | 1         | 1      | 1%      |
| LITEONIT            | 1         | 1      | 1%      |
| LITEON              | 1         | 1      | 1%      |
| Kston               | 1         | 1      | 1%      |
| KIOXIA-EXCERIA      | 1         | 1      | 1%      |
| Intenso             | 1         | 1      | 1%      |
| Intel               | 1         | 1      | 1%      |
| GOODRAM             | 1         | 1      | 1%      |
| Corsair             | 1         | 1      | 1%      |
| BAITITON            | 1         | 1      | 1%      |
| ASMT                | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |
| addlink             | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 85        | 123    | 34.41%  |
| HDD     | 77        | 149    | 31.17%  |
| NVMe    | 67        | 89     | 27.13%  |
| MMC     | 14        | 20     | 5.67%   |
| Unknown | 4         | 5      | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 252    | 56.7%   |
| NVMe | 67        | 89     | 29.91%  |
| SAS  | 16        | 25     | 7.14%   |
| MMC  | 14        | 20     | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 145    | 54.95%  |
| 0.51-1.0   | 45        | 68     | 24.73%  |
| 1.01-2.0   | 20        | 27     | 10.99%  |
| 3.01-4.0   | 9         | 11     | 4.95%   |
| 4.01-10.0  | 6         | 15     | 3.3%    |
| 2.01-3.0   | 2         | 6      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 27.51%  |
| 251-500        | 43        | 22.75%  |
| 501-1000       | 26        | 13.76%  |
| More than 3000 | 17        | 8.99%   |
| 1001-2000      | 15        | 7.94%   |
| 51-100         | 11        | 5.82%   |
| 21-50          | 10        | 5.29%   |
| 1-20           | 8         | 4.23%   |
| 2001-3000      | 5         | 2.65%   |
| Unknown        | 2         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 52        | 27.66%  |
| 21-50          | 30        | 15.96%  |
| 101-250        | 30        | 15.96%  |
| 51-100         | 24        | 12.77%  |
| 501-1000       | 14        | 7.45%   |
| 251-500        | 13        | 6.91%   |
| More than 3000 | 11        | 5.85%   |
| 1001-2000      | 8         | 4.26%   |
| 2001-3000      | 4         | 2.13%   |
| Unknown        | 2         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 3         | 3      | 14.29%  |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 1      | 4.76%   |
| WDC WD1001FALS-40Y6A0 1TB                    | 1         | 1      | 4.76%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 4.76%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 4.76%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 4.76%   |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 4.76%   |
| NGFF 2280 256GB SSD                          | 1         | 1      | 4.76%   |
| Netac SSD 256GB                              | 1         | 1      | 4.76%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 4.76%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 4.76%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 4.76%   |
| DAS TerraMaster 500GB                        | 1         | 3      | 4.76%   |
| China SSD 180GB                              | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 38.1%   |
| Samsung Electronics | 3         | 3      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| OCZ                 | 1         | 1      | 4.76%   |
| NGFF                | 1         | 1      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| DAS                 | 1         | 3      | 4.76%   |
| China               | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 66.67%  |
| WDC     | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |
| DAS     | 1         | 3      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 55%     |
| SSD  | 7         | 7      | 35%     |
| NVMe | 2         | 2      | 10%     |

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
| Works    | 106       | 203    | 51.46%  |
| Detected | 80        | 160    | 38.83%  |
| Malfunc  | 20        | 23     | 9.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 113       | 49.34%  |
| AMD                            | 39        | 17.03%  |
| Samsung Electronics            | 26        | 11.35%  |
| Phison Electronics             | 9         | 3.93%   |
| SanDisk                        | 8         | 3.49%   |
| SK hynix                       | 5         | 2.18%   |
| Kingston Technology Company    | 4         | 1.75%   |
| ASMedia Technology             | 4         | 1.75%   |
| Toshiba America Info Systems   | 3         | 1.31%   |
| Silicon Motion                 | 3         | 1.31%   |
| KIOXIA                         | 3         | 1.31%   |
| Nvidia                         | 2         | 0.87%   |
| ADATA Technology               | 2         | 0.87%   |
| Union Memory (Shenzhen)        | 1         | 0.44%   |
| Solid State Storage Technology | 1         | 0.44%   |
| Realtek Semiconductor          | 1         | 0.44%   |
| Micron Technology              | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.44%   |
| Marvell Technology Group       | 1         | 0.44%   |
| Lenovo                         | 1         | 0.44%   |
| Hewlett-Packard                | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 9.02%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 4.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 3.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 2.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 2.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.88%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.5%    |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.5%    |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.13%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.75%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.75%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.75%   |
| KIOXIA Non-Volatile memory controller                                          | 2         | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 132       | 55.23%  |
| NVMe | 67        | 28.03%  |
| IDE  | 22        | 9.21%   |
| RAID | 18        | 7.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 130       | 71.04%  |
| AMD    | 48        | 26.23%  |
| ARM    | 5         | 2.73%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ARM Processor                               | 4         | 2.19%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.64%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 3         | 1.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.09%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.09%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.09%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.09%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.09%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 2         | 1.09%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2         | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.09%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.09%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2         | 1.09%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.09%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.55%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.55%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 0.55%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1         | 0.55%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.55%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.55%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.55%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.55%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.55%   |
| Intel Pentium CPU B940 @ 2.00GHz            | 1         | 0.55%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.55%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.55%   |
| Intel Core i7-8705G CPU @ 3.10GHz           | 1         | 0.55%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.55%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 0.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 18.03%  |
| Intel Core i7           | 27        | 14.75%  |
| Other                   | 25        | 13.66%  |
| Intel Core i3           | 14        | 7.65%   |
| AMD Ryzen 5             | 14        | 7.65%   |
| Intel Core 2 Duo        | 10        | 5.46%   |
| Intel Celeron           | 10        | 5.46%   |
| Intel Pentium           | 7         | 3.83%   |
| AMD Ryzen 7             | 6         | 3.28%   |
| Intel Xeon              | 5         | 2.73%   |
| AMD Ryzen 9             | 3         | 1.64%   |
| AMD Ryzen 3             | 3         | 1.64%   |
| AMD Athlon II X2        | 3         | 1.64%   |
| AMD A8                  | 3         | 1.64%   |
| AMD A6                  | 3         | 1.64%   |
| AMD A4                  | 3         | 1.64%   |
| Intel Pentium Silver    | 1         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| Intel Pentium 4         | 1         | 0.55%   |
| Intel Core 2 Quad       | 1         | 0.55%   |
| AMD Turion II Neo       | 1         | 0.55%   |
| AMD Turion 64 X2 Mobile | 1         | 0.55%   |
| AMD Turion 64 Mobile    | 1         | 0.55%   |
| AMD Ryzen 7 PRO         | 1         | 0.55%   |
| AMD Phenom II X6        | 1         | 0.55%   |
| AMD FX                  | 1         | 0.55%   |
| AMD E1                  | 1         | 0.55%   |
| AMD E                   | 1         | 0.55%   |
| AMD Athlon X2           | 1         | 0.55%   |
| AMD Athlon II X4        | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 72        | 39.34%  |
| 2       | 65        | 35.52%  |
| 6       | 21        | 11.48%  |
| 8       | 12        | 6.56%   |
| 1       | 4         | 2.19%   |
| 12      | 3         | 1.64%   |
| 10      | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| 16      | 1         | 0.55%   |
| 14      | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 179       | 97.81%  |
| 2       | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 113       | 61.75%  |
| 1       | 68        | 37.16%  |
| Unknown | 2         | 1.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 99.45%  |
| Unknown        | 1         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 41.05%  |
| 0x306a9    | 9         | 4.74%   |
| 0x806c1    | 7         | 3.68%   |
| 0x806ec    | 5         | 2.63%   |
| 0x206a7    | 5         | 2.63%   |
| 0x0a50000c | 5         | 2.63%   |
| 0x806ea    | 4         | 2.11%   |
| 0x506e3    | 4         | 2.11%   |
| 0x306c3    | 4         | 2.11%   |
| 0xa0671    | 3         | 1.58%   |
| 0x906ea    | 3         | 1.58%   |
| 0x906e9    | 3         | 1.58%   |
| 0x806d1    | 3         | 1.58%   |
| 0x40651    | 3         | 1.58%   |
| 0x30678    | 3         | 1.58%   |
| 0x20655    | 3         | 1.58%   |
| 0x1067a    | 3         | 1.58%   |
| 0x08108109 | 3         | 1.58%   |
| 0x706e5    | 2         | 1.05%   |
| 0x706a8    | 2         | 1.05%   |
| 0x6fd      | 2         | 1.05%   |
| 0x506c9    | 2         | 1.05%   |
| 0x10676    | 2         | 1.05%   |
| 0x08608103 | 2         | 1.05%   |
| 0x0800820d | 2         | 1.05%   |
| 0x0700010f | 2         | 1.05%   |
| 0x06001119 | 2         | 1.05%   |
| 0xa0653    | 1         | 0.53%   |
| 0x906ed    | 1         | 0.53%   |
| 0x906c0    | 1         | 0.53%   |
| 0x906a4    | 1         | 0.53%   |
| 0x906a3    | 1         | 0.53%   |
| 0x90672    | 1         | 0.53%   |
| 0x806eb    | 1         | 0.53%   |
| 0x806e9    | 1         | 0.53%   |
| 0x6fb      | 1         | 0.53%   |
| 0x406e3    | 1         | 0.53%   |
| 0x406c4    | 1         | 0.53%   |
| 0x306f2    | 1         | 0.53%   |
| 0x206d7    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 12.97%  |
| IvyBridge        | 15        | 8.11%   |
| Unknown          | 15        | 8.11%   |
| Haswell          | 13        | 7.03%   |
| Icelake          | 9         | 4.86%   |
| TigerLake        | 8         | 4.32%   |
| SandyBridge      | 8         | 4.32%   |
| Penryn           | 8         | 4.32%   |
| Zen+             | 7         | 3.78%   |
| Zen 3            | 7         | 3.78%   |
| Westmere         | 7         | 3.78%   |
| Skylake          | 7         | 3.78%   |
| Silvermont       | 6         | 3.24%   |
| K10              | 6         | 3.24%   |
| Zen 2            | 5         | 2.7%    |
| Zen              | 5         | 2.7%    |
| Goldmont plus    | 4         | 2.16%   |
| Core             | 4         | 2.16%   |
| Piledriver       | 3         | 1.62%   |
| Excavator        | 3         | 1.62%   |
| CometLake        | 3         | 1.62%   |
| Alderlake Hybrid | 3         | 1.62%   |
| Puma             | 2         | 1.08%   |
| Nehalem          | 2         | 1.08%   |
| K8 Hammer        | 2         | 1.08%   |
| Jaguar           | 2         | 1.08%   |
| Goldmont         | 2         | 1.08%   |
| NetBurst         | 1         | 0.54%   |
| K8 & K10 hybrid  | 1         | 0.54%   |
| Bulldozer        | 1         | 0.54%   |
| Broadwell        | 1         | 0.54%   |
| Bobcat           | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 100       | 47.85%  |
| AMD                        | 58        | 27.75%  |
| Nvidia                     | 49        | 23.44%  |
| Matrox Electronics Systems | 1         | 0.48%   |
| ASPEED Technology          | 1         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.9%    |
| Intel HD Graphics 530                                                                    | 4         | 1.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.42%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.42%   |
| AMD Renoir                                                                               | 3         | 1.42%   |
| AMD Lucienne                                                                             | 3         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.95%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.95%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.95%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2         | 0.95%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.95%   |
| Intel HD Graphics 630                                                                    | 2         | 0.95%   |
| Intel HD Graphics 620                                                                    | 2         | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.95%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.47%   |
| Nvidia TU117M                                                                            | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 40.98%  |
| 1 x AMD        | 45        | 24.59%  |
| 1 x Nvidia     | 28        | 15.3%   |
| Intel + Nvidia | 16        | 8.74%   |
| Intel + AMD    | 6         | 3.28%   |
| Other          | 5         | 2.73%   |
| AMD + Nvidia   | 5         | 2.73%   |
| 2 x AMD        | 1         | 0.55%   |
| 1 x Matrox     | 1         | 0.55%   |
| AMD + ASPEED   | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 78.14%  |
| Proprietary | 30        | 16.39%  |
| Unknown     | 10        | 5.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 68.48%  |
| 0.01-0.5   | 18        | 9.78%   |
| 0.51-1.0   | 14        | 7.61%   |
| 1.01-2.0   | 11        | 5.98%   |
| 3.01-4.0   | 6         | 3.26%   |
| 5.01-6.0   | 4         | 2.17%   |
| 7.01-8.0   | 3         | 1.63%   |
| 2.01-3.0   | 1         | 0.54%   |
| 8.01-16.0  | 1         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30        | 14.71%  |
| BOE                     | 20        | 9.8%    |
| Chimei Innolux          | 18        | 8.82%   |
| Goldstar                | 13        | 6.37%   |
| AU Optronics            | 13        | 6.37%   |
| LG Display              | 11        | 5.39%   |
| Dell                    | 11        | 5.39%   |
| Acer                    | 9         | 4.41%   |
| Philips                 | 8         | 3.92%   |
| Hewlett-Packard         | 8         | 3.92%   |
| Apple                   | 6         | 2.94%   |
| Iiyama                  | 5         | 2.45%   |
| BenQ                    | 5         | 2.45%   |
| Lenovo                  | 4         | 1.96%   |
| Chi Mei Optoelectronics | 4         | 1.96%   |
| Ancor Communications    | 4         | 1.96%   |
| Sony                    | 3         | 1.47%   |
| PANDA                   | 3         | 1.47%   |
| AOC                     | 3         | 1.47%   |
| Vizio                   | 2         | 0.98%   |
| ViewSonic               | 2         | 0.98%   |
| Sharp                   | 2         | 0.98%   |
| Westinghouse            | 1         | 0.49%   |
| VMO                     | 1         | 0.49%   |
| Vita                    | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |
| Toshiba                 | 1         | 0.49%   |
| Sceptre Tech            | 1         | 0.49%   |
| Quanta Display          | 1         | 0.49%   |
| Packard Bell            | 1         | 0.49%   |
| NEC Computers           | 1         | 0.49%   |
| Medion                  | 1         | 0.49%   |
| LGD                     | 1         | 0.49%   |
| LG Philips              | 1         | 0.49%   |
| Insignia                | 1         | 0.49%   |
| Idek Iiyama             | 1         | 0.49%   |
| IBM                     | 1         | 0.49%   |
| Hitachi                 | 1         | 0.49%   |
| HannStar                | 1         | 0.49%   |
| Gateway                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 2         | 0.97%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.97%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 2         | 0.97%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.97%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 2         | 0.97%   |
| Acer K272HL H ACR087E 1920x1080 597x336mm 27.0-inch                  | 2         | 0.97%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                   | 2         | 0.97%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch         | 1         | 0.49%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch            | 1         | 0.49%   |
| Vizio M470NV VIZ0063 1920x1080 1040x585mm 47.0-inch                  | 1         | 0.49%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                 | 1         | 0.49%   |
| Vita LCD Monitor VIT0780 1920x1080                                   | 1         | 0.49%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch        | 1         | 0.49%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch        | 1         | 0.49%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1         | 0.49%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch             | 1         | 0.49%   |
| Sony LCD Monitor TV 3840x1080                                        | 1         | 0.49%   |
| Sony LCD Monitor TV                                                  | 1         | 0.49%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch              | 1         | 0.49%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 0.49%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch               | 1         | 0.49%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1         | 0.49%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch  | 1         | 0.49%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch  | 1         | 0.49%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 0.49%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch   | 1         | 0.49%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch    | 1         | 0.49%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch    | 1         | 0.49%   |
| Samsung Electronics S24E650 SAM0CB9 1920x1080 521x293mm 23.5-inch    | 1         | 0.49%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 1         | 0.49%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch    | 1         | 0.49%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch    | 1         | 0.49%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch    | 1         | 0.49%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1         | 0.49%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch    | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 47.85%  |
| 1366x768 (WXGA)    | 31        | 16.67%  |
| 2560x1440 (QHD)    | 11        | 5.91%   |
| 3840x2160 (4K)     | 9         | 4.84%   |
| 1440x900 (WXGA+)   | 8         | 4.3%    |
| 1680x1050 (WSXGA+) | 6         | 3.23%   |
| 1280x800 (WXGA)    | 5         | 2.69%   |
| 3440x1440          | 3         | 1.61%   |
| 2560x1600          | 3         | 1.61%   |
| 1280x1024 (SXGA)   | 3         | 1.61%   |
| 3840x1080          | 2         | 1.08%   |
| 2160x1440          | 2         | 1.08%   |
| 1920x1280          | 2         | 1.08%   |
| 1920x1200 (WUXGA)  | 2         | 1.08%   |
| 1600x900 (HD+)     | 2         | 1.08%   |
| 1360x768           | 2         | 1.08%   |
| Unknown            | 2         | 1.08%   |
| 3840x2400          | 1         | 0.54%   |
| 2880x1620          | 1         | 0.54%   |
| 2560x1080          | 1         | 0.54%   |
| 1280x720 (HD)      | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 23.5%   |
| 27      | 23        | 11.5%   |
| 24      | 16        | 8%      |
| 23      | 16        | 8%      |
| 21      | 15        | 7.5%    |
| 13      | 15        | 7.5%    |
| 17      | 14        | 7%      |
| 14      | 12        | 6%      |
| 31      | 10        | 5%      |
| Unknown | 5         | 2.5%    |
| 34      | 4         | 2%      |
| 19      | 4         | 2%      |
| 54      | 3         | 1.5%    |
| 22      | 3         | 1.5%    |
| 12      | 3         | 1.5%    |
| 18      | 2         | 1%      |
| 11      | 2         | 1%      |
| 84      | 1         | 0.5%    |
| 74      | 1         | 0.5%    |
| 40      | 1         | 0.5%    |
| 28      | 1         | 0.5%    |
| 25      | 1         | 0.5%    |
| 16      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 73        | 36.87%  |
| 501-600     | 52        | 26.26%  |
| 401-500     | 24        | 12.12%  |
| 601-700     | 13        | 6.57%   |
| 201-300     | 11        | 5.56%   |
| 351-400     | 10        | 5.05%   |
| Unknown     | 5         | 2.53%   |
| 701-800     | 4         | 2.02%   |
| 1001-1500   | 3         | 1.52%   |
| 1501-2000   | 2         | 1.01%   |
| 801-900     | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 129       | 75.44%  |
| 16/10   | 27        | 15.79%  |
| 5/4     | 4         | 2.34%   |
| 3/2     | 4         | 2.34%   |
| 21/9    | 4         | 2.34%   |
| Unknown | 3         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 22.84%  |
| 201-250        | 38        | 19.29%  |
| 81-90          | 23        | 11.68%  |
| 301-350        | 23        | 11.68%  |
| 351-500        | 15        | 7.61%   |
| 151-200        | 8         | 4.06%   |
| 121-130        | 8         | 4.06%   |
| 251-300        | 6         | 3.05%   |
| 141-150        | 6         | 3.05%   |
| More than 1000 | 5         | 2.54%   |
| Unknown        | 5         | 2.54%   |
| 71-80          | 4         | 2.03%   |
| 61-70          | 3         | 1.52%   |
| 51-60          | 2         | 1.02%   |
| 131-140        | 2         | 1.02%   |
| 91-100         | 2         | 1.02%   |
| 111-120        | 1         | 0.51%   |
| 501-1000       | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 70        | 37.04%  |
| 101-120       | 49        | 25.93%  |
| 121-160       | 46        | 24.34%  |
| 161-240       | 13        | 6.88%   |
| 1-50          | 5         | 2.65%   |
| Unknown       | 5         | 2.65%   |
| More than 240 | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 137       | 74.46%  |
| 2     | 37        | 20.11%  |
| 0     | 7         | 3.8%    |
| 3     | 2         | 1.09%   |
| 4     | 1         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 101       | 38.7%   |
| Intel                             | 92        | 35.25%  |
| Broadcom                          | 18        | 6.9%    |
| Qualcomm Atheros                  | 17        | 6.51%   |
| Ralink                            | 5         | 1.92%   |
| TP-Link                           | 3         | 1.15%   |
| Marvell Technology Group          | 3         | 1.15%   |
| Broadcom Limited                  | 3         | 1.15%   |
| ASIX Electronics                  | 3         | 1.15%   |
| Qualcomm Atheros Communications   | 2         | 0.77%   |
| Nvidia                            | 2         | 0.77%   |
| MediaTek                          | 2         | 0.77%   |
| Ericsson Business Mobile Networks | 2         | 0.77%   |
| Raspberry Pi                      | 1         | 0.38%   |
| Quectel Wireless Solutions        | 1         | 0.38%   |
| NetGear                           | 1         | 0.38%   |
| Microchip Technology              | 1         | 0.38%   |
| DisplayLink                       | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |
| AVM                               | 1         | 0.38%   |
| ASUSTek Computer                  | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 18.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.52%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.21%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.58%   |
| Realtek 802.11ac NIC                                              | 5         | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.58%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.26%   |
| Intel Wireless 7265                                               | 4         | 1.26%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.26%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.26%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.95%   |
| Intel Wireless 3165                                               | 3         | 0.95%   |
| Intel Wireless 3160                                               | 3         | 0.95%   |
| Intel WiFi Link 5100                                              | 3         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.95%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.95%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.95%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 47.74%  |
| Realtek Semiconductor           | 39        | 25.16%  |
| Qualcomm Atheros                | 14        | 9.03%   |
| Broadcom                        | 9         | 5.81%   |
| Ralink                          | 5         | 3.23%   |
| TP-Link                         | 3         | 1.94%   |
| Qualcomm Atheros Communications | 2         | 1.29%   |
| MediaTek                        | 2         | 1.29%   |
| Broadcom Limited                | 2         | 1.29%   |
| Quectel Wireless Solutions      | 1         | 0.65%   |
| NetGear                         | 1         | 0.65%   |
| D-Link System                   | 1         | 0.65%   |
| AVM                             | 1         | 0.65%   |
| ASUSTek Computer                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 5.13%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.49%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.21%   |
| Realtek 802.11ac NIC                                                    | 5         | 3.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 3.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.56%   |
| Intel Wireless 7265                                                     | 4         | 2.56%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.92%   |
| Intel Wireless 3165                                                     | 3         | 1.92%   |
| Intel Wireless 3160                                                     | 3         | 1.92%   |
| Intel WiFi Link 5100                                                    | 3         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.92%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.92%   |
| TP-Link 802.11ac NIC                                                    | 2         | 1.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.28%   |
| Intel Wireless 7260                                                     | 2         | 1.28%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.28%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.28%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.28%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 80        | 52.29%  |
| Intel                    | 47        | 30.72%  |
| Broadcom                 | 11        | 7.19%   |
| Qualcomm Atheros         | 4         | 2.61%   |
| Marvell Technology Group | 3         | 1.96%   |
| ASIX Electronics         | 3         | 1.96%   |
| Nvidia                   | 2         | 1.31%   |
| Microchip Technology     | 1         | 0.65%   |
| DisplayLink              | 1         | 0.65%   |
| Broadcom Limited         | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 60        | 37.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 11        | 6.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 3.16%   |
| Intel Ethernet Controller I225-V                                               | 5         | 3.16%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.27%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.27%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.27%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.27%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.63%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.63%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.63%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.63%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.63%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.63%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 149       | 49.83%  |
| WiFi     | 147       | 49.16%  |
| Modem    | 3         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 56.54%  |
| Ethernet | 83        | 43.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 102       | 55.74%  |
| 1     | 69        | 37.7%   |
| 0     | 6         | 3.28%   |
| 3     | 4         | 2.19%   |
| 4     | 2         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 124       | 67.39%  |
| Yes  | 60        | 32.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 46.67%  |
| Realtek Semiconductor           | 20        | 16.67%  |
| Broadcom                        | 11        | 9.17%   |
| IMC Networks                    | 7         | 5.83%   |
| Apple                           | 6         | 5%      |
| Cambridge Silicon Radio         | 5         | 4.17%   |
| Ralink                          | 3         | 2.5%    |
| Qualcomm Atheros Communications | 2         | 1.67%   |
| Foxconn / Hon Hai               | 2         | 1.67%   |
| Toshiba                         | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| Lite-On Technology              | 1         | 0.83%   |
| Integrated System Solution      | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Foxconn International           | 1         | 0.83%   |
| Belkin Components               | 1         | 0.83%   |
| ASUSTek Computer                | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 18        | 15%     |
| Intel Bluetooth wireless interface                                                  | 16        | 13.33%  |
| Realtek Bluetooth Radio                                                             | 15        | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.33%   |
| Intel AX210 Bluetooth                                                               | 4         | 3.33%   |
| Intel AX200 Bluetooth                                                               | 4         | 3.33%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.5%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.67%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.67%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.67%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.67%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.67%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.83%   |
| MediaTek Wireless_Device                                                            | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.83%   |
| Intel Bluetooth Device                                                              | 1         | 0.83%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.83%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.83%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.83%   |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.83%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.83%   |
| Belkin Components F8T013 Bluetooth Adapter                                          | 1         | 0.83%   |
| ASUS Bluetooth Radio                                                                | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 126       | 49.8%   |
| AMD                     | 58        | 22.92%  |
| Nvidia                  | 40        | 15.81%  |
| C-Media Electronics     | 7         | 2.77%   |
| ASUSTek Computer        | 4         | 1.58%   |
| Generalplus Technology  | 3         | 1.19%   |
| Logitech                | 2         | 0.79%   |
| JMTek                   | 2         | 0.79%   |
| TerraTec Electronic     | 1         | 0.4%    |
| Meizu                   | 1         | 0.4%    |
| Kingston Technology     | 1         | 0.4%    |
| GN Netcom               | 1         | 0.4%    |
| DSEA A/S                | 1         | 0.4%    |
| Creative Technology     | 1         | 0.4%    |
| Corsair                 | 1         | 0.4%    |
| Cambridge Silicon Radio | 1         | 0.4%    |
| BlackWeb                | 1         | 0.4%    |
| Anlya.cn                | 1         | 0.4%    |
| Alesis                  | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 7.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 5.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 2.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 2.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.35%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.68%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.34%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.34%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 4         | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.34%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 1.01%   |
| Generalplus Technology USB Audio Device                                    | 3         | 1.01%   |
| ASUSTek Computer USB Audio                                                 | 3         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 19.31%  |
| SK hynix            | 26        | 17.93%  |
| Kingston            | 18        | 12.41%  |
| Unknown             | 16        | 11.03%  |
| Micron Technology   | 14        | 9.66%   |
| Crucial             | 14        | 9.66%   |
| Corsair             | 10        | 6.9%    |
| Unknown (ABCD)      | 4         | 2.76%   |
| G.Skill             | 4         | 2.76%   |
| Nanya Technology    | 3         | 2.07%   |
| Ramaxel Technology  | 2         | 1.38%   |
| Unifosa             | 1         | 0.69%   |
| Hewlett-Packard     | 1         | 0.69%   |
| HBS                 | 1         | 0.69%   |
| GOODRAM             | 1         | 0.69%   |
| A-DATA Technology   | 1         | 0.69%   |
| Unknown             | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 2.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.91%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.27%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 2         | 1.27%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.64%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.64%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.64%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.64%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.64%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 0.64%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.64%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.64%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.64%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.64%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 0.64%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 1         | 0.64%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1333MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.64%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 49.61%  |
| DDR3    | 42        | 33.07%  |
| DDR2    | 8         | 6.3%    |
| LPDDR4  | 7         | 5.51%   |
| DDR5    | 2         | 1.57%   |
| Unknown | 2         | 1.57%   |
| SDRAM   | 1         | 0.79%   |
| LPDDR3  | 1         | 0.79%   |
| DDR     | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 80        | 61.07%  |
| DIMM         | 40        | 30.53%  |
| Row Of Chips | 9         | 6.87%   |
| Chip         | 1         | 0.76%   |
| Unknown      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 51        | 36.17%  |
| 4096  | 41        | 29.08%  |
| 16384 | 26        | 18.44%  |
| 2048  | 15        | 10.64%  |
| 32768 | 4         | 2.84%   |
| 1024  | 4         | 2.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 27        | 19.85%  |
| 3200    | 25        | 18.38%  |
| 2667    | 18        | 13.24%  |
| 2400    | 15        | 11.03%  |
| 1333    | 10        | 7.35%   |
| Unknown | 5         | 3.68%   |
| 2133    | 3         | 2.21%   |
| 1334    | 3         | 2.21%   |
| 667     | 3         | 2.21%   |
| 4800    | 2         | 1.47%   |
| 4267    | 2         | 1.47%   |
| 3600    | 2         | 1.47%   |
| 3466    | 2         | 1.47%   |
| 3266    | 2         | 1.47%   |
| 1067    | 2         | 1.47%   |
| 800     | 2         | 1.47%   |
| 4000    | 1         | 0.74%   |
| 3400    | 1         | 0.74%   |
| 3333    | 1         | 0.74%   |
| 3100    | 1         | 0.74%   |
| 2800    | 1         | 0.74%   |
| 2747    | 1         | 0.74%   |
| 2666    | 1         | 0.74%   |
| 2048    | 1         | 0.74%   |
| 1867    | 1         | 0.74%   |
| 1866    | 1         | 0.74%   |
| 1648    | 1         | 0.74%   |
| 1066    | 1         | 0.74%   |
| 975     | 1         | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dymo-CoStar         | 2         | 25%     |
| Brother Industries  | 2         | 25%     |
| Seiko Epson         | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Hewlett-Packard     | 1         | 12.5%   |
| Graphtec America    | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series        | 1         | 12.5%   |
| Samsung M2070 Series              | 1         | 12.5%   |
| HP DeskJet 2700 series            | 1         | 12.5%   |
| Graphtec America Graphtec Printer | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 450       | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 310       | 1         | 12.5%   |
| Brother HL-3140CW series          | 1         | 12.5%   |
| Brother DCP-L5500DN series        | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 2         | 50%     |
| Siemens Information and Communication Products | 1         | 25%     |
| Hewlett-Packard                                | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 25%     |
| HP ScanJet G4010                                                                | 1         | 25%     |
| Canon CanoScan LiDE 120                                                         | 1         | 25%     |
| Canon CanoScan LiDE 110                                                         | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 23.89%  |
| Realtek Semiconductor                  | 14        | 12.39%  |
| Logitech                               | 8         | 7.08%   |
| IMC Networks                           | 8         | 7.08%   |
| Microdia                               | 7         | 6.19%   |
| Quanta                                 | 6         | 5.31%   |
| Apple                                  | 6         | 5.31%   |
| Syntek                                 | 5         | 4.42%   |
| Suyin                                  | 4         | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.54%   |
| Acer                                   | 4         | 3.54%   |
| Sunplus Innovation Technology          | 2         | 1.77%   |
| Ricoh                                  | 2         | 1.77%   |
| Razer USA                              | 2         | 1.77%   |
| Luxvisions Innotech Limited            | 2         | 1.77%   |
| Lite-On Technology                     | 2         | 1.77%   |
| Lenovo                                 | 2         | 1.77%   |
| ARC International                      | 2         | 1.77%   |
| Z-Star Microelectronics                | 1         | 0.88%   |
| U0AS01A-0                              | 1         | 0.88%   |
| Sonix Technology                       | 1         | 0.88%   |
| Microsoft                              | 1         | 0.88%   |
| Generalplus Technology                 | 1         | 0.88%   |
| Alcor Micro                            | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 4         | 3.54%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 3.54%   |
| Chicony HP HD Camera                          | 4         | 3.54%   |
| Realtek USB Camera                            | 3         | 2.65%   |
| Realtek Integrated_Webcam_HD                  | 3         | 2.65%   |
| Microdia Webcam Vitade AF                     | 3         | 2.65%   |
| Chicony integrated camera                     | 3         | 2.65%   |
| Apple Built-in iSight                         | 3         | 2.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.77%   |
| Realtek MTD camera                            | 2         | 1.77%   |
| Realtek Integrated Webcam HD                  | 2         | 1.77%   |
| Razer USA Razer Kiyo                          | 2         | 1.77%   |
| Quanta HD User Facing                         | 2         | 1.77%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.77%   |
| Logitech Webcam C270                          | 2         | 1.77%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.77%   |
| IMC Networks Integrated Camera                | 2         | 1.77%   |
| Chicony HP Webcam                             | 2         | 1.77%   |
| Chicony HP Truevision HD camera               | 2         | 1.77%   |
| Chicony HD Webcam                             | 2         | 1.77%   |
| Chicony HD User Facing                        | 2         | 1.77%   |
| ARC International Camera                      | 2         | 1.77%   |
| Acer Integrated Camera                        | 2         | 1.77%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA          | 1         | 0.88%   |
| U0AS01A-0 U0AS01A-0                           | 1         | 0.88%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.88%   |
| Suyin USB 2.0 Camera                          | 1         | 0.88%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.88%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.88%   |
| Sunplus HP Truevision HD                      | 1         | 0.88%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 0.88%   |
| Ricoh Sony Vaio Integrated Webcam             | 1         | 0.88%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 0.88%   |
| Realtek NexiGo N960E FHD Webcam               | 1         | 0.88%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 0.88%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 0.88%   |
| Realtek HP 1.0MP High Definition Webcam       | 1         | 0.88%   |
| Quanta ov9734_techfront_camera                | 1         | 0.88%   |
| Quanta HP Webcam-101                          | 1         | 0.88%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 21.05%  |
| Upek                       | 4         | 21.05%  |
| Synaptics                  | 4         | 21.05%  |
| Shenzhen Goodix Technology | 4         | 21.05%  |
| Elan Microelectronics      | 2         | 10.53%  |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 21.05%  |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 21.05%  |
| Elan ELAN:ARM-M4                                                           | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics  WBDI                                                            | 1         | 5.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 5.26%   |
| AuthenTec AES1600                                                          | 1         | 5.26%   |
| Unknown                                                                    | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 50%     |
| Alcor Micro           | 4         | 25%     |
| Upek                  | 1         | 6.25%   |
| SCM Microsystems      | 1         | 6.25%   |
| O2 Micro              | 1         | 6.25%   |
| Advanced Card Systems | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 5         | 31.25%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.25%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom 5880                                                                | 1         | 6.25%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 133       | 71.89%  |
| 1     | 39        | 21.08%  |
| 2     | 9         | 4.86%   |
| 3     | 4         | 2.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 19        | 29.69%  |
| Chipcard              | 16        | 25%     |
| Graphics card         | 9         | 14.06%  |
| Net/wireless          | 6         | 9.38%   |
| Bluetooth             | 5         | 7.81%   |
| Camera                | 3         | 4.69%   |
| Unassigned class      | 1         | 1.56%   |
| Network               | 1         | 1.56%   |
| Multimedia controller | 1         | 1.56%   |
| Flash memory          | 1         | 1.56%   |
| Dvb card              | 1         | 1.56%   |
| Card reader           | 1         | 1.56%   |

